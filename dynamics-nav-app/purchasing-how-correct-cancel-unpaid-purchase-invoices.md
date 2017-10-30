---
title: "Corriger ou annuler des factures achat impayées"
description: "Explique comment corriger ou annuler une facture achat validée et créer automatiquement un avoir achat."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: undo, credit memo, return
ms.date: 08/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 294094f8483f9b51d47ad614b8702b289b9d1862
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-correct-or-cancel-unpaid-purchase-invoices"></a><span data-ttu-id="dce48-103">Procédure : corriger ou annuler des factures achat impayées</span><span class="sxs-lookup"><span data-stu-id="dce48-103">How to: Correct or Cancel Unpaid Purchase Invoices</span></span>
<span data-ttu-id="dce48-104">Vous pouvez corriger ou annuler une facture achat validée.</span><span class="sxs-lookup"><span data-stu-id="dce48-104">You can correct or cancel a posted purchase invoice.</span></span> <span data-ttu-id="dce48-105">Cela est utile si vous souhaitez corriger une erreur de saisie, ou si vous souhaitez modifier l'achat assez tôt dans le processus de commande.</span><span class="sxs-lookup"><span data-stu-id="dce48-105">This is useful if you want to correct a typing mistake, or if you want to change the purchase early in the order process.</span></span>

<span data-ttu-id="dce48-106">Si vous avez déjà payé des produits sur la facture achat validée, vous ne pouvez pas la corriger ni l'annuler à partir de la facture achat validée elle-même.</span><span class="sxs-lookup"><span data-stu-id="dce48-106">If you have already paid for products on the posted purchase invoice, you cannot correct or cancel it from the posted purchase invoice itself.</span></span> <span data-ttu-id="dce48-107">Au lieu de cela, vous devez créer manuellement un avoir achat pour contrepasser l'achat, éventuellement géré à l'aide d'un retour achat.</span><span class="sxs-lookup"><span data-stu-id="dce48-107">Instead, you must manually create a purchase credit memo to reverse the purchase, optionally managed with a purchase return order.</span></span> <span data-ttu-id="dce48-108">Pour plus d'informations, reportez-vous à [Procédure : traiter les retours ou annulations d'achats](purchasing-how-process-purchase-returns-cancellations.md).</span><span class="sxs-lookup"><span data-stu-id="dce48-108">For more information, see [How to: Process Purchase Returns or Cancellations](purchasing-how-process-purchase-returns-cancellations.md).</span></span>

<span data-ttu-id="dce48-109">Dans la fenêtre **Facture achat enregistrée**, vous pouvez cliquer sur le bouton **Corriger** ou **Annuler**.</span><span class="sxs-lookup"><span data-stu-id="dce48-109">In the **Posted Purchase Invoice** window, you can choose the **Correct** button or the **Cancel** button.</span></span> <span data-ttu-id="dce48-110">Lorsque vous corrigez ou annulez une facture achat enregistrée, l'avoir achat de correction est appliqué à toutes les écritures comptables de la comptabilité et de l'inventaire créées lors de la validation de la facture achat initiale.</span><span class="sxs-lookup"><span data-stu-id="dce48-110">When you correct or cancel a posted purchase invoice, the corrective purchase credit memo is applied to all general ledger and inventory ledger entries that were created when the initial purchase invoice was posted.</span></span> <span data-ttu-id="dce48-111">Cette action contrepasse la facture achat validée dans vos enregistrements financiers et laisse l'avoir achat validé de correction pour votre piste d'audit.</span><span class="sxs-lookup"><span data-stu-id="dce48-111">This reverses the posted purchase invoice in your financial records and leaves the corrective posted purchase credit memo for your audit trail.</span></span> <span data-ttu-id="dce48-112">L'utilisation des boutons **Corriger** et **Annuler** est décrite ci-après.</span><span class="sxs-lookup"><span data-stu-id="dce48-112">In the following the use of **Correct** and **Cancel** is described.</span></span>

## <a name="to-correct-a-posted-purchase-invoice"></a><span data-ttu-id="dce48-113">Pour corriger une facture achat validée</span><span class="sxs-lookup"><span data-stu-id="dce48-113">To correct a posted purchase invoice</span></span>
1. <span data-ttu-id="dce48-114">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Factures achat enregistrées**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="dce48-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="dce48-115">Sélectionnez la facture achat validée à corriger.</span><span class="sxs-lookup"><span data-stu-id="dce48-115">Select the posted purchase invoice that you want to correct.</span></span>  

    > [!NOTE]  
