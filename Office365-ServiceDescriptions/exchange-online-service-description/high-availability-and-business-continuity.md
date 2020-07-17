---
title: Hohe Verfügbarkeit und Geschäftskontinuität
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online bietet umfangreiche Aufbewahrungs-und Wiederherstellungsunterstützung für die e-Mail-Infrastruktur einer Organisation. Dazu zählen die Postfachreplikation in Datencentern und die Möglichkeit, gelöschte Postfächer und gelöschte Elemente wiederherzustellen.
ms.openlocfilehash: 395977f77d4293d18c5cf53e02d43566ca9f7313
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131969"
---
# <a name="high-availability-and-business-continuity"></a>Hohe Verfügbarkeit und Geschäftskontinuität

Microsoft Exchange Online bietet umfangreiche Aufbewahrungs-und Wiederherstellungsunterstützung für die e-Mail-Infrastruktur einer Organisation. Dazu zählen die Postfachreplikation in Datencentern und die Möglichkeit, gelöschte Postfächer und gelöschte Elemente wiederherzustellen.
  
## <a name="mailbox-replication-at-data-centers"></a>Postfachreplikation in Datencentern

Exchange Online-Postfächer werden kontinuierlich in mehreren Datenbankkopien in geografisch verteilten Microsoft-Datencentern repliziert, um eine Datenwiederherstellung zu ermöglichen, falls eine lokale Nachrichteninfrastruktur ausfällt. Bei umfangreichen Ausfällen werden Verwaltungsverfahren zur Aufrechterhaltung von Diensten eingeleitet.
  
Weitere Informationen dazu, wie Microsoft Ihre Daten schützt, finden Sie im [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). Bei Verwendung von Office 365 über 21Vianet finden Sie entsprechende Informationen im [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Wiederherstellung gelöschter Postfächer

Administratoren können Exchange Online Postfächer löschen, indem Sie das Microsoft 365 Admin Center verwenden, um das entsprechende Benutzerkonto zu löschen oder die Exchange Online Lizenz zu entfernen, oder indem Sie das Cmdlet **Remove-Mailbox** in Remote Windows PowerShell verwenden. Wenn ein Postfach gelöscht wird, behält Exchange Online das Postfach und dessen Inhalte standardmäßig 30 Tage lang bei. Nach 30 Tagen kann das Postfach nicht mehr hergestellt werden. Ein wieder hergestelltes Postfach enthält alle darin gespeicherten Daten zu dem Zeitpunkt, zu dem es gelöscht wurde. Administratoren können ein gelöschtes Postfach innerhalb des Aufbewahrungszeitraums mithilfe des Microsoft 365 Admin Center wiederherstellen. Um ein gelöschtes Postfach wiederherzustellen, müssen Administratoren das entsprechende Benutzerkonto wiederherstellen oder dem Benutzerkonto eine Exchange Online Lizenz zuweisen. Weitere Informationen finden Sie unter [Exchange Online-Benutzerpostfächer löschen oder wiederherstellen](https://go.microsoft.com/fwlink/p/?LinkId=286992).
  
## <a name="deleted-item-recovery"></a>Wiederherstellung gelöschter Elemente

Exchange Online ermöglicht Benutzern das Wiederherstellen von Elementen, die aus einem beliebigen e-Mail-Ordner gelöscht wurden, einschließlich des Ordners "Gelöschte Elemente". Wenn ein Element gelöscht wird, bleibt es im Ordner "Gelöschte Elemente" erhalten. Es wird dort aufbewahrt, bis es entweder manuell vom Benutzer oder automatisch durch Aufbewahrungsrichtlinien entfernt wird. Administratoren können Aufbewahrungsrichtlinien mit der Exchange-Verwaltungskonsole oder der Remote-Windows PowerShell anpassen.
  
Nachdem ein Element aus dem Ordner "Gelöschte Elemente" entfernt wurde, wird es in einem Ordner "Wiederherstellbare Elemente" für weitere 14 Tage aufbewahrt, bevor es endgültig entfernt wird, Administratoren können dies jedoch mit Remote Windows PowerShell auf maximal 30 Tage verlängern. Benutzer können das Element während dieses Zeitraums wiederherstellen, indem Sie das Feature Gelöschte Elemente wiederherstellen in Outlook im Internet oder Outlook verwenden. Hier erfahren Sie, wie Sie [den Aufbewahrungszeitraum für gelöschte Elemente ändern](https://go.microsoft.com/fwlink/p/?LinkId=286940).
  
Wenn ein Benutzer ein Element manuell aus dem Ordner "Wiederherstellbare Elemente" gelöscht hat, kann ein Administrator das Element mit der Funktion zur Wiederherstellung einzelner Elemente und der Remote-Windows PowerShell innerhalb desselben Zeitraums wiederherstellen. Die Wiederherstellung einzelner Elemente wird bei der Erstellung eines Postfachs standardmäßig aktiviert. Weitere Informationen finden Sie unter [Aktivieren oder Deaktivieren der Wiederherstellung einzelner Elemente für ein Postfach](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
Sollen Nachrichten länger als 30 Tage im Ordner "Wiederherstellbare Elemente" aufbewahrt werden, können Organisationen Langzeitaufbewahrung oder zeitbasierte In-Situ-Speicher implementieren. Unter diesem Link finden Sie weitere Informationen zu [In-Situ-Speichern für Postfächer](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  