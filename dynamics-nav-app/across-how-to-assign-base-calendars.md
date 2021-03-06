---
title: Comment configurer des calendriers principaux
description: "Vous pouvez affecter un calendrier principal à votre société et à ses partenaires commerciaux, tels que ses clients, ses fournisseurs, ou ses magasins. Les dates de livraison et de réception sur les lignes commande vente, commande achat, ordre de transfert, et ordre de fabrication sont calculées en fonction des jours ouvrés définis dans le calendrier."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 09cf0a5da9409a217b9394763acce0eb2acec99d
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-base-calendars"></a>Comment configurer des calendriers principaux
Vous pouvez affecter un calendrier principal à votre société et à ses partenaires commerciaux, tels que ses clients, ses fournisseurs, ou ses magasins. Les dates de livraison et de réception sur les lignes commande vente, commande achat, ordre de transfert, et ordre de fabrication sont calculées en fonction des jours ouvrés définis dans le calendrier. Lorsque vous paramétrez un nouveau calendrier principal, votre tâche consiste essentiellement à indiquer et à définir les jours chômés à appliquer.  

## <a name="to-set-up-a-base-calendar"></a>Pour configurer un calendrier principal  
1.  Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Calendrier principal**, puis sélectionnez le lien connexe.  
2.  Sélectionnez l'action **Nouveau**.  
3.  Complétez le champ **Code**.  
4. Choisissez l'action **Gérer modifications calendrier principal**.
5. Dans la fenêtre **Modifications calendrier principal**, utilisez le champ **Système abonnement** pour sélectionner une date ou un jour spécifique comme jour chômé récurrent. Vous pouvez choisir l'option **Abonnement annuel** ou **Abonnement hebdomadaire**.  

    Si vous sélectionnez **Abonnement annuel**, vous devez également entrer la date appropriée dans le champ **Date**.  

    Si vous sélectionnez **Abonnement hebdomadaire**, vous devez également sélectionner le jour de la semaine approprié dans le champ **Jour**. Si vous ne remplissez pas ce champ, vous devez compléter le champ **Date**. Le champ **Jour** est renseigné automatiquement.  

Lorsque vous créez une écriture, le champ **Jour chômé** est sélectionné. Vous pouvez choisir de décocher la case pour la définir comme un jour ouvré.  
 Lorsque vous affichez de nouveau la fiche calendrier principal, vous observerez que les écritures jour chômé que vous avez créées ont été mises à jour. Ces écritures s'affichent désormais en rouge et le champ **Jour chômé** est sélectionné.  

> [!NOTE]  
>  Lorsque vous paramétrez un nouveau calendrier principal, vous pouvez sélectionner des lignes dans un calendrier et les copier. Pour cela, utilisez la fenêtre **Modifications calendrier principal** correspondante.  

> [!IMPORTANT]  
>  Le calendrier principal défini pour le fournisseur ou le magasin affecte uniquement la manière dont les dates sont calculées et arrondies en jours ouvrés.
Spécifie une formule date pour le délai nécessaire au réapprovisionnement de l'article. Permet de calculer le champ **Date planifiée de réception**, si calcul en aval, et le champ **Date commande**, si calcul en amont. Reportez-vous à la section « Délai de réappro ».

## <a name="lead-time-calculation"></a>Délai de réappro.
Le calendrier principal défini pour le fournisseur ou le magasin affecte uniquement la manière dont les dates sont calculées et arrondies en jours ouvrés. En conséquence, les deux champs date sur les lignes commande achat sont calculés comme suit sous différentes conditions.

|Direction de calcul|Calendrier fournisseur défini|Calendrier fournisseur non défini|
|---------------------|-----------------------|---------------------------|
|Aval|date réception prévue = date commande + délai fournisseur (par calendrier fournisseur et arrondie au jour ouvré suivant dans le calendrier fournisseur, puis dans le calendrier du magasin)|date réception prévue = date commande + délai fournisseur (par calendrier de magasin)|
|Amont|date commande = date réception prévue - délai fournisseur (par calendrier fournisseur et arrondie au jour ouvré précédent dans le calendrier fournisseur, puis dans le calendrier du magasin)|date commande = date réception prévue - délai fournisseur (par calendrier de magasin)|

> [!NOTE]
> Outre le calcul du délai qui affecte la date de réception prévue et la date de commande, comme illustré dans la table ci-dessus, le délai d'activité entrepôt et le délai de sécurité peuvent être ajoutés à des formules pour constituer la valeur du champ **Date réception prévue** comme suit : Date planifiée de réception + Délai de sécurité + Délai enlogement = Date réception prévue.

> [!Important]
> Si votre magasin utilise un calendrier sensiblement différent de celui de vos fournisseurs, il est important de créer des calendriers spécifiques pour ces fournisseurs, pour calculer les délais fournisseur optimaux. Pour plus d'informations sur le paramétrage des calendriers fournisseur, voir la section « Pour affecter un calendrier principal ».

