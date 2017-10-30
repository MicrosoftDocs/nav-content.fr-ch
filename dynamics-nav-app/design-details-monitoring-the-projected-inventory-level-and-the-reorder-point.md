---
title: "Détails de conception : surveillance du niveau de stock prévisionnel et du point de commande"
description: "Découvrez comment la planification de stock différencie les niveaux de stock prévisionnel des niveaux de stock disponible projeté."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, supply, inventory, planning
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ef99b84a635a8403c62c38b8a66e77166bbf2883
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-monitoring-the-projected-inventory-level-and-the-reorder-point"></a><span data-ttu-id="c6176-103">Détails de conception : surveillance du niveau de stock prévisionnel et du point de commande</span><span class="sxs-lookup"><span data-stu-id="c6176-103">Design Details: Monitoring the Projected Inventory Level and the Reorder Point</span></span>
<span data-ttu-id="c6176-104">Le stock est un type d'approvisionnement, mais pour la planification de stock, le système de planification différencie deux niveaux de stock :</span><span class="sxs-lookup"><span data-stu-id="c6176-104">Inventory is a type of supply, but for inventory planning, the planning system distinguishes between two inventory levels:</span></span>  

* <span data-ttu-id="c6176-105">Stock projeté</span><span class="sxs-lookup"><span data-stu-id="c6176-105">Projected inventory</span></span>  
* <span data-ttu-id="c6176-106">Stock disponible projeté</span><span class="sxs-lookup"><span data-stu-id="c6176-106">Projected available inventory</span></span>  

## <a name="projected-inventory"></a><span data-ttu-id="c6176-107">Stocks projetés</span><span class="sxs-lookup"><span data-stu-id="c6176-107">Projected Inventory</span></span>  
<span data-ttu-id="c6176-108">Normalement, le stock prévisionnel est la quantité de stock brut, y compris les demandes et approvisionnements du passé même si non validés, au début du processus de planification.</span><span class="sxs-lookup"><span data-stu-id="c6176-108">Initially, projected inventory is the quantity of gross inventory, including supply and demand in the past even if not posted, when starting the planning process.</span></span> <span data-ttu-id="c6176-109">Dans le futur, cela devient un niveau de stock prévisionnel mobile qui est mis à jour par les quantités brutes d'un approvisionnement et d'une demande futurs parce que ceux-ci sont saisis suivant le planning (réservés ou affectés autrement).</span><span class="sxs-lookup"><span data-stu-id="c6176-109">In the future, this becomes a moving projected inventory level that is maintained by gross quantities from future supply and demand because those are introduced along the time line (whether reserved or in other ways allocated).</span></span>  

<span data-ttu-id="c6176-110">Le stock prévisionnel est utilisé par le système de planification pour contrôler le point de commande et pour déterminer la quantité de réapprovisionnement lorsque la méthode de réapprovisionnement Qté maximum est utilisée.</span><span class="sxs-lookup"><span data-stu-id="c6176-110">The projected inventory is used by the planning system to monitor the reorder point and to determine the reorder quantity when using the Maximum Qty. reordering policy.</span></span>  

## <a name="projected-available-inventory"></a><span data-ttu-id="c6176-111">Stock disponible projeté</span><span class="sxs-lookup"><span data-stu-id="c6176-111">Projected Available Inventory</span></span>  
<span data-ttu-id="c6176-112">Le stock disponible projeté est la partie du stock prévisionnel qui est disponible à un moment donné pour répondre à une demande.</span><span class="sxs-lookup"><span data-stu-id="c6176-112">The projected available inventory is the part of the projected inventory that at a given point in time is available to fulfill demand.</span></span> <span data-ttu-id="c6176-113">Le stock disponible projeté est utilisé par le moteur de planification lors du contrôle du niveau de stock de sécurité.</span><span class="sxs-lookup"><span data-stu-id="c6176-113">The projected available inventory is used by the planning engine when monitoring the safety stock level.</span></span>  

<span data-ttu-id="c6176-114">Le stock disponible projeté est utilisé par le système de planification pour contrôler le niveau de stock de sécurité, parce que le stock de sécurité doit toujours être disponible pour satisfaire une demande inattendue.</span><span class="sxs-lookup"><span data-stu-id="c6176-114">The projected available inventory is used by the planning system to monitor the safety stock level, since the safety stock must always be available to serve unexpected demand.</span></span>  

## <a name="time-buckets"></a><span data-ttu-id="c6176-115">Intervalles de planification</span><span class="sxs-lookup"><span data-stu-id="c6176-115">Time Buckets</span></span>  
<span data-ttu-id="c6176-116">Posséder un contrôle étroit du stock prévisionnel est crucial pour détecter le moment où le point de commande est atteint et pour calculer la quantité de commande correcte en utilisant la méthode de réapprovisionnement Qté maximum.</span><span class="sxs-lookup"><span data-stu-id="c6176-116">Having a tight control of the projected inventory is crucial to detect when the reorder point is reached or crossed and to calculate the right order quantity when using the Maximum Qty. reordering policy.</span></span>  

