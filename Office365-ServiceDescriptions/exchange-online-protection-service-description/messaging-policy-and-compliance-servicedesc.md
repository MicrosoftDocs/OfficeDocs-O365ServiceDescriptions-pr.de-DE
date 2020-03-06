---
title: Messagingrichtlinie und -kompatibilität
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: Microsoft Exchange Online Protection (EoP) bietet Funktionen für Messagingrichtlinien und-Kompatibilität, mit denen Sie Ihre e-Mail-Daten verwalten können.
ms.openlocfilehash: ee30f74e9b76c1344b91a6c31352cf857dfcfc5c
ms.sourcegitcommit: b957054b6d0a96dbb2b9ced39b5c9935aa07111c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2020
ms.locfileid: "42545838"
---
# <a name="messaging-policy-and-compliance"></a>Messagingrichtlinie und -kompatibilität

Microsoft Exchange Online Protection (EoP) bietet Funktionen für Messagingrichtlinien und-Kompatibilität, mit denen Sie Ihre e-Mail-Daten verwalten können.

Sie suchen nach Informationen zu allen EOP-Funktionen? Siehe [Exchange Online Protection-Dienstbeschreibung](exchange-online-protection-service-description.md).

## <a name="mail-flow-rules"></a>Nachrichtenflussregeln

Nachrichtenfluss Regeln (auch als Transportregeln bezeichnet) bieten Ihnen die Flexibilität, eigene unternehmensspezifische Richtlinien auf e-Mails anzuwenden. Nachrichtenfluss Regeln bestehen aus flexiblen Kriterien, mit denen Sie Bedingungen, Ausnahmen und Aktionen basierend auf den Kriterien definieren können. Weitere Informationen finden Sie unter [Mail Flow Rules (Transport Rules) in Exchange Online Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0).

## <a name="audit-logging"></a>Überwachungsprotokollierung

