---
title: "Procédure : créer et imprimer une déclaration de TVA suisse"
description: "Sur la base des informations que vous avez spécifiées dans la fenêtre **Paramètres compta. TVA**, [!INCLUDE[navnow](../../includes/navnow_md.md)] peut créer automatiquement de nouveaux paramètres de déclaration de TVA pour le report de TVA réalisée. Avant d'exécuter les procédures de cette rubrique, assurez-vous que vous avez défini les paramètres de comptabilisation TVA avec des valeurs spécifiées pour les champs chiffrés vente et achat."
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
ms.openlocfilehash: b7f857df4ea1aa14107c65dd89142c41e0c55bf1
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-and-print-a-swiss-vat-statement"></a>Procédure : créer et imprimer une déclaration de TVA suisse
Sur la base des informations que vous avez spécifiées dans la fenêtre **Paramètres compta. TVA**, [!INCLUDE[navnow](../../includes/navnow_md.md)] peut créer automatiquement de nouveaux paramètres de déclaration de TVA pour le report de TVA réalisée. Avant d'exécuter les procédures de cette rubrique, assurez-vous que vous avez défini les paramètres de comptabilisation TVA avec des valeurs spécifiées pour les champs chiffrés vente et achat.  
  
### <a name="to-set-up-a-swiss-vat-statement-template"></a>Pour paramétrer un modèle déclaration TVA  
  
1.  Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Mettre à jour modèle déclaration TVA**, puis sélectionnez le lien associé.  
  
2.  Sélectionnez un modèle dans le champ **Nom modèle déclaration TVA**. Pour plus d'informations sur la création d'un modèle, voir la rubrique Modèle déclaration TVA.  
  
3.  Cliquez sur le bouton **OK**. Choisissez le bouton **Oui** pour confirmer la création d'un modèle.  
  
4.  Vérifiez la déclaration TVA générée et corrigez-la au besoin.  
  
     La page Déclaration TVA contient le champ **Chiffre déclaration TVA**, qui indique dans quel chiffre de l'état le résultat sera imprimé. Ce champ est automatiquement renseigné par le traitement par lots en fonction des informations de la fenêtre **Paramètres compta. TVA**. Le champ peut être modifié si nécessaire.  
  
### <a name="to-print-the-swiss-vat-statement"></a>Pour imprimer une déclaration TVA suisse  
  
1.  Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Déclaration TVA suisse**, puis sélectionnez le lien associé.  
  
2.  Sous le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.  
  
    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**Date de début**|Entrez la date à laquelle vous souhaitez faire débuter l’intervalle de temps des lignes déclaration de TVA dans l’état.|  
    |**Date de fin**|Entrez la date à laquelle vous souhaitez faire terminer l’intervalle de temps des lignes déclaration de TVA dans l’état.|  
    |**Clôturées avec n° historique des transactions TVA**|Sélectionnez l'historique des transactions TVA qui contient la source de comptabilisation des écritures ajustement TVA. Cette option évalue les périodes comptables qui ont déjà été réglées. Lorsque vous choisissez cette option, vous ne spécifiez aucune option dans les champs **Inclure écritures TVA**.|  
    |**Inclure écritures TVA**|Sélectionnez l'une des options disponibles.|  
    |**Inclure écritures TVA**|Sélectionnez l'une des options disponibles.|  
    |**Taux normal %**|Entrez le taux TVA standard qui s’applique pour la période.|  
    |**Taux réduit %**|Entrez le taux TVA réduit pour certains biens et services.|  
    |**Taux pour l'hébergement %**|Entrez le taux TVA pour hébergement qui s’applique pour la période.|  
    |**Normal (autre taux) %**|Entrez un autre taux TVA pour transactions standard qui s'applique à certaines transactions pendant la période.|  
    |**Réduit (autre taux) %**|Entrez un autre taux TVA pour autres transactions qui s'applique à certaines transactions pendant la période.|  
    |**Hébergement (autre taux) %**|Entrez un autre taux TVA pour hébergement qui s'applique à certaines transactions pendant la période.|  
    |**Afficher montants en devise report**|Sélectionnez pour afficher les montants dans une devise report. Pour plus d'informations, voir la rubrique [À propos de l'utilisation des devises report](about-using-additional-reporting-currencies.md).|  
  
## <a name="see-also"></a>Voir aussi  
 [Taxe sur la valeur ajoutée suisse](swiss-value-added-tax.md)   
 Déclaration TVA suisse
