---
title: Messagingrichtlinie und Compliance in Exchange Online Protection
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- messaging-policy-and-compliance-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 1074f583-523f-4dca-9012-c9b93aae96b7
description: In diesem Artikel erfahren Sie mehr über messaging policy and compliance features in Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 81228b13036e831df630cca6f27b4ad285705f29
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653347"
---
# <a name="messaging-policy-and-compliance-in-exchange-online-protection"></a>Messagingrichtlinie und Compliance in Exchange Online Protection

Microsoft Exchange Online Protection (EOP) bietet Messagingrichtlinien- und Compliancefeatures, mit deren Hilfe Sie Ihre E-Mail-Daten verwalten können.

Sie suchen nach Informationen zu allen EOP-Funktionen? Weitere Informationen [finden Exchange Online Protection Dienstbeschreibung](exchange-online-protection-service-description.md).

## <a name="mail-flow-rules"></a>Nachrichtenflussregeln

Nachrichtenflussregeln (auch als Transportregeln bezeichnet) bieten Ihnen die Flexibilität, ihre eigenen unternehmensspezifischen Richtlinien auf E-Mails anzuwenden. Nachrichtenflussregeln sind aus flexiblen Kriterien, mit denen Sie Bedingungen, Ausnahmen und Aktionen definieren können, die basierend auf den Kriterien zu ergreifen sind. Weitere Informationen finden Sie unter [Nachrichtenflussregeln (Transportregeln) in Exchange Online Protection](/microsoft-365/security/office-365-security/mail-flow-rules-transport-rules-0).

## <a name="audit-logging"></a>Überwachungsprotokollierung

Mit der Überwachungsprotokollierung können Sie bestimmte Änderungen von Administratoren an Ihrer Organisation protokollieren. Dank dieser Berichte können Sie gesetzliche Bestimmungen einhalten und Daten, die für Rechtsstreitigkeiten erforderlich sind, aufbewahren. Weitere Informationen finden Sie unter [Überwachungsberichte in EOP](/microsoft-365/security/office-365-security/auditing-reports-in-eop).

## <a name="data-loss-prevention-dlp"></a>Verhinderung von Datenverlust (Data Loss Prevention, DLP)

Nicht verfügbar für Kunden der eigenständigen Lösung von EOP. Verhinderung von Datenverlust (Data Loss Prevention, DLP) ermöglicht Ihnen das Bestimmen, Überwachen und Schützen vertraulicher Daten in Ihrer Organisation mittels einer eingehenden Inhaltsanalyse. DLP gewinnt für Nachrichtensysteme von Unternehmen zunehmend an Bedeutung, da geschäftskritische E-Mails vertrauliche Daten enthalten, die geschützt werden müssen. Mit dem DLP-Feature können Sie vertrauliche Daten schützen, ohne die Produktivität der Mitarbeiter zu beeinträchtigen.

Sie können DLP-Richtlinien in der Exchange-Verwaltungskonsole konfigurieren, wodurch sich folgende Möglichkeiten ergeben:

- Beginnen Sie mit einer vorkonfigurierten Richtlinienvorlage, mit deren Hilfe Sie bestimmte Typen vertraulicher Informationen wie PCI DSS-Daten (Payment Card Industry Data Security Standard), Gramm-Leach-Bliley Act-Daten oder sogar standortspezifisch personenbezogene Informationen (PII) erkennen können.

- Nutzen Sie die volle Leistung der vorhandenen Kriterien und Aktionen der Nachrichtenflussregel, und fügen Sie neue Nachrichtenflussregeln hinzu.

- Testen Sie die Effektivität Ihrer DLP-Richtlinien vor deren vollständiger Erzwingung.

- Integrieren Sie eigene benutzerdefinierte DLP-Richtlinienvorlagen und Typen vertraulicher Informationen.

- Erkennen Sie vertrauliche Informationen in E-Mail-Anlagen, -Text oder -Betreffzeilen, und passen Sie die Vertrauensstufe an, bei der Maßnahmen ergreift.

- Erkennen Sie vertrauliche Formulardaten mithilfe von Dokumentfingerabdrücken. Mithilfe der Dokumentfingerabdrücke können Sie ganz einfach benutzerdefinierte Typen vertraulicher Informationen basierend auf textbasierten Formularen erstellen, mit deren Hilfe Sie Nachrichtenflussregeln und DLP-Richtlinien definieren können.

