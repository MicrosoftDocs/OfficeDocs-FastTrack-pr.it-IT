---
title: Il processo FastTrack
description: Panoramica del processo di onboarding del Vantaggio FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Normal
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a0fc877fa22f6198e45e212c85ea1234ed19da70
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817257"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Processo FastTrack Center Benefit per Enterprise Mobility + Security (EMS)

> [!CAUTION]
> Questo contenuto non è più corrente e viene pianificato per la rimozione. Utilizzare il sommario nel riquadro di spostamento sinistro per il contenuto corrente.

Se l'organizzazione è idonea per il Vantaggio FastTrack Center per EMS, è possibile collaborare in remoto con gli specialisti di FastTrack per avere Microsoft Azure Active Directory Premium, Microsoft Intune, Azure Information Protection pronti per l’utilizzo. È anche possibile richiedere assistenza nel [sito FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) per Azure Information Protection e Microsoft Cloud App Security. Per sapere se l'organizzazione è idonea, vedere [Piani e servizi idonei](M365-eligible-services-and-plans.md).


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

