---
title: Freigabe und Zusammenarbeit
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-sharing-and-collaboration
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 862dab54-701f-4014-a594-0b71e03772d2
ms.openlocfilehash: ca55a389f5ed117b09b6c10ca1b2caf42bf01be0
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246361"
---
# <a name="sharing-and-collaboration"></a>Freigabe und Zusammenarbeit

## <a name="federated-sharing"></a>Verbundfreigabe

Verbund bezieht sich auf die zugrunde liegende Vertrauensstellungsinfrastruktur, die die Verbundfreigabe unterstützt. Dies ist eine Methode für Microsoft Exchange Online-Benutzer, Frei/Gebucht-Kalenderdaten und Kontaktinformationen für Empfänger in anderen externen Verbundorganisationen oder für Benutzer mit Internetzugriff freizugeben. Dazu gehören Organisationen, die von Exchange Online gehostet werden, oder externe Microsoft Exchange Server 2010- oder Exchange Server 2013-Organisationen. Durch die Verwendung von Organisationsbeziehungen und Freigaberichtlinien können Exchange Online-Administratoren Benutzer in die Lage versetzen, Einladungen für die Kalenderfreigabe über Microsoft Outlook Web App bzw. Microsoft Outlook 2010 oder höher zu senden.
  
> [!IMPORTANT]
>  Externe Exchange 2010- und Exchange 2013-Organisationen müssen bei der Konfiguration der Verbundfreigabe eine Verbundvertrauensstellung mit Microsoft Federation Gateway konfigurieren. Exchange Online-Organisationen müssen keine Verbundvertrauensstellung konfigurieren, denn die Verbundvertrauensstellung mit Microsoft Federation Gateway wird automatisch bei der Erstellung des Office 365-Mandanten erstellt. >  Exchange Online-Organisationen müssen entweder eine Organisationsbeziehung oder eine Freigaberichtlinie erstellen, um eine Verbundfreigabe zu ermöglichen. >  Die Freigabe der globalen Adressliste (GAL) oder das Verschieben von Benutzerpostfächern zwischen Exchange Online-Organisationen in unterschiedliche Office 365-Mandanten wird für die Verbundfreigabe nicht unterstützt. 
  
Weitere Informationen zur Verbundfreigabe finden Sie unter [Freigabe in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271774).
  
## <a name="site-mailboxes"></a>Websitepostfächer

E-Mails und Dokumente werden herkömmlicherweise in zwei voneinander getrennten Datenrepositorys gespeichert. Die meisten Teams arbeiten mithilfe von E-Mails und Dokumenten zusammen. Die Herausforderung liegt darin, dass mit unterschiedlichen Clients auf E-Mails und Dokumente zugegriffen wird. Dies reduziert üblicherweise sowohl die Benutzerfreundlichkeit als auch die Benutzerproduktivität.
  
Das Websitepostfach ist ein neues Konzept in Exchange 2013, mit dem dieses Problem gelöst werden soll. Mit Websitepostfächern werden die Zusammenarbeit und die Benutzerproduktivität verbessert, indem die Benutzer über die gleiche Clientoberfläche auf Microsoft SharePoint 2013-Dokumente und Exchange-E-Mails zugreifen können. Ein Websitepostfach besteht funktional aus der Mitgliedschaft in einer SharePoint 2013-Website (Besitzer und Mitglieder), gemeinsam genutztem Speicher in einem Exchange 2013-Postfach für E-Mails und einer SharePoint 2013-Website für Dokumente sowie einer Verwaltungsoberfläche für Bereitstellungs- und Lebenszyklusanforderungen.
  
> [!IMPORTANT]
> Ihr Office 365-Plan muss SharePoint umfassen. Für Websitepostfächer ist es erforderlich, dass Benutzer über SharePoint- und Exchange-Lizenzen verfügen. 
  
