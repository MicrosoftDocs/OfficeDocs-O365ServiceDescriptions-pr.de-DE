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
description: Microsoft Defender für Office 365 ist ein cloudbasierter E-Mail-Filterdienst, der Ihre Organisation vor unbekannter Schadsoftware und Viren schützt, indem sie einen robusten Zero-Day-Schutz bietet und Features zum Schutz Ihrer Organisation vor schädlichen Links in Echtzeit enthält.
ms.openlocfilehash: 6116ffdce71686575258c19c7d70159bcefa2134
ms.sourcegitcommit: 02dd535b01c4ca7b19b43188ddd1a1f02c01afb5
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2021
ms.locfileid: "50460244"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defender für Office 365-Dienstbeschreibung

Microsoft Defender für Office 365 ist ein cloudbasierter E-Mail-Filterdienst, der Ihre Organisation vor unbekannter Schadsoftware und Viren schützt, indem sie einen robusten Zero-Day-Schutz bietet und Features zum Schutz Ihrer Organisation vor schädlichen Links in Echtzeit enthält. Defender für Office 365 verfügt über umfangreiche Funktionen zur Berichterstellung und URL-Ablaufverfolgung, die Administratoren Einen Einblick in die Art von Angriffen geben, die in Ihrer Organisation passieren.

Im Folgenden finden Sie die wichtigsten Möglichkeiten, Wie Sie Defender for Office 365 für den Nachrichtenschutz verwenden können:

- In einem Nur-Filterszenario von Defender für Office 365 bietet Defender for Office 365 cloudbasierten E-Mail-Schutz für Ihre lokale Exchange Server-Umgebung oder eine andere lokale SMTP-E-Mail-Lösung.

- Defender für Office 365 kann aktiviert werden, um in der Cloud gehostete Exchange Online-Postfächer zu schützen. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description/exchange-online-service-description.md).

- In einer Hybridbereitstellung kann Defender für Office 365 konfiguriert werden, um Ihre Messagingumgebung zu schützen und das E-Mail-Routing zu steuern, wenn Sie über eine Mischung aus lokalen und Cloudpostfächern mit Exchange Online Protection für die eingehende E-Mail-Filterung verfügen.

## <a name="microsoft-defender-for-office-365-availability"></a>Verfügbarkeit von Microsoft Defender für Office 365

Microsoft Defender für Office 365 Plan 2 ist in Office 365 E5, Office 365 A5, Microsoft 365 E5 Security und Microsoft 365 E5 enthalten, wie hier angegeben: [https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp) . Defender für Office 365 Plan 1 ist in Microsoft 365 Business Premium enthalten.

Sie können Defender für Office 365 den folgenden Exchange- und Microsoft 365-Abonnementplänen hinzufügen:

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

