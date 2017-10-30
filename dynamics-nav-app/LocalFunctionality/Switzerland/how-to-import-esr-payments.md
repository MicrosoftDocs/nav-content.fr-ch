---
title: "Procédure : importer des paiements BVR"
description: "Après avoir reçu le paiement d'un client, vous recevez un fichier qui contient des informations sur les factures payées. Vous pouvez recevoir ce fichier de votre banque par voie électronique ou par e-mail."
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
ms.openlocfilehash: 4cb9cb52eb3c7859b8da44e2743652e140c2d567
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-import-esr-payments"></a><span data-ttu-id="f9836-104">Procédure : importer des paiements BVR</span><span class="sxs-lookup"><span data-stu-id="f9836-104">How to: Import ESR Payments</span></span>
<span data-ttu-id="f9836-105">Après avoir reçu le paiement d'un client, vous recevez un fichier qui contient des informations sur les factures payées.</span><span class="sxs-lookup"><span data-stu-id="f9836-105">After you receive payment from a customer, you receive a file that contains information about paid invoices.</span></span> <span data-ttu-id="f9836-106">Vous pouvez recevoir ce fichier de votre banque par voie électronique ou par e-mail.</span><span class="sxs-lookup"><span data-stu-id="f9836-106">You can receive this file from your bank electronically, or by mail.</span></span>  
  
 <span data-ttu-id="f9836-107">Vous pouvez importer les données de facture BVR (bulletin de versement avec numéro de référence) à partir du fichier, imprimer les données à l'aide de l'état BVR facture vente ou l'état coupon BVR vente, et vérifier avant validation.</span><span class="sxs-lookup"><span data-stu-id="f9836-107">You can import the Einzahlungsschein mit Referenznummer (ESR) invoice data from the file, print the data by using the sales invoice ESR report or the sales ESR coupon report, and verify before posting.</span></span> <span data-ttu-id="f9836-108">Pour plus d'informations, voir la rubrique [Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md).</span><span class="sxs-lookup"><span data-stu-id="f9836-108">For more information, see [How to: Print ESR Invoices](how-to-print-esr-invoices.md).</span></span>  
  
### <a name="to-import-esr-payments"></a><span data-ttu-id="f9836-109">Pour importer des paiements BVR</span><span class="sxs-lookup"><span data-stu-id="f9836-109">To import ESR payments</span></span>  
  
1.  <span data-ttu-id="f9836-110">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles règlement**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="f9836-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Journals**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="f9836-111">Dans le champ **Nom de la feuille**, sélectionnez le nom de la feuille requis.</span><span class="sxs-lookup"><span data-stu-id="f9836-111">In the **Batch Name** field, select the required journal batch.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="f9836-112">La feuille doit être vide pour que vous puissiez importer le fichier BVR.</span><span class="sxs-lookup"><span data-stu-id="f9836-112">The journal must be empty before you import the ESR file.</span></span> <span data-ttu-id="f9836-113">Vous ne pouvez pas importer plusieurs fichiers BVR dans la même feuille règlement.</span><span class="sxs-lookup"><span data-stu-id="f9836-113">You cannot import more than one ESR file into the same cash receipt journal.</span></span>  
  
3.  <span data-ttu-id="f9836-114">Sous l'onglet **Accueil**, dans le groupe **Traiter**, choisissez **Lire fichier BVR**.</span><span class="sxs-lookup"><span data-stu-id="f9836-114">On the **Home** tab, in the **Process** group, choose **Read ESR File**.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="f9836-115">Si vous avez défini plusieurs banques BVR, un message d'avertissement vous demande de choisir la banque adéquate.</span><span class="sxs-lookup"><span data-stu-id="f9836-115">If you have defined more than one ESR bank, a warning message displays instructing you to choose the relevant bank.</span></span> <span data-ttu-id="f9836-116">Pour plus d'informations, voir la table Paramètres BVR.</span><span class="sxs-lookup"><span data-stu-id="f9836-116">For more information, see the ESR Setup table.</span></span>  
  
4.  <span data-ttu-id="f9836-117">Cliquez sur le bouton **Oui**, puis le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="f9836-117">Choose the **Yes** button, and then choose the **OK** button.</span></span>  
  
 <span data-ttu-id="f9836-118">Les informations sur les paiements sont importés dans les lignes feuille.</span><span class="sxs-lookup"><span data-stu-id="f9836-118">The payments information is imported to the journal lines.</span></span> <span data-ttu-id="f9836-119">Les paiements sont automatiquement appliqués aux factures respectives en fonction des numéros de référence BVR uniques.</span><span class="sxs-lookup"><span data-stu-id="f9836-119">The payments are automatically applied to the respective invoices according to unique ESR reference numbers.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="f9836-120">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="f9836-120">See Also</span></span>  
 <span data-ttu-id="f9836-121">[Paiements électroniques suisses avec BVR](swiss-electronic-payments-using-esr.md) </span><span class="sxs-lookup"><span data-stu-id="f9836-121">[Swiss Electronic Payments Using ESR](swiss-electronic-payments-using-esr.md) </span></span>  
 <span data-ttu-id="f9836-122">[Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md) </span><span class="sxs-lookup"><span data-stu-id="f9836-122">[How to: Print ESR Invoices](how-to-print-esr-invoices.md) </span></span>  
 <span data-ttu-id="f9836-123">Paramètres BVR</span><span class="sxs-lookup"><span data-stu-id="f9836-123">ESR Setup</span></span>   
 <span data-ttu-id="f9836-124">Feuille règlement</span><span class="sxs-lookup"><span data-stu-id="f9836-124">Cash Receipt Journal</span></span>   
 <span data-ttu-id="f9836-125">Feuille saisie BVR clients</span><span class="sxs-lookup"><span data-stu-id="f9836-125">Customer ESR Journal</span></span>
