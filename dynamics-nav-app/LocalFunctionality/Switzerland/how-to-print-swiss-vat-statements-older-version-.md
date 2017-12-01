---
title: "Procédure : imprimer des déclarations de TVA suisses (version plus ancienne)"
description: "**Déclaration de TVA suisse** est l'état de calcul standard pour réaliser la TVA. Vous pouvez imprimer cet état et l'utiliser pour la génération d'états fiscaux trimestriels."
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
ms.openlocfilehash: 567e1e936447893b80f7a976e643620fbab5d6ce
ms.contentlocale: fr-ch
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-print-swiss-vat-statements-older-version"></a><span data-ttu-id="34691-104">Procédure : imprimer des déclarations de TVA suisses (version plus ancienne)</span><span class="sxs-lookup"><span data-stu-id="34691-104">How to: Print Swiss VAT Statements (older version)</span></span>

> [!NOTE]  
>  <span data-ttu-id="34691-105">Cette rubrique est conservée à des fins de compatibilité descendante avec l'état **Déclaration TVA suisse**.</span><span class="sxs-lookup"><span data-stu-id="34691-105">This topic is retained for backward compatibility with the **Swiss VAT Statement** report.</span></span> <span data-ttu-id="34691-106">Pour plus d'informations sur l'utilisation de la déclaration de TVA suisse plus récente, voir Déclaration TVA suisse.</span><span class="sxs-lookup"><span data-stu-id="34691-106">For information about using the newer Swiss VAT Statement, see Swiss VAT Statement.</span></span>  

<span data-ttu-id="34691-107">**Déclaration de TVA suisse** est l'état de calcul standard pour réaliser la TVA.</span><span class="sxs-lookup"><span data-stu-id="34691-107">The **Swiss VAT Statement** is the standard calculation report for realizing VAT.</span></span> <span data-ttu-id="34691-108">Vous pouvez imprimer cet état et l'utiliser pour la génération d'états fiscaux trimestriels.</span><span class="sxs-lookup"><span data-stu-id="34691-108">You can print this report, and use it for quarterly tax reporting.</span></span> <span data-ttu-id="34691-109">L'état **Déclaration de TVA suisse** comprend les éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="34691-109">The **Swiss VAT Statement** includes the following:</span></span>  

- <span data-ttu-id="34691-110">Une écriture TVA.</span><span class="sxs-lookup"><span data-stu-id="34691-110">A VAT entry.</span></span>  
- <span data-ttu-id="34691-111">Des écritures ajustement TVA.</span><span class="sxs-lookup"><span data-stu-id="34691-111">VAT adjusting entries.</span></span>  
- <span data-ttu-id="34691-112">Une fiche comptable.</span><span class="sxs-lookup"><span data-stu-id="34691-112">An accounting sheet.</span></span>  

## <a name="to-print-the-swiss-vat-statement"></a><span data-ttu-id="34691-113">Pour imprimer une déclaration TVA suisse</span><span class="sxs-lookup"><span data-stu-id="34691-113">To print the Swiss VAT statement</span></span>  

1.  <span data-ttu-id="34691-114">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Déclaration TVA suisse**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="34691-114">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Swiss VAT Statement**, and then choose the related link.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="34691-115">Vous recevrez un message indiquant que la **Déclaration TVA suisse** va s'ouvrir dans la langue locale.</span><span class="sxs-lookup"><span data-stu-id="34691-115">You will receive a message stating that the **Swiss VAT Statement** will open in the local language.</span></span>  

