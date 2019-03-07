---
title: Berichterstellungsfeatures und Tools zur Problembehandlung
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-reporting-features-and-troubleshooting-tools
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7a89aaf4-747a-434a-a20b-ebc1ee10c742
description: Microsoft Exchange Online bietet eine Vielzahl von Berichtsfunktionen sowohl innerhalb als auch außerhalb der Exchange-Verwaltungskonsole.
ms.openlocfilehash: 1fb9a0fe62fb94c0ace7388613ca26f65fc4698f
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/07/2019
ms.locfileid: "30466982"
---
# <a name="reporting-features-and-troubleshooting-tools"></a>Berichterstellungsfeatures und Tools zur Problembehandlung

Microsoft Exchange Online bietet eine Vielzahl von Berichtsfunktionen sowohl innerhalb als auch außerhalb der Exchange-Verwaltungskonsole.
  
## <a name="reporting-features"></a>Berichtsfeatures

Exchange Online-Kunden können auf Berichte im Microsoft 365 Admin Center zugreifen, indem Sie eine Excel-Berichtsarbeitsmappe herunterladen oder Webdienste verwenden.
  
### <a name="reporting-in-the-microsoft-365-admin-center"></a>Berichterstellung im Microsoft 365 Admin Center

Es gibt Berichte auf der Seite "Berichte" im Microsoft 365 Admin Center, die zusammenfassende Informationen zu Postfächern und Gruppen bereitstellen. Beispielsweise wird in einem Bericht die Anzahl der Gruppen aufgeführt, die pro Tag, Woche, Monat oder Jahr erstellt und gelöscht wurden. Es gibt auch Zusammenfassungsberichte für neue und gelöschte sowie aktive und inaktive Postfächer. 
  
Darüber hinaus enthält die Seite "Berichte" im Microsoft 365 Admin Center Nachrichtendaten Berichte, die Informationen zum Nachrichten Datenverkehr, zu Spam-und Schadsoftware-Ermittlungen sowie zu Nachrichten von Exchange-Transport Regeln oder zur verHinderung von Datenverlust (Data Loss Prevention, DLP) enthalten. Richtlinien. Die optimierten Berichte zu Schutz, Regeln und DLP (Data Loss Prevention, Verhinderung von Datenverlust) bieten Exchange Online-Administratoren eine interaktive Umgebung für die Berichterstellung. Diese Berichte stellen Übersichtsinformationen und die Möglichkeit der Detailsuche in einzelnen Nachrichten zur Verfügung.
  
