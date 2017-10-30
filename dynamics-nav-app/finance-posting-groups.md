---
title: Configuration de groupe comptabilisation
description: "Aperçu des groupes comptabilisation que vous pouvez utiliser pour gagner du temps et éviter les erreurs lorsque vous validez des transactions."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: posting setup, initialize
ms.date: 06/02/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 284ced6073c206ff46884242d633181c2dce0b85
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-posting-groups"></a><span data-ttu-id="0c95d-103">Configuration de groupes comptabilisation</span><span class="sxs-lookup"><span data-stu-id="0c95d-103">Setting Up Posting Groups</span></span>
<span data-ttu-id="0c95d-104">Les groupes comptabilisation mappent des entités telles que les clients, les fournisseurs, les éléments, les ressources et les documents vente et achat dans des comptes généraux.</span><span class="sxs-lookup"><span data-stu-id="0c95d-104">Posting groups map entities like customers, vendors, items, resources, and sales and purchase documents to general ledger accounts.</span></span> <span data-ttu-id="0c95d-105">Ils vous font gagner du temps et permettent d'éviter des erreurs lorsque vous validez des transactions.</span><span class="sxs-lookup"><span data-stu-id="0c95d-105">They save time and help avoid mistakes when you post transactions.</span></span> <span data-ttu-id="0c95d-106">Les valeurs de transaction vont dans les comptes spécifiés dans le groupe comptabilisation pour cette entité particulière.</span><span class="sxs-lookup"><span data-stu-id="0c95d-106">The transaction values go to the accounts specified in the posting group for that particular entity.</span></span> <span data-ttu-id="0c95d-107">Il vous suffit seulement d'avoir un plan comptable.</span><span class="sxs-lookup"><span data-stu-id="0c95d-107">The only requirement is that you have a chart of accounts.</span></span> <span data-ttu-id="0c95d-108">Pour plus d'informations, reportez-vous à [Configuration du plan comptable](finance-setup-chart-accounts.md).</span><span class="sxs-lookup"><span data-stu-id="0c95d-108">For more information, see [Set Up the Chart of Accounts](finance-setup-chart-accounts.md).</span></span>  

<span data-ttu-id="0c95d-109">Les groupes comptabilisation sont traités dans trois catégories :</span><span class="sxs-lookup"><span data-stu-id="0c95d-109">Posting groups are covered under three umbrellas:</span></span>  

* <span data-ttu-id="0c95d-110">Général - définit à qui vous vendez et à qui vous achetez, et ce que vous vendez et ce que vous achetez.</span><span class="sxs-lookup"><span data-stu-id="0c95d-110">General - Define who you sell to and buy from, and what you sell and what you buy.</span></span> <span data-ttu-id="0c95d-111">Vous pouvez aussi combiner des groupes pour spécifier des éléments comme les comptes résultats dans lesquels valider ou utiliser des groupes pour filtrer les états.</span><span class="sxs-lookup"><span data-stu-id="0c95d-111">You can also combine groups to specify things like the income statement accounts to post to, or use groups to filter reports.</span></span>  
* <span data-ttu-id="0c95d-112">Spécifique - permet d'utiliser des documents vente au lieu de valider directement dans le module Comptabilité.</span><span class="sxs-lookup"><span data-stu-id="0c95d-112">Specific - Use sales documents, for example, instead of posting directly to the general ledger.</span></span> <span data-ttu-id="0c95d-113">Lors de la création d'écritures comptables client, les écritures correspondantes sont passées en comptabilité.</span><span class="sxs-lookup"><span data-stu-id="0c95d-113">When you create entries in the customer ledger, corresponding entries are made in the general ledger.</span></span>  
* <span data-ttu-id="0c95d-114">Taxe - définit les pourcentages de taxes et les types de calcul qui s'appliquent à l'acheteur et au vendeur, et à ce que vous vendez et ce que vous achetez.</span><span class="sxs-lookup"><span data-stu-id="0c95d-114">Tax - Define the tax percentages and calculation types that apply to who you sell to and buy from, and what you sell and what you buy.</span></span>

<span data-ttu-id="0c95d-115">Les tables suivantes décrivent les groupes comptabilisation dans chaque catégorie.</span><span class="sxs-lookup"><span data-stu-id="0c95d-115">The following tables describe the posting groups under each umbrella.</span></span>  

