---
title: "Procédure : restructurer les entrepôts"
description: "Vous pouvez souhaiter restructurer votre entrepôt avec de nouveaux codes et caractéristiques emplacement."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 852aa1a36b150d13d763e2c398265b9eaec5c3ea
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-restructure-warehouses"></a><span data-ttu-id="75cab-103">Procédure : restructurer les entrepôts</span><span class="sxs-lookup"><span data-stu-id="75cab-103">How to: Restructure Warehouses</span></span>
<span data-ttu-id="75cab-104">Vous pouvez souhaiter restructurer votre entrepôt avec de nouveaux codes et caractéristiques emplacement.</span><span class="sxs-lookup"><span data-stu-id="75cab-104">You may want to restructure your warehouse with new bin codes and new bin characteristics.</span></span> <span data-ttu-id="75cab-105">Ce type d'activité n'intervient que très rarement, mais un reclassement peut s'avérer nécessaire pour mettre à jour une opération ou la rendre plus efficace.</span><span class="sxs-lookup"><span data-stu-id="75cab-105">You will not undertake this kind of activity very often, but situations can occur where a reclassification is necessary to achieve or maintain a more efficient operation.</span></span> <span data-ttu-id="75cab-106">Par exemple :</span><span class="sxs-lookup"><span data-stu-id="75cab-106">For example:</span></span>  

- <span data-ttu-id="75cab-107">Vous pouvez être amené à créer des codes emplacement prenant en charge l'utilisation de la saisie automatisée avec des terminaux de saisie portables.</span><span class="sxs-lookup"><span data-stu-id="75cab-107">You might want to switch to bin codes that support the use of automatic data capture, for example, with hand-held devices.</span></span>  
- <span data-ttu-id="75cab-108">L'entrepôt peut avoir acheté un nouveau système de stockage garantissant de nouvelles possibilités pour stocker les articles.</span><span class="sxs-lookup"><span data-stu-id="75cab-108">The warehouse may have purchased a new rack system that gives new possibilities in item storage.</span></span>  
- <span data-ttu-id="75cab-109">La société peut avoir modifié sa gamme d'articles et déplacé l'entrepôt vers un nouvel emplacement pour prendre en charge cette modification.</span><span class="sxs-lookup"><span data-stu-id="75cab-109">The company may have altered its item assortment and moved the warehouse to a new physical location to accommodate this change.</span></span>  

<span data-ttu-id="75cab-110">Si votre entrepôt est configuré pour utiliser des emplacements mais sans prélèvement ni rangement suggérés, restructurez-le en créant les nouveaux emplacements que vous souhaitez utiliser ultérieurement.</span><span class="sxs-lookup"><span data-stu-id="75cab-110">If your warehouse is set up to use bins but not directed put-away and pick, restructure your warehouse by creating the new bins that you want to use in the future.</span></span>  

## <a name="to-restructure-a-basic-warehouse-that-uses-bins-only"></a><span data-ttu-id="75cab-111">Pour restructurer un entrepôt de base qui utilise uniquement des emplacements</span><span class="sxs-lookup"><span data-stu-id="75cab-111">To restructure a basic warehouse that uses bins only</span></span>  
1.  <span data-ttu-id="75cab-112">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Magasins**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="75cab-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Locations**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="75cab-113">Sur le raccourci **magasin**, paramétrez le champ **Sélection emplacement par déf sur** **Dernier emplacement utilisé**.</span><span class="sxs-lookup"><span data-stu-id="75cab-113">On the **Warehouse** FastTab, set the **Default Bin Selection** field to **Last-Used Bin**.</span></span>  
3.  <span data-ttu-id="75cab-114">Déplacez le contenu des emplacements actuels vers les emplacements que vous venez de créer.</span><span class="sxs-lookup"><span data-stu-id="75cab-114">Move all the contents of your current bins to the new bins that you have just created.</span></span>  

    1.  <span data-ttu-id="75cab-115">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuille reclassement article**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="75cab-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Item Reclassification Journal**, and then choose the related link.</span></span>  
    2.  <span data-ttu-id="75cab-116">Sélectionnez une ligne feuille, puis choisissez l'action **Extraire contenu emplacement**.</span><span class="sxs-lookup"><span data-stu-id="75cab-116">Select a journal line, and then choose the **Get Bin Content** action.</span></span>  
    3.  <span data-ttu-id="75cab-117">Sur le raccourci **Contenu emplacement**, définissez des filtres dans les champs **Code magasin**, **Code emplacement** et **N° article** pour indiquer le contenu que vous souhaitez déplacer.</span><span class="sxs-lookup"><span data-stu-id="75cab-117">On the **Bin Content** FastTab, set filters in the **Location Code**, **Bin Code**, and **Item No.** fields to specify the content that you want to move.</span></span>  
    4.  <span data-ttu-id="75cab-118">Cliquez sur le bouton **OK** pour renseigner une ligne feuille.</span><span class="sxs-lookup"><span data-stu-id="75cab-118">Choose the **OK** button to fill a journal line.</span></span>  
    5.  <span data-ttu-id="75cab-119">Dans le champ **Nouveau code emplacement**, sélectionnez l'emplacement vers lequel les articles doivent être déplacés.</span><span class="sxs-lookup"><span data-stu-id="75cab-119">In the **New Bin Code** field, select the bin to which the items should be moved.</span></span>  
    6.  <span data-ttu-id="75cab-120">Répétez les étapes b à e pour tout le contenu emplacement que vous souhaitez déplacer.</span><span class="sxs-lookup"><span data-stu-id="75cab-120">Repeat steps b through e for all bin content that you want to move.</span></span>  
    7.  <span data-ttu-id="75cab-121">Sélectionnez l'action **Valider**.</span><span class="sxs-lookup"><span data-stu-id="75cab-121">Choose the **Post** action.</span></span>  

