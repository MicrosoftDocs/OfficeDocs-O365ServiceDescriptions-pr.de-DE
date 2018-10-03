---
title: Kompatibilitäts- und Sicherheitsfeatures der Exchange Online-Archivierung
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: c54ec8f37c6f881dc934307f7784f79d01c7a878
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035766"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a><span data-ttu-id="d8bd6-102">Kompatibilitäts- und Sicherheitsfeatures der Exchange Online-Archivierung</span><span class="sxs-lookup"><span data-stu-id="d8bd6-102">Compliance and Security Features in Exchange Online Archiving</span></span>

## <a name="compliance-features-in-exchange-online-archiving"></a><span data-ttu-id="d8bd6-103">Kompatibilitätsfunktionen der Exchange Online-Archivierung</span><span class="sxs-lookup"><span data-stu-id="d8bd6-103">Compliance features in Exchange Online Archiving</span></span>

<span data-ttu-id="d8bd6-104">Im folgenden Abschnitt werden die Kompatibilitätsfunktionen von Microsoft Exchange Online-Archivierung beschrieben.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-104">The following sections describe the compliance features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="retention-policies"></a><span data-ttu-id="d8bd6-105">Aufbewahrungsrichtlinien</span><span class="sxs-lookup"><span data-stu-id="d8bd6-105">Retention policies</span></span>
<span data-ttu-id="d8bd6-106"><a name="BKMK_Retentionpolicies"> </a></span><span class="sxs-lookup"><span data-stu-id="d8bd6-106"></span></span>

<span data-ttu-id="d8bd6-p101">Exchange Online-Archivierung bietet Aufbewahrungsrichtlinien, die Organisationen dabei helfen, ihre Verpflichtungen hinsichtlich E-Mails und anderen Kommunikationsformen zu reduzieren. Mithilfe dieser Richtlinien haben Administratoren die Möglichkeit, Aufbewahrungseinstellungen für bestimmte Ordner des Posteingangs eines Benutzers anzuwenden. Administratoren können Benutzern auch ein Menü zu Aufbewahrungsrichtlinien zur Verfügung stellen, über das diese in Outlook 2010 oder Outlook Web App Richtlinien für bestimmte Elemente, Unterhaltungen oder Ordner aktivieren können. In Exchange Online-Archivierung verwalten Administratoren Aufbewahrungsrichtlinien aus der lokalen Infrastruktur.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p101">Exchange Online Archiving offers retention policies to help organizations reduce the liabilities associated with email and other communications. With these policies, administrators can apply retention settings to specific folders in users' inboxes. Administrators can also give users a menu of retention policies and let them apply the policies to specific items, conversations, or folders using Outlook 2010 or later or Outlook Web App. In Exchange Online Archiving, administrators manage retention policies from the on-premises infrastructure.</span></span>
  
<span data-ttu-id="d8bd6-p102">Exchange Online-Archivierung bietet zwei Arten von Richtlinien: archivieren und löschen. Beide Typen können auf das gleiche Element oder den gleichen Ordner angewendet werden. Ein Benutzer kann beispielsweise eine E-Mail so markieren, dass sie nach einer bestimmten Anzahl von Tagen automatisch in das persönliche Archiv verschoben oder nach einer anderen festgelegten Anzahl von Tagen gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p102">Exchange Online Archiving offers two types of policies: archive and delete. Both types can be applied to the same item or folder. For example, a user can tag an email message so that it is automatically moved to the personal archive in a specified number of days and deleted after another span of days.</span></span>
  
<span data-ttu-id="d8bd6-p103">In Outlook 2010 und höher und Outlook Web App können Benutzer Aufbewahrungsrichtlinien auf Ordner, Unterhaltungen oder einzelne Nachrichten anwenden und außerdem die geltenden Aufbewahrungsrichtlinien und vorgesehenen Löschtermine von Nachrichten anzeigen. Benutzer von anderen E-Mail-Clients können E-Mails basierend auf vom Administrator bereitgestellten Aufbewahrungsrichtlinien löschen oder archivieren lassen, verfügen aber nicht über das gleiche Maß an Transparenz und Steuerung.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p103">With Outlook 2010 and later and Outlook Web App, users can apply retention policies to folders, conversations, or individual messages and can also view the applied retention policies and expected deletion dates on messages. Users of other email clients can have email deleted or archived based on server-side retention policies provisioned by the administrator, but they do not have the same level of visibility and control.</span></span>
  
