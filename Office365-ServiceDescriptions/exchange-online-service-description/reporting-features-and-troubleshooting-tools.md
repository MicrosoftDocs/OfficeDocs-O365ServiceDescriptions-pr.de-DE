---
title: Berichterstellungsfeatures und Tools zur Problembehandlung
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online bietet eine Vielzahl von Berichtsfeatures sowohl in als auch außerhalb des Exchange Admin Center (EAC).
ms.openlocfilehash: f2cc51c9923be8d399fa2837e5b5fabe3117d5ba
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132599"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Berichterstellungsfeatures und Tools zur Problembehandlung

Microsoft Exchange Online bietet eine Vielzahl von Berichtsfeatures sowohl in als auch außerhalb des Exchange Admin Center (EAC).
  
## <a name="reporting-features"></a>Berichtsfeatures

Exchange Online Kunden können auf Berichte im Microsoft 365 Admin Center, durch Herunterladen einer Excel-Berichtsarbeitsmappe oder mithilfe von Webdiensten zugreifen.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Berichterstellung im Microsoft 365 Admin Center

Es gibt Berichte auf der Seite Berichte im Microsoft 365 Admin Center, die zusammenfassende Informationen zu Postfächern und Gruppen bereitstellen. Beispielsweise wird in einem Bericht die Anzahl der Gruppen aufgeführt, die pro Tag, Woche, Monat oder Jahr erstellt und gelöscht wurden. Es gibt auch Zusammenfassungsberichte für neue und gelöschte sowie aktive und inaktive Postfächer. 
  
Darüber hinaus enthält die Seite "Berichte" im Microsoft 365 Admin Center Nachrichtendaten Berichte, die Informationen zum Nachrichten Datenverkehr, zu Spam-und Schadsoftware-Erkennungen sowie Nachrichten enthalten, die von Exchange-Transport Regeln oder DLP-Richtlinien (Data Loss Prevention, Verhinderung von Datenverlust) betroffen sind. Die optimierten Berichte zu Schutz, Regeln und DLP (Data Loss Prevention, Verhinderung von Datenverlust) bieten Exchange Online-Administratoren eine interaktive Umgebung für die Berichterstellung. Diese Berichte stellen Übersichtsinformationen und die Möglichkeit der Detailsuche in einzelnen Nachrichten zur Verfügung.
  
Weitere Informationen darüber, welche Berichte mit den einzelnen Abonnements zur Verfügung stehen, finden Sie unter [Reports](../office-365-platform-service-description/reports.md). Ausführlichere Informationen zur Seite "Berichte" im Microsoft 365 Admin Center finden Sie unter [anzeigen und Herunterladen von Berichten über die Verwendung von Diensten in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) und [Verwenden von e-Mail-Schutz Berichten zum Anzeigen von Daten zu Schadsoftware, Spam und Regel Erkennungen](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Berichte über die Excel-Arbeitsmappe mit Berichten

Sie können auch die Excel 2013-Berichtsarbeitsmappe verwenden, um Zusammenfassungsberichte mit Drilldownfunktionalitäten anzuzeigen. Es wird jedoch empfohlen, stattdessen die verbesserten Microsoft 365 Admin Center-Berichte zu verwenden. Die Excel 2013-Berichtsarbeitsmappe wird voraussichtlich in naher Zukunft eingestellt. Einen detaillierteren Überblick und Links zum Herunterladen und Installieren der Arbeitsmappe finden Sie auf [dieser Downloadseite](https://go.microsoft.com/fwlink/p/?LinkId=271776). Informationen zur Verwendung der Arbeitsmappe finden Sie unter [E-Mail-Schutzberichte in der Excel-Berichtsarbeitsmappe](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
### <a name="reporting-using-web-services"></a>Reporting using web services

Der Zugriff auf zusammenfassende und detaillierte Berichte über Postfächer, Gruppen und Messagingdaten ist mithilfe der Rest/OData-Mandanten Berichterstattungswebdienst, die eine programmgesteuerte Schnittstelle ist, mit der Sie benutzerdefinierte Berichte erstellen können, verfügbar. Weitere Informationen finden Sie unter [Office 365 Reporting-Webdienste](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Berichtsfeatures und Problembehandlungstools in der Exchange-Verwaltungskonsole

Die folgenden Berichtsfeatures und Problembehandlungstools stehen in der Exchange-Verwaltungskonsole zur Verfügung.
  
### <a name="trace-an-email-message"></a>Verfolgen einer E-Mail

Mit dem Feature Nachrichtenablaufverfolgung können Sie als Administrator e-Mail-Nachrichten bei der Weitergabe Ihres Exchange Online Diensts befolgten. Sie können damit bestimmen, ob eine bestimmte E-Mail vom Dienst empfangen, abgelehnt, zurückgestellt oder zugestellt wurde. So können Sie in effizienter Weise Fragen der Benutzer beantworten und Probleme mit dem Nachrichtenfluss behandeln und müssen seltener den technischen Support um Unterstützung bitten.
  
> [!IMPORTANT]
> For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool. 
  
Weitere Informationen zum Feature für die Nachrichtenablaufverfolgung finden Sie unter [Verfolgen einer E-Mail](https://go.microsoft.com/fwlink/p/?LinkId=271777).
  
### <a name="auditing-reports"></a>Überwachungsberichte

You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:
  
- Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems. 
    
- Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done. 
    
Weitere Informationen zur Überwachungsprotokollierung finden Sie im Artikel zum Thema [Überwachungsberichte](https://go.microsoft.com/fwlink/p/?LinkId=271779).
  
### <a name="unified-messaging-reports"></a>Unified Messaging-Berichte

You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  

