---
title: Migrazione dei dati
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack consente di eseguire la migrazione della posta elettronica e dei file negli ambienti di origine in Office 365 (Exchange Online, SharePoint Online e OneDrive for Business). Il tipo di assistenza che forniamo varia in base al numero di licenze di Office 365.
ms.openlocfilehash: 4fc2f5c1bf74de40109e7022ba7c333065f74d24
ms.sourcegitcommit: 736a256276ead91385e1ec37b8a120b22259c4ea
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/24/2021
ms.locfileid: "52626673"
---
# <a name="data-migration"></a><span data-ttu-id="9b455-104">Migrazione dei dati</span><span class="sxs-lookup"><span data-stu-id="9b455-104">Data Migration</span></span>

<span data-ttu-id="9b455-105">FastTrack consente di eseguire la migrazione della posta elettronica e dei file negli ambienti di origine in Office 365 (Exchange Online, SharePoint Online e OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="9b455-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="9b455-106">Il tipo di assistenza che forniamo varia in base al numero di licenze di Office 365:</span><span class="sxs-lookup"><span data-stu-id="9b455-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="9b455-107">**Per i tenant di Office 365 con 150-499 licenze**: FastTrack fornisce solo una guida alla migrazione. Tu sei il responsabile dell'esecuzione della migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="9b455-108">Ti guideremo attraverso la documentazione che ti aiuta a pianificare e usare strumenti gratuiti per eseguire una migrazione in modalità self-service.</span><span class="sxs-lookup"><span data-stu-id="9b455-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="9b455-109">**Per i tenant di Office 365 con 500 o più licenze**: FastTrack fornisce indicazioni di migrazione e servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="9b455-110">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e il tenant di Office 365 e usare a tuo vantaggio i nostri servizi di migrazione dei dati per la migrazione dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="9b455-111">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-111">You create and schedule your migration events.</span></span> <span data-ttu-id="9b455-112">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="9b455-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="9b455-113">Se hai acquistato o rinnovato un piano commerciale prima del 1/9/2017, sono necessarie solo 150 licenze per qualificarsi ai servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="9b455-114">Per i piani per il settore dell'istruzione, solo l'istituto di istruzione a pagamento e il personale sono idonei per i servizi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="9b455-115">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="9b455-115">Considerations</span></span>

  - <span data-ttu-id="9b455-116">Per eseguire la migrazione dei dati in Office 365, è necessario che gli ambienti di origine soddisfino aspettative specifiche.</span><span class="sxs-lookup"><span data-stu-id="9b455-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="9b455-117">Per altre informazioni sulle aspettative relative all’ambiente di origine di Exchange, SharePoint e OneDrive for Business, consulta [Prodotti e funzionalità ](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="9b455-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="9b455-118">Sono necessari l'accesso e le autorizzazioni appropriate agli ambienti di origine e al tenant di Office 365 per offrire servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="9b455-119">I servizi di migrazione dei dati non sono progettati né destinati per i dati soggetti a particolari requisiti normativi o legali.</span><span class="sxs-lookup"><span data-stu-id="9b455-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="9b455-120">Durante la migrazione dei dati, è possibile trasferire, archiviare ed elaborare i dati da qualsiasi luogo in cui vengono gestiti i servizi, ad eccezione di quanto specificato per il progetto di migrazione FastTrack.</span><span class="sxs-lookup"><span data-stu-id="9b455-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="9b455-121">Microsoft non garantisce la velocità di migrazione dei file o e-mail.</span><span class="sxs-lookup"><span data-stu-id="9b455-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="9b455-122">Problemi imprevisti (come elementi illeggibili o corrotti nell'ambiente di origine) possono impedire la capacità di migrazione di alcuni dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="9b455-123">Fattori esterni fuori controllo, come modifiche apportate alle interfacce API per le applicazioni di terze parti, possono comportare modifiche, ritardi o sospensioni dei servizi di migrazione dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="9b455-124">Disponibilità servizio migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-124">Migration service availability</span></span>

  - <span data-ttu-id="9b455-125">**Per clienti commerciali e del governo del Regno Unito:** Microsoft offre servizi di migrazione dei dati, 24 ore al giorno, sette (7) giorni alla settimana (24x7).</span><span class="sxs-lookup"><span data-stu-id="9b455-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="9b455-126">**Per i clienti del governo e del Dipartimento della difesa degli Stati Uniti:** Microsoft offre servizi di migrazione dei dati, 24 ore al giorno, cinque (5) giorni lavorativi alla settimana (24x5).</span><span class="sxs-lookup"><span data-stu-id="9b455-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="9b455-127">Migrazione a Exchange Online</span><span class="sxs-lookup"><span data-stu-id="9b455-127">Migration to Exchange Online</span></span>

