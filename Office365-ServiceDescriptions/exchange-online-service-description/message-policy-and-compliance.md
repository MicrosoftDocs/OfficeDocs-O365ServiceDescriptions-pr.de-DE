---
title: Messagingrichtlinie und -einhaltung
ms.author: office365servicedesc
author: pamelaar
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
ms.openlocfilehash: 5565085472d43230f9059e1dcac115105a2e20d5
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132699"
---
# <a name="message-policy-and-compliance"></a>Messagingrichtlinie und -einhaltung

## <a name="archiving-exchange-online-based-mailboxes"></a>Archivieren von Exchange Online-basierten Postfächern

Exchange Online mailboxes reside in the cloud, and archiving them requires unique hosting environments. In some cases, Exchange Online can also be used to archive on-premises mailboxes in the cloud. The options for archiving with Exchange Online are described in this section.
  
Exchange Online bietet integrierte Archivierungsfunktionen für cloudbasierte Postfächer, einschließlich eines Compliance-Archivs, dass Benutzern einen praktischen Speicherort für ältere E-Mails zur Verfügung stellt. Bei einem in-Place-Archiv handelt es sich um einen speziellen Typ von Postfach, der neben den primären Postfachordnern eines Benutzers in Outlook und Outlook im Internet angezeigt wird. Benutzer können auf das Archiv genauso zugreifen und es durchsuchen, wie sie es von ihren primären Postfächern gewohnt sind. Die Verfügbarkeit der Funktionalität hängt vom jeweiligen Client ab:
  
- **Outlook 2016, Outlook 2013, Outlook 2010 und Outlook im Internet** Benutzer haben Zugriff auf die vollständigen Features des Archivs sowie auf verwandte Compliance-Features wie die Steuerung der Aufbewahrungs-und archivrichtlinien. 
    
- **Outlook 2007** Users have basic support for the In-Place Archive, but not all archiving and compliance features are available. For example, users cannot apply retention or archive policies to mailbox items and must rely on administrator-provisioned policies instead. 
    
Administratoren verwenden die Exchange-Verwaltungskonsole oder Windows PowerShell-Remotesitzungen, um für bestimmte Benutzer die Funktion für persönliche Archive zu aktivieren.
  
Weitere Informationen finden Sie unter:
  
- [Archivieren von Postfächern in Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-archiving-service-description/archive-features)
    
