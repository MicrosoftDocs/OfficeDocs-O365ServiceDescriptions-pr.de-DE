---
title: Berichterstellung und Nachrichtenablaufverfolgung
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP) bietet viele verschiedene Berichte an, mit deren Hilfe Sie den allgemeinen Status und die Integrität Ihrer Organisation ermitteln können. Einige Berichte stehen im Microsoft 365 Admin Center zur Verfügung, während andere im Exchange Admin Center (EAC) verfügbar sind.
ms.openlocfilehash: 0fab453ae50454e9f613c0996b8baacc7081cb97
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132759"
---
# <a name="reporting-and-message-trace"></a>Berichterstellung und Nachrichtenablaufverfolgung

Microsoft Exchange Online Protection (EOP) bietet viele verschiedene Berichte an, mit deren Hilfe Sie den allgemeinen Status und die Integrität Ihrer Organisation ermitteln können. Einige Berichte stehen im Microsoft 365 Admin Center zur Verfügung, während andere im Exchange Admin Center (EAC) verfügbar sind.

Sie suchen nach Informationen zu allen EOP-Funktionen? Siehe [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).

## <a name="microsoft-365-admin-center-reports"></a>Microsoft 365 Admin Center-Berichte

Die Seite Berichte im Microsoft 365 Admin Center enthält Informationen zum Nachrichten Datenverkehr, zu Spam-und Schadsoftware-Erkennungen sowie zu Nachrichten, die von Nachrichtenfluss Regeln (auch bekannt als Transportregeln) oder von DLP-Richtlinien (Data Loss Prevention) betroffen sind. Die erweiterten Berichte zu Schutz, Regeln und DLP bieten eine interaktive Berichterstellungserfahrung für EOP-Administratoren. Diese Berichte stellen Übersichtsinformationen und die Möglichkeit der Detailsuche in einzelnen Nachrichten zur Verfügung.

Ausführlichere Informationen zu diesen Berichten finden Sie unter [Verwenden von e-Mail-Schutz Berichten zum Anzeigen von Daten über Schadsoftware, Spam und Regel Erkennungen](https://docs.microsoft.com/exchange/monitoring/use-mail-protection-reports).

## <a name="reporting-using-web-services"></a>Reporting using web services

> [!NOTE]
> Viele der Rest-basierten Berichtsfeatures und zugehörigen Cmdlets wurden im Januar 2018 veraltet. Informationen zu den verfügbaren Ersatz-Microsoft Graph-Berichten in Office 365 finden Sie in den Unterthemen [Arbeiten mit Verwendungsberichten in Microsoft Graph](https://go.microsoft.com/fwlink/p/?LinkID=865135).

Nicht verfügbar für Kunden der eigenständigen Lösung von EOP. Sie können den Rest/OData-Mandanten Berichterstattungswebdienst verwenden, um zusammenfassende und detaillierte Berichte zu Messagingdaten programmgesteuert zu sammeln, und Sie können die Daten auf einer Webseite in einem benutzerdefinierten Webverwaltungs Portal anzeigen.

## <a name="message-trace"></a>Nachrichtenablaufverfolgung

Mit dem Feature Nachrichtenablaufverfolgung in der Exchange-Verwaltungskonsole können Sie als Administrator e-Mail-Nachrichten beim Durchlaufen des EoP verfolgen. Sie können damit bestimmen, ob eine bestimmte E-Mail vom Dienst empfangen, abgelehnt, zurückgestellt oder zugestellt wurde. Außerdem wird gezeigt, welche Aktionen in der Nachricht vorgenommen wurden, bevor der endgültige Status erreicht wurde. Wenn Sie detaillierte Informationen zu einer bestimmten Nachricht erhalten, können Sie Ihre Benutzer Fragen effizient beantworten, Probleme mit dem Nachrichtenfluss beheben, Richtlinienänderungen überprüfen und die Notwendigkeit entschärfen, den technischen Support um Unterstützung zu bitten. Weitere Informationen finden Sie unter [Ausführen einer Nachrichtenablaufverfolgung und Anzeigen der Ergebnisse im Exchange Admin Center](https://docs.microsoft.com/exchange/monitoring/trace-an-email-message/run-a-message-trace-and-view-results).

## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).
