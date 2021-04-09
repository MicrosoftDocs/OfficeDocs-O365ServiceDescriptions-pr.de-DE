---
title: Beschreibung des Exchange Online-Archivierungsdiensts
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-archiving-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: 21ebd4bb-7d88-489f-a8aa-376e2536900c
description: In diesem Artikel erfahren Sie mehr über Microsoft Exchange Online Archivierung.
ms.openlocfilehash: 1dcd594017f4699bbccdd29c109269bc9dea7875
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653077"
---
# <a name="exchange-online-archiving-service-description"></a>Beschreibung des Exchange Online-Archivierungsdiensts

Microsoft Exchange Online Archivierung ist eine cloudbasierte Archivierungslösung auf Microsoft 365-Unternehmensklasse für Organisationen, die Microsoft Exchange Server 2019, Microsoft Exchange Server 2016, Microsoft Exchange Server 2013, Microsoft Exchange Server 2010 (SP2 und höher) bereitgestellt haben, oder bestimmte Exchange Online- oder Microsoft365-Pläne abonnieren. Exchange Online-Archivierung unterstützt diese Organisationen bei ihren Herausforderungen bei Archivierung, Compliance, Vorschriften und eDiscovery und vereinfacht gleichzeitig die lokale Infrastruktur und reduziert dadurch Die Kosten und verringert die IT-Belastung.
  
Als Microsoft-Onlinedienst ist Exchange Online-Archivierung darauf ausgelegt, Anforderungen in puncto robuster Sicherheit, Zuverlässigkeit und Benutzerproduktivität zu erfüllen. Weitere Informationen zu Microsoft 365, einschließlich features common to all Microsoft online services, finden Sie unter [Microsoft 365 and Office 365 platform service description](../office-365-platform-service-description/office-365-platform-service-description.md).
  