| <span data-ttu-id="0c95d-116">Groupes comptabilisation généraux</span><span class="sxs-lookup"><span data-stu-id="0c95d-116">General Posting Groups</span></span> | <span data-ttu-id="0c95d-117">Désignation</span><span class="sxs-lookup"><span data-stu-id="0c95d-117">Description</span></span> |
| --- | --- |
| <span data-ttu-id="0c95d-118">Groupes comptabilisation marché</span><span class="sxs-lookup"><span data-stu-id="0c95d-118">General Business Posting Groups</span></span> |<span data-ttu-id="0c95d-119">Affectez ce groupe aux clients et aux fournisseurs pour spécifier à qui vous vendez, et à qui vous achetez.</span><span class="sxs-lookup"><span data-stu-id="0c95d-119">Assign this group to customers and vendors to specify who you sell to, and who you buy from.</span></span> <span data-ttu-id="0c95d-120">Définissez cela dans la fenêtre **Groupes compta. marché**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-120">Set these up in the **Gen. Business Posting Groups** window.</span></span> <span data-ttu-id="0c95d-121">Lorsque vous effectuez cette opération, vous devez prendre en compte le nombre de groupes nécessaires pour répartir les ventes et les achats.</span><span class="sxs-lookup"><span data-stu-id="0c95d-121">When you do, think about how many groups you'll need to break down sales and purchases.</span></span> <span data-ttu-id="0c95d-122">Par exemple, les groupes clients et fournisseurs peuvent être répartis par zone géographique ou par type d'activité.</span><span class="sxs-lookup"><span data-stu-id="0c95d-122">For example, group customers and vendors by geographical area, or by the type of business.</span></span> |
| <span data-ttu-id="0c95d-123">Groupes comptabilisation produit</span><span class="sxs-lookup"><span data-stu-id="0c95d-123">General Product Posting Groups</span></span> |<span data-ttu-id="0c95d-124">Affectez ce groupe à des articles et des ressources pour spécifier les éléments que vous vendez, et que vous achetez.</span><span class="sxs-lookup"><span data-stu-id="0c95d-124">Assign this group to items and resources to specify what you sell, and what you buy.</span></span> <span data-ttu-id="0c95d-125">Définissez cela dans la fenêtre **Groupes compta. produit**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-125">Set these up in the **Gen. Product Posting Groups** window.</span></span> <span data-ttu-id="0c95d-126">Lorsque vous effectuez cette opération, vous devez considérer le nombre de groupes nécessaires pour répartir les ventes par article et ressource, et pour répartir les achats par article.</span><span class="sxs-lookup"><span data-stu-id="0c95d-126">When you do, consider the number of groups you'll need to break down sales by product (items and resources) and purchases by items.</span></span> <span data-ttu-id="0c95d-127">Par exemple, divisez ces groupes par Matières premières, Vte détail, Ressources, Capacités, etc.</span><span class="sxs-lookup"><span data-stu-id="0c95d-127">For example, divide these groups by raw materials, retail, resources, capacity, and so on.</span></span> |
| <span data-ttu-id="0c95d-128">Paramètres comptabilisation</span><span class="sxs-lookup"><span data-stu-id="0c95d-128">General Posting Setups</span></span> |<span data-ttu-id="0c95d-129">Combinez les groupes comptabilisation marché et produit, puis choisissez les comptes à valider.</span><span class="sxs-lookup"><span data-stu-id="0c95d-129">Combine business and product posting groups and choose the accounts to post to.</span></span> <span data-ttu-id="0c95d-130">Pour chaque combinaison de groupes comptabilisation marché et produit, vous pouvez affecter un ensemble de comptes généraux.</span><span class="sxs-lookup"><span data-stu-id="0c95d-130">For each combination of business and product posting groups, you can assign a set of general ledger accounts.</span></span> <span data-ttu-id="0c95d-131">Par exemple, vous pouvez valider la vente d'un même article dans différents comptes ventes de la comptabilité car différents groupes comptabilisation marché sont affectés aux clients.</span><span class="sxs-lookup"><span data-stu-id="0c95d-131">For example, this means you can post the sale of the same item to different sales accounts in the general ledger because customers are assigned to different business posting groups.</span></span> <span data-ttu-id="0c95d-132">Définissez cela dans la fenêtre **Paramètres comptabilisation**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-132">Set these up in the **General Posting Setup** window.</span></span> |

