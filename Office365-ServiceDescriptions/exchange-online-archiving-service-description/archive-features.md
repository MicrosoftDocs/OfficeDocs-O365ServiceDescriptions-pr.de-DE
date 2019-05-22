---
title: Archivfunktionen in der Exchange Online-Archivierung
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/11/2019
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: In den folgenden Abschnitten werden die Archivfunktionen Microsoft Exchange Online Archivierung beschrieben.
ms.openlocfilehash: 3c11d5a9fccb05f027e5030c34eb9171295bfb1b
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341914"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="2097f-103">Archivfunktionen in der Exchange Online-Archivierung</span><span class="sxs-lookup"><span data-stu-id="2097f-103">Archive Features in Exchange Online Archiving</span></span>

<span data-ttu-id="2097f-104">In den folgenden Abschnitten werden die Archivfunktionen Microsoft Exchange Online Archivierung beschrieben.</span><span class="sxs-lookup"><span data-stu-id="2097f-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="2097f-105">Archivpostfach</span><span class="sxs-lookup"><span data-stu-id="2097f-105">Archive mailbox</span></span>

<span data-ttu-id="2097f-p101">Exchange Online-Archivierung bietet Benutzern mit der Archivpostfachfunktion erweiterte Archivierungsfunktionen. Ein Archivpostfach ist ein spezielles Postfach, das in Outlook oder Outlook Web App neben den primären Postfachordnern eines Benutzers angezeigt wird. Benutzer können auf das Archiv auf die gleiche Weise zugreifen, wie sie auf ihre primären Postfachordner zugreifen. Darüber hinaus können sie ihre Archive und primären Postfächer durchsuchen.</span><span class="sxs-lookup"><span data-stu-id="2097f-p101">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature. An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook Web App. Users can access the archive in the same way that they access their primary mailboxes. In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="2097f-p102">Administratoren können die Archivfunktion mithilfe des Exchange Admin Center (EAC) oder der remote verwendeten Windows PowerShell für bestimmte Benutzer archivieren. Weitere Informationen finden Sie unter [Aktivieren und Deaktivieren von Archivpostfächern in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span><span class="sxs-lookup"><span data-stu-id="2097f-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="2097f-p103">Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung zu Exchange Online-Archivierung zu kopieren. >  Das Archivpostfach eines Benutzers ist nur für diesen Benutzer vorgesehen. Microsoft behält sich das Recht vor, die uneingeschränkte Archivierung dann zu verweigern, wenn das Archivpostfach eines Benutzers zum Speichern von Archivdaten für andere Benutzer verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="2097f-p103">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted. >  A user's archive mailbox is intended for just that user. Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users.</span></span> 
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="2097f-115">Verschieben von Nachrichten zur Exchange Online-Archivierung</span><span class="sxs-lookup"><span data-stu-id="2097f-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="2097f-116">Benutzer können Nachrichten für einfachen Onlinezugriff aus PST-Dateien per Drag & Drop in das Archiv verschieben.</span><span class="sxs-lookup"><span data-stu-id="2097f-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="2097f-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span><span class="sxs-lookup"><span data-stu-id="2097f-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="2097f-118">Importieren von Daten in das Archiv</span><span class="sxs-lookup"><span data-stu-id="2097f-118">Import data to the archive</span></span>

<span data-ttu-id="2097f-119">Benutzer haben folgende Möglichkeiten, um Daten in das Archiv zu importieren:</span><span class="sxs-lookup"><span data-stu-id="2097f-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="2097f-120">Importieren von Daten aus einer PST-Datei mithilfe des Import/Export-Assistenten von Outlook.</span><span class="sxs-lookup"><span data-stu-id="2097f-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="2097f-121">Ziehen von E-Mail-Nachrichten aus PST-Dateien in das Archiv.</span><span class="sxs-lookup"><span data-stu-id="2097f-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="2097f-122">Ziehen von E-Mails aus dem primären Postfach in das Archiv.</span><span class="sxs-lookup"><span data-stu-id="2097f-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="2097f-p105">Archivrichtlinien automatisch E-Mail-Nachrichten je nach Alter der Nachrichten vom primären Postfach verschieben lassen. Weitere Informationen finden Sie unter [Aufbewahrungstags und Aufbewahrungsrichtlinien](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span><span class="sxs-lookup"><span data-stu-id="2097f-p105">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span></span>
    
> [!NOTE]
> <span data-ttu-id="2097f-p106">Administratoren können auch den Office 365-Importdienst verwenden, um PST-Dateien in cloudbasierte Archivpostfächer der Benutzer zu importieren. Weitere Informationen finden Sie unter [Verwenden des Netzwerkuploads zum Importieren von PST-Dateien in Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span><span class="sxs-lookup"><span data-stu-id="2097f-p106">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="2097f-127">Wiederherstellung gelöschter Elemente</span><span class="sxs-lookup"><span data-stu-id="2097f-127">Deleted item recovery</span></span>

<span data-ttu-id="2097f-p107">Benutzer können Elemente wiederherstellen, die sie aus einem E-Mail-Ordner in ihrem Archiv gelöscht haben. Wenn ein Element gelöscht wird, wird es im Ordner "Gelöschte Elemente" des Archivs aufbewahrt. Es wird dort so lange gespeichert, bis es vom Benutzer automatisch verschoben oder durch Aufbewahrungsrichtlinien automatisch entfernt wird.</span><span class="sxs-lookup"><span data-stu-id="2097f-p107">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="2097f-p108">Nachdem ein Element aus dem Ordner "Gelöschte Elemente" des Archivs gelöscht wurde, wird das Element im Ordner "Wiederherstellbare Elemente" des Archivs weitere 14 Tage lang aufbewahrt, bevor es endgültig gelöscht wird. Benutzer können diese Elemente mithilfe der Funktion **Gelöschte Objekte wiederherstellen** in Microsoft Outlook oder Outlook Web App wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="2097f-p108">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook Web App.</span></span> 
  
<span data-ttu-id="2097f-p109">Wenn ein Benutzer ein Element manuell aus dem Ordner „Wiederherstellbare Elemente" gelöscht hat, kann ein Administrator das Element innerhalb des gleichen 14-Tage-Zeitfensters mithilfe des Features „Wiederherstellung einzelner Elemente" wiederherstellen. Dieses Feature erlaubt Administratoren, eine Suche in mehreren Postfächern durchzuführen, um gelöschte Elemente zu finden, und dann mithilfe des Windows PowerShell-Cmdlets  `Search-Mailbox` die Elemente aus dem Discoverypostfach in die Postfächer von Benutzern zu verschieben. Weitere Informationen finden Sie unter [Aktivieren oder Deaktivieren der Wiederherstellung einzelner Elemente für ein Postfach](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span><span class="sxs-lookup"><span data-stu-id="2097f-p109">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="2097f-p110">Der Zeitraum für die Wiederherstellung einzelner Elemente beträgt standardmäßig 14 Tage, kann aber in einigen Fällen angepasst werden. >  Wenn ein Administrator das Postfach eines Benutzers in einem Compliance-Archiv platziert hat oder für ein Beweissicherungsverfahren aktiviert hat, werden gelöschte Elemente auf unbegrenzte Zeit gespeichert, und das 14-Tage-Zeitfenster gilt nicht.</span><span class="sxs-lookup"><span data-stu-id="2097f-p110">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances. >  If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="2097f-138">Wiederherstellung gelöschter Postfächer</span><span class="sxs-lookup"><span data-stu-id="2097f-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="2097f-p111">Wenn Administratoren Benutzer auf dem lokalen Exchange Server löschen, werden auch die Archive der Benutzer gelöscht. Wenn die gelöschten Archivpostfächer wiederhergestellt werden müssen, kann das Office 365-Supportteam diese Wiederherstellung durchführen. Ein wiederhergestelltes Archiv enthält alle E-Mails, die darin gespeichert waren, als es gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="2097f-p111">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted. If the deleted archive mailboxes need to be recovered, the Office 365 support team can perform this recovery. A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="2097f-p112">Administratoren haben ab dem Zeitpunkt, an dem das Postfach eines Benutzers gelöscht wird, 30 Tage Zeit, um die Wiederherstellung eines Archivpostfachs anzufordern. Nach 30 Tagen kann das Archivpostfach nicht mehr wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="2097f-p112">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="2097f-144">Redundanz von Postfachdiensten</span><span class="sxs-lookup"><span data-stu-id="2097f-144">Mailbox service redundancy</span></span>

<span data-ttu-id="2097f-145">Archivpostfächer in Exchange Online-Archivierung werden in mehreren Datenbankkopien in geografisch verteilten Microsoft-Datencentern repliziert, um eine Datenwiederherstellung zu ermöglichen, falls eine Nachrichteninfrastruktur ausfällt.</span><span class="sxs-lookup"><span data-stu-id="2097f-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="2097f-146">Bei umfangreicheren Ausfällen wird Geschäftskontinuitätsmanagement initiiert.</span><span class="sxs-lookup"><span data-stu-id="2097f-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="2097f-147">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="2097f-147">Feature Availability</span></span>

<span data-ttu-id="2097f-148">Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Beschreibung des Exchange Online-Archivierungsdiensts](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="2097f-148">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  
