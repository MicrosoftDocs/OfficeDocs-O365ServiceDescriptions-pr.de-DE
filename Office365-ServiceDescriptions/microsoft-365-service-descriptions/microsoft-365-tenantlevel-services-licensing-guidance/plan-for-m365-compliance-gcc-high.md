---
title: Planen von Microsoft 365 Compliance – GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in US-Bundesbehörden oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, in denen die Verwendung von Microsoft 365 Government – gcc High geeignet ist, um diese Anforderungen zu erfüllen.
ms.openlocfilehash: 8101a5801b01ba3c2d6e72e28cc0ce482b17ac8b
ms.sourcegitcommit: 29db7a8836114967fa3bf95ceed0b01222959962
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/02/2020
ms.locfileid: "48830356"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Plan for Microsoft 365 Compliance – gcc High

Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in US-Bundesbehörden oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, in denen die Verwendung von Microsoft 365 Government – gcc High geeignet ist, um diese Anforderungen zu erfüllen.

> [!NOTE]
>Wenn Ihre Organisation bereits die hohen Zulassungsvoraussetzungen für Microsoft 365 Government – gcc erfüllt und in das Programm übernommen und akzeptiert wurde, können Sie die Schritte 1 und 2 überspringen und direkt zu Schritt 3 wechseln.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Schritt 1: Ermitteln, ob Ihre Organisation Microsoft 365 Government – gcc High benötigt und erfüllt die Zulassungsvoraussetzungen

Die Microsoft 365 Government-gcc High Environment erfüllt die US-behördlichen Anforderungen für Cloud-Dienste. Neben den Features und Funktionen von Office 365 profitieren Organisationen von den folgenden Features, die für Microsoft 365 Government – gcc High einzigartig sind:

- Der Kunden Inhalt Ihrer Organisation wird logischerweise von Kundeninhalten in den kommerziellen Office 365 Diensten von Microsoft getrennt.
- Der Kundeninhalt Ihrer Organisation wird in den Vereinigten Staaten gespeichert.
- Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.
- Microsoft 365 Government – gcc High erfüllt die Zertifizierungen und Akkreditierungen, die für US-Kunden des öffentlichen Sektors erforderlich sind.