La valeur du champ **Délai de réappro.** est copiée à partir de la fiche article ou de la fiche point de stock, si le délai est défini pour l'article, ou dans la fenêtre **Catalogue fournisseur articles**, si le délai est défini pour le fournisseur.

## <a name="to-customize-a-calendar"></a>Pour personnaliser un calendrier
Lorsque vous personnalisez un calendrier principal pour votre société ou pour l'un de ses partenaires commerciaux, votre tâche consiste essentiellement à modifier le statut des jours ouvrés et chômés.

Par exemple, bien qu'un calendrier principal définisse en général tous les samedis comme des jours chômés, le calendrier personnalisé d'un magasin peut indiquer tous les samedis des mois de novembre et décembre, jusqu'aux vacances de Noël, comme des jours ouvrés.

La procédure suivante illustre l'exemple d'un magasin. Remarquez que, à ce stade, vous avez déjà affecté un calendrier principal au magasin.

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), saisissez **Magasins**, puis sélectionnez le lien connexe.
2. Ouvrez le magasin que vous voulez mettre à jour, puis sélectionnez le champ **Calendrier personnalisé**. Notez qu'un calendrier doit être sélectionné dans le champ **Code calendrier principal**.
3. Dans la fenêtre **Écritures calendrier personnalisé** qui s'ouvre, choisissez l'action **Conserver modifications calendrier personnalisé**.
4. Dans la fenêtre **Modifications calendrier personnalisé**, ajoutez des lignes pour les écritures calendrier personnalisé.

    Lorsque vous entrez une ligne, la case à cocher **Jour chômé** est activé. Vous pouvez désactiver cette case à cocher pour passer au statut Jour ouvré.

    Le champ **Système abonnement** permet de définir une date ou un jour spécifique comme jour chômé récurrent. Vous pouvez choisir l'option **Récurrence annuelle** ou **Récurrence hebdomadaire**.

    Si vous sélectionnez **Abonnement annuel**, vous devez également entrer la date appropriée dans le champ **Date**. Si vous sélectionnez **Abonnement hebdomadaire**, vous devez également sélectionner le jour de la semaine approprié dans le champ **Jour**. Si vous ne remplissez pas ce champ, vous devez compléter le champ **Date**. Le champ **Jour** est renseigné automatiquement. Cette opération se révèle utile si vous souhaitez marquer une date comme un jour chômé ou ouvré.

5. Cliquez sur le bouton **OK**.

Dans la fenêtre **Écritures calendrier personnalisé**, vous constaterez que les écritures de date sont mises à jour conformément aux modifications apportées.

Sur la fiche Magasin, le champ **Calendrier personnalisé** affiche **Oui**, indiquant ainsi que le calendrier personnalisé a été configuré.

> [!Important]
> Si vous ne renseignez pas le champ **Code magasin** d'une ligne commande, le calendrier de votre société est utilisé.


Si vous ne renseignez pas le champ **Code transporteur** de la ligne commande, le calendrier de votre société est utilisé.

> [!NOTE]  
> Si vous modifiez un calendrier principal auquel sont associés des calendriers personnalisés ayant fait l'objet de modifications, tous les calendriers personnalisés existants sont automatiquement mis à jour.

## <a name="to-assign-a-base-calendar"></a>Pour affecter un calendrier principal  
La procédure suivante planifie les dates de livraison sur les lignes commande vente pour un client comme exemple.

Les calendriers principaux sont affectés à votre propre société, à vos clients, fournisseurs, magasins et transporteurs comme suit :  

-   Sur les fiches **Informations société** et **Client**, le calendrier principal est affecté sur le raccourci **Expédition** .  
-   Sur la fiche **Fournisseur**, le calendrier principal est affecté sur le raccourci **Réception**.  
-   Sur la fiche **Magasin**, le calendrier principal est affecté sur le raccourci **Entrepôt**.  
-   Dans la fenêtre **Transporteurs** , le calendrier principal est affecté dans la fenêtre **Prestations transporteur**.  

1.  Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Clients**, puis sélectionnez le lien connexe.  
2.  Ouvrez la fiche **Client** pour laquelle vous allez affecter un calendrier principal.  
3.  Sur le raccourci **Expédition**, dans le champ **Code calendrier principal**, sélectionnez le calendrier principal à affecter.  

> [!IMPORTANT]  
>  -   Si vous n'affectez aucun calendrier principal aux sociétés, toutes les dates sont calculées comme des jours ouvrés.  
> -   Si vous n'indiquez pas le magasin sur une ligne commande, toutes les dates sont calculées comme des jours ouvrés.  
> -   Le calendrier principal défini pour le fournisseur ou le magasin affecte uniquement la manière dont les dates sont calculées et arrondies en jours ouvrés.

> [!NOTE]  
>  Pour créer des écritures calendrier personnalisé, vous devez d'abord affecter un calendrier principal à la société.  

## <a name="see-also"></a>Voir aussi
[Achats](purchasing-manage-purchasing.md)  
[Production](production-manage-manufacturing.md)    
[STOCKS ET EN-COURS](inventory-manage-inventory.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

