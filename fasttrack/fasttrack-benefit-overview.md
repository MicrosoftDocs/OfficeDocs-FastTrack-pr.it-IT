---
title: Informazioni generali su FastTrack Center Benefit
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 09/04/2018
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: ac467db0-3118-41fa-a93d-bb5de1e414d5
description: Con FastTrack Center Benefit per Office 365, è possibile lavorare in remoto con gli esperti di FastTrack per avere il proprio ambiente Office 365 pronto per l'uso e la pianificazione dell'implementazione e dell'utilizzo all'interno dell'organizzazione. Per ulteriori informazioni sull'idoneità, vedere FastTrack Center Benefit per Office 365.
ms.openlocfilehash: 4007e735e77649b7153b4498d98c2ba45c5473e2
ms.sourcegitcommit: 04c086418a97082a88b7ab85b284e4741c1c9139
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 09/20/2018
ms.locfileid: "24057740"
---
# <a name="fasttrack-center-benefit-overview"></a>Informazioni generali su FastTrack Center Benefit

Con FastTrack Center Benefit per Office 365, è possibile lavorare in remoto con gli esperti di FastTrack per avere il proprio ambiente Office 365 pronto per l'uso e la pianificazione dell'implementazione e dell'utilizzo all'interno dell'organizzazione. Per ulteriori informazioni sull'idoneità, vedere [FastTrack Center Benefit per Office 365](fasttrack-benefit-for-office-365.md).
  
Verranno trattati i seguenti argomenti:
- [Il processo FastTrack](fasttrack-process.md) 
- [Aspettative sull'ambiente di origine](source-environment-expectations.md)
- [Fasi del processo di onboarding e migrazione](onboarding-and-migration.md)
- [Migrazione dei dati](data-migration.md)
- [Responsabilità di FastTrack](fasttrack-responsibilities.md)
- [Responsabilità dell'utente](your-responsibilities.md) 
- [Appendice A: Migrazione da IBM Domino a Exchange Online](from-ibm-domino-to-exchange-online.md)
- [Appendice B: Ulteriore vantaggio di FastTrack Center](fasttrack-additional-benefits.md)
- [Appendice C - Contratto di società in affari HIPAA di FastTrack Center](hipaa-business-associate-agreement.md)
- [Appendice D - Informazioni generali su FastTrack Center Benefit per Office 365 US Government](US-Gov-appendix-overview.md)
    
Una volta completato l'onboarding, viene creato il tenant di Office 365. Gli utenti con licenza possono accedere a Office 365 utilizzando una delle seguenti opzioni di gestione delle identità:
- Identità cloud con account Office 365 univoci.
- Identità sincronizzate con account Office 365 sincronizzati da Active Directory locale con Azure Active Directory Connect (sincronizzazione degli hash delle password o autenticazione pass-throug ). Sono per i clienti con:
  - Una foresta Active Directory singola.
  - Una topologia di Active Directory a più foreste supportata. Per le topologie supportate, vedere [Previsioni dell'ambiente di origine](source-environment-expectations.md).
- Identità federate con i tipi di account Office 365 seguenti:
  - Sincronizzati da Active Directory con lo strumento Azure Active Directory Connect per i clienti con:
      - Una configurazione a foresta singola di Active Directory.
      - Una foresta account singola di Active Directory (nota anche come "foresta di accesso") e una configurazione foresta di risorse singola di Active Directory.
  - Configurati con un'infrastruttura Active Directory Federation Services (AD FS) locale che abbia le seguenti caratteristiche:
      - Federati con un ruolo Windows Server 2012 R2 AD FS e successivi da Active Directory locale.
      - Quando viene richiesto, un ruolo WAP di Windows Server 2012 R2 e successivi viene usato per pubblicare l'infrastruttura AD FS locale su Internet.
    > [!NOTE]
    > La distribuzione e la configurazione di AD FS e WAP vengono eseguite utilizzando l'[Installazione personalizzata di Azure AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) dall'ambiente locale. 
  
- Gli utenti con licenza ora possono accedere a [Piani e servizi idonei](eligible-services-and-plans.md).
    

 
