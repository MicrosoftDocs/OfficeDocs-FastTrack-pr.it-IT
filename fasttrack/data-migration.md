---
title: Migrazione dei dati
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack consente di eseguire la migrazione della posta elettronica e dei file negli ambienti di origine in Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). Il tipo di assistenza che forniamo varia in base al numero di licenze di Office 365.
ms.openlocfilehash: ec7bc5cf9c25ef1e386c7fae42a5fd8e1716dee5
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750043"
---
# <a name="data-migration"></a><span data-ttu-id="eb0ca-104">Migrazione dei dati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-104">Data Migration</span></span>

<span data-ttu-id="eb0ca-105">FastTrack consente di eseguire la migrazione della posta elettronica e dei file negli ambienti di origine in Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="eb0ca-106">Il tipo di assistenza che forniamo varia in base al numero di licenze di Office 365:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="eb0ca-107">**Per i tenant di Office 365 con 150-499 licenze**: FastTrack fornisce solo una guida alla migrazione. Tu sei il responsabile dell'esecuzione della migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="eb0ca-108">Ti guideremo attraverso la documentazione che ti aiuta a pianificare e usare strumenti gratuiti per eseguire una migrazione in modalità self-service.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="eb0ca-109">**Per i tenant di Office 365 con 500 o più licenze**: FastTrack fornisce indicazioni di migrazione e servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="eb0ca-110">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e il tenant di Office 365 e usare a tuo vantaggio i nostri servizi di migrazione dei dati per la migrazione dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="eb0ca-111">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-111">You create and schedule your migration events.</span></span> <span data-ttu-id="eb0ca-112">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="eb0ca-113">Se hai acquistato o rinnovato un piano commerciale prima del 1/9/2017, sono necessarie solo 150 licenze per qualificarsi ai servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="eb0ca-114">Per i piani per il settore dell'istruzione, solo l'istituto di istruzione a pagamento e il personale sono idonei per i servizi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="eb0ca-115">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="eb0ca-115">Considerations</span></span>

  - <span data-ttu-id="eb0ca-116">Per eseguire la migrazione dei dati in Office 365, è necessario che gli ambienti di origine soddisfino aspettative specifiche.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="eb0ca-117">Per altre informazioni sulle aspettative relative all’ambiente di origine di Exchange, SharePoint e OneDrive for Business, consulta [Prodotti e funzionalità ](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="eb0ca-118">Sono necessari l'accesso e le autorizzazioni appropriate agli ambienti di origine e al tenant di Office 365 per offrire servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="eb0ca-119">I servizi di migrazione dei dati non sono progettati né destinati per i dati soggetti a particolari requisiti normativi o legali.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="eb0ca-120">Durante la migrazione dei dati, è possibile trasferire, archiviare ed elaborare i dati da qualsiasi luogo in cui vengono gestiti i servizi, ad eccezione di quanto specificato per il progetto di migrazione FastTrack.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="eb0ca-121">Microsoft non garantisce la velocità di migrazione dei file o e-mail.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="eb0ca-122">Problemi imprevisti (come elementi illeggibili o corrotti nell'ambiente di origine) possono impedire la capacità di migrazione di alcuni dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="eb0ca-123">Fattori esterni fuori controllo, come modifiche apportate alle interfacce API per le applicazioni di terze parti, possono comportare modifiche, ritardi o sospensioni dei servizi di migrazione dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="eb0ca-124">Disponibilità servizio migrazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-124">Migration service availability</span></span>

  - <span data-ttu-id="eb0ca-125">**Per clienti commerciali e del governo del Regno Unito:** Microsoft offre servizi di migrazione dei dati, 24 ore al giorno, sette (7) giorni alla settimana (24x7).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="eb0ca-126">**Per i clienti del governo e del Dipartimento della difesa degli Stati Uniti:** Microsoft offre servizi di migrazione dei dati, 24 ore al giorno, cinque (5) giorni lavorativi alla settimana (24x5).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="eb0ca-127">Migrazione a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="eb0ca-127">Migration to Exchange Online</span></span>

