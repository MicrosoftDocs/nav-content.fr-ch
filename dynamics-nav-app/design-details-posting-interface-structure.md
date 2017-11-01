---
title: "Détails de conception - Structure de l'interface de validation"
description: "Cette rubrique donne un aperçu des procédures globales dans la structure de l'interface de validation."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: posting, interface, design
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: cc5efca8087bc24ab988ae592a9ba60e4caf46bb
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-posting-interface-structure"></a><span data-ttu-id="46936-103">Détails de conception : Structure de l'interface de validation</span><span class="sxs-lookup"><span data-stu-id="46936-103">Design Details: Posting Interface Structure</span></span>
<span data-ttu-id="46936-104">Dans la structure de l'interface de validation [!INCLUDE[d365fin](includes/d365fin_md.md)], il y a plusieurs procédures globales utilisant la même structure :</span><span class="sxs-lookup"><span data-stu-id="46936-104">In the [!INCLUDE[d365fin](includes/d365fin_md.md)] posting interface structure, there are several global procedures that use the same structure:</span></span>  
  
* <span data-ttu-id="46936-105">Code de procédure d'appel RunWithCheck et RunWithoutCheck – interface de validation générique pour Gen. Jnl Line.</span><span class="sxs-lookup"><span data-stu-id="46936-105">RunWithCheck and RunWithoutCheck call procedure Code – generic posting interface for Gen. Jnl Line.</span></span>  
* <span data-ttu-id="46936-106">CustPostApplyCustLedgEntry – l'application du client de la validation, appelé à partir du codeunit 226 CustEntry-Appliquer les écritures validées.</span><span class="sxs-lookup"><span data-stu-id="46936-106">CustPostApplyCustLedgEntry – post customer application, called from codeunit 226 CustEntry-Apply Posted Entries.</span></span>  
* <span data-ttu-id="46936-107">VendPostApplyVendLedgEntry – validation de l'application du fournisseur, appelée à partir du codeunit 227 VendEntry-Appliquer les écritures validées.</span><span class="sxs-lookup"><span data-stu-id="46936-107">VendPostApplyVendLedgEntry – post vendor application, called from codeunit 227 VendEntry-Apply Posted Entries.</span></span>  
* <span data-ttu-id="46936-108">UnapplyCustLedgEntry – validation de la désapplication de l'application du client, appelée à partir du codeunit 226 CustEntry-Appliquer les écritures validées</span><span class="sxs-lookup"><span data-stu-id="46936-108">UnapplyCustLedgEntry – post unapply of customer application, called from codeunit 226 CustEntry-Apply Posted Entries</span></span>  
* <span data-ttu-id="46936-109">UnapplyVendLedgEntry – validation de la désapplication de l'application du fournisseur, appelée à partir du codeunit 227 VendEntry-Appliquer les écritures validées</span><span class="sxs-lookup"><span data-stu-id="46936-109">UnapplyVendLedgEntry – post unapply of vendor application, called from codeunit 227 VendEntry-Apply Posted Entries</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="46936-110">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="46936-110">See Also</span></span>  
[<span data-ttu-id="46936-111">Détails de conception : Structure du moteur de validation</span><span class="sxs-lookup"><span data-stu-id="46936-111">Design Details: Posting Engine Structure</span></span>](design-details-posting-engine-structure.md)
