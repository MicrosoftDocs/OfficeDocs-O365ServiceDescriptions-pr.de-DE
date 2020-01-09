---
title: Archivfunktionen in Exchange Online Archivierung
ms.author: sharik
author: skjerland
manager: mnirkhe
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
ms.openlocfilehash: aa3a43a0af668f84adaf14c69ad5b38d7c5cb1eb
ms.sourcegitcommit: 0abb96f4771fd2e2a674589059ddc43c50f55d98
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/08/2020
ms.locfileid: "40987577"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="dee2a-103">Archivfunktionen in Exchange Online Archivierung</span><span class="sxs-lookup"><span data-stu-id="dee2a-103">Archive features in Exchange Online Archiving</span></span>

<span data-ttu-id="dee2a-104">In den folgenden Abschnitten werden die Archivfunktionen Microsoft Exchange Online Archivierung beschrieben.</span><span class="sxs-lookup"><span data-stu-id="dee2a-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="dee2a-105">Archivpostfach</span><span class="sxs-lookup"><span data-stu-id="dee2a-105">Archive mailbox</span></span>

<span data-ttu-id="dee2a-106">Exchange Online-Archivierung bietet Benutzern mit der Archivpostfachfunktion erweiterte Archivierungsfunktionen.</span><span class="sxs-lookup"><span data-stu-id="dee2a-106">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature.</span></span> <span data-ttu-id="dee2a-107">Bei einem Archivpostfach handelt es sich um ein spezielles Postfach, das neben den primären Postfachordnern der Benutzer in Outlook oder Outlook im Internet angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="dee2a-107">An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook on the web.</span></span> <span data-ttu-id="dee2a-108">Benutzer können auf das Archiv auf die gleiche Weise zugreifen, wie sie auf ihre primären Postfachordner zugreifen.</span><span class="sxs-lookup"><span data-stu-id="dee2a-108">Users can access the archive in the same way that they access their primary mailboxes.</span></span> <span data-ttu-id="dee2a-109">Darüber hinaus können sie ihre Archive und primären Postfächer durchsuchen.</span><span class="sxs-lookup"><span data-stu-id="dee2a-109">In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="dee2a-p102">Administratoren können die Archivfunktion mithilfe des Exchange Admin Center (EAC) oder der remote verwendeten Windows PowerShell für bestimmte Benutzer archivieren. Weitere Informationen finden Sie unter [Aktivieren und Deaktivieren von Archivpostfächern in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="dee2a-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="dee2a-112">Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung zu Exchange Online-Archivierung zu kopieren.</span><span class="sxs-lookup"><span data-stu-id="dee2a-112">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted.</span></span> <br/>
>  <span data-ttu-id="dee2a-113">Das Archivpostfach eines Benutzers ist nur für diesen Benutzer vorgesehen.</span><span class="sxs-lookup"><span data-stu-id="dee2a-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="dee2a-114">Microsoft behält sich das Recht vor, eine unbegrenzte Archivierung in Fällen zu verweigern, in denen das Archivpostfach eines Benutzers zum Speichern von Archivdaten für andere Benutzer oder in anderen Fällen ungeeigneter Verwendung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="dee2a-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users or in other cases of inappropriate use.</span></span>
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="dee2a-115">Verschieben von Nachrichten zur Exchange Online-Archivierung</span><span class="sxs-lookup"><span data-stu-id="dee2a-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="dee2a-116">Benutzer können Nachrichten für einfachen Onlinezugriff aus PST-Dateien per Drag & Drop in das Archiv verschieben.</span><span class="sxs-lookup"><span data-stu-id="dee2a-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="dee2a-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span><span class="sxs-lookup"><span data-stu-id="dee2a-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="dee2a-118">Importieren von Daten in das Archiv</span><span class="sxs-lookup"><span data-stu-id="dee2a-118">Import data to the archive</span></span>

<span data-ttu-id="dee2a-119">Benutzer haben folgende Möglichkeiten, um Daten in das Archiv zu importieren:</span><span class="sxs-lookup"><span data-stu-id="dee2a-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="dee2a-120">Importieren von Daten aus einer PST-Datei mithilfe des Import/Export-Assistenten von Outlook.</span><span class="sxs-lookup"><span data-stu-id="dee2a-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="dee2a-121">Ziehen von E-Mail-Nachrichten aus PST-Dateien in das Archiv.</span><span class="sxs-lookup"><span data-stu-id="dee2a-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="dee2a-122">Ziehen von E-Mails aus dem primären Postfach in das Archiv.</span><span class="sxs-lookup"><span data-stu-id="dee2a-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="dee2a-p106">Archivrichtlinien automatisch E-Mail-Nachrichten je nach Alter der Nachrichten vom primären Postfach verschieben lassen. Weitere Informationen finden Sie unter [Aufbewahrungstags und Aufbewahrungsrichtlinien](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span><span class="sxs-lookup"><span data-stu-id="dee2a-p106">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="dee2a-p107">Administratoren können auch den Office 365-Importdienst verwenden, um PST-Dateien in cloudbasierte Archivpostfächer der Benutzer zu importieren. Weitere Informationen finden Sie unter [Verwenden des Netzwerkuploads zum Importieren von PST-Dateien in Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="dee2a-p107">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="dee2a-127">Wiederherstellung gelöschter Elemente</span><span class="sxs-lookup"><span data-stu-id="dee2a-127">Deleted item recovery</span></span>

<span data-ttu-id="dee2a-p108">Benutzer können Elemente wiederherstellen, die sie aus einem E-Mail-Ordner in ihrem Archiv gelöscht haben. Wenn ein Element gelöscht wird, wird es im Ordner "Gelöschte Elemente" des Archivs aufbewahrt. Es wird dort so lange gespeichert, bis es vom Benutzer automatisch verschoben oder durch Aufbewahrungsrichtlinien automatisch entfernt wird.</span><span class="sxs-lookup"><span data-stu-id="dee2a-p108">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="dee2a-131">Nachdem ein Element aus dem Ordner "Gelöschte Elemente" des Archivs gelöscht wurde, wird das Element im Ordner "Wiederherstellbare Elemente" des Archivs weitere 14 Tage lang aufbewahrt, bevor es endgültig gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="dee2a-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span></span> <span data-ttu-id="dee2a-132">Benutzer können diese Elemente mithilfe der Funktion **Gelöschte Elemente wiederherstellen** in Microsoft Outlook oder Outlook im Internet wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="dee2a-132">Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook on the web.</span></span> 
  
<span data-ttu-id="dee2a-p110">Wenn ein Benutzer ein Element manuell aus dem Ordner „Wiederherstellbare Elemente" gelöscht hat, kann ein Administrator das Element innerhalb des gleichen 14-Tage-Zeitfensters mithilfe des Features „Wiederherstellung einzelner Elemente" wiederherstellen. Dieses Feature erlaubt Administratoren, eine Suche in mehreren Postfächern durchzuführen, um gelöschte Elemente zu finden, und dann mithilfe des Windows PowerShell-Cmdlets  `Search-Mailbox` die Elemente aus dem Discoverypostfach in die Postfächer von Benutzern zu verschieben. Weitere Informationen finden Sie unter [Aktivieren oder Deaktivieren der Wiederherstellung einzelner Elemente für ein Postfach](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="dee2a-p110">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="dee2a-136">Der Zeitraum für die Wiederherstellung einzelner Elemente beträgt standardmäßig 14 Tage, kann aber in einigen Fällen angepasst werden.</span><span class="sxs-lookup"><span data-stu-id="dee2a-136">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances.</span></span> <br/>
>  <span data-ttu-id="dee2a-137">Wenn ein Administrator das Postfach eines Benutzers in einem Compliance-Archiv oder einem Beweissicherungsverfahren platziert hat, werden gelöschte Elemente auf unbestimmte Zeit aufbewahrt, und das 14-Tage-Fenster gilt nicht.</span><span class="sxs-lookup"><span data-stu-id="dee2a-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="dee2a-138">Wiederherstellung gelöschter Postfächer</span><span class="sxs-lookup"><span data-stu-id="dee2a-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="dee2a-p112">Wenn Administratoren Benutzer auf dem lokalen Exchange Server löschen, werden auch die Archive der Benutzer gelöscht. Wenn die gelöschten Archivpostfächer wiederhergestellt werden müssen, kann das Office 365-Supportteam diese Wiederherstellung durchführen. Ein wiederhergestelltes Archiv enthält alle E-Mails, die darin gespeichert waren, als es gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="dee2a-p112">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted. If the deleted archive mailboxes need to be recovered, the Office 365 support team can perform this recovery. A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="dee2a-p113">Administratoren haben ab dem Zeitpunkt, an dem das Postfach eines Benutzers gelöscht wird, 30 Tage Zeit, um die Wiederherstellung eines Archivpostfachs anzufordern. Nach 30 Tagen kann das Archivpostfach nicht mehr wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="dee2a-p113">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="dee2a-144">Redundanz von Postfachdiensten</span><span class="sxs-lookup"><span data-stu-id="dee2a-144">Mailbox service redundancy</span></span>

<span data-ttu-id="dee2a-145">Archivpostfächer in Exchange Online-Archivierung werden in mehreren Datenbankkopien in geografisch verteilten Microsoft-Datencentern repliziert, um eine Datenwiederherstellung zu ermöglichen, falls eine Nachrichteninfrastruktur ausfällt.</span><span class="sxs-lookup"><span data-stu-id="dee2a-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="dee2a-146">Bei umfangreicheren Ausfällen wird Geschäftskontinuitätsmanagement initiiert.</span><span class="sxs-lookup"><span data-stu-id="dee2a-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="dee2a-147">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="dee2a-147">Feature availability</span></span>

<span data-ttu-id="dee2a-148">Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Archivierungsdienst Beschreibung](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="dee2a-148">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  
