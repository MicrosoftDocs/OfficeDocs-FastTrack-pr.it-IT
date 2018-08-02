---
title: Migrazione dei dati
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/27/18
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: e0c40008-4373-48d3-96bb-08f0afd08248
description: Gli esperti di FastTrack forniscono linee guida sulla procedura di migrazione di dati a Office 365. Viene fornita assistenza all'utente mediante una combinazione di strumenti, documentazione, nonché eseguendo le attività di configurazione se applicabili e possibili. Si tratta di un'opportunità offerta a tutti i clienti idonei con servizi Office 365 per Exchange Online, OneDrive for Business e SharePoint Online.
ms.openlocfilehash: 8a3157281947fbc9996a104014a29bb564fe7e13
ms.sourcegitcommit: ce2f0b156075cb8f07efa96c02115baf20779b6d
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 07/30/2018
ms.locfileid: "21498883"
---
# <a name="data-migration"></a>Migrazione dei dati

Gli esperti di FastTrack forniscono linee guida sulla procedura di migrazione di dati a Office 365. Viene fornita assistenza all'utente mediante una combinazione di strumenti, documentazione, nonché eseguendo le attività di configurazione se applicabili e possibili. Si tratta di un'opportunità offerta a tutti i clienti idonei con servizi Office 365 per Exchange Online, OneDrive for Business e SharePoint Online.
  
I servizi di migrazione dei dati descritti nella tabella seguente sono disponibili per i tenant di Office 365 con almeno 500 licenze.\*Ad esempio, si potrebbe disporre di dati nell'ambiente di origine da migrare a Office 365. Il vantaggio FastTrack Center include l'assistenza con l'integrazione dell'ambiente di origine per agevolare la migrazione dei contenuti.
  
\*Se è stato acquistato o rinnovato un piano commerciale prima del 1/9/2017, 150 postazioni è il requisito minimo di postazioni durante il periodo di abbonamento corrente per ricevere il vantaggio della migrazione. Per i piani formativi, solo l'istituto di istruzione e il personale sono idonei per i servizi di migrazione. 
  
> [!NOTE]
> I dati migrati tramite FastTrack possono essere trasferiti, archiviati ed elaborati in tutti i paesi in cui sono presenti sedi Microsoft (se non diversamente indicato nel proprio accordo FastTrack). I servizi FastTrack non sono progettati per i dati soggetti a particolari requisiti normativi o legali. 
  
