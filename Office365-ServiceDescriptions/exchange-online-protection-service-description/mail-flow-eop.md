---
title: E-Mail-Fluss[EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Im Falle der meisten Organisationen, die Office 365 verwenden, hosten wir die Postfächer und übernehmen die Abwicklung des E-Mail-Flusses. Das ist die einfachste Konfiguration und bedeutet, dass alle Postfächer und die gesamte Filterung von Office 365 verwaltet werden. Einige Organisationen jedoch müssen aufgrund geschäftlicher Anforderungen alle ihre Postfächer lokal hosten. Exchange Online Protection (EOP) macht das möglich und stellt cloudbasierte Antiviren- und Antispamfunktionen für E-Mails bereit. Weitere Informationen zu EOP und den entsprechenden Kaufmodalitäten finden Sie unter Exchange Online Protection.
ms.openlocfilehash: 0e9e5fffaa88b2ec654cb90dc5d432875336328e
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "33244911"
---
# <a name="mail-floweop"></a>E-Mail-Fluss[EOP]

Im Falle der meisten Organisationen, die Office 365 verwenden, hosten wir die Postfächer und übernehmen die Abwicklung des E-Mail-Flusses. Das ist die einfachste Konfiguration und bedeutet, dass alle Postfächer und die gesamte Filterung von Office 365 verwaltet werden. Einige Organisationen jedoch müssen aufgrund geschäftlicher Anforderungen alle ihre Postfächer lokal hosten. Exchange Online Protection (EOP) macht das möglich und stellt cloudbasierte Antiviren- und Antispamfunktionen für E-Mails bereit. Weitere Informationen zu EOP und den entsprechenden Kaufmodalitäten finden Sie unter [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).
  
Sie suchen nach Informationen zu Domänenverwaltung oder verzeichnisbasierter Edge-Blockierung (Directory Based Edge Blocking, DBEB)? Weitere Informationen finden Sie unter [Empfänger-, Domänen- und Unternehmensverwaltung](recipient-domain-and-company-management.md). Weitere Informationen zu allen EOP-Funktionen finden Sie unter [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Weiterleiten von E-Mails zwischen Office 365 und eigenen E-Mail-Servern
<a name="BKMK_outboundmailrouting"> </a>

Sie können einen Connector konfigurieren, um einen E-Mail-Fluss zwischen Office 365 (einschließlich Exchange Online oder EOP) und einem SMTP-basierten E-Mail-Server wie Exchange möglich zu machen. Details hierzu finden Sie unter [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? und [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

Als EOP-Kunde können Sie mithilfe von Office 365-Connectors einen sicheren E-Mail-Fluss mit einem vertrauenswürdigen Partner einrichten. Office 365 unterstützt die sichere Kommunikation über Transport Layer Security (TLS), und Sie können einen Connector erstellen, um TLS-Verschlüsselung zu erzwingen. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) ist ein kryptografisches Protokoll, das die Kommunikation über das Internet absichert. Mithilfe von Connectors können Sie TLS für eingehende und ausgehende Nachrichten erzwingen, basierend auf selbstsignierten Zertifikaten oder Zertifikaten, die von einer Zertifizierungsstelle validiert wurden. Sie können auch weitere Sicherheitseinschränkungen implementieren. Beispielsweise können Sie die Domänennamen oder IP-Adressbereiche angeben, über die Ihre Partnerorganisation E-Mails sendet. 
  
Weitere Informationen finden Sie unter [Einrichten von Connectors für den sicheren Nachrichtenfluss mit einer Partnerorganisation](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).
  
## <a name="safe-listing-a-partners-ip-address"></a>Übernehmen der IP-Adresse eines Partners in die Liste für sichere Absender (Safe List)
<a name="BKMK_safelistingapartnersipaddress"> </a>

Sie können die IP-Adresse eines vertrauenswürdigen Partners in eine Liste sicherer Absender aufnehmen, um zu gewährleisten, dass Nachrichten von diesem Partner von der Spamfilterung ausgenommen werden. Verwenden Sie dazu die Liste zugelassener IP-Adressen des Verbindungsfilters. Weitere Informationen finden Sie unter [Konfigurieren der Verbindungsfilterrichtlinie](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Bedingtes E-Mail-Routing
<a name="BKMK_conditionalmailrouting"> </a>

Sie können einen Connector mit einer Transportegel konfigurieren, die E-Mails basierend auf bestimmten Bedingungen an einen spezifischen Standort weiterleitet. Weitere Informationen finden Sie unter [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).
  
## <a name="hybrid-mail-routing"></a>Hybrid mail routing
<a name="BKMK_hybridmailrouting"> </a>

Hybrid bedeutet, dass ein Teil Ihrer Postfächer lokal gehostet wird, der andere in der Cloud (Exchange Online). Sie können von einer eigenständigen (lokalen) Bereitstellung zu einer hybriden Bereitstellung wechseln.
  
In einer hybriden Bereitstellung können Sie Ihre cloudbasierten und lokalen Postfächer mit EOP schützen. Für lokale Postfächer sind eigenständige Lizenzen erforderlich, wenn sie von EOP geschützt werden. Weitere Informationen zum E-Mail-Routing in einer hybriden Bereitstellung finden Sie unter [Transportweiterleitung in Exchange-Hybrid-Bereitstellungen](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
Im [Bereitstellungs-Assistent für Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) finden Sie darüber hinaus detaillierte Anleitungen zu Hybridbereitstellungen und zum Hybridnachrichtentransport. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen
<a name="BKMK_hybridmailrouting"> </a>

Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).
  

