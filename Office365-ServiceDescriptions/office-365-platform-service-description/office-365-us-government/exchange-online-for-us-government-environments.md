---
title: Exchange Online for US Government Environments
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Dieser Artikel bietet eine Übersicht über die Funktionsunterschiede zwischen der US Government Cloud und der kommerziellen Cloud, wie in der Exchange Online-Dienstbeschreibung aufgeführt.
ms.openlocfilehash: 2ecef2aeaa9c216e715f1084be022c5c4d0cce32
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173970"
---
# <a name="exchange-online-for-us-government-environments"></a>Exchange Online for US Government Environments

Dieser Artikel bietet eine Übersicht über die Funktionsunterschiede zwischen der US Government Cloud und der kommerziellen Cloud, wie in der [Exchange Online-Dienstbeschreibung aufgeführt.](../../exchange-online-service-description/exchange-online-service-description.md) Exchange Online ist für die Umgebungen Government Community Cloud (GCC), GCC High und Department of Defense (DoD) verfügbar.

Weitere Informationen zur Regierungs-Cloud, einschließlich Berechtigung und Erwerb, finden Sie unter [Microsoft 365 Government - how to buy](./microsoft-365-government-how-to-buy.md). Informationen zum Vergleich von Office 365 Government-Plänen finden Sie unter [Office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Informationen zu den erforderlichen Endpunkten beim Verwalten der Netzwerkkonnektivität finden Sie unter [Office 365 U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) oder [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Organisationen profitieren nicht nur von den Features und Funktionen von Office 365, sondern profitieren auch von den folgenden Features, die für die Cloudumgebungen der US-Regierung einzigartig sind:

- Die Kundeninhalte Ihrer Organisation werden logisch von Kundeninhalten in den kommerziellen Office 365-Diensten getrennt.

- Die Kundeninhalte Ihrer Organisation werden in den USA in Ruhe gespeichert.

- Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.

- Die Cloudumgebungen der Regierung entsprechen den Zertifizierungen und Akkreditierungen, die häufig für Kunden des öffentlichen US-Sektors erforderlich sind.

Es ist unsere allgemeine Absicht, alle kommerziellen Features und Funktionen von Exchange für die Cloudumgebung der Regierung bereitzustellen. Einige Features sind jedoch aufgrund der Anforderungen von Government Cloud-Kunden nicht verfügbar. Andere Features kommen in die Regierungsumgebungen, sind aber noch nicht verfügbar. In den folgenden Abschnitten finden Sie Informationen zur Verfügbarkeit von Features in den Cloudumgebungen der Regierung.

## <a name="exchange-online-features"></a>Exchange Online-Features

In der folgenden Tabelle wird erläutert, ob bestimmte Exchange Online-Features in den GCC-, GCC High- und DoD-Umgebungen verfügbar sind. Wenn es Nuancen bezüglich der Unterstützungserklärung (oder fehlender Unterstützung) gibt, wird zusätzlicher Kontext bereitgestellt.<br><br>

| Feature | GCC | GCC High | DoD | Wichtige Überlegungen |
|:-----|:-----|:-----|:-----|:-----|
|**[Planung und Bereitstellung](../../exchange-online-service-description/planning-and-deployment.md)**|||||
|Unterstützung für Hybridbereitstellung|Ja|Ja|Ja|Für die Koexistenz mit Exchange Server lokalen Clientzugriffsservern muss Microsoft mindestens einen Exchange Server 2013-Clientzugriffsserver (oder Exchange Server 2016) installieren. Exchange Server 2010 und früheren Versionen werden nicht unterstützt.|
|Unterstützung für IMAP-Migration|Ja|Ja|Ja||
|Unterstützung für Übernahmemigration|Ja|Ja|Ja||
|Unterstützung für phasenweise Migration|Ja|Ja|Ja|Die GSuite-Migration wird für GCC High und DoD nicht unterstützt. Weitere Informationen finden Sie unter <a href="/exchange/mailbox-migration/perform-g-suite-migration">Perform a GSuite migration</a>.|
|**[Berechtigungen](../../exchange-online-service-description/permissions.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Rollenbasierte Berechtigungen|Ja|Ja|Ja||
|Rollengruppen|Ja|Ja|Ja||
|Rollenzuweisungsrichtlinien|Ja|Ja|Ja||
|**[Messagingrichtlinie und -einhaltung](../../exchange-online-service-description/message-policy-and-compliance.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Archivieren von Exchange Online-basierten Postfächern|Ja|Ja|Ja||
|Cloudbasierte Archivierung von lokalen Postfächern|Ja|Ja|Ja||
|Verwaltung von Nachrichtendatensätzen (Messaging Records Management, MRM) |Ja|Ja|Ja||
|Manuelle Aufbewahrungsrichtlinien, Bezeichnungen und Tags |Ja|Ja|Ja||
|Verschlüsselung von Daten im Ruhezustand (BitLocker)|Ja|Ja|Ja||
|IRM mit Azure Information Protection|Ja|Ja|Ja|Weitere Informationen zu Einschränkungen von AIP in GCC High und DoD finden Sie unter <a href="/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description">Azure Information Protection Premium Government Service Description</a>.<br><br>Azure Information Protection ist nicht in G1/F3 enthalten, kann jedoch als separates Add-On erworben werden und aktiviert die unterstützten Information Rights Management (IRM)-Features. Einige Azure Information Protection-Features erfordern ein Abonnement für Office 365 ProPlus, das nicht in Office 365 Government G1 oder Office 365 Government F3 enthalten ist.|
|IRM mit Windows Server AD RMS|Ja|Ja|Ja|  Windows Server AD RMS ist ein lokaler Server, der separat erworben und verwaltet werden muss, um die unterstützten IRM-Funktionen zu aktivieren.|
|Office 365-Nachrichtenverschlüsselung|Ja|Ja|Ja|Weitere Informationen finden Sie unter Office 365 Message Encryption behavior [across GCC High/DoD boundary](#office-365-message-encryptionbehavior-across-gcc-highdod-boundary) in this article und Unique characteristics of Office <a href="/microsoft-365/compliance/ome-version-comparison#unique-characteristics-of-office-365-message-encryption-in-a-gcc-high-deployment">365 Message Encryption in a GCC High deployment</a>, which document behavioral nuances of Office 365 Message Encryption when sending messages between GCC High/DoD and non-GCC High/DoD users.|
|Kundenschlüssel|Ja|Ja|Ja|Erfordert G5-Dienstplan.|
|S/MIME|Ja|Ja|Ja||
|In-Situ-Speicher und Beweissicherungsverfahren|Ja|Ja|Ja|Erfordert G3- oder G5-Dienstplan.|
|Compliance-eDiscovery|Ja|Ja|Ja||
|Nachrichtenflussregeln|Ja|Ja|Ja||
|Data loss prevention|Ja|Ja|Ja|Erfordert G3- oder G5-Dienstplan.|
|Journale|Ja|Ja|Ja||
|**[Antispam- und Antischadsoftwareschutz](../../exchange-online-service-description/anti-spam-and-anti-malware-protection.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Integrierter Antispamschutz|Ja|Ja|Ja||
|Customize anti-spam policies|Ja|Ja|Ja||
|Integrierter Antischadsoftwareschutz|Ja|Ja|Ja||
|Customize anti-malware policies|Ja|Ja|Ja||
|Quarantäne - Verwaltung durch Administrator|Ja|Ja|Ja||
|Quarantäne - Selbstverwaltung durch Endbenutzer|Ja|Ja|Ja||
|Microsoft Defender für Office 365|Ja|Ja|Ja|Erfordert G5 Service Plan (oder Kauf von Add-On).<br><br>Antiphishing für Identitätswechsel und Spoof intelligence für Benutzer und Domänen sind in GCC High und DoD noch nicht verfügbar.|
|**[Nachrichtenübermittlung](../../exchange-online-service-description/mail-flow.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Benutzerdefiniertes Routing ausgehender E-Mails|Ja|Ja|Ja||
|Secure messaging with a trusted partner|Ja|Ja|Ja||
|Conditional mail routing|Ja|Ja|Ja||
|Hinzufügen eines Partners zu einer eingehenden sicheren Liste|Ja|Ja|Ja||
|Hybrides E-Mail-Routing|Ja|Ja|Ja||
|**[Empfänger](../../exchange-online-service-description/recipients.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Kapazitätswarnungen|Ja|Ja|Ja||
|Unwichtige Elemente|Ja|Ja|Ja||
|MailTips|Ja|Ja|Ja||
|Stellvertretungszugriff|Ja|Ja|Ja||
|Posteingangsregeln|Ja|Ja|Ja||
|Verbundene Konten|Ja|Nein|Nein|Dieses Feature wird in GCC High oder DoD aufgrund von Einschränkungen für ausgehende Verbindungen zu Diensten von Drittanbietern nicht unterstützt. Weitere Informationen zu features impacted finden Sie unter [Connectivity with third-party services](#connectivity-with-third-party-services) in this article.|
|Inaktive Postfächer|Ja|Ja|Ja|Erfordert G3- oder G5-Dienstplan.|
|Offlineadressbuch|Ja|Ja|Ja||
|Adressbuchrichtlinien|Ja|Ja|Ja||
|Hierarchisches Adressbuch|Ja|Ja|Ja||
|Adresslisten und globale Adressliste|Ja|Ja|Ja||
|Office 365-Gruppen|Ja|Ja|Ja|Gastzugriff auf Office 365-Gruppen wird in GCC High- und DoD-Umgebungen nicht unterstützt. Weitere Informationen finden Sie unter <a href="/azure/azure-government/documentation-government-services-securityandidentity">Azure Government Security + Identity</a>.|
|Verteilergruppen|Ja|Ja|Ja||
|Externe Kontakte (global)|Ja|Ja|Ja|Unterliegen Einschränkungen für die Zusammenarbeit zwischen Organisationen in GCC High- und DoD-Umgebungen. |
|Kontaktverknüpfung mit sozialen Netzwerken|Ja|Nein|Nein|Dieses Feature wird in GCC High oder DoD nicht unterstützt.|
|Ressourcenpostfächer|Ja|Ja|Ja||
|Konferenzraumverwaltung|Ja|Ja|Ja||
|Abwesenheitsantworten|Ja|Ja|Ja||
|Freigabe von Internetkalendern|Ja|Nein|Nein|In GCC High funktioniert die Veröffentlichung/Freigabe von Internetkalendern für eingehende Verbindungen mit Kalendern, die von GCC High-Benutzern freigegeben wurden, aber nicht für GCC High-Benutzer, die ausgehende Verbindungen mit einem freigegebenen Kalender außerhalb von GCC High herstellen.<br><br>In DoD–Internet Calendar sharing is not supported due to the requirement for inbound/outbound connection allow listing in that environment.|
|**[Berichterstellungsfeatures und Tools zur Problembehandlung](../../exchange-online-service-description/reporting-features-and-troubleshooting-tools.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Microsoft 365 Admin Center-Berichte|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Informationen zu <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Updates/aktueller</a> Verfügbarkeit finden Sie im Abschnitt Plattformfeatures der Office 365 US Government-Dienstbeschreibung.|
|Webdienstberichte|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Informationen zu <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Updates/aktueller</a> Verfügbarkeit finden Sie im Abschnitt Plattformfeatures der Office 365 US Government-Dienstbeschreibung.|
|Message trace|Ja|Ja|Ja||
|Überwachungsberichte|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Informationen zu <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Updates/aktueller</a> Verfügbarkeit finden Sie im Abschnitt Plattformfeatures der Office 365 US Government-Dienstbeschreibung.|
|Unified Messaging-Berichte|Ja|Nein|Nein||
|**[Freigabe und Zusammenarbeit](../../exchange-online-service-description/sharing-and-collaboration.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Verbundfreigabe (einschließlich Kalenderveröffentlichung)|Ja|Ja|Ja|Einschränkungen sind sowohl in GCC High als auch in DoD vorhanden. Weitere Informationen finden Sie unter [Frei/Gebucht-Verbund](#freebusy-federation) in diesem Artikel.|
|Websitepostfächer|Ja|Ja|Ja||
|Öffentliche Ordner|Ja|Ja|Ja||
|**[Clients und mobile Geräte](../../exchange-online-service-description/clients-and-mobile-devices.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|To Do on the Web|Ja|Nein|Nein||
|Outlook für Windows|Ja|Ja|Ja|Um die Complianceanforderungen für GCC High und DoD zu erfüllen, müssen Sie mindestens Version 1803 von Office 365 ProPlus ausführen. Office 365 ProPlus ist nicht in G1 oder F3 enthalten.|
|Outlook im Web|Ja|Ja|Ja||
|Outlook für Mac|Ja|Ja|Ja|Um die Complianceanforderungen für GCC High und DoD zu erfüllen, müssen Sie mindestens Version 1803 von Office 365 ProPlus ausführen. Office 365 ProPlus ist nicht in G1 oder F3 enthalten.|
|Outlook für iOS und Android|Ja|Ja|Ja||
|Exchange ActiveSync|Ja|Ja|Ja||
|Grundlegende Mobilität und Sicherheit für Microsoft 365|Ja|Nein|Nein||
|POP und IMAP|Ja|Ja|Ja||
|SMTP|Ja|Ja|Ja||
|Unterstützung von EWS-Anwendungen|Ja|Ja|Ja||
|**[Sprachnachrichtendienste](../../exchange-online-service-description/voice-message-services.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Voicemail|Nein|Nein|Nein|Die Integration von lokalen IP-PBX-Systemen in Exchange Online Unified Messaging wird nicht unterstützt.|
|Integration zwischen Voicemail und Fax von Drittanbietern|Nein|Nein|Nein|Die Integration von lokalen IP-PBX-Systemen in Exchange Online Unified Messaging wird nicht unterstützt.|
|Interoperabilität von Voicemails eines Drittanbieters|Nein|Nein|Nein|Die Integration von lokalen IP-PBX-Systemen in Exchange Online Unified Messaging wird nicht unterstützt.|
|Skype for Business-Integration|Ja|Ja|Ja||
|**[Hohe Verfügbarkeit und Geschäftskontinuität](../../exchange-online-service-description/high-availability-and-business-continuity.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Postfachreplikation in Rechenzentren|Ja|Ja|Ja||
|Wiederherstellung gelöschter Postfächer|Ja|Ja|Ja||
|Wiederherstellung gelöschter Elemente|Ja|Ja|Ja||
|Wiederherstellung einzelner Elemente|Ja|Ja|Ja||
|**[Interoperabilität, Konnektivität und Kompatibilität](../../exchange-online-service-description/interoperability-connectivity-and-compatibility.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Anwesenheit in OWA und Outlook|Ja|Ja|Ja||
|SharePoint-Interoperabilität|Ja|Ja|Ja||
|Unterstützung der EWS-Konnektivität|Ja|Ja|Ja||
|SMTP-Relayunterstützung|Ja|Ja|Ja||
|**[Einrichtung und Verwaltung in Exchange Online](../../exchange-online-service-description/exchange-online-setup-and-administration.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Zugriff auf das Microsoft Office 365-Portal|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Informationen zu <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Updates/aktueller</a> Verfügbarkeit finden Sie im Abschnitt Plattformfeatures der Office 365 US Government-Dienstbeschreibung.|
|Microsoft 365 Admin Center Access|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Informationen zu <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Updates/aktueller</a> Verfügbarkeit finden Sie im Abschnitt Plattformfeatures der Office 365 US Government-Dienstbeschreibung.|
|Zugriff auf die Exchange-Verwaltungskonsole|Ja|Ja|Ja||
|Zugriff auf die remote verwendete Windows PowerShell|Ja|Ja|Ja||
|ActiveSync-Richtlinien für mobile Geräte|Ja|Ja|Ja||
|Verwendungsberichte|Ja|Ja|Nein|Berichte sind für DoD nicht verfügbar. Informationen zu <a href="/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features">Updates/aktueller</a> Verfügbarkeit finden Sie im Abschnitt Plattformfeatures der Office 365 US Government-Dienstbeschreibung.|
|**[Erweitern des Diensts – Anpassung, Add-Ins und Ressourcen](../../exchange-online-service-description/exchange-online-service-description.md)**|**GCC**|**GCC High**|**DoD**|**Wichtige Überlegungen**|
|Outlook-Add-Ins und Outlook MAPI|Ja|Ja|Ja|Nur einige OWA- und Outlook-Add-Ins sind in GCC High und DoD verfügbar. Weitere Informationen finden Sie in diesem Artikel [unter Add-Ins in Outlook und Outlook Web App.](#add-insin-outlook-and-outlook-web-app)|

## <a name="feature-nuances-within-gcc-high-and-dod-environments"></a>Funktionsnuancen in GCC High- und DoD-Umgebungen

### <a name="connectivity-with-third-party-services"></a>Konnektivität mit Drittanbieterdiensten  

Sowohl GCC High- als auch DoD-Umgebungen sind eingeschränkte Umgebungen, die eine explizite Genehmigung und Konfiguration ausgehender Verbindungen erfordern. Darüber hinaus kann Microsoft Anforderungen nicht erfüllen, um ausgehenden Zugriff von diesen Umgebungen auf kommerzielle Clouddienste zu ermöglichen (Commercial Office 365, Google GSuite, Amazon Web Services und so weiter).

Aufgrund dieser Einschränkungen werden Features, die auf dieser ausgehenden Verbindung von den GCC High/DoD-Umgebungen beruhen, im Allgemeinen nicht unterstützt, einschließlich:

- Verbundene Konten – Benutzer können keine Konten hinzufügen/synchronisieren (Google, POP/IMAP und so weiter).

- Unterstützung für Dateispeicheranbieter von Drittanbietern – Nur auf das OneDrive for #A0 des Benutzers in *GCC High/DoD* kann innerhalb der verschiedenen #A1 zugegriffen werden, um Dateien anfügen/freigeben zu können. Speicherkonten von Drittanbietern (Dropbox, Box, Google Drive) können nicht hinzugefügt werden.

- Konnektivität mit sozialen Netzwerken wie Facebook oder LinkedIn.

### <a name="azure-active-directory-b2b-collaboration"></a>Azure Active Directory B2B-Zusammenarbeit

Die Azure Active Directory B2B-Zusammenarbeit wird derzeit nur zwischen Organisationen unterstützt, die sich beide in der Azure US Government-Cloud befinden und beide die B2B-Zusammenarbeit unterstützen.

Darüber hinaus werden B2B-Benutzer als Gäste in Office 365-Gruppen in GCC High- und DoD-Umgebungen nicht unterstützt. 

Weitere Informationen und die neuesten Updates finden Sie unter [Azure Government Security + Identity](/azure/azure-government/documentation-government-services-securityandidentity).

### <a name="office-365-message-encryption-behavior-across-gcc-highdod-boundary"></a>Office 365-Nachrichtenverschlüsselungsverhalten über die GCC-Grenze hinweg

Wenn Sie planen, die Office 365-Nachrichtenverschlüsselung in einer GCC High-Umgebung zu verwenden, beachten Sie diese eindeutigen Merkmale der Empfängererfahrung:  

- Beim Senden verschlüsselter E-Mails von GCC High oder DoD an Empfänger in derselben Umgebung:
    
    - Absender können E-Mails in Outlook für PC und Mac und Outlook im Web manuell verschlüsseln, oder Organisationen können eine Richtlinie zum Verschlüsseln von E-Mails mithilfe von Exchange-Nachrichtenflussregeln einrichten.
    
    - Empfänger in GCC High/DoD erhalten dieselbe Inlineleseerfahrung in Outlook für PC und Mac und Outlook im Web wie alle anderen Office 365-Benutzer.

<!-- end list -->

- Beim Senden verschlüsselter E-Mails von GCC High oder DoD an Empfänger außerhalb dieser Umgebung (einschließlich GCC und Commercial):
    
    - Absender innerhalb von GCC High/DoD können verschlüsselte E-Mails außerhalb der GCC High/DoD-Grenze senden.
    
    - Alle Empfänger außerhalb von GCC High/DoD, einschließlich kommerzieller Office 365-Benutzer, Outlook.com-Benutzer und andere Benutzer anderer E-Mail-Anbieter, erhalten eine Wrapper-E-Mail. Diese Wrapper-E-Mail leitet den Empfänger an das OME-Portal weiter, in dem der Empfänger die Nachricht lesen und beantworten kann.

Weitere Informationen und die neuesten Updates finden Sie unter [Vergleichen von Versionen von OME](/microsoft-365/compliance/ome-version-comparison).

### <a name="freebusy-federation"></a>Frei/Gebucht-Verbund

Die Verbundfreigabe, einschließlich Frei/Gebucht-Informationen, unterliegt derzeit in den GCC High- und DoD-Umgebungen mehreren wichtigen Einschränkungen.

In der GCC High-Umgebung:

- Die Verbundvertrauensstellung (einschließlich bidirektionaler Frei/Gebucht-Freigabe) wird zwischen Mandanten innerhalb von GCC High und über hybride Koexistenz (Exchange 2013 oder höher) unterstützt.

- Die Verbundfreigabe wird zwischen Mandanten in GCC High und GCC oder Office 365 Commercial nicht unterstützt. Ausgehende Verbindungen von der GCC High-Umgebung zu kommerziellen Clouds (einschließlich GCC und Office 365 commercial) sind derzeit nicht zulässig. Dies hat zur Folge, dass GCC High-Benutzer nicht in der Lage sind, die erforderliche ausgehende Anforderung an GCC/Commercial für den Zugriff auf freigegebene Kalenderinformationen zu stellen.

In der DoD-Umgebung:

  - Verbundvertrauensstellung (einschließlich Frei/Gebucht-Freigabe) wird derzeit nur zwischen Mandanten innerhalb der DoD-Umgebung unterstützt. Es wird nicht zwischen DoD-Mandanten und GCC- oder kommerziellen Mandanten unterstützt.

### <a name="client-configuration"></a>Clientkonfiguration

Weitere Schritte sind beim Bereitstellen und Konfigurieren von Office ProPlus (einschließlich Outlook) erforderlich. Eine ausführliche Beschreibung dieser Schritte finden Sie unter [Guidance for deploying Microsoft 365 Apps for Enterprise in a GCC High or DoD environment](/deployoffice/deploy-microsoft-365-apps-gcc-high-dod).

Outlook für iOS und Android ist auch für GCC High- und DoD-Umgebungen verfügbar. Weitere Informationen zu Funktionseinschränkungen und -verwaltung in diesen Umgebungen finden Sie unter [Using Outlook for iOS and Android in the Government Community Cloud](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud).

### <a name="add-ins-in-outlook-and-outlook-web-app"></a>Add-Ins in Outlook und Outlook Web App  

Nur einige OWA- und Outlook-Add-Ins sind in GCC High und DoD verfügbar. Meine Vorlagen und vorgeschlagene Besprechungen sind verfügbar und funktionieren voraussichtlich. Nur die fünf standardmäßigen OWA-Add-Ins werden unterstützt. Die Integration in Drittanbieteranwendungen ist möglich, diese Integrationen werden jedoch nicht durch Microsoft Compliance-Zusagen für GCC High oder DoD abgedeckt. Kunden sollten sich vor der Konfiguration des Add-Ons für ihre Organisation mit Denkmethoden und Complianceversprechen von Drittanbietern vertraut machen.

## <a name="feature-nuances-within-gcc-environments-for-microsoft-to-do"></a>Funktionsnuancen in GCC-Umgebungen für Microsoft To Do

| Feature | Beschreibung | WW | Verfügbarkeit in GCC |
|:-----|:-----|:-----|:-----|
|Unterstützte Plattformen|Web, Android, iOS, Mac, Windows|Alle|Nur Web|
|M365 Hub unterstützt|Integrationen in Outlook, Teams, Planner|Alle|Outlook, Planner (Teams soll mit der Teams-Aufgaben-App verfügbar sein)|
|Wunderlist Migration|Zulassen, dass Wunderlist-Benutzer Daten zu To Do im Web migrieren|Ja|Nein|
|Pushbenachrichtigungen|Senden von Pushbenachrichtigungen an Endbenutzer für Erinnerungen usw.|Ja|Nein|
|Helpshift-Unterstützung|Verwenden der Helpshift-Schnittstelle zum Erstellen einer Supportanfrage|Ja|Nein|
|My Day|Planen Ihres Tages|Ja|Ja|
|Geplante Liste|Alle Vorgänge mit einem Fälligkeitsdatum sehen|Ja|Ja|
|Ihnen zugewiesene Liste|Alle Aufgaben, die Ihnen in einer freigegebenen Liste, Planner oder WXP (zukunft) zugewiesen sind|Ja|Ja|
|Gekennzeichnete E-Mails|E-Mails in Outlook als Aufgaben gekennzeichnet sehen|Ja|Ja|
|Unterstützung für mehrere Konten|Verwenden des Heim- und Officekontos in einem Bereich|Ja|Ja|
|Auflisten der Freigabe|Freigeben von Listen für Kollegen in derselben Organisation|Ja|Ja|
|Mandantenübergreifende Freigabe|Aufgabenliste außerhalb Ihrer Organisation freigeben|Ja|Nein|
|Erinnerungen und Wiederholungen|Festlegen von Erinnerungen für Ihre Aufgabe |Ja|Ja|

*Alle anderen nicht erwähnten Features sind in beiden Umgebungen verfügbar.