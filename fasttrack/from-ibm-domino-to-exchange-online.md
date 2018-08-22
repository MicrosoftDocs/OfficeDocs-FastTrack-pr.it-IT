---
title: Appendice A Migrazione da IBM Domino a Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 8/2/18
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 7519ee6f-67e6-4064-b1b2-a26f35cdba0b
description: 'La migrazione da IBM Domino a Exchange Online include diversi aspetti importanti, tra cui le attività eseguite durante le fasi seguenti:'
ms.openlocfilehash: 1e2153627f7a52ed774c33c7d8aaa9a577f2b21d
ms.sourcegitcommit: 7865f572bf312a6ec49f72981d983c6370f34b11
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 08/10/2018
ms.locfileid: "22449104"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a>Appendice A: Migrazione da IBM Domino a Exchange Online

La migrazione da IBM Domino a Exchange Online include diversi aspetti importanti, tra cui le attività eseguite durante le fasi seguenti:
  
- [Fase di avvio](#initiate-phase)
    
- [Fase di valutazione](#assess-phase)
    
- [Fase di correzione](#remediate-phase)
    
- [Fase di attivazione:](#enable-phase)
    
- [Fase di migrazione](#migrate-phase)
    
## <a name="identities"></a>Identità

L'utente è responsabile della creazione e della gestione delle identità (solo cloud, sincronizzate o federate con Active Directory locale). È necessario completare il mapping delle identità (se non è già presente) tra Domino e Active Directory locale o Azure AD durante le fasi iniziali dell'onboarding.
  
## <a name="coexistence"></a>Coesistenza

FastTrack Center Benefit per Office 365 fornisce un flusso di posta bidirezionale tra l'ambiente Domino locale ed Exchange Online a tutti i clienti.
  
## <a name="migration"></a>Migrazione

Il processo di FastTrack Center standard per la migrazione da Domino a Exchange Online interessa i dati di Domino di pregestione per Azure prima della migrazione alle cassette postali di Exchange Online. Le migrazioni di FastTrack richiedono l'esecuzione di attività da parte del personale di FastTrack Center e dell'utente nelle diverse fasi dell'onboarding. Queste attività sono descritte nelle sezioni seguenti.
  
> [!NOTE]
> I dati migrati tramite i servizi FastTrack possono essere trasferiti, archiviati ed elaborati negli Stati Uniti o dovunque sia presente una sede Microsoft. I servizi FastTrack non sono progettati per i dati soggetti a particolari requisiti normativi o legali. 
  
## <a name="initiate-phase"></a>Fase di avvio

 **Azioni principali**
  
- Identificare Domino come piattaforma di posta elettronica di origine.
    
- Determinare se FastTrack Center esegue la migrazione.
    
 **Responsabilità dell'utente**
  
- Fornire informazioni di base sulla piattaforma di messaggistica di origine e confermare l'intenzione di effettuare la migrazione con FastTrack Center.
    
- Partecipare a una procedura dettagliata dei processi relativi al vantaggio FastTrack Center.
    
- Firmare il contratto per i servizi FastTrack.
    
## <a name="assess-phase"></a>Fase di valutazione

 **Azioni principali**
  
- FastTrack Center organizza un workshop sulla migrazione con il cliente.
    
- L'utente completa i prerequisiti della migrazione, come l'apposito questionario e il provisioning delle workstation amministrative.
    
- La valutazione della migrazione per Domino viene effettuata nell'ambiente locale dell'utente.
    
 **Responsabilità dell'utente**
  
- Effettuare il provisioning delle workstation amministrative utilizzate da FastTrack Center per l'amministrazione dell'onboarding e delle attività di migrazione, come la valutazione, la creazione di repliche, il controllo, la configurazione dell'inoltro durante la migrazione e così via.
    
    > [!NOTE]
    > La valutazione è fondamentale per la pianificazione e l'esecuzione corretta di migrazioni su vasta scala. Viene effettuata da un tecnico della migrazione che necessita di un accesso specifico all'ambiente Domino. Tra i componenti delle workstation amministrative necessari rientra un client Notes configurato per l'accesso a tutti i server di posta Domino di origine e il server di gestione temporanea delle repliche di Domino di Azure. 
  
- Fornire al team responsabile della migrazione l'accesso remoto alle workstation amministrative, agli account e alle autorizzazioni per effettuare le attività di valutazione e migrazione. Queste attività prevedono il provisioning di più account in locale e in Exchange Online con le autorizzazioni amministrative necessarie per la migrazione.
    
- Aprire le porte del firewall. È necessario che le porte in uscita siano aperte tra i server di posta Domino di origine e il server di gestione temporanea di Azure. Devono essere aperte anche le altre porte per le comunicazioni (come le workstation amministrative, i server Domino di origine e i server Exchange locali, se presenti).
    
- Abilitare la certificazione incrociata tra l'ambiente Domino di origine e il server di gestione temporanea Domino di Azure per agevolare la replica. Le attività relative alla certificazione incrociata sono coordinate tra l'amministratore Domino dei clienti e FastTrack Center.
    
- Completare il questionario sulla migrazione, che raccoglie le informazioni necessarie per la configurazione dell'ambiente di migrazione in Azure (come gli strumenti, gli script e i server di migrazione).
    
- Verificare che le cassette postali di destinazione in Office 365 abbiano il protocollo MAPI (Messaging Application Program Interface) abilitato.
    
> [!NOTE]
> Alcuni piani di Office 365 non supportano il protocollo MAPI. Per eseguire la migrazione dei dati, le cassette postali di tali piani devono essere convertite in un piano compatibile con MAPI prima dell'evento della migrazione. In seguito alla migrazione, questi piani possono essere modificati di nuovo. 
  
## <a name="remediate-phase"></a>Fase di correzione

 **Azioni principali**
  
- FastTrack Center esamina il report di valutazione della migrazione e verifica i dati forniti dall'utente tramite il questionario.
    
- Le correzioni suggerite da FastTrack Center devono essere completate dall'utente.
    
 **Responsabilità dell'utente**
  
- Correggere l'ambiente Domino in base alle linee guida indicate da FastTrack Center (ad esempio, la configurazione di eventuali autorizzazioni necessarie identificate come mancanti nei file di posta).
    
- Assicurarsi che le dimensioni delle cassette postali di Domino siano inferiori al limite consentito nella migrazione.
    
    > [!NOTE]
    >  Anche se FastTrack effettua la migrazione di una quantità massima di contenuti pari all'85% delle dimensioni totali consentite del target, tentare di migrare cassette postali di dimensioni superiori ai 2 GB comporta rischi aggiuntivi come quelli indicati di seguito:    <br/> Durata prolungata delle migrazioni.    <br/> Utilizzo di risorse altrimenti usate per la migrazione di altre cassette postali.    <br/> Notevole aumento della percentuale di errori. 
  
- Predisporre i database della posta in arrivo e i relativi ACL per la migrazione. È necessario eseguire alcune procedure di correzione per migrare in modo corretto i database della posta in arrivo e le relative autorizzazioni a una cassetta postale condivisa in Exchange Online. Alcune di queste procedure sono le seguenti:
    
  - Rimuovere le voci dei database della posta in arrivo esistenti nella directory di Domino e creare nuovi record Persona.
    
  - Creare gruppi di protezione universali abilitati alla posta elettronica in Active Directory locale che siano sincronizzati a Office 365 Azure AD e utilizzati per configurare le autorizzazioni sulla cassetta postale condivisa in Exchange Online. In questo modo le autorizzazioni impostate per il database della posta in arrivo vengono trasferite sulla cassetta postale condivisa in Exchange Online.
    
> [!NOTE]
> A questo punto è possibile avviare la valutazione e la formazione degli utenti finali per il nuovo sistema di messaggistica e il client. 
  
## <a name="enable-phase"></a>Fase di attivazione:

 **Azioni principali**
  
- FastTrack Center configura l'ambiente di migrazione in Azure.
    
- FastTrack Center configura gli strumenti di migrazione sulle workstation amministrative locali.
    
- FastTrack Center configura e mostra come utilizzare lo strumento di importazione automatica.
    
- FastTrack Center esegue la convalida di tutti i componenti della migrazione ed esegue le migrazioni di prova.
    
 **Responsabilità dell'utente**
  
- Il personale responsabile della pianificazione della migrazione della cassetta postale deve comprendere come usare lo strumento di importazione automatica. Tale strumento consente di importare il programma della migrazione nel database di pianificazione, che viene utilizzato da FastTrack Center per effettuare le attività di preparazione alla migrazione.
    
- Eseguire le attività preliminari alla migrazione quali l'importazione dei programmi dell'utente, l'analisi dei report di controllo, la correzione di eventuali problemi e la reimportazione degli account utente con problemi.
    
    Le attività di preparazione alla migrazione sono coordinate tra l'utente e FastTrack Center. La replica di Azure viene avviata dopo l'importazione del programma della migrazione dell'utente. 
    
    > [!NOTE]
    > Il tempo necessario per tale operazione dipende dalla quantità di dati. FastTrack Center esegue un controllo per determinare la conformità della migrazione. Gli esiti del controllo vengono forniti all'utente, con la consapevolezza che in genere è necessaria una fase di correzione successiva. Tutte queste attività vengono denominate "T-minus" perché devono iniziare prima della migrazione pianificata degli utenti. 
  
## <a name="migrate-phase"></a>Fase di migrazione

 **Azioni principali**
  
- FastTrack Center esegue migrazioni pilota e su vasta scala. 
    
- FastTrack Center esegue eventi di migrazione e attività "T-minus".
    
- FastTrack Center fornisce supporto post-migrazione.
    
 **Responsabilità dell'utente**
  
- Identificare e importare eventuali pianificazioni di migrazione 21 giorni prima della migrazione.
    
    > [!NOTE]
    > Questa operazione è molto importante perché le attività di preparazione alla migrazione comprendono la correzione e i possibili tentativi di creazione di repliche nelle diverse fasi prima della data della migrazione effettiva (T-0). Durante la migrazione di alcune cassette postali, le attività "T-minus" vengono eseguite sulle altre. Ciò rende necessaria una perfetta pianificazione e coordinazione. 
  
- Risolvere i problemi rilevati durante le attività "T-minus".
    
- Individuare e risolvere eventuali problemi del server Domino che influiscono sulle attività di migrazione.
    
- Inviare comunicazioni all'utente finale sulla data di migrazione.
    
- Condurre attività di valutazione dell'utente finale e formazione per il nuovo sistema di messaggistica e il client.
    
- Individuare e segnalare i problemi di post-migrazione. FastTrack Center fornisce supporto post-migrazione fino a 5 giorni dopo la migrazione (T+5), allo scadere dei quali tutto ciò che riguarda la migrazione sarà di responsabilità dell'utente. È possibile registrare ticket di post-migrazione per problemi quali messaggi di posta elettronica, elementi di calendario e contatti mancanti o per la presenza di duplicati nella cassetta postale.
    
FastTrack Center non copre la distribuzione, i canoni di licenza o il supporto relativo alla preparazione della directory (compresa la sincronizzazione delle directory Domino e Active Directory), i componenti aggiuntivi del software per la coesistenza per l'interoperabilità delle applicazioni Notes, la migrazione self-service o la migrazione dell'archivio.
  

  