> [!NOTE]
> Problemi imprevisti (ad esempio, elementi non leggibili o corrotti nell'ambiente di origine e molti altri ancora) potrebbero impedire la migrazione di determinati elementi. 
  
> [!NOTE]
> L'assistenza alla migrazione è disponibile in cinese tradizionale e cinese semplificato (le risorse parlano solo cinese mandarino), inglese, francese, tedesco, italiano, giapponese, portoghese (brasiliano) e spagnolo. 
  
> [!NOTE]
> Se l'integrazione è necessaria, l'ambiente di origine deve essere al livello minimo per tale applicazione. 
  
Nella seguente tabella viene descritto quanto previsto per la migrazione nell'ambiente di origine esistente.
  

|**Attività**|**Previsione dell'ambiente di origine**|
|:-----|:-----|
|Migrazione di Exchange Online  <br/> | Microsoft consente di migrare una combinazione di due degli ambienti di origine elencati di seguito, una per volta. È possibile migrare il sistema di messaggistica di cui è stato eseguito l'onboarding, tramite FastTrack Center o se ha superato i controlli di FastTrack Center. Ciò include:  <br/>  Una o più foreste di Active Directory con una o più organizzazioni di Exchange, se è implementato Exchange 2010 Hybrid e versioni successive in ogni organizzazione e i sistemi di posta elettronica di Exchange sono 2003 e versioni successive.  <br/> Un ambiente IBM Domino 7.0.3 e versioni successive singolo ([Appendice A: Migrazione da IBM Domino a Exchange Online](from-ibm-domino-to-exchange-online.md)).  <br/>  Un ambiente di posta elettronica con funzionalità IMAP singola.  <br/>  Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).  <br/>  Un ambiente Novell GroupWise 7.0.4 e versioni successive singolo.  <br/> <br/> **Nota:** *l'onboarding di Exchange Online deve essere completato prima della migrazione.* <br/> <br/> **Nota:** *FastTrack migra solamente verso cassette postali di Office 365 attive.* <br/> <br/> **Nota:** *per le dipendenze di Exchange locali, vedere [Prerequisiti per la distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).* <br/><br/> **Nota:** *quando si effettua la migrazione di più ambienti di messaggistica di origine (come più organizzazioni di Exchange o più domini Domino), tali migrazioni si verificano in sequenza.*| 
|Migrazione di SharePoint Online  <br/> | Condivisioni di file (condivisioni di file di Server Message Block su dispositivi che supportano SMB 2.0 e versioni successive).  <br/>  Box (Starter, Business, Enterprise).  <br/> |
|Migrazione di OneDrive for Business  <br/> | Condivisioni di file (condivisioni di file SMB su dispositivi che supportano SMB 2.0 e versioni successive).  <br/>  Un singolo ambiente di G Suite (soltanto Google Drive).  <br/>  Box (Starter, Business, Enterprise). <br/> <br/> **Nota:** *FastTrack migra solamente verso unità di Office 365 attive.*|
   
## <a name="migration-to-exchange-online"></a>Migrazione a Exchange Online

 **Abilitare alla migrazione**
  
Se si utilizza Microsoft per eseguire la migrazione della posta elettronica, sono disponibili istruzioni per abilitare Exchange Online e l'ambiente di origine per la migrazione. A seconda dell'ambiente di origine, è possibile che vengano eseguiti diversi passaggi di abilitazione. Viene fornita assistenza all'utente mediante una combinazione di strumenti e documentazione, nonché eseguendo le attività di configurazione se applicabili e possibili. In base ai parametri applicabili, è quindi possibile migrare le cassette postali, monitorare i processi e fornire report di stato.
  
Potrebbe essere necessario fornire a Microsoft autorizzazione e accesso al proprio sistema di posta per eseguire le attività di migrazione.
  
 **Procedura e criteri di migrazione**
  
- Le migrazioni vengono pianificate anticipatamente e vengono eseguite in modo standard 24 ore al giorno, 5 giorni a settimana (24 x 5) all'interno della fascia oraria di migrazione predefinita. Una "fascia oraria di migrazione" viene anche denominata "batch di migrazione". 
    
- Sono disponibili tre fasce orarie di migrazione per ogni giorno. Durante la settimana, sono disponibili 5 giorni per la migrazione: da lunedì alle 2:00 UTC (Coordinated Universal Time) al venerdì a mezzanotte UTC. Ciò significa che l'ultima migrazione pianificata viene eseguita il venerdì alle 20:00 UTC.
    
- Tutte le migrazioni utilizzano strumenti di migrazione basati su cloud.
    
- Potrebbe essere necessario fornire a Microsoft autorizzazione e accesso al proprio sistema di posta per eseguire le attività di migrazione.
    
 **Stato finale**
  
Lo stato finale previsto in seguito a un batch di migrazione include quanto segue:
  
- I dati delle cassette postali pianificate e idonee presenti nell'ambiente di origine vengono migrati in Office 365.
    
- Viene fornito da Microsoft un report di post-migrazione per il batch di migrazione.
    
Lo stato finale atteso al termine di tutte le migrazioni include quanto segue:
  
- I dati delle cassette postali di origine idonee vengono migrati su Office 365 come illustrato nella tabella seguente.
    
- Il tipo di dati da migrare dipende dall'ambiente di origine, come indicato nella tabella seguente.
    
> [!NOTE]
> Tutti gli ambienti di origine devono trovarsi a livello di Service Pack (SP) e di rollup (RU)/aggiornamento cumulativo (CU) per il rispettivo prodotto nell'ambiente di origine, al termine della fase di attivazione. I servizi di migrazione dei dati sono soggetti a fattori esterni oltre al controllo di Microsoft, come le modifiche alle interfacce API di terze parti, che potrebbero causare modifiche, ritardi o la sospensione di tali servizi. Per la durata dei servizi FastTrack, è possibile accedere ai dati resi disponibili per Microsoft e archiviarli dovunque sia presente una sede di Microsoft e dei suoi fornitori. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Ambiente di origine**|**Tipo di migrazione**|**Elementi sottoposti a migrazione**|**Elementi esclusi dalla migrazione**|
|Exchange 2003 e versioni successive|Completa| Messaggi di posta elettronica <br/> Regole della cassetta postale <br/> Delegati <br/> Contatti della cassetta postale <br/> Calendario <br/> Attività | Cartelle pubbliche <br/> Contatti personali <br/> Utenti abilitati all'utilizzo della posta <br/> Utenti bloccati o inattivi <br/> Firma <br/> Cassetta postale dumpster <br/>  Tutte le e-mail che superano il limite per la dimensione del messaggio <br/> Archiviazione dati <br/> Messaggi di posta elettronica crittografati o con contenuto protetto <br/> Elementi danneggiati <br/>  Cassette postali inattive |
|Exchange 2003 ed Exchange 2007|A fasi| Messaggi di posta elettronica <br/> Regole della cassetta postale <br/> Delegati <br/> Contatti della cassetta postale <br/> Calendario <br/> Attività | Cartelle pubbliche <br/> Contatti personali <br/> Utenti abilitati all'utilizzo della posta <br/> Utenti bloccati o inattivi <br/> Firma <br/> Cassetta postale dumpster <br/> Tutte le e-mail che superano il limite per la dimensione del messaggio <br/> Archiviazione dati <br/> Messaggi di posta elettronica crittografati o con contenuto protetto <br/> Elementi danneggiati <br/> Cassette postali inattive |
|Exchange 2010, Exchange 2013 ed Exchange 2016 <br/><br/> **Nota:** *per le dipendenze di Exchange locali, vedere [Prerequisiti per la distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).*           |Migrazione con distribuzione ibrida| Messaggi di posta elettronica <br/> Regole della cassetta postale <br/> Delegati <br/> Contatti della cassetta postale <br/> Calendario <br/> Attività <br/> Firma <br/> Archivio personale migrato con la cassetta postale dell'utente <br/> Elementi ripristinabili | Cartelle pubbliche <br/> Tutti i messaggi di posta elettronica che superano il limite relativo alla dimensione <br/> Archivio di inserimento nel journal oppure tutte le altre soluzioni di archiviazione di terze parti <br/> Utenti bloccati o inattivi <br/> Archiviazione dati da file PST (Personal Storage Table) <br/> Messaggi di posta elettronica crittografati o con contenuto protetto <br/> Elementi danneggiati <br/> Cassette postali inattive |
|Un ambiente G Suite (soltanto Gmail, Contatti e Calendario) <br/> <br/> **Nota** *Posizione dei dati: FastTrack può trasferire, elaborare e archiviare i dati migrati in base alla posizione del tenancy del cliente negli Stati Uniti o in qualsiasi altro luogo in cui si trovano le strutture di Microsoft o dei relativi fornitori di terze parti. FastTrack elimina i dati archiviati entro trenta giorni dal completamento dei servizi applicabili.*           |Completa o a fasi| Messaggi di posta elettronica <br/> Contatti della cassetta postale <br/> Calendario <br/> Etichette | regole <br/> Delegati <br/> Signature <br/> Attività <br/> Qualsiasi e-mail o allegato superiore ai 35 MB <br/> Utenti bloccati o inattivi <br/> Archiviazione dati da file PST o da una soluzione di archiviazione di terze parti (ad esempio, Google Vault) <br/> Messaggi di posta elettronica crittografati o con contenuto protetto <br/> Elementi danneggiati <br/> Hangouts di Google <br/> Gruppi di Google <br/> Cassette postali per la risorsa <br/> Cassette postali inattive |
|IBM Domino 7.0.3 e versioni successive ([Appendice A: Migrazione da IBM Domino a Exchange Online](from-ibm-domino-to-exchange-online.md))|A fasi| Messaggi di posta elettronica - ultimi 90 giorni <br/> Calendario - ultimi 90 giorni ed elementi futuri <br/> Contatti della cassetta postale - tutti <br/> Attività - tutte <br/> Sale e risorse - a condizione che siano implementate con il modello standard <br/> I file di posta elettronica, compresi i file di posta condivisi, devono utilizzare il modello di posta standard | Firme <br/> Regole della cassetta postale <br/> Delegati <br/> Elementi crittografati <br/> Collegamenti dei documenti <br/> Elementi decorativi dell'utente <br/> Tutti i messaggi di posta elettronica che superano il limite relativo alla dimensione <br/> Utenti bloccati o inattivi <br/> Archiviazione dati <br/> Elementi danneggiati <br/> Coesistenza di calendario <br/> Cassette postali inattive |
|Novell GroupWise 7.0.4 e versioni successive <br/><br/> **Nota** *Posizione dei dati: FastTrack può trasferire, elaborare e archiviare i dati migrati in base alla posizione del tenancy del cliente negli Stati Uniti o in qualsiasi altro luogo in cui si trovano le strutture di Microsoft o dei relativi fornitori di terze parti. FastTrack elimina i dati archiviati entro trenta giorni dal completamento dei servizi applicabili.*           |A fasi| Messaggi di posta elettronica <br/> Calendario <br/> Contatti della cassetta postale <br/> Gruppi personali <br/> Attività (con limitazioni) <br/> Documenti | Regole <br/> Conversione di proxy/delegati/elenco di controllo di accesso (ACL) <br/> Firme <br/> Categorie di contatto <br/> Messaggi di posta elettronica crittografati <br/> Cartelle di ricerca <br/> Qualsiasi e-mail o allegato superiore ai 35 MB <br/> Utenti bloccati o inattivi <br/> Archiviazione dati <br/> Elementi crittografati o con contenuto protetto <br/> Elementi danneggiati <br/> Coesistenza di calendario <br/> Cassette postali inattive |
|Origine IMAP4 |Migrazione tramite strumenti nativi di IMAP4| Messaggi di posta elettronica | Regole <br/> Delegati <br/> Liste di distribuzione <br/> Contatti esterni <br/> Utenti abilitati all'utilizzo della posta <br/> Utenti bloccati o inattivi <br/> Contatti della cassetta postale <br/> Calendario <br/> Firme <br/> Attività <br/> Tutte le e-mail che superano il limite per la dimensione del messaggio <br/> Archiviazione dati <br/> Messaggi di posta elettronica crittografati <br/> Elementi danneggiati <br/> Cassette postali inattive |
   
> [!NOTE]
> Se le liste di distribuzione (oggetti MailEnabledGroup) e i contatti esterni (oggetti MailEnabledContact) si trovano in Active Directory locale, è possibile sincronizzarli utilizzando Azure AD Connect. Tuttavia, non fanno parte della migrazione relativa ai dati della cassetta postale. Per maggior informazioni, vedere l'esempio **Identity Integration** in [Componenti di base](onboarding-and-migration.md#core). 
  
Gli esperti di FastTrack eseguono le seguenti operazioni durante le migrazioni:
  
- Fornisce il modello standard per pianificare le migrazioni della cassetta postale.
    
- Fornisce informazioni sulle autorizzazioni necessarie per specialisti FastTrack.
    
- Raccoglie informazioni relative alla pianificazione della migrazione predeterminata della cassetta postale in un formato prestabilito.
    
- Condivide gli strumenti preliminari con l'utente affinché sia possibile eseguire lo strumento preliminare e correggerne gli errori prima della migrazione delle cassette postali non riuscite.
    
- Tenta di eseguire fino a due migrazioni di una singola cassetta postale in un batch di migrazione, prima di segnalare la migrazione come non riuscita.
    
- Nel caso di ambienti di origine basati su Exchange e IMAP4, migrare i contenuti della cassetta postale dell'utente fino all'85% del limite di archiviazione (ad esempio, se il limite di archiviazione della cassetta postale è di 50 GB, Microsoft eseguirà la migrazione fino all'85% di tale limite). 
    
- Abilitare la coesistenza del routing di posta SMTP tra l'ambiente della messaggistica di origine e Office 365 Exchange Online, a meno che non si utilizzi la migrazione completa.
    
- Fornire i rapporti post-migrazione.
    
- Fornisce assistenza di post-migrazione in caso di problemi critici. I seguenti problemi vengono considerati critici:
    
  - Perdita di dati durante la migrazione.
    
  - L'ambiente di origine non è più disponibile durante la migrazione.
    
  - Le attività di migrazione causano errori nell'ambiente di origine.
    
Eseguire le seguenti operazioni durante le migrazioni:
  
- Completare l'onboarding a Exchange Online o superare i controlli necessari tramite FastTrack Center.
    
- Gestire tutte le comunicazioni con gli utenti finali.
    
- Installare il livello del software client più appropriato come indicato nelle linee guida di Office 365. Per ulteriori informazioni, vedere [Office 365 per le aziende](https://go.microsoft.com/fwlink/?linkid=2005429).
    
- Convalidare la coesistenza del routing di posta SMTP tra l'ambiente di messaggistica di origine e Office 365 Exchange Online, se applicabile.
    
- Fornire una pianificazione in un metodo definito e un elenco delle cassette postali specifiche da migrare in ogni fase, con almeno 14 giorni di anticipo. Nel caso delle migrazioni di note, accertarsi di fornire la pianificazione con 21 giorni di anticipo.
    
- Aggiungere alla pianificazione le cassette postali nuove o ripianificate, fino al 10% del totale delle cassette postali già pianificate. Tale operazione deve essere eseguita con 3 giorni di anticipo rispetto al batch di migrazione. A quel punto, si è giunti al batch di migrazione finale.
    
- Eliminare le cassette postali dalla pianificazione fino a 24 ore prima del batch di migrazione. A quel punto, si è giunti al batch di migrazione finale.
    
- Pianificare un numero medio di cassette postali di destinazione all'interno di un periodo di 24 ore, come descritto nella tabella seguente.
    
|||
|:-----|:-----|
|**Numero di cassette postali idonee per la migrazione** <br/> |**Media minima relativa alle cassette postali in un periodo di 24 ore** <br/> |
|150-1.000  <br/> |25% del totale  <br/> |
|1.001-5.000  <br/> |20% del totale  <br/> |
|5.001-10.000  <br/> |15% del totale  <br/> |
|\>10.000  <br/> |1.500  <br/> |
   
   > [!NOTE]
   > Tali cifre si basano sulle pratiche consigliate. Tuttavia, il numero di cassette postali sottoposte a migrazione ogni giorno varierà in base ai vincoli aziendali, di ambiente e conformità. Microsoft non è in grado di garantire la velocità di migrazione della cassetta postale. 
  
- Pianificare almeno 35 cassette postali in un batch di migrazione.
    
- Correggere gli errori della pre-migrazione (se applicabile).
    
- Fornire accesso e autorizzazione all'ambiente di origine, come stabilito dagli specialisti FastTrack al fine di eseguire attività di migrazione.
    
- Procurarsi e/o fornire account amministrativi con licenza in Office 365 per eseguire attività di migrazione (in base alle esigenze). 
    
- Supportare i problemi di migrazione dal lato client ed eseguire operazioni successive alla migrazione, se necessario.
    
- Eseguire la migrazione dei dati dal lato client, se desiderato. Tale migrazione include, ad esempio, le rubriche locali, i dati dei file PST locali, le regole e le impostazioni di Outlook locale.
    
- Ridurre la dimensione della cassetta postale a una percentuale inferiore rispetto all'85% del limite relativo alla cassetta postale di Office 365 (se applicabile).
    
- Gestire le azioni del rapporto di post-migrazione, comprese le cassette postali che non sono state spostate.
    
- Correggere gli errori di post-migrazione e pianificare di nuovo le cassette postali (se applicabile).
    
- Contribuire al supporto di post-migrazione in caso di problemi critici. I seguenti problemi vengono considerati critici:
    
  - Perdita di dati durante la migrazione.
    
  - L'ambiente di origine non è più disponibile durante la migrazione.
    
  - Le attività di migrazione causano errori nell'ambiente di origine.
    
È necessario seguire la procedura di migrazione standard e collaborare con Microsoft, fornendo autorizzazioni e accesso agli ambienti di origine e di Office 365, pianificazioni di migrazione, correggendo eventuali errori di migrazione e così via. Inoltre, è necessario rivolgersi agli utenti finali in caso di comunicazioni, pianificazione relativa alla migrazione della cassetta postale e gestione degli errori relativi alla migrazione dell'utente finale.
  
> [!NOTE]
> Le migrazioni utilizzano solo gli account che aderiscono ai requisiti di sicurezza definiti durante l'onboarding. Se non si utilizzano tali account, potrebbero verificarsi ritardi di migrazione. 
  
## <a name="migration-to-sharepoint-online"></a>Migrazione a SharePoint Online

 **Abilitare alla migrazione**
  
Se si utilizza Microsoft per eseguire la migrazione dei dati, sono disponibili istruzioni per abilitare SharePoint Online e l'ambiente di origine per la migrazione. A seconda dell'origine, è possibile che vengano eseguiti diversi passaggi di abilitazione. Viene fornita assistenza all'utente mediante una combinazione di strumenti e documentazione, nonché eseguendo le attività di configurazione se applicabili e possibili.
  
È necessario fornire a Microsoft l'accesso e le autorizzazioni per eseguire alcune attività.
  
 **Procedura e criteri di migrazione**
  
- Le migrazioni vengono assegnate\* per essere completate in base a pianificazioni standard, che a loro volta si basano sull'origine di migrazione riportata nella tabella seguente: 
    
|||
|:-----|:-----|
|**Origine** <br/> |**Criterio di programmazione** <br/> |
|Condivisione file, casella  <br/> | 24x5 in base a batch di migrazione predefiniti.  <br/>  Tre batch di migrazione per ogni giorni giorno.  <br/>  Durante la settimana, sono disponibili 5 giorni per la migrazione: da lunedì alle 2:00 UTC al venerdì a mezzanotte UTC.  <br/>  L'ultima finestra di migrazione pianificata viene eseguita il venerdì alle 20:00 UTC.  <br/> |
   
*La pianificazione si basa sulla dimensione del set di dati presunta e su fattori ambientali. È possibile che alcuni contenuti pianificati non siano in grado di migrare all'interno di una singola finestra di migrazione.
    
- Le migrazioni vengono pianificate anticipatamente e vengono eseguite in modo standard su una base 24x5 all'interno di batch di migrazione predefiniti. 
    
- Sono disponibili tre fasce orarie di migrazione per ogni giorno. Durante la settimana, sono disponibili 5 giorni per la migrazione: da lunedì alle 2:00 UTC al venerdì a mezzanotte UTC. Ciò significa che l'ultima migrazione pianificata viene eseguita il venerdì alle 20:00 UTC.
    
- Tutte le migrazioni richiedono accesso e autorizzazioni appropriate per l'ambiente di origine.
    
- Tutte le migrazioni sono soggette alle quote di SharePoint Online descritte in [SharePoint Online e OneDrive for Business: limiti del software](https://go.microsoft.com/fwlink/?LinkID=616612).
    
- La quantità complessiva dei dati migrati sarà legata al 75% della quota di archiviazione di SharePoint Online complessiva per la quale è abilitato l'utente (compresa l'archiviazione aggiuntiva che potrebbe essere stata acquistata separatamente).
    
 **Stato finale**
  
Lo stato finale previsto in seguito a un batch di migrazione include quanto segue:
  
- I dati delle origini pianificate e idonee presenti nell'ambiente di origine vengono migrati in SharePoint Online.
    
- Viene fornito da Microsoft un report di post-migrazione per il batch di migrazione.
    
Lo stato finale atteso al termine di tutte le migrazioni include quanto segue:
  
- I dati dell'origine idonea vengono migrati su Office 365 come illustrato nella tabella seguente.
    
- Il tipo di dati da migrare dipende dall'ambiente di origine, come indicato nella tabella seguente:
    
|||||
|:-----|:-----|:-----|:-----|
|**Ambiente di origine** <br/> |**Tipo di migrazione** <br/> |**Elementi sottoposti alla migrazione** <br/> |**Elementi esclusi dalla migrazione** <br/> |
|Qualsiasi dispositivo di condivisione dei file che supporta SMB 2.0 e versioni successive  <br/> |Passaggio singolo  <br/> | Documenti  <br/>   Struttura di file e cartelle  <br/>  Autorizzazioni per file e cartelle a livello di utente\*  <br/>  Autorizzazioni per file e cartelle a livello di gruppo\*  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/><br/> \**Configurazione della sincronizzazione della directory necessaria. Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows. Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate. Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.* <br/> | Cronologia di proprietà e versioni precedenti  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Versioni precedenti  <br/>  File di Windows e attributi di cartella (come Di sola lettura e Nascosto)  <br/>  Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):  <br/>  Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)  <br/>  Configurazione di controllo NTFS  <br/>  Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)  <br/>  Documenti inaccessibili o corrotti  <br/>  Condivisioni nascoste  <br/>  Condivisione (come autorizzazioni concesse a livello di condivisione)  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|Box (Starter, Business, Enterprise)  <br/> |Passaggio singolo  <br/> | Documenti  <br/>   Struttura di file e cartelle  <br/>  Autorizzazioni per file e cartelle a livello di utente  <br/>  Autorizzazioni per file e cartelle a livello di gruppo  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/>  Contenuto condiviso di proprietà dell'account Box migrato (se condiviso esplicitamente con utenti o gruppi)\*  <br/><br/> \**Utilizzare i report Box per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> | Cronologia di proprietà, versioni precedenti e commenti  <br/>  Descrizioni di file e cartelle  <br/>  Tag Box e metadati avanzati  <br/>  Attributi di blocco di file  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Elementi eliminati  <br/>  Documenti inaccessibili o corrotti  <br/>  Utenti bloccati o inattivi  <br/>  Note Box (non funzionali perché migrate senza conversione)  <br/>  App Box, Segnalibri, Preferiti e Flussi di lavoro  <br/>  Contenuto non di proprietà dell'account Box migrato (cartelle condivise)  <br/>  Autorizzazioni e metadati di base di utenti esterni\*  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
   
