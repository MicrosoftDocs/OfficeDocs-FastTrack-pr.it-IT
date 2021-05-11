---
title: Migrazione dei dati
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack consente di eseguire la migrazione della posta elettronica e dei file negli ambienti di origine in Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). Il tipo di assistenza che forniamo varia in base al numero di licenze di Office 365.
ms.openlocfilehash: 0e33e8a79ebc577188644dbc69cd78707a575838
ms.sourcegitcommit: 69a30fee5e7e199bd6830fb0837af1ae4904ef3b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/11/2021
ms.locfileid: "52312444"
---
# <a name="data-migration"></a>Migrazione dei dati

FastTrack consente di eseguire la migrazione della posta elettronica e dei file negli ambienti di origine in Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).

Il tipo di assistenza che forniamo varia in base al numero di licenze di Office 365:

  - **Per i tenant di Office 365 con 150-499 licenze**: FastTrack fornisce solo una guida alla migrazione. Tu sei il responsabile dell'esecuzione della migrazione dei dati. Ti guideremo attraverso la documentazione che ti aiuta a pianificare e usare strumenti gratuiti per eseguire una migrazione in modalità self-service.
  - **Per i tenant di Office 365 con 500 o più licenze**: FastTrack fornisce indicazioni di migrazione e servizi di migrazione dei dati. Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e il tenant di Office 365 e usare a tuo vantaggio i nostri servizi di migrazione dei dati per la migrazione dati. Crea e pianifica gli eventi di migrazione. Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.

> [!NOTE]
> Se hai acquistato o rinnovato un piano commerciale prima del 1/9/2017, sono necessarie solo 150 licenze per qualificarsi ai servizi di migrazione dei dati. Per i piani per il settore dell'istruzione, solo l'istituto di istruzione a pagamento e il personale sono idonei per i servizi di migrazione.

