---
title: Office 365 Advanced Threat Protection-Dienstbeschreibung
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Microsoft Office 365 Advanced Threat Protection (ATP) ist ein Cloud-basierter e-Mail-Filterdienst, der Ihre Organisation vor unbekannten Schadsoftware und Viren schützt, indem Sie einen robusten Zero-Day-Schutz bietet und Funktionen zum Schutz Ihrer Organisation von schädlichen Links in Echtzeit. ATP verfügt über umfangreiche Berichte und URL-Ablaufverfolgungsfunktionen, mit denen Administratoren Einblicke in die Art von Angriffen in Ihrer Organisation erhalten.
ms.openlocfilehash: 04aa26bf1911a46b1268259d15933f612a38369d
ms.sourcegitcommit: 64cb402c59d8688052ffd15213fcba2857d9cd47
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/02/2019
ms.locfileid: "36058817"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection-Dienstbeschreibung

Microsoft Office 365 Advanced Threat Protection (ATP) ist ein Cloud-basierter e-Mail-Filterdienst, der Ihre Organisation vor unbekannten Schadsoftware und Viren schützt, indem Sie einen robusten Zero-Day-Schutz bietet und Funktionen zum Schutz Ihrer Organisation von schädlichen Links in Echtzeit. ATP verfügt über umfangreiche Berichte und URL-Ablaufverfolgungsfunktionen, mit denen Administratoren Einblicke in die Art von Angriffen in Ihrer Organisation erhalten.
  
Im folgenden finden Sie die wichtigsten Methoden zum Verwenden von ATP für den Nachrichtenschutz:
  
- In einem Szenario mit Office 365 reinen ATP-Filterung bietet ATP Cloud-basierten e-Mail-Schutz für Ihre lokale Exchange Server Umgebung oder eine andere lokale SMTP-e-Mail-Lösung.
    
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
  
