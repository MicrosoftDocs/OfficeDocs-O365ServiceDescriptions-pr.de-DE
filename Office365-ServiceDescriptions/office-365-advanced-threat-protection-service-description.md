---
title: Microsoft Defender für Office 365-Dienstbeschreibung
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender for Office 365 ist ein cloudbasierter E-Mail-Filterdienst, der Ihre Organisation vor unbekannter Malware und Viren schützt, indem sie einen robusten Zero-Day-Schutz bietet, und funktionen, um Ihre Organisation vor schädlichen Links in Echtzeit zu schützen.
ms.openlocfilehash: 76b4d2e53c8a2942d4b974c5289c9ae4c8854b72
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52545972"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defender für Office 365-Dienstbeschreibung

Microsoft Defender for Office 365 ist ein cloudbasierter E-Mail-Filterdienst, der Ihre Organisation vor unbekannter Malware und Viren schützt, indem sie einen robusten Zero-Day-Schutz bietet, und funktionen, um Ihre Organisation vor schädlichen Links in Echtzeit zu schützen. Defender for Office 365 verfügt über umfangreiche Reporting- und URL-Trace-Funktionen, die Administratoren Einen Einblick in die Art von Angriffen in Ihrer Organisation geben.

Im Folgenden finden Sie die wichtigsten Möglichkeiten, defender for Office 365 für den Nachrichtenschutz zu verwenden:

- In einem Nur-Office 365-Filterszenario bietet Defender for Office 365 cloudbasierten E-Mail-Schutz für Ihre lokale Exchange Server Umgebung oder jede andere lokale SMTP-E-Mail-Lösung.

- Defender for Office 365 kann aktiviert werden, um Exchange Online in der Cloud gehosteten Postfächer zu schützen. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online Servicebeschreibung](exchange-online-service-description/exchange-online-service-description.md).

- In einer Hybridbereitstellung kann Defender for Office 365 so konfiguriert werden, dass Sie Ihre Messagingumgebung schützen und das E-Mail-Routing steuern, wenn Sie über eine Mischung aus lokalen und Cloudpostfächern mit Exchange Online Protection für die Filterung eingehender E-Mails verfügen.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender für Office 365 Verfügbarkeit

Microsoft Defender für Office 365 Plan 2 ist in Office 365 E5, Office 365 A5, Microsoft 365 E5 Security und Microsoft 365 E5 enthalten, wie hier angegeben: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defender for Office 365 Plan 1 ist in Microsoft 365 Business Premium enthalten.

Sie können Defender for Office 365 zu den folgenden Exchange- und Microsoft 365-Abonnementplänen hinzufügen:

- Exchange Online Plan 1

- Exchange Online Plan 2

- Exchange Online-Kiosk

- Exchange Online Protection

- Microsoft 365 Business Basic

- Microsoft 365 Business Standard

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F3

- Office 365 A1

- Office 365 A3