### <a name="considerations"></a>Considerazioni

  - Per eseguire la migrazione dei dati in Office 365, è necessario che gli ambienti di origine soddisfino aspettative specifiche. Per altre informazioni sulle aspettative relative all’ambiente di origine di Exchange, SharePoint e OneDrive for Business, consulta [Prodotti e funzionalità ](products-and-capabilities.md).
  - Sono necessari l'accesso e le autorizzazioni appropriate agli ambienti di origine e al tenant di Office 365 per offrire servizi di migrazione dei dati.
  - I servizi di migrazione dei dati non sono progettati né destinati per i dati soggetti a particolari requisiti normativi o legali. Durante la migrazione dei dati, è possibile trasferire, archiviare ed elaborare i dati da qualsiasi luogo in cui vengono gestiti i servizi, ad eccezione di quanto specificato per il progetto di migrazione FastTrack.
  - Microsoft non garantisce la velocità di migrazione dei file o e-mail.
  - Problemi imprevisti (come elementi illeggibili o corrotti nell'ambiente di origine) possono impedire la capacità di migrazione di alcuni dati.
  - Fattori esterni fuori controllo, come modifiche apportate alle interfacce API per le applicazioni di terze parti, possono comportare modifiche, ritardi o sospensioni dei servizi di migrazione dati.

### <a name="migration-service-availability"></a>Disponibilità servizio migrazione

  - **Per clienti commerciali e del governo del Regno Unito:** Microsoft offre servizi di migrazione dei dati, 24 ore al giorno, sette (7) giorni alla settimana (24x7).
  - **Per i clienti del governo e del Dipartimento della difesa degli Stati Uniti:** Microsoft offre servizi di migrazione dei dati, 24 ore al giorno, cinque (5) giorni lavorativi alla settimana (24x5).

## <a name="migration-to-exchange-online"></a>Migrazione a Exchange Online

Se scegli di usare FastTrack per eseguire la migrazione della posta elettronica a Exchange Online, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati. Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e Exchange Online e usare a tuo vantaggio i nostri servizi di migrazione dati per le cassette postali. Crea e pianifica gli eventi di migrazione. Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato. Al termine degli eventi di migrazione, è possibile che la posta proveniente dalle cassette postali di origine idonee e pianificate in modo appropriato degli ambienti di origine sia stata migrata a Exchange Online.

### <a name="considerations"></a>Considerazioni

  - Prima della migrazione, è necessario completare FastTrack Core onboarding per Exchange Online.
      - Se hai già eseguito l’onboarding personalmente, è necessario superare i controlli e prerequisiti necessari. Per informazioni dettagliate, visita [Prodotti e funzionalità](products-and-capabilities.md).
  - FastTrack migra soltanto verso cassette postali di Office 365 attive.
  - È necessario soddisfare requisiti specifici se intendi migrare da un ambiente Exchange locale. Per informazioni dettagliate, visita [Prerequisiti di distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).
  - Ogni ambiente di origine deve essere al livello di aggiornamento del Service Pack (SP) e del rollup (RU)/aggiornamento cumulativo (CU) per il rispettivo prodotto nell'ambiente di origine.
  - Le liste di distribuzione (oggetti *MailEnabledGroup*) e i contatti esterni (oggetti *MailEnabledContact*) che si trovano in Active Directory locale non fanno parte della migrazione dei dati delle cassette postali. È possibile tuttavia sincronizzarli con Azure Active Directory (Azure AD) Connect. 

## <a name="source-environments"></a>Ambienti di origine

Il servizio di migrazione dei dati esegue la migrazione dei dati dai seguenti ambienti di origine:

  - Una o più insiemi di strutture di Active Directory con una o multiple organizzazioni di Exchange (ogni sistema di posta di Exchange deve essere Exchange 2010 o versione successiva).
  - Un ambiente di posta elettronica con funzionalità IMAP singola.
  - Ambiente G Suite (solo Gmail, Contatti e Calendario)

Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:

<table>
<thead>
<tr class="header">
<th><strong>Ambiente di origine</strong></th>
<th><strong>Tipo di migrazione</strong></th>
<th><strong>Cosa migra</strong></th>
<th><strong>Cosa non migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010, Exchange 2013, Exchange 2016 o Exchange 2019</strong><br />
<br />
<strong>Nota:</strong> Per le dipendenze Exchange locali, vedere <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Prerequisiti per la distribuzione ibrida.</span></a></td>
<td>Migrazione con distribuzione ibrida</td>
<td><ul>
<li>Messaggi di posta elettronica</li>
<li>Regole delle cassette postali sul lato server</li>
<li>Delegati</li>
<li>Contatti della cassetta postale </li>
<li> Calendario </li>
<li> Attività </li>
<li> Messaggi di posta elettronica con contenuto protetto da Microsoft Rights Management </li>
<li> Messaggi di posta elettronica crittografati </li>
<li> Firme </li>
<li> Archivio personale migrato con la cassetta postale dell'utente </li>
<li> Elementi ripristinabili </li>
</ul></td>
<td><ul>
<li> Cartelle pubbliche </li>
<li> Tutti i messaggi di posta elettronica che superano il limite relativo alla dimensione </li>
<li> Archivio di inserimento nel journal oppure tutte le altre soluzioni di archiviazione di terze parti </li>
<li> Utenti bloccati o inattivi </li>
<li> Archiviazione dati da file PST (Personal Storage Table) </li>
<li> Elementi danneggiati </li>
<li> Cassette postali inattive </li>
<li> Regole delle cassette postali sul lato client</li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Ambiente G Suite (solo Gmail, Contatti e Calendario)</strong><br />
<br />
<strong>Nota:</strong> L'ambiente G Suite deve soddisfare i prerequisiti descritti in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration.</a></td>
<td>Completa o a fasi</td>
<td><ul>
<li> Messaggi di posta elettronica </li>
<li> Contatti di cassette postali (al massimo tre indirizzi di posta elettronica per ogni contatto) </li>
<li> Calendario </li>
<li> Etichette </li>
</ul></td>
<td><ul>
<li> regole </li>
<li> Delegati </li>
<li> Firme </li>
<li> Attività </li>
<li> Tutti i messaggi di posta elettronica o allegati che superano il limite relativo alla dimensione </li>
<li> Utenti bloccati o inattivi </li>
<li> Archiviazione dati da file PST o da una soluzione di archiviazione di terze parti (ad esempio, Google Vault) </li>
<li> Messaggi di posta elettronica crittografati o con contenuto protetto </li>
<li> Elementi danneggiati </li>
<li> Hangouts di Google** </li>
<li> Gruppi di Google </li>
<li> Cassette postali per la risorsa </li>
<li> Cassette postali inattive </li>
<li> Impostazioni delle ferie e impostazioni di risposta automatica </li>
<li> Calendari condivisi, allegati cloud, collegamenti di Google Hangout e colori per gli eventi </li>
</ul>
**È stata eseguita la migrazioni di conversazioni di Hangout salvate come etichetta. </td>
</tr>
<tr class="odd">
<td><strong>Origine IMAP4 (come Domino, GroupWise o Zimbra)</strong></td>
<td>Migrazione tramite strumenti nativi di IMAP4</td>
<td><li>Messaggi di posta elettronica </li></td>
<td><ul>
<li> Regole </li>
<li> Delegati </li>
<li> Liste di distribuzione </li>
<li> Contatti esterni </li>
<li> Utenti abilitati all'utilizzo della posta </li>
<li> Utenti bloccati o inattivi </li>
<li> Contatti della cassetta postale </li>
<li> Calendario </li>
<li> Firme </li>
<li> Attività </li>
<li> Tutte le e-mail che superano il limite per la dimensione del messaggio </li>
<li> Archiviazione dati </li>
<li> Messaggi di posta elettronica crittografati </li>
<li> Elementi danneggiati </li>
<li> Cassette postali inattive </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a>Responsabilità di FastTrack per Exchange Online migrazioni

Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione. Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.

Gli specialisti di FastTrack eseguono anche le attività seguenti, specifiche della migrazione di Exchange:

  -  Forniscono indicazioni utili per abilitare la coesistenza di routing della posta SMTP tra gli ambienti di origine e Exchange Online, se applicabile.

### <a name="your-responsibilities"></a>Responsabilità dell'utente

Tu esegui attività standard durante il progetto di migrazione. Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.

Tu esegui anche le attività seguenti, specifiche della migrazione di Exchange:

  - Completamento FastTrack Core onboarding per Exchange Online. Se hai già eseguito l’onboarding personalmente, è necessario superare i controlli e prerequisiti necessari. Per informazioni dettagliate, visita [Prodotti e funzionalità](products-and-capabilities.md).
  -  Installazione del livello appropriato di software client in base alle linee guida di Office 365. Per informazioni dettagliate, vedere [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).
  -  Soddisfare i requisiti specifici se intendi migrare da un ambiente Exchange locale. Per informazioni dettagliate, visita [Prerequisiti di distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).
  -  Assicurati che ogni ambiente di origine si trovi al livello di aggiornamento del Service Pack (SP) e del rollup (RU)/aggiornamento cumulativo (CU), se applicabile.
  -  Configura e convalida la coesistenza di routing della posta SMTP tra gli ambienti di origine e Exchange Online, se applicabile.
  -  Verifica che le dimensioni della cassetta postale di origine non superino la quota di destinazione. A seconda della piattaforma di origine, potrebbe essere necessario limitare i dati di origine all’85% della quota delle cassette postali di destinazione.
  -  Puoi migrare i dati dal lato client. Tale migrazione include, ad esempio, le rubriche locali, i dati dei file PST locali, le regole di Outlook e le impostazioni di Outlook locale.
  -  Aiutare gli utenti finali a correggere i problemi di migrazione sul lato client.

## <a name="migration-to-sharepoint-online"></a>Migrazione a SharePoint Online

Se scegli di usare FastTrack per eseguire la migrazione dei tuoi file di SharePoint Online, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati. Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e SharePoint Online e usare a tuo vantaggio i nostri servizi di migrazione dati per i tuoi file. Crea e pianifica gli eventi di migrazione. Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato. Al termine degli eventi di migrazione, è possibile che i file provenienti da fonti opportunamente programmate e idonee dei vostri ambienti di origine siano stati migrati a SharePoint Online.

### <a name="considerations"></a>Considerazioni

 - Tutte le migrazioni sono soggette a quote di SharePoint Online. Per informazioni <a href="https://go.microsoft.com/fwlink/?LinkId=698855">dettagliate, SharePoint limiti</a> di sicurezza. 
  - È consigliabile limitare l'importo complessivo della migrazione al 75% della quota complessiva di SharePoint Online a cui si ha diritto (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente).

### <a name="source-environment-details"></a>Dettagli ambiente di origine

Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine:

  - Condivisioni di file (condivisioni di file di Server Message Block su dispositivi che supportano SMB 2.0 e versioni successive).
  - Un singolo ambiente di G Suite (soltanto Google Drive).
  - Box (Starter, Business, Enterprise).
  - Dropbox per Team (Standard e Advanced).

Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:

<table>
<thead>
<tr class="header">
<th><strong>Ambiente di origine</strong></th>
<th><strong>Tipo di migrazione</strong></th>
<th><strong>Cosa migra</strong></th>
 <th><strong>Cosa non migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per file e cartelle a livello di utente* </li>
<li> Autorizzazioni per file e cartelle a livello di gruppo* </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
</ul>
*Configurazione della sincronizzazione della directory necessaria. Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows. Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate. Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.</td>
<td><ul>
<li> Cronologia di proprietà e versioni precedenti </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Versioni precedenti </li>
<li> File di Windows e attributi di cartella (come Di sola lettura e Nascosto) </li>
<li> Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS): </li>
<li> Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre) </li>
<li> Configurazione di controllo NTFS </li>
<li> Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI) </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Condivisioni nascoste </li>
<li> Condivisione (come autorizzazioni concesse a livello di condivisione) </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Ambiente G Suite singolo (solo Google Drive)</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente), anche quelli di oltre 10 MB </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per cartelle a livello di utente </li>
<li> Autorizzazioni per cartelle a livello di gruppo </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
<li> Unità condivise (cartelle e file) </li>
<li> Contenuto condiviso appartenente all'account Google Drive in corso di migrazione </li>
</ul></td>
<td><ul>
<li> Cronologia di proprietà, versioni precedenti e commenti </li>
<li> Descrizioni di file e cartelle, colori delle cartelle </li>
<li> Autorizzazioni per file a livello di utente </li>
<li> Autorizzazioni per file a livello di gruppo </li>
<li> Metadati avanzati </li>
<li> Attributi di blocco di file </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Elementi eliminati </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Utenti bloccati o inattivi </li>
<li> Google Photos, Moduli, Maps e altre app connesse </li>
<li> Disegni Google </li>
<li> Contenuti condivisi esterni alla tua impresa </li>
<li> Contenuto che appartenente all'account Google Drive che è in corso di migrazione </li>
<li> Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni. Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione). </li>
<li> Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise. Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione). </li>
<li> File contrassegnati come limitati o non copiabili </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per cartelle a livello di utente </li>
<li> Autorizzazioni per cartelle a livello di gruppo </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
<li> Contenuto condiviso appartenente all'account Box in corso di migrazione </li>
<li> Note casella (convertite in formato documento Word) </li>
</ul></td>
<td><ul>
<li> Cronologia di proprietà, versioni precedenti e commenti </li>
<li> Descrizioni di file e cartelle </li>
<li> Autorizzazioni per file a livello di utente </li>
<li> Autorizzazioni per file a livello di gruppo </li>
<li> Tag Box e metadati avanzati </li>
<li> Attributi di blocco di file </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Elementi eliminati </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Utenti bloccati o inattivi </li>
<li> App Box, Segnalibri, Preferiti e Flussi di lavoro </li>
<li> Contenuto non di proprietà dell'account Box migrato </li>
<li> Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni. Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione). </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox per Team (Standard e Advanced)</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per cartelle a livello di utente </li>
<li> Autorizzazioni per cartelle a livello di gruppo </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
<li> Contenuto e cartelle del team condiviso </li>
<li> Contenuto condiviso appartenente all'account Dropbox in corso di migrazione </li>
</ul></td>
<td><ul>
<li> Cronologia di proprietà, versioni precedenti e commenti </li>
<li> Descrizioni di file e cartelle </li>
<li> Autorizzazioni per file a livello di utente </li>
<li> Autorizzazioni per file a livello di gruppo </li>
<li> Metadati avanzati </li>
<li> Attributi di blocco di file </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Elementi eliminati </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Cartelle Dropbox non montate </li>
<li> Utenti eliminati o scollegati </li>
<li> Dropbox Paper, Showcases, e Spaces </li>
<li> App e preferiti di Dropbox (Pins/stars) </li>
<li> Contenuto non di proprietà dell'account Dropbox migrato </li>
<li> Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni. Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione) </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a>Responsabilità di FastTrack per le migrazioni SharePoint Online

Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione. Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli

