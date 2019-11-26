---
title: Clients und mobile Geräte
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-clients-and-mobile-devices
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: fce4ac03-f30a-4152-9145-4a9ce564c966
ms.openlocfilehash: 0a94e61fb7721861df57c72bb52f71b25848ba85
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262758"
---
# <a name="clients-and-mobile-devices"></a>Clients und mobile Geräte

## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook ist ein E-Mail-Programm, das Unterstützung für Kalender, Kontakte, Aufgaben und die folgenden Hauptfunktionen bietet:
  
- **MAPI über HTTP** MAPI (Messaging Application Program Interface) über HTTP ermöglicht Outlook-Benutzern das Herstellen einer Verbindung mit Exchange Online Postfächern über das Internet außerhalb der Firewall Ihrer Organisation. MAPI-über-HTTP ist der langfristige Ersatz für Outlook Anywhere. Diese Verbindungsmethode bietet verbesserte Verbindungsstabilität, eine sicherere Anmeldung, Erweiterbarkeit sowie Verbesserungen für IT und Support. Weitere Informationen hierzu finden Sie unter [RPC-über-HTTP-Unterstützung in Office 365 wird beendet](https://go.microsoft.com/fwlink/?linkid=863890) und [MAPI-über-HTTP](https://go.microsoft.com/fwlink/?linkid=393041).

- **AutoErmittlung** Die Funktion des AutoErmittlungsdiensts konfiguriert Outlook automatisch für die Zusammenarbeit mit Exchange Online. Outlook-Benutzer können ihre erforderlichen Profileinstellungen direkt von Exchange Online erhalten, sobald sie sich erstmals mit ihrer E-Mail-Adresse und ihrem Kennwort anmelden. Diese Einstellungen aktualisieren den Outlook-Client automatisch mit den Informationen, die zum Erstellen und Warten des Benutzerprofils erforderlich sind. Für die Verwendung des AutoErmittlungsdiensts wird ein SSL-Zertifikat benötigt. Dieses SSL-Zertifikat ist auf eine einzelne primäre SSL-Domäne beschränkt. 

- **Exchange-Cache-Modus** Das Feature für den Exchange-Cache-Modus ermöglicht Outlook-Benutzern den Zugriff auf lokale Kopien Ihrer Exchange Online Postfächer, wenn Sie nicht mit dem Internet verbunden sind. Der Exchange-Cache-Modus behält eine clientseitige Kopie der Exchange-Benutzerpostfächer in Outlook bei und synchronisiert diese Kopie automatisch mit dem E-Mail-Server. Es empfiehlt sich, Outlook im Exchange-Cache-Modus zu verwenden, da auf diese Weise Offlinezugriff bereitgestellt und auch dann Reaktionsfähigkeit ermöglicht wird, wenn zwischen dem Client und dem Server keine idealen die Netzwerkbedingungen bestehen. 

Outlook-Zugriff ist standardmäßig für alle Benutzer aktiviert. Über Windows PowerShell können Administratoren den Zugriff für bestimmte Benutzer oder Gruppen deaktivieren. Es empfiehlt sich, die neueste Version von Outlook - mit Installation des neuesten Service Packs - für den Zugriff auf Exchange Online zu verwenden. 
  
Informationen zu den in Exchange 2016 und Exchange Online unterstützten Outlook-Clients finden Sie im Abschnitt „Unterstützte Clients" unter [Exchange 2016 - Systemanforderungen](https://go.microsoft.com/fwlink/?LinkID=828972).
  
> [!IMPORTANT]
>  Outlook ist nicht im Exchange Online-Bezugspreis enthalten. Microsoft Office Pro Plus (welches Microsoft Outlook umfasst) ist in manchen Office 365-Plänen enthalten und kann als separates Abonnement erworben werden. Die folgenden Einschränkungen werden angezeigt, wenn Sie mit Pop eine Verbindung mit einem Exchange Online e-Mail-Konto herstellen: #a0 keine Kalenderinformationen #a1 keine Frei/Gebucht-Informationen #a2 keine globale Adressliste #a3 keine Push-e-Mail-> beim Verbinden über Pop werden alle Nachrichten auf den Client heruntergeladen, und es wird keine Synchronisierung zwischen mehreren Computern oder Geräten (beispielsweise zwischen einem Laptop und einem Telefon 
  
## <a name="outlook-on-the-web"></a>Outlook im Web

Outlook im Web ist eine webbasierte Version des Outlook-E-Mail-Programms, die mit Exchange Online verwendet wird. Benutzer können auf Ihre e-Mails, Kalender und Kontakte über einen Webbrowser zugreifen, unabhängig davon, wo Sie mit dem Internet verbunden sind. Informationen zu unterstützten Browsern finden Sie im Artikel zu [unterstützten Browsern für Outlook im Web für Unternehmen](https://support.office.com/article/Supported-browsers-for-Outlook-Web-App-c89774d6-0722-4c93-a547-ef45e693e006).
  
Outlook im Web ist in zwei Clientversionen erhältlich, die beide mit Exchange Online verwendet werden können:
  
- **Outlook im Internet** Die Standard Version von Outlook im Internet bietet Exchange Online Benutzern mit einer Messagingumgebung am ähnlichsten wie Outlook-Benutzern. Es unterstützt die meisten neueren Webbrowser und ist für die Verwendung auf Tablets und Smartphones sowie Desktops und Laptops optimiert. Benutzer können Nachrichten lesen und senden, Kontakte organisieren und Termine und Besprechungen planen. Das standardmäßige aktivitätsbasierte Timeout wird auf sechs Stunden festgelegt, kann aber [von einem Administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) von 5 Minuten auf 8 Stunden konfiguriert werden. Dieses Timeout hängt von den Benutzerinteraktionen innerhalb der Webanwendung ab, beispielsweise auswählen einer Schaltfläche oder Auswählen einer Nachricht. Es gibt auch ein separates Sicherheits gesteuertes Timeout, das nicht konfigurierbar ist und unabhängig von der Benutzeraktivität stattfindet. Wenn ein Benutzer 8 Stunden lang angemeldet ist, meldet OWA den Benutzer automatisch ab und fragt erneut, ob er erneut authentifiziert werden soll. 

- **Die Light-Version von Outlook im Internet** Die Light-Version von Outlook im Internet bietet Exchange Online Benutzern den Zugriff auf das Postfach mit nahezu jedem Webbrowser. Benutzer können Nachrichten lesen und senden, Kontakte organisieren und Termine und Besprechungen planen. Das standardmäßige aktivitätsbasierte Timeout wird auf sechs Stunden festgelegt, kann aber [von einem Administrator in Windows PowerShell](https://go.microsoft.com/fwlink/p/?LinkId=399155) von 5 Minuten auf 8 Stunden konfiguriert werden. Dieses Timeout hängt von den Benutzerinteraktionen innerhalb der Webanwendung ab, beispielsweise auswählen einer Schaltfläche oder Auswählen einer Nachricht. Es gibt auch ein separates Sicherheits gesteuertes Timeout, das nicht konfigurierbar ist und unabhängig von der Benutzeraktivität stattfindet. Wenn ein Benutzer 8 Stunden lang angemeldet ist, meldet die Light-Version von OWA den Benutzer automatisch ab und fragt nach der erneuten Authentifizierung. 

Outlook im Web ist auch in mobilen Versionen verfügbar. Weitere Informationen finden Sie auf [dieser Seite](https://go.microsoft.com/fwlink/?LinkID=785184&amp;clcid=0x409).
  
## <a name="outlook-for-mac"></a>Outlook für Mac

Exchange Online unterstützt Microsoft Outlook für Mac, das E-Mail, Kalender, Adressbuch, Aufgabenliste und Notizliste bietet.
  
## <a name="outlook-for-ios-android-and-windows-phone"></a>Outlook für iOS, Android und Windows Phone.

Exchange Online ist kompatibel mit Outlook-Apps für iOS, Android und Windows Phone. Auf jedem dieser Geräte finden Sie die Outlook-App im App-Store. Nachfolgend finden Sie eine Auflistung nach Betriebssystem.
  
|||||
|:-----|:-----|:-----|:-----|
|Gerät  <br/> |Android  <br/> |iOS  <br/> |Windows Phone  <br/> |
|Verfügbarkeit der mobilen Outlook-App  <br/> |Ja  <br/> [Abrufen von Outlook für Android](https://go.microsoft.com/fwlink/?linkid=863380) <br/> |Ja  <br/> [Abrufen von Outlook für iOS](https://go.microsoft.com/fwlink/?linkid=863382) <br/> |Integriert  <br/> |
|Integrierte, mit Exchange Online kompatible E-Mail-Apps  <br/> |Gmail-App/Samsung E-Mail-App  <br/> |iOS-Mail-App  <br/> |Outlook-Mail, Kalender, Kontakte  <br/> |
|Weitere Informationen  <br/> |[Android-Setup für mobile Geräte](https://go.microsoft.com/fwlink/?linkid=525632) <br/> |[iPhone- oder iPad-Setup](https://go.microsoft.com/fwlink/?linkid=396655) <br/> |[Windows Phone-Setup](https://go.microsoft.com/fwlink/?linkid=831342) <br/> |

Exchange Online kann auch mit Geräten wie einem Blackberry verwendet werden.
  
### <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Outlook bietet Benutzern ein schnelles und intuitives E-Mail- und Kalender-Erlebnis, wie man es von einer modernen mobilen App erwartet, und ist dabei die einzige App, die die besten Features von Office 365 unterstützt. Outlook ist die einzige E-Mail-App, die speziell für das gesamte Office 365-Erlebnis entwickelt wurde, und bietet Benutzern ein einheitliches Erlebnis vom Desktop bis zum mobilen Gerät. Outlook bietet Intune, Enterprise Mobility + Security und Exchange-Steuerelemente, um Daten und Benutzer zu schützen.
  
In Outlook können Benutzer Folgendes tun:
  
- Verwalten Sie Ihren gesamten Tagesablauf über ein mobiles Gerät.

- Verbinden Sie sich mit den Apps und Diensten, die Sie benötigen, um produktiv zu sein, während Sie Ihre Arbeit und persönliche Informationen separat und sicher aufbewahren.

Mit Outlook für iOS, Outlook für Android oder Outlook für Windows Phone können Benutzer:  
  
- Profitieren Sie von einem Posteingang mit Fokus, der wichtige E-Mails priorisiert.

- Passen Sie Ihre Fingereingabefuktionen entsprechend Ihrer individuellen E-Mail-Gewohnheiten an.

- Erstellen Sie Reisepläne mit übersichtlichen Schlüsselinformationen, die Sie direkt über den Kalender bearbeiten können.

- Antworten Sie in Besprechungen direkt über den Posteingang.

- Verwenden Sie intuitive Symbole in E-Mail- und Kalenderterminen, damit diese Informationen schnell verarbeitet werden.

- Nutzen Sie ein konsistentes und vertrautes Outlook-Erlebnis auf allen Geräten.

- Starten Sie ganz einfach Skype-Besprechungen über den Kalender und nehmen Sie daran teil.

- Lesen und beantworten Sie IRM-verschlüsselte und geschützte E-Mails.

- Geben Sie Dateien frei, die in OneDrive for Business gespeichert sind.

- Legen Sie automatische Antworten durch Tippen fest.

- Zeigen Sie delegierte Kalender an und geben Sie diese frei.

- Durchsuchen Sie die globale Adressliste Ihres Unternehmens mit wenigen Klicks.

- Zeigen Sie die Verfügbarkeit eines Mitarbeiters an und planen Sie eine Besprechungszeit, die allen zusagt.

- Zeigen Sie Statusinformationen wie Annehmen, Mit Vorbehalt oder Ablehnen der eingeladenen Personen an.

- Geben Sie Kalender direkt über Ihr Smartphone frei.

- Starten Sie Skype-Besprechungen direkt über den Kalender und nehmen Sie daran teil.

- Greifen Sie an einem zentralen Ort auf persönliche Kalender zu, ohne Apps zu wechseln.
    
## <a name="exchange-activesync"></a>Exchange ActiveSync

Exchange Online unterstützt das Microsoft Exchange ActiveSync-Protokoll, welches Postfachdaten zwischen mobilen Geräten und Exchange Online synchronisiert, damit Benutzer auch unterwegs auf E-Mail, Kalendar, Kontakte und Aufgaben zugreifen können.
  
Eine große Auswahl mobiler Geräte kann mit Exchange ActiveSync eingesetzt werden, einschließlich Microsoft Windows Phone, Apple iPhone und iPad sowie Android-Telefone und -Tablets. Außer von Mobiltelefonen und mobilen Geräten wird ActiveSync von der E-Mail-Anwendung in Windows Phone zum Herstellen einer Verbindung mit Exchange Online verwendet. Eine vollständige Liste aktueller Exchange ActiveSync-Lizenznehmer steht auf der Exchange ActiveSync-Lizenzierungswebsite zur Verfügung.
  
Weitere Informationen zu Exchange ActiveSync finden Sie im Thema [Exchange ActiveSync](https://go.microsoft.com/fwlink/p/?LinkId=271792).
  
> [!IMPORTANT]
> Es können maximal 100 Exchange ActiveSync-Geräte pro Postfach verwendet werden. 
  
## <a name="applications-developed-with-exchange-web-services-ews"></a>Mit Exchange-Webdiensten (Exchange Web Services, EWS) entwickelte Anwendungen

 Durch Anwendungen, die mit Exchange-Webdiensten oder der Exchange-Webdienste-MAPI entwickelt wurden, können Administratoren auf mit Exchange Online gespeicherte Daten aus Anwendungen zugreifen, die lokal, in Azure oder in anderen gehosteten Diensten ausgeführt werden. 
  
Weitere Informationen zu Anwendungen, die mit Exchange-Webdiensten entwickelt wurden, finden Sie im Artikel zum Thema [Webdienste in Exchange](https://go.microsoft.com/fwlink/?LinkId=325346).
  
## <a name="pop-and-imap"></a>POP und IMAP

Exchange Online unterstützt den Postfachzugriff über die Protokolle POP3 und IMAP4. Für den POP- und IMAP-Zugriff ist eine Verschlüsselung über SSL erforderlich. POP ist standardmäßig für alle Benutzer aktiviert. Benutzer können ihre POP- und IMAP-Verbindungseinstellungen in Outlook im Web anzeigen. Administratoren können den POP- und IMAP-Zugriff für einzelne Benutzer deaktivieren.
  
Weitere Informationen zu POP3- und IMAP4-Verbindungen finden Sie im Thema [POP3 und IMAP4](https://go.microsoft.com/fwlink/p/?LinkId=272070).
  
## <a name="smtp"></a>SMTP

Das Simple Mail Transfer Protocol (SMTP) wird zum Senden ausgehender E-Mails für Clients verwendet, die über IMAP oder POP eine Verbindung mit Exchange Online herstellen. Es ist das primäre Protokoll für das Weiterleiten und Zustellen über Exchange Server. Exchange Online unterstützt zwei Arten von SMTP-Relaydiensten für autorisierte interne Kundenanwendungen, die eine E-Mail-Übermittlung über SMTP erfordern:
  
- SMTP-Nachrichtenübermittlung an Benutzer innerhalb der verwalteten Umgebung.

- Authentifiziertes SMTP-Nachrichtenrelay an Adressen außerhalb der verwalteten Umgebung.

> [!IMPORTANT]
> IP-Adressen für autorisierte Quellserver müssen SMTP-Relay erlauben. TLS-Verschlüsselung (Transport Layer Security) und Authentifizierung sind erforderlich, wenn SMTP zum Senden von E-Mail verwendet wird. 
  
## <a name="blackberry-devices"></a>BlackBerry®-Geräte

Office 365-E-Mail steht auf BlackBerry®-Geräten über Exchange ActiveSync zur Verfügung. Die verfügbaren Optionen finden Sie in den folgenden Themen:
  
- [Einrichten von E-Mails auf einem BlackBerry](https://go.microsoft.com/fwlink/?linkid=863394).

- [Einrichten von E-Mails auf einem BlackBerry-Gerät mit BS 7.1 oder einer früheren Version](https://go.microsoft.com/fwlink/?linkid=863403).

Weitere Informationen finden Sie unter [BlackBerry](../office-365-platform-service-description/blackberry.md).
  
> [!NOTE]
> Bei Verwendung von Office 365 betrieben von 21Vianet, ist BlackBerry Business Cloud Services nicht verfügbar, Sie können jedoch Exchange ActiveSync-Geräte oder ein Angebot von Research in Motion (RIM, drahtlose E-Mail-Lösung von Blackberry) verwenden, um Blackberry Enterprise Server (BES) auszuführen. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  