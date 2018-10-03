---
title: Berichterstellung und Nachrichtenablaufverfolgung
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- reporting-and-message-trace-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: b9263f99-5921-44fd-bb4c-0d487b59a656
description: Microsoft Exchange Online Protection (EOP) bietet zahlreiche verschiedene Berichte, die Ihnen helfen können des allgemeinen Status und die Integrität Ihrer Organisation bestimmen. Einige Berichte stehen im Microsoft Office 365 Administrationscenter, während andere in der Exchange-Verwaltungskonsole (EAC) verfügbar sind.
ms.openlocfilehash: ead40ff8932d6f10ca91bd871e34ef9070c6b2db
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035883"
---
# <a name="reporting-and-message-trace"></a><span data-ttu-id="c00c0-104">Berichterstellung und Nachrichtenablaufverfolgung</span><span class="sxs-lookup"><span data-stu-id="c00c0-104">Reporting and Message Trace</span></span>

<span data-ttu-id="c00c0-p102">Microsoft Exchange Online Protection (EOP) bietet zahlreiche verschiedene Berichte, die Ihnen helfen können des allgemeinen Status und die Integrität Ihrer Organisation bestimmen. Einige Berichte stehen im Microsoft Office 365 Administrationscenter, während andere in der Exchange-Verwaltungskonsole (EAC) verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="c00c0-p102">Microsoft Exchange Online Protection (EOP) offers many different reports that can help you determine the overall status and health of your organization. Some reports are available in the Microsoft Office 365 admin center, while others are available in the Exchange admin center (EAC).</span></span>
  
<span data-ttu-id="c00c0-p103">Sie suchen nach Informationen zu allen EOP-Features? Entsprechendes finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="c00c0-p103">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="office-365-admin-center-reports"></a><span data-ttu-id="c00c0-109">Office 365 Admin Center-Berichte</span><span class="sxs-lookup"><span data-stu-id="c00c0-109">Office 365 admin center reports</span></span>
<span data-ttu-id="c00c0-110"><a name="BKMK_office365admincenterreports"> </a></span><span class="sxs-lookup"><span data-stu-id="c00c0-110"></span></span>

<span data-ttu-id="c00c0-p104">Die Seite "Berichte" im Office 365 Admin Center stellt Informationen über den Nachrichtenverkehr, Spam- und Schadsoftwareerkennungen sowie über Nachrichten bereit, die durch die Exchange-Transportregel oder DLP-Richtlinien (Data Lost Prevention, Verhinderung von Datenverlust) betroffen sind. Die erweiterten Berichte zu Schutz, Regeln und DLP bieten eine interaktive Berichterstellungserfahrung für EOP-Administratoren. Diese Berichte stellen Übersichtsinformationen und die Möglichkeit der Detailsuche in einzelnen Nachrichten zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="c00c0-p104">The Reports page in the Office 365 admin center provides information about message traffic, spam and malware detections, and messages affected by Exchange Transport Rules or Data Loss Prevention (DLP) policies. The enhanced reports for protection, rules, and DLP offer an interactive reporting experience for EOP admins. These reports provide summary data and the ability to drill down into details about individual messages.</span></span>
  
