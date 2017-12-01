---
title: "Paiements électroniques suisses avec LSV+"
description: "La méthode de paiement électronique LSV+ (Lastschrift Verfahren), ou prélèvement, une version améliorée de LSV, permet aux sociétés d'extraire les paiements directement sur les comptes bancaires de leurs clients. Pour extraire des paiements client, vous devez envoyer un fichier LSV à la banque, et la banque collectera les paiements demandés dans le fichier."
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
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 7ffb8ab0b0d5b4e9484cafcd40e960313d0945c7
ms.contentlocale: fr-ch
ms.lasthandoff: 12/01/2017

---
# <a name="swiss-electronic-payments-using-lsv"></a><span data-ttu-id="5e798-104">Paiements électroniques suisses avec LSV+</span><span class="sxs-lookup"><span data-stu-id="5e798-104">Swiss Electronic Payments Using LSV+</span></span>
<span data-ttu-id="5e798-105">La méthode de paiement électronique LSV+ (Lastschrift Verfahren), ou prélèvement, une version améliorée de LSV, permet aux sociétés d'extraire les paiements directement sur les comptes bancaires de leurs clients.</span><span class="sxs-lookup"><span data-stu-id="5e798-105">The Lastschrift Verfahren (LSV+)—or direct debit—electronic payment method, an improved version of LSV, allows companies to retrieve payments directly from its customers’ bank accounts.</span></span> <span data-ttu-id="5e798-106">Pour extraire des paiements client, vous devez envoyer un fichier LSV à la banque, et la banque collectera les paiements demandés dans le fichier.</span><span class="sxs-lookup"><span data-stu-id="5e798-106">To retrieve customer payments, you must send an LSV file to the bank, and the bank will collect the payments requested in the file.</span></span>  

<span data-ttu-id="5e798-107">La méthode LSV+ est un principe de prélèvement avec droit de contestation.</span><span class="sxs-lookup"><span data-stu-id="5e798-107">The LSV+ method is a direct debit principle with right of objection.</span></span> <span data-ttu-id="5e798-108">La méthode BDD (Business Direct Debit) est un système de prélèvement sans droit de contestation.</span><span class="sxs-lookup"><span data-stu-id="5e798-108">Business Direct Debit (BDD) is a direct debit system without right of objection.</span></span> <span data-ttu-id="5e798-109">Le format de fichier à envoyer à la banque est identique pour LSV+ et BDD.</span><span class="sxs-lookup"><span data-stu-id="5e798-109">The file format to be sent to the bank is the same for LSV+ and BDD.</span></span>  

<span data-ttu-id="5e798-110">Avant d'utiliser le module LSV, vous devez définir les paramètres dans la fenêtre **Paramètres LSV**.</span><span class="sxs-lookup"><span data-stu-id="5e798-110">Before using the LSV module, you must define the settings in the **LSV Setup** window.</span></span> <span data-ttu-id="5e798-111">Pour plus d'informations, voir la table Paramètres LSV.</span><span class="sxs-lookup"><span data-stu-id="5e798-111">For more information, see the LSV Setup table.</span></span>  

## <a name="automatic-esr-processing"></a><span data-ttu-id="5e798-112">Traitement BVR automatique</span><span class="sxs-lookup"><span data-stu-id="5e798-112">Automatic ESR Processing</span></span>  
<span data-ttu-id="5e798-113">Vous pouvez télécharger des transactions crédit paiement au format de fichier BVR (bulletin de versement avec numéro de référence) depuis la banque.</span><span class="sxs-lookup"><span data-stu-id="5e798-113">You can download payment credit transactions in Einzahlungsschein mit Referenznummer (ESR) file format from the bank.</span></span> <span data-ttu-id="5e798-114">Vous pouvez recevoir des paiements LSV traités dans le fichier BVR si le numéro de référence BVR est intégré au système LSV+.</span><span class="sxs-lookup"><span data-stu-id="5e798-114">You can receive processed LSV payments in the ESR file if the ESR reference number is integrated with the LSV+ system.</span></span> <span data-ttu-id="5e798-115">Si les paiements LSV+ sont inclus dans vos fichiers LSV importés, les lignes feuille LSV associées sont clôturées automatiquement.</span><span class="sxs-lookup"><span data-stu-id="5e798-115">If LSV+ payments are included in your imported LSV files, the related LSV journal lines are closed automatically.</span></span> <span data-ttu-id="5e798-116">Le traitement BVR automatique est exécuté uniquement pour les paiements qui utilisent des francs suisses (CHF) et exige que vous exécutiez les opérations suivantes :</span><span class="sxs-lookup"><span data-stu-id="5e798-116">Automatic ESR processing is performed only for payments that use Swiss Francs (CHF), and requires that you do the following:</span></span>  

