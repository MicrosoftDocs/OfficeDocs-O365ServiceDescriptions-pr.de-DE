---
title: Berichterstellungsfeatures und Tools zur Problembehandlung
ms.author: pebaum
author: pebaum
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
description: Microsoft Exchange Online bietet eine Vielzahl von Berichtsfunktionen, die innerhalb und außerhalb der Exchange-Verwaltungskonsole (EAC).
ms.openlocfilehash: b95ab58d2ec09f5e6bae32a3902e92deb75d789f
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035765"
---
# <a name="reporting-features-and-troubleshooting-tools"></a><span data-ttu-id="a469d-103">Berichterstellungsfeatures und Tools zur Problembehandlung</span><span class="sxs-lookup"><span data-stu-id="a469d-103">Reporting Features and Troubleshooting Tools</span></span>

<span data-ttu-id="a469d-104">Microsoft Exchange Online bietet eine Vielzahl von Berichtsfunktionen, die innerhalb und außerhalb der Exchange-Verwaltungskonsole (EAC).</span><span class="sxs-lookup"><span data-stu-id="a469d-104">Microsoft Exchange Online offers a variety of reporting features both in and out of the Exchange admin center (EAC).</span></span>
  
## <a name="reporting-features"></a><span data-ttu-id="a469d-105">Berichtsfeatures</span><span class="sxs-lookup"><span data-stu-id="a469d-105">Reporting features</span></span>

<span data-ttu-id="a469d-106">Exchange Online-Kunden können auf die Berichte im Office 365 Admin Center, durch Herunterladen einer Excel-Arbeitsmappe mit Berichten oder über Webdienste zugreifen.</span><span class="sxs-lookup"><span data-stu-id="a469d-106">Exchange Online customers can access reports in the Office 365 admin center, by downloading an Excel reporting workbook, or by using Web services.</span></span>
  
### <a name="reporting-in-the-office-365-admin-center"></a><span data-ttu-id="a469d-107">Berichte im Office 365 Admin Center</span><span class="sxs-lookup"><span data-stu-id="a469d-107">Reporting in the Office 365 admin center</span></span>

<span data-ttu-id="a469d-p101">Die Berichte auf der Seite "Berichte" im Microsoft Office 365 Admin Center bieten zusammenfassende Informationen zu Postfächern und Gruppen. Beispielsweise wird in einem Bericht die Anzahl der Gruppen aufgeführt, die pro Tag, Woche, Monat oder Jahr erstellt und gelöscht wurden. Es gibt auch Zusammenfassungsberichte für neue und gelöschte sowie aktive und inaktive Postfächer.</span><span class="sxs-lookup"><span data-stu-id="a469d-p101">There are reports on the Reports page in the Microsoft Office 365 admin center that provide summary information about mailboxes and groups. For example, one report lists the number of groups created and deleted by day, week, month, or year. There are also summary reports for new and deleted mailboxes, and active and inactive mailboxes.</span></span> 
  
