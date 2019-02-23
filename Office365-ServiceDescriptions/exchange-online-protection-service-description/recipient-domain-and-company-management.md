---
title: Empfänger-, Domänen- und Unternehmensverwaltung
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) bietet mehrere Möglichkeiten zum Verwalten von Empfänger-, Domänen-und Unternehmensinformationen. Als Administrator können Sie bestimmte Verwaltungsaufgaben innerhalb der Exchange-Verwaltungskonsole (EAC) ausführen und andere Verwaltungsaufgaben im Microsoft 365 Admin Center überprüfen.
ms.openlocfilehash: fcae2c3ad93b977fb197089e2c8809b74ada7bd7
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210328"
---
# <a name="recipient-domain-and-company-management"></a>Empfänger-, Domänen- und Unternehmensverwaltung

Microsoft Exchange Online Protection (EOP) bietet mehrere Möglichkeiten zum Verwalten von Empfänger-, Domänen-und Unternehmensinformationen. Als Administrator können Sie bestimmte Verwaltungsaufgaben innerhalb der Exchange-Verwaltungskonsole (EAC) ausführen und andere Verwaltungsaufgaben im Microsoft 365 Admin Center überprüfen.
  
Sie suchen nach Informationen zu allen EOP-Features? Entsprechendes finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>E-Mail-Empfänger
<a name="BKMK_mailrecipients"> </a>

E-Mail-Empfänger werden als e-Mail-Benutzer oder-Gruppen kategorisiert und können über die Verzeichnissynchronisierung direkt in der Exchange-Verwaltungskonsole oder über die Remote-Windows PowerShell verwaltet werden. Wenn Sie Ihre Empfänger lokal verwalten, müssen Sie die Verzeichnissynchronisierung ausführen, damit Ihre e-Mail-Empfänger in der Exchange-Verwaltungskonsole wiedergegeben werden. Benutzer, die ausschließlich im Microsoft 365 Admin Center verwaltet werden, können nicht in der Exchange-verwaltungsKONSOLE angezeigt werden, Sie sind jedoch in einer Administratorrollengruppe in der Exchange-Verwaltungskonsole zur Mitgliedschaft hinzugefügt oder daraus entfernt. Weitere Informationen zu Empfängern in EOP finden Sie unter [Recipients in EoP](https://go.microsoft.com/fwlink/p/?LinkId=280011).
  
## <a name="admin-role-group-permissions"></a>Berechtigungen für Administratorrollengruppen
<a name="BKMK_adminrolegrouppermissions"> </a>

Sie können in EOP nur Administratorrollen konfigurieren. Benutzer können direkt in der Exchange-Verwaltungskonsole den standardmäßigen Administratorrollengruppen hinzugefügt beziehungsweise daraus entfernt werden. Es ist keine Anpassung der rollenbasierten Zugriffssteuerung verfügbar. Weitere Informationen finden Sie unter [Verwalten der Berechtigungen der Administratorrollengruppen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).
  
## <a name="domain-management"></a>Domänenverwaltung
<a name="BKMK_domainmanagement"> </a>

Verwaltete Domänen sind Domänen, die von EOP geschützt werden. Verwaltete Domänen können angezeigt und Domänentypen in der Exchange-Verwaltungskonsole bearbeitet werden. Die Domänen Einrichtung und-Verwaltung erfolgt im Microsoft 365 Admin Center, und Änderungen werden in der Exchange-Verwaltungskonsole übernommen. Weitere Informationen finden Sie unter [anzeigen oder bearbeiten verwaltetEr Domänen in EoP](https://go.microsoft.com/fwlink/p/?LinkId=282239).
  
## <a name="match-subdomains"></a>Untergeordnete Domänen abgleichen
<a name="BKMK_EOP_Match_Subdomains"> </a>

Sie können in EOP E-Mail-Fluss zu Unterdomänen einer verwalteten Domäne aktivieren. Weitere Informationen finden Sie unter [Aktivieren des E-Mail-Flusses für Unterdomänen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Verzeichnisbasierte Edge-Blockierung (DBEB)
<a name="BKMK_DBEB"> </a>

Das Feature Verzeichnisbasierte Edge-Blockierung ermöglicht es Ihnen, Nachrichten für ungültige Empfänger im Dienstnetzwerkumkreis abzulehnen. Mit der verzeichnisbasierten Edge-Blockierung können Administratoren E-Mail-aktivierte Empfänger in Office 365 hinzufügen und alle an nicht in Office 365 vorhandene E-Mail-Adressen gesendete Nachrichten blockieren. Wird eine Nachricht an eine gültige, in Office 365 vorhandene E-Mail-Adresse gesendet, wird die Nachricht durch die verbleibenden Filterebenen des Diensts (Antischadsoftware, Antispam, Transportregeln) weitergeleitet. Ist die Adresse nicht vorhanden, blockiert der Dienst die Nachricht bereits vor der Filterung. Zudem wird der Absender durch einen Unzustellbarkeitsbericht (Non-Delivery Report, NDR) informiert, dass die Nachricht nicht übermittelt wurde. 
  
Zum Aktivieren von DBEB ist eine bestimmte Benutzer- und Domänenkonfiguration erforderlich. Weitere Informationen finden Sie unter [Ablehnen von Nachrichten an ungültige Empfänger mithilfe von verzeichnisbasierter Edge-Blockierung](https://go.microsoft.com/fwlink/p/?LinkId=390676).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen
<a name="BKMK_DBEB"> </a>

Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).
  

