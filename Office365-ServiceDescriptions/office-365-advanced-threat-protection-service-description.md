---
title: Office 365 Advanced Threat Protection-Dienstbeschreibung
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 02/08/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Bei Microsoft Office 365 Advanced Threat Protection (ATP) handelt es sich um einen cloudbasierten E-Mail-Filterdienst. Dieser schützt Ihre Organisation mithilfe des zuverlässigen Zero-Day-Schutzes vor unbekannter Schadsoftware und Viren. Er umfasst zudem Features, die Ihre Organisation in Echtzeit vor gefährlichen Links schützen. ATP verfügt über umfassende Berichterstellungs- und URL-Nachverfolgungsfunktionen. Dadurch erhalten Administratoren Einblick in die Angriffsarten, denen Ihre Organisation ausgesetzt ist.
ms.openlocfilehash: aeddc27c0275cb21ec257878e0978961356e7a85
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 02/11/2019
ms.locfileid: "29884196"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection-Dienstbeschreibung

Bei Microsoft Office 365 Advanced Threat Protection (ATP) handelt es sich um einen cloudbasierten E-Mail-Filterdienst. Dieser schützt Ihre Organisation mithilfe des zuverlässigen Zero-Day-Schutzes vor unbekannter Schadsoftware und Viren. Er umfasst zudem Features, die Ihre Organisation in Echtzeit vor gefährlichen Links schützen. ATP verfügt über umfassende Berichterstellungs- und URL-Nachverfolgungsfunktionen. Dadurch erhalten Administratoren Einblick in die Angriffsarten, denen Ihre Organisation ausgesetzt ist.
  
Im folgenden sind die primäre Methode ATP für Nachrichtenschutz verwendet werden können:
  
- In einem Office 365 ATP nur Filterung Szenario bietet ATP Cloud-basierte e-Mail-Schutz für Ihre lokale Exchange Server-Umgebung oder andere lokale SMTP-e-Mail-Lösungen.
    
- Office 365 ATP kann aktiviert werden, um über die Exchange Online-Cloud gehostete Postfächer zu schützen. Weitere Informationen über Exchange Online finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description/exchange-online-service-description.md).
    
- In einer Hybridbereitstellung kann ATP für den Schutz Ihrer Messaging-Umgebung und für die Steuerung von E-Mail-Routing konfiguriert werden, wenn Sie sowohl über lokale als auch über Cloud-Postfächer mit Exchange Online Protection für die eingehende E-Mail-Filterung verfügen.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Verfügbarkeit von Office 365 Advanced Threat Protection (ATP)

ATP ist in Office 365 Enterprise E5, Office 365 Education A5 und Microsoft 365 Business enthalten. 
  
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

