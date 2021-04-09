---
title: Messagingrichtlinie und -einhaltung
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-message-policy-recovery-and-compliance
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 5c43c8eb-f8f7-4b5a-a743-b1dab7dc2fc8
description: Erfahren Sie mehr über Nachrichtenrichtlinie und Compliance in Exchange Online.
ms.openlocfilehash: 22de08fb350785b63db97da7271182eb62980cae
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652709"
---
# <a name="message-policy-and-compliance"></a>Messagingrichtlinie und -einhaltung

## <a name="archiving-exchange-online-based-mailboxes"></a>Archivieren von Exchange Online-basierten Postfächern

Exchange Online-Postfächer befinden sich in der Cloud und müssen unter Verwendung eindeutiger Hostingumgebungen archiviert werden. In manchen Fällen kann Exchange Online auch zur Archivierung von lokalen Postfächern in der Cloud verwendet werden. In diesem Abschnitt werden die Optionen für die Archivierung mit Exchange Online beschrieben.
  
Exchange Online bietet integrierte Archivierungsfunktionen für cloudbasierte Postfächer, einschließlich eines Compliance-Archivs, dass Benutzern einen praktischen Speicherort für ältere E-Mails zur Verfügung stellt. Ein In-Place ist ein spezieller Postfachtyp, der neben den primären Postfachordnern eines Benutzers in Outlook und Outlook im Web angezeigt wird. Benutzer können auf das Archiv genauso zugreifen und es durchsuchen, wie sie es von ihren primären Postfächern gewohnt sind. Die Verfügbarkeit der Funktionalität hängt vom jeweiligen Client ab:
  
- **Outlook 2016, Outlook 2013, Outlook 2010 und Outlook im Web** Benutzer haben Zugriff auf die vollständigen Funktionen des Archivs sowie auf zugehörige Compliancefeatures wie die Kontrolle über Aufbewahrungs- und Archivrichtlinien. 
    
- **Outlook 2007** Benutzer erhalten grundlegenden Support für das Compliance-Archiv. Nicht alle Features für die Archivierung und Richtlinientreue sind jedoch verfügbar. So können Benutzer beispielsweise keine Aufbewahrungs- und Archivierungsrichtlinien für Postfachelemente anwenden, sondern müssen stattdessen auf Richtlinien vertrauen, die vom Administrator bereitgestellt werden. 
    
Administratoren verwenden die Exchange-Verwaltungskonsole oder Windows PowerShell-Remotesitzungen, um für bestimmte Benutzer die Funktion für persönliche Archive zu aktivieren.
  
Weitere Informationen finden Sie unter:
  
- [Archivieren von Postfächern in Exchange Online](../exchange-online-archiving-service-description/archive-features.md)
    
- [Aktivieren oder Deaktivieren von Archivpostfächern in Exchange Online](/office365/securitycompliance/enable-archive-mailboxes)
    
### <a name="archive-sizes"></a>Größe des Archivs

In einem persönlichen Archiv können nur die Nachrichtendaten eines Benutzers gespeichert werden. Die Zuweisung von Speicher hängt vom jeweiligen Abonnementplan ab. Weitere Informationen zur Größe von Archivpostfächern finden Sie im Abschnitt "Postfachspeicherbeschränkungen" in [Exchange Online-Beschränkungen.](exchange-online-limits.md)
  
