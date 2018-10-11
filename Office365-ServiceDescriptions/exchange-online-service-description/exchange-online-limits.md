---
title: Exchange Online-Begrenzungen
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 7/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Suchen Sie die Exchange Online-Begrenzungen für eine Vielzahl von Service-Bereichen, einschließlich Adressbuchbeschränkungen, Speicherbegrenzungen für Postfächer und Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung, um nur einige zu nennen.
ms.openlocfilehash: 26fc2f55bc678103b92607978d3a5c746d5df8cc
ms.sourcegitcommit: 0b61418567c542fe1f22da3174627b427218e18d
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/10/2018
ms.locfileid: "25492795"
---
# <a name="exchange-online-limits"></a>Exchange Online-Begrenzungen

Suchen Sie die Exchange Online-Begrenzungen für eine Vielzahl von Service-Bereichen, einschließlich Adressbuchbeschränkungen, Speicherbegrenzungen für Postfächer und Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung, um nur einige zu nennen.
  
> [!NOTE]
>  Wenn Sie Unterstützung bei einer Aufgabe benötigen oder ein Problem lösen müssen, könnten die folgenden Artikel hilfreich sein:  <br/> • [E-Mail](https://support.office.com/en-us/article/Email-94275804-7147-4332-9ccd-5d421760a9ed?ui=en-US&amp;rs=en-US&amp;ad=US) (für Informationen zum Erstellen und Senden von e-Mails)  <br/> • [E-Mail in Office 365 für Unternehmen - Admin-Hilfe](https://go.microsoft.com/fwlink/?linkid=529722) <br/>   • [Beheben von Outlook und Office 365-Probleme mit Microsoft-Support und Recovery-Assistenten für Office 365](https://diagnostics.office.com/) <br/>  • [E-Mail-Unzustellbarkeitsberichte in Office 365](https://go.microsoft.com/fwlink/?linkid=526653) <br/> • [Exchange Online-Hilfe](https://go.microsoft.com/fwlink/?linkid=825607) <br/>
  
In Microsoft Exchange Online Beschränkungen in der folgenden Kategorien unterteilt:
  
- [Adressbuchbeschränkungen](#address-book-limits)
    
- [Speicherbegrenzungen für Postfächer](#mailbox-storage-limits)
    
- [Kapazitätswarnungen](#capacity-alerts)
    
- [Begrenzungen für Postfachordner](#mailbox-folder-limits)
    
- [Nachrichtengrenzwerte](#message-limits)

- [Empfangs- und Sendegrenzen](#receiving-and-sending-limits)
    
- [Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung](#reporting-and-message-trace-limits)
    
- [Aufbewahrungsgrenzwerte](#retention-limits)
    
- [Verteilergruppen-Grenzwerte](#distribution-group-limits)
    
- [Journal, Transport- und Postfachregeln Regel Grenzwerte](#journal-transport-and-inbox-rule-limits)
    
- [Moderationsgrenzwerte](#moderation-limits)
    
- [Exchange ActiveSync-Grenzwerte](#exchange-activesync-limits)
    
> [!IMPORTANT]
>  •, Die die Grenzwerte für die auf einer Microsoft Office 365-Organisation angewendet sich je nach wie lange die Organisation unterscheiden hat den Dienst registriert wurde.<br/> • Wenn ein Grenzwert in den Microsoft-Daten geändert wird zentriert, dauert es etwas Zeit, um die Änderung für alle vorhandenen Kunden zu übernehmen.<br/> • Sie die meisten dieser Grenzwerte, aber Sie und Ihre Benutzer nicht geändert werden kann, sollte bekannt sein.<br/> • Diese Grenzwerte gelten für interne und externe Empfänger.<br/> Standardmäßig werden in Exchange Online Protection (EOP) • schützt Exchange Online-Postfächer. Grenzwerte, die für EOP-Funktionen in Exchange Online gelten, finden Sie unter [Exchange Online Protection Limits](../exchange-online-protection-service-description/exchange-online-protection-limits.md).<br/> • Informationen zu Office 365-Grenzwerte, finden Sie unter "Wie kann ich meine Groups? verwalten führen Sie" in [informieren Sie sich über Office 365-Gruppen](https://go.microsoft.com/fwlink/?linkid=846714). 
  
## <a name="address-book-limits"></a>Adressbuchbeschränkungen

- **Adresslistenbeschränkung** Die maximale Anzahl an Adresslisten, die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können. Diese Zahl schließt die Standardadresslisten in Exchange Online ein, z. B. alle Kontakte und alle Gruppen. 
    
    > [!NOTE]
    > Einem einzelnen Offlineadressbuch (OAB) können bis zu 20 Adresslisten zugewiesen werden. 
  
- **Offlineadressbuch-Beschränkungen** Die maximale Anzahl an Offlineadressbüchern (OAB), die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können. 
    
- **Adressbuchrichtlinien-Beschränkungen** Die maximale Anzahl an Adressbuchrichtlinien (ABP), die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können. 
    
- **Globale Adresslisten** Die maximale Anzahl an globalen Adresslisten (GAL), die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können. 
    
### <a name="address-book-limits-across-office-365-options"></a>Adressbuchbeschränkungen in Office 365-Optionen

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Adresslistenbeschränkung  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Beschränkung für Offlineadressbuch (OAB)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Beschränkung für Adressbuchrichtlinien (ABP)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Beschränkung für globale Adresslisten  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
### <a name="address-book-limits-across-standalone-plans"></a>Beschränkungen für Adressbücher für eigenständige Pläne

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Adresslistenbeschränkung  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Beschränkung für Offlineadressbuch (OAB)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Beschränkung für Adressbuchrichtlinien (ABP)  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Beschränkung für globale Adresslisten  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
   
## <a name="mailbox-storage-limits"></a>Speicherbegrenzungen für Postfächer

Die Größe des verfügbaren Postfachspeichers ist abhängig von Postfachtyp und Abonnementlizenz des Benutzers. Administratoren können die maximale Postfachgröße pro Benutzer oder global reduzieren.
  
> [!NOTE]
> Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung in ein Exchange Online-Postfach zu kopieren. Das Archivpostfach eines Benutzers ist nur für diesen Benutzer vorgesehen. Microsoft behält sich das Recht vor, die uneingeschränkte Archivierung dann zu verweigern, wenn das Archivpostfach eines Benutzers zum Speichern von Archivdaten für andere Benutzer verwendet wird. 
  
### <a name="storage-limits-across-office-365-options"></a>Speicherbegrenzungen in Office 365-Produkten

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Benutzerpostfächer  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|Archivipostfächer<sup>7, 8</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |Unbegrenzte<sup>1</sup> <br/> |Unbegrenzte<sup>1</sup> <br/> |Nicht verfügbar<sup>4</sup> <br/> |
|Freigegebene Postfächer  <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2,9</sup> <br/> |50 GB<sup>2</sup> <br/> |
|Ressourcenpostfächer  <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3,9</sup> <br/> |50 GB<sup>3</sup> <br/> |
|Websitepostfächer<sup>5</sup> <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |Nicht verfügbar  <br/> |
|Postfächer für öffentliche Ordner  <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |50 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |100 GB<sup>6</sup> <br/> |Nicht verfügbar  <br/> |
|Gruppenpostfächer  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> jeden Benutzer empfängt zunächst 100 GB an Speicher in das Archivpostfach. Wenn die Archivierung erweiterbares aktiviert ist, ist zusätzlicher Speicher automatisch hinzugefügt, wenn die Speicherkapazität 100 GB erreicht wird. Weitere Informationen finden Sie unter [Übersicht über die uneingeschränkte Archivierung in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Finden Sie weitere Informationen zur Verfügbarkeit der [Wegweiser für Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) .<br/>  <sup>2</sup> um ein freigegebenes Postfach zuzugreifen, muss ein Benutzer eine Exchange Online-Lizenz verfügen. Freigegebene Postfächer ist keine separate Lizenz erforderlich. Ohne eine Lizenz sind jedoch freigegebene Postfächer auf 50 GB beschränkt. Um die Größe des Postfachs zu erhöhen, muss eine E3 oder E5 Lizenz zugewiesen werden. Dadurch wird das Postfach auf 100 GB verbessert. Wenn Sie aktivieren das Archivpostfach oder eine Aufbewahrung für eventuelle Rechtsstreitigkeiten auf ein freigegebenes Postfach zu platzieren möchten, ist eine Lizenz für Exchange Online – Plan 2 oder ein Exchange Online – Plan 1 mit Exchange Online-Archivierung Lizenz erforderlich. Wenn Sie das Archivpostfach und erweiterbares Archivierung für ein freigegebenes Postfach aktivieren, wird zusätzlicher Speicher automatisch hinzugefügt, wenn die Speicherkapazität 100 GB für das Archivpostfach erreicht ist.<br/>  <sup>3</sup> Ressourcenpostfächer ist keine Lizenz erforderlich. Ohne eine Lizenz sind jedoch freigegebene Postfächer auf 50 GB beschränkt. Um die Größe des Postfachs zu erhöhen, muss eine E3 oder E5 Lizenz zugewiesen werden. Dadurch wird das Postfach auf 100 GB verbessert.<br/>  <sup>4</sup> archivpostfächer sind nicht in Exchange Online-Kiosk enthalten. Jedoch kann als Add-on über Exchange Online-Archivierung erworben werden. Weitere Informationen finden Sie in der [Exchange Online-Archivierung Service Description](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md).<br/>  <sup>5</sup> websitepostfächer Erstellung und Verwaltung in SharePoint Online. Weitere Informationen finden Sie unter [Vorbereitung für die Verwendung von websitepostfächern in Office 365](http://go.microsoft.com/fwlink/p/?LinkId=299131).<br/>  <sup>6</sup> Sie können maximal 1.000 Postfächer für Öffentliche Ordner, und die Gesamtgröße aller Postfächer für Öffentliche Ordner ist auf 50 TB begrenzt. Hierarchiepostfächer verarbeiten können nur 100 Postfächer für Öffentliche Ordner.<br/>  <sup>7</sup> archivpostfächer können nur verwendet werden zum Archivieren von e-Mail-Nachrichten für einen einzelnen Benutzer oder eine Entität (beispielsweise eines freigegebenen Postfachs) für die eine Lizenz angewendet wurden. Verwendung von archivpostfächern zum Speichern von e-Mails von mehreren Benutzern oder Entitäten ist unzulässig. Ein IT-Administrator kann nicht beispielsweise ein freigegebenes Postfach erstellen und haben Benutzer diesen explizite zum Zweck der Archivierung (über das Feld Cc und Bcc oder über eine Transportregel) kopieren. Beachten Sie, dass ein freigegebenes Postfach, mit denen mehrere Personen nicht tatsächlich e-Mail für einzelne Benutzer gespeichert. Mehrere Benutzer Zugriff haben, und sie als das freigegebene Postfach e-Mail senden. Daher sind die nur e-Mails, die in das freigegebene Postfach gespeichert, die von diesem *als* das freigegebene Postfach oder gesendet.<br/>  <sup>8</sup> Wenn Sie eine Aufbewahrungsrichtlinie in Exchange Online erstellt haben, werden Nachrichten automatisch in Archivpostfach des Benutzers verschoben werden nur, wenn das Postfach des Benutzers primären größer als 10 MB ist. Die Aufbewahrungsrichtlinie werden für Postfächer, die weniger als 10 MB sind, werden nicht automatisch ausgeführt.<br/>  <sup>9</sup> Shared und Ressource Postfächer ist keine Lizenz erforderlich. Ohne eine Lizenz sind jedoch freigegebene Postfächer auf 50 GB beschränkt. Um die Größe des Postfachs zu erhöhen, muss eine E3 oder E5 Lizenz zugewiesen werden. Dadurch wird das Postfach auf 100 GB verbessert. 
  
### <a name="storage-limits-across-standalone-plans"></a>Speicherbegrenzungen in eigenständigen Plänen

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Benutzerpostfächer  <br/> |2 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
|Archivieren von Postfächern<sup>8, 9</sup> <br/> |100 GB<sup>1</sup> <br/> |50 GB  <br/> |Unbegrenzte<sup>2</sup> <br/> |Nicht verfügbar<sup>5</sup> <br/> |
|Freigegebene Postfächer  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>3</sup> <br/> |50 GB<sup>3,10</sup> <br/> |50 GB<sup>3</sup> <br/> |
|Ressourcenpostfächer  <br/> |2 GB<sup>1</sup> <br/> |50 GB<sup>4</sup> <br/> |50 GB<sup>4,10</sup> <br/> |50 GB<sup>4</sup> <br/> |
|Postfächer für öffentliche Ordner  <br/> |2 GB<sup>6</sup> <br/> |50 GB<sup>7</sup> <br/> |100 GB<sup>7</sup> <br/> |Nicht verfügbar  <br/> |
|Gruppenpostfächer  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> Dies ist die standardmäßige Postfachgröße für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. Es ist keiner maximalen Speichergrenzwert für lokale Postfächer.<br/>  <sup>2</sup> jeder Benutzer empfängt zunächst 100 GB an Speicher in das Archivpostfach. Wenn die Archivierung erweiterbares aktiviert ist, ist zusätzlicher Speicher automatisch hinzugefügt, wenn die Speicherkapazität 100 GB erreicht wird. Weitere Informationen finden Sie unter [Übersicht über die uneingeschränkte Archivierung in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Finden Sie unter der [Wegweiser für Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) ausführliche Informationen zur Verfügbarkeit für erweiterbares Archivierung.<br/> <sup>3</sup> , um ein freigegebenes Postfach zugreifen zu können, muss ein Benutzer eine Exchange Online-Lizenz verfügen. Freigegebene Postfächer ist keine separate Lizenz erforderlich. Ohne eine Lizenz sind jedoch freigegebene Postfächer auf 50 GB beschränkt. Um die Größe des Postfachs zu erhöhen, muss eine Lizenz für Exchange Online – Plan 2 zugewiesen werden. Dadurch wird das Postfach auf 100 GB verbessert. Wenn Sie aktivieren das Archivpostfach oder eine Aufbewahrung für eventuelle Rechtsstreitigkeiten auf ein freigegebenes Postfach zu platzieren möchten, ist eine Lizenz für Exchange Online – Plan 2 oder ein Exchange Online – Plan 1 mit Exchange Online-Archivierung Lizenz erforderlich. Wenn Sie das Archivpostfach und erweiterbares Archivierung für ein freigegebenes Postfach aktivieren, wird zusätzlicher Speicher automatisch hinzugefügt, wenn die Speicherkapazität 100 GB für das Archivpostfach erreicht ist.<br/> <sup>4</sup> Ressourcenpostfächer ist keine Lizenz erforderlich. Ohne eine Lizenz sind jedoch freigegebene Postfächer auf 50 GB beschränkt. Um die Größe des Postfachs zu erhöhen, muss eine Lizenz für Exchange Online – Plan 2 zugewiesen werden. Dadurch wird das Postfach auf 100 GB verbessert.<br/>  <sup>5</sup> archivpostfächer sind nicht in Exchange Online-Kiosk enthalten. Jedoch kann als Add-on über Exchange Online-Archivierung erworben werden. Weitere Informationen finden Sie in der [Exchange Online-Archivierung Service Description](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md).<br/>  <sup>6</sup> Dies ist die standardmäßige Postfachgröße für Organisationen, die Microsoft Exchange Server 2013. Administratoren können diesen Wert für ihre Organisation ändern. In Exchange Server 2013, Sie können maximal 100 Postfächer für Öffentliche Ordner, und die Gesamtgröße aller Postfächer für Öffentliche Ordner ist auf 50 TB begrenzt.<br/>  <sup>7</sup> In Exchange Online, Sie können maximal 1.000 Postfächer für Öffentliche Ordner, und die Gesamtgröße aller Postfächer für Öffentliche Ordner ist auf 50 TB begrenzt.<br/>  <sup>8</sup> archivpostfächer können nur verwendet werden zum Archivieren von e-Mail-Nachrichten für einen einzelnen Benutzer oder eine Entität für die eine Lizenz angewendet wurde. Verwenden ein Archivpostfach als eine Möglichkeit zum Speichern von e-Mails von mehreren Benutzern oder Entitäten ist unzulässig. IT-Administratoren können nicht beispielsweise freigegebene Postfächer erstellen und Benutzer (über das Feld Cc und Bcc oder über eine Transportregel) ein freigegebenen Postfachs explizite zum Zweck der Archivierung kopiert haben.<br/>  <sup>9</sup> Wenn Sie eine Aufbewahrungsrichtlinie in Exchange Online erstellt haben, werden Nachrichten automatisch in Archivpostfach des Benutzers verschoben werden nur, wenn das Postfach des Benutzers primären größer als 10 MB ist. Die Aufbewahrungsrichtlinie werden für Postfächer, die weniger als 10 MB sind, werden nicht automatisch ausgeführt.<br/>  <sup>10</sup> Shared und Ressourcenpostfächer erfordern keine Lizenz zugewiesen werden soll. Ohne eine Lizenz sind diese Postfächer jedoch auf 50 GB beschränkt. Um die Größe des Postfachs zu erhöhen, muss eine Lizenz für Exchange Online – Plan 2 zugewiesen werden. Dadurch wird das Postfach auf 100 GB verbessert. 
  
> [!NOTE]
> Ein freigegebenes Postfach ist nicht für die direkte Anmeldung ausgelegt. Das Benutzerkonto für das freigegebene Postfach selbst sollte in einer (oder "getrennt") **deaktiviert** bleiben Zustand. 
  
## <a name="capacity-alerts"></a>Kapazitätswarnungen

Exchange Online bietet drei Arten von Benachrichtigungen, wenn das Postfach eines Benutzers sich der Kapazitätsgrenze nähert oder sie erreicht:
  
- **Warnung** Der Benutzer erhält eine Warnung per E-Mail, dass das Postfach sich dem oberen Grenzwert für die Größe nähert. Mit dieser Warnung sollen Benutzer dazu aufgefordert werden, unerwünschte E-Mails zu löschen. 
    
- **Senden verbieten** Der Benutzer erhält eine Benachrichtigungs-E-Mail "Senden verbieten", wenn der Grenzwert der Postfachgröße erreicht wurde. Der Benutzer kann keine neuen Nachrichten mehr senden, bis ausreichend E-Mails gelöscht wurden, um die Größe des Postfachs auf einen Wert unter dem Grenzwert zu senken. 
    
- **Senden/Empfangen verbieten** Exchange Online weist alle eingehenden Mails ab, wenn der Grenzwert für die Postfachgröße erreicht wurde, und sendet einen Unzustellbarkeitsbericht an den Absender. Der Absender hat die Möglichkeit, die E-Mail später erneut zu versenden. Um wieder Nachrichten zu erhalten, muss der Benutzer E-Mails löschen, bis die Größe des Postfachs wieder unter dem Grenzwert liegt. 
    
### <a name="capacity-alerts-across-office-365-options"></a>Kapazitätswarnungen in Office 365-Produkten

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Warnung  <br/> |49 GB  <br/> |49 GB  <br/> |49 GB  <br/> |98 GB  <br/> |98 GB  <br/> |1,96 GB  <br/> |
|Senden verbieten  <br/> |49,5 GB  <br/> |49.5 GB  <br/> |49.5 GB  <br/> |99 GB  <br/> |99 GB  <br/> |1.98 GB  <br/> |
|Senden/Empfangen verbieten  <br/> |50 GB  <br/> |50 GB  <br/> |50 GB  <br/> |100 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
### <a name="capacity-alerts-across-standalone-plans"></a>Kapazitätswarnungen in eigenständigen Plänen

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Warnung  <br/> |1,9 GB<sup>1</sup> <br/> |49 GB  <br/> |98 GB  <br/> |1,96 GB  <br/> |
|Senden verbieten  <br/> |2 GB<sup>1</sup> <br/> |49,5 GB  <br/> |99 GB  <br/> |1.98 GB  <br/> |
|Senden/Empfangen verbieten  <br/> |2,3 GB<sup>1</sup> <br/> |50 GB  <br/> |100 GB  <br/> |2 GB  <br/> |
   
> [!NOTE]
> <sup>1</sup> Dies ist die standardmäßige Größe für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. 
  
## <a name="mailbox-folder-limits"></a>Begrenzungen für Postfachordner

Diese Begrenzungen sollen Postfächer im Rahmen bekannter Abmessungen halten, die in Exchange Online unterstützt werden können. Mit diesen Begrenzungen soll verhindert werden, dass eine unbegrenzte Anzahl von Postfachelementen pro Ordner bzw. eine unbegrenzte Anzahl von Ordnern pro Postfach oder eine unbegrenzte Anzahl von öffentlichen Ordnern pro Exchange Online-Organisation möglich ist. Praktisch gesehen ist die Anzahl der Postfachordner quasi unbegrenzt, sodass die meisten Exchange-Postfächer und lokalen Postfächer unterstützt werden, die zu Exchange Online migriert werden.
  
- **Maximale Anzahl von Nachrichten pro Postfachordner** Maximal zulässige Anzahl von Nachrichten in einem Postfachordner. Sobald dieser Grenzwert erreicht wird, können keine neuen Nachrichten mehr übermittelt oder in einem Ordner gespeichert werden. 
    
- **Warnung zur Anzahl der Nachrichten pro Postfachordner** Anzahl der Nachrichten, die in einem Postfachordner gespeichert werden können, bevor Exchange Online eine Warnmeldung an den Eigentümer des Postfachs schickt. Wenn dieses Kontingent erreicht ist, werden Warnmeldungen einmal am Tag gesendet. 
    
- **Maximale Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"** Maximale Anzahl der Nachrichten, die in jedem Ordner im Ordner "Wiederherstellbare Elemente" gespeichert werden können. Wenn ein Ordner diesen Grenzwert überschreitet, können darin keine Nachrichten mehr gespeichert werden. Wenn der Ordner "Löschen" im Ordner "Wiederherstellbare Elemente" die maximale Anzahl an Nachrichten überschritten hat und der Postfachbesitzer versucht, Elemente permanent aus seinem Postfach zu löschen, wird der Löschvorgang fehlschlagen. 
    
- **Warnung zur Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"** Anzahl der Nachrichten, die in jedem Ordner im Ordner "Wiederherstellbare Elemente" gespeichert werden können, bevor Exchange Online ein Ereignis im Anwendungsereignisprotokoll vermerkt. 
    
- **Maximale Anzahl von Unterordnern pro Postfachordner** Maximal zulässige Anzahl von Unterordnern, die in einem Postfachordner erstellt werden können. Der Postfachbesitzer wird keinen neuen Unterordner erstellen können, wenn dieser Grenzwert erreicht ist. 
    
- **Warnung zur Anzahl der Unterordner pro Postfachordner** Anzahl der Unterordner, die in einem Postfachordner erstellt werden können, bevor Exchange Online eine Warnmeldung an den Eigentümer des Postfachs schickt. Wenn dieses Kontingent erreicht ist, werden Warnmeldungen einmal am Tag gesendet. 
    
- **Maximale Ordnerhierarchie-Tiefe** Maximale Anzahl an Ebenen in der Ordnerhierarchie eines Postfachs. Der Postfachbesitzer wird keine neue Ebene in der Ordnerhierarchie des Postfachordners erstellen können, wenn dieser Grenzwert erreicht ist. 
    
- **Warnung zur Ordnerhierarchie-Tiefe** Anzahl der Ebenen, die in der Ordnerhierarchie eines Postfachordners erstellt werden können, bevor Exchange Online eine Warnmeldung an den Eigentümer des Postfachs schickt. Wenn dieses Kontingent erreicht ist, werden Warnmeldungen einmal am Tag gesendet. 
    
- **Maximale Anzahl öffentlicher Ordner** Gibt die maximale Anzahl öffentlicher Ordner in der gesamten öffentlichen Ordnerhierarchie an. Wenn diese Grenze erreicht wird, müssen vorhandene öffentliche Ordner gelöscht werden, bevor neue öffentliche Ordner erstellt werden können. 
    
- **Maximale Anzahl von Unterordnern pro öffentlichem Ordner** Maximal zulässige Anzahl von Unterordnern, die in einem öffentlichen Ordner erstellt werden können. Neue Unterordner können in einem öffentlichen Ordner nicht erstellt werden, wenn diese Grenze erreicht ist. 
    
- **Warnung zur Anzahl der Unterordner pro öffentlichem Ordner** Anzahl der Unterordner, die in einem öffentlichen Ordner erstellt werden können, bevor Exchange Online eine Warnmeldung an den Eigentümer des Ordners schickt. Falls kein Eigentümer vorhanden ist, werden Warnmeldungen an Benutzer mit Eigentümerberechtigungen geschickt. Wenn dieses Kontingent erreicht ist, werden einmal am Tag Warnmeldungen gesendet. 
    
### <a name="mailbox-folder-limits-across-office-365-options"></a>Begrenzungen für Postfachordner in Office 365-Produkten

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Maximale Anzahl von Nachrichten pro Postfachordner  <br/> |1 Million  <br/> |1 Mio.  <br/> |1 Mio.  <br/> |1 Mio.  <br/> |1 Mio.  <br/> |1 Mio.  <br/> |
|Warnung zur Anzahl der Nachrichten pro Postfachordner  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|Maximale Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"  <br/> |3 Million  <br/> |3 Million  <br/> |3 Million  <br/> |3 Million  <br/> |3 Million  <br/> |3 Million  <br/> |
|Speicherkontingent für Ordner „Wiederherstellbare Elemente" im primären Postfach (keine Aufbewahrung aktiviert)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Speicherkontingent für Ordner „Wiederherstellbare Elemente" im primären Postfach (Aufbewahrung aktiviert)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|Speicherkontingent für Ordner „Wiederherstellbare Elemente" im Archivpostfach (keine Aufbewahrung aktiviert)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |Unbegrenzte<sup>2</sup> <br/> |Unbegrenzte<sup>2</sup> <br/> |30 GB  <br/> |
|Speicherkontingent für Ordner „Wiederherstellbare Elemente" im Archivpostfach (Aufbewahrung aktiviert)  <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |100 GB<sup>1</sup> <br/> |Unbegrenzte<sup>2</sup> <br/> |Unbegrenzte<sup>2</sup> <br/> |100 GB<sup>1</sup> <br/> |
|Warnung zur Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"  <br/> |2,75 Million  <br/> |2.75 Million  <br/> |2.75 Million  <br/> |2.75 Million  <br/> |2.75 Million  <br/> |2.75 Million  <br/> |
|Maximale Anzahl von Unterordnern pro Postfachordner  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |
|Warnung zur Anzahl der Unterordner pro Postfachordner  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |
|Maximale Ordnerhierarchie-Tiefe  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Warnung zur Ordnerhierarchie-Tiefe  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Maximale Anzahl öffentlicher Ordner  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |500,000  <br/> |Nicht verfügbar  <br/> |
|Maximale Anzahl von Unterordnern pro öffentlichem Ordner  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |10,000  <br/> |Nicht verfügbar  <br/> |
|Warnung zur Anzahl der Unterordner pro öffentlichem Ordner  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |9000  <br/> |Nicht verfügbar  <br/> |
   
> [!NOTE]
> <sup>1</sup> ist das Speicherkontingent für den Ordner wiederherstellbare Elemente, nicht das Kontingent für das gesamte Archivpostfach. Das Speicherkontingent für das Archivpostfach lautet unlimited für Benutzer mit einer Lizenz für Exchange Online – Plan 2 oder für Benutzer, die ein Exchange Online – Plan 1 und einer Exchange Online-Archivierung-Lizenz verfügen. Informationen zum Erhöhen des Kontingents wiederherstellbare Elemente finden Sie unter [Erhöhen der wiederherstellbare Elemente Kontingent für Postfächer auf halten](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx).<br/> <sup>2</sup> das anfängliche Speicherkontingent für den Ordner "wiederherstellbare Elemente" in ein Archivpostfach beträgt 100 GB. Wenn die Archivierung erweiterbares aktiviert ist, ist zusätzlicher Speicher automatisch hinzugefügt, wenn die Speicherkapazität für den Ordner wiederherstellbare Elemente erreicht wird. Weitere Informationen finden Sie unter [Übersicht über die uneingeschränkte Archivierung in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Finden Sie unter der [Wegweiser für Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) ausführliche Informationen zur Verfügbarkeit von erweiterbares Archivierung. 
  
### <a name="mailbox-folder-limits-across-standalone-plans"></a>Begrenzungen für Postfachordner in eigenständigen Plänen

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Maximale Anzahl von Nachrichten pro Postfachordner  <br/> |Keine Beschränkung<sup>1</sup> <br/> |1 Million  <br/> |1 Mio.  <br/> |1 Mio.  <br/> |
|Warnung zur Anzahl der Nachrichten pro Postfachordner  <br/> |Unbegrenzt  <br/> |900,000  <br/> |900,000  <br/> |900,000  <br/> |
|Maximale Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"  <br/> |Unbegrenzt  <br/> |3 Million  <br/> |3 Million  <br/> |3 Million  <br/> |
|Speicherkontingent für Ordner „Wiederherstellbare Elemente" im primären Postfach (keine Aufbewahrung aktiviert)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Speicherkontingent für Ordner „Wiederherstellbare Elemente" im primären Postfach (Aufbewahrung aktiviert)  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |100 GB  <br/> |
|Speicherkontingent für Ordner „Wiederherstellbare Elemente" im Archivpostfach (keine Aufbewahrung aktiviert)  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |30 GB  <br/> |
|Speicherkontingent für Ordner „Wiederherstellbare Elemente" im Archivpostfach (Aufbewahrung aktiviert)  <br/> |100 GB<sup>2</sup> <br/> |100 GB<sup>2</sup> <br/> |Unbegrenzte<sup>3</sup> <br/> |Unbegrenzte<sup>3</sup> <br/> |
|Warnung zur Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"  <br/> |Unbegrenzt  <br/> |2.75 Million  <br/> |2.75 Million  <br/> |2.75 Million  <br/> |
|Maximale Anzahl von Unterordnern pro Postfachordner  <br/> |Unbegrenzt  <br/> |1000  <br/> |1000  <br/> |1000  <br/> |
|Warnung zur Anzahl der Unterordner pro Postfachordner  <br/> |Unbegrenzt  <br/> |900  <br/> |900  <br/> |900  <br/> |
|Maximale Ordnerhierarchie-Tiefe  <br/> |Unbegrenzt  <br/> |300  <br/> |300  <br/> |300  <br/> |
|Warnung zur Ordnerhierarchie-Tiefe  <br/> |Unbegrenzt  <br/> |250  <br/> |250  <br/> |250  <br/> |
|Maximale Anzahl öffentlicher Ordner  <br/> |1,000,000  <br/> |100,000  <br/> |100,000  <br/> |Nicht verfügbar  <br/> |
|Maximale Anzahl von Unterordnern pro öffentlichem Ordner  <br/> |Nicht zutreffend  <br/> |1,000  <br/> |1,000  <br/> |Nicht verfügbar  <br/> |
|Warnung zur Anzahl der Unterordner pro öffentlichem Ordner  <br/> |Nicht zutreffend  <br/> |900  <br/> |900  <br/> |Nicht verfügbar  <br/> |
   
> [!NOTE]
> <sup>1</sup> Microsoft empfiehlt nicht mehr als 1.000.000 Nachrichten pro Postfachordner. ><br/> <sup>2</sup> Hierbei handelt es sich um das Speicherkontingent für den Ordner wiederherstellbare Elemente, nicht das Kontingent für das gesamte Archivpostfach. Das Speicherkontingent für das Archivpostfach lautet unlimited für Benutzer mit einer Lizenz für Exchange Online – Plan 2 oder für Benutzer, die ein Exchange Online – Plan 1 und einer Exchange Online-Archivierung-Lizenz verfügen. Informationen zum Erhöhen des Kontingents wiederherstellbare Elemente finden Sie unter [Erhöhen der wiederherstellbare Elemente Kontingent für Postfächer auf halten](http://technet.microsoft.com/library/a8bdcbdd-9298-462f-b889-df26037a990c.aspx).<br/> <sup>3</sup> das anfängliche Speicherkontingent für den Ordner "wiederherstellbare Elemente" in ein Archivpostfach beträgt 100 GB. Wenn die Archivierung erweiterbares aktiviert ist, ist zusätzlicher Speicher automatisch hinzugefügt, wenn die Speicherkapazität für den Ordner wiederherstellbare Elemente erreicht wird. Weitere Informationen finden Sie unter [Übersicht über die uneingeschränkte Archivierung in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Finden Sie unter der [Wegweiser für Office 365](http://go.microsoft.com/fwlink/?LinkId=509914) ausführliche Informationen zur Verfügbarkeit von erweiterbares Archivierung. 
  
## <a name="message-limits"></a>Nachrichtengrenzwerte

Die folgenden Grenzwerte gelten für sämtliche E-Mails.
  
- **Nachrichtengrößenbeschränkung** Nachrichtengrößenbeschränkungen sind notwendig, um zu verhindern, dass große Nachrichten die Zustellung von anderen Nachrichten blockieren und dass die Leistung des Diensts für alle Benutzer beeinträchtigt wird. Diese Beschränkungen umfassen auch Anlagen, und sie gelten organisationsweit für alle Nachrichten (eingehende, ausgehende und interne). Nachrichten, die größer sind, werden nicht zugestellt, und der Absender erhält einen Unzustellbarkeitsbericht. Während die Grenzwerte für die Nachrichtengröße nicht nach oben oder unten oder für die einzelnen Benutzer geändert werden können, können Administratoren auch Transportregeln einrichten, um die maximale Größe einzelner Anlagen zu beschränken. Weitere Informationen finden Sie unter [Office 365 unterstützt jetzt größere E-Mails](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).
    
    > [!NOTE]
    > Bestimmte E-Mail-Clients haben niedrigere Nachrichtengrößengrenzwerte oder beschränken die Größe einer einzelnen Dateianlage auf einen Wert, der unter dem Nachrichtengrößengrenzwert von Exchange Online liegt. 
  
- **Grenzwert für die Länge des Betreffs** Die maximale Anzahl von in der Betreffzeile einer E-Mail zulässigen Textzeichen. 
    
- **Grenzwert für Dateianlagen** Die maximale Anzahl der zulässigen Dateianlagen in einer E-Mail. Auch wenn die Gesamtgröße aller Dateianlagen nicht gegen das Nachrichtengrößenlimit verstößt, gibt es dennoch eine Grenze der Anzahl der zulässigen Anlagen in der Nachricht. Dieser Grenzwert wird vom Grenzwert für mehrteiligen Nachrichten gesteuert. 
    
- **Dateianlagengrößenlimit** Die maximale Dateigröße einer einzelnen Anlage. 
    
    > [!NOTE]
    > Dies ist die maximale Dateigröße einer einzelnen Anlage. Einzelne Clientprogramme, u. a. Outlook Web App, schränken die Größe von Anlagen ggf. noch weiter ein. Exchange ActiveSync implementiert keine Anlagengrößenlimits für einzelne Anlagen. Die Gesamtgröße aller Anlagen einer Exchange ActiveSync-Nachricht muss kleiner sein als die Nachrichtengrößeneinschränkung. 
  
- **Grenze für mehrteilige Nachrichten** Die maximale Anzahl der Nachrichtentextteile, die in einer mehrteiligen MIME-Nachricht zugelassen sind. Dieser Grenzwert steuert außerdem die maximale Anzahl Dateianlagen, die in einer Nachricht zulässig sind. 
    
- **Grenzwert für die Tiefe der Nachrichteneinbettung** Die maximale Anzahl von weitergeleiteten E-Mails, die in einer E-Mail zulässig sind. 
    
### <a name="message-limits-across-office-365-options"></a>Nachrichtengrenzwerte in Office 365-Produkten

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Grenzwert für Nachrichtengröße - Outlook  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Grenzwert für Nachrichtengröße - OWA  <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |
|Grenzwert für Nachrichtengröße - Outlook für Mac  <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Nachrichtengrößenbeschränkung - Migration  <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |150 MB <sup>4</sup> <br/> |
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die die Office 365-Nachrichtenverschlüsselung mit neuen Funktionen verwenden)<sup>5</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die die ältere Version der Office 365-Nachrichtenverschlüsselung verwenden)<sup>5</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Grenzwert für Länge des Betreffs  <br/> |255 Zeichen  <br/> |255 Zeichen  <br/> |255 Zeichen  <br/> |255 Zeichen  <br/> |255 Zeichen  <br/> |255 Zeichen  <br/> |
|Grenzwert für Dateianlagen  <br/> |250 Anlagen  <br/> |250 Anlagen  <br/> |250 Anlagen  <br/> |250 Anlagen  <br/> |250 Anlagen  <br/> |250 Anlagen  <br/> |
|Größenlimit für Dateianlagen - Outlook  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Größenlimit für Dateianlagen - OWA <sup>6</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|Größenlimit für Dateianlagen - Outlook für Mac  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Grenzwert für mehrteilige Nachrichten  <br/> |250 Teile  <br/> |250 Teile  <br/> |250 Teile  <br/> |250 Teile  <br/> |250 Teile  <br/> |250 Teile  <br/> |
|Grenzwert für die Tiefe der Nachrichteneinbettung  <br/> |30 eingebettete Nachrichten  <br/> |30 eingebettete Nachrichten  <br/> |30 eingebettete Nachrichten  <br/> |30 eingebettete Nachrichten  <br/> |30 eingebettete Nachrichten  <br/> |30 eingebettete Nachrichten  <br/> |
   
> [!NOTE]
> <sup>1</sup> die standardmäßige maximale Nachrichtengröße für Office 365-Postfächer ist 25 MB. Office 365-Administratoren können eine benutzerdefinierte Beschränkung zwischen 1 und 150 MB angeben. Hängt jedoch die Größe der Nachricht senden oder empfangen können auch was Ihre e-Mail-Client oder eine bestimmte Lösung unterstützt wird. Weitere Informationen zum Anpassen der maximal zulässige Nachrichtengröße für Ihre Organisation finden Sie unter [Office 365 jetzt unterstützt größere e-Mail-Nachrichten](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).<br/> <sup>2</sup> können Sie senden und Empfangen von Nachrichten zwischen Office 365-Benutzer (, in dem die Nachricht bleibt immer auf die Datencentern Office 365) 150 MB. Codierung erhöhen, in dem Fall die maximale Nachrichtengröße 112 MB ist eine zusätzliche 33 %-Übersetzung werden Nachrichten, die außerhalb der Office 365-Rechenzentren weitergeleitet werden.<br/> <sup>3</sup> OWA-Konten für die Möglichkeit, dass Ihre Nachricht kann sein, die Anhebung der-Codierung 33 % und beschränkt die Größe der Nachricht, dass Sie auf 25 % kleiner als das konfigurierte Einstellung senden können. Angenommen, wenn Sie Ihre Einstellungen für eine maximale Nachrichtengröße 100 MB anpassen, können Sie Nachrichten nicht mehr als 75 MB senden.<br/> <sup>4</sup>      Die Größe der Nachrichten, die in Exchange Online verschoben werden sollen, wird von Exchange Online berechnet. Ältere Exchange-Versionen als Exchange Server 2013 melden möglicherweise eine geringere Elementgröße. Dieser Grenzwert gilt für auf Verschiebungen basierende Migrationen mit einem beliebigen unterstützten Exchange-Postfachreplikationsdienst. Andere Migrationsmethoden (einstufig, mehrstufig, IMAP, PST-Datei) und andere Tools von Drittanbietern werden durch allgemeine Nachrichtengröße begrenzt.<br/> <sup>5</sup> Informationen zu OME mit neuen Funktionen finden Sie unter [Einrichten von neuen Office 365 Message Encryption-Funktionen, die auf der Basis Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US).<br/> <sup>6</sup> Sie können keine einzelne Datei anfügen, die mehr als 35 MB groß ist. Darüber hinaus können Sie keine Dateien anfügen, die insgesamt 35 MB überschreiten. Wenn Sie beispielsweise eine Datei mit 34 MB anfügen, können Sie nur noch eine weitere Datei mit 1 MB anfügen. 
  
### <a name="message-limits-across-standalone-options"></a>Nachrichtengrenzwert in eigenständigen Produkten

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Grenzwert für Nachrichtengröße - Outlook  <br/> |10 MB<sup>4</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |150 MB<sup>2</sup> <br/> |
|Grenzwert für Nachrichtengröße - OWA  <br/> |10 MB<sup>4</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |112 MB<sup>1, 3</sup> <br/> |150 MB<sup>1, 2</sup> <br/> |
|Grenzwert für Nachrichtengröße - Outlook für Mac  <br/> |10 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> ||
|Nachrichtengrößenbeschränkung - Migration  <br/> |Nicht zutreffend  <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |150 MB <sup>5</sup> <br/> |
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die die Office 365-Nachrichtenverschlüsselung mit neuen Funktionen verwenden)<sup>6</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die eine ältere Version der Office 365-Nachrichtenverschlüsselung verwenden)<sup>6</sup> <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Grenzwert für Länge des Betreffs  <br/> |255 Zeichen  <br/> |255 Zeichen  <br/> |255 Zeichen  <br/> |255 Zeichen  <br/> |
|Grenzwert für Dateianlagen  <br/> |1024 Anlagen<sup>4</sup> <br/> |250 Anlagen  <br/> |250 Anlagen  <br/> |250 Anlagen  <br/> |
|Größenlimit für Dateianlagen - Outlook  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |150 MB  <br/> |
|Größenlimit für Dateianlagen - OWA  <br/> |35 MB<sup>4</sup> <br/> |35 MB  <br/> |35 MB  <br/> |35 MB  <br/> |
|Größenlimit für Dateianlagen - Outlook für Mac  <br/> |35 MB<sup>4</sup> <br/> |150 MB  <br/> |150 MB  <br/> |35 MB  <br/> |
|Grenzwert für mehrteilige Nachrichten  <br/> |250 Teile  <br/> |250 Teile  <br/> |250 Teile  <br/> |250 Teile  <br/> |
|Grenzwert für die Tiefe der Nachrichteneinbettung  <br/> |30 eingebettete Nachrichten  <br/> |30 eingebettete Nachrichten  <br/> |30 eingebettete Nachrichten  <br/> |30 eingebettete Nachrichten  <br/> |
   
> [!NOTE]
> <sup>1</sup> Office 365-Administratoren können eine benutzerdefinierte Beschränkung zwischen 1 und 150 MB angeben. Hängt jedoch die Größe der Nachricht senden oder empfangen können auch was Ihre e-Mail-Client oder eine bestimmte Lösung unterstützt wird. Weitere Informationen zum Anpassen der maximal zulässige Nachrichtengröße für Ihre Organisation finden Sie unter [Office 365 jetzt unterstützt größere e-Mail-Nachrichten](https://blogs.office.com/2015/04/15/office-365-now-supports-larger-email-messages-up-to-150-mb/).<br/> <sup>2</sup> können Sie senden und Empfangen von Nachrichten zwischen Office 365-Benutzer (, in dem die Nachricht bleibt immer auf die Datencentern Office 365) 150 MB. Codierung erhöhen, in dem Fall die maximale Nachrichtengröße 112 MB ist eine zusätzliche 33 %-Übersetzung werden Nachrichten, die außerhalb der Office 365-Rechenzentren weitergeleitet werden.<br/> <sup>3</sup> OWA-Konten für die Möglichkeit, dass Ihre Nachricht kann sein, die Anhebung der-Codierung 33 % und beschränkt die Größe der Nachricht, dass Sie auf 25 % kleiner als das konfigurierte Einstellung senden können. Angenommen, wenn Sie Ihre Einstellungen für eine maximale Nachrichtengröße 100 MB anpassen, können Sie Nachrichten nicht mehr als 75 MB senden.<br/> <sup>4</sup> Dies ist die standardmäßige maximale für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern.<br/> <sup>5</sup> die Größe von Nachrichten, die in Exchange Online verschoben werden von Exchange Online berechnet. Versionen von Exchange vor Exchange Server 2013 meldet eine geringere Elementgröße.<br/> <sup>6</sup> Informationen zu OME mit neuen Funktionen finden Sie unter [Einrichten von neuen Office 365 Message Encryption-Funktionen, die auf der Basis Azure Information Protection](https://support.office.com/en-us/article/Set-up-new-Office-365-Message-Encryption-capabilities-built-on-top-of-Azure-Information-Protection-7ff0c040-b25c-4378-9904-b1b50210d00e?ui=en-US&amp;rs=en-US&amp;ad=US). 
  
## <a name="receiving-and-sending-limits"></a>Empfangs- und Sendegrenzen

Empfangs- und Sendegrenzen werden angewendet, um Spam und Massen-E-Mail-Würmer oder -Viren zu bekämpfen. Diese Grenzwerte tragen dazu bei, die Integrität unserer Systeme sowie unsere Benutzer zu schützen.
  
### <a name="receiving-limits"></a>Empfangsgrenzen

Empfangsgrenzen gelten für die Anzahl von Nachrichten, die ein Benutzer, eine Gruppe oder ein öffentlicher Ordner pro Stunde empfangen kann. Dies gilt sowohl für Nachrichten aus dem Internet als auch für Nachrichten von lokalen Servern. Wird die Empfangsgrenze überschritten, erhalten die Absender von E-Mails an dieses Postfach einen Unzustellbarkeitsbericht mit der Information, dass das Postfach den zulässigen Schwellenwert für die Anzahl zugestellter Nachrichten überschritten hat. Nach einer Stunde wird die Grenze zurückgesetzt, und das Postfach kann wieder Nachrichten empfangen.
  
||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium Office** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Empfangene Nachrichten  <br/> |3.600 Nachrichten pro Stunde  <br/> |3.600 Nachrichten pro Stunde  <br/> |3.600 Nachrichten pro Stunde  <br/> |3.600 Nachrichten pro Stunde  <br/> |3600 Nachrichten pro Stunde  <br/> |3600 Nachrichten pro Stunde  <br/> |
   
### <a name="sending-limits"></a>Sendegrenzen

Sendegrenzen gelten für die Anzahl von Empfängern, die Anzahl von Nachrichten und die Anzahl von Empfängern pro Nachricht, die ein Benutzer aus seinem Exchange Online-Konto senden kann.
  
> [!NOTE]
> Für im Adressbuch einer Organisation gespeicherte Verteilergruppen wird die Gruppe als ein Empfänger betrachtet. Für Verteilergruppen, die im Ordner "Kontakte" eines Postfachs gespeichert sind, werden die Mitglieder der Gruppe einzeln gezählt. 
  
- **Empfängerratengrenzwert** Um die massenhafte Zustellung von Junk-E-Mails zu unterbinden, verfügtExchange Online über Empfängerbeschränkungen, mit denen Benutzer und Anwendungen daran gehindert werden, große Mengen E-Mails zu versenden. Diese Grenzwerte gelten pro Benutzer für alle ausgehenden und internen Nachrichten. 
    
    > [!NOTE]
    > Exchange Online-Kunden, die seriöse kommerzielle E-Mails versenden müssen (z. B. Kunden-Newsletter), sollten einen Drittanbieter in Anspruch nehmen, der sich auf diese Dienste spezialisiert. 
  
- **Empfängergrenzwert** Dies ist die maximale Anzahl von Empfängern, die in den Feldern "An:", "Cc:" und "Bcc:" für eine einzelne E-Mail zulässig ist. 
    
    > [!NOTE]
    > Eine Verteilerliste, die im freigegebenen Adressbuch der Organisation gespeichert ist, zählt in Bezug auf den Empfängerratengrenzwert und die Empfängereinschränkung als ein Empfänger. In einer persönlichen Verteilerliste wird jeder Empfänger separat gezählt. 
  
- **Nachrichtenratengrenzwert** Nachrichtenratengrenzwerte bestimmen, wie viele Nachrichten ein Benutzer innerhalb eines festgelegten Zeitraums von seinem Exchange Online-Konto senden kann. Dieser Grenzwert verhindert den übermäßigen Verbrauch von Systemressourcen durch einen einzelnen Absender. Wenn ein Benutzer Nachrichten mit einer Häufigkeit übermittelt, welche die SMTP-Clientübermittlungsgrenze überschreitet, werden die Nachrichten abgelehnt, und der Client muss es erneut versuchen. 
    
#### <a name="sending-limits-across-office-365-options"></a>Sendegrenzwerte für Office 365-Optionen

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Empfängerratengrenzwert  <br/> |10.000 Empfänger pro Tag  <br/> |10.000 Empfänger pro Tag  <br/> |10.000 Empfänger pro Tag  <br/> |10.000 Empfänger pro Tag  <br/> |10.000 Empfänger pro Tag  <br/> |10.000 Empfänger pro Tag  <br/> |
|Empfängergrenzwert  <br/> |500 Empfänger  <br/> |500 Empfänger  <br/> |500 Empfänger  <br/> |500 Empfänger  <br/> |500 Empfänger  <br/> |500 Empfänger  <br/> |
|Grenzwert für Empfängerproxyadresse  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
|Nachrichtenratengrenzwert (nur SMTP-Clientübermittlung)  <br/> |30 Nachrichten pro Minute  <br/> |30 Nachrichten pro Minute  <br/> |30 Nachrichten pro Minute  <br/> |30 Nachrichten pro Minute  <br/> |30 Nachrichten pro Minute  <br/> |30 Nachrichten pro Minute  <br/> |
   
#### <a name="sending-limits-across-standalone-options"></a>Sendegrenzwerte bei Optionen für eigenständige Pläne

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Empfängerratengrenzwert  <br/> |Keine Beschränkung<sup>1</sup> <br/> |10.000 Empfänger pro Tag  <br/> |10.000 Empfänger pro Tag  <br/> |10.000 Empfänger pro Tag  <br/> |
|Empfängergrenzwert  <br/> |500 Empfänger<sup>1</sup> <br/> |500 Empfänger  <br/> |500 Empfänger  <br/> |500 Empfänger  <br/> |
|Grenzwert für Empfängerproxyadresse  <br/> |400  <br/> |400  <br/> |400  <br/> |400  <br/> |
   
> [!NOTE]
> <sup>1</sup> Dies ist der standardmäßige Grenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. 
  
## <a name="reporting-and-message-trace-limits"></a>Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung
<a name="bkmk_Reporting_Message_Trace_Limits"> </a>

Weitere Informationen zu Grenzwerten für Berichterstellung und Nachrichtenablaufverfolgung finden Sie im Abschnitt "Datenverfügbarkeit und Latenz bei berichterstellung und Nachrichtenablaufverfolgung" in [Berichterstellung und Nachrichtenablaufverfolgung in Exchange Online Protection](http://go.microsoft.com/fwlink/p/?LinkId=394248).
  
## <a name="retention-limits"></a>Aufbewahrungsgrenzwerte
<a name="RetentionLimits"> </a>

Mit diesen Grenzwerten wird gesteuert, für welchen Zeitraum auf Elemente in bestimmten Ordnern im Posteingang zugegriffen werden kann.
  
- **Aufbewahrungszeitraum im Ordner "Gelöschte Elemente"** Die maximale Anzahl von Tagen, die Elemente im Ordner "Gelöschte Elemente" verbleiben können, bevor sie automatisch entfernt werden. 
    
- **Aufbewahrungszeitraum für Elemente aus dem Ordner Gelöschte Objekte entfernt** Die maximale Anzahl von Tagen, die Elemente aus dem Ordner Gelöschte Objekte entfernt werden beibehalten, bevor sie endgültig gelöscht werden. 
    
- **Aufbewahrungszeitraum im Ordner "Junk-E-Mail"** Die maximale Anzahl von Tagen, die Elemente im Ordner "Junk-E-Mail" verbleiben können, bevor sie automatisch entfernt werden. 
    
### <a name="retention-limits-across-office-365-options"></a>Aufbewahrungszeitraum in Office 365-Produkten

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Aufbewahrungszeitraum des Ordners "Gelöschte Elemente"  <br/> |Keine Beschränkung<sup>1</sup> <br/> |Keine Beschränkung<sup>1</sup> <br/> |Keine Beschränkung<sup>1</sup> <br/> |Keine Beschränkung<sup>1</sup> <br/> |Keine Beschränkung<sup>1</sup> <br/> |Keine Beschränkung<sup>1</sup> <br/> |
|Aufbewahrungszeitraum für Elemente, die aus dem Ordner "Gelöschte Elemente" entfernt wurden  <br/> |14 Tage<sup>1</sup> <br/> |14 Tage<sup>1</sup> <br/> |14 Tage<sup>1</sup> <br/> |14 Tage<sup>1</sup> <br/> |14 Tage<sup>1</sup> <br/> |14 Tage<sup>1</sup> <br/> |
|Aufbewahrungszeitraum des Ordners "Junk-E-Mail"  <br/> |30 Tage  <br/> |30 Tage  <br/> |30 Tage  <br/> |30 Tage  <br/> |30 Tage  <br/> |30 Tage  <br/> |
   
> [!NOTE]
> <sup>1</sup> Dies ist die Standardeinstellung. Administratoren können diesen Wert für ihre Organisation ändern. 
  
### <a name="retention-limits-across-standalone-options"></a>Aufbewahrungszeitraum in eigenständigen Produkten

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Aufbewahrungszeitraum des Ordners "Gelöschte Elemente"  <br/> |Keine Beschränkung<sup>1</sup> <br/> |Keine Beschränkung<sup>1</sup> <br/> |Keine Beschränkung<sup>1</sup> <br/> |Keine Beschränkung<sup>1</sup> <br/> |
|Aufbewahrungszeitraum für Elemente, die aus dem Ordner "Gelöschte Elemente" entfernt wurden  <br/> |14 Tage<sup>1</sup> <br/> |14 Tage<sup>2</sup> <br/> |14 Tage<sup>2</sup> <br/> |14 Tage<sup>2</sup> <br/> |
|Aufbewahrungszeitraum des Ordners "Junk-E-Mail"  <br/> |2 Jahre<sup>1</sup> <br/> |30 Tage  <br/> |30 Tage  <br/> |30 Tage  <br/> |
   
> [!NOTE]
> <sup>1</sup> Dies ist die Standardeinstellung. Administratoren können diesen Wert für ihre Organisation ändern.<br/> <sup>2</sup> ist der Standardwert für Exchange Online-Organisationen. Administratoren können diesen Wert auf ein Maximum von 30 Tagen für Postfächer in ihrer Organisation ändern. 
  
## <a name="distribution-group-limits"></a>Verteilergruppen-Grenzwerte

Diese Grenzwerte gelten für Verteilergruppen im freigegebenen Adressbuch Ihrer Organisation.
  
- **Maximale Anzahl Mitglieder einer Verteilergruppe** Der gesamte der Empfänger wird wird nach der Erweiterung der Verteilergruppe ermittelt. 
    
- **Senden von Nachrichten an große Verteilergruppen beschränken** Verteilergruppen, die die von diesem Grenzwert vorgegebene Anzahl von Mitgliedern enthalten, müssen über eine Zustellungsverwaltung oder konfigurierte Optionen für die Nachrichtengenehmigung verfügen. In der Zustellungsverwaltung kann eine Liste von Absendern angegeben werden, die Nachrichten an die Verteilergruppe senden dürfen. Für die Nachrichtengenehmigung werden ein oder mehrere Moderatoren angegeben, die alle an die Verteilergruppe gesendeten Nachrichten genehmigen müssen. 
    
- **Maximale Nachrichtengröße für große Verteilergruppen** Wenn eine Nachricht an 5.000 oder mehr Empfänger gesendet wird, darf die Nachrichtengröße diese Grenze nicht überschreiten. Übersteigt die Nachrichtengröße den Grenzwert, wird die Nachricht nicht zugestellt, und der Absender erhält einen Unzustellbarkeitsbericht (Non-Delivery Report, NDR). Die Gesamtzahl der Empfänger wird nach der Erweiterung der Verteilergruppe ermittelt. 
    
### <a name="distribution-group-limits-across-office-365-options"></a>Verteilergruppen-Grenzwerte in Office 365-Produkten

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Maximale Anzahl Mitglieder einer Verteilergruppe<sup>1</sup> <br/> |100.000 Mitglieder  <br/> |100.000 Mitglieder  <br/> |100.000 Mitglieder  <br/> |100.000 Mitglieder  <br/> |100.000 Mitglieder  <br/> |100.000 Mitglieder  <br/> |
|Grenzwert für das Senden von Nachrichten an große Verteilergruppe  <br/> |5.000 oder mehr Mitglieder  <br/> |5.000 oder mehr Mitglieder  <br/> |5.000 oder mehr Mitglieder  <br/> |5.000 oder mehr Mitglieder  <br/> |5.000 oder mehr Mitglieder  <br/> |5.000 oder mehr Mitglieder  <br/> |
|Maximale Nachrichtengröße für Verteilergruppen mit 5.000 bis 100.000 Elemente  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
|Maximale Nachrichtengröße für Verteilergruppen mit 100.000 oder mehr Mitglieder  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |5 MB  <br/> |
|Maximale Anzahl von Verteilergruppenbesitzern  <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |
|Maximale Anzahl von Gruppen, die ein Benutzer erstellen kann  <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |300,000<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> bei Verwendung von Azure Active Directory DirSync ist die maximale Anzahl Mitglieder einer Verteilergruppe, die aus der lokalen Active Directory mit Azure Active Directory synchronisiert werden können 15.000. Wenn Sie Azure AD-Verbindung verwenden, ist diese Nummer 50.000.<br/> <sup>2</sup> Dieser Grenzwert gilt auch für Administratoren. 
  
### <a name="distribution-group-limits-across-standalone-options"></a>Grenzwerte für Verteilergruppen in eigenständigen Produkten

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Maximale Anzahl Mitglieder einer Verteilergruppe  <br/> |100.000 Mitglieder<sup>1</sup> <br/> |100.000 Mitglieder  <br/> |100.000 Mitglieder  <br/> |100.000 Mitglieder  <br/> |
|Grenzwert für das Senden von Nachrichten an große Verteilergruppe  <br/> |5.000 oder mehr Mitglieder<sup>1</sup> <br/> |5.000 oder mehr Mitglieder  <br/> |5.000 oder mehr Mitglieder  <br/> |5.000 oder mehr Mitglieder  <br/> |
|Maximale Anzahl von Verteilergruppenbesitzern  <br/> |10    <br/> |10    <br/> |10    <br/> |10    <br/> |
|Maximale Anzahl von Gruppen, die ein Benutzer erstellen kann  <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |250<sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Dies ist der standardmäßige Grenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern.<br/> <sup>2</sup> Dieser Grenzwert gilt auch für Administratoren. 
  
## <a name="journal-transport-and-inbox-rule-limits"></a>Journal-, Transport- und Postfachregelgrenzen

Die folgende Liste enthält Grenzwerte, die für Journalregeln, Transportregeln (auch als organisationsweite Regeln bezeichnet) sowie für Grenzwerte gelten, die für Posteingangsregeln gelten. Posteingangsregeln werden von einzelnen Benutzern festgelegt und auf Nachrichten angewendet, die vom Postfach des entsprechenden Benutzers gesendet und empfangen werden.
  
- **Maximale Anzahl von Journatregeln** Die maximale Anzahl von Journalregeln, die in der Organisation vorhanden sein können. 
    
- **Maximale Anzahl von Transportregeln** Die maximale Anzahl von Regeln, die in der Organisation vorhanden sein können. 
    
- **Maximalgröße einer einzelnen Transportregel** Die maximale Anzahl von Zeichen, die in einer einzelnen Transportregel verwendet werden können. Die Zeichen werden in der Bedingungen, Ausnahmen und Aktionen verwendet. 
    
- **Maximale Zeichenanzahl für alle regulären Ausdrücke in allen Transportregeln** Die Gesamtzahl der Zeichen, die in der Organisation von allen regulären Ausdrücken in allen Bedingungen und Ausnahmen von Transportregeln verwendet werden. Sie können wenige Regeln verwenden, in denen lange und komplexe reguläre Ausdrücke verwendet werden, oder Sie können viele Regeln verwenden, in denen einfache reguläre Ausdrücke verwendet werden. 
    
- **Überprüfungsgrenzwerte für Anlageninhalt**Mit den Transportregelbedingungen können Sie den Inhalt der E-Mail-Anlagen prüfen, es wird jedoch nur 1 MB des extrahierten Anlagentexts geprüft. Dieser Grenzwert von 1 MB bezieht sich auf den aus der Anlage extrahierten Text, nicht auf die Größe der Anlagendatei. Eine 2 MB große Datei kann weniger als 1 MB Text enthalten. Auf diese Weise wird der gesamte Text geprüft. 
    
- **Maximale Anzahl von Empfängern, die einer Nachricht von allen Transportregeln hinzugefügt werden** Wenn auf eine Nachricht unterschiedliche Transportregeln angewendet werden, kann der Nachricht nur eine begrenzte Anzahl von Empfängern hinzugefügt werden. Nachdem die Grenze erreicht wurde, werden verbleibende Empfänger der Nachricht nicht hinzugefügt. Außerdem können einer Nachricht von einer Transportregel keine Verteilergruppen hinzugefügt werden. 
    
- **Weiterleitungsgrenzwert** Die maximale Anzahl Empfänger, die für eine Postfach- oder Transportregel konfiguriert werden können, wenn die Weiterleitungs- oder Umleitungsaktion verwendet wird. Sollte eine Regel festgelegt werden, eine Nachricht an mehr als diese Anzahl von Empfängern weiterzuleiten, würde diese Regel nicht angewendet werden, und jede regelkonforme Nachricht würde nicht an die in dieser Regel aufgelisteten Empfänger weitergeleitet werden. 
    
- **Anzahl der Weiterleitungen einer Nachricht** Die Anzahl der auf Postfachregeln basierenden Umleitungen, Weiterleitungen oder automatischen Antworten einer Nachricht. Beispiel: Benutzer A hat eine Postfachregel, die, je nach Sender, Nachrichten an Benutzer B weiterleitet. Benutzer B hat eine Postregel, die, je nach Schlüsselwörtern in der Betreffzeile, Nachrichten an Benutzer C weiterleitet. Erfüllt eine Nachricht beide Bedingungen, wird sie nur an Benutzer B gesendet. Sie wird nicht an Benutzer C weitergeleitet, da nur eine Weiterleitung zulässig ist. In diesem Fall wird die Nachricht ohne Unzustellbarkeitsbericht (NDR) an Benutzer B entfernt. Benutzer B erfährt nicht, dass die Nachricht nicht an Benutzer C zugestellt wurde. 
    
### <a name="journal-transport-and-inbox-rule-limits-across-office-365-options"></a>Grenzwerte für Journal-, Transport- und Postfachregeln in Office 365-Produkten

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Maximale Anzahl von Journalregeln  <br/> |10 Regeln  <br/> |10 Regeln  <br/> |10 Regeln  <br/> |10 Regeln  <br/> |10 Regeln  <br/> |10 Regeln  <br/> |
|Maximale Anzahl Transportregeln  <br/> |300 Regeln  <br/> |300 Regeln  <br/> |300 Regeln  <br/> |300 Regeln  <br/> |300 Regeln  <br/> |300 Regeln  <br/> |
|Maximale Größe einer einzelnen Transportregel  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|Zeichenbegrenzung für reguläre Ausdrücke in allen Transportregeln  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|Überprüfungsgrenzwerte für Anlageninhalt  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |1 MB  <br/> |
|Maximale Anzahl der aufgrund alle Transportregeln zu einer Nachricht hinzugefügten Empfänger  <br/> |100 Empfänger  <br/> |100 Empfänger  <br/> |100 Empfänger  <br/> |100 Empfänger  <br/> |100 Empfänger  <br/> |100 Empfänger  <br/> |
|Weiterleitungsgrenzwert  <br/> |10 Empfänger  <br/> |10 Empfänger  <br/> |10 Empfänger  <br/> |10 Empfänger  <br/> |10 Empfänger  <br/> |10 Empfänger  <br/> |
|Anzahl der Umleitungen einer Nachricht  <br/> |1 Umleitung  <br/> |1 Umleitung  <br/> |1 Umleitung  <br/> |1 Umleitung  <br/> |1 Umleitung  <br/> |1 Umleitung  <br/> |
   
### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Grenzwerte für Journal-, Transport- und Postfachregeln in eigenständigen Produkten

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Maximale Anzahl von Journalregeln  <br/> |Unbegrenzt  <br/> |10 Regeln  <br/> |10 Regeln  <br/> |10 Regeln  <br/> |
|Maximale Anzahl Transportregeln  <br/> |Unbegrenzt  <br/> |300 Regeln  <br/> |300 Regeln  <br/> |300 Regeln  <br/> |
|Maximale Größe einer einzelnen Transportregel  <br/> |40 KB  <br/> |8 KB  <br/> |8 KB  <br/> |8 KB  <br/> |
|Zeichenbegrenzung für reguläre Ausdrücke in allen Transportregeln  <br/> |Unbegrenzt  <br/> |20 KB  <br/> |20 KB  <br/> |20 KB  <br/> |
|Maximale Anzahl der aufgrund alle Transportregeln zu einer Nachricht hinzugefügten Empfänger  <br/> |Unbegrenzt  <br/> |100 Empfänger  <br/> |100 Empfänger  <br/> |100 Empfänger  <br/> |
|Weiterleitungsgrenzwert  <br/> |Unbegrenzt  <br/> |10 Empfänger  <br/> |10 Empfänger  <br/> |10 Empfänger  <br/> |
|Anzahl der Umleitungen einer Nachricht  <br/> |3 Umleitungen  <br/> |1 Umleitung  <br/> |1 Umleitung  <br/> |1 Umleitung  <br/> |
  
## <a name="moderation-limits"></a>Moderationsgrenzwerte
<a name="ModerationLimits"> </a>

Diese Grenzwerte steuern die Moderationseinstellungen für die Nachrichtengenehmigung, die auf Verteilergruppen und Transportregeln angewendet wird.
  
- **Maximale Größe des Vermittlungspostfachs** Wenn das Vermittlungspostfach diese Grenze überschreitet, werden Nachrichten, die eine Moderation erfordern, zusammen mit einem Unzustellbarkeitsbericht an den Absender zurückgesendet. 
    
- **Maximale Anzahl Moderatoren** Die maximale Anzahl Moderatoren, die Sie einer einzigen moderierte Verteilergruppe oder, zuweisen kann eine Nachricht mit einer einzelnen Transportregel hinzugefügt werden. Beachten Sie, dass Sie eine Verteilergruppe als Moderator angeben können. 
    
- **Ablauf für Nachrichten, die auf Moderation warten** Standardmäßig läuft eine Nachricht, die auf Moderation wartet, nach zwei Tagen ab. Die Verarbeitung abgelaufener moderierter Nachrichten wird jedoch jeweils nach sieben Tagen durchgeführt. Dies bedeutet, dass eine moderierte Nachricht in einem Zeitraum von zwei bis neun Tagen jederzeit ablaufen kann. 
    
- **Maximale Rate für abgelaufene Moderationsbenachrichtigungen** Dieser Grenzwert gibt die maximale Anzahl von Benachrichtigungen für abgelaufene moderierte Nachrichten in einem Zeitraum von einer Stunde an. Der Grenzwert gilt für jede Postfachdatenbank im Datencenter. 
    
    Bei hoher Auslastung kann es vorkommen, dass einige Absender keine Benachrichtigungen über abgelaufene moderierte Nachrichten erhalten. Diese Benachrichtigungen können anhand von Übermittlungsberichten jedoch nachvollzogen werden.
    
### <a name="moderation-limits-across-office-365-options"></a>Moderationsgrenzwerte in Office 365-Produkten

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Maximale Größe des Vermittlungspostfachs  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|Maximale Anzahl Moderatoren  <br/> |10 Moderatoren  <br/> |10 Moderatoren  <br/> |10 Moderatoren  <br/> |10 Moderatoren  <br/> |10 Moderatoren  <br/> |10 Moderatoren  <br/> |
|Ablauf für Nachrichten, die auf Moderation warten  <br/> |2 Tage  <br/> |2 Tage  <br/> |2 Tage  <br/> |2 Tage  <br/> |2 Tage  <br/> |2 Tage  <br/> |
|Maximale Rate für abgelaufene Moderationsbenachrichtigungen  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |
   
### <a name="moderation-limits-across-standalone-options"></a>Moderationsgrenzwerte in eigenständigen Produkten

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Maximale Größe des Vermittlungspostfachs  <br/> |Keine Beschränkung<sup>1</sup> <br/> |10 GB  <br/> |10 GB  <br/> |10 GB  <br/> |
|Maximale Anzahl Moderatoren  <br/> |Unbegrenzt  <br/> |10 Moderatoren  <br/> |10 Moderatoren  <br/> |10 Moderatoren  <br/> |
|Ablauf für Nachrichten, die auf Moderation warten  <br/> |5 Tage<sup>1</sup> <br/> |2 Tage  <br/> |2 Tage  <br/> |2 Tage  <br/> |
|Maximale Rate für abgelaufene Moderationsbenachrichtigungen  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |300 Ablaufbenachrichtigungen pro Stunde  <br/> |
   
> [!NOTE]
> <sup>1</sup> Dies ist der standardmäßige Grenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. 
  
## <a name="exchange-activesync-limits"></a>Grenzwerte für Exchange ActiveSync
<a name="BKMK_ExchangeActiveSync_Limits"> </a>

Die folgenden Grenzwerte gelten für Microsoft Exchange ActiveSync. Hierbei handelt es sich um ein Clientprotokoll, das Postfachdaten zwischen Mobilgeräten und Exchange synchronisiert. 
  
- **Exchange ActiveSync-Gerätebegrenzung** Die maximale Anzahl an Exchange ActiveSync-Geräten pro Postfach. 
    
- **Exchange ActiveSync-Gerätelöschbegrenzung** Die maximale Anzahl an Exchange ActiveSync-Geräten, die ein Exchange-Administrator in einem einzelnen Monat löschen kann. 
    
- **Exchange ActiveSync-Dateianlagenbegrenzung** Die maximale Größe einer Nachrichtendateianlage, die durch ein Exchange ActiveSync-Gerät gesendet oder empfangen werden kann. 
    
### <a name="exchange-activesync-limits-across-office-365-options"></a>Exchange ActiveSync-Grenzwerte über Office 365-Optionen hinweg

||||||||
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials** <br/> |**Office 365 Business Premium** <br/> |**Office 365 Enterprise E1** <br/> |**Office 365 Enterprise E3** <br/> |**Office 365 Enterprise E5** <br/> |**Office 365 Enterprise F1** <br/> |
|Exchange ActiveSync-Gerätebegrenzung  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync-Gerätelöschbegrenzung  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Exchange ActiveSync-Dateianlagebegrenzung  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
   
### <a name="exchange-activesync-limits-across-standalone-options"></a>Exchange ActiveSync-Grenzwerte über eigenständige Optionen hinweg

||||||
|:-----|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Exchange Server 2013** <br/> |**Exchange Online Plan 1** <br/> |**Exchange Online Plan 2** <br/> |**Exchange Online-Kiosk** <br/> |
|Exchange ActiveSync-Gerätebegrenzung  <br/> |100  <br/> |100  <br/> |100  <br/> |100  <br/> |
|Exchange ActiveSync-Gerätelöschbegrenzung  <br/> |20  <br/> |20  <br/> |20  <br/> |20  <br/> |
|Exchange ActiveSync-Dateianlagebegrenzung  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |25 MB  <br/> |
