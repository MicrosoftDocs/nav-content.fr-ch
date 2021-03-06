---
title: "Envoyer des documents électroniques"
description: "Découvrez comment envoyer des factures par voie électronique."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5920ed97f054b3e7882f40f2fceec76183800297
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-send-electronic-documents"></a>Procédure : envoyer des documents électroniques
La version générique de [!INCLUDE[d365fin](includes/d365fin_md.md)] prend en charge l'envoi de factures et d'avoirs électroniques au format PEPPOL, qui est pris en charge par les principaux fournisseurs de services d'échange de documents. Un fournisseur de services d'échange de documents affecte des documents électroniques entre partenaires commerciaux. Pour assurer la prise en charge d'autres formats de documents électroniques, vous pouvez utiliser l'infrastructure d'échange de données.  

 Dans la version générique de [!INCLUDE[d365fin](includes/d365fin_md.md)], un service d'échange de documents est préconfiguré et prêt à être installé pour votre société. Pour plus d'informations, reportez vous à [Procédure : configurer un service d'échange de document](across-how-to-set-up-a-document-exchange-service.md).  

 Pour envoyer une facture vente en tant que document électronique PEPPOL, sélectionnez l'option **Document électronique** dans la boîte de dialogue **Valider et envoyer** à partir de laquelle vous pouvez également configurer le profil d'envoi de document par défaut du client. Au préalable, vous devez configurer différentes données de base, telles que les informations sur la société, les clients, les articles, et les unités de mesure. Celles-ci sont utilisées pour identifier les partenaires commerciaux et les articles lors de la conversion des données des champs dans [Procédure : configurer l'envoi et la réception de documents électroniques](across-how-to-set-up-electronic-document-sending-and-receiving.md).  

### <a name="to-send-an-electronic-sales-invoice"></a>Envoyer une facture vente électronique  

1.  Sélectionnez l'icône ![Page ou état pour la recherche](media/ui-search/search_small.png "Page ou état pour la recherche"), entrez **Factures vente**, puis sélectionnez le lien connexe.  

2.  Créez une facture vente.  

3.  Lorsque la facture vente est prête à être émise, sous l'onglet **Actions**, dans le groupe **Validation**, sélectionnez **Valider et envoyer**.  

     Si le profil d'envoi par défaut du client est **Document électronique**, il s'affiche dans la boîte de dialogue **Valider et envoyer une confirmation** et il vous suffit de choisir le bouton **Oui** pour valider et envoyer la facture par voie électronique au format sélectionné.  

4.  Dans la boîte de dialogue **Valider et envoyer une confirmation**, cliquez sur le bouton AssistEdit situé à droite du champ **Envoyer le document à**.  

5.  Dans la boîte de dialogue **Envoyer le document à**, dans le champ **Document électronique**, sélectionnez **Via le service d'échange de documents**.  

6.  Dans le champ **Format**, sélectionnez **PEPPOL**.  

7.  Cliquez sur le bouton **OK**. La boîte de dialogue **Valider et envoyer une confirmation** s'affiche. **Document électronique (PEPPOL)** est ajouté au champ **Envoyer le document à**.  

8.  Cliquez sur le bouton **Oui**.  

     La facture vente enregistrée est validée et envoyée au client en tant que document électronique au format PEPPOL.  

    > [!NOTE]  
    >  Vous pouvez également envoyer une facture vente validée en tant que document électronique. La procédure est la même que celle décrite dans cette rubrique pour les documents vente non validés. Dans la fenêtre **Facture vente enregistrée**, sous l'onglet **Actions**, dans le groupe **Général**, sélectionnez **Journal des activités** pour afficher le statut du document électronique. Pour plus d'informations, voir **Journal des activités**.  

## <a name="see-also"></a>Voir aussi  
[Procédure : facturer des ventes](sales-how-invoice-sales.md)  
[Procédure : configurer des profils d'envoi de documents](sales-how-setup-document-send-profiles.md)  
[Procédure : Configurer l'envoi et la réception de documents électroniques](across-how-to-set-up-electronic-document-sending-and-receiving.md)  
[Procédure : configurer un service d'échange de document](across-how-to-set-up-a-document-exchange-service.md)  
[Procédure : configurer les définitions d'échange de données](across-how-to-set-up-data-exchange-definitions.md)  
[Échanger des données par voir électronique](across-data-exchange.md)  
[Fonctionnalités marché](ui-across-business-areas.md)  

