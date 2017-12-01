---
title: "Procédure : importer des numéros de clearing bancaire suisses"
description: "Les numéros de clearing bancaire sont des numéros uniques utilisés pour identifier chaque agence ou établissement bancaire dans le répertoire des banques. Cette information est requise pour le paiement électronique. Le fichier peut être téléchargé à partir du site Web [Clearing interbancaire SIX](http://go.microsoft.com/fwlink/?LinkId=145121)."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 3e4eaa4bfa9a50d0a1cacbc06a44c52ef36ffb25
ms.contentlocale: fr-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-import-swiss-bank-clearing-numbers"></a>Procédure : importer des numéros de clearing bancaire suisses
Les numéros de clearing bancaire sont des numéros uniques utilisés pour identifier chaque agence ou établissement bancaire dans le répertoire des banques. Cette information est requise pour le paiement électronique. Le fichier peut être téléchargé à partir du site Web [Clearing interbancaire SIX](http://go.microsoft.com/fwlink/?LinkId=145121).  

Vous pouvez importer le fichier des banques CB (le fichier officiel des numéros de clearing bancaire suisses) pour mettre à jour les numéros de clearing bancaire dans le répertoire des banques. Lorsque vous importez le fichier de numéros de clearing bancaire, les données sont importées dans la table **Répertoire de la banque** et les données existantes sont remplacées. Après avoir importé le fichier de numéros de clearing bancaire, vous pouvez définir le numéro de l'établissement bancaire mis à jour pour les clients et les fournisseurs. Pour plus d'informations, consultez les tables Compte bancaire client et Compte bancaire fournisseur.  

## <a name="to-import-swiss-bank-clearing-numbers"></a>Pour importer des numéros de clearing bancaire suisses  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Répertoire de la banque**, puis sélectionnez le lien associé.  
2.  Choisissez l'action **Lire DB Banques**.  
3.  Dans la fenêtre **Lire DB Banques**, sur le raccourci **Options**, sélectionnez le champ **Mettre automatiquement à jour les numéros de clearing** pour mettre automatiquement à ajour les numéros de clearing bancaire.  
4.  Choisissez le bouton **Imprimer** ou **Aperçu** pour importer les numéros de clearing bancaire, puis, dans la fenêtre **Ouvrir**, repérez le fichier que vous avez téléchargé à partir du site web de clearing interbancaire SIX.
5. Choisissez le bouton **Ouvrir**.  

    Si vous choisissez le bouton **Imprimer**, le contenu du fichier sera imprimé. Si vous choisissez le bouton **Aperçu**, la table **Répertoire de la banque** sera mise à jour et un état présentant les numéros de clearing modifiés s'affichera.  

La procédure suivante décrit comment définir des numéros d'établissement bancaire pour les comptes bancaires clients, mais vous pouvez également la suivre pour définir des numéros d'établissement bancaire pour les comptes bancaires fournisseur.  

## <a name="to-define-bank-branch-numbers-for-customer-bank-accounts"></a>Pour définir des numéros d'établissement bancaire pour les comptes bancaires clients  

1.  Choisissez l'icône ![Page ou état pour la recherche](../../media/ui-search/search_small.png "icône Page ou état pour la recherche"), entrez **Clients**, puis sélectionnez le lien associé.  
2.  Sélectionnez le client pour lequel vous souhaitez créer des informations de compte bancaire, puis choisissez l'action **Comptes bancaires**.  
3.  Dans la fenêtre **Liste comptes bancaires client**, sélectionnez le compte bancaire requis, puis choisissez l'action **Modifier**.  
4.  Sous le raccourci **Général**, dans le champ **Code établissement**, sélectionnez le numéro de l'agence ou de l'établissement bancaire.  
5.  Cliquez sur le bouton **OK**.  

## <a name="see-also"></a>Voir aussi  
 [Paiements électroniques suisses](swiss-electronic-payments.md)   
 [Procédure : paramétrer des comptes bancaires](../../bank-how-setup-bank-accounts.md)