<span data-ttu-id="75cab-122">Vous avez à présent vidé les emplacements où les articles se trouvaient auparavant.</span><span class="sxs-lookup"><span data-stu-id="75cab-122">You have now emptied the bins where the items used to be.</span></span> <span data-ttu-id="75cab-123">Les emplacements par défaut des articles sont alors remplacés par les nouveaux emplacements.</span><span class="sxs-lookup"><span data-stu-id="75cab-123">The default bins for your items have now been changed to the new bins.</span></span>  

## <a name="to-restructure-an-advanced-warehouse-that-uses-directed-put-away-and-pick"></a><span data-ttu-id="75cab-124">Pour restructurer un entrepôt avancé qui utilise le prélèvement et le rangement suggérés</span><span class="sxs-lookup"><span data-stu-id="75cab-124">To restructure an advanced warehouse that uses directed put-away and pick</span></span>  

1.  <span data-ttu-id="75cab-125">Créez les emplacements à utiliser ultérieurement.</span><span class="sxs-lookup"><span data-stu-id="75cab-125">Create the new bins that you want to use in the future.</span></span> <span data-ttu-id="75cab-126">Pour plus d'informations, voir [Procédure : créer des emplacements](warehouse-how-to-create-individual-bins.md).</span><span class="sxs-lookup"><span data-stu-id="75cab-126">For more information, see [How to: Create Bins](warehouse-how-to-create-individual-bins.md).</span></span>  
2.  <span data-ttu-id="75cab-127">Déplacez le contenu des emplacements actuels vers les emplacements que vous venez de créer.</span><span class="sxs-lookup"><span data-stu-id="75cab-127">Move all the contents of your current bins to the new bins that you just created.</span></span>  

    1.  <span data-ttu-id="75cab-128">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuilles reclassement entrepôt**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="75cab-128">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Warehouse Reclassification Journal**, and then choose the related link.</span></span>  
    2.  <span data-ttu-id="75cab-129">Pour les emplacements sans mouvement réel d'articles, créez une ligne pour chacun de vos emplacements actuels dans la **feuille reclassement entrepôt** avec l'ancien code emplacement , **Du code emplacement**, et le nouveau code emplacement , **Du code emplacement**.</span><span class="sxs-lookup"><span data-stu-id="75cab-129">For the bins where no real movement of items is involved, create a line for each of your current bins in the **Warehouse Reclassification Journal** with the old bin code, **From Bin Code**, and the new bin code, **To Bin Code**.</span></span>  
    3.  <span data-ttu-id="75cab-130">Si certains mouvements nécessitent des mouvements physiques réels de la part des employés, utilisez les **feuilles mouvements** pour préparer les instructions mouvement au lieu d'utiliser la feuille reclassement entrepôt.</span><span class="sxs-lookup"><span data-stu-id="75cab-130">If some of the movements involve actual physical movements that you want employees to perform, use **Movement Worksheets** to prepare movement instructions instead of using the warehouse reclassification journal.</span></span> <span data-ttu-id="75cab-131">Pour plus d'informations, voir [Procédure : déplacer des articles dans les configurations de stockage avancées](warehouse-how-to-move-items-in-advanced-warehousing.md).</span><span class="sxs-lookup"><span data-stu-id="75cab-131">For more information, see [How to: Move Items in Advanced Warehouse Configurations](warehouse-how-to-move-items-in-advanced-warehousing.md).</span></span>  

