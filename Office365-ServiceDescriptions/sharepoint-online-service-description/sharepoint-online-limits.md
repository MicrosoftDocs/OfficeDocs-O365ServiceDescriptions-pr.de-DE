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
ms.openlocfilehash: d01e2af69d566b0e44d515e762049acd3cfba864
ms.sourcegitcommit: 638bacac9e663444f7a094d5887476d8a87e3b58
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/18/2020
ms.locfileid: "47962094"
---
# <a name="sharepoint-limits"></a>SharePoint-Beschränkungen

Erfahren Sie mehr über die Grenzwerte für Dienste in SharePoint für Microsoft 365.
  
## <a name="limits-by-plan"></a>Grenzen nach Plan 

|||||
|:-----|:-----|:-----|:-----|
|**Feature** <br/> |**Microsoft 365 Business Basic, Business Standard oder Business Premium** <br/> |**Microsoft 365 E3 oder E5, Office 365 Enterprise E1, E3 oder E5 oder SharePoint-Plan 1 oder 2** <br/> | **Microsoft 365 F1 oder F3, Office 365 Enterprise F3** <br/> |
|Gesamtspeicher pro Organisation<sup>1, 2, 6</sup> <br/> |1 TB plus 10 GB pro Lizenz erworben<sup>3</sup>  <br/> |1 TB plus 10 GB pro Lizenz erworben<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|Maximaler Speicherplatz pro Website (Websitesammlung)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|Websites (Websitesammlungen) pro Organisation  <br/> |2 Millionen<sup>6</sup> <br/> |2 Millionen<sup>6</sup> <br/> |2 Millionen<br/> |
|Anzahl der Benutzer  <br/> |Bis zu 300  <br/> |1-500.000<sup>7</sup> <br/> |1-500.000<sup>7</sup> <br/> |
   
<sup>1</sup> [erfahren Sie, wie Sie den gesamten und den verfügbaren Speicher für Ihre Organisation ermitteln können](/sharepoint/manage-site-collection-storage-limits). Sie können eine unbegrenzte Menge an zusätzlichem SharePoint-Speicher erwerben. Weitere Informationen finden Sie unter [Ändern von Speicherplatz für Ihr Abonnement](/office365/admin/subscriptions-and-billing/add-storage-space). 
<br/><sup>2</sup> Es wird empfohlen, den Papierkorb zu überwachen und regelmäßig zu leeren. Der verwendete Speicherplatz ist Teil des gesamten Speichergrenzwerts der Organisation. 
<br/> <sup>3</sup> Wenn Sie über ein Microsoft 365-Abonnement und ein Office 365 zusätzliches Dateispeicher-Add-on verfügen, werden die Speicher Beträge hinzugefügt. 
<br/> <sup>4</sup> hierbei handelt es sich um die Speicher *Grenze* für einen einzelnen Standort (zuvor als "Websitesammlung" bezeichnet), nicht für den Speicherplatz, der für die einzelnen Standorte *bereitgestellt* wird. Dieser Grenzwert gilt für alle Arten von Websites, einschließlich Office 365 Gruppen verbundenen Teamwebsites und OneDrive. SharePoint-Administratoren können [niedrigere Speichergrenzwerte manuell festlegen](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits). 
<br/> <sup>5</sup> Mitarbeiter von First-Work können SharePoint-Websites nicht verwalten. 
<br/> <sup>6</sup> nicht einschließlich der OneDrive, die für jeden lizenzierten Benutzer erstellt wurden. 
<br/> <sup>7</sup> Wenn Sie über mehr als 500.000 Benutzer verfügen, wenden Sie sich an einen Microsoft-Vertriebsmitarbeiter. 
  
## <a name="service-limits-for-all-plans"></a>Dienst Grenzwerte für alle Pläne

### <a name="items-in-lists-and-libraries"></a>Elemente in Listen und Bibliotheken

Eine Liste kann bis zu 30 Millionen Elemente enthalten, und eine Bibliothek kann bis zu 30 Millionen Dateien und Ordner haben. Wenn eine Liste, Bibliothek oder ein Ordner mehr als 100.000 Elemente enthält, können Sie die Vererbung von Berechtigungen für die Liste, Bibliothek oder den Ordner nicht unterbrechen. Sie können auch keine Berechtigungen erneut erben. Sie können die Vererbung allerdings für die einzelnen Elemente innerhalb dieser Liste, Bibliothek oder eines Ordners bis zur maximalen Anzahl eindeutiger Berechtigungen in der Liste oder Bibliothek aufheben (siehe nächster Abschnitt). Weitere Informationen zu anderen Einschränkungen beim Anzeigenumfang reicher Listen finden Sie unter [Verwalten umfangreicher Listen und Bibliotheken in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). 

> [!NOTE]
> Die Anzahl der Dokumentbibliotheken, die Sie auf einer Website haben können, ist unbegrenzt.

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>Eindeutige Berechtigungen für Elemente in einer Liste oder Bibliothek

Der zulässige Grenzwert ist 50.000 eindeutig Berechtigungselemente, aber die empfohlene allgemeine Grenze ist 5.000. Das vornehmen von Änderungen an mehr als 5.000 einmalig berechtigten Elementen gleichzeitig dauert länger. Bei umfangreichen Listen sollte Design so wenig eindeutige Berechtigungen wie möglich aufweisen.

Ein weiterer Grenzwert ist 5.000 Rollenzuweisungen pro eindeutig Berechtigungselement. 

### <a name="file-size-and-file-path-length"></a>Dateigröße und Länge des Dateipfads