Gli esperti di FastTrack eseguono le seguenti operazioni durante le migrazioni:
  
- Conduce un workshop dettagliato sulla migrazione illustrando la procedura e il metodo per lo scenario di migrazione selezionato.
    
- Fornisce i prerequisiti per gli strumenti di valutazione e migrazione applicabili per lo scenario.
    
- Fornisce i prerequisiti per l'accesso del team di migrazione all'ambiente di origine e di destinazione ai fini della valutazione e della migrazione.
    
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
  
- Fornisce le risorse del progetto consigliate per le attività di valutazione e migrazione. Ad esempio:
    
  - Gestione dei progetti.
    
  - Test di accettazione utenti (UAT).
    
  - Amministratori responsabili delle piattaforme dei contenuti di origine e di destinazione.
    
- Fornisce i prerequisiti dell'infrastruttura per le attività di valutazione e migrazione (se richiesto).
    
- Fornisce accesso e autorizzazione all'ambiente di origine e di destinazione, come stabilito dagli specialisti FastTrack al fine di eseguire attività di migrazione (se richiesto).
    
    > [!NOTE]
    > Le migrazioni utilizzano solo gli account che aderiscono ai requisiti di sicurezza definiti durante l'onboarding. Se non si utilizzano tali account, potrebbero verificarsi ritardi di migrazione. 
  
