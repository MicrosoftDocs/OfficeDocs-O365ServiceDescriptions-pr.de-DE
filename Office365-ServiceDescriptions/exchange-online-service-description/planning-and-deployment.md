---
title: Planung und Bereitstellung
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
description: Erfahren Sie mehr über die Planung und Bereitstellung in Microsoft Exchange Online.
ms.openlocfilehash: eabef8014f64295058b4f41ccd9835a8dea473d8
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652699"
---
# <a name="planning-and-deployment"></a>Planung und Bereitstellung

## <a name="planning-for-service-changes-and-growth"></a>Planung von Dienständerungen und Wachstum

Organisationen sollten die Migrationsoptionen basierend auf den Quell-E-Mail-Systemen, dem gewünschten Endzustand (vollständig oder teilweise gehostet), der Anzahl von zu migrierenden Benutzern sowie basierend darauf auswählen, wie schnell der gewünschte Endzustand erreicht werden soll.
  
## <a name="deployment-options"></a>Bereitstellungsoptionen

- **Nur-Cloud-Bereitstellung:** In Ihrer Organisation werden alle Benutzerpostfächer in Exchange Online. 
    
- **Exchange Hybridbereitstellung:** Ihre Organisation verfügt über einige Benutzerpostfächer, die in einer lokalen Exchange-Organisation gehostet werden, und einige Benutzerpostfächer, die in einer Exchange Online. 
    
### <a name="cloud-only"></a>Rein cloudbasiert

Bei einer reinen Cloudbereitstellung ist Ihre Organisation im Exchange Online-Dienst nicht mit einer lokalen Exchange-Organisation verbunden. Sämtliche Benutzer und Postfächer werden in Exchange Online und Office 365 gehostet.
  
### <a name="hybrid"></a>Hybrid

Eine Hybridbereitstellung steht für lokale Microsoft Exchange 2003-, Exchange 2007-, Exchange 2010- und Exchange 2013-Organisationen zur Verfügung und stellt entweder eine langfristige Koexistenzkonfiguration mit einigen Postfächern bereit, bei denen einige Postfächer lokal und andere in Exchange Online gehostet werden, oder die Hybridbereitstellung bietet einen Migrationspfad zum Hosten aller Benutzerpostfächer in Exchange Online. Eine Hybridbereitstellung bietet Unternehmen die Möglichkeit, den Funktionsreichtum und die Verwaltungskontrolle, die die vorhandene, lokale Microsoft Exchange-Organisation bietet, auf die Cloud auszudehnen. Zu den Funktionen einer Hybridbereitstellung gehören der sichere E-Mail-Transport, gemeinsam genutzte Frei/Gebucht-Kalenderinformationen sowie eine Nachrichtenverfolgung zwischen den lokalen und den Exchange Online-Organisationen.
  
