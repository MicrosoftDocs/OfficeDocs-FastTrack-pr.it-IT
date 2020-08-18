---
title: Migrazione dei dati
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack consente di eseguire la migrazione della posta elettronica e dei file negli ambienti di origine in Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). Il tipo di assistenza che forniamo varia in base al numero di licenze di Office 365.
ms.openlocfilehash: fc7f07aea6104fdc6f06b3d624778919b351b34d
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 08/17/2020
ms.locfileid: "46776888"
---
# <a name="data-migration"></a><span data-ttu-id="83dcc-104">Migrazione dei dati</span><span class="sxs-lookup"><span data-stu-id="83dcc-104">Data Migration</span></span>

<span data-ttu-id="83dcc-105">FastTrack consente di eseguire la migrazione della posta elettronica e dei file negli ambienti di origine in Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="83dcc-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="83dcc-106">Il tipo di assistenza che forniamo varia in base al numero di licenze di Office 365:</span><span class="sxs-lookup"><span data-stu-id="83dcc-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="83dcc-107">**Per i tenant di Office 365 con 150-499 licenze**: FastTrack fornisce solo una guida alla migrazione. Tu sei il responsabile dell'esecuzione della migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="83dcc-108">Ti guideremo attraverso la documentazione che ti aiuta a pianificare e usare strumenti gratuiti per eseguire una migrazione in modalità self-service.</span><span class="sxs-lookup"><span data-stu-id="83dcc-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="83dcc-109">**Per i tenant di Office 365 con 500 o più licenze**: FastTrack fornisce indicazioni di migrazione e servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="83dcc-110">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e il tenant di Office 365 e usare a tuo vantaggio i nostri servizi di migrazione dei dati per la migrazione dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="83dcc-111">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-111">You create and schedule your migration events.</span></span> <span data-ttu-id="83dcc-112">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="83dcc-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="83dcc-113">Se hai acquistato o rinnovato un piano commerciale prima del 1/9/2017, sono necessarie solo 150 licenze per qualificarsi ai servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="83dcc-114">Per i piani per il settore dell'istruzione, solo l'istituto di istruzione a pagamento e il personale sono idonei per i servizi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="83dcc-115">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="83dcc-115">Considerations</span></span>

  - <span data-ttu-id="83dcc-116">Per eseguire la migrazione dei dati in Office 365, è necessario che gli ambienti di origine soddisfino aspettative specifiche.</span><span class="sxs-lookup"><span data-stu-id="83dcc-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="83dcc-117">Per altre informazioni sulle aspettative relative all’ambiente di origine di Exchange, SharePoint e OneDrive for Business, consulta [Prodotti e funzionalità ](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="83dcc-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="83dcc-118">Sono necessari l'accesso e le autorizzazioni appropriate agli ambienti di origine e al tenant di Office 365 per offrire servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="83dcc-119">I servizi di migrazione dei dati non sono progettati né destinati per i dati soggetti a particolari requisiti normativi o legali.</span><span class="sxs-lookup"><span data-stu-id="83dcc-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="83dcc-120">Durante la migrazione dei dati, è possibile trasferire, archiviare ed elaborare i dati da qualsiasi luogo in cui vengono gestiti i servizi, ad eccezione di quanto specificato per il progetto di migrazione FastTrack.</span><span class="sxs-lookup"><span data-stu-id="83dcc-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="83dcc-121">Microsoft non garantisce la velocità di migrazione dei file o e-mail.</span><span class="sxs-lookup"><span data-stu-id="83dcc-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="83dcc-122">Problemi imprevisti (come elementi illeggibili o corrotti nell'ambiente di origine) possono impedire la capacità di migrazione di alcuni dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="83dcc-123">Fattori esterni fuori controllo, come modifiche apportate alle interfacce API per le applicazioni di terze parti, possono comportare modifiche, ritardi o sospensioni dei servizi di migrazione dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="83dcc-124">Disponibilità servizio migrazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-124">Migration service availability</span></span>

  - <span data-ttu-id="83dcc-125">**Per clienti commerciali e del governo del Regno Unito:** Microsoft offre servizi di migrazione dei dati, 24 ore al giorno, sette (7) giorni alla settimana (24x7).</span><span class="sxs-lookup"><span data-stu-id="83dcc-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="83dcc-126">**Per i clienti del governo e del Dipartimento della difesa degli Stati Uniti:** Microsoft offre servizi di migrazione dei dati, 24 ore al giorno, cinque (5) giorni lavorativi alla settimana (24x5).</span><span class="sxs-lookup"><span data-stu-id="83dcc-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="83dcc-127">Migrazione a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="83dcc-127">Migration to Exchange Online</span></span>

