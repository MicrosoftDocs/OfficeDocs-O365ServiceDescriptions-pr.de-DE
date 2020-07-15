---
title: Netzwerk
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft unterstützt die folgenden Netzwerkfunktionen.
ms.openlocfilehash: 0f0554bdd907a6f0a37299dc3e38e5f778e7187e
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132329"
---
# <a name="networking"></a>Netzwerk

Microsoft unterstützt die folgenden Netzwerkfunktionen.
  
## <a name="ports-protocols-and-ip-addresses"></a>Ports, Protokolle und IP-Adressen

Microsoft verwendet IPv4-und IPv6-Adressen. Die Verwendung von IPv6-Adressen ist optional und für Konnektivität mit Office 365 nicht erforderlich. Nicht alle Microsoft 365-Funktionen sind mit IPv6 vollständig aktiviert. Weitere Informationen zur IPv6-Unterstützung finden Sie unter [IPv6-Unterstützung in Microsoft Services](https://docs.microsoft.com/office365/enterprise/ipv6-support).
  
Microsoft verwaltet eine Liste zugelassener IP-Adressen in der Microsoft-Hilfe. Weitere Informationen finden Sie unter [URLs und IP-Adressbereiche](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). Für Office 365 betrieben von 21Vianet finden Sie entsprechende Informationen unter [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). Für Office 365 Deutschland finden Sie die betreffenden Informationen unter [Endpunkte - Office 365 Deutschland](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made. 
  
## <a name="bandwidth-requirements"></a>Erforderliche Bandbreite

Informationen zu Bandbreitenanforderungen finden Sie im Artikel zum Thema [Planen der Internetbandbreite](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Herstellen einer Verbindung mit Microsoft

Alle Verbindungen mit Microsoft werden über das öffentliche Internet oder über eine private Azure Express Route-Verbindung ausgeführt und durch SSL entsprechend gesichert. Azure Express Route ermöglicht die direkte Verbindung mit dem globalen Microsoft-Netzwerk, wobei das Internet umgangen wird. Ein Microsoft-Netzwerkpartner stellt die Konnektivität zum globalen Netzwerk von Microsoft bereit.
  
Weitere Informationen zu Azure ExpressRoute finden Sie unter [Azure ExpressRoute für Office 365](https://aka.ms/expressrouteoffice365).
  
### <a name="wan-accelerators"></a>WAN-Optimierung

Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Das globale Netzwerk von Microsoft

Die Microsoft-Netzwerkinfrastruktur besteht aus einem großen globalen Portfolio an Rechenzentren, Servern, Inhalts Verteilungs Netzwerken, Edge-Computing-Knoten und Glasfaser-Netzwerken, um eine globale Verteilung der Dienste bereitzustellen. Die ausgefeilte Dienst Instrumentation und Überwachung integriert sich auf den tiefsten Ebenen mit jeder Komponente, wodurch die Sichtbarkeit im Rechenzentrum, im Netzwerkbackbone, im Internet Austausch und darüber hinaus liegt, um die Ursache der auftretenden Unterbrechungen zu erkennen, zu diagnostizieren und zu verwalten. Das Netzwerk ist so konzipiert, dass auch bei umfangreichen Netzwerk Unterbrechungen ohne Beeinträchtigung der Leistung ausreichende Kapazität gewährleistet ist. Weitere Informationen finden Sie unter [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network). 
  
Um die Vertraulichkeit und Integrität von Kundendaten aufrechtzuerhalten, hält Microsoft Consumer Services-Netzwerke von Microsoft-Netzwerken getrennt. Es werden verschiedenste Techniken zur Steuerung des Informationsflusses eingesetzt, darunter die folgenden:
  
- Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.
    
- Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.
    
- Firewalls. Firewalls und andere Netzwerksicherheits-Durchsetzungs Punkte werden verwendet, um den Datenaustausch mit Systemen zu begrenzen, die mit dem Internet verbunden sind, und um Systeme von Back-End-Systemen zu isolieren, die von Microsoft verwaltet werden. 
    
- Protokolleinschränkungen.
    
Weitere Informationen finden Sie im [Office 365 Trust Center](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen finden Sie unter [Microsoft 365 und Office 365 Platform Service Description](office-365-platform-service-description.md).
  

