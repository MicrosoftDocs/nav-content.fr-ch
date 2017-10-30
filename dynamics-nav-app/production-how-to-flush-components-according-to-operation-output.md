---
title: "Procédure : consommer en aval des composants en fonction de la production réalisée"
description: "Pour les articles créés avec la méthode de consommation en amont, le comportement par défaut est de calculer et de valider la consommation de composants lorsque vous affectez à l'ordre de fabrication lancé le statut **Terminé**. Pour plus d'informations, voir Méthode consommation."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 48645ff5d943b2f7093224289ff3cad6cfa6537e
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-flush-components-according-to-operation-output"></a><span data-ttu-id="7915d-104">Procédure : consommer en aval des composants en fonction de la production réalisée</span><span class="sxs-lookup"><span data-stu-id="7915d-104">How to: Flush Components According to Operation Output</span></span>
<span data-ttu-id="7915d-105">Pour les articles créés avec la méthode de consommation en amont le comportement par défaut est de calculer et de valider la consommation de composants lorsque vous affectez à l'ordre de fabrication lancé le statut **Terminé**.</span><span class="sxs-lookup"><span data-stu-id="7915d-105">For items that are set up with backward flushing method, the default behavior is to calculate and post component consumption when you change the status of a released production order to **Finished**.</span></span>  

<span data-ttu-id="7915d-106">Si vous définissez également les codes lien gamme, le calcul et la validation ont lieu lorsque chaque opération est terminée et la quantité effectivement consommée au cours de l'opération est validée.</span><span class="sxs-lookup"><span data-stu-id="7915d-106">If you also define routing link codes, then calculation and posting occurs when each operation is finished, and the quantity that was actually consumed in the operation is posted.</span></span> <span data-ttu-id="7915d-107">Pour plus d'informations, reportez\-vous à [Procédure : Créer des gammes](production-how-to-create-routings.md).</span><span class="sxs-lookup"><span data-stu-id="7915d-107">For more information, see [How to: Create Routings](production-how-to-create-routings.md).</span></span>  

<span data-ttu-id="7915d-108">Par exemple, si un ordre de fabrication de 800 mètres nécessite pour son exécution 8 kilogrammes d'un composant, lorsque vous validez 200 mètres de production, 2 kilogrammes sont automatiquement validés comme étant consommés.</span><span class="sxs-lookup"><span data-stu-id="7915d-108">For example, if a production order to produce 800 meters requires 8 kg of a component, then when you post 200 meters as output, 2 kg are automatically posted as consumption.</span></span>  

<span data-ttu-id="7915d-109">Cette fonctionnalité est utile pour les motifs suivants :</span><span class="sxs-lookup"><span data-stu-id="7915d-109">This functionality is useful for the following reasons:</span></span>  

-   <span data-ttu-id="7915d-110">**Évaluation du stock** - Les écritures de valeur de production et de consommation sont créées parallèlement à l'état d'exécution de l'ordre de fabrication.</span><span class="sxs-lookup"><span data-stu-id="7915d-110">**Inventory Valuation** - Value entries for output and consumption are created in parallel as the production order progresses.</span></span> <span data-ttu-id="7915d-111">Sans les codes lien gamme, la valeur du stock augmente lorsque la production est validée, puis réduit ultérieurement lorsque la valeur de la consommation des composants est validée en même temps que l'ordre de fabrication terminé.</span><span class="sxs-lookup"><span data-stu-id="7915d-111">Without routing link codes, the inventory value will increase as output is posted and then decrease at a later point in time when the value of component consumption is posted together with the finished production order.</span></span>  
-   <span data-ttu-id="7915d-112">**Disponibilité du stock** - Avec une validation progressive de la consommation, la disponibilité des composants est mieux actualisée, ce qui est important pour conserver l'équilibre interne entre l'offre et la demande.</span><span class="sxs-lookup"><span data-stu-id="7915d-112">**Inventory Availability** - With gradual consumption posting, the availability of component items is more up-to-date, which is important to maintain the internal balance between demand and supply.</span></span> <span data-ttu-id="7915d-113">Sans les codes lien gamme, les autres demandeurs du composant peuvent croire qu'il est disponible tant que la validation de sa consommation reste en attente.</span><span class="sxs-lookup"><span data-stu-id="7915d-113">Without routing link codes, other demands for the component may believe that it is available as long as it is pending a delayed consumption posting.</span></span>  
-   <span data-ttu-id="7915d-114">**Just-in-Time** - Si vous pouvez personnaliser les produits en fonction des demandes client, vous pouvez réduire les rebuts en vous organisant pour que les procédures de travail et les systèmes ne soient modifiés que lorsque c'est nécessaire.</span><span class="sxs-lookup"><span data-stu-id="7915d-114">**Just-in-Time** – With the ability to customize products to customer requests, you can minimize waste by making sure that work and system changes only occur when it is necessary.</span></span>  

