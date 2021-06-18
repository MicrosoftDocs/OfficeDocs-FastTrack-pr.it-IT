---
title: Prodotti e funzionalità
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di poter iniziare. In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che consente all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding corretto.
ms.openlocfilehash: 0d5272079471b7dafe40e45f6c72189f1dad4c12
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994869"
---
# <a name="products-and-capabilities"></a>Prodotti e funzionalità

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Servizi e scenari supportati da FastTrack 

Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di poter iniziare. In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che consente all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding corretto.

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
> Per informazioni sulle previsioni dell’ambiente di origine di Office 365 U.S. Government, vedere [Previsioni dell’ambiente di origine di Office 365 U.S. Government](/us-gov-appendix-source-environment-expectations). 
 
## <a name="general"></a>Generale

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>FastTrack informazioni aggiuntive</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Onboarding di base</strong></td>
<td>  Forniamo indicazioni remote sull'onboarding di base, che prevede il provisioning dei servizi, il tenant e l'integrazione delle identità. Include inoltre i passaggi per fornire una base per l'onboarding di servizi come Exchange Online, SharePoint Online e Microsoft Teams, inclusa una discussione su sicurezza, connettività di rete e <a href="/office365/enterprise/office-365-network-connectivity-principles">conformità.</a>   

L'onboarding per uno o più servizi può iniziare al termine dell'onboarding di base.
</li>
</ul>  

<strong> Integrazione delle identità </strong>

Forniamo indicazioni remote per:
<ul>
<li>Preparazione delle identità di Active Directory locali per la sincronizzazione con Azure Active Directory (Azure AD), tra cui l'installazione e la configurazione di Azure AD Connessione (a foresta singola o multipla) e delle licenze (incluse le licenze basate su gruppo).</li>
<li>Creazione di identità cloud, tra cui importazione in blocco e licenze, incluso l'uso di licenze basate su gruppo.</li>
<li>Scelta e abilitazione del metodo di autenticazione corretto per il percorso cloud, Sincronizzazione hash password, Autenticazione pass-through o Active Directory Federation Services (AD FS).</li>
<li> Scelta e abilitazione di un'esperienza di autenticazione più comoda per gli utenti con autenticazione senza password (FIDO)2 o Microsoft Authenticator App).</li>
<li>Abilitazione di AD FS per i clienti con una singola foresta di Active Directory e identità sincronizzate con lo strumento di Connessione Azure AD. Questa operazione richiede Windows Server 2012 R2 Active Directory Federation Services 2.0 o versione successiva.</li>
<li>Migrazione dell'autenticazione da AD FS ad Azure AD tramite Sincronizzazione hash password o Autenticazione pass-through.</li>
<li>Migrazione di app pre-integrate (come le app SaaS (Software-as-a-Service) della raccolta di Azure AD) da AD FS ad Azure AD per single sign-on (SSO).</li>
<li>Abilitazione delle integrazioni di app SaaS con SSO dalla raccolta di Azure AD.</li>
<li>Abilitazione del provisioning automatico degli utenti per le app SaaS pre-integrate elencate nell'elenco delle esercitazioni sull'integrazione delle <a href="/azure/active-directory/saas-apps/tutorial-list">app </a> (limitate solo alle app SaaS della raccolta di Azure AD e solo al provisioning in uscita).  </li>

</td>

<td>  <strong>Abilitazione della rete </strong>  
  <br>Nell'ambito del FastTrack, si consiglia di utilizzare le procedure consigliate per la connessione ai servizi cloud per garantire i livelli di prestazioni più elevati di Microsoft 365.  
  
<strong>Foreste di Active Directory</strong> Il livello di foresta funzionale è impostato su Windows Server 2003 in poi, con la configurazione della foresta seguente:
<ul>
<li>  Una foresta unica di Active Directory.  </li>
<li>  Una singola foresta account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).  </li>
<li>  Più foreste account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).  </li>
<li>  Più foreste account di Active Directory con una delle foreste in posizione centrale nella foresta account di Active Directory contenente Exchange e/o Lync 2010, Lync 2013 o Skype for Business.  </li>
<li>  Più foreste account di Active Directory, ognuna con la propria organizzazione di Exchange.  </li>
<li>  Attività necessarie per la configurazione del tenant e l'integrazione con Azure Active Directory, se necessario.   </li>
</ul>
  <strong>Importante</strong>  <ul>
<li>  Per gli scenari di Active Directory a più foreste, se lync 2010, Lync 2013 o Skype for Business viene distribuito, deve essere distribuito nella stessa foresta di Active Directory di Exchange.  </li>
<li>  Quando si implementano più foreste di Active Directory con più organizzazioni Exchange in una configurazione multi-ibrida di Exchange, gli spazi dei nomi dell'entità utente condivisa (UPN) tra foreste di origine non sono supportati. Gli spazi dei nomi SMTP primari tra organizzazioni di Exchange devono essere separati. Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=845444">Distribuzioni ibride con più insiemi di strutture di Active Directory</a>.  </li>
<li>  Per tutte le configurazioni di più foreste, la distribuzione di Active Directory Federation Services (AD FS) non è in ambito. Per <a href="https://go.microsoft.com/fwlink/?linkid=2080150">assistenza, contattare</a> un partner Microsoft.  </li>
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
  Inoltre, se si dispone di una macro o di un componente aggiuntivo che funzionava con le versioni precedenti di Office e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema di compatibilità senza costi aggiuntivi tramite il programma App Assure. Vedi la <strong>sezione App Assure</strong> di <a href="#windows-10">Windows 10</a> per altri dettagli. </li>
</ul></td>
<td><ul>
<li>  Il software client online deve essere a un livello minimo, come definito nei requisiti di sistema per Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">e Office</a>.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Integrità della rete</strong></td>
<td>  Forniamo indicazioni remote per ottenere e interpretare i dati chiave di connettività di rete dall'ambiente in uso che mostrano quanto i siti dell'organizzazione siano allineati ai principi di connettività <a href="/office365/enterprise/office-365-network-connectivity-principles">di rete</a>di Microsoft. Questo evidenzia il punteggio di rete che influisce direttamente sulla velocità della migrazione, sull'esperienza utente, sulle prestazioni del servizio e sull'affidabilità.  
  Ti guideremo anche attraverso qualsiasi procedura di correzione evidenziata da questi dati per aiutarti a migliorare il punteggio di rete.  </td>
<td><ul>
<li>  Amministrazione Microsoft 365 Accesso centrale.  </li>
<li>  Sono necessarie versioni aggiornate Microsoft 365 app.  </li>
<li>  Servizi di posizione abilitati in base ai consigli sulle prestazioni <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">di rete nel Amministrazione Microsoft 365 Center (anteprima)</a>.  </li>
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
<th><strong>FastTrack informazioni aggiuntive</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></td>
<td>  Forniamo indicazioni remote per proteggere le identità cloud per gli scenari seguenti.  

 <br/>

