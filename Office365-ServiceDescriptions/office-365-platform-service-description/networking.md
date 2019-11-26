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
# <a name="networking"></a><span data-ttu-id="71fd3-103">Netzwerk</span><span class="sxs-lookup"><span data-stu-id="71fd3-103">Networking</span></span>

<span data-ttu-id="71fd3-104">Microsoft Office 365 unterstützt die folgenden Netzwerkfunktionen.</span><span class="sxs-lookup"><span data-stu-id="71fd3-104">Microsoft Office 365 supports the following networking features.</span></span>
  
## <a name="ports-protocols-and-ip-addresses"></a><span data-ttu-id="71fd3-105">Ports, Protokolle und IP-Adressen</span><span class="sxs-lookup"><span data-stu-id="71fd3-105">Ports, protocols, and IP addresses</span></span>

<span data-ttu-id="71fd3-p101">Office 365 verwendet IPv4- und IPv6-Adressen. Die Verwendung von IPv6-Adressen ist optional und für Konnektivität mit Office 365 nicht erforderlich. Bei Verwendung von IPv6 sind nicht alle Office 365-Features vollständig aktiviert. Weitere Informationen zur IPv6-Unterstützung in Office 365 finden Sie unter [IPv6-Unterstützung in Office 365-Diensten](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span><span class="sxs-lookup"><span data-stu-id="71fd3-p101">Office 365 uses IPv4 and IPv6 addresses. Use of IPv6 addressing is optional and not required for connectivity with Office 365. Not all Office 365 features are fully enabled using IPv6. For more information about Ipv6 support in Office 365, see [IPv6 support in Office 365 services](https://docs.microsoft.com/office365/enterprise/ipv6-support).</span></span>
  
<span data-ttu-id="71fd3-p102">Office 365 enthält eine Liste zulässiger IP-Adressen in der Office 365-Hilfe. Weitere Informationen finden Sie unter [URLs und IP-Adressbereiche von Office 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). Für Office 365 betrieben von 21Vianet finden Sie entsprechende Informationen unter [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). Für Office 365 Deutschland finden Sie die betreffenden Informationen unter [Endpunkte - Office 365 Deutschland](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span><span class="sxs-lookup"><span data-stu-id="71fd3-p102">Office 365 maintains a list of allowed IP addresses in the Office 365 help. For more information, see [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges). For Office 365 operated by 21Vianet, see [URLs and IP Addresses for Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/enterprise/managing-office-365-endpoints). For Office 365 Germany, see [Office 365 Germany endpoints](https://support.office.com/article/Office-365-Germany-endpoints-8a113a50-0071-4155-bb8e-eba5a8dbd4c8).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="71fd3-p103">Es wird dringend empfohlen, statt dem Routing zu bestimmten IP-Adress-Subnetzen das Routing an die Stammdomänennamen zu aktivieren, die in den oben aufgeführten Artikeln aufgelistet sind (z. B. \*.Outlook.com, \*.MicrosoftOnline.com und \*.SharePoint.com). Das Arbeiten mit IP-Adress-Subnetzen birgt das Risiko von Systemausfällen für Ihre Benutzer, sobald Änderungen erfolgen.</span><span class="sxs-lookup"><span data-stu-id="71fd3-p103">We strongly recommend that you enable routing to the root domain names listed in the articles above (such as \*.Outlook.com, \*.MicrosoftOnline.com and \*.SharePoint.com) instead of routing to specific IP address subnets. Relying on IP address subnets runs the risk of outages for your users as changes are made.</span></span> 
  
## <a name="bandwidth-requirements"></a><span data-ttu-id="71fd3-116">Erforderliche Bandbreite</span><span class="sxs-lookup"><span data-stu-id="71fd3-116">Bandwidth requirements</span></span>

<span data-ttu-id="71fd3-117">Informationen zu Bandbreitenanforderungen finden Sie im Artikel zum Thema [Planen der Internetbandbreite](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span><span class="sxs-lookup"><span data-stu-id="71fd3-117">For information on bandwidth requirements, see [Internet bandwidth planning](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance).</span></span>
  
## <a name="connecting-to-office-365"></a><span data-ttu-id="71fd3-118">Verbinden mit Office 365</span><span class="sxs-lookup"><span data-stu-id="71fd3-118">Connecting to Office 365</span></span>

<span data-ttu-id="71fd3-119">Alle Verbindungen mit Office 365 werden über das öffentliche Internet oder über eine private Azure Express Route-Verbindung ausgeführt und durch SSL entsprechend gesichert.</span><span class="sxs-lookup"><span data-stu-id="71fd3-119">All Connections to Office 365 are done over the public internet or over a private Azure ExpressRoute connection, and are secured by SSL as appropriate.</span></span> <span data-ttu-id="71fd3-120">Azure Express Route ermöglicht die direkte Verbindung mit dem globalen Microsoft-Netzwerk, wobei das Internet umgangen wird.</span><span class="sxs-lookup"><span data-stu-id="71fd3-120">Azure ExpressRoute allows connecting directly to the global Microsoft network, bypassing the internet.</span></span> <span data-ttu-id="71fd3-121">Ein Microsoft-Netzwerkpartner stellt die Konnektivität zum globalen Netzwerk von Microsoft bereit.</span><span class="sxs-lookup"><span data-stu-id="71fd3-121">A Microsoft networking partner provides the connectivity to the global Microsoft network.</span></span>
  
<span data-ttu-id="71fd3-122">Weitere Informationen zu Azure ExpressRoute finden Sie unter [Azure ExpressRoute für Office 365](https://aka.ms/expressrouteoffice365).</span><span class="sxs-lookup"><span data-stu-id="71fd3-122">For more information about Azure ExpressRoute, see [Azure ExpressRoute for Office 365.](https://aka.ms/expressrouteoffice365)</span></span>
  
### <a name="wan-accelerators"></a><span data-ttu-id="71fd3-123">WAN-Optimierung</span><span class="sxs-lookup"><span data-stu-id="71fd3-123">WAN accelerators</span></span>

<span data-ttu-id="71fd3-p105">Microsoft bietet keinen Support für kundeneigene Lösungen für WAN-Beschleunigung oder Geräte zur Zwischenspeicherung, die zusammen mit Office 365 eingesetzt werden. Wenn Sie zur Verbesserung der Leistung bei hoher Latenz oder geringer Bandbreite einen Controller zur WAN-Optimierung verwenden, müssen Sie diesen Controller während der Problembehandlung im Rahmen von Serviceanfragen an Microsoft deaktivieren. Bei Supportbedarf für das Gerät müssen Sie sich an den Gerätehersteller selbst wenden. Weitere Informationen finden Sie in diesem Artikel zum Thema [Einsatz von WAN-Beschleunigung und Geräten für die Zwischenspeicherung mit Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span><span class="sxs-lookup"><span data-stu-id="71fd3-p105">Microsoft does not provide support for customer-owned WAN acceleration and caching devices with Office 365. If you decide to use a WAN optimization controller to improve performance under conditions of high latency or low bandwidth, you'll need to disable it while troubleshooting service requests with Microsoft, and work with your device vendor for device support. For more information, see [WAN Acceleration and caching devices with Office 365](https://support.microsoft.com/help/2690045/using-third-party-network-devices-or-solutions-with-office-365).</span></span>
  
## <a name="the-global-microsoft-network"></a><span data-ttu-id="71fd3-127">Das globale Netzwerk von Microsoft</span><span class="sxs-lookup"><span data-stu-id="71fd3-127">The global Microsoft network</span></span>

<span data-ttu-id="71fd3-128">Die Office 365 Netzwerkinfrastruktur besteht aus einem großen globalen Portfolio an Rechenzentren, Servern, Inhalts Verteilungs Netzwerken, Edge-Computing-Knoten und Glasfaser-Netzwerken, um eine globale Verteilung der Dienste bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="71fd3-128">The Office 365 networking infrastructure is comprised of a large global portfolio of data centers, servers, content distribution networks, edge computing nodes, and fiber optic networks to provide global distribution of services.</span></span> <span data-ttu-id="71fd3-129">Die ausgefeilte Dienst Instrumentation und Überwachung integriert sich auf den tiefsten Ebenen mit jeder Komponente, wodurch die Sichtbarkeit im Rechenzentrum, im Netzwerkbackbone, im Internet Austausch und darüber hinaus liegt, um die Ursache von Unterbrechungen zu erkennen, zu diagnostizieren und zu verwalten, die entstehen.</span><span class="sxs-lookup"><span data-stu-id="71fd3-129">Sophisticated service instrumentation and monitoring integrates at the deepest levels with each component, giving visibility into the data center, network backbone, internet exchanges and beyond, to help spot, diagnose and manage the cause of disruptions that arise.</span></span> <span data-ttu-id="71fd3-130">Das Netzwerk ist so konzipiert, dass auch bei umfangreichen Netzwerk Unterbrechungen ohne Beeinträchtigung der Leistung ausreichende Kapazität gewährleistet ist.</span><span class="sxs-lookup"><span data-stu-id="71fd3-130">The network is built to maintain sufficient capacity even for large scale network interruptions without degradation of performance.</span></span> <span data-ttu-id="71fd3-131">Weitere Informationen finden Sie unter [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span><span class="sxs-lookup"><span data-stu-id="71fd3-131">For more information, see [Microsoft Global Network](https://docs.microsoft.com/azure/networking/microsoft-global-network).</span></span> 
  
<span data-ttu-id="71fd3-p107">Um die Vertraulichkeit und Integrität von Kundendaten sicherstellen zu können, trennt Microsoft zwischen Kundendienstnetzwerken und Office 365-Netzwerken. Es werden verschiedenste Techniken zur Steuerung des Informationsflusses eingesetzt, darunter die folgenden:</span><span class="sxs-lookup"><span data-stu-id="71fd3-p107">To maintain the confidentiality and integrity of customer data, Microsoft keeps consumer services networks separate from Office 365 networks. Multiple techniques are used to control information flows, including but not limited to:</span></span>
  
- <span data-ttu-id="71fd3-p108">Räumliche Trennung. Netzwerksegmente werden durch Router physisch getrennt, die so konfiguriert sind, dass sie bestimmte Kommunikationsmuster vermeiden.</span><span class="sxs-lookup"><span data-stu-id="71fd3-p108">Physical separation. Network segments are physically separated by routers that are configured to prevent specific communication patterns.</span></span>
    
- <span data-ttu-id="71fd3-p109">Logische Trennung. Virtuelles LAN (VLAN) wird für eine weitergehende Trennung von Kommunikation eingesetzt.</span><span class="sxs-lookup"><span data-stu-id="71fd3-p109">Logical separation. Virtual LAN (VLAN) technology is used to further separate communications.</span></span>
    
- <span data-ttu-id="71fd3-138">Firewalls.</span><span class="sxs-lookup"><span data-stu-id="71fd3-138">Firewalls.</span></span> <span data-ttu-id="71fd3-139">Firewalls und andere Netzwerksicherheits-Durchsetzungs Punkte werden verwendet, um den Datenaustausch mit Systemen zu begrenzen, die mit dem Internet verbunden sind, und um Systeme von Back-End-Systemen zu isolieren, die von Microsoft verwaltet werden.</span><span class="sxs-lookup"><span data-stu-id="71fd3-139">Firewalls and other network security enforcement points are used to limit data exchanges with systems that are exposed to the internet, and to isolate systems from back-end systems managed by Microsoft.</span></span> 
    
- <span data-ttu-id="71fd3-140">Protokolleinschränkungen.</span><span class="sxs-lookup"><span data-stu-id="71fd3-140">Protocol restrictions.</span></span>
    
<span data-ttu-id="71fd3-141">Weitere Informationen finden Sie im [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span><span class="sxs-lookup"><span data-stu-id="71fd3-141">For more information, see the [Office 365 Trust Center](https://www.microsoft.com/trust-center).</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="71fd3-142">Verfügbarkeit von Funktionen</span><span class="sxs-lookup"><span data-stu-id="71fd3-142">Feature availability</span></span>

<span data-ttu-id="71fd3-143">Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen finden Sie unter [Office 365 Platform Service Description](office-365-platform-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="71fd3-143">To view feature availability across Office 365 plans, see [Office 365 platform service description](office-365-platform-service-description.md).</span></span>
  

