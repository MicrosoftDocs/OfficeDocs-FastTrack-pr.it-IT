---
title: Migrazione dei dati
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack Specialists provide guidance on steps for data migration to Office 365. This is available for all eligible customers with Office 365 services for Exchange Online, OneDrive for Business, and SharePoint Online.
ms.openlocfilehash: 7780af3d5edcdbdf21acba1d421bf379967305fa
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011310"
---
# <a name="data-migration"></a>Migrazione dei dati

Potresti disporre di dati nell'ambiente di origine da migrare a Office 365.

**Per i tenant di Office 365 con 150-499 licenze:** Forniamo indicazioni usando una combinazione di strumenti e documentazioni, in modo che la migrazione sia senza problemi ed efficiente. 

**Per i tenant di Office 365 con 500 o più licenze\*:** i servizi di migrazione dati sono disponibili per Exchange Online, SharePoint Online e OneDrive for business. Il vantaggio di FastTrack include indicazioni con l'integrazione di origine e la migrazione dei dati.
  
\*If you purchased or renewed a commercial plan prior to 9/1/2017, 150 seats is the minimum seat requirement throughout your current subscription period in order to receive the migration benefit. For education plans, only paid faculty and staff licenses are eligible for migration services. 
  
> [!NOTE]
> Data migrated through the FastTrack services may be transferred to, stored, and processed anywhere that Microsoft maintains facilities (except as otherwise provided for your particular FastTrack engagement). The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements. 
  
