---
title: Freigabe und Zusammenarbeit
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: 1afee4f2868a8bf0f0a1662e2d70bd8de3f2043a
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653297"
---
# <a name="sharing-and-collaboration"></a>Freigabe und Zusammenarbeit

## <a name="federated-sharing"></a>Verbundfreigabe

Partnerverbund bezieht sich auf die zugrunde liegende Vertrauensinfrastruktur, die die Verbundfreigabe unterstützt, eine Methode für Microsoft Exchange Online-Benutzer zum Freigeben von Frei/Gebucht-Kalenderdaten und Kontaktinformationen für Empfänger in anderen externen Verbundorganisationen oder für Benutzer mit Internetzugang. Dazu gehören Organisationen, die auch von Exchange Online oder externen organisationen Microsoft Exchange Server 2010 oder Exchange Server 2013 gehostet werden. Mithilfe von Organisationsbeziehungen und Freigaberichtlinien können Exchange Online Benutzern das Senden von Kalenderfreigabeeinladungen von Microsoft Outlook im Web oder Microsoft Outlook 2010 oder höher ermöglichen.
  
> [!IMPORTANT]
>  Externe Exchange 2010- und Exchange 2013-Organisationen müssen bei der Konfiguration der Verbundfreigabe eine Verbundvertrauensstellung mit Microsoft Federation Gateway konfigurieren. Exchange Online Organisationen keine Verbundvertrauensstellung konfigurieren müssen– die Verbundvertrauensstellung mit dem Microsoft Federation Gateway wird automatisch erstellt, wenn die Microsoft 365 erstellt wird. 
>
>  Exchange Online Organisationen müssen entweder eine Organisationsbeziehung oder eine Freigaberichtlinie konfigurieren, um die Verbundfreigabe zu aktivieren. 
>
>  Die Freigabe globaler Zugriffslisten (GALs) oder das Verschieben von Benutzerpostfächern zwischen Exchange Online Organisationen in verschiedenen Microsoft-Plänen wird in der Verbundfreigabe nicht unterstützt. 
  
Weitere Informationen zur Verbundfreigabe finden Sie unter [Freigabe in Exchange Online](/exchange/sharing/sharing).
  
## <a name="site-mailboxes"></a>Websitepostfächer

E-Mails und Dokumente werden herkömmlicherweise in zwei voneinander getrennten Datenrepositorys gespeichert. Die meisten Teams arbeiten mithilfe von E-Mails und Dokumenten zusammen. Die Herausforderung liegt darin, dass mit unterschiedlichen Clients auf E-Mails und Dokumente zugegriffen wird. Dies reduziert üblicherweise sowohl die Benutzerfreundlichkeit als auch die Benutzerproduktivität.
  
Das Websitepostfach ist ein neues Konzept in Exchange 2013, mit dem dieses Problem gelöst werden soll. Mit Websitepostfächern werden die Zusammenarbeit und die Benutzerproduktivität verbessert, indem die Benutzer über die gleiche Clientoberfläche auf Microsoft SharePoint 2013-Dokumente und Exchange-E-Mails zugreifen können. Ein Websitepostfach besteht funktional aus der Mitgliedschaft in einer SharePoint 2013-Website (Besitzer und Mitglieder), gemeinsam genutztem Speicher in einem Exchange 2013-Postfach für E-Mails und einer SharePoint 2013-Website für Dokumente sowie einer Verwaltungsoberfläche für Bereitstellungs- und Lebenszyklusanforderungen.
  
> [!IMPORTANT]
> Ihr Plan muss SharePoint. Für Websitepostfächer ist es erforderlich, dass Benutzer über SharePoint- und Exchange-Lizenzen verfügen. 
  
Weitere Informationen zu Websitepostfächern finden Sie unter [Websitepostfächer](/exchange/collaboration-exo/collaboration-exo).
  
## <a name="public-folders"></a>Öffentliche Ordner

