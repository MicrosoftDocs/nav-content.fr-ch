---
title: "Procédure : importer des paiements BVR"
description: "Après avoir reçu le paiement d'un client, vous recevez un fichier qui contient des informations sur les factures payées. Vous pouvez recevoir ce fichier de votre banque par voie électronique ou par e-mail."
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
ms.openlocfilehash: c69d1f8574a4d890904f2c5ee00983186d070d17
ms.contentlocale: fr-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-import-esr-payments"></a>Procédure : importer des paiements BVR
Après avoir reçu le paiement d'un client, vous recevez un fichier qui contient des informations sur les factures payées. Vous pouvez recevoir ce fichier de votre banque par voie électronique ou par e-mail.  

Vous pouvez importer les données de facture BVR (bulletin de versement avec numéro de référence) à partir du fichier, imprimer les données à l'aide de l'état BVR facture vente ou l'état coupon BVR vente, et vérifier avant validation. Pour plus d'informations, voir la rubrique [Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md).  

## <a name="to-import-esr-payments"></a>Pour importer des paiements BVR  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Feuilles règlement**, puis sélectionnez le lien associé.  
2.  Dans le champ **Nom de la feuille**, sélectionnez le nom de la feuille requis.  

    > [!NOTE]  
    >  La feuille doit être vide pour que vous puissiez importer le fichier BVR. Vous ne pouvez pas importer plusieurs fichiers BVR dans la même feuille règlement.  

3.  Choisissez l'action **Lire fichier BVR**.  

    > [!NOTE]  
    >  Si vous avez défini plusieurs banques BVR, un message d'avertissement vous demande de choisir la banque adéquate. Pour plus d'informations, voir la table Paramètres BVR.  

4.  Cliquez sur le bouton **Oui**, puis le bouton **OK**.  

Les informations sur les paiements sont importés dans les lignes feuille. Les paiements sont automatiquement appliqués aux factures respectives en fonction des numéros de référence BVR uniques.  

## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses avec BVR](swiss-electronic-payments-using-esr.md)   
 [Procédure : imprimer des factures BVR](how-to-print-esr-invoices.md)

