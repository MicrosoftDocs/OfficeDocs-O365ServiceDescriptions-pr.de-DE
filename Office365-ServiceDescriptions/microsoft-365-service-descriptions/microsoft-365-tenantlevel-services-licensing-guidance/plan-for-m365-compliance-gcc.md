---
title: Planen von Microsoft 365 Compliance – GCC
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in den US-Bundesländern, Staaten, lokalen, Stammes-oder Gebietskörperschaften oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government-gcc geeignet ist, diese Anforderungen zu erfüllen.
ms.openlocfilehash: 1e172588c21c15bd0422edb12d5024764f56ead7
ms.sourcegitcommit: d4025c73f14b663ffcaa1ef8db4174b51debdae7
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/23/2020
ms.locfileid: "45388101"
---
# <a name="plan-for-microsoft-365-compliance--gcc"></a>Plan for Microsoft 365 Compliance – gcc

Dieser Leitfaden richtet sich an IT-Experten, die Bereitstellungen von Office 365 in den US-Bundesländern, Staaten, lokalen, Stammes-oder Gebietskörperschaften oder anderen Entitäten mit Daten verarbeiten, die behördlichen Vorschriften und Anforderungen unterliegen, wobei die Verwendung von Microsoft 365 Government-gcc geeignet ist, diese Anforderungen zu erfüllen.

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
> Möglicherweise möchten Sie die Tabellen mit Informationen in der Dienstbeschreibung in eine Excel-Arbeitsmappe übertragen und zwei Spalten hinzufügen: **relevant für meine Organisation y/n**   und **den Anforderungen meiner Organisation y/n entsprechen**. Anschließend können Sie diese Liste mit ihren Kollegen überprüfen, um zu bestätigen, dass dieser Dienst die Anforderungen Ihrer Organisation erfüllt.