- Fornire i prerequisiti ed eseguire attività necessarie per supportare valutazione e migrazione.
    
- Installa gli strumenti di valutazione forniti da FastTrack e completa le attività di raccolta dei dati di valutazione (se applicabile).
    
- Installa il software di migrazione fornito da FastTrack in locale (se applicabile).
    
- Completa le attività di correzione descritte nell'apposito report fornito da FastTrack (se applicabile).
    
- Fornisce una pianificazione di migrazione mediante le linee guida e i modelli di FastTrack.
    
- Conduce una verifica di controllo qualità della migrazione e il test di accettazione per gli utenti. 
    
- Conduce la correzione della migrazione post-migrazione (se applicabile).
    
- Pianifica e implementa la gestione delle modifiche e le comunicazioni con gli utenti finali (se applicabile).
    
- Amministra e configura le eventuali modifiche apportate al sistema di origine e ai dispositivi necessari per il completamento delle attività di migrazione e valutazione.
    
## <a name="migration-to-onedrive-for-business"></a>Migrazione a OneDrive for Business

 **Abilitare alla migrazione**
  
Se si utilizza Microsoft per eseguire la migrazione dei dati, sono disponibili istruzioni per abilitare OneDrive for Business e l'ambiente di origine per la migrazione. A seconda dell'origine, è possibile che vengano eseguiti diversi passaggi di abilitazione. Viene fornita assistenza all'utente per alcune attività mediante una combinazione di strumenti, documentazione e linee guida, nonché eseguendo le attività di configurazione se applicabili e possibili.
  
