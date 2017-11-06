---
title: Gestion des stocks suisse
description: "Les améliorations suisses incluent des fonctionnalités spéciales de gestion des stocks."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 98e1c1dd52127710cedf3c849eee0fffc876e02b
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="swiss-inventory-management"></a>Gestion des stocks suisse
[!INCLUDE[navnow](../../includes/navnow_md.md)] inclut des améliorations suisses concernant la gestion des stocks. Parmi celles-ci :  

- Création d'états détaillés.  Pour plus d'informations, consultez les états Statistiques vente stock et Liste stock.  
- Possibilité de suivre une facture avec plusieurs expéditions.  
- Inclure un code magasin fiche article comme code magasin par défaut pour les lignes vente et les feuilles article. Pour plus d'informations, voir [Procédure : paramétrer des magasins](../../inventory-how-setup-locations.md). 

## <a name="managing-item-details"></a>Gestion des détails article  
Les sociétés peuvent avoir différents entrepôts pour différentes catégories de produits. Dans ces cas, vous devez utiliser le code magasin par défaut récupéré de la fiche article. Lorsque vous définissez un code magasin pour un article, il est transféré aux lignes vente et aux feuilles article comme code magasin article par défaut. Pour plus d'informations, consultez les tables Ligne vente et Ligne feuille article.  

Vous pouvez fournir une description d'article de maximum 50 caractères ainsi qu'un numéro de nomenclature de maximum 15 caractères. Pour plus d'informations, consultez la fenêtre Fiche article.  

Des informations supplémentaires, comme le numéro de client, le code adresse destinataire et le code vendeur client, sont enregistrées dans les écritures comptables article. Ces informations vous aident à créer des critères personnalisés pour la création de rapports, comme les revenus par client et les dispositions relatives aux ventes ou aux articles pour les vendeurs. Pour plus d'informations, consultez la table Écriture comptable article.  

## <a name="invoices-with-multiple-shipments"></a>Factures avec plusieurs expéditions  
Si plusieurs expéditions ont été validées pour un client, vous pouvez créer une facture combinée avec la fonction **Extraire lignes expédition**. Pour plus d'informations, consultez la fenêtre Extraire lignes expédition. Lorsque vous utilisez cette fonction, le texte créé sur les lignes facture comprend des informations sur le numéro d'expédition et la date d'expédition. Par exemple, le texte pourrait apparaître comme N° expédition 102040 du 25.01.01. Cela vous permet de suivre aisément des factures avec plusieurs expéditions.  

## <a name="see-also"></a>Voir aussi  
 [Procédure : bloquer une expédition pour des stocks négatifs](how-to-block-shipment-for-negative-inventory.md)   
 [Procédure : bloquer des articles en stock pour des ventes ou des achats](how-to-block-inventory-items-for-sales-or-purchases.md)   
 [Procédure : copier des articles existants vers de nouveaux articles](how-to-copy-existing-items-to-new-items.md)   
 [Procédure : désactiver la traçabilité coût article](how-to-deactivate-item-cost-tracking.md)   
 [Fonctionnalités locales pour la Suisse](switzerland-local-functionality.md)   
 [Procédure : paramétrer des magasins](../../inventory-how-setup-locations.md)

