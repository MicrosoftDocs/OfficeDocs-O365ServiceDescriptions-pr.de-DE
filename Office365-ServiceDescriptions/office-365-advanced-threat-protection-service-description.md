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
description: Microsoft Defender für Office 365 ist ein cloudbasierter E-Mail-Filterdienst, der Ihre Organisation durch einen robusten Zero-Day-Schutz vor unbekannter Schadsoftware und Viren schützt und Features zum Schutz Ihrer Organisation vor schädlichen Links in Echtzeit bietet.
ms.openlocfilehash: 2f93551be9df45e6108d81da9d7a50bba53be549
ms.sourcegitcommit: 25b208f02689d4ef4b37d36a49135c1b4b5a8204
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/07/2021
ms.locfileid: "52798451"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defender für Office 365-Dienstbeschreibung

Microsoft Defender für Office 365 ist ein cloudbasierter E-Mail-Filterdienst, der Ihre Organisation durch einen robusten Zero-Day-Schutz vor unbekannter Schadsoftware und Viren schützt und Features zum Schutz Ihrer Organisation vor schädlichen Links in Echtzeit bietet. Defender für Office 365 verfügt über umfassende Funktionen für Berichterstellung und URL-Ablaufverfolgung, die Administratoren Einblicke in die Art von Angriffen geben, die in Ihrer Organisation stattfinden.

Es folgen die wichtigsten Möglichkeiten, wie Sie Defender für Office 365 für den Nachrichtenschutz verwenden können:

- In einem Szenario mit nur Filterung für Defender für Office 365 bietet Defender für Office 365 cloudbasierten E-Mail-Schutz für Ihre lokale Exchange Server umgebung oder eine andere lokale SMTP-E-Mail-Lösung.

- Defender für Office 365 kann aktiviert werden, um Exchange Online in der Cloud gehostete Postfächer zu schützen. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online Dienstbeschreibung.](exchange-online-service-description/exchange-online-service-description.md)

- In einer Hybridbereitstellung kann Defender für Office 365 so konfiguriert werden, dass Ihre Messagingumgebung geschützt und das E-Mail-Routing gesteuert wird, wenn Sie über eine Kombination aus lokalen und Cloudpostfächern mit Exchange Online Protection für eingehende E-Mail-Filterung verfügen.

## <a name="microsoft-defender-for-office-365-availability"></a>Verfügbarkeit von Microsoft Defender für Office 365

Microsoft Defender für Office 365 Plan 2 ist in Office 365 E5, Office 365 A5, Microsoft 365 E5 Security und Microsoft 365 E5 enthalten, wie hier angegeben: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](/microsoft-365/security/office-365-security/office-365-atp) . Defender für Office 365 Plan 1 ist in Microsoft 365 Business Premium enthalten.

Sie können Defender für Office 365 den folgenden Exchange und Microsoft 365 Abonnementplänen hinzufügen:

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

