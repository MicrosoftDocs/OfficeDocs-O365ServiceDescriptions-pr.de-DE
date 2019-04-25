---
title: Sprachnachrichtendienste
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 3879252927a26f47cd5d92f0fbcfbdecf4466c2a
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246471"
---
# <a name="voice-message-services"></a><span data-ttu-id="47e39-102">Sprachnachrichtendienste</span><span class="sxs-lookup"><span data-stu-id="47e39-102">Voice Message Services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="47e39-103">Voicemail</span><span class="sxs-lookup"><span data-stu-id="47e39-103">Voice mail</span></span>

<span data-ttu-id="47e39-104">Microsoft Exchange Online bietet gehostete Voicemaildienste mit folgenden Funktionen:</span><span class="sxs-lookup"><span data-stu-id="47e39-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="47e39-105">Mailboxansage (Voicemail)</span><span class="sxs-lookup"><span data-stu-id="47e39-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="47e39-106">Einwahlbenutzerschnittstelle zu Exchange (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="47e39-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="47e39-107">Einwahlschnittstelle für Anrufer (automatische Telefonzentrale)</span><span class="sxs-lookup"><span data-stu-id="47e39-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="47e39-p101">Gehostete Voicemessagingdienste erlauben einer Firma, ihre lokale Telefonanlage mit Voicemaildiensten von Exchange Online zu verbinden. Voicemailnachrichten werden aufgezeichnet und in der Exchange Online-Infrastruktur gespeichert. Benutzer können ihre Sprachnachrichten mit Outlook, Outlook im Web oder Mobiltelefonen abrufen. Alle Telefonieverbindungen zu Exchange Online erfordern Voice over IP-(VoIP-)Protokolle. Administratoren können lokale IP-Nebenstellenanlagen oder Nebenstellensysteme mithilfe von VoIP-Mediagateways und SBCs (Session Border Controllers) mit Exchange Online verbinden. Ein VoIP-Mediagateway ist nicht erforderlich, wenn der Kunde eine IP-Nebenstellenanlage bereitgestellt hat oder wenn eine Nebenstellenanlage direkt VoIP unterstützt und zusammen mit Exchange-Voicemessagingdiensten verwendet werden kann. SBCs werden innerhalb des Kundennetzwerks bereitgestellt, um ein lokales Telefonienetzwerk anzuschließen und die Kommunikation (und das Kundennetzwerk) vor Abhör- und Eindringversuchen zu schützen. Interoperabilität mit den Sprachfunktionen von Microsoft Lync Server 2010 und 2013 wird ebenfalls unterstützt.</span><span class="sxs-lookup"><span data-stu-id="47e39-p101">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="47e39-p102">Die Features der Voicemessagingdienste in Exchange Online sind mit den Features im lokalen Exchange Server 2016 vergleichbar. Dazu zählen:</span><span class="sxs-lookup"><span data-stu-id="47e39-p102">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:</span></span>
  
- <span data-ttu-id="47e39-117">Wiedergabe über Telefon in Outlook und Outlook im Web.</span><span class="sxs-lookup"><span data-stu-id="47e39-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="47e39-118">Benachrichtigungen über verpasste Anrufe.</span><span class="sxs-lookup"><span data-stu-id="47e39-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="47e39-119">Anrufer-ID (mithilfe der Informationen in der globale Adressliste, den persönlichen Kontakten der Benutzer, dem benutzerdefinierten Ordner "Kontakte" und Kontakten aus externen sozialen Netzwerken).</span><span class="sxs-lookup"><span data-stu-id="47e39-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="47e39-120">Zurücksetzen der Voicemail-PIN aus Outlook im Web und Outlook (Details siehe [Zurücksetzen einer Voicemail-PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328))</span><span class="sxs-lookup"><span data-stu-id="47e39-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).</span></span>
    
- <span data-ttu-id="47e39-121">Message Waiting Indicator (Details siehe [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794))</span><span class="sxs-lookup"><span data-stu-id="47e39-121">Message Waiting Indicator (see [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794) for details).</span></span> 
    
