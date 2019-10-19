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
ms.openlocfilehash: 8e27ce238fa0aa7e2b670f6d991178c5f595908a
ms.sourcegitcommit: 19591e97b35c1b2a99e04a496d83af27dc6530d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/18/2019
ms.locfileid: "37581401"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Archivfunktionen in Exchange Online Archivierung

In den folgenden Abschnitten werden die Archivfunktionen Microsoft Exchange Online Archivierung beschrieben.
  
## <a name="archive-mailbox"></a>Archivpostfach

Exchange Online-Archivierung bietet Benutzern mit der Archivpostfachfunktion erweiterte Archivierungsfunktionen. Bei einem Archivpostfach handelt es sich um ein spezielles Postfach, das neben den primären Postfachordnern der Benutzer in Outlook oder Outlook im Internet angezeigt wird. Benutzer können auf das Archiv auf die gleiche Weise zugreifen, wie sie auf ihre primären Postfachordner zugreifen. Darüber hinaus können sie ihre Archive und primären Postfächer durchsuchen.
  
Administratoren können die Archivfunktion mithilfe des Exchange Admin Center (EAC) oder der remote verwendeten Windows PowerShell für bestimmte Benutzer archivieren. Weitere Informationen finden Sie unter [Aktivieren und Deaktivieren von Archivpostfächern in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung zu Exchange Online-Archivierung zu kopieren. <br/>
>  Das Archivpostfach eines Benutzers ist nur für diesen Benutzer vorgesehen. Microsoft behält sich das Recht vor, die uneingeschränkte Archivierung dann zu verweigern, wenn das Archivpostfach eines Benutzers zum Speichern von Archivdaten für andere Benutzer verwendet wird. 
  
### <a name="move-messages-to-exchange-online-archiving"></a>Verschieben von Nachrichten zur Exchange Online-Archivierung

Benutzer können Nachrichten für einfachen Onlinezugriff aus PST-Dateien per Drag & Drop in das Archiv verschieben. Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox. 
  
### <a name="import-data-to-the-archive"></a>Importieren von Daten in das Archiv

Benutzer haben folgende Möglichkeiten, um Daten in das Archiv zu importieren:
  
- Importieren von Daten aus einer PST-Datei mithilfe des Import/Export-Assistenten von Outlook.
    
- Ziehen von E-Mail-Nachrichten aus PST-Dateien in das Archiv.
    
- Ziehen von E-Mails aus dem primären Postfach in das Archiv.
    
- Archivrichtlinien automatisch E-Mail-Nachrichten je nach Alter der Nachrichten vom primären Postfach verschieben lassen. Weitere Informationen finden Sie unter [Aufbewahrungstags und Aufbewahrungsrichtlinien](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administratoren können auch den Office 365-Importdienst verwenden, um PST-Dateien in cloudbasierte Archivpostfächer der Benutzer zu importieren. Weitere Informationen finden Sie unter [Verwenden des Netzwerkuploads zum Importieren von PST-Dateien in Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>Wiederherstellung gelöschter Elemente

Benutzer können Elemente wiederherstellen, die sie aus einem E-Mail-Ordner in ihrem Archiv gelöscht haben. Wenn ein Element gelöscht wird, wird es im Ordner "Gelöschte Elemente" des Archivs aufbewahrt. Es wird dort so lange gespeichert, bis es vom Benutzer automatisch verschoben oder durch Aufbewahrungsrichtlinien automatisch entfernt wird.
  
Nachdem ein Element aus dem Ordner "Gelöschte Elemente" des Archivs gelöscht wurde, wird das Element im Ordner "Wiederherstellbare Elemente" des Archivs weitere 14 Tage lang aufbewahrt, bevor es endgültig gelöscht wird. Benutzer können diese Elemente mithilfe der Funktion **Gelöschte Elemente wiederherstellen** in Microsoft Outlook oder Outlook im Internet wiederherstellen. 
  
Wenn ein Benutzer ein Element manuell aus dem Ordner „Wiederherstellbare Elemente" gelöscht hat, kann ein Administrator das Element innerhalb des gleichen 14-Tage-Zeitfensters mithilfe des Features „Wiederherstellung einzelner Elemente" wiederherstellen. Dieses Feature erlaubt Administratoren, eine Suche in mehreren Postfächern durchzuführen, um gelöschte Elemente zu finden, und dann mithilfe des Windows PowerShell-Cmdlets  `Search-Mailbox` die Elemente aus dem Discoverypostfach in die Postfächer von Benutzern zu verschieben. Weitere Informationen finden Sie unter [Aktivieren oder Deaktivieren der Wiederherstellung einzelner Elemente für ein Postfach](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  Der Zeitraum für die Wiederherstellung einzelner Elemente beträgt standardmäßig 14 Tage, kann aber in einigen Fällen angepasst werden. <br/>
>  Wenn ein Administrator das Postfach eines Benutzers in einem Compliance-Archiv oder einem Beweissicherungsverfahren platziert hat, werden gelöschte Elemente auf unbestimmte Zeit aufbewahrt, und das 14-Tage-Fenster gilt nicht. 
  
## <a name="deleted-mailbox-recovery"></a>Wiederherstellung gelöschter Postfächer

Wenn Administratoren Benutzer auf dem lokalen Exchange Server löschen, werden auch die Archive der Benutzer gelöscht. Wenn die gelöschten Archivpostfächer wiederhergestellt werden müssen, kann das Office 365-Supportteam diese Wiederherstellung durchführen. Ein wiederhergestelltes Archiv enthält alle E-Mails, die darin gespeichert waren, als es gelöscht wurde.
  
> [!IMPORTANT]
> Administratoren haben ab dem Zeitpunkt, an dem das Postfach eines Benutzers gelöscht wird, 30 Tage Zeit, um die Wiederherstellung eines Archivpostfachs anzufordern. Nach 30 Tagen kann das Archivpostfach nicht mehr wiederhergestellt werden. 
  
## <a name="mailbox-service-redundancy"></a>Redundanz von Postfachdiensten

Archivpostfächer in Exchange Online-Archivierung werden in mehreren Datenbankkopien in geografisch verteilten Microsoft-Datencentern repliziert, um eine Datenwiederherstellung zu ermöglichen, falls eine Nachrichteninfrastruktur ausfällt. Bei umfangreicheren Ausfällen wird Geschäftskontinuitätsmanagement initiiert. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Archivierungsdienst Beschreibung](exchange-online-archiving-service-description.md).
  
