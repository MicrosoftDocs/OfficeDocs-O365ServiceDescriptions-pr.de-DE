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
ms.openlocfilehash: aca09e0e7768228f39e942fbeffba1bae84cb77f
ms.sourcegitcommit: 9794350861e41d80980ecf6b9000a730b5564988
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/29/2020
ms.locfileid: "48793652"
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
> Möglicherweise möchten Sie die Tabellen mit Informationen in der Dienstbeschreibung in eine Excel-Arbeitsmappe übertragen und zwei Spalten hinzufügen: **relevant für meine Organisation y/n** und **den Anforderungen meiner Organisation y/n entsprechen** . Anschließend können Sie diese Liste mit ihren Kollegen überprüfen, um zu bestätigen, dass dieser Dienst die Anforderungen Ihrer Organisation erfüllt.

**Entscheidungspunkte** :<br/>
- *Entscheiden Sie, ob das Microsoft 365 Government-DoD für Ihre Organisation geeignet ist.*
- *Stellen Sie sicher, dass Ihre Organisation die Berechtigungsanforderungen erfüllt.*

> [!NOTE]
> Microsoft 365 Government-DoD ist nur in den Vereinigten Staaten verfügbar. Kunden außerhalb der US-Regierung können aus einer Reihe von [Office 365 Government-Plänen](https://products.office.com/government/compare-office-365-government-plans)wählen.

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Schritt 2: Beantragen von Microsoft 365 Government-DoD

Nachdem Sie entschieden haben, dass dieser Dienst für Ihre Organisation geeignet ist, starten Sie den Prozess der [Beantragung dieses Diensts](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>Schritt 3: Grundlegendes zu Microsoft 365-Standardsicherheitseinstellungen für das Government-DoD

Es wird empfohlen, dass Sie sich Zeit nehmen, um die Administrator-und Sicherheitseinstellungen sorgfältig zu überprüfen, bevor Sie Sie ändern und die Auswirkungen auf die Kompatibilität berücksichtigen, bevor Sie Änderungen an den Standardsicherheitseinstellungen vornehmen.

**Entscheidungspunkt** : *entscheiden Sie, ob Sie die Standardsicherheitseinstellungen von Microsoft 365 Government-DoD ändern, um zunächst die Auswirkungen von Änderungen zu verstehen, die Sie möglicherweise vornehmen.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dodsup1sup"></a>Schritt 4. Verstehen, welche Funktionen derzeit in Microsoft 365 Government – DoD<sup>1</sup> standardmäßig nicht verfügbar oder deaktiviert sind

Um die Anforderungen unserer Government Cloud-Kunden zu erfüllen, gibt es einige Unterschiede zwischen Microsoft 365 Government-DoD und Enterprise-Plänen. In der folgenden Tabelle finden Sie Informationen zu verfügbaren Features.<br><br>

| Bereich                                    | Feature                                         | GCC-Status             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Schutz von Daten**              | Unified Labeling-Client und-Scanner         | Available              |
|                                         | Exakte Datenübereinstimmung          | Available               |
|                                         | Automatische Klassifizierung und Beschriftung für Exchange Online, SharePoint Online, OneDrive                      | Rollout              |
|                                         | Automatische Klassifizierung und Kennzeichnung für Office-Apps (Word, Excel, PowerPoint, Outlook) über das Internet, Android, Ios, Windows und Mac            | In der Entwicklung |
|                                         | Klassifizierungs gesteuerte Richtlinien mit Office 365 Gruppen |  Rollout              |
|                                         | Automatische Klassifizierung und Kennzeichnung für mobile Geräte                                       | Im Entwicklungsrückstand              |
|                                         | Automatische Klassifizierung und Kennzeichnung für Teams                            | Im Entwicklungsrückstand |
|                                         | Datenklassifizierung: Übersicht und Inhalts Aktivitäts-Explorer                            | Im Entwicklungsrückstand |
|                                         | Maschinelle Schulungs Klassifizierungen mit automatischer Kennzeichnung                           | Im Entwicklungsrückstand  |
|                                         | Grundlegende Office 365 Nachrichtenverschlüsselung (E3)                            | Available              |
|                                         | Erweiterte Office 365 Nachrichtenverschlüsselung (E5)  | Available              |
|                                         | Kundenschlüssel für Office 365    | Available |
|                                         | Mitbringen eines eigenen Schlüssels (BYOK) für den Lebenszyklus von Kunden verwalteter Schlüssel Bereitstellung                            | Available |
|                                         | Halten Sie Ihren eigenen Schlüssel (Hyok), der sich über Azure Information Protection-und Active Directory (AD)-Rechteverwaltung für stark regulierte Szenarien erstreckt (Vorschau)                         | Available |
|                                         | Verschlüsselung mit Doppelschlüssel                           | In der Entwicklung |
|                                         | Verhinderung von Datenverlust (DLP) für Dateien und e-Mail         | Available |
|                                         | Verhinderung von Datenverlust für Chat-und Kanal Unterhaltungen in Teams         | Im Entwicklungsrückstand |
|                                         | Endpunkt der Verhinderung von Datenverlust | Im Entwicklungsrückstand |
| **Informationsgovernance** | Information Governance: e-Mail-Archivierung                                       | Available              |
|                                         | Information Governance: Aufbewahrungs Sperre          | Available              |
|                                         | Information Governance: Importieren von PST-Dateien                      | Available              |
|                                         | Information Governance: manuelle Aufbewahrungs Bezeichnungen, die nicht aufgezeichnet werden            | Available |
|                                         | Information Governance: standardmäßige Aufbewahrungs Bezeichnungen für SharePoint/OneDrive für Unternehmen-Bibliotheken,-Ordner und-Dokumentenmappen; Exchange-Posteingänge; und Office 365 Gruppen | Available              |
|                                         | Information Governance: Aufbewahrungsrichtlinien für die gesamte Organisation; bestimmte Standorte oder Benutzer; automatisch basierend auf einer bestimmten Bedingung (beispielsweise Schlüsselwörter oder vertrauliche Informationen); und basierend auf einem Ereignis                                       | Available              |
|                                         | Information Governance: Aufbewahrungs Bezeichnungen mithilfe der SharePoint-Syntex Klassifizierung                            | Im Entwicklungsrückstand |
|                                         | Information Governance: Aufbewahrungsrichtlinien mit Schulungs Klassifizierer                            | Im Entwicklungsrückstand |
|                                         | Information Governance: Aufbewahrungsrichtlinien für jammern und Teams                           | Im Entwicklungsrückstand              |
|                                         | Datensatzverwaltung: manuelle Klassifizierung für Daten Satzbezeichnungen                              | Available              |
|                                         | Datensatzverwaltung: standardmäßige Daten Satzbezeichnungen für SharePoint, OneDrive für Unternehmen Bibliotheken, Ordner und Dokumentenmappen; und Office 365 Gruppen                            | Available              |
|                                         | Datensatzverwaltung: automatische Datensatzrichtlinien basierend auf bestimmten Bedingungen (beispielsweise Schlüsselwörter oder vertrauliche Informationen); und basierend auf einem Ereignis  | Available              |
|                                         | Datensatzverwaltung: Disposition Review    | Available |
|                                         | Datensatzverwaltung: Datei Plan-Manager                            | Available |
|                                         | Datensatzverwaltung: Nachweis der Entsorgung                         | Available |
|                                         | Datensatzverwaltung: Daten Satz Versionsverwaltung                           | Available |
|                                         | Datensatzverwaltung: regulatorische Datensätze | Im Entwicklungsrückstand |
|                                         | Datensatzverwaltung: Durchsetzung von Lizenzen | Im Entwicklungsrückstand |
|                                         | Datensatzverwaltung: mehrstufige Dispositions Überprüfung | Im Entwicklungsrückstand |
|                                         | Datensatzverwaltung: Bezeichnungs Aktivitäts-Explorer         | Im Entwicklungsrückstand |
|                                         | Datensatzverwaltung: Auszubildende Klassifizierer         | Im Entwicklungsrückstand |
| **Insider-Risikomanagement**             | Kunden-Lockbox                                | Available            |
|                                         | Insider Risiko Management: Office-Indikatoren für Teams, SharePoint-Websites, e-Mail-Messaging                         | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Datendiebstahl durch Benutzer                        | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: allgemeine Datenlecks                                | Im Entwicklungsrückstand              |
|                                         | Insider Risikomanagement: Untersuchen von Warnungen beim Insider Risikomanagement                                   | Im Entwicklungsrückstand              |
|                                         | Insider Risikomanagement: Fall Dashboard, Inhalts-Explorer und Benachrichtigungsvorlagen | Im Entwicklungsrückstand |
|                                         | Insider Risiko Management: Eskalation zur Untersuchung für Advanced eDiscovery |Im Entwicklungsrückstand|
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
|                                         | Informationsbarrieren | Im Entwicklungsrückstand |
|                                         | Privileged Access Management                    | Im Entwicklungsrückstand |
| **Antworten auf & ermitteln**                  | Zentrale eDiscovery: in-Place-Aufbewahrung                            | Available              |
|                                         | Zentrale eDiscovery: Fallverwaltung                                 | Available              |
|                                         | Zentrale eDiscovery: Suche                                          | Available              |
|                                         | Haupt-eDiscovery: Export                                          | Available              |
|                                         | Zentrale eDiscovery: RMS-Entschlüsselung                                  | Available              |
|                                         | Zentrale eDiscovery: nativer Export                                   | Available              |
|                                         | Zentrale eDiscovery: Überwachung                                        | Available              |
|                                         | Zentrale eDiscovery: Microsoft Compliance Center erweiterte Unterstützung für das Suchen und Exportieren von Elementen in SharePoint und OneDrive für Unternehmen Papierkorb                             | In der Entwicklung |
|                                         | Erweiterte eDiscovery: erweiterte Verarbeitung                                 | Rollout |
|                                         | Erweiterte eDiscovery: Dashboard                   | Rollout |
|                                         | Erweiterte eDiscovery: e-Mail-Threading                                          | Rollout |
|                                         | Advanced eDiscovery: Export (herunterladen, exportieren, zu einem anderen Überprüfungs Sätze hinzufügen)                               | Rollout |
|                                         | Erweiterte eDiscovery: Filterung                 | Rollout |
|                                         | Erweiterte eDiscovery: rechtliche Aufbewahrung für private Channel-Nachrichten in Microsoft Teams                                         | Rollout |
|                                         | Erweiterte eDiscovery: nahe doppelte Identifikation                                         | Rollout |
|                                         | Erweiterte eDiscovery: Datenquellen ohne Freiheitsentzug                                      | Rollout |
|                                         | Advanced eDiscovery: Predictive Coding                                       | Rollout |
|                                         | Erweiterte eDiscovery: verarbeitete Exportdatei mit lastdatei                   | Rollout |
|                                         | Erweiterte eDiscovery:-Aktionen                        | Rollout |
|                                         | Erweiterte eDiscovery: Überprüfungs Sätze                                     | Rollout |
|                                         | Erweiterte eDiscovery: Überprüfen von Daten (Abfrage Daten, Smarttags, Dashboards und Anmerkungen (redact)                             | Rollout |
|                                         | Erweiterte eDiscovery: Suchbegriffs Bericht                        | Rollout |
|                                         | Erweiterte eDiscovery: Tagging                              | Rollout |
|                                         | Erweiterte eDiscovery: Mandanten Berichte                              | Rollout |
|                                         | Erweiterte eDiscovery: Viewer                              | Rollout |
|                                         | Erweiterte eDiscovery: jammern erweiterte eDiscovery im Microsoft Compliance Center                              | Rollout |
|                                         | Erweiterte eDiscovery: cjk/Double Byte Character-Unterstützung                              | Im Entwicklungsrückstand |
|                                         | Erweiterte eDiscovery: Graph-APIs                              | Im Entwicklungsrückstand |
|                                         | Erweiterte eDiscovery: Microsoft Compliance Center erweiterte Unterstützung für das Suchen und Exportieren von Elementen in SharePoint und OneDrive für Unternehmen Papierkorb                              | Im Entwicklungsrückstand |
|                                         | Erweiterte eDiscovery: nicht Office 365E Einnahme und Verarbeitung (beispielsweise OCR)                              | Im Entwicklungsrückstand |
|                                         | Erweiterte eDiscovery: Reaktionen von Support Teams                              | Im Entwicklungsrückstand |
|                                         | Grundlegende Überwachung                              | Available |
|                                         | Erweiterte Überwachung: Sicherheit und Compliance Center-Verfügbarkeit                              | Available |
|                                         | Erweiterte Überwachung: Zugriff auf wichtige Ereignisse (beispielsweise mailitemsaccessed)                              | Rollout |
|                                         | Erweiterte Überwachung: erhöhte Bandbreite zur Verwaltungs Aktivitäts-API                               | Rollout |
|                                         | Erweiterte Überwachung: Protokollaufbewahrung (1 Jahr)                              | Rollout |
|                                         | Erweiterte Überwachung: längerfristige Aufbewahrung in Überwachungsprotokollen                              | Im Entwicklungsrückstand |
|                                         | Erweiterte Überwachung: e-Mail-Weiterleitung und e-Mail-Sendeereignisse                              | Im Entwicklungsrückstand |
|                                         | Erweiterte Überwachung: verarbeitete Überwachungs Einblicke                              | Im Entwicklungsrückstand |
|                                         | Erweiterte Überwachung: Suchbegriffs Ereignisse in Exchange Online und SharePoint Online                              | Im Entwicklungsrückstand |
|    **Verwaltung der Richtlinientreue**            | Microsoft 365 Security and Compliance Center                              | Available |
|                                         | Microsoft Cloud App-Sicherheit                              | Im Entwicklungsrückstand |
|                                         | Compliance-Manager (Vorschau)                              | Im Entwicklungsrückstand |
|                                         | Unterstützung von Doppelbytezeichen                              | Im Entwicklungsrückstand |

<sup>1</sup> der Status "identifiziert" kann geändert werden, wenn Projektpläne und Prioritäten neu ausgewertet werden.<br/>
<sup>2</sup> die manuelle Anwendung von Bezeichnungen erfordert den [Azure Information Protection (AIP)-Client, Version 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Entscheidungspunkt** : *entscheiden Sie, ob die Konformitäts Funktionen den Anforderungen Ihrer Organisation entsprechen.*
