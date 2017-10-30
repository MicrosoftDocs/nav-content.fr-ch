---
title: "Comment créer des gammes"
description: "Une gamme contient les données de base qui capturent les exigences du traitement correspondant à un article produit donné. Après la création d'un ordre de fabrication pour cet article, sa gamme gouvernera le calendrier des opérations tels que représenté dans la fenêtre **Gamme O.F.** sous l'ordre de fabrication."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 49cce1f32f1d66dc17c0d9758937541ef1baaae7
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-routings"></a><span data-ttu-id="f0d5f-104">Comment créer des gammes</span><span class="sxs-lookup"><span data-stu-id="f0d5f-104">How to: Create Routings</span></span>
<span data-ttu-id="f0d5f-105">Les sociétés manufacturières utilisent des gammes pour visualiser et gérer le processus de fabrication.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-105">Manufacturing companies use routings to visualize and direct the manufacturing process.</span></span>

<span data-ttu-id="f0d5f-106">La gamme est la base de la planification des processus et des capacités, de l'affectation planifiée du matériel en fonction des besoins et des documents de production.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-106">The routing is the basis of process scheduling, capacity scheduling, scheduled assignment of material needs, and manufacturing documents.</span></span>  

<span data-ttu-id="f0d5f-107">En ce qui concerne les nomenclatures de production, les gammes sont affectées à l'article fini produit.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-107">As for production BOMs, the routings are assigned to the manufacturing end item.</span></span> <span data-ttu-id="f0d5f-108">Une gamme contient les données de base qui capturent les exigences du traitement correspondant à un article produit donné.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-108">A routing holds master data that captures the process requirements of a given produced item.</span></span> <span data-ttu-id="f0d5f-109">Après la création d'un ordre de fabrication pour cet article, sa gamme gouvernera le calendrier des opérations tels que représenté dans la fenêtre **Gamme O.F.** sous l'ordre de fabrication.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-109">Once a production order is created for that item, its routing will govern the scheduling of operations as represented in the **Prod. Order Routing** window under the production order.</span></span>  

<span data-ttu-id="f0d5f-110">Pour pouvoir configurer une gamme, les éléments suivants doivent être en place :</span><span class="sxs-lookup"><span data-stu-id="f0d5f-110">Before you can set up a routing, the following must be in place:</span></span>  

- <span data-ttu-id="f0d5f-111">Des fiches article sont créées pour les articles parents qui participent à la production.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-111">Item cards are created for parent items that take part in manufacturing.</span></span> <span data-ttu-id="f0d5f-112">Pour plus d'informations, reportez vous à [Procédure : enregistrer de nouveaux articles](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="f0d5f-112">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>
- <span data-ttu-id="f0d5f-113">Les ressources de production sont configurées.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-113">Production resources are set up.</span></span> <span data-ttu-id="f0d5f-114">Pour plus d'informations, voir [Procédure : configurer les centres de charge et les postes de charge](production-how-to-set-up-work-and-machine-centers.md).</span><span class="sxs-lookup"><span data-stu-id="f0d5f-114">For more information, see [How to: Set Up Work Centers and Machine Centers](production-how-to-set-up-work-and-machine-centers.md).</span></span>

## <a name="to-create-a-routing"></a><span data-ttu-id="f0d5f-115">Pour créer une gamme</span><span class="sxs-lookup"><span data-stu-id="f0d5f-115">To create a routing</span></span>  
1.  <span data-ttu-id="f0d5f-116">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Gammes**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f0d5f-117">Sélectionnez l'action **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-117">Choose the **New** action.</span></span>  
3. <span data-ttu-id="f0d5f-118">Renseignez les champs selon vos besoins.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-118">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4.  <span data-ttu-id="f0d5f-119">Dans le champ **Type**, sélectionnez **Série** pour calculer la gamme de fabrication en fonction de la valeur de **N° opération** .</span><span class="sxs-lookup"><span data-stu-id="f0d5f-119">In the **Type** field, select **Serial** to calculate the production routing according to the value in the **Operation No.**</span></span> <span data-ttu-id="f0d5f-120">.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-120">field.</span></span>   
    <span data-ttu-id="f0d5f-121">Sélectionnez **Parallèle** pour calculer les opérations en fonction de la valeur de **Numéro de l'opération suivante**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-121">Select **Parallel** to calculate the operations according to the value in the **Next Operation No.**</span></span> <span data-ttu-id="f0d5f-122">.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-122">field.</span></span>  
