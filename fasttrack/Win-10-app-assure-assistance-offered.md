---
title: Assistenza offerta
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Normal
ms.collection: FastTrack
description: Al momento dell'acquisto di uno dei servizi di Windows 10 o Microsoft 365, gli esperti FastTrack forniscono indicazioni e correzioni per la distribuzione di Windows 10 e Microsoft 365 Apps e consentono di mantenersi aggiornati senza costi aggiuntivi (con un abbonamento idoneo).
ms.openlocfilehash: 4cd513a4e0c1edda3598a6650bdea91d90f5584f
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016422"
---
# <a name="assistance-offered"></a>Assistenza offerta  

Quando si acquista uno dei servizi di Windows 10 o Microsoft 365 (come descritto in dettaglio in [Idoneità),](eligibility.md)gli esperti fasttrack forniscono indicazioni di consulenza e correzione se si verificano problemi di compatibilità delle app durante la distribuzione di prodotti Microsoft più nuovi, come descritto in [Prodotti Microsoft](#supported-microsoft-products)supportati.

Per assistenza, completare la [richiesta di servizio App Assure](https://go.microsoft.com/fwlink/?linkid=2022721).

I partner possono anche ricevere assistenza tramite il [sito FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) per conto di un cliente. Per farlo, il partner accede al sito, seleziona il record del cliente, fa clic su **Servizi** e completa il modulo **Richiesta di assistenza per App Assure**.

> [!NOTE]
> L'assistenza è disponibile in cinese tradizionale e cinese semplificato (le risorse parlano solo cinese mandarino), inglese, francese, tedesco, italiano, giapponese, coreano, portoghese (Brasile) e spagnolo. 

## <a name="supported-microsoft-products"></a>Prodotti Microsoft supportati

FastTrack fornisce assistenza per la correzione delle app distribuite nei prodotti Microsoft seguenti:

### <a name="windows-10-and-microsoft-365-apps"></a>Windows 10 e Microsoft 365 Apps

- Le app che hanno funzionato su Windows 7, Windows 8,1, Office 2010 e Office 2013 funzionano anche su Windows 10 e Microsoft 365 Apps.

### <a name="windows-10-on-arm"></a>Windows 10 in ARM

- Le app che hanno funzionato su Windows 7, Office 2010 o versioni successive funzionano su Windows 10 e Microsoft 365 Apps su dispositivi ARM64.

> [!NOTE]
> Le esclusioni e le limitazioni di Windows 10 in ARM includono app che si basano su driver software non compatibili in ARM, usano OpenGL o OpenCL o sono disponibili solo a 64 bit (x64).

### <a name="microsoft-edge"></a>Microsoft Edge

- Se le app o i siti Web funzionano in Internet Explorer 11, nelle versioni supportate di Google Chrome o in qualsiasi versione di Microsoft Edge, funzionano anche con Microsoft Edge.

Per informazioni sulla distribuzione di Microsoft Edge, vedere [Panoramica dei canali Microsoft Edge](https://docs.microsoft.com/DeployEdge/microsoft-edge-channels). Poiché il Web è in continua evoluzione, pubblichiamo un elenco di [modifiche note che influiscono sulla compatibilità dei siti per Microsoft Edge](https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes).

### <a name="windows-virtual-desktop"></a>Desktop virtuale Windows

- Applicazioni virtualizzate che vengono eseguite su Windows Server Remote Desktop Session Host (RDSH) vengono eseguite anche nella multisessione di Windows 10 Enterprise come parte del Desktop virtuale Windows.
- Le app in esecuzione in qualsiasi ambiente VDI (Virtual Desktop Infrastructure) di Windows 7 o Windows 10 vengono eseguite anche in Windows 7 Enterprise e Windows 10 Enterprise come parte di Desktop virtuale Windows.
- Le app che vengono eseguite su dispostivi client di Windows 7 o Windows 10, vengono eseguite anche su Windows 7 Enterprise e Windows 10 Enterprise come parte del Desktop virtuale Windows.

> [!NOTE]
> Le esclusioni e le limitazioni di compatibilità nella multisessione di Windows 10 Enterprise includono: 
> - Reindirizzamento limitato dell'hardware.
> - Le app con uso intensivo di A/V possono essere eseguite a una capacità ridotta.
> - Le app a 16 bit non sono supportate per la versione Desktop virtuale Windows a 64 bit.

Per altre informazioni, vedere [che cos'è il Desktop virtuale Windows?](https://docs.microsoft.com/azure/virtual-desktop/overview) e [domande frequenti sulla multisessione Windows 10 Enterprise](https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq).

> [!NOTE]
> FastTrack si impegna al massimo per risolvere i problemi di compatibilità. 

## <a name="out-of-scope"></a>Esclusioni

I servizi FastTrack non includono:
- Inventario e test delle app per stabilire cosa funziona e cosa non funziona in Windows 10 e Microsoft 365 Apps. Per altre indicazioni su questo processo, visitare il [Centro di distribuzione desktop](https://go.microsoft.com/fwlink/?linkid=2080140). Per richiedere una valutazione approfondita dell'idoneità per l'aggiornamento, compilare l'apposito [modulo](https://go.microsoft.com/fwlink/?linkid=2053818).
- Ricerca di applicazioni ISV di terze parti per istruzioni su supporto e compatibilità con Windows 10. Per ulteriori informazioni, vedere [Desktop Analytics](https://docs.microsoft.com/sccm/desktop-analytics/overview).
- Servizi di sola creazione di pacchetti di app. Tuttavia, il team di App Assure crea pacchetti di app che abbiamo corretto per Windows 10 per garantire che possano essere distribuiti nell'ambiente del cliente.

Le responsabilità dell'utente includono:
- Creazione di un inventario delle app.
- Convalida di tali app in Windows 10 e Microsoft 365 Apps.

> [!NOTE]
> Microsoft non può apportare modifiche al codice sorgente del cliente. Tuttavia, il team di App Assure può fornire indicazioni agli sviluppatori di app in merito alla disponibilità del codice sorgente per le applicazioni del cliente.

> [!NOTE]
> Contattare un [partner Microsoft](https://go.microsoft.com/fwlink/?linkid=2080150) per fornire assistenza per i servizi identificati come esclusi dall'ambito.


