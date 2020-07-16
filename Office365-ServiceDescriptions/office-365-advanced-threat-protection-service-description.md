---
title: Office 365 Advanced Threat Protection-Dienstbeschreibung
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
description: Microsoft Office 365 Advanced Threat Protection (ATP) ist ein Cloud-basierter e-Mail-Filterdienst, der Ihre Organisation vor unbekannten Schadsoftware und Viren schützt, indem Sie einen robusten Zero-Day-Schutz bietet und Funktionen zum Schutz Ihrer Organisation vor schädlichen Links in Echtzeit enthält.
ms.openlocfilehash: 53e80f635485594f95c62dfa5452ef5352b5a4d7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132369"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection-Dienstbeschreibung

Microsoft Office 365 Advanced Threat Protection (ATP) ist ein Cloud-basierter e-Mail-Filterdienst, der Ihre Organisation vor unbekannten Schadsoftware und Viren schützt, indem Sie einen robusten Zero-Day-Schutz bietet und Funktionen zum Schutz Ihrer Organisation vor schädlichen Links in Echtzeit enthält. ATP verfügt über umfangreiche Berichte und URL-Ablaufverfolgungsfunktionen, mit denen Administratoren Einblicke in die Art von Angriffen in Ihrer Organisation erhalten.

ATP kann in erster Linie über die folgenden Methoden für den Nachrichtenschutz eingesetzt werden:

- In einem Office 365 Protection-Szenario nur mit Filterung bietet ATP cloudbasierten E-Mail-Schutz für Ihre lokalen Exchange Server-Umgebung und alle anderen lokalen SMTP-E-Mail-Lösungen.

- Office 365 ATP kann für den Schutz von Exchange Online-Postfächern aktiviert werden, die auf der Cloud gehostet sind. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description/exchange-online-service-description.md).

- In einer Hybridbereitstellung kann ATP für den Schutz Ihrer Messaging-Umgebung und für die Steuerung von E-Mail-Routing konfiguriert werden, wenn Sie sowohl über lokale als auch über Cloud-Postfächer mit Exchange Online Protection für die eingehende E-Mail-Filterung verfügen.

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Verfügbarkeit von Office 365 Advanced Threat Protection (ATP)

ATP ist in Office 365 Enterprise E5, Office 365 Education a5 und Microsoft 365 Business Premium enthalten.

Sie können ATP zu den folgenden Exchange-und Microsoft 365-Abonnement Plänen hinzufügen:

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