> [!NOTE]
> Problemi imprevisti (ad esempio, elementi non leggibili o corrotti nell'ambiente di origine e molti altri ancora) potrebbero impedire la migrazione di determinati elementi. 
  
> [!NOTE]
> L'assistenza alla migrazione è disponibile in cinese tradizionale e cinese semplificato (le risorse parlano solo cinese mandarino), inglese, francese, tedesco, italiano, giapponese, portoghese (brasiliano) e spagnolo. 
  
> [!NOTE]
> Se l'integrazione è necessaria, l'ambiente di origine deve essere al livello minimo per tale applicazione. 
  
> [!NOTE]
> Novità di marzo 2020: Microsoft ha reso disponibili le licenze di valutazione della durata di sei mesi per [Office 365 E1](https://docs.microsoft.com/microsoftteams/e1-trial-license) e [Office 365 G1](https://docs.microsoft.com/microsoftteams/g1-trial-license) per aiutare i clienti con il lavoro in remoto e la formazione a distanza durante l'epidemia di COVID-19. Eccezionalmente, FastTrack sta rendendo disponibili i servizi di migrazione dei dati per i tenant con 500 o più licenze di queste versioni di valutazione e per [Office 365 A1](https://www.microsoft.com/microsoft-365/academic/compare-office-365-education-plans?activetab=tab:primaryr1) per gli studenti da marzo 2020 ad agosto 2020. Microsoft si riserva il diritto di annullare, modificare o sospendere questa offerta in qualsiasi momento senza preavviso.

Nella seguente tabella viene descritto quanto previsto per la migrazione nell'ambiente di origine esistente.
  

|**Attività**|**Previsione dell'ambiente di origine**|
|:-----|:-----|
|**Migrazione di Exchange Online**  <br/> | Microsoft migrates any combination of the source environments listed below, each one at a time. We can migrate the onboarded messaging system using the FastTrack Center or if it's passed the FastTrack Center checks. This includes:  <br/>  Una o più foreste di Active Directory con una o più organizzazioni di Exchange, se è implementato Exchange 2010 Hybrid e versioni successive in ogni organizzazione e i sistemi di posta elettronica di Exchange sono 2003 e versioni successive.  <br/>  Un ambiente di posta elettronica con funzionalità IMAP singola.  <br/>  Ambienti G Suite (soltanto Gmail, Contatti e Calendario). <br/> <br/> **Nota:** *l'onboarding di Exchange Online deve essere completato prima della migrazione.* <br/> <br/> **Nota:** *FastTrack migra solamente verso cassette postali di Office 365 attive.* <br/> <br/> **Nota:** *per le dipendenze di Exchange locali, vedere [Prerequisiti per la distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).* <br/><br/> **Nota:** *quando si effettua la migrazione di più ambienti di messaggistica di origine (come più organizzazioni di Exchange o più domini Domino), tali migrazioni si verificano in sequenza.*| 
|**Migrazione di SharePoint Online**  <br/> | Condivisioni di file (condivisioni di file di Server Message Block su dispositivi che supportano SMB 2.0 e versioni successive). <br/> Ambiente G Suite singolo (solo Google Drive)<br/>  Box (Starter, Business, Enterprise).  <br/> Dropbox per Team (Standard e Advanced).<br/> |
|**Migrazione di OneDrive for Business**  <br/> | Condivisioni di file (condivisioni di file SMB su dispositivi che supportano SMB 2.0 e versioni successive).  <br/>  Ambiente G Suite singolo (solo Google Drive)  <br/>  Box (Starter, Business, Enterprise). <br/> Dropbox per Team (Standard e Advanced).<br/><br/> **Nota:** *FastTrack migra solamente verso unità di Office 365 attive.*|
   
## <a name="migration-to-exchange-online"></a>Migrazione a Exchange Online
''
### <a name="enable-to-migrate"></a>Abilitare alla migrazione
  
Se si utilizza Microsoft per eseguire la migrazione della posta elettronica, sono disponibili istruzioni per abilitare Exchange Online e l'ambiente di origine per la migrazione. A seconda dell'ambiente di origine, è possibile che vengano eseguiti diversi passaggi di abilitazione. Viene fornita assistenza all'utente mediante una combinazione di strumenti e documentazione, nonché eseguendo le attività di configurazione se applicabili e possibili. In base ai parametri applicabili, è quindi possibile migrare le cassette postali, monitorare i processi e fornire report di stato.
" Potrebbe essere necessario fornire a Microsoft autorizzazione e accesso al proprio sistema di posta per eseguire le attività di migrazione.
  
### <a name="migration-policy-and-steps"></a>Procedura e criteri di migrazione
  
> [!NOTE]
> Il termine batch di migrazione viene usato in riferimento a una fascia oraria di migrazione.

#### <a name="commercial-and-uk-government"></a>Uso commerciale e governo del Regno Unito

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>Governo degli Stati Uniti/DoD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
 ### <a name="end-state"></a>Stato finale
  
Lo stato finale previsto in seguito a un batch di migrazione include quanto segue:
- I dati delle cassette postali pianificate e idonee presenti nell'ambiente di origine vengono migrati in Office 365. 
- Viene fornito da Microsoft un report di post-migrazione per il batch di migrazione.
    
Lo stato finale atteso al termine di tutte le migrazioni include quanto segue:
- I dati delle cassette postali di origine idonee vengono migrati su Office 365 come illustrato nella tabella seguente.
- Il tipo di dati da migrare dipende dall'ambiente di origine, come indicato nella tabella seguente.
    
> [!NOTE]
> All source environments need to be on the latest service packs (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment at the end of the Enable phase. Data migration services are subject to external factors beyond Microsoft's control, like changes to third-party application programming interfaces (APIs), which could result in changes to, delays in, or suspension of these services. For the duration of the FastTrack services, data you make available to Microsoft is accessible from and stored anywhere that Microsoft and its suppliers maintain facilities. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Ambiente di origine**|**Tipo di migrazione**|**Elementi sottoposti a migrazione**|**Elementi esclusi dalla migrazione**|
|**Exchange 2003 e versioni successive**|Completa| Messaggi di posta elettronica <br/> Regole della cassetta postale <br/> Delegati <br/> Contatti della cassetta postale <br/> Calendario <br/> Attività <br/> Messaggi di posta elettronica con contenuto protetto da Microsoft Rights Management <br/> Messaggi di posta elettronica crittografati| Cartelle pubbliche <br/> Contatti personali <br/> Utenti abilitati all'utilizzo della posta <br/> Utenti bloccati o inattivi <br/> Firme <br/> Cassetta postale dumpster <br/>  Tutte le e-mail che superano il limite per la dimensione del messaggio <br/> Archiviazione dati <br/> Elementi danneggiati <br/>  Cassette postali inattive |
|**Exchange 2003 ed Exchange 2007**|A fasi| Messaggi di posta elettronica <br/> Regole della cassetta postale <br/> Delegati <br/> Contatti della cassetta postale <br/> Calendario <br/> Attività <br/> Messaggi di posta elettronica con contenuto protetto da Microsoft Rights Management <br/> Messaggi di posta elettronica crittografati| Cartelle pubbliche <br/> Contatti personali <br/> Utenti abilitati all'utilizzo della posta <br/> Utenti bloccati o inattivi <br/> Firme <br/> Cassetta postale dumpster <br/> Tutte le e-mail che superano il limite per la dimensione del messaggio <br/> Archiviazione dati <br/> Elementi danneggiati <br/> Cassette postali inattive |
|**Exchange 2010, Exchange 2013, Exchange 2016 ed Exchange 2019** <br/><br/> **Nota:** *per le dipendenze di Exchange locali, vedere [Prerequisiti per la distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).*           |Migrazione con distribuzione ibrida| Messaggi di posta elettronica <br/> Regole della cassetta postale <br/> Delegati <br/> Contatti della cassetta postale <br/> Calendario <br/> Tasks <br/> Firme <br/> Archivio personale migrato con la cassetta postale dell'utente <br/> Elementi ripristinabili <br/> Messaggi di posta elettronica con contenuto protetto da Microsoft Rights Management <br/> Messaggi di posta elettronica crittografati| Cartelle pubbliche <br/> Tutti i messaggi di posta elettronica che superano il limite relativo alla dimensione <br/> Archivio di inserimento nel journal oppure tutte le altre soluzioni di archiviazione di terze parti <br/> Utenti bloccati o inattivi <br/> Archiviazione dati da file PST (Personal Storage Table) <br/> Elementi danneggiati <br/> Cassette postali inattive |
|**Ambiente G Suite (solo Gmail, Contatti e Calendario)** <br/> <br/> **Nota** *L’ambiente di G Suite deve avere le API di Google e SDK di amministrazione di Google abilitati per l'estensione della funzionalità.* <br/>          |Completa o a fasi| Messaggi di posta elettronica <br/> Contatti della cassetta postale\*  <br/> Calendario <br/> Etichette <br/> \*Viene eseguita la migrazione di un massimo di tre indirizzi di posta elettronica per ogni contatto| Regole <br/> Delegati <br/> Firme <br/> Attività <br/> Tutti i messaggi di posta elettronica o allegati che superano il limite relativo alla dimensione <br/> Utenti bloccati o inattivi <br/> Archiviazione dati da file PST o da una soluzione di archiviazione di terze parti (ad esempio, Google Vault) <br/> Messaggi di posta elettronica crittografati o con contenuto protetto <br/> Elementi danneggiati <br/> Hangouts di Google\*\* <br/> Gruppi di Google <br/> Cassette postali per la risorsa <br/> Cassette postali inattive <br/> Impostazioni delle ferie e impostazioni di risposta automatica <br/> Calendari condivisi, allegati cloud, collegamenti di Google Hangout e colori per gli eventi <br/>\*\*È stata eseguita la migrazioni di conversazioni di Hangout salvate come etichetta |
|**Origine IMAP4 (come Domino, GroupWise e Zimbra)** |Migrazione tramite strumenti nativi di IMAP4| Messaggi di posta elettronica | Regole <br/> Delegati <br/> Liste di distribuzione <br/> Contatti esterni <br/> Utenti abilitati all'utilizzo della posta <br/> Utenti bloccati o inattivi <br/> Contatti della cassetta postale <br/> Calendario <br/> Firme <br/> Attività <br/> Tutte le e-mail che superano il limite per la dimensione del messaggio <br/> Archiviazione dati <br/> Messaggi di posta elettronica crittografati <br/> Elementi danneggiati <br/> Cassette postali inattive |
   
> [!NOTE]
> If distribution lists (MailEnabledGroup objects) and external contacts (MailEnabledContact objects) are in the on-premises Active Directory, they can be synchronized using Azure AD Connect. However, they aren't a part of mailbox data migration. For more information, see the **Identity integration** example in [Core](O365-onboarding-and-migration.md#core). 
  
Gli esperti di FastTrack eseguono le seguenti operazioni durante le migrazioni:
- Fornisce il modello standard per pianificare le migrazioni della cassetta postale.
- Fornisce informazioni sulle autorizzazioni necessarie per specialisti FastTrack. 
- Raccoglie informazioni relative alla pianificazione della migrazione predeterminata della cassetta postale in un formato prestabilito.
- Tenta di eseguire fino a due migrazioni di una singola cassetta postale in un batch di migrazione, prima di segnalare la migrazione come non riuscita.
- Nel caso di ambienti di origine basati su Exchange e IMAP4, migrare i contenuti della cassetta postale dell'utente fino all'85% del limite di archiviazione (ad esempio, se il limite di archiviazione della cassetta postale è di 50 GB, Microsoft eseguirà la migrazione fino all'85% di tale limite). 
- Abilitare la coesistenza del routing di posta SMTP tra l'ambiente della messaggistica di origine e Office 365 Exchange Online, a meno che non si utilizzi la migrazione completa.
- Fornire i rapporti post-migrazione.
- Provide post-migration assistance for critical issues. The following issues are considered critical:
  - Perdita di dati durante la migrazione.
  - L'ambiente di origine non è più disponibile durante la migrazione.
  - Le attività di migrazione causano errori nell'ambiente di origine.
    
Eseguire le seguenti operazioni durante le migrazioni:
- Completare l'onboarding a Exchange Online o superare i controlli necessari tramite FastTrack Center.
- Gestire tutte le comunicazioni con gli utenti finali.  
- Installare il livello appropriato di software client in base alle linee guida di Office 365. Per ulteriori informazioni, vedere [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg). 
- Convalidare la coesistenza del routing di posta SMTP tra l'ambiente di messaggistica di origine e Office 365 Exchange Online, se applicabile.
- Fornire una pianificazione in un metodo definito e un elenco delle cassette postali specifiche da migrare in ogni fase.
- Eliminare le cassette postali dalla pianificazione fino a 24 ore prima del batch di migrazione. 
- Pianificare un numero medio di cassette postali di destinazione all'interno di un periodo di 24 ore, come descritto nella tabella seguente.
    
|||
|:-----|:-----|
|**Numero di cassette postali idonee per la migrazione** <br/> |**Media minima relativa alle cassette postali in un periodo di 24 ore** <br/> |
|150-1.000  <br/> |25% del totale  <br/> |
|1.001-5.000  <br/> |20% del totale  <br/> |
|5.001-10.000  <br/> |15% del totale  <br/> |
|\>10.000  <br/> |1.500  <br/> |
   
   > [!NOTE]
   > These numbers are based on best practice. However, the number of mailboxes that migrate per day will vary based on environment, readiness, and business constraints. Microsoft can't guarantee the speed of mailbox migration. 
  
- Pianificare almeno 35 cassette postali in un batch di migrazione. 
- Correggere gli errori della pre-migrazione (se applicabile).  
- Fornire accesso e autorizzazione all'ambiente di origine, come stabilito dagli specialisti FastTrack al fine di eseguire attività di migrazione. 
- Procurarsi e/o fornire account amministrativi con licenza in Office 365 per eseguire attività di migrazione (in base alle esigenze). 
- Supportare i problemi di migrazione dal lato client ed eseguire operazioni successive alla migrazione, se necessario. 
- Migrate client-side data if desired. This includes, but is not limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.   
- Ridurre la dimensione della cassetta postale a una percentuale inferiore rispetto all'85% del limite relativo alla cassetta postale di Office 365 (se applicabile).   
- Gestire le azioni del rapporto di post-migrazione, comprese le cassette postali che non sono state spostate.  
- Correggere gli errori di post-migrazione e pianificare di nuovo le cassette postali (se applicabile).   
- Engage in post-migration assistance for critical issues. The following issues are considered critical:
  - Perdita di dati durante la migrazione.
  - L'ambiente di origine non è più disponibile durante la migrazione.
  - Le attività di migrazione causano errori nell'ambiente di origine.
    
You need to follow the standard migration process and engage with Microsoft appropriately. This includes providing access and permissions to source and Office 365 environments, providing migration schedules, correcting any causes for migration errors, and so on. You also need to engage with end users for communications, mailbox migration schedule, and handling end user migration-related issues.
  
> [!NOTE]
> Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
  
## <a name="migration-to-sharepoint-online"></a>Migrazione a SharePoint Online

### <a name="enable-to-migrate"></a>Abilitare alla migrazione
  
If you use Microsoft to migrate your data, we provide guidance to enable both SharePoint Online and the source environment for migration. Depending on the source, we may perform various Enable steps. We provide guidance for you by using a combination of tools and documentation and by performing configuration tasks where applicable and feasible.
  
È necessario fornire a Microsoft l'accesso e le autorizzazioni per eseguire alcune attività.
  
### <a name="migration-policy-and-steps"></a>Procedura e criteri di migrazione
  
> [!NOTE]
> Il termine batch di migrazione viene usato in riferimento a una fascia oraria di migrazione.

#### <a name="commercial-and-uk-government"></a>Uso commerciale e governo del Regno Unito

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>Governo degli Stati Uniti/DoD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.

- Tutte le migrazioni sono soggette alle quote di SharePoint Online descritte in [SharePoint Online e OneDrive for Business: limiti del software](https://go.microsoft.com/fwlink/?LinkID=616612).   
- La quantità complessiva dei dati migrati sarà legata al 75% della quota di archiviazione di SharePoint Online complessiva per la quale è abilitato l'utente (compresa l'archiviazione aggiuntiva che potrebbe essere stata acquistata separatamente).
    
 ### <a name="end-state"></a>Stato finale
  
Lo stato finale previsto in seguito a un batch di migrazione include quanto segue: 
- I dati delle origini pianificate e idonee presenti nell'ambiente di origine vengono migrati in SharePoint Online.   
- Viene fornito da Microsoft un report di post-migrazione per il batch di migrazione.
    
Lo stato finale atteso al termine di tutte le migrazioni include quanto segue: 
- I dati dell'origine idonea vengono migrati su Office 365 come illustrato nella tabella seguente.  
- Il tipo di dati da migrare dipende dall'ambiente di origine, come indicato nella tabella seguente:
    
|||||
|:-----|:-----|:-----|:-----|
|**Ambiente di origine** <br/> |**Tipo di migrazione** <br/> |**Elementi sottoposti alla migrazione** <br/> |**Elementi esclusi dalla migrazione** <br/> |
|**Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive**  <br/> |Passaggio singolo o multiplo  <br/> | Documenti  <br/>  Struttura di file e cartelle  <br/>  Autorizzazioni per file e cartelle a livello di utente\*  <br/>  Autorizzazioni per file e cartelle a livello di gruppo\*  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/><br/> \**Configurazione della sincronizzazione della directory necessaria. Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows. Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate. Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.* <br/> | Cronologia di proprietà e versioni precedenti  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Versioni precedenti  <br/>  File di Windows e attributi di cartella (come Di sola lettura e Nascosto)  <br/>  Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):  <br/>  Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)  <br/>  Configurazione di controllo NTFS  <br/>  Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)  <br/>  Documenti inaccessibili o corrotti  <br/>  Condivisioni nascoste  <br/>  Condivisione (come autorizzazioni concesse a livello di condivisione)  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Ambiente G Suite singolo (solo Google Drive)**  <br/> |Passaggio singolo o multiplo  <br/> | <br/>  Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente), anche quelli di oltre 10 MB <br/>  Struttura di file e cartelle  <br/>  Autorizzazioni per cartelle a livello di utente  <br/>  Autorizzazioni per cartelle a livello di gruppo <br/>  File inferiori a 15 GB  <br/> Metadati cartella e documenti di base: <br/> Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/> Unità condivise (cartelle e file) <br/>  Contenuto condiviso di proprietà dell'account Google Drive migrato (se condiviso esplicitamente con utenti o gruppi)\*  <br/><br/> \**Utilizzare l'amministratore di Google Drive per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> | Cronologia di proprietà, versioni precedenti e commenti <br/>  Descrizioni di file e cartelle, colori delle cartelle  <br/>  Autorizzazioni per file a livello di utente  <br/>  Autorizzazioni per file a livello di gruppo  <br/>  Metadati avanzati  <br/>  Attributi di blocco di file  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Elementi eliminati  <br/>  Documenti inaccessibili o corrotti  <br/>  Utenti bloccati o inattivi  <br/>  Google Photos, Moduli, Maps e altre app connesse  <br/>  Disegni Google  <br/>  Contenuti condivisi esterni alla tua impresa  <br/> Contenuto che appartenente all'account Google Drive che è in corso di migrazione <br/>Autorizzazioni e metadati di base di utenti esterni  <br/> Autorizzazioni membri unità condivise\* <br/> File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Utilizzare l'amministratore di Google Drive per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/>|
|**Box (Starter, Business, Enterprise)**  <br/> |Passaggio singolo o multiplo  <br/> | Documenti  <br/>  Struttura di file e cartelle  <br/>  Autorizzazioni per cartelle a livello di utente  <br/>  Autorizzazioni per cartelle a livello di gruppo  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/>  Contenuto condiviso di proprietà dell'account Box migrato (se condiviso esplicitamente con utenti o gruppi)\*  <br/><br/> \**Utilizzare i report Box per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> | Cronologia di proprietà, versioni precedenti e commenti <br/>  Autorizzazioni per file a livello di utente  <br/>  Autorizzazioni per file a livello di gruppo  <br/>  Descrizioni di file e cartelle  <br/>  Tag Box e metadati avanzati  <br/>  Attributi di blocco di file  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Elementi eliminati  <br/>  Documenti inaccessibili o corrotti  <br/>  Utenti bloccati o inattivi  <br/>  Note Box (non funzionali perché migrate senza conversione)  <br/>  App Box, Segnalibri, Preferiti e Flussi di lavoro  <br/>  Contenuto non di proprietà dell'account Box migrato (cartelle condivise)  <br/>  Autorizzazioni e metadati di base di utenti esterni\*  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/>\**Utilizzare l'amministratore di Google Drive per identificare l'appartenenza a unità condivise. Indicare agli utenti finali di configurare le impostazioni di appartenenza nella destinazione prima della migrazione.* |
|**Dropbox per Team (Standard e Advanced)**  <br/> |Passaggio singolo o multiplo  <br/> | Documenti  <br/>  Struttura di file e cartelle  <br/>  Autorizzazioni per cartelle a livello di utente  <br/>  Autorizzazioni per cartelle a livello di gruppo  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/> Contenuto e cartelle del team condiviso <br/>  Contenuto condiviso di proprietà dell'account Box migrato (se condiviso esplicitamente con utenti o gruppi)\*  <br/> <br/> \**Utilizzare i report Dropbox per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> | Cronologia di proprietà, versioni precedenti e commenti <br/>  Descrizioni di file e cartelle <br/>  Autorizzazioni per file a livello di utente  <br/>  Autorizzazioni per file a livello di gruppo    <br/> Metadati avanzati  <br/>  Attributi di blocco di file  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Elementi eliminati  <br/>  Documenti inaccessibili o corrotti  <br/>  Cartelle Dropbox non montate <br/>  Utenti eliminati o scollegati <br/>  Dropbox Paper, Showcases, e Spaces  <br/> App e preferiti di Dropbox (Pins/stars) <br/> Contenuto non di proprietà dell'account Dropbox migrato  <br/>  Autorizzazioni e metadati di base di utenti esterni\*  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Utilizzare i report Dropbox per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> |
   