Informationen zum Vergleichen von Features in verschiedenen Plänen finden Sie unter [Leistungsstarke](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) Tools zur Unterstützung Ihres Unternehmens und Transformieren Ihres Unternehmens [mit Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-microsoft-defender-for-office-365"></a>Neues in Microsoft Defender für Office 365

Wir fügen defender for Office 365 weiterhin neue Features hinzu. Weitere Informationen zu neuen Features für Defender for Office 365 (oder Microsoft 365 im Allgemeinen) finden Sie in den folgenden Ressourcen:

- [Microsoft 365-Roadmap](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Neues in Microsoft Defender für Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-microsoft-defender-for-office-365"></a>Anforderungen für Microsoft Defender für Office 365

Defender für Office 365 kann mit jedem SMTP-E-Mail-Übertragungs-Agent verwendet werden, z. B. Microsoft Exchange Server. Informationen zu betriebssystemen, Webbrowsern und Sprachen, die von Defender für Office 365 unterstützt werden, finden Sie in den Abschnitten "Unterstützte Browser" und "Unterstützte Sprachen" im [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-defender-for-office-365-plans"></a>Verfügbarkeit von Features in Defender for Office 365-Plänen

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.<br><br>

| Feature | Defender für Office 365 Plan 1 | Defender für Office 365 Plan 2 | Microsoft 365 E5 /A5 Security|
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
|*Automatisierung, Untersuchung, Korrektur und Bildungseinrichtungen*|
|[Bedrohungs-Tracker](#threat-trackers)|Nein|Ja|Ja|
|Bedrohungsuntersuchung (erweiterte Bedrohungsuntersuchung)|[Echtzeiterkennungen](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Automatisierte Reaktion auf Vorfälle](#automated-incident-response)|Nein|Ja|Ja|
|[Angriffssimulator](#attack-simulator)|Nein|Ja|Ja|
|*Integration in [Microsoft 365 Defender](https://docs.microsoft.com/microsoft-365/security/mtp/microsoft-threat-protection)*|Nein|Ja|Ja|

> [!NOTE]
> Wenn Ihr Mandant nur über eine Microsoft Defender for Office Plan P2-Testlizenz oder eine Office 365 E5-Testlizenz verfügt, ohne eine andere berechtigte Lizenz für Microsoft 365 Defender, können Sie nicht auf Microsoft 365 Defender zugreifen. Weitere Informationen zur MTP-Lizenz finden Sie unter [Microsoft 365 Defender Requirements](https://docs.microsoft.com/microsoft-365/security/mtp/prerequisites).

## <a name="defender-for-office-365-capabilities"></a>Defender für Office 365-Funktionen

### <a name="safe-attachments"></a>Sichere Anlagen

[Sichere Anlagen](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) schützen vor unbekannter Schadsoftware und Viren und bieten Zero-Day-Schutz zum Schutz Ihres Messagingsystems. Alle Nachrichten und Anlagen, die keine bekannte Viren-/Schadsoftwaresignatur haben, werden an eine spezielle Umgebung geroutet, in der Defender for Office 365 eine Vielzahl von Maschinellem Lernen und Analysetechniken verwendet, um böswillige Absichten zu erkennen. Wenn keine verdächtige Aktivität ermittelt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben.

> [!NOTE]
> Die Überprüfung sicherer Anlagen erfolgt in derselben Region, in der sich Ihre Office 365-Daten befinden. Weitere Informationen zur Geografie des Rechenzentrums finden Sie unter [Wo befinden sich Ihre Daten?](https://products.office.com/where-is-your-data-located?geo=All).

### <a name="safe-links"></a>Sichere Links

Das [Feature "Sichere](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) Links" schützt Ihre Benutzer proaktiv vor bösartigen URLs in einer Nachricht oder in einem Office-Dokument. Der Schutz verbleibt, wenn sie auf den Link klicken, da böswillige Links dynamisch blockiert werden, während der Zugriff auf unbedenkliche Links gewährt wird.

Für URLs in den folgenden Apps steht „Sichere Links“ zur Verfügung:

- Microsoft 365 Apps for Enterprise unter Windows oder Mac

- Office für das Web (Word für das Web, Excel für das Web, PowerPoint für das Web und OneNote für das Web)

- Word, Excel und PowerPoint unter Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Defender für Office 365 lizenziert sein, müssen in Richtlinien für sichere Links enthalten sein und auf ihren Geräten angemeldet sein, damit der Schutz <sup>\*</sup> vorhanden ist.
>
> <sup>\*</sup> Für organisationsweite Defender for Office 365-Lizenzen (z. B. ATP_ENTERPRISE_FACULTY) müssen Sie einzelnen Benutzern keine Defender for Office 365-Lizenzen zuweisen.
>
> Weitere Informationen zum Schutz sicherer Links finden Sie unter [Safe Links in Microsoft Defender for Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links).

### <a name="safe-documents"></a>Sichere Dokumente

Das [Feature "Sichere Dokumente"](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs) verwendet [Microsoft Defender for Endpoint,](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) um Dokumente und Dateien zu überprüfen, die in der geschützten Ansicht [geöffnet werden.](https://support.microsoft.com/office/what-is-protected-view-d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)

Was sollten Sie wissen, bevor Sie beginnen?

- Sichere Dokumente sind jetzt allgemein für Benutzer mit Office Version 2004 (12730.x) oder höher verfügbar! Dieses Feature ist standardmäßig deaktiviert und muss vom Sicherheitsadministrator aktiviert werden.

- Dieses Feature ist nur für Benutzer mit der Microsoft 365 E5- oder Microsoft 365 E5-Sicherheitslizenz verfügbar (nicht in Defender for Office 365-Plänen enthalten).

- Word, Excel und PowerPoint unter Windows

- Microsoft Teams-Kanäle und -Chats

> [!NOTE]
> Benutzer müssen für Microsoft 365 E5 oder Microsoft 365 E5 Security lizenziert sein, müssen in Richtlinien für sichere Dokumente enthalten sein und auf ihren Geräten angemeldet sein, damit der Schutz vorhanden <sup>\*</sup> ist.
>
> Weitere Informationen zum Schutz sicherer Dokumente finden Sie unter [Safe Documents in Microsoft 365 E5](https://docs.microsoft.com/microsoft-365/security/office-365-security/safe-docs).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP für SharePoint, OneDrive und Microsoft Teams

[ATP für SharePoint, OneDrive](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)  und Microsoft Teams hilft beim Erkennen und Blockieren von Dateien, die in Teamwebsites und Dokumentbibliotheken als schädlich identifiziert werden. Darüber hinaus ist der Schutz sicherer Links jetzt in Microsoft Teams-Kanälen und -Chats verfügbar.

### <a name="anti-phishing-policies"></a>Antiphishing-Richtlinien

[Antiphishing überprüft](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) eingehende Nachrichten auf Indikatoren, dass es sich bei einer Nachricht um einen Phishingversuch handelt. Wenn Benutzer von Defender for Office 365-Richtlinien abgedeckt werden (sichere Anlagen, sichere Links oder Antiphishing), werden eingehende Nachrichten von mehreren Machine Learning-Modellen ausgewertet, die Nachrichten analysieren, und die entsprechenden Maßnahmen werden basierend auf den konfigurierten Richtlinien ergriffen.

### <a name="real-time-reports"></a>Echtzeitberichte

Die im Security & Compliance Center ( ) verfügbaren Überwachungsfunktionen umfassen Echtzeitberichte und Einblicke, mit deren Rahmen sich Ihre Sicherheits- und Complianceadministratoren auf Probleme mit hoher Priorität konzentrieren können, z. B. Sicherheitsangriffe oder erhöhte verdächtige [https://protection.office.com](https://protection.office.com) Aktivitäten. [](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) Neben der Hervorhebung von Problembereichen enthalten intelligente Berichte und Einblicke Empfehlungen und Links zum Anzeigen und Erkunden von Daten sowie schnelle Aktionen.

### <a name="explorer"></a>Explorer

Der Explorer (auch als Sicherheitsrisiken-Explorer bezeichnet) ist ein Echtzeitbericht, der es Ihnen ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Standardmäßig werden in diesem Bericht Daten für die letzten sieben Tage angezeigt. Ansichten können jedoch geändert werden, um Daten für die letzten 30 Tage anzeigen zu können.

Explorer enthält Ansichten, z. B. Schadsoftware (für E-Mails und Inhalte), Übermittlungen, Phish und Alle E-Mails. Laden Sie diese PDF herunter, um zu sehen, wie Explorer mit [Echtzeiterkennungen vergleicht.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Weitere Informationen zu Explorer (in Microsoft Defender für Office 365 Plan 2) und Echtzeiterkennungen (in Microsoft Defender für Office 365 Plan 1) finden Sie unter [Threat Explorer und](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)Echtzeiterkennungen .

### <a name="real-time-detections"></a>Echtzeiterkennungen

Bei Echtzeiterkennungen handelt es sich um einen Echtzeitbericht, der es autorisierten Benutzern ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Ähnlich wie Explorer zeigt dieser Bericht standardmäßig Daten für die letzten sieben Tage an.

Echtzeiterkennungen enthalten Ansichten, z. B. Schadsoftware (für E-Mails und Inhalte), Übermittlungen und Phish. Laden Sie diese PDF herunter, um zu sehen, wie Echtzeiterkennungen mit Explorer [verglichen werden.](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)

Weitere Informationen zu Explorer (in Microsoft Defender für Office 365 Plan 2) und Echtzeiterkennungen (in Microsoft Defender für Office 365 Plan 1) finden Sie unter [Threat Explorer (und Echtzeiterkennungen).](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer)

### <a name="threat-trackers"></a>Nachverfolgungslisten für Bedrohungen

[Threat Trackers sind](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) informative Widgets und Ansichten, die autorisierten Benutzern Informationen zu Cybersicherheitsproblemen bieten, die sich auf Ihre Organisation auswirken können.

### <a name="automated-incident-response"></a>Automatisierte Reaktion auf Vorfälle

Mit den in Defender for Office 365 Plan 2 verfügbaren Funktionen für die automatische Reaktion auf Vorfälle (Automated [Incident Response,](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) AIR) können Sie automatisierte Untersuchungsprozesse als Reaktion auf bekannte Bedrohungen ausführen, die heute vorhanden sind. Durch automatisierte bestimmte Untersuchungsaufgaben kann Ihr Sicherheitsteam effizienter und effektiver arbeiten. Abhilfemaßnahmen, z. B. das Löschen schädlicher E-Mail-Nachrichten, werden nach Genehmigung durch Ihr Sicherheitsteam ergriffen. Weitere Informationen finden Sie unter [How AIR works in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Angriffssimulator

[Mit dem](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) Angriffssimulator können autorisierte Benutzer realistische Angriffsszenarien in Ihrer Organisation ausführen. Es stehen verschiedene Arten von Angriffen zur Verfügung, darunter ein Speerphishingangriff mit Anzeigenamen, ein Kennwort-Spray-Angriff und ein Brute-Force-Kennwortangriff.
