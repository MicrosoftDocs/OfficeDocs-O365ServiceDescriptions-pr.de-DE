---
title: Nachrichtenübermittlung
ms.author: office365servicedesc
author: pamelaar
manager: gailw
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
description: Für die meisten Organisationen hosten wir Ihre Postfächer und kümmern uns um den Nachrichtenfluss. Dies ist die einfachste Konfiguration und bedeutet, dass Microsoft alle Postfächer und Filter verwaltet. Einige Organisationen benötigen jedoch komplexere Setups für den Nachrichtenfluss, um spezifischen gesetzlichen Bestimmungen oder Unternehmensvorgaben gerecht zu werden. Dieser Artikel stellt die verschiedenen Optionen vor.
ms.openlocfilehash: 0fe7cf2f0e8619bce911457ba634bee41ee4e113
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653327"
---
# <a name="mail-flow"></a>Nachrichtenübermittlung

Für die meisten Organisationen hosten wir Ihre Postfächer und kümmern uns um den Nachrichtenfluss. Dies ist die einfachste Konfiguration und bedeutet, dass Microsoft alle Postfächer und Filter verwaltet. Einige Organisationen benötigen jedoch komplexere Setups für den Nachrichtenfluss, um spezifischen gesetzlichen Bestimmungen oder Unternehmensvorgaben gerecht zu werden. Dieser Artikel stellt die verschiedenen Optionen vor. 
  
## <a name="custom-routing-of-outbound-email"></a>Benutzerdefiniertes Weiterleiten von ausgehenden E-Mails