- [Aktivieren oder Deaktivieren von Archivpostfächern in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Größe des Archivs

In einem persönlichen Archiv können nur die Nachrichtendaten eines Benutzers gespeichert werden. Die Zuweisung von Speicher hängt vom jeweiligen Abonnementplan ab. Weitere Informationen zur Größe von archivpostfächern finden Sie im Abschnitt "Speichergrenzwerte für Postfächer" in [Exchange Online Grenzwerte](exchange-online-limits.md).
  
> [!IMPORTANT]
> - Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung in ein Exchange Online-Postfach zu kopieren. Microsoft behält sich das Recht vor, eine unbegrenzte Archivierung in Fällen zu verweigern, in denen ein Post Fach Archiv nicht in einem persönlichen Szenario oder in anderen Fällen ungeeigneter Verwendung verwendet wird.
> - In-Place Archive has specific licensing requirements for Outlook users. Outlook 2007 users must have the Office 2007 Cumulative Update for February 2011 to access the personal archive. 
> - Exchange Online unterstützt das Cmdlet _New-MailboxImportRequest_ Windows PowerShell von Exchange Server 2010 Service Pack 1 oder höher für den Administrator gesteuerten Import von PST-Dateien in ein persönliches Archiv nicht. Wenn ein Benutzer sowohl über das primäre Postfach als auch über das Archiv in Exchange Online verfügt, kann ein Administrator das kostenlose Tool "PST Capture" verwenden, um Daten aus PST-Dateien in das primäre Postfach oder Archiv des Benutzers zu importieren.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Cloudbasierte Archivierung von lokalen Postfächern

Using Exchange Online for cloud-based archiving of on-premises Exchange Server 2010 or later mailboxes is possible with Microsoft Exchange Online Archiving, a hosted archiving solution from Microsoft. This requires that the on-premises organization be in Hybrid mode or be set up for Exchange Online Archiving.
  
> [!IMPORTANT]
> Wenn Benutzer über ein lokales Postfach auf einem Exchange 2010-Postfachserver verfügen und eine Richtlinie für verwaltete Ordner anwenden, ist die Aktivierung von lokalen oder cloudbasierten Compliance-Archiven nicht möglich. 
  
## <a name="retention-tags-and-retention-policies"></a>Aufbewahrungstags und Aufbewahrungsrichtlinien

Exchange Online bietet Aufbewahrungsrichtlinien, die Organisationen dabei helfen, ihre Verpflichtungen hinsichtlich E-Mails und anderen Kommunikationsformen zu reduzieren. Mithilfe dieser Richtlinien haben Administratoren die Möglichkeit, Aufbewahrungseinstellungen für bestimmte Ordner des Posteingangs eines Benutzers anzuwenden. Administratoren können Benutzern auch ein Menü mit Aufbewahrungsrichtlinien erteilen und die Richtlinien auf bestimmte Elemente, Unterhaltungen oder Ordner anwenden, die Outlook 2010 oder höher oder Outlook im Internet verwenden sollen.
  
In Exchange Online können Administratoren die Aufbewahrungsrichtlinien mithilfe der Exchange-Verwaltungskonsole oder von Windows PowerShell-Remotesitzungen verwalten.
  
Exchange Online offers two types of policies: archive policies and delete policies. Both types can be combined on the same item or folder. For example, a user can tag an email message to be automatically moved to the In-Place Archive in a specified number of days and deleted after another span of days.
  
Mit Outlook 2010 oder höher und Outlook im Internet können Benutzer Aufbewahrungsrichtlinien auf Ordner, Unterhaltungen oder einzelne Nachrichten anwenden. Außerdem können sie die geltenden Aufbewahrungsrichtlinien und vorgesehenen Löschtermine von Nachrichten anzeigen. Benutzer von anderen E-Mail-Clients können E-Mails nur basierend auf serverseitigen, vom Administrator definierten Aufbewahrungsrichtlinien löschen oder archivieren lassen.
  
The retention policy capabilities offered in Exchange Online are the same as those offered in Exchange Server 2010 Service Pack 2 RU4. Administrators can use remote Windows PowerShell to migrate retention policies from on-premises Exchange Server 2010 or later environments to Exchange Online.
  
> [!IMPORTANT]
> Verwaltete Ordner, ein älterer Ansatz für die Messaging-Datensatzverwaltung, der in Exchange Server 2007 eingeführt wurde, stehen in Exchange Online nicht zur Verfügung. 
  
Weitere Informationen finden Sie unter [Aufbewahrungstags und Aufbewahrungsrichtlinien](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Verschlüsselung von Daten im Ruhezustand

Die Verschlüsselung von Kundendaten im Ruhezustand wird von mehreren dienstseitigen Technologien bereitgestellt, einschließlich BitLocker, DKM, Azure Storage Service Encryption und Service Encryption in Exchange Online, Skype for Business, OneDrive für Unternehmen und SharePoint Online. Office 365-Dienstverschlüsselung umfasst eine Option zum Verwenden von Kunden verwalteter Verschlüsselungsschlüssel, die in Azure Key Vault gespeichert sind. Diese vom Kunden verwaltete Schlüssel Option, die als " [Kundenschlüssel](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key?redirectSourcePath=%252fen-us%252farticle%252fControlling-your-data-in-Office-365-using-Customer-Key-f2cd475a-e592-46cf-80a3-1bfb0fa17697)" bezeichnet wird, steht für Exchange Online, SharePoint Online und OneDrive für Unternehmen zur Verfügung. 
  
### <a name="bitlocker"></a>BitLocker

Microsoft-Server verwenden BitLocker zum Verschlüsseln der Datenträgerlaufwerke, die Kundendaten im Ruhezustand auf Volumen Ebene enthalten. BitLocker-Verschlüsselung ist eine Datenverschlüsselungsfunktion, die in Windows integriert ist. BitLocker ist eine der Technologien, die zum Schutz vor Bedrohungen verwendet werden, falls andere Prozesse oder Steuerelemente hinfällig werden (z. B. Zugriffssteuerung oder Access Control oder Recycling von Hardware), sodass andere Personen möglicherweise physischen Zugriff auf Laufwerke mit Kundendaten erlangen könnten. In diesem Fall eliminiert BitLocker das potenzielle Risiko für Datendiebstahl oder Offenlegung aufgrund von verloren gegangener, gestohlener oder nicht ordnungsgemäß außer Betrieb gesetzter Computer und Datenträger. 
  
### <a name="distributed-key-manager"></a>Distributed Key Manager

In addition to BitLocker, we use a technology called Distributed Key Manager (DKM). DKM is a client-side functionality that uses a set of secret keys to encrypt and decrypt information. Only members of a specific security group in Active Directory Domain Services can access those keys to decrypt the data that is encrypted by DKM. In Exchange Online, only certain service accounts under which the Exchange processes run are part of that security group. As part of standard operating procedure in the datacenter, no human is given credentials that are part of this security group and therefore no human has access to the keys that can decrypt these secrets.
  
## <a name="customer-key"></a>Kundenschlüssel

Mit dem Kundenschlüssel steuern Sie die Verschlüsselungsschlüssel Ihrer Organisation und konfigurieren diese dann so, dass Sie Ihre Daten im Ruhezustand in den Microsoft-Rechenzentren verschlüsseln. Zu den Daten im Ruhezustand gehören Daten aus Exchange Online und Skype for Business, die in SharePoint Online und OneDrive for Business in Postfächern und Dateien gespeichert sind. Weitere Informationen finden Sie unter [Controlling Your Data in using Customer Key](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key) and [Service Encryption with Customer Key FAQ](https://docs.microsoft.com/office365/securitycompliance/service-encryption-with-customer-key-faq).
  
## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

Office 365 Message Encryption allows email users to send encrypted email messages to anyone. We announced new capabilities in Office Message Encryption that leverage the protection features in Azure Information Encryption. These new capabilities provided enhanced end user experiences that make it easier to share and collaborate on protected messages with anyone inside or outside the organization. The new Office Message Encryption capabilities have some setup requirements. See Set up new Office 365 Message Encryption capabilities built on top of Azure Information Protection. Customers on legacy Office 365 Message Encryption do not get the new capabilities without following the set up guidance provided above. Please read the [FAQ](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e) for more details on what's included in the new vs. legacy Office 365 Message Encryption capabilities. 

Office 365 erweiterte Nachrichtenverschlüsselung bietet zusätzlichen Schutz, indem Nachrichtenablauf und-Sperrung zugelassen werden.  Sie können auch mehrere Vorlagen für verschlüsselte e-Mails erstellen, die von Ihrer Organisation stammen.  Die erweiterte Nachrichtenverschlüsselung ist in Microsoft 365 E5, Office 365 E5, Microsoft 365 E5 (Preise für gemeinnützige Mitarbeiter), Office 365 Enterprise E5 (Nonprofit-Mitarbeiter Preise) oder Office 365 Education A5 enthalten. Wenn Ihre Organisation über ein Abonnement verfügt, das Office 365 erweiterte Nachrichtenverschlüsselung nicht enthält, können Sie die Microsoft 365 E5-Compliance oder die Office 365 Advanced Compliance-SKU als Add-on erwerben.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)

S/MIME allows you to help protect sensitive information by sending signed and encrypted email within your organization. Administrators can use remote Windows PowerShell to set up S/MIME after establishing and issuing PKI certificates to users. These certificates must be synchronized from an on-premises Active Directory Certificate Service.
  
S/MIME wird in Microsoft Edge und Internet Explorer 11 unterstützt. Derzeit wird S/MIME von Firefox, Opera und Chrome nicht unterstützt. Weitere Informationen finden Sie unter [S/MIME zum Signieren und Verschlüsseln von Nachrichten](https://docs.microsoft.com/Exchange/policy-and-compliance/smime?view=exchserver-2019).
  
## <a name="in-place-hold-and-litigation-hold"></a>Compliance-Archiv und Aufbewahrung für eventuelle Rechtsstreitigkeiten

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
  
Weitere Informationen finden Sie unter [Compliance-Archiv](https://docs.microsoft.com/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>Compliance-eDiscovery

Exchange Online können Kunden den Inhalt von Postfächern in einer Organisation mithilfe einer webbasierten Schnittstelle durchsuchen. Administratoren oder Verantwortliche für Richtlinientreue und Sicherheit, die autorisiert sind, eine Compliance-eDiscovery-Suche auszuführen (durch Zuweisen), können E-Mails, Anlagen, Kalendertermine, Aufgaben und Kontakte sowie andere Elemente durchsuchen. Mit der Compliance-eDiscovery-Funktion können primäre Postfächer und Archive gleichzeitig durchsucht werden. Die umfangreichen Filterfunktionen umfassen Absender, Empfänger, Nachrichtentyp, Sende-/Empfangsdatum und Cc/Bcc sowie die Verwendung der KQL-Syntax. Die Suchergebnisse beinhalten auch Elemente aus dem Ordner "Gelöschte Elemente", wenn sie mit der Suchabfrage übereinstimmen.
  
Results of In-Place eDiscovery searches can be previewed in the web-based interface, exported to a PST file or copied to a special type of mailbox called a Discovery mailbox. A Discovery mailbox has a 50 GB quota for storing search results. Administrators can also connect Outlook to the Discovery mailbox to access search results, and export the search results to a .pst file.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform multi-mailbox searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox.
  
By default, one Discovery mailbox is created for each organization, but administrators can create additional Discovery mailboxes using remote Windows PowerShell. Discovery mailboxes cannot be used for any purpose other than storing In-Place eDiscovery search results.
  
Administrators use either the Exchange admin center or remote Windows PowerShell to perform In-Place eDiscovery searches. The Exchange admin center can provide a read-only preview of the search results, enabling administrators to quickly verify a search and rerun it, if needed, with different parameters. Once a search is optimized, the administrator can copy the results to the Discovery mailbox or export search results to a PST file.
  
Administratoren können entweder das Exchange Admin Center oder die Remote-Windows PowerShell verwenden, um gleichzeitig bis zu 10.000 Postfächer in einer Compliance-eDiscovery-Suche zu suchen. 
  
In Exchange Online können autorisierte Benutzer Compliance-eDiscovery-Suchen durchführen und eine der folgenden Aktionen auswählen:
  
- **Suchergebnisse schätzen** Rufen Sie eine Schätzung der Anzahl von Nachrichten ab, die von der Suche zurückgegeben werden - einschließlich einer Schlüsselwortstatistik zur Ermittlung der Effektivität von Schlüsselwörtern für die Suche und zur Optimierung der Suchparameter, falls erforderlich. 
    
- **Vorschau auf Suchergebnisse anzeigen**
    
- Kopiert Nachrichten, die in Suchergebnissen zurückgegeben werden, in ein Discoverypostfach.
    
Weitere Informationen finden Sie unter [Compliance-eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Nachrichtenflussregeln

You can use mail flow rules to look for specific conditions on messages that pass through your organization and act on them. Mail flow rules let you apply messaging policies to email messages, secure messages, protect messaging systems, and prevent information leakage.
  
Many organizations today are required by law, regulatory requirements, or company policies to apply messaging policies that limit the interaction between recipients and senders, both inside and outside the organization. In addition to limiting interactions among individuals, departmental groups inside the organization, and entities outside the organization, some organizations are also subject to the following messaging policy requirements:
  
- Verhindern, dass unangemessene Inhalte in die Organisation gelangen oder diese verlassen
    
- Filtern von vertraulichen Organisationsinformationen
    
- Nachverfolgen oder Kopieren von Nachrichten, die von bestimmten Einzelpersonen gesendet oder empfangen werden
    
- Umleiten von eingehenden und ausgehenden Nachrichten für die Untersuchung vor der Zustellung
    
- Hinzufügen von Haftungsausschlüssen zu Nachrichten während des Transports innerhalb der Organisation
    
> [!IMPORTANT]
> Attachment file types that require installation of third-party iFilters on the email server (such as Adobe .pdf) cannot be inspected using mail flow rules until after an appropriate iFilter is installed. For more information about file types that are supported by mail flow rules, see [Use mail flow rules to inspect message attachments in Office 365](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
Weitere Informationen zu Nachrichtenflussregeln finden Sie unter [Nachrichtenflussregeln in Exchange 2016](https://docs.microsoft.com/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Verhinderung von Datenverlust

Das Feature zur Verhinderung von Datenverlust (Data Loss Prevention, DLP) hilft Ihnen dabei, vertrauliche Informationen in Ihrer Organisation über eine eingehende Inhaltsanalyse zu identifizieren, zu überwachen und zu schützen. DLP ist ein Premium-Feature, dessen Bedeutung für Nachrichtensysteme von Unternehmen ständig zunimmt, da geschäftskritische E-Mails vertrauliche Daten enthalten, die geschützt werden müssen. Mit der DLP-Funktion in Exchange Online können Sie vertrauliche Daten schützen, ohne die Produktivität der Mitarbeiter zu beeinträchtigen.
  
Sie können DLP-Richtlinien in der Verwaltungsschnittstelle der Exchange-Verwaltungskonsole konfigurieren, die Ihnen Folgendes ermöglicht: 
  
- Beginnen Sie mit einer vorkonfigurierten Richtlinienvorlage, mit deren Hilfe Sie bestimmte Typen vertraulicher Informationen wie PCI DSS-Daten (Payment Card Industry Data Security Standard), Gramm-Leach-Bliley Act-Daten oder sogar standortspezifisch personenbezogene Informationen (PII) erkennen können.
    
- Nutzen Sie die volle Leistungsfähigkeit vorhandener Transportregelkriterien und -aktionen, und fügen Sie neue Transportregeln hinzu.
    
- Testen Sie die Effektivität Ihrer DLP-Richtlinien vor deren vollständiger Erzwingung.
    
- Integrieren Sie eigene benutzerdefinierte DLP-Richtlinienvorlagen und Typen vertraulicher Informationen.
    
- Erkennen Sie vertrauliche Informationen in E-Mail-Anlagen, -Text oder -Betreffzeilen, und passen Sie die Vertrauensstufe an, bei der Exchange Online Maßnahmen ergreift.
    
- Detect sensitive form data by using Document Fingerprinting. Document Fingerprinting helps you easily create custom sensitive information types based on text-based forms that you can use to define transport rules and DLP policies.
    
- Fügen Sie Richtlinien Tipps hinzu, die zur Verringerung von Datenverlusten beitragen können, indem Sie einen Hinweis zu Outlook 2016, Outlook 2013, Outlook im Internet und OWA für mobile Geräte Benutzern anzeigen und die Effektivität Ihrer Richtlinien verbessern, indem Sie eine falsch positive Berichterstellung zulassen. 
    
- Überprüfen Sie Vorfallsdaten in DLP-Berichten, oder fügen Sie Ihre eigene Berichterstellung mithilfe einer neuen Aktion zum Generieren eines Schadensberichts hinzu.
    
Weitere Informationen zu DLP finden Sie unter [Verhinderung von Datenverlust](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Journaling

You can configure Exchange Online to journal copies of emails to any external mailbox that can receive messages via SMTP. Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications. When planning for messaging retention and compliance, it's important to understand journaling and how it fits in with your organization's compliance policies.
  
You can manage journal rules by using the Exchange admin center or remote Windows PowerShell. You can configure journaling on a per-user and per-distribution list basis, and choose to journal only internal messages, only external messages, or both. Journaled messages include not only the original message but also information about the sender, recipients, copies, and blind copies.
  
Wenn Sie eine erfolgreiche und zuverlässige Journalinglösung sicherstellen möchten, müssen Sie die folgenden Aufgaben ausführen:
  
- Stellen Sie sicher, dass das Journalingziel kein Exchange Online-Postfach ist.
    
- Erstellen Sie in einem Kundenverzeichnis ein Kontaktobjekt für die SMTP-Ziel-E-Mail-Adresse, die für das Journaling verwendet wird.
    
- Erstellen Sie ein zweites Kontaktobjekt als alternatives Journalpostfach, in dem sämtliche Journalberichte erfasst werden, wenn das primäre Journalpostfach nicht verfügbar ist.
    
- Sorgen Sie für die Aufrechterhaltung der richtigen Verwaltungs-, Redundanz-, Verfügbarkeits- und Leistungsebenen des SMTP-Ziels, um die erfolgreiche E-Mail-Akzeptanz immer sicherzustellen.
    
- Stellen Sie die entsprechende Interoperabilität mit Exchange-Server und Exchange-Transport bereit, einschließlich Nachrichtenformate, der Integration von Absender-/Empfängerinformationen und angemessener Inhaltskonvertierung.
    
Weitere Informationen zum Journaling finden Sie unter [Journaling](https://docs.microsoft.com/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  

