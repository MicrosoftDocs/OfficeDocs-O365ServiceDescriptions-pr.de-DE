---
title: SharePoint für US Government Umgebungen
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Erfahren Sie mehr über die Verfügbarkeit von SharePoint-Features für Kunden der US Government Cloud.
ms.openlocfilehash: b0f36ea92b856a3fa9c1bf4ddd4cb4265655d1ae
ms.sourcegitcommit: 9961f5111b2b8b871183afcd03fcfb7fc05da4fc
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/21/2021
ms.locfileid: "49919748"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint für US Government Umgebungen

Dieser Artikel bietet eine Übersicht über die Funktionsunterschiede zwischen der US Government Cloud und der kommerziellen Cloud, wie in der [SharePoint-Dienstbeschreibung aufgeführt.](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description) SharePoint ist für die Government Community Cloud (GCC), GCC High- und DoD-Umgebungen verfügbar. 

Weitere Informationen zur Government Cloud, einschließlich Berechtigung und Erwerb, finden Sie unter [Microsoft 365 Government - So erwerben Sie .](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy) Informationen zum Vergleichen von Office 365 Government-Plänen finden Sie [unter Office 365 Government-Pläne.](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements)

Informationen zu den erforderlichen Endpunkten beim Verwalten der Netzwerkkonnektivität finden Sie in den [Office 365 U.S. Government GCC High-Endpunkten](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) oder [Office 365 U.S. Government DoD-Endpunkten.](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business)

Organisationen profitieren nicht nur von den Features und Funktionen von Office 365, sondern profitieren auch von den folgenden Features, die für die Cloudumgebungen der US Government einzigartig sind:

-   Die Kundeninhalte Ihrer Organisation werden logisch von Kundeninhalten in den kommerziellen Office 365-Diensten von Microsoft getrennt.
-   Der Kundeninhalt Ihrer Organisation wird in den Vereinigten Staaten gespeichert.
-   Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.
-   Die Behörden-Cloud-Umgebungen erfüllen Zertifizierungen und Akkreditierungen, die für Kunden im öffentlichen Us-Sektor erforderlich sind.

Es ist unser Ziel, alle kommerziellen Features und Funktionen von SharePoint für die Cloudumgebungen der Regierung bereitzustellen. Einige Features sind aufgrund der Anforderungen von Behörden-Cloud-Kunden nicht verfügbar. Andere Features kommen in die Behördenumgebungen, sind aber noch nicht verfügbar. In den folgenden Abschnitten finden Sie Informationen zur Verfügbarkeit von Features in den Government Cloud-Umgebungen.

## <a name="developer-features"></a>Entwicklerfeatures

Es gibt keine bekannten Unterschiede zwischen den Entwicklerfeatures für kommerzielle Kunden und denen für Government Cloud-Kunden.

- Verbindungen mit externen Anwendungen wie Datenquellen für Add-Ins sind auf Quellen beschränkt, die sich innerhalb der Systemsicherheitsgrenzen befinden, die von Ihrer Behördenumgebung unterstützt werden.
- Business Connectivity Services (BCS)-Funktionalität wird für Konnektivitätsszenarien unterstützt, in denen die Datenquellen innerhalb der Sicherheitsgrenze für Ihren Clouddienst erreichbar bleiben.

Wenn Sie Anwendungen von Drittanbietern auf Websites verwenden, überprüfen Sie die Datenschutz- und Compliancebestimmungen der Dritten, wenn Sie die geeignete Nutzung dieser Dienste für Ihre Organisation bewerten. Anwendungen und Dienste von Drittanbietern umfassen möglicherweise das Speichern, Übertragen und Verarbeiten der Kundendaten Ihrer Organisation auf Drittanbietersystemen, die sich außerhalb der Government Cloud befinden und daher nicht von ihren Compliance- und Datenschutzverpflichtungen abgedeckt sind. 

## <a name="it-admin-features"></a>Features von IT-Administratoren

Hier sind die Unterschiede zwischen den Features des IT-Admins für kommerzielle Kunden und denen für Government Cloud-Kunden.

