---
title: "Procédure : paramétrer l'archivage automatique de documents en Suisse"
description: "Vous pouvez paramétrer l'archivage automatique de documents vente et de documents achat (devis, commandes ouvertes et commandes) avant de supprimer ces documents."
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
ms.openlocfilehash: 74ea022df7ed88e06aa2eb793a0ca342a711e903
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-automatic-archiving-of-documents-in-switzerland"></a><span data-ttu-id="e5de9-103">Procédure : paramétrer l'archivage automatique de documents en Suisse</span><span class="sxs-lookup"><span data-stu-id="e5de9-103">How to: Set Up Automatic Archiving of Documents in Switzerland</span></span>
<span data-ttu-id="e5de9-104">Vous pouvez paramétrer l'archivage automatique de documents vente et de documents achat (devis, commandes ouvertes et commandes) avant de supprimer ces documents.</span><span class="sxs-lookup"><span data-stu-id="e5de9-104">You can set up automatic archiving of sales documents and purchase documents—such as quotes, blanket orders, and orders—before you delete documents.</span></span>  
  
 <span data-ttu-id="e5de9-105">La procédure suivante décrit comment paramétrer l'archivage automatique de documents vente, mais vous pouvez également la suivre pour paramétrer l'archivage automatique de documents achat.</span><span class="sxs-lookup"><span data-stu-id="e5de9-105">The following procedure describes how to set up automatic archiving of sales documents, but the same steps apply to purchase documents.</span></span>  
  
### <a name="to-set-up-automatic-archiving-of-documents"></a><span data-ttu-id="e5de9-106">Pour paramétrer l'archivage automatique de documents</span><span class="sxs-lookup"><span data-stu-id="e5de9-106">To set up automatic archiving of documents</span></span>  
  
1.  <span data-ttu-id="e5de9-107">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Paramètres ventes**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="e5de9-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales & Receivables Setup**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="e5de9-108">Dans la fenêtre **Paramètres ventes**, sur le raccourci **Archivage**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="e5de9-108">On the **Sales & Receivables Setup** window, on the **Archiving** FastTab, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="e5de9-109">Champ</span><span class="sxs-lookup"><span data-stu-id="e5de9-109">Field</span></span>|<span data-ttu-id="e5de9-110">Description</span><span class="sxs-lookup"><span data-stu-id="e5de9-110">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="e5de9-111">**Archivage devis**</span><span class="sxs-lookup"><span data-stu-id="e5de9-111">**Archiving Sales Quote**</span></span>|<span data-ttu-id="e5de9-112">**Jamais** pour ne jamais archiver les devis lors de leur suppression.</span><span class="sxs-lookup"><span data-stu-id="e5de9-112">**Never** to never archive sales quotes when they are deleted.</span></span><br /><br /> <span data-ttu-id="e5de9-113">–ou–</span><span class="sxs-lookup"><span data-stu-id="e5de9-113">–or–</span></span><br /><br /> <span data-ttu-id="e5de9-114">**Question** pour inviter l'utilisateur à choisir s'il souhaite archiver les devis lors de leur suppression.</span><span class="sxs-lookup"><span data-stu-id="e5de9-114">**Question** to prompt the user to choose whether to archive sales quotes when they are deleted.</span></span><br /><br /> <span data-ttu-id="e5de9-115">–ou–</span><span class="sxs-lookup"><span data-stu-id="e5de9-115">–or–</span></span><br /><br /> <span data-ttu-id="e5de9-116">**Toujours** pour archiver automatiquement les devis lors de leur suppression.</span><span class="sxs-lookup"><span data-stu-id="e5de9-116">**Always** to archive sales quotes automatically when they are deleted.</span></span>|  
    |<span data-ttu-id="e5de9-117">**Archivage commandes ouvertes vente**</span><span class="sxs-lookup"><span data-stu-id="e5de9-117">**Archiving Blanket Sales Orders**</span></span>|<span data-ttu-id="e5de9-118">Sélectionnez cette option pour archiver automatiquement les commandes vente ouvertes à chaque suppression.</span><span class="sxs-lookup"><span data-stu-id="e5de9-118">Select to archive blanket sales orders automatically each time they are deleted.</span></span>|  
    |<span data-ttu-id="e5de9-119">**Archivage commandes et retours**</span><span class="sxs-lookup"><span data-stu-id="e5de9-119">**Arch. Orders and Ret. Orders**</span></span>|<span data-ttu-id="e5de9-120">Sélectionnez cette option pour archiver automatiquement les commandes vente à chaque suppression.</span><span class="sxs-lookup"><span data-stu-id="e5de9-120">Select to automatically archive sales orders each time they are deleted.</span></span>|  
    |<span data-ttu-id="e5de9-121">**Journal interaction automatique**</span><span class="sxs-lookup"><span data-stu-id="e5de9-121">**Automatic Interaction Log**</span></span>|<span data-ttu-id="e5de9-122">Sélectionnez cette option pour créer automatiquement une écriture pour le contact dans le journal interaction lorsqu'une commande vente ou une expédition partielle est validée ou lorsqu'un devis est converti en commande vente.</span><span class="sxs-lookup"><span data-stu-id="e5de9-122">Select to automatically create an entry for the contact in the interaction log when a sales order or partial shipment is posted, or when a sales quote is converted into a sales order.</span></span> <span data-ttu-id="e5de9-123">**Remarque :**  ce champ n'est pas disponible sur la page **Paramètres achats**.</span><span class="sxs-lookup"><span data-stu-id="e5de9-123">**Note:**  This field is not available on the **Purchases & Payables Setup** page.</span></span>|  
  
3.  <span data-ttu-id="e5de9-124">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="e5de9-124">Choose the **OK** button.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="e5de9-125">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="e5de9-125">See Also</span></span>  
 <span data-ttu-id="e5de9-126">[Documents vente et documents achat suisses](swiss-purchase-documents-and-sales-documents.md) </span><span class="sxs-lookup"><span data-stu-id="e5de9-126">[Swiss Purchase Documents and Sales Documents](swiss-purchase-documents-and-sales-documents.md) </span></span>  
 <span data-ttu-id="e5de9-127">Paramètres ventes</span><span class="sxs-lookup"><span data-stu-id="e5de9-127">Sales & Receivables Setup</span></span>   
 <span data-ttu-id="e5de9-128">[Procédure : importer des codes postaux suisses](how-to-import-swiss-post-codes.md) </span><span class="sxs-lookup"><span data-stu-id="e5de9-128">[How to: Import Swiss Post Codes](how-to-import-swiss-post-codes.md) </span></span>  
 <span data-ttu-id="e5de9-129">[Procédure : imprimer une liste des prélèvements stock à partir d'une commande vente](how-to-print-an-inventory-picking-list-from-a-sales-order.md) </span><span class="sxs-lookup"><span data-stu-id="e5de9-129">[How to: Print an Inventory Picking List from a Sales Order](how-to-print-an-inventory-picking-list-from-a-sales-order.md) </span></span>  
 [<span data-ttu-id="e5de9-130">Procédure : imprimer des commandes achat et vente pendant le traitement par lots validation</span><span class="sxs-lookup"><span data-stu-id="e5de9-130">How to: Print Sales and Purchase Orders During Batch Posting</span></span>](how-to-print-sales-and-purchase-orders-during-batch-posting.md)