Informationen dazu, wie Sie Office 365 Advanced Threat Protection erwerben können, finden Sie unter [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Informationen zum Vergleich der Features in den Plänen finden Sie unter [leistungsstarke Tools zur Unterstützung Ihres Unternehmens](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) und [umwandeln Ihres Unternehmens mit Microsoft 365](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Neues in Office 365 Advanced Threat Protection (ATP)

Office 365 ATP werden weiterhin neue Features hinzugefügt. Weitere Informationen zu neuen Features in Bezug auf ATP (oder Microsoft 365 im allgemeinen) finden Sie in den folgenden Ressourcen:

- [Microsoft 365-Roadmap](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Neuerungen in Office 365 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Anforderungen für Office 365 Advanced Threat Protection (ATP)

ATP kann mit einem beliebigen SMTP-e-Mail-Übertragungs-Agent verwendet werden, beispielsweise Exchange Server. Informationen zu Betriebssystemen, Webbrowsern und Sprachen, die von ATP unterstützt werden, finden Sie in den Abschnitten "unterstützte Browser" und "Unterstützte Sprachen" im [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Verfügbarkeit von Features in ATP-Plänen (Advanced Threat Protection)

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.

|**Feature**|**ATP-Plan 1**<br>(ehemals ATP Standalone)|**ATP-Plan 2**<br>(ehemals Threat Intelligence <br>Standalone| Office 365 Enterprise E5|
|:-----|:-----|:-----|:-----|
|*Konfiguration, Schutz und Erkennung*|
|[Sichere Anlagen](#safe-attachments)|Ja|Ja|Ja|
|Sichere Anlagen in Microsoft Teams|Ja|Ja|Ja|
|[Sichere Links](#safe-links)|Ja|Ja|Ja|
|Sichere Links in Teams|Ja|Ja|Ja|
|[ATP für SharePoint, OneDrive und Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Ja|Ja|Ja|
|[Antiphishing-Richtlinien](#anti-phishing-policies)|Ja|Ja|Ja|
|[Echtzeitberichte](#real-time-reports)|Ja|Ja|Ja|
|*Automatisierung, Untersuchung, Korrektur und Schulung*|
|[Bedrohungs-Tracker](#threat-trackers)|Nein|Ja|Ja|
|Untersuchung von Bedrohungen (Erweiterte Bedrohungs Ermittlung)|[Echtzeiterkennungen](#real-time-detections)|[Explorer](#explorer)|[Explorer](#explorer)|
|[Automatische Vorfall Antwort](#automated-incident-response)|Nein|Ja|Ja|
|[Angriffssimulator](#attack-simulator)|Nein|Ja|Ja|

> [!TIP]
> Möchten Sie eine herunterladbare Liste der Unterschiede zwischen Office 365 ATP-Plan 1 und Plan 2? [Rufen Sie die PDF-Datei](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf)ab. 

## <a name="advanced-threat-protection-atp-capabilities"></a>Funktionen von Advanced Threat Protection (ATP)

### <a name="safe-attachments"></a>Sichere Anlagen

[ATP-sichere Anhänge](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) schützen vor unbekannten Schadsoftware und Viren und bieten einen Zero-Day-Schutz zum Schutz Ihres Messagingsystems. Alle Nachrichten und Anlagen ohne eine bekannte Signatur für Viren/böswillige Software werden an eine spezielle Umgebung umgeleitet, in der ATP eine Vielzahl von Machine Learning- und Analysetechniken verwendet, um Missbrauchsabsichten zu ermitteln. Wenn keine verdächtige Aktivität ermittelt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben.

> [!NOTE]
> Das Scannen durch das Feature "ATP-sichere Anlagen" erfolgt in der gleichen Region, in der sich Ihre Office 365-Daten befinden. Weitere Informationen zur Geografie des Rechenzentrums finden Sie unter [Wo befinden sich Ihre Daten?](https://products.office.com/where-is-your-data-located?geo=All).

### <a name="safe-links"></a>Sichere Links

Das Feature " [ATP-sichere Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) " schützt Ihre Benutzer proaktiv vor bösartigen URLs in einer Nachricht oder in einem Office-Dokument. Der Schutz verbleibt, wenn sie auf den Link klicken, da böswillige Links dynamisch blockiert werden, während der Zugriff auf unbedenkliche Links gewährt wird.

Sichere links stehen für URLs in den folgenden Apps zur Verfügung:

- Microsoft 365-Apps für Unternehmen unter Windows oder Mac

- Office für das Internet (Word für das Internet, Excel für das Internet, PowerPoint für das Internet und OneNote für das Internet)

- Word, Excel, PowerPoint und Visio unter Windows, sowie Office-Apps auf IOS-und Android-Geräten

- Microsoft Teams-Kanäle und -Chats.

> [!NOTE]
> Benutzer müssen für ATP lizenziert sein <sup>\*</sup> , müssen in Richtlinien für ATP-sichere Links enthalten sein und müssen auf Ihren Geräten angemeldet sein, damit der Schutz in Kraft ist.
>
> <sup>\*</sup>Für organisationsweite ATP-Lizenzen (beispielsweise ATP_ENTERPRISE_FACULTY) müssen Sie keinen einzelnen Benutzern ATP-Lizenzen zuweisen.
>
> Weitere Informationen zum Schutz von ATP-sicheren Links finden Sie unter [Funktionsweise von ATP-sicheren Links mit URLs in Office-Dokumenten](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP für SharePoint, OneDrive und Microsoft Teams

[ATP für SharePoint, OneDrive und Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) unterstützt das erkennen und Blockieren von Dateien, die als bösartig identifiziert werden, in Teamwebsites und Dokumentbibliotheken. Darüber hinaus ist der Schutz für ATP-sichere Links jetzt in Microsoft Teams-Kanälen und-Chats verfügbar.

### <a name="anti-phishing-policies"></a>Antiphishing-Richtlinien

[ATP-Anti-Phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) prüft eingehende Nachrichten auf Indikatoren, bei denen es sich möglicherweise um einen Phishing-Versuch handelt. Wenn Benutzer durch ATP-Richtlinien abgedeckt werden (sichere Anlagen, sichere Links oder Antiphishing), werden eingehende Nachrichten von mehreren Learning-Modellen analysiert und ausgewertet. Daraufhin wird eine entsprechende Aktion auf Grundlage der konfigurierten Richtlinien ausgeführt.

### <a name="real-time-reports"></a>Echtzeitberichte

Zu den im Security & Compliance Center verfügbaren Überwachungsfunktionen gehören [Echtzeitberichte und Einblicke](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) , mit denen sich Ihre Sicherheits-und Compliance-Administratoren auf Probleme mit hoher Priorität konzentrieren können, beispielsweise Sicherheitsangriffe oder erhöhte verdächtige Aktivitäten. Neben der Hervorhebung von Problembereichen enthalten Smart Reports und Einblicke auch Empfehlungen und Links zum Anzeigen und Durchsuchen von Daten sowie zum Ausführen von schnell Aktionen.

### <a name="explorer"></a>Explorer

Der Explorer (auch als Sicherheitsrisiken-Explorer bezeichnet) ist ein Echtzeitbericht, der es Ihnen ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Standardmäßig werden in diesem Bericht Daten der letzten 7 Tage angezeigt. Allerdings kann die Ansicht so geändert werden, dass Daten für die letzten 30 Tage angezeigt werden.

Der Explorer enthält Ansichten wie Schadsoftware (für e-Mails und Inhalte), Übermittlungen, Phishing und alle e-Mails. Um zu sehen, wie Explorer mit Echt Zeit Erkennungen vergleicht, [Laden Sie dieses PDF-Dokument herunter](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Weitere Informationen zum Explorer (in Office 365 Advanced Threat Protection Plan 2) und zur Echtzeiterkennung (in Office 365 Advanced Threat Protection Plan 1) finden Sie unter [Threat Explorer und Real-Time Detections](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="real-time-detections"></a>Echtzeiterkennungen

Bei Echtzeiterkennungen handelt es sich um einen Echtzeitbericht, der es autorisierten Benutzern ermöglicht, aktuelle Bedrohungen zu erkennen und zu analysieren. Ähnlich wie beim Explorer werden in diesem Bericht standardmäßig die Daten für die letzten 7 Tage angezeigt.

Echt Zeit Erkennungen enthalten Ansichten wie Schadsoftware (für e-Mails und Inhalte), Übermittlungen und Phishing. Um zu sehen, wie echt Zeit Erkennungen mit Explorer verglichen werden, [Laden Sie diese PDF herunter](https://github.com/MicrosoftDocs/microsoft-365-docs/raw/public/microsoft-365/downloads/office-365-atp-plan-comparison-march-2020.pdf).

Weitere Informationen zum Explorer (in Office 365 Advanced Threat Protection Plan 2) und zur Echtzeiterkennung (in Office 365 Advanced Threat Protection Plan 1) finden Sie unter [Threat Explorer (und Real-Time Detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="threat-trackers"></a>Nachverfolgungslisten für Bedrohungen

[Threat Tracker](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) sind informative Widgets und Ansichten, die autorisierten Benutzern Informationen zu Cyber-Problemen bereitstellen, die sich möglicherweise auf Ihre Organisation auswirken.

### <a name="automated-incident-response"></a>Automatische Vorfall Antwort

Mit den in Office 365 ATP Plan 2 verfügbaren Funktionen für die [Automatische Vorfall Reaktion](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) können Sie automatisierte Ermittlungsprozesse als Reaktion auf bekannte Bedrohungen ausführen, die heute vorhanden sind. Durch das Automatisieren bestimmter Ermittlungsaufgaben kann Ihr Sicherheits Betriebsteam effizienter und effektiver arbeiten. Korrekturaktionen, wie das Löschen von böswilligen e-Mail-Nachrichten, werden von Ihrem Sicherheits Betriebsteam zur Genehmigung ausgeführt. Weitere Informationen finden Sie unter [Funktionsweise von Air in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Angriffssimulator

Mit dem [Angriffs Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) können autorisierte Benutzer realistische Angriffsszenarien in Ihrer Organisation ausführen. Es stehen verschiedene Arten von Angriffen zur Verfügung, einschließlich eines Anzeigenamens Spear-Phishing-Angriffs, eines Kenn Wort Sprüh Angriffs und eines Brute-Force-Kenn Wort Angriffs.
