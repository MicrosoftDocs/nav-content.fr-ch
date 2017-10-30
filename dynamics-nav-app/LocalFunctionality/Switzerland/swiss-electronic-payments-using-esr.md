---
title: "Paiements électroniques suisses avec BVR"
description: "La méthode de paiement électronique BVR (bulletin de versement avec numéro de référence) est un service de débiteur électronique qui permet au client de facturer des factures ouvertes en francs suisses (CHF) et en euros (EUR), et de valider les paiements entrants de manière efficace. Le numéro de référence, ou la ligne code, contient toutes les données comptables pertinentes."
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
ms.openlocfilehash: 9063443b4efc8275aa487406c8c34f00d6b52782
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="swiss-electronic-payments-using-esr"></a><span data-ttu-id="96c0a-104">Paiements électroniques suisses avec BVR</span><span class="sxs-lookup"><span data-stu-id="96c0a-104">Swiss Electronic Payments Using ESR</span></span>
<span data-ttu-id="96c0a-105">La méthode de paiement électronique BVR (bulletin de versement avec numéro de référence) est un service de débiteur électronique qui permet au client de facturer des factures ouvertes en francs suisses (CHF) et en euros (EUR), et de valider les paiements entrants de manière efficace.</span><span class="sxs-lookup"><span data-stu-id="96c0a-105">The Einzahlungsschein mit Referenznummer (ESR) electronic payment method is an electronic debtor service that allows the customer to bill open invoices in Swiss Francs (CHF) and Euros (EUR), and to post incoming payments efficiently.</span></span> <span data-ttu-id="96c0a-106">Le numéro de référence, ou la ligne code, contient toutes les données comptables pertinentes.</span><span class="sxs-lookup"><span data-stu-id="96c0a-106">The reference number, or code line, contains all relevant bookkeeping data.</span></span>  
  
 <span data-ttu-id="96c0a-107">Avec les paiements électroniques BVR, vous pouvez réaliser les opérations suivantes :</span><span class="sxs-lookup"><span data-stu-id="96c0a-107">With ESR electronic payments, you can do the following:</span></span>  
  
-   <span data-ttu-id="96c0a-108">Envoyer des bordereaux de paiement BVR avec des numéros de référence uniques sur les factures.</span><span class="sxs-lookup"><span data-stu-id="96c0a-108">Send ESR payment slips with unique reference numbers on the invoices.</span></span> <span data-ttu-id="96c0a-109">En raison des numéros de références BVR uniques, les paiements pour déclaration sont automatiquement appliqués aux factures respectives.</span><span class="sxs-lookup"><span data-stu-id="96c0a-109">Because of the unique ESR reference numbers, the payments for settlement are automatically applied to the related invoices.</span></span> <span data-ttu-id="96c0a-110">Pour plus d'informations, voir la rubrique [Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md).</span><span class="sxs-lookup"><span data-stu-id="96c0a-110">For more information, see [How to: Print ESR Invoices](how-to-print-esr-invoices.md).</span></span>  
  
-   <span data-ttu-id="96c0a-111">Télécharger les fichiers BVR au départ de la banque chaque jour.</span><span class="sxs-lookup"><span data-stu-id="96c0a-111">Download the ESR files from the bank daily.</span></span> <span data-ttu-id="96c0a-112">Les fichiers contiennent des informations sur toutes les factures payées.</span><span class="sxs-lookup"><span data-stu-id="96c0a-112">The files contain information about all paid invoices.</span></span>  
  
-   <span data-ttu-id="96c0a-113">Importer les fichiers BVR et créer des lignes paiement automatiquement pour chaque paiement.</span><span class="sxs-lookup"><span data-stu-id="96c0a-113">Import the ESR files and create payment lines automatically for each payment.</span></span> <span data-ttu-id="96c0a-114">Pour plus d'informations, voir la rubrique [Procédure : importer des paiements BVR](how-to-import-esr-payments.md).</span><span class="sxs-lookup"><span data-stu-id="96c0a-114">For more information, see [How to: Import ESR Payments](how-to-import-esr-payments.md).</span></span>  
  
