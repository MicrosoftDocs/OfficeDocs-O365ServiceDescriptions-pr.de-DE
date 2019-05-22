---
title: Einrichtung und Verwaltung in Exchange Online
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-administration-and-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 80c07748-ac57-4b90-97dd-a2d1115009a6
description: In diesem Abschnitt werden die Verwaltungssteuerelemente und-Unterstützung beschrieben, die zum Anpassen Exchange Online Einstellungen und zum aufrecht erhalten der Exchange Online Umgebung eines Unternehmens eingerichtet, aktiv und aktuell verfügbar sind. Er enthält Informationen über Self-Service-Verwaltungstools und -funktionen, die Organisationen zur Verfügung stehen, Verwaltungszuständigkeiten und Leistungsverpflichtungen von Microsoft sowie Dienst- und Produktupgrades.
ms.openlocfilehash: 93eb996df011a83658aa953521a469d7822f9118
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342784"
---
# <a name="exchange-online-setup-and-administration"></a><span data-ttu-id="663d8-104">Einrichtung und Verwaltung in Exchange Online</span><span class="sxs-lookup"><span data-stu-id="663d8-104">Exchange Online Setup and Administration</span></span>

<span data-ttu-id="663d8-105">In diesem Abschnitt werden die Verwaltungssteuerelemente und-Unterstützung beschrieben, die zum Anpassen Exchange Online Einstellungen und zum aufrecht erhalten der Exchange Online Umgebung eines Unternehmens eingerichtet, aktiv und aktuell verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="663d8-105">This section describes the administration controls and support that are available to customize Exchange Online settings and keep an organization's Exchange Online environment up, running, and current.</span></span> <span data-ttu-id="663d8-106">Er enthält Informationen über Self-Service-Verwaltungstools und -funktionen, die Organisationen zur Verfügung stehen, Verwaltungszuständigkeiten und Leistungsverpflichtungen von Microsoft sowie Dienst- und Produktupgrades.</span><span class="sxs-lookup"><span data-stu-id="663d8-106">It includes information about self-service administration tools and capabilities available to organizations; Microsoft administration responsibilities and performance commitments; and service and product upgrades.</span></span>
  
## <a name="self-service-administration-tools"></a><span data-ttu-id="663d8-107">Self-Service-Verwaltungstools</span><span class="sxs-lookup"><span data-stu-id="663d8-107">Self-service administration tools</span></span>

<span data-ttu-id="663d8-p103">Zwar kontrolliert Microsoft direkt alle Exchange Online-Datencenter und ist für die Leistung des gesamten Systems zuständig, Microsoft kann aber nur einen Teil der Elemente steuern, die zusammen das Gesamterlebnis für Office 365-Benutzer ausmachen. Die Organisationen selbst sind für die Netzwerkverbindungen mit den Datencentern, das Fernnetz (WAN, Wide Area Network) des Kunden und die lokalen Netzwerke (LANs, Local Area Networks) des Kunden zuständig. Darüber hinaus sind sie für Benutzergeräte und deren Konfiguration verantwortlich. Sie sind auch für die Verwaltung der erforderlichen Lizenzierung pro Benutzer für alle gewünschten Features zuständig, einschließlich der Fähigkeit, diese Features zu verwalten, solange der Benutzer Zugriff auf die Funktion benötigt.</span><span class="sxs-lookup"><span data-stu-id="663d8-p103">Although Microsoft directly controls all Exchange Online data centers and is responsible for overall system performance, it can control only a portion of the elements that combine to provide the total experience for Office 365 users. Organizations themselves are responsible for the network connections to the data centers, the customer's wide area network (WAN), and the customer's local area networks (LANs). Additionally, they are in charge of user devices and their configuration.  They are also responsible for maintaining the required licensing per user for any desired feature, including, but not limited to, the ability to manage these features, for as long as the user needs access to the feature.</span></span>
  
<span data-ttu-id="663d8-112">Exchange Online bietet daher den Kundenadministratoren die im Folgenden beschriebenen Tools, um eine Vielzahl von Aufgaben im Zusammenhang mit Nachrichten zu bewältigen:</span><span class="sxs-lookup"><span data-stu-id="663d8-112">Exchange Online therefore provides customer administrators with the following tools, described below, to manage a variety of messaging-related tasks:</span></span>
  
