---
title: Relances de livraison
description: "Les relances de livraison sont utilisées pour suivre les expéditions fournisseur en retard et pour rappeler aux fournisseurs des livraisons en retard."
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
ms.openlocfilehash: da33a4b683d04669dd33e3ed715de0e91b861f23
ms.contentlocale: fr-ch
ms.lasthandoff: 12/01/2017

---
# <a name="delivery-reminders"></a><span data-ttu-id="5e0b9-103">Relances de livraison</span><span class="sxs-lookup"><span data-stu-id="5e0b9-103">Delivery Reminders</span></span>
<span data-ttu-id="5e0b9-104">Les relances de livraison sont utilisées pour suivre les expéditions fournisseur en retard et pour rappeler aux fournisseurs des livraisons en retard.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-104">Delivery reminders are used to track overdue vendor shipments, and to remind vendors about overdue deliveries.</span></span> <span data-ttu-id="5e0b9-105">Pour créer des relances de livraison, vous devez paramétrer les éléments suivants :</span><span class="sxs-lookup"><span data-stu-id="5e0b9-105">To create delivery reminders, you must set up the following:</span></span>  

- <span data-ttu-id="5e0b9-106">Conditions de relance de livraison</span><span class="sxs-lookup"><span data-stu-id="5e0b9-106">Delivery reminder terms</span></span>  

    <span data-ttu-id="5e0b9-107">Les conditions de relance de livraison sont identifiées par un code qui doit être assigné aux fournisseurs.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-107">Delivery reminder terms are identified by a code that must be assigned to vendors.</span></span> <span data-ttu-id="5e0b9-108">Pour utiliser plusieurs combinaisons de paramètres, vous devez paramétrer un code pour chaque paramètre séparément.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-108">To use more than one combination of settings, you must set up a code for each setting separately.</span></span> <span data-ttu-id="5e0b9-109">Vous pouvez paramétrer n'importe quel nombre de conditions de relances de livraison</span><span class="sxs-lookup"><span data-stu-id="5e0b9-109">You can set up any number of delivery reminder terms.</span></span>  

- <span data-ttu-id="5e0b9-110">Niveaux de relance de livraison</span><span class="sxs-lookup"><span data-stu-id="5e0b9-110">Delivery reminder levels</span></span>  

    <span data-ttu-id="5e0b9-111">Pour chaque condition de relance de livraison, vous devez paramétrer des niveaux de relance de livraison.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-111">For every delivery reminder term, you must set up delivery reminder levels.</span></span> <span data-ttu-id="5e0b9-112">Ces niveaux déterminent à quelle fréquence il est possible de créer des relances de livraison pour une condition spécifique.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-112">These levels determine how often delivery reminders can be created for a specific term.</span></span> <span data-ttu-id="5e0b9-113">Le niveau 1 est la première relance de livraison que vous créez pour une livraison en retard.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-113">Level 1 is the first delivery reminder that you create for an overdue delivery.</span></span> <span data-ttu-id="5e0b9-114">Le niveau 2 est la deuxième relance de livraison, etc.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-114">Level 2 is the second delivery reminder, and so on.</span></span> <span data-ttu-id="5e0b9-115">Lors de la création de relances de livraison, le nombre de relances créées précédemment est pris en compte, et le numéro actuel est utilisé pour appliquer des conditions.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-115">When delivery reminders are created, the number of reminders that were created previously is considered, and the current number is used to apply terms.</span></span>  

- <span data-ttu-id="5e0b9-116">Messages texte pour les relances de livraison</span><span class="sxs-lookup"><span data-stu-id="5e0b9-116">Delivery reminder texts messages</span></span>  

    <span data-ttu-id="5e0b9-117">Vous devez paramétrer des messages texte pour chaque niveau de relance de livraison.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-117">You must set up delivery reminder text messages for every delivery reminder level.</span></span> <span data-ttu-id="5e0b9-118">Il existe deux types de messages texte pour les relances de livraison : début et fin.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-118">There are two types of delivery reminder text messages: beginning and ending.</span></span> <span data-ttu-id="5e0b9-119">Le message texte de début est imprimé sous la section en-tête, avant la liste des écritures marquées pour relance.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-119">The beginning text message is printed under the header section, before the list of entries that are marked for reminder.</span></span> <span data-ttu-id="5e0b9-120">Le message texte de fin est imprimé après cette liste.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-120">The ending text message is printed after this list.</span></span>  

<span data-ttu-id="5e0b9-121">Pour plus d'informations, voir [Procédure : paramétrer des conditions de relances de livraison, niveaux et texte](how-to-set-up-delivery-reminder-terms-levels-and-text.md).</span><span class="sxs-lookup"><span data-stu-id="5e0b9-121">For more information, see [How to: Set Up Delivery Reminder Terms, Levels, and Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md).</span></span>  

