---
title: Rapprocher les paiements fournisseur manuellement
description: "Pour traiter, mettre en correspondance, ou rapprocher des paiements ou des remboursements fournisseur manuellement, vous lettrez le montant dans une ou plusieurs écritures comptables fournisseur ouvertes."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment application, payment processing, match payments
ms.date: 06/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b65b39c120dc1c6837e0b1f53a22bc2ef9b1de38
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-reconcile-vendor-payments-manually"></a>Procédure : rapprocher les paiements fournisseur manuellement
Lorsque vous envoyez un règlement à un fournisseur ou recevez un remboursement de sa part, vous devez décider si vous souhaitez lettrer le paiement ou le remboursement avec une ou plusieurs écritures ouvertes. Vous pouvez indiquer le montant exact que vous souhaitez lettrer avec la réception paiement ou le remboursement, puis ne lettrer que partiellement les écritures comptables fournisseur. Vous devez lettrer toutes les écritures comptables fournisseur pour obtenir des statistiques fournisseur et des rapports corrects des états financiers et des intérêts de retard.

> [!NOTE]  
>   Les fournisseurs préfèrent parfois procéder à un remboursement plutôt que de créer un avoir déductible des prochaines factures, notamment si vous renvoyez des articles que vous avez déjà payés ou si vous avez versé un montant trop élevé pour une facture.

Vous pouvez lettrer les écritures comptables fournisseur de trois manières différentes :

* En entrant des informations dans les fenêtres dédiées, telles que la fenêtre **Feuille paiement** et la fenêtre **Feuille rapprochement bancaire**.
* À partir des documents avoir achat.
* À partir des écritures comptables fournisseur une fois que les documents achat sont validés mais non lettrés.

> [!NOTE]  
>   Si le champ **Mode de lettrage** de la fiche fournisseur contient **Au plus ancien**, les paiements sont automatiquement lettrés avec l'écriture de crédit ouverte la plus ancienne si vous ne spécifiez pas avec quelle écriture lettrer. Si le mode de lettrage pour un client est **Manuel**, vous devez lettrer les écritures manuellement.

Vous pouvez lettrer les paiements fournisseur manuellement à leurs documents achat associés lorsque vous validez les paiements dans la fenêtre **Feuille paiement**. Pour plus d'informations sur comment renseigner la feuille paiement, reportez-vous à [Effectuer des paiements](payables-make-payments.md).

