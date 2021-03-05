---
title: Microsoft Teams Dienstbeschreibung
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Microsoft Teams bietet Chat, Datei- und Datenzusammenarbeit, Audio- und Videoanrufe, umfangreiche Onlinebesprechungen, mobile Erfahrungen und umfassende Webkonferenzfunktionen.
ms.openlocfilehash: 55511f990f749fc8f39e84a9e0a7b1211b43bd53
ms.sourcegitcommit: 02dd535b01c4ca7b19b43188ddd1a1f02c01afb5
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2021
ms.locfileid: "50460204"
---
# <a name="microsoft-teams-service-description"></a>Microsoft Teams Dienstbeschreibung

Microsoft Teams ist der Hub für Teamarbeit in Microsoft 365. Der Teams-Dienst ermöglicht Chat, Audio- und Videoanrufe, umfangreiche Onlinebesprechungen, mobile Erfahrungen und umfassende Webkonferenzfunktionen. Darüber hinaus bietet Teams Features für die Zusammenarbeit und Erweiterbarkeit von Dateien und Daten und integriert sich in Microsoft 365 und andere Microsoft- und Partner-Apps.

Skype for Business Online wird am 31. Juli 2021 eingestellt, was am 30. Juli 2019 angekündigt wurde. [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) Microsoft Teams ist ein völlig neuer Dienst, der von Grund auf für die Cloud entwickelt wurde, indem Azure und andere Dienstneuheiten von Microsoft verwendet werden. Microsoft Teams baut auf Microsoft 365-Gruppen, Microsoft Graph und mit derselben Sicherheit, Compliance und Verwaltbarkeit auf Unternehmensebene wie der Rest von Office 365 auf. Teams nutzt identitäten, die in Azure Active Directory (Azure AD) gespeichert sind. Diese Dienste werden von Microsoft-Rechenzentren zugestellt und sind für Benutzer auf einer Vielzahl von Geräten innerhalb eines Unternehmensnetzwerks oder über das Internet zugänglich. Weitere Informationen finden Sie auf den [Postern zu Microsoft Teams IT-Architektur und Telefonielösungen.](https://docs.microsoft.com/microsoftteams/teams-architecture-solutions-posters)

Microsoft setzt sich weiterhin für die Sicherheit Ihrer Daten und die [Barrierefreiheit](https://www.microsoft.com/trust-center/compliance/accessibility) unserer Dienste ein. Weitere Informationen finden Sie im [Microsoft Trust Center und](https://www.microsoft.com/trust-center) im Office Accessibility [Center](https://support.office.com/article/Office-Accessibility-Center-Resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).

Ausführliche Planinformationen zu Abonnements, die Benutzer für Microsoft Teams ermöglichen, finden Sie in der [vollständigen Abonnementvergleichstabelle](https://go.microsoft.com/fwlink/?linkid=2139145). Weitere Office 365 in Government-Pläne finden Sie unter [Office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans). Office 365 G1 bis G5 umfassen Zugriff auf Teams-Features.

Ausführliche Anleitungen zur Implementierung von Produktfeatures finden Sie in der [Microsoft Teams Admin Documentation](https://docs.microsoft.com/MicrosoftTeams). In dieser Dienstbeschreibung werden die wichtigsten Unterschiede zwischen diensten beschrieben, die in den verschiedenen Cloudinstallationen bereitgestellt werden. Die Kernfunktionen von Microsoft Teams unterscheiden sich nicht zwischen den Abonnements. Die Verfügbarkeit von Compliancefunktionen hängt von Ihrem Abonnementlevel ab. Weitere Informationen finden Sie unter [Sicherheit und Compliance in Microsoft Teams](https://docs.microsoft.com/microsoftteams/security-compliance-overview). Eine detaillierte Liste der in den einzelnen Abonnements verfügbaren Features finden Sie unter [Microsoft 365- und Office 365-Plattformdienstbeschreibung](https://docs.microsoft.com/office365/servicedescriptions/office-365-platform-service-description/office-365-platform-service-description).

**Cloud-Sprachfunktionen:** Für Audiokonferenzen muss Ihre Organisation eine Lizenz für Audiokonferenzen erwerben und jedem Benutzer zuweisen, der Einwahlbesprechungen einrichten wird. Für Teams-Features, die Anrufpläne erfordern, benötigt jeder Benutzer ein Telefonsystem sowie einen nationalen oder nationalen und internationalen Anrufplan. Weitere Informationen finden Sie unter [Microsoft Teams-Add-On-Lizenzen](https://docs.microsoft.com/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing).

**Liveereignisse:** Dieses Angebot in Office 365 ersetzt die eingestellte Skype-Besprechungsübertragung. Funktionen für Liveereignisse stehen für Lizenzierungspläne zur Verfügung, wie im Stream-Dienst detailliert. Lesen Sie hier [die Microsoft Stream-Lizenzierungsdetails.](https://docs.microsoft.com/stream/license-overview) Auf den Live-Ereignisdienst kann über Stream, Yammer oder Microsoft Teams zugegriffen werden. Weitere Informationen zu Liveereignisfunktionen finden Sie unter [Liveereignisse in Microsoft 365 in Yammer, Microsoft Teams und Microsoft Stream](https://docs.microsoft.com/stream/live-event-m365).

Alle unterstützten Abonnementpläne sind für den Zugriff auf den Microsoft Teams-Webclient, Desktopclients und mobile Apps berechtigt.

Microsoft Teams ist nicht als eigenständiger Dienst verfügbar.

## <a name="feature-category-reference"></a>Referenz zu Featurekategorien

In dieser Tabelle wird die Verfügbarkeit von Microsoft Teams-Features über Lizenzierungspläne oder Cloudinstanzen hinweg aufgeführt. Es gelten bestimmte Vorbehalte. Weitere Informationen finden Sie in den Fußnoten. Diese Tabelle kann sich ohne vorherige Ankündigung ändern. Weitere Informationen finden Sie unter Microsoft 365 Message Center notifications for core service change messaging und in der [Referenzdokumentation zu Microsoft-Lizenzierungsbedingungen.](https://www.microsoft.com/licensing/product-licensing/products)<br><br>

| Feature | Kleinunternehmen | Enterprise-Pläne | GCC | GCC – Hoch | DOD | Education |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Chat  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|Teams  <br/> |Ja <br/> |Ja <br/> |Ja <br/> |Ja<sup>1</sup>  <br/> |Ja<sup>1</sup>  <br/> |Ja  <br/> |
|Kanäle – Standard  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|Kanäle – Privat  <br/> |Ja  <br/> |Ja<sup>2</sup>  <br/> |Ja <br/> |Nein  <br/> |Nein <br/> |Ja  <br/> |
|Besprechungen  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|Bildschirmfreigabe PowerPoint Audio/Video Desktop <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|Sprachanrufe  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja<sup>3</sup>  <br/> |Ja<sup>3</sup>  <br/> |Ja  <br/> |
|Audiokonferenz  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja<sup>3</sup>  <br/> |Ja<sup>3</sup>  <br/> |Ja  <br/> |
|Apps, Bots, & Connectors  <br/> |Ja  <br/> |Ja  <br/> |Ja<sup>5</sup>  <br/> |Ja<sup>5</sup>  <br/> |Ja<sup>4,5</sup>  <br/> |Ja  <br/> |
|Liveereignisse  <br/> |Nein  <br/> |Ja  <br/> |Ja  <br/> |Nr.<sup>6</sup>  <br/> |Nr.<sup>6</sup>  <br/> |Ja  <br/> |

> <sup>1</sup>  Microsoft Teams in GCC-High und DOD unterstützen 2500 Mitglieder in einem einzelnen Team.<br/>
> <sup>2</sup> Microsoft Planner ist derzeit nicht für den Zugriff in privaten Kanälen verfügbar.<br/>
> <sup>3</sup> Direktes Routing muss so konfiguriert sein, dass Voice- und Audiokonferenzen von Microsoft Teams in GCCH und DoD funktionieren.<br/>
> <sup>4</sup> Microsoft OneNote ist in DOD-Clouds nicht verfügbar.<br/>
> <sup>5</sup> Anwendungen von Drittanbietern und die Anwendungsveröffentlichung sind derzeit nicht in diesen Clouds verfügbar.<br/>
> <sup>6</sup> Liveereignisse sind derzeit nicht in GCC-High oder DOD verfügbar.<br/>

## <a name="next-steps"></a>Nächste Schritte

Beginnen Sie mit der Planung Ihrer Microsoft Teams-Bereitstellung, indem Sie die [technische Dokumentation zu Microsoft Teams besuchen.](https://aka.ms/SuccessWithTeams) Bleiben Sie auf dem neuesten Stand zu Den Features und Funktionen von Teams, indem Sie unserer Community beitreten [und unseren Microsoft Teams-Blog besuchen.](https://aka.ms/TeamsBlog)

Weitere Informationen zu Den Features von Teams nach Betriebssystemplattform finden Sie im Artikel zur Unterstützung von Teams nach [Plattform.](https://aka.ms/teamsfeaturesbyplatform)
