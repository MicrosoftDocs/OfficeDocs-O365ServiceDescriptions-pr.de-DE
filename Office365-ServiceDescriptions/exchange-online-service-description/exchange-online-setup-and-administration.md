---
title: Einrichtung und Verwaltung in Exchange Online
ms.author: office365servicedesc
author: pamelaar
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
description: In diesem Artikel werden die Verwaltungssteuerelemente und-Unterstützung beschrieben, die zum Anpassen Exchange Online Einstellungen und zum aufrecht erhalten der Exchange Online Umgebung eines Unternehmens eingerichtet, aktiv und aktuell verfügbar sind. Er enthält Informationen über Self-Service-Verwaltungstools und -funktionen, die Organisationen zur Verfügung stehen, Verwaltungszuständigkeiten und Leistungsverpflichtungen von Microsoft sowie Dienst- und Produktupgrades.
ms.openlocfilehash: 19ec50b3f502ee111de05e1a115d17f16fec3569
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45133000"
---
# <a name="exchange-online-setup-and-administration"></a>Einrichtung und Verwaltung in Exchange Online

In diesem Artikel werden die Verwaltungssteuerelemente und-Unterstützung beschrieben, die zum Anpassen Exchange Online Einstellungen und zum aufrecht erhalten der Exchange Online Umgebung eines Unternehmens eingerichtet, aktiv und aktuell verfügbar sind. Er enthält Informationen über Self-Service-Verwaltungstools und -funktionen, die Organisationen zur Verfügung stehen, Verwaltungszuständigkeiten und Leistungsverpflichtungen von Microsoft sowie Dienst- und Produktupgrades.
  
## <a name="self-service-administration-tools"></a>Self-Service-Verwaltungstools

Obwohl Microsoft alle Exchange Online Rechenzentren direkt steuert und für die Gesamtsystem Leistung verantwortlich ist, kann nur ein Teil der Elemente gesteuert werden, die kombiniert werden, um die Gesamtbenutzer Erfahrung zu ermöglichen. Die Organisationen selbst sind für die Netzwerkverbindungen mit den Datencentern, das Fernnetz (WAN, Wide Area Network) des Kunden und die lokalen Netzwerke (LANs, Local Area Networks) des Kunden zuständig. Darüber hinaus sind sie für Benutzergeräte und deren Konfiguration verantwortlich.Sie sind auch für die Verwaltung der erforderlichen Lizenzierung pro Benutzer für alle gewünschten Features zuständig, einschließlich der Fähigkeit, diese Features zu verwalten, solange der Benutzer Zugriff auf die Funktion benötigt.
  
Exchange Online bietet daher den Kundenadministratoren die im Folgenden beschriebenen Tools, um eine Vielzahl von Aufgaben im Zusammenhang mit Nachrichten zu bewältigen:
  
