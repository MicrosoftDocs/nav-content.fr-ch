---
title: "Procédure : exporter des paiements avec OPAE"
description: "Vous pouvez générer un fichier pour paiement électronique à l'aide de la méthode OPAE (ordre de paiement électronique) et l'exporter pour permettre à la banque de l'utiliser pour les paiements."
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
ms.openlocfilehash: b9ea004d65e3d288c1c1db9771f4ed486c9f232b
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-payments-using-ezag"></a>Procédure : exporter des paiements avec OPAE
Vous pouvez générer un fichier pour paiement électronique à l'aide de la méthode OPAE (ordre de paiement électronique) et l'exporter pour permettre à la banque de l'utiliser pour les paiements.  
  
### <a name="to-export-payments-using-ezag"></a>Pour exporter des paiements avec OPAE  
  
1.  Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles paiement**, puis sélectionnez le lien associé.  
  
2.  Dans le champ **Nom de la feuille**, sélectionnez le nom de la feuille.  
  
3.  Sous l'onglet **Accueil**, dans le groupe **Traiter**, choisissez **Écrire fichier OPAE**.  
  
4.  Dans le traitement par lots **Fichier OPAE**, sur le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.  
  
    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**Banque à débiter**|Spécifiez le code de la banque à débiter.|  
    |**Totaliser par fournisseur**|Spécifiez si les lignes paiement présentant les mêmes fournisseur, devise, banque et banque à débiter dans le fichier OPAE généré seront combinées.|  
    |**Expédition avec disque**|Spécifiez si le fichier OPAE sera enregistré sur un disque que vous pourrez remettre à la banque.|  
  
5.  Cliquez sur le bouton **OK**. Le fichier OPAE est généré.  
  
## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md)   
 [Procédure : Proposer paiement DTA pour les fournisseurs](how-to-suggest-dta-payment-for-vendors.md)   
 [Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md)   
 [Procédure : soumettre des paiements DTA](how-to-submit-dta-payments.md)   
 Paramètres DTA   
 Feuille paiement
