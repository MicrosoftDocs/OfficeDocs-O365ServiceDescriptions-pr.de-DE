---
title: Office 365 Advanced Threat Protection-Dienstbeschreibung
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-advanced-threat-protection-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a8061c87-3572-49db-94ff-c8301e549cdd
description: Bei Microsoft Office 365 Advanced Threat Protection (ATP) handelt es sich um einen cloudbasierten E-Mail-Filterdienst. Dieser schützt Ihre Organisation mithilfe des zuverlässigen Zero-Day-Schutzes vor unbekannter Schadsoftware und Viren. Er umfasst zudem Features, die Ihre Organisation in Echtzeit vor gefährlichen Links schützen. ATP verfügt über umfassende Berichterstellungs- und URL-Nachverfolgungsfunktionen. Dadurch erhalten Administratoren Einblick in die Angriffsarten, denen Ihre Organisation ausgesetzt ist.
ms.openlocfilehash: 6c7ce44932312b82293b19d85ebac07137716617
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035832"
---
# <a name="office-365-advanced-threat-protection-service-description"></a>Office 365 Advanced Threat Protection-Dienstbeschreibung

Bei Microsoft Office 365 Advanced Threat Protection (ATP) handelt es sich um einen cloudbasierten E-Mail-Filterdienst. Dieser schützt Ihre Organisation mithilfe des zuverlässigen Zero-Day-Schutzes vor unbekannter Schadsoftware und Viren. Er umfasst zudem Features, die Ihre Organisation in Echtzeit vor gefährlichen Links schützen. ATP verfügt über umfassende Berichterstellungs- und URL-Nachverfolgungsfunktionen. Dadurch erhalten Administratoren Einblick in die Angriffsarten, denen Ihre Organisation ausgesetzt ist.
  
ATP kann in erster Linie über die folgenden Methoden für den Nachrichtenschutz eingesetzt werden:
  
- In einem Office 365 Protection-Szenario nur mit Filterung bietet ATP cloudbasierten E-Mail-Schutz für Ihre lokalen Exchange Server 2013-Umgebung, Legacyversionen von Exchange Server und alle anderen lokalen SMTP-E-Mail-Lösungen.
    
