---
title: "Procédure : bloquer des articles en stock pour des ventes ou des achats"
description: "Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], un article peut être marqué comme bloqué pour les ventes, bloqué pour les achats ou bloqué pour toutes les finalités."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 7e2559aca6a8b73bcd11ea6251dee13b30f7267b
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-block-inventory-items-for-sales-or-purchases"></a>Procédure : bloquer des articles en stock pour des ventes ou des achats
Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], un article peut être marqué comme bloqué pour les ventes, bloqué pour les achats ou bloqué pour toutes les finalités.  

Le tableau suivant illustre ce qui se passe lorsque des articles sont bloqués.  

|Article marqué comme|Résultat|  
|--------------------|------------|  
|**Bloqué à la vente**|Vous ne pouvez pas utiliser l'article dans un document vente ou dans une feuille article vente.|  
|**Bloqué à l'achat**|Vous ne pouvez pas utiliser l'article dans un document achat, dans une feuille article achat ou dans des processus planning achat.|  
|**Bloqué**|Vous ne pouvez pas utiliser l'article pour une quelconque transaction article. Pour plus d'informations sur le blocage d'un article pour toutes les finalités, voir Fiche article.|  

## <a name="to-block-inventory-items-for-sales"></a>Pour bloquer des articles stock pour les ventes  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Articles**, puis sélectionnez le lien associé.  
2.  Sélectionnez l'article que vous souhaitez bloquer, puis choisissez l'action **Modifier**.  
3.  Pour bloquer l'article sélectionné pour les transactions ventes, sur le raccourci **Facturation**, sélectionnez la case à cocher **Vente bloquée**.  
4.  Cliquez sur le bouton **OK**.  

## <a name="to-block-inventory-items-for-purchase"></a>Pour bloquer des articles stock pour les achats  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Articles**, puis sélectionnez le lien associé.  
2.  Sélectionnez l'article que vous souhaitez bloquer, puis choisissez l'action **Modifier**.  
3.  Pour bloquer un article pour les transactions achats, sur le raccourci **Réapprovisionnement**, sélectionnez la case à cocher **Achat bloqué**.  
4.  Cliquez sur le bouton **OK**.  

Vous recevrez un message d'erreur si vous tentez d'effectuer les opérations suivantes :  

- Entrer des lignes vente et des lignes achat dans des documents vente et des documents achat pour des articles bloqués. Pour plus d'informations, consultez les tables Ligne vente et Ligne achat.  
- Créer des lignes dans une feuille article pour des articles bloqués. Pour plus d'informations, consultez la fenêtre Feuille article.  
- Valider des transactions article pour des articles bloqués.  

## <a name="see-also"></a>Voir aussi  
 [Gestion des stocks suisse](swiss-inventory-management.md)   
 [Procédure : bloquer une expédition pour des stocks négatifs](how-to-block-shipment-for-negative-inventory.md)   
 [Procédure : copier des articles existants vers de nouveaux articles](how-to-copy-existing-items-to-new-items.md)   
 [Procédure : désactiver la traçabilité coût article](how-to-deactivate-item-cost-tracking.md)

