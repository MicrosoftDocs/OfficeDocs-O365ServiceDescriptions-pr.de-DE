---
title: Empfänger-, Domänen- und Unternehmensverwaltung
ms.author: sharik
author: skjerland
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
ms.openlocfilehash: ff773ca3e19c9f9419ad907ed102f6af8a3567c2
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246271"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="f85c3-104">Empfänger-, Domänen- und Unternehmensverwaltung</span><span class="sxs-lookup"><span data-stu-id="f85c3-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="f85c3-105">Microsoft Exchange Online Protection (EOP) bietet mehrere Möglichkeiten zum Verwalten von Empfänger-, Domänen-und Unternehmensinformationen.</span><span class="sxs-lookup"><span data-stu-id="f85c3-105">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="f85c3-106">Als Administrator können Sie bestimmte Verwaltungsaufgaben innerhalb der Exchange-Verwaltungskonsole (EAC) ausführen und andere Verwaltungsaufgaben im Microsoft 365 Admin Center überprüfen.</span><span class="sxs-lookup"><span data-stu-id="f85c3-106">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="f85c3-107">Sie suchen nach Informationen zu allen EOP-Funktionen?</span><span class="sxs-lookup"><span data-stu-id="f85c3-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="f85c3-108">Entsprechendes finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="f85c3-108">See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="f85c3-109">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="f85c3-109">Mail recipients</span></span>
<span data-ttu-id="f85c3-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="f85c3-110"></span></span>

<span data-ttu-id="f85c3-111">E-Mail-Empfänger werden als E-Mail-Benutzer oder -Gruppen kategorisiert und können durch die Verzeichnissynchronisierung direkt im EAC oder remote über die Windows PowerShell verwaltet werden.</span><span class="sxs-lookup"><span data-stu-id="f85c3-111">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="f85c3-112">Wenn Sie Ihre Empfänger lokal verwalten, müssen Sie die Verzeichnissynchronisierung ausführen, damit Ihre E-Mail-Empfänger in der Exchange-Verwaltungskonsole wiedergegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f85c3-112">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="f85c3-113">Benutzer, die ausschließlich im Microsoft 365 Admin Center verwaltet werden, können nicht in der Exchange-verwaltungsKONSOLE angezeigt werden, Sie sind jedoch in einer Administratorrollengruppe in der Exchange-Verwaltungskonsole zur Mitgliedschaft hinzugefügt oder daraus entfernt.</span><span class="sxs-lookup"><span data-stu-id="f85c3-113">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="f85c3-114">Weitere Informationen zu Empfängern in EOP finden Sie unter [Empfänger in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span><span class="sxs-lookup"><span data-stu-id="f85c3-114">For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="f85c3-115">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="f85c3-115">Admin role group permissions</span></span>
<span data-ttu-id="f85c3-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="f85c3-116"></span></span>

<span data-ttu-id="f85c3-p105">Sie können in EOP nur Administratorrollen konfigurieren. Benutzer können direkt in der Exchange-Verwaltungskonsole den standardmäßigen Administratorrollengruppen hinzugefügt beziehungsweise daraus entfernt werden. Es ist keine Anpassung der rollenbasierten Zugriffssteuerung verfügbar. Weitere Informationen finden Sie unter [Verwalten der Berechtigungen der Administratorrollengruppen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span><span class="sxs-lookup"><span data-stu-id="f85c3-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="f85c3-121">Domain management</span><span class="sxs-lookup"><span data-stu-id="f85c3-121">Domain management</span></span>
<span data-ttu-id="f85c3-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="f85c3-122"></span></span>

<span data-ttu-id="f85c3-123">Verwaltete Domänen sind Domänen, die von EOP geschützt werden.</span><span class="sxs-lookup"><span data-stu-id="f85c3-123">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="f85c3-124">In der Exchange-Verwaltungskonsole können verwaltete Domänen angezeigt und Domänentypen bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="f85c3-124">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="f85c3-125">Die Domänen Einrichtung und-Verwaltung erfolgt im Microsoft 365 Admin Center, und Änderungen werden in der Exchange-Verwaltungskonsole übernommen.</span><span class="sxs-lookup"><span data-stu-id="f85c3-125">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="f85c3-126">Weitere Informationen finden Sie unter [anzeigen oder bearbeiten verwaltetEr Domänen in EoP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="f85c3-126">For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="f85c3-127">Untergeordnete Domänen abgleichen</span><span class="sxs-lookup"><span data-stu-id="f85c3-127">Match subdomains</span></span>
<span data-ttu-id="f85c3-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="f85c3-128"></span></span>

<span data-ttu-id="f85c3-p107">Sie können in EOP E-Mail-Fluss zu Unterdomänen einer verwalteten Domäne aktivieren. Weitere Informationen finden Sie unter [Aktivieren des E-Mail-Flusses für Unterdomänen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span><span class="sxs-lookup"><span data-stu-id="f85c3-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="f85c3-131">Directory Based Edge Blocking (DBEB)</span><span class="sxs-lookup"><span data-stu-id="f85c3-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="f85c3-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="f85c3-132"></span></span>

<span data-ttu-id="f85c3-p108">Das Feature Verzeichnisbasierte Edge-Blockierung ermöglicht es Ihnen, Nachrichten für ungültige Empfänger im Dienstnetzwerkumkreis abzulehnen. Mit der verzeichnisbasierten Edge-Blockierung können Administratoren E-Mail-aktivierte Empfänger in Office 365 hinzufügen und alle an nicht in Office 365 vorhandene E-Mail-Adressen gesendete Nachrichten blockieren. Wird eine Nachricht an eine gültige, in Office 365 vorhandene E-Mail-Adresse gesendet, wird die Nachricht durch die verbleibenden Filterebenen des Diensts (Antischadsoftware, Antispam, Transportregeln) weitergeleitet. Ist die Adresse nicht vorhanden, blockiert der Dienst die Nachricht bereits vor der Filterung. Zudem wird der Absender durch einen Unzustellbarkeitsbericht (Non-Delivery Report, NDR) informiert, dass die Nachricht nicht übermittelt wurde.</span><span class="sxs-lookup"><span data-stu-id="f85c3-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="f85c3-p109">Zum Aktivieren von DBEB ist eine bestimmte Benutzer- und Domänenkonfiguration erforderlich. Weitere Informationen finden Sie unter [Ablehnen von Nachrichten an ungültige Empfänger mithilfe von verzeichnisbasierter Edge-Blockierung](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span><span class="sxs-lookup"><span data-stu-id="f85c3-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="f85c3-139">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="f85c3-139">Feature Availability</span></span>
<span data-ttu-id="f85c3-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="f85c3-140"></span></span>

<span data-ttu-id="f85c3-141">Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="f85c3-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