### <a name="your-responsibilities"></a>Responsabilità dell'utente

Tu esegui attività standard durante il progetto di migrazione. Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli

Tu esegui anche le attività seguenti, specifiche della migrazione di SharePoint Online:

  - Esecuzione del provisioning di tutti i siti del team di SharePoint per gli eventi di migrazione.

## <a name="migration-to-onedrive-for-business"></a>Migrazione a OneDrive for Business

Se scegli di usare FastTrack per eseguire la migrazione dei tuoi file di OneDrive for Business, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati. Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e OneDrive for Business e usare a tuo vantaggio i nostri servizi di migrazione dati per i tuoi file. Crea e pianifica gli eventi di migrazione. Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato. Al termine degli eventi di migrazione, è possibile che i file provenienti da fonti opportunamente programmate e idonee dei vostri ambienti di origine siano stati migrati a OneDrive for Business.

### <a name="considerations"></a>Considerazioni

  - Tutte le migrazioni sono soggette a quote di SharePoint Online. Per informazioni <a href="https://go.microsoft.com/fwlink/?LinkId=698855">dettagliate, SharePoint limiti</a> di sicurezza. 
  - È consigliabile limitare la quantità totale dei dati migrati al 75% della quota di archiviazione globale di SharePoint Online a cui si è autorizzati (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente).
  - FastTrack esegue la migrazione solo alle unità attive di OneDrive for Business.