> [!IMPORTANT]
> - Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung in ein Exchange Online-Postfach zu kopieren. Microsoft behält sich das Recht vor, die unbegrenzte Archivierung in Fällen zu verweigern, in denen ein Postfacharchiv nicht in einem persönlichen Szenario oder in anderen Fällen unangemessener Verwendung verwendet wird.
> - Das Compliance-Archiv hat spezielle Lizenzierungsanforderungen für Outlook-Benutzer. Die Benutzer von Outlook 2007 müssen das kumulative Office 2007-Update vom Februar 2011 installiert haben, um auf das persönliche Archiv zugreifen zu können. 
> - Exchange Online unterstützt das  _Cmdlet New-MailboxImportRequest_ Windows PowerShell von Exchange Server 2010 Service Pack 1 oder höher nicht für den administratorgesteuerten Import von PST-Dateien in ein persönliches Archiv. Wenn ein Benutzer sowohl über das primäre Postfach als auch über das Archiv in Exchange Online verfügt, kann ein Administrator das kostenlose Tool "PST Capture" verwenden, um Daten aus PST-Dateien in das primäre Postfach oder Archiv des Benutzers zu importieren.

## <a name="cloud-based-archiving-of-on-premises-mailboxes"></a>Cloudbasierte Archivierung von lokalen Postfächern

Mit der Microsoft Exchange Online-Archivierung, einer gehosteten Archivierungslösung von Microsoft, kann Exchange Online zur cloudbasierten Archivierung von Postfächern verwendet werden, die auf lokalen Postfachservern mit Exchange Server 2010 oder höher gehostet werden. Hierfür muss sich die lokale Organisation im Hybridmodus befinden oder für die Exchange Online-Archivierung eingerichtet werden.
  
> [!IMPORTANT]
> Wenn Benutzer über ein lokales Postfach auf einem Exchange 2010-Postfachserver verfügen und eine Richtlinie für verwaltete Ordner anwenden, ist die Aktivierung von lokalen oder cloudbasierten Compliance-Archiven nicht möglich. 
  
## <a name="retention-tags-and-retention-policies"></a>Aufbewahrungstags und Aufbewahrungsrichtlinien

Exchange Online bietet Aufbewahrungsrichtlinien, die Organisationen dabei helfen, ihre Verpflichtungen hinsichtlich E-Mails und anderen Kommunikationsformen zu reduzieren. Mithilfe dieser Richtlinien haben Administratoren die Möglichkeit, Aufbewahrungseinstellungen für bestimmte Ordner des Posteingangs eines Benutzers anzuwenden. Administratoren können Benutzern auch ein Menü mit Aufbewahrungsrichtlinien zur Verfügung stellen und ihnen ermöglichen, die Richtlinien mithilfe von Outlook 2010 oder höher oder Outlook im Web auf bestimmte Elemente, Unterhaltungen oder Ordner anzuwenden.
  
In Exchange Online können Administratoren die Aufbewahrungsrichtlinien mithilfe der Exchange-Verwaltungskonsole oder von Windows PowerShell-Remotesitzungen verwalten.
  
Exchange Online bietet zwei Richtlinientypen: Archiv- und Löschrichtlinien. Beide Typen können für das gleiche Element oder den gleichen Ordner kombiniert werden. Ein Benutzer kann beispielsweise eine E-Mail so markieren, dass sie nach einer bestimmten Anzahl von Tagen automatisch in das Compliance-Archiv verschoben und nach einer anderen bestimmten Anzahl von Tagen gelöscht wird.
  
Mit Outlook 2010 oder höher und Outlook im Web können Benutzer Aufbewahrungsrichtlinien auf Ordner, Unterhaltungen oder einzelne Nachrichten anwenden. Außerdem können sie die geltenden Aufbewahrungsrichtlinien und vorgesehenen Löschtermine von Nachrichten anzeigen. Benutzer von anderen E-Mail-Clients können E-Mails nur basierend auf serverseitigen, vom Administrator definierten Aufbewahrungsrichtlinien löschen oder archivieren lassen.
  
Die Aufbewahrungsrichtlinienfunktionen in Exchange Online entsprechen denen von Exchange Server 2010 Service Pack 2 RU4. Administratoren können mithilfe von Windows PowerShell-Remotesitzungen Aufbewahrungsrichtlinien aus lokalen Umgebungen mit Exchange Server 2010 oder höher zu Exchange Online migrieren.
  
