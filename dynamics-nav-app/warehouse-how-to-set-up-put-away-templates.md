---
title: "Procédure : configurer des modèles rangement"
description: "A l'aide de la fonctionnalité de prélèvement et de rangement suggérés, l'emplacement le mieux approprié à vos articles à un moment donné est suggéré, en fonction du modèle rangement configuré pour l'entrepôt, des priorités affectées aux emplacements et des quantités minimale et maximale définies pour les emplacements associés."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: be51b4d1cfc4d2a54e5f44f6419ed4539c01e9df
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-put-away-templates"></a>Procédure : configurer des modèles rangement
A l'aide de la fonctionnalité de prélèvement et de rangement suggérés, l'emplacement le mieux approprié à vos articles à un moment donné est suggéré, en fonction du modèle rangement configuré pour l'entrepôt, des priorités affectées aux emplacements et des quantités minimale et maximale définies pour les emplacements associés.  

Vous pouvez configurer un certain nombre de modèles rangement et en sélectionner un pour gérer les rangements dans votre entrepôt. Vous pouvez également sélectionner un modèle rangement pour un article ou un point de stock disposant d'exigences spéciales en matière de rangement.  

## <a name="to-set-up-put-away-templates"></a>Pour configurer des modèles rangement  
1.  Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Modèles rangement**, puis sélectionnez le lien connexe.  
2.  Sélectionnez l'action **Nouveau**.  
3.  Entrez un code représentant l'identifiant unique du modèle que vous allez créer.  
4.  Saisissez éventuellement une brève description.  
5.  Renseignez la première ligne avec les exigences emplacement auxquelles vous souhaitez qu'il soit répondu d'abord lors de la proposition d'un rangement.  
6.  Renseignez la deuxième ligne avec les exigences emplacement auxquelles on doit répondre ensuite lors de la recherche d'un emplacement de rangement. La deuxième ligne est utilisée uniquement si un emplacement répondant aux exigences de la première ligne ne peut être trouvé.  
7.  Continuez à renseigner les lignes jusqu'à ce que vous ayez décrit tous les placements acceptables à utiliser au cours du rangement.  
8.  Sur la dernière ligne du modèle rangement, cochez la case **Rechercher empl. Dynamique**.  

Vous pouvez créer plusieurs modèles rangement et les appliquer comme vous le souhaitez. On se réfère d'abord au modèle rangement sélectionné éventuel pour l'article ou le point de stock. Si ces champs ne sont pas renseignés, alors le modèle rangement sélectionné pour l'entrepôt sur le raccourci **Config. emplacement** de la fiche magasin sera utilisé.  

## <a name="see-also"></a>Voir aussi  
[Gestion d'entrepôt](warehouse-manage-warehouse.md)  
[STOCKS ET EN-COURS](inventory-manage-inventory.md)  
[Configuration de la gestion des entrepôts](warehouse-setup-warehouse.md)     
[Gestion des assemblages](assembly-assemble-items.md)    
[Détails de conception : gestion d'entrepôt](design-details-warehouse-management.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

