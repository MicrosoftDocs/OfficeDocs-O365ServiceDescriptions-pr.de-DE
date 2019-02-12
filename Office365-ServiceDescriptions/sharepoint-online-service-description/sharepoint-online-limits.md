---
title: SharePoint Online-Grenzwerte
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Suchen Sie nach SharePoint Online-Grenzwerten für Office 365 Enterprise-Pläne und eigenständige Pläne.
ms.openlocfilehash: 9d960aa50bef0b200fef2afe63ac1732cf201582
ms.sourcegitcommit: 30a452b9b9a0d8fc288e5911235454cc8f1907be
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 02/12/2019
ms.locfileid: "25848690"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online-Grenzwerte

Hier finden Sie die Grenzwerte für SharePoint für Office 365-Pläne und SharePoint Online-Plänen.
  
## <a name="limits-by-plan"></a>Grenzen nach plan

|||||
|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials oder Business Premium** <br/> |**Office 365 Enterprise E1, E3, oder E5 oder SharePoint Online-Plan 1 oder 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Speicher<sup>1, 2</sup> <br/> |1 TB pro Organisation plus 10 GB pro erworbene Lizenz  <br/> |1 TB pro Organisation plus 10 GB pro Lizenz erworben<sup>3</sup> <br/> |1 TB pro Organisation <sup>3</sup> <br/> |
|Speicher für Websitesammlungen  <br/> |Bis zu 25 TB pro Websitesammlung oder Gruppe<sup>4</sup> <br/> |Bis zu 25 TB pro Websitesammlung oder Gruppe<sup>4</sup> <br/> |Bis zu 25 TB pro Websitesammlung oder Gruppe<sup>5</sup> <br/> |
|Websitesammlungen pro Organisation  <br/> |500.000<sup>6</sup> <br/> |500.000<sup>6</sup> <br/> |500,000<br/> |
|Anzahl der Benutzer  <br/> |Bis zu 300  <br/> |1-500.000<sup>7</sup> <br/> |1-500.000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Sie können eine eine unbegrenzte Anzahl von zusätzlichen SharePoint Online-Speicherplatz erwerben. Finden Sie unter [Ändern von Speicherplatz für Ihr Abonnement](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C).<br/><sup>2</sup> empfohlen Überwachung den Papierkorb und regelmäßig zu leeren. Der verwendeten Speicherplatz ist Teil der Speichergrenze für die Organisation Gesamtgröße der Datei.<br/> <sup>3</sup> Wenn Sie über ein Office 365-Abonnement und einen eigenständigen SharePoint Online-Plan verfügen, wird der Speicherplatz zusammengerechnet.<br/><sup>4</sup> SharePoint Online-Administratoren können die Speichergrenzen für Websitesammlungen und Websites festlegen.<br/> <sup>5</sup> Kiosk-Worker können nicht SharePoint Online-Websitesammlungen verwalten. Sie benötigen mindestens einen Enterprise-Benutzerlizenz Kiosk Websitesammlungen verwalten.<br/> <sup>6</sup> Ohne OneDrive for Business-Websitesammlungen, die für jeden lizenzierten Benutzer erstellt wurden.<br/><sup>7</sup> Wenn Sie über mehr als 500.000 Benutzer verfügen, wenden Sie sich an einen Microsoft-Vertriebsmitarbeiter. 
  

  
## <a name="service-limits-for-all-plans"></a>Einschränkungen für den Dienst für alle Pläne

- **Elemente in Listen und Bibliotheken** - eine Liste kann bis zu 30 Millionen Elemente und eine Bibliothek kann bis zu 30 Millionen Dateien und Ordner. Ansichten können bis zu 12 Nachschlagespalten haben. Weitere Informationen zu anderen Einschränkungen für die Anzeige von großer Listen finden Sie unter [Verwalten von großen Listen und Bibliotheken in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Informationen über Zeichen, die in Dateinamen nicht verwendet werden kann, finden Sie unter [ungültige Zeichen in den Namen von Dateien und Ordner](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Dateigröße und Pfad der Dateilänge** - 15 GB. Weitere Informationen zu Beschränkungen und Grenzwerte bei Verwendung des neuen OneDrive Sync-Clients (OneDrive.exe) finden Sie unter [Ungültige Dateinamen und Dateitypen in OneDrive, OneDrive für Unternehmen, und SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Sync** - sollten für eine optimale Leistung nicht mehr als 300.000 Dateien in einer Bibliothek OneDrive oder ein Team-Website zu speichern. Obwohl SharePoint Online 30 Millionen Dokumente pro Bibliothek gespeichert werden kann, sollten für eine optimale Leistung nicht mehr als 300.000 Dateien über alle Dokumentbibliotheken synchronisieren. Darüber hinaus können die gleichen Leistungsprobleme auftreten, wenn 300.000 Elemente oder mehrere über alle Bibliotheken, die Sie synchronisieren, die auch wenn Sie nicht alle Elemente in diesen Bibliotheken synchronisieren. Wenn Sie die vorherige OneDrive for Business-Synchronisierungsclient (Groove.exe) verwenden, ist das Sync-Limit pro Bibliothek 20.000 Elemente (einschließlich 5.000 Elemente pro Teamwebsite).

- **Versionen** - 50.000 Hauptversionen und 511 Nebenversionen.

- **SharePoint-Gruppen** - Benutzer kann 5.000 Gruppen angehören, und jeder Gruppe kann bis zu 5.000 Benutzer haben. Sie können bis zu 10.000 Gruppen pro Websitesammlung haben.

- **Verwaltete Metadaten** - 200.000 Ausdrücke im Terminologiespeicher, 1.000 globale Ausdruckssätze 1.000 Gruppen.

- **Unterwebsites** - bis zu 2.000 pro Websitesammlung.

- **SharePoint gehosteten Anwendungen** - 20.000 Instanzen pro Organisation.

- **Eindeutiger Sicherheitsbereiche pro Liste oder Bibliothek** - 5.000. Für umfangreiche Listen Entwurf, um möglichst wenige eindeutige Berechtigungen verfügen.

- **Benutzer** : 2 Millionen pro Websitesammlung.

> [!NOTE]
> Es gibt keine Beschränkung der Anzahl der externen Benutzer aus, die Sie zu Ihrer SharePoint Online Websitesammlungen einladen können. Weitere Informationen finden Sie unter [externe Freigabe für Ihre SharePoint Online-Umgebung verwalten](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Siehe auch

[Suchbeschränkungen für SharePoint Online](/sharepoint/search-limits)