### <a name="source-environment-details"></a>Dettagli ambiente di origine

Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine:

  - Condivisioni di file (condivisioni di file SMB su dispositivi che supportano SMB 2.0 e versioni successive).
  - Ambiente G Suite singolo (solo Google Drive)
  - Box (Starter, Business, Enterprise).
  - Dropbox per Team (Standard e Advanced).

Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:

<table>
<thead>
<tr class="header">
 <th><strong>Ambiente di origine</strong></th>
 <th><strong>Tipo di migrazione</strong></th>
 <th><strong>Cosa migra</strong></th>
 <th><strong>Cosa non migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per file e cartelle a livello di utente* </li>
<li> Autorizzazioni per file e cartelle a livello di gruppo* </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
</ul>
<br>
*Configurazione della sincronizzazione della directory necessaria. Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows. Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate. Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB. </td>
<td><ul>
<li> Cronologia di proprietà e versioni precedenti </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Versioni precedenti </li>
<li> File di Windows e attributi di cartella (come Di sola lettura e Nascosto) </li>
<li> Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS): </li>
<li> Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre) </li>
<li> Configurazione di controllo NTFS </li>
<li> Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI) </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Condivisioni nascoste </li>
<li> Condivisione (come autorizzazioni concesse a livello di condivisione) </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Ambiente G Suite singolo (solo Google Drive)</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente, anche quelli di oltre 10 MB) </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per cartelle a livello di utente </li>
<li> Autorizzazioni per cartelle a livello di gruppo </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
<li> Unità condivise (cartelle e file) </li>
<li> Contenuto condiviso appartenente all'account Google Drive in corso di migrazione </li>
</ul></td>
<td><ul>
<li> Cronologia di proprietà, versioni precedenti e commenti </li>
<li> Descrizioni di file e cartelle, colori delle cartelle </li>
<li> Autorizzazioni per file a livello di utente </li>
<li> Autorizzazioni per file a livello di gruppo </li>
<li> Metadati avanzati </li>
<li> Attributi di blocco di file </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Elementi eliminati </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Utenti bloccati o inattivi </li>
<li> Google Photos, Moduli, Maps e altre app connesse </li>
<li> Disegni Google </li>
<li> Contenuti condivisi esterni alla tua impresa </li>
<li> Contenuto che appartenente all'account Google Drive che è in corso di migrazione </li>
<li> Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni. Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione). </li>
<li> Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise. Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione). </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per cartelle a livello di utente </li>
<li> Autorizzazioni per cartelle a livello di gruppo </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
<li> Contenuto condiviso appartenente all'account Box in corso di migrazione </li>
</ul></td>
<td><ul>
<li> Cronologia di proprietà, versioni precedenti e commenti </li>
<li> Descrizioni di file e cartelle </li>
<li> Autorizzazioni per file a livello di utente </li>
<li> Autorizzazioni per file a livello di gruppo </li>
<li> Tag Box e metadati avanzati </li>
<li> Attributi di blocco di file </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Elementi eliminati </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Utenti bloccati o inattivi </li>
<li> App Box, Segnalibri, Preferiti e Flussi di lavoro </li>
<li> Contenuto non di proprietà dell'account Box migrato </li>
<li> Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni. Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione). </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox per Team (Standard e Advanced)</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per cartelle a livello di utente </li>
<li> Autorizzazioni per cartelle a livello di gruppo </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
<li> Contenuto e cartelle del team condiviso </li>
<li> Contenuto condiviso appartenente all'account Dropbox in corso di migrazione </li>
</ul></td>
<td><ul>
<li> Cronologia di proprietà, versioni precedenti e commenti </li>
<li> Descrizioni di file e cartelle </li>
<li> Autorizzazioni per file a livello di utente </li>
<li> Autorizzazioni per file a livello di gruppo </li>
<li> Metadati avanzati </li>
<li> Attributi di blocco di file </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Elementi eliminati </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Cartelle Dropbox non montate </li>
<li> Utenti eliminati o scollegati </li>
<li> Dropbox Paper, Showcases, e Spaces </li>
<li> App e preferiti di Dropbox (Pins/stars) </li>
<li> Contenuto non di proprietà dell'account Dropbox migrato </li>
<li> Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni. Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione). </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a>Responsabilità di FastTrack per OneDrive for Business migrazioni

Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione. Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.

