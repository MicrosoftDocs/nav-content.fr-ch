---
title: "Procédure : paramétrer des relances de livraison"
description: "Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], vous pouvez utiliser des relances de livraison achat pour rappeler aux fournisseurs des livraisons en retard. Pour créer des relances de livraison pour les fournisseurs, vous devrez paramétrer des données de base pour la création de relances de livraison ainsi que des souches de numéros pour les relances de livraison dans la fenêtre **Paramètres achats**."
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
ms.openlocfilehash: 6932a2004d4ac713fee87e9d4f5257d66c54db19
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-delivery-reminders"></a><span data-ttu-id="37389-104">Procédure : paramétrer des relances de livraison</span><span class="sxs-lookup"><span data-stu-id="37389-104">How to: Set Up Delivery Reminders</span></span>
<span data-ttu-id="37389-105">Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], vous pouvez utiliser des relances de livraison achat pour rappeler aux fournisseurs des livraisons en retard.</span><span class="sxs-lookup"><span data-stu-id="37389-105">In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can use purchase delivery reminders to remind vendors about overdue deliveries.</span></span> <span data-ttu-id="37389-106">Pour créer des relances de livraison pour les fournisseurs, vous devrez paramétrer des données de base pour la création de relances de livraison ainsi que des souches de numéros pour les relances de livraison dans la fenêtre **Paramètres achats**.</span><span class="sxs-lookup"><span data-stu-id="37389-106">To create delivery reminders for vendors, you must set up base data for delivery reminder creation and number series for the delivery reminders in the **Purchases & Payables Setup** window.</span></span>  
  
### <a name="to-set-up-delivery-reminders"></a><span data-ttu-id="37389-107">Pour paramétrer des relances de livraison</span><span class="sxs-lookup"><span data-stu-id="37389-107">To set up delivery reminders</span></span>  
  
1.  <span data-ttu-id="37389-108">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Paramètres achats**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="37389-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="37389-109">Sous le raccourci **Général**, dans le champ **Champ Date rel. livr. par défaut**, spécifiez l'une des options suivantes comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="37389-109">On the **General** FastTab, in the **Default Del. Rem. Date Field** field, specify one of the following options as described in the following table.</span></span>  
  
    |<span data-ttu-id="37389-110">ADD INCLUDE<!--[!INCLUDE[bp_tableoption](../../includes/bp_tabledescription_md.md)]--></span><span class="sxs-lookup"><span data-stu-id="37389-110">ADD INCLUDE<!--[!INCLUDE[bp_tableoption](../../includes/bp_tabledescription_md.md)]--></span></span>|  
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="37389-111">**Date réception demandée**</span><span class="sxs-lookup"><span data-stu-id="37389-111">**Requested Receipt Date**</span></span>|<span data-ttu-id="37389-112">Pour spécifier que la valeur date dans le champ **Date réception demandée** sur la ligne commande achat sera utilisée comme date par défaut pour créer des relances de livraison.</span><span class="sxs-lookup"><span data-stu-id="37389-112">To specify that the date value in the **Requested Receipt Date** field on the purchase order line will be used as the default date for creating delivery reminders.</span></span>|  
    |<span data-ttu-id="37389-113">**Date réception confirmée**</span><span class="sxs-lookup"><span data-stu-id="37389-113">**Promised Receipt Date**</span></span>|<span data-ttu-id="37389-114">Pour spécifier que la valeur date dans le champ **Date réception confirmée** sur la ligne commande achat sera utilisée comme date par défaut pour créer des relances de livraison.</span><span class="sxs-lookup"><span data-stu-id="37389-114">To specify that the date value in the **Promised Receipt Date** field on the purchase order line will be used as the default date for creating delivery reminders.</span></span>|  
    |<span data-ttu-id="37389-115">**Date réception prévue**</span><span class="sxs-lookup"><span data-stu-id="37389-115">**Expected Receipt Date**</span></span>|<span data-ttu-id="37389-116">Pour spécifier que la valeur date dans le champ **Date réception prévue** sur la ligne commande achat sera utilisée comme date par défaut pour créer des relances de livraison.</span><span class="sxs-lookup"><span data-stu-id="37389-116">To specify that the date value in the **Expected Receipt Date** field on the purchase order line will be used as the default date for creating delivery reminders.</span></span>|  
  
3.  <span data-ttu-id="37389-117">Sous le raccourci **Numérotation**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="37389-117">On the **Numbering** FastTab, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="37389-118">Champ</span><span class="sxs-lookup"><span data-stu-id="37389-118">Field</span></span>|<span data-ttu-id="37389-119">Description</span><span class="sxs-lookup"><span data-stu-id="37389-119">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="37389-120">**N° relance livraison**</span><span class="sxs-lookup"><span data-stu-id="37389-120">**Delivery Reminder Nos.**</span></span>|<span data-ttu-id="37389-121">Le code souche de numéros pour les relances de livraison.</span><span class="sxs-lookup"><span data-stu-id="37389-121">The number series code for delivery reminders.</span></span>|  
    |<span data-ttu-id="37389-122">**N° relance livraison émise**</span><span class="sxs-lookup"><span data-stu-id="37389-122">**Issued Delivery Reminder Nos.**</span></span>|<span data-ttu-id="37389-123">Le code souche de numéros pour les relances de livraison émises.</span><span class="sxs-lookup"><span data-stu-id="37389-123">The number series code for issued delivery reminders.</span></span>|  
  
4.  <span data-ttu-id="37389-124">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="37389-124">Choose the **OK** button.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="37389-125">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="37389-125">See Also</span></span>  
 <span data-ttu-id="37389-126">Paramètres achats</span><span class="sxs-lookup"><span data-stu-id="37389-126">Purchases & Payables Setup</span></span>   
 <span data-ttu-id="37389-127">[Relances de livraison](delivery-reminders.md) </span><span class="sxs-lookup"><span data-stu-id="37389-127">[Delivery Reminders](delivery-reminders.md) </span></span>  
 <span data-ttu-id="37389-128">[Procédure : paramétrer des conditions de relances de livraison, niveaux et texte](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span><span class="sxs-lookup"><span data-stu-id="37389-128">[How to: Set Up Delivery Reminder Terms, Levels, and Text](how-to-set-up-delivery-reminder-terms-levels-and-text.md) </span></span>  
 <span data-ttu-id="37389-129">[Procédure : assigner des codes relance de livraison aux fournisseurs](how-to-assign-delivery-reminder-codes-to-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="37389-129">[How to: Assign Delivery Reminder Codes to Vendors](how-to-assign-delivery-reminder-codes-to-vendors.md) </span></span>  
 [<span data-ttu-id="37389-130">Procédure : créer des relances de livraison manuellement</span><span class="sxs-lookup"><span data-stu-id="37389-130">How to: Create Delivery Reminders Manually</span></span>](how-to-create-delivery-reminders-manually.md)