- <span data-ttu-id="5e798-117">Après avoir envoyé le fichier LSV+ à la banque, soumettre un état paiements dans les trois jours ouvrables qui suivent la date du traitement LSV demandé.</span><span class="sxs-lookup"><span data-stu-id="5e798-117">After you have sent the LSV+ file to the bank, submit a payments report within three business days following the requested LSV processing date.</span></span>  

- <span data-ttu-id="5e798-118">Importer les fichiers BVR et valider les feuilles BVR.</span><span class="sxs-lookup"><span data-stu-id="5e798-118">Import the ESR files, and post the ESR journals.</span></span> <span data-ttu-id="5e798-119">Si une transaction BVR importée est associée à une ligne paiement LSV+ ouverte, la ligne feuille LSV appropriée est automatiquement clôturée par BVR.</span><span class="sxs-lookup"><span data-stu-id="5e798-119">If an imported ESR transaction is related to an open LSV+ payment line, then the appropriate LSV journal line is automatically closed by ESR.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="5e798-120">Lors de l'importation d'un fichier BVR, la ligne feuille LSV est clôturée par BVR si la feuille LSV appropriée est trouvée, peu importe le type transaction BVR.</span><span class="sxs-lookup"><span data-stu-id="5e798-120">When importing an ESR file, the LSV journal line is closed by ESR if the appropriate LSV journal is found, regardless of the ESR transaction type.</span></span>  

- <span data-ttu-id="5e798-121">Après la date de traitement LSV, vous pouvez vérifier les lignes feuille LSV.</span><span class="sxs-lookup"><span data-stu-id="5e798-121">After the LSV processing date, you can check the LSV journal lines.</span></span> <span data-ttu-id="5e798-122">Si toutes les lignes feuille LSV sont clôturées, le statut du champ **Statut LSV** est mis à jour et devient **Terminé**.</span><span class="sxs-lookup"><span data-stu-id="5e798-122">If all of the LSV journal lines are closed, then the status of the **LSV Status** field is updated to  **Finished**.</span></span>  

## <a name="see-also"></a><span data-ttu-id="5e798-123">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="5e798-123">See Also</span></span>  
 <span data-ttu-id="5e798-124">[Procédure : traiter un recouvrement LSV](how-to-process-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="5e798-124">[How to: Process an LSV Collection](how-to-process-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="5e798-125">[Procédure : clôturer un recouvrement LSV](how-to-close-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="5e798-125">[How to: Close an LSV Collection](how-to-close-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="5e798-126">[Procédure : valider des paiements LSV+](how-to-post-lsv-payments.md) </span><span class="sxs-lookup"><span data-stu-id="5e798-126">[How to: Post LSV+ Payments](how-to-post-lsv-payments.md) </span></span>  
 <span data-ttu-id="5e798-127">[Procédure : exporter des paiements avec LSV](how-to-export-payments-using-lsv.md) </span><span class="sxs-lookup"><span data-stu-id="5e798-127">[How to: Export Payments Using LSV](how-to-export-payments-using-lsv.md) </span></span>  
 <span data-ttu-id="5e798-128">[Paiements électroniques suisses](swiss-electronic-payments.md) </span><span class="sxs-lookup"><span data-stu-id="5e798-128">[Swiss Electronic Payments](swiss-electronic-payments.md) </span></span>  
 <span data-ttu-id="5e798-129">[Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md) </span><span class="sxs-lookup"><span data-stu-id="5e798-129">[Swiss Electronic Payments Using DTA](swiss-electronic-payments-using-dta.md) </span></span>  
 <span data-ttu-id="5e798-130">[Paiements électroniques suisses avec BVR](swiss-electronic-payments-using-esr.md) </span><span class="sxs-lookup"><span data-stu-id="5e798-130">[Swiss Electronic Payments Using ESR](swiss-electronic-payments-using-esr.md) </span></span>  
 [<span data-ttu-id="5e798-131">Exécution de paiements</span><span class="sxs-lookup"><span data-stu-id="5e798-131">Making Payments</span></span>](../../payables-make-payments.md)

