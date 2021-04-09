---
title: Empfänger-, Domänen- und Unternehmensverwaltung in Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: In diesem Artikel erfahren Sie mehr über empfänger-, domänen- und unternehmensverwaltung in Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: f58ffe829be839d8321cfc98f331d1836986e293
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652997"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a>Empfänger-, Domänen- und Unternehmensverwaltung in Exchange Online Protection

Microsoft Exchange Online Protection (EOP) bietet verschiedene Möglichkeiten zum Verwalten von Empfänger-, Domänen- und Unternehmensinformationen. Als Administrator können Sie bestimmte Verwaltungsaufgaben im Exchange Admin Center (EAC) ausführen und andere Verwaltungsaufgaben überprüfen, die im Microsoft 365 Admin Center ausgeführt werden.
  
Sie suchen nach Informationen zu allen EOP-Funktionen? Weitere Informationen finden [Sie in der Beschreibung des Exchange Online Protection-Diensts](exchange-online-protection-service-description.md).
  
## <a name="mail-recipients"></a>Mail recipients

E-Mail-Empfänger werden als E-Mail-Benutzer oder -Gruppen kategorisiert und können durch die Verzeichnissynchronisierung direkt im EAC oder remote über die Windows PowerShell verwaltet werden. Wenn Sie Ihre Empfänger lokal verwalten, müssen Sie die Verzeichnissynchronisierung ausführen, damit Ihre E-Mail-Empfänger in der Exchange-Verwaltungskonsole wiedergegeben werden. Benutzer, die ausschließlich im Microsoft 365 Admin Center verwaltet werden, können in der EAC nicht angezeigt werden, sie können jedoch der Mitgliedschaft in einer Administratorrollegruppe in der EAC hinzugefügt oder aus dieser entfernt werden. Weitere Informationen zu Empfängern in EOP finden Sie unter [Empfänger in EOP](/microsoft-365/security/office-365-security/manage-recipients-in-eop).
  
## <a name="admin-role-group-permissions"></a>Admin role group permissions

Sie können in EOP nur Administratorrollen konfigurieren. Benutzer können direkt in der Exchange-Verwaltungskonsole den standardmäßigen Administratorrollengruppen hinzugefügt beziehungsweise daraus entfernt werden. Es ist keine Anpassung der rollenbasierten Zugriffssteuerung verfügbar. Weitere Informationen finden Sie unter [Verwalten der Berechtigungen der Administratorrollengruppen in EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).
  
## <a name="domain-management"></a>Domain management

Verwaltete Domänen sind Domänen, die durch EOP geschützt sind. In der Exchange-Verwaltungskonsole können verwaltete Domänen angezeigt und Domänentypen bearbeitet werden. Die Domänenbereitstellung und -verwaltung erfolgt im Microsoft 365 Admin Center, und Änderungen werden in der EAC widerspiegelt. Weitere Informationen finden Sie unter [Anzeigen oder Bearbeiten verwalteter Domänen in EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).
  
## <a name="match-subdomains"></a>Untergeordnete Domänen abgleichen

Sie können in EOP E-Mail-Fluss zu Unterdomänen einer verwalteten Domäne aktivieren. Weitere Informationen finden Sie unter [Aktivieren des E-Mail-Flusses für Unterdomänen in EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop). 
  
## <a name="directory-based-edge-blocking-dbeb"></a>Directory Based Edge Blocking (DBEB)

Mit der Funktion zum Blockieren von Verzeichnisbasierten Edges können Sie Nachrichten für ungültige Empfänger im Umkreis des Dienstnetzwerks ablehnen. MIT DBEB können Administratoren E-Mail-aktivierte Empfänger zu Microsoft hinzufügen und alle Nachrichten blockieren, die an E-Mail-Adressen gesendet werden, die nicht in Microsoft vorhanden sind. Wenn eine Nachricht an eine gültige E-Mail-Adresse gesendet wird, die in Microsoft vorhanden ist, wird die Nachricht über die restlichen Filterebenen des Diensts (Anti-Malware, Antispam, Transportregeln) fortgesetzt. Wenn die Adresse nicht vorhanden ist, blockiert der Dienst die Nachricht noch vor dem Filtern, und ein Unzustellbarkeitsbericht (NDR) wird mit der Benachrichtigung an den Absender gesendet, dass die Nachricht nicht zugestellt werden konnte. 
  
Zum Aktivieren von DBEB ist eine bestimmte Benutzer- und Domänenkonfiguration erforderlich. Weitere Informationen finden Sie unter [Ablehnen von Nachrichten an ungültige Empfänger mithilfe von verzeichnisbasierter Edge-Blockierung](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).