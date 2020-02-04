---
title: Fasi del processo di onboarding e migrazione
description: Fasi del FastTrack Center Benefit
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 2/04/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.openlocfilehash: 02f5a1c0c2bbbe2526f0ee0fcea9da844dae1f6a
ms.sourcegitcommit: 7365d80b2e4291e547c2d84b94da02697221abc9
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 02/03/2020
ms.locfileid: "41676804"
---
# <a name="onboarding-phases"></a>Fasi di onboarding

Se si usano i [Servizi e piani idonei](M365-eligible-services-and-plans.md) per ottenere Microsoft Azure Active Directory Premium, Microsoft Intune e Azure Information Protection pronti all’uso, nel processo sono coinvolte diverse fasi. Le sezioni seguenti descrivono ogni fase del processo di onboarding.

L'onboarding include quattro fasi principali:

![Le quattro fasi del processo di onboarding del FastTrack](./media/O365-Onboarding-Phases.png)


## <a name="initiate-phase"></a>Fase di avvio

Dopo aver acquistato i tipi e il numero appropriato di licenze, attenersi alle istruzioni nell'e-mail di conferma dell'acquisto per associare le licenze al tenant esistente o nuovo. Microsoft verifica quindi l'idoneità per il FastTrack Center Benefit e tenta di contattare l'utente per offrire assistenza nell’onboarding.

