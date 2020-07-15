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
ms.openlocfilehash: a6245acdeaeda173f1a675d1ce34d9086e3f077a
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132549"
---
# <a name="voice-message-services"></a>Sprachnachrichtendienste

## <a name="voice-mail"></a>Voicemail

Microsoft Exchange Online bietet gehostete Voicemaildienste mit folgenden Funktionen:
  
- Mailboxansage (Voicemail)
    
- Einwahlbenutzerschnittstelle zu Exchange (Outlook Voice Access)
    
- Einwahlschnittstelle für Anrufer (automatische Telefonzentrale)
    
Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.
  
The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:
  
- Wiedergabe über Telefon in Outlook und Outlook im Web.
    
- Benachrichtigungen über verpasste Anrufe.
    
- Anrufer-ID (mithilfe der Informationen in der globale Adressliste, den persönlichen Kontakten der Benutzer, dem benutzerdefinierten Ordner "Kontakte" und Kontakten aus externen sozialen Netzwerken).
    
- Zurücksetzen der Voicemail-PIN aus Outlook im Web und Outlook (Details siehe [Zurücksetzen einer Voicemail-PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328))
    
- Message Waiting Indicator (Details siehe [MWI in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271794)) 
    
- Mailboxansageregeln (Weitere Informationen finden Sie unter [Allow Voice Mail users to forward Calls](https://go.microsoft.com/fwlink/p/?LinkId=271795) for Details).
    
- Geschützte Voicemail in Exchange Online (Weitere Informationen finden Sie unter [Protect Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) for Details).
    
- Voicemailvorschau (siehe [zulassen, dass Benutzer ein Voicemail-Transkript](https://go.microsoft.com/fwlink/p/?LinkId=271797) für eine Liste unterstützter Sprachen anzeigen können).
    
- Sprachzugriff auf E-Mail, Voicemail, Kalender, persönliche Kontakte und persönliche Kontaktgruppen.
    
- Verzeichnissuche über Outlook Voice Access oder automatische Telefonzentrale.
    
- Administratoren konfigurieren und verwalten die Interoperabilität von Voicemessagingdiensten mithilfe der Exchange-Verwaltungskonsole.
    
Weitere Informationen zu Voicemail-Funktionen finden Sie unter [Voicemail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> Die automatische Spracherkennung (ASR) ist nicht verfügbar in der Menünavigation oder Verzeichnissuche für Outlook Voice Access-Benutzer oder Anrufer bei der automatischen Telefonzentrale, die Sprachbefehle verwenden. 
>
> Der Kunde muss eine telefonieverbindung aus dem Festnetz (Public Switched Telephone Network, PSTN) mit einem VoIP-Gateway und einer Nebenstellenanlage, einer IP-Nebenstellenanlage oder Skype for Business Server 2015 bereitstellen. 
>
> The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. 
>
> Gehostete Voicemail steht nur Exchange Online Plan 2-und Office 365 Enterprise E3-Abonnenten zur Verfügung. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilität von Voicemails eines Drittanbieters

On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>Skype for Business-Integration

Organisationen können Skype for Business Online als eigenständigen Dienst oder als Teil von Microsoft Office 365 erwerben. Lokales Skype for Business 2015 wird ebenfalls unterstützt. Weitere Informationen zu Skype for Business Online finden Sie unter [Skype for Business Online-Dienstbeschreibung](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  

