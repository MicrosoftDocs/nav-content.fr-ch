---
title: "Détails de conception - Flux d'entrepôt internes"
description: "Circulation des articles entre les emplacements dans les centres d'une société lors du prélèvement des composants, du rangement des articles finis pour les ordres d'assemblage ou de fabrication et les mouvements ad-hoc, tels que les réapprovisionnements emplacement, sans relation avec les documents origine."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 42ada458f7cdeced83ee9bceb4b997691f3cf8bb
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-internal-warehouse-flows"></a><span data-ttu-id="cfd73-103">Détails de conception : flux d'entrepôt internes</span><span class="sxs-lookup"><span data-stu-id="cfd73-103">Design Details: Internal Warehouse Flows</span></span>
<span data-ttu-id="cfd73-104">Circulation des articles entre les emplacements dans les centres d'une société lors du prélèvement des composants, du rangement des articles finis pour les ordres d'assemblage ou de fabrication et les mouvements ad-hoc, tels que les réapprovisionnements emplacement, sans relation avec les documents origine.</span><span class="sxs-lookup"><span data-stu-id="cfd73-104">The flow of items between bins at a company location centers on picking components and putting away end items for assembly or production orders and ad-hoc movements, such as bin replenishments, without a relation to source documents.</span></span> <span data-ttu-id="cfd73-105">La portée et la nature des activités impliquées varient entre l'entreposage de base et l'entreposage avancé.</span><span class="sxs-lookup"><span data-stu-id="cfd73-105">The scope and nature of the involved activities vary between basic and advanced warehousing.</span></span>  

 <span data-ttu-id="cfd73-106">Certains flux internes chevauchent des flux entrants ou sortants.</span><span class="sxs-lookup"><span data-stu-id="cfd73-106">Some internal flows overlap with inbound or outbound flows.</span></span> <span data-ttu-id="cfd73-107">Une partie de cette superposition est illustrée aux étapes 4 et 5 dans les schémas graphiques des flux enlogement et désenlogement avancés respectivement.</span><span class="sxs-lookup"><span data-stu-id="cfd73-107">Some of this overlap is shown as steps 4 and 5 in the graphical diagrams for advanced inbound and outbound flows respectively.</span></span> <span data-ttu-id="cfd73-108">Pour plus d'informations, reportez\-vous à [Détails de conception : flux d'enlogement](design-details-outbound-warehouse-flow.md).</span><span class="sxs-lookup"><span data-stu-id="cfd73-108">For more information, see [Design Details: Inbound Warehouse Flow](design-details-outbound-warehouse-flow.md).</span></span>  

## <a name="internal-flows-in-basic-warehousing"></a><span data-ttu-id="cfd73-109">Flux internes dans l'entreposage de base</span><span class="sxs-lookup"><span data-stu-id="cfd73-109">Internal Flows in Basic Warehousing</span></span>  
 <span data-ttu-id="cfd73-110">Dans une configuration entrepôt de base, la circulation des articles entre les emplacements dans les centres de la société lors du prélèvement des composants, du rangement des articles finis pour les ordres de fabrication ou les ordres d'assemblage et les mouvements ad-hoc, tels que les réapprovisionnements emplacement, sans relation avec les documents origine.</span><span class="sxs-lookup"><span data-stu-id="cfd73-110">In basic warehouse configuration, the flow of items between bins inside the company centers on picking component and putting away end items for production or assembly orders and ad-hoc movements, such as bin replenishments, without relation to source documents.</span></span>  

