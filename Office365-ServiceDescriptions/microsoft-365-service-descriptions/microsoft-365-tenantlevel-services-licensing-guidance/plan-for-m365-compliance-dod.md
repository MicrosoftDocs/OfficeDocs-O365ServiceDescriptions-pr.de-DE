---
title: Planen von Microsoft 365 Compliance – DoD-Bereitstellungen
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in US-Bundesbehörden oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government – DoD geeignet ist, um diese Anforderungen zu erfüllen.
ms.openlocfilehash: a619943b5eed63007b78613ab9b6715a52ef467d
ms.sourcegitcommit: d0ca41de5b242d2d5688d92d55064d9eecbb89a9
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601720"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Planen von Microsoft 365 Compliance – DoD-Bereitstellungen

Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in US-Bundesbehörden oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government – DoD geeignet ist, um diese Anforderungen zu erfüllen.

> [!NOTE]
> Wenn Ihre Organisation bereits die Zulassungsvoraussetzungen für das Microsoft 365 Government – DoD erfüllt und in das Programm übernommen und akzeptiert wurde, können Sie die Schritte 1 und 2 überspringen und direkt zu Schritt 3 wechseln.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Schritt 1. Ermitteln, ob Ihre Organisation Microsoft 365 Government-DoD benötigt und die Zulassungsvoraussetzungen erfüllt

Die Microsoft 365 Government-DoD-Umgebung erfüllt die US-behördlichen Anforderungen für Cloud-Dienste.

Neben den Features und Funktionen von Office 365 profitieren Organisationen von den folgenden Features, die für Microsoft 365 Government – DoD einzigartig sind:

- Der Kunden Inhalt Ihrer Organisation wird logischerweise von Kundeninhalten in den kommerziellen Office 365 Diensten von Microsoft getrennt.
- Der Kundeninhalt Ihrer Organisation wird in den Vereinigten Staaten gespeichert.
- Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.
- Microsoft 365 Government-DoD erfüllt Zertifizierungen und Akkreditierungen, die für US-Kunden im öffentlichen Sektor erforderlich sind.

