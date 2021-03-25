---
title: Planen von Microsoft 365 Compliance – GCC High
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Diese Anleitung gilt für IT-Profis, die Bereitstellungen von Office 365 in Us Federal Government-Entitäten oder anderen Entitäten antreibt, die Daten verarbeiten, die staatlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government – GCC High geeignet ist, um diese Anforderungen zu erfüllen.
ms.openlocfilehash: 14c92229fa5ec147ff995d0cebe991cfdce0de70
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173080"
---
# <a name="plan-for-microsoft-365-compliance--gcc-high"></a>Planen der Microsoft 365-Compliance – GCC High

Diese Anleitung gilt für IT-Profis, die Bereitstellungen von Office 365 in Us Federal Government-Entitäten oder anderen Entitäten antreibt, die Daten verarbeiten, die staatlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government – GCC High geeignet ist, um diese Anforderungen zu erfüllen.

> [!NOTE]
>Wenn Ihre Organisation die Anforderungen von Microsoft 365 Government – GCC Hohe Berechtigungsanforderungen bereits erfüllt und für das Programm beantragt und in das Programm aufgenommen wurde, können Sie die Schritte 1 und 2 überspringen und direkt zu Schritt 3 wechseln.
 
## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government--gcc-high-and-meets-eligibility-requirements"></a>Schritt 1. Bestimmen, ob Ihre Organisation Microsoft 365 Government – GCC High benötigt und die Berechtigungsanforderungen erfüllt

Die Microsoft 365 Government - GCC High-Umgebung entspricht den Anforderungen der US Government für Clouddienste. Organisationen profitieren nicht nur von den Features und Funktionen von Office 365, sondern profitieren auch von den folgenden Features, die für Microsoft 365 Government – GCC High einzigartig sind:

- Die Kundeninhalte Ihrer Organisation werden logisch von Kundeninhalten in den kommerziellen Office 365-Diensten von Microsoft getrennt.
- Der Kundeninhalt Ihrer Organisation wird in den Vereinigten Staaten gespeichert.
- Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.
- Microsoft 365 Government – GCC High entspricht den Zertifizierungen und Akkreditierungen, die für Kunden im öffentlichen Us-Sektor erforderlich sind.

