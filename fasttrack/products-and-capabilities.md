---
title: Prodotti e funzionalità
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 12/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: In questo argomento sono inclusi i dettagli sugli scenari di carico di lavoro supportati da FastTrack e le aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, è possibile creare un piano di correzione che consentirà all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding di esito positivo.
ms.openlocfilehash: 3fdd57f1d0e8bf53b68f0bc54fda4665ca85f513
ms.sourcegitcommit: d69d3e1e478a817f8279e9da98880499e9302665
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 12/01/2020
ms.locfileid: "49525461"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="508e8-104">Prodotti e funzionalità</span><span class="sxs-lookup"><span data-stu-id="508e8-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="508e8-105">Servizi e scenari supportati da FastTrack</span><span class="sxs-lookup"><span data-stu-id="508e8-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="508e8-106">In questo argomento sono inclusi i dettagli sugli scenari di carico di lavoro supportati da FastTrack e le aspettative dell'ambiente di origine necessarie prima di iniziare.</span><span class="sxs-lookup"><span data-stu-id="508e8-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="508e8-107">In base alla configurazione corrente, è possibile creare un piano di correzione che consentirà all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding di esito positivo.</span><span class="sxs-lookup"><span data-stu-id="508e8-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="508e8-108">FastTrack fornisce indicazioni utili per la prima volta con le funzionalità di base (comuni per tutti i servizi online Microsoft) e quindi con l'onboarding di ogni servizio idoneo:</span><span class="sxs-lookup"><span data-stu-id="508e8-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="508e8-109">Generale</span><span class="sxs-lookup"><span data-stu-id="508e8-109">General</span></span>](#general)
  - [<span data-ttu-id="508e8-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="508e8-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="508e8-111">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="508e8-111">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="508e8-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="508e8-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="508e8-113">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="508e8-113">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="508e8-114">App Assure</span><span class="sxs-lookup"><span data-stu-id="508e8-114">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="508e8-115">Il nuovo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="508e8-115">The new Microsoft Edge</span></span>](#the-new-microsoft-edge)

> [!NOTE]
> <span data-ttu-id="508e8-116">Per informazioni sulle previsioni dell’ambiente di origine di Office 365 U.S. Government, vedere [Previsioni dell’ambiente di origine di Office 365 U.S. Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="508e8-116">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="508e8-117">Generale</span><span class="sxs-lookup"><span data-stu-id="508e8-117">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="508e8-118"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-118"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="508e8-119"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-119"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="508e8-120"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-120"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="508e8-121"><strong>Onboarding di base</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-121"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="508e8-122">Vengono fornite istruzioni Remote sull'onboarding di base, che include il provisioning dei servizi, il tenant e l'integrazione delle identità.</span><span class="sxs-lookup"><span data-stu-id="508e8-122">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="508e8-123">Sono inoltre disponibili passaggi per fornire una base per i servizi di onboarding quali Exchange Online, SharePoint Online e Microsoft teams, tra cui una <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussione sulla sicurezza, la connettività di rete e la conformità</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-123">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="508e8-124">L'onboarding per uno o più servizi può iniziare al termine dell'onboarding di base.</span><span class="sxs-lookup"><span data-stu-id="508e8-124">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="508e8-125"></li>
</ul>  

<strong> Integrazione dell'identità </strong></span><span class="sxs-lookup"><span data-stu-id="508e8-125"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="508e8-126">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-126">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="508e8-127">Preparazione delle identità di Active Directory locale per la sincronizzazione di Azure Active Directory (Azure AD), inclusa l'installazione e la configurazione di Azure AD Connect (Single-o multi-Forest) e delle licenze (incluse le licenze basate su gruppo).</span><span class="sxs-lookup"><span data-stu-id="508e8-127">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="508e8-128">Creazione di identità cloud inclusa l'importazione in blocco e la gestione delle licenze, incluso l'utilizzo delle licenze basate su gruppo.</span><span class="sxs-lookup"><span data-stu-id="508e8-128">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="508e8-129">Scelta e attivazione del metodo di autenticazione corretto per il percorso Cloud, la sincronizzazione hash delle password, l'autenticazione pass-through o Active Directory Federation Services (AD FS).</span><span class="sxs-lookup"><span data-stu-id="508e8-129">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="508e8-130">Abilitazione di ADFS per i clienti con una singola foresta di Active Directory e le identità sincronizzate con lo strumento Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="508e8-130">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="508e8-131">Per questo è necessario Windows Server 2012 R2 Active Directory Federation Services 2,0 o versione successiva.</span><span class="sxs-lookup"><span data-stu-id="508e8-131">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="508e8-132">Migrazione dell'autenticazione da AD FS ad Azure ad utilizzando la sincronizzazione hash delle password o l'autenticazione pass-through.</span><span class="sxs-lookup"><span data-stu-id="508e8-132">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="508e8-133">Migrazione delle app preintegrate (come le app di Azure AD Gallery software-as-a-Service (SaaS)) da AD FS ad Azure ad per Single Sign-on (SSO).</span><span class="sxs-lookup"><span data-stu-id="508e8-133">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="508e8-134">Abilitazione delle integrazioni delle app SaaS con SSO dalla raccolta di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-134">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="508e8-135">Abilitazione del provisioning automatico degli utenti per le app SaaS preintegrate elencate nell' <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">elenco app Integration tutorial</a> (solo per le app SaaS di Azure ad Gallery e per il provisioning in uscita solo).</span><span class="sxs-lookup"><span data-stu-id="508e8-135">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="508e8-136"><strong>Abilitazione della rete </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="508e8-136"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="508e8-137">Nell'ambito del vantaggio FastTrack, si consiglia di eseguire le procedure consigliate per la connessione a servizi cloud per garantire i massimi livelli di prestazioni di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-137">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="508e8-138"><strong>Foreste di Active Directory</strong> Il livello di foresta funzionale è impostato su Windows Server 2003 e versioni successive, con la seguente configurazione della foresta:</span><span class="sxs-lookup"><span data-stu-id="508e8-138"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-139">Una foresta unica di Active Directory.</span><span class="sxs-lookup"><span data-stu-id="508e8-139">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="508e8-140">Una singola foresta account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="508e8-140">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-141">Più foreste account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="508e8-141">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-142">Più foreste account di Active Directory con una delle foreste in posizione centrale nella foresta account di Active Directory contenente Exchange e/o Lync 2010, Lync 2013 o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="508e8-142">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="508e8-143">Più foreste account di Active Directory, ognuna con la propria organizzazione di Exchange.</span><span class="sxs-lookup"><span data-stu-id="508e8-143">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="508e8-144">Attività necessarie per la configurazione tenant e l'integrazione con Azure Active Directory, se necessario.</span><span class="sxs-lookup"><span data-stu-id="508e8-144">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="508e8-145">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="508e8-145">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="508e8-146">Per gli scenari a più foreste di Active Directory, se Lync 2010, Lync 2013 o Skype for business è distribuito, deve essere distribuito nella stessa foresta di Active Directory di Exchange.</span><span class="sxs-lookup"><span data-stu-id="508e8-146">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="508e8-147">Quando si implementano più foreste di Active Directory con più organizzazioni di Exchange in una configurazione multi-ibrida di Exchange, gli spazi dei nomi UPN (Shared User Principal Name) tra le foreste di origine non sono supportati.</span><span class="sxs-lookup"><span data-stu-id="508e8-147">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="508e8-148">Gli spazi dei nomi SMTP primari tra organizzazioni di Exchange devono essere separati.</span><span class="sxs-lookup"><span data-stu-id="508e8-148">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="508e8-149">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=845444">Distribuzioni ibride con più insiemi di strutture di Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-149">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="508e8-150">Per tutte le configurazioni di più insiemi di strutture, la distribuzione di Active Directory Federation Services (AD FS) non rientra nell'ambito.</span><span class="sxs-lookup"><span data-stu-id="508e8-150">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="508e8-151">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="508e8-151">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-152"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-152"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="508e8-153">Vengono fornite indicazioni per la distribuzione remota per:</span><span class="sxs-lookup"><span data-stu-id="508e8-153">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-154">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-154">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="508e8-155">Assegnazione dei contratti di licenza con l'utente finale e di licenze basate sul dispositivo utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="508e8-155">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="508e8-156">Installare Microsoft 365 Apps dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="508e8-156">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="508e8-157">Installazione delle app di Office Mobile (ad esempio Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) sui dispositivi iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="508e8-157">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="508e8-158">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-158">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="508e8-159">Selezione e configurazione di un'installazione locale o cloud.</span><span class="sxs-lookup"><span data-stu-id="508e8-159">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="508e8-160">Creazione del codice XML di configurazione dello Strumento di distribuzione di Office con lo Strumento di personalizzazione di Office o del codice XML nativo per configurare il pacchetto di distribuzione.</span><span class="sxs-lookup"><span data-stu-id="508e8-160">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="508e8-161">Distribuzione con Microsoft Endpoint Configuration Manager, che include una guida per la creazione del pacchetto di Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="508e8-161">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="508e8-162">Inoltre, se si dispone di una macro o di un componente aggiuntivo che ha avuto esito positivo con le versioni precedenti di Office e si verificano problemi di compatibilità, vengono fornite indicazioni per correggere il problema di compatibilità senza costi aggiuntivi tramite il programma app assure.</span><span class="sxs-lookup"><span data-stu-id="508e8-162">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="508e8-163">Per ulteriori informazioni, vedere la sezione <strong>assure app</strong> di <a href="#windows-10">Windows 10</a> .</span><span class="sxs-lookup"><span data-stu-id="508e8-163">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="508e8-164">Il software client online deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-164">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="508e8-165"><strong>Integrità della rete</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-165"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="508e8-166">Vengono fornite istruzioni Remote per ottenere e interpretare i dati chiave di connettività di rete dall'ambiente che illustrano la modalità di allineamento dei siti <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">dell'organizzazione ai principi di connettività di rete di</a>Microsoft.</span><span class="sxs-lookup"><span data-stu-id="508e8-166">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="508e8-167">Questo evidenzia il Punteggio di rete che incide direttamente sulla velocità di migrazione, l'esperienza utente, le prestazioni del servizio e l'affidabilità.</span><span class="sxs-lookup"><span data-stu-id="508e8-167">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="508e8-168">È inoltre possibile eseguire le operazioni di correzione evidenziate da questi dati per migliorare il Punteggio di rete.</span><span class="sxs-lookup"><span data-stu-id="508e8-168">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="508e8-169">Accesso all'interfaccia di amministrazione di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-169">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="508e8-170">Sono necessarie le versioni aggiornate delle app Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-170">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="508e8-171">Servizi di posizione abilitati <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">in base alle raccomandazioni relative alle prestazioni di rete nell'interfaccia di amministrazione di Microsoft 365 (Preview)</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-171">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="508e8-172">Office 365</span><span class="sxs-lookup"><span data-stu-id="508e8-172">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="508e8-173"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-173"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="508e8-174"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-174"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="508e8-175"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-175"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="508e8-176"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-176"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="508e8-177">Per Exchange Online, è possibile eseguire la procedura per preparare l'organizzazione all'utilizzo della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="508e8-177">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="508e8-178">I passaggi esatti dipendono dall'ambiente di origine e dai piani di migrazione della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="508e8-178">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="508e8-179">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-179">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-180">Configurare le funzionalità di Exchange Online Protection (EOP) per tutti i domini abilitati alla posta elettronica convalidati in Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-180">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="508e8-181">Puntamento dei record MX (mail Exchange) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-181">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="508e8-182">Configurazione della funzionalità ATP di Office 365 se fa parte del servizio di sottoscrizione.</span><span class="sxs-lookup"><span data-stu-id="508e8-182">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="508e8-183">Per ulteriori informazioni, vedere la sezione <strong>Office 365 Advanced Threat Protection</strong> di questa tabella.</span><span class="sxs-lookup"><span data-stu-id="508e8-183">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="508e8-p113">Configurare la funzionalità di prevenzione della perdita dei dati (DLP) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="508e8-p114">Configurare Office 365 Message Encryption (OME) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="508e8-188">
  <strong>Nota:</strong> Il servizio di replica delle cassette postali (MRS) tenta di migrare i messaggi di posta elettronica IRM (Information Rights Managed) dalla cassetta postale locale alla corrispondente cassetta postale di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="508e8-188">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="508e8-189">La possibilità di leggere i contenuti protetti dopo la migrazione dipende dal fatto che il cliente esegua il mapping e copi i modelli di Active Directory Rights Managed Services (AD RMS) in Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="508e8-189">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="508e8-190">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="508e8-190">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="508e8-191">Configurazione di DNS, tra cui il servizio di individuazione automatica, il servizio di gestione dei messaggi (SPF), la posta elettronica identificata di DomainKeys (DKIM), l'autenticazione del messaggio basata sul dominio, la creazione di report e la conformità (DMARC) e i record MX (se necessario).</span><span class="sxs-lookup"><span data-stu-id="508e8-191">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="508e8-192">Configurare il flusso di posta elettronica tra l'ambiente di messaggistica di origine e Exchange Online (in base alle esigenze).</span><span class="sxs-lookup"><span data-stu-id="508e8-192">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="508e8-193">Eseguire la migrazione della posta dall'ambiente di messaggistica di origine a Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-193">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="508e8-194">Configurazione di client delle cassette postali (Outlook per Windows, Outlook sul web e Outlook per iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="508e8-194">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="508e8-195">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="508e8-195">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="508e8-196">Per informazioni sull'utilizzo del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-196">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="508e8-197">L'ambiente di origine deve disporre di uno dei livelli minimi seguenti:</span><span class="sxs-lookup"><span data-stu-id="508e8-197">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-198">Una o più organizzazioni di Exchange con Exchange Server 2003 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="508e8-198">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="508e8-199">Un singolo ambiente di posta elettronica abilitato per il protocollo IMAP.</span><span class="sxs-lookup"><span data-stu-id="508e8-199">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="508e8-200">Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).</span><span class="sxs-lookup"><span data-stu-id="508e8-200">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="508e8-201">Per informazioni su multi-Geo capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=872776">multi-Geo capabilities in Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-201">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="508e8-202">Il software client online come Project per Office 365, Outlook per Windows, Outlook per iOS e Android, il client di sincronizzazione di OneDrive for business, il desktop Power BI e Skype for business devono essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-202">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-203"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-203"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="508e8-204">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-204">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-205">Etichette e criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-205">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-206">Gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="508e8-206">Records management.</span></span>  </li>
<li>  <span data-ttu-id="508e8-207">Criteri di eliminazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-207">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-208">Conformità delle comunicazioni.</span><span class="sxs-lookup"><span data-stu-id="508e8-208">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="508e8-209">Gestione dei rischi Insider.</span><span class="sxs-lookup"><span data-stu-id="508e8-209">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="508e8-210">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="508e8-210">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="508e8-211">

  <strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-211">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="508e8-212">Sviluppo di un piano file di gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="508e8-212">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="508e8-213">Connettori di dati.</span><span class="sxs-lookup"><span data-stu-id="508e8-213">Data connectors.</span></span></li>
<li> <span data-ttu-id="508e8-214">Barriere informative.</span><span class="sxs-lookup"><span data-stu-id="508e8-214">Information barriers.</span></span></li>
<li> <span data-ttu-id="508e8-215">Gestione degli accessi con privilegi.</span><span class="sxs-lookup"><span data-stu-id="508e8-215">Privileged access management.</span></span></li>
<li> <span data-ttu-id="508e8-216">Sviluppo dell'architettura delle informazioni in SharePoint.</span><span class="sxs-lookup"><span data-stu-id="508e8-216">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="508e8-217">Scripting e codifica personalizzato.</span><span class="sxs-lookup"><span data-stu-id="508e8-217">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="508e8-218">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="508e8-218">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="508e8-219"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-219"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="508e8-220">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-220">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-221">Classificazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="508e8-221">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="508e8-222">Tipi di informazioni sensibili.</span><span class="sxs-lookup"><span data-stu-id="508e8-222">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="508e8-223">Creare etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="508e8-223">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="508e8-224">Applicazione di etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="508e8-224">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="508e8-225">Etichettatura unificata.</span><span class="sxs-lookup"><span data-stu-id="508e8-225">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="508e8-226">Classificatori sottoponibili a formazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-226">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="508e8-227">Conoscere i dati tramite Esplora contenuto ed Esplora attività.</span><span class="sxs-lookup"><span data-stu-id="508e8-227">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="508e8-228">Pubblicare etichette con criteri (manuale e automatico).</span><span class="sxs-lookup"><span data-stu-id="508e8-228">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="508e8-229">Creare criteri di prevenzione della perdita dei dati (DLP) per chat e canali di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="508e8-229">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="508e8-230">Creazione di criteri DLP di endpoint per i dispositivi Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-230">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="508e8-231">

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-231">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="508e8-232">Chiave del cliente.</span><span class="sxs-lookup"><span data-stu-id="508e8-232">Customer key.</span></span></li>
<li><span data-ttu-id="508e8-233">Sviluppo di espressioni regolari (RegEx) personalizzate per i tipi di informazioni riservate.</span><span class="sxs-lookup"><span data-stu-id="508e8-233">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="508e8-234">Creazione o modifica di dizionari di parole chiave.</span><span class="sxs-lookup"><span data-stu-id="508e8-234">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="508e8-235">Scripting e codifica personalizzato.</span><span class="sxs-lookup"><span data-stu-id="508e8-235">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="508e8-236">
<strong>Nota:</strong> Per ulteriori informazioni, vedere <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-236">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="508e8-237">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="508e8-237">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-238"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-238"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="508e8-239">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-239">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-240">Conferma dei requisiti minimi nei gruppi di Exchange Online, SharePoint Online, Office 365 e Azure AD per il supporto dei team.</span><span class="sxs-lookup"><span data-stu-id="508e8-240">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="508e8-241">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="508e8-241">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="508e8-242">Configurazione di DNS.</span><span class="sxs-lookup"><span data-stu-id="508e8-242">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="508e8-243">Conferma dell'abilitazione di Teams nel tenant Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-243">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="508e8-244">Abilitazione o disabilitazione delle licenze utente.</span><span class="sxs-lookup"><span data-stu-id="508e8-244">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="508e8-245">Valutazione della rete per i team:</span><span class="sxs-lookup"><span data-stu-id="508e8-245">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-246">Controlli di porta ed endpoint.</span><span class="sxs-lookup"><span data-stu-id="508e8-246">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="508e8-247">Controlli sulla qualità della connessione.</span><span class="sxs-lookup"><span data-stu-id="508e8-247">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="508e8-248">Stime sulla larghezza di banda.</span><span class="sxs-lookup"><span data-stu-id="508e8-248">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="508e8-249">Configurazione dei criteri delle app per i team (teams Web App, teams desktop app e teams for iOS and Android app).</span><span class="sxs-lookup"><span data-stu-id="508e8-249">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="508e8-250">Se applicabile, vengono fornite anche indicazioni per:</span><span class="sxs-lookup"><span data-stu-id="508e8-250">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-251">Dispositivi della sala Microsoft teams:</span><span class="sxs-lookup"><span data-stu-id="508e8-251">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="508e8-252">Creazione di account online necessari per i dispositivi di telefonia e di sala riunioni supportati elencati nel <a href="https://go.microsoft.com/fwlink/?linkid=2066478">catalogo dei dispositivi Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-252">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="508e8-253">Assistenza remota con la configurazione sul fianco del servizio dei dispositivi Microsoft teams Rooms certificati.</span><span class="sxs-lookup"><span data-stu-id="508e8-253">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="508e8-254">Abilitazione dell'audioconferenza:</span><span class="sxs-lookup"><span data-stu-id="508e8-254">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="508e8-255">Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.</span><span class="sxs-lookup"><span data-stu-id="508e8-255">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="508e8-256">Assegnazione di bridge per conferenze agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="508e8-256">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="508e8-257">Sistema telefonico:</span><span class="sxs-lookup"><span data-stu-id="508e8-257">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-258">Configurazione aziendale delle impostazioni predefinite vocali cloud.</span><span class="sxs-lookup"><span data-stu-id="508e8-258">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="508e8-259">Guida ai piani di chiamata (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercati disponibili</a>):</span><span class="sxs-lookup"><span data-stu-id="508e8-259">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="508e8-260">Assegnazione di numeri agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="508e8-260">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="508e8-261">Guida alla portabilità del numero locale tramite UI fino a 999.</span><span class="sxs-lookup"><span data-stu-id="508e8-261">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="508e8-262">Supporto RS per la richiesta di servizio di portabilità del numero locale superiore a 999.</span><span class="sxs-lookup"><span data-stu-id="508e8-262">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="508e8-263">Guida per il routing diretto:</span><span class="sxs-lookup"><span data-stu-id="508e8-263">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-264">Linee guida per l'installazione dell'organizzazione per la progettazione di routing diretto di scenari ospitati da partner o scenari distribuiti dal cliente per un massimo di 10 siti.</span><span class="sxs-lookup"><span data-stu-id="508e8-264">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="508e8-265">Verifica della configurazione del session border controller (SBC).</span><span class="sxs-lookup"><span data-stu-id="508e8-265">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="508e8-266">Assistenza remota con la configurazione del dial plan.</span><span class="sxs-lookup"><span data-stu-id="508e8-266">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="508e8-267">Configurazione della route vocale.</span><span class="sxs-lookup"><span data-stu-id="508e8-267">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="508e8-268">Bypass multimediale e ottimizzazione dei supporti locali.</span><span class="sxs-lookup"><span data-stu-id="508e8-268">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="508e8-269">Abilitazione degli eventi live in Teams.</span><span class="sxs-lookup"><span data-stu-id="508e8-269">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="508e8-270">Configurazione dell'organizzazione e integrazione in Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="508e8-270">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="508e8-271">Linee guida per la transizione da Skype for business a teams.</span><span class="sxs-lookup"><span data-stu-id="508e8-271">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="508e8-272">Identità abilitate in Azure Active Directory per Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-272">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="508e8-273">Utenti abilitati per SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="508e8-273">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="508e8-274">Le cassette postali di Exchange sono presenti (online e in locale in una configurazione ibrida di Exchange).</span><span class="sxs-lookup"><span data-stu-id="508e8-274">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="508e8-275">Abilitato per i gruppi di Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-275">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="508e8-276">
  <strong>Nota:</strong> Se gli utenti non sono assegnati e abilitati con le licenze di SharePoint Online, non avranno l'archiviazione di OneDrive for business in Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-276">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="508e8-277">La condivisione dei file continua a funzionare nei canali, ma gli utenti non possono condividere file in chat senza OneDrive for Business Storage in Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-277">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="508e8-278">I team non supportano SharePoint locale.</span><span class="sxs-lookup"><span data-stu-id="508e8-278">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="508e8-279">
  <strong>Nota:</strong> Lo stato ideale è che tutti gli utenti dispongano delle cassette postali in Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="508e8-279">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="508e8-280">Gli utenti con cassette postali ospitate in locale devono avere le rispettive identità sincronizzate con la directory di Office 365 tramite Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="508e8-280">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="508e8-281">Per questi clienti ibridi di Exchange, se la cassetta postale dell'utente è in locale, l'utente non è in grado di aggiungere o configurare i connettori.</span><span class="sxs-lookup"><span data-stu-id="508e8-281">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="508e8-282">I programmi di installazione per i client desktop di Microsoft Teams per Windows e Mac possono essere scaricati da <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-282">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="508e8-283"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-283"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="508e8-284">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-285">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="508e8-285">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="508e8-286">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="508e8-286">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="508e8-287">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="508e8-287">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="508e8-288">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="508e8-288">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="508e8-289">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="508e8-289">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-290"><strong>Outlook per iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-290"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="508e8-291">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-291">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-292">Download di Outlook per iOS e Android tramite l'Apple App Store e Google Play.</span><span class="sxs-lookup"><span data-stu-id="508e8-292">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="508e8-293">Configurazione degli account e accesso alla cassetta postale di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="508e8-293">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="508e8-294">Protezione di Outlook Mobile (vedere <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">protezione di Outlook per iOS e Android in Exchange Online</a> per ulteriori informazioni).</span><span class="sxs-lookup"><span data-stu-id="508e8-294">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="508e8-295">Identità abilitate in Azure Active Directory per Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-295">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="508e8-296">Exchange Online configurato e licenze assegnate.</span><span class="sxs-lookup"><span data-stu-id="508e8-296">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="508e8-297"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-297"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="508e8-298">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-298">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-299">Assegnare licenze di Power BI.</span><span class="sxs-lookup"><span data-stu-id="508e8-299">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="508e8-300">Distribuire l'app Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="508e8-300">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="508e8-301">Il software client online come Power BI desktop deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-301">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-302"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-302"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="508e8-303">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-303">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-304">Verificare la funzionalità di base di SharePoint sulla quale fa affidamento Project Online.</span><span class="sxs-lookup"><span data-stu-id="508e8-304">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="508e8-305">Aggiungere il servizio Project Online al tenant (inclusa l'aggiunta di sottoscrizioni per gli utenti).</span><span class="sxs-lookup"><span data-stu-id="508e8-305">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="508e8-306">Configurare il pool di risorse organizzazione (ERP).</span><span class="sxs-lookup"><span data-stu-id="508e8-306">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="508e8-307">Creare il primo progetto.</span><span class="sxs-lookup"><span data-stu-id="508e8-307">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="508e8-308">Il software client online come Project per Office 365 deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-308">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="508e8-309"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-309"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="508e8-310">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-310">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-311">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-311">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="508e8-312">Assegnare i contratti di licenza con l'utente finale utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="508e8-312">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="508e8-313">Installare Client desktop di Project Online dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="508e8-313">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="508e8-314">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-314">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="508e8-315">Configurare un unico server di distribuzione nel sito per Client desktop di Project Online, includendo una guida per la creazione del file configuration.xml da usare con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-315">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="508e8-316">Connettere Client desktop di Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="508e8-316">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="508e8-317">Il software client online come Project per Office 365 deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-317">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-318"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-318"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="508e8-319">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-319">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-320">Configurazione DNS.</span><span class="sxs-lookup"><span data-stu-id="508e8-320">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="508e8-321">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="508e8-321">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="508e8-322">Provisioning di utenti e licenze.</span><span class="sxs-lookup"><span data-stu-id="508e8-322">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="508e8-323">Abilitazione alla creazione di siti per l'amministratore di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="508e8-323">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="508e8-324">Pianificazione delle raccolte di siti.</span><span class="sxs-lookup"><span data-stu-id="508e8-324">Planning site collections.</span></span></li>
