---
title: Prodotti e funzionalità
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: In questo argomento sono inclusi i dettagli sugli scenari di carico di lavoro supportati da FastTrack e le aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, è possibile creare un piano di correzione che consentirà all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding di esito positivo.
ms.openlocfilehash: 5e65d160822ed50840ecc65f484433bf0d485913
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750103"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="05569-104">Prodotti e funzionalità</span><span class="sxs-lookup"><span data-stu-id="05569-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="05569-105">Servizi e scenari supportati da FastTrack</span><span class="sxs-lookup"><span data-stu-id="05569-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="05569-106">In questo argomento sono inclusi i dettagli sugli scenari di carico di lavoro supportati da FastTrack e le aspettative dell'ambiente di origine necessarie prima di iniziare.</span><span class="sxs-lookup"><span data-stu-id="05569-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="05569-107">In base alla configurazione corrente, è possibile creare un piano di correzione che consentirà all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding di esito positivo.</span><span class="sxs-lookup"><span data-stu-id="05569-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="05569-108">FastTrack fornisce indicazioni utili per la prima volta con le funzionalità di base (comuni per tutti i servizi online Microsoft) e quindi con l'onboarding di ogni servizio idoneo:</span><span class="sxs-lookup"><span data-stu-id="05569-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="05569-109">Generale</span><span class="sxs-lookup"><span data-stu-id="05569-109">General</span></span>](#general)
  - [<span data-ttu-id="05569-110">Sicurezza e conformità</span><span class="sxs-lookup"><span data-stu-id="05569-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="05569-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="05569-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="05569-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="05569-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="05569-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="05569-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="05569-114">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="05569-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="05569-115">App Assure</span><span class="sxs-lookup"><span data-stu-id="05569-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="05569-116">Il nuovo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="05569-116">The new Microsoft Edge</span></span>](#the-new-microsoft-edge)

> [!NOTE]
> <span data-ttu-id="05569-117">Per informazioni sulle previsioni dell’ambiente di origine di Office 365 U.S. Government, vedere [Previsioni dell’ambiente di origine di Office 365 U.S. Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="05569-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="05569-118">Generale</span><span class="sxs-lookup"><span data-stu-id="05569-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="05569-119"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="05569-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="05569-120"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="05569-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="05569-121"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="05569-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="05569-122"><strong>Onboarding di base</strong></span><span class="sxs-lookup"><span data-stu-id="05569-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="05569-123">Vengono fornite istruzioni Remote sull'onboarding di base, che include il provisioning dei servizi, il tenant e l'integrazione delle identità.</span><span class="sxs-lookup"><span data-stu-id="05569-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="05569-124">Sono inoltre disponibili passaggi per fornire una base per i servizi di onboarding quali Exchange Online, SharePoint Online e Microsoft teams, tra cui una <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussione sulla sicurezza, la connettività di rete e la conformità</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="05569-125">L'onboarding per uno o più servizi può iniziare al termine dell'onboarding di base.</span><span class="sxs-lookup"><span data-stu-id="05569-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="05569-126"></li>
</ul>  

<strong> Integrazione dell'identità </strong></span><span class="sxs-lookup"><span data-stu-id="05569-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="05569-127">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="05569-128">Preparazione delle identità di Active Directory locale per la sincronizzazione di Azure Active Directory (Azure AD), inclusa l'installazione e la configurazione di Azure AD Connect (Single-o multi-Forest) e delle licenze (incluse le licenze basate su gruppo).</span><span class="sxs-lookup"><span data-stu-id="05569-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="05569-129">Creazione di identità cloud inclusa l'importazione in blocco e la gestione delle licenze, incluso l'utilizzo delle licenze basate su gruppo.</span><span class="sxs-lookup"><span data-stu-id="05569-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="05569-130">Scelta e attivazione del metodo di autenticazione corretto per il percorso Cloud, la sincronizzazione hash delle password, l'autenticazione pass-through o Active Directory Federation Services (AD FS).</span><span class="sxs-lookup"><span data-stu-id="05569-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="05569-131">Abilitazione di ADFS per i clienti con una singola foresta di Active Directory e le identità sincronizzate con lo strumento Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="05569-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="05569-132">Per questo è necessario Windows Server 2012 R2 Active Directory Federation Services 2,0 o versione successiva.</span><span class="sxs-lookup"><span data-stu-id="05569-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="05569-133">Migrazione dell'autenticazione da AD FS ad Azure ad utilizzando la sincronizzazione hash delle password o l'autenticazione pass-through.</span><span class="sxs-lookup"><span data-stu-id="05569-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="05569-134">Migrazione delle app preintegrate (come le app di Azure AD Gallery software-as-a-Service (SaaS)) da AD FS ad Azure ad per Single Sign-on (SSO).</span><span class="sxs-lookup"><span data-stu-id="05569-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="05569-135">Abilitazione delle integrazioni delle app SaaS con SSO dalla raccolta di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="05569-136">Abilitazione del provisioning automatico degli utenti per le app SaaS preintegrate elencate nell' <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">elenco app Integration tutorial</a> (solo per le app SaaS di Azure ad Gallery e per il provisioning in uscita solo).</span><span class="sxs-lookup"><span data-stu-id="05569-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="05569-137"><strong>Abilitazione della rete </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="05569-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="05569-138">Nell'ambito del vantaggio FastTrack, si consiglia di eseguire le procedure consigliate per la connessione a servizi cloud per garantire i massimi livelli di prestazioni di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="05569-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="05569-139"><strong>Foreste di Active Directory</strong> Il livello di foresta funzionale è impostato su Windows Server 2003 e versioni successive, con la seguente configurazione della foresta:</span><span class="sxs-lookup"><span data-stu-id="05569-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="05569-140">Una foresta unica di Active Directory.</span><span class="sxs-lookup"><span data-stu-id="05569-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="05569-141">Una singola foresta account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="05569-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="05569-142">Più foreste account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="05569-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="05569-143">Più foreste account di Active Directory con una delle foreste in posizione centrale nella foresta account di Active Directory contenente Exchange e/o Lync 2010, Lync 2013 o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="05569-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="05569-144">Più foreste account di Active Directory, ognuna con la propria organizzazione di Exchange.</span><span class="sxs-lookup"><span data-stu-id="05569-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="05569-145">Attività necessarie per la configurazione tenant e l'integrazione con Azure Active Directory, se necessario.</span><span class="sxs-lookup"><span data-stu-id="05569-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="05569-146">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="05569-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="05569-147">Per gli scenari a più foreste di Active Directory, se Lync 2010, Lync 2013 o Skype for business è distribuito, deve essere distribuito nella stessa foresta di Active Directory di Exchange.</span><span class="sxs-lookup"><span data-stu-id="05569-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="05569-148">Quando si implementano più foreste di Active Directory con più organizzazioni di Exchange in una configurazione multi-ibrida di Exchange, gli spazi dei nomi UPN (Shared User Principal Name) tra le foreste di origine non sono supportati.</span><span class="sxs-lookup"><span data-stu-id="05569-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="05569-149">Gli spazi dei nomi SMTP primari tra organizzazioni di Exchange devono essere separati.</span><span class="sxs-lookup"><span data-stu-id="05569-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="05569-150">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=845444">Distribuzioni ibride con più insiemi di strutture di Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="05569-151">Per tutte le configurazioni di più insiemi di strutture, la distribuzione di Active Directory Federation Services (AD FS) non rientra nell'ambito.</span><span class="sxs-lookup"><span data-stu-id="05569-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="05569-152">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="05569-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="05569-153"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="05569-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="05569-154">Vengono fornite indicazioni per la distribuzione remota per:</span><span class="sxs-lookup"><span data-stu-id="05569-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-155">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="05569-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="05569-156">Assegnazione dei contratti di licenza con l'utente finale e di licenze basate sul dispositivo utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="05569-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="05569-157">Installare Microsoft 365 Apps dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="05569-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="05569-158">Installazione delle app di Office Mobile (ad esempio Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) sui dispositivi iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="05569-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="05569-159">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="05569-160">Selezione e configurazione di un'installazione locale o cloud.</span><span class="sxs-lookup"><span data-stu-id="05569-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="05569-161">Creazione del codice XML di configurazione dello Strumento di distribuzione di Office con lo Strumento di personalizzazione di Office o del codice XML nativo per configurare il pacchetto di distribuzione.</span><span class="sxs-lookup"><span data-stu-id="05569-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="05569-162">Distribuzione con Microsoft Endpoint Configuration Manager, che include una guida per la creazione del pacchetto di Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="05569-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="05569-163">Inoltre, se si dispone di una macro o di un componente aggiuntivo che ha avuto esito positivo con le versioni precedenti di Office e si verificano problemi di compatibilità, vengono fornite indicazioni per correggere il problema di compatibilità senza costi aggiuntivi tramite il programma app assure.</span><span class="sxs-lookup"><span data-stu-id="05569-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="05569-164">Per ulteriori informazioni, vedere la sezione <strong>assure app</strong> di <a href="#windows-10">Windows 10</a> .</span><span class="sxs-lookup"><span data-stu-id="05569-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="05569-165">Il software client online deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="05569-166"><strong>Integrità della rete</strong></span><span class="sxs-lookup"><span data-stu-id="05569-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="05569-167">Vengono fornite istruzioni Remote per ottenere e interpretare i dati chiave di connettività di rete dall'ambiente che illustrano la modalità di allineamento dei siti <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">dell'organizzazione ai principi di connettività di rete di</a>Microsoft.</span><span class="sxs-lookup"><span data-stu-id="05569-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="05569-168">Questo evidenzia il Punteggio di rete che incide direttamente sulla velocità di migrazione, l'esperienza utente, le prestazioni del servizio e l'affidabilità.</span><span class="sxs-lookup"><span data-stu-id="05569-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="05569-169">È inoltre possibile eseguire le operazioni di correzione evidenziate da questi dati per migliorare il Punteggio di rete.</span><span class="sxs-lookup"><span data-stu-id="05569-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="05569-170">Accesso all'interfaccia di amministrazione di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="05569-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="05569-171">Sono necessarie le versioni aggiornate delle app Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="05569-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="05569-172">Servizi di posizione abilitati <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">in base alle raccomandazioni relative alle prestazioni di rete nell'interfaccia di amministrazione di Microsoft 365 (Preview)</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="05569-173">Sicurezza e conformità</span><span class="sxs-lookup"><span data-stu-id="05569-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="05569-174"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="05569-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="05569-175"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="05569-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="05569-176"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="05569-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="05569-177"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="05569-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="05569-178">Vengono fornite istruzioni Remote per la protezione delle identità cloud per gli scenari seguenti.</span><span class="sxs-lookup"><span data-stu-id="05569-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="05569-179">

<strong>Infrastruttura di Fondazione sicura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="05569-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="05569-180">La configurazione e l'abilitazione dell'autenticazione avanzata per le identità, tra cui la protezione con l'autenticazione a più fattori di Azure (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure Mae e la reimpostazione della password self-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="05569-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="05569-181">Per i clienti non Azure AD Premium, vengono fornite indicazioni per proteggere le identità utilizzando le impostazioni predefinite per la sicurezza.</span><span class="sxs-lookup"><span data-stu-id="05569-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="05569-182">Per i clienti di Azure AD Premium, vengono fornite indicazioni per proteggere le identità con accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="05569-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="05569-183">Rilevamento e blocco dell'utilizzo di password deboli con la protezione delle password di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="05569-184">Protezione dell'accesso remoto alle app Web locali con proxy di applicazione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="05569-185">Abilitazione del rilevamento e del monitoraggio basati sui rischi con la protezione delle identità di Azure.</span><span class="sxs-lookup"><span data-stu-id="05569-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="05569-186">Abilitazione di una schermata di accesso personalizzata, tra cui logo, testo e immagini con personalizzazione personalizzata.</span><span class="sxs-lookup"><span data-stu-id="05569-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="05569-187">Condivisione sicura delle app e dei servizi con gli utenti guest che utilizzano Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="05569-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="05569-188">Gestione dell'accesso per gli amministratori di Office 365 mediante ruoli amministrativi basati sul controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.</span><span class="sxs-lookup"><span data-stu-id="05569-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="05569-189">Configuring Hybrid Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="05569-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="05569-190">Configurazione di Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="05569-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="05569-191">
  
<strong>Monitoraggio e creazione di report</strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="05569-192">Abilitazione del monitoraggio remoto per ADFS, Azure AD Connect e controller di dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="05569-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="05569-193">
  
<strong>Governance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="05569-194">Gestione dell'identità di Azure AD e del ciclo di vita di accesso in scala con la gestione dei diritti di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="05569-195">Gestire le appartenenze ai gruppi di Azure AD, l'accesso alle app Enterprise e le assegnazioni di ruolo con le recensioni di Azure AD Access.</span><span class="sxs-lookup"><span data-stu-id="05569-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-196">Revisione delle condizioni di utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-197">Gestione e controllo dell'accesso agli account amministratore privilegiati con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="05569-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="05569-198">
  
<strong>Automazione ed efficienza </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="05569-199">Abilitazione di Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="05569-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="05569-200">Consentendo agli utenti di creare e gestire i propri gruppi di sicurezza cloud o di Office 365 con la gestione di gruppi self-service di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="05569-201">Gestione dell'accesso delegato alle app Enterprise con la gestione dei gruppi delegati AD Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="05569-202">Abilitazione di gruppi dinamici di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="05569-203">Organizzazione delle app nel portale My Apps using Collections.</span><span class="sxs-lookup"><span data-stu-id="05569-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="05569-204">Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione di problemi identificati che impediscono l'integrazione con Azure AD e le funzionalità di Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="05569-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="05569-205"><strong>Protezione delle informazioni di Azure </strong></span><span class="sxs-lookup"><span data-stu-id="05569-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="05569-206">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-206">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-207">Attivazione e configurazione del tenant.</span><span class="sxs-lookup"><span data-stu-id="05569-207">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="05569-208">Creare e configurare etichette e criteri.</span><span class="sxs-lookup"><span data-stu-id="05569-208">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-209">Applicare la protezione delle informazioni ai documenti.</span><span class="sxs-lookup"><span data-stu-id="05569-209">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="05569-210">Classificare ed etichettare automaticamente le informazioni nelle app di Office, come Word, PowerPoint, Excel e Outlook, che eseguono Windows e con il client di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="05569-210">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="05569-211">Individuazione ed etichettatura dei file a riposo tramite lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="05569-211">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="05569-212">Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="05569-212">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="05569-213">Vengono inoltre fornite indicazioni per l'applicazione della protezione tramite Microsoft Azure Rights Management Services (Azure RMS), la crittografia dei messaggi di Office 365 (OME) e la prevenzione della perdita di dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="05569-213">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="05569-214">Le responsabilità dei prerequisiti dei clienti includono:</span><span class="sxs-lookup"><span data-stu-id="05569-214">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="05569-215">Un elenco di percorsi di condivisione file da analizzare.</span><span class="sxs-lookup"><span data-stu-id="05569-215">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="05569-216">Una tassonomia di classificazione approvata.</span><span class="sxs-lookup"><span data-stu-id="05569-216">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="05569-217">Informazioni su eventuali restrizioni o requisiti normativi relativi alla gestione delle chiavi.</span><span class="sxs-lookup"><span data-stu-id="05569-217">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="05569-218">Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-218">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="05569-219">Etichette configurate per la classificazione e la protezione.</span><span class="sxs-lookup"><span data-stu-id="05569-219">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="05569-220">Tutti i prerequisiti per lo scanner di Azure Information Protection sono sul posto.</span><span class="sxs-lookup"><span data-stu-id="05569-220">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="05569-221">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">prerequisiti per l'installazione e la distribuzione di Azure Information Protection Unified Labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-221">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="05569-222">Verificare che i dispositivi utente eseguano un sistema operativo supportato e che siano installati i prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="05569-222">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="05569-223">Per ulteriori informazioni, vedere i seguenti elementi.</span><span class="sxs-lookup"><span data-stu-id="05569-223">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="05569-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guida per gli amministratori: installare il client di etichettatura unificata di Azure Information Protection per gli utenti</a>   </span><span class="sxs-lookup"><span data-stu-id="05569-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="05569-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="05569-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="05569-226">Installazione e configurazione del connettore e dei server di Azure RMS incluso il connettore RMS (AD RMS) di Active Directory per il supporto ibrido.</span><span class="sxs-lookup"><span data-stu-id="05569-226">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="05569-227">Installazione e configurazione di Bring your own key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificata) oppure conserva la propria chiave (HYOK) (solo client classico) è necessario disporre di una di queste opzioni per la distribuzione.</span><span class="sxs-lookup"><span data-stu-id="05569-227">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="05569-228"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="05569-228"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="05569-229">Microsoft 365 Defender è una famiglia di prodotti di difesa aziendale unificata che coordina in modo nativo il rilevamento, la prevenzione, l'analisi e la risposta tra endpoint, identità, posta elettronica e app per garantire la protezione integrata da attacchi sofisticati.</span><span class="sxs-lookup"><span data-stu-id="05569-229">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="05569-230">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-230">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="05569-231">Fornire una panoramica del Microsoft 365 Security Center.</span><span class="sxs-lookup"><span data-stu-id="05569-231">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="05569-232">Revisione degli incidenti incrociati tra i prodotti, tra cui concentrarsi su ciò che è critico garantendo l'ambito di attacco completo, le risorse interessate e le azioni di correzione automatica raggruppate.</span><span class="sxs-lookup"><span data-stu-id="05569-232">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="05569-233">Dimostrazione del modo in cui Microsoft 365 Defender può orchestrare l'analisi delle risorse, degli utenti, dei dispositivi e delle cassette postali che potrebbero essere state compromesse tramite la correzione automatica.</span><span class="sxs-lookup"><span data-stu-id="05569-233">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="05569-234">Spiegare e fornire esempi di come i clienti possano cercare in modo proattivo i tentativi di intrusione e le attività di violazione che interessano la posta elettronica, i dati, i dispositivi e gli account su più set di dati.</span><span class="sxs-lookup"><span data-stu-id="05569-234">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="05569-235">Mostrare ai clienti come è possibile esaminare e migliorare la propria posizione di sicurezza in modo olistico utilizzando Microsoft Secure score.</span><span class="sxs-lookup"><span data-stu-id="05569-235">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="05569-236"><strong>L'ambito seguente è esterno</strong></span><span class="sxs-lookup"><span data-stu-id="05569-236"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="05569-237">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-237">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="05569-238">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="05569-238">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="05569-239">Guida alla distribuzione o istruzione su:</span><span class="sxs-lookup"><span data-stu-id="05569-239">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="05569-240">Informazioni su come correggere o interpretare i diversi tipi di avviso e le attività monitorate.</span><span class="sxs-lookup"><span data-stu-id="05569-240">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="05569-241">Come esaminare un utente, un computer, un percorso di spostamento laterale o un'entità.</span><span class="sxs-lookup"><span data-stu-id="05569-241">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="05569-242">Caccia alle minacce personalizzate.</span><span class="sxs-lookup"><span data-stu-id="05569-242">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="05569-243">Informazioni sulla sicurezza e la gestione degli eventi (SIEM) o l'integrazione dell'API.</span><span class="sxs-lookup"><span data-stu-id="05569-243">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="05569-244"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="05569-244"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="05569-245">Microsoft cloud app Security è un broker di sicurezza cloud Access (CASB) che offre una visibilità completa, il controllo dei dati di viaggio e un'analisi avanzata per identificare e combattere le minacce cibernetiche in tutti i servizi cloud di Microsoft e di terze parti.</span><span class="sxs-lookup"><span data-stu-id="05569-245">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="05569-246">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-246">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-247">Configurazione del portale, tra cui:</span><span class="sxs-lookup"><span data-stu-id="05569-247">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="05569-248">Importazione di gruppi di utenti.</span><span class="sxs-lookup"><span data-stu-id="05569-248">Importing user groups.</span></span></li>
<li> <span data-ttu-id="05569-249">Gestione dell'accesso e delle impostazioni di amministratore.</span><span class="sxs-lookup"><span data-stu-id="05569-249">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="05569-250">Ambito della distribuzione per selezionare alcuni gruppi di utenti da monitorare o escludere dal monitoraggio.</span><span class="sxs-lookup"><span data-stu-id="05569-250">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="05569-251">Impostazione di intervalli e tag IP.</span><span class="sxs-lookup"><span data-stu-id="05569-251">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="05569-252">Personalizzare l'esperienza dell'utente finale con il logo e la messaggistica personalizzata.</span><span class="sxs-lookup"><span data-stu-id="05569-252">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="05569-253">Impostazione dell'individuazione del cloud per fornire un'ombreggiatura mediante:</span><span class="sxs-lookup"><span data-stu-id="05569-253">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="05569-254">Microsoft Defender per gli endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-254">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="05569-255">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="05569-255">Zscaler.</span></span></li>
<li> <span data-ttu-id="05569-256">iboss.</span><span class="sxs-lookup"><span data-stu-id="05569-256">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="05569-257">Connessione delle app in <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">primo piano</a> con i connettori app.</span><span class="sxs-lookup"><span data-stu-id="05569-257">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="05569-258">Configurare il controllo delle app di accesso condizionale nei portali di accesso condizionale e cloud app Security per applicare i controlli di sessione in tempo reale.</span><span class="sxs-lookup"><span data-stu-id="05569-258">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="05569-259">Distribuzione dei dashboard cloud app Security e cloud Discovery.</span><span class="sxs-lookup"><span data-stu-id="05569-259">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="05569-260">Personalizzazione dei punteggi dei rischi delle app in base alle priorità dell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="05569-260">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="05569-261">Creazione di tag e categorie di applicazioni.</span><span class="sxs-lookup"><span data-stu-id="05569-261">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="05569-262">Sanzionare e non autorizzare le app.</span><span class="sxs-lookup"><span data-stu-id="05569-262">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="05569-263">Utilizzo dei registri attività e file.</span><span class="sxs-lookup"><span data-stu-id="05569-263">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="05569-264">Gestione delle app OAuth.</span><span class="sxs-lookup"><span data-stu-id="05569-264">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="05569-265">Informazioni sulla correlazione degli incidenti nel portale Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="05569-265">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="05569-266">Fornire assistenza per la configurazione con i <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">primi 20 casi di utilizzo per CASBs</a> (inclusa la creazione o l'aggiornamento di un massimo di sei (6) criteri) ad eccezione di:</span><span class="sxs-lookup"><span data-stu-id="05569-266">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="05569-267">Controllo della configurazione degli ambienti Internet come servizio (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="05569-267">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="05569-268">Monitoraggio delle attività degli utenti per la protezione dalle minacce negli ambienti di IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="05569-268">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="05569-269"><strong>L'ambito seguente è esterno</strong></span><span class="sxs-lookup"><span data-stu-id="05569-269"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="05569-270">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-270">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="05569-271">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="05569-271">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="05569-272">Impostazione dell'infrastruttura, dell'installazione o della distribuzione di caricamenti automatici dei registri per i rapporti continui tramite la finestra mobile o un raccoglitore di log.</span><span class="sxs-lookup"><span data-stu-id="05569-272">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="05569-273">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> .</span><span class="sxs-lookup"><span data-stu-id="05569-273">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="05569-274">Creazione di un report snapshot di individuazione cloud.</span><span class="sxs-lookup"><span data-stu-id="05569-274">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="05569-275">Blocco dell'utilizzo delle app tramite script di blocco.</span><span class="sxs-lookup"><span data-stu-id="05569-275">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="05569-276">Connessione delle app personalizzate.</span><span class="sxs-lookup"><span data-stu-id="05569-276">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="05569-277">Integrazione con provider di identità di terze parti e provider di prevenzione della perdita di dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="05569-277">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="05569-278">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="05569-278">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="05569-279">Indagine automatizzata e correzione, tra cui Microsoft Power automatizzate Playbooks.</span><span class="sxs-lookup"><span data-stu-id="05569-279">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="05569-280">Informazioni di sicurezza e gestione eventi (SIEM) o API Integration (inclusa la sentinella di Azure).</span><span class="sxs-lookup"><span data-stu-id="05569-280">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="05569-281">Implementazione dell'individuazione di app cloud come prova del concetto.</span><span class="sxs-lookup"><span data-stu-id="05569-281">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="05569-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="05569-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="05569-283">Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.</span><span class="sxs-lookup"><span data-stu-id="05569-283">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="05569-284">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-285">Distribuzione delle tecnologie per la protezione degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-285">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="05569-286">Configurazione di Endpoint Protection e dei profili di restrizione del dispositivo.</span><span class="sxs-lookup"><span data-stu-id="05569-286">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="05569-287">Valutare la versione del sistema operativo e la gestione dei dispositivi (tra cui Intune, Microsoft endpoint Configuration Manager, oggetti Criteri di gruppo (GPO) e configurazioni di terze parti), nonché lo stato di Windows Defender AV Services o di altri software di sicurezza di endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-287">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="05569-288">Valutazione dello stato dei servizi AV di Windows o di altri software di sicurezza di endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-288">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="05569-289">Valutazione di proxy e firewall che limitano il traffico di rete.</span><span class="sxs-lookup"><span data-stu-id="05569-289">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="05569-290">Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo di agente ATP utilizzando un endpoint di bordo.</span><span class="sxs-lookup"><span data-stu-id="05569-290">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="05569-291">Guida alla distribuzione, assistenza alla configurazione e istruzione su:</span><span class="sxs-lookup"><span data-stu-id="05569-291">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-292">Gestione delle minacce e delle vulnerabilità.</span><span class="sxs-lookup"><span data-stu-id="05569-292">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-293">Riduzione della superficie di attacco.</span><span class="sxs-lookup"><span data-stu-id="05569-293">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-294">Protezione di nuova generazione.</span><span class="sxs-lookup"><span data-stu-id="05569-294">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-295">Rilevamento e risposta degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-295">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-296">Indagine e correzione automatizzate.</span><span class="sxs-lookup"><span data-stu-id="05569-296">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-297">Punteggio di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="05569-297">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-298">Revisione delle simulazioni e delle esercitazioni (come gli scenari di esercitazione, il malware falso e le indagini automatizzate).</span><span class="sxs-lookup"><span data-stu-id="05569-298">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="05569-299">Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="05569-299">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="05569-300">Integrazione di Office 365 ATP con Microsoft Defender ATP.</span><span class="sxs-lookup"><span data-stu-id="05569-300">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="05569-301">Procedure dettagliate nel portale di Microsoft Defender Security Center.</span><span class="sxs-lookup"><span data-stu-id="05569-301">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="05569-302">I sistemi operativi seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-302">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-303">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-303">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-304">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="05569-304">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-305">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="05569-305">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-306">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="05569-306">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-307">Windows Server Semi-Annual Channel (SAC) versione 1803.</span><span class="sxs-lookup"><span data-stu-id="05569-307">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-308">versioni macOS 10,13, 10,14 e 10,15.</span><span class="sxs-lookup"><span data-stu-id="05569-308">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="05569-309">
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft endpoint Configuration Manager (versione 2002 o superiore).</span><span class="sxs-lookup"><span data-stu-id="05569-309">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="05569-310"></li>
</ul>

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-310"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="05569-311">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-311">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="05569-312">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="05569-312">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="05569-313">Gestione continua e risposta alle minacce.</span><span class="sxs-lookup"><span data-stu-id="05569-313">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="05569-314">Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-314">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-315">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="05569-315">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-316">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="05569-316">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-317">Linux.</span><span class="sxs-lookup"><span data-stu-id="05569-317">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-318">Dispositivi mobili (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="05569-318">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-319">Onboarding e configurazione del server:</span><span class="sxs-lookup"><span data-stu-id="05569-319">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-320">Configurazione di un server proxy per le comunicazioni offline.</span><span class="sxs-lookup"><span data-stu-id="05569-320">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-321">Configurazione di pacchetti di distribuzione di Configuration Manager nelle versioni e nelle varianti di gestione della configurazione.</span><span class="sxs-lookup"><span data-stu-id="05569-321">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-322">Onboarding servers to Azure Security Center.</span><span class="sxs-lookup"><span data-stu-id="05569-322">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-323">Server non gestiti da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="05569-323">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-324">onboarding e configurazione di macOS:</span><span class="sxs-lookup"><span data-stu-id="05569-324">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-325">Distribuzione manuale basata su Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-325">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-326">Distribuzione basata su GRAFP.</span><span class="sxs-lookup"><span data-stu-id="05569-326">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="05569-327">Altre distribuzioni basate su prodotto di gestione dei dispositivi mobili (MDM).</span><span class="sxs-lookup"><span data-stu-id="05569-327">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-328">Distribuzione manuale.</span><span class="sxs-lookup"><span data-stu-id="05569-328">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-329">Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-329">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-330">Isolamento basato su hardware.</span><span class="sxs-lookup"><span data-stu-id="05569-330">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-331">Controllo app.</span><span class="sxs-lookup"><span data-stu-id="05569-331">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-332">Protezione dagli exploit.</span><span class="sxs-lookup"><span data-stu-id="05569-332">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-333">Firewall di rete.</span><span class="sxs-lookup"><span data-stu-id="05569-333">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-334">Iscrizione o configurazione di Microsoft Threat Experts.</span><span class="sxs-lookup"><span data-stu-id="05569-334">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="05569-335">Configurazione o formazione per la revisione delle API o delle informazioni di sicurezza e delle connessioni di gestione eventi (SIEM).</span><span class="sxs-lookup"><span data-stu-id="05569-335">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="05569-336">Iscrizione o configurazione di Microsoft Threat Protection (MTP).</span><span class="sxs-lookup"><span data-stu-id="05569-336">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="05569-337">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="05569-337">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="05569-338">Formazione o indicazioni su come usare o creare query Kusto.</span><span class="sxs-lookup"><span data-stu-id="05569-338">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="05569-339">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="05569-339">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="05569-340"><strong>Microsoft Defender per l'identità </strong></span><span class="sxs-lookup"><span data-stu-id="05569-340"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="05569-341">Microsoft Defender for Identity è una soluzione di sicurezza basata sul cloud che utilizza i segnali di Active Directory locali per identificare, rilevare ed esaminare le minacce avanzate, le identità compromesse e le azioni di insider dannose indirizzate alla propria organizzazione.</span><span class="sxs-lookup"><span data-stu-id="05569-341">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="05569-342">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-342">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="05569-343">Creazione dell'istanza di Defender per Identity.</span><span class="sxs-lookup"><span data-stu-id="05569-343">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="05569-344">Connecting Defender for Identity to Active Directory.</span><span class="sxs-lookup"><span data-stu-id="05569-344">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="05569-345">Valutazione della conformità dell'ambiente per la distribuzione del protezione per il sensore di identità nei controller di dominio, tra cui:</span><span class="sxs-lookup"><span data-stu-id="05569-345">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="05569-346">Esecuzione dello strumento di ridimensionamento per la pianificazione della capacità delle risorse.</span><span class="sxs-lookup"><span data-stu-id="05569-346">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="05569-347">Esecuzione dello strumento di controllo per valutare la compatibilità dei controller di dominio con il sensore.</span><span class="sxs-lookup"><span data-stu-id="05569-347">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="05569-348">Distribuzione del sensore per acquisire e analizzare il traffico di rete e gli eventi di Windows direttamente dai controller di dominio, tra cui:</span><span class="sxs-lookup"><span data-stu-id="05569-348">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="05569-349">Download del pacchetto di sensori.</span><span class="sxs-lookup"><span data-stu-id="05569-349">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="05569-350">Configurazione del sensore.</span><span class="sxs-lookup"><span data-stu-id="05569-350">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="05569-351">Installazione del sensore sul controller di dominio in modo invisibile all'utente.</span><span class="sxs-lookup"><span data-stu-id="05569-351">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="05569-352">Distribuzione del sensore nell'ambiente a più foreste.</span><span class="sxs-lookup"><span data-stu-id="05569-352">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="05569-353">Integrazione del difensore per l'identità con Microsoft cloud app Security (cloud app Security Licensing non è obbligatorio).</span><span class="sxs-lookup"><span data-stu-id="05569-353">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="05569-354">Fornire indicazioni sulla distribuzione, assistenza per la configurazione e istruzione su:</span><span class="sxs-lookup"><span data-stu-id="05569-354">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="05569-355">Ottimizzazione dell'ambiente per la riduzione del rumore.</span><span class="sxs-lookup"><span data-stu-id="05569-355">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="05569-356">Informazioni sul rapporto di valutazione delle posizioni sulla sicurezza delle identità.</span><span class="sxs-lookup"><span data-stu-id="05569-356">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="05569-357">Informazioni sul punteggio di priorità dell'analisi degli utenti e sul rapporto di classificazione dell'analisi degli utenti.</span><span class="sxs-lookup"><span data-stu-id="05569-357">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="05569-358">Informazioni sul rapporto utenti inattivi.</span><span class="sxs-lookup"><span data-stu-id="05569-358">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="05569-359">Fornire opzioni di correzione su un account compromesso.</span><span class="sxs-lookup"><span data-stu-id="05569-359">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="05569-360">Facilitare la migrazione da Advanced Threat Analytics (ATA) al difensore dell'identità.</span><span class="sxs-lookup"><span data-stu-id="05569-360">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="05569-361"><strong>L'ambito seguente è esterno</strong></span><span class="sxs-lookup"><span data-stu-id="05569-361"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="05569-362">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-362">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="05569-363">Gestione continua, risposta alle minacce e correzione.</span><span class="sxs-lookup"><span data-stu-id="05569-363">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="05569-364">Distribuzione del protezione per il sensore di identità, tra cui:</span><span class="sxs-lookup"><span data-stu-id="05569-364">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="05569-365">Pianificazione della capacità manuale.</span><span class="sxs-lookup"><span data-stu-id="05569-365">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="05569-366">Distribuzione del sensore in una capacità autonoma.</span><span class="sxs-lookup"><span data-stu-id="05569-366">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="05569-367">Distribuzione del sensore tramite un adattatore per la scheda di interfaccia di rete (NIC).</span><span class="sxs-lookup"><span data-stu-id="05569-367">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="05569-368">Distribuzione del sensore tramite uno strumento di terze parti.</span><span class="sxs-lookup"><span data-stu-id="05569-368">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="05569-369">Connessione al servizio protezione per il Cloud Identity tramite una connessione proxy Web.</span><span class="sxs-lookup"><span data-stu-id="05569-369">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="05569-370">Creazione e gestione di honeytokens.</span><span class="sxs-lookup"><span data-stu-id="05569-370">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="05569-371">Guida alla distribuzione o istruzione su:</span><span class="sxs-lookup"><span data-stu-id="05569-371">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="05569-372">Correzione o interpretazione di vari tipi di avviso e attività monitorate.</span><span class="sxs-lookup"><span data-stu-id="05569-372">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="05569-373">Analisi di un utente, un computer, un percorso di spostamento laterale o un'entità.</span><span class="sxs-lookup"><span data-stu-id="05569-373">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="05569-374">Minaccia o caccia avanzata.</span><span class="sxs-lookup"><span data-stu-id="05569-374">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="05569-375">Risposta agli incidenti.</span><span class="sxs-lookup"><span data-stu-id="05569-375">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="05569-376">Fornire un'esercitazione sul laboratorio di avviso per la sicurezza per il difensore dell'identità.</span><span class="sxs-lookup"><span data-stu-id="05569-376">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="05569-377">Notifica quando il difensore dell'identità rileva attività sospette inviando avvisi di sicurezza al server syslog tramite un sensore nominato.</span><span class="sxs-lookup"><span data-stu-id="05569-377">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="05569-378">Configurazione del difensore per l'identità per eseguire query utilizzando il protocollo SAMR (Security Account Manager Remote) per identificare gli amministratori locali su computer specifici.</span><span class="sxs-lookup"><span data-stu-id="05569-378">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="05569-379">Configurazione di soluzioni VPN per aggiungere informazioni dalla connessione VPN alla pagina del profilo di un utente.</span><span class="sxs-lookup"><span data-stu-id="05569-379">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="05569-380">Informazioni di sicurezza e gestione eventi (SIEM) o API Integration (inclusa la sentinella di Azure).</span><span class="sxs-lookup"><span data-stu-id="05569-380">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="05569-381">Distribuzione di Defender per i sensori di identità come prova del concetto.</span><span class="sxs-lookup"><span data-stu-id="05569-381">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="05569-382">Distribuzione di Active Directory.</span><span class="sxs-lookup"><span data-stu-id="05569-382">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="05569-383">I controller di dominio che si intende installare Defender per i sensori di identità dispongono di connettività Internet al difensore del servizio Cloud Identity.</span><span class="sxs-lookup"><span data-stu-id="05569-383">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="05569-384">Il firewall e il proxy devono essere aperti per comunicare con il servizio Defender per Identity cloud (\*. atp.azure.com la porta 443 deve essere aperta).</span><span class="sxs-lookup"><span data-stu-id="05569-384">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="05569-385">Controller di dominio in esecuzione su una delle opzioni seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-385">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="05569-386">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="05569-386">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="05569-387">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="05569-387">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="05569-388">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="05569-388">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="05569-389">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="05569-389">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="05569-390">Windows Server 2019 con KB4487044 (OS Build 17763,316).</span><span class="sxs-lookup"><span data-stu-id="05569-390">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="05569-391"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="05569-391"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="05569-392">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-392">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-393">Etichette e criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="05569-393">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-394">Gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="05569-394">Records management.</span></span>  </li>
<li>  <span data-ttu-id="05569-395">Criteri di eliminazione.</span><span class="sxs-lookup"><span data-stu-id="05569-395">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-396">Conformità delle comunicazioni.</span><span class="sxs-lookup"><span data-stu-id="05569-396">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="05569-397">Gestione dei rischi Insider.</span><span class="sxs-lookup"><span data-stu-id="05569-397">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="05569-398">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="05569-398">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="05569-399">

  <strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-399">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="05569-400">Sviluppo di un piano file di gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="05569-400">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="05569-401">Connettori di dati.</span><span class="sxs-lookup"><span data-stu-id="05569-401">Data connectors.</span></span></li>
<li> <span data-ttu-id="05569-402">Barriere informative.</span><span class="sxs-lookup"><span data-stu-id="05569-402">Information barriers.</span></span></li>
<li> <span data-ttu-id="05569-403">Gestione degli accessi con privilegi.</span><span class="sxs-lookup"><span data-stu-id="05569-403">Privileged access management.</span></span></li>
<li> <span data-ttu-id="05569-404">Sviluppo dell'architettura delle informazioni in SharePoint.</span><span class="sxs-lookup"><span data-stu-id="05569-404">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="05569-405">Scripting e codifica personalizzato.</span><span class="sxs-lookup"><span data-stu-id="05569-405">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="05569-406">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="05569-406">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="05569-407"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="05569-407"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="05569-408">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-408">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-409">Classificazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="05569-409">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="05569-410">Tipi di informazioni sensibili.</span><span class="sxs-lookup"><span data-stu-id="05569-410">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="05569-411">Creare etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="05569-411">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="05569-412">Applicazione di etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="05569-412">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="05569-413">Etichettatura unificata.</span><span class="sxs-lookup"><span data-stu-id="05569-413">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="05569-414">Classificatori sottoponibili a formazione.</span><span class="sxs-lookup"><span data-stu-id="05569-414">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="05569-415">Conoscere i dati tramite Esplora contenuto ed Esplora attività.</span><span class="sxs-lookup"><span data-stu-id="05569-415">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="05569-416">Pubblicare etichette con criteri (manuale e automatico).</span><span class="sxs-lookup"><span data-stu-id="05569-416">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="05569-417">Creare criteri di prevenzione della perdita dei dati (DLP) per chat e canali di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="05569-417">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="05569-418">Creazione di criteri DLP di endpoint per i dispositivi Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-418">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="05569-419">

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-419">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="05569-420">Chiave del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-420">Customer key.</span></span></li>
<li><span data-ttu-id="05569-421">Sviluppo di espressioni regolari (RegEx) personalizzate per i tipi di informazioni riservate.</span><span class="sxs-lookup"><span data-stu-id="05569-421">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="05569-422">Creazione o modifica di dizionari di parole chiave.</span><span class="sxs-lookup"><span data-stu-id="05569-422">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="05569-423">Scripting e codifica personalizzato.</span><span class="sxs-lookup"><span data-stu-id="05569-423">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="05569-424">
<strong>Nota:</strong> Per ulteriori informazioni, vedere <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-424">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="05569-425">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="05569-425">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="05569-426"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="05569-426"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="05569-427">Vengono fornite informazioni remote su come preparare l'utilizzo di Intune come provider di gestione dei dispositivi mobili basato sul cloud (MDM) e mobile app Management (MAM) per le app e i dispositivi.</span><span class="sxs-lookup"><span data-stu-id="05569-427">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="05569-428">I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili.</span><span class="sxs-lookup"><span data-stu-id="05569-428">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="05569-429">I passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="05569-429">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="05569-430">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="05569-430">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="05569-431">Configurazione delle identità per l'utilizzo da parte di Intune mediante l'uso di Active Directory o identità cloud locali (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="05569-431">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="05569-432">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="05569-432">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="05569-433">Configurazione dell'autorità MDM, in base alle esigenze di gestione, tra cui:</span><span class="sxs-lookup"><span data-stu-id="05569-433">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="05569-434">Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.</span><span class="sxs-lookup"><span data-stu-id="05569-434">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="05569-435">Fornire le indicazioni di MDM per:</span><span class="sxs-lookup"><span data-stu-id="05569-435">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-436">Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.</span><span class="sxs-lookup"><span data-stu-id="05569-436">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-437">Configurare criteri e servizi di gestione MDM come:</span><span class="sxs-lookup"><span data-stu-id="05569-437">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="05569-438">Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o Deep Links.</span><span class="sxs-lookup"><span data-stu-id="05569-438">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="05569-439">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="05569-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-440">Distribuzione di messaggi di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="05569-440">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="05569-441">Connessione al data warehouse di Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-441">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="05569-442">Integrare Intune con:</span><span class="sxs-lookup"><span data-stu-id="05569-442">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="05569-443">Visualizzatore team per assistenza remota (è necessario un abbonamento a un visualizzatore di Team).</span><span class="sxs-lookup"><span data-stu-id="05569-443">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="05569-444">Soluzioni partner per la difesa di minacce mobili (MTD) (è necessaria una sottoscrizione di MTD).</span><span class="sxs-lookup"><span data-stu-id="05569-444">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="05569-445">Una soluzione Telecom Expense Management (è richiesta una sottoscrizione di una soluzione per la gestione delle spese Telecom).</span><span class="sxs-lookup"><span data-stu-id="05569-445">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="05569-446">Microsoft Defender ATP (sono necessarie licenze Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="05569-446">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="05569-447">Registrare i dispositivi di ogni piattaforma supportata in Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-447">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="05569-448">Fornire indicazioni sulla protezione delle app:</span><span class="sxs-lookup"><span data-stu-id="05569-448">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="05569-449">Configurare criteri di protezione delle app per ogni piattaforma supportata.</span><span class="sxs-lookup"><span data-stu-id="05569-449">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="05569-450">Configurazione dei criteri di accesso condizionale per le app gestite.</span><span class="sxs-lookup"><span data-stu-id="05569-450">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="05569-451">Indirizzare i gruppi di utenti corretti con i criteri MAM precedentemente citati.</span><span class="sxs-lookup"><span data-stu-id="05569-451">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-452">Utilizzo di report sull'utilizzo delle app gestite.</span><span class="sxs-lookup"><span data-stu-id="05569-452">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="05569-453">Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="05569-453">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="05569-454">
  <strong>Nota</strong>: la gestione dei PC legacy non è più supportata dal 15 ottobre 2020 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="05569-454">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="05569-455"></li>
</ul>
  
<strong>Collegamento tramite cloud</strong></span><span class="sxs-lookup"><span data-stu-id="05569-455"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="05569-456">Si consiglia di preparare gli ambienti di gestione della configurazione esistenti tramite cloud con Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-456">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="05569-457">I passaggi esatti dipendono dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="05569-457">The exact steps depend on your source environment.</span></span> <span data-ttu-id="05569-458">Questi passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="05569-458">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="05569-459">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="05569-459">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="05569-460">Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.</span><span class="sxs-lookup"><span data-stu-id="05569-460">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="05569-461">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="05569-461">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="05569-462">Fornire linee guida per la configurazione di un join ibrido di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-462">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="05569-463">Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.</span><span class="sxs-lookup"><span data-stu-id="05569-463">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="05569-464">Offrire indicazioni su come configurare il gateway di gestione cloud.</span><span class="sxs-lookup"><span data-stu-id="05569-464">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="05569-465">Configurare i carichi di lavoro supportati che si desidera passare a Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-465">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="05569-466">Installare il client Configuration Manager nei dispositivi registrati di Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-466">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="05569-467"><strong>Distribuire Outlook Mobile per iOS e Android in modo sicuro</strong> È possibile fornire assistenza per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire che gli utenti dispongano di tutte le app necessarie installate.</span><span class="sxs-lookup"><span data-stu-id="05569-467"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="05569-468">La procedura per distribuire in modo sicuro Outlook Mobile per iOS e Android con Intune dipende dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="05569-468">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="05569-469">Può includere:</span><span class="sxs-lookup"><span data-stu-id="05569-469">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="05569-470">Scaricare le app di Outlook per iOS e Android, Microsoft Authenticator e il portale aziendale di Intune tramite l'App Store di Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="05569-470">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="05569-471">Fornire indicazioni sulla configurazione:</span><span class="sxs-lookup"><span data-stu-id="05569-471">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="05569-472">Distribuzione di Outlook per iOS e Android, Microsoft Authenticator e Intune per le app del portale aziendale con Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-472">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="05569-473">Criteri di protezione delle app.</span><span class="sxs-lookup"><span data-stu-id="05569-473">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-474">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="05569-474">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-475">Criteri di configurazione dell'app.</span><span class="sxs-lookup"><span data-stu-id="05569-475">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="05569-476"><strong>Nota</strong>: FastTrack non supporta la protezione di Outlook per iOS e Android con i criteri cassetta postale dei dispositivi mobili di Exchange.</span><span class="sxs-lookup"><span data-stu-id="05569-476"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="05569-477">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="05569-477">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="05569-478">Gli amministratori IT devono disporre dell'autorità di certificazione, della rete wireless e delle infrastrutture VPN esistenti che già operano nei rispettivi ambienti di produzione durante la pianificazione della distribuzione della rete wireless e dei profili VPN con Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-478">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="05569-479"><strong>Nota</strong>: il vantaggio del servizio di FastTrack non include assistenza per la configurazione o la configurazione di autorità di certificazione, reti wireless, infrastrutture VPN o certificati push di Apple MDM per Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-479"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="05569-480"><strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud.</span><span class="sxs-lookup"><span data-stu-id="05569-480"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="05569-481">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="05569-481">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="05569-482"><strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="05569-482"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="05569-483"><strong>Nota</strong>: viene fornita assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-483"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="05569-484">Non viene fornita assistenza per l'acquisto, la gestione delle licenze o l'attivazione.</span><span class="sxs-lookup"><span data-stu-id="05569-484">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="05569-485">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="05569-485">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="05569-486"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="05569-486"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="05569-487">Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="05569-487">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="05569-488"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="05569-488"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="05569-489">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-489">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-490">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="05569-490">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="05569-491">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="05569-491">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="05569-492">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="05569-492">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="05569-493">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="05569-493">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="05569-494">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="05569-494">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="05569-495">Office 365</span><span class="sxs-lookup"><span data-stu-id="05569-495">Office 365</span></span>

<<table>
<thead>
<tr class="header">
<th><span data-ttu-id="05569-496"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="05569-496"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="05569-497"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="05569-497"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="05569-498"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="05569-498"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="05569-499"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="05569-499"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="05569-500">Per Exchange Online, è possibile eseguire la procedura per preparare l'organizzazione all'utilizzo della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="05569-500">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="05569-501">I passaggi esatti dipendono dall'ambiente di origine e dai piani di migrazione della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="05569-501">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="05569-502">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-502">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-503">Configurare le funzionalità di Exchange Online Protection (EOP) per tutti i domini abilitati alla posta elettronica convalidati in Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-503">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="05569-504">Puntamento dei record MX (mail Exchange) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-504">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="05569-505">Configurazione della funzionalità ATP di Office 365 se fa parte del servizio di sottoscrizione.</span><span class="sxs-lookup"><span data-stu-id="05569-505">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="05569-506">Per ulteriori informazioni, vedere la sezione <strong>Office 365 Advanced Threat Protection</strong> di questa tabella.</span><span class="sxs-lookup"><span data-stu-id="05569-506">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="05569-p128">Configurare la funzionalità di prevenzione della perdita dei dati (DLP) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-p128">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="05569-p129">Configurare Office 365 Message Encryption (OME) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-p129">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="05569-511">
  <strong>Nota:</strong> Il servizio di replica delle cassette postali (MRS) tenta di migrare i messaggi di posta elettronica IRM (Information Rights Managed) dalla cassetta postale locale alla corrispondente cassetta postale di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="05569-511">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="05569-512">La possibilità di leggere i contenuti protetti dopo la migrazione dipende dal fatto che il cliente esegua il mapping e copi i modelli di Active Directory Rights Managed Services (AD RMS) in Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="05569-512">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="05569-513">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="05569-513">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="05569-514">Configurazione di DNS, tra cui il servizio di individuazione automatica, il servizio di gestione dei messaggi (SPF), la posta elettronica identificata di DomainKeys (DKIM), l'autenticazione del messaggio basata sul dominio, la creazione di report e la conformità (DMARC) e i record MX (se necessario).</span><span class="sxs-lookup"><span data-stu-id="05569-514">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="05569-515">Configurare il flusso di posta elettronica tra l'ambiente di messaggistica di origine e Exchange Online (in base alle esigenze).</span><span class="sxs-lookup"><span data-stu-id="05569-515">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="05569-516">Eseguire la migrazione della posta dall'ambiente di messaggistica di origine a Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-516">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="05569-517">Configurazione di client delle cassette postali (Outlook per Windows, Outlook sul web e Outlook per iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="05569-517">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="05569-518">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="05569-518">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="05569-519">Per informazioni sull'utilizzo del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-519">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="05569-520">L'ambiente di origine deve disporre di uno dei livelli minimi seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-520">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="05569-521">Una o più organizzazioni di Exchange con Exchange Server 2003 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="05569-521">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="05569-522">Un singolo ambiente di posta elettronica abilitato per il protocollo IMAP.</span><span class="sxs-lookup"><span data-stu-id="05569-522">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="05569-523">Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).</span><span class="sxs-lookup"><span data-stu-id="05569-523">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="05569-524">Per informazioni su multi-Geo capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=872776">multi-Geo capabilities in Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-524">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="05569-525">Il software client online come Project per Office 365, Outlook per Windows, Outlook per iOS e Android, il client di sincronizzazione di OneDrive for business, il desktop Power BI e Skype for business devono essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-525">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="05569-526"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="05569-526"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="05569-527">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-527">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-528">Etichette e criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="05569-528">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-529">Gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="05569-529">Records management.</span></span>  </li>
<li>  <span data-ttu-id="05569-530">Criteri di eliminazione.</span><span class="sxs-lookup"><span data-stu-id="05569-530">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-531">Conformità delle comunicazioni.</span><span class="sxs-lookup"><span data-stu-id="05569-531">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="05569-532">Gestione dei rischi Insider.</span><span class="sxs-lookup"><span data-stu-id="05569-532">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="05569-533">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="05569-533">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="05569-534">

  <strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-534">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="05569-535">Sviluppo di un piano file di gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="05569-535">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="05569-536">Connettori di dati.</span><span class="sxs-lookup"><span data-stu-id="05569-536">Data connectors.</span></span></li>
<li> <span data-ttu-id="05569-537">Barriere informative.</span><span class="sxs-lookup"><span data-stu-id="05569-537">Information barriers.</span></span></li>
<li> <span data-ttu-id="05569-538">Gestione degli accessi con privilegi.</span><span class="sxs-lookup"><span data-stu-id="05569-538">Privileged access management.</span></span></li>
<li> <span data-ttu-id="05569-539">Sviluppo dell'architettura delle informazioni in SharePoint.</span><span class="sxs-lookup"><span data-stu-id="05569-539">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="05569-540">Scripting e codifica personalizzato.</span><span class="sxs-lookup"><span data-stu-id="05569-540">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="05569-541">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="05569-541">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="05569-542"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="05569-542"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="05569-543">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-543">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-544">Classificazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="05569-544">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="05569-545">Tipi di informazioni sensibili.</span><span class="sxs-lookup"><span data-stu-id="05569-545">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="05569-546">Creare etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="05569-546">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="05569-547">Applicazione di etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="05569-547">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="05569-548">Etichettatura unificata.</span><span class="sxs-lookup"><span data-stu-id="05569-548">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="05569-549">Classificatori sottoponibili a formazione.</span><span class="sxs-lookup"><span data-stu-id="05569-549">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="05569-550">Conoscere i dati tramite Esplora contenuto ed Esplora attività.</span><span class="sxs-lookup"><span data-stu-id="05569-550">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="05569-551">Pubblicare etichette con criteri (manuale e automatico).</span><span class="sxs-lookup"><span data-stu-id="05569-551">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="05569-552">Creare criteri di prevenzione della perdita dei dati (DLP) per chat e canali di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="05569-552">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="05569-553">Creazione di criteri DLP di endpoint per i dispositivi Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-553">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="05569-554">

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-554">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="05569-555">Chiave del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-555">Customer key.</span></span></li>
<li><span data-ttu-id="05569-556">Sviluppo di espressioni regolari (RegEx) personalizzate per i tipi di informazioni riservate.</span><span class="sxs-lookup"><span data-stu-id="05569-556">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="05569-557">Creazione o modifica di dizionari di parole chiave.</span><span class="sxs-lookup"><span data-stu-id="05569-557">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="05569-558">Scripting e codifica personalizzato.</span><span class="sxs-lookup"><span data-stu-id="05569-558">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="05569-559">
<strong>Nota:</strong> Per ulteriori informazioni, vedere <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-559">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="05569-560">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="05569-560">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="05569-561"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="05569-561"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="05569-562">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-562">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-563">Conferma dei requisiti minimi nei gruppi di Exchange Online, SharePoint Online, Office 365 e Azure AD per il supporto dei team.</span><span class="sxs-lookup"><span data-stu-id="05569-563">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="05569-564">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="05569-564">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="05569-565">Configurazione di DNS.</span><span class="sxs-lookup"><span data-stu-id="05569-565">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="05569-566">Conferma dell'abilitazione di Teams nel tenant Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-566">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="05569-567">Abilitazione o disabilitazione delle licenze utente.</span><span class="sxs-lookup"><span data-stu-id="05569-567">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="05569-568">Valutazione della rete per i team:</span><span class="sxs-lookup"><span data-stu-id="05569-568">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="05569-569">Controlli di porta ed endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-569">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="05569-570">Controlli sulla qualità della connessione.</span><span class="sxs-lookup"><span data-stu-id="05569-570">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="05569-571">Stime sulla larghezza di banda.</span><span class="sxs-lookup"><span data-stu-id="05569-571">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="05569-572">Configurazione dei criteri delle app per i team (teams Web App, teams desktop app e teams for iOS and Android app).</span><span class="sxs-lookup"><span data-stu-id="05569-572">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="05569-573">Se applicabile, vengono fornite anche indicazioni per:</span><span class="sxs-lookup"><span data-stu-id="05569-573">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-574">Dispositivi della sala Microsoft teams:</span><span class="sxs-lookup"><span data-stu-id="05569-574">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="05569-575">Creazione di account online necessari per i dispositivi di telefonia e di sala riunioni supportati elencati nel <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogo dei dispositivi Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-575">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="05569-576">Assistenza remota con la configurazione sul fianco del servizio dei dispositivi Microsoft teams Rooms certificati.</span><span class="sxs-lookup"><span data-stu-id="05569-576">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="05569-577">Abilitazione dell'audioconferenza:</span><span class="sxs-lookup"><span data-stu-id="05569-577">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="05569-578">Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.</span><span class="sxs-lookup"><span data-stu-id="05569-578">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="05569-579">Assegnazione di bridge per conferenze agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="05569-579">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="05569-580">Sistema telefonico:</span><span class="sxs-lookup"><span data-stu-id="05569-580">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="05569-581">Configurazione aziendale delle impostazioni predefinite vocali cloud.</span><span class="sxs-lookup"><span data-stu-id="05569-581">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="05569-582">Guida ai piani di chiamata (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercati disponibili</a>):</span><span class="sxs-lookup"><span data-stu-id="05569-582">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="05569-583">Assegnazione di numeri agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="05569-583">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="05569-584">Guida alla portabilità del numero locale tramite UI fino a 999.</span><span class="sxs-lookup"><span data-stu-id="05569-584">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="05569-585">Supporto RS per la richiesta di servizio di portabilità del numero locale superiore a 999.</span><span class="sxs-lookup"><span data-stu-id="05569-585">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="05569-586">Guida per il routing diretto:</span><span class="sxs-lookup"><span data-stu-id="05569-586">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="05569-587">Linee guida per l'installazione dell'organizzazione per la progettazione di routing diretto di scenari ospitati da partner o scenari distribuiti dal cliente per un massimo di 10 siti.</span><span class="sxs-lookup"><span data-stu-id="05569-587">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="05569-588">Verifica della configurazione del session border controller (SBC).</span><span class="sxs-lookup"><span data-stu-id="05569-588">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="05569-589">Assistenza remota con la configurazione del dial plan.</span><span class="sxs-lookup"><span data-stu-id="05569-589">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="05569-590">Configurazione della route vocale.</span><span class="sxs-lookup"><span data-stu-id="05569-590">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="05569-591">Bypass multimediale e ottimizzazione dei supporti locali.</span><span class="sxs-lookup"><span data-stu-id="05569-591">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="05569-592">Abilitazione degli eventi live in Teams.</span><span class="sxs-lookup"><span data-stu-id="05569-592">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="05569-593">Configurazione dell'organizzazione e integrazione in Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="05569-593">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="05569-594">Linee guida per la transizione da Skype for business a teams.</span><span class="sxs-lookup"><span data-stu-id="05569-594">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="05569-595">Identità abilitate in Azure Active Directory per Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-595">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="05569-596">Utenti abilitati per SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="05569-596">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="05569-597">Le cassette postali di Exchange sono presenti (online e in locale in una configurazione ibrida di Exchange).</span><span class="sxs-lookup"><span data-stu-id="05569-597">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="05569-598">Abilitato per i gruppi di Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-598">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="05569-599">
  <strong>Nota:</strong> Se gli utenti non sono assegnati e abilitati con le licenze di SharePoint Online, non avranno l'archiviazione di OneDrive for business in Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-599">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="05569-600">La condivisione dei file continua a funzionare nei canali, ma gli utenti non possono condividere file in chat senza OneDrive for Business Storage in Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-600">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="05569-601">I team non supportano SharePoint locale.</span><span class="sxs-lookup"><span data-stu-id="05569-601">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="05569-602">
  <strong>Nota:</strong> Lo stato ideale è che tutti gli utenti dispongano delle cassette postali in Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="05569-602">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="05569-603">Gli utenti con cassette postali ospitate in locale devono avere le rispettive identità sincronizzate con la directory di Office 365 tramite Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="05569-603">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="05569-604">Per questi clienti ibridi di Exchange, se la cassetta postale dell'utente è in locale, l'utente non è in grado di aggiungere o configurare i connettori.</span><span class="sxs-lookup"><span data-stu-id="05569-604">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="05569-605">I programmi di installazione per i client desktop di Microsoft Teams per Windows e Mac possono essere scaricati da <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-605">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="05569-606"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="05569-606"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="05569-607">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-607">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-608">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="05569-608">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="05569-609">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="05569-609">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="05569-610">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="05569-610">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="05569-611">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="05569-611">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="05569-612">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="05569-612">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="05569-613"><strong>Outlook per iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="05569-613"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="05569-614">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-614">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-615">Download di Outlook per iOS e Android tramite l'Apple App Store e Google Play.</span><span class="sxs-lookup"><span data-stu-id="05569-615">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="05569-616">Configurazione degli account e accesso alla cassetta postale di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="05569-616">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="05569-617">Protezione di Outlook Mobile (vedere <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">protezione di Outlook per iOS e Android in Exchange Online</a> per ulteriori informazioni).</span><span class="sxs-lookup"><span data-stu-id="05569-617">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="05569-618">Identità abilitate in Azure Active Directory per Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-618">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="05569-619">Exchange Online configurato e licenze assegnate.</span><span class="sxs-lookup"><span data-stu-id="05569-619">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="05569-620"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="05569-620"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="05569-621">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-621">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-622">Assegnare licenze di Power BI.</span><span class="sxs-lookup"><span data-stu-id="05569-622">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="05569-623">Distribuire l'app Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="05569-623">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="05569-624">Il software client online come Power BI desktop deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-624">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="05569-625"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="05569-625"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="05569-626">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-626">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-627">Verificare la funzionalità di base di SharePoint sulla quale fa affidamento Project Online.</span><span class="sxs-lookup"><span data-stu-id="05569-627">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="05569-628">Aggiungere il servizio Project Online al tenant (inclusa l'aggiunta di sottoscrizioni per gli utenti).</span><span class="sxs-lookup"><span data-stu-id="05569-628">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="05569-629">Configurare il pool di risorse organizzazione (ERP).</span><span class="sxs-lookup"><span data-stu-id="05569-629">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="05569-630">Creare il primo progetto.</span><span class="sxs-lookup"><span data-stu-id="05569-630">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="05569-631">Il software client online come Project per Office 365 deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-631">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="05569-632"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="05569-632"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="05569-633">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-634">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="05569-634">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="05569-635">Assegnare i contratti di licenza con l'utente finale utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="05569-635">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="05569-636">Installare Client desktop di Project Online dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="05569-636">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="05569-637">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-637">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="05569-638">Configurare un unico server di distribuzione nel sito per Client desktop di Project Online, includendo una guida per la creazione del file configuration.xml da usare con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="05569-638">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="05569-639">Connettere Client desktop di Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="05569-639">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="05569-640">Il software client online come Project per Office 365 deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-640">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="05569-641"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="05569-641"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="05569-642">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-642">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-643">Configurazione DNS.</span><span class="sxs-lookup"><span data-stu-id="05569-643">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="05569-644">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="05569-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="05569-645">Provisioning di utenti e licenze.</span><span class="sxs-lookup"><span data-stu-id="05569-645">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="05569-646">Abilitazione alla creazione di siti per l'amministratore di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="05569-646">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="05569-647">Pianificazione delle raccolte di siti.</span><span class="sxs-lookup"><span data-stu-id="05569-647">Planning site collections.</span></span></li>
<li><span data-ttu-id="05569-648">Protezione del contenuto e gestione delle autorizzazioni.</span><span class="sxs-lookup"><span data-stu-id="05569-648">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="05569-649">Configurazione delle caratteristiche di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="05569-649">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="05569-650">Configurazione delle funzionalità dell'ambiente ibrido di SharePoint, come la ricerca ibrida, i siti ibridi, la tassonomia ibrida, i tipi di contenuto, la creazione siti in modalità self-service ibrida (solo SharePoint Server 2013), l'icona di avvio delle app estesa, OneDrive for Business ibrido e i siti extranet.</span><span class="sxs-lookup"><span data-stu-id="05569-650">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="05569-651">Approccio di migrazione.</span><span class="sxs-lookup"><span data-stu-id="05569-651">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="05569-652">Vengono fornite indicazioni aggiuntive per OneDrive for business a seconda della versione di SharePoint, ad esempio:</span><span class="sxs-lookup"><span data-stu-id="05569-652">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="05569-653">Identificare le opzioni di integrazione e la revisione dell'infrastruttura di rete e della larghezza di banda in locale e online.</span><span class="sxs-lookup"><span data-stu-id="05569-653">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="05569-654">Installazione di SharePoint Online 2013 SP1 (se applicabile), pianificazione e implementazione dei requisiti di sincronizzazione e identità e identificazione del client di sincronizzazione di OneDrive for business.</span><span class="sxs-lookup"><span data-stu-id="05569-654">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="05569-655">Pianificazione e implementazione di una singola implementazione per tutti gli utenti (o per una distribuzione in fasi).</span><span class="sxs-lookup"><span data-stu-id="05569-655">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="05569-656">Assegnazione delle licenze, Reindirizzamento dei siti personali e delle raccolte documenti personale a Office 365 (applicabile a SharePoint Online 2013), impostazione di gruppi di destinatari per controllare l'accesso a OneDrive (applicabile a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="05569-656">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="05569-657">Reindirizzamento o spostamento di cartelle note in OneDrive.</span><span class="sxs-lookup"><span data-stu-id="05569-657">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="05569-658">Distribuzione della sincronizzazione client di OneDrive for business.</span><span class="sxs-lookup"><span data-stu-id="05569-658">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="05569-659">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="05569-659">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="05569-660">Per informazioni sull'utilizzo del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-660">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="05569-661"><strong>Per l'ambiente ibrido di SharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-661"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="05569-662">La configurazione ibrida di SharePoint include la configurazione della ricerca ibrida, dei siti, della tassonomia, dei tipi di contenuto, di OneDrive for business, di un'applicazione di avvio delle app estesa, di siti Extranet e della creazione di siti in modalità self-service connessi da un singolo ambiente SharePoint Online di destinazione.</span><span class="sxs-lookup"><span data-stu-id="05569-662">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="05569-663">
  <strong>Nota:</strong> La creazione di siti in modalità self-service non è in ambito con i server locali che eseguono SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="05569-663">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="05569-664">Per abilitare l'ambiente ibrido di SharePoint, è necessario disporre di uno dei seguenti ambienti locali di SharePoint Server: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="05569-664">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="05569-665">
  <strong>Nota:</strong> L'aggiornamento degli ambienti di SharePoint locali a SharePoint Server non è incluso nell'ambito.</span><span class="sxs-lookup"><span data-stu-id="05569-665">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="05569-666">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="05569-666">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="05569-667">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=853548">livelli di aggiornamento pubblico minimi per le funzionalità ibride di SharePoint</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="05569-667">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="05569-668">
  <strong>Nota:</strong> Per informazioni su multi-Geo capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=831056">multi-Geo capabilities in OneDrive e SharePoint online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="05569-668">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="05569-669"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="05569-669"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="05569-670">Vengono fornite istruzioni Remote per abilitare il servizio Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="05569-670">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="05569-671">Il software client online deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-671">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="05569-672">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="05569-672">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="05569-673"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="05569-673"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="05569-674"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="05569-674"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="05569-675"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="05569-675"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="05569-676"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="05569-676"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="05569-677">Vengono fornite istruzioni Remote per la protezione delle identità cloud per gli scenari seguenti.</span><span class="sxs-lookup"><span data-stu-id="05569-677">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="05569-678">

<strong>Infrastruttura di Fondazione sicura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="05569-678">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="05569-679">La configurazione e l'abilitazione dell'autenticazione avanzata per le identità, tra cui la protezione con l'autenticazione a più fattori di Azure (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure Mae e la reimpostazione della password self-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="05569-679">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="05569-680">Per i clienti non Azure AD Premium, vengono fornite indicazioni per proteggere le identità utilizzando le impostazioni predefinite per la sicurezza.</span><span class="sxs-lookup"><span data-stu-id="05569-680">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="05569-681">Per i clienti di Azure AD Premium, vengono fornite indicazioni per proteggere le identità con accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="05569-681">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="05569-682">Rilevamento e blocco dell'utilizzo di password deboli con la protezione delle password di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-682">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="05569-683">Protezione dell'accesso remoto alle app Web locali con proxy di applicazione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-683">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="05569-684">Abilitazione del rilevamento e del monitoraggio basati sui rischi con la protezione delle identità di Azure.</span><span class="sxs-lookup"><span data-stu-id="05569-684">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="05569-685">Abilitazione di una schermata di accesso personalizzata, tra cui logo, testo e immagini con personalizzazione personalizzata.</span><span class="sxs-lookup"><span data-stu-id="05569-685">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="05569-686">Condivisione sicura delle app e dei servizi con gli utenti guest che utilizzano Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="05569-686">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="05569-687">Gestione dell'accesso per gli amministratori di Office 365 mediante ruoli amministrativi basati sul controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.</span><span class="sxs-lookup"><span data-stu-id="05569-687">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="05569-688">Configuring Hybrid Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="05569-688">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="05569-689">Configurazione di Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="05569-689">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="05569-690">
  
<strong>Monitoraggio e creazione di report</strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-690">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="05569-691">Abilitazione del monitoraggio remoto per ADFS, Azure AD Connect e controller di dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="05569-691">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="05569-692">
  
<strong>Governance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-692">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="05569-693">Gestione dell'identità di Azure AD e del ciclo di vita di accesso in scala con la gestione dei diritti di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-693">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="05569-694">Gestire le appartenenze ai gruppi di Azure AD, l'accesso alle app Enterprise e le assegnazioni di ruolo con le recensioni di Azure AD Access.</span><span class="sxs-lookup"><span data-stu-id="05569-694">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-695">Revisione delle condizioni di utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-695">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-696">Gestione e controllo dell'accesso agli account amministratore privilegiati con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="05569-696">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="05569-697">
  
<strong>Automazione ed efficienza </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-697">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="05569-698">Abilitazione di Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="05569-698">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="05569-699">Consentendo agli utenti di creare e gestire i propri gruppi di sicurezza cloud o di Office 365 con la gestione di gruppi self-service di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-699">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="05569-700">Gestione dell'accesso delegato alle app Enterprise con la gestione dei gruppi delegati AD Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-700">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="05569-701">Abilitazione di gruppi dinamici di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-701">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="05569-702">Organizzazione delle app nel portale My Apps using Collections.</span><span class="sxs-lookup"><span data-stu-id="05569-702">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="05569-703">Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione di problemi identificati che impediscono l'integrazione con Azure AD e le funzionalità di Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="05569-703">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="05569-704"><strong>Protezione delle informazioni di Azure </strong></span><span class="sxs-lookup"><span data-stu-id="05569-704"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="05569-705">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-705">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-706">Attivazione e configurazione del tenant.</span><span class="sxs-lookup"><span data-stu-id="05569-706">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="05569-707">Creare e configurare etichette e criteri.</span><span class="sxs-lookup"><span data-stu-id="05569-707">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-708">Applicare la protezione delle informazioni ai documenti.</span><span class="sxs-lookup"><span data-stu-id="05569-708">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="05569-709">Classificare ed etichettare automaticamente le informazioni nelle app di Office, come Word, PowerPoint, Excel e Outlook, che eseguono Windows e con il client di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="05569-709">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="05569-710">Individuazione ed etichettatura dei file a riposo tramite lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="05569-710">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="05569-711">Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="05569-711">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="05569-712">Vengono inoltre fornite indicazioni per l'applicazione della protezione tramite Microsoft Azure Rights Management Services (Azure RMS), la crittografia dei messaggi di Office 365 (OME) e la prevenzione della perdita di dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="05569-712">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="05569-713">Le responsabilità dei prerequisiti dei clienti includono:</span><span class="sxs-lookup"><span data-stu-id="05569-713">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="05569-714">Un elenco di percorsi di condivisione file da analizzare.</span><span class="sxs-lookup"><span data-stu-id="05569-714">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="05569-715">Una tassonomia di classificazione approvata.</span><span class="sxs-lookup"><span data-stu-id="05569-715">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="05569-716">Informazioni su eventuali restrizioni o requisiti normativi relativi alla gestione delle chiavi.</span><span class="sxs-lookup"><span data-stu-id="05569-716">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="05569-717">Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-717">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="05569-718">Etichette configurate per la classificazione e la protezione.</span><span class="sxs-lookup"><span data-stu-id="05569-718">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="05569-719">Tutti i prerequisiti per lo scanner di Azure Information Protection sono sul posto.</span><span class="sxs-lookup"><span data-stu-id="05569-719">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="05569-720">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">prerequisiti per l'installazione e la distribuzione di Azure Information Protection Unified Labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-720">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="05569-721">Verificare che i dispositivi utente eseguano un sistema operativo supportato e che siano installati i prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="05569-721">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="05569-722">Per ulteriori informazioni, vedere i seguenti elementi.</span><span class="sxs-lookup"><span data-stu-id="05569-722">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="05569-723"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guida per gli amministratori: installare il client di etichettatura unificata di Azure Information Protection per gli utenti</a>   </span><span class="sxs-lookup"><span data-stu-id="05569-723"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="05569-724"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="05569-724"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="05569-725">Installazione e configurazione del connettore e dei server di Azure RMS incluso il connettore RMS (AD RMS) di Active Directory per il supporto ibrido.</span><span class="sxs-lookup"><span data-stu-id="05569-725">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="05569-726">Installazione e configurazione di Bring your own key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificata) oppure conserva la propria chiave (HYOK) (solo client classico) è necessario disporre di una di queste opzioni per la distribuzione.</span><span class="sxs-lookup"><span data-stu-id="05569-726">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="05569-727"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="05569-727"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="05569-728">Vengono fornite informazioni remote su come preparare l'utilizzo di Intune come provider di gestione dei dispositivi mobili basato sul cloud (MDM) e mobile app Management (MAM) per le app e i dispositivi.</span><span class="sxs-lookup"><span data-stu-id="05569-728">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="05569-729">I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili.</span><span class="sxs-lookup"><span data-stu-id="05569-729">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="05569-730">I passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="05569-730">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="05569-731">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="05569-731">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="05569-732">Configurazione delle identità per l'utilizzo da parte di Intune mediante l'uso di Active Directory o identità cloud locali (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="05569-732">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="05569-733">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="05569-733">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="05569-734">Configurazione dell'autorità MDM, in base alle esigenze di gestione, tra cui:</span><span class="sxs-lookup"><span data-stu-id="05569-734">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="05569-735">Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.</span><span class="sxs-lookup"><span data-stu-id="05569-735">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="05569-736">Fornire le indicazioni di MDM per:</span><span class="sxs-lookup"><span data-stu-id="05569-736">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-737">Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.</span><span class="sxs-lookup"><span data-stu-id="05569-737">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-738">Configurare criteri e servizi di gestione MDM come:</span><span class="sxs-lookup"><span data-stu-id="05569-738">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="05569-739">Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o Deep Links.</span><span class="sxs-lookup"><span data-stu-id="05569-739">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="05569-740">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="05569-740">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-741">Distribuzione di messaggi di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="05569-741">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="05569-742">Connessione al data warehouse di Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-742">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="05569-743">Integrare Intune con:</span><span class="sxs-lookup"><span data-stu-id="05569-743">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="05569-744">Visualizzatore team per assistenza remota (è necessario un abbonamento a un visualizzatore di Team).</span><span class="sxs-lookup"><span data-stu-id="05569-744">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="05569-745">Soluzioni partner per la difesa di minacce mobili (MTD) (è necessaria una sottoscrizione di MTD).</span><span class="sxs-lookup"><span data-stu-id="05569-745">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="05569-746">Una soluzione Telecom Expense Management (è richiesta una sottoscrizione di una soluzione per la gestione delle spese Telecom).</span><span class="sxs-lookup"><span data-stu-id="05569-746">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="05569-747">Microsoft Defender ATP (sono necessarie licenze Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="05569-747">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="05569-748">Registrare i dispositivi di ogni piattaforma supportata in Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-748">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="05569-749">Fornire indicazioni sulla protezione delle app:</span><span class="sxs-lookup"><span data-stu-id="05569-749">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="05569-750">Configurare criteri di protezione delle app per ogni piattaforma supportata.</span><span class="sxs-lookup"><span data-stu-id="05569-750">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="05569-751">Configurazione dei criteri di accesso condizionale per le app gestite.</span><span class="sxs-lookup"><span data-stu-id="05569-751">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="05569-752">Indirizzare i gruppi di utenti corretti con i criteri MAM precedentemente citati.</span><span class="sxs-lookup"><span data-stu-id="05569-752">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-753">Utilizzo di report sull'utilizzo delle app gestite.</span><span class="sxs-lookup"><span data-stu-id="05569-753">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="05569-754">Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="05569-754">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="05569-755">
  <strong>Nota</strong>: la gestione dei PC legacy non è più supportata dal 15 ottobre 2020 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="05569-755">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="05569-756"></li>
</ul>
  
<strong>Collegamento tramite cloud</strong></span><span class="sxs-lookup"><span data-stu-id="05569-756"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="05569-757">Si consiglia di preparare gli ambienti di gestione della configurazione esistenti tramite cloud con Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-757">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="05569-758">I passaggi esatti dipendono dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="05569-758">The exact steps depend on your source environment.</span></span> <span data-ttu-id="05569-759">Questi passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="05569-759">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="05569-760">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="05569-760">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="05569-761">Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.</span><span class="sxs-lookup"><span data-stu-id="05569-761">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="05569-762">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="05569-762">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="05569-763">Fornire linee guida per la configurazione di un join ibrido di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="05569-763">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="05569-764">Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.</span><span class="sxs-lookup"><span data-stu-id="05569-764">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="05569-765">Offrire indicazioni su come configurare il gateway di gestione cloud.</span><span class="sxs-lookup"><span data-stu-id="05569-765">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="05569-766">Configurare i carichi di lavoro supportati che si desidera passare a Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-766">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="05569-767">Installare il client Configuration Manager nei dispositivi registrati di Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-767">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="05569-768"><strong>Distribuire Outlook Mobile per iOS e Android in modo sicuro</strong> È possibile fornire assistenza per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire che gli utenti dispongano di tutte le app necessarie installate.</span><span class="sxs-lookup"><span data-stu-id="05569-768"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="05569-769">La procedura per distribuire in modo sicuro Outlook Mobile per iOS e Android con Intune dipende dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="05569-769">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="05569-770">Può includere:</span><span class="sxs-lookup"><span data-stu-id="05569-770">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="05569-771">Scaricare le app di Outlook per iOS e Android, Microsoft Authenticator e il portale aziendale di Intune tramite l'App Store di Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="05569-771">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="05569-772">Fornire indicazioni sulla configurazione:</span><span class="sxs-lookup"><span data-stu-id="05569-772">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="05569-773">Distribuzione di Outlook per iOS e Android, Microsoft Authenticator e Intune per le app del portale aziendale con Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-773">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="05569-774">Criteri di protezione delle app.</span><span class="sxs-lookup"><span data-stu-id="05569-774">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-775">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="05569-775">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="05569-776">Criteri di configurazione dell'app.</span><span class="sxs-lookup"><span data-stu-id="05569-776">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="05569-777"><strong>Nota</strong>: FastTrack non supporta la protezione di Outlook per iOS e Android con i criteri cassetta postale dei dispositivi mobili di Exchange.</span><span class="sxs-lookup"><span data-stu-id="05569-777"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="05569-778">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="05569-778">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="05569-779">Gli amministratori IT devono disporre dell'autorità di certificazione, della rete wireless e delle infrastrutture VPN esistenti che già operano nei rispettivi ambienti di produzione durante la pianificazione della distribuzione della rete wireless e dei profili VPN con Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-779">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="05569-780"><strong>Nota</strong>: il vantaggio del servizio di FastTrack non include assistenza per la configurazione o la configurazione di autorità di certificazione, reti wireless, infrastrutture VPN o certificati push di Apple MDM per Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-780"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="05569-781"><strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud.</span><span class="sxs-lookup"><span data-stu-id="05569-781"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="05569-782">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="05569-782">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="05569-783"><strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="05569-783"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="05569-784"><strong>Nota</strong>: viene fornita assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-784"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="05569-785">Non viene fornita assistenza per l'acquisto, la gestione delle licenze o l'attivazione.</span><span class="sxs-lookup"><span data-stu-id="05569-785">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="05569-786">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="05569-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="05569-787"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="05569-787"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="05569-788">Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="05569-788">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="05569-789">Windows 10</span><span class="sxs-lookup"><span data-stu-id="05569-789">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="05569-790"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="05569-790"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="05569-791"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="05569-791"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="05569-792"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="05569-792"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="05569-793"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="05569-793"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="05569-794">Vengono fornite indicazioni per l'aggiornamento da Windows 7 Professional e Windows 8,1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="05569-794">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="05569-795">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-795">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-796">Informazioni sull'intenzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-796">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="05569-797">Valutazione dell'ambiente di origine e dei requisiti (verificare che Microsoft endpoint Configuration Manager venga aggiornato al livello richiesto per supportare la distribuzione di Windows 10).</span><span class="sxs-lookup"><span data-stu-id="05569-797">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="05569-798">Distribuzione delle app di Windows 10 Enterprise e Microsoft 365 tramite Microsoft endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="05569-798">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="05569-799">Opzioni di raccomandazione per valutare le app di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-799">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="05569-800">Abilitazione dell'utilizzo di analisi desktop e linee guida tramite la creazione di un piano di distribuzione di analisi desktop.</span><span class="sxs-lookup"><span data-stu-id="05569-800">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="05569-801">Microsoft 365 Apps Compatibility assessment by leveraging The Office 365 prontezza dashboard in Configuration Manager o with the stand-alone Pronation Toolkit for Office Plus Assistance Deploying Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="05569-801">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="05569-802">Creazione di un elenco di controllo di correzione su cosa è necessario fare per riportare l'ambiente di origine ai requisiti minimi per una distribuzione corretta.</span><span class="sxs-lookup"><span data-stu-id="05569-802">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="05569-803">Fornire indicazioni sull'aggiornamento per i dispositivi esistenti a Windows 10 Enterprise, se soddisfano i requisiti hardware necessari per il dispositivo.</span><span class="sxs-lookup"><span data-stu-id="05569-803">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="05569-804">Fornire indicazioni sull'aggiornamento per supportare il movimento di distribuzione esistente.</span><span class="sxs-lookup"><span data-stu-id="05569-804">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="05569-805">FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-805">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="05569-806">Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="05569-806">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="05569-807">Distribuzione di app Microsoft 365 mediante Configuration Manager nell'ambito della distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-807">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="05569-808">Fornire indicazioni per aiutare l'organizzazione a rimanere sempre aggiornati con le app Windows 10 Enterprise e Microsoft 365 utilizzando l'ambiente di gestione della configurazione esistente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="05569-808">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="05569-809">
  <strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-809">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="05569-810">Aggiornamento di Configuration Manager al Current Branch.</span><span class="sxs-lookup"><span data-stu-id="05569-810">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="05569-811">Creazione di immagini personalizzate per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-811">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="05569-812">Creazione e supporto degli script di distribuzione per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-812">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="05569-813">Conversione di un sistema di Windows 10 dal BIOS a Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="05569-813">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="05569-814">Abilitare le funzionalità di sicurezza di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-814">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="05569-815">Configurazione di Windows Deployment Services (WDS) per il boot di Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="05569-815">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="05569-816">Uso di Microsoft Deployment Toolkit (MDT) per acquisire e distribuire immagini di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-816">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="05569-817">Uso dell’Utilità di migrazione dello stato utente (USMT).</span><span class="sxs-lookup"><span data-stu-id="05569-817">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="05569-818">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="05569-818">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="05569-819">Per l'aggiornamento del PC, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-819">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="05569-820">Sistema operativo di origine: Windows 7 Enterprise o Professional, Windows 8,1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="05569-820">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="05569-821">Dispositivi: fattore di forma desktop, notebook o tablet.</span><span class="sxs-lookup"><span data-stu-id="05569-821">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="05569-822">Sistema operativo di destinazione: Window 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="05569-822">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="05569-823">Per l'aggiornamento dell'infrastruttura, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-823">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="05569-824">Gestione configurazione Microsoft endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-824">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="05569-825">La versione di Configuration Manager deve essere supportata dalla versione di destinazione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-825">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="05569-826">Per altre informazioni, vedere la tabella di supporto di Configuration Manager in <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Supporto per Windows 10 in Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-826">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="05569-827"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="05569-827"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="05569-828">Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.</span><span class="sxs-lookup"><span data-stu-id="05569-828">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="05569-829">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-829">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="05569-830">Distribuzione delle tecnologie per la protezione degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-830">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="05569-831">Configurazione di Endpoint Protection e dei profili di restrizione del dispositivo.</span><span class="sxs-lookup"><span data-stu-id="05569-831">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="05569-832">Valutare la versione del sistema operativo e la gestione dei dispositivi (tra cui Intune, Microsoft endpoint Configuration Manager, oggetti Criteri di gruppo (GPO) e configurazioni di terze parti), nonché lo stato di Windows Defender AV Services o di altri software di sicurezza di endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-832">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="05569-833">Valutazione dello stato dei servizi AV di Windows o di altri software di sicurezza di endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-833">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="05569-834">Valutazione di proxy e firewall che limitano il traffico di rete.</span><span class="sxs-lookup"><span data-stu-id="05569-834">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="05569-835">Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo di agente ATP utilizzando un endpoint di bordo.</span><span class="sxs-lookup"><span data-stu-id="05569-835">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="05569-836">Guida alla distribuzione, assistenza alla configurazione e istruzione su:</span><span class="sxs-lookup"><span data-stu-id="05569-836">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-837">Gestione delle minacce e delle vulnerabilità.</span><span class="sxs-lookup"><span data-stu-id="05569-837">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-838">Riduzione della superficie di attacco.</span><span class="sxs-lookup"><span data-stu-id="05569-838">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-839">Protezione di nuova generazione.</span><span class="sxs-lookup"><span data-stu-id="05569-839">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-840">Rilevamento e risposta degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="05569-840">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-841">Indagine e correzione automatizzate.</span><span class="sxs-lookup"><span data-stu-id="05569-841">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-842">Punteggio di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="05569-842">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-843">Revisione delle simulazioni e delle esercitazioni (come gli scenari di esercitazione, il malware falso e le indagini automatizzate).</span><span class="sxs-lookup"><span data-stu-id="05569-843">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="05569-844">Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="05569-844">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="05569-845">Integrazione di Office 365 ATP con Microsoft Defender ATP.</span><span class="sxs-lookup"><span data-stu-id="05569-845">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="05569-846">Procedure dettagliate nel portale di Microsoft Defender Security Center.</span><span class="sxs-lookup"><span data-stu-id="05569-846">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="05569-847">I sistemi operativi seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-847">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-848">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-848">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-849">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="05569-849">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-850">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="05569-850">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-851">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="05569-851">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-852">Windows Server Semi-Annual Channel (SAC) versione 1803.</span><span class="sxs-lookup"><span data-stu-id="05569-852">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-853">versioni macOS 10,13, 10,14 e 10,15.</span><span class="sxs-lookup"><span data-stu-id="05569-853">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="05569-854">
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft endpoint Configuration Manager (versione 2002 o superiore).</span><span class="sxs-lookup"><span data-stu-id="05569-854">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="05569-855"></li>
</ul>

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-855"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="05569-856">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-856">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="05569-857">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="05569-857">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="05569-858">Gestione continua e risposta alle minacce.</span><span class="sxs-lookup"><span data-stu-id="05569-858">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="05569-859">Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-859">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-860">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="05569-860">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-861">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="05569-861">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-862">Linux.</span><span class="sxs-lookup"><span data-stu-id="05569-862">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-863">Dispositivi mobili (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="05569-863">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-864">Onboarding e configurazione del server:</span><span class="sxs-lookup"><span data-stu-id="05569-864">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-865">Configurazione di un server proxy per le comunicazioni offline.</span><span class="sxs-lookup"><span data-stu-id="05569-865">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-866">Configurazione di pacchetti di distribuzione di Configuration Manager nelle versioni e nelle varianti di gestione della configurazione.</span><span class="sxs-lookup"><span data-stu-id="05569-866">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-867">Onboarding servers to Azure Security Center.</span><span class="sxs-lookup"><span data-stu-id="05569-867">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-868">Server non gestiti da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="05569-868">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-869">onboarding e configurazione di macOS:</span><span class="sxs-lookup"><span data-stu-id="05569-869">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-870">Distribuzione manuale basata su Intune.</span><span class="sxs-lookup"><span data-stu-id="05569-870">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-871">Distribuzione basata su GRAFP.</span><span class="sxs-lookup"><span data-stu-id="05569-871">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="05569-872">Altre distribuzioni basate su prodotto di gestione dei dispositivi mobili (MDM).</span><span class="sxs-lookup"><span data-stu-id="05569-872">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-873">Distribuzione manuale.</span><span class="sxs-lookup"><span data-stu-id="05569-873">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-874">Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-874">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-875">Isolamento basato su hardware.</span><span class="sxs-lookup"><span data-stu-id="05569-875">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-876">Controllo app.</span><span class="sxs-lookup"><span data-stu-id="05569-876">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-877">Protezione dagli exploit.</span><span class="sxs-lookup"><span data-stu-id="05569-877">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-878">Firewall di rete.</span><span class="sxs-lookup"><span data-stu-id="05569-878">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="05569-879">Iscrizione o configurazione di Microsoft Threat Experts.</span><span class="sxs-lookup"><span data-stu-id="05569-879">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="05569-880">Configurazione o formazione per la revisione delle API o delle informazioni di sicurezza e delle connessioni di gestione eventi (SIEM).</span><span class="sxs-lookup"><span data-stu-id="05569-880">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="05569-881">Iscrizione o configurazione di Microsoft Threat Protection (MTP).</span><span class="sxs-lookup"><span data-stu-id="05569-881">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="05569-882">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="05569-882">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="05569-883">Formazione o indicazioni su come usare o creare query Kusto.</span><span class="sxs-lookup"><span data-stu-id="05569-883">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="05569-884">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="05569-884">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="05569-885">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="05569-885">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="05569-886"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="05569-886"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="05569-887"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="05569-887"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="05569-888"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="05569-888"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="05569-889"><strong>Desktop virtuale Windows</strong></span><span class="sxs-lookup"><span data-stu-id="05569-889"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="05569-890">Vengono fornite indicazioni per la distribuzione per l'onboarding su Windows Virtual Desktop (un servizio di virtualizzazione per desktop e app).</span><span class="sxs-lookup"><span data-stu-id="05569-890">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="05569-891">Windows Virtual Desktop si avvale dell'esperienza multisessione di Windows 10 ed è ottimizzato per le app Microsoft 365 per Enterprise con la sicurezza integrata e la gestione di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="05569-891">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="05569-892">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="05569-892">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="05569-893">Distribuzione dell'ambiente desktop virtuale di Windows con le app di Windows 10 Enterprise Multi-Session e Microsoft 365 per l'organizzazione con quanto segue:</span><span class="sxs-lookup"><span data-stu-id="05569-893">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="05569-894">Immagine di Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="05569-894">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="05569-895">Immagine condivisa.</span><span class="sxs-lookup"><span data-stu-id="05569-895">Shared image.</span></span></li>
<li><span data-ttu-id="05569-896">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="05569-896">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="05569-897">Configurazione di FSLogix:</span><span class="sxs-lookup"><span data-stu-id="05569-897">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="05569-898">Distribuzione dell'agente di FSLogix con il contenitore di profili.</span><span class="sxs-lookup"><span data-stu-id="05569-898">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="05569-899">Distribuzione dell'agente FSLogix con il contenitore di Office.</span><span class="sxs-lookup"><span data-stu-id="05569-899">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="05569-900">Configurazione della cartella FSLogix con le esclusioni di contenuto.</span><span class="sxs-lookup"><span data-stu-id="05569-900">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="05569-901">Distribuzione di Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="05569-901">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="05569-902">Distribuzione di Microsoft teams.</span><span class="sxs-lookup"><span data-stu-id="05569-902">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="05569-903">Connessione mediante client desktop virtuali di Windows.</span><span class="sxs-lookup"><span data-stu-id="05569-903">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="05569-904">

<strong>L'ambito seguente è esterno</strong>
</span><span class="sxs-lookup"><span data-stu-id="05569-904">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="05569-905">Gestione dei progetti della distribuzione di Windows Virtual Desktop del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-905">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="05569-906">Virtualizzazione e distribuzione di app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="05569-906">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="05569-907">Immagini personalizzate.</span><span class="sxs-lookup"><span data-stu-id="05569-907">Custom images.</span></span></li>
<li><span data-ttu-id="05569-908">Migrazioni e scenari che coinvolgono VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="05569-908">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="05569-909">Scenari di Linux.</span><span class="sxs-lookup"><span data-stu-id="05569-909">Linux scenarios.</span></span></li>
<li><span data-ttu-id="05569-910">Conversione o migrazione dei profili utente.</span><span class="sxs-lookup"><span data-stu-id="05569-910">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="05569-911">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="05569-911">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="05569-912">È consigliabile che siano già presenti le operazioni seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-912">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="05569-913"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisiti relativi alle licenze Desktop virtuali di Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-913"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="05569-914">Rete di Azure:</span><span class="sxs-lookup"><span data-stu-id="05569-914">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="05569-915">Creazione e subnetting della rete virtuale (rete virtuale).</span><span class="sxs-lookup"><span data-stu-id="05569-915">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="05569-916">Firewall e gruppi di sicurezza di rete.</span><span class="sxs-lookup"><span data-stu-id="05569-916">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="05569-917">VPN e ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="05569-917">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="05569-918">Routing in Azure da locale.</span><span class="sxs-lookup"><span data-stu-id="05569-918">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="05569-919">Regole del firewall per consentire la connettività a desktop virtuale di Windows.</span><span class="sxs-lookup"><span data-stu-id="05569-919">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="05569-920">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> client desktop remoto supportati</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-920">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="05569-921">Installazione generale di Azure AD:</span><span class="sxs-lookup"><span data-stu-id="05569-921">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="05569-922">Strategia <i>di identità (è possibile utilizzare solo una delle tre opzioni seguenti):</i>
</span><span class="sxs-lookup"><span data-stu-id="05569-922">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="05569-923">Active Directory con Azure AD Connect in Azure.</span><span class="sxs-lookup"><span data-stu-id="05569-923">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="05569-924">Active Directory con Azure AD Connect in locale tramite VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="05569-924">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="05569-925">Servizi di dominio Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="05569-925">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="05569-926">App Assure</span><span class="sxs-lookup"><span data-stu-id="05569-926">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="05569-927"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="05569-927"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="05569-928"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="05569-928"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="05569-929"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="05569-929"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="05569-930"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="05569-930"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="05569-931">App assure è un servizio studiato per risolvere i problemi relativi alla compatibilità delle app Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="05569-931">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="05569-932">Quando si richiede il servizio app assure, è possibile collaborare con l'utente per risolvere i problemi di app validi senza costi aggiuntivi per l'utente con un abbonamento idoneo.</span><span class="sxs-lookup"><span data-stu-id="05569-932">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="05569-933">Vengono inoltre fornite indicazioni per i clienti che affrontano i problemi di compatibilità durante la distribuzione di desktop virtuali di Windows e del nuovo Microsoft Edge e offrono ogni ragionevole sforzo per risolvere i problemi di compatibilità.</span><span class="sxs-lookup"><span data-stu-id="05569-933">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and the new Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="05569-934">Viene fornita assistenza per la correzione per le app distribuite nei prodotti Microsoft seguenti:</span><span class="sxs-lookup"><span data-stu-id="05569-934">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="05569-935"><strong>Windows 10 </strong> (compresi i dispositivi arm64)</span><span class="sxs-lookup"><span data-stu-id="05569-935"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="05569-936"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="05569-936"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="05569-937"><strong>La nuova Microsoft Edge-</strong> Per informazioni sulle linee guida sulla distribuzione, vedere <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge Channels</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-937"><strong>The new Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="05569-938">Desktop virtuale di <strong>Windows</strong> - Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">che cos'è Windows Virtual Desktop?</a> e <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">domande frequenti su Windows 10 Enterprise Multi-Session</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-938"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="05569-939">

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-939">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="05569-p149">Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro di distribuzione desktop</a>. Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito <a href="https://go.microsoft.com/fwlink/?linkid=2053818">modulo</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-p149">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="05569-943">Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="05569-943">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="05569-944">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-944">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="05569-945">Servizi di sola creazione di pacchetti di app.</span><span class="sxs-lookup"><span data-stu-id="05569-945">App packaging-only services.</span></span> <span data-ttu-id="05569-946">Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-946">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="05569-947">

<strong>Responsabilità del cliente:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-947">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="05569-948">Creazione di un inventario delle app.</span><span class="sxs-lookup"><span data-stu-id="05569-948">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="05569-949">Convalida di tali app in Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="05569-949">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="05569-950">
<strong>Nota:</strong>  Microsoft non è in grado di apportare modifiche al codice sorgente.</span><span class="sxs-lookup"><span data-stu-id="05569-950">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="05569-951">Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-951">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="05569-952">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="05569-952">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="05569-953"><strong>App di Windows 10 e Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="05569-953"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="05569-954">Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="05569-954">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="05569-955">
<strong>Windows 10 su ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="05569-955">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="05569-956">Le app che hanno lavorato su Windows 7, Office 2010 o versioni successive funzionano anche su app Windows 10 e Microsoft 365 nei dispositivi di ARM64.</span><span class="sxs-lookup"><span data-stu-id="05569-956">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="05569-957">
  <strong>Nota</strong> 
</span><span class="sxs-lookup"><span data-stu-id="05569-957">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="05569-958">l'emulazione x64 (64 bit) è disponibile in anteprima per i clienti che partecipano al <a href="https://insider.windows.com/">programma Windows Insider</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-958">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="05569-959">Per i clienti non Windows insider su Windows 10 versione 2004 (o versioni successive), ARM64 Photoshop è supportato tramite <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL e OpenGL Compatibility Pack</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-959">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="05569-960">I clienti del programma Windows Insider possono scaricare una versione Insider di OpenCL e OpenGL Compatibility Pack per l'utilizzo con altre app.</span><span class="sxs-lookup"><span data-stu-id="05569-960">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="05569-961">
<strong>Nuovo server perimetrale Microsoft</strong>
</span><span class="sxs-lookup"><span data-stu-id="05569-961">
<strong>The new Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="05569-962">Se le app o i siti Web sono compatibili con Internet Explorer 11, versioni supportate di Google Chrome o qualsiasi versione di Microsoft Edge, saranno compatibili anche con il nuovo Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="05569-962">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with the new Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-963">Poiché il Web è in continua evoluzione, assicurarsi di esaminare l'elenco pubblicato delle <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">modifiche note sulla compatibilità dei siti per Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="05569-963">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="05569-964">
  <strong>Desktop virtuale di Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-964">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="05569-965">Applicazioni virtualizzate che vengono eseguite su Windows Server Remote Desktop Session Host (RDSH) vengono eseguite anche nella multisessione di Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="05569-965">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-966">Le app in esecuzione su qualsiasi ambiente Windows 7 o Windows 10 Virtual Desktop Infrastructure (VDI) vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte di Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="05569-966">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-967">Le app che vengono eseguite su dispostivi client di Windows 7 o Windows 10, vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="05569-967">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="05569-968">
  <strong>Nota:</strong> Le esclusioni e limitazioni per la compatibilità tra più sessioni di Windows 10 Enterprise includono:</span><span class="sxs-lookup"><span data-stu-id="05569-968">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="05569-969">Reindirizzamento limitato dell'hardware.</span><span class="sxs-lookup"><span data-stu-id="05569-969">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-970">Le app con uso intensivo di A/V possono essere eseguite a una capacità ridotta.</span><span class="sxs-lookup"><span data-stu-id="05569-970">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="05569-971">Le app a 16 bit non sono supportate per la versione Desktop virtuale Windows a 64 bit.</span><span class="sxs-lookup"><span data-stu-id="05569-971">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a><span data-ttu-id="05569-972">Il nuovo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="05569-972">The new Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="05569-973"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="05569-973"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="05569-974"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="05569-974"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="05569-975"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="05569-975"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="05569-976"><strong>Microsoft Edge</strong> (per i clienti di Windows 10 Enterprise)</span><span class="sxs-lookup"><span data-stu-id="05569-976"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="05569-977">Vengono fornite indicazioni per la distribuzione remota e assistenza per la compatibilità per: distribuzione del nuovo Microsoft Edge in Windows 10 Enterprise con Microsoft Endpoint Manager (Microsoft endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="05569-977">We provide remote deployment guidance and compatibility assistance for: Deploying the new Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="05569-978">Configurazione Microsoft Edge (mediante criteri di gruppo o di configurazione delle app di Intune e criteri app).</span><span class="sxs-lookup"><span data-stu-id="05569-978">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="05569-979">Inventariare l'elenco dei siti che possono richiedere l'utilizzo in modalità Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="05569-979">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="05569-980">Abilitazione della modalità Internet Explorer con l'elenco dei siti dell'organizzazione esistente.</span><span class="sxs-lookup"><span data-stu-id="05569-980">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="05569-981">Inoltre, se si dispone di un'app Web o di un sito che funziona con Internet Explorer o Google Chrome e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema senza costi aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="05569-981">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="05569-982">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">app assure</a> .</span><span class="sxs-lookup"><span data-stu-id="05569-982">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="05569-983">

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="05569-983">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="05569-984">Gestione dei progetti per la distribuzione di Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="05569-984">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="05569-985">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="05569-985">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
