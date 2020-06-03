---
title: Fasi di onboarding
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 6/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: Il processo di onboarding di Windows 10 prevede quattro fasi principali, ovvero avvio, valutazione, correzione e attivazione.
ms.openlocfilehash: c42792ea21b0c8d08ba9fa5e225882fa540a792a
ms.sourcegitcommit: 826f140cc0ddee32005f74e5d995073af1dc3fa2
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/01/2020
ms.locfileid: "44472069"
---
# <a name="onboarding-phases"></a>Fasi di onboarding

Il processo di onboarding di Windows 10 prevede quattro fasi principali, ovvero avvio, valutazione, correzione e attivazione.

## <a name="initiate"></a>Avvio

Durante questa fase, verrà discusso il processo di onboarding, saranno verificati i dati e verrà impostata la riunione iniziale. Ciò include collaborare con l’utente per comprendere le sue intenzioni riguardanti Windows 10.

## <a name="assess"></a>Valutazione

Gli specialisti di FastTrack assistono l'utente nel valutare l'ambiente di origine e i requisiti. Assicurarsi che Microsoft Endpoint Configuration Manager venga aggiornato al livello necessario per supportare la distribuzione di Windows 10. 

Sono disponibili opzioni consigliate per valutare le app di Windows 10. FastTrack fornisce indicazioni per abilitare l'uso di analisi desktop e consente di creare un piano di distribuzione di analisi desktop.

FastTrack può anche guidare la valutazione della compatibilità di App di Microsoft 365 sfruttando il dashboard di conformità di Office 365 in Configuration Manager o con il Toolkit di conformità autonomo per Office. Per altre informazioni sui servizi disponibili, vedere [FastTrack Center Benefit per Office 365](O365-fasttrack-benefit-for-office-365.md). 

FastTrack valuta anche le strategie di gestione moderne, tra cui il collegamento tramite cloud di Configuration Manager con Microsoft Intune o la distribuzione di Intune come unica soluzione di gestione cloud.

## <a name="remediate"></a>Correzione

L'utente esegue le attività di correzione basate sull'ambiente di origine, per soddisfare i requisiti per l'onboarding. Forniamo un elenco di controllo per la preparazione dell'ambiente e la conferma dell'avvenuta implementazione di questi elementi per garantire il rispetto dei requisiti minimi per una distribuzione corretta. 

## <a name="enable"></a>Attivazione

FastTrack fornisce indicazioni per l'aggiornamento dei dispositivi esistenti a Windows 10 Enterprise, purché soddisfino i requisiti hardware necessari per i dispositivi. Sono disponibili indicazioni per l'aggiornamento per supportare il movimento di distribuzione esistente. FastTrack consiglia e fornisce indicazioni per l'aggiornamento sul posto a Windows 10. Sono inoltre disponibili indicazioni per l'installazione di immagini pulite di Windows e per gli scenari di distribuzione di [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot). 

Sono disponibili indicazioni per distribuire App di Microsoft 365 con Configuration Manager nell'ambito della distribuzione di Windows 10. Per altre informazioni sui servizi associati, vedere [App di Microsoft 365](O365-onboarding-and-migration.md#microsoft-365-apps).

Sono disponibili indicazioni per aiutare l'organizzazione a mantenersi aggiornata con Windows 10 Enterprise e App di Microsoft 365 con l'ambiente di Configuration Manager esistente o con Microsoft 365.

Se necessario, FastTrack è in grado di guidare i clienti nella gestione moderna mediante il collegamento tramite cloud di Configuration Manager a Intune o la distribuzione di Intune come soluzione autonoma. Vedere [FastTrack Center Benefit Process per Enterprise Mobility + Security (EMS)](EMS-fasttrack-process.md) per maggiori dettagli sui servizi associati.

> [!NOTE]
> Se non si dispone di un piano o di un processo di distribuzione o manutenzione esistente, è possibile fornire indicazioni consigliate basate sullo scenario di aggiornamento sul posto (scelta consigliata)o [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot).

## <a name="out-of-scope"></a>Esclusioni

FastTrack non fornisce indicazioni per:

- Aggiornamento di Configuration Manager al Current Branch.
- Creazione di immagini personalizzate per la distribuzione di Windows 10.
- Creazione e supporto degli script di distribuzione per la distribuzione di Windows 10.
- Conversione di un sistema di Windows 10 dal BIOS a Unified Extensible Firmware Interface (UEFI).
- Abilitare le funzionalità di sicurezza di Windows 10. 
- Configurazione di Windows Deployment Services (WDS) per il boot di Preboot Execution Environment (PXE).
- Uso di Microsoft Deployment Toolkit (MDT) per acquisire e distribuire immagini di Windows 10.
- Uso dell’Utilità di migrazione dello stato utente (USMT).

  > [!NOTE]
  > Contattare un [partner Microsoft](https://go.microsoft.com/fwlink/?linkid=2080150) per fornire assistenza per i servizi identificati come esclusi dall'ambito.

 