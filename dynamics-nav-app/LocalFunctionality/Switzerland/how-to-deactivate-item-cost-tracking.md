---
title: "Procédure : désactiver la traçabilité coût article"
description: "Lorsque le stock n'est pas suivi pour un article, le coût article ne doit pas nécessairement être suivi et une écriture comptable article ne doit pas nécessairement être créée."
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
ms.openlocfilehash: 862a897adfb7bc5e2e4aaf80e54760a558e87a90
ms.contentlocale: fr-ch
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-deactivate-item-cost-tracking"></a><span data-ttu-id="98a8f-103">Procédure : désactiver la traçabilité coût article</span><span class="sxs-lookup"><span data-stu-id="98a8f-103">How to: Deactivate Item Cost Tracking</span></span>
<span data-ttu-id="98a8f-104">Lorsque le stock n'est pas suivi pour un article, le coût article ne doit pas nécessairement être suivi et une écriture comptable article ne doit pas nécessairement être créée.</span><span class="sxs-lookup"><span data-stu-id="98a8f-104">When inventory is not tracked for an item, the item cost does not need to be tracked, and an item ledger entry does not need to be created.</span></span>  

<span data-ttu-id="98a8f-105">Vous pouvez désactiver la traçabilité coût article pour un article.</span><span class="sxs-lookup"><span data-stu-id="98a8f-105">You can deactivate item cost tracking for an item.</span></span> <span data-ttu-id="98a8f-106">Généralement, la traçabilité coût article devrait être désactivée pour les articles consommables, comme les produits en papier usagé et pour les services comptabilisés comme des articles, comme les frais de stationnement forfaitaires.</span><span class="sxs-lookup"><span data-stu-id="98a8f-106">Generally, item cost tracking should be deactivated for consumable items, such as waste paper products and for services that are counted as items, such as flat rate parking fees.</span></span> <span data-ttu-id="98a8f-107">La traçabilité coût article devrait être désactivée sur les articles pour lesquels elle pourrait être trompeuse.</span><span class="sxs-lookup"><span data-stu-id="98a8f-107">Item cost tracking should be deactivated on items for which tracking could be misleading.</span></span> <span data-ttu-id="98a8f-108">Les articles pour lesquels la traçabilité coût article a été désactivée sont exclus des systèmes de réservation, de contrôle de disponibilité, de traçabilité et de planning de matériel.</span><span class="sxs-lookup"><span data-stu-id="98a8f-108">Items for which item cost tracking has been deactivated are excluded from reservation, availability check, item tracking, and material planning systems.</span></span>  

## <a name="to-deactivate-item-cost-tracking"></a><span data-ttu-id="98a8f-109">Pour désactiver la traçabilité coût article</span><span class="sxs-lookup"><span data-stu-id="98a8f-109">To deactivate item cost tracking</span></span>  

1.  <span data-ttu-id="98a8f-110">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Articles**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="98a8f-110">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="98a8f-111">Sélectionnez l'article requis, puis choisissez l'action **Modifier**.</span><span class="sxs-lookup"><span data-stu-id="98a8f-111">Select the required item, and then choose the **Edit** action.</span></span>  
3.  <span data-ttu-id="98a8f-112">Sous l'onglet **Général**, sélectionnez la case à cocher **Pas de gestion stock**.</span><span class="sxs-lookup"><span data-stu-id="98a8f-112">On the **General** FastTab, select the **No Stockkeeping** check box.</span></span>  

    <span data-ttu-id="98a8f-113">Une écriture comptable article ne sera pas créée lorsque vous validez une transaction pour cet article.</span><span class="sxs-lookup"><span data-stu-id="98a8f-113">An item ledger entry will not be created when you post a transaction for this item.</span></span> <span data-ttu-id="98a8f-114">Pour plus d'informations, consultez la table Écriture comptable article.</span><span class="sxs-lookup"><span data-stu-id="98a8f-114">For more information, see the Item Ledger Entry table.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="98a8f-115">Vous ne pouvez pas sélectionner la case à cocher **Pas de gestion stock** sur un article pour lequel des écritures comptables article ont déjà été validées.</span><span class="sxs-lookup"><span data-stu-id="98a8f-115">You cannot select the **No Stockkeeping** check box on an item for which item ledger entries have already been posted.</span></span>  

4.  <span data-ttu-id="98a8f-116">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="98a8f-116">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="98a8f-117">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="98a8f-117">See Also</span></span>  
 <span data-ttu-id="98a8f-118">[Gestion des stocks suisse](swiss-inventory-management.md) </span><span class="sxs-lookup"><span data-stu-id="98a8f-118">[Swiss Inventory Management](swiss-inventory-management.md) </span></span>  
 [<span data-ttu-id="98a8f-119">Procédure : bloquer des articles en stock pour des ventes ou des achats</span><span class="sxs-lookup"><span data-stu-id="98a8f-119">How to: Block Inventory Items for Sales or Purchases</span></span>](how-to-block-inventory-items-for-sales-or-purchases.md)

