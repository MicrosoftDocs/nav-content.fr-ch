---
title: "Procédure : valider des paiements LSV+"
description: "Vous pouvez valider des paiements après avoir reçu une notification de paiement LSV+ (Lastschrift Verfahren) de la banque."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 628c8e23bbd6cdd1dd518d57eb05b1be6f1245fa
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-post-lsv-payments"></a>Procédure : valider des paiements LSV+
Vous pouvez valider des paiements après avoir reçu une notification de paiement LSV+ (Lastschrift Verfahren) de la banque.  

## <a name="to-post-lsv-payments"></a>Pour valider des paiements LSV+  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles règlement**, puis sélectionnez le lien associé.  
2.  Sélectionnez la feuille requise, puis choisissez l'action **Modifier feuille**.  

    > [!NOTE]  
    >  Vous pouvez sélectionner la feuille pour LSV où est défini le compte de contrepartie que vous souhaitez traiter. Vous ne pouvez pas importer plusieurs lignes feuille LSV dans la même feuille règlement. Pour plus d'informations, consultez la fenêtre Feuille règlement.  

3.  Choisissez l'action **Extraire de la feuille LSV**.  
4.  Dans la fenêtre **Liste feuilles LSV**, sélectionnez la ligne feuille LSV que vous souhaitez importer dans la feuille règlement.  

    > [!NOTE]  
    >  Vous ne pouvez importer que les lignes feuille dont le champ **Statut LSV** est défini sur **Fichier créé**.  

5.  Cliquez sur le bouton **OK**.  

    La ligne feuille LSV est importée dans la feuille règlement. La valeur du champ **Statut LSV** dans la fenêtre **Liste feuilles LSV** passe de **Fichier créé** à **Terminé**.  

    Vous pouvez vérifier les paiements importés et les comparer avec votre avis de paiement bancaire dans la fenêtre **Feuille règlement**. Vous pouvez également supprimer les lignes paiement qui n'ont pas pu être traitées par la banque, et pour lesquelles vous devez assurer un suivi avec le client manuellement.  

6.  Choisissez l'action **Valider**.  

## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Procédure : traiter un recouvrement LSV](how-to-process-an-lsv-collection.md)   
 [Procédure : clôturer un recouvrement LSV](how-to-close-an-lsv-collection.md)   
 [Procédure : exporter des paiements avec LSV](how-to-export-payments-using-lsv.md) 

