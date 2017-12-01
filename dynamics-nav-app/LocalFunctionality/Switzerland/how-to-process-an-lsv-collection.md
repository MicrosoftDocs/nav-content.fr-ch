---
title: "Procédure : traiter un recouvrement LSV"
description: "Vous pouvez utiliser les **feuilles LSV** pour créer et traiter les paiements des clients LSV+ (Lastschrift Verfahren). Vous pouvez enregistrer ces paiements dans la feuille règlement, créer un fichier LSV, puis imprimer l'ordre de recouvrement."
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
ms.openlocfilehash: e68c61cdfff93b2642714d3d736e139079079665
ms.contentlocale: fr-ch
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-process-an-lsv-collection"></a><span data-ttu-id="ef7e0-104">Procédure : traiter un recouvrement LSV</span><span class="sxs-lookup"><span data-stu-id="ef7e0-104">How to: Process an LSV Collection</span></span>
<span data-ttu-id="ef7e0-105">Vous pouvez utiliser les **feuilles LSV** pour créer et traiter les paiements des clients LSV+ (Lastschrift Verfahren).</span><span class="sxs-lookup"><span data-stu-id="ef7e0-105">You can use **LSV Journals** to create and process payments from Lastschrift Verfahren (LSV+) customers.</span></span> <span data-ttu-id="ef7e0-106">Vous pouvez enregistrer ces paiements dans la feuille règlement, créer un fichier LSV, puis imprimer l'ordre de recouvrement.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-106">You can register these payments in the cash receipt journal, create an LSV file, and then print the collection order.</span></span> <span data-ttu-id="ef7e0-107">Pour plus d'informations, consultez la fenêtre Feuille règlement et [Procédure : exporter des paiements avec LSV](how-to-export-payments-using-lsv.md).</span><span class="sxs-lookup"><span data-stu-id="ef7e0-107">For more information, see the Cash Receipt Journal window and [How to: Export Payments Using LSV](how-to-export-payments-using-lsv.md).</span></span>  

<span data-ttu-id="ef7e0-108">Lorsque vous exécutez le traitement par lots **Proposition de recouvrement LSV**, chaque recouvrement proposé est enregistré sur une ligne feuille LSV, et les factures ouvertes sont transférées dans les feuilles LSV.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-108">When you run the **LSV Suggest Collection** batch job, each suggested collection is registered on an LSV journal line, and the open invoices are transferred to the LSV journals.</span></span> <span data-ttu-id="ef7e0-109">Pour plus d'informations, voir la table Feuille LSV.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-109">For more information, see the LSV Journal table.</span></span>  

<span data-ttu-id="ef7e0-110">Vous pouvez afficher, modifier ou supprimer les lignes paiement proposées.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-110">You can view, edit, or delete the suggested payment lines.</span></span> <span data-ttu-id="ef7e0-111">Si vous corrigez le montant proposé, la différence est marquée comme remise.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-111">If you correct the suggested amount, then the difference is marked as a discount.</span></span> <span data-ttu-id="ef7e0-112">Vous pouvez exécuter le traitement par lots plusieurs fois pour différents groupes de clients.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-112">You can run the batch job multiple times for different customer groups.</span></span> <span data-ttu-id="ef7e0-113">Les lignes proposition peuvent être placées dans la même feuille.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-113">The suggestion lines can be placed in the same journal.</span></span>  

## <a name="to-create-an-lsv-collection"></a><span data-ttu-id="ef7e0-114">Pour créer un recouvrement LSV</span><span class="sxs-lookup"><span data-stu-id="ef7e0-114">To create an LSV collection</span></span>  

1.  <span data-ttu-id="ef7e0-115">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Liste feuilles LSV**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-115">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **LSV Journal List**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="ef7e0-116">Choisissez l'action **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-116">Choose the **New** action.</span></span>  
3.  <span data-ttu-id="ef7e0-117">Dans la fenêtre **Liste feuilles LSV**, complétez les champs requis comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-117">In the **LSV Journal List** window, fill in the required fields as described in the following table.</span></span>  

    |<span data-ttu-id="ef7e0-118">Champ</span><span class="sxs-lookup"><span data-stu-id="ef7e0-118">Field</span></span>|<span data-ttu-id="ef7e0-119">Description</span><span class="sxs-lookup"><span data-stu-id="ef7e0-119">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="ef7e0-120">**Code banque LSV**</span><span class="sxs-lookup"><span data-stu-id="ef7e0-120">**LSV Bank Code**</span></span>|<span data-ttu-id="ef7e0-121">Sélectionnez le code banque LSV de la banque qui exécutera le recouvrement.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-121">Select the LSV bank code for the bank that will perform the collection.</span></span>|  
    |<span data-ttu-id="ef7e0-122">**Description de feuille LSV**</span><span class="sxs-lookup"><span data-stu-id="ef7e0-122">**LSV Journal Description**</span></span>|<span data-ttu-id="ef7e0-123">Entrez une description pour l'écriture.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-123">Enter a description for the entry.</span></span>|

