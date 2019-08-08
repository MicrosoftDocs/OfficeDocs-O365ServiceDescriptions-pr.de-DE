---
title: Nachrichtenübermittlung
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: 'Im Falle der meisten Organisationen, die Office 365 verwenden, hosten wir die Postfächer und übernehmen die Abwicklung des Nachrichtenflusses. Das ist die einfachste Konfiguration und bedeutet, dass alle Postfächer und die gesamte Filterung von Office 365 verwaltet werden. Einige Organisationen benötigen jedoch komplexere Setups für den Nachrichtenfluss, um spezifischen gesetzlichen Bestimmungen oder Unternehmensvorgaben gerecht zu werden. Dieser Artikel stellt die verschiedenen Optionen vor. '
ms.openlocfilehash: a50c85fff3ba023706932f227db1df3915923545
ms.sourcegitcommit: 5b1670c36e256aef7f222951a49a4411afc3bcb6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/07/2019
ms.locfileid: "36231413"
---
# <a name="mail-flow"></a>Mail Flow

Im Falle der meisten Organisationen, die Office 365 verwenden, hosten wir die Postfächer und übernehmen die Abwicklung des Nachrichtenflusses. Das ist die einfachste Konfiguration und bedeutet, dass alle Postfächer und die gesamte Filterung von Office 365 verwaltet werden. Einige Organisationen benötigen jedoch komplexere Setups für den Nachrichtenfluss, um spezifischen gesetzlichen Bestimmungen oder Unternehmensvorgaben gerecht zu werden. Dieser Artikel stellt die verschiedenen Optionen vor.  
  
## <a name="custom-routing-of-outbound-email"></a>Benutzerdefiniertes Weiterleiten von ausgehenden E-Mails