5.  <span data-ttu-id="f0d5f-123">Pour modifier la gamme, définissez le champ **Statut** sur **Création en cours** ou sur **Modification en cours**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-123">To edit the routing, set the **Status** field to **New** or **Under Development**.</span></span> <span data-ttu-id="f0d5f-124">Pour l'activer, définissez le champ **Statut** sur **Validée**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-124">To activate it, set the **Status** field to **Certified**.</span></span>  

    <span data-ttu-id="f0d5f-125">Renseignez les lignes gamme.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-125">Proceed to fill in the routing lines.</span></span>
6.  <span data-ttu-id="f0d5f-126">Dans le champ **N° opération**,</span><span class="sxs-lookup"><span data-stu-id="f0d5f-126">In the **Operation No.**</span></span> <span data-ttu-id="f0d5f-127">entrez le numéro de la première opération \(par exemple, **10**\).</span><span class="sxs-lookup"><span data-stu-id="f0d5f-127">field, enter the number of the first operation, for example,  **10**.</span></span>  
7.  <span data-ttu-id="f0d5f-128">Dans le champ **Type**, sélectionnez le type de ressource utilisé, par exemple, **Centre de charge**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-128">In the **Type** field, specify which kind of resource is used, for example, **Work Center**.</span></span>  
8.  <span data-ttu-id="f0d5f-129">Dans le champ **N°**,</span><span class="sxs-lookup"><span data-stu-id="f0d5f-129">In the **No.**</span></span> <span data-ttu-id="f0d5f-130">sélectionnez la ressource à utiliser, ou entrez\-la.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-130">field, select the resource to be used, or type it in the field.</span></span>  
9.  <span data-ttu-id="f0d5f-131">Dans le champ **Code lien gamme**, vous pouvez entrer un code permettant de lier le composant à une opération spécifique.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-131">In the **Routing Link Code** field, enter a code to connect the component to a specific operation.</span></span> <span data-ttu-id="f0d5f-132">Pour plus d'informations, voir la section « Pour créer des liens gamme ».</span><span class="sxs-lookup"><span data-stu-id="f0d5f-132">For more information, see the "To create routing links" section.</span></span>
10.  <span data-ttu-id="f0d5f-133">Dans les champs **Temps d'exécution** et **Temps de préparation**, entrez les temps opératoires nécessaires pour exécuter l'opération.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-133">In the **Run Time** and **Setup Time** fields, enter the process times needed to perform the operation.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="f0d5f-134">Le temps de préparation est calculé par O.F., tandis que le temps d'exécution est calculé par article produit.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-134">Setup time is calculated per production order, whereas run time is calculated per produced item.</span></span>  

