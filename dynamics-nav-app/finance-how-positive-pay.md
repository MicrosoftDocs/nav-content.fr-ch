---
title: Exporter les fichiers Positive Pay
description: "Vous pouvez vous assurer que la banque efface uniquement les chèques et les montants validés en exportant un fichier Positive Pay contenant des informations de paiement et fournisseur."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: check, clearing
ms.date: 06/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: bf09817e318b5338da0358f829ea2ed1edde9d67
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-a-positive-pay-file"></a><span data-ttu-id="2d6b7-103">Procédure : exporter des fichiers Positive Pay</span><span class="sxs-lookup"><span data-stu-id="2d6b7-103">How to: Export a Positive Pay file</span></span>
<span data-ttu-id="2d6b7-104">Pour vous assurer que votre banque efface uniquement les chèques et les montants validés, vous pouvez exporter un fichier Positive Pay contenant des informations fournisseur, un numéro de chèque, un montant de paiement que vous envoyez à la banque pour référence lorsque vous traitez les paiements.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-104">To make sure that your bank only clears validated checks and amounts, you can export a Positive Pay file that contains vendor information, check number, and payment amount, which you send to the bank for reference when you process payments.</span></span>

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="2d6b7-105"> est préconfiguré pour prendre en charge les fichiers Positive Pay de la Bank of America et de la City Bank.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-105"> is preconfigured to support Positive Pay files for Bank of America and City Bank.</span></span>

## <a name="to-set-up-a-bank-account-for-positive-pay"></a><span data-ttu-id="2d6b7-106">Pour configurer une banque pour Positive Pay</span><span class="sxs-lookup"><span data-stu-id="2d6b7-106">To set up a bank account for Positive Pay</span></span>
1. <span data-ttu-id="2d6b7-107">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Comptes bancaires**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="2d6b7-108">Ouvrez la fiche de la banque pour laquelle vous souhaitez utiliser Positive Pay.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-108">Open the card for the bank that you want to use Positive Pay for.</span></span>
3. <span data-ttu-id="2d6b7-109">Dans le champ **Code exportation Positive Pay**, entrez POSPAYBANK.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-109">In the **Positive Pay Export Code** field, enter POSPAYBANK.</span></span>
4. <span data-ttu-id="2d6b7-110">Fermez la fenêtre.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-110">Close the window.</span></span>

## <a name="to-export-a-positive-pay-file"></a><span data-ttu-id="2d6b7-111">Pour exporter un fichier Positive Pay</span><span class="sxs-lookup"><span data-stu-id="2d6b7-111">To export a Positive Pay file</span></span>
1. <span data-ttu-id="2d6b7-112">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Comptes bancaires**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="2d6b7-113">Sélectionnez le compte bancaire pour lequel vous voulez exporter un fichier Positive Pay.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-113">Select the bank account that you want to export a Positive Pay file for.</span></span>
3. <span data-ttu-id="2d6b7-114">Choisissez l'option **Exportation Positive Pay**.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-114">Choose **Positive Pay Export** action.</span></span>

    <span data-ttu-id="2d6b7-115">La fenêtre **Exportation Positive Pay** s'ouvre et affiche les paiements qui ont été effectués pour le compte bancaire depuis la dernière date de téléchargement, comme indiqué dans les champs **Date dernier téléchargement** et **Heure dernier téléchargement**.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-115">The **Positive Pay Export** window opens displaying payments that have been made for the bank account since the last upload date, as shown in the **Last Upload Date** and **Last Upload Time** fields.</span></span>
4. <span data-ttu-id="2d6b7-116">Dans le champ **Date limite téléchargement**, spécifiez une date avant laquelle les paiements ne sont pas inclus dans le fichier exporté.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-116">In the **Cutoff Upload Date** field, specify a date before which payments are not included in the exported file.</span></span>
5. <span data-ttu-id="2d6b7-117">Sélectionnez l'option **Exporter**.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-117">Choose the **Export** action.</span></span>
6. <span data-ttu-id="2d6b7-118">Dans la fenêtre **Exporter fichier**, choisissez le bouton **Enregistrer**, puis enregistrez le fichier à l'emplacement approprié.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-118">In the **Export File** window, choose the **Save** button, and then save the file to a convenient location.</span></span>
7. <span data-ttu-id="2d6b7-119">Téléchargez le fichier sur votre site bancaire électronique.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-119">Upload the file to your electronic bank site.</span></span>
8. <span data-ttu-id="2d6b7-120">Notez ou copiez le numéro de confirmation qui s'affiche lorsque le téléchargement du fichier est terminé.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-120">Write down or copy the confirmation number that is displayed when the file upload is successful.</span></span>

