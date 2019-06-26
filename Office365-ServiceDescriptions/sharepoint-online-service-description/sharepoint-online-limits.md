---
title: SharePoint Online-Grenzwerte
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Suchen Sie nach SharePoint Online-Grenzwerten für Office 365 Enterprise-Pläne und eigenständige Pläne.
ms.openlocfilehash: 2e99bcd4ed05f345757323359350a00161780b03
ms.sourcegitcommit: e77906b172913bb7b3359d649da59c5d2ee1123f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/26/2019
ms.locfileid: "35233532"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online-Grenzwerte 

Hier finden Sie die SharePoint-Grenzwerte für Office 365 Pläne und SharePoint Online eigenständige Pläne.
  
## <a name="limits-by-plan"></a>Grenzen nach Plan 

|||||
|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Office 365 Business Essentials oder Business Premium** <br/> |**Office 365 Enterprise E1, E3 oder E5 oder SharePoint Online Plan 1 oder 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Gesamtspeicher pro Organisation<sup>1, 2</sup> <br/> |1 TB plus 10 GB pro erworbener Lizenz  <br/> |1 TB plus 10 GB pro Lizenz erworben<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Max Storage pro Websitesammlung<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Websitesammlungen pro Organisation  <br/> |1 Million<sup>6</sup> <br/> |1 Million<sup>6</sup> <br/> |1 Million<br/> |
|Anzahl der Benutzer  <br/> |Bis zu 300  <br/> |1-500.000<sup>7</sup> <br/> |1-500.000<sup>7</sup> <br/> |
   
<sup>1</sup> Sie können eine unbegrenzte Menge an zusätzlichem SharePoint-Speicher erwerben. Weitere Informationen finden Sie unter [Ändern von Speicherplatz für Ihr Abonnement](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Es wird empfohlen, den Papierkorb zu überwachen und regelmäßig zu leeren. Der verwendete Speicherplatz ist Teil des gesamten Speichergrenzwerts der Organisation. 
<br/> <sup>3</sup> Wenn Sie über ein Office 365-Abonnement und ein Office 365 zusätzliches Dateispeicher-Add-on verfügen, werden die Speicher Beträge hinzugefügt. 
<br/> <sup>4</sup> hierbei handelt es sich um den Speichergrenzwert für eine einzelne Websitesammlung, nicht um die für jede Websitesammlung bereitgestellte Speichermenge. Dieser Grenzwert gilt für alle Arten von Websitesammlungen, einschließlich Office 365 Gruppen verbundenen Teamwebsites und OneDrive. SharePoint-Administratoren können [niedrigere Speichergrenzwerte manuell festlegen](https://docs.microsoft.com/sharepoint/manage-site-collection-storage-limits). 
<br/> <sup>5</sup> Mitarbeiter von First-Work können keine SharePoint-Websitesammlungen verwalten. 
<br/> <sup>6</sup> nicht einschließlich der OneDrive, die für jeden lizenzierten Benutzer erstellt wurden. 
<br/> <sup>7</sup> Wenn Sie über mehr als 500.000 Benutzer verfügen, wenden Sie sich an einen Microsoft-Vertriebsmitarbeiter. 
  
## <a name="service-limits-for-all-plans"></a>Dienst Grenzwerte für alle Pläne

- **Elemente in Listen und Bibliotheken** – eine Liste kann bis zu 30 Millionen Elemente aufweisen, und eine Bibliothek kann bis zu 30 Millionen Dateien und Ordner aufweisen. Nachdem 100.000 Elemente zu einer Liste, einer Bibliothek oder einem Ordner hinzugefügt wurden, kann die Vererbung von Berechtigungen für die Liste, die Bibliothek oder den Ordner nicht geändert werden. Weitere Informationen zu anderen Einschränkungen beim Anzeigenumfang reicher Listen finden Sie unter [Verwalten umfangreicher Listen und Bibliotheken in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Informationen zu Zeichen, die in Dateinamen nicht verwendet werden können, finden Sie unter [ungültige Zeichen in Datei-und Ordnernamen](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Dateigröße und Dateipfadlänge** -15 GB. Weitere Informationen zu Einschränkungen und Beschränkungen bei der Verwendung des neuen OneDrive-Synchronisierungs Clients (OneDrive. exe) finden Sie unter [ungültige Dateinamen und Dateitypen in OneDrive, OneDrive für Unternehmen und SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Verschieben und Kopieren über Websitesammlungen** – 100 GB pro Vorgang. Der Webbrowser muss geöffnet bleiben.

- **Sync** – für eine optimale Leistung wird empfohlen, nicht mehr als 300.000 Dateien für alle synchronisierten Dokumentbibliotheken zu speichern, selbst wenn Sie Dateien bei Bedarf verwenden oder nur einige Ordner innerhalb der zu synchronisierenden Bibliotheken auswählen. Wenn Sie den vorherigen OneDrive für Unternehmen synchronisierungsclient (Groove. exe) verwenden, beträgt der Synchronisierungs Grenzwert pro Bibliothek 20.000 Elemente (einschließlich 5.000 Elemente pro Teamwebsite).

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
