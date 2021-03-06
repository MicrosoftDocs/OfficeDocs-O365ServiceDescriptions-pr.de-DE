---
title: Empfänger
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-recipients
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: da22b03a-c981-49c6-9928-4312c2c5e2ee
description: In diesem Thema werden die empfängerbezogenen Features von Microsoft Exchange Online beschrieben. Dazu gehören E-Mail, Kontakte, Verteilergruppen sowie Kalender- und Terminplanungsfunktionen.
ms.openlocfilehash: 5771fd11a51ecfb8bff2b1be8a86dd3d87a51f81
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653307"
---
# <a name="recipients"></a>Empfänger

In diesem Thema werden die empfängerbezogenen Features von Microsoft Exchange Online beschrieben. Dazu gehören E-Mail, Kontakte, Verteilergruppen sowie Kalender- und Terminplanungsfunktionen.
  
## <a name="email"></a>E-Mails

Jeder Microsoft Exchange Online-Abonnent erhält ein Postfach; für die Planung von Einrichtungsressourcen (wie Konferenzräume) und für den Zugriff mehrerer Benutzer auf gemeinsam genutzte E-Mail-Adressen stehen Spezialpostfächer zur Verfügung. Für die meisten Postfächer gelten obere Speichergrenzwerte, und Administratoren können die zulässigen Postfachgrößen steuern. Automatisierte Benachrichtigungen und Beschränkungen können Benutzer warnen, wenn ihre Postfächer sich der maximalen Kapazität annähern oder sie erreichen. Exchange Online verfügt auch über verschiedene Arten an Nachrichtenbeschränkungen – Grenzwerte für Nachrichtengröße, Nachrichtenrate und Empfängerliste. Informationen über alle diese Funktionen und Grenzwerte werden nachfolgend angegeben.
  
> [!NOTE]
> Catch-All-Adressen werden in Exchange Online nicht mehr unterstützt. Aufgrund der vorhandenen Empfängerfilterung zum Schutz vor potenziellen Spamnachrichten werden E-Mail-Adressen, die in Ihrer Organisation nicht vorhanden sind, abgelehnt. 
  
### <a name="mailbox-types-storage-limits-and-capacity-alerts"></a>Mailbox-Typen, Speicherbegrenzungen und Kapazitätswarnungen

Die Größe des verfügbaren Postfachspeichers für einen Benutzer und die Standardpostfachgröße werden durch den Postfachtyp sowie die Abonnementlizenz des Benutzers bestimmt. Administratoren können die maximale Postfachgröße pro Benutzer oder global reduzieren. Exchange Online bietet drei Arten von Benachrichtigungen, wenn das Postfach eines Benutzers seine Kapazität fast oder vollständig erreicht hat:
  
Weitere Informationen finden Sie in den Abschnitten "Postfachspeicherbeschränkungen" und "Kapazitätswarnungen" im Thema Exchange Online [Grenzwerte](exchange-online-limits.md).
  
### <a name="mailtips"></a>MailTips

E-Mail-Infos sind automatisierte, informative Nachrichten, die über der Zeile "An:" angezeigt werden, während Benutzer Nachrichten verfassen oder adressieren. Sie dienen dazu, eine unbeabsichtigte Zustellung, Richtlinienverletzungen oder unnötige Unzustellbarkeitsberichte zu verhindern. E-Mail-Infos können beispielsweise einen Alarm generieren, wenn Absender versuchen, Nachrichten an zu große Gruppen, an Gruppen mit externen Empfängern oder an eine moderierte oder gesperrte Verteilergruppe zu senden. Weitere Informationen finden Sie im Artikel zum Thema [E-Mail-Infos](/exchange/clients-and-mobile-in-exchange-online/mailtips/mailtips).
  
### <a name="delegate-access"></a>Stellvertretungszugriff

Exchange Online unterstützt den Stellvertretungszugriff– die Möglichkeit für Benutzer, anderen die Verwaltung ihrer E-Mails und Kalender zu ermöglichen. Der Stellvertretungszugriff wird häufig zwischen einem Vorgesetzten und einem Assistenten verwendet, wobei der Assistent die eingehenden E-Mail-Nachrichten des Managers verarbeitet und den Zeitplan des Managers koordiniert. Der Stellvertretungszugriff kann von Exchange Online Benutzern in Outlook oder Outlook im Web oder von Administratoren im Exchange Admin Center aktiviert werden. 
  