<span data-ttu-id="a469d-p102">Darüber hinaus enthält die Seite "Berichte" im Microsoft Office 365 Admin Center Berichte mit Nachrichtendaten, die Informationen zur Erkennung von Nachrichtenverkehr, Spam und Schadsoftware sowie zu Nachrichten, die von Exchange-Transportregeln oder DLP-Richtlinien (Data Loss Prevention, Verhinderung von Datenverlust) betroffen waren, bereitstellen. Die optimierten Berichte zu Schutz, Regeln und DLP (Data Loss Prevention, Verhinderung von Datenverlust) bieten Exchange Online-Administratoren eine interaktive Umgebung für die Berichterstellung. Diese Berichte stellen Übersichtsinformationen und die Möglichkeit der Detailsuche in einzelnen Nachrichten zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="a469d-p102">Additionally, the Reports page in the Microsoft Office 365 admin center contains messaging data reports, which provide information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies. The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for Exchange Online admins. These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="a469d-p103">Weitere Informationen darüber, welche Berichte im Rahmen der verschiedenen Office 365-Abonnements jeweils zur Verfügung stehen, finden Sie unter [Berichte](../office-365-platform-service-description/reports.md). Detailliertere Informationen über die Seite "Berichte" im Office 365 Admin Center finden Sie im Artikel zum Thema [Anzeigen und Herunterladen von Berichten über die Verwendung von Diensten in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) sowie unter [Verwenden von Berichten zum E-Mail-Schutz in Office 365, um Daten über Schadsoftware, Spam und Regelerkennung anzuzeigen](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span><span class="sxs-lookup"><span data-stu-id="a469d-p103">For more information about which reports are available with each Office 365 subscription, see [Reports](../office-365-platform-service-description/reports.md). For more detailed information about the Reports page in the Office 365 admin center, see [View and download reports about service usage in Office 365](https://go.microsoft.com/fwlink/p/?LinkId=401187) and [Use mail protection reports in Office 365 to view data about malware, spam, and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
### <a name="reporting-using-the-excel-reporting-workbook"></a><span data-ttu-id="a469d-116">Berichte über die Excel-Arbeitsmappe mit Berichten</span><span class="sxs-lookup"><span data-stu-id="a469d-116">Reporting using the Excel reporting workbook</span></span>

<span data-ttu-id="a469d-p104">Sie können auch die Excel 2013-Berichtsarbeitsmappe verwenden, um Zusammenfassungsberichte mit Drilldownfunktionalitäten anzuzeigen. Wir empfehlen jedoch, die erweiterten Office 365 Admin Center-Berichte zu verwenden. Die Excel 2013-Berichtsarbeitsmappe wird voraussichtlich in naher Zukunft eingestellt. Einen detaillierteren Überblick und Links zum Herunterladen und Installieren der Arbeitsmappe finden Sie auf [dieser Downloadseite](https://go.microsoft.com/fwlink/p/?LinkId=271776). Informationen zur Verwendung der Arbeitsmappe finden Sie unter [E-Mail-Schutzberichte in der Excel-Berichtsarbeitsmappe](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span><span class="sxs-lookup"><span data-stu-id="a469d-p104">You can also use the Excel 2013 reporting workbook to view summary reports with drill-down capabilities. However, we recommend using the enhanced Office 365 admin center reports instead. The Excel 2013 reporting workbook is planned to be deprecated in the future. For more overview information and links to download and install the workbook, see the following [download page](https://go.microsoft.com/fwlink/p/?LinkId=271776). For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span> 
  
### <a name="reporting-using-web-services"></a><span data-ttu-id="a469d-122">Berichterstattung mit Webservices</span><span class="sxs-lookup"><span data-stu-id="a469d-122">Reporting using Web services</span></span>

<span data-ttu-id="a469d-p105">Zugriff auf Zusammenfassungs- und Detailberichte über Postfächer, Gruppen und Nachrichtendaten ist über den Webdienst "REST/OData Tenant Reporting" möglich. Bei diesem Dienst handelt es sich um eine programmgesteuerte Oberfläche, über die Sie benutzerdefinierte Berichte erstellen können. Weitere Informationen finden Sie unter [Office 365-Berichterstattungswebdienst](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span><span class="sxs-lookup"><span data-stu-id="a469d-p105">Access to both summary and detailed reports about mailboxes, groups, and messaging data is available by using the REST/OData Tenant Reporting Web service, which is a programmatic interface that enables you to create custom reports. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/p/?LinkId=287041).</span></span>
  
## <a name="reporting-features-and-troubleshooting-tools-in-the-eac"></a><span data-ttu-id="a469d-125">Berichtsfeatures und Problembehandlungstools in der Exchange-Verwaltungskonsole</span><span class="sxs-lookup"><span data-stu-id="a469d-125">Reporting features and troubleshooting tools in the EAC</span></span>

<span data-ttu-id="a469d-126">Die folgenden Berichtsfeatures und Problembehandlungstools stehen in der Exchange-Verwaltungskonsole zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="a469d-126">The following reporting features and troubleshooting tools are available in the Exchange admin center.</span></span>
  
### <a name="trace-an-email-message"></a><span data-ttu-id="a469d-127">Verfolgen einer E-Mail</span><span class="sxs-lookup"><span data-stu-id="a469d-127">Trace an email message</span></span>

<span data-ttu-id="a469d-p106">Mit dem Feature für die Nachrichtenablaufverfolgung können Sie als Administrator E-Mails verfolgen, während sie Ihren Exchange Online-Dienst durchlaufen. Sie können damit bestimmen, ob eine bestimmte E-Mail vom Dienst empfangen, abgelehnt, zurückgestellt oder zugestellt wurde. So können Sie in effizienter Weise Fragen der Benutzer beantworten und Probleme mit dem Nachrichtenfluss behandeln und müssen seltener den technischen Support um Unterstützung bitten.</span><span class="sxs-lookup"><span data-stu-id="a469d-p106">The message trace feature enables you as an administrator to follow email messages as they pass through your Exchange Online service. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. This lets you efficiently answer your users' questions and troubleshoot mail flow issues, and alleviates the need to contact technical support for assistance.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="a469d-p107">Verwenden Sie für die Behandlung allgemeiner Probleme und Trends die Berichtstools, um solche Daten abzurufen. Verwenden Sie bei speziellen Besonderheiten, bei denen Details zu einer Nachricht erforderlich sind, das Tool für die Nachrichtenablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="a469d-p107">For troubleshooting general issues and trends, use the reporting tools to obtain such data. For single point specifics where details are needed about a message, use the message trace tool.</span></span> 
  
<span data-ttu-id="a469d-133">Weitere Informationen zum Feature für die Nachrichtenablaufverfolgung finden Sie unter [Verfolgen einer E-Mail](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span><span class="sxs-lookup"><span data-stu-id="a469d-133">For more information about the message trace feature, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkId=271777).</span></span>
  
### <a name="auditing-reports"></a><span data-ttu-id="a469d-134">Überwachungsberichte</span><span class="sxs-lookup"><span data-stu-id="a469d-134">Auditing reports</span></span>

<span data-ttu-id="a469d-p108">Sie können die Überwachungsprotokollierung zum Behandeln von Konfigurationsproblemen verwenden, indem Sie bestimmte von Administratoren vorgenommene Änderungen nachverfolgen. Außerdem können Sie damit gesetzliche Bestimmungen sowie Anforderungen an Richtlinientreue und Beweissicherungsverfahren einhalten. Von Exchange Online werden zwei Arten der Überwachungsprotokollierung bereitgestellt:</span><span class="sxs-lookup"><span data-stu-id="a469d-p108">You can use audit logging to troubleshoot configuration issues by tracking specific changes made by administrators and to help you meet regulatory, compliance, and litigation requirements. Exchange Online provides two types of audit logging:</span></span>
  
- <span data-ttu-id="a469d-p109">Mit der Administrator-Überwachungsprotokollierung wird jede Aktion aufgezeichnet, die von einem Administrator durchgeführt wird. Diese Informationen können Sie zur Behandlung von Konfigurationsproblemen bzw. zum Ermitteln der Ursache von Sicherheits- oder Kompatibilitätsproblemen heranziehen.</span><span class="sxs-lookup"><span data-stu-id="a469d-p109">Administrator audit logging records any action performed by an administrator. This can help you troubleshoot configuration issues or identify the cause of security-related or compliance-related problems.</span></span> 
    
- <span data-ttu-id="a469d-p110">Bei der Postfachüberwachungsprotokollierung werden alle Postfachzugriffe erfasst, die von Personen vorgenommen werden, bei denen es sich nicht um den Besitzer des Postfachs handelt. Dadurch können Sie feststellen, wer auf ein Postfach zugegriffen hat und welche Aktionen ausgeführt wurden.</span><span class="sxs-lookup"><span data-stu-id="a469d-p110">Mailbox audit logging records whenever a mailbox is accessed by someone other than the person who owns the mailbox. This can help you determine who has accessed a mailbox and what they've done.</span></span> 
    
<span data-ttu-id="a469d-141">Weitere Informationen zur Überwachungsprotokollierung finden Sie im Artikel zum Thema [Überwachungsberichte](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span><span class="sxs-lookup"><span data-stu-id="a469d-141">For more information about audit logging, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=271779).</span></span>
  
### <a name="unified-messaging-reports"></a><span data-ttu-id="a469d-142">Unified Messaging-Berichte</span><span class="sxs-lookup"><span data-stu-id="a469d-142">Unified Messaging reports</span></span>

<span data-ttu-id="a469d-p111">Mithilfe dieser Berichte können Sie Unified Messaging (UM) in Ihrer Exchange Online-Organisation überwachen und Probleme beheben. Weitere Informationen finden Sie im Artikel zum Thema [Erstellen von Berichten für Voicemailanrufe](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span><span class="sxs-lookup"><span data-stu-id="a469d-p111">You can use these reports to monitor and troubleshoot Unified Messaging (UM) in your Exchange Online organization. For more information, see [Run Reports for Voice Mail Calls](https://go.microsoft.com/fwlink/p/?LinkId=287042).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="a469d-145">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="a469d-145">Feature Availability</span></span>

<span data-ttu-id="a469d-146">Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="a469d-146">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

