---
title: Netzwerk
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 unterstützt die folgenden Netzwerkfunktionen.
ms.openlocfilehash: f2343872faac2b1b289c37b8dc91240fa030482d
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262898"
---
# <a name="networking"></a>Netzwerk

Microsoft Office 365 unterstützt die folgenden Netzwerkfunktionen.
  
## <a name="ports-protocols-and-ip-addresses"></a>Ports, Protokolle und IP-Adressen

Office 365 verwendet IPv4- und IPv6-Adressen. Die Verwendung von IPv6-Adressen ist optional und für Konnektivität mit Office 365 nicht erforderlich. Bei Verwendung von IPv6 sind nicht alle Office 365-Features vollständig aktiviert. Weitere Informationen zur IPv6-Unterstützung in Office 365 finden Sie unter [IPv6-Unterstützung in Office 365-Diensten](https://docs.microsoft.com/office365/enterprise/ipv6-support).
  
Office 365 enthält eine Liste zulässiger IP-Adressen in der Office 365-Hilfe. Weitere Informationen finden Sie unter [URLs und IP-Adressbereiche von Office 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). Für Office 365 betrieben von 21Vianet finden Sie entsprechende Informationen unter [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). Für Office 365 Deutschland finden Sie die betreffenden Informationen unter [Endpunkte - Office 365 Deutschland](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Es wird dringend empfohlen, statt dem Routing zu bestimmten IP-Adress-Subnetzen das Routing an die Stammdomänennamen zu aktivieren, die in den oben aufgeführten Artikeln aufgelistet sind (z. B. \*.Outlook.com, \*.MicrosoftOnline.com und \*.SharePoint.com). Das Arbeiten mit IP-Adress-Subnetzen birgt das Risiko von Systemausfällen für Ihre Benutzer, sobald Änderungen erfolgen. 
  
## <a name="bandwidth-requirements"></a>Erforderliche Bandbreite

Informationen zu Bandbreitenanforderungen finden Sie im Artikel zum Thema [Planen der Internetbandbreite](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).
  
## <a name="connecting-to-office-365"></a>Verbinden mit Office 365

Alle Verbindungen mit Office 365 werden über das öffentliche Internet oder über eine private Azure Express Route-Verbindung ausgeführt und durch SSL entsprechend gesichert. Azure Express Route ermöglicht die direkte Verbindung mit dem globalen Microsoft-Netzwerk, wobei das Internet umgangen wird. Ein Microsoft-Netzwerkpartner stellt die Konnektivität zum globalen Netzwerk von Microsoft bereit.
  
Weitere Informationen zu Azure ExpressRoute finden Sie unter [Azure ExpressRoute für Office 365](https://aka.ms/expressrouteoffice365).
  
### <a name="wan-accelerators"></a>WAN-Optimierung

Microsoft bietet keinen Support für kundeneigene Lösungen für WAN-Beschleunigung oder Geräte zur Zwischenspeicherung, die zusammen mit Office 365 eingesetzt werden. Wenn Sie zur Verbesserung der Leistung bei hoher Latenz oder geringer Bandbreite einen Controller zur WAN-Optimierung verwenden, müssen Sie diesen Controller während der Problembehandlung im Rahmen von Serviceanfragen an Microsoft deaktivieren. Bei Supportbedarf für das Gerät müssen Sie sich an den Gerätehersteller selbst wenden. Weitere Informationen finden Sie in diesem Artikel zum Thema [Einsatz von WAN-Beschleunigung und Geräten für die Zwischenspeicherung mit Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).
  
## <a name="the-global-microsoft-network"></a>Das globale Netzwerk von Microsoft

Die Office 365 Netzwerkinfrastruktur besteht aus einem großen globalen Portfolio an Rechenzentren, Servern, Inhalts Verteilungs Netzwerken, Edge-Computing-Knoten und Glasfaser-Netzwerken, um eine globale Verteilung der Dienste bereitzustellen. Die ausgefeilte Dienst Instrumentation und Überwachung integriert sich auf den tiefsten Ebenen mit jeder Komponente, wodurch die Sichtbarkeit im Rechenzentrum, im Netzwerkbackbone, im Internet Austausch und darüber hinaus liegt, um die Ursache von Unterbrechungen zu erkennen, zu diagnostizieren und zu verwalten, die entstehen. Das Netzwerk ist so konzipiert, dass auch bei umfangreichen Netzwerk Unterbrechungen ohne Beeinträchtigung der Leistung ausreichende Kapazität gewährleistet ist. Weitere Informationen finden Sie unter [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network). 
  
Um die Vertraulichkeit und Integrität von Kundendaten sicherstellen zu können, trennt Microsoft zwischen Kundendienstnetzwerken und Office 365-Netzwerken. Es werden verschiedenste Techniken zur Steuerung des Informationsflusses eingesetzt, darunter die folgenden:
  
- Räumliche Trennung. Netzwerksegmente werden durch Router physisch getrennt, die so konfiguriert sind, dass sie bestimmte Kommunikationsmuster vermeiden.
    
- Logische Trennung. Virtuelles LAN (VLAN) wird für eine weitergehende Trennung von Kommunikation eingesetzt.
    
- Firewalls. Firewalls und andere Netzwerksicherheits-Durchsetzungs Punkte werden verwendet, um den Datenaustausch mit Systemen zu begrenzen, die mit dem Internet verbunden sind, und um Systeme von Back-End-Systemen zu isolieren, die von Microsoft verwaltet werden. 
    
- Protokolleinschränkungen.
    
Weitere Informationen finden Sie im [Office 365 Trust Center](https://www.microsoft.com/trust-center). 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen finden Sie unter [Office 365 Platform Service Description](office-365-platform-service-description.md).
  

