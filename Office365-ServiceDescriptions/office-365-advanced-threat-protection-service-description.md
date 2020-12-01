---
title: Microsoft Defender für Office 365-Dienstbeschreibung
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Defender für Office 365 ist ein Cloud-basierter e-Mail-Filterdienst, der Ihre Organisation vor unbekannten Schadsoftware und Viren schützt, indem Sie einen robusten Zero-Day-Schutz bieten und Funktionen zum Schutz Ihrer Organisation vor schädlichen Links in Echtzeit bietet.
ms.openlocfilehash: 1d99b59e089ecb351d436c49a4f4e3986aefa6cd
ms.sourcegitcommit: 0752cc6c082737a19c7dca24c8f3b555ea871f4f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 12/01/2020
ms.locfileid: "49519026"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defender für Office 365-Dienstbeschreibung

Microsoft Defender für Office 365 ist ein Cloud-basierter e-Mail-Filterdienst, der Ihre Organisation vor unbekannten Schadsoftware und Viren schützt, indem Sie einen robusten Zero-Day-Schutz bieten und Funktionen zum Schutz Ihrer Organisation vor schädlichen Links in Echtzeit bietet. Defender für Office 365 verfügt über umfangreiche Berichte und URL-Ablaufverfolgungsfunktionen, mit denen Administratoren Einblicke in die Art von Angriffen in Ihrer Organisation erhalten.

Im folgenden finden Sie die wichtigsten Methoden zum Verwenden von Defender für Office 365 für den Nachrichtenschutz:

- In einem Verteidiger für Office 365 Szenario mit Filterung bietet Defender für Office 365 cloudbasierten e-Mail-Schutz für Ihre lokale Exchange Server Umgebung oder eine andere lokale SMTP-e-Mail-Lösung.

- Defender für Office 365 kann aktiviert werden, um Exchange Online in der Cloud gehosteten Postfächer zu schützen. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description/exchange-online-service-description.md).

- In einer hybridbereitstellung kann Defender für Office 365 so konfiguriert werden, dass Ihre Messaging-Umgebung geschützt wird und das e-Mail-Routing gesteuert wird, wenn Sie über eine Mischung aus lokalen und Cloud-Postfächern mit Exchange Online Schutz für die eingehende e-Mail-Filterung verfügen.

## <a name="microsoft-defender-for-office-365-availability"></a>Microsoft Defender für Office 365 Verfügbarkeit

Defender for Office 365 Plan 2 ist in Office 365 E5, Office 365 a5 und Microsoft 365 E5 enthalten. Defender for Office 365 Plan 1 ist in Microsoft 365 Business Premium enthalten.

Sie können Defender für Office 365 zu den folgenden Exchange-und Microsoft 365-Abonnement Plänen hinzufügen:

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