<span data-ttu-id="eb0ca-128">Se scegli di usare FastTrack per eseguire la migrazione della posta elettronica a Exchange Online, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="eb0ca-129">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e Exchange Online e usare a tuo vantaggio i nostri servizi di migrazione dati per le cassette postali.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="eb0ca-130">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-130">You create and schedule your migration events.</span></span> <span data-ttu-id="eb0ca-131">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="eb0ca-132">Al termine degli eventi di migrazione, è possibile che la posta proveniente dalle cassette postali di origine idonee e pianificate in modo appropriato degli ambienti di origine sia stata migrata a Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="eb0ca-133">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="eb0ca-133">Considerations</span></span>

  - <span data-ttu-id="eb0ca-134">Prima della migrazione, è necessario completare FastTrack Core onboarding per Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="eb0ca-135">Se hai già eseguito l’onboarding personalmente, è necessario superare i controlli e prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="eb0ca-136">Per informazioni dettagliate, visita [Prodotti e funzionalità](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="eb0ca-137">FastTrack migra soltanto verso cassette postali di Office 365 attive.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="eb0ca-138">È necessario soddisfare requisiti specifici se intendi migrare da un ambiente Exchange locale.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="eb0ca-139">Per informazioni dettagliate, visita [Prerequisiti di distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="eb0ca-140">Ogni ambiente di origine deve essere al livello di aggiornamento del Service Pack (SP) e del rollup (RU)/aggiornamento cumulativo (CU) per il rispettivo prodotto nell'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="eb0ca-141">Le liste di distribuzione (oggetti *MailEnabledGroup*) e i contatti esterni (oggetti *MailEnabledContact*) che si trovano in Active Directory locale non fanno parte della migrazione dei dati delle cassette postali.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="eb0ca-142">È possibile tuttavia sincronizzarli con Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="eb0ca-143">Ambienti di origine</span><span class="sxs-lookup"><span data-stu-id="eb0ca-143">Source environments</span></span>

<span data-ttu-id="eb0ca-144">Il servizio di migrazione dei dati esegue la migrazione dei dati dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="eb0ca-145">Una o più insiemi di strutture di Active Directory con una o multiple organizzazioni di Exchange (ogni sistema di posta di Exchange deve essere Exchange 2010 o versione successiva).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="eb0ca-146">Un ambiente di posta elettronica con funzionalità IMAP singola.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="eb0ca-147">Ambiente G Suite (solo Gmail, Contatti e Calendario)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="eb0ca-148">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="eb0ca-149"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="eb0ca-150"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="eb0ca-151"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="eb0ca-152"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="eb0ca-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016 o Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="eb0ca-154">
<strong>Nota:</strong> Per le dipendenze di Exchange locali, vedere Prerequisiti per la <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">distribuzione ibrida</span></a>.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="eb0ca-155">Migrazione con distribuzione ibrida</span><span class="sxs-lookup"><span data-stu-id="eb0ca-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="eb0ca-156">Messaggi di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-156">Emails</span></span></li>
<li><span data-ttu-id="eb0ca-157">Regole della cassetta postale</span><span class="sxs-lookup"><span data-stu-id="eb0ca-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="eb0ca-158">Delegati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-158">Delegates</span></span></li>
<li><span data-ttu-id="eb0ca-159">Contatti della cassetta postale</span><span class="sxs-lookup"><span data-stu-id="eb0ca-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="eb0ca-160">Calendario</span><span class="sxs-lookup"><span data-stu-id="eb0ca-160">Calendar</span></span> </li>
<li> <span data-ttu-id="eb0ca-161">Attività</span><span class="sxs-lookup"><span data-stu-id="eb0ca-161">Tasks</span></span> </li>
<li> <span data-ttu-id="eb0ca-162">Messaggi di posta elettronica con contenuto protetto da Microsoft Rights Management</span><span class="sxs-lookup"><span data-stu-id="eb0ca-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="eb0ca-163">Messaggi di posta elettronica crittografati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="eb0ca-164">Firme</span><span class="sxs-lookup"><span data-stu-id="eb0ca-164">Signatures</span></span> </li>
<li> <span data-ttu-id="eb0ca-165">Archivio personale migrato con la cassetta postale dell'utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="eb0ca-166">Elementi ripristinabili</span><span class="sxs-lookup"><span data-stu-id="eb0ca-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-167">Cartelle pubbliche</span><span class="sxs-lookup"><span data-stu-id="eb0ca-167">Public folders</span></span> </li>
<li> <span data-ttu-id="eb0ca-168">Tutti i messaggi di posta elettronica che superano il limite relativo alla dimensione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="eb0ca-169">Archivio di inserimento nel journal oppure tutte le altre soluzioni di archiviazione di terze parti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="eb0ca-170">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="eb0ca-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="eb0ca-171">Archiviazione dati da file PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="eb0ca-172">Elementi danneggiati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="eb0ca-173">Cassette postali inattive</span><span class="sxs-lookup"><span data-stu-id="eb0ca-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="eb0ca-174"><strong>Ambiente G Suite (solo Gmail, Contatti e Calendario)</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="eb0ca-175">
<strong>Nota:</strong> L'ambiente G Suite deve soddisfare i prerequisiti descritti in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">perform a g Suite Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="eb0ca-176">Completa o a fasi</span><span class="sxs-lookup"><span data-stu-id="eb0ca-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-177">Messaggi di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-177">Emails</span></span> </li>
<li> <span data-ttu-id="eb0ca-178">Contatti di cassette postali (al massimo tre indirizzi di posta elettronica per ogni contatto)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="eb0ca-179">Calendario</span><span class="sxs-lookup"><span data-stu-id="eb0ca-179">Calendar</span></span> </li>
<li> <span data-ttu-id="eb0ca-180">Etichette</span><span class="sxs-lookup"><span data-stu-id="eb0ca-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-181">regole</span><span class="sxs-lookup"><span data-stu-id="eb0ca-181">Rules</span></span> </li>
<li> <span data-ttu-id="eb0ca-182">Delegati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-182">Delegates</span></span> </li>
<li> <span data-ttu-id="eb0ca-183">Firme</span><span class="sxs-lookup"><span data-stu-id="eb0ca-183">Signatures</span></span> </li>
<li> <span data-ttu-id="eb0ca-184">Attività</span><span class="sxs-lookup"><span data-stu-id="eb0ca-184">Tasks</span></span> </li>
<li> <span data-ttu-id="eb0ca-185">Tutti i messaggi di posta elettronica o allegati che superano il limite relativo alla dimensione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="eb0ca-186">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="eb0ca-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="eb0ca-187">Archiviazione dati da file PST o da una soluzione di archiviazione di terze parti (ad esempio, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="eb0ca-188">Messaggi di posta elettronica crittografati o con contenuto protetto</span><span class="sxs-lookup"><span data-stu-id="eb0ca-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="eb0ca-189">Elementi danneggiati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="eb0ca-190">Hangouts di Google\*\*</span><span class="sxs-lookup"><span data-stu-id="eb0ca-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="eb0ca-191">Gruppi di Google</span><span class="sxs-lookup"><span data-stu-id="eb0ca-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="eb0ca-192">Cassette postali per la risorsa</span><span class="sxs-lookup"><span data-stu-id="eb0ca-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="eb0ca-193">Cassette postali inattive</span><span class="sxs-lookup"><span data-stu-id="eb0ca-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="eb0ca-194">Impostazioni delle ferie e impostazioni di risposta automatica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="eb0ca-195">Calendari condivisi, allegati cloud, collegamenti di Google Hangout e colori per gli eventi</span><span class="sxs-lookup"><span data-stu-id="eb0ca-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="eb0ca-196">\*\*È stata eseguita la migrazioni di conversazioni di Hangout salvate come etichetta.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="eb0ca-197"><strong>Origine IMAP4 (come Domino, GroupWise o Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="eb0ca-198">Migrazione tramite strumenti nativi di IMAP4</span><span class="sxs-lookup"><span data-stu-id="eb0ca-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="eb0ca-199">Messaggi di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-200">Regole</span><span class="sxs-lookup"><span data-stu-id="eb0ca-200">Rules</span></span> </li>
<li> <span data-ttu-id="eb0ca-201">Delegati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-201">Delegates</span></span> </li>
<li> <span data-ttu-id="eb0ca-202">Liste di distribuzione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="eb0ca-203">Contatti esterni</span><span class="sxs-lookup"><span data-stu-id="eb0ca-203">External contacts</span></span> </li>
<li> <span data-ttu-id="eb0ca-204">Utenti abilitati all'utilizzo della posta</span><span class="sxs-lookup"><span data-stu-id="eb0ca-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="eb0ca-205">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="eb0ca-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="eb0ca-206">Contatti della cassetta postale</span><span class="sxs-lookup"><span data-stu-id="eb0ca-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="eb0ca-207">Calendario</span><span class="sxs-lookup"><span data-stu-id="eb0ca-207">Calendar</span></span> </li>
<li> <span data-ttu-id="eb0ca-208">Firme</span><span class="sxs-lookup"><span data-stu-id="eb0ca-208">Signatures</span></span> </li>
<li> <span data-ttu-id="eb0ca-209">Attività</span><span class="sxs-lookup"><span data-stu-id="eb0ca-209">Tasks</span></span> </li>
<li> <span data-ttu-id="eb0ca-210">Tutte le e-mail che superano il limite per la dimensione del messaggio</span><span class="sxs-lookup"><span data-stu-id="eb0ca-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="eb0ca-211">Archiviazione dati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-211">Archive data</span></span> </li>
<li> <span data-ttu-id="eb0ca-212">Messaggi di posta elettronica crittografati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="eb0ca-213">Elementi danneggiati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="eb0ca-214">Cassette postali inattive</span><span class="sxs-lookup"><span data-stu-id="eb0ca-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="eb0ca-215">Responsabilità di FastTrack</span><span class="sxs-lookup"><span data-stu-id="eb0ca-215">FastTrack responsibilities</span></span>

<span data-ttu-id="eb0ca-216">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="eb0ca-217">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="eb0ca-218">Gli specialisti di FastTrack eseguono anche le attività seguenti, specifiche della migrazione di Exchange:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="eb0ca-219">Forniscono indicazioni utili per abilitare la coesistenza di routing della posta SMTP tra gli ambienti di origine e Exchange Online, se applicabile.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="eb0ca-220">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-220">Your responsibilities</span></span>

<span data-ttu-id="eb0ca-221">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="eb0ca-222">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="eb0ca-223">Tu esegui anche le attività seguenti, specifiche della migrazione di Exchange:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="eb0ca-224">Completamento FastTrack Core onboarding per Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="eb0ca-225">Se hai già eseguito l’onboarding personalmente, è necessario superare i controlli e prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="eb0ca-226">Per informazioni dettagliate, visita [Prodotti e funzionalità](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="eb0ca-227">Installazione del livello appropriato di software client in base alle linee guida di Office 365.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="eb0ca-228">Per informazioni dettagliate, vedere [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="eb0ca-229">Soddisfare i requisiti specifici se intendi migrare da un ambiente Exchange locale.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="eb0ca-230">Per informazioni dettagliate, visita [Prerequisiti di distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="eb0ca-231">Assicurati che ogni ambiente di origine si trovi al livello di aggiornamento del Service Pack (SP) e del rollup (RU)/aggiornamento cumulativo (CU), se applicabile.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="eb0ca-232">Configura e convalida la coesistenza di routing della posta SMTP tra gli ambienti di origine e Exchange Online, se applicabile.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="eb0ca-233">Verifica che le dimensioni della cassetta postale di origine non superino la quota di destinazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="eb0ca-234">A seconda della piattaforma di origine, potrebbe essere necessario limitare i dati di origine all’85% della quota delle cassette postali di destinazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="eb0ca-235">Puoi migrare i dati dal lato client.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="eb0ca-236">Tale migrazione include, ad esempio, le rubriche locali, i dati dei file PST locali, le regole di Outlook e le impostazioni di Outlook locale.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="eb0ca-237">Aiutare gli utenti finali a correggere i problemi di migrazione sul lato client.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="eb0ca-238">Migrazione a SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="eb0ca-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="eb0ca-239">Se scegli di usare FastTrack per eseguire la migrazione dei tuoi file di SharePoint Online, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="eb0ca-240">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e SharePoint Online e usare a tuo vantaggio i nostri servizi di migrazione dati per i tuoi file.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="eb0ca-241">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-241">You create and schedule your migration events.</span></span> <span data-ttu-id="eb0ca-242">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="eb0ca-243">Al termine degli eventi di migrazione, è possibile che i file provenienti da fonti opportunamente programmate e idonee dei vostri ambienti di origine siano stati migrati a SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="eb0ca-244">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="eb0ca-244">Considerations</span></span>

  - <span data-ttu-id="eb0ca-245">Tutte le migrazioni sono soggette a quote di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="eb0ca-246">Per informazioni dettagliate, vedere [<span class="underline">SharePoint Online e OneDrive for Business: limiti del software</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="eb0ca-247">È consigliabile limitare l'importo complessivo della migrazione al 75% della quota complessiva di SharePoint Online a cui si ha diritto (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="eb0ca-248">Dettagli ambiente di origine</span><span class="sxs-lookup"><span data-stu-id="eb0ca-248">Source environment details</span></span>

<span data-ttu-id="eb0ca-249">Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="eb0ca-250">Condivisioni di file (condivisioni di file di Server Message Block su dispositivi che supportano SMB 2.0 e versioni successive).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="eb0ca-251">Un singolo ambiente di G Suite (soltanto Google Drive).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="eb0ca-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="eb0ca-253">Dropbox per Team (Standard e Advanced).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="eb0ca-254">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="eb0ca-255"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="eb0ca-256"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="eb0ca-257"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="eb0ca-258"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="eb0ca-259"><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="eb0ca-260">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-261">Documenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-261">Documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-262">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="eb0ca-263">Autorizzazioni per file e cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="eb0ca-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="eb0ca-264">Autorizzazioni per file e cartelle a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="eb0ca-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="eb0ca-265">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="eb0ca-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="eb0ca-266">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="eb0ca-267">Data creazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-267">Created date</span></span> </li>
<li> <span data-ttu-id="eb0ca-268">Data modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-268">Modified date</span></span> </li>
<li> <span data-ttu-id="eb0ca-269">Creato da</span><span class="sxs-lookup"><span data-stu-id="eb0ca-269">Created by</span></span> </li>
<li> <span data-ttu-id="eb0ca-270">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="eb0ca-271">\*Configurazione della sincronizzazione della directory necessaria.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="eb0ca-272">Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="eb0ca-273">Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="eb0ca-274">Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-275">Cronologia di proprietà e versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="eb0ca-276">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="eb0ca-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="eb0ca-277">Versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="eb0ca-278">File di Windows e attributi di cartella (come Di sola lettura e Nascosto)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="eb0ca-279">Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):</span><span class="sxs-lookup"><span data-stu-id="eb0ca-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="eb0ca-280">Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="eb0ca-281">Configurazione di controllo NTFS</span><span class="sxs-lookup"><span data-stu-id="eb0ca-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="eb0ca-282">Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="eb0ca-283">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-284">Condivisioni nascoste</span><span class="sxs-lookup"><span data-stu-id="eb0ca-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="eb0ca-285">Condivisione (come autorizzazioni concesse a livello di condivisione)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="eb0ca-286">File o cartelle che superano i <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limiti e le restrizioni di SharePoint Online</span> correnti</a> </span><span class="sxs-lookup"><span data-stu-id="eb0ca-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="eb0ca-287"><strong>Ambiente G Suite singolo (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="eb0ca-288">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-289">Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente), anche quelli di oltre 10 MB</span><span class="sxs-lookup"><span data-stu-id="eb0ca-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="eb0ca-290">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="eb0ca-291">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-292">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-293">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="eb0ca-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="eb0ca-294">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="eb0ca-295">Data creazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-295">Created date</span></span> </li>
<li> <span data-ttu-id="eb0ca-296">Data modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-296">Modified date</span></span> </li>
<li> <span data-ttu-id="eb0ca-297">Creato da</span><span class="sxs-lookup"><span data-stu-id="eb0ca-297">Created by</span></span> </li>
<li> <span data-ttu-id="eb0ca-298">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="eb0ca-299">Unità condivise (cartelle e file)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="eb0ca-300">Contenuto condiviso appartenente all'account Google Drive in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-301">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="eb0ca-302">Descrizioni di file e cartelle, colori delle cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="eb0ca-303">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-304">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-305">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="eb0ca-306">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="eb0ca-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="eb0ca-307">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="eb0ca-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="eb0ca-308">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="eb0ca-309">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-310">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="eb0ca-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="eb0ca-311">Google Photos, Moduli, Maps e altre app connesse</span><span class="sxs-lookup"><span data-stu-id="eb0ca-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="eb0ca-312">Disegni Google</span><span class="sxs-lookup"><span data-stu-id="eb0ca-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="eb0ca-313">Contenuti condivisi esterni alla tua impresa</span><span class="sxs-lookup"><span data-stu-id="eb0ca-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="eb0ca-314">Contenuto che appartenente all'account Google Drive che è in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="eb0ca-315">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="eb0ca-316">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="eb0ca-317">Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="eb0ca-318">Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="eb0ca-319">File contrassegnati come limitati o non copiabili</span><span class="sxs-lookup"><span data-stu-id="eb0ca-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="eb0ca-320">File o cartelle che superano i <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limiti e le restrizioni di SharePoint Online</span> correnti</a> </span><span class="sxs-lookup"><span data-stu-id="eb0ca-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="eb0ca-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="eb0ca-322">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-323">Documenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-323">Documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-324">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="eb0ca-325">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-326">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-327">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="eb0ca-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="eb0ca-328">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="eb0ca-329">Data creazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-329">Created date</span></span> </li>
<li> <span data-ttu-id="eb0ca-330">Data modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-330">Modified date</span></span> </li>
<li> <span data-ttu-id="eb0ca-331">Creato da</span><span class="sxs-lookup"><span data-stu-id="eb0ca-331">Created by</span></span> </li>
<li> <span data-ttu-id="eb0ca-332">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="eb0ca-333">Contenuto condiviso appartenente all'account Box in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="eb0ca-334">Note di casella (convertite in formato documento di Word)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-335">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="eb0ca-336">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="eb0ca-337">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-338">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-339">Tag Box e metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="eb0ca-340">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="eb0ca-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="eb0ca-341">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="eb0ca-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="eb0ca-342">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="eb0ca-343">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-344">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="eb0ca-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="eb0ca-345">App Box, Segnalibri, Preferiti e Flussi di lavoro</span><span class="sxs-lookup"><span data-stu-id="eb0ca-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="eb0ca-346">Contenuto non di proprietà dell'account Box migrato</span><span class="sxs-lookup"><span data-stu-id="eb0ca-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="eb0ca-347">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="eb0ca-348">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="eb0ca-349">File o cartelle che superano i <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limiti e le restrizioni di SharePoint Online</span> correnti</a> </span><span class="sxs-lookup"><span data-stu-id="eb0ca-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="eb0ca-350"><strong>Dropbox per Team (Standard e Advanced)</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="eb0ca-351">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-352">Documenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-352">Documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-353">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="eb0ca-354">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-355">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-356">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="eb0ca-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="eb0ca-357">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="eb0ca-358">Data creazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-358">Created date</span></span> </li>
<li> <span data-ttu-id="eb0ca-359">Data modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-359">Modified date</span></span> </li>
<li> <span data-ttu-id="eb0ca-360">Creato da</span><span class="sxs-lookup"><span data-stu-id="eb0ca-360">Created by</span></span> </li>
<li> <span data-ttu-id="eb0ca-361">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="eb0ca-362">Contenuto e cartelle del team condiviso</span><span class="sxs-lookup"><span data-stu-id="eb0ca-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="eb0ca-363">Contenuto condiviso appartenente all'account Dropbox in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-364">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="eb0ca-365">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="eb0ca-366">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-367">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-368">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="eb0ca-369">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="eb0ca-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="eb0ca-370">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="eb0ca-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="eb0ca-371">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="eb0ca-372">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-373">Cartelle Dropbox non montate</span><span class="sxs-lookup"><span data-stu-id="eb0ca-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="eb0ca-374">Utenti eliminati o scollegati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="eb0ca-375">Dropbox Paper, Showcases, e Spaces</span><span class="sxs-lookup"><span data-stu-id="eb0ca-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="eb0ca-376">App e preferiti di Dropbox (Pins/stars)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="eb0ca-377">Contenuto non di proprietà dell'account Dropbox migrato</span><span class="sxs-lookup"><span data-stu-id="eb0ca-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="eb0ca-378">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="eb0ca-379">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="eb0ca-380">File o cartelle che superano i <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limiti e le restrizioni di SharePoint Online</span> correnti</a> </span><span class="sxs-lookup"><span data-stu-id="eb0ca-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="eb0ca-381">Responsabilità di FastTrack</span><span class="sxs-lookup"><span data-stu-id="eb0ca-381">FastTrack responsibilities</span></span>

<span data-ttu-id="eb0ca-382">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="eb0ca-383">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli</span><span class="sxs-lookup"><span data-stu-id="eb0ca-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="eb0ca-384">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-384">Your responsibilities</span></span>

<span data-ttu-id="eb0ca-385">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="eb0ca-386">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli</span><span class="sxs-lookup"><span data-stu-id="eb0ca-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="eb0ca-387">Tu esegui anche le attività seguenti, specifiche della migrazione di SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="eb0ca-388">Esecuzione del provisioning di tutti i siti del team di SharePoint per gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="eb0ca-389">Migrazione a OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="eb0ca-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="eb0ca-390">Se scegli di usare FastTrack per eseguire la migrazione dei tuoi file di OneDrive for Business, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="eb0ca-391">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e OneDrive for Business e usare a tuo vantaggio i nostri servizi di migrazione dati per i tuoi file.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="eb0ca-392">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-392">You create and schedule your migration events.</span></span> <span data-ttu-id="eb0ca-393">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="eb0ca-394">Al termine degli eventi di migrazione, è possibile che i file provenienti da fonti opportunamente programmate e idonee dei vostri ambienti di origine siano stati migrati a OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="eb0ca-395">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="eb0ca-395">Considerations</span></span>

  - <span data-ttu-id="eb0ca-396">Tutte le migrazioni sono soggette alle quote di OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="eb0ca-397">Per altre informazioni dettagliate, consulta [<span class="underline">SharePoint Online e OneDrive for Business: limiti del software</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="eb0ca-398">È consigliabile limitare la quantità totale dei dati migrati al 75% della quota di archiviazione globale di SharePoint Online a cui si è autorizzati (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="eb0ca-399">FastTrack esegue la migrazione solo alle unità attive di OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="eb0ca-400">Dettagli ambiente di origine</span><span class="sxs-lookup"><span data-stu-id="eb0ca-400">Source environment details</span></span>

<span data-ttu-id="eb0ca-401">Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="eb0ca-402">Condivisioni di file (condivisioni di file SMB su dispositivi che supportano SMB 2.0 e versioni successive).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="eb0ca-403">Ambiente G Suite singolo (solo Google Drive)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="eb0ca-404">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="eb0ca-405">Dropbox per Team (Standard e Advanced).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="eb0ca-406">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="eb0ca-407"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="eb0ca-408"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="eb0ca-409"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="eb0ca-410"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="eb0ca-411"><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="eb0ca-412">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-413">Documenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-413">Documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-414">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="eb0ca-415">Autorizzazioni per file e cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="eb0ca-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="eb0ca-416">Autorizzazioni per file e cartelle a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="eb0ca-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="eb0ca-417">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="eb0ca-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="eb0ca-418">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="eb0ca-419">Data creazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-419">Created date</span></span> </li>
<li> <span data-ttu-id="eb0ca-420">Data modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-420">Modified date</span></span> </li>
<li> <span data-ttu-id="eb0ca-421">Creato da</span><span class="sxs-lookup"><span data-stu-id="eb0ca-421">Created by</span></span> </li>
<li> <span data-ttu-id="eb0ca-422">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="eb0ca-423">\*Configurazione della sincronizzazione della directory necessaria.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="eb0ca-424">Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="eb0ca-425">Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="eb0ca-426">Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="eb0ca-427">Cronologia di proprietà e versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="eb0ca-428">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="eb0ca-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="eb0ca-429">Versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="eb0ca-430">File di Windows e attributi di cartella (come Di sola lettura e Nascosto)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="eb0ca-431">Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):</span><span class="sxs-lookup"><span data-stu-id="eb0ca-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="eb0ca-432">Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="eb0ca-433">Configurazione di controllo NTFS</span><span class="sxs-lookup"><span data-stu-id="eb0ca-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="eb0ca-434">Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="eb0ca-435">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-436">Condivisioni nascoste</span><span class="sxs-lookup"><span data-stu-id="eb0ca-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="eb0ca-437">Condivisione (come autorizzazioni concesse a livello di condivisione)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="eb0ca-438">File o cartelle che superano i <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limiti e le restrizioni di SharePoint Online</span> correnti</a> </span><span class="sxs-lookup"><span data-stu-id="eb0ca-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="eb0ca-439"><strong>Ambiente G Suite singolo (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="eb0ca-440">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-441">Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente, anche quelli di oltre 10 MB)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="eb0ca-442">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="eb0ca-443">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-444">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-445">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="eb0ca-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="eb0ca-446">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="eb0ca-447">Data creazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-447">Created date</span></span> </li>
<li> <span data-ttu-id="eb0ca-448">Data modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-448">Modified date</span></span> </li>
<li> <span data-ttu-id="eb0ca-449">Creato da</span><span class="sxs-lookup"><span data-stu-id="eb0ca-449">Created by</span></span> </li>
<li> <span data-ttu-id="eb0ca-450">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="eb0ca-451">Unità condivise (cartelle e file)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="eb0ca-452">Contenuto condiviso appartenente all'account Google Drive in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-453">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="eb0ca-454">Descrizioni di file e cartelle, colori delle cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="eb0ca-455">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-456">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-457">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="eb0ca-458">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="eb0ca-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="eb0ca-459">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="eb0ca-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="eb0ca-460">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="eb0ca-461">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-462">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="eb0ca-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="eb0ca-463">Google Photos, Moduli, Maps e altre app connesse</span><span class="sxs-lookup"><span data-stu-id="eb0ca-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="eb0ca-464">Disegni Google</span><span class="sxs-lookup"><span data-stu-id="eb0ca-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="eb0ca-465">Contenuti condivisi esterni alla tua impresa</span><span class="sxs-lookup"><span data-stu-id="eb0ca-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="eb0ca-466">Contenuto che appartenente all'account Google Drive che è in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="eb0ca-467">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="eb0ca-468">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="eb0ca-469">Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="eb0ca-470">Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="eb0ca-471">File o cartelle che superano i <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limiti e le restrizioni di SharePoint Online</span> correnti</a> </span><span class="sxs-lookup"><span data-stu-id="eb0ca-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="eb0ca-472"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="eb0ca-473">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-474">Documenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-474">Documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-475">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="eb0ca-476">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-477">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-478">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="eb0ca-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="eb0ca-479">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="eb0ca-480">Data creazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-480">Created date</span></span> </li>
<li> <span data-ttu-id="eb0ca-481">Data modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-481">Modified date</span></span> </li>
<li> <span data-ttu-id="eb0ca-482">Creato da</span><span class="sxs-lookup"><span data-stu-id="eb0ca-482">Created by</span></span> </li>
<li> <span data-ttu-id="eb0ca-483">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="eb0ca-484">Contenuto condiviso appartenente all'account Box in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-485">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="eb0ca-486">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="eb0ca-487">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-488">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-489">Tag Box e metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="eb0ca-490">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="eb0ca-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="eb0ca-491">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="eb0ca-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="eb0ca-492">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="eb0ca-493">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-494">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="eb0ca-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="eb0ca-495">App Box, Segnalibri, Preferiti e Flussi di lavoro</span><span class="sxs-lookup"><span data-stu-id="eb0ca-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="eb0ca-496">Contenuto non di proprietà dell'account Box migrato</span><span class="sxs-lookup"><span data-stu-id="eb0ca-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="eb0ca-497">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="eb0ca-498">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="eb0ca-499">File o cartelle che superano i <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limiti e le restrizioni di SharePoint Online</span> correnti</a> </span><span class="sxs-lookup"><span data-stu-id="eb0ca-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="eb0ca-500"><strong>Dropbox per Team (Standard e Advanced)</strong></span><span class="sxs-lookup"><span data-stu-id="eb0ca-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="eb0ca-501">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-502">Documenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-502">Documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-503">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="eb0ca-504">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-505">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-506">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="eb0ca-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="eb0ca-507">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="eb0ca-508">Data creazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-508">Created date</span></span> </li>
<li> <span data-ttu-id="eb0ca-509">Data modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-509">Modified date</span></span> </li>
<li> <span data-ttu-id="eb0ca-510">Creato da</span><span class="sxs-lookup"><span data-stu-id="eb0ca-510">Created by</span></span> </li>
<li> <span data-ttu-id="eb0ca-511">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="eb0ca-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="eb0ca-512">Contenuto e cartelle del team condiviso</span><span class="sxs-lookup"><span data-stu-id="eb0ca-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="eb0ca-513">Contenuto condiviso appartenente all'account Dropbox in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="eb0ca-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="eb0ca-514">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="eb0ca-515">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="eb0ca-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="eb0ca-516">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-517">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="eb0ca-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="eb0ca-518">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="eb0ca-519">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="eb0ca-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="eb0ca-520">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="eb0ca-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="eb0ca-521">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="eb0ca-522">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="eb0ca-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="eb0ca-523">Cartelle Dropbox non montate</span><span class="sxs-lookup"><span data-stu-id="eb0ca-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="eb0ca-524">Utenti eliminati o scollegati</span><span class="sxs-lookup"><span data-stu-id="eb0ca-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="eb0ca-525">Dropbox Paper, Showcases, e Spaces</span><span class="sxs-lookup"><span data-stu-id="eb0ca-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="eb0ca-526">App e preferiti di Dropbox (Pins/stars)</span><span class="sxs-lookup"><span data-stu-id="eb0ca-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="eb0ca-527">Contenuto non di proprietà dell'account Dropbox migrato</span><span class="sxs-lookup"><span data-stu-id="eb0ca-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="eb0ca-528">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="eb0ca-529">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="eb0ca-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="eb0ca-530">File o cartelle che superano i <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">limiti e le restrizioni di SharePoint Online</span> correnti</a> </span><span class="sxs-lookup"><span data-stu-id="eb0ca-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="eb0ca-531">Responsabilità di FastTrack</span><span class="sxs-lookup"><span data-stu-id="eb0ca-531">FastTrack responsibilities</span></span>

<span data-ttu-id="eb0ca-532">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="eb0ca-533">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="eb0ca-534">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="eb0ca-534">Your responsibilities</span></span>

<span data-ttu-id="eb0ca-535">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="eb0ca-536">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="eb0ca-537">Tu esegui anche le attività seguenti, specifiche della migrazione di OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="eb0ca-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="eb0ca-538">Esecuzione del provisioning di tutti i siti di OneDrive for Business che verranno assegnati agli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="eb0ca-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
