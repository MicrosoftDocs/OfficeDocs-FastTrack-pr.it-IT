---
title: Il processo FastTrack
description: Panoramica del processo di onboarding del Vantaggio FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 09/04/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: d8a120c0f385549a6732a9d493313b5814b93be5
ms.sourcegitcommit: df949b40ade215de00f74771ffadf0d3be0de797
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 09/03/2019
ms.locfileid: "36711468"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Processo FastTrack Center Benefit per Enterprise Mobility + Security (EMS)
Se l'organizzazione è idonea per il Vantaggio FastTrack Center per EMS, è possibile collaborare in remoto con gli specialisti di FastTrack per avere Microsoft Azure Active Directory Premium, Microsoft Intune, Azure Information Protection pronti per l’utilizzo. È anche possibile richiedere assistenza nel [sito FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) per Azure Information Protection, Microsoft Cloud App Security e Microsoft Advanced Threat Analytics. Per sapere se l'organizzazione è idonea, vedere [Piani e servizi idonei](M365-eligible-services-and-plans.md).


Ecco il processo di onboarding:

-   [Panoramica del processo di onboarding](EMS-fasttrack-benefit-overview.md)

-   [Previsioni per l'ambiente di origine](EMS-source-environment-expectations.md)

-   [Fasi del processo di onboarding](EMS-onboarding-phases.md)

-   [Responsabilità di FastTrack](EMS-fasttrack-responsibilities.md) per ogni fase

-   [Responsabilità dei clienti](EMS-your-responsibilities.md) per ogni fase

Ecco cosa aspettarsi una volta completato il processo di onboarding:

-   Vengono creati i tenant EMS per i servizi selezionati.

-   Gli utenti con licenza possono accedere ai servizi EMS utilizzando una delle seguenti opzioni di gestione delle identità:

    -   Identità cloud (con account EMS univoci).

    -   Identità sincronizzate: account EMS sincronizzati da Active Directory locale con lo strumento Azure Active Directory Connect (sincronizzazione degli hash delle password o autenticazione pass-throug ). Questa opzione è per i clienti con una singola foresta o più foreste di Active Directory.

    -   Identità federate--con gli account Microsoft EMS seguenti:

        -   Sincronizzato da Active Directory con lo strumento Azure AD Connect. Questa opzione è per i clienti con una configurazione a foresta singola di Active Directory.

        -   Federato con Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 o versione successiva di Active Directory locale.

        -   La possibilità di classificare e proteggere automaticamente le informazioni sia inattive che in transito con Azure Information Protection. 

        -   La possibilità di individuare informazioni all'interno di condivisioni file locali e server di SharePoint con lo scanner di Azure Information Protection. 

        -   La possibilità di gestire le chiavi del tenant di Azure Information Protection nell’Azure Key Vault. 
