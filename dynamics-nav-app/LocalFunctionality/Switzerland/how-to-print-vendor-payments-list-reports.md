---
title: "Procédure : imprimer des états Liste des paiements fournisseur"
description: "L'état **Liste des paiements fournisseur** fournit une liste des paiements pour chaque fournisseur. L'état peut trier les paiements, soit par ordre chronologique, soit groupés par fournisseur."
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
ms.openlocfilehash: 7ffec12fdb784a881f6907da7a3b93cdadb9b1b9
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-print-vendor-payments-list-reports"></a><span data-ttu-id="15d14-104">Procédure : imprimer des états Liste des paiements fournisseur</span><span class="sxs-lookup"><span data-stu-id="15d14-104">How to: Print Vendor Payments List Reports</span></span>
<span data-ttu-id="15d14-105">L'état **Liste des paiements fournisseur** fournit une liste des paiements pour chaque fournisseur.</span><span class="sxs-lookup"><span data-stu-id="15d14-105">The **Vendor Payments List** report provides a list of payments for each vendor.</span></span> <span data-ttu-id="15d14-106">L'état peut trier les paiements, soit par ordre chronologique, soit groupés par fournisseur.</span><span class="sxs-lookup"><span data-stu-id="15d14-106">The report can sort payments chronologically or grouped by vendor.</span></span>  
  
### <a name="to-print-the-vendor-payments-list-report"></a><span data-ttu-id="15d14-107">Pour imprimer des états Liste des paiements fournisseur</span><span class="sxs-lookup"><span data-stu-id="15d14-107">To print the vendor payments list report</span></span>  
  
1.  <span data-ttu-id="15d14-108">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Liste des paiements fournisseur**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="15d14-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendor Payments List**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="15d14-109">Sous le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="15d14-109">On the **Options** FastTab, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="15d14-110">Champ</span><span class="sxs-lookup"><span data-stu-id="15d14-110">Field</span></span>|<span data-ttu-id="15d14-111">Description</span><span class="sxs-lookup"><span data-stu-id="15d14-111">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="15d14-112">**Tri**</span><span class="sxs-lookup"><span data-stu-id="15d14-112">**Sorting**</span></span>|<span data-ttu-id="15d14-113">Spécifie l'ordre de tri.</span><span class="sxs-lookup"><span data-stu-id="15d14-113">Specifies the sort order.</span></span> <span data-ttu-id="15d14-114">Vous pouvez trier soit par fournisseur, soit par ordre chronologique.</span><span class="sxs-lookup"><span data-stu-id="15d14-114">You can sort by vendor or chronologically.</span></span> <span data-ttu-id="15d14-115">Si vous triez par fournisseur, vous verrez un sous-total pour chaque fournisseur.</span><span class="sxs-lookup"><span data-stu-id="15d14-115">If you sort by vendor, you will see a subtotal for each vendor.</span></span> <span data-ttu-id="15d14-116">Si vous triez par ordre chronologique, vous ne verrez pas de sous-totaux.</span><span class="sxs-lookup"><span data-stu-id="15d14-116">If you sort chronologically, you will not see subtotals.</span></span>|  
    |<span data-ttu-id="15d14-117">**Mise en page**</span><span class="sxs-lookup"><span data-stu-id="15d14-117">**Layout**</span></span>|<span data-ttu-id="15d14-118">Spécifie la présentation de l'état.</span><span class="sxs-lookup"><span data-stu-id="15d14-118">Specifies the layout of the report.</span></span><br /><br /> <span data-ttu-id="15d14-119">Les résultats peuvent être affichés selon les présentations suivantes :</span><span class="sxs-lookup"><span data-stu-id="15d14-119">The results can be displayed in the following layouts:</span></span><br /><br /> <span data-ttu-id="15d14-120">**Standard**</span><span class="sxs-lookup"><span data-stu-id="15d14-120">**Standard**</span></span><br /> <span data-ttu-id="15d14-121">Affiche le numéro du fournisseur et son nom, avec des détails de comptabilisation, comme le numéro de document et le montant total dans la devise société.</span><span class="sxs-lookup"><span data-stu-id="15d14-121">Displays the vendor number and vendor name, together with posting details, such as the document number and the amount in local currency.</span></span><br /><br /> <span data-ttu-id="15d14-122">**Montants DE**</span><span class="sxs-lookup"><span data-stu-id="15d14-122">**FCY Amounts**</span></span><br /> <span data-ttu-id="15d14-123">Affiche le numéro du fournisseur, son nom, le numéro de document, le statut règlement (O pour Ouvert, PP pour Paiement Partiel et C pour Clôturé), et le montant du paiement.</span><span class="sxs-lookup"><span data-stu-id="15d14-123">Displays the vendor number, vendor name, document number, payment status (O for open, PP for partial payment, and C for closed), and payment amount.</span></span><br /><br /> <span data-ttu-id="15d14-124">**Infos compta.**</span><span class="sxs-lookup"><span data-stu-id="15d14-124">**Posting Info**</span></span><br /> <span data-ttu-id="15d14-125">Affiche le numéro du fournisseur, son nom, le département, le dossier, le code utilisateur et le montant du paiement.</span><span class="sxs-lookup"><span data-stu-id="15d14-125">Displays the vendor number, vendor name, cost center, cost object, user ID, and payment amount.</span></span>|  
  
 <span data-ttu-id="15d14-126">À la fin de l'état, le numéro des paiements traités est affiché.</span><span class="sxs-lookup"><span data-stu-id="15d14-126">At the end of the report, the number of processed payments is displayed.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="15d14-127">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="15d14-127">See Also</span></span>  
 <span data-ttu-id="15d14-128">Liste des paiements fournisseur</span><span class="sxs-lookup"><span data-stu-id="15d14-128">Vendor Payments List</span></span>
