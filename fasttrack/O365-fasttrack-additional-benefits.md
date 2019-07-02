---
title: Appendice B Ulteriore vantaggio di FastTrack Center
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 07/02/2019
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: I clienti che acquistano almeno 20.000 licenze per un tenant di Exchange Online possono ottenere i servizi aggiuntivi di FastTrack Center. Per ulteriori dettagli, vedere Piani e servizi idonei.
ms.openlocfilehash: 1675085a18c8bedf05ccedac7450f8d67d682de2
ms.sourcegitcommit: ed0bbc37b887f2ea408575b1a667550b2797cc0a
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 07/01/2019
ms.locfileid: "35411007"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>Appendice B: Ulteriore vantaggio di FastTrack Center

I clienti che acquistano almeno 20.000 licenze per un tenant di Exchange Online possono ottenere i servizi aggiuntivi di FastTrack Center. Per ulteriori dettagli, vedere [Piani e servizi idonei](M365-eligible-services-and-plans.md). 
  
## <a name="onboarding-and-migration-phases"></a>Fasi del processo di onboarding e migrazione

## <a name="core"></a>Componenti di base

I servizi aggiuntivi relativi all'onboarding di base includono una guida di configurazione per AD FS (Active Directory Federation Services) e per i criteri di accesso client AD FS con ridondanza geografica per quel servizio. 
  
## <a name="exchange-online"></a>Exchange Online

Nel caso di Exchange Online, viene fornita una guida di configurazione per gli aspetti seguenti:
- Impostazione della messaggistica unificata con Exchange Online.
- Configurazione della coesistenza tra Exchange Online e cartelle pubbliche locali legacy.
- Integrazione di applicazioni abilitate alla posta elettronica. 
- Pianificazione della migrazione e raggruppamento della cassetta postale.
    
## <a name="skype-for-business-online"></a>Skype for Business online

Per Skype for Business online, viene fornita una guida per la migrazione degli utenti di Lync locale e Skype for Business a Skype for Business online.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Nel caso di Office 365 ProPlus, viene fornita una guida per gli aspetti seguenti: 
- Valutazione e pianificazione concentrate sulla preparazione dell'ambiente per la distribuzione iniziale e la gestione degli aggiornamenti in linea con le procedure consigliate di Microsoft. 
- Sviluppo delle configurazioni di distribuzione e delle impostazioni di aggiornamento con lo Strumento di distribuzione di Office 365. 
- Creazione di pacchetti per la distribuzione mediante System Center Configuration Manager.  
- La distribuzione e la configurazione della telemetria di Office offrono assistenza per valutare l'utilizzo di documenti e soluzioni di Office cruciali per l'organizzazione per garantire la compatibilità delle applicazioni.
    
## <a name="fasttrack-responsibilities"></a>Responsabilità di FastTrack

Gli esperti di FastTrack hanno le seguenti responsabilità durante la procedura di onboarding. Tali responsabilità possono aggiungersi o sostituire le attività definite nell'argomento [Responsabilità di FastTrack](O365-fasttrack-responsibilities.md).
  
## <a name="general"></a>Generale