<span data-ttu-id="c6176-117">Comme indiqué précédemment, le niveau de stock projeté est calculé au début de la période de planification.</span><span class="sxs-lookup"><span data-stu-id="c6176-117">As stated earlier, the projected inventory level is calculated at the start of the planning period.</span></span> <span data-ttu-id="c6176-118">Il s'agit d'un niveau brut qui ne tient pas compte des réservations et des ventilations similaires.</span><span class="sxs-lookup"><span data-stu-id="c6176-118">It is a gross level that does not consider reservations and similar allocations.</span></span> <span data-ttu-id="c6176-119">Pour contrôler ce niveau de stock durant la séquence de planification, le système gère les changements cumulés sur une période de temps, un intervalle de planification.</span><span class="sxs-lookup"><span data-stu-id="c6176-119">To monitor this inventory level during the planning sequence, the system monitors the aggregated changes over a period of time, a time bucket.</span></span> <span data-ttu-id="c6176-120">Le système garantit que l'intervalle de planification est au moins d'un jour comme il s'agit de l'unité de temps la plus précise pour une demande ou un événement d'approvisionnement.</span><span class="sxs-lookup"><span data-stu-id="c6176-120">The system ensures that the time bucket is at least one day since it is the most precise unit of time for a demand or supply event.</span></span>  

## <a name="determining-the-projected-inventory-level"></a><span data-ttu-id="c6176-121">Déterminer le niveau de stock prévisionnel</span><span class="sxs-lookup"><span data-stu-id="c6176-121">Determining the Projected Inventory Level</span></span>  
<span data-ttu-id="c6176-122">La prochaine séquence décrit la manière dont le niveau de stock prévisionnel est déterminé :</span><span class="sxs-lookup"><span data-stu-id="c6176-122">The following sequence describes how the projected inventory level is determined:</span></span>  

* <span data-ttu-id="c6176-123">Lorsqu'un événement d'approvisionnement, tel qu'une commande achat, a été totalement planifié, il augmente le stock prévisionnel à sa date d'échéance.</span><span class="sxs-lookup"><span data-stu-id="c6176-123">When a supply event, such as a purchase order has been totally planned, it will increase the projected inventory on its due date.</span></span>  
* <span data-ttu-id="c6176-124">Lorsqu'un événement de demande a été entièrement satisfait, il ne diminue pas le stock prévisionnel immédiatement.</span><span class="sxs-lookup"><span data-stu-id="c6176-124">When a demand event has been fully satisfied, it will not decrease the projected inventory right away.</span></span> <span data-ttu-id="c6176-125">Au lieu de cela, il valide une relance de baisse, qui est un enregistrement interne qui contient la date et la quantité de la contribution au stock prévisionnel.</span><span class="sxs-lookup"><span data-stu-id="c6176-125">Instead, it posts a decrease reminder, which is an internal record that holds the date and quantity of the contribution to the projected inventory.</span></span>  
* <span data-ttu-id="c6176-126">Lorsqu'un événement d'approvisionnement ultérieur est planifié et placé sur la chronologie, les rappels de diminution publiés sont examinés un à un jusqu'à la date d'approvisionnement planifiée tout en mettant à jour le stock prévisionnel.</span><span class="sxs-lookup"><span data-stu-id="c6176-126">When a subsequent supply event is planned and placed on the time line, the posted decrease reminders are investigated one by one up until the planned date of the supply while updating the projected inventory.</span></span> <span data-ttu-id="c6176-127">Lors de ce processus, le niveau du point de commande de la relance interne d'augmentation peut être atteint ou dépassé.</span><span class="sxs-lookup"><span data-stu-id="c6176-127">During this process, the reorder point level of the internal increase reminder may be reached or crossed.</span></span>  
* <span data-ttu-id="c6176-128">Si une nouvelle commande approvisionnement est créée, le système vérifie si elle est saisie avant l'approvisionnement actif.</span><span class="sxs-lookup"><span data-stu-id="c6176-128">If a new supply order is introduced, the system checks if it is entered before the current supply.</span></span> <span data-ttu-id="c6176-129">Si c'est le cas, le nouvel approvisionnement devient l'approvisionnement actif et la procédure d'équilibrage reprend depuis le début.</span><span class="sxs-lookup"><span data-stu-id="c6176-129">If it is, the new supply becomes current supply and the balancing procedure starts over.</span></span>  

<span data-ttu-id="c6176-130">Voici une illustration graphique de ce principe :</span><span class="sxs-lookup"><span data-stu-id="c6176-130">The following shows a graphical illustration of this principle:</span></span>  

![](media/nav_app_supply_planning_2_projected_inventory.png "NAV_APP_supply_planning_2_projected_inventory")  