<span data-ttu-id="7915d-115">La procédure suivante montre comment combiner la consommation en amont et les codes lien gamme pour que la quantité consommée par chaque opération soit proportionnelle à la production réelle de cette opération terminée.</span><span class="sxs-lookup"><span data-stu-id="7915d-115">The following procedure shows how to combine backward flushing and routing link codes so that the quantity that is flushed for each operation is proportional to the actual output of the finished operation.</span></span>  

## <a name="to-flush-components-according-to-operation-output"></a><span data-ttu-id="7915d-116">Pour consommer en aval des composants en fonction de la production réalisée</span><span class="sxs-lookup"><span data-stu-id="7915d-116">To flush components according to operation output</span></span>  
1.  <span data-ttu-id="7915d-117">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Articles**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="7915d-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="7915d-118">Choisissez l'action **Modifier**.</span><span class="sxs-lookup"><span data-stu-id="7915d-118">Choose the **Edit** action.</span></span>  
3.  <span data-ttu-id="7915d-119">Sur le raccourci **Réapprovisionnement**, dans le champ **Méthode consommation**, sélectionnez **En aval**.</span><span class="sxs-lookup"><span data-stu-id="7915d-119">On the **Replenishment** FastTab, in the **Flushing Method** field, select **Forward**.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="7915d-120">Sélectionnez **Prélèvement + Aval** si le composant est utilisé dans un magasin configuré pour un prélèvement et un rangement suggérés.</span><span class="sxs-lookup"><span data-stu-id="7915d-120">Select **Pick+ Forward** if the component is used in a location that is set up for directed put-away and pick.</span></span>  

4.  <span data-ttu-id="7915d-121">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Gammes**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="7915d-121">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
5.  <span data-ttu-id="7915d-122">Définir les codes lien gamme pour chaque opération qui consomme le composant.</span><span class="sxs-lookup"><span data-stu-id="7915d-122">Define routing link codes for every operation that consumes the component.</span></span> <span data-ttu-id="7915d-123">Pour plus d'informations, reportez\-vous à [Procédure : Créer des gammes](production-how-to-create-routings.md).</span><span class="sxs-lookup"><span data-stu-id="7915d-123">For more information, see [How to: Create Routings ](production-how-to-create-routings.md).</span></span>  
6.  <span data-ttu-id="7915d-124">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Nomenclature de production**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="7915d-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Production BOM**, and then choose the related link.</span></span>  
7.  <span data-ttu-id="7915d-125">Associe aux codes lien gamme de chaque instance du composant l'opération dans laquelle il est consommé.</span><span class="sxs-lookup"><span data-stu-id="7915d-125">Define routing link codes from each instance of the component to the operation where it is consumed.</span></span>

    > [!IMPORTANT]  
    >  <span data-ttu-id="7915d-126">Le composant doit avoir un lien gamme l'associant à la dernière opération de la gamme.</span><span class="sxs-lookup"><span data-stu-id="7915d-126">The component must have a routing link to the last operation in the routing.</span></span>  

## <a name="see-also"></a><span data-ttu-id="7915d-127">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="7915d-127">See Also</span></span>  
[<span data-ttu-id="7915d-128">Procédure : créer des nomenclatures de production</span><span class="sxs-lookup"><span data-stu-id="7915d-128">How to: Create Production BOMs</span></span>](production-how-to-create-production-boms.md)  
[<span data-ttu-id="7915d-129">Paramétrage de la production</span><span class="sxs-lookup"><span data-stu-id="7915d-129">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="7915d-130">[Production](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="7915d-130">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
<span data-ttu-id="7915d-131">[Planifié](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="7915d-131">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="7915d-132">STOCKS ET EN-COURS</span><span class="sxs-lookup"><span data-stu-id="7915d-132">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="7915d-133">Achats</span><span class="sxs-lookup"><span data-stu-id="7915d-133">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="7915d-134">[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="7915d-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