Informationen zum Exchange Online-Archivierung finden Sie [unter Exchange Online-Archivierung server](https://products.office.com/exchange/microsoft-exchange-online-archiving-email).
  
## <a name="available-plans"></a>Verfügbare Pläne

Ausführliche Planinformationen zu Abonnements, die Benutzern Exchange Online-Archivierung ermöglichen, finden Sie in der [vollständigen Abonnementvergleichstabelle](https://go.microsoft.com/fwlink/?linkid=2139145).
  
> [!TIP]
> Sie können Seiten in den Dienstbeschreibungen exportieren, speichern und drucken. Erfahren Sie, [wie Sie Inhaltssuchergebnisse exportieren.](/office365/securitycompliance/export-search-results) 
  
## <a name="exchange-online-archiving-plans"></a>Exchange Online-Archivierungspläne

Exchange Online-Archivierung steht über die folgenden Pläne zur Verfügung.<br><br>
  
| Plan | Beschreibung |
|:-----|:-----|
|**Exchange Online-Archivierung für Exchange Server** <br/> |Cloudbasiertes Archiv für Benutzer mit primären Postfächern in Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 oder Exchange 2010 (SP2 oder höher).  <br/> Wenn Sie ein cloudbasiertes Archiv zu einem primären Postfach hinzufügen möchten, das sich auf einem lokalen Exchange-Server befindet, müssen Sie eine Hybridbereitstellung konfigurieren. Weitere Informationen zu Hybridbereitstellungen finden Sie [Exchange Server Hybridbereitstellungen](/exchange/exchange-hybrid).  <br/> |
|**Exchange Online-Archivierung für Exchange Server (über die Enterprise CAL-Suite)** <br/> |Cloudbasiertes Archiv für Benutzer mit primären Postfächern in Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 oder Exchange 2010 (SP2 oder höher). Weitere Informationen finden Sie unter [Clientzugriffslizenzen und Verwaltungslizenzen](https://www.microsoft.com/licensing/product-licensing/client-access-license).  <br/> |
|**Exchange Online-Archivierung für Exchange Online** <br/> | Cloudbasiertes Archiv und in-place-Archiv als Add-On für die folgenden Pläne<sup>1, 2</sup>:<br/>  Exchange Online Plan 1  <br/>  Exchange Online-Kiosk  <br/>  Microsoft 365 Business Basic  <br/>  Microsoft 365 Business Standard  <br/>  Office 365 Enterprise E1  <br/>  Office 365 Enterprise F3  <br/> Microsoft 365 Enterprise F3<br/> <b>Hinweis:</b> Die folgenden Pläne umfassen bereits die Archivierung und erfordern Exchange Online-Archivierung als Add-On:<br/>Office 365 Education A1 <br/>Office 365 Education A3 <br/>  Office 365 Education A5 <br/>  Office 365 Enterprise E3 <br/>  Office 365 Enterprise E5 <br/>  Exchange Online Plan 2 <br/> Microsoft 365 Business Premium <br/>Microsoft 365 Enterprise E3 <br/> Microsoft 365 Enterprise E5 <br/>Weitere Informationen zu den Archivierungsfunktionen von Exchange Online-Postfächern finden Sie unter [Archivfeatures in Exchange Online-Archivierung](./archive-features.md).           |
   
>[!NOTE]
><sup>1</sup> Organisationen, die lediglich über eine Cloud verfügen und bei denen keine Postfächer auf einem lokalen Exchange-Server vorhanden sind, benötigen keine Hybridbereitstellung. Wenn lokale Postfächer vorhanden sind, ist eine Hybridbereitstellung erforderlich.
<br/>
<sup>2</sup> Exchange Online Plan 1 und Microsoft 365 Apps haben eine Größenbeschränkung für das Postfach und Archiv. Weitere Informationen finden Sie unter [Exchange Online-Beschränkungen](../exchange-online-service-description/exchange-online-limits.md). Durch die Exchange Online-Archivierung wird Exchange Online um ein cloudbasiertes Archiv und [Compliance-Archiv und Aufbewahrung für eventuelle Rechtsstreitigkeiten](compliance-and-security-features.md#in-place-hold-and-litigation-hold) ergänzt, beides ohne Begrenzung.
  
Suchen Sie nach Informationen zu allen Microsoft 365-Plänen? Microsoft 365 ist in einer Vielzahl von Plänen verfügbar, um die Anforderungen Ihrer Organisation optimal zu erfüllen. Informationen zu verschiedenen Plänen, einschließlich eigenständiger Planoptionen und Informationen zum Wechsel von einem Plan zu einem anderen, finden Sie unter [Office 365 Plan Options](../office-365-platform-service-description/office-365-plan-options.md).
  
## <a name="requirements"></a>Anforderungen

Um Exchange Online-Archivierung für Exchange Server zu verwenden, müssen sich Benutzerpostfächer auf Exchange Server 2019, Exchange Server 2016, Exchange Server 2013 oder Exchange Server 2010 (SP2 oder höher) befinden.
  
### <a name="federated-identity-and-single-sign-on"></a>Identitätsverbund und einmaliges Anmelden

Administratoren können einen Ansatz für einmaliges Anmelden für die Authentifizierung mit lokalem Active Directory verwenden. Um dies zu erreichen, können Administratoren lokale Active Directory-Verbunddienste – einen Microsoft Windows Server 2008-Dienst – konfigurieren, um eine Verbindung mit dem &reg; Microsoft Federation Gateway herzustellen. Nach der Konfiguration der Active Directory-Verbunddienste können alle Benutzer, deren Identitäten auf der Verbunddomäne basieren, ihre vorhandene Unternehmensanmeldung verwenden, um sich automatisch bei Office 365 zu authentifizieren.
  
### <a name="user-subscriptions"></a>Benutzerabonnements

Jeder Benutzer, der auf den Exchange Online-Archivierung-Dienst zugreift, muss über ein Exchange Online-Archivierung-Abonnement verfügen. Ein E-Mail-Archivabonnement kann nur zum Speichern der Nachrichtendaten eines Benutzers verwendet werden.
  
## <a name="unlimited-archive-storage-quota"></a>Unbegrenztes Archivspeicherkontingent

 Das unbegrenzte Archivierungsfeature (*automatisch erweiternde Archivierung* genannt) bietet zusätzlichen Speicherplatz in Archivpostfächern. Jeder Abonnent der Exchange Online Archivierung erhält anfänglich 100 GB Speicherplatz im Archivpostfach. Wenn die Archivierung automatisch erweitert wird, wird automatisch zusätzlicher Speicherplatz hinzugefügt, wenn die Speicherkapazität von 100 GB erreicht ist. In Exchange-Hybridbereitstellungen wird die automatisch erweiternde Archivierung nur für cloudbasierte Archivpostfächer unterstützt, wenn sich das Postfach des lokalen Benutzers auf Exchange Server 2019, Exchange Server 2016 oder Exchange Server 2013 (SP1 oder höher) befindet. Weitere Informationen finden Sie unter [Übersicht zur unbeschränkten Archivierung](/office365/securitycompliance/unlimited-archiving).
  
> [!IMPORTANT]
> Administratoren können das Speicherkontingent nicht anpassen.<br/>
> Die automatische Erweiterung der Archivierung wird für Postfächer, die sich in 2010 Exchange Server, nicht unterstützt.
  
> [!IMPORTANT]
> Das Archiv für automatisches Erweitern wird nur für Postfächer unterstützt, die für einzelne Benutzer oder freigegebene Postfächer verwendet werden, deren Zuwachsrate 1 GB pro *&nbsp; Tag nicht überschreitet.* Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung zu Exchange Online-Archivierung zu kopieren. Das Archivpostfach eines Benutzers ist nur für diesen Benutzer vorgesehen. Microsoft behält sich das Recht vor, die uneingeschränkte Archivierung dann zu verweigern, wenn das Archivpostfach eines Benutzers zum Speichern von Archivdaten für andere Benutzer oder auf eine andere unangemessene Weise verwendet wird.
  
## <a name="feature-availability-across-exchange-online-archiving-plans"></a>Verfügbarkeit von Features in Exchange Online-Archivierungsplänen

| Feature | Exchange Online-Archivierung für Exchange Server<sup>1</sup> | Exchange Online-Archivierung für Exchange Online<sup>2</sup> |
|:-----|:-----|:-----|
|**[Archivfunktionen in Exchange Online-Archivierung](archive-features.md)** <br/> |||
|Archivpostfach  <br/> |Ja  <br/> |Ja  <br/> |
|Verschieben von Nachrichten mithilfe von Archivrichtlinien  <br/> |Ja  <br/> |Ja  <br/> |
|Importieren von Daten in das Archiv  <br/> |Ja  <br/> |Ja  <br/> |
|Wiederherstellung gelöschter Elemente  <br/> |Ja  <br/> |Ja  <br/> |
|Wiederherstellung gelöschter Postfächer  <br/> |Ja  <br/> |Ja  <br/> |
|Postfach-Backup  <br/> |Ja  <br/> |Ja  <br/> |
|**[Clientfeatures in Exchange Online-Archivierung](client-features.md)** <br/> |||
|Outlook<sup>3</sup> <br/> |Ja  <br/> |Ja  <br/> |
|Outlook im Web   <br/> |Ja  <br/> |Ja  <br/> |
|**[Compliance- und Sicherheitsfeatures in Exchange Online-Archivierung](compliance-and-security-features.md)** <br/> |||
|Aufbewahrungsrichtlinien  <br/> |Ja  <br/> |Ja  <br/> |
|In-Situ-Speicher und Beweissicherungsverfahren<sup>6</sup> <br/> |Ja  <br/> |Ja  <br/> |
|Compliance-eDiscovery  <br/> |Ja  <br/> |Ja  <br/> |
|Verschlüsselung zwischen lokalen Servern und Exchange Online-Archivierung  <br/> |Ja  <br/> |Ja  <br/> |
|Verschlüsselung zwischen Clients und Exchange Online-Archivierung  <br/> |Ja  <br/> |Ja  <br/> |
|Verschlüsselung: S/MIME und PGP  <br/> |Ja  <br/> |Ja  <br/> |
|IRM mit Azure Information Protection  <br/> |Nein  <br/> |Nr.<sup>4</sup> <br/> |
|IRM mit Windows Server AD RMS  <br/> |Ja<sup>5</sup> <br/> |Ja<sup>5</sup> <br/> |
|Überwachung  <br/> |Ja  <br/> |Ja  <br/> |
   

<sup>1</sup> Benutzerpostfächer müssen sich in Exchange 2010 SP2 oder höher befinden.
<br/>
<sup>2</sup> Ein In-Place Archiv kann nur zum Archivieren von E-Mails für einen einzelnen Benutzer oder eine Entität verwendet werden, für den eine Lizenz angewendet wurde. Die Verwendung In-Place Archiv als Mittel zum Speichern von E-Mails von mehreren Benutzern oder Entitäten ist verboten. IT-Administratoren ist beispielsweise nicht berechtigt, ein freigegebenes Postfach zu erstellen und die Benutzer anzuweisen, dieses freigegebene Postfach zum expliziten Zweck der Archivierung in E-Mails zu adressieren (auf CC oder BCC bzw. über eine Transportregel). <br/> 
<sup>3</sup> Eine Liste der unterstützten Microsoft Outlook-Versionen finden Sie unter [Clientfeatures in Exchange Online-Archivierung](client-features.md). <br/>
<sup>4</sup> Azure Information Protection ist nicht enthalten, kann aber als separates Add-On erworben werden und aktiviert die unterstützten Information Rights Management (IRM)-Features. Einige Azure Information Protection-Features erfordern ein Abonnement für Microsoft 365 Apps for Enterprise, das nicht in Microsoft 365 Business Basic, Microsoft 365 Business Standard, Office 365 Enterprise E1, Office 365 Education oder Office 365 Enterprise F3 enthalten ist. <br/>
<sup>5</sup> Windows Server AD RMS ist ein lokaler Server, der separat erworben und verwaltet werden muss, um die unterstützten IRM-Features zu aktivieren. <br/>
<sup>6</sup> Wenn Sie ein Postfach in In-Place oder Das Archivarchiv setzen, wird das Archiv für das primäre und das Archivpostfach aktiviert.