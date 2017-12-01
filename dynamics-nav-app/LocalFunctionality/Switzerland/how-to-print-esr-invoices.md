---
title: "Procédure : imprimer des factures BVR"
description: "Vous pouvez imprimer un bordereau de paiement BVR (bulletin de versement avec numéro de référence) de plusieurs manières."
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
ms.openlocfilehash: 6f8972ab2df8b4704beb42695f8c79861fdf398c
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-print-esr-invoices"></a>Procédure : imprimer des factures BVR
Vous pouvez imprimer un bordereau de paiement BVR (bulletin de versement avec numéro de référence) de plusieurs manières.  

- En tant que partie du BVR facture vente.  
- En tant que document séparé appelé coupon BVR.  

L'état BVR facture vente correspond à la facture vente accompagnée d'un coupon BVR supplémentaire. En utilisant l'état coupon BVR vente, vous pouvez imprimer le bordereau de dépôt bleu.  

> [!NOTE]  
>  Vous devez sélectionner une imprimante et sélectionner les paramètres pendant l'installation du module de paiement BVR pour imprimer le bordereau de dépôt correctement. Pour plus d'informations, consultez la table Sélection de l'imprimante.  

La procédure suivante décrit comment imprimer des factures vente BVR, mais vous pouvez également la suivre pour imprimer des coupons BVR.  

## <a name="to-print-esr-invoices"></a>Pour imprimer des factures BVR  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **BVR facture**, puis sélectionnez le lien associé.  
2.  Dans le traitement par lots **BVR facture vente**, sur le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.  

    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**Nombre de copies**|Entrez le nombre requis d'exemplaires du rapport.|  
    |**Banque BVR**|Sélectionnez le code banque BVR à imprimer dans l'état.<br /><br /> Si la valeur dans ce champ est <Blank> et si le code du mode de règlement BVR n'est pas défini dans la fenêtre **Paramètres BVR**, la banque principale BVR sélectionnée dans la fenêtre **Paramètres BVR** sera imprimée.|  
    |**Journal interaction**|Spécifiez si les interactions que vous avez avec vos contacts seront consignées.|  
    |**Système BVR**|Sélectionnez le système BVR par lequel vous pouvez envoyer de nouveaux coupons BVR aux clients. Pour utiliser le système BVR utilisé par la banque que vous avez spécifiée dans le champ **Banque BVR**, sélectionnez **Selon banque BVR**.|  

3.  Choisissez le bouton **Imprimer** pour imprimer l'état ou le bouton **Aperçu** pour l'afficher à l'écran.  

Vous pouvez également réimprimer l'état BVR facture vente ou l'état coupon BVR vente.  

## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses avec BVR](swiss-electronic-payments-using-esr.md)   
 [Procédure : importer des paiements BVR](how-to-import-esr-payments.md)

