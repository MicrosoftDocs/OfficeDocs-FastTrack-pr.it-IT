---
title: Informazioni generali su FastTrack Center Benefit
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see FastTrack Center Benefit for Office 365.
ms.openlocfilehash: 3537f6effa5bd2c65f542496ea42ab70075621ce
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011334"
---
# <a name="fasttrack-center-benefit-overview"></a>Informazioni generali su FastTrack Center Benefit

With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see [FastTrack Center Benefit for Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Verranno trattati i seguenti argomenti:
- [Il processo FastTrack](O365-fasttrack-process.md) 
- [Aspettative sull'ambiente di origine](O365-source-environment-expectations.md)
- [Fasi del processo di onboarding e migrazione](O365-onboarding-and-migration.md)
- [Migrazione dei dati](O365-data-migration.md)
- [Responsabilità di FastTrack](O365-fasttrack-responsibilities.md)
- [Responsabilità dell'utente](O365-your-responsibilities.md) 
- [Appendice A: Ulteriore vantaggio di FastTrack Center](O365-fasttrack-additional-benefits.md)
- [Appendice B - Contratto di società in affari HIPAA di FastTrack Center](O365-hipaa-business-associate-agreement.md)
- [Appendice C - Informazioni generali su FastTrack Center Benefit per Office 365 US Government](US-Gov-appendix-overview.md)
    
Your Office 365 tenant is created at the completion of onboarding. Licensed users can access Office 365 by using one of the following identity options:
- Identità cloud con account Office 365 univoci.
- Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication). These are for customers with:
  - Una foresta Active Directory singola.
  - Supported multi-forests Active Directory topology. For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
- Identità federate con i tipi di account Office 365 seguenti:
  - Sincronizzati da Active Directory con lo strumento Azure Active Directory Connect per i clienti con:
      - Una configurazione a foresta singola di Active Directory.
      - Una foresta account singola di Active Directory (nota anche come "foresta di accesso") e una configurazione foresta di risorse singola di Active Directory.
  - Configurati con un'infrastruttura Active Directory Federation Services (AD FS) locale che abbia le seguenti caratteristiche:
      - Federati con un ruolo Windows Server 2012 R2 AD FS e successivi da Active Directory locale.
      - Quando viene richiesto, un ruolo WAP di Windows Server 2012 R2 e successivi viene usato per pubblicare l'infrastruttura AD FS locale su Internet.
    > [!NOTE]
    > La distribuzione e la configurazione di AD FS e WAP vengono eseguite utilizzando l'[Installazione personalizzata di Azure AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) dall'ambiente locale. 
  
- Gli utenti con licenza ora possono accedere a [Piani e servizi idonei](M365-eligible-services-and-plans.md).

