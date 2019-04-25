---
title: Hohe Verfügbarkeit und Geschäftskontinuität
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online bietet umfassende Aufbewahrungs-und Wiederherstellungsunterstützung für die e-Mail-Infrastruktur einer Organisation. Dazu zählen die Postfachreplikation in Datencentern und die Möglichkeit, gelöschte Postfächer und gelöschte Elemente wiederherzustellen.
ms.openlocfilehash: 2da41ba335faa4cf18228a64fbb1b420d438e503
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "33244901"
---
# <a name="high-availability-and-business-continuity"></a>High Availability and Business Continuity

Microsoft Exchange Online bietet umfassende Aufbewahrungs-und Wiederherstellungsunterstützung für die e-Mail-Infrastruktur einer Organisation. Dazu zählen die Postfachreplikation in Datencentern und die Möglichkeit, gelöschte Postfächer und gelöschte Elemente wiederherzustellen.
  
## <a name="mailbox-replication-at-data-centers"></a>Postfachreplikation in Datencentern

Exchange Online-Postfächer werden kontinuierlich in mehreren Datenbankkopien in geografisch verteilten Microsoft-Datencentern repliziert, um eine Datenwiederherstellung zu ermöglichen, falls eine lokale Nachrichteninfrastruktur ausfällt. Bei umfangreichen Ausfällen werden Verwaltungsverfahren zur Aufrechterhaltung von Diensten eingeleitet.
  
Weitere Informationen dazu, wie Microsoft Ihre Daten schützt, finden Sie im [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). Bei Verwendung von Office 365 über 21Vianet finden Sie entsprechende Informationen im [21Vianet Trust Center](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Wiederherstellung gelöschter Postfächer

Administratoren können Exchange Online-Postfächer mithilfe des Microsoft 365 admin Centers löschen, um das entsprechende Benutzerkonto zu löschen oder die Exchange Online-Lizenz zu entfernen oder das Cmdlet **Remove-Mailbox** in Windows PowerShell zu verwenden. Wenn ein Postfach gelöscht wird, werden das Postfach und sein Inhalt von Exchange Online standardmäßig 30 Tage lang aufbewahrt. Nach 30 Tagen kann das Postfach nicht wiederhergestellt werden. Ein wieder hergestelltes Postfach enthält alle Daten, die zu dem Zeitpunkt gespeichert wurden, zu dem es gelöscht wurde. Administratoren können ein gelöschtes Postfach innerhalb des Aufbewahrungszeitraums wiederherstellen, indem Sie das Microsoft 365 Admin Center verwenden. Zum Wiederherstellen eines gelöschten Postfachs müssen Administratoren das entsprechende Office 365-Benutzerkonto wiederherstellen oder dem Benutzerkonto eine Exchange Online-Lizenz zuweisen. Weitere Informationen finden Sie unter [Exchange Online-Benutzerpostfächer löschen oder wiederherstellen](https://go.microsoft.com/fwlink/p/?LinkId=286992).
  
## <a name="deleted-item-recovery"></a>Wiederherstellung gelöschter Elemente

In Exchange Online können Benutzer Elemente wiederherstellen, die sie aus einem E-Mail-Ordner, einschließlich des Ordners "Gelöschte Elemente", gelöscht haben. Wenn ein Element gelöscht wird, bleibt es im Ordner "Gelöschte Elemente" erhalten. Es wird dort aufbewahrt, bis es entweder manuell vom Benutzer oder automatisch durch Aufbewahrungsrichtlinien entfernt wird. Administratoren können Aufbewahrungsrichtlinien mit der Exchange-Verwaltungskonsole oder der Remote-Windows PowerShell anpassen.
  
Nach der Entfernung eines Elements aus dem Ordner "Gelöschte Elemente" wird es weitere 14 Tage lang im Ordner "Wiederherstellbare Elemente" aufbewahrt, bevor es dauerhaft entfernt wird. Administratoren können diese Zeitspanne jedoch auf maximal 30 Tage erhöhen, indem sie die Remote-Windows PowerShell verwenden. Mithilfe der Funktion "Gelöschte Elemente wiederherstellen" in Outlook Web App oder Outlook können Benutzer das Element während dieses Zeitraums wiederherstellen. [Hier können Sie nachlesen, wie Sie den Aufbewahrungszeitraum für gelöschte Elemente ändern](https://go.microsoft.com/fwlink/p/?LinkId=286940).
  
Wenn ein Benutzer ein Element manuell aus dem Ordner "Wiederherstellbare Elemente" gelöscht hat, kann ein Administrator das Element mit der Funktion zur Wiederherstellung einzelner Elemente und der Remote-Windows PowerShell innerhalb desselben Zeitraums wiederherstellen. Die Wiederherstellung einzelner Elemente wird bei der Erstellung eines Postfachs standardmäßig aktiviert. Weitere Informationen finden Sie unter [Aktivieren oder Deaktivieren der Wiederherstellung einzelner Elemente für ein Postfach](https://go.microsoft.com/fwlink/p/?LinkID=286941).
  
Sollen Nachrichten länger als 30 Tage im Ordner "Wiederherstellbare Elemente" aufbewahrt werden, können Organisationen Langzeitaufbewahrung oder zeitbasierte In-Situ-Speicher implementieren. Unter diesem Link finden Sie weitere Informationen zu [In-Situ-Speichern für Postfächer](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description.md).
  

