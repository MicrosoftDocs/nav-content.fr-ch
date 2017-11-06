---
title: "Procédure : soumettre des paiements DTA"
description: "Pour soumettre des paiements DTA (DatenTrägerAustausch) à votre banque pour paiement, vous devez exécuter certaines tâches."
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
ms.openlocfilehash: bf79d68ddb398672cccec48812266b8808e1e714
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-submit-dta-payments"></a>Procédure : soumettre des paiements DTA
Pour soumettre des paiements DTA (DatenTrägerAustausch) à votre banque pour paiement, vous devez exécuter les actions suivantes :  

- Générer un fichier DTA pour paiement électronique après impression de l'avis de paiement.  
- Imprimer l’ordre de paiement DTA.  

Avant de soumettre des paiements DTA, vous devez vérifier la liste des fournisseurs pour paiement DTA. Pour plus d'informations, voir la rubrique [Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md).  

Vous pouvez valider la feuille paiement une fois que les paiements bancaires sont finalisés. Dans la feuille paiement, il est possible que les paiements DTA soient suggérés sur la base des factures validées. Les paiements suggérés contiennent des informations sur le numéro de document externe et le fournisseur, et peuvent être modifiés. Pour plus d'informations, voir la rubrique [Procédure : Proposer paiement DTA pour les fournisseurs](how-to-suggest-dta-payment-for-vendors.md).  

## <a name="to-generate-a-dta-file"></a>Pour générer un fichier DTA  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles paiement**, puis sélectionnez le lien associé.  
2.  Dans le champ **Nom de la feuille**, sélectionnez le nom de la feuille requis.  
3.  Sélectionnez l'écriture paiement que vous souhaitez générer en tant que fichier DTA, puis choisissez l'action **Écrire fichier DTA**.  
4.  Dans le traitement par lots **Fichier DTA**, complétez les champs comme décrit dans le tableau suivant.  

    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**Banque DTA pour fichier**|Sélectionnez le code banque DTA à partir duquel les informations sur le nom de fichier et la copie de sauvegarde doivent être transférées. Ce champ utilise le nom de la banque principale comme valeur par défaut, mais vous pouvez modifier cette information au besoin.|  
    |**Totaliser par fournisseur**|Spécifiez si les lignes paiement présentant les mêmes fournisseur, devise, banque et banque à débiter seront combinées dans le fichier DTA généré.|  

5.  Cliquez sur le bouton **OK**. Le fichier DTA est généré dans le dossier prédéterminé.  

Après avoir généré le fichier DTA, vous pouvez imprimer l'ordre de paiement DTA et transférer le fichier et l'ordre de paiement à votre banque. L'ordre de paiement DTA répertorie tous les paiements fournisseur proposés dans une fenêtre **Feuille paiement** en fonction du code devise. Cet ordre est envoyé à la banque pour libérer le fichier DTA pour paiement.  

## <a name="to-print-a-dta-payment-order"></a>Pour imprimer un ordre de paiement DTA  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles paiement**, puis sélectionnez le lien associé.  
2.  Dans le champ **Nom de la feuille**, sélectionnez le nom de la feuille requis.  
3.  Sélectionnez l'écriture paiement requise, puis choisissez l'action **Ordre de paiement DTA**.  
4.  Dans le champ **Message**, entrez un message pour la banque, qui sera imprimé dans le bas de l'ordre de paiement.  
5.  Choisissez le bouton **Imprimer** pour imprimer l'ordre de paiement DTA ou le bouton **Aperçu** pour l'afficher à l'écran.  

    Vous devez soumettre l'ordre de paiement DTA et le fichier DTA à la banque, où les paiements aux fournisseurs sont libérés en quelques heures. Après que les paiements ont été traités par la banque, vous pouvez valider la feuille paiement.  

## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses avec DTA](swiss-electronic-payments-using-dta.md)   
 [Procédure : Proposer paiement DTA pour les fournisseurs](how-to-suggest-dta-payment-for-vendors.md)   
 [Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md)   
 [Procédure : exporter des paiements avec OPAE](how-to-export-payments-using-ezag.md)

