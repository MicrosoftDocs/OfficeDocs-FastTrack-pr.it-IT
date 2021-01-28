---
title: Prodotti e funzionalità
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che resegni l'ambiente di origine ai requisiti minimi per l'onboarding corretto.
ms.openlocfilehash: abbc97a7b2d70b0b0111f1cbe96904bbe552e463
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016688"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="662e1-104">Prodotti e funzionalità</span><span class="sxs-lookup"><span data-stu-id="662e1-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="662e1-105">Servizi e scenari supportati da FastTrack</span><span class="sxs-lookup"><span data-stu-id="662e1-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="662e1-106">Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di iniziare.</span><span class="sxs-lookup"><span data-stu-id="662e1-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="662e1-107">In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che resegni l'ambiente di origine fino ai requisiti minimi per l'onboarding corretto.</span><span class="sxs-lookup"><span data-stu-id="662e1-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="662e1-108">FastTrack fornisce indicazioni per aiutarti prima con le funzionalità di base (comuni per tutti i Microsoft Online Services) e quindi con l'onboarding di ogni servizio idoneo:</span><span class="sxs-lookup"><span data-stu-id="662e1-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="662e1-109">Generale</span><span class="sxs-lookup"><span data-stu-id="662e1-109">General</span></span>](#general)
  - [<span data-ttu-id="662e1-110">Sicurezza e conformità</span><span class="sxs-lookup"><span data-stu-id="662e1-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="662e1-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="662e1-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="662e1-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="662e1-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="662e1-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="662e1-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="662e1-114">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="662e1-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="662e1-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="662e1-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="662e1-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="662e1-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="662e1-117">Per informazioni sulle previsioni dell’ambiente di origine di Office 365 U.S. Government, vedere [Previsioni dell’ambiente di origine di Office 365 U.S. Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="662e1-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="662e1-118">Generale</span><span class="sxs-lookup"><span data-stu-id="662e1-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="662e1-119"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="662e1-120"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="662e1-121"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="662e1-122"><strong>Onboarding di base</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="662e1-123">Forniamo indicazioni remote sull'onboarding di base, che implica il provisioning dei servizi, il tenant e l'integrazione delle identità.</span><span class="sxs-lookup"><span data-stu-id="662e1-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="662e1-124">Include inoltre la procedura per fornire una base per i servizi di onboarding come Exchange Online, SharePoint Online e Microsoft Teams, inclusa una discussione su sicurezza, connettività di rete <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">e conformità.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="662e1-125">L'onboarding per uno o più servizi può iniziare al termine dell'onboarding di base.</span><span class="sxs-lookup"><span data-stu-id="662e1-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="662e1-126"></li>
</ul>  

<strong> Integrazione delle identità </strong></span><span class="sxs-lookup"><span data-stu-id="662e1-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="662e1-127">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="662e1-128">Preparazione delle identità di Active Directory locali per la sincronizzazione con Azure Active Directory (Azure AD), tra cui l'installazione e la configurazione di Azure AD Connect (a foresta singola o multipla) e delle licenze (incluse le licenze basate su gruppo).</span><span class="sxs-lookup"><span data-stu-id="662e1-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="662e1-129">Creazione di identità cloud, tra cui importazione in blocco e licenze, incluso l'uso delle licenze basate su gruppo.</span><span class="sxs-lookup"><span data-stu-id="662e1-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="662e1-130">Scelta e abilitazione del metodo di autenticazione corretto per il percorso cloud, Sincronizzazione hash password, Autenticazione pass-through o Active Directory Federation Services (AD FS).</span><span class="sxs-lookup"><span data-stu-id="662e1-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="662e1-131">Abilitazione di AD FS per i clienti con una singola foresta di Active Directory e identità sincronizzate con lo strumento Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="662e1-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="662e1-132">Questa operazione richiede Windows Server 2012 R2 Active Directory Federation Services 2.0 o versione successiva.</span><span class="sxs-lookup"><span data-stu-id="662e1-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="662e1-133">Migrazione dell'autenticazione da AD FS ad Azure AD tramite la sincronizzazione hash delle password o l'autenticazione pass-through.</span><span class="sxs-lookup"><span data-stu-id="662e1-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="662e1-134">Migrazione di app pre-integrate (come le app SaaS (Software-as-a-Service) della raccolta di Azure AD da AD FS ad Azure AD per Single #A0 (SSO).</span><span class="sxs-lookup"><span data-stu-id="662e1-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="662e1-135">Abilitazione delle integrazioni di app SaaS con SSO dalla raccolta di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="662e1-136">Abilitazione del provisioning automatico degli utenti per le app SaaS pre-integrate, come indicato nell'elenco delle esercitazioni sull'integrazione delle <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">app</a> (limitato alle app SaaS della raccolta di Azure AD e solo al provisioning in uscita).</span><span class="sxs-lookup"><span data-stu-id="662e1-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="662e1-137"><strong>Abilitazione della rete </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="662e1-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="662e1-138">Nell'ambito del vantaggio FastTrack, si consiglia di utilizzare le procedure consigliate per la connessione ai servizi cloud per garantire i livelli più elevati di prestazioni di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="662e1-139"><strong>Foreste di Active Directory</strong> Il livello di foresta funzionale è impostato su Windows Server 2003 e successive, con la seguente configurazione della foresta:</span><span class="sxs-lookup"><span data-stu-id="662e1-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-140">Una foresta unica di Active Directory.</span><span class="sxs-lookup"><span data-stu-id="662e1-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="662e1-141">Una singola foresta account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="662e1-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-142">Più foreste account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="662e1-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-143">Più foreste account di Active Directory con una delle foreste in posizione centrale nella foresta account di Active Directory contenente Exchange e/o Lync 2010, Lync 2013 o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="662e1-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="662e1-144">Più foreste account di Active Directory, ognuna con la propria organizzazione di Exchange.</span><span class="sxs-lookup"><span data-stu-id="662e1-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="662e1-145">Attività necessarie per la configurazione e l'integrazione del tenant con Azure Active Directory, se necessario.</span><span class="sxs-lookup"><span data-stu-id="662e1-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="662e1-146">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="662e1-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="662e1-147">Per gli scenari di Active Directory a più foreste, se lync 2010, Lync 2013 o Skype for Business è distribuito, deve essere distribuito nella stessa foresta di Active Directory di Exchange.</span><span class="sxs-lookup"><span data-stu-id="662e1-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="662e1-148">Quando si implementano più foreste di Active Directory con più organizzazioni Exchange in una configurazione multi-ibrida di Exchange, gli spazi dei nomi dell'entità utente (UPN) condivisi tra foreste di origine non sono supportati.</span><span class="sxs-lookup"><span data-stu-id="662e1-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="662e1-149">Gli spazi dei nomi SMTP primari tra organizzazioni di Exchange devono essere separati.</span><span class="sxs-lookup"><span data-stu-id="662e1-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="662e1-150">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=845444">Distribuzioni ibride con più insiemi di strutture di Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="662e1-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="662e1-151">Per tutte le configurazioni di più foreste, la distribuzione di Active Directory Federation Services (AD FS) non è in ambito.</span><span class="sxs-lookup"><span data-stu-id="662e1-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="662e1-152">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="662e1-153"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="662e1-154">Vengono fornite indicazioni per la distribuzione remota per:</span><span class="sxs-lookup"><span data-stu-id="662e1-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-155">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="662e1-156">Assegnazione dei contratti di licenza con l'utente finale e di licenze basate sul dispositivo utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="662e1-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="662e1-157">Installare Microsoft 365 Apps dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="662e1-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="662e1-158">Installazione delle app di Office Mobile (ad esempio Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) sui dispositivi iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="662e1-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="662e1-159">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="662e1-160">Selezione e configurazione di un'installazione locale o cloud.</span><span class="sxs-lookup"><span data-stu-id="662e1-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="662e1-161">Creazione del codice XML di configurazione dello Strumento di distribuzione di Office con lo Strumento di personalizzazione di Office o del codice XML nativo per configurare il pacchetto di distribuzione.</span><span class="sxs-lookup"><span data-stu-id="662e1-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="662e1-162">Distribuzione con Microsoft Endpoint Configuration Manager, che include una guida per la creazione del pacchetto di Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="662e1-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="662e1-163">Inoltre, se si dispone di una macro o di un componente aggiuntivo che funzionava con le versioni precedenti di Office e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema di compatibilità senza costi aggiuntivi tramite il programma App Assure.</span><span class="sxs-lookup"><span data-stu-id="662e1-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="662e1-164">Per altri <strong>dettagli,</strong> vedi la parte App Assure di <a href="#windows-10">Windows 10.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="662e1-165">Il software client online deve essere al livello minimo definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="662e1-166"><strong>Integrità della rete</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="662e1-167">Forniamo indicazioni remote per ottenere e interpretare i dati di connettività di rete chiave dall'ambiente in uso che mostrano quanto i siti dell'organizzazione sono allineati ai principi di connettività <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">di rete di</a>Microsoft.</span><span class="sxs-lookup"><span data-stu-id="662e1-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="662e1-168">Questo evidenzia il punteggio di rete che influisce direttamente sulla velocità della migrazione, sull'esperienza utente, sulle prestazioni del servizio e sull'affidabilità.</span><span class="sxs-lookup"><span data-stu-id="662e1-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="662e1-169">Ti guideremo anche attraverso qualsiasi procedura di correzione evidenziata da questi dati per aiutarti a migliorare il punteggio di rete.</span><span class="sxs-lookup"><span data-stu-id="662e1-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="662e1-170">Accesso all'interfaccia di amministrazione di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="662e1-171">Sono necessarie versioni aggiornate delle app di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="662e1-172">Servizi percorso abilitati in base ai suggerimenti sulle prestazioni di rete nell'interfaccia di amministrazione di <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 (anteprima).</a></span><span class="sxs-lookup"><span data-stu-id="662e1-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="662e1-173">Sicurezza e conformità</span><span class="sxs-lookup"><span data-stu-id="662e1-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="662e1-174"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="662e1-175"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="662e1-176"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="662e1-177"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="662e1-178">Vengono fornite indicazioni remote per la protezione delle identità cloud per gli scenari seguenti.</span><span class="sxs-lookup"><span data-stu-id="662e1-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="662e1-179">

<strong>Infrastruttura di base protetta</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="662e1-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="662e1-180">Configurazione e abilitazione dell'autenticazione avanzata per le identità, inclusa la protezione con Azure Multi-Factor Authentication (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure MFA e la reimpostazione della password self-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="662e1-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="662e1-181">Per i clienti non di Azure AD Premium, vengono fornite indicazioni per proteggere le identità usando le impostazioni predefinite di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="662e1-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="662e1-182">Per i clienti premium di Azure AD, vengono fornite indicazioni per proteggere le identità con l'accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="662e1-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="662e1-183">Rilevamento e blocco dell'uso di password deboli con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="662e1-184">Protezione dell'accesso remoto alle app Web locali con il proxy dell'applicazione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="662e1-185">Abilitazione del rilevamento e della correzione in base al rischio con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="662e1-186">Abilitazione di una schermata di accesso personalizzata, inclusi logo, testo e immagini con personalizzazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="662e1-187">Condivisione sicura di app e servizi con utenti guest con Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="662e1-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="662e1-188">Gestione dell'accesso per gli amministratori di Office 365 tramite i ruoli amministrativi incorporati del controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.</span><span class="sxs-lookup"><span data-stu-id="662e1-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="662e1-189">Configurazione dell'aggiunta ad Azure AD ibrido.</span><span class="sxs-lookup"><span data-stu-id="662e1-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="662e1-190">Configurazione dell'aggiunta ad Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="662e1-191">
  
<strong>Monitoraggio e creazione di report</strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="662e1-192">Abilitazione del monitoraggio remoto per AD FS, Azure AD Connect e controller di dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="662e1-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="662e1-193">
  
<strong>Governance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="662e1-194">Gestione del ciclo di vita delle identità e degli accessi di Azure AD su vasta scala con la gestione dei diritti di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="662e1-195">Gestione dell'appartenenza ai gruppi di Azure AD, dell'accesso alle app aziendali e delle assegnazioni dei ruoli con le verifiche di accesso di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-196">Esame delle Condizioni per l'utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-197">Gestione e controllo dell'accesso agli account amministratore con privilegi con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="662e1-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="662e1-198">
  
<strong>Automazione ed efficienza </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="662e1-199">Abilitazione di Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="662e1-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="662e1-200">Consentire agli utenti di creare e gestire la propria sicurezza cloud o i gruppi di Office 365 con la gestione dei gruppi self-service di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-201">Gestione dell'accesso delegato alle app aziendali con la gestione dei gruppi delegati di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-202">Abilitazione dei gruppi dinamici di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="662e1-203">Organizzazione delle app nel portale App personali tramite raccolte.</span><span class="sxs-lookup"><span data-stu-id="662e1-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="662e1-204">Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione dei problemi identificati che impediscono l'integrazione con le funzionalità di Azure AD e Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="662e1-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="662e1-205"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="662e1-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="662e1-206">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-206">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-207">Attivazione e configurazione del tenant.</span><span class="sxs-lookup"><span data-stu-id="662e1-207">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="662e1-208">Creare e configurare etichette e criteri.</span><span class="sxs-lookup"><span data-stu-id="662e1-208">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-209">Applicare la protezione delle informazioni ai documenti.</span><span class="sxs-lookup"><span data-stu-id="662e1-209">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="662e1-210">Classificare ed etichettare automaticamente le informazioni nelle app di Office, come Word, PowerPoint, Excel e Outlook, che eseguono Windows e con il client di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-210">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="662e1-211">Individuazione e applicazione di etichette ai file in stato di inquieto con lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-211">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="662e1-212">Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="662e1-212">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="662e1-213">Vengono inoltre fornite indicazioni per applicare la protezione tramite Microsoft Azure Rights Management Services (Azure RMS), Crittografia messaggi di Office 365 e prevenzione della perdita dei dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="662e1-213">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="662e1-214">Le responsabilità preliminari del cliente includono:</span><span class="sxs-lookup"><span data-stu-id="662e1-214">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-215">Elenco di percorsi di condivisione file da analizzare.</span><span class="sxs-lookup"><span data-stu-id="662e1-215">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="662e1-216">Tassonomia di classificazione approvata.</span><span class="sxs-lookup"><span data-stu-id="662e1-216">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="662e1-217">Informazioni su eventuali restrizioni normative o requisiti relativi alla gestione delle chiavi.</span><span class="sxs-lookup"><span data-stu-id="662e1-217">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-218">Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-218">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="662e1-219">Etichette configurate per la classificazione e la protezione.</span><span class="sxs-lookup"><span data-stu-id="662e1-219">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="662e1-220">Sono presenti tutti i prerequisiti per lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-220">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="662e1-221">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisiti per l'installazione</a>e la distribuzione dello scanner di etichettatura unificata di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-221">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="662e1-222">Verificare che i dispositivi degli utenti esercitino un sistema operativo supportato e che siano installati i prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="662e1-222">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="662e1-223">Per ulteriori dettagli, vedere gli argomenti seguenti.</span><span class="sxs-lookup"><span data-stu-id="662e1-223">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="662e1-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guida dell'amministratore: Installare il client di etichettatura unificata di Azure Information Protection per gli utenti</a>   </span><span class="sxs-lookup"><span data-stu-id="662e1-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="662e1-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="662e1-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="662e1-226">Installazione e configurazione del connettore Azure RMS e dei server, incluso il connettore ACTIVE Directory RMS (AD RMS) per il supporto ibrido.</span><span class="sxs-lookup"><span data-stu-id="662e1-226">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="662e1-227">L'installazione e la configurazione di Bring Your Own Key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificato) o Hold Your Own Key (HYOK) (solo client classico) richiede una di queste opzioni per la distribuzione.</span><span class="sxs-lookup"><span data-stu-id="662e1-227">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="662e1-228"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-228"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="662e1-229">Microsoft 365 Defender è una famiglia di prodotti di difesa aziendale pre e post-violazione unificata che coordina in modo nativo il rilevamento, la prevenzione, l'indagine e la risposta tra endpoint, identità, posta elettronica e app per fornire una protezione integrata da attacchi sofisticati.</span><span class="sxs-lookup"><span data-stu-id="662e1-229">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="662e1-230">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-230">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="662e1-231">Panoramica del Centro sicurezza Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-231">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="662e1-232">Esame degli incidenti tra prodotti, inclusa l'attenzione su ciò che è critico, garantendo l'ambito completo degli attacchi, le risorse influenzate e le azioni di correzione automatizzate raggruppate.</span><span class="sxs-lookup"><span data-stu-id="662e1-232">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="662e1-233">Dimostrazione del modo in cui Microsoft 365 Defender può orchestrare l'analisi di risorse, utenti, dispositivi e cassette postali che potrebbero essere state compromesse tramite l'auto-riparazione automatica.</span><span class="sxs-lookup"><span data-stu-id="662e1-233">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="662e1-234">Spiegare e fornire esempi di come i clienti possono cercare in modo proattivo tentativi di intrusione e attività di violazione che influiscono su posta elettronica, dati, dispositivi e account in più set di dati.</span><span class="sxs-lookup"><span data-stu-id="662e1-234">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="662e1-235">Mostrare ai clienti come possono esaminare e migliorare la loro posizione di sicurezza in modo olistico con Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="662e1-235">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="662e1-236"><strong>Gli elementi seguenti non sono nell'ambito</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-236"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="662e1-237">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-237">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="662e1-238">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="662e1-238">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="662e1-239">Linee guida per la distribuzione o formazione su:</span><span class="sxs-lookup"><span data-stu-id="662e1-239">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="662e1-240">Come correggere o interpretare i vari tipi di avviso e le attività monitorate.</span><span class="sxs-lookup"><span data-stu-id="662e1-240">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="662e1-241">Come analizzare un utente, un computer, un percorso di spostamento laterale o un'entità.</span><span class="sxs-lookup"><span data-stu-id="662e1-241">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="662e1-242">Ricerca personalizzata delle minacce.</span><span class="sxs-lookup"><span data-stu-id="662e1-242">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="662e1-243">Integrazione DIEM (Security Information and Event Management) o API.</span><span class="sxs-lookup"><span data-stu-id="662e1-243">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="662e1-244"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-244"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="662e1-245">Microsoft Cloud App Security è un Cloud Access Security Broker (CASB) che offre visibilità completa, controllo sui viaggi dei dati e analisi sofisticate per identificare e contrastare le minacce informatiche in tutti i servizi cloud Microsoft e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="662e1-245">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="662e1-246">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-246">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-247">Configurazione del portale, tra cui:</span><span class="sxs-lookup"><span data-stu-id="662e1-247">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="662e1-248">Importazione di gruppi di utenti.</span><span class="sxs-lookup"><span data-stu-id="662e1-248">Importing user groups.</span></span></li>
<li> <span data-ttu-id="662e1-249">Gestione dell'accesso e delle impostazioni dell'amministratore.</span><span class="sxs-lookup"><span data-stu-id="662e1-249">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="662e1-250">Definizione dell'ambito della distribuzione per selezionare determinati gruppi di utenti da monitorare o escludere dal monitoraggio.</span><span class="sxs-lookup"><span data-stu-id="662e1-250">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="662e1-251">Impostazione di intervalli e tag IP.</span><span class="sxs-lookup"><span data-stu-id="662e1-251">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="662e1-252">Personalizzazione dell'esperienza dell'utente finale con il logo e la messaggistica personalizzata.</span><span class="sxs-lookup"><span data-stu-id="662e1-252">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="662e1-253">Configurare l'individuazione cloud per fornire shadow IT tramite:</span><span class="sxs-lookup"><span data-stu-id="662e1-253">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="662e1-254">Microsoft Defender per gli endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-254">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="662e1-255">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="662e1-255">Zscaler.</span></span></li>
<li> <span data-ttu-id="662e1-256">iboss.</span><span class="sxs-lookup"><span data-stu-id="662e1-256">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="662e1-257">Connessione <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">di app in primo</a> piano tramite connettori di app.</span><span class="sxs-lookup"><span data-stu-id="662e1-257">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="662e1-258">Configurazione del controllo dell'app di accesso condizionale nei portali di Accesso condizionale e Cloud App Security per applicare i controlli delle sessioni in tempo reale.</span><span class="sxs-lookup"><span data-stu-id="662e1-258">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="662e1-259">Distribuzione dei dashboard cloud App Security e Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="662e1-259">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="662e1-260">Personalizzazione dei punteggi di rischio delle app in base alle priorità dell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-260">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="662e1-261">Creazione di tag e categorie dell'app.</span><span class="sxs-lookup"><span data-stu-id="662e1-261">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="662e1-262">App che sanzionano e annullano l'associazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-262">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="662e1-263">Uso di attività e log di file.</span><span class="sxs-lookup"><span data-stu-id="662e1-263">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="662e1-264">Gestione delle app OAuth.</span><span class="sxs-lookup"><span data-stu-id="662e1-264">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="662e1-265">Informazioni sulla correlazione degli eventi imprevisti nel portale di Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="662e1-265">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="662e1-266">Fornire assistenza alla configurazione con i <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> casi d'uso principali per i casb (inclusa la creazione o l'aggiornamento di un massimo di sei (6) criteri), ad eccezione di:</span><span class="sxs-lookup"><span data-stu-id="662e1-266">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="662e1-267">Controllo della configurazione degli ambienti IaaS (Internet as a Service) (#18).</span><span class="sxs-lookup"><span data-stu-id="662e1-267">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="662e1-268">Monitoraggio delle attività degli utenti per la protezione dalle minacce negli ambienti IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="662e1-268">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="662e1-269"><strong>Gli elementi seguenti non sono nell'ambito</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-269"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="662e1-270">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-270">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="662e1-271">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="662e1-271">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="662e1-272">Configurazione dell'infrastruttura, dell'installazione o della distribuzione dei caricamenti automatici dei log per i report continui tramite Docker o un agente di raccolta log.</span><span class="sxs-lookup"><span data-stu-id="662e1-272">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="662e1-273">Per <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">ulteriori informazioni, vedere i 20 casi</a> di utilizzo principali per i casb.</span><span class="sxs-lookup"><span data-stu-id="662e1-273">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="662e1-274">Creazione di un report snapshot di Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="662e1-274">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="662e1-275">Blocco dell'utilizzo dell'app tramite script di blocco.</span><span class="sxs-lookup"><span data-stu-id="662e1-275">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="662e1-276">Connessione di app personalizzate.</span><span class="sxs-lookup"><span data-stu-id="662e1-276">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="662e1-277">Integrazione con provider di identità (IsP) di terze parti e provider di prevenzione della perdita di dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="662e1-277">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="662e1-278">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="662e1-278">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="662e1-279">Analisi e correzione automatizzate, inclusi i playbook di Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="662e1-279">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="662e1-280">Integrazione delle API e delle informazioni di sicurezza (SIEM, Security Information and Event Management) (incluso Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="662e1-280">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="662e1-281">Distribuzione di Cloud App Discovery come modello di prova.</span><span class="sxs-lookup"><span data-stu-id="662e1-281">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="662e1-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="662e1-283">Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.</span><span class="sxs-lookup"><span data-stu-id="662e1-283">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="662e1-284">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-285">Distribuzione delle tecnologie per proteggere gli endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-285">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="662e1-286">Configurazione dei profili di protezione degli endpoint e delle restrizioni dei dispositivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-286">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="662e1-287">Valutazione della versione del sistema operativo e della gestione dei dispositivi (inclusi Intune, Microsoft Endpoint Configuration Manager, oggetti Criteri di gruppo e configurazioni di terze parti), nonché lo stato dei servizi av di Windows Defender o di altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-287">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="662e1-288">Valutazione dello stato dei servizi Windows AV o di altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-288">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="662e1-289">Valutazione dei proxy e dei firewall che limitano il traffico di rete.</span><span class="sxs-lookup"><span data-stu-id="662e1-289">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="662e1-290">Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo agente ATP con un endpoint di onboarding.</span><span class="sxs-lookup"><span data-stu-id="662e1-290">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="662e1-291">Linee guida per la distribuzione, assistenza alla configurazione ed istruzione su:</span><span class="sxs-lookup"><span data-stu-id="662e1-291">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-292">Gestione delle minacce e delle vulnerabilità.</span><span class="sxs-lookup"><span data-stu-id="662e1-292">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-293">Riduzione della superficie di attacco.</span><span class="sxs-lookup"><span data-stu-id="662e1-293">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-294">Protezione di nuova generazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-294">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-295">Rilevamento e risposta degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-295">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-296">Indagine e correzione automatizzate.</span><span class="sxs-lookup"><span data-stu-id="662e1-296">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-297">Punteggio di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="662e1-297">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-298">Esame di simulazioni ed esercitazioni (come scenari di pratica, malware falso e indagini automatizzate).</span><span class="sxs-lookup"><span data-stu-id="662e1-298">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="662e1-299">Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="662e1-299">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="662e1-300">Integrazione di Office 365 ATP con Microsoft Defender ATP.</span><span class="sxs-lookup"><span data-stu-id="662e1-300">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="662e1-301">Procedure dettagliate nel portale di Microsoft Defender Security Center.</span><span class="sxs-lookup"><span data-stu-id="662e1-301">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="662e1-302">I sistemi operativi seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-302">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-303">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-303">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-304">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="662e1-304">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-305">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="662e1-305">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-306">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="662e1-306">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-307">Windows Server Semi-Annual Channel (SAC) versione 1803.</span><span class="sxs-lookup"><span data-stu-id="662e1-307">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-308">macOS versioni 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="662e1-308">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="662e1-309">
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versione 2002 o successiva).</span><span class="sxs-lookup"><span data-stu-id="662e1-309">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="662e1-310"></li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-310"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="662e1-311">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-311">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="662e1-312">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="662e1-312">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="662e1-313">Gestione continua e risposta alle minacce.</span><span class="sxs-lookup"><span data-stu-id="662e1-313">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="662e1-314">Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-314">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-315">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="662e1-315">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-316">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="662e1-316">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-317">Linux.</span><span class="sxs-lookup"><span data-stu-id="662e1-317">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-318">Dispositivi mobili (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="662e1-318">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-319">Onboarding e configurazione del server:</span><span class="sxs-lookup"><span data-stu-id="662e1-319">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-320">Configurazione di un server proxy per le comunicazioni offline.</span><span class="sxs-lookup"><span data-stu-id="662e1-320">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-321">Configurazione dei pacchetti di distribuzione di Configuration Manager nelle istanze e nelle versioni di Configuration Manager di livello inferiore.</span><span class="sxs-lookup"><span data-stu-id="662e1-321">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-322">Onboarding dei server nel Centro sicurezza di Azure.</span><span class="sxs-lookup"><span data-stu-id="662e1-322">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-323">Server non gestiti da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="662e1-323">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-324">Onboarding e configurazione di macOS:</span><span class="sxs-lookup"><span data-stu-id="662e1-324">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-325">Distribuzione manuale basata su Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-325">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-326">Distribuzione basata su JAMF.</span><span class="sxs-lookup"><span data-stu-id="662e1-326">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="662e1-327">Altra distribuzione basata sul prodotto di gestione dei dispositivi mobili (MDM).</span><span class="sxs-lookup"><span data-stu-id="662e1-327">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-328">Distribuzione manuale.</span><span class="sxs-lookup"><span data-stu-id="662e1-328">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-329">Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-329">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-330">Isolamento basato su hardware.</span><span class="sxs-lookup"><span data-stu-id="662e1-330">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-331">Controllo dell'app.</span><span class="sxs-lookup"><span data-stu-id="662e1-331">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-332">Protezione dagli exploit.</span><span class="sxs-lookup"><span data-stu-id="662e1-332">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-333">Firewall di rete.</span><span class="sxs-lookup"><span data-stu-id="662e1-333">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-334">Iscrizione o configurazione di Microsoft Threat Experts.</span><span class="sxs-lookup"><span data-stu-id="662e1-334">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="662e1-335">Configurazione o formazione che esamina le connessioni API o siem (Security Information and Event Management).</span><span class="sxs-lookup"><span data-stu-id="662e1-335">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="662e1-336">Iscrizione o configurazione di Microsoft Threat Protection (MTP).</span><span class="sxs-lookup"><span data-stu-id="662e1-336">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="662e1-337">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="662e1-337">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="662e1-338">Formazione o indicazioni su come usare o creare query Kusto.</span><span class="sxs-lookup"><span data-stu-id="662e1-338">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="662e1-339">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="662e1-339">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="662e1-340"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="662e1-340"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="662e1-341">Microsoft Defender per identità è una soluzione di sicurezza basata sul cloud che sfrutta i segnali di Active Directory locali per identificare, rilevare e analizzare minacce avanzate, identità compromesse ed azioni Insider dannose dirette all'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-341">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="662e1-342">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-342">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="662e1-343">Creazione dell'istanza di Defender per l'identità.</span><span class="sxs-lookup"><span data-stu-id="662e1-343">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="662e1-344">Connessione di Defender per l'identità ad Active Directory.</span><span class="sxs-lookup"><span data-stu-id="662e1-344">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="662e1-345">Valutazione della preparazione dell'ambiente per la distribuzione del sensore Defender for Identity nei controller di dominio, tra cui:</span><span class="sxs-lookup"><span data-stu-id="662e1-345">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="662e1-346">Esecuzione dello strumento di dimensionamento per la pianificazione della capacità delle risorse.</span><span class="sxs-lookup"><span data-stu-id="662e1-346">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="662e1-347">Esecuzione dello strumento di controllo per valutare la compatibilità dei controller di dominio con il sensore.</span><span class="sxs-lookup"><span data-stu-id="662e1-347">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="662e1-348">Distribuzione del sensore per acquisire e analizzare il traffico di rete e gli eventi di Windows direttamente dai controller di dominio, tra cui:</span><span class="sxs-lookup"><span data-stu-id="662e1-348">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="662e1-349">Download del pacchetto del sensore.</span><span class="sxs-lookup"><span data-stu-id="662e1-349">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="662e1-350">Configurazione del sensore.</span><span class="sxs-lookup"><span data-stu-id="662e1-350">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="662e1-351">Installazione del sensore nel controller di dominio in modo invisibile all'utente.</span><span class="sxs-lookup"><span data-stu-id="662e1-351">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="662e1-352">Distribuzione del sensore nell'ambiente a più foreste.</span><span class="sxs-lookup"><span data-stu-id="662e1-352">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="662e1-353">Integrazione di Defender per l'identità con Microsoft Cloud App Security (la licenza di Cloud App Security non è necessaria).</span><span class="sxs-lookup"><span data-stu-id="662e1-353">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="662e1-354">Fornire indicazioni sulla distribuzione, assistenza alla configurazione ed istruzione su:</span><span class="sxs-lookup"><span data-stu-id="662e1-354">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="662e1-355">Ottimizzazione dell'ambiente per ridurre il "rumore".</span><span class="sxs-lookup"><span data-stu-id="662e1-355">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="662e1-356">Informazioni sul report di valutazione della postura di sicurezza delle identità.</span><span class="sxs-lookup"><span data-stu-id="662e1-356">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="662e1-357">Informazioni sul punteggio di priorità dell'indagine utente e sul report di classificazione delle indagini degli utenti.</span><span class="sxs-lookup"><span data-stu-id="662e1-357">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="662e1-358">Informazioni sul report degli utenti inattivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-358">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="662e1-359">Fornire opzioni di correzione per un account compromesso.</span><span class="sxs-lookup"><span data-stu-id="662e1-359">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="662e1-360">Facilitare la migrazione da Advanced Threat Analytics (ATA) a Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="662e1-360">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="662e1-361"><strong>Gli elementi seguenti non sono nell'ambito</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-361"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="662e1-362">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-362">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="662e1-363">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="662e1-363">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="662e1-364">Distribuzione del sensore Defender for Identity, tra cui:</span><span class="sxs-lookup"><span data-stu-id="662e1-364">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="662e1-365">Pianificazione manuale della capacità.</span><span class="sxs-lookup"><span data-stu-id="662e1-365">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="662e1-366">Distribuzione del sensore in una capacità autonoma.</span><span class="sxs-lookup"><span data-stu-id="662e1-366">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="662e1-367">Distribuzione del sensore con una scheda nic (Network Interface Card) Del teaming.</span><span class="sxs-lookup"><span data-stu-id="662e1-367">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="662e1-368">Distribuzione del sensore tramite uno strumento di terze parti.</span><span class="sxs-lookup"><span data-stu-id="662e1-368">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="662e1-369">Connessione al servizio cloud Defender for Identity tramite una connessione proxy Web.</span><span class="sxs-lookup"><span data-stu-id="662e1-369">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="662e1-370">Creazione e gestione di honeytoken.</span><span class="sxs-lookup"><span data-stu-id="662e1-370">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="662e1-371">Linee guida per la distribuzione o formazione su:</span><span class="sxs-lookup"><span data-stu-id="662e1-371">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="662e1-372">Correzione o interpretazione di vari tipi di avviso e attività monitorate.</span><span class="sxs-lookup"><span data-stu-id="662e1-372">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="662e1-373">Analisi di un utente, di un computer, di un percorso di spostamento laterale o di un'entità.</span><span class="sxs-lookup"><span data-stu-id="662e1-373">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="662e1-374">Minaccia o ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="662e1-374">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="662e1-375">Risposta a un evento imprevisto.</span><span class="sxs-lookup"><span data-stu-id="662e1-375">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="662e1-376">Esercitazione del laboratorio di avviso di sicurezza per Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="662e1-376">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="662e1-377">Fornire una notifica quando Defender for Identity rileva attività sospette inviando avvisi di sicurezza al server syslog tramite un sensore designato.</span><span class="sxs-lookup"><span data-stu-id="662e1-377">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="662e1-378">Configurazione di Defender per l'identità per eseguire query utilizzando il protocollo samr (Security Account Manager Remote) per identificare gli amministratori locali in computer specifici.</span><span class="sxs-lookup"><span data-stu-id="662e1-378">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="662e1-379">Configurazione di soluzioni VPN per aggiungere informazioni dalla connessione VPN alla pagina del profilo di un utente.</span><span class="sxs-lookup"><span data-stu-id="662e1-379">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="662e1-380">Integrazione delle API e delle informazioni di sicurezza (SIEM, Security Information and Event Management) (incluso Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="662e1-380">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="662e1-381">Distribuzione di Defender per i sensori di identità come modello di prova.</span><span class="sxs-lookup"><span data-stu-id="662e1-381">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="662e1-382">Distribuzione di Active Directory.</span><span class="sxs-lookup"><span data-stu-id="662e1-382">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="662e1-383">I controller di dominio in cui intendi installare Defender per i sensori di identità dispongono di connettività Internet al servizio cloud Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="662e1-383">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="662e1-384">Il firewall e il proxy devono essere aperti per comunicare con il servizio cloud Defender for Identity (\*.atp.azure.com la porta 443 deve essere aperta).</span><span class="sxs-lookup"><span data-stu-id="662e1-384">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="662e1-385">Controller di dominio in esecuzione in uno dei seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-385">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="662e1-386">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="662e1-386">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="662e1-387">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="662e1-387">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="662e1-388">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="662e1-388">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="662e1-389">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="662e1-389">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="662e1-390">Windows Server 2019 con KB4487044 (OS Build 17763.316).</span><span class="sxs-lookup"><span data-stu-id="662e1-390">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="662e1-391"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-391"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="662e1-392">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-392">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-393">Etichette e criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-393">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-394">Gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="662e1-394">Records management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-395">Criteri di eliminazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-395">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-396">Conformità delle comunicazioni.</span><span class="sxs-lookup"><span data-stu-id="662e1-396">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="662e1-397">Gestione dei rischi Insider.</span><span class="sxs-lookup"><span data-stu-id="662e1-397">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-398">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="662e1-398">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="662e1-399">

  <strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-399">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="662e1-400">Sviluppo di un piano di gestione dei file di record.</span><span class="sxs-lookup"><span data-stu-id="662e1-400">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="662e1-401">Connettori dati.</span><span class="sxs-lookup"><span data-stu-id="662e1-401">Data connectors.</span></span></li>
<li> <span data-ttu-id="662e1-402">Barriere in fatto di informazioni.</span><span class="sxs-lookup"><span data-stu-id="662e1-402">Information barriers.</span></span></li>
<li> <span data-ttu-id="662e1-403">Gestione degli accessi con privilegi.</span><span class="sxs-lookup"><span data-stu-id="662e1-403">Privileged access management.</span></span></li>
<li> <span data-ttu-id="662e1-404">Sviluppo dell'architettura delle informazioni in SharePoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-404">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="662e1-405">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="662e1-405">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="662e1-406">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="662e1-406">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="662e1-407"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-407"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="662e1-408">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-408">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-409">Classificazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="662e1-409">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="662e1-410">Tipi di informazioni sensibili.</span><span class="sxs-lookup"><span data-stu-id="662e1-410">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="662e1-411">Creare etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="662e1-411">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="662e1-412">Applicazione di etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="662e1-412">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="662e1-413">Etichettatura unificata.</span><span class="sxs-lookup"><span data-stu-id="662e1-413">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="662e1-414">Classificatori sottoponibili a formazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-414">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="662e1-415">Conoscere i dati tramite Esplora contenuto ed Esplora attività.</span><span class="sxs-lookup"><span data-stu-id="662e1-415">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="662e1-416">Pubblicare etichette con criteri (manuale e automatico).</span><span class="sxs-lookup"><span data-stu-id="662e1-416">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="662e1-417">Creare criteri di prevenzione della perdita dei dati (DLP) per chat e canali di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="662e1-417">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="662e1-418">Creazione di criteri endpoint DLP per i dispositivi Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-418">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="662e1-419">

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-419">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="662e1-420">Codice cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-420">Customer key.</span></span></li>
<li><span data-ttu-id="662e1-421">Sviluppo di espressioni regolari personalizzate (RegEx) per tipi di informazioni riservate.</span><span class="sxs-lookup"><span data-stu-id="662e1-421">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="662e1-422">Creazione o modifica di dizionari di parole chiave.</span><span class="sxs-lookup"><span data-stu-id="662e1-422">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="662e1-423">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="662e1-423">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="662e1-424">
<strong>Nota:</strong> Per ulteriori informazioni, vedere <strong>Azure Information Protection</strong> in Enterprise Mobility + <a href="#enterprise-mobility--security">Security.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-424">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="662e1-425">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="662e1-425">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="662e1-426"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-426"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="662e1-427">Forniamo indicazioni remote su come prepararsi a usare Intune come provider di gestione dei dispositivi mobili (MDM) e di gestione delle app per dispositivi mobili (MAM) basato su cloud per le tue app e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-427">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="662e1-428">I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili.</span><span class="sxs-lookup"><span data-stu-id="662e1-428">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="662e1-429">I passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="662e1-429">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-430">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="662e1-430">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="662e1-431">Configurazione delle identità che devono essere usate da Intune sfruttando Active Directory locale o le identità cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="662e1-431">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="662e1-432">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-432">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="662e1-433">Configurazione dell'autorità MDM in base alle esigenze di gestione, tra cui:</span><span class="sxs-lookup"><span data-stu-id="662e1-433">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-434">Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.</span><span class="sxs-lookup"><span data-stu-id="662e1-434">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-435">Fornire le indicazioni di MDM per:</span><span class="sxs-lookup"><span data-stu-id="662e1-435">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-436">Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.</span><span class="sxs-lookup"><span data-stu-id="662e1-436">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-437">Configurare criteri e servizi di gestione MDM come:</span><span class="sxs-lookup"><span data-stu-id="662e1-437">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-438">Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o collegamenti diretti.</span><span class="sxs-lookup"><span data-stu-id="662e1-438">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="662e1-439">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="662e1-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-440">Distribuzione di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-440">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="662e1-441">Connessione al data warehouse di Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-441">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="662e1-442">Integrare Intune con:</span><span class="sxs-lookup"><span data-stu-id="662e1-442">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-443">Visualizzatore team per assistenza remota (è necessaria una sottoscrizione del Visualizzatore del team).</span><span class="sxs-lookup"><span data-stu-id="662e1-443">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="662e1-444">Soluzioni partner di Mobile Threat Defense (MTD) (è necessaria una sottoscrizione MTD).</span><span class="sxs-lookup"><span data-stu-id="662e1-444">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="662e1-445">Una soluzione di gestione delle spese per telecomunicazioni (è necessaria una sottoscrizione a una soluzione di gestione delle spese per telecomunicazioni).</span><span class="sxs-lookup"><span data-stu-id="662e1-445">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="662e1-446">Registrare i dispositivi di ogni piattaforma supportata in Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-446">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="662e1-447">Fornire indicazioni sulla protezione delle app su:</span><span class="sxs-lookup"><span data-stu-id="662e1-447">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-448">Configurare criteri di protezione delle app per ogni piattaforma supportata.</span><span class="sxs-lookup"><span data-stu-id="662e1-448">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="662e1-449">Configurazione dei criteri di accesso condizionale per le app gestite.</span><span class="sxs-lookup"><span data-stu-id="662e1-449">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="662e1-450">Destinazione dei gruppi di utenti appropriati con i criteri MAM menzionati in precedenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-450">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-451">Uso dei report sull'utilizzo delle app gestite.</span><span class="sxs-lookup"><span data-stu-id="662e1-451">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-452">Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="662e1-452">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="662e1-453">
 
</li>
</ul>
  
<strong>Collegamento tramite cloud</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-453">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="662e1-454">Ti guideremo per prepararti a collegare gli ambienti di Configuration Manager esistenti con Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-454">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="662e1-455">I passaggi esatti dipendono dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="662e1-455">The exact steps depend on your source environment.</span></span> <span data-ttu-id="662e1-456">Questi passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="662e1-456">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="662e1-457">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="662e1-457">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="662e1-458">Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.</span><span class="sxs-lookup"><span data-stu-id="662e1-458">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="662e1-459">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-459">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="662e1-460">Fornire indicazioni per configurare l'aggiunta ad Azure AD ibrido.</span><span class="sxs-lookup"><span data-stu-id="662e1-460">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="662e1-461">Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.</span><span class="sxs-lookup"><span data-stu-id="662e1-461">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="662e1-462">Fornire indicazioni su come configurare il gateway di gestione cloud se usato come soluzione per la co-gestione della gestione remota dei dispositivi basati su Internet.</span><span class="sxs-lookup"><span data-stu-id="662e1-462">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-463">Configurare i carichi di lavoro supportati che si desidera passare a Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-463">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="662e1-464">Installare il client Configuration Manager nei dispositivi registrati di Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-464">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="662e1-465"><strong>Distribuire Outlook Mobile per iOS e Android in modo sicuro</strong> È possibile fornire indicazioni per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire agli utenti che siano installate tutte le app necessarie.</span><span class="sxs-lookup"><span data-stu-id="662e1-465"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="662e1-466">La procedura per distribuire in modo sicuro Outlook mobile per iOS e Android con Intune dipende dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="662e1-466">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="662e1-467">Può includere:</span><span class="sxs-lookup"><span data-stu-id="662e1-467">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-468">Download delle app Outlook per iOS e Android, Microsoft Authenticator e portale aziendale intune tramite Apple App Store o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="662e1-468">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="662e1-469">Fornire indicazioni sulla configurazione:</span><span class="sxs-lookup"><span data-stu-id="662e1-469">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-470">Distribuzione delle app Outlook per iOS e Android, Microsoft Authenticator e Intune Company Portal con Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-470">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="662e1-471">Criteri di protezione delle app.</span><span class="sxs-lookup"><span data-stu-id="662e1-471">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-472">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="662e1-472">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-473">Criteri di configurazione delle app.</span><span class="sxs-lookup"><span data-stu-id="662e1-473">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="662e1-474">Gli amministratori IT devono disporre di un'autorità di certificazione, di una rete wireless e di infrastrutture VPN esistenti già funzionanti nei propri ambienti di produzione durante la pianificazione della distribuzione di reti wireless e profili VPN con Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-474">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="662e1-475"><strong>Nota:</strong>il vantaggio del servizio FastTrack non include l'assistenza per la configurazione di autorità di certificazione, reti wireless, infrastrutture VPN o certificati push MDM Apple per Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-475"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="662e1-476"><strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud.</span><span class="sxs-lookup"><span data-stu-id="662e1-476"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="662e1-477">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-477">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="662e1-478"><strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-478"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="662e1-479"><strong>Nota:</strong>microsoft fornisce assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-479"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="662e1-480">Non forniamo assistenza per l'acquisto, la gestione delle licenze o l'attivazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-480">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="662e1-481">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-481">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="662e1-482"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-482"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="662e1-483">Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="662e1-483">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="662e1-484"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-484"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="662e1-485">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-485">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-486">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="662e1-486">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="662e1-487">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="662e1-487">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="662e1-488">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="662e1-488">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="662e1-489">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="662e1-489">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="662e1-490">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti di sistema minimi.</span><span class="sxs-lookup"><span data-stu-id="662e1-490">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="662e1-491">Office 365</span><span class="sxs-lookup"><span data-stu-id="662e1-491">Office 365</span></span>

<<table>
<thead>
<tr class="header">
<th><span data-ttu-id="662e1-492"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-492"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="662e1-493"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-493"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="662e1-494"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-494"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="662e1-495"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-495"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="662e1-496">Per Exchange Online, viene illustrato il processo per ottenere l'organizzazione pronta per l'utilizzo della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="662e1-496">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="662e1-497">I passaggi esatti dipendono dall'ambiente di origine e dai piani di migrazione della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="662e1-497">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="662e1-498">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-498">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-499">Configurare le funzionalità di Exchange Online Protection (EOP) per tutti i domini abilitati alla posta elettronica convalidati in Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-499">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="662e1-500">Puntare i record MX (Mail Exchange) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-500">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="662e1-501">Configurazione della funzionalità Office 365 ATP se fa parte del servizio di sottoscrizione.</span><span class="sxs-lookup"><span data-stu-id="662e1-501">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="662e1-502">Per ulteriori informazioni, vedere la parte relativa a <strong>Office 365 Advanced Threat Protection</strong> di questa tabella.</span><span class="sxs-lookup"><span data-stu-id="662e1-502">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="662e1-p126">Configurare la funzionalità di prevenzione della perdita dei dati (DLP) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="662e1-p127">Configurare Office 365 Message Encryption (OME) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="662e1-507">
  <strong>Nota:</strong> Il servizio di replica delle cassette postali tenta di eseguire la migrazione dei messaggi di posta elettronica di Information Rights Managed (IRM) dalla cassetta postale locale alla cassetta postale di Exchange Online corrispondente.</span><span class="sxs-lookup"><span data-stu-id="662e1-507">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="662e1-508">La possibilità di leggere i contenuti protetti dopo la migrazione dipende dal fatto che il cliente esegua il mapping e copi i modelli di Active Directory Rights Managed Services (AD RMS) in Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="662e1-508">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="662e1-509">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="662e1-509">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="662e1-510">Configurazione di DNS, tra cui l'individuazione automatica, il framework dei criteri mittente (SPF), DKIM (DomainKeys Identified Mail), l'autenticazione dei messaggi basata su dominio, la creazione di report e conformità (DMARC) e i record MX (se necessario).</span><span class="sxs-lookup"><span data-stu-id="662e1-510">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="662e1-511">Configurare il flusso di posta elettronica tra l'ambiente di messaggistica di origine e Exchange Online (in base alle esigenze).</span><span class="sxs-lookup"><span data-stu-id="662e1-511">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="662e1-512">Eseguire la migrazione della posta dall'ambiente di messaggistica di origine a Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-512">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="662e1-513">Configurazione di client delle cassette postali (Outlook per Windows, Outlook sul web e Outlook per iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="662e1-513">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="662e1-514">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="662e1-514">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="662e1-515">Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Migrazione dei dati.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-515">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="662e1-516">L'ambiente di origine deve avere uno dei livelli minimi seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-516">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-517">Una o più organizzazioni di Exchange con Exchange Server 2003 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="662e1-517">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="662e1-518">Un singolo ambiente di posta elettronica abilitato per il protocollo IMAP.</span><span class="sxs-lookup"><span data-stu-id="662e1-518">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="662e1-519">Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).</span><span class="sxs-lookup"><span data-stu-id="662e1-519">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="662e1-520">Per informazioni su Multi-Geo Capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-520">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="662e1-521">Il software client online come Project per Office 365, Outlook per Windows, Outlook per iOS e Android, il client di sincronizzazione di OneDrive for Business, Power BI Desktop e Skype for Business deve essere al livello minimo, come definito in Requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-521">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="662e1-522"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-522"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="662e1-523">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-523">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-524">Etichette e criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-524">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-525">Gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="662e1-525">Records management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-526">Criteri di eliminazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-526">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-527">Conformità delle comunicazioni.</span><span class="sxs-lookup"><span data-stu-id="662e1-527">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="662e1-528">Gestione dei rischi Insider.</span><span class="sxs-lookup"><span data-stu-id="662e1-528">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-529">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="662e1-529">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="662e1-530">

  <strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-530">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="662e1-531">Sviluppo di un piano di gestione dei file di record.</span><span class="sxs-lookup"><span data-stu-id="662e1-531">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="662e1-532">Connettori dati.</span><span class="sxs-lookup"><span data-stu-id="662e1-532">Data connectors.</span></span></li>
<li> <span data-ttu-id="662e1-533">Barriere in fatto di informazioni.</span><span class="sxs-lookup"><span data-stu-id="662e1-533">Information barriers.</span></span></li>
<li> <span data-ttu-id="662e1-534">Gestione degli accessi con privilegi.</span><span class="sxs-lookup"><span data-stu-id="662e1-534">Privileged access management.</span></span></li>
<li> <span data-ttu-id="662e1-535">Sviluppo dell'architettura delle informazioni in SharePoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-535">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="662e1-536">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="662e1-536">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="662e1-537">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="662e1-537">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="662e1-538"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-538"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="662e1-539">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-539">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-540">Classificazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="662e1-540">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="662e1-541">Tipi di informazioni sensibili.</span><span class="sxs-lookup"><span data-stu-id="662e1-541">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="662e1-542">Creare etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="662e1-542">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="662e1-543">Applicazione di etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="662e1-543">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="662e1-544">Etichettatura unificata.</span><span class="sxs-lookup"><span data-stu-id="662e1-544">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="662e1-545">Classificatori sottoponibili a formazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-545">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="662e1-546">Conoscere i dati tramite Esplora contenuto ed Esplora attività.</span><span class="sxs-lookup"><span data-stu-id="662e1-546">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="662e1-547">Pubblicare etichette con criteri (manuale e automatico).</span><span class="sxs-lookup"><span data-stu-id="662e1-547">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="662e1-548">Creare criteri di prevenzione della perdita dei dati (DLP) per chat e canali di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="662e1-548">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="662e1-549">Creazione di criteri endpoint DLP per i dispositivi Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-549">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="662e1-550">

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-550">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="662e1-551">Codice cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-551">Customer key.</span></span></li>
<li><span data-ttu-id="662e1-552">Sviluppo di espressioni regolari personalizzate (RegEx) per tipi di informazioni riservate.</span><span class="sxs-lookup"><span data-stu-id="662e1-552">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="662e1-553">Creazione o modifica di dizionari di parole chiave.</span><span class="sxs-lookup"><span data-stu-id="662e1-553">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="662e1-554">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="662e1-554">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="662e1-555">
<strong>Nota:</strong> Per ulteriori informazioni, vedere <strong>Azure Information Protection</strong> in Enterprise Mobility + <a href="#enterprise-mobility--security">Security.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-555">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="662e1-556">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="662e1-556">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="662e1-557"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-557"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="662e1-558">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-558">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-559">Conferma dei requisiti minimi in Exchange Online, SharePoint Online, Gruppi di Office 365 e Azure AD per supportare Teams.</span><span class="sxs-lookup"><span data-stu-id="662e1-559">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="662e1-560">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="662e1-560">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="662e1-561">Configurazione di DNS.</span><span class="sxs-lookup"><span data-stu-id="662e1-561">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="662e1-562">Conferma dell'abilitazione di Teams nel tenant Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-562">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="662e1-563">Abilitazione o disabilitazione delle licenze utente.</span><span class="sxs-lookup"><span data-stu-id="662e1-563">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="662e1-564">Valutazione della rete per Teams:</span><span class="sxs-lookup"><span data-stu-id="662e1-564">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-565">Controlli di porta ed endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-565">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="662e1-566">Controlli sulla qualità della connessione.</span><span class="sxs-lookup"><span data-stu-id="662e1-566">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="662e1-567">Stime sulla larghezza di banda.</span><span class="sxs-lookup"><span data-stu-id="662e1-567">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="662e1-568">Configurazione dei criteri delle app di Teams (app Web di Teams, app Desktop di Teams e app Teams per iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="662e1-568">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="662e1-569">Se applicabile, forniamo anche indicazioni per:</span><span class="sxs-lookup"><span data-stu-id="662e1-569">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-570">Dispositivi sala di Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="662e1-570">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="662e1-571">Creazione di account online necessari per i dispositivi di telefonia e di sala riunioni supportati elencati nel <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogo dei dispositivi Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="662e1-571">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="662e1-572">Assistenza remota con la configurazione lato servizio dei dispositivi Microsoft Teams Rooms certificati.</span><span class="sxs-lookup"><span data-stu-id="662e1-572">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="662e1-573">Abilitazione dell'audioconferenza:</span><span class="sxs-lookup"><span data-stu-id="662e1-573">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="662e1-574">Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.</span><span class="sxs-lookup"><span data-stu-id="662e1-574">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="662e1-575">Assegnazione di bridge per conferenze agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-575">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="662e1-576">Sistema telefonico:</span><span class="sxs-lookup"><span data-stu-id="662e1-576">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-577">Configurazione aziendale delle impostazioni predefinite vocali cloud.</span><span class="sxs-lookup"><span data-stu-id="662e1-577">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="662e1-578">Linee guida per i piani di chiamata (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercati disponibili</a>):</span><span class="sxs-lookup"><span data-stu-id="662e1-578">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="662e1-579">Assegnazione di numeri agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-579">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="662e1-580">Guida alla portabilità del numero locale tramite UI fino a 999.</span><span class="sxs-lookup"><span data-stu-id="662e1-580">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="662e1-581">Supporto RS per la richiesta di servizio di portabilità del numero locale superiore a 999.</span><span class="sxs-lookup"><span data-stu-id="662e1-581">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-582">Linee guida per l'instradamento diretto:</span><span class="sxs-lookup"><span data-stu-id="662e1-582">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-583">Indicazioni per la configurazione dell'organizzazione per la progettazione del routing diretto di scenari ospitati da partner o scenari distribuiti dal cliente per un massimo di 10 siti.</span><span class="sxs-lookup"><span data-stu-id="662e1-583">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="662e1-584">Verifica della configurazione di Session Border Controller (SBC).</span><span class="sxs-lookup"><span data-stu-id="662e1-584">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="662e1-585">Assistenza remota per la configurazione del dial plan.</span><span class="sxs-lookup"><span data-stu-id="662e1-585">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="662e1-586">Configurazione route vocale.</span><span class="sxs-lookup"><span data-stu-id="662e1-586">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="662e1-587">Bypass multimediale e ottimizzazione multimediale locale.</span><span class="sxs-lookup"><span data-stu-id="662e1-587">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="662e1-588">Abilitazione degli eventi live in Teams.</span><span class="sxs-lookup"><span data-stu-id="662e1-588">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="662e1-589">Configurazione dell'organizzazione e integrazione in Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="662e1-589">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="662e1-590">Indicazioni per la transizione da Skype for Business a Teams.</span><span class="sxs-lookup"><span data-stu-id="662e1-590">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="662e1-591">Identità abilitate in Azure AD per Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-591">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="662e1-592">Utenti abilitati per SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="662e1-592">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="662e1-593">Le cassette postali di Exchange sono presenti (online e locali in una configurazione ibrida di Exchange).</span><span class="sxs-lookup"><span data-stu-id="662e1-593">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="662e1-594">Abilitato per i gruppi di Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-594">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="662e1-595">
  <strong>Nota:</strong> Se gli utenti non sono assegnati e abilitati con licenze di SharePoint Online, non diranno spazio di archiviazione in OneDrive for Business in Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-595">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="662e1-596">La condivisione dei file continua a funzionare nei canali, ma gli utenti non possono condividere file nelle chat senza l'archiviazione di OneDrive for Business in Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-596">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="662e1-597">Teams non supporta SharePoint locale.</span><span class="sxs-lookup"><span data-stu-id="662e1-597">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="662e1-598">
  <strong>Nota:</strong> Lo stato ideale è che tutti gli utenti hanno le proprie cassette postali ospitate su Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="662e1-598">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="662e1-599">Gli utenti con cassette postali ospitate in locale devono avere le proprie identità sincronizzate con la directory di Office 365 tramite Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="662e1-599">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="662e1-600">Per questi clienti ibridi di Exchange, se la cassetta postale dell'utente è locale, l'utente non può aggiungere o configurare i connettori.</span><span class="sxs-lookup"><span data-stu-id="662e1-600">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="662e1-601">I programmi di installazione per i client desktop di Microsoft Teams per Windows e Mac possono essere scaricati da <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="662e1-601">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="662e1-602"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-602"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="662e1-603">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-603">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-604">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="662e1-604">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="662e1-605">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="662e1-605">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="662e1-606">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="662e1-606">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="662e1-607">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="662e1-607">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="662e1-608">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="662e1-608">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="662e1-609"><strong>Outlook per iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-609"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="662e1-610">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-610">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-611">Download di Outlook per iOS e Android tramite l'Apple App Store e Google Play.</span><span class="sxs-lookup"><span data-stu-id="662e1-611">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="662e1-612">Configurazione degli account e accesso alla cassetta postale di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="662e1-612">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="662e1-613">Protezione di Outlook mobile (per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Protezione di Outlook per iOS e Android in Exchange Online).</a></span><span class="sxs-lookup"><span data-stu-id="662e1-613">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="662e1-614">Identità abilitate in Azure AD per Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-614">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="662e1-615">Exchange Online configurato e licenze assegnate.</span><span class="sxs-lookup"><span data-stu-id="662e1-615">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="662e1-616"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-616"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="662e1-617">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-617">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-618">Assegnare licenze di Power BI.</span><span class="sxs-lookup"><span data-stu-id="662e1-618">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="662e1-619">Distribuire l'app Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="662e1-619">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="662e1-620">Il software client online come Power BI Desktop deve essere al livello minimo, come definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-620">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="662e1-621"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-621"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="662e1-622">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-622">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-623">Verificare la funzionalità di base di SharePoint sulla quale fa affidamento Project Online.</span><span class="sxs-lookup"><span data-stu-id="662e1-623">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="662e1-624">Aggiungere il servizio Project Online al tenant (inclusa l'aggiunta di sottoscrizioni per gli utenti).</span><span class="sxs-lookup"><span data-stu-id="662e1-624">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="662e1-625">Configurare il pool di risorse organizzazione (ERP).</span><span class="sxs-lookup"><span data-stu-id="662e1-625">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="662e1-626">Creare il primo progetto.</span><span class="sxs-lookup"><span data-stu-id="662e1-626">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="662e1-627">Il software client online come Project per Office 365 deve essere al livello minimo, come definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-627">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="662e1-628"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-628"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="662e1-629">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-629">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-630">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-630">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="662e1-631">Assegnare i contratti di licenza con l'utente finale utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="662e1-631">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="662e1-632">Installare Client desktop di Project Online dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="662e1-632">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="662e1-633">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-633">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="662e1-634">Configurare un unico server di distribuzione nel sito per Client desktop di Project Online, includendo una guida per la creazione del file configuration.xml da usare con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-634">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="662e1-635">Connettere Client desktop di Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="662e1-635">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="662e1-636">Il software client online come Project per Office 365 deve essere al livello minimo, come definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-636">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="662e1-637"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-637"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="662e1-638">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-638">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-639">Configurazione DNS.</span><span class="sxs-lookup"><span data-stu-id="662e1-639">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="662e1-640">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="662e1-640">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="662e1-641">Provisioning di utenti e licenze.</span><span class="sxs-lookup"><span data-stu-id="662e1-641">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="662e1-642">Abilitazione alla creazione di siti per l'amministratore di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="662e1-642">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="662e1-643">Pianificazione delle raccolte di siti.</span><span class="sxs-lookup"><span data-stu-id="662e1-643">Planning site collections.</span></span></li>
<li><span data-ttu-id="662e1-644">Protezione del contenuto e gestione delle autorizzazioni.</span><span class="sxs-lookup"><span data-stu-id="662e1-644">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="662e1-645">Configurazione delle caratteristiche di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="662e1-645">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="662e1-646">Configurazione delle funzionalità dell'ambiente ibrido di SharePoint, come la ricerca ibrida, i siti ibridi, la tassonomia ibrida, i tipi di contenuto, la creazione siti in modalità self-service ibrida (solo SharePoint Server 2013), l'icona di avvio delle app estesa, OneDrive for Business ibrido e i siti extranet.</span><span class="sxs-lookup"><span data-stu-id="662e1-646">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="662e1-647">L'approccio alla migrazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-647">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="662e1-648">Vengono fornite indicazioni aggiuntive per OneDrive for Business a seconda della versione di SharePoint, ad esempio:</span><span class="sxs-lookup"><span data-stu-id="662e1-648">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-649">Identificazione delle opzioni di integrazione ed esame dell'infrastruttura di rete locale e online e della larghezza di banda.</span><span class="sxs-lookup"><span data-stu-id="662e1-649">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="662e1-650">Installazione di SharePoint Online 2013 SP1 (se applicabile), pianificazione e implementazione dei requisiti di sincronizzazione e identità e identificazione del client di sincronizzazione di OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="662e1-650">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="662e1-651">Pianificazione e implementazione di una singola implementazione per tutti gli utenti (o un'implementazione in più fasi).</span><span class="sxs-lookup"><span data-stu-id="662e1-651">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="662e1-652">Assegnazione di licenze, reindirizzamento di siti personali e raccolte documenti personali a Office 365 (applicabile a SharePoint Online 2013), configurazione di gruppi di destinatari per controllare l'accesso a OneDrive (applicabile a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="662e1-652">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="662e1-653">Reindirizzamento o spostamento di cartelle note in OneDrive.</span><span class="sxs-lookup"><span data-stu-id="662e1-653">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="662e1-654">Distribuzione della sincronizzazione del client OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="662e1-654">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="662e1-655">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="662e1-655">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="662e1-656">Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Migrazione dei dati.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-656">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="662e1-657"><strong>Per SharePoint ibrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-657"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="662e1-658">La configurazione ibrida di SharePoint include la configurazione di ricerca ibrida, siti, tassonomia, tipi di contenuto, OneDrive for Business, un'icona di avvio delle app estesa, siti Extranet e creazione di siti in modalità self-service connessi dall'ambiente locale a un singolo ambiente SharePoint Online di destinazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-658">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="662e1-659">
  <strong>Nota:</strong> La creazione di siti in modalità self-service non è nell'ambito dei server locali che eseguono SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="662e1-659">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="662e1-660">Per abilitare l'ambiente ibrido di SharePoint, è necessario disporre di uno dei seguenti ambienti SharePoint Server locali: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="662e1-660">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="662e1-661">
  <strong>Nota:</strong> L'aggiornamento degli ambienti SharePoint locali a SharePoint Server non è nell'ambito.</span><span class="sxs-lookup"><span data-stu-id="662e1-661">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="662e1-662">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-662">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="662e1-663">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=853548">Livelli di aggiornamento pubblico minimi per le funzionalità ibride di SharePoint.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="662e1-663">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="662e1-664">
  <strong>Nota:</strong> Per informazioni su Multi-Geo Capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive e SharePoint Online in Office 365.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="662e1-664">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="662e1-665"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-665"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="662e1-666">Vengono fornite indicazioni remote per l'abilitazione del servizio Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="662e1-666">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="662e1-667">Il software client online deve essere al livello minimo definito nei requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 e Office.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-667">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="662e1-668">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="662e1-668">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="662e1-669"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-669"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="662e1-670"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-670"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="662e1-671"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-671"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="662e1-672"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-672"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="662e1-673">Vengono fornite indicazioni remote per la protezione delle identità cloud per gli scenari seguenti.</span><span class="sxs-lookup"><span data-stu-id="662e1-673">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="662e1-674">

<strong>Infrastruttura di base protetta</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="662e1-674">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="662e1-675">Configurazione e abilitazione dell'autenticazione avanzata per le identità, inclusa la protezione con Azure Multi-Factor Authentication (MFA) (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure MFA e la reimpostazione della password self-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="662e1-675">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="662e1-676">Per i clienti non di Azure AD Premium, vengono fornite indicazioni per proteggere le identità usando le impostazioni predefinite di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="662e1-676">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="662e1-677">Per i clienti premium di Azure AD, vengono fornite indicazioni per proteggere le identità con l'accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="662e1-677">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="662e1-678">Rilevamento e blocco dell'uso di password deboli con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-678">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="662e1-679">Protezione dell'accesso remoto alle app Web locali con il proxy dell'applicazione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-679">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="662e1-680">Abilitazione del rilevamento e della correzione basata sui rischi con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-680">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="662e1-681">Abilitazione di una schermata di accesso personalizzata, inclusi logo, testo e immagini con personalizzazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-681">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="662e1-682">Condivisione sicura di app e servizi con utenti guest con Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="662e1-682">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="662e1-683">Gestione dell'accesso per gli amministratori di Office 365 tramite i ruoli amministrativi incorporati del controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.</span><span class="sxs-lookup"><span data-stu-id="662e1-683">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="662e1-684">Configurazione dell'aggiunta ad Azure AD ibrido.</span><span class="sxs-lookup"><span data-stu-id="662e1-684">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="662e1-685">Configurazione dell'aggiunta ad Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-685">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="662e1-686">
  
<strong>Monitoraggio e creazione di report</strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-686">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="662e1-687">Abilitazione del monitoraggio remoto per AD FS, Azure AD Connect e controller di dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="662e1-687">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="662e1-688">
  
<strong>Governance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-688">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="662e1-689">Gestione del ciclo di vita delle identità e degli accessi di Azure AD su vasta scala con la gestione dei diritti di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-689">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="662e1-690">Gestione dell'appartenenza ai gruppi di Azure AD, dell'accesso alle app aziendali e delle assegnazioni dei ruoli con le verifiche di accesso di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-690">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-691">Esame delle Condizioni per l'utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-691">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-692">Gestione e controllo dell'accesso agli account amministratore con privilegi con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="662e1-692">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="662e1-693">
  
<strong>Automazione ed efficienza </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-693">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="662e1-694">Abilitazione di Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="662e1-694">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="662e1-695">Consentire agli utenti di creare e gestire la propria sicurezza cloud o i gruppi di Office 365 con la gestione dei gruppi self-service di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-695">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-696">Gestione dell'accesso delegato alle app aziendali con la gestione dei gruppi delegati di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-696">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-697">Abilitazione dei gruppi dinamici di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-697">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="662e1-698">Organizzazione delle app nel portale App personali tramite raccolte.</span><span class="sxs-lookup"><span data-stu-id="662e1-698">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="662e1-699">Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione dei problemi identificati che impediscono l'integrazione con le funzionalità di Azure AD e Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="662e1-699">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="662e1-700"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="662e1-700"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="662e1-701">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-701">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-702">Attivazione e configurazione del tenant.</span><span class="sxs-lookup"><span data-stu-id="662e1-702">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="662e1-703">Creare e configurare etichette e criteri.</span><span class="sxs-lookup"><span data-stu-id="662e1-703">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-704">Applicare la protezione delle informazioni ai documenti.</span><span class="sxs-lookup"><span data-stu-id="662e1-704">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="662e1-705">Classificare ed etichettare automaticamente le informazioni nelle app di Office, come Word, PowerPoint, Excel e Outlook, che eseguono Windows e con il client di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-705">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="662e1-706">Individuazione e applicazione di etichette ai file in stato di inquieto con lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-706">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="662e1-707">Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="662e1-707">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="662e1-708">Vengono inoltre fornite indicazioni per applicare la protezione tramite Microsoft Azure Rights Management Services (Azure RMS), Crittografia messaggi di Office 365 e prevenzione della perdita dei dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="662e1-708">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="662e1-709">Le responsabilità preliminari del cliente includono:</span><span class="sxs-lookup"><span data-stu-id="662e1-709">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-710">Elenco di percorsi di condivisione file da analizzare.</span><span class="sxs-lookup"><span data-stu-id="662e1-710">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="662e1-711">Tassonomia di classificazione approvata.</span><span class="sxs-lookup"><span data-stu-id="662e1-711">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="662e1-712">Informazioni su eventuali restrizioni o requisiti normativi relativi alla gestione delle chiavi.</span><span class="sxs-lookup"><span data-stu-id="662e1-712">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-713">Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="662e1-713">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="662e1-714">Etichette configurate per la classificazione e la protezione.</span><span class="sxs-lookup"><span data-stu-id="662e1-714">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="662e1-715">Sono presenti tutti i prerequisiti per lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-715">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="662e1-716">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisiti per l'installazione</a>e la distribuzione dello scanner di etichettatura unificata di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="662e1-716">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="662e1-717">Verificare che i dispositivi degli utenti esercitino un sistema operativo supportato e che siano installati i prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="662e1-717">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="662e1-718">Per ulteriori dettagli, vedere gli argomenti seguenti.</span><span class="sxs-lookup"><span data-stu-id="662e1-718">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="662e1-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guida dell'amministratore: Installare il client di etichettatura unificata di Azure Information Protection per gli utenti</a>   </span><span class="sxs-lookup"><span data-stu-id="662e1-719"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="662e1-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="662e1-720"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="662e1-721">Installazione e configurazione del connettore Azure RMS e dei server, incluso il connettore ACTIVE Directory RMS (AD RMS) per il supporto ibrido.</span><span class="sxs-lookup"><span data-stu-id="662e1-721">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="662e1-722">L'installazione e la configurazione di Bring Your Own Key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificato) o Hold Your Own Key (HYOK) (solo client classico) richiede una di queste opzioni per la distribuzione.</span><span class="sxs-lookup"><span data-stu-id="662e1-722">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="662e1-723"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-723"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="662e1-724">Forniamo indicazioni remote su come prepararsi a usare Intune come provider di gestione dei dispositivi mobili (MDM) e di gestione delle app per dispositivi mobili (MAM) basato su cloud per le tue app e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-724">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="662e1-725">I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili.</span><span class="sxs-lookup"><span data-stu-id="662e1-725">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="662e1-726">I passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="662e1-726">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-727">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="662e1-727">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="662e1-728">Configurazione delle identità che devono essere usate da Intune sfruttando Active Directory locale o le identità cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="662e1-728">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="662e1-729">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-729">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="662e1-730">Configurazione dell'autorità MDM in base alle esigenze di gestione, tra cui:</span><span class="sxs-lookup"><span data-stu-id="662e1-730">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-731">Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.</span><span class="sxs-lookup"><span data-stu-id="662e1-731">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-732">Fornire le indicazioni di MDM per:</span><span class="sxs-lookup"><span data-stu-id="662e1-732">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-733">Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.</span><span class="sxs-lookup"><span data-stu-id="662e1-733">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-734">Configurare criteri e servizi di gestione MDM come:</span><span class="sxs-lookup"><span data-stu-id="662e1-734">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-735">Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o collegamenti diretti.</span><span class="sxs-lookup"><span data-stu-id="662e1-735">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="662e1-736">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="662e1-736">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-737">Distribuzione di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-737">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="662e1-738">Connessione al data warehouse di Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-738">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="662e1-739">Integrare Intune con:</span><span class="sxs-lookup"><span data-stu-id="662e1-739">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-740">Visualizzatore team per assistenza remota (è necessaria una sottoscrizione del Visualizzatore del team).</span><span class="sxs-lookup"><span data-stu-id="662e1-740">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="662e1-741">Soluzioni partner di Mobile Threat Defense (MTD) (è necessaria una sottoscrizione MTD).</span><span class="sxs-lookup"><span data-stu-id="662e1-741">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="662e1-742">Una soluzione di gestione delle spese per telecomunicazioni (è necessaria una sottoscrizione a una soluzione di gestione delle spese per telecomunicazioni).</span><span class="sxs-lookup"><span data-stu-id="662e1-742">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-743">Registrare i dispositivi di ogni piattaforma supportata in Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-743">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="662e1-744">Fornire indicazioni sulla protezione delle app su:</span><span class="sxs-lookup"><span data-stu-id="662e1-744">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-745">Configurare criteri di protezione delle app per ogni piattaforma supportata.</span><span class="sxs-lookup"><span data-stu-id="662e1-745">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="662e1-746">Configurazione dei criteri di accesso condizionale per le app gestite.</span><span class="sxs-lookup"><span data-stu-id="662e1-746">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="662e1-747">Destinazione dei gruppi di utenti appropriati con i criteri MAM menzionati in precedenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-747">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-748">Uso dei report sull'utilizzo delle app gestite.</span><span class="sxs-lookup"><span data-stu-id="662e1-748">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-749">Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="662e1-749">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="662e1-750">
  
</li>
</ul>
  
<strong>Collegamento tramite cloud</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-750">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="662e1-751">Ti guideremo per prepararti a collegare gli ambienti di Configuration Manager esistenti con Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-751">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="662e1-752">I passaggi esatti dipendono dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="662e1-752">The exact steps depend on your source environment.</span></span> <span data-ttu-id="662e1-753">Questi passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="662e1-753">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="662e1-754">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="662e1-754">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="662e1-755">Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.</span><span class="sxs-lookup"><span data-stu-id="662e1-755">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="662e1-756">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-756">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="662e1-757">Fornire indicazioni per configurare l'aggiunta ad Azure AD ibrido.</span><span class="sxs-lookup"><span data-stu-id="662e1-757">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="662e1-758">Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.</span><span class="sxs-lookup"><span data-stu-id="662e1-758">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="662e1-759">Fornire indicazioni su come configurare il gateway di gestione cloud se usato come soluzione per la co-gestione della gestione remota dei dispositivi basati su Internet.</span><span class="sxs-lookup"><span data-stu-id="662e1-759">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="662e1-760">Configurare i carichi di lavoro supportati che si desidera passare a Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-760">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="662e1-761">Installare il client Configuration Manager nei dispositivi registrati di Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-761">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="662e1-762"><strong>Distribuire Outlook Mobile per iOS e Android in modo sicuro</strong> È possibile fornire indicazioni per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire agli utenti che siano installate tutte le app necessarie.</span><span class="sxs-lookup"><span data-stu-id="662e1-762"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="662e1-763">La procedura per distribuire in modo sicuro Outlook mobile per iOS e Android con Intune dipende dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="662e1-763">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="662e1-764">Può includere:</span><span class="sxs-lookup"><span data-stu-id="662e1-764">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-765">Download delle app Outlook per iOS e Android, Microsoft Authenticator e portale aziendale intune tramite Apple App Store o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="662e1-765">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="662e1-766">Fornire indicazioni sulla configurazione:</span><span class="sxs-lookup"><span data-stu-id="662e1-766">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-767">Distribuzione delle app Outlook per iOS e Android, Microsoft Authenticator e Intune Company Portal con Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-767">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="662e1-768">Criteri di protezione delle app.</span><span class="sxs-lookup"><span data-stu-id="662e1-768">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-769">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="662e1-769">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="662e1-770">Criteri di configurazione delle app.</span><span class="sxs-lookup"><span data-stu-id="662e1-770">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="662e1-771">Gli amministratori IT devono disporre di un'autorità di certificazione, di una rete wireless e di infrastrutture VPN esistenti già funzionanti nei propri ambienti di produzione durante la pianificazione della distribuzione di reti wireless e profili VPN con Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-771">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="662e1-772"><strong>Nota:</strong>il vantaggio del servizio FastTrack non include l'assistenza per la configurazione delle autorità di certificazione, delle reti wireless, delle infrastrutture VPN o dei certificati push MDM di Apple per Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-772"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="662e1-773"><strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud.</span><span class="sxs-lookup"><span data-stu-id="662e1-773"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="662e1-774">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-774">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="662e1-775"><strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-775"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="662e1-776"><strong>Nota:</strong>microsoft fornisce assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-776"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="662e1-777">Non forniamo assistenza per l'acquisto, la gestione delle licenze o l'attivazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-777">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="662e1-778">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="662e1-778">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="662e1-779"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-779"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="662e1-780">Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="662e1-780">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="662e1-781">Windows 10</span><span class="sxs-lookup"><span data-stu-id="662e1-781">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="662e1-782"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-782"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="662e1-783"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-783"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="662e1-784"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-784"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="662e1-785"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-785"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="662e1-786">Forniamo indicazioni per l'aggiornamento da Windows 7 Professional e Windows 8.1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="662e1-786">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="662e1-787">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-787">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-788">Informazioni sull'intenzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-788">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="662e1-789">Valutazione dell'ambiente di origine e dei requisiti (assicurarsi che Microsoft Endpoint Configuration Manager sia aggiornato al livello necessario per supportare la distribuzione di Windows 10).</span><span class="sxs-lookup"><span data-stu-id="662e1-789">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="662e1-790">Distribuzione di Windows 10 Enterprise e Microsoft 365 Apps con Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-790">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="662e1-791">Opzioni consigliate per valutare le tue app di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-791">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="662e1-792">Abilitazione dell'uso di Desktop Analytics e indicazioni tramite la creazione di un piano di distribuzione di Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="662e1-792">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="662e1-793">Valutazione della compatibilità delle app di Microsoft 365 sfruttando il dashboard di preparazione di Office 365 in Configuration Manager o con lo strumento autonomo Readiness Toolkit for Office, oltre all'assistenza per la distribuzione di Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="662e1-793">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="662e1-794">Creazione di un elenco di controllo di correzione sulle operazioni da eseguire per portare l'ambiente di origine ai requisiti minimi per una distribuzione corretta.</span><span class="sxs-lookup"><span data-stu-id="662e1-794">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="662e1-795">Fornire indicazioni per l'aggiornamento dei dispositivi esistenti a Windows 10 Enterprise se soddisfano i requisiti hardware dei dispositivi necessari.</span><span class="sxs-lookup"><span data-stu-id="662e1-795">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="662e1-796">Fornire indicazioni sull'aggiornamento per supportare il movimento di distribuzione esistente.</span><span class="sxs-lookup"><span data-stu-id="662e1-796">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="662e1-797">FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-797">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="662e1-798">Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="662e1-798">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="662e1-799">Distribuzione di Microsoft 365 Apps con Configuration Manager nell'ambito della distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-799">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="662e1-800">Fornire indicazioni per aiutare l'organizzazione a rimanere aggiornata con Windows 10 Enterprise e Microsoft 365 Apps usando l'ambiente Configuration Manager esistente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-800">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="662e1-801">
  <strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-801">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="662e1-802">Aggiornamento di Configuration Manager al Current Branch.</span><span class="sxs-lookup"><span data-stu-id="662e1-802">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="662e1-803">Creazione di immagini personalizzate per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-803">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="662e1-804">Creazione e supporto degli script di distribuzione per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-804">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="662e1-805">Conversione di un sistema di Windows 10 dal BIOS a Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="662e1-805">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="662e1-806">Abilitare le funzionalità di sicurezza di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-806">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="662e1-807">Configurazione di Windows Deployment Services (WDS) per il boot di Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="662e1-807">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="662e1-808">Uso di Microsoft Deployment Toolkit (MDT) per acquisire e distribuire immagini di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-808">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="662e1-809">Uso dell’Utilità di migrazione dello stato utente (USMT).</span><span class="sxs-lookup"><span data-stu-id="662e1-809">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="662e1-810">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="662e1-810">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="662e1-811">Per l'aggiornamento del PC, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-811">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-812">Sistema operativo di origine: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="662e1-812">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="662e1-813">Dispositivi: fattore di forma per desktop, notebook o tablet.</span><span class="sxs-lookup"><span data-stu-id="662e1-813">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="662e1-814">Sistema operativo di destinazione: Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="662e1-814">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="662e1-815">Per l'aggiornamento dell'infrastruttura, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-815">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-816">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="662e1-816">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="662e1-817">La versione di Configuration Manager deve essere supportata dalla versione di destinazione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-817">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="662e1-818">Per altre informazioni, vedere la tabella di supporto di Configuration Manager in <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Supporto per Windows 10 in Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="662e1-818">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="662e1-819"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-819"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="662e1-820">Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.</span><span class="sxs-lookup"><span data-stu-id="662e1-820">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="662e1-821">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-821">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-822">Distribuzione delle tecnologie per proteggere gli endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-822">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="662e1-823">Configurazione dei profili di protezione degli endpoint e delle restrizioni dei dispositivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-823">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="662e1-824">Valutazione della versione del sistema operativo e della gestione dei dispositivi (inclusi Intune, Microsoft Endpoint Configuration Manager, oggetti Criteri di gruppo e configurazioni di terze parti), nonché lo stato dei servizi av di Windows Defender o di altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-824">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="662e1-825">Valutazione dello stato dei servizi Windows AV o di altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-825">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="662e1-826">Valutazione dei proxy e dei firewall che limitano il traffico di rete.</span><span class="sxs-lookup"><span data-stu-id="662e1-826">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="662e1-827">Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo agente ATP con un endpoint di onboarding.</span><span class="sxs-lookup"><span data-stu-id="662e1-827">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="662e1-828">Linee guida per la distribuzione, assistenza alla configurazione ed istruzione su:</span><span class="sxs-lookup"><span data-stu-id="662e1-828">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-829">Gestione delle minacce e delle vulnerabilità.</span><span class="sxs-lookup"><span data-stu-id="662e1-829">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-830">Riduzione della superficie di attacco.</span><span class="sxs-lookup"><span data-stu-id="662e1-830">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-831">Protezione di nuova generazione.</span><span class="sxs-lookup"><span data-stu-id="662e1-831">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-832">Rilevamento e risposta degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="662e1-832">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-833">Indagine e correzione automatizzate.</span><span class="sxs-lookup"><span data-stu-id="662e1-833">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="662e1-834">Microsoft Defender ATP (sono necessarie licenze di Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="662e1-834">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="662e1-835">Punteggio di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="662e1-835">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-836">Revisione di simulazioni ed esercitazioni (come scenari di pratica, malware falso e indagini automatizzate).</span><span class="sxs-lookup"><span data-stu-id="662e1-836">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="662e1-837">Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="662e1-837">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="662e1-838">Integrazione di Office 365 ATP con Microsoft Defender ATP.</span><span class="sxs-lookup"><span data-stu-id="662e1-838">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="662e1-839">Procedure dettagliate nel portale di Microsoft Defender Security Center.</span><span class="sxs-lookup"><span data-stu-id="662e1-839">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="662e1-840">I sistemi operativi seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-840">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-841">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-841">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-842">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="662e1-842">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-843">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="662e1-843">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-844">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="662e1-844">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-845">Windows Server Semi-Annual Channel (SAC) versione 1803.</span><span class="sxs-lookup"><span data-stu-id="662e1-845">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-846">macOS versioni 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="662e1-846">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="662e1-847">
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versione 2002 o successiva).</span><span class="sxs-lookup"><span data-stu-id="662e1-847">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="662e1-848"></li>
</ul>

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-848"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="662e1-849">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-849">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="662e1-850">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="662e1-850">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="662e1-851">Gestione continua e risposta alle minacce.</span><span class="sxs-lookup"><span data-stu-id="662e1-851">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="662e1-852">Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-852">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-853">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="662e1-853">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-854">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="662e1-854">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-855">Linux.</span><span class="sxs-lookup"><span data-stu-id="662e1-855">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-856">Dispositivi mobili (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="662e1-856">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-857">Onboarding e configurazione del server:</span><span class="sxs-lookup"><span data-stu-id="662e1-857">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-858">Configurazione di un server proxy per le comunicazioni offline.</span><span class="sxs-lookup"><span data-stu-id="662e1-858">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-859">Configurazione dei pacchetti di distribuzione di Configuration Manager nelle istanze e nelle versioni di Configuration Manager di livello inferiore.</span><span class="sxs-lookup"><span data-stu-id="662e1-859">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-860">Onboarding dei server nel Centro sicurezza di Azure.</span><span class="sxs-lookup"><span data-stu-id="662e1-860">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-861">Server non gestiti da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="662e1-861">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-862">Onboarding e configurazione di macOS:</span><span class="sxs-lookup"><span data-stu-id="662e1-862">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-863">Distribuzione manuale basata su Intune.</span><span class="sxs-lookup"><span data-stu-id="662e1-863">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-864">Distribuzione basata su JAMF.</span><span class="sxs-lookup"><span data-stu-id="662e1-864">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="662e1-865">Altra distribuzione basata sul prodotto di gestione dei dispositivi mobili (MDM).</span><span class="sxs-lookup"><span data-stu-id="662e1-865">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-866">Distribuzione manuale.</span><span class="sxs-lookup"><span data-stu-id="662e1-866">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-867">Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-867">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-868">Isolamento basato su hardware.</span><span class="sxs-lookup"><span data-stu-id="662e1-868">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-869">Controllo dell'app.</span><span class="sxs-lookup"><span data-stu-id="662e1-869">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-870">Protezione dagli exploit.</span><span class="sxs-lookup"><span data-stu-id="662e1-870">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-871">Firewall di rete.</span><span class="sxs-lookup"><span data-stu-id="662e1-871">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="662e1-872">Iscrizione o configurazione di Microsoft Threat Experts.</span><span class="sxs-lookup"><span data-stu-id="662e1-872">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="662e1-873">Configurazione o formazione che esamina le connessioni API o siem (Security Information and Event Management).</span><span class="sxs-lookup"><span data-stu-id="662e1-873">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="662e1-874">Iscrizione o configurazione di Microsoft Threat Protection (MTP).</span><span class="sxs-lookup"><span data-stu-id="662e1-874">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="662e1-875">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="662e1-875">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="662e1-876">Formazione o indicazioni su come usare o creare query Kusto.</span><span class="sxs-lookup"><span data-stu-id="662e1-876">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="662e1-877">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="662e1-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="662e1-878">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="662e1-878">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="662e1-879"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-879"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="662e1-880"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-880"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="662e1-881"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-881"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="662e1-882"><strong>Desktop virtuale Windows</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-882"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="662e1-883">Forniamo indicazioni sulla distribuzione per l'onboarding in Desktop virtuale Windows (un servizio di virtualizzazione di desktop e app).</span><span class="sxs-lookup"><span data-stu-id="662e1-883">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="662e1-884">Desktop virtuale Windows sfrutta l'esperienza multi-sessione di Windows 10 ed è ottimizzato per Microsoft 365 Apps for Enterprise con sicurezza e gestione integrate per Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="662e1-884">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="662e1-885">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="662e1-885">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="662e1-886">Distribuzione dell'ambiente Desktop virtuale Windows con Windows 10 Enterprise multi-sessione e Microsoft 365 Apps for Enterprise con gli strumenti seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-886">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="662e1-887">Immagine di Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="662e1-887">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="662e1-888">Immagine condivisa.</span><span class="sxs-lookup"><span data-stu-id="662e1-888">Shared image.</span></span></li>
<li><span data-ttu-id="662e1-889">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="662e1-889">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="662e1-890">Configurazione di FSLogix:</span><span class="sxs-lookup"><span data-stu-id="662e1-890">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="662e1-891">Distribuzione dell'agente FSLogix con il contenitore dei profili.</span><span class="sxs-lookup"><span data-stu-id="662e1-891">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="662e1-892">Distribuzione dell'agente FSLogix con contenitore di Office.</span><span class="sxs-lookup"><span data-stu-id="662e1-892">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="662e1-893">Configurazione della cartella FSLogix con esclusioni di contenuto.</span><span class="sxs-lookup"><span data-stu-id="662e1-893">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="662e1-894">Distribuzione di Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="662e1-894">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="662e1-895">Distribuzione di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="662e1-895">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="662e1-896">Connessione tramite client Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="662e1-896">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="662e1-897">

<strong>Gli elementi seguenti non sono nell'ambito</strong>
</span><span class="sxs-lookup"><span data-stu-id="662e1-897">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="662e1-898">Gestione dei progetti della distribuzione di Desktop virtuale Windows del cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-898">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="662e1-899">Virtualizzazione e distribuzione di app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="662e1-899">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="662e1-900">Immagini personalizzate.</span><span class="sxs-lookup"><span data-stu-id="662e1-900">Custom images.</span></span></li>
<li><span data-ttu-id="662e1-901">Migrazioni e scenari che coinvolgono VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="662e1-901">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="662e1-902">Scenari Linux.</span><span class="sxs-lookup"><span data-stu-id="662e1-902">Linux scenarios.</span></span></li>
<li><span data-ttu-id="662e1-903">Conversione o migrazione dei profili utente.</span><span class="sxs-lookup"><span data-stu-id="662e1-903">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="662e1-904">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="662e1-904">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="662e1-905">Dovresti già disporre di quanto segue:</span><span class="sxs-lookup"><span data-stu-id="662e1-905">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="662e1-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisiti di licenza di Desktop virtuale Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="662e1-906"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="662e1-907">Rete di Azure:</span><span class="sxs-lookup"><span data-stu-id="662e1-907">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="662e1-908">Creazione e subnetting della rete virtuale (VNET).</span><span class="sxs-lookup"><span data-stu-id="662e1-908">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="662e1-909">Gruppi di sicurezza firewall e di rete.</span><span class="sxs-lookup"><span data-stu-id="662e1-909">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="662e1-910">VPN ed ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="662e1-910">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="662e1-911">Routing ad Azure dall'ambiente locale.</span><span class="sxs-lookup"><span data-stu-id="662e1-911">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="662e1-912">Regole del firewall per consentire la connettività a Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="662e1-912">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="662e1-913">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Client Desktop remoto supportati.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-913">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="662e1-914">Configurazione generale di Azure AD:</span><span class="sxs-lookup"><span data-stu-id="662e1-914">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="662e1-915">Strategia di <i>identità (è possibile utilizzare solo una delle tre opzioni seguenti):</i>
</span><span class="sxs-lookup"><span data-stu-id="662e1-915">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="662e1-916">Active Directory con Azure AD Connect in Azure.</span><span class="sxs-lookup"><span data-stu-id="662e1-916">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="662e1-917">Active Directory con Azure AD Connect locale tramite VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="662e1-917">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="662e1-918">Servizi di dominio Active Directory.</span><span class="sxs-lookup"><span data-stu-id="662e1-918">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="662e1-919">App Assure</span><span class="sxs-lookup"><span data-stu-id="662e1-919">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="662e1-920"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-920"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="662e1-921"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-921"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="662e1-922"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-922"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="662e1-923"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-923"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="662e1-924">App Assure è un servizio progettato per risolvere i problemi di compatibilità delle app di Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="662e1-924">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="662e1-925">Quando richiedi il servizio App Assure, microsoft lavora con te per risolvere i problemi validi dell'app senza costi aggiuntivi con un abbonamento idoneo.</span><span class="sxs-lookup"><span data-stu-id="662e1-925">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="662e1-926">Forniamo anche indicazioni ai clienti che devono affrontare problemi di compatibilità durante la distribuzione di Desktop virtuale Windows e Microsoft Edge e facciamo ogni sforzo ragionevole per risolvere i problemi di compatibilità.</span><span class="sxs-lookup"><span data-stu-id="662e1-926">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="662e1-927">Forniamo assistenza per la correzione per le app distribuite nei prodotti Microsoft seguenti:</span><span class="sxs-lookup"><span data-stu-id="662e1-927">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="662e1-928"><strong>Windows 10 </strong> (inclusi i dispositivi ARM64)</span><span class="sxs-lookup"><span data-stu-id="662e1-928"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="662e1-929"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="662e1-929"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="662e1-930"><strong>Microsoft Edge -</strong> Per indicazioni sulla distribuzione, vedere <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Panoramica dei canali di Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-930"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="662e1-931"><strong>Desktop virtuale</strong> - Windows Per altre informazioni, vedi <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Che cos'è Desktop virtuale Windows?</a> e Domande frequenti su <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-sessione.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-931"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="662e1-932">

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-932">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="662e1-p145">Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro di distribuzione desktop</a>. Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito <a href="https://go.microsoft.com/fwlink/?linkid=2053818">modulo</a>.</span><span class="sxs-lookup"><span data-stu-id="662e1-p145">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="662e1-936">Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="662e1-936">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="662e1-937">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span><span class="sxs-lookup"><span data-stu-id="662e1-937">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="662e1-938">Servizi di sola creazione di pacchetti di app.</span><span class="sxs-lookup"><span data-stu-id="662e1-938">App packaging-only services.</span></span> <span data-ttu-id="662e1-939">Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-939">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="662e1-940">

<strong>Le responsabilità del cliente includono</strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-940">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="662e1-941">Creazione di un inventario delle app.</span><span class="sxs-lookup"><span data-stu-id="662e1-941">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="662e1-942">Convalida di tali app in Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="662e1-942">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="662e1-943">
<strong>Nota:</strong>  Microsoft non può apportare modifiche al codice sorgente.</span><span class="sxs-lookup"><span data-stu-id="662e1-943">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="662e1-944">Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-944">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="662e1-945">Contatta un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="662e1-945">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="662e1-946"><strong>Windows 10 e Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="662e1-946"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="662e1-947">Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="662e1-947">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="662e1-948">
<strong>Windows 10 in ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="662e1-948">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="662e1-949">Le app che hanno funzionato in Windows 7, Office 2010 o versioni successive funzionano anche in Windows 10 e Microsoft 365 Apps nei dispositivi ARM64.</span><span class="sxs-lookup"><span data-stu-id="662e1-949">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="662e1-950">
  <strong>Nota:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="662e1-950">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="662e1-951">L'emulazione x64 (64 bit) è disponibile in anteprima per i clienti che partecipano al <a href="https://insider.windows.com/">Programma Windows Insider.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-951">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="662e1-952">Per i clienti non Windows Insider con Windows 10 versione 2004 (o successiva), ARM64 Photoshop è supportato con OpenCL e <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-952">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="662e1-953">I clienti del Programma Windows Insider possono scaricare una versione Insider del pacchetto di compatibilità OpenCL e OpenGL da usare con altre app.</span><span class="sxs-lookup"><span data-stu-id="662e1-953">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="662e1-954">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="662e1-954">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="662e1-955">Se le app o i siti Web funzionano in Internet Explorer 11, nelle versioni supportate di Google Chrome o in qualsiasi versione di Microsoft Edge, funzionano anche con Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="662e1-955">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-956">Poiché il Web è in continua evoluzione, assicurarsi di leggere questo elenco pubblicato delle modifiche note che influiscono sulla compatibilità dei siti <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">per Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-956">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="662e1-957">
  <strong>Desktop virtuale Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-957">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="662e1-958">Applicazioni virtualizzate che vengono eseguite su Windows Server Remote Desktop Session Host (RDSH) vengono eseguite anche nella multisessione di Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="662e1-958">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-959">Le app in esecuzione in qualsiasi ambiente VDI (Virtual Desktop Infrastructure) di Windows 7 o Windows 10 vengono eseguite anche in Windows 7 Enterprise e Windows 10 Enterprise come parte di Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="662e1-959">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-960">Le app che vengono eseguite su dispostivi client di Windows 7 o Windows 10, vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="662e1-960">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="662e1-961">
  <strong>Nota:</strong> Le esclusioni e le limitazioni per la compatibilità con più sessioni di Windows 10 Enterprise includono:</span><span class="sxs-lookup"><span data-stu-id="662e1-961">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="662e1-962">Reindirizzamento limitato dell'hardware.</span><span class="sxs-lookup"><span data-stu-id="662e1-962">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-963">Le app con uso intensivo di A/V possono essere eseguite a una capacità ridotta.</span><span class="sxs-lookup"><span data-stu-id="662e1-963">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="662e1-964">Le app a 16 bit non sono supportate per la versione Desktop virtuale Windows a 64 bit.</span><span class="sxs-lookup"><span data-stu-id="662e1-964">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="662e1-965">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="662e1-965">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="662e1-966"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-966"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="662e1-967"><strong>Dettagli della guida di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-967"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="662e1-968"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="662e1-968"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="662e1-969"><strong>Microsoft Edge</strong> (per i clienti con Windows 10 Enterprise)</span><span class="sxs-lookup"><span data-stu-id="662e1-969"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="662e1-970">Forniamo indicazioni per la distribuzione remota e assistenza per la compatibilità per: distribuzione di Microsoft Edge in Windows 10 Enterprise con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="662e1-970">We provide remote deployment guidance and compatibility assistance for: Deploying Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="662e1-971">Configurazione di Microsoft Edge (con i criteri di gruppo o la configurazione delle app di Intune e i criteri delle app di Intune).</span><span class="sxs-lookup"><span data-stu-id="662e1-971">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="662e1-972">Creare un inventario dell'elenco dei siti che potrebbero richiedere l'uso in modalità Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="662e1-972">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="662e1-973">Abilitazione della modalità Internet Explorer con l'elenco di siti dell'organizzazione esistente.</span><span class="sxs-lookup"><span data-stu-id="662e1-973">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="662e1-974">Inoltre, se si dispone di un'app Web o di un sito che funziona con Internet Explorer o Google Chrome e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema senza costi aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="662e1-974">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="662e1-975">Per altri dettagli, vedi <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure.</a></span><span class="sxs-lookup"><span data-stu-id="662e1-975">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="662e1-976">

<strong>Gli elementi seguenti non sono nell'ambito </strong>  
</span><span class="sxs-lookup"><span data-stu-id="662e1-976">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="662e1-977">Gestione dei progetti per la distribuzione di Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="662e1-977">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="662e1-978">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="662e1-978">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