<span data-ttu-id="9b455-128">Se scegli di usare FastTrack per eseguire la migrazione della posta elettronica a Exchange Online, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9b455-129">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e Exchange Online e usare a tuo vantaggio i nostri servizi di migrazione dati per le cassette postali.</span><span class="sxs-lookup"><span data-stu-id="9b455-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="9b455-130">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-130">You create and schedule your migration events.</span></span> <span data-ttu-id="9b455-131">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="9b455-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9b455-132">Al termine degli eventi di migrazione, è possibile che la posta proveniente dalle cassette postali di origine idonee e pianificate in modo appropriato degli ambienti di origine sia stata migrata a Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="9b455-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="9b455-133">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="9b455-133">Considerations</span></span>

  - <span data-ttu-id="9b455-134">Prima della migrazione, è necessario completare FastTrack Core onboarding per Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="9b455-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="9b455-135">Se hai già eseguito l’onboarding personalmente, è necessario superare i controlli e prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="9b455-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="9b455-136">Per informazioni dettagliate, visita [Prodotti e funzionalità](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="9b455-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="9b455-137">FastTrack migra soltanto verso cassette postali di Office 365 attive.</span><span class="sxs-lookup"><span data-stu-id="9b455-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="9b455-138">È necessario soddisfare requisiti specifici se intendi migrare da un ambiente Exchange locale.</span><span class="sxs-lookup"><span data-stu-id="9b455-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="9b455-139">Per informazioni dettagliate, visita [Prerequisiti di distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="9b455-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="9b455-140">Ogni ambiente di origine deve essere al livello di aggiornamento del Service Pack (SP) e del rollup (RU)/aggiornamento cumulativo (CU) per il rispettivo prodotto nell'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="9b455-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="9b455-141">Le liste di distribuzione (oggetti *MailEnabledGroup*) e i contatti esterni (oggetti *MailEnabledContact*) che si trovano in Active Directory locale non fanno parte della migrazione dei dati delle cassette postali.</span><span class="sxs-lookup"><span data-stu-id="9b455-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="9b455-142">È possibile tuttavia sincronizzarli con Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="9b455-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="9b455-143">Ambienti di origine</span><span class="sxs-lookup"><span data-stu-id="9b455-143">Source environments</span></span>

<span data-ttu-id="9b455-144">Il servizio di migrazione dei dati esegue la migrazione dei dati dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="9b455-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="9b455-145">Una o più insiemi di strutture di Active Directory con una o multiple organizzazioni di Exchange (ogni sistema di posta di Exchange deve essere Exchange 2010 o versione successiva).</span><span class="sxs-lookup"><span data-stu-id="9b455-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="9b455-146">Un ambiente di posta elettronica con funzionalità IMAP singola.</span><span class="sxs-lookup"><span data-stu-id="9b455-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="9b455-147">Ambiente G Suite (solo Gmail, Contatti e Calendario)</span><span class="sxs-lookup"><span data-stu-id="9b455-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="9b455-148">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="9b455-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9b455-149"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="9b455-150"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="9b455-151"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="9b455-152"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9b455-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016 o Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="9b455-154">
<strong>Nota:</strong> Per le dipendenze Exchange locali, vedere <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Prerequisiti per la distribuzione ibrida.</span></a></span><span class="sxs-lookup"><span data-stu-id="9b455-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="9b455-155">Migrazione con distribuzione ibrida</span><span class="sxs-lookup"><span data-stu-id="9b455-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="9b455-156">Messaggi di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="9b455-156">Emails</span></span></li>
<li><span data-ttu-id="9b455-157">Regole delle cassette postali sul lato server</span><span class="sxs-lookup"><span data-stu-id="9b455-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="9b455-158">Delegati</span><span class="sxs-lookup"><span data-stu-id="9b455-158">Delegates</span></span></li>
<li><span data-ttu-id="9b455-159">Contatti della cassetta postale</span><span class="sxs-lookup"><span data-stu-id="9b455-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="9b455-160">Calendario</span><span class="sxs-lookup"><span data-stu-id="9b455-160">Calendar</span></span> </li>
<li> <span data-ttu-id="9b455-161">Attività</span><span class="sxs-lookup"><span data-stu-id="9b455-161">Tasks</span></span> </li>
<li> <span data-ttu-id="9b455-162">Messaggi di posta elettronica con contenuto protetto da Microsoft Rights Management</span><span class="sxs-lookup"><span data-stu-id="9b455-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="9b455-163">Messaggi di posta elettronica crittografati</span><span class="sxs-lookup"><span data-stu-id="9b455-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="9b455-164">Firme</span><span class="sxs-lookup"><span data-stu-id="9b455-164">Signatures</span></span> </li>
<li> <span data-ttu-id="9b455-165">Archivio personale migrato con la cassetta postale dell'utente</span><span class="sxs-lookup"><span data-stu-id="9b455-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="9b455-166">Elementi ripristinabili</span><span class="sxs-lookup"><span data-stu-id="9b455-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9b455-167">Cartelle pubbliche</span><span class="sxs-lookup"><span data-stu-id="9b455-167">Public folders</span></span> </li>
<li> <span data-ttu-id="9b455-168">Tutti i messaggi di posta elettronica che superano il limite relativo alla dimensione</span><span class="sxs-lookup"><span data-stu-id="9b455-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="9b455-169">Archivio di inserimento nel journal oppure tutte le altre soluzioni di archiviazione di terze parti</span><span class="sxs-lookup"><span data-stu-id="9b455-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="9b455-170">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="9b455-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9b455-171">Archiviazione dati da file PST (Personal Storage Table)</span><span class="sxs-lookup"><span data-stu-id="9b455-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="9b455-172">Elementi danneggiati</span><span class="sxs-lookup"><span data-stu-id="9b455-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="9b455-173">Cassette postali inattive</span><span class="sxs-lookup"><span data-stu-id="9b455-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="9b455-174">Regole delle cassette postali sul lato client</span><span class="sxs-lookup"><span data-stu-id="9b455-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9b455-175"><strong>Ambiente G Suite (solo Gmail, Contatti e Calendario)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="9b455-176">
<strong>Nota:</strong> L'ambiente G Suite deve soddisfare i prerequisiti descritti in <a href="/exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration.</a></span><span class="sxs-lookup"><span data-stu-id="9b455-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="/exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="9b455-177">Completa o a fasi</span><span class="sxs-lookup"><span data-stu-id="9b455-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-178">Messaggi di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="9b455-178">Emails</span></span> </li>
<li> <span data-ttu-id="9b455-179">Contatti di cassette postali (al massimo tre indirizzi di posta elettronica per ogni contatto)</span><span class="sxs-lookup"><span data-stu-id="9b455-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="9b455-180">Calendario</span><span class="sxs-lookup"><span data-stu-id="9b455-180">Calendar</span></span> </li>
<li> <span data-ttu-id="9b455-181">Etichette</span><span class="sxs-lookup"><span data-stu-id="9b455-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9b455-182">regole</span><span class="sxs-lookup"><span data-stu-id="9b455-182">Rules</span></span> </li>
<li> <span data-ttu-id="9b455-183">Delegati</span><span class="sxs-lookup"><span data-stu-id="9b455-183">Delegates</span></span> </li>
<li> <span data-ttu-id="9b455-184">Firme</span><span class="sxs-lookup"><span data-stu-id="9b455-184">Signatures</span></span> </li>
<li> <span data-ttu-id="9b455-185">Attività</span><span class="sxs-lookup"><span data-stu-id="9b455-185">Tasks</span></span> </li>
<li> <span data-ttu-id="9b455-186">Tutti i messaggi di posta elettronica o allegati che superano il limite relativo alla dimensione</span><span class="sxs-lookup"><span data-stu-id="9b455-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="9b455-187">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="9b455-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9b455-188">Archiviazione dati da file PST o da una soluzione di archiviazione di terze parti (ad esempio, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="9b455-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="9b455-189">Messaggi di posta elettronica crittografati o con contenuto protetto</span><span class="sxs-lookup"><span data-stu-id="9b455-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="9b455-190">Elementi danneggiati</span><span class="sxs-lookup"><span data-stu-id="9b455-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="9b455-191">Hangouts di Google\*\*</span><span class="sxs-lookup"><span data-stu-id="9b455-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="9b455-192">Gruppi di Google</span><span class="sxs-lookup"><span data-stu-id="9b455-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="9b455-193">Cassette postali per la risorsa</span><span class="sxs-lookup"><span data-stu-id="9b455-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="9b455-194">Cassette postali inattive</span><span class="sxs-lookup"><span data-stu-id="9b455-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="9b455-195">Impostazioni delle ferie e impostazioni di risposta automatica</span><span class="sxs-lookup"><span data-stu-id="9b455-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="9b455-196">Calendari condivisi, allegati cloud, collegamenti di Google Hangout e colori per gli eventi</span><span class="sxs-lookup"><span data-stu-id="9b455-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="9b455-197">\*\*È stata eseguita la migrazioni di conversazioni di Hangout salvate come etichetta.</span><span class="sxs-lookup"><span data-stu-id="9b455-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9b455-198"><strong>Origine IMAP4 (come Domino, GroupWise o Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="9b455-199">Migrazione tramite strumenti nativi di IMAP4</span><span class="sxs-lookup"><span data-stu-id="9b455-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="9b455-200">Messaggi di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="9b455-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="9b455-201">Regole</span><span class="sxs-lookup"><span data-stu-id="9b455-201">Rules</span></span> </li>
<li> <span data-ttu-id="9b455-202">Delegati</span><span class="sxs-lookup"><span data-stu-id="9b455-202">Delegates</span></span> </li>
<li> <span data-ttu-id="9b455-203">Liste di distribuzione</span><span class="sxs-lookup"><span data-stu-id="9b455-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="9b455-204">Contatti esterni</span><span class="sxs-lookup"><span data-stu-id="9b455-204">External contacts</span></span> </li>
<li> <span data-ttu-id="9b455-205">Utenti abilitati all'utilizzo della posta</span><span class="sxs-lookup"><span data-stu-id="9b455-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="9b455-206">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="9b455-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9b455-207">Contatti della cassetta postale</span><span class="sxs-lookup"><span data-stu-id="9b455-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="9b455-208">Calendario</span><span class="sxs-lookup"><span data-stu-id="9b455-208">Calendar</span></span> </li>
<li> <span data-ttu-id="9b455-209">Firme</span><span class="sxs-lookup"><span data-stu-id="9b455-209">Signatures</span></span> </li>
<li> <span data-ttu-id="9b455-210">Attività</span><span class="sxs-lookup"><span data-stu-id="9b455-210">Tasks</span></span> </li>
<li> <span data-ttu-id="9b455-211">Tutte le e-mail che superano il limite per la dimensione del messaggio</span><span class="sxs-lookup"><span data-stu-id="9b455-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="9b455-212">Archiviazione dati</span><span class="sxs-lookup"><span data-stu-id="9b455-212">Archive data</span></span> </li>
<li> <span data-ttu-id="9b455-213">Messaggi di posta elettronica crittografati</span><span class="sxs-lookup"><span data-stu-id="9b455-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="9b455-214">Elementi danneggiati</span><span class="sxs-lookup"><span data-stu-id="9b455-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="9b455-215">Cassette postali inattive</span><span class="sxs-lookup"><span data-stu-id="9b455-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="9b455-216">Responsabilità di FastTrack per Exchange Online migrazioni</span><span class="sxs-lookup"><span data-stu-id="9b455-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="9b455-217">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9b455-218">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="9b455-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="9b455-219">Gli specialisti di FastTrack eseguono anche le attività seguenti, specifiche della migrazione di Exchange:</span><span class="sxs-lookup"><span data-stu-id="9b455-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="9b455-220">Forniscono indicazioni utili per abilitare la coesistenza di routing della posta SMTP tra gli ambienti di origine e Exchange Online, se applicabile.</span><span class="sxs-lookup"><span data-stu-id="9b455-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="9b455-221">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="9b455-221">Your responsibilities</span></span>

<span data-ttu-id="9b455-222">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9b455-223">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="9b455-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="9b455-224">Tu esegui anche le attività seguenti, specifiche della migrazione di Exchange:</span><span class="sxs-lookup"><span data-stu-id="9b455-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="9b455-225">Completamento FastTrack Core onboarding per Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="9b455-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="9b455-226">Se hai già eseguito l’onboarding personalmente, è necessario superare i controlli e prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="9b455-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="9b455-227">Per informazioni dettagliate, visita [Prodotti e funzionalità](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="9b455-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="9b455-228">Installazione del livello appropriato di software client in base alle linee guida di Office 365.</span><span class="sxs-lookup"><span data-stu-id="9b455-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="9b455-229">Per informazioni dettagliate, vedere [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="9b455-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="9b455-230">Soddisfare i requisiti specifici se intendi migrare da un ambiente Exchange locale.</span><span class="sxs-lookup"><span data-stu-id="9b455-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="9b455-231">Per informazioni dettagliate, visita [Prerequisiti di distribuzione ibrida](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="9b455-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="9b455-232">Assicurati che ogni ambiente di origine si trovi al livello di aggiornamento del Service Pack (SP) e del rollup (RU)/aggiornamento cumulativo (CU), se applicabile.</span><span class="sxs-lookup"><span data-stu-id="9b455-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="9b455-233">Configura e convalida la coesistenza di routing della posta SMTP tra gli ambienti di origine e Exchange Online, se applicabile.</span><span class="sxs-lookup"><span data-stu-id="9b455-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="9b455-234">Verifica che le dimensioni della cassetta postale di origine non superino la quota di destinazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="9b455-235">A seconda della piattaforma di origine, potrebbe essere necessario limitare i dati di origine all’85% della quota delle cassette postali di destinazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="9b455-236">Puoi migrare i dati dal lato client.</span><span class="sxs-lookup"><span data-stu-id="9b455-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="9b455-237">Tale migrazione include, ad esempio, le rubriche locali, i dati dei file PST locali, le regole di Outlook e le impostazioni di Outlook locale.</span><span class="sxs-lookup"><span data-stu-id="9b455-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="9b455-238">Aiutare gli utenti finali a correggere i problemi di migrazione sul lato client.</span><span class="sxs-lookup"><span data-stu-id="9b455-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="9b455-239">Migrazione a SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="9b455-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="9b455-240">Se scegli di usare FastTrack per eseguire la migrazione dei tuoi file di SharePoint Online, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9b455-241">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e SharePoint Online e usare a tuo vantaggio i nostri servizi di migrazione dati per i tuoi file.</span><span class="sxs-lookup"><span data-stu-id="9b455-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="9b455-242">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-242">You create and schedule your migration events.</span></span> <span data-ttu-id="9b455-243">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="9b455-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9b455-244">Al termine degli eventi di migrazione, è possibile che i file provenienti da fonti opportunamente programmate e idonee dei vostri ambienti di origine siano stati migrati a SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="9b455-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="9b455-245">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="9b455-245">Considerations</span></span>

 - <span data-ttu-id="9b455-246">Tutte le migrazioni sono soggette a quote di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="9b455-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="9b455-247">Per informazioni <a href="https://go.microsoft.com/fwlink/?LinkId=698855">dettagliate, SharePoint limiti</a> di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="9b455-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="9b455-248">È consigliabile limitare l'importo complessivo della migrazione al 75% della quota complessiva di SharePoint Online a cui si ha diritto (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente).</span><span class="sxs-lookup"><span data-stu-id="9b455-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="9b455-249">Dettagli ambiente di origine</span><span class="sxs-lookup"><span data-stu-id="9b455-249">Source environment details</span></span>

<span data-ttu-id="9b455-250">Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="9b455-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="9b455-251">Condivisioni di file (condivisioni di file di Server Message Block su dispositivi che supportano SMB 2.0 e versioni successive).</span><span class="sxs-lookup"><span data-stu-id="9b455-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="9b455-252">Un singolo ambiente di G Suite (soltanto Google Drive).</span><span class="sxs-lookup"><span data-stu-id="9b455-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="9b455-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="9b455-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="9b455-254">Dropbox per Team (Standard e Advanced).</span><span class="sxs-lookup"><span data-stu-id="9b455-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="9b455-255">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="9b455-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9b455-256"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="9b455-257"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="9b455-258"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="9b455-259"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9b455-260"><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="9b455-261">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-262">Documenti</span><span class="sxs-lookup"><span data-stu-id="9b455-262">Documents</span></span> </li>
<li> <span data-ttu-id="9b455-263">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-264">Autorizzazioni per file e cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="9b455-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-265">Autorizzazioni per file e cartelle a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="9b455-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-266">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-267">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-268">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-268">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-269">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-269">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-270">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-270">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-271">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="9b455-272">\*Configurazione della sincronizzazione della directory necessaria.</span><span class="sxs-lookup"><span data-stu-id="9b455-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="9b455-273">Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows.</span><span class="sxs-lookup"><span data-stu-id="9b455-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="9b455-274">Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate.</span><span class="sxs-lookup"><span data-stu-id="9b455-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="9b455-275">Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.</span><span class="sxs-lookup"><span data-stu-id="9b455-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-276">Cronologia di proprietà e versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="9b455-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="9b455-277">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-278">Versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="9b455-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="9b455-279">File di Windows e attributi di cartella (come Di sola lettura e Nascosto)</span><span class="sxs-lookup"><span data-stu-id="9b455-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="9b455-280">Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):</span><span class="sxs-lookup"><span data-stu-id="9b455-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="9b455-281">Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)</span><span class="sxs-lookup"><span data-stu-id="9b455-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="9b455-282">Configurazione di controllo NTFS</span><span class="sxs-lookup"><span data-stu-id="9b455-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="9b455-283">Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)</span><span class="sxs-lookup"><span data-stu-id="9b455-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="9b455-284">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-285">Condivisioni nascoste</span><span class="sxs-lookup"><span data-stu-id="9b455-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="9b455-286">Condivisione (come autorizzazioni concesse a livello di condivisione)</span><span class="sxs-lookup"><span data-stu-id="9b455-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="9b455-287">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9b455-288"><strong>Ambiente G Suite singolo (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="9b455-289">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-290">Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente), anche quelli di oltre 10 MB</span><span class="sxs-lookup"><span data-stu-id="9b455-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="9b455-291">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-292">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-293">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-294">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-295">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-296">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-296">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-297">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-297">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-298">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-298">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-299">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9b455-300">Unità condivise (cartelle e file)</span><span class="sxs-lookup"><span data-stu-id="9b455-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="9b455-301">Contenuto condiviso appartenente all'account Google Drive in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9b455-302">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="9b455-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9b455-303">Descrizioni di file e cartelle, colori delle cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="9b455-304">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-305">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-306">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="9b455-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9b455-307">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="9b455-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9b455-308">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-309">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="9b455-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="9b455-310">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-311">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="9b455-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9b455-312">Google Photos, Moduli, Maps e altre app connesse</span><span class="sxs-lookup"><span data-stu-id="9b455-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="9b455-313">Disegni Google</span><span class="sxs-lookup"><span data-stu-id="9b455-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="9b455-314">Contenuti condivisi esterni alla tua impresa</span><span class="sxs-lookup"><span data-stu-id="9b455-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="9b455-315">Contenuto che appartenente all'account Google Drive che è in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="9b455-316">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9b455-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="9b455-317">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-318">Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise.</span><span class="sxs-lookup"><span data-stu-id="9b455-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="9b455-319">Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-320">File contrassegnati come limitati o non copiabili</span><span class="sxs-lookup"><span data-stu-id="9b455-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="9b455-321">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9b455-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="9b455-323">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-324">Documenti</span><span class="sxs-lookup"><span data-stu-id="9b455-324">Documents</span></span> </li>
<li> <span data-ttu-id="9b455-325">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-326">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-327">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-328">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-329">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-330">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-330">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-331">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-331">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-332">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-332">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-333">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9b455-334">Contenuto condiviso appartenente all'account Box in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="9b455-335">Note casella (convertite in formato documento Word)</span><span class="sxs-lookup"><span data-stu-id="9b455-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9b455-336">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="9b455-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9b455-337">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9b455-338">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-339">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-340">Tag Box e metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="9b455-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="9b455-341">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="9b455-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9b455-342">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-343">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="9b455-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="9b455-344">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-345">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="9b455-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9b455-346">App Box, Segnalibri, Preferiti e Flussi di lavoro</span><span class="sxs-lookup"><span data-stu-id="9b455-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="9b455-347">Contenuto non di proprietà dell'account Box migrato</span><span class="sxs-lookup"><span data-stu-id="9b455-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="9b455-348">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9b455-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="9b455-349">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-350">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9b455-351"><strong>Dropbox per Team (Standard e Advanced)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="9b455-352">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-353">Documenti</span><span class="sxs-lookup"><span data-stu-id="9b455-353">Documents</span></span> </li>
<li> <span data-ttu-id="9b455-354">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-355">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-356">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-357">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-358">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-359">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-359">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-360">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-360">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-361">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-361">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-362">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9b455-363">Contenuto e cartelle del team condiviso</span><span class="sxs-lookup"><span data-stu-id="9b455-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="9b455-364">Contenuto condiviso appartenente all'account Dropbox in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9b455-365">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="9b455-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9b455-366">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9b455-367">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-368">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-369">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="9b455-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9b455-370">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="9b455-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9b455-371">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-372">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="9b455-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="9b455-373">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-374">Cartelle Dropbox non montate</span><span class="sxs-lookup"><span data-stu-id="9b455-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="9b455-375">Utenti eliminati o scollegati</span><span class="sxs-lookup"><span data-stu-id="9b455-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="9b455-376">Dropbox Paper, Showcases, e Spaces</span><span class="sxs-lookup"><span data-stu-id="9b455-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="9b455-377">App e preferiti di Dropbox (Pins/stars)</span><span class="sxs-lookup"><span data-stu-id="9b455-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="9b455-378">Contenuto non di proprietà dell'account Dropbox migrato</span><span class="sxs-lookup"><span data-stu-id="9b455-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="9b455-379">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9b455-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="9b455-380">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione)</span><span class="sxs-lookup"><span data-stu-id="9b455-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="9b455-381">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="9b455-382">Responsabilità di FastTrack per le migrazioni SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="9b455-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="9b455-383">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9b455-384">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli</span><span class="sxs-lookup"><span data-stu-id="9b455-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="9b455-385">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="9b455-385">Your responsibilities</span></span>

<span data-ttu-id="9b455-386">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9b455-387">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli</span><span class="sxs-lookup"><span data-stu-id="9b455-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="9b455-388">Tu esegui anche le attività seguenti, specifiche della migrazione di SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="9b455-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="9b455-389">Esecuzione del provisioning di tutti i siti del team di SharePoint per gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="9b455-390">Migrazione a OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="9b455-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="9b455-391">Se scegli di usare FastTrack per eseguire la migrazione dei tuoi file di OneDrive for Business, Microsoft fornisce linee guida sulla migrazione e sui servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9b455-392">Forniamo una guida per aiutarti a pianificare la migrazione, configurare gli ambienti di origine e OneDrive for Business e usare a tuo vantaggio i nostri servizi di migrazione dati per i tuoi file.</span><span class="sxs-lookup"><span data-stu-id="9b455-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="9b455-393">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-393">You create and schedule your migration events.</span></span> <span data-ttu-id="9b455-394">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="9b455-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9b455-395">Al termine degli eventi di migrazione, è possibile che i file provenienti da fonti opportunamente programmate e idonee dei vostri ambienti di origine siano stati migrati a OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="9b455-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="9b455-396">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="9b455-396">Considerations</span></span>

  - <span data-ttu-id="9b455-397">Tutte le migrazioni sono soggette a quote di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="9b455-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="9b455-398">Per informazioni <a href="https://go.microsoft.com/fwlink/?LinkId=698855">dettagliate, SharePoint limiti</a> di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="9b455-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="9b455-399">È consigliabile limitare la quantità totale dei dati migrati al 75% della quota di archiviazione globale di SharePoint Online a cui si è autorizzati (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente).</span><span class="sxs-lookup"><span data-stu-id="9b455-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="9b455-400">FastTrack esegue la migrazione solo alle unità attive di OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="9b455-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="9b455-401">Dettagli ambiente di origine</span><span class="sxs-lookup"><span data-stu-id="9b455-401">Source environment details</span></span>

<span data-ttu-id="9b455-402">Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="9b455-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="9b455-403">Condivisioni di file (condivisioni di file SMB su dispositivi che supportano SMB 2.0 e versioni successive).</span><span class="sxs-lookup"><span data-stu-id="9b455-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="9b455-404">Ambiente G Suite singolo (solo Google Drive)</span><span class="sxs-lookup"><span data-stu-id="9b455-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="9b455-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="9b455-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="9b455-406">Dropbox per Team (Standard e Advanced).</span><span class="sxs-lookup"><span data-stu-id="9b455-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="9b455-407">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="9b455-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="9b455-408"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="9b455-409"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="9b455-410"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="9b455-411"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9b455-412"><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="9b455-413">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-414">Documenti</span><span class="sxs-lookup"><span data-stu-id="9b455-414">Documents</span></span> </li>
<li> <span data-ttu-id="9b455-415">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-416">Autorizzazioni per file e cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="9b455-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-417">Autorizzazioni per file e cartelle a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="9b455-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-418">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-419">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-420">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-420">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-421">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-421">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-422">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-422">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-423">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="9b455-424">\*Configurazione della sincronizzazione della directory necessaria.</span><span class="sxs-lookup"><span data-stu-id="9b455-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="9b455-425">Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows.</span><span class="sxs-lookup"><span data-stu-id="9b455-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="9b455-426">Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate.</span><span class="sxs-lookup"><span data-stu-id="9b455-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="9b455-427">Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.</span><span class="sxs-lookup"><span data-stu-id="9b455-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="9b455-428">Cronologia di proprietà e versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="9b455-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="9b455-429">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-430">Versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="9b455-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="9b455-431">File di Windows e attributi di cartella (come Di sola lettura e Nascosto)</span><span class="sxs-lookup"><span data-stu-id="9b455-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="9b455-432">Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):</span><span class="sxs-lookup"><span data-stu-id="9b455-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="9b455-433">Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)</span><span class="sxs-lookup"><span data-stu-id="9b455-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="9b455-434">Configurazione di controllo NTFS</span><span class="sxs-lookup"><span data-stu-id="9b455-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="9b455-435">Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)</span><span class="sxs-lookup"><span data-stu-id="9b455-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="9b455-436">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-437">Condivisioni nascoste</span><span class="sxs-lookup"><span data-stu-id="9b455-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="9b455-438">Condivisione (come autorizzazioni concesse a livello di condivisione)</span><span class="sxs-lookup"><span data-stu-id="9b455-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="9b455-439">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9b455-440"><strong>Ambiente G Suite singolo (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="9b455-441">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-442">Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente, anche quelli di oltre 10 MB)</span><span class="sxs-lookup"><span data-stu-id="9b455-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="9b455-443">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-444">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-445">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-446">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-447">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-448">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-448">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-449">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-449">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-450">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-450">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-451">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9b455-452">Unità condivise (cartelle e file)</span><span class="sxs-lookup"><span data-stu-id="9b455-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="9b455-453">Contenuto condiviso appartenente all'account Google Drive in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9b455-454">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="9b455-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9b455-455">Descrizioni di file e cartelle, colori delle cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="9b455-456">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-457">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-458">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="9b455-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9b455-459">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="9b455-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9b455-460">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-461">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="9b455-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="9b455-462">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-463">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="9b455-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9b455-464">Google Photos, Moduli, Maps e altre app connesse</span><span class="sxs-lookup"><span data-stu-id="9b455-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="9b455-465">Disegni Google</span><span class="sxs-lookup"><span data-stu-id="9b455-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="9b455-466">Contenuti condivisi esterni alla tua impresa</span><span class="sxs-lookup"><span data-stu-id="9b455-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="9b455-467">Contenuto che appartenente all'account Google Drive che è in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="9b455-468">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9b455-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="9b455-469">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-470">Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise.</span><span class="sxs-lookup"><span data-stu-id="9b455-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="9b455-471">Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-472">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9b455-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="9b455-474">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-475">Documenti</span><span class="sxs-lookup"><span data-stu-id="9b455-475">Documents</span></span> </li>
<li> <span data-ttu-id="9b455-476">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-477">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-478">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-479">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-480">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-481">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-481">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-482">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-482">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-483">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-483">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-484">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9b455-485">Contenuto condiviso appartenente all'account Box in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9b455-486">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="9b455-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9b455-487">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9b455-488">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-489">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-490">Tag Box e metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="9b455-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="9b455-491">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="9b455-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9b455-492">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-493">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="9b455-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="9b455-494">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-495">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="9b455-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9b455-496">App Box, Segnalibri, Preferiti e Flussi di lavoro</span><span class="sxs-lookup"><span data-stu-id="9b455-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="9b455-497">Contenuto non di proprietà dell'account Box migrato</span><span class="sxs-lookup"><span data-stu-id="9b455-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="9b455-498">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9b455-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="9b455-499">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-500">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9b455-501"><strong>Dropbox per Team (Standard e Advanced)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="9b455-502">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-503">Documenti</span><span class="sxs-lookup"><span data-stu-id="9b455-503">Documents</span></span> </li>
<li> <span data-ttu-id="9b455-504">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-505">Autorizzazioni per cartelle a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-506">Autorizzazioni per cartelle a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9b455-507">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-508">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-509">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-509">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-510">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-510">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-511">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-511">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-512">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9b455-513">Contenuto e cartelle del team condiviso</span><span class="sxs-lookup"><span data-stu-id="9b455-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="9b455-514">Contenuto condiviso appartenente all'account Dropbox in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9b455-515">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="9b455-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9b455-516">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9b455-517">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-518">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-519">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="9b455-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9b455-520">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="9b455-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9b455-521">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-522">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="9b455-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="9b455-523">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-524">Cartelle Dropbox non montate</span><span class="sxs-lookup"><span data-stu-id="9b455-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="9b455-525">Utenti eliminati o scollegati</span><span class="sxs-lookup"><span data-stu-id="9b455-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="9b455-526">Dropbox Paper, Showcases, e Spaces</span><span class="sxs-lookup"><span data-stu-id="9b455-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="9b455-527">App e preferiti di Dropbox (Pins/stars)</span><span class="sxs-lookup"><span data-stu-id="9b455-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="9b455-528">Contenuto non di proprietà dell'account Dropbox migrato</span><span class="sxs-lookup"><span data-stu-id="9b455-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="9b455-529">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9b455-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="9b455-530">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-531">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="9b455-532">Responsabilità di FastTrack per OneDrive for Business migrazioni</span><span class="sxs-lookup"><span data-stu-id="9b455-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="9b455-533">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9b455-534">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="9b455-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="9b455-535">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="9b455-535">Your responsibilities</span></span>

