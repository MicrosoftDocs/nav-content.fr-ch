---
title: "Créer une facture vente projet pour facturer un projet"
description: "Décrit comment facturer des clients pour les coûts au fur et à mesure de l'avancée du projet."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project invoice
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 74b9209216f6e62dfc9519b288adca785cdb8100
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-invoice-jobs"></a>Procédure : Facturer des projets
Au cours du projet, les coûts provenant de l'utilisation de ressources, de matières, et d'achats associés au projet peuvent s'accumuler. Au fur et à mesure de la progression du projet, ces transactions sont validées dans la feuille projet. Il est important que tous les coûts enregistrés dans la feuille projet avant de facturer le client.

Vous pouvez facturer l'ensemble du projet à partir de la fenêtre **Lignes tâche projet** ou facturer uniquement les lignes facturables sélectionnées dans la fenêtre **Lignes planning**. La facturation peut avoir lieu une fois le projet terminé ou à certains intervalles au cours du projet sur la base d'une prévision de facture.

> [!NOTE]  
>   Si vous sélectionnez **Facturable** dans le champ **Type ligne projet** dans les documents d'achat pour les achats associés au projet, les lignes planning projet prêtes pour facturation sont créées. Pour en savoir plus, reportez-vous à [Procédure : Gérer des fournitures d'un projet](projects-how-manage-project-supplies.md).

## <a name="to-create-and-post-a-job-sales-invoice"></a>Pour créer et valider une facture vente projet
Vous pouvez créer une facture pour un projet ou pour une ou plusieurs tâches projet pour un client lorsque le travail à facturer est terminé ou lorsque la date de facturation dépendante d'une prévision de facture est atteinte.

Dans la fenêtre **Projets**, vous pouvez facturer un client en sélectionnant le projet, puis en cliquant sur **Créer une facture vente projet**. La procédure suivante explique comment utiliser un traitement par lots pour facturer plusieurs projets.  

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Projet Créer facture vente**, puis sélectionnez le lien connexe.  
2. Renseignez les champs selon vos besoins. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Définissez des filtres si vous souhaitez limiter le nombre de projets que le traitement par lots va traiter.
4. Pour créer les factures, cliquez sur le bouton **OK**.  

## <a name="to-create-multiple-job-sales-invoices-from-job-planning-lines"></a>Pour créer plusieurs factures vente projet à partir de lignes planning projet
Vous pouvez créer une facture à partir des lignes planning projet et indiquer à ce moment-là la quantité de l'article, la ressource ou le compte général sur lequel vous souhaitez facturer.

1. Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Projets**, puis choisissez le lien associé.
2. Ouvrez le projet approprié.
3. Sélectionnez une tâche projet pour laquelle le champ **Type tâche projet** contient **Validation** puis, cliquez sur **Lignes planning projet**.  
4. Dans une ligne planning projet, dans le champ **Qté à transférer à facturer**, saisissez la quantité de l'article, la ressource, le type de compte général sur lequel vous souhaitez facturer.  
5. Cliquez sur **Créer facture vente**.
6. Dans la fenêtre **Projet Créer facture vente**, saisissez la date de validation et si vous souhaitez créer une facture ou ajouter cette facture à une facture existante.
7. Cliquez sur le bouton **OK**.  

    Dans la ligne planning projet, dans le champ **Qté à transférer à facturer**, vous pouvez visualiser la quantité.
8. Dans la fenêtre **Lignes planning projet**, cliquez sur **Avoirs/Factures vente**.

    La fenêtre **Facture vente** s'ouvre et affiche la quantité que vous avez transférée à la facture.  
9. Apportez les modifications supplémentaires, puis cliquez sur **Valider**.

> [!NOTE]  
>   La procédure ci-dessus permet également de créer, de consulter, puis de valider un avoir vente associé à un projet.

## <a name="to-calculate-and-post-job-completion-entries"></a>Pour calculer et valider les écritures d'achèvement du projet
À la fin des activités d'un projet (validation et facturation comprises), vous devez le mettre à jour pour définir le **Statut** du projet sur **Terminé**. Ensuite, vous devez contrepasser tous les travaux en cours validés antérieurement dans la comptabilité.

1. Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Projets**, puis choisissez le lien associé.  
2. Sélectionnez un projet ouvert, puis cliquez sur **Modifier**.
3. Dans le champ **Statut**, sélectionnez **Terminé**.
4. Suivez les étapes d'aide pour calculer et valider les travaux en cours. Sinon, suivez les étapes 5 et 6 pour le faire manuellement.  
5. Cliquez sur **Calculer TEC**.
6. Dans la fenêtre **Projet Calculer TEC**, renseignez les champs comme nécessaire.  

     Les écritures TEC projet créées par le traitement par lots auront la case **Projet terminé** cochée pour indiquer qu'il s'agit d'écritures d’achèvement.  
7. Cliquez sur **Projet Valider TEC en comptabilité**.
8. Dans la fenêtre **Projet Valider TEC en comptabilité**, renseignez les champs selon vos besoins.  

     Les écritures comptabilité TEC projet créées par le traitement par lots verront la case **Projet terminé** cochée pour indiquer qu'il s'agit d'écritures d’achèvement.

## <a name="see-also"></a>Voir aussi
[Gestion des projets](projects-manage-projects.md)  
[Finances](finance.md)  
[Achats](purchasing-manage-purchasing.md)         
[Ventes](sales-manage-sales.md)      
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

