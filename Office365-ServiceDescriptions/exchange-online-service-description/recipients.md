---
title: Empfänger
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: In diesem Thema werden die empfängerbezogenen Features von Microsoft Exchange Online beschrieben. Dazu gehören E-Mail, Kontakte, Verteilergruppen sowie Kalender- und Terminplanungsfunktionen.
ms.openlocfilehash: a2d1f37bf4f86399522573d18177f6c397fd761c
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132639"
---
# <a name="recipients"></a>Empfänger

This topic describes recipient-related features included with Microsoft Exchange Online. This includes email, contacts, distribution groups, and calendar and scheduling capabilities.
  
## <a name="email"></a>E-Mails

Every Microsoft Exchange Online subscriber receives a mailbox, and specialty mailboxes are available for scheduling facilities resources (such as conference rooms) and for multiuser access to shared email addresses. Maximum storage limits apply to most mailboxes, and administrators can control allowable mailbox sizes. Automated notifications and restrictions can alert users when their mailboxes are nearing, or at, capacity. Exchange Online also has several types of message limitations—message size, message rate, and recipient list limits. Details of all these features and limits are provided below.
  
> [!NOTE]
> Catch-All-Adressen werden in Exchange Online nicht mehr unterstützt. Da die Empfängerfilterung vor potenziellen Spamnachrichten geschützt ist, werden e-Mail-Adressen, die nicht in Ihrer Organisation vorhanden sind, abgelehnt. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Mailbox-Typen, Speicherbegrenzungen und Kapazitätswarnungen

The amount of mailbox storage available to a user and the default mailbox size are determined by the mailbox type and the user's subscription license. Administrators can reduce maximum mailbox sizes per user or globally. Exchange Online also provides notifications when a user's mailbox is nearing, or at, capacity.
  
Weitere Informationen finden Sie in den Abschnitten "Speichergrenzwerte für Postfächer" und "Kapazitäts Warnungen" im Thema [Exchange Online Limits](exchange-online-limits.md).
  
### <a name="mailtips"></a>MailTips

