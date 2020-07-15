---
title: Beschränkungen von Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Die folgenden Grenzwertesind derzeit für Exchange Online Schutz vorhanden. Diese Grenzwertesind nicht konfigurierbar, sofern nicht anders angegeben.
ms.openlocfilehash: 3c5a8e0c5f9a19c9cae81b3bc1e39bb153af0137
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133009"
---
# <a name="exchange-online-protection-limits"></a>Beschränkungen von Exchange Online Protection

Die folgenden Grenzwertesind derzeit für Exchange Online Schutz vorhanden. Diese Grenzwertesind nicht konfigurierbar, sofern nicht anders angegeben. 
  
> [!TIP]
> Weitere Informationen zu Grenzwerten in Exchange Online finden Sie unter [Exchange Online Limits](../exchange-online-service-description/exchange-online-limits.md). Die Grenzwerte für Transportregeln gelten auch für Kunden der eigenständigen Lösung von EOP. Die Grenzwerte für Empfängerrate und Nachrichtenrate für Exchange Online gelten nicht für Kunden der eigenständigen Lösung von EOP. 
  
- **Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Größenbeschränkung für Nachrichten** Die maximale Nachrichtengröße für Kunden der eigenständigen Lösung von EOP beträgt 150 MB. 
    
- **Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers. 
    
- **Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked. 
    
- **Begrenzung für IP-Zulassungsliste oder IP-Sperrliste** Wenn Sie im Verbindungsfilter eine IP-Zulassungsliste oder IP-Sperrliste konfigurieren, können Sie maximal 1273 Einträge angeben, wobei ein Eintrag entweder eine einzelne IP-Adresse oder einen CIDR-Bereich von IP-Adressen von /24 bis /32 darstellt. 
    
- **Grenzwert für Nachrichten Verschiebung** Nachrichten in einem zurückstellungs Zeitraum bleiben 24 Stunden lang in unseren Warteschlangen stehen. Wiederholungsversuche hängen davon ab, welcher Fehlertyp vom E-Mail-System des Empfängers zurückgegeben wird. Das Wiederholungsintervall für die Übertragung von Nachrichten ist 15 Minuten. 
    
- **Aufbewahrungszeitraum für Spam Quarantäne** Standardmäßig werden Spamnachrichten, die an die Quarantäne gesendet werden, 30 Tage lang aufbewahrt. Administratoren können diesen Wert über Inhaltsfilterrichtlinien verringern. 
    
- **End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days. 
    
- **Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung** Informationen zu Grenzwerten für Berichterstellung und Nachrichtenablaufverfolgung finden Sie im Abschnitt "Verfügbarkeit und Latenz von Berichten und Nachrichtenablauf Verfolgungsdaten" in [Berichterstellung und Nachrichtenablaufverfolgung in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Beschränkungen bei EOP-Optionen

|**Funktion**|****EOP als eigenständige Lösung****|****EOP-Funktionen in Exchange Online****|****Exchange Enterprise CAL mit Diensten****|
|:-----|:-----|:-----|:-----|
|Domänenbegrenzung  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Größenbeschränkung für Nachrichten (einschließlich Anlagen)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Empfängergrenzwert  <br/> |Siehe „Empfängergrenzwert" weiter oben  <br/> |500 Empfänger beim Senden von einem gehosteten Postfach; Informationen finden Sie unter "Empfängergrenzwert" weiter oben bei anderen Szenarien  <br/> |Siehe „Empfängergrenzwert" weiter oben  <br/> |
|Grenzwert sicherer Absender  <br/> |1024 Einträge  <br/> |1024 Einträge  <br/> ||
|Grenzwert für blockierte Absender pro Richtlinie  <br/> |1024 Einträge  <br/> |1024 Einträge  <br/> ||
|Beschränkung für zugelassene IP-Adressen oder IP-Block  <br/> |1273 Einträge  <br/> |1273 Einträge  <br/> |1273 Einträge  <br/> |
|Beschränkung der Rückstellung  <br/> |1 Tag, alle 15 Minuten erneut versucht  <br/> |1 Tag, alle 15 Minuten erneut versucht  <br/> |1 Tag, alle 15 Minuten erneut versucht  <br/> |
|Aufbewahrungsdauer für Spam-Quarantäne  <br/> |standardmäßig 30 Tage, kann jedoch gesenkt werden  <br/> |standardmäßig 30 Tage, kann jedoch gesenkt werden  <br/> |standardmäßig 30 Tage, kann jedoch gesenkt werden  <br/> |
|Spamquarantänebenachrichtigungen für Endbenutzer  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |
   