Weitere Informationen zum Microsoft 365 Government – gcc High-Angebot für US-Regierungskunden finden Sie unter [Office 365 Government-Pläne](https://products.office.com/government/compare-office-365-government-plans), einschließlich Berechtigungsanforderungen.

Die [Office 365 US Government Service Description](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) beschreibt die Vorteile der Plattform, die sich auf die Erfüllung der Compliance-Anforderungen in den Vereinigten Staaten konzentrieren.

> [!TIP]
> Möglicherweise möchten Sie die Tabellen mit Informationen in der Dienstbeschreibung in eine Excel-Arbeitsmappe übertragen und zwei Spalten hinzufügen: **relevant für meine Organisation y/n** und **den Anforderungen meiner Organisation y/n entsprechen** . Anschließend können Sie diese Liste mit ihren Kollegen überprüfen, um zu bestätigen, dass dieser Dienst die Anforderungen Ihrer Organisation erfüllt.

**Entscheidungspunkte** :<br/>
- *Entscheiden Sie, ob Microsoft 365 Government – GCC-High für Ihre Organisation geeignet ist.*
- *Stellen Sie sicher, dass Ihre Organisation die Berechtigungsanforderungen erfüllt.*

> [!NOTE]
> Microsoft 365 Government-gcc High ist nur in den Vereinigten Staaten verfügbar. Kunden außerhalb der US-Regierung können aus einer Reihe von [Office 365 Government-Plänen](https://products.office.com/government/compare-office-365-government-plans)wählen.

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Schritt 2: Beantragen von Microsoft 365 Government – GCC-High

Nachdem Sie entschieden haben, dass dieser Dienst für Ihre Organisation geeignet ist, starten Sie den Prozess der [Beantragung dieses Diensts](https://products.office.com/government/eligibility-validation).
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Schritt 3: Grundlegendes zu Microsoft 365 Government – GCC-High Standardsicherheitseinstellungen

Es wird empfohlen, dass Sie sich Zeit nehmen, um die Administrator-und Sicherheitseinstellungen sorgfältig zu überprüfen, bevor Sie Sie ändern und die Auswirkungen auf die Kompatibilität berücksichtigen, bevor Sie Änderungen an den Standardsicherheitseinstellungen vornehmen.

**Entscheidungspunkt** : *entscheiden Sie, ob Sie die standardmäßigen Microsoft 365 Government-GCC-High-Sicherheitseinstellungen ändern, um zunächst die Auswirkungen von Änderungen zu verstehen, die Sie möglicherweise vornehmen.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Schritt 4: Verstehen, welche Funktionen derzeit in Microsoft 365 Government – gcc-High<sup>1</sup> standardmäßig nicht verfügbar oder deaktiviert sind

Um die Anforderungen unserer Government Cloud-Kunden zu erfüllen, gibt es einige Unterschiede zwischen Microsoft 365 Government – GCC-High und Enterprise-Plänen. In der folgenden Tabelle finden Sie Informationen zu verfügbaren Features. [Hier](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) finden Sie die neuesten Kompatibilitäts Produktupdates, die im Microsoft 365-Fahrplan veröffentlicht wurden.<br><br>

| Bereich                                    | Feature                                         | GCC-Status             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Schutz von Daten**              | Unified Labeling-Client und-Scanner         | Available              |
|                                         | Exakte Datenübereinstimmung          | Available              |
|                                         | Automatische Klassifizierung und Beschriftung für Exchange Online, SharePoint Online und OneDrive                      | Rollout              |
|                                         | Automatische Klassifizierung und Kennzeichnung für Office-Apps (Word, Excel, PowerPoint, Outlook) über das Internet, Android, Ios, Windows und Mac            | In der Entwicklung |
|                                         | Automatische Klassifizierung und Bezeichnung für Office-Clients (Mobile)                                       | Im Entwicklungsrückstand              |
|                                         | Automatische Klassifizierung und Kennzeichnung für Teams                            | Im Entwicklungsrückstand |
|                                         | Analyse der Datenklassifikation: Übersicht und Inhalts-Explorer                            | Im Entwicklungsrückstand |
|                                         | Analyse: maschinelle Schulungs Klassifizierungen mit automatischer Kennzeichnung auf Dienstseite                           | Im Entwicklungsrückstand  |
|                                         | Analyse: maschinelle Schulungs Klassifizierungen mit automatischer Kennzeichnung auf Office-Apps/Clientseite                           | Im Entwicklungsrückstand  |
|                                         | Grundlegende Office 365 Nachrichtenverschlüsselung (E3)                            | Available              |
|                                         | Erweiterte Office 365 Nachrichtenverschlüsselung (E5)  | Available              |
|                                         | Kundenschlüssel für Office 365    | Available |
|                                         | Mitbringen eines eigenen Schlüssels (BYOK) für den Lebenszyklus von Kunden verwalteter Schlüssel Bereitstellung                            | Available |
|                                         | Halten Sie Ihren eigenen Schlüssel (Hyok), der sich über Azure Information Protection-und Active Directory (AD)-Rechteverwaltung für stark regulierte Szenarien erstreckt (Vorschau)                         | Available |
|                                         | Verschlüsselung mit Doppelschlüssel                           | Available |
|                                         | Verschlüsselung: gemeinsame Dokumenterstellung in verschlüsselten Dokumenten mit WXP-Webanwendungen         | Im Entwicklungsrückstand |
|                                         | Verhinderung von Datenverlust (DLP) für Dateien und e-Mail         | Available |
|                                         | DLP für Microsoft Teams-Chat und Kanal Unterhaltungen | Im Entwicklungsrückstand |
|                                         | DLP-Endpunkt | Im Entwicklungsrückstand |
| **Informationsgovernance** | Information Governance: e-Mail-Archivierung                                       | Available              |
|                                         | Information Governance: Aufbewahrungs Sperre          | Available              |
|                                         | Information Governance: Importieren von PST-Dateien                      | Available              |
|                                         | Information Governance: manuelle Aufbewahrungs Bezeichnungen, die nicht aufgezeichnet werden            | Available |
|                                         | Information Governance: standardmäßige Aufbewahrungs Bezeichnungen für SharePoint/OneDrive für Unternehmen-Bibliotheken,-Ordner und-Dokumentenmappen; Exchange-Posteingänge; und Office 365 Gruppen | Available              |
|                                         | Information Governance: Aufbewahrungsrichtlinien für die gesamte Organisation; bestimmte Standorte oder Benutzer; automatisch basierend auf einer bestimmten Bedingung (beispielsweise Schlüsselwörter oder vertrauliche Informationen); und basierend auf einem Ereignis                                       | Available              |
|                                         | Information Governance: Aufbewahrungsrichtlinien für Teams                            | Im Entwicklungsrückstand |
|                                         | Information Governance: Aufbewahrungs Bezeichnungen mithilfe der SharePoint-Syntex Klassifizierung                            | Im Entwicklungsrückstand |
|                                         | Information Governance: Aufbewahrungsrichtlinien mit Schulungs Klassifizierern                            | Im Entwicklungsrückstand |
|                                         | Information Governance: Aufbewahrungsrichtlinien für Microsoft Teams-Besprechungsaufzeichnungen                            | Im Entwicklungsrückstand |
|                                         | Information Governance: Aufbewahrungsrichtlinien für jammern                            | Im Entwicklungsrückstand |
|                                         | Datensatzverwaltung: manuelle Klassifizierung für Daten Satzbezeichnungen                           | Available              |
|                                         | Datensatzverwaltung: standardmäßige Daten Satzbezeichnungen für SharePoint, OneDrive für Unternehmen Bibliotheken, Ordner und Dokumentenmappen; und Office 365 Gruppen                              | Available              |
|                                         | Datensatzverwaltung: automatische Datensatzrichtlinien basierend auf bestimmten Bedingungen (beispielsweise Schlüsselwörter oder vertrauliche Informationen); und basierend auf einem Ereignis                            | Available              |
|                                         | Datensatzverwaltung: Disposition Review  | Available              |
|                                         | Datensatzverwaltung: Datei Plan-Manager    | Available |
|                                         | Datensatzverwaltung: Nachweis der Entsorgung                            | Available |
|                                         | Datensatzverwaltung: Daten Satz Versionsverwaltung                         | Available |
|                                         | Datensatzverwaltung: regulatorische Datensätze                         | Im Entwicklungsrückstand |
|                                         | Datensatzverwaltung: mehrstufige Dispositions Überprüfung | Im Entwicklungsrückstand |
|                                         | Datensatzverwaltung: Verwenden von SharePoint-Syntex Klassifizierung zum Anwenden von Daten Satzbezeichnungen | Im Entwicklungsrückstand |
| **Insider-Risikomanagement**             | Kunden-Lockbox                                | Available            |
|                                         | Insider Risiko Management: Office-Indikatoren für Teams, SharePoint-Websites, e-Mail-Messaging                         | In der Entwicklung |
|                                         | Insider Risiko Management: Datendiebstahl durch Benutzer                        | In der Entwicklung |
|                                         | Insider Risiko Management: allgemeine Datenlecks                                | In der Entwicklung              |
|                                         | Insider Risikomanagement: Untersuchen von Warnungen beim Insider Risikomanagement                                   | In der Entwicklung              |
|                                         | Insider Risiko Management: Fall Dashboard, Inhalts-Explorer und Benachrichtigungsvorlagen | In der Entwicklung |
|                                         | Insider Risiko Management: Eskalation zur Untersuchung für Advanced eDiscovery | In der Entwicklung|
|                                         | Insider Risiko Management: Geräte Indikatoren für Aktivitäten unter Windows 10 Build 1809 und höher | Im Entwicklungsrückstand|
|                                         | Insider Risiko Management: Indikatoren für Sicherheitsrichtlinienverletzungen (Vorschau) | Im Entwicklungsrückstand|
|                                         | Insider Risiko Management: Indikatoren für ATP-Warnungen für Windows Defender (Vorschau) | Im Entwicklungsrückstand|
|                                         | Insider Risiko Management: Richtlinienvorlagen für Datenverluste nach Prioritäts Benutzern (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Richtlinienvorlagen für Datenverluste durch verärgerte Benutzer (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Richtlinienvorlagen für allgemeine Sicherheitsrichtlinienverletzungen (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Richtlinienvorlagen für Sicherheitsrichtlinienverletzungen nach Prioritäts Benutzern, Benutzer mit abgehender Priorität, verärgerte Benutzer (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Richtlinien Anpassung (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Export Benachrichtigungen (Vorschau) | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Prioritäts Benutzergruppen (Vorschau) | Im Entwicklungsrückstand |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Erstellen von Kunden Richtlinien, 3 vorkonfiguriert  | In der Entwicklung |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Unterstützung für Teams, Exchange und Entfernen von Microsoft Teams-Nachricht | In der Entwicklung |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Zugriffs Warnungen; Hinweis Vorlagen; Kommunikationsrichtlinien-Dashboard | In der Entwicklung  |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Eskalation zur Untersuchung für Advanced eDiscovery | In der Entwicklung |
|                                         | Kommunikation Compliance (einschließlich Aufsichtsrichtlinien): Ermitteln von Inhalten für Erwachsene | In der Entwicklung |
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
|                                         | Verwaltung des privilegierten Zugriffs                    | Im Entwicklungsrückstand |
| **Antworten auf & ermitteln**                  | Zentrale eDiscovery: in-Place-Aufbewahrung                            | Available              |
|                                         | Zentrale eDiscovery: Fallverwaltung                                 | Available              |
|                                         | Zentrale eDiscovery: Suche                                          | Available              |
|                                         | Haupt-eDiscovery: Export                                          | Available              |
|                                         | Zentrale eDiscovery: RMS-Entschlüsselung                                  | Available              |
|                                         | Zentrale eDiscovery: nativer Export                                   | Available              |
|                                         | Zentrale eDiscovery: Überwachung                                        | Available              |
|                                         | Zentrale eDiscovery: Microsoft Compliance Center erweiterte Unterstützung für das Suchen und Exportieren von Elementen in SharePoint und OneDrive für Unternehmen Papierkorb                                        | In der Entwicklung              |
|                                         | Erweiterte eDiscovery: erweiterte Verarbeitung                             | Available |
|                                         | Erweiterte eDiscovery: Depotverwaltung für Arbeits Auslastungs Zuordnung                             | Available |
|                                         | Erweiterte eDiscovery: Depotbank-Kommunikation                             | Available |
|                                         | Erweiterte eDiscovery: Dashboard                             | Available |
|                                         | Erweiterte eDiscovery: e-Mail-Threading                                 | Available |
|                                         | Advanced eDiscovery: Export (herunterladen, exportieren, zu einem anderen Überprüfungs Sätze hinzufügen)                   | Available |
|                                         | Erweiterte eDiscovery: Filterung                                          | Available |
|                                         | Erweiterte eDiscovery: rechtliche Aufbewahrung für private Channel-Nachrichten in Microsoft Teams                               | Available |
|                                         | Erweiterte eDiscovery: nahe doppelte Identifikation                 | Available |
|                                         | Erweiterte eDiscovery: Datenquellen ohne Freiheitsentzug                                         | Available |
|                                         | Erweiterte eDiscovery: nicht Office 365E Einnahme                                         | Available |
|                                         | Advanced eDiscovery: Predictive Coding                                      | Available |
|                                         | Erweiterte eDiscovery: verarbeitete Exportdatei mit lastdatei                                       | Available |
|                                         | Erweiterte eDiscovery:-Aktionen                   | Available |
|                                         | Erweiterte eDiscovery: Überprüfungs Sätze                        | Available |
|                                         | Erweiterte eDiscovery: Überprüfen der Daten (Abfrage Daten, Smarttags, Dashboards) und annotieren (redact)                                     | Available |
|                                         | Erweiterte eDiscovery: Suchbegriffs Bericht                             | Available |
|                                         | Erweiterte eDiscovery: Fehlerbehebung für einzelne Elemente                        | Available |
|                                         | Erweiterte eDiscovery: Unterstützung für PST-Export                              | Rollout |
|                                         | Erweiterte eDiscovery: Unterstützung für verknüpfte Inhalte aus OneDrive und SharePoint Online (moderne Anlagen)                              | Available |
|                                         | Erweiterte eDiscovery: Tagging                              | Available |
|                                         | Erweiterte eDiscovery: Mandanten Berichte                              | Available |
|                                         | Erweiterte eDiscovery: Designs                               | Available |
|                                         | Erweiterte eDiscovery: Viewer                              | Available |
|                                         | Erweiterte eDiscovery: jammern erweiterte eDiscovery im Microsoft Compliance Center                              | Available |
|                                         | Erweiterte eDiscovery: cjk/Double Byte-Unterstützung für Advanced eDiscovery                              | In der Entwicklung |
|                                         | Erweiterte eDiscovery: Reaktionen von Support Teams                             | In der Entwicklung |
|                                         | Erweiterte eDiscovery: Microsoft Compliance Center erweiterte Unterstützung für das Suchen und Exportieren von Elementen in SharePoint und OneDrive für Unternehmen Papierkorb                               | Im Entwicklungsrückstand |
|                                         | Grundlegende Überwachung                              | Available |
|                                         | Erweiterte Überwachung: Zugriff auf wichtige Ereignisse (beispielsweise mailitemsaccessed)                              | Available |
|                                         | Erweiterte Überwachung: erhöhte Bandbreite zur Verwaltungs Aktivitäts-API                              | Available |
|                                         | Erweiterte Überwachung: Rechtliche Aufbewahrungspflicht für Microsoft Teams-Nachrichten für private Kanäle                              | Available |
|                                         | Erweiterte Überwachung: Protokollaufbewahrung (1 Jahr)                              | Available |
|                                         | Erweiterte Überwachung: Sicherheit und Compliance Center-Verfügbarkeit                              | Available |
|                                         | Erweiterte Überwachung: längerfristige Aufbewahrung in Überwachungsprotokollen                              | Im Entwicklungsrückstand |
|                                         | Erweiterte Überwachung: e-Mail-Weiterleitung und e-Mail-Sendeereignisse                              | Im Entwicklungsrückstand |
|                                         | Erweiterte Überwachung: verarbeitete Überwachungs Einblicke                              | Im Entwicklungsrückstand |
|                                         | Erweiterte Überwachung: Suchbegriffs Ereignisse in Exchange Online und SharePoint Online                              | Im Entwicklungsrückstand |
|    **Verwaltung der Richtlinientreue**            | Microsoft 365 Security and Compliance Center                              | Available |
|                                         | Compliance-Manager (Vorschau)                                 | Rollout              |
|                                         | Microsoft Cloud App-Sicherheit                                 | Available              |
|                                         | Unterstützung von Doppelbytezeichen                                 | Im Entwicklungsrückstand              |
|    **Ökosystem**            | Graph-APIs für Advanced eDiscovery                              | In der Entwicklung |
|                                         | Erstanbieter-Daten-Konnektoren                                 | Im Entwicklungsrückstand              |
|                                         | Daten-Connectoren von Drittanbietern                                 | Im Entwicklungsrückstand              |
|                                         | Diagramm-APIs für Teams Exportieren von Daten                                 | Im Entwicklungsrückstand              |

<sup>1</sup> der Status "identifiziert" kann geändert werden, wenn Projektpläne und Prioritäten neu ausgewertet werden.<br/>

**Entscheidungspunkt** : *entscheiden Sie, ob die Konformitäts Funktionen den Anforderungen Ihrer Organisation entsprechen.*