MailTips are automated, informative messages that appear above the To: line while users are composing or addressing a message. They are designed to help prevent accidental delivery, policy violations, or unnecessary non-delivery reports (NDRs). For example, MailTips can generate an alert if senders try to send messages to overly large groups, to groups that contain external recipients, or to a distribution group that is moderated or restricted. For more information, see [MailTips](https://go.microsoft.com/fwlink/p/?LinkId=401472).
  
### <a name="delegate-access"></a>Stellvertretungszugriff

Exchange Online unterstützt Stellvertretungszugriff – die Möglichkeit für Benutzer, anderen Benutzern das Verwalten von e-Mails und Kalendern zu ermöglichen. Stellvertretungszugriff wird häufig zwischen einem Manager und einem Assistenten verwendet, wobei der Assistent die eingehenden e-Mail-Nachrichten des Managers verarbeitet und den Zeitplan des Vorgesetzten koordiniert. Stellvertretungszugriff kann durch Exchange Online von Benutzern in Outlook oder Outlook im Internet oder von Administratoren im Exchange Admin Center aktiviert werden. 
  
Stellvertreter können zwei Arten von Zugriff haben:
  
- **Berechtigung "Senden im Auftrag von"** Der Stellvertreter kann E-Mail-Nachrichten verfassen und den Namen der anderen Person in das Feld "Von" eingeben, wo er als "[Name des Stellvertreters] im Auftrag von [Name der Person]" angezeigt wird. 
    
- **Send As permissions** The delegate can send messages from the other person's mailbox as if the delegate were the mailbox owner. This scenario is common where there is a shared mailbox and several employees send email messages from that shared mailbox instead of from their Exchange Online accounts. 
    
Weitere Informationen zu Zugriffsrechten finden Sie unter [Verwalten von Berechtigungen für Empfänger](https://technet.microsoft.com/library/jj919240%28v=exchg.160%29.aspx).
  
### <a name="inbox-rules"></a>Posteingangsregeln

Exchange Online ermöglicht es Benutzern, Posteingangsregeln zu erstellen, die automatisch spezifische, kriteriumsbasierte Aktionen beim Eingang von Nachrichten ausführen. Sie können beispielsweise eine Regel erstellen, um automatisch alle E-Mails in einen bestimmten Ordner zu verschieben, wenn die Mail an eine bestimmte Verteilergruppe gesendet wurde. Benutzer verwalten Posteingangsregeln in Outlook oder Outlook im Internet. Administratoren können bestimmte Typen von Posteingangsregeln blockieren, indem sie die serverseitige Weiterleitung und/oder serverseitige automatische Antworten deaktivieren. Wenn beispielsweise die serverseitige E-Mail-Weiterleitung deaktiviert ist, kann dies die Benutzer daran hindern, automatisch E-Mails an persönliche Konten weiterzuleiten. Gleichermaßen gilt, dass, wenn die serverseitigen automatischen Antworten deaktiviert sind, dies verhindern kann, dass außenstehende Parteien diese Antworten dazu nutzen, um gültige E-Mail-Adresse zu identifizieren. Diese Änderungen werden über die remote Windows PowerShell vorgenommen.
  
### <a name="clutter"></a>Unwichtige Elemente

Clutter is designed to help you focus on the most important messages in your inbox. It uses machine learning to de-clutter your inbox by moving lower priority messages out of your way and into a new Clutter folder. Clutter respects your existing email rules, so if you have created rules to organize your email those rules continue to be applied and Clutter won't act on those messages. Clutter is disabled by default for your inbox. To learn more, see [De-clutter your inbox in Office 365](https://www.microsoft.com/en-us/microsoft-365/blog/2014/11/11/de-clutter-inbox-office-365/).
  
### <a name="connected-accounts"></a>Verbundene Konten

Mit dem Feature verbundene Konten können Exchange Online Benutzer externe e-Mail-Konten (beispielsweise persönliche Konten) mit ihren internen e-Mail-Konten in Exchange Online verbinden und dann Outlook im Internet verwenden, um mit allen ihren Nachrichten an einer Stelle zu interagieren. Verbundene Konten werden bei der Anmeldung bei Outlook im Internet automatisch synchronisiert; Benutzer können die Konten auch manuell aus Outlook im Internet synchronisieren. Administratoren können dieses Feature für bestimmte Benutzer oder alle Benutzer über das [Exchange Admin Center](https://go.microsoft.com/fwlink/?LinkID=785297&amp;clcid=0x409)aktivieren und deaktivieren.
  
### <a name="inactive-mailboxes"></a>Inaktive Postfächer

Exchange Online provides the capability to preserve the contents of deleted mailboxes indefinitely. This feature is called inactive mailboxes. A mailbox becomes inactive when an In-Place Hold or a Litigation Hold is placed on the mailbox before it's deleted. This results in the contents of the mailbox being preserved indefinitely. Administrators, compliance officers, or record managers can use the In-Place eDiscovery feature in Exchange Online to access the contents of an inactive mailbox.
  
Damit ein inaktives Postfach aktiviert werden kann, muss dem Postfach eine Exchange Online-Lizenz (Plan 2) zugewiesen werden, oder es muss ein Abonnement für die Exchange Online-Archivierung vorhanden sein, sodass das Postfach in einem Compliance-Archiv platziert oder ein Beweissicherungsverfahren für das Postfach aktiviert werden kann, bevor es gelöscht wird.
  
> [!IMPORTANT]
> If a hold isn't placed on a mailbox before it's deleted, the contents of the mailbox will not be preserved or discoverable. The mailbox can be recovered within 30 days of deletion, but the mailbox and its contents will be permanently deleted after 30 days if it isn't recovered. 
  
Weitere Informationen finden Sie unter:
  
- [Verwalten inaktiver Postfächer in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286991)
    
- [In-Situ-Speicher und Beweissicherungsverfahren](https://go.microsoft.com/fwlink/p/?LinkId=271746)
    
- [Compliance-eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=271747)
    
## <a name="contacts-and-distribution-groups"></a>Kontakte und Verteilergruppen

### <a name="offline-address-book"></a>Offlineadressbuch

Das Offlineadressbuch-Feature stellt eine Momentaufnahme der Active Directory Informationen bereit, die in der globalen Outlook-Adressliste (GAL) verfügbar sind. Sie werden lokal in Outlook zwischengespeichert, um sie bei der Offlinearbeit verfügbar zu machen.
  
### <a name="address-book-policies"></a>Adressbuchrichtlinien

Exchange Online unterstützt adressbuchrichtlinien. Adressbuchrichtlinien ermöglichen Ihnen die Einteilung von Benutzern in bestimmte Gruppen, um benutzerdefinierte Ansichten der globalen Adressliste Ihrer Organisation bereitzustellen. Bei der Erstellung einer ABP weisen Sie der Richtlinie eine globale Adressliste (GAL), ein Offlineadressbuch (OAB), eine Raumliste und eine oder mehrere Adresslisten zu. Anschließend können Sie die adressbuchrichtlinie Postfachbenutzern zuweisen und Ihnen Zugriff auf eine benutzerdefinierte GAL in Outlook und Outlook im Internet gewähren. Administratoren können über Windows PowerShell-Remotesitzungen Adressbuchrichtlinien konfigurieren. Weitere Informationen zu Adressbuchrichtlinien finden Sie unter [Adressbücher in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=394203).
  
### <a name="address-lists"></a>Adresslisten

Exchange Online unterstützt die Anpassung von Adresslisten und GALs. Eine GAL ist ein organisationsweites Verzeichnis aller e-Mail-aktivierten Benutzer, Verteilergruppen und externen Kontakte. Administratoren können Benutzer, Verteilergruppen und Kontakte aus der globalen Adressliste ausblenden, indem Sie das Verzeichnissynchronisierungstool oder Remote Windows PowerShell verwenden.
  
### <a name="hierarchical-address-books"></a>Hierarchische Adressbücher

 Hierarchical address books allow end users to browse for recipients in their Exchange organization using an organizational hierarchy. Administrators can customize the address book by seniority and rank rather than alphabetical listings. 
  
### <a name="distribution-groups-global"></a>Verteilergruppen (global)

Eine Verteilergruppe (oder Verteilerliste) ist eine Sammlung von Benutzern, Kontakten und anderen Verteilergruppen, die allen Benutzern in einem Unternehmen zur Verfügung steht. Benutzer richten eine E-Mail an ein Verteilergruppen-Alias, um Nachrichten an alle Personen in der Gruppe zu senden. Verteilergruppen ähneln persönlichen Verteilergruppen, die einzelne Benutzer in Outlook erstellen, allerdings sind ihre Mitgliederlisten global für das Unternehmen verfügbar. Administratoren erstellen Verteilergruppen in der Exchange-Verwaltungskonsole. Die Gruppen können auch aus dem lokalen Active Directory mit Exchange Online synchronisiert werden. Sie werden in der GAL in Outlook angezeigt. Exchange Online unterstützt erweiterte Verteilergruppenfunktionen, darunter auch die nachfolgend beschriebenen:
  
- **Restricted distribution groups** By default, anyone can send emails to any distribution group. Administrators can change permissions to allow only specific individuals to send emails to a particular group—for example, to discourage inappropriate use of large distribution lists. Administrators can also block external sources from sending email to distribution groups to help prevent spam. For distribution groups that are synchronized from on-premises Active Directory using the Directory Synchronization tool, the attributes for restriction are synchronized to the cloud automatically. For more information, see [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Dynamic distribution groups** The membership list for a dynamic distribution group (also known as a dynamic distribution list, or query-based distribution list) is calculated every time a message is sent to the group. This calculation is based on filters and conditions that the administrator defines. They are managed in Exchange Online through remote Windows PowerShell. For more information about dynamic distribution groups, see [Manage Dynamic Distribution Groups](https://technet.microsoft.com/library/bb123722%28v=exchg.160%29.aspx).
    
    > [!IMPORTANT]
    > The Office 365 Directory Synchronization tool ignores dynamic distribution groups in on-premises Active Directory, and does not synchronize these to Exchange Online. Organizations that use the Directory Synchronization tool should use a naming convention that avoids conflicts between the regular distribution groups that are managed on-premises and the dynamic distribution groups that are managed in Exchange Online. 
  
- **Moderated distribution groups** Administrators can select a moderator to regulate the flow of messages to a distribution group. With moderated distribution groups, anyone can email the distribution group alias, but before the message is delivered to the members of the group, a moderator must review and approve it. For more information about moderation, see the Message Approval section in [Manage Distribution Groups](https://technet.microsoft.com/library/mt577270%28v=exchg.160%29.aspx).
    
- **Self-Service distribution groups** Administrators can give users the ability to manage their own distribution group membership from a web-based interface. Users can be given permissions to create, delete, join, or leave distribution groups. These capabilities are enabled by default for all Exchange Online users. Administrators can disable them so that only the IT department can manage distribution groups, if desired. They can also create naming policies to standardize and manage the names of distribution groups that their users create. For example, they can add a specific prefix or suffix to the distribution group name when it is created, or block specific words from being used in the group's name. 
    
    > [!IMPORTANT]
    > Self-service capabilities are not available for distribution groups that are synchronized from on-premises Active Directory to Exchange Online. Organizations that use Directory Synchronization should use a naming convention that avoids conflicts between distribution groups that are managed on-premises and distribution groups that are managed in the cloud. 
  
### <a name="external-contacts-global"></a>Externe Kontakte (global)

Ein externer Kontakt ist ein Datensatz mit Informationen zu einer Person, die außerhalb einer bestimmten Organisation arbeitet. Externe Kontakte ähneln persönlichen Kontakten, die einzelne Benutzer in Outlook erstellen, allerdings sind sie global für das Unternehmen verfügbar. Administratoren können externe Kontakte mit der Exchange-Verwaltungskonsole oder über Windows PowerShell-Remotesitzungen erstellen. Diese Kontakte können auch aus dem lokalen Active Directory mit Exchange Online synchronisiert werden. Sie werden in der GAL in Outlook angezeigt.
  
Weitere Informationen zu externen Kontakten finden Sie unter [Erstellen einer Organisationsbeziehung in Exchange Online](https://technet.microsoft.com/library/jj916671%28v=exchg.150%29.aspx).
  
## <a name="calendar-and-scheduling"></a>Kalender und Terminplanung

### <a name="resource-mailboxes"></a>Ressourcenpostfächer

Ressourcenpostfächer (beispielsweise für Konferenzräume und physische Geräte) stellen die Besprechungsräume eines Unternehmens oder andere Einrichtungen oder Ressourcen dar. Benutzer können Räume oder Ressourcen reservieren, indem Sie den e-Mail-Alias der Ressource zu Besprechungsanfragen in Outlook oder Outlook im Internet hinzufügen. Konferenzräume und Ressourcen werden in der globalen Adressliste in Outlook und Outlook im Internet angezeigt.
  
Administrators create resource mailboxes using the Exchange admin center or remote Windows PowerShell. The mailboxes can also be synchronized with Exchange Online from on-premises Active Directory.
  
Weitere Informationen zu Ressourcenpostfächern finden Sie unter:
  
- [Erstellen und Verwalten von Raumpostfächern](https://go.microsoft.com/fwlink/?LinkId=717533&amp;clcid=0x409)
    
- [Verwalten von Gerätepostfächern](https://go.microsoft.com/fwlink/?LinkId=717534)
    
### <a name="conference-room-management"></a>Konferenzraumverwaltung

Exchange Online includes the Resource Booking Attendant (RBA), which automates scheduling of conference rooms and other resources. A resource mailbox that is RBA-configured accepts, declines, or acknowledges meeting requests from a meeting organizer based on the resource's calendar availability. 
  
Administratoren können automatisierte Konferenzraum Antworten anpassen und Buchungsrichtlinien in Outlook im Internet konfigurieren. Diese Richtlinien beinhalten, wer die Ressource planen kann, wann sie eingeplant werden kann, welche Besprechungsinformationen im Kalender der Ressource angezeigt werden sowie den Prozentsatz der zulässigen Planungskonflikte. Administratoren können die Ressourcenbuchungsautomatik deaktivieren und bestimmte Benutzer zuweisen, um die Besprechungsanfragen für Konferenzräume manuell zu verwalten.
  
Administratoren müssen die RBA-Einstellungen über die remote Windows-PowerShell definieren und verwalten.
  
### <a name="out-of-office-replies"></a>Abwesenheitsantworten

Out-of-office messages are automatic replies to incoming messages that Exchange Online sends on behalf of a user. Users can schedule out-of-office messages in advance, with specific start and end times, and can configure separate out-of-office messages for internal and external recipients. They can also set out-of-office messages from mobile devices that support this Exchange ActiveSync feature. Junk-email and mailing-list awareness within Exchange Online prevents users from sending external out-of-office messages to extended mailing lists and potential spammers. Administrators can also prevent users from sending out-of-office messages to external users using remote Windows PowerShell.
  
### <a name="calendar-sharing"></a>Kalenderfreigabe

Benutzer können ihre persönlichen Kalender auf zwei Arten freigeben:
  
- **Verbundfreigabe für Kalender** Verbund bezieht sich auf die zugrunde liegende Vertrauensstellungsinfrastruktur, die die Verbundfreigabe unterstützt, eine einfache Methode für Exchange-Benutzer, die Frei/Gebucht-Daten im Kalender und Kontaktinformationen für Empfänger in anderen externen Verbundorganisationen freigeben möchten. Dazu gehören Exchange Online-Organisationen oder Organisationen, die Exchange Server 2010 oder Exchange Server 2013 lokal ausführen. Exchange Online Administratoren müssen keine Vertrauensstellung mit dem Microsoft Federation Gateway einrichten, da diese Vertrauensstellung für alle Exchange Online-Kunden vorkonfiguriert ist, wenn der Microsoft-Dienst erstellt wird. Eine Standardfreigaberichtlinie ermöglicht Benutzern das Senden von Einladungen zur Kalenderfreigabe aus Outlook im Internet oder Outlook 2010. Administratoren verwenden die remote Windows PowerShell, um diese Richtlinie zu deaktivieren oder um den Umfang an Frei/Gebucht-Daten im Kalender zu konfigurieren, die Benutzer freigeben können. Administratoren können auch eine Beziehung von einer Organisation zu einer anderen mit einer anderen Verbundorganisation erstellen, sodass der gewünschte Umfang an Frei/Gebucht-Informationen für alle Benutzer organisationsübergreifend sichtbar ist, ohne dass einzelne Benutzer eine Freigabeeinladung senden müssen. Innerhalb der vom Administrator definierten Freigaberichtlinien und/oder Organisation-zu-Organisation-Beziehungen können Benutzer den Umfang ihrer Freigabe weiter gezielt einschränken. 
    
- **Kalenderfreigabe im Internet** Exchange Online ermöglicht es den Benutzern, ihre Kalender im iCal-Format für einen anonymen Zugriff von Benutzern innerhalb oder außerhalb der Organisation zu veröffentlichen. Empfänger können Exchange, eine andere Plattform oder einfach einen Webbrowser verwenden. Exchange Online Benutzer können auch Kalender abonnieren, die andere über iCal an Internetstandorten veröffentlicht haben. Diese Freigabe von persönlichen Kalendern unterscheidet sich von der Verbundfreigabe für Kalender, die von einem Administrator eingerichtet wird und die die Freigabe von Frei/Gebucht-Informationen zwischen Organisationen ermöglicht. Kein Benutzer kann Kalenderdaten im iCal-Format veröffentlichen, bis der Administrator eine Freigaberichtlinie festgelegt und angewendet hat, die dies zulässt. Administratoren können die iCal-Veröffentlichung und iCal-Abonnements für Benutzer in einer Organisation mit der remoten Windows PowerShell deaktivieren.
    
Weitere Informationen zur Verbundfreigabe finden Sie unter [Freigabe in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010-Raumsuche

Exchange Online supports the Room Finder feature of Outlook 2010, which arranges rooms into lists (for example, a list called "Building 5 rooms") to make it easier to find a nearby room when scheduling a meeting. To appear in the room list, a distribution group must be specially marked using one of two methods: 
  
- Eine neue Raumliste kann mithilfe der remoten Windows PowerShell erstellt werden. 
    
- Jede Verteilergruppe, die nur Räume enthält, kann über die remote Windows PowerShell in eine Raumliste konvertiert werden.
    
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  