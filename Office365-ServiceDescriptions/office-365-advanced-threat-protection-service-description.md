---
title: Office 365 Advanced Threat Protection-Dienstbeschreibung
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) ist ein Cloud-basierter e-Mail-Filterdienst, der Ihre Organisation vor unbekannten Schadsoftware und Viren schützt, indem Sie einen robusten Zero-Day-Schutz bietet und Funktionen zum Schutz Ihrer Organisation von schädlichen Links in Echtzeit.
ms.openlocfilehash: 5457cbe5304665f7cddc9cc068a167684cf77024
ms.sourcegitcommit: 83c602d9c498df5a2fe0095c6fb0a267c8a708b7
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/12/2020
ms.locfileid: "42609836"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection-Dienstbeschreibung

Microsoft Office 365 Advanced Threat Protection (ATP) ist ein Cloud-basierter e-Mail-Filterdienst, der Ihre Organisation vor unbekannten Schadsoftware und Viren schützt, indem Sie einen robusten Zero-Day-Schutz bietet und Funktionen zum Schutz Ihrer Organisation von schädlichen Links in Echtzeit. ATP verfügt über umfangreiche Berichte und URL-Ablaufverfolgungsfunktionen, mit denen Administratoren Einblicke in die Art von Angriffen in Ihrer Organisation erhalten.

Im folgenden finden Sie die wichtigsten Methoden zum Verwenden von ATP für den Nachrichtenschutz:

- In einem Szenario mit Office 365 reinen ATP-Filterung bietet ATP Cloud-basierten e-Mail-Schutz für Ihre lokale Exchange Server Umgebung oder eine andere lokale SMTP-e-Mail-Lösung.

- Office 365 ATP kann aktiviert werden, um über die Exchange Online-Cloud gehostete Postfächer zu schützen. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description/exchange-online-service-description.md).

- In einer Hybridbereitstellung kann ATP für den Schutz Ihrer Messaging-Umgebung und für die Steuerung von E-Mail-Routing konfiguriert werden, wenn Sie sowohl über lokale als auch über Cloud-Postfächer mit Exchange Online Protection für die eingehende E-Mail-Filterung verfügen.

## <a name="office-365-advanced-threat-protection-atp-availability"></a>Verfügbarkeit von Office 365 Advanced Threat Protection (ATP)

ATP ist in Office 365 Enterprise E5, Office 365 Education a5 und Microsoft 365 Business enthalten.

Sie können ATP zu den folgenden Exchange- und Office 365-Abonnementplänen hinzufügen:

- Exchange Online Plan 1

- Exchange Online Plan 2

- Exchange Online-Kiosk

- Exchange Online Protection

- Office 365 Business Essentials

- Office 365 Business Premium

- Office 365 Enterprise E1

- Office 365 Enterprise E3

- Office 365 Enterprise F3

- Office 365 A1

- Office 365 A3

Informationen dazu, wie Sie Office 365 Advanced Threat Protection erwerben können, finden Sie unter [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).

