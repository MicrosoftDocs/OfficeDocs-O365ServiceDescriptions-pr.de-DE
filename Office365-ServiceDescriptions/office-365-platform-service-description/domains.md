---
title: Domänen
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/10/2017
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Wenn Sie eine Domäne hinzufügen, hilft Ihnen ein Schritt-für-Schritt-Assistent beim Hinzufügen von Benutzern und beim Konvertieren Ihrer Office 365-e-Mail-Adressen und anderer Dienste in den Namen Ihres Unternehmens. Wenn Sie den Assistenten abschließen, beginnt Ihr geschäftlicher e-Mail-Dienst zu Office 365, statt zu Ihrem aktuellen e-Mail-Anbieter zu wechseln. Weitere Informationen finden Sie unter Hinzufügen Ihrer Benutzer und Domänen zu Office 365. Wenn Sie Office 365, betrieben von 21Vianet, verwenden, finden Sie weitere Informationen unter Überprüfen Ihrer Domäne.
ms.openlocfilehash: 15254355d2bb7aed01d7be8c8e56d455409a51a5
ms.sourcegitcommit: 4abe1be8a63406e8a8c1a4a69f95386906ea1499
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 02/22/2019
ms.locfileid: "30210238"
---
# <a name="domains"></a>Domänen

Wenn Sie eine Domäne hinzufügen, hilft Ihnen ein Schritt-für-Schritt-Assistent beim Hinzufügen von Benutzern und beim Konvertieren Ihrer Office 365-e-Mail-Adressen und anderer Dienste in den Namen Ihres Unternehmens. Wenn Sie den Assistenten abschließen, beginnt Ihr geschäftlicher e-Mail-Dienst zu Office 365, statt zu Ihrem aktuellen e-Mail-Anbieter zu wechseln. Weitere Informationen finden Sie unter [Hinzufügen Ihrer Benutzer und Domänen zu Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Wenn Sie Office 365, betrieben von 21Vianet, verwenden, finden Sie weitere Informationen unter [Überprüfen Ihrer Domäne](http://go.microsoft.com/fwlink/?LinkID=733344&amp;clcid=0x409).
  
## <a name="custom-domains"></a>Benutzerdefinierte Domänen
<a name="BKMK_CustomDomains"> </a>

Sie können Ihrem Office 365-Abonnement bis zu 900 Domänen hinzufügen. Sie können jedoch keine Domäne zu Office 365 hinzufügen, die Sie bereits in einem anderen Microsoft-clouddienst verwenden. Dies führt dazu, dass Sie die gleiche Domäne nicht mehreren Office 365-Abonnements hinzufügen können. Weitere Informationen finden Sie unter [häufig gestellte Fragen zu Domänen](https://support.office.com/en-us/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domänen der zweiten und dritten Ebene
<a name="BKMK_SecondAndThirdLevelDomains"> </a>

Mit Office 365 Enterprise und Office 365 Business können Sie jede beliebige Domänenebene hinzufügen, einschließlich Domänen der dritten Ebene, z. B. „marketing.contoso.com". Informationen dazu finden Sie unter [Hinzufügen benutzerdefinierter Unterdomänen oder mehrerer Domänen zu Office 365](http://go.microsoft.com/fwlink/?LinkID=733345&amp;clcid=0x409). Wenn Sie Office 365 verwenden, betrieben von 21Vianet, lesen Sie [Hinzufügen benutzerdefinierter Unterdomänen oder mehrerer Domänen zu Office 365, betrieben von 21Vianet](http://go.microsoft.com/fwlink/?LinkID=733346&amp;clcid=0x409).
  
## <a name="domain-verification-and-managing-dns-records"></a>Domänenüberprüfung und Verwaltung von DNS-Einträgen
<a name="BKMK_ManagingDNSRecords"> </a>

Mit Office 365 können Sie Ihre DNS-Einträge bei Ihrem DNS-Hostinganbieter verwalten oder Office 365 einrichten und die DNS-Einträge Ihrer Domäne für Sie verwalten lassen. Wenn Sie die Datensätze weiterhin verwalten, ändern Sie bestimmte Datensätze bei Bedarf, sodass sie auf Office 365 Dienste verweisen. Eine Liste der Domänenregistrierungsstellen, für die wir Schritt-für-Schritt-Anweisungen zum Hinzufügen der Einträge (inklusive spezifischer Werte für jeden Eintrag) bereitstellen, finden Sie unter [Erstellen von DNS-Einträgen für Office 365](https://go.microsoft.com/fwlink/p/?LinkID=270173) oder, wenn Sie Office 365 verwenden, betrieben von 21Vianet, unter „Erstellen von DNS-Einträgen bei einem beliebigen Anbieter für Office 365, betrieben von 21Vianet". 
  
Wenn Office 365 die DNS-Einträge Ihrer Domäne verwaltet, müssen Sie zuerst die Einträge Ihres Domänen-Nameserver so ändern, dass sie auf Office 365 verweisen, und dann richtet Office 365 Ihre Office 365 Dienste ein. Anschließend werden Ihre DNS-Einträge von Office 365 verwaltet.
  
Wenn Ihre Domäne unter GoDaddy registriert ist, kann Office 365 bei GoDaddy die erforderlichen Einträge für Sie erstellen. 
  
Unabhängig davon, wo Ihre DNS-Einträge gehostet werden, können Sie die Einträge so einrichten, dass Ihre Domäne für die URL einer auf Office 365 oder bei einem anderen Hostinganbieter gehostete öffentliche Website verwendet wird. 
  
Office 365 überprüft Ihre DNS-Einträge proaktiv, um DNS-Probleme zu beheben. Wenn Ihre DNS-Einträge nicht mit den erwarteten übereinstimmen, erhalten Sie im Microsoft 365 Admin Center eine Benachrichtigung sowie Informationen, die Ihnen mitteilen, wie Sie die identifizierten Probleme beheben können.
  
Weitere Informationen finden Sie unter [Wie Office 365 DNS-Einträge verwaltet](https://go.microsoft.com/fwlink/p/?LinkID=270144) oder für Office 365, betrieben von 21Vianet, unter [Erstellen von DNS-Einträgen für Office 365, wenn Sie diese verwalten](http://go.microsoft.com/fwlink/?LinkID=817326&amp;clcid=0x409).
  
## <a name="sharing-a-domain"></a>Freigeben einer Domäne
<a name="BKMK_ManagingDNSRecords"> </a>

Sie können Pilot Office 365 mit einigen e-Mail-Adressen für eine Domäne in Office 365 und einige auf Ihrem vorherigen e-Mail-Anbieter. Dies wird nur für die Verwendung während eines Pilotprojekts von Office 365 empfohlen, da es zusätzliche Setupschritte erfordert und einige Einschränkungen für Office 365-Dienste aufweist. Weitere Informationen finden Sie unter:
  
- [Testen von Office 365 für Kleinunternehmen](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilot Office 365 für ein Großunternehmen (mit FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen
<a name="BKMK_ManagingDNSRecords"> </a>

Weitere Informationen zur Verfügbarkeit von Funktionen in Office 365-Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Office 365-Plattformdienstbeschreibung](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

