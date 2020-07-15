---
title: Kompatibilitäts-und Sicherheitsfeatures in Exchange Online Archivierung
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b03c74e0c760cf22c12e6973a544553d119471fe
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132739"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Kompatibilitäts-und Sicherheitsfeatures in Exchange Online Archivierung

## <a name="compliance-features-in-exchange-online-archiving"></a>Kompatibilitätsfunktionen der Exchange Online-Archivierung

Im folgenden Abschnitt werden die Kompatibilitätsfunktionen von Microsoft Exchange Online-Archivierung beschrieben.
  
### <a name="retention-policies"></a>Aufbewahrungsrichtlinien

Exchange Online-Archivierung bietet Aufbewahrungsrichtlinien, die Organisationen dabei helfen, ihre Verpflichtungen hinsichtlich E-Mails und anderen Kommunikationsformen zu reduzieren. Mithilfe dieser Richtlinien haben Administratoren die Möglichkeit, Aufbewahrungseinstellungen für bestimmte Ordner des Posteingangs eines Benutzers anzuwenden. Administratoren können Benutzern auch ein Menü mit Aufbewahrungsrichtlinien erteilen und die Richtlinien auf bestimmte Elemente, Unterhaltungen oder Ordner anwenden, die Outlook 2010 oder höher oder Outlook im Internet verwenden sollen. In Exchange Online-Archivierung verwalten Administratoren Aufbewahrungsrichtlinien aus der lokalen Infrastruktur.
  
Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.
  
Mit Outlook 2010 und höher und Outlook im Internet können Benutzer Aufbewahrungsrichtlinien auf Ordner, Unterhaltungen oder einzelne Nachrichten anwenden, und Sie können auch die angewendeten Aufbewahrungsrichtlinien und die erwarteten Löschungs Termine für Nachrichten anzeigen. Benutzer von anderen E-Mail-Clients können E-Mails basierend auf vom Administrator bereitgestellten Aufbewahrungsrichtlinien löschen oder archivieren lassen, verfügen aber nicht über das gleiche Maß an Transparenz und Steuerung.
  
The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Compliance-Archiv und Aufbewahrung für eventuelle Rechtsstreitigkeiten

When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.
  
In Exchange Online können Sie das Compliance-Archiv oder die Aufbewahrung für eventuelle Rechtsstreitigkeiten verwenden, um folgende Ziele zu erreichen:
  
- Platzieren von Benutzerpostfächern in Archiven und Beibehalten von Postfachelementen in unveränderbarer Form
    
- Beibehalten von Postfachelementen, die von Benutzern oder automatischen Löschprozessen wie z. B. MRM gelöscht werden
    
- Schützen von Postfachelementen vor Manipulation, Änderungen durch einen Benutzer oder automatische Prozesse, indem eine Kopie des ursprünglichen Elements gespeichert wird
    
- Beibehalten von Elementen auf unbestimmte Zeit oder über einen bestimmten Zeitraum
    
- Das Halten für den Benutzer transparent halten, ohne MRM anhalten zu müssen
    
- Verwenden von Compliance-eDiscovery, um Postfachelemente, einschließlich Elementen in einem Compliance-Archiv, zu durchsuchen
    
Außerdem können Sie das Compliance-Archiv für Folgendes verwenden:
  
- Durchsuchen und Halten von Elementen, die bestimmte Kriterien erfüllen
    
- Platzieren von Benutzern in mehreren Compliance-Archiven für unterschiedliche Fälle oder Untersuchungen
    
> [!NOTE]
> Wenn Sie für ein Postfach den In-Situ-Speicher oder das Beweissicherungsverfahren aktivieren, wird diese Einstellung auf das primäre und das Archivpostfach angewendet. 
  
