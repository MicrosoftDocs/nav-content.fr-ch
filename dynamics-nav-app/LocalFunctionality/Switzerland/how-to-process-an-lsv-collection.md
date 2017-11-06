---
title: "Procédure : traiter un recouvrement LSV"
description: "Vous pouvez utiliser les **feuilles LSV** pour créer et traiter les paiements des clients LSV+ (Lastschrift Verfahren). Vous pouvez enregistrer ces paiements dans la feuille règlement, créer un fichier LSV, puis imprimer l'ordre de recouvrement."
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
ms.openlocfilehash: a7503fec71d315d3a2bf4e9e1e3a734209990e14
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-process-an-lsv-collection"></a>Procédure : traiter un recouvrement LSV
Vous pouvez utiliser les **feuilles LSV** pour créer et traiter les paiements des clients LSV+ (Lastschrift Verfahren). Vous pouvez enregistrer ces paiements dans la feuille règlement, créer un fichier LSV, puis imprimer l'ordre de recouvrement. Pour plus d'informations, consultez la fenêtre Feuille règlement et [Procédure : exporter des paiements avec LSV](how-to-export-payments-using-lsv.md).  

Lorsque vous exécutez le traitement par lots **Proposition de recouvrement LSV**, chaque recouvrement proposé est enregistré sur une ligne feuille LSV, et les factures ouvertes sont transférées dans les feuilles LSV. Pour plus d'informations, voir la table Feuille LSV.  

Vous pouvez afficher, modifier ou supprimer les lignes paiement proposées. Si vous corrigez le montant proposé, la différence est marquée comme remise. Vous pouvez exécuter le traitement par lots plusieurs fois pour différents groupes de clients. Les lignes proposition peuvent être placées dans la même feuille.  

## <a name="to-create-an-lsv-collection"></a>Pour créer un recouvrement LSV  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Liste feuilles LSV**, puis sélectionnez le lien associé.  
2.  Choisissez l'action **Nouveau**.  
3.  Dans la fenêtre **Liste feuilles LSV**, complétez les champs requis comme décrit dans le tableau suivant.  

    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**Code banque LSV**|Sélectionnez le code banque LSV de la banque qui exécutera le recouvrement.|  
    |**Description de feuille LSV**|Entrez une description pour l'écriture.|

4.  Sélectionnez l'écriture feuille LSV requise, puis choisissez l'action **Proposition de recouvrement LSV** pour créer les paiements dont le recouvrement se fera automatiquement par LSV+.  
5.  Dans la fenêtre **Proposition de recouvrement LSV**, sur le raccourci **Options**, complétez les champs comme décrit dans le tableau suivant.  

    |Champ|Description|  
    |---------------------------------|---------------------------------------|  
    |**N°**|Entrez le numéro de la feuille LSV.|  
    |**Date d'échéance début**|Spécifiez la date d'échéance de début des écritures ouvertes à proposer pour le recouvrement.|  
    |**Date d'échéance fin**|Spécifiez la date d'échéance de fin des écritures ouvertes à proposer pour le recouvrement.|  
    |**Date de recouvrement**|Spécifiez la date de clôture du recouvrement. L'ordre LSV+ doit être soumis au moins trois jours bancaires avant la date du recouvrement.|  

6.  Cliquez sur le bouton **OK**.  

Toutes les lignes associées sont transférées à la feuille LSV. Après le traitement du recouvrement LSV, vous pouvez afficher, vérifier ou modifier les paiements proposés dans la fenêtre **Feuille LSV**. Pour plus d'informations, voir la table Ligne feuille LSV.  

## <a name="to-manage-suggested-payments"></a>Pour gérer les paiements proposés  

1.  Dans la fenêtre **Liste feuilles LSV**, sélectionnez l'écriture feuille requise, puis choisissez l'action **Ligne feuille LSV**.  

    Vous pouvez afficher et modifier les paiements proposés dans cette fenêtre. Vous pouvez entrer les paiements requis manuellement. Pour les nouvelles lignes feuille, le champ **Statut LSV** est défini sur **Ouvert** pour indiquer que la facture est impayée.  

3.  Cliquez sur le bouton **OK**.  

## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Procédure : clôturer un recouvrement LSV](how-to-close-an-lsv-collection.md)   
 [Procédure : valider des paiements LSV+](how-to-post-lsv-payments.md)   
 [Procédure : exporter des paiements avec LSV](how-to-export-payments-using-lsv.md)

