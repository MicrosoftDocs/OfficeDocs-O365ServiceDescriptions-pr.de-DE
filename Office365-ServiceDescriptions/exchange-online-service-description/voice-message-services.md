---
title: Sprachnachrichten Dienste
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: c1df4da5a1877728b3060e5605071d8175d1c503
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262688"
---
# <a name="voice-message-services"></a>Sprachnachrichten Dienste

## <a name="voice-mail"></a>Voicemail

Microsoft Exchange Online bietet gehostete Voicemaildienste mit folgenden Funktionen:
  
- Mailboxansage (Voicemail)
    
- Einwahlbenutzerschnittstelle zu Exchange (Outlook Voice Access)
    
- Einwahlschnittstelle für Anrufer (automatische Telefonzentrale)
    
Gehostete Voicemessagingdienste erlauben einer Firma, ihre lokale Telefonanlage mit Voicemaildiensten von Exchange Online zu verbinden. Voicemailnachrichten werden aufgezeichnet und in der Exchange Online-Infrastruktur gespeichert. Benutzer können ihre Sprachnachrichten mit Outlook, Outlook im Web oder Mobiltelefonen abrufen. Alle Telefonieverbindungen zu Exchange Online erfordern Voice over IP-(VoIP-)Protokolle. Administratoren können lokale IP-Nebenstellenanlagen oder Nebenstellensysteme mithilfe von VoIP-Mediagateways und SBCs (Session Border Controllers) mit Exchange Online verbinden. Ein VoIP-Mediagateway ist nicht erforderlich, wenn der Kunde eine IP-Nebenstellenanlage bereitgestellt hat oder wenn eine Nebenstellenanlage direkt VoIP unterstützt und zusammen mit Exchange-Voicemessagingdiensten verwendet werden kann. SBCs werden innerhalb des Kundennetzwerks bereitgestellt, um ein lokales Telefonienetzwerk anzuschließen und die Kommunikation (und das Kundennetzwerk) vor Abhör- und Eindringversuchen zu schützen. Interoperabilität mit den Sprachfunktionen von Microsoft Lync Server 2010 und 2013 wird ebenfalls unterstützt.
  
Die Features der Voicemessagingdienste in Exchange Online sind mit den Features im lokalen Exchange Server 2016 vergleichbar. Dazu zählen:
  
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
> Der Kunde muss die lokalen SBC-Hardwaregeräte bereitstellen und sicherstellen, dass die SBCs ordnungsgemäß konfiguriert sind, um eine Verbindung zu den Online-Voicemaildiensten herzustellen. Dazu gehört das Konfigurieren der entsprechenden Sicherheitsebene, indem Zertifikate sowie öffentliche und private IP-Schnittstellen verwendet und die richtigen TCP-Ports in den lokalen Firewalls aktiviert werden. 
>
> Gehostete Voicemail steht nur Exchange Online Plan 2-und Office 365 Enterprise E3-Abonnenten zur Verfügung. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilität von Voicemails eines Drittanbieters

Lokale Voicemaillösungen von Drittanbietern können mit Exchange Online zusammenarbeiten, wenn sie Sprachnachrichten über SMTP weiterleiten können oder Microsoft Exchange-Webdienste unterstützen. Wenn das Voicemailsystem keine eigene Unterstützung für das Weiterleiten von Sprachnachrichten über SMTP bietet, kann ein lokaler E-Mail-Server weiterverwendet werden, um Nachrichten vom Voicemailsystem zu empfangen und anschließend über SMTP an die Cloud weiterzuleiten. Da viele Voicemailsysteme von Drittanbietern MAPI/CDO verwenden, um bei erweiterten UM-Funktionen mit Exchange Server zusammenzuarbeiten, ist unter Umständen nicht der gesamte Funktionsumfang dieser Systeme verfügbar, wenn SMTP für die Interoperabilität mit Exchange Online verwendet wird.
  
> [!NOTE]
> Die Exchange Online UM-Unterstützung für Nebenstellenanlagen von Drittanbietern über direkte Verbindungen von SBCs, die von Kunden betrieben werden, endet im Juli 2018. Weitere Informationen finden Sie im Blogbeitrag zur Einstellung des Supports für SBCs in Exchange Online UM unter [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117). 
  
## <a name="skype-for-business-integration"></a>Skype for Business-Integration

Organisationen können Skype for Business Online als eigenständigen Dienst oder als Teil von Microsoft Office 365 erwerben. Lokales Skype for Business 2015 wird ebenfalls unterstützt. Weitere Informationen zu Skype for Business Online finden Sie unter [Skype for Business Online-Dienstbeschreibung](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  