100 GB. Die maximale Größe für an Listenelemente angefügte Dateien beträgt 250 MB. Weitere Informationen zu Einschränkungen und Beschränkungen bei der Verwendung der neuen OneDrive-Synchronisierungs-app (OneDrive.exe) finden Sie unter [ungültige Dateinamen und Dateitypen](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

### <a name="moving-and-copying-across-sites"></a>Verschieben und Kopieren über Websites hinweg

Das Kopieren/Verschieben mehrerer Dateien in einem einzelnen Vorgang hat drei Anforderungen: 

- Gesamtdateigröße von maximal 100 GB 
- Nicht mehr als 30.000 Dateien
- Jede Datei muss weniger als 2 GB betragen.

### <a name="sync"></a>Synchronisierung

**Neue OneDrive-Sync-App** – für eine optimale Leistung wird empfohlen, nicht mehr als 300.000 Dateien pro Benutzer in allen synchronisierten Dokumentbibliotheken zu speichern, selbst wenn Sie Dateien bei Bedarf verwenden oder nur einige Ordner innerhalb der zu synchronisierenden Bibliotheken auswählen.

**Frühere OneDrive für Unternehmen Sync-app (Groove.exe)** – Sie können insgesamt bis zu 20.000 Elemente für alle synchronisierten Bibliotheken synchronisieren. Dies umfasst OneDrive-Bibliotheken, Teamwebsite-Bibliotheken oder beides. Unabhängig vom gesamten Synchronisierungs Grenzwert gibt es Einschränkungen für die Anzahl der Elemente, die für jeden Bibliotheks synchronisiert werden können:

   - Sie können bis zu 20.000 Elemente in einer OneDrive-Bibliothek synchronisieren. Dies umfasst Ordner und Dateien. 
   - Sie können bis zu 5.000 Elemente in einer SharePoint-Bibliothek synchronisieren. Dies umfasst Ordner und Dateien. Dabei handelt es sich um Bibliotheken, die Sie auf verschiedenen SharePoint-Websites finden, wie Teamwebsites und Community-Websites, Bibliotheken, die von anderen Benutzern erstellt wurden oder die Sie auf der Seite Websites erstellt haben. Sie können mehrere SharePoint-Bibliotheken synchronisieren. Alle Teamwebsites, die Sie synchronisieren, gelten auch für die gesamte 20.000-Elementgrenze für alle synchronisierten Bibliotheken.

> [!NOTE]
> Wenn Benutzer Dateien in Dokumentbibliotheken mit Hunderten von Tausenden von Dateien synchronisieren müssen, können Sie Ordner aus der Synchronisierungs-App ausblenden, indem Sie die Berechtigungsstufe der Ordner auf "Eingeschränkter Lesezugriff" festlegen. 

### <a name="versions"></a>Versionen

50.000 Hauptversionen und 511 Nebenversionen.

### <a name="sharepoint-groups"></a>SharePoint-Gruppen

Ein Benutzer kann zu 5.000 Gruppen pro Website (Websitesammlung) gehören, und jede Gruppe kann bis zu 5.000 Benutzer haben. Sie können bis zu 10.000 Gruppen pro Website (Websitesammlung) haben.

> [!NOTE]
> Informationen zu Azure AD Gruppenbeschränkungen finden Sie unter [Azure Ad Service Limits and Restrictions](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) , da diese Grenzwerte sich auf öffentliche und private Gruppen Websites für die Mitgliedschaftsverwaltung auswirken können. 

### <a name="managed-metadata"></a>Verwaltete Metadaten

200.000 Ausdrücke in Term Store, 1.000 globale Ausdruckssätze, 1.000 Gruppen.

### <a name="overall-site-metadata"></a>Allgemeine Website Metadaten

1000 GB pro Website (Metadaten erreichen selten diese Größe).

### <a name="subsites"></a>Websites 

2.000 pro Website (Websitesammlung). Es wird empfohlen, Websites zu erstellen und diese in Hubs zu organisieren, statt Unterwebsites zu erstellen. Wenn Sie Unterwebsites verwenden, empfehlen wir die Begrenzung ihrer Anzahl (insbesondere auf Websites mit starkem Handel).

> [!NOTE] 
> Ihre Organisation ist auf 2.000 Hubwebsites beschränkt. Möglicherweise benötigen Sie für jede Funktion keinen Hub-Standort, und es ist wichtig, dass Sie vor dem Erstellen von Hubs einige Planungsaufgaben durchführen. Weitere Informationen finden Sie unter [Planning Your SharePoint Hub Sites](https://docs.microsoft.com/sharepoint/planning-hub-sites).

### <a name="sharepoint-hosted-applications"></a>Gehostete SharePoint-Anwendungen

20.000 Instanzen pro Organisation.

### <a name="people-editing-a-document-at-the-same-time"></a>Personen, die ein Dokument gleichzeitig bearbeiten

99 Personen können ein Dokument gleichzeitig zur Bearbeitung öffnen. Wenn mehr als 10 Personen ein Dokument gleichzeitig bearbeiten, treten die Bearbeitungen eher in Konflikt, und die Benutzeroberfläche verschlechtert sich allmählich.

### <a name="users"></a>Benutzer

2 Millionen pro Website (Websitesammlung).
   
> [!NOTE]
> Es gibt keine Begrenzung für die Anzahl der Gäste, die Sie zu SharePoint-Websites einladen können. Weitere Informationen zur externen Freigabe finden Sie unter [External Sharing Overview](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Siehe auch

[Such Grenzwerte für SharePoint](/sharepoint/search-limits)
