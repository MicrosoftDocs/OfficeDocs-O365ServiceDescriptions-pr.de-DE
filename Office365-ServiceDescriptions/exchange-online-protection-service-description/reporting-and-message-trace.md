---
title: Berichterstellung und Nachrichtenablaufverfolgung in Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: In diesem Artikel erfahren Sie mehr über Reporting and message trace in Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 383c222563e76d4a5613c9faac5b68417fa64b8a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653127"
---
# <a name="reporting-and-message-trace-in-exchange-online-protection"></a>Berichterstellung und Nachrichtenablaufverfolgung in Exchange Online Protection

Microsoft Exchange Online Protection (EOP) bietet viele verschiedene Berichte an, mit deren Hilfe Sie den allgemeinen Status und die Integrität Ihrer Organisation ermitteln können. Einige Berichte sind im Microsoft 365 Admin Center verfügbar, während andere im Exchange Admin Center (EAC) verfügbar sind.

Sie suchen nach Informationen zu allen EOP-Funktionen? Weitere Informationen [finden Exchange Online Protection Dienstbeschreibung](exchange-online-protection-service-description.md).

## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 Admin Center-Berichte

Die Seite Berichte im Microsoft 365 Admin Center enthält Informationen zu Nachrichtendatenverkehr, Spam- und Schadsoftwareerkennungen und Nachrichten, die von Nachrichtenflussregeln (auch als Transportregeln bezeichnet) oder DLP-Richtlinien (Data Loss Prevention) betroffen sind. Die erweiterten Berichte zu Schutz, Regeln und DLP bieten eine interaktive Berichterstellungserfahrung für EOP-Administratoren. Diese Berichte stellen Übersichtsinformationen und die Möglichkeit der Detailsuche in einzelnen Nachrichten zur Verfügung.

Ausführlichere Informationen zu diesen Berichten finden Sie unter Verwenden von E-Mail-Schutzberichten zum Anzeigen von Daten zu Schadsoftware, Spam und [Regelerkennungen.](/exchange/monitoring/use-mail-protection-reports)

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> Viele der REST-basierten Berichtsfunktionen und zugehörigen Cmdlets waren im Januar 2018 veraltet. Informationen zu den verfügbaren Microsoft Graph in Office 365 finden Sie in den Untertopen arbeiten mit Verwendungsberichten [in Microsoft Graph](/graph/api/resources/report).

Nicht verfügbar für Kunden der eigenständigen Lösung von EOP. Sie können den REST/OData-Mandantenberichtswebdienst verwenden, um zusammenfassungs- und detaillierte Berichte zu Messagingdaten programmgesteuert zu erfassen, und Sie können die Daten auf einer Webseite in einem benutzerdefinierten Webverwaltungsportal anzeigen.

## <a name="message-trace"></a>Nachrichtenablaufverfolgung

Mit dem Nachrichtenverfolgungsfeature in der EAC können Sie als Administrator E-Mail-Nachrichten beim Passieren des EOP verfolgen. Sie können damit bestimmen, ob eine bestimmte E-Mail vom Dienst empfangen, abgelehnt, zurückgestellt oder zugestellt wurde. Außerdem wird gezeigt, welche Aktionen für die Nachricht vor dem Erreichen des endgültigen Status aufgetreten sind. Durch das Abrufen detaillierter Informationen zu einer bestimmten Nachricht können Sie die Fragen Ihres Benutzers effizient beantworten, Probleme mit dem Nachrichtenfluss beheben, Richtlinienänderungen überprüfen und den technischen Support um Unterstützung bitten. Weitere Informationen finden Sie unter [Ausführen einer Nachrichtenverfolgung und Anzeigen](/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results)der Ergebnisse im Exchange Admin Center .

## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie [unter Exchange Online Protection Service description](exchange-online-protection-service-description.md).