<span data-ttu-id="9b455-536">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9b455-537">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="9b455-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="9b455-538">Tu esegui anche le attività seguenti, specifiche della migrazione di OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="9b455-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="9b455-539">Esecuzione del provisioning di tutti i siti di OneDrive for Business che verranno assegnati agli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="9b455-540">Migrazione a Microsoft Teams e Microsoft 365 gruppi</span><span class="sxs-lookup"><span data-stu-id="9b455-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="9b455-541">Quando si sceglie di usare FastTrack per eseguire la migrazione dei file a Microsoft Teams e Microsoft 365, vengono fornite indicazioni sulla migrazione e servizi di migrazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="9b455-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9b455-542">Vengono fornite indicazioni per pianificare la migrazione, configurare gli ambienti di origine e i gruppi Teams e Microsoft 365 e sfruttare i servizi di migrazione dei dati per eseguire la migrazione dei file.</span><span class="sxs-lookup"><span data-stu-id="9b455-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="9b455-543">Crea e pianifica gli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-543">You create and schedule your migration events.</span></span> <span data-ttu-id="9b455-544">Avviamo gli eventi di migrazione in base alla programmazione, monitorando lo stato di avanzamento e fornendo relazioni sullo stato.</span><span class="sxs-lookup"><span data-stu-id="9b455-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9b455-545">Una volta completati gli eventi di migrazione, è possibile prevedere la migrazione dei file delle origini pianificate e idonee degli ambienti di origine in Teams e Microsoft 365 gruppi.</span><span class="sxs-lookup"><span data-stu-id="9b455-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="9b455-546">Teams e i Microsoft 365 devono essere pre-provisioning dal cliente prima di poter eseguire la migrazione dei dati in questi tipi di destinazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="9b455-547">Teams e Microsoft 365 gruppi influiscono sulle autorizzazioni sul percorso di destinazione del file.</span><span class="sxs-lookup"><span data-stu-id="9b455-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="9b455-548">Teams e Microsoft 365 sono creati per consentire la collaborazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="9b455-549">Il Teams o il Microsoft 365 determinano chi ha accesso a tali file durante la migrazione in tali destinazioni.</span><span class="sxs-lookup"><span data-stu-id="9b455-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="9b455-550">FastTrack non aggiunge utenti finali o gruppi ad alcun canale Teams o Microsoft 365 gruppi durante la migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="9b455-551">Considerazioni</span><span class="sxs-lookup"><span data-stu-id="9b455-551">Considerations</span></span>

