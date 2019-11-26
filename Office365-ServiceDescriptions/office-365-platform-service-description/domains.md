---
title: Domänen
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-domains
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 5c374309-8016-4f18-8f2a-bceeb863ca67
description: Wenn Sie eine Domäne hinzufügen, hilft Ihnen ein Assistent Schritt für Schritt beim Hinzufügen von Benutzern und beim Umstellen Ihrer Office 365-E-Mail-Adressen und anderer Dienste auf den Namen des Unternehmens. Nach dem Ausführen des Assistenten gehen Ihre geschäftlichen E-Mails an Office 365 statt an Ihren aktuellen E-Mail-Anbieter. Weitere Informationen finden Sie unter Hinzufügen Ihrer Benutzer und Domänen zu Office 365. Wenn Sie Office 365 betrieben von 21Vianet verwenden, finden Sie weitere Informationen unter Überprüfen Ihrer Domäne.
ms.openlocfilehash: a1038e0ff6db0dc5def4fd5d50bd5798e45fde2c
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262788"
---
# <a name="domains"></a>Domänen

Wenn Sie eine Domäne hinzufügen, hilft Ihnen ein Assistent Schritt für Schritt beim Hinzufügen von Benutzern und beim Umstellen Ihrer Office 365-E-Mail-Adressen und anderer Dienste auf den Namen des Unternehmens. Nach dem Ausführen des Assistenten gehen Ihre geschäftlichen E-Mails an Office 365 statt an Ihren aktuellen E-Mail-Anbieter. Weitere Informationen finden Sie unter [Hinzufügen Ihrer Benutzer und Domänen zu Office 365](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Wenn Sie Office 365, betrieben von 21Vianet verwenden, lesen Sie [Prüfen der Domäne](https://docs.microsoft.com/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Benutzerdefinierte Domänen

Sie können Ihrem Office 365-Abonnement bis zu 900 Domänen hinzufügen. Wenn Sie allerdings eine Domäne bereits in einem anderen Cloud-Dienst von Microsoft verwenden, können Sie diese nicht zu Office 365 hinzufügen. Das bedeutet, dass Sie eine Domäne nicht zu mehreren Office 365-Abonnements gleichzeitig hinzufügen können. Weitere Informationen finden Sie unter [häufig gestellte Fragen zu Domänen](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domänen der zweiten und dritten Ebene

Mit Office 365 Enterprise und Office 365 Business können Sie jede beliebige Domänenebene hinzufügen, einschließlich Domänen der dritten Ebene, z. B. „marketing.contoso.com". Informationen dazu finden Sie unter [Hinzufügen benutzerdefinierter Unterdomänen oder mehrerer Domänen zu Office 365](https://docs.microsoft.com/office365/admin/setup/domains-faq). Wenn Sie Office 365 verwenden, betrieben von 21Vianet, lesen Sie [Hinzufügen benutzerdefinierter Unterdomänen oder mehrerer Domänen zu Office 365, betrieben von 21Vianet](https://docs.microsoft.com/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Domänenüberprüfung und Verwaltung von DNS-Einträgen

Mit Office 365 können Sie Ihre DNS-Einträge bei Ihrem DNS-Hostinganbieter verwalten oder Office 365 einrichten und die DNS-Einträge Ihrer Domäne für Sie verwalten lassen. Wenn Sie die Datensätze weiterhin verwalten, ändern Sie bestimmte Datensätze bei Bedarf, sodass sie auf Office 365 Dienste verweisen. Eine Liste der Domänenregistrierungsstellen, für die wir Schritt-für-Schritt-Anweisungen zum Hinzufügen der Einträge (inklusive spezifischer Werte für jeden Eintrag) bereitstellen, finden Sie unter [Erstellen von DNS-Einträgen für Office 365](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) oder, wenn Sie Office 365 verwenden, betrieben von 21Vianet, unter „Erstellen von DNS-Einträgen bei einem beliebigen Anbieter für Office 365, betrieben von 21Vianet". 
  
Wenn Office 365 die DNS-Einträge Ihrer Domäne verwaltet, müssen Sie zuerst die Einträge Ihres Domänen-Nameserver so ändern, dass sie auf Office 365 verweisen, und dann richtet Office 365 Ihre Office 365 Dienste ein. Anschließend werden Ihre DNS-Einträge von Office 365 verwaltet.
  
Wenn Ihre Domäne unter GoDaddy registriert ist, kann Office 365 bei GoDaddy die erforderlichen Einträge für Sie erstellen. 
  
Unabhängig davon, wo Ihre DNS-Einträge gehostet werden, können Sie die Einträge so einrichten, dass Ihre Domäne für die URL einer auf Office 365 oder bei einem anderen Hostinganbieter gehostete öffentliche Website verwendet wird. 
  
Office 365 überprüft Ihre DNS-Datensätze proaktiv, um DNS-Probleme zu finden und bei der Problembehebung zu helfen. Wenn Ihre DNS-Einträge nicht mit dem übereinstimmen, was von uns erwartet wird, erhalten Sie eine Benachrichtigung im Microsoft 365 Admin Center sowie Informationen dazu, wie Sie die möglichen Probleme beheben können, die identifiziert wurden.
  
Weitere Informationen finden Sie unter [Wie Office 365 DNS-Einträge verwaltet](https://docs.microsoft.com/office365/admin/setup/domains-faq) oder für Office 365, betrieben von 21Vianet, unter [Erstellen von DNS-Einträgen für Office 365, wenn Sie diese verwalten](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Freigeben einer Domäne

Sie können Office 365 über einige E-Mail-Adressen für eine Domäne bei Office 365 und einige E-Mail-Adressen bei Ihrem vorherigen E-Mail-Anbieter steuern. Dies wird nur für die Verwendung während eines Pilotprojekts von Office 365 empfohlen, da es zusätzliche Installationsschritte erfordert und einige Einschränkungen für Office 365 Dienste aufweist. Weitere Informationen finden Sie unter:
  
- [Testen von Office 365 für Kleinunternehmen](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilot Office 365 für ein Großunternehmen (mit FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Office 365 Platform Service Description](office-365-platform-service-description.md).
  