Im Februar 2019 beginnen und anschließend in den nächsten Monaten einführen, sind ATP Threat Intelligence-Funktionen hinzugefügt wird. Darüber hinaus Wenn Ihre Organisation ATP derzeit nicht vorhanden ist, müssen neue Optionen zu berücksichtigen sind, Sie einschließlich ATP Plan 1 und ATP Plan 2. Weitere Informationen finden Sie unter [Erweiterte Threat Protection von Office 365-Pläne und zu Preisen](https://products.office.com/en-us/exchange/advance-threat-protection#pmg-allup-content) und [Verfügbarkeit von Features in verschiedenen Plänen erweiterte Threat Protection (ATP)](#feature-availability-across-advanced-threat-protection-atp-plans).

Informationen zu neuen Features in ATP finden Sie unter [neue Features in ATP](https://docs.microsoft.com/office365/securitycompliance/office-365-atp#new-features-are-continually-being-added-to-atp).
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Anforderungen für Office 365 Advanced Threat Protection (ATP)

ATP kann mit einem beliebigen SMTP-E-Mail-Übertragungsagent wie Microsoft Exchange Server 2013 verwendet werden. Informationen zu von ATP unterstützten Betriebssystemen, Webbrowsern und Sprachen finden Sie in den Abschnitten „Unterstützte Browser" und „Unterstützte Sprachen" unter [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Verfügbarkeit von Features in ATP-Plänen (Advanced Threat Protection)

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.
  
|**Funktion**|**ATP Plan 1**<br>(früher ATP eigenständig)|**ATP Plan 2**<br>(früher Bedrohungsanalyse <br>eigenständig) | Office 365 Enterprise E5| 
|:-----|:-----|:-----|:-----|
| *Konfiguration, den Schutz und Erkennung* | 
|Sichere Anlagen |Ja|Ja  |Ja |
|Sichere Links |Ja|Ja  |Ja  | 
|Anti-Phishing-Richtlinien |Ja |Ja  |Ja  |
|ATP für SharePoint, OneDrive und Microsoft-Teams |Ja |Ja  |Ja |
|Sichere Links in Teams |Ja|Ja  |Ja  |
|Berichte in Echtzeit |Ja |Ja  |Ja |
|*Automatisierung, Untersuchung, Wartung und Bildungseinrichtungen* |
|Bedrohung Tracker |Nein |Ja |Ja  |
|Explorer (Bedrohung Untersuchung erweitert) |Nein |Ja |Ja  |
|Untersuchung und Antwort  |Nein |Ja |Ja  |
|Angriff Simulator |Nein |Ja |Ja |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Funktionen von Advanced Threat Protection (ATP)

### <a name="safe-attachments"></a>Sichere Anlagen

[Sichere Anlagen ATP](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) schützt vor unbekannten Malware und Viren und bietet Zero-Day-Schutz zum Schützen des messaging-Systems. Alle Nachrichten und Anlagen, die nicht über eine bekannte Virus/Schadsoftware Signatur verfügen werden an eine spezielle Umgebung weitergeleitet, sofern ATP Lern- und Analyse Fair-Computer zum Erkennen von böswilligen Absichten verwendet. Wenn keine verdächtigen Aktivität erkannt wird, wird die Nachricht zur Zustellung an das Postfach freigegeben. 

### <a name="safe-links"></a>Sichere Links

Das Feature [ATP sichere Links](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) schützt die Benutzer proaktiv vor schädliche URLs in einer Nachricht oder in einem Office-Dokument. Der Schutz bleibt jedes Mal, wenn sie auf den Link klicken, wie böswillige Links dynamisch gesperrt sind, während eine gute Links zugegriffen werden kann.

### <a name="anti-phishing-policies"></a>Anti-Phishing-Richtlinien

[ATP Anti-Phishing](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) überprüft eingehende Nachrichten Indikatoren, dass eine Nachricht ein Phishing-Versuch möglicherweise auf. Wenn Benutzer fallen ATP-Richtlinien (sichere Anlagen, sicheren Links oder Anti-Phishing), eingehende Nachrichten von mehreren Computer erlernen Modelle, die Nachrichten zu analysieren ausgewertet, und die entsprechende Aktion ausgeführt, basierend auf der konfigurierten Richtlinien.
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP für SharePoint, OneDrive und Microsoft Teams

[ATP für SharePoint, OneDrive, und Microsoft-Teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) können erkennen und blockieren Dateien, die in Dokumentbibliotheken und Teamwebsites wie böswilligen identifiziert werden.

### <a name="real-time-reports"></a>Berichte in Echtzeit

Überwachungsfunktionen verfügbar in die Office 365-Sicherheit & Compliance Center beinhalten [Berichte in Echtzeit und Insights](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) , mit denen die Sicherheit und Richtlinientreue Administratoren Probleme mit hoher Priorität, wie Sicherheitsangriffen konzentrieren können oder verdächtigen Aktivitäten erhöht. Zusätzlich zur Hervorhebung Problembereiche, umfassen smart Berichte und Einblicke in die Empfehlungen und Links zu anzeigen und Durchsuchen von Daten und auch quick Aktionen. 
  
### <a name="threat-trackers"></a>Bedrohung Tracker

[Bedrohung Tracker](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) sind informative Widgets und Ansichten, die autorisierte Benutzern Intelligence Sicherheit im Internet Fragen bereitzustellen, die Ihre Organisation beeinträchtigen könnten.

### <a name="explorer"></a>Explorer

[Explorer](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance) (auch als Bedrohung Explorer bezeichnet) ist ein in Echtzeit Bericht, dass autorisierte Benutzer identifizieren und Analysieren der letzte Bedrohungen können. In diesem Bericht zeigt standardmäßig Daten für die letzten 7 Tage; Ansichten können jedoch geändert werden, um Daten für den letzten 30 Tagen anzuzeigen. 

### <a name="attack-simulator"></a>Angriff Simulator
  
[Angriff Simulator](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) können autorisierte Benutzer realistische Angriff Szenarien in Ihrer Organisation ausgeführt. Verschiedene Arten von Angriffen sind verfügbar, einschließlich einen Display Name Spear Phishing-Angriff, ein Kennwort Sprühende-Angriff und ein Brute-Force-Kennwortangriff.