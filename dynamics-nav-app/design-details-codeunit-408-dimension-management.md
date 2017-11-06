---
title: "Détails de conception - Codeunit 408 Gestion des axes analytiques"
description: "Codeunit 408 Gestion des axes analytiques est une bibliothèque de fonctions qui gère les tâches courantes qui sont liées aux axes analytiques, tels que copier d'une table à une autre ou d'un document à un autre."
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
ms.openlocfilehash: c1b3c745597f96165aec92a08bba50ecb6727a84
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="design-details-codeunit-408-dimension-management"></a><span data-ttu-id="b94a3-103">Détails de conception : Codeunit 408 Gestion des axes analytiques</span><span class="sxs-lookup"><span data-stu-id="b94a3-103">Design Details: Codeunit 408 Dimension Management</span></span>
<span data-ttu-id="b94a3-104">Codeunit 408 Gestion des axes analytiques est une bibliothèque de fonctions qui gère les tâches courantes qui sont liées aux axes analytiques, tels que copier d'une table à une autre ou d'un document à un autre.</span><span class="sxs-lookup"><span data-stu-id="b94a3-104">Codeunit 408 Dimension Management is a function library that handles common tasks that are related to dimensions, such as copying from one table to another or from one document to another.</span></span> <span data-ttu-id="b94a3-105">Cette rubrique répertorie les fonctions modifiées dans Microsoft Dynamics NAV 2013 R2 et spécifie ce qui doit être effectué sur les fonctions.</span><span class="sxs-lookup"><span data-stu-id="b94a3-105">This topic lists the functions that are modified in Microsoft Dynamics NAV 2013 R2 and specifies what has to be done to the functions.</span></span> <span data-ttu-id="b94a3-106">La plupart des fonctions sont supprimées parce qu'il n'y a pas besoin de copier entre les tables axe analytique.</span><span class="sxs-lookup"><span data-stu-id="b94a3-106">Many functions are deleted because there is no need for copying between dimension tables.</span></span>  

## <a name="modified-functions"></a><span data-ttu-id="b94a3-107">Fonctions modifiées</span><span class="sxs-lookup"><span data-stu-id="b94a3-107">Modified Functions</span></span>  

|<span data-ttu-id="b94a3-108">Nom de fonction</span><span class="sxs-lookup"><span data-stu-id="b94a3-108">Function Name</span></span>|<span data-ttu-id="b94a3-109">Description de modification</span><span class="sxs-lookup"><span data-stu-id="b94a3-109">Modification Description</span></span>|  
|-------------------|------------------------------|  
|<span data-ttu-id="b94a3-110">CheckDimSetIDComb</span><span class="sxs-lookup"><span data-stu-id="b94a3-110">CheckDimSetIDComb</span></span>|<span data-ttu-id="b94a3-111">Nouvelle fonction qui remplace les autres fonctions de contrôle et prend un ID d'ensemble de dimensions dans un argument au lieu d'une table axe analytique.</span><span class="sxs-lookup"><span data-stu-id="b94a3-111">New function that substitutes the other check functions and takes a Dimension Set ID as an argument instead of a dimension table.</span></span>|  
|<span data-ttu-id="b94a3-112">CheckDimSetIDComb</span><span class="sxs-lookup"><span data-stu-id="b94a3-112">CheckDimSetIDComb</span></span><br /><br /> <span data-ttu-id="b94a3-113">CheckDocDimComb</span><span class="sxs-lookup"><span data-stu-id="b94a3-113">CheckDocDimComb</span></span><br /><br /> <span data-ttu-id="b94a3-114">CheckServContractDimComb</span><span class="sxs-lookup"><span data-stu-id="b94a3-114">CheckServContractDimComb</span></span><br /><br /> <span data-ttu-id="b94a3-115">CheckDimBuffer</span><span class="sxs-lookup"><span data-stu-id="b94a3-115">CheckDimBuffer</span></span><br /><br /> <span data-ttu-id="b94a3-116">CheckDimComb</span><span class="sxs-lookup"><span data-stu-id="b94a3-116">CheckDimComb</span></span><br /><br /> <span data-ttu-id="b94a3-117">CheckDimValueComb</span><span class="sxs-lookup"><span data-stu-id="b94a3-117">CheckDimValueComb</span></span>|<span data-ttu-id="b94a3-118">Supprimer.</span><span class="sxs-lookup"><span data-stu-id="b94a3-118">Delete.</span></span> <span data-ttu-id="b94a3-119">L'ensemble de l'activité doit être changé en CheckDimSetIDComb.</span><span class="sxs-lookup"><span data-stu-id="b94a3-119">All usage should be changed to CheckDimSetIDComb.</span></span>|  
|<span data-ttu-id="b94a3-120">GetDefaultDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-120">GetDefaultDim</span></span>|<span data-ttu-id="b94a3-121">Modifiez pour renvoyer un ID d'ensemble de dimensions entier au lieu d'un ensemble d'enregistrements.</span><span class="sxs-lookup"><span data-stu-id="b94a3-121">Modify to return an integer Dimension Set ID instead of a set of records.</span></span>|  
|<span data-ttu-id="b94a3-122">CopyJnlLineDimToICJnlDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-122">CopyJnlLineDimToICJnlDim</span></span><br /><br /> <span data-ttu-id="b94a3-123">CopyICJnlDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-123">CopyICJnlDimToJnlLineDim</span></span><br /><br /> <span data-ttu-id="b94a3-124">CopyDocDimtoICDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-124">CopyDocDimtoICDocDim</span></span><br /><br /> <span data-ttu-id="b94a3-125">CopyICDocDimtoICDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-125">CopyICDocDimtoICDocDim</span></span>|<span data-ttu-id="b94a3-126">Modifier pour utiliser DimSetID -> ICJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-126">Modify to work with DimSetID -> ICJnlLineDim</span></span>|  