Gli esperti di FastTrack eseguono le seguenti operazioni durante le migrazioni: 
- Conducono un workshop dettagliato sulla migrazione illustrando la procedura e il metodo per lo scenario di migrazione selezionato.
- Forniscono i prerequisiti per gli strumenti di valutazione e migrazione applicabili per lo scenario.   
- Forniscono i prerequisiti per l'accesso del team di migrazione all'ambiente di origine e di destinazione ai fini della valutazione e della migrazione. 
- Fornisce appositi strumenti per effettuare valutazioni dell'ambiente di origine/destinazione o istruzioni su come utilizzare le funzioni delle piattaforme di origine native per creare report di valutazione.   
- Assiste alla distribuzione e all'esecuzione di strumenti di valutazione e migrazione (se applicabile).   
- Configura l'infrastruttura di migrazione nella preparazione della migrazione dei contenuti (laddove applicabile).    
- Conduce una migrazione di prova limitata per convalidare l'infrastruttura di migrazione e i prerequisiti necessari.   
- Effettua il provisioning dei siti di SharePoint Online di destinazione predefiniti come parte della migrazione.    
- Conduce una migrazione pilota prima della migrazione su vasta scala.   
- Fornisce indicazioni sulla pianificazione della migrazione per lo scenario selezionato. 
- Conduce migrazioni su vasta scala di contenuti in base alla pianificazione della migrazione fornita dal cliente e convalidata dalle risorse FastTrack.   
- Fornisce i risultati della migrazione dopo ogni finestra di migrazione.   
- Partecipa alla valutazione dei problemi relativi alla migrazione su vasta scala e fornisce indicazioni sulle potenziali opzioni di risoluzione.   
- Fornisce un report di migrazione finale per ogni finestra di migrazione su vasta scala.   
- Fornisce supporto post-migrazione durante il test di accettazione per gli utenti fino a cinque giorni dopo il completamento della migrazione.
    
