---
title: Client Features in Exchange Online Archivierung
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Lesen Sie diesen Artikel, um mehr über die Clientfeatures zu erfahren, die in Microsoft Exchange Online-Archivierung verfügbar sind.
ms.openlocfilehash: 54f066562b08eeeed90b8c9b465c4740bcc3f0df
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/28/2020
ms.locfileid: "48293637"
---
# <a name="client-features-in-exchange-online-archiving"></a>Client Features in Exchange Online Archivierung

Microsoft Exchange Online-Archivierung können Benutzer über eine Vielzahl von Geräten und Plattformen eine Verbindung zu ihren archivpostfächern herstellen. Die gesamte Netzwerkverbindung mit dem Archiv des Benutzers erfolgt über das Internet, und es sind keine VPN-Verbindungen (virtuelles privates Netzwerk) erforderlich. Organisationen können einen lokalen Clientzugriffsserver veröffentlichen, damit Benutzer mit Outlook Anywhere auf ihr primäres Postfach zugreifen können, ohne dass eine VPN-Verbindung erforderlich ist. Wenn VPN für den Zugriff auf das primäre Postfach des Benutzers erforderlich ist, das sich auf einem lokalen Server befindet, ändert sich diese Anforderung nicht.
  
> [!IMPORTANT]
> Microsoft behält sich das Recht vor, Verbindungen von Clientsoftware, welche die Integrität des Exchange Online-Archivierung-Dienstes beeinträchtigt, zu blockieren oder zu drosseln.
  
## <a name="microsoft-outlook"></a>Microsoft Outlook

Microsoft Outlook ist ein E-Mail-Programm mit umfassenden Funktionen, das Unterstützung für Kalendereinträge, Kontakte und Aufgaben bietet. Exchange Online-Archivierung unterstützt Outlook 2013, Outlook 2010 und Outlook 2007. Zu den zentralen Features zählen folgende:
  
- Outlook **Anywhere** – Outlook Anywhere ermöglicht Outlook-Benutzern das Herstellen einer Verbindung mit Exchange Server und Exchange Online Archivierung über das Internet ohne eine VPN-Verbindung erforderlich ist. Die Kommunikation zwischen Outlook und Exchange Online-Archivierung erfolgt mithilfe der RPC-über-HTTP-Netzwerkkomponente von Windows über einen SSL-gesicherten Tunnel.    
- **AutoErmittlung** : der Exchange-AutoErmittlungsdienst konfiguriert Outlook automatisch für die Zusammenarbeit mit Exchange Online Archivierung. Mit der AutoErmittlung können Outlook-Benutzer ihre erforderlichen Profileinstellungen direkt aus Exchange erhalten (und danach in festen Intervallen), dass Sie sich mit Ihrer e-Mail-Adresse und Ihrem Kennwort anmelden. 

Outlook 2010 und höher und Outlook im Internet bieten Benutzern die vollständigen Features des Archivs sowie verwandte Features wie Aufbewahrungs-und archivrichtlinien.
  
Outlook 2007 bietet eine grundlegende Unterstützung des Archivs, jedoch nicht aller Features für Archivierung und Richtlinientreue, die in Outlook 2007 verfügbar sind. In Outlook 2007 können Benutzer beispielsweise auf Elemente in ihrem Postfach keine Aufbewahrungs- oder Archivierungsrichtlinien anwenden. Stattdessen muss der Administrator diese Richtlinien bereitstellen. Die Benutzer von Outlook 2007 müssen das kumulative Office 2007-Update vom Februar 2011 installiert haben, um auf das Archiv zugreifen zu können.
  
> [!NOTE]
> Outlook ist nicht im Lieferumfang von Exchange Online-Archivierung enthalten. Microsoft 365 apps for Enterprise (einschließlich Microsoft Outlook) ist in einigen Plänen enthalten und kann als separates Abonnement erworben werden. Weitere Informationen finden Sie unter [Microsoft 365-Planoptionen](../office-365-platform-service-description/office-365-plan-options.md). Weitere Informationen zu Microsoft 365-Apps für Unternehmen finden Sie in der [Office Applications-Dienstbeschreibung](../office-applications-service-description/office-applications-service-description.md). 
  