### <a name="flows-to-and-from-production"></a><span data-ttu-id="cfd73-111">Flux entrants et sortants de la production</span><span class="sxs-lookup"><span data-stu-id="cfd73-111">Flows to and from Production</span></span>  
 <span data-ttu-id="cfd73-112">La principale intégration entre les ordres de fabrication et les activités d'entrepôt de base est représentée par la capacité de prélever des composants de production à l'aide de la fenêtre **Prélèvement stock** ou **Mouvement de stock**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-112">The main integration between production orders and basic warehouse activities is represented by the ability to pick production components with the **Inventory Pick** or the **Inventory Movement** windows.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="cfd73-113">Dans la fenêtre **Prélèvement stock**, la consommation de composants est validée lors de la validation du prélèvement.</span><span class="sxs-lookup"><span data-stu-id="cfd73-113">In the **Inventory Pick** window, the component consumption is posted together with the pick posting.</span></span> <span data-ttu-id="cfd73-114">À l'aide de la fenêtre **Mouvement de stock**, seuls les ajustements d'emplacement sont enregistrés, aucune validation dans la comptabilité article n'a lieu.</span><span class="sxs-lookup"><span data-stu-id="cfd73-114">By using the **Inventory Movement** window, only bin adjustments are registered, no item ledger posting occurs.</span></span>  

 <span data-ttu-id="cfd73-115">En plus de la gestion de composants, l'intégration est représentée par la capacité de ranger les articles fabriqués à l'aide de la fenêtre **Rangement stock**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-115">In addition to component handling, the integration is represented by the ability to put produced items away with the **Inventory Put-away** window.</span></span>  

 <span data-ttu-id="cfd73-116">Les champs **To-Production Bin Code**, **From-Production Bin Code**, et **Open Shop Floor Bin Code** de la fiche magasin ou des fiches poste/centre de charge définissent les flux par défaut depuis ou vers les zones de production.</span><span class="sxs-lookup"><span data-stu-id="cfd73-116">The **To-Production Bin Code**, **From-Production Bin Code**, and **Open Shop Floor Bin Code** fields on the location card or the machine/work center cards define default flows to and from production areas.</span></span>  

 <span data-ttu-id="cfd73-117">Pour plus d'informations sur la manière dont la consommation de composants est vidée des emplacements des consommations ou des emplacements atelier ouverts, reportez-vous à la section « Consommation des composants de production dans l'entrepôt » de cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="cfd73-117">For more information about how component consumption is flushed from the To-Production or Open Shop Floor bins, see the “Flushing Production Components in the Warehouse” section in this topic.</span></span>  

### <a name="flows-to-and-from-assembly"></a><span data-ttu-id="cfd73-118">Flux entrants et sortants de l'assemblage</span><span class="sxs-lookup"><span data-stu-id="cfd73-118">Flows to and from Assembly</span></span>  
 <span data-ttu-id="cfd73-119">La principale intégration entre les ordres d'assemblage et les activités d'entrepôt de base est représentée par la capacité de déplacer les composants d'assemblage vers la zone d'assemblage.</span><span class="sxs-lookup"><span data-stu-id="cfd73-119">The main integration between assembly orders and basic warehouse activities is represented by the ability to move assembly components to the assembly area.</span></span>  

 <span data-ttu-id="cfd73-120">Lorsqu'aucune fonctionnalité entrepôt spécifique n'existe pour le stockage des éléments d'assemblage, le code d'emplacement sur l'ordre d'assemblage peut être défini sur un emplacement de stockage par défaut.</span><span class="sxs-lookup"><span data-stu-id="cfd73-120">While no specific warehouse functionality exists for putting assembly items away, the bin code on the assembly order header may be set to a default put-away bin.</span></span> <span data-ttu-id="cfd73-121">La validation de l'ordre d'assemblage fonctionne alors comme la validation d'un rangement.</span><span class="sxs-lookup"><span data-stu-id="cfd73-121">Posting the assembly order then functions like posting a put-away.</span></span> <span data-ttu-id="cfd73-122">L'activité entrepôt pour déplacer des éléments d'assemblage dans l'entrepôt peut être gérée dans la fenêtre **Mouvement interne**, sans rapport avec l'ordre d'assemblage.</span><span class="sxs-lookup"><span data-stu-id="cfd73-122">The warehouse activity to move assembly items into the warehouse can be managed in the **Internal Movement** window, with no relation to the assembly order.</span></span>  

 <span data-ttu-id="cfd73-123">Les flux d'assemblage suivants existent.</span><span class="sxs-lookup"><span data-stu-id="cfd73-123">The following assembly flows exist.</span></span>  

