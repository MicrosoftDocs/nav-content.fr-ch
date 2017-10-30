---
title: "Paiements électroniques suisses avec DTA"
description: "Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], vous pouvez effectuer des paiements électroniques de factures à l'aide de la méthode de paiement électronique DTA (DatenTrägerAustausch). Les banques suisses utilisent la méthode de paiement électronique DTA pour régler efficacement les paiements à l'aide d'enregistrements de paiement standardisés. Cette méthode est basée sur des supports de données et un transfer de données. Ce service électronique vous permet de convertir des paiements électroniquement en format DTA puis de les soumettre à votre banque pour paiement."
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
ms.openlocfilehash: cc84201548ca2c1ff6be7963310ea83bc81de94d
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="swiss-electronic-payments-using-dta"></a>Paiements électroniques suisses avec DTA
Dans [!INCLUDE[navnow](../../includes/navnow_md.md)], vous pouvez effectuer des paiements électroniques de factures à l'aide de la méthode de paiement électronique DTA (DatenTrägerAustausch). Les banques suisses utilisent la méthode de paiement électronique DTA pour régler efficacement les paiements à l'aide d'enregistrements de paiement standardisés. Cette méthode est basée sur des supports de données et un transfer de données. Ce service électronique vous permet de convertir des paiements électroniquement en format DTA puis de les soumettre à votre banque pour paiement.  
  
> [!NOTE]  
>  Avant d'utiliser la méthode de paiement électronique DTA, vous devez définir les paramètres DTA pour effectuer des paiements électroniques dans les Paramètres DTA. Pour plus d'informations, voir la table Paramètres DTA.  
  
 Avec les paiements électroniques DTA, vous pouvez réaliser les opérations suivantes :  
  
-   Générer des paiements fournisseur en traitant le paiement DTA automatique. Pour plus d'informations, voir la rubrique [Procédure : Proposer paiement DTA pour les fournisseurs](how-to-suggest-dta-payment-for-vendors.md).  
  
-   Vérifier la liste des fournisseurs et des informations de paiement. Pour plus d'informations, voir la rubrique [Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md).  
  
-   Soumettre le fichier DTA à la banque électroniquement, où les paiements fournisseur sont libérés en quelques heures. Pour plus d'informations, voir la rubrique [Procédure : soumettre des paiements DTA](how-to-submit-dta-payments.md). Une fois cette opération effectuée, la feuille paiement peut être validée.  
  
 Dans la feuille paiement, il est possible que les paiements DTA soient suggérés sur la base des factures validées. Les paiements suggérés contiennent des informations sur le numéro de document externe et le fournisseur, et peuvent être modifiés. Pour plus d'informations, voir la rubrique [Procédure : Proposer paiement DTA pour les fournisseurs](how-to-suggest-dta-payment-for-vendors.md) et la fenêtre Feuille paiement DTA.  
  
 Lorsque vous souhaitez payer un fournisseur avec la méthode DTA, vous générez un fichier DTA qui contient des données issues de la ligne feuille paiement et la ligne feuille comptabilité. Éventuellement, le fichier DTA peut combiner plusieurs paiements au fournisseur. Le fichier DTA contient également le texte de validation.  
  
> [!NOTE]  
>  Si vous combinez des paiements au fournisseur, le texte de validation doit inclure les numéros document des factures. De même, si la longueur du numéro document est supérieure à 50 caractères, le mot « etc. » sera ajouté au champ.  
  
## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses](swiss-electronic-payments.md)   
 [Procédure : Proposer paiement DTA pour les fournisseurs](how-to-suggest-dta-payment-for-vendors.md)   
 [Procédure : vérifier une liste de fournisseurs pour paiements DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md)   
 [Procédure : soumettre des paiements DTA](how-to-submit-dta-payments.md)   
 [Procédure : exporter des paiements avec EZAG](how-to-export-payments-using-ezag.md)   
 [Paiements électroniques suisses avec BVR](swiss-electronic-payments-using-esr.md)   
 [Paiements électroniques suisses avec LSV+](swiss-electronic-payments-using-lsv-.md)   
 Feuille paiement   
 Paramètres DTA