> [!NOTE]
> Microsoft 365 Government-gcc ist nur in den Vereinigten Staaten verfügbar. Kunden außerhalb der US-Regierung können aus einer Reihe von [Office 365 Government-Plänen](https://products.office.com/government/compare-office-365-government-plans)wählen.

**Entscheidungspunkte**: <br/>
- *Entscheiden Sie, ob Microsoft 365 Government-gcc für Ihre Organisation geeignet ist.*
- *Stellen Sie sicher, dass Ihre Organisation die Berechtigungsanforderungen erfüllt.*

## <a name="step-2-apply-for-microsoft-365-government---gcc"></a>Schritt 2: Beantragen von Microsoft 365 Government-gcc

Nachdem Sie entschieden haben, dass dieser Dienst für Ihre Organisation geeignet ist, starten Sie den Prozess der [Beantragung dieses Diensts](https://products.office.com/government/eligibility-validation).

## <a name="step-3-understand-microsoft-365-government---gcc-default-security-settings"></a>Schritt 3: Grundlegendes zu Microsoft 365 Government-gcc-Standardsicherheitseinstellungen

Es wird empfohlen, dass Sie sich Zeit nehmen, um die Administrator-und Sicherheitseinstellungen sorgfältig zu überprüfen, bevor Sie Sie ändern und die Auswirkungen auf die Kompatibilität berücksichtigen, bevor Sie Änderungen an den Standardsicherheitseinstellungen vornehmen.

**Entscheidungspunkt**: *entscheiden Sie, ob Sie die Standardsicherheitseinstellungen von Microsoft 365 Government-gcc ändern, um zunächst die Auswirkungen von Änderungen zu verstehen, die Sie möglicherweise vornehmen.*

## <a name="step-4-understand-which-capabilities-are-currently-unavailable-or-disabled-by-default-in-microsoft-365-government--gccsup1sup"></a>Schritt 4: Grundlegendes zu den derzeit nicht verfügbaren oder deaktivierten Funktionen in Microsoft 365 Government – gcc<sup>1</sup>

Um den Anforderungen unserer Government Cloud-Kunden gerecht zu werden, gibt es einige Unterschiede zwischen Microsoft 365 Government-gcc und Enterprise-Plänen. In der folgenden Tabelle finden Sie Informationen zu verfügbaren Features.

|                                         | **Feature**                                     | **GCC-Status**         |
| --------------------------------------- | ----------------------------------------------- | ---------------------- |
| **Informationsschutz & Steuerung** | Archivierung                                       | Available              |
|                                         | Manuelle Bezeichnungen und Richtlinien<sup>2</sup>          | Available              |
|                                         | Automatische Anwendung von Beschriftungen                      | Available              |
|                                         | Bezeichnungen basierend auf vertraulichen Datentypen            | Im Entwicklungsrückstand |
|                                         | Bezeichnungen und zugeordnete Richtlinien basierend auf Abfragen | Available              |
|                                         | Dateiplan                                       | Available              |
|                                         | Empfohlene Richtlinien                            | Im Entwicklungsrückstand |
|                                         | Intelligente Importfilter                            | Im Entwicklungsrückstand |
|                                         | Ereignisbasierte Aufbewahrung                           | Available              |
|                                         | Dispositionsüberprüfung                              | Available              |
|                                         | Informationsbarrieren                            | Available              |
|                                         | Verhinderung von Datenverlust (DLP) für Dateien und e-Mail  | Available              |
|                                         | DLP für Microsoft Teams-Chat und Kanal Unterhaltungen    | Im Entwicklungsrückstand |
|                                         | Exakte DLP-Datenübereinstimmung                            | Im Entwicklungsrückstand |
|                                         | Bezeichnungsaktivitäten-Explorer                         | Im Entwicklungsrückstand |
|                                         | Trainierbare Klassifizierungsmerkmale                           | Im Entwicklungsrückstand |
|                                         | Einheitliche Beschriftungs-und Vertraulichkeits Bezeichnungen         | Im Entwicklungsrückstand |
| **Insider-Risikomanagement**             | Erweiterte Nachrichtenverschlüsselung                     | Available              |
|                                         | Insider-Risikomanagement                         | Im Entwicklungsrückstand |
|                                         | Kommunikationscompliance                        | Im Entwicklungsrückstand |
|                                         | Kunden-Lockbox                                | Available              |
|                                         | Kundenschlüssel                                    | Available              |
|                                         | Privileged Access Management                    | Im Entwicklungsrückstand |
| **Antworten auf & ermitteln**                  | Zentrale eDiscovery: in-Place-Aufbewahrung                            | Available              |
|                                         | Zentrale eDiscovery: Fallverwaltung                                 | Available              |
|                                         | Zentrale eDiscovery: Suche                                          | Available              |
|                                         | Haupt-eDiscovery: Export                                          | Available              |
|                                         | Zentrale eDiscovery: RMS-Entschlüsselung                                  | Available              |
|                                         | Zentrale eDiscovery: nativer Export                                   | Available              |
|                                         | Zentrale eDiscovery: Überwachung                                        | Available              |
|                                         | Erweiterte eDiscovery: erweiterte Verarbeitung                             | Available |
|                                         | Erweiterte eDiscovery: e-Mail-Threading                                 | Available |
|                                         | Erweiterte eDiscovery: nahe doppelte Identifikation                   | Available |
|                                         | Erweiterte eDiscovery: Designs                                          | Available |
|                                         | Advanced eDiscovery: Predictive Coding                               | Available |
|                                         | Erweiterte eDiscovery: verarbeitete Exportdatei mit lastdatei                 | Available |
|                                         | Erweiterte eDiscovery: Tagging                                         | Available |
|                                         | Erweiterte eDiscovery: Viewer                                         | Available |
|                                         | Erweiterte eDiscovery:-Aktionen                                      | Available |
|                                         | Erweiterte eDiscovery: Filterung                                       | Available |
|                                         | Erweiterte eDiscovery: Depotverwaltung für Arbeits Auslastungs Zuordnung                   | Available |
|                                         | Erweiterte eDiscovery: Depotbank-Kommunikation                        | Available |
|                                         | Erweiterte eDiscovery: Überprüfungs Sätze                                     | Available |
|                                         | Erweiterte eDiscovery: überprüfen und kommentieren                             | Available |
|                                         | Erweiterte eDiscovery: nicht Office 365E Einnahme                        | Available |
|                                         | Erweiterte eDiscovery: Suchbegriffs Bericht                              | Available |

<sup>1</sup> der Status "identifiziert" kann geändert werden, wenn Projektpläne und Prioritäten neu ausgewertet werden.<br/>
<sup>2</sup> die manuelle Anwendung von Bezeichnungen erfordert den [Azure Information Protection (AIP)-Client, Version 1](https://docs.microsoft.com/azure/information-protection/rms-client/client-version-release-history).


**Entscheidungspunkt**: *entscheiden Sie, ob die Konformitäts Funktionen den Anforderungen Ihrer Organisation entsprechen.*
