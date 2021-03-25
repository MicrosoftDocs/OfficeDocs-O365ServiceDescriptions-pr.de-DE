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
description: Weitere Informieren zu den SharePoint-Beschränkungen für Microsoft 365- und eigenständige Pläne.
ms.openlocfilehash: 60a9fc63c60952ef8a71706d79ddac055fecc887
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51172610"
---
# <a name="sharepoint-limits"></a>SharePoint-Beschränkungen

Weitere Informationen zu Dienstbeschränkungen in SharePoint für Microsoft 365.
  
## <a name="limits-by-plan"></a>Grenzwerte nach Plan 

| Feature | Microsoft 365 Business Basic, Business Standard, oder Business Premium | Microsoft 365 E3 oder E5, Office 365 E1, E3, oder E5, oder SharePoint Plan 1 oder 2 | Microsoft 365 F1 oder F3, Office 365 F3 |
|:-----|:-----|:-----|:-----|
|Gesamtspeicher pro Organisation<sup>1, 2, 6</sup> <br/> |1 TB plus 10 GB pro erworbene Lizenz<sup>3</sup>  <br/> |1 TB plus 10 GB pro erworbene Lizenz<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Maximaler Speicher pro Website (Websitesammlung) <sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Websites (Websitesammlungen) pro Organisation  <br/> |2 Mio.<sup>6</sup> <br/> |2 Mio.<sup>6</sup> <br/> |2 Mio.<br/> |
|Anzahl der Benutzer  <br/> |Bis zu 300  <br/> |1-500.000<sup>7</sup> <br/> |1-500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [Erfahren Sie, wie Sie den gesamten und verfügbaren Speicherplatz für Ihre Organisation finden können](/sharepoint/manage-site-collection-storage-limits). Sie können eine unbegrenzte Menge an zusätzlichem SharePoint-Speicher kaufen. Siehe [Ändern von Speicherplatz für Ihr Abonnement](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Es wird empfohlen, den Papierkorb zu überwachen und regelmäßig zu leeren. Der vom Papierkorb belegte Speicherplatz ist Teil des Limits des Gesamtspeicherplatzes der Organisation. 
<br/> <sup>3</sup> Wenn Sie ein Microsoft 365-Abonnement und einen zusätzlichen Office 365-Dateispeicherplatz-Add-On haben, werden die Speichermengen hinzugefügt. 
<br/> <sup>4</sup> dies ist das *Limit* des Speichers für eine einzelne Website (früher als „Websitesammlung“ bezeichnet), nicht die Größe des Speicherplatzes, der für jede Website *bereitgestellt* wird. Dieses Limit gilt für alle Typen von Websites, einschließlich Office 365-Teamwebsites, die mit einer Gruppe verbunden sind, und OneDrive. SharePoint-Administratoren können [manuell niedrigere Speicherlimits festlegen](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> Mitarbeiter „an vorderster Front“ können SharePoint-Websites nicht verwalten. 
<br/> <sup>6</sup> Ohne OneDrive, das für jeden lizenzierten Benutzer erstellt wurde. 
<br/> <sup>7</sup> Wenn Sie über mehr als 500.000 Benutzer verfügen, wenden Sie sich an einen Microsoft-Vertriebsmitarbeiter. 
  
## <a name="service-limits-for-all-plans"></a>Dienstbeschränkungen für alle Pläne

### <a name="items-in-lists-and-libraries"></a>Elemente in Listen und Bibliotheken

Eine Liste kann bis zu 30 Millionen Elemente und eine Bibliothek bis zu 30 Millionen Dateien und Ordner enthalten. Wenn eine Liste, Bibliothek, oder ein Ordner mehr als 100 000 Elemente enthält, können Sie die Vererbung von Berechtigungen für die Liste, Bibliothek, oder Ordner nicht unterbrechen. Ebenfalls können Sie nicht die Berechtigungen erneut erben. Sie können aber immer noch die Vererbung auf den einzelnen Elementen innerhalb der Liste, Bibliothek, oder des Ordners bis zur maximalen Anzahl eindeutiger Berechtigungen on der Liste oder Bibliothek unterbrechen (mehr dazu im nächsten Abschnitt). Weitere Informationen zu anderen Einschränkungen für die Anzeige umfangreicher Listen finden Sie unter [Verwalten umfangreicher Listen und Bibliotheken in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784).

### <a name="unique-security-scopes-per-list-or-library"></a>Eindeutige Sicherheitsbereiche pro Liste oder Bibliothek

Entwerfen Sie umfangreiche Listen so, dass sie über so wenig eindeutiger Berechtigungen verfügen, wie möglich, und unterhalb von 5.000 bleiben.

### <a name="file-size-and-file-path-length"></a>Dateigröße und Dateipfadlänge

250 GB. Weitere Informationen zu den Einschränkungen und Limits bei der Verwendung der neuen OneDrive-Synchronisationsapp (OneDrive.exe) finden Sie unter [Ungültige Dateinamen und Dateitypen](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Websiteübergreifendes Verschieben und Kopieren

Das Kopieren/Verschieben mehrerer Dateien in einem einzigen Vorgang muss drei Anforderungen erfüllen:

- Eine Gesamtdateigröße von höchstens 100 GB
- Höchstens 30.000 Dateien
- Jede Datei muss kleiner als 15 GB sein

### <a name="sync"></a>Synchronisierung

Für optimale Leistung wird empfohlen, nicht mehr als 300.000 Dateien in einer einzigen OneDrive- oder Teamwebsite-Bibliothek zu speichern. Obwohl SharePoint Online 30 Mio. Dokumente pro Bibliothek speichern kann, empfehlen wir zur Erzielung einer optimalen Leistung, dass aus allen Dokumentbibliotheken maximal 300.000 Dateien synchronisiert werden. Darüber hinaus können die gleichen Leistungsprobleme auftreten, wenn alle zu synchronisierenden Bibliotheken 300.000 Elemente oder mehr enthalten – selbst wenn Sie nicht alle Elemente in diesen Bibliotheken synchronisieren. Wenn Sie den vorherigen Synchronisierungsclient für OneDrive for Business (Groove.exe) verwenden, liegt die Synchronisierungsgrenze pro Bibliothek bei 20.000 Elementen (einschließlich 5.000 Elementen pro Teamwebsite).

### <a name="versions"></a>Versionen

50.000 Hauptversionen und 511 Nebenversionen.

### <a name="sharepoint-groups"></a>SharePoint-Gruppen

Ein Benutzer kann 5.000 Gruppen per Website (Websitesammlung) angehören, und jede Gruppe kann bis zu 5.000 Benutzer enthalten. Es können bis zu 10.000 Gruppen pro Website (Websitesammlung) vorhanden sein.

> [!NOTE]
> Informationen zu Grenzwerten für Gruppen bei Azure AD finden Sie unter [Azure AD-Dienstbeschränkungen und Einschränkungen](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions), denn solche Grenzwerte können die Verwaltung der Mitgliedschaft von privaten und öffentlichen Gruppenwebsites beeinflussen.

### <a name="managed-metadata"></a>Verwaltete Metadaten

200.000 Ausdrücke im Terminologiespeicher, 1.000 globale Ausdruckssätze, 1,000 Gruppen.

### <a name="overall-site-metadata"></a>Metadaten der gesamten Website

1.000 GB pro Website (Metadaten erreichen diesen Umfang nur selten).

### <a name="subsites"></a>Unterwebsites

2.000 pro Website (Websitesammlung). Wir empfehlen Websites zu erstellen und sie in Hubs zu organisieren, anstatt Unterwebsites zu erstellen. Wenn Sie Unterwebsites verwenden, empfehlen wir deren Anzahl zu beschränken (insbesondere auf stark frequentierten Websites).

> [!NOTE]
> Ihre Organisation ist auf 2.000 Hubwebsites beschränkt. Möglicherweise benötigen Sie für jede Funktion keine Hubwebsite, und es ist wichtig, dass Sie vor dem Erstellen von Hubs einiges planen. Weitere Informationen finden Sie unter [Planen Ihrer SharePoint-Hubwebsiten](/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>In SharePoint gehostete Anwendungen

20.000 Instanzen pro Organisation.

### <a name="users"></a>Benutzer

2 Millionen pro Websitesammlung.

> [!NOTE]
> Es gibt keine eindeutige Beschränkung der Anzahl von Gästen, die Sie zu SharePoint-Websites einladen können. Weitere Informationen zur externen Freigabe finden Sie unter [Übersicht über die externe Freigabe](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Mehr dazu

[Suchgrenzwerte von SharePoint](/sharepoint/search-limits)