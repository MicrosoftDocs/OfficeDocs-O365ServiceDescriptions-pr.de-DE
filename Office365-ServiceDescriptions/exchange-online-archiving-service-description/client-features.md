---
title: Clientfunktionen in der Exchange Online-Archivierung
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Mit Microsoft Exchange Online-Archivierung können Benutzer über eine Vielzahl von Geräten und Plattformen eine Verbindung zu ihren archivpostfächern herstellen. Alle Netzwerkverbindungen zum Archiv des Benutzers erfolgen über das Internet, und es sind keine VPN-Verbindungen (Virtual Private Network) erforderlich. Organisationen können einen lokalen Clientzugriffsserver veröffentlichen, damit Benutzer mit Outlook Anywhere auf ihr primäres Postfach zugreifen können, ohne dass eine VPN-Verbindung erforderlich ist. Wenn VPN für den Zugriff auf das primäre Postfach des Benutzers erforderlich ist, das sich auf einem lokalen Server befindet, ändert sich diese Anforderung nicht.
ms.openlocfilehash: 616de5cb187f74b048d14770abb8fe640d0782d3
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341844"
---
# <a name="client-features-in-exchange-online-archiving"></a>Clientfunktionen in der Exchange Online-Archivierung

Mit Microsoft Exchange Online-Archivierung können Benutzer über eine Vielzahl von Geräten und Plattformen eine Verbindung zu ihren archivpostfächern herstellen. Alle Netzwerkverbindungen zum Archiv des Benutzers erfolgen über das Internet, und es sind keine VPN-Verbindungen (Virtual Private Network) erforderlich. Organisationen können einen lokalen Clientzugriffsserver veröffentlichen, damit Benutzer mit Outlook Anywhere auf ihr primäres Postfach zugreifen können, ohne dass eine VPN-Verbindung erforderlich ist. Wenn VPN für den Zugriff auf das primäre Postfach des Benutzers erforderlich ist, das sich auf einem lokalen Server befindet, ändert sich diese Anforderung nicht.
  
> [!IMPORTANT]
> Microsoft behält sich das Recht vor, Verbindungen von Clientsoftware, welche die Integrität des Exchange Online-Archivierung-Dienstes beeinträchtigt, zu blockieren oder zu drosseln. 
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook ist ein E-Mail-Programm mit umfassenden Funktionen, das Unterstützung für Kalendereinträge, Kontakte und Aufgaben bietet. Exchange Online-Archivierung unterstützt Outlook 2013, Outlook 2010 und Outlook 2007. Zu den zentralen Features zählen folgende:
  
- **Outlook Anywhere** Mit Outlook Anywhere können Outlook-Benutzer über das Internet eine Verbindung zu Exchange Server und Exchange Online-Archivierung herstellen, ohne dass eine VPN-Verbindung erforderlich ist. Die Kommunikation zwischen Outlook und Exchange Online-Archivierung erfolgt mithilfe der RPC-über-HTTP-Netzwerkkomponente von Windows über einen SSL-gesicherten Tunnel. 
    
- **AutoErmittlung** Der Exchange AutoErmittlungsdienst konfiguriert Outlook automatisch für die Zusammenarbeit mit Exchange Online-Archivierung. AutoErmittlung ermöglicht Outlook-Benutzern, ihre erforderlichen Profileinstellungen direkt von Exchange zu erhalten, wenn sie sich zum ersten Mal mit ihrer E-Mail-Adresse und ihrem Kennwort anmelden (und dann in regelmäßigen Abständen). 
    
Outlook 2010 und höher und Outlook Web App bieten den Benutzern sämtliche Features des Archivs sowie verwandte Features wie Aufbewahrungs- und Archivierungsrichtlinien.
  
Outlook 2007 bietet eine grundlegende Unterstützung des Archivs, jedoch nicht aller Features für Archivierung und Richtlinientreue, die in Outlook 2007 verfügbar sind. In Outlook 2007 können Benutzer beispielsweise auf Elemente in ihrem Postfach keine Aufbewahrungs- oder Archivierungsrichtlinien anwenden. Stattdessen muss der Administrator diese Richtlinien bereitstellen. Die Benutzer von Outlook 2007 müssen das kumulative Office 2007-Update vom Februar 2011 installiert haben, um auf das Archiv zugreifen zu können.
  
