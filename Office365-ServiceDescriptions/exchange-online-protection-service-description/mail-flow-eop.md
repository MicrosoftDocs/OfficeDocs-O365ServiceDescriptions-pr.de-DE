---
title: Nachrichtenfluss [EoP]
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Im Falle der meisten Organisationen, die Office 365 verwenden, hosten wir die Postfächer und übernehmen die Abwicklung des E-Mail-Flusses. Das ist die einfachste Konfiguration und bedeutet, dass alle Postfächer und die gesamte Filterung von Office 365 verwaltet werden. Einige Organisationen jedoch müssen aufgrund geschäftlicher Anforderungen alle ihre Postfächer lokal hosten. Mit Exchange Online Protection (EoP) können Sie dies tun und in der Cloud Antivirus-und Antispam-e-Mail-Verarbeitung bereitstellen.
ms.openlocfilehash: c6a41df3e8b8c157d599f6a9d55be4b7f826e1d9
ms.sourcegitcommit: b957054b6d0a96dbb2b9ced39b5c9935aa07111c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2020
ms.locfileid: "42545818"
---
# <a name="mail-floweop"></a>Nachrichtenfluss [EoP]

Im Falle der meisten Organisationen, die Office 365 verwenden, hosten wir die Postfächer und übernehmen die Abwicklung des E-Mail-Flusses. Das ist die einfachste Konfiguration und bedeutet, dass alle Postfächer und die gesamte Filterung von Office 365 verwaltet werden. Einige Organisationen jedoch müssen aufgrund geschäftlicher Anforderungen alle ihre Postfächer lokal hosten. Mit Exchange Online Protection (EoP) können Sie dies tun und in der Cloud Antivirus-und Antispam-e-Mail-Verarbeitung bereitstellen. Weitere Informationen zu EOP und den entsprechenden Kaufmodalitäten finden Sie unter [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Sie suchen nach Informationen zu Domänenverwaltung oder verzeichnisbasierter Edge-Blockierung (Directory Based Edge Blocking, DBEB)? Siehe [Empfänger-, Domänen-und Unternehmensverwaltung](recipient-domain-and-company-management.md). Weitere Informationen zu allen EoP-Features finden Sie in der [Beschreibung des Exchange Online Protection-Diensts](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Weiterleiten von E-Mails zwischen Office 365 und eigenen E-Mail-Servern

Sie können einen Connector konfigurieren, um einen E-Mail-Fluss zwischen Office 365 (einschließlich Exchange Online oder EOP) und einem SMTP-basierten E-Mail-Server wie Exchange möglich zu machen. Details hierzu finden Sie unter [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? und [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Sichere Nachrichten mit einem vertrauenswürdigen Partner

Als EoP-Kunde können Sie einen sicheren e-Mail-Fluss mit einem vertrauenswürdigen Partner mithilfe von Office 365-Konnektoren einrichten. Office 365 unterstützt die sichere Kommunikation über TLS (Transport Layer Security) und Sie können einen Connector erstellen, um die Verschlüsselung über TLS zu erzwingen. [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) ist ein kryptografisches Protokoll, das Sicherheit für die Kommunikation über das Internet bietet. Mithilfe von Connectors können Sie sowohl erzwungene eingehende als auch ausgehende TLS-Zertifikate mit selbstsignierten oder Zertifizierungsstellen validierten Zertifikaten konfigurieren. Sie können auch andere Sicherheitseinschränkungen anwenden, beispielsweise die Angabe von Domänennamen oder IP-Adressbereichen, aus denen Ihre Partnerorganisation e-Mails sendet. 
  
Weitere Informationen finden Sie unter [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Übernehmen der IP-Adresse eines Partners in die Liste für sichere Absender (Safe List)

Sie können die IP-Adresse eines vertrauenswürdigen Partners in eine Liste sicherer Absender aufnehmen, um zu gewährleisten, dass Nachrichten von diesem Partner von der Spamfilterung ausgenommen werden. Verwenden Sie dazu die Liste zugelassener IP-Adressen des Verbindungsfilters. Weitere Informationen finden Sie unter [Konfigurieren der Verbindungsfilterrichtlinie](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Bedingtes E-Mail-Routing

Sie können einen Connector mit einer Transportegel konfigurieren, die E-Mails basierend auf bestimmten Bedingungen an einen spezifischen Standort weiterleitet. Weitere Informationen finden Sie unter [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Hybrides E-Mail-Routing

Hybrid bedeutet, dass ein Teil Ihrer Postfächer lokal gehostet wird, der andere in der Cloud (Exchange Online). Sie können von einer eigenständigen (lokalen) Bereitstellung zu einer hybriden Bereitstellung wechseln.
  
In einer hybriden Bereitstellung können Sie Ihre cloudbasierten und lokalen Postfächer mit EOP schützen. Für lokale Postfächer sind eigenständige Lizenzen erforderlich, wenn sie von EOP geschützt werden. Weitere Informationen zum E-Mail-Routing in einer hybriden Bereitstellung finden Sie unter [Transportweiterleitung in Exchange-Hybrid-Bereitstellungen](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
Im [Bereitstellungs-Assistent für Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) finden Sie darüber hinaus detaillierte Anleitungen zu Hybridbereitstellungen und zum Hybridnachrichtentransport. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).