<span data-ttu-id="d8bd6-p104">Die Aufbewahrungsrichtlinienfunktionen in Exchange Online-Archivierung entsprechen denen von Exchange Server 2010 Service Pack 2 (SP2) und höher. Administratoren können Aufbewahrungsrichtlinien aus lokalen Exchange Server 2010-Umgebungen (und höher) verwalten. Verwaltete Ordner, ein älterer Ansatz zur Verwaltung von Nachrichtendatensätzen, der in Exchange 2007 eingeführt wurde, stehen bei der Exchange Online-Archivierung nicht zur Verfügung und sind mit dieser nicht kompatibel. Weitere Informationen finden Sie unter [Aufbewahrungstags und Aufbewahrungsrichtlinien](https://go.microsoft.com/fwlink/p/?LinkID=314153).</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p104">The retention policy capabilities offered in Exchange Online Archiving are the same as those offered in Exchange Server 2010 Service Pack 2 (SP2) and later. Administrators can manage retention policies from on-premises Exchange Server 2010 and later environments. Managed Folders, an older approach to messaging records management that was introduced in Exchange 2007, are not available in and not compatible with Exchange Online Archiving. For more details, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkID=314153).</span></span>
  
### <a name="in-place-hold-and-litigation-hold"></a><span data-ttu-id="d8bd6-120">In-Situ-Speicher und Beweissicherungsverfahren</span><span class="sxs-lookup"><span data-stu-id="d8bd6-120">In-Place Hold and Litigation Hold</span></span>
<span data-ttu-id="d8bd6-121"><a name="BKMK_In_placehold"> </a></span><span class="sxs-lookup"><span data-stu-id="d8bd6-121"></span></span>

<span data-ttu-id="d8bd6-p105">Wenn Rechtsstreitigkeiten zu erwarten sind, sind Organisationen dazu verpflichtet, die für den Fall relevanten elektronisch gespeicherten Informationen einschließlich E-Mail aufzubewahren. Diese Erwartung kann eintreten, bevor die Details des Falls bekannt werden, und die Menge der aufzubewahrenden Daten ist häufig groß. Organisationen können alle E-Mails zu einem bestimmten Thema oder alle E-Mails für bestimmte Personen aufbewahren.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p105">When a reasonable expectation of litigation exists, organizations are required to preserve electronically stored information (ESI), including email that's relevant to the case. This expectation can occur before the specifics of the case are known, and preservation is often broad. Organizations may preserve all email related to a specific topic, or all email for certain individuals.</span></span>
  
> [!NOTE]
> <span data-ttu-id="d8bd6-125">Compliance-Archiv und Beweissicherungsverfahren gelten nicht für E-Mails, die mithilfe von POP- oder IMAP-Clients oder von benutzerdefinierten Anwendungen gesendet werden, die das SMTP-Protokoll verwenden.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-125">In-place hold and litigation hold currently do not apply to emails sent using POP or IMAP clients, or by custom applications that use the SMTP protocol.</span></span> 
  
<span data-ttu-id="d8bd6-126">In Exchange Online können Sie das Compliance-Archiv oder die Aufbewahrung für eventuelle Rechtsstreitigkeiten verwenden, um folgende Ziele zu erreichen:</span><span class="sxs-lookup"><span data-stu-id="d8bd6-126">In Exchange Online, you can use In-Place Hold or Litigation Hold to accomplish the following goals:</span></span>
  
- <span data-ttu-id="d8bd6-127">Platzieren von Benutzerpostfächern in Archiven und Beibehalten von Postfachelementen in unveränderbarer Form</span><span class="sxs-lookup"><span data-stu-id="d8bd6-127">Enable users to be placed on hold and preserve mailbox items immutably</span></span>
    
- <span data-ttu-id="d8bd6-128">Beibehalten von Postfachelementen, die von Benutzern oder automatischen Löschprozessen wie z. B. MRM gelöscht werden</span><span class="sxs-lookup"><span data-stu-id="d8bd6-128">Preserve mailbox items deleted by users or automatic deletion processes such as MRM</span></span>
    
- <span data-ttu-id="d8bd6-129">Schützen von Postfachelementen vor Manipulation, Änderungen durch einen Benutzer oder automatische Prozesse, indem eine Kopie des ursprünglichen Elements gespeichert wird</span><span class="sxs-lookup"><span data-stu-id="d8bd6-129">Protect mailbox items from tampering, changes by a user, or automatic processes by saving a copy of the original item</span></span>
    
- <span data-ttu-id="d8bd6-130">Beibehalten von Elementen auf unbestimmte Zeit oder über einen bestimmten Zeitraum</span><span class="sxs-lookup"><span data-stu-id="d8bd6-130">Preserve items indefinitely or for a specific duration</span></span>
    
- <span data-ttu-id="d8bd6-131">Das Halten für den Benutzer transparent halten, ohne MRM anhalten zu müssen</span><span class="sxs-lookup"><span data-stu-id="d8bd6-131">Keep holds transparent from the user by not having to suspend MRM</span></span>
    
- <span data-ttu-id="d8bd6-132">Verwenden von Compliance-eDiscovery, um Postfachelemente, einschließlich Elementen in einem Compliance-Archiv, zu durchsuchen</span><span class="sxs-lookup"><span data-stu-id="d8bd6-132">Use In-Place eDiscovery to search mailbox items, including items placed on hold</span></span>
    
<span data-ttu-id="d8bd6-133">Außerdem können Sie das Compliance-Archiv für Folgendes verwenden:</span><span class="sxs-lookup"><span data-stu-id="d8bd6-133">Additionally, you can use In-Place Hold to:</span></span>
  
- <span data-ttu-id="d8bd6-134">Durchsuchen und Halten von Elementen, die bestimmte Kriterien erfüllen</span><span class="sxs-lookup"><span data-stu-id="d8bd6-134">Search and hold items matching specified criteria</span></span>
    
- <span data-ttu-id="d8bd6-135">Platzieren von Benutzern in mehreren Compliance-Archiven für unterschiedliche Fälle oder Untersuchungen</span><span class="sxs-lookup"><span data-stu-id="d8bd6-135">Place a user on multiple In-Place Holds for different cases or investigations</span></span>
    
> [!NOTE]
> <span data-ttu-id="d8bd6-136">Wenn Sie für ein Postfach den In-Situ-Speicher oder das Beweissicherungsverfahren aktivieren, wird diese Einstellung auf das primäre und das Archivpostfach angewendet.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-136">When you put a mailbox on In-Place Hold or Litigation Hold, the hold is placed on both the primary and the archive mailbox.</span></span> 
  
<span data-ttu-id="d8bd6-137">Weitere Informationen finden Sie unter [Compliance-Archiv](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span><span class="sxs-lookup"><span data-stu-id="d8bd6-137">For more information, see [In-Place Hold and Litigation Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
> [!NOTE]
> <span data-ttu-id="d8bd6-138">Das standardmäßige Kontingent für den Ordner „Wiederherstellbare Elemente" beträgt 100 GB für Exchange Online-Archivierung-Benutzer.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-138">The default quota for the Recoverable Items Folder is 100 GB for Exchange Online Archiving users.</span></span> 
  
### <a name="in-place-ediscovery"></a><span data-ttu-id="d8bd6-139">Compliance-eDiscovery</span><span class="sxs-lookup"><span data-stu-id="d8bd6-139">In-Place eDiscovery</span></span>
<span data-ttu-id="d8bd6-140"><a name="BKMK_In_placehold"> </a></span><span class="sxs-lookup"><span data-stu-id="d8bd6-140"></span></span>

<span data-ttu-id="d8bd6-p106">Exchange Online-Archivierung unterstützt Compliance-eDiscovery für das Durchsuchen von Postfachinhalten in einer Organisation. Unter Verwendung der Exchange-Verwaltungskonsole oder von Remote Windows PowerShell von einem lokalen Exchange 2013-Server können Administratoren oder autorisierte Discovery-Manager verschiedene Postfachelemente durchsuchen, darunter E-Mails, Anhänge, Kalendertermine, Aufgaben und Kontakte. Mit der Compliance-eDiscovery-Funktion können primäre Postfächer und Archive gleichzeitig durchsucht werden. Die umfangreichen Filterfunktionen umfassen Absender, Empfänger, Nachrichtentyp, Sende-/Empfangsdatum und Cc/Bcc sowie die Verwendung der KQL(Keyword Query Language)-Syntax. Weitere Informationen finden Sie unter [Compliance-eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p106">Exchange Online Archiving supports In-Place eDiscovery for searching the contents of mailboxes in an organization. Using the Exchange admin center or remote Windows PowerShell from an on-premises Exchange 2013 server, administrators or authorized Discovery managers can search a variety of mailbox items - including email messages, attachments, calendar appointments, tasks, and contacts. In-Place eDiscovery can search simultaneously across primary mailboxes and archives. Rich filtering capabilities include sender, receiver, message types, sent date, received date, carbon copy, and blind carbon copy, along with Keyword Query Language (KQL) syntax. For more details, see [In-Place eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).</span></span>
  
<span data-ttu-id="d8bd6-p107">Mithilfe von Exchange Admin Center und der Remote-Windows PowerShell können in einer Compliance-eDiscovery-Suche bis zu 5.000 Postfächer gleichzeitig durchsucht werden. Details über die Verwendung der Remote-Windows PowerShell zum Ausführen von Compliance-eDiscovery-Suchvorgängen finden Sie unter [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170).</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p107">The Exchange admin center and remote Windows PowerShell can be used to search up to 5,000 mailboxes at a time in an In-Place eDiscovery search. For details about using remote Windows PowerShell to run In-Place eDiscovery searches, see [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170).</span></span> 
  
> [!NOTE]
> <span data-ttu-id="d8bd6-p108">In der Remote-Windows PowerShell kann das  `Search-Mailbox`-Cmdlet verwendet werden, um mehr als 5.000 Postfächer zu suchen. Weitere Informationen zum Durchsuchen einer großen Anzahl an Postfächern anhand von Remote Windows PowerShell finden Sie unter [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171).</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p108">In remote Windows PowerShell, the  `Search-Mailbox` cmdlet can be used to search more than 5,000 mailboxes. For details about searching large numbers of mailboxes using remote Windows PowerShell, see [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171).</span></span> 
  
<span data-ttu-id="d8bd6-p109">Die Ergebnisse von Compliance-eDiscovery-Suchvorgängen können in einer Vorschau in der Exchange-Verwaltungskonsole angezeigt, in eine PST-Datei exportiert oder in einen speziellen Typ von Postfach mit der Bezeichnung Discovery-Postfach kopiert werden. Administratoren oder Richtlinienbeauftrage können eine Verbindung zum Discovery-Postfach herstellen, um Nachrichten zu lesen. Weitere Informationen finden Sie unter [Erstellen einer Compliance-eDiscovery-Suche](https://go.microsoft.com/fwlink/p/?LinkId=314172).</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p109">Results of an In-Place eDiscovery search can be previewed in the Exchange admin center, exported to a .pst file, or copied to a special type of mailbox, called a discovery mailbox. Administrators or compliance officers can connect to the discovery mailbox to review messages. For details, see [Create an In-Place eDiscovery Search](https://go.microsoft.com/fwlink/p/?LinkId=314172).</span></span>
  
> [!NOTE]
> <span data-ttu-id="d8bd6-p110">Beim Kopieren von Suchergebnissen einer Compliance-eDiscovery-Suche, die über lokale und cloudbasierte Postfächer und Archive durchgeführt wurde, müssen Sie ein lokales Discovery-Postfach auswählen. Nachrichten aus dem lokalen primären Postfach und dem cloudbasierten Archiv werden in das lokale Discovery-Postfach kopiert.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p110">When copying search results for an In-Place eDiscovery search performed across on-premises and cloud-based mailboxes or archives, you must select an on-premises discovery mailbox. Messages from the on-premises primary mailbox and the cloud-based archive are copied to the on-premises discovery mailbox.</span></span> 
  
<span data-ttu-id="d8bd6-p111">Administratoren können auch nach unangemessenen E-Mails, die an mehrere Postfächer in der Organisation geschickt wurden, suchen und diese löschen. Wenn beispielsweise eine E-Mail mit vertraulichen Gehaltsinformationen versehentlich an alle Mitarbeiter gesendet wurde, kann ein Administrator diese E-Mail aus den Postfächern der Benutzer löschen. Diese Art der Suche ist in der Exchange-Verwaltungskonsole nicht verfügbar. Sie muss über Remote PowerShell durchgeführt werden. Weitere Informationen zum Löschen von Nachrichten aus Benutzerpostfächern finden Sie unter [Suchen und Löschen von Nachrichten](https://go.microsoft.com/fwlink/p/?LinkId=314173).</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p111">Administrators can also search for and delete inappropriate email messages sent to multiple mailboxes across their organizations. For example, if confidential salary information was accidentally sent to all employees, an administrator can delete the email from the users' mailboxes. This type of search is not available in the Exchange admin center. It must be performed using Remote PowerShell. For details on how to delete messages from users' mailboxes, see [Search and Delete Messages](https://go.microsoft.com/fwlink/p/?LinkId=314173).</span></span>
  
## <a name="security-features-in-exchange-online-archiving"></a><span data-ttu-id="d8bd6-160">Sicherheitsfunktionen der Exchange Online-Archivierung</span><span class="sxs-lookup"><span data-stu-id="d8bd6-160">Security features in Exchange Online Archiving</span></span>

<span data-ttu-id="d8bd6-161">Im folgenden Abschnitt werden die Sicherheitsfunktionen von Microsoft Exchange Online-Archivierung beschrieben.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-161">The following sections describe the security features of Microsoft Exchange Online Archiving.</span></span>
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a><span data-ttu-id="d8bd6-162">Verschlüsselung zwischen lokalen Servern und Exchange Online-Archivierung</span><span class="sxs-lookup"><span data-stu-id="d8bd6-162">Encryption between on-premises servers and Exchange Online Archiving</span></span>

<span data-ttu-id="d8bd6-p112">TLS wird zum Verschlüsseln der Verbindung zwischen E-Mail-Servern verwendet, um Spoofing zu verhindern und die Vertraulichkeit von in der Übertragung befindlichen Nachrichten zu ermöglichen. TLS dient auch zum Schutz des Datenverkehrs des lokalen E-Mail-Servers zu Office 365-Datenzentren für Exchange Online-Archivierung.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p112">TLS is used to encrypt the connection between email servers to help prevent spoofing and provide confidentiality for messages in transit. TLS is also used for securing on-premises mail server traffic to Office 365 data centers for Exchange Online Archiving.</span></span>
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a><span data-ttu-id="d8bd6-165">Verschlüsselung zwischen Clients und Exchange Online-Archivierung</span><span class="sxs-lookup"><span data-stu-id="d8bd6-165">Encrypting between clients and Exchange Online Archiving</span></span>

<span data-ttu-id="d8bd6-166">Bei Clientverbindungen zu Exchange Online-Archivierung wird die Sicherheit anhand der folgenden Verschlüsselungsmethoden erhöht:</span><span class="sxs-lookup"><span data-stu-id="d8bd6-166">Client connections to Exchange Online Archiving use the following encryption methods to enhance security:</span></span>
  
- <span data-ttu-id="d8bd6-167">SSL wird zum Sichern von Outlook-, Outlook Web App- und Exchange Web Services-Datenverkehr über den TCP-Port 443 verwendet.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-167">SSL is used for securing Outlook, Outlook Web App, and Exchange Web Services traffic, using TCP port 443.</span></span>
    
- <span data-ttu-id="d8bd6-168">Clientverbindungen zu lokalen Servern ändern sich mit der Einführung von Exchange Online-Archivierung nicht.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-168">Client connections to on-premises servers do not change with the introduction of Exchange Online Archiving.</span></span>
    
### <a name="encryption-smime-and-pgp"></a><span data-ttu-id="d8bd6-169">Verschlüsselung: S/MIME und PGP</span><span class="sxs-lookup"><span data-stu-id="d8bd6-169">Encryption: S/MIME and PGP</span></span>

<span data-ttu-id="d8bd6-p113">Exchange Online-Archivierung speichert S/MIME(Secure/Multipurpose Internet Mail Extensions)-Nachrichten. Exchange Online-Archivierung hostet jedoch keine S/MIME-Funktionen oder öffentliche Schlüssel und bietet auch keine Speicher-, Verwaltungs- und Verzeichnisdienste für Schlüssel an, da all diese Dienste mit der lokalen Exchange-Infrastruktur zusammenhängen.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p113">Exchange Online Archiving will store Secure/Multipurpose Internet Mail Extensions (S/MIME) messages. However, Exchange Online Archiving does not host S/MIME functions or host the public keys, nor does it provide key repository, key management, or key directory services because all of these services attach to the on-premises Exchange infrastructure.</span></span>
  
<span data-ttu-id="d8bd6-172">In ähnlicher Weise speichert Exchange Online-Archivierung Nachrichten, die anhand von clientseitigen, Drittanbieter-Verschlüsselungslösungen wie Pretty Good Privacy (PGP) verschlüsselt wurden.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-172">Similarly, Exchange Online Archiving will store messages that are encrypted using client-side, third-party encryption solutions such as Pretty Good Privacy (PGP).</span></span>
  
### <a name="information-rights-management"></a><span data-ttu-id="d8bd6-173">Verwaltung von Informationsrechten</span><span class="sxs-lookup"><span data-stu-id="d8bd6-173">Information Rights Management</span></span>

<span data-ttu-id="d8bd6-p114">Exchange Online-Archivierung bietet keine gehosteten Dienste für die Verwaltung von Informationsrechten, doch Administratoren können lokale Active Directory-Rechteverwaltungsdienste nutzen. Wenn ein AD RMS-Server bereitgestellt wird, kann Outlook direkt mit dem Server kommunizieren und ermöglicht somit den Benutzern das Verfassen und Lesen von IRM-geschützten Nachrichten. Wenn die Interoperabilität zwischen AD RMS-Server und lokaler Exchange-Umgebung konfiguriert wurde, können Benutzer IRM-geschützte Nachrichten verfassen und lesen.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p114">Exchange Online Archiving does not provide hosted Information Rights Management (IRM) services, but administrators can use on-premises Active Directory Rights Management Services (AD RMS). If an AD RMS server is deployed, Outlook can communicate directly with that server, enabling users to compose and read IRM-protected messages. If interoperability between the AD RMS server and the on-premises Exchange environment is configured, users will be able to compose and read IRM-protected messages.</span></span>
  
#### <a name="support-for-irm-in-outlook-web-app"></a><span data-ttu-id="d8bd6-177">Unterstützung für IRM in Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="d8bd6-177">Support for IRM in Outlook Web App</span></span>

<span data-ttu-id="d8bd6-p115">Benutzer können in Outlook Web App wie in Outlook IRM-geschützte Nachrichten lesen und verfassen. IRM-geschützte Nachrichten in Outlook Web App können über die Browser Internet Explorer, Firefox, Safari und Chrome angezeigt werden (ohne erforderliches Plug-in). Die Nachrichten bieten die Volltextsuche, die Unterhaltungsansicht und das Vorschaufenster. Dafür muss die Interoperabilität zwischen dem AD RMS(Active Directory Rights Management Services)-Server und der lokalen Exchange-Umgebung konfiguriert werden.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p115">Users can read and create IRM-protected messages natively in Outlook Web App, just as they can in Outlook. IRM-protected messages in Outlook Web App can be accessed through Internet Explorer, Firefox, Safari, and Chrome (with no plug-in required). The messages include full-text search, conversation view, and the preview pane. Interoperability between the Active Directory Rights Management Services server and the on-premises Exchange environment must be configured to enable this.</span></span>
  
#### <a name="irm-search"></a><span data-ttu-id="d8bd6-182">IRM-Suche</span><span class="sxs-lookup"><span data-stu-id="d8bd6-182">IRM Search</span></span>

<span data-ttu-id="d8bd6-p116">IRM-geschützte Nachrichten werden indiziert und sind durchsuchbar, einschließlich Header, Betreff, Text und Anlagen. Benutzer können IRM-geschützte Elemente in Outlook und Outlook Web App durchsuchen. Administratoren können IRM-geschützte Elemente über In-Situ-eDiscovery oder unter Verwendung des **Search-Mailbox** -Cmdlets durchsuchen.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p116">IRM-protected messages are indexed and searchable, including headers, subject, body, and attachments. Users can search IRM-protected items in Outlook and Outlook Web App, and administrators can search IRM-protected items by using In-Place eDiscovery or the **Search-Mailbox** cmdlet.</span></span> 
  
### <a name="auditing"></a><span data-ttu-id="d8bd6-185">Überwachung</span><span class="sxs-lookup"><span data-stu-id="d8bd6-185">Auditing</span></span>

<span data-ttu-id="d8bd6-186">Exchange Online-Archivierung bietet zwei Arten von integrierten Überwachungsfunktionen:</span><span class="sxs-lookup"><span data-stu-id="d8bd6-186">Exchange Online Archiving provides two types of built-in auditing capabilities:</span></span>
  
- <span data-ttu-id="d8bd6-187">**Administrator-Überwachungsprotokollierung** Die Administrator-Überwachungsprotokollierung ermöglicht Kunden das Nachverfolgen von Änderungen durch Administratoren in der Exchange Online-Archivierung-Umgebung, darunter Änderungen an der rollenbasierten Zugriffssteuerung oder an Exchange-Richtlinien und -Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-187">**Administrator audit logging** Administrator audit logging allows customers to track changes made by their administrators in the Exchange Online Archiving environment, including changes to RBAC roles or Exchange policies and settings.</span></span> 
    
- <span data-ttu-id="d8bd6-188">**Postfachüberwachungsprotokollierung** Die Postfachüberwachungsprotokollierung ermöglicht Kunden das Nachverfolgen des Postfachzugriffs durch Benutzer, die nicht mit dem Postfachbesitzer identisch sind.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-188">**Mailbox audit logging** Mailbox audit logging allows customers to track access to mailboxes by users other than the mailbox owner.</span></span> 
    
<span data-ttu-id="d8bd6-p117">In der Exchange-Verwaltungskonsole stehen einige vordefinierte Überwachungsberichte zur Verfügung, einschließlich Berichten zu Administratorrollenänderungen, zu Beweissicherungsverfahren und zu Postfachzugriffen von Nicht-Besitzern. Administratoren können Berichte nach Datum und Rolle filtern, außerdem können sie alle Überwachungsereignisse für bestimmte Postfächer im XML-Format exportieren, um sie langfristig aufzubewahren oder benutzerdefinierte Berichte zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p117">Several predefined audit reports are available in the Exchange admin center, including Administrator Role Changes, Litigation Hold, and Non-Owner Mailbox Access. Administrators can filter reports by date and role, and they can export all audit events for specified mailboxes in XML format for long-term retention or custom reporting.</span></span>
  
<span data-ttu-id="d8bd6-p118">Standardmäßig ist die Administrator-Überwachungsprotokollierung aktiviert und die Postfachüberwachungsprotokollierung deaktiviert. Administratoren können anhand von Remote Windows PowerShell die Postfachüberwachungsprotokollierung für einige oder alle Postfächer in der Organisation aktivieren. Weitere Informationen finden Sie unter [Überwachungsberichte](https://go.microsoft.com/fwlink/p/?LinkId=314175).</span><span class="sxs-lookup"><span data-stu-id="d8bd6-p118">Administrator audit logging is on by default, and mailbox audit logging is off by default. Administrators can use remote Windows PowerShell to enable mailbox audit logging for some or all mailboxes in their organization. For more information, see [Auditing Reports](https://go.microsoft.com/fwlink/p/?LinkId=314175).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="d8bd6-194">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="d8bd6-194">Feature Availability</span></span>

<span data-ttu-id="d8bd6-195">Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Beschreibung des Exchange Online-Archivierungsdiensts](exchange-online-archiving-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="d8bd6-195">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  
