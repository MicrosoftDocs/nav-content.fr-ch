---
title: "Comptes généraux suisses"
description: "Les améliorations suisses incluent des fonctionnalités spéciales concernant les comptes généraux."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 574a9f233798f0e5bc3945af3391039f2e900112
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="swiss-general-ledger-accounts"></a>Comptes généraux suisses
[!INCLUDE[navnow](../../includes/navnow_md.md)] inclut des améliorations suisses aux comptes généraux.

- Maintenir les soldes en devise étrangère d'un compte bancaire dans la comptabilité.  
- Trier les numéros de comptes généraux dans la fenêtre **Plan comptable**.  
- Éviter l'utilisation des signes positifs ou négatifs incorrects pour les montants entrés manuellement dans les feuilles.  
- Afficher un aperçu des effets que la validation des feuilles comptabilité aurait sur les soldes de certains comptes généraux avant leur validation proprement dite.  

## <a name="general-ledger-accounts-and-general-journals"></a>Comptes généraux et feuilles comptabilité  
Les sociétés ont souvent des comptes bancaires différents pour les devises étrangères, et un compte général pour chaque compte bancaire. Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], vous pouvez paramétrer des informations sur le solde en devise étrangère et le code devise dans la fenêtre **Plan comptable**. Cela vous permet de maintenir le solde en devise étrangère d'origine d'un compte bancaire. Pour plus d'informations, consultez [la fenêtre Plan comptable](assetId:///fa407624-b670-44b6-8397-91aa606e4c39) et [la table Compte général](assetId:///a65c2b09-9bb2-43db-8c53-c047bfc49777).  

Par exemple, une société a deux comptes bancaires : un pour la devise société (DS) et l'autre pour les euros (EUR). Vous devez créer un compte général pour chaque compte bancaire. Pour le compte EUR, définissez le code devise comme **EUR** et validez les feuilles en EUR ou DS.  

Lorsque le taux de change pour EUR et DS est modifié, vous pouvez mettre à jour et ajuster le solde en devise société pour le compte général EUR à l'aide du traitement par lots Ajuster taux de change. Ce traitement par lots crée et valide des écritures ajustement devise dans la comptabilité et met à jour le solde DS.  

## <a name="data-type-for-general-ledger-accounts"></a>Type de données pour les comptes généraux  
Le type de données est défini sur Texte pour le code compte ou numéro de compte général afin de répondre aux exigences de tri du plan comptable commun KMU (Kontenrahmen Käfe) suisse standardisé. Pour plus d'informations, consultez [la fenêtre Plan comptable](assetId:///fa407624-b670-44b6-8397-91aa606e4c39). La liste des numéros de compte est triée en fonction du type de données Texte. Le plan comptable KMU contient les numéros de comptes suivants :  

- 1176  
- 119.0  
- 1190  

## <a name="correcting-positive-and-negative-signs-in-general-journals"></a>Correction des signes positifs et négatifs dans les feuilles comptabilité  
Lorsque vous entrez manuellement des montants dans la feuille, les signes positifs et négatifs des montants sont automatiquement vérifiés. En fonction du type de compte et du type de document, les signes incorrects sont automatiquement corrigés et un message est affiché. Pour plus d'informations, consultez [la table Ligne feuille comptabilité](assetId:///5308c791-0964-41d9-bc54-fd87e815d1be).  

Les montants des factures client, des avoirs fournisseur et des paiements doivent être positifs. Les montants des factures fournisseur, des avoirs client et des paiements doivent être négatifs.  

## <a name="viewing-temporary-balances-in-general-journals"></a>Affichage des soldes temporaires dans les feuilles comptabilité  
Avant de valider une feuille comptabilité, vous pouvez afficher un aperçu de l'effet que la validation aurait sur les soldes de certains comptes généraux. Vous pouvez ouvrir une fenêtre de statistiques qui affiche les soldes des comptes et les soldes des lignes actives qui incluaient les valeurs non validées pour la feuille actuelle. Pour plus d'informations, consultez [Procédure : afficher les soldes temporaires dans les feuilles comptabilité](how-to-view-temporary-balances-in-general-ledger-journals.md).  

## <a name="see-also"></a>Voir aussi  
 [Procédure : afficher les soldes temporaires dans les feuilles comptabilité](how-to-view-temporary-balances-in-general-ledger-journals.md)   
 [Fonctionnalités locales pour la Suisse](switzerland-local-functionality.md)

