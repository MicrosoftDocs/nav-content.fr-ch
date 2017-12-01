---
title: "Paiements électroniques suisses avec BVR"
description: "La méthode de paiement électronique BVR (bulletin de versement avec numéro de référence) est un service de débiteur électronique qui permet au client de facturer des factures ouvertes en francs suisses (CHF) et en euros (EUR), et de valider les paiements entrants de manière efficace."
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
ms.openlocfilehash: 7cdbeea4d65fb3be55feb49cea5a8ac5cf804382
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="swiss-electronic-payments-using-esr"></a>Paiements électroniques suisses avec BVR
La méthode de paiement électronique BVR (bulletin de versement avec numéro de référence) est un service de débiteur électronique qui permet au client de facturer des factures ouvertes en francs suisses (CHF) et en euros (EUR), et de valider les paiements entrants de manière efficace. Le numéro de référence, ou la ligne code, contient toutes les données comptables pertinentes.  

Avec les paiements électroniques BVR, vous pouvez réaliser les opérations suivantes :  

- Envoyer des bordereaux de paiement BVR avec des numéros de référence uniques sur les factures. En raison des numéros de références BVR uniques, les paiements pour déclaration sont automatiquement appliqués aux factures respectives. Pour plus d'informations, voir la rubrique [Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md).  

- Télécharger les fichiers BVR au départ de la banque chaque jour. Les fichiers contiennent des informations sur toutes les factures payées.  

- Importer les fichiers BVR et créer des lignes paiement automatiquement pour chaque paiement. Pour plus d'informations, voir la rubrique [Procédure : importer des paiements BVR](how-to-import-esr-payments.md).  

> [!NOTE]  
>  Avant de pouvoir utiliser le module BVR, vous devez paramétrer la banque, le compte bancaire et le nom de fichier. Vous devez également spécifier si la méthode BVR ou BVR+ sera utilisée.

Une fois que vous avez évalué les informations de configuration, vous pouvez ajuster le formulaire facture et créer une souche test et demander à votre service bancaire ou postal de la valider.  

Lorsque vous paramétrez des souches de numéros pour des factures, vous devez respecter les directives suivantes :  

- Utilisez un maximum de huit chiffres.  
- Utilisez uniquement des caractères numériques.  
- N'utilisez pas de zéros devant les nombres.  

## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses](swiss-electronic-payments.md)   
 [Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md)   
 [Procédure : importer des paiements BVR](how-to-import-esr-payments.md)   
 [Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md)   
 [Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Exécution de paiements](../../payables-make-payments.md)