- Fornire assistenza al supporto remoto per un corretto sviluppo della pianificazione, implementazione e per le necessarie attività di configurazione, come descritto in [Fasi del processo di onboarding e migrazione](#onboarding-and-migration-phases).
    
## <a name="assess-phase"></a>Fase di valutazione

- Effettuare una chiamata per fornire assistenza in merito a una corretta adozione da parte dell'utente. 
- Valutare il proprio ambiente per offrire supporto alla configurazione di AD FS con ridondanza geografica.  
- Eseguire una valutazione per identificare i requisiti per l'accesso client AD FS.
    
## <a name="enable-phase"></a>Fase di attivazione:

### <a name="geo-redundant-ad-fs-guidance"></a>Indicazioni su AD FS con ridondanza geografica

- Fornire la progettazione dell'architettura di riferimento standard per una topologia AD FS con ridondanza geografica che si estende su due (2) data center. L'architettura standard fornisce:
  - Autenticazione federata per i servizi relativi al FastTrack Center Benefit. 
  - Resilienza del sito singolo.  
  - Disponibilità elevata e failover.  
  - Indicazioni di ridimensionamento. 
- Fornire istruzioni su come usare Windows Internal Database e SQL Server come istanza del database per la farm AD FS.   
- Convalidare la determinazione relativa all'autenticazione federata per ogni foresta dell'ambito.  
- Confermare il funzionamento dell'autenticazione federata per un massimo di 10 utenti.
    
> [!NOTE]
> Le distribuzioni AD FS sono comprese per i clienti che hanno diritto a benefit aggiuntivi, i quali dispongono di più configurazioni di foresta Active Directory. 
  
### <a name="ad-fs-client-access-policy-guidance"></a>Indicazioni sui criteri di accesso client AD FS

- Rivedere i criteri e la configurazione necessari per proteggere le risorse di Office 365.  
- Fornire istruzioni e assistenza per configurare i criteri di accesso client AD FS per le situazioni di accesso client identificate all'interno degli scenari supportati. Per ulteriori informazioni, vedere [Limitazione dell'accesso ai servizi di Office 365 in base al percorso del client](https://go.microsoft.com/fwlink/?LinkID=525689). 
- Convalidare il funzionamento dell'autenticazione federata con i criteri di accesso client modificati per scenari di accesso identificati, con un massimo di 10 utenti configurati.
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Indicazioni su Messaggistica unificata di Exchange

- Fornire assistenza in merito alla configurazione richiesta su Exchange Online per abilitare fino a 10: 
  - Dial plan di messaggistica unificata.   
  - Criteri cassetta postale di messaggistica unificata. 
  - Operatori automatici.  
- Fornire assistenza per la configurazione di Lync locale o per l'ambiente di Skype for Business al fine di abilitare la messaggistica unificata e avere come target:  
  - Criteri ospitati su Exchange Online.  
  - Criteri di segreteria telefonica ospitati su Exchange Online. 
  - I contatti relativi all'operatore automatico di messaggistica unificata e la segreteria telefonica di Outlook per reindirizzare gli utenti a Exchange Online. 
  - Assistenza per la creazione dei record SRV, così come richiesto dalla federazione.
> [!NOTE]
> La messaggistica unificata può essere configurata con gateway IP di messaggistica unificata supportati e session border controller (SBC). Per ulteriori informazioni, vedere [Integrazione del sistema di telefonia con la messaggistica unificata](https://go.microsoft.com/fwlink/?LinkID=809293). 
  
### <a name="public-folder-coexistence-guidance"></a>Indicazioni sulla coesistenza delle cartelle pubbliche

- Fornire indicazioni sulla coesistenza di un singolo albero di cartelle pubbliche, comprese informazioni su:  
  - Preparazione di cartelle pubbliche in Exchange 2007, Exchange 2010 e Exchange 2013. 
  - Cmdlet Windows PowerShell necessari per sincronizzare la gerarchia di cartelle pubbliche di Exchange 2007, Exchange 2010 e Exchange 2013 con Exchange Online.  
  - Configurazione di Exchange Online per reindirizzare l'accesso della cartella pubblica alle cartelle pubbliche locali.  
  - Configurazione dell'accesso alle cartelle pubbliche da Exchange Online all'ambiente locale singolo di Exchange 2007, Exchange 2010 o Exchange 2013.  
  - Guida alla convalida dell'accesso alla cartella pubblica per un massimo di 10 utenti in Exchange Online.
    
### <a name="mail-enabled-application-integration-guidance"></a>Guida all'integrazione di applicazioni abilitate alla posta elettronica

- Fornire modelli di assistenza per:  
  - Applicazioni posta di massa.  
  - Applicazioni che instradano i messaggi di posta elettronica tramite Exchange.  
  - Applicazioni che utilizzano le cassette postali di Exchange.  
  - Applicazioni che necessitano di componenti personalizzati o di terze parte da installare nei server di Exchange.
    
### <a name="mailbox-migration-planning-and-grouping"></a>Pianificazione della migrazione e raggruppamento della cassetta postale

- Fornire assistenza in merito alla creazione di un piano di migrazione:  
  - Raggruppamento di utenti e risorse.
  - Coordinamento della distribuzione relativa ai pacchetti software necessari per i batch di migrazione.   
  - Istruzioni su come creare un piano di comunicazione per gli utenti finali. 
  - Coordinamento relativo alla dimensione dei batch di migrazione, alle percentuali di errore e all'assistenza del supporto tecnico prevista. 
- Fornire assistenza in merito al raggruppamento delle cassette postali degli utenti e delle risorse in base alla tipologia, alla funzione aziendale e all'accesso delegato, attenendosi alle informazioni fornite dal cliente.
    
## <a name="skype-for-business-online"></a>Skype for Business online

- Fornire indicazioni sulla migrazione degli utenti raggruppati in una distribuzione ibrida di Skype for Business (mantenendo gli elenchi dei contatti degli utenti).
    
## <a name="office-365-proplus"></a>Office 365 ProPlus

- Fornire indicazioni e assistenza per:  
  - Valutazione e pianificazione in linea con le procedure consigliate di Microsoft per la distribuzione iniziale e per la gestione degli aggiornamenti.
  - Implementare e configurare la telemetria di Office. 
  - Attivare la registrazione della telemetria per i client di Office 2013 e versioni successive usando i Criteri di gruppo. 
  - Distribuire agenti di telemetria di Office per i client di Office (Office 2003 Office 2007 e Office 2010). 
  - Implementare il processore di telemetria. 
    > [!NOTE]
    > Questa operazione necessita di un percorso di condivisione nel quale memorizzare i dati della telemetria, nonché di un server con SQL Server 2005 e versioni successive al quale inviare i dati elaborati. 
  
## <a name="your-responsibilities"></a>Responsabilità dell'utente

L'utente ha le seguenti responsabilità durante la procedura di onboarding. Si tratta di responsabilità che vanno ad aggiungersi a quelle definite nella sezione [Responsabilità dell'utente](O365-your-responsibilities.md). 
  
- Assegnare e gestire le risorse in base alla pianificazione del progetto.  
- Intervenire tempestivamente per mitigare i rischi e risolvere i problemi sollevati dai clienti, dai project manager del partner e dal responsabile FastTrack.   
- Esaminare i report di stato ed agire in base a quanto riportato.   
- Indicare uno sponsor operativo o un lead con l'autorità decisionale necessaria per presiedere le riunioni sull'andamento dei progetti.  
- Indicare uno sponsor esecutivo che possa collaborare con lo sponsor esecutivo Microsoft.  
- Pianificare una riunione mensile sull'andamento del progetto.
    

  