<span data-ttu-id="2d6b7-121">Pour afficher les enregistrements Positive Pay exportés</span><span class="sxs-lookup"><span data-stu-id="2d6b7-121">To view exported Positive Pay records</span></span>

1. <span data-ttu-id="2d6b7-122">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Comptes bancaires**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-122">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="2d6b7-123">Sélectionnez le compte bancaire pour lequel vous voulez afficher l'enregistrement d'exportation de Positive Pay.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-123">Select the bank account that you want to view Positive Pay export records for.</span></span>
3. <span data-ttu-id="2d6b7-124">Choisissez l'option **Écritures Positive Pay**.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-124">Choose the **Positive Pay Entries** action.</span></span>

    <span data-ttu-id="2d6b7-125">Dans la fenêtre **Écritures Positive Pay**, vous pouvez afficher tous les enregistrements d'exportation de Positive Pay pour le compte bancaire.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-125">In the **Positive Pay Entries** window, you can see all the Positive Pay export records for the bank account.</span></span>
4. <span data-ttu-id="2d6b7-126">Dans le champ **Numéro de confirmation**, entrez, pour chaque enregistrement d'exportation, le numéro de confirmation que vous recevez lorsque le téléchargement du fichier vers la banque est terminé.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-126">In the **Confirmation Number** field, enter, for each export record, the confirmation number that you receive when the file upload to the bank is successful.</span></span>
5. <span data-ttu-id="2d6b7-127">Pour afficher les lignes de paiement associées, choisissez l'option **Détails écriture Positive Pay**.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-127">To view the related payment lines, choose the **Positive Pay Entry Details** action.</span></span>

<span data-ttu-id="2d6b7-128">Pour réexporter les fichiers Positive Pay</span><span class="sxs-lookup"><span data-stu-id="2d6b7-128">To reexport Positive Pay files</span></span>

1. <span data-ttu-id="2d6b7-129">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Comptes bancaires**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-129">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="2d6b7-130">Sélectionnez le compte bancaire pour lequel vous voulez réeexporter les fichiers Positive Pay.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-130">Select the bank account that you want to reexport Positive Pay files for.</span></span>
3. <span data-ttu-id="2d6b7-131">Choisissez l'option **Écritures Positive Pay**.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-131">Choose the **Positive Pay Entries** action.</span></span>
4. <span data-ttu-id="2d6b7-132">Sélectionnez la ligne du fichier d'exportation Positive Pay à réexporter.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-132">Select the line for the Positive Pay export file that you want to reexport.</span></span>
5. <span data-ttu-id="2d6b7-133">Dans la fenêtre **Écritures Positive Pay**, choisissez l'option **Réexporter Positive Pay dans un fichier**.</span><span class="sxs-lookup"><span data-stu-id="2d6b7-133">In the **Positive Pay Entries** window, choose the **Reexport Positive Pay to File** action.</span></span>

## <a name="see-also"></a><span data-ttu-id="2d6b7-134">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="2d6b7-134">See Also</span></span>
[<span data-ttu-id="2d6b7-135">Finances</span><span class="sxs-lookup"><span data-stu-id="2d6b7-135">Finance</span></span>](finance.md)  
[<span data-ttu-id="2d6b7-136">Configuration de Finance</span><span class="sxs-lookup"><span data-stu-id="2d6b7-136">Setting Up Finance</span></span>](finance-setup-finance.md)  
[<span data-ttu-id="2d6b7-137">Utilisation de feuilles comptabilité</span><span class="sxs-lookup"><span data-stu-id="2d6b7-137">Working with General Journals</span></span>](ui-work-general-journals.md)  
<span data-ttu-id="2d6b7-138">[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="2d6b7-138">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
