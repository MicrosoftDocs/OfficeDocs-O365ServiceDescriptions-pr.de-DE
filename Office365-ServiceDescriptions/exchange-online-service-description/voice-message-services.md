---
title: Sprachnachrichtendienste
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: fe1d1f5a58012498e5b0f71c9a4299e61a4456ad
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173390"
---
# <a name="voice-message-services"></a><span data-ttu-id="681f9-102">Sprachnachrichtendienste</span><span class="sxs-lookup"><span data-stu-id="681f9-102">Voice message services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="681f9-103">Voicemail</span><span class="sxs-lookup"><span data-stu-id="681f9-103">Voice mail</span></span>

<span data-ttu-id="681f9-104">Microsoft Exchange Online bietet gehostete Voicemaildienste mit folgenden Funktionen:</span><span class="sxs-lookup"><span data-stu-id="681f9-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="681f9-105">Mailboxansage (Voicemail)</span><span class="sxs-lookup"><span data-stu-id="681f9-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="681f9-106">Einwahlbenutzerschnittstelle zu Exchange (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="681f9-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="681f9-107">Einwahlschnittstelle für Anrufer (automatische Telefonzentrale)</span><span class="sxs-lookup"><span data-stu-id="681f9-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="681f9-p101">Gehostete Voicemessagingdienste erlauben einer Firma, ihre lokale Telefonanlage mit Voicemaildiensten von Exchange Online zu verbinden. Voicemailnachrichten werden aufgezeichnet und in der Exchange Online-Infrastruktur gespeichert. Benutzer können ihre Sprachnachrichten mit Outlook, Outlook im Web oder Mobiltelefonen abrufen. Alle Telefonieverbindungen zu Exchange Online erfordern Voice over IP-(VoIP-)Protokolle. Administratoren können lokale IP-Nebenstellenanlagen oder Nebenstellensysteme mithilfe von VoIP-Mediagateways und SBCs (Session Border Controllers) mit Exchange Online verbinden. Ein VoIP-Mediagateway ist nicht erforderlich, wenn der Kunde eine IP-Nebenstellenanlage bereitgestellt hat oder wenn eine Nebenstellenanlage direkt VoIP unterstützt und zusammen mit Exchange-Voicemessagingdiensten verwendet werden kann. SBCs werden innerhalb des Kundennetzwerks bereitgestellt, um ein lokales Telefonienetzwerk anzuschließen und die Kommunikation (und das Kundennetzwerk) vor Abhör- und Eindringversuchen zu schützen. Interoperabilität mit den Sprachfunktionen von Microsoft Lync Server 2010 und 2013 wird ebenfalls unterstützt.</span><span class="sxs-lookup"><span data-stu-id="681f9-p101">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="681f9-p102">Die Features der Voicemessagingdienste in Exchange Online sind mit den Features im lokalen Exchange Server 2016 vergleichbar. Dazu zählen:</span><span class="sxs-lookup"><span data-stu-id="681f9-p102">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:</span></span>
  
- <span data-ttu-id="681f9-117">Wiedergabe über Telefon in Outlook und Outlook im Web.</span><span class="sxs-lookup"><span data-stu-id="681f9-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="681f9-118">Benachrichtigungen über verpasste Anrufe.</span><span class="sxs-lookup"><span data-stu-id="681f9-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="681f9-119">Anrufer-ID (mithilfe der Informationen in der globale Adressliste, den persönlichen Kontakten der Benutzer, dem benutzerdefinierten Ordner "Kontakte" und Kontakten aus externen sozialen Netzwerken).</span><span class="sxs-lookup"><span data-stu-id="681f9-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="681f9-120">Zurücksetzen der Voicemail-PIN aus Outlook im Web und Outlook (Details siehe [Zurücksetzen einer Voicemail-PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin))</span><span class="sxs-lookup"><span data-stu-id="681f9-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).</span></span>
    
- <span data-ttu-id="681f9-121">Message Waiting Indicator (Details siehe [MWI in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online))</span><span class="sxs-lookup"><span data-stu-id="681f9-121">Message Waiting Indicator (see [MWI in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online) for details).</span></span> 
    
- <span data-ttu-id="681f9-122">Anrufbeantwortungsregeln (weitere Informationen finden Sie unter [Zulassen](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) der Weiterleitung von Anrufen durch Voicemailbenutzer).</span><span class="sxs-lookup"><span data-stu-id="681f9-122">Call answering rules (see [Allow voice mail users to forward calls](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) for details).</span></span>
    
- <span data-ttu-id="681f9-123">Geschützte Voicemail in Exchange Online (Weitere Informationen finden Sie unter Schützen von [Voicemail in Exchange Online).](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail)</span><span class="sxs-lookup"><span data-stu-id="681f9-123">Protected voice mail in Exchange Online (see [Protect voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) for details).</span></span>
    