- Das Ändern einer Websiteadresse ist für GCC -High-Kunden nicht verfügbar.
- SharePoint Server hybrid ist nicht für alle Kunden der Government Cloud verfügbar
- Das SharePoint-Migrationstool und der Migrations-Manager erfordern eine Konfigurationsänderung. Weitere Informationen finden Sie unter [SPMT Government Cloud Support](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Mover.io wird noch nicht unterstützt
- Multi-Geo ist nicht für alle Kunden der Government Cloud verfügbar.

Informationen zur FastTrack-Migration finden Sie in der [Office 365 US Government-Dienstbeschreibung.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack)

## <a name="security-and-compliance-features"></a>Sicherheits- und Compliancefeatures

Es gibt keine bekannten Unterschiede zwischen den Sicherheits- und Compliancefeatures für kommerzielle Kunden und denen für Government Cloud-Kunden.

Informationen zu Sicherheits- und Compliancefeatures finden Sie im [Security & Compliance Center.](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-securitycompliance-center)

Informationen zu Azure Active Directory-Features für Behörden finden Sie in der Dokumentation zu [Azure Government Security + Identity.](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory) 

Informationen zu Azure Information Protection-Features für Behörden finden Sie in der [Azure Information Protection Premium Government Service Description](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description). 

## <a name="sites-and-content"></a>Websites und Inhalte

Hier sind die Unterschiede zwischen den Website- und Inhaltsfeatures für kommerzielle Kunden und denen für Government Cloud-Kunden:

- Webparts, die auf Verbindungen mit Internetdiensten wie Amazon Bing, Bing Maps, Twitter und YouTube angewiesen sind, funktionieren nicht wie erwartet
- Bibliothek für Organisationsressourcen ist nicht verfügbar
- Das Hinzufügen von Listen und Seiten zu Teams ist für GCC High- und DoD-Kunden nicht verfügbar.
- Die Graphfunktionalität in SharePoint Online für GCC High ist derzeit deaktiviert. Jeder Dienst, der auf Microsoft Graph basiert, ist derzeit möglicherweise nicht verfügbar.

## <a name="search-features"></a>Suchfeatures

Hier sind die Unterschiede zwischen den Suchfeatures für kommerzielle Kunden und denen für Government Cloud-Kunden:

- Die Microsoft Search-Integration ist nicht verfügbar.

## <a name="sharing-and-sync"></a>Freigabe und Synchronisierung

Funktionsunterschiede zwischen der kommerziellen Cloud und der Government Cloudumgebung finden Sie unter [Dateifreigabe.](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing)

## <a name="plan-for-governance"></a>Planen der Steuerung

Ihr Wechsel in die Cloud bietet transformative Erfahrungen mit integrierten Administratorsteuerelementen. Bestimmen Sie Ihre Anforderungen für governance und wie Sie diese erfüllen können. Weitere Informationen [finden Sie unter "Plan for governance to transform teamwork with Microsoft 365".](https://resources.techcommunity.microsoft.com/teamwork-governance/) Hier finden Sie Anleitungen zu Office 365-Gruppen, SharePoint, Teams und mehr.

## <a name="deploy-sharepoint-for-collaboration"></a>Bereitstellen von SharePoint für die Zusammenarbeit

Nachdem Sie Ihre Organisation in der Microsoft US Government Cloud eingerichtet haben, folgen Sie dem empfohlenen Bereitstellungspfad, der im [SharePoint Adoption Resource Center beschrieben ist.](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/) Stellen Sie sicher, dass Sie sich mit Ihren Einführungs- und Change Management-Champions beschäftigen.
Sie können auch mit [FastTrack oder](https://www.microsoft.com/fasttrack) Ihrem ausgewählten Partner zusammenarbeiten, um den Dienst für Ihre Benutzer zu nutzen.
Besuchen Sie [das Microsoft Trust Center,](https://www.microsoft.com/trust-center) um mehr darüber zu erfahren, wie Microsoft Sicherheit, Datenschutz und Compliance, die wichtigsten Grundsätze für die Unterstützung von Organisationen in der Lage sind, ihre Kunden zu bedienen.
