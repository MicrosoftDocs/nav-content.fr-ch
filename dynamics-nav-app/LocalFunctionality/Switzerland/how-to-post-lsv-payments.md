---
title: "Procédure : valider des paiements LSV+"
description: "Vous pouvez valider des paiements après avoir reçu une notification de paiement LSV+ (Lastschrift Verfahren) de la banque."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 628c8e23bbd6cdd1dd518d57eb05b1be6f1245fa
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-post-lsv-payments"></a><span data-ttu-id="140bf-103">Procédure : valider des paiements LSV+</span><span class="sxs-lookup"><span data-stu-id="140bf-103">How to: Post LSV+ Payments</span></span>
<span data-ttu-id="140bf-104">Vous pouvez valider des paiements après avoir reçu une notification de paiement LSV+ (Lastschrift Verfahren) de la banque.</span><span class="sxs-lookup"><span data-stu-id="140bf-104">You can post payments after you have received Lastschrift Verfahren (LSV+) payment advice from the bank.</span></span>  

## <a name="to-post-lsv-payments"></a><span data-ttu-id="140bf-105">Pour valider des paiements LSV+</span><span class="sxs-lookup"><span data-stu-id="140bf-105">To post LSV+ payments</span></span>  

1.  <span data-ttu-id="140bf-106">Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles règlement**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="140bf-106">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="140bf-107">Sélectionnez la feuille requise, puis choisissez l'action **Modifier feuille**.</span><span class="sxs-lookup"><span data-stu-id="140bf-107">Select the required journal, and then choose the **Edit Journal** action.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="140bf-108">Vous pouvez sélectionner la feuille pour LSV où est défini le compte de contrepartie que vous souhaitez traiter.</span><span class="sxs-lookup"><span data-stu-id="140bf-108">You can select the journal batch for LSV where the balance account you want to address is defined.</span></span> <span data-ttu-id="140bf-109">Vous ne pouvez pas importer plusieurs lignes feuille LSV dans la même feuille règlement.</span><span class="sxs-lookup"><span data-stu-id="140bf-109">You cannot import more than one LSV journal line into the same cash receipt journal.</span></span> <span data-ttu-id="140bf-110">Pour plus d'informations, consultez la fenêtre Feuille règlement.</span><span class="sxs-lookup"><span data-stu-id="140bf-110">For more information, see the Cash Receipt Journal window.</span></span>  

3.  <span data-ttu-id="140bf-111">Choisissez l'action **Extraire de la feuille LSV**.</span><span class="sxs-lookup"><span data-stu-id="140bf-111">Choose the **Get From LSV Journal** action.</span></span>  
4.  <span data-ttu-id="140bf-112">Dans la fenêtre **Liste feuilles LSV**, sélectionnez la ligne feuille LSV que vous souhaitez importer dans la feuille règlement.</span><span class="sxs-lookup"><span data-stu-id="140bf-112">In the **LSV Journal List** window, select the LSV journal line that you want to import to the cash receipt journal.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="140bf-113">Vous ne pouvez importer que les lignes feuille dont le champ **Statut LSV** est défini sur **Fichier créé**.</span><span class="sxs-lookup"><span data-stu-id="140bf-113">You can only import journal lines where the **LSV Status** field is set to **File Created**.</span></span>  

5.  <span data-ttu-id="140bf-114">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="140bf-114">Choose the **OK** button.</span></span>  

    <span data-ttu-id="140bf-115">La ligne feuille LSV est importée dans la feuille règlement.</span><span class="sxs-lookup"><span data-stu-id="140bf-115">The LSV journal line is imported into the cash receipt journal.</span></span> <span data-ttu-id="140bf-116">La valeur du champ **Statut LSV** dans la fenêtre **Liste feuilles LSV** passe de **Fichier créé** à **Terminé**.</span><span class="sxs-lookup"><span data-stu-id="140bf-116">The value in the **LSV Status** field in the **LSV Journal List** window changes from **File Created** to **Finished**.</span></span>  

    <span data-ttu-id="140bf-117">Vous pouvez vérifier les paiements importés et les comparer avec votre avis de paiement bancaire dans la fenêtre **Feuille règlement**.</span><span class="sxs-lookup"><span data-stu-id="140bf-117">You can check the imported payments, and compare them with your bank payment advice in the **Cash Receipt Journal** window.</span></span> <span data-ttu-id="140bf-118">Vous pouvez également supprimer les lignes paiement qui n'ont pas pu être traitées par la banque, et pour lesquelles vous devez assurer un suivi avec le client manuellement.</span><span class="sxs-lookup"><span data-stu-id="140bf-118">You can also delete the payment lines that could not be processed by the bank, and for which you must follow up with the customer manually.</span></span>  

6.  <span data-ttu-id="140bf-119">Choisissez l'action **Valider**.</span><span class="sxs-lookup"><span data-stu-id="140bf-119">Choose the **Post** action.</span></span>  

## <a name="see-also"></a><span data-ttu-id="140bf-120">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="140bf-120">See Also</span></span>  
 <span data-ttu-id="140bf-121">[Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md) </span><span class="sxs-lookup"><span data-stu-id="140bf-121">[Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md) </span></span>  
 <span data-ttu-id="140bf-122">[Procédure : traiter un recouvrement LSV](how-to-process-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="140bf-122">[How to: Process an LSV Collection](how-to-process-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="140bf-123">[Procédure : clôturer un recouvrement LSV](how-to-close-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="140bf-123">[How to: Close an LSV Collection](how-to-close-an-lsv-collection.md) </span></span>  
 [<span data-ttu-id="140bf-124">Procédure : exporter des paiements avec LSV</span><span class="sxs-lookup"><span data-stu-id="140bf-124">How to: Export Payments Using LSV</span></span>](how-to-export-payments-using-lsv.md) 