> [!IMPORTANT]
> Verwaltete Ordner, ein älterer Ansatz für die Messaging-Datensatzverwaltung, der in Exchange Server 2007 eingeführt wurde, stehen in Exchange Online nicht zur Verfügung. 
  
Weitere Informationen finden Sie unter [Aufbewahrungstags und Aufbewahrungsrichtlinien](/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies).
  
## <a name="encryption-of-data-at-rest"></a>Verschlüsselung von Daten im Ruhezustand

Die Verschlüsselung ruherer Kundendaten wird von mehreren dienstseitigen Technologien bereitgestellt, einschließlich BitLocker, DKM, Azure Storage Service Encryption und Dienstverschlüsselung in Exchange Online, Skype for Business, OneDrive for Business und SharePoint Online. Office 365-Dienstverschlüsselung umfasst eine Option zum Verwenden von Kunden verwalteter Verschlüsselungsschlüssel, die in Azure Key Vault gespeichert sind. Diese vom Kunden verwaltete Schlüsseloption namens [Customer Key](/microsoft-365/compliance/customer-key-overview)ist für Exchange Online, SharePoint Online und OneDrive for Business verfügbar. 
  
### <a name="bitlocker"></a>BitLocker

Microsoft-Server verwenden BitLocker, um datenträgerlaufwerke zu verschlüsseln, die Kundendaten enthalten, die sich auf Volumeebene befinden. BitLocker-Verschlüsselung ist eine Datenverschlüsselungsfunktion, die in Windows integriert ist. BitLocker ist eine der Technologien, die zum Schutz vor Bedrohungen verwendet werden, falls andere Prozesse oder Steuerelemente hinfällig werden (z. B. Zugriffssteuerung oder Access Control oder Recycling von Hardware), sodass andere Personen möglicherweise physischen Zugriff auf Laufwerke mit Kundendaten erlangen könnten. In diesem Fall eliminiert BitLocker das potenzielle Risiko für Datendiebstahl oder Offenlegung aufgrund von verloren gegangener, gestohlener oder nicht ordnungsgemäß außer Betrieb gesetzter Computer und Datenträger. 
  
### <a name="distributed-key-manager"></a>Distributed Key Manager

Neben Bitlocker verwenden wir eine Technologie, die Distributed Key Manager (DKM) genannt wird. Die verteilte Schlüsselverwaltung (DKM) ist eine clientseitige Funktionalität, die eine Reihe von geheimen Schlüsseln zum Verschlüsseln und Entschlüsseln von Informationen verwendet. Nur Mitglieder einer bestimmten Sicherheitsgruppe in Active Directory-Domänendiensten können auf diese Schlüssel zugreifen, um die Daten zu entschlüsseln, die von DKM verschlüsselt wurden. In Exchange Online sind nur bestimmte Dienstkonten, unter denen die Exchange-Prozesse ausgeführt werden, Teil dieser Sicherheitsgruppe. Zum Standardverfahren im Datencenter gehört es, dass kein Benutzer Anmeldeinformationen erhält, die Teil dieser Sicherheitsgruppe sind. Daher hat keine Person Zugriff auf die Schlüssel, mit denen diese geheimen Daten entschlüsselt werden können.
  
## <a name="customer-key"></a>Kundenschlüssel

Mit dem Kundenschlüssel steuern Sie die Verschlüsselungsschlüssel Ihrer Organisation und konfigurieren diese dann so, dass ihre ruhenden Daten in den Rechenzentren von Microsoft verschlüsselt werden. Zu den Daten im Ruhezustand gehören Daten aus Exchange Online und Skype for Business, die in SharePoint Online und OneDrive for Business in Postfächern und Dateien gespeichert sind. Weitere Informationen finden Sie unter [Steuern Ihrer Daten in Verwendung von Customer Key](/office365/securitycompliance/controlling-your-data-using-customer-key) and Service Encryption with Customer Key [FAQ](/office365/securitycompliance/service-encryption-with-customer-key-faq).
  
## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

E-Mail-Benutzer können mit der Office 365-Nachrichtenverschlüsselung an jeden und ganz einfach verschlüsselte E-Mail-Nachrichten senden. Wir haben neue Funktionen bei der Office-Nachrichtenverschlüsselung angekündigt, die die Schutzfunktionen von Azure Information Encryption nutzen. Diese neuen Funktionen bieten eine verbesserte Endbenutzererfahrung, die eine einfache Freigabe und Zusammenarbeit an geschützten Nachrichten mit Personen innerhalb und außerhalb der Organisation ermöglichen. Für die neuen Funktionen der Office-Nachrichtenverschlüsselung müssen einige Setupanforderungen erfüllt sein. Informationen dazu finden Sie unter „Einrichten der neuen Office 365-Nachrichtenverschlüsselungsfunktionen, die auf Azure Information Protection aufbauen". Kunden mit älteren Versionen der Office 365-Nachrichtenverschlüsselung erhalten nur Zugriff auf die neuen Funktionen, wenn Sie der aufgeführte Anleitung folgen. Weitere Informationen zu den neuen und alten Funktionen der Office 365-Nachrichtenverschlüsselung finden Sie in den [häufig gestellten Fragen](https://support.office.com/article/Office-365-Message-Encryption-FAQ-0432dce9-d9b6-4e73-8a13-4a932eb0081e). 

Die erweiterte Office 365-Nachrichtenverschlüsselung bietet zusätzlichen Schutz, indem der Ablauf und der Widerruf von Nachrichten ermöglicht werden.  Sie können auch mehrere Vorlagen für verschlüsselte E-Mails erstellen, die aus Ihrer Organisation stammen.  Die erweiterte Nachrichtenverschlüsselung ist in Microsoft 365 E5, Office 365 E5, Microsoft 365 E5 (Preis für gemeinnützige Mitarbeiter), Office 365 Enterprise E5 (Preis für gemeinnützige Mitarbeiter) oder Office 365 Education A5 enthalten. Wenn Ihre Organisation über ein Abonnement verfügt, das keine erweiterte Office 365-Nachrichtenverschlüsselung umfasst, können Sie Microsoft 365 E5 Compliance oder die Office 365 Advanced Compliance SKU als Add-On erwerben.

## <a name="securemultipurpose-internet-mail-extensions-smime"></a>Secure/Multipurpose Internet Mail Extensions (S/MIME)

Mit S/MIME können Sie vertrauliche Daten schützen, indem Sie in Ihrer Organisation signierte und verschlüsselte E-Mails versenden. Administratoren können die remote Windows PowerShell verwenden, um S/MIME einzurichten, nachdem PKI-Zertifikate an die Benutzer ausgegeben wurden. Diese Zertifikate müssen von einem lokalen Active Directory-Zertifikatsdienst synchronisiert werden.
  
S/MIME wird in Microsoft Edge und Internet Explorer 11 unterstützt. Derzeit wird S/MIME von Firefox, Opera und Chrome nicht unterstützt. Weitere Informationen finden Sie unter [S/MIME zum Signieren und Verschlüsseln von Nachrichten](/Exchange/policy-and-compliance/smime?preserve-view=true&view=exchserver-2019).
  
## <a name="in-place-hold-and-litigation-hold"></a>Compliance-Archiv und Aufbewahrung für eventuelle Rechtsstreitigkeiten

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
  
Weitere Informationen finden Sie unter [Compliance-Archiv](/exchange/security-and-compliance/in-place-and-litigation-holds).
  
## <a name="in-place-ediscovery"></a>Compliance-eDiscovery

