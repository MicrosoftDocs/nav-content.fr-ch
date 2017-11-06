---
title: Documents vente et documents achat suisses
description: "Les améliorations suisses incluent des fonctionnalités spéciales concernant les documents achat et vente."
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
ms.openlocfilehash: 9142631a84e8b756d4fa99b220d2cca15c4b8e79
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="swiss-purchase-documents-and-sales-documents"></a>Documents vente et documents achat suisses
[!INCLUDE[navnow](../../includes/navnow_md.md)] inclut des améliorations suisses aux documents achat et aux documents vente. Parmi celles-ci :  

- Descriptions de validation améliorées pour les écritures comptables générales, les écritures comptables client et les écritures comptables fournisseur. Pour plus d'informations, consultez les tables Écriture comptable, Écriture comptable client et Écriture comptable fournisseur.  
- Possibilité d'avoir des sous-titres, des sous-totaux et des totaux début et fin dans les devis et les commandes vente.  
- Possibilité d'arrondir les totaux de facture dans les lignes feuille paiement si un escompte est accordé.  
- Possibilité de désactiver l'impression de documents d'expédition supplémentaires pour les factures achat et les factures vente.  

## <a name="purchase-documents-and-sales-documents"></a>Documents achat et documents vente  
Les descriptions de validation validées sur les écritures comptables pour les commandes achat et les commandes vente affichent le nom des fournisseurs ou des clients, ainsi que les factures ou les numéros des avoirs. Par exemple, **Inv. 103020/ The Cannon Group PLC** est une description de validation. Cette description de validation affiche un numéro pertinent pour les transactions financières, qui permet d'analyser les transactions plus facilement.  

### <a name="sales-quotes-and-sales-orders"></a>Devis et commandes vente  
Lors de la création d'un devis ou d'une commande vente, si le type de ligne devis ou de ligne commande vente est **Début total** ou **Fin total**, les articles figurant sur les lignes sont marqués comme des articles physiques ou des articles de service. Les articles ont alors des sous-titres pour chaque groupe article, et un sous-total est créé pour chaque groupe article.  

Les articles sont divisés en fonction des valeurs générées par le système et affichées dans le champ **Niveau**.  

Vous pouvez spécifier un article comme une variante dans la ligne devis. Cela vous permet de répertorier les autres articles sans inclure le prix dans le devis. Vous pouvez également vous reporter à des parties spécifiques d'un devis ou d'une commande vente en fonction de la valeur affichée dans le champ **Position** de la ligne devis ou de la ligne commande vente. Pour plus d'informations, voir la table Ligne vente.  

## <a name="purchase-invoices-and-sales-invoices-with-payment-discounts"></a>Factures achat et factures vente avec escomptes  
Pour les factures achat et les factures vente, le montant de la facture est diminué du montant de l'escompte, puis arrondi. Le total de la facture est également arrondi si un escompte est accordé. Pour plus d'informations, consultez la table Paramètres comptabilité.  

## <a name="shipment-documents"></a>Documents d'expédition  
Dans la fenêtre **Paramètres ventes**, le champ **B.L. sur livraison et facture** permet de désactiver l'impression de documents d'expédition supplémentaires pour les factures achat et les factures vente. Lorsque vous validez une commande, une expédition validée et une facture validée sont automatiquement créées. Si la facture imprimée est également utilisée comme un document d'expédition, il n'est pas nécessaires d'imprimer d'autres documents d'expédition. Vous pouvez désactiver l'impression de documents d'expédition supplémentaires pour les factures achat et les factures vente en désélectionnant le champ **B.L. sur livraison et facture** dans la fenêtre **Paramètres ventes**. Pour plus d'informations, consultez la table Paramètres ventes.  

## <a name="see-also"></a>Voir aussi  
 [Procédure : paramétrer l'archivage automatique de documents en Suisse](how-to-set-up-automatic-archiving-of-documents-in-switzerland.md)   
 [Procédure : importer des codes postaux suisses](how-to-import-swiss-post-codes.md)   
 [Procédure : imprimer une liste des prélèvements stock à partir d'une commande vente](how-to-print-an-inventory-picking-list-from-a-sales-order.md)   
 [Procédure : imprimer des commandes achat et vente pendant le traitement par lots validation](how-to-print-sales-and-purchase-orders-during-batch-posting.md)   
 [Fonctionnalités locales pour la Suisse](switzerland-local-functionality.md)

