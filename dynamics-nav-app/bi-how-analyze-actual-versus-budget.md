---
title: "Analyse comparative Réel/Budget"
description: "Décrit comment analyser les montants réalisés et les montants budgétés."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bi, power BI, analysis, KPI
ms.date: 06/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a39f213e7e96423efe25bb715f4a1b4bb3c0258b
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-analyze-actual-amounts-versus-budgeted-amounts"></a><span data-ttu-id="6f582-103">Procédure : analyser les montants réalisés et les montants budgétés</span><span class="sxs-lookup"><span data-stu-id="6f582-103">How to: Analyze Actual Amounts Versus Budgeted Amounts</span></span>
<span data-ttu-id="6f582-104">Lors de la collecte, l'analyse, et le partage des données de votre société, vous voyez les montants réels comparés aux montants budgétés de tous les comptes et pour plusieurs périodes.</span><span class="sxs-lookup"><span data-stu-id="6f582-104">As a part of gathering, analyzing, and sharing your company data, you view actual amounts compared to budgeted amounts for all accounts and for several periods.</span></span>

<span data-ttu-id="6f582-105">Pour analyser les montants budgétés, vous devez d'abord créer des budgets.</span><span class="sxs-lookup"><span data-stu-id="6f582-105">To analyze budgeted amounts, you must first create budgets.</span></span> <span data-ttu-id="6f582-106">Pour plus d'informations, voir [Procédure : Créer des budgets](finance-how-create-budgets.md).</span><span class="sxs-lookup"><span data-stu-id="6f582-106">For more information, see [How to: Create Budgets](finance-how-create-budgets.md).</span></span>

## <a name="to-view-a-budget"></a><span data-ttu-id="6f582-107">Pour visualiser un budget</span><span class="sxs-lookup"><span data-stu-id="6f582-107">To view a budget</span></span>
<span data-ttu-id="6f582-108">Dans un budget doté d'axes, vous pouvez filtrer les écritures et visualiser des budgets spécifiques.</span><span class="sxs-lookup"><span data-stu-id="6f582-108">In a budget with dimensions, you can filter the entries and see specific budgets.</span></span>

1. <span data-ttu-id="6f582-109">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Budgets**, puis choisissez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="6f582-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **G/L Budgets**, and then choose the related link.</span></span>
2. <span data-ttu-id="6f582-110">Dans la fenêtre **Budgets**, ouvrez le budget que vous souhaitez visualiser.</span><span class="sxs-lookup"><span data-stu-id="6f582-110">In the **G/L Budgets** window, open the budget that you want to view.</span></span>  
3. <span data-ttu-id="6f582-111">En haut de la fenêtre, renseignez les champs nécessaires pour définir ce qui est affiché.</span><span class="sxs-lookup"><span data-stu-id="6f582-111">At the top of the window, fill in the fields as necessary to define what is shown.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   <span data-ttu-id="6f582-112">Si vous avez sélectionné **Période** dans le champ **Afficher lignes** ou **Afficher colonnes**, puis vous devez renseigner le champ **Afficher par**.</span><span class="sxs-lookup"><span data-stu-id="6f582-112">If you have selected **Period** in either the **Show as Lines** or the **Show as Columns** field, then you must fill in the **View by** field.</span></span> <span data-ttu-id="6f582-113">Si vous n'avez pas sélectionné **Période** dans le champ **Afficher lignes** ou **Afficher colonnes**, entrez la période appropriée dans le champ **Filtre date**.</span><span class="sxs-lookup"><span data-stu-id="6f582-113">If you have not selected **Period** in either the **Show as Lines** or **Show as Columns** field, then enter the appropriate period in **Date Filter** field.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="6f582-114">Seules les écritures budget en comptabilité contenant les codes filtre entrés sur le raccourci **Filtres** sont incluses dans le calcul.</span><span class="sxs-lookup"><span data-stu-id="6f582-114">Only entries from the general ledger budget with the filter codes that you enter on the **Filters** FastTab are included in the calculation.</span></span> <span data-ttu-id="6f582-115">Les écritures budget contenant d'autres codes filtre ou ne contenant aucun code filtre sont exclues.</span><span class="sxs-lookup"><span data-stu-id="6f582-115">Budget entries with other filter codes or without any filter codes are not included.</span></span> <span data-ttu-id="6f582-116">Tant que le filtre est présent dans la fenêtre, le budget n'affiche que les écritures budget contenant ces codes filtre.</span><span class="sxs-lookup"><span data-stu-id="6f582-116">As long as the filter remains on the window, the budget only displays the budget entries with these filter codes.</span></span>  

> [!TIP]  
>   <span data-ttu-id="6f582-117">Si vous souhaitez modifier le budget, vous pouvez modifier les écritures budget.</span><span class="sxs-lookup"><span data-stu-id="6f582-117">If you want to modify the budget, you can modify the budget entries.</span></span> <span data-ttu-id="6f582-118">Choisissez un montant pour afficher les écritures Budget sous-jacentes.</span><span class="sxs-lookup"><span data-stu-id="6f582-118">Choose an amount to view the underlying general ledger budget entries.</span></span>