- [<span data-ttu-id="663d8-113">Microsoft Office 365-Portal</span><span class="sxs-lookup"><span data-stu-id="663d8-113">Microsoft Office 365 portal</span></span>](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [<span data-ttu-id="663d8-114">Microsoft 365 Admin Center</span><span class="sxs-lookup"><span data-stu-id="663d8-114">Microsoft 365 admin center</span></span>](#microsoft-365-admin-center)
    
- [<span data-ttu-id="663d8-115">Exchange-Verwaltungskonsole</span><span class="sxs-lookup"><span data-stu-id="663d8-115">Exchange admin center</span></span>](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [<span data-ttu-id="663d8-116">Remote Windows PowerShell für Exchange Online</span><span class="sxs-lookup"><span data-stu-id="663d8-116">Remote Windows PowerShell for Exchange Online</span></span>](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a><span data-ttu-id="663d8-117">Microsoft Office 365-Portal</span><span class="sxs-lookup"><span data-stu-id="663d8-117">Microsoft Office 365 portal</span></span>
<span data-ttu-id="663d8-118"><a name="BKMK_MicrosoftOnlineServicesPortal"> </a></span><span class="sxs-lookup"><span data-stu-id="663d8-118"></span></span>

<span data-ttu-id="663d8-119">Das Microsoft Office 365-Portal, auf [https://portal.office.com](https://portal.office.com), ist die Website, über die Administratoren und Partner Office 365-Dienste erwerben und verwalten. Zudem greifen Benutzer über dieses Portal auf Office 365-Tools für die Zusammenarbeit zu.</span><span class="sxs-lookup"><span data-stu-id="663d8-119">The Microsoft Office 365 portal, at [https://portal.office.com](https://portal.office.com), is the website through which administrators and partners purchase and manage Office 365 services and where users access and use Office 365 collaborative tools.</span></span>
  
### <a name="microsoft-365-admin-center"></a><span data-ttu-id="663d8-120">Microsoft 365 Admin Center</span><span class="sxs-lookup"><span data-stu-id="663d8-120">Microsoft 365 admin center</span></span>
<span data-ttu-id="663d8-121"><a name="BKMK_Office365admincenterl"> </a></span><span class="sxs-lookup"><span data-stu-id="663d8-121"></span></span>

<span data-ttu-id="663d8-122">Das Microsoft 365 Admin Center ist das Webportal, aus dem die Dienstadministratoren der einzelnen Unternehmen Benutzerkonten und Einstellungen für die einzelnen Office 365 Dienste verwalten können, für die Sie sich anmelden.</span><span class="sxs-lookup"><span data-stu-id="663d8-122">The Microsoft 365 admin center is the web portal from which each company's service administrator can manage user accounts and settings for each of the Office 365 services to which they subscribe.</span></span> <span data-ttu-id="663d8-123">Innerhalb des Microsoft 365 admin Centers können Administratoren Links zur Exchange-Verwaltungskonsole (EAC) ausführen, auf der Sie Einstellungen für Exchange Online verwalten können.</span><span class="sxs-lookup"><span data-stu-id="663d8-123">From within the Microsoft 365 admin center, administrators can follow links to the Exchange admin center (EAC), where they can manage settings specific to Exchange Online.</span></span> <span data-ttu-id="663d8-124">Weitere Informationen zum Einrichten und Ausführen von Microsoft 365 Admin Center finden Sie im folgenden Video: [Einführung in Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span><span class="sxs-lookup"><span data-stu-id="663d8-124">For more information about getting up and running using the Microsoft 365 admin center, see the following video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).</span></span>
  
### <a name="exchange-admin-center"></a><span data-ttu-id="663d8-125">Exchange Admin Center</span><span class="sxs-lookup"><span data-stu-id="663d8-125">Exchange admin center</span></span>
<span data-ttu-id="663d8-126"><a name="BKMK_ExchangeAdministrationCenter"> </a></span><span class="sxs-lookup"><span data-stu-id="663d8-126"></span></span>

<span data-ttu-id="663d8-p105">Exchange Online bietet eine zentrale vereinheitlichte und benutzerfreundliche Verwaltungskonsole, die für die Verwaltung von lokalen, Online- und Hybridbereitstellungen optimiert wurde. In der Exchange-Verwaltungskonsole können Administratoren Exchange-spezifische Einstellungen verwalten.</span><span class="sxs-lookup"><span data-stu-id="663d8-p105">Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.</span></span>
  
<span data-ttu-id="663d8-129">Weitere Informationen zur Verwaltung von Exchange Online mithilfe des EAC finden Sie im Artikel zum [Exchange Admin Center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span><span class="sxs-lookup"><span data-stu-id="663d8-129">For more information about how to use the EAC to manage Exchange Online, see [Exchange admin center](https://go.microsoft.com/fwlink/p/?LinkId=271807).</span></span>
  
### <a name="remote-windows-powershell-for-exchange-online"></a><span data-ttu-id="663d8-130">Remote Windows PowerShell für Exchange Online</span><span class="sxs-lookup"><span data-stu-id="663d8-130">Remote Windows PowerShell for Exchange Online</span></span>
<span data-ttu-id="663d8-131"><a name="BKMK_RemoteWindowsPowerShell"> </a></span><span class="sxs-lookup"><span data-stu-id="663d8-131"></span></span>

<span data-ttu-id="663d8-p106">Über Windows PowerShell-Remotesitzungen können Administratoren eine Verbindung mit Exchange Online herstellen, um Verwaltungsaufgaben auszuführen, die im Exchange Admin Center nicht verfügbar oder nur kompliziert umzusetzen sind. Dazu zählen die Automatisierung repetitiver Aufgaben, die Extrahierung von Daten für benutzerdefinierte Berichte, die Anpassung von Richtlinien und die Einbindung von Exchange Online in vorhandene Infrastrukturen und Prozesse. Weitere Informationen finden Sie unter [Herstellen einer Verbindung mit Exchange Online mithilfe der Remote-PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span><span class="sxs-lookup"><span data-stu-id="663d8-p106">Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).</span></span>
  
<span data-ttu-id="663d8-p107">Exchange Online verwendet die gleichen Windows PowerShell-Cmdlets wie Exchange Server 2013. Einige Befehle und Parameter sind jedoch nicht verfügbar, da diese Features für Exchange Online nicht gelten. Eine Liste der Cmdlets für Exchange Online finden Sie unter [Exchange Online-Cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="663d8-p107">Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
<span data-ttu-id="663d8-p108">Administratoren müssen keine Verwaltungs- oder Migrationstools von Exchange Server installieren, um Windows PowerShell-Remotesitzungen zu nutzen. Auf den Computern der Administratoren müssen jedoch Windows Management Framework 3.0 (in dieser Komponente sind Windows PowerShell v3 und WinRM 3.0 enthalten) und Windows .NET Framework 4.5 ausgeführt werden. Diese Komponenten sind auf Computern unter Windows 8 oder Windows Server 2012 bereits installiert. Administratoren können diese Komponenten für Computer unter Windows 7 oder Windows Server 2008 R2 manuell herunterladen.</span><span class="sxs-lookup"><span data-stu-id="663d8-p108">Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="663d8-141">Um die Abwehr von DoS-Angriffen (Denial of Service) zu unterstützen, ist die Anzahl der offenen Windows PowerShell-Verbindungen zu Ihrer Exchange Online-Organisation auf drei beschränkt.</span><span class="sxs-lookup"><span data-stu-id="663d8-141">To help prevent denial of service (DoS) attacks, you're limited to three open Windows PowerShell connections to your Exchange Online organization.</span></span> 
  
## <a name="self-service-capabilities-for-exchange-online"></a><span data-ttu-id="663d8-142">Self-Service-Funktionen für Exchange Online</span><span class="sxs-lookup"><span data-stu-id="663d8-142">Self-service capabilities for Exchange Online</span></span>

<span data-ttu-id="663d8-p109">Im Folgenden sind wichtige Funktionen aufgeführt, die für die Verwaltung von Exchange Online mit der Exchange-Verwaltungskonsole, mit Windows PowerShell-Remotesitzungen und mit anderen Tools verfügbar sind. Darüber hinaus können viele andere Einstellungen mit diesen Tools gesteuert werden, wie in diesem Dokument beschrieben.</span><span class="sxs-lookup"><span data-stu-id="663d8-p109">Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.</span></span>
  
### <a name="mobile-device-security-policies-for-exchange-online"></a><span data-ttu-id="663d8-145">Sicherheitsrichtlinien für mobile Geräte für Exchange Online</span><span class="sxs-lookup"><span data-stu-id="663d8-145">Mobile device security policies for Exchange Online</span></span>

<span data-ttu-id="663d8-p110">Exchange Online unterstützt die gleichen ActiveSync-Richtlinien für mobile Geräte wie Exchange Server 2013. Administratoren können diese Sicherheitsrichtlinien für bestimmte Benutzer und Gruppen mit der Exchange-Verwaltungskonsole oder mit Windows PowerShell-Remotesitzungen durchsetzen und anpassen.</span><span class="sxs-lookup"><span data-stu-id="663d8-p110">Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.</span></span>
  
### <a name="message-tracking-for-exchange-online"></a><span data-ttu-id="663d8-148">Nachrichtenverfolgung für Exchange Online</span><span class="sxs-lookup"><span data-stu-id="663d8-148">Message tracking for Exchange Online</span></span>

<span data-ttu-id="663d8-149">Das Feature zur Nachrichtenverfolgung über Zustellungsberichte wird im folgenden Thema beschrieben: [Berichterstellungsfeatures und Tools zur Problembehandlung](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="663d8-149">Message tracking via the Delivery Reports feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
### <a name="usage-reporting-for-exchange-online"></a><span data-ttu-id="663d8-150">Verwendungsberichte für Exchange Online</span><span class="sxs-lookup"><span data-stu-id="663d8-150">Usage reporting for Exchange Online</span></span>

<span data-ttu-id="663d8-p111">Administratoren können mit Windows PowerShell-Remotesitzungen Informationen darüber abrufen, wie der Exchange Online-Dienst von den Benutzern in der Organisation verwendet wird. Dazu zählen folgende Informationen:</span><span class="sxs-lookup"><span data-stu-id="663d8-p111">Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:</span></span>
  
- <span data-ttu-id="663d8-153">Anzeigen der Postfachgröße für jeden Benutzer in der Organisation.</span><span class="sxs-lookup"><span data-stu-id="663d8-153">Showing the mailbox size for each user in the organization.</span></span>
    
- <span data-ttu-id="663d8-154">Anzeigen benutzerdefinierter Berechtigungen für Postfächer, wie z. B. Stellvertretungszugriff.</span><span class="sxs-lookup"><span data-stu-id="663d8-154">Displaying custom permissions that are set on mailboxes, such as delegate access.</span></span>
    
- <span data-ttu-id="663d8-155">Extrahieren von Daten über den Zugriff mobiler Geräte, beispielsweise welche Benutzer über Exchange ActiveSync eine Verbindung herstellen, welche Geräte sie verwenden und wann sie zuletzt eine Verbindung hergestellt haben.</span><span class="sxs-lookup"><span data-stu-id="663d8-155">Extracting data about mobile device access, such as which users are connecting through Exchange ActiveSync, what devices they are using, and when they last connected.</span></span>
    
<span data-ttu-id="663d8-p112">Cmdlets von Windows PowerShell-Remotesitzungen, die mit "get-" beginnen, können Daten aus dem Exchange Online-System abrufen. Administratoren können diese Informationen aus Windows PowerShell in das CSV-Format exportieren, um sie in genaueren Analysen und Berichten zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="663d8-p112">Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.</span></span>
  
<span data-ttu-id="663d8-158">Weitere Informationen über Windows PowerShell-Cmdlets für Exchange Online finden Sie unter [Exchange Online-Cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span><span class="sxs-lookup"><span data-stu-id="663d8-158">For more information about Windows PowerShell cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).</span></span>
  
### <a name="auditing-for-exchange-online"></a><span data-ttu-id="663d8-159">Überwachung für Exchange Online</span><span class="sxs-lookup"><span data-stu-id="663d8-159">Auditing for Exchange Online</span></span>

<span data-ttu-id="663d8-160">Das Feature für die Überwachungsprotokollierung wird im folgenden Thema beschrieben: [Berichterstellungsfeatures und Tools zur Problembehandlung](reporting-features-and-troubleshooting-tools.md).</span><span class="sxs-lookup"><span data-stu-id="663d8-160">The audit logging feature is described in the following topic: [Reporting Features and Troubleshooting Tools](reporting-features-and-troubleshooting-tools.md).</span></span>
  
## <a name="service-and-product-upgrades-for-exchange-online"></a><span data-ttu-id="663d8-161">Dienst- und Produktupgrades für Exchange Online</span><span class="sxs-lookup"><span data-stu-id="663d8-161">Service and product upgrades for Exchange Online</span></span>

<span data-ttu-id="663d8-p113">Exchange Online-Kunden profitieren von regelmäßigen Upgrades auf die aktuelle Exchange-Technologie, einschließlich neuer Exchange Server-Versionen. Diese Upgrades werden ohne zusätzliche Gebühren zur Verfügung gestellt. Sie stellen sicher, dass die Kunden immer die aktuelle Exchange-Software verwenden.</span><span class="sxs-lookup"><span data-stu-id="663d8-p113">Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.</span></span>
  
<span data-ttu-id="663d8-164">Nachdem Microsoft eine Hauptversion von Exchange veröffentlicht hat, haben Kunden bis zu 12 Monate Zeit, um ihren Dienst auf die neue Version zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="663d8-164">After a major version of Exchange is released by Microsoft, customers have up to 12 months to upgrade their service to the new release.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="663d8-165">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="663d8-165">Feature Availability</span></span>

<span data-ttu-id="663d8-166">Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="663d8-166">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