4.  <span data-ttu-id="ef7e0-124">Sélectionnez l'écriture feuille LSV requise, puis choisissez l'action **Proposition de recouvrement LSV** pour créer les paiements dont le recouvrement se fera automatiquement par LSV+.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-124">Select the required LSV journal entry, and then choose the **LSV Suggest Collection** action to create the payments to be collected automatically by LSV+.</span></span>  
5.  <span data-ttu-id="ef7e0-125">Dans la fenêtre **Proposition de recouvrement LSV**, sur le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-125">In the **LSV Suggest Collection** window, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="ef7e0-126">Champ</span><span class="sxs-lookup"><span data-stu-id="ef7e0-126">Field</span></span>|<span data-ttu-id="ef7e0-127">Description</span><span class="sxs-lookup"><span data-stu-id="ef7e0-127">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="ef7e0-128">**N°**</span><span class="sxs-lookup"><span data-stu-id="ef7e0-128">**No.**</span></span>|<span data-ttu-id="ef7e0-129">Entrez le numéro de la feuille LSV.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-129">Enter the LSV journal number.</span></span>|  
    |<span data-ttu-id="ef7e0-130">**Date d'échéance début**</span><span class="sxs-lookup"><span data-stu-id="ef7e0-130">**From due date**</span></span>|<span data-ttu-id="ef7e0-131">Spécifiez la date d'échéance de début des écritures ouvertes à proposer pour le recouvrement.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-131">Specify the starting due date of open entries to be suggested for collection.</span></span>|  
    |<span data-ttu-id="ef7e0-132">**Date d'échéance fin**</span><span class="sxs-lookup"><span data-stu-id="ef7e0-132">**To due date**</span></span>|<span data-ttu-id="ef7e0-133">Spécifiez la date d'échéance de fin des écritures ouvertes à proposer pour le recouvrement.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-133">Specify the ending due date of open entries to be suggested for collection.</span></span>|  
    |<span data-ttu-id="ef7e0-134">**Date de recouvrement**</span><span class="sxs-lookup"><span data-stu-id="ef7e0-134">**Collection date**</span></span>|<span data-ttu-id="ef7e0-135">Spécifiez la date de clôture du recouvrement.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-135">Specify the date on which the collection closes.</span></span> <span data-ttu-id="ef7e0-136">L'ordre LSV+ doit être soumis au moins trois jours bancaires avant la date du recouvrement.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-136">The LSV+ order must be submitted at least three banking days before the collection date.</span></span>|  

6.  <span data-ttu-id="ef7e0-137">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-137">Choose the **OK** button.</span></span>  

<span data-ttu-id="ef7e0-138">Toutes les lignes associées sont transférées à la feuille LSV.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-138">All related lines are transferred to the LSV journal.</span></span> <span data-ttu-id="ef7e0-139">Après le traitement du recouvrement LSV, vous pouvez afficher, vérifier ou modifier les paiements proposés dans la fenêtre **Feuille LSV**.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-139">After processing the LSV collection, you can view, check, or edit the suggested payments in the **LSV Journal** window.</span></span> <span data-ttu-id="ef7e0-140">Pour plus d'informations, voir la table Ligne feuille LSV.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-140">For more information, see the LSV Journal Line table.</span></span>  

## <a name="to-manage-suggested-payments"></a><span data-ttu-id="ef7e0-141">Pour gérer les paiements proposés</span><span class="sxs-lookup"><span data-stu-id="ef7e0-141">To manage suggested payments</span></span>  

1.  <span data-ttu-id="ef7e0-142">Dans la fenêtre **Liste feuilles LSV**, sélectionnez l'écriture feuille requise, puis choisissez l'action **Ligne feuille LSV**.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-142">In the **LSV Journal List** window, select the required journal entry, and then choose the **LSV Journal Line** action.</span></span>  

    <span data-ttu-id="ef7e0-143">Vous pouvez afficher et modifier les paiements proposés dans cette fenêtre.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-143">You can view and modify the suggested payments in this window.</span></span> <span data-ttu-id="ef7e0-144">Vous pouvez entrer les paiements requis manuellement.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-144">You can enter the required payments manually.</span></span> <span data-ttu-id="ef7e0-145">Pour les nouvelles lignes feuille, le champ **Statut LSV** est défini sur **Ouvert** pour indiquer que la facture est impayée.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-145">For new journal lines, the **LSV Status** field is set to **Open** to indicate that the invoice is unpaid.</span></span>  

3.  <span data-ttu-id="ef7e0-146">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="ef7e0-146">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="ef7e0-147">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="ef7e0-147">See Also</span></span>  
 <span data-ttu-id="ef7e0-148">[Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md) </span><span class="sxs-lookup"><span data-stu-id="ef7e0-148">[Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md) </span></span>  
 <span data-ttu-id="ef7e0-149">[Procédure : clôturer un recouvrement LSV](how-to-close-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="ef7e0-149">[How to: Close an LSV Collection](how-to-close-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="ef7e0-150">[Procédure : valider des paiements LSV+](how-to-post-lsv-payments.md) </span><span class="sxs-lookup"><span data-stu-id="ef7e0-150">[How to: Post LSV+ Payments](how-to-post-lsv-payments.md) </span></span>  
 [<span data-ttu-id="ef7e0-151">Procédure : exporter des paiements avec LSV</span><span class="sxs-lookup"><span data-stu-id="ef7e0-151">How to: Export Payments Using LSV</span></span>](how-to-export-payments-using-lsv.md)

