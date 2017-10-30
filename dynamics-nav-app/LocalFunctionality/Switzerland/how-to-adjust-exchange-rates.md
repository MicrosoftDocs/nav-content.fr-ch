---
title: "Procédure : ajuster des taux de change"
description: "Si vous avez des ventes imposables dans une devise étrangère, vous devez utiliser le taux officiel pour la conversion de devise TVA comme défini par l'Administration fédérale des contributions."
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
ms.openlocfilehash: 5aa71c751b9ebbf81cfea8582488aec9bb467e62
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-adjust-exchange-rates"></a><span data-ttu-id="88868-103">Procédure : ajuster des taux de change</span><span class="sxs-lookup"><span data-stu-id="88868-103">How to: Adjust Exchange Rates</span></span>
<span data-ttu-id="88868-104">Si vous avez des ventes imposables dans une devise étrangère, vous devez utiliser le taux officiel pour la conversion de devise TVA comme défini par l'Administration fédérale des contributions.</span><span class="sxs-lookup"><span data-stu-id="88868-104">If you have taxable sales in a foreign currency, you must use the official rate for VAT currency conversion as set by the Federal Tax Administration.</span></span>  
  
 <span data-ttu-id="88868-105">Si ces taux ne correspondent pas aux taux de devise utilisés dans les factures achat ou vente, vous devrez ajuster les taux de TVA à l'aide d'un traitement par lots ultérieurement.</span><span class="sxs-lookup"><span data-stu-id="88868-105">If these rates do not match the currency rates used in the purchase or sales invoices, you will have to adjust the VAT rates with a batch job later.</span></span> <span data-ttu-id="88868-106">Ces ajustements ne peuvent être exécutés qu'avec un taux de TVA autorisé.</span><span class="sxs-lookup"><span data-stu-id="88868-106">These adjustments can only be run using an authorized VAT rate.</span></span>  
  
 <span data-ttu-id="88868-107">Vous pouvez exécuter ce traitement par lots aussi souvent que vous le souhaitez. Toutefois, veillez à toujours l'exécuter avant de créer une déclaration de TVA.</span><span class="sxs-lookup"><span data-stu-id="88868-107">You can run this batch job as often as you like, however make sure that you always run it before creating a VAT statement.</span></span>  
  
