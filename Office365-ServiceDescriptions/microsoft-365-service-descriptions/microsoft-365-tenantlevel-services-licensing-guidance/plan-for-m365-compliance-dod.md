---
title: Planen von Microsoft 365 Compliance – DoD-Bereitstellungen
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Diese Anleitung gilt für IT-Profis, die Bereitstellungen von Office 365 in Us Federal Government-Entitäten oder anderen Entitäten antreibt, die Daten verarbeiten, die staatlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government – DoD geeignet ist, um diese Anforderungen zu erfüllen.
ms.openlocfilehash: bc6d69c32db6801763e47984c0513da9c16ba0f8
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546002"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Planen von Microsoft 365 Compliance – DoD-Bereitstellungen

Diese Anleitung gilt für IT-Profis, die Bereitstellungen von Office 365 in Us Federal Government-Entitäten oder anderen Entitäten antreibt, die Daten verarbeiten, die staatlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government – DoD geeignet ist, um diese Anforderungen zu erfüllen.

> [!NOTE]
> Wenn Ihre Organisation die Anforderungen für die Microsoft 365 Government – DoD-Berechtigung bereits erfüllt hat und die Schritte 1 und 2 für das Programm beantragt und akzeptiert hat, können Sie die Schritte 1 und 2 überspringen und direkt zu Schritt 3 wechseln.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Schritt 1. Bestimmen, ob Ihre Organisation eine Microsoft 365 benötigt – DoD und erfüllt Berechtigungsanforderungen

Die Microsoft 365 Government - DoD-Umgebung entspricht den Anforderungen der US-Regierung für Clouddienste.

Organisationen profitieren nicht nur von den Features und Funktionen von Office 365, sondern profitieren auch von den folgenden Features, die für Microsoft 365 Government – DoD einzigartig sind:

- Die Kundeninhalte Ihrer Organisation werden logisch von Kundeninhalten in den kommerziellen Office 365 von Microsoft getrennt.
- Der Kundeninhalt Ihrer Organisation wird in den Vereinigten Staaten gespeichert.
- Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.
- Microsoft 365 Government – DoD entspricht den Zertifizierungen und Akkreditierungen, die für Kunden des öffentlichen US-Amerikanischen Öffentlichen Diensts erforderlich sind.