## <a name="deleted-functions"></a><span data-ttu-id="b94a3-127">Fonctions supprimées</span><span class="sxs-lookup"><span data-stu-id="b94a3-127">Deleted Functions</span></span>  
 <span data-ttu-id="b94a3-128">Les fonctions supprimées du codeunit 408 en relation avec la fonction Écritures de l'ensemble de dimensions sont répertoriées ci-dessous.</span><span class="sxs-lookup"><span data-stu-id="b94a3-128">Functions that are deleted from codeunit 408 in connection with the Dimension Set Entries feature are listed below.</span></span>  

> [!CAUTION]  
>  <span data-ttu-id="b94a3-129">Lors de la mise à niveau du code d'application depuis Microsoft Dynamics NAV 2009 ou des versions antérieures vers Microsoft Dynamics NAV 2016, les fonctions suivantes ne sont pas disponibles dans Microsoft Dynamics NAV 2016.</span><span class="sxs-lookup"><span data-stu-id="b94a3-129">During the upgrade of application code from Microsoft Dynamics NAV 2009 or earlier versions to Microsoft Dynamics NAV 2016, the following functions are not available in Microsoft Dynamics NAV 2016.</span></span> <span data-ttu-id="b94a3-130">Si des personnalisations utilisent une ou plusieurs fonctions, vous devez mettre à niveau ce code en conséquence.</span><span class="sxs-lookup"><span data-stu-id="b94a3-130">If you have customizations that use one or more of the functions, you must upgrade that code accordingly.</span></span>

 <span data-ttu-id="b94a3-131">InsertJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-131">InsertJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-132">UpdateJnlLineDefaultDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-132">UpdateJnlLineDefaultDim</span></span>  

 <span data-ttu-id="b94a3-133">GetJnlLineDefaultDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-133">GetJnlLineDefaultDim</span></span>  

 <span data-ttu-id="b94a3-134">GetPreviousDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-134">GetPreviousDocDefaultDim</span></span>  

 <span data-ttu-id="b94a3-135">GetPreviousProdDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-135">GetPreviousProdDocDefaultDim</span></span>  

 <span data-ttu-id="b94a3-136">InsertDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-136">InsertDocDim</span></span>  

 <span data-ttu-id="b94a3-137">UpdateDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-137">UpdateDocDefaultDim</span></span>  

 <span data-ttu-id="b94a3-138">ExtractDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-138">ExtractDocDefaultDim</span></span>  

 <span data-ttu-id="b94a3-139">InsertProdDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-139">InsertProdDocDim</span></span>  

 <span data-ttu-id="b94a3-140">UpdateProdDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-140">UpdateProdDocDefaultDim</span></span>  

 <span data-ttu-id="b94a3-141">InsertServContractDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-141">InsertServContractDim</span></span>  

 <span data-ttu-id="b94a3-142">UpdateServcontractDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-142">UpdateServcontractDim</span></span>  

 <span data-ttu-id="b94a3-143">UpdateDefaultDimNewDimValue</span><span class="sxs-lookup"><span data-stu-id="b94a3-143">UpdateDefaultDimNewDimValue</span></span>  

 <span data-ttu-id="b94a3-144">GetDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-144">GetDocDim</span></span>  

 <span data-ttu-id="b94a3-145">GetProdDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-145">GetProdDocDim</span></span>  

 <span data-ttu-id="b94a3-146">TypeToTableID1</span><span class="sxs-lookup"><span data-stu-id="b94a3-146">TypeToTableID1</span></span>  

 <span data-ttu-id="b94a3-147">TypeToTableID2</span><span class="sxs-lookup"><span data-stu-id="b94a3-147">TypeToTableID2</span></span>  

 <span data-ttu-id="b94a3-148">TypeToTableID3</span><span class="sxs-lookup"><span data-stu-id="b94a3-148">TypeToTableID3</span></span>  

 <span data-ttu-id="b94a3-149">TypeToTableID4</span><span class="sxs-lookup"><span data-stu-id="b94a3-149">TypeToTableID4</span></span>  

 <span data-ttu-id="b94a3-150">TypeToTableID5</span><span class="sxs-lookup"><span data-stu-id="b94a3-150">TypeToTableID5</span></span>  

 <span data-ttu-id="b94a3-151">DeleteJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-151">DeleteJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-152">DeleteDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-152">DeleteDocDim</span></span>  

 <span data-ttu-id="b94a3-153">DeletePostedDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-153">DeletePostedDocDim</span></span>  

 <span data-ttu-id="b94a3-154">DeleteProdDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-154">DeleteProdDocDim</span></span>  

 <span data-ttu-id="b94a3-155">DeleteServContractDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-155">DeleteServContractDim</span></span>  

 <span data-ttu-id="b94a3-156">ShowJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-156">ShowJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-157">SaveJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-157">SaveJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-158">ShowJnlLineNewDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-158">ShowJnlLineNewDim</span></span>  

 <span data-ttu-id="b94a3-159">SaveJnlLineNewDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-159">SaveJnlLineNewDim</span></span>  

 <span data-ttu-id="b94a3-160">ShowDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-160">ShowDocDim</span></span>  

 <span data-ttu-id="b94a3-161">SaveDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-161">SaveDocDim</span></span>  

 <span data-ttu-id="b94a3-162">ShowProdDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-162">ShowProdDocDim</span></span>  

 <span data-ttu-id="b94a3-163">SaveProdDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-163">SaveProdDocDim</span></span>  

 <span data-ttu-id="b94a3-164">ShowTempDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-164">ShowTempDim</span></span>  

 <span data-ttu-id="b94a3-165">SaveTempDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-165">SaveTempDim</span></span>  

 <span data-ttu-id="b94a3-166">ShowTempNewDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-166">ShowTempNewDim</span></span>  

 <span data-ttu-id="b94a3-167">SaveTempNewDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-167">SaveTempNewDim</span></span>  

 <span data-ttu-id="b94a3-168">SaveServContractDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-168">SaveServContractDim</span></span>  

 <span data-ttu-id="b94a3-169">MoveJnlLineDimToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-169">MoveJnlLineDimToLedgEntryDim</span></span>  

 <span data-ttu-id="b94a3-170">MoveDocDimToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-170">MoveDocDimToPostedDocDim</span></span>  

 <span data-ttu-id="b94a3-171">MoveOneDocDimToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-171">MoveOneDocDimToPostedDocDim</span></span>  

 <span data-ttu-id="b94a3-172">MoveLedgEntryDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-172">MoveLedgEntryDimToJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-173">MoveDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-173">MoveDimBufToJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-174">MoveDimBufToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-174">MoveDimBufToLedgEntryDim</span></span>  

 <span data-ttu-id="b94a3-175">MoveDimBufToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-175">MoveDimBufToPostedDocDim</span></span>  

 <span data-ttu-id="b94a3-176">MoveDimBufToGLBudgetDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-176">MoveDimBufToGLBudgetDim</span></span>  

 <span data-ttu-id="b94a3-177">CopyJnlLineDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-177">CopyJnlLineDimToJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-178">CopyLedgEntryDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-178">CopyLedgEntryDimToJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-179">CopyDocDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-179">CopyDocDimToDocDim</span></span>  

 <span data-ttu-id="b94a3-180">CopyPostedDocDimToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-180">CopyPostedDocDimToPostedDocDim</span></span>  

 <span data-ttu-id="b94a3-181">CopyDocDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-181">CopyDocDimToJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-182">CopyDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-182">CopyDimBufToJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-183">CopyDimBufToDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-183">CopyDimBufToDocDim</span></span>  

 <span data-ttu-id="b94a3-184">CopySCDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-184">CopySCDimToDocDim</span></span>  

 <span data-ttu-id="b94a3-185">MoveDocDimToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-185">MoveDocDimToLedgEntryDim</span></span>  

 <span data-ttu-id="b94a3-186">MoveDocDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-186">MoveDocDimToDocDim</span></span>  

 <span data-ttu-id="b94a3-187">MoveDocDimArchvToDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-187">MoveDocDimArchvToDocDim</span></span>  

 <span data-ttu-id="b94a3-188">MoveLedgEntryDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-188">MoveLedgEntryDimToDocDim</span></span>  

 <span data-ttu-id="b94a3-189">MoveProdDocDimToProdDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-189">MoveProdDocDimToProdDocDim</span></span>  

 <span data-ttu-id="b94a3-190">MoveJnlLineDimToProdDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-190">MoveJnlLineDimToProdDocDim</span></span>  

 <span data-ttu-id="b94a3-191">MoveJnlLineDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-191">MoveJnlLineDimToDocDim</span></span>  

 <span data-ttu-id="b94a3-192">MoveJnlLineDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-192">MoveJnlLineDimToJnlLineDim</span></span>  

 <span data-ttu-id="b94a3-193">CopyLedgEntryDimToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-193">CopyLedgEntryDimToLedgEntryDim</span></span>  

 <span data-ttu-id="b94a3-194">MoveTempFromDimToTempToDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-194">MoveTempFromDimToTempToDim</span></span>  

 <span data-ttu-id="b94a3-195">TransferTempToDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-195">TransferTempToDimToDocDim</span></span>  

 <span data-ttu-id="b94a3-196">MoveJnlLineDimToBuf</span><span class="sxs-lookup"><span data-stu-id="b94a3-196">MoveJnlLineDimToBuf</span></span>  

 <span data-ttu-id="b94a3-197">CopyICJnlDimToICJnlDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-197">CopyICJnlDimToICJnlDim</span></span>  

 <span data-ttu-id="b94a3-198">TestDimValue</span><span class="sxs-lookup"><span data-stu-id="b94a3-198">TestDimValue</span></span>  

 <span data-ttu-id="b94a3-199">TestNewDimValue</span><span class="sxs-lookup"><span data-stu-id="b94a3-199">TestNewDimValue</span></span>  

 <span data-ttu-id="b94a3-200">MoveDimBufToItemBudgetDim.</span><span class="sxs-lookup"><span data-stu-id="b94a3-200">MoveDimBufToItemBudgetDim.</span></span> <span data-ttu-id="b94a3-201">(Supprimé, car la table ItemBudgetDim est supprimée.)</span><span class="sxs-lookup"><span data-stu-id="b94a3-201">(Delete because the ItemBudgetDim Table is deleted.)</span></span>  

 <span data-ttu-id="b94a3-202">GetServContractDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-202">GetServContractDim</span></span>  

 <span data-ttu-id="b94a3-203">MoveTempDimToBuf</span><span class="sxs-lookup"><span data-stu-id="b94a3-203">MoveTempDimToBuf</span></span>  

 <span data-ttu-id="b94a3-204">UpdateSCInvLineDim</span><span class="sxs-lookup"><span data-stu-id="b94a3-204">UpdateSCInvLineDim</span></span>  

 <span data-ttu-id="b94a3-205">CopyJnlLineDimToBuffer</span><span class="sxs-lookup"><span data-stu-id="b94a3-205">CopyJnlLineDimToBuffer</span></span>  

 <span data-ttu-id="b94a3-206">UpdateDocDefaultDim2</span><span class="sxs-lookup"><span data-stu-id="b94a3-206">UpdateDocDefaultDim2</span></span>  

