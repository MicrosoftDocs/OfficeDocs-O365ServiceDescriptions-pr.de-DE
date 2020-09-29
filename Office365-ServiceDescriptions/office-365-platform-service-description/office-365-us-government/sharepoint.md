---
title: SharePoint für US-Regierungs Umgebungen
ms.author: mkashman
author: kaarins
manager: mkashman
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Erfahren Sie mehr über die SharePoint-Feature-Verfügbarkeit für US Government Cloud-Kunden.
ms.openlocfilehash: 4e09ec8fda62fb5ce7a6e886799c5f35edd32cf5
ms.sourcegitcommit: e342174df76128430dfc8c971716da5c4b2942ac
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/28/2020
ms.locfileid: "48294191"
---
# <a name="sharepoint-for-us-government-environments"></a>SharePoint für US-Regierungs Umgebungen

Dieser Artikel bietet eine Übersicht über Funktionsunterschiede zwischen der US Government-Cloud und der kommerziellen Cloud, wie in der [SharePoint-Dienstbeschreibung](/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-service-description)aufgeführt. SharePoint steht für die Umgebungen Government Community Cloud (gcc), gcc High und DoD zur Verfügung. 

Weitere Informationen zur Government-Cloud, einschließlich der Berechtigung und des Kaufs, finden Sie unter [Microsoft 365 Government-How to Buy](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/microsoft-365-government-how-to-buy). Informationen zum Vergleich Office 365er Regierungspläne finden Sie unter [Office 365 Government Plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans?rtc=1#EligibilityRequirements).

Informationen zu den erforderlichen Endpunkten beim Verwalten der Netzwerkkonnektivität finden Sie unter [Office 365 US Government gcc High Endpoint](/office365/enterprise/office-365-u-s-government-gcc-high-endpoints#sharepoint-online-and-onedrive-for-business) oder [Office 365 US Government DoD Endpoints](/office365/enterprise/office-365-u-s-government-dod-endpoints#sharepoint-online-and-onedrive-for-business).

Neben den Features und Funktionen von Office 365 profitieren Organisationen von den folgenden Features, die für die US Government Cloud-Umgebungen einzigartig sind:

-   Der Kunden Inhalt Ihrer Organisation wird logischerweise von Kundeninhalten in den kommerziellen Office 365 Diensten von Microsoft getrennt.
-   Der Kundeninhalt Ihrer Organisation wird in den Vereinigten Staaten gespeichert.
-   Der Zugriff auf den Kundeninhalt Ihrer Organisation ist auf ausgewähltes Microsoft-Personal beschränkt.
-   Die staatlichen Cloud-Umgebungen entsprechen Zertifizierungen und Akkreditierungen, die für US-Kunden des öffentlichen Sektors erforderlich sind.

Unser Ziel ist es, alle SharePoint-Geschäfts Features und-Funktionen für die Government-Cloud-Umgebungen bereitzustellen. Einige Funktionen sind aufgrund der Anforderungen von Government Cloud-Kunden nicht verfügbar. Andere Features kommen in die Regierungs Umgebungen, aber noch nicht zur Verfügung. In den folgenden Abschnitten finden Sie Informationen zur Verfügbarkeit von Features in den Government-Cloud-Umgebungen.

## <a name="developer-features"></a>Entwicklerfeatures

Es gibt keine bekannten Unterschiede zwischen den Entwicklerfeatures für kommerzielle Kunden und denen für Government Cloud-Kunden.

- Verbindungen mit externen Anwendungen wie Datenquellen für Add-Ins sind auf Quellen begrenzt, die sich innerhalb der von ihrer Regierungs Umgebung unterstützten System Sicherheitsgrenzen befinden.
- Business Connectivity Services (BCS) Funktionalität wird für Verbindungsszenarien unterstützt, in denen die Datenquellen innerhalb der Sicherheitsgrenze Ihres Cloud-Diensts erreichbar bleiben.

Wenn Sie Drittanbieteranwendungen auf Websites verwenden, überprüfen Sie die von den Drittanbietern bereitgestellten Datenschutz-und Konformitätserklärungen, wenn Sie die entsprechende Verwendung dieser Dienste für Ihre Organisation bewerten. Drittanbieteranwendungen und-Dienste umfassen möglicherweise das Speichern, übertragen und Verarbeiten der Kundendaten Ihrer Organisation auf Drittanbietersystemen, die sich außerhalb der Regierungs Cloud befinden und daher nicht von den Compliance-und Datenschutzverpflichtungen abgedeckt werden. 

## <a name="it-admin-features"></a>IT-Administrator Features

Hier sind die Unterschiede zwischen den IT-Administrator Features für kommerzielle Kunden und denen für Government Cloud-Kunden.

- Das Ändern einer Websiteadresse steht für gcc High-Kunden nicht zur Verfügung.
- Hybrid SharePoint Server steht nicht für alle Government Cloud-Kunden zur Verfügung
- Für das SharePoint-Migrations Tool und den Migrations-Manager ist eine Konfigurationsänderung erforderlich. Informationen finden Sie unter [SPMT Government Cloud Support](/sharepointmigration/spmt-install-issues#government-cloud-support).
- Mover.IO wird noch nicht unterstützt
- Multi-Geo steht nicht für alle Government Cloud-Kunden zur Verfügung

Informationen zur Migrations Migration finden Sie in der [Office 365 US Government Service Description](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#data-migrations-performed-by-fasttrack).

## <a name="security-and-compliance-features"></a>Sicherheits-und Compliance-Features

Es gibt keine bekannten Unterschiede zwischen den Sicherheits-und Compliance-Features für kommerzielle Kunden und denen für Government Cloud-Kunden.

Informationen zu den folgenden Funktionen finden Sie in der [Office 365 US Government Service Description](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/office-365-us-government#platform-features):
- Kunden-Lockbox
- Verhinderung von Datenverlust (Data Loss Prevention, DLP)
- eDiscovery (Inhaltssuche, Aufbewahrung, Export)
- Office 365 Advanced Threat Protection (ATP)
- Vertraulichkeitsbezeichnungen

Informationen zu Azure Active Directory-Features für die Regierung finden Sie unter [Azure Government Security + Identity Documentation](/azure/azure-government/documentation-government-services-securityandidentity#azure-active-directory). 

Informationen zu Azure Information Protection-Funktionen für die Regierung finden Sie in der [Azure Information Protection Premium Government-Dienstbeschreibung](/enterprise-mobility-security/solutions/ems-aip-premium-govt-service-description) 

## <a name="sites-and-content"></a>Websites und Inhalte

Hier sind die Unterschiede zwischen den Websites und den Inhalts Features für kommerzielle Kunden und die für Government Cloud-Kunden:

- Webparts, die auf Verbindungen mit Internet Diensten wie Amazon Kindle, Bing Maps, Twitter und YouTube-Webparts angewiesen sind, funktionieren nicht wie erwartet.
- Bibliothek "Organisationsobjekte" ist nicht verfügbar
- Das Hinzufügen von Listen und Seiten zu Microsoft Teams ist für gcc High-und DoD-Kunden nicht verfügbar.

## <a name="search-features"></a>Suchfeatures

Hier sind die Unterschiede zwischen den Suchfeatures für kommerzielle Kunden und die für Government Cloud-Kunden:

- Die Microsoft-Suchintegration ist nicht verfügbar.

## <a name="sharing-and-sync"></a>Freigabe und Synchronisierung

Informationen zu Funktions unterschieden zwischen der kommerziellen Cloud und den staatlichen Cloud-Umgebungen finden Sie unter [File Sharing](/office365/servicedescriptions/office-365-platform-service-description/office-365-us-government/gcc-high-and-dod#file-sharing).

## <a name="plan-for-governance"></a>Planen der Steuerung

Ihr Wechsel zur Cloud bietet transformative Erfahrungen mit integrierten Administrator Steuerelementen. Bestimmen Sie Ihre Anforderungen für die Steuerung und wie Sie Sie erfüllen können. Wechseln Sie zu [Plan for Governance, um die Zusammenarbeit mit Microsoft 365 zu transformieren,](https://resources.techcommunity.microsoft.com/teamwork-governance/) um weitere Informationen zu erhalten. Hier finden Sie Anleitungen zu Office 365 Gruppen, SharePoint, Teams und vielem mehr.

## <a name="deploy-sharepoint-for-collaboration"></a>Bereitstellen von SharePoint für die Zusammenarbeit

Nachdem Sie Ihre Organisation in der Microsoft US Government-Cloud eingerichtet haben, führen Sie den empfohlenen Bereitstellungspfad aus, der im [SharePoint-Adoptions-Ressourcencenter](https://resources.techcommunity.microsoft.com/resources/SharePoint-adoption/)erläutert wird. Stellen Sie sicher, dass Sie sich mit ihren Champions für Akzeptanz und Change Management beschäftigen.
Sie können [auch mit dem](https://www.microsoft.com/fasttrack) Kurzfilm oder Ihrem ausgewählten Partner zusammenarbeiten, um den Dienst für Ihre Benutzer bereitzustellen.
Besuchen Sie das [Microsoft Trust Center](https://www.microsoft.com/trust-center) , um mehr darüber zu erfahren, wie Microsoft Sicherheit, Datenschutz und Compliance angeht, Kernprinzipien dafür, wie wir Organisationen bei der Bereitstellung Ihrer Kunden unterstützen.
