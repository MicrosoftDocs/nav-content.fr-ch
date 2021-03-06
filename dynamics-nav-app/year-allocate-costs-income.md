---
title: "Aperçu des tâches de ventilation des coûts et des revenus"
description: "Décrit les tâches pour ventiler une écriture dans une feuille comptabilité dans différents comptes lorsque vous validez la feuille."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fdb03090dc9ba024d84a175e313f7d530bd0feae
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-allocate-costs-and-income"></a>Procédure : ventiler des coûts et des bénéfices
Vous pouvez ventiler une écriture dans une feuille comptabilité dans différents comptes lorsque vous validez la feuille. La ventilation peut être effectuée de trois manières différentes :

* Quantité
* Pourcentage (%)
* Montant

Les fonctions de ventilation peuvent être utilisées avec les feuilles abonnement et dans les feuilles immobilisation.
<!--You can also distribute the cost or revenue of a line to an intercompany partner when you post a sales or purchase document. When you post the document, a line will be posted in your general journal, and a corresponding line will be created in the intercompany outbox.-->

Les procédures suivantes décrivent comment se préparer à affecter des coûts dans une feuille abonnement en définissant des clés de ventilation. Lorsque des clés de ventilation sont définies, vous renseignez et validez la feuille comme toute autre feuille abonnement. Pour plus d'informations, voir [Utilisation des feuilles comptabilité](ui-work-general-journals.md).

## <a name="to-set-up-allocation-keys"></a>Pour définir des clés de ventilation
Vous pouvez ventiler une écriture dans une feuille abonnement dans différents comptes lorsque vous validez la feuille. La ventilation peut être effectuée par quantité, pourcentage ou montant.
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuille abonnement**, puis sélectionnez le lien connexe.
2. Sélectionnez le champ **Nom de la feuille** pour ouvrir la fenêtre **Noms feuilles comptabilité**.
3. Vous pouvez soit modifier les ventilations sur un lot existant dans la liste ou créer un lot avec des ventilations.
   * Pour créer un lot, sélectionnez l'action **Nouveau**, et passez à l'étape suivante.
   * Pour modifier les ventilations à partir d'une feuille existante, sélectionnez la feuille et passez à l'étape 7.    
4. Dans le champ **Nom**, saisissez le nom du lot, par exemple NETTOYAGE. Dans le champ **Description**, saisissez une description, par exemple Feuille frais de nettoyage.
5. Fermez la fenêtre lorsque vous avez terminé. Une nouvelle feuille récurrente vide s'ouvre.
6. Renseignez les champs de la ligne.
7. Sélectionnez l'action **Ventilations**.
8. Ajoutez une ligne pour chaque ventilation. Vous devez renseigner le champ **% ventilation**, **Quantité imputée** ou **Montant**. Vous devez également renseigner le champ **N° compte** et, si vous affectez la transaction à des axes principaux, les champs de ces axes principaux.
9. Si vous saisissez un pourcentage dans une ligne, le montant du champ **Montant** est calculé automatiquement. Ces montants sont dotés du signe opposé à celui du montant total figurant dans le champ **Montant** de la feuille récurrente.
10. Après avoir saisi les lignes de ventilation, cliquez sur **OK** pour revenir à la fenêtre **Feuille abonnement**. Le champ **Montant imputé DS** est renseigné et correspond au champ **Montant**.
11. Validez la feuille.

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a>Pour modifier une clé de ventilation déjà configurée
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuille abonnement**, puis sélectionnez le lien connexe.
2. Dans la fenêtre **Feuille récurrente**, sélectionnez la feuille contenant la ventilation.
3. Sélectionnez la ligne de la ventilation, puis sélectionnez l'action **Ventilations**.
4. Modifiez les champs appropriés, puis cliquez sur le bouton **OK**.

## <a name="see-also"></a>Voir aussi
[Clôture des exercices et des périodes](year-close-years-periods.md)  
[Utilisation de feuilles comptabilité](ui-work-general-journals.md)    
[Validation des documents et des feuilles](ui-post-documents-journals.md)    
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