| <span data-ttu-id="0c95d-133">Groupes comptabilisation spécifiques</span><span class="sxs-lookup"><span data-stu-id="0c95d-133">Specific Posting Groups</span></span> | <span data-ttu-id="0c95d-134">Désignation</span><span class="sxs-lookup"><span data-stu-id="0c95d-134">Description</span></span> |
| --- | --- |
| <span data-ttu-id="0c95d-135">Groupes compta. client</span><span class="sxs-lookup"><span data-stu-id="0c95d-135">Customer Posting Groups</span></span> |<span data-ttu-id="0c95d-136">Définissez les comptes à utiliser lorsque vous validez des transactions Comptabilité client.</span><span class="sxs-lookup"><span data-stu-id="0c95d-136">Define the accounts to use when you post accounts receivable transactions.</span></span> <span data-ttu-id="0c95d-137">Si vous utilisez un stock conjointement avec des clients, le groupe comptabilisation marché affecté au client et le groupe comptabilisation produit affecté à l'article en stock déterminent les comptes dans lesquels les écritures lignes commande vente valident.</span><span class="sxs-lookup"><span data-stu-id="0c95d-137">If you use inventory with receivables, the general business posting group assigned to your customer, and the general product posting group assigned to the inventory item determine the accounts the sales order lines post to.</span></span> <span data-ttu-id="0c95d-138">Définissez cela dans la fenêtre **Groupes compta. client**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-138">Set these up in the **Customer Posting Groups** window.</span></span> |
| <span data-ttu-id="0c95d-139">Groupes compta. fournisseur</span><span class="sxs-lookup"><span data-stu-id="0c95d-139">Vendor Posting Groups</span></span> |<span data-ttu-id="0c95d-140">Définissez où valider les transactions des comptes fournisseur, des comptes frais forfaitaires, et des comptes d'escompte.</span><span class="sxs-lookup"><span data-stu-id="0c95d-140">Define where to post transactions for payables accounts, service charge accounts, and payment discount accounts.</span></span> <span data-ttu-id="0c95d-141">Cela est similaire aux groupes comptabilisation client.</span><span class="sxs-lookup"><span data-stu-id="0c95d-141">This is similar to customer posting groups.</span></span> <span data-ttu-id="0c95d-142">Définissez cela dans la fenêtre **Groupes compta. fournisseur**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-142">Set these up in the **Vendor Posting Groups** window.</span></span> |
| <span data-ttu-id="0c95d-143">Groupes compta. stock</span><span class="sxs-lookup"><span data-stu-id="0c95d-143">Inventory Posting Groups</span></span> |<span data-ttu-id="0c95d-144">Définissez les comptes stock de bilan.</span><span class="sxs-lookup"><span data-stu-id="0c95d-144">Define balance sheet inventory accounts.</span></span> <span data-ttu-id="0c95d-145">Ils offrent également un bon moyen d'organiser vos stocks, vous pouvez ainsi séparer des articles par groupe comptabilisation lors de la génération d'états.</span><span class="sxs-lookup"><span data-stu-id="0c95d-145">These also provide a good way to organize your inventory, so you can separate items by their posting group when you generate reports.</span></span> <span data-ttu-id="0c95d-146">Définissez cela dans la fenêtre **Groupes compta. stock**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-146">Set these up in the **Inventory Posting Groups** window.</span></span> |
| <span data-ttu-id="0c95d-147">Groupes compta. banque</span><span class="sxs-lookup"><span data-stu-id="0c95d-147">Bank Account Posting Groups</span></span> |<span data-ttu-id="0c95d-148">Définissez des comptes bancaires.</span><span class="sxs-lookup"><span data-stu-id="0c95d-148">Define accounts for bank accounts.</span></span> <span data-ttu-id="0c95d-149">Par exemple, cela peut simplifier les processus de traçabilité des transactions et des rapprochements bancaires.</span><span class="sxs-lookup"><span data-stu-id="0c95d-149">For example, this can simplify the processes of tracing transactions and reconciling bank accounts.</span></span> <span data-ttu-id="0c95d-150">Définissez cela dans la fenêtre **Groupes compta. banque**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-150">Set these up in the **Bank Account Posting Groups** window.</span></span> |
| <span data-ttu-id="0c95d-151">Groupes comptabilisation immobilisations</span><span class="sxs-lookup"><span data-stu-id="0c95d-151">Fixed Assets Posting Groups</span></span> |<span data-ttu-id="0c95d-152">Définissez des comptes pour les différents types de dépenses et frais, tels que les coûts d'acquisition, les montants d'amortissement cumulés, les coûts d'acquisition sur cession, l'amortissement cumulé sur cession, les gains sur cession, les pertes sur cession, les frais de maintenance et les frais d'amortissement.</span><span class="sxs-lookup"><span data-stu-id="0c95d-152">Define accounts for different types of expenses and costs, such as acquisition costs, accumulated depreciation amounts, acquisition costs on disposal, accumulated depreciation on disposal, gains on disposal, losses on disposal, maintenance expenses, and depreciation expenses.</span></span> <span data-ttu-id="0c95d-153">Définissez cela dans la fenêtre **Groupes compta. immo.**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-153">Set these up in the **FA Posting Groups** window.</span></span> |