<strong>Infrastruttura di base sicura</strong>  </ul>
<ul>
<li>  Configurazione e abilitazione dell'autenticazione avanzata per le identità, inclusa la protezione con Azure Multi-Factor Authentication (MFA) (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure MFA e la reimpostazione della password self-service ( SSPR).  </li>
<li> Distribuzione di FIDO2 o Microsoft Authenticator App. </li>
<li>  Per i clienti non Azure AD Premium, vengono fornite indicazioni per proteggere le identità utilizzando le impostazioni predefinite di sicurezza.  </li>
<li>  Per i clienti premium di Azure AD, vengono fornite indicazioni per proteggere le identità con l'accesso condizionale.  </li>
<li>  Rilevamento e blocco dell'uso di password deboli con Azure AD Password Protection.  </li>
<li>  Protezione dell'accesso remoto alle app Web locali con il proxy dell'applicazione Azure AD.  </li>
<li>  Abilitazione del rilevamento e correzione basati sui rischi con Azure Identity Protection.  </li>
<li>  Abilitazione di una schermata di accesso personalizzata, inclusi logo, testo e immagini con personalizzazione.  </li>
<li>  Condivisione sicura di app e servizi con utenti guest con Azure AD B2B.  </li>
<li>  Gestione dell'accesso per Office 365 amministratori con ruoli amministrativi incorporati RBAC (Role-Based Access Control) e per ridurre il numero di account amministratore con privilegi.  </li>
<li>  Configurazione dell'aggiunta ibrida di Azure AD.  </li>
<li>  Configurazione dell'aggiunta ad Azure AD.  </li>
</ul>
  
<strong>Monitorare e creare report</strong>  
<ul>
<li>  
  Abilitazione del monitoraggio remoto per AD FS, Azure AD Connessione e controller di dominio con Azure AD Connessione Health.  
  </li>
</ul>
  
<strong>Governance</strong>  
<ul>
<li>  
  Gestione del ciclo di vita dell'identità e dell'accesso di Azure AD su larga scala con la gestione dei diritti di Azure AD.
  </li>
<li>  
  Gestione delle appartenenze ai gruppi di Azure AD, dell'accesso alle app aziendali e delle assegnazioni di ruolo con le verifiche di accesso di Azure AD.  
  </li>
<li>  
  Revisione delle Condizioni per l'utilizzo di Azure AD.  
  </li>
<li>  
  Gestione e controllo dell'accesso agli account di amministratore con privilegi con Azure AD Gestione identità con privilegi.  
  </li>
</ul>
  
<strong>Automazione ed efficienza </strong>  
<ul>
<li>  
  Abilitazione di Azure AD SSPR.  
  </li>
<li>  Consentire agli utenti di creare e gestire la propria sicurezza cloud o Office 365 con la gestione dei gruppi self-service di Azure AD.  </li>
<li>  Gestione dell'accesso delegato alle app aziendali con la gestione dei gruppi delegati di Azure AD.  </li>
<li>  Abilitazione dei gruppi dinamici di Azure AD.  </li>
<li>  Organizzazione delle app nel portale App personali tramite raccolte.  </li>
</ul></td>
<td>Active Directory locale e il relativo ambiente sono stati preparati per la Azure AD Premium, inclusa la correzione dei problemi identificati che impediscono l'integrazione con Azure AD e le Azure AD Premium funzionalità.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Per altre informazioni su Azure Information Protection, <strong>vedere</strong> Microsoft Information Protection più avanti in questa tabella.

  </td>
<td>  
  <tr class="odd">
<td><strong>Individuazione & rispondi</strong></td>
<td>  

<strong>Advanced eDiscovery</strong>
  
Forniamo indicazioni remote per: 
<ul>
<li>  Creazione di un nuovo caso.   </li>
<li>  Mettere i custodi in attesa.  </li>
<li>  Esecuzione di ricerche. </li>
<li>  Aggiunta di risultati della ricerca a un insieme da rivedere. </li>
<li>  Esecuzione di analisi in un set di revisione.  </li>
<li>  Revisione e applicazione di tag ai documenti.  </li>
<li>  Esportazione di dati dal set di revisione. </li>
<li>  Importazione di dati non Office 365 dati. </li>
</ul>

<strong>Controllo avanzato</strong> (supportato solo in E5)

Forniamo indicazioni remote per:  
<ul>
<li> Abilitazione del controllo avanzato.</li>
<li> Esecuzione di un'interfaccia utente del log di controllo della ricerca e comandi di PowerShell di controllo di base.</li>
</ul>

<strong> Compliance Manager</strong>

Forniamo indicazioni remote per:  

<ul> <li>Revisione dei tipi di ruolo.  </li>
<li> Aggiunta e configurazione di valutazioni.</li>
<li> Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</li>
<li> Revisione del mapping dei controlli incorporati e valutazione dei controlli.</li>
<li> Generazione di un report all'interno di una valutazione.</li>
</ul>

<strong>L'ambito seguente non è disponibile </strong> 
<ul>
<li> Script o codifica personalizzati.</li>
<li> API eDiscovery. </li>
<li> Connettori dati. </li>
<li> Limiti di conformità e filtri di sicurezza.</li>
<li> Indagini sui dati.</li>
<li> Richieste dell'oggetto dei dati.</li>
<li> Revisione dei documenti di progettazione, architetto e di terze parti.</li>
<li> Conformità alle normative e ai requisiti del settore e regionale.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul>
</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> core in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>

<tr class="odd">
<td><strong>Insider Risk Management</strong></td>

<td>  Forniamo indicazioni remote per:
<ul>
<li> Creazione di criteri e revisione delle impostazioni.</li>
<li> Accesso a report e avvisi.</li>
<li> Creare casi.</li>
<li> Creazione di modelli di avviso.</li>
<li> Linee guida per la creazione del connettore risorse umane.</li>
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

<ul> <li>Revisione dei tipi di ruolo.  </li>
<li> Aggiunta e configurazione di valutazioni.</li>
<li> Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</li>
<li> Revisione del mapping dei controlli incorporati e valutazione dei controlli.</li>
<li> Generazione di un report all'interno di una valutazione.</li>
</ul>

