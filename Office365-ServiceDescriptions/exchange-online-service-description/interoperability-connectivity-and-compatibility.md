---
title: Interoperabilität, Konnektivität und Kompatibilität
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 21df7d4747ae0b92f21a9da56c0d4bc9ff96ccaf
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173320"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interoperabilität, Konnektivität und Kompatibilität

## <a name="interoperability-with-other-microsoft-products"></a>Interoperabilität mit anderen Microsoft-Produkten

### <a name="skype-for-business-online"></a>Skype for Business Online

Bei Kunden, die Microsoft Lync Server 2010, Lync Server 2013 oder Microsoft Office Communications Server 2007 R2 lokal bereitgestellt haben, kann Microsoft Office Communicator eine Verbindung zu Microsoft Exchange Online mithilfe der Exchange-Webdienste herstellen, um auf Abwesenheitsnotizen und Kalenderdaten zuzugreifen.
  
Lokale Bereitstellungen von Lync Server 2010 und Lync Server 2013 unterstützen die Interoperabilität mit Exchange Online auf zwei Arten:
  
- Interoperabilität von Im- und Anwesenheitsinformationen in Outlook im Web
    
- Interoperabilität von Voicemails
    
Weitere Informationen zum Konfigurieren von Skype for Business Server 2015 mit Exchange Online finden Sie unter [Konfigurieren der Integration zwischen lokalem Skype for Business Server 2015 und Exchange Online](/skypeforbusiness/deploy/integrate-with-exchange-server/outlook-web-app). Informationen zu Hybridkonfigurationen finden Sie unter [Unterstützte Hybridkonfigurationen für Skype for Business Server 2015](/skypeforbusiness/skype-for-business-hybrid-solutions/integration-with-exchange-and-sharepoint).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Für Kunden, die Microsoft SharePoint Server oder SharePoint Online als Teil eines Abonnementplans bereitgestellt haben, kann SharePoint eine Verbindung mit Exchange Online für integrierte Dienste herstellen.
  
Weitere Informationen zum Verbinden von SharePoint mit Exchange Online finden Sie unter [Verwenden von SharePoint Online zusammen mit anderen Diensten in einer benutzerdefinierten Domäne](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Funktionen für externe Konnektivität

Exchange Online bietet die folgenden Funktionen zum Herstellen einer Verbindung mit externen Anwendungen und Geräten:
  
- **Über Messaging-Protokolle wie MAPI-über-HTTP, SMTP, POP3, IMAP4 oder Exchange-Webdienste** Externe Anwendungen, die lokal, in Azure oder in anderen gehosteten Diensten ausgeführt werden, können auf mit Exchange Online gespeicherte Daten zugreifen, indem Messaging-Protokolle wie MAPI-über-HTTP, SMTP, POP3 und IMAP4 verwendet werden. Für die Anwendungsentwicklung werden Exchange-Webdienste oder die Exchange-Webdienste-MAPI empfohlen. 
    
- **Als SMTP-Relay** Exchange Online kann als ein SMTP-Zustellungsdienst eingerichtet werden, um von Fax-Gateways, Netzwerkgeräten und benutzerdefinierten Anwendungen gesendete E-Mail-Nachrichten weiterzugeben. 
    
### <a name="exchange-web-services"></a>Exchange-Webdienste

Exchange-Webdienste (Exchange Web Services, EWS) ist die bevorzugte Entwicklungs-API für Exchange Server und Exchange Online. Mithilfe von EWS oder der verwalteten EWS-API können Administratoren über Anwendungen, die lokal, in Azure oder in anderen gehosteten Diensten ausgeführt werden, auf mit Exchange Online gespeicherte Daten zugreifen. MIT EWS können Administratoren spezielle Aktionen ausführen, z. B. das Abfragen des Inhalts eines Postfachs, das Veröffentlichen eines Kalenderereigniss, das Erstellen einer Aufgabe oder das Auslösen einer bestimmten Aktion basierend auf dem Inhalt einer E-Mail-Nachricht. Exchange Online aktiviert Exchange-Webdienste-Funktionen, indem Kundenkonten Anwendungsberechtigungen gewährt werden. Diese Berechtigungen ermöglichen es der Kundenanwendung, auf das Anwendungspostfach zuzugreifen und Inhalte hinzuzufügen. Exchange-Identitätswechsel ist eine Methode, um Anwendungsberechtigungen zu gewähren. Informationen dazu, wie Sie Exchange-Webdienste mit Exchange Online verwenden können, finden Sie in den technischen Artikeln im Exchange Online Developer Center.
  
### <a name="smtp-relay"></a>SMTP-Relay

Exchange Online kann als ein SMTP-Zustelldienst verwendet werden, um von Fax-Gateways, Netzwerkgeräten und benutzerdefinierten Anwendungen gesendete E-Mail-Nachrichten weiterzugeben. Wenn beispielsweise eine Branchenanwendung E-Mail-Alarme an Benutzer sendet, kann sie so konfiguriert werden, dass Exchange Online als Mail-Zustellsystem verwendet wird. Die Anwendung oder der Dienst muss mit dem Benutzernamen und Kennwort eines gültigen, lizenzierten Exchange Online-Postfachs authentifiziert und mittels Transport Layer Security (TLS) verbunden werden.
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
