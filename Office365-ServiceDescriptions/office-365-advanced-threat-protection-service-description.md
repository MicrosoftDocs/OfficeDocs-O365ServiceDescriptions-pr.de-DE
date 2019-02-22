---
title: Office 365 Advanced Threat Protection-Dienstbeschreibung
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/20/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Bei Microsoft Office 365 Advanced Threat Protection (ATP) handelt es sich um einen cloudbasierten E-Mail-Filterdienst. Dieser schützt Ihre Organisation mithilfe des zuverlässigen Zero-Day-Schutzes vor unbekannter Schadsoftware und Viren. Er umfasst zudem Features, die Ihre Organisation in Echtzeit vor gefährlichen Links schützen. ATP verfügt über umfassende Berichterstellungs- und URL-Nachverfolgungsfunktionen. Dadurch erhalten Administratoren Einblick in die Angriffsarten, denen Ihre Organisation ausgesetzt ist.
ms.openlocfilehash: bf16c3593ba7ff8cb5ecc9c57b170d5ce153d77e
ms.sourcegitcommit: 0779536e4b9dc4bed4fb3c7f0767314b9a63d397
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 02/21/2019
ms.locfileid: "30178344"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection-Dienstbeschreibung

Bei Microsoft Office 365 Advanced Threat Protection (ATP) handelt es sich um einen cloudbasierten E-Mail-Filterdienst. Dieser schützt Ihre Organisation mithilfe des zuverlässigen Zero-Day-Schutzes vor unbekannter Schadsoftware und Viren. Er umfasst zudem Features, die Ihre Organisation in Echtzeit vor gefährlichen Links schützen. ATP verfügt über umfassende Berichterstellungs- und URL-Nachverfolgungsfunktionen. Dadurch erhalten Administratoren Einblick in die Angriffsarten, denen Ihre Organisation ausgesetzt ist.
  
Im folgenden finden Sie die wichtigsten Möglichkeiten zum Verwenden von ATP für den Nachrichtenschutz:
  
- In einem Szenario mit Office 365 ATP-Filterung bietet ATP Cloud-basierten e-Mail-Schutz für Ihre lokale Exchange Server-Umgebung oder eine andere lokale SMTP-e-Mail-Lösung.
    
- Office 365 ATP kann aktiviert werden, um über die Exchange Online-Cloud gehostete Postfächer zu schützen. Weitere Informationen über Exchange Online finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description/exchange-online-service-description.md).
    
- In einer Hybridbereitstellung kann ATP für den Schutz Ihrer Messaging-Umgebung und für die Steuerung von E-Mail-Routing konfiguriert werden, wenn Sie sowohl über lokale als auch über Cloud-Postfächer mit Exchange Online Protection für die eingehende E-Mail-Filterung verfügen.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Verfügbarkeit von Office 365 Advanced Threat Protection (ATP)

ATP ist in Office 365 Enterprise E5, Office 365 Education a5 und Microsoft 365 Business enthalten. 
  
Sie können ATP zu den folgenden Exchange- und Office 365-Abonnementplänen hinzufügen: 
  
- Exchange Online Plan 1
    
- Exchange Online Plan 2
    
- Exchange Online-Kiosk
    
- Exchange Online Protection
    
- Office 365 Business Essentials
    
- Office 365 Business Premium
    
- Office 365 Enterprise E1
    
- Office 365 Enterprise E3
    
- Office 365 Enterprise F1
    
- Office 365 A1
    
- Office 365 A3
    
