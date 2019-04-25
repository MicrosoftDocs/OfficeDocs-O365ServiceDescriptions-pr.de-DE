---
title: Messagingrichtlinien und -kompatibilität
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 04/10/2019
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EOP) bietet Funktionen für Messagingrichtlinien und-Kompatibilität, die Ihnen bei der Verwaltung Ihrer e-Mail-Daten helfen.
ms.openlocfilehash: a37ad3c1bcecb73f7c903b553bdcb43935dc9ed7
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246121"
---
# <a name="messaging-policy-and-compliance"></a>Messagingrichtlinien und -kompatibilität

Microsoft Exchange Online Protection (EOP) bietet Funktionen für Messagingrichtlinien und-Kompatibilität, die Ihnen bei der Verwaltung Ihrer e-Mail-Daten helfen.
  
Sie suchen nach Informationen zu allen EOP-Funktionen? Entsprechendes finden Sie in der [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).
  
## <a name="transport-rules"></a>Transportregeln
<a name="BKMK_transportrules"> </a>

Transportregeln bieten Ihnen die Möglichkeit, auf flexible Weise eigene unternehmensspezifische Richtlinien auf E-Mails anzuwenden. Transportregeln bestehen aus flexiblen Kriterien, mit denen Sie Bedingungen und Ausnahmen sowie die Aktionen, die basierend auf den Kriterien ausgeführt werden sollen, definieren können. Weitere Informationen zu Transportregeln in EOP finden Sie unter [Transportregeln](https://go.microsoft.com/fwlink/p/?LinkId=320399).
  
## <a name="audit-logging"></a>Überwachungsprotokollierung
<a name="BKMK_auditlogging"> </a>

Mit der Überwachungsprotokollierung können Sie bestimmte Änderungen von Administratoren an Ihrer Organisation protokollieren. Dank dieser Berichte können Sie gesetzliche Bestimmungen einhalten und Daten, die für Rechtsstreitigkeiten erforderlich sind, aufbewahren. Weitere Informationen finden Sie unter [Überwachungsberichte in EOP](https://go.microsoft.com/fwlink/p/?LinkId=314258).
  
## <a name="data-loss-prevention-dlp"></a>Verhinderung von Datenverlusten (Data Loss Prevention, DLP)
<a name="BKMK_datalossprevention"> </a>

Nicht verfügbar für Kunden der eigenständigen Lösung von EOP. Verhinderung von Datenverlust (Data Loss Prevention, DLP) ermöglicht Ihnen das Bestimmen, Überwachen und Schützen vertraulicher Daten in Ihrer Organisation mittels einer eingehenden Inhaltsanalyse. DLP gewinnt für Nachrichtensysteme von Unternehmen zunehmend an Bedeutung, da geschäftskritische E-Mails vertrauliche Daten enthalten, die geschützt werden müssen. Mit der DLP-Funktion können Sie sensible Daten schützen, ohne die Produktivität der Mitarbeiter zu beeinträchtigen.
  
Sie können DLP-Richtlinien in der Exchange-Verwaltungskonsole konfigurieren, wodurch sich folgende Möglichkeiten ergeben:
  
- Beginnen Sie mit einer vorkonfigurierten Richtlinienvorlage, mit deren Hilfe Sie bestimmte Typen vertraulicher Informationen wie PCI DSS-Daten (Payment Card Industry Data Security Standard), Gramm-Leach-Bliley Act-Daten oder sogar standortspezifisch personenbezogene Informationen (PII) erkennen können.
    
- Nutzen Sie die volle Leistungsfähigkeit vorhandener Transportregelkriterien und -aktionen, und fügen Sie neue Transportregeln hinzu.
    
- Testen Sie die Effektivität Ihrer DLP-Richtlinien vor deren vollständiger Erzwingung.
    
- Integrieren Sie eigene benutzerdefinierte DLP-Richtlinienvorlagen und Typen vertraulicher Informationen.
    
- Erkennen Sie vertrauliche Informationen in E-Mail-Anlagen, -Text oder -Betreffzeilen, und passen Sie die Vertrauensstufe an, bei der Maßnahmen ergreift.
    
- Erkennen Sie vertrauliche Formulardaten mithilfe von Dokumentfingerabdrücken. Dokumentfingerabdrücke helfen Ihnen, problemlos benutzerdefinierte Typen vertraulicher Informationen auf Basis textbasierter Formulare zu erstellen, die Sie zum Definieren von Transportregeln und DLP-Richtlinien verwenden können.
    
- Fügen Sie Richtlinientipps hinzu, die helfen können, Datenverluste zu vermeiden, indem Ihren Outlook 2013-, Outlook Web App- und OWA for Devices-Benutzern ein Hinweis angezeigt wird, und die auch die Effektivität Ihrer Richtlinien verbessern können, indem falsch positive Ergebnisse gemeldet werden können.
    
- Überprüfen Sie Vorfallsdaten in DLP-Berichten, oder fügen Sie Ihre eigene Berichterstellung mithilfe einer neuen Aktion zum Generieren eines Schadensberichts hinzu.
    
> [!NOTE]
> DLP-Richtlinien werden nur auf E-Mails angewendet, die in Ihre oder aus Ihrer Organisation übertragen werden. Auf organisationsinterne E-Mails werden keine DLP-Richtlinien angewendet, es sei denn, Sie führen Exchange Server 2013 mit DLP lokal aus. Dies trifft auch auf DLP-Richtlinientipps zu, mit denen Benutzer über potenzielle Richtlinienverletzungen informiert werden, bevor vertrauliche Informationen versehentlich an nicht autorisierte Personen gesendet werden. 
  
Weitere Informationen zu DLP finden Sie unter [Verhinderung von Datenverlust](https://go.microsoft.com/fwlink/p/?LinkId=320398).
  
## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung
<a name="BKMK_OME_in_EOP"> </a>

Office 365-Nachrichtenverschlüsselung, ein Bestandteil von Azure Information Protection, ist ein Onlinedienst, der es E-Mail-Benutzern erlaubt, an beliebige Personen verschlüsselte E-Mail-Nachrichten zu senden. Lokale Kunden können auf Office 365-Nachrichtenverschlüsselung zugreifen, indem sie Azure Information Protection erwerben und Exchange Online Protection zum Einrichten der Nachrichtenübermittlung über Exchange Online verwenden. Weitere Informationen zu Office 365-Nachrichtenverschlüsselung in Exchange Online finden Sie unter [Office 365-Nachrichtenverschlüsselung](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) in der Exchange Online-Dienstbeschreibung. 
  
## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Features zu Messagingrichtlinien und -einhaltung in EOP-Optionen
<a name="BKMK_OME_in_EOP"> </a>

|**Feature**|**EOP als eigenständige Lösung**|**EOP-Funktionen in Exchange Online**|**Exchange Enterprise CAL mit Diensten**|
|:-----|:-----|:-----|:-----|
|Transportregeln  <br/> |Ja<sup>1</sup> <br/> |Ja<sup>1</sup> <br/> |Ja  <br/> |
|Überwachungsprotokollierung  <br/> |Ja<sup>2</sup> <br/> |Ja  <br/> |Ja  <br/> |
|Verhinderung von Datenverlust (Data Loss Prevention, DLP)  <br/> |Nein  <br/> |Ja  <br/> |Ja<sup>3</sup> <br/> |
|Office 365-Nachrichtenverschlüsselung  <br/> |Ja<sup>4</sup> <br/> |Ja  <br/> |Ja<sup>4</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> In Exchange Online und EOP sind jeweils unterschiedliche Kriterien und Aktionen verfügbar. Eine Auflistung der in EOP verfügbaren Kriterien und Aktionen finden Sie unter [ Transportregelbedingungen ](https://go.microsoft.com/fwlink/p/?LinkId=320392) und [Transportregelaktionen](https://go.microsoft.com/fwlink/p/?LinkId=320393). Eine Auflistung der in Exchange Online verfügbaren Kriterien und Aktionen finden Sie unter [Transportregelkriterien](https://go.microsoft.com/fwlink/p/?LinkId=320394) und [Transportregelaktionen](https://go.microsoft.com/fwlink/p/?LinkId=320395). <br/>
> <sup>2</sup> Die EOP-Überwachungsberichte sind eine Teilmenge der Exchange Online-Überwachungsberichte und enthalten keine Informationen zu Postfächern. <br/>
> <sup>3</sup> DLP-Richtlinientipps sind für Kunden von Exchange Enterprise CAL mit Diensten nicht verfügbar. <br/>
> <sup>4</sup> Wird für lokale Kunden unterstützt, die das Add-On Azure Information Protection erwerben und Exchange Online Protection zum Routen von E-Mails über Exchange Online verwenden. Für die Desktopdarstellung muss zusätzlich zum Add-On Azure Information ProtectionOffice 365 ProPlus erworben werden. <br/>
  

