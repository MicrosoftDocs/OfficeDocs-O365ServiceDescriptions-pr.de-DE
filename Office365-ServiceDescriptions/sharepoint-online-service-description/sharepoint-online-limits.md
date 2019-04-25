---
title: SharePoint Online-Grenzwerte
ms.author: sharik
author: skjerland
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Suchen Sie nach SharePoint Online-Grenzwerten für Office 365 Enterprise-Pläne und eigenständige Pläne.
ms.openlocfilehash: c1b6185c46be6f1343e6679a5b887bab5b393708
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246611"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online-Grenzwerte

Hier finden Sie die SharePoint-Grenzwerte für Office 365-Pläne und eigenständige SharePoint Online-Pläne.
  
## <a name="limits-by-plan"></a>Grenzwerte nach Plan

|||||
|:-----|:-----|:-----|:-----|
|**Funktion** <br/> |**Office 365 Business Essentials oder Business Premium** <br/> |**Office 365 Enterprise E1, E3 oder E5 oder SharePoint Online-Plan 1 oder 2** <br/> | **Office 365 Enterprise F1** <br/> |
|Speicher<sup>1, 2</sup> <br/> |1 TB pro Organisation plus 10 GB pro erworbene Lizenz  <br/> |1 TB pro Organisation plus 10 GB pro erworbene Lizenz<sup>3</sup> <br/> |1 TB pro Organisation <sup>3</sup> <br/> |
|Speicher für Websitesammlungen  <br/> |Bis zu 25 TB pro Websitesammlung oder Gruppe<sup>4</sup> <br/> |Bis zu 25 TB pro Websitesammlung oder Gruppe<sup>4</sup> <br/> |Bis zu 25 TB pro Websitesammlung oder Gruppe<sup>5</sup> <br/> |
|Websitesammlungen pro Organisation  <br/> |500.000<sup>6</sup> <br/> |500.000<sup>6</sup> <br/> |500.000<br/> |
|Anzahl der Benutzer  <br/> |Bis zu 300  <br/> |1-500.000<sup>7</sup> <br/> |1-500.000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Sie können eine unbegrenzte Menge an zusätzlichem SharePoint Online-Speicher kaufen. Weitere Informationen finden Sie unter [Ändern von Speicherplatz für Ihr Abonnement](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C). 
<br/><sup>2</sup> Es wird empfohlen, den Papierkorb zu überwachen und regelmäßig zu leeren. Der vom Papierkorb verwendete Speicherplatz wird beim Grenzwert für den Gesamtspeicher der Organisation mit berücksichtigt. 
<br/> <sup>3</sup> Wenn Sie über ein Office 365-Abonnement und einen eigenständigen SharePoint Online-Plan verfügen, wird der Speicherplatz zusammengerechnet. 
<br/><sup>4</sup> SharePoint Online-Administratoren können Speichergrenzwerte für Websitesammlungen und Websites festlegen.
<br/> <sup>5</sup> Kiosk-Worker können keine SharePoint Online-Websitesammlungen verwalten. Sie benötigen mindestens eine Enterprise-Benutzerlizenz, um Kiosk-Websitesammlungen zu verwalten. 
<br/> <sup>6</sup> Ohne OneDrive for Business-Websitesammlungen, die für jeden lizenzierten Benutzer erstellt wurden. 
<br/><sup>7</sup> Wenn Sie über mehr als 500.000 Benutzer verfügen, wenden Sie sich an einen Microsoft-Vertriebsmitarbeiter. 
  

  
## <a name="service-limits-for-all-plans"></a>Dienst Grenzwerte für alle Pläne

- **Elemente in Listen und Bibliotheken** : eine Liste kann bis zu 30 Millionen Elemente enthalten, und eine Bibliothek kann bis zu 30 Millionen Dateien und Ordner enthalten. Ansichten können bis zu 12 Nachschlagespalten aufweisen. Weitere Informationen zu anderen Einschränkungen für das Anzeigenumfang reicher Listen finden Sie unter [Manage umfangreicher Listen und Bibliotheken in Office 365](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784). Informationen zu Zeichen, die in Dateinamen nicht verwendet werden können, finden Sie unter [ungültige Zeichen in Datei-und Ordnernamen](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Dateigröße und** Dateipfad-Länge: 15 GB. Weitere Informationen zu Einschränkungen und Beschränkungen bei der Verwendung des neuen OneDrive-Synchronisierungs Clients (OneDrive. exe) finden Sie unter [ungültige Dateinamen und Dateitypen in OneDrive, OneDrive for Business und SharePoint](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa).

- **Verschiebung und Kopieren über Websitesammlungen hinweg** – 100 GB pro Vorgang. Der Webbrowser muss geöffnet bleiben.

- **Sync** -für eine optimale Leistung empfiehlt es sich, nicht mehr als 300.000 Dateien in einer einzelnen OneDrive-oder Teamwebsite Bibliothek zu speichern. Obwohl SharePoint Online 30 Millionen-Dokumente pro Bibliothek speichern kann, empfiehlt es sich, nicht mehr als 300.000-Dateien für alle Dokumentbibliotheken zu synchronisieren. Darüber hinaus können die gleichen Leistungsprobleme auftreten, wenn Sie 300.000 Elemente oder mehr in allen Bibliotheken haben, die Sie synchronisieren, auch wenn Sie nicht alle Elemente in diesen Bibliotheken synchronisieren. Wenn Sie den vorherigen OneDrive for Business-synchronisierungsclient (Groove. exe) verwenden, beträgt der Synchronisierungs Grenzwert pro Bibliothek 20.000 Elemente (einschließlich 5.000-Elementen pro Teamwebsite).

- **Versionen** -50.000 Hauptversionen und 511-Nebenversionen.

- **SharePoint-Gruppen** : ein Benutzer kann zu 5.000-Gruppen gehören, und jede Gruppe kann bis zu 5.000 Benutzer haben. Sie können bis zu 10.000 Gruppen pro Websitesammlung haben.

- **Verwaltete Metadaten** -200.000 Ausdrücke im Terminologiespeicher, 1.000 globale Ausdruckssätze, 1.000 Gruppen.

- Unter **Websites** – bis zu 2.000 pro Websitesammlung.

- In **SharePoint gehostete Anwendungen** – 20.000 Instanzen pro Organisation.

- **Eindeutige Sicherheitsbereiche pro Liste oder Bibliothek** – 5.000. Für umfangreiche Listen muss Design so wenig eindeutige Berechtigungen wie möglich aufweisen.

- **Benutzer** – 2 Millionen pro Websitesammlung.

> [!NOTE]
> Es gibt keine Begrenzung für die Anzahl externer Benutzer, die Sie zu Ihren SharePoint Online-Websitesammlungen einladen können. Weitere Informationen finden Sie unter [Verwalten der externen Dateifreigabe für Ihre SharePoint-Onlineumgebung](/sharepoint/external-sharing-overview).

## <a name="see-also"></a>Siehe auch

[Such Grenzwerte für SharePoint Online](/sharepoint/search-limits)