| <span data-ttu-id="0c95d-154">Groupe compta. TVA</span><span class="sxs-lookup"><span data-stu-id="0c95d-154">Tax Posting Group</span></span> | <span data-ttu-id="0c95d-155">Désignation</span><span class="sxs-lookup"><span data-stu-id="0c95d-155">Description</span></span> |
| --- | --- |
| <span data-ttu-id="0c95d-156">Groupes compta. marché TVA</span><span class="sxs-lookup"><span data-stu-id="0c95d-156">Tax Business Posting Groups</span></span> |<span data-ttu-id="0c95d-157">Déterminez la manière de calculer et de valider la taxe de vente pour les clients et les fournisseurs.</span><span class="sxs-lookup"><span data-stu-id="0c95d-157">Determine how to calculate and post sales tax for customers and vendors.</span></span> <span data-ttu-id="0c95d-158">Définissez cela dans la fenêtre **Groupes compta. marché TVA**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-158">Set these up in the **Tax Business Posting Groups** window.</span></span> <span data-ttu-id="0c95d-159">Lorsque vous le faites, pensez au nombre de groupes dont vous avez besoin.</span><span class="sxs-lookup"><span data-stu-id="0c95d-159">When you do, think about how many groups you need.</span></span> <span data-ttu-id="0c95d-160">De nombreux facteurs peuvent entrer en jeu, notamment la législation locale, et le fait de travailler sur le marché national et international.</span><span class="sxs-lookup"><span data-stu-id="0c95d-160">For example, this can depend on factors like local legislation, and whether you trade both domestically and internationally.</span></span> |
| <span data-ttu-id="0c95d-161">Groupes compta. produit TVA</span><span class="sxs-lookup"><span data-stu-id="0c95d-161">Tax Product Posting Groups</span></span> |<span data-ttu-id="0c95d-162">Indiquez les calculs TVA nécessaires pour les types d'articles ou de ressources que vous achetez ou vendez.</span><span class="sxs-lookup"><span data-stu-id="0c95d-162">Indicate the tax calculations needed for the types of items or resources you buy or sell.</span></span> |
| <span data-ttu-id="0c95d-163">Paramètres compta. TVA</span><span class="sxs-lookup"><span data-stu-id="0c95d-163">Tax Posting Setup</span></span> |<span data-ttu-id="0c95d-164">Combinez des groupes compta. marché et des groupes compta. produit TVA.</span><span class="sxs-lookup"><span data-stu-id="0c95d-164">Combine tax business posting groups and tax product posting groups.</span></span> <span data-ttu-id="0c95d-165">Lorsque vous renseignez une ligne dans une feuille comptabilité, une ligne achat, ou une ligne vente, nous allons consulter la combinaison pour identifier les comptes à utiliser.</span><span class="sxs-lookup"><span data-stu-id="0c95d-165">When you fill in a general journal line, purchase line, or sales line, we'll look at the combination to identify the accounts to use.</span></span> |

## <a name="example-of-linking-posting-groups"></a><span data-ttu-id="0c95d-166">Exemple de liaison de groupes comptabilisation</span><span class="sxs-lookup"><span data-stu-id="0c95d-166">Example of linking posting groups</span></span>
<span data-ttu-id="0c95d-167">Voici un scénario.</span><span class="sxs-lookup"><span data-stu-id="0c95d-167">Here's a scenario.</span></span>  

<span data-ttu-id="0c95d-168">Ces groupes comptabilisation sont choisis dans la fiche client :</span><span class="sxs-lookup"><span data-stu-id="0c95d-168">These posting groups are chosen on the customer card:</span></span>  

* <span data-ttu-id="0c95d-169">Groupe comptabilisation marché</span><span class="sxs-lookup"><span data-stu-id="0c95d-169">General business posting group</span></span>
* <span data-ttu-id="0c95d-170">Groupe compta. client</span><span class="sxs-lookup"><span data-stu-id="0c95d-170">Customer posting group</span></span>  

<span data-ttu-id="0c95d-171">Ces groupes comptabilisation sont choisis dans la fiche article :</span><span class="sxs-lookup"><span data-stu-id="0c95d-171">These posting groups are chosen on the item card:</span></span>  

* <span data-ttu-id="0c95d-172">Groupe comptabilisation produit</span><span class="sxs-lookup"><span data-stu-id="0c95d-172">General product posting group</span></span>  
* <span data-ttu-id="0c95d-173">Groupe comptabilisation stock</span><span class="sxs-lookup"><span data-stu-id="0c95d-173">Inventory posting group</span></span>  

