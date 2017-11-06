---
title: "Taxe sur la valeur ajoutée suisse"
description: "Les améliorations suisses incluent des fonctionnalités spéciales concernant la déclaration de TVA."
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
ms.openlocfilehash: 2060d66d895c907186ac3dbcf22ada1925b73f17
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="swiss-value-added-tax"></a>Taxe sur la valeur ajoutée suisse
[!INCLUDE[navnow](../../includes/navnow_md.md)] inclut les améliorations suivantes concernant la déclaration de TVA suisse :  

- Ajustement automatique des montants de TVA pour les factures, en fonctions des escomptes.  
- Taux de change TVA supplémentaires en devises étrangères.  
- Montants et pourcentages TVA inclus dans les feuilles.  

Pour plus d'informations sur les exigences suisses en matière de codage et de déclaration de TVA, consultez [Informations sur la TVA suisse](http://www.estv.admin.ch/mwst/dokumentation/00130/00947/00948/index.html?lang=fr), en particulier le document 605.525.01. Les informations sont disponibles en français, allemand et italien.  

## <a name="vat-amounts-and-vat-exchange-rates"></a>Montants de TVA et taux de change TVA  
Selon les lois locales en matière de TVA, le montant de base de TVA d'une facture peut être réduit du montant de l'escompte si une remise est accordée. Pour autoriser l'ajustement automatique de la TVA pour un escompte sur une facture, le champ **Ajuster pour escompte** est activé par défaut dans la fenêtre **Paramètres comptabilité**. Vous pouvez activer cette fonction dans les Paramètres comptabilisation TVA. Pour plus d'informations, consultez les tables Paramètres comptabilité et Paramètres comptabilisation TVA.  

### <a name="currency-exchange-rates-for-vat-reporting"></a>Taux de change devise pour les déclarations de TVA  
Pour les factures en devise étrangère, vous devez utiliser le taux de change officiel fourni par les pouvoirs publics pour le calcul de la TVA. Vous pouvez également paramétrer des taux de change supplémentaires pour la TVA, que vous pouvez utiliser pour des aspects de facturation autres que le calcul de la TVA. Vous pouvez fournir le taux de change TVA gouvernemental correct pour chaque devise étrangère pertinente dans les paramètres de taux de change pour les factures. Pour plus d'informations, consultez la table Taux de change devise.  

Vous pouvez également ajuster tous les montants de TVA dans les écritures TVA qui résultent de transactions en devise étrangère. Lorsque vous activez la fonction d'ajustement du taux de change TVA, les taux de change TVA sont ajustés automatiquement. Les différences positives qui résultent des taux de change sont validées sur les comptes gain de change. Les différences négatives qui résultent des taux de change sont validées sur les comptes perte de change. Pour plus d'informations, consultez le traitement par lots Ajuster taux de change.  

Des informations complémentaires, comme le taux de TVA et le montant devise initial, sont transférées dans les écritures TVA. Pour plus d'informations, voir la table Écriture TVA.  

## <a name="vat-information-in-journals"></a>Informations sur la TVA dans les feuilles  
Lorsque vous entrez une nouvelle ligne dans une feuille, les pourcentages de TVA et les montants de TVA pour le compte et le compte contrepartie de la ligne feuille sélectionnée sont renseignés dans la zone Statut de la feuille. Pour plus d'informations, consultez les fenêtres Feuille comptabilité, Feuille vente et Feuille achat.  

## <a name="see-also"></a>Voir aussi  
 [Taux de TVA pour la Suisse](vat-rates-for-switzerland.md)   
 [Procédure : créer et imprimer une déclaration de TVA suisse](how-to-create-and-print-a-swiss-vat-statement.md)   
 [Fonctionnalités locales pour la Suisse](switzerland-local-functionality.md)   

