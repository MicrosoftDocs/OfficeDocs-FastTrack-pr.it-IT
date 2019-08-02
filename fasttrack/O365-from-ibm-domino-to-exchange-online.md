---
title: Appendice A Migrazione da IBM Domino a Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 08/02/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'La migrazione da IBM Domino a Exchange Online include diversi aspetti importanti, tra cui le attività eseguite durante le fasi seguenti:'
ms.openlocfilehash: 83235a7765aa424baf92d9081fec86b6f688c365
ms.sourcegitcommit: 911b0d32a26eb068a2a94ebc48d9f8f2fc70e5a9
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 08/01/2019
ms.locfileid: "36053979"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="bf669-103">Appendice A: Migrazione da IBM Domino a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="bf669-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="bf669-104">La migrazione da IBM Domino a Exchange Online include diversi aspetti importanti, tra cui le attività eseguite durante le fasi seguenti:</span><span class="sxs-lookup"><span data-stu-id="bf669-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="bf669-105">Fase di avvio</span><span class="sxs-lookup"><span data-stu-id="bf669-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="bf669-106">Fase di valutazione</span><span class="sxs-lookup"><span data-stu-id="bf669-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="bf669-107">Fase di correzione</span><span class="sxs-lookup"><span data-stu-id="bf669-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="bf669-108">Fase di attivazione:</span><span class="sxs-lookup"><span data-stu-id="bf669-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="bf669-109">Fase di migrazione</span><span class="sxs-lookup"><span data-stu-id="bf669-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="bf669-110">Identità</span><span class="sxs-lookup"><span data-stu-id="bf669-110">Identities</span></span>

<span data-ttu-id="bf669-111">L'utente è responsabile della creazione e della gestione delle identità (solo cloud, sincronizzate o federate con Active Directory locale).</span><span class="sxs-lookup"><span data-stu-id="bf669-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory).</span></span> <span data-ttu-id="bf669-112">È necessario completare il mapping delle identità (se non è già presente) tra Domino e Active Directory locale o Azure Active Directory durante le fasi iniziali dell'onboarding.</span><span class="sxs-lookup"><span data-stu-id="bf669-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure Active Directory during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="bf669-113">Coesistenza</span><span class="sxs-lookup"><span data-stu-id="bf669-113">Coexistence</span></span>

<span data-ttu-id="bf669-114">FastTrack Center Benefit per Office 365 fornisce un flusso di posta bidirezionale tra l'ambiente Domino locale ed Exchange Online a tutti i clienti.</span><span class="sxs-lookup"><span data-stu-id="bf669-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="bf669-115">Migrazione</span><span class="sxs-lookup"><span data-stu-id="bf669-115">Migration</span></span>

<span data-ttu-id="bf669-p102">Il processo di FastTrack Center standard per la migrazione da Domino a Exchange Online interessa i dati di Domino di pregestione per Azure prima della migrazione alle cassette postali di Exchange Online. Le migrazioni di FastTrack richiedono l'esecuzione di attività da parte del personale di FastTrack Center e dell'utente nelle diverse fasi dell'onboarding. Queste attività sono descritte nelle sezioni seguenti.</span><span class="sxs-lookup"><span data-stu-id="bf669-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="bf669-p103">I dati migrati tramite i servizi FastTrack possono essere trasferiti, archiviati ed elaborati negli Stati Uniti o dovunque sia presente una sede Microsoft. I servizi FastTrack non sono progettati per i dati soggetti a particolari requisiti normativi o legali.</span><span class="sxs-lookup"><span data-stu-id="bf669-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="bf669-121">Fase di avvio</span><span class="sxs-lookup"><span data-stu-id="bf669-121">Initiate phase</span></span>

 <span data-ttu-id="bf669-122">**Azioni principali**</span><span class="sxs-lookup"><span data-stu-id="bf669-122">**Key actions**</span></span>
  