11.  <span data-ttu-id="f0d5f-135">Dans le champ **Capacités simultanées** , indiquez combien d'unités de la ressource sélectionnée sont utilisées pour exécuter l'opération.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-135">In the **Concurrent Capacities** field, specify how many units of the selected resource are used to perform the operation.</span></span> <span data-ttu-id="f0d5f-136">Par exemple, deux personnes affectées à une opération de livraison diviseront par deux le temps d'exécution.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-136">For example, two people allocated to one packing operation will halve the run time.</span></span>  
12.  <span data-ttu-id="f0d5f-137">Poursuivez le remplissage des lignes pour toutes les opérations intervenant dans la production de l'article en question.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-137">Continue to fill in lines for all operations involved in producing the item in question.</span></span>  
13.  <span data-ttu-id="f0d5f-138">Pour copier des lignes à partir d'une gamme existante, choisissez l'action **Copier gamme** pour sélectionner des lignes existantes.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-138">To copy lines from an existing routing, choose the **Copy Routing** action to select existing lines.</span></span>  
14. <span data-ttu-id="f0d5f-139">Certifiez la gamme.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-139">Certify the routing.</span></span>  
15. <span data-ttu-id="f0d5f-140">Vous pouvez désormais lier la nouvelle gamme à la fiche de l'article produit concerné en renseignant le champ **N° gamme**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-140">You can now attach the new routing to the card of the production item in question, by filling in the **Routing No.** field.</span></span> <span data-ttu-id="f0d5f-141">Pour plus d'informations, reportez vous à [Procédure : enregistrer de nouveaux articles](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="f0d5f-141">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="f0d5f-142">N'oubliez pas également de recalculer le coût standard de l'article de la fiche **Article** : choisissez l'action **Production**, sélectionnez l'action **Calculer coût standard**, puis sélectionnez l'action **Tous niveaux**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-142">Remember also to recalculate the item’s standard cost from the **Item** card: Choose the **Manufacturing** action, select the **Calc. Standard Cost** action, and then select the **All Levels** action.</span></span>  

## <a name="to-create-routing-links"></a><span data-ttu-id="f0d5f-143">Pour créer des liens gamme</span><span class="sxs-lookup"><span data-stu-id="f0d5f-143">To create routing links</span></span>
<span data-ttu-id="f0d5f-144">Vous pouvez créer des liens gamme pour lier des composants à des opérations spécifiques afin de conserver leur relation, même si la nomenclature de production ou la gamme sont modifiées.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-144">You can create routing links to connect components to specific operations in order to retain their relationship even though the production BOM or routing is modified.</span></span> <span data-ttu-id="f0d5f-145">Cela simplifie également la consommation automatique juste-à-temps des composants, à savoir lorsque l'opération liée commence, et non quand l'ordre de fabrication complet est lancé.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-145">It also facilitates just-in-time flushing of components, namely when the specific linked operation starts, not when the complete production order is released.</span></span> <span data-ttu-id="f0d5f-146">Pour plus d'informations, voir [Procédure : consommer en aval des composants en fonction de la production réalisée](production-how-to-flush-components-according-to-operation-output.md).</span><span class="sxs-lookup"><span data-stu-id="f0d5f-146">For more information see [How to: Flush Components According to Operation Output](production-how-to-flush-components-according-to-operation-output.md).</span></span>  

<span data-ttu-id="f0d5f-147">Les composants et opérations liés apparaissent dans une structure opératoire logique lorsque vous utilisez la fenêtre **Feuille production** pour la validation production et consommation, ce qui constitue un autre avantage majeur.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-147">Another important benefit is that linked components and operations are displayed in a logical process structure when you use the **Production Journal** window for output and consumption posting.</span></span>  

1.  <span data-ttu-id="f0d5f-148">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Gammes**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-148">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f0d5f-149">Ouvrez la gamme contenant les opérations que vous voulez lier.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-149">Open the routing that contains the operations that you want to link.</span></span>  

    <span data-ttu-id="f0d5f-150">Vérifiez que le statut de la gamme est **Modification en cours**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-150">Make sure the routing status is **Under Development**.</span></span>  

3.  <span data-ttu-id="f0d5f-151">Sur la ligne gamme appropriée, dans le champ **Code lien gamme** , sélectionnez un code.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-151">On the relevant routing line, in the **Routing Link Code** field, select a code.</span></span>  
4.  <span data-ttu-id="f0d5f-152">Ajoutez ensuite plusieurs codes lien gamme à d'autres opérations de la gamme, si nécessaire.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-152">Proceed to add different routing link codes to other operations in the routing, if relevant.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="f0d5f-153">Vous ne devez pas utiliser le même code lien gamme dans plusieurs opérations d'une gamme, car vous risquez de lier de manière incorrecte un même composant à deux opérations différentes et, de ce fait, de le consommer deux fois.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-153">You should not use the same routing link code in different operations on a routing because you may incorrectly link a component to two different operations, so that it is consumed two times.</span></span>  
    >   
    >  <span data-ttu-id="f0d5f-154">Il peut être judicieux de nommer le code lien gamme au terme de l'opération pour garantir que les liens gamme soient propres à chaque opération.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-154">It is a good idea to name the routing link code after the operation in order to ensure operation-specific routing links.</span></span>

5.  <span data-ttu-id="f0d5f-155">Définissez le statut de la gamme sur **Validé**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-155">Set the routing status to **Certified**.</span></span>  

    <span data-ttu-id="f0d5f-156">Les codes lien gamme sont désormais affectés aux opérations.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-156">Routing link codes are now assigned to operations.</span></span> <span data-ttu-id="f0d5f-157">Ensuite, vous devez créer le lien réel en attribuant les mêmes codes à des composants spécifiques de la nomenclature de production appropriée.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-157">Next, you must create the actual link by assigning the same codes to specific components in the relevant production BOM.</span></span>  

6.  <span data-ttu-id="f0d5f-158">Ouvrez la **Nomenclature de production** qui contient les composants à lier aux opérations ci-dessus.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-158">Open the **Production BOM** that contains the components that you want to link to the above operations.</span></span> <span data-ttu-id="f0d5f-159">Pour plus d'informations, reportez\-vous à [Procédure : créer des nomenclatures de production](production-how-to-create-production-boms.md).</span><span class="sxs-lookup"><span data-stu-id="f0d5f-159">For more information, see [How to: Create Production BOMs](production-how-to-create-production-boms.md).</span></span>
7.  <span data-ttu-id="f0d5f-160">Vérifiez que le statut de la nomenclature est **Modification en cours**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-160">Make sure the BOM status is **Under Development**.</span></span>  
8.  <span data-ttu-id="f0d5f-161">Sur la ligne appropriée de nomenclature de production, dans le champ **Code lien gamme**, sélectionnez le code que vous venez d'affecter à l'opération correspondante.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-161">On the relevant production BOM line, in the **Routing Link Code** field, select the code that you have just assigned to the relevant operation.</span></span>  
9. <span data-ttu-id="f0d5f-162">Ajoutez ensuite des codes lien gamme à d'autres composants, selon les opérations uniques pour lesquelles ils sont utilisés.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-162">Proceed to add routing link codes to other components according to the unique operations where they are used.</span></span>  
10. <span data-ttu-id="f0d5f-163">Définissez le statut de la nomenclature de production sur **Validé**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-163">Set the production BOM status to **Certified**.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="f0d5f-164">Pour activer les liens gamme d'un ordre de fabrication existant, vous devez actualiser l'ordre de fabrication.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-164">To enable the routing links on an existing production order, you must refresh the productio1n order.</span></span> <span data-ttu-id="f0d5f-165">Pour plus d'informations, voir [Procédure : créer des ordres de fabrication](production-how-to-create-production-orders.md).</span><span class="sxs-lookup"><span data-stu-id="f0d5f-165">For more information, see [How to: Create Production Orders](production-how-to-create-production-orders.md).</span></span>  

<span data-ttu-id="f0d5f-166">Les composants sélectionnés seront liés aux opérations sélectionnées lorsque vous créerez ou actualiserez un ordre de fabrication à l'aide de la nomenclature de production et de la gamme concernées.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-166">The selected components will now be linked to the selected operations when you create or refresh a production order using the production BOM and routing in question.</span></span> <span data-ttu-id="f0d5f-167">Ceci est visible dans la fenêtre **Composants O.F.** sous l'ordre de fabrication. Ici, vous pouvez également ajouter ou supprimer à tout moment les codes lien gamme définis.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-167">This is visible in the **Prod. Order Components** window under the production order, and here you can also remove and add the defined routing link codes at any time.</span></span>

## <a name="to-assign-personnel-tools-and-quality-measures-to-routing-operations"></a><span data-ttu-id="f0d5f-168">Pour affecter des qualifications, des outils et des contrôles qualité à des opérations gamme.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-168">To assign personnel, tools, and quality measures to routing operations.</span></span>
<span data-ttu-id="f0d5f-169">Si vous avez besoin de personnes ayant des qualifications, un savoir-faire particulier, ou bénéficiant d'une autorisation spéciale pour une opération, vous pouvez affecter ces personnes à l'opération.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-169">If you require personnel with qualifications, special knowledge, or special authorization for an operation, you can assign these personnel to the operation.</span></span> <span data-ttu-id="f0d5f-170">En outre, vous pouvez affecter des outils et des exigences de qualité à l'opération.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-170">In addition, you can assign tools and quality requirements to the operation.</span></span> <span data-ttu-id="f0d5f-171">Cette procédure décrit l'affectation de qualifications.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-171">This procedure describes how to assign personnel.</span></span> <span data-ttu-id="f0d5f-172">Les étapes sont similaires pour d'autres types d'informations sur l'opération.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-172">The steps are similar for other types of operation information.</span></span>

1.  <span data-ttu-id="f0d5f-173">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Gammes**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-173">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f0d5f-174">Ouvrez la gamme appropriée.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-174">Open the relevant routing.</span></span>  
3.  <span data-ttu-id="f0d5f-175">Sur le raccourci **Lignes**, sélectionnez la ligne à traiter, puis choisissez l'action **Qualifications**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-175">On the **Lines** FastTab, select the line that you want to process, and then choose the **Personnel** action.</span></span>  
4.  <span data-ttu-id="f0d5f-176">Renseignez les champs de la fenêtre **Qualifications gamme**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-176">Fill in the fields in the **Routing Personnel** window.</span></span>  
5.  <span data-ttu-id="f0d5f-177">Cliquez sur le bouton **OK** pour quitter la fenêtre.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-177">Choose the **OK** button to exit the window.</span></span> <span data-ttu-id="f0d5f-178">Les valeurs saisies sont copiées et affectées à l'opération.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-178">The entered values are copied and assigned to the operation.</span></span>    

## <a name="to-create-a-new-versions-of-a-routing"></a><span data-ttu-id="f0d5f-179">Pour créer une nouvelle version d'une gamme</span><span class="sxs-lookup"><span data-stu-id="f0d5f-179">To create a new versions of a routing</span></span>  
<span data-ttu-id="f0d5f-180">Le principe de la version permet de gérer différentes versions d'une gamme.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-180">The version principle enables you to manage several versions of a routing.</span></span> <span data-ttu-id="f0d5f-181">La structure d'une version de gamme correspond à la structure de la gamme composée d'un en-tête et de lignes version de gamme.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-181">The structure of the routing version corresponds to the structure of the routing consisting of the routing version header and the routing version lines.</span></span> <span data-ttu-id="f0d5f-182">La différence de base est définie par la date début.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-182">The basic difference is defined by the starting date.</span></span>  

1.  <span data-ttu-id="f0d5f-183">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Gammes**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-183">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Routings**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="f0d5f-184">Sélectionnez la gamme à copier, puis choisissez l'action **Versions**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-184">Select the routing to be copied, and then choose the **Versions** action.</span></span>  
3. <span data-ttu-id="f0d5f-185">Dans la fenêtre **Versions de gamme**, sélectionnez l'action **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-185">In the **Routing Versions** window, choose the **New** action.</span></span>
4. <span data-ttu-id="f0d5f-186">Renseignez les champs selon vos besoins.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-186">Fill in the fields as necessary.</span></span>
5.  <span data-ttu-id="f0d5f-187">Dans le champ **Code version**, saisissez le numéro d'identification unique de la version.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-187">In the **Version Code** field, enter the unique identification of the version.</span></span> <span data-ttu-id="f0d5f-188">Ce champ admet n'importe quelle combinaison de chiffres et de lettres.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-188">Any combination of numbers and letters is permitted.</span></span>  

    <span data-ttu-id="f0d5f-189">Le statut **Nouveau** est automatiquement affecté à la version que vous venez de créer.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-189">The newly created version is automatically assigned the status **New**.</span></span>  
6.  <span data-ttu-id="f0d5f-190">Pour créer des lignes opération, sélectionnez la première ligne vide, puis renseignez le champ **N° opération**</span><span class="sxs-lookup"><span data-stu-id="f0d5f-190">To create operation lines, select the first blank line, and then fill in the **Operation No.**</span></span> <span data-ttu-id="f0d5f-191">en fonction de la séquence des opérations.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-191">field according to the sequence of operations.</span></span>

    <span data-ttu-id="f0d5f-192">Les lignes opération sont triées par ordre croissant, en fonction du numéro des opérations.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-192">The operation lines are sorted in ascending order by operation numbers.</span></span> <span data-ttu-id="f0d5f-193">Afin de faciliter les modifications ultérieures, optez pour des incréments de taille adéquate.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-193">To be able to make changes later, we recommend you to select adequate step widths.</span></span> <span data-ttu-id="f0d5f-194">Le champ **N° opération suivante**</span><span class="sxs-lookup"><span data-stu-id="f0d5f-194">The **Next Operation No.**</span></span> <span data-ttu-id="f0d5f-195">se réfère à l'opération suivante.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-195">field refers to the following operation.</span></span> <span data-ttu-id="f0d5f-196">Vous pouvez y entrer directement le numéro de l'opération.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-196">The number of the operation can be entered directly.</span></span>

7. <span data-ttu-id="f0d5f-197">Lorsque la version de gamme est terminée, définissez le champ **Statut** sur **Validé**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-197">When the routing version is completed, setting the **Status** field to **Certified**.</span></span>

<span data-ttu-id="f0d5f-198">La validité de la version est définie par le champ **Date début**.</span><span class="sxs-lookup"><span data-stu-id="f0d5f-198">The time validity of the version is specified by the **Starting Date** field.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f0d5f-199">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="f0d5f-199">See Also</span></span>  
[<span data-ttu-id="f0d5f-200">Procédure : créer des nomenclatures de production</span><span class="sxs-lookup"><span data-stu-id="f0d5f-200">How to: Create Production BOMs</span></span>](production-how-to-create-production-boms.md)  
[<span data-ttu-id="f0d5f-201">Paramétrage de la production</span><span class="sxs-lookup"><span data-stu-id="f0d5f-201">Setting Up Manufacturing</span></span>](production-configure-production-processes.md)  
<span data-ttu-id="f0d5f-202">[Production](production-manage-manufacturing.md)  </span><span class="sxs-lookup"><span data-stu-id="f0d5f-202">[Manufacturing](production-manage-manufacturing.md)  </span></span>  
<span data-ttu-id="f0d5f-203">[Planifié](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="f0d5f-203">[Planning](production-planning.md) </span></span>  
[<span data-ttu-id="f0d5f-204">STOCKS ET EN-COURS</span><span class="sxs-lookup"><span data-stu-id="f0d5f-204">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="f0d5f-205">Achats</span><span class="sxs-lookup"><span data-stu-id="f0d5f-205">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="f0d5f-206">[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f0d5f-206">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
