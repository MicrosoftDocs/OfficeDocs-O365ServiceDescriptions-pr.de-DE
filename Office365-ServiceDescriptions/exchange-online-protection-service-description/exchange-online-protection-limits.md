---
title: Beschränkungen von Exchange Online Protection
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: f866fe3b-a183-4e6d-abd9-bbec0a0c7fae
description: Die folgenden Grenzwertegelten derzeit für Exchange Online Protection. Diese Beschränkungen sind nicht konfigurierbar, sofern nicht anders angegeben.
ms.openlocfilehash: 3c96449b2694dba470f6860f8324d86bb84d3774
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/07/2019
ms.locfileid: "30468142"
---
# <a name="exchange-online-protection-limits"></a>Beschränkungen von Exchange Online Protection

Die folgenden Grenzwertegelten derzeit für Exchange Online Protection. Diese Beschränkungen sind nicht konfigurierbar, sofern nicht anders angegeben. 
  
> [!TIP]
> Weitere Informationen zu Beschränkungen in Exchange Online finden Sie unter [Exchange Online-Begrenzungen](../exchange-online-service-description/exchange-online-limits.md). Die Grenzwerte für Transportregeln gelten auch für Kunden der eigenständigen Lösung von EOP. Die Grenzwerte für Empfängerrate und Nachrichtenrate für Exchange Online gelten nicht für Kunden der eigenständigen Lösung von EOP. 
  
- **Grenzwert für Domänen** Sie können bis zu 900 Domänen pro Mandant hinzufügen. Unterdomänen können in diesem Grenzwert von 900 enthalten sein oder, falls erforderlich, als Teil einer CatchAll-Option Unterdomänen entsprechen. Weitere Informationen finden Sie unter [Verwalten akzeptierter Domänen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
    
- **Größenbeschränkung für Nachrichten** Die maximale Nachrichtengröße für Kunden der eigenständigen Lösung von EOP beträgt 150 MB. 
    
- **Anzahl der ausgehenden Nachrichten** Der Grenzwert für die Anzahl ausgehender Nachrichten, die über EOP gesendet werden, ist so hoch, dass normale E-Mail-Kommunikation nicht als Spam behandelt wird. Wenn Sie geschäftliche Massen-E-Mails und keine ausgehenden Nachrichten über EOP senden möchten, sollten Sie entweder einen E-Mail-Drittanbieter (Email Service Provider, ESP) verwenden oder die E-Mails über Ihre lokalen E-Mail-Server senden. 
    
- **Empfängergrenzwert** Solange der sendende Host die Nachricht in Segmente mit weniger als 500 Empfängern aufteilen kann, wird keine explizite Grenze definiert. Jedes Segment wird effektiv wie eine neue Nachricht behandelt. Zu viele Nachrichten in einem kurzen Zeitraum, Nachrichten von einem Host mit einem schlechten Ruf oder Nachrichten mit verdächtigem Inhalt können gedrosselt oder blockiert werden. 
    
- **Begrenzung für IP-Zulassungsliste oder IP-Sperrliste** Wenn Sie im Verbindungsfilter eine IP-Zulassungsliste oder IP-Sperrliste konfigurieren, können Sie maximal 1273 Einträge angeben, wobei ein Eintrag entweder eine einzelne IP-Adresse oder einen CIDR-Bereich von IP-Adressen von /24 bis /32 darstellt. 
    
- **Beschränkung der Rückstellung** Zurückgestellte Nachrichten bleiben 2 Tage lang in der Warteschlange. Wiederholungsversuche hängen davon ab, welcher Fehlertyp vom E-Mail-System des Empfängers zurückgegeben wird. Das Wiederholungsintervall für die Übertragung von Nachrichten ist 15 Minuten. 
    
- **Dauer der Spamquarantäne** Standardmäßig werden in den Quarantäneordner verschobene Spamnachrichten 15 Tage lang aufbewahrt. Administratoren können diesen Wert über Inhaltsfilterrichtlinien verringern. 
    
- **Spamquarantänebenachrichtigungen für Endbenutzer** Standardmäßig werden Spamquarantänebenachrichtigungen alle 3 Tage an den Endbenutzer versendet. Sie können so konfiguriert werden, dass sie alle 1 bis 15 Tage versendet werden. 
    
- **Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung** Weitere Informationen zu Grenzwerten für Berichterstellung und Nachrichtenablaufverfolgung finden Sie im Abschnitt „Datenverfügbarkeit und Latenz bei Berichterstellung und Nachrichtenablaufverfolgung" unter [Berichterstellung und Nachrichtenablaufverfolgung in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).
    
### <a name="limits-across-eop-options"></a>Beschränkungen bei EOP-Optionen

|**Funktion**|****EOP als eigenständige Lösung****|****EOP-Funktionen in Exchange Online****|****Exchange Enterprise CAL mit Diensten****|
|:-----|:-----|:-----|:-----|
|Domänenbegrenzung  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Größenbeschränkung für Nachrichten (einschließlich Anlagen)  <br/> |150 MB  <br/> |150 MB   <br/> |150 MB  <br/> |
|Empfängergrenzwert  <br/> |Siehe „Empfängergrenzwert" weiter oben  <br/> |500 Empfänger beim Senden von einem gehosteten Postfach; Informationen finden Sie unter "Empfängergrenzwert" weiter oben bei anderen Szenarien  <br/> |Siehe „Empfängergrenzwert" weiter oben  <br/> |
|Grenzwert sicherer Absender  <br/> |1024 Einträge  <br/> |1024 Einträge  <br/> ||
|Grenzwert blockierter Absender  <br/> |1024 Einträge  <br/> |1024 Einträge  <br/> ||
|Beschränkung für zugelassene IP-Adressen oder IP-Block  <br/> |1273 Einträge  <br/> |1273 Einträge  <br/> |1273 Einträge  <br/> |
|Beschränkung der Rückstellung  <br/> |2 Tage, alle 15 Minuten wiederholt  <br/> |2 Tage, alle 15 Minuten wiederholt  <br/> |2 Tage, alle 15 Minuten wiederholt  <br/> |
|Aufbewahrungsdauer für Spam-Quarantäne  <br/> |15 Tage in der Standardeinstellung jedoch gesenkt werden kann  <br/> |15 Tage in der Standardeinstellung jedoch gesenkt werden kann  <br/> |15 Tage in der Standardeinstellung jedoch gesenkt werden kann  <br/> |
|Spamquarantänebenachrichtigungen für Endbenutzer  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage  <br/> |
   

