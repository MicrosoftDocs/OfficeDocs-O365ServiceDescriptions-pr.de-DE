---
title: Exchange Online für Umgebungen in der US-Regierung
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Dieser Artikel bietet eine Übersicht über Funktionsunterschiede zwischen der US Government-Cloud und der kommerziellen Cloud, wie in der Exchange Online-Dienstbeschreibung aufgeführt.
ms.openlocfilehash: b2ea792f6a205cbe6c9031c924a22e7f6d1d3030
ms.sourcegitcommit: 1a212a9f9c8d28090bc0b7c6e20e76d1353dad2e
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/13/2020
ms.locfileid: "44213697"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online für Umgebungen in der US-Regierung

Dieser Artikel bietet eine Übersicht über Funktionsunterschiede zwischen der US Government-Cloud und der kommerziellen Cloud, wie in der [Exchange Online-Dienstbeschreibung](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-service-description)aufgeführt. Exchange Online steht für die Umgebungen Government Community Cloud (gcc), gcc High und Department of Defense (DoD) zur Verfügung.

Weitere Informationen zur Government-Cloud, einschließlich der Berechtigung und des Kaufs, finden Sie unter [Microsoft 365 Government-How to Buy](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Informationen zum Vergleich Office 365er Regierungspläne finden Sie unter [Office 365 Government Plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Informationen zu den erforderlichen Endpunkten beim Verwalten der Netzwerkkonnektivität finden Sie unter [Office 365 US Government gcc High Endpoint](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business)   oder [Office 365 US Government DoD Endpoints](https://docs.microsoft.com/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Neben den Features und Funktionen von Office 365 profitieren Organisationen von den folgenden Features, die für die US Government Cloud-Umgebungen einzigartig sind:

- Der Kunden Inhalt Ihrer Organisation wird logischerweise von Kundeninhalten in den kommerziellen Office 365 Diensten getrennt.

- Der Kunden Inhalt Ihrer Organisation wird in Rest innerhalb der USA gespeichert.

- Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.

- Die staatlichen Cloud-Umgebungen entsprechen Zertifizierungen und Akkreditierungen, die häufig für US-Kunden des öffentlichen Sektors erforderlich sind.

Es ist unsere allgemeine Absicht, alle kommerziellen Features und Funktionen von Exchange für die Government-Cloud-Umgebung bereitzustellen. Allerdings stehen einige Funktionen aufgrund der Anforderungen von Government Cloud-Kunden nicht zur Verfügung. Andere Features kommen in die Regierungs Umgebungen, sind aber noch nicht verfügbar. In den folgenden Abschnitten finden Sie Informationen zur Verfügbarkeit von Features in den Government-Cloud-Umgebungen.

## <a name="exchange-online-features"></a>Exchange Online-Features

In der folgenden Tabelle wird erläutert, ob die angegebenen Exchange Online Features in den Umgebungen gcc, gcc High und DoD verfügbar sind. Wenn es Nuancen hinsichtlich der Unterstützungserklärung gibt (oder deren Fehlen), wird zusätzlicher Kontext bereitgestellt.

|**Funktionsbereich**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|:-----|:-----|:-----|:-----|:-----|
|**[Planung und Bereitstellung](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Unterstützung für Hybridbereitstellung|Ja|Ja|Ja|Für die Koexistenz mit Exchange Server lokal benötigt Microsoft mindestens einen Exchange Server 2013-Client Zugriffs Server (oder Exchange Server 2016.). Exchange Server 2010 und früher werden nicht unterstützt.|
|Unterstützung für IMAP-Migration|Ja|Ja|Ja||
|Unterstützung für Übernahmemigration|Ja|Ja|Ja||
|Unterstützung für phasenweise Migration|Ja|Ja|Ja|Die GSuite-Migration wird für gcc High und DoD nicht unterstützt. Weitere Informationen finden Sie unter <a href="https://docs.microsoft.com/exchange/mailbox-migration/perform-g-suite-migration">Durchführen einer GSuite Migration</a>.|
|**[Berechtigungen](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Rollenbasierte Berechtigungen|Ja|Ja|Ja||
|Rollengruppen|Ja|Ja|Ja||
|Rollenzuweisungsrichtlinien|Ja|Ja|Ja||
|**[Messagingrichtlinie und -einhaltung](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Archivieren von Exchange Online-basierten Postfächern|Ja|Ja|Ja||
|Cloudbasierte Archivierung von lokalen Postfächern|Ja|Ja|Ja||
|Verwaltung von Nachrichtendatensätzen (Messaging Records Management, MRM) |Ja|Ja|Ja||
|Manuelle Aufbewahrungsrichtlinien, Bezeichnungen und Tags |Ja|Ja|Ja||
|Verschlüsselung von Daten im Ruhezustand (BitLocker)|Ja|Ja|Ja||
|IRM mit Azure Information Protection|Ja|Ja|Ja|Weitere Informationen zu den Einschränkungen von AIP in gcc High und DoD finden Sie unter <a href="https://docs.microsoft.com/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government Service Description</a>.<br><br>Azure Information Protection ist nicht in G1/F3 enthalten, kann aber als separates Add-on erworben werden und aktiviert die unterstützten IRM-Funktionen (Information Rights Management, Verwaltung von Informationsrechten). Einige Azure Information Protection-Features erfordern ein Abonnement für Office 365 ProPlus, das nicht in Office 365 Government G1 oder Office 365 Government F3 enthalten ist.|
|IRM mit Windows Server AD RMS|Ja|Ja|Ja|  Windows Server AD RMS ist ein lokaler Server, der separat erworben und verwaltet werden muss, um die unterstützten IRM-Funktionen zu aktivieren.|
|Office 365-Nachrichtenverschlüsselung|Ja|Ja|Ja|Weitere Informationen finden Sie unter [Office 365 Nachrichten Verschlüsselungs Verhalten in gcc High/DoD-Grenze](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) in diesem Artikel und <a href="https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">einzigartige Merkmale der Office 365 Nachrichtenverschlüsselung in einer gcc-hoch Bereitstellung</a>, die Verhaltens Nuancen von Office 365 Nachrichtenverschlüsselung beim Senden von Nachrichten zwischen gcc High/DoD-und nicht-gcc-Benutzern mit hoher/DoD-Funktion dokumentiert.|
|Kundenschlüssel|Ja|Ja|Ja|Erfordert G5-Dienstplan.|
|S/MIME|Ja|Ja|Ja||
|In-Situ-Speicher und Beweissicherungsverfahren|Ja|Ja|Ja|Erfordert G3-oder G5-Dienstplan.|
|Compliance-eDiscovery|Ja|Ja|Ja||
|Nachrichtenflussregeln|Ja|Ja|Ja||
|Data loss prevention|Ja|Ja|Ja|Erfordert G3-oder G5-Dienstplan.|
|Journale|Ja|Ja|Ja||
|**[Antispam- und Antischadsoftwareschutz](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Integrierter Antispamschutz|Ja|Ja|Ja||
|Customize anti-spam policies|Ja|Ja|Ja||
|Integrierter Antischadsoftwareschutz|Ja|Ja|Ja||
|Customize anti-malware policies|Ja|Ja|Ja||
|Quarantäne - Verwaltung durch Administrator|Ja|Ja|Ja||
|Quarantäne - Selbstverwaltung durch Endbenutzer|Ja|Ja|Ja||
|Advanced Threat Protection|Ja|Ja|Ja|Erfordert G5-Service Plan (oder Erwerb von Add-on).<br><br>Anti-Phishing für Benutzer-und Domänen Identitätswechsel und Spoof Intelligence steht in gcc High und DoD noch nicht zur Verfügung.|
|**[Nachrichtenübermittlung](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Benutzerdefiniertes Routing von ausgehenden e-Mails|Ja|Ja|Ja||
|Secure messaging with a trusted partner|Ja|Ja|Ja||
|Conditional mail routing|Ja|Ja|Ja||
|Hinzufügen eines Partners zu einer eingehenden Liste sicherer Adressen|Ja|Ja|Ja||
|Hybrides E-Mail-Routing|Ja|Ja|Ja||
|**[Empfänger](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Kapazitätswarnungen|Ja|Ja|Ja||
|Unwichtige Elemente|Ja|Ja|Ja||
|MailTips|Ja|Ja|Ja||
|Stellvertretungszugriff|Ja|Ja|Ja||
|Posteingangsregeln|Ja|Ja|Ja||
|Verbundene Konten|Ja|Nein|Nein|Dieses Feature wird in gcc High oder DoD aufgrund von Einschränkungen für ausgehende Verbindungen mit Drittanbieterdiensten nicht unterstützt. Weitere Informationen zu den betroffenen Features finden Sie unter [Connectivity with Third-Party Services](#connectivity-with-third-party-services) in this article.|
|Inaktive Postfächer|Ja|Ja|Ja|Erfordert G3-oder G5-Dienstplan.|
|Offlineadressbuch|Ja|Ja|Ja||
|Adressbuchrichtlinien|Ja|Ja|Ja||
|Hierarchisches Adressbuch|Ja|Ja|Ja||
|Adresslisten und globale Adressliste|Ja|Ja|Ja||
|Office 365-Gruppen|Ja|Ja|Ja|Gastzugriff auf Office 365 Gruppen wird in gcc High-und DoD-Umgebungen nicht unterstützt. Weitere Informationen finden Sie unter <a href="https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity</a>.|
|Verteilergruppen|Ja|Ja|Ja||
|Externe Kontakte (global)|Ja|Ja|Ja|Vorbehaltlich der Einschränkungen der org-Beziehungs Zusammenarbeit in gcc-High-und DoD-Umgebungen. |
|Kontaktverknüpfung mit sozialen Netzwerken|Ja|Nein|Nein|Dieses Feature wird in gcc High oder DoD nicht unterstützt.|
|Ressourcenpostfächer|Ja|Ja|Ja||
|Konferenzraumverwaltung|Ja|Ja|Ja||
|Abwesenheitsantworten|Ja|Ja|Ja||
|Internet Kalenderfreigabe|Ja|Nein|Nein|In gcc High funktioniert die Veröffentlichung/Freigabe von Internet Kalendern für eingehende Verbindungen mit Kalendern, die von gcc-hoch Benutzern freigegeben werden, jedoch nicht für gcc-hoch Benutzer, die ausgehende zu einem freigegebenen Kalender außerhalb von gcc High verbinden.<br><br>In DoD – die Internet Kalenderfreigabe wird aufgrund der Anforderung einer eingehenden/ausgehenden Verbindung in dieser Umgebung nicht unterstützt.|
|**[Berichterstellungsfeatures und Tools zur Problembehandlung](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Microsoft 365 Admin Center-Berichte|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Weitere Informationen finden Sie im Abschnitt <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Plattformfeatures</a> der Office 365 US Government-Dienstbeschreibung für Updates/aktuelle Verfügbarkeit.|
|Webdienste Berichte|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Weitere Informationen finden Sie im Abschnitt <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Plattformfeatures</a> der Office 365 US Government-Dienstbeschreibung für Updates/aktuelle Verfügbarkeit.|
|Message trace|Ja|Ja|Ja||
|Überwachungsberichte|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Weitere Informationen finden Sie im Abschnitt <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Plattformfeatures</a> der Office 365 US Government-Dienstbeschreibung für Updates/aktuelle Verfügbarkeit.|
|Unified Messaging-Berichte|Ja|Nein|Nein||
|**[Freigabe und Zusammenarbeit](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Verbundfreigabe (einschließlich Kalenderveröffentlichung)|Ja|Ja|Ja|Einschränkungen bestehen sowohl in gcc High als auch in DoD. Siehe [Frei/Gebucht-Partnerverbund](#freebusy-federation) in diesem Artikel.|
|Websitepostfächer|Ja|Ja|Ja||
|Öffentliche Ordner|Ja|Ja|Ja||
|**[Clients und mobile Geräte](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Outlook für Windows|Ja|Ja|Ja|Um die Anforderungen an gcc High and DoD Compliance erfüllen zu können, müssen Sie mindestens Version 1803 von Office 365 ProPlus betreiben. Office 365 ProPlus ist nicht mit G1 oder F3 enthalten.|
|Outlook im Web|Ja|Ja|Ja||
|Outlook für Mac|Ja|Ja|Ja|Um die Anforderungen an gcc High and DoD Compliance erfüllen zu können, müssen Sie mindestens Version 1803 von Office 365 ProPlus betreiben. Office 365 ProPlus ist nicht mit G1 oder F3 enthalten.|
|Outlook für iOS und Android|Ja|Ja|Ja||
|Exchange ActiveSync|Ja|Ja|Ja||
|Verwaltung mobiler Geräte in Office 365|Ja|Ja|Ja||
|POP und IMAP|Ja|Ja|Ja||
|SMTP|Ja|Ja|Ja||
|Unterstützung für EWS-Anwendungen|Ja|Ja|Ja||
|**[Sprachnachrichtendienste](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Voicemail|Nein|Nein|Nein|Die Integration von lokalen IP-PBX-Systemen mit Exchange Online Unified Messaging wird nicht unterstützt.|
|Integration von Voicemail und Fax eines Drittanbieters|Nein|Nein|Nein|Die Integration von lokalen IP-PBX-Systemen mit Exchange Online Unified Messaging wird nicht unterstützt.|
|Interoperabilität von Voicemails eines Drittanbieters|Nein|Nein|Nein|Die Integration von lokalen IP-PBX-Systemen mit Exchange Online Unified Messaging wird nicht unterstützt.|
|Skype for Business Integration|Ja|Ja|Ja||
|**[Hohe Verfügbarkeit und Geschäftskontinuität](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Post Fach Replikation in Datencentern|Ja|Ja|Ja||
|Wiederherstellung gelöschter Postfächer|Ja|Ja|Ja||
|Wiederherstellung gelöschter Elemente|Ja|Ja|Ja||
|Wiederherstellung einzelner Elemente|Ja|Ja|Ja||
|**[Interoperabilität, Konnektivität und Kompatibilität](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Anwesenheit in OWA und Outlook|Ja|Ja|Ja||
|SharePoint-Interoperabilität|Ja|Ja|Ja||
|Unterstützung für EWS-Konnektivität|Ja|Ja|Ja||
|Unterstützung für SMTP-Relay|Ja|Ja|Ja||
|**[Einrichtung und Verwaltung in Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Zugriff auf das Microsoft Office 365-Portal|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Weitere Informationen finden Sie im Abschnitt <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Plattformfeatures</a> der Office 365 US Government-Dienstbeschreibung für Updates/aktuelle Verfügbarkeit.|
|Microsoft 365 Admin Center-Zugriff|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Weitere Informationen finden Sie im Abschnitt <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Plattformfeatures</a> der Office 365 US Government-Dienstbeschreibung für Updates/aktuelle Verfügbarkeit.|
|Zugriff auf die Exchange-Verwaltungskonsole|Ja|Ja|Ja||
|Zugriff auf die remote verwendete Windows PowerShell|Ja|Ja|Ja||
|ActiveSync-Richtlinien für mobile Geräte|Ja|Ja|Ja||
|Verwendungsberichte|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Weitere Informationen finden Sie im Abschnitt <a href="https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Plattformfeatures</a> der Office 365 US Government-Dienstbeschreibung für Updates/aktuelle Verfügbarkeit.|
|**[Erweitern des Diensts – Anpassung, Add-Ins und Ressourcen](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC hoch**|**DoD**|**Wichtige Überlegungen**|
|Outlook-Add-Ins und Outlook-MAPI|Ja|Ja|Ja|Nur einige OWA-und Outlook-Add-Ins sind in gcc High und DoD verfügbar. Weitere Informationen finden Sie unter [Add-Ins in Outlook und Outlook Web App](#add-insin-outlook-and-outlook-web-app) in diesem Artikel.|

## <a name="feature-nuances-within-gcc-high-and-dod-environment"></a>Funktions Nuancen innerhalb der gcc High-und DoD-Umgebung

### <a name="connectivity-with-third-party-services"></a>Konnektivität mit Drittanbieterdiensten  

Sowohl gcc High-als auch DoD-Umgebungen sind eingeschränkte Umgebungen, die eine explizite Genehmigung und Konfiguration von ausgehenden Verbindungen erfordern. Darüber hinaus kann Microsoft keine Anforderungen erfüllen, um ausgehenden Zugriff von diesen Umgebungen auf kommerzielle Cloud-Dienste (kommerzielle Office 365, Google GSuite, Amazon Webdienste usw.) zuzulassen.     

Aufgrund dieser Einschränkungen werden Features, die von dieser ausgehenden Verbindung von den gcc-High/DoD-Umgebungen abhängen, in der Regel nicht unterstützt, einschließlich: 

- Verbundene Konten &mdash; Benutzer können keine Konten hinzufügen/synchronisieren (Google, POP/IMAP usw.). 

- Unterstützung für Dateispeicher Anbieter von Drittanbietern &mdash; nur das OneDrive for Business-Konto des Benutzers *innerhalb von gcc High/DoD*   kann über die verschiedenen Outlook-Clients in Verbindung mit dem Anfügen/Freigeben von Dateien auf diese zugreifen. Speicherkonten von Drittanbietern (Dropbox, Box, Google Drive) können nicht hinzugefügt werden. 

- Konnektivität mit sozialen Netzwerken wie Facebook oder LinkedIn. 

### <a name="azure-active-directoryb2b-collaboration"></a>Azure Active Directory B2B-Zusammenarbeit 

Azure Active Directory B2B-Zusammenarbeit wird derzeit nur zwischen Organisationen unterstützt, die sowohl in der Azure US Government Cloud als auch in der Unterstützung der B2B-Zusammenarbeit stehen.

Darüber hinaus werden B2B-Benutzer als Gäste in Office 365 Gruppen in gcc High-und DoD-Umgebungen nicht unterstützt. 

Weitere Informationen und die neuesten Updates finden Sie unter [Azure Government Security + Identity](https://docs.microsoft.com/azure/azure-government/documentation-government-services-securityandidentity). 

### <a name="office-365-message-encryptionbehavior-across-gcc-highdod-boundary"></a>Office 365 Nachrichten Verschlüsselungs Verhalten über gcc High/DoD-Grenze hinweg 

Wenn Sie Office 365 Nachrichtenverschlüsselung in einer gcc-High-Umgebung verwenden möchten, sollten Sie sich dieser eindeutigen Merkmale hinsichtlich der Empfänger Erfahrung bewusst sein:  

- Beim Senden von verschlüsselten e-Mail-Nachrichten von gcc High oder DoD an Empfänger in derselben Umgebung:
    
    - Absender können e-Mails manuell in Outlook für PC und Mac und Outlook im Internet verschlüsseln, oder Organisationen können eine Richtlinie zum Verschlüsseln von e-Mails mithilfe von Exchange-Nachrichtenfluss Regeln einrichten. 
    
    - Empfänger in gcc High/DoD erhalten dieselbe Inline Leseerfahrung in Outlook für PC und Mac sowie Outlook im Internet wie alle anderen Office 365-Benutzer. 

<!-- end list -->

- Beim Senden von verschlüsselten e-Mail-Nachrichten von gcc High oder DoD an Empfänger außerhalb dieser Umgebung (einschließlich gcc und Commercial):
    
    - Absender innerhalb von gcc High/DoD können verschlüsselte e-Mails außerhalb der gcc-Obergrenze (High/DoD) senden. 
    
    - Alle Empfänger außerhalb des GCC High/DoD, einschließlich kommerzieller Office 365 Benutzer, Outlook.com-Benutzer und anderer Benutzer anderer e-Mail-Anbieter, erhalten eine Wrapper-e-Mail. Mit dieser Wrapper-e-Mail wird der Empfänger an das OM-Portal umgeleitet, in dem der Empfänger die Nachricht lesen und beantworten kann. 

Weitere Informationen und die neuesten Updates finden Sie unter [Compare Versionen of OM](https://docs.microsoft.com/microsoft-365/compliance/ome-version-comparison?view=o365-worldwide).

### <a name="freebusy-federation"></a>Frei/Gebucht-Partnerverbund

Die Verbundfreigabe, einschließlich Frei/Gebucht-Informationen, unterliegt derzeit mehreren wichtigen Einschränkungen in den gcc-High-und DoD-Umgebungen.

In der gcc-hoch Umgebung:

- Die Verbundvertrauensstellung (einschließlich bidirektionaler frei/gebucht-Freigaben) wird zwischen Mandanten in gcc hoch und über hybride Koexistenz (Exchange 2013 oder höher) unterstützt.

- Die Verbundfreigabe wird zwischen Mandanten in gcc High und gcc oder Office 365 kommerziell nicht unterstützt. Ausgehende Verbindungen von der gcc-hoch Umgebung zu kommerziellen Clouds (einschließlich gcc und Office 365 Commercial) sind zu diesem Zeitpunkt nicht zulässig. Daher können gcc-hoch Benutzer nicht die erforderliche ausgehende Anforderung an gcc/Commercial weitergeben, um auf freigegebene Kalenderinformationen zuzugreifen.

In der DoD-Umgebung:

  - Die Verbundvertrauensstellung (einschließlich Freigabe von Frei/Gebucht-Informationen) wird derzeit nur zwischen Mandanten innerhalb der DoD-Umgebung unterstützt. Es wird nicht zwischen DoD-Mandanten und gcc-oder kommerziellen Mandanten unterstützt.

### <a name="client-configuration"></a>Client Konfiguration 

Zusätzliche Schritte sind bei der Bereitstellung und Konfiguration von Office ProPlus (einschließlich Outlook) beteiligt. Eine ausführliche Beschreibung dieser Schritte finden Sie unter [Leitfaden für die Bereitstellung von Microsoft 365-Apps für Unternehmen in einer gcc-hoch-oder DoD-Umgebung ](https://docs.microsoft.com/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

Outlook für IOS und Android steht auch für gcc High-und DoD-Umgebungen zur Verfügung. Weitere Informationen zu Funktionseinschränkungen und-Verwaltung in diesen Umgebungen finden Sie unter [Verwenden von Outlook für IOS und Android in der Government Community Cloud](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud).

### <a name="add-insin-outlook-and-outlook-web-app"></a>Add-Ins in Outlook und Outlook Web App  

Nur einige OWA-und Outlook-Add-Ins sind in gcc High und DoD verfügbar. Meine Vorlagen und vorgeschlagene Besprechungen sind verfügbar und werden erwartet, dass Sie funktionieren. Nur die fünf Standard-OWA-Add-Ins werden unterstützt. Die Integration in Drittanbieteranwendungen ist möglich, diese Integrationen werden jedoch nicht von den Microsoft-Konformitäts Zusagen für gcc High oder DoD abgedeckt. Kunden sollten sich vor dem Konfigurieren des Add-ons für Ihre Organisation mit Drittanbieter-Methoden für Datenverarbeitung und Compliance-Zusagen vertraut machen.