<li><span data-ttu-id="508e8-325">Protezione del contenuto e gestione delle autorizzazioni.</span><span class="sxs-lookup"><span data-stu-id="508e8-325">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="508e8-326">Configurazione delle caratteristiche di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="508e8-326">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="508e8-327">Configurazione delle funzionalità dell'ambiente ibrido di SharePoint, come la ricerca ibrida, i siti ibridi, la tassonomia ibrida, i tipi di contenuto, la creazione siti in modalità self-service ibrida (solo SharePoint Server 2013), l'icona di avvio delle app estesa, OneDrive for Business ibrido e i siti extranet.</span><span class="sxs-lookup"><span data-stu-id="508e8-327">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="508e8-328">Approccio di migrazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-328">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="508e8-329">Vengono fornite indicazioni aggiuntive per OneDrive for business a seconda della versione di SharePoint, ad esempio:</span><span class="sxs-lookup"><span data-stu-id="508e8-329">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-330">Identificare le opzioni di integrazione e la revisione dell'infrastruttura di rete e della larghezza di banda in locale e online.</span><span class="sxs-lookup"><span data-stu-id="508e8-330">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="508e8-331">Installazione di SharePoint Online 2013 SP1 (se applicabile), pianificazione e implementazione dei requisiti di sincronizzazione e identità e identificazione del client di sincronizzazione di OneDrive for business.</span><span class="sxs-lookup"><span data-stu-id="508e8-331">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="508e8-332">Pianificazione e implementazione di una singola implementazione per tutti gli utenti (o per una distribuzione in fasi).</span><span class="sxs-lookup"><span data-stu-id="508e8-332">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="508e8-333">Assegnazione delle licenze, Reindirizzamento dei siti personali e delle raccolte documenti personale a Office 365 (applicabile a SharePoint Online 2013), impostazione di gruppi di destinatari per controllare l'accesso a OneDrive (applicabile a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="508e8-333">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="508e8-334">Reindirizzamento o spostamento di cartelle note in OneDrive.</span><span class="sxs-lookup"><span data-stu-id="508e8-334">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="508e8-335">Distribuzione della sincronizzazione client di OneDrive for business.</span><span class="sxs-lookup"><span data-stu-id="508e8-335">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="508e8-336">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="508e8-336">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="508e8-337">Per informazioni sull'utilizzo del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-337">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="508e8-338"><strong>Per l'ambiente ibrido di SharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-338"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="508e8-339">La configurazione ibrida di SharePoint include la configurazione della ricerca ibrida, dei siti, della tassonomia, dei tipi di contenuto, di OneDrive for business, di un'applicazione di avvio delle app estesa, di siti Extranet e della creazione di siti in modalità self-service connessi da un singolo ambiente SharePoint Online di destinazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-339">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="508e8-340">
  <strong>Nota:</strong> La creazione di siti in modalità self-service non è in ambito con i server locali che eseguono SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="508e8-340">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="508e8-341">Per abilitare l'ambiente ibrido di SharePoint, è necessario disporre di uno dei seguenti ambienti locali di SharePoint Server: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="508e8-341">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="508e8-342">
  <strong>Nota:</strong> L'aggiornamento degli ambienti di SharePoint locali a SharePoint Server non è incluso nell'ambito.</span><span class="sxs-lookup"><span data-stu-id="508e8-342">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="508e8-343">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="508e8-343">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="508e8-344">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=853548">livelli di aggiornamento pubblico minimi per le funzionalità ibride di SharePoint</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="508e8-344">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="508e8-345">
  <strong>Nota:</strong> Per informazioni su multi-Geo capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=831056">multi-Geo capabilities in OneDrive e SharePoint online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="508e8-345">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-346"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-346"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="508e8-347">Vengono fornite istruzioni Remote per abilitare il servizio Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="508e8-347">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="508e8-348">Il software client online deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-348">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="508e8-349">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="508e8-349">Enterprise Mobility + Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-350"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-350"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="508e8-351">Vengono fornite istruzioni Remote per la protezione delle identità cloud per gli scenari seguenti.</span><span class="sxs-lookup"><span data-stu-id="508e8-351">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="508e8-352">

<strong>Infrastruttura di Fondazione sicura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="508e8-352">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="508e8-353">La configurazione e l'abilitazione dell'autenticazione avanzata per le identità, tra cui la protezione con l'autenticazione a più fattori di Azure (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure Mae e la reimpostazione della password self-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="508e8-353">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="508e8-354">Per i clienti non Azure AD Premium, vengono fornite indicazioni per proteggere le identità utilizzando le impostazioni predefinite per la sicurezza.</span><span class="sxs-lookup"><span data-stu-id="508e8-354">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="508e8-355">Per i clienti di Azure AD Premium, vengono fornite indicazioni per proteggere le identità con accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="508e8-355">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="508e8-356">Rilevamento e blocco dell'utilizzo di password deboli con la protezione delle password di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-356">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="508e8-357">Protezione dell'accesso remoto alle app Web locali con proxy di applicazione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-357">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="508e8-358">Abilitazione del rilevamento e del monitoraggio basati sui rischi con la protezione delle identità di Azure.</span><span class="sxs-lookup"><span data-stu-id="508e8-358">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="508e8-359">Abilitazione di una schermata di accesso personalizzata, tra cui logo, testo e immagini con personalizzazione personalizzata.</span><span class="sxs-lookup"><span data-stu-id="508e8-359">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="508e8-360">Condivisione sicura delle app e dei servizi con gli utenti guest che utilizzano Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="508e8-360">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="508e8-361">Gestione dell'accesso per gli amministratori di Office 365 mediante ruoli amministrativi basati sul controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.</span><span class="sxs-lookup"><span data-stu-id="508e8-361">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="508e8-362">Configuring Hybrid Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="508e8-362">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="508e8-363">Configurazione di Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="508e8-363">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="508e8-364">
  
<strong>Monitoraggio e creazione di report</strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-364">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="508e8-365">Abilitazione del monitoraggio remoto per ADFS, Azure AD Connect e controller di dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="508e8-365">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="508e8-366">
  
<strong>Governance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-366">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="508e8-367">Gestione dell'identità di Azure AD e del ciclo di vita di accesso in scala con la gestione dei diritti di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-367">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="508e8-368">Gestire le appartenenze ai gruppi di Azure AD, l'accesso alle app Enterprise e le assegnazioni di ruolo con le recensioni di Azure AD Access.</span><span class="sxs-lookup"><span data-stu-id="508e8-368">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-369">Revisione delle condizioni di utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-369">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-370">Gestione e controllo dell'accesso agli account amministratore privilegiati con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="508e8-370">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="508e8-371">
  
<strong>Automazione ed efficienza </strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-371">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="508e8-372">Abilitazione di Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="508e8-372">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="508e8-373">Consentendo agli utenti di creare e gestire i propri gruppi di sicurezza cloud o di Office 365 con la gestione di gruppi self-service di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-373">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="508e8-374">Gestione dell'accesso delegato alle app Enterprise con la gestione dei gruppi delegati AD Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-374">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="508e8-375">Abilitazione di gruppi dinamici di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-375">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="508e8-376">Organizzazione delle app nel portale My Apps using Collections.</span><span class="sxs-lookup"><span data-stu-id="508e8-376">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="508e8-377">Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione di problemi identificati che impediscono l'integrazione con Azure AD e le funzionalità di Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="508e8-377">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="508e8-378"><strong>Protezione delle informazioni di Azure </strong></span><span class="sxs-lookup"><span data-stu-id="508e8-378"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="508e8-379">Vengono fornite indicazioni su come:</span><span class="sxs-lookup"><span data-stu-id="508e8-379">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-380">Attivare e configurare il tenant.</span><span class="sxs-lookup"><span data-stu-id="508e8-380">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="508e8-381">Creare e configurare etichette e criteri.</span><span class="sxs-lookup"><span data-stu-id="508e8-381">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-382">Applicare la protezione delle informazioni ai documenti.</span><span class="sxs-lookup"><span data-stu-id="508e8-382">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="508e8-383">Classificare ed etichettare automaticamente le informazioni nelle app di Office, come Word, PowerPoint, Excel e Outlook, che eseguono Windows e con il client di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="508e8-383">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="508e8-384">Individuare e contrassegnare i file in REST utilizzando lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="508e8-384">Discover and label files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="508e8-385">Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="508e8-385">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="508e8-386">Vengono inoltre fornite indicazioni per l'applicazione della protezione tramite Microsoft Azure Rights Management Services (Azure RMS), la crittografia dei messaggi di Office 365 (OME) e la prevenzione della perdita di dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="508e8-386">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="508e8-387">Le responsabilità dei prerequisiti dei clienti includono:</span><span class="sxs-lookup"><span data-stu-id="508e8-387">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-388">Un elenco di percorsi di condivisione file da analizzare.</span><span class="sxs-lookup"><span data-stu-id="508e8-388">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="508e8-389">Una tassonomia di classificazione approvata.</span><span class="sxs-lookup"><span data-stu-id="508e8-389">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="508e8-390">Informazioni su eventuali restrizioni o requisiti normativi relativi alla gestione delle chiavi.</span><span class="sxs-lookup"><span data-stu-id="508e8-390">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="508e8-391">Un account di servizio creato per Active Directory locale che è stato sincronizzato con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-391">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="508e8-392">Etichette configurate per la classificazione e la protezione.</span><span class="sxs-lookup"><span data-stu-id="508e8-392">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="508e8-393">Tutti i prerequisiti per lo scanner di Azure Information Protection sono sul posto.</span><span class="sxs-lookup"><span data-stu-id="508e8-393">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="508e8-394">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">prerequisiti per l'installazione e la distribuzione di Azure Information Protection Unified Labeling scanner</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-394">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="508e8-395">Verificare che i dispositivi utente eseguano un sistema operativo supportato e che siano installati i prerequisiti necessari.</span><span class="sxs-lookup"><span data-stu-id="508e8-395">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="508e8-396">Per ulteriori informazioni, vedere i seguenti elementi.</span><span class="sxs-lookup"><span data-stu-id="508e8-396">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="508e8-397"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Guida per gli amministratori: installare il client di etichettatura unificata di Azure Information Protection per gli utenti</a>   </span><span class="sxs-lookup"><span data-stu-id="508e8-397"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="508e8-398"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Che cos'è l'app Azure Information Protection per iOS o Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="508e8-398"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="508e8-399">Installazione e configurazione del connettore e dei server di Azure RMS incluso il connettore RMS (AD RMS) di Active Directory per il supporto ibrido.</span><span class="sxs-lookup"><span data-stu-id="508e8-399">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="508e8-400">Installazione e configurazione di Bring your own key (BYOK), Double Key Encryption (DKE) (solo client di etichettatura unificata) oppure conserva la propria chiave (HYOK) (solo client classico) è necessario disporre di una di queste opzioni per la distribuzione.</span><span class="sxs-lookup"><span data-stu-id="508e8-400">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-401"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-401"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="508e8-402">Vengono fornite indicazioni su come preparare l'utilizzo di Intune come provider di gestione dei dispositivi mobili basato sul cloud (MDM) e mobile app Management (MAM) per le app e i dispositivi.</span><span class="sxs-lookup"><span data-stu-id="508e8-402">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="508e8-403">I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili.</span><span class="sxs-lookup"><span data-stu-id="508e8-403">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="508e8-404">I passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="508e8-404">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-405">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="508e8-405">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="508e8-406">Configurazione delle identità per l'utilizzo da parte di Intune mediante l'uso di Active Directory o identità cloud locali (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="508e8-406">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="508e8-407">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="508e8-407">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="508e8-408">Configurazione dell'autorità MDM, in base alle esigenze di gestione, tra cui:</span><span class="sxs-lookup"><span data-stu-id="508e8-408">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-409">Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.</span><span class="sxs-lookup"><span data-stu-id="508e8-409">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="508e8-410">Fornire le indicazioni di MDM per:</span><span class="sxs-lookup"><span data-stu-id="508e8-410">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-411">Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.</span><span class="sxs-lookup"><span data-stu-id="508e8-411">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-412">Configurare criteri e servizi di gestione MDM come:</span><span class="sxs-lookup"><span data-stu-id="508e8-412">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-413">Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o Deep Links.</span><span class="sxs-lookup"><span data-stu-id="508e8-413">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="508e8-414">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="508e8-414">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-415">Distribuzione di messaggi di posta elettronica, reti wireless e profili VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-415">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="508e8-416">Connessione al data warehouse di Intune.</span><span class="sxs-lookup"><span data-stu-id="508e8-416">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="508e8-417">Integrare Intune con:</span><span class="sxs-lookup"><span data-stu-id="508e8-417">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-418">Visualizzatore team per assistenza remota (è necessario un abbonamento a un visualizzatore di Team).</span><span class="sxs-lookup"><span data-stu-id="508e8-418">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="508e8-419">Soluzioni partner per la difesa di minacce mobili (MTD) (è necessaria una sottoscrizione di MTD).</span><span class="sxs-lookup"><span data-stu-id="508e8-419">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="508e8-420">Una soluzione Telecom Expense Management (è richiesta una sottoscrizione di una soluzione per la gestione delle spese Telecom).</span><span class="sxs-lookup"><span data-stu-id="508e8-420">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="508e8-421">Microsoft Defender ATP (sono necessarie licenze Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="508e8-421">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="508e8-422">Registrare i dispositivi di ogni piattaforma supportata in Intune.</span><span class="sxs-lookup"><span data-stu-id="508e8-422">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="508e8-423">Fornire indicazioni sulla protezione delle app:</span><span class="sxs-lookup"><span data-stu-id="508e8-423">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-424">Configurare criteri di protezione delle app per ogni piattaforma supportata.</span><span class="sxs-lookup"><span data-stu-id="508e8-424">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="508e8-425">Configurazione dei criteri di accesso condizionale per le app gestite.</span><span class="sxs-lookup"><span data-stu-id="508e8-425">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="508e8-426">Indirizzare i gruppi di utenti corretti con i criteri MAM precedentemente citati.</span><span class="sxs-lookup"><span data-stu-id="508e8-426">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-427">Utilizzo di report sull'utilizzo delle app gestite.</span><span class="sxs-lookup"><span data-stu-id="508e8-427">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="508e8-428">Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="508e8-428">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="508e8-429">
  <strong>Nota</strong>: la gestione dei PC legacy non è più supportata dal 15 ottobre 2020 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="508e8-429">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="508e8-430"></li>
</ul>
  
<strong>Collegamento tramite cloud</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-430"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="508e8-431">Si consiglia di preparare gli ambienti di gestione della configurazione esistenti tramite cloud con Intune.</span><span class="sxs-lookup"><span data-stu-id="508e8-431">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="508e8-432">I passaggi esatti dipendono dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="508e8-432">The exact steps depend on your source environment.</span></span> <span data-ttu-id="508e8-433">Questi passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="508e8-433">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="508e8-434">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="508e8-434">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="508e8-435">Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.</span><span class="sxs-lookup"><span data-stu-id="508e8-435">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="508e8-436">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="508e8-436">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="508e8-437">Fornire linee guida per la configurazione di un join ibrido di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="508e8-437">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="508e8-438">Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.</span><span class="sxs-lookup"><span data-stu-id="508e8-438">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="508e8-439">Offrire indicazioni su come configurare il gateway di gestione cloud.</span><span class="sxs-lookup"><span data-stu-id="508e8-439">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="508e8-440">Configurare i carichi di lavoro supportati che si desidera passare a Intune.</span><span class="sxs-lookup"><span data-stu-id="508e8-440">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="508e8-441">Installare il client Configuration Manager nei dispositivi registrati di Intune.</span><span class="sxs-lookup"><span data-stu-id="508e8-441">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="508e8-442"><strong>Distribuire Outlook Mobile per iOS e Android in modo sicuro</strong> È possibile fornire assistenza per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire che gli utenti dispongano di tutte le app necessarie installate.</span><span class="sxs-lookup"><span data-stu-id="508e8-442"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="508e8-443">La procedura per distribuire in modo sicuro Outlook Mobile per iOS e Android con Intune dipende dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="508e8-443">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="508e8-444">Può includere:</span><span class="sxs-lookup"><span data-stu-id="508e8-444">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-445">Scaricare le app di Outlook per iOS e Android, Microsoft Authenticator e il portale aziendale di Intune tramite l'App Store di Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="508e8-445">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="508e8-446">Fornire indicazioni sulla configurazione:</span><span class="sxs-lookup"><span data-stu-id="508e8-446">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-447">Distribuzione di Outlook per iOS e Android, Microsoft Authenticator e Intune per le app del portale aziendale con Intune.</span><span class="sxs-lookup"><span data-stu-id="508e8-447">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="508e8-448">Criteri di protezione delle app.</span><span class="sxs-lookup"><span data-stu-id="508e8-448">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-449">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="508e8-449">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="508e8-450">Criteri di configurazione dell'app.</span><span class="sxs-lookup"><span data-stu-id="508e8-450">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="508e8-451"><strong>Nota</strong>: FastTrack non supporta la protezione di Outlook per iOS e Android con i criteri cassetta postale dei dispositivi mobili di Exchange.</span><span class="sxs-lookup"><span data-stu-id="508e8-451"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="508e8-452">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="508e8-452">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="508e8-453">Gli amministratori IT devono disporre dell'autorità di certificazione, della rete wireless e delle infrastrutture VPN esistenti che già operano nei rispettivi ambienti di produzione durante la pianificazione della distribuzione della rete wireless e dei profili VPN con Intune.</span><span class="sxs-lookup"><span data-stu-id="508e8-453">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="508e8-454"><strong>Nota</strong>: il vantaggio del servizio di FastTrack non include assistenza per la configurazione o la configurazione di autorità di certificazione, reti wireless, infrastrutture VPN o certificati push di Apple MDM per Intune.</span><span class="sxs-lookup"><span data-stu-id="508e8-454"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="508e8-455"><strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud.</span><span class="sxs-lookup"><span data-stu-id="508e8-455"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="508e8-456">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="508e8-456">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="508e8-457"><strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-457"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="508e8-458"><strong>Nota</strong>: viene fornita assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-458"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="508e8-459">Non viene fornita assistenza per l'acquisto, la gestione delle licenze o l'attivazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-459">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="508e8-460">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="508e8-460">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="508e8-461"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-461"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="508e8-462">Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="508e8-462">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="508e8-463">Windows 10</span><span class="sxs-lookup"><span data-stu-id="508e8-463">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="508e8-464"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-464"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="508e8-465"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-465"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="508e8-466"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-466"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="508e8-467"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-467"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="508e8-468">Vengono fornite indicazioni per l'aggiornamento da Windows 7 Professional e Windows 8,1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="508e8-468">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="508e8-469">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-469">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-470">Informazioni sull'intenzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-470">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="508e8-471">Valutazione dell'ambiente di origine e dei requisiti (verificare che Microsoft endpoint Configuration Manager venga aggiornato al livello richiesto per supportare la distribuzione di Windows 10).</span><span class="sxs-lookup"><span data-stu-id="508e8-471">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="508e8-472">Distribuzione delle app di Windows 10 Enterprise e Microsoft 365 tramite Microsoft endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-472">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="508e8-473">Opzioni di raccomandazione per valutare le app di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-473">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="508e8-474">Abilitazione dell'utilizzo di analisi desktop e linee guida tramite la creazione di un piano di distribuzione di analisi desktop.</span><span class="sxs-lookup"><span data-stu-id="508e8-474">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="508e8-475">Microsoft 365 Apps Compatibility assessment by leveraging The Office 365 prontezza dashboard in Configuration Manager o with the stand-alone Pronation Toolkit for Office Plus Assistance Deploying Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="508e8-475">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="508e8-476">Creazione di un elenco di controllo di correzione su cosa è necessario fare per riportare l'ambiente di origine ai requisiti minimi per una distribuzione corretta.</span><span class="sxs-lookup"><span data-stu-id="508e8-476">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="508e8-477">Fornire indicazioni sull'aggiornamento per i dispositivi esistenti a Windows 10 Enterprise, se soddisfano i requisiti hardware necessari per il dispositivo.</span><span class="sxs-lookup"><span data-stu-id="508e8-477">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="508e8-478">Fornire indicazioni sull'aggiornamento per supportare il movimento di distribuzione esistente.</span><span class="sxs-lookup"><span data-stu-id="508e8-478">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="508e8-479">FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-479">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="508e8-480">Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="508e8-480">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="508e8-481">Distribuzione di app Microsoft 365 mediante Configuration Manager nell'ambito della distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-481">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="508e8-482">Fornire indicazioni per aiutare l'organizzazione a rimanere sempre aggiornati con le app Windows 10 Enterprise e Microsoft 365 utilizzando l'ambiente di gestione della configurazione esistente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-482">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="508e8-483">
  <strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-483">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="508e8-484">Aggiornamento di Configuration Manager al Current Branch.</span><span class="sxs-lookup"><span data-stu-id="508e8-484">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="508e8-485">Creazione di immagini personalizzate per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-485">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="508e8-486">Creazione e supporto degli script di distribuzione per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-486">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="508e8-487">Conversione di un sistema di Windows 10 dal BIOS a Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="508e8-487">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="508e8-488">Abilitare le funzionalità di sicurezza di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-488">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="508e8-489">Configurazione di Windows Deployment Services (WDS) per il boot di Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="508e8-489">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="508e8-490">Uso di Microsoft Deployment Toolkit (MDT) per acquisire e distribuire immagini di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-490">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="508e8-491">Uso dell’Utilità di migrazione dello stato utente (USMT).</span><span class="sxs-lookup"><span data-stu-id="508e8-491">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="508e8-492">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="508e8-492">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="508e8-493">Per l'aggiornamento del PC, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="508e8-493">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-494">Sistema operativo di origine: Windows 7 Enterprise o Professional, Windows 8,1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="508e8-494">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="508e8-495">Dispositivi: fattore di forma desktop, notebook o tablet.</span><span class="sxs-lookup"><span data-stu-id="508e8-495">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="508e8-496">Sistema operativo di destinazione: Window 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="508e8-496">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="508e8-497">Per l'aggiornamento dell'infrastruttura, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="508e8-497">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-498">Gestione configurazione Microsoft endpoint.</span><span class="sxs-lookup"><span data-stu-id="508e8-498">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="508e8-499">La versione di Configuration Manager deve essere supportata dalla versione di destinazione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-499">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="508e8-500">Per altre informazioni, vedere la tabella di supporto di Configuration Manager in <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Supporto per Windows 10 in Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-500">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="508e8-501"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-501"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="508e8-502">Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.</span><span class="sxs-lookup"><span data-stu-id="508e8-502">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="508e8-503">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-503">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-504">Distribuzione delle tecnologie per la protezione degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="508e8-504">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="508e8-505">Configurazione di Endpoint Protection e dei profili di restrizione del dispositivo.</span><span class="sxs-lookup"><span data-stu-id="508e8-505">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="508e8-506">Valutare la versione del sistema operativo e la gestione dei dispositivi (tra cui Intune, Microsoft endpoint Configuration Manager, oggetti Criteri di gruppo (GPO) e configurazioni di terze parti), nonché lo stato di Windows Defender AV Services o di altri software di sicurezza di endpoint.</span><span class="sxs-lookup"><span data-stu-id="508e8-506">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="508e8-507">Valutazione dello stato dei servizi AV di Windows o di altri software di sicurezza di endpoint.</span><span class="sxs-lookup"><span data-stu-id="508e8-507">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="508e8-508">Valutazione di proxy e firewall che limitano il traffico di rete.</span><span class="sxs-lookup"><span data-stu-id="508e8-508">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="508e8-509">Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo di agente ATP utilizzando un endpoint di bordo.</span><span class="sxs-lookup"><span data-stu-id="508e8-509">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="508e8-510">Guida alla distribuzione, assistenza alla configurazione e istruzione su:</span><span class="sxs-lookup"><span data-stu-id="508e8-510">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="508e8-511">Gestione delle minacce e delle vulnerabilità.</span><span class="sxs-lookup"><span data-stu-id="508e8-511">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-512">Riduzione della superficie di attacco.</span><span class="sxs-lookup"><span data-stu-id="508e8-512">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-513">Protezione di nuova generazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-513">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-514">Rilevamento e risposta degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="508e8-514">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-515">Indagine e correzione automatizzate.</span><span class="sxs-lookup"><span data-stu-id="508e8-515">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-516">Punteggio di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="508e8-516">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="508e8-517">Revisione delle simulazioni e delle esercitazioni (come gli scenari di esercitazione, il malware falso e le indagini automatizzate).</span><span class="sxs-lookup"><span data-stu-id="508e8-517">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="508e8-518">Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="508e8-518">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="508e8-519">Integrazione di Office 365 ATP con Microsoft Defender ATP.</span><span class="sxs-lookup"><span data-stu-id="508e8-519">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="508e8-520">Procedure dettagliate nel portale di Microsoft Defender Security Center.</span><span class="sxs-lookup"><span data-stu-id="508e8-520">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="508e8-521">I sistemi operativi seguenti:</span><span class="sxs-lookup"><span data-stu-id="508e8-521">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="508e8-522">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-522">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-523">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="508e8-523">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-524">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="508e8-524">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-525">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="508e8-525">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-526">Windows Server Semi-Annual Channel (SAC) versione 1803.</span><span class="sxs-lookup"><span data-stu-id="508e8-526">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-527">versioni macOS 10,13, 10,14 e 10,15.</span><span class="sxs-lookup"><span data-stu-id="508e8-527">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="508e8-528">
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft endpoint Configuration Manager (versione 2002 o superiore).</span><span class="sxs-lookup"><span data-stu-id="508e8-528">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="508e8-529"></li>
</ul>

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-529"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="508e8-530">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="508e8-530">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="508e8-531">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="508e8-531">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="508e8-532">Gestione continua e risposta alle minacce.</span><span class="sxs-lookup"><span data-stu-id="508e8-532">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="508e8-533">Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:</span><span class="sxs-lookup"><span data-stu-id="508e8-533">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="508e8-534">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="508e8-534">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-535">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="508e8-535">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-536">Linux.</span><span class="sxs-lookup"><span data-stu-id="508e8-536">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-537">Dispositivi mobili (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="508e8-537">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="508e8-538">Onboarding e configurazione del server:</span><span class="sxs-lookup"><span data-stu-id="508e8-538">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="508e8-539">Configurazione di un server proxy per le comunicazioni offline.</span><span class="sxs-lookup"><span data-stu-id="508e8-539">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-540">Configurazione di pacchetti di distribuzione di Configuration Manager nelle versioni e nelle varianti di gestione della configurazione.</span><span class="sxs-lookup"><span data-stu-id="508e8-540">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-541">Onboarding servers to Azure Security Center.</span><span class="sxs-lookup"><span data-stu-id="508e8-541">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-542">Server non gestiti da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="508e8-542">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="508e8-543">onboarding e configurazione di macOS:</span><span class="sxs-lookup"><span data-stu-id="508e8-543">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="508e8-544">Distribuzione manuale basata su Intune.</span><span class="sxs-lookup"><span data-stu-id="508e8-544">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-545">Distribuzione basata su GRAFP.</span><span class="sxs-lookup"><span data-stu-id="508e8-545">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="508e8-546">Altre distribuzioni basate su prodotto di gestione dei dispositivi mobili (MDM).</span><span class="sxs-lookup"><span data-stu-id="508e8-546">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-547">Distribuzione manuale.</span><span class="sxs-lookup"><span data-stu-id="508e8-547">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="508e8-548">Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:</span><span class="sxs-lookup"><span data-stu-id="508e8-548">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="508e8-549">Isolamento basato su hardware.</span><span class="sxs-lookup"><span data-stu-id="508e8-549">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-550">Controllo app.</span><span class="sxs-lookup"><span data-stu-id="508e8-550">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-551">Protezione dagli exploit.</span><span class="sxs-lookup"><span data-stu-id="508e8-551">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-552">Firewall di rete.</span><span class="sxs-lookup"><span data-stu-id="508e8-552">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="508e8-553">Iscrizione o configurazione di Microsoft Threat Experts.</span><span class="sxs-lookup"><span data-stu-id="508e8-553">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="508e8-554">Configurazione o formazione per la revisione delle API o delle informazioni di sicurezza e delle connessioni di gestione eventi (SIEM).</span><span class="sxs-lookup"><span data-stu-id="508e8-554">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="508e8-555">Iscrizione o configurazione di Microsoft Threat Protection (MTP).</span><span class="sxs-lookup"><span data-stu-id="508e8-555">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="508e8-556">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="508e8-556">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="508e8-557">Formazione o indicazioni su come usare o creare query Kusto.</span><span class="sxs-lookup"><span data-stu-id="508e8-557">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="508e8-558">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="508e8-558">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="508e8-559">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="508e8-559">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="508e8-560"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-560"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="508e8-561"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-561"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="508e8-562"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-562"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="508e8-563"><strong>Desktop virtuale Windows</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-563"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="508e8-564">Vengono fornite indicazioni per la distribuzione per l'onboarding su Windows Virtual Desktop (un servizio di virtualizzazione per desktop e app).</span><span class="sxs-lookup"><span data-stu-id="508e8-564">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="508e8-565">Windows Virtual Desktop si avvale dell'esperienza multisessione di Windows 10 ed è ottimizzato per le app Microsoft 365 per Enterprise con la sicurezza integrata e la gestione di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="508e8-565">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="508e8-566">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="508e8-566">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="508e8-567">Distribuzione dell'ambiente desktop virtuale di Windows con le app di Windows 10 Enterprise Multi-Session e Microsoft 365 per l'organizzazione con quanto segue:</span><span class="sxs-lookup"><span data-stu-id="508e8-567">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="508e8-568">Immagine di Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="508e8-568">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="508e8-569">Immagine condivisa.</span><span class="sxs-lookup"><span data-stu-id="508e8-569">Shared image.</span></span></li>
<li><span data-ttu-id="508e8-570">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="508e8-570">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="508e8-571">Configurazione di FSLogix:</span><span class="sxs-lookup"><span data-stu-id="508e8-571">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="508e8-572">Distribuzione dell'agente di FSLogix con il contenitore di profili.</span><span class="sxs-lookup"><span data-stu-id="508e8-572">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="508e8-573">Distribuzione dell'agente FSLogix con il contenitore di Office.</span><span class="sxs-lookup"><span data-stu-id="508e8-573">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="508e8-574">Configurazione della cartella FSLogix con le esclusioni di contenuto.</span><span class="sxs-lookup"><span data-stu-id="508e8-574">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="508e8-575">Distribuzione di Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="508e8-575">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="508e8-576">Distribuzione di Microsoft teams.</span><span class="sxs-lookup"><span data-stu-id="508e8-576">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="508e8-577">Connessione mediante client desktop virtuali di Windows.</span><span class="sxs-lookup"><span data-stu-id="508e8-577">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="508e8-578">

<strong>L'ambito seguente è esterno</strong>
</span><span class="sxs-lookup"><span data-stu-id="508e8-578">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="508e8-579">Gestione dei progetti della distribuzione di Windows Virtual Desktop del cliente.</span><span class="sxs-lookup"><span data-stu-id="508e8-579">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="508e8-580">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="508e8-580">On-site support.</span></span></li>
<li><span data-ttu-id="508e8-581">Virtualizzazione e distribuzione di app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="508e8-581">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="508e8-582">Immagini personalizzate.</span><span class="sxs-lookup"><span data-stu-id="508e8-582">Custom images.</span></span></li>
<li><span data-ttu-id="508e8-583">Migrazioni e scenari che coinvolgono VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="508e8-583">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="508e8-584">Scenari di Linux.</span><span class="sxs-lookup"><span data-stu-id="508e8-584">Linux scenarios.</span></span></li>
<li><span data-ttu-id="508e8-585">Conversione o migrazione dei profili utente.</span><span class="sxs-lookup"><span data-stu-id="508e8-585">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="508e8-586">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="508e8-586">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="508e8-587">È consigliabile che siano già presenti le operazioni seguenti:</span><span class="sxs-lookup"><span data-stu-id="508e8-587">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="508e8-588"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisiti relativi alle licenze Desktop virtuali di Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-588"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="508e8-589">Rete di Azure:</span><span class="sxs-lookup"><span data-stu-id="508e8-589">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="508e8-590">Creazione e subnetting della rete virtuale (rete virtuale).</span><span class="sxs-lookup"><span data-stu-id="508e8-590">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="508e8-591">Firewall e gruppi di sicurezza di rete.</span><span class="sxs-lookup"><span data-stu-id="508e8-591">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="508e8-592">VPN e ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="508e8-592">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="508e8-593">Routing in Azure da locale.</span><span class="sxs-lookup"><span data-stu-id="508e8-593">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="508e8-594">Regole del firewall per consentire la connettività a desktop virtuale di Windows.</span><span class="sxs-lookup"><span data-stu-id="508e8-594">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="508e8-595">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> client desktop remoto supportati</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-595">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="508e8-596">Installazione generale di Azure AD:</span><span class="sxs-lookup"><span data-stu-id="508e8-596">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="508e8-597">Strategia <i>di identità (è possibile utilizzare solo una delle tre opzioni seguenti):</i>
</span><span class="sxs-lookup"><span data-stu-id="508e8-597">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="508e8-598">Active Directory con Azure AD Connect in Azure.</span><span class="sxs-lookup"><span data-stu-id="508e8-598">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="508e8-599">Active Directory con Azure AD Connect in locale tramite VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="508e8-599">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="508e8-600">Servizi di dominio Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="508e8-600">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="508e8-601">App Assure</span><span class="sxs-lookup"><span data-stu-id="508e8-601">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="508e8-602"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-602"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="508e8-603"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-603"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="508e8-604"><strong>Prodotti supportati</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-604"><strong>Supported products</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-605"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-605"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="508e8-606">App assure è un servizio studiato per risolvere i problemi relativi alla compatibilità delle app Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="508e8-606">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="508e8-607">Quando si richiede il servizio app assure, è possibile collaborare con l'utente per risolvere i problemi di app validi senza costi aggiuntivi per l'utente con un abbonamento idoneo.</span><span class="sxs-lookup"><span data-stu-id="508e8-607">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="508e8-608">Vengono inoltre fornite indicazioni per i clienti che affrontano i problemi di compatibilità durante la distribuzione di desktop virtuali di Windows e del nuovo Microsoft Edge e offrono ogni ragionevole sforzo per risolvere i problemi di compatibilità.</span><span class="sxs-lookup"><span data-stu-id="508e8-608">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and the new Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="508e8-609">Viene fornita assistenza per la correzione per le app distribuite nei prodotti Microsoft seguenti:</span><span class="sxs-lookup"><span data-stu-id="508e8-609">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="508e8-610"><strong>Windows 10 </strong> (compresi i dispositivi arm64)</span><span class="sxs-lookup"><span data-stu-id="508e8-610"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="508e8-611"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="508e8-611"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="508e8-612"><strong>La nuova Microsoft Edge-</strong> Per informazioni sulle linee guida sulla distribuzione, vedere <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge Channels</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-612"><strong>The new Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="508e8-613">Desktop virtuale di <strong>Windows</strong> - Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">che cos'è Windows Virtual Desktop?</a> e <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">domande frequenti su Windows 10 Enterprise Multi-Session</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-613"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="508e8-614">

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-614">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="508e8-p134">Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro di distribuzione desktop</a>. Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito <a href="https://go.microsoft.com/fwlink/?linkid=2053818">modulo</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-p134">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="508e8-618">Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="508e8-618">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="508e8-619">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-619">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="508e8-620">Servizi di sola creazione di pacchetti di app.</span><span class="sxs-lookup"><span data-stu-id="508e8-620">App packaging-only services.</span></span> <span data-ttu-id="508e8-621">Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.</span><span class="sxs-lookup"><span data-stu-id="508e8-621">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="508e8-622">

<strong>Responsabilità del cliente:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-622">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="508e8-623">Creazione di un inventario delle app.</span><span class="sxs-lookup"><span data-stu-id="508e8-623">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="508e8-624">Convalida di tali app in Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="508e8-624">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="508e8-625">
<strong>Nota:</strong>  Microsoft non è in grado di apportare modifiche al codice sorgente.</span><span class="sxs-lookup"><span data-stu-id="508e8-625">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="508e8-626">Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente.</span><span class="sxs-lookup"><span data-stu-id="508e8-626">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="508e8-627">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="508e8-627">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="508e8-628"><strong>App di Windows 10 e Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="508e8-628"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="508e8-629">Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="508e8-629">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="508e8-630">
<strong>Windows 10 su ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="508e8-630">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="508e8-631">Le app che hanno lavorato su Windows 7, Office 2010 o versioni successive funzionano anche su app Windows 10 e Microsoft 365 nei dispositivi di ARM64.</span><span class="sxs-lookup"><span data-stu-id="508e8-631">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="508e8-632">
  <strong>Nota</strong> 
</span><span class="sxs-lookup"><span data-stu-id="508e8-632">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="508e8-633">l'emulazione x64 (64 bit) è disponibile in anteprima per i clienti che partecipano al <a href="https://insider.windows.com/">programma Windows Insider</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-633">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="508e8-634">Per i clienti non Windows insider su Windows 10 versione 2004 (o versioni successive), ARM64 Photoshop è supportato tramite <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL e OpenGL Compatibility Pack</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-634">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="508e8-635">I clienti del programma Windows Insider possono scaricare una versione Insider di OpenCL e OpenGL Compatibility Pack per l'utilizzo con altre app.</span><span class="sxs-lookup"><span data-stu-id="508e8-635">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="508e8-636">
<strong>Nuovo server perimetrale Microsoft</strong>
</span><span class="sxs-lookup"><span data-stu-id="508e8-636">
<strong>The new Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="508e8-637">Se le app o i siti Web sono compatibili con Internet Explorer 11, versioni supportate di Google Chrome o qualsiasi versione di Microsoft Edge, saranno compatibili anche con il nuovo Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="508e8-637">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with the new Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-638">Poiché il Web è in continua evoluzione, assicurarsi di esaminare l'elenco pubblicato delle <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">modifiche note sulla compatibilità dei siti per Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="508e8-638">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="508e8-639">
  <strong>Desktop virtuale di Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-639">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="508e8-640">Applicazioni virtualizzate che vengono eseguite su Windows Server Remote Desktop Session Host (RDSH) vengono eseguite anche nella multisessione di Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="508e8-640">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-641">Le app in esecuzione su qualsiasi ambiente Windows 7 o Windows 10 Virtual Desktop Infrastructure (VDI) vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte di Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="508e8-641">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-642">Le app che vengono eseguite su dispostivi client di Windows 7 o Windows 10, vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="508e8-642">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="508e8-643">
  <strong>Nota:</strong> Le esclusioni e limitazioni per la compatibilità tra più sessioni di Windows 10 Enterprise includono:</span><span class="sxs-lookup"><span data-stu-id="508e8-643">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="508e8-644">Reindirizzamento limitato dell'hardware.</span><span class="sxs-lookup"><span data-stu-id="508e8-644">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-645">Le app con uso intensivo di A/V possono essere eseguite a una capacità ridotta.</span><span class="sxs-lookup"><span data-stu-id="508e8-645">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="508e8-646">Le app a 16 bit non sono supportate per la versione Desktop virtuale Windows a 64 bit.</span><span class="sxs-lookup"><span data-stu-id="508e8-646">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a><span data-ttu-id="508e8-647">Il nuovo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="508e8-647">The new Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="508e8-648"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-648"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="508e8-649"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-649"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="508e8-650"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="508e8-650"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="508e8-651"><strong>Microsoft Edge</strong> (per i clienti di Windows 10 Enterprise)</span><span class="sxs-lookup"><span data-stu-id="508e8-651"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="508e8-652">Vengono fornite indicazioni per la distribuzione remota e assistenza per la compatibilità per: distribuzione del nuovo Microsoft Edge in Windows 10 Enterprise con Microsoft Endpoint Manager (Microsoft endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="508e8-652">We provide remote deployment guidance and compatibility assistance for: Deploying the new Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="508e8-653">Configurazione Microsoft Edge (mediante criteri di gruppo o di configurazione delle app di Intune e criteri app).</span><span class="sxs-lookup"><span data-stu-id="508e8-653">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="508e8-654">Inventariare l'elenco dei siti che possono richiedere l'utilizzo in modalità Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="508e8-654">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="508e8-655">Abilitazione della modalità Internet Explorer con l'elenco dei siti dell'organizzazione esistente.</span><span class="sxs-lookup"><span data-stu-id="508e8-655">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="508e8-656">Inoltre, se si dispone di un'app Web o di un sito che funziona con Internet Explorer o Google Chrome e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema senza costi aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="508e8-656">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="508e8-657">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">app assure</a> .</span><span class="sxs-lookup"><span data-stu-id="508e8-657">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="508e8-658">

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="508e8-658">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="508e8-659">Gestione dei progetti per la distribuzione di Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="508e8-659">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="508e8-660">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="508e8-660">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
