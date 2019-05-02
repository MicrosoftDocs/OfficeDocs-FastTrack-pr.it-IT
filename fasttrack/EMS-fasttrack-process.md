---
title: Processo di FastTrack
description: Panoramica del processo di onboarding dei vantaggi di FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 1e3f34284cb4b6300a50116ad2bb1df3cb6ab0fe
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513775"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Processo FastTrack Center Benefit per Enterprise Mobility + Security (EMS)
Se l'organizzazione è idonea per il vantaggio FastTrack Center per EMS, è possibile lavorare in remoto con gli specialisti di FastTrack per ottenere Microsoft Azure Active Directory Premium, Microsoft Intune e Azure Information Protection pronto per l'uso. È inoltre possibile richiedere assistenza tramite il [sito FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) per Azure Information Protection, Microsoft cloud app Security e Microsoft Advanced Threat Analytics. Per sapere se l'organizzazione è idonea, vedere [Servizi e piani idonei](M365-eligible-services-and-plans.md).


Di seguito viene illustrato il processo di onboarding:

-   [Panoramica del processo di onboarding](EMS-fasttrack-benefit-overview.md)

-   [Aspettative per l'ambiente di origine](EMS-source-environment-expectations.md)

-   [Fasi del processo di onboarding](EMS-onboarding-phases.md)

-   [Responsabilità di FastTrack](EMS-fasttrack-responsibilities.md) per ogni fase

-   [Responsabilità del cliente](EMS-your-responsibilities.md) per ogni fase

Ecco cosa è possibile prevedere quando l'onboarding è completo:

-   Vengono creati i tenant EMS per i servizi selezionati.

-   Gli utenti con licenza possono accedere ai servizi EMS utilizzando una delle seguenti opzioni di identità:

    -   Identità cloud (account EMS univoci).

    -   Identità sincronizzate: account EMS sincronizzati da Active Directory locale utilizzando lo strumento Azure Active Directory Connect (sincronizzazione hash password o autenticazione pass-through). Questa opzione è destinata ai clienti con una singola foresta o più foreste di Active Directory.

    -   Identità federate--con gli account di Microsoft EMS che sono:

        -   Sincronizzato da Active Directory con lo strumento Azure AD Connect. Questa opzione è destinata ai clienti con una singola configurazione della foresta di Active Directory.

        -   Federata con Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2,0 o versioni successive da Active Directory locale.

        -   La possibilità di classificare automaticamente e proteggere le informazioni sia a riposo che in transito con Azure Information Protection. 

        -   La possibilità di individuare le informazioni all'interno di condivisioni di file locali e server di SharePoint con lo scanner di Azure Information Protection. 

        -   La possibilità di gestire le chiavi tenant di Azure Information Protection all'interno del Vault Key di Azure. 
