---
title: Prodotti e funzionalità
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che resegni l'ambiente di origine fino ai requisiti minimi per l'onboarding corretto.
ms.openlocfilehash: e49ada61aee869785f061bbebbee4ae14aaee045
ms.sourcegitcommit: 895a8b9df9a7cd26e27e95e5fd3145e7306c78e8
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/05/2021
ms.locfileid: "50464208"
---
# <a name="products-and-capabilities"></a>Prodotti e funzionalità

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Servizi e scenari supportati da FastTrack 

Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che resegni l'ambiente di origine ai requisiti minimi per l'onboarding corretto.

FastTrack fornisce indicazioni per aiutarti prima con le funzionalità di base (comuni per tutti i Microsoft Online Services) e quindi con l'onboarding di ogni servizio idoneo:

  - [Generale](#general)
  - [Sicurezza e conformità](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Desktop virtuale Windows](#windows-virtual-desktop)
  - [App Assure](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Per informazioni sulle previsioni dell’ambiente di origine di Office 365 U.S. Government, vedere [Previsioni dell’ambiente di origine di Office 365 U.S. Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations). 
 
## <a name="general"></a>Generale

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli della guida di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Onboarding di base</strong></td>
<td>  Forniamo indicazioni remote sull'onboarding di base, che implica il provisioning dei servizi, il tenant e l'integrazione delle identità. Include inoltre la procedura per fornire una base per i servizi di onboarding come Exchange Online, SharePoint Online e Microsoft Teams, inclusa una discussione su sicurezza, connettività di rete <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">e conformità.</a>  
  L'onboarding per uno o più servizi può iniziare al termine dell'onboarding di base.
</li>
</ul>  

<strong> Integrazione delle identità </strong>

Forniamo indicazioni remote per:
<ul>
<li>Preparazione delle identità di Active Directory locali per la sincronizzazione con Azure Active Directory (Azure AD), tra cui l'installazione e la configurazione di Azure AD Connect (a foresta singola o multipla) e delle licenze (incluse le licenze basate su gruppo).</li>
<li>Creazione di identità cloud, tra cui importazione in blocco e licenze, incluso l'uso delle licenze basate su gruppo.</li>
<li>Scelta e abilitazione del metodo di autenticazione corretto per il percorso cloud, Sincronizzazione hash password, Autenticazione pass-through o Active Directory Federation Services (AD FS).</li>
<li>Abilitazione di AD FS per i clienti con una singola foresta di Active Directory e identità sincronizzate con lo strumento Azure AD Connect. Questa operazione richiede Windows Server 2012 R2 Active Directory Federation Services 2.0 o versione successiva.</li>
<li>Migrazione dell'autenticazione da AD FS ad Azure AD tramite la sincronizzazione hash delle password o l'autenticazione pass-through.</li>
<li>Migrazione di app pre-integrate (come le app SaaS (Software-as-a-Service) della raccolta di Azure AD da AD FS ad Azure AD per Single #A0 (SSO).</li>
<li>Abilitazione delle integrazioni di app SaaS con SSO dalla raccolta di Azure AD.</li>
<li>Abilitazione del provisioning automatico degli utenti per le app SaaS pre-integrate, come indicato nell'elenco delle esercitazioni sull'integrazione delle <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">app</a> (limitato alle app SaaS della raccolta di Azure AD e solo al provisioning in uscita).  </li>
</td>

<td>  <strong>Abilitazione della rete </strong>  
  <br>Nell'ambito del vantaggio FastTrack, si consiglia di utilizzare le procedure consigliate per la connessione ai servizi cloud per garantire i massimi livelli di prestazioni di Microsoft 365.  
  
<strong>Foreste di Active Directory</strong> Il livello di foresta funzionale è impostato su Windows Server 2003 e successive, con la seguente configurazione della foresta:
<ul>
<li>  Una foresta unica di Active Directory.  </li>
<li>  Una singola foresta account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).  </li>
<li>  Più foreste account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).  </li>
<li>  Più foreste account di Active Directory con una delle foreste in posizione centrale nella foresta account di Active Directory contenente Exchange e/o Lync 2010, Lync 2013 o Skype for Business.  </li>
<li>  Più foreste account di Active Directory, ognuna con la propria organizzazione di Exchange.  </li>
<li>  Attività necessarie per la configurazione e l'integrazione del tenant con Azure Active Directory, se necessario.   </li>
</ul>
  <strong>Importante</strong>  <ul>
<li>  Per gli scenari di Active Directory a più foreste, se lync 2010, Lync 2013 o Skype for Business è distribuito, deve essere distribuito nella stessa foresta di Active Directory di Exchange.  </li>
<li>  Quando si implementano più foreste di Active Directory con più organizzazioni Exchange in una configurazione multi-ibrida di Exchange, gli spazi dei nomi dell'entità utente (UPN) condivisi tra foreste di origine non sono supportati. Gli spazi dei nomi SMTP primari tra organizzazioni di Exchange devono essere separati. Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=845444">Distribuzioni ibride con più insiemi di strutture di Active Directory</a>.  </li>
<li>  Per tutte le configurazioni di più foreste, la distribuzione di Active Directory Federation Services (AD FS) non è in ambito. Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 Apps</strong></td>
<td>  Vengono fornite indicazioni per la distribuzione remota per:
<ul>
<li>  Risoluzione dei problemi di implementazione.  </li>
<li>  Assegnazione dei contratti di licenza con l'utente finale e di licenze basate sul dispositivo utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.  </li>
<li>  Installare Microsoft 365 Apps dal portale di Office 365 tramite la tecnologia A portata di clic.  </li>
<li>  Installazione delle app di Office Mobile (ad esempio Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) sui dispositivi iOS o Android.  </li>
<li>  Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.  </li>
<li>  Selezione e configurazione di un'installazione locale o cloud.  </li>
<li>  Creazione del codice XML di configurazione dello Strumento di distribuzione di Office con lo Strumento di personalizzazione di Office o del codice XML nativo per configurare il pacchetto di distribuzione.  </li>
<li>  Distribuzione con Microsoft Endpoint Configuration Manager, che include una guida per la creazione del pacchetto di Microsoft Endpoint Configuration Manager.  
  Inoltre, se si dispone di una macro o di un componente aggiuntivo che funzionava con le versioni precedenti di Office e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema di compatibilità senza costi aggiuntivi tramite il programma App Assure. Per altri <strong>dettagli,</strong> vedi la parte App Assure di <a href="#windows-10">Windows 10.</a> </li>
</ul></td>
<td><ul>
<li>  Il software client online deve essere al livello minimo definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Integrità della rete</strong></td>
<td>  Forniamo indicazioni remote per ottenere e interpretare i dati di connettività di rete chiave dall'ambiente in uso che mostrano quanto i siti dell'organizzazione sono allineati ai principi di connettività <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">di rete di</a>Microsoft. Questo evidenzia il punteggio di rete che influisce direttamente sulla velocità della migrazione, sull'esperienza utente, sulle prestazioni del servizio e sull'affidabilità.  
  Ti guideremo anche attraverso qualsiasi procedura di correzione evidenziata da questi dati per aiutarti a migliorare il punteggio di rete.  </td>
<td><ul>
<li>  Accesso all'interfaccia di amministrazione di Microsoft 365.  </li>
<li>  Sono necessarie versioni aggiornate delle app di Microsoft 365.  </li>
<li>  Servizi percorso abilitati in base ai suggerimenti sulle prestazioni di rete nell'interfaccia di amministrazione di <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 (anteprima).</a>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a>Sicurezza e conformità

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli della guida di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></td>
<td>  Vengono fornite indicazioni remote per la protezione delle identità cloud per gli scenari seguenti.  

 <br/>

<strong>Infrastruttura di base protetta</strong>  </ul>
<ul>
<li>  Configurazione e abilitazione dell'autenticazione avanzata per le identità, inclusa la protezione con Azure Multi-Factor Authentication (MFA) (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure MFA e la reimpostazione della password self-service (SSPR).  </li>
<li>  Per i clienti non di Azure AD Premium, vengono fornite indicazioni per proteggere le identità usando le impostazioni predefinite di sicurezza.  </li>
<li>  Per i clienti premium di Azure AD, vengono fornite indicazioni per proteggere le identità con l'accesso condizionale.  </li>
<li>  Rilevamento e blocco dell'uso di password deboli con Azure AD Password Protection.  </li>
<li>  Protezione dell'accesso remoto alle app Web locali con il proxy dell'applicazione Azure AD.  </li>
<li>  Abilitazione del rilevamento e della correzione basata sui rischi con Azure Identity Protection.  </li>
<li>  Abilitazione di una schermata di accesso personalizzata, inclusi logo, testo e immagini con personalizzazione.  </li>
<li>  Condivisione sicura di app e servizi con utenti guest con Azure AD B2B.  </li>
<li>  Gestione dell'accesso per gli amministratori di Office 365 tramite i ruoli amministrativi incorporati del controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.  </li>
<li>  Configurazione dell'aggiunta ad Azure AD ibrido.  </li>
<li>  Configurazione dell'aggiunta ad Azure AD.  </li>
</ul>
  
<strong>Monitoraggio e creazione di report</strong>  
<ul>
<li>  
  Abilitazione del monitoraggio remoto per AD FS, Azure AD Connect e controller di dominio con Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Governance</strong>  
<ul>
<li>  
  Gestione del ciclo di vita delle identità e degli accessi di Azure AD su vasta scala con la gestione dei diritti di Azure AD.
  </li>
<li>  
  Gestione dell'appartenenza ai gruppi di Azure AD, dell'accesso alle app aziendali e delle assegnazioni dei ruoli con le verifiche di accesso di Azure AD.  
  </li>
<li>  
  Esame delle Condizioni per l'utilizzo di Azure AD.  
  </li>
<li>  
  Gestione e controllo dell'accesso agli account amministratore con privilegi con Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automazione ed efficienza </strong>  
<ul>
<li>  
  Abilitazione di Azure AD SSPR.  
  </li>
<li>  Consentire agli utenti di creare e gestire la propria sicurezza cloud o i gruppi di Office 365 con la gestione dei gruppi self-service di Azure AD.  </li>
<li>  Gestione dell'accesso delegato alle app aziendali con la gestione dei gruppi delegati di Azure AD.  </li>
<li>  Abilitazione dei gruppi dinamici di Azure AD.  </li>
<li>  Organizzazione delle app nel portale App personali tramite raccolte.  </li>
</ul></td>
<td>Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione dei problemi identificati che impediscono l'integrazione con le funzionalità di Azure AD e Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Per altre informazioni su Azure Information Protection, vedere <strong>Microsoft Information Protection</strong> più avanti in questa tabella.

  </td>
<td>  
  <tr class="odd">
<td><strong>Risposta & individuazione</strong></td>
<td>  

<strong>Advanced eDiscovery</strong>
  
<ul>
<li>  Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.  </li>
<li>  Configurazione di automazione, analisi e risposta.  </li>
<li>  Uso del simulatore di attacchi.  </li>
<li>  Creazione di report e analisi delle minacce.  </li>
</ul>

<strong>Controllo avanzato</strong> (supportato solo in E5)

Forniamo indicazioni remote per:  
<ul>
<li> Abilitazione del controllo avanzato.</li>
<li> Esecuzione di un'interfaccia utente del log di controllo della ricerca e comandi di powerShell di controllo di base.</li>
</ul>

<strong> Compliance Manager</strong>

Forniamo indicazioni remote per:  

<ul> <li>Esame dei tipi di ruolo.  </li>
<li> Aggiunta e configurazione di valutazioni.</li>
<li> Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</li>
<li> Revisione del mapping dei controlli incorporati e valutazione dei controlli.</li>
<li> Generazione di un report all'interno di una valutazione.</li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong> 
<ul>
<li> Script o codifica personalizzati.</li>
<li> API eDiscovery. </li>
<li> Connettori dati. </li>
<li> Limiti di conformità e filtri di sicurezza.</li>
<li> Indagini sui dati.</li>
<li> Richieste dell'oggetto dei dati.</li>
<li> Revisione di documenti di progettazione, architetto e di terze parti.</li>
<li> Conformità alle normative e ai requisiti di settore e regionali.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul>
</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>

<tr class="odd">
<td><strong>Insider Threat Management</strong></td>

<td>  Forniamo indicazioni remote per:
<ul>
<li> Creazione di criteri e revisione delle impostazioni.</li>
<li> Accesso a report e avvisi.</li>
<li> Creare casi.</li>
<li> Creazione di modelli di avviso.</li>
<li> Linee guida sulla creazione del connettore risorse umane (HR).</li>
</ul>

<strong> Conformità delle comunicazioni </strong> 

Forniamo indicazioni remote per: 
<ul>
<li> Creazione di criteri e revisione delle impostazioni.</li>
<li> Accesso a report e avvisi.</li>
<li> Creazione di modelli di avviso.</li>
</ul>

<strong> Compliance Manager</strong>

Forniamo indicazioni remote per:  

<ul> <li>Esame dei tipi di ruolo.  </li>
<li> Aggiunta e configurazione di valutazioni.</li>
<li> Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</li>
<li> Revisione del mapping dei controlli incorporati e valutazione dei controlli.</li>
<li> Generazione di un report all'interno di una valutazione.</li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong> 
<ul>
<li> Creazione e gestione dei flussi di Power Automate.</li>
<li> Connettori dati (oltre il connettore HR). </li>
<li> Configurazioni di espressioni regolari personalizzate (RegEx).</li>
<li> Revisione di documenti di progettazione, architetto e di terze parti.</li>
<li> Barriere in fatto di informazioni.</li>
<li> Gestione degli accessi con privilegi.</li>
<li> Conformità alle normative e ai requisiti di settore e regionali.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul></td>
<td>A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender è una famiglia di prodotti di difesa aziendale pre e post-violazione unificata che coordina in modo nativo il rilevamento, la prevenzione, l'indagine e la risposta tra endpoint, identità, posta elettronica e app per fornire una protezione integrata da attacchi sofisticati. Forniamo indicazioni remote per: </p> 
<ul>
<li>  Panoramica del Centro sicurezza Microsoft 365.  </li>
<li>  Esame degli incidenti tra prodotti, inclusa l'attenzione su ciò che è critico, garantendo l'ambito completo degli attacchi, le risorse influenzate e le azioni di correzione automatizzate raggruppate.  </li>
<li>  Dimostrazione del modo in cui Microsoft 365 Defender può orchestrare l'analisi di risorse, utenti, dispositivi e cassette postali che potrebbero essere state compromesse tramite l'auto-riparazione automatica. </li>
<li>  Spiegare e fornire esempi di come i clienti possono cercare in modo proattivo tentativi di intrusione e attività di violazione che influiscono su posta elettronica, dati, dispositivi e account in più set di dati.   </li>
<li> Mostrare ai clienti come possono esaminare e migliorare la loro posizione di sicurezza in modo olistico con Microsoft Secure Score.</li>
</ul>
<p><strong>Gli elementi seguenti non sono nell'ambito</strong></p>
<ul>
<li> Gestione dei progetti delle attività di correzione del cliente. </li>
<li> Gestione continua, risposta alle minacce e correzione. </li>
<li> Linee guida per la distribuzione o formazione su:
<ul>
<li> Come correggere o interpretare i vari tipi di avviso e le attività monitorate. </li>
<li> Come analizzare un utente, un computer, un percorso di spostamento laterale o un'entità. </li>
<li> Ricerca personalizzata delle minacce.  </li>
</ul>
</li>
<li> Integrazione DIEM (Security Information and Event Management) o API.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security è un Cloud Access Security Broker (CASB) che offre visibilità completa, controllo sui viaggi dei dati e analisi sofisticate per identificare e contrastare le minacce informatiche in tutti i servizi cloud Microsoft e di terze parti. Forniamo indicazioni remote per:
<ul>
<li>  Configurazione del portale, tra cui:  </li>
<ul>
<li> Importazione di gruppi di utenti.</li>
<li> Gestione dell'accesso e delle impostazioni dell'amministratore.  </li>
<li> Definizione dell'ambito della distribuzione per selezionare determinati gruppi di utenti da monitorare o escludere dal monitoraggio.</li>
<li> Impostazione di intervalli e tag IP.</li>
<li> Personalizzazione dell'esperienza dell'utente finale con il logo e la messaggistica personalizzata.</li>
</ul>
<li> Configurare l'individuazione cloud per fornire shadow IT tramite:</li>
<ul>
<li> Microsoft Defender per gli endpoint.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Connessione <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">di app in primo</a> piano tramite connettori di app.</li>
<li> Configurazione del controllo dell'app di accesso condizionale nei portali di Accesso condizionale e Cloud App Security per applicare i controlli delle sessioni in tempo reale.</li>
<li> Distribuzione dei dashboard cloud App Security e Cloud Discovery.</li>
<li> Personalizzazione dei punteggi di rischio delle app in base alle priorità dell'organizzazione.</li>
<li> Creazione di tag e categorie dell'app.</li>
<li> App che sanzionano e annullano l'associazione.</li>
<li> Uso di attività e log di file.</li>
<li> Gestione delle app OAuth.</li>
<li> Informazioni sulla correlazione degli eventi imprevisti nel portale di Microsoft 365 Defender.</li>
<li> Fornire assistenza alla configurazione con i <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> casi d'uso principali per i casb (inclusa la creazione o l'aggiornamento di un massimo di sei (6) criteri), ad eccezione di: </li>
<ul>
<li> Controllo della configurazione degli ambienti IaaS (Internet as a Service) (#18).</li>
<li> Monitoraggio delle attività degli utenti per la protezione dalle minacce negli ambienti IaaS (#19).</li>
</ul>
</ul>
<p><strong>Gli elementi seguenti non sono nell'ambito</strong></p>
<ul>
<li> Gestione dei progetti delle attività di correzione del cliente.</li>
<li> Gestione continua, risposta alle minacce e correzione. </li>
<li> Configurazione dell'infrastruttura, dell'installazione o della distribuzione dei caricamenti automatici dei log per i report continui tramite Docker o un agente di raccolta log. Per <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">ulteriori informazioni, vedere i 20 casi</a> di utilizzo principali per i casb.</li>
<li> Creazione di un report snapshot di Cloud Discovery.</li>
<li> Blocco dell'utilizzo dell'app tramite script di blocco.</li>
<li> Connessione di app personalizzate.</li>
<li> Integrazione con provider di identità (IsP) di terze parti e provider di prevenzione della perdita di dati (DLP).</li>
<li> Formazione o indicazioni sulla ricerca avanzata.</li>
<li> Analisi e correzione automatizzate, inclusi i playbook di Microsoft Power Automate.</li>
<li> Integrazione delle API e delle informazioni di sicurezza (SIEM, Security Information and Event Management) (incluso Azure Sentinel).</li>
<li> Distribuzione di Cloud App Discovery come modello di prova.</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.  
  Forniamo indicazioni remote per:
<ul>
<li>  Distribuzione delle tecnologie per proteggere gli endpoint.  </li>
<li>  Configurazione dei profili di protezione degli endpoint e delle restrizioni dei dispositivi.  </li>
<li>  Valutazione della versione del sistema operativo e della gestione dei dispositivi (inclusi Intune, Microsoft Endpoint Configuration Manager, oggetti Criteri di gruppo e configurazioni di terze parti), nonché lo stato dei servizi av di Windows Defender o di altro software di sicurezza degli endpoint.  </li>
<li>  Valutazione dello stato dei servizi Windows AV o di altro software di sicurezza degli endpoint.  </li>
<li>  Valutazione dei proxy e dei firewall che limitano il traffico di rete.  </li>
<li>  Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo agente ATP con un endpoint di onboarding.  </li>
<li>  Linee guida per la distribuzione, assistenza alla configurazione ed istruzione su:
<ul>
<li>  
  Gestione delle minacce e delle vulnerabilità.  
  </li>
<li>  
  Riduzione della superficie di attacco.  
  </li>
<li>  
  Protezione di nuova generazione.  
  </li>
<li>  
  Rilevamento e risposta degli endpoint.  
  </li>
<li>  
  Indagine e correzione automatizzate.  
  </li>
<li>  
  Punteggio di sicurezza.  
  </li>
</ul></li>
<li>  Revisione di simulazioni ed esercitazioni (come scenari di pratica, malware falso e indagini automatizzate).  </li>
<li>  Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.  </li>
<li>  Integrazione di Office 365 ATP con Microsoft Defender ATP.  </li>
<li>  Procedure dettagliate nel portale di Microsoft Defender Security Center.  </li>
<li>  I sistemi operativi seguenti:
<ul>
<li>  
  Windows 10.  
  </li>
<li>  
  Windows Server 2016.  
  </li>
<li>  
  Windows Server 2019.  
  </li>
<li>  
  Windows Server 2019 Core Edition.  
  </li>
<li>  
  Windows Server Semi-Annual Channel (SAC) versione 1803.  
  </li>
<li>  
  macOS versioni 10.13, 10.14 e 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versione 2002 o successiva). 

</li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
<ul>
<li>  Gestione dei progetti delle attività di correzione del cliente.  </li>
<li>  Supporto nel sito.  </li>
<li>  Gestione continua e risposta alle minacce.  </li>
<li>  Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:
<ul>
<li>  
  Windows Server 2008.  
  </li>
<li>  
  Windows Server 2012.  
  </li>
<li>  
  Linux.  
  </li>
<li>  
  Dispositivi mobili (Android e iOS).  
  </li>
<li> Virtual Desktop Infrastructure (VDI) (persistente o non persistente).  </li>
</ul></li>
<li>  Onboarding e configurazione del server:
<ul>
<li>  
  Configurazione di un server proxy per le comunicazioni offline.  
  </li>
<li>  
  Configurazione dei pacchetti di distribuzione di Configuration Manager nelle istanze e nelle versioni di Configuration Manager di livello inferiore.  
  </li>
<li>  
  Onboarding dei server nel Centro sicurezza di Azure.  
  </li>
<li>  
  Server non gestiti da Configuration Manager.  
  </li>
</ul></li>
<li>  Onboarding e configurazione di macOS:
<ul>
<li>  
  Distribuzione manuale basata su Intune.  
  </li>
<li>  
  Distribuzione basata su JAMF.
  </li>
<li>  
  Altra distribuzione basata sul prodotto di gestione dei dispositivi mobili (MDM).  
  </li>
<li>  
  Distribuzione manuale.  
  </li>
</ul></li>
<li>  Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:
<ul>
<li>  
  Isolamento basato su hardware.  
  </li>
<li>  
  Controllo dell'app.  
  </li>
<li> Controllo del dispositivo.</li>
<li>  
  Protezione dagli exploit.  
  </li>
<li>  
  Firewall di rete.  
  </li>



</ul></li>
<li> Configurazione o gestione delle funzionalità di protezione degli account, ad esempio: </li>
<ul>

<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>
<li> Configurazione o gestione di BitLocker.</li>
<li>  Iscrizione o configurazione di Microsoft Threat Experts.  </li>
<li>  Configurazione o formazione che esamina le connessioni SIEM (Security Information and Event Management) o API.  </li>
<li>  Iscrizione o configurazione di Microsoft Threat Protection (MTP).  </li>
<li>  Formazione o indicazioni sulla ricerca avanzata.  </li>
<li>  Formazione o indicazioni su come usare o creare query Kusto.</li>
</li>
</ul>
Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  Microsoft Defender per identità è una soluzione di sicurezza basata sul cloud che sfrutta i segnali di Active Directory locali per identificare, rilevare e analizzare minacce avanzate, identità compromesse ed azioni Insider dannose dirette all'organizzazione. Forniamo indicazioni remote per:
<ul>
<li>   Creazione dell'istanza di Defender per l'identità. </li>
<li>   Connessione di Defender per l'identità ad Active Directory. </li>
<li>   Valutazione della preparazione dell'ambiente per la distribuzione del sensore Defender for Identity nei controller di dominio, tra cui:</li>   
<ul> 
<li>  Esecuzione dello strumento di dimensionamento per la pianificazione della capacità delle risorse. </li>
<li>  Esecuzione dello strumento di controllo per valutare la compatibilità dei controller di dominio con il sensore. </li>
</ul>
<li>  Distribuzione del sensore per acquisire e analizzare il traffico di rete e gli eventi di Windows direttamente dai controller di dominio, tra cui: </li>
<ul> 
<li>  Download del pacchetto del sensore. </li>
<li>  Configurazione del sensore. </li>
<li>  Installazione del sensore nel controller di dominio in modo invisibile all'utente. </li>
<li>  Distribuzione del sensore nell'ambiente a più foreste. </li>
</ul>
<li>  Integrazione di Defender per l'identità con Microsoft Cloud App Security (la licenza di Cloud App Security non è necessaria). </li>
<li>  Fornire indicazioni sulla distribuzione, assistenza alla configurazione ed istruzione su: </li>
<ul>
<li> Ottimizzazione dell'ambiente per ridurre il "rumore".  </li>
<li>  Informazioni sul report di valutazione della postura di sicurezza delle identità. </li>
<li>  Informazioni sul punteggio di priorità dell'analisi degli utenti e sul report di classificazione delle indagini degli utenti. </li>
<li> Informazioni sul report degli utenti inattivi.  </li>
<li> Fornire opzioni di correzione per un account compromesso.  </li>
</ul>
<li>  Facilitare la migrazione da Advanced Threat Analytics (ATA) a Defender for Identity. </li>
</ul>
<p><strong>Gli elementi seguenti non sono nell'ambito</strong></p>
<ul>

<li> Gestione dei progetti delle attività di correzione del cliente. </li>
<li> Gestione continua, risposta alle minacce e correzione.  </li>
<li> Distribuzione del sensore Defender for Identity, tra cui: </li>
<ul>
<li> Pianificazione manuale della capacità. </li>
<li> Distribuzione del sensore in una capacità autonoma. </li>
<li> Distribuzione del sensore con una scheda nic (Network Interface Card) Del teaming. </li>
<li> Distribuzione del sensore tramite uno strumento di terze parti. </li>
<li> Connessione al servizio cloud Defender for Identity tramite una connessione proxy Web. </li>
</ul>
<li> Creazione e gestione di honeytoken. </li>
<li> Linee guida per la distribuzione o formazione su: </li>
<ul>
<li> Correzione o interpretazione di vari tipi di avviso e attività monitorate.  </li>
<li> Analisi di un utente, di un computer, di un percorso di spostamento laterale o di un'entità. </li>
<li> Minaccia o ricerca avanzata. </li>
<li> Risposta a un evento imprevisto. </li>
</ul>
<li> Esercitazione del laboratorio di avviso di sicurezza per Defender for Identity. </li>
<li> Fornire una notifica quando Defender for Identity rileva attività sospette inviando avvisi di sicurezza al server syslog tramite un sensore designato.  </li>
<li> Configurazione di Defender per l'identità per eseguire query utilizzando il protocollo samr (Security Account Manager Remote) per identificare gli amministratori locali in computer specifici. </li>
<li> Configurazione di soluzioni VPN per aggiungere informazioni dalla connessione VPN alla pagina del profilo di un utente.  </li>
<li> Integrazione delle API e delle informazioni di sicurezza (SIEM, Security Information and Event Management) (incluso Azure Sentinel). </li>
<li> Distribuzione di Defender per i sensori di identità come modello di prova.</li>
</ul></td>
<td><ul>
<li>  Distribuzione di Active Directory.  </li>
<li>  I controller di dominio in cui intendi installare Defender per i sensori di identità dispongono di connettività Internet al servizio cloud Defender for Identity.  </li>
<ul>
<li> Il firewall e il proxy devono essere aperti per comunicare con il servizio cloud Defender for Identity (*.atp.azure.com la porta 443 deve essere aperta).</li>
</ul>
<li> Controller di dominio in esecuzione in uno dei seguenti:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 con KB4487044 (OS Build 17763.316).</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>

<td>  Forniamo indicazioni remote per:
<ul>
<li>  Creazione e pubblicazione di etichette e criteri di conservazione (supportati solo in E5).  
</li>
<li>  Gestione dei record (supportata solo in E5).  </li>
<ul><li>  Revisione della creazione del piano di file. </li>
<li>  Creazione e gestione di record,inclusi i record basati su eventi.  </li>
<li>  Revisione dell'eliminazione. </ul> </li>
</ul>

<strong> Compliance Manager</strong>

Forniamo indicazioni remote per:  

<ul> <li>Esame dei tipi di ruolo.  </li>
<li> Aggiunta e configurazione di valutazioni.</li>
<li> Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</li>
<li> Revisione del mapping dei controlli incorporati e valutazione dei controlli.</li>
<li> Generazione di un report all'interno di una valutazione.</li>
</ul>

  <strong>Gli elementi seguenti non sono nell'ambito </strong>  
<ul>
<li> Sviluppo di un piano di gestione dei file di record.</li>
<li> Connettori dati.</li>
<li> Sviluppo dell'architettura delle informazioni in SharePoint.</li>
<li> Script e codifica personalizzati.</li>
<li> Revisione di documenti di progettazione, architetto e di terze parti.</li>
<li> Supporto per E3.</li>
<li> Conformità alle normative e ai requisiti di settore e regionali.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul>

</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Classificazione dei dati (supportata in E3 ed E5).  </li>
<li>  Tipi di informazioni riservate (supportati in E3 ed E5).  </li>
<li>  Creazione di etichette di riservatezza (supportate in E3 ed E5).  </li>
<li>  Applicazione di etichette di riservatezza (supportate in E3 ed E5).  </li>
<li>  Classificatori trainabili (supportati in E5).  </li>
<li>  Conoscere i dati con Esplora contenuto ed Esplora attività (supportato in E5).  </li>
<li>  Pubblicazione di etichette con criteri (manuali e automatici) (supportati in E5).  </li>
<li>  Creazione di criteri di prevenzione della perdita dei dati (DLP) degli endpoint per i dispositivi Windows 10 (supportati in E5).  </li>
<li>  Creazione di criteri DLP per chat e canali di Microsoft Teams.  </li>
</ul>

<strong> Compliance Manager</strong>

Forniamo indicazioni remote per:  

<ul> <li>Esame dei tipi di ruolo.  </li>
<li> Aggiunta e configurazione di valutazioni.</li>
<li> Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</li>
<li> Revisione del mapping dei controlli incorporati e valutazione dei controlli.</li>
<li> Generazione di un report all'interno di una valutazione.</li>
</ul>

<strong> Azure Information Protection</strong>

Forniamo indicazioni remote per:  
<ul>
<li>  Attivazione e configurazione del tenant.  </li>
<li>  Creazione e configurazione di etichette e criteri (supportati in P1 e P2).  </li>
<li>  Applicazione della protezione delle informazioni ai documenti (supportata in P1 e P2).  </li>
<li>  Classificare ed etichettare automaticamente le informazioni nelle app di Office (ad esempio Word, PowerPoint, Excel e Outlook) in esecuzione in Windows e con il client Azure Information Protection (supportato in P2).  </li>
<li>  Individuazione e applicazione di etichette ai file in stato di inquieto con lo scanner di Azure Information Protection (supportato in P1 e P2).  </li>
<li>  Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.  </li>
</ul>

  Vengono inoltre fornite indicazioni per applicare la protezione tramite Microsoft Azure Rights Management Services (Azure RMS), Crittografia messaggi di Office 365 e prevenzione della perdita dei dati (DLP).

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
<ul>
<li>Codice cliente.</li>
<li>Sviluppo di espressioni regolari personalizzate (RegEx) per tipi di informazioni riservate.</li>
<li>Creazione o modifica di dizionari di parole chiave.</li>
<li>Script e codifica personalizzati.</li>
<li> Azure Purview.</li>
<li> Revisione di documenti di progettazione, architetto e di terze parti.</li>
<li> Conformità alle normative e ai requisiti di settore e regionali.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul>

<ul>

</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti di sistema minimi ad eccezione di Azure Information Protection.

<strong>Azure Information Protection</strong>

Le responsabilità preliminari del cliente includono:  
<ul>
<li>  Elenco di percorsi di condivisione file da analizzare.  </li>
<li>  Tassonomia di classificazione approvata. </li>
<li> Informazioni su eventuali restrizioni o requisiti normativi relativi alla gestione delle chiavi.  </li>
<li>  Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD. </li>
<li>  Etichette configurate per la classificazione e la protezione. </li>
<li> Sono presenti tutti i prerequisiti per lo scanner di Azure Information Protection. Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisiti per l'installazione</a>e la distribuzione dello scanner di etichettatura unificata di Azure Information Protection. </li>
<li>  Verificare che i dispositivi degli utenti esercitino un sistema operativo supportato e che siano installati i prerequisiti necessari. Per ulteriori dettagli, vedere gli argomenti seguenti.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guida dell'amministratore: Installare il client di etichettatura unificata di Azure Information Protection per gli utenti</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </li>
</ul>
<li> Installazione e configurazione del connettore Azure RMS e dei server, incluso il connettore ACTIVE Directory RMS (AD RMS) per il supporto ibrido.  </li>
<li> L'installazione e la configurazione di Bring Your Own Key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificato) o Hold Your Own Key (HYOK) (solo client classico) richiede una di queste opzioni per la distribuzione.  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Forniamo indicazioni remote su come prepararsi a usare Intune come provider di gestione dei dispositivi mobili (MDM) e di gestione delle app per dispositivi mobili (MAM) basato su cloud per le tue app e dispositivi. I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili. I passaggi possono includere:
<ul>
<li>  Licenze per gli utenti finali.  </li>
<li>  Configurazione delle identità che devono essere usate da Intune sfruttando Active Directory locale o le identità cloud (Azure AD).  </li>
<li>  Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.  </li>
<li>  Configurazione dell'autorità MDM in base alle esigenze di gestione, tra cui:
<ul>
<li>  Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.  </li>
</ul></li>
<li>  Fornire le indicazioni di MDM per:
<ul>
<li>  Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.  </li>
<li>  Configurare criteri e servizi di gestione MDM come:
<ul>
<li>  Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o collegamenti diretti.  </li>
<li>  Criteri di accesso condizionale.  </li>
<li>  Distribuzione di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.  </li>
<li>  Connessione al data warehouse di Intune.  </li>
<li>  Integrare Intune con:
<ul>
<li>  Visualizzatore team per assistenza remota (è necessaria una sottoscrizione del Visualizzatore del team).  </li>
<li>  Soluzioni partner di Mobile Threat Defense (MTD) (è necessaria una sottoscrizione MTD).  </li>
<li>  Una soluzione di gestione delle spese per telecomunicazioni (è necessaria una sottoscrizione a una soluzione di gestione delle spese per telecomunicazioni).  </li>

</ul></li>
<li>  Registrare i dispositivi di ogni piattaforma supportata in Intune.  </li>
</ul></li>
</ul></li>
<li>  Fornire indicazioni sulla protezione delle app su:
<ul>
<li>  Configurare criteri di protezione delle app per ogni piattaforma supportata.  </li>
<li>  Configurazione dei criteri di accesso condizionale per le app gestite.  </li>
<li>  Destinazione dei gruppi di utenti appropriati con i criteri MAM menzionati in precedenza.  </li>
<li>  Uso dei report sull'utilizzo delle app gestite.  </li>
</ul></li>
<li>  Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.  </li>
</ul>
 
</li>
</ul>
  
<strong>Collegamento tramite cloud</strong>  

  Ti guideremo per prepararti a collegare gli ambienti di Configuration Manager esistenti con Intune. I passaggi esatti dipendono dall'ambiente di origine. Questi passaggi possono includere:  
<ul>
<li>  Licenze per gli utenti finali.  </li>
<li>  Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.  </li>
<li>  Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.  </li>
<li>  Fornire indicazioni per configurare l'aggiunta ad Azure AD ibrido.  </li>
<li>  Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.  </li>
<li>  Fornire indicazioni su come configurare il gateway di gestione cloud se usato come soluzione per la co-gestione della gestione remota dei dispositivi basati su Internet.  </li>
<li>  Configurare i carichi di lavoro supportati che si desidera passare a Intune.  </li>
<li>  Installare il client Configuration Manager nei dispositivi registrati di Intune.  </li>
</ul> 

<strong>Distribuire Outlook Mobile per iOS e Android in modo sicuro</strong> È possibile fornire indicazioni per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire agli utenti che siano installate tutte le app necessarie.  
  La procedura per distribuire in modo sicuro Outlook mobile per iOS e Android con Intune dipende dall'ambiente di origine. Può includere:
<ul>
<li>  Download delle app Outlook per iOS e Android, Microsoft Authenticator e portale aziendale intune tramite Apple App Store o Google Play Store.  </li>
<li>  Fornire indicazioni sulla configurazione:
<ul>
<li>  Distribuzione delle app Outlook per iOS e Android, Microsoft Authenticator e Intune Company Portal con Intune.  </li>
<li>  Criteri di protezione delle app.  </li>
<li>  Criteri di accesso condizionale.  </li>
<li>  Criteri di configurazione delle app.  </li>
</ul></li>
</ul>  
  </td>
<td>  Gli amministratori IT devono disporre di un'autorità di certificazione, di una rete wireless e di infrastrutture VPN esistenti già funzionanti nei propri ambienti di produzione durante la pianificazione della distribuzione di reti wireless e profili VPN con Intune.  
  <strong>Nota:</strong>il vantaggio del servizio FastTrack non include l'assistenza per la configurazione delle autorità di certificazione, delle reti wireless, delle infrastrutture VPN o dei certificati push MDM di Apple per Intune.  
 
  <strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud. Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.

  <strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong> 
 
  <strong>Nota:</strong>microsoft fornisce assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10. Non forniamo assistenza per l'acquisto, la gestione delle licenze o l'attivazione. Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.  
  
<strong>Windows Autopilot</strong> 
 
  Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.  
  
</td>
</tr>

<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.  </li>
<li>  Configurazione di automazione, analisi e risposta.  </li>
<li>  Uso del simulatore di attacchi.  </li>
<li>  Creazione di report e analisi delle minacce.  </li>
</ul></td>
<td>A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli della guida di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Per Exchange Online, viene illustrato il processo per ottenere l'organizzazione pronta per l'utilizzo della posta elettronica. I passaggi esatti dipendono dall'ambiente di origine e dai piani di migrazione della posta elettronica.  
  Forniamo indicazioni remote per:
<ul>
<li>  Configurare le funzionalità di Exchange Online Protection (EOP) per tutti i domini abilitati alla posta elettronica convalidati in Office 365.  </li>
<li>  Configurazione dei record MX (Mail Exchange) in modo che puntino a Office 365.  </li>
<li>  Configurazione della funzionalità Office 365 ATP se fa parte del servizio di sottoscrizione. Per ulteriori informazioni, vedere la parte relativa a <strong>Office 365 Advanced Threat Protection</strong> di questa tabella.  </li>
<li>  Configurare la funzionalità di prevenzione della perdita dei dati (DLP) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</li>
<li>  Configurare Office 365 Message Encryption (OME) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</li>
</ul>
  <strong>Nota:</strong> Il servizio di replica delle cassette postali tenta di eseguire la migrazione dei messaggi di posta elettronica di Information Rights Managed (IRM) dalla cassetta postale locale alla cassetta postale di Exchange Online corrispondente. La possibilità di leggere i contenuti protetti dopo la migrazione dipende dal fatto che il cliente esegua il mapping e copi i modelli di Active Directory Rights Managed Services (AD RMS) in Azure Rights Management Service (Azure RMS).  
<ul>
<li>  Configurazione delle porte del firewall.  </li>
<li>  Configurazione di DNS, tra cui l'individuazione automatica necessaria, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) e MX records (in base alle esigenze).  </li>
<li>  Configurare il flusso di posta elettronica tra l'ambiente di messaggistica di origine e Exchange Online (in base alle esigenze).  </li>
<li>  Eseguire la migrazione della posta dall'ambiente di messaggistica di origine a Office 365.  </li>
<li>  Configurazione di client delle cassette postali (Outlook per Windows, Outlook sul web e Outlook per iOS e Android).  </li>
</ul>
  <strong>Migrazione dei dati</strong>  <br>
Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Migrazione dei dati.</a>   
<td>  L'ambiente di origine deve avere uno dei livelli minimi seguenti:
<ul>
<li>  Una o più organizzazioni di Exchange con Exchange Server 2003 e versioni successive.  </li>
<li>  Un singolo ambiente di posta elettronica abilitato per il protocollo IMAP.  </li>
<li>  Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).  </li>
<li>  Per informazioni su Multi-Geo Capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online.</a>  </li>
</ul>
Il software client online come Project per Office 365, Outlook per Windows, Outlook per iOS e Android, il client di sincronizzazione di OneDrive for Business, Power BI Desktop e Skype for Business deve essere al livello minimo, come definito in Requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a>  </td>
</tr>
<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Creazione e pubblicazione di etichette e criteri di conservazione (supportati solo in E5).  
</li>
<li>  Gestione dei record (supportata solo in E5).  </li>
<ul><li>  Revisione della creazione del piano di file. </li>
<li>  Creazione e gestione di record,inclusi i record basati su eventi.  </li>
<li>  Revisione dell'eliminazione. </ul> </li>
</ul>

<strong> Compliance Manager</strong>

Forniamo indicazioni remote per:  

<ul> <li>Esame dei tipi di ruolo.  </li>
<li> Aggiunta e configurazione di valutazioni.</li>
<li> Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</li>
<li> Revisione del mapping dei controlli incorporati e valutazione dei controlli.</li>
<li> Generazione di un report all'interno di una valutazione.</li>
</ul>

  <strong>Gli elementi seguenti non sono nell'ambito </strong>  
<ul>
<li> Sviluppo di un piano di gestione dei file di record.</li>
<li> Connettori dati.</li>
<li> Sviluppo dell'architettura delle informazioni in SharePoint.</li>
<li> Script e codifica personalizzati.</li>
<li> Revisione di documenti di progettazione, architetto e di terze parti.</li>
<li> Supporto per E3.</li>
<li> Conformità alle normative e ai requisiti di settore e regionali.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul>


</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Classificazione dei dati (supportata in E3 ed E5).  </li>
<li>  Tipi di informazioni riservate (supportati in E3 ed E5).  </li>
<li>  Creazione di etichette di riservatezza (supportate in E3 ed E5).  </li>
<li>  Applicazione di etichette di riservatezza (supportate in E3 ed E5).  </li>
<li>  Classificatori trainabili (supportati in E5).  </li>
<li>  Conoscere i dati con Esplora contenuto ed Esplora attività (supportato in E5).  </li>
<li>  Pubblicazione di etichette con criteri (manuali e automatici) (supportati in E5).  </li>
<li>  Creazione di criteri di prevenzione della perdita dei dati (DLP) degli endpoint per i dispositivi Windows 10 (supportati in E5).  </li>
<li>  Creazione di criteri DLP per chat e canali di Microsoft Teams.  </li>
</ul>

<strong> Compliance Manager</strong>

Forniamo indicazioni remote per:  

<ul> <li>Esame dei tipi di ruolo.  </li>
<li> Aggiunta e configurazione di valutazioni.</li>
<li> Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</li>
<li> Revisione del mapping dei controlli incorporati e valutazione dei controlli.</li>
<li> Generazione di un report all'interno di una valutazione.</li>
</ul>

<strong> Azure Information Protection</strong>

Forniamo indicazioni remote per:  
<ul>
<li>  Attivazione e configurazione del tenant.  </li>
<li>  Creazione e configurazione di etichette e criteri (supportati in P1 e P2).  </li>
<li>  Applicazione della protezione delle informazioni ai documenti (supportata in P1 e P2).  </li>
<li>  Classificare ed etichettare automaticamente le informazioni nelle app di Office (ad esempio Word, PowerPoint, Excel e Outlook) in esecuzione in Windows e con il client Azure Information Protection (supportato in P2).  </li>
<li>  Individuazione e applicazione di etichette ai file in stato di inquieto con lo scanner di Azure Information Protection (supportato in P1 e P2).  </li>
<li>  Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.  </li>
</ul>
  
Vengono inoltre fornite indicazioni per applicare la protezione tramite Microsoft Azure Rights Management Services (Azure RMS), Crittografia messaggi di Office 365 e prevenzione della perdita dei dati (DLP).

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
<ul>
<li>Codice cliente.</li>
<li>Sviluppo di espressioni regolari personalizzate (RegEx) per tipi di informazioni riservate.</li>
<li>Creazione o modifica di dizionari di parole chiave.</li>
<li>Script e codifica personalizzati.</li>
<li> Azure Purview.</li>
<li> Revisione di documenti di progettazione, architetto e di terze parti.</li>
<li> Conformità alle normative e ai requisiti di settore e regionali.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul>

</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti di sistema minimi ad eccezione di Azure Information Protection.

<strong>Azure Information Protection</strong>

Le responsabilità preliminari del cliente includono:  
<ul>
<li>  Elenco di percorsi di condivisione file da analizzare.  </li>
<li>  Tassonomia di classificazione approvata. </li>
<li> Informazioni su eventuali restrizioni o requisiti normativi relativi alla gestione delle chiavi.  </li>
<li>  Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD. </li>
<li>  Etichette configurate per la classificazione e la protezione. </li>
<li> Sono presenti tutti i prerequisiti per lo scanner di Azure Information Protection. Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisiti per l'installazione</a>e la distribuzione dello scanner di etichettatura unificata di Azure Information Protection. </li>
<li>  Verificare che i dispositivi degli utenti esercitino un sistema operativo supportato e che siano installati i prerequisiti necessari. Per ulteriori dettagli, vedere gli argomenti seguenti.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guida dell'amministratore: Installare il client di etichettatura unificata di Azure Information Protection per gli utenti</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </li>
</ul>
<li> Installazione e configurazione del connettore Azure RMS e dei server, incluso il connettore ACTIVE Directory RMS (AD RMS) per il supporto ibrido.  </li>
<li> L'installazione e la configurazione di Bring Your Own Key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificato) o Hold Your Own Key (HYOK) (solo client classico) richiede una di queste opzioni per la distribuzione.  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Conferma dei requisiti minimi in Exchange Online, SharePoint Online, Gruppi di Office 365 e Azure AD per supportare Teams.  </li>
<li>  Configurazione delle porte del firewall.  </li>
<li>  Configurazione di DNS.  </li>
<li>  Conferma dell'abilitazione di Teams nel tenant Office 365.  </li>
<li>  Abilitazione o disabilitazione delle licenze utente.  </li>
<li>  Valutazione della rete per Teams:
<ul>
<li>  Controlli di porta ed endpoint.  </li>
<li>  Controlli sulla qualità della connessione.  </li>
<li>  Stime sulla larghezza di banda.  </li>
</ul>
<ul>
<li>  Configurazione dei criteri delle app di Teams (app Web di Teams, app Desktop di Teams e app Teams per iOS e Android).  </li>
</ul>
Se applicabile, forniamo anche indicazioni per:
<ul>
<li>  Dispositivi sala di Microsoft Teams:  </li>
<ul>
<li>  Creazione di account online necessari per i dispositivi di telefonia e di sala riunioni supportati elencati nel <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogo dei dispositivi Teams</a>.  </li>
<li>  Assistenza remota con la configurazione lato servizio dei dispositivi Microsoft Teams Rooms certificati.  </li>
<li>  Abilitazione dell'audioconferenza:  </li>
<li>  Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.  </li>
<li>  Assegnazione di bridge per conferenze agli utenti con licenza.  </li>
</ul>
<li>  Sistema telefonico:
<ul>
<li>  Configurazione aziendale delle impostazioni predefinite vocali cloud.  </li>
<li>  Linee guida per i piani di chiamata (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercati disponibili</a>):
<ul>
<li>  Assegnazione di numeri agli utenti con licenza.  </li>
<li>  Guida alla portabilità del numero locale tramite UI fino a 999.  </li>
<li>  Supporto RS per la richiesta di servizio di portabilità del numero locale superiore a 999.  </li>
</ul></li>
<li>  Linee guida per l'instradamento diretto:
<ul>
<li>  Indicazioni per la configurazione dell'organizzazione per la progettazione del routing diretto di scenari ospitati da partner o scenari distribuiti dal cliente per un massimo di 10 siti.  </li>
<li> Verifica della configurazione di Session Border Controller (SBC). </li>

<li> Assistenza remota per la configurazione del dial plan. </li>

<li> Configurazione route vocale.</li>

<li> Bypass multimediale e ottimizzazione multimediale locale. </li>

</ul></li>
</ul></li>
<li>  Abilitazione degli eventi live in Teams.  </li>
<li>  Configurazione dell'organizzazione e integrazione in Microsoft Stream.  </li>
<li>  Indicazioni per la transizione da Skype for Business a Teams.  </li>
</ul></td>
<td><ul>
<li>  Identità abilitate in Azure AD per Office 365.  </li>
<li>  Utenti abilitati per SharePoint Online.  </li>
<li>  Le cassette postali di Exchange sono presenti (online e locali in una configurazione ibrida di Exchange).  </li>
<li>  Abilitato per i gruppi di Office 365.  </li>
</ul>
  <strong>Nota:</strong> Se gli utenti non sono assegnati e abilitati con licenze di SharePoint Online, non diranno spazio di archiviazione in OneDrive for Business in Office 365. La condivisione dei file continua a funzionare nei canali, ma gli utenti non possono condividere file nelle chat senza l'archiviazione di OneDrive for Business in Office 365. Teams non supporta SharePoint locale.  <br>
  <strong>Nota:</strong> Lo stato ideale è che tutti gli utenti hanno le proprie cassette postali ospitate su Exchange Online. Gli utenti con cassette postali ospitate in locale devono avere le proprie identità sincronizzate con la directory di Office 365 tramite Azure AD Connect. Per questi clienti ibridi di Exchange, se la cassetta postale dell'utente è locale, l'utente non può aggiungere o configurare i connettori.  
  I programmi di installazione per i client desktop di Microsoft Teams per Windows e Mac possono essere scaricati da <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.  </li>
<li>  Configurazione di automazione, analisi e risposta.  </li>
<li>  Uso del simulatore di attacchi.  </li>
<li>  Creazione di report e analisi delle minacce.  </li>
</ul></td>
<td>A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>
<tr class="even">
<td><strong>Outlook per iOS e Android</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Download di Outlook per iOS e Android tramite l'Apple App Store e Google Play.  </li>
<li>  Configurazione degli account e accesso alla cassetta postale di Exchange Online.  </li>
<li>  Protezione di Outlook mobile (per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Protezione di Outlook per iOS e Android in Exchange Online).</a>  </li>
</ul></td>
<td><ul>
<li>  Identità abilitate in Azure AD per Office 365.  </li>
<li>  Exchange Online configurato e licenze assegnate.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Assegnare licenze di Power BI.  </li>
<li>  Distribuire l'app Power BI Desktop.  </li>
</ul></td>
<td>Il software client online come Power BI Desktop deve essere a un livello minimo, come definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Verificare la funzionalità di base di SharePoint sulla quale fa affidamento Project Online.  </li>
<li>  Aggiungere il servizio Project Online al tenant (inclusa l'aggiunta di sottoscrizioni per gli utenti).  </li>
<li>  Configurare il pool di risorse organizzazione (ERP).  </li>
<li>  Creare il primo progetto.  </li>
</ul></td>
<td>Il software client online come Project per Office 365 deve essere al livello minimo, come definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional e Premium</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Risoluzione dei problemi di implementazione.  </li>
<li>  Assegnare i contratti di licenza con l'utente finale utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.  </li>
<li>  Installare Client desktop di Project Online dal portale di Office 365 tramite la tecnologia A portata di clic.  </li>
<li>  Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.  </li>
<li>  Configurare un unico server di distribuzione nel sito per Client desktop di Project Online, includendo una guida per la creazione del file configuration.xml da usare con lo strumento di distribuzione di Office 365.  </li>
<li>  Connettere Client desktop di Project Online a Project Online Professional o Project Online Premium.  </li>
</ul></td>
<td>Il software client online come Project per Office 365 deve essere al livello minimo, come definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></td>
</tr>
<tr class="even">
<td><strong>SharePoint Online e OneDrive for Business</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Configurazione DNS.  </li>
<li>  Configurazione delle porte del firewall.  </li>
<li>  Provisioning di utenti e licenze.  </li>
<li>Abilitazione alla creazione di siti per l'amministratore di SharePoint Online.</li>
<li>Pianificazione delle raccolte di siti.</li>
<li>Protezione del contenuto e gestione delle autorizzazioni.</li>
<li>Configurazione delle caratteristiche di SharePoint Online.</li>
<li>  Configurazione delle funzionalità dell'ambiente ibrido di SharePoint, come la ricerca ibrida, i siti ibridi, la tassonomia ibrida, i tipi di contenuto, la creazione siti in modalità self-service ibrida (solo SharePoint Server 2013), l'icona di avvio delle app estesa, OneDrive for Business ibrido e i siti extranet.  </li>
<li>  L'approccio alla migrazione.  </li>
</ul>
Vengono fornite indicazioni aggiuntive per OneDrive for Business a seconda della versione di SharePoint, ad esempio:
<ul>
<li>  Identificazione delle opzioni di integrazione e revisione dell'infrastruttura di rete locale e online e della larghezza di banda.  </li>
<li>  Installazione di SharePoint Online 2013 SP1 (se applicabile), pianificazione e implementazione dei requisiti di sincronizzazione e identità e identificazione del client di sincronizzazione di OneDrive for Business.  </li>
<li>  Pianificazione e implementazione di una singola implementazione per tutti gli utenti (o un'implementazione in più fasi).  </li>
<li>  Assegnazione di licenze, reindirizzamento di siti personali e raccolte documenti personali a Office 365 (applicabile a SharePoint Online 2013), configurazione dei gruppi di destinatari per controllare l'accesso a OneDrive (applicabile a SharePoint Online 2013).  </li>
<li>Reindirizzamento o spostamento di cartelle note in OneDrive.</li>
<li>  Distribuzione della sincronizzazione del client OneDrive for Business.  </li>
</ul>
  <strong>Migrazione dei dati</strong>  <br>
Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Migrazione dei dati.</a>
</ul></td>
<td><br><strong>Per SharePoint ibrido:</strong>  
<ul>
<li>  La configurazione ibrida di SharePoint include la configurazione di ricerca ibrida, siti, tassonomia, tipi di contenuto, OneDrive for Business, un'icona di avvio delle app estesa, siti Extranet e creazione di siti in modalità self-service connessi dall'ambiente locale a un singolo ambiente SharePoint Online di destinazione.  </li>
</ul>
  <strong>Nota:</strong> La creazione di siti in modalità self-service non è nell'ambito dei server locali che eseguono SharePoint 2013.  
<ul>
<li>  Per abilitare l'ambiente ibrido di SharePoint, è necessario disporre di uno dei seguenti ambienti SharePoint Server locali: 2013, 2016 o 2019.  </li>
</ul>
  <strong>Nota:</strong> L'aggiornamento degli ambienti SharePoint locali a SharePoint Server non è nell'ambito. Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza. Per ulteriori informazioni, vedere Livelli di aggiornamento <a href="https://go.microsoft.com/fwlink/?linkid=853548">pubblico minimi per le funzionalità ibride di SharePoint.</a><em></em>  <br>
  <strong>Nota:</strong> Per informazioni su Multi-Geo Capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive e SharePoint Online in Office 365.</a><em></em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Vengono fornite indicazioni remote per l'abilitazione del servizio Yammer Enterprise.  
</ul></td>
<td>Il software client online deve essere al livello minimo definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli della guida di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></td>
<td>  Vengono fornite indicazioni remote per la protezione delle identità cloud per gli scenari seguenti.  

 <br/>

<strong>Infrastruttura di base protetta</strong>  </ul>
<ul>
<li>  Configurazione e abilitazione dell'autenticazione avanzata per le identità, inclusa la protezione con Azure Multi-Factor Authentication (MFA) (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure MFA e la reimpostazione della password self-service (SSPR).  </li>
<li>  Per i clienti non di Azure AD Premium, vengono fornite indicazioni per proteggere le identità usando le impostazioni predefinite di sicurezza.  </li>
<li>  Per i clienti premium di Azure AD, vengono fornite indicazioni per proteggere le identità con l'accesso condizionale.  </li>
<li>  Rilevamento e blocco dell'uso di password deboli con Azure AD Password Protection.  </li>
<li>  Protezione dell'accesso remoto alle app Web locali con il proxy dell'applicazione Azure AD.  </li>
<li>  Abilitazione del rilevamento e della correzione basata sui rischi con Azure Identity Protection.  </li>
<li>  Abilitazione di una schermata di accesso personalizzata, inclusi logo, testo e immagini con personalizzazione.  </li>
<li>  Condivisione sicura di app e servizi con utenti guest con Azure AD B2B.  </li>
<li>  Gestione dell'accesso per gli amministratori di Office 365 tramite i ruoli amministrativi incorporati del controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.  </li>
<li>  Configurazione dell'aggiunta ad Azure AD ibrido.  </li>
<li>  Configurazione dell'aggiunta ad Azure AD.  </li>
</ul>
  
<strong>Monitoraggio e creazione di report</strong>  
<ul>
<li>  
  Abilitazione del monitoraggio remoto per AD FS, Azure AD Connect e controller di dominio con Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Governance</strong>  
<ul>
<li>  
  Gestione del ciclo di vita delle identità e degli accessi di Azure AD su vasta scala con la gestione dei diritti di Azure AD.
  </li>
<li>  
  Gestione dell'appartenenza ai gruppi di Azure AD, dell'accesso alle app aziendali e delle assegnazioni dei ruoli con le verifiche di accesso di Azure AD.  
  </li>
<li>  
  Esame delle Condizioni per l'utilizzo di Azure AD.  
  </li>
<li>  
  Gestione e controllo dell'accesso agli account amministratore con privilegi con Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automazione ed efficienza </strong>  
<ul>
<li>  
  Abilitazione di Azure AD SSPR.  
  </li>
<li>  Consentire agli utenti di creare e gestire la propria sicurezza cloud o i gruppi di Office 365 con la gestione dei gruppi self-service di Azure AD.  </li>
<li>  Gestione dell'accesso delegato alle app aziendali con la gestione dei gruppi delegati di Azure AD.  </li>
<li>  Abilitazione dei gruppi dinamici di Azure AD.  </li>
<li>  Organizzazione delle app nel portale App personali tramite raccolte.  </li>
</ul></td>
<td>Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione dei problemi identificati che impediscono l'integrazione con le funzionalità di Azure AD e Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Per altre informazioni su Azure Information Protection, vedere <strong>Microsoft Information Protection</strong> in Sicurezza e <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> conformità.  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Forniamo indicazioni remote su come prepararsi a usare Intune come provider di gestione dei dispositivi mobili (MDM) e di gestione delle app per dispositivi mobili (MAM) basato su cloud per le tue app e dispositivi. I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili. I passaggi possono includere:
<ul>
<li>  Licenze per gli utenti finali.  </li>
<li>  Configurazione delle identità che devono essere usate da Intune sfruttando Active Directory locale o le identità cloud (Azure AD).  </li>
<li>  Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.  </li>
<li>  Configurazione dell'autorità MDM in base alle esigenze di gestione, tra cui:
<ul>
<li>  Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.  </li>
</ul></li>
<li>  Fornire le indicazioni di MDM per:
<ul>
<li>  Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.  </li>
<li>  Configurare criteri e servizi di gestione MDM come:
<ul>
<li>  Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o collegamenti diretti.  </li>
<li>  Criteri di accesso condizionale.  </li>
<li>  Distribuzione di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.  </li>
<li>  Connessione al data warehouse di Intune.  </li>
<li>  Integrare Intune con:
<ul>
<li>  Visualizzatore team per assistenza remota (è necessaria una sottoscrizione del Visualizzatore del team).  </li>
<li>  Soluzioni partner di Mobile Threat Defense (MTD) (è necessaria una sottoscrizione MTD).  </li>
<li>  Una soluzione di gestione delle spese per telecomunicazioni (è necessaria una sottoscrizione a una soluzione di gestione delle spese per telecomunicazioni).  </li>
</ul></li>
<li>  Registrare i dispositivi di ogni piattaforma supportata in Intune.  </li>
</ul></li>
</ul></li>
<li>  Fornire indicazioni sulla protezione delle app su:
<ul>
<li>  Configurare criteri di protezione delle app per ogni piattaforma supportata.  </li>
<li>  Configurazione dei criteri di accesso condizionale per le app gestite.  </li>
<li>  Destinazione dei gruppi di utenti appropriati con i criteri MAM menzionati in precedenza.  </li>
<li>  Uso dei report sull'utilizzo delle app gestite.  </li>
</ul></li>
<li>  Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.  </li>
</ul>
  
</li>
</ul>
  
<strong>Collegamento tramite cloud</strong>  

  Ti guideremo per prepararti a collegare gli ambienti di Configuration Manager esistenti con Intune. I passaggi esatti dipendono dall'ambiente di origine. Questi passaggi possono includere:  
<ul>
<li>  Licenze per gli utenti finali.  </li>
<li>  Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.  </li>
<li>  Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.  </li>
<li>  Fornire indicazioni per configurare l'aggiunta ad Azure AD ibrido.  </li>
<li>  Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.  </li>
<li>  Fornire indicazioni su come configurare il gateway di gestione cloud se usato come soluzione per la co-gestione della gestione remota dei dispositivi basati su Internet.  </li>
<li>  Configurare i carichi di lavoro supportati che si desidera passare a Intune.  </li>
<li>  Installare il client Configuration Manager nei dispositivi registrati di Intune.  </li>
</ul> 

<strong>Distribuire Outlook Mobile per iOS e Android in modo sicuro</strong> È possibile fornire indicazioni per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire agli utenti che siano installate tutte le app necessarie.  
  La procedura per distribuire in modo sicuro Outlook mobile per iOS e Android con Intune dipende dall'ambiente di origine. Può includere:
<ul>
<li>  Download delle app Outlook per iOS e Android, Microsoft Authenticator e portale aziendale intune tramite Apple App Store o Google Play Store.  </li>
<li>  Fornire indicazioni sulla configurazione:
<ul>
<li>  Distribuzione delle app Outlook per iOS e Android, Microsoft Authenticator e Intune Company Portal con Intune.  </li>
<li>  Criteri di protezione delle app.  </li>
<li>  Criteri di accesso condizionale.  </li>
<li>  Criteri di configurazione delle app.  </li>
</ul></li>
</ul>  
  </td>
<td>  Gli amministratori IT devono disporre di un'autorità di certificazione, di una rete wireless e di infrastrutture VPN esistenti già funzionanti nei propri ambienti di produzione durante la pianificazione della distribuzione di reti wireless e profili VPN con Intune.  
  <strong>Nota:</strong>il vantaggio del servizio FastTrack non include l'assistenza per la configurazione delle autorità di certificazione, delle reti wireless, delle infrastrutture VPN o dei certificati push MDM di Apple per Intune.  
 
  <strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud. Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.

  <strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong> 
 
  <strong>Nota:</strong>microsoft fornisce assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10. Non forniamo assistenza per l'acquisto, la gestione delle licenze o l'attivazione. Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.  
  
<strong>Windows Autopilot</strong> 
 
  Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli della guida di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Forniamo indicazioni per l'aggiornamento da Windows 7 Professional e Windows 8.1 Professional a Windows 10 Enterprise.  
  Forniamo indicazioni remote per:
<ul>
<li>  Informazioni sull'intenzione di Windows 10.  </li>
<li>  Valutazione dell'ambiente di origine e dei requisiti (assicurarsi che Microsoft Endpoint Configuration Manager sia aggiornato al livello necessario per supportare la distribuzione di Windows 10).  </li>
<li>  Distribuzione di Windows 10 Enterprise e Microsoft 365 Apps con Microsoft Endpoint Configuration Manager o Microsoft 365.  </li>
<li>  Opzioni consigliate per valutare le tue app di Windows 10.  </li>
<li>  Abilitazione dell'uso di Desktop Analytics e indicazioni tramite la creazione di un piano di distribuzione di Desktop Analytics.  </li>
<li>  Valutazione della compatibilità di Microsoft 365 Apps sfruttando il dashboard di preparazione di Office 365 in Configuration Manager o con readiness Toolkit per Office autonomo e assistenza per la distribuzione di Microsoft 365 Apps.  </li>
<li>  Creazione di un elenco di controllo di correzione sulle operazioni da eseguire per portare l'ambiente di origine ai requisiti minimi per una distribuzione corretta.  </li>
<li>  Fornire indicazioni per l'aggiornamento dei dispositivi esistenti a Windows 10 Enterprise se soddisfano i requisiti hardware dei dispositivi necessari.  </li>
<li>  Fornire indicazioni sull'aggiornamento per supportare il movimento di distribuzione esistente. FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10. Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di Windows Autopilot.  </li>
<li>  Distribuzione di Microsoft 365 Apps con Configuration Manager nell'ambito della distribuzione di Windows 10.   </li>
<li>  Fornire indicazioni per aiutare l'organizzazione a rimanere aggiornata con Windows 10 Enterprise e Microsoft 365 Apps usando l'ambiente Configuration Manager esistente o Microsoft 365.  </li>
</ul>
  <strong>Gli elementi seguenti non sono nell'ambito </strong>  
<ul>
<li>  Aggiornamento di Configuration Manager al Current Branch.  </li>
<li>  Creazione di immagini personalizzate per la distribuzione di Windows 10.  </li>
<li>  Creazione e supporto degli script di distribuzione per la distribuzione di Windows 10.  </li>
<li>  Conversione di un sistema di Windows 10 dal BIOS a Unified Extensible Firmware Interface (UEFI).  </li>
<li>  Abilitare le funzionalità di sicurezza di Windows 10.  </li>
<li>  Configurazione di Windows Deployment Services (WDS) per il boot di Preboot Execution Environment (PXE).  </li>
<li>  Uso di Microsoft Deployment Toolkit (MDT) per acquisire e distribuire immagini di Windows 10.  </li>
<li>  Uso dell’Utilità di migrazione dello stato utente (USMT).  </li>
</ul>
Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.  </td>
<td>  Per l'aggiornamento del PC, è necessario soddisfare i requisiti seguenti:
<ul>
<li>  Sistema operativo di origine: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.  </li>
<li>  Dispositivi: fattore di forma per desktop, notebook o tablet.  </li>
<li>  Sistema operativo di destinazione: Windows 10 Enterprise.  </li>
</ul>
Per l'aggiornamento dell'infrastruttura, è necessario soddisfare i requisiti seguenti:
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  La versione di Configuration Manager deve essere supportata dalla versione di destinazione di Windows 10. Per altre informazioni, vedere la tabella di supporto di Configuration Manager in <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Supporto per Windows 10 in Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.  
  Forniamo indicazioni remote per:
<ul>
<li>  Distribuzione delle tecnologie per proteggere gli endpoint.  </li>
<li>  Configurazione dei profili di protezione degli endpoint e delle restrizioni dei dispositivi.  </li>
<li>  Valutazione della versione del sistema operativo e della gestione dei dispositivi (inclusi Intune, Microsoft Endpoint Configuration Manager, oggetti Criteri di gruppo e configurazioni di terze parti), nonché lo stato dei servizi av di Windows Defender o di altro software di sicurezza degli endpoint.  </li>
<li>  Valutazione dello stato dei servizi Windows AV o di altro software di sicurezza degli endpoint.  </li>
<li>  Valutazione dei proxy e dei firewall che limitano il traffico di rete.  </li>
<li>  Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo agente ATP con un endpoint di onboarding.  </li>
<li>  Linee guida per la distribuzione, assistenza alla configurazione ed istruzione su:
<ul>
<li>  
  Gestione delle minacce e delle vulnerabilità.  
  </li>
<li>  
  Riduzione della superficie di attacco.  
  </li>
<li>  
  Protezione di nuova generazione.  
  </li>
<li>  
  Rilevamento e risposta degli endpoint.  
  </li>
<li>  
  Indagine e correzione automatizzate.  
  </li>
<li> Microsoft Defender ATP (sono necessarie licenze di Windows E5 o Microsoft 365 E5).  </li>
<li>  
  Punteggio di sicurezza.  
  </li>
</ul></li>
<li>  Revisione di simulazioni ed esercitazioni (come scenari di pratica, malware falso e indagini automatizzate).  </li>
<li>  Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.  </li>
<li>  Integrazione di Office 365 ATP con Microsoft Defender ATP.  </li>
<li>  Procedure dettagliate nel portale di Microsoft Defender Security Center.  </li>
<li>  I sistemi operativi seguenti:
<ul>
<li>  
  Windows 10.  
  </li>
<li>  
  Windows Server 2016.  
  </li>
<li>  
  Windows Server 2019.  
  </li>
<li>  
  Windows Server 2019 Core Edition.  
  </li>
<li>  
  Windows Server Semi-Annual Channel (SAC) versione 1803.  
  </li>
<li>  
  macOS versioni 10.13, 10.14 e 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versione 2002 o successiva). 

</li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
<ul>
<li>  Gestione dei progetti delle attività di correzione del cliente.  </li>
<li>  Supporto nel sito.  </li>
<li>  Gestione continua e risposta alle minacce.  </li>
<li>  Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:
<ul>
<li>  
  Windows Server 2008.  
  </li>
<li>  
  Windows Server 2012.  
  </li>
<li>  
  Linux.  
  </li>
<li>  
  Dispositivi mobili (Android e iOS).  
  </li>
<li> Virtual Desktop Infrastructure (VDI) (persistente o non persistente).  </li>
</ul></li>
<li>  Onboarding e configurazione del server:
<ul>
<li>  
  Configurazione di un server proxy per le comunicazioni offline.  
  </li>
<li>  
  Configurazione dei pacchetti di distribuzione di Configuration Manager nelle istanze e nelle versioni di Configuration Manager di livello inferiore.  
  </li>
<li>  
  Onboarding dei server nel Centro sicurezza di Azure.  
  </li>
<li>  
  Server non gestiti da Configuration Manager.  
  </li>
</ul></li>
<li>  Onboarding e configurazione di macOS:
<ul>
<li>  
  Distribuzione manuale basata su Intune.  
  </li>
<li>  
  Distribuzione basata su JAMF.
  </li>
<li>  
  Altra distribuzione basata sul prodotto di gestione dei dispositivi mobili (MDM).  
  </li>
<li>  
  Distribuzione manuale.  
  </li>
</ul></li>
<li>  Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:
<ul>
<li>  
  Isolamento basato su hardware.  
  </li>
<li>  
  Controllo dell'app.  
  </li>
<li> Controllo del dispositivo.</li>
<li>  
  Protezione dagli exploit.  
  </li>
<li>  
  Firewall di rete.  
  </li>

<ul>
<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>

</ul></li>
<li> Configurazione o gestione di BitLocker.</li>
<li>  Iscrizione o configurazione di Microsoft Threat Experts.  </li>
<li>  Configurazione o formazione che esamina le connessioni SIEM (Security Information and Event Management) o API.  </li>
<li>  Iscrizione o configurazione di Microsoft Threat Protection (MTP).  </li>
<li>  Formazione o indicazioni sulla ricerca avanzata.  </li>
<li>  Formazione o indicazioni su come usare o creare query Kusto.</li>
</li>
</ul>
Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Desktop virtuale Windows

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli della guida di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Desktop virtuale Windows</strong></td>
<td><p>Forniamo indicazioni sulla distribuzione per l'onboarding in Desktop virtuale Windows (un servizio di virtualizzazione di desktop e app). Desktop virtuale Windows sfrutta l'esperienza multi-sessione di Windows 10 ed è ottimizzato per Microsoft 365 Apps for Enterprise con sicurezza e gestione integrate per Microsoft 365.</p>
<p>Forniamo indicazioni remote per:</p>
<ul>
<li>Distribuzione dell'ambiente Desktop virtuale Windows con Windows 10 Enterprise multi-sessione e Microsoft 365 Apps for Enterprise con gli strumenti seguenti:
<ul>
<li>Immagine di Azure Marketplace.</li>
<li>Immagine condivisa.</li>
<li>Office Deployment Toolkit (ODT).</li>
</ul></li>
<li>Configurazione di FSLogix:
<ul>
<li>Distribuzione dell'agente FSLogix con il contenitore dei profili.</li>
<li>Distribuzione dell'agente FSLogix con contenitore di Office.</li>
<li>Configurazione della cartella FSLogix con esclusioni di contenuto.</li>
</ul></li>
<li>Distribuzione di Microsoft Edge.</li>
<li>Distribuzione di Microsoft Teams.</li>
<li>Connessione tramite client Desktop virtuale Windows.</li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito</strong>
<ul>
<li>Gestione dei progetti della distribuzione di Desktop virtuale Windows del cliente.</li>
<li>Virtualizzazione e distribuzione di app di terze parti.</li>
<li>Immagini personalizzate.</li>
<li>Migrazioni e scenari che coinvolgono VMware e Citrix.</li>
<li>Scenari Linux.</li>
<li>Conversione o migrazione dei profili utente.</li>
</ul>
Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</td>
<td>Dovresti già disporre di quanto segue:
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisiti di licenza di Desktop virtuale Windows</a>.</li>
<li>Rete di Azure:
<ul>
<li>Creazione e subnetting della rete virtuale (VNET).</li>
<li>Gruppi di sicurezza firewall e di rete.</li>
<li>VPN ed ExpressRoute.</li>
<li>Routing ad Azure dall'ambiente locale.</li>
<li>Regole del firewall per consentire la connettività a Desktop virtuale Windows.
</ul>
Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Client Desktop remoto supportati.</a>
</ul>
<ul><li>Configurazione generale di Azure AD:
<ul>
<li>Strategia di <i>identità (è possibile utilizzare solo una delle tre opzioni seguenti):</i>
<ul>
<li>Active Directory con Azure AD Connect in Azure.</li>
<li>Active Directory con Azure AD Connect locale tramite VPN o ExpressRoute.</li>
<li>Servizi di dominio Active Directory.</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>App Assure


<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli della guida di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>App Assure</strong></td>
<td>  App Assure è un servizio progettato per risolvere i problemi di compatibilità delle app di Windows 10 e Microsoft 365 Apps. Quando richiedi il servizio App Assure, microsoft lavora con te per risolvere i problemi validi dell'app senza costi aggiuntivi con un abbonamento idoneo. Forniamo anche indicazioni ai clienti che devono affrontare problemi di compatibilità durante la distribuzione di Desktop virtuale Windows e Microsoft Edge e facciamo ogni sforzo ragionevole per risolvere i problemi di compatibilità. Forniamo assistenza per la correzione per le app distribuite nei prodotti Microsoft seguenti:
<ul>
<li>  <strong>Windows 10 </strong> (inclusi i dispositivi ARM64)</li>
<li> <strong>Microsoft 365 Apps</strong>  </li>
<li>  <strong>Microsoft Edge -</strong> Per indicazioni sulla distribuzione, vedere <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Panoramica dei canali di Microsoft Edge.</a>  </li>
<li>  <strong>Desktop virtuale</strong> - Windows Per altre informazioni, vedi <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Che cos'è Desktop virtuale Windows?</a> e Domande frequenti su <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-sessione.</a>  </li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
<ul>
<li>  Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro di distribuzione desktop</a>. Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito <a href="https://go.microsoft.com/fwlink/?linkid=2053818">modulo</a>.</li>
<li>  Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10. Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</li>
<li>Servizi di sola creazione di pacchetti di app. Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.</li>
</ul>

<strong>Le responsabilità del cliente includono</strong>  
<ul>
<li>  Creazione di un inventario delle app.</li>
<li>  Convalida di tali app in Windows 10 e Microsoft 365 Apps.</li>
</ul>
<strong>Nota:</strong>  Microsoft non può apportare modifiche al codice sorgente. Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente. 


  Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.  </td>

</td>
<td><strong>Windows 10 e Microsoft 365 Apps</strong>
<ul>
<li>  
  Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.  
  </li>
</ul>
<strong>Windows 10 in ARM</strong>
<ul>
<li>  
Le app che hanno funzionato in Windows 7, Office 2010 o versioni successive funzionano anche in Windows 10 e Microsoft 365 Apps nei dispositivi ARM64. 
  </li>
</ul>
  <strong>Nota:</strong> 
<ul>
<li> L'emulazione x64 (64 bit) è disponibile in anteprima per i clienti che partecipano al <a href="https://insider.windows.com/">Programma Windows Insider.</a>  </li>
<li>  
 Per i clienti non windows insider con Windows 10 versione 2004 (o successiva), ARM64 Photoshop è supportato con OpenCL e <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack.</a> 
  </li>
<li>  
  I clienti del Programma Windows Insider possono scaricare una versione Insider del pacchetto di compatibilità OpenCL e OpenGL da usare con altre app.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Se le app o i siti Web funzionano in Internet Explorer 11, nelle versioni supportate di Google Chrome o in qualsiasi versione di Microsoft Edge, funzionano anche con Microsoft Edge.  
  </li>
<li>  
  Poiché il Web è in continua evoluzione, assicurarsi di leggere questo elenco pubblicato delle modifiche note che influiscono sulla compatibilità dei siti <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">per Microsoft Edge.</a>  
  </li>
</ul>
  <strong>Desktop virtuale Windows </strong>  
<ul>
<li>  
  Applicazioni virtualizzate che vengono eseguite su Windows Server Remote Desktop Session Host (RDSH) vengono eseguite anche nella multisessione di Windows 10 Enterprise come parte del Desktop virtuale Windows.  
  </li>
<li>  
  Le app in esecuzione in qualsiasi ambiente VDI (Virtual Desktop Infrastructure) di Windows 7 o Windows 10 vengono eseguite anche in Windows 7 Enterprise e Windows 10 Enterprise come parte di Desktop virtuale Windows.  
  </li>
<li>  
  Le app che vengono eseguite su dispostivi client di Windows 7 o Windows 10, vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte del Desktop virtuale Windows.  
  </li>
</ul>
  <strong>Nota:</strong> Le esclusioni e le limitazioni per la compatibilità con più sessioni di Windows 10 Enterprise includono:
<ul>
<li>  
  Reindirizzamento limitato dell'hardware.  
  </li>
<li>  
  Le app con uso intensivo di A/V possono essere eseguite a una capacità ridotta.  
  </li>
<li>  
  Le app a 16 bit non sono supportate per la versione Desktop virtuale Windows a 64 bit.  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli della guida di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
Forniamo indicazioni per la distribuzione remota e l'adozione e assistenza per la compatibilità per: <ul> <li>Distribuzione di Microsoft Edge in Windows 10 con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).  </li>
<li>  Configurazione di Microsoft Edge (tramite criteri di gruppo o la configurazione delle app di Intune e i criteri delle app).  </li>
<li>  Inventario dell'elenco di siti che potrebbero richiedere l'uso in modalità Internet Explorer.  </li>
<li>  Abilitazione della modalità Internet Explorer con l'elenco di siti dell'organizzazione esistente. Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Coinvolgimento di FastTrack.</a> Inoltre, se si dispone di un'app Web o di un sito che funziona con Internet Explorer o Google Chrome e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema senza costi aggiuntivi. Per richiedere il supporto della compatibilità per App Assure, accedi al portale <a href="https://fasttrack.microsoft.com/portal#/signin">fasttrack</a> per avviare un'interazione.  </li>
<li> Indicazioni sulla pianificazione per l'adozione di Edge e la configurazione dei segnalibri di Microsoft Search.</li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
<ul>
<li>Gestione dei progetti per la distribuzione di Microsoft Edge del cliente.</li>
<li>  Supporto nel sito.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