> [!NOTE]  
>  <span data-ttu-id="96c0a-115">Avant de pouvoir utiliser le module BVR, vous devez paramétrer la banque, le compte bancaire et le nom de fichier.</span><span class="sxs-lookup"><span data-stu-id="96c0a-115">Before you can use the ESR module, you must set up the bank, bank account, and file name.</span></span> <span data-ttu-id="96c0a-116">Vous devez également spécifier si la méthode BVR ou BVR+ sera utilisée.</span><span class="sxs-lookup"><span data-stu-id="96c0a-116">You must also specify whether ESR or ESR+ should be used.</span></span> <span data-ttu-id="96c0a-117">Pour plus d'informations, voir la table Paramètres BVR.</span><span class="sxs-lookup"><span data-stu-id="96c0a-117">For more information, see the ESR Setup table.</span></span>  
  
 <span data-ttu-id="96c0a-118">Une fois que vous avez évalué les informations de configuration, vous pouvez ajuster le formulaire facture et créer une souche test et demander à votre service bancaire ou postal de la valider.</span><span class="sxs-lookup"><span data-stu-id="96c0a-118">When you have evaluated the setup information, you can adjust the invoice form, and you can create a test series that you can ask your bank or postal service to validate.</span></span>  
  
 <span data-ttu-id="96c0a-119">Lorsque vous paramétrez des souches de numéros pour des factures, vous devez respecter les directives suivantes :</span><span class="sxs-lookup"><span data-stu-id="96c0a-119">When you set up number series for invoices, you must follow these guidelines:</span></span>  
  
-   <span data-ttu-id="96c0a-120">Utilisez un maximum de huit chiffres.</span><span class="sxs-lookup"><span data-stu-id="96c0a-120">Use a maximum of eight digits.</span></span>  
  
-   <span data-ttu-id="96c0a-121">Utilisez uniquement des caractères numériques.</span><span class="sxs-lookup"><span data-stu-id="96c0a-121">Use only numeric characters.</span></span>  
  
-   <span data-ttu-id="96c0a-122">N'utilisez pas de zéros devant les nombres.</span><span class="sxs-lookup"><span data-stu-id="96c0a-122">Do not precede numbers with zeros.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="96c0a-123">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="96c0a-123">See Also</span></span>  
 <span data-ttu-id="96c0a-124">[Paiements électroniques suisses](swiss-electronic-payments.md) </span><span class="sxs-lookup"><span data-stu-id="96c0a-124">[Swiss Electronic Payments](swiss-electronic-payments.md) </span></span>  
 <span data-ttu-id="96c0a-125">[Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md) </span><span class="sxs-lookup"><span data-stu-id="96c0a-125">[How to: Print ESR Invoices](how-to-print-esr-invoices.md) </span></span>  
 <span data-ttu-id="96c0a-126">[Procédure : importer des paiements BVR](how-to-import-esr-payments.md) </span><span class="sxs-lookup"><span data-stu-id="96c0a-126">[How to: Import ESR Payments](how-to-import-esr-payments.md) </span></span>  
 <span data-ttu-id="96c0a-127">[Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md) </span><span class="sxs-lookup"><span data-stu-id="96c0a-127">[Swiss Electronic Payments Using DTA](swiss-electronic-payments-using-dta.md) </span></span>  
 <span data-ttu-id="96c0a-128">[Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md) </span><span class="sxs-lookup"><span data-stu-id="96c0a-128">[Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md) </span></span>  
 <span data-ttu-id="96c0a-129">Paramètres BVR</span><span class="sxs-lookup"><span data-stu-id="96c0a-129">ESR Setup</span></span>   
 <span data-ttu-id="96c0a-130">N°</span><span class="sxs-lookup"><span data-stu-id="96c0a-130">No.</span></span> <span data-ttu-id="96c0a-131">Souches</span><span class="sxs-lookup"><span data-stu-id="96c0a-131">Series</span></span>