<strong>L'ambito seguente non è disponibile </strong> 
<ul>
<li> Creazione e gestione di Power Automate flussi.</li>
<li> Connettori dati (oltre il connettore HR). </li>
<li> Configurazioni di espressioni regolari personalizzate (RegEx).</li>
<li> Revisione dei documenti di progettazione, architetto e di terze parti.</li>
<li> Barriere d'informazione.</li>
<li> Gestione degli accessi con privilegi.</li>
<li> Conformità alle normative e ai requisiti del settore e regionale.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul></td>
<td>A parte la <strong>parte relativa all'onboarding</strong> core in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender è una famiglia di prodotti di difesa aziendale unificata pre e post-violazione che coordina in modo nativo il rilevamento, la prevenzione, l'indagine e la risposta tra endpoint, identità, posta elettronica e app per fornire una protezione integrata da attacchi sofisticati. Forniamo indicazioni remote per: </p> 
<ul>
<li>  Fornire una panoramica del centro Microsoft 365 sicurezza.  </li>
<li>  Esame degli incidenti tra prodotti, inclusa la messa a fuoco su ciò che è critico garantendo l'ambito di attacco completo, gli asset influenzati e le azioni di correzione automatizzate raggruppate tra loro.  </li>
<li>  Dimostrazione del Microsoft 365 Defender può orchestrare l'indagine di asset, utenti, dispositivi e cassette postali che potrebbero essere state compromesse tramite l'auto-correzione automatica. </li>
<li>  Illustrando e fornendo esempi di come i clienti possono cercare in modo proattivo tentativi di intrusione e attività di violazione che influiscono su posta elettronica, dati, dispositivi e account in più set di dati.   </li>
<li> Mostrare ai clienti come possono rivedere e migliorare la loro posizione di sicurezza in modo olistico usando Microsoft Secure Score.</li>
</ul>
<p><strong>L'ambito seguente non è disponibile</strong></p>
<ul>
<li> Gestione dei progetti delle attività di correzione del cliente. </li>
<li> Gestione continua, risposta alle minacce e correzione. </li>
<li> Linee guida per la distribuzione o formazione su:
<ul>
<li> Come correggere o interpretare i vari tipi di avviso e le attività monitorate. </li>
<li> Come analizzare un utente, un computer, un percorso di movimento laterale o un'entità. </li>
<li> Ricerca personalizzata delle minacce.  </li>
</ul>
</li>
<li> Supporting <a href=" /fasttrack/us-gov-appendix-overview">GCC-High or GCC-DoD (Office 365 US Government)</a>.</li>
<li> Integrazione di informazioni di sicurezza e eventi (SIEM) o API.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security è un Cloud Access Security Broker (CASB) che offre visibilità avanzata, controllo sui viaggi dei dati e analisi sofisticate per identificare e contrastare le minacce informatiche in tutti i servizi cloud microsoft e di terze parti. Forniamo indicazioni remote per:
<ul>
<li>  Configurazione del portale, tra cui:  </li>
<ul>
<li> Importazione di gruppi di utenti.</li>
<li> Gestione dell'accesso e delle impostazioni dell'amministratore.  </li>
<li> Definizione dell'ambito della distribuzione per selezionare determinati gruppi di utenti da monitorare o escludere dal monitoraggio.</li>
<li> Come configurare intervalli e tag IP.</li>
<li> Personalizzare l'esperienza dell'utente finale con il logo e la messaggistica personalizzata.</li>
</ul>
<li> Integrazione di servizi di prima parte, tra cui:
<ul>
<li> Microsoft Defender per endpoint.</li>
<li> Microsoft Defender per identità.</li>
<li> Azure AD Identity Protection.</li>
<li> Azure Information Protection.</li>
</ul>
<li> Configurazione dell'individuazione cloud tramite:</li>
<ul>
<li> Microsoft Defender per endpoint.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Creazione di tag e categorie dell'app.</li>
<li> Personalizzazione dei punteggi dei rischi delle app in base alle priorità dell'organizzazione.</li>
<li> App che sanzionano e annullano l'applicazione.</li>
<li> Esame dei dashboard di Cloud App Security e Cloud Discovery.</li>
<li> Connessione <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> di app in primo</a> piano tramite connettori di app.</li>
<li> Protezione delle app con controllo dell'app di accesso condizionale nell'accesso condizionale all'interno dei portali di Azure AD e Cloud App Security.</li>
<li> Distribuzione del controllo dell'app con accesso condizionale per le app in primo piano.</li>
<li> Utilizzo dei log attività e dei file.</li>
<li> Gestione delle app OAuth.</li>
<li> Revisione e configurazione dei modelli di criteri.</li>
<li> Fornire assistenza alla configurazione con <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">i 20</a> casi d'uso principali per i casb (inclusa la creazione o l'aggiornamento di un massimo di sei (6) criteri) ad eccezione di: </li>
<ul>
<li> Controllo della configurazione dell'ambiente Internet as a Service (IaaS) (#18).</li>
<li> Monitoraggio delle attività degli utenti per la protezione dalle minacce negli ambienti IaaS (#19).</li>
</ul>
<li> Informazioni sulla correlazione degli incidenti nel portale di Microsoft 365 Defender.</li>
</ul>
<p><strong>L'ambito seguente non è disponibile</strong></p>
<ul>
<li> Gestione dei progetti delle attività di correzione del cliente.</li>
<li> Gestione continua, risposta alle minacce e correzione. </li>
<li> Discussioni che confrontano Cloud App Security con altre offerte CASB.</li>
<li> Configurazione di Cloud App Security per soddisfare requisiti normativi o di conformità specifici.</li>
<li> Distribuzione del servizio in un ambiente di produzione non di testing.</li>
<li> Distribuzione di Cloud App Discovery come prova di concetto.</li>
<li> Supporto di <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High o GCC-DoD (Office 365 US Government)</a>.</li>
<li> Configurazione dell'infrastruttura, dell'installazione o della distribuzione dei caricamenti automatici dei log per i report continui tramite Docker o un agente di raccolta log. </li>
<li> Creazione di un report snapshot di Cloud Discovery.</li>
<li> Blocco dell'utilizzo delle app tramite script di blocco.</li>
<li> Connessione di app personalizzate.</li>
<li> Onboarding e distribuzione del controllo dell'app con accesso condizionale per le app non in primo piano.</li>
<li> Integrazione con provider di identità di terze parti (IsP) e provider di prevenzione della perdita dei dati (DLP).</li>
<li> Formazione o indicazioni sulla ricerca avanzata.</li>
<li> Analisi e correzione automatizzate, inclusi i playbook di Microsoft Power Automate.</li>
<li> Integrazione delle informazioni di sicurezza e degli eventi (SIEM) o delle API (incluso Azure Sentinel).</li>

</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender per endpoint</strong></td>
<td>  Microsoft Defender for Endpoint è una piattaforma progettata per aiutare le reti aziendali a prevenire, rilevare, analizzare e rispondere alle minacce avanzate.  
  Forniamo indicazioni remote per:
<ul>
<li>  Distribuzione delle tecnologie per proteggere gli endpoint.  </li>
<li>  Configurazione dei profili di protezione degli endpoint e di restrizione dei dispositivi.  </li>
<li>  Valutazione della versione del sistema operativo e della gestione dei dispositivi (inclusi Intune, Microsoft Endpoint Configuration Manager, oggetti Criteri di gruppo e configurazioni di terze parti), nonché lo stato dei servizi av di Windows Defender o altro software di sicurezza degli endpoint.  </li>
<li>  Valutazione dello stato dei servizi Windows AV o di altro software di sicurezza degli endpoint.  </li>
<li>  Valutazione dei proxy e dei firewall che limitano il traffico di rete.  </li>
<li>  Abilitazione di Microsoft Defender per il servizio endpoint spiegando come distribuire un profilo dell'agente Defender for Endpoint usando un endpoint di onboarding.  </li>
<li>  Linee guida per la distribuzione, assistenza alla configurazione e formazione su:
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
  Punteggio sicuro per i dispositivi.  
  </li>
<li> Configurazione di Microsoft Defender SmartScreen con Microsoft Endpoint Manager.</li>

</ul></li>
<li>  Revisione di simulazioni ed esercitazioni (come scenari di pratica, malware contraffatto e indagini automatizzate).  </li>
<li>  Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.  </li>
<li>  Integrazione di Microsoft Defender per Office 365 con Microsoft Defender for Endpoint.  </li>
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

<strong>L'ambito seguente non è disponibile </strong>  
<ul>
<li>  Gestione dei progetti delle attività di correzione del cliente.  </li>
<li> Supporto di <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High o GCC-DoD (Office 365 US Government)</a>.</li>
<li>  Supporto nel sito.  </li>
<li>  Gestione continua e risposta alle minacce.  </li>
<li>  Onboarding o configurazione per i seguenti agenti di Microsoft Defender for Endpoint:
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
  Configurazione dei pacchetti di distribuzione di Configuration Manager nelle versioni e nelle istanze di Configuration Manager di livello inferiore.  
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
  Altra distribuzione basata su prodotti di gestione dei dispositivi mobili (MDM).  
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
<li> Controllo dispositivo.</li>
<li>  
  Protezione dagli exploit.  
  </li>
<li>  
  Firewall di rete.  
  </li>



</ul></li>
<li> Configurazione o gestione delle funzionalità di protezione degli account come: </li>
<ul>

<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>
<li> Configurazione o gestione di BitLocker.</li>
<li>  Iscrizione o configurazione di Microsoft Threat Experts.  </li>
<li>  Configurazione o formazione che esamina le connessioni SIEM (Security Information and Event Management).  </li>
<li>  Registrazione o configurazione di Microsoft 365 Defender.  </li>
<li>  Formazione o indicazioni sulla ricerca avanzata.  </li>
<li>  Formazione o indicazioni su come usare o creare query Kusto.</li>
<li> Formazione o indicazioni sulla configurazione di Defender SmartScreen tramite oggetti Criteri di gruppo,Sicurezza di Windows o Microsoft Edge.</li>
</li>
</ul>
Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  Microsoft Defender per identità è una soluzione di sicurezza basata sul cloud che sfrutta i segnali di Active Directory locali per identificare, rilevare e analizzare minacce avanzate, identità compromesse ed azioni Insider dannose dirette all'organizzazione. Forniamo indicazioni remote per:
<ul>
<li>  Esecuzione dello strumento di ridimensionamento per la pianificazione della capacità delle risorse. </li>
<li>   Creazione dell'istanza di Defender per l'identità. </li>
<li>   Connessione di Defender for Identity ad Active Directory. </li>

<li>  Distribuzione del sensore per acquisire e analizzare il traffico di rete e Windows eventi direttamente dai controller di dominio, tra cui: </li>
<ul> 
<li>  Download del pacchetto del sensore. </li>
<li>  Configurazione del sensore. </li>
<li>  Installazione del sensore nel controller di dominio in modo invisibile all'utente. </li>
<li>  Distribuzione del sensore nell'ambiente a più foreste. </li>
<li> Configurazione dell'agente Windows eventi.</li>
</ul>
<li>  Configurazione del portale, tra cui: </li>
<ul>
<li> Integrazione di Defender for Identity con Microsoft Cloud App Security (Cloud App Security non è necessaria la licenza). </li>
<li> Configurazione dei tag di entità.</li>
<li> Tagging di account sensibili. </li>
<li> Ricezione di notifiche tramite posta elettronica per problemi di integrità e avvisi di sicurezza. </li>
<li> Configurazione delle esclusioni degli avvisi.  </li>
</ul>
<li> Fornire indicazioni sulla distribuzione, assistenza alla configurazione e formazione su:</li>
<ul>
<li> Informazioni sul report di valutazione delle posture di sicurezza dell'identità.</li>
<li> Informazioni sul punteggio di priorità dell'indagine utente e sulla classificazione delle indagini utente.</li>
<li> Informazioni sul report degli utenti inattivi.</li>
<li> Spiegazione delle opzioni di correzione per un account compromesso.</li>
</ul>
<li>  Facilitare la migrazione da Advanced Threat Analytics (ATA) a Defender for Identity. </li>
</ul>
<p><strong>L'ambito seguente non è disponibile</strong></p>
<ul>

<li> Gestione dei progetti delle attività di correzione del cliente. </li>
<li> Gestione continua, risposta alle minacce e correzione.  </li>
<li> Distribuzione di Defender for Identity come prova di concetto.</li>
<li> Supporting <a href=" /fasttrack/us-gov-appendix-overview">GCC-High or GCC-DoD (Office 365 US Government)</a>.</li>
<li> Distribuzione o esecuzione delle seguenti attività del sensore Defender for Identity: </li>
<ul>
<li> Pianificazione manuale della capacità. </li>
<li> Esecuzione dello strumento di controllo. </li>
<li> Distribuzione del sensore autonomo. </li>
<li> Distribuzione in server Active Directory Federation Services (AD FS).
<li> Distribuzione del sensore tramite una scheda nic (Network Interface Card) Per il teaming. </li>
<li> Distribuzione del sensore tramite uno strumento di terze parti. </li>
<li> Connessione al servizio cloud Defender for Identity tramite una connessione proxy Web. </li>
</ul>
<li> Configurazione dell'account Microsoft (MSA) in Active Directory.
<li> Creazione e gestione di honeytoken. </li>
<li> Abilitazione della risoluzione dei nomi di rete (NNR). </li>
<li> Configurazione del contenitore Oggetti eliminati.</li>
<li> Linee guida per la distribuzione o formazione su: </li>
<ul>
<li> Correzione o interpretazione di vari tipi di avviso e attività monitorate.  </li>
<li> Analisi di un utente, di un computer, di un percorso di spostamento laterale o di un'entità. </li>
<li> Minaccia o ricerca avanzata. </li>
<li> Risposta agli eventi imprevisti. </li>
</ul>
<li> Esercitazione sul laboratorio di avviso di sicurezza per Defender for Identity. </li>
<li> Fornire una notifica quando Defender for Identity rileva attività sospette inviando avvisi di sicurezza al server syslog tramite un sensore nominato.  </li>
<li> Configurazione di Defender for Identity per eseguire query utilizzando il protocollo samr (Security Account Manager Remote) per identificare gli amministratori locali in computer specifici. </li>
<li> Configurazione delle soluzioni VPN per aggiungere informazioni dalla connessione VPN alla pagina del profilo di un utente.  </li>
<li> Integrazione delle informazioni di sicurezza e degli eventi (SIEM) o delle API (incluso Azure Sentinel). </li>
</ul></td>
<td><ul>
<li> Allineato ai <a href="/defender-for-identity/prerequisites"> prerequisiti di Microsoft Defender for Identity</a>. </li>
<li>  Active Directory distribuito.  </li>
<li>  I controller di dominio che intendi installare defender per i sensori di identità dispongono di connettività Internet al servizio cloud Defender for Identity.  </li>
<ul>
<li> Il firewall e il proxy devono essere aperti per comunicare con il servizio cloud Defender for Identity (*.atp.azure.com la porta 443 deve essere aperta).</li>
</ul>
<li> Controller di dominio in esecuzione in uno dei seguenti:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 con KB4487044 (OS Build 17763.316 o versione successiva).</li>
</ul>
<li> Microsoft .NET Framework 4.7 o versione successiva.</li>
<li> Sono necessari almeno cinque (5) GB di spazio su disco e 10 GB consigliati.</li>
<li> Due (2) core e sei (6) GB di RAM installati nel controller di dominio.</li>
</ul></td>
</tr>

<tr class="odd">
<td><strong>Microsoft Defender per Office 365</strong></td>
<td>  Microsoft Defender per Office 365 protegge l'organizzazione da minacce dannose derivanti da messaggi di posta elettronica, collegamenti (URL) e strumenti di collaborazione. Defender per Office 365 include:<ul>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Criteri di protezione dalle minacce:</a>definire i criteri di protezione dalle minacce per impostare il livello di protezione appropriato per l'organizzazione.</li>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Report</a>: consente di visualizzare report in tempo reale per monitorare Defender per Office 365 prestazioni nell'organizzazione.</li>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Funzionalità di analisi e risposta alle minacce</a>: consente di usare strumenti all'avanguardia per analizzare, comprendere, simulare e prevenire minacce.</li>
<li> <a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Funzionalità di analisi e risposta automatizzate</a>: consente di risparmiare tempo e fatica nell'analisi e nell'attenuazione delle minacce.</li>
</ul>

Forniamo indicazioni remote per:  
<ul>
<li>  Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.  </li>
<li>  Configurazione di automazione, analisi e risposta.  </li>
<li>  Uso del simulatore di attacchi.  </li>
<li>  Creazione di report e analisi delle minacce.  </li>
<li>  Informazioni sulla correlazione degli eventi imprevisti nel Microsoft 365 Defender portale.</li>
</ul>
<p><strong>L'ambito seguente non è disponibile</strong></p>
<ul>
<li> Gestione dei progetti delle attività di correzione del cliente.</li>
<li> Gestione continua, risposta alle minacce e correzione.</li>
<li> Supporting <a href=" /fasttrack/us-gov-appendix-overview">GCC-High or GCC-DoD (Office 365 US Government)</a>.</li>
<li> Discussioni che confrontano Defender per Office 365 altre offerte di sicurezza.</li>
<li> Distribuzione di Defender per Office 365 come prova di concetto.</li>
<li> Connessione di app personalizzate.</li>
<li> Formazione o indicazioni sulla ricerca avanzata.</li>
<li> Analisi e correzione automatizzate, inclusi i playbook Power Automate Microsoft.</li>
<li> Integrazione delle informazioni di sicurezza e degli eventi (SIEM) o delle API (incluso Azure Sentinel).</li>
</ul>
</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> core in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>


<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>

<td>  Forniamo indicazioni remote per:
<ul>
<li>  Creazione e pubblicazione di etichette e criteri di conservazione (supportati solo in E5).  
</li>
<li>  Gestione dei record (supportata solo in E5).  </li>
<ul><li>  Revisione della creazione del piano di file. </li>
<li>  Creazione e gestione dei record (inclusi i record basati su eventi).  </li>
<li>  Revisione dell'eliminazione. </ul> </li>
</ul>

<strong> Compliance Manager</strong>

Forniamo indicazioni remote per:  

<ul> <li>Revisione dei tipi di ruolo.  </li>
<li> Aggiunta e configurazione di valutazioni.</li>
<li> Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</li>
<li> Revisione del mapping dei controlli incorporati e valutazione dei controlli.</li>
<li> Generazione di un report all'interno di una valutazione.</li>
</ul>

  <strong>L'ambito seguente non è disponibile </strong>  
<ul>
<li> Sviluppo di un piano di gestione dei record.</li>
<li> Connettori dati.</li>
<li> Sviluppo dell'architettura delle informazioni in SharePoint.</li>
<li> Script e codifica personalizzati.</li>
<li> Revisione dei documenti di progettazione, architetto e di terze parti.</li>
<li> Supporto per E3.</li>
<li> Conformità alle normative e ai requisiti del settore e regionale.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul>

</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> core in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
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
<li>  Creazione di criteri di prevenzione della perdita dei dati degli endpoint (DLP) per i dispositivi Windows 10 (supportati in E5).  </li>
<li>  Creazione di criteri DLP per chat e canali di Microsoft Teams.  </li>
</ul>

<strong> Compliance Manager</strong>

Forniamo indicazioni remote per:  

<ul> <li>Revisione dei tipi di ruolo.  </li>
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
<li>  Classificare ed etichettare automaticamente le informazioni nelle app di Office (ad esempio Word, PowerPoint, Excel e Outlook) in esecuzione in Windows e usando il client Azure Information Protection (supportato in P2).  </li>
<li>  Individuazione e applicazione di etichette ai file in pausa tramite lo scanner di Azure Information Protection (supportato in P1 e P2).  </li>
<li>  Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.  </li>
</ul>

  Vengono inoltre fornite indicazioni per applicare la protezione tramite Microsoft Azure Rights Management Services (Azure RMS), Crittografia messaggi di Office 365 (OME) e prevenzione della perdita dei dati (DLP).

<strong>L'ambito seguente non è disponibile </strong>  
<ul>
<li>Codice cliente.</li>
<li>Sviluppo di espressioni regolari personalizzate (RegEx) per tipi di informazioni riservate.</li>
<li>Creazione o modifica di dizionari di parole chiave.</li>
<li>Script e codifica personalizzati.</li>
<li> Azure Purview.</li>
<li> Revisione dei documenti di progettazione, architetto e di terze parti.</li>
<li> Conformità alle normative e ai requisiti del settore e regionale.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul>

<ul>

</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema ad eccezione di Azure Information Protection.

<strong>Azure Information Protection</strong>

Le responsabilità preliminari del cliente includono:  
<ul>
<li>  Elenco dei percorsi di condivisione file da analizzare.  </li>
<li>  Tassonomia di classificazione approvata. </li>
<li> Informazioni su eventuali restrizioni o requisiti normativi relativi alla gestione delle chiavi.  </li>
<li>  Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD. </li>
<li>  Etichette configurate per la classificazione e la protezione. </li>
<li> Tutti i prerequisiti per lo scanner di Azure Information Protection sono stati installati. Per ulteriori informazioni, vedere <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisiti per l'installazione</a>e la distribuzione dello scanner di etichettatura unificata di Azure Information Protection. </li>
<li>  Verificare che i dispositivi utente esercitino un sistema operativo supportato e che siano installati i prerequisiti necessari. Per ulteriori dettagli, vedere quanto segue.</li>
<ul>
<li> <a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </li>
<li>  <a href="/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </li>
</ul>
<li> Installazione e configurazione del connettore Azure RMS e dei server, incluso il connettore AD RMS (Active Directory RMS) per il supporto ibrido.  </li>
<li> L'installazione e la configurazione di Bring Your Own Key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificato) o Hold Your Own Key (HYOK) (solo client classico) devono essere necessarie per una di queste opzioni per la distribuzione.  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Forniamo indicazioni remote su come prepararsi a usare Intune come provider di gestione dei dispositivi mobili (MDM) e maM (Mobile App Management) basato su cloud per le tue app e dispositivi. I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili. I passaggi possono includere:
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
<li>  Distribuzione di posta elettronica, reti wireless e profili VPN se nell'organizzazione è presente un'autorità di certificazione, una rete wireless o un'infrastruttura VPN.  </li>
<li>  Connessione al data warehouse di Intune.  </li>
<li>  Integrare Intune con:
<ul>
<li>  Visualizzatore team per assistenza remota (è necessaria una sottoscrizione a Visualizzatore team).  </li>
<li>  Soluzioni per i partner di Mobile Threat Defense (MTD) (è necessaria una sottoscrizione MTD).  </li>
<li>  Una soluzione di gestione delle spese per le telecomunicazioni (è necessaria una sottoscrizione a una soluzione di gestione delle spese di telecomunicazione).  </li>

</ul></li>
<li>  Registrare i dispositivi di ogni piattaforma supportata in Intune.  </li>
</ul></li>
</ul></li>
<li>  Fornire indicazioni sulla protezione delle app su:
<ul>
<li>  Configurare criteri di protezione delle app per ogni piattaforma supportata.  </li>
<li>  Configurazione dei criteri di accesso condizionale per le app gestite.  </li>
<li>  Destinazione dei gruppi di utenti appropriati con i criteri MAM menzionati in precedenza.  </li>
<li>  Uso dei report di utilizzo delle app gestite.  </li>
</ul></li>
<li>  Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Mdm di Intune.  </li>
</ul>
 
</li>
</ul>
  
<strong>Collegamento tramite cloud</strong>  

  Ti guideremo per prepararti a collegare gli ambienti di Configuration Manager esistenti con Intune. I passaggi esatti dipendono dall'ambiente di origine. Questi passaggi possono includere:  
<ul>
<li>  Licenze per gli utenti finali.  </li>
<li>  Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.  </li>
<li>  Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.  </li>
<li>  Fornire indicazioni per la configurazione dell'aggiunta ibrida ad Azure AD.  </li>
<li>  Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.  </li>
<li>  Fornisce indicazioni su come configurare il gateway di gestione cloud se usato come soluzione per la co-gestione della gestione remota dei dispositivi basati su Internet.  </li>
<li>  Configurare i carichi di lavoro supportati che si desidera passare a Intune.  </li>
<li>  Installare il client Configuration Manager nei dispositivi registrati di Intune.  </li>
</ul> 

<strong>Distribuire Outlook mobile per iOS e Android in modo sicuro</strong> Possiamo fornire indicazioni per distribuire Outlook mobile per iOS e Android in modo sicuro nell'organizzazione per garantire agli utenti che siano installate tutte le app necessarie.  
  La procedura per distribuire In modo sicuro Outlook mobile per iOS e Android con Intune dipende dall'ambiente di origine. Può includere:
<ul>
<li>  Download delle app Outlook per iOS e Android, Microsoft Authenticator e Intune Company Portal tramite Apple App Store o Google Play Store.  </li>
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
  <strong>Nota:</strong>il vantaggio del servizio FastTrack non include l'assistenza per la configurazione di Autorità di certificazione, reti wireless, infrastrutture VPN o certificati push MDM Apple per Intune.  
 
  <strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud. Per <a href="https://go.microsoft.com/fwlink/?linkid=2080150">assistenza, contattare</a> un partner Microsoft.

  <strong>Intune integrato con Microsoft Defender per Endpoint</strong> 
 
  <strong>Nota:</strong>microsoft fornisce assistenza per l'integrazione di Intune con Microsoft Defender for Endpoint e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10. Non forniamo assistenza per l'acquisto, la gestione delle licenze o l'attivazione. Per <a href="https://go.microsoft.com/fwlink/?linkid=2080150">assistenza, contattare</a> un partner Microsoft.  
  
<strong>Windows Autopilot</strong> 
 
  Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni aggiuntive su FastTrack</strong></th>
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
<li>  Puntare i record MX (Mail Exchange) a Office 365.  </li>
<li>  Configurare la funzionalità Microsoft Defender per Office 365 se fa parte del servizio di sottoscrizione. Per ulteriori informazioni, vedere la <strong>parte relativa a Microsoft Defender per Office 365</strong> di questa tabella.  </li>
<li>  Configurare la funzionalità di prevenzione della perdita dei dati (DLP) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</li>
<li>  Configurare Office 365 Message Encryption (OME) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</li>
</ul>
  <strong>Nota:</strong> Il servizio di replica delle cassette postali tenta di eseguire la migrazione dei messaggi di posta elettronica IRM (Information Rights Managed) dalla cassetta postale locale alla cassetta postale di Exchange Online corrispondente. La possibilità di leggere i contenuti protetti dopo la migrazione dipende dal fatto che il cliente esegua il mapping e copi i modelli di Active Directory Rights Managed Services (AD RMS) in Azure Rights Management Service (Azure RMS).  
<ul>
<li>  Configurazione delle porte del firewall.  </li>
<li>  Configurazione di DNS, tra cui l'individuazione automatica necessaria, il framework dei criteri mittente (SPF), la posta identificata da DomainKeys (DKIM), l'autenticazione dei messaggi basata su dominio, la creazione di report e conformità (DMARC) e i record MX (in base alle esigenze).  </li>
<li>  Configurare il flusso di posta elettronica tra l'ambiente di messaggistica di origine e Exchange Online (in base alle esigenze).  </li>
<li>  Eseguire la migrazione della posta dall'ambiente di messaggistica di origine a Office 365.  </li>
<li>  Configurazione di client delle cassette postali (Outlook per Windows, Outlook sul web e Outlook per iOS e Android).  </li>
</ul>
  <strong>Migrazione dei dati</strong>  <br>
Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="/fasttrack/data-migration">Data Migration</a>.   
<td>  L'ambiente di origine deve avere uno dei livelli minimi seguenti:
<ul>
<li>  Una o più organizzazioni di Exchange con Exchange Server 2003 e versioni successive.  </li>
<li>  Un singolo ambiente di posta elettronica abilitato per il protocollo IMAP.  </li>
<li>  Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).  </li>
<li>  Per informazioni sulle funzionalità multi-geografiche, vedere <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online.</a>  </li>
</ul>
Il software client online come Project per Office 365, Outlook per Windows, Outlook per iOS e Android, il client di sincronizzazione di OneDrive for Business, Power BI Desktop e Skype for Business deve essere al livello minimo, come definito in Requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a>  </td>
</tr>

