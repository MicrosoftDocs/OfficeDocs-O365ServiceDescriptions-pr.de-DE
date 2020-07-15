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
ms.openlocfilehash: 5308770ff7fc6ab6c44f27293ff89ebbffa6e72f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132749"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="4ca94-102">Interoperabilität, Konnektivität und Kompatibilität</span><span class="sxs-lookup"><span data-stu-id="4ca94-102">Interoperability, connectivity, and compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="4ca94-103">Interoperabilität mit anderen Microsoft-Produkten</span><span class="sxs-lookup"><span data-stu-id="4ca94-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="4ca94-104">Skype for Business Online</span><span class="sxs-lookup"><span data-stu-id="4ca94-104">Skype for Business Online</span></span>

<span data-ttu-id="4ca94-105">Bei Kunden, die Microsoft Lync Server 2010, Lync Server 2013 oder Microsoft Office Communications Server 2007 R2 lokal bereitgestellt haben, kann Microsoft Office Communicator eine Verbindung zu Microsoft Exchange Online mithilfe der Exchange-Webdienste herstellen, um auf Abwesenheitsnotizen und Kalenderdaten zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="4ca94-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="4ca94-106">Lokale Bereitstellungen von Lync Server 2010 und Lync Server 2013 unterstützen die Interoperabilität mit Exchange Online auf zwei Arten:</span><span class="sxs-lookup"><span data-stu-id="4ca94-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="4ca94-107">Interoperabilität von Sofortnachrichten und Anwesenheit in Outlook im Internet</span><span class="sxs-lookup"><span data-stu-id="4ca94-107">IM and presence interoperability in Outlook on the web</span></span>
    
- <span data-ttu-id="4ca94-108">Interoperabilität von Voicemails</span><span class="sxs-lookup"><span data-stu-id="4ca94-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="4ca94-109">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804).</span><span class="sxs-lookup"><span data-stu-id="4ca94-109">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804).</span></span> <span data-ttu-id="4ca94-110">For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="4ca94-110">For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="4ca94-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="4ca94-111">Microsoft SharePoint</span></span>

<span data-ttu-id="4ca94-112">Für Kunden, die Microsoft SharePoint Server oder SharePoint Online im Rahmen eines Abonnementplans bereitgestellt haben, kann SharePoint eine Verbindung mit Exchange Online für integrierte Dienste herstellen.</span><span class="sxs-lookup"><span data-stu-id="4ca94-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="4ca94-113">Weitere Informationen zum Verbinden von SharePoint mit Exchange Online finden Sie unter [Verwenden von SharePoint Online zusammen mit anderen Diensten in einer benutzerdefinierten Domäne](https://go.microsoft.com/fwlink/?LinkId=271805).</span><span class="sxs-lookup"><span data-stu-id="4ca94-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="4ca94-114">Funktionen für externe Konnektivität</span><span class="sxs-lookup"><span data-stu-id="4ca94-114">Features for external connectivity</span></span>

<span data-ttu-id="4ca94-115">Exchange Online bietet die folgenden Funktionen zum Herstellen einer Verbindung mit externen Anwendungen und Geräten:</span><span class="sxs-lookup"><span data-stu-id="4ca94-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="4ca94-116">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4.</span><span class="sxs-lookup"><span data-stu-id="4ca94-116">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4.</span></span> <span data-ttu-id="4ca94-117">Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span><span class="sxs-lookup"><span data-stu-id="4ca94-117">Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="4ca94-118">**Als SMTP-Relay** Exchange Online kann als ein SMTP-Zustellungsdienst eingerichtet werden, um von Fax-Gateways, Netzwerkgeräten und benutzerdefinierten Anwendungen gesendete E-Mail-Nachrichten weiterzugeben.</span><span class="sxs-lookup"><span data-stu-id="4ca94-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="4ca94-119">Exchange-Webdienste</span><span class="sxs-lookup"><span data-stu-id="4ca94-119">Exchange Web Services</span></span>

<span data-ttu-id="4ca94-120">Exchange-Webdienste (Exchange Web Services, EWS) ist die bevorzugte Entwicklungs-API für Exchange Server und Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="4ca94-120">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online.</span></span> <span data-ttu-id="4ca94-121">Mithilfe von EWS oder der verwaltete EWS-API können Administratoren auf Daten zugreifen, die mit Exchange Online von Anwendungen gespeichert werden, die lokal, in Azure oder in anderen gehosteten Diensten ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="4ca94-121">Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> <span data-ttu-id="4ca94-122">Mit EWS können Administratoren spezielle Aktionen durchführen, beispielsweise das Abfragen des Inhalts eines Postfachs, das Veröffentlichen eines Kalenderereignisses, das Erstellen einer Aufgabe oder das Auslösen einer bestimmten Aktion basierend auf dem Inhalt einer e-Mail-Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4ca94-122">EWS lets administrators perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message.</span></span> <span data-ttu-id="4ca94-123">Exchange Online aktiviert Exchange-Webdienste-Funktionen, indem Kundenkonten Anwendungsberechtigungen gewährt werden.</span><span class="sxs-lookup"><span data-stu-id="4ca94-123">Exchange Online enables EWS functionality by granting application permissions to customer accounts.</span></span> <span data-ttu-id="4ca94-124">Diese Berechtigungen ermöglichen es der Kundenanwendung, auf das Anwendungspostfach zuzugreifen und Inhalte hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="4ca94-124">These permissions allow the customer application to access the application mailbox and add content.</span></span> <span data-ttu-id="4ca94-125">Exchange-Identitätswechsel ist eine Methode, um Anwendungsberechtigungen zu gewähren.</span><span class="sxs-lookup"><span data-stu-id="4ca94-125">Exchange Impersonation is one method used to grant application permissions.</span></span> <span data-ttu-id="4ca94-126">Informationen dazu, wie Sie Exchange-Webdienste mit Exchange Online verwenden können, finden Sie in den technischen Artikeln im Exchange Online Developer Center.</span><span class="sxs-lookup"><span data-stu-id="4ca94-126">For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="4ca94-127">SMTP-Relay</span><span class="sxs-lookup"><span data-stu-id="4ca94-127">SMTP relay</span></span>

<span data-ttu-id="4ca94-128">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span><span class="sxs-lookup"><span data-stu-id="4ca94-128">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> <span data-ttu-id="4ca94-129">For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system.</span><span class="sxs-lookup"><span data-stu-id="4ca94-129">For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system.</span></span> <span data-ttu-id="4ca94-130">The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span><span class="sxs-lookup"><span data-stu-id="4ca94-130">The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="4ca94-131">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="4ca94-131">Feature availability</span></span>

<span data-ttu-id="4ca94-132">Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="4ca94-132">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

