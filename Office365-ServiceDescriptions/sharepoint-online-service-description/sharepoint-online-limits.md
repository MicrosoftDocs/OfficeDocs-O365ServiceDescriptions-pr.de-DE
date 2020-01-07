---
title: SharePoint Online-Beschränkungen
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Suchen Sie nach SharePoint Online-Grenzwerten für Office 365 Enterprise-Pläne und eigenständige Pläne.
ms.openlocfilehash: acf9731e4515a345f0cc9e0ac676c5ac8ed13ed4
ms.sourcegitcommit: 3417565ac5e101726865f3f6cfb8d13317350693
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/07/2020
ms.locfileid: "40952036"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online-Beschränkungen

Hier finden Sie die SharePoint-Grenzwerte für Office 365 Pläne und SharePoint Online eigenständige Pläne.
  
## <a name="limits-by-plan"></a>Grenzen nach Plan 

|||||
|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Office 365 Business Essentials oder Business Premium** <br/> |**Office 365 Enterprise E1, E3 oder E5 oder SharePoint Online Plan 1 oder 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Gesamtspeicher pro Organisation<sup>1, 2, 6</sup> <br/> |1 TB plus 10 GB pro erworbener Lizenz  <br/> |1 TB plus 10 GB pro Lizenz erworben<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Max Storage pro Websitesammlung<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Websitesammlungen pro Organisation  <br/> |2 Millionen<sup>6</sup> <br/> |2 Millionen<sup>6</sup> <br/> |2 Millionen<br/> |
|Anzahl der Benutzer  <br/> |Bis zu 300  <br/> |1-500.000<sup>7</sup> <br/> |1-500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [erfahren Sie, wie Sie den gesamten und den verfügbaren Speicher für Ihre Organisation ermitteln können](/sharepoint/manage-site-collection-storage-limits). Sie können eine unbegrenzte Menge an zusätzlichem SharePoint-Speicher erwerben. Weitere Informationen finden Sie unter [Ändern von Speicherplatz für Ihr Abonnement](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Es wird empfohlen, den Papierkorb zu überwachen und regelmäßig zu leeren. Der verwendete Speicherplatz ist Teil des gesamten Speichergrenzwerts der Organisation. 
<br/> <sup>3</sup> Wenn Sie über ein Office 365-Abonnement und ein Office 365 zusätzliches Dateispeicher-Add-on verfügen, werden die Speicher Beträge hinzugefügt. 
<br/> <sup>4</sup> hierbei handelt es sich um den Speichergrenzwert für eine einzelne Websitesammlung, nicht um die für jede Websitesammlung bereitgestellte Speichermenge. Dieser Grenzwert gilt für alle Arten von Websitesammlungen, einschließlich Office 365 Gruppen verbundenen Teamwebsites und OneDrive. SharePoint-Administratoren können [niedrigere Speichergrenzwerte manuell festlegen](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> Mitarbeiter von First-Work können keine SharePoint-Websitesammlungen verwalten. 
<br/> <sup>6</sup> nicht einschließlich der OneDrive, die für jeden lizenzierten Benutzer erstellt wurden. 
<br/> <sup>7</sup> Wenn Sie über mehr als 500.000 Benutzer verfügen, wenden Sie sich an einen Microsoft-Vertriebsmitarbeiter. 
  
## <a name="service-limits-for-all-plans"></a>Dienst Grenzwerte für alle Pläne

- **Elemente in Listen und Bibliotheken** – eine Liste kann bis zu 30 Millionen Elemente aufweisen, und eine Bibliothek kann bis zu 30 Millionen Dateien und Ordner aufweisen. Nachdem 100.000 Elemente zu einer Liste, einer Bibliothek oder einem Ordner hinzugefügt wurden, kann die Vererbung von Berechtigungen für die Liste, die Bibliothek oder den Ordner nicht geändert werden. Weitere Informationen zu anderen Einschränkungen beim Anzeigenumfang reicher Listen finden Sie unter [Verwalten umfangreicher Listen und Bibliotheken in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). 

- **Dateigröße und Dateipfadlänge** -15 GB. Die maximale Größe für an Listenelemente angefügte Dateien beträgt 250 MB. Weitere Informationen zu Einschränkungen und Beschränkungen bei der Verwendung des neuen OneDrive-Synchronisierungs Clients (OneDrive. exe) finden Sie unter [ungültige Dateinamen und Dateitypen](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Verschieben und Kopieren über Websitesammlungen** – 100 GB pro Vorgang. Der Webbrowser muss geöffnet bleiben.

- **Sync** – für eine optimale Leistung wird empfohlen, nicht mehr als 300.000 Dateien für alle synchronisierten Dokumentbibliotheken zu speichern, selbst wenn Sie Dateien bei Bedarf verwenden oder nur einige Ordner innerhalb der zu synchronisierenden Bibliotheken auswählen.

    Wenn Sie den vorherigen OneDrive für Unternehmen synchronisierungsclient (Groove. exe) verwenden, können Sie insgesamt bis zu 20.000 Elemente für alle synchronisierten Bibliotheken synchronisieren. Dazu gehören OneDrive für Unternehmen Bibliotheken, Teamwebsite-Bibliotheken oder beides. Unabhängig vom gesamten Synchronisierungs Grenzwert gibt es Einschränkungen für die Anzahl der Elemente, die für jeden Bibliotheks synchronisiert werden können:
    - Sie können bis zu 20.000 Elemente in einer OneDrive für Unternehmen Bibliothek synchronisieren. Dies umfasst Ordner und Dateien. 
    - Sie können bis zu 5.000 Elemente in einer SharePoint-Bibliothek synchronisieren. Dies umfasst Ordner und Dateien. Dabei handelt es sich um Bibliotheken, die Sie auf verschiedenen SharePoint-Websites finden, wie Teamwebsites und Community-Websites, Bibliotheken, die von anderen Benutzern erstellt wurden oder die Sie auf der Seite Websites erstellt haben. Sie können mehrere SharePoint-Bibliotheken synchronisieren. Alle Teamwebsites, die Sie synchronisieren, gelten auch für die gesamte 20.000-Elementgrenze für alle synchronisierten Bibliotheken.

    > [!NOTE]
    > Wenn Benutzer Dateien in Dokumentbibliotheken mit Hunderten von Tausenden von Dateien synchronisieren müssen, können Sie Ordner aus dem synchronisierungsclient ausblenden, indem Sie die Berechtigungsstufe der Ordner auf "Eingeschränkter Lesezugriff" festlegen. 

- **Versionen** -50.000 Hauptversionen und 511 Nebenversionen.

- **SharePoint-Gruppen** : ein Benutzer kann 5.000-Gruppen angehören, und jede Gruppe kann bis zu 5.000 Benutzer haben. Sie können bis zu 10.000 Gruppen pro Websitesammlung haben.
    > [!NOTE]
    > Informationen zu Azure AD Gruppenbeschränkungen finden Sie unter [Azure Ad Service Limits and Restrictions](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) , da diese Grenzwerte sich auf öffentliche und private Gruppen Websites für die Mitgliedschaftsverwaltung auswirken können. 
- **Verwaltete Metadaten** – 200.000 Ausdrücke in Term Store, 1.000 globale Ausdruckssätze, 1.000 Gruppen.

- Unter **Websites** -2.000 pro Websitesammlung.

- **Gehostete SharePoint-Anwendungen** -20.000 Instanzen pro Organisation.

- **Eindeutige Sicherheitsbereiche pro Liste oder Bibliothek** – 5.000. Bei umfangreichen Listen sollte Design so wenig eindeutige Berechtigungen wie möglich aufweisen.

- **Users** -2 Millionen pro Websitesammlung.
    > [!NOTE]
    > Es gibt keine Beschränkung für die Anzahl der Gäste, die Sie zu SharePoint-Websitesammlungen einladen können. Weitere Informationen zur externen Freigabe finden Sie unter [External Sharing Overview](https://docs.microsoft.com/sharepoint/external-sharing-overview).
## <a name="see-also"></a>Siehe auch

[Such Grenzwerte für SharePoint Online](https://docs.microsoft.com/sharepoint/search-limits)
