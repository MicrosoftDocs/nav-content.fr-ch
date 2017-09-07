---
title: "Création de sociétés contact"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: a16e1748472805137d6b9a6d792e93470333f6ff
ms.contentlocale: fr-ch
ms.lasthandoff: 06/26/2017

---
# <a name="create-contact-companies"></a>Création de sociétés contact
Vous pouvez créer un contact pour chaque nouvelle société avec laquelle vous êtes en contact, par exemple un client, un fournisseur, un prospect, une banque, un cabinet d'avocats, un consultant, et ainsi de suite.

Il existe deux méthodes permettant de créer un contact : à partir de zéro ou à partir d'un client, d'un fournisseur ou d'un compte bancaire existant.

Avant de créer un contact, vous pouvez vérifier les paramètres dans la fenêtre **Paramètres Marketing**. Pour plus d'informations, reportez-vous à [Configuration de la gestion du marketing et des contacts](marketing-setup-marketing.md).

## <a name="create-a-company-contact-from-scratch"></a>Créer un contact société à partir de zéro
1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, entrez **Contacts**, puis sélectionnez le lien connexe.
2. Sélectionnez l'action **Nouveau**.
3. Dans le champ **N°**, saisissez le numéro du contact.

  Si vous avez configuré une souche de numéros pour les contacts dans la fenêtre **Paramètres Marketing**, appuyez sur la touche Entrée pour sélectionner le numéro de contact suivant.
4. Définissez **Type** à **Société**.
5. Renseignez les autres champs selon vos besoins.

## <a name="create-a-company-contact-from-a-customer-vendor-or-bank-account"></a>Créer un contact société à partir d'un client, d'un fournisseur ou d'un compte bancaire
Si vous avez configuré plusieurs clients, fournisseurs et comptes bancaires, vous pouvez créer des contacts sur la base des données existantes. Lorsque vous créez un contact de cette façon, les informations de contact sont synchronisées avec les informations du client, du fournisseur ou du compte bancaire.

**Remarque** : avant de créer des sociétés contact de cette manière, vous devez spécifier un code relation d'affaires pour les clients, les fournisseurs, ainsi que des comptes bancaires dans la fenêtre **Paramètres marketing**. Si vous devez créer des contacts à partir de comptes bancaires, vous devez également spécifier des souches de numéros pour les comptes bancaires dans la fenêtre **Paramètres comptabilité**.

1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, entrez l'un des choix suivants, selon l'élément à partir duquel vous souhaitez créer des contacts, puis sélectionnez le lien connexe.
  * **Créer contacts à partir des clients**
  * **Créer contacts à partir des fournisseurs**
  * **Créer contacts à partir des cptes banc**
2. Dans la fenêtre de traitement par lots qui s'affiche, dans la section **Client**, **Fournisseur** ou **Compte bancaire**, définissez des filtres si vous souhaitez créer des contacts à partir de clients, de fournisseurs ou de comptes bancaires spécifiques.
3. Pour démarrer la création de contacts, cliquez sur le bouton **OK**.

  Les numéros de contact suivants de la souche de numéros sont affectés aux nouveaux contacts. La relation d'affaires des fournisseurs qui est spécifiée dans la fenêtre **Paramètres Marketing** est affectée aux contacts nouvellement créés.

**Conseil** :vous pouvez également créer un client, un fournisseur ou un compte bancaire à partir d'un contact. Pour plus d'informations, reportez-vous à [Créer un client, un fournisseur ou un compte bancaire à partir d'un contact](marketing-how-create-contacts-new-customers-vendors-bank-accounts.md).
##<a name="see-also"></a>Voir aussi
[Synchronisation des contacts avec les clients, les fournisseurs et les comptes bancaires](marketing-synchronize-contacts-customers-vendors-bank-accounts.md)  
[Affecter des relations d'affaires à un contact](marketing-business-relations.md#assign-business-relations-to-a-contact)  
[Affecter des secteurs d'activité à un contact](marketing-industry-groups.md#assign-industry-groups-to-a-contact)  
[Affecter des groupes de distribution à un contact](marketing-mailing-groups.md#assign-mailing-groups-to-a-contact)  
[Procédure : créer des personnes contact](marketing-create-contact-persons.md)  