Eseguire le seguenti operazioni durante le migrazioni: 
- Provide project resources recommended for assessment and migration activities. These include: 
  - Gestione dei progetti. 
  - Test di accettazione utenti (UAT).  
  - Amministratori responsabili delle piattaforme dei contenuti di origine e di destinazione.  
- Fornisce i prerequisiti dell'infrastruttura per le attività di valutazione e migrazione (se richiesto).  
- Fornisce accesso e autorizzazione all'ambiente di origine e di destinazione, come stabilito dagli specialisti FastTrack al fine di eseguire attività di migrazione (se richiesto).
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- Fornire i prerequisiti ed eseguire attività necessarie per supportare valutazione e migrazione.   
- Installa gli strumenti di valutazione forniti da FastTrack e completa le attività di raccolta dei dati di valutazione (se applicabile).   
- Installa il software di migrazione fornito da FastTrack in locale (se applicabile).   
- Completa le attività di correzione descritte nell'apposito report fornito da FastTrack (se applicabile).  
- Fornisce una pianificazione di migrazione mediante le linee guida e i modelli di FastTrack.   
- Conduce una verifica di controllo qualità della migrazione e il test di accettazione per gli utenti.   
- Conduce la correzione della migrazione post-migrazione (se applicabile).
- Pianifica e implementa la gestione delle modifiche e le comunicazioni con gli utenti finali (se applicabile).   
- Amministrare e configurare le eventuali modifiche apportate al sistema di origine e ai dispositivi necessari per il completamento delle attività di migrazione e valutazione.
- Forniscono una pianificazione in un metodo definito e un elenco dei dati utente specifici di cui eseguire la migrazione in ogni fase, con almeno tre (3) giorni di anticipo.
- Eliminare i dati utente dalla pianificazione fino a 24 ore prima del batch di migrazione. A quel punto, si è giunti al batch di migrazione finale.
> [!NOTE]
> Microsoft non garantisce la velocità di migrazione dei file.
    
