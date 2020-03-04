---
title: Responsabilità di FastTrack
description: Responsabilità di FastTrack quando i clienti usano il FastTrack Center Benefit per EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 3/03/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 3313834ef5c342d71f6c3940bd55d62bc1e87863
ms.sourcegitcommit: 79a5b31863be3d554223f75ca866dcf40dd2c2dd
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 03/02/2020
ms.locfileid: "42347408"
---
# <a name="fasttrack-responsibilities"></a>Responsabilità di FastTrack

FastTrack ha le seguenti responsabilità durante la procedura di onboarding.

## <a name="general"></a>Generale

-   Viene fornita all'utente assistenza al supporto remoto per le necessarie attività di configurazione, come descritto in dettaglio nelle fasi riportate.

-   All'utente vengono forniti documentazione disponibile, strumenti software, console di amministrazione per ridurre o eliminare le attività di configurazione. 

## <a name="initiate-phase"></a>Fase di avvio

-   Collaborare per avviare l'onboarding.

-   Definire i servizi da caricare.

## <a name="assess-phase"></a>Fase di valutazione

-   Fornire una panoramica sull'amministrazione.

-   Fornire indicazioni su:

    -   Esigenze di DNS, rete e infrastruttura.

    -   Esigenze del client (esigenze di browser, sistema operativo client e servizi)

    -   Identità dell'utente e provisioning.

    -   Abilitare i servizi che sono stati acquistati e definiti come parte dell'onboarding.

-   Stabilire la sequenza temporale per le attività di correzione.

-   Viene fornito un elenco di controllo correttivo per Intune e Azure AD Premium.

## <a name="remediate-phase"></a>Fase di correzione

-   Organizzare conferenze telefoniche con l'utente in base alla pianificazione concordata per esaminare lo stato di avanzamento delle attività di correzione, ad esempio, per illustrare i prerequisiti per l'installazione prima dell’onboarding di un servizio cloud Microsoft.

## <a name="enable-phase"></a>Fase di attivazione
Fornire indicazioni su:

-   Attivare il tenant o l'abbonamento di Microsoft Online Services.

-   Configurazione di protocolli TCP/IP e porte del firewall.

-   Configurazione del DNS per servizi.

-   Convalidare la connettività ai servizi online Microsoft.

-   Per un ambiente a foresta singola:

    -   Installazione di un server di sincronizzazione delle directory tra Active Directory Domain Services (AD DS) e ai Microsoft Online Services online (solo assistenza se necessario).

    -   Configurazione dell'autenticazione gestita (sincronizzazione hash password o autenticazione pass-through) con lo strumento Azure Active Directory Connect. (solo assistenza se necessario).

        > [!NOTE]
        > Sviluppo e implementazione per estensioni di regole personalizzate non rientrano nell'ambito.

-   Per una singola foresta, se la destinazione sono le identità federative: Installazione e configurazione di Active Directory Federation Services (AD FS) per l'autenticazione di domini locali con Intune in un solo sito e configurazione a tolleranza di errore, se necessario.

    > [!NOTE]
    > Per tutte le configurazioni di più foreste, le distribuzioni di AD FS non rientrano nell'ambito.

-   Test sulla funzionalità SSO (Single Sign-On), se distribuita.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Fase di attivazione: Microsoft Azure Active Directory Premium

Fornire indicazioni su:

- Attivazione del tenant di Azure AD Premium.

- Configurazione delle porte del firewall.

- Configurazione del DNS per servizi.

- Convalidare la connettività ai servizi di Azure AD Premium.

- Per un ambiente a foresta singola:

  -   Installazione di una sincronizzazione delle directory tra Active Directory Domain Services (AD DS) e Azure AD Connect, se necessario.

  -   Configurazione un metodo di autenticazione gestita (sincronizzazione hash password o autenticazione pass-through) con lo strumento Azure AD Connect.

- Per un ambiente a più foreste:

  -   Installare la sincronizzazione di Azure AD Connect, configurare scenari con più foreste.
