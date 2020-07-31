---
title: Domänen
ms.author: office365servicedesc
author: pamelaar
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
description: Wenn Sie eine Domäne hinzufügen, hilft Ihnen ein Schritt-für-Schritt-Assistent beim Hinzufügen von Benutzern und beim Konvertieren Ihrer e-Mail-Adressen und anderer Dienste in den Namen Ihres Unternehmens. Wenn Sie den Assistenten abgeschlossen haben, wird Ihre geschäftliche e-Mail-Adresse an Microsoft gesendet, anstatt zu Ihrem aktuellen e-Mail-Anbieter zu wechseln. Weitere Informationen finden Sie unter Hinzufügen von Benutzern und Domänen zu Microsoft. Wenn Sie Office 365, betrieben von 21Vianet verwenden, lesen Sie Prüfen der Domäne.
ms.openlocfilehash: 109dd15af75c8e3e04406a63c8868e010c12b9c5
ms.sourcegitcommit: 6a9c3c47e7526de046787ad0f02b9c008e541c34
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/31/2020
ms.locfileid: "46531218"
---
# <a name="domains"></a>Domänen

Wenn Sie eine Domäne hinzufügen, hilft Ihnen ein Schritt-für-Schritt-Assistent beim Hinzufügen von Benutzern und beim Konvertieren Ihrer e-Mail-Adressen und anderer Dienste in den Namen Ihres Unternehmens. Wenn Sie den Assistenten abgeschlossen haben, wird Ihre geschäftliche e-Mail-Adresse an Microsoft gesendet, anstatt zu Ihrem aktuellen e-Mail-Anbieter zu wechseln. Weitere Informationen finden Sie unter [Hinzufügen von Benutzern und Domänen zu Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Wenn Sie Office 365, betrieben von 21Vianet verwenden, lesen Sie [Prüfen der Domäne](https://docs.microsoft.com/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Benutzerdefinierte Domänen

Sie können Ihrem Abonnement bis zu 900 Domänen hinzufügen (einschließlich Unterdomänen). Sie können keine Domäne zu Microsoft 365 hinzufügen, die Sie bereits in einem anderen Microsoft Cloud-Dienst verwenden. Das bedeutet, dass Sie die gleiche Domäne nicht mehreren Abonnements hinzufügen können. Weitere Informationen finden Sie unter [häufig gestellte Fragen zu Domänen](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domänen der zweiten und dritten Ebene

Mit Office 365 Enterprise und Microsoft 365 apps for Business können Sie eine beliebige Domänenebene hinzufügen, einschließlich Domänen der dritten Ebene wie Marketing.contoso.com. Siehe [Hinzufügen von benutzerdefinierten Unterdomänen oder mehreren Domänen zu Microsoft](https://docs.microsoft.com/office365/admin/setup/domains-faq). Wenn Sie Office 365 betrieben von 21Vianet verwenden, lesen Sie [Hinzufügen von benutzerdefinierten Unterdomänen oder mehreren Domänen zu Office 365 betrieben von 21Vianet](https://docs.microsoft.com/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Domänenüberprüfung und Verwaltung von DNS-Einträgen

Mit Microsoft 365 können Sie alle Ihre DNS-Einträge bei Ihrem DNS-Hostinganbieter verwalten oder sich dafür entscheiden lassen, dass Microsoft die DNS-Einträge Ihrer Domäne für Sie einrichten und verwalten kann. Wenn Sie die Datensätze weiterhin verwalten, ändern Sie bestimmte Datensätze so, dass Sie nach Bedarf auf Microsoft-Dienste verweist. Eine Liste der Domänenregistrierungsstellen, für die schrittweise Anweisungen zum Hinzufügen der Datensätze, einschließlich der für jeden Datensatz zu verwendenden Werte, bereitgestellt werden, finden Sie unter [Create DNS Records](https://docs.microsoft.com/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) oder wenn Sie Office 365 operated by 21Vianet verwenden, finden Sie unter CREATE DNS Records on any Provider for Office 365 operated by 21Vianet. 
  
Wenn Microsoft die DNS-Einträge Ihrer Domäne für Sie verwaltet, müssen Sie zuerst die Namenservereinträge Ihrer Domäne so ändern, dass Sie auf Microsoft verweist, und Microsoft richtet ihre Dienste ein, und dann werden die DNS-Einträge Ihrer Domäne bei Microsoft verwaltet.
  
Wenn Ihre Domäne bei GoDaddy registriert ist, kann Microsoft die erforderlichen Einträge für Sie bei GoDaddy erstellen. 
  
Unabhängig davon, wo Ihre DNS-Einträge gehostet werden, können Sie die DNS-Einträge so einrichten, dass Sie Ihre Domäne für die URL einer öffentlichen Website, die auf Microsoft oder einem anderen Hostinganbieter gehostet wird, verwenden. 
  
Microsoft prüft proaktiv Ihre DNS-Einträge, um DNS-Probleme zu finden und zu beheben. Wenn Ihre DNS-Einträge nicht mit dem übereinstimmen, was von uns erwartet wird, erhalten Sie eine Benachrichtigung im Microsoft 365 Admin Center sowie Informationen dazu, wie Sie die möglichen Probleme beheben können, die identifiziert wurden.
  
Weitere Informationen finden Sie unter [How Microsoft Managed DNS Records](https://docs.microsoft.com/office365/admin/setup/domains-faq) oder, for Office 365 operated by 21Vianet, siehe [Erstellen von DNS-Einträgen für Office 365, wenn Sie Ihre DNS-Einträge verwalten](https://docs.microsoft.com/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Freigeben einer Domäne

Sie können einige e-Mail-Adressen für eine Domäne in Microsoft und einige in Ihrem vorherigen e-Mail-Anbieter pilotieren. Dies wird nur für die Verwendung während eines Pilotprojekts empfohlen, da es zusätzliche Installationsschritte erfordert und einige Einschränkungen für Microsoft-Dienste aufweist. Weitere Informationen finden Sie hier:
  
- [Pilot Microsoft 365 für kleine Unternehmen](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilot Microsoft 365 für ein großes Unternehmen (mit einer kurzphase)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Microsoft 365 for Business-Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Microsoft 365 und Office 365 Platform Service Description](office-365-platform-service-description.md).
  

