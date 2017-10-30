---
title: "Procédure : suivre les relations entre l'offre et la demande"
description: "À partir d'un document d'offre ou de demande dans le réseau d'ordres, vous pouvez suivre la demande de commande (quantité chaînée), les prévisions, les commandes ouvertes vente ou les paramètres de planification (quantité non chaînée) qui ont donné lieu à la ligne planning en question."
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
ms.openlocfilehash: acf030ab57c9251671900b1262dd8441c241c185
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-track-relations-between-demand-and-supply"></a><span data-ttu-id="b15c6-103">Procédure : suivre les relations entre l'offre et la demande</span><span class="sxs-lookup"><span data-stu-id="b15c6-103">How to: Track Relations Between Demand and Supply</span></span>
<span data-ttu-id="b15c6-104">À partir d'un document d'offre ou de demande dans le réseau d'ordres, vous pouvez suivre la demande de commande (quantité chaînée), les prévisions, les commandes ouvertes vente ou les paramètres de planification (quantité non chaînée) qui ont donné lieu à la ligne planning en question.</span><span class="sxs-lookup"><span data-stu-id="b15c6-104">From any supply or demand document in the so-called order network, you can track the order demand (tracked quantity), forecast, blanket sales order, or planning parameter (untracked quantity) that has given rise to the planning line in question.</span></span>

<span data-ttu-id="b15c6-105">Les feuilles planning incluent également des informations de planification sur les entités sans rapport avec les commandes pour aider le gestionnaire à obtenir un programme d'approvisionnement optimal.</span><span class="sxs-lookup"><span data-stu-id="b15c6-105">The planning worksheets also offers supporting planning information about non-order entities to help the planner obtain an optimal supply plan.</span></span> <span data-ttu-id="b15c6-106">Pour plus d'informations, voir la section « Éléments planning non chaînés ».</span><span class="sxs-lookup"><span data-stu-id="b15c6-106">For more information, see the "Untracked Planning Elements" section.</span></span>

## <a name="to-track-linked-items"></a><span data-ttu-id="b15c6-107">Pour chaîner des articles liés</span><span class="sxs-lookup"><span data-stu-id="b15c6-107">To track linked items</span></span>
<span data-ttu-id="b15c6-108">Par l'intermédiaire des systèmes de planification et de réservation, le chaînage montre le lien entre les commandes vente, les ordres de fabrication et les commandes achat.</span><span class="sxs-lookup"><span data-stu-id="b15c6-108">Order tracking shows how sales orders, production orders, and purchase orders are related to the manufacturing order through the planning and reservation systems.</span></span>

<span data-ttu-id="b15c6-109">La procédure suivante décrit comment chaîner des articles liés sur un ordre de fabrication planifié ferme.</span><span class="sxs-lookup"><span data-stu-id="b15c6-109">The following describes how to track linked items on a firm planned production order.</span></span> <span data-ttu-id="b15c6-110">La procédure est similaire pour tous les autres types de commande, et à partir des lignes feuille planning.</span><span class="sxs-lookup"><span data-stu-id="b15c6-110">The steps are similar for all other order types, and from planning worksheet lines.</span></span>

1. <span data-ttu-id="b15c6-111">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **O.F. planifié ferme**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="b15c6-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Firm Planned Prod. Order**, and then choose the related link.</span></span>
2. <span data-ttu-id="b15c6-112">Ouvrez l'O.F. planifié ferme approprié dans la liste.</span><span class="sxs-lookup"><span data-stu-id="b15c6-112">Open the relevant firm planned production order from the list.</span></span>
3. <span data-ttu-id="b15c6-113">Sur le raccourci **Lignes**, choisissez l'action **Fonctions**, puis l'action **Chaînage**.</span><span class="sxs-lookup"><span data-stu-id="b15c6-113">On the **Lines** FastTab, choose the **Functions** action, and then choose the **Order Tracking** action.</span></span>

<span data-ttu-id="b15c6-114">Les lignes de la fenêtre **Chaînage** affichent les documents liés à la ligne de l'ordre de fabrication en cours.</span><span class="sxs-lookup"><span data-stu-id="b15c6-114">The lines in the **Order Tracking** display the documents that are related to the current production order line.</span></span>

## <a name="untracked-planning-elements"></a><span data-ttu-id="b15c6-115">Éléments planning non chaînés</span><span class="sxs-lookup"><span data-stu-id="b15c6-115">Untracked Planning Elements</span></span>
<span data-ttu-id="b15c6-116">La fenêtre **Éléments planning non chaînés** s'affiche lorsque vous cliquez sur le champ **Qté non chaînée** dans la fenêtre **Planification commande**.</span><span class="sxs-lookup"><span data-stu-id="b15c6-116">The **Untracked Planning Elements** window opens when you choose the **Untracked Qty.** field in the **order Planning** window.</span></span> <span data-ttu-id="b15c6-117">Elle a deux objectifs :</span><span class="sxs-lookup"><span data-stu-id="b15c6-117">It serves two purposes:</span></span>

