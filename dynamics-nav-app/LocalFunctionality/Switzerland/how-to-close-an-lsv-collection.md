---
title: "Procédure : clôturer un recouvrement LSV"
description: "Vous devez clôturer les recouvrements LSV+ (Lastschrift Verfahren) pour écrire des fichiers LSV qu'il est possible d'envoyer à la banque pour recouvrement de paiement. Lorsque vous clôturez un recouvrement, celui-ci est complet, et les validations dans la feuille LSV sont combinées."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1d63f24a50024f4561b5827f2b6b1328c207a873
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-close-an-lsv-collection"></a>Procédure : clôturer un recouvrement LSV
Vous devez clôturer les recouvrements LSV+ (Lastschrift Verfahren) pour écrire des fichiers LSV qu'il est possible d'envoyer à la banque pour recouvrement de paiement. Lorsque vous clôturez un recouvrement, celui-ci est complet, et les validations dans la feuille LSV sont combinées.  
  
 Lorsque le recouvrement est complet, le numéro de recouvrement actuel est assigné dans la feuille LSV, en fonction du dernier recouvrement. Ce numéro LSV est transféré aux écritures client pour toutes les factures en attente. Le fichier de recouvrement peut être reconstitué à tout moment à l'aide du numéro LSV. Le champ **En attente** est également renseigné avec **LSV** dans les écritures client pour éviter la duplication d'écritures ouvertes. Pour plus d'informations, consultez les tables **Feuille LSV** et **Écriture comptable client**. Vous pouvez également rouvrir un recouvrement clôturé.  
  
### <a name="to-close-an-lsv-collection"></a>Pour clôturer un recouvrement LSV  
  
1.  Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Liste feuilles LSV**, puis sélectionnez le lien associé.  
  
2.  Sélectionnez la ligne feuille requise, sous l'onglet **Actions**, dans le groupe **Fonctions**, sélectionnez **Modifier date comptabilisation**. Cela modifiera la valeur du champ **Date-valeur** par la valeur suggérée pendant le recouvrement LSV.  
  
3.  Dans le champ **Nouvelle date**, entrez la nouvelle date.  
  
4.  Sous l'onglet **Actions**, dans le groupe **Fonctions**, sélectionnez **Clôturer recouvrement**.  
  
    > [!NOTE]  
    >  Les champs sous le raccourci **Options** pour le traitement par lots **Clôturer LSV** ne peuvent pas être modifiés et correspondent à la ligne feuille sélectionnée.  
  
5.  Cliquez sur le bouton **OK**.  
  
     Dans la fenêtre **Liste feuilles LSV**, la valeur du champ **Statut LSV** est modifiée de **Modifier** en **Lancé**. Les lignes feuille ne peuvent plus être modifiées.  
  
### <a name="to-reopen-an-lsv-collection"></a>Pour rouvrir un recouvrement LSV  
  
1.  Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Liste feuilles LSV**, puis sélectionnez le lien associé.  
  
2.  Sélectionnez la ligne feuille requise pour laquelle vous souhaitez rouvrir le recouvrement, sous l'onglet **Actions**, dans le groupe **Fonctions**, sélectionnez **Rouvrir le recouvrement**.  
  
    > [!NOTE]  
    >  Vous ne pouvez rouvrir le recouvrement que si vous n'avez pas encore soumis le fichier LSV+ à la banque.  
  
3.  Choisissez le bouton **Oui** pour confirmer la réouverture du recouvrement.  
  
## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Procédure : traiter un recouvrement LSV](how-to-process-an-lsv-collection.md)   
 [Procédure : valider des paiements LSV+](how-to-post-lsv-payments.md)   
 [Procédure : exporter des paiements avec LSV](how-to-export-payments-using-lsv.md)   
 Feuille LSV   
 Ligne feuille LSV   
 Écriture comptable client