> [!NOTE]  
>  <span data-ttu-id="88868-108">Lorsque vous utilisez une devise report, assurez-vous que le champ **Ajustement tx de change TVA** dans la fenêtre **Paramètres comptabilité** est défini sur **Aucun ajustement**.</span><span class="sxs-lookup"><span data-stu-id="88868-108">When using a report currency, make sure that the **VAT Exchange Rate Adjustment** field in the **General Ledger Setup** window is set to **No Adjustment**.</span></span>  
  
 <span data-ttu-id="88868-109">Pour plus d'informations sur la TVA et les devises étrangères, consultez le site web de [l'ESTV](http://go.microsoft.com/fwlink/?LinkId=285999).</span><span class="sxs-lookup"><span data-stu-id="88868-109">For more information about VAT and foreign currencies, see the [ESTV](http://go.microsoft.com/fwlink/?LinkId=285999) website.</span></span>  
  
### <a name="to-adjust-an-exchange-rate"></a><span data-ttu-id="88868-110">Pour ajuster un taux de change</span><span class="sxs-lookup"><span data-stu-id="88868-110">To adjust an exchange rate</span></span>  
  
1.  <span data-ttu-id="88868-111">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Devises**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="88868-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Currencies**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="88868-112">Sous l'onglet **Accueil**, dans le groupe **Taux de change**, choisissez **Taux change**.</span><span class="sxs-lookup"><span data-stu-id="88868-112">On the **Home** tab, in the **Exchange Rate** group, choose **Exch. Rates**.</span></span>  
  
3.  <span data-ttu-id="88868-113">Dans la fenêtre **Taux de change devise**, entrez le taux de TVA officiel par période pour chaque devise dans les champs **Montant taux chge TVA** et **Montant taux change lié ajust.**.</span><span class="sxs-lookup"><span data-stu-id="88868-113">In the **Currency Exchange Rates** window, enter the official VAT rate per period for each currency in the **VAT Exch. Rate Amount** and the **Relational VAT Exch. Rate Amt** fields.</span></span>  
  
4.  <span data-ttu-id="88868-114">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="88868-114">Choose the **OK** button.</span></span>  
  
5.  <span data-ttu-id="88868-115">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Ajuster taux change**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="88868-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Adjust Exchange Rates**, and then choose the related link.</span></span>  
  
6.  <span data-ttu-id="88868-116">Sous le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="88868-116">On the **Options** FastTab, fill in the fields as described in the following table.</span></span>   
  
    |<span data-ttu-id="88868-117">Champ</span><span class="sxs-lookup"><span data-stu-id="88868-117">Field</span></span>|<span data-ttu-id="88868-118">Description</span><span class="sxs-lookup"><span data-stu-id="88868-118">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="88868-119">**Date de début**</span><span class="sxs-lookup"><span data-stu-id="88868-119">**Starting Date**</span></span>|<span data-ttu-id="88868-120">Entrez une date pour spécifier le début de la période pour laquelle des écritures seront ajustées.</span><span class="sxs-lookup"><span data-stu-id="88868-120">Enter a date to specify the beginning of the period for which entries will be adjusted.</span></span>|  
    |<span data-ttu-id="88868-121">**Date de fin**</span><span class="sxs-lookup"><span data-stu-id="88868-121">**Ending Date**</span></span>|<span data-ttu-id="88868-122">Entrez la dernière date pour laquelle des écritures seront ajustées.</span><span class="sxs-lookup"><span data-stu-id="88868-122">Enter the last date for which entries will be adjusted.</span></span> <span data-ttu-id="88868-123">Cette date est généralement la même que la date comptabilisation figurant dans le champ **Date comptabilisation**.</span><span class="sxs-lookup"><span data-stu-id="88868-123">This date is typically the same as the posting date in the **Posting Date** field.</span></span>|  
    |<span data-ttu-id="88868-124">**Ajustement du cours TVA**</span><span class="sxs-lookup"><span data-stu-id="88868-124">**Adjust VAT exch. rate**</span></span>|<span data-ttu-id="88868-125">Spécifiez si vous souhaitez ajuster le taux de change TVA.</span><span class="sxs-lookup"><span data-stu-id="88868-125">Specify if you want to adjust the VAT exchange rate.</span></span>|  
  
7.  <span data-ttu-id="88868-126">Choisissez le bouton **Imprimer** pour démarrer le traitement par lots.</span><span class="sxs-lookup"><span data-stu-id="88868-126">Choose the **Print** button to start the batch job.</span></span> <span data-ttu-id="88868-127">Ce traitement par lots contrôle si des écritures TVA doivent être ajustées et prépare une écriture d'ajustement pour chacune de ces écritures pour les comptes Ajustements taux change réalisés/non réalisés.</span><span class="sxs-lookup"><span data-stu-id="88868-127">This batch job controls whether VAT entries have to be adjusted and prepares an adjusting entry for each of these entries for the Unrealized/Realized Exchange Rate Adjustment accounts.</span></span> <span data-ttu-id="88868-128">Les écritures TVA existantes sont également corrigées.</span><span class="sxs-lookup"><span data-stu-id="88868-128">The existing VAT entries are also corrected.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="88868-129">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="88868-129">See Also</span></span>  
 <span data-ttu-id="88868-130">[Taxe sur la valeur ajoutée suisse](swiss-value-added-tax.md) </span><span class="sxs-lookup"><span data-stu-id="88868-130">[Swiss Value Added Tax](swiss-value-added-tax.md) </span></span>  
 <span data-ttu-id="88868-131">[Taux de TVA pour la Suisse](vat-rates-for-switzerland.md) </span><span class="sxs-lookup"><span data-stu-id="88868-131">[VAT Rates for Switzerland](vat-rates-for-switzerland.md) </span></span>  
 <span data-ttu-id="88868-132">Paramètres compta. TVA</span><span class="sxs-lookup"><span data-stu-id="88868-132">VAT Posting Setup</span></span>   
 <span data-ttu-id="88868-133">Paramètres comptabilité</span><span class="sxs-lookup"><span data-stu-id="88868-133">General Ledger Setup</span></span>   
 <span data-ttu-id="88868-134">Ecriture TVA</span><span class="sxs-lookup"><span data-stu-id="88868-134">VAT Entry</span></span>   
 <span data-ttu-id="88868-135">[Ajuster taux de change](-$-b_595-adjust-exchange-rates-$.md) </span><span class="sxs-lookup"><span data-stu-id="88868-135">[Adjust Exchange Rates](-$-b_595-adjust-exchange-rates-$.md) </span></span>  
 <span data-ttu-id="88868-136">Taux de change devise</span><span class="sxs-lookup"><span data-stu-id="88868-136">Currency Exchange Rates</span></span>
