---
title: SharePoint für US-Regierungsumgebungen
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Erfahren Sie mehr über die Verfügbarkeit von SharePoint-Features für Us Government Cloud-Kunden.
ms.openlocfilehash: fc782a01c99165fbf19156250e09220656d46ba3
ms.sourcegitcommit: ab82834030929e1583074b3f5b0b27182746fff4
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/19/2021
ms.locfileid: "50902024"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint für US-Regierungsumgebungen

Dieser Artikel bietet eine Übersicht über die Funktionsunterschiede zwischen der US Government Cloud und der kommerziellen Cloud, wie in der Beschreibung des [SharePoint-Diensts aufgeführt.](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description) SharePoint ist für die Government Community Cloud (GCC), GCC High und DoD-Umgebungen verfügbar. 

Weitere Informationen zur Government Cloud, einschließlich Berechtigung und Kauf, finden Sie unter [Microsoft 365 Government - how to buy](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Informationen zum Vergleich von Office 365 Government-Plänen finden Sie unter [Office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Informationen zu den erforderlichen Endpunkten beim Verwalten der Netzwerkkonnektivität finden Sie unter [Office 365 U.S. Government GCC High endpoints](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) oder [Office 365 U.S. Government DoD endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Organisationen profitieren nicht nur von den Features und Funktionen von Office 365, sondern profitieren auch von den folgenden Features, die für die Cloudumgebungen der US-Regierung einzigartig sind:

-   Die Kundeninhalte Ihrer Organisation werden logisch von Kundeninhalten in den kommerziellen Office 365-Diensten von Microsoft getrennt.
-   Der Kundeninhalt Ihrer Organisation wird in den Vereinigten Staaten gespeichert.
-   Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.
-   Die Cloudumgebungen der Regierung entsprechen den Zertifizierungen und Akkreditierungen, die für Kunden des öffentlichen US-Sektors erforderlich sind.

Unser Ziel ist es, alle kommerziellen SharePoint-Features und -Funktionen für die Cloudumgebungen der Regierung bereitzustellen. Einige Features sind aufgrund der Anforderungen von Government Cloud-Kunden nicht verfügbar. Andere Features kommen in die Regierungsumgebungen, sind aber noch nicht verfügbar. In den folgenden Abschnitten finden Sie Informationen zur Verfügbarkeit von Features in den Cloudumgebungen der Regierung.

## <a name="developer-features"></a>Entwicklerfeatures

Es gibt keine bekannten Unterschiede zwischen den Entwicklerfeatures für kommerzielle Kunden und denen für Government Cloud-Kunden.

- Verbindungen mit externen Anwendungen, z. B. Datenquellen für Add-Ins, sind auf Quellen beschränkt, die sich innerhalb der von Ihrer Regierungsumgebung unterstützten Systemsicherheitsgrenzen befinden.
- Business Connectivity Services (BCS) wird für Konnektivitätsszenarien unterstützt, in denen die Datenquellen innerhalb der Sicherheitsgrenze für Ihren Clouddienst erreichbar bleiben.

Wenn Sie Anwendungen von Drittanbietern auf Websites verwenden, überprüfen Sie die Datenschutz- und Compliancebestimmungen, die von Drittanbietern bereitgestellt werden, wenn Sie die angemessene Nutzung dieser Dienste für Ihre Organisation bewerten. Anwendungen und Dienste von Drittanbietern können die Speicherung, Übertragung und Verarbeitung der Kundendaten Ihrer Organisation auf Drittanbietersystemen umfassen, die sich außerhalb der Cloud der Regierung befinden und daher nicht von ihren Compliance- und Datenschutzverpflichtungen abgedeckt werden. 

## <a name="it-admin-features"></a>IT-Administratorfeatures

Hier sind die Unterschiede zwischen den IT-Administratorfeatures für kommerzielle Kunden und denen für Government Cloud-Kunden.

- Ändern einer Websiteadresse ist für GCC High-Kunden nicht verfügbar
- Hybrid sharePoint Server ist nicht für alle Cloudkunden der Regierung verfügbar
- Das SharePoint-Migrationstool und der Migrations-Manager erfordern eine Konfigurationsänderung. Weitere Informationen finden Sie unter [SPMT Government Cloud Support](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Mover.io wird noch nicht unterstützt
- Multi-Geo ist nicht für alle Cloudkunden der Regierung verfügbar

Informationen zur FastTrack-Migration finden Sie in der [Office 365 US Government-Dienstbeschreibung](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack).

## <a name="security-and-compliance-features"></a>Sicherheits- und Compliancefeatures

Es gibt keine bekannten Unterschiede zwischen den Sicherheits- und Compliancefeatures für kommerzielle Kunden und denen für Government Cloud-Kunden.

Informationen zu Sicherheits- und Compliancefeatures finden Sie im [Security & Compliance Center](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center).

Informationen zu Azure Active Directory-Features für Behörden finden Sie in [der Azure Government Security + Identity-Dokumentation](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory). 

Informationen zu Azure Information Protection-Features für Behörden finden Sie unter [Azure Information Protection Premium Government Service Description](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description). 

## <a name="sites-and-content"></a>Websites und Inhalte

Hier sind die Unterschiede zwischen den Websites und Inhaltsfeatures für kommerzielle Kunden und denen für Government Cloud-Kunden:

- Webparts, die auf Verbindungen mit Internetdiensten wie Amazon Kindle, Bing Maps, Twitter und YouTube-Webparts angewiesen sind, funktionieren nicht wie erwartet
- Bibliothek für Organisationsressourcen ist nicht verfügbar
- Das Hinzufügen von Listen und Seiten zu Teams ist für GCC High- und DoD-Kunden nicht verfügbar.
- Die Graph-Funktionalität in SharePoint Online für GCC High ist derzeit deaktiviert. Alle Dienste, die auf Microsoft Graph angewiesen sind, sind derzeit möglicherweise nicht verfügbar.
- Features, die auf Verbindungen mit Internetdiensten beruhen, z. B. die Registerkarte "Bestandsbilder", funktionieren nicht wie erwartet
- Benachrichtigungen für Datei- und Websiteaktivitäten sind nicht verfügbar

## <a name="search-features"></a>Suchfeatures

Hier sind die Unterschiede zwischen den Suchfeatures für kommerzielle Kunden und denen für Government Cloud-Kunden:

- Die Microsoft Search-Integration ist nicht verfügbar.

## <a name="sharing-and-sync"></a>Freigabe und Synchronisierung

Funktionsunterschiede zwischen der kommerziellen Cloud und den Cloudumgebungen der Regierung finden Sie unter [Dateifreigabe](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing).

## <a name="plan-for-governance"></a>Planen der Steuerung

Ihr Wechsel in die Cloud bietet transformative Erfahrungen mit integrierten Administratorsteuerelementen. Bestimmen Sie Ihre Anforderungen für die Steuerung und wie Sie diese erfüllen können. Weitere Informationen [finden Sie unter Plan for governance to transform teamwork with Microsoft 365.](https://resources.techcommunity.microsoft.com/teamwork-governance/) Hier finden Sie Anleitungen zu Office 365-Gruppen, SharePoint, Teams und mehr.

## <a name="deploy-sharepoint-for-collaboration"></a>Bereitstellen von SharePoint für die Zusammenarbeit

Folgen Sie nach dem Einrichten Ihrer Organisation in der Microsoft US Government Cloud dem empfohlenen Bereitstellungspfad, der im [SharePoint Adoption Resource Center beschrieben ist.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Achten Sie darauf, dass Sie sich mit Ihren Einführungs- und Änderungsverwaltungs-Champions beschäftigen.
Sie können auch mit [FastTrack](https://www.microsoft.com/fasttrack) oder Ihrem ausgewählten Partner zusammenarbeiten, um den Dienst für Ihre Benutzer zu rollouten.
Besuchen Sie [das Microsoft Trust Center,](https://www.microsoft.com/trust-center) um mehr darüber zu erfahren, wie Microsoft Sicherheit, Datenschutz und Compliance als Kernansätze für die Unterstützung von Organisationen für ihre Kunden verwendet.