<td><strong>Microsoft Defender per Office 365</strong></td>
<td>  Per ulteriori informazioni, vedere <strong>Microsoft Defender per Office 365</strong> in Sicurezza e <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformità.</a>  
</td>
<td></td>
</tr>


<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>
<td>  Per ulteriori informazioni, vedere <strong>Governance delle informazioni Microsoft</strong> in Sicurezza e <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformità.</a> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  
Per ulteriori informazioni, vedere <strong>Microsoft Information Protection</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a>

</td>
<td>

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
<li>  Configurazione dei criteri dell'app Teams (app Web Teams, app Desktop teams e App Teams per iOS e Android).  </li>
</ul>
Se applicabile, forniamo anche indicazioni per:
<ul>
<li>  Dispositivi sala Di Microsoft Teams:  </li>
<ul>
<li>  Creazione di account online necessari per i dispositivi di telefonia e di sala riunioni supportati elencati nel <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogo dei dispositivi Teams</a>.  </li>
<li>  Assistenza remota con la configurazione sul lato servizio dei dispositivi Microsoft Teams Rooms certificati.  </li>
<li>  Abilitazione dell'audioconferenza:  </li>
<li>  Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.  </li>
<li>  Assegnazione di bridge per conferenze agli utenti con licenza.  </li>
</ul>
<li>  Sistema telefonico:
<ul>
<li>  Configurazione aziendale delle impostazioni predefinite vocali cloud.  </li>
<li>  Indicazioni per i piani di chiamata (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercati disponibili</a>):
<ul>
<li>  Assegnazione di numeri agli utenti con licenza.  </li>
<li>  Guida alla portabilità del numero locale tramite UI fino a 999.  </li>
<li>  Supporto RS per la richiesta di servizio di portabilità del numero locale superiore a 999.  </li>
</ul></li>
<li>  Linee guida per l'instradamento diretto:
<ul>
<li>  Indicazioni per la configurazione dell'organizzazione per la progettazione del routing diretto di scenari ospitati da partner o scenari distribuiti dal cliente per un massimo di 10 siti.  </li>
<li> Session Border Controller (SBC) configuration review. </li>