### <a name="your-responsibilities"></a>Responsabilità dell'utente

Tu esegui attività standard durante il progetto di migrazione. Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.

Tu esegui anche le attività seguenti, specifiche della migrazione di OneDrive for Business:

  - Esecuzione del provisioning di tutti i siti di OneDrive for Business che verranno assegnati agli eventi di migrazione.

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a>Migrazione a Microsoft Teams e Microsoft 365 gruppi

Quando si sceglie di usare FastTrack per eseguire la migrazione dei file a Microsoft Teams e Microsoft 365, vengono fornite indicazioni sulla migrazione e servizi di migrazione dei dati. Vengono fornite indicazioni per pianificare la migrazione, configurare gli ambienti di origine e i gruppi Teams e Microsoft 365 e sfruttare i servizi di migrazione dei dati per eseguire la migrazione dei file. Crea e pianifica gli eventi di migrazione. Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato. Una volta completati gli eventi di migrazione, è possibile prevedere la migrazione dei file delle origini pianificate e idonee degli ambienti di origine in Teams e Microsoft 365 gruppi. Teams e i Microsoft 365 devono essere pre-provisioning dal cliente prima di poter eseguire la migrazione dei dati in questi tipi di destinazione. Teams e Microsoft 365 gruppi influiscono sulle autorizzazioni sul percorso di destinazione del file. Teams e Microsoft 365 sono creati per consentire la collaborazione. Il Teams o il Microsoft 365 determinano chi ha accesso a tali file durante la migrazione in tali destinazioni. FastTrack non aggiunge utenti finali o gruppi ad alcun canale Teams o Microsoft 365 gruppi durante la migrazione.