Potrebbe essere necessario fornire a Microsoft autorizzazione e accesso per eseguire alcune attività. In caso contrario, l'utente deve eseguire alcune attività autonomamente, con la guida di Microsoft. 
  
 **Procedura e criteri di migrazione**
  
- Le migrazioni vengono assegnate\* per essere completate in base a pianificazioni standard, che a loro volta si basano sull'origine di migrazione riportata nella tabella seguente: 
    
|||
|:-----|:-----|
|**Origine** <br/> |**Criterio di programmazione** <br/> |
|Condivisione di file, casella, Google Drive  <br/> | 24x5 in base a batch di migrazione predefiniti.  <br/>  Tre batch di migrazione per ogni giorni giorno.  <br/>  Durante la settimana, sono disponibili 5 giorni per la migrazione: da lunedì alle 2:00 UTC al venerdì a mezzanotte UTC.  <br/>  L'ultima finestra di migrazione pianificata viene eseguita il venerdì alle 20:00 UTC.  <br/> |
   
*La pianificazione si basa sulla dimensione del set di dati presunta e su fattori ambientali. È possibile che alcuni contenuti pianificati non siano in grado di migrare all'interno di una singola finestra di migrazione.
    
- Tutte le migrazioni richiedono accesso e autorizzazioni appropriate per l'ambiente di origine.
    
