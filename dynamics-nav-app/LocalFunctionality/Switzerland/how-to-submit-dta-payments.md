---
title: "Procédure : soumettre des paiements DTA"
description: "Pour soumettre des paiements DTA (DatenTrägerAustausch) à votre banque pour paiement, vous devez exécuter certaines tâches."
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
ms.openlocfilehash: 81e10c740ffe491338fc1d94fea6ef00ec930d3c
ms.contentlocale: fr-ch
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-submit-dta-payments"></a><span data-ttu-id="fd08c-103">Procédure : soumettre des paiements DTA</span><span class="sxs-lookup"><span data-stu-id="fd08c-103">How to: Submit DTA Payments</span></span>
<span data-ttu-id="fd08c-104">Pour soumettre des paiements DTA (DatenTrägerAustausch) à votre banque pour paiement, vous devez exécuter les actions suivantes :</span><span class="sxs-lookup"><span data-stu-id="fd08c-104">To submit DatenTrägerAustausch (DTA) payments to your bank for payment, you must do the following:</span></span>  

- <span data-ttu-id="fd08c-105">Générer un fichier DTA pour paiement électronique après impression de l'avis de paiement.</span><span class="sxs-lookup"><span data-stu-id="fd08c-105">Generate a DTA file for electronic payment after printing the payment advice.</span></span>  
- <span data-ttu-id="fd08c-106">Imprimer l’ordre de paiement DTA.</span><span class="sxs-lookup"><span data-stu-id="fd08c-106">Print the DTA payment order.</span></span>  

<span data-ttu-id="fd08c-107">Avant de soumettre des paiements DTA, vous devez vérifier la liste des fournisseurs pour paiement DTA.</span><span class="sxs-lookup"><span data-stu-id="fd08c-107">Before you submit DTA payments, you must verify the list of vendors for DTA payment.</span></span> <span data-ttu-id="fd08c-108">Pour plus d'informations, voir la rubrique [Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md).</span><span class="sxs-lookup"><span data-stu-id="fd08c-108">For more information, see [How to: Verify a List of Vendors for DTA Payments](how-to-verify-a-list-of-vendors-for-dta-payments.md).</span></span>  

<span data-ttu-id="fd08c-109">Vous pouvez valider la feuille paiement une fois que les paiements bancaires sont finalisés.</span><span class="sxs-lookup"><span data-stu-id="fd08c-109">You can post the payment journal after the bank payments are complete.</span></span> <span data-ttu-id="fd08c-110">Dans la feuille paiement, il est possible que les paiements DTA soient suggérés sur la base des factures validées.</span><span class="sxs-lookup"><span data-stu-id="fd08c-110">In the payment journal, you can have the DTA payments suggested based on posted invoices.</span></span> <span data-ttu-id="fd08c-111">Les paiements suggérés contiennent des informations sur le numéro de document externe et le fournisseur, et peuvent être modifiés.</span><span class="sxs-lookup"><span data-stu-id="fd08c-111">The suggested payments contain vendor and external document number information, and can be modified.</span></span> <span data-ttu-id="fd08c-112">Pour plus d'informations, voir la rubrique [Procédure : Proposer paiement DTA pour les fournisseurs](how-to-suggest-dta-payment-for-vendors.md).</span><span class="sxs-lookup"><span data-stu-id="fd08c-112">For more information, see [How to: Suggest DTA Payment for Vendors](how-to-suggest-dta-payment-for-vendors.md).</span></span>  

## <a name="to-generate-a-dta-file"></a><span data-ttu-id="fd08c-113">Pour générer un fichier DTA</span><span class="sxs-lookup"><span data-stu-id="fd08c-113">To generate a DTA file</span></span>  

1.  <span data-ttu-id="fd08c-114">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles paiement**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="fd08c-114">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="fd08c-115">Dans le champ **Nom de la feuille**, sélectionnez le nom de la feuille requis.</span><span class="sxs-lookup"><span data-stu-id="fd08c-115">In the **Batch Name** field, select the required journal batch.</span></span>  
3.  <span data-ttu-id="fd08c-116">Sélectionnez l'écriture paiement que vous souhaitez générer en tant que fichier DTA, puis choisissez l'action **Écrire fichier DTA**.</span><span class="sxs-lookup"><span data-stu-id="fd08c-116">Select the payment entry that you want to generate as a DTA file, and then choose the **Generate DTA File** action.</span></span>  
4.  <span data-ttu-id="fd08c-117">Dans le traitement par lots **Fichier DTA**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="fd08c-117">In the **DTA File** batch job, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="fd08c-118">Champ</span><span class="sxs-lookup"><span data-stu-id="fd08c-118">Field</span></span>|<span data-ttu-id="fd08c-119">Description</span><span class="sxs-lookup"><span data-stu-id="fd08c-119">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="fd08c-120">**Banque DTA pour fichier**</span><span class="sxs-lookup"><span data-stu-id="fd08c-120">**DTA Bank for File**</span></span>|<span data-ttu-id="fd08c-121">Sélectionnez le code banque DTA à partir duquel les informations sur le nom de fichier et la copie de sauvegarde doivent être transférées.</span><span class="sxs-lookup"><span data-stu-id="fd08c-121">Select the DTA bank code from which the information for the file name and backup copy is to be transferred.</span></span> <span data-ttu-id="fd08c-122">Ce champ utilise le nom de la banque principale comme valeur par défaut, mais vous pouvez modifier cette information au besoin.</span><span class="sxs-lookup"><span data-stu-id="fd08c-122">This field uses the main bank name as the default, but you can modify this information if you want.</span></span>|  
    |<span data-ttu-id="fd08c-123">**Totaliser par fournisseur**</span><span class="sxs-lookup"><span data-stu-id="fd08c-123">**Combined payment for vendor**</span></span>|<span data-ttu-id="fd08c-124">Spécifiez si les lignes paiement présentant les mêmes fournisseur, devise, banque et banque à débiter seront combinées dans le fichier DTA généré.</span><span class="sxs-lookup"><span data-stu-id="fd08c-124">Specify if the payment lines that have the same vendor, currency, bank, and debit bank will be combined in the generated DTA file.</span></span>|  

