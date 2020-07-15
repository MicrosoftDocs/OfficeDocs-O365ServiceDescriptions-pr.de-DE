---
title: Nachrichtenübermittlung
ms.author: office365servicedesc
author: pamelaar
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
description: Für die meisten Organisationen hosten wir Ihre Postfächer und kümmern uns um den Nachrichtenfluss. Dies ist die einfachste Konfiguration und bedeutet, dass Microsoft alle Postfächer und Filterung verwaltet. Einige Organisationen benötigen jedoch komplexere Setups für den Nachrichtenfluss, um spezifischen gesetzlichen Bestimmungen oder Unternehmensvorgaben gerecht zu werden. Dieser Artikel stellt die verschiedenen Optionen vor.
ms.openlocfilehash: 1ada5a3199e6ae65c6aaa99873f13a4025366a8d
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132719"
---
# <a name="mail-flow"></a>Nachrichtenübermittlung

Für die meisten Organisationen hosten wir Ihre Postfächer und kümmern uns um den Nachrichtenfluss. Dies ist die einfachste Konfiguration und bedeutet, dass Microsoft alle Postfächer und Filterung verwaltet. Einige Organisationen benötigen jedoch komplexere Setups für den Nachrichtenfluss, um spezifischen gesetzlichen Bestimmungen oder Unternehmensvorgaben gerecht zu werden. Dieser Artikel stellt die verschiedenen Optionen vor. 
  
## <a name="custom-routing-of-outbound-email"></a>Benutzerdefiniertes Weiterleiten von ausgehenden E-Mails