2.  <span data-ttu-id="34691-116">Sous le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="34691-116">On the **Options** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="34691-117">Champ</span><span class="sxs-lookup"><span data-stu-id="34691-117">Field</span></span>|<span data-ttu-id="34691-118">Description</span><span class="sxs-lookup"><span data-stu-id="34691-118">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="34691-119">**Lettrées avec n° de journal**</span><span class="sxs-lookup"><span data-stu-id="34691-119">**Closed with Journal no.**</span></span>|<span data-ttu-id="34691-120">Sélectionnez les feuilles comptabilité qui contiennent la source de comptabilisation des écritures ajustement TVA.</span><span class="sxs-lookup"><span data-stu-id="34691-120">Select the general ledger journals that contain the posting source of the VAT adjusting entries.</span></span> <span data-ttu-id="34691-121">Ce champ évalue les périodes comptables qui ont déjà été réglées.</span><span class="sxs-lookup"><span data-stu-id="34691-121">This field evaluates accounting periods that have already been settled.</span></span>|  
    |<span data-ttu-id="34691-122">**Ouvertes jusqu'à la date**</span><span class="sxs-lookup"><span data-stu-id="34691-122">**Open until date**</span></span>|<span data-ttu-id="34691-123">Sélectionnez la dernière date pour régler les écritures TVA ouvertes ou non réglées.</span><span class="sxs-lookup"><span data-stu-id="34691-123">Select the last date for settling open or unsettled VAT entries.</span></span>|  
    |<span data-ttu-id="34691-124">**Afficher écritures**</span><span class="sxs-lookup"><span data-stu-id="34691-124">**Show Postings**</span></span>|<span data-ttu-id="34691-125">Spécifie si toutes les écritures TVA pour chaque groupe seront imprimées.</span><span class="sxs-lookup"><span data-stu-id="34691-125">Specifies if all of the VAT entries for each group will be printed.</span></span>|  
    |<span data-ttu-id="34691-126">**Afficher écritures lettrage**</span><span class="sxs-lookup"><span data-stu-id="34691-126">**Show Chargeback**</span></span>|<span data-ttu-id="34691-127">Spécifie si les écritures TVA et les écritures comptables avec résumés clôturés ou taxe revalidée seront imprimées.</span><span class="sxs-lookup"><span data-stu-id="34691-127">Specifies if VAT entries and general ledger entries with closed summaries or reposted tax will be printed.</span></span>|  
    |<span data-ttu-id="34691-128">**Taux TVA normal %**</span><span class="sxs-lookup"><span data-stu-id="34691-128">**Normal rate VAT %**</span></span>|<span data-ttu-id="34691-129">Sélectionnez les taux actuels de TVA normale utilisés pour assigner les taux corrects aux groupes produit et marché définis dans les paramètres TVA.</span><span class="sxs-lookup"><span data-stu-id="34691-129">Select the current typical VAT rates used to assign the correct rates to the business and product groups defined in the VAT settings.</span></span>|  
    |<span data-ttu-id="34691-130">**Taux TVA réduit %**</span><span class="sxs-lookup"><span data-stu-id="34691-130">**Reduced rate VAT %**</span></span>|<span data-ttu-id="34691-131">Sélectionnez les taux actuels de taxe réduite utilisés pour assigner les taux corrects aux groupes produit et marché définis dans les paramètres TVA.</span><span class="sxs-lookup"><span data-stu-id="34691-131">Select the current reduced tax rates used to assign the correct rates to the business and product groups defined in the VAT settings.</span></span>|  
    |<span data-ttu-id="34691-132">**Taux TVA spécial %**</span><span class="sxs-lookup"><span data-stu-id="34691-132">**Special rate VAT %**</span></span>|<span data-ttu-id="34691-133">Sélectionnez les taux actuels de taxe spéciale utilisés pour assigner les taux corrects aux groupes produit et marché définis dans les paramètres TVA.</span><span class="sxs-lookup"><span data-stu-id="34691-133">Select the current special tax rates used to assign the correct rates to the business and product groups defined in the VAT settings.</span></span>|  
    |<span data-ttu-id="34691-134">**Compte général TVA achat investissements/charges d'exploitation**</span><span class="sxs-lookup"><span data-stu-id="34691-134">**Investment/Operating Purchase VAT G/L Account**</span></span>|<span data-ttu-id="34691-135">Sélectionnez le compte général TVA.</span><span class="sxs-lookup"><span data-stu-id="34691-135">Select the VAT general ledger account.</span></span>|  
    |<span data-ttu-id="34691-136">**Groupe compta. marché auto-cons.**</span><span class="sxs-lookup"><span data-stu-id="34691-136">**Own Consumption Bus. Group**</span></span>|<span data-ttu-id="34691-137">Sélectionnez le groupe produit et marché pour les consommations propres.</span><span class="sxs-lookup"><span data-stu-id="34691-137">Select the business and product group for own consumptions.</span></span>|  
    |<span data-ttu-id="34691-138">**Groupe compta. marché Prestations de service à l'étranger**</span><span class="sxs-lookup"><span data-stu-id="34691-138">**Service Foreign Bus. Group**</span></span>|<span data-ttu-id="34691-139">Sélectionnez le groupe produit et marché pour les services à l'étranger.</span><span class="sxs-lookup"><span data-stu-id="34691-139">Select the foreign service business and product group.</span></span>|  
    |<span data-ttu-id="34691-140">**Groupe marché export**</span><span class="sxs-lookup"><span data-stu-id="34691-140">**Export Bus. Group**</span></span>|<span data-ttu-id="34691-141">Sélectionnez le groupe produit et marché pour les exportations.</span><span class="sxs-lookup"><span data-stu-id="34691-141">Select the business and product group for exports.</span></span>|  

3.  <span data-ttu-id="34691-142">Choisissez le bouton **Imprimer** pour imprimer la déclaration TVA ou le bouton **Aperçu** pour l'afficher à l'écran.</span><span class="sxs-lookup"><span data-stu-id="34691-142">Choose the **Print** button to print the VAT statement or choose the **Preview** button to view it on the screen.</span></span>  

## <a name="see-also"></a><span data-ttu-id="34691-143">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="34691-143">See Also</span></span>  
 <span data-ttu-id="34691-144">[Taxe sur la valeur ajoutée suisse](swiss-value-added-tax.md) </span><span class="sxs-lookup"><span data-stu-id="34691-144">[Swiss Value Added Tax](swiss-value-added-tax.md) </span></span>  
 [<span data-ttu-id="34691-145">Taux de TVA pour la Suisse</span><span class="sxs-lookup"><span data-stu-id="34691-145">VAT Rates for Switzerland</span></span>](vat-rates-for-switzerland.md)