>   <span data-ttu-id="dce48-116">Si la case à cocher **Annulé** est activée, vous ne pouvez pas corriger la facture achat validée car elle l'a déjà été, ou a été annulée.</span><span class="sxs-lookup"><span data-stu-id="dce48-116">If the **Canceled** check box is selected, then you cannot correct the posted purchase invoice because it has already been corrected or canceled.</span></span>
3. <span data-ttu-id="dce48-117">Dans la fenêtre **Facture achat enregistrée** sélectionnez **Corriger**.</span><span class="sxs-lookup"><span data-stu-id="dce48-117">In the **Posted Purchase Invoice** window, choose **Correct**.</span></span>

    <span data-ttu-id="dce48-118">Une nouvelle facture achat avec les mêmes informations et dans laquelle vous pouvez apporter une correction est créée.</span><span class="sxs-lookup"><span data-stu-id="dce48-118">A new purchase invoice with the same information is created where you can make the correction.</span></span> <span data-ttu-id="dce48-119">Pour plus d'informations, reportez-vous à [Procédure : enregistrer des achats](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="dce48-119">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span> <span data-ttu-id="dce48-120">La valeur du champ **Annulé** de la facture achat validée initiale devient **Oui**.</span><span class="sxs-lookup"><span data-stu-id="dce48-120">The **Canceled** field on the initial posted purchase invoice is changed to **Yes**.</span></span>

    <span data-ttu-id="dce48-121">Un avoir achat est automatiquement créé et validé pour annuler la facture achat validée initiale.</span><span class="sxs-lookup"><span data-stu-id="dce48-121">A purchase credit memo is automatically created and posted to void the initial posted purchase invoice.</span></span>
4. <span data-ttu-id="dce48-122">Sélectionnez **Afficher un avoir correctif** pour afficher l'avoir achat validé qui annule la facture achat validée initiale.</span><span class="sxs-lookup"><span data-stu-id="dce48-122">Choose **Show Corrective Credit Memo** to view the posted purchase credit memo that voids the initial posted purchase invoice.</span></span>

## <a name="to-cancel-a-posted-purchase-invoice"></a><span data-ttu-id="dce48-123">Pour annuler une facture achat validée</span><span class="sxs-lookup"><span data-stu-id="dce48-123">To cancel a posted purchase invoice</span></span>
1. <span data-ttu-id="dce48-124">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Factures achat enregistrées**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="dce48-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="dce48-125">Sélectionnez la facture achat validée à annuler.</span><span class="sxs-lookup"><span data-stu-id="dce48-125">Select the posted purchase invoice that you want to cancel.</span></span>

    > [!NOTE]  
>   <span data-ttu-id="dce48-126">Si la case à cocher **Annulé** est activée, vous ne pouvez pas annuler la facture achat validée car elle l'a déjà été, ou a été corrigée.</span><span class="sxs-lookup"><span data-stu-id="dce48-126">If the **Canceled** check box is selected, then you cannot cancel the posted purchase invoice because it has already been canceled or corrected.</span></span>
3. <span data-ttu-id="dce48-127">Dans la fenêtre **Facture achat enregistrée** sélectionnez **Annuler**.</span><span class="sxs-lookup"><span data-stu-id="dce48-127">In the **Posted Purchase Invoice** window, choose **Cancel**.</span></span>

    <span data-ttu-id="dce48-128">Un avoir achat est automatiquement créé et validé pour annuler la facture achat validée initiale.</span><span class="sxs-lookup"><span data-stu-id="dce48-128">A purchase credit memo is automatically created and posted to void the initial posted purchase invoice.</span></span> <span data-ttu-id="dce48-129">La valeur du champ **Annulé** de la facture achat validée initiale devient **Oui**.</span><span class="sxs-lookup"><span data-stu-id="dce48-129">The **Canceled** field on the initial posted purchase invoice is changed to **Yes**.</span></span>
4. <span data-ttu-id="dce48-130">Sélectionnez **Afficher un avoir correctif** pour afficher l'avoir achat validé qui annule la facture achat validée initiale.</span><span class="sxs-lookup"><span data-stu-id="dce48-130">Choose **Show Corrective Credit Memo** to view the posted purchase credit memo that voids the initial posted purchase invoice.</span></span>

## <a name="see-also"></a><span data-ttu-id="dce48-131">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="dce48-131">See Also</span></span>
[<span data-ttu-id="dce48-132">Achats</span><span class="sxs-lookup"><span data-stu-id="dce48-132">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="dce48-133">Procédure : enregistrer des achats</span><span class="sxs-lookup"><span data-stu-id="dce48-133">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
<span data-ttu-id="dce48-134">[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="dce48-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
