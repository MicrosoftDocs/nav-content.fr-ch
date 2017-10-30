---
title: "Procédure : clôturer les écritures comptables article ouvertes qui résultent d'un lettrage fixe dans la feuille article"
description: "Vous pouvez utiliser le champ **Lettrage à partir écriture** de la fenêtre **Feuille article** pour créer manuellement un lettrage fixe entre une transaction entrante et la transaction sortante initiale. Par exemple, pour corriger la transaction sortante ou pour traiter un retour."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/09/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b0b0daad01f8108d035739e387b38af4f0311ff9
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-close-open-item-ledger-entries-resulting-from-fixed-application-in-the-item-journal"></a><span data-ttu-id="c2cb0-104">Procédure : clôturer les écritures comptables article ouvertes qui résultent d'un lettrage fixe dans la feuille article</span><span class="sxs-lookup"><span data-stu-id="c2cb0-104">How to: Close Open Item Ledger Entries Resulting from Fixed Application in the Item Journal</span></span>
<span data-ttu-id="c2cb0-105">Vous pouvez utiliser le champ **Lettrage à partir écriture** de la fenêtre **Feuille article** pour créer manuellement un lettrage fixe entre une transaction entrante et la transaction sortante initiale.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-105">You can use the **Applies-from Entry** field in the **Item Journal** window to create a fixed application between an inbound transaction and the original outbound transaction.</span></span> <span data-ttu-id="c2cb0-106">Par exemple, pour corriger la transaction sortante ou pour traiter un retour.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-106">For example, to correct the outbound transaction or to process its return.</span></span> <span data-ttu-id="c2cb0-107">Pour plus d'informations, voir Lettrage à partir écriture.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-107">For more information, see Applies-from Entry.</span></span>  

> [!IMPORTANT]  
>  <span data-ttu-id="c2cb0-108">Les lettrages fixes exécutés de cette manière s'appliquent uniquement au coût, non à la quantité.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-108">Fixed applications made in this manner only apply the cost, not the quantity.</span></span> <span data-ttu-id="c2cb0-109">Par conséquent, l'écriture comptable article positive enregistrée ne ferme pas l'écriture sortante rapprochée et demeure ouverte elle-même.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-109">Accordingly, the posted positive item ledger entry will not close the applied outbound entry and will itself remain open.</span></span> <span data-ttu-id="c2cb0-110">Cela s'applique également lorsque vous validez un lettrage fixe pour une écriture positive vers une écriture négative qui n'a pas été clôturée par une écriture positive ordinaire ; les écritures négatives et positives restent ouvertes.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-110">This also applies when you post a fixed application for a positive entry to a negative entry that has not been closed by a regular positive entry, then both the negative and the positive entries will remain open.</span></span>  
>   
>  <span data-ttu-id="c2cb0-111">Cela signifie également que vous ne pouvez pas clôturer une période inventaire si une telle écriture existe.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-111">This also means that you cannot close an inventory period if such an entry exists.</span></span>  

<span data-ttu-id="c2cb0-112">La procédure suivante explique comment clôturer des écritures de ce genre au cours de deux validations de correction dans la feuille article.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-112">The following procedure shows how to close such entries by performing two corrective postings in the item journal.</span></span>  

## <a name="to-close-open-item-ledger-entries-that-result-from-a-fixed-application-in-the-item-journal"></a><span data-ttu-id="c2cb0-113">Pour clôturer les écritures comptables article ouvertes qui résultent d'un lettrage fixe dans la feuille article</span><span class="sxs-lookup"><span data-stu-id="c2cb0-113">To close open item ledger entries that result from a fixed application in the item journal</span></span>  

1.  <span data-ttu-id="c2cb0-114">Utilisez le champ **Lettrage à partir écriture** pour valider un ajustement positif avec la quantité correspondante.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-114">Use the **Applies-from Entry** field to post a positive adjustment with the corresponding quantity.</span></span> <span data-ttu-id="c2cb0-115">Cela permet de clôturer l'écriture négative initiale avec un lettrage fixe.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-115">This closes the original negative entry with a fixed application.</span></span>  
2.  <span data-ttu-id="c2cb0-116">Utilisez le champ **Lettrage à partir écriture** pour valider un ajustement négatif.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-116">Use the **Applies-to Entry** field to post a negative adjustment.</span></span> <span data-ttu-id="c2cb0-117">Cela permet de clôturer l'écriture positive de correction initiale avec un lettrage fixe.</span><span class="sxs-lookup"><span data-stu-id="c2cb0-117">This closes the original corrective positive entry with a fixed application.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c2cb0-118">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="c2cb0-118">See Also</span></span>  
[<span data-ttu-id="c2cb0-119"> Procédure : supprimer et relettrer des écritures comptables article</span><span class="sxs-lookup"><span data-stu-id="c2cb0-119"> How to: Remove and Reapply Item Ledger Entries</span></span>](finance-how-to-remove-and-reapply-item-entries.md)  
 <span data-ttu-id="c2cb0-120">[Procédure : traiter les retours et annulations de ventes](sales-how-process-sales-returns-cancellations.md) </span><span class="sxs-lookup"><span data-stu-id="c2cb0-120">[How to: Process Sales Returns and Cancellations](sales-how-process-sales-returns-cancellations.md) </span></span>  
 <span data-ttu-id="c2cb0-121">[Configuration de l'évaluation du stock](finance-set-up-inventory-valuation-and-costing.md) </span><span class="sxs-lookup"><span data-stu-id="c2cb0-121">[Setting Up Inventory Valuation and Costing](finance-set-up-inventory-valuation-and-costing.md) </span></span>  
 <span data-ttu-id="c2cb0-122">[Gestion des coûts ajustés](finance-manage-inventory-costs.md) </span><span class="sxs-lookup"><span data-stu-id="c2cb0-122">[Managing Inventory Costs](finance-manage-inventory-costs.md) </span></span>  
 [<span data-ttu-id="c2cb0-123">Détails de conception : modes évaluation stock</span><span class="sxs-lookup"><span data-stu-id="c2cb0-123">Design Details: Costing Methods</span></span>](design-details-costing-methods.md)