<span data-ttu-id="5e0b9-122">Après avoir configuré les conditions de relance, vous devez assigner les codes condition de relance de livraison aux fournisseurs.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-122">After you have set up the delivery terms, you must assign the delivery reminder term codes to vendors.</span></span> <span data-ttu-id="5e0b9-123">Pour plus d'informations, voir [Procédure : assigner des codes de relance de livraison aux fournisseurs](how-to-assign-delivery-reminder-codes-to-vendors.md).</span><span class="sxs-lookup"><span data-stu-id="5e0b9-123">For more information, see [How to: Assign Delivery Reminder Codes to Vendors](how-to-assign-delivery-reminder-codes-to-vendors.md).</span></span>  

<span data-ttu-id="5e0b9-124">Vous pouvez créer des relances de livraison manuellement ou automatiquement.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-124">You can create delivery reminders manually or automatically.</span></span> <span data-ttu-id="5e0b9-125">Vous pouvez utiliser le traitement par lots **Créer une relance de livraison** pour créer des relances de livraison automatiquement.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-125">You can use the **Create Delivery Reminder** batch job to create delivery reminders automatically.</span></span> <span data-ttu-id="5e0b9-126">Ce traitement par lots vous permet de sélectionner les commandes achat pour lesquelles vous devez créer des relances de livraison.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-126">This batch job allows you to select the purchase orders for which delivery reminders must be created.</span></span> <span data-ttu-id="5e0b9-127">Pour plus d'informations, voir [Procédure : générer des relances de livraison](how-to-issue-delivery-reminders.md).</span><span class="sxs-lookup"><span data-stu-id="5e0b9-127">For more information, see [How to: Generate Delivery Reminders](how-to-issue-delivery-reminders.md).</span></span>  

<span data-ttu-id="5e0b9-128">Vous pouvez également suivre des documents en fonction de lignes commande achat et de lignes commande vente.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-128">You can also track documents in relation to purchase order lines and sales order lines.</span></span>  

[!INCLUDE[navnow](../../includes/navnow_md.md)]<span data-ttu-id="5e0b9-129"> propose les états suivants :</span><span class="sxs-lookup"><span data-stu-id="5e0b9-129"> provides the following reports:</span></span>  

- <span data-ttu-id="5e0b9-130">**Relance de livraison émise** - Pour afficher les relances de livraison pour les fournisseurs.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-130">**Issued Delivery Reminder** - To view the delivery reminders for vendors.</span></span>  
- <span data-ttu-id="5e0b9-131">**Relance de livraison - Test** - Pour vérifier les relances de livraison avant de les émettre.</span><span class="sxs-lookup"><span data-stu-id="5e0b9-131">**Delivery Reminder - Test** - To verify the delivery reminders before you issue them.</span></span>  

<span data-ttu-id="5e0b9-132">Pour plus d'informations, voir [Procédure : imprimer des impressions test pour des relances de livraison](how-to-print-test-reports-for-delivery-reminders.md).</span><span class="sxs-lookup"><span data-stu-id="5e0b9-132">For more information, see [How to: Print Test Reports for Delivery Reminders](how-to-print-test-reports-for-delivery-reminders.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="5e0b9-133">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="5e0b9-133">See Also</span></span>  
 <span data-ttu-id="5e0b9-134">[Procédure : paramétrer des relances de livraison](how-to-set-up-delivery-reminders.md) </span><span class="sxs-lookup"><span data-stu-id="5e0b9-134">[How to: Set Up Delivery Reminders](how-to-set-up-delivery-reminders.md) </span></span>  
 <span data-ttu-id="5e0b9-135">[Procédure : paramétrer des conditions de relances de livraison, niveaux et texte](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span><span class="sxs-lookup"><span data-stu-id="5e0b9-135">[How to: Set Up Delivery Reminder Terms, Levels, and Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span></span>  
 <span data-ttu-id="5e0b9-136">[Procédure : assigner des codes relance de livraison aux fournisseurs](how-to-assign-delivery-reminder-codes-to-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="5e0b9-136">[How to: Assign Delivery Reminder Codes to Vendors](how-to-assign-delivery-reminder-codes-to-vendors.md) </span></span>  
 <span data-ttu-id="5e0b9-137">[Procédure : générer des relances de livraison](how-to-generate-delivery-reminders.md) </span><span class="sxs-lookup"><span data-stu-id="5e0b9-137">[How to: Generate Delivery Reminders](how-to-generate-delivery-reminders.md) </span></span>  
 <span data-ttu-id="5e0b9-138">[Procédure : créer des relances de livraison manuellement](how-to-create-delivery-reminders-manually.md) </span><span class="sxs-lookup"><span data-stu-id="5e0b9-138">[How to: Create Delivery Reminders Manually](how-to-create-delivery-reminders-manually.md) </span></span>  
 <span data-ttu-id="5e0b9-139">[Procédure : émettre des relances de livraison](how-to-issue-delivery-reminders.md) </span><span class="sxs-lookup"><span data-stu-id="5e0b9-139">[How to: Issue Delivery Reminders](how-to-issue-delivery-reminders.md) </span></span>  
 [<span data-ttu-id="5e0b9-140">Procédure : imprimer des impressions test pour des relances de livraison</span><span class="sxs-lookup"><span data-stu-id="5e0b9-140">How to: Print Test Reports for Delivery Reminders</span></span>](how-to-print-test-reports-for-delivery-reminders.md)