Weitere Informationen zu Websitepostfächern finden Sie unter [Websitepostfächer](https://go.microsoft.com/fwlink/p/?LinkId=271789).
  
## <a name="public-folders"></a>Öffentliche Ordner

Öffentliche Ordner in Exchange Online wurden modernisiert, um die vorhandenen Technologien für hohe Verfügbarkeit und Speicherung der Postfachdatenbank zu nutzen. Die Architektur für öffentliche Ordner verwendet speziell entworfene Postfächer, um sowohl die Hierarchie als auch die Inhalte öffentlicher Ordner zu speichern. Dies bedeutet, dass keine gesonderte Datenbank für öffentliche Ordner mehr vorhanden ist. Für die Replikation öffentlicher Ordner wird jetzt das Modell der fortlaufenden Replikation eingesetzt. Die hohe Verfügbarkeit der Hierarchie und der Inhaltspostfächer wird durch eine Database Availability Group (DAG) im Datencenter bereitgestellt. In Exchange Online sind Sie auf 1000 Postfächer für Öffentliche Ordner beschränkt. Für jedes Postfach für öffentliche Ordner gilt außerdem eine maximale Speichergröße. Weitere Informationen finden Sie im Abschnitt "Begrenzungen für Postfachordner" unter [Exchange Online-Begrenzungen](exchange-online-limits.md). Postfächer mit öffentlichen Ordnern haben dieselben Warngrenzen bei Nachrichten-/Empfängeranzahl und Kapazität wie normale Postfächer. Weitere Informationen finden Sie unter [Empfänger](recipients.md). 
  
Weitere Informationen zu öffentlichen Ordnern finden Sie im Artikel zum Thema [Öffentliche Ordner](https://go.microsoft.com/fwlink/p/?LinkId=271790).
  
## <a name="group-and-shared-mailboxes"></a>Gruppenpostfächer und freigegebene Postfächer

Gruppenpostfächer und freigegebene Postfächer vereinfachen einer speziellen Gruppe von Personen das Überwachen und Senden von E-Mails von einem gemeinsamen Konto wie einer öffentlichen E-Mail-Adresse aus (z. B. „info@contoso.com" oder „contact@contoso.com"). Wenn eine Person in der Gruppe auf eine an das freigegebene Postfach gesendete Nachricht antwortet, hat es den Anschein, als stamme die E-Mail vom freigegebenen Postfach und nicht von dem bestimmten Benutzer.
  
Gruppenpostfächer oder freigegebene Postfächer erfordern keine separate Benutzerlizenz. Wenn jedoch das In-Situ-Archiv für ein Gruppenpostfach oder ein freigegebenes Postfach aktiviert werden soll, müssen Sie diesem eine Exchange Online Plan 1- oder Exchange Online Plan 2-Lizenz zuweisen. Nach Zuweisung der Lizenz wird die Postfachgröße auf die Größe im lizenzierten Plan erhöht. Soll der In-Situ-Speicher für ein freigegebenes Postfach aktiviert werden, müssen Sie diesem eine Exchange Online Plan 2-Lizenz zuweisen. Beachten Sie, dass Gruppenpostfächern derzeit nicht zugewiesen werden können, sie sollten aber in der Gesamtzahl von Lizenzen berücksichtigt werden.
  
Im In-Situ-Archiv können lediglich Mails für einen einzelnen Benutzer oder eine einzelne Entität (z. B. ein freigegebenes Postfach) archiviert werden, für die eine Lizenz angewendet wurde. Ein In-Situ-Archiv darf nicht zum Speichern von Mails von mehreren Benutzern oder Entitäten verwendet werden. Ein IT-Administrator ist beispielsweise nicht berechtigt, ein freigegebenes Postfach zu erstellen und die Benutzer anzuweisen, dieses freigegebene Postfach zum expliziten Zweck der Archivierung in E-Mails zu adressieren (auf CC oder BCC bzw. über eine Transportregel). Ein freigegebenes Postfach, das von mehreren Benutzern verwendet wird, speichert keine E-Mails für die einzelnen Benutzer. Mehrere Benutzer können darauf zugreifen und E-Mails als das freigegebene Postfach senden. Aus diesem Grund werden im freigegebenen Postfach nur die E-Mails gespeichert, die an das freigegebene Postfach und von diesem Postfach gesendet werden.
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, für eigenständige Produkte und lokale Lösungen finden Sie in der [Exchange Online-Dienstbeschreibung](exchange-online-service-description.md).
  

