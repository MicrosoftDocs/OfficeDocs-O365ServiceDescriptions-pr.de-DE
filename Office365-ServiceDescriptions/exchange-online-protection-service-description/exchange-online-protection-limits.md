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
ms.openlocfilehash: 555177349005c275fcbf91a1e70467ebcc25f2be
ms.sourcegitcommit: 0f17ea421190f52bf55e530e9374543fd59b8665
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/24/2020
ms.locfileid: "48261492"
---
# <a name="exchange-online-protection-limits"></a>Beschränkungen von Exchange Online Protection

Die folgenden Grenzwertesind derzeit für Exchange Online Schutz vorhanden. Diese Grenzwertesind nicht konfigurierbar, sofern nicht anders angegeben. 
  
> [!TIP]
> Weitere Informationen zu Grenzwerten in Exchange Online finden Sie unter [Exchange Online Limits](../exchange-online-service-description/exchange-online-limits.md). Die Grenzwerte für Transportregeln gelten auch für Kunden der eigenständigen Lösung von EOP. Die Grenzwerte für Empfängerrate und Nachrichtenrate für Exchange Online gelten nicht für Kunden der eigenständigen Lösung von EOP. 
  
- **Domänen Grenzwert** -Sie können bis zu 900 Domänen pro Mandant hinzufügen. Unterdomänen können in diesem Grenzwert von 900 enthalten sein oder, falls erforderlich, als Teil einer CatchAll-Option Unterdomänen entsprechen. Weitere Informationen finden Sie unter [Verwalten akzeptierter Domänen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).

- **Grenzwert für Remotedomänen** : Sie können bis zu 200 Remotedomänen pro Mandant hinzufügen.
    
- **Grenzwert für die Nachrichtengröße** : die maximale Nachrichtengröße für EoP-eigenständige Kunden, einschließlich Anlagen, beträgt 150 MB. 
    
- **Anzahl der gesendeten ausgehenden Nachrichten** – der Grenzwert für die Anzahl der über EoP gesendeten ausgehenden Nachrichten ist hoch genug, um sicherzustellen, dass die normale e-Mail-Kommunikation nicht als Spam behandelt wird. Wenn Sie geschäftliche Massen-E-Mails und keine ausgehenden Nachrichten über EOP senden möchten, sollten Sie entweder einen E-Mail-Drittanbieter (Email Service Provider, ESP) verwenden oder die E-Mails über Ihre lokalen E-Mail-Server senden. 
    
- **Empfängergrenzwert** – solange der sendende Host die Nachricht in "Chunks" mit weniger als 500 Empfängern aufteilen kann, wird kein expliziter Grenzwert definiert. Jedes Segment wird effektiv wie eine neue Nachricht behandelt. Zu viele Nachrichten in einem kurzen Zeitraum, Nachrichten von einem Host mit einem schlechten Ruf oder Nachrichten mit verdächtigem Inhalt können gedrosselt oder blockiert werden. 
    
- **Grenzwert für IP-Zulassungs-oder IP-Sperrliste** : beim Konfigurieren einer IP-Zulassungsliste oder einer IP-Sperrliste im Verbindungsfilter können Sie maximal 1273 Einträge angeben, wobei ein Eintrag entweder eine einzelne IP-Adresse oder ein CIDR-Bereich von IP-Adressen von/24 bis/32 ist. 
    
- **Grenzwert** für die Nachrichten Zurücksetzung – Nachrichten in zurückstellen bleiben 24 Stunden lang in unseren Warteschlangen. Wiederholungsversuche hängen davon ab, welcher Fehlertyp vom E-Mail-System des Empfängers zurückgegeben wird. Das Wiederholungsintervall für die Übertragung von Nachrichten ist 15 Minuten. 
    
- **Aufbewahrungszeitraum für Spamquarantäne** – standardmäßig werden Spamnachrichten, die an die Quarantäne gesendet werden, 30 Tage lang aufbewahrt. Administratoren können diesen Wert über Inhaltsfilterrichtlinien verringern. 
    
- **Spamquarantäne Benachrichtigungen für Endbenutzer** – standardmäßig werden bei Aktivierung Spamquarantäne Benachrichtigungen für Endbenutzer alle drei Tage gesendet. Sie können so konfiguriert werden, dass sie alle 1 bis 15 Tage versendet werden. 
    
- **Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung** : Informationen zu Grenzwerten für Berichte und Nachrichtenablaufverfolgung finden Sie im Abschnitt "Berichterstellung und Nachrichtenablaufverfolgung für Datenverfügbarkeit und-Wartezeit" in [Berichterstellung und Nachrichtenablaufverfolgung in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Beschränkungen bei EOP-Optionen

| Feature | EOP als eigenständige Lösung | EOP-Funktionen in Exchange Online | Exchange Enterprise CAL mit Diensten |
|:-----|:-----|:-----|:-----|
|Domänenbegrenzung  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Grenzwert für Remote Domäne  <br/> |200  <br/> |200  <br/> |200  <br/> |
|Größenbeschränkung für Nachrichten (einschließlich Anlagen)  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Empfängergrenzwert  <br/> |Siehe „Empfängergrenzwert" weiter oben  <br/> |500 Empfänger beim Senden von einem gehosteten Postfach; Informationen finden Sie unter "Empfängergrenzwert" weiter oben bei anderen Szenarien  <br/> |Siehe „Empfängergrenzwert" weiter oben  <br/> |
|Grenzwert sicherer Absender  <br/> |1024 Einträge  <br/> |1024 Einträge  <br/> ||
|Grenzwert für blockierte Absender pro Richtlinie  <br/> |1024 Einträge  <br/> |1024 Einträge  <br/> ||
|Beschränkung für zugelassene IP-Adressen oder IP-Block  <br/> |1273 Einträge  <br/> |1273 Einträge  <br/> |1273 Einträge  <br/> |
|Beschränkung der Rückstellung  <br/> |1 Tag, alle 15 Minuten erneut versucht  <br/> |1 Tag, alle 15 Minuten erneut versucht  <br/> |1 Tag, alle 15 Minuten erneut versucht  <br/> |
|Aufbewahrungsdauer für Spam-Quarantäne  <br/> |standardmäßig 30 Tage, kann jedoch gesenkt werden  <br/> |standardmäßig 30 Tage, kann jedoch gesenkt werden  <br/> |standardmäßig 30 Tage, kann jedoch gesenkt werden  <br/> |
|Spamquarantänebenachrichtigungen für Endbenutzer  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |
   

