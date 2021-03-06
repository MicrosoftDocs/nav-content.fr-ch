---
title: "Tâches administratives dans Dynamics NAV"
description: "Certaines tâches dans [!INCLUDE[d365fin](includes/d365fin_md.md)] requièrent une administration centrale et une configuration. Découvrez quelles sont ces tâches et ce que vous devez faire."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 873c8e6f9887ef49d8639851bb64013d985e640e
ms.contentlocale: fr-ch
ms.lasthandoff: 10/16/2017

---
# <a name="setup-and-administration-in-dynamics-nav"></a>Configuration et administration dans Dynamics NAV
Les tâches d'administration centrale sont généralement effectuées par une fonction dans la société. La portée de ces tâches peut dépendre de la taille de la société et des responsabilités de l'administrateur. Ces tâches sont notamment la synchronisation de bases de données de gestion de file d'attentes de travaux ou d'e-mails, la configuration utilisateur, la personnalisation d'interface utilisateur, et la gestion des clés de chiffrement.  

Il est important d'entrer des valeurs de configuration correctes dès le début pour garantir le succès de tout nouveau logiciel de gestion. [!INCLUDE[d365fin](includes/d365fin_md.md)] inclut plusieurs guides de configuration qui vous permettent de configurer les données de base. Pour plus d'informations, reportez-vous à [Configuration de Dynamics NAV](setup.md).

<!--Whether you use [!INCLUDE[rim](../../includes/rim_md.md)] to implement setup values or you manually enter them in the new company, you can support your setup decisions with some general recommendations for selected setup fields that are known to potentially cause the solution to be inefficient if defined incorrectly.-->  

Un super utilisateur ou un administrateur peut configurer une infrastructure d'échange de données pour permettre aux utilisateurs d'exporter et d'importer des données dans des fichiers de banques ou de salaires, par exemple plusieurs processus de gestion d'espèces.  

Le tableau suivant décrit une série de tâches et inclut des liens vers les rubriques qui les décrivent.   

|**Pour**|**Voir**|  
|------------|-------------|  
|Ajouter des utilisateurs, gérer les autorisations et les accès aux données et affecter des rôles.|[Utilisateurs, profils et tableaux de bord dans Dynamics NAV](admin-users-profiles-roles.md)|  
|Suivre les modifications directes des données effectuées par les utilisateurs dans la base de données pour identifier l'origine des erreurs et les modifications de données.|[Journalisation des modifications dans Dynamics NAV](across-log-changes.md)|  
|Justifiez vos décisions de configuration à l'aide de recommandations pour les champs sélectionnés connus pour éventuellement entraîner l'inefficacité de la solution en cas de mauvaise configuration|[Configurer les modules complexes à l'aide des meilleures pratiques](set-up-complex-application-areas-using-best-practices.md)|  
|Affichez des pages, des codeunites, et des requêtes comme des services Web.|[Procédure : publication d'un service Web](across-how-publish-web-service.md)|  
|Configurer un serveur SMTP pour activer une communication entrante et sortante de Dynamics NAV via e-mail.| [Procédure : paramétrer la messagerie manuellement ou à l'aide de la configuration assistée](madeira-how-setup-email.md)|  
|Entrer des demandes ponctuelles ou récurrentes pour exécuter des états ou des codeunits.|[Utiliser des files d'attente des travaux pour planifier des tâches](admin-job-queues-schedule-tasks.md)|  
|Gérer, supprimer ou compresser des documents|[Gérer les documents](admin-manage-documents.md)|  

## <a name="see-also"></a>Voir aussi
[Aperçu de la fonctionnalité d'affaires](madeira-business-functionality.md)  
[Fonctionnalités marché](ui-across-business-areas.md)  
[Utilisation de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Bienvenue dans [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)  

