---
title: Description des processus Assembler pour commande et Assembler pour stock
description: "Les éléments d'assemblage peuvent être fournis soit en les assemblant lors de leur commande ou en les assemblant pour les conserver en stock jusqu'à ce qu'ils soient nécessaires pour une commande vente."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b1c768e738191b3ae378ffdaa80a10c885cc4ee6
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="understanding-assemble-to-order-and-assemble-to-stock"></a>Description des processus Assembler pour commande et Assembler pour stock
Les éléments d'assemblage peuvent être fournis dans le cadre des deux processus suivants :  

-   Assembler pour commande.  
-   Assembler pour stock.  

## <a name="assemble-to-order"></a>Assembler pour commande  
En règle générale, vous utilisez *l'assemblage pour commande* pour les articles que vous ne souhaitez pas stocker parce que vous comptez les personnaliser en fonction des demandes des clients ou parce que vous voulez réduire les frais de transport associés au stock. La fonctionnalité de prise en charge inclut les points suivants :  

-   Possibilité de personnaliser les éléments d'assemblage lors d'une prise de commande vente.  
-   Aperçu de la disponibilité de l'élément d'assemblage et de ses composants.  
-   Possibilité de réserver des composants d'assemblage immédiatement afin de garantir le traitement de la commande.  
-   Fonction permettant de déterminer la rentabilité de la commande personnalisée par le calcul multi-niveau du prix et du coût.  
-   Intégration à l'entrepôt pour faciliter l'assemblage et l'expédition.  
-   Possibilité d'assemblage pour commande au moment de la création d'un devis vente ou d'une commande ouverte vente.  
-   Possibilité de combiner les quantités de stock et les quantités à assembler pour commande.  

Dans le processus d'assemblage pour commande, l'article est assemblé en réponse à une commande vente et via un lien un-un entre l'ordre d'assemblage et la commande vente.  

Lorsque vous entrez un article à assembler pour commande sur une ligne vente, un ordre d'assemblage est automatiquement créé avec un en-tête basé sur la ligne vente et avec des lignes qui reposent sur la nomenclature d'assemblage de l'article multipliée par la quantité de commande. Vous pouvez utiliser la fenêtre **Lignes Assembler pour commande** pour visualiser les lignes d'ordre d'assemblage liées afin de vous aider dans la personnalisation de l'élément d'assemblage et l'établissement d'une date de livraison qui est basée sur les informations de disponibilité des composants. Pour plus d'informations sur le paramétrage des éléments d'assemblage, voir [Procédure : Vente d'articles à assembler pour commande](assembly-how-to-sell-items-assembled-to-order.md).  