1. <span data-ttu-id="c6176-131">L'approvisionnement **Sa** de 4 (fixe) clôture la demande **Da** de 3.</span><span class="sxs-lookup"><span data-stu-id="c6176-131">Supply **Sa** of 4 (fixed) closes Demand **Da** of -3.</span></span>  
2. <span data-ttu-id="c6176-132">CloseDemand : créez une relance de baisse de -3 (pas affiché).</span><span class="sxs-lookup"><span data-stu-id="c6176-132">CloseDemand: Create a decrease reminder of -3 (not shown).</span></span>  
3. <span data-ttu-id="c6176-133">L'approvisionnement **Sa** est clôturé avec un excédent de 1 (plus aucune demande n'existe).</span><span class="sxs-lookup"><span data-stu-id="c6176-133">Supply **Sa** is closed with a surplus of 1 (no more demand exists).</span></span>  

     <span data-ttu-id="c6176-134">Cela augmente le niveau de stock prévisionnel à +4, alors que le stock **disponible** devient -1.</span><span class="sxs-lookup"><span data-stu-id="c6176-134">This increases the projected inventory level to +4, while the projected **available** inventory becomes -1.</span></span>  

4. <span data-ttu-id="c6176-135">L'approvisionnement suivant **Sb** de 2 (une autre commande) a déjà été placé dans la chronologie.</span><span class="sxs-lookup"><span data-stu-id="c6176-135">The next supply **Sb** of 2 (another order) has already been placed on the timeline.</span></span>  
5. <span data-ttu-id="c6176-136">Le système vérifie s'il y a des relances de sortie précédant **Sb** (il n'y en a pas, donc aucune action n'est prise).</span><span class="sxs-lookup"><span data-stu-id="c6176-136">System checks if there is any decrease reminder preceding **Sb** (there is not, so no action is taken).</span></span>  
6. <span data-ttu-id="c6176-137">Le système ferme l'approvisionnement **Sb** (plus aucune demande n'existe)—A : en réduisant à 0 (annuler) ou B : en le laissant tel quel.</span><span class="sxs-lookup"><span data-stu-id="c6176-137">System closes supply **Sb** (no more demand exists)—either A: by reducing it to 0 (cancel) or B: by leaving as is.</span></span>  

     <span data-ttu-id="c6176-138">Cela entraîne l'augmentation du niveau de stock projeté (A : +0 => +4 or B : +2 = +6).</span><span class="sxs-lookup"><span data-stu-id="c6176-138">This increases the projected inventory level (A: +0 => +4 or B: +2 = +6).</span></span>  

7. <span data-ttu-id="c6176-139">Le système effectue un contrôle final : existe-t-il une relance de sortie ?</span><span class="sxs-lookup"><span data-stu-id="c6176-139">System makes a final check: Is there any decrease reminder?</span></span> <span data-ttu-id="c6176-140">Oui, il y en a un en date du **Da**.</span><span class="sxs-lookup"><span data-stu-id="c6176-140">Yes, there is one on the date of **Da**.</span></span>  
8. <span data-ttu-id="c6176-141">Le système ajoute le rappel de diminution -3 au niveau de stock projeté, soit A : +4 -3 = 1 or B : +6 -3 = +3.</span><span class="sxs-lookup"><span data-stu-id="c6176-141">System adds the decrease reminder of -3 reminder to the projected inventory level, either A: +4 -3 = 1 or B: +6 -3 = +3.</span></span>  
9. <span data-ttu-id="c6176-142">En cas de A, le système crée une commande planifiée en aval qui commence à la date **Da**.</span><span class="sxs-lookup"><span data-stu-id="c6176-142">In case of A, the system creates a forward-scheduled order starting on date **Da**.</span></span>  

     <span data-ttu-id="c6176-143">Dans le cas de B, le point de commande est atteint et aucune commande n'est créée.</span><span class="sxs-lookup"><span data-stu-id="c6176-143">In case of B, the reorder point is reached and a new order is created.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c6176-144">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="c6176-144">See Also</span></span>  
<span data-ttu-id="c6176-145">[Détails de conception : méthodes de réapprovisionnement](design-details-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="c6176-145">[Design Details: Reordering Policies](design-details-reordering-policies.md) </span></span>  
<span data-ttu-id="c6176-146">[Détails de conception : paramètres de planification](design-details-planning-parameters.md) </span><span class="sxs-lookup"><span data-stu-id="c6176-146">[Design Details: Planning Parameters](design-details-planning-parameters.md) </span></span>  
<span data-ttu-id="c6176-147">[Détails de conception : gestion des méthodes de réapprovisionnement](design-details-handling-reordering-policies.md) </span><span class="sxs-lookup"><span data-stu-id="c6176-147">[Design Details: Handling Reordering Policies](design-details-handling-reordering-policies.md) </span></span>  
[<span data-ttu-id="c6176-148">Détails de conception : planification de l'approvisionnement</span><span class="sxs-lookup"><span data-stu-id="c6176-148">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)
