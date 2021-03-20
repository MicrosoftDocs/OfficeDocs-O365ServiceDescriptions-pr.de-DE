---
title: Exchange Online Protection-Dienstbeschreibung
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Abrufen von Informationen zu Features und Anforderungen für Exchange Online Protection. Enthalten ist eine Liste von Plänen, die Exchange Online Protection bereitstellen, sowie einen Vergleich der Features in diesen Plänen.
ms.openlocfilehash: 187ec7cee1b045a9e859e1157cddef29059cac2b
ms.sourcegitcommit: ab82834030929e1583074b3f5b0b27182746fff4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/19/2021
ms.locfileid: "50901936"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection-Dienstbeschreibung

Abrufen von Informationen zu Features und Anforderungen für Exchange Online Protection. Enthalten ist eine Liste von Plänen, die Exchange Online Protection bereitstellen, sowie einen Vergleich der Features in diesen Plänen.

Microsoft Exchange Online Protection (EOP) ist ein cloudbasierter Dienst zum Filtern von E-Mails, mit dem Sie Ihre Organisation vor Spam und Schadsoftware schützen können. EOP kann die Verwaltung Ihrer Messagingumgebung und viele der beschwerlichen Aufgaben bei der Verwaltung lokaler Hardware und Software vereinfachen.

In der folgenden Liste werden die wichtigsten Möglichkeiten beschrieben, wie Sie EOP für den Messagingschutz verwenden können:

- **In einem eigenständigen Szenario:** EOP bietet cloudbasierten E-Mail-Schutz für Ihre lokale E-Mail-Umgebung (Exchange Server oder andere lokale SMTP-E-Mail-Lösungen).

- **Im Rahmen von Microsoft Exchange Online**: Standardmäßig schützt EOP in der Cloud gehostete Exchange Online-Postfächer. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online-Dienstbeschreibung](../exchange-online-service-description/exchange-online-service-description.md).

- **In einer Hybridbereitstellung:** EOP kann konfiguriert werden, um Ihre Messagingumgebung zu schützen und das E-Mail-Routing zu steuern, wenn Sie über eine Mischung aus lokalen und Cloudpostfächern verfügen.

## <a name="available-plans"></a>Verfügbare Pläne

Ausführliche Planinformationen zu Abonnements, die Benutzer für Exchange Online Protection aktivieren, finden Sie in der [vollständigen Abonnementvergleichstabelle](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans).