Informationen zum Kauf von Microsoft Defender für Office 365 finden Sie unter [Microsoft Defender für Office 365](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Detaillierte Planinformationen zu Abonnements, die Benutzern microsoft Defender für Office 365 ermöglichen, finden Sie in der [vollständigen Vergleichstabelle](https://go.microsoft.com/fwlink/?linkid=2139145)für Abonnements.

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Neuigkeiten in Microsoft Defender für Office 365

Wir werden Defender weiterhin neue Features für Office 365 hinzufügen. Weitere Informationen zu neuen Features, die für Office 365 (oder Microsoft 365 im Allgemeinen) in Defender verfügbar sind, finden Sie in den folgenden Ressourcen:

- [Microsoft 365-Roadmap](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Neuigkeiten in Microsoft Defender für Office 365 – Office 365 | Microsoft-Dokumente](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Anforderungen für Microsoft Defender für Office 365

Defender für Office 365 kann mit jedem SMTP-E-Mail-Übertragungs-Agent verwendet werden, z. B. Microsoft Exchange Server. Informationen zu den Betriebssystemen, Webbrowsern und Sprachen, die von Defender für Office 365 unterstützt werden, finden Sie in den Abschnitten "Unterstützte Browser" und "Unterstützte Sprachen" im [Exchange Admin Center in Exchange Online Protection.](/microsoft-365/security/office-365-security/exchange-admin-center-in-exchange-online-protection-eop)

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Verfügbarkeit von Features in Defender für Office 365-Plänen

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.<br><br>

| Feature | Microsoft Defender für Office 365 Plan 1 | Microsoft Defender für Office 365 Plan 2 | Microsoft 365 E5/A5 Security|
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
|*Automatisierung, Untersuchung, Wartung und Bildung*|
|[Bedrohungs-Tracker](#threat-trackers)|Nein|Ja|Ja|
|Bedrohungsuntersuchung (erweiterte Bedrohungsuntersuchung)|[Echtzeiterkennungen](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Automatisierte Reaktion auf Vorfälle](#automated-incident-response)|Nein|Ja|Ja|
|[Angriffssimulationstraining](#attack-simulation-training)|Nein|Ja|Ja|
|*Integration in [Microsoft 365 Defender](/microsoft-365/security/mtp/microsoft-threat-protection)*|Nein|Ja|Ja|

> [!NOTE]
> Wenn Ihr Mandant nur über eine Testlizenz für Microsoft Defender for Office Plan P2 oder Office 365 E5 verfügt, ohne dass eine andere berechtigte Lizenz für Microsoft 365 Defender besteht, können Sie nicht auf Microsoft 365 Defender zugreifen. Weitere Informationen zur MTP-Lizenz finden Sie unter [Microsoft 365 Defender-Anforderungen.](/microsoft-365/security/mtp/prerequisites)

## <a name="defender-for-office-365-capabilities"></a>Defender für Office 365-Funktionen

### <a name="safe-attachments"></a>Sichere Anlagen

[Sichere Anlagen](/microsoft-365/security/office-365-security/atp-safe-attachments) schützen vor unbekannter Schadsoftware und Viren und bieten Zero-Day-Schutz, um Ihr Messagingsystem zu schützen. Alle Nachrichten und Anlagen, die nicht über eine bekannte Viren-/Schadsoftwaresignatur verfügen, werden an eine spezielle Umgebung weitergeleitet, in der Defender für Office 365 eine Vielzahl von maschinellen Lern- und Analysetechniken verwendet, um böswillige Absichten zu erkennen. Wenn keine verdächtige Aktivität ermittelt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben.

> [!NOTE]
> Die Überprüfung von sicheren Anlagen erfolgt in derselben Region, in der sich Ihre Office 365-Daten befinden. Weitere Informationen zur Geografie des Rechenzentrums finden Sie unter [Wo befinden sich Ihre Daten?](https://products.office.com/where-is-your-data-located?geo=All).

### <a name="safe-links"></a>Sichere Links

Das Feature ["Sichere Links"](/microsoft-365/security/office-365-security/atp-safe-links) schützt Ihre Benutzer proaktiv vor bösartigen URLs in einer Nachricht oder in einem Office Dokument. Der Schutz verbleibt, wenn sie auf den Link klicken, da böswillige Links dynamisch blockiert werden, während der Zugriff auf unbedenkliche Links gewährt wird.

Für URLs in den folgenden Apps steht „Sichere Links“ zur Verfügung:

- Microsoft 365 Apps for Enterprise auf Windows oder Mac

- Office für das Web (Word für das Web, Excel für das Web, PowerPoint für das Web und OneNote für das Web)

- Word, Excel und PowerPoint auf Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Office 365 für Defender lizenziert <sup>\*</sup> sein, in den Richtlinien für sichere Links enthalten sein und auf ihren Geräten angemeldet sein, damit der Schutz aktiviert ist.
>
> <sup>\*</sup>Bei organisationsweiten Defender für Office 365-Lizenzen (z. B. ATP_ENTERPRISE_FACULTY) müssen Sie defender für Office 365 Lizenzen nicht einzelnen Benutzern zuweisen.
>
> Weitere Informationen zum Schutz sicherer Links finden Sie unter ["Sichere Links" in Microsoft Defender für Office 365.](/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Sichere Dokumente

Das Feature ["Sichere Dokumente"](/microsoft-365/security/office-365-security/safe-docs) verwendet [Microsoft Defender für Endpunkt](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) zum Scannen von Dokumenten und Dateien, die in der [geschützten Ansicht](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)geöffnet sind.

Was sollten Sie wissen, bevor Sie beginnen?

- Sichere Dokumente sind jetzt allgemein für Benutzer mit Office Version 2004 (12730.x) oder höher verfügbar! Dieses Feature ist standardmäßig deaktiviert und muss vom Sicherheitsadministrator aktiviert werden.

- Dieses Feature ist nur für Benutzer mit der Microsoft 365 E5 oder Microsoft 365 E5 Security-Lizenz verfügbar (nicht in Defender für Office 365-Pläne enthalten).

- Word, Excel und PowerPoint auf Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Microsoft 365 E5 oder Microsoft 365 E5 Security lizenziert <sup>\*</sup> sein, in richtlinien für sichere Dokumente eingeschlossen sein und auf ihren Geräten angemeldet sein, damit der Schutz aktiviert ist.
>
> Weitere Informationen zum Schutz sicherer Dokumente finden Sie unter ["Sichere Dokumente" in Microsoft 365 E5.](/microsoft-365/security/office-365-security/safe-docs)

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP für SharePoint, OneDrive und Microsoft Teams

[ATP für SharePoint, OneDrive und Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) hilft beim Erkennen und Blockieren von Dateien, die in Teamwebsites und Dokumentbibliotheken als bösartig erkannt werden. Darüber hinaus ist der Schutz vor sicheren Links jetzt in Microsoft Teams Kanälen und Chats verfügbar.

### <a name="anti-phishing-policies"></a>Antiphishing-Richtlinien

[Antiphishing](/microsoft-365/security/office-365-security/atp-anti-phishing) überprüft eingehende Nachrichten auf Indikatoren, dass es sich bei einer Nachricht um einen Phishingversuch handeln könnte. Wenn Benutzer von Defender für Office 365 Richtlinien abgedeckt werden (sichere Anlagen, sichere Links oder Antiphishing), werden eingehende Nachrichten von mehreren Machine Learning-Modellen ausgewertet, die Nachrichten analysieren, und die entsprechende Aktion wird basierend auf den konfigurierten Richtlinien ausgeführt.

### <a name="real-time-reports"></a>Echtzeitberichte

Die im Security & Compliance Center ( ) verfügbaren Überwachungsfunktionen [https://protection.office.com](https://protection.office.com) umfassen [Echtzeitberichte und Einblicke,](/microsoft-365/security/office-365-security/view-reports-for-atp) mit denen sich Sicherheits- und Complianceadministratoren auf Probleme mit hoher Priorität konzentrieren können, z. B. Sicherheitsangriffe oder erhöhte verdächtige Aktivitäten. Neben der Hervorhebung von Problembereichen umfassen intelligente Berichte und Erkenntnisse Empfehlungen und Links zum Anzeigen und Erkunden von Daten sowie schnelle Maßnahmen.

### <a name="explorer"></a>Explorer

Der Explorer (auch als Sicherheitsrisiken-Explorer bezeichnet) ist ein Echtzeitbericht, der es Ihnen ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Standardmäßig werden in diesem Bericht Daten für die letzten sieben Tage angezeigt. Ansichten können jedoch geändert werden, um Daten für die letzten 30 Tage anzuzeigen.

Explorer enthält Ansichten wie Schadsoftware (für E-Mails und Inhalte), Übermittlungen, Phishing und alle E-Mails. Um zu sehen, wie Explorer mit Echtzeiterkennungen vergleicht, [laden Sie diese PDF herunter.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Weitere Informationen zu Explorer (in Microsoft Defender für Office 365 Plan 2) und Echtzeiterkennungen (in Microsoft Defender für Office 365 Plan 1) finden Sie unter [Bedrohungs-Explorer und Echtzeiterkennungen.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Echtzeiterkennungen

Bei Echtzeiterkennungen handelt es sich um einen Echtzeitbericht, der es autorisierten Benutzern ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Ähnlich wie im Explorer werden in diesem Bericht standardmäßig Daten für die letzten sieben Tage angezeigt.

Echtzeiterkennungen enthalten Ansichten wie Schadsoftware (für E-Mails und Inhalte), Übermittlungen und Phishing. Um zu sehen, wie Echtzeiterkennungen mit Explorer verglichen werden, [laden Sie diese PDF herunter.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Weitere Informationen zu Explorer (in Microsoft Defender für Office 365 Plan 2) und Echtzeiterkennungen (in Microsoft Defender für Office 365 Plan 1) finden Sie unter [Bedrohungs-Explorer (und Echtzeiterkennungen).](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Nachverfolgungslisten für Bedrohungen

[Bedrohungsverfolgungen](/microsoft-365/security/office-365-security/threat-trackers) sind informative Widgets und Ansichten, die autorisierten Benutzern Informationen zu Internetsicherheitsproblemen bieten, die sich auf Ihre Organisation auswirken können.

### <a name="automated-incident-response"></a>Automatisierte Reaktion auf Vorfälle

Mit den in Defender für Office 365 Plan 2 verfügbaren Air-Funktionen [(Automated Incident Response)](/microsoft-365/security/office-365-security/office-365-air) können Sie automatisierte Untersuchungsprozesse als Reaktion auf bekannte Bedrohungen ausführen, die heute vorhanden sind. Durch die Automatisierung bestimmter Untersuchungsaufgaben kann Ihr Sicherheitsteam effizienter und effektiver arbeiten. Korrekturmaßnahmen, z. B. das Löschen bösartiger E-Mail-Nachrichten, werden nach genehmigung durch Ihr Sicherheitsteam ausgeführt. Weitere Informationen finden Sie unter [Funktionsweise von AIR in Office 365](/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulation-training"></a>Angriffssimulationstraining

[Angriffssimulationsschulungen](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) sind ein intelligentes Tool für das Soziale Risikomanagement, das die Erstellung und Verwaltung von Phishingsimulationen automatisiert. Mithilfe von Simulationen können Kunden Phishing-Risiken erkennen, priorisieren und beheben, indem phish-Locken aus der Praxis und hyperorientierte Schulungen verwendet werden, um das Verhalten der Mitarbeiter zu ändern.

- Angriffssimulationsschulungen sind jetzt in WW und GCC verfügbar (werden ab dem 21. Juni in GCC).
- Weitere Informationen zu den ersten Schritten finden Sie unter ["Erste Schritte mit der Angriffssimulationsschulung".](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Es stehen verschiedene Angriffstechniken zur Verfügung, die nicht-verwaffnete, reale Phish-Nutzlasten anwenden, die das Verhalten von Angreifern in der realen Welt replizieren, um Phishingsimulationen relevant zu machen.
- Dieser Dienst steht Organisationen zur Verfügung, die über Microsoft 365 E5- Office 365 E5- oder [Microsoft Defender for Office 365 Plan 2-Lizenzen](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) verfügen. E3-Kunden wird eine Teilmenge der Funktionen als Testversion angeboten.
- Weitere Informationen und das Testen einer Simulation finden Sie unter [Simulieren eines Phishingangriffs.](/microsoft-365/security/office-365-security/attack-simulation-training)