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
ms.openlocfilehash: 5781f34419eb697cb97634c55fa486fd141d76dd
ms.sourcegitcommit: 7ee8775831fd481ab2ef477245d2ae2af98ac2d7
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/30/2021
ms.locfileid: "53204842"
---
# <a name="microsoft-defender-for-office-365-service-description"></a>Microsoft Defender für Office 365-Dienstbeschreibung

Microsoft Defender für Office 365 ist ein cloudbasierter E-Mail-Filterdienst, der Ihre Organisation vor erweiterten Bedrohungen für E-Mail- und Zusammenarbeitstools wie Phishing, Geschäftliche E-Mail-Kompromittierung und Schadsoftwareangriffe schützt. Defender für Office 365 bietet auch Untersuchungs-, Such- und Korrekturfunktionen, mit denen Sicherheitsteams Bedrohungen effizient identifizieren, priorisieren, untersuchen und darauf reagieren können.

Es folgen die wichtigsten Möglichkeiten, wie Sie Defender für Office 365 für den Nachrichtenschutz verwenden können:

- In einem Szenario mit nur-Filterung für Defender für Office 365 bietet Defender für Office 365 cloudbasierten E-Mail-Schutz für Ihre lokale Exchange Server umgebung oder eine andere lokale SMTP-E-Mail-Lösung.

- Defender für Office 365 kann aktiviert werden, um Exchange Online in der Cloud gehostete Postfächer zu schützen. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online Dienstbeschreibung.](exchange-online-service-description/exchange-online-service-description.md)

- In einer Hybridbereitstellung kann Defender für Office 365 konfiguriert werden, um Ihre Messagingumgebung zu schützen und das E-Mail-Routing zu steuern, wenn Sie über eine Mischung aus lokalen und Cloudpostfächern mit Exchange Online Protection für eingehende E-Mail-Filterung verfügen.

## <a name="available-plans"></a>Verfügbare Pläne

Ausführliche Informationen zum Plan zu Abonnements, die Benutzer für Microsoft Defender für Office 365 aktivieren, finden Sie in der [vollständigen Vergleichstabelle](https://go.microsoft.com/fwlink/?linkid=2139145)für Abonnements.

## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

In der folgenden Tabelle sind die wichtigsten Features von Microsoft Defender für Office 365 aufgeführt, die in allen Plänen verfügbar sind. Einige Vorbehalte gelten. Lesen Sie die Fußnoten für weitere Informationen. Diese Tabelle kann ohne vorherige Ankündigung geändert werden. Die aktuellste, vollständige Liste von Microsoft Defender für Office 365 Features in allen Plänen finden Sie unter [Microsoft Defender for Office 365 Features Service Description.](microsoft-defender-for-office-365-features.md)

| Feature | Microsoft Defender für Office 365 Plan 1 | Microsoft Defender für Office 365 Plan 2 | Microsoft 365 E5/A5 Security |
|---------|--------------------------------|--------------------------------|--------------------------------|
| *Konfiguration, Schutz und Erkennung* | | | |
| Voreingestellte Sicherheitsrichtlinien und Configuration Analyzer | Ja | Ja | Ja |
| [Sichere Anlagen](microsoft-defender-for-office-365-features.md#safe-attachments) | Ja | Ja | Ja |
| Tresor Anlagen in Teams | Ja | Ja | Ja |
| [Sichere Links](microsoft-defender-for-office-365-features.md#safe-links) | Ja | Ja | Ja |
| [Sichere Dokumente](microsoft-defender-for-office-365-features.md#safe-documents) | Nein | Nein | Ja |
| Sichere Links in Teams | Ja | Ja | Ja |
| Add-In melden | Ja | Ja | Ja |
| [Schutz für SharePoint, OneDrive und Microsoft Teams](microsoft-defender-for-office-365-features.md#protection-for-sharepoint-onedrive-and-microsoft-teams) | Ja | Ja | Ja |
| [Antiphishingrichtlinien](microsoft-defender-for-office-365-features.md#anti-phishing-policies) | Ja | Ja | Ja |
| [Echtzeitberichte](microsoft-defender-for-office-365-features.md#real-time-reports) | Ja | Ja | Ja |
| Erweiterter Schutz für interne E-Mails | Ja | Ja | Ja |
| *Automatisierung, Untersuchung, Wartung und Bildung* | | | |
| [Bedrohungs-Tracker](microsoft-defender-for-office-365-features.md#threat-trackers) | Nein | Ja | Ja |
| Kampagnenansichten | Nein | Ja | Ja |
| Bedrohungsuntersuchung (erweiterte Bedrohungsuntersuchung) | [Echtzeiterkennungen](microsoft-defender-for-office-365-features.md#real-time-detections) | [Explorer](microsoft-defender-for-office-365-features.md#threat-explorer) | [Explorer](microsoft-defender-for-office-365-features.md#threat-explorer) |
| [Automatisierte Untersuchung & Antwort](microsoft-defender-for-office-365-features.md#automated-investigation--response) | Nein | Ja | Ja |
| [Angriffssimulationstraining](microsoft-defender-for-office-365-features.md#attack-simulation-training) | Nein | Ja | Ja |
| *Integration in [Microsoft 365 Defender](/microsoft-365/security/defender/microsoft-365-defender)* | Nein | Ja | Ja |

> [!NOTE]
> Microsoft Defender für Office 365 ist eine Komponente von Microsoft 365 Defender. Weitere Informationen zur automatisierten domänenübergreifenden Sicherheit mit Microsoft 365 Defender finden Sie unter [Microsoft 365 Defender Anforderungen.](/microsoft-365/security/mtp/prerequisites)

## <a name="learn-more"></a>Weitere Informationen

Weitere Informationen zu Microsoft Defender für Office 365 finden Sie in den folgenden Ressourcen:

- [Microsoft Defender für Office 365 in Microsoft-Dokumenten](/microsoft-365/security/office-365-security/defender-for-office-365)
- [Microsoft Defender für Office 365 Website](https://www.microsoft.com/security/business/threat-protection/office-365-defender)
- [Blog zu Microsoft Defender für Office 365](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bg-p/MicrosoftDefenderforOffice365Blog)
- [Microsoft Defender für Office 365 Forum](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bd-p/MicrosoftDefenderforOffice365)

### <a name="licensing-terms"></a>Lizenzierungsbedingungen

Lizenzierungsbestimmungen für Produkte und Dienste, die Sie über kommerzielle Volumenlizenzierungsprogramme von Microsoft erworben haben, finden Sie auf der [Website für Produktbestimmungen](https://www.microsoft.com/licensing/terms/).

### <a name="messaging"></a>Nachrichten

Um über bevorstehende Änderungen, einschließlich neuer und geänderter Features, geplanter Wartung oder anderer wichtiger Ankündigungen, auf dem Laufenden zu bleiben, besuchen Sie das Nachrichtencenter. Weitere Informationen finden Sie unter [Nachrichtencenter](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Barrierefreiheit

Microsoft bleibt der Sicherheit Ihrer Daten und der [Barrierefreiheit](https://www.microsoft.com/trust-center/compliance/accessibility) unserer Dienste verpflichtet. Weitere Informationen finden Sie im [Microsoft Trust Center](https://www.microsoft.com/trust-center) und dem [Office-Barrierefreiheitscenter](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
