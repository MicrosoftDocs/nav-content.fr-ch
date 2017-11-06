---
title: "Procédure : Proposer un paiement DTA pour les fournisseurs"
description: "Vous pouvez proposer des paiements fournisseur à l'aide de la feuille paiement, et transférer les factures échues dans la feuille pour des fournisseurs spécifiques. Vous pouvez également rechercher les avoirs ouverts ou les paiements ouverts pour chaque fournisseur et constituer une liste de fournisseurs pour traitement DTA (DatenTrägerAustausch)."
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
ms.openlocfilehash: b51b3f9273e9e737ef09901b0718d55350d44f87
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-suggest-dta-payment-for-vendors"></a>Procédure : Proposer paiement DTA pour les fournisseurs
Vous pouvez proposer des paiements fournisseur à l'aide de la feuille paiement, et transférer les factures échues dans la feuille pour des fournisseurs spécifiques. Vous pouvez également rechercher les avoirs ouverts ou les paiements ouverts pour chaque fournisseur et constituer une liste de fournisseurs pour traitement DTA (DatenTrägerAustausch). Pour plus d'informations, consultez [Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md).  

Pendant le traitement par lots des propositions de paiement DTA, le montant en devise étrangère (DE) est converti en devise société (DS) au taux actuel des paiements DE et transféré dans la feuille paiement. Pour plus d'informations, consultez la fenêtre **Feuille paiement** . Dans le cas d'un débit bancaire, le montant DS est remplacé par le montant DS débité, et le taux de change (ou facteur de change) est calculé.

## <a name="to-suggest-dta-payment-for-vendors"></a>Pour proposer un paiement DTA pour les fournisseurs  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles paiement**, puis sélectionnez le lien associé.  
2.  Dans le champ **Nom de la feuille**, sélectionnez le nom de la feuille requis.  
3.  Sélectionnez la ligne paiement requise, puis choisissez l'action **Proposer paiements fournisseur DTA**.  
4.  Dans la fenêtre **Proposer paiements fournisseur DTA**, sur le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.  

    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**Date comptabilisation**|Spécifiez la date crédit du paiement. Cette date est utile pour déterminer si un escompte a été accordé.|  
    |**Date échéance début**|Spécifiez la date de début des factures ouvertes à inclure dans la proposition de paiement.|  
    |**Date échéance fin**|Spécifiez la date de fin des factures ouvertes à inclure dans la proposition de paiement.|  
    |**Rechercher les escomptes**|Spécifiez si les paiements d'escompte en dehors de la plage de dates d'échéance seront pris en considération pour la proposition de paiement.|  
    |**Date début d'escompte**|Spécifiez la date de début de l'escompte. Les écritures ouvertes avec dates d'escompte dans cette plage de dates sont incluses dans la proposition de paiement.|  
    |**Date fin d'escompte**|Spécifiez la date de fin de l'escompte. Les écritures ouvertes avec dates d'escompte dans cette plage de dates sont incluses dans la proposition de paiement.|  
    |**Montant disponible DS**|Entrez la valeur maximum de la somme de tous les paiements.|  
    |**Premier n° document**|Spécifiez le numéro de document de la proposition de paiement. Ce numéro est attribué en fonction de la souche de numéros du journal actuel.|  
    |**Banque à débiter**|Sélectionnez le code de la banque qui recevra le débit. La banque doit être activée pour DTA.|  
    |**Banque à débiter auto.**|Spécifiez si la banque sera débitée automatiquement, en fonction du code devise.|  

5.  Cliquez sur le bouton **OK**.  

Pendant le traitement, chaque fournisseur est contrôlé pour rechercher les avoirs ouverts ou les paiements ouverts, et un message s'affiche à la fin du processus. Toutes les lignes associées sont transférées vers la feuille paiement. Les écritures comptables fournisseur correspondantes sont marquées **DTA** pour éviter le transfert d'écritures en double dans la feuille paiement. Vous pouvez afficher, vérifier et modifier les paiements proposés, et vous pouvez décider si vous souhaitez diminuer les paiements du montant des avoirs ou appliquer les avoirs ouverts et les factures ouvertes.  

## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md)   
 [Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md)   
 [Procédure : soumettre des paiements DTA](how-to-submit-dta-payments.md)   
 [Procédure : exporter des paiements avec EZAG](how-to-export-payments-using-ezag.md)   
 [Exécution de paiements](../../payables-make-payments.md)