Weitere Informationen zu Hybridbereitstellungen finden Sie im Artikel zum Thema [Hybridbereitstellungen in Exchange Server 2013](/exchange/exchange-hybrid). Wenn Sie Office 365 über 21Vianet nutzen, lesen Sie [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> In einer lokalen Exchange 2003-Organisation muss mindestens ein Exchange 2010-Clientzugriffs-/Postfachserver installiert werden, um eine Hybridbereitstellung mit Exchange Online zu konfigurieren. In einer lokalen Exchange 2007-Organisation muss mindestens ein Exchange 2010- oder Exchange 2013-Clientzugriffs- und -Postfachserver installiert werden, um eine Hybridbereitstellung mit Exchange Online zu konfigurieren. Lokale Exchange 2010- und Exchange 2013-Organisationen bieten systemeigene Unterstützung für Hybridbereitstellungen mit Exchange Online. Weitere Informationen zur Exchange-Serverkompatibilität in Hybridbereitstellungen finden Sie unter [Voraussetzungen für die Hybridbereitstellung](/exchange/hybrid-deployment-prerequisites). > Lokale Exchange-Organisationen müssen ihre Organisation für eine Hybridbereitstellung konfigurieren. Es wird dringend empfohlen, dass Administratoren den Bereitstellungs-Assistenten für Exchange Server und den Assistenten für Hybridkonfigurationen nutzen, um die Hybridbereitstellung zu konfigurieren. Weitere Informationen finden Sie unter [Bereitstellungs-Assistent für Exchange Server](/exchange/exchange-deployment-assistant).
  
## <a name="migration-options"></a>Migrationsoptionen

Organisationen sollten die Migrationsoptionen basierend auf den Quell-E-Mail-Systemen, dem gewünschten Endzustand (vollständig oder teilweise gehostet), der Anzahl von zu migrierenden Benutzern sowie basierend darauf auswählen, wie schnell der gewünschte Endzustand erreicht werden soll. Zu den möglichen Migrationsoptionen gehören:
  
- **IMAP-Migration** : Migrieren Sie Postfachdaten von IMAP-basierten E-Mail-Systemen zu Exchange Online. 
    
- **Cutover Exchange Migration** : Migrieren Sie Postfächer aus Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 und Hosted Exchange-Systemen zu Exchange Online in einer einzigen Cutovermigration. 
    
- Mehrstufige **Exchange** Migration: Führen Sie eine mehrstufige Migration durch, um Postfächer aus Exchange Server 2003 oder Exchange Server 2007 mit webbasierten Migrationstools und minimalen Änderungen an der lokalen Infrastruktur zu migrieren. 
    
- **Remotemigration :** Migrieren Sie lokale Exchange Postfächer zu Exchange Online in einer Exchange Hybridbereitstellung. Für die Verwendung einer Remoteverschiebungsmigration müssen Sie über eine Exchange-Hybridbereitstellung verfügen. 
    
Weitere Informationen zum Migrieren von E-Mails und Postfächern zu Exchange Online finden Sie unter [Migrieren von Postfächern zu Exchange Online](https://support.office.com/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>IMAP-Migration

Exchange Online stellt ein webbasiertes Tool für die Migration von Postfachdaten von E-Mail-Systemen bereit, die IMAP unterstützen. Das Tool leitet Administratoren durch die folgenden Migrationsschritte: 
  
1. Erstellen von leeren Postfächern in der Cloud für Benutzer in der Organisation (typischerweise geschieht dies durch Hochladen einer CSV-Datei oder durch Verwendung von Windows PowerShell).
    
2. Eingeben der Einstellungen für die Remoteserververbindung.
    
3. Verwendung einer CSV-Datei zum Angeben der Postfächer, deren Daten zu Exchange Online-Postfächern migriert werden.
    
4. Nach Eingabe dieser Informationen beginnt Exchange Online mit der Migration der Postfachinhalte über IMAP (Kalenderelemente, Kontakte, Aufgaben und weitere, nicht E-Mail-bezogene Elemente werden nicht migriert).
    
Weitere Informationen zur IMAP-Migration finden Sie unter [Migrieren von E-Mails von einem IMAP-Server zu Exchange Online-Postfächern](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) und [Migrieren anderer Typen von IMAP-Postfächern](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Exchange Online baut weniger als 10 Verbindungen mit dem IMAP-Server auf, um eine Überlastung von Ressourcen und Bandbreite des Remoteservers zu vermeiden. 
  
### <a name="cutover-exchange-migration"></a>Exchange-Übernahmemigration

Exchange Online stellt ein webbasiertes Tool für die Migration von Daten von lokalen Exchange Server 2003-, Exchange Server 2007- oder Exchange Server 2010-Umgebungen bereit. Administratoren werden durch die folgenden Migrationsschritte geleitet:
  
1. Unter Verwendung der E-Mail-Adresse und der Anmeldedaten für ein lokales Administratorkonto stellt Exchange Online über den AutoErmittlungsdienst eine Verbindung mit der lokalen E-Mail-Organisation her.
    
2. Exchange Online verwendet eine RPC/HTTP-Verbindung, um Verzeichnisinformationen vom Remoteserver zu lesen und Postfächer in Exchange Online zu erstellen.
    
3. Exchange Online synchronisiert die Inhalte des Postfachs mit den Cloudpostfächern. Benutzer bleiben mit ihren ursprünglichen Postfächern verbunden, während die Daten zu Exchange Online migriert werden.
    
4. Nach Abschluss der anfänglichen Migration werden Änderungen alle 24 Stunden mit der Cloud synchronisiert, bis der Administrator den Migrationsbatch anhält oder löscht.
    
Um Benutzer zu ihren Cloudpostfächern zu wechseln, konfigurieren Administratoren ihren MX-Eintrag so, dass er auf Microsoft verweisen kann, und konfigurieren die Benutzerprofile in Outlook. Wenn Benutzer auf ihre Cloudpostfächer wechseln, werden ihre lokalen Offlineordner (OST-Dateien) erneut synchronisiert, was dazu führt, dass migrierte E-Mails auf die Clientarbeitsstation heruntergeladen werden. Benutzer können nach der Migration auf alte Nachrichten in ihren Postfächern antworten.
  
Weitere Informationen zu einer Exchange-Übernahmemigration finden Sie unter [Wichtige Informationen zur E-Mail-Übernahmemigration zu Office 365](https://support.office.com/article/365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> Eine Organisation kann mit einer Exchange-Übernahmemigration maximal 2.000 Exchange 2003-, Exchange 2007-, Exchange 2010- oder Exchange 2013-Postfächer zur Cloud migrieren. > Exchange Online muss sich mit einem lokalen Exchange Server verbinden, deshalb muss der lokale Server über ein Zertifikat verfügen, dass von einer vertrauenswürdigen Zertifizierungsstelle ausgegeben wurde und über eine öffentliche IP-Adresse verfügt. 
  
### <a name="staged-exchange-migration"></a>Phasenweise Exchange-Migration

Bei einer phasenweisen Migration können Benutzer unter Verwendung des webbasierten Exchange-Migrationstools und dem Tool für die Verzeichnissynchronisierung zur Cloud migriert werden. Statt alle Benutzer in einem Schritt zu migrieren, wie bei der Exchange-Übernahmemigration, können Administratoren Benutzer in Gruppen migrieren. Dies wird erreicht, indem eine CSV-Datei zur Festlegung einer Teilmenge der Benutzer für die Migration hochgeladen wird. Bei einer phasenweisen Migration können alle Benutzer in einer Organisation denselben E-Mail-Domänennamen verwenden.
  
Zur Durchführung einer phasenweisen Exchange-Migration müssen Administratoren das Microsoft Online Services-Verzeichnissynchronisierungstool verwenden. Das Tool stellt Benutzern eine einheitliche globale Adressliste (Global Address List, GAL) bereit, wobei die Onlineumgebung fortlaufend mit der lokalen Umgebung synchronisiert wird.
  
Weitere Informationen zu mehrstufigen Exchange-Migrationen finden Sie unter [Wichtige Informationen zur mehrstufigen E-Mail-Migration zu Office 365](https://support.office.com/en-ie/article/365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Organisationen können eine mehrstufige Exchange-Migration nicht zur Migration von Exchange 2010- und Exchange 2013-Postfächern verwenden. Wenn sich weniger als 2.000 Exchange 2010- oder Exchange 2013-Postfächer in der Organisation befinden, können Sie eine Exchange-Übernahmemigration verwenden. Wenn sich mehr als 2.000 Exchange 2010- oder Exchange 2013-Postfächer in der Organisation befinden, können Sie eine Hybridbereitstellung implementieren. > Während der Migration müssen Administratoren das Microsoft Online Services-Verzeichnissynchronisierungstool verwenden, um für die Benutzer eine einheitliche globale Adressliste bereitzustellen. Es wird eine fortlaufende Synchronisierung mit der lokalen Umgebung durchgeführt. 
  
## <a name="migration-tools"></a>Migrationstools

Microsoft stellt verschiedene Tools zur Migration einer vorhandenen E-Mail-Umgebung zu Exchange Online bereit. Welches Migrationstool für eine Organisation am besten geeignet ist, richtet sich nach der aktuellen Umgebung und den Bereitstellungszielen:
  
- **Migrationsdashboard** – Administratoren können das Migrationsdashboard im Exchange Admin Center verwenden, um die Postfachmigration zu Exchange Online in einer überschneidenen oder mehrstufigen Migration Exchange verwalten. Administratoren können das Dashboard auch einsetzen, um die Inhalte von Benutzerpostfächern von einem lokalen IMAP-Server zu vorhandenen Exchange Online-Postfächern zu migrieren. Das Dashboard bietet Administratoren die folgenden Funktionen: 
    
  - **Erstellen und Starten mehrerer Migrationsbatches** – Administratoren können bis zu 100 Migrationsbatches erstellen und in eine Warteschlange stellen. Es wird jeweils nur ein Migrationsbatch ausgeführt, aber Administratoren können mehrere Batches in die Warteschlange einreihen, sodass nach Abschluss der Ausführung eines Migrationsbatches der nächste Batch in der Warteschlange gestartet wird. 
    
  - Neustarten eines Migrationsbatches mit Fehlern **–** Nach der anfänglichen Synchronisierung für einen Migrationsbatch, bei der Elemente aus lokalen Postfächern in die Cloudpostfächer für jeden Benutzer im Migrationsbatch kopiert werden, können einige Postfächer die Synchronisierung nicht mehr durchführen. Administratoren können diesen Migrationsbatch neu starten, um die Postfächer, bei denen Fehler aufgetreten sind, erneut zu synchronisieren. 
    
  - Details zu übersprungenen Elementen **erhalten:** Für IMAP-Migrationen, Zuschnittmigrationen und mehrstufige Migrationen zeigt das Migrationsdashboard Informationen zu den bestimmten Elementen an, die übersprungen wurden, einschließlich des Grunds und des Orts, an dem sich das Element im Postfach des Benutzers befindet. 
    
  - **Öffnen von Migrationsberichten** : Administratoren können Migrationsstatistiken oder den Migrationsfehlerbericht für einen Migrationsbatch direkt aus dem Dashboard öffnen. 
    
  - **Bearbeiten eines** Migrationsbatches : Wenn sich ein Migrationsbatch für eine mehrstufige migration Exchange oder eine IMAP-Migration in der Migrationswarteschlange befindet, aber derzeit nicht ausgeführt wird, können Administratoren den Migrationsbatch bearbeiten. 
    
- **Azure Active Directory** Synchronisierungstool : Das Azure Active Directory-Synchronisierungstool spielt eine wichtige Rolle bei der Migration zu hybriden E-Mail-Szenarien, die sowohl Exchange Online als auch eine lokale Exchange Server. Das Tool führt eine einseitige Synchronisierung vom lokalen Active Directory-Verzeichnis zu Exchange Online durch. Nach Abschluss der Migration benötigen Administratoren nur Exchange Online, um Active Directory-Benutzer und -Gruppen zu verwalten. Das Tool stellt Benutzern außerdem eine einheitliche globale Adressliste (Global Address List, GAL) zur Verfügung, wobei die Onlineumgebung fortlaufend mit der lokalen Umgebung synchronisiert wird. 
    
    Weitere Informationen zum Azure Active Directory-Synchronisierungstool finden Sie in der [Roadmap Verzeichnissynchronisierung](/azure/active-directory/hybrid/whatis-hybrid-identity).
    
- **Assistent für** die Hybridkonfiguration – Der Assistent für die Hybridkonfiguration optimiert den Hybridbereitstellungsprozess, indem die lokale und Exchange Online von Features und Diensten vereinfacht wird. Der Im Rahmen von Exchange Server 2010 Service Pack 2 eingeführte Assistent für die Hybridkonfiguration wird nur in lokalen Organisationen ausgeführt und verfügt über die folgenden Komponenten: 
    
  - Einen Assistenten für die Exchange-Verwaltungskonsole, der Administratoren durch die gesamte Konfiguration einer Hybridbereitstellung leitet.
    
  - Einen Satz Befehle für die Exchange-Verwaltungsshell zur Abstimmung des Konfigurationsprozesses.
    
    Weitere Informationen zum Assistenten für die Hybridkonfiguration finden Sie unter [Assistent für die Hybridkonfiguration](/exchange/hybrid-configuration-wizard).
    
- **Remote Windows PowerShell** : Im Rahmen des Exchange Online 2011 Service Update können Remote-Windows PowerShell zur Problembehandlung von Migrationsfehlern verwendet werden. Beispielsweise können Administratoren Diagnoseinformationen für Migrationsbatches sowie Migrationsstatistiken anzeigen sowie basierend auf ihren primären SMTP-Adressen Diagnoseinformationen für Benutzer abrufen. 
    
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie [unter Exchange Online Dienstbeschreibung](exchange-online-service-description.md).