Weitere Informationen zum Microsoft 365 Government – GCC High-Angebot für Us Government-Kunden finden Sie unter [Office 365](https://products.office.com/government/compare-office-365-government-plans)Government-Pläne, einschließlich Berechtigungsanforderungen.

In [der Office 365 US Government-Dienstbeschreibung](../../office-365-platform-service-description/office-365-us-government/office-365-us-government.md) werden die Vorteile der Plattform beschrieben, die sich auf die Einhaltung von Complianceanforderungen in den USA zentriert haben.

> [!TIP]
> Möglicherweise möchten Sie die Tabellen mit Informationen in der Dienstbeschreibung in eine Excel-Arbeitsmappe übertragen und zwei Spalten hinzufügen: Relevant für meine Organisation **Y/N** und Erfüllt die Anforderungen meiner Organisation **Y/N**. Anschließend können Sie diese Liste mit Ihren Kollegen überprüfen, um zu bestätigen, dass dieser Dienst den Anforderungen Ihrer Organisation entspricht.

**Entscheidungspunkte**:<br/>
- *Entscheiden Sie, ob Microsoft 365 Government – GCC-High für Ihre Organisation geeignet ist.*
- *Vergewissern Sie sich, dass Ihre Organisation die Berechtigungsanforderungen erfüllt.*

> [!NOTE]
> Microsoft 365 Government – GCC High ist nur in den USA verfügbar. Kunden außerhalb der USA können aus einer Reihe von [Office 365 Government-Plänen auswählen.](https://products.office.com/government/compare-office-365-government-plans)

## <a name="step-2-apply-for-microsoft-365-government--gcc-high"></a>Schritt 2. Bewerben Sie sich für Microsoft 365 Government – GCC-High

Nachdem Sie entschieden haben, dass dieser Dienst für Ihre Organisation richtig ist, starten Sie den Prozess der [Anwendung für diesen Dienst.](https://products.office.com/government/eligibility-validation)
 
## <a name="step-3-understand-microsoft-365-government--gcc-high-default-security-settings"></a>Schritt 3. Verstehen von Microsoft 365 Government – GCC-High Standardsicherheitseinstellungen

Es wird empfohlen, sich zeit zu nehmen, ihre Administrator- und Sicherheitseinstellungen sorgfältig zu überprüfen, bevor Sie sie ändern, und die Auswirkungen auf die Compliance zu berücksichtigen, bevor Sie Änderungen an den Standardsicherheitseinstellungen vornehmen.

**Entscheidungspunkt**: Entscheiden Sie, ob Sie eine der Standardmäßigen *Microsoft 365 Government -GCC-High-Sicherheitseinstellungen* ändern, um zunächst die Auswirkungen etwaiger Änderungen zu verstehen.

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc-highsup1sup"></a>Schritt 4. Informationen zu den derzeit nicht verfügbaren oder deaktivierten Funktionen in Microsoft 365 Government – GCC-High<sup>1</sup>

Um die Anforderungen unserer Government Cloud-Kunden zu erfüllen, gibt es einige Unterschiede zwischen Microsoft 365 Government – GCC-High und Unternehmensplänen. In der folgenden Tabelle finden Sie Informationen zu den verfügbaren Features. Hier [finden](https://www.microsoft.com/microsoft-365/roadmap?filters=GCC%2CGCC%20High%2CDoD%2CMicrosoft%20Information%20Protection%2CMicrosoft%20Compliance%20center%2COffice%20365%20Data%20Loss%20Prevention%2CSecurity%20and%20Compliance%20center#owRoadmapMainContent) Sie die neuesten Kompatibilitätsproduktupdates, die in der Microsoft 365-Roadmap veröffentlicht wurden.<br><br>

| Bereich                                    | Feature                                         | GCC-Status             |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Schutz von Daten**              | Client und Scanner für einheitliche Bezeichnungen         | Available              |
|                                         | Genaue Übereinstimmung der Daten          | Available              |
|                                         | Automatische Klassifizierung und Bezeichnung für Exchange Online, SharePoint Online und OneDrive                      | Rollout              |
|                                         | Automatische Klassifizierung und Bezeichnung für Office-Apps (Word, Excel, PowerPoint, Outlook) über Web, Android, iOS, Windows und Mac            | In der Entwicklung |
|                                         | Automatische Klassifizierung und Bezeichnung für Office-Clients (Mobile)                                       | On Engineering Backlog              |
|                                         | Automatische Klassifizierung und Bezeichnung für Teams                            | On Engineering Backlog |
|                                         | Analyse der Datenklassifizierung: Übersicht und Inhalts-Explorer                            | On Engineering Backlog |
|                                         | Analytics: Machine Learning-Klassifizierungen mit automatischer Bezeichnung auf Dienstseite                           | On Engineering Backlog  |
|                                         | Analytics: Machine Learning-Klassifizierungen mit automatischer Bezeichnung auf Office-Apps/-Clientseite                           | On Engineering Backlog  |
|                                         | Grundlegende Office 365-Nachrichtenverschlüsselung (E3)                            | Available              |
|                                         | Erweiterte Office 365-Nachrichtenverschlüsselung (E5)  | Available              |
|                                         | Kundenschlüssel für Office 365    | Available |
|                                         | Bring Your Own Key (BYOK) für den Lebenszyklus der Bereitstellung von kundenver verwalteten Schlüsseln                            | Available |
|                                         | Hold Your Own Key (HYOK), der Azure Information Protection und Active Directory (AD) Rights Management für stark regulierte Szenarien umfasst (Vorschau)                         | Available |
|                                         | Verschlüsselung mit Doppelschlüssel                           | Available |
|                                         | Verschlüsselung: Gemeinsamen Dokumenterstellung für verschlüsselte Dokumente mithilfe von WXP-Web-Apps         | On Engineering Backlog |
|                                         | Verhinderung von Datenverlust (Data Loss Prevention, DLP) für Dateien und E-Mails         | Available |
|                                         | Chat- und Kanalunterhaltungen von DLP für Teams | On Engineering Backlog |
|                                         | DLP-Endpunkt | On Engineering Backlog |
| **Informationsgovernance** | Information Governance: E-Mail-Archivierung                                       | Available              |
|                                         | Informationsverwaltung: Erhaltungssperre          | Available              |
|                                         | Information Governance: Importieren von PST                      | Available              |
|                                         | Information Governance: Manuelle Aufbewahrungsbezeichnungen ohne Datensatz            | Available |
|                                         | Information Governance: Standardaufbewahrungsbezeichnungen für SharePoint/OneDrive for #A0, Ordner und Dokumentmappen; #A0 und Office 365-Gruppen | Available              |
|                                         | Information Governance: Aufbewahrungsrichtlinien für die gesamte Organisation; bestimmte Speicherorte oder Benutzer; automatisch basierend auf einer bestimmten Bedingung (z. B. Schlüsselwörter oder vertrauliche Informationen); und basierend auf einem Ereignis                                       | Available              |
|                                         | Information Governance: Aufbewahrungsrichtlinien für Teams                            | On Engineering Backlog |
|                                         | Information Governance: Aufbewahrungsbezeichnungen mithilfe der SharePoint-Syntex-Klassifizierung                            | On Engineering Backlog |
|                                         | Information Governance: Aufbewahrungsrichtlinien mit trainierbaren Klassifizierungen                            | On Engineering Backlog |
|                                         | Information Governance: Aufbewahrungsrichtlinien für die Aufzeichnung von Teams-Besprechungen                            | On Engineering Backlog |
|                                         | Information Governance: Aufbewahrungsrichtlinien für Yammer                            | On Engineering Backlog |
|                                         | Datensatzverwaltung: Manuelle Klassifizierung für Datensatzbeschriftungen                           | Available              |
|                                         | Datensatzverwaltung: Standarddatensatzbezeichnungen für SharePoint, OneDrive for #A0, Ordner und Dokumentmappen; und Office 365-Gruppen                              | Available              |
|                                         | Datensatzverwaltung: Automatische Datensatzrichtlinien basierend auf bestimmten Bedingungen (z. B. Schlüsselwörter oder vertrauliche Informationen); und basierend auf einem Ereignis                            | Available              |
|                                         | Datensatzverwaltung: Dispositionsüberprüfung  | Available              |
|                                         | Datensatzverwaltung: Dateiplan-Manager    | Available |
|                                         | Datensatzverwaltung: Nachweis der Entsorgung                            | Available |
|                                         | Datensatzverwaltung: Datensatzversionsverwaltung                         | Available |
|                                         | Datensatzverwaltung: Behördliche Datensätze                         | On Engineering Backlog |
|                                         | Datensatzverwaltung: Mehrstufige Dispositionsüberprüfung | On Engineering Backlog |
|                                         | Datensatzverwaltung: Verwenden der SharePoint-Syntex-Klassifizierung zum Anwenden von Datensatzbezeichnungen | On Engineering Backlog |
| **Insider-Risikomanagement**             | Kunden-Lockbox                                | Available            |
|                                         | Insider Risk Management: Office-Indikatoren für Teams, SharePoint-Websites, E-Mail-Nachrichten                         | In der Entwicklung |
|                                         | Insider Risk Management: Datendiebstahl durch ausscheidende Benutzer                        | In der Entwicklung |
|                                         | Insider Risk Management: Allgemeine Datenlecks                                | In der Entwicklung              |
|                                         | Insider Risk Management: Untersuchen von Insider-Risikomanagementwarnungen                                   | In der Entwicklung              |
|                                         | Insider Risk Management: Falldashboard, Inhalts-Explorer und Benachrichtigungsvorlagen | In der Entwicklung |
|                                         | Insider Risk Management: Eskalieren der Untersuchung für Advanced eDiscovery | In der Entwicklung|
|                                         | Insider Risk Management: Geräteindikatoren für Aktivitäten unter Windows 10 Build 1809 und höher | On Engineering Backlog|
|                                         | Insider Risk Management: Indikatoren für Sicherheitsrichtlinienverletzung (Vorschau) | On Engineering Backlog|
|                                         | Insider Risk Management: Indikatoren für Microsoft Defender for Endpoint-Warnungen (Vorschau) | On Engineering Backlog|
|                                         | Insider Risk Management: Richtlinienvorlagen für Datenlecks nach Prioritätsbenutzern (Vorschau) | On Engineering Backlog |
|                                         | Insider Risk Management: Richtlinienvorlagen für Datenlecks von unzufriedenen Benutzern (Vorschau) | On Engineering Backlog |
|                                         | Insider Risk Management: Richtlinienvorlagen für allgemeine Sicherheitsrichtlinienverletzungen (Vorschau) | On Engineering Backlog |
|                                         | Insider Risk Management: Richtlinienvorlagen für Sicherheitsrichtlinienverletzungen durch Prioritätsbenutzer, ausscheidende Benutzer, unzufriedene Benutzer (Vorschau) | On Engineering Backlog |
|                                         | Insider Risk Management: Policy customization (preview) | On Engineering Backlog |
|                                         | Insider Risk Management: Export alerts (preview) | On Engineering Backlog |
|                                         | Insider Risk Management: Priority user groups (preview) | On Engineering Backlog |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Erstellen von Kundenrichtlinien, 3 vorkonfiguriert  | In der Entwicklung |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Unterstützung für Teams, Exchange und Entfernen von Teams-Nachrichten | In der Entwicklung |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Zugriffswarnungen; Benachrichtigungsvorlagen; Kommunikationsrichtliniendashboard | In der Entwicklung  |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Eskalieren der Untersuchung für Advanced eDiscovery | In der Entwicklung |
|                                         | Kommunikationskonformität (inkl. Aufsichtsrichtlinien): Erkennen von Inhalten für Erwachsene | In der Entwicklung |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Erkennt wiederholte Verhaltensverletzungen im Laufe der Zeit | Rollout |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Unterstützung für differenziertere Berechtigungen | Rollout |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Analysieren von Teams-Chatdaten von Benutzern mit einem postfachvoreingespeicherten Postfach | Rollout |
|                                         | Kommunikationskonformität (inkl. Aufsichtsrichtlinien): Vorlage für Interessenkonflikte | On Engineering Backlog |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Möglichkeit, E-Mail-Signatur oder Haftungsausschluss zu ignorieren | On Engineering Backlog |
|                                         | Kommunikationskonformität (inkl. Aufsichtsrichtlinien): Hand-off für Insider-Risikomanagement | On Engineering Backlog |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Überprüfung der Richtlinienintegität und Möglichkeit zum Anhalten von Richtlinien | On Engineering Backlog |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Übersetzen von Integritätsinhalten während der Untersuchung | On Engineering Backlog |
|                                         | Kommunikationskonformität (einschließlich Aufsichtsrichtlinien): Burnout- und Suiziderkennung | On Engineering Backlog |
|                                         | Informationsbarrieren | On Engineering Backlog |
|                                         | Verwaltung privilegierter Zugriffe                    | On Engineering Backlog |
| **Ermitteln & Antworten**                  | Core eDiscovery: In-Place-Erhaltung                            | Available              |
|                                         | Kern-eDiscovery: Fallverwaltung                                 | Available              |
|                                         | Core eDiscovery: Search                                          | Available              |
|                                         | Core eDiscovery: Export                                          | Available              |
|                                         | Kern-eDiscovery: RMS-Entschlüsselung                                  | Available              |
|                                         | Kern-eDiscovery: Nativer Export                                   | Available              |
|                                         | Kern-eDiscovery: Überwachung                                        | Available              |
|                                         | Kern-eDiscovery: Microsoft Compliance Center erweiterte Unterstützung für die Suche und den Export von Elementen in SharePoint und OneDrive for Business-Papierkorb                                        | In der Entwicklung              |
|                                         | Advanced eDiscovery: Erweiterte Verarbeitung                             | Available |
|                                         | Advanced eDiscovery: Zuordnung von Verwahrer zu Arbeitsauslastung                             | Available |
|                                         | Advanced eDiscovery: Custodian Communications                             | Available |
|                                         | Advanced eDiscovery: Dashboard                             | Available |
|                                         | Advanced eDiscovery: E-Mail-Threading                                 | Available |
|                                         | Advanced eDiscovery: Export (download, export, add to another review set)                   | Available |
|                                         | Advanced eDiscovery: Filterung                                          | Available |
|                                         | Advanced eDiscovery: Rechtlicher Halteschutz für Nachrichten privater Teams-Kanäle                               | Available |
|                                         | Advanced eDiscovery: Beinahe doppelte Identifizierung                 | Available |
|                                         | Advanced eDiscovery: Nicht verwahrte Datenquellen                                         | Available |
|                                         | Advanced eDiscovery: Nicht-Office 365-Aufnahme                                         | Available |
|                                         | Advanced eDiscovery: Vorhersagecodierung                                      | Available |
|                                         | Advanced eDiscovery: Export mit Ladedatei verarbeitet                                       | Available |
|                                         | Advanced eDiscovery: Redactions                   | Available |
|                                         | Advanced eDiscovery: Überprüfen von Sätzen                        | Available |
|                                         | Advanced eDiscovery: Überprüfen von Daten (Abfragedaten, Smarttags, Dashboard) und Anmerkungen (Redact)                                     | Available |
|                                         | Advanced eDiscovery: Suchbegriffsbericht                             | Available |
|                                         | Advanced eDiscovery: Behebung von Fehlern einzelner Elemente                        | Available |
|                                         | Advanced eDiscovery: Unterstützt den PST-Export                              | Rollout |
|                                         | Advanced eDiscovery: Unterstützung verknüpfter Inhalte von OneDrive und SharePoint Online (moderne Anlagen)                              | Available |
|                                         | Advanced eDiscovery: Tagging                              | Available |
|                                         | Advanced eDiscovery: Mandantenberichte                              | Available |
|                                         | Advanced eDiscovery: Designs                               | Available |
|                                         | Advanced eDiscovery: Viewers                              | Available |
|                                         | Advanced eDiscovery: Yammer Advanced eDiscovery im Microsoft Compliance Center                              | Available |
|                                         | Advanced eDiscovery: CJK/Double-Byteunterstützung für Advanced eDiscovery                              | In der Entwicklung |
|                                         | Advanced eDiscovery: Unterstützung von Teams-Reaktionen                             | In der Entwicklung |
|                                         | Advanced eDiscovery: Microsoft Compliance Center erweiterte Unterstützung für die Suche und den Export von Elementen in SharePoint und OneDrive for Business-Papierkorb                               | On Engineering Backlog |
|                                         | Grundlegende Überwachung                              | Available |
|                                         | Erweiterte Überwachung: Zugriff auf wichtige Ereignisse (z. B. mailitemsaccessed)                              | Available |
|                                         | Erweiterte Überwachung: Erhöhte Bandbreite für die Verwaltungsaktivitäts-API                              | Available |
|                                         | Erweiterte Überwachung: Rechtliches Haltehalten für Nachrichten privater Teams-Kanäle                              | Available |
|                                         | Erweiterte Überwachung: Protokollaufbewahrung (1 Jahr)                              | Rollout |
|                                         | Erweiterte Überwachung: Verfügbarkeit von Security and Compliance Center                              | Available |
|                                         | Erweiterte Überwachung: Langfristige Aufbewahrung in Überwachungsprotokollen (10 Jahre)                              | On Engineering Backlog |
|                                         | Erweiterte Überwachung: E-Mail-Weiterleitungs- und E-Mail-Sendeereignisse                              | On Engineering Backlog |
|                                         | Erweiterte Überwachung: Verarbeitete Überwachungseinblicke                              | On Engineering Backlog |
|                                         | Erweiterte Überwachung: Suchbegriffsereignisse in Exchange Online und SharePoint Online                              | On Engineering Backlog |
|    **Verwaltung der Richtlinientreue**            | Microsoft 365 Security and Compliance Center                              | Available |
|                                         | Compliance-Manager                                 | Available              |
|                                         | Microsoft Cloud App Security                                 | Available              |
|                                         | Unterstützung für Doppelte Bytezeichen                                 | On Engineering Backlog              |
|    **Ökosystem**            | Graph-APIs für Advanced eDiscovery                              | In der Entwicklung |
|                                         | First-Party-Datenconnectors                                 | On Engineering Backlog              |
|                                         | Daten-Connectoren von Drittanbietern                                 | On Engineering Backlog              |
|                                         | Graph-APIs für Teams exportieren Daten                                 | On Engineering Backlog              |

<sup>1</sup> Der identifizierte Status kann geändert werden, wenn Projektpläne und Prioritäten neu bewertet werden.<br/>

**Entscheidungspunkt:** *Entscheiden Sie, ob die Compliancefeatures den Anforderungen Ihrer Organisation entsprechen.*