5.  <span data-ttu-id="fd08c-125">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="fd08c-125">Choose the **OK** button.</span></span> <span data-ttu-id="fd08c-126">Le fichier DTA est généré dans le dossier prédéterminé.</span><span class="sxs-lookup"><span data-stu-id="fd08c-126">The DTA file is generated in the predetermined folder.</span></span>  

<span data-ttu-id="fd08c-127">Après avoir généré le fichier DTA, vous pouvez imprimer l'ordre de paiement DTA et transférer le fichier et l'ordre de paiement à votre banque.</span><span class="sxs-lookup"><span data-stu-id="fd08c-127">After you have generated the DTA file, you can print the DTA payment order and transfer both the file and the payment order to your bank.</span></span> <span data-ttu-id="fd08c-128">L'ordre de paiement DTA répertorie tous les paiements fournisseur proposés dans une fenêtre **Feuille paiement** en fonction du code devise.</span><span class="sxs-lookup"><span data-stu-id="fd08c-128">The DTA payment order lists all suggested vendor payments in a **Payment Journal** window based on currency code.</span></span> <span data-ttu-id="fd08c-129">Cet ordre est envoyé à la banque pour libérer le fichier DTA pour paiement.</span><span class="sxs-lookup"><span data-stu-id="fd08c-129">This order is sent to the bank to release the DTA file for payment.</span></span>  

## <a name="to-print-a-dta-payment-order"></a><span data-ttu-id="fd08c-130">Pour imprimer un ordre de paiement DTA</span><span class="sxs-lookup"><span data-stu-id="fd08c-130">To print a DTA payment order</span></span>  

1.  <span data-ttu-id="fd08c-131">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles paiement**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="fd08c-131">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="fd08c-132">Dans le champ **Nom de la feuille**, sélectionnez le nom de la feuille requis.</span><span class="sxs-lookup"><span data-stu-id="fd08c-132">In the **Batch Name** field, select the required journal batch.</span></span>  
3.  <span data-ttu-id="fd08c-133">Sélectionnez l'écriture paiement requise, puis choisissez l'action **Ordre de paiement DTA**.</span><span class="sxs-lookup"><span data-stu-id="fd08c-133">Select the required payment entry, and then choose the **DTA Payment Order** action.</span></span>  
4.  <span data-ttu-id="fd08c-134">Dans le champ **Message**, entrez un message pour la banque, qui sera imprimé dans le bas de l'ordre de paiement.</span><span class="sxs-lookup"><span data-stu-id="fd08c-134">In the **Message** field, enter a message for the bank, to be printed at the bottom of the payment order.</span></span>  
5.  <span data-ttu-id="fd08c-135">Choisissez le bouton **Imprimer** pour imprimer l'ordre de paiement DTA ou le bouton **Aperçu** pour l'afficher à l'écran.</span><span class="sxs-lookup"><span data-stu-id="fd08c-135">Choose the **Print** button to print the DTA payment order or choose the **Preview** button to view it on the screen.</span></span>  

    <span data-ttu-id="fd08c-136">Vous devez soumettre l'ordre de paiement DTA et le fichier DTA à la banque, où les paiements aux fournisseurs sont libérés en quelques heures.</span><span class="sxs-lookup"><span data-stu-id="fd08c-136">You must submit the DTA payment order and the DTA file to the bank, where payments to the vendors are released in a few hours.</span></span> <span data-ttu-id="fd08c-137">Après que les paiements ont été traités par la banque, vous pouvez valider la feuille paiement.</span><span class="sxs-lookup"><span data-stu-id="fd08c-137">After the payments have been processed by the bank, you can post the payment journal.</span></span>  

## <a name="see-also"></a><span data-ttu-id="fd08c-138">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="fd08c-138">See Also</span></span>  
 <span data-ttu-id="fd08c-139">[Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md) </span><span class="sxs-lookup"><span data-stu-id="fd08c-139">[Swiss Electronic Payments Using DTA](swiss-electronic-payments-using-dta.md) </span></span>  
 <span data-ttu-id="fd08c-140">[Procédure : Proposer paiement DTA pour les fournisseurs](how-to-suggest-dta-payment-for-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="fd08c-140">[How to: Suggest DTA Payment for Vendors](how-to-suggest-dta-payment-for-vendors.md) </span></span>  
 <span data-ttu-id="fd08c-141">[Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span><span class="sxs-lookup"><span data-stu-id="fd08c-141">[How to: Verify a List of Vendors for DTA Payments](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span></span>  
 [<span data-ttu-id="fd08c-142">Procédure : exporter des paiements avec OPAE</span><span class="sxs-lookup"><span data-stu-id="fd08c-142">How to: Export Payments Using EZAG</span></span>](how-to-export-payments-using-ezag.md)