<span data-ttu-id="83dcc-128">Se scegli di usare FastTrack per eseguire la migrazione della posta elettronica a Exchange Online, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="83dcc-129">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e Exchange Online e usare a tuo vantaggio i nostri servizi di migrazione dati per le cassette postali.</span><span class="sxs-lookup"><span data-stu-id="83dcc-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="83dcc-130">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-130">You create and schedule your migration events.</span></span> <span data-ttu-id="83dcc-131">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="83dcc-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="83dcc-132">Al termine degli eventi di migrazione, è possibile che la posta proveniente dalle cassette postali di origine idonee e pianificate in modo appropriato degli ambienti di origine sia stata migrata a Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="83dcc-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="83dcc-133">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="83dcc-133">Considerations</span></span>

  - <span data-ttu-id="83dcc-134">Prima della migrazione, è necessario completare FastTrack Core onboarding per Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="83dcc-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="83dcc-135">Se hai già eseguito l’onboarding personalmente, è necessario superare i controlli e prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="83dcc-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="83dcc-136">Per informazioni dettagliate, visita [Prodotti e funzionalità](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="83dcc-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="83dcc-137">FastTrack migra soltanto verso cassette postali di Office 365 attive.</span><span class="sxs-lookup"><span data-stu-id="83dcc-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="83dcc-138">È necessario soddisfare requisiti specifici se intendi migrare da un ambiente Exchange locale.</span><span class="sxs-lookup"><span data-stu-id="83dcc-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="83dcc-139">Per informazioni dettagliate, visita [Prerequisiti di distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="83dcc-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="83dcc-140">Ogni ambiente di origine deve essere al livello di aggiornamento del Service Pack (SP) e del rollup (RU)/aggiornamento cumulativo (CU) per il rispettivo prodotto nell'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="83dcc-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="83dcc-141">Le liste di distribuzione (oggetti *MailEnabledGroup*) e i contatti esterni (oggetti *MailEnabledContact*) che si trovano in Active Directory locale non fanno parte della migrazione dei dati delle cassette postali.</span><span class="sxs-lookup"><span data-stu-id="83dcc-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="83dcc-142">È possibile tuttavia sincronizzarli con Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="83dcc-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="83dcc-143">Ambienti di origine</span><span class="sxs-lookup"><span data-stu-id="83dcc-143">Source environments</span></span>

<span data-ttu-id="83dcc-144">Il servizio di migrazione dei dati esegue la migrazione dei dati dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="83dcc-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="83dcc-145">Una o più insiemi di strutture di Active Directory con una o multiple organizzazioni di Exchange (ogni sistema di posta di Exchange deve essere Exchange 2010 o versione successiva).</span><span class="sxs-lookup"><span data-stu-id="83dcc-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="83dcc-146">Un ambiente di posta elettronica con funzionalità IMAP singola.</span><span class="sxs-lookup"><span data-stu-id="83dcc-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="83dcc-147">Ambiente G Suite (solo Gmail, Contatti e Calendario)</span><span class="sxs-lookup"><span data-stu-id="83dcc-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="83dcc-148">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="83dcc-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="83dcc-149"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="83dcc-150"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="83dcc-151"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="83dcc-152"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="83dcc-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016 o Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="83dcc-154">
<strong>Nota:</strong>  per le dipendenze di Exchange locali, vedere  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Prerequisiti per la distribuzione ibrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="83dcc-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="83dcc-155">Migrazione con distribuzione ibrida</span><span class="sxs-lookup"><span data-stu-id="83dcc-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="83dcc-156">Messaggi di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="83dcc-156">Emails</span></span></li>
<li><span data-ttu-id="83dcc-157">Regole della cassetta postale</span><span class="sxs-lookup"><span data-stu-id="83dcc-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="83dcc-158">Delegati</span><span class="sxs-lookup"><span data-stu-id="83dcc-158">Delegates</span></span></li>
<li><span data-ttu-id="83dcc-159">Contatti della cassetta postale</span><span class="sxs-lookup"><span data-stu-id="83dcc-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="83dcc-160">Calendario</span><span class="sxs-lookup"><span data-stu-id="83dcc-160">Calendar</span></span> </li>
<li> <span data-ttu-id="83dcc-161">Attività</span><span class="sxs-lookup"><span data-stu-id="83dcc-161">Tasks</span></span> </li>
<li> <span data-ttu-id="83dcc-162">Messaggi di posta elettronica con contenuto protetto da Microsoft Rights Management</span><span class="sxs-lookup"><span data-stu-id="83dcc-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="83dcc-163">Messaggi di posta elettronica crittografati</span><span class="sxs-lookup"><span data-stu-id="83dcc-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="83dcc-164">Firme</span><span class="sxs-lookup"><span data-stu-id="83dcc-164">Signatures</span></span> </li>
<li> <span data-ttu-id="83dcc-165">Archivio personale migrato con la cassetta postale dell'utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="83dcc-166">Elementi ripristinabili</span><span class="sxs-lookup"><span data-stu-id="83dcc-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="83dcc-167">Cartelle pubbliche</span><span class="sxs-lookup"><span data-stu-id="83dcc-167">Public folders</span></span> </li>
<li> <span data-ttu-id="83dcc-168">Tutti i messaggi di posta elettronica che superano il limite relativo alla dimensione</span><span class="sxs-lookup"><span data-stu-id="83dcc-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="83dcc-169">Archivio di inserimento nel journal oppure tutte le altre soluzioni di archiviazione di terze parti</span><span class="sxs-lookup"><span data-stu-id="83dcc-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="83dcc-170">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="83dcc-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="83dcc-171">Archiviazione dati da file PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="83dcc-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="83dcc-172">Elementi danneggiati</span><span class="sxs-lookup"><span data-stu-id="83dcc-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="83dcc-173">Cassette postali inattive</span><span class="sxs-lookup"><span data-stu-id="83dcc-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="83dcc-174"><strong>Ambiente G Suite (solo Gmail, Contatti e Calendario)</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="83dcc-175">
<strong>Nota:</strong> l'ambiente G Suite deve rispettare i prerequisiti descritti in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Eseguire una migrazione di G Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="83dcc-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="83dcc-176">Completa o a fasi</span><span class="sxs-lookup"><span data-stu-id="83dcc-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-177">Messaggi di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="83dcc-177">Emails</span></span> </li>
<li> <span data-ttu-id="83dcc-178">Contatti di cassette postali (al massimo tre indirizzi di posta elettronica per ogni contatto)</span><span class="sxs-lookup"><span data-stu-id="83dcc-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="83dcc-179">Calendario</span><span class="sxs-lookup"><span data-stu-id="83dcc-179">Calendar</span></span> </li>
<li> <span data-ttu-id="83dcc-180">Etichette</span><span class="sxs-lookup"><span data-stu-id="83dcc-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="83dcc-181">regole</span><span class="sxs-lookup"><span data-stu-id="83dcc-181">Rules</span></span> </li>
<li> <span data-ttu-id="83dcc-182">Delegati</span><span class="sxs-lookup"><span data-stu-id="83dcc-182">Delegates</span></span> </li>
<li> <span data-ttu-id="83dcc-183">Firme</span><span class="sxs-lookup"><span data-stu-id="83dcc-183">Signatures</span></span> </li>
<li> <span data-ttu-id="83dcc-184">Attività</span><span class="sxs-lookup"><span data-stu-id="83dcc-184">Tasks</span></span> </li>
<li> <span data-ttu-id="83dcc-185">Tutti i messaggi di posta elettronica o allegati che superano il limite relativo alla dimensione</span><span class="sxs-lookup"><span data-stu-id="83dcc-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="83dcc-186">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="83dcc-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="83dcc-187">Archiviazione dati da file PST o da una soluzione di archiviazione di terze parti (ad esempio, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="83dcc-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="83dcc-188">Messaggi di posta elettronica crittografati o con contenuto protetto</span><span class="sxs-lookup"><span data-stu-id="83dcc-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="83dcc-189">Elementi danneggiati</span><span class="sxs-lookup"><span data-stu-id="83dcc-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="83dcc-190">Hangouts di Google\*\*</span><span class="sxs-lookup"><span data-stu-id="83dcc-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="83dcc-191">Gruppi di Google</span><span class="sxs-lookup"><span data-stu-id="83dcc-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="83dcc-192">Cassette postali per la risorsa</span><span class="sxs-lookup"><span data-stu-id="83dcc-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="83dcc-193">Cassette postali inattive</span><span class="sxs-lookup"><span data-stu-id="83dcc-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="83dcc-194">Impostazioni delle ferie e impostazioni di risposta automatica</span><span class="sxs-lookup"><span data-stu-id="83dcc-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="83dcc-195">Calendari condivisi, allegati cloud, collegamenti di Google Hangout e colori per gli eventi</span><span class="sxs-lookup"><span data-stu-id="83dcc-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="83dcc-196">\*\*È stata eseguita la migrazioni di conversazioni di Hangout salvate come etichetta.</span><span class="sxs-lookup"><span data-stu-id="83dcc-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="83dcc-197"><strong>Origine IMAP4 (come Domino, GroupWise o Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="83dcc-198">Migrazione tramite strumenti nativi di IMAP4</span><span class="sxs-lookup"><span data-stu-id="83dcc-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="83dcc-199">Messaggi di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="83dcc-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="83dcc-200">Regole</span><span class="sxs-lookup"><span data-stu-id="83dcc-200">Rules</span></span> </li>
<li> <span data-ttu-id="83dcc-201">Delegati</span><span class="sxs-lookup"><span data-stu-id="83dcc-201">Delegates</span></span> </li>
<li> <span data-ttu-id="83dcc-202">Liste di distribuzione</span><span class="sxs-lookup"><span data-stu-id="83dcc-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="83dcc-203">Contatti esterni</span><span class="sxs-lookup"><span data-stu-id="83dcc-203">External contacts</span></span> </li>
<li> <span data-ttu-id="83dcc-204">Utenti abilitati all'utilizzo della posta</span><span class="sxs-lookup"><span data-stu-id="83dcc-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="83dcc-205">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="83dcc-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="83dcc-206">Contatti della cassetta postale</span><span class="sxs-lookup"><span data-stu-id="83dcc-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="83dcc-207">Calendario</span><span class="sxs-lookup"><span data-stu-id="83dcc-207">Calendar</span></span> </li>
<li> <span data-ttu-id="83dcc-208">Firme</span><span class="sxs-lookup"><span data-stu-id="83dcc-208">Signatures</span></span> </li>
<li> <span data-ttu-id="83dcc-209">Attività</span><span class="sxs-lookup"><span data-stu-id="83dcc-209">Tasks</span></span> </li>
<li> <span data-ttu-id="83dcc-210">Tutte le e-mail che superano il limite per la dimensione del messaggio</span><span class="sxs-lookup"><span data-stu-id="83dcc-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="83dcc-211">Archiviazione dati</span><span class="sxs-lookup"><span data-stu-id="83dcc-211">Archive data</span></span> </li>
<li> <span data-ttu-id="83dcc-212">Messaggi di posta elettronica crittografati</span><span class="sxs-lookup"><span data-stu-id="83dcc-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="83dcc-213">Elementi danneggiati</span><span class="sxs-lookup"><span data-stu-id="83dcc-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="83dcc-214">Cassette postali inattive</span><span class="sxs-lookup"><span data-stu-id="83dcc-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="83dcc-215">Responsabilità di FastTrack</span><span class="sxs-lookup"><span data-stu-id="83dcc-215">FastTrack responsibilities</span></span>

<span data-ttu-id="83dcc-216">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="83dcc-217">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="83dcc-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="83dcc-218">Gli specialisti di FastTrack eseguono anche le attività seguenti, specifiche della migrazione di Exchange:</span><span class="sxs-lookup"><span data-stu-id="83dcc-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="83dcc-219">Forniscono indicazioni utili per abilitare la coesistenza di routing della posta SMTP tra gli ambienti di origine e Exchange Online, se applicabile.</span><span class="sxs-lookup"><span data-stu-id="83dcc-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="83dcc-220">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-220">Your responsibilities</span></span>

<span data-ttu-id="83dcc-221">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="83dcc-222">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="83dcc-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="83dcc-223">Tu esegui anche le attività seguenti, specifiche della migrazione di Exchange:</span><span class="sxs-lookup"><span data-stu-id="83dcc-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="83dcc-224">Completamento FastTrack Core onboarding per Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="83dcc-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="83dcc-225">Se hai già eseguito l’onboarding personalmente, è necessario superare i controlli e prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="83dcc-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="83dcc-226">Per informazioni dettagliate, visita [Prodotti e funzionalità](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="83dcc-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="83dcc-227">Installazione del livello appropriato di software client in base alle linee guida di Office 365.</span><span class="sxs-lookup"><span data-stu-id="83dcc-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="83dcc-228">Per informazioni dettagliate, vedere [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="83dcc-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="83dcc-229">Soddisfare i requisiti specifici se intendi migrare da un ambiente Exchange locale.</span><span class="sxs-lookup"><span data-stu-id="83dcc-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="83dcc-230">Per informazioni dettagliate, visita [Prerequisiti di distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="83dcc-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="83dcc-231">Assicurati che ogni ambiente di origine si trovi al livello di aggiornamento del Service Pack (SP) e del rollup (RU)/aggiornamento cumulativo (CU), se applicabile.</span><span class="sxs-lookup"><span data-stu-id="83dcc-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="83dcc-232">Configura e convalida la coesistenza di routing della posta SMTP tra gli ambienti di origine e Exchange Online, se applicabile.</span><span class="sxs-lookup"><span data-stu-id="83dcc-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="83dcc-233">Verifica che le dimensioni della cassetta postale di origine non superino la quota di destinazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="83dcc-234">A seconda della piattaforma di origine, potrebbe essere necessario limitare i dati di origine all’85% della quota delle cassette postali di destinazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="83dcc-235">Puoi migrare i dati dal lato client.</span><span class="sxs-lookup"><span data-stu-id="83dcc-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="83dcc-236">Tale migrazione include, ad esempio, le rubriche locali, i dati dei file PST locali, le regole di Outlook e le impostazioni di Outlook locale.</span><span class="sxs-lookup"><span data-stu-id="83dcc-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="83dcc-237">Aiutare gli utenti finali a correggere i problemi di migrazione sul lato client.</span><span class="sxs-lookup"><span data-stu-id="83dcc-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="83dcc-238">Migrazione a SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="83dcc-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="83dcc-239">Se scegli di usare FastTrack per eseguire la migrazione dei tuoi file di SharePoint Online, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="83dcc-240">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e SharePoint Online e usare a tuo vantaggio i nostri servizi di migrazione dati per i tuoi file.</span><span class="sxs-lookup"><span data-stu-id="83dcc-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="83dcc-241">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-241">You create and schedule your migration events.</span></span> <span data-ttu-id="83dcc-242">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="83dcc-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="83dcc-243">Al termine degli eventi di migrazione, è possibile che i file provenienti da fonti opportunamente programmate e idonee dei vostri ambienti di origine siano stati migrati a SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="83dcc-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="83dcc-244">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="83dcc-244">Considerations</span></span>

  - <span data-ttu-id="83dcc-245">Tutte le migrazioni sono soggette a quote di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="83dcc-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="83dcc-246">Per informazioni dettagliate, vedere [<span class="underline">SharePoint Online e OneDrive for Business: limiti del software</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="83dcc-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="83dcc-247">È consigliabile limitare l'importo complessivo della migrazione al 75% della quota complessiva di SharePoint Online a cui si ha diritto (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente).</span><span class="sxs-lookup"><span data-stu-id="83dcc-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="83dcc-248">Dettagli ambiente di origine</span><span class="sxs-lookup"><span data-stu-id="83dcc-248">Source environment details</span></span>

<span data-ttu-id="83dcc-249">Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="83dcc-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="83dcc-250">Condivisioni di file (condivisioni di file di Server Message Block su dispositivi che supportano SMB 2.0 e versioni successive).</span><span class="sxs-lookup"><span data-stu-id="83dcc-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="83dcc-251">Un singolo ambiente di G Suite (soltanto Google Drive).</span><span class="sxs-lookup"><span data-stu-id="83dcc-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="83dcc-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="83dcc-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="83dcc-253">Dropbox per Team (Standard e Advanced).</span><span class="sxs-lookup"><span data-stu-id="83dcc-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="83dcc-254">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="83dcc-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="83dcc-255"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="83dcc-256"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="83dcc-257"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="83dcc-258"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="83dcc-259"><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="83dcc-260">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="83dcc-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-261">Documenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-261">Documents</span></span> </li>
<li> <span data-ttu-id="83dcc-262">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="83dcc-263">Autorizzazioni per file e cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="83dcc-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="83dcc-264">Autorizzazioni per file e cartelle a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="83dcc-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="83dcc-265">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="83dcc-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="83dcc-266">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="83dcc-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="83dcc-267">Data creazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-267">Created date</span></span> </li>
<li> <span data-ttu-id="83dcc-268">Data modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-268">Modified date</span></span> </li>
<li> <span data-ttu-id="83dcc-269">Creato da</span><span class="sxs-lookup"><span data-stu-id="83dcc-269">Created by</span></span> </li>
<li> <span data-ttu-id="83dcc-270">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="83dcc-271">\*Configurazione della sincronizzazione della directory necessaria.</span><span class="sxs-lookup"><span data-stu-id="83dcc-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="83dcc-272">Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows.</span><span class="sxs-lookup"><span data-stu-id="83dcc-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="83dcc-273">Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate.</span><span class="sxs-lookup"><span data-stu-id="83dcc-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="83dcc-274">Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.</span><span class="sxs-lookup"><span data-stu-id="83dcc-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-275">Cronologia di proprietà e versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="83dcc-276">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="83dcc-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="83dcc-277">Versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="83dcc-278">File di Windows e attributi di cartella (come Di sola lettura e Nascosto)</span><span class="sxs-lookup"><span data-stu-id="83dcc-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="83dcc-279">Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):</span><span class="sxs-lookup"><span data-stu-id="83dcc-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="83dcc-280">Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)</span><span class="sxs-lookup"><span data-stu-id="83dcc-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="83dcc-281">Configurazione di controllo NTFS</span><span class="sxs-lookup"><span data-stu-id="83dcc-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="83dcc-282">Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)</span><span class="sxs-lookup"><span data-stu-id="83dcc-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="83dcc-283">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="83dcc-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="83dcc-284">Condivisioni nascoste</span><span class="sxs-lookup"><span data-stu-id="83dcc-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="83dcc-285">Condivisione (come autorizzazioni concesse a livello di condivisione)</span><span class="sxs-lookup"><span data-stu-id="83dcc-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="83dcc-286">File o cartelle che superano  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">i limiti e le restrizioni di SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="83dcc-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="83dcc-287"><strong>Ambiente G Suite singolo (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="83dcc-288">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="83dcc-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-289">Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente), anche quelli di oltre 10 MB</span><span class="sxs-lookup"><span data-stu-id="83dcc-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="83dcc-290">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="83dcc-291">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-292">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-293">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="83dcc-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="83dcc-294">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="83dcc-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="83dcc-295">Data creazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-295">Created date</span></span> </li>
<li> <span data-ttu-id="83dcc-296">Data modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-296">Modified date</span></span> </li>
<li> <span data-ttu-id="83dcc-297">Creato da</span><span class="sxs-lookup"><span data-stu-id="83dcc-297">Created by</span></span> </li>
<li> <span data-ttu-id="83dcc-298">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="83dcc-299">Unità condivise (cartelle e file)</span><span class="sxs-lookup"><span data-stu-id="83dcc-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="83dcc-300">Contenuto condiviso appartenente all'account Google Drive in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="83dcc-301">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="83dcc-302">Descrizioni di file e cartelle, colori delle cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="83dcc-303">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-304">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-305">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="83dcc-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="83dcc-306">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="83dcc-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="83dcc-307">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="83dcc-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="83dcc-308">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="83dcc-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="83dcc-309">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="83dcc-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="83dcc-310">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="83dcc-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="83dcc-311">Google Photos, Moduli, Maps e altre app connesse</span><span class="sxs-lookup"><span data-stu-id="83dcc-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="83dcc-312">Disegni Google</span><span class="sxs-lookup"><span data-stu-id="83dcc-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="83dcc-313">Contenuti condivisi esterni alla tua impresa</span><span class="sxs-lookup"><span data-stu-id="83dcc-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="83dcc-314">Contenuto che appartenente all'account Google Drive che è in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="83dcc-315">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="83dcc-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="83dcc-316">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="83dcc-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="83dcc-317">Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise.</span><span class="sxs-lookup"><span data-stu-id="83dcc-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="83dcc-318">Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione).</span><span class="sxs-lookup"><span data-stu-id="83dcc-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="83dcc-319">File o cartelle che superano  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">i limiti e le restrizioni di SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="83dcc-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="83dcc-320"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="83dcc-321">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="83dcc-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-322">Documenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-322">Documents</span></span> </li>
<li> <span data-ttu-id="83dcc-323">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="83dcc-324">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-325">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-326">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="83dcc-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="83dcc-327">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="83dcc-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="83dcc-328">Data creazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-328">Created date</span></span> </li>
<li> <span data-ttu-id="83dcc-329">Data modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-329">Modified date</span></span> </li>
<li> <span data-ttu-id="83dcc-330">Creato da</span><span class="sxs-lookup"><span data-stu-id="83dcc-330">Created by</span></span> </li>
<li> <span data-ttu-id="83dcc-331">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="83dcc-332">Contenuto condiviso appartenente all'account Box in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="83dcc-333">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="83dcc-334">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="83dcc-335">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-336">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-337">Tag Box e metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="83dcc-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="83dcc-338">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="83dcc-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="83dcc-339">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="83dcc-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="83dcc-340">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="83dcc-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="83dcc-341">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="83dcc-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="83dcc-342">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="83dcc-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="83dcc-343">App Box, Segnalibri, Preferiti e Flussi di lavoro</span><span class="sxs-lookup"><span data-stu-id="83dcc-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="83dcc-344">Contenuto non di proprietà dell'account Box migrato</span><span class="sxs-lookup"><span data-stu-id="83dcc-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="83dcc-345">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="83dcc-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="83dcc-346">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="83dcc-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="83dcc-347">File o cartelle che superano  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">i limiti e le restrizioni di SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="83dcc-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="83dcc-348"><strong>Dropbox per Team (Standard e Advanced)</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="83dcc-349">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="83dcc-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-350">Documenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-350">Documents</span></span> </li>
<li> <span data-ttu-id="83dcc-351">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="83dcc-352">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-353">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-354">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="83dcc-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="83dcc-355">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="83dcc-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="83dcc-356">Data creazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-356">Created date</span></span> </li>
<li> <span data-ttu-id="83dcc-357">Data modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-357">Modified date</span></span> </li>
<li> <span data-ttu-id="83dcc-358">Creato da</span><span class="sxs-lookup"><span data-stu-id="83dcc-358">Created by</span></span> </li>
<li> <span data-ttu-id="83dcc-359">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="83dcc-360">Contenuto e cartelle del team condiviso</span><span class="sxs-lookup"><span data-stu-id="83dcc-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="83dcc-361">Contenuto condiviso appartenente all'account Dropbox in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="83dcc-362">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="83dcc-363">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="83dcc-364">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-365">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-366">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="83dcc-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="83dcc-367">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="83dcc-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="83dcc-368">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="83dcc-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="83dcc-369">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="83dcc-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="83dcc-370">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="83dcc-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="83dcc-371">Cartelle Dropbox non montate</span><span class="sxs-lookup"><span data-stu-id="83dcc-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="83dcc-372">Utenti eliminati o scollegati</span><span class="sxs-lookup"><span data-stu-id="83dcc-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="83dcc-373">Dropbox Paper, Showcases, e Spaces</span><span class="sxs-lookup"><span data-stu-id="83dcc-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="83dcc-374">App e preferiti di Dropbox (Pins/stars)</span><span class="sxs-lookup"><span data-stu-id="83dcc-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="83dcc-375">Contenuto non di proprietà dell'account Dropbox migrato</span><span class="sxs-lookup"><span data-stu-id="83dcc-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="83dcc-376">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="83dcc-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="83dcc-377">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione)</span><span class="sxs-lookup"><span data-stu-id="83dcc-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="83dcc-378">File o cartelle che superano  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">i limiti e le restrizioni di SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="83dcc-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="83dcc-379">Responsabilità di FastTrack</span><span class="sxs-lookup"><span data-stu-id="83dcc-379">FastTrack responsibilities</span></span>

<span data-ttu-id="83dcc-380">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="83dcc-381">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli</span><span class="sxs-lookup"><span data-stu-id="83dcc-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="83dcc-382">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-382">Your responsibilities</span></span>

<span data-ttu-id="83dcc-383">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="83dcc-384">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli</span><span class="sxs-lookup"><span data-stu-id="83dcc-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="83dcc-385">Tu esegui anche le attività seguenti, specifiche della migrazione di SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="83dcc-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="83dcc-386">Esecuzione del provisioning di tutti i siti del team di SharePoint per gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="83dcc-387">Migrazione a OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="83dcc-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="83dcc-388">Se scegli di usare FastTrack per eseguire la migrazione dei tuoi file di OneDrive for Business, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="83dcc-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="83dcc-389">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e OneDrive for Business e usare a tuo vantaggio i nostri servizi di migrazione dati per i tuoi file.</span><span class="sxs-lookup"><span data-stu-id="83dcc-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="83dcc-390">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-390">You create and schedule your migration events.</span></span> <span data-ttu-id="83dcc-391">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="83dcc-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="83dcc-392">Al termine degli eventi di migrazione, è possibile che i file provenienti da fonti opportunamente programmate e idonee dei vostri ambienti di origine siano stati migrati a OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="83dcc-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="83dcc-393">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="83dcc-393">Considerations</span></span>

  - <span data-ttu-id="83dcc-394">Tutte le migrazioni sono soggette alle quote di OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="83dcc-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="83dcc-395">Per altre informazioni dettagliate, consulta [<span class="underline">SharePoint Online e OneDrive for Business: limiti del software</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="83dcc-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="83dcc-396">È consigliabile limitare la quantità totale dei dati migrati al 75% della quota di archiviazione globale di SharePoint Online a cui si è autorizzati (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente).</span><span class="sxs-lookup"><span data-stu-id="83dcc-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="83dcc-397">FastTrack esegue la migrazione solo alle unità attive di OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="83dcc-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="83dcc-398">Dettagli ambiente di origine</span><span class="sxs-lookup"><span data-stu-id="83dcc-398">Source environment details</span></span>

<span data-ttu-id="83dcc-399">Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="83dcc-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="83dcc-400">Condivisioni di file (condivisioni di file SMB su dispositivi che supportano SMB 2.0 e versioni successive).</span><span class="sxs-lookup"><span data-stu-id="83dcc-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="83dcc-401">Ambiente G Suite singolo (solo Google Drive)</span><span class="sxs-lookup"><span data-stu-id="83dcc-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="83dcc-402">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="83dcc-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="83dcc-403">Dropbox per Team (Standard e Advanced).</span><span class="sxs-lookup"><span data-stu-id="83dcc-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="83dcc-404">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="83dcc-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="83dcc-405"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="83dcc-406"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="83dcc-407"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="83dcc-408"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="83dcc-409"><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="83dcc-410">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="83dcc-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-411">Documenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-411">Documents</span></span> </li>
<li> <span data-ttu-id="83dcc-412">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="83dcc-413">Autorizzazioni per file e cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="83dcc-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="83dcc-414">Autorizzazioni per file e cartelle a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="83dcc-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="83dcc-415">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="83dcc-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="83dcc-416">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="83dcc-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="83dcc-417">Data creazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-417">Created date</span></span> </li>
<li> <span data-ttu-id="83dcc-418">Data modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-418">Modified date</span></span> </li>
<li> <span data-ttu-id="83dcc-419">Creato da</span><span class="sxs-lookup"><span data-stu-id="83dcc-419">Created by</span></span> </li>
<li> <span data-ttu-id="83dcc-420">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="83dcc-421">\*Configurazione della sincronizzazione della directory necessaria.</span><span class="sxs-lookup"><span data-stu-id="83dcc-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="83dcc-422">Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows.</span><span class="sxs-lookup"><span data-stu-id="83dcc-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="83dcc-423">Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate.</span><span class="sxs-lookup"><span data-stu-id="83dcc-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="83dcc-424">Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.</span><span class="sxs-lookup"><span data-stu-id="83dcc-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="83dcc-425">Cronologia di proprietà e versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="83dcc-426">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="83dcc-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="83dcc-427">Versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="83dcc-428">File di Windows e attributi di cartella (come Di sola lettura e Nascosto)</span><span class="sxs-lookup"><span data-stu-id="83dcc-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="83dcc-429">Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):</span><span class="sxs-lookup"><span data-stu-id="83dcc-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="83dcc-430">Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)</span><span class="sxs-lookup"><span data-stu-id="83dcc-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="83dcc-431">Configurazione di controllo NTFS</span><span class="sxs-lookup"><span data-stu-id="83dcc-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="83dcc-432">Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)</span><span class="sxs-lookup"><span data-stu-id="83dcc-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="83dcc-433">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="83dcc-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="83dcc-434">Condivisioni nascoste</span><span class="sxs-lookup"><span data-stu-id="83dcc-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="83dcc-435">Condivisione (come autorizzazioni concesse a livello di condivisione)</span><span class="sxs-lookup"><span data-stu-id="83dcc-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="83dcc-436">File o cartelle che superano  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">i limiti e le restrizioni di SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="83dcc-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="83dcc-437"><strong>Ambiente G Suite singolo (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="83dcc-438">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="83dcc-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-439">Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente, anche quelli di oltre 10 MB)</span><span class="sxs-lookup"><span data-stu-id="83dcc-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="83dcc-440">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="83dcc-441">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-442">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-443">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="83dcc-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="83dcc-444">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="83dcc-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="83dcc-445">Data creazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-445">Created date</span></span> </li>
<li> <span data-ttu-id="83dcc-446">Data modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-446">Modified date</span></span> </li>
<li> <span data-ttu-id="83dcc-447">Creato da</span><span class="sxs-lookup"><span data-stu-id="83dcc-447">Created by</span></span> </li>
<li> <span data-ttu-id="83dcc-448">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="83dcc-449">Unità condivise (cartelle e file)</span><span class="sxs-lookup"><span data-stu-id="83dcc-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="83dcc-450">Contenuto condiviso appartenente all'account Google Drive in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="83dcc-451">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="83dcc-452">Descrizioni di file e cartelle, colori delle cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="83dcc-453">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-454">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-455">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="83dcc-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="83dcc-456">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="83dcc-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="83dcc-457">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="83dcc-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="83dcc-458">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="83dcc-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="83dcc-459">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="83dcc-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="83dcc-460">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="83dcc-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="83dcc-461">Google Photos, Moduli, Maps e altre app connesse</span><span class="sxs-lookup"><span data-stu-id="83dcc-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="83dcc-462">Disegni Google</span><span class="sxs-lookup"><span data-stu-id="83dcc-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="83dcc-463">Contenuti condivisi esterni alla tua impresa</span><span class="sxs-lookup"><span data-stu-id="83dcc-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="83dcc-464">Contenuto che appartenente all'account Google Drive che è in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="83dcc-465">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="83dcc-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="83dcc-466">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="83dcc-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="83dcc-467">Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise.</span><span class="sxs-lookup"><span data-stu-id="83dcc-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="83dcc-468">Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione).</span><span class="sxs-lookup"><span data-stu-id="83dcc-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="83dcc-469">File o cartelle che superano  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">i limiti e le restrizioni di SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="83dcc-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="83dcc-470"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="83dcc-471">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="83dcc-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-472">Documenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-472">Documents</span></span> </li>
<li> <span data-ttu-id="83dcc-473">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="83dcc-474">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-475">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-476">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="83dcc-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="83dcc-477">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="83dcc-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="83dcc-478">Data creazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-478">Created date</span></span> </li>
<li> <span data-ttu-id="83dcc-479">Data modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-479">Modified date</span></span> </li>
<li> <span data-ttu-id="83dcc-480">Creato da</span><span class="sxs-lookup"><span data-stu-id="83dcc-480">Created by</span></span> </li>
<li> <span data-ttu-id="83dcc-481">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="83dcc-482">Contenuto condiviso appartenente all'account Box in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="83dcc-483">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="83dcc-484">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="83dcc-485">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-486">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-487">Tag Box e metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="83dcc-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="83dcc-488">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="83dcc-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="83dcc-489">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="83dcc-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="83dcc-490">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="83dcc-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="83dcc-491">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="83dcc-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="83dcc-492">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="83dcc-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="83dcc-493">App Box, Segnalibri, Preferiti e Flussi di lavoro</span><span class="sxs-lookup"><span data-stu-id="83dcc-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="83dcc-494">Contenuto non di proprietà dell'account Box migrato</span><span class="sxs-lookup"><span data-stu-id="83dcc-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="83dcc-495">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="83dcc-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="83dcc-496">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="83dcc-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="83dcc-497">File o cartelle che superano  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">i limiti e le restrizioni di SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="83dcc-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="83dcc-498"><strong>Dropbox per Team (Standard e Advanced)</strong></span><span class="sxs-lookup"><span data-stu-id="83dcc-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="83dcc-499">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="83dcc-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="83dcc-500">Documenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-500">Documents</span></span> </li>
<li> <span data-ttu-id="83dcc-501">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="83dcc-502">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-503">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-504">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="83dcc-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="83dcc-505">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="83dcc-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="83dcc-506">Data creazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-506">Created date</span></span> </li>
<li> <span data-ttu-id="83dcc-507">Data modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-507">Modified date</span></span> </li>
<li> <span data-ttu-id="83dcc-508">Creato da</span><span class="sxs-lookup"><span data-stu-id="83dcc-508">Created by</span></span> </li>
<li> <span data-ttu-id="83dcc-509">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="83dcc-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="83dcc-510">Contenuto e cartelle del team condiviso</span><span class="sxs-lookup"><span data-stu-id="83dcc-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="83dcc-511">Contenuto condiviso appartenente all'account Dropbox in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="83dcc-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="83dcc-512">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="83dcc-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="83dcc-513">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="83dcc-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="83dcc-514">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-515">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="83dcc-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="83dcc-516">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="83dcc-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="83dcc-517">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="83dcc-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="83dcc-518">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="83dcc-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="83dcc-519">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="83dcc-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="83dcc-520">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="83dcc-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="83dcc-521">Cartelle Dropbox non montate</span><span class="sxs-lookup"><span data-stu-id="83dcc-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="83dcc-522">Utenti eliminati o scollegati</span><span class="sxs-lookup"><span data-stu-id="83dcc-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="83dcc-523">Dropbox Paper, Showcases, e Spaces</span><span class="sxs-lookup"><span data-stu-id="83dcc-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="83dcc-524">App e preferiti di Dropbox (Pins/stars)</span><span class="sxs-lookup"><span data-stu-id="83dcc-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="83dcc-525">Contenuto non di proprietà dell'account Dropbox migrato</span><span class="sxs-lookup"><span data-stu-id="83dcc-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="83dcc-526">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="83dcc-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="83dcc-527">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="83dcc-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="83dcc-528">File o cartelle che superano  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">i limiti e le restrizioni di SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="83dcc-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="83dcc-529">Responsabilità di FastTrack</span><span class="sxs-lookup"><span data-stu-id="83dcc-529">FastTrack responsibilities</span></span>

<span data-ttu-id="83dcc-530">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="83dcc-531">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="83dcc-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="83dcc-532">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="83dcc-532">Your responsibilities</span></span>

<span data-ttu-id="83dcc-533">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="83dcc-534">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="83dcc-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="83dcc-535">Tu esegui anche le attività seguenti, specifiche della migrazione di OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="83dcc-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="83dcc-536">Esecuzione del provisioning di tutti i siti di OneDrive for Business che verranno assegnati agli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="83dcc-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
