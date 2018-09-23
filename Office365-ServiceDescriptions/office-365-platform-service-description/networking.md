---
title: Netzwerk
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-networking
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 073dea34-7fd8-4c1d-9a31-6bee87924a81
description: Microsoft Office 365 unterstützt die folgenden Netzwerkfeatures.
ms.openlocfilehash: 8a9a8d8b5276f4f4578fec625849410268f855ad
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/19/2018
ms.locfileid: "24035738"
---
# <a name="networking"></a>Netzwerk

Microsoft Office 365 unterstützt die folgenden Netzwerkfeatures.
  
## <a name="ports-protocols-and-ip-addresses"></a>Ports, Protokolle und IP-Adressen

Office 365 verwendet IPv4- und IPv6-Adressen. Die Verwendung von IPv6-Adressen ist optional und für Konnektivität mit Office 365 nicht erforderlich. Bei Verwendung von IPv6 sind nicht alle Office 365-Features vollständig aktiviert. Weitere Informationen zur IPv6-Unterstützung in Office 365 finden Sie unter [IPv6-Unterstützung in Office 365-Diensten](https://go.microsoft.com/fwlink/?LinkID=785121&amp;clcid=0x409).
  
Office 365 enthält eine Liste zulässiger IP-Adressen in der Office 365-Hilfe. Weitere Informationen finden Sie unter [URLs und IP-Adressbereiche von Office 365](https://go.microsoft.com/fwlink/p/?LinkID=243567). Für Office 365 betrieben von 21Vianet finden Sie entsprechende Informationen unter [URLs and IP Addresses for Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733351&amp;clcid=0x409). Für Office 365 Deutschland finden Sie die betreffenden Informationen unter [Endpunkte - Office 365 Deutschland](https://support.office.com/en-us/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).
  
> [!IMPORTANT]
> Es wird dringend empfohlen, statt dem Routing zu bestimmten IP-Adress-Subnetzen das Routing an die Stammdomänennamen zu aktivieren, die in den oben aufgeführten Artikeln aufgelistet sind (z. B. \*.Outlook.com, \*.MicrosoftOnline.com und \*.SharePoint.com). Das Arbeiten mit IP-Adress-Subnetzen birgt das Risiko von Systemausfällen für Ihre Benutzer, sobald Änderungen erfolgen. 
  
## <a name="bandwidth-requirements"></a>Bandbreitenanforderungen

Informationen zu Bandbreitenanforderungen finden Sie im Artikel zum Thema [Planen der Internetbandbreite](https://go.microsoft.com/fwlink/p/?LinkID=282467).
  
## <a name="connecting-to-office-365"></a>Verbinden mit Office 365

Alle Verbindungen mit Office 365 erfolgen über das öffentliche Internet oder über eine private Azure ExpressRoute-Verbindung und werden nach Bedarf durch SSL gesichert. Azure ExpressRoute ermöglicht eine direkte Verbindung zum globalen Netzwerk von Microsoft unter Umgehung des Internets. Ein Microsoft-Netzwerkpartner stellt die Konnektivität zum globalen Netzwerk von Microsoft bereit.
  
Weitere Informationen zu Azure ExpressRoute finden Sie unter [Azure ExpressRoute für Office 365](https://aka.ms/expressrouteoffice365).
  
### <a name="wan-accelerators"></a>WAN-Beschleuniger

Microsoft bietet keinen Support für kundeneigene Lösungen für WAN-Beschleunigung oder Geräte zur Zwischenspeicherung, die zusammen mit Office 365 eingesetzt werden. Wenn Sie zur Verbesserung der Leistung bei hoher Latenz oder geringer Bandbreite einen Controller zur WAN-Optimierung verwenden, müssen Sie diesen Controller während der Problembehandlung im Rahmen von Serviceanfragen an Microsoft deaktivieren. Bei Supportbedarf für das Gerät müssen Sie sich an den Gerätehersteller selbst wenden. Weitere Informationen finden Sie in diesem Artikel zum Thema [Einsatz von WAN-Beschleunigung und Geräten für die Zwischenspeicherung mit Office 365](https://go.microsoft.com/fwlink/p/?LinkID=282468).
  
## <a name="the-global-microsoft-network"></a>Das globale Netzwerk von Microsoft

Die Office 365-Netzwerkinfrastruktur setzt sich aus einem umfangreichen globalen Portfolio von Rechenzentren, Servern, Inhaltsverteilungsnetzwerken, Edge-Computing-Knoten und Glasfasernetzen zusammen, das eine globale Diensteverteilung möglich macht. Ausgefeilte Dienstinstrumentierung und -überwachung ist bis hinunter auf die Ebene der einzelnen Komponenten integriert, sodass die Vorgänge im Rechenzentrum, im Netzwerkbackbone, an Internetknoten und darüber hinaus jederzeit transparent sind. Diese Transparenz hilft dabei, Unterbrechungen zu lokalisieren und ihre Ursachen zu diagnostizieren und zu beheben. Das Netzwerk ist so konzipiert, dass es selbst bei weitreichenden Unterbrechungen über genügend Kapazität verfügt, um Leistungseinbrüche zu verhindern. Weitere Informationen finden Sie unter [Global Foundation Services](https://go.microsoft.com/fwlink/p/?LinkID=282622). 
  
Um die Vertraulichkeit und Integrität von Kundendaten sicherstellen zu können, trennt Microsoft zwischen Kundendienstnetzwerken und Office 365-Netzwerken. Es werden verschiedenste Techniken zur Steuerung des Informationsflusses eingesetzt, darunter die folgenden:
  
- Räumliche Trennung. Netzwerksegmente werden durch Router physisch getrennt, die so konfiguriert sind, dass sie bestimmte Kommunikationsmuster vermeiden.
    
- Logische Trennung. Virtuelles LAN (VLAN) wird für eine weitergehende Trennung von Kommunikation eingesetzt.
    
- Firewalls. Firewalls und andere Durchsetzungspunkte für die Netzwerksicherheit dienen zur Begrenzung des Datenaustauschs mit Systemen mit Internetverbindung und zur Isolierung Ihrer Systeme von durch Microsoft verwalteten Back-End-Systemen. 
    
- Protokolleinschränkungen.
    
Weitere Informationen finden Sie im [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkID=282621). 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Weitere Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen finden Sie unter [Office 365-Plattformdienstbeschreibung](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