Informationen zum Kauf von Microsoft Defender für Office 365 finden Sie unter [Microsoft Defender for Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Ausführliche Planinformationen zu Abonnements, die Benutzer für Microsoft Defender für Office 365 aktivieren, finden Sie in der [vollständigen Tabelle zum Abonnementvergleich](https://go.microsoft.com/fwlink/?linkid=2139145).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Neuerungen in Microsoft Defender für Office 365

Wir fügen Defender weiterhin neue Funktionen für Office 365 hinzu. Weitere Informationen zu neuen Funktionen, die zu Defender for Office 365 (oder Microsoft 365 im Allgemeinen) kommen, finden Sie in den folgenden Ressourcen:

- [Microsoft 365-Roadmap](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Neuerungen in Microsoft Defender für Office 365](/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Anforderungen an Microsoft Defender für Office 365

Defender for Office 365 kann mit jedem SMTP-Mailübertragungs-Agent verwendet werden, z. B. Microsoft Exchange Server. Informationen zu den Betriebssystemen, Webbrowsern und Sprachen, die von Defender for Office 365 unterstützt werden, finden Sie in den Abschnitten "Unterstützte Browser" und "Unterstützte Sprachen" in [Exchange Admin Center in Exchange Online Protection](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Feature-Verfügbarkeit für Office 365-Pläne

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.<br><br>

| Feature | Microsoft Defender für Office 365 Plan 1 | Microsoft Defender für Office 365 Plan 2 | Microsoft 365 E5 / A5 Sicherheit|
|:-----|:-----|:-----|:-----|
|*Konfiguration, Schutz und Erkennung*|
|[Sichere Anlagen](#safe-attachments)|Ja|Ja|Ja|
|Sichere Anlagen in Teams|Ja|Ja|Ja|
|[Sichere Links](#safe-links)|Ja|Ja|Ja|
|[Sichere Dokumente](#safe-documents)|Nein|Nein|Ja|
|Sichere Links in Teams|Ja|Ja|Ja|
|[ATP für SharePoint, OneDrive und Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Ja|Ja|Ja|
|[Antiphishingrichtlinien](#anti-phishing-policies)|Ja|Ja|Ja|
|[Echtzeitberichte](#real-time-reports)|Ja|Ja|Ja|
|*Automatisierung, Untersuchung, Sanierung und Bildung*|
|[Bedrohungs-Tracker](#threat-trackers)|Nein|Ja|Ja|
|Bedrohungsuntersuchung (erweiterte Bedrohungsuntersuchung)|[Echtzeiterkennungen](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Automatisierte Reaktion auf Vorfälle](#automated-incident-response)|Nein|Ja|Ja|
|[Angriffssimulationstraining](#attack-simulation-training)|Nein|Ja|Ja|
|*Integration mit [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|Nein|Ja|Ja|

> [!NOTE]
> Wenn Ihr Mandant nur über Microsoft Defender für Office Plan P2-Testlizenz oder Office 365 E5-Testlizenz verfügt, ohne dass eine andere berechtigte Lizenz für Microsoft 365 Defender berechtigt ist, können Sie nicht auf Microsoft 365 Defender zugreifen. Weitere Informationen zur MTP-Lizenz finden Sie unter [Microsoft 365 Defender-Anforderungen](/microsoft-365/security/mtp/prerequisites).

## <a name="defender-for-office-365-capabilities"></a>Defender für Office 365 Fähigkeiten

### <a name="safe-attachments"></a>Sichere Anlagen

[Sichere Anlagen](/microsoft-365/security/office-365-security/atp-safe-attachments) schützen vor unbekannter Malware und Viren und bieten Zero-Day-Schutz zum Schutz Ihres Messaging-Systems. Alle Nachrichten und Anhänge, die keine bekannte Viren-/Malwaresignatur haben, werden an eine spezielle Umgebung weitergeleitet, in der Defender for Office 365 eine Vielzahl von Machine Learning- und Analysetechniken verwendet, um böswillige Absichten zu erkennen. Wenn keine verdächtige Aktivität ermittelt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben.

> [!NOTE]
> Das Scannen sicherer Anlagen findet in derselben Region statt, in der sich Ihre Office 365 Daten befinden. Weitere Informationen zur Geografie des Rechenzentrums finden Sie unter [Wo befinden sich Ihre Daten?](https://products.office.com/where-is-your-data-located?geo=All).

### <a name="safe-links"></a>Sichere Links

Die Funktion ["Sichere Links"](/microsoft-365/security/office-365-security/atp-safe-links) schützt Ihre Benutzer proaktiv vor schädlichen URLs in einer Nachricht oder in einem Office Dokument. Der Schutz verbleibt, wenn sie auf den Link klicken, da böswillige Links dynamisch blockiert werden, während der Zugriff auf unbedenkliche Links gewährt wird.

Für URLs in den folgenden Apps steht „Sichere Links“ zur Verfügung:

- Microsoft 365 Apps for Enterprise auf Windows oder Mac

- Office für das Web (Word für das Web, Excel für das Web, PowerPoint für das Web und OneNote für das Web)

- Word, Excel und PowerPoint auf Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Defender für Office 365 lizenziert sein, müssen in safe <sup>\*</sup> Links-Richtlinien enthalten sein und auf ihren Geräten angemeldet sein, damit der Schutz vorhanden ist.
>
> <sup>\*</sup>Für organisationsweite Defender for Office 365-Lizenzen (z. B. ATP_ENTERPRISE_FACULTY) müssen Sie Defender for Office 365-Lizenzen nicht einzelnen Benutzern zuweisen.
>
> Weitere Informationen zum Schutz sicherer Links finden Sie [unter Sichere Links in Microsoft Defender für Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Sichere Dokumente

Die Funktion [Sichere Dokumente](/microsoft-365/security/office-365-security/safe-docs) verwendet Microsoft Defender [for Endpoint,](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) um Dokumente und Dateien zu scannen, die in [der geschützten Ansicht](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)geöffnet werden.

Was sollten Sie wissen, bevor Sie beginnen?

- Sichere Dokumente sind jetzt allgemein für Benutzer mit Office Version 2004 (12730.x) oder höher verfügbar! Diese Funktion ist standardmäßig deaktiviert und muss vom Sicherheitsadministrator aktiviert werden.

- Diese Funktion ist nur für Benutzer mit der Microsoft 365 E5- oder Microsoft 365 E5 Security-Lizenz verfügbar (nicht in Defender for Office 365-Pläneenthalten).

- Word, Excel und PowerPoint auf Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Microsoft 365 E5 oder Microsoft 365 E5 Security lizenziert sein, müssen in den Richtlinien für <sup>\*</sup> sichere Dokumente enthalten sein und auf ihren Geräten angemeldet sein, damit der Schutz vorhanden ist.
>
> Weitere Informationen zum Schutz sicherer Dokumente finden Sie [unter Sichere Dokumente in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP für SharePoint, OneDrive und Microsoft Teams

[ATP für SharePoint, OneDrive und Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) hilft beim Erkennen und Blockieren von Dateien, die in Teamwebsites und Dokumentbibliotheken als bösartig identifiziert werden. Darüber hinaus ist Safe Links-Schutz jetzt in Microsoft Teams Kanälen und Chats verfügbar.

### <a name="anti-phishing-policies"></a>Antiphishing-Richtlinien

[Anti-Phishing](/microsoft-365/security/office-365-security/atp-anti-phishing) überprüft eingehende Nachrichten auf Indikatoren, dass es sich bei einer Nachricht um einen Phishingversuch handelt. Wenn Benutzer von Defender for Office 365-Richtlinien (Safe Attachments, Safe Links oder Anti-Phishing) abgedeckt werden, werden eingehende Nachrichten von mehreren Machine Learning-Modellen ausgewertet, die Nachrichten analysieren, und die entsprechenden Maßnahmen werden basierend auf den konfigurierten Richtlinien ausgeführt.

### <a name="real-time-reports"></a>Echtzeitberichte

Zu den Überwachungsfunktionen, die im Security & Compliance Center ( ) verfügbar sind, [https://protection.office.com](https://protection.office.com) gehören [Echtzeitberichte und Einblicke,](/microsoft-365/security/office-365-security/view-reports-for-atp) mit denen sich Ihre Sicherheits- und Compliance-Administratoren auf Probleme mit hoher Priorität wie Sicherheitsangriffe oder erhöhte verdächtige Aktivitäten konzentrieren können. Smart Reports und Insights heben nicht nur Problembereiche hervor, sondern enthalten auch Empfehlungen und Links zum Anzeigen und Erkunden von Daten sowie schnelle Maßnahmen.

### <a name="explorer"></a>Explorer

Der Explorer (auch als Sicherheitsrisiken-Explorer bezeichnet) ist ein Echtzeitbericht, der es Ihnen ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Standardmäßig werden in diesem Bericht Daten für die letzten sieben Tage angezeigt. Ansichten können jedoch geändert werden, um Daten für die letzten 30 Tage anzuzeigen.

Explorer enthält Ansichten, z. B. Malware (für E-Mail und Inhalt), Einsendungen, Phishing und Alle E-Mails. Um zu sehen, wie Explorer mit Echtzeiterkennungen verglichen wird, [laden Sie diese PDF](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)herunter.

Weitere Informationen zu Explorer (in Microsoft Defender for Office 365 Plan 2) und Echtzeiterkennungen (in Microsoft Defender for Office 365 Plan 1) finden Sie unter [Bedrohungs-Explorer und Echtzeiterkennungen](/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Echtzeiterkennungen

Bei Echtzeiterkennungen handelt es sich um einen Echtzeitbericht, der es autorisierten Benutzern ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Ähnlich wie Explorer zeigt dieser Bericht standardmäßig Daten für die letzten sieben Tage an.

Echtzeiterkennungen enthalten Ansichten wie Malware (für E-Mail und Inhalt), Einsendungen und Phishing. Um zu sehen, wie Echtzeit-Erkennungen mit Explorer verglichen werden, [laden Sie diese PDF herunter.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Weitere Informationen zu Explorer (in Microsoft Defender for Office 365 Plan 2) und Echtzeiterkennungen (in Microsoft Defender for Office 365 Plan 1) finden Sie unter [Bedrohungs-Explorer (und Echtzeiterkennungen)](/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Nachverfolgungslisten für Bedrohungen

[Threat Tracker s](/microsoft-365/security/office-365-security/threat-trackers) sind informative Widgets und Ansichten, die autorisierten Benutzern Informationen zu Cybersicherheitsproblemen bereitstellen, die sich auf Ihr Unternehmen auswirken könnten.

### <a name="automated-incident-response"></a>Automatisierte Reaktion auf Vorfälle

[Mit](/microsoft-365/security/office-365-security/office-365-air) den in Defender for Office 365 Plan 2 verfügbaren Funktionen zur automatischen Reaktion auf Vorfälle können Sie automatisierte Untersuchungsprozesse als Reaktion auf bekannte Bedrohungen ausführen, die heute bestehen. Durch automatisierte bestimmte Untersuchungsaufgaben kann Ihr Sicherheitsbetriebsteam effizienter und effektiver arbeiten. Behebungsaktionen, wie das Löschen bösartiger E-Mail-Nachrichten, werden nach Genehmigung durch Ihr Sicherheitsdienstteam durchgeführt. Weitere Informationen finden Sie [unter Funktionsweise von AIR in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Angriffssimulationstraining

[Das Angriffssimulationstraining](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) ist ein intelligentes Social-Risikomanagement-Tool, das die Erstellung und Verwaltung von Phishing-Simulationen automatisiert. Simulationen helfen Kunden dabei, Phishing-Risiken zu erkennen, zu priorisieren und zu beheben, indem sie Phishing-Lures in der realen Welt und hyper-gezielte Schulungen verwenden, um das Verhalten der Mitarbeiter zu ändern.

- Das Angriffssimulationstraining ist jetzt in WW und GCC verfügbar (wird ab dem 21. Juni in GCC sein).
- Weitere Informationen zum Einstieg finden Sie unter [Erste Schritte mit Angriffssimulationstraining](/microsoft-365/security/office-365-security/attack-simulation-training-get-started).
- Es stehen verschiedene Angriffstechniken zur Verfügung, die entwaffente, reale Phishing-Nutzlasten anwenden, die das Verhalten von Angreifern in der realen Welt replizieren, um Phishing-Simulationen relevant zu machen.
- Dieser Dienst steht Organisationen zur Verfügung, die über Microsoft 365 E5, Office 365 E5 oder [Microsoft Defender für Office 365 Plan 2-Lizenzen](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) verfügen. E3-Kunden wird als Testversion eine Teilmenge von Funktionen angeboten.
- Weitere Informationen und das Ausprobieren einer Simulation finden Sie unter [Simulieren eines Phishing-Angriffs](/microsoft-365/security/office-365-security/attack-simulation-training).