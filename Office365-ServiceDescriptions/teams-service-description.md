---
title: Microsoft Teams Dienstbeschreibung
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Erfahren Sie Microsoft Teams Service- und Featureverfügbarkeit in Microsoft 365 und Office 365 Plänen.
ms.openlocfilehash: 721c4bd99fd8f81e471ea79e6725c2d6c53d1791
ms.sourcegitcommit: c455501e86037b0f86e0afc9d6d6d04afdfd3442
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/28/2021
ms.locfileid: "52074486"
---
# <a name="microsoft-teams-service-description"></a>Microsoft Teams Dienstbeschreibung

Microsoft Teams ist der Hub für Teamarbeit in Microsoft 365. Der Teams-Dienst ermöglicht Instant Messaging, Audio- und Videoanrufe, umfangreiche Onlinebesprechungen, mobile Erfahrungen und umfassende Webkonferenzfunktionen. Darüber hinaus bietet Teams Funktionen für die Zusammenarbeit und Erweiterbarkeit von Dateien und Daten und integriert sich in Microsoft 365 und andere Microsoft- und Partner-Apps.

Skype for Business Online geht am 31. Juli 2021 in Rente, was am 30. Juli 2019 angekündigt wurde. [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) Microsoft Teams ist ein komplett neuer Dienst, der von Grund auf für die Cloud entwickelt wurde, indem Azure und andere Dienstneuheiten von Microsoft verwendet werden. Microsoft Teams baut auf Microsoft 365-Gruppen, Microsoft Graph und mit derselben Sicherheit, Compliance und Verwaltbarkeit auf Unternehmensebene auf wie die restlichen Office 365. Teams verwendet identitäten, die in Azure Active Directory (Azure AD) gespeichert sind. Diese Dienste werden von Microsoft-Rechenzentren zugestellt und sind für Benutzer auf einer Vielzahl von Geräten innerhalb eines Unternehmensnetzwerks oder über das Internet zugänglich. Weitere Informationen finden Sie auf den [postern Microsoft Teams it architecture and telephony solutions](/microsoftteams/teams-architecture-solutions-posters).

In dieser Dienstbeschreibung werden die wichtigsten Unterschiede zwischen diensten beschrieben, die in den verschiedenen Cloudinstallationen bereitgestellt werden. Microsoft Teams Kernfunktionen unterscheiden sich nicht zwischen den Abonnements. Die Verfügbarkeit von Compliancefunktionen hängt von Ihrem Abonnementlevel ab. Weitere Informationen zu Teams und Compliance finden Sie unter [Security and compliance in Microsoft Teams](/microsoftteams/security-compliance-overview).

Wenn Benutzer vollständig online migriert wurden, müssen sie sowohl über Teams- als auch Skype for Business Onlinelizenzen für vollständige Teams verfügen, auch wenn Skype for Business Online nicht verwendet wird.

## <a name="available-plans"></a>Verfügbare Pläne

