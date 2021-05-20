---
title: Prodotti e funzionalità
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che consente all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding corretto.
ms.openlocfilehash: f3d10392b3d5f5712ae2b40c0af36a4ddc953682
ms.sourcegitcommit: 48c1a68ecf668b849037beb05b5490c6b922e833
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/19/2021
ms.locfileid: "52570554"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="e8521-104">Prodotti e funzionalità</span><span class="sxs-lookup"><span data-stu-id="e8521-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="e8521-105">Servizi e scenari supportati da FastTrack</span><span class="sxs-lookup"><span data-stu-id="e8521-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="e8521-106">Questo argomento include informazioni dettagliate sugli scenari di carico di lavoro supportati da FastTrack e sulle aspettative dell'ambiente di origine necessarie prima di iniziare.</span><span class="sxs-lookup"><span data-stu-id="e8521-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="e8521-107">In base alla configurazione corrente, microsoft lavora con l'utente per creare un piano di correzione che consente all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding corretto.</span><span class="sxs-lookup"><span data-stu-id="e8521-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="e8521-108">FastTrack fornisce indicazioni per aiutarti prima con le funzionalità di base (comuni per tutti Microsoft Online Services) e quindi con l'onboarding di ogni servizio idoneo:</span><span class="sxs-lookup"><span data-stu-id="e8521-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="e8521-109">Generale</span><span class="sxs-lookup"><span data-stu-id="e8521-109">General</span></span>](#general)
  - [<span data-ttu-id="e8521-110">Sicurezza e conformità</span><span class="sxs-lookup"><span data-stu-id="e8521-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="e8521-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="e8521-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="e8521-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="e8521-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="e8521-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="e8521-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="e8521-114">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="e8521-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="e8521-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="e8521-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="e8521-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="e8521-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="e8521-117">Per informazioni sulle previsioni dell’ambiente di origine di Office 365 U.S. Government, vedere [Previsioni dell’ambiente di origine di Office 365 U.S. Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="e8521-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="e8521-118">Generale</span><span class="sxs-lookup"><span data-stu-id="e8521-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e8521-119"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e8521-120"><strong>Informazioni aggiuntive su FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e8521-121"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e8521-122"><strong>Onboarding di base</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="e8521-123">Forniamo indicazioni remote sull'onboarding di base, che prevede il provisioning dei servizi, il tenant e l'integrazione delle identità.</span><span class="sxs-lookup"><span data-stu-id="e8521-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="e8521-124">Include inoltre i passaggi per fornire una base per l'onboarding di servizi come Exchange Online, SharePoint Online e Microsoft Teams, inclusa una discussione su sicurezza, connettività di rete e <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">conformità.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="e8521-125">L'onboarding per uno o più servizi può iniziare al termine dell'onboarding di base.</span><span class="sxs-lookup"><span data-stu-id="e8521-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="e8521-126"></li>
</ul>  

<strong> Integrazione delle identità </strong></span><span class="sxs-lookup"><span data-stu-id="e8521-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="e8521-127">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="e8521-128">Preparazione delle identità di Active Directory locali per la sincronizzazione con Azure Active Directory (Azure AD), tra cui l'installazione e la configurazione di Azure AD Connessione (a foresta singola o multipla) e delle licenze (incluse le licenze basate su gruppo).</span><span class="sxs-lookup"><span data-stu-id="e8521-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="e8521-129">Creazione di identità cloud, tra cui importazione in blocco e licenze, incluso l'uso di licenze basate su gruppo.</span><span class="sxs-lookup"><span data-stu-id="e8521-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="e8521-130">Scelta e abilitazione del metodo di autenticazione corretto per il percorso cloud, Sincronizzazione hash password, Autenticazione pass-through o Active Directory Federation Services (AD FS).</span><span class="sxs-lookup"><span data-stu-id="e8521-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="e8521-131">Scelta e abilitazione di un'esperienza di autenticazione più comoda per gli utenti con autenticazione senza password (FIDO)2 o Microsoft Authenticator App).</span><span class="sxs-lookup"><span data-stu-id="e8521-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="e8521-132">Abilitazione di AD FS per i clienti con una singola foresta di Active Directory e identità sincronizzate con lo strumento di Connessione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="e8521-133">Questa operazione richiede Windows Server 2012 R2 Active Directory Federation Services 2.0 o versione successiva.</span><span class="sxs-lookup"><span data-stu-id="e8521-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="e8521-134">Migrazione dell'autenticazione da AD FS ad Azure AD tramite Sincronizzazione hash password o Autenticazione pass-through.</span><span class="sxs-lookup"><span data-stu-id="e8521-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="e8521-135">Migrazione di app pre-integrate (come le app SaaS (Software-as-a-Service) della raccolta di Azure AD) da AD FS ad Azure AD per single sign-on (SSO).</span><span class="sxs-lookup"><span data-stu-id="e8521-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="e8521-136">Abilitazione delle integrazioni di app SaaS con SSO dalla raccolta di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="e8521-137">Abilitazione del provisioning automatico degli utenti per le app SaaS pre-integrate elencate nell'elenco delle esercitazioni sull'integrazione delle <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">app</a> (limitate solo alle app SaaS della raccolta di Azure AD e solo al provisioning in uscita).</span><span class="sxs-lookup"><span data-stu-id="e8521-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="e8521-138"><strong>Abilitazione della rete </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="e8521-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="e8521-139">Nell'ambito del vantaggio FastTrack, si consiglia di utilizzare le procedure consigliate per la connessione ai servizi cloud per garantire i livelli più elevati di prestazioni di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="e8521-140"><strong>Foreste di Active Directory</strong> Il livello di foresta funzionale è impostato su Windows Server 2003 in poi, con la configurazione della foresta seguente:</span><span class="sxs-lookup"><span data-stu-id="e8521-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-141">Una foresta unica di Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e8521-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="e8521-142">Una singola foresta account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="e8521-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="e8521-143">Più foreste account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="e8521-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="e8521-144">Più foreste account di Active Directory con una delle foreste in posizione centrale nella foresta account di Active Directory contenente Exchange e/o Lync 2010, Lync 2013 o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="e8521-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="e8521-145">Più foreste account di Active Directory, ognuna con la propria organizzazione di Exchange.</span><span class="sxs-lookup"><span data-stu-id="e8521-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="e8521-146">Attività necessarie per la configurazione del tenant e l'integrazione con Azure Active Directory, se necessario.</span><span class="sxs-lookup"><span data-stu-id="e8521-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="e8521-147">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="e8521-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="e8521-148">Per gli scenari di Active Directory a più foreste, se lync 2010, Lync 2013 o Skype for Business viene distribuito, deve essere distribuito nella stessa foresta di Active Directory di Exchange.</span><span class="sxs-lookup"><span data-stu-id="e8521-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="e8521-149">Quando si implementano più foreste di Active Directory con più organizzazioni Exchange in una configurazione multi-ibrida di Exchange, gli spazi dei nomi dell'entità utente condivisa (UPN) tra foreste di origine non sono supportati.</span><span class="sxs-lookup"><span data-stu-id="e8521-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="e8521-150">Gli spazi dei nomi SMTP primari tra organizzazioni di Exchange devono essere separati.</span><span class="sxs-lookup"><span data-stu-id="e8521-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="e8521-151">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=845444">Distribuzioni ibride con più insiemi di strutture di Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="e8521-152">Per tutte le configurazioni di più foreste, la distribuzione di Active Directory Federation Services (AD FS) non è in ambito.</span><span class="sxs-lookup"><span data-stu-id="e8521-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="e8521-153">Per <a href="https://go.microsoft.com/fwlink/?linkid=2080150">assistenza, contattare</a> un partner Microsoft.</span><span class="sxs-lookup"><span data-stu-id="e8521-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e8521-154"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="e8521-155">Vengono fornite indicazioni per la distribuzione remota per:</span><span class="sxs-lookup"><span data-stu-id="e8521-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-156">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="e8521-157">Assegnazione dei contratti di licenza con l'utente finale e di licenze basate sul dispositivo utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="e8521-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="e8521-158">Installare Microsoft 365 Apps dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="e8521-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="e8521-159">Installazione delle app di Office Mobile (ad esempio Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) sui dispositivi iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="e8521-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="e8521-160">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="e8521-161">Selezione e configurazione di un'installazione locale o cloud.</span><span class="sxs-lookup"><span data-stu-id="e8521-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="e8521-162">Creazione del codice XML di configurazione dello Strumento di distribuzione di Office con lo Strumento di personalizzazione di Office o del codice XML nativo per configurare il pacchetto di distribuzione.</span><span class="sxs-lookup"><span data-stu-id="e8521-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="e8521-163">Distribuzione con Microsoft Endpoint Configuration Manager, che include una guida per la creazione del pacchetto di Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="e8521-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="e8521-164">Inoltre, se si dispone di una macro o di un componente aggiuntivo che funzionava con le versioni precedenti di Office e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema di compatibilità senza costi aggiuntivi tramite il programma App Assure.</span><span class="sxs-lookup"><span data-stu-id="e8521-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="e8521-165">Vedi la <strong>sezione App Assure</strong> di <a href="#windows-10">Windows 10</a> per altri dettagli.</span><span class="sxs-lookup"><span data-stu-id="e8521-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="e8521-166">Il software client online deve essere a un livello minimo, come definito nei requisiti di sistema per Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e8521-167"><strong>Integrità della rete</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="e8521-168">Forniamo indicazioni remote per ottenere e interpretare i dati chiave di connettività di rete dall'ambiente in uso che mostrano quanto i siti dell'organizzazione siano allineati ai principi di connettività <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">di rete</a>di Microsoft.</span><span class="sxs-lookup"><span data-stu-id="e8521-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="e8521-169">Questo evidenzia il punteggio di rete che influisce direttamente sulla velocità della migrazione, sull'esperienza utente, sulle prestazioni del servizio e sull'affidabilità.</span><span class="sxs-lookup"><span data-stu-id="e8521-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="e8521-170">Ti guideremo anche attraverso qualsiasi procedura di correzione evidenziata da questi dati per aiutarti a migliorare il punteggio di rete.</span><span class="sxs-lookup"><span data-stu-id="e8521-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="e8521-171">Microsoft 365 Accesso all'interfaccia di amministrazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="e8521-172">Sono necessarie versioni aggiornate Microsoft 365 app.</span><span class="sxs-lookup"><span data-stu-id="e8521-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="e8521-173">Servizi di posizione abilitati in base ai consigli sulle prestazioni di rete nell Microsoft 365 <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">admin center (anteprima)</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-173">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="e8521-174">Sicurezza e conformità</span><span class="sxs-lookup"><span data-stu-id="e8521-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e8521-175"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e8521-176"><strong>Informazioni aggiuntive su FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e8521-177"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="e8521-178"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="e8521-179">Forniamo indicazioni remote per proteggere le identità cloud per gli scenari seguenti.</span><span class="sxs-lookup"><span data-stu-id="e8521-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="e8521-180">

<strong>Infrastruttura di base sicura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="e8521-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="e8521-181">Configurazione e abilitazione dell'autenticazione avanzata per le identità, inclusa la protezione con Azure Multi-Factor Authentication (MFA) (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure MFA e la reimpostazione della password self-service ( SSPR).</span><span class="sxs-lookup"><span data-stu-id="e8521-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="e8521-182">Distribuzione di FIDO2 o Microsoft Authenticator App.</span><span class="sxs-lookup"><span data-stu-id="e8521-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="e8521-183">Per i clienti non Premium Azure AD, vengono fornite indicazioni per proteggere le identità usando le impostazioni predefinite di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="e8521-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="e8521-184">Per i clienti premium di Azure AD, vengono fornite indicazioni per proteggere le identità con l'accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="e8521-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="e8521-185">Rilevamento e blocco dell'uso di password deboli con Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="e8521-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="e8521-186">Protezione dell'accesso remoto alle app Web locali con il proxy dell'applicazione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="e8521-187">Abilitazione del rilevamento e correzione basati sui rischi con Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="e8521-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="e8521-188">Abilitazione di una schermata di accesso personalizzata, inclusi logo, testo e immagini con personalizzazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="e8521-189">Condivisione sicura di app e servizi con utenti guest con Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="e8521-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="e8521-190">Gestione dell'accesso per Office 365 amministratori con ruoli amministrativi incorporati RBAC (Role-Based Access Control) e per ridurre il numero di account amministratore con privilegi.</span><span class="sxs-lookup"><span data-stu-id="e8521-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="e8521-191">Configurazione dell'aggiunta ibrida di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="e8521-192">Configurazione dell'aggiunta ad Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="e8521-193">
  
<strong>Monitorare e creare report</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e8521-194">Abilitazione del monitoraggio remoto per AD FS, Azure AD Connessione e controller di dominio con Azure AD Connessione Health.</span><span class="sxs-lookup"><span data-stu-id="e8521-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="e8521-195">
  
<strong>Governance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e8521-196">Gestione del ciclo di vita dell'identità e dell'accesso di Azure AD su larga scala con la gestione dei diritti di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="e8521-197">Gestione delle appartenenze ai gruppi di Azure AD, dell'accesso alle app aziendali e delle assegnazioni di ruolo con le verifiche di accesso di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-198">Revisione delle Condizioni per l'utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-199">Gestione e controllo dell'accesso agli account di amministratore con privilegi con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="e8521-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="e8521-200">
  
<strong>Automazione ed efficienza </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e8521-201">Abilitazione di Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="e8521-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="e8521-202">Consentire agli utenti di creare e gestire la propria sicurezza cloud o Office 365 con la gestione dei gruppi self-service di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="e8521-203">Gestione dell'accesso delegato alle app aziendali con la gestione dei gruppi delegati di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="e8521-204">Abilitazione dei gruppi dinamici di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="e8521-205">Organizzazione delle app nel portale App personali tramite raccolte.</span><span class="sxs-lookup"><span data-stu-id="e8521-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e8521-206">Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione dei problemi identificati che impediscono l'integrazione con le funzionalità di azure AD e Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="e8521-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e8521-207"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="e8521-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="e8521-208">Per ulteriori informazioni su Azure Information Protection, vedere <strong>Microsoft Information Protection</strong> più avanti in questa tabella.</span><span class="sxs-lookup"><span data-stu-id="e8521-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="e8521-209"><strong>Individuazione & rispondi</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="e8521-210"><strong>Advanced eDiscovery</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="e8521-211">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="e8521-212">Creazione di un nuovo caso.</span><span class="sxs-lookup"><span data-stu-id="e8521-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="e8521-213">Mettere i custodi in attesa.</span><span class="sxs-lookup"><span data-stu-id="e8521-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="e8521-214">Esecuzione di ricerche.</span><span class="sxs-lookup"><span data-stu-id="e8521-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="e8521-215">Aggiunta di risultati della ricerca a un insieme da rivedere.</span><span class="sxs-lookup"><span data-stu-id="e8521-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="e8521-216">Esecuzione di analisi in un set di revisione.</span><span class="sxs-lookup"><span data-stu-id="e8521-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="e8521-217">Revisione e applicazione di tag ai documenti.</span><span class="sxs-lookup"><span data-stu-id="e8521-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="e8521-218">Esportazione di dati dal set di revisione.</span><span class="sxs-lookup"><span data-stu-id="e8521-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="e8521-219">Importazione di dati non Office 365 dati.</span><span class="sxs-lookup"><span data-stu-id="e8521-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="e8521-220"><strong>Controllo avanzato</strong> (supportato solo in E5)</span><span class="sxs-lookup"><span data-stu-id="e8521-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="e8521-221">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="e8521-222">Abilitazione del controllo avanzato.</span><span class="sxs-lookup"><span data-stu-id="e8521-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="e8521-223">Esecuzione di un'interfaccia utente del log di controllo della ricerca e comandi di PowerShell di controllo di base.</span><span class="sxs-lookup"><span data-stu-id="e8521-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="e8521-224">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e8521-225">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e8521-226">Revisione dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="e8521-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e8521-227">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="e8521-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e8521-228">Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="e8521-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e8521-229">Revisione del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="e8521-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e8521-230">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e8521-231">

<strong>L'ambito seguente non è disponibile </strong> 
</span><span class="sxs-lookup"><span data-stu-id="e8521-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="e8521-232">Script o codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="e8521-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="e8521-233">API eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="e8521-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="e8521-234">Connettori dati.</span><span class="sxs-lookup"><span data-stu-id="e8521-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="e8521-235">Limiti di conformità e filtri di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="e8521-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="e8521-236">Indagini sui dati.</span><span class="sxs-lookup"><span data-stu-id="e8521-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="e8521-237">Richieste dell'oggetto dei dati.</span><span class="sxs-lookup"><span data-stu-id="e8521-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="e8521-238">Revisione dei documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="e8521-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e8521-239">Conformità alle normative e ai requisiti del settore e regionale.</span><span class="sxs-lookup"><span data-stu-id="e8521-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e8521-240">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="e8521-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="e8521-241">A parte la <strong>parte relativa all'onboarding</strong> core in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="e8521-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="e8521-242"><strong>Insider Risk Management</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="e8521-243">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="e8521-244">Creazione di criteri e revisione delle impostazioni.</span><span class="sxs-lookup"><span data-stu-id="e8521-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="e8521-245">Accesso a report e avvisi.</span><span class="sxs-lookup"><span data-stu-id="e8521-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="e8521-246">Creare casi.</span><span class="sxs-lookup"><span data-stu-id="e8521-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="e8521-247">Creazione di modelli di avviso.</span><span class="sxs-lookup"><span data-stu-id="e8521-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="e8521-248">Linee guida per la creazione del connettore risorse umane.</span><span class="sxs-lookup"><span data-stu-id="e8521-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="e8521-249">

<strong> Conformità delle comunicazioni </strong></span><span class="sxs-lookup"><span data-stu-id="e8521-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="e8521-250">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="e8521-251">Creazione di criteri e revisione delle impostazioni.</span><span class="sxs-lookup"><span data-stu-id="e8521-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="e8521-252">Accesso a report e avvisi.</span><span class="sxs-lookup"><span data-stu-id="e8521-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="e8521-253">Creazione di modelli di avviso.</span><span class="sxs-lookup"><span data-stu-id="e8521-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="e8521-254">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e8521-255">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e8521-256">Revisione dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="e8521-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e8521-257">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="e8521-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e8521-258">Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="e8521-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e8521-259">Revisione del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="e8521-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e8521-260">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e8521-261">

<strong>L'ambito seguente non è disponibile </strong> 
</span><span class="sxs-lookup"><span data-stu-id="e8521-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="e8521-262">Creazione e gestione di Power Automate flussi.</span><span class="sxs-lookup"><span data-stu-id="e8521-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="e8521-263">Connettori dati (oltre il connettore HR).</span><span class="sxs-lookup"><span data-stu-id="e8521-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="e8521-264">Configurazioni di espressioni regolari personalizzate (RegEx).</span><span class="sxs-lookup"><span data-stu-id="e8521-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="e8521-265">Revisione dei documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="e8521-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e8521-266">Barriere d'informazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="e8521-267">Gestione degli accessi con privilegi.</span><span class="sxs-lookup"><span data-stu-id="e8521-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="e8521-268">Conformità alle normative e ai requisiti del settore e regionale.</span><span class="sxs-lookup"><span data-stu-id="e8521-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e8521-269">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="e8521-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="e8521-270">A parte la <strong>parte relativa all'onboarding</strong> core in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="e8521-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="e8521-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="e8521-272">Microsoft 365 Defender è una famiglia di prodotti di difesa aziendale unificata pre e post-violazione che coordina in modo nativo il rilevamento, la prevenzione, l'indagine e la risposta tra endpoint, identità, posta elettronica e app per fornire una protezione integrata da attacchi sofisticati.</span><span class="sxs-lookup"><span data-stu-id="e8521-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="e8521-273">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="e8521-274">Fornire una panoramica del centro Microsoft 365 sicurezza.</span><span class="sxs-lookup"><span data-stu-id="e8521-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="e8521-275">Esame degli incidenti tra prodotti, inclusa la messa a fuoco su ciò che è critico garantendo l'ambito di attacco completo, gli asset influenzati e le azioni di correzione automatizzate raggruppate tra loro.</span><span class="sxs-lookup"><span data-stu-id="e8521-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="e8521-276">Dimostrazione di Microsoft 365 Defender può orchestrare l'indagine di asset, utenti, dispositivi e cassette postali che potrebbero essere state compromesse tramite l'auto-correzione automatica.</span><span class="sxs-lookup"><span data-stu-id="e8521-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="e8521-277">Illustrando e fornendo esempi di come i clienti possono cercare in modo proattivo tentativi di intrusione e attività di violazione che influiscono su posta elettronica, dati, dispositivi e account in più set di dati.</span><span class="sxs-lookup"><span data-stu-id="e8521-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="e8521-278">Mostrare ai clienti come possono rivedere e migliorare la loro posizione di sicurezza in modo olistico usando Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="e8521-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="e8521-279"><strong>L'ambito seguente non è disponibile</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="e8521-280">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="e8521-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="e8521-281">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="e8521-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="e8521-282">Linee guida per la distribuzione o formazione su:</span><span class="sxs-lookup"><span data-stu-id="e8521-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="e8521-283">Come correggere o interpretare i vari tipi di avviso e le attività monitorate.</span><span class="sxs-lookup"><span data-stu-id="e8521-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="e8521-284">Come analizzare un utente, un computer, un percorso di movimento laterale o un'entità.</span><span class="sxs-lookup"><span data-stu-id="e8521-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="e8521-285">Ricerca personalizzata delle minacce.</span><span class="sxs-lookup"><span data-stu-id="e8521-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="e8521-286">Integrazione di informazioni di sicurezza e eventi (SIEM) o API.</span><span class="sxs-lookup"><span data-stu-id="e8521-286">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e8521-287"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-287"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="e8521-288">Microsoft Cloud App Security è un Cloud Access Security Broker (CASB) che offre visibilità avanzata, controllo sui viaggi dei dati e analisi sofisticate per identificare e contrastare le minacce informatiche in tutti i servizi cloud microsoft e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="e8521-288">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="e8521-289">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-289">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-290">Configurazione del portale, tra cui:</span><span class="sxs-lookup"><span data-stu-id="e8521-290">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="e8521-291">Importazione di gruppi di utenti.</span><span class="sxs-lookup"><span data-stu-id="e8521-291">Importing user groups.</span></span></li>
<li> <span data-ttu-id="e8521-292">Gestione dell'accesso e delle impostazioni dell'amministratore.</span><span class="sxs-lookup"><span data-stu-id="e8521-292">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="e8521-293">Definizione dell'ambito della distribuzione per selezionare determinati gruppi di utenti da monitorare o escludere dal monitoraggio.</span><span class="sxs-lookup"><span data-stu-id="e8521-293">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="e8521-294">Impostazione di intervalli e tag IP.</span><span class="sxs-lookup"><span data-stu-id="e8521-294">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="e8521-295">Personalizzare l'esperienza dell'utente finale con il logo e la messaggistica personalizzata.</span><span class="sxs-lookup"><span data-stu-id="e8521-295">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="e8521-296">Configurare l'individuazione cloud per fornire l'IT shadow usando:</span><span class="sxs-lookup"><span data-stu-id="e8521-296">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="e8521-297">Microsoft Defender per endpoint.</span><span class="sxs-lookup"><span data-stu-id="e8521-297">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="e8521-298">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="e8521-298">Zscaler.</span></span></li>
<li> <span data-ttu-id="e8521-299">iboss.</span><span class="sxs-lookup"><span data-stu-id="e8521-299">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="e8521-300">Connessione <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">di app in primo</a> piano tramite connettori di app.</span><span class="sxs-lookup"><span data-stu-id="e8521-300">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="e8521-301">Configurazione del controllo dell'app di accesso condizionale nei portali di accesso condizionale e Cloud App Security per applicare i controlli delle sessioni in tempo reale.</span><span class="sxs-lookup"><span data-stu-id="e8521-301">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="e8521-302">Distribuzione dei dashboard Cloud App Security e Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="e8521-302">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="e8521-303">Personalizzazione dei punteggi dei rischi delle app in base alle priorità dell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-303">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="e8521-304">Creazione di tag e categorie dell'app.</span><span class="sxs-lookup"><span data-stu-id="e8521-304">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="e8521-305">App che sanzionano e annullano l'applicazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-305">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="e8521-306">Utilizzo dei log attività e dei file.</span><span class="sxs-lookup"><span data-stu-id="e8521-306">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="e8521-307">Gestione delle app OAuth.</span><span class="sxs-lookup"><span data-stu-id="e8521-307">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="e8521-308">Informazioni sulla correlazione degli eventi imprevisti nel portale Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="e8521-308">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="e8521-309">Fornire assistenza alla configurazione con <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">i 20</a> casi d'uso principali per i casb (inclusa la creazione o l'aggiornamento di un massimo di sei (6) criteri) ad eccezione di:</span><span class="sxs-lookup"><span data-stu-id="e8521-309">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="e8521-310">Controllo della configurazione dell'ambiente Internet as a Service (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="e8521-310">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="e8521-311">Monitoraggio delle attività degli utenti per la protezione dalle minacce negli ambienti IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="e8521-311">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="e8521-312"><strong>L'ambito seguente non è disponibile</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-312"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="e8521-313">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="e8521-313">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="e8521-314">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="e8521-314">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="e8521-315">Configurazione dell'infrastruttura, dell'installazione o della distribuzione dei caricamenti automatici dei log per i report continui tramite Docker o un agente di raccolta log.</span><span class="sxs-lookup"><span data-stu-id="e8521-315">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="e8521-316">Per <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">ulteriori dettagli, vedere Top 20 use cases for CASBs.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-316">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="e8521-317">Creazione di un report snapshot di Cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="e8521-317">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="e8521-318">Blocco dell'utilizzo delle app tramite script di blocco.</span><span class="sxs-lookup"><span data-stu-id="e8521-318">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="e8521-319">Connessione di app personalizzate.</span><span class="sxs-lookup"><span data-stu-id="e8521-319">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="e8521-320">Integrazione con provider di identità di terze parti (IsP) e provider di prevenzione della perdita dei dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="e8521-320">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="e8521-321">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="e8521-321">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="e8521-322">Analisi e correzione automatizzate, inclusi i playbook Power Automate Microsoft.</span><span class="sxs-lookup"><span data-stu-id="e8521-322">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="e8521-323">Integrazione delle informazioni di sicurezza e degli eventi (SIEM) o delle API (incluso Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="e8521-323">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="e8521-324">Distribuzione di Cloud App Discovery come prova di concetto.</span><span class="sxs-lookup"><span data-stu-id="e8521-324">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="e8521-325"><strong>Microsoft Defender per endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-325"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="e8521-326">Microsoft Defender for Endpoint è una piattaforma progettata per aiutare le reti aziendali a prevenire, rilevare, analizzare e rispondere alle minacce avanzate.</span><span class="sxs-lookup"><span data-stu-id="e8521-326">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="e8521-327">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-328">Distribuzione delle tecnologie per proteggere gli endpoint.</span><span class="sxs-lookup"><span data-stu-id="e8521-328">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="e8521-329">Configurazione dei profili di protezione degli endpoint e di restrizione dei dispositivi.</span><span class="sxs-lookup"><span data-stu-id="e8521-329">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="e8521-330">Valutazione della versione del sistema operativo e della gestione dei dispositivi (inclusi Intune, Microsoft Endpoint Configuration Manager, oggetti Criteri di gruppo e configurazioni di terze parti), nonché lo stato dei servizi av di Windows Defender o di altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="e8521-330">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="e8521-331">Valutazione dello stato dei servizi di Windows av o altro software di sicurezza degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="e8521-331">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="e8521-332">Valutazione dei proxy e dei firewall che limitano il traffico di rete.</span><span class="sxs-lookup"><span data-stu-id="e8521-332">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="e8521-333">Abilitazione di Microsoft Defender per il servizio endpoint spiegando come distribuire un profilo dell'agente Defender for Endpoint usando un endpoint di onboarding.</span><span class="sxs-lookup"><span data-stu-id="e8521-333">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="e8521-334">Linee guida per la distribuzione, assistenza alla configurazione e formazione su:</span><span class="sxs-lookup"><span data-stu-id="e8521-334">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="e8521-335">Gestione delle minacce e delle vulnerabilità.</span><span class="sxs-lookup"><span data-stu-id="e8521-335">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-336">Riduzione della superficie di attacco.</span><span class="sxs-lookup"><span data-stu-id="e8521-336">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-337">Protezione di nuova generazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-337">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-338">Rilevamento e risposta degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="e8521-338">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-339">Indagine e correzione automatizzate.</span><span class="sxs-lookup"><span data-stu-id="e8521-339">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-340">Punteggio di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="e8521-340">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="e8521-341">Revisione di simulazioni ed esercitazioni (come scenari di pratica, malware contraffatto e indagini automatizzate).</span><span class="sxs-lookup"><span data-stu-id="e8521-341">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="e8521-342">Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="e8521-342">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="e8521-343">Integrazione di Microsoft Defender per Office 365 con Microsoft Defender per Endpoint.</span><span class="sxs-lookup"><span data-stu-id="e8521-343">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="e8521-344">Procedure dettagliate nel portale di Microsoft Defender Security Center.</span><span class="sxs-lookup"><span data-stu-id="e8521-344">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="e8521-345">I sistemi operativi seguenti:</span><span class="sxs-lookup"><span data-stu-id="e8521-345">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="e8521-346">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e8521-346">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-347">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="e8521-347">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-348">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="e8521-348">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-349">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="e8521-349">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-350">Windows Server Semi-Annual Channel (SAC) versione 1803.</span><span class="sxs-lookup"><span data-stu-id="e8521-350">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-351">macOS versioni 10.13, 10.14 e 10.15.</span><span class="sxs-lookup"><span data-stu-id="e8521-351">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="e8521-352">
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft Endpoint Configuration Manager (versione 2002 o successiva).</span><span class="sxs-lookup"><span data-stu-id="e8521-352">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="e8521-353"></li>
</ul>

<strong>L'ambito seguente non è disponibile </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-353"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="e8521-354">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="e8521-354">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="e8521-355">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="e8521-355">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="e8521-356">Gestione continua e risposta alle minacce.</span><span class="sxs-lookup"><span data-stu-id="e8521-356">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="e8521-357">Onboarding o configurazione per i seguenti agenti di Microsoft Defender for Endpoint:</span><span class="sxs-lookup"><span data-stu-id="e8521-357">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="e8521-358">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="e8521-358">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-359">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="e8521-359">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-360">Linux.</span><span class="sxs-lookup"><span data-stu-id="e8521-360">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-361">Dispositivi mobili (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="e8521-361">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="e8521-362">Virtual Desktop Infrastructure (VDI) (persistente o non persistente).</span><span class="sxs-lookup"><span data-stu-id="e8521-362">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e8521-363">Onboarding e configurazione del server:</span><span class="sxs-lookup"><span data-stu-id="e8521-363">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="e8521-364">Configurazione di un server proxy per le comunicazioni offline.</span><span class="sxs-lookup"><span data-stu-id="e8521-364">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-365">Configurazione dei pacchetti di distribuzione di Configuration Manager nelle versioni e nelle istanze di Configuration Manager di livello inferiore.</span><span class="sxs-lookup"><span data-stu-id="e8521-365">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-366">Onboarding dei server nel Centro sicurezza di Azure.</span><span class="sxs-lookup"><span data-stu-id="e8521-366">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-367">Server non gestiti da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="e8521-367">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="e8521-368">Onboarding e configurazione di macOS:</span><span class="sxs-lookup"><span data-stu-id="e8521-368">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="e8521-369">Distribuzione manuale basata su Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-369">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-370">Distribuzione basata su JAMF.</span><span class="sxs-lookup"><span data-stu-id="e8521-370">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="e8521-371">Altra distribuzione basata su prodotti di gestione dei dispositivi mobili (MDM).</span><span class="sxs-lookup"><span data-stu-id="e8521-371">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-372">Distribuzione manuale.</span><span class="sxs-lookup"><span data-stu-id="e8521-372">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="e8521-373">Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:</span><span class="sxs-lookup"><span data-stu-id="e8521-373">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="e8521-374">Isolamento basato su hardware.</span><span class="sxs-lookup"><span data-stu-id="e8521-374">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-375">Controllo dell'app.</span><span class="sxs-lookup"><span data-stu-id="e8521-375">App control.</span></span>  
  </li>
<li> <span data-ttu-id="e8521-376">Controllo dispositivo.</span><span class="sxs-lookup"><span data-stu-id="e8521-376">Device control.</span></span></li>
<li>  
  <span data-ttu-id="e8521-377">Protezione dagli exploit.</span><span class="sxs-lookup"><span data-stu-id="e8521-377">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-378">Firewall di rete.</span><span class="sxs-lookup"><span data-stu-id="e8521-378">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="e8521-379">Configurazione o gestione delle funzionalità di protezione degli account come:</span><span class="sxs-lookup"><span data-stu-id="e8521-379">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="e8521-380">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="e8521-380">Windows Hello</span></span></li>
<li> <span data-ttu-id="e8521-381">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="e8521-381">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="e8521-382">Configurazione o gestione di BitLocker.</span><span class="sxs-lookup"><span data-stu-id="e8521-382">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="e8521-383">Iscrizione o configurazione di Microsoft Threat Experts.</span><span class="sxs-lookup"><span data-stu-id="e8521-383">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="e8521-384">Configurazione o formazione che esamina le connessioni SIEM (Security Information and Event Management).</span><span class="sxs-lookup"><span data-stu-id="e8521-384">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="e8521-385">Iscrizione o configurazione di Microsoft Threat Protection (MTP).</span><span class="sxs-lookup"><span data-stu-id="e8521-385">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="e8521-386">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="e8521-386">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="e8521-387">Formazione o indicazioni su come usare o creare query Kusto.</span><span class="sxs-lookup"><span data-stu-id="e8521-387">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="e8521-388">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="e8521-388">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="e8521-389"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="e8521-389"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="e8521-390">Microsoft Defender per identità è una soluzione di sicurezza basata sul cloud che sfrutta i segnali di Active Directory locali per identificare, rilevare e analizzare minacce avanzate, identità compromesse ed azioni Insider dannose dirette all'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-390">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="e8521-391">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-391">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="e8521-392">Creazione dell'istanza di Defender per l'identità.</span><span class="sxs-lookup"><span data-stu-id="e8521-392">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="e8521-393">Connessione di Defender for Identity ad Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e8521-393">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="e8521-394">Valutare la preparazione dell'ambiente per distribuire il sensore Defender for Identity nei controller di dominio, tra cui:</span><span class="sxs-lookup"><span data-stu-id="e8521-394">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="e8521-395">Esecuzione dello strumento di ridimensionamento per la pianificazione della capacità delle risorse.</span><span class="sxs-lookup"><span data-stu-id="e8521-395">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="e8521-396">Esecuzione dello strumento di controllo per valutare la compatibilità dei controller di dominio con il sensore.</span><span class="sxs-lookup"><span data-stu-id="e8521-396">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="e8521-397">Distribuzione del sensore per acquisire e analizzare il traffico di rete e Windows eventi direttamente dai controller di dominio, tra cui:</span><span class="sxs-lookup"><span data-stu-id="e8521-397">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="e8521-398">Download del pacchetto del sensore.</span><span class="sxs-lookup"><span data-stu-id="e8521-398">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="e8521-399">Configurazione del sensore.</span><span class="sxs-lookup"><span data-stu-id="e8521-399">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="e8521-400">Installazione del sensore nel controller di dominio in modo invisibile all'utente.</span><span class="sxs-lookup"><span data-stu-id="e8521-400">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="e8521-401">Distribuzione del sensore nell'ambiente a più foreste.</span><span class="sxs-lookup"><span data-stu-id="e8521-401">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="e8521-402">Integrazione di Defender for Identity con Microsoft Cloud App Security (Cloud App Security non è necessaria la licenza).</span><span class="sxs-lookup"><span data-stu-id="e8521-402">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="e8521-403">Fornire indicazioni sulla distribuzione, assistenza alla configurazione e formazione su:</span><span class="sxs-lookup"><span data-stu-id="e8521-403">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="e8521-404">Ottimizzazione dell'ambiente per ridurre il "rumore".</span><span class="sxs-lookup"><span data-stu-id="e8521-404">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="e8521-405">Informazioni sul report di valutazione della postura di sicurezza dell'identità.</span><span class="sxs-lookup"><span data-stu-id="e8521-405">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="e8521-406">Informazioni sul punteggio di priorità dell'indagine dell'utente e sul rapporto di classificazione delle indagini degli utenti.</span><span class="sxs-lookup"><span data-stu-id="e8521-406">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="e8521-407">Informazioni sul report degli utenti inattivi.</span><span class="sxs-lookup"><span data-stu-id="e8521-407">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="e8521-408">Fornire opzioni di correzione per un account compromesso.</span><span class="sxs-lookup"><span data-stu-id="e8521-408">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="e8521-409">Facilitare la migrazione da Advanced Threat Analytics (ATA) a Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="e8521-409">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="e8521-410"><strong>L'ambito seguente non è disponibile</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-410"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="e8521-411">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="e8521-411">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="e8521-412">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="e8521-412">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="e8521-413">Distribuzione del sensore Defender for Identity, tra cui:</span><span class="sxs-lookup"><span data-stu-id="e8521-413">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="e8521-414">Pianificazione manuale della capacità.</span><span class="sxs-lookup"><span data-stu-id="e8521-414">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="e8521-415">Distribuzione del sensore in una capacità autonoma.</span><span class="sxs-lookup"><span data-stu-id="e8521-415">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="e8521-416">Distribuzione del sensore tramite una scheda nic (Network Interface Card) Per il teaming.</span><span class="sxs-lookup"><span data-stu-id="e8521-416">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="e8521-417">Distribuzione del sensore tramite uno strumento di terze parti.</span><span class="sxs-lookup"><span data-stu-id="e8521-417">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="e8521-418">Connessione al servizio cloud Defender for Identity tramite una connessione proxy Web.</span><span class="sxs-lookup"><span data-stu-id="e8521-418">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="e8521-419">Creazione e gestione di honeytoken.</span><span class="sxs-lookup"><span data-stu-id="e8521-419">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="e8521-420">Linee guida per la distribuzione o formazione su:</span><span class="sxs-lookup"><span data-stu-id="e8521-420">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="e8521-421">Correzione o interpretazione di vari tipi di avviso e attività monitorate.</span><span class="sxs-lookup"><span data-stu-id="e8521-421">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="e8521-422">Analisi di un utente, di un computer, di un percorso di spostamento laterale o di un'entità.</span><span class="sxs-lookup"><span data-stu-id="e8521-422">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="e8521-423">Minaccia o ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="e8521-423">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="e8521-424">Risposta agli eventi imprevisti.</span><span class="sxs-lookup"><span data-stu-id="e8521-424">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="e8521-425">Esercitazione sul laboratorio di avviso di sicurezza per Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="e8521-425">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="e8521-426">Fornire una notifica quando Defender for Identity rileva attività sospette inviando avvisi di sicurezza al server syslog tramite un sensore nominato.</span><span class="sxs-lookup"><span data-stu-id="e8521-426">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="e8521-427">Configurazione di Defender for Identity per eseguire query utilizzando il protocollo samr (Security Account Manager Remote) per identificare gli amministratori locali in computer specifici.</span><span class="sxs-lookup"><span data-stu-id="e8521-427">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="e8521-428">Configurazione delle soluzioni VPN per aggiungere informazioni dalla connessione VPN alla pagina del profilo di un utente.</span><span class="sxs-lookup"><span data-stu-id="e8521-428">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="e8521-429">Integrazione delle informazioni di sicurezza e degli eventi (SIEM) o delle API (incluso Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="e8521-429">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="e8521-430">Distribuzione di Defender per i sensori di identità come prova di concetto.</span><span class="sxs-lookup"><span data-stu-id="e8521-430">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="e8521-431">Active Directory distribuito.</span><span class="sxs-lookup"><span data-stu-id="e8521-431">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="e8521-432">I controller di dominio che intendi installare defender per i sensori di identità dispongono di connettività Internet al servizio cloud Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="e8521-432">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="e8521-433">Il firewall e il proxy devono essere aperti per comunicare con il servizio cloud Defender for Identity (\*.atp.azure.com la porta 443 deve essere aperta).</span><span class="sxs-lookup"><span data-stu-id="e8521-433">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="e8521-434">Controller di dominio in esecuzione in uno dei seguenti:</span><span class="sxs-lookup"><span data-stu-id="e8521-434">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="e8521-435">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="e8521-435">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="e8521-436">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="e8521-436">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="e8521-437">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="e8521-437">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="e8521-438">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="e8521-438">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="e8521-439">Windows Server 2019 con KB4487044 (OS Build 17763.316).</span><span class="sxs-lookup"><span data-stu-id="e8521-439">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="e8521-440"><strong>Microsoft Defender per Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-440"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="e8521-441">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-441">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-442">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="e8521-442">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="e8521-443">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="e8521-443">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="e8521-444">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="e8521-444">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="e8521-445">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="e8521-445">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e8521-446">A parte la <strong>parte relativa all'onboarding</strong> core in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="e8521-446">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="e8521-447"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-447"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="e8521-448">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-448">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-449">Creazione e pubblicazione di etichette e criteri di conservazione (supportati solo in E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-449">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="e8521-450">Gestione dei record (supportata solo in E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-450">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="e8521-451">Revisione della creazione del piano di file.</span><span class="sxs-lookup"><span data-stu-id="e8521-451">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="e8521-452">Creazione e gestione dei record (inclusi i record basati su eventi).</span><span class="sxs-lookup"><span data-stu-id="e8521-452">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="e8521-453">Revisione dell'eliminazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-453">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="e8521-454">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-454">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e8521-455">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-455">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e8521-456">Revisione dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="e8521-456">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e8521-457">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="e8521-457">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e8521-458">Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="e8521-458">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e8521-459">Revisione del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="e8521-459">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e8521-460">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-460">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e8521-461">

  <strong>L'ambito seguente non è disponibile </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-461">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="e8521-462">Sviluppo di un piano di gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="e8521-462">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="e8521-463">Connettori dati.</span><span class="sxs-lookup"><span data-stu-id="e8521-463">Data connectors.</span></span></li>
<li> <span data-ttu-id="e8521-464">Sviluppo dell'architettura delle informazioni in SharePoint.</span><span class="sxs-lookup"><span data-stu-id="e8521-464">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="e8521-465">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="e8521-465">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="e8521-466">Revisione dei documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="e8521-466">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e8521-467">Supporto per E3.</span><span class="sxs-lookup"><span data-stu-id="e8521-467">Support for E3.</span></span></li>
<li> <span data-ttu-id="e8521-468">Conformità alle normative e ai requisiti del settore e regionale.</span><span class="sxs-lookup"><span data-stu-id="e8521-468">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e8521-469">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="e8521-469">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="e8521-470">A parte la <strong>parte relativa all'onboarding</strong> core in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="e8521-470">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e8521-471"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-471"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="e8521-472">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-472">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-473">Classificazione dei dati (supportata in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-473">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e8521-474">Tipi di informazioni riservate (supportati in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-474">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e8521-475">Creazione di etichette di riservatezza (supportate in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-475">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e8521-476">Applicazione di etichette di riservatezza (supportate in E3 ed E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-476">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e8521-477">Classificatori trainabili (supportati in E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-477">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e8521-478">Conoscere i dati con Esplora contenuto ed Esplora attività (supportato in E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-478">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e8521-479">Pubblicazione di etichette con criteri (manuali e automatici) (supportati in E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-479">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e8521-480">Creazione di criteri di prevenzione della perdita dei dati degli endpoint (DLP) per Windows 10 dispositivi (supportati in E5).</span><span class="sxs-lookup"><span data-stu-id="e8521-480">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e8521-481">Creazione di criteri DLP per Microsoft Teams chat e canali.</span><span class="sxs-lookup"><span data-stu-id="e8521-481">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="e8521-482">

<strong> Compliance Manager</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-482">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e8521-483">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-483">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e8521-484">Revisione dei tipi di ruolo.</span><span class="sxs-lookup"><span data-stu-id="e8521-484">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e8521-485">Aggiunta e configurazione di valutazioni.</span><span class="sxs-lookup"><span data-stu-id="e8521-485">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e8521-486">Valutare la conformità implementando azioni di miglioramento e determinando l'impatto del punteggio di conformità.</span><span class="sxs-lookup"><span data-stu-id="e8521-486">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e8521-487">Revisione del mapping dei controlli incorporati e valutazione dei controlli.</span><span class="sxs-lookup"><span data-stu-id="e8521-487">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e8521-488">Generazione di un report all'interno di una valutazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-488">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e8521-489">

<strong> Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-489">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="e8521-490">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-490">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="e8521-491">Attivazione e configurazione del tenant.</span><span class="sxs-lookup"><span data-stu-id="e8521-491">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="e8521-492">Creazione e configurazione di etichette e criteri (supportati in P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="e8521-492">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="e8521-493">Applicazione della protezione delle informazioni ai documenti (supportata in P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="e8521-493">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="e8521-494">Classificare ed etichettare automaticamente le informazioni nelle app di Office (ad esempio Word, PowerPoint, Excel e Outlook) in esecuzione su Windows e usando il client Azure Information Protection (supportato in P2).</span><span class="sxs-lookup"><span data-stu-id="e8521-494">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="e8521-495">Individuazione e applicazione di etichette ai file in pausa tramite lo scanner di Azure Information Protection (supportato in P1 e P2).</span><span class="sxs-lookup"><span data-stu-id="e8521-495">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="e8521-496">Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e8521-496">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="e8521-497">Vengono inoltre fornite indicazioni per applicare la protezione tramite Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME) e prevenzione della perdita dei dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="e8521-497">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="e8521-498"><strong>L'ambito seguente non è disponibile </strong></span><span class="sxs-lookup"><span data-stu-id="e8521-498"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="e8521-499">Codice cliente.</span><span class="sxs-lookup"><span data-stu-id="e8521-499">Customer key.</span></span></li>
<li><span data-ttu-id="e8521-500">Sviluppo di espressioni regolari personalizzate (RegEx) per tipi di informazioni riservate.</span><span class="sxs-lookup"><span data-stu-id="e8521-500">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="e8521-501">Creazione o modifica di dizionari di parole chiave.</span><span class="sxs-lookup"><span data-stu-id="e8521-501">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="e8521-502">Script e codifica personalizzati.</span><span class="sxs-lookup"><span data-stu-id="e8521-502">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="e8521-503">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="e8521-503">Azure Purview.</span></span></li>
<li> <span data-ttu-id="e8521-504">Revisione dei documenti di progettazione, architetto e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="e8521-504">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e8521-505">Conformità alle normative e ai requisiti del settore e regionale.</span><span class="sxs-lookup"><span data-stu-id="e8521-505">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e8521-506">Implementazione pratica delle azioni di miglioramento consigliate per le valutazioni in Compliance Manager.</span><span class="sxs-lookup"><span data-stu-id="e8521-506">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="e8521-507">A parte la <strong>parte relativa all'onboarding</strong> di base in <a href="#general">Generale,</a>non esistono requisiti minimi di sistema ad eccezione di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="e8521-507">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="e8521-508"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-508"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="e8521-509">Le responsabilità preliminari del cliente includono:</span><span class="sxs-lookup"><span data-stu-id="e8521-509">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="e8521-510">Elenco dei percorsi di condivisione file da analizzare.</span><span class="sxs-lookup"><span data-stu-id="e8521-510">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="e8521-511">Tassonomia di classificazione approvata.</span><span class="sxs-lookup"><span data-stu-id="e8521-511">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="e8521-512">Informazioni su eventuali restrizioni o requisiti normativi relativi alla gestione delle chiavi.</span><span class="sxs-lookup"><span data-stu-id="e8521-512">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="e8521-513">Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-513">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="e8521-514">Etichette configurate per la classificazione e la protezione.</span><span class="sxs-lookup"><span data-stu-id="e8521-514">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="e8521-515">Tutti i prerequisiti per lo scanner di Azure Information Protection sono stati installati.</span><span class="sxs-lookup"><span data-stu-id="e8521-515">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="e8521-516">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisiti per l'installazione</a>e la distribuzione dello scanner di etichettatura unificata di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="e8521-516">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="e8521-517">Verificare che i dispositivi utente esercitino un sistema operativo supportato e che siano installati i prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="e8521-517">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="e8521-518">Per ulteriori dettagli, vedere quanto segue.</span><span class="sxs-lookup"><span data-stu-id="e8521-518">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="e8521-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span><span class="sxs-lookup"><span data-stu-id="e8521-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="e8521-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="e8521-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="e8521-521">Installazione e configurazione del connettore Azure RMS e dei server, incluso il connettore AD RMS (Active Directory RMS) per il supporto ibrido.</span><span class="sxs-lookup"><span data-stu-id="e8521-521">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="e8521-522">L'installazione e la configurazione di Bring Your Own Key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificato) o Hold Your Own Key (HYOK) (solo client classico) devono essere necessarie per una di queste opzioni per la distribuzione.</span><span class="sxs-lookup"><span data-stu-id="e8521-522">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="e8521-523"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-523"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="e8521-524">Forniamo indicazioni remote su come prepararsi a usare Intune come provider di gestione dei dispositivi mobili (MDM) e maM (Mobile App Management) basato su cloud per le tue app e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="e8521-524">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="e8521-525">I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili.</span><span class="sxs-lookup"><span data-stu-id="e8521-525">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="e8521-526">I passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="e8521-526">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-527">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="e8521-527">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="e8521-528">Configurazione delle identità che devono essere usate da Intune sfruttando Active Directory locale o le identità cloud (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="e8521-528">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="e8521-529">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="e8521-529">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="e8521-530">Configurazione dell'autorità MDM in base alle esigenze di gestione, tra cui:</span><span class="sxs-lookup"><span data-stu-id="e8521-530">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-531">Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.</span><span class="sxs-lookup"><span data-stu-id="e8521-531">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e8521-532">Fornire le indicazioni di MDM per:</span><span class="sxs-lookup"><span data-stu-id="e8521-532">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-533">Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.</span><span class="sxs-lookup"><span data-stu-id="e8521-533">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="e8521-534">Configurare criteri e servizi di gestione MDM come:</span><span class="sxs-lookup"><span data-stu-id="e8521-534">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-535">Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o collegamenti diretti.</span><span class="sxs-lookup"><span data-stu-id="e8521-535">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="e8521-536">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="e8521-536">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="e8521-537">Distribuzione di posta elettronica, reti wireless e profili VPN se nell'organizzazione è presente un'autorità di certificazione, una rete wireless o un'infrastruttura VPN.</span><span class="sxs-lookup"><span data-stu-id="e8521-537">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="e8521-538">Connessione al data warehouse di Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-538">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="e8521-539">Integrare Intune con:</span><span class="sxs-lookup"><span data-stu-id="e8521-539">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-540">Visualizzatore team per assistenza remota (è necessaria una sottoscrizione a Visualizzatore team).</span><span class="sxs-lookup"><span data-stu-id="e8521-540">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="e8521-541">Soluzioni per i partner di Mobile Threat Defense (MTD) (è necessaria una sottoscrizione MTD).</span><span class="sxs-lookup"><span data-stu-id="e8521-541">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="e8521-542">Una soluzione di gestione delle spese per le telecomunicazioni (è necessaria una sottoscrizione a una soluzione di gestione delle spese di telecomunicazione).</span><span class="sxs-lookup"><span data-stu-id="e8521-542">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="e8521-543">Registrare i dispositivi di ogni piattaforma supportata in Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-543">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="e8521-544">Fornire indicazioni sulla protezione delle app su:</span><span class="sxs-lookup"><span data-stu-id="e8521-544">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-545">Configurare criteri di protezione delle app per ogni piattaforma supportata.</span><span class="sxs-lookup"><span data-stu-id="e8521-545">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="e8521-546">Configurazione dei criteri di accesso condizionale per le app gestite.</span><span class="sxs-lookup"><span data-stu-id="e8521-546">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="e8521-547">Destinazione dei gruppi di utenti appropriati con i criteri MAM menzionati in precedenza.</span><span class="sxs-lookup"><span data-stu-id="e8521-547">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="e8521-548">Uso dei report di utilizzo delle app gestite.</span><span class="sxs-lookup"><span data-stu-id="e8521-548">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e8521-549">Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Mdm di Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-549">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="e8521-550">
 
</li>
</ul>
  
<strong>Collegamento tramite cloud</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-550">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="e8521-551">Ti guideremo per prepararti a collegare gli ambienti di Configuration Manager esistenti con Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-551">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="e8521-552">I passaggi esatti dipendono dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="e8521-552">The exact steps depend on your source environment.</span></span> <span data-ttu-id="e8521-553">Questi passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="e8521-553">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="e8521-554">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="e8521-554">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="e8521-555">Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.</span><span class="sxs-lookup"><span data-stu-id="e8521-555">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="e8521-556">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="e8521-556">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="e8521-557">Fornire indicazioni per la configurazione dell'aggiunta ibrida ad Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e8521-557">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="e8521-558">Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.</span><span class="sxs-lookup"><span data-stu-id="e8521-558">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="e8521-559">Fornisce indicazioni su come configurare il gateway di gestione cloud se usato come soluzione per la co-gestione della gestione remota dei dispositivi basati su Internet.</span><span class="sxs-lookup"><span data-stu-id="e8521-559">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="e8521-560">Configurare i carichi di lavoro supportati che si desidera passare a Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-560">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="e8521-561">Installare il client Configuration Manager nei dispositivi registrati di Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-561">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="e8521-562"><strong>Distribuire Outlook dispositivi mobili per iOS e Android in modo sicuro</strong> Possiamo fornire indicazioni per aiutarti a distribuire Outlook dispositivi mobili per iOS e Android in modo sicuro nell'organizzazione per assicurarti che gli utenti siano installate tutte le app necessarie.</span><span class="sxs-lookup"><span data-stu-id="e8521-562"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="e8521-563">La procedura per distribuire in modo sicuro Outlook dispositivi mobili per iOS e Android con Intune dipende dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="e8521-563">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="e8521-564">Può includere:</span><span class="sxs-lookup"><span data-stu-id="e8521-564">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-565">Download delle app Outlook per iOS e Android, Microsoft Authenticator e Portale aziendale Intune app tramite Apple App Store o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="e8521-565">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="e8521-566">Fornire indicazioni sulla configurazione:</span><span class="sxs-lookup"><span data-stu-id="e8521-566">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-567">La Outlook per iOS e Android, Microsoft Authenticator e Portale aziendale Intune distribuzione di app con Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-567">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="e8521-568">Criteri di protezione delle app.</span><span class="sxs-lookup"><span data-stu-id="e8521-568">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="e8521-569">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="e8521-569">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="e8521-570">Criteri di configurazione delle app.</span><span class="sxs-lookup"><span data-stu-id="e8521-570">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="e8521-571">Gli amministratori IT devono disporre di un'autorità di certificazione, di una rete wireless e di infrastrutture VPN esistenti già funzionanti nei propri ambienti di produzione durante la pianificazione della distribuzione di reti wireless e profili VPN con Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-571">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="e8521-572"><strong>Nota:</strong>il vantaggio del servizio FastTrack non include l'assistenza per la configurazione di Autorità di certificazione, reti wireless, infrastrutture VPN o certificati push MDM Apple per Intune.</span><span class="sxs-lookup"><span data-stu-id="e8521-572"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="e8521-573"><strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud.</span><span class="sxs-lookup"><span data-stu-id="e8521-573"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="e8521-574">Per <a href="https://go.microsoft.com/fwlink/?linkid=2080150">assistenza, contattare</a> un partner Microsoft.</span><span class="sxs-lookup"><span data-stu-id="e8521-574">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="e8521-575"><strong>Intune integrato con Microsoft Defender per Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-575"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="e8521-576"><strong>Nota:</strong>microsoft fornisce assistenza sull'integrazione di Intune con Microsoft Defender for Endpoint e sulla creazione di criteri di conformità dei dispositivi in base alla valutazione Windows 10 livello di rischio.</span><span class="sxs-lookup"><span data-stu-id="e8521-576"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="e8521-577">Non forniamo assistenza per l'acquisto, la gestione delle licenze o l'attivazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-577">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="e8521-578">Per <a href="https://go.microsoft.com/fwlink/?linkid=2080150">assistenza, contattare</a> un partner Microsoft.</span><span class="sxs-lookup"><span data-stu-id="e8521-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="e8521-579"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-579"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="e8521-580">Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="e8521-580">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="e8521-581">Office 365</span><span class="sxs-lookup"><span data-stu-id="e8521-581">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e8521-582"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-582"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e8521-583"><strong>Informazioni aggiuntive su FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-583"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e8521-584"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-584"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e8521-585"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-585"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="e8521-586">For Exchange Online, we guide you through the process to get your organization ready to use email.</span><span class="sxs-lookup"><span data-stu-id="e8521-586">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="e8521-587">I passaggi esatti dipendono dall'ambiente di origine e dai piani di migrazione della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="e8521-587">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="e8521-588">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-588">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-589">Configurare le funzionalità di Exchange Online Protection (EOP) per tutti i domini abilitati alla posta elettronica convalidati in Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-589">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e8521-590">Puntare i record MX (Mail Exchange) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-590">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e8521-591">Configurare la funzionalità Microsoft Defender for Office 365 se fa parte del servizio di sottoscrizione.</span><span class="sxs-lookup"><span data-stu-id="e8521-591">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="e8521-592">Per altre informazioni, vedi <strong>microsoft Defender per Office 365</strong> parte di questa tabella.</span><span class="sxs-lookup"><span data-stu-id="e8521-592">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="e8521-p127">Configurare la funzionalità di prevenzione della perdita dei dati (DLP) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="e8521-p128">Configurare Office 365 Message Encryption (OME) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="e8521-597">
  <strong>Nota:</strong> Il servizio di replica delle cassette postali tenta di eseguire la migrazione dei messaggi di posta elettronica di Information Rights Managed (IRM) dalla cassetta postale locale alla cassetta postale Exchange Online corrispondente.</span><span class="sxs-lookup"><span data-stu-id="e8521-597">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="e8521-598">La possibilità di leggere i contenuti protetti dopo la migrazione dipende dal fatto che il cliente esegua il mapping e copi i modelli di Active Directory Rights Managed Services (AD RMS) in Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="e8521-598">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="e8521-599">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="e8521-599">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="e8521-600">Configurazione di DNS, tra cui l'individuazione automatica necessaria, il framework dei criteri mittente (SPF), la posta identificata da DomainKeys (DKIM), l'autenticazione dei messaggi basata su dominio, la creazione di report e conformità (DMARC) e i record MX (in base alle esigenze).</span><span class="sxs-lookup"><span data-stu-id="e8521-600">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="e8521-601">Configurare il flusso di posta elettronica tra l'ambiente di messaggistica di origine e Exchange Online (in base alle esigenze).</span><span class="sxs-lookup"><span data-stu-id="e8521-601">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="e8521-602">Eseguire la migrazione della posta dall'ambiente di messaggistica di origine a Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-602">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e8521-603">Configurazione di client delle cassette postali (Outlook per Windows, Outlook sul web e Outlook per iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="e8521-603">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="e8521-604">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="e8521-604">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="e8521-605">Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-605">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="e8521-606">L'ambiente di origine deve avere uno dei livelli minimi seguenti:</span><span class="sxs-lookup"><span data-stu-id="e8521-606">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-607">Una o più organizzazioni di Exchange con Exchange Server 2003 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="e8521-607">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="e8521-608">Un singolo ambiente di posta elettronica abilitato per il protocollo IMAP.</span><span class="sxs-lookup"><span data-stu-id="e8521-608">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="e8521-609">Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).</span><span class="sxs-lookup"><span data-stu-id="e8521-609">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="e8521-610">Per informazioni sulle funzionalità multi-geografiche, vedere <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-610">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="e8521-611">Il software client online come Project per Office 365, Outlook per Windows, Outlook per iOS e Android, client di sincronizzazione OneDrive for Business, Power BI Desktop e Skype for Business deve essere al livello minimo, come definito in Requisiti di sistema per <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-611">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="e8521-612"><strong>Microsoft Defender per Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-612"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="e8521-613">Per altre informazioni, vedi <strong>Microsoft Defender per Office 365</strong> sicurezza e <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">conformità.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-613">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="e8521-614"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-614"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="e8521-615">Per ulteriori informazioni, vedere <strong>Governance delle informazioni Microsoft</strong> in Sicurezza e <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">conformità.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-615">For more information, see <strong> Microsoft Information Governance</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e8521-616"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-616"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="e8521-617">Per ulteriori informazioni, vedere <strong>Microsoft Information Protection</strong> in Security and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-617">For more information, see <strong>Microsoft Information Protection </strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="e8521-618"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-618"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="e8521-619">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-619">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-620">Conferma dei requisiti minimi in Exchange Online, SharePoint Online, Office 365 gruppi e Azure AD per supportare Teams.</span><span class="sxs-lookup"><span data-stu-id="e8521-620">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="e8521-621">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="e8521-621">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="e8521-622">Configurazione di DNS.</span><span class="sxs-lookup"><span data-stu-id="e8521-622">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="e8521-623">Conferma dell'abilitazione di Teams nel tenant Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-623">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="e8521-624">Abilitazione o disabilitazione delle licenze utente.</span><span class="sxs-lookup"><span data-stu-id="e8521-624">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="e8521-625">Valutazione della rete per Teams:</span><span class="sxs-lookup"><span data-stu-id="e8521-625">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-626">Controlli di porta ed endpoint.</span><span class="sxs-lookup"><span data-stu-id="e8521-626">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="e8521-627">Controlli sulla qualità della connessione.</span><span class="sxs-lookup"><span data-stu-id="e8521-627">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="e8521-628">Stime sulla larghezza di banda.</span><span class="sxs-lookup"><span data-stu-id="e8521-628">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="e8521-629">Configurazione dei Teams app (Teams app Web, Teams desktop e Teams per app iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="e8521-629">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="e8521-630">Se applicabile, forniamo anche indicazioni per:</span><span class="sxs-lookup"><span data-stu-id="e8521-630">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-631">Microsoft Teams Dispositivi sala:</span><span class="sxs-lookup"><span data-stu-id="e8521-631">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="e8521-632">Creazione di account online necessari per i dispositivi di telefonia e di sala riunioni supportati elencati nel <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogo dei dispositivi Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-632">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="e8521-633">Assistenza remota con la configurazione sul lato servizio di dispositivi Microsoft Teams Rooms certificati.</span><span class="sxs-lookup"><span data-stu-id="e8521-633">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="e8521-634">Abilitazione dell'audioconferenza:</span><span class="sxs-lookup"><span data-stu-id="e8521-634">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="e8521-635">Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.</span><span class="sxs-lookup"><span data-stu-id="e8521-635">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="e8521-636">Assegnazione di bridge per conferenze agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="e8521-636">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="e8521-637">Sistema telefonico:</span><span class="sxs-lookup"><span data-stu-id="e8521-637">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-638">Configurazione aziendale delle impostazioni predefinite vocali cloud.</span><span class="sxs-lookup"><span data-stu-id="e8521-638">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="e8521-639">Indicazioni per i piani di chiamata (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercati disponibili</a>):</span><span class="sxs-lookup"><span data-stu-id="e8521-639">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="e8521-640">Assegnazione di numeri agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="e8521-640">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="e8521-641">Guida alla portabilità del numero locale tramite UI fino a 999.</span><span class="sxs-lookup"><span data-stu-id="e8521-641">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="e8521-642">Supporto RS per la richiesta di servizio di portabilità del numero locale superiore a 999.</span><span class="sxs-lookup"><span data-stu-id="e8521-642">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e8521-643">Linee guida per l'instradamento diretto:</span><span class="sxs-lookup"><span data-stu-id="e8521-643">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-644">Indicazioni per la configurazione dell'organizzazione per la progettazione del routing diretto di scenari ospitati da partner o scenari distribuiti dal cliente per un massimo di 10 siti.</span><span class="sxs-lookup"><span data-stu-id="e8521-644">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="e8521-645">Session Border Controller (SBC) configuration review.</span><span class="sxs-lookup"><span data-stu-id="e8521-645">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="e8521-646">Assistenza remota con la configurazione del dial plan.</span><span class="sxs-lookup"><span data-stu-id="e8521-646">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="e8521-647">Configurazione delle route vocali.</span><span class="sxs-lookup"><span data-stu-id="e8521-647">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="e8521-648">Bypass multimediale e ottimizzazione multimediale locale.</span><span class="sxs-lookup"><span data-stu-id="e8521-648">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="e8521-649">Abilitazione degli eventi live in Teams.</span><span class="sxs-lookup"><span data-stu-id="e8521-649">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="e8521-650">Configurazione dell'organizzazione e integrazione in Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="e8521-650">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="e8521-651">Linee guida per Skype for Business a Teams transizione.</span><span class="sxs-lookup"><span data-stu-id="e8521-651">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="e8521-652">Identità abilitate in Azure AD per Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-652">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e8521-653">Utenti abilitati per SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e8521-653">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="e8521-654">Exchange sono presenti cassette postali (online e locali in una Exchange ibrida).</span><span class="sxs-lookup"><span data-stu-id="e8521-654">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="e8521-655">Abilitato per i gruppi di Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-655">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="e8521-656">
  <strong>Nota:</strong> Se gli utenti non sono assegnati e abilitati con SharePoint Online, non diseranno OneDrive for Business archiviazione in Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-656">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="e8521-657">La condivisione dei file continua a funzionare nei canali, ma gli utenti non possono condividere file in Chat senza OneDrive for Business archiviazione in Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-657">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="e8521-658">Teams non supporta SharePoint locale.</span><span class="sxs-lookup"><span data-stu-id="e8521-658">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="e8521-659">
  <strong>Nota:</strong> Lo stato ideale è che tutti gli utenti hanno le loro cassette postali ospitate Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e8521-659">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="e8521-660">Gli utenti con cassette postali ospitate in locale devono avere le proprie identità sincronizzate con la directory Office 365 tramite Azure AD Connessione.</span><span class="sxs-lookup"><span data-stu-id="e8521-660">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="e8521-661">Per questi Exchange ibridi, se la cassetta postale dell'utente è locale, l'utente non può aggiungere o configurare i connettori.</span><span class="sxs-lookup"><span data-stu-id="e8521-661">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="e8521-662">I programmi di installazione per i client desktop di Microsoft Teams per Windows e Mac possono essere scaricati da <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-662">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="e8521-663"><strong>Outlook per iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-663"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="e8521-664">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-665">Download di Outlook per iOS e Android tramite l'Apple App Store e Google Play.</span><span class="sxs-lookup"><span data-stu-id="e8521-665">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="e8521-666">Configurazione degli account e accesso alla cassetta postale di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e8521-666">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="e8521-667">Protezione Outlook dispositivi mobili (per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online).</a></span><span class="sxs-lookup"><span data-stu-id="e8521-667">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="e8521-668">Identità abilitate in Azure AD per Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-668">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e8521-669">Exchange Online configurato e licenze assegnate.</span><span class="sxs-lookup"><span data-stu-id="e8521-669">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e8521-670"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-670"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="e8521-671">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-671">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-672">Assegnare licenze di Power BI.</span><span class="sxs-lookup"><span data-stu-id="e8521-672">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="e8521-673">Distribuire l'app Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="e8521-673">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e8521-674">Il software client online Power BI Desktop deve essere al livello minimo definito nei requisiti di sistema per Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-674">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e8521-675"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-675"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="e8521-676">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-676">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-677">Verificare la funzionalità di base di SharePoint sulla quale fa affidamento Project Online.</span><span class="sxs-lookup"><span data-stu-id="e8521-677">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="e8521-678">Aggiungere il servizio Project Online al tenant (inclusa l'aggiunta di sottoscrizioni per gli utenti).</span><span class="sxs-lookup"><span data-stu-id="e8521-678">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="e8521-679">Configurare il pool di risorse organizzazione (ERP).</span><span class="sxs-lookup"><span data-stu-id="e8521-679">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="e8521-680">Creare il primo progetto.</span><span class="sxs-lookup"><span data-stu-id="e8521-680">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e8521-681">Il software client online Project per Office 365 deve essere al livello minimo definito nei requisiti di sistema per Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-681">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e8521-682"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-682"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="e8521-683">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-683">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-684">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-684">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="e8521-685">Assegnare i contratti di licenza con l'utente finale utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="e8521-685">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="e8521-686">Installare Client desktop di Project Online dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="e8521-686">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="e8521-687">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-687">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="e8521-688">Configurare un unico server di distribuzione nel sito per Client desktop di Project Online, includendo una guida per la creazione del file configuration.xml da usare con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-688">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="e8521-689">Connettere Client desktop di Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="e8521-689">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e8521-690">Il software client online Project per Office 365 deve essere al livello minimo definito nei requisiti di sistema per Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-690">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e8521-691"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-691"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="e8521-692">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-692">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-693">Configurazione DNS.</span><span class="sxs-lookup"><span data-stu-id="e8521-693">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="e8521-694">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="e8521-694">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="e8521-695">Provisioning di utenti e licenze.</span><span class="sxs-lookup"><span data-stu-id="e8521-695">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="e8521-696">Abilitazione alla creazione di siti per l'amministratore di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e8521-696">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="e8521-697">Pianificazione delle raccolte di siti.</span><span class="sxs-lookup"><span data-stu-id="e8521-697">Planning site collections.</span></span></li>
<li><span data-ttu-id="e8521-698">Protezione del contenuto e gestione delle autorizzazioni.</span><span class="sxs-lookup"><span data-stu-id="e8521-698">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="e8521-699">Configurazione delle caratteristiche di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e8521-699">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="e8521-700">Configurazione delle funzionalità dell'ambiente ibrido di SharePoint, come la ricerca ibrida, i siti ibridi, la tassonomia ibrida, i tipi di contenuto, la creazione siti in modalità self-service ibrida (solo SharePoint Server 2013), l'icona di avvio delle app estesa, OneDrive for Business ibrido e i siti extranet.</span><span class="sxs-lookup"><span data-stu-id="e8521-700">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="e8521-701">Approccio alla migrazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-701">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="e8521-702">Vengono fornite ulteriori indicazioni per OneDrive for Business a seconda della versione SharePoint, ad esempio:</span><span class="sxs-lookup"><span data-stu-id="e8521-702">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-703">Identificazione delle opzioni di integrazione e revisione dell'infrastruttura di rete locale e online e della larghezza di banda.</span><span class="sxs-lookup"><span data-stu-id="e8521-703">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="e8521-704">Installazione di SharePoint Online 2013 SP1 (se applicabile), pianificazione e implementazione dei requisiti di sincronizzazione e identità e identificazione del client OneDrive for Business sincronizzazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-704">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="e8521-705">Pianificazione e implementazione di una singola implementazione per tutti gli utenti (o un'implementazione in più fasi).</span><span class="sxs-lookup"><span data-stu-id="e8521-705">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="e8521-706">Assegnazione di licenze, reindirizzamento dei siti personali e delle raccolte documenti personali a Office 365 (applicabile a SharePoint Online 2013), configurazione dei gruppi di destinatari per controllare l'accesso a OneDrive (applicabile a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="e8521-706">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="e8521-707">Reindirizzamento o spostamento di cartelle note in OneDrive.</span><span class="sxs-lookup"><span data-stu-id="e8521-707">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="e8521-708">Distribuzione della sincronizzazione OneDrive for Business client.</span><span class="sxs-lookup"><span data-stu-id="e8521-708">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="e8521-709">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="e8521-709">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="e8521-710">Per informazioni sull'uso del vantaggio FastTrack per la migrazione dei dati Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-710">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="e8521-711"><strong>Per SharePoint ibrido:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-711"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="e8521-712">la configurazione ibrida di SharePoint include la configurazione di ricerca ibrida, siti, tassonomia, tipi di contenuto, OneDrive for Business, un'icona di avvio delle app estesa, siti Extranet e creazione siti in modalità self-service connessi da locale a un singolo ambiente SharePoint online di destinazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-712">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="e8521-713">
  <strong>Nota:</strong> La creazione siti in modalità self-service non è in ambito con i server locali che eseguono SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="e8521-713">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="e8521-714">Per abilitare SharePoint ibrido, è necessario disporre di uno dei seguenti ambienti SharePoint Server locali: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="e8521-714">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="e8521-715">
  <strong>Nota:</strong> L'aggiornamento degli ambienti SharePoint locali a SharePoint Server non è nell'ambito.</span><span class="sxs-lookup"><span data-stu-id="e8521-715">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="e8521-716">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza.</span><span class="sxs-lookup"><span data-stu-id="e8521-716">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="e8521-717">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="e8521-717">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="e8521-718">
  <strong>Nota:</strong> Per informazioni sulle funzionalità multi-geografiche, vedere <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="e8521-718">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e8521-719"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-719"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="e8521-720">Forniamo indicazioni remote per abilitare il servizio Yammer Enterprise remoto.</span><span class="sxs-lookup"><span data-stu-id="e8521-720">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="e8521-721">Il software client online deve essere a un livello minimo, come definito nei requisiti di sistema per Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-721">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="e8521-722">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="e8521-722">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e8521-723"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-723"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e8521-724"><strong>Informazioni aggiuntive su FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-724"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e8521-725"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-725"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="e8521-726"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-726"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="e8521-727">Per ulteriori informazioni, vedere <strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong> in Sicurezza e <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">conformità.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-727">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e8521-728"><strong>Azure Information Protection </strong></span><span class="sxs-lookup"><span data-stu-id="e8521-728"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="e8521-729">Per altre informazioni su Azure Information Protection, vedi <strong>Microsoft Information Protection</strong> in Sicurezza e <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> conformità.</span><span class="sxs-lookup"><span data-stu-id="e8521-729">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="e8521-730"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-730"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="e8521-731">Per ulteriori informazioni, vedere <strong>Microsoft Intune</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Sicurezza e conformità.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-731">For more information, see <strong> Microsoft Intune</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="e8521-732">Windows 10</span><span class="sxs-lookup"><span data-stu-id="e8521-732">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e8521-733"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-733"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e8521-734"><strong>Informazioni aggiuntive su FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-734"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e8521-735"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-735"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e8521-736"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-736"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="e8521-737">Vengono fornite indicazioni per l'aggiornamento da Windows 7 Professional e Windows 8.1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="e8521-737">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="e8521-738">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-738">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-739">Comprendere l'Windows 10 intenzione.</span><span class="sxs-lookup"><span data-stu-id="e8521-739">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="e8521-740">Valutare l'ambiente di origine e i requisiti (assicurarsi che Microsoft Endpoint Configuration Manager l'aggiornamento al livello necessario per supportare la Windows 10 distribuzione).</span><span class="sxs-lookup"><span data-stu-id="e8521-740">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="e8521-741">Distribuzione di Windows 10 Enterprise e Microsoft 365 Apps usando Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-741">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="e8521-742">Consigliando le opzioni per valutare le tue Windows 10 app.</span><span class="sxs-lookup"><span data-stu-id="e8521-742">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="e8521-743">Abilitazione dell'uso di Desktop Analytics e indicazioni tramite la creazione di un piano di distribuzione di Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="e8521-743">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="e8521-744">Microsoft 365 Apps la valutazione della compatibilità sfruttando il dashboard di conformità di Office 365 in Configuration Manager o con readiness Toolkit per Office autonomo e assistenza per la distribuzione di Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="e8521-744">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="e8521-745">Creazione di un elenco di controllo di correzione sulle operazioni da eseguire per portare l'ambiente di origine ai requisiti minimi per una corretta distribuzione.</span><span class="sxs-lookup"><span data-stu-id="e8521-745">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="e8521-746">Fornire indicazioni per l'aggiornamento per i dispositivi Windows 10 Enterprise se soddisfano i requisiti hardware dei dispositivi necessari.</span><span class="sxs-lookup"><span data-stu-id="e8521-746">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="e8521-747">Fornire indicazioni sull'aggiornamento per supportare il movimento di distribuzione esistente.</span><span class="sxs-lookup"><span data-stu-id="e8521-747">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="e8521-748">FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e8521-748">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="e8521-749">Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="e8521-749">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="e8521-750">La distribuzione Microsoft 365 Apps tramite Configuration Manager come parte della Windows 10 distribuzione.</span><span class="sxs-lookup"><span data-stu-id="e8521-750">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="e8521-751">Fornire indicazioni per aiutare l'organizzazione a rimanere aggiornata con Windows 10 Enterprise e Microsoft 365 Apps utilizzando l'ambiente configuration manager esistente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-751">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="e8521-752">
  
<strong>L'ambito seguente non è disponibile </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-752">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="e8521-753">Aggiornamento di Configuration Manager al Current Branch.</span><span class="sxs-lookup"><span data-stu-id="e8521-753">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="e8521-754">Creazione di immagini personalizzate per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e8521-754">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="e8521-755">Creazione e supporto degli script di distribuzione per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e8521-755">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="e8521-756">Conversione di un sistema di Windows 10 dal BIOS a Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="e8521-756">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="e8521-757">Abilitare le funzionalità di sicurezza di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e8521-757">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="e8521-758">Configurazione di Windows Deployment Services (WDS) per il boot di Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="e8521-758">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="e8521-759">Uso di Microsoft Deployment Toolkit (MDT) per acquisire e distribuire immagini di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e8521-759">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="e8521-760">Uso dell’Utilità di migrazione dello stato utente (USMT).</span><span class="sxs-lookup"><span data-stu-id="e8521-760">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="e8521-761">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="e8521-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="e8521-762">Per l'aggiornamento del PC, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="e8521-762">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-763">Sistema operativo di origine: Windows 7 Enterprise o Professional, Windows 8.1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="e8521-763">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="e8521-764">Dispositivi: fattore di forma per desktop, blocco appunti o tablet.</span><span class="sxs-lookup"><span data-stu-id="e8521-764">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="e8521-765">Sistema operativo di destinazione: finestra 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="e8521-765">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="e8521-766">Per l'aggiornamento dell'infrastruttura, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="e8521-766">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-767">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="e8521-767">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="e8521-768">La versione di Configuration Manager deve essere supportata dalla Windows 10 di destinazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-768">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="e8521-769">Per altre informazioni, vedere la tabella di supporto di Configuration Manager in <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Supporto per Windows 10 in Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-769">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="e8521-770"><strong>Microsoft Defender per endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-770"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="e8521-771">Per altre informazioni, vedi <strong>Microsoft Defender per Endpoint</strong> in Sicurezza e <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">conformità.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-771">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="e8521-772">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="e8521-772">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e8521-773"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-773"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e8521-774"><strong>Informazioni aggiuntive su FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-774"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e8521-775"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-775"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e8521-776"><strong>Desktop virtuale Windows</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-776"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="e8521-777">Forniamo indicazioni per la distribuzione per l'onboarding Windows desktop virtuale (un servizio di virtualizzazione desktop e app).</span><span class="sxs-lookup"><span data-stu-id="e8521-777">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="e8521-778">Windows Virtual Desktop sfrutta l'esperienza Windows 10 multi-sessione ed è ottimizzato per Microsoft 365 Apps per Enterprise con sicurezza e gestione integrate per Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e8521-778">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="e8521-779">Forniamo indicazioni remote per:</span><span class="sxs-lookup"><span data-stu-id="e8521-779">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="e8521-780">Distribuzione dell'Windows desktop virtuale con Windows 10 Enterprise multi-sessione e Microsoft 365 Apps per Enterprise utilizzando quanto segue:</span><span class="sxs-lookup"><span data-stu-id="e8521-780">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="e8521-781">Immagine di Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="e8521-781">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="e8521-782">Immagine condivisa.</span><span class="sxs-lookup"><span data-stu-id="e8521-782">Shared image.</span></span></li>
<li><span data-ttu-id="e8521-783">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="e8521-783">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="e8521-784">Configurazione di FSLogix:</span><span class="sxs-lookup"><span data-stu-id="e8521-784">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="e8521-785">Distribuzione dell'agente FSLogix con contenitore di profili.</span><span class="sxs-lookup"><span data-stu-id="e8521-785">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="e8521-786">Distribuzione dell'agente FSLogix con Office contenitore.</span><span class="sxs-lookup"><span data-stu-id="e8521-786">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="e8521-787">Configurazione della cartella FSLogix con esclusioni di contenuto.</span><span class="sxs-lookup"><span data-stu-id="e8521-787">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="e8521-788">Distribuzione di Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="e8521-788">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="e8521-789">Distribuzione di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="e8521-789">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="e8521-790">Connessione tramite Windows client Desktop virtuale.</span><span class="sxs-lookup"><span data-stu-id="e8521-790">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="e8521-791">

<strong>L'ambito seguente non è disponibile</strong>
</span><span class="sxs-lookup"><span data-stu-id="e8521-791">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="e8521-792">Project della distribuzione di Desktop virtuale Windows del cliente.</span><span class="sxs-lookup"><span data-stu-id="e8521-792">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="e8521-793">Virtualizzazione e distribuzione di app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="e8521-793">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="e8521-794">Immagini personalizzate.</span><span class="sxs-lookup"><span data-stu-id="e8521-794">Custom images.</span></span></li>
<li><span data-ttu-id="e8521-795">Migrazioni e scenari che coinvolgono VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="e8521-795">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="e8521-796">Scenari Linux.</span><span class="sxs-lookup"><span data-stu-id="e8521-796">Linux scenarios.</span></span></li>
<li><span data-ttu-id="e8521-797">Conversione o migrazione di profili utente.</span><span class="sxs-lookup"><span data-stu-id="e8521-797">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="e8521-798">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="e8521-798">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="e8521-799">Dovresti già disporre di quanto segue:</span><span class="sxs-lookup"><span data-stu-id="e8521-799">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="e8521-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows licenze desktop virtuale</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="e8521-801">Rete di Azure:</span><span class="sxs-lookup"><span data-stu-id="e8521-801">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="e8521-802">Creazione e subnetting della rete virtuale (VNET).</span><span class="sxs-lookup"><span data-stu-id="e8521-802">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="e8521-803">Firewall e gruppi di sicurezza di rete.</span><span class="sxs-lookup"><span data-stu-id="e8521-803">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="e8521-804">VPN ed ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="e8521-804">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="e8521-805">Routing ad Azure da locale.</span><span class="sxs-lookup"><span data-stu-id="e8521-805">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="e8521-806">Regole firewall per consentire la connettività Windows Desktop virtuale.</span><span class="sxs-lookup"><span data-stu-id="e8521-806">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="e8521-807">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-807">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="e8521-808">Configurazione generale di Azure AD:</span><span class="sxs-lookup"><span data-stu-id="e8521-808">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="e8521-809">Strategia di <i>identità (è possibile utilizzare solo una delle tre opzioni seguenti):</i>
</span><span class="sxs-lookup"><span data-stu-id="e8521-809">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="e8521-810">Active Directory con Azure AD Connessione in Azure.</span><span class="sxs-lookup"><span data-stu-id="e8521-810">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="e8521-811">Active Directory con Azure AD Connessione locale tramite VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="e8521-811">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="e8521-812">Servizi di dominio Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e8521-812">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="e8521-813">App Assure</span><span class="sxs-lookup"><span data-stu-id="e8521-813">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e8521-814"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-814"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e8521-815"><strong>Informazioni aggiuntive su FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-815"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e8521-816"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-816"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="e8521-817"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-817"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="e8521-818">App Assure è un servizio progettato per risolvere i problemi di compatibilità Windows 10 e Microsoft 365 Apps app.</span><span class="sxs-lookup"><span data-stu-id="e8521-818">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="e8521-819">Quando richiedi il servizio App Assure, microsoft lavora con te per risolvere i problemi validi dell'app senza costi aggiuntivi con un abbonamento idoneo.</span><span class="sxs-lookup"><span data-stu-id="e8521-819">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="e8521-820">Vengono inoltre fornite indicazioni ai clienti che devono affrontare problemi di compatibilità durante la distribuzione di Windows Virtual Desktop e Microsoft Edge e si fanno ogni sforzo ragionevole per risolvere i problemi di compatibilità.</span><span class="sxs-lookup"><span data-stu-id="e8521-820">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="e8521-821">Microsoft fornisce assistenza per la correzione delle app distribuite nei prodotti Microsoft seguenti:</span><span class="sxs-lookup"><span data-stu-id="e8521-821">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="e8521-822"><strong>Windows 10</strong> (inclusi i dispositivi ARM64)</span><span class="sxs-lookup"><span data-stu-id="e8521-822"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="e8521-823"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="e8521-823"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="e8521-824"><strong>Microsoft Edge -</strong> Per istruzioni sulla distribuzione, vedere <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Panoramica dei canali Microsoft Edge distribuzione</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-824"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="e8521-825"><strong>Windows desktop virtuale</strong> - Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> e Windows 10 Enterprise domande frequenti su più <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">sessioni.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-825"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="e8521-826">

<strong>L'ambito seguente non è disponibile </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-826">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="e8521-p137">Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro di distribuzione desktop</a>. Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito <a href="https://go.microsoft.com/fwlink/?linkid=2053818">modulo</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-p137">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="e8521-830">Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e8521-830">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="e8521-831">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-831">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="e8521-832">Servizi di sola creazione di pacchetti di app.</span><span class="sxs-lookup"><span data-stu-id="e8521-832">App packaging-only services.</span></span> <span data-ttu-id="e8521-833">Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.</span><span class="sxs-lookup"><span data-stu-id="e8521-833">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="e8521-834">

<strong>Le responsabilità dei clienti includono</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-834">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="e8521-835">Creazione di un inventario delle app.</span><span class="sxs-lookup"><span data-stu-id="e8521-835">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="e8521-836">Convalida di tali app in Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="e8521-836">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="e8521-837">
<strong>Nota:</strong>  Microsoft non può apportare modifiche al codice sorgente.</span><span class="sxs-lookup"><span data-stu-id="e8521-837">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="e8521-838">Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente.</span><span class="sxs-lookup"><span data-stu-id="e8521-838">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="e8521-839">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="e8521-839">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="e8521-840"><strong>Windows 10 e Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="e8521-840"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="e8521-841">Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="e8521-841">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="e8521-842">
<strong>Windows 10 in ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="e8521-842">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="e8521-843">Le app che hanno funzionato Windows 7, Office 2010 o versioni successive funzionano anche su Windows 10 e Microsoft 365 Apps nei dispositivi ARM64.</span><span class="sxs-lookup"><span data-stu-id="e8521-843">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="e8521-844">
  <strong>Nota:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="e8521-844">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="e8521-845">L'emulazione x64 (64 bit) è disponibile in anteprima per i clienti che partecipano al Windows <a href="https://insider.windows.com/">Insider Program.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-845">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="e8521-846">Per i clienti non Windows Insider Windows 10 versione 2004 (o successiva), ARM64 Photoshop è supportato con OpenCL e <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL Compatibility Pack.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-846">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="e8521-847">I clienti del Windows Insider Possono scaricare una versione Insider del Pacchetto di compatibilità OpenCL e OpenGL per l'uso con altre app.</span><span class="sxs-lookup"><span data-stu-id="e8521-847">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="e8521-848">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="e8521-848">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="e8521-849">Se le app o i siti Web funzionano su Internet Explorer 11, versioni supportate di Google Chrome o qualsiasi versione di Microsoft Edge, funzionano anche con Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="e8521-849">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-850">Poiché il Web è in continua evoluzione, leggere l'elenco pubblicato delle modifiche note che influiscono sulla compatibilità dei siti <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">per Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="e8521-850">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="e8521-851">
  <strong>Windows Desktop virtuale</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-851">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e8521-852">Applicazioni virtualizzate che vengono eseguite su Windows Server Remote Desktop Session Host (RDSH) vengono eseguite anche nella multisessione di Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="e8521-852">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-853">Le app in esecuzione in qualsiasi ambiente VDI (Virtual Desktop Infrastructure) di Windows 7 o Windows 10 vengono eseguite anche in Windows 7 Enterprise e Windows 10 Enterprise come parte di Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="e8521-853">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-854">Le app che vengono eseguite su dispostivi client di Windows 7 o Windows 10, vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="e8521-854">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="e8521-855">
  <strong>Nota: Windows 10 Enterprise</strong> limitazioni e esclusioni di compatibilità multi-sessione includono:</span><span class="sxs-lookup"><span data-stu-id="e8521-855">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="e8521-856">Reindirizzamento limitato dell'hardware.</span><span class="sxs-lookup"><span data-stu-id="e8521-856">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-857">Le app con uso intensivo di A/V possono essere eseguite a una capacità ridotta.</span><span class="sxs-lookup"><span data-stu-id="e8521-857">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e8521-858">Le app a 16 bit non sono supportate per la versione Desktop virtuale Windows a 64 bit.</span><span class="sxs-lookup"><span data-stu-id="e8521-858">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="e8521-859">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="e8521-859">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e8521-860"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-860"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e8521-861"><strong>Informazioni aggiuntive su FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-861"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e8521-862"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="e8521-862"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="e8521-863"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="e8521-863"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="e8521-864">Forniamo indicazioni per la distribuzione remota e l'adozione e assistenza per la compatibilità per:</span><span class="sxs-lookup"><span data-stu-id="e8521-864">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="e8521-865">Distribuzione di Microsoft Edge Windows 10 con Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="e8521-865">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="e8521-866">Configurazione di Microsoft Edge (usando i criteri di gruppo o la configurazione dell'app Intune e i criteri delle app).</span><span class="sxs-lookup"><span data-stu-id="e8521-866">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="e8521-867">Inventario dell'elenco dei siti che potrebbero richiedere l'utilizzo in modalità Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="e8521-867">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="e8521-868">Abilitazione della modalità Internet Explorer con l'Enterprise sito esistente.</span><span class="sxs-lookup"><span data-stu-id="e8521-868">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="e8521-869">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Coinvolgente FastTrack.</a></span><span class="sxs-lookup"><span data-stu-id="e8521-869">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="e8521-870">Inoltre, se si dispone di un'app Web o di un sito che funziona con Internet Explorer o Google Chrome e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema senza costi aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="e8521-870">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="e8521-871">Per richiedere il supporto per la compatibilità per App Assure, accedi al portale <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack</a> per avviare un'interazione.</span><span class="sxs-lookup"><span data-stu-id="e8521-871">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="e8521-872">Indicazioni per la pianificazione per l'adozione e la configurazione di Edge per i segnalibri di Microsoft Search.</span><span class="sxs-lookup"><span data-stu-id="e8521-872">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="e8521-873">

<strong>L'ambito seguente non è disponibile </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e8521-873">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="e8521-874">Gestione dei progetti per la distribuzione di Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="e8521-874">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="e8521-875">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="e8521-875">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
