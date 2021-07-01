---
title: Exchange Online Protection-Dienstbeschreibung
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Abrufen von Informationen zu Features und Anforderungen für Exchange Online Protection. Enthalten ist eine Liste von Plänen, die Exchange Online Protection bereitstellen, sowie ein Vergleich der Features zwischen diesen Plänen.
ms.openlocfilehash: fbfbe39931e6037b358bb76c124937904a408783
ms.sourcegitcommit: 427dbb27426a12e8c5dba7d8b4cbaf2bedb3aaba
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/30/2021
ms.locfileid: "53222482"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection-Dienstbeschreibung

Abrufen von Informationen zu Features und Anforderungen für Exchange Online Protection. Enthalten ist eine Liste von Plänen, die Exchange Online Protection bereitstellen, sowie ein Vergleich der Features zwischen diesen Plänen.

Microsoft Exchange Online Der Schutz (EOP) ist ein cloudbasierter E-Mail-Filterdienst, der Ihre Organisation vor Spam und Schadsoftware schützt und Features zum Schutz Ihrer Organisation vor Verstößen gegen Nachrichtenrichtlinien enthält. EOP kann die Verwaltung Ihrer Messagingumgebung und viele der beschwerlichen Aufgaben bei der Verwaltung lokaler Hardware und Software vereinfachen.

In der folgenden Liste werden die primären Möglichkeiten beschrieben, wie Sie EOP für den Messagingschutz verwenden können:

- **In einem eigenständigen Szenario:** EOP bietet cloudbasierten E-Mail-Schutz für Ihre lokale E-Mail-Umgebung (Exchange Server oder andere lokale SMTP-E-Mail-Lösungen).

- **Als Teil von Microsoft Exchange Online:** EOP schützt standardmäßig Exchange Online in der Cloud gehosteten Postfächer. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online Dienstbeschreibung.](../exchange-online-service-description/exchange-online-service-description.md)

- **In einer Hybridbereitstellung:** EOP kann konfiguriert werden, um Ihre Messagingumgebung zu schützen und das E-Mail-Routing zu steuern, wenn Sie über eine Kombination aus lokalen und Cloudpostfächern verfügen.

## <a name="available-plans"></a>Verfügbare Pläne

In der folgenden Tabelle sind die Pläne aufgeführt, die Exchange Online Protection enthalten, damit Sie die Lösung auswählen können, die den Anforderungen Ihrer Organisation am besten entspricht. Ausführliche Informationen zum Plan finden Sie unter [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).

