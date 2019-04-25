---
title: Exchange Online Protection-Dienstbeschreibung
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c9127cb4-689c-43b0-b224-a44ebf4374c8
description: Abrufen von Informationen zu Features und Anforderungen für Exchange Online Protection. Enthält eine Liste von Plänen, die Exchange Online Protection sowie einen Vergleich der Features in diesen Plänen bereitstellt.
ms.openlocfilehash: b90b480df4fb4116ab75f5d25428be86a9395ae0
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246111"
---
# <a name="exchange-online-protection-service-description"></a>Exchange Online Protection-Dienstbeschreibung

Abrufen von Informationen zu Features und Anforderungen für Exchange Online Protection. Enthält eine Liste von Plänen, die Exchange Online Protection sowie einen Vergleich der Features in diesen Plänen bereitstellt.
  
Microsoft Exchange Online Protection (EOP) ist ein cloudbasierter Dienst zum Filtern von E-Mails, mit dem Sie Ihre Organisation vor Spam und Schadsoftware schützen können. EOP kann die Verwaltung Ihrer Messagingumgebung und viele der beschwerlichen Aufgaben bei der Verwaltung lokaler Hardware und Software vereinfachen.
  
EOP kann in erster Linie über die folgenden Methoden für den Nachrichtenschutz eingesetzt werden:
  
- **In einem eigenständigen Szenario** EOP bietet Cloud-basierten e-Mail-Schutz für Ihre lokale Exchange Server 2013-Umgebung, Legacyversionen von Exchange Server oder für andere lokale SMTP-e-Mail-Lösungen. 
    
- **Als Bestandteil von Microsoft Exchange Online** EOP schützt standardmäßig cloudgehostete Postfächer von Exchange Online. Weitere Informationen zu Exchange Online finden Sie in der [Exchange Online-Dienstbeschreibung](../exchange-online-service-description/exchange-online-service-description.md).
    
- **In einer Hybridbereitstellung** EOP kann für den Schutz Ihrer Messaging-Umgebung und für die Steuerung von E-Mail-Routing konfiguriert werden, wenn Sie sowohl über lokale als auch über Cloudpostfächer verfügen. 
    