## <a name="migration-to-onedrive-for-business"></a>Migrazione a OneDrive for Business

 ### <a name="enable-to-migrate"></a>Abilitare alla migrazione
  
If you use Microsoft to migrate your data, we provide guidance to enable both OneDrive for Business and the source environment for migration. Depending on the source, we may perform various Enable steps. We help you with some activities by using a combination of tools, documentation, and guidance, and by performing configuration tasks where applicable and feasible.
  
You may need to provide appropriate access and permissions to Microsoft to perform some activities. If you don't provide access and/or permissions, you need to perform certain defined tasks yourself with guidance from Microsoft. 
  
### <a name="migration-policy-and-steps"></a>Procedura e criteri di migrazione
  
> [!NOTE]
> Il termine batch di migrazione viene usato in riferimento a una fascia oraria di migrazione.

#### <a name="commercial-and-uk-government"></a>Uso commerciale e governo del Regno Unito

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>Governo degli Stati Uniti/DoD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
- Tutte le migrazioni richiedono accesso e autorizzazioni appropriate per l'ambiente di origine.   
- Tutte le migrazioni sono soggette alle quote di OneDrive for Business descritte in [SharePoint Online e OneDrive for Business: limiti del software](https://go.microsoft.com/fwlink/?LinkId=698855).
    
 ### <a name="end-state"></a>Stato finale
  
Lo stato finale previsto in seguito a un batch di migrazione include quanto segue:  
- I dati delle origini pianificate e idonee presenti nell'ambiente di origine vengono migrati in OneDrive for Business.  
- Viene fornito da Microsoft un report di post-migrazione per il batch di migrazione.
    
Lo stato finale atteso al termine di tutte le migrazioni include quanto segue:
- I dati delle origini idonee vengono migrati su Office 365, come illustrato nella tabella seguente.  
- Il tipo di dati da migrare dipende dall'ambiente di origine, come indicato nella tabella seguente.
    
|||||
|:-----|:-----|:-----|:-----|
|**Ambiente di origine**|**Tipo di migrazione**|**Elementi sottoposti alla migrazione**|**Elementi esclusi dalla migrazione**|
|**Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive**  <br/> |Passaggio singolo o multiplo  <br/> | Documenti  <br/>  Struttura di file e cartelle  <br/>  Autorizzazioni per file e cartelle a livello di utente\*  <br/>  Autorizzazioni per file e cartelle a livello di gruppo\*  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/> <br/>\**Configurazione della sincronizzazione della directory necessaria. Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows. Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate. Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.* <br/> | Cronologia di proprietà e versioni precedenti  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Versioni precedenti  <br/>  File di Windows e attributi di cartella (come Di sola lettura e Nascosto)  <br/>  Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):  <br/>  Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)  <br/>  Configurazione di controllo NTFS  <br/>  Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)  <br/>  Documenti inaccessibili o corrotti  <br/>  Condivisioni nascoste  <br/>  Condivisione (come autorizzazioni concesse a livello di condivisione)  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Ambiente G Suite singolo (solo Google Drive)**  <br/> |Passaggio singolo o multiplo  <br/> | Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente, anche quelli di oltre 10 MB)  <br/>  Struttura di file e cartelle  <br/>  Autorizzazioni per cartelle a livello di utente  <br/>  Autorizzazioni per cartelle a livello di gruppo  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/> Unità condivise (cartelle e file) <br/> Contenuto condiviso di proprietà dell'account Google Drive migrato (se condiviso esplicitamente con utenti o gruppi)\* <br/> <br/>\**Utilizzare l'amministratore di Google Drive per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> | Cronologia di proprietà, versioni precedenti e commenti  <br/>  Descrizioni di file e cartelle, colori delle cartelle  <br/>   Autorizzazioni per file a livello di utente  <br/>  Autorizzazioni per file a livello di gruppo  <br/> Metadati avanzati <br/>  Attributi di blocco di file <br/> Conversione degli URL incorporati nel contenuto  <br/> Elementi eliminati <br/> Documenti inaccessibili o corrotti <br/> Utenti bloccati o inattivi <br/> Google Foto <br/> Forms, Maps, e altre app connesse <br/> Disegni Google <br/> Contenuti condivisi esterni alla tua impresa <br/> Contenuto che appartenente all'account Google Drive che è in corso di migrazione <br/> Autorizzazioni e metadati di base di utenti esterni<br/> Autorizzazioni membri unità condivise\*<br/> File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/><br/> \**Utilizzare l'amministratore di Google Drive per identificare l'appartenenza a unità condivise. Indicare agli utenti finali di configurare le impostazioni di appartenenza nella destinazione prima della migrazione.* <br/> |
|**Box (Starter, Business, Enterprise)**  <br/> |Passaggio singolo o multiplo  <br/> | Documenti  <br/>  Struttura di file e cartelle  <br/>  Autorizzazioni per cartelle a livello di utente  <br/>  Autorizzazioni per cartelle a livello di gruppo  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/>  Contenuto condiviso di proprietà dell'account Box migrato (se condiviso esplicitamente con utenti o gruppi)\*  <br/><br/> \**Utilizzare i report Box per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> | Cronologia di proprietà, versioni precedenti e commenti  <br/>  Descrizioni di file e cartelle  <br/>  Autorizzazioni per file a livello di utente  <br/>  Autorizzazioni per file a livello di gruppo  <br/>  Tag Box e metadati avanzati  <br/>  Attributi di blocco di file  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Elementi eliminati  <br/>  Documenti inaccessibili o corrotti  <br/>  Utenti bloccati o inattivi  <br/>  Note Box (non funzionali perché migrate senza conversione)  <br/>  App Box, Segnalibri, Preferiti e Flussi di lavoro  <br/>  Contenuto non di proprietà dell'account Box migrato (cartelle condivise)  <br/>  Autorizzazioni e metadati di base di utenti esterni\*  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Dropbox per Team (Standard e Advanced)**  <br/> |Passaggio singolo o multiplo  <br/> | Documenti  <br/>  Struttura di file e cartelle  <br/>  Autorizzazioni per cartelle a livello di utente  <br/>  Autorizzazioni per cartelle a livello di gruppo  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/> Contenuto e cartelle del team condiviso <br/> Contenuto condiviso di proprietà dell'account Box migrato (se condiviso esplicitamente con utenti o gruppi)\*  <br/> <br/> \**Utilizzare i report Dropbox per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> | Cronologia di proprietà, versioni precedenti e commenti <br/>  Descrizioni di file e cartelle <br/>  Autorizzazioni per file a livello di utente  <br/>  Autorizzazioni per file a livello di gruppo    <br/> Metadati avanzati  <br/>  Attributi di blocco di file  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Elementi eliminati  <br/>  Documenti inaccessibili o corrotti  <br/>  Cartelle Dropbox non montate <br/>  Utenti eliminati o scollegati <br/>  Dropbox Paper, Showcases, e Spaces  <br/> App e preferiti di Dropbox (Pins/stars) <br/> Contenuto non di proprietà dell'account Dropbox migrato  <br/>  Autorizzazioni e metadati di base di utenti esterni\*  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Utilizzare i report Dropbox per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> |
   
