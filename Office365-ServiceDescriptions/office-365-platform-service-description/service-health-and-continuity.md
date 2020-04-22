---
title: Service health and continuity
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Microsoft-Administratoren können den Status von Diensten anzeigen und herausfinden, wann die Wartung geplant ist. Dienststatusinformationen sind jederzeit verfügbar, wenn Sie sich anmelden.
ms.openlocfilehash: 6ac04087599b2ddbe212a1f292b06b7d5b22a378
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/21/2020
ms.locfileid: "43640235"
---
# <a name="service-health-and-continuity"></a>Service health and continuity

Microsoft-Administratoren können den Status von Diensten anzeigen und herausfinden, wann die Wartung geplant ist. Dienststatusinformationen sind jederzeit verfügbar, wenn Sie sich anmelden.
  
> [!NOTE]
> Bei Verwendung von Office 365, betrieben von 21Vianet, treffen einige unten aufgeführten Informationen möglicherweise nicht zu. Lesen Sie stattdessen die [Vereinbarung zum Servicelevel von 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Anzeigen des Dienststatus

Im Abschnitt Dienst Integrität wird der aktuelle Status des Diensts sowie Details zu Dienstunterbrechungen und-Ausfällen angezeigt. Informationen zu geplanten Wartungszeiten stehen im Nachrichtencenter zur Verfügung. Weitere Informationen finden Sie unter [Dienststatus anzeigen](https://docs.microsoft.com/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Dienstincidents

Ein Dienstincident (auch als Servicevorfall bezeichnet) ist ein Ereignis, das die Bereitstellung eines Diensts beeinträchtigt. Dienstincidents können durch Hardware- oder Softwarefehler im Microsoft-Rechenzentrum, eine fehlerhafte Netzwerkverbindung zwischen dem Kunden und Microsoft oder ein größeres Problem im Rechenzentrum wie Feuer, Überschwemmung oder eine regionale Naturkatastrophe verursacht werden. Die meisten Dienstincidents können mit Technologie- und Prozesslösungen von Microsoft behandelt werden, und sie werden in kurzer Zeit gelöst. Einige Dienstincidents sind jedoch schwerwiegender und können zu längeren Ausfällen führen.
  
Es gibt zwei Arten von Benachrichtigungen über Zeiten, zu denen Dienste möglicherweise nicht zur Verfügung stehen:
  
- **Geplante Wartungsereignisse:** Die geplante Wartung umfasst regelmäßige von Microsoft gestartete Dienstupdates an der Infrastruktur und den Softwareanwendungen. Geplante wartungsbenachrichtigungen informieren Kunden über Dienst arbeiten, die sich möglicherweise auf die Funktionalität eines Microsoft-Diensts auswirken. Kunden werden spätestens fünf Tage vor der geplanten Wartung über das Nachrichtencenter im Microsoft 365 Admin Center benachrichtigt. Microsoft plant die Wartung normalerweise für Zeiten ein, zu denen die Dienstnutzung üblicherweise am geringsten ist, basierend auf regionalen Zeitzonen. 
    
- **Ungeplante Ausfallzeit:** Ungeplante Dienst Vorfälle treten auf, wenn einer der Dienste nicht verfügbar ist oder nicht mehr reagiert. 

### <a name="recent-worldwide-uptimes"></a>Aktuelle weltweiten UpTimes

Das Wechseln zu einem clouddienst sollte nicht bedeuten, die Möglichkeit zu verlieren, zu wissen, was vor sich geht. Bei Office 365 ist dies nicht der Fall. Unser Ziel ist es, in unseren Geschäftsabläufen transparent zu sein, damit Sie den Status Ihres Diensts überwachen, Probleme nachverfolgen und die Verfügbarkeit historisch betrachten können. In den folgenden Tabellen sind die letzten weltweiten Uptime-Daten aufgeführt.

<br/>

|**2019** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99,97% <br/> | 99,97% <br/> | 99,98% <br/> | 99,98% <br/> |

<br/>

|**2018** <br/>||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99,99 % <br/> | 99,98% <br/> | 99,97% <br/> | 99,98% <br/> |

<br/>

|**2017** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Q2** <br/> |**Q3** <br/> |**Q4** <br/> |
| 99,99 % <br/> | 99,97% <br/> | 99,98% <br/> | 99,99 % <br/> |

<br/>

## <a name="notification-policy"></a>Benachrichtigungsrichtlinie

Microsoft ist sich bewusst, dass im Fall eines Dienstincidents zeitnahe, zielgerichtete und genaue Informationen für die Kunden entscheidend sind. Microsoft benachrichtigt Administratoren durch die Aktualisierung des mandantenspezifischen Service Health Dashboards ("") im Microsoft 365 Admin Center. Dienstincidentupdates werden stündlich bereitgestellt oder, wenn ein anderes Intervall erforderlich ist, in einer SHD-Kommunikationsveröffentlichung bekanntgegeben. 
  
## <a name="service-health-communication-channels"></a>Dienstintegritäts-Kommunikationskanäle

### <a name="admin-app"></a>Admin-App

Die Administrator-App für Organisationsadministratoren gibt Ihnen die Möglichkeit, sich unterwegs mit dem Microsoft-Dienststatus Ihrer Organisation zu verbinden. Microsoft-Administratoren haben die Möglichkeit, Informationen zum Dienststatus und Wartungsstatus von ihren mobilen Geräten anzuzeigen. Weitere Informationen finden Sie unter „Häufig gestellte Fragen zur Admin-App“[Admin-App FAQ](https://docs.microsoft.com/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Office 365 Management Pack für Microsoft System Center 2012 R2

Microsoft System Center ist eine integrierte Verwaltungsplattform, die Ihnen hilft, Ihr Rechenzentrum, Ihre Clientgeräte und Hybrid Cloud-IT-Umgebungen zu verwalten. Microsoft-Administratoren, die System Center verwenden, haben jetzt die Möglichkeit, das Office 365 Management Pack zu importieren, mit dem Sie alle Dienst Kommunikationen in Operations Manager in System Center anzeigen können. Dieses Tool ermöglicht den Zugriff auf den Status Ihrer abonnierten Dienste, aktive und abgeschlossene Dienstereignisse sowie die Message Center-Kommunikation. Weitere Informationen finden Sie im Blogbeitrag [Neue Office 365-Verwaltungstools](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/). 
  
### <a name="office-365-service-communications-api"></a>Office 365-Dienstkommunikations-API

Mit dem Office 365-Dienstkommunikations-API können Sie auf die Dienst Kommunikation zugreifen, wie Sie möchten. Mit diesem neuen Verwaltungstool haben Sie nun die Möglichkeit, ihre Tools für die Dienst Kommunikation zu erstellen oder zu verbinden, wodurch die Überwachung Ihrer Umgebung möglicherweise vereinfacht wird. Mit der Dienst Kommunikations-API können Sie Folgendes in Ihrer Umgebung überwachen:
  
- Dienststatus in Echtzeit
    
- Message Center-Kommunikation
    
- Benachrichtigungen für geplante Wartungen
    
Weitere Informationen finden Sie im Blogbeitrag [neue Verwaltungstools](https://www.microsoft.com/en-us/microsoft-365/blog/2014/07/29/new-office-365-admin-tools/) . 
  
## <a name="post-incident-reviews"></a>Bewertungen nach Vorfällen

Zur Verpflichtung von Microsoft für eine kontinuierliche Verbesserung gehört die Analyse ungeplanter Dienstvorfälle mit Auswirkungen auf die Kunden, um deren Auftreten in der Zukunft zu minimieren. 
  
Ungeplante Dienstincidents sind als Dienstunterbrechungen mehrerer Mandanten definiert, die sich auf die Dienstverwendung, wie durch unsere Dienst-SLAs definiert, auswirken und vom Service Health Dashboard als solche deklariert wurden.
  
 Bei ungeplanten Dienstincidents, die sich auf Kunden auswirken und zu einer merkbaren Beeinträchtigung über eine große Anzahl von Organisationen hinweg führten, wird eine vorläufige Vorfallnachsorgeüberprüfung (PIR, Post-Incident Review) innerhalb von 48 Stunden nach Lösung des Incidents über Ihr Dienststatus-Dashboard bereitgestellt, gefolgt von einer endgültigen PIR innerhalb von fünf Geschäftstagen. Der ausführliche PIR-Bericht enthält Folgendes: 
  
- Benutzererfahrung und Kundenauswirkungen
    
- Start- und Enddatum/-zeit des Incidents
    
- Detaillierte Zeitachse der Auswirkungen und Lösungsmaßnahmen
    
- Ursachenanalyse und Maßnahmen zur kontinuierlichen Verbesserung
    
Bei allen anderen Dienstincidents stellt das Service Health Dashboard eine Zusammenfassung der Incidentlösung einschließlich einer entgültigen Zusammenfassung des Ereignisses, einer vorläufigen Ursache, Anfangs- und Enzeiten sowie detaillierte Informationen zu den nächsten Schritten bereit. Für diese Kategorie von Dienstincidents wird keine PIR generiert. 
  
## <a name="service-continuity"></a>Dienstverfügbarkeit

Microsoft-Angebote werden durch hoch belastbare Systeme bereitgestellt, mit denen die Leistung des Spitzen Diensts aufrecht erhalten werden kann. Service Continuity-bestimmungensind Bestandteil des Systemdesigns. Diese Bestimmungen ermöglichen Microsoft die schnelle Wiederherstellung vor unerwarteten Ereignissen wie Hardware-oder Anwendungsfehlern, Datenbeschädigungen oder anderen Vorfällen, die sich auf Benutzer auswirken. Diese Lösungen für die Dienstverfügbarkeit gelten auch bei schwerwiegenden Ausfällen (wie Naturkatastrophen oder einem Incident in einem Microsoft-Rechenzentrum, durch den das gesamte Rechenzentrum nicht mehr funktionsfähig ist).
  
Nach der Wiederherstellung nach einem schwerwiegenden Ausfall dauert es eine gewisse Zeit, bis die vollständige Rechenzentrumsredundanz für den Dienst wiederhergestellt ist. Beispiel: Wenn Rechenzentrum 1 ausfällt, werden die Dienste durch Ressourcen in Rechenzentrum 2 wiederhergestellt. Allerdings kann es u. U. eine gewisse Zeit dauern, bis die Dienste in Rechenzentrum 2 unterbrechungsfrei ausgeführt werden, sei es durch wiederhergestellte Ressourcen in Rechenzentrum 1 oder neue Ressourcen in Rechenzentrum 3. Die Microsoft [Service Level Agreement](service-level-agreement.md) (SLA) gilt während dieser Zeit. Office 365, die von 21Vianet betrieben werden, verfügt über eine andere SLA. Weitere Informationen finden Sie auf der [21Vianet-Website](https://www.21vbluecloud.com/office365/O365-SLA/) . 
  
## <a name="ensuring-data-availability"></a>Sicherstellen der Datenverfügbarkeit

Mit den folgenden Features stellt Microsoft sicher, dass Kundendaten immer zur Verfügung stehen, wenn sie benötigt werden:
  
- **Datenspeicherung und -redundanz:** Die Daten der Kunden werden in einer redundanten Umgebung mit zuverlässigen Datenschutzfunktionen gespeichert, um Verfügbarkeit, Geschäftskontinuität und schnelle Wiederherstellung zu ermöglichen. Mehrere Ebenen von Datenredundanz sind implementiert. Sie reichen von redundanten Datenträgern zum Schutz vor lokalen Datenträgerfehlern über die fortlaufende Replikation bis zu geografisch verteilten Rechenzentren. 
    
- **Datenüberwachung:** Microsoft-Dienste halten eine hohe Leistung durch: 
    
  - **Überwachung von Datenbanken:**
    
  - Blockierte Prozesse
    
  - Paketverlust
    
  - Prozesse in der Warteschlange
    
  - Abfragewartezeit
    
- **Durchführung vorbeugender Wartung:** Die vorbeugende Wartung umfasst Überprüfungen der Datenbankkonsistenz, regelmäßige Datenkomprimierung und Überprüfungen der Fehlerprotokolle. 
    
## <a name="support"></a>Support

Die Microsoft-Entwicklungs-und Betriebsteams werden durch eine dedizierte Support Organisation ergänzt, die eine wichtige Rolle bei der Bereitstellung von Geschäftskontinuität für Kunden spielt. Das Support Team verfügt über umfassende Kenntnisse des Diensts und der dazugehörigen Anwendungen sowie des direkten Zugriffs auf Microsoft-Experten in Architektur, Entwicklung und Tests.
  
Die Supportorganisation ist eng am Betrieb und der Produktentwicklung ausgerichtet, bietet Lösungen in kurzer Zeit und ermöglicht es den Kunden, ihre Meinung zu sagen. Feedback von Kunden leistet Beiträge zu Planungs-, Entwicklungs- und Betriebsprozessen.
  
- **Onlineverfolgung von Problemen:** Die Kunden müssen wissen, dass ihre Probleme behandelt werden, und sie müssen in der Lage sein, zeitnah die Lösung zu verfolgen. Das Microsoft 365 padmin Center Ortal bietet eine einzelne webbasierte Schnittstelle für Unterstützung. Die Kunden können über das Portal Dienstanforderungen hinzufügen und überwachen und Feedback von Microsoft-Supportteams erhalten. 
    
- **Selbsthilfe, unterstützt durch kontinuierliche Mitarbeiter Unterstützung:** Microsoft bietet eine breite Palette von Ressourcen und Tools zur Selbsthilfe, mit denen kundendienstbezogene Probleme lösen können, ohne dass Microsoft-Support erforderlich ist. 
    
Bevor Kunden Dienstanforderungen eingeben, können Sie auf Artikel der Knowledge Base und häufig gestellte Fragen zugreifen, die Hilfe bei den am häufigsten auftretenden Problemen bieten. Diese Ressourcen werden ständig mit aktuellen Informationen aktualisiert, sodass Verzögerungen bei Lösungen für bekannte Probleme vermieden werden. Wenn jedoch ein Problem auftritt, bei dem die Hilfe eines Supportmitarbeiters erforderlich ist, stehen entsprechende Mitarbeiter täglich rund um die Uhr für eine unmittelbare Unterstützung per Telefon und über das Verwaltungsportal zur Verfügung.
  
Weitere Informationen zum Support finden Sie unter [Unterstützung](support.md). 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen finden Sie in der [Beschreibung des Office 365-Platt Form Diensts](office-365-platform-service-description.md).
  