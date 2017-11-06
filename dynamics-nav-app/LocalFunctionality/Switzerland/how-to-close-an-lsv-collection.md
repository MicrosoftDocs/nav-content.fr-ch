---
title: "Procédure : clôturer un recouvrement LSV"
description: "Vous devez clôturer les recouvrements LSV+ (Lastschrift Verfahren) pour écrire des fichiers LSV qu'il est possible d'envoyer à la banque pour recouvrement de paiement. Lorsque vous clôturez un recouvrement, celui-ci est complet, et les validations dans la feuille LSV sont combinées."
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
ms.openlocfilehash: 2f0275f75c67839c373f8abe574d539b6763d408
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-close-an-lsv-collection"></a><span data-ttu-id="93661-104">Procédure : clôturer un recouvrement LSV</span><span class="sxs-lookup"><span data-stu-id="93661-104">How to: Close an LSV Collection</span></span>
<span data-ttu-id="93661-105">Vous devez clôturer les recouvrements LSV+ (Lastschrift Verfahren) pour écrire des fichiers LSV qu'il est possible d'envoyer à la banque pour recouvrement de paiement.</span><span class="sxs-lookup"><span data-stu-id="93661-105">You must close Lastschrift Verfahren (LSV+) collections to write LSV files that can be sent to the bank for payment collection.</span></span> <span data-ttu-id="93661-106">Lorsque vous clôturez un recouvrement, celui-ci est complet, et les validations dans la feuille LSV sont combinées.</span><span class="sxs-lookup"><span data-stu-id="93661-106">When you close a collection, the collection is complete, and the postings in the LSV journal are combined.</span></span>  

<span data-ttu-id="93661-107">Lorsque le recouvrement est complet, le numéro de recouvrement actuel est assigné dans la feuille LSV, en fonction du dernier recouvrement.</span><span class="sxs-lookup"><span data-stu-id="93661-107">When the collection is complete, the current collection number is assigned in the LSV journal, based on the last collection.</span></span> <span data-ttu-id="93661-108">Ce numéro LSV est transféré aux écritures client pour toutes les factures en attente.</span><span class="sxs-lookup"><span data-stu-id="93661-108">This LSV number is transferred to the customer entries for all outstanding invoices.</span></span> <span data-ttu-id="93661-109">Le fichier de recouvrement peut être reconstitué à tout moment à l'aide du numéro LSV.</span><span class="sxs-lookup"><span data-stu-id="93661-109">The collection file can be reconstructed at any time using the LSV number.</span></span> <span data-ttu-id="93661-110">Le champ **En attente** est également renseigné avec **LSV** dans les écritures client pour éviter la duplication d'écritures ouvertes.</span><span class="sxs-lookup"><span data-stu-id="93661-110">The **On Hold** field is also populated with **LSV** in the customer entries to avoid the duplication of open entries.</span></span> <span data-ttu-id="93661-111">Pour plus d'informations, consultez les tables **Feuille LSV** et **Écriture comptable client**.</span><span class="sxs-lookup"><span data-stu-id="93661-111">For more information, see the **LSV Journal** table and the **Cust. Ledger Entry** table.</span></span> <span data-ttu-id="93661-112">Vous pouvez également rouvrir un recouvrement clôturé.</span><span class="sxs-lookup"><span data-stu-id="93661-112">You can also reopen a closed collection.</span></span>  

## <a name="to-close-an-lsv-collection"></a><span data-ttu-id="93661-113">Pour clôturer un recouvrement LSV</span><span class="sxs-lookup"><span data-stu-id="93661-113">To close an LSV collection</span></span>  