Informationen zum Vergleichen von Features in den Plänen finden Sie unter [Vergleichen von Office 365 for Business-Plänen](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409) und [Ermitteln der richtigen Lösung für Microsoft 365 Enterprise](https://www.microsoft.com/microsoft-365/compare-all-microsoft-365-plans).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Neues in Office 365 Advanced Threat Protection (ATP)

Office 365 ATP werden weiterhin neue Features hinzugefügt. Nachfolgend finden Sie eine Liste mit mehreren neuen Features, von denen einige eine ATP-Richtlinie zum Überprüfen und aktualisieren aufrufen. Weitere Informationen zu den neuen Features von ATP (oder Microsoft 365 im allgemeinen) finden Sie in der [Microsoft 365-Roadmap](https://www.microsoft.com/microsoft-365/roadmap?filters=O365).

|Funktionsupdates  |Aktionselemente  |
|---------|---------|
|[Office 365 Threat Intelligence](https://docs.microsoft.com/office365/securitycompliance/office-365-ti) (TI) Funktionen sind jetzt Bedrohungs Ermittlungs-und-Antwortfunktionen im Rahmen von ATP-Plan 2. Neue Features wie [Automatische Untersuchung und Antwort](https://docs.microsoft.com/office365/securitycompliance/automated-investigation-response-office)sowie Verbesserungen des [Threat-Explorers](https://docs.microsoft.com/office365/securitycompliance/use-explorer-in-security-and-compliance)werden bereit gerollt.<br/><br/>Wenn Ihre Organisation derzeit nicht über ATP verfügt oder wenn Sie ATP, aber nicht TI hatten, haben Sie nun mehrere Optionen zu berücksichtigen, wobei ATP Plan 1 und ATP Plan 2 verfügbar sind. Weitere Informationen finden Sie unter [Feature-Verfügbarkeit über Advanced Threat Protection (ATP)-Pläne](#feature-availability-across-advanced-threat-protection-atp-plans) (in diesem Artikel) und [Office 365 Advanced Threat Protection-Pläne und-Preise](https://products.office.com/exchange/advance-threat-protection). |Überprüfen Sie das Abonnement Ihrer Organisation, und falls erforderlich, [kaufen oder bearbeiten Sie ein Add-on](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/buy-or-edit-an-add-on).  |
|Wenn Benutzer Outlook oder Outlook-Webanwendung (OWA) verwenden, rendert [ATP-sichere Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) Original-URLs, nicht umgeschriebene URLs. (Wir rufen dieses systemeigene Link Rendering auf.)<br>Wenn ein systemeigenes Link Rendering für Ihre Organisation zur Verfügung steht, funktioniert dieses Feature in Outlook 365 (Klick-und-Los), OWA und unter Windows und Mac OS. |Keine         |
|[Office 365 ATP-Warn Seiten](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links-warning-pages) verfügen über ein neues Farbschema, mehr Details und die Möglichkeit, mit einer Website zu arbeiten, obwohl Warnungen und Empfehlungen gegeben sind. |Keine         |
|Der Schutz für [ATP-sichere Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) wird erweitert, um auf URLs in Office für das Internet zuzutreffen (Word für das Internet, Excel für das Internet, PowerPoint für das Internet und OneNote für das Internet) und Office 365 ProPlus auf dem Mac.   |[Überprüfen und Bearbeiten der Richtlinien für ATP-sichere Links](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies)  |
|Die Quarantänefunktionen im Security &amp; Compliance Center werden [für SharePoint Online, OneDrive für Unternehmen und Microsoft Teams auf ATP](https://docs.microsoft.com/office365/SecurityCompliance/atp-for-spo-odb-and-teams)erweitert. |[Überprüfen und Bearbeiten der Richtlinien für ATP-sichere Anlagen](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-attachments-policies) |
|Der Schutz für [ATP-sichere Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) wird auf e-Mails ausgedehnt, die zwischen Personen innerhalb einer Organisation gesendet werden. |[Überprüfen und Bearbeiten der Richtlinien für ATP-sichere Links](https://docs.microsoft.com/office365/SecurityCompliance/set-up-atp-safe-links-policies) |
|Der Schutz für [ATP-sichere Links](https://docs.microsoft.com/office365/SecurityCompliance/atp-safe-links) wird erweitert, um auf URLs in e-Mails sowie auf URLs in Office 365 ProPlus-Dokumenten wie Word, Excel, PowerPoint und Visio unter Windows sowie auf Office-Apps auf IOS-und Android-Geräten anzuwenden.  |Vergewissern Sie sich, dass Sie die [moderne Authentifizierung für Office](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016) verwenden |

  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Anforderungen für Office 365 Advanced Threat Protection (ATP)

ATP kann mit einem beliebigen SMTP-e-Mail-Übertragungs-Agent verwendet werden, beispielsweise Exchange Server. Informationen zu von ATP unterstützten Betriebssystemen, Webbrowsern und Sprachen finden Sie in den Abschnitten „Unterstützte Browser" und „Unterstützte Sprachen" unter [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Verfügbarkeit von Features in ATP-Plänen (Advanced Threat Protection)

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.
  
|**Feature**|**ATP-Plan 1**<br>(ehemals ATP Standalone)|**ATP-Plan 2**<br>(ehemals Threat Intelligence <br>Standalone | Office 365 Enterprise E5| 
|:-----|:-----|:-----|:-----|
| *Konfiguration, Schutz und Erkennung* | 
|Sichere Anlagen |Ja|Ja |Ja|
|Sichere Links |Ja|Ja |Ja | 
|Anti-Phishing-Richtlinien |Ja |Ja |Ja |
|ATP für SharePoint, OneDrive und Microsoft Teams |Ja |Ja |Ja|
|Sichere Links in Microsoft Teams |Ja|Ja |Ja |
|Echtzeitberichte |Ja |Ja |Ja|
|*Automatisierung, Untersuchung, Behebung und Schulung* |
|Nachverfolgungslisten für Bedrohungen |Nein |Ja |Ja |
|Explorer (Advanced Threat Investigation) |Nein |Ja |Ja |
|Automatische Untersuchung und Reaktion  |Nein |Ja |Ja |
|Angriffs Simulator |Nein |Ja |Ja |

   
## <a name="advanced-threat-protection-atp-capabilities"></a>Funktionen von Advanced Threat Protection (ATP)

### <a name="safe-attachments"></a>Sichere Anlagen

[ATP-sichere Anhänge](https://docs.microsoft.com/office365/securitycompliance/atp-safe-attachments) schützen vor unbekannten Schadsoftware und Viren und bieten einen Zero-Day-Schutz zum Schutz Ihres Messagingsystems. Alle Nachrichten und Anlagen ohne eine bekannte Signatur für Viren/böswillige Software werden an eine spezielle Umgebung umgeleitet, in der ATP eine Vielzahl von Machine Learning- und Analysetechniken verwendet, um Missbrauchsabsichten zu ermitteln. Wenn keine verdächtige Aktivität ermittelt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben. 

> [!NOTE]
> Die Überprüfung der ATP-Tresoranlagen erfolgt in derselben Region, in der sich Ihre Office 365 Daten befinden. Weitere Informationen zur Geografie des Rechenzentrums finden Sie unter [wo befinden sich Ihre Daten?](https://products.office.com/where-is-your-data-located?geo=All) 

### <a name="safe-links"></a>Sichere Links

Das Feature " [ATP-sichere Links](https://docs.microsoft.com/Office365/SecurityCompliance/atp-safe-links) " schützt Ihre Benutzer proaktiv vor bösartigen URLs in einer Nachricht oder in einem Office-Dokument. Der Schutz verbleibt, wenn sie auf den Link klicken, da böswillige Links dynamisch blockiert werden, während der Zugriff auf unbedenkliche Links gewährt wird.

### <a name="anti-phishing-policies"></a>Anti-Phishing-Richtlinien

[ATP-Anti-Phishing](https://docs.microsoft.com/office365/securitycompliance/atp-anti-phishing) prüft eingehende Nachrichten auf Indikatoren, bei denen es sich möglicherweise um einen Phishing-Versuch handelt. Wenn Benutzer von ATP-Richtlinien abgedeckt werden (sichere Anlagen, sichere Links oder Anti-Phishing), werden eingehende Nachrichten von mehreren maschinellen Lernmodellen ausgewertet, die Nachrichten analysieren, und die entsprechende Aktion wird basierend auf den konfigurierten Richtlinien ausgeführt.
  
### <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP für SharePoint, OneDrive und Microsoft Teams

[ATP für SharePoint, OneDrive und Microsoft Teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams) unterstützt das erkennen und Blockieren von Dateien, die als bösartig identifiziert werden, in Teamwebsites und Dokumentbibliotheken.

### <a name="real-time-reports"></a>Echtzeitberichte

Die im Office 365 Security #a0 Compliance Center verfügbaren Überwachungsfunktionen umfassen [Echtzeitberichte und](https://docs.microsoft.com/office365/securitycompliance/view-reports-for-atp) Einblicke, mit denen sich Ihre Sicherheits-und Compliance-Administratoren auf Probleme mit hoher Priorität konzentrieren können, beispielsweise Sicherheitsangriffe oder erhöhte verdächtige Aktivitäten. Neben der Hervorhebung von Problembereichen enthalten Smart Reports und Einblicke auch Empfehlungen und Links zum Anzeigen und Durchsuchen von Daten sowie zum Ausführen von schnell Aktionen. 
  
### <a name="threat-trackers"></a>Nachverfolgungslisten für Bedrohungen

[Threat Tracker](https://docs.microsoft.com/office365/securitycompliance/threat-trackers) sind informative Widgets und Ansichten, die autorisierten Benutzern Informationen zu Cyber-Problemen bereitstellen, die sich möglicherweise auf Ihre Organisation auswirken.

### <a name="explorer"></a>Explorer

Explorer (auch als Threat Explorer bezeichnet) ist ein Echtzeitbericht, mit dem autorisierte Benutzer die aktuellen Bedrohungen identifizieren und analysieren können. Standardmäßig werden in diesem Berichtdaten für die letzten 7 Tage angezeigt; Ansichten können jedoch geändert werden, um Daten für die letzten 30 Tage anzuzeigen. 

Weitere Informationen zum Explorer (in Office 365 Advanced Threat Protection Plan 2) und zur Echtzeiterkennung (in Office 365 Advanced Threat Protection Plan 1) finden Sie unter [Threat Explorer (und Real-Time Detections)](https://docs.microsoft.com/office365/securitycompliance/threat-explorer).

### <a name="attack-simulator"></a>Angriffs Simulator
  
Mit dem Angriffs [Simulator](https://docs.microsoft.com/office365/SecurityCompliance/attack-simulator) können autorisierte Benutzer realistische Angriffsszenarien in Ihrer Organisation ausführen. Es stehen verschiedene Arten von Angriffen zur Verfügung, einschließlich eines Anzeigenamens Spear-Phishing-Angriffs, eines Kenn Wort Sprüh Angriffs und eines Brute-Force-Kenn Wort Angriffs.