- <span data-ttu-id="9b455-552">Tutte le migrazioni sono soggette a quote di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="9b455-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="9b455-553">Per informazioni <a href="https://go.microsoft.com/fwlink/?LinkId=698855">dettagliate, SharePoint limiti</a> di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="9b455-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="9b455-554">È consigliabile limitare l'importo complessivo della migrazione al 75% della quota complessiva di SharePoint Online a cui si ha diritto (incluso lo spazio di archiviazione aggiuntivo acquistato separatamente).</span><span class="sxs-lookup"><span data-stu-id="9b455-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="9b455-555">Dettagli ambiente di origine</span><span class="sxs-lookup"><span data-stu-id="9b455-555">Source environment details</span></span>

<span data-ttu-id="9b455-556">Il servizio di migrazione dei dati esegue la migrazione dai seguenti ambienti di origine:</span><span class="sxs-lookup"><span data-stu-id="9b455-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="9b455-557">Condivisioni di file (condivisioni di file di Server Message Block su dispositivi che supportano SMB 2.0 e versioni successive).</span><span class="sxs-lookup"><span data-stu-id="9b455-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="9b455-558">Un singolo ambiente di G Suite (soltanto Google Drive).</span><span class="sxs-lookup"><span data-stu-id="9b455-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="9b455-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="9b455-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="9b455-560">Dropbox per Team (Standard e Advanced).</span><span class="sxs-lookup"><span data-stu-id="9b455-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="9b455-561">Nella tabella seguente vengono illustrati i dettagli della migrazione specifici per ogni ambiente di origine:</span><span class="sxs-lookup"><span data-stu-id="9b455-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="9b455-562"><strong>Ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="9b455-563"><strong>Tipo di migrazione</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="9b455-564"><strong>Cosa migra</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="9b455-565"><strong>Cosa non migra</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9b455-566"><strong>Qualsiasi dispositivo di condivisione file che supporta SMB 2.0 e versioni successive</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="9b455-567">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-568">Documenti</span><span class="sxs-lookup"><span data-stu-id="9b455-568">Documents</span></span> </li>
<li> <span data-ttu-id="9b455-569">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-570">Autorizzazioni per file e cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="9b455-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-571">Autorizzazioni per file e cartelle a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="9b455-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-572">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-573">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-574">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-574">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-575">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-575">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-576">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-576">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-577">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="9b455-578">\*Configurazione della sincronizzazione della directory necessaria.</span><span class="sxs-lookup"><span data-stu-id="9b455-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="9b455-579">Vengono migrate solo le autorizzazioni NTFS esposte a Esplora file di Windows.</span><span class="sxs-lookup"><span data-stu-id="9b455-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="9b455-580">Le autorizzazioni gestite direttamente nei dispositivi di condivisione dei file non vengono migrate.</span><span class="sxs-lookup"><span data-stu-id="9b455-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="9b455-581">Se i dati sono archiviati su un dispositivo SMB 2.0, vengono migrate le autorizzazioni equivalenti a NTFS esposte dal protocollo SMB.</span><span class="sxs-lookup"><span data-stu-id="9b455-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="9b455-582">Le autorizzazioni sono influenzate dal Microsoft 365 e/o Microsoft Teams canale.</span><span class="sxs-lookup"><span data-stu-id="9b455-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="9b455-583">Se la destinazione è un Microsoft 365 gruppo o Microsoft Teams, il gruppo o il canale determina il profilo delle autorizzazioni finali per i file migrati.</span><span class="sxs-lookup"><span data-stu-id="9b455-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="9b455-584">È consigliabile non eseguire la migrazione delle autorizzazioni per la migrazione dei file a un Microsoft 365 gruppo o Microsoft Teams canale.</span><span class="sxs-lookup"><span data-stu-id="9b455-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-585">Cronologia di proprietà e versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="9b455-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="9b455-586">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-587">Versioni precedenti</span><span class="sxs-lookup"><span data-stu-id="9b455-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="9b455-588">File di Windows e attributi di cartella (come Di sola lettura e Nascosto)</span><span class="sxs-lookup"><span data-stu-id="9b455-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="9b455-589">Impostazioni avanzate e autorizzazioni speciali non Windows New Technology File System (NTFS):</span><span class="sxs-lookup"><span data-stu-id="9b455-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="9b455-590">Autorizzazioni di negazione esplicita (contenuto rimosso dopo la migrazione, contenuto soggetto ad autorizzazioni parallele o autorizzazioni sulla cartella padre)</span><span class="sxs-lookup"><span data-stu-id="9b455-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="9b455-591">Configurazione di controllo NTFS</span><span class="sxs-lookup"><span data-stu-id="9b455-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="9b455-592">Metadati di file aggiuntivi forniti dall'Infrastruttura di classificazione file (FCI)</span><span class="sxs-lookup"><span data-stu-id="9b455-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="9b455-593">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-594">Condivisioni nascoste</span><span class="sxs-lookup"><span data-stu-id="9b455-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="9b455-595">Condivisione (come autorizzazioni concesse a livello di condivisione)</span><span class="sxs-lookup"><span data-stu-id="9b455-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="9b455-596">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9b455-597"><strong>Ambiente G Suite singolo (solo Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="9b455-598">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-599">Documenti, Fogli e Presentazioni Google (i file sono convertiti al formato Office equivalente, anche quelli di oltre 10 MB)</span><span class="sxs-lookup"><span data-stu-id="9b455-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="9b455-600">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-601">Autorizzazioni per le cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="9b455-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-602">Autorizzazioni cartella a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="9b455-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-603">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-604">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-605">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-605">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-606">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-606">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-607">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-607">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-608">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9b455-609">Unità condivise (cartelle e file)</span><span class="sxs-lookup"><span data-stu-id="9b455-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="9b455-610">Contenuto condiviso appartenente all'account Google Drive in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="9b455-611">\*Le autorizzazioni sono influenzate dal Microsoft 365 gruppo e/o Microsoft Teams canale.</span><span class="sxs-lookup"><span data-stu-id="9b455-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="9b455-612">Se la destinazione è un Microsoft 365 gruppo o Microsoft Teams, il gruppo o il canale determina il profilo delle autorizzazioni finali per i file migrati.</span><span class="sxs-lookup"><span data-stu-id="9b455-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="9b455-613">È consigliabile non eseguire la migrazione delle autorizzazioni per la migrazione dei file a un Microsoft 365 gruppo o Microsoft Teams canale.</span><span class="sxs-lookup"><span data-stu-id="9b455-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="9b455-614">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="9b455-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9b455-615">Descrizioni di file e cartelle, colori delle cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="9b455-616">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-617">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-618">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="9b455-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9b455-619">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="9b455-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9b455-620">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-621">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="9b455-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="9b455-622">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-623">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="9b455-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9b455-624">Google Photos, Moduli, Maps e altre app connesse</span><span class="sxs-lookup"><span data-stu-id="9b455-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="9b455-625">Disegni Google</span><span class="sxs-lookup"><span data-stu-id="9b455-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="9b455-626">Contenuti condivisi esterni alla tua impresa</span><span class="sxs-lookup"><span data-stu-id="9b455-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="9b455-627">Contenuto che appartenente all'account Google Drive che è in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="9b455-628">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Google Drive Admin per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9b455-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="9b455-629">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-630">Autorizzazioni di appartenenza alle unità condivisa (<strong>Nota</strong>: usare i report amministratore di Google Drive per identificare l’appartenenza alle unità condivise.</span><span class="sxs-lookup"><span data-stu-id="9b455-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="9b455-631">Indicare agli utenti finali di configurare queste impostazioni di appartenenza nella destinazione prima della migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-632">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9b455-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="9b455-634">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-635">Documenti</span><span class="sxs-lookup"><span data-stu-id="9b455-635">Documents</span></span> </li>
<li> <span data-ttu-id="9b455-636">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-637">Autorizzazioni per le cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="9b455-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-638">Autorizzazioni cartella a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="9b455-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-639">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-640">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-641">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-641">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-642">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-642">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-643">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-643">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-644">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9b455-645">Contenuto condiviso appartenente all'account Box in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="9b455-646">Note casella (convertite in formato documento Word)</span><span class="sxs-lookup"><span data-stu-id="9b455-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="9b455-647">\*Le autorizzazioni sono influenzate dal Microsoft 365 gruppo e/o Microsoft Teams canale.</span><span class="sxs-lookup"><span data-stu-id="9b455-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="9b455-648">Se la destinazione è un Microsoft 365 gruppo o Microsoft Teams, il gruppo o il canale determina il profilo delle autorizzazioni finali per i file migrati.</span><span class="sxs-lookup"><span data-stu-id="9b455-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="9b455-649">È consigliabile non eseguire la migrazione delle autorizzazioni per la migrazione dei file a un Microsoft 365 gruppo o Microsoft Teams canale.</span><span class="sxs-lookup"><span data-stu-id="9b455-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="9b455-650">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="9b455-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9b455-651">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9b455-652">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-653">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-654">Tag Box e metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="9b455-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="9b455-655">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="9b455-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9b455-656">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-657">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="9b455-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="9b455-658">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-659">Utenti bloccati o inattivi</span><span class="sxs-lookup"><span data-stu-id="9b455-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9b455-660">App Box, Segnalibri, Preferiti e Flussi di lavoro</span><span class="sxs-lookup"><span data-stu-id="9b455-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="9b455-661">Contenuto non di proprietà dell'account Box migrato</span><span class="sxs-lookup"><span data-stu-id="9b455-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="9b455-662">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Box per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9b455-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="9b455-663">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-664">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9b455-665"><strong>Dropbox per Team (Standard e Advanced)</strong></span><span class="sxs-lookup"><span data-stu-id="9b455-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="9b455-666">Passaggio singolo o multiplo</span><span class="sxs-lookup"><span data-stu-id="9b455-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9b455-667">Documenti</span><span class="sxs-lookup"><span data-stu-id="9b455-667">Documents</span></span> </li>
<li> <span data-ttu-id="9b455-668">Struttura di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9b455-669">Autorizzazioni per le cartelle a livello di utente\*</span><span class="sxs-lookup"><span data-stu-id="9b455-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-670">Autorizzazioni cartella a livello di gruppo\*</span><span class="sxs-lookup"><span data-stu-id="9b455-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9b455-671">File inferiori a 15 GB</span><span class="sxs-lookup"><span data-stu-id="9b455-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9b455-672">Metadati cartella e documenti di base:</span><span class="sxs-lookup"><span data-stu-id="9b455-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9b455-673">Data creazione</span><span class="sxs-lookup"><span data-stu-id="9b455-673">Created date</span></span> </li>
<li> <span data-ttu-id="9b455-674">Data modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-674">Modified date</span></span> </li>
<li> <span data-ttu-id="9b455-675">Creato da</span><span class="sxs-lookup"><span data-stu-id="9b455-675">Created by</span></span> </li>
<li> <span data-ttu-id="9b455-676">Autore ultima modifica</span><span class="sxs-lookup"><span data-stu-id="9b455-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9b455-677">Contenuto e cartelle del team condiviso</span><span class="sxs-lookup"><span data-stu-id="9b455-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="9b455-678">Contenuto condiviso appartenente all'account Dropbox in corso di migrazione</span><span class="sxs-lookup"><span data-stu-id="9b455-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="9b455-679">\*Le autorizzazioni sono influenzate dal Microsoft 365 gruppo e/o Microsoft Teams canale.</span><span class="sxs-lookup"><span data-stu-id="9b455-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="9b455-680">Se la destinazione è un Microsoft 365 gruppo o Microsoft Teams, il gruppo o il canale determina il profilo delle autorizzazioni finali per i file migrati.</span><span class="sxs-lookup"><span data-stu-id="9b455-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="9b455-681">È consigliabile non eseguire la migrazione delle autorizzazioni per la migrazione dei file a un Microsoft 365 gruppo o Microsoft Teams canale.</span><span class="sxs-lookup"><span data-stu-id="9b455-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="9b455-682">Cronologia di proprietà, versioni precedenti e commenti</span><span class="sxs-lookup"><span data-stu-id="9b455-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9b455-683">Descrizioni di file e cartelle</span><span class="sxs-lookup"><span data-stu-id="9b455-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9b455-684">Autorizzazioni per file a livello di utente</span><span class="sxs-lookup"><span data-stu-id="9b455-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-685">Autorizzazioni per file a livello di gruppo</span><span class="sxs-lookup"><span data-stu-id="9b455-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9b455-686">Metadati avanzati</span><span class="sxs-lookup"><span data-stu-id="9b455-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9b455-687">Attributi di blocco di file</span><span class="sxs-lookup"><span data-stu-id="9b455-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9b455-688">Conversione degli URL incorporati nel contenuto</span><span class="sxs-lookup"><span data-stu-id="9b455-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9b455-689">Elementi eliminati</span><span class="sxs-lookup"><span data-stu-id="9b455-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="9b455-690">Documenti inaccessibili o corrotti</span><span class="sxs-lookup"><span data-stu-id="9b455-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9b455-691">Cartelle Dropbox non montate</span><span class="sxs-lookup"><span data-stu-id="9b455-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="9b455-692">Utenti eliminati o scollegati</span><span class="sxs-lookup"><span data-stu-id="9b455-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="9b455-693">Dropbox Paper, Showcases, e Spaces</span><span class="sxs-lookup"><span data-stu-id="9b455-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="9b455-694">App e preferiti di Dropbox (Pins/stars)</span><span class="sxs-lookup"><span data-stu-id="9b455-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="9b455-695">Contenuto non di proprietà dell'account Dropbox migrato</span><span class="sxs-lookup"><span data-stu-id="9b455-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="9b455-696">Autorizzazioni e metadati di base degli utenti esterni ( <strong>Nota</strong>: usare i report di Dropbox per identificare i contenuti condivisi con gli utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9b455-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="9b455-697">Indicare agli utenti finali di ricondividere i propri contenuti con utenti esterni dopo la migrazione).</span><span class="sxs-lookup"><span data-stu-id="9b455-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9b455-698">File o cartelle che superano le SharePoint e le limitazioni correnti <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">di Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9b455-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="9b455-699">Responsabilità di FastTrack per le migrazioni Microsoft Teams e Microsoft 365 gruppi</span><span class="sxs-lookup"><span data-stu-id="9b455-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="9b455-700">Gli specialisti di FastTrack eseguono attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9b455-701">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="9b455-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="9b455-702">Responsabilità dell'utente</span><span class="sxs-lookup"><span data-stu-id="9b455-702">Your responsibilities</span></span> 

<span data-ttu-id="9b455-703">Tu esegui attività standard durante il progetto di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9b455-704">Fare riferimento alle informazioni sulle responsabilità della migrazione dei dati in [Processo e aspettative](process-and-expectations.md) per maggiori dettagli.</span><span class="sxs-lookup"><span data-stu-id="9b455-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="9b455-705">È inoltre possibile eseguire le attività seguenti, specifiche per le migrazioni Microsoft Teams e Microsoft 365 gruppi:</span><span class="sxs-lookup"><span data-stu-id="9b455-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="9b455-706">Esegui il provisioning di Microsoft Teams canali e Microsoft 365 gruppi come destinazione degli eventi di migrazione.</span><span class="sxs-lookup"><span data-stu-id="9b455-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="9b455-707">FastTrack non effettua il pre-provisioning Microsoft Teams canali o Microsoft 365 gruppi.</span><span class="sxs-lookup"><span data-stu-id="9b455-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="9b455-708">FastTrack non aggiunge utenti finali o gruppi a Microsoft Teams o Microsoft 365 gruppi.</span><span class="sxs-lookup"><span data-stu-id="9b455-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="9b455-709">È necessario aggiungere gli utenti finali o i gruppi a tutti i canali Microsoft Teams e i gruppi di Microsoft 365 prima di eseguire la migrazione dei dati in tali destinazioni in modo che tali utenti finali hanno accesso ai documenti appena migrati</span><span class="sxs-lookup"><span data-stu-id="9b455-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>