## <a name="see-also"></a><span data-ttu-id="b94a3-207">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="b94a3-207">See Also</span></span>
 <span data-ttu-id="b94a3-208">[Détails de conception : écritures d'ensemble de dimensions](design-details-dimension-set-entries.md) </span><span class="sxs-lookup"><span data-stu-id="b94a3-208">[Design Details: Dimension Set Entries](design-details-dimension-set-entries.md) </span></span>  
 <span data-ttu-id="b94a3-209">[Détails de conception : aperçu des écritures de l'ensemble de dimensions](design-details-dimension-set-entries-overview.md) </span><span class="sxs-lookup"><span data-stu-id="b94a3-209">[Design Details: Dimension Set Entries Overview](design-details-dimension-set-entries-overview.md) </span></span>  
 <span data-ttu-id="b94a3-210">[Détails de conception : recherche des croisements analytiques](design-details-searching-for-dimension-combinations.md) </span><span class="sxs-lookup"><span data-stu-id="b94a3-210">[Design Details: Searching for Dimension Combinations](design-details-searching-for-dimension-combinations.md) </span></span>  
 <span data-ttu-id="b94a3-211">[Détails de conception : structure de la table](design-details-table-structure.md) </span><span class="sxs-lookup"><span data-stu-id="b94a3-211">[Design Details: Table Structure](design-details-table-structure.md) </span></span>  
 [<span data-ttu-id="b94a3-212">Détails de conception : exemples de code de motifs modifiés dans les modifications</span><span class="sxs-lookup"><span data-stu-id="b94a3-212">Design Details: Code Examples of Changed Patterns in Modifications</span></span>](design-details-code-examples-of-changed-patterns-in-modifications.md)

