---
title: Planen von Microsoft 365 Compliance – gcc
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ROBOTS: NOINDEX, NOFOLLOW
description: Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in den US-Bundesstaaten, Ländern, lokalen, Stammes-oder Gebietskörperschaften oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government-gcc ist geeignet, um diese Anforderungen zu erfüllen.
ms.openlocfilehash: 50649287df37afe20b58f98333a10bc7885b417d
ms.sourcegitcommit: f69656f34dcb4f4e9a5857d8c4236084c94a05b1
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/31/2019
ms.locfileid: "37890491"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Plan for Microsoft 365 Compliance – gcc

Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in den US-Bundesstaaten, Ländern, lokalen, Stammes-oder Gebietskörperschaften oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government-gcc ist geeignet, um diese Anforderungen zu erfüllen.

> [!NOTE]
> Wenn Ihre Organisation bereits die Microsoft 365 Government-gcc-Zulassungsvoraussetzungen erfüllt und in das Programm übernommen und akzeptiert wurde, können Sie die Schritte 1 und 2 überspringen und direkt zu Schritt 3 wechseln.

## <a name="step-1-determine-whether-your-organization-needs-microsoft-365-government---gcc-and-meets-eligibility-requirements"></a>Schritt 1: Ermitteln, ob Ihre Organisation Microsoft 365 Government-gcc benötigt und die Zulassungsvoraussetzungen erfüllt

Die Microsoft 365 Government-gcc-Umgebung erfüllt die US-behördlichen Anforderungen für Cloud-Dienste, einschließlich FedRAMP moderat, und Anforderungen für Strafjustiz und Eidgenössische Steuer Informationssysteme (CJI-und FTI-Datentypen).

Neben den Features und Funktionen von Office 365 profitieren Organisationen von den folgenden Features, die für Microsoft 365 Government-gcc einzigartig sind:

- Der Kunden Inhalt Ihrer Organisation wird logischerweise von Kundeninhalten in den kommerziellen Office 365 Diensten von Microsoft getrennt.

- Der Kundeninhalt Ihrer Organisation wird in den Vereinigten Staaten gespeichert.

- Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.

- Microsoft 365 Government-gcc erfüllt Zertifizierungen und Akkreditierungen, die für US-Kunden des öffentlichen Sektors erforderlich sind.

