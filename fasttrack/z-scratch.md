## <a name="security-and-compliance"></a>Sicurezza e conformità

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></th>
<th><strong>Aspettative sull'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender è una famiglia di prodotti di difesa aziendale unificata che coordina in modo nativo il rilevamento, la prevenzione, l'analisi e la risposta tra endpoint, identità, posta elettronica e app per garantire la protezione integrata da attacchi sofisticati. Sono disponibili linee guida Remote per: </p> 
<ul>
<li>  Fornire una panoramica del Microsoft 365 Security Center.  </li>
<li>  Revisione degli incidenti incrociati tra i prodotti, tra cui concentrarsi su ciò che è critico garantendo l'ambito di attacco completo, le risorse interessate e le azioni di correzione automatica raggruppate.  </li>
<li>  Dimostrazione del modo in cui Microsoft 365 Defender può orchestrare l'analisi delle risorse, degli utenti, dei dispositivi e delle cassette postali che potrebbero essere state compromesse tramite la correzione automatica. </li>
<li>  Spiegare e fornire esempi di come i clienti possano cercare in modo proattivo i tentativi di intrusione e le attività di violazione che interessano la posta elettronica, i dati, i dispositivi e gli account su più set di dati.   </li>
<li> Mostrare ai clienti come è possibile esaminare e migliorare la propria posizione di sicurezza in modo olistico utilizzando Microsoft Secure score.</li>
</ul>
<p><strong>L'ambito seguente è esterno</strong></p>
<ul>
<li> Gestione dei progetti delle attività di correzione del cliente. </li>
<li> Gestione continua, risposta alle minacce e correzione. </li>
<li> Guida alla distribuzione o istruzione su:
<ul>
<li> Informazioni su come correggere o interpretare i diversi tipi di avviso e le attività monitorate. </li>
<li> Come esaminare un utente, un computer, un percorso di spostamento laterale o un'entità. </li>
<li> Caccia alle minacce personalizzate.  </li>
</ul>
</li>
<li> Informazioni sulla sicurezza e la gestione degli eventi (SIEM) o l'integrazione dell'API.</li>
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft cloud app Security è un broker di sicurezza cloud Access (CASB) che offre una visibilità completa, il controllo dei dati di viaggio e un'analisi avanzata per identificare e combattere le minacce cibernetiche in tutti i servizi cloud di Microsoft e di terze parti. Sono disponibili linee guida Remote per:
<ul>
<li>  Configurazione del portale, tra cui:  </li>
<ul>
<li> Importazione di gruppi di utenti.</li>
<li> Gestione dell'accesso e delle impostazioni di amministratore.  </li>
<li> Ambito della distribuzione per selezionare alcuni gruppi di utenti da monitorare o escludere dal monitoraggio.</li>
<li> Impostazione di intervalli e tag IP.</li>
<li> Personalizzare l'esperienza dell'utente finale con il logo e la messaggistica personalizzata.</li>
</ul>
<li> Impostazione dell'individuazione del cloud per fornire un'ombreggiatura mediante:</li>
<ul>
<li> Microsoft Defender per gli endpoint.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Connessione delle app in <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">primo piano</a> con i connettori app.</li>
<li> Configurare il controllo delle app di accesso condizionale nei portali di accesso condizionale e cloud app Security per applicare i controlli di sessione in tempo reale.</li>
<li> Distribuzione dei dashboard cloud app Security e cloud Discovery.</li>
<li> Personalizzazione dei punteggi dei rischi delle app in base alle priorità dell'organizzazione.</li>
<li> Creazione di tag e categorie di applicazioni.</li>
<li> Sanzionare e non autorizzare le app.</li>
<li> Utilizzo dei registri attività e file.</li>
<li> Gestione delle app OAuth.</li>
<li> Informazioni sulla correlazione degli incidenti nel portale Microsoft 365 Defender.</li>
<li> Fornire assistenza per la configurazione con i <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">primi 20 casi di utilizzo per CASBs</a> (inclusa la creazione o l'aggiornamento di un massimo di sei (6) criteri) ad eccezione di: </li>
<ul>
<li> Controllo della configurazione degli ambienti Internet come servizio (IaaS) (#18).</li>
<li> Monitoraggio delle attività degli utenti per la protezione dalle minacce negli ambienti di IaaS (#19).</li>
</ul>
</ul>
<p><strong>L'ambito seguente è esterno</strong></p>
<ul>
<li> Gestione dei progetti delle attività di correzione del cliente.</li>
<li> Gestione continua, risposta alle minacce e correzione. </li>
<li> Impostazione dell'infrastruttura, dell'installazione o della distribuzione di caricamenti automatici dei registri per i rapporti continui tramite la finestra mobile o un raccoglitore di log. Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> .</li>
<li> Creazione di un report snapshot di individuazione cloud.</li>
<li> Blocco dell'utilizzo delle app tramite script di blocco.</li>
<li> Connessione delle app personalizzate.</li>
<li> Integrazione con provider di identità di terze parti e provider di prevenzione della perdita di dati (DLP).</li>
<li> Formazione o indicazioni sulla ricerca avanzata.</li>
<li> Indagine automatizzata e correzione, tra cui Microsoft Power automatizzate Playbooks.</li>
<li> Informazioni di sicurezza e gestione eventi (SIEM) o API Integration (inclusa la sentinella di Azure).</li>
<li> Distribuzione di cloud app Security come prova del concetto.</li>
</ul></td>
</tr>



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
  Windows Server Semi-Annual Channel (SAC) versione 1803.  
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

<tr class="odd">
<td><strong>Microsoft Defender per l'identità </strong></td>
<td>  Microsoft Defender for Identity è una soluzione di sicurezza basata sul cloud che utilizza i segnali di Active Directory locali per identificare, rilevare ed esaminare le minacce avanzate, le identità compromesse e le azioni di insider dannose indirizzate alla propria organizzazione. Sono disponibili linee guida Remote per:
<ul>
<li>   Creazione dell'istanza di Defender per Identity. </li>
<li>   Connecting Defender for Identity to Active Directory. </li>
<li>   Valutazione della conformità dell'ambiente per la distribuzione del protezione per il sensore di identità nei controller di dominio, tra cui:</li>   
<ul> 
<li>  Esecuzione dello strumento di ridimensionamento per la pianificazione della capacità delle risorse. </li>
<li>  Esecuzione dello strumento di controllo per valutare la compatibilità dei controller di dominio con il sensore. </li>
</ul>
<li>  Distribuzione del sensore per acquisire e analizzare il traffico di rete e gli eventi di Windows direttamente dai controller di dominio, tra cui: </li>
<ul> 
<li>  Download del pacchetto di sensori. </li>
<li>  Configurazione del sensore. </li>
<li>  Installazione del sensore sul controller di dominio in modo invisibile all'utente. </li>
<li>  Distribuzione del sensore nell'ambiente a più foreste. </li>
</ul>
<li>  Integrazione del difensore per l'identità con Microsoft cloud app Security (cloud app Security Licensing non è obbligatorio). </li>
<li>  Fornire indicazioni sulla distribuzione, assistenza per la configurazione e istruzione su: </li>
<ul>
<li> Ottimizzazione dell'ambiente per la riduzione del rumore.  </li>
<li>  Informazioni sul rapporto di valutazione delle posizioni sulla sicurezza delle identità. </li>
<li>  Informazioni sul punteggio di priorità dell'analisi degli utenti e sul rapporto di classificazione dell'analisi degli utenti. </li>
<li> Informazioni sul rapporto utenti inattivi.  </li>
<li> Fornire opzioni di correzione su un account compromesso.  </li>
</ul>
<li>  Facilitare la migrazione da Advanced Threat Analytics (ATA) al difensore dell'identità. </li>
</ul>
<p><strong>L'ambito seguente è esterno</strong></p>
<ul>

<li> Gestione dei progetti delle attività di correzione del cliente. </li>
<li> Gestione continua, risposta alle minacce e correzione.  </li>
<li> Distribuzione del protezione per il sensore di identità, tra cui: </li>
<ul>
<li> Pianificazione della capacità manuale. </li>
<li> Distribuzione del sensore in una capacità autonoma. </li>
<li> Distribuzione del sensore tramite un adattatore per la scheda di interfaccia di rete (NIC). </li>
<li> Distribuzione del sensore tramite uno strumento di terze parti. </li>
<li> Connessione al servizio protezione per il Cloud Identity tramite una connessione proxy Web. </li>
</ul>
<li> Creazione e gestione di honeytokens. </li>
<li> Guida alla distribuzione o istruzione su: </li>
<ul>
<li> Correzione o interpretazione di vari tipi di avviso e attività monitorate.  </li>
<li> Analisi di un utente, un computer, un percorso di spostamento laterale o un'entità. </li>
<li> Minaccia o caccia avanzata. </li>
<li> Risposta agli incidenti. </li>
</ul>
<li> Fornire un'esercitazione sul laboratorio di avviso per la sicurezza per il difensore dell'identità. </li>
<li> Notifica quando il difensore dell'identità rileva attività sospette inviando avvisi di sicurezza al server syslog tramite un sensore nominato.  </li>
<li> Configurazione del difensore per l'identità per eseguire query utilizzando il protocollo SAMR (Security Account Manager Remote) per identificare gli amministratori locali su computer specifici. </li>
<li> Configurazione di soluzioni VPN per aggiungere informazioni dalla connessione VPN alla pagina del profilo di un utente.  </li>
<li> Informazioni di sicurezza e gestione eventi (SIEM) o API Integration (inclusa la sentinella di Azure). </li>
<li> Distribuzione di Defender per i sensori di identità come prova del concetto.</li>
</ul></td>
<td><ul>
<li>  Distribuzione di Active Directory.  </li>
<li>  I controller di dominio che si intende installare Defender per i sensori di identità dispongono di connettività Internet al difensore del servizio Cloud Identity.  </li>
<ul>
<li> Il firewall e il proxy devono essere aperti per comunicare con il servizio Defender per Identity cloud (*. atp.azure.com la porta 443 deve essere aperta).</li>
</ul>
<li> Controller di dominio in esecuzione su una delle opzioni seguenti:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 con KB4487044 (OS Build 17763,316).</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Etichette e criteri di conservazione.  </li>
<li>  Gestione dei record.  </li>
<li>  Criteri di eliminazione.  </li>
<li>  Conformità delle comunicazioni.  </li>
<li>  Gestione dei rischi Insider.  </li>
<li>  Advanced eDiscovery.  </li>
</ul>

  <strong>L'ambito seguente è esterno </strong>  
<ul>
<li> Sviluppo di un piano file di gestione dei record.</li>
<li> Connettori di dati.</li>
<li> Barriere informative.</li>
<li> Gestione degli accessi con privilegi.</li>
<li> Sviluppo dell'architettura delle informazioni in SharePoint.</li>
<li> Scripting e codifica personalizzato.</li>
</td>
<td>Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Sono disponibili linee guida Remote per:
<ul>
<li>  Classificazione dei dati.  </li>
<li>  Tipi di informazioni sensibili.  </li>
<li>  Creare etichette di riservatezza.  </li>
<li>  Applicazione di etichette di riservatezza.  </li>
<li>  Etichettatura unificata.  </li>
<li>  Classificatori sottoponibili a formazione.  </li>
<li>  Conoscere i dati tramite Esplora contenuto ed Esplora attività.  </li>
<li>  Pubblicare etichette con criteri (manuale e automatico).  </li>
<li>  Creare criteri di prevenzione della perdita dei dati (DLP) per chat e canali di Microsoft Teams.  </li>
<li>  Creazione di criteri DLP di endpoint per i dispositivi Windows 10.  </li>
</ul>

<strong>L'ambito seguente è esterno </strong>  
<ul>
<li>Chiave del cliente.</li>
<li>Sviluppo di espressioni regolari (RegEx) personalizzate per i tipi di informazioni riservate.</li>
<li>Creazione o modifica di dizionari di parole chiave.</li>
<li>Scripting e codifica personalizzato.</li>
</ul>
<strong>Nota:</strong> Per ulteriori informazioni, vedere <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.
<ul>

</td>
<td>Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</td>
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

</tbody>
</table>


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><strong>Servizio</strong></TD>
<TD width 50%><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></TD>
<TD width 25%><strong>Aspettative dell'ambiente di origine</strong></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>