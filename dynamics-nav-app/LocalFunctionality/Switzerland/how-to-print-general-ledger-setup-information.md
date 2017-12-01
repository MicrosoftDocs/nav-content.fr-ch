---
title: "Procédure : imprimer des informations sur la configuration comptabilité"
description: "Avant d'utiliser [!INCLUDE[navnow](../../includes/navnow_md.md)] dans le cadre de vos activités quotidiennes, vous pouvez exécuter l'état **Informations sur la configuration comptabilité** pour afficher les données principales que vous avez configurées."
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
ms.openlocfilehash: 45ef0a2c3e32e1a30688a51b9565928d2163f712
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-print-general-ledger-setup-information"></a>Procédure : imprimer des informations sur la configuration comptabilité
Avant d'utiliser [!INCLUDE[navnow](../../includes/navnow_md.md)] dans le cadre de vos activités quotidiennes, vous pouvez exécuter l'état **Informations sur la configuration comptabilité** pour afficher les données principales que vous avez configurées. Vous pouvez consulter ces données principales afin de disposer d'une base de comparaison, puis vérifier que vous avez configuré des groupes comptabilisation correctement, par exemple.  

## <a name="to-print-general-ledger-setup-information"></a>Pour imprimer des informations sur la configuration comptabilité  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Informations sur la configuration comptabilité**, puis sélectionnez le lien associé.  
2.  Sous le raccourci **Options**, dans le champ **Informations de configuration**, sélectionnez la zone données principales comme décrit dans le tableau suivant.  

    |Option|Description|  
    |-------------------------------------|---------------------------------------|  
    |**Configuration comptabilité - Données société - Consolidation**|Affiche des tables pour les paramètres comptabilité, les informations société et les centres de profit.|  
    |**Groupes comptabilisation**|Affiche des tables groupe comptabilisation client, des tables groupes comptabilisation fournisseur, des tables groupe comptabilisation stock et des tables groupe comptabilisation banque.|  
    |**Matrice comptabilisation**|Affiche des tables groupe comptabilisation marché, des tables groupes comptabilisation produit, des tables groupe comptabilisation général.|  
    |**Paramètres VAT**|Affiche des tables groupe comptabilisation marché TVA, des tables groupes comptabilisation produit TVA, des tables paramètres comptabilisation TVA.|  
    |**Code journal - Code motif**|Affiche des tables source, des tables paramètres codes journaux et des tables codes motif.|  
    |**Contrôle des souches de numéros**|Sélectionner pour obtenir un aperçu de l'utilisation des souches de numéros pour que vous puissiez identifier les souches de numéros qui posent problème pour l'exportation de données dans le cadre de la GDPdU (Grundsätze zum Datenzugriff und zur Prüfbarkeit digitaler Unterlagen). L'état affichera les souches de numéros présentant l'un des problèmes suivants :<br /><br /> -   La souche de numéros autorise les numéros de document manuels.<br />-   La souche de numéros n'est pas chronologique.<br />-   La souche de numéros est utilisée dans plusieurs tables/champs.|  

3.  Choisissez le bouton **Imprimer** pour imprimer l'état ou le bouton **Aperçu** pour l'afficher à l'écran.  

## <a name="see-also"></a>Voir aussi  
[Configuration de Finance](../../finance-setup-finance.md)

