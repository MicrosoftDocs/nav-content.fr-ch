---
title: "Procédure : importer des numéros de clearing bancaire suisses"
description: "Les numéros de clearing bancaire sont des numéros uniques utilisés pour identifier chaque agence ou établissement bancaire dans le répertoire des banques. Cette information est requise pour le paiement électronique. Le fichier peut être téléchargé à partir du site Web [Clearing interbancaire SIX](http://go.microsoft.com/fwlink/?LinkId=145121)."
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
ms.openlocfilehash: a45e794b745e76444b20b2fa953434517302d7ae
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-import-swiss-bank-clearing-numbers"></a><span data-ttu-id="dd05a-105">Procédure : importer des numéros de clearing bancaire suisses</span><span class="sxs-lookup"><span data-stu-id="dd05a-105">How to: Import Swiss Bank Clearing Numbers</span></span>
<span data-ttu-id="dd05a-106">Les numéros de clearing bancaire sont des numéros uniques utilisés pour identifier chaque agence ou établissement bancaire dans le répertoire des banques.</span><span class="sxs-lookup"><span data-stu-id="dd05a-106">Bank clearing numbers are unique numbers used to identify each bank agency or branch in the bank directory.</span></span> <span data-ttu-id="dd05a-107">Cette information est requise pour le paiement électronique.</span><span class="sxs-lookup"><span data-stu-id="dd05a-107">This information is required for electronic payment.</span></span> <span data-ttu-id="dd05a-108">Le fichier peut être téléchargé à partir du site Web [Clearing interbancaire SIX](http://go.microsoft.com/fwlink/?LinkId=145121).</span><span class="sxs-lookup"><span data-stu-id="dd05a-108">The file can be downloaded from the [SIX Interbank Clearing](http://go.microsoft.com/fwlink/?LinkId=145121) website.</span></span>  
  
 <span data-ttu-id="dd05a-109">Vous pouvez importer le fichier des banques CB (le fichier officiel des numéros de clearing bancaire suisses) pour mettre à jour les numéros de clearing bancaire dans le répertoire des banques.</span><span class="sxs-lookup"><span data-stu-id="dd05a-109">You can import the BC Bank Master file—the official Swiss bank clearing number file—to update the bank clearing number information in the bank directory.</span></span> <span data-ttu-id="dd05a-110">Lorsque vous importez le fichier de numéros de clearing bancaire, les données sont importées dans la table **Répertoire de la banque** et les données existantes sont remplacées.</span><span class="sxs-lookup"><span data-stu-id="dd05a-110">When you import the bank clearing number file, the data is imported to the **Bank Directory** table, and the existing data is overwritten.</span></span> <span data-ttu-id="dd05a-111">Après avoir importé le fichier de numéros de clearing bancaire, vous pouvez définir le numéro de l'établissement bancaire mis à jour pour les clients et les fournisseurs.</span><span class="sxs-lookup"><span data-stu-id="dd05a-111">After importing the bank clearing number file, you can define the updated bank branch number for customers and vendors.</span></span> <span data-ttu-id="dd05a-112">Pour plus d'informations, consultez les tables Compte bancaire client et Compte bancaire fournisseur.</span><span class="sxs-lookup"><span data-stu-id="dd05a-112">For more information, see the Customer Bank Account table and the Vendor Bank Account table.</span></span>  
  
### <a name="to-import-swiss-bank-clearing-numbers"></a><span data-ttu-id="dd05a-113">Pour importer des numéros de clearing bancaire suisses</span><span class="sxs-lookup"><span data-stu-id="dd05a-113">To import Swiss bank clearing numbers</span></span>  
  
1.  <span data-ttu-id="dd05a-114">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Répertoire de la banque**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="dd05a-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Directory**, and choose the related link.</span></span>  
  
2.  <span data-ttu-id="dd05a-115">Sous l'onglet **Accueil**, dans le groupe **Traiter**, choisissez **Lire DB Banques**.</span><span class="sxs-lookup"><span data-stu-id="dd05a-115">On the **Home** tab, in the **Process** group, select **Import Bank Directory**.</span></span>  
  
3.  <span data-ttu-id="dd05a-116">Dans la fenêtre **Lire DB Banques**, sur le raccourci **Options**, sélectionnez le champ **Mettre automatiquement à jour les numéros de clearing** pour mettre automatiquement à ajour les numéros de clearing bancaire.</span><span class="sxs-lookup"><span data-stu-id="dd05a-116">In the **Import Bank Directory** window, on the **Options** FastTab, select the **Automatically Update Clearing Numbers** field to update the bank clearing numbers automatically.</span></span>  
  
4.  <span data-ttu-id="dd05a-117">Choisissez le bouton **Imprimer** ou **Aperçu** pour importer les numéros de clearing bancaire, puis, dans la fenêtre **Ouvrir**, repérez le fichier que vous avez téléchargé à partir du site web de clearing interbancaire SIX.</span><span class="sxs-lookup"><span data-stu-id="dd05a-117">Choose the **Print** button or the **Preview** button to import the bank clearing numbers, and then, in the **Open** window, locate the file that you have downloaded from the SIX Interbank Clearing website.</span></span> <span data-ttu-id="dd05a-118">Choisissez le bouton **Ouvrir**.</span><span class="sxs-lookup"><span data-stu-id="dd05a-118">Choose the **Open** button.</span></span>  
  
     <span data-ttu-id="dd05a-119">Si vous choisissez le bouton **Imprimer**, le contenu du fichier sera imprimé.</span><span class="sxs-lookup"><span data-stu-id="dd05a-119">If you choose the **Print** button, the contents of the file will be printed.</span></span> <span data-ttu-id="dd05a-120">Si vous choisissez le bouton **Aperçu**, la table **Répertoire de la banque** sera mise à jour et un état présentant les numéros de clearing modifiés s'affichera.</span><span class="sxs-lookup"><span data-stu-id="dd05a-120">If you choose the **Preview** button, the **Bank Directory** table will be updated and a report that has clearing numbers that have changed will be displayed.</span></span>  
  
 <span data-ttu-id="dd05a-121">La procédure suivante décrit comment définir des numéros d'établissement bancaire pour les comptes bancaires clients, mais vous pouvez également la suivre pour définir des numéros d'établissement bancaire pour les comptes bancaires fournisseur.</span><span class="sxs-lookup"><span data-stu-id="dd05a-121">The following procedure describes how to define bank branch numbers for customer bank accounts, but the same steps also apply for defining bank branch numbers for vendor bank accounts.</span></span>  
  
### <a name="to-define-bank-branch-numbers-for-customer-bank-accounts"></a><span data-ttu-id="dd05a-122">Pour définir des numéros d'établissement bancaire pour les comptes bancaires clients</span><span class="sxs-lookup"><span data-stu-id="dd05a-122">To define bank branch numbers for customer bank accounts</span></span>  
  
1.  <span data-ttu-id="dd05a-123">Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Clients**, puis sélectionnez le lien associé.</span><span class="sxs-lookup"><span data-stu-id="dd05a-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="dd05a-124">Sélectionnez le client pour lequel vous souhaitez créer des informations de compte bancaire et, sous l'onglet **Naviguer**, dans le group **Client**, sélectionnez **Comptes bancaires**.</span><span class="sxs-lookup"><span data-stu-id="dd05a-124">Select the customer for whom you want to create bank account information, and on the **Navigate** tab, in the **Customer** group, select **Bank Accounts**.</span></span>  
  
3.  <span data-ttu-id="dd05a-125">Dans la fenêtre **Liste comptes bancaires client**, sélectionnez le compte bancaire requis et, sous l'onglet **Accueil**, sélectionnez **Modifier**.</span><span class="sxs-lookup"><span data-stu-id="dd05a-125">In the **Customer Bank Account List** window, select the required bank account, and on the **Home** tab, select **Edit**.</span></span>  
  
4.  <span data-ttu-id="dd05a-126">Sous le raccourci **Général**, dans le champ **Code établissement**,</span><span class="sxs-lookup"><span data-stu-id="dd05a-126">On the **General** FastTab, in the **Bank Branch No.**</span></span> <span data-ttu-id="dd05a-127">sélectionnez le numéro de l'agence ou de l'établissement bancaire.</span><span class="sxs-lookup"><span data-stu-id="dd05a-127">field, select the number of the bank agency or branch.</span></span>  
  
5.  <span data-ttu-id="dd05a-128">Cliquez sur le bouton **OK**.</span><span class="sxs-lookup"><span data-stu-id="dd05a-128">Choose the **OK** button.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="dd05a-129">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="dd05a-129">See Also</span></span>  
 <span data-ttu-id="dd05a-130">[Paiements électroniques suisses](swiss-electronic-payments.md) </span><span class="sxs-lookup"><span data-stu-id="dd05a-130">[Swiss Electronic Payments](swiss-electronic-payments.md) </span></span>  
 <span data-ttu-id="dd05a-131">Répertoire de la banque</span><span class="sxs-lookup"><span data-stu-id="dd05a-131">Bank Directory</span></span>   
 <span data-ttu-id="dd05a-132">Compte bancaire client</span><span class="sxs-lookup"><span data-stu-id="dd05a-132">Customer Bank Account</span></span>   
 <span data-ttu-id="dd05a-133">Compte bancaire fournisseur</span><span class="sxs-lookup"><span data-stu-id="dd05a-133">Vendor Bank Account</span></span>   
 [<span data-ttu-id="dd05a-134">Procédure : paramétrer des comptes bancaires fournisseurs</span><span class="sxs-lookup"><span data-stu-id="dd05a-134">How to: Set Up Vendor Bank Accounts</span></span>](how-to-set-up-vendor-bank-accounts.md)