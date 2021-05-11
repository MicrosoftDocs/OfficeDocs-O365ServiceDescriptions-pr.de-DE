---
title: Hohe Verfügbarkeit und Geschäftskontinuität
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online bietet umfassende Aufbewahrungs- und Wiederherstellungsunterstützung für die E-Mail-Infrastruktur einer Organisation. Dazu zählen die Postfachreplikation in Datencentern und die Möglichkeit, gelöschte Postfächer und gelöschte Elemente wiederherzustellen.
ms.openlocfilehash: 5415499e85d0e6fb0334e2e23abc435d0df9d2ab
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653337"
---
# <a name="high-availability-and-business-continuity"></a>Hohe Verfügbarkeit und Geschäftskontinuität

Microsoft Exchange Online bietet umfassende Aufbewahrungs- und Wiederherstellungsunterstützung für die E-Mail-Infrastruktur einer Organisation. Dazu zählen die Postfachreplikation in Datencentern und die Möglichkeit, gelöschte Postfächer und gelöschte Elemente wiederherzustellen.
  
## <a name="mailbox-replication-at-data-centers"></a>Postfachreplikation in Datencentern

Exchange Online-Postfächer werden kontinuierlich in mehreren Datenbankkopien in geografisch verteilten Microsoft-Datencentern repliziert, um eine Datenwiederherstellung zu ermöglichen, falls eine lokale Nachrichteninfrastruktur ausfällt. Bei umfangreichen Ausfällen werden Verwaltungsverfahren zur Aufrechterhaltung von Diensten eingeleitet.
  
Weitere Informationen dazu, wie Microsoft Ihre Daten schützt, finden Sie im [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). Bei Verwendung von Office 365 über 21Vianet finden Sie entsprechende Informationen im [21Vianet Trust Center](https://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).
  
## <a name="deleted-mailbox-recovery"></a>Wiederherstellung gelöschter Postfächer

Administratoren können Exchange Online Postfächer löschen, indem sie das Microsoft 365 Admin Center verwenden, um das entsprechende Benutzerkonto zu löschen oder die Exchange Online-Lizenz zu entfernen, oder mithilfe des **Cmdlets Remove-Mailbox** in remote Windows PowerShell. Wenn ein Postfach gelöscht wird, Exchange Online das Postfach und seinen Inhalt standardmäßig 30 Tage lang beibehalten. Nach 30 Tagen kann das Postfach nicht mehr wiederhergestellt werden. Ein wiederhergestelltes Postfach enthält alle Daten, die zum Zeitpunkt des Löschens gespeichert wurden. Administratoren können ein gelöschtes Postfach innerhalb des Aufbewahrungszeitraums mithilfe des Microsoft 365 wiederherstellen. Zum Wiederherstellen eines gelöschten Postfachs müssen Administratoren das entsprechende Benutzerkonto wiederherstellen oder eine Exchange Online dem Benutzerkonto neu zuweisen. Weitere Informationen finden Sie unter [Exchange Online-Benutzerpostfächer löschen oder wiederherstellen](/exchange/recipients-in-exchange-online/delete-or-restore-mailboxes).
  
## <a name="deleted-item-recovery"></a>Wiederherstellung gelöschter Elemente

Exchange Online können Benutzer Elemente wiederherstellen, die sie aus einem beliebigen E-Mail-Ordner gelöscht haben, einschließlich des Ordners "Gelöschte Elemente". Wenn ein Element gelöscht wird, bleibt es im Ordner "Gelöschte Elemente" erhalten. Es wird dort aufbewahrt, bis es entweder manuell vom Benutzer oder automatisch durch Aufbewahrungsrichtlinien entfernt wird. Administratoren können Aufbewahrungsrichtlinien mit der Exchange-Verwaltungskonsole oder der Remote-Windows PowerShell anpassen.
  
Nachdem ein Element aus dem Ordner "Gelöschte Elemente" entfernt wurde, wird es für weitere 14 Tage in einem Ordner "Wiederherstellbare Elemente" aufbewahrt, bevor es endgültig entfernt wird. Administratoren können dies jedoch mithilfe von Remoteservern auf maximal 30 Tage Windows PowerShell. Benutzer können das Element während dieses Zeitraums mithilfe des Features Gelöschte Elemente wiederherstellen in Outlook web oder Outlook. Erfahren Sie, wie [Sie den Aufbewahrungszeitraum für gelöschte Elemente ändern.](/exchange/recipients-in-exchange-online/manage-user-mailboxes/change-deleted-item-retention)
  
Wenn ein Benutzer ein Element manuell aus dem Ordner "Wiederherstellbare Elemente" gelöscht hat, kann ein Administrator das Element mit der Funktion zur Wiederherstellung einzelner Elemente und der Remote-Windows PowerShell innerhalb desselben Zeitraums wiederherstellen. Die Wiederherstellung einzelner Elemente wird bei der Erstellung eines Postfachs standardmäßig aktiviert. Weitere Informationen finden Sie unter [Aktivieren oder Deaktivieren der Wiederherstellung einzelner Elemente für ein Postfach](/exchange/recipients-in-exchange-online/manage-user-mailboxes/enable-or-disable-single-item-recovery).
  
Sollen Nachrichten länger als 30 Tage im Ordner "Wiederherstellbare Elemente" aufbewahrt werden, können Organisationen Langzeitaufbewahrung oder zeitbasierte In-Situ-Speicher implementieren. Unter diesem Link finden Sie weitere Informationen zu [In-Situ-Speichern für Postfächer](/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie [unter Exchange Online Service description](exchange-online-service-description.md).
