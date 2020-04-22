---
title: Kompatibilitäts-und Sicherheitsfeatures in Exchange Online Archivierung
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- compliance-and-security-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7482322a-39fe-4a99-b29c-63cb1bc3cf1f
ms.openlocfilehash: b977fea67c28a660a7468945c76d19677769cd8f
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/21/2020
ms.locfileid: "43638693"
---
# <a name="compliance-and-security-features-in-exchange-online-archiving"></a>Kompatibilitäts-und Sicherheitsfeatures in Exchange Online Archivierung

## <a name="compliance-features-in-exchange-online-archiving"></a>Kompatibilitätsfunktionen der Exchange Online-Archivierung

Im folgenden Abschnitt werden die Kompatibilitätsfunktionen von Microsoft Exchange Online-Archivierung beschrieben.
  
### <a name="retention-policies"></a>Aufbewahrungsrichtlinien

Exchange Online-Archivierung bietet Aufbewahrungsrichtlinien, die Organisationen dabei helfen, ihre Verpflichtungen hinsichtlich E-Mails und anderen Kommunikationsformen zu reduzieren. Mithilfe dieser Richtlinien haben Administratoren die Möglichkeit, Aufbewahrungseinstellungen für bestimmte Ordner des Posteingangs eines Benutzers anzuwenden. Administratoren können Benutzern auch ein Menü mit Aufbewahrungsrichtlinien erteilen und die Richtlinien auf bestimmte Elemente, Unterhaltungen oder Ordner anwenden, die Outlook 2010 oder höher oder Outlook im Internet verwenden sollen. In Exchange Online-Archivierung verwalten Administratoren Aufbewahrungsrichtlinien aus der lokalen Infrastruktur.
  
Exchange Online-Archivierung bietet zwei Arten von Richtlinien: archivieren und löschen. Beide Typen können auf das gleiche Element oder den gleichen Ordner angewendet werden. Ein Benutzer kann beispielsweise eine E-Mail so markieren, dass sie nach einer bestimmten Anzahl von Tagen automatisch in das persönliche Archiv verschoben oder nach einer anderen festgelegten Anzahl von Tagen gelöscht wird.
  
Mit Outlook 2010 und höher und Outlook im Internet können Benutzer Aufbewahrungsrichtlinien auf Ordner, Unterhaltungen oder einzelne Nachrichten anwenden, und Sie können auch die angewendeten Aufbewahrungsrichtlinien und die erwarteten Löschungs Termine für Nachrichten anzeigen. Benutzer von anderen E-Mail-Clients können E-Mails basierend auf vom Administrator bereitgestellten Aufbewahrungsrichtlinien löschen oder archivieren lassen, verfügen aber nicht über das gleiche Maß an Transparenz und Steuerung.
  