Weitere Informationen zum Angebot Microsoft 365 Government – DoD für Us Government-Kunden finden Sie unter [Office 365 Government-](https://products.office.com/government/compare-office-365-government-plans)und Berechtigungsanforderungen.

In [Office 365 us Government service description](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) werden die Vorteile der Plattform beschrieben, die sich auf die Einhaltung von Complianceanforderungen in den USA zentriert haben.

> [!TIP]
> Möglicherweise möchten Sie die Informationstabellen in der Dienstbeschreibung in eine Excel-Arbeitsmappe übertragen und zwei Spalten hinzufügen: Relevant für meine Organisation **Y/N** und Erfüllt die Anforderungen meiner Organisation **Y/N**. Anschließend können Sie diese Liste mit Ihren Kollegen überprüfen, um zu bestätigen, dass dieser Dienst den Anforderungen Ihrer Organisation entspricht.

**Entscheidungspunkte**:<br/>
- *Entscheiden Sie, Microsoft 365 government – DoD für Ihre Organisation geeignet ist.*
- *Vergewissern Sie sich, dass Ihre Organisation die Berechtigungsanforderungen erfüllt.*

> [!NOTE]
> Microsoft 365 Government – DoD ist nur in den USA verfügbar. Kunden außerhalb der USA können aus einer Reihe von Office 365 Government [auswählen.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Schritt 2. Beantragen einer Microsoft 365 - DoD

Nachdem Sie entschieden haben, dass dieser Dienst für Ihre Organisation richtig ist, starten Sie den Prozess der [Anwendung für diesen Dienst.](https://products.office.com/government/eligibility-validation)

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Schritt 3: Verstehen Microsoft 365 Government – DoD-Standardsicherheitseinstellungen

Es wird empfohlen, sich zeit zu nehmen, ihre Administrator- und Sicherheitseinstellungen sorgfältig zu überprüfen, bevor Sie sie ändern, und die Auswirkungen auf die Compliance zu berücksichtigen, bevor Sie Änderungen an den Standardsicherheitseinstellungen vornehmen.

**Entscheidungspunkt**: Entscheiden Sie, ob Sie eine der standardmäßigen Microsoft 365 Government - DoD-Sicherheitseinstellungen ändern, um zunächst die Auswirkungen etwaiger Änderungen *zu verstehen.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Schritt 4. Verstehen, welche Funktionen derzeit nicht verfügbar sind oder standardmäßig in Microsoft 365 Government – DoD<sup>1 deaktiviert sind</sup>

Um die Anforderungen unserer Government-Cloud-Kunden zu erfüllen, gibt es einige Unterschiede zwischen Microsoft 365 Government - DoD und Enterprise-Plänen. In der folgenden Tabelle finden Sie Informationen zu den verfügbaren Features. Hier [finden](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) Sie die neuesten Kompatibilitätsproduktupdates, die auf der Microsoft 365 veröffentlicht werden.<br><br>

| Bereich | Feature | DoD-Status |
|------|---------|------------|
| **Schutz von Daten** | Client und Scanner für einheitliche Bezeichnungen | Available |
| | Genaue Übereinstimmung der Daten | Available |
| | Automatische Klassifizierung und Bezeichnung für Exchange Online, SharePoint Online und OneDrive for Business | Rollout |
| | Automatische Klassifizierung und Bezeichnung für Office Apps (Word, Excel, PowerPoint, Outlook) plattformübergreifend (Web, Windows und Mac) | Available |
| | Automatische Klassifizierung und Bezeichnung für Office - Mobile | On Engineering Backlog |
| | Automatische Klassifizierung und Bezeichnung für Teams, Microsoft 365 Gruppen und SharePoint Websites | Available |
| | Obligatorische Bezeichnung | Available |
| | Manuelle Vertraulichkeitsbezeichnung in Office (iOS, Android, Windows) | Available |
| | Konfiguration von Vertraulichkeitsbezeichnungen für verschlüsselungsschutz für Outlook Nachrichten | Rollout |
| **Analyse** | Datenklassifizierung: Übersicht und Inhalts-Explorer | Rollout |
| | Analytics: Machine Learning-Klassifizierungen mit automatischer Bezeichnung auf Dienstseite | In der Entwicklung |
| | Analyse: Maschinelles Lernen mit automatischer Bezeichnung auf Office/Clientseite | Rollout |
| **Verschlüsselung** | Grundlegende Office 365-Nachrichtenverschlüsselung (E3) | Available |
| | Erweiterte Office 365-Nachrichtenverschlüsselung (E5) | Available |
| | Bring Your Own Key (BYOK) für den Lebenszyklus der Bereitstellung von kundenver verwalteten Schlüsseln | Available |
| | Kundenschlüssel für Office 365 | Available |
| | Verschlüsselung mit Doppelschlüssel | Available |
| **Verhinderung von Datenverlust** | Verhinderung von Datenverlust (Data Loss Prevention, DLP) für Dateien und E-Mails | Available |
| | DLP für Teams und Kanalunterhaltungen | Available |
| | DLP: Benachrichtigungsdashboard | Rollout |
| | DLP-Endpunkt | In der Entwicklung |
| | DLP On-prem | On Engineering Backlog |
| | Seite "DLP-Übersicht" | In der Entwicklung |
| **Informationsgovernance** | Information Governance: E-Mail-Archivierung | Available |
| | Informationsverwaltung: Erhaltungssperre | Available |
| | Information Governance: Importieren von PST | Available |
| | Informationssteuerung: Manuelles Anwenden von Aufbewahrungsbezeichnungen ohne Datensatz | Available |
| | Information Governance: Anwenden von Standardaufbewahrungsbezeichnungen SharePoint/OneDrive for Business Bibliotheken, Ordnern und Dokumentenmappen; Exchange Posteingang; und Office 365 Gruppen | Available |
| | Information Governance: Anwenden einer einzelnen Standardaufbewahrungsbezeichnung auf die gesamte Organisation; bestimmte Speicherorte oder Benutzer; und automatisch basierend auf einer bestimmten Bedingung (z. B. Schlüsselwörter oder vertrauliche Informationen) | Available |
| | Information Governance: Anwenden einer Standardbezeichnung für Exchange Posteingange | Available |
| | Information Governance: Mehrstufige Dispositionsüberprüfung | On Engineering Backlog |
| | Information Governance: Aufbewahrungsrichtlinien mit trainierbaren Klassifizierungen | In der Entwicklung |
| | Information Governance: Aufbewahrungsrichtlinien für Teams Chat | Rollout |
| | Information Governance: Aufbewahrungsrichtlinien für Teams Besprechungsaufzeichnung | Available |
| | Information Governance: Aufbewahrungsrichtlinien für Teams private Kanalnachrichten | On Engineering Backlog |
| | Information Governance: Adaptive Bereiche für Aufbewahrungs- und Bezeichnungsrichtlinien | In der Entwicklung |
| | Datensatzverwaltung: Datensatzbeschriftung manuell anwenden | Available |
| | Datensatzverwaltung: Anwenden einer Standarddatensatzbezeichnung für SharePoint, OneDrive for Business, Ordner und Dokumentenmappen; und Office 365 Gruppen | Available |
| | Datensatzverwaltung: Automatische Datensatzrichtlinien basierend auf bestimmten Bedingungen (z. B. Schlüsselwörter oder vertrauliche Informationen); und basierend auf einem Ereignis | Available |
| | Datensatzverwaltung: Dispositionsüberprüfung | Available |
| | Datensatzverwaltung: Dateiplan-Manager | Available |
| | Datensatzverwaltung: Nachweis der Entsorgung | Available |
| | Datensatzverwaltung: Datensatzversionsverwaltung | Available |
| | Datensatzverwaltung: Behördliche Datensätze | Available |
| | Datensatzverwaltung: Verwenden SharePoint Syntexklassifizierung zum Anwenden von Datensatzbezeichnungen | On Engineering Backlog |
| **Insider-Risikomanagement** | Kunden-Lockbox | Available |
| | Insider-Risikomanagement: Falldashboard, Inhalts-Explorer und Benachrichtigungsvorlagen | Rollout |
| | Insider Risk Management: Eskalieren der Untersuchung für Advanced eDiscovery | Rollout |
| | Insider Risk Management: Datendiebstahl durch ausscheidende Benutzer | Rollout |
| | Insider Risk Management: Allgemeine Datenlecks | Rollout |
| | Insider Risk Management: Untersuchen von Insider-Risikomanagementwarnungen | Rollout |
| | Insider Risk Management: Office Indikatoren für Teams, SharePoint Websites, E-Mail-Nachrichten | Rollout |
| | Insider Risk Management Activity Explorer | On Engineering Backlog |
| | Insider Risk Management: Geräteindikatoren für Aktivitäten auf Windows 10 Build 1809 und höher | On Engineering Backlog |
| | Insider Risk Management: Indikatoren für Microsoft Defender for Endpoint-Warnungen | On Engineering Backlog |
| | Insider Risk Management: Indikatoren für Sicherheitsrichtlinienverletzungen | On Engineering Backlog |
| | Insider Risk Management: Richtlinienvorlagen für Datenlecks von unzufriedenen Benutzern | On Engineering Backlog |
| | Insider Risk Management: Richtlinienvorlagen für Datenlecks nach Prioritätsbenutzern | On Engineering Backlog |
| | Insider Risk Management: Richtlinienvorlagen für allgemeine Sicherheitsrichtlinienverletzungen | On Engineering Backlog |
| | Insider Risk Management: Richtlinienvorlagen für Sicherheitsrichtlinienverletzungen durch Prioritätsbenutzer, ausscheidende Benutzer, unzufriedene Benutzer (Vorschau) | On Engineering Backlog |
| | Insider Risk Management: Richtlinienanpassung | On Engineering Backlog |
| | Insider Risk Management: Export alerts | On Engineering Backlog |
| | Insider Risk Management: Microsoft Teams Integration | On Engineering Backlog |
| | Insider Risk Management: Benutzergruppen mit Priorität | On Engineering Backlog |
| | Kommunikationskonformität: Erstellen von Kundenrichtlinien, 3 vorkonfiguriert | Available |
| | Kommunikationskonformität: Unterstützung für Teams, Exchange und Teams Nachricht | Available |
| | Kommunikationskonformität: Zugriffswarnungen; Benachrichtigungsvorlagen; Kommunikationsrichtliniendashboard | Available |
| | Kommunikationskonformität: Eskalieren zur Untersuchung Advanced eDiscovery | Available |
| | Kommunikationskonformität: Erkennt wiederholte Verhaltensverletzungen im Laufe der Zeit | Available |
| | Kommunikationskonformität: Unterstützung für detailliertere Berechtigungen | Available |
| | Kommunikationskonformität: Analysieren Teams Chatdaten von Benutzern mit einem Postfach vor dem Zugriff | Available |
| | Kommunikationskonformität: Vorlage für Interessenkonflikte | Available |
| | Kommunikationskonformität: Möglichkeit, E-Mail-Signatur oder Haftungsausschluss zu ignorieren | In der Entwicklung |
| | Kommunikationskonformität: Möglichkeit zum Festlegen eines Aufbewahrungszeitraums für eine Kommunikations-Compliance-Richtlinie | On Engineering Backlog |
| | Kommunikationskonformität: Erkennen von inhalten für Erwachsene | On Engineering Backlog |
| | Kommunikations-Compliance: Hand-off für Insider-Risikomanagement | In der Entwicklung |
| | Kommunikationskonformität: Überprüfung der Richtlinienintegität und Möglichkeit zum Anhalten der Richtlinie | In der Entwicklung |
| | Kommunikationskonformität: Unterstützung von 7 Sprachen für Bedrohungen, gezielte Belästigungen und Profanities-Klassifizierungen | In der Entwicklung |
| | Kommunikationskonformität: Übersetzen von Integritätsinhalten während der Untersuchung | In der Entwicklung |
| | Informationsbarrieren | Rollout |
| | Verwaltung des privilegierten Zugriffs | On Engineering Backlog |
| **Ermitteln & Antworten** | Core eDiscovery: In-Place-Erhaltung | Available |
| | Kern-eDiscovery: Fallverwaltung | Available |
| | Core eDiscovery: Search | Available |
| | Core eDiscovery: Export | Available |
| | Kern-eDiscovery: RMS-Entschlüsselung | Available |
| | Kern-eDiscovery: Nativer Export | Available |
| | Kern-eDiscovery: Überwachung | Available |
| | Kern-eDiscovery: Compliancegrenzen für OneDrive for Business | Rollout |
| | Advanced eDiscovery: Erweiterte Verarbeitung | Available |
| | Advanced eDiscovery: CJK/Double-Byteunterstützung für Advanced eDiscovery | Available |
| | Advanced eDiscovery: Zuordnung von Verwahrer zu Arbeitsauslastung | Available |
| | Advanced eDiscovery: Custodian Communications | Available |
| | Advanced eDiscovery: Dashboard | Available |
| | Advanced eDiscovery: E-Mail-Threading | Available |
| | Advanced eDiscovery: Exportieren (Herunterladen, Exportieren, Hinzufügen zu einem anderen Überprüfungssatz) | Available |
| | Advanced eDiscovery: Filtern | Available |
| | Advanced eDiscovery: Beinahe doppelte Identifikation | Available |
| | Advanced eDiscovery: Vorhersagecodierung | Available |
| | Advanced eDiscovery: Verarbeiteter Export mit Ladedatei | Available |
| | Advanced eDiscovery: Redactions | Available |
| | Advanced eDiscovery: Überprüfen von Sätzen | Available |
| | Advanced eDiscovery: Überprüfen und Kommentieren | Available |
| | Advanced eDiscovery: Suchbegriffsbericht | Available |
| | Advanced eDiscovery: Unterstützung verknüpfter Inhalte von OneDrive und SharePoint Online (moderne Anlagen) | Available |
| | Advanced eDiscovery: Tagging | Available |
| | Advanced eDiscovery: Unterstützung Teams Reaktionen | Available |
| | Advanced eDiscovery: Mandantenberichte | Available |
| | Advanced eDiscovery: Designs | Available |
| | Advanced eDiscovery: Viewer | Available |
| | Advanced eDiscovery: Yammer Advanced eDiscovery im Microsoft Compliance Center | Available |
| | Advanced eDiscovery: Speicheroptimierungen | In der Entwicklung |
| | Advanced eDiscovery: Microsoft Compliance Center erweiterte Unterstützung für die Suche und den Export von Elementen in SharePoint, OneDrive for Business, Papierkorb in Core und Advanced eDiscovery | In der Entwicklung |
| | Advanced eDiscovery: Rechtlicher Halteraum für nachrichten Teams privaten Kanälen | In der Entwicklung |
| | Advanced eDiscovery: Neues Vorhersagecodierungsmodul | In der Entwicklung |
| | Advanced eDiscovery: Nicht Office 365 Aufnahme | On Engineering Backlog |
| | Advanced eDiscovery: Mandantenberichte | In der Entwicklung |
| | Grundlegende Überwachung | Available |
| | Erweiterte Überwachung: Zugriff auf wichtige Ereignisse (z. B. mailitemsaccessed) | Available |
| | Erweiterte Überwachung: Erhöhte Bandbreite für die Verwaltungsaktivitäts-API | Available |
| | Erweiterte Überwachung: Protokollaufbewahrung (1 Jahr) | Available |
| | Erweiterte Überwachung: E-Mail-Weiterleitungs- und E-Mail-Sendeereignisse | Available |
| | Erweiterte Überwachung: Verfügbarkeit von Security and Compliance Center | Available |
| | Erweiterte Überwachung: Langfristige Aufbewahrung in Überwachungsprotokollen (10 Jahre) | In der Entwicklung |
| | Erweiterte Überwachung: Suchbegriffsereignisse in Exchange Online und SharePoint Online | On Engineering Backlog |
| **Verwaltung der Richtlinientreue** | Microsoft 365 Security and Compliance Center | Available |
| | Microsoft Cloud App Security | In der Entwicklung |
| | Compliance-Manager | Available |
| | Unterstützung für Doppelte Bytezeichen | Available |
| **Ökosystem** | First-Party-Datenconnectors: HR | Available |
| | First-Party-Datenconnectors: Instant Bloomberg, Bloomberg Mail, LinkedIn Business-Seiten, ICE Chat | On Engineering Backlog |
| | Daten-Connectoren von Drittanbietern | On Engineering Backlog |
| | Graph APIs für Advanced eDiscovery | In der Entwicklung |
| | Graph APIs für Teams Exportieren von Daten | On Engineering Backlog |

<sup>1</sup> Der identifizierte Status kann geändert werden, wenn Projektpläne und Prioritäten neu bewertet werden.<br/>

**Entscheidungspunkt:** *Entscheiden Sie, ob die Compliancefeatures den Anforderungen Ihrer Organisation entsprechen.*