Microsoft Exchange Online kann von Ihrer Organisation gesendete E-Mails über einen lokalen Server oder einen gehosteten Dienst weiterleiten (gelegentlich als „Smarthost" bezeichnet). Auf diese Weise kann Ihre Organisation DLP-Appliances (Data Loss Prevention, Verhinderung von Datenverlust) verwenden, eine benutzerdefinierte Nachbearbeitung ausgehender E-Mails durchführen und E-Mails über private Netzwerke an Geschäftspartner senden. Exchange Online unterstützt auch das Umschreiben von Adressen: Dabei werden ausgehende E-Mails über ein lokales Gateway weitergeleitet, das die Adressen ändert. Mit diesem Feature können Sie Unterdomänen ausblenden, E-Mails aus einer Organisation mit mehreren Domänen als eine einzige Domäne erscheinen lassen oder partnerrelierte E-Mails so erscheinen lassen, als ob sie von innerhalb Ihrer Organisation gesendet wurden. Administratoren können das benutzerdefinierte E-Mail-Routing im Exchange Admin Center (EAC) konfigurieren.
  
Weitere Informationen finden Sie unter Einrichten von Connectors zum Routen von [E-Mails zwischen Microsoft und Ihren eigenen E-Mail-Servern.](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)
  
> [!IMPORTANT]
> Exchange Online kann eingehende und ausgehende E-Mails zustellen. Wenn Ihre Empfängerdomäne in Exchange Online mit DNS-MX-Einträgen gehostet wird, die auf Exchange Online Protection verweisen, wird der E-Mail-Fluss von Ihrem Mandanten zum Empfänger nicht über das Internet übertragen.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Als Exchange Online können Sie einen sicheren E-Mail-Fluss mit einem vertrauenswürdigen Partner mithilfe von Microsoft Connectors einrichten. Microsoft unterstützt die sichere Kommunikation über Transport Layer Security (TLS), und Sie können einen Connector erstellen, um die Verschlüsselung über TLS zu erzwingen. [TLS](/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) ist ein kryptografisches Protokoll, das Sicherheit für die Kommunikation über das Internet bietet. Mithilfe von Connectors können Sie sowohl erzwungene ein- als auch ausgehende TLS mithilfe von selbst signierten oder zertifizierungsstellen-validierten Zertifikaten konfigurieren. Sie können auch andere Sicherheitseinschränkungen anwenden, z. B. das Angeben von Domänennamen oder IP-Adressbereichen, von denen Ihre Partnerorganisation E-Mails sendet. 
  
Weitere Informationen finden Sie unter [Set up connectors for secure mail flow with a partner organization](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Unter Umständen ist ein CA-validiertes Zertifikat obligatorisch. 
  
## <a name="conditional-mail-routing"></a>Bedingtes E-Mail-Routing

Sie können E-Mails mithilfe von Connectors und Transportregeln an bestimmte Standorte umleiten. Beim kriterienbasierten Routing kann der jeweilige Connector auf Basis spezifischer Bedingungen ausgewählt werden.
  
Weitere Informationen finden Sie unter [Scenario: Conditional mail routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Liste sicherer Absender für eingehende E-Mails

Sie können die IP-Adresse eines vertrauenswürdigen Partners in eine Liste sicherer Absender aufnehmen, um zu gewährleisten, dass Nachrichten von diesem Partner von der Spamfilterung ausgenommen werden. Verwenden Sie dazu die Liste zugelassener IP-Adressen des Verbindungsfilters.
  
Weitere Informationen finden Sie unter [Configure the connection filter policy](/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Hybrides E-Mail-Routing

Eine Hybridbereitstellung bietet Organisationen die Möglichkeit, den großen Funktionsumfang und die Verwaltungskontrolle, die die vorhandene lokale Microsoft Exchange-Organisation bietet, auf die Cloud auszudehnen. Durch den Hybridtransport können zwischen Empfängern in den Organisationen gesendete Nachrichten mithilfe von TLS (Transport Layer Security) authentifiziert, verschlüsselt und übertragen und für Exchange-Komponenten wie Transportregeln, Journaling und Antispamrichtlinien als „intern" angezeigt werden. Der Hybridtransport wird mithilfe des Hybrid Configuration Wizard in Exchange Server konfiguriert.
  
Weitere Informationen zum E-Mail-Routing in hybriden Bereitstellungen finden Sie unter [Transportweiterleitung in Exchange-Hybrid-Bereitstellungen](/exchange/transport-routing).
  
Im [Bereitstellungs-Assistent für Microsoft Exchange Server](/exchange/exchange-deployment-assistant) finden Sie darüber hinaus detaillierte Anleitungen zu Hybridbereitstellungen und zum Hybridnachrichtentransport. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Freigegebener Adressraum mit lokaler Routingsteuerung (MX zeigt auf Lokal)

Freigegebener Adressraum mit der lokalen Routingsteuerung (MX Points to On-Premises) ist ein Hybridbereitstellungsszenario für das E-Mail-Routing, in dem Ihre Postfächer teilweise in Exchange Online und teilweise lokal gehostet werden und der eingehende und ausgehende Internet-E-Mail-Fluss über die lokale Exchange-Organisation geroutet wird. Dieses Szenario wird auch als zentraler E-Mail-Transport bezeichnet. In diesem Szenario wird Exchange Online EOP bereitgestellt, und eingehende Internet-E-Mails werden an Ihren lokalen E-Mail-Server geroutet, bevor sie an EOP und schließlich an postfächer, die in EOP gehostet Exchange Online. Darüber hinaus werden ausgehende E-Mails Exchange Online postfächern für Nachrichten, die an externe Empfänger gesendet werden, Exchange die lokale Organisation geroutet. Mit dieser Konfiguration können Sie einen einzelnen SMTP-Domänennamespace für alle Postfächer in Ihrer lokalen organisation Exchange und Exchange Online verwenden. 
  
Weitere Informationen zu Transportoptionen in einer Hybridbereitstellung finden Sie im Artikel [Transportoptionen in Exchange-Hybridbereitstellungen](/exchange/transport-options).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Freigegebener Adressraum mit lokaler Routingsteuerung (MX zeigt auf EOP)

Freigegebener Adressraum ohne lokale Routingsteuerung (MX Points to EOP) ist ein hybrides E-Mail-Routingszenario, in dem Ihre Postfächer teilweise in der Cloud mit Exchange Online und teilweise lokal gehostet werden und Ihr MX-Eintrag auf EOP verweist. Dieses Szenario ist geeignet, wenn Sie Microsoft zum Hosten einiger Postfächer Ihrer Organisation verwenden und EOP sowohl Ihre lokalen als auch Ihre Cloudpostfächer schützen soll. In diesem Szenario werden E-Mails, die an Empfänger innerhalb Ihrer Organisation gesendet werden, zunächst über EOP geroutet, wo Spam- und Richtlinienfilterung stattfindet, bevor sie Ihre lokalen Postfächer und Cloudpostfächer erreicht. 
  
Weitere Informationen zu Transportoptionen in einer Hybridbereitstellung finden Sie im Artikel [Transportoptionen in Exchange-Hybridbereitstellungen](/exchange/transport-options).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Behandeln von Bereitstellungsproblemen mit dem Assistenten für die Hybridkonfiguration

Wenn Sie den Hybrid Configuration Wizard zur Konfiguration einer hybriden Bereitstellung in Microsoft Exchange Server verwenden, reduzieren Sie das Risiko für Probleme in der hybriden Bereitstellung auf ein Minimum. Es gibt jedoch einige typische Bereiche, die nicht vom Hybrid Configuration Wizard abgedeckt werden und bei falscher Konfiguration zu Problemen in der Hybridbereitstellung führen können. Dazu gehören die richtige Konfiguration des Clientzugriffsservers sowie die richtige Installation und Konfiguration der Zertifikate.
  
Weitere Informationen zur Behandlung von Problemen in einer Bereitstellung mithilfe des Hybrid Configuration Wizard finden Sie unter [Problembehandlung in einer Hybridbereitstellung](/exchange/hybrid-deployment/troubleshoot-a-hybrid-deployment).
  
### <a name="managing-a-hybrid-configuration"></a>Verwalten einer Hybridkonfiguration

Eine vorhandene Hybridkonfiguration können Sie über die Einstellungen des Assistenten für die Hybridkonfiguration ändern. Mögliche Szenarien stellen das Deaktivieren des zentralen Transports oder das Deaktivieren des sicheren E-Mail-Transports dar.
  
Weitere Informationen zur Verwaltung von hybriden Bereitstellungen finden Sie unter [Verwalten einer Hybrid-Bereitstellung](/previous-versions/exchange-server/exchange-150/jj200791(v=exchg.150)).
  
### <a name="hybrid-deployment-requirements"></a>Anforderungen an Hybridbereitstellungen

Weitere Informationen zu den Anforderungen an Hybridbereitstellungen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](/exchange/hybrid-deployment-prerequisites).
  
> [!IMPORTANT]
> In bestimmten Hybridkonfigurationen müssen Sie unter Umständen Exchange Online Protection-Lizenzen für Ihre lokalen Postfächer erwerben. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Dienstbeschreibung](exchange-online-service-description.md).