Öffentliche Ordner in Exchange Online wurden modernisiert, um die vorhandenen Technologien für hohe Verfügbarkeit und Speicherung der Postfachdatenbank zu nutzen. Die Architektur für öffentliche Ordner verwendet speziell entworfene Postfächer, um sowohl die Hierarchie als auch die Inhalte öffentlicher Ordner zu speichern. Dies bedeutet, dass keine gesonderte Datenbank für öffentliche Ordner mehr vorhanden ist. Für die Replikation öffentlicher Ordner wird jetzt das Modell der fortlaufenden Replikation eingesetzt. Die hohe Verfügbarkeit der Hierarchie und der Inhaltspostfächer wird durch eine Database Availability Group (DAG) im Datencenter bereitgestellt. In Exchange Online sind Sie auf 1.000 Postfächer für öffentliche Ordner beschränkt. Für jedes Postfach für öffentliche Ordner gilt außerdem eine maximale Speichergröße. Weitere Informationen finden Sie im Abschnitt "Postfachordnerbeschränkungen" unter [Exchange Online .](exchange-online-limits.md) Postfächer mit öffentlichen Ordnern haben dieselben Warngrenzen bei Nachrichten-/Empfängeranzahl und Kapazität wie normale Postfächer. Weitere Informationen finden Sie unter [Empfänger](recipients.md). 
  
Weitere Informationen zu öffentlichen Ordnern finden Sie im Artikel zum Thema [Öffentliche Ordner](/exchange/collaboration-exo/public-folders/public-folders).
  
## <a name="group-and-shared-mailboxes"></a>Gruppen- und freigegebene Postfächer

Gruppen- und freigegebene Postfächer machen es einer bestimmten Gruppe von Personen leicht, E-Mails von einem allgemeinen Konto wie öffentlichen E-Mail-Adressen (z. B. info@contoso.com oder contact@contoso.com) zu überwachen und zu senden. Wenn eine Person in der Gruppe auf eine Nachricht antwortet, die an das freigegebene Postfach gesendet wird, scheint die E-Mail vom freigegebenen Postfach und nicht vom einzelnen Benutzer zu sein.
  
In der Regel erfordern Gruppenpostfächer oder freigegebene Postfächer keine separate Benutzerlizenz. Um jedoch In-Place Archiv für eine Gruppe oder ein freigegebenes Postfach zu aktivieren, müssen Sie ihm eine Exchange Online Plan 1- oder Exchange Online Plan 2-Lizenz zuweisen. Nach Zuweisung der Lizenz wird die Postfachgröße auf die Größe im lizenzierten Plan erhöht. Um ein freigegebenes Postfach in In-Place zu setzen, müssen Sie ihm eine Exchange Online Plan 2-Lizenz zuweisen. Bitte beachten Sie, dass Gruppenpostfächer zu diesem Zeitpunkt nicht zugewiesen werden können, aber in Ihren Gesamtlizenzen berücksichtigt werden sollten.
  
In-Place Archive kann nur zum Archivieren von E-Mails für einen einzelnen Benutzer oder eine entität (z. B. ein freigegebenes Postfach) verwendet werden, für den eine Lizenz angewendet wurde. Es ist In-Place, E-Mails von mehreren Benutzern oder Entitäten zu speichern. Ein IT-Administrator ist beispielsweise nicht berechtigt, ein freigegebenes Postfach zu erstellen und die Benutzer anzuweisen, dieses freigegebene Postfach zum expliziten Zweck der Archivierung in E-Mails zu adressieren (auf CC oder BCC bzw. über eine Transportregel). Ein freigegebenes Postfach, das von mehreren Benutzern verwendet wird, speichert keine E-Mails für die einzelnen Benutzer. Mehrere Benutzer können darauf zugreifen und E-Mails als das freigegebene Postfach senden. Aus diesem Grund werden im freigegebenen Postfach nur die E-Mails gespeichert, die an das freigegebene Postfach und von diesem Postfach gesendet werden.
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie [unter Exchange Online Service description](exchange-online-service-description.md).