- [Microsoft Office 365-Portal](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft 365 Admin Center](#microsoft-365-admin-center)
    
- [Exchange-Verwaltungskonsole](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Remote Windows PowerShell für Exchange Online](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365-Portal

Das Microsoft Office 365-Portal, auf [https://portal.office.com](https://portal.office.com), ist die Website, über die Administratoren und Partner Office 365-Dienste erwerben und verwalten. Zudem greifen Benutzer über dieses Portal auf Office 365-Tools für die Zusammenarbeit zu.
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 Admin Center

Das Microsoft 365 Admin Center ist das Webportal, aus dem die Dienstadministratoren der einzelnen Unternehmen Benutzerkonten und Einstellungen für die einzelnen Microsoft-Dienste, für die Sie abonniert haben, verwalten können. Innerhalb des Microsoft 365 admin Centers können Administratoren Links zur Exchange-Verwaltungskonsole (EAC) ausführen, auf der Sie Einstellungen für Exchange Online verwalten können. Weitere Informationen zum Einrichten und Ausführen von Microsoft 365 Admin Center finden Sie im folgenden Video: [Einführung in Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).
  
### <a name="exchange-admin-center"></a>Exchange-Verwaltungskonsole

Exchange Online provides a single unified management console that allows for ease of use and is optimized for management of on-premises, online, or hybrid deployments. The Exchange admin center (EAC) is where administrators can manage Exchange-specific settings.
  
Weitere Informationen zur Verwaltung von Exchange Online mithilfe des EAC finden Sie im Artikel zum [Exchange Admin Center](https://go.microsoft.com/fwlink/p/?LinkId=271807).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Remote Windows PowerShell für Exchange Online

Using remote Windows PowerShell, administrators can connect to Exchange Online to perform management tasks that are not available or practical using the EAC. These include the ability to automate repetitive tasks, extract data for custom reports, customize policies, and connect Exchange Online to existing infrastructure and processes. For more information, see [Connect to Exchange Online Using Remote PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=308994).
  
Exchange Online uses the same Windows PowerShell cmdlets as Exchange Server 2013, with certain commands and parameters unavailable because these features do not apply in Exchange Online. For a list of cmdlets for use with Exchange Online, see [Exchange Online cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
Administrators do not need to install any Exchange Server management or migration tools to use remote Windows PowerShell. However, administrators' computers must be running the Windows Management Framework 3.0, which contains Windows PowerShell v3 and WinRM 3.0; and Windows .NET Framework 4.5. These components are already installed on computers running Windows 8 or Windows Server 2012. Administrators can manually download these components for computers that are running Windows 7 or Windows Server 2008 R2.
  
> [!IMPORTANT]
> Um die Abwehr von DoS-Angriffen (Denial of Service) zu unterstützen, ist die Anzahl der offenen Windows PowerShell-Verbindungen zu Ihrer Exchange Online-Organisation auf drei beschränkt. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Self-Service-Funktionen für Exchange Online

Below are important capabilities that are available for managing Exchange Online by using the EAC, remote Windows PowerShell, and other tools. Many other settings can also be controlled with these tools, as described throughout this document.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Sicherheitsrichtlinien für mobile Geräte für Exchange Online

Exchange Online supports the same ActiveSync policies for mobile devices as Exchange Server 2013. Administrators can enforce and customize these security policies for specific users and groups by using the EAC or remote Windows PowerShell.
  
### <a name="message-tracking-for-exchange-online"></a>Nachrichtenverfolgung für Exchange Online

Die Nachrichtenverfolgung über das Feature Zustellungsberichte wird im folgenden Thema beschrieben: [Berichterstellungsfeatures und Tools zur Problembehandlung](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Verwendungsberichte für Exchange Online

Administrators can use remote Windows PowerShell to retrieve information about how people in their organizations use the Exchange Online service. Available information includes:
  
- Anzeigen der Postfachgröße für jeden Benutzer in der Organisation.
    
- Anzeigen benutzerdefinierter Berechtigungen für Postfächer, wie z. B. Stellvertretungszugriff.
    
- Extrahieren von Daten über den Zugriff mobiler Geräte, beispielsweise welche Benutzer über Exchange ActiveSync eine Verbindung herstellen, welche Geräte sie verwenden und wann sie zuletzt eine Verbindung hergestellt haben.
    
Remote Windows PowerShell cmdlets that start with "get-" can fetch data from the Exchange Online system. Administrators can export this information from Windows PowerShell in .csv format for advanced analysis or reporting.
  
Weitere Informationen über Windows PowerShell-Cmdlets für Exchange Online finden Sie unter [Exchange Online-Cmdlets](https://go.microsoft.com/fwlink/p/?LinkId=271808).
  
### <a name="auditing-for-exchange-online"></a>Überwachung für Exchange Online

Das Feature für die Überwachungsprotokollierung wird im folgenden Thema beschrieben: [Berichterstellungsfeatures und Tools zur Problembehandlung](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Dienst- und Produktupgrades für Exchange Online

Exchange Online customers benefit from periodic upgrades to the latest Exchange technology, including new releases of Exchange Server. These upgrades are made available at no additional charge, and ensure that customers are always using the latest Exchange software.
  
Nachdem Microsoft eine Hauptversion von Exchange veröffentlicht hat, haben Kunden bis zu 12 Monate Zeit, um ihren Dienst auf die neue Version zu aktualisieren.
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  