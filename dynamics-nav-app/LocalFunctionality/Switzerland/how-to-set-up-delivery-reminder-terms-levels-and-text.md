---
title: "Procédure : paramétrer des conditions, des niveaux et du texte pour les relances de livraison"
description: "Pour créer des relances de livraison, vous devez paramétrer des conditions, des niveaux et du texte pour ces dernières. messages"
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: d1bb57cce6c6a681e31bdfaafe05a1d8f42979e4
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-set-up-delivery-reminder-terms-levels-and-text"></a>Procédure : paramétrer des conditions de relances de livraison, niveaux et texte
Pour créer des relances de livraison, vous devez paramétrer les éléments suivants :  

- Conditions de relance de livraison  
- Niveaux de relance de livraison  
- Messages texte pour les relances de livraison  

Chaque condition de relance de livraison compte deux ou plusieurs niveaux de relance de livraison et, pour chaque niveau de relance de livraison, vous pouvez spécifier le texte qui fera partie de la relance de livraison.  

Pour plus d'informations, voir [Relances de livraison](delivery-reminders.md).  

## <a name="to-set-up-delivery-reminder-terms"></a>Pour paramétrer des conditions de relance de livraison  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Conditions de relance de livraison**, puis sélectionnez le lien associé.  
2.  Choisissez l'action **Nouveau**.  
3.  Complétez les champs comme décrit dans le tableau suivant.  

    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**Code**|Code de la condition de relance de livraison. Vous pouvez entrer au maximum 10 caractères alphanumériques.|  
    |**Description**|Description de la condition de relance de livraison. Vous pouvez entrer au maximum 30 caractères alphanumériques.|  
    |**Nombre max. de relances de livraison**|Nombre maximum de relances de livraison qui peuvent être créées pour une commande.<br /><br /> **REMARQUE :** il s'agit du nombre maximum pour tous les niveaux de relance pour cette relance de livraison. Par exemple, si vous avez paramétré trois niveaux et que vous définissez **Nombre max. de relances de livraison** sur 5, la première relance est créée au niveau 1, la deuxième au niveau 2 et les trois dernières au niveau 3.|  

4.  Cliquez sur le bouton **OK**.  

## <a name="to-add-delivery-reminder-levels-to-a-delivery-reminder-term"></a>Pour ajouter des niveaux de relance de livraison à une condition de relance de livraison  

1.  Dans la fenêtre **Conditions de relance de livraison**, sélectionnez la condition de relance de livraison pour laquelle vous souhaitez paramétrer des niveaux, puis choisissez l'action **Niveaux**.  
2.  Choisissez l'action **Nouveau**.  
3.  Complétez les champs comme décrit dans le tableau suivant.  

    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**N°**|Numéro du niveau de la relance de livraison. Ce champ est renseigné automatiquement.|  
    |**Calcul date échéance**|Formule pour le calcul de la date d'échéance de la relance de livraison. Vous pouvez entrer une combinaison de nombres de 0 à 9999 et des codes date (J pour jour, JS pour jour de semaine, S pour semaine, M pour mois, T pour trimestre, ou A pour année). Les codes date désignent le calcul de la date d'échéance de la relance de livraison. Vous pouvez entrer au maximum 20 caractères pour la formule du calcul de la date d'échéance.|  

4.  Cliquez sur le bouton **OK**.  

Pour chaque niveau de relance de livraison, vous définissez des messages texte qui sont ajoutés à la relance de livraison. Vous pouvez définir le texte de début qui est ajouté avant la description de la commande achat en retard et le texte de fin qui est ajouté après la description de la commande achat en retard.  

La procédure suivante décrit comment paramétrer des messages texte de début, mais vous pouvez également la suivre pour paramétrer les messages texte de fin.  

## <a name="to-set-up-delivery-reminder-text-messages"></a>Pour paramétrer des messages texte pour les relances de livraison  

1.  Dans la fenêtre **Niveaux relance de livraison**, sélectionnez un niveau, puis choisissez l'action **Texte début**.  
2.  Choisissez l'action **Nouveau**.  
3.  Dans le champ **Description**, entrez le message texte de début de la relance de livraison.  
4.  Cliquez sur le bouton **OK**.  

## <a name="see-also"></a>Voir aussi  
 [Relances de livraison](delivery-reminders.md)   
 [Procédure : paramétrer des relances de livraison](how-to-set-up-delivery-reminders.md)   
 [Procédure : assigner des codes relance de livraison aux fournisseurs](how-to-assign-delivery-reminder-codes-to-vendors.md)   
 [Procédure : créer des relances de livraison manuellement](how-to-create-delivery-reminders-manually.md)   
 [Procédure : émettre des relances de livraison](how-to-issue-delivery-reminders.md)