Gli esperti di FastTrack eseguono le seguenti operazioni durante le migrazioni:  
- Conducono un workshop dettagliato sulla migrazione illustrando la procedura e il metodo per lo scenario di migrazione selezionato.   
- Forniscono i prerequisiti per gli strumenti di valutazione e migrazione applicabili per lo scenario.  
- Forniscono i prerequisiti per l'accesso del team di migrazione all'ambiente di origine e di destinazione ai fini della valutazione e della migrazione.   
- Fornisce appositi strumenti per effettuare valutazioni dell'ambiente di origine/destinazione o istruzioni su come utilizzare le funzioni delle piattaforme di origine native per creare report di valutazione.    
- Assiste alla distribuzione e all'esecuzione di strumenti di valutazione e migrazione (se applicabile).   
- Configura l'infrastruttura di migrazione nella preparazione della migrazione dei contenuti (laddove applicabile).    
- Conduce una migrazione di prova limitata per convalidare l'infrastruttura di migrazione e i prerequisiti necessari.    
- Effettua il provisioning dei siti di OneDrive for Business di destinazione predefiniti come parte della migrazione.    
- Conduce una migrazione pilota prima della migrazione su vasta scala.
- Fornisce indicazioni sulla pianificazione della migrazione per lo scenario selezionato.   
- Conduce migrazioni su vasta scala di contenuti in base alla pianificazione della migrazione fornita dal cliente e convalidata dalle risorse FastTrack.   
- Fornisce i risultati della migrazione dopo ogni finestra di migrazione.   
- Partecipa alla valutazione dei problemi relativi alla migrazione su vasta scala e fornisce indicazioni sulle potenziali opzioni di risoluzione. 
- Fornisce un report di migrazione finale per ogni finestra di migrazione su vasta scala.   
- Fornisce supporto post-migrazione durante il test di accettazione per gli utenti fino a cinque giorni dopo il completamento della migrazione.
   