Die Aufbewahrungsrichtlinienfunktionen in Exchange Online-Archivierung entsprechen denen von Exchange Server 2010 Service Pack 2 (SP2) und höher. Administratoren können Aufbewahrungsrichtlinien aus lokalen Exchange Server 2010-Umgebungen (und höher) verwalten. Verwaltete Ordner, ein älterer Ansatz zur Verwaltung von Nachrichtendatensätzen, der in Exchange 2007 eingeführt wurde, stehen bei der Exchange Online-Archivierung nicht zur Verfügung und sind mit dieser nicht kompatibel. Weitere Informationen finden Sie unter [Aufbewahrungstags und Aufbewahrungsrichtlinien](https://go.microsoft.com/fwlink/p/?LinkID=314153).
  
### <a name="in-place-hold-and-litigation-hold"></a>Compliance-Archiv und Aufbewahrung für eventuelle Rechtsstreitigkeiten

Wenn Rechtsstreitigkeiten zu erwarten sind, sind Organisationen dazu verpflichtet, die für den Fall relevanten elektronisch gespeicherten Informationen einschließlich E-Mail aufzubewahren. Diese Erwartung kann eintreten, bevor die Details des Falls bekannt werden, und die Menge der aufzubewahrenden Daten ist häufig groß. Organisationen können alle E-Mails zu einem bestimmten Thema oder alle E-Mails für bestimmte Personen aufbewahren.
  
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

Exchange Online-Archivierung unterstützt Compliance-eDiscovery für das Durchsuchen von Postfachinhalten in einer Organisation. Unter Verwendung der Exchange-Verwaltungskonsole oder von Remote Windows PowerShell von einem lokalen Exchange 2013-Server können Administratoren oder autorisierte Discovery-Manager verschiedene Postfachelemente durchsuchen, darunter E-Mails, Anhänge, Kalendertermine, Aufgaben und Kontakte. Mit der Compliance-eDiscovery-Funktion können primäre Postfächer und Archive gleichzeitig durchsucht werden. Die umfangreichen Filterfunktionen umfassen Absender, Empfänger, Nachrichtentyp, Sende-/Empfangsdatum und Cc/Bcc sowie die Verwendung der KQL(Keyword Query Language)-Syntax. Weitere Informationen finden Sie unter [Compliance-eDiscovery](https://go.microsoft.com/fwlink/p/?LinkId=314169).
  
Mithilfe von Exchange Admin Center und der Remote-Windows PowerShell können in einer Compliance-eDiscovery-Suche bis zu 5.000 Postfächer gleichzeitig durchsucht werden. Details über die Verwendung der Remote-Windows PowerShell zum Ausführen von Compliance-eDiscovery-Suchvorgängen finden Sie unter [New-MailboxSearch](https://go.microsoft.com/fwlink/p/?LinkId=314170). 
  
> [!NOTE]
> In der Remote-Windows PowerShell kann das  `Search-Mailbox`-Cmdlet verwendet werden, um mehr als 5.000 Postfächer zu suchen. Weitere Informationen zum Durchsuchen einer großen Anzahl an Postfächern anhand von Remote Windows PowerShell finden Sie unter [Search-Mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314171). 
  
Die Ergebnisse von Compliance-eDiscovery-Suchvorgängen können in einer Vorschau in der Exchange-Verwaltungskonsole angezeigt, in eine PST-Datei exportiert oder in einen speziellen Typ von Postfach mit der Bezeichnung Discovery-Postfach kopiert werden. Administratoren oder Richtlinienbeauftrage können eine Verbindung zum Discovery-Postfach herstellen, um Nachrichten zu lesen. Weitere Informationen finden Sie unter [Erstellen einer Compliance-eDiscovery-Suche](https://go.microsoft.com/fwlink/p/?LinkId=314172).
  
> [!NOTE]
> Beim Kopieren von Suchergebnissen einer Compliance-eDiscovery-Suche, die über lokale und cloudbasierte Postfächer und Archive durchgeführt wurde, müssen Sie ein lokales Discovery-Postfach auswählen. Nachrichten aus dem lokalen primären Postfach und dem cloudbasierten Archiv werden in das lokale Discovery-Postfach kopiert. 
  
Administratoren können auch nach unangemessenen E-Mails, die an mehrere Postfächer in der Organisation geschickt wurden, suchen und diese löschen. Wenn beispielsweise eine E-Mail mit vertraulichen Gehaltsinformationen versehentlich an alle Mitarbeiter gesendet wurde, kann ein Administrator diese E-Mail aus den Postfächern der Benutzer löschen. Diese Art der Suche ist in der Exchange-Verwaltungskonsole nicht verfügbar. Sie muss über Remote PowerShell durchgeführt werden. Weitere Informationen zum Löschen von Nachrichten aus Benutzerpostfächern finden Sie unter [Suchen und Löschen von Nachrichten](https://go.microsoft.com/fwlink/p/?LinkId=314173).
  
## <a name="security-features-in-exchange-online-archiving"></a>Sicherheitsfunktionen der Exchange Online-Archivierung

Im folgenden Abschnitt werden die Sicherheitsfunktionen von Microsoft Exchange Online-Archivierung beschrieben.
  
### <a name="encryption-between-on-premises-servers-and-exchange-online-archiving"></a>Verschlüsselung zwischen lokalen Servern und Exchange Online-Archivierung

TLS wird zum Verschlüsseln der Verbindung zwischen E-Mail-Servern verwendet, um Spoofing zu verhindern und die Vertraulichkeit von in der Übertragung befindlichen Nachrichten zu ermöglichen. TLS wird auch verwendet, um den lokalen e-Mail-Server Datenverkehr für Exchange Online Archivierung an Microsoft-Rechenzentren zu sichern.
  
### <a name="encrypting-between-clients-and-exchange-online-archiving"></a>Verschlüsselung zwischen Clients und Exchange Online-Archivierung

Bei Clientverbindungen zu Exchange Online-Archivierung wird die Sicherheit anhand der folgenden Verschlüsselungsmethoden erhöht:
  
- SSL wird zum Sichern von Outlook, Outlook im Internet und Exchange Webdienste-Datenverkehr mithilfe von TCP-Port 443 verwendet.
    
- Clientverbindungen zu lokalen Servern ändern sich mit der Einführung von Exchange Online-Archivierung nicht.
    
### <a name="encryption-smime-and-pgp"></a>Verschlüsselung: S/MIME und PGP

Exchange Online-Archivierung speichert S/MIME(Secure/Multipurpose Internet Mail Extensions)-Nachrichten. Exchange Online-Archivierung hostet jedoch keine S/MIME-Funktionen oder öffentliche Schlüssel und bietet auch keine Speicher-, Verwaltungs- und Verzeichnisdienste für Schlüssel an, da all diese Dienste mit der lokalen Exchange-Infrastruktur zusammenhängen.
  
In ähnlicher Weise speichert Exchange Online-Archivierung Nachrichten, die anhand von clientseitigen, Drittanbieter-Verschlüsselungslösungen wie Pretty Good Privacy (PGP) verschlüsselt wurden.
  
### <a name="information-rights-management"></a>Verwaltung von Informationsrechten

Exchange Online-Archivierung bietet keine gehosteten Dienste für die Verwaltung von Informationsrechten, doch Administratoren können lokale Active Directory-Rechteverwaltungsdienste nutzen. Wenn ein AD RMS-Server bereitgestellt wird, kann Outlook direkt mit dem Server kommunizieren und ermöglicht somit den Benutzern das Verfassen und Lesen von IRM-geschützten Nachrichten. Wenn die Interoperabilität zwischen AD RMS-Server und lokaler Exchange-Umgebung konfiguriert wurde, können Benutzer IRM-geschützte Nachrichten verfassen und lesen.
  
#### <a name="support-for-irm-in-outlook-on-the-web"></a>Unterstützung für IRM in Outlook im Internet

Benutzer können IRM-geschützte Nachrichten nativ in Outlook im Web lesen und erstellen, so wie Sie es in Outlook tun können. Auf IRM-geschützte Nachrichten in Outlook im Internet kann über Internet Explorer, Firefox, Safari und Chrome (ohne Plug-in erforderlich) zugegriffen werden. Die Nachrichten bieten die Volltextsuche, die Unterhaltungsansicht und das Vorschaufenster. Dafür muss die Interoperabilität zwischen dem AD RMS(Active Directory Rights Management Services)-Server und der lokalen Exchange-Umgebung konfiguriert werden.
  
#### <a name="irm-search"></a>IRM-Suche

IRM-geschützte Nachrichten sind indiziert und durchsuchbar, einschließlich Kopfzeilen, Betreff, Text und Anlagen. Benutzer können IRM-geschützte Elemente in Outlook und Outlook im Internet durchsuchen, und Administratoren können IRM-geschützte Elemente mithilfe von in-Place eDiscovery oder mit dem Cmdlet **Search-Mailbox** durchsuchen.
  
### <a name="auditing"></a>Überwachung

Exchange Online-Archivierung bietet zwei Arten von integrierten Überwachungsfunktionen:
  
- **Administrator-Überwachungsprotokollierung** Die Administrator-Überwachungsprotokollierung ermöglicht Kunden das Nachverfolgen von Änderungen durch Administratoren in der Exchange Online-Archivierung-Umgebung, darunter Änderungen an der rollenbasierten Zugriffssteuerung oder an Exchange-Richtlinien und -Einstellungen. 
    
- **Postfachüberwachungsprotokollierung** Die Postfachüberwachungsprotokollierung ermöglicht Kunden das Nachverfolgen des Postfachzugriffs durch Benutzer, die nicht mit dem Postfachbesitzer identisch sind. 
    
In der Exchange-Verwaltungskonsole stehen einige vordefinierte Überwachungsberichte zur Verfügung, einschließlich Berichten zu Administratorrollenänderungen, zu Beweissicherungsverfahren und zu Postfachzugriffen von Nicht-Besitzern. Administratoren können Berichte nach Datum und Rolle filtern, außerdem können sie alle Überwachungsereignisse für bestimmte Postfächer im XML-Format exportieren, um sie langfristig aufzubewahren oder benutzerdefinierte Berichte zu erstellen.
  
Standardmäßig ist die Administrator-Überwachungsprotokollierung aktiviert und die Postfachüberwachungsprotokollierung deaktiviert. Administratoren können anhand von Remote Windows PowerShell die Postfachüberwachungsprotokollierung für einige oder alle Postfächer in der Organisation aktivieren. Weitere Informationen finden Sie unter [Überwachungsberichte](https://go.microsoft.com/fwlink/p/?LinkId=314175).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Archivierungsdienst Beschreibung](exchange-online-archiving-service-description.md).
  

