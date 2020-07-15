---
title: Nachrichtenfluss [EoP]
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Im Falle der meisten Organisationen, die Office 365 verwenden, hosten wir die Postfächer und übernehmen die Abwicklung des E-Mail-Flusses. Dies ist die einfachste Konfiguration und bedeutet, dass Microsoft alle Postfächer und Filterung verwaltet. Einige Organisationen jedoch müssen aufgrund geschäftlicher Anforderungen alle ihre Postfächer lokal hosten. Mit Exchange Online Protection (EoP) können Sie dies tun und in der Cloud Antivirus-und Antispam-e-Mail-Verarbeitung bereitstellen.
ms.openlocfilehash: 751551ef6b3ae710646b2fb63960eee5983d6c47
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132819"
---
# <a name="mail-floweop"></a>Nachrichtenfluss [EoP]

Für die meisten Organisationen, die Microsoft verwenden, hosten wir Ihre Postfächer und kümmern uns um den Nachrichtenfluss. Dies ist die einfachste Konfiguration und bedeutet, dass Microsoft alle Postfächer und Filterung verwaltet. Einige Organisationen jedoch müssen aufgrund geschäftlicher Anforderungen alle ihre Postfächer lokal hosten. Mit Exchange Online Protection (EoP) können Sie dies tun und in der Cloud Antivirus-und Antispam-e-Mail-Verarbeitung bereitstellen. Weitere Informationen zu EOP und den entsprechenden Kaufmodalitäten finden Sie unter [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Sie suchen nach Informationen zu Domänenverwaltung oder verzeichnisbasierter Edge-Blockierung (Directory Based Edge Blocking, DBEB)? Siehe [Empfänger-, Domänen-und Unternehmensverwaltung](recipient-domain-and-company-management.md). Weitere Informationen zu allen EoP-Features finden Sie in der [Beschreibung des Exchange Online Protection-Diensts](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Weiterleiten von e-Mails zwischen Microsoft und ihren eigenen e-Mail-Servern

Sie können einen Connector so konfigurieren, dass der Nachrichtenfluss zwischen Microsoft (einschließlich Exchange Online oder EoP) und einem SMTP-basierten e-Mail-Server wie Exchange aktiviert wird. Details hierzu finden Sie unter [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? Und [Einrichten von Connectors zum Weiterleiten von e-Mails zwischen Microsoft und ihren eigenen e-Mail-Servern](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Als EoP-Kunde können Sie einen sicheren e-Mail-Fluss mit einem vertrauenswürdigen Partner mithilfe von Microsoft-Connectors einrichten. Microsoft unterstützt die sichere Kommunikation über TLS (Transport Layer Security) und Sie können einen Connector erstellen, um die Verschlüsselung über TLS zu erzwingen. [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) ist ein kryptografisches Protokoll, das Sicherheit für die Kommunikation über das Internet bietet. Mithilfe von Connectors können Sie sowohl erzwungene eingehende als auch ausgehende TLS-Zertifikate mit selbstsignierten oder Zertifizierungsstellen validierten Zertifikaten konfigurieren. Sie können auch andere Sicherheitseinschränkungen anwenden, beispielsweise die Angabe von Domänennamen oder IP-Adressbereichen, aus denen Ihre Partnerorganisation e-Mails sendet. 
  
Weitere Informationen finden Sie unter [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Übernehmen der IP-Adresse eines Partners in die Liste für sichere Absender (Safe List)

You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Bedingtes E-Mail-Routing

You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Hybrides E-Mail-Routing

Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.
  
If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
Im [Bereitstellungs-Assistent für Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) finden Sie darüber hinaus detaillierte Anleitungen zu Hybridbereitstellungen und zum Hybridnachrichtentransport. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).