<span data-ttu-id="c00c0-114">Detailliertere Informationen über diese Berichte finden Sie unter [Verwenden von Berichten zum E-Mail-Schutz in Office 365, um Daten über Schadsoftware, Spam und Regelerkennung anzuzeigen](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span><span class="sxs-lookup"><span data-stu-id="c00c0-114">For more detailed information about these reports, see [Use mail protection reports in Office 365 to view data about malware, spam and rule detections](https://go.microsoft.com/fwlink/p/?LinkID=401102).</span></span>
  
## <a name="excel-download-application-reports"></a><span data-ttu-id="c00c0-115">Berichte der Excel-Downloadanwendung</span><span class="sxs-lookup"><span data-stu-id="c00c0-115">Excel download application reports</span></span>
<span data-ttu-id="c00c0-116"><a name="BKMK_exceldownloadapplicationreports"> </a></span><span class="sxs-lookup"><span data-stu-id="c00c0-116"></span></span>

<span data-ttu-id="c00c0-p105">E-Mail-Schutzberichte sind auch in der Excel 2013-Berichtsarbeitsmappe verfügbar, welche Zusammenfassungsberichte mit Drilldownfunktionen bereitstellt. Wir empfehlen jedoch, die erweiterten Office 365 Admin Center-Berichte zu verwenden. Die Excel 2013-Berichtsarbeitsmappe wird voraussichtlich in naher Zukunft eingestellt.</span><span class="sxs-lookup"><span data-stu-id="c00c0-p105">Email protection reports are also available in the Excel 2013 reporting workbook, which provides summary reports with drill-down capabilities. However, we recommend using the enhanced Office 365 admin center reports instead. The Excel 2013 reporting workbook is planned to be deprecated in the future.</span></span> 
  
<span data-ttu-id="c00c0-p106">Weitere Übersichtsinformationen sowie Links zum Herunterladen und Installieren der Arbeitsmappe finden Sie unter [Mail Protection Reports for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271776). Informationen zur Verwendung der Arbeitsmappe finden Sie unter [E-Mail-Schutzberichte in der Excel-Berichtsarbeitsmappe](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span><span class="sxs-lookup"><span data-stu-id="c00c0-p106">For more overview information and links to download and install the workbook, see [Mail Protection Reports for Office 365](https://go.microsoft.com/fwlink/p/?LinkId=271776). For information about how to use the workbook, see [Mail Protection Reports Using the Excel Reporting Workbook](https://go.microsoft.com/fwlink/p/?LinkId=285211).</span></span>
  
## <a name="reporting-using-web-services"></a><span data-ttu-id="c00c0-122">Berichterstellung mit Webdiensten</span><span class="sxs-lookup"><span data-stu-id="c00c0-122">Reporting using web services</span></span>
<span data-ttu-id="c00c0-123"><a name="BKMK_reportingusingwebservices"> </a></span><span class="sxs-lookup"><span data-stu-id="c00c0-123"></span></span>

<span data-ttu-id="c00c0-p107">Nicht verfügbar für Kunden der eigenständigen EOP-Lösung. Sie können mit dem Webdienst "REST/OData Tenant Reporting" programmgesteuert Zusammenfassungs- und Detailberichte über Nachrichtendaten erfassen und die Daten auf einer Webseite in einem benutzerdefinierten Webportal für die Verwaltung anzeigen. Weitere Informationen finden Sie unter [Office 365-Berichterstattungswebdienst](https://go.microsoft.com/fwlink/?LinkId=279926).</span><span class="sxs-lookup"><span data-stu-id="c00c0-p107">Not available to EOP standalone customers. You can use the REST/OData Tenant Reporting Web service to programmatically collect summary and detailed reports about messaging data, and you can display the data on a web page in a custom management Web portal. For more information, see [Office 365 Reporting Web Services](https://go.microsoft.com/fwlink/?LinkId=279926).</span></span>
  
## <a name="message-trace"></a><span data-ttu-id="c00c0-127">Nachrichtenablaufverfolgung</span><span class="sxs-lookup"><span data-stu-id="c00c0-127">Message trace</span></span>
<span data-ttu-id="c00c0-128"><a name="BKMK_messagetrace"> </a></span><span class="sxs-lookup"><span data-stu-id="c00c0-128"></span></span>

<span data-ttu-id="c00c0-p108">Mit dem Feature für die Nachrichtenablaufverfolgung im EAC können Sie als Administrator E-Mails verfolgen, während sie den EOP-Dienst durchlaufen. So können Sie herausfinden, ob eine bestimmte E-Mail vom Dienst empfangen, abgelehnt, zurückgestellt oder zugestellt wurde. Außerdem werden alle Aktionen angezeigt, die auf die Nachricht angewendet wurden, bevor sie ihren finalen Status erreicht hat. Mithilfe ausführlicher Informationen zu bestimmten Nachrichten können Sie in effizienter Weise Fragen der Benutzer beantworten, Probleme mit dem Nachrichtenfluss behandeln und Richtlinienänderungen überprüfen. Außerdem müssen Sie seltener den technischen Support um Unterstützung bitten. Weitere Informationen finden Sie unter [Verfolgen einer E-Mail](https://go.microsoft.com/fwlink/p/?LinkID=282262).</span><span class="sxs-lookup"><span data-stu-id="c00c0-p108">The message trace feature in the EAC enables you as an administrator to follow email messages as they pass through the EOP. It helps you determine whether a targeted email message was received, rejected, deferred, or delivered by the service. It also shows what actions have occurred to the message before reaching its final status. Obtaining detailed information about a specific message lets you efficiently answer your user's questions, troubleshoot mail flow issues, validate policy changes, and alleviates the need to contact technical support for assistance. For more information, see [Trace an Email Message](https://go.microsoft.com/fwlink/p/?LinkID=282262).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="c00c0-134">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="c00c0-134">Feature Availability</span></span>
<span data-ttu-id="c00c0-135"><a name="BKMK_messagetrace"> </a></span><span class="sxs-lookup"><span data-stu-id="c00c0-135"></span></span>

<span data-ttu-id="c00c0-136">Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="c00c0-136">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