- <span data-ttu-id="bf669-123">Identificare Domino come piattaforma di posta elettronica di origine.</span><span class="sxs-lookup"><span data-stu-id="bf669-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="bf669-124">Determinare se FastTrack Center esegue la migrazione.</span><span class="sxs-lookup"><span data-stu-id="bf669-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="bf669-125">**Responsabilità dell'utente**</span><span class="sxs-lookup"><span data-stu-id="bf669-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="bf669-126">Fornire informazioni di base sulla piattaforma di messaggistica di origine e confermare l'intenzione di effettuare la migrazione con FastTrack Center.</span><span class="sxs-lookup"><span data-stu-id="bf669-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="bf669-127">Partecipare a una procedura dettagliata dei processi relativi al vantaggio FastTrack Center.</span><span class="sxs-lookup"><span data-stu-id="bf669-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="bf669-128">Firmare il contratto per i servizi FastTrack.</span><span class="sxs-lookup"><span data-stu-id="bf669-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="bf669-129">Fase di valutazione</span><span class="sxs-lookup"><span data-stu-id="bf669-129">Assess phase</span></span>

 <span data-ttu-id="bf669-130">**Azioni principali**</span><span class="sxs-lookup"><span data-stu-id="bf669-130">**Key actions**</span></span>
  
- <span data-ttu-id="bf669-131">FastTrack Center organizza un workshop sulla migrazione con il cliente.</span><span class="sxs-lookup"><span data-stu-id="bf669-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="bf669-132">L'utente completa i prerequisiti della migrazione, come l'apposito questionario e il provisioning delle workstation amministrative.</span><span class="sxs-lookup"><span data-stu-id="bf669-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="bf669-133">La valutazione della migrazione per Domino viene effettuata nell'ambiente locale dell'utente.</span><span class="sxs-lookup"><span data-stu-id="bf669-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="bf669-134">**Responsabilità dell'utente**</span><span class="sxs-lookup"><span data-stu-id="bf669-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="bf669-135">Effettuare il provisioning delle workstation amministrative utilizzate da FastTrack Center per l'amministrazione dell'onboarding e delle attività di migrazione, come la valutazione, la creazione di repliche, il controllo, la configurazione dell'inoltro durante la migrazione e così via.</span><span class="sxs-lookup"><span data-stu-id="bf669-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="bf669-p104">La valutazione è fondamentale per la pianificazione e l'esecuzione corretta di migrazioni su vasta scala. Viene effettuata da un tecnico della migrazione che necessita di un accesso specifico all'ambiente Domino. Tra i componenti delle workstation amministrative necessari rientra un client Notes configurato per l'accesso a tutti i server di posta Domino di origine e il server di gestione temporanea delle repliche di Domino di Azure.</span><span class="sxs-lookup"><span data-stu-id="bf669-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="bf669-p105">Fornire al team responsabile della migrazione l'accesso remoto alle workstation amministrative, agli account e alle autorizzazioni per effettuare le attività di valutazione e migrazione. Queste attività prevedono il provisioning di più account in locale e in Exchange Online con le autorizzazioni amministrative necessarie per la migrazione.</span><span class="sxs-lookup"><span data-stu-id="bf669-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="bf669-p106">Aprire le porte del firewall. È necessario che le porte in uscita siano aperte tra i server di posta Domino di origine e il server di gestione temporanea di Azure. Devono essere aperte anche le altre porte per le comunicazioni (come le workstation amministrative, i server Domino di origine e i server Exchange locali, se presenti).</span><span class="sxs-lookup"><span data-stu-id="bf669-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="bf669-p107">Abilitare la certificazione incrociata tra l'ambiente Domino di origine e il server di gestione temporanea Domino di Azure per agevolare la replica. Le attività relative alla certificazione incrociata sono coordinate tra l'amministratore Domino dei clienti e FastTrack Center.</span><span class="sxs-lookup"><span data-stu-id="bf669-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="bf669-146">Completare il questionario sulla migrazione, che raccoglie le informazioni necessarie per la configurazione dell'ambiente di migrazione in Azure (come gli strumenti, gli script e i server di migrazione).</span><span class="sxs-lookup"><span data-stu-id="bf669-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="bf669-147">Verificare che le cassette postali di destinazione in Office 365 abbiano il protocollo MAPI (Messaging Application Program Interface) abilitato.</span><span class="sxs-lookup"><span data-stu-id="bf669-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="bf669-p108">Alcuni piani di Office 365 non supportano il protocollo MAPI. Per eseguire la migrazione dei dati, le cassette postali di tali piani devono essere convertite in un piano compatibile con MAPI prima dell'evento della migrazione. In seguito alla migrazione, questi piani possono essere modificati di nuovo.</span><span class="sxs-lookup"><span data-stu-id="bf669-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="bf669-151">Fase di correzione</span><span class="sxs-lookup"><span data-stu-id="bf669-151">Remediate phase</span></span>

 <span data-ttu-id="bf669-152">**Azioni principali**</span><span class="sxs-lookup"><span data-stu-id="bf669-152">**Key actions**</span></span>
  