1. <span data-ttu-id="b15c6-118">Stockage d'informations sur les quantités non chaînées qui s'affichent lorsque l'utilisateur affiche la fenêtre Chaînage.</span><span class="sxs-lookup"><span data-stu-id="b15c6-118">To hold information about untracked quantities displayed when the user looks up from the Order Tracking window to see untracked quantities.</span></span>
2. <span data-ttu-id="b15c6-119">Stockage des messages d'avertissement qui s'affichent lorsque l'utilisateur clique sur l'icône **Avertissement** dans la fenêtre **Feuille planning**.</span><span class="sxs-lookup"><span data-stu-id="b15c6-119">To hold warning messages displayed when the user chooses the **Warning** icon in the **Planning Worksheet** window.</span></span>

<span data-ttu-id="b15c6-120">La fenêtre inclut les écritures représentant une quantité excédentaire non chaînée du réseau de chaînage.</span><span class="sxs-lookup"><span data-stu-id="b15c6-120">The window contains entries which account for an untracked surplus quantity in order tracking network.</span></span> <span data-ttu-id="b15c6-121">Ces écritures sont générées au cours de l'exécution de la planification et expliquent la provenance de la quantité excédentaire non chaînée des lignes chaînage.</span><span class="sxs-lookup"><span data-stu-id="b15c6-121">These entries are generated during the planning run and explain where the untracked surplus quantity in the order tracking lines came from.</span></span> <span data-ttu-id="b15c6-122">Cet excédent non chaîné peut provenir des lignes suivantes :</span><span class="sxs-lookup"><span data-stu-id="b15c6-122">This untracked surplus can come from:</span></span>

- <span data-ttu-id="b15c6-123">Prévisions production ;</span><span class="sxs-lookup"><span data-stu-id="b15c6-123">Production forecast</span></span>
- <span data-ttu-id="b15c6-124">Commandes ouvertes ;</span><span class="sxs-lookup"><span data-stu-id="b15c6-124">Blanket orders</span></span>
- <span data-ttu-id="b15c6-125">Stock de sécurité ;</span><span class="sxs-lookup"><span data-stu-id="b15c6-125">Safety stock quantity</span></span>
- <span data-ttu-id="b15c6-126">Point de commande ;</span><span class="sxs-lookup"><span data-stu-id="b15c6-126">Reorder point</span></span>
- <span data-ttu-id="b15c6-127">Stock maximum ;</span><span class="sxs-lookup"><span data-stu-id="b15c6-127">Maximum inventory</span></span>
- <span data-ttu-id="b15c6-128">Quantité de réappro. ;</span><span class="sxs-lookup"><span data-stu-id="b15c6-128">Reorder quantity</span></span>
- <span data-ttu-id="b15c6-129">Qté maximum commande ;</span><span class="sxs-lookup"><span data-stu-id="b15c6-129">Maximum order quantity</span></span>
- <span data-ttu-id="b15c6-130">Qté minimum commande ;</span><span class="sxs-lookup"><span data-stu-id="b15c6-130">Minimum order quantity</span></span>
- <span data-ttu-id="b15c6-131">Commandé par ;</span><span class="sxs-lookup"><span data-stu-id="b15c6-131">Order multiple</span></span>
- <span data-ttu-id="b15c6-132">Seuil (% taille lot).</span><span class="sxs-lookup"><span data-stu-id="b15c6-132">Dampener (% of lot size)</span></span>

## <a name="see-also"></a><span data-ttu-id="b15c6-133">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="b15c6-133">See Also</span></span>  
<span data-ttu-id="b15c6-134">[Planifié](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="b15c6-134">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="b15c6-135">Paramétrage de la production</span><span class="sxs-lookup"><span data-stu-id="b15c6-135">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="b15c6-136">[Production](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="b15c6-136">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
[<span data-ttu-id="b15c6-137">STOCKS ET EN-COURS</span><span class="sxs-lookup"><span data-stu-id="b15c6-137">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="b15c6-138">Achats</span><span class="sxs-lookup"><span data-stu-id="b15c6-138">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="b15c6-139">Détails de conception : réservation, chaînage et message d'action</span><span class="sxs-lookup"><span data-stu-id="b15c6-139">Design Details: Reservation, Tracking, and Action Messaging</span></span>](design-details-reservation-order-tracking-and-action-messaging.md)  
<span data-ttu-id="b15c6-140">[Détails de conception : planification de l'approvisionnement](design-details-supply-planning.md) </span><span class="sxs-lookup"><span data-stu-id="b15c6-140">[Design Details: Supply Planning](design-details-supply-planning.md) </span></span>  
[<span data-ttu-id="b15c6-141">Pratiques de configuration recommandées : planification de l'approvisionnement</span><span class="sxs-lookup"><span data-stu-id="b15c6-141">Setup Best Practices: Supply Planning</span></span>](setup-best-practices-supply-planning.md)  
<span data-ttu-id="b15c6-142">[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="b15c6-142">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

