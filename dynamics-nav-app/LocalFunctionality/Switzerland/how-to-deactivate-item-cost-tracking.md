---
title: "Procédure : désactiver la traçabilité coût article"
description: "Lorsque le stock n'est pas suivi pour un article, le coût article ne doit pas nécessairement être suivi et une écriture comptable article ne doit pas nécessairement être créée."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 8f5526fd7fc65ebb3b66d98ddffea9eb3f0854d9
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-deactivate-item-cost-tracking"></a>Procédure : désactiver la traçabilité coût article
Lorsque le stock n'est pas suivi pour un article, le coût article ne doit pas nécessairement être suivi et une écriture comptable article ne doit pas nécessairement être créée.  

Vous pouvez désactiver la traçabilité coût article pour un article. Généralement, la traçabilité coût article devrait être désactivée pour les articles consommables, comme les produits en papier usagé et pour les services comptabilisés comme des articles, comme les frais de stationnement forfaitaires. La traçabilité coût article devrait être désactivée sur les articles pour lesquels elle pourrait être trompeuse. Les articles pour lesquels la traçabilité coût article a été désactivée sont exclus des systèmes de réservation, de contrôle de disponibilité, de traçabilité et de planning de matériel.  

## <a name="to-deactivate-item-cost-tracking"></a>Pour désactiver la traçabilité coût article  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Articles**, puis sélectionnez le lien associé.  
2.  Sélectionnez l'article requis, puis choisissez l'action **Modifier**.  
3.  Sous l'onglet **Général**, sélectionnez la case à cocher **Pas de gestion stock**.  

    Une écriture comptable article ne sera pas créée lorsque vous validez une transaction pour cet article. Pour plus d'informations, consultez la table Écriture comptable article.  

    > [!NOTE]  
    >  Vous ne pouvez pas sélectionner la case à cocher **Pas de gestion stock** sur un article pour lequel des écritures comptables article ont déjà été validées.  

4.  Cliquez sur le bouton **OK**.  

## <a name="see-also"></a>Voir aussi  
 [Gestion des stocks suisse](swiss-inventory-management.md)   
 [Procédure : bloquer des articles en stock pour des ventes ou des achats](how-to-block-inventory-items-for-sales-or-purchases.md)

