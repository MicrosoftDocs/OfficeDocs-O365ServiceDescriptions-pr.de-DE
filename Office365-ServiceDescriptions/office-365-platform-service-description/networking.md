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
ms.openlocfilehash: 318437ce65c5ced55d42e798bf76774cda6708f9
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173020"
---
# <a name="networking"></a>Netzwerk

Microsoft unterstützt die folgenden Netzwerkfunktionen.
  
## <a name="ports-protocols-and-ip-addresses"></a>Ports, Protokolle und IP-Adressen

Microsoft verwendet IPv4- und IPv6-Adressen. Die Verwendung von IPv6-Adressen ist optional und für Konnektivität mit Office 365 nicht erforderlich. Nicht alle Microsoft 365-Features sind mit IPv6 vollständig aktiviert. Weitere Informationen zum Ipv6-Support finden Sie unter [IPv6-Support in Microsoft Services](/office365/enterprise/ipv6-support).
  
Microsoft verwaltet eine Liste der zulässigen IP-Adressen in der Microsoft-Hilfe. Weitere Informationen finden Sie unter [URLs und IP-Adressbereiche](/office365/enterprise/urls-and-ip-address-ranges). Für Office 365 betrieben von 21Vianet finden Sie entsprechende Informationen unter [URLs and IP Addresses for Office 365 operated by 21Vianet](/office365/enterprise/managing-office-365-endpoints). Für Office 365 Deutschland finden Sie die betreffenden Informationen unter [Endpunkte - Office 365 Deutschland](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Es wird dringend empfohlen, statt dem Routing zu bestimmten IP-Adress-Subnetzen das Routing an die Stammdomänennamen zu aktivieren, die in den oben aufgeführten Artikeln aufgelistet sind (z. B. \*.Outlook.com, \*.MicrosoftOnline.com und \*.SharePoint.com). Das Arbeiten mit IP-Adress-Subnetzen birgt das Risiko von Systemausfällen für Ihre Benutzer, sobald Änderungen erfolgen. 
  
## <a name="bandwidth-requirements"></a>Erforderliche Bandbreite

Informationen zu Bandbreitenanforderungen finden Sie im Artikel zum Thema [Planen der Internetbandbreite](/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-microsoft"></a>Herstellen einer Verbindung mit Microsoft

Alle Verbindungen mit Microsoft werden über das öffentliche Internet oder über eine private Azure ExpressRoute-Verbindung ausgeführt und werden gegebenenfalls durch SSL gesichert. Azure ExpressRoute ermöglicht eine direkte Verbindung mit dem globalen Microsoft-Netzwerk, indem das Internet umgangen wird. Ein Microsoft-Netzwerkpartner stellt die Konnektivität zum globalen Netzwerk von Microsoft bereit.
  
Weitere Informationen zu Azure ExpressRoute finden Sie unter [Azure ExpressRoute für Office 365](/microsoft-365/enterprise/azure-expressroute).
  
### <a name="wan-accelerators"></a>WAN-Optimierung

Microsoft bietet keinen Support für kundeneigene Lösungen für WAN-Beschleunigung oder Geräte zur Zwischenspeicherung, die zusammen mit Office 365 eingesetzt werden. Wenn Sie zur Verbesserung der Leistung bei hoher Latenz oder geringer Bandbreite einen Controller zur WAN-Optimierung verwenden, müssen Sie diesen Controller während der Problembehandlung im Rahmen von Serviceanfragen an Microsoft deaktivieren. Bei Supportbedarf für das Gerät müssen Sie sich an den Gerätehersteller selbst wenden. Weitere Informationen finden Sie in diesem Artikel zum Thema [Einsatz von WAN-Beschleunigung und Geräten für die Zwischenspeicherung mit Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Das globale Netzwerk von Microsoft

Die Microsoft-Netzwerkinfrastruktur besteht aus einem großen globalen Portfolio an Rechenzentren, Servern, Inhaltsverteilungsnetzwerken, Edge-Computing-Knoten und Glasfasernetzwerken, um eine globale Verteilung von Diensten zu ermöglichen. Die ausgefeilte Dienstinstrumentierung und -überwachung integriert sich auf den tiefsten Ebenen in jede Komponente und bietet Einblicke in das Rechenzentrum, das Netzwerk backbone, den Internetaustausch und darüber hinaus, um die Ursache von Störungen zu erkennen, zu diagnostizieren und zu verwalten. Das Netzwerk ist so aufgebaut, dass auch bei großen Netzwerkunterbrechungen ohne Leistungseinbußen genügend Kapazität vorhanden ist. Weitere Informationen finden Sie unter [Microsoft Global Network](/azure/networking/microsoft-global-network). 
  
Um die Vertraulichkeit und Integrität von Kundendaten zu wahren, hält Microsoft Verbraucherdienstenetzwerke von Microsoft-Netzwerken getrennt. Es werden verschiedenste Techniken zur Steuerung des Informationsflusses eingesetzt, darunter die folgenden:
  
- Räumliche Trennung. Netzwerksegmente werden durch Router physisch getrennt, die so konfiguriert sind, dass sie bestimmte Kommunikationsmuster vermeiden.
    
- Logische Trennung. Virtuelles LAN (VLAN) wird für eine weitergehende Trennung von Kommunikation eingesetzt.
    
- Firewalls. Firewalls und andere Durchsetzungspunkte für die Netzwerksicherheit werden verwendet, um den Datenaustausch mit Systemen zu beschränken, die dem Internet ausgesetzt sind, und um Systeme von von Microsoft verwalteten Back-End-Systemen zu isolieren. 
    
- Protokolleinschränkungen.
    
Weitere Informationen finden Sie im [Office 365 Trust Center](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in allen Plänen finden Sie unter [Microsoft 365- und Office 365-Plattformdienstbeschreibung](office-365-platform-service-description.md).