Stellvertreter können zwei Arten von Zugriff haben:
  
- **Berechtigung "Senden im Auftrag von"** Der Stellvertreter kann E-Mail-Nachrichten verfassen und den Namen der anderen Person in das Feld "Von" eingeben, wo er als "[Name des Stellvertreters] im Auftrag von [Name der Person]" angezeigt wird. 
    
- **Berechtigung "Senden als"** Der Stellvertreter kann Nachrichten vom Postfach der anderen Person senden, so als sei er der Inhaber des Postfachs. Dieses Szenario kommt häufig dann zum Einsatz, wenn ein gemeinsam genutztes Postfach vorliegt und mehrere Mitarbeiter E-Mail-Nachrichten von diesem Postfach aus senden, anstatt von ihren eigenen Exchange Online-Konten. 
    
Weitere Informationen zu Zugriffsrechten finden Sie unter [Verwalten von Berechtigungen für Empfänger](/Exchange/recipients/mailbox-permissions).
  
### <a name="inbox-rules"></a>Posteingangsregeln

Exchange Online ermöglicht es Benutzern, Posteingangsregeln zu erstellen, die automatisch spezifische, kriteriumsbasierte Aktionen beim Eingang von Nachrichten ausführen. Sie können beispielsweise eine Regel erstellen, um automatisch alle E-Mails in einen bestimmten Ordner zu verschieben, wenn die Mail an eine bestimmte Verteilergruppe gesendet wurde. Benutzer verwalten Posteingangsregeln von Outlook oder Outlook im Web. Administratoren können bestimmte Typen von Posteingangsregeln blockieren, indem sie die serverseitige Weiterleitung und/oder serverseitige automatische Antworten deaktivieren. Wenn beispielsweise die serverseitige E-Mail-Weiterleitung deaktiviert ist, kann dies die Benutzer daran hindern, automatisch E-Mails an persönliche Konten weiterzuleiten. Gleichermaßen gilt, dass, wenn die serverseitigen automatischen Antworten deaktiviert sind, dies verhindern kann, dass außenstehende Parteien diese Antworten dazu nutzen, um gültige E-Mail-Adresse zu identifizieren. Diese Änderungen werden über die remote Windows PowerShell vorgenommen.
  
### <a name="clutter"></a>Unwichtige Elemente

