---
title: Interoperabilität, Konnektivität und Kompatibilität
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 55cb63c948d6e5f98cea64f98d0ca9d3d8fcdc21
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467772"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="4f7a7-102">Interoperabilität, Konnektivität und Kompatibilität</span><span class="sxs-lookup"><span data-stu-id="4f7a7-102">Interoperability, Connectivity, and Compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="4f7a7-103">Interoperabilität mit anderen Microsoft-Produkten</span><span class="sxs-lookup"><span data-stu-id="4f7a7-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="4f7a7-104">Skype for Business Online</span><span class="sxs-lookup"><span data-stu-id="4f7a7-104">Skype for Business Online</span></span>

<span data-ttu-id="4f7a7-105">Bei Kunden, die Microsoft Lync Server 2010, Lync Server 2013 oder Microsoft Office Communications Server 2007 R2 lokal bereitgestellt haben, kann Microsoft Office Communicator eine Verbindung zu Microsoft Exchange Online mithilfe der Exchange-Webdienste herstellen, um auf Abwesenheitsnotizen und Kalenderdaten zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="4f7a7-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="4f7a7-106">Lokale Bereitstellungen von Lync Server 2010 und Lync Server 2013 unterstützen die Interoperabilität mit Exchange Online auf zwei Arten:</span><span class="sxs-lookup"><span data-stu-id="4f7a7-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="4f7a7-107">Sofortnachrichten- und Anwesenheits-Interoperabilität in Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="4f7a7-107">IM and presence interoperability in Outlook Web App</span></span>
    
- <span data-ttu-id="4f7a7-108">Interoperabilität von Voicemails</span><span class="sxs-lookup"><span data-stu-id="4f7a7-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="4f7a7-p101">Weitere Informationen zum Konfigurieren von Skype for Business Server 2015 mit Exchange Online finden Sie unter [Konfigurieren der Integration zwischen lokalem Skype for Business Server 2015 und Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). Informationen zu Hybridkonfigurationen finden Sie unter [Unterstützte Hybridkonfigurationen für Skype for Business Server 2015](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="4f7a7-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="4f7a7-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="4f7a7-111">Microsoft SharePoint</span></span>

<span data-ttu-id="4f7a7-112">Bei Kunden, die Microsoft SharePoint Server oder SharePoint Online als Teil eines Office 365-Abonnementplans bereitgestellt haben, kann SharePoint für integrierte Dienste eine Verbindung zu Exchange Online herstellen.</span><span class="sxs-lookup"><span data-stu-id="4f7a7-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an Office 365 subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="4f7a7-113">Weitere Informationen zum Verbinden von SharePoint mit Exchange Online finden Sie unter [Verwenden von SharePoint Online zusammen mit anderen Diensten in einer benutzerdefinierten Domäne](https://go.microsoft.com/fwlink/?LinkId=271805).</span><span class="sxs-lookup"><span data-stu-id="4f7a7-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="4f7a7-114">Funktionen für externe Konnektivität</span><span class="sxs-lookup"><span data-stu-id="4f7a7-114">Features for external connectivity</span></span>

<span data-ttu-id="4f7a7-115">Exchange Online bietet die folgenden Funktionen zum Herstellen einer Verbindung mit externen Anwendungen und Geräten:</span><span class="sxs-lookup"><span data-stu-id="4f7a7-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="4f7a7-p102">**Über Messaging-Protokolle wie MAPI-über-HTTP, SMTP, POP3, IMAP4 oder Exchange-Webdienste** Externe Anwendungen, die lokal, in Azure oder in anderen gehosteten Diensten ausgeführt werden, können auf mit Exchange Online gespeicherte Daten zugreifen, indem Messaging-Protokolle wie MAPI-über-HTTP, SMTP, POP3 und IMAP4 verwendet werden. Für die Anwendungsentwicklung werden Exchange-Webdienste oder die Exchange-Webdienste-MAPI empfohlen.</span><span class="sxs-lookup"><span data-stu-id="4f7a7-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="4f7a7-118">**Als SMTP-Relay** Exchange Online kann als ein SMTP-Zustellungsdienst eingerichtet werden, um von Fax-Gateways, Netzwerkgeräten und benutzerdefinierten Anwendungen gesendete E-Mail-Nachrichten weiterzugeben.</span><span class="sxs-lookup"><span data-stu-id="4f7a7-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="4f7a7-119">Exchange-Webdienste</span><span class="sxs-lookup"><span data-stu-id="4f7a7-119">Exchange Web Services</span></span>

<span data-ttu-id="4f7a7-p103">Exchange-Webdienste (Exchange Web Services, EWS) ist die bevorzugte Entwicklungs-API für Exchange Server und Exchange Online. Mit Exchange-Webdienste oder der Exchange-Webdienste-MAPI können Administratoren auf mit Exchange Online gespeicherte Daten aus Anwendungen zugreifen, die lokal in Azure oder in anderen gehosteten Diensten ausgeführt werden. Mit Exchange-Webdiensten können Administratoren spezielle Aktionen ausführen, z. B. Inhalte eines Postfachs abfragen, ein Kalenderereignis veröffentlichen, eine Aufgabe erstellen oder eine bestimmte Aktion basierend auf dem Inhalt einer E-Mail-Nachricht auslösen. Exchange Online aktiviert Exchange-Webdienste-Funktionen, indem Kundenkonten Anwendungsberechtigungen gewährt werden. Diese Berechtigungen ermöglichen es der Kundenanwendung, auf das Anwendungspostfach zuzugreifen und Inhalte hinzuzufügen. Exchange-Identitätswechsel ist eine Methode, um Anwendungsberechtigungen zu gewähren. Informationen dazu, wie Sie Exchange-Webdienste mit Exchange Online verwenden können, finden Sie in den technischen Artikeln im Exchange Online Developer Center.</span><span class="sxs-lookup"><span data-stu-id="4f7a7-p103">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online. Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services. EWS enables administrators to perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message. Exchange Online enables EWS functionality by granting application permissions to customer accounts. These permissions allow the customer application to access the application mailbox and add content. Exchange Impersonation is one method used to grant application permissions. For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="4f7a7-127">SMTP-Relay</span><span class="sxs-lookup"><span data-stu-id="4f7a7-127">SMTP relay</span></span>

<span data-ttu-id="4f7a7-p104">Exchange Online kann als ein SMTP-Zustelldienst verwendet werden, um von Fax-Gateways, Netzwerkgeräten und benutzerdefinierten Anwendungen gesendete E-Mail-Nachrichten weiterzugeben. Wenn beispielsweise eine Branchenanwendung E-Mail-Alarme an Benutzer sendet, kann sie so konfiguriert werden, dass Exchange Online als Mail-Zustellsystem verwendet wird. Die Anwendung oder der Dienst muss mit dem Benutzernamen und Kennwort eines gültigen, lizenzierten Exchange Online-Postfachs authentifiziert und mittels Transport Layer Security (TLS) verbunden werden.</span><span class="sxs-lookup"><span data-stu-id="4f7a7-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="4f7a7-131">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="4f7a7-131">Feature Availability</span></span>

<span data-ttu-id="4f7a7-132">Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="4f7a7-132">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