Informationen zum Vergleich der Features in den Plänen finden Sie unter [leistungsstarke Tools zur Unterstützung Ihres Unternehmens](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) und [umwandeln Ihres Unternehmens mit Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Neuerungen in Microsoft Defender für Office 365

Wir fügen dem Verteidiger weiterhin neue Features für Office 365 hinzu. Weitere Informationen zu den neuen Features von Defender für Office 365 (oder Microsoft 365 im allgemeinen) finden Sie in den folgenden Ressourcen:

- [Microsoft 365-Roadmap](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Neuerungen in Microsoft Defender für Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Anforderungen für Microsoft Defender für Office 365

Defender für Office 365 kann mit einem beliebigen SMTP-e-Mail-Übertragungs-Agent wie Exchange Server verwendet werden. Informationen zu den Betriebssystemen, Webbrowsern und Sprachen, die von Defender für Office 365 unterstützt werden, finden Sie in den Abschnitten "unterstützte Browser" und "Unterstützte Sprachen" im [Exchange Admin Center unter Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Verfügbarkeit von Features in Defender für Office 365 Pläne

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.<br><br>

| Feature | Verteidiger für Office 365 Plan 1 | Verteidiger für Office 365 Plan 2 | Microsoft 365 E5/E5-Sicherheit|
|:-----|:-----|:-----|:-----|
|*Konfiguration, Schutz und Erkennung*|
|[Sichere Anlagen](#safe-attachments)|Ja|Ja|Ja|
|Sichere Anlagen in Microsoft Teams|Ja|Ja|Ja|
|[Sichere Links](#safe-links)|Ja|Ja|Ja|
|[Sichere Dokumente](#safe-documents)|Nein|Nein|Ja|
|Sichere Links in Teams|Ja|Ja|Ja|
|[ATP für SharePoint, OneDrive und Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Ja|Ja|Ja|
|[Antiphishing-Richtlinien](#anti-phishing-policies)|Ja|Ja|Ja|
|[Echtzeitberichte](#real-time-reports)|Ja|Ja|Ja|
|*Automatisierung, Untersuchung, Korrektur und Schulung*|
|[Bedrohungs-Tracker](#threat-trackers)|Nein|Ja|Ja|
|Untersuchung von Bedrohungen (Erweiterte Bedrohungs Ermittlung)|[Echtzeiterkennungen](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Automatische Vorfall Antwort](#automated-incident-response)|Nein|Ja|Ja|
|[Angriffssimulator](#attack-simulator)|Nein|Ja|Ja|
|*Integration mit Microsoft 365 Defender*|Nein|Nein|Ja|

> [!TIP]
> Möchten Sie eine herunterladbare Liste der Unterschiede zwischen Defender für Office 365 Plan 1 und Plan 2? [Rufen Sie die PDF-Datei](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)ab. 

## <a name="defender-for-office-365-capabilities"></a>Verteidiger für Office 365 Funktionen

### <a name="safe-attachments"></a>Sichere Anlagen

[Sichere Anlagen](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) schützen vor unbekannten Schadsoftware und Viren und bieten einen Zero-Day-Schutz zum Schutz Ihres Messagingsystems. Alle Nachrichten und Anlagen, die nicht über eine bekannte Virus/Malware-Signatur verfügen, werden an eine spezielle Umgebung weitergeleitet, in der Defender for Office 365 eine Vielzahl von Methoden zum Erlernen und Analysieren von Computern verwendet, um böswillige Absicht zu erkennen. Wenn keine verdächtige Aktivität ermittelt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben.

> [!NOTE]
> Die Überprüfung sicherer Anlagen erfolgt in derselben Region, in der sich Ihre Office 365 Daten befinden. Weitere Informationen zur Geografie des Rechenzentrums finden Sie unter [Wo befinden sich Ihre Daten?](https://products.office.com/where-is-your-data-located?geo=All).

### <a name="safe-links"></a>Sichere Links

Das Feature " [sichere Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) " schützt Ihre Benutzer proaktiv vor bösartigen URLs in einer Nachricht oder in einem Office-Dokument. Der Schutz verbleibt, wenn sie auf den Link klicken, da böswillige Links dynamisch blockiert werden, während der Zugriff auf unbedenkliche Links gewährt wird.

Für URLs in den folgenden Apps steht „Sichere Links“ zur Verfügung:

- Microsoft 365-Apps für Unternehmen unter Windows oder Mac

- Office für das Web (Word für das Web, Excel für das Web, PowerPoint für das Web und OneNote für das Web)

- Word, Excel und PowerPoint unter Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Defender für Office 365 lizenziert werden <sup>\*</sup> , müssen in Richtlinien für sichere Links enthalten sein und müssen auf Ihren Geräten angemeldet sein, damit der Schutz in Kraft tritt.
>
> <sup>\*</sup> Für den organisationsweiten Defender für Office 365 Lizenzen (beispielsweise ATP_ENTERPRISE_FACULTY) müssen Sie keinen Verteidiger für Office 365 Lizenzen einzelnen Benutzern zuweisen.
>
> Weitere Informationen zum Schutz von sicheren Links finden Sie unter [sichere Links in Microsoft Defender für Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Sichere Dokumente

Das Feature für [sichere Dokumente](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) verwendet [Microsoft Defender für Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) zum Überprüfen von Dokumenten und Dateien, die in der [geschützten Ansicht](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)geöffnet werden.

Was sollten Sie wissen, bevor Sie beginnen?

- Sichere Dokumente sind nun allgemein für Benutzer mit Office-Version 2004 (12730. x) oder höher verfügbar! Dieses Feature ist standardmäßig deaktiviert und muss vom Sicherheits Administrator aktiviert werden.

- Dieses Feature ist nur für Benutzer mit der Sicherheitslizenz Microsoft 365 E5 oder Microsoft 365 E5 verfügbar (nicht in Defender für Office 365 Pläne enthalten).

- Word, Excel und PowerPoint unter Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Microsoft 365 E5 oder Microsoft 365 E5-Sicherheit lizenziert werden <sup>\*</sup> , müssen in Richtlinien für sichere Dokumente enthalten sein und müssen auf Ihren Geräten angemeldet sein, damit der Schutz in Kraft ist.
>
> Weitere Informationen zum Schutz sicherer Dokumente finden Sie unter [sichere Dokumente in Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP für SharePoint, OneDrive und Microsoft Teams

[ATP für SharePoint, OneDrive und Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  unterstützt das erkennen und Blockieren von Dateien, die als bösartig identifiziert werden, in Teamwebsites und Dokumentbibliotheken. Außerdem steht der Schutz für sichere Links jetzt in Microsoft Teams-Kanälen und-Chats zur Verfügung.

### <a name="anti-phishing-policies"></a>Antiphishing-Richtlinien

[Anti-Phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) prüft eingehende Nachrichten auf Indikatoren, bei denen es sich möglicherweise um einen Phishing-Versuch handelt. Wenn Benutzer von Defender für Office 365-Richtlinien (sichere Anlagen, sichere Links oder Anti-Phishing) abgedeckt werden, werden eingehende Nachrichten von mehreren maschinellen Lernmodellen ausgewertet, die Nachrichten analysieren, und die entsprechende Aktion wird basierend auf den konfigurierten Richtlinien ausgeführt.

### <a name="real-time-reports"></a>Echtzeitberichte

Zu den im Security & Compliance Center verfügbaren Überwachungsfunktionen gehören [Echtzeitberichte und Einblicke](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) , mit denen sich Ihre Sicherheits-und Compliance-Administratoren auf Probleme mit hoher Priorität konzentrieren können, beispielsweise Sicherheitsangriffe oder erhöhte verdächtige Aktivitäten. Neben der Hervorhebung von Problembereichen enthalten Smart Reports und Einblicke auch Empfehlungen und Links zum Anzeigen und Durchsuchen von Daten sowie zum Ausführen von schnell Aktionen.

### <a name="explorer"></a>Explorer

Der Explorer (auch als Sicherheitsrisiken-Explorer bezeichnet) ist ein Echtzeitbericht, der es Ihnen ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Standardmäßig werden in diesem Bericht Daten der letzten 7 Tage angezeigt. Allerdings kann die Ansicht so geändert werden, dass Daten für die letzten 30 Tage angezeigt werden.

Der Explorer enthält Ansichten wie Schadsoftware (für e-Mails und Inhalte), Übermittlungen, Phishing und alle e-Mails. Um zu sehen, wie Explorer mit Echt Zeit Erkennungen vergleicht, [Laden Sie dieses PDF-Dokument herunter](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Weitere Informationen zum Explorer (in Microsoft Defender für Office 365 Plan 2) und zur Echtzeiterkennung (in Microsoft Defender für Office 365 Plan 1) finden Sie unter [Threat Explorer und Real-Time Detections](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Echtzeiterkennungen

Bei Echtzeiterkennungen handelt es sich um einen Echtzeitbericht, der es autorisierten Benutzern ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Ähnlich wie beim Explorer werden in diesem Bericht standardmäßig die Daten für die letzten 7 Tage angezeigt.

Echt Zeit Erkennungen enthalten Ansichten wie Schadsoftware (für e-Mails und Inhalte), Übermittlungen und Phishing. Um zu sehen, wie echt Zeit Erkennungen mit Explorer verglichen werden, [Laden Sie diese PDF herunter](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Weitere Informationen zum Explorer (in Microsoft Defender für Office 365 Plan 2) und zur Echtzeiterkennung (in Microsoft Defender für Office 365 Plan 1) finden Sie unter [Threat Explorer (and Real-Time Detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Nachverfolgungslisten für Bedrohungen

[Threat Tracker](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) sind informative Widgets und Ansichten, die autorisierten Benutzern Informationen zu Cyber-Problemen bereitstellen, die sich möglicherweise auf Ihre Organisation auswirken.

### <a name="automated-incident-response"></a>Automatische Vorfall Antwort

Mit den in Defender verfügbaren Funktionen für die [Automatische Vorfall Antwort](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) (Air) für Office 365 Plan 2 können Sie automatisierte Ermittlungsprozesse als Reaktion auf bekannte Bedrohungen ausführen, die heute vorhanden sind. Durch das Automatisieren bestimmter Ermittlungsaufgaben kann Ihr Sicherheits Betriebsteam effizienter und effektiver arbeiten. Korrekturaktionen, wie das Löschen von böswilligen e-Mail-Nachrichten, werden von Ihrem Sicherheits Betriebsteam zur Genehmigung ausgeführt. Weitere Informationen finden Sie unter [Funktionsweise von Air in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Angriffssimulator

Mit dem [Angriffs Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) können autorisierte Benutzer realistische Angriffsszenarien in Ihrer Organisation ausführen. Es stehen verschiedene Arten von Angriffen zur Verfügung, einschließlich eines Anzeigenamens Spear-Phishing-Angriffs, eines Kenn Wort Sprüh Angriffs und eines Brute-Force-Kenn Wort Angriffs.
