---
title: "Procédure : ajuster des taux de change"
description: "Si vous avez des ventes imposables dans une devise étrangère, vous devez utiliser le taux officiel pour la conversion de devise TVA comme défini par l'Administration fédérale des contributions."
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
ms.openlocfilehash: 5aa71c751b9ebbf81cfea8582488aec9bb467e62
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-adjust-exchange-rates"></a>Procédure : ajuster des taux de change
Si vous avez des ventes imposables dans une devise étrangère, vous devez utiliser le taux officiel pour la conversion de devise TVA comme défini par l'Administration fédérale des contributions.  
  
 Si ces taux ne correspondent pas aux taux de devise utilisés dans les factures achat ou vente, vous devrez ajuster les taux de TVA à l'aide d'un traitement par lots ultérieurement. Ces ajustements ne peuvent être exécutés qu'avec un taux de TVA autorisé.  
  
 Vous pouvez exécuter ce traitement par lots aussi souvent que vous le souhaitez. Toutefois, veillez à toujours l'exécuter avant de créer une déclaration de TVA.  
  
> [!NOTE]  
>  Lorsque vous utilisez une devise report, assurez-vous que le champ **Ajustement tx de change TVA** dans la fenêtre **Paramètres comptabilité** est défini sur **Aucun ajustement**.  
  
 Pour plus d'informations sur la TVA et les devises étrangères, consultez le site web de [l'ESTV](http://go.microsoft.com/fwlink/?LinkId=285999).  
  
### <a name="to-adjust-an-exchange-rate"></a>Pour ajuster un taux de change  
  
1.  Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Devises**, puis sélectionnez le lien associé.  
  
2.  Sous l'onglet **Accueil**, dans le groupe **Taux de change**, choisissez **Taux change**.  
  
3.  Dans la fenêtre **Taux de change devise**, entrez le taux de TVA officiel par période pour chaque devise dans les champs **Montant taux chge TVA** et **Montant taux change lié ajust.**.  
  
4.  Cliquez sur le bouton **OK**.  
  
5.  Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Ajuster taux change**, puis sélectionnez le lien associé.  
  
6.  Sous le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.   
  
    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**Date de début**|Entrez une date pour spécifier le début de la période pour laquelle des écritures seront ajustées.|  
    |**Date de fin**|Entrez la dernière date pour laquelle des écritures seront ajustées. Cette date est généralement la même que la date comptabilisation figurant dans le champ **Date comptabilisation**.|  
    |**Ajustement du cours TVA**|Spécifiez si vous souhaitez ajuster le taux de change TVA.|  
  
7.  Choisissez le bouton **Imprimer** pour démarrer le traitement par lots. Ce traitement par lots contrôle si des écritures TVA doivent être ajustées et prépare une écriture d'ajustement pour chacune de ces écritures pour les comptes Ajustements taux change réalisés/non réalisés. Les écritures TVA existantes sont également corrigées.  
  
## <a name="see-also"></a>Voir aussi  
 [Taxe sur la valeur ajoutée suisse](swiss-value-added-tax.md)   
 [Taux de TVA pour la Suisse](vat-rates-for-switzerland.md)   
 Paramètres compta. TVA   
 Paramètres comptabilité   
 Ecriture TVA   
 [Ajuster taux de change](-$-b_595-adjust-exchange-rates-$.md)   
 Taux de change devise
