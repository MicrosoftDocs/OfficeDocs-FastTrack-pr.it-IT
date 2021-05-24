---
title: Desktop virtuale Windows
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack fornisce Windows guida alla distribuzione di Desktop virtuale per aiutarti a eseguire l'onboarding su questo desktop.
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592439"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="1b642-103">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="1b642-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="1b642-104"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="1b642-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="1b642-105"><strong>Dettagli guida FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="1b642-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="1b642-106"><strong>Aspettative sull'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="1b642-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="1b642-107">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="1b642-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="1b642-108">FastTrack fornisce indicazioni per la distribuzione di desktop virtuali Windows per facilitare l'onboarding di questo servizio di virtualizzazione desktop e app sfruttando al contempo l'esperienza multi-sessione di Windows 10, ottimizzata per Microsoft 365 Apps per Enterprise con sicurezza e gestione integrate per Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="1b642-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="1b642-109">Si collabora con specialisti di FastTrack per:</span><span class="sxs-lookup"><span data-stu-id="1b642-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="1b642-110">Distribuire l'ambiente WVD con Windows 10 Enterprise multi-sessione e Microsoft 365 Apps per Enterprise usando quanto segue:</span><span class="sxs-lookup"><span data-stu-id="1b642-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="1b642-111">Immagine di Azure Marketplace</span><span class="sxs-lookup"><span data-stu-id="1b642-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="1b642-112">Immagine condivisa</span><span class="sxs-lookup"><span data-stu-id="1b642-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="1b642-113">Office Distribuzione Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="1b642-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="1b642-114">Configurare FSLogix</span><span class="sxs-lookup"><span data-stu-id="1b642-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="1b642-115">Distribuire l'agente FSLogix con il contenitore dei profili</span><span class="sxs-lookup"><span data-stu-id="1b642-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="1b642-116">Distribuire l'agente FSLogix con Office contenitore</span><span class="sxs-lookup"><span data-stu-id="1b642-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="1b642-117">Configurare la cartella FSLogix con esclusioni di contenuto</span><span class="sxs-lookup"><span data-stu-id="1b642-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="1b642-118">Distribuzione di Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="1b642-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="1b642-119">Distribuire Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="1b642-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="1b642-120">Connessione l'Windows client desktop virtuale</span><span class="sxs-lookup"><span data-stu-id="1b642-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="1b642-121"><strong>L'ambito seguente non è disponibile</strong></span><span class="sxs-lookup"><span data-stu-id="1b642-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="1b642-122">Project della distribuzione di Desktop virtuale Windows del cliente.</span><span class="sxs-lookup"><span data-stu-id="1b642-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="1b642-123">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="1b642-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="1b642-124">Virtualizzazione/distribuzione di applicazioni di terze parti.</span><span class="sxs-lookup"><span data-stu-id="1b642-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="1b642-125">Immagini personalizzate.</span><span class="sxs-lookup"><span data-stu-id="1b642-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="1b642-126">Migrazioni e scenari che coinvolgono VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="1b642-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="1b642-127">Scenari Linux.</span><span class="sxs-lookup"><span data-stu-id="1b642-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="1b642-128">Conversione o migrazione di profili utente.</span><span class="sxs-lookup"><span data-stu-id="1b642-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="1b642-129">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="1b642-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="1b642-130">Dovresti già disporre di quanto segue:</span><span class="sxs-lookup"><span data-stu-id="1b642-130">You should already have the following:</span></span></p>
<ul>
<li><p>[<span data-ttu-id="1b642-131">Requisiti di licenza WVD</span><span class="sxs-lookup"><span data-stu-id="1b642-131">WVD Licensing Requirements</span></span>](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p><span data-ttu-id="1b642-132">Rete di Azure:</span><span class="sxs-lookup"><span data-stu-id="1b642-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="1b642-133">Creazione VNET &amp; Subnetting</span><span class="sxs-lookup"><span data-stu-id="1b642-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="1b642-134">Firewall/Gruppi di sicurezza di rete</span><span class="sxs-lookup"><span data-stu-id="1b642-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="1b642-135">VPN / ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="1b642-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="1b642-136">Routing ad Azure da locale</span><span class="sxs-lookup"><span data-stu-id="1b642-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="1b642-137">Regole firewall per consentire la connettività a WVD</span><span class="sxs-lookup"><span data-stu-id="1b642-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p>[<span data-ttu-id="1b642-138">Documentazione di riferimento</span><span class="sxs-lookup"><span data-stu-id="1b642-138">Docs Reference</span></span>](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="1b642-139">Azure Active Directory Configurazione generale</span><span class="sxs-lookup"><span data-stu-id="1b642-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="1b642-140">Strategia di <strong>identità (selezionare SOLO 1 delle seguenti 3 opzioni)</strong></span><span class="sxs-lookup"><span data-stu-id="1b642-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="1b642-141">Active Directory con Azure AD Connessione in Azure</span><span class="sxs-lookup"><span data-stu-id="1b642-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="1b642-142">Active Directory con Azure AD Connessione locale su VPN /ER</span><span class="sxs-lookup"><span data-stu-id="1b642-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="1b642-143">Servizi di dominio Active Directory</span><span class="sxs-lookup"><span data-stu-id="1b642-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
