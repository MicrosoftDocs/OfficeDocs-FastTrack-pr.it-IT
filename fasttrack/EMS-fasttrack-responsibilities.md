---
title: Responsabilità di FastTrack
description: Responsabilità di FastTrack quando i clienti utilizzano FastTrack Center benefit per EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: ca5de05adc154a6adb0119fd71de46280cb4cb23
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016912"
---
# <a name="fasttrack-responsibilities"></a>Responsabilità di FastTrack

FastTrack ha le seguenti responsabilità durante la procedura di onboarding.

## <a name="general"></a>Generale

-   Fornire assistenza al supporto remoto per le attività di configurazione necessarie come elencato nelle descrizioni dettagliate delle fasi.

-   Fornire documentazione disponibile, strumenti software e console di amministrazione che consentono di ridurre o eliminare le attività di configurazione.

## <a name="initiate-phase"></a>Fase di avvio

-   Collaborare con l'utente per iniziare l'onboarding.

-   Definire i servizi da caricare.

## <a name="assess-phase"></a>Fase di valutazione

-   Fornire una panoramica sull'amministrazione.

-   Fornire indicazioni su:

    -   Esigenze di DNS, di rete e di infrastruttura.

    -   Esigenze del client (Internet browser, sistema operativo client e esigenze dei servizi).

    -   Identità dell'utente e provisioning.

    -   Abilitazione dei servizi idonei che sono stati acquistati e definiti come parte dell'onboarding.

-   Stabilire la sequenza temporale per le attività di correzione.

-   Fornire un elenco di controllo di correzione per Intune e Azure AD Premium.

## <a name="remediate-phase"></a>Fase di correzione

-   Tenere conferenze telefoniche con l'utente in base alla pianificazione concordata per esaminare lo stato di avanzamento delle attività di correzione, ad esempio la guida per i prerequisiti di installazione prima di onboarding di un servizio cloud Microsoft.

## <a name="enable-phase"></a>Fase di attivazione:
Fornire indicazioni su:

-   Attivazione del tenant o della sottoscrizione del servizio Microsoft online.

-   Configurazione di protocolli TCP/IP e porte del firewall.

-   Configurazione del DNS per servizi.

-   Convalida della connettività ai servizi online Microsoft.

-   Per un ambiente a foresta singola:

    -   Installazione di un server di sincronizzazione della directory tra i servizi di dominio Active Directory e i Microsoft Online Services idonei (solo indicazioni se necessario).

    -   Configurazione dell'autenticazione gestita (sincronizzazione hash delle password o autenticazione pass-through) con lo strumento Azure Active Directory Connect. (solo indicazioni se necessario).

        > [!NOTE]
        > Lo sviluppo e l'implementazione di estensioni di regole personalizzate non sono disponibili nell'ambito.

-   Per una singola foresta quando la destinazione è identità federative: installazione e configurazione di Active Directory Federation Services (AD FS) per l'autenticazione di dominio locale con Intune in una configurazione a sito singolo e a tolleranza di errore, se necessario.

    > [!NOTE]
    > Per tutte le configurazioni di più foreste, le distribuzioni AD FS non rientrano nell'ambito.

-   Verifica della funzionalità Single Sign-on (SSO), se distribuita.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Fase di abilitazione-Microsoft Azure Active Directory Premium

Fornire indicazioni su:

- Attivazione del tenant di Azure AD Premium.

- Configurazione delle porte del firewall.

- Configurazione del DNS per servizi.

- Convalida della connettività ai servizi di Azure AD Premium.

- Per un ambiente a foresta singola:

  -   Installazione di una sincronizzazione della directory tra servizi di dominio Active Directory (AD DS) e Azure AD Connect, se necessario.

  -   Configurazione di un metodo di autenticazione (sincronizzazione hash delle password o autenticazione pass-through) con lo strumento Azure AD Connect.

- Per un ambiente con più foreste:

  -   Installazione di Azure AD Connect Synchronization, configurata per scenari a più foreste.