> [!NOTE]
> È anche possibile richiedere assistenza dal [FastTrack Center](https://go.microsoft.com/fwlink/?linkid=780698), se si è pronti a distribuire questi servizi per l'organizzazione.

### <a name="to-request-assistance"></a>Per richiedere assistenza

1. Accedere al [sito di FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).
2. Selezionare **FastTrack**.
3. Selezionare **Servizi**.
4. Completare il **modulo di richiesta di assistenza con Microsoft 365**.

Una volta contattato il supporto tecnico per l'onboarding, verrà impostata la pianificazione delle riunioni online.

I partner Microsoft possono anche ricevere assistenza tramite il [sito FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) per conto di un cliente. A questo scopo:

1. Accedere al [sito di FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).
2. Selezionare **FastTrack**.
3. Selezionare **Clienti personali**.
4. Cercare il cliente desiderato o selezionarlo nell'elenco di clienti.
5. Selezionare **Servizi**.
6. Completare il **modulo di richiesta di assistenza con Microsoft 365**.

Dopo l'avvio del supporto per l’onboarding, FastTrack configurerà una programmazione delle riunioni online con l'utente per discutere il processo di onboarding, verificare i dati e configurare una riunione di avvio.

![Fase di avvio dell’onboarding](./media/ft-initiate-phase.png)

## <a name="assess-phase"></a>Fase di valutazione

Una volta avviato il processo di onboarding, il centro FastTrack assisterà l'utente nel valutare l'ambiente di origine e i requisiti. Vengono utilizzati strumenti per raccogliere dati e gli specialisti Fast Track guideranno l'utente nella stima dei requisiti dell’Active Directory e nella valutazione di browser, sistemi operativi del client, DNS (Domain Name System), rete, infrastruttura e sistema di identità, in caso fossero necessarie modifiche per l'onboarding.

Il centro FastTrack fornisce, inoltre, all'utente, delle linee guida per l'adozione corretta dei servizi idonei.

In base all'impostazione corrente, viene suggerito un piano di correzione che fornisce all'ambiente di origine i requisiti minimi per l'onboarding a EMS e, se necessario, per la migrazione dei dati e/o delle cassette postali. Verranno inoltre stabilite delle chiamate di controllo appropriate per la fase di correzione.

![Fase di valutazione dell’onboarding](./media/ft-assess-phase.png)

## <a name="remediate-phase"></a>Fase di correzione
L'utente eseguirà le attività del piano di correzione sull'ambiente di origine, per soddisfare i requisiti per l’onboarding e adottare ciascun sevizio (se necessario).

![Fase di correzione dell’onboarding](./media/ft-remediate-phase.png)

Prima di iniziare la fase di attivazione, vengono verificati i risultati delle attività di correzione per verificare che l'utente sia pronto a procedere.

## <a name="enable-phase"></a>Fase di attivazione
Una volta completate tutte le attività di correzione, il progetto passa alla configurazione dell'infrastruttura di base per l'utilizzo dei servizi e per il provisioning di tutti i servizi cloud EMS idonei.

**Fase di attivazione - Funzionalità di base**

L'onboarding di base prevede il provisioning di servizi e l'integrazione di identità e tenant. Include anche la procedura per fornire una base per l'onboarding di servizi online come Azure AD Premium, Intune e Azure Information Protection.

![Fase di attivazione dell’onboarding - Funzionalità di base](./media/ft-enable-phase-core-01.png)

![Fase di attivazione dell’onboarding - Funzionalità di base](./media/ft-enable-phase-core-02.png)
> [!NOTE]
> WAP è l'acronimo di Web Application Proxy. SSL è l'acronimo di Secure Sockets Layer. SDS è l'acronimo di School Data Sync. Per ulteriori informazioni su SDS, vedere [Introduzione a Microsoft School Data Sync](https://go.microsoft.com/fwlink/?linkid=871480).

> [!NOTE]
> Un metodo di autenticazione gestita include, tra l’altro, la sincronizzazione hash con password. L'integrazione delle identità è un'attività che non include la migrazione o la rimozione di metodi di autenticazione esistenti, come quelli gestiti o federati.

### <a name="enable-phase---azure-ad-premium"></a>Fase di attivazione - Azure AD Premium

È possibile configurare l'ambiente di Azure Active Directory con la sincronizzazione della directory di Azure Active Directory Connect e Active Directory Federation Services (AD FS), in base alle esigenze.

Per gli scenari di Azure AD Premium che includono la sincronizzazione delle identità locali nel cloud, è possibile aggiungere amministratori e utenti IT all'abbonamento, configurare prerequisiti di gestione, configurare Azure AD Premium, configurare la sincronizzazione delle directory con l'autenticazione gestita e ADFS tramite lo strumento Azure AD Connect, configurare gli utenti di test e convalidare i casi di utilizzo principali per il servizio.

La configurazione di Azure AD Premium include l'abilitazione delle caratteristiche seguenti:

-   Reimpostazione password self-service (SSPR) di Azure Active Directory.

-   Azure Multi-Factor Authentication (Azure MFA).

-   Fino a tre (3) o più integrazioni di applicazioni software come un servizio (SaaS) con Single Sign-on (SSO) da [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

-   Il provisioning automatico degli utenti per le applicazioni SaaS preintegrate, come indicato [nell'elenco delle esercitazioni di integrazione di app](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list), solo per il provisioning in uscita.

-   Schermata di accesso personalizzata, tra cui il logo, il testo e le immagini.

-   Gruppi dinamici e self-service (Gruppi).

-   Azure Active Directory Application Proxy.

-   Azure Active Directory Connect Health.

-   Accesso condizionale di Azure Active Directory.

-   Condizioni d'uso di Azure Active Directory.

-   Azure Active Directory Identity Protection.

-   Azure Active Directory Privileged Identity Management.

-   Controllo accessi di Azure Active Directory.

![Fase di attivazione dell’onboarding - Azure AD Premium](./media/ft-enable-phase_aad-premium_adconnect_adfed.png)

### <a name="enable-phase---intune"></a>Fase di attivazione - Intune

Per Intune, una procedura guidata assiste l’utente le prime volte che usa Microsoft Intune per gestire i dispositivi. I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili. I passaggi possono includere:

-   Licenze per gli utenti finali. È anche disponibile assistenza per l’attivazione delle licenze multilicenza per il tenant del servizio cloud Microsoft (se necessario).

-   Configurare le identità utilizzate da Intune, sfruttando Active Directory locale o le identità cloud.

-   Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.

-   Configurare l'autorità di Gestione dispositivi mobili (MDM), a seconda delle esigenze di gestione, tra cui:

    -   Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.

-   Fornire le indicazioni di MDM per:

    -   Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.

    -   Configurare criteri e servizi di gestione MDM come:

        -   Distribuzione dell'applicazione per ogni piattaforma supportata tramite collegamenti Web e/o collegamenti diretti.

        -   Criteri di accesso condizionale.

        -   Distribuzione di posta elettronica, reti wireless e profili di rete virtuale privata VPN se si ha un'autorità di certificazione esistente, un'infrastruttura Wi-Fi o VPN nell'organizzazione.

        -   Configurazione di Microsoft Intune Exchange Connector (se applicabile).

        -   Connettersi al data warehouse di Intune

        -   Integrare Intune con:
            -   Visualizzatore del team per assistenza remota (è necessario un abbonamento al visualizzatore del team).

            -   Soluzioni per i partner di Mobile Threat Defense MTD (è necessario un abbonamento a Mobile Threat Defense).

            -   Soluzione di gestione delle spese per telecomunicazioni (è necessario un abbonamento alla soluzione di gestione delle spese per telecomunicazioni).

            -   Windows Defender Advanced Threat Protection (sono necessarie le licenze di Windows E5 o Microsoft 365 E5).

    -   Registrare i dispositivi di ogni [piattaforma supportata](https://technet.microsoft.com/library/dn600287.aspx) in Intune.

-   Offrire indicazioni per la protezione delle app su:

    -   Configurare criteri di protezione delle app per ogni piattaforma supportata.

    -   Configurare i criteri di accesso condizionale per app gestite.

    -   Destinare i gruppi di utenti appropriati con i criteri MAM sopra descritti.

    -   Usare i report sull'utilizzo delle applicazioni gestite.

-   Fornire indicazioni per la gestione del PC su:

    -   Se necessario, installare il software client di Intune.

    -   Usare dei report software e hardware disponibili in Intune.

    > [!IMPORTANT]
    > FastTrack non supporta la classica gestione del PC di Windows 10 con Intune. FastTrack supporta solo la gestione di Windows 10 tramite la gestione di dispositivi mobili Intune (MDM).

#### <a name="windows-autopilot"></a>Windows Autopilot

FastTrack può aiutare a semplificare il provisioning del dispositivo con Autopilot di Windows e Intune, fornendo nuovi dispositivi agli utenti finali senza la necessità di creare, gestire e applicare immagini personalizzate del sistema operativo ai dispositivi.

FastTrack supporta gli scenari di Autopilot seguenti:

- **Self-service Azure AD:** i dispositivi si connettono ad Azure AD ed eseguono l’iscrizione a Intune. Questo scenario è supportato con l’utilizzo di Windows 10 1703 e le versioni più recenti.

- **Self-service AAD ibrido:** i dispositivi si connettono a versioni locali di AD e Azure AD ed eseguono l’iscrizione a Intune. Questo scenario è supportato con l’utilizzo di Windows 10 1809 e le versioni più recenti.

- **Provisioning automatico:** i dispositivi si connettono automaticamente ad Azure AD. Questo scenario è supportato con l’utilizzo di Windows 1809 e le versioni più recenti.

    > [!IMPORTANT]
    > FastTrack non supporta scenari con Autopilot avviati da Configuration Manager.

La procedura per configurare Autopilot di Windows dipende dall'ambiente di origine e può includere:

- Configurare e impostare Microsoft Intune per Windows Autopilot.

- Configurare i gruppi dinamici di Azure Active Directory

- Aggiungere il marchio aziendale in Azure AD.

- Creare e assegnare dispositivi ai profili Windows Autopilot, ad esempio un profilo di Windows Autopilot che limita la creazione di account di amministratore locale.

- Personalizzare la Configurazione guidata (OOBE) per rispettare i requisiti dell’organizzazione.

- Configurare la registrazione automatica MDM in Azure AD e Intune.

#### <a name="deploy-outlook-for-ios-and-android-securely"></a>Distribuire Outlook per iOS e Android in modo sicuro

FastTrack può essere di aiuto nella distribuzione sicura di Outlook per iOS e Android nell'organizzazione, per garantire che gli utenti abbiano installato tutte le app necessarie.

I passaggi per la distribuzione sicura di Outlook Mobile per iOS e Android con Intune variano in base all'ambiente di origine e possono includere:

- Scaricare Outlook per iOS e Android, Microsoft Authenticator e l'app Portale aziendale Intune tramite Apple App Store o Google Play Store.
- Fornire inoltre indicazioni sulla configurazione di:
    - Outlook per iOS e Android, Microsoft Authenticator e l'app Portale aziendale Intune.
    - Criteri di protezione delle app
    - Criteri di accesso condizionale
    - Criteri di configurazione dell’app

    > [!IMPORTANT]
    > Il team di FastTrack non supporta la protezione di Outlook per iOS e Android con i criteri delle cassette postali dei dispositivi mobili di Exchange.

#### <a name="co-management"></a>Co-gestione

Le guide di FastTrack forniscono assistenza nella gestione simultanea dei dispositivi Windows 10 sia con Configuration Manager che con Intune. I passaggi esatti dipendono dall'ambiente di origine e possono includere:

- Illustrare i vantaggi della co-gestione.

- Assegnare una licenza agli utenti finali. FastTrack offre anche assistenza su come attivare le licenze multilicenza per il tenant del servizio cloud Microsoft (se necessario).

- Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e/o le identità cloud.

- Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.

- Offrire indicazioni su come passare da Intune integrato con System Center Configuration Manager (ibrido) a Intune autonomo.

- Fornire indicazioni su come configurare Azure Active Directory per la registrazione automatica MDM.

- Fornire indicazioni su come configurare Aggiunta ad Azure Active Directory ibrido.

- Offrire indicazioni su come configurare il gateway di gestione cloud

- Abilitare la co-gestione nella console di Configuration Manager.

- Configurare i carichi di lavoro supportati che si desidera far passare a Intune.

- Installare il client Configuration Manager nei dispositivi registrati di Intune.

- Fornire istruzioni su come monitorare l'attività di co-gestione nel proprio ambiente.

FastTrack fornisce all'utente, inoltre, delle linee guida per l'adozione corretta dei servizi idonei.

![Fase di attivazione dell’onboarding - Intune](./media/ft-enable-phase_intune_mam.png)

![Fase di attivazione dell’onboarding - Intune](./media/ft-enable-phase_intune_mdm-mam_cloudonly.png)

![Fase di attivazione dell’onboarding - Co-gestione](./media/ft-9-enable-phase-comanagement.png)

#### <a name="enable-phase--azure-information-protection"></a>Fase di attivazione - Azure Information Protection

Ai clienti vengono fornite indicazioni su come: 

- Attivare e configurare il tenant.
- Creare e configurare etichette e criteri.
- Applicare la protezione delle informazioni ai documenti. 
- Classificare ed etichettare automaticamente le informazioni nelle app di Office, come Word, PowerPoint, Excel e Outlook, che eseguono Windows e con il client di Azure Information Protection.
- Utilizzare file inattivi con lo scanner di Azure Information Protection.
- Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.

Sono inoltre disponibili indicazioni per i clienti che vogliono applicare la protezione con Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME) e prevenzione della perdita dei dati (DLP).

> [!NOTE]
> **Per saperne di più** consultare [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Passaggi successivi

[Offerta FastTrack per EMS - Responsabilità Microsoft](EMS-fasttrack-responsibilities.md)