Informationen zum Vergleichen von Features in den Plänen finden Sie unter [Vergleichen von Office 365 for Business-Plänen](https://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) und [Ermitteln der richtigen Lösung für Microsoft 365 Enterprise](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).

## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Neues in Office 365 Advanced Threat Protection (ATP)

Office 365 ATP werden weiterhin neue Features hinzugefügt. Weitere Informationen zu neuen Features in Bezug auf ATP (oder Microsoft 365 im allgemeinen) finden Sie in den folgenden Ressourcen:

- [Microsoft 365-Roadmap](https://www.microsoft.com/microsoft-365/roadmap?filters=O365)

- [Neuerungen in Office 365 ATP](https://docs.microsoft.com/microsoft-365/security/office-365-security/whats-new-in-office-365-atp)

## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Anforderungen für Office 365 Advanced Threat Protection (ATP)

ATP kann mit einem beliebigen SMTP-e-Mail-Übertragungs-Agent verwendet werden, beispielsweise Exchange Server. Informationen zu von ATP unterstützten Betriebssystemen, Webbrowsern und Sprachen finden Sie in den Abschnitten „Unterstützte Browser" und „Unterstützte Sprachen" unter [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).

## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Verfügbarkeit von Features in ATP-Plänen (Advanced Threat Protection)

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.

|**Feature**|**ATP-Plan 1**<br>(ehemals ATP Standalone)|**ATP-Plan 2**<br>(ehemals Threat Intelligence <br>Standalone| Office 365 Enterprise E5|
|:-----|:-----|:-----|:-----|
|*Konfiguration, Schutz und Erkennung*|
|[Sichere Anlagen](#safe-attachments)|Ja|Ja|Ja|
|Sichere Anlagen in Microsoft Teams|Ja|Ja|Ja|
|[Sichere Links](#safe-links)|Ja|Ja|Ja|
|Sichere Links in Microsoft Teams|Nein|Nein|Nein|
|[ATP für SharePoint, OneDrive und Microsoft Teams](#atp-for-sharepoint-onedrive-and-microsoft-teams)|Ja|Ja|Ja|
|[Anti-Phishing-Richtlinien](#anti-phishing-policies)|Ja|Ja|Ja|
|[Echtzeitberichte](#real-time-reports)|Ja|Ja|Ja|
|*Automatisierung, Untersuchung, Korrektur und Schulung*|
|[Nachverfolgungslisten für Bedrohungen](#threat-trackers)|Nein|Ja|Ja|
|[Explorer](#explorer) (Advanced Threat Investigation)|Nein|Ja|Ja|
|[Automatische Vorfall Antwort](#automated-incident-response)|Nein|Ja|Ja|
|[Angriffssimulator](#attack-simulator)|Nein|Ja|Ja|

## <a name="advanced-threat-protection-atp-capabilities"></a>Funktionen für Advanced Threat Protection (ATP)

### <a name="safe-attachments"></a>Sichere Anlagen

[ATP-sichere Anhänge](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments) schützen vor unbekannten Schadsoftware und Viren und bieten einen Zero-Day-Schutz zum Schutz Ihres Messagingsystems. Alle Nachrichten und Anlagen ohne eine bekannte Signatur für Viren/böswillige Software werden an eine spezielle Umgebung umgeleitet, in der ATP eine Vielzahl von Machine Learning- und Analysetechniken verwendet, um Missbrauchsabsichten zu ermitteln. Wenn keine verdächtige Aktivität ermittelt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben.

> [!NOTE]
> Die Überprüfung der ATP-Tresoranlagen erfolgt in derselben Region, in der sich Ihre Office 365 Daten befinden. Weitere Informationen zur Geografie des Rechenzentrums finden Sie unter [wo befinden sich Ihre Daten?](https://products.office.com/where-is-your-data-located?geo=All)

### <a name="safe-links"></a>Sichere Links

Das Feature " [ATP-sichere Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) " schützt Ihre Benutzer proaktiv vor bösartigen URLs in einer Nachricht oder in einem Office-Dokument. Der Schutz bleibt jedes Mal, wenn Sie den Link auswählen, da böswillige Links dynamisch blockiert werden, während auf gute Links zugegriffen werden kann.

Sichere links stehen für URLs in den folgenden Apps zur Verfügung:

- Office 365 ProPlus unter Windows oder Mac

- Office für das Internet (Word für das Internet, Excel für das Internet, PowerPoint für das Internet und OneNote für das Internet)

- Word, Excel, PowerPoint und Visio unter Windows, sowie Office-Apps auf IOS-und Android-Geräten

> [!NOTE]
> Benutzer müssen für ATP<sup>\*</sup>lizenziert sein, müssen in Richtlinien für ATP-sichere Links enthalten sein und müssen auf Ihren Geräten angemeldet sein, damit der Schutz in Kraft ist.
>
> <sup>\*</sup>Für organisationsweite ATP-Lizenzen (beispielsweise ATP_ENTERPRISE_FACULTY) müssen Sie keinen einzelnen Benutzern ATP-Lizenzen zuweisen.
>
> Weitere Informationen zum Schutz von ATP-sicheren Links finden Sie unter [Funktionsweise von ATP-sicheren Links mit URLs in Office-Dokumenten](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-atp-safe-links-works#how-atp-safe-links-works-with-urls-in-office-documents).

### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP für SharePoint, OneDrive und Microsoft Teams

[ATP für SharePoint, OneDrive und Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams) unterstützt das erkennen und Blockieren von Dateien, die als bösartig identifiziert werden, in Teamwebsites und Dokumentbibliotheken.

### <a name="anti-phishing-policies"></a>Anti-Phishing-Richtlinien

[ATP-Anti-Phishing](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-anti-phishing) prüft eingehende Nachrichten auf Indikatoren, bei denen es sich möglicherweise um einen Phishing-Versuch handelt. Wenn Benutzer durch ATP-Richtlinien (sichere Anlagen, sichere Links oder Anti-Phishing) abgedeckt werden, werden eingehende Nachrichten von mehreren maschinellen Lernmodellen ausgewertet, die Nachrichten analysieren, und die entsprechende Aktion wird basierend auf den konfigurierten Richtlinien ausgeführt.

### <a name="real-time-reports"></a>Echtzeitberichte

Zu den im Office 365 Security & Compliance Center verfügbaren Überwachungsfunktionen gehören [Echtzeitberichte und Einblicke](https://docs.microsoft.com/microsoft-365/security/office-365-security/view-reports-for-atp) , mit denen sich Ihre Sicherheits-und Compliance-Administratoren auf Probleme mit hoher Priorität konzentrieren können, beispielsweise Sicherheitsangriffe oder erhöhte verdächtige Aktivitäten. Neben der Hervorhebung von Problembereichen enthalten Smart Reports und Einblicke auch Empfehlungen und Links zum Anzeigen und Durchsuchen von Daten sowie zum Ausführen von schnell Aktionen.

### <a name="threat-trackers"></a>Nachverfolgungslisten für Bedrohungen

[Threat Tracker](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-trackers) sind informative Widgets und Ansichten, die autorisierten Benutzern Informationen zu Cyber-Problemen bereitstellen, die sich möglicherweise auf Ihre Organisation auswirken.

### <a name="explorer"></a>Explorer

Explorer (auch als Threat Explorer bezeichnet) ist ein Echtzeitbericht, mit dem autorisierte Benutzer die aktuellen Bedrohungen identifizieren und analysieren können. Standardmäßig werden in diesem Berichtdaten für die letzten 7 Tage angezeigt; Ansichten können jedoch geändert werden, um Daten für die letzten 30 Tage anzuzeigen.

Weitere Informationen zum Explorer (in Office 365 Advanced Threat Protection Plan 2) und zur Echtzeiterkennung (in Office 365 Advanced Threat Protection Plan 1) finden Sie unter [Threat Explorer (und Real-Time Detections)](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer).

### <a name="automated-incident-response"></a>Automatische Vorfall Antwort

Mit den in Office 365 ATP Plan 2 verfügbaren Funktionen für die [Automatische Vorfall Reaktion](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-air) können Sie automatisierte Ermittlungsprozesse als Reaktion auf bekannte Bedrohungen ausführen, die heute vorhanden sind. Durch das Automatisieren bestimmter Ermittlungsaufgaben kann Ihr Sicherheits Betriebsteam effizienter und effektiver arbeiten. Korrekturaktionen, wie das Löschen von böswilligen e-Mail-Nachrichten, werden von Ihrem Sicherheits Betriebsteam zur Genehmigung ausgeführt. Weitere Informationen finden Sie unter [Funktionsweise von Air in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office).

### <a name="attack-simulator"></a>Angriffssimulator

Mit dem [Angriffs Simulator](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator) können autorisierte Benutzer realistische Angriffsszenarien in Ihrer Organisation ausführen. Es stehen verschiedene Arten von Angriffen zur Verfügung, einschließlich eines Anzeigenamens Spear-Phishing-Angriffs, eines Kenn Wort Sprüh Angriffs und eines Brute-Force-Kenn Wort Angriffs.
