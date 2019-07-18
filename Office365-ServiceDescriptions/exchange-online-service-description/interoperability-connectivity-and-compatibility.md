---
title: Interoperabilität, Konnektivität und Kompatibilität
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 38ab8f7baf16c5bf837bca9310a0d34a5e25469f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776796"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interoperabilität, Konnektivität und Kompatibilität

## <a name="interoperability-with-other-microsoft-products"></a>Interoperabilität mit anderen Microsoft-Produkten

### <a name="skype-for-business-online"></a>Skype for Business Online

Bei Kunden, die Microsoft Lync Server 2010, Lync Server 2013 oder Microsoft Office Communications Server 2007 R2 lokal bereitgestellt haben, kann Microsoft Office Communicator eine Verbindung zu Microsoft Exchange Online mithilfe der Exchange-Webdienste herstellen, um auf Abwesenheitsnotizen und Kalenderdaten zuzugreifen.
  
Lokale Bereitstellungen von Lync Server 2010 und Lync Server 2013 unterstützen die Interoperabilität mit Exchange Online auf zwei Arten:
  
- Sofortnachrichten- und Anwesenheits-Interoperabilität in Outlook Web App
    
- Interoperabilität von Voicemails
    
Weitere Informationen zum Konfigurieren von Skype for Business Server 2015 mit Exchange Online finden Sie unter [Konfigurieren der Integration zwischen lokalem Skype for Business Server 2015 und Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). Informationen zu Hybridkonfigurationen finden Sie unter [Unterstützte Hybridkonfigurationen für Skype for Business Server 2015](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Bei Kunden, die Microsoft SharePoint Server oder SharePoint Online als Teil eines Office 365-Abonnementplans bereitgestellt haben, kann SharePoint für integrierte Dienste eine Verbindung zu Exchange Online herstellen.
  
Weitere Informationen zum Verbinden von SharePoint mit Exchange Online finden Sie unter [Verwenden von SharePoint Online zusammen mit anderen Diensten in einer benutzerdefinierten Domäne](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Funktionen für externe Konnektivität

Exchange Online bietet die folgenden Funktionen zum Herstellen einer Verbindung mit externen Anwendungen und Geräten:
  
- **Über Messaging-Protokolle wie MAPI-über-HTTP, SMTP, POP3, IMAP4 oder Exchange-Webdienste** Externe Anwendungen, die lokal, in Azure oder in anderen gehosteten Diensten ausgeführt werden, können auf mit Exchange Online gespeicherte Daten zugreifen, indem Messaging-Protokolle wie MAPI-über-HTTP, SMTP, POP3 und IMAP4 verwendet werden. Für die Anwendungsentwicklung werden Exchange-Webdienste oder die Exchange-Webdienste-MAPI empfohlen. 
    
- **Als SMTP-Relay** Exchange Online kann als ein SMTP-Zustellungsdienst eingerichtet werden, um von Fax-Gateways, Netzwerkgeräten und benutzerdefinierten Anwendungen gesendete E-Mail-Nachrichten weiterzugeben. 
    
### <a name="exchange-web-services"></a>Exchange-Webdienste

Exchange-Webdienste (Exchange Web Services, EWS) ist die bevorzugte Entwicklungs-API für Exchange Server und Exchange Online. Mit Exchange-Webdienste oder der Exchange-Webdienste-MAPI können Administratoren auf mit Exchange Online gespeicherte Daten aus Anwendungen zugreifen, die lokal in Azure oder in anderen gehosteten Diensten ausgeführt werden. Mit Exchange-Webdiensten können Administratoren spezielle Aktionen ausführen, z. B. Inhalte eines Postfachs abfragen, ein Kalenderereignis veröffentlichen, eine Aufgabe erstellen oder eine bestimmte Aktion basierend auf dem Inhalt einer E-Mail-Nachricht auslösen. Exchange Online aktiviert Exchange-Webdienste-Funktionen, indem Kundenkonten Anwendungsberechtigungen gewährt werden. Diese Berechtigungen ermöglichen es der Kundenanwendung, auf das Anwendungspostfach zuzugreifen und Inhalte hinzuzufügen. Exchange-Identitätswechsel ist eine Methode, um Anwendungsberechtigungen zu gewähren. Informationen dazu, wie Sie Exchange-Webdienste mit Exchange Online verwenden können, finden Sie in den technischen Artikeln im Exchange Online Developer Center.
  
### <a name="smtp-relay"></a>SMTP-Relay

Exchange Online kann als ein SMTP-Zustelldienst verwendet werden, um von Fax-Gateways, Netzwerkgeräten und benutzerdefinierten Anwendungen gesendete E-Mail-Nachrichten weiterzugeben. Wenn beispielsweise eine Branchenanwendung E-Mail-Alarme an Benutzer sendet, kann sie so konfiguriert werden, dass Exchange Online als Mail-Zustellsystem verwendet wird. Die Anwendung oder der Dienst muss mit dem Benutzernamen und Kennwort eines gültigen, lizenzierten Exchange Online-Postfachs authentifiziert und mittels Transport Layer Security (TLS) verbunden werden.
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description.md).
  