- <span data-ttu-id="bf669-153">FastTrack Center esamina il report di valutazione della migrazione e verifica i dati forniti dall'utente tramite il questionario.</span><span class="sxs-lookup"><span data-stu-id="bf669-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="bf669-154">Le correzioni suggerite da FastTrack Center devono essere completate dall'utente.</span><span class="sxs-lookup"><span data-stu-id="bf669-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="bf669-155">**Responsabilità dell'utente**</span><span class="sxs-lookup"><span data-stu-id="bf669-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="bf669-156">Correggere l'ambiente Domino in base alle linee guida indicate da FastTrack Center (ad esempio, la configurazione di eventuali autorizzazioni necessarie identificate come mancanti nei file di posta).</span><span class="sxs-lookup"><span data-stu-id="bf669-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="bf669-157">Assicurarsi che le dimensioni delle cassette postali di Domino siano inferiori al limite consentito nella migrazione.</span><span class="sxs-lookup"><span data-stu-id="bf669-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="bf669-158">Anche se FastTrack effettua la migrazione di una quantità massima di contenuti pari all'85% delle dimensioni totali consentite del target, tentare di migrare cassette postali di dimensioni superiori ai 2 GB comporta rischi aggiuntivi come quelli indicati di seguito:</span><span class="sxs-lookup"><span data-stu-id="bf669-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="bf669-p109">Durata prolungata delle migrazioni.    </span><span class="sxs-lookup"><span data-stu-id="bf669-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="bf669-p110">Utilizzo di risorse altrimenti usate per la migrazione di altre cassette postali.    </span><span class="sxs-lookup"><span data-stu-id="bf669-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="bf669-161">Notevole aumento della percentuale di errori.</span><span class="sxs-lookup"><span data-stu-id="bf669-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="bf669-p111">Predisporre i database della posta in arrivo e i relativi ACL per la migrazione. È necessario eseguire alcune procedure di correzione per migrare in modo corretto i database della posta in arrivo e le relative autorizzazioni a una cassetta postale condivisa in Exchange Online. Alcune di queste procedure sono le seguenti:</span><span class="sxs-lookup"><span data-stu-id="bf669-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="bf669-165">Rimuovere le voci dei database della posta in arrivo esistenti nella directory di Domino e creare nuovi record Persona.</span><span class="sxs-lookup"><span data-stu-id="bf669-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="bf669-166">Creare gruppi di sicurezza universali abilitati alla posta elettronica in Active Directory locale che siano sincronizzati a Office 365Azure Active Directory e usati per configurare le autorizzazioni per la cassetta postale condivisa in Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="bf669-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure Active Directory and used to configure permissions on the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="bf669-167">In questo modo le autorizzazioni impostate per il database della posta in arrivo vengono trasferite sulla cassetta postale condivisa in Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="bf669-167">This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="bf669-168">A questo punto è possibile avviare la valutazione e la formazione degli utenti finali per il nuovo sistema di messaggistica e il client.</span><span class="sxs-lookup"><span data-stu-id="bf669-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="bf669-169">Fase di attivazione:</span><span class="sxs-lookup"><span data-stu-id="bf669-169">Enable phase</span></span>

 <span data-ttu-id="bf669-170">**Azioni principali**</span><span class="sxs-lookup"><span data-stu-id="bf669-170">**Key actions**</span></span>
  
