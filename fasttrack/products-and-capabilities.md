---
title: Prodotti e funzionalità
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: In questo argomento sono inclusi i dettagli sugli scenari di carico di lavoro supportati da FastTrack e le aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, è possibile creare un piano di correzione che consentirà all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding di esito positivo.
ms.openlocfilehash: a3477be6958dea88874bbc042445bbc693c10ffb
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/30/2020
ms.locfileid: "48320032"
---
# <a name="products-and-capabilities"></a>Prodotti e funzionalità

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Servizi e scenari supportati da FastTrack

In questo argomento sono inclusi i dettagli sugli scenari di carico di lavoro supportati da FastTrack e le aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, è possibile creare un piano di correzione che consentirà all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding di esito positivo.

FastTrack fornisce indicazioni utili per la prima volta con le funzionalità di base (comuni per tutti i servizi online Microsoft) e quindi con l'onboarding di ogni servizio idoneo:

  - [Generale](#general)
  - [Office 365](#office-365)
  - [Sicurezza delle & Enterprise Mobility](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Desktop virtuale Windows](#windows-virtual-desktop)
  - [App Assure](#app-assure)
  - [Il nuovo Microsoft Edge](#the-new-microsoft-edge)

> [!NOTE]
> Per informazioni sulle aspettative dell'ambiente di origine per Office 365 US Government, vedere [source Environment aspettations for office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).
 
## <a name="general"></a>Generale

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Onboarding di base</strong></td>
<td>  Vengono fornite istruzioni Remote sull'onboarding di base, che include il provisioning dei servizi, il tenant e l'integrazione delle identità. Sono inoltre disponibili passaggi per fornire una base per i servizi di onboarding quali Exchange Online, SharePoint Online e Microsoft teams, tra cui una <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussione sulla sicurezza, la connettività di rete e la conformità</a>.  
  L'onboarding per uno o più servizi può iniziare al termine dell'onboarding di base.
</li>
</ul>  

<strong> Integrazione dell'identità </strong>

Sono disponibili linee guida Remote per:
<ul>
<li>Preparazione delle identità di Active Directory locale per la sincronizzazione di Azure Active Directory (Azure AD), inclusa l'installazione e la configurazione di Azure AD Connect (Single-o multi-Forest) e delle licenze (incluse le licenze basate su gruppo).</li>
<li>Creazione di identità cloud inclusa l'importazione in blocco e la gestione delle licenze, incluso l'utilizzo delle licenze basate su gruppo.</li>
<li>Scelta e attivazione del metodo di autenticazione corretto per il percorso Cloud, la sincronizzazione hash delle password, l'autenticazione pass-through o Active Directory Federation Services (AD FS).</li>
<li>Abilitazione di ADFS per i clienti con una singola foresta di Active Directory e le identità sincronizzate con lo strumento Azure AD Connect. Per questo è necessario Windows Server 2012 R2 Active Directory Federation Services 2,0 o versione successiva.</li>
<li>Migrazione dell'autenticazione da AD FS ad Azure ad utilizzando la sincronizzazione hash delle password o l'autenticazione pass-through.</li>
<li>Migrazione delle app preintegrate (come le app di Azure AD Gallery software-as-a-Service (SaaS)) da AD FS ad Azure ad per Single Sign-on (SSO).</li>
<li>Abilitazione delle integrazioni delle app SaaS con SSO dalla raccolta di Azure AD.</li>
<li>Abilitazione del provisioning automatico degli utenti per le app SaaS preintegrate elencate nell' <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">elenco app Integration tutorial</a> (solo per le app SaaS di Azure ad Gallery e per il provisioning in uscita solo).  </li>
</td>

<td>  <strong>Abilitazione della rete </strong>  
  <br>Nell'ambito del vantaggio FastTrack, si consiglia di eseguire le procedure consigliate per la connessione a servizi cloud per garantire i massimi livelli di prestazioni di Microsoft 365.  
  
<strong>Foreste di Active Directory</strong> Il livello di foresta funzionale è impostato su Windows Server 2003 e versioni successive, con la seguente configurazione della foresta:
<ul>
<li>  Una foresta unica di Active Directory.  </li>
<li>  Una singola foresta account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).  </li>
<li>  Più foreste account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).  </li>
<li>  Più foreste account di Active Directory con una delle foreste in posizione centrale nella foresta account di Active Directory contenente Exchange e/o Lync 2010, Lync 2013 o Skype for Business.  </li>
<li>  Più foreste account di Active Directory, ognuna con la propria organizzazione di Exchange.  </li>
<li>  Attività necessarie per la configurazione tenant e l'integrazione con Azure Active Directory, se necessario.   </li>
</ul>
  <strong>Importante</strong>  <ul>
<li>  Per gli scenari a più foreste di Active Directory, se Lync 2010, Lync 2013 o Skype for business è distribuito, deve essere distribuito nella stessa foresta di Active Directory di Exchange.  </li>
<li>  Quando si implementano più foreste di Active Directory con più organizzazioni di Exchange in una configurazione multi-ibrida di Exchange, gli spazi dei nomi UPN (Shared User Principal Name) tra le foreste di origine non sono supportati. Gli spazi dei nomi SMTP primari tra organizzazioni di Exchange devono essere separati. Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=845444">Distribuzioni ibride con più insiemi di strutture di Active Directory</a>.  </li>
<li>  Per tutte le configurazioni di più insiemi di strutture, la distribuzione di Active Directory Federation Services (AD FS) non rientra nell'ambito. Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.  </li>
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
  Inoltre, se si dispone di una macro o di un componente aggiuntivo che ha avuto esito positivo con le versioni precedenti di Office e si verificano problemi di compatibilità, vengono fornite indicazioni per correggere il problema di compatibilità senza costi aggiuntivi tramite il programma app assure. Per ulteriori informazioni, vedere la sezione <strong>assure app</strong> di <a href="#windows-10">Windows 10</a> . </li>
</ul></td>
<td><ul>
<li>  Il software client online deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Integrità della rete</strong></td>
<td>  Vengono fornite istruzioni Remote per ottenere e interpretare i dati chiave di connettività di rete dall'ambiente che illustrano la modalità di allineamento dei siti <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">dell'organizzazione ai principi di connettività di rete di</a>Microsoft. Questo evidenzia il Punteggio di rete che incide direttamente sulla velocità di migrazione, l'esperienza utente, le prestazioni del servizio e l'affidabilità.  
  È inoltre possibile eseguire le operazioni di correzione evidenziate da questi dati per migliorare il Punteggio di rete.  </td>
<td><ul>
<li>  Accesso all'interfaccia di amministrazione di Microsoft 365.  </li>
<li>  Sono necessarie le versioni aggiornate delle app Microsoft 365.  </li>
<li>  Servizi di posizione abilitati <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">in base alle raccomandazioni relative alle prestazioni di rete nell'interfaccia di amministrazione di Microsoft 365 (Preview)</a>.  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Per Exchange Online, è possibile eseguire la procedura per preparare l'organizzazione all'utilizzo della posta elettronica. I passaggi esatti dipendono dall'ambiente di origine e dai piani di migrazione della posta elettronica.  
  Sono disponibili linee guida Remote per:
<ul>
<li>  Configurare le funzionalità di Exchange Online Protection (EOP) per tutti i domini abilitati alla posta elettronica convalidati in Office 365.  </li>
<li>  Puntamento dei record MX (mail Exchange) a Office 365.  </li>
<li>  Configurazione della funzionalità ATP di Office 365 se fa parte del servizio di sottoscrizione. Per ulteriori informazioni, vedere la sezione <strong>Office 365 Advanced Threat Protection</strong> di questa tabella.  </li>
<li>  Configurare la funzionalità di prevenzione della perdita dei dati (DLP) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</li>
<li>  Configurare Office 365 Message Encryption (OME) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</li>
</ul>
  <strong>Nota:</strong> Il servizio di replica delle cassette postali (MRS) tenta di migrare i messaggi di posta elettronica IRM (Information Rights Managed) dalla cassetta postale locale alla corrispondente cassetta postale di Exchange Online. La possibilità di leggere i contenuti protetti dopo la migrazione dipende dal fatto che il cliente esegua il mapping e copi i modelli di Active Directory Rights Managed Services (AD RMS) in Azure Rights Management Service (Azure RMS).  
<ul>
<li>  Configurazione delle porte del firewall.  </li>
<li>  Configurazione di DNS, tra cui il servizio di individuazione automatica, il servizio di gestione dei messaggi (SPF), la posta elettronica identificata di DomainKeys (DKIM), l'autenticazione del messaggio basata sul dominio, la creazione di report e la conformità (DMARC) e i record MX (se necessario).  </li>
<li>  Configurare il flusso di posta elettronica tra l'ambiente di messaggistica di origine e Exchange Online (in base alle esigenze).  </li>
<li>  Eseguire la migrazione della posta dall'ambiente di messaggistica di origine a Office 365.  </li>
<li>  Configurazione di client delle cassette postali (Outlook per Windows, Outlook sul web e Outlook per iOS e Android).  </li>
</ul>
  <strong>Migrazione dei dati</strong>  <br>
Per informazioni sull'utilizzo del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.   
<td>  L'ambiente di origine deve disporre di uno dei livelli minimi seguenti:
<ul>
<li>  Una o più organizzazioni di Exchange con Exchange Server 2003 e versioni successive.  </li>
<li>  Un singolo ambiente di posta elettronica abilitato per il protocollo IMAP.  </li>
<li>  Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).  </li>
<li>  Per informazioni su multi-Geo capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=872776">multi-Geo capabilities in Exchange Online</a>.  </li>
</ul>
Il software client online come Project per Office 365, Outlook per Windows, Outlook per iOS e Android, il client di sincronizzazione di OneDrive for business, il desktop Power BI e Skype for business devono essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 Office</a>.  </td>
</tr>
<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Governance delle informazioni.  </li>
<li>  Etichette e criteri di conservazione.  </li>
<li>  Gestione dei record.  </li>
<li>  Criteri di eliminazione.  </li>
<li>  Conformità delle comunicazioni.  </li>
<li>  Gestione dei rischi Insider.  </li>
<li>  Advanced eDiscovery.  </li>
</ul></td>
<td>Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Classificazione dei dati.  </li>
<li>  Tipi di informazioni sensibili.  </li>
<li>  Creare etichette di riservatezza.  </li>
<li>  Applicare etichette di riservatezza.  </li>
<li>  Etichettatura unificata.  </li>
<li>  Classificatori sottoponibili a formazione.  </li>
<li>  Conoscere i dati tramite Esplora contenuto ed Esplora attività.  </li>
<li>  Pubblicare etichette con criteri (manuale e automatico).  </li>
<li>  Creare criteri di prevenzione della perdita dei dati (DLP) per chat e canali di Microsoft Teams.  </li>
</ul></td>
<td>Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Conferma dei requisiti minimi nei gruppi di Exchange Online, SharePoint Online, Office 365 e Azure AD per il supporto dei team.  </li>
<li>  Configurazione delle porte del firewall.  </li>
<li>  Configurazione di DNS.  </li>
<li>  Conferma dell'abilitazione di Teams nel tenant Office 365.  </li>
<li>  Abilitazione o disabilitazione delle licenze utente.  </li>
<li>  Valutazione della rete per i team:
<ul>
<li>  Controlli di porta ed endpoint.  </li>
<li>  Controlli sulla qualità della connessione.  </li>
<li>  Stime sulla larghezza di banda.  </li>
</ul>
<ul>
<li>  Configurazione dei criteri delle app per i team (teams Web App, teams desktop app e teams for iOS and Android app).  </li>
</ul>
Se applicabile, vengono fornite anche indicazioni per:
<ul>
<li>  Dispositivi della sala Microsoft teams:  </li>
<ul>
<li>  Creazione di account online necessari per i dispositivi di telefonia e sala riunioni supportati, elencati nel <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catalogo dispositivi teams</a>.  </li>
<li>  Assistenza remota con la configurazione sul fianco del servizio dei dispositivi Microsoft teams Rooms certificati.  </li>
<li>  Abilitazione dell'audioconferenza:  </li>
<li>  Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.  </li>
<li>  Assegnazione di bridge per conferenze agli utenti con licenza.  </li>
</ul>
<li>  Sistema telefonico:
<ul>
<li>  Configurazione aziendale delle impostazioni predefinite vocali cloud.  </li>
<li>  Guida ai piani di chiamata (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercati disponibili</a>):
<ul>
<li>  Assegnazione di numeri agli utenti con licenza.  </li>
<li>  Guida alla portabilità del numero locale tramite UI fino a 999.  </li>
<li>  Supporto RS per la richiesta di servizio di portabilità del numero locale superiore a 999.  </li>
</ul></li>
<li>  Guida per il routing diretto:
<ul>
<li>  Linee guida per l'installazione dell'organizzazione per la progettazione di routing diretto di scenari ospitati da partner o scenari distribuiti dal cliente per un massimo di 10 siti.  </li>
<li> Verifica della configurazione del session border controller (SBC). </li>

<li> Assistenza remota con la configurazione del dial plan. </li>

<li> Configurazione della route vocale.</li>

<li> Bypass multimediale e ottimizzazione dei supporti locali. </li>

</ul></li>
</ul></li>
<li>  Abilitazione degli eventi live in Teams.  </li>
<li>  Configurazione dell'organizzazione e integrazione in Microsoft Stream.  </li>
<li>  Linee guida per la transizione da Skype for business a teams.  </li>
</ul></td>
<td><ul>
<li>  Identità abilitate in Azure Active Directory per Office 365.  </li>
<li>  Utenti abilitati per SharePoint Online.  </li>
<li>  Le cassette postali di Exchange sono presenti (online e in locale in una configurazione ibrida di Exchange).  </li>
<li>  Abilitato per i gruppi di Office 365.  </li>
</ul>
  <strong>Nota:</strong>   Se gli utenti non sono assegnati e abilitati con le licenze di SharePoint Online, non avranno l'archiviazione di OneDrive for business in Office 365. La condivisione dei file continua a funzionare nei canali, ma gli utenti non possono condividere file in chat senza OneDrive for Business Storage in Office 365. I team non supportano SharePoint locale.  <br>
  <strong>Nota:</strong>   Lo stato ideale è che tutti gli utenti dispongano delle cassette postali in Exchange Online. Gli utenti con cassette postali ospitate in locale devono avere le rispettive identità sincronizzate con la directory di Office 365 tramite Azure AD Connect. Per questi clienti ibridi di Exchange, se la cassetta postale dell'utente è in locale, l'utente non è in grado di aggiungere o configurare i connettori.  
  I programmi di installazione per i client desktop di Microsoft teams Windows e Mac possono essere scaricati da  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> .  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 Advanced Threat Protection (ATP)</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.  </li>
<li>  Configurazione di automazione, analisi e risposta.  </li>
<li>  Uso del simulatore di attacchi.  </li>
<li>  Creazione di report e analisi delle minacce.  </li>
</ul></td>
<td>Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</td>
</tr>
<tr class="even">
<td><strong>Outlook per iOS e Android</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Download di Outlook per iOS e Android tramite l'Apple App Store e Google Play.  </li>
<li>  Configurazione degli account e accesso alla cassetta postale di Exchange Online.  </li>
<li>  Protezione di Outlook Mobile (vedere <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">protezione di Outlook per iOS e Android in Exchange Online</a> per ulteriori informazioni).  </li>
</ul></td>
<td><ul>
<li>  Identità abilitate in Azure Active Directory per Office 365.  </li>
<li>  Exchange Online configurato e licenze assegnate.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Assegnare licenze di Power BI.  </li>
<li>  Distribuire l'app Power BI Desktop.  </li>
</ul></td>
<td>Il software client online come Power BI desktop deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Verificare la funzionalità di base di SharePoint sulla quale fa affidamento Project Online.  </li>
<li>  Aggiungere il servizio Project Online al tenant (inclusa l'aggiunta di sottoscrizioni per gli utenti).  </li>
<li>  Configurare il pool di risorse organizzazione (ERP).  </li>
<li>  Creare il primo progetto.  </li>
</ul></td>
<td>Il software client online come Project per Office 365 deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional e Premium</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Risoluzione dei problemi di implementazione.  </li>
<li>  Assegnare i contratti di licenza con l'utente finale utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.  </li>
<li>  Installare Client desktop di Project Online dal portale di Office 365 tramite la tecnologia A portata di clic.  </li>
<li>  Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.  </li>
<li>  Configurare un unico server di distribuzione nel sito per Client desktop di Project Online, includendo una guida per la creazione del file configuration.xml da usare con lo strumento di distribuzione di Office 365.  </li>
<li>  Connettere Client desktop di Project Online a Project Online Professional o Project Online Premium.  </li>
</ul></td>
<td>Il software client online come Project per Office 365 deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online e OneDrive for Business</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Configurazione DNS.  </li>
<li>  Configurazione delle porte del firewall.  </li>
<li>  Provisioning di utenti e licenze.  </li>
<li>Abilitazione alla creazione di siti per l'amministratore di SharePoint Online.</li>
<li>Pianificazione delle raccolte di siti.</li>
<li>Protezione del contenuto e gestione delle autorizzazioni.</li>
<li>Configurazione delle caratteristiche di SharePoint Online.</li>
<li>  Configurazione delle funzionalità dell'ambiente ibrido di SharePoint, come la ricerca ibrida, i siti ibridi, la tassonomia ibrida, i tipi di contenuto, la creazione siti in modalità self-service ibrida (solo SharePoint Server 2013), l'icona di avvio delle app estesa, OneDrive for Business ibrido e i siti extranet.  </li>
<li>  Approccio di migrazione.  </li>
</ul>
Vengono fornite indicazioni aggiuntive per OneDrive for business a seconda della versione di SharePoint, ad esempio:
<ul>
<li>  Identificare le opzioni di integrazione e la revisione dell'infrastruttura di rete e della larghezza di banda in locale e online.  </li>
<li>  Installazione di SharePoint Online 2013 SP1 (se applicabile), pianificazione e implementazione dei requisiti di sincronizzazione e identità e identificazione del client di sincronizzazione di OneDrive for business.  </li>
<li>  Pianificazione e implementazione di una singola implementazione per tutti gli utenti (o per una distribuzione in fasi).  </li>
<li>  Assegnazione delle licenze, Reindirizzamento dei siti personali e delle raccolte documenti personale a Office 365 (applicabile a SharePoint Online 2013), impostazione di gruppi di destinatari per controllare l'accesso a OneDrive (applicabile a SharePoint Online 2013).  </li>
<li>Reindirizzamento o spostamento di cartelle note in OneDrive.</li>
<li>  Distribuzione della sincronizzazione client di OneDrive for business.  </li>
</ul>
  <strong>Migrazione dei dati</strong>  <br>
Per informazioni sull'utilizzo del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.
</ul></td>
<td><br><strong>Per l'ambiente ibrido di SharePoint:</strong>  
<ul>
<li>  La configurazione ibrida di SharePoint include la configurazione della ricerca ibrida, dei siti, della tassonomia, dei tipi di contenuto, di OneDrive for business, di un'applicazione di avvio delle app estesa, di siti Extranet e della creazione di siti in modalità self-service connessi da un singolo ambiente SharePoint Online di destinazione.  </li>
</ul>
  <strong>Nota:</strong> La creazione di siti in modalità self-service non è in ambito con i server locali che eseguono SharePoint 2013.  
<ul>
<li>  Per abilitare l'ambiente ibrido di SharePoint, è necessario disporre di uno dei seguenti ambienti locali di SharePoint Server: 2013, 2016 o 2019.  </li>
</ul>
  <strong>Nota:</strong> L'aggiornamento degli ambienti di SharePoint locali a SharePoint Server non è incluso nell'ambito. Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza. Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=853548">livelli di aggiornamento pubblico minimi per le funzionalità ibride di SharePoint</a><em>.</em>  <br>
  <strong>Nota:</strong> Per informazioni su multi-Geo capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=831056">multi-Geo capabilities in OneDrive e SharePoint online in Office 365</a><em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Vengono fornite istruzioni Remote per abilitare il servizio Yammer Enterprise.  
</ul></td>
<td>Il software client online deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Sicurezza delle & Enterprise Mobility

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></td>
<td>  Vengono fornite istruzioni Remote per la protezione delle identità cloud per gli scenari seguenti.  

 <br/>

<strong>Infrastruttura di Fondazione sicura</strong>  </ul>
<ul>
<li>  La configurazione e l'abilitazione dell'autenticazione avanzata per le identità, tra cui la protezione con l'autenticazione a più fattori di Azure (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure Mae e la reimpostazione della password self-service (SSPR).  </li>
<li>  Per i clienti non Azure AD Premium, vengono fornite indicazioni per proteggere le identità utilizzando le impostazioni predefinite per la sicurezza.  </li>
<li>  Per i clienti di Azure AD Premium, vengono fornite indicazioni per proteggere le identità con accesso condizionale.  </li>
<li>  Rilevamento e blocco dell'utilizzo di password deboli con la protezione delle password di Azure AD.  </li>
<li>  Protezione dell'accesso remoto alle app Web locali con proxy di applicazione Azure AD.  </li>
<li>  Abilitazione del rilevamento e del monitoraggio basati sui rischi con la protezione delle identità di Azure.  </li>
<li>  Abilitazione di una schermata di accesso personalizzata, tra cui logo, testo e immagini con personalizzazione personalizzata.  </li>
<li>  Condivisione sicura delle app e dei servizi con gli utenti guest che utilizzano Azure AD B2B.  </li>
<li>  Gestione dell'accesso per gli amministratori di Office 365 mediante ruoli amministrativi basati sul controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.  </li>
<li>  Configuring Hybrid Azure AD join.  </li>
<li>  Configurazione di Azure AD join.  </li>
</ul>
  
<strong>Monitoraggio e creazione di report</strong>  
<ul>
<li>  
  Abilitazione del monitoraggio remoto per ADFS, Azure AD Connect e controller di dominio con Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Governance</strong>  
<ul>
<li>  
  Gestione dell'identità di Azure AD e del ciclo di vita di accesso in scala con la gestione dei diritti di Azure AD.
  </li>
<li>  
  Gestire le appartenenze ai gruppi di Azure AD, l'accesso alle app Enterprise e le assegnazioni di ruolo con le recensioni di Azure AD Access.  
  </li>
<li>  
  Revisione delle condizioni di utilizzo di Azure AD.  
  </li>
<li>  
  Gestione e controllo dell'accesso agli account amministratore privilegiati con Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Automazione ed efficienza </strong>  
<ul>
<li>  
  Abilitazione di Azure AD SSPR.  
  </li>
<li>  Consentendo agli utenti di creare e gestire i propri gruppi di sicurezza cloud o di Office 365 con la gestione di gruppi self-service di Azure AD.  </li>
<li>  Gestione dell'accesso delegato alle app Enterprise con la gestione dei gruppi delegati AD Azure AD.  </li>
<li>  Abilitazione di gruppi dinamici di Azure AD.  </li>
<li>  Organizzazione delle app nel portale My Apps using Collections.  </li>
</ul></td>
<td>Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione di problemi identificati che impediscono l'integrazione con Azure AD e le funzionalità di Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection (P2 o EMS E5)</strong></td>
<td>  Vengono fornite indicazioni su come:
<ul>
<li>  Attivare e configurare il tenant.  </li>
<li>  Creare e configurare etichette e criteri.  </li>
<li>  Applicare la protezione delle informazioni ai documenti.  </li>
<li>  Classificare ed etichettare automaticamente le informazioni nelle app di Office, come Word, PowerPoint, Excel e Outlook, che eseguono Windows e con il client di Azure Information Protection.  </li>
<li>  Utilizzare file inattivi con lo scanner di Azure Information Protection.  </li>
<li>  Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.  </li>
</ul>
Vengono inoltre fornite indicazioni per l'applicazione della protezione tramite Microsoft Azure Rights Management Services (Azure RMS), la crittografia dei messaggi di Office 365 (OME) e la prevenzione della perdita di dati (DLP).  </td>
<td>  È necessario già:
<ul>
<li>  Utilizzo di Azure AD.  </li>
<li>  Utilizzare Windows o iOS (altri sistemi operativi non sono inclusi nell'ambito).  
  </ul>
<strong>Nota</strong>: i computer e i dispositivi mobili devono essere eseguiti in un <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">sistema operativo</a> che supporta Azure Information Protection.  
<li>  Disporre dei percorsi di condivisione file principali.  </li>
<strong>Nota</strong>: il supporto ibrido richiede il connettore ad RMS. 
<li>  Avere una tassonomia di classificazione approvata.  </li>
<li>  Comprendere eventuali restrizioni normative per la gestione delle chiavi protette.  </li>
</ul>
  
<strong>Scanner di Azure Information Protection</strong>  
  
È necessario già:  
<ul>
<li>  Utilizzare Windows Server 2012 R2 o Windows Server 2016.  </li>
<li>  Disporre di una connessione Internet.  </li>
<li>  Microsoft SQL Server 2012 e versioni successive in un'istanza locale o remota.  </li>
<li>  Disporre di un account di servizio creato per Active Directory locale e sincronizzato con Azure AD.  </li>
<li>  Sono stati scaricati AzInfoProtection.exe.  </li>
<li>  Sono state configurate etichette per la classificazione/protezione automatica.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Vengono fornite indicazioni su come preparare l'utilizzo di Intune come provider di gestione dei dispositivi mobili basato sul cloud (MDM) e mobile app Management (MAM) per le app e i dispositivi. I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili. I passaggi possono includere:
<ul>
<li>  Licenze per gli utenti finali.  </li>
<li>  Configurazione delle identità per l'utilizzo da parte di Intune mediante l'uso di Active Directory o identità cloud locali (Azure AD).  </li>
<li>  Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.  </li>
<li>  Configurazione dell'autorità MDM, in base alle esigenze di gestione, tra cui:
<ul>
<li>  Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.  </li>
</ul></li>
<li>  Fornire le indicazioni di MDM per:
<ul>
<li>  Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.  </li>
<li>  Configurare criteri e servizi di gestione MDM come:
<ul>
<li>  Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o Deep Links.  </li>
<li>  Criteri di accesso condizionale.  </li>
<li>  Distribuzione di profili di posta elettronica, reti wireless e VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.  </li>
<li>  Connessione al data warehouse di Intune.  </li>
<li>  Integrare Intune con:
<ul>
<li>  Visualizzatore team per assistenza remota (è necessario un abbonamento a un visualizzatore di Team).  </li>
<li>  Soluzioni partner per la difesa di minacce mobili (MTD) (è necessaria una sottoscrizione di MTD).  </li>
<li>  Una soluzione Telecom Expense Management (è richiesta una sottoscrizione di una soluzione per la gestione delle spese Telecom).  </li>
<li>  Microsoft Defender ATP (sono necessarie licenze Windows E5 o Microsoft 365 E5).  </li>
</ul></li>
<li>  Registrare i dispositivi di ogni piattaforma supportata in Intune.  </li>
</ul></li>
</ul></li>
<li>  Fornire indicazioni sulla protezione delle app:
<ul>
<li>  Configurare criteri di protezione delle app per ogni piattaforma supportata.  </li>
<li>  Configurazione dei criteri di accesso condizionale per le app gestite.  </li>
<li>  Indirizzare i gruppi di utenti corretti con i criteri MAM precedentemente citati.  </li>
<li>  Utilizzo di report sull'utilizzo delle app gestite.  </li>
</ul></li>
<li>  Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.  </li>
</ul>
  <strong>Nota</strong>: la gestione dei PC legacy non è più supportata dal 15 ottobre 2020 e versioni successive.  
</li>
</ul>
  
<strong>Collegamento tramite cloud</strong>  

  Si consiglia di preparare gli ambienti di gestione della configurazione esistenti tramite cloud con Intune. I passaggi esatti dipendono dall'ambiente di origine. Questi passaggi possono includere:  
<ul>
<li>  Licenze per gli utenti finali.  </li>
<li>  Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.  </li>
<li>  Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.  </li>
<li>  Fornire linee guida per la configurazione di un join ibrido di Azure AD.  </li>
<li>  Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.  </li>
<li>  Offrire indicazioni su come configurare il gateway di gestione cloud.  </li>
<li>  Configurare i carichi di lavoro supportati che si desidera passare a Intune.  </li>
<li>  Installare il client Configuration Manager nei dispositivi registrati di Intune.  </li>
</ul> 

<strong>Distribuire Outlook Mobile per iOS e Android in modo sicuro</strong> È possibile fornire assistenza per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire che gli utenti dispongano di tutte le app necessarie installate.  
  La procedura per distribuire in modo sicuro Outlook Mobile per iOS e Android con Intune dipende dall'ambiente di origine. Può includere:
<ul>
<li>  Scaricare le app di Outlook per iOS e Android, Microsoft Authenticator e il portale aziendale di Intune tramite l'App Store di Apple o Google Play Store.  </li>
<li>  Fornire indicazioni sulla configurazione:
<ul>
<li>  Distribuzione di Outlook per iOS e Android, Microsoft Authenticator e Intune per le app del portale aziendale con Intune.  </li>
<li>  Criteri di protezione delle app.  </li>
<li>  Criteri di accesso condizionale.  </li>
<li>  Criteri di configurazione dell'app.  </li>
</ul></li>
</ul>
  
  <strong>Nota</strong>: FastTrack non supporta la protezione di Outlook per iOS e Android con i criteri cassetta postale dei dispositivi mobili di Exchange. Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.  
  </td>
<td>  Gli amministratori IT devono disporre dell'autorità di certificazione, della rete wireless e delle infrastrutture VPN esistenti che già operano nei rispettivi ambienti di produzione durante la pianificazione della distribuzione della rete wireless e dei profili VPN con Intune.  
  <strong>Nota</strong>: il vantaggio del servizio di FastTrack non include assistenza per la configurazione o la configurazione di autorità di certificazione, reti wireless, infrastrutture VPN o certificati push di Apple MDM per Intune.  
 
  <strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud. Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.

  <strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong> 
 
  <strong>Nota</strong>: viene fornita assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10. Non viene fornita assistenza per l'acquisto, la gestione delle licenze o l'attivazione. Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.  
  
<strong>Windows Autopilot</strong> 
 
  Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.  
  
<strong>Distribuire Outlook per iOS e Android in modo sicuro con Intune </strong>  
<ul>
<li>  Identità degli utenti abilitate in Azure Active Directory per Office 365.  </li>
<li>  Exchange Online o Hybrid Exchange configurati con le licenze utente assegnate.  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Vengono fornite indicazioni per l'aggiornamento da Windows 7 Professional e Windows 8,1 Professional a Windows 10 Enterprise.  
  Sono disponibili linee guida Remote per:
<ul>
<li>  Informazioni sull'intenzione di Windows 10.  </li>
<li>  Valutazione dell'ambiente di origine e dei requisiti (verificare che Microsoft endpoint Configuration Manager venga aggiornato al livello richiesto per supportare la distribuzione di Windows 10).  </li>
<li>  Distribuzione delle app di Windows 10 Enterprise e Microsoft 365 tramite Microsoft endpoint Configuration Manager o Microsoft 365.  </li>
<li>  Opzioni di raccomandazione per valutare le app di Windows 10.  </li>
<li>  Abilitazione dell'utilizzo di analisi desktop e linee guida tramite la creazione di un piano di distribuzione di analisi desktop.  </li>
<li>  Microsoft 365 Apps Compatibility assessment by leveraging The Office 365 prontezza dashboard in Configuration Manager o with the stand-alone Pronation Toolkit for Office Plus Assistance Deploying Microsoft 365 Apps.  </li>
<li>  Creazione di un elenco di controllo di correzione su cosa è necessario fare per riportare l'ambiente di origine ai requisiti minimi per una distribuzione corretta.  </li>
<li>  Fornire indicazioni sull'aggiornamento per i dispositivi esistenti a Windows 10 Enterprise, se soddisfano i requisiti hardware necessari per il dispositivo.  </li>
<li>  Fornire indicazioni sull'aggiornamento per supportare il movimento di distribuzione esistente. FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10. Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di Windows Autopilot.  </li>
<li>  Distribuzione di app Microsoft 365 mediante Configuration Manager nell'ambito della distribuzione di Windows 10.   </li>
<li>  Fornire indicazioni per aiutare l'organizzazione a rimanere sempre aggiornati con le app Windows 10 Enterprise e Microsoft 365 utilizzando l'ambiente di gestione della configurazione esistente o Microsoft 365.  </li>
</ul>
  <strong>L'ambito seguente è esterno </strong>  
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
Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.  </td>
<td>  Per l'aggiornamento del PC, è necessario soddisfare i requisiti seguenti:
<ul>
<li>  Sistema operativo di origine: Windows 7 Enterprise o Professional, Windows 8,1 Enterprise o Professional.  </li>
<li>  Dispositivi: fattore di forma desktop, notebook o tablet.  </li>
<li>  Sistema operativo di destinazione: Window 10 Enterprise.  </li>
</ul>
Per l'aggiornamento dell'infrastruttura, è necessario soddisfare i requisiti seguenti:
<ul>
<li>  Gestione configurazione Microsoft endpoint.  </li>
<li>  La versione di Configuration Manager deve essere supportata dalla versione di destinazione di Windows 10. Per ulteriori informazioni, vedere la tabella di supporto di Configuration Manager al <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">supporto di Windows 10 in Configuration Manager</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.  
  Sono disponibili linee guida Remote per:
<ul>
<li>  Distribuzione delle tecnologie per la protezione degli endpoint.  </li>
<li>  Configurazione di Endpoint Protection e dei profili di restrizione del dispositivo.  </li>
<li>  Valutare la versione del sistema operativo e la gestione dei dispositivi (tra cui Intune, Microsoft endpoint Configuration Manager, oggetti Criteri di gruppo (GPO) e configurazioni di terze parti), nonché lo stato di Windows Defender AV Services o di altri software di sicurezza di endpoint.  </li>
<li>  Valutazione dello stato dei servizi AV di Windows o di altri software di sicurezza di endpoint.  </li>
<li>  Valutazione di proxy e firewall che limitano il traffico di rete.  </li>
<li>  Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo di agente ATP utilizzando un endpoint di bordo.  </li>
<li>  Guida alla distribuzione, assistenza alla configurazione e istruzione su:
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
<li>  Revisione delle simulazioni e delle esercitazioni (come gli scenari di esercitazione, il malware falso e le indagini automatizzate).  </li>
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
  Canale semestrale di Windows Server (SAC) versione 1803.  
  </li>
<li>  
  versioni macOS 10,13, 10,14 e 10,15.  
  </li>
</ul>
</li>
</ul>
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft endpoint Configuration Manager (versione 2002 o superiore). 

</li>
</ul>

<strong>L'ambito seguente è esterno </strong>  
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
</ul></li>
<li>  Onboarding e configurazione del server:
<ul>
<li>  
  Configurazione di un server proxy per le comunicazioni offline.  
  </li>
<li>  
  Configurazione di pacchetti di distribuzione di Configuration Manager nelle versioni e nelle varianti di gestione della configurazione.  
  </li>
<li>  
  Onboarding servers to Azure Security Center.  
  </li>
<li>  
  Server non gestiti da Configuration Manager.  
  </li>
</ul></li>
<li>  onboarding e configurazione di macOS:
<ul>
<li>  
  Distribuzione manuale basata su Intune.  
  </li>
<li>  
  Distribuzione basata su GRAFP.
  </li>
<li>  
  Altre distribuzioni basate su prodotto di gestione dei dispositivi mobili (MDM).  
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
  Controllo app.  
  </li>
<li>  
  Protezione dagli exploit.  
  </li>
<li>  
  Firewall di rete.  
  </li>
</ul></li>
<li>  Iscrizione o configurazione di Microsoft Threat Experts.  </li>
<li>  Configurazione o formazione per la revisione delle API o delle informazioni di sicurezza e delle connessioni di gestione eventi (SIEM).  </li>
<li>  Iscrizione o configurazione di Microsoft Threat Protection (MTP).  </li>
<li>  Formazione o indicazioni sulla ricerca avanzata.  </li>
<li>  Formazione o indicazioni su come usare o creare query Kusto.</li>
</li>
</ul>
Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Desktop virtuale Windows

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Desktop virtuale Windows</strong></td>
<td><p>Vengono fornite indicazioni per la distribuzione per l'onboarding su Windows Virtual Desktop (un servizio di virtualizzazione per desktop e app). Windows Virtual Desktop si avvale dell'esperienza multisessione di Windows 10 ed è ottimizzato per le app Microsoft 365 per Enterprise con la sicurezza integrata e la gestione di Microsoft 365.</p>
<p>Sono disponibili linee guida Remote per:</p>
<ul>
<li>Distribuzione dell'ambiente desktop virtuale di Windows con le app di Windows 10 Enterprise Multi-Session e Microsoft 365 per l'organizzazione con quanto segue:
<ul>
<li>Immagine di Azure Marketplace.</li>
<li>Immagine condivisa.</li>
<li>Office Deployment Toolkit (ODT).</li>
</ul></li>
<li>Configurazione di FSLogix:
<ul>
<li>Distribuzione dell'agente di FSLogix con il contenitore di profili.</li>
<li>Distribuzione dell'agente FSLogix con il contenitore di Office.</li>
<li>Configurazione della cartella FSLogix con le esclusioni di contenuto.</li>
</ul></li>
<li>Distribuzione di Microsoft Edge.</li>
<li>Distribuzione di Microsoft teams.</li>
<li>Connessione mediante client desktop virtuali di Windows.</li>
</ul>

<strong>L'ambito seguente è esterno</strong>
<ul>
<li>Gestione dei progetti della distribuzione di Windows Virtual Desktop del cliente.</li>
<li>Supporto nel sito.</li>
<li>Virtualizzazione e distribuzione di app di terze parti.</li>
<li>Immagini personalizzate.</li>
<li>Migrazioni e scenari che coinvolgono VMware e Citrix.</li>
<li>Scenari di Linux.</li>
<li>Conversione o migrazione dei profili utente.</li>
</ul>
Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a>   per assistenza con questi servizi.</td>
<td>È consigliabile che siano già presenti le operazioni seguenti:
<ul>
<li><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisiti relativi alle licenze Desktop virtuali di Windows</a>.</li>
<li>Rete di Azure:
<ul>
<li>Creazione e subnetting della rete virtuale (rete virtuale).</li>
<li>Firewall e gruppi di sicurezza di rete.</li>
<li>VPN e ExpressRoute.</li>
<li>Routing in Azure da locale.</li>
<li>Regole del firewall per consentire la connettività a desktop virtuale di Windows.
</ul>
Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> client desktop remoto supportati</a>.
</ul>
<ul><li>Installazione generale di Azure AD:
<ul>
<li>Strategia <i>di identità (è possibile utilizzare solo una delle tre opzioni seguenti):</i>
<ul>
<li>Active Directory con Azure AD Connect in Azure.</li>
<li>Active Directory con Azure AD Connect in locale tramite VPN o ExpressRoute.</li>
<li>Servizi di dominio Active Directory (AD DS).</li>
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
<th><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></th>
<th><strong>Prodotti supportati</strong></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><strong>App Assure</strong></td>
<td>  App assure è un servizio studiato per risolvere i problemi relativi alla compatibilità delle app Windows 10 e Microsoft 365 Apps. Quando si richiede il servizio app assure, è possibile collaborare con l'utente per risolvere i problemi di app validi senza costi aggiuntivi per l'utente con un abbonamento idoneo. Vengono inoltre fornite indicazioni per i clienti che affrontano i problemi di compatibilità durante la distribuzione di desktop virtuali di Windows e del nuovo Microsoft Edge e offrono ogni ragionevole sforzo per risolvere i problemi di compatibilità. Viene fornita assistenza per la correzione per le app distribuite nei prodotti Microsoft seguenti:
<ul>
<li>  <strong>Windows 10 </strong> (compresi i dispositivi arm64)</li>
<li> <strong>Microsoft 365 Apps</strong>  </li>
<li>  <strong>La nuova Microsoft Edge-</strong> Per informazioni sulle linee guida sulla distribuzione, vedere <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge Channels</a>.  </li>
<li>  Desktop virtuale di <strong>Windows</strong> - Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">che cos'è Windows Virtual Desktop?</a> e <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">domande frequenti su Windows 10 Enterprise Multi-Session</a>.  </li>
</ul>

<strong>L'ambito seguente è esterno </strong>  
<ul>
<li>  Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro di distribuzione desktop</a>. Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito <a href="https://go.microsoft.com/fwlink/?linkid=2053818">modulo</a>.</li>
<li>  Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10. Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</li>
<li>Servizi di sola creazione di pacchetti di app. Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.</li>
</ul>

<strong>Responsabilità del cliente:</strong>  
<ul>
<li>  Creazione di un inventario delle app.</li>
<li>  Convalida di tali app in Windows 10 e Microsoft 365 Apps.</li>
</ul>
<strong>Nota:</strong>  Microsoft non è in grado di apportare modifiche al codice sorgente. Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente. 


  Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.  </td>

</td>
<td><strong>App di Windows 10 e Microsoft 365</strong>
<ul>
<li>  
  Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.  
  </li>
</ul>
<strong>Windows 10 su ARM</strong>
<ul>
<li>  
Le app che hanno lavorato su Windows 7, Office 2010 o versioni successive funzionano con Windows 10 e Microsoft 365 Apps nei dispositivi di ARM64. 
  </li>
</ul>
  <strong>Nota:</strong> Le esclusioni e limitazioni di Windows 10 su ARM includono:
<ul>
<li>  
 App che si basano su driver software che non sono compatibili con ARM.  
  </li>
<li>  
  App che utilizzano OpenGL o OpenCL.   
  </li>
<li>  
  Le app sono disponibili solo in 64 bit (x64).  
  </li>
</ul>
<strong>Nuovo server perimetrale Microsoft</strong>
<ul>
<li>  
  Se le app o i siti Web sono compatibili con Internet Explorer 11, versioni supportate di Google Chrome o qualsiasi versione di Microsoft Edge, saranno compatibili anche con il nuovo Microsoft Edge.  
  </li>
<li>  
  Poiché il Web è in continua evoluzione, assicurarsi di esaminare l'elenco pubblicato delle <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">modifiche note sulla compatibilità dei siti per Microsoft Edge</a>.  
  </li>
</ul>
  <strong>Desktop virtuale di Windows </strong>  
<ul>
<li>  
  Applicazioni virtualizzate che vengono eseguite su Windows Server Remote Desktop Session Host (RDSH) vengono eseguite anche nella multisessione di Windows 10 Enterprise come parte del Desktop virtuale Windows.  
  </li>
<li>  
  Le app in esecuzione su qualsiasi ambiente Windows 7 o Windows 10 Virtual Desktop Infrastructure (VDI) vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte di Windows Virtual Desktop.  
  </li>
<li>  
  Le app che vengono eseguite su dispostivi client di Windows 7 o Windows 10, vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte del Desktop virtuale Windows.  
  </li>
</ul>
  <strong>Nota:</strong> Le esclusioni e limitazioni per la compatibilità tra più sessioni di Windows 10 Enterprise includono:
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

## <a name="the-new-microsoft-edge"></a>Il nuovo Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></th>
<th><strong>Aspettative dell'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><strong>Microsoft Edge</strong> (per i clienti di Windows 10 Enterprise)</td>
<td><ul>
<li>  Vengono fornite indicazioni per la distribuzione remota e assistenza per la compatibilità per: distribuzione del nuovo Microsoft Edge in Windows 10 Enterprise con Microsoft Endpoint Manager (Microsoft endpoint Configuration Manager o Intune).  </li>
<li>  Configurazione Microsoft Edge (mediante criteri di gruppo o di configurazione delle app di Intune e criteri app).  </li>
<li>  Inventariare l'elenco dei siti che possono richiedere l'utilizzo in modalità Internet Explorer.  </li>
<li>  Abilitazione della modalità Internet Explorer con l'elenco dei siti dell'organizzazione esistente.  
  Inoltre, se si dispone di un'app Web o di un sito che funziona con Internet Explorer o Google Chrome e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema senza costi aggiuntivi. Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">app assure</a> .  </li>
</ul>

<strong>L'ambito seguente è esterno </strong>  
<ul>
<li>Gestione dei progetti per la distribuzione di Microsoft Edge del cliente.</li>
<li>  Supporto nel sito.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
