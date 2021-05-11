---
title: Berichterstellungsfeatures und Tools zur Problembehandlung
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online bietet eine Vielzahl von Berichtsfeatures sowohl im Exchange Admin Center (EAC).
ms.openlocfilehash: fa80cd6c7d8e9e5f0527c478474cffe17e9204af
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652689"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Berichterstellungsfeatures und Tools zur Problembehandlung

Microsoft Exchange Online bietet eine Vielzahl von Berichtsfeatures sowohl im Exchange Admin Center (EAC).
  
## <a name="reporting-features"></a>Berichterstellungsfeatures

Exchange Online Kunden können auf Berichte im Microsoft 365 Admin Center zugreifen, indem sie eine Excel-Berichtsarbeitsmappe herunterladen oder Webdienste verwenden.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Berichterstellung im Microsoft 365 Admin Center

Es gibt Berichte auf der Seite Berichte im Microsoft 365 Admin Center, die Zusammenfassende Informationen zu Postfächern und Gruppen bereitstellen. Beispielsweise wird in einem Bericht die Anzahl der Gruppen aufgeführt, die pro Tag, Woche, Monat oder Jahr erstellt und gelöscht wurden. Es gibt auch Zusammenfassungsberichte für neue und gelöschte sowie aktive und inaktive Postfächer. 
  
Darüber hinaus enthält die Seite Berichte im Microsoft 365 Admin Center Messagingdatenberichte, die Informationen zu Nachrichtendatenverkehr, Spam- und Schadsoftwareerkennungen und Nachrichten bereitstellen, die von Exchange-Transportregeln oder DLP-Richtlinien (Data Loss Prevention) betroffen sind. Die optimierten Berichte zu Schutz, Regeln und DLP (Data Loss Prevention, Verhinderung von Datenverlust) bieten Exchange Online-Administratoren eine interaktive Umgebung für die Berichterstellung. Diese Berichte stellen Übersichtsinformationen und die Möglichkeit der Detailsuche in einzelnen Nachrichten zur Verfügung.
  
Weitere Informationen dazu, welche Berichte für jedes Abonnement verfügbar sind, finden Sie unter [Berichte](../office-365-platform-service-description/reports.md). Weitere Informationen zur Seite Berichte im Microsoft 365 Admin Center finden Sie unter Anzeigen und Herunterladen von Berichten zur Dienstnutzung [in Office 365](/microsoft-365/admin/activity-reports/activity-reports) und Verwenden von E-Mail-Schutzberichten zum Anzeigen von Daten zu Schadsoftware, Spam und Regelerkennungen. [](/exchange/monitoring/use-mail-protection-reports)
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Berichte über die Excel-Arbeitsmappe mit Berichten

Sie können auch die Excel 2013-Berichtsarbeitsmappe verwenden, um Zusammenfassungsberichte mit Drilldownfunktionalitäten anzuzeigen. Es wird jedoch empfohlen, stattdessen die Microsoft 365 Admin Center-Berichte zu verwenden. Die Excel 2013-Berichtsarbeitsmappe wird voraussichtlich in naher Zukunft eingestellt. Einen detaillierteren Überblick und Links zum Herunterladen und Installieren der Arbeitsmappe finden Sie auf [dieser Downloadseite](https://go.microsoft.com/fwlink/p/?LinkId=271776). Informationen zur Verwendung der Arbeitsmappe finden Sie unter [E-Mail-Schutzberichte in der Excel-Berichtsarbeitsmappe](/previous-versions/exchange-server/exchange-150/jj945734(v=exchg.150)). 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

Der Zugriff auf zusammenfassende und detaillierte Berichte zu Postfächern, Gruppen und Messagingdaten ist über den REST/OData-Mandantenberichtswebdienst verfügbar, einer programmgesteuerten Schnittstelle, mit der Sie benutzerdefinierte Berichte erstellen können. Weitere Informationen finden Sie unter [Office 365 Reporting Web Services](/previous-versions/office/developer/o365-enterprise-developers/jj984325(v=office.15)).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Berichtsfeatures und Problembehandlungstools in der Exchange-Verwaltungskonsole

Die folgenden Berichtsfeatures und Problembehandlungstools stehen in der Exchange-Verwaltungskonsole zur Verfügung.
  
### <a name="trace-an-email-message"></a>Verfolgen einer E-Mail

Mit dem Nachrichtenverfolgungsfeature können Sie als Administrator E-Mail-Nachrichten verfolgen, während sie Ihren Exchange Online übergeben. Sie können damit bestimmen, ob eine bestimmte E-Mail vom Dienst empfangen, abgelehnt, zurückgestellt oder zugestellt wurde. So können Sie in effizienter Weise Fragen der Benutzer beantworten und Probleme mit dem Nachrichtenfluss behandeln und müssen seltener den technischen Support um Unterstützung bitten.
  
> [!IMPORTANT]
> Verwenden Sie für die Behandlung allgemeiner Probleme und Trends die Berichtstools, um solche Daten abzurufen. Verwenden Sie bei speziellen Besonderheiten, bei denen Details zu einer Nachricht erforderlich sind, das Tool für die Nachrichtenablaufverfolgung. 
  
Weitere Informationen zum Feature für die Nachrichtenablaufverfolgung finden Sie unter [Verfolgen einer E-Mail](/exchange/monitoring/trace-an-email-message/trace-an-email-message).
  
### <a name="auditing-reports"></a>Überwachungsberichte

Sie können die Überwachungsprotokollierung zum Behandeln von Konfigurationsproblemen verwenden, indem Sie bestimmte von Administratoren vorgenommene Änderungen nachverfolgen. Außerdem können Sie damit gesetzliche Bestimmungen sowie Anforderungen an Richtlinientreue und Beweissicherungsverfahren einhalten. Von Exchange Online werden zwei Arten der Überwachungsprotokollierung bereitgestellt:
  
- Mit der Administrator-Überwachungsprotokollierung wird jede Aktion aufgezeichnet, die von einem Administrator durchgeführt wird. Diese Informationen können Sie zur Behandlung von Konfigurationsproblemen bzw. zum Ermitteln der Ursache von Sicherheits- oder Kompatibilitätsproblemen heranziehen. 
    
- Bei der Postfachüberwachungsprotokollierung werden alle Postfachzugriffe erfasst, die von Personen vorgenommen werden, bei denen es sich nicht um den Besitzer des Postfachs handelt. Dadurch können Sie feststellen, wer auf ein Postfach zugegriffen hat und welche Aktionen ausgeführt wurden. 
    
Weitere Informationen zur Überwachungsprotokollierung finden Sie im Artikel zum Thema [Überwachungsberichte](/exchange/security-and-compliance/exchange-auditing-reports/exchange-auditing-reports).
  
### <a name="unified-messaging-reports"></a>Unified Messaging-Berichte

Mithilfe dieser Berichte können Sie Unified Messaging (UM) in Ihrer Exchange Online-Organisation überwachen und Probleme beheben. Weitere Informationen finden Sie im Artikel zum Thema [Erstellen von Berichten für Voicemailanrufe](/exchange/voice-mail-unified-messaging/run-voice-mail-call-reports/run-voice-mail-call-reports).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie [unter Exchange Online Service description](exchange-online-service-description.md).
