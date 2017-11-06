---
title: "Paiements électroniques suisses"
description: "Les améliorations suisses vous permettent d'envoyer des factures aux clients sous forme électronique. Les factures sont présentées et payées directement à l'aide du logiciel bancaire en ligne du client."
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
ms.openlocfilehash: e08f2c3d911e20c631f32683c284c0988a2b55b9
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="swiss-electronic-payments"></a>Paiements électroniques suisses
[!INCLUDE[navnow](../../includes/navnow_md.md)] vous permet d'envoyer des factures aux clients sous forme électronique. Les factures sont présentées et payées directement à l'aide du logiciel bancaire en ligne du client.  

## <a name="electronic-payment-methods"></a>Méthodes de paiement électronique  
Vous pouvez effectuer des paiements électroniques à l'aide des méthodes suivantes :  

- DTA (DatenTrägerAustausch)  
- OPAE (ordre de paiement électronique)  
- BVR (bulletin de versement avec numéro de référence)  
- LSV+ (Lastschrift Verfahren)  
- Virements SEPA  

## <a name="dta-and-ezag"></a>DTA et OPAE  
La méthode de paiement électronique DTA est un service universel adopté par les banques suisses pour régler les paiements par voie électronique au format DTA à l'aide d'enregistrements de paiement standardisés. Cette méthode est basée sur des supports de données et un transfer de données. Les spécifications sont coordonnées par le système SIC (Swiss Interbank Clearing). Pour plus d'informations, consultez [Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md).  

La méthode de paiement électronique OPAE est celle de l'organisme suisse PostFinance. Elle nécessite un compte courant. Vous pouvez créer et envoyer des ordres pour des paiements fournisseur au format DTA bancaire ou au format OPAE de PostFinance.  

## <a name="esr"></a>RED  
BVR est un service de débiteur électronique qui utilise des bordereaux de paiement pour les recouvrements d'argent. Il s'agit du système de paiement électronique standard créé par la Poste suisse. Vous pouvez imprimer des bordereaux de paiement BVR joints à des factures, calculer les numéros de référence BVR et importer des fichiers BVR contenant des informations de paiement provenant des banques. Pour plus d'informations, consultez [Paiements électroniques suisses avec BVR](how-to-print-esr-invoices.md). Vous pouvez également effectuer des paiements BVR et BVR+ avec la version bancaire de cette méthode de paiement, appelée BVR-Banque (BVRB).  

## <a name="lsv"></a>LSV+  
LSV+ est un service de prélèvement utilisé pour le traitement des paiements. Les sociétés peuvent libérer des paiements client directement auprès de la banque du client au moyen d'un prélèvement. Vous pouvez demander des paiements client et procéder à leur recouvrement au moyen d'un prélèvement au format bancaire LSV+ ou au format DebitDirect de PostFinance. Pour plus d'informations, consultez [Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md).  

## <a name="sepa-credit-transfers"></a>Virements SEPA  
Pour exporter des paiements conformément à la norme SEPA, vous devez utiliser un compte bancaire. Pour garantir que les écritures comptables correspondantes sont cohérentes avec celles générées pour les méthodes de paiement suisse (voir ci-dessus), la valeur du champ **Groupe compta. banque** de la fenêtre **Fiche compte bancaire** doit pointer sur le compte général pertinent. Pour plus d'informations sur la manière d'exporter des paiements SEPA, consultez [Procédure : créer des écritures recouvrement prélèvement SEPA et les exporter dans un fichier bancaire](../../finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md).  

## <a name="see-also"></a>Voir aussi  
 [Procédure : importer des numéros de clearing bancaire suisses](how-to-import-swiss-bank-clearing-numbers.md)   
 [Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md)   
 [Paiements électroniques suisses avec BVR](swiss-electronic-payments-using-esr.md)   
 [Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md)   
 [Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Fonctionnalité locale suisse](switzerland-local-functionality.md)  ' [Procédure : créer des écritures recouvrement prélèvement SEPA et les exporter dans un fichier bancaire](../../finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md)  
 [Exécution de paiements](../../payables-make-payments.md)

