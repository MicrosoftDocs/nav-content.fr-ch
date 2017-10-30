---
title: "Procédure : exporter des paiements avec OPAE"
description: "Vous pouvez générer un fichier pour paiement électronique à l'aide de la méthode OPAE (ordre de paiement électronique) et l'exporter pour permettre à la banque de l'utiliser pour les paiements."
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
ms.openlocfilehash: b9ea004d65e3d288c1c1db9771f4ed486c9f232b
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-payments-using-ezag"></a><span data-ttu-id="09fe1-103">Procédure : exporter des paiements avec OPAE</span><span class="sxs-lookup"><span data-stu-id="09fe1-103">How to: Export Payments Using EZAG</span></span>
<span data-ttu-id="09fe1-104">Vous pouvez générer un fichier pour paiement électronique à l'aide de la méthode OPAE (ordre de paiement électronique) et l'exporter pour permettre à la banque de l'utiliser pour les paiements.</span><span class="sxs-lookup"><span data-stu-id="09fe1-104">You can generate a file for electronic payment using the Elektronischer Zahlungsauftrag (EZAG) method, and export it for the bank to use for the payments.</span></span>  
  
### <a name="to-export-payments-using-ezag"></a><span data-ttu-id="09fe1-105">Pour exporter des paiements avec OPAE</span><span class="sxs-lookup"><span data-stu-id="09fe1-105">To export payments using EZAG</span></span>  
  
1.  <span data-ttu-id="09fe1-106">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles paiement**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="09fe1-106">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="09fe1-107">Dans le champ **Nom de la feuille**, sélectionnez le nom de la feuille.</span><span class="sxs-lookup"><span data-stu-id="09fe1-107">In the **Batch Name** field, select the journal batch name.</span></span>  
  
3.  <span data-ttu-id="09fe1-108">Sous l'onglet **Accueil**, dans le groupe **Traiter**, choisissez **Écrire fichier OPAE**.</span><span class="sxs-lookup"><span data-stu-id="09fe1-108">On the **Home** tab, in the **Process** group, choose **Generate EZAG File**.</span></span>  
  
4.  <span data-ttu-id="09fe1-109">Dans le traitement par lots **Fichier OPAE**, sur le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="09fe1-109">In the **EZAG File** batch job, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="09fe1-110">Champ</span><span class="sxs-lookup"><span data-stu-id="09fe1-110">Field</span></span>|<span data-ttu-id="09fe1-111">Description</span><span class="sxs-lookup"><span data-stu-id="09fe1-111">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="09fe1-112">**Banque à débiter**</span><span class="sxs-lookup"><span data-stu-id="09fe1-112">**Debit to bank**</span></span>|<span data-ttu-id="09fe1-113">Spécifiez le code de la banque à débiter.</span><span class="sxs-lookup"><span data-stu-id="09fe1-113">Specify the code of the bank to be charged.</span></span>|  
    |<span data-ttu-id="09fe1-114">**Totaliser par fournisseur**</span><span class="sxs-lookup"><span data-stu-id="09fe1-114">**Combined payment for vendor**</span></span>|<span data-ttu-id="09fe1-115">Spécifiez si les lignes paiement présentant les mêmes fournisseur, devise, banque et banque à débiter dans le fichier OPAE généré seront combinées.</span><span class="sxs-lookup"><span data-stu-id="09fe1-115">Specify if the payment lines that have the same vendor, currency, bank, and debit bank in the generated EZAG file will be combined.</span></span>|  
    |<span data-ttu-id="09fe1-116">**Expédition avec disque**</span><span class="sxs-lookup"><span data-stu-id="09fe1-116">**Shipment with disk**</span></span>|<span data-ttu-id="09fe1-117">Spécifiez si le fichier OPAE sera enregistré sur un disque que vous pourrez remettre à la banque.</span><span class="sxs-lookup"><span data-stu-id="09fe1-117">Specify if the EZAG file will be saved to a disk so that you can deliver it to the bank.</span></span>|  
  
5.  <span data-ttu-id="09fe1-118">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="09fe1-118">Choose the **OK** button.</span></span> <span data-ttu-id="09fe1-119">Le fichier OPAE est généré.</span><span class="sxs-lookup"><span data-stu-id="09fe1-119">The EZAG file is generated.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="09fe1-120">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="09fe1-120">See Also</span></span>  
 <span data-ttu-id="09fe1-121">[Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md) </span><span class="sxs-lookup"><span data-stu-id="09fe1-121">[Swiss Electronic Payments Using DTA](swiss-electronic-payments-using-dta.md) </span></span>  
 <span data-ttu-id="09fe1-122">[Procédure : Proposer paiement DTA pour les fournisseurs](how-to-suggest-dta-payment-for-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="09fe1-122">[How to: Suggest DTA Payment for Vendors](how-to-suggest-dta-payment-for-vendors.md) </span></span>  
 <span data-ttu-id="09fe1-123">[Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span><span class="sxs-lookup"><span data-stu-id="09fe1-123">[How to: Verify a List of Vendors for DTA Payments](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span></span>  
 <span data-ttu-id="09fe1-124">[Procédure : soumettre des paiements DTA](how-to-submit-dta-payments.md) </span><span class="sxs-lookup"><span data-stu-id="09fe1-124">[How to: Submit DTA Payments](how-to-submit-dta-payments.md) </span></span>  
 <span data-ttu-id="09fe1-125">Paramètres DTA</span><span class="sxs-lookup"><span data-stu-id="09fe1-125">DTA Setup</span></span>   
 <span data-ttu-id="09fe1-126">Feuille paiement</span><span class="sxs-lookup"><span data-stu-id="09fe1-126">Payment Journal</span></span>
