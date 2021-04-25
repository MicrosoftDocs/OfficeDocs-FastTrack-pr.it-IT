---
title: Sicurezza e conformità
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: O365-seccomp
localization_priority: None
ms.collection: FastTrack
description: FastTrack Guidance Dettagli per i servizi Microsoft.
ms.openlocfilehash: 000a81c51729deba8d3f5c4d88a0baa918dcd048
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996244"
---
# <a name="security-and-compliance"></a>Sicurezza e conformità

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli guida FastTrack</strong></th>
<th><strong>Aspettative sull'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender è una famiglia di prodotti di difesa aziendale pre e post-violazione unificata che coordina in modo nativo il rilevamento, la prevenzione, l'indagine e la risposta tra endpoint, identità, posta elettronica e app per fornire una protezione integrata da attacchi sofisticati. Forniamo indicazioni remote per: </p> 
<ul>
<li>  Panoramica del Centro sicurezza Microsoft 365.  </li>
<li>  Esame degli incidenti tra prodotti, inclusa la messa a fuoco su ciò che è critico garantendo l'ambito di attacco completo, gli asset influenzati e le azioni di correzione automatizzate raggruppate tra loro.  </li>
<li>  Dimostrazione del modo in cui Microsoft 365 Defender può orchestrare l'analisi di asset, utenti, dispositivi e cassette postali che potrebbero essere state compromesse tramite l'auto-riparazione automatica. </li>
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
<li> Integrazione di informazioni di sicurezza e eventi (SIEM) o API.</li>
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security è un Cloud Access Security Broker (CASB) che offre visibilità avanzata, controllo sui viaggi di dati e analisi sofisticate per identificare e contrastare le minacce informatiche in tutti i servizi cloud microsoft e di terze parti. Forniamo indicazioni remote per:
<ul>
<li>  Configurazione del portale, tra cui:  </li>
<ul>
<li> Importazione di gruppi di utenti.</li>
<li> Gestione dell'accesso e delle impostazioni dell'amministratore.  </li>
<li> Definizione dell'ambito della distribuzione per selezionare determinati gruppi di utenti da monitorare o escludere dal monitoraggio.</li>
<li> Impostazione di intervalli e tag IP.</li>
<li> Personalizzare l'esperienza dell'utente finale con il logo e la messaggistica personalizzata.</li>
</ul>
<li> Configurare l'individuazione cloud per fornire l'IT shadow usando:</li>
<ul>
<li> Microsoft Defender per endpoint.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Connessione <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">di app in primo</a> piano tramite connettori di app.</li>
<li> Configurare il controllo dell'app di accesso condizionale nei portali di Accesso condizionale e Cloud App Security per applicare controlli di sessione in tempo reale.</li>
<li> Distribuzione dei dashboard di Cloud App Security e Cloud Discovery.</li>
<li> Personalizzazione dei punteggi dei rischi delle app in base alle priorità dell'organizzazione.</li>
<li> Creazione di tag e categorie dell'app.</li>
<li> App che sanzionano e annullano l'applicazione.</li>
<li> Utilizzo dei log attività e dei file.</li>
<li> Gestione delle app OAuth.</li>
<li> Informazioni sulla correlazione degli incidenti nel portale di Microsoft 365 Defender.</li>
<li> Fornire assistenza alla configurazione con <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">i 20</a> casi d'uso principali per i casb (inclusa la creazione o l'aggiornamento di un massimo di sei (6) criteri) ad eccezione di: </li>
<ul>
<li> Controllo della configurazione dell'ambiente Internet as a Service (IaaS) (#18).</li>
<li> Monitoraggio delle attività degli utenti per la protezione dalle minacce negli ambienti IaaS (#19).</li>
</ul>
</ul>
<p><strong>L'ambito seguente non è disponibile</strong></p>
<ul>
<li> Gestione dei progetti delle attività di correzione del cliente.</li>
<li> Gestione continua, risposta alle minacce e correzione. </li>
<li> Configurazione dell'infrastruttura, dell'installazione o della distribuzione dei caricamenti automatici dei log per i report continui tramite Docker o un agente di raccolta log. Per <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">ulteriori dettagli, vedere Top 20 use cases for CASBs.</a></li>
<li> Creazione di un report snapshot di Cloud Discovery.</li>
<li> Blocco dell'utilizzo delle app tramite script di blocco.</li>
<li> Connessione di app personalizzate.</li>
<li> Integrazione con provider di identità di terze parti (IsP) e provider di prevenzione della perdita dei dati (DLP).</li>
<li> Formazione o indicazioni sulla ricerca avanzata.</li>
<li> Analisi e correzione automatizzate, inclusi i playbook di Microsoft Power Automate.</li>
<li> Integrazione delle informazioni di sicurezza e degli eventi (SIEM) o delle API (incluso Azure Sentinel).</li>
<li> Distribuzione di Cloud App Security come prova di concetto.</li>
</ul></td>
</tr>



<tr class="odd">
<td><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.  
  Forniamo indicazioni remote per:
<ul>
<li>  Distribuzione delle tecnologie per proteggere gli endpoint.  </li>
<li>  Configurazione dei profili di protezione degli endpoint e di restrizione dei dispositivi.  </li>
<li>  Valutazione della versione del sistema operativo e della gestione dei dispositivi (inclusi Intune, Microsoft Endpoint Configuration Manager, oggetti Criteri di gruppo e configurazioni di terze parti), nonché lo stato dei servizi av di Windows Defender o altro software di sicurezza degli endpoint.  </li>
<li>  Valutazione dello stato dei servizi Windows AV o di altro software di sicurezza degli endpoint.  </li>
<li>  Valutazione dei proxy e dei firewall che limitano il traffico di rete.  </li>
<li>  Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo agente ATP usando un endpoint di onboarding.  </li>
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
  Punteggio di sicurezza.  
  </li>
</ul></li>
<li>  Revisione di simulazioni ed esercitazioni (come scenari di pratica, malware contraffatto e indagini automatizzate).  </li>
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

<strong>L'ambito seguente non è disponibile </strong>  
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
<li>  
  Protezione dagli exploit.  
  </li>
<li>  
  Firewall di rete.  
  </li>
</ul></li>
<li>  Iscrizione o configurazione di Microsoft Threat Experts.  </li>
<li>  Configurazione o formazione che esamina le connessioni SIEM (Security Information and Event Management).  </li>
<li>  Iscrizione o configurazione di Microsoft Threat Protection (MTP).  </li>
<li>  Formazione o indicazioni sulla ricerca avanzata.  </li>
<li>  Formazione o indicazioni su come usare o creare query Kusto.</li>
</li>
</ul>
Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  Microsoft Defender per identità è una soluzione di sicurezza basata sul cloud che sfrutta i segnali di Active Directory locali per identificare, rilevare e analizzare minacce avanzate, identità compromesse ed azioni Insider dannose dirette all'organizzazione. Forniamo indicazioni remote per:
<ul>
<li>   Creazione dell'istanza di Defender per l'identità. </li>
<li>   Connessione di Defender for Identity ad Active Directory. </li>
<li>   Valutare la preparazione dell'ambiente per distribuire il sensore Defender for Identity nei controller di dominio, tra cui:</li>   
<ul> 
<li>  Esecuzione dello strumento di ridimensionamento per la pianificazione della capacità delle risorse. </li>
<li>  Esecuzione dello strumento di controllo per valutare la compatibilità dei controller di dominio con il sensore. </li>
</ul>
<li>  Distribuzione del sensore per acquisire e analizzare il traffico di rete e gli eventi di Windows direttamente dai controller di dominio, tra cui: </li>
<ul> 
<li>  Download del pacchetto del sensore. </li>
<li>  Configurazione del sensore. </li>
<li>  Installazione del sensore nel controller di dominio in modo invisibile all'utente. </li>
<li>  Distribuzione del sensore nell'ambiente a più foreste. </li>
</ul>
<li>  Integrazione di Defender for Identity con Microsoft Cloud App Security (le licenze di Cloud App Security non sono necessarie). </li>
<li>  Fornire indicazioni sulla distribuzione, assistenza alla configurazione e formazione su: </li>
<ul>
<li> Ottimizzazione dell'ambiente per ridurre il "rumore".  </li>
<li>  Informazioni sul report di valutazione della postura di sicurezza dell'identità. </li>
<li>  Informazioni sul punteggio di priorità dell'indagine dell'utente e sul rapporto di classificazione delle indagini degli utenti. </li>
<li> Informazioni sul report degli utenti inattivi.  </li>
<li> Fornire opzioni di correzione per un account compromesso.  </li>
</ul>
<li>  Facilitare la migrazione da Advanced Threat Analytics (ATA) a Defender for Identity. </li>
</ul>
<p><strong>L'ambito seguente non è disponibile</strong></p>
<ul>

<li> Gestione dei progetti delle attività di correzione del cliente. </li>
<li> Gestione continua, risposta alle minacce e correzione.  </li>
<li> Distribuzione del sensore Defender for Identity, tra cui: </li>
<ul>
<li> Pianificazione manuale della capacità. </li>
<li> Distribuzione del sensore in una capacità autonoma. </li>
<li> Distribuzione del sensore tramite una scheda nic (Network Interface Card) Per il teaming. </li>
<li> Distribuzione del sensore tramite uno strumento di terze parti. </li>
<li> Connessione al servizio cloud Defender for Identity tramite una connessione proxy Web. </li>
</ul>
<li> Creazione e gestione di honeytoken. </li>
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
<li> Distribuzione di Defender per i sensori di identità come prova di concetto.</li>
</ul></td>
<td><ul>
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
<li> Windows Server 2019 con KB4487044 (OS Build 17763.316).</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft Information Governance</strong></td>
<td>  Forniamo indicazioni remote per:
<ul>
<li>  Etichette e criteri di conservazione.  </li>
<li>  Gestione dei record.  </li>
<li>  Criteri di eliminazione.  </li>
<li>  Conformità delle comunicazioni.  </li>
<li>  Gestione dei rischi Insider.  </li>
<li>  Advanced eDiscovery.  </li>
</ul>

  <strong>L'ambito seguente non è disponibile </strong>  
<ul>
<li> Sviluppo di un piano di gestione dei record.</li>
<li> Connettori dati.</li>
<li> Barriere d'informazione.</li>
<li> Gestione degli accessi con privilegi.</li>
<li> Sviluppo dell'architettura delle informazioni in SharePoint.</li>
<li> Script e codifica personalizzati.</li>
</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> core in <a href="products-and-capabilities.md#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Forniamo indicazioni remote per:
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
<li>  Creazione di criteri DLP degli endpoint per i dispositivi Windows 10.  </li>
</ul>

<strong>L'ambito seguente non è disponibile </strong>  
<ul>
<li>Codice cliente.</li>
<li>Sviluppo di espressioni regolari personalizzate (RegEx) per tipi di informazioni riservate.</li>
<li>Creazione o modifica di dizionari di parole chiave.</li>
<li>Script e codifica personalizzati.</li>
</ul>
<strong>Nota:</strong> Per ulteriori informazioni, vedere <strong>Azure Information Protection</strong> in Enterprise Mobility + <a href="products-and-capabilities.md#enterprise-mobility--security">Security.</a>
<ul>

</td>
<td>A parte la <strong>parte relativa all'onboarding</strong> core in <a href="products-and-capabilities.md#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
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
<td>A parte la <strong>parte relativa all'onboarding</strong> core in <a href="products-and-capabilities.md#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>


<tr class="odd">
<td><strong>Discovery & Response</strong></td>
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
<td>A parte la <strong>parte relativa all'onboarding</strong> core in <a href="products-and-capabilities.md#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>
<tr class="odd">
<td><strong>Insider Threat Management</strong></td>

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
<li> Creazione e gestione dei flussi di Power Automate.</li>
<li> Connettori dati (oltre il connettore HR). </li>
<li> Configurazioni di espressioni regolari personalizzate (RegEx).</li>
<li> Revisione dei documenti di progettazione, architetto e di terze parti.</li>
<li> Barriere d'informazione.</li>
<li> Gestione degli accessi con privilegi.</li>
<li> Conformità alle normative e ai requisiti del settore e regionale.</li>
<li> Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</li>
</ul></td>
<td>A parte la <strong>parte relativa all'onboarding</strong> core in <a href="products-and-capabilities.md#general">Generale,</a>non esistono requisiti minimi di sistema.</td>
</tr>


</tbody>
</table>












</tbody>
</table>


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><strong>Servizio</strong></TD>
<TD width 50%><strong>Informazioni aggiuntive su FastTrack</strong></TD>
<TD width 25%><strong>Aspettative dell'ambiente di origine</strong></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>