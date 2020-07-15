---
title: Empfänger-, Domänen- und Unternehmensverwaltung
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EoP) bietet verschiedene Möglichkeiten zur Verwaltung Ihrer Empfänger-, Domänen-und Unternehmensinformationen. Als Administrator können Sie bestimmte Verwaltungsaufgaben im Exchange Admin Center (EAC) ausführen und andere Verwaltungsaufgaben überprüfen, die im Microsoft 365 Admin Center ausgeführt werden.
ms.openlocfilehash: 4a2d2d091a6170e0606702a4a8047a21ad57ac11
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132769"
---
# <a name="recipient-domain-and-company-management"></a>Empfänger-, Domänen- und Unternehmensverwaltung

Microsoft Exchange Online Protection (EoP) bietet verschiedene Möglichkeiten zur Verwaltung Ihrer Empfänger-, Domänen-und Unternehmensinformationen. Als Administrator können Sie bestimmte Verwaltungsaufgaben im Exchange Admin Center (EAC) ausführen und andere Verwaltungsaufgaben überprüfen, die im Microsoft 365 Admin Center ausgeführt werden.
  
Sie suchen nach Informationen zu allen EOP-Funktionen? Siehe [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Mail recipients

E-Mail-Empfänger werden als E-Mail-Benutzer oder -Gruppen kategorisiert und können durch die Verzeichnissynchronisierung direkt im EAC oder remote über die Windows PowerShell verwaltet werden. Wenn Sie Ihre Empfänger lokal verwalten, müssen Sie die Verzeichnissynchronisierung ausführen, damit Ihre E-Mail-Empfänger in der Exchange-Verwaltungskonsole wiedergegeben werden. Benutzer, die ausschließlich im Microsoft 365 Admin Center verwaltet werden, sind in der Exchange-Verwaltungskonsole nicht sichtbar, können jedoch der Mitgliedschaft in einer Administratorrollengruppe in der Exchange-Verwaltungskonsole hinzugefügt oder daraus entfernt werden. Weitere Informationen zu Empfängern in EOP finden Sie unter [Empfänger in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Domain management

Verwaltete Domänen sind Domänen, die durch EoP geschützt sind. In der Exchange-Verwaltungskonsole können verwaltete Domänen angezeigt und Domänentypen bearbeitet werden. Die Domänen Einrichtung und-Verwaltung erfolgt im Microsoft 365 Admin Center, und Änderungen werden in der Exchange-Verwaltungskonsole übernommen. Weitere Informationen finden Sie unter [anzeigen oder bearbeiten verwalteter Domänen in EoP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Untergeordnete Domänen abgleichen

In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Directory Based Edge Blocking (DBEB)

Mit der Funktion verzeichnisbasierte Edge-Blockierung können Sie Nachrichten für ungültige Empfänger im Dienst Netzwerkumkreis ablehnen. Mit Blockierung können Administratoren e-Mail-aktivierte Empfänger zu Microsoft hinzufügen und alle an e-Mail-Adressen gesendeten Nachrichten blockieren, die in Microsoft nicht vorhanden sind. Wenn eine Nachricht an eine gültige e-Mail-Adresse gesendet wird, die in Microsoft vorhanden ist, wird die Nachricht über die restlichen Dienstfilter Ebenen (Anti-Malware, Antispam, Transportregeln) weitergeleitet. Wenn die Adresse nicht vorhanden ist, blockiert der Dienst die Nachricht noch vor dem Filtern, und ein Unzustellbarkeitsbericht (NDR) wird mit der Benachrichtigung an den Absender gesendet, dass die Nachricht nicht zugestellt werden konnte. 
  
Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).
