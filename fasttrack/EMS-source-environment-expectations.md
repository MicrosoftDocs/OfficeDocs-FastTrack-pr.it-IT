---
title: Previsioni dell'ambiente di origine
description: Requisiti dell'ambiente di origine per l'utilizzo del FastTrack Center benefit per EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 6b3a5ed24ac254c3a989a584df0cbd89533ff1af
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359984"
---
# <a name="source-environment-expectations"></a>Previsioni dell'ambiente di origine

Quando si utilizza [FastTrack Center benefit per Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) per ottenere Microsoft Azure Active Directory Premium e Microsoft Intune pronto per l'uso, l'ambiente deve soddisfare le aspettative descritte nelle sezioni seguenti.

Potrebbe essere già presente Active Directory locale nell'organizzazione che si desidera integrare con Enterprise Mobility + Security (EMS) o uno qualsiasi dei suoi singoli servizi che utilizzano la gestione avanzata delle identità da una singola console. Il vantaggio di FastTrack Center per Enterprise Mobility + Security (EMS) include la funzionalità di integrazione di Azure Active Directory con l'ambiente Active Directory locale esistente.

Nella tabella seguente sono riportate le aspettative per l'ambiente di origine esistente per l'on-boarding.

|Attività|Previsione dell'ambiente di origine|
|------------|----------------------------------|
|Base d'imbarco|Foreste di Active Directory con il livello di foresta funzionale impostato su Windows Server 2008 o superiore, con la seguente configurazione della foresta:<br /><br />-Singola foresta di Active Directory<br />-Più foreste di Active Directory </br></br>**Nota**: per tutte le configurazioni di più insiemi di strutture, la distribuzione di Active Directory Federation Services (ad FS) non rientra nell'ambito del vantaggio FastTrack Center.|
|Azure AD Premium on-boarding|Active Directory locale e il relativo ambiente sono stati preparati per Azure AD Premium, che include la correzione di problemi identificati che impediscono l'integrazione con Azure AD e le funzionalità di Azure AD Premium.|
|On-boarding di Intune| Gli amministratori IT devono disporre di infrastrutture di certificazione, Wi-Fi e VPN già esistenti nei rispettivi ambienti di produzione durante la pianificazione della distribuzione di profili WiFi e VPN con Intune.<br /><br /> **Nota**: il vantaggio del servizio non include assistenza per la configurazione o la configurazione di autorità di certificazione, Wi-Fi, infrastrutture VPN o certificati push di Apple MDM per  |
|Cogestione|Con la cogestione IT Admins è responsabile della preparazione dell'ambiente locale, che potrebbe includere la correzione di problemi che impediscono di gestire contemporaneamente i dispositivi Windows 10 con Gestione configurazione e Intune.<br /><br />**Nota**: il vantaggio del servizio FastTrack non include assistenza per la configurazione o l'aggiornamento del server del sito di Configuration Manager e/o del client di gestione della configurazione ai requisiti minimi necessari per supportare la cogestione con i dispositivi Windows 10. |
|Intune integrato con Windows Defender Advanced Threat Protection (Windows Defender ATP)|La sottoscrizione di Windows Defender ATP è stata attivata e configurata in base ai requisiti di sicurezza dell'azienda.<br /><br />**Nota**: il vantaggio del servizio FastTrack fornisce assistenza nell'integrazione di Intune con Windows Defender ATP e nella creazione di criteri di conformità dei dispositivi in base alla valutazione del livello di rischio di Windows 10. Il vantaggio del servizio FastTrack non fornisce assistenza per l'acquisto, la gestione delle licenze, l'attivazione o l'utilizzo di Windows Defender ATP e della relativa console del Centro sicurezza. |
|Windows Autopilot|Gli amministratori IT sono responsabili della registrazione dei propri dispositivi nell'organizzazione, in quanto il fornitore dell'hardware ha caricato i propri ID hardware per conto di essi o caricandosi nel servizio Autopilot di Windows. |
|Distribuire Outlook per iOS e Android in modo sicuro con Intune|<br /><br />-Identità degli utenti abilitati in Azure AD per Office 365.<br />-Exchange Online o Hybrid Exchange configurati con le licenze utente assegnate.<br />|

> [!NOTE]
> **Vuoi saperne di più?** 
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Passaggi successivi

[FastTrack Center benefit per le fasi di onboarding EMS](EMS-onboarding-phases.md)