### <a name="considerations"></a>Considerazioni

- Tutte le migrazioni sono soggette a quote di SharePoint Online. Per informazioni <a href="https://go.microsoft.com/fwlink/?LinkId=698855">dettagliate, SharePoint limiti</a> di sicurezza. 
- È consigliabile limitare l'importo complessivo della migrazione al 75% della quota complessiva di SharePoint Online a cui si ha diritto (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente). 


### <a name="source-environment-details"></a>Dettagli ambiente di origine

Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine: 

- Condivisioni di file (condivisioni di file di Server Message Block su dispositivi che supportano SMB 2.0 e versioni successive).
-  Un singolo ambiente di G Suite (soltanto Google Drive). 
- Box (Starter, Business, Enterprise). 
- Dropbox per Team (Standard e Advanced). 

Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:

<table>
<thead>
<tr class="header">
 <th><strong>Ambiente di origine</strong></th>
 <th><strong>Tipo di migrazione</strong></th>
 <th><strong>Cosa migra</strong></th>
 <th><strong>Cosa non migra</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per file e cartelle a livello di utente* </li>
<li> Autorizzazioni per file e cartelle a livello di gruppo* </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
</ul>
<br>
*Configurazione della sincronizzazione della directory necessaria. Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows. Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate. Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB. Le autorizzazioni sono influenzate dal Microsoft 365 e/o Microsoft Teams canale. Se la destinazione è un Microsoft 365 gruppo o Microsoft Teams, il gruppo o il canale determina il profilo delle autorizzazioni finali per i file migrati. È consigliabile non eseguire la migrazione delle autorizzazioni per la migrazione dei file a un Microsoft 365 gruppo o Microsoft Teams canale.</td>
<td><ul>
<li> Cronologia di proprietà e versioni precedenti </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Versioni precedenti </li>
<li> File di Windows e attributi di cartella (come Di sola lettura e Nascosto) </li>
<li> Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS): </li>
<li> Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre) </li>
<li> Configurazione di controllo NTFS </li>
<li> Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI) </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Condivisioni nascoste </li>
<li> Condivisione (come autorizzazioni concesse a livello di condivisione) </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Ambiente G Suite singolo (solo Google Drive)</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente, anche quelli di oltre 10 MB) </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per le cartelle a livello di utente* </li>
<li> Autorizzazioni cartella a livello di gruppo* </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
<li> Unità condivise (cartelle e file) </li>
<li> Contenuto condiviso appartenente all'account Google Drive in corso di migrazione </li>
</ul>
<br>
*Le autorizzazioni sono influenzate dal Microsoft 365 gruppo e/o Microsoft Teams canale. Se la destinazione è un Microsoft 365 gruppo o Microsoft Teams, il gruppo o il canale determina il profilo delle autorizzazioni finali per i file migrati. È consigliabile non eseguire la migrazione delle autorizzazioni per la migrazione dei file a un Microsoft 365 gruppo o Microsoft Teams canale. 
</td>
<td><ul>
<li> Cronologia di proprietà, versioni precedenti e commenti </li>
<li> Descrizioni di file e cartelle, colori delle cartelle </li>
<li> Autorizzazioni per file a livello di utente </li>
<li> Autorizzazioni per file a livello di gruppo </li>
<li> Metadati avanzati </li>
<li> Attributi di blocco di file </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Elementi eliminati </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Utenti bloccati o inattivi </li>
<li> Google Photos, Moduli, Maps e altre app connesse </li>
<li> Disegni Google </li>
<li> Contenuti condivisi esterni alla tua impresa </li>
<li> Contenuto che appartenente all'account Google Drive che è in corso di migrazione </li>
<li> Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni. Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione). </li>
<li> Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise. Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione). </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per le cartelle a livello di utente* </li>
<li> Autorizzazioni cartella a livello di gruppo* </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
<li> Contenuto condiviso appartenente all'account Box in corso di migrazione </li>
<li> Note casella (convertite in formato documento Word) </li>
</ul>
<br>
*Le autorizzazioni sono influenzate dal Microsoft 365 gruppo e/o Microsoft Teams canale. Se la destinazione è un Microsoft 365 gruppo o Microsoft Teams, il gruppo o il canale determina il profilo delle autorizzazioni finali per i file migrati. È consigliabile non eseguire la migrazione delle autorizzazioni per la migrazione dei file a un Microsoft 365 gruppo o Microsoft Teams canale. </td>
<td><ul>
<li> Cronologia di proprietà, versioni precedenti e commenti </li>
<li> Descrizioni di file e cartelle </li>
<li> Autorizzazioni per file a livello di utente </li>
<li> Autorizzazioni per file a livello di gruppo </li>
<li> Tag Box e metadati avanzati </li>
<li> Attributi di blocco di file </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Elementi eliminati </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Utenti bloccati o inattivi </li>
<li> App Box, Segnalibri, Preferiti e Flussi di lavoro </li>
<li> Contenuto non di proprietà dell'account Box migrato </li>
<li> Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni. Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione). </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox per Team (Standard e Advanced)</strong></td>
<td>Passaggio singolo o multiplo</td>
<td><ul>
<li> Documenti </li>
<li> Struttura di file e cartelle </li>
<li> Autorizzazioni per le cartelle a livello di utente* </li>
<li> Autorizzazioni cartella a livello di gruppo* </li>
<li> File inferiori a 15 GB </li>
<li> Metadati cartella e documenti di base:
<ul>
<li> Data creazione </li>
<li> Data modifica </li>
<li> Creato da </li>
<li> Autore ultima modifica </li>
</ul></li>
<li> Contenuto e cartelle del team condiviso </li>
<li> Contenuto condiviso appartenente all'account Dropbox in corso di migrazione </li>
</ul>
<br>
*Le autorizzazioni sono influenzate dal Microsoft 365 gruppo e/o Microsoft Teams canale. Se la destinazione è un Microsoft 365 gruppo o Microsoft Teams, il gruppo o il canale determina il profilo delle autorizzazioni finali per i file migrati. È consigliabile non eseguire la migrazione delle autorizzazioni per la migrazione dei file a un Microsoft 365 gruppo o Microsoft Teams canale.
</td>
<td><ul>
<li> Cronologia di proprietà, versioni precedenti e commenti </li>
<li> Descrizioni di file e cartelle </li>
<li> Autorizzazioni per file a livello di utente </li>
<li> Autorizzazioni per file a livello di gruppo </li>
<li> Metadati avanzati </li>
<li> Attributi di blocco di file </li>
<li> Conversione degli URL incorporati nel contenuto </li>
<li> Elementi eliminati </li>
<li> Documenti inaccessibili o corrotti </li>
<li> Cartelle Dropbox non montate </li>
<li> Utenti eliminati o scollegati </li>
<li> Dropbox Paper, Showcases, e Spaces </li>
<li> App e preferiti di Dropbox (Pins/stars) </li>
<li> Contenuto non di proprietà dell'account Dropbox migrato </li>
<li> Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni. Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione). </li>
<li> File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a>Responsabilità di FastTrack per le migrazioni Microsoft Teams e Microsoft 365 gruppi

Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione. Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.

### <a name="your-responsibilities"></a>Responsabilità dell'utente 

Tu esegui attività standard durante il progetto di migrazione. Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.
È inoltre possibile eseguire le attività seguenti, specifiche per le migrazioni Microsoft Teams e Microsoft 365 gruppi: 

- Esegui il provisioning di Microsoft Teams canali e Microsoft 365 gruppi come destinazione degli eventi di migrazione.

> [!NOTE]
>FastTrack non effettua il pre-provisioning Microsoft Teams canali o Microsoft 365 gruppi. FastTrack non aggiunge utenti finali o gruppi a Microsoft Teams o Microsoft 365 gruppi. È necessario aggiungere gli utenti finali o i gruppi a tutti i canali Microsoft Teams e i gruppi di Microsoft 365 prima di eseguire la migrazione dei dati in tali destinazioni in modo che tali utenti finali hanno accesso ai documenti appena migrati