- Per gli ambienti con una o più foreste:
  - Configurazione dell'Autenticazione pass-through di Azure Active Directory, se necessario.
  - Configurazione dell'Accesso Single Sign-On facile di Azure Active Directory, se necessario.
    > [!NOTE]
    > L'Autenticazione pass-through di Azure Active Directory per ambienti con più foreste è supportata se sono presenti trust tra le foreste di Active Directory e se il routing dei suffissi nome è configurato correttamente. È possibile installare ulteriori agenti su più server locali per fornire disponibilità elevata per le richieste di accesso.

  - Per ulteriori informazioni, vedere [Autenticazione pass-through di Azure Active Directory: avvio rapido](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) e [Accesso Single Sign-On facile di Azure Active Directory: guida introduttiva](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Per ulteriori informazioni sui limiti dell'autenticazione pass-through, vedere [Autenticazione pass-through di Azure Active Directory: limitazioni correnti](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Per ulteriori informazioni sui problemi relativi all'accesso Single Sign-On facile, vedere [Risolvere i problemi relativi all'accesso Single Sign-On facile di Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > Sincronizzazione hash delle password e writeback delle password supportano più foreste. Tuttavia, gli altri scenari writeback non sono supportati.

  - Configurazione della sincronizzazione tra insiemi di strutture di Active Directory locali e directory di Microsoft Azure Active Directory Premium (Azure Active Directory).

    > [!NOTE]
    > Lo sviluppo e l'implementazione di estensioni di regole personalizzate non sono disponibili nell'ambito.

- Per una singola foresta quando la destinazione è identità federative:

  -   Installazione e configurazione di AD FS per l'autenticazione di domini locali con Azure AD Premium in una configurazione a tolleranza di errore a sito singolo (se necessario).

  > [!NOTE]
  > Per tutte le configurazioni di più foreste, le distribuzioni AD FS non rientrano nell'ambito.

- Verifica della funzionalità SSO (se distribuita).

### <a name="enable-phase---azure-ad-premium--with-azure-ad-connect-and-ad-fs"></a>Enable Phase-Azure AD Premium--con Azure AD Connect e AD FS

Fornire indicazioni sulla configurazione:

- Provisioning degli utenti, inclusa la gestione delle licenze.

- Sincronizzazione della directory di Azure AD Connect (con password writeback e sincronizzazione hash delle password).

  - ReImpostazione della password di Azure Active Directory Self Service (SSPR).

  - Autenticazione a più fattori di Azure.

  - Fino a tre (3) o più software come un'applicazione di servizio (SaaS) integrazione con Single Sign-on (SSO) dal [Marketplace di Azure Active Directory](https://azure.microsoft.com/marketplace/active-directory/).

  - Provisioning automatico degli utenti per le applicazioni SaaS preintegrate, come indicato nell' [elenco delle app di integrazione dell'applicazione](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list), limitate al solo provisioning in uscita.

  - Schermata di accesso personalizzata, tra cui logo, testo e immagini.

  - Gruppi self-service e dinamici (gruppi).

  - Proxy di applicazione di Azure Active Directory.

  - Azure Active Directory Connect Health.

  - Accesso condizionale di Azure Active Directory.

  - Condizioni di utilizzo di Azure Active Directory.

  - Protezione dell'identità di Azure Active Directory.

  - Gestione delle identità con privilegi di Azure Active Directory.

  - Recensioni di Azure Active Directory Access.

### <a name="enable-phase---intune"></a>Attiva fase-Intune

> [!IMPORTANT]
> FastTrack non supporta Windows 10 Classic PC Management con Intune. FastTrack supporta solo Windows 10 Management tramite la gestione dei dispositivi mobili (MDM) di Intune.

Fornire **indicazioni** su:

-   Configurazione delle identità per l'utilizzo da parte di Intune, sfruttando le identità di Active Directory o cloud locali (Azure Active Directory).

-   Gestione delle licenze per gli utenti finali.

-   Aggiunta di utenti alla sottoscrizione di Intune, definizione dei ruoli di amministratore IT e creazione di gruppi di utenti e dispositivi.

-   Configurare l'autorità di gestione dei dispositivi mobili, in base alle proprie esigenze di gestione, tra cui:

    -   Impostazione di Intune come autorità MDM.

    -   Configurazione dei gruppi di test da utilizzare per convalidare i criteri di gestione MDM.

    -   Esplorare il portale di amministrazione di Intune per individuare le informazioni su utenti e dispositivi.

    -   Impostazione dei ruoli di Intune (operatore del supporto tecnico, amministratori e così via)

    -   Configurazione di criteri e servizi di gestione MDM come:

        -   Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web, MSI e/o Deep Links.

        -   Distribuzione di Office ProPlus su dispositivi Windows 10.

        -   Programmi di acquisto dei volumi per la distribuzione di app, tra cui VPP di Apple, Windows Store for business e l'archivio di riproduzione per il lavoro di Google.

        -   Distribuzione di messaggi di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione esistente, di un'infrastruttura Wi-Fi o VPN nell'organizzazione.

        -   Configurazione del connettore di Microsoft Intune Exchange (se applicabile).

        -   Profili di configurazione dei dispositivi per le piattaforme dispositivo supportate.

    -   Impostazione dei criteri di accesso condizionale.

    -   Configurazione e distribuzione dei criteri di protezione delle app di Intune per ogni piattaforma supportata.

    -   Preparazione delle app line-of-business (LOB) per i criteri di protezione delle app di Intune, con indicazioni sulle opzioni disponibili.

    -   La registrazione di dispositivi di ogni piattaforma supportata per Intune o Configuration Manager con il servizio Microsoft Intune.

    -   Connessione al data warehouse di Intune.

    -   Integrazione di Intune con:
        -   Visualizzatore team per assistenza remota (è necessario un abbonamento al visualizzatore del team).

        -   Soluzioni per dispositivi mobili per la difesa delle minacce (è richiesta la sottoscrizione della soluzione per dispositivi mobili per la difesa).

        -   Telecom Expense Management Solutions (è richiesta la sottoscrizione della soluzione Telecom Expense Management).

        -   Windows Defender Advanced Threat Protection (sono necessarie licenze Windows E5 o Microsoft 365 E5).

    -   Configurazione degli aggiornamenti software per le piattaforme supportate applicabili.

    -   Risorse per la pianificazione dell'adozione degli utenti.

- Configurazione di Windows Autopilot:

    - Configurazione e installazione di Microsoft Intune per Windows Autopilot.

    - Configurare i gruppi dinamici di Azure AD

    - Aggiungere il marchio dell'azienda in Azure AD.

    - Creare e assegnare i dispositivi ai profili Autopilot di Windows (ad esempio, un profilo di Windows Autopilot che limita la creazione dell'account amministratore locale).

    - Personalizzare l'out-of-Box-Experience (OOBE) per conformarsi ai requisiti dell'organizzazione.

    - Configurazione della registrazione automatica MDM in Azure AD e Intune.

    > [!NOTE]
    > La configurazione del pilota automatico di Windows all'esterno di Intune non rientra nell'ambito del vantaggio FastTrack.

### <a name="enable-phase---co-management"></a>Abilitare la fase di cogestione

Fornire indicazioni su:

-   Gestione delle licenze per gli utenti finali.

-   Aggiunta di utenti alla sottoscrizione di Intune, definizione dei ruoli di amministratore IT e creazione di gruppi di utenti e dispositivi (se Intune non è installato).

-   Configurazione di Azure Active Directory per la registrazione automatica MDM.

-   Configurare la join di Azure Active Directory ibrido.

-   Configurare il gateway di gestione cloud.

-   Aggiunta di utenti alla sottoscrizione di Intune, definizione dei ruoli di amministratore IT e creazione di gruppi di utenti e dispositivi.

-   Preparare Intune (se Intune non è installato):

    -   Configurare l'autorità di gestione dei dispositivi mobili, in base alle proprie esigenze di gestione, tra cui:

    -   Impostazione di Intune come autorità MDM.

    -   Configurazione dei gruppi di test da utilizzare per convalidare i criteri di gestione MDM.

    -   Esplorare il portale di amministrazione di Intune per individuare le informazioni su utenti e dispositivi.

    -   Impostazione dei ruoli di Intune (operatore del supporto tecnico, amministratori e così via)

    -   Configurazione e distribuzione dei criteri di protezione delle app di Intune per ogni piattaforma supportata.

    -   Registrazione di dispositivi Windows 10 a Intune.

- Abilitare la coGestione nella console di Configuration Manager.

- Passare i carichi di lavoro a Intune.

- Monitorare l'attività di cogestione nell'ambiente.

> [!NOTE]
> **Vuoi saperne di più?** vedere [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Passaggi successivi

[FastTrack benefit for EMS-le tue responsabilità](EMS-your-responsibilities.md)