Die Funktion "Unwichtige Elemente" soll Ihnen helfen, sich auf die wichtigsten Nachrichten in Ihrem Posteingang zu konzentrieren. Sie verschiebt durch maschinelles Lernen Nachrichten mit niedriger Priorität in Ihrem Posteingang in einen neuen Ordner namens "Unwichtige Elemente". Dabei werden Ihre vorhandenen E-Mail-Regeln berücksichtigt. Wenn Sie also Regeln zum Organisieren Ihrer E-Mails festgelegt haben, gelten diese Regeln weiterhin, und die betreffenden Nachrichten werden durch "Unwichtige Elemente" nicht beeinflusst. "Unwichtige Elemente" ist für Ihren Posteingang standardmäßig deaktiviert. Weitere Informationen finden Sie im englischsprachigen Blogbeitrag [De-clutter your inbox in Office 365](https://go.microsoft.com/fwlink/?linkid=2144145).
  
### <a name="connected-accounts"></a>Verbundene Konten

Mit dem Feature Verbundene Konten können Exchange Online Benutzer externe E-Mail-Konten (z. B. persönliche Konten) mit ihren internen E-Mail-Konten in Exchange Online verbinden und dann Outlook im Web verwenden, um mit allen nachrichten an einem Ort zu interagieren. Verbundene Konten werden bei der Anmeldung automatisch mit Outlook im Web synchronisiert. Benutzer können die Konten auch manuell aus Outlook im Web synchronisieren. Administratoren können dieses Feature für bestimmte Benutzer oder alle Benutzer über das Exchange [aktivieren und deaktivieren.](/exchange/exchange-admin-center)
  
### <a name="inactive-mailboxes"></a>Inaktive Postfächer

Exchange Online enthält eine Funktion, mit der Inhalte gelöschter Postfächer für unbegrenzte Zeit beibehalten werden können. Dieses Feature heißt inaktive Postfächer. Ein Postfach wird deaktiviert, wenn es vor seiner Löschung in einem Compliance-Archiv platziert oder ein Beweissicherungsverfahren für das Postfach aktiviert wird. Dies führt dazu, dass die Inhalte des Postfachs für unbegrenzte Zeit beibehalten werden. Administratoren, Compliance Officers oder Datensatzmanager können das Compliance-eDiscovery-Feature in Exchange Online verwenden, um auf die Inhalte eines inaktiven Postfachs zuzugreifen.
  
Damit ein inaktives Postfach aktiviert werden kann, muss dem Postfach eine Exchange Online-Lizenz (Plan 2) zugewiesen werden, oder es muss ein Abonnement für die Exchange Online-Archivierung vorhanden sein, sodass das Postfach in einem Compliance-Archiv platziert oder ein Beweissicherungsverfahren für das Postfach aktiviert werden kann, bevor es gelöscht wird.
  
> [!IMPORTANT]
> Wenn vor dem Löschen des Postfachs diesem kein Compliance-Archiv zugeordnet wird, werden die Inhalte des Postfachs nicht beibehalten bzw. können diese nicht gefunden werden. Das Postfach kann innerhalb von 30 Tagen nach dem Löschen wiederhergestellt werden; wird es nicht innerhalb von 30 Tagen wiederhergestellt, wird das Postfach samt Inhalten unwiderruflich gelöscht. 
  
Weitere Informationen finden Sie unter:
  
- [Verwalten inaktiver Postfächer in Exchange Online](/microsoft-365/security/office-365-security/exchange-online-protection-overview)
    
- [In-Situ-Speicher und Beweissicherungsverfahren](/exchange/security-and-compliance/in-place-and-litigation-holds)
    
- [Compliance-eDiscovery](/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery)
    
## <a name="contacts-and-distribution-groups"></a>Kontakte und Verteilergruppen

### <a name="offline-address-book"></a>Offlineadressbuch

Das Offlineadressbuchfeature stellt eine Momentaufnahme der Active Directory-Informationen bereit, die in der Outlook Globale Adressliste (GAL) verfügbar sind. Sie werden lokal in Outlook zwischengespeichert, um sie bei der Offlinearbeit verfügbar zu machen.
  
### <a name="address-book-policies"></a>Adressbuchrichtlinien

Exchange Online unterstützt Adressbuchrichtlinien. Adressbuchrichtlinien ermöglichen Ihnen die Einteilung von Benutzern in bestimmte Gruppen, um benutzerdefinierte Ansichten der globalen Adressliste Ihrer Organisation bereitzustellen. Bei der Erstellung einer ABP weisen Sie der Richtlinie eine globale Adressliste (GAL), ein Offlineadressbuch (OAB), eine Raumliste und eine oder mehrere Adresslisten zu. Anschließend können Sie den Postfachbenutzern den APS zuweisen und ihnen Zugriff auf eine angepasste GAL in Outlook und Outlook im Web bieten. Administratoren können über Windows PowerShell-Remotesitzungen Adressbuchrichtlinien konfigurieren. Weitere Informationen zu Adressbuchrichtlinien finden Sie unter [Adressbücher in Exchange Online](/exchange/address-books/address-books).
  
### <a name="address-lists"></a>Adresslisten

Exchange Online unterstützt die Anpassung von Adresslisten und GALs. Eine GAL ist ein organisationsweites Verzeichnis aller E-Mail-aktivierten Benutzer, Verteilergruppen und externen Kontakte. Administratoren können Benutzer, Verteilergruppen und Kontakte über das Verzeichnissynchronisierungstool oder remote Windows PowerShell.
  
### <a name="hierarchical-address-books"></a>Hierarchische Adressbücher

 Hierarchische Adressbücher ermöglichen es Endbenutzern, in ihrer Exchange-Organisation über eine Organisationshierarchie nach Empfängern zu suchen. Administratoren können das Adressbuch nach Rang statt von A–Z sortieren. 
  
### <a name="distribution-groups-global"></a>Verteilergruppen (global)

Eine Verteilergruppe (oder Verteilerliste) ist eine Sammlung von Benutzern, Kontakten und anderen Verteilergruppen, die allen Benutzern in einem Unternehmen zur Verfügung steht. Benutzer richten eine E-Mail an ein Verteilergruppen-Alias, um Nachrichten an alle Personen in der Gruppe zu senden. Verteilergruppen ähneln persönlichen Verteilergruppen, die einzelne Benutzer in Outlook erstellen, allerdings sind ihre Mitgliederlisten global für das Unternehmen verfügbar. Administratoren erstellen Verteilergruppen in der Exchange-Verwaltungskonsole. Die Gruppen können auch aus dem lokalen Active Directory mit Exchange Online synchronisiert werden. Sie werden in der GAL in Outlook. Exchange Online unterstützt erweiterte Verteilergruppenfunktionen, darunter auch die nachfolgend beschriebenen:
  
- **Eingeschränkte Verteilergruppen** Standardmäßig kann jeder E-Mails an eine beliebige Verteilergruppe senden. Administratoren können Berechtigungen ändern, um es nur bestimmten Personen zu erlauben, E-Mails an eine bestimmte Gruppe zu senden, um z. B. den unangemessenen Gebrauch großer Verteilerlisten zu vermeiden. Administratoren können auch externe Quellen blockieren, sodass sie keine E-Mails an Verteilergruppen senden können, um den Versand von Junk-E-Mails zu verhindern. Bei Verteilergruppen, die mit dem Tool zur Verzeichnissynchronisierung aus dem lokalen Active Directory synchronisiert wurden, werden die Einschränkungsattribute automatisch mit der Cloud synchronisiert. Weitere Informationen finden Sie unter [Verwalten von Verteilergruppen](/Exchange/recipients/distribution-groups).
    
- **Dynamische Verteilergruppen** Die Mitgliedschaftsliste für eine dynamische Verteilergruppe (auch bekannt als dynamische Verteilerliste oder abfragebasierte Verteilerliste) wird bei jedem Senden einer Nachricht an die Gruppe berechnet. Diese Berechnung basiert auf vom Administrator definierten Filtern und Bedingungen. Sie wird in Exchange Online über die remote Windows-PowerShell verwaltet. Weitere Informationen zu dynamischen Verteilergruppen finden Sie unter [Verwalten dynamischer Verteilergruppen](/Exchange/recipients/dynamic-distribution-groups/dynamic-distribution-groups).
    
    > [!IMPORTANT]
    > Das Office 365-Tool zur Verzeichnissynchronisierung ignoriert dynamische Verteilergruppen im lokalen Active Directory und führt keine Synchronisierung mit Exchange Online durch. Organisationen, die das Tool zur Verzeichnissynchronisierung nutzen, sollten eine Benennungskonvention verwenden, mit der Konflikte zwischen den normalen Verteilergruppen, die lokal verwaltet werden, und den dynamischen Verteilergruppen, die in Exchange Online verwaltet werden, vermieden werden. 
  
- **Moderierte Verteilergruppen** Administratoren können einen Moderator bestimmen, der den Nachrichtenfluss für eine Verteilergruppe reguliert. Bei moderierten Verteilergruppen kann jeder eine E-Mail an das Verteilergruppen-Alias senden; bevor jedoch die Nachricht an die Mitglieder der Gruppe zugestellt werden, muss ein Moderator sie überprüfen und genehmigen. Weitere Informationen zur Moderation finden Sie im Abschnitt „Nachrichtengenehmigung" unter [Verwalten von Verteilergruppen](/Exchange/recipients/distribution-groups).
    
- **Self-Service-Verteilergruppen** Administratoren können es Benutzern gestatten, ihre eigene Mitgliedschaft in Verteilergruppen über eine webbasierte Oberfläche zu verwalten. Benutzern können die Berechtigungen gewährt werden, um Verteilergruppen zu erstellen, zu löschen, um ihnen beizutreten oder um aus ihnen auszutreten. Diese Funktionen sind standardmäßig für alle Benutzer von Exchange Online aktiviert. Administratoren können sie bei Bedarf deaktivieren, sodass nur die IT-Abteilung Verteilergruppen verwalten kann. Sie können auch Richtlinien für Benennungskonventionen erstellen, um die Namen von Verteilergruppen, die ihre Benutzer erstellen, zu standardisieren und zu verwalten. Sie können beim Erstellen des Verteilergruppennamens beispielsweise ein bestimmtes Präfix oder Suffix hinzufügen oder bestimmte Wörter für den Gruppennamen blockieren. 
    
    > [!IMPORTANT]
    > Self-Service-Funktionen stehen nicht für Verteilergruppen zur Verfügung, die von dem lokalen Active Directory mit Exchange Online synchronisiert werden. Organisationen, die das Tool zur Verzeichnissynchronisierung nutzen, sollten eine Benennungskonvention verwenden, mit der Konflikte zwischen Verteilergruppen, die lokal verwaltet werden, und den Verteilergruppen, die in der Cloud verwaltet werden, vermieden werden. 
  
### <a name="external-contacts-global"></a>Externe Kontakte (global)

Ein externer Kontakt ist ein Datensatz mit Informationen zu einer Person, die außerhalb einer bestimmten Organisation arbeitet. Externe Kontakte ähneln persönlichen Kontakten, die einzelne Benutzer in Outlook erstellen, allerdings sind sie global für das Unternehmen verfügbar. Administratoren können externe Kontakte mit der Exchange-Verwaltungskonsole oder über Windows PowerShell-Remotesitzungen erstellen. Diese Kontakte können auch aus dem lokalen Active Directory mit Exchange Online synchronisiert werden. Sie werden in der GAL in Outlook.
  
Weitere Informationen zu externen Kontakten finden Sie unter [Erstellen einer Organisationsbeziehung in Exchange Online](/exchange/sharing/organization-relationships/create-an-organization-relationship).
  
## <a name="calendar-and-scheduling"></a>Kalender und Terminplanung

### <a name="resource-mailboxes"></a>Ressourcenpostfächer

Ressourcenpostfächer (z. B. für Konferenzräume und physische Geräte) stellen die Besprechungsräume oder andere Einrichtungen oder Ressourcen eines Unternehmens dar. Benutzer können Räume oder Ressourcen reservieren, indem sie den E-Mail-Alias der Ressource besprechungsanfragen in Outlook oder Outlook im Web hinzufügen. Konferenzräume und Ressourcen werden in der GAL in Outlook und Outlook im Web angezeigt.
  
Administratoren erstellen Ressourcenpostfächer mithilfe der Exchange-Verwaltungskonsole oder über Windows PowerShell-Remotesitzungen. Die Postfächer können auch aus dem lokalen Active Directory mit Exchange Online synchronisiert werden.
  
Weitere Informationen zu Ressourcenpostfächern finden Sie unter:
  
- [Erstellen und Verwalten von Raumpostfächern](/Exchange/recipients/room-mailboxes)
    
- [Verwalten von Gerätepostfächern](/Exchange/recipients/equipment-mailboxes)
    
### <a name="conference-room-management"></a>Konferenzraumverwaltung

Exchange Online umfasst eine Ressourcenbuchungsautomatik (RBA), mit der die Planung von Konferenzräumen und anderen Ressourcen automatisiert wird. Ein Ressourcenpostfach das mit der RBA konfiguriert wurde, akzeptiert oder bestätigt basierend auf der Kalenderverfügbarkeit der Ressource Besprechungsanfragen von einem Besprechungsorganisator oder lehnt sie ab. 
  
Administratoren können automatisierte Konferenzraumantworten anpassen und Buchungsrichtlinien in Outlook Web konfigurieren. Diese Richtlinien beinhalten, wer die Ressource planen kann, wann sie eingeplant werden kann, welche Besprechungsinformationen im Kalender der Ressource angezeigt werden sowie den Prozentsatz der zulässigen Planungskonflikte. Administratoren können die Ressourcenbuchungsautomatik deaktivieren und bestimmte Benutzer zuweisen, um die Besprechungsanfragen für Konferenzräume manuell zu verwalten.
  
Administratoren müssen die RBA-Einstellungen über die remote Windows-PowerShell definieren und verwalten.
  
### <a name="out-of-office-replies"></a>Abwesenheitsantworten

Abwesenheitsnachrichten sind automatische Antworten auf eingehende Nachrichten, die Exchange Online im Auftrag eines Benutzers sendet. Benutzer können Abwesenheitsnachrichten vorab mit genauen Start- und Endzeiten planen und separate Abwesenheitsnachrichten für interne und externe Empfänger konfigurieren. Sie können Abwesenheitsnachrichten auch über Mobilgeräte einrichten, die diese Exchange ActiveSync-Funktion unterstützen. Informationen zu Junk-E-Mails und Mailing-Listen in Exchange Online verhindern, dass Benutzer externe Abwesenheitsnachrichten an erweiterte Mailing-Listen und potenzielle Junk-E-Mail-Absender senden. Administratoren können Benutzer auch daran hindern, Abwesenheitsnachrichten an externe Benutzer mit der remoten Windows PowerShell zu senden.
  
### <a name="calendar-sharing"></a>Kalenderfreigabe

Benutzer können ihre persönlichen Kalender auf zwei Arten freigeben:
  
- **Verbundfreigabe für Kalender** Verbund bezieht sich auf die zugrunde liegende Vertrauensstellungsinfrastruktur, die die Verbundfreigabe unterstützt, eine einfache Methode für Exchange-Benutzer, die Frei/Gebucht-Daten im Kalender und Kontaktinformationen für Empfänger in anderen externen Verbundorganisationen freigeben möchten. Dazu gehören Exchange Online-Organisationen oder Organisationen, die Exchange Server 2010 oder Exchange Server 2013 lokal ausführen. Exchange Online Administratoren müssen keine Vertrauensstellung mit dem Microsoft Federation Gateway einrichten, da diese Vertrauensstellung für alle Exchange Online vorkonfiguriert ist, wenn der Microsoft-Dienst erstellt wird. Eine Standardfreigaberichtlinie ermöglicht Benutzern das Senden von Kalenderfreigabeeinladungen von Outlook im Web oder Outlook 2010. Administratoren verwenden die remote Windows PowerShell, um diese Richtlinie zu deaktivieren oder um den Umfang an Frei/Gebucht-Daten im Kalender zu konfigurieren, die Benutzer freigeben können. Administratoren können auch eine Beziehung von einer Organisation zu einer anderen mit einer anderen Verbundorganisation erstellen, sodass der gewünschte Umfang an Frei/Gebucht-Informationen für alle Benutzer organisationsübergreifend sichtbar ist, ohne dass einzelne Benutzer eine Freigabeeinladung senden müssen. Innerhalb der vom Administrator definierten Freigaberichtlinien und/oder Organisation-zu-Organisation-Beziehungen können Benutzer den Umfang ihrer Freigabe weiter gezielt einschränken. 
    
- **Kalenderfreigabe im Internet** Exchange Online ermöglicht es den Benutzern, ihre Kalender im iCal-Format für einen anonymen Zugriff von Benutzern innerhalb oder außerhalb der Organisation zu veröffentlichen. Empfänger können Exchange, eine andere Plattform oder einfach einen Webbrowser verwenden. Exchange Online benutzer können auch Kalender abonnieren, die andere über iCal an Internetstandorten veröffentlicht haben. Diese Freigabe von persönlichen Kalendern unterscheidet sich von der Verbundfreigabe für Kalender, die von einem Administrator eingerichtet wird und die die Freigabe von Frei/Gebucht-Informationen zwischen Organisationen ermöglicht. Kein Benutzer kann Kalenderdaten im iCal-Format veröffentlichen, bis der Administrator eine Freigaberichtlinie festgelegt und angewendet hat, die dies zulässt. Administratoren können die iCal-Veröffentlichung und iCal-Abonnements für Benutzer in einer Organisation mit der remoten Windows PowerShell deaktivieren.
    
Weitere Informationen zur Verbundfreigabe finden Sie unter [Freigabe in Exchange Online](/exchange/sharing/sharing).
  
### <a name="outlook-2010-room-finder"></a>Outlook 2010-Raumsuche

Exchange Online unterstützt die Raumsuchfunktion von Outlook 2010, mit der Räume in Listen angeordnet werden (z. B. eine Liste namens "Gebäude 5 Räume"), was die Suche nach einem nahe gelegenen Raum bei der Planung einer Besprechung erleichtert. Um in der Raumliste angezeigt zu werden, muss eine Verteilerliste speziell mit einer der beiden Methoden markiert werden: 
  
- Eine neue Raumliste kann mithilfe der remoten Windows PowerShell erstellt werden. 
    
- Jede Verteilergruppe, die nur Räume enthält, kann über die remote Windows PowerShell in eine Raumliste konvertiert werden.
    
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie [unter Exchange Online Service description](exchange-online-service-description.md).