|<span data-ttu-id="cfd73-124">Flux de travail</span><span class="sxs-lookup"><span data-stu-id="cfd73-124">Flow</span></span>|<span data-ttu-id="cfd73-125">Désignation</span><span class="sxs-lookup"><span data-stu-id="cfd73-125">Description</span></span>|  
|----------|---------------------------------------|  
|<span data-ttu-id="cfd73-126">Assembler pour stock</span><span class="sxs-lookup"><span data-stu-id="cfd73-126">Assemble-to-stock</span></span>|<span data-ttu-id="cfd73-127">Les composants sont nécessaires sur un ordre d'assemblage dans lequel la production est stockée dans l'entrepôt.</span><span class="sxs-lookup"><span data-stu-id="cfd73-127">The components are needed on an assembly order where the output is stored in the warehouse.</span></span><br /><br /> <span data-ttu-id="cfd73-128">Ce flux d'entrepôt est géré dans la fenêtre **Mouvement de stock**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-128">This warehouse flow is managed in the **Inventory Movement** window.</span></span> <span data-ttu-id="cfd73-129">Une ligne prélèvement spécifie où prélever les composants.</span><span class="sxs-lookup"><span data-stu-id="cfd73-129">One take line specifies where to take the components.</span></span> <span data-ttu-id="cfd73-130">Une ligne d'emplacement spécifie où placer les composants.</span><span class="sxs-lookup"><span data-stu-id="cfd73-130">One place line specifies where to place the components.</span></span>|  
|<span data-ttu-id="cfd73-131">Assembler pour commande</span><span class="sxs-lookup"><span data-stu-id="cfd73-131">Assemble-to-order</span></span>|<span data-ttu-id="cfd73-132">Les composants sont nécessaires sur un ordre d'assemblage qui est lié à une commande vente expédiée lors de l'assemblage de l'article vendu.</span><span class="sxs-lookup"><span data-stu-id="cfd73-132">The components are needed on an assembly order that is linked to a sales order that is shipped when the sold item is assembled.</span></span>|  

> [!NOTE]  
>  <span data-ttu-id="cfd73-133">Si les articles sont assemblés pour commande, le prélèvement stock de la commande vente liée déclenche un mouvement de stock pour tous les composants d'assemblage impliqués, et non seulement pour l'article vendu, comme lors de l'expédition d'articles en stock.</span><span class="sxs-lookup"><span data-stu-id="cfd73-133">If items are assembled to order, then the inventory pick of the linked sales order triggers an inventory movement for all the involved assembly components, not just for the sold item as when shipping inventory items.</span></span>  

 <span data-ttu-id="cfd73-134">Les champs **Code empl. vers assemblage**, **Code empl. depuis assemblage** et **Code empl. exp. ass. pr comm.** de la fiche magasin définissent les flux par défaut depuis et vers les champs d'assemblage.</span><span class="sxs-lookup"><span data-stu-id="cfd73-134">The **To-Assembly Bin Code**, **From-Assembly Bin Code**, and **Asm.-to-Order Shpt. Bin Code** fields on the location card define default flows to and from assembly areas.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="cfd73-135">Le champ **Code empl. exp. ass. pr comm.** fonctionne comme emplacement après assemblage dans les scénarios assembler pour commande.</span><span class="sxs-lookup"><span data-stu-id="cfd73-135">The **Asm.-to-Order Shpt. Bin Code** field functions as the from-assembly bin in assemble-to-order scenarios.</span></span>  

### <a name="ad-hoc-movements"></a><span data-ttu-id="cfd73-136">Mouvements ad hoc</span><span class="sxs-lookup"><span data-stu-id="cfd73-136">Ad-Hoc Movements</span></span>  
 <span data-ttu-id="cfd73-137">Dans l'entreposage de base, un mouvement d'articles d'un emplacement à un autre sans relation avec les documents origine est effectué dans la fenêtre **Mouvement interne** qui fonctionne conjointement avec la fenêtre **Mouvement de stock**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-137">In basic warehousing, the movement of items from bin to bin without relation to source documents is performed in the **Internal Movement** window, which functions together with the **Inventory Movement** window.</span></span>  

 <span data-ttu-id="cfd73-138">Il existe un autre moyen de déplacer des articles ad hoc entre les emplacements : il suffit de valider les écritures positives dans le champ **Nouveau code emplacement** de la fenêtre **Feuille reclassement article**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-138">Another way to move items ad hoc between bins is to post positive entries in the **New Bin Code** field in the **Item Reclass. Journal** window.</span></span>  