## <a name="to-view-actual-and-budgeted-amounts-for-all-accounts"></a><span data-ttu-id="6f582-119">Pour afficher les montants budgétés et réalisés de tous les comptes</span><span class="sxs-lookup"><span data-stu-id="6f582-119">To view actual and budgeted amounts for all accounts</span></span>  
<span data-ttu-id="6f582-120">Vous pouvez afficher des budgets et les comparer aux chiffres réels dans différents modules de [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="6f582-120">You can view general ledger budgets and compare them with actual figures in several areas of [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>

1. <span data-ttu-id="6f582-121">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Plan comptable**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="6f582-121">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6f582-122">Dans la fenêtre **Plan comptable**, choisissez l'action **Réalisé/Budget par compte**.</span><span class="sxs-lookup"><span data-stu-id="6f582-122">In the **Chart of Accounts** window, choose the **G/L Balance/Budget** action.</span></span>
3. <span data-ttu-id="6f582-123">En haut de la fenêtre, renseignez les champs nécessaires pour définir ce qui est affiché.</span><span class="sxs-lookup"><span data-stu-id="6f582-123">At the top of the window, fill in the fields as necessary to define what is shown.</span></span>  
4. <span data-ttu-id="6f582-124">Pour voir le détail d'un montant affiché, sélectionnez ce champ.</span><span class="sxs-lookup"><span data-stu-id="6f582-124">To see a specification that makes up the amount shown, choose the field.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="6f582-125">Les filtres que vous définissez dans l'en-tête de la fenêtre sont appliqués aux écritures comptables et aux écritures budget.</span><span class="sxs-lookup"><span data-stu-id="6f582-125">The filters you set in the window header will be applied to general ledger entries and also budget entries.</span></span>

<span data-ttu-id="6f582-126">Les colonnes les plus à gauche contiennent le plan comptable.</span><span class="sxs-lookup"><span data-stu-id="6f582-126">The leftmost columns contain the chart of accounts.</span></span> <span data-ttu-id="6f582-127">Sur les cinq colonnes les plus à droite, les quatre premières affichent les montants crédit et débit budgétés, et réalisés pour chaque compte.</span><span class="sxs-lookup"><span data-stu-id="6f582-127">Of the five columns on the rightmost side, the first four columns show actual and budgeted debit and credit amounts for each account.</span></span> <span data-ttu-id="6f582-128">La cinquième colonne indique la relation proportionnelle entre les montants budgétés et réalisés sur le compte général.</span><span class="sxs-lookup"><span data-stu-id="6f582-128">The fifth column shows the proportional relationship between the actual and the budgeted amounts on the general ledger account.</span></span>  

> [!TIP]  
>   <span data-ttu-id="6f582-129">Le champ **Afficher par** de la fenêtre **Réalisé/Budget par compte** permet de sélectionner la longueur de la période.</span><span class="sxs-lookup"><span data-stu-id="6f582-129">Use the **View by** field in the **G/L Balance/Budget** window to select the period length.</span></span> <span data-ttu-id="6f582-130">Le champ **Afficher en tant que** permet de sélectionner le mode de calcul des montants, à savoir **Solde période** ou **Solde au**.</span><span class="sxs-lookup"><span data-stu-id="6f582-130">Use the **View as** field to select the way the amounts will be calculated, **Net Change** or **Balance at Date**.</span></span> <span data-ttu-id="6f582-131">Choisissez **Période précédente** ou **Période suivante** pour changer de période.</span><span class="sxs-lookup"><span data-stu-id="6f582-131">Choose the **Previous Period** or **Next Period** action to change the period.</span></span>  

## <a name="to-view-actual-and-budgeted-amounts-for-several-periods"></a><span data-ttu-id="6f582-132">Pour afficher les montants budgétés et réalisés de plusieurs périodes</span><span class="sxs-lookup"><span data-stu-id="6f582-132">To view actual and budgeted amounts for several periods</span></span>  
<span data-ttu-id="6f582-133">Au lieu de visualiser les montants budgétés et réalisés de tous les comptes au sein d'une seule période, vous pouvez afficher un certain nombre de périodes pour un seul compte.</span><span class="sxs-lookup"><span data-stu-id="6f582-133">Instead of viewing the actual and budgeted amounts for all accounts within a single period, you can view a number of periods for a single account.</span></span>  

1. <span data-ttu-id="6f582-134">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Plan comptable**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="6f582-134">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6f582-135">Dans la fenêtre **Plan comptable**, sélectionnez le compte général approprié, puis choisissez l'action **Réalisé/Budget compte général**.</span><span class="sxs-lookup"><span data-stu-id="6f582-135">In the **Chart of Accounts** window, select the relevant general ledger account, and then choose the **G/L Account Balance/Budget** action.</span></span>  
3. <span data-ttu-id="6f582-136">En haut de la fenêtre, renseignez les champs nécessaires pour définir ce qui est affiché.</span><span class="sxs-lookup"><span data-stu-id="6f582-136">At the top of the window, fill in the fields as necessary to define what is shown.</span></span>   
4. <span data-ttu-id="6f582-137">Pour voir le détail d'un montant affiché, sélectionnez ce champ.</span><span class="sxs-lookup"><span data-stu-id="6f582-137">To see a specification of an amount shown, choose the field.</span></span>  

## <a name="see-also"></a><span data-ttu-id="6f582-138">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="6f582-138">See Also</span></span>
<span data-ttu-id="6f582-139">[Veille économique](bi.md)
[Procédure : Utiliser des tableaux d'analyse](bi-how-work-account-schedule.md)</span><span class="sxs-lookup"><span data-stu-id="6f582-139">[Business Intelligence](bi.md)
[How to: Work with Account Schedules](bi-how-work-account-schedule.md)</span></span>  
[<span data-ttu-id="6f582-140">Finances</span><span class="sxs-lookup"><span data-stu-id="6f582-140">Finance</span></span>](finance.md)  
[<span data-ttu-id="6f582-141">Configuration de Finance</span><span class="sxs-lookup"><span data-stu-id="6f582-141">Setting Up Finance</span></span>](finance-setup-finance.md)  
[<span data-ttu-id="6f582-142">Les écritures comptables et le plan comptable</span><span class="sxs-lookup"><span data-stu-id="6f582-142">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
<span data-ttu-id="6f582-143">[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="6f582-143">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