- Fügen Sie Richtlinien-Tipps hinzu, die dazu beitragen kann, Datenverluste zu reduzieren, indem Sie Ihren Outlook 2013-, Outlook- und OWA for Devices-Benutzern eine Benachrichtigung anzeigen und die Effektivität Ihrer Richtlinien verbessern, indem falsch positive Berichte ermöglicht werden.

- Überprüfen Sie Vorfallsdaten in DLP-Berichten, oder fügen Sie Ihre eigene Berichterstellung mithilfe einer neuen Aktion zum Generieren eines Schadensberichts hinzu.

> [!NOTE]
> DLP-Richtlinien werden nur auf E-Mails angewendet, die in Ihre oder aus Ihrer Organisation übertragen werden. Auf organisationsinterne E-Mails werden keine DLP-Richtlinien angewendet, es sei denn, Sie führen Exchange Server 2013 mit DLP lokal aus. Dies trifft auch auf DLP-Richtlinientipps zu, mit denen Benutzer über potenzielle Richtlinienverletzungen informiert werden, bevor vertrauliche Informationen versehentlich an nicht autorisierte Personen gesendet werden.

Weitere Informationen zu DLP finden Sie unter Verhinderung von Datenverlust [in Exchange Online](/exchange/security-and-compliance/data-loss-prevention/data-loss-prevention).

## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

Office 365-Nachrichtenverschlüsselung, ein Bestandteil von Azure Information Protection, ist ein Onlinedienst, der es E-Mail-Benutzern erlaubt, an beliebige Personen verschlüsselte E-Mail-Nachrichten zu senden. Lokale Kunden können auf Office 365-Nachrichtenverschlüsselung zugreifen, indem sie Azure Information Protection erwerben und Exchange Online Protection zum Einrichten der Nachrichtenübermittlung über Exchange Online verwenden. Weitere Informationen zu Office 365-Nachrichtenverschlüsselung in Exchange Online finden Sie unter [Office 365-Nachrichtenverschlüsselung](../exchange-online-service-description/message-policy-and-compliance.md#office-365-message-encryption) in Exchange Online Dienstbeschreibung.

## <a name="messaging-policy-and-compliance-features-across-eop-options"></a>Features zu Messagingrichtlinien und -einhaltung in EOP-Optionen

| Feature | EOP als eigenständige Lösung | EOP-Features in <br/> Exchange Online | Exchange Enterprise <br/> CAL mit Diensten |
|:-----|:-----|:-----|:-----|
|Nachrichtenflussregeln|Ja<sup>1</sup>|Ja<sup>1</sup>|Ja<sup>1, 3</sup>|
|Überwachungsprotokollierung|Ja<sup>2</sup>|Ja|Ja|
|Verhinderung von Datenverlust (Data Loss Prevention, DLP)|Nein|Ja|Ja<sup>3</sup>|
|Office 365-Nachrichtenverschlüsselung|Ja<sup>4</sup>|Ja|Ja<sup>4</sup>|

> [!NOTE]
> <sup>1</sup> Die verfügbaren Nachrichtenflussregelbedingungen, Ausnahmen und Aktionen unterscheiden sich geringfügig zwischen EOP und Exchange Online. Diese Unterschiede werden in Nachrichtenflussregelbedingungen und Ausnahmen [(Prädikate) in](/Exchange/security-and-compliance/mail-flow-rules/conditions-and-exceptions) Exchange Online und [Nachrichtenflussregelaktionen in](/Exchange/security-and-compliance/mail-flow-rules/mail-flow-rule-actions)Exchange Online . <br/>
> <sup>2</sup> Die EOP-Überwachungsberichte sind eine Teilmenge der Exchange Online-Überwachungsberichte und enthalten keine Informationen zu Postfächern.<br/>
> <sup>3</sup> DLP-Richtlinientipps sind für Kunden von Exchange Enterprise CAL mit Diensten nicht verfügbar.<br/>
> <sup>4</sup> Wird für lokale Kunden unterstützt, die das Add-On Azure Information Protection erwerben und Exchange Online Protection zum Routen von E-Mails über Exchange Online verwenden. Für die Desktoperfahrung muss zusätzlich zum Azure Information Protection-Add-On Microsoft 365 Apps for Enterprise erworben werden. <br/>