Weitere Informationen zum Kauf von Exchange Online Protection finden Sie unter [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

> [!NOTE]
> EOP ersetzt Forefront Online Protection for Exchange (FOPE). Alle FOPE-Kunden wurden zu EOP übertragen.

## <a name="whats-new-in-exchange-online-protection-eop"></a>Neues in Exchange Online Protection (EOP)

Die [Microsoft 365-Roadmap](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) ist eine gute Ressource, um Informationen zu bevorstehenden neuen Features zu erhalten.

## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection-Pläne (EOP)

EOP ist über die folgenden Abonnementpläne verfügbar:<br><br>

| Plan | Beschreibung |
|:-----|:-----|
|[EOP als eigenständige Lösung](https://products.office.com/exchange/exchange-email-security-spam-protection)|Ein separater cloudbasierter Dienst, der Ihre lokale E-Mail-Organisation schützt.|
|[EOP-Funktionen in Exchange Online](https://products.office.com/exchange/compare-microsoft-exchange-online-plans)|Der integrierte Schutz für Ihre in der Cloud gehosteten Exchange Online-Postfächer.|
|[Exchange Enterprise CAL mit Diensten](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)|Add-On-Lizenzen, die Sie für Ihre lokale Exchange-Organisation erwerben, die EOP und andere cloudbasierte Features enthalten (Weitere Informationen finden Sie im nächsten Abschnitt).|

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL mit Diensten

Microsoft Exchange Enterprise CAL with Services bietet die E-Mail-Schutzfunktionen von EOP und die folgenden zusätzlichen cloudbasierten Features:

- [Verhinderung von Datenverlusten (Data Loss Prevention, DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Berichterstellung mit Webdiensten](reporting-and-message-trace.md#reporting-using-web-services)

Weitere Informationen zur Exchange Enterprise CAL with Services-Lizenzierung finden Sie unter Häufig gestellte Fragen zur [Exchange-Lizenzierung](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business).

Wenn Sie über Exchange Enterprise CAL mit Services-Lizenzen verfügen und EOP bereitstellen möchten, befolgen Sie die Anweisungen unter [Einrichten Ihres EOP-Diensts.](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-your-eop-service) Die Installationsschritte sind mit den Schritten für die Installation der eigenständigen EOP-Lösung identisch.

> [!NOTE]
> Neue Funktionen für Exchange Enterprise CAL mit Diensten werden gleichzeitig mit Exchange Online bereitgestellt, nicht mit der eigenständigen Installation von EOP. Beachten Sie, dass sich die Bereitstellungszeitpläne für EOP als eigenständige Installation und Exchange Online/Exchange Enterprise CAL mit Diensten geringfügig unterscheiden können.

## <a name="requirements-for-exchange-online-protection-eop"></a>Anforderungen für Exchange Online Protection (EOP)

EOP kann mit jedem SMTP-E-Mail-Übertragungs-Agent verwendet werden, z. B. Microsoft Exchange Server. Informationen zu den von EOP unterstützten Betriebssystemen, Webbrowsern und Sprachen finden Sie in den Abschnitten "Unterstützte Browser" und "Unterstützte Sprachen" im [Exchange Admin Center in Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="limits"></a>Grenzwerte

Einschränkungen in EOP finden Sie unter [Exchange Online Protection limits](exchange-online-protection-limits.md).

## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Verfügbarkeit von Features in EOP-Plänen (Exchange Online Protection)

Jedes Funktion ist unten aufgeführt. Detailliertere Informationen zu EOP-Funktionen finden Sie unter den Links in der Tabelle. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.<br><br>

| Feature | EOP als eigenständige Lösung | EOP-Funktionen in Exchange Online | Exchange Enterprise CAL mit Diensten|
|:-----|:-----|:-----|:-----|
|[E-Mail-Empfänger](recipient-domain-and-company-management.md#mail-recipients)|Ja<sup>1</sup>|Ja<sup>1</sup>|Ja|
|[Berechtigungen für Administratorrollengruppen](recipient-domain-and-company-management.md#admin-role-group-permissions)|Ja<sup>2</sup>|Ja|Ja|
|[Domänenverwaltung](recipient-domain-and-company-management.md#domain-management)|Ja<sup>3</sup>|Ja<sup>3</sup>|Ja<sup>3</sup>|
|[Untergeordnete Domänen abgleichen](recipient-domain-and-company-management.md#match-subdomains)|Ja|Ja|Nein|
|[Verzeichnisbasierte Edge-Blockierung (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb)|Ja|Ja|Ja|
|[Nachrichtenflussregeln](../exchange-online-service-description/message-policy-and-compliance.md#mail-flow-rules)|Ja<sup>4</sup>|Ja<sup>4, 6</sup>|Ja|
|[Überwachungsprotokollierung](messaging-policy-and-compliance-servicedesc.md#audit-logging)|Ja<sup>5</sup>|Ja|Ja|
|[Verhinderung von Datenverlusten (Data Loss Prevention, DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)|Nein|Ja|Ja<sup>6</sup>|
|[Office 365-Nachrichtenverschlüsselung](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption)|Ja<sup>12</sup>|Ja|Ja<sup>12</sup>|
|[Antispamschutz](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (integriert)|Ja|Ja|Ja|
|[Anpassung von Antispamrichtlinien](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies)|Ja<sup>7</sup>|Ja|Ja|
|[Schutz vor Schadsoftware](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (integriert)|Ja<sup>13</sup>|Ja|Ja|
|[Anpassung von Antischadsoftwarerichtlinien](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies)|Ja|Ja|Ja|
|[Quarantäne](anti-spam-and-anti-malware-protection-eop.md#quarantine): Verwaltung durch Administrator|Ja|Ja|Ja|
|[Quarantäne](anti-spam-and-anti-malware-protection-eop.md#quarantine): Selbstverwaltung durch Endbenutzer|Ja|Ja|Ja|
|[Übermittlung](anti-spam-and-anti-malware-protection-eop.md#report-messages-to-microsoft-for-analysis)|Nein|Ja|Nein|
|[Melden von Nachrichten-Add-Ins für Outlook](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in)|Ja|Ja|Ja|
|[Junk-E-Mail-Berichterstellung in Outlook im Web](https://docs.microsoft.com/microsoft-365/security/office-365-security/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop)|Ja|Ja|Ja|
|[Weiterleiten von E-Mails zwischen Microsoft und Ihren eigenen E-Mail-Servern](mail-flow-eop.md#routing-email-between-microsoft-and-your-own-email-servers)|Ja|Ja|Ja|
|[Sichere Nachrichten mit einem vertrauenswürdigen Partner](mail-flow-eop.md#secure-messaging-with-a-trusted-partner)|Ja|Ja|Ja|
|[Übernehmen der IP-Adresse eines Partners in die Liste für sichere Absender (Safe List)](mail-flow-eop.md#safe-listing-a-partners-ip-address)|Ja|Ja|Ja|
|[Bedingtes E-Mail-Routing](mail-flow-eop.md#conditional-mail-routing)|Ja|Ja|Ja|
|[Hybrides E-Mail-Routing](mail-flow-eop.md#hybrid-mail-routing)|Ja|Ja|Ja|
|[Microsoft 365 Admin Center-Berichte](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Ja<sup>9</sup>|Ja<sup>10</sup>|Ja <sup>9, 10</sup>|
|[Berichterstellung mit Webdiensten](reporting-and-message-trace.md#reporting-using-web-services)|Nein|Ja|Ja|
|[Nachrichtenablaufverfolgung](reporting-and-message-trace.md#message-trace)|Ja<sup>15</sup>|Ja<sup>15</sup>|Ja|
|[Zugriff auf das Microsoft 365 Admin Center](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center)|Ja|Ja|Ja|
|[Zugriff auf das Exchange Admin Center](administration-and-management-eop.md#access-to-the-exchange-admin-center (EAC))|Ja|Ja|Ja|
|[Remote Windows PowerShell access](administration-and-management-eop.md#remote-windows-powershell-access)|Ja|Ja|Ja|

<sup>1</sup> E-Mail-Benutzer werden als „Postfächer" definiert und können zusammen mit externen E-Mail-Kontakten direkt in der Exchange-Verwaltungskonsole hinzugefügt, entfernt und anderweitig verwaltet werden. <br/>
<sup>2</sup> Keine RBAC-Anpassung. Nur Administratorrollen. <br/>
<sup>3</sup> In der Exchange-Verwaltungskonsole können verwaltete Domänen angezeigt und Domänentypen bearbeitet werden. Alle anderen Domänenverwaltungen müssen im Microsoft 365 Admin Center durchgeführt werden.<br/>
<sup>4</sup> Nachrichtenflussregeln (auch als Transportregeln bezeichnet) in EOP werden unter [Nachrichtenflussregeln (Transportregeln) in Exchange Online Protection beschrieben.](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0) Die verfügbaren Nachrichtenflussregelbedingungen, Ausnahmen und Aktionen unterscheiden sich geringfügig zwischen EOP und Exchange Online. Diese Unterschiede werden in Nachrichtenflussregelbedingungen und Ausnahmen [(Prädikate) in Exchange Online-](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) und [Nachrichtenflussregelaktionen in Exchange Online festgestellt.](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)<br/>
<sup>5</sup> EOP-Überwachungsberichte sind eine Teilmenge der Exchange Online-Überwachungsberichte und enthalten keine Informationen zu Postfächern. <br/>
<sup>6</sup> DLP-Richtlinientipps sind für Kunden von Exchange Enterprise CAL mit Diensten nicht verfügbar.  <br/>
<sup>7</sup> Die standardmäßige Inhaltsfilteraktion besteht darin, Spamnachrichten in die Junk-E-Mail-Ordner der Empfänger zu verschieben. Damit dies mit lokalen Exchange-Postfächern funktioniert, müssen Sie auch zwei Transportregeln in Ihrer lokalen Exchange-Organisation konfigurieren, um von EOP hinzugefügte Spamheader zu erkennen. Weitere Informationen finden Sie unter [Configure standalone EOP to deliver spam to the Junk Email folder in hybrid environments](https://docs.microsoft.com/microsoft-365/security/office-365-security/ensure-that-spam-is-routed-to-each-user-s-junk-email-folder). <br/>
<sup>9</sup> Die EOP-Berichte sind eine Teilmenge der Exchange Online-Berichte und enthalten keine Informationen zu Postfächern.<br/>
<sup>10</sup> Enthält DLP-Berichte. <br/>
<sup>12</sup> Wird für lokale Kunden unterstützt, die Azure Information Protection erwerben und Exchange Online Protection zum Routen von E-Mails über Exchange Online verwenden. <br/>
<sup>13</sup> Scannt ein- und ausgehende Nachrichten, aber keine internen Nachrichten, die ein Absender in Ihrer Organisation an einen Empfänger in Ihrer Organisation gesendet hat. <br/>
<sup>15</sup> Hybridsetup steht nicht über den Hybrid-Assistenten zur Verfügung, Sie können die Einrichtung jedoch manuell vornehmen, wenn Sie über Exchange SP1 verfügen.
