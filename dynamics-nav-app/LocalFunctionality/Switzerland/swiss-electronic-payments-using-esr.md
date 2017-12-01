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
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: bf438e09f7a899b8539c878630f6c773ffbe6e96
ms.contentlocale: fr-ch
ms.lasthandoff: 12/01/2017

---
# <a name="swiss-electronic-payments-using-esr"></a><span data-ttu-id="e9055-103">Paiements électroniques suisses avec BVR</span><span class="sxs-lookup"><span data-stu-id="e9055-103">Swiss Electronic Payments Using ESR</span></span>
<span data-ttu-id="e9055-104">La méthode de paiement électronique BVR (bulletin de versement avec numéro de référence) est un service de débiteur électronique qui permet au client de facturer des factures ouvertes en francs suisses (CHF) et en euros (EUR), et de valider les paiements entrants de manière efficace.</span><span class="sxs-lookup"><span data-stu-id="e9055-104">The Einzahlungsschein mit Referenznummer (ESR) electronic payment method is an electronic debtor service that allows the customer to bill open invoices in Swiss Francs (CHF) and Euros (EUR), and to post incoming payments efficiently.</span></span> <span data-ttu-id="e9055-105">Le numéro de référence, ou la ligne code, contient toutes les données comptables pertinentes.</span><span class="sxs-lookup"><span data-stu-id="e9055-105">The reference number, or code line, contains all relevant bookkeeping data.</span></span>  

<span data-ttu-id="e9055-106">Avec les paiements électroniques BVR, vous pouvez réaliser les opérations suivantes :</span><span class="sxs-lookup"><span data-stu-id="e9055-106">With ESR electronic payments, you can do the following:</span></span>  

- <span data-ttu-id="e9055-107">Envoyer des bordereaux de paiement BVR avec des numéros de référence uniques sur les factures.</span><span class="sxs-lookup"><span data-stu-id="e9055-107">Send ESR payment slips with unique reference numbers on the invoices.</span></span> <span data-ttu-id="e9055-108">En raison des numéros de références BVR uniques, les paiements pour déclaration sont automatiquement appliqués aux factures respectives.</span><span class="sxs-lookup"><span data-stu-id="e9055-108">Because of the unique ESR reference numbers, the payments for settlement are automatically applied to the related invoices.</span></span> <span data-ttu-id="e9055-109">Pour plus d'informations, voir la rubrique [Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md).</span><span class="sxs-lookup"><span data-stu-id="e9055-109">For more information, see [How to: Print ESR Invoices](how-to-print-esr-invoices.md).</span></span>  

- <span data-ttu-id="e9055-110">Télécharger les fichiers BVR au départ de la banque chaque jour.</span><span class="sxs-lookup"><span data-stu-id="e9055-110">Download the ESR files from the bank daily.</span></span> <span data-ttu-id="e9055-111">Les fichiers contiennent des informations sur toutes les factures payées.</span><span class="sxs-lookup"><span data-stu-id="e9055-111">The files contain information about all paid invoices.</span></span>  

- <span data-ttu-id="e9055-112">Importer les fichiers BVR et créer des lignes paiement automatiquement pour chaque paiement.</span><span class="sxs-lookup"><span data-stu-id="e9055-112">Import the ESR files and create payment lines automatically for each payment.</span></span> <span data-ttu-id="e9055-113">Pour plus d'informations, voir la rubrique [Procédure : importer des paiements BVR](how-to-import-esr-payments.md).</span><span class="sxs-lookup"><span data-stu-id="e9055-113">For more information, see [How to: Import ESR Payments](how-to-import-esr-payments.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="e9055-114">Avant de pouvoir utiliser le module BVR, vous devez paramétrer la banque, le compte bancaire et le nom de fichier.</span><span class="sxs-lookup"><span data-stu-id="e9055-114">Before you can use the ESR module, you must set up the bank, bank account, and file name.</span></span> <span data-ttu-id="e9055-115">Vous devez également spécifier si la méthode BVR ou BVR+ sera utilisée.</span><span class="sxs-lookup"><span data-stu-id="e9055-115">You must also specify whether ESR or ESR+ should be used.</span></span>

<span data-ttu-id="e9055-116">Une fois que vous avez évalué les informations de configuration, vous pouvez ajuster le formulaire facture et créer une souche test et demander à votre service bancaire ou postal de la valider.</span><span class="sxs-lookup"><span data-stu-id="e9055-116">When you have evaluated the setup information, you can adjust the invoice form, and you can create a test series that you can ask your bank or postal service to validate.</span></span>  

<span data-ttu-id="e9055-117">Lorsque vous paramétrez des souches de numéros pour des factures, vous devez respecter les directives suivantes :</span><span class="sxs-lookup"><span data-stu-id="e9055-117">When you set up number series for invoices, you must follow these guidelines:</span></span>  

- <span data-ttu-id="e9055-118">Utilisez un maximum de huit chiffres.</span><span class="sxs-lookup"><span data-stu-id="e9055-118">Use a maximum of eight digits.</span></span>  
- <span data-ttu-id="e9055-119">Utilisez uniquement des caractères numériques.</span><span class="sxs-lookup"><span data-stu-id="e9055-119">Use only numeric characters.</span></span>  
- <span data-ttu-id="e9055-120">N'utilisez pas de zéros devant les nombres.</span><span class="sxs-lookup"><span data-stu-id="e9055-120">Do not precede numbers with zeros.</span></span>  

## <a name="see-also"></a><span data-ttu-id="e9055-121">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="e9055-121">See Also</span></span>  
 <span data-ttu-id="e9055-122">[Paiements électroniques suisses](swiss-electronic-payments.md) </span><span class="sxs-lookup"><span data-stu-id="e9055-122">[Swiss Electronic Payments](swiss-electronic-payments.md) </span></span>  
 <span data-ttu-id="e9055-123">[Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md) </span><span class="sxs-lookup"><span data-stu-id="e9055-123">[How to: Print ESR Invoices](how-to-print-esr-invoices.md) </span></span>  
 <span data-ttu-id="e9055-124">[Procédure : importer des paiements BVR](how-to-import-esr-payments.md) </span><span class="sxs-lookup"><span data-stu-id="e9055-124">[How to: Import ESR Payments](how-to-import-esr-payments.md) </span></span>  
 <span data-ttu-id="e9055-125">[Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md) </span><span class="sxs-lookup"><span data-stu-id="e9055-125">[Swiss Electronic Payments Using DTA](swiss-electronic-payments-using-dta.md) </span></span>  
 <span data-ttu-id="e9055-126">[Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md) </span><span class="sxs-lookup"><span data-stu-id="e9055-126">[Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md) </span></span>  
 [<span data-ttu-id="e9055-127">Exécution de paiements</span><span class="sxs-lookup"><span data-stu-id="e9055-127">Making Payments</span></span>](../../payables-make-payments.md)