Microsoft Exchange Online kann von Ihrer Organisation gesendete E-Mails über einen lokalen Server oder einen gehosteten Dienst weiterleiten (gelegentlich als „Smarthost" bezeichnet). So kann Ihre Organisation spezielle Appliances zur Verhinderung von Datenverlust einsetzen, benutzerdefinierte Nachbearbeitungstasks auf ausgehende E-Mails anwenden und E-Mails an Geschäftspartner über private Netzwerke senden. Exchange Online unterstützt auch das Umschreiben von Adressen: Dabei werden ausgehende E-Mails über ein lokales Gateway weitergeleitet, das die Adressen ändert. Diese Funktion macht es möglich, Unterdomänen zu verbergen, E-Mails von einer Organisation mit mehreren Domänen wie E-Mails erscheinen zu lassen, die von einer Organisation mit nur einer einzigen Domäne gesendet wurden, oder von Partnern weitergeleitete E-Mails so erscheinen zu lassen, als ob sie von innerhalb Ihrer Organisation gesendet worden wären. Administratoren können das benutzerdefinierte E-Mail-Routing im Exchange Admin Center (EAC) konfigurieren.
  
Weitere Informationen finden Sie unter [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
> [!IMPORTANT]
> Exchange Online kann eingehende und ausgehende E-Mails zustellen. Wenn Ihre Empfängerdomäne in Exchange Online gehostet wird und DNS MX-Einträge auf Exchange Online Schutz hindeuten, wird der e-Mail-Fluss von Ihrem Mandanten an den Empfänger nicht über das Internet übertragen.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Als Exchange Online-Kunde können Sie mithilfe von Office 365-Connectors einen sicheren Nachrichtenfluss mit einem vertrauenswürdigen Partner einrichten. Office 365 unterstützt die sichere Kommunikation über Transport Layer Security (TLS), und Sie können einen Connector erstellen, um TLS-Verschlüsselung zu erzwingen. [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) ist ein kryptografisches Protokoll, das die Kommunikation über das Internet absichert. Mithilfe von Connectors können Sie TLS für eingehende und ausgehende Nachrichten erzwingen, basierend auf selbstsignierten Zertifikaten oder Zertifikaten, die von einer Zertifizierungsstelle validiert wurden. Sie können auch weitere Sicherheitseinschränkungen implementieren. Beispielsweise können Sie die Domänennamen oder IP-Adressbereiche angeben, über die Ihre Partnerorganisation E-Mails sendet. 
  
Weitere Informationen finden Sie unter [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Unter Umständen ist ein CA-validiertes Zertifikat obligatorisch. 
  
## <a name="conditional-mail-routing"></a>Bedingtes E-Mail-Routing

Sie können E-Mails mithilfe von Connectors und Transportregeln an bestimmte Standorte umleiten. Beim kriterienbasierten Routing kann der jeweilige Connector auf Basis spezifischer Bedingungen ausgewählt werden.
  
Weitere Informationen finden Sie unter [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Liste sicherer Absender für eingehende E-Mails

Sie können die IP-Adresse eines vertrauenswürdigen Partners in eine Liste sicherer Absender aufnehmen, um zu gewährleisten, dass Nachrichten von diesem Partner von der Spamfilterung ausgenommen werden. Verwenden Sie dazu die Liste zugelassener IP-Adressen des Verbindungsfilters.
  
Weitere Informationen finden Sie unter [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Hybrides E-Mail-Routing

Eine Hybridbereitstellung bietet Organisationen die Möglichkeit, den großen Funktionsumfang und die Verwaltungskontrolle, die die vorhandene lokale Microsoft Exchange-Organisation bietet, auf die Cloud auszudehnen. Durch den Hybridtransport können zwischen Empfängern in den Organisationen gesendete Nachrichten mithilfe von TLS (Transport Layer Security) authentifiziert, verschlüsselt und übertragen und für Exchange-Komponenten wie Transportregeln, Journaling und Antispamrichtlinien als „intern" angezeigt werden. Der Hybridtransport wird mithilfe des Hybrid Configuration Wizard in Exchange Server konfiguriert.
  
Weitere Informationen zum E-Mail-Routing in hybriden Bereitstellungen finden Sie unter [Transportweiterleitung in Exchange-Hybrid-Bereitstellungen](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
Im [Bereitstellungs-Assistent für Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) finden Sie darüber hinaus detaillierte Anleitungen zu Hybridbereitstellungen und zum Hybridnachrichtentransport. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Freigegebener Adressraum mit lokaler Routingsteuerung (MX zeigt auf Lokal)

Freigegebener Adressraum mit lokaler Routingsteuerung (MX zeigt auf Lokal) ist ein Hybridbereitstellungsszenario für das E-Mail-Routing, in dem Ihre Postfächer teilweise in Exchange Online und teilweise lokal gehostet werden und der eingehende und ausgehende Internet-Nachrichtenfluss über die lokale Exchange-Organisation weitergeleitet wird. Dieses Szenario wird auch als zentralisierter E-Mail-Transport bezeichnet. In diesem Szenario wird Exchange Online mit EOP bereitgestellt. Aus dem Internet eingehende E-Mails werden zuerst an den lokalen E-Mail-Server weitergeleitet, bevor sie an EOP und schließlich an die in Exchange Online gehosteten Postfächer weitergeleitet werden. Zusätzlich werden von Exchange Online-Postfächern an externe Empfänger gesendete Nachrichten über die lokale Exchange-Organisation weitergeleitet. Bei dieser Konfiguration können Sie für alle Postfächer in Ihrer lokalen Exchange-Organisation und Ihrer Exchange Online-Organisation einen einzigen SMTP-Domänennamespace verwenden. 
  
Weitere Informationen zu Transportoptionen in einer Hybridbereitstellung finden Sie im Artikel [Transportoptionen in Exchange-Hybridbereitstellungen](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Freigegebener Adressraum mit lokaler Routingsteuerung (MX zeigt auf EOP)

Freigegebener Adressraum ohne lokale Routingsteuerung (MX zeigt auf EOP) ist ein Hybridszenario für das E-Mail-Routing, in dem Ihre Postfächer teilweise cloudbasiert in Exchange Online und teilweise lokal gehostet werden und Ihr MX-Eintrag auf EOP zeigt. Dieses Szenario empfiehlt sich, wenn Sie den Office 365-Dienst verwenden, um bestimmte Postfächer Ihrer Organisation zu hosten, und sowohl Ihre lokalen als auch Ihre cloudbasierten Postfächer mit EOP schützen möchten. In diesem Szenario werden E-Mails an Empfänger innerhalb Ihrer Organisation zuerst über EOP weitergeleitet. Dort findet die Spam- und Richtlinienfilterung statt, bevor die E-Mails schließlich an die lokalen und cloudbasierten Postfächer übermittelt werden. 
  
Weitere Informationen zu Transportoptionen in einer Hybridbereitstellung finden Sie im Artikel [Transportoptionen in Exchange-Hybridbereitstellungen](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Behandeln von Bereitstellungsproblemen mit dem Assistenten für die Hybridkonfiguration

Wenn Sie den Hybrid Configuration Wizard zur Konfiguration einer hybriden Bereitstellung in Microsoft Exchange Server verwenden, reduzieren Sie das Risiko für Probleme in der hybriden Bereitstellung auf ein Minimum. Es gibt jedoch einige typische Bereiche, die nicht vom Hybrid Configuration Wizard abgedeckt werden und bei falscher Konfiguration zu Problemen in der Hybridbereitstellung führen können. Dazu gehören die richtige Konfiguration des Clientzugriffsservers sowie die richtige Installation und Konfiguration der Zertifikate.
  
Weitere Informationen zur Behandlung von Problemen in einer Bereitstellung mithilfe des Hybrid Configuration Wizard finden Sie unter [Problembehandlung in einer Hybridbereitstellung](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Verwalten einer Hybridkonfiguration

Eine vorhandene Hybridkonfiguration können Sie über die Einstellungen des Assistenten für die Hybridkonfiguration ändern. Mögliche Szenarien stellen das Deaktivieren des zentralen Transports oder das Deaktivieren des sicheren E-Mail-Transports dar.
  
Weitere Informationen zur Verwaltung von hybriden Bereitstellungen finden Sie unter [Verwalten einer Hybrid-Bereitstellung](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Anforderungen an Hybridbereitstellungen

Weitere Informationen zu den Anforderungen an Hybridbereitstellungen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> In bestimmten Hybridkonfigurationen müssen Sie unter Umständen Exchange Online Protection-Lizenzen für Ihre lokalen Postfächer erwerben. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Welche Funktionen in den einzelnen Office 365-Plänen, eigenständigen Optionen und lokalen Lösungen jeweils verfügbar sind, können Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description.md) nachlesen.
  