---
title: Freigabe und Zusammenarbeit
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 8e5ce6ce41f206c5736241340c393833ae78fea7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132589"
---
# <a name="sharing-and-collaboration"></a>Freigabe und Zusammenarbeit

## <a name="federated-sharing"></a>Verbundfreigabe

Verbund bezieht sich auf die zugrunde liegende Vertrauensinfrastruktur, die die Verbundfreigabe unterstützt, eine Methode für Microsoft Exchange Online Benutzer zum Freigeben von Frei/Gebucht-Kalenderdaten und Kontaktinformationen für Empfänger in anderen externen Verbundorganisationen oder mit Benutzern, die über Internetzugriff verfügen. Dazu gehören auch Organisationen, die von Exchange Online oder externen Microsoft Exchange Server 2010 oder Exchange Server 2013 Organisationen gehostet werden. Mithilfe von Organisationsbeziehungen und Freigaberichtlinien können Exchange Online Administratoren Benutzern das Senden von Einladungen zur Kalenderfreigabe aus Microsoft Outlook im Internet oder Microsoft Outlook 2010 oder höher ermöglichen.
  
> [!IMPORTANT]
>  Externe Exchange 2010- und Exchange 2013-Organisationen müssen bei der Konfiguration der Verbundfreigabe eine Verbundvertrauensstellung mit Microsoft Federation Gateway konfigurieren. Exchange Online Organisationen keine Verbundvertrauensstellung konfigurieren müssen – die Verbundvertrauensstellung mit dem Microsoft Federation Gateway wird automatisch erstellt, wenn die Microsoft 365-Organisation erstellt wird. 
>
>  Exchange Online Organisationen müssen entweder eine Organisationsbeziehung oder eine Freigaberichtlinie konfigurieren, um die Verbundfreigabe zu aktivieren. 
>
>  Die Freigabe von globalen Zugriffslisten (GAL) oder das Verschieben von Benutzerpostfächern zwischen Exchange Online Organisationen in unterschiedlichen Microsoft-Plänen wird in der Verbundfreigabe nicht unterstützt. 
  
Weitere Informationen zur Verbundfreigabe finden Sie unter [Freigabe in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
## <a name="site-mailboxes"></a>Websitepostfächer

Email and documents are traditionally kept in two unique and separate data repositories. Most teams collaborate by using both email and documents. The challenge is that email and documents are accessed by using different clients. This usually results in a reduction in user productivity and a degraded user experience.
  
The site mailbox is a new concept in Exchange 2013 that attempts to solve this problem. Site mailboxes improve collaboration and user productivity by using the same client interface to allow access to both Microsoft SharePoint 2013 documents and Exchange email. A site mailbox functionally consists of SharePoint 2013 site membership (owners and members), shared storage through an Exchange 2013 mailbox for email messages and a SharePoint 2013 site for documents, and a management interface that addresses provisioning and life cycle needs.
  
> [!IMPORTANT]
> Ihr Plan muss SharePoint enthalten. Für Websitepostfächer ist es erforderlich, dass Benutzer über SharePoint- und Exchange-Lizenzen verfügen. 
  
Weitere Informationen zu Websitepostfächern finden Sie unter [Websitepostfächer](https://go.microsoft.com/fwlink/p/?LinkId=271789).
  
## <a name="public-folders"></a>Öffentliche Ordner

Öffentliche Ordner in Exchange Online wurden modernisiert, um die vorhandenen Technologien für hohe Verfügbarkeit und Speicherung der Postfachdatenbank zu nutzen. Die Architektur für öffentliche Ordner verwendet speziell entworfene Postfächer, um sowohl die Hierarchie als auch die Inhalte öffentlicher Ordner zu speichern. Dies bedeutet, dass keine gesonderte Datenbank für öffentliche Ordner mehr vorhanden ist. Für die Replikation öffentlicher Ordner wird jetzt das Modell der fortlaufenden Replikation eingesetzt. Die hohe Verfügbarkeit der Hierarchie und der Inhaltspostfächer wird durch eine Database Availability Group (DAG) im Datencenter bereitgestellt. In Exchange Online sind Sie auf 1000 Postfächer für Öffentliche Ordner limitiert. Für jedes Postfach für öffentliche Ordner gilt außerdem eine maximale Speichergröße. Weitere Informationen finden Sie im Abschnitt "Grenzwerte für Postfachordner" in [Exchange Online Grenzwerte](exchange-online-limits.md). Postfächer mit öffentlichen Ordnern haben dieselben Warngrenzen bei Nachrichten-/Empfängeranzahl und Kapazität wie normale Postfächer. Weitere Informationen finden Sie unter [Empfänger](recipients.md). 
  
Weitere Informationen zu öffentlichen Ordnern finden Sie im Artikel zum Thema [Öffentliche Ordner](https://go.microsoft.com/fwlink/p/?LinkId=271790).
  
## <a name="group-and-shared-mailboxes"></a>Gruppen-und freigegebene Postfächer

Gruppen-und freigegebene Postfächer erleichtern einer bestimmten Gruppe von Personen das überwachen und Senden von e-Mails von einem gemeinsamen Konto wie öffentliche e-Mail-Adressen (beispielsweise Info@contoso.com oder Contact@contoso.com). Wenn eine Person in der Gruppe auf eine Nachricht antwortet, die an das freigegebene Postfach gesendet wurde, scheint die e-Mail aus dem freigegebenen Postfach, nicht aus dem einzelnen Benutzer zu sein.
  
In der Regel ist für Gruppen-oder freigegebene Postfächer keine separate Benutzerlizenz erforderlich. Um jedoch das in-Place-Archiv für eine Gruppe oder ein freigegebenes Postfach zu aktivieren, müssen Sie eine Exchange Online Plan 1 oder Exchange Online Plan 2 License zuweisen. Nach Zuweisung der Lizenz wird die Postfachgröße auf die Größe im lizenzierten Plan erhöht. Wenn Sie ein freigegebenes Postfach in einem Compliance-Archiv speichern möchten, müssen Sie ihm eine Lizenz für Exchange Online Plan 2 zuweisen. Beachten Sie, dass Gruppen Postfächer zu diesem Zeitpunkt nicht zugewiesen werden können, sondern in ihren Gesamt Lizenzen berücksichtigt werden sollten.
  
Das in-Place-Archiv kann nur zum Archivieren von e-Mails für einen einzelnen Benutzer oder eine einzelne Entität (beispielsweise ein freigegebenes Postfach) verwendet werden, für das eine Lizenz angewendet wurde. Das Verwenden eines in-Place-Archivs als Möglichkeit zum Speichern von e-Mails von mehreren Benutzern oder Entitäten ist untersagt. Ein IT-Administrator ist beispielsweise nicht berechtigt, ein freigegebenes Postfach zu erstellen und die Benutzer anzuweisen, dieses freigegebene Postfach zum expliziten Zweck der Archivierung in E-Mails zu adressieren (auf CC oder BCC bzw. über eine Transportregel). Ein freigegebenes Postfach, das von mehreren Benutzern verwendet wird, speichert keine E-Mails für die einzelnen Benutzer. Mehrere Benutzer können darauf zugreifen und E-Mails als das freigegebene Postfach senden. Daher sind die einzigen e-Mails, die im freigegebenen Postfach gespeichert werden, die, die an oder von ihr gesendet werden, als freigegebenes Postfach.
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  

