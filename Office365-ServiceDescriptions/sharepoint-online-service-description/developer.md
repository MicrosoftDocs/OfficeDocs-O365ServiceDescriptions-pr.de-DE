---
title: Entwickler
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- sharepoint-online-developer-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 415c9536-ae70-4d4b-b481-5255cb03cc32
description: SharePoint Online ist eine Sammlung von webbasierten Tools und Technologien, mit denen Ihre Organisation digitale Informationen speichern, freigeben und verwalten kann. Dieser gehostete Dienst setzt auf Microsoft SharePoint Server 2013 auf und eignet sich ideal für die Arbeit an Projekten, das Speichern von Daten und Dokumenten an einem zentralen Ort und die Freigabe von Informationen für andere Benutzer. Die folgenden Features unterstützen Entwickler beim Entwickeln von Apps und Lösungen zur Erweiterung der Funktionalität von SharePoint.
ms.openlocfilehash: 52b1b15dd098b6dd40a531cb5b462a7fff8b69f7
ms.sourcegitcommit: 05458701350d269dce45c9a0812d67d653c52621
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/25/2019
ms.locfileid: "37726252"
---
# <a name="developer"></a>Entwickler

SharePoint Online ist eine Sammlung von webbasierten Tools und Technologien, mit denen Ihre Organisation digitale Informationen speichern, freigeben und verwalten kann. Dieser gehostete Dienst setzt auf Microsoft SharePoint Server 2013 auf und eignet sich ideal für die Arbeit an Projekten, das Speichern von Daten und Dokumenten an einem zentralen Ort und die Freigabe von Informationen für andere Benutzer. Die folgenden Features unterstützen Entwickler beim Entwickeln von Apps und Lösungen zur Erweiterung der Funktionalität von SharePoint.
  
## <a name="app-catalog-sharepoint"></a>App-Katalog (SharePoint)

