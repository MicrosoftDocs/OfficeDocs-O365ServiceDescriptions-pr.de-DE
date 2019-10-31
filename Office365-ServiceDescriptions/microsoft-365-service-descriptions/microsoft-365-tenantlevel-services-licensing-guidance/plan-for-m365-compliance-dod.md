---
title: Planen von Microsoft 365-Compliance-DoD-Bereitstellungen
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ROBOTS: NOINDEX, NOFOLLOW
description: Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in US-Bundesbehörden oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, in denen die Verwendung von Microsoft 365 Government – DoD geeignet ist, Diese Anforderungen erfüllen.
ms.openlocfilehash: 27f51c80b4d19f2ca42f0dc7f8b25c93d39dd5ca
ms.sourcegitcommit: f69656f34dcb4f4e9a5857d8c4236084c94a05b1
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/31/2019
ms.locfileid: "37890492"
---
# <a name="plan-for-microsoft-365-compliance---dod-deployments"></a>Planen von Microsoft 365-Compliance-DoD-Bereitstellungen

Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in US-Bundesbehörden oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, in denen die Verwendung von Microsoft 365 Government – DoD geeignet ist, Diese Anforderungen erfüllen.

> [!NOTE]
> Wenn Ihre Organisation bereits die Zulassungsvoraussetzungen für das Microsoft 365 Government – DoD erfüllt und in das Programm übernommen und akzeptiert wurde, können Sie die Schritte 1 und 2 überspringen und direkt zu Schritt 3 wechseln.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---dod-and-meets-eligibility-requirements"></a>Schritt 1: Ermitteln, ob Ihre Organisation Microsoft 365 Government-DoD benötigt und die Zulassungsvoraussetzungen erfüllt

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

## <a name="step-2-apply-for-microsoft-365-government---dod"></a>Schritt 2: Beantragen von Microsoft 365 Government-DoD

Nachdem Sie entschieden haben, dass dieser Dienst für Ihre Organisation geeignet ist, starten Sie den Prozess der [Beantragung dieses Diensts](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---dod-default-security-settings"></a>SCHRITT 3: Grundlegendes zu Microsoft 365-Standardsicherheitseinstellungen für das Government-DoD

Es wird empfohlen, dass Sie sich Zeit nehmen, um die Administrator-und Sicherheitseinstellungen sorgfältig zu überprüfen, bevor Sie Sie ändern und die Auswirkungen auf die Kompatibilität berücksichtigen, bevor Sie Änderungen an den Standardsicherheitseinstellungen vornehmen.

**Entscheidungspunkt**: *entscheiden Sie, ob Sie die Standardsicherheitseinstellungen von Microsoft 365 Government-DoD ändern, um zunächst die Auswirkungen von Änderungen zu verstehen, die Sie möglicherweise vornehmen.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--dod"></a>Schritt 4: Verstehen, welche Funktionen derzeit in Microsoft 365 Government – DoD standardmäßig nicht verfügbar oder deaktiviert sind

Um die Anforderungen unserer Government Cloud-Kunden zu erfüllen, gibt es einige Unterschiede zwischen Microsoft 365 Government-DoD und Enterprise-Plänen. In der folgenden Tabelle finden Sie Informationen zu verfügbaren Features.


|         |Feature  |DoD-Status  |
|---------|---------|---------|
|**Informationsschutz #a0 Steuerung** | Archivierung                                      |  Available             |
|                                        |Manuelle Bezeichnungen und Richtlinien                      |  Available             |
|                                        |Automatische Anwendung von Beschriftungen                      | Im Entwicklungsrückstand |
|                                        |Bezeichnungen basierend auf vertraulichen Datentypen            | Im Entwicklungsrückstand |
|                                        |Bezeichnungen und zugeordnete Richtlinien basierend auf Abfragen | Im Entwicklungsrückstand |
|                                        |Dateiplan                                       | Im Entwicklungsrückstand |
|                                        |Empfohlene Richtlinien                            | Im Entwicklungsrückstand |
|                                        |Intelligente Importfilter                            | Im Entwicklungsrückstand |  
|                                        |Ereignisbasierte Aufbewahrung                           | Im Entwicklungsrückstand |
|                                        |Dispositions Überprüfung                              | Im Entwicklungsrückstand |
|                                        |Informationsbarrieren                            | Available              |
|                                        |Verhinderung von Datenverlust (DLP) für Dateien und e-Mail  | Available              |
|                                        |DLP für Microsoft Teams-Chat und Kanal Unterhaltungen    | Im Entwicklungsrückstand |
|**Insider Risikomanagement**             |Erweiterte Nachrichtenverschlüsselung                     | Available              |
|                                        |Kommunikation Compliance                        | Im Entwicklungsrückstand |
|                                        |Kunden-Lockbox                                | Available              |
|                                        |Kundenschlüssel                                    | Available              |
|                                        |Privileged Access Management                    | Im Entwicklungsrückstand |
|**Antworten auf #a0 ermitteln**                  |In-Place-Reservierung                            | Available              |
|                                        |Fallverwaltung                                 | Available              |
|                                        |Suche                                          | Available              |
|                                        |Exportieren                                          | Available              |
|                                        |RMS-Entschlüsselung                                  | Available              |
|                                        |Nativer Export                                   | Available              |
|                                        |Erweiterte Verarbeitung                             | Im Entwicklungsrückstand |
|                                        |E-Mail-Threading                                 | Im Entwicklungsrückstand |
|                                        |Nahe doppelte Identifikation                   | Im Entwicklungsrückstand |
|                                        |Designs                                          | Im Entwicklungsrückstand |
|                                        |Prädiktive Codierung                               | Im Entwicklungsrückstand |
|                                        |Verarbeitete Exportdatei mit Ladedatei                 | Im Entwicklungsrückstand |
|                                        |Kategorien                                         | Im Entwicklungsrückstand |
|                                        |Anzeigende Benutzer                                         | Im Entwicklungsrückstand |
|                                        |Redaktionen                                      | Im Entwicklungsrückstand |
|                                        |Filterung                                       | Im Entwicklungsrückstand |
|                                        |Depot für Arbeits Auslastungs Zuordnung                   | Im Entwicklungsrückstand |
|                                        |Depotbank-Kommunikation                        | Im Entwicklungsrückstand |
|                                        |Überprüfungs Sätze                                     | Im Entwicklungsrückstand |
|                                        |Überprüfen und kommentieren                             | Im Entwicklungsrückstand |
|                                        |Nicht Office 365E Einnahme                        | Im Entwicklungsrückstand |
|                                        |Suchausdrucks Bericht                              | Im Entwicklungsrückstand |

**Entscheidungspunkt**: *entscheiden Sie, ob die Konformitäts Funktionen den Anforderungen Ihrer Organisation entsprechen.*