### <a name="clients-supported-by-exchange-online-archiving"></a>Clients, die von der Exchange Online-Archivierung unterstützt werden

Die folgende Tabelle enthält die von der Exchange Online-Archivierung unterstützten Clients:<br><br>
  
| Client | EOA-Unterstützung |
|:-----|:-----|
|Outlook 2013 und höher  <br/> |Unterstützt die neuesten Funktionen in Exchange Online-Archivierung.<sup>1</sup> <br/> |
|Outlook 2010  <br/> |Unterstützt die neuesten Features in Exchange Online Archivierung nur bis zum 13. Oktober 2020|
|Outlook 2007  <br/> |Nicht unterstützt |
|Outlook 2003  <br/> |Nicht unterstützt  <br/> |
|Outlook für Mac 2011  <br/> |Nicht unterstützt  <br/> |
|Outlook für Mac  <br/> |Unterstützt für die Verwendung mit Exchange Online-Archivierung.<sup>3</sup> <br/> |
|Microsoft Office Entourage 2008 Web Services Edition  <br/> |Nicht unterstützt  <br/> |
|IMAP und POP  <br/> |Nicht unterstützt  <br/> |
|Exchange ActiveSync (Mobile Geräte)  <br/> |Nicht unterstützt  <br/> |
   
> [!NOTE]
> <sup>1</sup> Die in Microsoft Office Standard enthaltene Outlook-Version wird nicht unterstützt. Weitere Informationen finden Sie im Artikel zum Thema [Lizenzanforderungen für persönliche Archive und Aufbewahrungsrichtlinien](https://support.office.com/article/Outlook-license-requirements-for-Exchange-features-46B6B7C5-C3CA-43E5-8424-1E2807917C99). <br/> 
<sup>2</sup> Zur Aktivierung der Archivierungsunterstützung ist ein Update erforderlich. Outlook 2007-Benutzer können keine Aufbewahrungs- oder Archivierungsrichtlinien anzeigen oder auf Elemente in ihren Archivpostfächern anwenden; Richtlinien müssen vom Administrator bereitgestellt werden. Darüber hinaus können Benutzer von Outlook 2007 das lokale Postfach und das Archiv nicht gleichzeitig durchsuchen. <br/> 
<sup>3</sup> Sie können Outlook 2016 für Mac oder Outlook für Mac nicht zum Verschieben oder Kopieren von Ordnern, Kalenderelementen, Kontakten, Aufgaben oder Notizen in Ihrem Archiv oder zum Anzeigen dieser Elemente im Archivpostfach verwenden, wenn diese Elemente zuvor unter Verwendung einer anderen Version von Outlook (zum Beispiel Outlook 2016 für Windows) dorthin verschoben wurden. Weitere Informationen finden Sie unter [Verwenden Ihres Onlinearchivs bei Outlook 2016 für Mac](https://support.office.com/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238). 

## <a name="outlook-on-the-web"></a>Outlook im Web

Outlook im Web ist eine webbasierte Version des Outlook-E-Mail-Programms, die mit Exchange Online verwendet wird. Überall dort, wo Benutzer zu Hause, im Büro oder unterwegs mit dem Internet verbunden sind, &mdash; &mdash; können Sie über Outlook im Web auf Ihre e-Mails zugreifen.
  
Benutzer können auf Ihr Archiv zugreifen, indem Sie sich bei Outlook im Internet lokal anmelden (unter Verwendung derselben URL). Das Archiv wird neben dem primären Postfach in Outlook im Internet angezeigt. Es gibt keine explizite Möglichkeit, direkt aus Outlook im Internet auf das Archiv zuzugreifen.
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Archivierungsdienst Beschreibung](exchange-online-archiving-service-description.md).