Mit Exchange Online können Kunden den Inhalt von Postfächern in einer Organisation mithilfe einer webbasierten Schnittstelle durchsuchen. Administratoren oder Verantwortliche für Richtlinientreue und Sicherheit, die autorisiert sind, eine Compliance-eDiscovery-Suche auszuführen (durch Zuweisen), können E-Mails, Anlagen, Kalendertermine, Aufgaben und Kontakte sowie andere Elemente durchsuchen. Mit der Compliance-eDiscovery-Funktion können primäre Postfächer und Archive gleichzeitig durchsucht werden. Die umfangreichen Filterfunktionen umfassen Absender, Empfänger, Nachrichtentyp, Sende-/Empfangsdatum und Cc/Bcc sowie die Verwendung der KQL-Syntax. Die Suchergebnisse beinhalten auch Elemente aus dem Ordner "Gelöschte Elemente", wenn sie mit der Suchabfrage übereinstimmen.
  
Die Ergebnisse von Compliance-eDiscovery-Suchvorgängen können in einer Vorschau in der webbasierten Oberfläche angezeigt, in eine PST-Datei exportiert oder in einen speziellen Typ von Postfach mit der Bezeichnung Discoverypostfach kopiert werden. Ein Discoverypostfach verfügt über ein Kontingent von 50 GB für die Speicherung von Suchergebnissen. Administratoren können auch Outlook mit dem Discoverypostfach verbinden, sodass der Zugriff auf die Suchergebnisse möglich ist und diese in eine PST-Datei exportiert werden können.
  
Für die Suche in mehreren Postfächern verwenden Administratoren entweder die Exchange-Verwaltungskonsole oder Windows PowerShell-Remotesitzungen. Mit der Exchange-Verwaltungskonsole kann eine schreibgeschützte Vorschau der Suchergebnisse bereitgestellt werden, die es Administratoren ermöglicht, eine Suche schnell zu prüfen und diese bei Bedarf mit anderen Parametern erneut auszuführen. Nach der Optimierung eines Suchvorgangs kann der Administrator die Ergebnisse in das Discoverypostfach kopieren.
  
Standardmäßig wird für jede Organisation ein Discoverypostfach erstellt. Administratoren können jedoch zusätzliche Discoverypostfächer mithilfe von Windows PowerShell-Remotesitzungen hinzufügen. Discoverypostfächer können nur zum Speichern von Compliance-eDiscovery-Suchergebnissen verwendet werden.
  
Für Compliance-eDiscovery-Suchvorgänge verwenden Administratoren entweder die Exchange-Verwaltungskonsole oder Windows PowerShell-Remotesitzungen. Mit der Exchange-Verwaltungskonsole kann eine schreibgeschützte Vorschau der Suchergebnisse bereitgestellt werden, die es Administratoren ermöglicht, eine Suche schnell zu prüfen und diese bei Bedarf mit anderen Parametern erneut auszuführen. Nach der Optimierung eines Suchvorgangs kann der Administrator die Ergebnisse in das Discoverypostfach kopieren oder die Suchergebnisse in eine PST-Datei exportieren.
  
Administratoren können entweder das Exchange Admin Center oder die Remote-Windows PowerShell verwenden, um gleichzeitig bis zu 10.000 Postfächer in einer Compliance-eDiscovery-Suche zu suchen. 
  
In Exchange Online können autorisierte Benutzer Compliance-eDiscovery-Suchen durchführen und eine der folgenden Aktionen auswählen:
  
- **Suchergebnisse schätzen** Rufen Sie eine Schätzung der Anzahl von Nachrichten ab, die von der Suche zurückgegeben werden - einschließlich einer Schlüsselwortstatistik zur Ermittlung der Effektivität von Schlüsselwörtern für die Suche und zur Optimierung der Suchparameter, falls erforderlich. 
    
- **Vorschau auf Suchergebnisse anzeigen**
    
- Kopiert Nachrichten, die in Suchergebnissen zurückgegeben werden, in ein Discoverypostfach.
    
Weitere Informationen finden Sie unter [Compliance-eDiscovery](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery).
  
## <a name="mail-flow-rules"></a>Nachrichtenflussregeln

