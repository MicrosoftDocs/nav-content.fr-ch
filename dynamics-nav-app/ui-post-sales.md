---
title: Familiarisation avec la validation des documents vente
description: "En savoir plus sur les différentes fonctions de validation pour valider des documents vente."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7261e8faca0c14330e66093f8db3d44935c4d141
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="posting-sales"></a>Validation des ventes
Dans le groupe **Validation** sur un document vente, vous pouvez faire votre choix parmi les fonctions de validation suivantes :

* **Valider**
* **Impression test**
* **Valider et envoyer**
* **Valider et Imprimer**
* **Valider et envoyer par e-mail**
* **Valider par lot**
* **Aperçu compta.**

Lorsque vous avez renseigné toutes les lignes et entré toutes les informations de la commande de vente, vous pouvez la valider. Cela crée une expédition et une facture.

Lorsqu’une commande vente est validée, le compte du client, les écritures comptables et les écritures comptables article sont mis à jour.

Pour chaque commande vente, une écriture vente est créée dans la table **Écriture comptable**. Une écriture est également créée dans le compte client de la table **Écriture comptable client** et une écriture comptable est créée dans le compte client approprié. De plus, la validation de la commande peut avoir pour résultat la création d’une écriture TVA et d’une écriture comptable pour le montant de la remise. La validation d’une écriture pour la remise dépend de la valeur du champ **Comptabilisation remises** de la fenêtre **Paramètres ventes**.

Pour chaque ligne commande vente, une écriture comptable article est créée dans la table **Écriture comptable article** (si les lignes vente contiennent des numéros des articles) ou une écriture comptable est créée dans la table **Écriture comptable** (si les lignes vente contiennent un compte général). En outre, les commandes vente sont toujours enregistrées dans les tables **En-tête expédition vente** et **En-tête facture vente**.

> [!IMPORTANT]  
>   Lorsque vous validez une commande, vous pouvez créer une expédition et une facture. Ceci peut être effectué de manière simultanée ou indépendante. Vous pouvez également créer une expédition partielle et une facture partielle en renseignant les champs **Qté à expédier** et **Qté à facturer** sur chaque ligne commande vente avant la validation. Notez que vous ne pouvez pas créer de facture pour un article qui n'est pas expédié. C'est-à-dire que, avant de pouvoir facturer, vous devez avoir validé une expédition, ou vous devez choisir de livrer et de facturer en même temps.

Lorsque la validation est terminée, les lignes vente validées sont supprimées de la commande. Un message vous indique lorsque la validation est terminée. Vous pouvez ensuite afficher les écritures validées dans les diverses fenêtres qui contiennent les écritures validées, telles que **Écritures comptables client**, **Écritures comptables**, **Écritures comptables article**, **Expéditions vente enregistrées** et **Factures vente enregistrées**.

## <a name="see-also"></a>Voir aussi
[Ventes](sales-manage-sales.md)  
[Procédure : envoyer des documents par e-mail](ui-how-send-documents-email.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