Vous pouvez également lettrer des paiements fournisseur et des paiements client après que les paiements apparaissent en tant que des transactions bancaires négatives au niveau de votre banque. Dans la fenêtre **Feuille rapprochement bancaire**, vous pouvez utiliser les fonctions pour l'importation de relevés bancaires, le lettrage automatique, et le rapprochement bancaire. Pour plus d'informations, reportez-vous à [Rapprocher les paiements à l'aide du lettrage automatique](receivables-how-reconcile-payments-auto-application.md).

## <a name="to-apply-a-payment-to-a-single-or-multiple-vendor-ledger-entries"></a>Pour lettrer un paiement à une seule ou à plusieurs écritures comptable fournisseur
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuille paiement**, puis sélectionnez le lien connexe.
2. Dans la fenêtre **Feuille paiement**, dans la première ligne feuille, saisissez les informations appropriées sur l'écriture règlement.
3. Pour lettrer une seule écriture comptable fournisseur :
   1. Dans le champ **N° doc. lettrage**, sélectionnez le champ permettant d'ouvrir la fenêtre **Lettrer écritures fournisseur**.
   2. Dans la fenêtre **Lettrer écritures fournisseur**, sélectionnez l'écriture à laquelle lettrer le paiement.
   3. Sur la ligne du champ **Montant à lettrer**, entrez le montant à lettrer à l'écriture.
4. Ou, pour lettrer plusieurs écritures comptables fournisseur :

   1. Sélectionnez l'action **Lettrer écritures**.
   2. Dans la fenêtre **Lettrer écritures fournisseur**, sélectionnez les lignes contenant les écritures auxquelles lettrer le paiement.
   3. Sélectionnez l'action **Lettrer**.  
   4. Sur chaque ligne du champ **Montant à lettrer**, entrez le montant à lettrer à l'écriture.

      Si vous n'entrez aucun montant, le programme lettre automatiquement le montant maximal. Au bas de la fenêtre **Lettrer écritures fournisseur**, vous voyez le montant dans le champ Montant lettré et vous constatez si le lettrage est équilibré.
5. Cliquez sur le bouton **OK**.
6. Sélectionnez l'action **Valider** pour valider la feuille paiement.

## <a name="to-apply-a-credit-memo-to-a-single-or-multiple-vendor-ledger-entries"></a>Pour lettrer un avoir à une seule ou à plusieurs écritures comptables fournisseur
1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuille paiement**, puis sélectionnez le lien connexe.
2. Ouvrez l'avoir à lettrer.
3. Entrez les informations nécessaires dans l'en-tête.
4. Pour lettrer une seule écriture comptable fournisseur, dans le raccourci **Lettrage**, dans le champ **N° doc. lettrage**, sélectionnez l'écriture sur laquelle lettrer le crédit puis, dans le champ **Montant à lettrer**, entrez le montant à lettrer sur l'écriture.
5. Ou, pour lettrer plusieurs écritures comptables fournisseur :

   1. Sélectionnez l'action **Lettrer écritures**.
   2. Sélectionnez les lignes contenant les écritures auxquelles lettrer l'avoir.
   3. Sélectionnez l'action **Lettrer**.  
   4. Sur chaque ligne du champ **Montant à lettrer**, entrez le montant à lettrer à l'écriture.

       Si vous n'entrez aucun montant, le programme lettre automatiquement le montant maximal. Au bas de la fenêtre **Lettrer écritures fournisseur**, vous voyez le montant dans le champ **Montant lettré** et vous constatez si le lettrage est équilibré.
6. Cliquez sur le bouton **OK**.  
   La fenêtre **Avoir achat** affiche l'écriture que vous avez sélectionnée dans les champs **Type doc. lettrage** et **N° doc. lettrage**. La fenêtre affiche également le montant de l'avoir à valider, escomptes éventuels déduits.
7. Cliquez sur le bouton **Valider** pour valider l'avoir achat.

## <a name="to-apply-posted-vendor-ledger-entries"></a>Pour lettrer des écritures comptables fournisseur validées
1. Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Comptes bancaires**, puis sélectionnez le lien connexe.
2. Ouvrez le fournisseur approprié possédant des écritures déjà validées.
3. Sélectionnez l'action **Écritures comptables**, puis sélectionnez l'action **Lettrer écritures**.
4. Dans la fenêtre **Lettrer écritures fournisseur**, les écritures ouvertes de ce fournisseur s'affichent.
5. Sélectionnez la ligne où figure l'écriture qui sera lettrée.
6. Sélectionnez l'action **Lettrer**.

    Le champ **ID lettrage** affiche trois astérisques si vous travaillez dans un système mono-utilisateur ou votre code utilisateur si vous travaillez dans un système multi-utilisateur.  
7. Pour chaque ligne du champ **Montant à lettrer**, entrez le montant à lettrer à l'écriture.

    Si vous n'entrez aucun montant, le programme lettre automatiquement le montant maximal. Vous pouvez voir le montant dans le champ **Montant lettré** au bas de la fenêtre **Lettrer écritures fournisseur**.
8. Sélectionnez l'action **Valider le lettrage**.  

    La fenêtre **Valider le lettrage** s'ouvre et affiche le numéro de document de l'écriture lettrage et la date comptabilisation de l'écriture ayant la date comptabilisation la plus récente.
9. Cliquez sur **OK** pour valider le lettrage.

## <a name="to-apply-vendor-ledger-entries-in-different-currencies-to-one-another"></a>Pour lettrer des écritures comptables fournisseur en devises différentes les unes avec les autres
Si vous achetez des produits auprès d'un fournisseur dans une devise et que vous effectuez le paiement dans une autre devise, vous pouvez tout de même lettrer la facture avec le paiement.

Si vous lettrez une écriture (Écriture 1) dans une devise avec une autre écriture (Écriture 2) dont la devise est différente, la date de comptabilisation de l'Écriture 1 est utilisée pour trouver le taux de change adéquat et convertir les montants de l'Écriture 2. Le taux de change approprié se trouve dans la fenêtre **Taux de change devise**. Dans ce cas, vous devez activer le lettrage d'écritures comptables fournisseur en devises différentes. Pour plus d'informations, reportez-vous à [Procédure : activer le lettrage d'écritures comptables client en devises différentes](finance-how-enable-application-ledger-entries-different-currencies.md)

1. Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Feuille paiement**, puis sélectionnez le lien connexe.
2. Ouvrez la feuille que vous souhaitez, puis renseignez la première ligne vide de la feuille à l'aide d'un code devise.
3. Sélectionnez l'action **Lettrer écritures**.
4. Sélectionnez la ligne comportant l'écriture à lettrer avec l'écriture de la feuille paiement. Sélectionnez ensuite l'action **Lettrer**, puis sélectionnez l'écriture sur laquelle le lettrage doit être effectué.
5. Cliquez sur le bouton **OK** pour revenir à la feuille de paiement.
6. Validez la feuille paiement.

> [!IMPORTANT]  
>   Lorsque vous lettrez des écritures les unes aux autres en devises différentes, les écritures sont converties en USD. Bien que le taux de change des deux devises concernées soit fixe, comme entre le USD et l'EUR, la conversion de ces montants en devise en une somme en USD peut donner un petit montant résiduel. Le programme valide ces petits montants résiduels en tant que gains et pertes dans le compte défini dans le champ **Cpte gains constatés report** ou **Cpte pertes constatées report** de la fenêtre **Devises**. La valeur du champ **Montant (USD)** est également ajustée sur les écritures comptables fournisseur concernées.

## <a name="to-unapply-an-application-of-vendor-entries"></a>Pour délettrer un lettrage des écritures fournisseur
Lorsque vous délettrez un lettrage erroné, des écritures de correction (écritures identiques à l'écriture originale mais avec le signe opposé dans le champ du montant) sont créées et validées pour toutes les écritures comportant des validations comptables issues du lettrage, comme les escomptes et les pertes et gains en devise. Les écritures qui sont fermées par l'application sont rouvertes.

1. Choisissez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Comptes bancaires**, puis sélectionnez le lien connexe.
2. Ouvrez la fiche fournisseur appropriée.
3. Sélectionnez l'action **Écritures comptables**.
4. Sélectionnez l'écriture comptable appropriée, puis sélectionnez l'action **Délettrer les écritures**.
5. Sinon, sélectionnez l'action **Écritures comptables détaillées**.
6. Sélectionnez l'écriture de lettrage appropriée, puis sélectionnez l'action **Délettrer les écritures**.
7. Renseignez les champs de l'en-tête, puis sélectionnez l'action **Délettrer**.

> [!IMPORTANT]  
>   Si une écriture a été lettrée par plusieurs écritures lettrage, vous devez commencer par délettrer la dernière écriture lettrage.

## <a name="see-also"></a>Voir aussi
[Fournisseurs](payables-manage-payables.md)  
[Achats](purchasing-manage-purchasing.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

