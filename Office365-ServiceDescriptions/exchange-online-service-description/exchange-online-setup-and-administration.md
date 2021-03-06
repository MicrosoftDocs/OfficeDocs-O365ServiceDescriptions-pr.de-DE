---
title: Einrichtung und Verwaltung in Exchange Online
ms.author: office365servicedesc
author: pamelaar
manager: gailw
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
description: In diesem Artikel werden die Verwaltungssteuerelemente und -unterstützung beschrieben, die verfügbar sind, um Exchange Online-Einstellungen anzupassen und die Exchange Online einer Organisation auf dem laufenden zu halten. Er enthält Informationen über Self-Service-Verwaltungstools und -funktionen, die Organisationen zur Verfügung stehen, Verwaltungszuständigkeiten und Leistungsverpflichtungen von Microsoft sowie Dienst- und Produktupgrades.
ms.openlocfilehash: 56d7dbc7e5e6300172d120bbf1464fd2bbf0daf0
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652729"
---
# <a name="exchange-online-setup-and-administration"></a>Einrichtung und Verwaltung in Exchange Online

In diesem Artikel werden die Verwaltungssteuerelemente und -unterstützung beschrieben, die verfügbar sind, um Exchange Online-Einstellungen anzupassen und die Exchange Online einer Organisation auf dem laufenden zu halten. Er enthält Informationen über Self-Service-Verwaltungstools und -funktionen, die Organisationen zur Verfügung stehen, Verwaltungszuständigkeiten und Leistungsverpflichtungen von Microsoft sowie Dienst- und Produktupgrades.
  
## <a name="self-service-administration-tools"></a>Self-Service-Verwaltungstools

Obwohl Microsoft direkt alle Exchange Online steuert und für die Gesamtleistung des Systems verantwortlich ist, kann es nur einen Teil der Elemente steuern, die kombiniert werden, um die Gesamterfahrung für Benutzer zu ermöglichen. Die Organisationen selbst sind für die Netzwerkverbindungen mit den Datencentern, das Fernnetz (WAN, Wide Area Network) des Kunden und die lokalen Netzwerke (LANs, Local Area Networks) des Kunden zuständig. Darüber hinaus sind sie für Benutzergeräte und deren Konfiguration verantwortlich.Sie sind auch für die Verwaltung der erforderlichen Lizenzierung pro Benutzer für alle gewünschten Features zuständig, einschließlich der Fähigkeit, diese Features zu verwalten, solange der Benutzer Zugriff auf die Funktion benötigt.
  
Exchange Online bietet daher den Kundenadministratoren die im Folgenden beschriebenen Tools, um eine Vielzahl von Aufgaben im Zusammenhang mit Nachrichten zu bewältigen:
  
