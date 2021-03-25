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
description: Die folgenden Grenzwerte sind derzeit für Exchange Online Protection vorhanden. Diese Grenzwerte können nur konfiguriert werden, wenn anders angegeben.
ms.openlocfilehash: 6c399c359d39f50a4bd359833fdf595415872bff
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173800"
---
# <a name="exchange-online-protection-limits"></a>Beschränkungen von Exchange Online Protection

Die folgenden Grenzwerte sind derzeit für Exchange Online Protection vorhanden. Diese Grenzwerte können nur konfiguriert werden, wenn anders angegeben. 
  
> [!TIP]
> Weitere Informationen zu Grenzwerten in Exchange Online finden Sie unter [Exchange Online-Grenzwerte](../exchange-online-service-description/exchange-online-limits.md). Die Grenzwerte für Transportregeln gelten auch für Kunden der eigenständigen Lösung von EOP. Die Grenzwerte für Empfängerrate und Nachrichtenrate für Exchange Online gelten nicht für Kunden der eigenständigen Lösung von EOP. 
  
- **Domänenbeschränkung** : Sie können bis zu 900 Domänen pro Mandant hinzufügen. Unterdomänen können in diesem Grenzwert von 900 enthalten sein oder, falls erforderlich, als Teil einer CatchAll-Option Unterdomänen entsprechen. Weitere Informationen finden Sie unter [Verwalten akzeptierter Domänen in EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).

- **Grenzwert für** Remotedomänen: Sie können bis zu 200 Remotedomänen pro Mandant hinzufügen.
    
- **Nachrichtengrößenbeschränkung** – Die maximale Nachrichtengröße für eigenständige EOP-Kunden, einschließlich Anlagen, beträgt 150 MB. 
    
- **Anzahl der gesendeten** ausgehenden Nachrichten – Der Grenzwert für die Anzahl der ausgehenden Nachrichten, die über EOP gesendet werden, ist hoch genug, um sicherzustellen, dass die normale E-Mail-Kommunikation nicht als Spam behandelt wird. Wenn Sie geschäftliche Massen-E-Mails und keine ausgehenden Nachrichten über EOP senden möchten, sollten Sie entweder einen E-Mail-Drittanbieter (Email Service Provider, ESP) verwenden oder die E-Mails über Ihre lokalen E-Mail-Server senden. 
    
- **Empfängerbeschränkung** – Solange der sendende Host die Nachricht in "Blöcke" von weniger als 500 Empfängern aufteilen kann, wird kein expliziter Grenzwert definiert. Jedes Segment wird effektiv wie eine neue Nachricht behandelt. Zu viele Nachrichten in einem kurzen Zeitraum, Nachrichten von einem Host mit einem schlechten Ruf oder Nachrichten mit verdächtigem Inhalt können gedrosselt oder blockiert werden. 
    
- BESCHRÄNKUNG DER **LISTE "IP-Zulassen"** oder "IP-Sperrliste": Beim Konfigurieren einer Liste mit zulässigen IP-Adressen oder einer Liste mit IP-Sperren im Verbindungsfilter können Sie maximal 1273 Einträge angeben, wobei ein Eintrag entweder eine einzelne IP-Adresse oder ein CIDR-Bereich von IP-Adressen von /24 bis /32 ist. 
    
- **Grenzwert für die** Nachrichtenumgereifung: Nachrichten, die sich zurückdingen, verbleiben 24 Stunden lang in unseren Warteschlangen. Wiederholungsversuche hängen davon ab, welcher Fehlertyp vom E-Mail-System des Empfängers zurückgegeben wird. Das Wiederholungsintervall für die Übertragung von Nachrichten ist 15 Minuten. 
    
- **Aufbewahrungszeitraum für** Spamquarantäne : Spamnachrichten, die an die Quarantäne gesendet werden, werden standardmäßig 30 Tage lang aufbewahrt. Administratoren können diesen Wert über Inhaltsfilterrichtlinien verringern. 
    
- **Spamquarantänebenachrichtigungen** für Endbenutzer – Standardmäßig werden bei Aktivierter Spamquarantänebenachrichtigungen für Endbenutzer alle 3 Tage gesendet. Sie können so konfiguriert werden, dass sie alle 1 bis 15 Tage versendet werden. 
    
- Grenzwerte für Die Berichterstellung und Nachrichtenverfolgung – Informationen zu Grenzwerten für Die Berichterstellung und Nachrichtenverfolgung finden Sie im Abschnitt **"Verfügbarkeit** und Latenz von Daten zur Berichterstellung und Nachrichtenverfolgung" [unter Reporting and message trace in Exchange Online Protection](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection).
    
### <a name="limits-across-eop-options"></a>Beschränkungen bei EOP-Optionen

| Feature | EOP als eigenständige Lösung | EOP-Funktionen in Exchange Online | Exchange Enterprise CAL mit Diensten |
|:-----|:-----|:-----|:-----|
|Domänenbegrenzung  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Grenzwert für Remotedomänen  <br/> |200  <br/> |200  <br/> |200  <br/> |
|Größenbeschränkung für Nachrichten (einschließlich Anlagen)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Empfängergrenzwert  <br/> |Siehe „Empfängergrenzwert" weiter oben  <br/> |500 Empfänger beim Senden von einem gehosteten Postfach; Informationen finden Sie unter "Empfängergrenzwert" weiter oben bei anderen Szenarien  <br/> |Siehe „Empfängergrenzwert" weiter oben  <br/> |
|Grenzwert sicherer Absender  <br/> |1024 Einträge  <br/> |1024 Einträge  <br/> ||
|Grenzwert für blockierte Absender pro Richtlinie  <br/> |1024 Einträge  <br/> |1024 Einträge  <br/> ||
|Beschränkung für zugelassene IP-Adressen oder IP-Block  <br/> |1273 Einträge  <br/> |1273 Einträge  <br/> |1273 Einträge  <br/> |
|Beschränkung der Rückstellung  <br/> |1 Tag, alle 15 Minuten wiederholt  <br/> |1 Tag, alle 15 Minuten wiederholt  <br/> |1 Tag, alle 15 Minuten wiederholt  <br/> |
|Aufbewahrungsdauer für Spam-Quarantäne  <br/> |Standardmäßig 30 Tage, kann aber gesenkt werden  <br/> |Standardmäßig 30 Tage, kann aber gesenkt werden  <br/> |Standardmäßig 30 Tage, kann aber gesenkt werden  <br/> |
|Spamquarantänebenachrichtigungen für Endbenutzer  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |
