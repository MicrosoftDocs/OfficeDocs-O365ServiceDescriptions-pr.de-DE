---
title: Nachrichtenfluss in Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: In diesem Artikel erfahren Sie mehr über den Nachrichtenfluss in Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 0923f31ccb639271303654cbdccf4890b2a55062
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653137"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Nachrichtenfluss in Exchange Online Protection

Für die meisten Organisationen, die Microsoft verwenden, hosten wir Ihre Postfächer und kümmern uns um den Nachrichtenfluss. Dies ist die einfachste Konfiguration und bedeutet, dass Microsoft alle Postfächer und Filter verwaltet. Einige Organisationen jedoch müssen aufgrund geschäftlicher Anforderungen alle ihre Postfächer lokal hosten. Exchange Online Protection (EOP) können Sie dies tun und bietet Antivirus- und Antispam-E-Mail-Verarbeitung in der Cloud. Weitere Informationen zu EOP und den entsprechenden Kaufmodalitäten finden Sie unter [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
Sie suchen nach Informationen zu Domänenverwaltung oder verzeichnisbasierter Edge-Blockierung (Directory Based Edge Blocking, DBEB)? Weitere Informationen finden Sie [unter Recipient, domain, and company management](recipient-domain-and-company-management.md). Weitere Informationen zu allen EOP-Features finden Sie unter [Exchange Online Protection Dienstbeschreibung](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Weiterleiten von E-Mails zwischen Microsoft und Ihren eigenen E-Mail-Servern

Sie können einen Connector konfigurieren, um den Nachrichtenfluss zwischen Microsoft (einschließlich Exchange Online oder EOP) und einem SMTP-basierten E-Mail-Server wie Exchange. Details hierzu finden Sie unter [Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)? Und [Richten Sie Connectors ein, um E-Mails zwischen Microsoft und Ihren eigenen E-Mail-Servern weiter zu routen.](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Als EOP-Kunde können Sie einen sicheren E-Mail-Fluss mit einem vertrauenswürdigen Partner mithilfe von Microsoft Connectors einrichten. Microsoft unterstützt die sichere Kommunikation über Transport Layer Security (TLS), und Sie können einen Connector erstellen, um die Verschlüsselung über TLS zu erzwingen. [TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) ist ein kryptografisches Protokoll, das Sicherheit für die Kommunikation über das Internet bietet. Mithilfe von Connectors können Sie sowohl erzwungene ein- als auch ausgehende TLS mithilfe von selbst signierten oder zertifizierungsstellen-validierten Zertifikaten konfigurieren. Sie können auch andere Sicherheitseinschränkungen anwenden, z. B. das Angeben von Domänennamen oder IP-Adressbereichen, von denen Ihre Partnerorganisation E-Mails sendet. 
  
Weitere Informationen finden Sie unter [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Übernehmen der IP-Adresse eines Partners in die Liste für sichere Absender (Safe List)

Sie können die IP-Adresse eines vertrauenswürdigen Partners in eine Liste sicherer Absender aufnehmen, um zu gewährleisten, dass Nachrichten von diesem Partner von der Spamfilterung ausgenommen werden. Verwenden Sie dazu die Liste zugelassener IP-Adressen des Verbindungsfilters. Weitere Informationen finden Sie unter [Konfigurieren der Verbindungsfilterrichtlinie](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy).
  
## <a name="conditional-mail-routing"></a>Bedingtes E-Mail-Routing

Sie können einen Connector mit einer Transportegel konfigurieren, die E-Mails basierend auf bestimmten Bedingungen an einen spezifischen Standort weiterleitet. Weitere Informationen finden Sie unter [Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Hybrides E-Mail-Routing

Hybrid bedeutet, dass ein Teil Ihrer Postfächer lokal gehostet wird, der andere in der Cloud (Exchange Online). Sie können von einer eigenständigen (lokalen) Bereitstellung zu einer hybriden Bereitstellung wechseln.
  
In einer hybriden Bereitstellung können Sie Ihre cloudbasierten und lokalen Postfächer mit EOP schützen. Für lokale Postfächer sind eigenständige Lizenzen erforderlich, wenn sie von EOP geschützt werden. Weitere Informationen zum E-Mail-Routing in einer hybriden Bereitstellung finden Sie unter [Transportweiterleitung in Exchange-Hybrid-Bereitstellungen](/exchange/transport-routing).
  
Im [Bereitstellungs-Assistent für Microsoft Exchange Server](/exchange/exchange-deployment-assistant) finden Sie darüber hinaus detaillierte Anleitungen zu Hybridbereitstellungen und zum Hybridnachrichtentransport. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie [unter Exchange Online Protection Service description](exchange-online-protection-service-description.md).