Ausführliche Planinformationen zu Abonnements, die Benutzern Teams ermöglichen, finden Sie unter [Find the right Microsoft Teams for your business](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options). Weitere Details finden Sie in der [Vergleichstabelle für Microsoft-Lösungen.](https://go.microsoft.com/fwlink/?linkid=2139145)

Regierungspläne, die Teams unterstützen, umfassen Office 365 G1 bis G5. Weitere Informationen finden Sie unter [Office 365 Government Pläne](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans).

Alle unterstützten Abonnementpläne sind für den Zugriff auf den Microsoft Teams, Desktopclients und mobile Apps berechtigt.

Microsoft Teams ist nicht als eigenständiger Dienst verfügbar.

## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

In der folgenden Tabelle sind die wichtigsten Teams, die planübergreifend verfügbar sind. Es gelten bestimmte Vorbehalte. Weitere Informationen finden Sie in den Fußnoten. Diese Tabelle kann sich ohne vorherige Ankündigung ändern.

Weitere Informationen zu den features Teams betriebssystemplattform finden Sie [unter Teams features by platform](https://aka.ms/teamsfeaturesbyplatform).

Eine aktuelle, vollständige Liste der Teams-Features Microsoft 365 und Office 365 finden Sie unter Find [the right Microsoft Teams for your business](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options).<br><br>

| Feature | Pläne für kleine Unternehmen | Enterprise-Pläne | GCC | GCC – Hoch | DOD | Bildungspläne |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Chat  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|Teams  <br/> |Ja <br/> |Ja <br/> |Ja <br/> |Ja<sup>1</sup>  <br/> |Ja<sup>1</sup>  <br/> |Ja  <br/> |
|Kanäle – Standard  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|Kanäle – Privat  <br/> |Ja  <br/> |Ja<sup>2</sup>  <br/> |Ja <br/> |Nein  <br/> |Nein <br/> |Ja  <br/> |
|Besprechungen  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|Bildschirmfreigabe PowerPoint Audio/Video Desktop <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |
|Sprachanrufe  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja<sup>3</sup>  <br/> |Ja<sup>3</sup>  <br/> |Ja  <br/> |
|Audiokonferenz  <br/> |Ja  <br/> |Ja  <br/> |Ja  <br/> |Ja<sup>3</sup>  <br/> |Ja<sup>3</sup>  <br/> |Ja  <br/> |
|Apps, Bots, & Connectors  <br/> |Ja  <br/> |Ja  <br/> |Ja<sup>4</sup>  <br/> |Ja<sup>4</sup>  <br/> |Ja<sup>4</sup>  <br/> |Ja  <br/> |
|Liveereignisse  <br/> |Nein  <br/> |Ja  <br/> |Ja  <br/> |No<sup>5</sup>  <br/> |No<sup>5</sup>  <br/> |Ja  <br/> |

<sup>1</sup> Microsoft Teams in GCC-High und DOD unterstützen 2500 Mitglieder in einem einzelnen Team.<br/>
<sup>2</sup> Microsoft Planner ist derzeit nicht für den Zugriff in privaten Kanälen verfügbar.<br/>
<sup>3</sup> Direktes Routing muss so konfiguriert sein, Microsoft Teams sprach- und audiokonferenzen in GCCH und DoD funktionieren.<br/>
<sup>4</sup> Anwendungen von Drittanbietern und die Anwendungsveröffentlichung sind derzeit nicht in diesen Clouds verfügbar. Connectors werden in GCCH und DOD nicht unterstützt.<br/>
<sup>5</sup> Liveereignisse sind derzeit nicht in GCC-High oder DOD verfügbar.<br/>

### <a name="cloud-voice-features"></a>Cloud-Sprachfeatures

Für Audiokonferenzen muss Ihre Organisation eine Lizenz für Audiokonferenzen erwerben und jedem Benutzer zuweisen, der Einwahlbesprechungen eingerichtet hat. Für Teams, die Anrufpläne erfordern, benötigt jeder Benutzer ein Telefonsystem und einen nationalen oder nationalen und internationalen Anrufplan. Weitere Informationen finden Sie unter [Microsoft Teams add-on licenses](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing).

### <a name="live-events"></a>Liveereignisse

Dieses Angebot in Office 365 ersetzt die eingestellte Skype-Besprechung Broadcast. Funktionen für Liveereignisse stehen für Lizenzierungspläne zur Verfügung, wie im Stream-Dienst detailliert. Weitere Informationen finden Sie in der [Microsoft Stream-Lizenzierungsübersicht](/stream/license-overview). Auf den Liveereignissedienst kann über Stream, Yammer oder Microsoft Teams. Weitere Informationen zu Liveereignisfunktionen finden Sie unter [Liveereignisse in Microsoft 365 in Yammer, Microsoft Teams und Microsoft Stream](/stream/live-event-m365). Weitere Informationen zur Planung von Liveereignissen, einschließlich Lizenzanforderungen, finden Sie unter [Plan for live events in Microsoft Teams](/microsoftteams/teams-live-events/plan-for-teams-live-events).

## <a name="learn-more"></a>Weitere Informationen

Weitere Informationen zu Teams finden Sie in den folgenden Ressourcen:
 
- [Microsoft Teams-Administratordokumentation](/MicrosoftTeams)
- [Microsoft Teams Tech Community](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Microsoft Teams Blog](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Lizenzierungsbedingungen

Lizenzbedingungen für Produkte und Dienste, die über Kommerzielle Volumenlizenzprogramme von Microsoft erworben wurden, finden Sie auf der [Website "Produktbedingungen".](https://www.microsoft.com/licensing/terms/) 

### <a name="messaging"></a>Messaging 

Besuchen Sie das Nachrichtencenter, um über bevorstehende Änderungen, einschließlich neuer und geänderter Features, geplanter Wartung oder anderer wichtiger Ankündigungen, auf dem Laufenden zu bleiben. Weitere Informationen finden Sie unter [Message Center](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Barrierefreiheit

Microsoft setzt sich weiterhin für die Sicherheit Ihrer Daten und die Barrierefreiheit unserer Dienste ein. Weitere Informationen finden Sie im [Microsoft Trust Center](https://www.microsoft.com/trust-center) und im Office Accessibility [Center](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