Microsoft Exchange Online kann von Ihrer Organisation gesendete E-Mails über einen lokalen Server oder einen gehosteten Dienst weiterleiten (gelegentlich als „Smarthost" bezeichnet). Auf diese Weise kann Ihre Organisation Datenverlust Verhinderung (DLP)-Appliances verwenden, benutzerdefinierte Post-Processing von ausgehenden e-Mails durchführen und e-Mails an Geschäftspartner über private Netzwerke zuzustellen. Exchange Online unterstützt auch das Umschreiben von Adressen: Dabei werden ausgehende E-Mails über ein lokales Gateway weitergeleitet, das die Adressen ändert. Mit diesem Feature können Sie Sub-Domains ausblenden, e-Mails aus einer Organisation mit mehreren Domänen als einzelne Domäne anzeigen oder Partner weitergeleitete e-Mails so erscheinen lassen, als ob Sie von innerhalb Ihrer Organisation gesendet würden. Administratoren können das benutzerdefinierte E-Mail-Routing im Exchange Admin Center (EAC) konfigurieren.
  
Weitere Informationen finden Sie unter [Einrichten von Connectors zum Weiterleiten von e-Mails zwischen Microsoft und ihren eigenen e-Mail-Servern](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
> [!IMPORTANT]
> Exchange Online kann eingehende und ausgehende E-Mails zustellen. Wenn Ihre Empfängerdomäne in Exchange Online gehostet wird und DNS MX-Einträge auf Exchange Online Schutz hindeuten, wird der e-Mail-Fluss von Ihrem Mandanten an den Empfänger nicht über das Internet übertragen.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Als Exchange Onlineer Kunde können Sie einen sicheren Nachrichtenfluss mit einem vertrauenswürdigen Partner mithilfe von Microsoft-Connectors einrichten. Microsoft unterstützt die sichere Kommunikation über TLS (Transport Layer Security) und Sie können einen Connector erstellen, um die Verschlüsselung über TLS zu erzwingen. [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) ist ein kryptografisches Protokoll, das Sicherheit für die Kommunikation über das Internet bietet. Mithilfe von Connectors können Sie sowohl erzwungene eingehende als auch ausgehende TLS-Zertifikate mit selbstsignierten oder Zertifizierungsstellen validierten Zertifikaten konfigurieren. Sie können auch andere Sicherheitseinschränkungen anwenden, beispielsweise die Angabe von Domänennamen oder IP-Adressbereichen, aus denen Ihre Partnerorganisation e-Mails sendet. 
  
Weitere Informationen finden Sie unter [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Unter Umständen ist ein CA-validiertes Zertifikat obligatorisch. 
  
## <a name="conditional-mail-routing"></a>Bedingtes E-Mail-Routing

You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.
  
Weitere Informationen finden Sie unter [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Liste sicherer Absender für eingehende E-Mails

You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.
  
Weitere Informationen finden Sie unter [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Hybrides E-Mail-Routing

A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.
  
Weitere Informationen zum E-Mail-Routing in hybriden Bereitstellungen finden Sie unter [Transportweiterleitung in Exchange-Hybrid-Bereitstellungen](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
Im [Bereitstellungs-Assistent für Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) finden Sie darüber hinaus detaillierte Anleitungen zu Hybridbereitstellungen und zum Hybridnachrichtentransport. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Freigegebener Adressraum mit lokaler Routingsteuerung (MX zeigt auf Lokal)

Freigegebener Adressraum mit lokaler Routing Steuerung (MX Points to on-premises) ist ein e-Mail-Routingszenario für die hybridbereitstellung, in dem ihre Postfächer teilweise in Exchange Online und teilweise lokal gehostet werden und ein-und ausgehende Internetnachrichtenfluss über die lokale Exchange-Organisation weitergeleitet wird. Dieses Szenario wird auch als zentralisierter e-Mail-Transport bezeichnet. In diesem Szenario wird Exchange Online mit EoP bereitgestellt und eingehende Internet-e-Mail-Nachrichten werden an den lokalen e-Mail-Server weitergeleitet, bevor Sie an EoP und schließlich an Postfächer weitergeleitet werden, die in Exchange Online gehostet werden. Darüber hinaus werden ausgehende e-Mails von Exchange Online Postfächern über die lokale Exchange-Organisation für Nachrichten weitergeleitet, die an externe Empfänger gesendet werden. Mit dieser Konfiguration können Sie einen einzelnen SMTP-Domänennamespace für alle Postfächer sowohl in Ihrer lokalen Exchange-Organisation als auch in Ihrer Exchange Online Organisation verwenden. 
  
Weitere Informationen zu Transportoptionen in einer Hybridbereitstellung finden Sie im Artikel [Transportoptionen in Exchange-Hybridbereitstellungen](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Freigegebener Adressraum mit lokaler Routingsteuerung (MX zeigt auf EOP)

Freigegebener Adressraum ohne lokale Routing Steuerung (MX Points to EoP) ist ein hybrides e-Mail-Routing-Szenario, in dem ihre Postfächer teilweise in der Cloud mit Exchange Online und teilweise lokal gehostet werden, und Ihr MX-Eintrag zeigt auf EoP. Dieses Szenario ist sinnvoll, wenn Sie Microsoft zum Hosten einiger Postfächer Ihrer Organisation verwenden, und Sie möchten, dass EoP sowohl Ihre lokalen als auch die Cloud-Postfächer schützt. In diesem Szenario werden e-Mails, die an Empfänger in Ihrer Organisation gesendet werden, anfänglich über EoP weitergeleitet, wobei Spam-und Richtlinienfilterung auftreten, bevor Sie Ihre lokalen Postfächer und Cloud-Postfächer erreichen. 
  
Weitere Informationen zu Transportoptionen in einer Hybridbereitstellung finden Sie im Artikel [Transportoptionen in Exchange-Hybridbereitstellungen](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Behandeln von Bereitstellungsproblemen mit dem Assistenten für die Hybridkonfiguration

Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.
  
Weitere Informationen zur Behandlung von Problemen in einer Bereitstellung mithilfe des Hybrid Configuration Wizard finden Sie unter [Problembehandlung in einer Hybridbereitstellung](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Verwalten einer Hybridkonfiguration

You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.
  
Weitere Informationen zur Verwaltung von hybriden Bereitstellungen finden Sie unter [Verwalten einer Hybrid-Bereitstellung](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Anforderungen an Hybridbereitstellungen

Weitere Informationen zu den Anforderungen an Hybridbereitstellungen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> In bestimmten Hybridkonfigurationen müssen Sie unter Umständen Exchange Online Protection-Lizenzen für Ihre lokalen Postfächer erwerben. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie in der [Beschreibung des Exchange Online Diensts](exchange-online-service-description.md).
  