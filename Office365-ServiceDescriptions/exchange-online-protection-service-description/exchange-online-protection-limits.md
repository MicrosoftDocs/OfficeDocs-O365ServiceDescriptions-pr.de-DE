---
title: Beschränkungen von Exchange Online Protection
ms.author: pebaum
author: pebaum
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
description: Die folgenden Grenzwerte, die derzeit für Exchange Online Protection vorhanden sein. Diese Grenzwerte sind nicht konfigurierbar, sofern nicht anders angegeben.
ms.openlocfilehash: 2e2efe4693cb7e5cdf52b4d035512657c39f03c2
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035895"
---
# <a name="exchange-online-protection-limits"></a><span data-ttu-id="1d114-104">Beschränkungen von Exchange Online Protection</span><span class="sxs-lookup"><span data-stu-id="1d114-104">Exchange Online Protection Limits</span></span>

<span data-ttu-id="1d114-p102">Die folgenden Grenzwerte, die derzeit für Exchange Online Protection vorhanden sein. Diese Grenzwerte sind nicht konfigurierbar, sofern nicht anders angegeben.</span><span class="sxs-lookup"><span data-stu-id="1d114-p102">The following limits currently exist for Exchange Online Protection. These limits are not configurable, unless specified otherwise.</span></span> 
  
> [!TIP]
> <span data-ttu-id="1d114-p103">Weitere Informationen zu Beschränkungen in Exchange Online finden Sie unter [Exchange Online-Begrenzungen](../exchange-online-service-description/exchange-online-limits.md). Die Grenzwerte für Transportregeln gelten auch für Kunden der eigenständigen Lösung von EOP. Die Grenzwerte für Empfängerrate und Nachrichtenrate für Exchange Online gelten nicht für Kunden der eigenständigen Lösung von EOP.</span><span class="sxs-lookup"><span data-stu-id="1d114-p103">For more information about limits in Exchange Online, see [Exchange Online Limits](../exchange-online-service-description/exchange-online-limits.md). The transport rule limits also apply to EOP standalone customers. The recipient rate and message rate limits for Exchange Online are not applicable for EOP standalone customers.</span></span> 
  
