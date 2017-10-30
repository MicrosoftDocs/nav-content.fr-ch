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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 895dedf4b86157dca24b1107495df2047135fd67
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-post-lsv-payments"></a><span data-ttu-id="bd206-103">Procédure : valider des paiements LSV+</span><span class="sxs-lookup"><span data-stu-id="bd206-103">How to: Post LSV+ Payments</span></span>
<span data-ttu-id="bd206-104">Vous pouvez valider des paiements après avoir reçu une notification de paiement LSV+ (Lastschrift Verfahren) de la banque.</span><span class="sxs-lookup"><span data-stu-id="bd206-104">You can post payments after you have received Lastschrift Verfahren (LSV+) payment advice from the bank.</span></span>  
  
### <a name="to-post-lsv-payments"></a><span data-ttu-id="bd206-105">Pour valider des paiements LSV+</span><span class="sxs-lookup"><span data-stu-id="bd206-105">To post LSV+ payments</span></span>  
  
1.  <span data-ttu-id="bd206-106">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles règlement**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="bd206-106">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Journals**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="bd206-107">Sélectionnez la feuille requise, et sous l'onglet **Accueil**, dans le groupe **Traiter**, choisissez **Modifier feuille**.</span><span class="sxs-lookup"><span data-stu-id="bd206-107">Select the required journal, and on the **Home** tab, in the **Process** group, choose **Edit Journal**.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="bd206-108">Vous pouvez sélectionner la feuille pour LSV où est défini le compte de contrepartie que vous souhaitez traiter.</span><span class="sxs-lookup"><span data-stu-id="bd206-108">You can select the journal batch for LSV where the balance account you want to address is defined.</span></span> <span data-ttu-id="bd206-109">Vous ne pouvez pas importer plusieurs lignes feuille LSV dans la même feuille règlement.</span><span class="sxs-lookup"><span data-stu-id="bd206-109">You cannot import more than one LSV journal line into the same cash receipt journal.</span></span> <span data-ttu-id="bd206-110">Pour plus d'informations, consultez la fenêtre Feuille règlement.</span><span class="sxs-lookup"><span data-stu-id="bd206-110">For more information, see the Cash Receipt Journal window.</span></span>  
  
3.  <span data-ttu-id="bd206-111">Sous l'onglet **Accueil**, dans le groupe **Traiter**, choisissez **Extraire de la feuille LSV**.</span><span class="sxs-lookup"><span data-stu-id="bd206-111">On the **Home** tab, in the **Process** group, choose **Get From LSV Journal**.</span></span>  
  
4.  <span data-ttu-id="bd206-112">Dans la fenêtre **Liste feuilles LSV**, sélectionnez la ligne feuille LSV que vous souhaitez importer dans la feuille règlement.</span><span class="sxs-lookup"><span data-stu-id="bd206-112">In the **LSV Journal List** window, select the LSV journal line that you want to import to the cash receipt journal.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="bd206-113">Vous ne pouvez importer que les lignes feuille dont le champ **Statut LSV** est défini sur **Fichier créé**.</span><span class="sxs-lookup"><span data-stu-id="bd206-113">You can only import journal lines where the **LSV Status** field is set to **File Created**.</span></span>  
  
5.  <span data-ttu-id="bd206-114">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="bd206-114">Choose the **OK** button.</span></span>  
  
     <span data-ttu-id="bd206-115">La ligne feuille LSV est importée dans la feuille règlement.</span><span class="sxs-lookup"><span data-stu-id="bd206-115">The LSV journal line is imported into the cash receipt journal.</span></span> <span data-ttu-id="bd206-116">La valeur du champ **Statut LSV** dans la fenêtre **Liste feuilles LSV** passe de **Fichier créé** à **Terminé**.</span><span class="sxs-lookup"><span data-stu-id="bd206-116">The value in the **LSV Status** field in the **LSV Journal List** window changes from **File Created** to **Finished**.</span></span>  
  
     <span data-ttu-id="bd206-117">Vous pouvez vérifier les paiements importés et les comparer avec votre avis de paiement bancaire dans la fenêtre **Feuille règlement**.</span><span class="sxs-lookup"><span data-stu-id="bd206-117">You can check the imported payments, and compare them with your bank payment advice in the **Cash Receipt Journal** window.</span></span> <span data-ttu-id="bd206-118">Vous pouvez également supprimer les lignes paiement qui n'ont pas pu être traitées par la banque, et pour lesquelles vous devez assurer un suivi avec le client manuellement.</span><span class="sxs-lookup"><span data-stu-id="bd206-118">You can also delete the payment lines that could not be processed by the bank, and for which you must follow up with the customer manually.</span></span>  
  
6.  <span data-ttu-id="bd206-119">Sous l'onglet **Accueil**, dans le groupe **Validation**, choisissez **Valider**.</span><span class="sxs-lookup"><span data-stu-id="bd206-119">On the **Home** tab, in the **Posting** group, choose **Post**.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="bd206-120">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="bd206-120">See Also</span></span>  
 <span data-ttu-id="bd206-121">[Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md) </span><span class="sxs-lookup"><span data-stu-id="bd206-121">[Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md) </span></span>  
 <span data-ttu-id="bd206-122">[Procédure : traiter un recouvrement LSV](how-to-process-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="bd206-122">[How to: Process an LSV Collection](how-to-process-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="bd206-123">[Procédure : clôturer un recouvrement LSV](how-to-close-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="bd206-123">[How to: Close an LSV Collection](how-to-close-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="bd206-124">[Procédure : exporter des paiements avec LSV](how-to-export-payments-using-lsv.md) </span><span class="sxs-lookup"><span data-stu-id="bd206-124">[How to: Export Payments Using LSV](how-to-export-payments-using-lsv.md) </span></span>  
 <span data-ttu-id="bd206-125">Feuille règlement</span><span class="sxs-lookup"><span data-stu-id="bd206-125">Cash Receipt Journal</span></span>   
 <span data-ttu-id="bd206-126">Feuille LSV</span><span class="sxs-lookup"><span data-stu-id="bd206-126">LSV Journal</span></span>   
 <span data-ttu-id="bd206-127">Ligne feuille LSV</span><span class="sxs-lookup"><span data-stu-id="bd206-127">LSV Journal Line</span></span>
