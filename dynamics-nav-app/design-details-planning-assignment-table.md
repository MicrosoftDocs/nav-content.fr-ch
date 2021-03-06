---
title: "Détails de conception - Tableau d'affectation de planification"
description: "Cette rubrique donne un aperçu de ce qui se produit lorsque vous modifiez la planification d'un article."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4de661000de46293eaeec22ce6a6243f0efaa630
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-planning-assignment-table"></a>Détails de conception : tableau d'affectation de planification
Tous les articles doivent être planifiés. Cependant, il n'existe aucune raison de calculer une planification pour un article à moins qu'il n'y ait eu une modification de la configuration de l'offre ou de la demande depuis la dernière fois qu'un plan a été calculé.  
  
Si l'utilisateur a saisi une commande vente ou en a modifié une existante, il existe un motif de recalculer la planification. Les autres motifs sont notamment une modification de prévision ou la quantité de stock de sécurité souhaitée. La modification de nomenclatures lorsque vous ajoutez ou supprimez un composant indique très probablement une modification, mais pour le composant uniquement.  
  
Pour plusieurs magasins, l'affectation se fait au niveau de l'article par combinaison de magasins. Si, par exemple, une commande vente a été créée à un seul magasin, le programme affecte l'article à ce magasin spécifique pour la planification.  
  
La raison de la sélection d'articles pour la planification est une question de performances système. Si aucune modification du motif demande-approvisionnement d'un article n'a été apportée, le système de planification ne propose aucune action à effectuer. Sans l'affectation de planification, le système devrait effectuer les calculs pour tous les articles afin de déterminer quoi planifier, et cela purgerait des ressources du système.  
  
La table **Affectation planning** contrôle les événements d'offre et de demande et affecte les articles appropriés de façon à les planifier. Les événements suivants sont contrôlés :  
  
* Nouveau/nouvelle commande vente, prévision, composant, commande achat, ordre de fabrication, ordre d'assemblage ou ordre de transfert.  
* Modification d'un article, d'une quantité, d'un magasin, d'une variante, ou d'une date sur une commande vente, d'une prévision, d'un composant, d'une commande achat, d'un ordre de fabrication, d'un ordre d'assemblage ou d'un ordre de transfert.  
* Annulation d'une commande vente, d'une prévision, d'un composant, d'une commande achat, d'un ordre de fabrication, d'un ordre d'assemblage ou d'un ordre de transfert.  
* Consommation d'autres articles que planifiés.  
* Production d'autres articles que planifiés.  
* Modifications non planifiées dans le stock.  
  
Pour ces déplacements directs de demande-approvisionnement, le système de chaînage et de messages d'action gère la table affectation de planification et indique un motif de planification comme message d'action.  
  
Les modifications suivantes dans les données de base peuvent également provoquer un déséquilibre du planning :  
  
* Modification du statut sur Validée dans l'en-tête de la nomenclature de production (pour tous les articles avec cet en-tête).  
* Ligne supprimée (article enfant).  
* Modification du statut sur Validée dans l'en-tête gamme (pour tous les articles avec cette gamme).  
* Modifications des champs suivants de la fiche article.  
* Quantité du stock de sécurité ou délai de sécurité.  
* Délai de réapprovisionnement.  
* Point de commande.  
* N° de nomenclature de production (et tous les enfants de l'ancienne référence de nomenclature).  
* N° gamme  
* Méthode de réapprovisionnement.  
  
Dans ces cas, une nouvelle fonction, Gestion d'affectation de planification, met à jour la table et indique le motif de planification Solde période.  
  
Les modifications suivantes n'entraînent pas une affectation de planification :  
  
* Calendriers  
* Autres paramètres de planification sur la fiche article  
  
Lors du calcul d'un MPS ou d'un MRP, les restrictions suivantes s'appliquent :  
  
* PDP : Le système de planification vérifie que l'article indique une prévision de production ou une commande vente. Sinon, l'article n'est pas inclus dans le planning.  
* MRP : si le système de planification détecte que l'article est réapprovisionné par une ligne planning PDP ou une commande approvisionnement PDP, l'article sera laissé en dehors de la planification. Toutefois, toute demande des composants pertinents est incluse.  
  
## <a name="see-also"></a>Voir aussi  
[Détails de conception : équilibrage de la demande et de l'approvisionnement](design-details-balancing-demand-and-supply.md)   
[Détails de conception : gestion des méthodes de réapprovisionnement](design-details-handling-reordering-policies.md)   
[Détails de conception : transferts de planification](design-details-transfers-in-planning.md)   
[Détails de conception : paramètres de planification](design-details-planning-parameters.md)  