- <span data-ttu-id="1d114-p104">**Grenzwert für Domänen** Sie können bis zu 900 Domänen pro Mandant hinzufügen. Unterdomänen können in diesem Grenzwert von 900 enthalten sein oder, falls erforderlich, als Teil einer CatchAll-Option Unterdomänen entsprechen. Weitere Informationen finden Sie unter [Verwalten akzeptierter Domänen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="1d114-p104">**Domain limit** You can add up to 900 domains per tenant. Subdomains can be included in this 900 limit, or if necessary, as part of a catch-all option, match subdomains. For more information, see [Manage Accepted Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
    
- <span data-ttu-id="1d114-113">**Größenbeschränkung für Nachrichten** Die maximale Nachrichtengröße für Kunden der eigenständigen Lösung von EOP beträgt 150 MB.</span><span class="sxs-lookup"><span data-stu-id="1d114-113">**Message size limit** The maximum message size for EOP standalone customers, including attachments, is 150 MB.</span></span> 
    
- <span data-ttu-id="1d114-p105">**Anzahl der ausgehenden Nachrichten** Der Grenzwert für die Anzahl ausgehender Nachrichten, die über EOP gesendet werden, ist so hoch, dass normale E-Mail-Kommunikation nicht als Spam behandelt wird. Wenn Sie geschäftliche Massen-E-Mails und keine ausgehenden Nachrichten über EOP senden möchten, sollten Sie entweder einen E-Mail-Drittanbieter (Email Service Provider, ESP) verwenden oder die E-Mails über Ihre lokalen E-Mail-Server senden.</span><span class="sxs-lookup"><span data-stu-id="1d114-p105">**Number of outbound messages sent** The limit for the number of outbound messages sent through EOP is high enough to ensure that normal email communication is not treated as spam. If you want to send commercial bulk email messages, rather than sending outbound messages through EOP, we recommend that you either use a third-party email service provider (ESP) or send them through your on-premises email servers.</span></span> 
    
- <span data-ttu-id="1d114-p106">**Empfängergrenzwert** Solange der sendende Host die Nachricht in Segmente mit weniger als 500 Empfängern aufteilen kann, wird keine explizite Grenze definiert. Jedes Segment wird effektiv wie eine neue Nachricht behandelt. Zu viele Nachrichten in einem kurzen Zeitraum, Nachrichten von einem Host mit einem schlechten Ruf oder Nachrichten mit verdächtigem Inhalt können gedrosselt oder blockiert werden.</span><span class="sxs-lookup"><span data-stu-id="1d114-p106">**Recipient limit** As long as the sending host can split the message into "chunks" of fewer than 500 recipients, no explicit limit is defined. However, each "chunk" is effectively treated as a new message. Too many messages in a short period, messages from a host with a poor reputation, or messages with questionable content could be throttled or blocked.</span></span> 
    
- <span data-ttu-id="1d114-119">**Begrenzung für IP-Zulassungsliste oder IP-Sperrliste** Wenn Sie im Verbindungsfilter eine IP-Zulassungsliste oder IP-Sperrliste konfigurieren, können Sie maximal 1273 Einträge angeben, wobei ein Eintrag entweder eine einzelne IP-Adresse oder einen CIDR-Bereich von IP-Adressen von /24 bis /32 darstellt.</span><span class="sxs-lookup"><span data-stu-id="1d114-119">**IP Allow or IP Block list limit** When configuring an IP Allow list or an IP Block list in the connection filter, you can specify a maximum of 1273 entries, where an entry is either a single IP address or a CIDR range of IP addresses from /24 to /32.</span></span> 
    
- <span data-ttu-id="1d114-p107">**Beschränkung der Rückstellung** Zurückgestellte Nachrichten bleiben 2 Tage lang in der Warteschlange. Wiederholungsversuche hängen davon ab, welcher Fehlertyp vom E-Mail-System des Empfängers zurückgegeben wird. Das Wiederholungsintervall für die Übertragung von Nachrichten ist 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="1d114-p107">**Message deferral limit** Messages in deferral will remain in our queues for 2 days. Message retry attempts are based on the error type received from the recipient's mail system. Messages are retried every 15 minutes.</span></span> 
    
- <span data-ttu-id="1d114-p108">**Dauer der Spamquarantäne** Standardmäßig werden in den Quarantäneordner verschobene Spamnachrichten 15 Tage lang aufbewahrt. Administratoren können diesen Wert über Inhaltsfilterrichtlinien verringern.</span><span class="sxs-lookup"><span data-stu-id="1d114-p108">**Spam quarantine retention period** By default, spam messages sent to the quarantine are retained for 15 days. Administrators can lower this value via content filter policies.</span></span> 
    
- <span data-ttu-id="1d114-p109">**Spamquarantänebenachrichtigungen für Endbenutzer** Standardmäßig werden Spamquarantänebenachrichtigungen alle 3 Tage an den Endbenutzer versendet. Sie können so konfiguriert werden, dass sie alle 1 bis 15 Tage versendet werden.</span><span class="sxs-lookup"><span data-stu-id="1d114-p109">**End-user spam quarantine notifications** By default, if enabled, end-user spam quarantine notifications are sent every 3 days. They can be configured to be sent every 1 to 15 days.</span></span> 
    
- <span data-ttu-id="1d114-127">**Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung** Weitere Informationen zu Grenzwerten für Berichterstellung und Nachrichtenablaufverfolgung finden Sie im Abschnitt „Datenverfügbarkeit und Latenz bei Berichterstellung und Nachrichtenablaufverfolgung" unter [Berichterstellung und Nachrichtenablaufverfolgung in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).</span><span class="sxs-lookup"><span data-stu-id="1d114-127">**Reporting and message trace limits** For reporting and message trace limits, see the "Reporting and message trace data availability and latency" section in [Reporting and Message Trace in Exchange Online Protection](https://go.microsoft.com/fwlink/?LinkId=394248).</span></span>
    
### <a name="limits-across-eop-options"></a><span data-ttu-id="1d114-128">Beschränkungen bei EOP-Optionen</span><span class="sxs-lookup"><span data-stu-id="1d114-128">Limits across EOP options</span></span>

|<span data-ttu-id="1d114-129">**Funktion**</span><span class="sxs-lookup"><span data-stu-id="1d114-129">**Feature**</span></span>|<span data-ttu-id="1d114-130">\*\*\*\*EOP als eigenständige Lösung\*\*\*\*</span><span class="sxs-lookup"><span data-stu-id="1d114-130">\*\*\*\*EOP Standalone\*\*\*\*</span></span>|<span data-ttu-id="1d114-131">\*\*\*\*EOP-Funktionen in Exchange Online\*\*\*\*</span><span class="sxs-lookup"><span data-stu-id="1d114-131">\*\*\*\*EOP features in Exchange Online\*\*\*\*</span></span>|<span data-ttu-id="1d114-132">\*\*\*\*Exchange Enterprise CAL mit Diensten\*\*\*\*</span><span class="sxs-lookup"><span data-stu-id="1d114-132">\*\*\*\*Exchange Enterprise CAL with Services\*\*\*\*</span></span>|
|:-----|:-----|:-----|:-----|
|<span data-ttu-id="1d114-133">Domänenbegrenzung</span><span class="sxs-lookup"><span data-stu-id="1d114-133">Domain limit</span></span>  <br/> |<span data-ttu-id="1d114-134">900</span><span class="sxs-lookup"><span data-stu-id="1d114-134">900</span></span>  <br/> |<span data-ttu-id="1d114-135">900</span><span class="sxs-lookup"><span data-stu-id="1d114-135">900</span></span>  <br/> |<span data-ttu-id="1d114-136">900</span><span class="sxs-lookup"><span data-stu-id="1d114-136">900</span></span>  <br/> |
|<span data-ttu-id="1d114-137">Größenbeschränkung für Nachrichten (einschließlich Anlagen)</span><span class="sxs-lookup"><span data-stu-id="1d114-137">Message size limit (including attachments)</span></span>  <br/> |<span data-ttu-id="1d114-138">150 MB</span><span class="sxs-lookup"><span data-stu-id="1d114-138">150 MB</span></span>  <br/> |<span data-ttu-id="1d114-139">150 MB</span><span class="sxs-lookup"><span data-stu-id="1d114-139">150 MB</span></span>  <br/> |<span data-ttu-id="1d114-140">150 MB</span><span class="sxs-lookup"><span data-stu-id="1d114-140">150 MB</span></span>  <br/> |
|<span data-ttu-id="1d114-141">Empfängergrenzwert</span><span class="sxs-lookup"><span data-stu-id="1d114-141">Recipient limit</span></span>  <br/> |<span data-ttu-id="1d114-142">Siehe „Empfängergrenzwert" weiter oben</span><span class="sxs-lookup"><span data-stu-id="1d114-142">See "Recipient limit" above</span></span>  <br/> |<span data-ttu-id="1d114-143">500 Empfänger beim Senden von einem gehosteten Postfach; Informationen finden Sie unter "Empfängergrenzwert" weiter oben bei anderen Szenarien</span><span class="sxs-lookup"><span data-stu-id="1d114-143">500 recipients when sending from a hosted mailbox; see "Recipient limit" above for other scenarios</span></span>  <br/> |<span data-ttu-id="1d114-144">Siehe „Empfängergrenzwert" weiter oben</span><span class="sxs-lookup"><span data-stu-id="1d114-144">See "Recipient limit" above</span></span>  <br/> |
|<span data-ttu-id="1d114-145">Grenzwert sicherer Absender</span><span class="sxs-lookup"><span data-stu-id="1d114-145">Safe sender limit</span></span>  <br/> |<span data-ttu-id="1d114-146">1024 Einträge</span><span class="sxs-lookup"><span data-stu-id="1d114-146">1024 entries</span></span>  <br/> |<span data-ttu-id="1d114-147">1024 Einträge</span><span class="sxs-lookup"><span data-stu-id="1d114-147">1024 entries</span></span>  <br/> ||
|<span data-ttu-id="1d114-148">Grenzwert blockierter Absender</span><span class="sxs-lookup"><span data-stu-id="1d114-148">Blocked sender limit</span></span>  <br/> |<span data-ttu-id="1d114-149">1024 Einträge</span><span class="sxs-lookup"><span data-stu-id="1d114-149">1024 entries</span></span>  <br/> |<span data-ttu-id="1d114-150">1024 Einträge</span><span class="sxs-lookup"><span data-stu-id="1d114-150">1024 entries</span></span>  <br/> ||
|<span data-ttu-id="1d114-151">Beschränkung für zugelassene IP-Adressen oder IP-Block</span><span class="sxs-lookup"><span data-stu-id="1d114-151">IP Allow or IP Block list limit</span></span>  <br/> |<span data-ttu-id="1d114-152">1273 Einträge</span><span class="sxs-lookup"><span data-stu-id="1d114-152">1273 entries</span></span>  <br/> |<span data-ttu-id="1d114-153">1273 Einträge</span><span class="sxs-lookup"><span data-stu-id="1d114-153">1273 entries</span></span>  <br/> |<span data-ttu-id="1d114-154">1273 Einträge</span><span class="sxs-lookup"><span data-stu-id="1d114-154">1273 entries</span></span>  <br/> |
|<span data-ttu-id="1d114-155">Beschränkung der Rückstellung</span><span class="sxs-lookup"><span data-stu-id="1d114-155">Message deferral limit</span></span>  <br/> |<span data-ttu-id="1d114-156">2 Tage, alle 15 Minuten wiederholt</span><span class="sxs-lookup"><span data-stu-id="1d114-156">2 days, retried every 15 minutes</span></span>  <br/> |<span data-ttu-id="1d114-157">2 Tage, alle 15 Minuten wiederholt</span><span class="sxs-lookup"><span data-stu-id="1d114-157">2 days, retried every 15 minutes</span></span>  <br/> |<span data-ttu-id="1d114-158">2 Tage, alle 15 Minuten wiederholt</span><span class="sxs-lookup"><span data-stu-id="1d114-158">2 days, retried every 15 minutes</span></span>  <br/> |
|<span data-ttu-id="1d114-159">Aufbewahrungsdauer für Spam-Quarantäne</span><span class="sxs-lookup"><span data-stu-id="1d114-159">Spam quarantine retention period</span></span>  <br/> |<span data-ttu-id="1d114-160">15 Tage in der Standardeinstellung jedoch gesenkt werden kann</span><span class="sxs-lookup"><span data-stu-id="1d114-160">15 days by default but can be lowered</span></span>  <br/> |<span data-ttu-id="1d114-161">15 Tage in der Standardeinstellung jedoch gesenkt werden kann</span><span class="sxs-lookup"><span data-stu-id="1d114-161">15 days by default but can be lowered</span></span>  <br/> |<span data-ttu-id="1d114-162">15 Tage in der Standardeinstellung jedoch gesenkt werden kann</span><span class="sxs-lookup"><span data-stu-id="1d114-162">15 days by default but can be lowered</span></span>  <br/> |
|<span data-ttu-id="1d114-163">Spamquarantänebenachrichtigungen für Endbenutzer</span><span class="sxs-lookup"><span data-stu-id="1d114-163">End-user spam quarantine notifications</span></span>  <br/> |<span data-ttu-id="1d114-164">3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage</span><span class="sxs-lookup"><span data-stu-id="1d114-164">3 days by default, configurable from 1 to 15 days</span></span>  <br/> |<span data-ttu-id="1d114-165">3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage</span><span class="sxs-lookup"><span data-stu-id="1d114-165">3 days by default, configurable from 1 to 15 days</span></span>  <br/> |<span data-ttu-id="1d114-166">3 Tage standardmäßig konfigurierbar von 1 bis 15 Tage</span><span class="sxs-lookup"><span data-stu-id="1d114-166">3 days by default, configurable from 1 to 15 days</span></span>  <br/> |
   