Eseguire le seguenti operazioni durante le migrazioni:
- Provide project resources recommended for assessment and migration activities. These include:
  - Gestione dei progetti.
  - UAT.
  - Amministratori responsabili delle piattaforme dei contenuti di origine e di destinazione.
- Fornisce i prerequisiti dell'infrastruttura per le attività di valutazione e migrazione (se richiesto).   
- Fornisce accesso e autorizzazione all'ambiente di origine e di destinazione, come stabilito dagli specialisti FastTrack al fine di eseguire attività di migrazione (se richiesto).  
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- Installare gli strumenti di valutazione forniti da FastTrack e completare le attività di raccolta dei dati di valutazione (se applicabile).
- Installa il software di migrazione fornito da FastTrack in locale (se applicabile).  
- Completa le attività di correzione descritte nell'apposito report fornito da FastTrack (se applicabile).   
- Fornisce una pianificazione di migrazione mediante le linee guida e i modelli di FastTrack. 
- Fornire una pianificazione in un metodo definito e un elenco dei dati utente specifici da migrare in ogni fase.
- Drop user data from the schedule until 24 hours in advance of the migration batch. This should correspond to the final migration batch.
- Conduce una verifica di controllo qualità della migrazione e il test di accettazione per gli utenti.   
- Conduce la correzione della migrazione post-migrazione (se applicabile).  
- Pianifica e implementa la gestione delle modifiche e le comunicazioni con gli utenti finali (se applicabile).  
- Amministrare e configurare le eventuali modifiche apportate al sistema di origine e ai dispositivi necessari per il completamento delle attività di migrazione e valutazione.
    
> [!NOTE]
> Microsoft non garantisce la velocità di migrazione dei file. 