Ausführliche Informationen zu Abonnements, die Benutzern Exchange Online Protection ermöglichen, finden Sie in der [vollständigen Abonnementvergleichstabelle.](https://www.microsoft.com/microsoft-365/compare-microsoft-365-enterprise-plans)

### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL mit Diensten

Microsoft Exchange Enterprise CAL mit Diensten bietet die E-Mail-Schutzfunktionen von EOP und die folgenden zusätzlichen cloudbasierten Features:

- [Verhinderung von Datenverlust](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)

- [Berichterstellung mit Webdiensten](reporting-and-message-trace.md#reporting-using-web-services)

Weitere Informationen zu Exchange Enterprise CAL mit Services-Lizenzierung finden Sie unter Exchange Häufig gestellte Fragen zur [Lizenzierung.](https://products.office.com/exchange/microsoft-exchange-licensing-faq-email-for-business)

Wenn Sie über Exchange Enterprise CAL mit Dienstlizenzen verfügen und EOP bereitstellen möchten, folgen Sie den Anweisungen unter [Einrichten Ihres EOP-Diensts.](/microsoft-365/security/office-365-security/set-up-your-eop-service) Die Installationsschritte sind mit den Schritten für die Installation der eigenständigen EOP-Lösung identisch.

> [!NOTE]
> Neue Funktionen für Exchange Enterprise CAL mit Diensten werden gleichzeitig mit Exchange Online bereitgestellt, nicht mit der eigenständigen Installation von EOP. Beachten Sie, dass sich die Bereitstellungszeitpläne für EOP als eigenständige Installation und Exchange Online/Exchange Enterprise CAL mit Diensten geringfügig unterscheiden können.

## <a name="requirements-for-exchange-online-protection-eop"></a>Anforderungen für Exchange Online Protection (EOP)

EOP kann mit jedem SMTP-E-Mail-Übertragungs-Agent verwendet werden, z. B. Microsoft Exchange Server. Informationen zu den Betriebssystemen, Webbrowsern und Sprachen, die von EOP unterstützt werden, finden Sie in den Abschnitten "Unterstützte Browser" und "Unterstützte Sprachen" im [Exchange Admin Center in Exchange Online Protection.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="limits"></a>Einschränkungen

Grenzwerte in EOP finden Sie unter [Exchange Online Protection Grenzwerten.](exchange-online-protection-limits.md)

## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

In der folgenden Tabelle sind die wichtigsten Exchange Online Protection Features aufgeführt, die in allen Plänen verfügbar sind. Einige Vorbehalte gelten. Lesen Sie die Fußnoten für weitere Informationen. Diese Tabelle kann ohne vorherige Ankündigung geändert werden. Die aktuellste, vollständige Liste der Features finden Sie unter ["Leistungsstarke Tools zur Unterstützung Ihres Unternehmens".](https://products.office.com/business/compare-more-office-365-for-business-plans)

| Feature | Eigenständiger EOP | EOP in EE CAL mit Diensten | EOP-Funktionen in Exchange Online |
|:-----|:-----|:-----|:-----|
|**Schutz**||||
|Antischadsoftwarerichtlinien (integriert und benutzerdefinierte Richtlinien)|Ja|Ja|Ja|
|Eingehende Antispamrichtlinien (integriert und benutzerdefinierte)|Ja|Ja|Ja|
|Ausgehende Antispamrichtlinien (integriert und benutzerdefinierte)|Ja|Ja|Ja|
|Verbindungsfilterung (IP-Zulassungsliste und LISTE blockierter IP-Adressen)|Ja|Ja|Ja|
|Antiphishingrichtlinien (integriert und benutzerdefinierte Richtlinien)|Ja|Ja|Ja|
|Antispoofingschutz (integriert und benutzerdefinierte)|Ja|Ja|Ja|
|Zero-Hour Auto Purge (ZAP) für zugestellte Schadsoftware, Spam und Phishing-Nachrichten<sup>10</sup>|Nein|Nein|Ja|
|Voreingestellte Sicherheitsrichtlinien|Ja|Ja|Ja|
|Konfigurationsanalyse für Schutzrichtlinien|Ja|Ja|Ja|
|Mandanten-Zulassungs-/Sperrliste|Ja|Ja|Ja|
|Blockieren von Listen für Nachrichtensender|Ja|Ja|Ja|
|Zulassungslisten für Nachrichtensender|Ja|Ja|Ja|
|Blockieren von Edges|Ja|Ja|Ja|
|Verzeichnisbasierte Edgeblockierung (Directory Based Edge Blocking, DBEB) für nicht vorhandene Empfänger|Ja|Ja|Ja|
|**Quarantäne und Übermittlungen**||||
|Administratorübermittlung<sup>10</sup>|Nein|Nein|Ja|
|Benutzerübermittlung (benutzerdefiniertes Postfach)<sup>10</sup>|Nein|Nein|Ja|
|Administratorquarantäne|Ja|Ja|Ja|
|Quarantäne für Endbenutzer|Ja|Ja|Ja|
|Add-In "Nachricht melden" und "Phishing melden" für Outlook|Ja|Ja|Ja|
|**Nachrichtenfluss**||||
|Nachrichtenflussregeln (Transportregeln)<sup>4</sup>|Ja|Ja<sup>6</sup>|Ja|
|Akzeptierte Domänen<sup>3</sup> |Ja|Ja|Ja|
|Connectors|Ja|Ja|Ja|
|Erweiterte Filterung für Connectors (Auflistung überspringen)|Ja|Ja|Ja|
|**Überwachen**||||
|Message trace|Ja|Ja|Ja|
|E-Mail- und Sicherheitsberichte im Microsoft 365 Admin Center|Ja<sup>7</sup>|Ja<sup>7,8</sup>|Ja<sup>8</sup>|
|Sicherheitsberichte im Microsoft 365 Security Center|Ja<sup>7</sup>|Ja<sup>7,8</sup>|Ja<sup>8</sup>|
|E-Mail-Berichte im EAC|Ja<sup>7</sup>|Ja<sup>7,8</sup>|Ja<sup>8</sup>|
|Administratorüberwachungsprotokollierung<sup>5</sup>|Ja|Ja|Ja|
|**Users**||||
|E-Mail-Benutzer und E-Mail-Kontakte<sup>1</sup>|Ja|Ja|Ja|
|Postfächer|Nein|Nein|Ja<sup>1a</sup>|
|Rollenbasierte Zugriffssteuerung (RBAC)<sup>2</sup>|Ja|Ja|Ja|
|**Compliance**||||
|Verhinderung von Datenverlust für E-Mails|Nein|Ja|Ja|
|Office 365-Nachrichtenverschlüsselung|No<sup>9</sup>|No<sup>9</sup>|Ja|
|**Verwaltung**||||
|Microsoft 365 Admin Center|Ja|Ja|Ja|
|Exchange Admin-Center|Ja|Ja|Ja|
|Microsoft 365 Security Center|Ja|Ja|Ja|
|Eigenständige Exchange Online Protection PowerShell|Ja|Nein|Nein|
|Exchange Online PowerShell|Nein|Ja|Ja|

<sup>1</sup> Sie erstellen, entfernen und bearbeiten E-Mail-Benutzer und E-Mail-Kontakte im EAC. <br/>
<sup>1a</sup> Sie erstellen und entfernen Postfächer im Microsoft 365 Admin Center. Sie können vorhandene Postfächer im EAC bearbeiten. <br/>
<sup>2</sup> In eigenständigen EOP- und EE CAL mit Diensten gibt es keine Endbenutzerrollen oder Rollenzuweisungsrichtlinien.<br/>
<sup>3</sup> Sie fügen Domänen im Microsoft 365 Admin Center hinzu und entfernen sie.  Im EAC konfigurieren Sie Domänen als autoritativ oder nicht autoritativ.<br/>
<sup>4</sup> Einige Regelbedingungen, Ausnahmen und Aktionen sind in der eigenständigen EOP oder der EOP in EE CAL mit Diensten nicht verfügbar. Diese Unterschiede werden in Exchange Online Inhalt der Nachrichtenflussregel deutlich hervorgehoben. <br/>
<sup>5</sup> In eigenständiger EOP und EE CAL mit Diensten:

- Postfachüberwachungsberichte sind nicht verfügbar.
- Der Administratorrollengruppenbericht und der Administratorüberwachungsprotokollbericht sind die einzigen Administratorüberwachungsberichte im EAC.
- Überwachungsprotokollexport nur über PowerShell verfügbar. <br/>

<sup>6</sup> DLP-Richtlinientipps sind in EE CAL mit Diensten nicht verfügbar. <br/>
<sup>7</sup> Berichte in eigenständiger EOP und EE CAL mit Diensten sind eine Teilmenge der Exchange Online Berichte (Berichte, die sich auf Postfächer beziehen).<br/>
<sup>8</sup> Umfasst DLP-Berichte. <br/>
<sup>9</sup> Sie können Azure Information Protection als Add-On-Abonnement erwerben und OME verwenden, wenn Sie Ihre lokale E-Mail-Umgebung so konfigurieren, dass E-Mails über EOP an das und aus dem Internet weitergeleitet werden. <br/>
<sup>10</sup> Dieses Feature erfordert Exchange Online Postfächer. <br/>

## <a name="learn-more"></a>Weitere Informationen

Technische Informationen zu Exchange Online Protection finden Sie in den folgenden Ressourcen:

Die [Microsoft 365 Roadmap](https://office.microsoft.com/products/office-365-roadmap-FX104343353.aspx) ist eine gute Ressource, um Informationen zu bevorstehenden neuen Features zu finden.

### <a name="licensing-terms"></a>Lizenzierungsbedingungen

Lizenzierungsbestimmungen für Produkte und Dienste, die Sie über kommerzielle Volumenlizenzierungsprogramme von Microsoft erworben haben, finden Sie auf der [Website für Produktbestimmungen](https://www.microsoft.com/licensing/terms/).

### <a name="messaging"></a>Nachrichten

Um den Überblick über bevorstehende Änderungen zu behalten, einschließlich neuer und geänderter Funktionen, geplanter Wartungsarbeiten oder anderer wichtiger Ankündigungen, besuchen Sie das Nachrichtencenter. Weitere Informationen finden Sie unter [Nachrichtencenter](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Barrierefreiheit

Microsoft bleibt der Sicherheit Ihrer Daten und der [Barrierefreiheit](https://www.microsoft.com/trust-center/compliance/accessibility) unserer Dienste verpflichtet. Weitere Informationen finden Sie im [Microsoft Trust Center](https://www.microsoft.com/trust-center) und dem [Office-Barrierefreiheitscenter](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
