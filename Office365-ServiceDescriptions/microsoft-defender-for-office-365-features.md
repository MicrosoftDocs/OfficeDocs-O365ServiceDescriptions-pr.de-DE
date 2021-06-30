---
title: Dienstbeschreibung für Microsoft Defender für Office 365 Features
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
ms.assetid: ''
description: Erfahren Sie mehr über die in Microsoft Defender für Office 365 verfügbaren Features.
ms.openlocfilehash: 620639a2c40d589123ebda33446411533798d2ec
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204865"
---
# <a name="microsoft-defender-for-office-365-features-service-description"></a>Dienstbeschreibung für Microsoft Defender für Office 365 Features

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Neuigkeiten in Microsoft Defender für Office 365

Wir werden Defender weiterhin neue Features für Office 365 hinzufügen. Weitere Informationen zu neuen Features, die für Office 365 (oder Microsoft 365 im Allgemeinen) in Defender verfügbar sind, finden Sie in den folgenden Ressourcen:

- [Microsoft 365-Roadmap](https://www.microsoft.com/microsoft-365/roadmap)

- [Neuigkeiten in Microsoft Defender für Office 365 – Office 365 | Microsoft-Dokumente](/microsoft-365/security/office-365-security/whats-new-in-defender-for-office-365)

## <a name="defender-for-office-365-capabilities"></a>Defender for Office 365-Funktionen

### <a name="safe-attachments"></a>Sichere Anlagen

[Tresor Attachments](/microsoft-365/security/office-365-security/atp-safe-attachments) schützt vor unbekannter Schadsoftware und Viren und bietet Zero-Day-Schutz, um Ihr Messagingsystem zu schützen. Alle Nachrichten und Anlagen, die nicht über eine bekannte Viren-/Schadsoftwaresignatur verfügen, werden an eine spezielle Umgebung weitergeleitet, in der Defender für Office 365 eine Vielzahl von maschinellen Lern- und Analysetechniken verwendet, um böswillige Absichten zu erkennen. Wenn keine verdächtige Aktivität ermittelt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben.

> [!NOTE]
> Tresor Die Anlagenüberprüfung erfolgt in derselben Region, in der sich Ihre Office 365-Daten befinden. Weitere Informationen zur Geografie des Rechenzentrums finden Sie unter [Wo befinden sich Ihre Daten?](/microsoft-365/enterprise/o365-data-locations).

### <a name="safe-links"></a>Sichere Links

Das [Feature Tresor Links](/microsoft-365/security/office-365-security/atp-safe-links) schützt Ihre Benutzer proaktiv vor bösartigen URLs in einer Nachricht oder in einem Office Dokument. Der Schutz verbleibt, wenn sie auf den Link klicken, da böswillige Links dynamisch blockiert werden, während der Zugriff auf unbedenkliche Links gewährt wird.

Für URLs in den folgenden Apps steht „Sichere Links“ zur Verfügung:

- Microsoft 365 Apps for Enterprise auf Windows oder Mac

- Office für das Web (Word für das Web, Excel für das Web, PowerPoint für das Web und OneNote für das Web)

- Word, Excel und PowerPoint auf Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Office 365 für Defender lizenziert <sup>\*</sup> sein, in Tresor Links-Richtlinien enthalten sein und auf ihren Geräten angemeldet sein, damit der Schutz aktiviert ist.
>
> <sup>\*</sup>Bei organisationsweiten Defender für Office 365-Lizenzen (z. B. ATP_ENTERPRISE_FACULTY) müssen Sie Defender für Office 365 Lizenzen nicht einzelnen Benutzern zuweisen.
>
> Weitere Informationen zum Schutz von Tresor Links finden Sie unter [Tresor Links in Microsoft Defender für Office 365.](/microsoft-365/security/office-365-security/atp-safe-links)

### <a name="safe-documents"></a>Sichere Dokumente

Das [Feature Tresor Dokumente](/microsoft-365/security/office-365-security/safe-docs) verwendet Microsoft Defender für [Endpunkt](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) zum Scannen von Dokumenten und Dateien, die in [der geschützten Ansicht](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)geöffnet sind.

Was sollten Sie wissen, bevor Sie beginnen?

- Tresor Dokumente sind jetzt allgemein für Benutzer mit Office Version 2004 (12730.x) oder höher verfügbar! Dieses Feature ist standardmäßig deaktiviert und muss vom Sicherheitsadministrator aktiviert werden.

- Dieses Feature ist nur für Benutzer mit der Microsoft 365 E5 oder Microsoft 365 E5 Security-Lizenz verfügbar (nicht in Defender für Office 365-Plänen enthalten).

- Word, Excel und PowerPoint auf Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Microsoft 365 E5 oder Microsoft 365 E5 Security lizenziert <sup>\*</sup> sein, in Tresor Dokumentrichtlinien eingeschlossen sein und auf ihren Geräten angemeldet sein, damit der Schutz aktiviert ist.
>
> Weitere Informationen zum Schutz von Tresor Dokumenten finden Sie unter [Tresor Dokumente in Microsoft 365 E5](/microsoft-365/security/office-365-security/safe-docs).

### <a name="protection-for-sharepoint-onedrive-and-microsoft-teams"></a>Schutz für SharePoint, OneDrive und Microsoft Teams

[Der Schutz für SharePoint, OneDrive und Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) hilft beim Erkennen und Blockieren von Dateien, die in Teamwebsites und Dokumentbibliotheken als bösartig erkannt werden. Darüber hinaus ist Tresor Linksschutz jetzt in Microsoft Teams Kanälen und Chats verfügbar.

### <a name="anti-phishing-policies"></a>Antiphishing-Richtlinien

[Antiphishing](/microsoft-365/security/office-365-security/atp-anti-phishing) überprüft eingehende Nachrichten auf Indikatoren, dass es sich bei einer Nachricht um einen Phishingversuch handeln könnte. Wenn Benutzer von Defender für Office 365 Richtlinien abgedeckt werden (Tresor Anlagen, Tresor Links oder Antiphishing), werden eingehende Nachrichten von mehreren Machine Learning-Modellen ausgewertet, die Nachrichten analysieren, und die entsprechende Aktion wird basierend auf den konfigurierten Richtlinien ausgeführt.

### <a name="real-time-reports"></a>Echtzeitberichte

Die im [Security & Compliance Center](https://protection.office.com) verfügbaren Überwachungsfunktionen umfassen [Echtzeitberichte und Einblicke,](/microsoft-365/security/office-365-security/view-reports-for-atp) mit denen sich Ihre Sicherheits- und Complianceadministratoren auf Probleme mit hoher Priorität konzentrieren können, z. B. Sicherheitsangriffe oder erhöhte verdächtige Aktivitäten. Neben der Hervorhebung von Problembereichen umfassen intelligente Berichte und Erkenntnisse Empfehlungen und Links zum Anzeigen und Erkunden von Daten sowie schnelle Maßnahmen.

### <a name="threat-explorer"></a>Sicherheitsrisiken-Explorer

Der Bedrohungs-Explorer (auch als Explorer bezeichnet) ist ein Echtzeitbericht, mit dem autorisierte Benutzer aktuelle Bedrohungen identifizieren und analysieren können. Standardmäßig werden in diesem Bericht Daten für die letzten sieben Tage angezeigt. Ansichten können jedoch geändert werden, um Daten für die letzten 30 Tage anzuzeigen.

Explorer enthält Ansichten wie Schadsoftware (für E-Mails und Inhalte), Übermittlungen, Phishing und alle E-Mails. Um zu sehen, wie Explorer mit Echtzeiterkennungen vergleicht, [laden Sie diese PDF herunter.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Weitere Informationen zu Explorer (in Microsoft Defender für Office 365 Plan 2) und Echtzeiterkennungen (in Microsoft Defender für Office 365 Plan 1) finden Sie unter [Bedrohungs-Explorer und Echtzeiterkennungen.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="real-time-detections"></a>Echtzeiterkennungen

Bei Echtzeiterkennungen handelt es sich um einen Echtzeitbericht, der es autorisierten Benutzern ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Ähnlich wie im Explorer werden in diesem Bericht standardmäßig Daten für die letzten sieben Tage angezeigt.

Echtzeiterkennungen enthalten Ansichten wie Schadsoftware (für E-Mails und Inhalte), Übermittlungen und Phishing. Um zu sehen, wie Echtzeiterkennungen mit Explorer verglichen werden, [laden Sie diese PDF herunter.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Weitere Informationen zu Explorer (in Microsoft Defender für Office 365 Plan 2) und Echtzeiterkennungen (in Microsoft Defender für Office 365 Plan 1) finden Sie unter [Bedrohungs-Explorer und Echtzeiterkennungen.](/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Nachverfolgungslisten für Bedrohungen

[Bedrohungsverfolgungen](/microsoft-365/security/office-365-security/threat-trackers) sind informative Widgets und Ansichten, die autorisierten Benutzern Informationen zu Internetsicherheitsproblemen bieten, die sich auf Ihre Organisation auswirken können.

### <a name="automated-investigation--response"></a>Automatisierte Untersuchung & Antwort

Mit den in Defender für Office 365 Plan 2 verfügbaren Air-Funktionen [(Automated Investigation & Response)](/microsoft-365/security/office-365-security/office-365-air) können Sie automatisierte Untersuchungsprozesse als Reaktion auf bekannte Bedrohungen ausführen, die heute vorhanden sind. Durch die Automatisierung bestimmter Untersuchungsaufgaben kann Ihr Sicherheitsteam effizienter und effektiver arbeiten. Korrekturmaßnahmen, z. B. das Löschen bösartiger E-Mail-Nachrichten, werden nach genehmigung durch Ihr Sicherheitsteam ausgeführt. Weitere Informationen finden Sie unter [Funktionsweise von AIR in Office 365.](/microsoft-365/security/office-365-security/automated-investigation-response-office)

### <a name="attack-simulation-training"></a>Angriffssimulationstraining

[Angriffssimulationsschulungen](/microsoft-365/security/office-365-security/attack-simulation-training-get-started) sind ein intelligentes Tool für das Soziale Risikomanagement, das die Erstellung und Verwaltung von Phishingsimulationen automatisiert. Mithilfe von Simulationen können Kunden Phishing-Risiken erkennen, priorisieren und beheben, indem phish-Locken aus der Praxis und hyperorientierte Schulungen verwendet werden, um das Verhalten der Mitarbeiter zu ändern.

- Angriffssimulationsschulungen sind jetzt in WW und GCC verfügbar (werden ab dem 21. Juni in GCC).
- Weitere Informationen zu den ersten Schritten finden Sie unter ["Erste Schritte mit der Angriffssimulationsschulung".](/microsoft-365/security/office-365-security/attack-simulation-training-get-started)
- Es stehen verschiedene Angriffstechniken zur Verfügung, die nicht-verwaffnete, reale Phish-Nutzlasten anwenden, die das Verhalten von Angreifern in der realen Welt replizieren, um Phishingsimulationen relevant zu machen.
- Dieser Dienst steht Organisationen zur Verfügung, die über Microsoft 365 E5- Office 365 E5 oder [Microsoft Defender für Office 365 Plan 2-Lizenzen](/microsoft-365/security/office-365-security/defender-for-office-365#microsoft-defender-for-office-365-plan-1-and-plan-2) verfügen. E3-Kunden wird eine Teilmenge der Funktionen als Testversion angeboten.
- Weitere Informationen und das Testen einer Simulation finden Sie unter [Simulieren eines Phishingangriffs.](/microsoft-365/security/office-365-security/attack-simulation-training)