3.  <span data-ttu-id="75cab-132">Lorsque les anciens emplacements sont vidés, reclassez-les en tant qu'emplacements de type **CQ** pour vous assurer qu'ils ne sont pas inclus dans les flux d'articles.</span><span class="sxs-lookup"><span data-stu-id="75cab-132">When the old bins are emptied, reclassify them as **QC** type bins to ensure that they are not included in item flows.</span></span>  

    1.  <span data-ttu-id="75cab-133">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Magasins**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="75cab-133">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Locations**, and then choose the related link.</span></span>  
    2.  <span data-ttu-id="75cab-134">Sélectionnez la ligne indiquant l'emplacement, puis, sous l'onglet Naviguer, choisissez l'action **Emplacements**.</span><span class="sxs-lookup"><span data-stu-id="75cab-134">Select the line with the location, and then choose the **Bins** action.</span></span>  
    3.  <span data-ttu-id="75cab-135">Dans la fenêtre **Emplacements**, dans le champ **Code type emplacement**, entrez **CQ** pour chacun des anciens emplacements que vous avez vidés à l'étape 3 de la procédure précédente.</span><span class="sxs-lookup"><span data-stu-id="75cab-135">In the **Bins** window, in the **Bin Type Code** field, enter **QC** for each of the old bins that you emptied in step 3 in the previous procedure.</span></span>  