- <span data-ttu-id="47e39-122">Regeln für die Mailboxansage (Details siehe Artikel zum Thema [Ermöglichen der Anrufweiterleitung für Voicemailbenutzer](https://go.microsoft.com/fwlink/p/?LinkId=271795))</span><span class="sxs-lookup"><span data-stu-id="47e39-122">Call Answering Rules (see [Allow Voice Mail Users to Forward Calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for details).</span></span> 
    
- <span data-ttu-id="47e39-123">Geschützte Voicemail in Exchange Online (Details siehe [Schützen von Voicemail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796))</span><span class="sxs-lookup"><span data-stu-id="47e39-123">Protected Voice Mail in Exchange Online (see [Protected Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for details).</span></span> 
    
- <span data-ttu-id="47e39-124">Voicemailvorschau (Liste unterstützter Sprachen siehe [Zulassen der Anzeige von Voicemailtranskriptionen für Benutzer](https://go.microsoft.com/fwlink/p/?LinkId=271797))</span><span class="sxs-lookup"><span data-stu-id="47e39-124">Voice Mail Preview (see [Allow Users to See a Voice Mail Transcript](https://go.microsoft.com/fwlink/p/?LinkId=271797) for a list of supported languages).</span></span> 
    
- <span data-ttu-id="47e39-125">Sprachzugriff auf E-Mail, Voicemail, Kalender, persönliche Kontakte und persönliche Kontaktgruppen.</span><span class="sxs-lookup"><span data-stu-id="47e39-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="47e39-126">Verzeichnissuche über Outlook Voice Access oder automatische Telefonzentrale.</span><span class="sxs-lookup"><span data-stu-id="47e39-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="47e39-127">Administratoren konfigurieren und verwalten die Interoperabilität von Voicemessagingdiensten mithilfe der Exchange-Verwaltungskonsole.</span><span class="sxs-lookup"><span data-stu-id="47e39-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="47e39-128">Weitere Informationen zu Voicemailfeatures finden Sie im Artikel zum Thema [Voicemail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span><span class="sxs-lookup"><span data-stu-id="47e39-128">For more information about voice mail features, see [Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="47e39-p103">Die automatische Spracherkennung (ASR) ist nicht verfügbar in der Menünavigation oder Verzeichnissuche für Outlook Voice Access-Benutzer oder Anrufer bei der automatischen Telefonzentrale, die Sprachbefehle verwenden. > Der Kunde muss eine Telefonieverbindung zum öffentlichen Telefonnetz (PSTN) mithilfe eines VoIP-Gateways und einer Nebenstellenanlage, einer IP-Nebenstellenanlage oder Skype for Business Server 2015 bereitstellen. > Der Kunde muss die lokalen SBC-Hardwaregeräte bereitstellen und sicherstellen, dass die SBCs ordnungsgemäß konfiguriert sind, um eine Verbindung zu den Online-Voicemaildiensten herzustellen. Dazu gehört das Konfigurieren der entsprechenden Sicherheitsebene, indem Zertifikate sowie öffentliche und private IP-Schnittstellen verwendet und die richtigen TCP-Ports in den lokalen Firewalls aktiviert werden. > Gehostete Voicemail steht nur Abonnenten von Exchange Online Plan 2 und Office 365 Enterprise E3 zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="47e39-p103">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. > The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015. > The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. > Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="47e39-134">Interoperabilität von Voicemails eines Drittanbieters</span><span class="sxs-lookup"><span data-stu-id="47e39-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="47e39-p104">Lokale Voicemaillösungen von Drittanbietern können mit Exchange Online zusammenarbeiten, wenn sie Sprachnachrichten über SMTP weiterleiten können oder Microsoft Exchange-Webdienste unterstützen. Wenn das Voicemailsystem keine eigene Unterstützung für das Weiterleiten von Sprachnachrichten über SMTP bietet, kann ein lokaler E-Mail-Server weiterverwendet werden, um Nachrichten vom Voicemailsystem zu empfangen und anschließend über SMTP an die Cloud weiterzuleiten. Da viele Voicemailsysteme von Drittanbietern MAPI/CDO verwenden, um bei erweiterten UM-Funktionen mit Exchange Server zusammenzuarbeiten, ist unter Umständen nicht der gesamte Funktionsumfang dieser Systeme verfügbar, wenn SMTP für die Interoperabilität mit Exchange Online verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="47e39-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="47e39-p105">Die Exchange Online UM-Unterstützung für Nebenstellenanlagen von Drittanbietern über direkte Verbindungen von SBCs, die von Kunden betrieben werden, endet im Juli 2018. Weitere Informationen finden Sie im Blogbeitrag zur Einstellung des Supports für SBCs in Exchange Online UM unter [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/).</span><span class="sxs-lookup"><span data-stu-id="47e39-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="47e39-140">Skype for Business-Integration</span><span class="sxs-lookup"><span data-stu-id="47e39-140">Skype for Business integration</span></span>

<span data-ttu-id="47e39-p106">Organisationen können Skype for Business Online als eigenständigen Dienst oder als Teil von Microsoft Office 365 erwerben. Lokales Skype for Business 2015 wird ebenfalls unterstützt. Weitere Einzelheiten zu Skype for Business Online finden Sie unter [Skype for Business Online-Dienstbeschreibung](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="47e39-p106">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365. Skype for Business 2015 on-premises is also supported. To learn more about Skype for Business Online, see [Skype for Business Online Service Description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="47e39-144">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="47e39-144">Feature Availability</span></span>

<span data-ttu-id="47e39-145">Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="47e39-145">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

