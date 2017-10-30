---
title: "Procédure : désactiver la traçabilité coût article"
description: "Lorsque le stock n'est pas suivi pour un article, le coût article ne doit pas nécessairement être suivi et une écriture comptable article ne doit pas nécessairement être créée."
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
ms.openlocfilehash: c2043fe4506ba4baf1b76509f73d2ee99c7dba8c
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-deactivate-item-cost-tracking"></a><span data-ttu-id="27899-103">Procédure : désactiver la traçabilité coût article</span><span class="sxs-lookup"><span data-stu-id="27899-103">How to: Deactivate Item Cost Tracking</span></span>
<span data-ttu-id="27899-104">Lorsque le stock n'est pas suivi pour un article, le coût article ne doit pas nécessairement être suivi et une écriture comptable article ne doit pas nécessairement être créée.</span><span class="sxs-lookup"><span data-stu-id="27899-104">When inventory is not tracked for an item, the item cost does not need to be tracked, and an item ledger entry does not need to be created.</span></span>  
  
 <span data-ttu-id="27899-105">Vous pouvez désactiver la traçabilité coût article pour un article.</span><span class="sxs-lookup"><span data-stu-id="27899-105">You can deactivate item cost tracking for an item.</span></span> <span data-ttu-id="27899-106">Généralement, la traçabilité coût article devrait être désactivée pour les articles consommables, comme les produits en papier usagé et pour les services comptabilisés comme des articles, comme les frais de stationnement forfaitaires.</span><span class="sxs-lookup"><span data-stu-id="27899-106">Generally, item cost tracking should be deactivated for consumable items, such as waste paper products and for services that are counted as items, such as flat rate parking fees.</span></span> <span data-ttu-id="27899-107">La traçabilité coût article devrait être désactivée sur les articles pour lesquels elle pourrait être trompeuse.</span><span class="sxs-lookup"><span data-stu-id="27899-107">Item cost tracking should be deactivated on items for which tracking could be misleading.</span></span> <span data-ttu-id="27899-108">Les articles pour lesquels la traçabilité coût article a été désactivée sont exclus des systèmes de réservation, de contrôle de disponibilité, de traçabilité et de planning de matériel.</span><span class="sxs-lookup"><span data-stu-id="27899-108">Items for which item cost tracking has been deactivated are excluded from reservation, availability check, item tracking, and material planning systems.</span></span>  
  
### <a name="to-deactivate-item-cost-tracking"></a><span data-ttu-id="27899-109">Pour désactiver la traçabilité coût article</span><span class="sxs-lookup"><span data-stu-id="27899-109">To deactivate item cost tracking</span></span>  
  
1.  <span data-ttu-id="27899-110">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Articles**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="27899-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="27899-111">Sélectionnez l'article requis, et sous l'onglet **Accueil**, dans le groupe **Gérer**, choisissez **Modifier**.</span><span class="sxs-lookup"><span data-stu-id="27899-111">Select the required item, and on the **Home** tab, in the **Manage** group, choose **Edit**.</span></span>  
  
3.  <span data-ttu-id="27899-112">Sous l'onglet **Général**, sélectionnez la case à cocher **Pas de gestion stock**.</span><span class="sxs-lookup"><span data-stu-id="27899-112">On the **General** FastTab, select the **No Stockkeeping** check box.</span></span>  
  
     <span data-ttu-id="27899-113">Une écriture comptable article ne sera pas créée lorsque vous validez une transaction pour cet article.</span><span class="sxs-lookup"><span data-stu-id="27899-113">An item ledger entry will not be created when you post a transaction for this item.</span></span> <span data-ttu-id="27899-114">Pour plus d'informations, consultez la table Écriture comptable article.</span><span class="sxs-lookup"><span data-stu-id="27899-114">For more information, see the Item Ledger Entry table.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="27899-115">Vous ne pouvez pas sélectionner la case à cocher **Pas de gestion stock** sur un article pour lequel des écritures comptables article ont déjà été validées.</span><span class="sxs-lookup"><span data-stu-id="27899-115">You cannot select the **No Stockkeeping** check box on an item for which item ledger entries have already been posted.</span></span>  
  
4.  <span data-ttu-id="27899-116">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="27899-116">Choose the **OK** button.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="27899-117">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="27899-117">See Also</span></span>  
 <span data-ttu-id="27899-118">Article</span><span class="sxs-lookup"><span data-stu-id="27899-118">Item</span></span>   
 <span data-ttu-id="27899-119">Écriture comptable article</span><span class="sxs-lookup"><span data-stu-id="27899-119">Item Ledger Entry</span></span>   
 <span data-ttu-id="27899-120">[Gestion des stocks suisse](swiss-inventory-management.md) </span><span class="sxs-lookup"><span data-stu-id="27899-120">[Swiss Inventory Management](swiss-inventory-management.md) </span></span>  
 [<span data-ttu-id="27899-121">Procédure : bloquer des articles en stock pour des ventes ou des achats</span><span class="sxs-lookup"><span data-stu-id="27899-121">How to: Block Inventory Items for Sales or Purchases</span></span>](how-to-block-inventory-items-for-sales-or-purchases.md)