Informationen dazu, wie Sie Office 365 Advanced Threat Protection erwerben können, finden Sie unter [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection#pmg-allup-content).
  
Informationen zum Vergleichen der Features für die verschiedenen Pläne finden Sie unter [Vergleichen der Pläne für Office 365 for Business](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Neues in Office 365 Advanced Threat Protection (ATP)

Wir werden weiterhin neue Features zu Office 365 ATP hinzufügen. Nachfolgend finden Sie eine Liste mit verschiedenen neuen Features, von denen einige erfordern, dass eine ATP-Richtlinie überprüft und aktualisiert wird. Weitere Informationen zu neuen Features in ATP (oder Microsoft 365 im allgemeinen) finden Sie im [microsoft 365-Fahrplan](https://www.microsoft.com/microsoft-365/roadmap?filters=O365).

|Featureupdates  |Aktionselemente  |
|---------|---------|
|Ab Februar 2019 werden in den nächsten Monaten die Funktionen für [Threat Intelligence](https://docs.microsoft.com/office365/securitycompliance/office-365-ti) hinzugefügt. <br>Wenn Ihre Organisation derzeit nicht über ATP verfügt, stehen Ihnen neue Optionen zur Verfügung, einschließlich ATP-Plan 1 und ATP-Plan 2. <br>Weitere Informationen finden Sie unter [Feature Availability Across Advanced Threat Protection (ATP) Pläne](#feature-availability-across-advanced-threat-protection-atp-plans) (in diesem Artikel) und [Office 365 Advanced Threat Protection Plans and Pricing](https://products.office.com/exchange/advance-threat-protection). |Überarbeiten Sie das Abonnement Ihrer Organisation, und [kaufen oder bearbeiten Sie, falls erforderlich, ein Add-on](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on).  |
|Beginnend im Oktober 2018 und über die nächsten Monate hinaus, wenn Personen Outlook oder Outlook Web Application (OWA) verwenden, rendert [ATP Safe Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) ursprüngliche URLs, nicht umgeschriebene URLs. (Wir nennen dies Native Link Rendering.)<br>Wenn Native Link Rendering für Ihre Organisation verfügbar ist, funktioniert dieses Feature in Outlook 365 (Click-to-Run) und OWA.|Keine         |
|Beginnend im September 2018, [Office 365 ATP Warning Pages](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages) Feature ein neues Farbschema, weitere Details und die Möglichkeit, eine Website trotz der Warnungen und Empfehlungen weiterhin. |Keine         |
|Ab der zweiten Hälfte von 2018 wird der ATP-Schutz für [sichere Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) auf URLs in Office Online (Word Online, Excel Online, PowerPoint Online und OneNote Online) und Office 365 ProPlus unter Mac erweitert.   |[Überarbeiten und Bearbeiten Ihrer ATP-Richtlinien für sichere Links](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|Ab Ende Mai 2018 werden die Quarantänefunktionen im Security &amp; Compliance Center auf [ATP für SharePoint Online, OneDrive for Business und Microsoft Teams](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams)ausgedehnt. |[Überarbeiten und Bearbeiten Ihrer ATP-Richtlinien für sichere Anlagen](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|Ab März 2018 wird [ATP Safe Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) Protection auf e-Mails ausgedehnt, die zwischen Personen innerhalb einer Organisation gesendet werden. |[Überarbeiten und Bearbeiten Ihrer ATP-Richtlinien für sichere Links](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|Ab Ende Oktober 2017 wird der [ATP Safe Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) Protection auf URLs in E-Mails sowie URLs in Office 365 ProPlus-Dokumenten wie Word, Excel, PowerPoint und Visio unter Windows sowie auf Office-Apps auf IOS-und Android-Geräten ausgedehnt.  |Stellen Sie sicher, dass Sie die [moderne Authentifizierung für Office](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) verwenden. |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Anforderungen für Office 365 Advanced Threat Protection (ATP)

ATP kann mit einem beliebigen SMTP-e-Mail-Übertragungs-Agent wie Microsoft Exchange Server verwendet werden. Informationen zu den Betriebssystemen, Webbrowsern und Sprachen, die von ATP unterstützt werden, finden Sie in den Abschnitten "unterstützte Browser" und "Unterstützte Sprachen" in Exchange [Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Verfügbarkeit von Features in ATP-Plänen (Advanced Threat Protection)

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.
  
|**Funktion**|**ATP-Plan 1**<br>(früher ATP Standalone)|**ATP-Plan 2**<br>(ehemals Threat Intelligence <br>Standalone | Office 365 Enterprise E5| 
|:-----|:-----|:-----|:-----|
| *Konfiguration, Schutz und Erkennung* | 
|Sichere Anlagen |Ja|Ja  |Ja |
|Sichere Links |Ja|Ja  |Ja  | 
|Richtlinien zum Schutz vor Phishing |Ja |Ja  |Ja  |
|ATP für SharePoint, OneDrive und Microsoft Teams |Ja |Ja  |Ja |
|Sichere Links in Teams |Ja|Ja  |Ja  |
|Echtzeitberichte |Ja |Ja  |Ja |
|*Automatisierung, Untersuchung, Sanierung und Schulung* |
|Nachverfolgungslisten für Bedrohungen |Nein |Ja |Ja  |
|Explorer (Erweiterte Bedrohungs Ermittlung) |Nein |Ja |Ja  |
|Automatisierte Untersuchung und Antwort  |Nein |Ja |Ja  |
|AnGriffs Simulator |Nein |Ja |Ja |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Funktionen von Advanced Threat Protection (ATP)

### <a name="safe-attachments"></a>Sichere Anlagen

[ATP Safe Attachments](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) schützt vor unbekannten Schadsoftware und Viren und bietet Zero-Day-Schutz, um Ihr Messagingsystem zu schützen. Alle Nachrichten und Anlagen, die keine bekannte Virus-/Schadsoftware-Signatur aufweisen, werden an eine spezielle Umgebung weitergeleitet, in der ATP eine Vielzahl von Techniken zum Erlernen und Analysieren von Computern verwendet, um eine böswillige Absicht zu erkennen. Wenn keine verdächtige Aktivität erkannt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben. 

### <a name="safe-links"></a>Sichere Links

Das Feature für [sichere ATP-Links](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) schützt Ihre Benutzer proaktiv vor böswilligen URLs in einer Nachricht oder in einem Office-Dokument. Der Schutz bleibt immer dann, wenn Sie auf den Link klicken, da böswillige Links dynamisch blockiert werden, während auf gute Links zugegriffen werden kann.

### <a name="anti-phishing-policies"></a>Richtlinien zum Schutz vor Phishing

[ATP-AntiPhishing](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) prüft eingehende Nachrichten auf Indikatoren, die eine Nachricht als Phishing-Versuch eingestuft werden kann. Wenn Benutzer von ATP-Richtlinien abgedeckt werden (sichere Anlagen, sichere Links oder Phishing), werden eingehende Nachrichten durch mehrere Computer Lernmodelle ausgewertet, die Nachrichten analysieren und die entsprechende Aktion basierend auf den konfigurierten Richtlinien treffen.
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP für SharePoint, OneDrive und Microsoft Teams

[ATP für SharePoint, OneDrive und Microsoft Teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) hilft bei der Erkennung und Blockierung von Dateien, die in Teamwebsites und Dokumentbibliotheken als bösartig identifiziert werden.

### <a name="real-time-reports"></a>Echtzeitberichte

Zu den im Office 365 Security & Compliance Center verfügbaren Überwachungsfunktionen gehört [Echtzeit-Berichte und](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) Einblicke, mit denen sich Sicherheits-und Compliance-Administratoren auf Probleme mit hoher Priorität konzentrieren können, beispielsweise Sicherheitsangriffe oder erhöhte verdächtige Aktivität. Zusätzlich zur Hervorhebung von Problembereichen enthält Smart Reports und Einblicke Empfehlungen und Links zum Anzeigen und Durchsuchen von Daten sowie für schnelle Aktionen. 
  
### <a name="threat-trackers"></a>Nachverfolgungslisten für Bedrohungen

[Threat Tracker](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) sind informative Widgets und Ansichten, die autorisierten Benutzern Informationen zu Cyber-Problemen bereitstellen, die sich möglicherweise auf Ihre Organisation auswirken.

### <a name="explorer"></a>Explorer

[Explorer](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance) (auch als Bedrohungs-Explorer bezeichnet) ist ein Echtzeitbericht, mit dem autorisierte Benutzer neue Bedrohungen erkennen und analysieren können. Standardmäßig werden in diesem Berichtdaten für die letzten 7 Tage angezeigt; Ansichten können jedoch geändert werden, um Daten für die letzten 30 Tage anzuzeigen. 

### <a name="attack-simulator"></a>AnGriffs Simulator
  
[Angriffs Simulator](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) ermöglicht autorisierten Benutzern das Ausführen realistischer Angriffsszenarien in Ihrer Organisation. Es stehen verschiedene Arten von Angriffen zur Verfügung, einschließlich eines Vornamen-Spear-Phishing-Angriffs, eines Kennwort-Sprüh Angriffs und eines Brute-Force-Kenn Wort Angriffs.