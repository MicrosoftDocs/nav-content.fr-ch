---
title: "Procédure : imprimer des factures BVR"
description: "Vous pouvez imprimer un bordereau de paiement BVR (bulletin de versement avec numéro de référence) de plusieurs manières."
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
ms.openlocfilehash: bdf9dcc16f1e5cd510b07a90fffeccfb36e67955
ms.contentlocale: fr-ch
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-print-esr-invoices"></a><span data-ttu-id="e442b-103">Procédure : imprimer des factures BVR</span><span class="sxs-lookup"><span data-stu-id="e442b-103">How to: Print ESR Invoices</span></span>
<span data-ttu-id="e442b-104">Vous pouvez imprimer un bordereau de paiement BVR (bulletin de versement avec numéro de référence) de plusieurs manières.</span><span class="sxs-lookup"><span data-stu-id="e442b-104">You can print an Einzahlungsschein mit Referenznummer (ESR) payment slip in the following ways:</span></span>  

- <span data-ttu-id="e442b-105">En tant que partie du BVR facture vente.</span><span class="sxs-lookup"><span data-stu-id="e442b-105">As part of the sales invoice ESR.</span></span>  
- <span data-ttu-id="e442b-106">En tant que document séparé appelé coupon BVR.</span><span class="sxs-lookup"><span data-stu-id="e442b-106">As a separate document called an ESR coupon.</span></span>  

<span data-ttu-id="e442b-107">L'état BVR facture vente correspond à la facture vente accompagnée d'un coupon BVR supplémentaire.</span><span class="sxs-lookup"><span data-stu-id="e442b-107">The sales invoice ESR report corresponds with the sales invoice that is accompanied by an additional ESR coupon.</span></span> <span data-ttu-id="e442b-108">En utilisant l'état coupon BVR vente, vous pouvez imprimer le bordereau de dépôt bleu.</span><span class="sxs-lookup"><span data-stu-id="e442b-108">By using the sales ESR coupon report, you can print the blue deposit slip.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="e442b-109">Vous devez sélectionner une imprimante et sélectionner les paramètres pendant l'installation du module de paiement BVR pour imprimer le bordereau de dépôt correctement.</span><span class="sxs-lookup"><span data-stu-id="e442b-109">You must select a printer and select settings during the ESR payment module installation to print the deposit slip correctly.</span></span> <span data-ttu-id="e442b-110">Pour plus d'informations, consultez la table Sélection de l'imprimante.</span><span class="sxs-lookup"><span data-stu-id="e442b-110">For more information, see the Printer Selection table.</span></span>  

<span data-ttu-id="e442b-111">La procédure suivante décrit comment imprimer des factures vente BVR, mais vous pouvez également la suivre pour imprimer des coupons BVR.</span><span class="sxs-lookup"><span data-stu-id="e442b-111">The following procedure describes how to print ESR sales invoices, but the same steps also apply for printing ESR coupons.</span></span>  

## <a name="to-print-esr-invoices"></a><span data-ttu-id="e442b-112">Pour imprimer des factures BVR</span><span class="sxs-lookup"><span data-stu-id="e442b-112">To print ESR invoices</span></span>  

1.  <span data-ttu-id="e442b-113">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **BVR facture**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="e442b-113">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Invoice ESR**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="e442b-114">Dans le traitement par lots **BVR facture vente**, sur le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="e442b-114">In the **Sales Invoice ESR** batch job, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="e442b-115">Champ</span><span class="sxs-lookup"><span data-stu-id="e442b-115">Field</span></span>|<span data-ttu-id="e442b-116">Description</span><span class="sxs-lookup"><span data-stu-id="e442b-116">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="e442b-117">**Nombre de copies**</span><span class="sxs-lookup"><span data-stu-id="e442b-117">**No. of copies**</span></span>|<span data-ttu-id="e442b-118">Entrez le nombre requis d'exemplaires du rapport.</span><span class="sxs-lookup"><span data-stu-id="e442b-118">Enter the required number of report copies.</span></span>|  
    |<span data-ttu-id="e442b-119">**Banque BVR**</span><span class="sxs-lookup"><span data-stu-id="e442b-119">**ESR Bank**</span></span>|<span data-ttu-id="e442b-120">Sélectionnez le code banque BVR à imprimer dans l'état.</span><span class="sxs-lookup"><span data-stu-id="e442b-120">Select the ESR bank code that is to be printed in the report.</span></span><br /><br /> <span data-ttu-id="e442b-121">Si la valeur dans ce champ est <Blank> et si le code du mode de règlement BVR n'est pas défini dans la fenêtre **Paramètres BVR**, la banque principale BVR sélectionnée dans la fenêtre **Paramètres BVR** sera imprimée.</span><span class="sxs-lookup"><span data-stu-id="e442b-121">If the value in this field is <Blank> and the ESR payment method code is not defined in the **ESR Setup** window, then the ESR main bank selected in the **ESR Setup** window will be printed.</span></span>|  
    |<span data-ttu-id="e442b-122">**Journal interaction**</span><span class="sxs-lookup"><span data-stu-id="e442b-122">**LogInteraction**</span></span>|<span data-ttu-id="e442b-123">Spécifiez si les interactions que vous avez avec vos contacts seront consignées.</span><span class="sxs-lookup"><span data-stu-id="e442b-123">Specify if the interactions that you have with your contacts will be logged.</span></span>|  
    |<span data-ttu-id="e442b-124">**Système BVR**</span><span class="sxs-lookup"><span data-stu-id="e442b-124">**ESR System**</span></span>|<span data-ttu-id="e442b-125">Sélectionnez le système BVR par lequel vous pouvez envoyer de nouveaux coupons BVR aux clients.</span><span class="sxs-lookup"><span data-stu-id="e442b-125">Select the ESR system through which you can send new ESR coupons to customers.</span></span> <span data-ttu-id="e442b-126">Pour utiliser le système BVR utilisé par la banque que vous avez spécifiée dans le champ **Banque BVR**, sélectionnez **Selon banque BVR**.</span><span class="sxs-lookup"><span data-stu-id="e442b-126">To use the ESR system that is used by the bank that you have specified in **ESR Bank** field, select **Based on ESR Bank**.</span></span>|  

3.  <span data-ttu-id="e442b-127">Choisissez le bouton **Imprimer** pour imprimer l'état ou le bouton **Aperçu** pour l'afficher à l'écran.</span><span class="sxs-lookup"><span data-stu-id="e442b-127">Choose the **Print** button to print the report or choose the **Preview** button to view it on the screen.</span></span>  

<span data-ttu-id="e442b-128">Vous pouvez également réimprimer l'état BVR facture vente ou l'état coupon BVR vente.</span><span class="sxs-lookup"><span data-stu-id="e442b-128">You can also reprint the sales invoice ESR report or sales ESR coupon report.</span></span>  

## <a name="see-also"></a><span data-ttu-id="e442b-129">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="e442b-129">See Also</span></span>  
 <span data-ttu-id="e442b-130">[Paiements électroniques suisses avec BVR](swiss-electronic-payments-using-esr.md) </span><span class="sxs-lookup"><span data-stu-id="e442b-130">[Swiss Electronic Payments Using ESR](swiss-electronic-payments-using-esr.md) </span></span>  
 [<span data-ttu-id="e442b-131">Procédure : importer des paiements BVR</span><span class="sxs-lookup"><span data-stu-id="e442b-131">How to: Import ESR Payments</span></span>](how-to-import-esr-payments.md)

