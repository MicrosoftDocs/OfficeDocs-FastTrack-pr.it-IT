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
# <a name="windows-virtual-desktop"></a>Desktop virtuale Windows

<table>
<thead>
<tr class="header">
<th><strong>Servizio</strong></th>
<th><strong>Dettagli guida FastTrack</strong></th>
<th><strong>Aspettative sull'ambiente di origine</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Desktop virtuale Windows</td>
<td><p>FastTrack fornisce indicazioni per la distribuzione di desktop virtuali Windows per facilitare l'onboarding di questo servizio di virtualizzazione desktop e app sfruttando al contempo l'esperienza multi-sessione di Windows 10, ottimizzata per Microsoft 365 Apps per Enterprise con sicurezza e gestione integrate per Microsoft 365.</p>
<p>Si collabora con specialisti di FastTrack per:</p>
<ul>
<li><p>Distribuire l'ambiente WVD con Windows 10 Enterprise multi-sessione e Microsoft 365 Apps per Enterprise usando quanto segue:</p>
<ul>
<li><p>Immagine di Azure Marketplace</p></li>
<li><p>Immagine condivisa</p></li>
<li><p>Office Distribuzione Toolkit (ODT)</p></li>
</ul></li>
<li><p>Configurare FSLogix</p>
<ul>
<li><p>Distribuire l'agente FSLogix con il contenitore dei profili</p></li>
<li><p>Distribuire l'agente FSLogix con Office contenitore</p></li>
<li><p>Configurare la cartella FSLogix con esclusioni di contenuto</p></li>
</ul></li>
<li><p>Distribuzione di Microsoft Edge</p></li>
<li><p>Distribuire Microsoft Teams</p></li>
<li><p>Connessione l'Windows client desktop virtuale</p></li>
</ul>
<p><strong>L'ambito seguente non è disponibile</strong></p>
<ul>
<li><p>Project della distribuzione di Desktop virtuale Windows del cliente.</p></li>
<li><p>Supporto nel sito.</p></li>
<li><p>Virtualizzazione/distribuzione di applicazioni di terze parti.</p></li>
<li><p>Immagini personalizzate.</p></li>
<li><p>Migrazioni e scenari che coinvolgono VMware e Citrix.</p></li>
<li><p>Scenari Linux.</p></li>
<li><p>Conversione o migrazione di profili utente.</p></li>
</ul>
<p>Contattare un <a href="https://go.microsoft.com/fwlink/?linkid=2080150">partner Microsoft per</a> assistenza con questi servizi.</p></td>
<td><p>Dovresti già disporre di quanto segue:</p>
<ul>
<li><p>[Requisiti di licenza WVD](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p>Rete di Azure:</p>
<ul>
<li><p>Creazione VNET &amp; Subnetting</p></li>
<li><p>Firewall/Gruppi di sicurezza di rete</p></li>
<li><p>VPN / ExpressRoute</p></li>
<li><p>Routing ad Azure da locale</p></li>
<li><p>Regole firewall per consentire la connettività a WVD</p>
<ul>
<li><p>[Documentazione di riferimento](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory Configurazione generale</p>
<ul>
<li><p>Strategia di <strong>identità (selezionare SOLO 1 delle seguenti 3 opzioni)</strong></p>
<ul>
<li><p>Active Directory con Azure AD Connessione in Azure</p></li>
<li><p>Active Directory con Azure AD Connessione locale su VPN /ER</p></li>
<li><p>Servizi di dominio Active Directory</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
