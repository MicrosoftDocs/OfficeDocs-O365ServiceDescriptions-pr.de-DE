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
description: Microsoft Exchange Online Protection (EOP) bietet mehrere bedeutet, dass der Verwaltung Ihrer Empfänger, Domäne und Firmeninformationen. Als Administrator können Sie bestimmte Verwaltungsaufgaben innerhalb der Exchange-Verwaltungskonsole (EAC) ausführen, und Überprüfen von anderen Verwaltungsaufgaben in der Microsoft Office 365-Verwaltungskonsole ausgeführt.
ms.openlocfilehash: 17a87a85611dc286e3d19eaeefe04466a1ac62d0
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035880"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="0504e-104">Empfänger-, Domänen- und Unternehmensverwaltung</span><span class="sxs-lookup"><span data-stu-id="0504e-104">Recipient, Domain, and Company Management</span></span>

<span data-ttu-id="0504e-p102">Microsoft Exchange Online Protection (EOP) bietet mehrere bedeutet, dass der Verwaltung Ihrer Empfänger, Domäne und Firmeninformationen. Als Administrator können Sie bestimmte Verwaltungsaufgaben innerhalb der Exchange-Verwaltungskonsole (EAC) ausführen, und Überprüfen von anderen Verwaltungsaufgaben in der Microsoft Office 365-Verwaltungskonsole ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="0504e-p102">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information. As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft Office 365 admin center.</span></span>
  
<span data-ttu-id="0504e-p103">Sie suchen nach Informationen zu allen EOP-Features? Entsprechendes finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="0504e-p103">Looking for information about all EOP features? See the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="0504e-109">E-Mail-Empfänger</span><span class="sxs-lookup"><span data-stu-id="0504e-109">Mail recipients</span></span>
<span data-ttu-id="0504e-110"><a name="BKMK_mailrecipients"> </a></span><span class="sxs-lookup"><span data-stu-id="0504e-110"></span></span>

<span data-ttu-id="0504e-p104">E-Mail-Empfänger werden als E-Mail-Benutzer oder -Gruppen kategorisiert und können durch die Verzeichnissynchronisierung direkt im EAC oder remote über die Windows PowerShell verwaltet werden. Wenn Sie Ihre Empfänger lokal verwalten, müssen Sie die Verzeichnissynchronisierung ausführen, damit Ihre E-Mail-Empfänger in der Exchange-Verwaltungskonsole wiedergegeben werden. Benutzer, die nur im Office 365 Admin Center verwaltet werden, sind in der Exchange-Verwaltungskonsole nicht sichtbar, können jedoch in der Administratorrollengruppe in der Exchange-Verwaltungskonsole hinzugefügt oder entfernt werden. Weitere Informationen zu Empfängern in EOP finden Sie unter [Empfänger in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span><span class="sxs-lookup"><span data-stu-id="0504e-p104">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell. If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC. Users managed solely in the Office 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC. For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="0504e-115">Berechtigungen für Administratorrollengruppen</span><span class="sxs-lookup"><span data-stu-id="0504e-115">Admin role group permissions</span></span>
<span data-ttu-id="0504e-116"><a name="BKMK_adminrolegrouppermissions"> </a></span><span class="sxs-lookup"><span data-stu-id="0504e-116"></span></span>

<span data-ttu-id="0504e-p105">Sie können in EOP nur Administratorrollen konfigurieren. Benutzer können direkt in der Exchange-Verwaltungskonsole den standardmäßigen Administratorrollengruppen hinzugefügt beziehungsweise daraus entfernt werden. Es ist keine Anpassung der rollenbasierten Zugriffssteuerung verfügbar. Weitere Informationen finden Sie unter [Verwalten der Berechtigungen der Administratorrollengruppen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span><span class="sxs-lookup"><span data-stu-id="0504e-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="0504e-121">Domänenverwaltung</span><span class="sxs-lookup"><span data-stu-id="0504e-121">Domain management</span></span>
<span data-ttu-id="0504e-122"><a name="BKMK_domainmanagement"> </a></span><span class="sxs-lookup"><span data-stu-id="0504e-122"></span></span>

<span data-ttu-id="0504e-p106">Verwaltete Domänen sind Domänen, die mit EOP geschützt sind. In der Exchange-Verwaltungskonsole können verwaltete Domänen angezeigt und Domänentypen bearbeitet werden. Domänenbereitstellung und -verwaltung erfolgen im Office 365-Admin Center. Änderungen werden in der Exchange-Verwaltungskonsole wiedergegeben. Weitere Informationen finden Sie unter [Anzeigen oder Bearbeiten von verwalteten Domänen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span><span class="sxs-lookup"><span data-stu-id="0504e-p106">Managed domains are domains that are protected by EOP. Managed domains can be viewed and domain types can be edited in the EAC. Domain provisioning and management occurs in the Office 365 admin center and changes are reflected in the EAC. For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="0504e-127">Untergeordnete Domänen abgleichen</span><span class="sxs-lookup"><span data-stu-id="0504e-127">Match subdomains</span></span>
<span data-ttu-id="0504e-128"><a name="BKMK_EOP_Match_Subdomains"> </a></span><span class="sxs-lookup"><span data-stu-id="0504e-128"></span></span>

<span data-ttu-id="0504e-p107">Sie können in EOP E-Mail-Fluss zu Unterdomänen einer verwalteten Domäne aktivieren. Weitere Informationen finden Sie unter [Aktivieren des E-Mail-Flusses für Unterdomänen in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span><span class="sxs-lookup"><span data-stu-id="0504e-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="0504e-131">Verzeichnisbasierte Edge-Blockierung (DBEB)</span><span class="sxs-lookup"><span data-stu-id="0504e-131">Directory Based Edge Blocking (DBEB)</span></span>
<span data-ttu-id="0504e-132"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="0504e-132"></span></span>

<span data-ttu-id="0504e-p108">Das Feature Verzeichnisbasierte Edge-Blockierung ermöglicht es Ihnen, Nachrichten für ungültige Empfänger im Dienstnetzwerkumkreis abzulehnen. Mit der verzeichnisbasierten Edge-Blockierung können Administratoren E-Mail-aktivierte Empfänger in Office 365 hinzufügen und alle an nicht in Office 365 vorhandene E-Mail-Adressen gesendete Nachrichten blockieren. Wird eine Nachricht an eine gültige, in Office 365 vorhandene E-Mail-Adresse gesendet, wird die Nachricht durch die verbleibenden Filterebenen des Diensts (Antischadsoftware, Antispam, Transportregeln) weitergeleitet. Ist die Adresse nicht vorhanden, blockiert der Dienst die Nachricht bereits vor der Filterung. Zudem wird der Absender durch einen Unzustellbarkeitsbericht (Non-Delivery Report, NDR) informiert, dass die Nachricht nicht übermittelt wurde.</span><span class="sxs-lookup"><span data-stu-id="0504e-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="0504e-p109">Zum Aktivieren von DBEB ist eine bestimmte Benutzer- und Domänenkonfiguration erforderlich. Weitere Informationen finden Sie unter [Ablehnen von Nachrichten an ungültige Empfänger mithilfe von verzeichnisbasierter Edge-Blockierung](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span><span class="sxs-lookup"><span data-stu-id="0504e-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="0504e-139">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="0504e-139">Feature Availability</span></span>
<span data-ttu-id="0504e-140"><a name="BKMK_DBEB"> </a></span><span class="sxs-lookup"><span data-stu-id="0504e-140"></span></span>

<span data-ttu-id="0504e-141">Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="0504e-141">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

