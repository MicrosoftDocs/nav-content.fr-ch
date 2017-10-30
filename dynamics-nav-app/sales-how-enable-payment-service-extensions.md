---
title: Activer les paiements client via les services de paiement
description: Activez les services de paiement pour permettre aux clients de payer facilement leurs factures.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: online payment
ms.date: 07/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 71ff4af2fa3c0d1020a24de4325aafe17978f715
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-customer-payments-through-payment-services"></a><span data-ttu-id="05f5e-103">Procédure : activer les paiements client via les services de paiement</span><span class="sxs-lookup"><span data-stu-id="05f5e-103">How to: Enable Customer Payments Through Payment Services</span></span>
<span data-ttu-id="05f5e-104">Au lieu de collecter des paiements par l'intermédiaire de transferts bancaires ou de cartes de crédit, vos clients peuvent vous payer via leur compte avec des services de paiement, tels que Microsoft Pay, PayPal ou WorldPay.</span><span class="sxs-lookup"><span data-stu-id="05f5e-104">As an alternative to collecting payments through bank transfer or credit cards, your customers can pay you through their account with payment services, such as Microsoft Pay, PayPal, or WorldPay.</span></span>  

<span data-ttu-id="05f5e-105">Après avoir activé un service de paiement dans [!INCLUDE[d365fin](includes/d365fin_md.md)], un lien est disponible vers le service sur les documents vente que vous envoyez par e-mail à vos clients.</span><span class="sxs-lookup"><span data-stu-id="05f5e-105">After you enable a payment service in [!INCLUDE[d365fin](includes/d365fin_md.md)], a link to the service is available on sales documents that you send by email to your customers.</span></span> <span data-ttu-id="05f5e-106">Les clients peuvent utiliser le lien pour accéder au service de paiement et payer la facture, directement à partir du document vente.</span><span class="sxs-lookup"><span data-stu-id="05f5e-106">Customers can use the link to go to the payment service and pay the bill, directly from the sales document.</span></span> <span data-ttu-id="05f5e-107">Si vous ne souhaitez pas inclure le lien, par exemple, si un client paie en liquide, vous pouvez supprimer le service de paiement de la facture avant la validation.</span><span class="sxs-lookup"><span data-stu-id="05f5e-107">If you don't want to include the link, for example, if a customer will pay with cash, you can remove the payment service from the invoice before posting.</span></span>  

<span data-ttu-id="05f5e-108">Les extensions Microsoft Pay, PayPal Payments Standard et WorldPay Payments Standard sont installées dans [!INCLUDE[d365fin](includes/d365fin_md.md)] et sont prêtes à être activées.</span><span class="sxs-lookup"><span data-stu-id="05f5e-108">The Microsoft Pay, PayPal Payments Standard, and WorldPay Payments Standard extensions are installed in [!INCLUDE[d365fin](includes/d365fin_md.md)], and are ready for you to enable.</span></span>  

## <a name="to-enable-a-payment-service-in-included365finincludesd365finmdmd"></a><span data-ttu-id="05f5e-109">Pour activer un service de paiement dans [!INCLUDE[d365fin](includes/d365fin_md.md)]</span><span class="sxs-lookup"><span data-stu-id="05f5e-109">To enable a payment service in [!INCLUDE[d365fin](includes/d365fin_md.md)]</span></span>
1. <span data-ttu-id="05f5e-110">Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Services de paiement**, puis sélectionnez le lien connexe.</span><span class="sxs-lookup"><span data-stu-id="05f5e-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Services**, and then choose the related link.</span></span>  
2. <span data-ttu-id="05f5e-111">Dans la fenêtre **Services de paiement**, sélectionnez l'action **Nouveau**.</span><span class="sxs-lookup"><span data-stu-id="05f5e-111">In the **Payment Services** window, choose the **New** action.</span></span>  
3. <span data-ttu-id="05f5e-112">Sélectionnez le service de paiement, puis fermez la fenêtre.</span><span class="sxs-lookup"><span data-stu-id="05f5e-112">Select the payment service, and then close the window.</span></span>  
4. <span data-ttu-id="05f5e-113">Dans la fenêtre **Services de paiement**, sélectionnez l'action **Configuration**.</span><span class="sxs-lookup"><span data-stu-id="05f5e-113">In the **Payment Services** window, choose the **Setup** action.</span></span>  
5. <span data-ttu-id="05f5e-114">Renseignez les champs selon vos besoins.</span><span class="sxs-lookup"><span data-stu-id="05f5e-114">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
6. <span data-ttu-id="05f5e-115">Fermez la fenêtre.</span><span class="sxs-lookup"><span data-stu-id="05f5e-115">Close the window.</span></span>  

## <a name="to-select-a-payment-service-on-a-sales-invoice"></a><span data-ttu-id="05f5e-116">Pour sélectionner un service de paiement dans une facture vente</span><span class="sxs-lookup"><span data-stu-id="05f5e-116">To select a payment service on a sales invoice</span></span>
1. <span data-ttu-id="05f5e-117">Sur la page d'accueil, sélectionnez **Factures vente**.</span><span class="sxs-lookup"><span data-stu-id="05f5e-117">On the Home page, choose **Sales Invoices**.</span></span>  
2. <span data-ttu-id="05f5e-118">Ouvrez la facture vente que vous souhaitez payer en utilisant le service de paiement.</span><span class="sxs-lookup"><span data-stu-id="05f5e-118">Open the sales invoice that you want to pay by using the payment service.</span></span>  
3. <span data-ttu-id="05f5e-119">Dans le champ **Service de paiement**, sélectionnez le service de paiement.</span><span class="sxs-lookup"><span data-stu-id="05f5e-119">In the **Payment Service** field, choose the payment service.</span></span>  

    > [!NOTE]  
>   <span data-ttu-id="05f5e-120">Le champ **Service de paiement** est uniquement disponible si vous avez activé le service de paiement.</span><span class="sxs-lookup"><span data-stu-id="05f5e-120">The **Payment Service** field is available only if you've enabled the payment service.</span></span>  

## <a name="see-also"></a><span data-ttu-id="05f5e-121">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="05f5e-121">See Also</span></span>  
[<span data-ttu-id="05f5e-122">Définition des ventes</span><span class="sxs-lookup"><span data-stu-id="05f5e-122">Setting Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="05f5e-123">Ventes</span><span class="sxs-lookup"><span data-stu-id="05f5e-123">Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="05f5e-124">[Personnalisation de [!INCLUDE[d365fin](includes/d365fin_md.md)] à l'aide des extensions](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="05f5e-124">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions](ui-extensions.md)</span></span>  
<span data-ttu-id="05f5e-125">[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="05f5e-125">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