Informationen zum Vergleichen der Features für die verschiedenen Pläne finden Sie unter [Vergleichen der Pläne für Office 365 for Business](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
Weitere Informationen zum Kauf von Exchange Online Protection finden Sie unter [Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
Sie können Seiten in den Office 365-Dienstbeschreibungen exportieren, speichern und drucken. Informationen zum [Exportieren mehrerer Seiten](https://go.microsoft.com/fwlink/?LinkId=403349).
  
> [!IMPORTANT]
> EOP ersetzt Forefront Online Protection for Exchange (FOPE). Alle FOPE-Kunden werden zu EOP migriert. EOP bietet neben den von FOPE bereitgestellten Schutz- und Kontrollfunktionen einige weitere Funktionen. Weitere Informationen zum Übergang von FOPE zu EOP finden Sie im [Forefront Online Protection for Exchange (FOPE)-Übergangscenter](http://www.movetoeop.com). 
  
## <a name="whats-new-in-exchange-online-protection-eop"></a>Neues in Exchange Online Protection (EOP)

Weitere Informationen zu neuen Funktionen in EOP finden Sie im Artikel zu [Neuerungen in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=320390). Einen Vergleich der Funktionen von FOPE und EOP finden Sie in diesem [Funktionsvergleich zwischen FOPE und EOP](https://go.microsoft.com/fwlink/p/?LinkId=320391).
  
## <a name="exchange-online-protection-eop-plans"></a>Exchange Online Protection-Pläne (EOP)

EOP ist über die folgenden Abonnementpläne verfügbar:
  
|**Plan**|**Beschreibung**|
|:-----|:-----|
|[EOP als eigenständige Lösung](https://go.microsoft.com/fwlink/p/?LinkId=294201) <br/> |Hier schützt EOP Ihre lokalen Postfächer.  <br/> |
|[EOP-Funktionen in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=294197) <br/> |Hier schützt EOP Ihre cloudgehosteten Exchange Online-Postfächer.  <br/> |
|[Exchange Enterprise CAL mit Diensten](https://go.microsoft.com/fwlink/p/?LinkId=293699) <br/> |Hier schützt EOP Ihre lokalen Postfächer wie EOP als eigenständige Lösung. Außerdem sind DLP-Funktionen (Data Loss Prevention, Verhinderung von Datenverlust) und eine Berichterstellung mithilfe von Webdiensten verfügbar.  <br/> |
   
### <a name="exchange-enterprise-cal-with-services-features"></a>Exchange Enterprise CAL mit Diensten

Microsoft Exchange Enterprise CAL mit Diensten liefert den E-Mail-Schutz des EOP-Diensts für Ihre lokale Messaging-Umgebung sowie die folgenden Funktionen:
  
- [Data loss prevention (DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp)
    
- [Reporting using web services](reporting-and-message-trace.md#reporting-using-web-services)
    
Weitere Informationen zur Lizenzierung von Exchange Enterprise CAL mit Diensten finden Sie im Artikel zum Thema [Exchange Server 2013-Lizenzierung](https://go.microsoft.com/fwlink/p/?LinkId=293699).
  
Wenn Sie über Lizenzen für Exchange Enterprise CAL mit Diensten verfügen und den Dienst bereitstellen möchten, befolgen Sie die Anweisungen unter [Einrichten Ihres EOP-Diensts](https://go.microsoft.com/fwlink/p/?LinkId=320397). Die Installationsschritte sind mit den Schritten für die Installation der eigenständigen EOP-Lösung identisch.
  
> [!NOTE]
> Neue Funktionen für Exchange Enterprise CAL mit Diensten werden gleichzeitig mit Exchange Online bereitgestellt, nicht mit der eigenständigen Installation von EOP. Beachten Sie, dass sich die Bereitstellungszeitpläne für EOP als eigenständige Installation und Exchange Online/Exchange Enterprise CAL mit Diensten geringfügig unterscheiden können. 
  
## <a name="requirements-for-exchange-online-protection-eop"></a>Anforderungen für Exchange Online Protection (EOP)

EOP kann mit einem beliebigen SMTP-E-Mail-Übertragungsagent wie Microsoft Exchange Server 2013 verwendet werden. Informationen zu von EOP unterstützten Betriebssystemen, Webbrowsern und Sprachen finden Sie in den Abschnitten „Unterstützte Browser" und „Unterstützte Sprachen in EOP" unter [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="limits"></a>Beschränkungen

Beschränkungen in EOP finden Sie unter [Beschränkungen von Exchange Online Protection](exchange-online-protection-limits.md).
  
## <a name="feature-availability-across-exchange-online-protection-eop-plans"></a>Verfügbarkeit von Features in EOP-Plänen (Exchange Online Protection)

Jedes Funktion ist unten aufgeführt. Detailliertere Informationen zu EOP-Funktionen finden Sie unter den Links in der Tabelle. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.
  
|||||
|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**EOP als eigenständige Lösung** <br/> |**EOP-Funktionen in Exchange Online** <br/> |**Exchange Enterprise CAL mit Diensten** <br/> |
|[E-Mail-Empfänger](recipient-domain-and-company-management.md#mail-recipients) <br/> |Ja<sup>1</sup> <br/> |Ja<sup>1</sup> <br/> |Ja  <br/> |
|[Berechtigungen für Administratorrollengruppen](recipient-domain-and-company-management.md#admin-role-group-permissions) <br/> |Ja<sup>2</sup> <br/> |Ja  <br/> |Ja  <br/> |
|[Domänenverwaltung](recipient-domain-and-company-management.md#domain-management) <br/> |Ja<sup>3</sup> <br/> |Ja<sup>3</sup> <br/> |Ja<sup>3</sup> <br/> |
|[Untergeordnete Domänen abgleichen](recipient-domain-and-company-management.md#match-subdomains) <br/> |Ja  <br/> |Ja  <br/> |Nein  <br/> |
|[Verzeichnisbasierte Edge-Blockierung (DBEB)](recipient-domain-and-company-management.md#directory-based-edge-blocking-dbeb) <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Transportregeln](messaging-policy-and-compliance-servicedesc.md#transport-rules) <br/> |Ja<sup>3, 4, 14</sup> <br/> |Ja<sup>3, 4, 14</sup> <br/> |Ja  <br/> |
|[Überwachungsprotokollierung](messaging-policy-and-compliance-servicedesc.md#audit-logging) <br/> |Ja<sup>5</sup> <br/> |Ja  <br/> |Ja  <br/> |
|[Verhinderung von Datenverlusten (Data Loss Prevention, DLP)](messaging-policy-and-compliance-servicedesc.md#data-loss-prevention-dlp) <br/> |Nein  <br/> |Ja  <br/> |Ja<sup>6</sup> <br/> |
|[Office 365-Nachrichtenverschlüsselung](messaging-policy-and-compliance-servicedesc.md#office-365-message-encryption) <br/> |Ja<sup>12</sup> <br/> |Ja  <br/> |Ja<sup>12</sup> <br/> |
|[Antispamschutz](anti-spam-and-anti-malware-protection-eop.md#anti-spam-protection) (integriert)  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Anpassung von Antispamrichtlinien](anti-spam-and-anti-malware-protection-eop.md#customize-anti-spam-policies) <br/> |Ja<sup>7</sup> <br/> |Ja  <br/> |Ja  <br/> |
|[Schutz vor Schadsoftware](anti-spam-and-anti-malware-protection-eop.md#anti-malware-protection) (integriert)  <br/> |Ja<sup>13</sup> <br/> |Ja  <br/> |Ja  <br/> |
|[Anpassung von Antischadsoftwarerichtlinien](anti-spam-and-anti-malware-protection-eop.md#customize-anti-malware-policies) <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Quarantäne](anti-spam-and-anti-malware-protection-eop.md#quarantine): Verwaltung durch Administrator  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Quarantäne](anti-spam-and-anti-malware-protection-eop.md#quarantine): Selbstverwaltung durch Endbenutzer  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Add-In "Junk-E-Mail-Berichtsprogramm" für Microsoft Office Outlook](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-add-in-for-microsoft-office-outlook) <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Junk-E-Mail-Meldeprogramm in Outlook Web App](anti-spam-and-anti-malware-protection-eop.md#junk-email-reporting-in-outlook-web-app) <br/> |Ja<sup>8</sup> <br/> |Nr.<sup>8</sup> <br/> |Nr.<sup>8</sup> <br/> |
|[Weiterleiten von E-Mails zwischen Office 365 und eigenen E-Mail-Servern](mail-flow-eop.md#routing-email-between-office-365-and-your-own-email-servers) <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Sichere Nachrichten mit einem vertrauenswürdigen Partner](mail-flow-eop.md#secure-messaging-with-a-trusted-partner) <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Übernehmen der IP-Adresse eines Partners in die Liste für sichere Absender (Safe List)](mail-flow-eop.md#safe-listing-a-partners-ip-address) <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Bedingtes E-Mail-Routing](mail-flow-eop.md#conditional-mail-routing) <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Hybrides E-Mail-Routing](mail-flow-eop.md#hybrid-mail-routing) <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Microsoft 365 Admin Center-Berichte](reporting-and-message-trace.md#microsoft-365-admin-center-reports)<br/> |Ja<sup>9</sup> <br/> |Ja<sup>10</sup> <br/> |Ja <sup>9, 10</sup> <br/> |
|[Berichte der Excel-Downloadanwendung](reporting-and-message-trace.md#excel-download-application-reports) <br/> |Ja  <br/> |Ja  <br/> |Ja<sup>11</sup> <br/> |
|[Berichterstellung mit Webdiensten](reporting-and-message-trace.md#reporting-using-web-services) <br/> |Nein  <br/> |Ja  <br/> |Ja  <br/> |
|[Nachrichtenablaufverfolgung](reporting-and-message-trace.md#message-trace) <br/> |Ja<sup>15</sup> <br/> |Ja<sup>15</sup> <br/> |Ja  <br/> |
|[Zugriff auf das Microsoft 365 Admin Center](administration-and-management-eop.md#access-to-the-microsoft-365-admin-center) <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Zugriff auf die Exchange-Verwaltungskonsole](administration-and-management-eop.md#access-to-the-exchange-admin-center) (EAC)  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|[Zugriff auf Remote Windows PowerShell](administration-and-management-eop.md#remote-windows-powershell-access) <br/> |Ja<sup>2</sup> <br/> |Ja  <br/> |Ja  <br/> |
   
> [!NOTE]
> <sup>1</sup> E-Mail-Benutzer werden als „Postfächer" definiert und können zusammen mit externen E-Mail-Kontakten direkt in der Exchange-Verwaltungskonsole hinzugefügt, entfernt und anderweitig verwaltet werden. 
 <br/><sup>2</sup> Keine RBAC-Anpassung. Nur Administratorrollen. 
 <br/> <sup>3</sup> In der Exchange-Verwaltungskonsole können verwaltete Domänen angezeigt und Domänentypen bearbeitet werden. Alle anderen Domänen Verwaltungen müssen im Microsoft 365 Admin Center durchgeführt werden. 
 <br/><sup>4</sup> In Exchange Online und EOP sind jeweils unterschiedliche flexible Kriterien und Aktionen verfügbar. Eine Auflistung der in EOP verfügbaren Kriterien und Aktionen finden Sie unter [ Transportregelbedingungen ](https://go.microsoft.com/fwlink/p/?LinkId=320392) und [Transportregelaktionen](https://go.microsoft.com/fwlink/p/?LinkId=320393). Eine Auflistung der in Exchange Online verfügbaren Kriterien und Aktionen finden Sie unter [Transportregelkriterien](https://go.microsoft.com/fwlink/p/?LinkId=320394) und [Transportregelaktionen](https://go.microsoft.com/fwlink/p/?LinkId=320395). 
 <br/><sup>5</sup> EOP-Überwachungsberichte sind eine Teilmenge der Exchange Online-Überwachungsberichte und enthalten keine Informationen zu Postfächern. 
 <br/> <sup>6</sup> DLP-Richtlinientipps sind für Kunden von Exchange Enterprise CAL mit Diensten nicht verfügbar.  <br/><sup>7</sup> Die standardmäßige Inhaltsfilteraktion besteht darin, Spamnachrichten in die Junk-E-Mail-Ordner der Empfänger zu verschieben. Damit das in lokalen Postfächern funktioniert, müssen Sie auch zwei Exchange-Transportregeln auf Ihren lokalen Servern konfigurieren, um von EOP hinzugefügte Spamkopfzeilen zu erkennen. Weitere Informationen finden Sie unter [Sicherstellen, dass Spam an die Junk-E-Mail-Ordner der einzelnen Benutzer geleitet wird](https://go.microsoft.com/fwlink/p/?LinkId=320396). 
 <br/><sup>8</sup> Diese Funktion steht derzeit den Exchange Server 2013 Service Pack 1 (SP1)-Kunden zur Verfügung, deren Posteingänge von EOP gefiltert werden, und wird in Kürze auch für Exchange Online-Kunden zugänglich sein. 
 <br/><sup>9</sup> Die EOP-Berichte sind eine Teilmenge der Exchange Online-Berichte und enthalten keine Informationen zu Postfächern.
 <br/><sup>10</sup> Enthält DLP-Berichte. 
 <br/><sup>11</sup> Kunden von Exchange Enterprise CAL mit Diensten sollten die Arbeitsmappe durch Auswahl des **Exchange Online**-Diensts anstatt des **Exchange Online Protection**-Diensts installieren. 
 <br/><sup>12</sup> Wird für lokale Kunden unterstützt, die Azure Information Protection erwerben und Exchange Online Protection zum Routen von E-Mails über Exchange Online verwenden. 
 <br/> <sup>13</sup> Scannt ein- und ausgehende Nachrichten, aber keine internen Nachrichten, die ein Absender in Ihrer Organisation an einen Empfänger in Ihrer Organisation gesendet hat. 
 <br/><sup>14</sup> Für Exchange Online und EOP sind unterschiedliche Prädikate und Aktionen verfügbar. 
 <br/> <sup>15</sup> Hybridsetup steht nicht über den Hybrid-Assistenten zur Verfügung, Sie können die Einrichtung jedoch manuell vornehmen, wenn Sie über Exchange SP1 verfügen. 