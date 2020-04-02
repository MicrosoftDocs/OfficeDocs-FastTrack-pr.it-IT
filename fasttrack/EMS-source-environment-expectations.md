---
title: Previsioni dell'ambiente di origine
description: Requisiti dell’ambiente di origine per utilizzare FastTrack Center Benefit per EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 4/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: ffec6096b8f8bb587318b1f5ee93789a80247a61
ms.sourcegitcommit: f2b9cb334c7687724c36b1c38ba24463576233bf
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 04/01/2020
ms.locfileid: "43098078"
---
# <a name="source-environment-expectations"></a>Previsioni dell'ambiente di origine

Se si usa il [FastTrack Center Benefit per Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) per avere Microsoft Azure Active Directory Premium, Microsoft Intune e Azure Information Protection pronti per l'uso, l'ambiente deve essere conforme alle previsioni descritte nelle sezioni seguenti.

È possibile che si abbia già Active Directory locale nell'organizzazione da integrare con Enterprise Mobility + Security (EMS) o uno dei suoi singoli servizi che usano gestione delle identità avanzate da una singola console. Il FastTrack Center Benefit per Enterprise Mobility + Security (EMS) offre assistenza per l'integrazione di Azure Active Directory con l'ambiente Active Directory locale.

Nella tabella seguente vengono mostrate le previsioni per l'ambiente di origine esistente per l'onboarding.

|Attività|Previsione dell'ambiente di origine|
|------------|----------------------------------|
|Onboarding di base|Insiemi di strutture di Active Directory con il livello di funzionalità foresta impostata a Windows Server 2008 o versioni successive, con la seguente configurazione dell'insieme di strutture:<br /><br />- Foresta unica di Active Directory<br />- Più foreste di Active Directory </br></br>**Nota**: per tutte le configurazioni di più foreste, la distribuzione di Active Directory Federation Services (AD FS) non rientra nell'ambito di FastTrack Center Benefit.|
|Onboarding di Azure AD Premium|Active Directory locale e l'ambiente sono stati preparati per Azure AD Premium, che include la correzione di problemi rilevati che impediscono l'integrazione con le funzionalità di Azure AD e Azure AD Premium.|
|Onboarding di Intune| Gli amministratori IT devono disporre di infrastrutture di autorità di certificazione, Wi-Fi e VPN esistenti già in uso negli ambienti di produzione durante la pianificazione della distribuzione dei profili Wi-Fi e VPN con Intune.<br /><br /> **Nota**: l'offerta del servizio non include l'assistenza per la configurazione o l'impostazione di infrastrutture di autorità di certificazione, Wi-Fi, VPN o certificati per le notifiche push di Apple MDM per  |
|Collegare tramite cloud Configuration Manager con Intune|Con il collegamento tramite cloud gli amministratori IT sono responsabili della preparazione dell'ambiente locale, che potrebbe includere la correzione di problemi che impediscono il collegamento tramite cloud degli ambienti di Configuration Manager con Intune.<br /><br />**Nota**: l'offerta del servizio FastTrack non include l'assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e del client di Configuration Manager ai requisiti minimi necessari per supportare il collegamento tramite cloud. |
|Intune integrato con Microsoft Defender Advanced Threat Protection (ATP)|**Nota**: l'offerta del servizio di FastTrack fornisce assistenza sull'integrazione di Intune con Microsoft Defender ATP e di creare criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10. L'offerta del servizio non fornisce assistenza sull'acquisto, sulla gestione delle licenze o sull'attivazione. |
|Windows Autopilot|Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore hardware carica gli ID hardware per conto degli amministratori o caricandoli loro stessi nel servizio Windows Autopilot. |
|Distribuire Outlook per iOS e Android in modo sicuro con Intune|<br /><br />- Identità dell’utente abilitate in Azure AD per Office 365.<br />- Exchange Online o Exchange ibrido configurato con le licenze utente assegnate.<br />|
|Azure Information Protection (P2 o EMS E5)|<br /><br />I clienti dovrebbero già sapere: <br /> - Utilizzare Azure AD.<br />- Usare Windows o iOS (non sono previsti altri sistemi operativi).<br /> - Usare client di Office più recenti di Office 2010 SP2 che non si basano su Office come client principale. <br /> - Disporre dei principali percorsi di condivisione file.  <br /> - Aver aggiornato Active Directory Rights Management Services (AD RMS) <br /> - Avere tassonomia di classificazione approvata. <br /> - Comprendere qualsiasi restrizione normativa per la gestione delle chiavi protette. <br />|
|Scanner di Azure Information Protection|<br /><br /> I clienti dovrebbero già sapere: <br /> - Utilizzare Windows Server 2012 R2 o Windows Server 2016.<br /> - Disporre di una connessione Internet. <br /> - Avere una versione successiva a Microsoft SQL Server 2012 in un'istanza locale o remota.  <br /> - Disporre di un account di servizio creato per Active Directory locale e sincronizzato con Azure AD.  <br /> - Aver scaricato AzInfoProtection.exe. <br /> - Avere etichette configurate per la classificazione/protezione automatica.<br />|

> [!NOTE]
> **Per saperne di più**
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Passaggi successivi

[FastTrack Center Benefit per le fasi di onboarding EMS](EMS-onboarding-phases.md)

