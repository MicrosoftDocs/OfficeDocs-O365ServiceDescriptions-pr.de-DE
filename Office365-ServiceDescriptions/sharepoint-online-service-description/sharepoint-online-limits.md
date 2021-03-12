---
title: SharePoint-Beschränkungen
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Erfahren Sie mehr über die SharePoint-Grenzwerte für Microsoft 365 und eigenständige Pläne.
ms.openlocfilehash: 12baba7f9da374e88825b97aef30182f9b2014f5
ms.sourcegitcommit: 34fd77f26c3fde723680c82af1004dffc143c823
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/11/2021
ms.locfileid: "50726760"
---
# <a name="sharepoint-limits"></a>SharePoint-Beschränkungen

Erfahren Sie mehr über die Dienstbeschränkungen in SharePoint für Microsoft 365.
  
## <a name="limits-by-plan"></a>Grenzwerte nach Plan 

| Feature | Microsoft 365 Business Basic, Business Standard oder Business Premium | Microsoft 365 E3 oder E5, Office 365 E1, E3 oder E5 oder SharePoint Plan 1 oder 2 | Microsoft 365 F1 oder F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Gesamtspeicher pro Organisation<sup>1, 2, 6</sup> <br/> |1 TB plus 10 GB pro erworbener<sup>Lizenz 3</sup>  <br/> |1 TB plus 10 GB pro erworbener<sup>Lizenz 3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Maximaler Speicher pro Website (Websitesammlung)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Websites (Websitesammlungen) pro Organisation  <br/> |2 Millionen<sup>6</sup> <br/> |2 Millionen<sup>6</sup> <br/> |2 Millionen<br/> |
|Anzahl der Benutzer  <br/> |Bis zu 300  <br/> |1-500.000<sup>7</sup> <br/> |1-500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [Erfahren Sie, wie Sie den gesamten und verfügbaren Speicher für Ihre Organisation finden.](/sharepoint/manage-site-collection-storage-limits) Sie können eine unbegrenzte Menge an zusätzlichem SharePoint-Speicher erwerben. Weitere Informationen finden Sie unter [Ändern von Speicherplatz für Ihr Abonnement](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Es wird empfohlen, den Papierkorb zu überwachen und regelmäßig zu leeren. Der von ihr verbrauchte Speicherplatz ist Teil des gesamten Speicherlimits der Organisation. 
<br/> <sup>3</sup> Wenn Sie über ein Microsoft 365-Abonnement und ein Office 365 Extra File Storage-Add-On verfügen, werden die Speichermengen hinzugefügt. 
<br/> <sup>4</sup> Dies  ist der Speichergrenzwert für eine einzelne Website (zuvor als "Websitesammlung" bezeichnet), nicht die Menge an *Speicherplatz,* die für jede Website bereitgestellt wird. Dieser Grenzwert gilt für alle Arten von Websites, einschließlich Office 365-Teamwebsites mit Gruppen und OneDrive. SharePoint-Administratoren können [manuell niedrigere Speichergrenzwerte festlegen.](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits) 
<br/> <sup>5</sup> Firstline Workers können keine SharePoint-Websites verwalten. 
<br/> <sup>6</sup> Nicht einschließlich des oneDrive, das für jeden lizenzierten Benutzer erstellt wurde. 
<br/> <sup>7</sup> Wenn Sie mehr als 500.000 Benutzer haben, wenden Sie sich an einen Microsoft-Vertreter. 
  
## <a name="service-limits-for-all-plans"></a>Dienstbeschränkungen für alle Pläne

### <a name="items-in-lists-and-libraries"></a>Elemente in Listen und Bibliotheken

Eine Liste kann bis zu 30 Millionen Elemente enthalten, und eine Bibliothek kann bis zu 30 Millionen Dateien und Ordner enthalten. Wenn eine Liste, Bibliothek oder ein Ordner mehr als 100.000 Elemente enthält, können Sie die Vererbung von Berechtigungen für die Liste, Bibliothek oder den Ordner nicht brechen. Sie können auch keine Berechtigungen erneut erben. Sie können jedoch die Vererbung für die einzelnen Elemente in dieser Liste, Bibliothek oder in diesem Ordner bis zur maximalen Anzahl eindeutiger Berechtigungen in der Liste oder Bibliothek (siehe nächsten Abschnitt) weiterhin unterbrechen. Weitere Informationen zu anderen Einschränkungen für das Anzeigen großer Listen finden Sie unter Verwalten großer Listen und Bibliotheken [in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="unique-security-scopes-per-list-or-library"></a>Eindeutige Sicherheitsbereiche pro Liste oder Bibliothek

Bei großen Listen muss der Entwurf so wenige eindeutige Berechtigungen wie möglich besitzen und insgesamt unter 5.000 bleiben.

### <a name="file-size-and-file-path-length"></a>Dateigröße und Dateipfadlänge

250 GB. Weitere Informationen zu Einschränkungen und Beschränkungen bei verwendung der neuen OneDrive-Synchronisierungs-App (OneDrive.exe) finden Sie unter [Ungültige Dateinamen und Dateitypen](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Verschieben und Kopieren über Websites hinweg

Das Kopieren/Verschieben mehrerer Dateien in einem einzelnen Vorgang hat drei Anforderungen:

- Dateigröße von nicht mehr als 100 GB
- Nicht mehr als 30.000 Dateien
- Jede Datei muss kleiner als 15 GB sein.

### <a name="sync"></a>Synchronisierung

Für eine optimale Leistung wird empfohlen, nicht mehr als 300.000 Dateien in einer einzelnen OneDrive- oder Teamwebsitebibliothek zu speichern. Obwohl SharePoint Online 30 Millionen Dokumente pro Bibliothek speichern kann, empfehlen wir für eine optimale Leistung die Synchronisierung von nicht mehr als 300.000 Dateien in allen Dokumentbibliotheken. Darüber hinaus können dieselben Leistungsprobleme auftreten, wenn Sie über 300.000 Elemente oder mehr in allen Bibliotheken verfügen, die Sie synchronisieren, auch wenn Sie nicht alle Elemente in diesen Bibliotheken synchronisieren. Wenn Sie den vorherigen OneDrive for Groove.exe (Groove.exe) verwenden, beträgt der Synchronisierungsgrenzwert pro Bibliothek 20.000 Elemente (einschließlich 5.000 Elemente pro Teamwebsite).

### <a name="versions"></a>Versionen

50.000 Hauptversionen und 511 Nebenversionen.

### <a name="sharepoint-groups"></a>SharePoint-Gruppen

Ein Benutzer kann zu 5.000 Gruppen pro Website (Websitesammlung) gehören, und jede Gruppe kann bis zu 5.000 Benutzer haben. Pro Website (Websitesammlung) können bis zu 10.000 Gruppen vorhanden sein.

> [!NOTE]
> Informationen zu Azure AD-Gruppenbeschränkungen finden Sie unter [Azure AD-Dienstbeschränkungen](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) und -Einschränkungen, da solche Beschränkungen sich auf die Verwaltung der Mitgliedschaft von öffentlichen und privaten Gruppenwebsites auswirken können.

### <a name="managed-metadata"></a>Verwaltete Metadaten

200.000 Begriffe im Laufzeitspeicher, 1.000 globale Ausdruckssätze, 1.000 Gruppen.

### <a name="overall-site-metadata"></a>Allgemeine Websitemetadaten

1000 GB pro Standort (Metadaten erreichen selten diese Größe).

### <a name="subsites"></a>Unterwebsites

2.000 pro Website (Websitesammlung). Es wird empfohlen, Websites zu erstellen und in Hubs zu organisieren, anstatt Unterwebsites zu erstellen. Wenn Sie Unterwebsites verwenden, empfiehlt es sich, ihre Anzahl zu begrenzen (insbesondere auf Stark traffickierten Websites).

> [!NOTE]
> Ihre Organisation ist auf 2.000 Hubwebsites beschränkt. Möglicherweise benötigen Sie nicht für jede Funktion eine Hubwebsite, und es ist wichtig, vor dem Erstellen von Hubs einige Planungen zu machen. Weitere Informationen finden Sie unter [Planning your SharePoint hub sites](https://docs.microsoft.com/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>Von SharePoint gehostete Anwendungen

20.000 Instanzen pro Organisation.

### <a name="users"></a>Benutzer

2 Millionen pro Websitesammlung.

> [!NOTE]
> Die Anzahl der Gäste, die Sie zu SharePoint-Websites einladen können, ist nicht eindeutig begrenzt. Weitere Informationen zur externen Freigabe finden Sie unter [Übersicht über die externe Freigabe.](https://docs.microsoft.com/sharepoint/external-sharing-overview)

## <a name="see-also"></a>Siehe auch

[Suchgrenzwerte für SharePoint](https://docs.microsoft.com/sharepoint/search-limits)
