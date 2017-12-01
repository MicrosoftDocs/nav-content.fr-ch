---
title: "Procédure : paramétrer des relances de livraison"
description: Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], vous pouvez utiliser des relances de livraison achat pour rappeler aux fournisseurs des livraisons en retard.
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
ms.openlocfilehash: 8895148c8e969f1d4cf95c21924940668fdd6bf3
ms.contentlocale: fr-ch
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-delivery-reminders"></a><span data-ttu-id="64b3f-103">Procédure : paramétrer des relances de livraison</span><span class="sxs-lookup"><span data-stu-id="64b3f-103">How to: Set Up Delivery Reminders</span></span>
<span data-ttu-id="64b3f-104">Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], vous pouvez utiliser des relances de livraison achat pour rappeler aux fournisseurs des livraisons en retard.</span><span class="sxs-lookup"><span data-stu-id="64b3f-104">In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can use purchase delivery reminders to remind vendors about overdue deliveries.</span></span> <span data-ttu-id="64b3f-105">Pour créer des relances de livraison pour les fournisseurs, vous devrez paramétrer des données de base pour la création de relances de livraison ainsi que des souches de numéros pour les relances de livraison dans la fenêtre **Paramètres achats**.</span><span class="sxs-lookup"><span data-stu-id="64b3f-105">To create delivery reminders for vendors, you must set up base data for delivery reminder creation and number series for the delivery reminders in the **Purchases & Payables Setup** window.</span></span>  

## <a name="to-set-up-delivery-reminders"></a><span data-ttu-id="64b3f-106">Pour paramétrer des relances de livraison</span><span class="sxs-lookup"><span data-stu-id="64b3f-106">To set up delivery reminders</span></span>  

1.  <span data-ttu-id="64b3f-107">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Paramètres achats**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="64b3f-107">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="64b3f-108">Sous le raccourci **Général**, dans le champ **Champ Date rel. livr. par défaut**, spécifiez l'une des options suivantes comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="64b3f-108">On the **General** FastTab, in the **Default Del. Rem. Date Field** field, specify one of the following options as described in the following table.</span></span>  

    |<span data-ttu-id="64b3f-109">Option</span><span class="sxs-lookup"><span data-stu-id="64b3f-109">Option</span></span>|<span data-ttu-id="64b3f-110">Description</span><span class="sxs-lookup"><span data-stu-id="64b3f-110">Description</span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="64b3f-111">**Date réception demandée**</span><span class="sxs-lookup"><span data-stu-id="64b3f-111">**Requested Receipt Date**</span></span>|<span data-ttu-id="64b3f-112">Pour spécifier que la valeur date dans le champ **Date réception demandée** sur la ligne commande achat sera utilisée comme date par défaut pour créer des relances de livraison.</span><span class="sxs-lookup"><span data-stu-id="64b3f-112">To specify that the date value in the **Requested Receipt Date** field on the purchase order line will be used as the default date for creating delivery reminders.</span></span>|  
    |<span data-ttu-id="64b3f-113">**Date réception confirmée**</span><span class="sxs-lookup"><span data-stu-id="64b3f-113">**Promised Receipt Date**</span></span>|<span data-ttu-id="64b3f-114">Pour spécifier que la valeur date dans le champ **Date réception confirmée** sur la ligne commande achat sera utilisée comme date par défaut pour créer des relances de livraison.</span><span class="sxs-lookup"><span data-stu-id="64b3f-114">To specify that the date value in the **Promised Receipt Date** field on the purchase order line will be used as the default date for creating delivery reminders.</span></span>|  
    |<span data-ttu-id="64b3f-115">**Date réception prévue**</span><span class="sxs-lookup"><span data-stu-id="64b3f-115">**Expected Receipt Date**</span></span>|<span data-ttu-id="64b3f-116">Pour spécifier que la valeur date dans le champ **Date réception prévue** sur la ligne commande achat sera utilisée comme date par défaut pour créer des relances de livraison.</span><span class="sxs-lookup"><span data-stu-id="64b3f-116">To specify that the date value in the **Expected Receipt Date** field on the purchase order line will be used as the default date for creating delivery reminders.</span></span>|  

3.  <span data-ttu-id="64b3f-117">Sous le raccourci **Numérotation**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="64b3f-117">On the **Numbering** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="64b3f-118">Champ</span><span class="sxs-lookup"><span data-stu-id="64b3f-118">Field</span></span>|<span data-ttu-id="64b3f-119">Description</span><span class="sxs-lookup"><span data-stu-id="64b3f-119">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="64b3f-120">**N° relance livraison**</span><span class="sxs-lookup"><span data-stu-id="64b3f-120">**Delivery Reminder Nos.**</span></span>|<span data-ttu-id="64b3f-121">Le code souche de numéros pour les relances de livraison.</span><span class="sxs-lookup"><span data-stu-id="64b3f-121">The number series code for delivery reminders.</span></span>|  
    |<span data-ttu-id="64b3f-122">**N° relance livraison émise**</span><span class="sxs-lookup"><span data-stu-id="64b3f-122">**Issued Delivery Reminder Nos.**</span></span>|<span data-ttu-id="64b3f-123">Le code souche de numéros pour les relances de livraison émises.</span><span class="sxs-lookup"><span data-stu-id="64b3f-123">The number series code for issued delivery reminders.</span></span>|  

4.  <span data-ttu-id="64b3f-124">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="64b3f-124">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="64b3f-125">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="64b3f-125">See Also</span></span>  
 <span data-ttu-id="64b3f-126">[Relances de livraison](delivery-reminders.md) </span><span class="sxs-lookup"><span data-stu-id="64b3f-126">[Delivery Reminders](delivery-reminders.md) </span></span>  
 <span data-ttu-id="64b3f-127">[Procédure : paramétrer des conditions, des niveaux et du texte pour les relances de livraison](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span><span class="sxs-lookup"><span data-stu-id="64b3f-127">[How to: Set Up Delivery Reminder Terms, Levels, and Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span></span>  
 <span data-ttu-id="64b3f-128">[Procédure : assigner des codes relance de livraison aux fournisseurs](how-to-assign-delivery-reminder-codes-to-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="64b3f-128">[How to: Assign Delivery Reminder Codes to Vendors](how-to-assign-delivery-reminder-codes-to-vendors.md) </span></span>  
 [<span data-ttu-id="64b3f-129">Procédure : créer des relances de livraison manuellement</span><span class="sxs-lookup"><span data-stu-id="64b3f-129">How to: Create Delivery Reminders Manually</span></span>](how-to-create-delivery-reminders-manually.md)