> [!NOTE]  
>  Bien que cette tâche ne fasse pas partie du processus par défaut, vous pouvez vendre des quantités de stock avec les quantités à assembler pour commande. Pour plus d’informations, reportez-vous à la section [Procédure : Vente d'articles en stock dans des flux à assembler pour commande](assembly-how-to-sell-inventory-items-in-assemble-to-order-flows.md).  

 Pour activer ce processus, il faut que le champ **Stratégie d'assemblage** de la fiche article contienne la valeur **Assembler pour commande**.  

## <a name="assemble-to-stock"></a>Assembler pour stock  
 En règle générale, vous utilisez *l'assemblage pour stock* pour les articles que vous souhaitez assembler avant les ventes (par exemple, pour préparer des articles pour une campagne de kit et les conserver dans le stock jusqu'à ce qu'ils soient commandés). Ces articles sont généralement des articles standard tels que les kits emballés qui ne peuvent pas être personnalisés en fonction des demandes des clients.  

 Dans le processus d'assemblage pour stock, l'article est assemblé sans demande vente immédiate puis il est stocké dans l'entrepôt en tant qu'article de stock en vue d'une vente ultérieure ou d'une consommation en tant que produit semi-fini. Pour plus d'informations, voir [Procédure : assembler des articles](assembly-how-to-assemble-items.md). À ce stade, l'article est prélevé et traité en tant qu'article unique. Il est considéré comme un article fini.  

 Lorsque vous entrez un article à assembler pour stock sur une ligne vente, la ligne ressemble à tout autre article vendu à partir du stock. Par exemple, la disponibilité est vérifiée uniquement pour l'élément d'assemblage.  

> [!NOTE]  
>  Bien que cette tâche ne fasse pas partie du processus par défaut, vous pouvez assembler un article pour commande même s'il est configuré pour être assemblé pour stock. Pour plus d’informations, reportez-vous à la section [Procédure : vente simultanée d'articles à assembler pour commande et d'articles en stock](assembly-how-to-sell-assemble-to-order-items-and-inventory-items-together.md).  

 Pour activer ce processus, il faut que le champ **Stratégie d'assemblage** de la fiche article contienne la valeur **Assembler pour stock**.  

## <a name="combination-scenarios"></a>Scénarios de combinaison  
 Un principe général de la gestion nomenclature d'assemblage stipule qu'une fois regroupées sur une ligne commande vente, les quantités à assembler pour commande doivent être expédiées avant les quantités de stock.  

 Si un ordre d'assemblage est lié à une ligne commande vente, la valeur du champ **Qté vers Assembler pour commande** sur la ligne commande vente est copiée dans le champ **Quantité à assembler** via le champ **Quantité** dans l'en\-tête d'ordre d'assemblage. Pour plus d'informations sur le paramétrage des éléments d'assemblage, voir [Procédure : Vente d'articles à assembler pour commande](assembly-how-to-sell-items-assembled-to-order.md).  

 En outre, la valeur du champ **Quantité à assembler** est liée au champ **Qté à expédier** sur la ligne commande vente, et cette relation gère l'expédition des quantités à assembler pour commande, partiellement et entièrement. C'est le cas lorsque toute la quantité de la ligne vente est assemblée pour commande et, dans les scénarios de combinaison, lorsqu'une partie de la quantité de la ligne vente est assemblée pour commande et qu'une autre partie est expédiée à partir du stock. Toutefois, dans le scénario de combinaison, vous disposez d'une flexibilité supplémentaire lors de l'expédition partielle, car vous pouvez modifier le champ **Quantité à assembler** dans des règles prédéfinies afin de spécifier le nombre d'unités à expédier partiellement à partir du stock et le nombre à expédier partiellement lors de l'assemblage pour commande.  

 Si toute la quantité de la ligne vente doit être assemblée en vue de la commande et de l’expédition, la valeur du champ **Qté. à expédier** est copiée dans le champ **Quantité à assembler** de l’ordre d’assemblage lié lorsque vous modifiez la quantité à expédier. Ceci assure que la quantité expédiée est entièrement approvisionnée par la quantité à assembler pour commande.  

 Toutefois, dans les scénarios de combinaison, la valeur du champ **Qté. à expédier** n'est pas copiée dans le champ **Quantité à assembler** de l'en\-tête d'ordre d'assemblage. C'est une valeur par défaut qui est insérée dans le champ **Quantité à assembler**. Cette valeur est calculée à partir du champ **Qté. à expédier** en fonction d'une règle prédéfinie qui garantit l'expédition prioritaire des quantités à assembler pour commande.  

 Si vous voulez utiliser une valeur autre que celle par défaut, par exemple, parce que vous souhaitez uniquement assembler une quantité supérieure ou inférieure à celle indiquée dans le champ **Qté. à expédier**, vous pouvez modifier le champ **Quantité à assembler**, mais uniquement dans le cadre de règles prédéfinies, comme illustré ci\-dessous.  

 Par exemple, la raison pour laquelle vous voudriez modifier la quantité à assembler peut être liée au souhait de valider partiellement l'expédition des quantités en stock avant que le résultat d'assemblage ne puisse être expédié.  

 Ce qui suit explique les règles qui définissent les valeurs minimale et maximale que vous pouvez entrer manuellement dans le champ **Quantité à assembler** pour spécifier une valeur autre que celle par défaut dans un scénario de combinaison. Le tableau affiche un scénario de combinaison dont le champ **Qté. à expédier** de la ligne commande vente liée passe de 7 à 4 ; le champ **Quantité à assembler** prend donc par défaut la valeur 4.  

||Ligne commande vente|En-tête d'ordre d'assemblage|  
|-|----------------------|---------------------------|  
||**Quantité**|**Qté à expédier**|**Qté vers Assembler pour commande**|**Qté expédiée**|**Quantité**|**Quantité à assembler**|**Quantité assemblée**|**Quantité restante**|  
|Initial|10|7|7|0|7|7|0|7|  
|Activer||4||||4 (valeur insérée par défaut)|||  

 D'après la situation présentée ci\-dessus, vous ne pouvez modifier que le champ **Quantité à assembler** comme suit :  

-   La quantité minimum que vous pouvez saisir est 1. En effet, vous devez assembler au moins une unité pour pouvoir vendre les quatre, en supposant que les trois autres soient disponibles dans le stock.  
-   La quantité maximum que vous pouvez saisir est 4. Cela permet de s'assurer que vous n'assemblez pas une quantité d'articles assemblés pour commande supérieure à celle requise pour la vente.  

## <a name="see-also"></a>Voir aussi  
[Gestion des assemblages](assembly-assemble-items.md)  
[Procédure : utiliser les nomenclatures](inventory-how-work-BOMs.md)  
[STOCKS ET EN-COURS](inventory-manage-inventory.md)  
[Détails de conception : gestion d'entrepôt](design-details-warehouse-management.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

