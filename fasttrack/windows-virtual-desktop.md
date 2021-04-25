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
description: FastTrack fornisce indicazioni sulla distribuzione di Desktop virtuale Windows per aiutarti a eseguire l'onboarding su questo desktop.
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996239"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="d41aa-103">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="d41aa-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d41aa-104"><strong>Servizio</strong></span><span class="sxs-lookup"><span data-stu-id="d41aa-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="d41aa-105"><strong>Dettagli guida FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="d41aa-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="d41aa-106"><strong>Aspettative sull'ambiente di origine</strong></span><span class="sxs-lookup"><span data-stu-id="d41aa-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d41aa-107">Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="d41aa-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="d41aa-108">FastTrack fornisce indicazioni per la distribuzione di Desktop virtuale Windows per facilitare l'onboarding di questo servizio di virtualizzazione desktop e app, sfruttando al contempo l'esperienza multi-sessione di Windows 10, ottimizzata per Microsoft 365 Apps for Enterprise con sicurezza e gestione integrate per Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="d41aa-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="d41aa-109">Si collabora con specialisti di FastTrack per:</span><span class="sxs-lookup"><span data-stu-id="d41aa-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="d41aa-110">Distribuire l'ambiente WVD con Windows 10 Enterprise multi-sessione + Microsoft 365 Apps for Enterprise usando quanto segue:</span><span class="sxs-lookup"><span data-stu-id="d41aa-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="d41aa-111">Immagine di Azure Marketplace</span><span class="sxs-lookup"><span data-stu-id="d41aa-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="d41aa-112">Immagine condivisa</span><span class="sxs-lookup"><span data-stu-id="d41aa-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="d41aa-113">Office Deployment Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="d41aa-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="d41aa-114">Configurare FSLogix</span><span class="sxs-lookup"><span data-stu-id="d41aa-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="d41aa-115">Distribuire l'agente FSLogix con il contenitore dei profili</span><span class="sxs-lookup"><span data-stu-id="d41aa-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="d41aa-116">Distribuire l'agente FSLogix con il contenitore di Office</span><span class="sxs-lookup"><span data-stu-id="d41aa-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="d41aa-117">Configurare la cartella FSLogix con esclusioni di contenuto</span><span class="sxs-lookup"><span data-stu-id="d41aa-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="d41aa-118">Distribuzione di Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="d41aa-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="d41aa-119">Distribuire Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="d41aa-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="d41aa-120">Connettersi tramite client Desktop virtuale Windows</span><span class="sxs-lookup"><span data-stu-id="d41aa-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="d41aa-121"><strong>L'ambito seguente non è disponibile</strong></span><span class="sxs-lookup"><span data-stu-id="d41aa-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="d41aa-122">Project management of the customer's Windows Virtual Desktop deployment.</span><span class="sxs-lookup"><span data-stu-id="d41aa-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="d41aa-123">Supporto nel sito.</span><span class="sxs-lookup"><span data-stu-id="d41aa-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="d41aa-124">Virtualizzazione/distribuzione di applicazioni di terze parti.</span><span class="sxs-lookup"><span data-stu-id="d41aa-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="d41aa-125">Immagini personalizzate.</span><span class="sxs-lookup"><span data-stu-id="d41aa-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="d41aa-126">Migrazioni e scenari che coinvolgono VMware e Citrix.</span><span class="sxs-lookup"><span data-stu-id="d41aa-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="d41aa-127">Scenari Linux.</span><span class="sxs-lookup"><span data-stu-id="d41aa-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="d41aa-128">Conversione o migrazione di profili utente.</span><span class="sxs-lookup"><span data-stu-id="d41aa-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="d41aa-129">Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</span><span class="sxs-lookup"><span data-stu-id="d41aa-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="d41aa-130">Dovresti già disporre di quanto segue:</span><span class="sxs-lookup"><span data-stu-id="d41aa-130">You should already have the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="d41aa-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Requisiti di licenza WVD</a></span><span class="sxs-lookup"><span data-stu-id="d41aa-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD Licensing Requirements</a></span></span></p></li>
<li><p><span data-ttu-id="d41aa-132">Rete di Azure:</span><span class="sxs-lookup"><span data-stu-id="d41aa-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="d41aa-133">Creazione VNET &amp; Subnetting</span><span class="sxs-lookup"><span data-stu-id="d41aa-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="d41aa-134">Firewall/Gruppi di sicurezza di rete</span><span class="sxs-lookup"><span data-stu-id="d41aa-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="d41aa-135">VPN / ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="d41aa-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="d41aa-136">Routing ad Azure da locale</span><span class="sxs-lookup"><span data-stu-id="d41aa-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="d41aa-137">Regole firewall per consentire la connettività a WVD</span><span class="sxs-lookup"><span data-stu-id="d41aa-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p><span data-ttu-id="d41aa-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Documentazione di riferimento</a></span><span class="sxs-lookup"><span data-stu-id="d41aa-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Docs Reference</a></span></span></p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="d41aa-139">Installazione generale di Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="d41aa-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="d41aa-140">Strategia di <strong>identità (selezionare SOLO 1 delle seguenti 3 opzioni)</strong></span><span class="sxs-lookup"><span data-stu-id="d41aa-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="d41aa-141">Active Directory con Azure AD Connect in Azure</span><span class="sxs-lookup"><span data-stu-id="d41aa-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="d41aa-142">Active Directory con Azure AD Connect on premise su VPN /ER</span><span class="sxs-lookup"><span data-stu-id="d41aa-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="d41aa-143">Servizi di dominio Active Directory</span><span class="sxs-lookup"><span data-stu-id="d41aa-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