> [!NOTE]
> Outlook ist nicht im Lieferumfang von Exchange Online-Archivierung enthalten. Microsoft Office 365 ProPlus (welches Microsoft Outlook umfasst) ist in manchen Office 365-Plänen enthalten und kann als separates Abonnement erworben werden. Weitere Informationen finden Sie unter [Optionen zum Office 365-Plan](../office-365-platform-service-description/office-365-plan-options.md). Weitere Informationen zu Office 365 ProPlus finden Sie unter [Dienstbeschreibung zu Office-Anwendungen](../office-applications-service-description/office-applications-service-description.md). 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clients, die von der Exchange Online-Archivierung unterstützt werden

Die folgende Tabelle enthält die von der Exchange Online-Archivierung unterstützten Clients:
  
|**Client**|**EOA-Unterstützung**|
|:-----|:-----|
|Outlook 2010 und höher  <br/> |Unterstützt die neuesten Funktionen in Exchange Online-Archivierung.<sup>1</sup> <br/> |
|Outlook 2007  <br/> |Unterstützt Exchange Online-Archivierung.<sup>1, 2</sup> <br/> |
|Outlook 2003  <br/> |Nicht unterstützt  <br/> |
|Outlook für Mac 2011  <br/> |Nicht unterstützt  <br/> |
|Outlook für Mac  <br/> |Unterstützt für die Verwendung mit Exchange Online-Archivierung.<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |Nicht unterstützt  <br/> |
|IMAP und POP  <br/> |Nicht unterstützt  <br/> |
|Exchange ActiveSync (mobile Geräte)  <br/> |Nicht unterstützt  <br/> |
   
> [!NOTE]
> <sup>1</sup> Die in Microsoft Office Standard enthaltene Outlook-Version wird nicht unterstützt. Weitere Informationen finden Sie im Artikel zum Thema [Lizenzanforderungen für persönliche Archive und Aufbewahrungsrichtlinien](https://go.microsoft.com/fwlink/?LinkId=389396). > <sup>2</sup> Zur Aktivierung der Archivierungsunterstützung ist ein Update erforderlich. Outlook 2007-Benutzer können keine Aufbewahrungs- oder Archivierungsrichtlinien anzeigen oder auf Elemente in ihren Archivpostfächern anwenden; Richtlinien müssen vom Administrator bereitgestellt werden. Darüber hinaus können Benutzer von Outlook 2007 das lokale Postfach und das Archiv nicht gleichzeitig durchsuchen. > <sup>3</sup> Sie können Outlook 2016 für Mac oder Outlook für Mac nicht zum Verschieben oder Kopieren von Ordnern, Kalenderelementen, Kontakten, Aufgaben oder Notizen in Ihrem Archiv oder zum Anzeigen dieser Elemente im Archivpostfach verwenden, wenn diese Elemente zuvor unter Verwendung einer anderen Version von Outlook (zum Beispiel Outlook 2016 für Windows) dorthin verschoben wurden. Weitere Informationen finden Sie unter [Verwenden Ihres Onlinearchivs bei Outlook 2016 für Mac](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 
  
## <a name="outlook-web-app"></a>Outlook Web App

Outlook Web App ist eine webbasierte Version des Outlook-E-Mail-Programms, das mit Exchange Online verwendet wird. Egal, ob Benutzer zu Hause, im Büro oder unterwegs eine Internetverbindung herstellen – sie können über Outlook Web App auf ihre E-Mails zugreifen.
  
Benutzer können auf ihr Archiv zugreifen, indem sie sich lokal (mithilfe der gleichen URL) bei Outlook Web App anmelden. Das Archiv wird in Outlook Web App neben dem primären Postfach angezeigt. Es ist nicht möglich, direkt von Outlook Web App aus auf das Archiv zuzugreifen.
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Beschreibung des Exchange Online-Archivierungsdiensts](exchange-online-archiving-service-description.md).
  