## <a name="internal-flows-in-advanced-warehousing"></a><span data-ttu-id="cfd73-139">Flux internes dans l'entreposage avancé</span><span class="sxs-lookup"><span data-stu-id="cfd73-139">Internal Flows in Advanced Warehousing</span></span>  
 <span data-ttu-id="cfd73-140">Dans les configurations d'entrepôt avancées, la circulation des articles entre les emplacements dans les centres de la société lors du prélèvement des composants, du rangement des articles finis pour les ordres de fabrication et du prélèvement des composants pour les ordres d'assemblage.</span><span class="sxs-lookup"><span data-stu-id="cfd73-140">In advanced warehouse configurations, the flow of items between bins inside the company centers on picking component and putting away end items for production orders and picking components for assembly orders.</span></span> <span data-ttu-id="cfd73-141">En outre, les flux internes se produisent en tant que mouvements ad-hoc, tels que les réapprovisionnements emplacement, sans relation avec les documents origine.</span><span class="sxs-lookup"><span data-stu-id="cfd73-141">In addition, internal flows occur as ad-hoc movements, such as bin replenishments, without relation to source documents.</span></span>  

### <a name="flows-to-and-from-production"></a><span data-ttu-id="cfd73-142">Flux entrants et sortants de la production</span><span class="sxs-lookup"><span data-stu-id="cfd73-142">Flows To and From Production</span></span>  
 <span data-ttu-id="cfd73-143">La principale intégration entre les ordres de fabrication et les activités d'entrepôt avancées est représentée par la capacité de prélever des composants de production, dans la fenêtre **Prélèvement entrepôt** et dans la fenêtre, **Feuille prélèvement**, et par la capacité de ranger des articles fabriqués à l'aide de la fenêtre **Rangement interne entrepôt**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-143">The main integration between production orders and advanced warehouse activities is represented by the ability to pick production components, in the **Warehouse Pick** window and the **Pick Worksheet** window, and the ability to put produced items away with the **Whse. Internal-Put-away** window.</span></span>  

 <span data-ttu-id="cfd73-144">Un autre point d'intégration dans la production est fourni via la fenêtre **Mouvement entrepôt**, ainsi que la fenêtre Feuille mouvement, ce qui vous permet de placer des composants et de prendre des articles fabriqués pour des ordres de fabrication lancés.</span><span class="sxs-lookup"><span data-stu-id="cfd73-144">Another integration point in production is provided with the **Warehouse Movement** window, together with the Movement Worksheet window, which enables you to place components and take produced items for released production orders.</span></span>  

 <span data-ttu-id="cfd73-145">Les champs **To-Production Bin Code**, **From-Production Bin Code**, et **Open Shop Floor Bin Code** de la fiche magasin ou des fiches poste/centre de charge définissent les flux par défaut depuis ou vers les zones de production.</span><span class="sxs-lookup"><span data-stu-id="cfd73-145">The **To-Production Bin Code**, **From-Production Bin Code**, and **Open Shop Floor Bin Code** fields on the location card or the machine/work center cards define default flows to and from production areas.</span></span>  

 <span data-ttu-id="cfd73-146">Pour plus d'informations sur la manière dont la consommation de composants est vidée des emplacements des consommations ou des emplacements atelier ouverts, reportez-vous à la section « Consommation des composants de production dans l'entrepôt » de cette rubrique.</span><span class="sxs-lookup"><span data-stu-id="cfd73-146">For more information about how component consumption is flushed from the To-Production or Open Shop Floor Bins, see the “Flushing Production Components in the Warehouse” section in this topic.</span></span>  