Weitere Informationen zum Microsoft 365 Government-gcc-Angebot für US-Regierungskunden finden Sie unter [Office 365 Government-Pläne](https://products.office.com/government/compare-office-365-government-plans), einschließlich der Berechtigungsanforderungen.

Die [Office 365 US Government Service Description](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government) beschreibt die Vorteile der Plattform, die sich auf die Erfüllung der Compliance-Anforderungen in den Vereinigten Staaten konzentrieren.

> [!TIP]
> Möglicherweise möchten Sie die Tabellen mit Informationen in der Dienstbeschreibung in eine Excel-Arbeitsmappe übertragen und zwei Spalten hinzufügen: **relevant für meine Organisation y/n** und **den Anforderungen meiner Organisation y/n entsprechen**. Anschließend können Sie diese Liste mit ihren Kollegen überprüfen, um zu bestätigen, dass dieser Dienst die Anforderungen Ihrer Organisation erfüllt.

> [!NOTE]
> Microsoft 365 Government-gcc ist nur in den Vereinigten Staaten verfügbar. Kunden außerhalb der US-Regierung können aus einer Reihe von [Office 365 Government-Plänen](https://products.office.com/government/compare-office-365-government-plans)wählen.

**Entscheidungspunkte**: <br/>
- *Entscheiden Sie, ob Microsoft 365 Government-gcc für Ihre Organisation geeignet ist.*
- *Stellen Sie sicher, dass Ihre Organisation die Berechtigungsanforderungen erfüllt.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Schritt 2: Beantragen von Microsoft 365 Government-gcc

Nachdem Sie entschieden haben, dass dieser Dienst für Ihre Organisation geeignet ist, starten Sie den Prozess der [Beantragung dieses Diensts](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>SCHRITT 3: Grundlegendes zu Microsoft 365 Government-gcc-Standardsicherheitseinstellungen

Es wird empfohlen, dass Sie sich Zeit nehmen, um die Administrator-und Sicherheitseinstellungen sorgfältig zu überprüfen, bevor Sie Sie ändern und die Auswirkungen auf die Kompatibilität berücksichtigen, bevor Sie Änderungen an den Standardsicherheitseinstellungen vornehmen.

**Entscheidungspunkt**: *entscheiden Sie, ob Sie die Standardsicherheitseinstellungen von Microsoft 365 Government-gcc ändern, um zunächst die Auswirkungen von Änderungen zu verstehen, die Sie möglicherweise vornehmen.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gcc"></a>Schritt 4: Grundlegendes zu den derzeit nicht verfügbaren oder standardmäßig in Microsoft 365 Government – gcc deaktivierten Funktionen

Um den Anforderungen unserer Government Cloud-Kunden gerecht zu werden, gibt es einige Unterschiede zwischen Microsoft 365 Government-gcc und Enterprise-Plänen. In der folgenden Tabelle finden Sie Informationen zu verfügbaren Features.

|                                         | **Feature**                                     | **GCC-Status**         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Informationsschutz #a0 Steuerung** | Archivierung                                       | Available              |
|                                         | Manuelle Bezeichnungen und Richtlinien                      | Available              |
|                                         | Automatische Anwendung von Beschriftungen                      | Im Entwicklungsrückstand |
|                                         | Bezeichnungen basierend auf vertraulichen Datentypen            | Im Entwicklungsrückstand |
|                                         | Bezeichnungen und zugeordnete Richtlinien basierend auf Abfragen | Im Entwicklungsrückstand |
|                                         | Dateiplan                                       | Im Entwicklungsrückstand |
|                                         | Empfohlene Richtlinien                            | Im Entwicklungsrückstand |
|                                         | Intelligente Importfilter                            | Im Entwicklungsrückstand |
|                                         | Ereignisbasierte Aufbewahrung                           | Im Entwicklungsrückstand |
|                                         | Dispositions Überprüfung                              | Im Entwicklungsrückstand |
|                                         | Informationsbarrieren                            | Available              |
|                                         | Verhinderung von Datenverlust (DLP) für Dateien und e-Mail  | Available              |
|                                         | DLP für Microsoft Teams-Chat und Kanal Unterhaltungen    | Available              |
| **Insider Risikomanagement**             | Erweiterte Nachrichtenverschlüsselung                     | Available              |
|                                         | Kommunikation Compliance                        | Im Entwicklungsrückstand |
|                                         | Kunden-Lockbox                                | Available              |
|                                         | Kundenschlüssel                                    | Available              |
|                                         | Privileged Access Management                    | Im Entwicklungsrückstand |
| **Antworten auf #a0 ermitteln**                  | In-Place-Reservierung                            | Available              |
|                                         | Fallverwaltung                                 | Available              |
|                                         | Suche                                          | Available              |
|                                         | Exportieren                                          | Available              |
|                                         | RMS-Entschlüsselung                                  | Available              |
|                                         | Nativer Export                                   | Available              |
|                                         | Überwachung                                        | Available              |
|                                         | Erweiterte Verarbeitung                             | Im Entwicklungsrückstand |
|                                         | E-Mail-Threading                                 | Im Entwicklungsrückstand |
|                                         | Nahe doppelte Identifikation                   | Im Entwicklungsrückstand |
|                                         | Designs                                          | Im Entwicklungsrückstand |
|                                         | Prädiktive Codierung                               | Im Entwicklungsrückstand |
|                                         | Verarbeitete Exportdatei mit Ladedatei                 | Im Entwicklungsrückstand |
|                                         | Kategorien                                         | Im Entwicklungsrückstand |
|                                         | Anzeigende Benutzer                                         | Im Entwicklungsrückstand |
|                                         | Redaktionen                                      | Im Entwicklungsrückstand |
|                                         | Filterung                                       | Im Entwicklungsrückstand |
|                                         | Depot für Arbeits Auslastungs Zuordnung                   | Im Entwicklungsrückstand |
|                                         | Depotbank-Kommunikation                        | Im Entwicklungsrückstand |
|                                         | Überprüfungs Sätze                                     | Im Entwicklungsrückstand |
|                                         | Überprüfen und kommentieren                             | Im Entwicklungsrückstand |
|                                         | Nicht Office 365E Einnahme                        | Im Entwicklungsrückstand |
|                                         | Suchausdrucks Bericht                              | Im Entwicklungsrückstand |

**Entscheidungspunkt**: *entscheiden Sie, ob die Konformitäts Funktionen den Anforderungen Ihrer Organisation entsprechen.*