- <span data-ttu-id="681f9-124">Voicemailvorschau (siehe Zulassen, dass Benutzern eine [Voicemail-Transkription](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) für eine Liste der unterstützten Sprachen angezeigt wird).</span><span class="sxs-lookup"><span data-stu-id="681f9-124">Voice mail preview (see [Allow users to see a voice mail transcript](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) for a list of supported languages).</span></span>
    
- <span data-ttu-id="681f9-125">Sprachzugriff auf E-Mail, Voicemail, Kalender, persönliche Kontakte und persönliche Kontaktgruppen.</span><span class="sxs-lookup"><span data-stu-id="681f9-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="681f9-126">Verzeichnissuche über Outlook Voice Access oder automatische Telefonzentrale.</span><span class="sxs-lookup"><span data-stu-id="681f9-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="681f9-127">Administratoren konfigurieren und verwalten die Interoperabilität von Voicemessagingdiensten mithilfe der Exchange-Verwaltungskonsole.</span><span class="sxs-lookup"><span data-stu-id="681f9-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="681f9-128">Weitere Informationen zu Voicemailfeatures finden Sie unter [Voicemail in Exchange Online](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging).</span><span class="sxs-lookup"><span data-stu-id="681f9-128">For more information about voice mail features, see [Voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="681f9-129">Die automatische Spracherkennung (ASR) ist nicht verfügbar in der Menünavigation oder Verzeichnissuche für Outlook Voice Access-Benutzer oder Anrufer bei der automatischen Telefonzentrale, die Sprachbefehle verwenden.</span><span class="sxs-lookup"><span data-stu-id="681f9-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span></span> 
>
> <span data-ttu-id="681f9-130">Der Kunde muss über ein VoIP-Gateway und eine Nebenstellenanlage, IP-PBX oder Skype for Business Server 2015 eine Telefonieverbindung über das Festnetz (Public Switched Telephone Network, PSTN) bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="681f9-130">The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015.</span></span> 
>
> <span data-ttu-id="681f9-p103">Der Kunde muss die lokalen SBC-Hardwaregeräte bereitstellen und sicherstellen, dass die SBCs ordnungsgemäß konfiguriert sind, um eine Verbindung zu den Online-Voicemaildiensten herzustellen. Dazu gehört das Konfigurieren der entsprechenden Sicherheitsebene, indem Zertifikate sowie öffentliche und private IP-Schnittstellen verwendet und die richtigen TCP-Ports in den lokalen Firewalls aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="681f9-p103">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span></span> 
>
> <span data-ttu-id="681f9-133">Gehostete Voicemail ist nur für Exchange Online Plan 2- und Office 365 Enterprise E3-Abonnenten verfügbar.</span><span class="sxs-lookup"><span data-stu-id="681f9-133">Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="681f9-134">Interoperabilität von Voicemails eines Drittanbieters</span><span class="sxs-lookup"><span data-stu-id="681f9-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="681f9-p104">Lokale Voicemaillösungen von Drittanbietern können mit Exchange Online zusammenarbeiten, wenn sie Sprachnachrichten über SMTP weiterleiten können oder Microsoft Exchange-Webdienste unterstützen. Wenn das Voicemailsystem keine eigene Unterstützung für das Weiterleiten von Sprachnachrichten über SMTP bietet, kann ein lokaler E-Mail-Server weiterverwendet werden, um Nachrichten vom Voicemailsystem zu empfangen und anschließend über SMTP an die Cloud weiterzuleiten. Da viele Voicemailsysteme von Drittanbietern MAPI/CDO verwenden, um bei erweiterten UM-Funktionen mit Exchange Server zusammenzuarbeiten, ist unter Umständen nicht der gesamte Funktionsumfang dieser Systeme verfügbar, wenn SMTP für die Interoperabilität mit Exchange Online verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="681f9-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="681f9-p105">Die Exchange Online UM-Unterstützung für Nebenstellenanlagen von Drittanbietern über direkte Verbindungen von SBCs, die von Kunden betrieben werden, endet im Juli 2018. Weitere Informationen finden Sie im Blogbeitrag zur Einstellung des Supports für SBCs in Exchange Online UM unter [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117).</span><span class="sxs-lookup"><span data-stu-id="681f9-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="681f9-140">Skype for Business-Integration</span><span class="sxs-lookup"><span data-stu-id="681f9-140">Skype for Business integration</span></span>

<span data-ttu-id="681f9-141">Organisationen können Skype for Business Online als eigenständigen Dienst oder als Teil von Microsoft Office 365 erwerben.</span><span class="sxs-lookup"><span data-stu-id="681f9-141">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365.</span></span> <span data-ttu-id="681f9-142">Lokales Skype for Business 2015 wird ebenfalls unterstützt.</span><span class="sxs-lookup"><span data-stu-id="681f9-142">Skype for Business 2015 on-premises is also supported.</span></span> <span data-ttu-id="681f9-143">Weitere Informationen zu Skype for Business Online finden Sie unter [Skype for Business Online service description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="681f9-143">To learn more about Skype for Business Online, see [Skype for Business Online service description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="681f9-144">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="681f9-144">Feature availability</span></span>

<span data-ttu-id="681f9-145">Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="681f9-145">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