### <a name="flows-to-and-from-assembly"></a><span data-ttu-id="cfd73-147">Flux entrants et sortants de l'assemblage</span><span class="sxs-lookup"><span data-stu-id="cfd73-147">Flows to and from Assembly</span></span>  
 <span data-ttu-id="cfd73-148">La principale intégration entre les ordres d'assemblage et les activités d'entrepôt avancées est représentée par la capacité de prélever des composants d'assemblage, aussi bien à l'aide de la fenêtre **Prélèvement entrepôt** que de la fenêtre **Feuille prélèvement**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-148">The main integration between assembly orders and advanced warehouse activities is represented by the ability to pick assembly components, both with the **Warehouse Pick** window and the **Pick Worksheet** window.</span></span> <span data-ttu-id="cfd73-149">Cette fonctionnalité est identique au prélèvement des composants pour les ordres de fabrication.</span><span class="sxs-lookup"><span data-stu-id="cfd73-149">This functionality works just like when picking components for production orders.</span></span>  

 <span data-ttu-id="cfd73-150">Lorsqu'aucune fonctionnalité entrepôt spécifique n'existe pour le stockage des éléments d'assemblage, le code d'emplacement sur l'ordre d'assemblage peut être défini sur un emplacement de stockage par défaut.</span><span class="sxs-lookup"><span data-stu-id="cfd73-150">While no specific warehouse functionality exists for putting assembly items away, the bin code on the assembly order header may be set to a default put-away bin.</span></span> <span data-ttu-id="cfd73-151">La validation de l'ordre d'assemblage fonctionne alors comme la validation d'un rangement.</span><span class="sxs-lookup"><span data-stu-id="cfd73-151">Posting the assembly order then functions like posting a put-away.</span></span> <span data-ttu-id="cfd73-152">L'activité entrepôt pour déplacer des éléments d'assemblage dans l'entrepôt peut être gérée dans la fenêtre **Feuille mouvement** ou la fenêtre **Rangement interne entrepôt**, sans rapport avec l'ordre d'assemblage.</span><span class="sxs-lookup"><span data-stu-id="cfd73-152">The warehouse activity to move assembly items into the warehouse can be managed in the **Movement Worksheet** window or the **Whse. Internal Put-away** window, with no relation to the assembly order.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="cfd73-153">Si les articles sont assemblés pour commande, l'expédition entrepôt de la commande vente liée déclenche un prélèvement entrepôt de tous les composants d'assemblage impliqués, et non seulement de l'article vendu, comme lors de l'expédition d'articles en stock.</span><span class="sxs-lookup"><span data-stu-id="cfd73-153">If items are assembled to order, then the warehouse shipment of the linked sales order triggers a warehouse pick for all the involved assembly components, not just for the sold item as when shipping inventory items.</span></span>  

 <span data-ttu-id="cfd73-154">Les champs **To-Assembly Bin Code** **From-Assembly Bin Code** de la fiche magasin définissent les flux par défaut depuis et vers les champs d'assemblage.</span><span class="sxs-lookup"><span data-stu-id="cfd73-154">The **To-Assembly Bin Code** and **From-Assembly Bin Code** fields on the location card define default flows to and from assembly areas.</span></span>  

### <a name="ad-hoc-movements"></a><span data-ttu-id="cfd73-155">Mouvements ad hoc</span><span class="sxs-lookup"><span data-stu-id="cfd73-155">Ad-Hoc Movements</span></span>  
 <span data-ttu-id="cfd73-156">Dans l'entreposage avancé, un mouvement d'articles d'un emplacement à un autre sans relation avec les documents origine est géré dans la fenêtre **Feuille mouvement** et enregistré dans la fenêtre Mouvement entrepôt.</span><span class="sxs-lookup"><span data-stu-id="cfd73-156">In advanced warehousing, the movement of items from bin to bin without relation to source documents is managed in the **Movement Worksheet** window and registered in the Warehouse Movement window.</span></span>  

