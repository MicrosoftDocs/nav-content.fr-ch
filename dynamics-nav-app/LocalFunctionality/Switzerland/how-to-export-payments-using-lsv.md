---
title: "Procédure : exporter des paiements avec LSV"
description: "Vous pouvez exporter ou écrire des fichiers LSV+ (Lastschrift Verfahren) qui contiennent des informations sur les paiements après avoir clôturé le recouvrement LSV. Vous pouvez envoyer les fichiers générés à la banque sur disque, ou utiliser un transfert de fichier électronique comme votre logiciel de banque en ligne ou un portail Internet."
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
ms.openlocfilehash: b71163a277189dfecdd408c1fbbb1a9883862407
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-payments-using-lsv"></a><span data-ttu-id="db236-104">Procédure : exporter des paiements avec LSV</span><span class="sxs-lookup"><span data-stu-id="db236-104">How to: Export Payments Using LSV</span></span>
<span data-ttu-id="db236-105">Vous pouvez exporter ou écrire des fichiers LSV+ (Lastschrift Verfahren) qui contiennent des informations sur les paiements après avoir clôturé le recouvrement LSV.</span><span class="sxs-lookup"><span data-stu-id="db236-105">You can export or write Lastschrift Verfahren (LSV+) files that contain payments information after closing the LSV collection.</span></span> <span data-ttu-id="db236-106">Vous pouvez envoyer les fichiers générés à la banque sur disque, ou utiliser un transfert de fichier électronique comme votre logiciel de banque en ligne ou un portail Internet.</span><span class="sxs-lookup"><span data-stu-id="db236-106">You can send the generated files to the bank on a disk, or use an electronic file transfer such as your online banking software or an Internet portal.</span></span>  
  
### <a name="to-export-payments-using-lsv"></a><span data-ttu-id="db236-107">Pour exporter des paiements avec LSV</span><span class="sxs-lookup"><span data-stu-id="db236-107">To export payments using LSV</span></span>  
  
1.  <span data-ttu-id="db236-108">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Liste feuilles LSV**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="db236-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **LSV Journal List**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="db236-109">Dans la fenêtre **Liste feuilles LSV**, sélectionnez la feuille LSV requise.</span><span class="sxs-lookup"><span data-stu-id="db236-109">In the **LSV Journal List** window, select the required LSV journal.</span></span>  
  
3.  <span data-ttu-id="db236-110">Sous l'onglet **Actions**, dans le groupe **Fonctions**, sélectionnez **Écrire fichier LSV**.</span><span class="sxs-lookup"><span data-stu-id="db236-110">On the **Actions** tab, in the **Functions** group, select **Write LSV File**.</span></span>  
  
4.  <span data-ttu-id="db236-111">Dans la fenêtre **Écrire fichier LSV**, sur le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.</span><span class="sxs-lookup"><span data-stu-id="db236-111">In the **Write LSV File** window, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="db236-112">Champ</span><span class="sxs-lookup"><span data-stu-id="db236-112">Field</span></span>|<span data-ttu-id="db236-113">Description</span><span class="sxs-lookup"><span data-stu-id="db236-113">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="db236-114">**N°**</span><span class="sxs-lookup"><span data-stu-id="db236-114">**No.**</span></span>|<span data-ttu-id="db236-115">Spécifiez le numéro de la feuille LSV que vous souhaitez exporter.</span><span class="sxs-lookup"><span data-stu-id="db236-115">Specify the LSV journal number that you want to export.</span></span>|  
    |<span data-ttu-id="db236-116">**Test**</span><span class="sxs-lookup"><span data-stu-id="db236-116">**Test**</span></span>|<span data-ttu-id="db236-117">Spécifiez si vous envoyez des livraisons test à votre banque.</span><span class="sxs-lookup"><span data-stu-id="db236-117">Specify if you are sending test deliveries to your bank.</span></span> <span data-ttu-id="db236-118">La banque ne traite pas les fichiers test.</span><span class="sxs-lookup"><span data-stu-id="db236-118">The bank does not process test files.</span></span>|  
  
5.  <span data-ttu-id="db236-119">Toutes les lignes associées sont transférées à la feuille LSV.</span><span class="sxs-lookup"><span data-stu-id="db236-119">All related lines are transferred to the LSV journal.</span></span> <span data-ttu-id="db236-120">Le fichier LSV est généré dans le dossier prédéterminé.</span><span class="sxs-lookup"><span data-stu-id="db236-120">The LSV file is generated in the predetermined folder.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="db236-121">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="db236-121">See Also</span></span>  
 <span data-ttu-id="db236-122">[Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md) </span><span class="sxs-lookup"><span data-stu-id="db236-122">[Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md) </span></span>  
 <span data-ttu-id="db236-123">[Procédure : traiter un recouvrement LSV](how-to-process-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="db236-123">[How to: Process an LSV Collection](how-to-process-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="db236-124">[Procédure : clôturer un recouvrement LSV](how-to-close-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="db236-124">[How to: Close an LSV Collection](how-to-close-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="db236-125">[Procédure : valider des paiements LSV+](how-to-post-lsv-payments.md) </span><span class="sxs-lookup"><span data-stu-id="db236-125">[How to: Post LSV+ Payments](how-to-post-lsv-payments.md) </span></span>  
 <span data-ttu-id="db236-126">Feuille LSV</span><span class="sxs-lookup"><span data-stu-id="db236-126">LSV Journal</span></span>   
 <span data-ttu-id="db236-127">Ligne feuille LSV</span><span class="sxs-lookup"><span data-stu-id="db236-127">LSV Journal Line</span></span>   
 <span data-ttu-id="db236-128">Paramètres LSV</span><span class="sxs-lookup"><span data-stu-id="db236-128">LSV Setup</span></span>
