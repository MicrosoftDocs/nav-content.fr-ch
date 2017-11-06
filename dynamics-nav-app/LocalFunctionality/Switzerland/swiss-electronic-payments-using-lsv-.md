---
title: "Paiements électroniques suisses avec LSV+"
description: "La méthode de paiement électronique LSV+ (Lastschrift Verfahren), ou prélèvement, une version améliorée de LSV, permet aux sociétés d'extraire les paiements directement sur les comptes bancaires de leurs clients. Pour extraire des paiements client, vous devez envoyer un fichier LSV à la banque, et la banque collectera les paiements demandés dans le fichier."
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
ms.openlocfilehash: d7f41ba3ad0706bad87d98b590eda38304bddf85
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="swiss-electronic-payments-using-lsv"></a>Paiements électroniques suisses avec LSV+
La méthode de paiement électronique LSV+ (Lastschrift Verfahren), ou prélèvement, une version améliorée de LSV, permet aux sociétés d'extraire les paiements directement sur les comptes bancaires de leurs clients. Pour extraire des paiements client, vous devez envoyer un fichier LSV à la banque, et la banque collectera les paiements demandés dans le fichier.  

La méthode LSV+ est un principe de prélèvement avec droit de contestation. La méthode BDD (Business Direct Debit) est un système de prélèvement sans droit de contestation. Le format de fichier à envoyer à la banque est identique pour LSV+ et BDD.  

Avant d'utiliser le module LSV, vous devez définir les paramètres dans la fenêtre **Paramètres LSV**. Pour plus d'informations, voir la table Paramètres LSV.  

## <a name="automatic-esr-processing"></a>Traitement BVR automatique  
Vous pouvez télécharger des transactions crédit paiement au format de fichier BVR (bulletin de versement avec numéro de référence) depuis la banque. Vous pouvez recevoir des paiements LSV traités dans le fichier BVR si le numéro de référence BVR est intégré au système LSV+. Si les paiements LSV+ sont inclus dans vos fichiers LSV importés, les lignes feuille LSV associées sont clôturées automatiquement. Le traitement BVR automatique est exécuté uniquement pour les paiements qui utilisent des francs suisses (CHF) et exige que vous exécutiez les opérations suivantes :  

- Après avoir envoyé le fichier LSV+ à la banque, soumettre un état paiements dans les trois jours ouvrables qui suivent la date du traitement LSV demandé.  

- Importer les fichiers BVR et valider les feuilles BVR. Si une transaction BVR importée est associée à une ligne paiement LSV+ ouverte, la ligne feuille LSV appropriée est automatiquement clôturée par BVR.  

    > [!NOTE]  
    >  Lors de l'importation d'un fichier BVR, la ligne feuille LSV est clôturée par BVR si la feuille LSV appropriée est trouvée, peu importe le type transaction BVR.  

- Après la date de traitement LSV, vous pouvez vérifier les lignes feuille LSV. Si toutes les lignes feuille LSV sont clôturées, le statut du champ **Statut LSV** est mis à jour et devient **Terminé**.  

## <a name="see-also"></a>Voir aussi  
 [Procédure : traiter un recouvrement LSV](how-to-process-an-lsv-collection.md)   
 [Procédure : clôturer un recouvrement LSV](how-to-close-an-lsv-collection.md)   
 [Procédure : valider des paiements LSV+](how-to-post-lsv-payments.md)   
 [Procédure : exporter des paiements avec LSV](how-to-export-payments-using-lsv.md)   
 [Paiements électroniques suisses](swiss-electronic-payments.md)   
 [Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md)   
 [Paiements électroniques suisses avec BVR](swiss-electronic-payments-using-esr.md)   
 [Exécution de paiements](../../payables-make-payments.md)