- Office 365 ATP kann aktiviert werden, um über die Exchange Online-Cloud gehostete Postfächer zu schützen. Weitere Informationen über Exchange Online finden Sie in der [Exchange Online-Dienstbeschreibung](https://technet.microsoft.com/en-us/library/exchange-online-service-description.aspx).
    
- In einer Hybridbereitstellung kann ATP für den Schutz Ihrer Messaging-Umgebung und für die Steuerung von E-Mail-Routing konfiguriert werden, wenn Sie sowohl über lokale als auch über Cloud-Postfächer mit Exchange Online Protection für die eingehende E-Mail-Filterung verfügen.
    
## <a name="office-365-advanced-threat-protection-atp-availability"></a>Verfügbarkeit von Office 365 Advanced Threat Protection (ATP)

ATP ist in Office 365 Enterprise E5, Office 365 Education A5 und Microsoft 365 Business enthalten. 
  
> [!NOTE]
> Client-abhängigen ATP-Features in Microsoft 365 Business werden die verfügbaren Sommer 2018. 
  
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
    
Informationen dazu, wie Sie Office 365 Advanced Threat Protection erwerben können, finden Sie unter [Office 365 Advanced Threat Protection](https://go.microsoft.com/fwlink/p/?LinkId=294201).
  
Informationen zum Vergleichen der Features für die verschiedenen Pläne finden Sie unter [Vergleichen der Pläne für Office 365 for Business](http://go.microsoft.com/fwlink/?LinkID=799177&amp;clcid=0x409).
  
## <a name="whats-new-in-office-365-advanced-threat-protection-atp"></a>Neues in Office 365 Advanced Threat Protection (ATP)

Weitere Informationen zu neuen Features in ATP finden Sie unter [Advanced Threat Protection (ATP) - Sichere Links in Office 365](https://go.microsoft.com/fwlink/?linkid=846016).
  
## <a name="requirements-for-office-365-advanced-threat-protection-atp"></a>Anforderungen für Office 365 Advanced Threat Protection (ATP)

ATP kann mit einem beliebigen SMTP-E-Mail-Übertragungsagent wie Microsoft Exchange Server 2013 verwendet werden. Informationen zu von ATP unterstützten Betriebssystemen, Webbrowsern und Sprachen finden Sie in den Abschnitten „Unterstützte Browser" und „Unterstützte Sprachen" unter [Exchange Admin Center in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=282381).
  
## <a name="feature-availability-across-advanced-threat-protection-atp-plans"></a>Verfügbarkeit von Features in ATP-Plänen (Advanced Threat Protection)

Jedes Feature ist unten aufgeführt. Wenn Exchange Online erwähnt wird, beziehen sich die Informationen üblicherweise auf die Office 365 Enterprise-Dienstfamilie.
  
|**Feature**|**ATP, eigenständig**|**Exchange Online Protection**|
|:-----|:-----|:-----|
|Sichere Links  <br/> |Ja  <br/> |Nein  <br/> |
|Sichere Anlagen  <br/> |Ja  <br/> |Nein  <br/> |
|Spoofing Intelligence  <br/> |Ja  <br/> |Nein  <br/> |
|Quarantäne  <br/> |Ja  <br/> |Ja  <br/> |
|Erweiterte Anti-Phishing-Funktionen  <br/> |Ja  <br/> |Nein  <br/> |
   
## <a name="advanced-threat-protection-atp-capabilities"></a>Funktionen von Advanced Threat Protection (ATP)

### <a name="safe-links"></a>Sichere Links

Das ATP-Feature für sichere Links schützt Ihre Benutzer proaktiv vor böswilligen Hyperlinks in einer Nachricht. Der Schutz verbleibt, wenn sie auf den Link klicken, da böswillige Links dynamisch blockiert werden, während der Zugriff auf unbedenkliche Links gewährt wird.
  
### <a name="safe-attachments"></a>Sichere Anlagen

Sichere Anlagen schützen gegen unbekannte böswillige Software und Viren und bieten Zero-Day-Schutz für Ihr Messaging-System. Alle Nachrichten und Anlagen ohne eine bekannte Signatur für Viren/böswillige Software werden an eine spezielle Umgebung umgeleitet, in der ATP eine Vielzahl von Machine Learning- und Analysetechniken verwendet, um Missbrauchsabsichten zu ermitteln. Wenn keine verdächtige Aktivität ermittelt wird, wird die Nachricht für die Übermittlung an das Postfach freigegeben. 
  
### <a name="spoof-intelligence"></a>Spoofing Intelligence

Spoofing Intelligence erkennt, wenn ein Absender E-Mails im Namen eines oder mehrerer Benutzerkonten in einer der Domänen Ihrer Organisation zu senden scheint. Das Feature ermöglicht es Ihnen, alle Absender zu überprüfen, die Ihre Domäne spoofen, und dann zu entscheiden, ob der Absender den Vorgang fortsetzen darf oder blockiert werden soll. Spoofing Intelligence ist im Security &amp; Compliance Center auf der Seite mit Antispameinstellungen verfügbar.
  
### <a name="quarantine"></a>Quarantäne

Nachrichten, die vom Office 365-Dienst als Spam, Massensendung oder Phishing-E-Mail identifiziert werden, die Schadsoftware enthalten oder die einer Nachrichtenflussregel entsprechen, können unter Quarantäne gestellt werden. Standardmäßig sendet Office 365 Phishingnachrichten und Nachrichten mit Schadsoftware direkt in Quarantäne. Autorisierte Benutzer können unter Quarantäne gestellte E-Mail-Nachrichten überprüfen, löschen oder verwalten.
  
### <a name="advanced-anti-phishing-capabilities"></a>Erweiterte Anti-Phishing-Funktionen

Dieses Feature verwendet Machine Learning-Modelle zum Erkennen von Phishingnachrichten. 
  