Mithilfe von Nachrichtenflussregeln können Sie Nachrichten, die Ihre Organisation durchlaufen, auf bestimmte Bedingungen prüfen und entsprechende Aktionen ausführen. Mit Nachrichtenflussregeln können Sie Nachrichtenrichtlinien auf E-Mails anwenden, Nachrichten sichern, Nachrichtensysteme schützen und Informationsverluste vermeiden.
  
Viele Organisationen müssen gegenwärtig zur Einhaltung von Gesetzen, Vorschriften oder Unternehmensrichtlinien Messagingrichtlinien umsetzen, um die Interaktion zwischen Absendern und Empfängern sowohl innerhalb als auch außerhalb der Organisation zu begrenzen. Über das Einschränken von Interaktionen zwischen Einzelpersonen, Abteilungsgruppen in der Organisation und Entitäten außerhalb der Organisation hinaus, unterliegen einige Organisationen außerdem folgenden Anforderungen an die Messagingrichtlinien:
  
- Verhindern, dass unangemessene Inhalte in die Organisation gelangen oder diese verlassen
    
- Filtern von vertraulichen Organisationsinformationen
    
- Nachverfolgen oder Kopieren von Nachrichten, die von bestimmten Einzelpersonen gesendet oder empfangen werden
    
- Umleiten von eingehenden und ausgehenden Nachrichten für die Untersuchung vor der Zustellung
    
- Hinzufügen von Haftungsausschlüssen zu Nachrichten während des Transports innerhalb der Organisation
    
> [!IMPORTANT]
> Anlagendateitypen, für die iFilter von Drittanbietern auf dem E-Mail-Server installiert werden müssen (z. B. Adobe PDF-Dateien), können erst nach der Installation eines geeigneten iFilters mithilfe von Nachrichtenflussregeln überprüft werden. Weitere Informationen zu Dateitypen, die von Nachrichtenflussregeln unterstützt werden, finden Sie unter [in Office 365 ](/exchange/security-and-compliance/mail-flow-rules/inspect-message-attachments).
  
Weitere Informationen zu Nachrichtenflussregeln finden Sie unter [Nachrichtenflussregeln in Exchange 2016](/Exchange/policy-and-compliance/mail-flow-rules/mail-flow-rules?preserve-view=true&view=exchserver-2019).
  
## <a name="data-loss-prevention"></a>Verhinderung von Datenverlust

Das Feature zur Verhinderung von Datenverlust (Data Loss Prevention, DLP) hilft Ihnen dabei, vertrauliche Informationen in Ihrer Organisation über eine eingehende Inhaltsanalyse zu identifizieren, zu überwachen und zu schützen. DLP ist ein Premium-Feature, dessen Bedeutung für Nachrichtensysteme von Unternehmen ständig zunimmt, da geschäftskritische E-Mails vertrauliche Daten enthalten, die geschützt werden müssen. Mit dem DLP-Feature in Exchange Online können Sie vertrauliche Daten schützen, ohne die Produktivität der Mitarbeiter zu beeinträchtigen.
  
Sie können DLP-Richtlinien in der Verwaltungsschnittstelle der Exchange-Verwaltungskonsole konfigurieren, die Ihnen Folgendes ermöglicht: 
  
- Beginnen Sie mit einer vorkonfigurierten Richtlinienvorlage, mit deren Hilfe Sie bestimmte Typen vertraulicher Informationen wie PCI DSS-Daten (Payment Card Industry Data Security Standard), Gramm-Leach-Bliley Act-Daten oder sogar standortspezifisch personenbezogene Informationen (PII) erkennen können.
    
- Nutzen Sie die volle Leistungsfähigkeit vorhandener Transportregelkriterien und -aktionen, und fügen Sie neue Transportregeln hinzu.
    
- Testen Sie die Effektivität Ihrer DLP-Richtlinien vor deren vollständiger Erzwingung.
    