Weitere Informationen darüber, welche Berichte im Rahmen der verschiedenen Office 365-Abonnements jeweils zur Verfügung stehen, finden Sie unter [Berichte](../office-365-platform-service-description/reports.md). Ausführlichere Informationen zur Seite "Berichte" im Microsoft 365 Admin Center finden Sie unter [anzeigen und Herunterladen von Berichten zur Dienst Verwendung in office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) und [Verwenden von e-Mail-Schutz berichten in Office 365 zum Anzeigen von Daten über Schadsoftware, Spam und Regel Erfassungen ](https://go.microsoft.com/fwlink/p/?LinkID=401102).
  
### <a name="reporting-using-the-excel-reporting-workbook"></a>Berichte über die Excel-Arbeitsmappe mit Berichten

Sie können auch die Excel 2013-Berichtsarbeitsmappe verwenden, um Zusammenfassungsberichte mit Drilldownfunktionalitäten anzuzeigen. Es wird jedoch empfohlen, stattdessen die erweiterten Microsoft 365 Admin Center-Berichte zu verwenden. Die Excel 2013-Berichtsarbeitsmappe wird voraussichtlich in naher Zukunft eingestellt. Einen detaillierteren Überblick und Links zum Herunterladen und Installieren der Arbeitsmappe finden Sie auf [dieser Downloadseite](https://go.microsoft.com/fwlink/p/?LinkId=271776). Informationen zur Verwendung der Arbeitsmappe finden Sie unter [E-Mail-Schutzberichte in der Excel-Berichtsarbeitsmappe](https://go.microsoft.com/fwlink/p/?LinkId=285211). 
  
### <a name="reporting-using-web-services"></a>Berichterstattung mit Webservices

Zugriff auf Zusammenfassungs- und Detailberichte über Postfächer, Gruppen und Nachrichtendaten ist über den Webdienst "REST/OData Tenant Reporting" möglich. Bei diesem Dienst handelt es sich um eine programmgesteuerte Oberfläche, über die Sie benutzerdefinierte Berichte erstellen können. Weitere Informationen finden Sie unter [Office 365-Berichterstattungswebdienst](https://go.microsoft.com/fwlink/p/?LinkId=287041).
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a>Berichtsfeatures und Problembehandlungstools in der Exchange-Verwaltungskonsole

Die folgenden Berichtsfeatures und Problembehandlungstools stehen in der Exchange-Verwaltungskonsole zur Verfügung.
  
### <a name="trace-an-email-message"></a>Verfolgen einer E-Mail

Mit dem Feature für die Nachrichtenablaufverfolgung können Sie als Administrator E-Mails verfolgen, während sie Ihren Exchange Online-Dienst durchlaufen. Sie können damit bestimmen, ob eine bestimmte E-Mail vom Dienst empfangen, abgelehnt, zurückgestellt oder zugestellt wurde. So können Sie in effizienter Weise Fragen der Benutzer beantworten und Probleme mit dem Nachrichtenfluss behandeln und müssen seltener den technischen Support um Unterstützung bitten.
  
> [!IMPORTANT]
> Verwenden Sie für die Behandlung allgemeiner Probleme und Trends die Berichtstools, um solche Daten abzurufen. Verwenden Sie bei speziellen Besonderheiten, bei denen Details zu einer Nachricht erforderlich sind, das Tool für die Nachrichtenablaufverfolgung. 
  
Weitere Informationen zum Feature für die Nachrichtenablaufverfolgung finden Sie unter [Verfolgen einer E-Mail](https://go.microsoft.com/fwlink/p/?LinkId=271777).
  
### <a name="auditing-reports"></a>Überwachungsberichte

Sie können die Überwachungsprotokollierung zum Behandeln von Konfigurationsproblemen verwenden, indem Sie bestimmte von Administratoren vorgenommene Änderungen nachverfolgen. Außerdem können Sie damit gesetzliche Bestimmungen sowie Anforderungen an Richtlinientreue und Beweissicherungsverfahren einhalten. Von Exchange Online werden zwei Arten der Überwachungsprotokollierung bereitgestellt:
  
- Mit der Administrator-Überwachungsprotokollierung wird jede Aktion aufgezeichnet, die von einem Administrator durchgeführt wird. Diese Informationen können Sie zur Behandlung von Konfigurationsproblemen bzw. zum Ermitteln der Ursache von Sicherheits- oder Kompatibilitätsproblemen heranziehen. 
    
- Bei der Postfachüberwachungsprotokollierung werden alle Postfachzugriffe erfasst, die von Personen vorgenommen werden, bei denen es sich nicht um den Besitzer des Postfachs handelt. Dadurch können Sie feststellen, wer auf ein Postfach zugegriffen hat und welche Aktionen ausgeführt wurden. 
    
Weitere Informationen zur Überwachungsprotokollierung finden Sie im Artikel zum Thema [Überwachungsberichte](https://go.microsoft.com/fwlink/p/?LinkId=271779).
  
### <a name="unified-messaging-reports"></a>Unified Messaging-Berichte

Mithilfe dieser Berichte können Sie Unified Messaging (UM) in Ihrer Exchange Online-Organisation überwachen und Probleme beheben. Weitere Informationen finden Sie im Artikel zum Thema [Erstellen von Berichten für Voicemailanrufe](https://go.microsoft.com/fwlink/p/?LinkId=287042).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description.md).
  