Mit der Überwachungsprotokollierung können Sie bestimmte Änderungen von Administratoren an Ihrer Organisation protokollieren. Dank dieser Berichte können Sie gesetzliche Bestimmungen einhalten und Daten, die für Rechtsstreitigkeiten erforderlich sind, aufbewahren. Weitere Informationen finden Sie unter [Überwachungsberichte in EOP](https://docs.microsoft.com/microsoft-365/security/office-365-security/auditing-reports-in-eop).

## <a name="data-loss-prevention-dlp"></a>Verhinderung von Datenverlusten (Data Loss Prevention, DLP)

Nicht verfügbar für Kunden der eigenständigen Lösung von EOP. Verhinderung von Datenverlust (Data Loss Prevention, DLP) ermöglicht Ihnen das Bestimmen, Überwachen und Schützen vertraulicher Daten in Ihrer Organisation mittels einer eingehenden Inhaltsanalyse. DLP gewinnt für Nachrichtensysteme von Unternehmen zunehmend an Bedeutung, da geschäftskritische E-Mails vertrauliche Daten enthalten, die geschützt werden müssen. Mit dem DLP-Feature können Sie vertrauliche Daten schützen, ohne die Produktivität der Mitarbeiter zu beeinträchtigen.

Sie können DLP-Richtlinien in der Exchange-Verwaltungskonsole konfigurieren, wodurch sich folgende Möglichkeiten ergeben:

- Beginnen Sie mit einer vorkonfigurierten Richtlinienvorlage, mit deren Hilfe Sie bestimmte Typen vertraulicher Informationen wie PCI DSS-Daten (Payment Card Industry Data Security Standard), Gramm-Leach-Bliley Act-Daten oder sogar standortspezifisch personenbezogene Informationen (PII) erkennen können.

- Verwenden Sie die vollständige Leistungsfähigkeit vorhandener Nachrichtenfluss Regelkriterien und-Aktionen, und fügen Sie neue Nachrichtenfluss Regeln hinzu.

- Testen Sie die Effektivität Ihrer DLP-Richtlinien vor deren vollständiger Erzwingung.

- Integrieren Sie eigene benutzerdefinierte DLP-Richtlinienvorlagen und Typen vertraulicher Informationen.

- Erkennen Sie vertrauliche Informationen in E-Mail-Anlagen, -Text oder -Betreffzeilen, und passen Sie die Vertrauensstufe an, bei der Maßnahmen ergreift.

- Erkennen Sie vertrauliche Formulardaten mithilfe von Dokumentfingerabdrücken. Mit dem Dokument Fingerabdruck können Sie auf einfache Weise benutzerdefinierte Typen vertraulicher Informationen basierend auf textbasierten Formularen erstellen, die Sie zum Definieren von Nachrichtenfluss Regeln und DLP-Richtlinien verwenden können.

- Fügen Sie Richtlinien Tipps hinzu, die zur Verringerung von Datenverlusten beitragen können, indem Sie eine Mitteilung an Ihre Outlook 2013, Outlook im Internet und OWA für mobile Geräte Benutzer anzeigen und außerdem die Effektivität Ihrer Richtlinien verbessern, indem Sie eine falsch positive Berichterstellung zulassen.

- Überprüfen Sie Vorfallsdaten in DLP-Berichten, oder fügen Sie Ihre eigene Berichterstellung mithilfe einer neuen Aktion zum Generieren eines Schadensberichts hinzu.

> [!NOTE]
> DLP-Richtlinien werden nur auf E-Mails angewendet, die in Ihre oder aus Ihrer Organisation übertragen werden. Auf organisationsinterne E-Mails werden keine DLP-Richtlinien angewendet, es sei denn, Sie führen Exchange Server 2013 mit DLP lokal aus. Dies trifft auch auf DLP-Richtlinientipps zu, mit denen Benutzer über potenzielle Richtlinienverletzungen informiert werden, bevor vertrauliche Informationen versehentlich an nicht autorisierte Personen gesendet werden.

Weitere Informationen zu DLP finden Sie unter [Verhinderung von Datenverlust in Exchange Online](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).

## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

Office 365-Nachrichtenverschlüsselung, ein Bestandteil von Azure Information Protection, ist ein Onlinedienst, der es E-Mail-Benutzern erlaubt, an beliebige Personen verschlüsselte E-Mail-Nachrichten zu senden. Lokale Kunden können auf Office 365-Nachrichtenverschlüsselung zugreifen, indem sie Azure Information Protection erwerben und Exchange Online Protection zum Einrichten der Nachrichtenübermittlung über Exchange Online verwenden. Weitere Informationen zur Office 365 Nachrichtenverschlüsselung in Exchange Online finden Sie unter [Office 365 Nachrichtenverschlüsselung](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) in der Exchange Online-Dienstbeschreibung.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Features zu Messagingrichtlinien und -einhaltung in EOP-Optionen

|**Feature**|**EOP als eigenständige Lösung**|**EoP-Features <br/> in Exchange Online**|**Exchange Enter <br/> Prise CAL mit Diensten**|
|:-----|:-----|:-----|:-----|
|Nachrichtenflussregeln|Ja<sup>1</sup>|Ja<sup>1</sup>|Ja<sup>1, 3</sup>|
|Überwachungsprotokollierung|Ja<sup>2</sup>|Ja|Ja|
|Verhinderung von Datenverlusten (Data Loss Prevention, DLP)|Nein|Ja|Ja<sup>3</sup>|
|Office 365-Nachrichtenverschlüsselung|Ja<sup>4</sup>|Ja|Ja<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> die verfügbaren Nachrichtenfluss Regelbedingungen, Ausnahmen und Aktionen unterscheiden sich geringfügig zwischen EoP und Exchange Online. Diese Unterschiede werden in [Nachrichtenfluss Regel-Bedingungen und-Ausnahmen (Prädikate) in Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) -und [Nachrichtenfluss Regelaktionen in Exchange Online](https://docs.microsoft.com/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)aufgeführt. <br/>
> <sup>2</sup> Die EOP-Überwachungsberichte sind eine Teilmenge der Exchange Online-Überwachungsberichte und enthalten keine Informationen zu Postfächern. <br/>
> <sup>3</sup> DLP-Richtlinientipps sind für Kunden von Exchange Enterprise CAL mit Diensten nicht verfügbar. <br/>
> <sup>4</sup> Wird für lokale Kunden unterstützt, die das Add-On Azure Information Protection erwerben und Exchange Online Protection zum Routen von E-Mails über Exchange Online verwenden. Für die Desktopdarstellung muss zusätzlich zum Add-On Azure Information ProtectionOffice 365 ProPlus erworben werden. <br/>