## <a name="flushing-production-components-in-the-warehouse"></a><span data-ttu-id="cfd73-157">Consommation des composants de production dans l'entrepôt</span><span class="sxs-lookup"><span data-stu-id="cfd73-157">Flushing Production Components in the Warehouse</span></span>  
 <span data-ttu-id="cfd73-158">Si cela est paramétré dans la fiche article, les composants prélevés avec des prélèvements entrepôt sont validés comme étant consommés par l'ordre de fabrication lorsque le prélèvement entrepôt est enregistré.</span><span class="sxs-lookup"><span data-stu-id="cfd73-158">If set up on the item card, components picked with warehouse picks are posted as consumed by the production order when the warehouse pick is registered.</span></span> <span data-ttu-id="cfd73-159">En utilisant la méthode **Prélèvement + Aval** et la méthode de consommation **Prélèvement + Amont**, l'enregistrement de prélèvement déclenche la validation des consommations associées lorsque la première opération commence ou lorsque la dernière opération finit, respectivement.</span><span class="sxs-lookup"><span data-stu-id="cfd73-159">By using the **Pick + Forward** method and the **Pick + Backward** flushing method, the pick registration triggers the related consumption posting when the first operation starts or when the last operation finishes, respectively.</span></span>  

 <span data-ttu-id="cfd73-160">Considérez le scénario suivant basé sur la base de données de démonstration [!INCLUDE[d365fin](includes/d365fin_md.md)], magasin BLANC.</span><span class="sxs-lookup"><span data-stu-id="cfd73-160">Consider the following scenario based on the [!INCLUDE[d365fin](includes/d365fin_md.md)] demonstration database, WHITE location.</span></span>  

 <span data-ttu-id="cfd73-161">Il existe un ordre de fabrication pour 15 pièces de l'article LS-100.</span><span class="sxs-lookup"><span data-stu-id="cfd73-161">A production order for 15 PCS of item LS-100 exists.</span></span> <span data-ttu-id="cfd73-162">Certains articles sur la liste des composants doivent être consommés manuellement dans une feuille consommation et d'autres articles de la liste peuvent être prélevés et consommés automatiquement à l'aide de la méthode de consommation **Prélèvement + Amont**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-162">Some of the items on the component list must be flushed manually in a consumption journal, and other items on the list can be picked and flushed automatically using the **Pick + Backward** flushing method.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="cfd73-163">**Prélèvement + Aval** ne fonctionne que si la deuxième opération ligne gamme de production utilise le code lien gamme.</span><span class="sxs-lookup"><span data-stu-id="cfd73-163">**Pick + Forward** only works if the second production routing line operation uses a routing link code.</span></span> <span data-ttu-id="cfd73-164">Le lancement d'un ordre de fabrication planifié lance la consommation en aval des composants paramétrés sur **Prélèvement + Aval**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-164">Releasing a planned production order initiates forward flushing of components set to **Pick + Forward**.</span></span> <span data-ttu-id="cfd73-165">Toutefois, la consommation ne peut pas avoir lieu tant que le prélèvement des composants n'est pas enregistré, ce qui à nouveau ne peut avoir lieu que lorsque la commande est lancée.</span><span class="sxs-lookup"><span data-stu-id="cfd73-165">However, the flushing cannot take place until the pick of the components is registered, which again can only take place when the order is released.</span></span>  

 <span data-ttu-id="cfd73-166">Les étapes suivantes décrivent les actions impliquées par divers utilisateurs et la réponse associée :</span><span class="sxs-lookup"><span data-stu-id="cfd73-166">The following steps describe the involved actions by different users and the related response:</span></span>  

1.  <span data-ttu-id="cfd73-167">Le chef atelier lance l'ordre de fabrication.</span><span class="sxs-lookup"><span data-stu-id="cfd73-167">The shop floor supervisor releases the production order.</span></span> <span data-ttu-id="cfd73-168">Les articles utilisant la méthode de consommation **Aval** et aucun code lien gamme sont déduits de l'emplacement atelier ouvert.</span><span class="sxs-lookup"><span data-stu-id="cfd73-168">Items with **Forward** flushing method and no routing link code are deducted from the open shop floor bin.</span></span>  
2.  <span data-ttu-id="cfd73-169">Le chef atelier choisit le bouton **Créer prélèvement entrepôt** sur l'ordre de fabrication.</span><span class="sxs-lookup"><span data-stu-id="cfd73-169">The shop floor supervisor chooses the **Create Warehouse Pick** button on the production order.</span></span> <span data-ttu-id="cfd73-170">Un document prélèvement entrepôt est créé pour les articles avec les méthodes de consommation **Manuelle**, **Prélèvement + Amont** et **Prélèvement + Aval**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-170">A warehouse pick document is created pick for items with **Manual**, **Pick + Backward**, and **Pick + Forward** flushing methods.</span></span> <span data-ttu-id="cfd73-171">Ces articles sont placés dans l'emplacement des consommations.</span><span class="sxs-lookup"><span data-stu-id="cfd73-171">These items are placed in the To-Production bin.</span></span>  
3.  <span data-ttu-id="cfd73-172">Le gestionnaire d'entrepôt affecte les prélèvements à un magasinier.</span><span class="sxs-lookup"><span data-stu-id="cfd73-172">The warehouse manager assigns the picks to a warehouse worker.</span></span>  
4.  <span data-ttu-id="cfd73-173">Le magasinier prélève les articles des emplacements appropriés et les place dans l'emplacement des consommations ou dans l'emplacement spécifié sur le prélèvement entrepôt, qui peut être un emplacement de centre de charge ou du poste de charge).</span><span class="sxs-lookup"><span data-stu-id="cfd73-173">The warehouse worker picks the items from appropriate bins and places them in the To-Production bin or in the bin specified on the warehouse pick, which may be a work center or machine center bin).</span></span>  
5.  <span data-ttu-id="cfd73-174">Le magasinier enregistre le prélèvement.</span><span class="sxs-lookup"><span data-stu-id="cfd73-174">The warehouse worker registers the pick.</span></span> <span data-ttu-id="cfd73-175">La quantité est soustraite des emplacements prélèvement et ajoutée à l'emplacement de consommation.</span><span class="sxs-lookup"><span data-stu-id="cfd73-175">The quantity is subtracted from the pick bins and added to the consumption bin.</span></span> <span data-ttu-id="cfd73-176">Le champ **Qté prélevée** sur la liste des composants de tous les articles prélevés est mis à jour.</span><span class="sxs-lookup"><span data-stu-id="cfd73-176">The **Qty. Picked** field on the component list for all picked items is updated.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="cfd73-177">Seule la quantité qui est prélevée peut être consommée.</span><span class="sxs-lookup"><span data-stu-id="cfd73-177">Only the quantity that is picked can be consumed.</span></span>  

