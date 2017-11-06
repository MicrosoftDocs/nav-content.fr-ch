---
title: Relances de livraison
description: "Les relances de livraison sont utilisées pour suivre les expéditions fournisseur en retard et pour rappeler aux fournisseurs des livraisons en retard."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 263a1a00f4e0511b6e49ffb749ac06518828e30a
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="delivery-reminders"></a>Relances de livraison
Les relances de livraison sont utilisées pour suivre les expéditions fournisseur en retard et pour rappeler aux fournisseurs des livraisons en retard. Pour créer des relances de livraison, vous devez paramétrer les éléments suivants :  

- Conditions de relance de livraison  

    Les conditions de relance de livraison sont identifiées par un code qui doit être assigné aux fournisseurs. Pour utiliser plusieurs combinaisons de paramètres, vous devez paramétrer un code pour chaque paramètre séparément. Vous pouvez paramétrer n'importe quel nombre de conditions de relances de livraison  

- Niveaux de relance de livraison  

    Pour chaque condition de relance de livraison, vous devez paramétrer des niveaux de relance de livraison. Ces niveaux déterminent à quelle fréquence il est possible de créer des relances de livraison pour une condition spécifique. Le niveau 1 est la première relance de livraison que vous créez pour une livraison en retard. Le niveau 2 est la deuxième relance de livraison, etc. Lors de la création de relances de livraison, le nombre de relances créées précédemment est pris en compte, et le numéro actuel est utilisé pour appliquer des conditions.  

- Messages texte pour les relances de livraison  

    Vous devez paramétrer des messages texte pour chaque niveau de relance de livraison. Il existe deux types de messages texte pour les relances de livraison : début et fin. Le message texte de début est imprimé sous la section en-tête, avant la liste des écritures marquées pour relance. Le message texte de fin est imprimé après cette liste.  

Pour plus d'informations, voir [Procédure : paramétrer des conditions de relances de livraison, niveaux et texte](how-to-set-up-delivery-reminder-terms-levels-and-text.md).  

Après avoir configuré les conditions de relance, vous devez assigner les codes condition de relance de livraison aux fournisseurs. Pour plus d'informations, voir [Procédure : assigner des codes de relance de livraison aux fournisseurs](how-to-assign-delivery-reminder-codes-to-vendors.md).  

Vous pouvez créer des relances de livraison manuellement ou automatiquement. Vous pouvez utiliser le traitement par lots **Créer une relance de livraison** pour créer des relances de livraison automatiquement. Ce traitement par lots vous permet de sélectionner les commandes achat pour lesquelles vous devez créer des relances de livraison. Pour plus d'informations, voir [Procédure : générer des relances de livraison](how-to-issue-delivery-reminders.md).  

Vous pouvez également suivre des documents en fonction de lignes commande achat et de lignes commande vente.  

[!INCLUDE[navnow](../../includes/navnow_md.md)] propose les états suivants :  

- **Relance de livraison émise** - Pour afficher les relances de livraison pour les fournisseurs.  
- **Relance de livraison - Test** - Pour vérifier les relances de livraison avant de les émettre.  

Pour plus d'informations, voir [Procédure : imprimer des impressions test pour des relances de livraison](how-to-print-test-reports-for-delivery-reminders.md).  

## <a name="see-also"></a>Voir aussi  
 [Procédure : paramétrer des relances de livraison](how-to-set-up-delivery-reminders.md)   
 [Procédure : paramétrer des conditions de relances de livraison, niveaux et texte](how-to-set-up-delivery-reminder-terms-levels-and-text.md)   
 [Procédure : assigner des codes relance de livraison aux fournisseurs](how-to-assign-delivery-reminder-codes-to-vendors.md)   
 [Procédure : générer des relances de livraison](how-to-generate-delivery-reminders.md)   
 [Procédure : créer des relances de livraison manuellement](how-to-create-delivery-reminders-manually.md)   
 [Procédure : émettre des relances de livraison](how-to-issue-delivery-reminders.md)   
 [Procédure : imprimer des impressions test pour des relances de livraison](how-to-print-test-reports-for-delivery-reminders.md)