<li> Assistenza remota con la configurazione del dial plan. </li>

<li> Configurazione delle route vocali.</li>

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
  <strong>Nota:</strong> Se gli utenti non sono assegnati e abilitati con le licenze di SharePoint Online, non diranno spazio di archiviazione in OneDrive for Business in Office 365. La condivisione dei file continua a funzionare nei canali, ma gli utenti non possono condividere file in Chat senza l'archiviazione di OneDrive for Business in Office 365. Teams non supporta SharePoint locale.  <br>
  <strong>Nota:</strong> Lo stato ideale è che tutti gli utenti hanno le loro cassette postali ospitate in Exchange Online. Gli utenti con cassette postali ospitate in locale devono avere le proprie identità sincronizzate con la directory di Office 365 tramite Azure AD Connect. Per questi clienti ibridi di Exchange, se la cassetta postale dell'utente è locale, l'utente non può aggiungere o configurare i connettori.  
  I programmi di installazione per i client desktop di Microsoft Teams per Windows e Mac possono essere scaricati da <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.  </td>
</tr>

<tr class="even">
<td><strong>Outlook per iOS e Android</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Download di Outlook per iOS e Android tramite l'Apple App Store e Google Play.  </li>
<li>  Configurazione degli account e accesso alla cassetta postale di Exchange Online.  </li>
<li>  Protezione di Outlook mobile (per ulteriori informazioni, vedere <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Protezione di Outlook per iOS e Android in Exchange Online).</a>  </li>
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
<td>Il software client online come Power BI Desktop deve essere a un livello minimo, come definito nei requisiti di sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">per Microsoft 365 e Office.</a></td>
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
<li>  Approccio alla migrazione.  </li>
</ul>
Vengono fornite ulteriori indicazioni per OneDrive for Business a seconda della versione di SharePoint, ad esempio:
<ul>
<li>  Identificazione delle opzioni di integrazione e revisione dell'infrastruttura di rete locale e online e della larghezza di banda.  </li>
<li>  Installazione di SharePoint Online 2013 SP1 (se applicabile), pianificazione e implementazione dei requisiti di sincronizzazione e identità e identificazione del client di sincronizzazione di OneDrive for Business.  </li>
<li>  Pianificazione e implementazione di una singola implementazione per tutti gli utenti (o un'implementazione in più fasi).  </li>
<li>  Assegnazione di licenze, reindirizzamento dei siti personali e delle raccolte documenti personali a Office 365 (applicabile a SharePoint Online 2013), configurazione dei gruppi di destinatari per controllare l'accesso a OneDrive (applicabile a SharePoint Online 2013).  </li>
<li>Reindirizzamento o spostamento di cartelle note in OneDrive.</li>
<li>  Distribuzione della sincronizzazione del client OneDrive for Business.  </li>
</ul>
  <strong>Migrazione dei dati</strong>  <br>
Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="/fasttrack/data-migration">Data Migration</a>.
</ul></td>
<td><br><strong>Per SharePoint ibrido:</strong>  
<ul>
<li>  La configurazione ibrida di SharePoint include la configurazione di ricerca ibrida, siti, tassonomia, tipi di contenuto, OneDrive for Business, un'icona di avvio delle app estesa, siti Extranet e creazione siti in modalità self-service connessi da locale a un ambiente SharePoint Online di destinazione singolo.  </li>
</ul>
  <strong>Nota:</strong> La creazione siti in modalità self-service non è in ambito con server locali che eseguono SharePoint 2013.  
<ul>
<li>  Per abilitare l'ambiente ibrido di SharePoint, è necessario disporre di uno dei seguenti ambienti SharePoint Server locali: 2013, 2016 o 2019.  </li>
</ul>
  <strong>Nota:</strong> L'aggiornamento degli ambienti SharePoint locali a SharePoint Server non è in ambito. Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza. Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=853548">Livelli minimi di aggiornamento pubblico per le funzionalità ibride di SharePoint.</a><em></em>  <br>
  <strong>Nota:</strong> Per informazioni sulle funzionalità multi-geografiche, vedere <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive e SharePoint Online in Office 365.</a><em></em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td>
Vengono fornite indicazioni remote per l'abilitazione del servizio Yammer Enterprise.  
</td>
<td>Il software client online deve essere a un livello minimo, come definito nei requisiti di sistema <a href="https://go.microsoft.com/fwlink/?LinkID=723597">per Microsoft 365 e Office.</a></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security 

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni aggiuntive su FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></td>
<td>  Per ulteriori informazioni, vedere <strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong> in Sicurezza e <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformità.</a></td>
<td></td>
</tr>
<tr class="odd">#sicurezza e conformità
<td><strong>Azure Information Protection </strong></td>
<td>  Per ulteriori informazioni su Azure Information Protection, vedere <strong>Microsoft Information Protection</strong> in Sicurezza e <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformità.</a>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Per altre informazioni, vedi <strong>Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Sicurezza e conformità.</a>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni aggiuntive su FastTrack</strong></th>
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
<li>  Valutare l'ambiente di origine e i requisiti (assicurarsi che Microsoft Endpoint Configuration Manager sia aggiornato al livello necessario per supportare la distribuzione di Windows 10).  </li>
<li>  Distribuzione di Windows 10 Enterprise e Microsoft 365 Apps con Microsoft Endpoint Configuration Manager o Microsoft 365.  </li>
<li>  Consigliando le opzioni per valutare le app di Windows 10.  </li>
<li>  Abilitazione dell'uso di Desktop Analytics e indicazioni tramite la creazione di un piano di distribuzione di Desktop Analytics.  </li>
<li>  Valutazione della compatibilità di Microsoft 365 Apps sfruttando il dashboard di conformità di Office 365 in Configuration Manager o con readiness Toolkit per Office autonomo e assistenza per la distribuzione di Microsoft 365 Apps.  </li>
<li>  Creazione di un elenco di controllo di correzione sulle operazioni da eseguire per portare l'ambiente di origine ai requisiti minimi per una corretta distribuzione.  </li>
<li>  Fornire indicazioni per l'aggiornamento dei dispositivi esistenti a Windows 10 Enterprise se soddisfano i requisiti hardware dei dispositivi necessari.  </li>
<li>  Fornire indicazioni sull'aggiornamento per supportare il movimento di distribuzione esistente. FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10. Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di Windows Autopilot.  </li>
<li>  Distribuzione di Microsoft 365 Apps con Configuration Manager come parte della distribuzione di Windows 10.   </li>
<li>  Fornire indicazioni per aiutare l'organizzazione a rimanere aggiornata con Windows 10 Enterprise e Microsoft 365 Apps usando l'ambiente Configuration Manager esistente o Microsoft 365.  </li>
</ul>
  
<strong>L'ambito seguente non è disponibile </strong>  
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
Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.  </td>
<td>  Per l'aggiornamento del PC, è necessario soddisfare i requisiti seguenti:
<ul>
<li>  Sistema operativo di origine: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.  </li>
<li>  Dispositivi: fattore di forma per desktop, blocco appunti o tablet.  </li>
<li>  Sistema operativo di destinazione: Finestra 10 Enterprise.  </li>
</ul>
Per l'aggiornamento dell'infrastruttura, è necessario soddisfare i requisiti seguenti:
<ul>
<li>  Microsoft Endpoint Configuration Manager.  </li>
<li>  La versione di Configuration Manager deve essere supportata dalla versione di destinazione di Windows 10. Per altre informazioni, vedere la tabella di supporto di Configuration Manager in <a href="/sccm/core/plan-design/configs/support-for-windows-10">Supporto per Windows 10 in Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender per endpoint</strong></td>
<td>  Per altre informazioni, vedi <strong>Microsoft Defender per Endpoint</strong> in Sicurezza e <a href="/fasttrack/products-and-capabilities#security-and-compliance">conformità.</a></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Desktop virtuale Windows

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni aggiuntive su FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Desktop virtuale Windows</strong></td>
<td><p>Forniamo indicazioni per la distribuzione per l'onboarding a Desktop virtuale Windows (un servizio di virtualizzazione desktop e app). Desktop virtuale Windows sfrutta l'esperienza multi-sessione di Windows 10 ed è ottimizzato per Microsoft 365 Apps for Enterprise con sicurezza e gestione integrate per Microsoft 365.</p>
<p>Forniamo indicazioni remote per:</p>
<ul>
<li>Distribuzione di Windows 10 Enterprise multi-session e Microsoft 365 Apps for Enterprise usando quanto segue:
<ul>
<li>Immagine di Azure Marketplace.</li>
<li>Immagine condivisa.</li>
<li>Office Deployment Toolkit (ODT).</li>
</ul></li>
<li>Configurazione di Microsoft 365 Apps for FSLogix in un desktop virtuale Windows nativo. Per FSLogix:
<ul>
<li>Distribuzione dell'agente.</li>
<li>Configurazione dei contenitori di Profili e Office.</li>
<li>Configurazione delle esclusioni di contenuto e dei reindirizzamenti delle cartelle per Microsoft 365 Apps.</li>
</ul></li>
<li>Distribuzione di Microsoft Edge.</li>
<li>Distribuzione di Microsoft Teams con ottimizzazione.</li>
</ul>

<strong>L'ambito seguente non è disponibile</strong>
<ul>
<li>Project management of the customer's Windows Virtual Desktop infrastructure deployment.</li>
<li>Virtualizzazione e distribuzione di app di terze parti.</li>
<li>Creazione di immagini personalizzate per Desktop virtuale Windows.</li>
<li>Migrazioni e scenari che coinvolgono VMware e Citrix.</li>
<li>Scenari Linux.</li>
<li>Conversione o migrazione di profili utente.</li>
<li>Configurazione di Microsoft Endpoint Configuration Manager e Microsoft Endpoint Manager per Desktop virtuale Windows (inclusa l'applicazione di patch e la gestione). </li>
<li>Microsoft 365 Defender con windows 10 multi-sessione.</li>
</ul>
Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</td>
<td>Dovresti già disporre di quanto segue:
<ul>
<li><a href="/azure/virtual-desktop/overview#requirements">Requisiti di licenza per Desktop virtuale Windows</a>.</li>
<li> Infrastruttura <a href="/azure/virtual-desktop/overview">necessaria per supportare Windows Virtual Deskstop.</a> </li>
<ul>
<li><a href="/azure/virtual-desktop/store-fslogix-profile"> Archiviazione per i contenitori dei profili FSLogix in Windows Virtual Deskstop</a>. </li>
</ul>
<li>Rete di Azure:
<ul>
<li>Creazione e subnetting della rete virtuale (VNET).</li>
<li>Firewall e gruppi di sicurezza di rete.</li>
<li>VPN ed ExpressRoute.</li>
<li>Routing ad Azure da locale.</li>
<li>Regole firewall per consentire la connettività a Desktop virtuale Windows.
</ul>
Per ulteriori informazioni, vedere <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.
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
<th><strong>Informazioni aggiuntive su FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>App Assure</strong></td>
<td>  App Assure è un servizio progettato per risolvere i problemi di compatibilità delle app di Windows 10 e Microsoft 365 Apps. Quando richiedi il servizio App Assure, microsoft lavora con te per risolvere i problemi validi dell'app senza costi aggiuntivi con un abbonamento idoneo. Forniamo inoltre indicazioni ai clienti che devono affrontare problemi di compatibilità durante la distribuzione di Desktop virtuale Windows e Microsoft Edge e ci sforziamo ogni ragionevole sforzo per risolvere i problemi di compatibilità. Microsoft fornisce assistenza per la correzione delle app distribuite nei prodotti Microsoft seguenti:
<ul>
<li>  <strong>Windows 10 </strong> (inclusi i dispositivi ARM64)</li>
<li> <strong>Microsoft 365 Apps</strong>  </li>
<li>  <strong>Microsoft Edge -</strong> Per istruzioni sulla distribuzione, vedere <a href="/DeployEdge/microsoft-edge-channels">Panoramica dei canali di Microsoft Edge.</a>  </li>
<li>  <strong>Desktop virtuale</strong> - Windows Per altre informazioni, vedi Domande frequenti <a href="/azure/virtual-desktop/overview">su Desktop virtuale Windows e</a> Windows <a href="/azure/virtual-desktop/windows-10-multisession-faq">10 Enterprise.</a>  </li>
</ul>

<strong>L'ambito seguente non è disponibile </strong>  
<ul>
<li>  Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro di distribuzione desktop</a>. Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito <a href="https://go.microsoft.com/fwlink/?linkid=2053818">modulo</a>.</li>
<li>  Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10. Per ulteriori informazioni, vedere <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</li>
<li>Servizi di sola creazione di pacchetti di app. Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.</li>
</ul>

<strong>Le responsabilità dei clienti includono</strong>  
<ul>
<li>  Creazione di un inventario delle app.</li>
<li>  Convalida di tali app in Windows 10 e Microsoft 365 Apps.</li>
</ul>
<strong>Nota:</strong>  Microsoft non può apportare modifiche al codice sorgente. Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente. 


  Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.  </td>

</td>
<td><strong>Windows 10 e Microsoft 365 Apps</strong>
<ul>
<li>  
  Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.  
  </li>
</ul>
<strong>Windows 10 on ARM</strong>
<ul>
<li>  
Le app che funzionavano su Windows 7, Office 2010 o versioni successive funzionano anche in Windows 10 e Microsoft 365 Apps nei dispositivi ARM64. 
  </li>
</ul>
  <strong>Nota:</strong> 
<ul>
<li> L'emulazione x64 (64 bit) è disponibile in anteprima per i clienti che partecipano al <a href="https://insider.windows.com/">Programma Windows Insider.</a>  </li>
<li>  
 Per i clienti non Windows Insider in Windows 10 versione 2004 (o successiva), ARM64 Photoshop è supportato con <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL e OpenGL Compatibility Pack.</a> 
  </li>
<li>  
  I clienti del programma Windows Insider possono scaricare una versione Insider del Pacchetto di compatibilità OpenCL e OpenGL per l'uso con altre app.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Se le app o i siti Web funzionano in Internet Explorer 11, nelle versioni supportate di Google Chrome o in qualsiasi versione di Microsoft Edge, funzionano anche con Microsoft Edge.  
  </li>
<li>  
  Poiché il Web è in continua evoluzione, leggere questo elenco pubblicato delle modifiche note che influiscono sulla compatibilità dei siti <a href="/microsoft-edge/web-platform/site-impacting-changes">per Microsoft Edge.</a>  
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
  <strong>Nota:</strong> Le esclusioni e le limitazioni di compatibilità multi-sessione di Windows 10 Enterprise includono:
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
<th><strong>FastTrack informazioni aggiuntive</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
Forniamo indicazioni per la distribuzione remota e l'adozione e assistenza per la compatibilità per: <ul> <li>Distribuzione di Microsoft Edge Windows 10 con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).  </li>
<li>  Configurazione di Microsoft Edge (usando i criteri di gruppo o la configurazione dell'app Intune e i criteri delle app).  </li>
<li>  Inventario dell'elenco dei siti che potrebbero richiedere l'utilizzo in modalità Internet Explorer.  </li>
<li>  Abilitazione della modalità Internet Explorer con l'Enterprise sito esistente. Per ulteriori informazioni, vedere <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Coinvolgente FastTrack</a>. Inoltre, se si dispone di un'app Web o di un sito che funziona con Internet Explorer o Google Chrome e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema senza costi aggiuntivi. Per richiedere il supporto per la compatibilità per App Assure, accedi al portale <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack per</a> avviare un'interazione.  </li>
<li> Indicazioni per la pianificazione per l'adozione e la configurazione di Edge per Microsoft Search segnalibri.</li>
</ul>

<strong>L'ambito seguente non è disponibile </strong>  
<ul>
<li>Gestione dei progetti per la distribuzione di Microsoft Edge del cliente.</li>
<li>  Supporto nel sito.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