6.  <span data-ttu-id="cfd73-178">L'opérateur indique au gestionnaire de production que les articles finis sont terminés.</span><span class="sxs-lookup"><span data-stu-id="cfd73-178">The machine operator informs the production manager that the end items are finished.</span></span>  
7.  <span data-ttu-id="cfd73-179">Le chef atelier utilise la feuille consommation ou la feuille production pour valider la consommation de composants qui utilisent la méthode de consommation **Manuel** ou les méthodes de consommation **Aval** ou **Prélèvement + Aval** avec des codes lien gamme.</span><span class="sxs-lookup"><span data-stu-id="cfd73-179">The shop floor supervisor uses the consumption journal or production journal to post the consumption of component items that use either **Manual** flushing method or **Forward** or **Pick + Forward** flushing methods together with routing link codes.</span></span>  
8.  <span data-ttu-id="cfd73-180">Le gestionnaire de production valide la production de l'ordre de fabrication et modifie le statut en **Terminé**.</span><span class="sxs-lookup"><span data-stu-id="cfd73-180">The production manager posts the output of the production order and changes status to **Finished**.</span></span> <span data-ttu-id="cfd73-181">La quantité de composants qui utilisent la méthode de consommation **En amont** est déduite de l'emplacement atelier ouvert, et la quantité de composants qui utilisent la méthode de consommation **Prélèvement + Amont** est déduite de l'emplacement des consommations.</span><span class="sxs-lookup"><span data-stu-id="cfd73-181">The quantity of component items that use **Backward** flushing method is deducted from the open shop floor bin, and the quantity of component items that use **Pick + Backward** flushing method is deducted from the To-Production bin.</span></span>  

 <span data-ttu-id="cfd73-182">La figure ci-après indique la date à laquelle le champ **Code emplacement** de la liste des composants est renseigné en fonction du paramétrage de votre magasin ou poste/centre de charge.</span><span class="sxs-lookup"><span data-stu-id="cfd73-182">The following illustration shows when the **Bin Code** field on the component list is filled according to your location or machine/work center setup.</span></span>  

 <span data-ttu-id="cfd73-183">![Organigramme Flux d'emplacement](media/binflow.png "BinFlow")</span><span class="sxs-lookup"><span data-stu-id="cfd73-183">![Bin flow chart](media/binflow.png "BinFlow")</span></span>  

## <a name="see-also"></a><span data-ttu-id="cfd73-184">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="cfd73-184">See Also</span></span>  
 [<span data-ttu-id="cfd73-185">Détails de conception : gestion d'entrepôt</span><span class="sxs-lookup"><span data-stu-id="cfd73-185">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)