1.  <span data-ttu-id="93661-114">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Liste feuilles LSV**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="93661-114">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **LSV Journal List**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="93661-115">Sélectionnez la ligne feuille requise, puis choisissez l'action **Modifier date comptabilisation**.</span><span class="sxs-lookup"><span data-stu-id="93661-115">Select the required journal line, and then choose the **Modify Posting Date** action.</span></span> <span data-ttu-id="93661-116">Cela modifiera la valeur du champ **Date-valeur** par la valeur suggérée pendant le recouvrement LSV.</span><span class="sxs-lookup"><span data-stu-id="93661-116">This will modify the value in the **Credit Date** field by using the value suggested during the LSV collection.</span></span>  
3.  <span data-ttu-id="93661-117">Dans le champ **Nouvelle date**, entrez la nouvelle date.</span><span class="sxs-lookup"><span data-stu-id="93661-117">In the **New Date** field, enter the new date.</span></span>  
4.  <span data-ttu-id="93661-118">Choisissez l'action **Clôturer recouvrement**.</span><span class="sxs-lookup"><span data-stu-id="93661-118">Choose the **Close Collection* action*.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="93661-119">Les champs sous le raccourci **Options** pour le traitement par lots **Clôturer LSV** ne peuvent pas être modifiés et correspondent à la ligne feuille sélectionnée.</span><span class="sxs-lookup"><span data-stu-id="93661-119">The fields on the **Options** FastTab for the **LSV Close Collection** batch job cannot be modified, and correspond to the selected journal line.</span></span>  

5.  <span data-ttu-id="93661-120">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="93661-120">Choose the **OK** button.</span></span>  

    <span data-ttu-id="93661-121">Dans la fenêtre **Liste feuilles LSV**, la valeur du champ **Statut LSV** est modifiée de **Modifier** en **Lancé**.</span><span class="sxs-lookup"><span data-stu-id="93661-121">In the **LSV Journal List** window, the value in the **LSV Status** field is changed from **Edit** to **Released**.</span></span> <span data-ttu-id="93661-122">Les lignes feuille ne peuvent plus être modifiées.</span><span class="sxs-lookup"><span data-stu-id="93661-122">The journal lines can no longer be modified.</span></span>  

## <a name="to-reopen-an-lsv-collection"></a><span data-ttu-id="93661-123">Pour rouvrir un recouvrement LSV</span><span class="sxs-lookup"><span data-stu-id="93661-123">To reopen an LSV collection</span></span>  

1.  <span data-ttu-id="93661-124">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Liste feuilles LSV**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="93661-124">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **LSV Journal List**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="93661-125">Sélectionnez la ligne feuille requise pour laquelle vous souhaitez rouvrir le recouvrement, puis choisissez l'action **Rouvrir le recouvrement**.</span><span class="sxs-lookup"><span data-stu-id="93661-125">Select the required journal line for which you want to reopen the collection, on then choose the **Reopen Collection** action.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="93661-126">Vous ne pouvez rouvrir le recouvrement que si vous n'avez pas encore soumis le fichier LSV+ à la banque.</span><span class="sxs-lookup"><span data-stu-id="93661-126">You can only reopen the collection if you have not yet submitted the LSV+ file to the bank.</span></span>  

3.  <span data-ttu-id="93661-127">Choisissez le bouton **Oui** pour confirmer la réouverture du recouvrement.</span><span class="sxs-lookup"><span data-stu-id="93661-127">Choose the **Yes** button to confirm the reopening of the collection.</span></span>  

## <a name="see-also"></a><span data-ttu-id="93661-128">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="93661-128">See Also</span></span>  
 <span data-ttu-id="93661-129">[Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md) </span><span class="sxs-lookup"><span data-stu-id="93661-129">[Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md) </span></span>  
 <span data-ttu-id="93661-130">[Procédure : traiter un recouvrement LSV](how-to-process-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="93661-130">[How to: Process an LSV Collection](how-to-process-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="93661-131">[Procédure : valider des paiements LSV+](how-to-post-lsv-payments.md) </span><span class="sxs-lookup"><span data-stu-id="93661-131">[How to: Post LSV+ Payments](how-to-post-lsv-payments.md) </span></span>  
 [<span data-ttu-id="93661-132">Procédure : exporter des paiements avec LSV</span><span class="sxs-lookup"><span data-stu-id="93661-132">How to: Export Payments Using LSV</span></span>](how-to-export-payments-using-lsv.md)

