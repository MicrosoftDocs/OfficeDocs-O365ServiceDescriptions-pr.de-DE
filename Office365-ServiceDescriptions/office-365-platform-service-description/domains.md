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
description: Wenn Sie eine Domäne hinzufügen, hilft Ihnen ein schrittweiser Assistent, Benutzer hinzuzufügen und Ihre E-Mail-Adressen und anderen Dienste in Ihren Geschäftsnamen zu konvertieren. Wenn Sie den Assistenten abschließen, wird Ihre Geschäfts-E-Mail an Microsoft gesendet, anstatt zu Ihrem aktuellen E-Mail-Anbieter zu wechseln. Weitere Informationen finden Sie unter Add your users and domains to Microsoft. Wenn Sie Office 365, betrieben von 21Vianet verwenden, lesen Sie Prüfen der Domäne.
ms.openlocfilehash: 57df3e7fb22e8a576099432b8cdc7c84a8462bad
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51172990"
---
# <a name="domains"></a>Domänen

Wenn Sie eine Domäne hinzufügen, hilft Ihnen ein schrittweiser Assistent, Benutzer hinzuzufügen und Ihre E-Mail-Adressen und anderen Dienste in Ihren Geschäftsnamen zu konvertieren. Wenn Sie den Assistenten abschließen, wird Ihre Geschäfts-E-Mail an Microsoft gesendet, anstatt zu Ihrem aktuellen E-Mail-Anbieter zu wechseln. Weitere Informationen finden Sie unter [Add your users and domains to Microsoft](https://support.office.com/article/6383f56d-3d09-4dcb-9b41-b5f5a5efd611). Wenn Sie Office 365, betrieben von 21Vianet verwenden, lesen Sie [Prüfen der Domäne](/office365/admin/setup/add-domain).
  
## <a name="custom-domains"></a>Benutzerdefinierte Domänen

Sie können Ihrem Abonnement bis zu 900 Domänen hinzufügen (einschließlich Unterdomänen). Sie können Microsoft 365 keine Domäne hinzufügen, die Sie bereits in einem anderen Microsoft-Clouddienst verwenden. Das bedeutet, dass Sie mehreren Abonnements nicht dieselbe Domäne hinzufügen können. Weitere Informationen finden Sie unter [Häufig gestellte Fragen zu Domänen](https://support.office.com/article/Domains-FAQ-1272bad0-4bd4-4796-8005-67d6fb3afc5a).
  
### <a name="second-and-third-level-domains"></a>Domänen der zweiten und dritten Ebene

Mit Office 365 Enterprise und Microsoft 365 Apps for Business können Sie beliebige Domänen auf ebener Ebene hinzufügen, einschließlich Domänen der dritten Ebene wie marketing.contoso.com. Weitere Informationen finden Sie unter Hinzufügen von [benutzerdefinierten Unterdomänen oder mehreren Domänen zu Microsoft](/office365/admin/setup/domains-faq). Wenn Sie Office 365 verwenden, das von 21Vianet betrieben wird, lesen Sie Hinzufügen benutzerdefinierter Unterdomänen oder mehrerer Domänen zu [Office 365, betrieben von 21Vianet](/office365/admin/setup/domains-faq).
  
## <a name="domain-verification-and-managing-dns-records"></a>Domänenüberprüfung und Verwaltung von DNS-Einträgen

Mit Microsoft 365 können Sie alle Ihre DNS-Einträge bei Ihrem DNS-Hostinganbieter verwalten oder sich dafür entscheiden, dass Microsoft die DNS-Einträge Ihrer Domäne für Sie einrichten und verwalten lässt. Wenn Sie die Datensätze weiterhin verwalten, ändern Sie bestimmte Datensätze so, dass sie bei Bedarf auf Microsoft-Dienste verweisen. Eine Liste der Domänenregistrierungsstellen, für die wir schrittweise Anweisungen zum Hinzufügen der Datensätze bereitstellen, einschließlich der für jeden Datensatz zu verwendenden spezifischen Werte, finden Sie unter [Erstellen](/office365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider) von DNS-Einträgen oder, wenn Sie Office 365 verwenden, betrieben von 21Vianet, unter Erstellen von DNS-Einträgen bei einem beliebigen Anbieter für Office 365, betrieben von 21Vianet. 
  
Wenn Microsoft die DNS-Einträge Ihrer Domäne für Sie verwaltet, müssen Sie zunächst die Namenservereinträge Ihrer Domäne so ändern, dass sie auf Microsoft verweisen, und Dann richtet Microsoft Ihre Dienste ein, und dann werden die DNS-Einträge Ihrer Domäne bei Microsoft verwaltet.
  
Wenn Ihre Domäne bei GoDaddy registriert ist, kann Microsoft die erforderlichen Datensätze für Sie bei GoDaddy erstellen. 
  
Unabhängig davon, wo Ihre DNS-Einträge gehostet werden, können Sie die DNS-Einträge so einrichten, dass Ihre Domäne für die URL für eine öffentliche Website verwendet wird, die auf Microsoft oder mit einem anderen Hostinganbieter gehostet wird. 
  
Microsoft überprüft Ihre DNS-Einträge proaktiv, um DNS-Probleme zu finden und zu beheben. Wenn Ihre DNS-Einträge nicht mit dem übereinstimmen, was wir erwarten, erhalten Sie eine Benachrichtigung im Microsoft 365 Admin Center, zusammen mit Informationen, die Ihnen zeigen, wie Sie die möglichen Probleme beheben können, die identifiziert wurden.
  
Weitere Informationen finden Sie unter [How Microsoft manages DNS records](/office365/admin/setup/domains-faq) oder, for Office 365 operated by 21Vianet, see Create DNS records for Office [365 when you manage your DNS records](/office365/admin/services-in-china/create-dns-records-when-you-manage-your-dns-records).
  
## <a name="sharing-a-domain"></a>Freigeben einer Domäne

Sie können einige E-Mail-Adressen für eine Domäne bei Microsoft und einige für Ihren vorherigen E-Mail-Anbieter piloten. Dies wird nur für die Verwendung während eines Pilotprojekts empfohlen, da zusätzliche Setupschritte erforderlich sind und einige Einschränkungen für Microsoft-Dienste gelten. Weitere Informationen finden Sie unter:
  
- [Pilot microsoft 365 für ein kleines Unternehmen](https://support.office.com/article/39cee536-6a03-40cf-b9c1-f301bb6001d7)
    
- [Pilot microsoft 365 für ein großes Unternehmen (mit FastTrack)](https://fasttrack.office.com/onboard)
    
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Funktionsverfügbarkeit in Microsoft 365 Business-Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Microsoft 365- und Office 365-Plattformdienstbeschreibung](office-365-platform-service-description.md).
