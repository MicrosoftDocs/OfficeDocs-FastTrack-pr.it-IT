---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack fornisce indicazioni per la distribuzione di Windows 10 che consentono di eseguire l'aggiornamento da Windows 7 Professional e Windows 8.1 Professional a Windows 10 Enterprise.
ms.openlocfilehash: 0b19ada41624d8c8fa8d3ab5e85a14b42edd53f3
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817137"
---
# <a name="windows-10"></a><span data-ttu-id="28cf1-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="28cf1-103">Windows 10</span></span>

> [!CAUTION]
> <span data-ttu-id="28cf1-104">Questo contenuto non è più corrente e viene pianificato per la rimozione.</span><span class="sxs-lookup"><span data-stu-id="28cf1-104">This content is no longer current and is scheduled for removal.</span></span> <span data-ttu-id="28cf1-105">Utilizzare il sommario nel riquadro di spostamento sinistro per il contenuto corrente.</span><span class="sxs-lookup"><span data-stu-id="28cf1-105">Use the table of contents in the left-hand navigation for current content.</span></span>

<span data-ttu-id="28cf1-106">FastTrack fornisce indicazioni per la distribuzione di Windows 10 che consentono di eseguire l'aggiornamento da Windows 7 Professional e Windows 8.1 Professional a Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="28cf1-106">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="28cf1-107">Si collabora con specialisti di FastTrack per:</span><span class="sxs-lookup"><span data-stu-id="28cf1-107">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="28cf1-108">Distribuire Windows 10 Enterprise con Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="28cf1-108">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="28cf1-109">Distribuire Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="28cf1-109">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="28cf1-110">Aggiornare Windows 10 Enterprise e Microsoft 365 Apps con Microsoft Endpoint Configuration Manager o Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="28cf1-110">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="28cf1-111">Collegare tramite cloud Configuration Manager con Microsoft Intune o distribuire Intune come unica soluzione di gestione cloud.</span><span class="sxs-lookup"><span data-stu-id="28cf1-111">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="28cf1-112">FastTrack offre ai clienti un approccio consigliato, linee guida e procedure consigliate progettate per ottenere risultati rapidi e prevedibili.</span><span class="sxs-lookup"><span data-stu-id="28cf1-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="28cf1-113">Se si sceglie di eseguire la distribuzione senza seguire questa guida, ciò potrebbe influire sull'esperienza.</span><span class="sxs-lookup"><span data-stu-id="28cf1-113">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="28cf1-114">L'assistenza viene definita come una combinazione di supporto in forma orale e scritta.</span><span class="sxs-lookup"><span data-stu-id="28cf1-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="28cf1-115">Quando gli esperti di FastTrack offrono assistenza, il personale di FastTrack non può agire per conto dell'utente.</span><span class="sxs-lookup"><span data-stu-id="28cf1-115">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="28cf1-116">È possibile usare i servizi di FastTrack per i piani idonei a condizione che l'abbonamento sia corrente.</span><span class="sxs-lookup"><span data-stu-id="28cf1-116">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="28cf1-117">Nella tabella seguente sono elencati i ruoli e le responsabilità per il processo.</span><span class="sxs-lookup"><span data-stu-id="28cf1-117">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="28cf1-118">**Ruolo**</span><span class="sxs-lookup"><span data-stu-id="28cf1-118">**Role**</span></span> <br/> |<span data-ttu-id="28cf1-119">**Responsabilità**</span><span class="sxs-lookup"><span data-stu-id="28cf1-119">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="28cf1-120">**Esperto FastTrack**</span><span class="sxs-lookup"><span data-stu-id="28cf1-120">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="28cf1-121">Fornisce tutti i servizi di distribuzione e aggiornamento in remoto.</span><span class="sxs-lookup"><span data-stu-id="28cf1-121">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="28cf1-122">Offre assistenza in remoto, sfruttando una combinazione di strumenti e documentazione pubblicata.</span><span class="sxs-lookup"><span data-stu-id="28cf1-122">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="28cf1-123">Lavora direttamente con l'utente o con il rappresentante.</span><span class="sxs-lookup"><span data-stu-id="28cf1-123">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="28cf1-124">**FastTrack Center**</span><span class="sxs-lookup"><span data-stu-id="28cf1-124">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="28cf1-125">Fornisce indicazioni per pianificare e distribuire Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="28cf1-125">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="28cf1-126">Offre assistenza ed è disponibile durante il regolare orario lavorativo in base all'area.</span><span class="sxs-lookup"><span data-stu-id="28cf1-126">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="28cf1-127">Offre assistenza in cinese tradizionale e cinese semplificato (le risorse parlano solo cinese mandarino), inglese, francese, tedesco, italiano, giapponese, coreano, portoghese (Brasile), spagnolo, tailandese e vietnamita.</span><span class="sxs-lookup"><span data-stu-id="28cf1-127">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="28cf1-128">È possibile ottenere assistenza tramite l'[interfaccia di amministrazione di Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704) o il [sito di FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).</span><span class="sxs-lookup"><span data-stu-id="28cf1-128">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="28cf1-129">Per accedere, è necessario avere un account aziendale o dell'istituto di istruzione (ID organizzazione o ID di Azure Active Directory) in un tenant attivo.</span><span class="sxs-lookup"><span data-stu-id="28cf1-129">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="28cf1-130">Per ottenere assistenza tramite il [sito di FastTrack](https://go.microsoft.com/fwlink/?linkid=780698):</span><span class="sxs-lookup"><span data-stu-id="28cf1-130">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="28cf1-131">Accedere al [sito di FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).</span><span class="sxs-lookup"><span data-stu-id="28cf1-131">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="28cf1-132">Selezionare**Richiedi assistenza con Microsoft 365** da **Azioni Rapide** nella parte superiore della pagina di destinazione.</span><span class="sxs-lookup"><span data-stu-id="28cf1-132">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="28cf1-133">Completare il modulo **Richiesta di assistenza con Microsoft 365**.</span><span class="sxs-lookup"><span data-stu-id="28cf1-133">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="28cf1-p105">I partner possono anche ricevere assistenza tramite il [sito di FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) per conto di un cliente. A tale scopo:</span><span class="sxs-lookup"><span data-stu-id="28cf1-p105">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.    <span data-ttu-id="28cf1-136">Accedere al [sito di FastTrack](https://go.microsoft.com/fwlink/?linkid=780698).</span><span class="sxs-lookup"><span data-stu-id="28cf1-136">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="28cf1-137">Selezionare**Richiedi assistenza con Microsoft 365** da **Azioni Rapide** nella parte superiore della pagina di destinazione.</span><span class="sxs-lookup"><span data-stu-id="28cf1-137">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="28cf1-138">Cercare il cliente immettendo il nome del cliente, il dominio o il TPID.</span><span class="sxs-lookup"><span data-stu-id="28cf1-138">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="28cf1-139">Selezionare il cliente dai risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="28cf1-139">Select customer from the search results.</span></span>
5.    <span data-ttu-id="28cf1-140">Completare il modulo **Richiesta di assistenza con Microsoft 365**.</span><span class="sxs-lookup"><span data-stu-id="28cf1-140">Complete the **Request Assistance with Microsoft 365** form.</span></span>
 
