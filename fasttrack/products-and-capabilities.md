---
title: Prodotti e funzionalità
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che resegni l'ambiente di origine ai requisiti minimi per l'onboarding corretto.
ms.openlocfilehash: 05936adee3f21e6078933a686dfa8dc24c33d1be
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416565"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="f01fe-104">Prodotti e funzionalità</span><span class="sxs-lookup"><span data-stu-id="f01fe-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="f01fe-105">Servizi e scenari supportati da FastTrack</span><span class="sxs-lookup"><span data-stu-id="f01fe-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="f01fe-106">Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di iniziare.</span><span class="sxs-lookup"><span data-stu-id="f01fe-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="f01fe-107">In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che resegni l'ambiente di origine fino ai requisiti minimi per l'onboarding corretto.</span><span class="sxs-lookup"><span data-stu-id="f01fe-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="f01fe-108">FastTrack fornisce indicazioni per aiutarti prima con le funzionalità di base (comuni per tutti i Microsoft Online Services) e quindi con l'onboarding di ogni servizio idoneo:</span><span class="sxs-lookup"><span data-stu-id="f01fe-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="f01fe-109">Generale</span><span class="sxs-lookup"><span data-stu-id="f01fe-109">General</span></span>](#general)
  - [<span data-ttu-id="f01fe-110">Sicurezza e conformità</span><span class="sxs-lookup"><span data-stu-id="f01fe-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="f01fe-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="f01fe-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="f01fe-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="f01fe-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="f01fe-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="f01fe-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="f01fe-114">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="f01fe-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="f01fe-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="f01fe-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="f01fe-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="f01fe-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="f01fe-117">Per informazioni sulle previsioni dell’ambiente di origine di Office 365 U.S. Government, vedere [Previsioni dell’ambiente di origine di Office 365 U.S. Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="f01fe-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="f01fe-118">Generale</span><span class="sxs-lookup"><span data-stu-id="f01fe-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f01fe-119"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f01fe-120"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f01fe-121"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f01fe-122"><strong>Onboarding di base</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-123">Forniamo indicazioni remote sull'onboarding di base, che implica il provisioning dei servizi, il tenant e l'integrazione delle identità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="f01fe-124">Include inoltre la procedura per fornire una base per i servizi di onboarding come Exchange Online, SharePoint Online e Microsoft Teams, inclusa una discussione su sicurezza, connettività di rete <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">e conformità.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="f01fe-125">L'onboarding per uno o più servizi può iniziare al termine dell'onboarding di base.</span><span class="sxs-lookup"><span data-stu-id="f01fe-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="f01fe-126"></li>
</ul>  

<strong> Integrazione delle identità </strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="f01fe-127">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="f01fe-128">Preparazione delle identità di Active Directory locali per la sincronizzazione con Azure Active Directory (Azure AD), tra cui l'installazione e la configurazione di Azure AD Connect (a foresta singola o multipla) e delle licenze (incluse le licenze basate su gruppo).</span><span class="sxs-lookup"><span data-stu-id="f01fe-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="f01fe-129">Creazione di identità cloud, tra cui importazione in blocco e licenze, incluso l'uso delle licenze basate su gruppo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="f01fe-130">Scelta e abilitazione del metodo di autenticazione corretto per il percorso cloud, Sincronizzazione hash password, Autenticazione pass-through o Active Directory Federation Services (AD FS).</span><span class="sxs-lookup"><span data-stu-id="f01fe-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="f01fe-131">Abilitazione di AD FS per i clienti con una singola foresta di Active Directory e identità sincronizzate con lo strumento Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="f01fe-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="f01fe-132">Questa operazione richiede Windows Server 2012 R2 Active Directory Federation Services 2.0 o versione successiva.</span><span class="sxs-lookup"><span data-stu-id="f01fe-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="f01fe-133">Migrazione dell'autenticazione da AD FS ad Azure AD tramite la sincronizzazione hash delle password o l'autenticazione pass-through.</span><span class="sxs-lookup"><span data-stu-id="f01fe-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="f01fe-134">Migrazione di app pre-integrate (come le app SaaS (Software-as-a-Service) della raccolta di Azure AD da AD FS ad Azure AD per Single #A0 (SSO).</span><span class="sxs-lookup"><span data-stu-id="f01fe-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="f01fe-135">Abilitazione delle integrazioni di app SaaS con SSO dalla raccolta di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="f01fe-136">Abilitazione del provisioning automatico degli utenti per le app SaaS pre-integrate, come indicato nell'elenco delle esercitazioni sull'integrazione delle <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">app</a> (limitato alle app SaaS della raccolta di Azure AD e solo al provisioning in uscita).</span><span class="sxs-lookup"><span data-stu-id="f01fe-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="f01fe-137"><strong>Abilitazione della rete </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="f01fe-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="f01fe-138">Nell'ambito del vantaggio FastTrack, si consiglia di utilizzare le procedure consigliate per la connessione ai servizi cloud per garantire i massimi livelli di prestazioni di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="f01fe-139"><strong>Foreste di Active Directory</strong> Il livello di foresta funzionale è impostato su Windows Server 2003 e successive, con la seguente configurazione della foresta:</span><span class="sxs-lookup"><span data-stu-id="f01fe-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-140">Una foresta unica di Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f01fe-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-141">Una singola foresta account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="f01fe-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-142">Più foreste account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="f01fe-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-143">Più foreste account di Active Directory con una delle foreste in posizione centrale nella foresta account di Active Directory contenente Exchange e/o Lync 2010, Lync 2013 o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="f01fe-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-144">Più foreste account di Active Directory, ognuna con la propria organizzazione di Exchange.</span><span class="sxs-lookup"><span data-stu-id="f01fe-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-145">Attività necessarie per la configurazione e l'integrazione del tenant con Azure Active Directory, se necessario.</span><span class="sxs-lookup"><span data-stu-id="f01fe-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="f01fe-146">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="f01fe-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="f01fe-147">Per gli scenari di Active Directory a più foreste, se è distribuito Lync 2010, Lync 2013 o Skype for Business, deve essere distribuito nella stessa foresta di Active Directory di Exchange.</span><span class="sxs-lookup"><span data-stu-id="f01fe-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-148">Quando si implementano più foreste di Active Directory con più organizzazioni Exchange in una configurazione multi-ibrida di Exchange, gli spazi dei nomi dell'entità utente (UPN) condivisi tra foreste di origine non sono supportati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="f01fe-149">Gli spazi dei nomi SMTP primari tra organizzazioni di Exchange devono essere separati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="f01fe-150">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=845444">Distribuzioni ibride con più insiemi di strutture di Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="f01fe-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-151">Per tutte le configurazioni di più foreste, la distribuzione di Active Directory Federation Services (AD FS) non è in ambito.</span><span class="sxs-lookup"><span data-stu-id="f01fe-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="f01fe-152">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f01fe-153"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-154">Vengono fornite indicazioni per la distribuzione remota per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-155">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-156">Assegnazione dei contratti di licenza con l'utente finale e di licenze basate sul dispositivo utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f01fe-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-157">Installare Microsoft 365 Apps dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="f01fe-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-158">Installazione delle app di Office Mobile (ad esempio Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) sui dispositivi iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="f01fe-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-159">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-160">Selezione e configurazione di un'installazione locale o cloud.</span><span class="sxs-lookup"><span data-stu-id="f01fe-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-161">Creazione del codice XML di configurazione dello Strumento di distribuzione di Office con lo Strumento di personalizzazione di Office o del codice XML nativo per configurare il pacchetto di distribuzione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-162">Distribuzione con Microsoft Endpoint Configuration Manager, che include una guida per la creazione del pacchetto di Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="f01fe-163">Inoltre, se si dispone di una macro o di un componente aggiuntivo che funzionava con le versioni precedenti di Office e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema di compatibilità senza costi aggiuntivi tramite il programma App Assure.</span><span class="sxs-lookup"><span data-stu-id="f01fe-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="f01fe-164">Per altri <strong>dettagli,</strong> vedi la parte App Assure di <a href="#windows-10">Windows 10.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f01fe-165">Il software client online deve essere al livello minimo definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f01fe-166"><strong>Integrità della rete</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-167">Forniamo indicazioni remote per ottenere e interpretare i dati di connettività di rete chiave dall'ambiente in uso che mostrano quanto i siti dell'organizzazione sono allineati ai principi di connettività <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">di rete di</a>Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f01fe-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="f01fe-168">Questo evidenzia il punteggio di rete che influisce direttamente sulla velocità della migrazione, sull'esperienza utente, sulle prestazioni del servizio e sull'affidabilità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="f01fe-169">Ti guideremo anche attraverso qualsiasi procedura di correzione evidenziata da questi dati per aiutarti a migliorare il punteggio di rete.</span><span class="sxs-lookup"><span data-stu-id="f01fe-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="f01fe-170">Accesso all'interfaccia di amministrazione di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-171">Sono necessarie versioni aggiornate delle app di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-172">Servizi percorso abilitati in base ai suggerimenti sulle prestazioni di rete nell'interfaccia di amministrazione di <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 (anteprima).</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="f01fe-173">Sicurezza e conformità</span><span class="sxs-lookup"><span data-stu-id="f01fe-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f01fe-174"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f01fe-175"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f01fe-176"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="f01fe-177"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-178">Vengono fornite indicazioni remote per la protezione delle identità cloud per gli scenari seguenti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="f01fe-179">

<strong>Infrastruttura di base protetta</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="f01fe-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="f01fe-180">Configurazione e abilitazione dell'autenticazione avanzata per le identità, inclusa la protezione con Azure Multi-Factor Authentication (MFA) (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure MFA e la reimpostazione della password self-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="f01fe-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-181">Per i clienti non di Azure AD Premium, vengono fornite indicazioni per proteggere le identità usando le impostazioni predefinite di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-182">Per i clienti premium di Azure AD, vengono fornite indicazioni per proteggere le identità con l'accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-183">Rilevamento e blocco dell'uso di password deboli con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-184">Protezione dell'accesso remoto alle app Web locali con il proxy dell'applicazione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-185">Abilitazione del rilevamento e della correzione basata sui rischi con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-186">Abilitazione di una schermata di accesso personalizzata, inclusi logo, testo e immagini con personalizzazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-187">Condivisione sicura di app e servizi con utenti guest con Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="f01fe-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-188">Gestione dell'accesso per gli amministratori di Office 365 tramite i ruoli amministrativi incorporati del controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-189">Configurazione dell'aggiunta ad Azure AD ibrido.</span><span class="sxs-lookup"><span data-stu-id="f01fe-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-190">Configurazione dell'aggiunta ad Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="f01fe-191">
  
<strong>Monitoraggio e creazione di report</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f01fe-192">Abilitazione del monitoraggio remoto per AD FS, Azure AD Connect e controller di dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="f01fe-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="f01fe-193">
  
<strong>Governance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f01fe-194">Gestione del ciclo di vita delle identità e degli accessi di Azure AD su vasta scala con la gestione dei diritti di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="f01fe-195">Gestione dell'appartenenza ai gruppi di Azure AD, dell'accesso alle app aziendali e delle assegnazioni dei ruoli con le verifiche di accesso di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-196">Esame delle Condizioni per l'utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-197">Gestione e controllo dell'accesso agli account amministratore con privilegi con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="f01fe-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="f01fe-198">
  
<strong>Automazione ed efficienza </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f01fe-199">Abilitazione di Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="f01fe-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="f01fe-200">Consentire agli utenti di creare e gestire la propria sicurezza cloud o i gruppi di Office 365 con la gestione dei gruppi self-service di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-201">Gestione dell'accesso delegato alle app aziendali con la gestione dei gruppi delegati di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-202">Abilitazione dei gruppi dinamici di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-203">Organizzazione delle app nel portale App personali tramite raccolte.</span><span class="sxs-lookup"><span data-stu-id="f01fe-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f01fe-204">Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione dei problemi identificati che impediscono l'integrazione con le funzionalità di Azure AD e Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="f01fe-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f01fe-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="f01fe-206">Per altre informazioni su Azure Information Protection, vedere <strong>Microsoft Information Protection</strong> più avanti in questa tabella.</span><span class="sxs-lookup"><span data-stu-id="f01fe-206">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="f01fe-207"><strong>Risposta & individuazione</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-207"><strong>Discovery & Response</strong></span></span></td>
<td>  

<span data-ttu-id="f01fe-208"><strong>Advanced eDiscovery</strong>
  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-208"><strong>Advanced eDiscovery</strong>
  
</span></span><ul>
<li>  <span data-ttu-id="f01fe-209">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="f01fe-209">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-210">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="f01fe-210">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-211">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-211">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-212">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="f01fe-212">Reporting and threat analytics.</span></span>  </li>
</ul>

<span data-ttu-id="f01fe-213"><strong>Controllo avanzato</strong> (supportato solo in E5)</span><span class="sxs-lookup"><span data-stu-id="f01fe-213"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="f01fe-214">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-214">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="f01fe-215">Abilitazione del controllo avanzato.</span><span class="sxs-lookup"><span data-stu-id="f01fe-215">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="f01fe-216">Esecuzione di un'interfaccia utente del log di controllo della ricerca e dei comandi di base di PowerShell di controllo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-216">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="f01fe-217">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-217">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f01fe-218">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-218">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f01fe-219">Esame dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-219">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f01fe-220">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-220">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f01fe-221">Valutare la conformità implementando azioni di miglioramento e determinando in che modo ciò influisce sul punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-221">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f01fe-222">Analisi del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="f01fe-222">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f01fe-223">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-223">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f01fe-224">

<strong>Gli elementi seguenti non sono nell'ambito </strong> 
</span><span class="sxs-lookup"><span data-stu-id="f01fe-224">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="f01fe-225">Script o codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-225">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="f01fe-226">API eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="f01fe-226">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="f01fe-227">Connettori dati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-227">Data connectors.</span></span> </li>
<li> <span data-ttu-id="f01fe-228">Limiti di conformità e filtri di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-228">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="f01fe-229">Indagini sui dati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-229">Data investigations.</span></span></li>
<li> <span data-ttu-id="f01fe-230">Richieste dell'oggetto dei dati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-230">Data subject requests.</span></span></li>
<li> <span data-ttu-id="f01fe-231">Revisione di documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-231">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f01fe-232">Conformità alle normative e ai requisiti di settore e regionali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-232">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f01fe-233">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-233">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="f01fe-234">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="f01fe-234">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="f01fe-235"><strong>Insider Threat Management</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-235"><strong>Insider Threat Management</strong></span></span></td>

<td>  <span data-ttu-id="f01fe-236">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-236">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="f01fe-237">Creazione di criteri e revisione delle impostazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-237">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="f01fe-238">Accesso a report e avvisi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-238">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="f01fe-239">Creare casi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-239">Creating cases.</span></span></li>
<li> <span data-ttu-id="f01fe-240">Creazione di modelli di avviso.</span><span class="sxs-lookup"><span data-stu-id="f01fe-240">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="f01fe-241">Linee guida per la creazione del connettore risorse umane (HR).</span><span class="sxs-lookup"><span data-stu-id="f01fe-241">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="f01fe-242">

<strong> Conformità delle comunicazioni </strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-242">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="f01fe-243">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-243">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="f01fe-244">Creazione di criteri e revisione delle impostazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="f01fe-245">Accesso a report e avvisi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="f01fe-246">Creazione di modelli di avviso.</span><span class="sxs-lookup"><span data-stu-id="f01fe-246">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="f01fe-247">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-247">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f01fe-248">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-248">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f01fe-249">Esame dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-249">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f01fe-250">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-250">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f01fe-251">Valutare la conformità implementando azioni di miglioramento e determinando in che modo ciò influisce sul punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-251">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f01fe-252">Analisi del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="f01fe-252">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f01fe-253">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-253">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f01fe-254">

<strong>Gli elementi seguenti non sono nell'ambito </strong> 
</span><span class="sxs-lookup"><span data-stu-id="f01fe-254">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="f01fe-255">Creazione e gestione dei flussi di Power Automate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-255">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="f01fe-256">Connettori dati (oltre il connettore HR).</span><span class="sxs-lookup"><span data-stu-id="f01fe-256">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="f01fe-257">Configurazioni di espressioni regolari personalizzate (RegEx).</span><span class="sxs-lookup"><span data-stu-id="f01fe-257">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="f01fe-258">Revisione di documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-258">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f01fe-259">Barriere in fatto di informazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-259">Information barriers.</span></span></li>
<li> <span data-ttu-id="f01fe-260">Gestione degli accessi con privilegi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-260">Privileged access management.</span></span></li>
<li> <span data-ttu-id="f01fe-261">Conformità alle normative e ai requisiti di settore e regionali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-261">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f01fe-262">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-262">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="f01fe-263">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="f01fe-263">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="f01fe-264"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-264"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="f01fe-265">Microsoft 365 Defender è una famiglia di prodotti di difesa aziendale pre e post-violazione unificata che coordina in modo nativo il rilevamento, la prevenzione, l'indagine e la risposta tra endpoint, identità, posta elettronica e app per fornire una protezione integrata da attacchi sofisticati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-265">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="f01fe-266">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-266">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="f01fe-267">Panoramica del Centro sicurezza Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-267">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-268">Esame degli incidenti tra prodotti, inclusa l'attenzione su ciò che è critico, garantendo l'ambito completo degli attacchi, le risorse influenzate e le azioni di correzione automatizzate raggruppate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-268">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-269">Dimostrazione del modo in cui Microsoft 365 Defender può orchestrare l'analisi di risorse, utenti, dispositivi e cassette postali che potrebbero essere state compromesse tramite l'auto-riparazione automatica.</span><span class="sxs-lookup"><span data-stu-id="f01fe-269">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="f01fe-270">Spiegare e fornire esempi di come i clienti possono cercare in modo proattivo tentativi di intrusione e attività di violazione che influiscono su posta elettronica, dati, dispositivi e account in più set di dati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-270">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="f01fe-271">Mostrare ai clienti come possono esaminare e migliorare la loro posizione di sicurezza in modo olistico con Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="f01fe-271">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="f01fe-272"><strong>Gli elementi seguenti non sono nell'ambito</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-272"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="f01fe-273">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-273">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="f01fe-274">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-274">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="f01fe-275">Linee guida per la distribuzione o formazione su:</span><span class="sxs-lookup"><span data-stu-id="f01fe-275">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="f01fe-276">Come correggere o interpretare i vari tipi di avviso e le attività monitorate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-276">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="f01fe-277">Come analizzare un utente, un computer, un percorso di spostamento laterale o un'entità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-277">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="f01fe-278">Ricerca personalizzata delle minacce.</span><span class="sxs-lookup"><span data-stu-id="f01fe-278">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="f01fe-279">Integrazione DIEM (Security Information and Event Management) o API.</span><span class="sxs-lookup"><span data-stu-id="f01fe-279">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f01fe-280"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-280"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-281">Microsoft Cloud App Security è un Cloud Access Security Broker (CASB) che offre visibilità completa, controllo sui viaggi dei dati e analisi sofisticate per identificare e contrastare le minacce informatiche in tutti i servizi cloud Microsoft e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-281">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="f01fe-282">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-282">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-283">Configurazione del portale, tra cui:</span><span class="sxs-lookup"><span data-stu-id="f01fe-283">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="f01fe-284">Importazione di gruppi di utenti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-284">Importing user groups.</span></span></li>
<li> <span data-ttu-id="f01fe-285">Gestione dell'accesso e delle impostazioni dell'amministratore.</span><span class="sxs-lookup"><span data-stu-id="f01fe-285">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="f01fe-286">Definizione dell'ambito della distribuzione per selezionare determinati gruppi di utenti da monitorare o escludere dal monitoraggio.</span><span class="sxs-lookup"><span data-stu-id="f01fe-286">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="f01fe-287">Impostazione di intervalli e tag IP.</span><span class="sxs-lookup"><span data-stu-id="f01fe-287">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="f01fe-288">Personalizzazione dell'esperienza dell'utente finale con il logo e la messaggistica personalizzata.</span><span class="sxs-lookup"><span data-stu-id="f01fe-288">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="f01fe-289">Configurare l'individuazione cloud per fornire shadow IT tramite:</span><span class="sxs-lookup"><span data-stu-id="f01fe-289">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="f01fe-290">Microsoft Defender per gli endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-290">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="f01fe-291">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="f01fe-291">Zscaler.</span></span></li>
<li> <span data-ttu-id="f01fe-292">iboss.</span><span class="sxs-lookup"><span data-stu-id="f01fe-292">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="f01fe-293">Connessione <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">di app in primo</a> piano tramite connettori di app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-293">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="f01fe-294">Configurazione del controllo dell'app di accesso condizionale nei portali di Accesso condizionale e Cloud App Security per applicare i controlli delle sessioni in tempo reale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-294">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="f01fe-295">Distribuzione dei dashboard cloud App Security e Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="f01fe-295">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="f01fe-296">Personalizzazione dei punteggi di rischio delle app in base alle priorità dell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-296">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="f01fe-297">Creazione di tag e categorie dell'app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-297">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="f01fe-298">App che sanzionano e annullano l'associazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-298">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="f01fe-299">Uso di attività e log di file.</span><span class="sxs-lookup"><span data-stu-id="f01fe-299">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="f01fe-300">Gestione delle app OAuth.</span><span class="sxs-lookup"><span data-stu-id="f01fe-300">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="f01fe-301">Informazioni sulla correlazione degli eventi imprevisti nel portale di Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="f01fe-301">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="f01fe-302">Fornire assistenza alla configurazione con i <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> casi d'uso principali per i casb (inclusa la creazione o l'aggiornamento di un massimo di sei (6) criteri), ad eccezione di:</span><span class="sxs-lookup"><span data-stu-id="f01fe-302">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="f01fe-303">Controllo della configurazione degli ambienti IaaS (Internet as a Service) (#18).</span><span class="sxs-lookup"><span data-stu-id="f01fe-303">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="f01fe-304">Monitoraggio delle attività degli utenti per la protezione dalle minacce negli ambienti IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="f01fe-304">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="f01fe-305"><strong>Gli elementi seguenti non sono nell'ambito</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-305"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="f01fe-306">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-306">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="f01fe-307">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-307">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="f01fe-308">Configurazione dell'infrastruttura, dell'installazione o della distribuzione dei caricamenti automatici dei log per i report continui tramite Docker o un agente di raccolta log.</span><span class="sxs-lookup"><span data-stu-id="f01fe-308">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="f01fe-309">Per <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">ulteriori informazioni, vedere i 20 casi</a> di utilizzo principali per i casb.</span><span class="sxs-lookup"><span data-stu-id="f01fe-309">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="f01fe-310">Creazione di un report snapshot di Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="f01fe-310">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="f01fe-311">Blocco dell'utilizzo dell'app tramite script di blocco.</span><span class="sxs-lookup"><span data-stu-id="f01fe-311">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="f01fe-312">Connessione di app personalizzate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-312">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="f01fe-313">Integrazione con provider di identità (IsP) di terze parti e provider di prevenzione della perdita di dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="f01fe-313">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="f01fe-314">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="f01fe-314">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="f01fe-315">Analisi e correzione automatizzate, inclusi i playbook di Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-315">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="f01fe-316">Integrazione delle API e delle informazioni di sicurezza (SIEM, Security Information and Event Management) (incluso Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="f01fe-316">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="f01fe-317">Distribuzione di Cloud App Discovery come modello di prova.</span><span class="sxs-lookup"><span data-stu-id="f01fe-317">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="f01fe-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-319">Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-319">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="f01fe-320">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-320">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-321">Distribuzione delle tecnologie per proteggere gli endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-321">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-322">Configurazione dei profili di protezione degli endpoint e delle restrizioni dei dispositivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-322">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-323">Valutazione della versione del sistema operativo e della gestione dei dispositivi (inclusi Intune, Microsoft Endpoint Configuration Manager, oggetti Criteri di gruppo e configurazioni di terze parti), nonché lo stato dei servizi av di Windows Defender o di altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-323">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-324">Valutazione dello stato dei servizi Windows AV o di altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-324">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-325">Valutazione dei proxy e dei firewall che limitano il traffico di rete.</span><span class="sxs-lookup"><span data-stu-id="f01fe-325">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-326">Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo agente ATP con un endpoint di onboarding.</span><span class="sxs-lookup"><span data-stu-id="f01fe-326">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-327">Linee guida per la distribuzione, assistenza alla configurazione ed istruzione su:</span><span class="sxs-lookup"><span data-stu-id="f01fe-327">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-328">Gestione delle minacce e delle vulnerabilità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-328">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-329">Riduzione della superficie di attacco.</span><span class="sxs-lookup"><span data-stu-id="f01fe-329">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-330">Protezione di nuova generazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-330">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-331">Rilevamento e risposta degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-331">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-332">Indagine e correzione automatizzate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-332">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-333">Punteggio di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-333">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-334">Revisione di simulazioni ed esercitazioni (come scenari di pratica, malware falso e indagini automatizzate).</span><span class="sxs-lookup"><span data-stu-id="f01fe-334">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-335">Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="f01fe-335">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-336">Integrazione di Office 365 ATP con Microsoft Defender ATP.</span><span class="sxs-lookup"><span data-stu-id="f01fe-336">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-337">Procedure dettagliate nel portale di Microsoft Defender Security Center.</span><span class="sxs-lookup"><span data-stu-id="f01fe-337">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-338">I sistemi operativi seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-338">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-339">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-339">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-340">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f01fe-340">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-341">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="f01fe-341">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-342">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="f01fe-342">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-343">Windows Server Semi-Annual Channel (SAC) versione 1803.</span><span class="sxs-lookup"><span data-stu-id="f01fe-343">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-344">macOS versioni 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="f01fe-344">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="f01fe-345">
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versione 2002 o successiva).</span><span class="sxs-lookup"><span data-stu-id="f01fe-345">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="f01fe-346"></li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-346"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f01fe-347">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-347">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-348">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="f01fe-348">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-349">Gestione continua e risposta alle minacce.</span><span class="sxs-lookup"><span data-stu-id="f01fe-349">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-350">Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-350">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-351">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="f01fe-351">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-352">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="f01fe-352">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-353">Linux.</span><span class="sxs-lookup"><span data-stu-id="f01fe-353">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-354">Dispositivi mobili (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="f01fe-354">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="f01fe-355">Virtual Desktop Infrastructure (VDI) (persistente o non persistente).</span><span class="sxs-lookup"><span data-stu-id="f01fe-355">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-356">Onboarding e configurazione del server:</span><span class="sxs-lookup"><span data-stu-id="f01fe-356">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-357">Configurazione di un server proxy per le comunicazioni offline.</span><span class="sxs-lookup"><span data-stu-id="f01fe-357">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-358">Configurazione dei pacchetti di distribuzione di Configuration Manager nelle istanze e nelle versioni di Configuration Manager di livello inferiore.</span><span class="sxs-lookup"><span data-stu-id="f01fe-358">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-359">Onboarding dei server nel Centro sicurezza di Azure.</span><span class="sxs-lookup"><span data-stu-id="f01fe-359">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-360">Server non gestiti da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-360">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-361">Onboarding e configurazione di macOS:</span><span class="sxs-lookup"><span data-stu-id="f01fe-361">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-362">Distribuzione manuale basata su Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-362">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-363">Distribuzione basata su JAMF.</span><span class="sxs-lookup"><span data-stu-id="f01fe-363">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="f01fe-364">Altra distribuzione basata sul prodotto di gestione dei dispositivi mobili (MDM).</span><span class="sxs-lookup"><span data-stu-id="f01fe-364">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-365">Distribuzione manuale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-365">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-366">Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-366">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-367">Isolamento basato su hardware.</span><span class="sxs-lookup"><span data-stu-id="f01fe-367">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-368">Controllo dell'app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-368">App control.</span></span>  
  </li>
<li> <span data-ttu-id="f01fe-369">Controllo dispositivo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-369">Device control.</span></span></li>
<li>  
  <span data-ttu-id="f01fe-370">Protezione dagli exploit.</span><span class="sxs-lookup"><span data-stu-id="f01fe-370">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-371">Firewall di rete.</span><span class="sxs-lookup"><span data-stu-id="f01fe-371">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="f01fe-372">Configurazione o gestione delle funzionalità di protezione degli account, ad esempio:</span><span class="sxs-lookup"><span data-stu-id="f01fe-372">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="f01fe-373">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="f01fe-373">Windows Hello</span></span></li>
<li> <span data-ttu-id="f01fe-374">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="f01fe-374">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="f01fe-375">Configurazione o gestione di BitLocker.</span><span class="sxs-lookup"><span data-stu-id="f01fe-375">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="f01fe-376">Iscrizione o configurazione di Microsoft Threat Experts.</span><span class="sxs-lookup"><span data-stu-id="f01fe-376">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-377">Configurazione o formazione che esamina le connessioni API o siem (Security Information and Event Management).</span><span class="sxs-lookup"><span data-stu-id="f01fe-377">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-378">Iscrizione o configurazione di Microsoft Threat Protection (MTP).</span><span class="sxs-lookup"><span data-stu-id="f01fe-378">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-379">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="f01fe-379">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-380">Formazione o indicazioni su come usare o creare query Kusto.</span><span class="sxs-lookup"><span data-stu-id="f01fe-380">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="f01fe-381">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-381">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="f01fe-382"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-382"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="f01fe-383">Microsoft Defender per identità è una soluzione di sicurezza basata sul cloud che sfrutta i segnali di Active Directory locali per identificare, rilevare e analizzare minacce avanzate, identità compromesse ed azioni Insider dannose dirette all'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-383">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="f01fe-384">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-384">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="f01fe-385">Creazione dell'istanza di Defender per l'identità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-385">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="f01fe-386">Connessione di Defender per l'identità ad Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f01fe-386">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="f01fe-387">Valutazione della preparazione dell'ambiente per la distribuzione del sensore Defender for Identity nei controller di dominio, tra cui:</span><span class="sxs-lookup"><span data-stu-id="f01fe-387">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="f01fe-388">Esecuzione dello strumento di dimensionamento per la pianificazione della capacità delle risorse.</span><span class="sxs-lookup"><span data-stu-id="f01fe-388">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="f01fe-389">Esecuzione dello strumento di controllo per valutare la compatibilità dei controller di dominio con il sensore.</span><span class="sxs-lookup"><span data-stu-id="f01fe-389">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="f01fe-390">Distribuzione del sensore per acquisire e analizzare il traffico di rete e gli eventi di Windows direttamente dai controller di dominio, tra cui:</span><span class="sxs-lookup"><span data-stu-id="f01fe-390">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="f01fe-391">Download del pacchetto del sensore.</span><span class="sxs-lookup"><span data-stu-id="f01fe-391">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="f01fe-392">Configurazione del sensore.</span><span class="sxs-lookup"><span data-stu-id="f01fe-392">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="f01fe-393">Installazione del sensore nel controller di dominio in modo invisibile all'utente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-393">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="f01fe-394">Distribuzione del sensore nell'ambiente a più foreste.</span><span class="sxs-lookup"><span data-stu-id="f01fe-394">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="f01fe-395">Integrazione di Defender per l'identità con Microsoft Cloud App Security (la licenza di Cloud App Security non è necessaria).</span><span class="sxs-lookup"><span data-stu-id="f01fe-395">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="f01fe-396">Fornire indicazioni sulla distribuzione, assistenza alla configurazione e formazione su:</span><span class="sxs-lookup"><span data-stu-id="f01fe-396">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="f01fe-397">Ottimizzazione dell'ambiente per ridurre il "rumore".</span><span class="sxs-lookup"><span data-stu-id="f01fe-397">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="f01fe-398">Informazioni sul report di valutazione della sicurezza delle identità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-398">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="f01fe-399">Informazioni sul punteggio di priorità dell'indagine utente e sul report di classificazione delle indagini degli utenti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-399">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="f01fe-400">Informazioni sul report degli utenti inattivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-400">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="f01fe-401">Fornire opzioni di correzione per un account compromesso.</span><span class="sxs-lookup"><span data-stu-id="f01fe-401">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="f01fe-402">Facilitare la migrazione da Advanced Threat Analytics (ATA) a Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="f01fe-402">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="f01fe-403"><strong>Gli elementi seguenti non sono nell'ambito</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-403"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="f01fe-404">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-404">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="f01fe-405">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-405">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="f01fe-406">Distribuzione del sensore Defender for Identity, tra cui:</span><span class="sxs-lookup"><span data-stu-id="f01fe-406">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="f01fe-407">Pianificazione manuale della capacità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-407">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="f01fe-408">Distribuzione del sensore in una capacità autonoma.</span><span class="sxs-lookup"><span data-stu-id="f01fe-408">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="f01fe-409">Distribuzione del sensore con una scheda nic (Network Interface Card) Del teaming.</span><span class="sxs-lookup"><span data-stu-id="f01fe-409">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="f01fe-410">Distribuzione del sensore tramite uno strumento di terze parti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-410">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="f01fe-411">Connessione al servizio cloud Defender for Identity tramite una connessione proxy Web.</span><span class="sxs-lookup"><span data-stu-id="f01fe-411">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="f01fe-412">Creazione e gestione di honeytoken.</span><span class="sxs-lookup"><span data-stu-id="f01fe-412">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="f01fe-413">Linee guida per la distribuzione o formazione su:</span><span class="sxs-lookup"><span data-stu-id="f01fe-413">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="f01fe-414">Correzione o interpretazione di vari tipi di avviso e attività monitorate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-414">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="f01fe-415">Analisi di un utente, di un computer, di un percorso di spostamento laterale o di un'entità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-415">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="f01fe-416">Minaccia o ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="f01fe-416">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="f01fe-417">Risposta a un evento imprevisto.</span><span class="sxs-lookup"><span data-stu-id="f01fe-417">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="f01fe-418">Esercitazione del laboratorio di avviso di sicurezza per Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="f01fe-418">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="f01fe-419">Fornire una notifica quando Defender for Identity rileva attività sospette inviando avvisi di sicurezza al server syslog tramite un sensore designato.</span><span class="sxs-lookup"><span data-stu-id="f01fe-419">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="f01fe-420">Configurazione di Defender per l'identità per eseguire query utilizzando il protocollo samr (Security Account Manager Remote) per identificare gli amministratori locali in computer specifici.</span><span class="sxs-lookup"><span data-stu-id="f01fe-420">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="f01fe-421">Configurazione di soluzioni VPN per aggiungere informazioni dalla connessione VPN alla pagina del profilo di un utente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-421">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="f01fe-422">Integrazione delle API e delle informazioni di sicurezza (SIEM, Security Information and Event Management) (incluso Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="f01fe-422">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="f01fe-423">Distribuzione di Defender per i sensori di identità come modello di prova.</span><span class="sxs-lookup"><span data-stu-id="f01fe-423">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f01fe-424">Active Directory distribuito.</span><span class="sxs-lookup"><span data-stu-id="f01fe-424">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-425">I controller di dominio in cui intendi installare Defender per i sensori di identità dispongono di connettività Internet al servizio cloud Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="f01fe-425">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="f01fe-426">Il firewall e il proxy devono essere aperti per comunicare con il servizio cloud Defender for Identity (\*.atp.azure.com la porta 443 deve essere aperta).</span><span class="sxs-lookup"><span data-stu-id="f01fe-426">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="f01fe-427">Controller di dominio in esecuzione in uno dei seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-427">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="f01fe-428">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="f01fe-428">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="f01fe-429">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="f01fe-429">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="f01fe-430">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="f01fe-430">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="f01fe-431">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f01fe-431">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="f01fe-432">Windows Server 2019 con KB4487044 (OS Build 17763.316).</span><span class="sxs-lookup"><span data-stu-id="f01fe-432">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="f01fe-433"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-433"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="f01fe-434">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-434">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-435">Creazione e pubblicazione di etichette e criteri di conservazione (supportati solo in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-435">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="f01fe-436">Gestione dei record (supportata solo in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-436">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="f01fe-437">Revisione della creazione del piano di file.</span><span class="sxs-lookup"><span data-stu-id="f01fe-437">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="f01fe-438">Creazione e gestione di record(inclusi i record basati su eventi).</span><span class="sxs-lookup"><span data-stu-id="f01fe-438">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-439">Revisione dell'eliminazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-439">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="f01fe-440">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-440">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f01fe-441">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-441">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f01fe-442">Esame dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-442">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f01fe-443">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-443">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f01fe-444">Valutare la conformità implementando azioni di miglioramento e determinando in che modo ciò influisce sul punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-444">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f01fe-445">Analisi del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="f01fe-445">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f01fe-446">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-446">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f01fe-447">

  <strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-447">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="f01fe-448">Sviluppo di un piano di gestione dei file di record.</span><span class="sxs-lookup"><span data-stu-id="f01fe-448">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="f01fe-449">Connettori dati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-449">Data connectors.</span></span></li>
<li> <span data-ttu-id="f01fe-450">Sviluppo dell'architettura delle informazioni in SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-450">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="f01fe-451">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-451">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f01fe-452">Revisione di documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-452">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f01fe-453">Supporto per E3.</span><span class="sxs-lookup"><span data-stu-id="f01fe-453">Support for E3.</span></span></li>
<li> <span data-ttu-id="f01fe-454">Conformità alle normative e ai requisiti di settore e regionali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-454">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f01fe-455">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-455">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="f01fe-456">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="f01fe-456">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f01fe-457"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-457"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-458">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-458">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-459">Classificazione dei dati (supportata in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-459">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-460">Tipi di informazioni riservate (supportati in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-460">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-461">Creazione di etichette di riservatezza (supportate in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-461">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-462">Applicazione di etichette di riservatezza (supportate in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-462">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-463">Classificatori trainabili (supportati in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-463">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-464">Conoscere i dati con Esplora contenuto ed Esplora attività (supportato in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-464">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-465">Pubblicazione di etichette con criteri (manuali e automatici) (supportati in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-465">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-466">Creazione di criteri di prevenzione della perdita dei dati (DLP) degli endpoint per i dispositivi Windows 10 (supportati in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-466">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-467">Creazione di criteri DLP per chat e canali di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f01fe-467">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="f01fe-468">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-468">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f01fe-469">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-469">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f01fe-470">Esame dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-470">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f01fe-471">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-471">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f01fe-472">Valutare la conformità implementando azioni di miglioramento e determinando in che modo ciò influisce sul punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-472">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f01fe-473">Analisi del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="f01fe-473">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f01fe-474">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-474">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f01fe-475">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-475">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="f01fe-476">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-476">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="f01fe-477">Attivazione e configurazione del tenant.</span><span class="sxs-lookup"><span data-stu-id="f01fe-477">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-478">Creazione e configurazione di etichette e criteri (supportati in P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f01fe-478">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-479">Applicazione della protezione delle informazioni ai documenti (supportata in P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f01fe-479">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-480">Classificare ed etichettare automaticamente le informazioni nelle app di Office (ad esempio Word, PowerPoint, Excel e Outlook) in esecuzione in Windows e con il client Azure Information Protection (supportato in P2).</span><span class="sxs-lookup"><span data-stu-id="f01fe-480">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-481">Individuazione e applicazione di etichette ai file in stato di inquieto con lo scanner di Azure Information Protection (supportato in P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f01fe-481">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-482">Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f01fe-482">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="f01fe-483">Vengono inoltre fornite indicazioni per applicare la protezione tramite Microsoft Azure Rights Management Services (Azure RMS), Crittografia messaggi di Office 365 e prevenzione della perdita dei dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="f01fe-483">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="f01fe-484"><strong>Gli elementi seguenti non sono nell'ambito </strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-484"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="f01fe-485">Codice cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-485">Customer key.</span></span></li>
<li><span data-ttu-id="f01fe-486">Sviluppo di espressioni regolari personalizzate (RegEx) per tipi di informazioni riservate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-486">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="f01fe-487">Creazione o modifica di dizionari di parole chiave.</span><span class="sxs-lookup"><span data-stu-id="f01fe-487">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="f01fe-488">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-488">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f01fe-489">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="f01fe-489">Azure Purview.</span></span></li>
<li> <span data-ttu-id="f01fe-490">Revisione di documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-490">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f01fe-491">Conformità alle normative e ai requisiti di settore e regionali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-491">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f01fe-492">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-492">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="f01fe-493">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti di sistema minimi ad eccezione di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-493">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="f01fe-494"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-494"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="f01fe-495">Le responsabilità preliminari del cliente includono:</span><span class="sxs-lookup"><span data-stu-id="f01fe-495">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="f01fe-496">Elenco di percorsi di condivisione file da analizzare.</span><span class="sxs-lookup"><span data-stu-id="f01fe-496">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-497">Tassonomia di classificazione approvata.</span><span class="sxs-lookup"><span data-stu-id="f01fe-497">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="f01fe-498">Informazioni su eventuali restrizioni normative o requisiti relativi alla gestione delle chiavi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-498">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-499">Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-499">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="f01fe-500">Etichette configurate per la classificazione e la protezione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-500">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="f01fe-501">Sono presenti tutti i prerequisiti per lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-501">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="f01fe-502">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisiti per l'installazione</a>e la distribuzione dello scanner di etichettatura unificata di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-502">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="f01fe-503">Verificare che i dispositivi degli utenti esercitino un sistema operativo supportato e che siano installati i prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="f01fe-503">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="f01fe-504">Per ulteriori dettagli, vedere gli argomenti seguenti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-504">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="f01fe-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guida dell'amministratore: Installare il client di etichettatura unificata di Azure Information Protection per gli utenti</a>   </span><span class="sxs-lookup"><span data-stu-id="f01fe-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="f01fe-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="f01fe-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="f01fe-507">Installazione e configurazione del connettore Azure RMS e dei server, incluso il connettore ACTIVE Directory RMS (AD RMS) per il supporto ibrido.</span><span class="sxs-lookup"><span data-stu-id="f01fe-507">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="f01fe-508">L'installazione e la configurazione di Bring Your Own Key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificato) o Hold Your Own Key (HYOK) (solo client classico) richiede una di queste opzioni per la distribuzione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-508">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="f01fe-509"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-509"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-510">Forniamo indicazioni remote su come prepararsi a usare Intune come provider di gestione dei dispositivi mobili (MDM) e di gestione delle app per dispositivi mobili (MAM) basato su cloud per le tue app e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-510">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="f01fe-511">I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili.</span><span class="sxs-lookup"><span data-stu-id="f01fe-511">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="f01fe-512">I passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="f01fe-512">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-513">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-513">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-514">Configurazione delle identità che devono essere usate da Intune sfruttando Active Directory locale o le identità cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="f01fe-514">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-515">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-515">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-516">Configurazione dell'autorità MDM in base alle esigenze di gestione, tra cui:</span><span class="sxs-lookup"><span data-stu-id="f01fe-516">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-517">Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.</span><span class="sxs-lookup"><span data-stu-id="f01fe-517">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-518">Fornire le indicazioni di MDM per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-518">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-519">Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.</span><span class="sxs-lookup"><span data-stu-id="f01fe-519">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-520">Configurare criteri e servizi di gestione MDM come:</span><span class="sxs-lookup"><span data-stu-id="f01fe-520">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-521">Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o collegamenti diretti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-521">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-522">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-522">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-523">Distribuzione di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-523">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-524">Connessione al data warehouse di Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-524">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-525">Integrare Intune con:</span><span class="sxs-lookup"><span data-stu-id="f01fe-525">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-526">Visualizzatore team per assistenza remota (è necessaria una sottoscrizione del Visualizzatore del team).</span><span class="sxs-lookup"><span data-stu-id="f01fe-526">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-527">Soluzioni partner di Mobile Threat Defense (MTD) (è necessaria una sottoscrizione MTD).</span><span class="sxs-lookup"><span data-stu-id="f01fe-527">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-528">Una soluzione di gestione delle spese per telecomunicazioni (è necessaria una sottoscrizione a una soluzione di gestione delle spese per telecomunicazioni).</span><span class="sxs-lookup"><span data-stu-id="f01fe-528">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="f01fe-529">Registrare i dispositivi di ogni piattaforma supportata in Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-529">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="f01fe-530">Fornire indicazioni sulla protezione delle app su:</span><span class="sxs-lookup"><span data-stu-id="f01fe-530">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-531">Configurare criteri di protezione delle app per ogni piattaforma supportata.</span><span class="sxs-lookup"><span data-stu-id="f01fe-531">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-532">Configurazione dei criteri di accesso condizionale per le app gestite.</span><span class="sxs-lookup"><span data-stu-id="f01fe-532">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-533">Destinazione dei gruppi di utenti appropriati con i criteri MAM menzionati in precedenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-533">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-534">Uso dei report sull'utilizzo delle app gestite.</span><span class="sxs-lookup"><span data-stu-id="f01fe-534">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-535">Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="f01fe-535">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="f01fe-536">
 
</li>
</ul>
  
<strong>Collegamento tramite cloud</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-536">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="f01fe-537">Ti guideremo per prepararti a collegare gli ambienti di Configuration Manager esistenti con Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-537">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="f01fe-538">I passaggi esatti dipendono dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="f01fe-538">The exact steps depend on your source environment.</span></span> <span data-ttu-id="f01fe-539">Questi passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="f01fe-539">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="f01fe-540">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-540">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-541">Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.</span><span class="sxs-lookup"><span data-stu-id="f01fe-541">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-542">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-542">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-543">Fornire indicazioni per configurare l'aggiunta ad Azure AD ibrido.</span><span class="sxs-lookup"><span data-stu-id="f01fe-543">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-544">Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.</span><span class="sxs-lookup"><span data-stu-id="f01fe-544">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-545">Fornire indicazioni su come configurare il gateway di gestione cloud se usato come soluzione per la co-gestione della gestione remota dei dispositivi basati su Internet.</span><span class="sxs-lookup"><span data-stu-id="f01fe-545">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-546">Configurare i carichi di lavoro supportati che si desidera passare a Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-546">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-547">Installare il client Configuration Manager nei dispositivi registrati di Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-547">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="f01fe-548"><strong>Distribuire Outlook mobile per iOS e Android in modo sicuro</strong> È possibile fornire indicazioni per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire agli utenti che siano installate tutte le app necessarie.</span><span class="sxs-lookup"><span data-stu-id="f01fe-548"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="f01fe-549">La procedura per distribuire in modo sicuro Outlook mobile per iOS e Android con Intune dipende dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="f01fe-549">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="f01fe-550">Può includere:</span><span class="sxs-lookup"><span data-stu-id="f01fe-550">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-551">Download delle app Outlook per iOS e Android, Microsoft Authenticator e portale aziendale intune tramite Apple App Store o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="f01fe-551">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-552">Fornire indicazioni sulla configurazione:</span><span class="sxs-lookup"><span data-stu-id="f01fe-552">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-553">Distribuzione delle app Outlook per iOS e Android, Microsoft Authenticator e Intune Company Portal con Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-553">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-554">Criteri di protezione delle app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-554">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-555">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-555">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-556">Criteri di configurazione delle app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-556">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="f01fe-557">Gli amministratori IT devono disporre di un'autorità di certificazione, di una rete wireless e di infrastrutture VPN esistenti già funzionanti nei propri ambienti di produzione durante la pianificazione della distribuzione di profili VPN e di rete wireless con Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-557">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="f01fe-558"><strong>Nota:</strong>il vantaggio del servizio FastTrack non include l'assistenza per la configurazione delle autorità di certificazione, delle reti wireless, delle infrastrutture VPN o dei certificati push MDM di Apple per Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-558"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="f01fe-559"><strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud.</span><span class="sxs-lookup"><span data-stu-id="f01fe-559"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="f01fe-560">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-560">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="f01fe-561"><strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-561"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="f01fe-562"><strong>Nota:</strong>microsoft fornisce assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-562"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="f01fe-563">Non forniamo assistenza per l'acquisto, la gestione delle licenze o l'attivazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-563">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="f01fe-564">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-564">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="f01fe-565"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-565"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="f01fe-566">Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="f01fe-566">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="f01fe-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-568">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-568">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-569">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="f01fe-569">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-570">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="f01fe-570">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-571">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-571">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-572">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="f01fe-572">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f01fe-573">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="f01fe-573">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="f01fe-574">Office 365</span><span class="sxs-lookup"><span data-stu-id="f01fe-574">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f01fe-575"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-575"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f01fe-576"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-576"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f01fe-577"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-577"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f01fe-578"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-578"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-579">Per Exchange Online, viene illustrato il processo per ottenere l'organizzazione pronta per l'utilizzo della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="f01fe-579">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="f01fe-580">I passaggi esatti dipendono dall'ambiente di origine e dai piani di migrazione della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="f01fe-580">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="f01fe-581">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-581">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-582">Configurare le funzionalità di Exchange Online Protection (EOP) per tutti i domini abilitati alla posta elettronica convalidati in Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-582">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-583">Puntare i record MX (Mail Exchange) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-583">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-584">Configurazione della funzionalità Office 365 ATP se fa parte del servizio di sottoscrizione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-584">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="f01fe-585">Per ulteriori informazioni, vedere la parte relativa a <strong>Office 365 Advanced Threat Protection</strong> di questa tabella.</span><span class="sxs-lookup"><span data-stu-id="f01fe-585">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-p127">Configurare la funzionalità di prevenzione della perdita dei dati (DLP) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="f01fe-p128">Configurare Office 365 Message Encryption (OME) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="f01fe-590">
  <strong>Nota:</strong> Il servizio di replica delle cassette postali tenta di eseguire la migrazione dei messaggi di posta elettronica di Information Rights Managed (IRM) dalla cassetta postale locale alla cassetta postale di Exchange Online corrispondente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-590">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="f01fe-591">La possibilità di leggere i contenuti protetti dopo la migrazione dipende dal fatto che il cliente esegua il mapping e copi i modelli di Active Directory Rights Managed Services (AD RMS) in Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="f01fe-591">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="f01fe-592">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="f01fe-592">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-593">Configurazione di DNS, tra cui l'individuazione automatica necessaria, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) e MX records (in base alle esigenze).</span><span class="sxs-lookup"><span data-stu-id="f01fe-593">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-594">Configurare il flusso di posta elettronica tra l'ambiente di messaggistica di origine e Exchange Online (in base alle esigenze).</span><span class="sxs-lookup"><span data-stu-id="f01fe-594">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-595">Eseguire la migrazione della posta dall'ambiente di messaggistica di origine a Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-595">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-596">Configurazione di client delle cassette postali (Outlook per Windows, Outlook sul web e Outlook per iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="f01fe-596">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="f01fe-597">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="f01fe-597">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="f01fe-598">Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Migrazione dei dati.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-598">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="f01fe-599">L'ambiente di origine deve avere uno dei livelli minimi seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-599">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-600">Una o più organizzazioni di Exchange con Exchange Server 2003 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="f01fe-600">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-601">Un singolo ambiente di posta elettronica abilitato per il protocollo IMAP.</span><span class="sxs-lookup"><span data-stu-id="f01fe-601">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-602">Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).</span><span class="sxs-lookup"><span data-stu-id="f01fe-602">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-603">Per informazioni su Multi-Geo Capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-603">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="f01fe-604">Il software client online come Project per Office 365, Outlook per Windows, Outlook per iOS e Android, il client di sincronizzazione di OneDrive for Business, Power BI Desktop e Skype for Business deve essere al livello minimo, come definito in Requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-604">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="f01fe-605"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-605"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-606">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-606">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-607">Creazione e pubblicazione di etichette e criteri di conservazione (supportati solo in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-607">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="f01fe-608">Gestione dei record (supportata solo in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-608">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="f01fe-609">Revisione della creazione del piano di file.</span><span class="sxs-lookup"><span data-stu-id="f01fe-609">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="f01fe-610">Creazione e gestione di record(inclusi i record basati su eventi).</span><span class="sxs-lookup"><span data-stu-id="f01fe-610">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-611">Revisione dell'eliminazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-611">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="f01fe-612">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-612">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f01fe-613">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-613">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f01fe-614">Esame dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-614">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f01fe-615">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-615">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f01fe-616">Valutare la conformità implementando azioni di miglioramento e determinando in che modo ciò influisce sul punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-616">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f01fe-617">Analisi del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="f01fe-617">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f01fe-618">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-618">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f01fe-619">

  <strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-619">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="f01fe-620">Sviluppo di un piano di gestione dei file di record.</span><span class="sxs-lookup"><span data-stu-id="f01fe-620">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="f01fe-621">Connettori dati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-621">Data connectors.</span></span></li>
<li> <span data-ttu-id="f01fe-622">Sviluppo dell'architettura delle informazioni in SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-622">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="f01fe-623">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-623">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f01fe-624">Revisione di documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-624">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f01fe-625">Supporto per E3.</span><span class="sxs-lookup"><span data-stu-id="f01fe-625">Support for E3.</span></span></li>
<li> <span data-ttu-id="f01fe-626">Conformità alle normative e ai requisiti di settore e regionali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-626">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f01fe-627">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-627">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>


</td>
<td><span data-ttu-id="f01fe-628">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="f01fe-628">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f01fe-629"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-629"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-630">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-630">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-631">Classificazione dei dati (supportata in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-631">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-632">Tipi di informazioni riservate (supportati in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-632">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-633">Creazione di etichette di riservatezza (supportate in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-633">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-634">Applicazione di etichette di riservatezza (supportate in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-634">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-635">Classificatori trainabili (supportati in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-635">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-636">Conoscere i dati con Esplora contenuto ed Esplora attività (supportato in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-636">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-637">Pubblicazione di etichette con criteri (manuali e automatici) (supportati in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-637">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-638">Creazione di criteri di prevenzione della perdita dei dati (DLP) degli endpoint per i dispositivi Windows 10 (supportati in E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-638">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-639">Creazione di criteri DLP per chat e canali di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f01fe-639">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="f01fe-640">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-640">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="f01fe-641">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-641">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="f01fe-642">Esame dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-642">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="f01fe-643">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-643">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="f01fe-644">Valutare la conformità implementando azioni di miglioramento e determinando in che modo ciò influisce sul punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-644">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="f01fe-645">Analisi del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="f01fe-645">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="f01fe-646">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-646">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="f01fe-647">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-647">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="f01fe-648">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-648">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="f01fe-649">Attivazione e configurazione del tenant.</span><span class="sxs-lookup"><span data-stu-id="f01fe-649">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-650">Creazione e configurazione di etichette e criteri (supportati in P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f01fe-650">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-651">Applicazione della protezione delle informazioni ai documenti (supportata in P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f01fe-651">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-652">Classificare ed etichettare automaticamente le informazioni nelle app di Office (ad esempio Word, PowerPoint, Excel e Outlook) in esecuzione in Windows e con il client Azure Information Protection (supportato in P2).</span><span class="sxs-lookup"><span data-stu-id="f01fe-652">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-653">Individuazione e applicazione di etichette ai file in stato di inquieto con lo scanner di Azure Information Protection (supportato in P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="f01fe-653">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-654">Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f01fe-654">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
  
<span data-ttu-id="f01fe-655">Vengono inoltre fornite indicazioni per applicare la protezione tramite Microsoft Azure Rights Management Services (Azure RMS), Crittografia messaggi di Office 365 e prevenzione della perdita dei dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="f01fe-655">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="f01fe-656"><strong>Gli elementi seguenti non sono nell'ambito </strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-656"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="f01fe-657">Codice cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-657">Customer key.</span></span></li>
<li><span data-ttu-id="f01fe-658">Sviluppo di espressioni regolari personalizzate (RegEx) per tipi di informazioni riservate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-658">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="f01fe-659">Creazione o modifica di dizionari di parole chiave.</span><span class="sxs-lookup"><span data-stu-id="f01fe-659">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="f01fe-660">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-660">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="f01fe-661">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="f01fe-661">Azure Purview.</span></span></li>
<li> <span data-ttu-id="f01fe-662">Revisione di documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-662">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="f01fe-663">Conformità alle normative e ai requisiti di settore e regionali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-663">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="f01fe-664">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-664">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="f01fe-665">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti di sistema minimi ad eccezione di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-665">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="f01fe-666"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-666"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="f01fe-667">Le responsabilità preliminari del cliente includono:</span><span class="sxs-lookup"><span data-stu-id="f01fe-667">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="f01fe-668">Elenco di percorsi di condivisione file da analizzare.</span><span class="sxs-lookup"><span data-stu-id="f01fe-668">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-669">Tassonomia di classificazione approvata.</span><span class="sxs-lookup"><span data-stu-id="f01fe-669">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="f01fe-670">Informazioni su eventuali restrizioni normative o requisiti relativi alla gestione delle chiavi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-670">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-671">Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-671">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="f01fe-672">Etichette configurate per la classificazione e la protezione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-672">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="f01fe-673">Sono presenti tutti i prerequisiti per lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-673">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="f01fe-674">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisiti per l'installazione</a>e la distribuzione dello scanner di etichettatura unificata di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-674">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="f01fe-675">Verificare che i dispositivi degli utenti esercitino un sistema operativo supportato e che siano installati i prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="f01fe-675">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="f01fe-676">Per ulteriori dettagli, vedere gli argomenti seguenti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-676">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="f01fe-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guida dell'amministratore: Installare il client di etichettatura unificata di Azure Information Protection per gli utenti</a>   </span><span class="sxs-lookup"><span data-stu-id="f01fe-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="f01fe-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="f01fe-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="f01fe-679">Installazione e configurazione del connettore Azure RMS e dei server, incluso il connettore ACTIVE Directory RMS (AD RMS) per il supporto ibrido.</span><span class="sxs-lookup"><span data-stu-id="f01fe-679">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="f01fe-680">L'installazione e la configurazione di Bring Your Own Key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificato) o Hold Your Own Key (HYOK) (solo client classico) richiede una di queste opzioni per la distribuzione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-680">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="f01fe-681"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-681"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-682">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-682">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-683">Conferma dei requisiti minimi in Exchange Online, SharePoint Online, Gruppi di Office 365 e Azure AD per supportare Teams.</span><span class="sxs-lookup"><span data-stu-id="f01fe-683">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-684">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="f01fe-684">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-685">Configurazione di DNS.</span><span class="sxs-lookup"><span data-stu-id="f01fe-685">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-686">Conferma dell'abilitazione di Teams nel tenant Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-686">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-687">Abilitazione o disabilitazione delle licenze utente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-687">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-688">Valutazione della rete per Teams:</span><span class="sxs-lookup"><span data-stu-id="f01fe-688">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-689">Controlli di porta ed endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-689">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-690">Controlli sulla qualità della connessione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-690">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-691">Stime sulla larghezza di banda.</span><span class="sxs-lookup"><span data-stu-id="f01fe-691">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="f01fe-692">Configurazione dei criteri delle app di Teams (app Web di Teams, app Desktop di Teams e app Teams per iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="f01fe-692">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="f01fe-693">Se applicabile, forniamo anche indicazioni per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-693">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-694">Dispositivi sala di Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="f01fe-694">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="f01fe-695">Creazione di account online necessari per i dispositivi di telefonia e di sala riunioni supportati elencati nel <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogo dei dispositivi Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="f01fe-695">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-696">Assistenza remota con la configurazione lato servizio dei dispositivi Microsoft Teams Rooms certificati.</span><span class="sxs-lookup"><span data-stu-id="f01fe-696">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-697">Abilitazione dell'audioconferenza:</span><span class="sxs-lookup"><span data-stu-id="f01fe-697">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="f01fe-698">Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.</span><span class="sxs-lookup"><span data-stu-id="f01fe-698">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-699">Assegnazione di bridge per conferenze agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-699">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="f01fe-700">Sistema telefonico:</span><span class="sxs-lookup"><span data-stu-id="f01fe-700">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-701">Configurazione aziendale delle impostazioni predefinite vocali cloud.</span><span class="sxs-lookup"><span data-stu-id="f01fe-701">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-702">Linee guida per i piani di chiamata (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercati disponibili</a>):</span><span class="sxs-lookup"><span data-stu-id="f01fe-702">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-703">Assegnazione di numeri agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-703">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-704">Guida alla portabilità del numero locale tramite UI fino a 999.</span><span class="sxs-lookup"><span data-stu-id="f01fe-704">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-705">Supporto RS per la richiesta di servizio di portabilità del numero locale superiore a 999.</span><span class="sxs-lookup"><span data-stu-id="f01fe-705">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-706">Linee guida per l'instradamento diretto:</span><span class="sxs-lookup"><span data-stu-id="f01fe-706">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-707">Indicazioni per la configurazione dell'organizzazione per la progettazione del routing diretto di scenari ospitati da partner o scenari distribuiti dal cliente per un massimo di 10 siti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-707">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="f01fe-708">Verifica della configurazione di Session Border Controller (SBC).</span><span class="sxs-lookup"><span data-stu-id="f01fe-708">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="f01fe-709">Assistenza remota per la configurazione del dial plan.</span><span class="sxs-lookup"><span data-stu-id="f01fe-709">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="f01fe-710">Configurazione route vocale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-710">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="f01fe-711">Bypass multimediale e ottimizzazione multimediale locale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-711">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="f01fe-712">Abilitazione degli eventi live in Teams.</span><span class="sxs-lookup"><span data-stu-id="f01fe-712">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-713">Configurazione dell'organizzazione e integrazione in Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="f01fe-713">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-714">Indicazioni per la transizione da Skype for Business a Teams.</span><span class="sxs-lookup"><span data-stu-id="f01fe-714">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f01fe-715">Identità abilitate in Azure AD per Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-715">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-716">Utenti abilitati per SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f01fe-716">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-717">Le cassette postali di Exchange sono presenti (online e locali in una configurazione ibrida di Exchange).</span><span class="sxs-lookup"><span data-stu-id="f01fe-717">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-718">Abilitato per i gruppi di Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-718">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="f01fe-719">
  <strong>Nota:</strong> Se gli utenti non sono assegnati e abilitati con licenze di SharePoint Online, non diranno spazio di archiviazione in OneDrive for Business in Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-719">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="f01fe-720">La condivisione dei file continua a funzionare nei canali, ma gli utenti non possono condividere file nelle chat senza l'archiviazione di OneDrive for Business in Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-720">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="f01fe-721">Teams non supporta SharePoint locale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-721">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="f01fe-722">
  <strong>Nota:</strong> Lo stato ideale è che tutti gli utenti hanno le proprie cassette postali ospitate su Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f01fe-722">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="f01fe-723">Gli utenti con cassette postali ospitate in locale devono avere le proprie identità sincronizzate con la directory di Office 365 tramite Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="f01fe-723">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="f01fe-724">Per questi clienti ibridi di Exchange, se la cassetta postale dell'utente è locale, l'utente non può aggiungere o configurare i connettori.</span><span class="sxs-lookup"><span data-stu-id="f01fe-724">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="f01fe-725">I programmi di installazione per i client desktop di Microsoft Teams per Windows e Mac possono essere scaricati da <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="f01fe-725">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f01fe-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-727">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-727">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-728">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="f01fe-728">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-729">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="f01fe-729">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-730">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-730">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-731">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="f01fe-731">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f01fe-732">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="f01fe-732">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f01fe-733"><strong>Outlook per iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-733"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-734">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-734">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-735">Download di Outlook per iOS e Android tramite l'Apple App Store e Google Play.</span><span class="sxs-lookup"><span data-stu-id="f01fe-735">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-736">Configurazione degli account e accesso alla cassetta postale di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f01fe-736">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-737">Protezione di Outlook mobile (per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Protezione di Outlook per iOS e Android in Exchange Online).</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-737">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="f01fe-738">Identità abilitate in Azure AD per Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-738">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-739">Exchange Online configurato e licenze assegnate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-739">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f01fe-740"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-740"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-741">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-741">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-742">Assegnare licenze di Power BI.</span><span class="sxs-lookup"><span data-stu-id="f01fe-742">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-743">Distribuire l'app Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="f01fe-743">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f01fe-744">Il software client online come Power BI Desktop deve essere a un livello minimo, come definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-744">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f01fe-745"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-745"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-746">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-746">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-747">Verificare la funzionalità di base di SharePoint sulla quale fa affidamento Project Online.</span><span class="sxs-lookup"><span data-stu-id="f01fe-747">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-748">Aggiungere il servizio Project Online al tenant (inclusa l'aggiunta di sottoscrizioni per gli utenti).</span><span class="sxs-lookup"><span data-stu-id="f01fe-748">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-749">Configurare il pool di risorse organizzazione (ERP).</span><span class="sxs-lookup"><span data-stu-id="f01fe-749">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-750">Creare il primo progetto.</span><span class="sxs-lookup"><span data-stu-id="f01fe-750">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f01fe-751">Il software client online come Project per Office 365 deve essere al livello minimo, come definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-751">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f01fe-752"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-752"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-753">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-753">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-754">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-754">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-755">Assegnare i contratti di licenza con l'utente finale utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f01fe-755">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-756">Installare Client desktop di Project Online dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="f01fe-756">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-757">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-757">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-758">Configurare un unico server di distribuzione nel sito per Client desktop di Project Online, includendo una guida per la creazione del file configuration.xml da usare con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-758">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-759">Connettere Client desktop di Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="f01fe-759">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f01fe-760">Il software client online come Project per Office 365 deve essere al livello minimo, come definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-760">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f01fe-761"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-761"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-762">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-762">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-763">Configurazione DNS.</span><span class="sxs-lookup"><span data-stu-id="f01fe-763">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-764">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="f01fe-764">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-765">Provisioning di utenti e licenze.</span><span class="sxs-lookup"><span data-stu-id="f01fe-765">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="f01fe-766">Abilitazione alla creazione di siti per l'amministratore di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f01fe-766">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="f01fe-767">Pianificazione delle raccolte di siti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-767">Planning site collections.</span></span></li>
<li><span data-ttu-id="f01fe-768">Protezione del contenuto e gestione delle autorizzazioni.</span><span class="sxs-lookup"><span data-stu-id="f01fe-768">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="f01fe-769">Configurazione delle caratteristiche di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f01fe-769">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="f01fe-770">Configurazione delle funzionalità dell'ambiente ibrido di SharePoint, come la ricerca ibrida, i siti ibridi, la tassonomia ibrida, i tipi di contenuto, la creazione siti in modalità self-service ibrida (solo SharePoint Server 2013), l'icona di avvio delle app estesa, OneDrive for Business ibrido e i siti extranet.</span><span class="sxs-lookup"><span data-stu-id="f01fe-770">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-771">L'approccio alla migrazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-771">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="f01fe-772">Vengono fornite indicazioni aggiuntive per OneDrive for Business a seconda della versione di SharePoint, ad esempio:</span><span class="sxs-lookup"><span data-stu-id="f01fe-772">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-773">Identificazione delle opzioni di integrazione e revisione dell'infrastruttura di rete locale e online e della larghezza di banda.</span><span class="sxs-lookup"><span data-stu-id="f01fe-773">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-774">Installazione di SharePoint Online 2013 SP1 (se applicabile), pianificazione e implementazione dei requisiti di sincronizzazione e identità e identificazione del client di sincronizzazione di OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="f01fe-774">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-775">Pianificazione e implementazione di una singola implementazione per tutti gli utenti (o un'implementazione in più fasi).</span><span class="sxs-lookup"><span data-stu-id="f01fe-775">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-776">Assegnazione di licenze, reindirizzamento di siti personali e raccolte documenti personali a Office 365 (applicabile a SharePoint Online 2013), configurazione dei gruppi di destinatari per controllare l'accesso a OneDrive (applicabile a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="f01fe-776">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="f01fe-777">Reindirizzamento o spostamento di cartelle note in OneDrive.</span><span class="sxs-lookup"><span data-stu-id="f01fe-777">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="f01fe-778">Distribuzione della sincronizzazione del client OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="f01fe-778">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="f01fe-779">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="f01fe-779">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="f01fe-780">Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Migrazione dei dati.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-780">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="f01fe-781"><strong>Per SharePoint ibrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-781"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="f01fe-782">La configurazione ibrida di SharePoint include la configurazione di ricerca ibrida, siti, tassonomia, tipi di contenuto, OneDrive for Business, un'icona di avvio delle app estesa, siti Extranet e creazione di siti in modalità self-service connessi dall'ambiente locale a un singolo ambiente SharePoint Online di destinazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-782">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="f01fe-783">
  <strong>Nota:</strong> La creazione di siti in modalità self-service non è nell'ambito dei server locali che eseguono SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="f01fe-783">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="f01fe-784">Per abilitare l'ambiente ibrido di SharePoint, è necessario disporre di uno dei seguenti ambienti SharePoint Server locali: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="f01fe-784">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="f01fe-785">
  <strong>Nota:</strong> L'aggiornamento degli ambienti SharePoint locali a SharePoint Server non è nell'ambito.</span><span class="sxs-lookup"><span data-stu-id="f01fe-785">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="f01fe-786">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="f01fe-787">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=853548">Livelli di aggiornamento pubblico minimi per le funzionalità ibride di SharePoint.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="f01fe-787">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="f01fe-788">
  <strong>Nota:</strong> Per informazioni su Multi-Geo Capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive e SharePoint Online in Office 365.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="f01fe-788">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f01fe-789"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-789"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="f01fe-790">Vengono fornite indicazioni remote per l'abilitazione del servizio Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f01fe-790">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="f01fe-791">Il software client online deve essere al livello minimo definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-791">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="f01fe-792">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="f01fe-792">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f01fe-793"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-793"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f01fe-794"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-794"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f01fe-795"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-795"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="f01fe-796"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-796"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-797">Vengono fornite indicazioni remote per la protezione delle identità cloud per gli scenari seguenti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-797">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="f01fe-798">

<strong>Infrastruttura di base protetta</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="f01fe-798">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="f01fe-799">Configurazione e abilitazione dell'autenticazione avanzata per le identità, inclusa la protezione con Azure Multi-Factor Authentication (MFA) (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure MFA e la reimpostazione della password self-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="f01fe-799">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-800">Per i clienti non di Azure AD Premium, vengono fornite indicazioni per proteggere le identità usando le impostazioni predefinite di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-800">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-801">Per i clienti premium di Azure AD, vengono fornite indicazioni per proteggere le identità con l'accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-801">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-802">Rilevamento e blocco dell'uso di password deboli con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-802">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-803">Protezione dell'accesso remoto alle app Web locali con il proxy dell'applicazione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-803">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-804">Abilitazione del rilevamento e della correzione basata sui rischi con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="f01fe-804">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-805">Abilitazione di una schermata di accesso personalizzata, inclusi logo, testo e immagini con personalizzazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-805">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-806">Condivisione sicura di app e servizi con utenti guest con Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="f01fe-806">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-807">Gestione dell'accesso per gli amministratori di Office 365 tramite i ruoli amministrativi incorporati del controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-807">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-808">Configurazione dell'aggiunta ad Azure AD ibrido.</span><span class="sxs-lookup"><span data-stu-id="f01fe-808">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-809">Configurazione dell'aggiunta ad Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-809">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="f01fe-810">
  
<strong>Monitoraggio e creazione di report</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-810">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f01fe-811">Abilitazione del monitoraggio remoto per AD FS, Azure AD Connect e controller di dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="f01fe-811">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="f01fe-812">
  
<strong>Governance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-812">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f01fe-813">Gestione del ciclo di vita delle identità e degli accessi di Azure AD su vasta scala con la gestione dei diritti di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-813">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="f01fe-814">Gestione dell'appartenenza ai gruppi di Azure AD, dell'accesso alle app aziendali e delle assegnazioni dei ruoli con le verifiche di accesso di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-814">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-815">Esame delle Condizioni per l'utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-815">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-816">Gestione e controllo dell'accesso agli account amministratore con privilegi con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="f01fe-816">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="f01fe-817">
  
<strong>Automazione ed efficienza </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-817">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f01fe-818">Abilitazione di Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="f01fe-818">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="f01fe-819">Consentire agli utenti di creare e gestire la propria sicurezza cloud o i gruppi di Office 365 con la gestione dei gruppi self-service di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-819">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-820">Gestione dell'accesso delegato alle app aziendali con la gestione dei gruppi delegati di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-820">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-821">Abilitazione dei gruppi dinamici di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="f01fe-821">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-822">Organizzazione delle app nel portale App personali tramite raccolte.</span><span class="sxs-lookup"><span data-stu-id="f01fe-822">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="f01fe-823">Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione dei problemi identificati che impediscono l'integrazione con le funzionalità di Azure AD e Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="f01fe-823">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f01fe-824"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-824"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="f01fe-825">Per altre informazioni su Azure Information Protection, vedere <strong>Microsoft Information Protection</strong> in Sicurezza e <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> conformità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-825">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="f01fe-826"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-826"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-827">Forniamo indicazioni remote su come prepararsi a usare Intune come provider di gestione dei dispositivi mobili (MDM) e di gestione delle app per dispositivi mobili (MAM) basato su cloud per le tue app e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-827">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="f01fe-828">I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili.</span><span class="sxs-lookup"><span data-stu-id="f01fe-828">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="f01fe-829">I passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="f01fe-829">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-830">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-830">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-831">Configurazione delle identità che devono essere usate da Intune sfruttando Active Directory locale o le identità cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="f01fe-831">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-832">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-832">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-833">Configurazione dell'autorità MDM in base alle esigenze di gestione, tra cui:</span><span class="sxs-lookup"><span data-stu-id="f01fe-833">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-834">Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.</span><span class="sxs-lookup"><span data-stu-id="f01fe-834">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-835">Fornire le indicazioni di MDM per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-835">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-836">Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.</span><span class="sxs-lookup"><span data-stu-id="f01fe-836">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-837">Configurare criteri e servizi di gestione MDM come:</span><span class="sxs-lookup"><span data-stu-id="f01fe-837">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-838">Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o collegamenti diretti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-838">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-839">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-839">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-840">Distribuzione di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-840">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-841">Connessione al data warehouse di Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-841">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-842">Integrare Intune con:</span><span class="sxs-lookup"><span data-stu-id="f01fe-842">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-843">Visualizzatore team per assistenza remota (è necessaria una sottoscrizione del Visualizzatore del team).</span><span class="sxs-lookup"><span data-stu-id="f01fe-843">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-844">Soluzioni partner di Mobile Threat Defense (MTD) (è necessaria una sottoscrizione MTD).</span><span class="sxs-lookup"><span data-stu-id="f01fe-844">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-845">Una soluzione di gestione delle spese per telecomunicazioni (è necessaria una sottoscrizione a una soluzione di gestione delle spese per telecomunicazioni).</span><span class="sxs-lookup"><span data-stu-id="f01fe-845">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-846">Registrare i dispositivi di ogni piattaforma supportata in Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-846">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="f01fe-847">Fornire indicazioni sulla protezione delle app su:</span><span class="sxs-lookup"><span data-stu-id="f01fe-847">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-848">Configurare criteri di protezione delle app per ogni piattaforma supportata.</span><span class="sxs-lookup"><span data-stu-id="f01fe-848">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-849">Configurazione dei criteri di accesso condizionale per le app gestite.</span><span class="sxs-lookup"><span data-stu-id="f01fe-849">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-850">Destinazione dei gruppi di utenti appropriati con i criteri MAM menzionati in precedenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-850">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-851">Uso dei report sull'utilizzo delle app gestite.</span><span class="sxs-lookup"><span data-stu-id="f01fe-851">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-852">Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="f01fe-852">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="f01fe-853">
  
</li>
</ul>
  
<strong>Collegamento tramite cloud</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-853">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="f01fe-854">Ti guideremo per prepararti a collegare gli ambienti di Configuration Manager esistenti con Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-854">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="f01fe-855">I passaggi esatti dipendono dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="f01fe-855">The exact steps depend on your source environment.</span></span> <span data-ttu-id="f01fe-856">Questi passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="f01fe-856">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="f01fe-857">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="f01fe-857">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-858">Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.</span><span class="sxs-lookup"><span data-stu-id="f01fe-858">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-859">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-859">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-860">Fornire indicazioni per configurare l'aggiunta ad Azure AD ibrido.</span><span class="sxs-lookup"><span data-stu-id="f01fe-860">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-861">Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.</span><span class="sxs-lookup"><span data-stu-id="f01fe-861">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-862">Fornire indicazioni su come configurare il gateway di gestione cloud se usato come soluzione per la co-gestione della gestione remota dei dispositivi basati su Internet.</span><span class="sxs-lookup"><span data-stu-id="f01fe-862">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-863">Configurare i carichi di lavoro supportati che si desidera passare a Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-863">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-864">Installare il client Configuration Manager nei dispositivi registrati di Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-864">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="f01fe-865"><strong>Distribuire Outlook mobile per iOS e Android in modo sicuro</strong> È possibile fornire indicazioni per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire agli utenti che siano installate tutte le app necessarie.</span><span class="sxs-lookup"><span data-stu-id="f01fe-865"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="f01fe-866">La procedura per distribuire in modo sicuro Outlook mobile per iOS e Android con Intune dipende dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="f01fe-866">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="f01fe-867">Può includere:</span><span class="sxs-lookup"><span data-stu-id="f01fe-867">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-868">Download delle app Outlook per iOS e Android, Microsoft Authenticator e portale aziendale intune tramite Apple App Store o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="f01fe-868">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-869">Fornire indicazioni sulla configurazione:</span><span class="sxs-lookup"><span data-stu-id="f01fe-869">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-870">Distribuzione delle app Outlook per iOS e Android, Microsoft Authenticator e Intune Company Portal con Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-870">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-871">Criteri di protezione delle app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-871">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-872">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-872">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-873">Criteri di configurazione delle app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-873">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="f01fe-874">Gli amministratori IT devono disporre di un'autorità di certificazione, di una rete wireless e di infrastrutture VPN esistenti già funzionanti nei propri ambienti di produzione durante la pianificazione della distribuzione di profili VPN e di rete wireless con Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-874">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="f01fe-875"><strong>Nota:</strong>il vantaggio del servizio FastTrack non include l'assistenza per la configurazione delle autorità di certificazione, delle reti wireless, delle infrastrutture VPN o dei certificati push MDM di Apple per Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-875"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="f01fe-876"><strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud.</span><span class="sxs-lookup"><span data-stu-id="f01fe-876"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="f01fe-877">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="f01fe-878"><strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-878"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="f01fe-879"><strong>Nota:</strong>microsoft fornisce assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-879"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="f01fe-880">Non forniamo assistenza per l'acquisto, la gestione delle licenze o l'attivazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-880">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="f01fe-881">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-881">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="f01fe-882"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-882"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="f01fe-883">Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="f01fe-883">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="f01fe-884">Windows 10</span><span class="sxs-lookup"><span data-stu-id="f01fe-884">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f01fe-885"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-885"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f01fe-886"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-886"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f01fe-887"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-887"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f01fe-888"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-888"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-889">Forniamo indicazioni per l'aggiornamento da Windows 7 Professional e Windows 8.1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f01fe-889">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="f01fe-890">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-890">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-891">Informazioni sull'intenzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-891">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-892">Valutazione dell'ambiente di origine e dei requisiti (assicurarsi che Microsoft Endpoint Configuration Manager sia aggiornato al livello necessario per supportare la distribuzione di Windows 10).</span><span class="sxs-lookup"><span data-stu-id="f01fe-892">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-893">Distribuzione di Windows 10 Enterprise e Microsoft 365 Apps con Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-893">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-894">Opzioni consigliate per valutare le tue app di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-894">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-895">Abilitazione dell'uso di Desktop Analytics e indicazioni tramite la creazione di un piano di distribuzione di Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="f01fe-895">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-896">Valutazione della compatibilità di Microsoft 365 Apps sfruttando il dashboard di preparazione di Office 365 in Configuration Manager o con readiness Toolkit per Office autonomo e assistenza per la distribuzione di Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f01fe-896">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-897">Creazione di un elenco di controllo per la correzione delle operazioni necessarie per portare l'ambiente di origine ai requisiti minimi per una distribuzione corretta.</span><span class="sxs-lookup"><span data-stu-id="f01fe-897">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-898">Fornire indicazioni per l'aggiornamento dei dispositivi esistenti a Windows 10 Enterprise se soddisfano i requisiti hardware dei dispositivi necessari.</span><span class="sxs-lookup"><span data-stu-id="f01fe-898">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-899">Fornire indicazioni sull'aggiornamento per supportare il movimento di distribuzione esistente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-899">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="f01fe-900">FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-900">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="f01fe-901">Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="f01fe-901">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-902">Distribuzione di Microsoft 365 Apps con Configuration Manager nell'ambito della distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-902">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="f01fe-903">Fornire indicazioni per aiutare l'organizzazione a rimanere aggiornata con Windows 10 Enterprise e Microsoft 365 Apps usando l'ambiente Configuration Manager esistente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-903">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="f01fe-904">
  <strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-904">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f01fe-905">Aggiornamento di Configuration Manager al Current Branch.</span><span class="sxs-lookup"><span data-stu-id="f01fe-905">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-906">Creazione di immagini personalizzate per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-906">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-907">Creazione e supporto degli script di distribuzione per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-907">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-908">Conversione di un sistema di Windows 10 dal BIOS a Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="f01fe-908">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-909">Abilitare le funzionalità di sicurezza di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-909">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-910">Configurazione di Windows Deployment Services (WDS) per il boot di Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="f01fe-910">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-911">Uso di Microsoft Deployment Toolkit (MDT) per acquisire e distribuire immagini di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-911">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-912">Uso dell’Utilità di migrazione dello stato utente (USMT).</span><span class="sxs-lookup"><span data-stu-id="f01fe-912">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="f01fe-913">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-913">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="f01fe-914">Per l'aggiornamento del PC, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-914">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-915">Sistema operativo di origine: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="f01fe-915">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-916">Dispositivi: fattore di forma per desktop, notebook o tablet.</span><span class="sxs-lookup"><span data-stu-id="f01fe-916">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-917">Sistema operativo di destinazione: Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="f01fe-917">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="f01fe-918">Per l'aggiornamento dell'infrastruttura, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-918">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-919">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-919">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-920">La versione di Configuration Manager deve essere supportata dalla versione di destinazione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-920">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="f01fe-921">Per altre informazioni, vedere la tabella di supporto di Configuration Manager in <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Supporto per Windows 10 in Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="f01fe-921">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="f01fe-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-923">Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-923">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="f01fe-924">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-924">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-925">Distribuzione delle tecnologie per proteggere gli endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-925">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-926">Configurazione dei profili di protezione degli endpoint e delle restrizioni dei dispositivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-926">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-927">Valutazione della versione del sistema operativo e della gestione dei dispositivi (inclusi Intune, Microsoft Endpoint Configuration Manager, oggetti Criteri di gruppo e configurazioni di terze parti), nonché lo stato dei servizi av di Windows Defender o di altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-927">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-928">Valutazione dello stato dei servizi Windows AV o di altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-928">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-929">Valutazione dei proxy e dei firewall che limitano il traffico di rete.</span><span class="sxs-lookup"><span data-stu-id="f01fe-929">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-930">Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo agente ATP con un endpoint di onboarding.</span><span class="sxs-lookup"><span data-stu-id="f01fe-930">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-931">Linee guida per la distribuzione, assistenza alla configurazione ed istruzione su:</span><span class="sxs-lookup"><span data-stu-id="f01fe-931">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-932">Gestione delle minacce e delle vulnerabilità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-932">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-933">Riduzione della superficie di attacco.</span><span class="sxs-lookup"><span data-stu-id="f01fe-933">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-934">Protezione di nuova generazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-934">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-935">Rilevamento e risposta degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="f01fe-935">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-936">Indagine e correzione automatizzate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-936">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="f01fe-937">Microsoft Defender ATP (sono necessarie licenze di Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="f01fe-937">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="f01fe-938">Punteggio di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="f01fe-938">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-939">Revisione di simulazioni ed esercitazioni (come scenari di pratica, malware falso e indagini automatizzate).</span><span class="sxs-lookup"><span data-stu-id="f01fe-939">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-940">Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="f01fe-940">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-941">Integrazione di Office 365 ATP con Microsoft Defender ATP.</span><span class="sxs-lookup"><span data-stu-id="f01fe-941">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-942">Procedure dettagliate nel portale di Microsoft Defender Security Center.</span><span class="sxs-lookup"><span data-stu-id="f01fe-942">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-943">I sistemi operativi seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-943">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-944">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-944">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-945">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="f01fe-945">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-946">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="f01fe-946">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-947">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="f01fe-947">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-948">Windows Server Semi-Annual Channel (SAC) versione 1803.</span><span class="sxs-lookup"><span data-stu-id="f01fe-948">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-949">macOS versioni 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="f01fe-949">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="f01fe-950">
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versione 2002 o successiva).</span><span class="sxs-lookup"><span data-stu-id="f01fe-950">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="f01fe-951"></li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-951"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f01fe-952">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-952">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-953">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="f01fe-953">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-954">Gestione continua e risposta alle minacce.</span><span class="sxs-lookup"><span data-stu-id="f01fe-954">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-955">Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-955">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-956">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="f01fe-956">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-957">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="f01fe-957">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-958">Linux.</span><span class="sxs-lookup"><span data-stu-id="f01fe-958">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-959">Dispositivi mobili (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="f01fe-959">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="f01fe-960">Virtual Desktop Infrastructure (VDI) (persistente o non persistente).</span><span class="sxs-lookup"><span data-stu-id="f01fe-960">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-961">Onboarding e configurazione del server:</span><span class="sxs-lookup"><span data-stu-id="f01fe-961">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-962">Configurazione di un server proxy per le comunicazioni offline.</span><span class="sxs-lookup"><span data-stu-id="f01fe-962">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-963">Configurazione dei pacchetti di distribuzione di Configuration Manager nelle istanze e nelle versioni di Configuration Manager di livello inferiore.</span><span class="sxs-lookup"><span data-stu-id="f01fe-963">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-964">Onboarding dei server nel Centro sicurezza di Azure.</span><span class="sxs-lookup"><span data-stu-id="f01fe-964">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-965">Server non gestiti da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f01fe-965">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-966">Onboarding e configurazione di macOS:</span><span class="sxs-lookup"><span data-stu-id="f01fe-966">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-967">Distribuzione manuale basata su Intune.</span><span class="sxs-lookup"><span data-stu-id="f01fe-967">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-968">Distribuzione basata su JAMF.</span><span class="sxs-lookup"><span data-stu-id="f01fe-968">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="f01fe-969">Altra distribuzione basata sul prodotto di gestione dei dispositivi mobili (MDM).</span><span class="sxs-lookup"><span data-stu-id="f01fe-969">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-970">Distribuzione manuale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-970">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="f01fe-971">Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-971">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-972">Isolamento basato su hardware.</span><span class="sxs-lookup"><span data-stu-id="f01fe-972">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-973">Controllo dell'app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-973">App control.</span></span>  
  </li>
<li> <span data-ttu-id="f01fe-974">Controllo dispositivo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-974">Device control.</span></span></li>
<li>  
  <span data-ttu-id="f01fe-975">Protezione dagli exploit.</span><span class="sxs-lookup"><span data-stu-id="f01fe-975">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-976">Firewall di rete.</span><span class="sxs-lookup"><span data-stu-id="f01fe-976">Network firewall.</span></span>  
  </li>

<ul>
<li> <span data-ttu-id="f01fe-977">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="f01fe-977">Windows Hello</span></span></li>
<li> <span data-ttu-id="f01fe-978">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="f01fe-978">Credential Guard</span></span></li>
</ul>

</ul></li>
<li> <span data-ttu-id="f01fe-979">Configurazione o gestione di BitLocker.</span><span class="sxs-lookup"><span data-stu-id="f01fe-979">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="f01fe-980">Iscrizione o configurazione di Microsoft Threat Experts.</span><span class="sxs-lookup"><span data-stu-id="f01fe-980">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-981">Configurazione o formazione che esamina le connessioni API o siem (Security Information and Event Management).</span><span class="sxs-lookup"><span data-stu-id="f01fe-981">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-982">Iscrizione o configurazione di Microsoft Threat Protection (MTP).</span><span class="sxs-lookup"><span data-stu-id="f01fe-982">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-983">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="f01fe-983">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-984">Formazione o indicazioni su come usare o creare query Kusto.</span><span class="sxs-lookup"><span data-stu-id="f01fe-984">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="f01fe-985">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-985">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="f01fe-986">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="f01fe-986">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f01fe-987"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-987"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f01fe-988"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-988"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f01fe-989"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-989"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f01fe-990"><strong>Desktop virtuale Windows</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-990"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="f01fe-991">Forniamo indicazioni sulla distribuzione per l'onboarding in Desktop virtuale Windows (un servizio di virtualizzazione di desktop e app).</span><span class="sxs-lookup"><span data-stu-id="f01fe-991">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="f01fe-992">Desktop virtuale Windows sfrutta l'esperienza multi-sessione di Windows 10 ed è ottimizzato per Microsoft 365 Apps for Enterprise con sicurezza e gestione integrate per Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f01fe-992">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="f01fe-993">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-993">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="f01fe-994">Distribuzione dell'ambiente Desktop virtuale Windows con Windows 10 Enterprise multi-sessione e Microsoft 365 Apps for Enterprise con gli strumenti seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-994">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="f01fe-995">Immagine di Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="f01fe-995">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="f01fe-996">Immagine condivisa.</span><span class="sxs-lookup"><span data-stu-id="f01fe-996">Shared image.</span></span></li>
<li><span data-ttu-id="f01fe-997">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="f01fe-997">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="f01fe-998">Configurazione di FSLogix:</span><span class="sxs-lookup"><span data-stu-id="f01fe-998">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="f01fe-999">Distribuzione dell'agente FSLogix con il contenitore dei profili.</span><span class="sxs-lookup"><span data-stu-id="f01fe-999">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="f01fe-1000">Distribuzione dell'agente FSLogix con contenitore di Office.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1000">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="f01fe-1001">Configurazione della cartella FSLogix con esclusioni di contenuto.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1001">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="f01fe-1002">Distribuzione di Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1002">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="f01fe-1003">Distribuzione di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1003">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="f01fe-1004">Connessione tramite client Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1004">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="f01fe-1005">

<strong>Gli elementi seguenti non sono nell'ambito</strong>
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1005">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="f01fe-1006">Gestione dei progetti della distribuzione di Desktop virtuale Windows del cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1006">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="f01fe-1007">Virtualizzazione e distribuzione di app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1007">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="f01fe-1008">Immagini personalizzate.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1008">Custom images.</span></span></li>
<li><span data-ttu-id="f01fe-1009">Migrazioni e scenari che coinvolgono VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1009">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="f01fe-1010">Scenari Linux.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1010">Linux scenarios.</span></span></li>
<li><span data-ttu-id="f01fe-1011">Conversione o migrazione dei profili utente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1011">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="f01fe-1012">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1012">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="f01fe-1013">È necessario disporre già di quanto segue:</span><span class="sxs-lookup"><span data-stu-id="f01fe-1013">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="f01fe-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisiti di licenza di Desktop virtuale Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="f01fe-1015">Rete di Azure:</span><span class="sxs-lookup"><span data-stu-id="f01fe-1015">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="f01fe-1016">Creazione e subnetting della rete virtuale (VNET).</span><span class="sxs-lookup"><span data-stu-id="f01fe-1016">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="f01fe-1017">Gruppi di sicurezza firewall e di rete.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1017">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="f01fe-1018">VPN ed ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1018">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="f01fe-1019">Routing ad Azure dall'ambiente locale.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1019">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="f01fe-1020">Regole del firewall per consentire la connettività a Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1020">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="f01fe-1021">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Client Desktop remoto supportati.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-1021">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="f01fe-1022">Configurazione generale di Azure AD:</span><span class="sxs-lookup"><span data-stu-id="f01fe-1022">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="f01fe-1023">Strategia di <i>identità (è possibile utilizzare solo una delle tre opzioni seguenti):</i>
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1023">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="f01fe-1024">Active Directory con Azure AD Connect in Azure.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1024">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="f01fe-1025">Active Directory con Azure AD Connect locale tramite VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1025">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="f01fe-1026">Servizi di dominio Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1026">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="f01fe-1027">App Assure</span><span class="sxs-lookup"><span data-stu-id="f01fe-1027">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f01fe-1028"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-1028"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f01fe-1029"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-1029"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f01fe-1030"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-1030"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="f01fe-1031"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-1031"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="f01fe-1032">App Assure è un servizio progettato per risolvere i problemi di compatibilità delle app di Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1032">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="f01fe-1033">Quando richiedi il servizio App Assure, microsoft lavora con te per risolvere i problemi validi dell'app senza costi aggiuntivi con un abbonamento idoneo.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1033">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="f01fe-1034">Forniamo anche indicazioni ai clienti che devono affrontare problemi di compatibilità durante la distribuzione di Desktop virtuale Windows e Microsoft Edge e facciamo ogni sforzo ragionevole per risolvere i problemi di compatibilità.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1034">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="f01fe-1035">Forniamo assistenza per la correzione per le app distribuite nei prodotti Microsoft seguenti:</span><span class="sxs-lookup"><span data-stu-id="f01fe-1035">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="f01fe-1036"><strong>Windows 10 </strong> (inclusi i dispositivi ARM64)</span><span class="sxs-lookup"><span data-stu-id="f01fe-1036"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="f01fe-1037"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="f01fe-1037"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="f01fe-1038"><strong>Microsoft Edge -</strong> Per indicazioni sulla distribuzione, vedere <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Panoramica dei canali di Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-1038"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-1039"><strong>Desktop virtuale</strong> - Windows Per altre informazioni, vedi <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Che cos'è Desktop virtuale Windows?</a> e Domande frequenti su <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-sessione.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-1039"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="f01fe-1040">

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1040">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="f01fe-p147">Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro di distribuzione desktop</a>. Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito <a href="https://go.microsoft.com/fwlink/?linkid=2053818">modulo</a>.</span><span class="sxs-lookup"><span data-stu-id="f01fe-p147">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="f01fe-1044">Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1044">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="f01fe-1045">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1045">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="f01fe-1046">Servizi di sola creazione di pacchetti di app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1046">App packaging-only services.</span></span> <span data-ttu-id="f01fe-1047">Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1047">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="f01fe-1048">

<strong>Le responsabilità del cliente includono</strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1048">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="f01fe-1049">Creazione di un inventario delle app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1049">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="f01fe-1050">Convalida di tali app in Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1050">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="f01fe-1051">
<strong>Nota:</strong>  Microsoft non può apportare modifiche al codice sorgente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1051">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="f01fe-1052">Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1052">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="f01fe-1053">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1053">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="f01fe-1054"><strong>Windows 10 e Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1054"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="f01fe-1055">Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1055">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="f01fe-1056">
<strong>Windows 10 in ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1056">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="f01fe-1057">Le app che hanno funzionato in Windows 7, Office 2010 o versioni successive funzionano anche in Windows 10 e Microsoft 365 Apps nei dispositivi ARM64.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1057">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="f01fe-1058">
  <strong>Nota:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1058">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="f01fe-1059">L'emulazione x64 (64 bit) è disponibile in anteprima per i clienti che partecipano al <a href="https://insider.windows.com/">Programma Windows Insider.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-1059">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="f01fe-1060">Per i clienti non Windows Insider con Windows 10 versione 2004 (o successiva), ARM64 Photoshop è supportato con OpenCL e <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-1060">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="f01fe-1061">I clienti del Programma Windows Insider possono scaricare una versione Insider del pacchetto di compatibilità OpenCL e OpenGL da usare con altre app.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1061">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="f01fe-1062">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1062">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="f01fe-1063">Se le app o i siti Web funzionano in Internet Explorer 11, nelle versioni supportate di Google Chrome o in qualsiasi versione di Microsoft Edge, funzionano anche con Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1063">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-1064">Poiché il Web è in continua evoluzione, assicurarsi di leggere questo elenco pubblicato delle modifiche note che influiscono sulla compatibilità dei siti <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">per Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-1064">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="f01fe-1065">
  <strong>Desktop virtuale Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1065">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="f01fe-1066">Applicazioni virtualizzate che vengono eseguite su Windows Server Remote Desktop Session Host (RDSH) vengono eseguite anche nella multisessione di Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1066">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-1067">Le app in esecuzione in qualsiasi ambiente VDI (Virtual Desktop Infrastructure) di Windows 7 o Windows 10 vengono eseguite anche in Windows 7 Enterprise e Windows 10 Enterprise come parte di Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1067">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-1068">Le app che vengono eseguite su dispostivi client di Windows 7 o Windows 10, vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1068">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="f01fe-1069">
  <strong>Nota:</strong> Le esclusioni e le limitazioni per la compatibilità con più sessioni di Windows 10 Enterprise includono:</span><span class="sxs-lookup"><span data-stu-id="f01fe-1069">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="f01fe-1070">Reindirizzamento limitato dell'hardware.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1070">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-1071">Le app con uso intensivo di A/V possono essere eseguite a una capacità ridotta.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1071">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="f01fe-1072">Le app a 16 bit non sono supportate per la versione Desktop virtuale Windows a 64 bit.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1072">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="f01fe-1073">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="f01fe-1073">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f01fe-1074"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-1074"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="f01fe-1075"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-1075"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="f01fe-1076"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="f01fe-1076"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="f01fe-1077"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="f01fe-1077"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="f01fe-1078">Forniamo indicazioni per la distribuzione remota e l'adozione e assistenza per la compatibilità per:</span><span class="sxs-lookup"><span data-stu-id="f01fe-1078">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="f01fe-1079">Distribuzione di Microsoft Edge in Windows 10 con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="f01fe-1079">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-1080">Configurazione di Microsoft Edge (tramite criteri di gruppo o la configurazione delle app di Intune e i criteri delle app).</span><span class="sxs-lookup"><span data-stu-id="f01fe-1080">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="f01fe-1081">Inventario dell'elenco di siti che potrebbero richiedere l'uso in modalità Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1081">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="f01fe-1082">Abilitazione della modalità Internet Explorer con l'elenco di siti dell'organizzazione esistente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1082">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="f01fe-1083">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Coinvolgimento di FastTrack.</a></span><span class="sxs-lookup"><span data-stu-id="f01fe-1083">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="f01fe-1084">Inoltre, se si dispone di un'app Web o di un sito che funziona con Internet Explorer o Google Chrome e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema senza costi aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1084">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="f01fe-1085">Per richiedere il supporto della compatibilità per App Assure, accedi al portale <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack</a> per avviare un'interazione.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1085">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="f01fe-1086">Indicazioni sulla pianificazione per l'adozione di Edge e la configurazione dei segnalibri di Microsoft Search.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1086">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="f01fe-1087">

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="f01fe-1087">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="f01fe-1088">Gestione dei progetti per la distribuzione di Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1088">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="f01fe-1089">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="f01fe-1089">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
