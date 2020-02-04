---
title: Responsabilità di FastTrack per il governo degli Stati Uniti di Office 365
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 2/04/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: Gli esperti di FastTrack hanno le seguenti responsabilità durante la procedura di onboarding.
ms.openlocfilehash: 502f3c7595de510caf98b51b7b2d0bd274d076e8
ms.sourcegitcommit: 7365d80b2e4291e547c2d84b94da02697221abc9
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 02/03/2020
ms.locfileid: "41677032"
---
# <a name="fasttrack-responsibilities-for-office-365-us-government"></a>Responsabilità di FastTrack per il governo degli Stati Uniti di Office 365

Gli esperti di FastTrack hanno le seguenti responsabilità durante la procedura di onboarding.  
  
## <a name="general"></a>Generale

- Viene fornita assistenza al supporto remoto per un corretto sviluppo della pianificazione e alla relativa implementazione e per le necessarie attività di configurazione, come descritto nelle fasi riportate.
- Offrire documentazione disponibile e strumenti software, console di amministrazione e script che consentono di ridurre o eliminare le attività di configurazione e risorse per una corretta configurazione.   
    
## <a name="initiate-phase"></a>Fase di avvio

- Collaborare per comprendere lo scopo, gli obiettivi aziendali e i piani di utilizzo per il servizio. 
- Collaborare all'utilizzo dei servizi di collaborazione di Office 365 (come Microsoft Teams) per avviare la procedura di onboarding. 
- Definire i servizi da caricare. 
    
## <a name="assess-phase"></a>Fase di valutazione

- Effettuare una chiamata per fornire assistenza in merito a una corretta adozione da parte dell'utente.  
- Fornire una panoramica sull'amministrazione.  
- Fornire indicazioni su: 
  - Esigenze relative al DNS, alla rete e all'infrastruttura.  
  - Esigenze del client (esigenze di browser, sistema operativo client, dispositivo mobile e servizi).
  - Identità dell'utente e provisioning. 
  - Abilitare i servizi che sono acquistati e definiti come parte dell'onboarding.
  - Favorire l'adozione corretta e il valore del servizio.   
- Stabilire la sequenza temporale per le attività di correzione.
- Fornire un elenco di controllo della correzione.   
- Valutare l'infrastruttura SharePoint Server 2013 o SharePoint Server 2016, ad esempio:  
  - Prerequisiti per l'ambiente ibrido di SharePoint Online.  
  - Idoneità dell'infrastruttura locale per le funzionalità dell'ambiente ibrido di SharePoint Online.  
  - Accesso agli endpoint SharePoint Online necessari. 
  - Gruppi di destinatari per l'ambiente ibrido di OneDrive for Business.    
- Valutare l'infrastruttura Lync o Skype for Business online, ad esempio:  
  - Strategia di distribuzione del client di Skype for Business supportato.  
  - Accesso agli endpoint.  
  - Qualità della connessione.  
  - Stime sulla larghezza di banda.  
  - Prerequisiti per supportare la configurazione server del dominio condiviso.  
  - Conformità di determinati utenti a spostarsi verso Skype for Business online.  
- Valutare l'infrastruttura di messaggistica, tra cui:   
  - Principi generali su flusso di posta e routing.  
  - Accesso client (compresi gli endpoint di accesso client pubblicati).  
  - Ambiente di messaggistica di origine per esigenze di integrazione. 
- Fornire indicazioni sulla migrazione dei dati se viene utilizzato il servizio di migrazione dei dati FastTrack Center e se si è idonei.
    
## <a name="remediate-phase"></a>Fase di correzione

- Effettuare conferenze telefoniche con l'utente in base a una pianificazione concordata per esaminare il progresso delle attività di correzione e una corretta pianificazione.   
- Offrire assistenza in merito all'esecuzione degli strumenti di valutazione che consentono di identificare e risolvere problemi e interpretare i risultati.
    
## <a name="enable-phase"></a>Fase di attivazione:

Fornire indicazioni su: 
- Valutazione del progresso relativo alla pianificazione del buon esito della procedura e determinazione dell'ulteriore supporto di cui si ha bisogno.    
- Attivazione del tenant di Office 365.
- Configurazione di protocolli TCP/IP e porte del firewall.   
- Configurazione del DNS per servizi.   
- Convalida di connettività a Office 365.   
- Connessione ad Active Directory locale con Azure Active Directory:   
  - Installazione di un server di sincronizzazione delle directory tra Active Directory Domain Services (AD DS) e Office 365, se necessario.   
  - Configurazione della sincronizzazione della password (hash password) su Office 365 (Azure Active Directory) con lo strumento Azure Active Directory Connect, se necessario.  
  - Per gli ambienti con una o più foreste:
      - Configurazione dell'autenticazione pass-through di Azure Active Directory, se necessario (non disponibile nei piani GCC High o DoD).
      - Configurazione di Azure Active Directory Single Sign-on seamless (SSO), se necessario (non disponibile nei piani GCC High o DoD).
    > [!NOTE]
    > L'Autenticazione pass-through di Azure Active Directory per ambienti con più foreste è supportata se sono presenti trust tra le foreste di Active Directory e se il routing dei suffissi nome è configurato correttamente. È possibile installare ulteriori agenti su più server locali per fornire disponibilità elevata per le richieste di accesso. Per ulteriori informazioni, vedere [Autenticazione pass-through di Azure Active Directory: avvio rapido](https://go.microsoft.com/fwlink/?linkid=860094) e [Accesso Single Sign-On facile di Azure Active Directory: guida introduttiva](https://go.microsoft.com/fwlink/?linkid=860095).[!NOTE]
    > Per ulteriori informazioni sui limiti dell'autenticazione pass-through, vedere [Autenticazione pass-through di Azure Active Directory: limitazioni correnti](https://go.microsoft.com/fwlink/?linkid=860356).[!NOTE]
    > Per ulteriori informazioni sui problemi relativi all'accesso Single Sign-On facile, vedere [Risolvere i problemi relativi all'accesso Single Sign-On facile di Azure Active Directory](https://go.microsoft.com/fwlink/?linkid=841926). 
- Per una singola foresta, se la destinazione è costituita dalle identità federative: 
  - Installazione e configurazione di AD FS per l'autenticazione di domini locali con Office 365 in un solo sito e configurazione a tolleranza di errore, se necessario.  
  - Installazione e configurazione di WAP per la pubblicazione dell'infrastruttura di AD FS su Internet, se necessario. 
    > [!NOTE]
    > Per tutte le configurazioni di più foreste, le distribuzioni di AD FS non rientrano nell'ambito. 
- Test sulla funzionalità SSO (Single Sign-On) se distribuita.   
- Favorire l'adozione corretta del servizio e aumentarne il valore.
    
## <a name="exchange-online"></a>Exchange Online

Fornire indicazioni su: 
- Creazione o aggiornamento di record DNS.    
- Abilitazione del routing di posta elettronica tra sistema di messaggistica di origine e ambienti Office 365.    
- Configurazione delle funzionalità di Exchange Online Protection (comprese quelle di Protezione avanzata dalle minacce per Exchange Online se disponibili nella propria sottoscrizione) e verifica che i record MX puntino a Office 365 per tutti i domini abilitati alla posta elettronica convalidati.   
- Configurazione ibrida tra l'organizzazione di Exchange singola in locale e Office 365 *o* tra più organizzazioni di Exchange locale e Office 365. 
- Configurazione della messaggistica unificata con Exchange Online (la messaggistica UNIFICAta non è disponibile nei piani di GCC DoD). 
    
Per ulteriori informazioni sulle responsabilità nella migrazione dei dati, vedere [Migrazione dei dati](O365-data-migration.md).
  
## <a name="sharepoint-online"></a>SharePoint Online

Fornire indicazioni su:
- Impostazione di provisioning incluse le licenze dell'utente.   
- Abilitazione alla creazione di siti per l'amministratore di SharePoint Online.   
- Pianificazione delle raccolte di siti.   
- Protezione del contenuto e gestione delle autorizzazioni.   
- Attivazione di siti personali e caratteristiche di social networking.   
- Configurazione delle caratteristiche di SharePoint Online.    
- Fornitura di indicazioni sulla migrazione dei dati se viene utilizzato il servizio di migrazione dei dati FastTrack Center e se si è idonei.  
- Valutazione della configurazione relativa all'infrastruttura della farm locale di SharePoint, necessaria per l'ambiente ibrido di SharePoint Online.    
- Utilizzo di strumenti e automazione per: 
  - Configurare le applicazioni del servizio di ricerca cloud in locale.    
  - Configurare l'attendibilità tra gli ambienti SharePoint locali e cloud.   
- Configurare i siti locali di SharePoint affinché usino le funzionalità dell'ambiente ibrido di SharePoint Online.
    
## <a name="onedrive-for-business"></a>OneDrive for Business

Fornire indicazioni su: 
- Identificazione delle opzioni di integrazione e della versione locale di SharePoint.    
- Identificazione delle opzioni di sincronizzazione e identità.   
- Selezione dell'opzione di implementazione:   
  - Implementazione just-in-time.  
  - Implementazione in più fasi (in sequenza e fasi).   
- Preparazione dell'ambiente locale alla distribuzione di OneDrive for Business:  
  - Identificazione del client di sincronizzazione OneDrive for Business corretto. 
  - Configurazione di DNS, porte di rete e firewall.   
- Assegnazione di licenze per l'utente finale.   
- Impostazione di gruppi di destinatari di SharePoint Online per controllare e regolare chi scarica OneDrive for Business.    
- Distribuzione del client di sincronizzazione OneDrive for Business su desktop.   
- Come configurare il reindirizzamento all'ambiente ibrido di SharePoint Online e OneDrive for Business (solo SharePoint 2013 e SharePoint 2016).  
- Migrazione dei dati se viene utilizzato il servizio di migrazione dei dati FastTrack Center e se si è idonei.
    
## <a name="skype-for-business-online"></a>Skype for Business Online

Fornire indicazioni su:
- Provisioning delle identità di Skype for Business per Office 365.   
- Abilitazione delle conferenze in linea, della messaggistica immediata (IM) e funzionalità di presenza per Office 365.  
- Creazione di account da associare ai dispositivi del sistema chat room supportati (fino a 10 account).    
- Configurazione di un ambiente server del dominio condiviso in grado di supportare Lync ibrido o scenari ibridi di Skype for Business online (se applicabile).   
- Abilitazione dell'audioconferenza:   
  - Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.   
  - Assegnazione di bridge per conferenze agli utenti con licenza 
- Abilitazione del sistema telefonico (non disponibile nei piani GCC High o DoD):  
  - Abilitazione del sistema telefonico e dell'onboarding relativo ai piani di chiamata (mercati idonei). 
  - Assegnazione di numeri agli utenti con licenza.  
  - Guida alla portabilità del numero locale tramite UI fino a 999.  
  - Supporto RS per la portabilità del numero locale superiore a 999.  
- Abilitazione di Skype for business meeting broadcast (non disponibile nei piani GCC High o DoD):  
  - Onboarding guidato per l'abilitazione di Skype for Business Meeting Broadcast.  
  - Configurazione aziendale per la federazione con il servizio Meeting Broadcast.
    
## <a name="microsoft-teams"></a>Microsoft Teams

Fornire indicazioni su:
- Conferma dei requisiti minimi.   
- Configurazione delle porte del firewall.  
- Configurazione DNS.  
- Conferma dell'abilitazione di Microsoft Teams sul tenant Office 365.   
- Abilitazione o disabilitazione delle licenze utente.  
- Distribuzione client di Microsoft Teams.    
- Funzionalità per amministratori e professionisti IT. 
- Componenti di base del prodotto.  
- Modelli di customer success.
    
## <a name="power-bi"></a>Power BI

Fornire indicazioni su:
- Revisione dei piani di sottoscrizione di Power BI.    
- Aggiunta del servizio Power BI.    
- Download dell'app Power BI Desktop.
    
## <a name="project-online"></a>Project Online

Fornire indicazioni su:  
- Revisione dei piani di sottoscrizione.  
- Verifica della funzionalità di SharePoint di base.    
- Aggiunta del servizio Project Online.  
- Aggiunta degli utenti a Project Online includendo la sincronizzazione del pool di risorse dell'organizzazione.  
- Verifica della funzionalità di Project Online di base creando un progetto.
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

Fornire una guida sulla conversione della rete Yammer Basic singola in una sola rete Yammer Enterprise.

> [!NOTE]
> Yammer Enterprise non è un componente di Office 365 US Government, ma può essere acquisito gratuitamente come offerta autonoma per ogni utente concesso in licenza per Office 365 in GCC. Questa offerta è attualmente limitata ai clienti che acquistano Office 365 GCC in contratti Enterprise e contratti di sottoscrizione Enterprise. Yammer non è disponibile nei piani GCC High o DoD.
  
## <a name="office-365-proplus"></a>Office 365 ProPlus

Fornire indicazioni su:
- Risoluzione dei problemi di implementazione.   
- Assegnazione dei contratti di licenza con l'utente finale utilizzando l'[interfaccia di amministrazione di Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704) e Windows PowerShell.  
- Installare Office 365 ProPlus dal portale di Office 365 tramite la tecnologia A portata di clic.   
- Installazione delle app di Office Mobile (ad esempio Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) sui dispositivi iOS, Android o Windows Mobile.   
- Configurazione delle impostazioni di aggiornamento usando lo strumento di distribuzione di Office 2016 oppure i modelli dei criteri di gruppo.   
- Configurazione di un solo server di distribuzione nel sito per Office 365 ProPlus, includendo una guida per la creazione del file configuration.xml da usare con lo strumento di distribuzione di Office 365.   
- Implementazione con System Center Configuration Manager, che include una guida per la creazione del pacchetto di System Center Configuration Manager.

    