Weitere Informationen zum Microsoft 365 Government-DoD-Angebot für Kunden der US-Regierung finden Sie unter [Office 365 Government-Pläne](https://products.office.com/government/compare-office-365-government-plans), einschließlich der Berechtigungsanforderungen.

Die [Office 365 US Government Service Description](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) beschreibt die Vorteile der Plattform, die sich auf die Erfüllung der Compliance-Anforderungen in den Vereinigten Staaten konzentrieren.

> [!TIP]
> Möglicherweise möchten Sie die Tabellen mit Informationen in der Dienstbeschreibung in eine Excel-Arbeitsmappe übertragen und zwei Spalten hinzufügen: **relevant für meine Organisation y/n** und **den Anforderungen meiner Organisation y/n entsprechen**. Anschließend können Sie diese Liste mit ihren Kollegen überprüfen, um zu bestätigen, dass dieser Dienst die Anforderungen Ihrer Organisation erfüllt.

**Entscheidungspunkte**:<br/>
- *Entscheiden Sie, ob das Microsoft 365 Government-DoD für Ihre Organisation geeignet ist.*
- *Stellen Sie sicher, dass Ihre Organisation die Berechtigungsanforderungen erfüllt.*

> [!NOTE]
> Microsoft 365 Government-DoD ist nur in den Vereinigten Staaten verfügbar. Kunden außerhalb der US-Regierung können aus einer Reihe von [Office 365 Government-Plänen](https://products.office.com/government/compare-office-365-government-plans)wählen.

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Schritt 2. Beantragen von Microsoft 365 Government-DoD

Nachdem Sie entschieden haben, dass dieser Dienst für Ihre Organisation geeignet ist, starten Sie den Prozess der [Beantragung dieses Diensts](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Schritt 3. Grundlegendes zu Microsoft 365-Standardsicherheitseinstellungen für das Government-DoD

Es wird empfohlen, dass Sie sich Zeit nehmen, um die Administrator-und Sicherheitseinstellungen sorgfältig zu überprüfen, bevor Sie Sie ändern und die Auswirkungen auf die Kompatibilität berücksichtigen, bevor Sie Änderungen an den Standardsicherheitseinstellungen vornehmen.

**Entscheidungspunkt**: *entscheiden Sie, ob Sie die Standardsicherheitseinstellungen von Microsoft 365 Government-DoD ändern, um zunächst die Auswirkungen von Änderungen zu verstehen, die Sie möglicherweise vornehmen.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Schritt 4: Verstehen, welche Funktionen derzeit in Microsoft 365 Government – DoD<sup>1</sup> standardmäßig nicht verfügbar oder deaktiviert sind

Um die Anforderungen unserer Government Cloud-Kunden zu erfüllen, gibt es einige Unterschiede zwischen Microsoft 365 Government-DoD und Enterprise-Plänen. In der folgenden Tabelle finden Sie Informationen zu verfügbaren Features. [Hier](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) finden Sie die neuesten Kompatibilitäts Produktupdates, die im Microsoft 365-Fahrplan veröffentlicht wurden.<br><br>

| Bereich                                    | Feature                                         | GCC-Status             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Schutz von Daten**              | Unified Labeling-Client und-Scanner         | Available              |
|                                         | Exakte Datenübereinstimmung          | Available               |
|                                         | Automatische Klassifizierung und Beschriftung für Exchange Online, SharePoint Online und OneDrive                      | Rollout              |
|                                         | Automatische Klassifizierung und Beschriftung für Office-Apps (Word, Excel, PowerPoint, Outlook) plattformübergreifend (Internet, Android, Ios, Windows und Mac)            | In der Entwicklung |
|                                         | Automatische Klassifizierung und Kennzeichnung für mobile Geräte                                       | Im Entwicklungsrückstand              |
|                                         | Automatische Klassifizierung und Kennzeichnung für Teams                            | Im Entwicklungsrückstand |
|                                         | Datenklassifizierung: Übersicht und Inhalts-Explorer                            | In der Entwicklung |
|                                         | Analyse: maschinelle Schulungs Klassifizierungen mit automatischer Kennzeichnung auf Dienstseite                           | Im Entwicklungsrückstand  |
|                                         | Analyse: maschinelle Schulungs Klassifizierungen mit automatischer Kennzeichnung auf Office-Apps/Clientseite                           | Im Entwicklungsrückstand  |
|                                         | Grundlegende Office 365 Nachrichtenverschlüsselung (E3)                            | Available              |
|                                         | Erweiterte Office 365 Nachrichtenverschlüsselung (E5)  | Available              |
|                                         | Kundenschlüssel für Office 365    | Available |
|                                         | Mitbringen eines eigenen Schlüssels (BYOK) für den Lebenszyklus von Kunden verwalteter Schlüssel Bereitstellung                            | Available |
|                                         | Halten Sie Ihren eigenen Schlüssel (Hyok), der sich über Azure Information Protection-und Active Directory (AD)-Rechteverwaltung für stark regulierte Szenarien erstreckt (Vorschau)                         | Available |
|                                         | Verschlüsselung mit Doppelschlüssel                           | Rollout |
|                                         | Verhinderung von Datenverlust (DLP) für Dateien und e-Mail         | Available |
|                                         | DLP für Microsoft Teams-Chat und Kanal Unterhaltungen         | Im Entwicklungsrückstand |
|                                         | Exakte DLP-Datenübereinstimmung         | Im Entwicklungsrückstand |
|                                         | DLP-Endpunkt | Im Entwicklungsrückstand |
| **Informationsgovernance** | Information Governance: e-Mail-Archivierung                                       | Available              |
|                                         | Information Governance: Aufbewahrungs Sperre          | Available              |
|                                         | Information Governance: Importieren von PST-Dateien                      | Available              |
|                                         | Information Governance: manuelle Aufbewahrungs Bezeichnungen, die nicht aufgezeichnet werden            | Available |
|                                         | Information Governance: standardmäßige Aufbewahrungs Bezeichnungen für SharePoint/OneDrive für Unternehmen-Bibliotheken,-Ordner und-Dokumentenmappen; Exchange-Posteingänge; und Office 365 Gruppen | Available              |
|                                         | Information Governance: Aufbewahrungsrichtlinien für die gesamte Organisation; bestimmte Standorte oder Benutzer; und automatisch basierend auf bestimmten Bedingungen (beispielsweise Schlüsselwörter oder vertrauliche Informationen)                                       | Available              |
|                                         | Information Governance: Aufbewahrungsrichtlinien mit Schulungs Klassifizierern                            | Im Entwicklungsrückstand |
|                                         | Information Governance: Aufbewahrungsrichtlinien für Microsoft Teams-Besprechungsaufzeichnungen                            | Im Entwicklungsrückstand |
|                                         | Information Governance: Aufbewahrungsrichtlinien für jammern und Teams                           | Im Entwicklungsrückstand              |
|                                         | Datensatzverwaltung: manuelle Klassifizierung für Daten Satzbezeichnungen                              | Available              |
|                                         | Datensatzverwaltung: standardmäßige Daten Satzbezeichnungen für SharePoint, OneDrive für Unternehmen Bibliotheken, Ordner und Dokumentenmappen; und Office 365 Gruppen                            | Available              |
|                                         | Datensatzverwaltung: automatische Datensatzrichtlinien basierend auf bestimmten Bedingungen (beispielsweise Schlüsselwörter oder vertrauliche Informationen); und basierend auf einem Ereignis  | Available              |
|                                         | Datensatzverwaltung: Disposition Review    | Available |
|                                         | Datensatzverwaltung: Datei Plan-Manager                            | Available |
|                                         | Datensatzverwaltung: Nachweis der Entsorgung                         | Available |
|                                         | Datensatzverwaltung: regulatorische Datensätze | Im Entwicklungsrückstand |
|                                         | Datensatzverwaltung: mehrstufige Dispositions Überprüfung | Im Entwicklungsrückstand |
|                                         | Datensatzverwaltung: Verwenden von SharePoint-Syntex Klassifizierung zum Anwenden von Daten Satzbezeichnungen         | Im Entwicklungsrückstand |
| **Insider-Risikomanagement**             | Kunden-Lockbox                                | Available            |
|                                         | Insider Risiko Management: Office-Indikatoren für Teams, SharePoint-Websites, e-Mail-Messaging                         | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Datendiebstahl durch Benutzer                        | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: allgemeine Datenlecks                                | Im Entwicklungsrückstand              |
|                                         | Insider Risikomanagement: Untersuchen von Warnungen beim Insider Risikomanagement                                   | Im Entwicklungsrückstand              |
|                                         | Insider Risikomanagement: Fall Dashboard, Inhalts-Explorer und Benachrichtigungsvorlagen | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Eskalation zur Untersuchung für Advanced eDiscovery |Im Entwicklungsrückstand|
|                                         | Insider Risiko Management: Geräte Indikatoren für Aktivitäten unter Windows 10 Build 1809 und höher |Im Entwicklungsrückstand|
|                                         | Insider Risiko Management: Indikatoren für Sicherheitsrichtlinienverletzungen (Vorschau) |Im Entwicklungsrückstand|
|                                         | Insider Risiko Management: Indikatoren für Microsoft Defender für Endpoint Alerts (Vorschau) |Im Entwicklungsrückstand|
|                                         | Insider Risiko Management: Richtlinienvorlagen für Datenverluste nach Prioritäts Benutzern (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Richtlinienvorlagen für Datenverluste durch verärgerte Benutzer (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Richtlinienvorlagen für allgemeine Sicherheitsrichtlinienverletzungen (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Richtlinienvorlagen für Sicherheitsrichtlinienverletzungen nach Prioritäts Benutzern, Benutzer mit abgehender Priorität, verärgerte Benutzer (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Richtlinien Anpassung (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Export Benachrichtigungen (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Prioritäts Benutzergruppen (Vorschau) | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Erstellen von Kunden Richtlinien, 3 vorkonfiguriert  | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Unterstützung für Teams, Exchange und Entfernen von Microsoft Teams-Nachricht | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Zugriffs Warnungen; Hinweis Vorlagen; Kommunikationsrichtlinien-Dashboard | Im Entwicklungsrückstand  |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Eskalation zur Untersuchung für Advanced eDiscovery | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Ermitteln von Inhalten für Erwachsene | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (inkl. Aufsichtsrichtlinien): erkennt Wiederholungs Code Verstoß im Laufe der Zeit | Rollout |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Unterstützung für detailliertere Berechtigungen | Rollout |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Analysieren von Chat Daten von Benutzern mit einem "on-Prem"-Postfach | Rollout |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Vorlage für Interessenkonflikte | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Möglichkeit zum Ignorieren von e-Mail-Signaturen oder Haftungsausschlüssen | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (inkl. Aufsichtsrichtlinien): Insider Risk Management – Übergabe | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Richtlinienintegritätsprüfung und Fähigkeit zum Anhalten der Richtlinie | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Übersetzen von Integritäts Inhalten während der Untersuchung | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Burnout und Selbstmord Erkennung | Im Entwicklungsrückstand |
|                                         | Informationsbarrieren | Im Entwicklungsrückstand |
|                                         | Privileged Access Management                    | Im Entwicklungsrückstand |
| **Antworten auf & ermitteln**                  | Zentrale eDiscovery: in-Place-Aufbewahrung                            | Available              |
|                                         | Zentrale eDiscovery: Fallverwaltung                                 | Available              |
|                                         | Zentrale eDiscovery: Suche                                          | Available              |
|                                         | Haupt-eDiscovery: Export                                          | Available              |
|                                         | Zentrale eDiscovery: RMS-Entschlüsselung                                  | Available              |
|                                         | Zentrale eDiscovery: nativer Export                                   | Available              |
|                                         | Zentrale eDiscovery: Überwachung                                        | Available              |
|                                         | Erweiterte eDiscovery: erweiterte Verarbeitung                                 | Rollout |
|                                         | Erweiterte eDiscovery: Depotverwaltung für Arbeits Auslastungs Zuordnung                                 | Rollout |
|                                         | Erweiterte eDiscovery: Depotbank-Kommunikation                                 | Rollout |
|                                         | Erweiterte eDiscovery: Dashboard                   | Rollout |
|                                         | Erweiterte eDiscovery: e-Mail-Threading                                          | Rollout |
|                                         | Advanced eDiscovery: Export (herunterladen, exportieren, zu einem anderen Überprüfungs Sätze hinzufügen)                               | Rollout |
|                                         | Erweiterte eDiscovery: Filterung                 | Rollout |
|                                         | Erweiterte eDiscovery: rechtliche Aufbewahrung für private Channel-Nachrichten in Microsoft Teams                                         | Rollout |
|                                         | Erweiterte eDiscovery: nahe doppelte Identifikation                                         | Rollout |
|                                         | Erweiterte eDiscovery: nicht Office 365E Einnahme                                      | Rollout |
|                                         | Advanced eDiscovery: Predictive Coding                                       | Rollout |
|                                         | Erweiterte eDiscovery: verarbeitete Exportdatei mit lastdatei                   | Rollout |
|                                         | Erweiterte eDiscovery:-Aktionen                        | Rollout |
|                                         | Erweiterte eDiscovery: Überprüfungs Sätze                                     | Rollout |
|                                         | Erweiterte eDiscovery: überprüfen und kommentieren                             | Rollout |
|                                         | Erweiterte eDiscovery: Suchbegriffs Bericht                        | Rollout |
|                                         | Erweiterte eDiscovery: Unterstützung für verknüpfte Inhalte aus OneDrive und SharePoint Online (moderne Anlagen)                        | Rollout |
|                                         | Erweiterte eDiscovery: Tagging                              | Rollout |
|                                         | Erweiterte eDiscovery: Teams-Reaktions Unterstützung                              | Rollout |
|                                         | Erweiterte eDiscovery: Mandanten Berichte                              | Rollout |
|                                         | Erweiterte eDiscovery: Designs                              | Rollout |
|                                         | Erweiterte eDiscovery: Viewer                              | Rollout |
|                                         | Erweiterte eDiscovery: jammern erweiterte eDiscovery im Microsoft Compliance Center                              | Rollout |
|                                         | Erweiterte eDiscovery: cjk/Double Byte-Unterstützung für Advanced eDiscovery                              | In der Entwicklung |
|                                         | Grundlegende Überwachung                              | Available |
|                                         | Erweiterte Überwachung: Zugriff auf wichtige Ereignisse (beispielsweise mailitemsaccessed)                              | Rollout |
|                                         | Erweiterte Überwachung: erhöhte Bandbreite zur Verwaltungs Aktivitäts-API                              | Rollout |
|                                         | Erweiterte Überwachung: Protokollaufbewahrung (1 Jahr)                              | Rollout |
|                                         | Erweiterte Überwachung: Sicherheit und Compliance Center-Verfügbarkeit                              | Available |
|                                         | Erweiterte Überwachung: längerfristige Aufbewahrung in Überwachungsprotokollen (10 Jahre)                              | Im Entwicklungsrückstand |
|                                         | Erweiterte Überwachung: e-Mail-Weiterleitung und e-Mail-Sendeereignisse                              | Im Entwicklungsrückstand |
|                                         | Erweiterte Überwachung: verarbeitete Überwachungs Einblicke                              | Im Entwicklungsrückstand |
|                                         | Erweiterte Überwachung: Suchbegriffs Ereignisse in Exchange Online und SharePoint Online                              | Im Entwicklungsrückstand |
|    **Verwaltung der Richtlinientreue**            | Microsoft 365 Security and Compliance Center                              | Available |
|                                         | Microsoft Cloud App Security                              | Im Entwicklungsrückstand |
|                                         | Compliance-Manager                              | Im Entwicklungsrückstand |
|                                         | Unterstützung von Doppelbytezeichen                              | Im Entwicklungsrückstand |
|    **Ökosystem**            | Graph-APIs für Advanced eDiscovery                              | In der Entwicklung |
|                                         | Erstanbieter-Daten-Konnektoren                              | Im Entwicklungsrückstand |
|                                         | Daten-Connectoren von Drittanbietern                              | Im Entwicklungsrückstand |
|                                         | Diagramm-APIs für Teams Exportieren von Daten                              | Im Entwicklungsrückstand |

<sup>1</sup> der Status "identifiziert" kann geändert werden, wenn Projektpläne und Prioritäten neu ausgewertet werden.<br/>

**Entscheidungspunkt**: *entscheiden Sie, ob die Konformitäts Funktionen den Anforderungen Ihrer Organisation entsprechen.*