- Per gli ambienti con una o più foreste:
  - Configurazione dell'Autenticazione pass-through di Azure Active Directory, se necessario.
  - Configurazione dell'Accesso Single Sign-On facile di Azure Active Directory, se necessario.
    > [!NOTE]
    > L'Autenticazione pass-through di Azure Active Directory per ambienti con più foreste è supportata se sono presenti trust tra le foreste di Active Directory e se il routing dei suffissi nome è configurato correttamente. È possibile installare ulteriori agenti su più server locali per fornire disponibilità elevata per le richieste di accesso.

  - Per ulteriori informazioni, vedere [Autenticazione pass-through di Azure Active Directory: avvio rapido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) e [Accesso Single Sign-On facile di Azure Active Directory: guida introduttiva](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Per ulteriori informazioni sui limiti dell'autenticazione pass-through, vedere [Autenticazione pass-through di Azure Active Directory: limitazioni correnti](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Per ulteriori informazioni sui problemi relativi all'accesso Single Sign-On facile, vedere [Risolvere i problemi relativi all'accesso Single Sign-On facile di Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > Sincronizzazione dell’hash delle password e writeback delle passare supportano più foreste. Tuttavia, altri scenari writeback non sono supportati.

  - Configurare la sincronizzazione tra foreste Active Directory in locale e la directory di Microsoft Azure Active Directory Premium directory (Azure Active Directory).

    > [!NOTE]
    > Sviluppo e implementazione per estensioni di regole personalizzate non rientrano nell'ambito.

- Per una singola foresta, se la destinazione è costituita dalle identità federative:

  -   Installazione e configurazione di AD FS per l'autenticazione di domini locali con Azure AD Premium in un solo sito e configurazione a tolleranza di errore, se necessario.

  > [!NOTE]
  > Per tutte le configurazioni di più foreste, le distribuzioni di AD FS non rientrano nell'ambito.

- Test sulla funzionalità SSO (se distribuita).

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>Fase di attivazione - Azure AD Premium - con Azure AD Connect e AD FS

Fornire indicazioni sulla configurazione:

- Provisioning dell'utente, incluse le licenze.

- Sincronizzazione della directory di Azure AD Connect (con il writeback delle password e la sincronizzazione dell’hash delle password).

  - Reimpostazione password self-service (SSPR) di Azure Active Directory.

  - Autenticazione a più fattori di Azure.

  - Fino a tre (3) o più software come integrazioni applicazioni di servizio (SaaS) con Single Sign-on (SSO) dall’[Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Il provisioning automatico degli utenti per le applicazioni SaaS preintegrate, come indicato [nell'elenco delle esercitazioni di integrazione di app](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list), solo per il provisioning in uscita.

  - Schermata di accesso personalizzata, tra cui il logo, il testo e le immagini.

  - Gruppi dinamici e self-service (Gruppi).

  - Azure Active Directory Application Proxy.

  - Azure Active Directory Connect Health.

  - Accesso condizionale di Azure Active Directory.

  - Condizioni d'uso di Azure Active Directory.

  - Azure Active Directory Identity Protection.

  - Azure Active Directory Privileged Identity Management.

  - Controllo accessi di Azure Active Directory.

  -   Password di protezione di Azure Active Directory.

  -   Azure Active Directory B2B.

### <a name="enable-phase---intune"></a>Fase di attivazione - Intune

> [!IMPORTANT]
> FastTrack non supporta la classica gestione del PC di Windows 10 con Intune. FastTrack supporta solo la gestione di Windows 10 tramite la gestione di dispositivi mobili Intune (MDM).

Fornire indicazioni su come:

-   Configurare le identità utilizzate da Intune, sfruttando Active Directory locale o le identità cloud (Azure Active Directory).

-   Licenze per gli utenti finali.

-   Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.

-   Configurare l’autorità della gestione dei dispositivi mobili (MDM), in base alle esigenze di gestione, tra cui:

    -   Configurare Intune come autorità MDM.

    -   Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.

    -   Esplorare il portale di amministrazione di Intune per trovare informazioni su utenti e dispositivi.

    -   Configurare ruoli di Intune (operatore dell’help desk, amministratori e così via)

    -   Configurare criteri e servizi di gestione MDM come:

        -   Distribuire l'app per ogni piattaforma supportata tramite collegamenti Web, MSI e/o collegamenti diretti.

        -   Distribuire Office ProPlus su dispositivi Windows 10.

        -   Volume purchase program per la distribuzione di app, tra cui VPP di Apple, Windows Store for Business e Play for Work Store di Google.

        -   Distribuzione di posta elettronica, reti wireless e profili VPN se si ha un'autorità di certificazione esistente, un'infrastruttura Wi-Fi o VPN nell'organizzazione.

        -   Configurare Microsoft Intune Exchange Connector (se applicabile).

        -   Profili di configurazione dei dispositivi per le piattaforme di dispositivi supportate.

    -   Condizionale criteri di accesso condizionale.

    -   Configurare e distribuire criteri di protezione delle app di Intune per ogni piattaforma supportata.

    -   Preparazione delle app line-of-business per i criteri di protezione delle app di Intune, con indicazioni sulle opzioni disponibili.

    -   Registrare i dispositivi di ogni piattaforma supportata su Intune o Configuration Manager con il servizio Microsoft Intune.

    -   Connettersi al data warehouse di Intune.

    -   Integrare Intune con:
        -   Visualizzatore del team per assistenza remota (è necessario un abbonamento al visualizzatore del team).

        -   Soluzioni per i partner di Mobile Threat Defense (è necessario un abbonamento alla soluzione partner di Mobile Threat Defense).

        -   Le soluzioni di gestione delle spese per telecomunicazioni (è necessario un abbonamento alla soluzione di gestione delle spese per telecomunicazioni).

        -   Microsoft Defender Advanced Threat Protection (sono necessarie le licenze di Windows E5 o Microsoft 365 E5).

    -   Configurare gli aggiornamenti software per le piattaforme supportate applicabili.

    -   Risorse per la pianificazione dell'adozione da parte degli utenti.

- Configurare Windows AutoPilot:

    - Configurare e impostare Microsoft Intune per Windows Autopilot.

    - Configurare i gruppi dinamici di Azure Active Directory

    - Aggiungere il marchio aziendale in Azure AD.

    - Creare e assegnare dispositivi ai profili Windows Autopilot, ad esempio un profilo di Windows Autopilot che limita la creazione di account di amministratore locale.

    - Personalizzare la Configurazione guidata (OOBE) per rispettare i requisiti dell’organizzazione.

    - Configurare la registrazione automatica MDM in Azure AD e Intune.

    > [!NOTE]
    > Configurare Windows Autopilot all'esterno di Intune non rientra nell'offerta FastTrack.

### <a name="enable-phase---co-management"></a>Fase di attivazione - Co-gestione

Fornire indicazioni su come:

-   Licenze per gli utenti finali.

-   Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi (se Intune non è installato).

-   Configurare Azure Active Directory per la registrazione automatica MDM.

-   Configurare l’aggiunta ad Azure Active Directory ibrido.

-   Configurare Cloud Management Gateway.

-   Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.

-   Preparare Intune (se Intune non è installato):

    -   Configurare l’autorità della gestione dei dispositivi mobili (MDM), in base alle esigenze di gestione, tra cui:

    -   Configurare Intune come autorità MDM.

    -   Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.

    -   Esplorare il portale di amministrazione di Intune per trovare informazioni su utenti e dispositivi.

    -   Configurare ruoli di Intune (operatore dell’help desk, amministratori e così via)

    -   Configurare e distribuire criteri di protezione delle app di Intune per ogni piattaforma supportata.

    -   Registrare i dispositivi Windows 10 in Intune.

- Abilitare la co-gestione nella console di Configuration Manager.

- Passare ai carichi di lavoro in Intune.

- Monitorare l'attività di co-gestione nel proprio ambiente.

### <a name="enable-phase--azure-information-protection"></a>Fase di attivazione - Azure Information Protection

Fornire indicazioni su: 

- Attivare e configurare il tenant del cliente.

- Creare e configurare etichette e criteri.

- Applicare la protezione delle informazioni ai documenti. 

- Classificare ed etichettare automaticamente le informazioni nelle app di Office, come Word, PowerPoint, Excel e Outlook, che eseguono Windows e con il client di Azure Information Protection.

- Utilizzare file inattivi con lo scanner di Azure Information Protection.

- Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.

Sono inoltre disponibili indicazioni per i clienti che vogliono applicare la protezione con Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME) e prevenzione della perdita dei dati (DLP).

> [!NOTE]
> **Per saperne di più** consultare [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Passaggi successivi

[Offerta FastTrack per EMS - Proprie responsabilità](EMS-your-responsibilities.md)