Weitere Informationen finden Sie unter [Compliance-Archiv](https://go.microsoft.com/fwlink/p/?LinkId=271746).
  
> [!NOTE]
> Das standardmäßige Kontingent für den Ordner „Wiederherstellbare Elemente" beträgt 100 GB für Exchange Online-Archivierung-Benutzer. 
  
### <a name="in-place-ediscovery"></a>Compliance-eDiscovery

Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox. 
  
Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Sicherheitsfunktionen der Exchange Online-Archivierung

Im folgenden Abschnitt werden die Sicherheitsfunktionen von Microsoft Exchange Online-Archivierung beschrieben.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Verschlüsselung zwischen lokalen Servern und Exchange Online-Archivierung

TLS wird zum Verschlüsseln der Verbindung zwischen E-Mail-Servern verwendet, um Spoofing zu verhindern und die Vertraulichkeit von in der Übertragung befindlichen Nachrichten zu ermöglichen. TLS wird auch verwendet, um den lokalen e-Mail-Server Datenverkehr für Exchange Online Archivierung an Microsoft-Rechenzentren zu sichern.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Verschlüsselung zwischen Clients und Exchange Online-Archivierung

Bei Clientverbindungen zu Exchange Online-Archivierung wird die Sicherheit anhand der folgenden Verschlüsselungsmethoden erhöht:
  
- SSL wird zum Sichern von Outlook, Outlook im Internet und Exchange Webdienste-Datenverkehr mithilfe von TCP-Port 443 verwendet.
    
- Clientverbindungen zu lokalen Servern ändern sich mit der Einführung von Exchange Online-Archivierung nicht.
    
### <a name="encryption-smime-and-pgp"></a>Verschlüsselung: S/MIME und PGP

Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.
  
In ähnlicher Weise speichert Exchange Online-Archivierung Nachrichten, die anhand von clientseitigen, Drittanbieter-Verschlüsselungslösungen wie Pretty Good Privacy (PGP) verschlüsselt wurden.
  
### <a name="information-rights-management"></a>Verwaltung von Informationsrechten

Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Unterstützung für IRM in Outlook im Internet

Benutzer können IRM-geschützte Nachrichten nativ in Outlook im Web lesen und erstellen, so wie Sie es in Outlook tun können. Auf IRM-geschützte Nachrichten in Outlook im Internet kann über Internet Explorer, Firefox, Safari und Chrome (ohne Plug-in erforderlich) zugegriffen werden. Die Nachrichten bieten die Volltextsuche, die Unterhaltungsansicht und das Vorschaufenster. Dafür muss die Interoperabilität zwischen dem AD RMS(Active Directory Rights Management Services)-Server und der lokalen Exchange-Umgebung konfiguriert werden.
  
#### <a name="irm-search"></a>IRM-Suche

IRM-geschützte Nachrichten sind indiziert und durchsuchbar, einschließlich Kopfzeilen, Betreff, Text und Anlagen. Benutzer können IRM-geschützte Elemente in Outlook und Outlook im Internet durchsuchen, und Administratoren können IRM-geschützte Elemente mithilfe von in-Place eDiscovery oder mit dem Cmdlet **Search-Mailbox** durchsuchen.
  
### <a name="auditing"></a>Überwachung

Exchange Online-Archivierung bietet zwei Arten von integrierten Überwachungsfunktionen:
  
- **Administrator-Überwachungsprotokollierung** Die Administrator-Überwachungsprotokollierung ermöglicht Kunden das Nachverfolgen von Änderungen durch Administratoren in der Exchange Online-Archivierung-Umgebung, darunter Änderungen an der rollenbasierten Zugriffssteuerung oder an Exchange-Richtlinien und -Einstellungen. 
    
- **Postfachüberwachungsprotokollierung** Die Postfachüberwachungsprotokollierung ermöglicht Kunden das Nachverfolgen des Postfachzugriffs durch Benutzer, die nicht mit dem Postfachbesitzer identisch sind. 
    
Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.
  
Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Archivierungsdienst Beschreibung](exchange-online-archiving-service-description.md).
  