<span data-ttu-id="75cab-136">Vous avez à présent supprimé les emplacements du flux entrepôt et les avez reclassés en tant qu'emplacements de type CQ. Pour les emplacements de ce type, aucun des champs d'activité de la fenêtre **Types d'emplacement** n'est sélectionné, par conséquent ils ne sont pas pris en compte par le flux d'articles.</span><span class="sxs-lookup"><span data-stu-id="75cab-136">You have now removed the bins from the warehouse flow, and reclassified them as QC bins. QC bins have none of the activity fields in the **Bin Types** window selected and are therefore not considered by the item flow.</span></span> <span data-ttu-id="75cab-137">Pour plus d'informations, reportez-vous à [Procédure : configurer des types d'emplacement](warehouse-how-to-set-up-bin-types.md).</span><span class="sxs-lookup"><span data-stu-id="75cab-137">For more information, see [How to: Set Up Bin Types](warehouse-how-to-set-up-bin-types.md).</span></span>  

## <a name="to-delete-a-bin"></a><span data-ttu-id="75cab-138">Pour supprimer un emplacement</span><span class="sxs-lookup"><span data-stu-id="75cab-138">To delete a bin</span></span>  

1.  <span data-ttu-id="75cab-139">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Magasins**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="75cab-139">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Locations**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="75cab-140">Sélectionnez le magasin à partir duquel vous souhaitez supprimer des emplacements. Choisissez l'action **Emplacements**.</span><span class="sxs-lookup"><span data-stu-id="75cab-140">Select the location where you want to delete bins. Choose the **Bins** action.</span></span>  
3.  <span data-ttu-id="75cab-141">Sélectionnez les lignes des emplacements que vous souhaitez supprimer.</span><span class="sxs-lookup"><span data-stu-id="75cab-141">Select the lines for the bins that you want to delete.</span></span>  
4.  <span data-ttu-id="75cab-142">Cliquez sur l'action **Supprimer**.</span><span class="sxs-lookup"><span data-stu-id="75cab-142">Choose the **Delete** action.</span></span>  

<span data-ttu-id="75cab-143">Si vous sélectionnez le bouton **Oui**, l'emplacement est supprimé pour ne plus être utilisé, mais le code emplacement de toutes les écritures entrepôt reste le même.</span><span class="sxs-lookup"><span data-stu-id="75cab-143">If you choose the **Yes** button, the bin is deleted for use in the future, but the bin code in all warehouse entries remains the same.</span></span>  

<span data-ttu-id="75cab-144">Pour renommer un emplacement de façon à ce que tous les enregistrements associés à cet emplacement soient également renommés, y compris les enregistrements comprennent le contenu des emplacements, les lignes activité entrepôt, les lignes activité entrepôt enregistrées, les lignes feuille entrepôt, les lignes réception entrepôt, les lignes réception entrepôt validées, les lignes expédition entrepôt, les lignes expédition entrepôt validées et les écritures entrepôt, vous pouvez utiliser la fenêtre **Emplacements**.</span><span class="sxs-lookup"><span data-stu-id="75cab-144">If you want to rename a bin so that all records associated with the bin are also renamed, including bin contents, warehouse activity lines, registered warehouse activity lines, warehouse worksheet lines, warehouse receipt lines, posted warehouse receipt lines, warehouse shipment lines, posted warehouse shipment lines, and warehouse entries, you can do so in the **Bins** window.</span></span>  

## <a name="to-rename-a-bin-and-change-the-bin-code-in-all-records"></a><span data-ttu-id="75cab-145">Pour renommer un emplacement et modifier le code emplacement de tous les enregistrements</span><span class="sxs-lookup"><span data-stu-id="75cab-145">To rename a bin and change the bin code in all records</span></span>  

1.  <span data-ttu-id="75cab-146">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Magasins**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="75cab-146">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Locations**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="75cab-147">Sélectionnez le magasin dans lequel vous souhaitez renommer un emplacement ou modifier le code emplacement, puis choisissez l'action **Emplacements**.</span><span class="sxs-lookup"><span data-stu-id="75cab-147">Select the location where you want to rename a bin or change the bin code, and then choose the **Bins** action.</span></span>  
3.  <span data-ttu-id="75cab-148">Sélectionnez l'emplacement que vous souhaitez modifier et entrez un nouveau code emplacement dans le champ **Code**.</span><span class="sxs-lookup"><span data-stu-id="75cab-148">Select the bin that you want to change and enter a new bin code in the **Code** field.</span></span>  
4.  <span data-ttu-id="75cab-149">Cliquez sur le bouton **Oui**.</span><span class="sxs-lookup"><span data-stu-id="75cab-149">Choose the **Yes** button.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="75cab-150">Si vous sélectionnez **Oui** et que de nombreuses écritures se rapportent à cet emplacement, parce que vous n'avez pas supprimé de documents entrepôt depuis longtemps, par exemple, l'attribution d'un nouveau nom à tous les enregistrements peut prendre un certain temps.</span><span class="sxs-lookup"><span data-stu-id="75cab-150">If you choose **Yes** and there are many entries concerning this bin, for example, because you have not deleted warehouse documents for some time, it may take some time to rename all the records.</span></span> <span data-ttu-id="75cab-151">Par conséquent, si vous utilisez cette méthode, nous vous recommandons d'exécuter le traitement par lots **Supprimer documents entr. enreg.** avant de lancer le processus lié à l'attribution de nouveaux noms.</span><span class="sxs-lookup"><span data-stu-id="75cab-151">Therefore, if you use this method, consider running the batch job **Delete Registered Whse. Documents** before you start the renaming process.</span></span> <span data-ttu-id="75cab-152">Notez également que les seuls documents supprimés dans ce traitement par lots sont des rangements, des prélèvements, et des mouvements.</span><span class="sxs-lookup"><span data-stu-id="75cab-152">Also note that the only documents that are deleted in this batch job are put-aways, picks, and movements.</span></span>  
>   
>  <span data-ttu-id="75cab-153">Si vous renommez un emplacement réception ou un emplacement expédition, toutes les réceptions ou expéditions enregistrées se rapportant à l'emplacement concerné sont renommées.</span><span class="sxs-lookup"><span data-stu-id="75cab-153">If you are renaming a receiving bin or a shipping bin, all the posted receipts or shipments that refer to the bin in question are renamed.</span></span>  

## <a name="see-also"></a><span data-ttu-id="75cab-154">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="75cab-154">See Also</span></span>  
[<span data-ttu-id="75cab-155">Gestion d'entrepôt</span><span class="sxs-lookup"><span data-stu-id="75cab-155">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="75cab-156">STOCKS ET EN-COURS</span><span class="sxs-lookup"><span data-stu-id="75cab-156">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="75cab-157">[Configuration de la gestion des entrepôts](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="75cab-157">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="75cab-158">[Gestion des assemblages](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="75cab-158">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="75cab-159">Détails de conception : gestion d'entrepôt</span><span class="sxs-lookup"><span data-stu-id="75cab-159">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="75cab-160">[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="75cab-160">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
