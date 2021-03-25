---
title: Dienststatus und Verfügbarkeit
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft-Administratoren können den Status der Dienste anzeigen und herausfinden, wann Die Wartung geplant ist. Dienstinte health information is at any time by signing in.
ms.openlocfilehash: ea9beb020d2f868eb51638c4729924a7ac873b7b
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51174140"
---
# <a name="service-health-and-continuity"></a>Dienststatus und Verfügbarkeit

Microsoft-Administratoren können den Status der Dienste anzeigen und herausfinden, wann Die Wartung geplant ist. Dienstinte health information is at any time by signing in.
  
> [!NOTE]
> Bei Verwendung von Office 365, betrieben von 21Vianet, treffen einige unten aufgeführten Informationen möglicherweise nicht zu. Lesen Sie stattdessen die [Vereinbarung zum Servicelevel von 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Anzeigen des Status von Diensten

Im Abschnitt Dienstintestatus werden der aktuelle Status des Diensts und Details zu Dienstunterbrechungen und -ausbrüchen angezeigt. Informationen zu geplanten Wartungszeiten stehen im Nachrichtencenter zur Verfügung. Weitere Informationen finden Sie unter [Dienststatus anzeigen](/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Dienstincidents

Ein Dienstincident (auch als Servicevorfall bezeichnet) ist ein Ereignis, das die Bereitstellung eines Diensts beeinträchtigt. Dienstincidents können durch Hardware- oder Softwarefehler im Microsoft-Rechenzentrum, eine fehlerhafte Netzwerkverbindung zwischen dem Kunden und Microsoft oder ein größeres Problem im Rechenzentrum wie Feuer, Überschwemmung oder eine regionale Naturkatastrophe verursacht werden. Die meisten Dienstincidents können mit Technologie- und Prozesslösungen von Microsoft behandelt werden, und sie werden in kurzer Zeit gelöst. Einige Dienstincidents sind jedoch schwerwiegender und können zu längeren Ausfällen führen.
  
Es gibt zwei Arten von Benachrichtigungen über Zeiten, zu denen Dienste möglicherweise nicht zur Verfügung stehen:
  
- **Geplante Wartungsereignisse:** Die geplante Wartung umfasst regelmäßige von Microsoft gestartete Dienstupdates an der Infrastruktur und den Softwareanwendungen. Geplante Wartungsbenachrichtigungen informieren Kunden über Dienstarbeiten, die sich auf die Funktionalität eines Microsoft-Diensts auswirken können. Kunden werden nicht später als fünf Tage im Voraus über das Message Center im Microsoft 365 Admin Center über die geplante Wartung benachrichtigt. Microsoft plant die Wartung normalerweise für Zeiten ein, zu denen die Dienstnutzung üblicherweise am geringsten ist, basierend auf regionalen Zeitzonen. 
    
- **Ungeplante Ausfallzeiten:** Ungeplante Dienstvorfälle treten auf, wenn einer der Dienste nicht verfügbar oder nicht reagiert. 

### <a name="recent-worldwide-uptimes"></a>Aktuelle weltweite Uptimes

Der Wechsel zu einem Clouddienst sollte nicht bedeuten, dass die Fähigkeit verloren geht, zu wissen, was los ist. Bei Office 365 nicht. Wir möchten in unseren Vorgängen transparent sein, damit Sie den Status Ihres Diensts überwachen, Probleme nachverfolgen und einen historischen Überblick über die Verfügbarkeit haben können. In den folgenden Tabellen sind aktuelle Daten zur weltweiten Uptime dargestellt.

**2020**

| F1 | F2 | Q3 | F4 |
|:-----|:-----|:-----|:-----|
| 99.98% <br/> | 99,99 %<br/> | 99.97%<br/> | 99.97%<br/> |

<br>

**2019**

| F1 | F2 | Q3 | F4 |
|:-----|:-----|:-----|:-----|
| 99.97% <br/> | 99.97% <br/> | 99.98% <br/> | 99.98% <br/> |

<br>

**2018**

| F1 | F2 | Q3 | F4 |
|:-----|:-----|:-----|:-----|
| 99,99 % <br/> | 99.98% <br/> | 99.97% <br/> | 99.98% <br/> |

<br>

**2017**

| F1 | F2 | Q3 | F4 |
|:-----|:-----|:-----|:-----|
| 99,99 % <br/> | 99.97% <br/> | 99.98% <br/> | 99,99 % <br/> |

## <a name="notification-policy"></a>Benachrichtigungsrichtlinie

Microsoft ist sich bewusst, dass im Fall eines Dienstincidents zeitnahe, zielgerichtete und genaue Informationen für die Kunden entscheidend sind. Microsoft benachrichtigt Administratoren, indem es das mandantenspezifische Dienstinteschashboard (Service Health Dashboard, SHD) im Microsoft 365 Admin Center aktualisiert. Dienstincidentupdates werden stündlich bereitgestellt oder, wenn ein anderes Intervall erforderlich ist, in einer SHD-Kommunikationsveröffentlichung bekanntgegeben. 
  
## <a name="service-health-communication-channels"></a>Kommunikationskanäle für den Dienstinte health

### <a name="admin-app"></a>Administrator-App

Mit der Admin App für Organisationsadministratoren können Sie unterwegs eine Verbindung mit dem Microsoft-Dienststatus Ihrer Organisation herstellen. Microsoft-Administratoren können Dienststatusinformationen und Wartungsstatusupdates von ihren mobilen Geräten anzeigen. Weitere Informationen finden Sie unter „Häufig gestellte Fragen zur Admin-App“[Admin-App FAQ](/office365/admin/admin-overview/admin-mobile-app).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Office 365 Management Pack für Microsoft System Center 2012 R2

Microsoft System Center ist eine integrierte Verwaltungsplattform, die Ihnen hilft, Ihr Rechenzentrum, Ihre Clientgeräte und Hybrid Cloud-IT-Umgebungen zu verwalten. Microsoft-Administratoren, die System Center verwenden, haben jetzt die Möglichkeit, das Office 365 Management Pack zu importieren, mit dem sie die gesamte Dienstkommunikation im Operations Manager im System Center anzeigen können. Dieses Tool ermöglicht den Zugriff auf den Status Ihrer abonnierten Dienste, aktive und abgeschlossene Dienstereignisse sowie die Message Center-Kommunikation. Weitere Informationen finden Sie unter [Microsoft System Center Management Pack für Office 365](https://www.microsoft.com/download/details.aspx?id=43708) im Microsoft Download Center. 
  
### <a name="office-365-service-communications-api"></a>Office 365-Dienstkommunikations-API

Mit der Office 365 Service Communications-API können Sie auf die Dienstkommunikation zugreifen, wie Sie möchten. Mit dieser API haben Sie die Möglichkeit, Ihre Tools mit der Dienstkommunikation zu erstellen oder zu verbinden, was die Überwachung Ihrer Umgebung potenziell vereinfacht. Mit der Dienstkommunikations-API können Sie die folgenden Elemente in Ihrer Umgebung überwachen:
  
- Dienststatus in Echtzeit
    
- Message Center-Kommunikation
    
Weitere Informationen finden Sie unter [Office 365 Service Communications API reference](/office/office-365-management-api/office-365-service-communications-api-reference). 
  
## <a name="post-incident-reviews"></a>Bewertungen nach Vorfällen

Zur Verpflichtung von Microsoft für eine kontinuierliche Verbesserung gehört die Analyse ungeplanter Dienstvorfälle mit Auswirkungen auf die Kunden, um deren Auftreten in der Zukunft zu minimieren. 
  
Ungeplante Dienstvorfälle werden als Dienstunterbrechungen mit mehreren Mandanten definiert, die sich auf die Dienstnutzung auswirken, wie in unseren Vereinbarungen zum Servicelevel (Service Level Agreements, SLAs) definiert und im Service Health Dashboard als solche deklariert wurden.
  
 Bei ungeplanten Dienstincidents, die sich auf Kunden auswirken und zu einer merkbaren Beeinträchtigung über eine große Anzahl von Organisationen hinweg führten, wird eine vorläufige Vorfallnachsorgeüberprüfung (PIR, Post-Incident Review) innerhalb von 48 Stunden nach Lösung des Incidents über Ihr Dienststatus-Dashboard bereitgestellt, gefolgt von einer endgültigen PIR innerhalb von fünf Geschäftstagen. Der ausführliche PIR-Bericht enthält Folgendes: 
  
- Benutzererfahrung und Kundenauswirkungen
    
- Start- und Enddatum/-zeit des Incidents
    
- Detaillierte Zeitachse der Auswirkungen und Lösungsmaßnahmen
    
- Ursachenanalyse und Maßnahmen zur kontinuierlichen Verbesserung
    
Bei allen anderen Dienstincidents stellt das Service Health Dashboard eine Zusammenfassung der Incidentlösung einschließlich einer entgültigen Zusammenfassung des Ereignisses, einer vorläufigen Ursache, Anfangs- und Enzeiten sowie detaillierte Informationen zu den nächsten Schritten bereit. Für diese Kategorie von Dienstincidents wird keine PIR generiert. 
  
## <a name="service-continuity"></a>Service continuity

Microsoft-Angebote werden von besonders ausfallsicheren Systemen angeboten, die dazu beitragen, die Leistung des Diensts auf hohem Stand zu halten. Dienstkontinuitätsbestimmungen sind Teil des Systementwurfs. Diese Bestimmungen ermöglichen Microsoft die schnelle Wiederherstellung von unerwarteten Ereignissen wie Hardware- oder Anwendungsfehlern, Datenbeschädigungen oder anderen Vorfällen, die Sich auf Benutzer auswirken. Diese Lösungen für die Dienstverfügbarkeit gelten auch bei schwerwiegenden Ausfällen (wie Naturkatastrophen oder einem Incident in einem Microsoft-Rechenzentrum, durch den das gesamte Rechenzentrum nicht mehr funktionsfähig ist).
  
Nach der Wiederherstellung nach einem schwerwiegenden Ausfall dauert es eine gewisse Zeit, bis die vollständige Rechenzentrumsredundanz für den Dienst wiederhergestellt ist. Beispiel: Wenn Rechenzentrum 1 ausfällt, werden die Dienste durch Ressourcen in Rechenzentrum 2 wiederhergestellt. Allerdings kann es u. U. eine gewisse Zeit dauern, bis die Dienste in Rechenzentrum 2 unterbrechungsfrei ausgeführt werden, sei es durch wiederhergestellte Ressourcen in Rechenzentrum 1 oder neue Ressourcen in Rechenzentrum 3. Der Microsoft [Service Level Agreement](service-level-agreement.md) (SLA) gilt während dieser Zeit. Office 365, betrieben von 21Vianet, verfügt über eine andere SLA. Weitere Informationen finden Sie auf der [21Vianet-Website](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Sicherstellen der Datenverfügbarkeit

Mit den folgenden Features stellt Microsoft sicher, dass Kundendaten immer zur Verfügung stehen, wenn sie benötigt werden:
  
- **Datenspeicherung und -redundanz:** Die Daten der Kunden werden in einer redundanten Umgebung mit zuverlässigen Datenschutzfunktionen gespeichert, um Verfügbarkeit, Geschäftskontinuität und schnelle Wiederherstellung zu ermöglichen. Mehrere Ebenen von Datenredundanz sind implementiert. Sie reichen von redundanten Datenträgern zum Schutz vor lokalen Datenträgerfehlern über die fortlaufende Replikation bis zu geografisch verteilten Rechenzentren. 
    
- **Datenüberwachung:** Microsoft-Dienste behalten ein hohes Leistungsniveau durch Überwachung bei: 
    
  - Datenbanken
    
  - Blockierte Prozesse
    
  - Paketverlust
    
  - Prozesse in der Warteschlange
    
  - Abfragewartezeit
    
- **Durchführung vorbeugender Wartung:** Die vorbeugende Wartung umfasst Überprüfungen der Datenbankkonsistenz, regelmäßige Datenkomprimierung und Überprüfungen der Fehlerprotokolle. 
    
## <a name="support"></a>Support

Die Entwicklungs- und Betriebsteams von Microsoft werden durch eine dedizierte Supportorganisation ergänzt, die eine wichtige Rolle bei der Bereitstellung von Geschäftskontinuität für Kunden spielt. Supportmitarbeiter haben ein tiefes Wissen über den Dienst und die zugehörigen Anwendungen sowie direkten Zugriff auf Microsoft-Experten in Architektur, Entwicklung und Tests.
  
Die Supportorganisation ist eng am Betrieb und der Produktentwicklung ausgerichtet, bietet Lösungen in kurzer Zeit und ermöglicht es den Kunden, ihre Meinung zu sagen. Feedback von Kunden leistet Beiträge zu Planungs-, Entwicklungs- und Betriebsprozessen.
  
- **Onlineverfolgung von Problemen:** Die Kunden müssen wissen, dass ihre Probleme behandelt werden, und sie müssen in der Lage sein, zeitnah die Lösung zu verfolgen. Das Microsoft 365 Admin Center bietet eine einzige webbasierte Benutzeroberfläche zur Unterstützung. Die Kunden können über das Portal Dienstanforderungen hinzufügen und überwachen und Feedback von Microsoft-Supportteams erhalten. 
    
- **Selbsthilfe, unterstützt durch kontinuierliche Unterstützung durch Mitarbeiter:** Microsoft bietet eine breite Palette von Selbsthilferessourcen und Tools, die Kunden dabei helfen können, dienstbezogene Probleme zu beheben, ohne microsoft support zu benötigen. 
    
Bevor Kunden Dienstanforderungen eingeben, können Sie auf Artikel der Knowledge Base und häufig gestellte Fragen zugreifen, die Hilfe bei den am häufigsten auftretenden Problemen bieten. Diese Ressourcen werden ständig mit aktuellen Informationen aktualisiert, sodass Verzögerungen bei Lösungen für bekannte Probleme vermieden werden. Wenn jedoch ein Problem auftritt, bei dem die Hilfe eines Supportmitarbeiters erforderlich ist, stehen entsprechende Mitarbeiter täglich rund um die Uhr für eine unmittelbare Unterstützung per Telefon und über das Verwaltungsportal zur Verfügung.
  
Weitere Informationen zum Support [](support.md) finden Sie im Support-Artikel. 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in allen Plänen finden Sie unter [Microsoft 365- und Office 365-Plattformdienstbeschreibung](office-365-platform-service-description.md).
