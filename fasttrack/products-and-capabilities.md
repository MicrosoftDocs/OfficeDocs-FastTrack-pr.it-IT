---
title: Prodotti e funzionalità
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: In questo argomento sono inclusi i dettagli sugli scenari di carico di lavoro supportati da FastTrack e le aspettative dell'ambiente di origine necessarie prima di iniziare. In base alla configurazione corrente, è possibile creare un piano di correzione che consentirà all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding di esito positivo.
ms.openlocfilehash: a3477be6958dea88874bbc042445bbc693c10ffb
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 09/30/2020
ms.locfileid: "48320032"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="8cc4e-104">Prodotti e funzionalità</span><span class="sxs-lookup"><span data-stu-id="8cc4e-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="8cc4e-105">Servizi e scenari supportati da FastTrack</span><span class="sxs-lookup"><span data-stu-id="8cc4e-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="8cc4e-106">In questo argomento sono inclusi i dettagli sugli scenari di carico di lavoro supportati da FastTrack e le aspettative dell'ambiente di origine necessarie prima di iniziare.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="8cc4e-107">In base alla configurazione corrente, è possibile creare un piano di correzione che consentirà all'ambiente di origine di soddisfare i requisiti minimi per l'onboarding di esito positivo.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="8cc4e-108">FastTrack fornisce indicazioni utili per la prima volta con le funzionalità di base (comuni per tutti i servizi online Microsoft) e quindi con l'onboarding di ogni servizio idoneo:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="8cc4e-109">Generale</span><span class="sxs-lookup"><span data-stu-id="8cc4e-109">General</span></span>](#general)
  - [<span data-ttu-id="8cc4e-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="8cc4e-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="8cc4e-111">Sicurezza delle & Enterprise Mobility</span><span class="sxs-lookup"><span data-stu-id="8cc4e-111">Enterprise Mobility & Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="8cc4e-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="8cc4e-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="8cc4e-113">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="8cc4e-113">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="8cc4e-114">App Assure</span><span class="sxs-lookup"><span data-stu-id="8cc4e-114">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="8cc4e-115">Il nuovo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="8cc4e-115">The new Microsoft Edge</span></span>](#the-new-microsoft-edge)

> [!NOTE]
> <span data-ttu-id="8cc4e-116">Per informazioni sulle aspettative dell'ambiente di origine per Office 365 US Government, vedere [source Environment aspettations for office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-116">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="8cc4e-117">Generale</span><span class="sxs-lookup"><span data-stu-id="8cc4e-117">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8cc4e-118"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-118"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="8cc4e-119"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-119"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="8cc4e-120"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-120"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8cc4e-121"><strong>Onboarding di base</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-121"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-122">Vengono fornite istruzioni Remote sull'onboarding di base, che include il provisioning dei servizi, il tenant e l'integrazione delle identità.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-122">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="8cc4e-123">Sono inoltre disponibili passaggi per fornire una base per i servizi di onboarding quali Exchange Online, SharePoint Online e Microsoft teams, tra cui una <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussione sulla sicurezza, la connettività di rete e la conformità</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-123">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="8cc4e-124">L'onboarding per uno o più servizi può iniziare al termine dell'onboarding di base.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-124">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="8cc4e-125"></li>
</ul>  

<strong> Integrazione dell'identità </strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-125"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="8cc4e-126">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-126">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="8cc4e-127">Preparazione delle identità di Active Directory locale per la sincronizzazione di Azure Active Directory (Azure AD), inclusa l'installazione e la configurazione di Azure AD Connect (Single-o multi-Forest) e delle licenze (incluse le licenze basate su gruppo).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-127">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="8cc4e-128">Creazione di identità cloud inclusa l'importazione in blocco e la gestione delle licenze, incluso l'utilizzo delle licenze basate su gruppo.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-128">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="8cc4e-129">Scelta e attivazione del metodo di autenticazione corretto per il percorso Cloud, la sincronizzazione hash delle password, l'autenticazione pass-through o Active Directory Federation Services (AD FS).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-129">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="8cc4e-130">Abilitazione di ADFS per i clienti con una singola foresta di Active Directory e le identità sincronizzate con lo strumento Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-130">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="8cc4e-131">Per questo è necessario Windows Server 2012 R2 Active Directory Federation Services 2,0 o versione successiva.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-131">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="8cc4e-132">Migrazione dell'autenticazione da AD FS ad Azure ad utilizzando la sincronizzazione hash delle password o l'autenticazione pass-through.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-132">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="8cc4e-133">Migrazione delle app preintegrate (come le app di Azure AD Gallery software-as-a-Service (SaaS)) da AD FS ad Azure ad per Single Sign-on (SSO).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-133">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="8cc4e-134">Abilitazione delle integrazioni delle app SaaS con SSO dalla raccolta di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-134">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="8cc4e-135">Abilitazione del provisioning automatico degli utenti per le app SaaS preintegrate elencate nell' <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">elenco app Integration tutorial</a> (solo per le app SaaS di Azure ad Gallery e per il provisioning in uscita solo).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-135">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="8cc4e-136"><strong>Abilitazione della rete </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="8cc4e-136"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="8cc4e-137">Nell'ambito del vantaggio FastTrack, si consiglia di eseguire le procedure consigliate per la connessione a servizi cloud per garantire i massimi livelli di prestazioni di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-137">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="8cc4e-138"><strong>Foreste di Active Directory</strong> Il livello di foresta funzionale è impostato su Windows Server 2003 e versioni successive, con la seguente configurazione della foresta:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-138"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-139">Una foresta unica di Active Directory.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-139">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-140">Una singola foresta account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-140">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-141">Più foreste account di Active Directory e topologie di foreste di risorse (Exchange e/o Lync 2010, Lync 2013 o Skype for Business).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-141">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-142">Più foreste account di Active Directory con una delle foreste in posizione centrale nella foresta account di Active Directory contenente Exchange e/o Lync 2010, Lync 2013 o Skype for Business.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-142">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-143">Più foreste account di Active Directory, ognuna con la propria organizzazione di Exchange.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-143">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-144">Attività necessarie per la configurazione tenant e l'integrazione con Azure Active Directory, se necessario.   </span><span class="sxs-lookup"><span data-stu-id="8cc4e-144">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.   </span></span></li>
</ul><span data-ttu-id="8cc4e-145">
  <strong>Importante</strong>  </span><span class="sxs-lookup"><span data-stu-id="8cc4e-145">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="8cc4e-146">Per gli scenari a più foreste di Active Directory, se Lync 2010, Lync 2013 o Skype for business è distribuito, deve essere distribuito nella stessa foresta di Active Directory di Exchange.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-146">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-147">Quando si implementano più foreste di Active Directory con più organizzazioni di Exchange in una configurazione multi-ibrida di Exchange, gli spazi dei nomi UPN (Shared User Principal Name) tra le foreste di origine non sono supportati.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-147">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="8cc4e-148">Gli spazi dei nomi SMTP primari tra organizzazioni di Exchange devono essere separati.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-148">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="8cc4e-149">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=845444">Distribuzioni ibride con più insiemi di strutture di Active Directory</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-149">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-150">Per tutte le configurazioni di più insiemi di strutture, la distribuzione di Active Directory Federation Services (AD FS) non rientra nell'ambito.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-150">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="8cc4e-151">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-151">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-152"><strong>Microsoft 365 Apps</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-152"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-153">Vengono fornite indicazioni per la distribuzione remota per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-153">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-154">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-154">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-155">Assegnazione dei contratti di licenza con l'utente finale e di licenze basate sul dispositivo utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-155">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-156">Installare Microsoft 365 Apps dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-156">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-157">Installazione delle app di Office Mobile (ad esempio Outlook Mobile, Word Mobile, Excel Mobile e PowerPoint Mobile) sui dispositivi iOS o Android.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-157">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-158">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-158">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-159">Selezione e configurazione di un'installazione locale o cloud.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-159">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-160">Creazione del codice XML di configurazione dello Strumento di distribuzione di Office con lo Strumento di personalizzazione di Office o del codice XML nativo per configurare il pacchetto di distribuzione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-160">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-161">Distribuzione con Microsoft Endpoint Configuration Manager, che include una guida per la creazione del pacchetto di Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-161">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="8cc4e-162">Inoltre, se si dispone di una macro o di un componente aggiuntivo che ha avuto esito positivo con le versioni precedenti di Office e si verificano problemi di compatibilità, vengono fornite indicazioni per correggere il problema di compatibilità senza costi aggiuntivi tramite il programma app assure.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-162">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="8cc4e-163">Per ulteriori informazioni, vedere la sezione <strong>assure app</strong> di <a href="#windows-10">Windows 10</a> .</span><span class="sxs-lookup"><span data-stu-id="8cc4e-163">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="8cc4e-164">Il software client online deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-164">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8cc4e-165"><strong>Integrità della rete</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-165"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-166">Vengono fornite istruzioni Remote per ottenere e interpretare i dati chiave di connettività di rete dall'ambiente che illustrano la modalità di allineamento dei siti <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">dell'organizzazione ai principi di connettività di rete di</a>Microsoft.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-166">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="8cc4e-167">Questo evidenzia il Punteggio di rete che incide direttamente sulla velocità di migrazione, l'esperienza utente, le prestazioni del servizio e l'affidabilità.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-167">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="8cc4e-168">È inoltre possibile eseguire le operazioni di correzione evidenziate da questi dati per migliorare il Punteggio di rete.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-168">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="8cc4e-169">Accesso all'interfaccia di amministrazione di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-169">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-170">Sono necessarie le versioni aggiornate delle app Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-170">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-171">Servizi di posizione abilitati <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">in base alle raccomandazioni relative alle prestazioni di rete nell'interfaccia di amministrazione di Microsoft 365 (Preview)</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-171">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="8cc4e-172">Office 365</span><span class="sxs-lookup"><span data-stu-id="8cc4e-172">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8cc4e-173"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-173"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="8cc4e-174"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-174"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="8cc4e-175"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-175"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8cc4e-176"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-176"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-177">Per Exchange Online, è possibile eseguire la procedura per preparare l'organizzazione all'utilizzo della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-177">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="8cc4e-178">I passaggi esatti dipendono dall'ambiente di origine e dai piani di migrazione della posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-178">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="8cc4e-179">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-179">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-180">Configurare le funzionalità di Exchange Online Protection (EOP) per tutti i domini abilitati alla posta elettronica convalidati in Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-180">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-181">Puntamento dei record MX (mail Exchange) a Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-181">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-182">Configurazione della funzionalità ATP di Office 365 se fa parte del servizio di sottoscrizione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-182">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="8cc4e-183">Per ulteriori informazioni, vedere la sezione <strong>Office 365 Advanced Threat Protection</strong> di questa tabella.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-183">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-p113">Configurare la funzionalità di prevenzione della perdita dei dati (DLP) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="8cc4e-p114">Configurare Office 365 Message Encryption (OME) per tutti i domini abilitati per la posta elettronica convalidati in Office 365 se rientra nel servizio in abbonamento. Questa operazione viene eseguita dopo aver impostato i record MX in modo che puntino a Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="8cc4e-188">
  <strong>Nota:</strong> Il servizio di replica delle cassette postali (MRS) tenta di migrare i messaggi di posta elettronica IRM (Information Rights Managed) dalla cassetta postale locale alla corrispondente cassetta postale di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-188">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="8cc4e-189">La possibilità di leggere i contenuti protetti dopo la migrazione dipende dal fatto che il cliente esegua il mapping e copi i modelli di Active Directory Rights Managed Services (AD RMS) in Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-189">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="8cc4e-190">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-190">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-191">Configurazione di DNS, tra cui il servizio di individuazione automatica, il servizio di gestione dei messaggi (SPF), la posta elettronica identificata di DomainKeys (DKIM), l'autenticazione del messaggio basata sul dominio, la creazione di report e la conformità (DMARC) e i record MX (se necessario).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-191">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-192">Configurare il flusso di posta elettronica tra l'ambiente di messaggistica di origine e Exchange Online (in base alle esigenze).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-192">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-193">Eseguire la migrazione della posta dall'ambiente di messaggistica di origine a Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-193">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-194">Configurazione di client delle cassette postali (Outlook per Windows, Outlook sul web e Outlook per iOS e Android).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-194">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="8cc4e-195">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="8cc4e-195">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="8cc4e-196">Per informazioni sull'utilizzo del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-196">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="8cc4e-197">L'ambiente di origine deve disporre di uno dei livelli minimi seguenti:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-197">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-198">Una o più organizzazioni di Exchange con Exchange Server 2003 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-198">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-199">Un singolo ambiente di posta elettronica abilitato per il protocollo IMAP.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-199">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-200">Un ambiente singolo G Suite (soltanto Gmail, contatti e Calendar).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-200">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-201">Per informazioni su multi-Geo capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=872776">multi-Geo capabilities in Exchange Online</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-201">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="8cc4e-202">Il software client online come Project per Office 365, Outlook per Windows, Outlook per iOS e Android, il client di sincronizzazione di OneDrive for business, il desktop Power BI e Skype for business devono essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 Office</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-202">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-203"><strong>Microsoft Information Governance</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-203"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-204">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-204">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-205">Governance delle informazioni.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-205">Information governance.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-206">Etichette e criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-206">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-207">Gestione dei record.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-207">Records management.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-208">Criteri di eliminazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-208">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-209">Conformità delle comunicazioni.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-209">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-210">Gestione dei rischi Insider.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-210">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-211">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-211">Advanced eDiscovery.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="8cc4e-212">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-212">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8cc4e-213"><strong>Microsoft Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-213"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-214">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-214">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-215">Classificazione dei dati.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-215">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-216">Tipi di informazioni sensibili.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-216">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-217">Creare etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-217">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-218">Applicare etichette di riservatezza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-218">Applying Sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-219">Etichettatura unificata.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-219">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-220">Classificatori sottoponibili a formazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-220">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-221">Conoscere i dati tramite Esplora contenuto ed Esplora attività.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-221">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-222">Pubblicare etichette con criteri (manuale e automatico).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-222">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-223">Creare criteri di prevenzione della perdita dei dati (DLP) per chat e canali di Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-223">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="8cc4e-224">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-224">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-225"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-225"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-226">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-226">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-227">Conferma dei requisiti minimi nei gruppi di Exchange Online, SharePoint Online, Office 365 e Azure AD per il supporto dei team.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-227">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-228">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-228">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-229">Configurazione di DNS.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-229">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-230">Conferma dell'abilitazione di Teams nel tenant Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-230">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-231">Abilitazione o disabilitazione delle licenze utente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-231">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-232">Valutazione della rete per i team:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-232">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-233">Controlli di porta ed endpoint.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-233">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-234">Controlli sulla qualità della connessione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-234">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-235">Stime sulla larghezza di banda.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-235">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="8cc4e-236">Configurazione dei criteri delle app per i team (teams Web App, teams desktop app e teams for iOS and Android app).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-236">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="8cc4e-237">Se applicabile, vengono fornite anche indicazioni per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-237">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-238">Dispositivi della sala Microsoft teams:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-238">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="8cc4e-239">Creazione di account online necessari per i dispositivi di telefonia e sala riunioni supportati, elencati nel <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Catalogo dispositivi teams</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-239">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-240">Assistenza remota con la configurazione sul fianco del servizio dei dispositivi Microsoft teams Rooms certificati.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-240">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-241">Abilitazione dell'audioconferenza:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-241">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-242">Configurazione aziendale delle impostazioni predefinite del bridge per conferenze.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-242">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-243">Assegnazione di bridge per conferenze agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-243">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="8cc4e-244">Sistema telefonico:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-244">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-245">Configurazione aziendale delle impostazioni predefinite vocali cloud.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-245">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-246">Guida ai piani di chiamata (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">mercati disponibili</a>):</span><span class="sxs-lookup"><span data-stu-id="8cc4e-246">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-247">Assegnazione di numeri agli utenti con licenza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-247">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-248">Guida alla portabilità del numero locale tramite UI fino a 999.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-248">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-249">Supporto RS per la richiesta di servizio di portabilità del numero locale superiore a 999.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-249">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-250">Guida per il routing diretto:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-250">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-251">Linee guida per l'installazione dell'organizzazione per la progettazione di routing diretto di scenari ospitati da partner o scenari distribuiti dal cliente per un massimo di 10 siti.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-251">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="8cc4e-252">Verifica della configurazione del session border controller (SBC).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-252">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="8cc4e-253">Assistenza remota con la configurazione del dial plan.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-253">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="8cc4e-254">Configurazione della route vocale.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-254">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="8cc4e-255">Bypass multimediale e ottimizzazione dei supporti locali.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-255">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-256">Abilitazione degli eventi live in Teams.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-256">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-257">Configurazione dell'organizzazione e integrazione in Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-257">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-258">Linee guida per la transizione da Skype for business a teams.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-258">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="8cc4e-259">Identità abilitate in Azure Active Directory per Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-259">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-260">Utenti abilitati per SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-260">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-261">Le cassette postali di Exchange sono presenti (online e in locale in una configurazione ibrida di Exchange).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-261">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-262">Abilitato per i gruppi di Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-262">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="8cc4e-263">
  <strong>Nota:</strong>   Se gli utenti non sono assegnati e abilitati con le licenze di SharePoint Online, non avranno l'archiviazione di OneDrive for business in Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-263">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="8cc4e-264">La condivisione dei file continua a funzionare nei canali, ma gli utenti non possono condividere file in chat senza OneDrive for Business Storage in Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-264">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="8cc4e-265">I team non supportano SharePoint locale.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-265">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="8cc4e-266">
  <strong>Nota:</strong>   Lo stato ideale è che tutti gli utenti dispongano delle cassette postali in Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-266">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="8cc4e-267">Gli utenti con cassette postali ospitate in locale devono avere le rispettive identità sincronizzate con la directory di Office 365 tramite Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-267">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="8cc4e-268">Per questi clienti ibridi di Exchange, se la cassetta postale dell'utente è in locale, l'utente non è in grado di aggiungere o configurare i connettori.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-268">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="8cc4e-269">I programmi di installazione per i client desktop di Microsoft teams Windows e Mac possono essere scaricati da  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> .</span><span class="sxs-lookup"><span data-stu-id="8cc4e-269">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8cc4e-270"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-270"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-271">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-271">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-272">Abilitazione di Collegamenti sicuri, Allegati sicuri e anti-phishing.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-272">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-273">Configurazione di automazione, analisi e risposta.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-273">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-274">Uso del simulatore di attacchi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-274">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-275">Creazione di report e analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-275">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="8cc4e-276">Oltre alla parte di <strong>onboarding di base</strong> in <a href="#general">generale</a>, non esistono requisiti minimi di sistema.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-276">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-277"><strong>Outlook per iOS e Android</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-277"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-278">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-278">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-279">Download di Outlook per iOS e Android tramite l'Apple App Store e Google Play.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-279">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-280">Configurazione degli account e accesso alla cassetta postale di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-280">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-281">Protezione di Outlook Mobile (vedere <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">protezione di Outlook per iOS e Android in Exchange Online</a> per ulteriori informazioni).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-281">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="8cc4e-282">Identità abilitate in Azure Active Directory per Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-282">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-283">Exchange Online configurato e licenze assegnate.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-283">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8cc4e-284"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-284"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-285">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-285">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-286">Assegnare licenze di Power BI.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-286">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-287">Distribuire l'app Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-287">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="8cc4e-288">Il software client online come Power BI desktop deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-288">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-289"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-289"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-290">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-291">Verificare la funzionalità di base di SharePoint sulla quale fa affidamento Project Online.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-291">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-292">Aggiungere il servizio Project Online al tenant (inclusa l'aggiunta di sottoscrizioni per gli utenti).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-292">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-293">Configurare il pool di risorse organizzazione (ERP).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-293">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-294">Creare il primo progetto.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-294">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="8cc4e-295">Il software client online come Project per Office 365 deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-295">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8cc4e-296"><strong>Project Online Professional e Premium</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-296"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-297">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-297">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-298">Risoluzione dei problemi di implementazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-298">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-299">Assegnare i contratti di licenza con l'utente finale utilizzando l'interfaccia di amministrazione di Microsoft 365 e Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-299">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-300">Installare Client desktop di Project Online dal portale di Office 365 tramite la tecnologia A portata di clic.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-300">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-301">Configurare le impostazioni di aggiornamento con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-301">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-302">Configurare un unico server di distribuzione nel sito per Client desktop di Project Online, includendo una guida per la creazione del file configuration.xml da usare con lo strumento di distribuzione di Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-302">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-303">Connettere Client desktop di Project Online a Project Online Professional o Project Online Premium.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-303">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="8cc4e-304">Il software client online come Project per Office 365 deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-304">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-305"><strong>SharePoint Online e OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-305"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-306">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-306">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-307">Configurazione DNS.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-307">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-308">Configurazione delle porte del firewall.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-308">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-309">Provisioning di utenti e licenze.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-309">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="8cc4e-310">Abilitazione alla creazione di siti per l'amministratore di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-310">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="8cc4e-311">Pianificazione delle raccolte di siti.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-311">Planning site collections.</span></span></li>
<li><span data-ttu-id="8cc4e-312">Protezione del contenuto e gestione delle autorizzazioni.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-312">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="8cc4e-313">Configurazione delle caratteristiche di SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-313">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="8cc4e-314">Configurazione delle funzionalità dell'ambiente ibrido di SharePoint, come la ricerca ibrida, i siti ibridi, la tassonomia ibrida, i tipi di contenuto, la creazione siti in modalità self-service ibrida (solo SharePoint Server 2013), l'icona di avvio delle app estesa, OneDrive for Business ibrido e i siti extranet.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-314">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-315">Approccio di migrazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-315">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="8cc4e-316">Vengono fornite indicazioni aggiuntive per OneDrive for business a seconda della versione di SharePoint, ad esempio:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-316">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-317">Identificare le opzioni di integrazione e la revisione dell'infrastruttura di rete e della larghezza di banda in locale e online.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-317">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-318">Installazione di SharePoint Online 2013 SP1 (se applicabile), pianificazione e implementazione dei requisiti di sincronizzazione e identità e identificazione del client di sincronizzazione di OneDrive for business.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-318">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-319">Pianificazione e implementazione di una singola implementazione per tutti gli utenti (o per una distribuzione in fasi).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-319">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-320">Assegnazione delle licenze, Reindirizzamento dei siti personali e delle raccolte documenti personale a Office 365 (applicabile a SharePoint Online 2013), impostazione di gruppi di destinatari per controllare l'accesso a OneDrive (applicabile a SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-320">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="8cc4e-321">Reindirizzamento o spostamento di cartelle note in OneDrive.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-321">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="8cc4e-322">Distribuzione della sincronizzazione client di OneDrive for business.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-322">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="8cc4e-323">
  <strong>Migrazione dei dati</strong>  </span><span class="sxs-lookup"><span data-stu-id="8cc4e-323">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="8cc4e-324">Per informazioni sull'utilizzo del vantaggio FastTrack per la migrazione dei dati a Office 365, vedere <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-324">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="8cc4e-325"><strong>Per l'ambiente ibrido di SharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-325"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="8cc4e-326">La configurazione ibrida di SharePoint include la configurazione della ricerca ibrida, dei siti, della tassonomia, dei tipi di contenuto, di OneDrive for business, di un'applicazione di avvio delle app estesa, di siti Extranet e della creazione di siti in modalità self-service connessi da un singolo ambiente SharePoint Online di destinazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-326">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="8cc4e-327">
  <strong>Nota:</strong> La creazione di siti in modalità self-service non è in ambito con i server locali che eseguono SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-327">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="8cc4e-328">Per abilitare l'ambiente ibrido di SharePoint, è necessario disporre di uno dei seguenti ambienti locali di SharePoint Server: 2013, 2016 o 2019.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-328">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="8cc4e-329">
  <strong>Nota:</strong> L'aggiornamento degli ambienti di SharePoint locali a SharePoint Server non è incluso nell'ambito.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-329">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="8cc4e-330">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-330">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="8cc4e-331">Per ulteriori informazioni, vedere <a href="https://go.microsoft.com/fwlink/?linkid=853548">livelli di aggiornamento pubblico minimi per le funzionalità ibride di SharePoint</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="8cc4e-331">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="8cc4e-332">
  <strong>Nota:</strong> Per informazioni su multi-Geo capabilities, vedere <a href="https://go.microsoft.com/fwlink/?linkid=831056">multi-Geo capabilities in OneDrive e SharePoint online in Office 365</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="8cc4e-332">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-333"><strong>Yammer Enterprise</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-333"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="8cc4e-334">Vengono fornite istruzioni Remote per abilitare il servizio Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-334">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="8cc4e-335">Il software client online deve essere a un livello minimo, come definito nei <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requisiti di sistema per Microsoft 365 e Office</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-335">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="8cc4e-336">Sicurezza delle & Enterprise Mobility</span><span class="sxs-lookup"><span data-stu-id="8cc4e-336">Enterprise Mobility & Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-337"><strong>Azure Active Directory (Azure AD) e Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-337"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-338">Vengono fornite istruzioni Remote per la protezione delle identità cloud per gli scenari seguenti.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-338">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="8cc4e-339">

<strong>Infrastruttura di Fondazione sicura</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-339">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="8cc4e-340">La configurazione e l'abilitazione dell'autenticazione avanzata per le identità, tra cui la protezione con l'autenticazione a più fattori di Azure (solo cloud), l'app Microsoft Authenticator e la registrazione combinata per Azure Mae e la reimpostazione della password self-service (SSPR).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-340">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-341">Per i clienti non Azure AD Premium, vengono fornite indicazioni per proteggere le identità utilizzando le impostazioni predefinite per la sicurezza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-341">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-342">Per i clienti di Azure AD Premium, vengono fornite indicazioni per proteggere le identità con accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-342">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-343">Rilevamento e blocco dell'utilizzo di password deboli con la protezione delle password di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-343">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-344">Protezione dell'accesso remoto alle app Web locali con proxy di applicazione Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-344">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-345">Abilitazione del rilevamento e del monitoraggio basati sui rischi con la protezione delle identità di Azure.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-345">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-346">Abilitazione di una schermata di accesso personalizzata, tra cui logo, testo e immagini con personalizzazione personalizzata.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-346">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-347">Condivisione sicura delle app e dei servizi con gli utenti guest che utilizzano Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-347">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-348">Gestione dell'accesso per gli amministratori di Office 365 mediante ruoli amministrativi basati sul controllo dell'accesso basato sui ruoli (RBAC) e per ridurre il numero di account amministratore con privilegi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-348">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-349">Configuring Hybrid Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-349">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-350">Configurazione di Azure AD join.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-350">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="8cc4e-351">
  
<strong>Monitoraggio e creazione di report</strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-351">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="8cc4e-352">Abilitazione del monitoraggio remoto per ADFS, Azure AD Connect e controller di dominio con Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-352">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="8cc4e-353">
  
<strong>Governance</strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-353">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="8cc4e-354">Gestione dell'identità di Azure AD e del ciclo di vita di accesso in scala con la gestione dei diritti di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-354">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="8cc4e-355">Gestire le appartenenze ai gruppi di Azure AD, l'accesso alle app Enterprise e le assegnazioni di ruolo con le recensioni di Azure AD Access.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-355">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-356">Revisione delle condizioni di utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-356">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-357">Gestione e controllo dell'accesso agli account amministratore privilegiati con Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-357">Managing and controling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="8cc4e-358">
  
<strong>Automazione ed efficienza </strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-358">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="8cc4e-359">Abilitazione di Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-359">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="8cc4e-360">Consentendo agli utenti di creare e gestire i propri gruppi di sicurezza cloud o di Office 365 con la gestione di gruppi self-service di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-360">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-361">Gestione dell'accesso delegato alle app Enterprise con la gestione dei gruppi delegati AD Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-361">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-362">Abilitazione di gruppi dinamici di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-362">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-363">Organizzazione delle app nel portale My Apps using Collections.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-363">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="8cc4e-364">Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, inclusa la correzione di problemi identificati che impediscono l'integrazione con Azure AD e le funzionalità di Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-364">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8cc4e-365"><strong>Azure Information Protection (P2 o EMS E5)</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-365"><strong>Azure Information Protection (P2 or EMS E5)</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-366">Vengono fornite indicazioni su come:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-366">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-367">Attivare e configurare il tenant.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-367">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-368">Creare e configurare etichette e criteri.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-368">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-369">Applicare la protezione delle informazioni ai documenti.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-369">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-370">Classificare ed etichettare automaticamente le informazioni nelle app di Office, come Word, PowerPoint, Excel e Outlook, che eseguono Windows e con il client di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-370">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-371">Utilizzare file inattivi con lo scanner di Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-371">Use files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-372">Controllare i messaggi di posta elettronica in transito con regole del flussi di posta di Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-372">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="8cc4e-373">Vengono inoltre fornite indicazioni per l'applicazione della protezione tramite Microsoft Azure Rights Management Services (Azure RMS), la crittografia dei messaggi di Office 365 (OME) e la prevenzione della perdita di dati (DLP).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-373">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="8cc4e-374">È necessario già:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-374">You should already:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-375">Utilizzo di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-375">Use Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-376">Utilizzare Windows o iOS (altri sistemi operativi non sono inclusi nell'ambito).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-376">Use either Windows or iOS (other operating systems are out of scope).</span></span>  
  </ul><span data-ttu-id="8cc4e-377">
<strong>Nota</strong>: i computer e i dispositivi mobili devono essere eseguiti in un <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">sistema operativo</a> che supporta Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-377">
<strong>Note</strong>: Computers and mobile devices must run on an <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">operating system</a> that supports Azure Information Protection.</span></span>  
<li>  <span data-ttu-id="8cc4e-378">Disporre dei percorsi di condivisione file principali.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-378">Have your main file share locations.</span></span>  </li><span data-ttu-id="8cc4e-379">
<strong>Nota</strong>: il supporto ibrido richiede il connettore ad RMS.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-379">
<strong>Note</strong>: Hybrid support requires the AD RMS connector.</span></span> 
<li>  <span data-ttu-id="8cc4e-380">Avere una tassonomia di classificazione approvata.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-380">Have an approved classification taxonomy.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-381">Comprendere eventuali restrizioni normative per la gestione delle chiavi protette.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-381">Understand any regulatory restrictions for your protected key management.</span></span>  </li><span data-ttu-id="8cc4e-382">
</ul>
  
<strong>Scanner di Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-382">
</ul>
  
<strong>Azure Information Protection scanner</strong></span></span>  
  
<span data-ttu-id="8cc4e-383">È necessario già:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-383">You should already:</span></span>  
<ul>
<li>  <span data-ttu-id="8cc4e-384">Utilizzare Windows Server 2012 R2 o Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-384">Use Windows Server 2012 R2 or Windows Server 2016.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-385">Disporre di una connessione Internet.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-385">Have an internet connection.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-386">Microsoft SQL Server 2012 e versioni successive in un'istanza locale o remota.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-386">Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-387">Disporre di un account di servizio creato per Active Directory locale e sincronizzato con Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-387">Have a service account created for your on-premises Active Directory and synchronized with Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-388">Sono stati scaricati AzInfoProtection.exe.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-388">Have downloaded AzInfoProtection.exe.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-389">Sono state configurate etichette per la classificazione/protezione automatica.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-389">Have labels configured for Automatic Classification/Protection.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-390"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-390"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-391">Vengono fornite indicazioni su come preparare l'utilizzo di Intune come provider di gestione dei dispositivi mobili basato sul cloud (MDM) e mobile app Management (MAM) per le app e i dispositivi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-391">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="8cc4e-392">I passaggi esatti dipendono dall'ambiente di origine e sono basati sulle esigenze di gestione di dispositivi mobili e app per dispositivi mobili.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-392">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="8cc4e-393">I passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-393">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-394">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-394">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-395">Configurazione delle identità per l'utilizzo da parte di Intune mediante l'uso di Active Directory o identità cloud locali (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-395">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-396">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-396">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-397">Configurazione dell'autorità MDM, in base alle esigenze di gestione, tra cui:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-397">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-398">Impostazione di Intune come autorità di MDM quando Intune è l'unica soluzione di MDM.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-398">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-399">Fornire le indicazioni di MDM per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-399">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-400">Configurare i gruppi di test da usare per convalidare i criteri di gestione MDM.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-400">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-401">Configurare criteri e servizi di gestione MDM come:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-401">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-402">Distribuzione di app per ogni piattaforma supportata tramite collegamenti Web o Deep Links.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-402">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-403">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-403">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-404">Distribuzione di profili di posta elettronica, reti wireless e VPN se si dispone di un'autorità di certificazione, di una rete wireless o di un'infrastruttura VPN esistente nell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-404">Deployment of email, wireless networks, and VPN)profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-405">Connessione al data warehouse di Intune.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-405">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-406">Integrare Intune con:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-406">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-407">Visualizzatore team per assistenza remota (è necessario un abbonamento a un visualizzatore di Team).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-407">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-408">Soluzioni partner per la difesa di minacce mobili (MTD) (è necessaria una sottoscrizione di MTD).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-408">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-409">Una soluzione Telecom Expense Management (è richiesta una sottoscrizione di una soluzione per la gestione delle spese Telecom).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-409">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-410">Microsoft Defender ATP (sono necessarie licenze Windows E5 o Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-410">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-411">Registrare i dispositivi di ogni piattaforma supportata in Intune.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-411">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-412">Fornire indicazioni sulla protezione delle app:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-412">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-413">Configurare criteri di protezione delle app per ogni piattaforma supportata.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-413">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-414">Configurazione dei criteri di accesso condizionale per le app gestite.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-414">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-415">Indirizzare i gruppi di utenti corretti con i criteri MAM precedentemente citati.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-415">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-416">Utilizzo di report sull'utilizzo delle app gestite.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-416">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-417">Fornire indicazioni sulla migrazione dalla gestione dei PC legacy a Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-417">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="8cc4e-418">
  <strong>Nota</strong>: la gestione dei PC legacy non è più supportata dal 15 ottobre 2020 e versioni successive.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-418">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="8cc4e-419"></li>
</ul>
  
<strong>Collegamento tramite cloud</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-419"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="8cc4e-420">Si consiglia di preparare gli ambienti di gestione della configurazione esistenti tramite cloud con Intune.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-420">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="8cc4e-421">I passaggi esatti dipendono dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-421">The exact steps depend on your source environment.</span></span> <span data-ttu-id="8cc4e-422">Questi passaggi possono includere:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-422">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="8cc4e-423">Licenze per gli utenti finali.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-423">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-424">Configurare le identità utilizzate da Intune, sfruttando Active Directory locale e le identità cloud.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-424">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-425">Aggiungere utenti all'abbonamento a Intune, definire i ruoli di amministratore IT e creare gruppi di utenti e dispositivi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-425">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-426">Fornire linee guida per la configurazione di un join ibrido di Azure AD.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-426">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-427">Fornire indicazioni sulla configurazione di Azure AD per la registrazione automatica MDM.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-427">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-428">Offrire indicazioni su come configurare il gateway di gestione cloud.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-428">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-429">Configurare i carichi di lavoro supportati che si desidera passare a Intune.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-429">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-430">Installare il client Configuration Manager nei dispositivi registrati di Intune.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-430">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="8cc4e-431"><strong>Distribuire Outlook Mobile per iOS e Android in modo sicuro</strong> È possibile fornire assistenza per la distribuzione sicura di Outlook Mobile per iOS e Android nell'organizzazione per garantire che gli utenti dispongano di tutte le app necessarie installate.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-431"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="8cc4e-432">La procedura per distribuire in modo sicuro Outlook Mobile per iOS e Android con Intune dipende dall'ambiente di origine.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-432">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="8cc4e-433">Può includere:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-433">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-434">Scaricare le app di Outlook per iOS e Android, Microsoft Authenticator e il portale aziendale di Intune tramite l'App Store di Apple o Google Play Store.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-434">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-435">Fornire indicazioni sulla configurazione:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-435">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-436">Distribuzione di Outlook per iOS e Android, Microsoft Authenticator e Intune per le app del portale aziendale con Intune.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-436">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-437">Criteri di protezione delle app.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-437">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-438">Criteri di accesso condizionale.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-438">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-439">Criteri di configurazione dell'app.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-439">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="8cc4e-440"><strong>Nota</strong>: FastTrack non supporta la protezione di Outlook per iOS e Android con i criteri cassetta postale dei dispositivi mobili di Exchange.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-440"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="8cc4e-441">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-441">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="8cc4e-442">Gli amministratori IT devono disporre dell'autorità di certificazione, della rete wireless e delle infrastrutture VPN esistenti che già operano nei rispettivi ambienti di produzione durante la pianificazione della distribuzione della rete wireless e dei profili VPN con Intune.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-442">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="8cc4e-443"><strong>Nota</strong>: il vantaggio del servizio di FastTrack non include assistenza per la configurazione o la configurazione di autorità di certificazione, reti wireless, infrastrutture VPN o certificati push di Apple MDM per Intune.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-443"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="8cc4e-444"><strong>Nota</strong>: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-444"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="8cc4e-445">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-445">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="8cc4e-446"><strong>Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-446"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="8cc4e-447"><strong>Nota</strong>: viene fornita assistenza per l'integrazione di Intune con Microsoft Defender ATP e la creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-447"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="8cc4e-448">Non viene fornita assistenza per l'acquisto, la gestione delle licenze o l'attivazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-448">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="8cc4e-449">Rivolgersi a un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-449">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="8cc4e-450"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-450"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="8cc4e-451">Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-451">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
<span data-ttu-id="8cc4e-452"><strong>Distribuire Outlook per iOS e Android in modo sicuro con Intune </strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-452"><strong>Deploy Outlook for iOS and Android securely with Intune </strong></span></span>  
<ul>
<li>  <span data-ttu-id="8cc4e-453">Identità degli utenti abilitate in Azure Active Directory per Office 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-453">User identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-454">Exchange Online o Hybrid Exchange configurati con le licenze utente assegnate.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-454">Exchange Online or hybrid Exchange configured with user licenses assigned.</span></span>  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="8cc4e-455">Windows 10</span><span class="sxs-lookup"><span data-stu-id="8cc4e-455">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8cc4e-456"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-456"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="8cc4e-457"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-457"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="8cc4e-458"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-458"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8cc4e-459"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-459"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-460">Vengono fornite indicazioni per l'aggiornamento da Windows 7 Professional e Windows 8,1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-460">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="8cc4e-461">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-461">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-462">Informazioni sull'intenzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-462">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-463">Valutazione dell'ambiente di origine e dei requisiti (verificare che Microsoft endpoint Configuration Manager venga aggiornato al livello richiesto per supportare la distribuzione di Windows 10).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-463">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-464">Distribuzione delle app di Windows 10 Enterprise e Microsoft 365 tramite Microsoft endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-464">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-465">Opzioni di raccomandazione per valutare le app di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-465">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-466">Abilitazione dell'utilizzo di analisi desktop e linee guida tramite la creazione di un piano di distribuzione di analisi desktop.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-466">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-467">Microsoft 365 Apps Compatibility assessment by leveraging The Office 365 prontezza dashboard in Configuration Manager o with the stand-alone Pronation Toolkit for Office Plus Assistance Deploying Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-467">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-468">Creazione di un elenco di controllo di correzione su cosa è necessario fare per riportare l'ambiente di origine ai requisiti minimi per una distribuzione corretta.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-468">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-469">Fornire indicazioni sull'aggiornamento per i dispositivi esistenti a Windows 10 Enterprise, se soddisfano i requisiti hardware necessari per il dispositivo.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-469">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-470">Fornire indicazioni sull'aggiornamento per supportare il movimento di distribuzione esistente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-470">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="8cc4e-471">FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-471">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="8cc4e-472">Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-472">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-473">Distribuzione di app Microsoft 365 mediante Configuration Manager nell'ambito della distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-473">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="8cc4e-474">Fornire indicazioni per aiutare l'organizzazione a rimanere sempre aggiornati con le app Windows 10 Enterprise e Microsoft 365 utilizzando l'ambiente di gestione della configurazione esistente o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-474">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="8cc4e-475">
  <strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-475">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="8cc4e-476">Aggiornamento di Configuration Manager al Current Branch.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-476">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-477">Creazione di immagini personalizzate per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-477">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-478">Creazione e supporto degli script di distribuzione per la distribuzione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-478">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-479">Conversione di un sistema di Windows 10 dal BIOS a Unified Extensible Firmware Interface (UEFI).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-479">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-480">Abilitare le funzionalità di sicurezza di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-480">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-481">Configurazione di Windows Deployment Services (WDS) per il boot di Preboot Execution Environment (PXE).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-481">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-482">Uso di Microsoft Deployment Toolkit (MDT) per acquisire e distribuire immagini di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-482">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-483">Uso dell’Utilità di migrazione dello stato utente (USMT).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-483">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="8cc4e-484">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-484">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="8cc4e-485">Per l'aggiornamento del PC, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-485">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-486">Sistema operativo di origine: Windows 7 Enterprise o Professional, Windows 8,1 Enterprise o Professional.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-486">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-487">Dispositivi: fattore di forma desktop, notebook o tablet.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-487">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-488">Sistema operativo di destinazione: Window 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-488">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="8cc4e-489">Per l'aggiornamento dell'infrastruttura, è necessario soddisfare i requisiti seguenti:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-489">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-490">Gestione configurazione Microsoft endpoint.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-490">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-491">La versione di Configuration Manager deve essere supportata dalla versione di destinazione di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-491">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="8cc4e-492">Per ulteriori informazioni, vedere la tabella di supporto di Configuration Manager al <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">supporto di Windows 10 in Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-492">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="8cc4e-493"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-493"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-494">Microsoft Defender Advanced Threat Protection (ATP) è una piattaforma progettata per consentire alle reti aziendali di bloccare, rilevare, analizzare e rispondere a minacce avanzate.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-494">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="8cc4e-495">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-495">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-496">Distribuzione delle tecnologie per la protezione degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-496">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-497">Configurazione di Endpoint Protection e dei profili di restrizione del dispositivo.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-497">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-498">Valutare la versione del sistema operativo e la gestione dei dispositivi (tra cui Intune, Microsoft endpoint Configuration Manager, oggetti Criteri di gruppo (GPO) e configurazioni di terze parti), nonché lo stato di Windows Defender AV Services o di altri software di sicurezza di endpoint.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-498">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-499">Valutazione dello stato dei servizi AV di Windows o di altri software di sicurezza di endpoint.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-499">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-500">Valutazione di proxy e firewall che limitano il traffico di rete.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-500">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-501">Abilitazione del servizio Microsoft Defender ATP spiegando come distribuire un profilo di agente ATP utilizzando un endpoint di bordo.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-501">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-502">Guida alla distribuzione, assistenza alla configurazione e istruzione su:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-502">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="8cc4e-503">Gestione delle minacce e delle vulnerabilità.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-503">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-504">Riduzione della superficie di attacco.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-504">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-505">Protezione di nuova generazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-505">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-506">Rilevamento e risposta degli endpoint.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-506">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-507">Indagine e correzione automatizzate.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-507">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-508">Punteggio di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-508">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-509">Revisione delle simulazioni e delle esercitazioni (come gli scenari di esercitazione, il malware falso e le indagini automatizzate).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-509">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-510">Panoramica delle caratteristiche della creazione di report e dell’analisi delle minacce.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-510">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-511">Integrazione di Office 365 ATP con Microsoft Defender ATP.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-511">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-512">Procedure dettagliate nel portale di Microsoft Defender Security Center.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-512">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-513">I sistemi operativi seguenti:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-513">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="8cc4e-514">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-514">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-515">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-515">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-516">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-516">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-517">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-517">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-518">Canale semestrale di Windows Server (SAC) versione 1803.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-518">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-519">versioni macOS 10,13, 10,14 e 10,15.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-519">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="8cc4e-520">
<strong>Nota:</strong> Tutte le versioni di Windows Server devono essere gestite dalla versione più recente di System Center Configuration Manager 2012 (versioni 1012 R2, 1511 o 1602) o Microsoft endpoint Configuration Manager (versione 2002 o superiore).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-520">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="8cc4e-521"></li>
</ul>

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-521"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="8cc4e-522">Gestione dei progetti delle attività di correzione del cliente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-522">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-523">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-523">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-524">Gestione continua e risposta alle minacce.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-524">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-525">Onboarding o configurazione per gli agenti Microsoft Defender ATP seguenti:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-525">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="8cc4e-526">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-526">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-527">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-527">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-528">Linux.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-528">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-529">Dispositivi mobili (Android e iOS).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-529">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-530">Onboarding e configurazione del server:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-530">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="8cc4e-531">Configurazione di un server proxy per le comunicazioni offline.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-531">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-532">Configurazione di pacchetti di distribuzione di Configuration Manager nelle versioni e nelle varianti di gestione della configurazione.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-532">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-533">Onboarding servers to Azure Security Center.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-533">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-534">Server non gestiti da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-534">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-535">onboarding e configurazione di macOS:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-535">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="8cc4e-536">Distribuzione manuale basata su Intune.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-536">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-537">Distribuzione basata su GRAFP.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-537">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="8cc4e-538">Altre distribuzioni basate su prodotto di gestione dei dispositivi mobili (MDM).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-538">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-539">Distribuzione manuale.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-539">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-540">Configurazione delle funzionalità di riduzione della superficie d'attacco seguenti:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-540">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="8cc4e-541">Isolamento basato su hardware.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-541">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-542">Controllo app.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-542">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-543">Protezione dagli exploit.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-543">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-544">Firewall di rete.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-544">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="8cc4e-545">Iscrizione o configurazione di Microsoft Threat Experts.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-545">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-546">Configurazione o formazione per la revisione delle API o delle informazioni di sicurezza e delle connessioni di gestione eventi (SIEM).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-546">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-547">Iscrizione o configurazione di Microsoft Threat Protection (MTP).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-547">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-548">Formazione o indicazioni sulla ricerca avanzata.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-548">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-549">Formazione o indicazioni su come usare o creare query Kusto.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-549">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="8cc4e-550">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-550">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="8cc4e-551">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="8cc4e-551">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8cc4e-552"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-552"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="8cc4e-553"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-553"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="8cc4e-554"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-554"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8cc4e-555"><strong>Desktop virtuale Windows</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-555"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="8cc4e-556">Vengono fornite indicazioni per la distribuzione per l'onboarding su Windows Virtual Desktop (un servizio di virtualizzazione per desktop e app).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-556">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="8cc4e-557">Windows Virtual Desktop si avvale dell'esperienza multisessione di Windows 10 ed è ottimizzato per le app Microsoft 365 per Enterprise con la sicurezza integrata e la gestione di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-557">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="8cc4e-558">Sono disponibili linee guida Remote per:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-558">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="8cc4e-559">Distribuzione dell'ambiente desktop virtuale di Windows con le app di Windows 10 Enterprise Multi-Session e Microsoft 365 per l'organizzazione con quanto segue:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-559">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="8cc4e-560">Immagine di Azure Marketplace.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-560">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="8cc4e-561">Immagine condivisa.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-561">Shared image.</span></span></li>
<li><span data-ttu-id="8cc4e-562">Office Deployment Toolkit (ODT).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-562">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="8cc4e-563">Configurazione di FSLogix:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-563">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="8cc4e-564">Distribuzione dell'agente di FSLogix con il contenitore di profili.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-564">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="8cc4e-565">Distribuzione dell'agente FSLogix con il contenitore di Office.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-565">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="8cc4e-566">Configurazione della cartella FSLogix con le esclusioni di contenuto.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-566">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="8cc4e-567">Distribuzione di Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-567">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="8cc4e-568">Distribuzione di Microsoft teams.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-568">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="8cc4e-569">Connessione mediante client desktop virtuali di Windows.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-569">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="8cc4e-570">

<strong>L'ambito seguente è esterno</strong>
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-570">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="8cc4e-571">Gestione dei progetti della distribuzione di Windows Virtual Desktop del cliente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-571">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="8cc4e-572">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-572">On-site support.</span></span></li>
<li><span data-ttu-id="8cc4e-573">Virtualizzazione e distribuzione di app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-573">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="8cc4e-574">Immagini personalizzate.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-574">Custom images.</span></span></li>
<li><span data-ttu-id="8cc4e-575">Migrazioni e scenari che coinvolgono VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-575">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="8cc4e-576">Scenari di Linux.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-576">Linux scenarios.</span></span></li>
<li><span data-ttu-id="8cc4e-577">Conversione o migrazione dei profili utente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-577">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="8cc4e-578">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a>   per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="8cc4e-579">È consigliabile che siano già presenti le operazioni seguenti:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-579">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="8cc4e-580"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisiti relativi alle licenze Desktop virtuali di Windows</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-580"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="8cc4e-581">Rete di Azure:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-581">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="8cc4e-582">Creazione e subnetting della rete virtuale (rete virtuale).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-582">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="8cc4e-583">Firewall e gruppi di sicurezza di rete.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-583">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="8cc4e-584">VPN e ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-584">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="8cc4e-585">Routing in Azure da locale.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-585">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="8cc4e-586">Regole del firewall per consentire la connettività a desktop virtuale di Windows.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-586">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="8cc4e-587">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> client desktop remoto supportati</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-587">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="8cc4e-588">Installazione generale di Azure AD:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-588">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="8cc4e-589">Strategia <i>di identità (è possibile utilizzare solo una delle tre opzioni seguenti):</i>
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-589">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="8cc4e-590">Active Directory con Azure AD Connect in Azure.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-590">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="8cc4e-591">Active Directory con Azure AD Connect in locale tramite VPN o ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-591">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="8cc4e-592">Servizi di dominio Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-592">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="8cc4e-593">App Assure</span><span class="sxs-lookup"><span data-stu-id="8cc4e-593">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8cc4e-594"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-594"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="8cc4e-595"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-595"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="8cc4e-596"><strong>Prodotti supportati</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-596"><strong>Supported products</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-597"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-597"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="8cc4e-598">App assure è un servizio studiato per risolvere i problemi relativi alla compatibilità delle app Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-598">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="8cc4e-599">Quando si richiede il servizio app assure, è possibile collaborare con l'utente per risolvere i problemi di app validi senza costi aggiuntivi per l'utente con un abbonamento idoneo.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-599">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="8cc4e-600">Vengono inoltre fornite indicazioni per i clienti che affrontano i problemi di compatibilità durante la distribuzione di desktop virtuali di Windows e del nuovo Microsoft Edge e offrono ogni ragionevole sforzo per risolvere i problemi di compatibilità.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-600">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and the new Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="8cc4e-601">Viene fornita assistenza per la correzione per le app distribuite nei prodotti Microsoft seguenti:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-601">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="8cc4e-602"><strong>Windows 10 </strong> (compresi i dispositivi arm64)</span><span class="sxs-lookup"><span data-stu-id="8cc4e-602"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="8cc4e-603"><strong>Microsoft 365 Apps</strong>  </span><span class="sxs-lookup"><span data-stu-id="8cc4e-603"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="8cc4e-604"><strong>La nuova Microsoft Edge-</strong> Per informazioni sulle linee guida sulla distribuzione, vedere <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge Channels</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-604"><strong>The new Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-605">Desktop virtuale di <strong>Windows</strong> - Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">che cos'è Windows Virtual Desktop?</a> e <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">domande frequenti su Windows 10 Enterprise Multi-Session</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-605"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="8cc4e-606">

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-606">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="8cc4e-p132">Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Centro di distribuzione desktop</a>. Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito <a href="https://go.microsoft.com/fwlink/?linkid=2053818">modulo</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-p132">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="8cc4e-610">Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-610">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="8cc4e-611">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-611">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="8cc4e-612">Servizi di sola creazione di pacchetti di app.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-612">App packaging-only services.</span></span> <span data-ttu-id="8cc4e-613">Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-613">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="8cc4e-614">

<strong>Responsabilità del cliente:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-614">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="8cc4e-615">Creazione di un inventario delle app.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-615">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="8cc4e-616">Convalida di tali app in Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-616">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="8cc4e-617">
<strong>Nota:</strong>  Microsoft non è in grado di apportare modifiche al codice sorgente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-617">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="8cc4e-618">Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-618">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="8cc4e-619">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft</a> per assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-619">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="8cc4e-620"><strong>App di Windows 10 e Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-620"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="8cc4e-621">Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-621">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="8cc4e-622">
<strong>Windows 10 su ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-622">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="8cc4e-623">Le app che hanno lavorato su Windows 7, Office 2010 o versioni successive funzionano con Windows 10 e Microsoft 365 Apps nei dispositivi di ARM64.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-623">Apps that worked on Windows 7, Office 2010, or later versions work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="8cc4e-624">
  <strong>Nota:</strong> Le esclusioni e limitazioni di Windows 10 su ARM includono:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-624">
  <strong>Note:</strong> Windows 10 on ARM exclusions and limitations include:</span></span>
<ul>
<li>  
 <span data-ttu-id="8cc4e-625">App che si basano su driver software che non sono compatibili con ARM.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-625">Apps that rely on software drivers that aren’t compatible in ARM.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-626">App che utilizzano OpenGL o OpenCL.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-626">Apps that use OpenGL or OpenCL.</span></span>   
  </li>
<li>  
  <span data-ttu-id="8cc4e-627">Le app sono disponibili solo in 64 bit (x64).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-627">Apps only available in 64-bit (x64).</span></span>  
  </li>
</ul><span data-ttu-id="8cc4e-628">
<strong>Nuovo server perimetrale Microsoft</strong>
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-628">
<strong>The new Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="8cc4e-629">Se le app o i siti Web sono compatibili con Internet Explorer 11, versioni supportate di Google Chrome o qualsiasi versione di Microsoft Edge, saranno compatibili anche con il nuovo Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-629">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with the new Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-630">Poiché il Web è in continua evoluzione, assicurarsi di esaminare l'elenco pubblicato delle <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">modifiche note sulla compatibilità dei siti per Microsoft Edge</a>.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-630">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="8cc4e-631">
  <strong>Desktop virtuale di Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-631">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="8cc4e-632">Applicazioni virtualizzate che vengono eseguite su Windows Server Remote Desktop Session Host (RDSH) vengono eseguite anche nella multisessione di Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-632">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-633">Le app in esecuzione su qualsiasi ambiente Windows 7 o Windows 10 Virtual Desktop Infrastructure (VDI) vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte di Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-633">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-634">Le app che vengono eseguite su dispostivi client di Windows 7 o Windows 10, vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte del Desktop virtuale Windows.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-634">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="8cc4e-635">
  <strong>Nota:</strong> Le esclusioni e limitazioni per la compatibilità tra più sessioni di Windows 10 Enterprise includono:</span><span class="sxs-lookup"><span data-stu-id="8cc4e-635">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="8cc4e-636">Reindirizzamento limitato dell'hardware.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-636">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-637">Le app con uso intensivo di A/V possono essere eseguite a una capacità ridotta.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-637">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="8cc4e-638">Le app a 16 bit non sono supportate per la versione Desktop virtuale Windows a 64 bit.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-638">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a><span data-ttu-id="8cc4e-639">Il nuovo Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="8cc4e-639">The new Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8cc4e-640"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-640"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="8cc4e-641"><strong>Informazioni dettagliate sull'orientamento di FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-641"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="8cc4e-642"><strong>Aspettative dell'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="8cc4e-642"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
</tr>
<tr class="even">
<td><span data-ttu-id="8cc4e-643"><strong>Microsoft Edge</strong> (per i clienti di Windows 10 Enterprise)</span><span class="sxs-lookup"><span data-stu-id="8cc4e-643"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="8cc4e-644">Vengono fornite indicazioni per la distribuzione remota e assistenza per la compatibilità per: distribuzione del nuovo Microsoft Edge in Windows 10 Enterprise con Microsoft Endpoint Manager (Microsoft endpoint Configuration Manager o Intune).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-644">We provide remote deployment guidance and compatibility assistance for: Deploying the new Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-645">Configurazione Microsoft Edge (mediante criteri di gruppo o di configurazione delle app di Intune e criteri app).</span><span class="sxs-lookup"><span data-stu-id="8cc4e-645">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-646">Inventariare l'elenco dei siti che possono richiedere l'utilizzo in modalità Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-646">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="8cc4e-647">Abilitazione della modalità Internet Explorer con l'elenco dei siti dell'organizzazione esistente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-647">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="8cc4e-648">Inoltre, se si dispone di un'app Web o di un sito che funziona con Internet Explorer o Google Chrome e si verificano problemi di compatibilità, vengono fornite indicazioni per risolvere il problema senza costi aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-648">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="8cc4e-649">Per ulteriori informazioni, vedere <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">app assure</a> .</span><span class="sxs-lookup"><span data-stu-id="8cc4e-649">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="8cc4e-650">

<strong>L'ambito seguente è esterno </strong>  
</span><span class="sxs-lookup"><span data-stu-id="8cc4e-650">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="8cc4e-651">Gestione dei progetti per la distribuzione di Microsoft Edge del cliente.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-651">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="8cc4e-652">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="8cc4e-652">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
