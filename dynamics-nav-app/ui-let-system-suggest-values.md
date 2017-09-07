---
title: "Laisser Dynamics NAV suggérer des valeurs"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 889d0aa5da36d7a4b7e2be1d796ac95e74aaaaf6
ms.contentlocale: fr-ch
ms.lasthandoff: 06/26/2017

---

# <a name="letting-dynamics-nav-suggest-values"></a>Laisser Dynamics NAV suggérer des valeurs
Dynamics NAV peut vous aider à effectuer ces tâches plus rapidement et avec davantage de précision en pré-remplissant les champs ou en complétant les lignes avec des données que vous auriez, sinon, à calculer et à saisir vous-même. Bien qu'une telle saisie de données automatisée soit toujours correcte, vous pouvez la modifier par la suite si vous le souhaitez.

La fonctionnalité qui saisit les valeurs de champ pour vous est en général proposée pour les tâches qui demandent la saisie de volumes importants de données transactionnelles et pour lesquelles vous souhaitez éviter les erreurs et gagner du temps. Cette rubrique contient une sélection de ces fonctionnalités. Davantage de sections seront ajoutées dans les prochaines mises à jour de Dynamics NAV.

## <a name="the-suggest-balancing-amount-check-box-in-the-general-journal-batches-window"></a>La case à cocher **Suggérer le montant contrepartie** dans la fenêtre **Noms feuille comptabilité**
Lorsque, par exemple, vous saisissez des lignes feuille comptabilité pour plusieurs frais qui doivent tous être validés dans le même compte bancaire, chaque fois que vous saisissez une nouvelle ligne feuille pour les frais, vous pouvez faire en sorte que le champ **Montant** de la ligne compte bancaire soit automatiquement mis à jour avec le montant qui équilibre les frais. Pour plus d'informations sur l'utilisation des feuilles comptabilité, reportez-vous à [Utilisation des feuilles comptabilité](ui-work-general-journals.md).

### <a name="to-have-the-amount-field-on-balancing-general-journal-lines-filled-automatically"></a>Pour que le champ **Montant** sur les lignes feuille comptabilité contrepartie soit renseigné automatiquement
1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, entrez **Feuilles comptabilité**, puis sélectionnez le lien connexe.
2. Sur la ligne du nom de votre feuille comptabilité favorite, cochez la case **Suggérer le montant contrepartie**.
3. Ouvrez la feuille comptabilité commencez à enregistrer et valider des transactions en utilisant la fonctionnalité décrite pour la saisie automatique d'une valeur de champ.       

Pour plus d'informations sur la procédure permettant de configurer un nom de feuille comptabilité personnel, par exemple pour la gestion des frais, reportez-vous à [Utilisation des feuilles comptabilité](ui-work-general-journals.md).

## <a name="the-automatically-fill-date-received-field-in-the-payment-registration-window"></a>Le champ **Renseigner automatiquement la date de réception** de la fenêtre **Enregistrement de paiement**
La fenêtre **Enregistrement de paiement** affiche les arriérés de paiement entrants sous la forme de lignes représentant les documents vente pour lesquels un montant doit être payé. Pour plus d'informations sur le lettrage des paiements client, reportez-vous à [Procédure : rapprocher les paiements client manuellement à partir de la liste des documents vente échus](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md).

Vos tâches principales dans cette fenêtre consistent à cocher la case **Paiement effectué** et à renseigner le champ **Date de réception**. Vous pouvez définir Dynamics NAV afin de saisir automatiquement la date de travail dans le champ **Date de réception** lorsque vous cochez la case **Paiement effectué**.

### <a name="to-have-the-date-received-field-in-the-payment-registration-window-filled-automatically"></a>Pour que le champ **Date de réception** de la fenêtre **Enregistrement de paiement** soit automatiquement renseigné
1. Dans le coin supérieur droit, sélectionnez l'icône **Page ou état pour la recherche**, entrez **Paramétrage de l'enregistrement de paiement**, puis sélectionnez le lien connexe.
2. Cochez la case **Renseigner automatiquement la date de réception**.
3. Ouvrez la fenêtre **Enregistrement de paiement** et commencer à traiter les paiements client entrants à l'aide de la fonctionnalité décrite pour la saisie automatique d'une valeur de champ.

## <a name="see-also"></a>Voir aussi
[Utiliser Dynamics NAV](ui-work-product.md)  
[Finance](Finance.md)
