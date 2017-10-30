---
title: "Procédure : créer des relances de livraison manuellement"
description: Dans ADD INCLUDE<!--[!INCLUDE[navnow](../../includes/how-to-generate-delivery-reminders.md).
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
ms.openlocfilehash: 1437b22bfd5d8998953e5683f057bdd4a5017134
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-delivery-reminders-manually"></a>Procédure : créer des relances de livraison manuellement
Dans ADD INCLUDE<!--[!INCLUDE[navnow](../../includes/how-to-generate-delivery-reminders.md).  
  
> [!NOTE]  
>  Pour créer des relances de livraison, vous devez définir leurs propriétés. Pour plus d'informations, voir [Procédure : paramétrer des relances de livraison](how-to-set-up-delivery-reminders.md).  
  
### <a name="to-create-a-delivery-reminder-manually"></a>Pour créer une relance de livraison manuellement  
  
1.  Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Relance de livraison**, puis sélectionnez le lien associé.  
  
2.  Dans la fenêtre **Relance de livraison**, sous l'onglet **Accueil**, choisissez **Nouveau**.  
  
3.  Dans la fenêtre **Relance de livraison**, sur le raccourci **Général**, complétez les champs comme décrit dans le tableau suivant.  
  
    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**N°**|Numéro d'identification unique pour la relance de livraison.|  
    |**N° fournisseur**|Numéro du fournisseur pour lequel vous souhaitez valider la relance de livraison.<br /><br /> Lorsque vous sélectionnez le numéro fournisseur, les champs **Nom**, **Adresse**, **Code postal/Ville** et **Contact** sont renseignés automatiquement.|  
    |**Date comptabilisation**|Date comptabilisation de la relance de livraison. Cette date est copiée sur toutes les écritures comptables relance de livraison.|  
    |**Date document**|Date document de la relance de livraison. Cette date est également utilisée pour calculer la date d'échéance de la relance de livraison. Vous pouvez modifier la date de comptabilisation si nécessaire.|  
    |**Niveau relance**|Niveau de la relance de livraison. Cette valeur est basée sur le nombre de relances de livraison qui ont déjà été envoyées. Pour plus d'informations, voir [Procédure : paramétrer des conditions de relances de livraison, niveaux et texte](how-to-set-up-delivery-reminder-terms-levels-and-text.md).|  
    |**Code condition relance**|Spécifiez le code conditions de relance de livraison paramétré pour le fournisseur.|  
    |**Date besoin**|Date déchéance de la relance de livraison.|  
  
4.  Sous l'onglet **Actions**, dans le groupe **Fonctions**, choisissez **Proposer lignes relance**.  
  
     S'il existe des livraisons en retard en provenance du fournisseur spécifié, elles sont ajoutées à la relance de livraison.  
  
5.  Cliquez sur le bouton **OK**.  
  
     La relance de livraison est créée. Vous pouvez à présent émettre et imprimer la relance de livraison.  
  
## <a name="see-also"></a>Voir aussi  
 [Relances de livraison](delivery-reminders.md)   
 [Procédure : générer des relances de livraison](how-to-generate-delivery-reminders.md)   
 [Procédure : paramétrer des relances de livraison](how-to-set-up-delivery-reminders.md)   
 [Procédure : paramétrer des conditions de relances de livraison, niveaux et texte](how-to-set-up-delivery-reminder-terms-levels-and-text.md)   
 [Procédure : assigner des codes relance de livraison aux fournisseurs](how-to-assign-delivery-reminder-codes-to-vendors.md)   
 [Procédure : émettre des relances de livraison](how-to-issue-delivery-reminders.md)   
 [Procédure : imprimer des impressions test pour des relances de livraison](how-to-print-test-reports-for-delivery-reminders.md)