<span data-ttu-id="0c95d-174">Lors de la création d'un document vente, l'en-tête vente utilise les informations de la fiche client et les lignes ventes utilisent les informations de la fiche article.</span><span class="sxs-lookup"><span data-stu-id="0c95d-174">When you create a sales document, the sales header uses the customer card information, and the sales lines use the item card information.</span></span>  

* <span data-ttu-id="0c95d-175">La validation revenus (résultats) est déterminée par la combinaison du groupe comptabilisation marché et du groupe comptabilisation produit.</span><span class="sxs-lookup"><span data-stu-id="0c95d-175">The revenue posting (income statement) is determined by the combination of the general business posting group and the general product posting group.</span></span>  
* <span data-ttu-id="0c95d-176">La validation comptabilisation client (bilan) est déterminée par le groupe comptabilisation client.</span><span class="sxs-lookup"><span data-stu-id="0c95d-176">The accounts receivable posting (balance sheet) is determined by the customer posting group.</span></span>  
* <span data-ttu-id="0c95d-177">La validation stock (bilan) est déterminée par le groupe comptabilisation stock.</span><span class="sxs-lookup"><span data-stu-id="0c95d-177">The inventory posting (balance sheet) is determined by the inventory posting group.</span></span>  
* <span data-ttu-id="0c95d-178">La validation coût des biens vendus (comptes résultats) est déterminée par la combinaison du groupe comptabilisation marché et du groupe comptabilisation produit.</span><span class="sxs-lookup"><span data-stu-id="0c95d-178">The cost of goods sold posting (income statement) is determined by the combination of general business posting group and general product posting group.</span></span>  

<span data-ttu-id="0c95d-179">Votre paramétrage détermine quand la validation a lieu.</span><span class="sxs-lookup"><span data-stu-id="0c95d-179">Your setup determines when posting happens.</span></span> <span data-ttu-id="0c95d-180">Par exemple, la synchronisation est affectée au moment où vous exécutez des activités périodiques, par exemple : valider coûts ajustés et ajuster coût écritures article.</span><span class="sxs-lookup"><span data-stu-id="0c95d-180">For example, the timing is affected by when you do periodic activities, such as posting inventory cost or adjusting cost item entries.</span></span>

## <a name="copying-posting-setup-lines"></a><span data-ttu-id="0c95d-181">Copie de lignes paramètres validation</span><span class="sxs-lookup"><span data-stu-id="0c95d-181">Copying posting setup lines</span></span>
<span data-ttu-id="0c95d-182">Plus il y a de groupes comptabilisation produit et marché, plus la fenêtre Paramètres comptabilisation contient de lignes.</span><span class="sxs-lookup"><span data-stu-id="0c95d-182">The more product and business posting groups you have, the more lines you see in the General Posting Setup window.</span></span> <span data-ttu-id="0c95d-183">Cela peut entraîner la nécessité d'entrer un grand nombre de données pour configurer les paramètres comptabilisation pour la société.</span><span class="sxs-lookup"><span data-stu-id="0c95d-183">This can mean a lot of data entry to set up the general posting setup for the company.</span></span> <span data-ttu-id="0c95d-184">S'il peut y avoir un grand nombre de combinaisons différentes de groupes comptabilisation marché et produit, différentes combinaisons peuvent encore valider dans les mêmes comptes généraux.</span><span class="sxs-lookup"><span data-stu-id="0c95d-184">While there may be many different combinations of business and product posting groups, different combinations may still post to the same general ledger accounts.</span></span> <span data-ttu-id="0c95d-185">Pour limiter le nombre de saisies manuelles, copiez les comptes généraux à partir d'une ligne existante dans la fenêtre **Paramètres comptabilisation**.</span><span class="sxs-lookup"><span data-stu-id="0c95d-185">To limit the amount of manual entry, copy the general ledger accounts from an existing line in the **General Posting Setup** window.</span></span>

## <a name="see-also"></a><span data-ttu-id="0c95d-186">Voir aussi .</span><span class="sxs-lookup"><span data-stu-id="0c95d-186">See also</span></span>
[<span data-ttu-id="0c95d-187">Les écritures comptables et le plan comptable</span><span class="sxs-lookup"><span data-stu-id="0c95d-187">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
[<span data-ttu-id="0c95d-188">Configuration de Finance</span><span class="sxs-lookup"><span data-stu-id="0c95d-188">Setting Up Finance</span></span>](finance-setup-finance.md)  
<span data-ttu-id="0c95d-189">[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="0c95d-189">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