- <span data-ttu-id="bf669-171">FastTrack Center:</span><span class="sxs-lookup"><span data-stu-id="bf669-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="bf669-172">Configura l'ambiente di migrazione in Azure.</span><span class="sxs-lookup"><span data-stu-id="bf669-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="bf669-173">Configura gli strumenti di migrazione sulle workstation amministrative locali.</span><span class="sxs-lookup"><span data-stu-id="bf669-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="bf669-174">Configura e mostra come utilizzare lo strumento di importazione automatica.</span><span class="sxs-lookup"><span data-stu-id="bf669-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="bf669-175">Esegue la convalida di tutti i componenti della migrazione ed esegue le migrazioni di prova.</span><span class="sxs-lookup"><span data-stu-id="bf669-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="bf669-176">**Responsabilità dell'utente**</span><span class="sxs-lookup"><span data-stu-id="bf669-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="bf669-p113">Il personale responsabile della pianificazione della migrazione della cassetta postale deve comprendere come usare lo strumento di importazione automatica. Tale strumento consente di importare il programma della migrazione nel database di pianificazione, che viene utilizzato da FastTrack Center per effettuare le attività di preparazione alla migrazione.</span><span class="sxs-lookup"><span data-stu-id="bf669-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="bf669-179">Eseguire le attività preliminari alla migrazione quali l'importazione dei programmi dell'utente, l'analisi dei report di controllo, la correzione di eventuali problemi e la reimportazione degli account utente con problemi.</span><span class="sxs-lookup"><span data-stu-id="bf669-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="bf669-p114">Le attività di preparazione alla migrazione sono coordinate tra l'utente e FastTrack Center. La replica di Azure viene avviata dopo l'importazione del programma della migrazione dell'utente.</span><span class="sxs-lookup"><span data-stu-id="bf669-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="bf669-p115">Il tempo necessario per tale operazione dipende dalla quantità di dati. FastTrack Center esegue un controllo per determinare la conformità della migrazione. Gli esiti del controllo vengono forniti all'utente, con la consapevolezza che in genere è necessaria una fase di correzione successiva. Tutte queste attività vengono denominate "T-minus" perché devono iniziare prima della migrazione pianificata degli utenti.</span><span class="sxs-lookup"><span data-stu-id="bf669-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="bf669-186">Fase di migrazione</span><span class="sxs-lookup"><span data-stu-id="bf669-186">Migrate phase</span></span>

 <span data-ttu-id="bf669-187">**Azioni principali**</span><span class="sxs-lookup"><span data-stu-id="bf669-187">**Key actions**</span></span>
  
- <span data-ttu-id="bf669-188">FastTrack Center:</span><span class="sxs-lookup"><span data-stu-id="bf669-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="bf669-189">Esegue migrazioni pilota e su vasta scala.</span><span class="sxs-lookup"><span data-stu-id="bf669-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="bf669-190">Esegue eventi di migrazione e attività "T-minus".</span><span class="sxs-lookup"><span data-stu-id="bf669-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="bf669-191">Fornisce supporto post-migrazione.</span><span class="sxs-lookup"><span data-stu-id="bf669-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="bf669-192">**Responsabilità dell'utente**</span><span class="sxs-lookup"><span data-stu-id="bf669-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="bf669-193">Identificare e importare eventuali pianificazioni di migrazione 21 giorni prima della migrazione.</span><span class="sxs-lookup"><span data-stu-id="bf669-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="bf669-p116">Questa operazione è molto importante perché le attività di preparazione alla migrazione comprendono la correzione e i possibili tentativi di creazione di repliche nelle diverse fasi prima della data della migrazione effettiva (T-0). Durante la migrazione di alcune cassette postali, le attività "T-minus" vengono eseguite sulle altre. Ciò rende necessaria una perfetta pianificazione e coordinazione.</span><span class="sxs-lookup"><span data-stu-id="bf669-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="bf669-197">Risolvere i problemi rilevati durante le attività "T-minus".</span><span class="sxs-lookup"><span data-stu-id="bf669-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="bf669-198">Individuare e risolvere eventuali problemi del server Domino che influiscono sulle attività di migrazione.</span><span class="sxs-lookup"><span data-stu-id="bf669-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="bf669-199">Inviare comunicazioni all'utente finale sulla data di migrazione.</span><span class="sxs-lookup"><span data-stu-id="bf669-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="bf669-200">Condurre attività di valutazione dell'utente finale e formazione per il nuovo sistema di messaggistica e il client.</span><span class="sxs-lookup"><span data-stu-id="bf669-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="bf669-p117">Individuare e segnalare i problemi di post-migrazione. FastTrack Center fornisce supporto post-migrazione fino a 5 giorni dopo la migrazione (T+5), allo scadere dei quali tutto ciò che riguarda la migrazione sarà di responsabilità dell'utente. È possibile registrare ticket di post-migrazione per problemi quali messaggi di posta elettronica, elementi di calendario e contatti mancanti o per la presenza di duplicati nella cassetta postale.</span><span class="sxs-lookup"><span data-stu-id="bf669-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="bf669-204">FastTrack Center non copre la distribuzione, i canoni di licenza o il supporto relativo alla preparazione della directory (compresa la sincronizzazione delle directory Domino e Active Directory), i componenti aggiuntivi del software per la coesistenza per l'interoperabilità delle applicazioni Notes, la migrazione self-service o la migrazione dell'archivio.</span><span class="sxs-lookup"><span data-stu-id="bf669-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