- Tutte le migrazioni sono soggette alle quote di OneDrive for Business descritte in [SharePoint Online e OneDrive for Business: limiti del software](https://go.microsoft.com/fwlink/?LinkId=698855).
    
 **Stato finale**
  
Lo stato finale previsto in seguito a un batch di migrazione include quanto segue: 
  
- I dati delle origini pianificate e idonee presenti nell'ambiente di origine vengono migrati in OneDrive for Business.
    
- Viene fornito da Microsoft un report di post-migrazione per il batch di migrazione.
    
Lo stato finale atteso al termine di tutte le migrazioni include quanto segue:
  
- I dati delle origini idonee vengono migrati su Office 365, come illustrato nella tabella seguente.
    
- Il tipo di dati da migrare dipende dall'ambiente di origine, come indicato nella tabella seguente.
    
|||||
|:-----|:-----|:-----|:-----|
|**Ambiente di origine**|**Tipo di migrazione**|**Elementi sottoposti alla migrazione**|**Elementi esclusi dalla migrazione**|
|Singolo ambiente di G Suite (soltanto Google Drive)  <br/> |Passaggio singolo  <br/> | Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente)  <br/>  Disegni Google (i file sono convertiti in formato .svg o .png)  <br/>  Struttura di file e cartelle  <br/>  Autorizzazioni per file e cartelle a livello di utente  <br/>  Autorizzazioni per file e cartelle a livello di gruppo  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/>  Contenuto condiviso di proprietà dell'account Google Drive migrato (se condiviso esplicitamente con utenti o gruppi)  <br/> | Cronologia di proprietà, versioni precedenti e commenti  <br/>  Descrizioni di file e cartelle, colori delle cartelle  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Elementi eliminati  <br/>  Documenti inaccessibili o corrotti  <br/>  Utenti bloccati o inattivi  <br/>  Contenuti condivisi esterni all'organizzazione  <br/>  Google Photos. Moduli, Maps e altre app connesse  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|Qualsiasi dispositivo di condivisione dei file che supporta SMB 2.0 e versioni successive  <br/> |Passaggio singolo  <br/> | Documenti  <br/>   Struttura di file e cartelle  <br/>  Autorizzazioni per file e cartelle a livello di utente\*  <br/>  Autorizzazioni per file e cartelle a livello di gruppo\*  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/> <br/>\**Configurazione della sincronizzazione della directory necessaria. Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows. Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate. Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.* <br/> | Cronologia di proprietà e versioni precedenti  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Versioni precedenti  <br/>  File di Windows e attributi di cartella (come Di sola lettura e Nascosto)  <br/>  Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):  <br/>  Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)  <br/>  Configurazione di controllo NTFS  <br/>  Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)  <br/>  Documenti inaccessibili o corrotti  <br/>  Condivisioni nascoste  <br/>  Condivisione (come autorizzazioni concesse a livello di condivisione)  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|Box (Starter, Business, Enterprise)  <br/> |Passaggio singolo  <br/> | Documenti  <br/>   Struttura di file e cartelle  <br/>  Autorizzazioni per file e cartelle a livello di utente  <br/>  Autorizzazioni per file e cartelle a livello di gruppo  <br/>  File inferiori a 15 GB  <br/>  Metadati cartella e documenti di base:  <br/>  Data creazione  <br/>  Data modifica  <br/>  Creato da  <br/>  Autore ultima modifica  <br/>  Contenuto condiviso di proprietà dell'account Box migrato (se condiviso esplicitamente con utenti o gruppi)\*  <br/><br/> \**Utilizzare i report Box per identificare gli account esterni. Indicare agli utenti finali di ricondividere i propri contenuti dopo la migrazione.* <br/> | Cronologia di proprietà, versioni precedenti e commenti  <br/>  Descrizioni di file e cartelle  <br/>  Tag Box e metadati avanzati  <br/>  Attributi di blocco di file  <br/>  Conversione degli URL incorporati nel contenuto  <br/>  Elementi eliminati  <br/>  Documenti inaccessibili o corrotti  <br/>  Utenti bloccati o inattivi  <br/>  Note Box (non funzionali perché migrate senza conversione)  <br/>  App Box, Segnalibri, Preferiti e Flussi di lavoro  <br/>  Contenuto non di proprietà dell'account Box migrato (cartelle condivise)  <br/>  Autorizzazioni e metadati di base di utenti esterni\*  <br/>  File o cartelle che superano [i limiti e le restrizioni di SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
   
Gli esperti di FastTrack eseguono le seguenti operazioni durante le migrazioni:
  
- Conduce un workshop dettagliato sulla migrazione illustrando la procedura e il metodo per lo scenario di migrazione selezionato.
    
- Fornisce i prerequisiti per gli strumenti di valutazione e migrazione applicabili per lo scenario.
    
- Fornisce i prerequisiti per l'accesso del team di migrazione all'ambiente di origine e di destinazione ai fini della valutazione e della migrazione.
    
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
  
- Fornisce le risorse del progetto consigliate per le attività di valutazione e migrazione. Ad esempio:
    
  - Gestione dei progetti.
    
  - UAT.
    
  - Amministratori responsabili delle piattaforme dei contenuti di origine e di destinazione.
    
- Fornisce i prerequisiti dell'infrastruttura per le attività di valutazione e migrazione (se richiesto).
    
- Fornisce accesso e autorizzazione all'ambiente di origine e di destinazione, come stabilito dagli specialisti FastTrack al fine di eseguire attività di migrazione (se richiesto).
    
    > [!NOTE]
    > Le migrazioni utilizzano solo gli account che aderiscono ai requisiti di sicurezza definiti durante l'onboarding. Se non si utilizzano tali account, potrebbero verificarsi ritardi di migrazione. 
  
- Installare gli strumenti di valutazione forniti da FastTrack e completare le attività di raccolta dei dati di valutazione (se applicabile).
    
- Installa il software di migrazione fornito da FastTrack in locale (se applicabile).
    
- Completa le attività di correzione descritte nell'apposito report fornito da FastTrack (se applicabile).
    
- Fornisce una pianificazione di migrazione mediante le linee guida e i modelli di FastTrack.
    
- Conduce una verifica di controllo qualità della migrazione e il test di accettazione per gli utenti. 
    
- Conduce la correzione della migrazione post-migrazione (se applicabile).
    
- Pianifica e implementa la gestione delle modifiche e le comunicazioni con gli utenti finali (se applicabile).
    
- Amministrare e configurare le eventuali modifiche apportate al sistema di origine e ai dispositivi necessari per il completamento delle attività di migrazione e valutazione.
    
  

