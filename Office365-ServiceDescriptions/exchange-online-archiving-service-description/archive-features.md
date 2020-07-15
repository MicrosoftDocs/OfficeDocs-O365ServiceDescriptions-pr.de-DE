---
title: Archivfunktionen in Exchange Online Archivierung
ms.author: office365servicedesc
author: pamelaar
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
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131529"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Archivfunktionen in Exchange Online Archivierung

In den folgenden Abschnitten werden die Archivfunktionen Microsoft Exchange Online Archivierung beschrieben.
  
## <a name="archive-mailbox"></a>Archivpostfach

Exchange Online-Archivierung bietet Benutzern mit der Archivpostfachfunktion erweiterte Archivierungsfunktionen. Bei einem Archivpostfach handelt es sich um ein spezielles Postfach, das neben den primären Postfachordnern der Benutzer in Outlook oder Outlook im Internet angezeigt wird. Benutzer können auf das Archiv auf die gleiche Weise zugreifen, wie sie auf ihre primären Postfachordner zugreifen. Darüber hinaus können sie ihre Archive und primären Postfächer durchsuchen.
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung zu Exchange Online-Archivierung zu kopieren. <br/>
>  Das Archivpostfach eines Benutzers ist nur für diesen Benutzer vorgesehen. Microsoft behält sich das Recht vor, eine unbegrenzte Archivierung in Fällen zu verweigern, in denen das Archivpostfach eines Benutzers zum Speichern von Archivdaten für andere Benutzer oder in anderen Fällen ungeeigneter Verwendung verwendet wird.
  
### <a name="move-messages-to-exchange-online-archiving"></a>Verschieben von Nachrichten zur Exchange Online-Archivierung

Benutzer können Nachrichten für einfachen Onlinezugriff aus PST-Dateien per Drag & Drop in das Archiv verschieben. Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox. 
  
### <a name="import-data-to-the-archive"></a>Importieren von Daten in das Archiv

Benutzer haben folgende Möglichkeiten, um Daten in das Archiv zu importieren:
  
- Importieren von Daten aus einer PST-Datei mithilfe des Import/Export-Assistenten von Outlook.
    
- Ziehen von E-Mail-Nachrichten aus PST-Dateien in das Archiv.
    
- Ziehen von E-Mails aus dem primären Postfach in das Archiv.
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>Wiederherstellung gelöschter Elemente

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
Nachdem ein Element aus dem Ordner "Gelöschte Elemente" des Archivs gelöscht wurde, wird das Element im Ordner "Wiederherstellbare Elemente" des Archivs weitere 14 Tage lang aufbewahrt, bevor es endgültig gelöscht wird. Benutzer können diese Elemente mithilfe der Funktion **Gelöschte Elemente wiederherstellen** in Microsoft Outlook oder Outlook im Internet wiederherstellen. 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  Der Zeitraum für die Wiederherstellung einzelner Elemente beträgt standardmäßig 14 Tage, kann aber in einigen Fällen angepasst werden. <br/>
>  Wenn ein Administrator das Postfach eines Benutzers in einem Compliance-Archiv oder einem Beweissicherungsverfahren platziert hat, werden gelöschte Elemente auf unbestimmte Zeit aufbewahrt, und das 14-Tage-Fenster gilt nicht. 
  
## <a name="deleted-mailbox-recovery"></a>Wiederherstellung gelöschter Postfächer

Wenn Administratoren Benutzer auf dem lokalen Exchange Server löschen, werden auch die Archive der Benutzer gelöscht. Wenn die gelöschten Archivpostfächer wiederhergestellt werden müssen, kann das Microsoft-Support Team diese Wiederherstellung durchführen. Ein wiederhergestelltes Archiv enthält alle E-Mails, die darin gespeichert waren, als es gelöscht wurde.
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>Redundanz von Postfachdiensten

Archivpostfächer in Exchange Online-Archivierung werden in mehreren Datenbankkopien in geografisch verteilten Microsoft-Datencentern repliziert, um eine Datenwiederherstellung zu ermöglichen, falls eine Nachrichteninfrastruktur ausfällt. Bei umfangreicheren Ausfällen wird Geschäftskontinuitätsmanagement initiiert. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Archivierungsdienst Beschreibung](exchange-online-archiving-service-description.md).
  