- Integrieren Sie eigene benutzerdefinierte DLP-Richtlinienvorlagen und Typen vertraulicher Informationen.
    
- Erkennen Sie vertrauliche Informationen in E-Mail-Anlagen, -Text oder -Betreffzeilen, und passen Sie die Vertrauensstufe an, bei der Exchange Online Maßnahmen ergreift.
    
- Erkennen Sie vertrauliche Formulardaten mithilfe von Dokumentfingerabdrücken. Dokumentfingerabdrücke helfen Ihnen, problemlos benutzerdefinierte Typen vertraulicher Informationen auf Basis textbasierter Formulare zu erstellen, die Sie zum Definieren von Transportregeln und DLP-Richtlinien verwenden können.
    
- Fügen Sie Richtlinientipps hinzu, die dazu beitragen können, Datenverluste zu reduzieren, indem Sie Ihren Benutzern in Outlook 2016, Outlook 2013, Outlook im Web und OWA für Geräte eine Benachrichtigung anzeigen und die Effektivität Ihrer Richtlinien verbessern, indem falsch positive Berichte ermöglicht werden. 
    
- Überprüfen Sie Vorfallsdaten in DLP-Berichten, oder fügen Sie Ihre eigene Berichterstellung mithilfe einer neuen Aktion zum Generieren eines Schadensberichts hinzu.
    
Weitere Informationen zu DLP finden Sie unter [Verhinderung von Datenverlust](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).
  
## <a name="journaling"></a>Journaling

Sie können Exchange Online so konfigurieren, dass Kopien von E-Mails in Journalen beliebiger externer Postfächer erfasst werden, die Nachrichten über SMTP erhalten können. Mithilfe der Aufzeichnung eingehender und ausgehender E-Mail-Kommunikation in Journalen kann Ihre Organisation rechtlichen, regulatorischen und organisatorischen Auflagen genügen. Bei der Planung von Nachrichtenaufbewahrung und Richtlinientreue ist es wichtig zu wissen, was Journaling ist und wie es in die Konformitätsrichtlinien Ihrer Organisation passt.
  
Sie können die Journalregeln über die Exchange-Verwaltungskonsole oder über Windows PowerShell-Remotesitzungen verwalten. Journaling kann auf Benutzerbasis oder basierend auf der Verteilerliste konfiguriert werden. Sie können auswählen, ob nur interne Nachrichten, nur externe Nachrichten oder sowohl interne als externe Nachrichten in einem Journal erfasst werden. Journalnachrichten enthalten nicht nur die ursprüngliche Nachricht, sondern auch Informationen über den Absender, Empfänger, Kopien und Bcc.
  
Wenn Sie eine erfolgreiche und zuverlässige Journalinglösung sicherstellen möchten, müssen Sie die folgenden Aufgaben ausführen:
  
- Stellen Sie sicher, dass das Journalingziel kein Exchange Online-Postfach ist.
    
- Erstellen Sie in einem Kundenverzeichnis ein Kontaktobjekt für die SMTP-Ziel-E-Mail-Adresse, die für das Journaling verwendet wird.
    
- Erstellen Sie ein zweites Kontaktobjekt als alternatives Journalpostfach, in dem sämtliche Journalberichte erfasst werden, wenn das primäre Journalpostfach nicht verfügbar ist.
    
- Sorgen Sie für die Aufrechterhaltung der richtigen Verwaltungs-, Redundanz-, Verfügbarkeits- und Leistungsebenen des SMTP-Ziels, um die erfolgreiche E-Mail-Akzeptanz immer sicherzustellen.
    
- Stellen Sie die entsprechende Interoperabilität mit Exchange-Server und Exchange-Transport bereit, einschließlich Nachrichtenformate, der Integration von Absender-/Empfängerinformationen und angemessener Inhaltskonvertierung.
    
Weitere Informationen zum Journaling finden Sie unter [Journaling](/exchange/security-and-compliance/journaling/journaling).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
