---
title: Utilisation de l'extension QuickBooks Data Migration
description: "Décrit comment utiliser l'extension pour migrer des clients, des fournisseurs, des articles, et des comptes de QuickBooks Online à Dynamics NAV."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: extension, migrate, data, QuickBooks, import
ms.date: 05/24/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ff8f8f0c529966fc108d2d4c86e2d0681b1fc005
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---

# <a name="the-quickbooks-online-data-migration-extension-for-dynamics-nav"></a>L'extension QuickBooks Online Data Migration pour Dynamics NAV
Cette extension est incluse dans le guide d'installation facilité **Migration des données** pour vous aider à migrer les données métier pertinentes de QuickBooks Online vers [!INCLUDE[d365fin](includes/d365fin_md.md)]. Par exemple, c'est utile si votre activité se développe, et que vous avez décidé de mettre à niveau votre application de gestion d'entreprise en commençant à utiliser [!INCLUDE[d365fin](includes/d365fin_md.md)].

## <a name="what-data-can-i-import-from-quickbooks-online"></a>Quelles données puis-je importer de QuickBooks Online ?
Vous pouvez importer les données suivantes de QuickBooks Online vers [!INCLUDE[d365fin](includes/d365fin_md.md)]:  

* Clients
* Fournisseurs
* Articles
* Plan comptable 
* Commencer la transaction de solde en comptabilité
* Quantités disponibles pour les articles de stock
* Ouvrir des documents pour les clients et les fournisseurs, par exemple des factures, des avoirs, et des paiements

Nous effectuons une migration uniquement pour les montants complets dans les documents achat et vente. Nous ne mettons pas à jour les montants partiellement payés. Par exemple, si un client a payé 300 dollars sur un total de 500 dollars dans une facture vente, nous effectuons une migration des 500 complets. Si vous avez reçu des paiements partiels, vous devez les mettre à jour manuellement, avant ou après la migration de données. Nous vous recommandons de lettrer les transactions ouvertes avant d'exécuter une migration, pour faciliter juste des éléments ensuite.

> [!NOTE]  
>   Nous n'effectuons pas de migration des commandes achat ou des commandes vente.

## <a name="before-you-start"></a>Avant de commencer
Une grande partie du processus de migration consiste à spécifier les comptes vers lesquels migrer les transactions. Il est judicieux de planifier ce mappage avant d'exécuter la migration de données. Par exemple, les comptes où vous validez des transactions :  
  
* La vente d'articles ou de services à un client.
* L'achat d'articles ou de service auprès d'un fournisseur.  
* Ajustements des écritures comptables.  

[!INCLUDE[d365fin](includes/d365fin_md.md)] nécessite que les comptes généraux aient des numéros de compte. S'assurer que les numéros de compte sont affectés aux comptes dans QuickBooks Online.

Si les transactions de QuickBooks Online ont des montants de taxe, vous devez créer un compte taxes pour vos administrations fiscales dans [!INCLUDE[d365fin](includes/d365fin_md.md)] avant de pouvoir valider des transactions.

## <a name="how-do-i-start-using-the-extension"></a>Comment commencer à utiliser à l'extension ?
La mise en route est simple. Il vous suffit d'exécuter le guide d'installation assistée **Migration des données**. Voici comment :

1. Choisissez l'icône ![Page ou état pour la recherchei](media/ui-search/search_small.png "cône Page ou état pour la recherche") et entrez **Configuration assistée**, puis **Migrer des données métier**.
2. Suivez les instructions à chaque étape du guide d'installation assistée.

## <a name="what-do-i-do-after-i-migrate-data"></a>Que faire après une migration des données ?
Après avoir effectué une migration des données, les transactions ont le statut **Non validé**, vous pouvez les consulter et faire des ajustements. Pour consulter les transactions, accédez à la page où vous les trouveriez normalement. Par exemple, pour examiner les factures vente non validées, accédez à la page **Factures vente**. Pour consulter des feuilles paiement, accédez à la page **Feuilles paiement**.   

Il existe quelques éléments en particulier que vous devez effectuer :

* Si les transactions dans QuickBooks Online avaient des montants de majoration ou remise, vous devez ajouter manuellement les montants aux transactions associées dans [!INCLUDE[d365fin](includes/d365fin_md.md)] avant de les valider.
* Si vous utilisez la taxe sur la valeur ajoutée (TVA), vous devez ajouter un groupe comptabilisation marché et un groupe comptabilisation produit au paramétrage de la validation de manière à pouvoir valider les montants TVA.
* Vérifiez les soldes de début des comptes du grand livre. QuickBooks Online ne stocke pas le solde actuel de tous les comptes, vous pouvez être amené à corriger les soldes d'ouverture.

## <a name="see-also"></a>Voir aussi
[Importation des données métier à partir d'autres systèmes financiers](upload-data.md)  
[Personnalisation de [!INCLUDE[d365fin](includes/d365fin_md.md)] à l'aide des extensions](ui-extensions.md)  

