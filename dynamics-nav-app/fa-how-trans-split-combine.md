---
title: Reclassification d'immobilisations
description: "Vous reclassez une immobilisation pour la transférer vers un autre service, la fractionner, ou la combiner avec d'autres immobilisations."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 43b24201037de228faf4f58cc46bd92f796d72e3
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-transfer-split-or-combine-fixed-assets"></a>Procédure : transférer, fractionner ou regrouper les immobilisations
Vous pouvez utiliser la feuille reclassement immobilisation pour transférer, fractionner et regrouper des immobilisations. Vous visualisez ou imprimez les résultats d'un reclassement immobilisation avec l'état **Immo. - Valeur comptable 02**.

## <a name="to-transfer-a-fixed-asset-to-a-different-department"></a>Pour transférer une immobilisation vers un autre département
Vous pouvez transférer une immobilisation vers un autre département lorsque, par exemple, vous placez une immobilisation dans le département production lorsqu'elle est en construction, puis la déplacez vers le département administration lorsqu'elle est finalisée.  

1. Définissez une nouvelle immobilisation. Saisissez le nouveau département dans le champ **Code département**.
2. Affectez une loi d'amortissement d'immobilisation vers la nouvelle immobilisation. Pour en savoir plus, voir [Procédure : acquérir les immobilisations](fa-how-acquire.md).
3. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuilles reclassement immo.**, puis sélectionnez le lien connexe.
4. Créez une feuille reclassement lorsque le champ **N° immo.** contient l'immobilisation initiale, et le champ **Nouveau N° immo.** indique la nouvelle immobilisation à déplacer.  
5. Sélectionnez l'action **Reclasser**.

    Deux lignes sont maintenant créées dans la ligne feuille immobilisation à l'aide du modèle et de la feuille que vous avez indiqués dans la fenêtre **Param. feuille immo.** pour la loi d'amortissement sélectionnée. Pour en savoir plus, voir [Procédure : configurer l'amortissement d'immobilisation](fa-how-setup-depreciation.md).
6. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuille comptabilisation immobilisation**, puis sélectionnez le lien connexe.    
7. Dans la fenêtre **Feuille compta. immo.**, sélectionnez l'action **Valider** pour valider le reclassement que vosu avez effectué aux étapes 4 et 5.

Si vous avez validé un coût d'acquisition pour une immobilisation, vous pouvez utiliser la feuille reclassement immobilisation pour répartir ce coût sur plusieurs immobilisations.  

## <a name="to-split-a-fixed-asset-into-three-fixed-assets"></a>Pour fractionner une immobilisation en trois immobilisations
Vous pouvez fractionner une immobilisation en plusieurs immobilisations, par exemple lorsque vous devez distribuer une immobilisation auprès de trois départements. Dans ce cas, vous pouvez déplacer, par exemple, 25 % du coût d'acquisition et de l'amortissement de l'immobilisation d'origine vers une autre, et 45 % vers une troisième. Les 30 % restants sont maintenus dans l'immobilisation d'origine.

1. Configurez deux nouvelles immobilisations. Saisissez le nouveau département dans le champ **Code département**.
2. Affectez des lois d'amortissement d'immobilisation aux nouvelles immobilisations. Pour en savoir plus, voir [Procédure : acquérir les immobilisations](fa-how-acquire.md).
3. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuilles reclassement immo.**, puis sélectionnez le lien connexe.
4. Créez deux lignes feuille reclassement, une pour chaque nouvelle immobilisation.
5. Sur la première ligne, entrez la deuxième immobilisation dans le champ **Nouveau N° immo.** et 25 dans le champ **Reclass. coût acq. %**.
6. Sur la deuxième ligne, entrez la troisième immobilisation dans le champ **Nouveau N° immo.** et 40 dans le champ **Reclass. coût acq. %**.
7. Sur les deux lignes, cochez les cases **Reclass. coût acq.** et **Reclass. amortissement**.   
8. Sélectionnez l'action **Reclasser**.

    Deux lignes sont maintenant créées dans la ligne feuille immobilisation à l'aide du modèle et de la feuille que vous avez indiqués dans la fenêtre **Param. feuille immo.** pour la loi d'amortissement sélectionnée. Pour en savoir plus, voir [Procédure : configurer l'amortissement d'immobilisation](fa-how-setup-depreciation.md).    
9. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuille comptabilisation immobilisation**, puis sélectionnez le lien connexe.
10. Dans la fenêtre **Feuille compta. immo.**, sélectionnez l'action **Valider** pour valider le reclassement que vous avez effectué aux étapes 4 à 8.

## <a name="to-combine-two-fixed-assets-into-one"></a>Pour regrouper deux immobilisations en une
Vous pouvez regrouper plusieurs immobilisations en une, par exemple lorsque vous déplacez les immobilisations distribuées dans un département. Si vous avez validé les coûts d'acquisition et l'amortissement pour l'immobilisation à déplacer, ces valeurs seront regroupées dans l'immobilisation unique.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuilles reclassement immo.**, puis sélectionnez le lien connexe.
2. Créez une feuille reclassement lorsque le champ **N° immo.** contient l'immobilisation initiale à déplacer/combiner, et le champ **Nouveau N° immo.** indique la nouvelle immobilisation qui lui sera combinée.
3. Laissez le champ **Reclass. coût acq. %** vide pour déplacer/regrouper le coût total de l'acquisition.    
4. Cochez les deux cases **Reclass. coût acq.** et **Reclass. amortissement**.
5. Sous l'onglet **Actions**, choisissez **Reclasser**.

    Deux lignes sont maintenant créées dans la ligne feuille immobilisation à l'aide du modèle et de la feuille que vous avez indiqués dans la fenêtre **Param. feuille immo.** pour la loi d'amortissement sélectionnée. Pour en savoir plus, voir [Procédure : configurer l'amortissement d'immobilisation](fa-how-setup-depreciation.md).   
6. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuille comptabilisation immobilisation**, puis sélectionnez le lien connexe.
7. Dans la fenêtre **Feuille compta. immo.**, sélectionnez l'action **Valider** pour valider le reclassement que vosu avez effectué aux étapes 2 à 5.

## <a name="to-view-changed-depreciation-book-values-due-to-fixed-asset-reclassification"></a>Pour afficher les valeurs de loi d'amortissement modifiées en raison d'un reclassement immobilisation.
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuilles reclassement immo.**, puis sélectionnez le lien connexe.
2. Renseignez les champs selon vos besoins.
3. Cliquez sur le bouton **Imprimer** ou **Aperçu**.  

## <a name="see-also"></a>Voir aussi
[Immobilisations](fa-manage.md)  
[Paramétrage d'immobilisations](fa-setup.md)  
[Finances](finance.md)  
[Bienvenue dans [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