Wenn Sie Ihre Apps in einem internen Unternehmenskatalog veröffentlichen, der in Ihrer SharePoint-Bereitstellung gehostet wird, machen Sie sie für Benutzer verfügbar, die auf diese SharePoint-Bereitstellung zugreifen können. Weitere Informationen finden Sie unter [Veröffentlichen von Apps für Office und SharePoint](https://docs.microsoft.com/office/dev/store/submit-to-the-office-store).
  
## <a name="app-deployment-cloud-hosted-apps"></a>App-Bereitstellung: in der Cloud gehostete Apps

In der Cloud gehostete Apps für SharePoint umfassen mindestens eine Remotekomponente und können auch in SharePoint gehostete Komponenten umfassen. Weitere Informationen finden Sie unter [Hostingoptionen für Apps für SharePoint](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in). 
  
## <a name="app-deployment-sharepoint-hosted-apps"></a>App-Bereitstellung: von SharePoint gehostete Apps

In von SharePoint gehosteten Apps können Sie häufig verwendete SharePoint-Artefakte wie Listen und Webparts wieder verwenden. Bei diesem Ansatz können Sie nur JavaScript und keinen serverseitigen Code verwenden. Weitere Informationen finden Sie unter [Hostingoptionen für Apps für SharePoint](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/choose-patterns-for-developing-and-hosting-your-sharepoint-add-in).
  
## <a name="app-management-service"></a>App-Verwaltungsdienst

Die Datenbank des App-Verwaltungsdiensts speichert Lizenzinformationen sämtlicher Apps für SharePoint. 
  
## <a name="bcs-app-scoped-external-content-types-ects"></a>BCS: externe Inhaltstypen auf App-Ebene (ECTS)

Durch das Hinzufügen des neuen App-Modells in SharePoint können Business Connectivity Services (BCS) nun externe Inhaltstypen auf App-Ebene anstatt auf Farmebene bereichern. Dies gibt großen Spielraum für App-Entwickler, da externe Daten in ihren apps verwendet werden können. Erfahren Sie mehr über [App-bezogene externe Inhaltstypen](https://docs.microsoft.com/sharepoint/dev/general-development/add-in-scoped-external-content-types-in-sharepoint).
  
## <a name="bcs-business-data-web-parts"></a>BCS: Geschäftsdaten-Webparts

Geschäftsdaten-Webparts sind spezielle Webparts, die mit externen Daten arbeiten. Sie werden wie SharePoint-Standardwebparts verwendet, basieren jedoch auf externen Inhaltstypen, die XML-Beschreibungen der Verbindungen mit externen Daten enthalten. 
  
## <a name="bcs-external-list"></a>BCS: externe Liste

Eine externe Liste ist eine spezielle SharePoint-Liste, die Daten aus einer externen Datenquelle anzeigt. Sie basiert auf einem externen Inhaltstyp, der die Datenquelle beschreibt, und ermöglicht Benutzern das Arbeiten mit Daten über eine gewohnte SharePoint-Benutzeroberfläche. Weitere Informationen finden Sie unter [Externe Inhaltstypen](https://docs.microsoft.com/SharePoint/administration/deploy-an-on-premises-solution). 
  
## <a name="bcs-odata-connector"></a>BCS: OData-Connector

Der OData-Connector ist neu in SharePoint. Es ermöglicht Business Connectivity Services (BCS), einen Rest-OData-Endpunkt als Datenquelle für externe Listen, Geschäftsdaten-Webparts und Benutzeroberflächen zu verwenden.
  
## <a name="bcs-rich-client-integration"></a>BCS: Rich Client-Integration

Nicht verfügbar für SharePoint Online-Kunden. Business Connectivity Services (BCS) verwendet einen zusätzlichen Client sowie serverseitige Architektur, sodass Office-Clients wie Outlook und Excel direkt mit externen Daten arbeiten können, die über externe Inhaltstypen in SharePoint verfügbar gemacht wurden. Weitere Informationen finden Sie unter [Business Connectivity Services-Clientlaufzeit](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2010/ee559310(v=office.14)).
  
## <a name="client-object-model-om"></a>Client Objektmodell (OM)

SharePoint 2013 bietet drei Clientobjektmodelle für verwalteten Code: .NET, Silverlight und mobil. Darüber hinaus enthält SharePoint ein JavaScript-Clientobjektmodell. Weitere Informationen finden Sie unter [Auswählen des richtigen API-Satzes in SharePoint-2013](https://docs.microsoft.com/sharepoint/dev/general-development/choose-the-right-api-set-in-sharepoint).
  
## <a name="custom-site-provisioning-page"></a>Seite für die benutzerdefinierte Website Einrichtung

Nicht verfügbar für SharePoint Online-Kunden. SharePoint Server 2013-Kunden können Ihren Benutzern die Möglichkeit bieten, schnell und einfach ihre Websiteabfragen auszuführen und ihre Websites schnell nutzen zu können.
  
## <a name="developer-site"></a>Entwickler Website

Verwenden Sie eine Office 365 Entwickler Website als Entwicklungs-und Testumgebung, um die Einrichtungszeit zu verkürzen und mit dem Erstellen, testen und Bereitstellen Ihrer Apps für SharePoint zu beginnen. Erfahren Sie mehr über [die Anmeldung für eine Office 365 Entwickler Website](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/create-a-developer-site-on-an-existing-office-365-subscription).
  
## <a name="forms-based-applications"></a>Formularbasierte Anwendungen

Eine Formularansicht ist eine Ansicht, die Steuerelemente enthält. Eine formularbasierte Anwendung ermöglicht dem Benutzer das Erstellen und Verwenden eines oder mehrerer Formulare in der Anwendung. Erfahren Sie mehr über [formularbasierte Anwendungen](https://docs.microsoft.com/previous-versions/visualstudio/visual-studio-6.0/aa733955(v=vs.60)).
  
## <a name="full-trust-solutions"></a>Voll vertrauenswürdige Lösungen

Nicht verfügbar für SharePoint Online-Kunden. SharePoint Server 2013 Kunden können voll vertrauenswürdige Lösungen erstellen (auch als Farmlösungen bezeichnet). Im Gegensatz zu Apps für SharePoint enthalten Farmlösungen Code, der auf SharePoint-Servern bereitgestellt wird und Aufrufe des SharePoint-Serverobjektmodells ausführen kann. Diese Assemblys werden immer mit voller Vertrauenswürdigkeit ausgeführt. Farmlösungen sollten für Anpassungen von SharePoint-Verwaltungsfunktionen wie benutzerdefinierte Zeitgeberaufträge, benutzerdefinierte Windows PowerShell-Cmdlets und Erweiterungen der Zentralverwaltung verwendet werden. Weitere Informationen finden Sie unter [Erstellen von Farmlösungen in SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/general-development/build-farm-solutions-in-sharepoint).
  
## <a name="infopath-forms-services"></a>InfoPath Forms Services

Der Forms Service bietet in SharePoint basierend auf in InfoPath entworfenen Formularvorlagen eine Erfahrung im Webbrowser-Formular Füllung. Weitere Informationen finden Sie unter [InfoPath Forms Services](https://docs.microsoft.com/previous-versions/office/developer/sharepoint-2007/ms540731(v=office.12))
  
## <a name="javascript-object-model"></a>JavaScript-Objektmodell

SharePoint bietet ein JavaScript-Objektmodell zur Verwendung in Inlineskripts oder in gesonderten JS-Dateien. Es umfasst die gleiche Funktionalität wie die Clientobjektmodelle von .NET Framework und Silverlight. Das JavaScript-Objektmodell ist nützlich, um benutzerdefinierten SharePoint-Code in eine App einzuschließen. Außerdem können Webentwickler ihre vorhandenen JavaScript-Fähigkeiten verwenden, um SharePoint-Anwendungen mit minimaler Lernkurve zu erstellen. Weitere Informationen finden Sie unter [JavaScript-API-Verweis für SharePoint 2013](https://docs.microsoft.com/previous-versions/office/sharepoint-visio/jj193034(v=office.15)).
  
## <a name="remote-event-receiver"></a>Remote Ereignisempfänger

In einer App für SharePoint können Entwickler zur Behandlung von Ereignissen Remoteereignisempfänger sowie App-Ereignisempfänger erstellen. Remoteereignisempfänger behandeln Ereignisse, die bei Elementen in Apps auftreten, z. B. einer Liste, einem Listenelement oder einer Website. Weitere Informationen finden Sie unter [Behandeln von Ereignissen in Apps für SharePoint](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/handle-events-in-sharepoint-add-ins). 
  
## <a name="rest-apis"></a>REST-APIs

SharePoint 2013 bietet eine Implementierung eines REST-Webdiensts (Representational State Transfer), der CRUD-Vorgänge auf SharePoint-Listendaten über das OData-Protokoll ausführt. Verwenden Sie dieses Feature für den Zugriff auf SharePoint-Daten über Client-Technologien, die nicht JavaScript verwenden und nicht auf den Plattformen .NET Framework oder Microsoft Silverlight basieren. Weitere Informationen finden Sie unter [Programmierung unter Verwendung des SharePoint 2013-REST-Diensts](https://docs.microsoft.com/sharepoint/dev/sp-add-ins/use-odata-query-operations-in-sharepoint-rest-requests).
  
## <a name="sharepoint-design-manager"></a>SharePoint Design Manager

Der Entwurfs-Manager ermöglicht eine schrittweise Herangehensweise für das Erstellen von Designobjekten, die Sie für das Branding von Websites verwenden können. Laden Sie zunächst die Designobjekte hoch (Bilder, HTML, CSS usw.), und erstellen Sie dann Ihre Masterseiten und Seitenlayouts. Weitere Informationen finden Sie unter [Websiteentwicklung in SharePoint 2013](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-with-sharepoint-site-development).
  
## <a name="sharepoint-designer-2013"></a>SharePoint Designer 2013

Mit SharePoint Designer können fortgeschrittene Benutzer und Entwickler schnell SharePoint-Lösungen als Reaktion auf geschäftliche Anforderungen erstellen. Weitere Informationen finden Sie unter [SharePoint Designer für Entwickler](https://go.microsoft.com/fwlink/?LinkId=271294).
  
## <a name="sharepoint-framework"></a>SharePoint Framework

Das SharePoint Framework (SPFx) ist ein Seiten- und Webpart-Modell, das vollständige Unterstützung für die clientseitige SharePoint-Entwicklung, einfache Integration in SharePoint-Daten und Unterstützung für Open-Source-Tools bietet. Erfahren Sie mehr über das [SharePoint-Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview).
  
## <a name="sharepoint-2010-workflows-out-of-the-box"></a>SharePoint 2010-Workflows (sofort einsetzbar)

Verwenden Sie in SharePoint enthaltene, sofort einsetzbare Workflows zum Modellieren allgemeiner Geschäftsprozesse.
  
## <a name="sharepoint-2013-and-sharepoint-2016-workflows"></a>SharePoint 2013- und SharePoint 2016-Workflows

SharePoint 2013-und SharePoint 2016-Workflows werden von Windows Workflow Foundation 4 (WF) angetrieben, das in früheren Versionen erheblich neu gestaltet wurde. Das vielleicht bekannteste Feature der neuen Workflowinfrastruktur ist die Einführung von Azure als Host für die Workflowausführung. Erfahren Sie mehr über Neuigkeiten [in Workflows für SharePoint](https://docs.microsoft.com/sharepoint/dev/general-development/what-s-new-in-workflows-for-sharepoint).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [SharePoint Online Service Description](sharepoint-online-service-description.md).
  