- [Microsoft Office 365-Portal](exchange-online-setup-and-administration.md#microsoft-office-365-portal)
    
- [Microsoft 365 Admin Center](#microsoft-365-admin-center)
    
- [Exchange-Verwaltungskonsole](exchange-online-setup-and-administration.md#exchange-admin-center)
    
- [Remote Windows PowerShell für Exchange Online](exchange-online-setup-and-administration.md#remote-windows-powershell-for-exchange-online)
    
### <a name="microsoft-office-365-portal"></a>Microsoft Office 365-Portal

Das Microsoft Office 365-Portal, auf [https://portal.office.com](https://portal.office.com), ist die Website, über die Administratoren und Partner Office 365-Dienste erwerben und verwalten. Zudem greifen Benutzer über dieses Portal auf Office 365-Tools für die Zusammenarbeit zu.
  
### <a name="microsoft-365-admin-center"></a>Microsoft 365 Admin Center

Das Microsoft 365 Admin Center ist das Webportal, über das der Dienstadministrator der einzelnen Unternehmen Benutzerkonten und Einstellungen für jede der Microsoft-Dienste verwalten kann, die sie abonnieren. Innerhalb des Microsoft 365 Admin Center können Administratoren Links zum Exchange Admin Center (EAC) folgen, wo sie einstellungen für bestimmte Benutzer Exchange Online. Weitere Informationen zum Einrichten und Ausführen des Microsoft 365 Admin Center finden Sie im folgenden Video: [Introducing Office 365 Enterprise](https://go.microsoft.com/fwlink/p/?LinkId=271806).
  
### <a name="exchange-admin-center"></a>Exchange-Verwaltungskonsole

Exchange Online bietet eine zentrale vereinheitlichte und benutzerfreundliche Verwaltungskonsole, die für die Verwaltung von lokalen, Online- und Hybridbereitstellungen optimiert wurde. In der Exchange-Verwaltungskonsole können Administratoren Exchange-spezifische Einstellungen verwalten.
  
Weitere Informationen zur Verwaltung von Exchange Online mithilfe des EAC finden Sie im Artikel zum [Exchange Admin Center](/exchange/exchange-admin-center).
  
### <a name="remote-windows-powershell-for-exchange-online"></a>Remote Windows PowerShell für Exchange Online

Über Windows PowerShell-Remotesitzungen können Administratoren eine Verbindung mit Exchange Online herstellen, um Verwaltungsaufgaben auszuführen, die im Exchange Admin Center nicht verfügbar oder nur kompliziert umzusetzen sind. Dazu zählen die Automatisierung repetitiver Aufgaben, die Extrahierung von Daten für benutzerdefinierte Berichte, die Anpassung von Richtlinien und die Einbindung von Exchange Online in vorhandene Infrastrukturen und Prozesse. Weitere Informationen finden Sie unter [Herstellen einer Verbindung mit Exchange Online mithilfe der Remote-PowerShell](/powershell/exchange/connect-to-exchange-online-powershell).
  
Exchange Online verwendet die gleichen Windows PowerShell-Cmdlets wie Exchange Server 2013. Einige Befehle und Parameter sind jedoch nicht verfügbar, da diese Features für Exchange Online nicht gelten. Eine Liste der Cmdlets für Exchange Online finden Sie unter [Exchange Online-Cmdlets](/powershell/exchange/exchange-online-powershell).
  
Administratoren müssen keine Verwaltungs- oder Migrationstools von Exchange Server installieren, um Windows PowerShell-Remotesitzungen zu nutzen. Auf den Computern der Administratoren müssen jedoch Windows Management Framework 3.0 (in dieser Komponente sind Windows PowerShell v3 und WinRM 3.0 enthalten) und Windows .NET Framework 4.5 ausgeführt werden. Diese Komponenten sind auf Computern unter Windows 8 oder Windows Server 2012 bereits installiert. Administratoren können diese Komponenten für Computer unter Windows 7 oder Windows Server 2008 R2 manuell herunterladen.
  
> [!IMPORTANT]
> Um die Abwehr von DoS-Angriffen (Denial of Service) zu unterstützen, ist die Anzahl der offenen Windows PowerShell-Verbindungen zu Ihrer Exchange Online-Organisation auf drei beschränkt. 
  
## <a name="self-service-capabilities-for-exchange-online"></a>Self-Service-Funktionen für Exchange Online

Im Folgenden sind wichtige Funktionen aufgeführt, die für die Verwaltung von Exchange Online mit der Exchange-Verwaltungskonsole, mit Windows PowerShell-Remotesitzungen und mit anderen Tools verfügbar sind. Darüber hinaus können viele andere Einstellungen mit diesen Tools gesteuert werden, wie in diesem Dokument beschrieben.
  
### <a name="mobile-device-security-policies-for-exchange-online"></a>Sicherheitsrichtlinien für mobile Geräte für Exchange Online

Exchange Online unterstützt die gleichen ActiveSync-Richtlinien für mobile Geräte wie Exchange Server 2013. Administratoren können diese Sicherheitsrichtlinien für bestimmte Benutzer und Gruppen mit der Exchange-Verwaltungskonsole oder mit Windows PowerShell-Remotesitzungen durchsetzen und anpassen.
  
### <a name="message-tracking-for-exchange-online"></a>Nachrichtenverfolgung für Exchange Online

Die Nachrichtenverfolgung über das Feature "Übermittlungsberichte" wird im folgenden Thema [beschrieben: Berichtsfeatures und Problembehandlungstools](reporting-features-and-troubleshooting-tools.md).
  
### <a name="usage-reporting-for-exchange-online"></a>Verwendungsberichte für Exchange Online

Administratoren können mit Windows PowerShell-Remotesitzungen Informationen darüber abrufen, wie der Exchange Online-Dienst von den Benutzern in der Organisation verwendet wird. Dazu zählen folgende Informationen:
  
- Anzeigen der Postfachgröße für jeden Benutzer in der Organisation.
    
- Anzeigen benutzerdefinierter Berechtigungen für Postfächer, wie z. B. Stellvertretungszugriff.
    
- Extrahieren von Daten über den Zugriff mobiler Geräte, beispielsweise welche Benutzer über Exchange ActiveSync eine Verbindung herstellen, welche Geräte sie verwenden und wann sie zuletzt eine Verbindung hergestellt haben.
    
Cmdlets von Windows PowerShell-Remotesitzungen, die mit "get-" beginnen, können Daten aus dem Exchange Online-System abrufen. Administratoren können diese Informationen aus Windows PowerShell in das CSV-Format exportieren, um sie in genaueren Analysen und Berichten zu verwenden.
  
Weitere Informationen über Windows PowerShell-Cmdlets für Exchange Online finden Sie unter [Exchange Online-Cmdlets](/powershell/exchange/exchange-online-powershell).
  
### <a name="auditing-for-exchange-online"></a>Überwachung für Exchange Online

Das Überwachungsprotokollierungsfeature wird im folgenden Thema beschrieben: [Berichtsfeatures und Problembehandlungstools](reporting-features-and-troubleshooting-tools.md).
  
## <a name="service-and-product-upgrades-for-exchange-online"></a>Dienst- und Produktupgrades für Exchange Online

Exchange Online-Kunden profitieren von regelmäßigen Upgrades auf die aktuelle Exchange-Technologie, einschließlich neuer Exchange Server-Versionen. Diese Upgrades werden ohne zusätzliche Gebühren zur Verfügung gestellt. Sie stellen sicher, dass die Kunden immer die aktuelle Exchange-Software verwenden.
  
Nachdem Microsoft eine Hauptversion von Exchange veröffentlicht hat, haben Kunden bis zu 12 Monate Zeit, um ihren Dienst auf die neue Version zu aktualisieren.
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie [unter Exchange Online Service description](exchange-online-service-description.md).
