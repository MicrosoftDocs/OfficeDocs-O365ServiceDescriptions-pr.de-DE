---
title: Microsoft 365-Lizenzierungsleitfas für & Compliance
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Dieser Artikel enthält Lizenzierungsleitfaden für Microsoft 365-Compliance, um potenzielle Dienstunterbrechungen aufgrund eines nicht lizenzierten Zugriffs zu vermeiden.
ms.openlocfilehash: 0971b241d486180bd406c8472fa1a2dbcb9cb873
ms.sourcegitcommit: 50179fef4616ffa270d7e766d70e9c9f1379d824
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/15/2021
ms.locfileid: "49871138"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Microsoft 365-Lizenzierungsleitfas für & Compliance

Für die Zwecke dieses Artikels ist ein Dienst auf Mandantenebene ein Onlinedienst, der, wenn er für einen beliebigen Benutzer im Mandanten erworben wird (eigenständig oder als Teil von &mdash; Office 365- oder Microsoft 365-Plänen), für alle Benutzer im Mandanten teilweise oder vollständig aktiviert &mdash; wird. Obwohl einige nicht lizenzierte Benutzer technisch möglicherweise auf den Dienst zugreifen können, ist für jeden Benutzer, der von dem Dienst profitieren möchte, eine Lizenz erforderlich.

> [!NOTE]
> Einige Mandantendienste sind derzeit nicht in der Lage, die Vorteile auf bestimmte Benutzer zu beschränken. Es sollten Anstrengungen unternommen werden, um die Dienstvorteile auf lizenzierte Benutzer zu beschränken. Dies hilft Ihnen, potenzielle Dienstunterbrechungen in Ihrer Organisation zu vermeiden, sobald Zielfunktionen verfügbar sind.

Laden Sie den detaillierten Microsoft 365-Compliancelizenzierungsvergleich herunter, um die Optionen für die Lizenzierung Ihrer Benutzer anzuzeigen, um von den Microsoft 365-Compliancefeatures ab dem 1. April 2020 zu profitieren. [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection ist ein Feature des Azure Active Directory Premium P2-Plans, mit dem Sie potenzielle Sicherheitsrisiken erkennen können, die sich auf die IdentitätEn Ihrer Organisation negativ auf die Identitäten Ihrer Organisation ausdingen, automatisierte Antworten auf erkannte verdächtige Aktionen im Zusammenhang mit den Identitäten Ihrer Organisation konfigurieren und verdächtige Vorfälle untersuchen und entsprechende Maßnahmen ergreifen können, um sie zu beheben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

SecOps-Analysten und Sicherheitsexperten profitieren von konsolidierten Ansichten gekennzeichneter Benutzer und Risikoereignissen basierend auf Machine Learning-Algorithmen. Endbenutzer profitieren von dem automatischen Schutz, der durch risikobasierten bedingten Zugriff bereitgestellt wird, und von der verbesserten Sicherheit, die durch die Ausnutzen von Sicherheitsrisiken bereitgestellt wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Azure Active Directory Premium Plan 2 bieten benutzern die Rechte, von Azure Active Directory Identity Protection zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Azure AD Identity Protection-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Weitere Informationen zu Azure AD Identity Protection finden Sie unter [Was ist Identity Protection?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können den Umfang von Azure AD Identity Protection festlegen, indem sie Risikorichtlinien zuweisen, die die Ebene für kennwortzurücksetzungen definieren und nur lizenzierten Benutzern den Zugriff ermöglichen. Anweisungen zum Umfang von Azure AD Identity Protection-Bereitstellungen finden Sie unter Konfigurieren und [Aktivieren von Risikorichtlinien.](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Identity Governance

Azure Active Directory Identity Governance ermöglicht es Ihnen, die Anforderungen Ihrer Organisation an Sicherheit und Mitarbeiterproduktivität mit den richtigen Prozessen und Sichtbarkeit zu abgleichen. Sie verwendet Berechtigungsverwaltung, Zugriffsüberprüfungen, Privileged Identity Management und Nutzungsbedingungenrichtlinien, um sicherzustellen, dass die richtigen Personen den richtigen Zugriff auf die richtigen Ressourcen haben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Azure Active Directory Identity Governance erhöht die Produktivität der Benutzer, indem der Zugriff auf Apps, Gruppen und Microsoft Teams in einem einzigen Zugriffspaket einfacher an die Benutzer gesendet werden kann. Benutzer können auch als genehmigende Personen ohne Beteiligung von Administratoren konfiguriert werden. Bei Zugriffsüberprüfungen können Benutzer Mitgliedschaften von Gruppen mit intelligenten Empfehlungen überprüfen, um in regelmäßigen Abständen Maßnahmen zu ergreifen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Azure Active Directory Premium Plan 2 bieten benutzern die Rechte, von Azure Active Directory Identity Governance zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Azure AD Identity Governance-Features sind auf Mandantenebene aktiviert, werden jedoch pro Benutzer implementiert. Informationen zur Azure AD Identity Governance finden Sie unter [Was ist Azure AD Identity Governance?](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können die Azure AD Identity Governance durch Zuweisen von Zugriffspaketen, Zugriffsüberprüfungen oder privileged Identity Management nur lizenzierten Benutzern zuweisen. Anweisungen zum Umfang von Azure AD Identity Governance-Bereitstellungen finden Sie unter:

- [Lizenzanforderungen für die Azure AD-Berechtigungsverwaltung](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Lizenzanforderungen für die Azure AD-Zugriffsüberprüfung](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Lizenzanforderungen für die Verwendung von Privileged Identity Management](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (früher Azure Advanced Threat Protection) ist ein Clouddienst, der Unternehmenshybridumgebungen vor mehreren Arten von erweiterten gezielten Cyberangriffen und Insiderbedrohungen schützt.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Analysten und Sicherheitsexperten von SecOp profitieren von der Fähigkeit von Microsoft Defender for Identity, fortgeschrittene Bedrohungen, gefährdete Identitäten und böswillige Insideraktionen zu erkennen und zu untersuchen. Endbenutzer profitieren davon, dass ihre Daten von Microsoft Defender for Identity überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Microsoft Defender for Identity for Users bieten die Rechte, von Microsoft Defender for Identity zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender for Identity-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Azure ATP finden Sie unter ["Erstellen Ihrer Microsoft Defender for Identity-Instanz".](https://docs.microsoft.com/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender for Identity Services ist derzeit nicht in der Lage, die Funktionen auf bestimmte Benutzer zu beschränken. Sie müssen jeden Benutzer lizenzen, den Sie nutzen möchten.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender für Office 365

Microsoft Defender für Office 365 (früher Office 365 Advanced Threat Protection) schützt Organisationen vor komplexen Angriffen wie Phishing und Zero-Day-Schadsoftware. Microsoft Defender für Office 365 bietet auch umsetzbare Einblicke, indem Signale aus einer vielzahl von Daten korreliert werden, um potenzielle Bedrohungen zu identifizieren, zu priorisieren und Empfehlungen zur Verfügung zu stellen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Microsoft Defender für Office 365 schützt Benutzer vor komplexen Angriffen wie Phishing und Zero-Day-Schadsoftware. Die vollständige Liste der in Plan 1 und Plan 2 bereitgestellten Dienste finden Sie unter [Microsoft Defender für Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren? 

Microsoft Defender für Office 365 Plans 1 und 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security und Microsoft 365 Business Premium bieten benutzern die Rechte, von Microsoft Defender für Office 365 zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender für Office 365-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Microsoft Defender für Office 365-Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Defender für Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp).


### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Befolgen Sie zum Umfang von Microsoft Defender für Office 365 die Bereitstellungsrichtlinien für sichere Links und sichere Anlagen:

- Informationen zum Konfigurieren sicherer Links für lizenzierte Benutzer finden Sie unter ["Sichere Links" in Microsoft Defender für Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links)

- Informationen zum Konfigurieren sicherer Anlagen für lizenzierte Benutzer finden Sie unter ["Sichere Anlagen" in Microsoft Defender für Office 365.](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments)

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) ist eine Teilmenge von Microsoft Cloud App Security, mit Auf Office 365 beschränkten Features und ohne zusätzliche Sicherheit für Drittanbieter-Cloud-Apps und IaaS-Dienste.

OCAS bietet Organisationen Einblicke in ihre Produktivitäts-Cloud-Apps und -Dienste, bietet komplexe Analysen zur Identifizierung und Bekämpfung von Cyberbedrohungen und ermöglicht es ihnen, zu steuern, wie Daten über &mdash; Office 365 hinweg datenübertragungsübergreifend sind.

Informationen zum Vergleichen von Features finden Sie unter "Unterschiede zwischen Microsoft Cloud App Security und [Office 365 Cloud App Security".](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365)

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

OCAS ermittelt Schatten-IT, bietet Bedrohungsschutz in Office 365 und kann steuern, welche Apps über die Berechtigung zum Zugreifen auf Daten verfügen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A3/A5/G5 bietet einem Benutzer die Rechte, von OCAS zu profitieren.
Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Features von OCAS auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren des Diensts finden Sie unter ["Grundlegendes Setup für Cloud App Security".](https://docs.microsoft.com/cloud-app-security/general-setup)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können den Umfang von OCAS-Bereitstellungen einschränken, um zu erzwingen, wie auf bestimmte Apps zugegriffen wird, und Benutzergruppen einschränken, die von Office 365 Cloud App Security überwacht werden. Weitere Informationen finden Sie unter ["Bereichsbereitstellung".](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App-Sicherheit

Microsoft Cloud App Security (MCAS) ist eine Cloud Access Security Broker (CASB)-Lösung, die Organisationen Einblicke in ihre Cloud-Apps und -Dienste bietet, komplexe Analysen zur Identifizierung und Bekämpfung von Cyberbedrohungen bietet und ihnen ermöglicht, zu steuern, wie Daten über jede Cloud-App gesendet &mdash; werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

MCAS ermittelt und bewertet Shadow IT, bietet Bedrohungsschutz für Cloud-Apps von Erst- und Drittanbietern und schützt Informationen in Erst- und Drittanbieter-Cloud-Apps.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance bieten benutzern die Rechte, von MCAS zu profitieren.

Azure AD P1 bietet benutzern die Rechte, von den Discoveryfunktionen in MCAS zu profitieren.

Um von den Funktionen für bedingten Zugriff in MCAS zu profitieren, müssen Benutzer auch für Azure Active Directory P1 lizenziert werden, das in Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Security enthalten ist.

Um von der automatischen Bezeichnung zu profitieren, müssen Benutzer für Azure Information Protection P2 lizenziert werden, das in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance enthalten ist.

Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Funktionen von MCAS auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren von Microsoft Cloud App Security-Richtlinien für lizenzierte Benutzer finden Sie in der [Übersicht über Microsoft Cloud App Security.](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können die Bereiche für die Bereitstellung von MCAS für lizenzierte Benutzer mithilfe der bereichsbereichsierten Bereitstellungsfunktionen des Diensts erweitern. Weitere Informationen finden Sie unter ["Bereichsbereitstellung".](https://docs.microsoft.com/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>Compliance-Manager

Vereinfachen Sie die Compliance und verringern Sie risiken mit dem Compliance-Manager. Der Compliance-Manager unterstützt Organisationen bei der Erfüllung der Anforderungen an Vorschriften, Standards, Unternehmensrichtlinien oder andere gewünschte Kontrollframeworks.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Im Folgenden finden Sie die Vorteile des Compliance-Manager-Diensts für die Benutzer:

- Übersetzt komplizierte Vorschriften, Standards, Unternehmensrichtlinien oder andere gewünschte Steuerungsframeworks in eine einfache Sprache.
- Bietet Zugriff auf eine umfangreiche Bibliothek mit out-of-the-Box-Bewertungen und benutzerdefinierten Bewertungen, um eindeutige Complianceanforderungen zu erfüllen
- Ordnet regulatorische Kontrollen empfohlenen Verbesserungsmaßnahmen zu
- Enthält schrittweise Anleitungen zum Implementieren der Lösungen zur Erfüllung gesetzlicher Anforderungen
- Hilft Benutzern, Aktionen zu priorisieren, die die höchste Auswirkung auf die Organisationskonformität haben, indem jeder Aktion eine Bewertung zuzuordnen ist.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Kunden mit E1- und E3-Lizenzen können nur auf die standardmäßige Bewertung der Datenschutzgrundwerte zugreifen. Kunden mit Office 365 E5/A5- und Microsoft 365 E5/A5-Lizenzen (Compliance, Info Protection Governance sowie eDiscovery- und Überwachungs-SKUs enthalten) können auf die Standardbewertungen für Datenschutz, DSGVO, &amp; NIST 800-53 und ISO 27001 zugreifen. Das benutzerdefinierte Bewertungsfeature und die Premiumbewertungen sind Office 365 E5/A5- und Microsoft 365 E5/A5-Kunden vorbehalten. #A0 stehen im ersten Quartal 2021 über VL, CSP und WebDirect zum Kauf zur Verfügung. 

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Der Compliance-Manager wird standardmäßig für Ihren Mandanten bereitgestellt. Administratoren legen Benutzerberechtigungen fest und weisen Rollen zu, damit Benutzer, die keine Administratoren sind, in Ihrer Organisation mit der Verwendung des Compliance-Managers beginnen können. Weitere Informationen finden Sie unter ["Erste Schritte mit dem Compliance-Manager": Festlegen von Benutzerberechtigungen und Zuweisen von Rollen.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Der Zugriff auf den Compliance-Manager wird durch Festlegen von Benutzerberechtigungen und Zuweisen von Rollen gesteuert. Weitere Informationen finden Sie unter ["Erste Schritte mit dem Compliance-Manager": Festlegen von Benutzerberechtigungen und Zuweisen von Rollen.](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender für Endpunkt

Microsoft Defender for Endpoint (früher Microsoft Defender ATP) ist eine Endpunktsicherheitslösung, die risikobasiertes Sicherheitsrisikomanagement und -bewertung umfasst. Funktionen zur Reduzierung der Angriffsfläche; verhaltensbasierter und cloudgestützter Schutz der nächsten Generation; Endpunkterkennung und -reaktion (Endpoint Detection and Response, EDR); automatische Untersuchung und Wartung; und verwaltete Dienste für die Suche. Weitere Informationen finden Sie auf der [Microsoft Defender for Endpoint-Seite.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5 (M365 E5), einschließlich Windows 10 Enterprise E5, Microsoft 365 E5 Security, Microsoft 365 A5 (M365 A5), können von Microsoft Defender for Endpoint profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Analysten und Sicherheitsexperten von SecOps profitieren von den Endpunktsicherheitsfunktionen von Microsoft Defender for Endpoint, um vorbeugenden Schutz, Erkennung nach Sicherheitsverletzungen, automatisierte Untersuchung und Reaktion auf erweiterte Bedrohungen zu ermöglichen. Endbenutzer profitieren davon, dass bösartige Ereignisse von Microsoft Defender for Endpoint überwacht werden.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender für Endpunktfeatures auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Weitere Informationen zur Bereitstellung finden Sie in den [Bereitstellungsphasen.](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender für Endpunktadministratoren können die rollenbasierte Zugriffssteuerung verwenden, um Rollen und Gruppen innerhalb des Sicherheitsteams zu erstellen, um den entsprechenden Zugriff auf das Microsoft Defender Security Center zu gewähren. Weitere Informationen finden Sie unter ["Verwalten des Portalzugriffs mithilfe der rollenbasierten Zugriffssteuerung".](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="information-protection"></a>Informationsschutz

Der Informationsschutz hilft Organisationen dabei, vertrauliche Dokumente und E-Mails zu erkennen, zu klassifizieren, zu beschriften und zu schützen. Administratoren können Regeln und Bedingungen definieren, um Bezeichnungen automatisch anzuwenden, Benutzer können Bezeichnungen manuell anwenden, oder es kann eine Kombination der beiden verwendet werden, wobei Benutzern Empfehlungen zum Anwenden von Bezeichnungen gegeben werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von der Möglichkeit, Vertraulichkeitsbezeichnungen manuell auf ihre Inhalte anzuwenden oder ihre Inhalte automatisch zu klassifizierten.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 und AIP Plan 2 bieten benutzern die Rechte, von der manuellen Vertraulichkeitsbezeichnung zu profitieren.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 und AIP Plan 2 bieten benutzern die Rechte, von der Anwendung und Anzeige von Vertraulichkeitsbezeichnungen in Power BI zu profitieren und Daten zu schützen, wenn sie aus Power BI nach Excel, PowerPoint oder PDF exportiert werden. 

> [!NOTE]
> Power BI ist in Microsoft 365 E5/A5/G5 enthalten. in allen anderen Plänen muss Power BI separat lizenziert werden.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection und Governance, Office 365 E5, Office 365 Advanced Compliance, Enterprise Mobility + Security E5 und AIP Plan 2 bieten benutzern die Rechte, von der automatischen Vertraulichkeitsbezeichnung zu profitieren.

Spezifische Rechte nach Lizenz finden Sie im detaillierten Vergleich der Microsoft 365-Compliance-Lizenzierung. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Enthält keine Rechte für die automatische Klassifizierung basierend auf Machine Learning (trainierbare Klassifizierungen).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind features zum Schutz von Informationen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Richtlinien für lizenzierte Benutzer finden Sie unter Aktivieren von Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Mit Ausnahme der Verwendung des AIP-Scannerfeatures können Richtlinien auf bestimmte Gruppen oder Benutzer und Registrierungen begrenzt werden, um zu verhindern, dass nicht lizenzierte Benutzer Klassifizierungs- oder Bezeichnungsfeatures ausführen. Anweisungen zum Umfang von AIP-Bereitstellungen finden Sie unter ["Konfigurieren der Azure Information Protection-Richtlinie".](https://docs.microsoft.com/azure/information-protection/configure-policy)

Für die AIP-Scanner-Funktion verpflichtet sich Microsoft nicht, Benutzern, die nicht lizenziert sind, Dateiklassifizierungs-, Bezeichnungs- oder Schutzfunktionen zur Verfügung zu stellen.

## <a name="information-governance"></a>Informationssteuerung

Informationssteuerung hilft Organisationen bei der Verwaltung ihres Risikos durch das Ermitteln, Klassifizieren, Bezeichnungen und Steuern ihrer Daten. Mit Information Governance können Organisationen geschäftliche und behördliche Anforderungen erfüllen und ihre Angriffsfläche reduzieren, indem sie Aufbewahrungs- und Löschfunktionen für ihre Microsoft 365- und Drittanbieterdaten bereitstellen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren, indem sie Daten für Aufbewahrungszwecke klassifizieren können, um bestimmte Richtlinien und Vorschriften zu erfüllen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 F3/Business Premium-, Office 365 E1/A1/F3- und eigenständige Exchange-Pläne bieten benutzern die Rechte, von der manuellen Anwendung von Aufbewahrungsbezeichnungen ohne Datensatz auf Postfachdaten zu profitieren.

Microsoft 365 F3/F1/Business Premium-, Office 365 E1/A1/F3- und eigenständige #A0 bieten benutzern die Rechte, von der manuellen Anwendung von Aufbewahrungsbezeichnungen für #A1 auf Dateien in SharePoint oder OneDrive zu profitieren. 

Microsoft 365 E5/A5/E3/A3/Business Premium, Office 365 E5/A5/E3/A3, Exchange Plan 2 und Exchange Online-Archivierung bieten einem Benutzer die Rechte, von einer grundlegenden organisationsweiten oder standortweiten Postfachaufbewahrungsrichtlinie zu profitieren und/oder eine Aufbewahrungsbezeichnung ohne Datensatz manuell auf Postfachdaten anzuwenden.

Microsoft 365 E5/A5/E3/A3, Office 365 E5/A5/E3/A3 und SharePoint Plan 2 bieten benutzern die Rechte, von einer grundlegenden SharePoint- oder #A0 zu profitieren und/oder eine Aufbewahrungsbezeichnung, die keine Datensatzbezeichnung ist, manuell auf Dateien in SharePoint oder OneDrive anzuwenden.

Microsoft 365 E5/A5/E3/A3 und Office 365 E5/A5/E3/A3 bieten benutzern die Rechte, von einer Aufbewahrungsrichtlinie für Teams zu profitieren.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5 und Office 365 Advanced Compliance bieten einem Benutzer die Rechte, von der automatischen Anwendung von Aufbewahrungsbezeichnungen oder -richtlinien, dem Anwenden von Standardaufbewahrungsbezeichnungen oder -richtlinien, dem Starten des Aufbewahrungszeitraums einer Aufbewahrungsbezeichnung auf der Grundlage eines benutzerdefinierten Ereignisses, dem Auslösen einer manuellen Dispositionsüberprüfung am Ende des Aufbewahrungszeitraums der Bezeichnung, dem Importieren von Drittanbieterdaten über systemeigene Datenconnectors, dem Deklarieren einer Datei als Datensatz, dem Ermitteln von bezeichnetem Inhalt und der Überwachung der Bezeichnungsaktivität zu profitieren.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection und Governance bieten benutzern die Rechte, von der automatischen Anwendung von Aufbewahrungsbezeichnungen basierend auf trainierbaren Klassifizierungen zu profitieren.

Spezifische Rechte nach Lizenz finden Sie im detaillierten Vergleich der Microsoft 365-Compliance-Lizenzierung. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Die Features der Informationsverwaltung für alle Benutzer innerhalb des Mandanten auf Mandantenebene aktiviert. Informationen zum Konfigurieren von Information Governance zum Anwenden der automatischen Kennzeichnung und Richtlinien für lizenzierte Benutzer finden Sie [unter Microsoft Information Governance in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Features für die Informationssteuerung können auf lizenzierte Benutzer an bestimmten Standorten (Teamwebsites, Gruppenwebsites usw.) angewendet werden. Informationen zum Konfigurieren von Information Governance zum Anwenden der automatischen Kennzeichnung und Richtlinien für lizenzierte Benutzer finden Sie [unter Microsoft Information Governance in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Datensatzverwaltung

Mit der Datensatzverwaltung können Organisationen ihre geschäftlichen und behördlichen Datensatzaufbewahrungsverpflichtungen erfüllen, indem sie ihre Microsoft 365- und Drittanbieterdaten ermitteln, klassifizieren, bezeichnungen, speichern und defensible Löschungsfunktionen nutzen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5/G5, Office 365 Advanced Compliance bieten benutzern die Rechte, von der Datensatzverwaltung zu profitieren, einschließlich der Deklaration von Elementen als Datensätze oder behördlichen Datensätzen, der automatischen Anwendung von Aufbewahrungs- oder Datensatzbezeichnungen und der Ausführung von Dispositionsüberprüfungsprozessen (mit Ausnahme der automatischen Anwendung einer Aufbewahrungsbezeichnung basierend auf trainierbaren Klassifizierungen).

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und Microsoft 365 Information Protection and Governance bieten benutzern die Rechte, von der automatischen Anwendung von Aufbewahrungs- oder Datensatzbezeichnungen basierend auf trainierbaren Klassifizierungen zu profitieren.

Spezifische Rechte nach Lizenz finden Sie im detaillierten Vergleich der Microsoft 365-Compliance-Lizenzierung. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von der Möglichkeit, Inhalte als Datensatz zu deklarieren und ihren vollständigen Datensatzprozess von der Richtliniendefinition und -deklaration bis hin zur verwerfbaren Entsorgung zu verwalten.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Die Datensatzverwaltungsfeatures auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren der Datensatzverwaltung für lizenzierte Benutzer finden Sie unter [Informationen zur Datensatzverwaltung in Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Datensatzverwaltungsfeatures können auf lizenzierte Benutzer an bestimmten Speicherorten (Teamwebsites, Gruppenwebsites usw.) angewendet werden. Informationen zum Konfigurieren der Datensatzverwaltung für lizenzierte Benutzer finden Sie unter [Informationen zur Datensatzverwaltung in Microsoft 365.](https://docs.microsoft.com/microsoft-365/compliance/records-management)

## <a name="data-connectors"></a>Datenconnectors 

Microsoft stellt Datenconnectors von Drittanbietern zur Verfügung, die im Microsoft 365 Compliance Center konfiguriert werden können. Eine Liste der von Microsoft bereitgestellten Datenconnectors finden Sie in der Tabelle [mit Datenconnectors von](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) Drittanbietern. In dieser Tabelle sind auch die Compliancelösungen zusammengefasst, die Sie nach dem Importieren und Archivieren von Daten in Microsoft 365 auf Drittanbieterdaten anwenden können, sowie Links zu den schrittweisen Anweisungen für jeden Connector.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Der Hauptvorteil der Verwendung von Datenconnectors zum Importieren und Archivieren von Drittanbieterdaten in Microsoft 365 besteht in der Anwendung verschiedener Microsoft 365-Compliancelösungen auf die Daten, nachdem sie importiert wurden. Dadurch wird sichergestellt, dass die Nicht-Microsoft-Daten Ihrer Organisation den Vorschriften und Standards entsprechen, die sich auf Ihre Organisation auswirken.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Die folgenden Lizenzen bieten benutzern die Rechte, von Datenconnectors zu profitieren:

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 Info Protection & Governance
- Microsoft 365 E5/A5 Compliance
- Microsoft 365 E5/A5 Insider Risk Management
- Microsoft 365 E5/A5 eDiscovery und Überwachung
- Office 365 E5/A5
- Office 365 Advanced Compliance

Für Datenconnectors im M365 Security & Compliance Center, die von einem Microsoft-Partner bereitgestellt werden, benötigt Ihre Organisation eine Geschäftsbeziehung mit dem Partner, bevor Sie diese Connectors bereitstellen können.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Connectors werden mithilfe des Security & Compliance Center und des Connectorkatalogs konfiguriert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Datenconnectorsdienste sind ein Wert auf Mandantenebene. Jeder Benutzer, der von diesem Dienst profitieren soll, muss lizenziert sein.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Microsoft Graph APIs für die Verhinderung von Datenverlust (Data Loss Prevention, DLP) von Teams

Anfang dieses Jahres haben wir die öffentliche Vorschau der [Microsoft Graph-Änderungsbenachrichtigungs-API für Nachrichten in Teams angekündigt.](https://go.microsoft.com/fwlink/?linkid=2143888) Mit dieser API können Entwickler Apps erstellen, die Microsoft Teams-Nachrichten nahezu in Echtzeit abhören und Implementierungen von DLP-Szenarios sowohl für Kunden als auch für ISVs aktivieren können. Darüber hinaus ermöglicht die Microsoft Graph-Patch-API das Anwenden von DLP-Aktionen auf Teams-Nachrichten.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

[Funktionen zur Verhinderung von Datenverlust (Data Loss Prevention, DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) werden in Microsoft Teams häufig verwendet, insbesondere, wenn Organisationen auf Remotearbeit umschalten. Wenn Ihre Organisation über DLP verfügt, können Sie jetzt Richtlinien definieren, die verhindern, dass Personen vertrauliche Informationen in einem Microsoft Teams-Kanal oder einer Chatsitzung freigeben.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Sie benötigen eine der folgenden E5-Lizenzen, um Unterstützung für den DLP-Schutz in Teams Chat zu erhalten:

- Microsoft 365 E5/A5
- Microsoft 365 E5/A5 Compliance
- Microsoft 365 E5/A5 Information Protection und Governance
- Office 365 E5/A5 

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Der Zugriff auf die API wird auf Mandantenebene konfiguriert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Die Microsoft Graph-API für Teams-DLP ist ein Wert auf Mandantenebene. Jeder Benutzer, der von diesem Dienst profitieren soll, muss lizenziert sein.

## <a name="ediscovery"></a>eDiscovery

eDiscovery bietet Untersuchungs- und eDiscovery-Lösungen für IT- und Rechtsabteilungen in Unternehmen, um Inhalte im Zusammenhang mit einer Untersuchung oder einem Rechtsstreit vor dem Export aus dem Microsoft 365-System zu identifizieren, zu sammeln, zu erhalten, zu reduzieren und zu überprüfen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Ein Benutzer profitiert von Advanced eDiscovery, wenn der Benutzer als Datenverwahrer (eine Person mit administrativer Kontrolle über ein Dokument oder eine elektronische Datei) für einen Fall ausgewählt wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 und Office 365 Advanced Compliance bieten benutzern die Rechte, von Core eDiscovery zu profitieren.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5 eDiscovery and Audit, Office 365 E5/A5/G5 und Office 365 Advanced Compliance bieten benutzern die Rechte, um von Advanced eDiscovery zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind erweiterte eDiscovery-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert, wenn Administratoren eDiscovery-Berechtigungen im Security & Compliance Center zuweisen.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

eDiscovery-Administratoren können bestimmte Benutzer als Datenverwahrer für einen Fall auswählen, indem sie das integrierte Verwaltungstool für Verwahrer in Advanced eDiscovery verwenden, wie in "Hinzufügen von Verwahrern zu einem [Advanced eDiscovery-Fall"](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)beschrieben.

## <a name="office-365-customer-key"></a>Office 365 Customer Key

Mit Customer Key steuern Sie die Verschlüsselungsschlüssel Ihrer Organisation und konfigurieren Office 365 so, dass diese zum Verschlüsseln Ihrer ruhen daten in Microsoft-Rechenzentren verwendet werden. Mit anderen Worten: Mit Customer Key können Sie eine Verschlüsselungsebene hinzufügen, die Ihnen gehört, indem Sie Ihre eigenen Schlüssel verwenden. Zu den ruhen daten gehören Daten aus Exchange Online und Skype for Business, die in Postfächern und Dateien in SharePoint Online und OneDrive for Business gespeichert sind.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von Customer Key, indem sie ihre Ruhedaten auf der Anwendungsebene mithilfe von Verschlüsselungsschlüsseln verschlüsselt lassen, die von ihrer eigenen Organisation bereitgestellt, gesteuert und verwaltet werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5 und Office 365 Advanced Compliance bieten benutzern die Rechte, von Kundenschlüsseln zu profitieren. Um den vollen Nutzen von Customer Key zu erhalten, müssen Sie auch über ein Abonnement für Azure Key Vault verfügen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Office 365-Kundenschlüsselverschlüsselungsschlüssel können für alle Daten aktiviert werden, die in Exchange Online- und Skype for #A0 sowie SharePoint Online-, OneDrive for Business- und #A1 gespeichert sind. Weitere Informationen zu Office 365 Customer Key, einschließlich der ersten Schritte, finden Sie unter ["Dienstverschlüsselung mit Customer Key".](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Für Exchange Online und Skype for Business können Postfächer mithilfe des Kundenschlüssels verschlüsselt werden. Sie müssen Azure einrichten, bevor Sie Customer Key für Office 365 verwenden können. Unter ["Kundenschlüssel einrichten"](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) finden Sie die Schritte, die Sie ausführen müssen, um die erforderlichen Azure-Ressourcen zu erstellen und zu konfigurieren, sowie die Schritte zum Einrichten von Customer Key in Office 365. Nachdem Sie das Setup von Azure abgeschlossen haben, bestimmen Sie, welche Richtlinie und damit welche Schlüssel Postfächern und Dateien in Ihrer Organisation zugewiesen werden sollen. Für Postfächer und Dateien, denen Sie keine Richtlinie zuweisen, werden Verschlüsselungsrichtlinien verwendet, die von Microsoft gesteuert und verwaltet werden. Weitere Informationen zu Customer Key oder eine allgemeine Übersicht finden Sie unter [Dienstverschlüsselung mit Customer Key](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview).

## <a name="office-365-customer-lockbox"></a>Office 365-Kunden-Lockbox

Die Kunden-Lockbox bietet eine zusätzliche Kontrollebene, indem Sie Kunden die Möglichkeit bieten, eine explizite Zugriffsautorisierung für Dienstvorgänge zu erhalten. Durch den Nachweis, dass Verfahren für die explizite Autorisierung des Datenzugriffs durchgeführt werden, kann die Kunden-Lockbox Organisationen auch dabei helfen, bestimmte Complianceverpflichtungen wie HIPAA und FEDRAMP zu erfüllen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Die Kunden-Lockbox stellt sicher, dass niemand bei Microsoft auf Kundeninhalte zugreifen kann, um einen Dienstvorgang ohne ausdrückliche Genehmigung des Kunden durchzuführen. Die Kunden-Lockbox führt den Kunden in den Genehmigungsworkflow für Anfragen zum Zugriff auf seine Inhalte ein. Gelegentlich sind die Techniker von Microsoft während des Supportprozesses an der Problembehandlung und Behebung von problemen beteiligt, die von Kunden gemeldet wurden. In den meisten Fällen werden Probleme durch umfangreiche Telemetrie- und Debugtools behoben, die Microsoft für seine Dienste installiert hat. Es kann jedoch Fälle gibt, in denen ein Microsoft-Techniker auf Kundeninhalte zugreifen muss, um die Ursache zu ermitteln und das Problem zu beheben. Kunden-Lockbox setzt voraus, dass der Techniker den Zugriff vom Kunden als letzten Schritt im Genehmigungsworkflow anfordert. Dadurch haben Organisationen die Möglichkeit, diese Anforderungen zu genehmigen oder zu verweigern, wodurch sie direkt steuern können, ob ein Microsoft-Techniker auf die Endbenutzerdaten der Organisation zugreifen kann.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Insider Risk Management und Office 365 Advanced Compliance bieten benutzern die Rechte, von der Kunden-Lockbox zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren können die Kunden-Lockbox im Microsoft 365 Admin Center aktivieren. Weitere Informationen finden Sie unter ["Kunden-Lockbox" in Office 365.](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests) Wenn die Kunden-Lockbox aktiviert ist, muss Microsoft die Genehmigung einer Organisation ein holen, bevor auf ihre Inhalte zugegriffen wird.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Derzeit kann der Kunden-Lockbox-Dienst nicht auf bestimmte Benutzer beschränkt werden. Sie müssen jeden Benutzer lizenzen, den Sie nutzen möchten.

## <a name="privileged-access-management-in-office-365"></a>Privileged Access Management in Office 365

[Privileged Access Management (PAM) bietet](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) eine präzise Zugriffssteuerung über privilegierte Administratoraufgaben in Office 365. Nach der Aktivierung von PAM müssen Benutzer zum Ausführen von Aufgaben mit erhöhten und privilegierten Rechten just-in-time-Zugriff über einen Genehmigungsworkflow anfordern, der in hohem Umfang und zeitgebunden ist.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Wenn Sie PAM aktivieren, können Organisationen ohne ständige Berechtigungen arbeiten. Benutzer profitieren von der zusätzlichen Schutzebene gegen Sicherheitsrisiken, die aus dem ständigen Administratorzugriff entstehen, der einen unkontrollierten Zugriff auf ihre Daten ermöglicht.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und Microsoft 365 E5/A5 Information Protection and Governance bieten benutzern die Rechte, von PAM zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die PAM-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von PAM-Richtlinien finden Sie unter ["Erste Schritte mit der Verwaltung des privilegierten Zugriffs".](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Kunden können PAM auf Benutzerbasis über eine Genehmigende Gruppe und Zugriffsrichtlinien verwalten, die auf lizenzierte Benutzer angewendet werden können. Weitere Informationen finden Sie unter [Privileged Access Management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Verschlüsselung mit Doppelschlüsseln für Microsoft 365 

Mit der Doppelschlüsselverschlüsselung für Microsoft 365 können Sie Ihre hochgradig vertraulichen Daten schützen, um spezielle Anforderungen zu erfüllen und die vollständige Kontrolle über Ihren Verschlüsselungsschlüssel zu behalten. Die Verschlüsselung mit Doppelschlüsseln verwendet zwei Schlüssel, um Ihre Daten zu schützen, mit einem Schlüssel in Ihrem Steuerelement und dem zweiten Schlüssel, der sicher von Microsoft Azure gespeichert wird. Um die Daten anzeigen zu können, müssen Sie zugriff auf beide Schlüssel haben. Da Microsoft nur auf einen Schlüssel zugreifen kann, sind Ihr Schlüssel und auch Ihre Daten für Microsoft nicht verfügbar, um sicherzustellen, dass Sie die vollständige Kontrolle über den Datenschutz und die Sicherheit Ihrer Daten haben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von der Doppelschlüsselverschlüsselung, indem sie ihre verschlüsselten Daten in die Cloud migrieren können, wodurch der Zugriff durch Dritte verhindert wird, solange der Schlüssel die Kontrolle über die Benutzer hat. Benutzer können verschlüsselte Inhalte mit Doppelschlüsseln schützen und nutzen, ähnlich wie andere durch Vertraulichkeitsbezeichnungen geschützte Inhalte.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/A5 und Office 365 Advanced Compliance bieten benutzern die Rechte, von der Verschlüsselung mit Doppelschlüsseln zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Die Verschlüsselung mit Doppelschlüssel unterstützt die Desktopversion Microsoft Office Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Um Daten in einer Office 365- und/oder Microsoft 365-Organisation Verschlüsselungsschlüssel für lizenzierte Benutzer zuzuordnen, befolgen Sie die Anweisungen zur Bereitstellung der Doppelten Schlüsselverschlüsselung.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Verhinderung von Datenverlust in Office 365 für Exchange Online, SharePoint Online und OneDrive for Business

Mit Office 365 Data Loss Prevention (DLP) für Exchange Online, SharePoint Online und OneDrive for Business können Organisationen vertrauliche Informationen in E-Mails und Dateien (einschließlich Dateien, die in Microsoft #A0 gespeichert sind) identifizieren, überwachen und automatisch schützen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von DLP für Exchange Online, SharePoint Online und OneDrive for Business, wenn ihre E-Mails und Dateien auf vertrauliche Informationen überprüft werden, wie in der #A0 der Organisation konfiguriert.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 und Office 365 Data Loss Prevention bieten benutzern die Rechte, von Office 365 DLP für Exchange Online, SharePoint Online und OneDrive for Business zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Exchange Online-E-Mails, #A0 und #A1 aktivierte Speicherorte *(Workloads)* für diese #A2 für alle Benutzer innerhalb des Mandanten. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie [unter Übersicht über die Verhinderung von Datenverlust.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security & Compliance Center unter Speicherorte zur Verhinderung von Datenverlust  >  **anpassen.**

## <a name="communication-data-loss-prevention-for-teams"></a>Verhinderung von Kommunikationsdatenverlusten für Teams

Mit Kommunikations-DLP für Teams können Organisationen Chats und Kanalnachrichten blockieren, die vertrauliche Informationen enthalten, z. B. Finanzinformationen, personenbezogene Informationen, gesundheitsbezogene Informationen oder andere vertrauliche Informationen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 Information Protection and Governance und Office 365 Advanced Compliance können von Kommunikations-DLP für Teams profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Absender profitieren davon, dass vertrauliche Informationen in ihren ausgehenden Chat- und Kanalnachrichten auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Chat- und Kanalnachrichten von Teams ein aktivierter *Speicherort (Workload)* für diese DLP-Features für alle Benutzer innerhalb des Mandanten. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie [unter Übersicht über die Verhinderung von Datenverlust.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security & Compliance Center unter Speicherorte zur Verhinderung von Datenverlust  >  **anpassen.**

## <a name="information-barriers"></a>Informationsbarrieren

Informationsbarrieren sind Richtlinien, die ein Administrator konfigurieren kann, um zu verhindern, dass Einzelpersonen oder Gruppen miteinander kommunizieren. Dies ist z. B. hilfreich, wenn eine Abteilung Informationen abhanden kommt, die nicht für andere Abteilungen freigegeben werden sollen, oder eine Gruppe an der Kommunikation mit außen bzw. von Außenkontakten gehindert werden muss. Richtlinien für Informationsbarrieren verhindern auch Nachschlage- und Ermittlungsinformationen. Dies bedeutet, dass Sie diesen Benutzer nicht in der Personenauswahl finden, wenn Sie versuchen, mit einer Person zu kommunizieren, mit der Sie nicht kommunizieren sollten.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von den erweiterten Compliancefunktionen von Informationsbarrieren, wenn sie nicht mit anderen kommunizieren können. Beispiel:<br><br>

| Szenario | Wer benötigt eine Lizenz? |
|:------|:------|:------|
| Zwei Gruppen (Gruppe 1 und Gruppe 2) können nicht miteinander kommunizieren (d. h. Benutzer der Gruppe 1 können nicht mit Benutzern der Gruppe 2 kommunizieren, und Benutzer der Gruppe 2 können nicht mit Benutzern der Gruppe &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1 kommunizieren. | Benutzer in Gruppe &nbsp; 1 und Gruppe &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Insider Risk Management, Office 365 E5/A5 und Office 365 Advanced Compliance bieten benutzern die Rechte, von Informationsbarrieren zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Richtlinien für Informationsbarrieren mithilfe von PowerShell-Cmdlets im Security & Compliance Center. Administratoren muss die Rolle "Globaler Microsoft 365 Enterprise-Administrator", "Globaler Office 365-Administrator" oder "Complianceadministrator" zugewiesen sein, um eine Richtlinie für Informationsbarrieren zu erstellen. Diese Richtlinien gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zu Informationsbarrieren finden Sie unter [Informationsbarrieren in Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security & Compliance Center anpassen. Wenn beispielsweise alle Benutzer für Office 365 E3 lizenziert sind und keiner für Office 365 Advanced Compliance/E5 lizenziert ist, müssten sie keine Richtlinien für Informationsbarrieren für die Organisation erstellen. Weitere Informationen finden Sie unter [Informationsbarrieren in Microsoft Teams.](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams)

## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

Office 365-Nachrichtenverschlüsselung (Office Message Encryption, OME) ist ein Dienst, der auf Azure Rights Management (Azure RMS) aufbaut und mit dem Sie verschlüsselte E-Mails an Personen innerhalb oder außerhalb Ihrer Organisation senden können, unabhängig von der E-Mail-Zieladresse (Gmail, Yahoo! Mail, Outlook.com usw.).

Zum Anzeigen verschlüsselter Nachrichten können Empfänger eine einmalige Kennung abrufen, sich mit einem Microsoft-Konto anmelden oder sich mit einem Geschäfts-, Schul- oder Unikonto, das Office 365 zugeordnet ist, anmelden. Empfänger können auch verschlüsselte Antworten senden. Sie benötigen kein Abonnement, um verschlüsselte Nachrichten anzeigen oder verschlüsselte Antworten senden zu können.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Nachrichtensender profitieren von der hinzugefügten Kontrolle über vertrauliche E-Mails, die von der Office 365-Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E3/A3, Office 365 E3/A3 und Azure Information Protection Plan 1 bieten benutzern die Rechte, von der Office 365-Nachrichtenverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Office 365-Nachrichtenverschlüsselungsrichtlinien im Exchange Admin Center unter **"Nachrichtenflussregeln".**  >   Diese Regeln gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Office 365-Nachrichtenverschlüsselungsfunktionen finden Sie unter Einrichten neuer Funktionen für [die Nachrichtenverschlüsselung.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenflussregeln für die Office 365-Nachrichtenverschlüsselung nur auf lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenflussregeln finden Sie unter Definieren von [Nachrichtenflussregeln zum Verschlüsseln von E-Mail-Nachrichten.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Erweiterte Office 365-Nachrichtenverschlüsselung

Die erweiterte Nachrichtenverschlüsselung in Office 365 hilft Kunden bei der Erfüllung von Complianceverpflichtungen, die flexiblere Kontrollen über externe Empfänger und deren Zugriff auf verschlüsselte E-Mails erfordern. Mit der erweiterten Nachrichtenverschlüsselung können Administratoren vertrauliche E-Mails steuern, die außerhalb der Organisation freigegeben wurden, indem sie automatische Richtlinien verwenden, die vertrauliche Informationstypen erkennen können (z. B. personenbezogene Informationen oder Finanz- oder Integritäts-IDs), oder sie können Schlüsselwörter verwenden, um den Schutz durch Anwenden benutzerdefinierter E-Mail-Vorlagen und ablaufenden Zugriff auf verschlüsselte E-Mails über ein sicheres Webportal zu verbessern. Darüber hinaus können Administratoren verschlüsselte E-Mails, auf die extern über ein sicheres Webportal zugegriffen wird, weiter steuern, indem sie den Zugriff jederzeit wiedererstellen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Nachrichtensender profitieren von der hinzugefügten Kontrolle über vertrauliche E-Mails, die von der erweiterten Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance und Office 365 Advanced Compliance bieten benutzern die Rechte, von der erweiterten Nachrichtenverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten richtlinien für die erweiterte Nachrichtenverschlüsselung im Exchange Admin Center unter **"Nachrichtenflussregeln".**  >   Diese Regeln gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Funktionen für die Nachrichtenverschlüsselung finden Sie unter Einrichten der neuen [Office 365-Nachrichtenverschlüsselungsfunktionen.](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenflussregeln für die erweiterte Nachrichtenverschlüsselung nur auf lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenflussregeln finden Sie unter Definieren von Nachrichtenflussregeln zum [Verschlüsseln von E-Mail-Nachrichten in Office 365.](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="communication-compliance"></a>Kommunikationscompliance

Die Kommunikationskonformität in Microsoft 365 trägt dazu bei, Kommunikationsrisiken zu minimieren, indem Sie unangemessene Nachrichten in Ihrer Organisation erkennen, erfassen und Abhilfemaßnahmen ergreifen können. Sie können bestimmte Richtlinien definieren, die interne und externe E-Mails, Microsoft Teams oder Drittanbieterkommunikationen in Ihrer Organisation erfassen. Prüfer können geeignete Abhilfemaßnahmen ergreifen, um sicherzustellen, dass sie den Nachrichtenstandards Ihrer Organisation entsprechen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Compliancespezialisten profitieren von dem Dienst, indem sie die Unternehmenskommunikation durch Richtlinien zur Kommunikationskonformität überwachen lassen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und Microsoft 365 Insider Risk Management bieten benutzern die Rechte, von der Kommunikationskonformität zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren und Compliancespezialisten erstellen Kommunikations-Compliance-Richtlinien im Microsoft 365 Compliance Center. Diese Richtlinien definieren, welche Kommunikationen und Benutzer in der Organisation überprüft werden, definieren benutzerdefinierte Bedingungen, die die Kommunikation erfüllen muss, und geben an, wer Überprüfungen durchführen soll.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren wählen bestimmte Benutzer oder Gruppen aus, die in eine Richtlinie zur Kommunikationskonformität enthalten sein sollten. Wenn sie eine Gruppe auswählen, können sie auch bestimmte Benutzer in der Gruppe auswählen, die von der Kommunikationskonformitätsrichtlinie ausgeschlossen werden sollen. Weitere Informationen zu Richtlinien zur Kommunikationskonformität finden Sie unter ["Erste Schritte mit der Kommunikationskonformität in Microsoft 365".](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure)

## <a name="insider-risk-management"></a>Insider-Risikomanagement

Das Risikomanagement für Insider ist eine Lösung in Microsoft 365, mit der Sie interne Risiken minimieren können, indem Sie riskante Aktivitäten in Ihrer Organisation erkennen, untersuchen und Maßnahmen ergreifen können.

Mit benutzerdefinierten Richtlinien können Sie bösartige und versehentlich riskante Aktivitäten in Ihrer Organisation erkennen und maßnahmen ergreifen, einschließlich der Eskalierung von Fällen an Microsoft Advanced eDiscovery, falls erforderlich. Risikoanalysten in Ihrer Organisation können schnell geeignete Maßnahmen ergreifen, um sicherzustellen, dass die Benutzer den Compliancestandards Ihrer Organisation entsprechen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren davon, dass ihre Aktivitäten auf Risiken überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und Microsoft 365 Insider Risk Management bieten einem Benutzer die Rechte, von dem Insider Risk Management zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Richtlinien für das Insider-Risikomanagement müssen im Microsoft 365 Compliance Center erstellt und Benutzern zugewiesen werden.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Wählen Sie beim Erstellen einer Richtlinie im Microsoft  365 Compliance  Center auf der Seite Benutzer und Gruppen auswählen die Option Benutzer oder Gruppen auswählen, um nur lizenzierte Benutzer auszuwählen. Wenn alle Ihre Benutzer lizenziert sind, können Sie das Kontrollkästchen "Alle Benutzer und **E-Mail-aktivierte** Gruppen" aktivieren. Weitere Informationen finden Sie unter ["Erste Schritte mit dem Insider-Risikomanagement".](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>Richtlinien für bedingten Zugriff

Bedingter Zugriff ist das Tool, das von Azure Active Directory verwendet wird, um Signale zusammenzubringen, Entscheidungen zu treffen und Organisationsrichtlinien zu erzwingen. Bedingter Zugriff ist das Herzstück der identitätsgesteuerten Steuerung. Richtlinien für bedingten Zugriff sind am einfachsten if-then-Anweisungen. Wenn ein Benutzer auf eine Ressource zugreifen möchte, muss er eine Aktion abschließen. Beispiel: Ein Lohnbuchhaltungsmanager möchte auf die Abrechnungsanwendung zugreifen und muss eine mehrstufige Authentifizierung ausführen, um darauf zu zugreifen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium und Azure Active Directory Premium Plan 1 können von Richtlinien für bedingten Zugriff profitieren. Lizenzierte Benutzer von Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5, Microsoft E5 Security und Azure Active Directory Premium Plan 2 können von Identity Protection (risikobasierte Richtlinien für bedingten Zugriff) profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Analysten und Sicherheitsexperten für Sicherheitsvorgänge profitieren von der Möglichkeit, Organisationsrichtlinien für Benutzer zu erzwingen, damit sie bestimmte Kriterien erfüllen müssen, bevor sie Zugriff auf Unternehmensinhalte erhalten. Endbenutzer profitieren davon, dass sie überall und jederzeit auf ihre Arbeit zugreifen können und gleichzeitig die Ressourcen der Organisation schützen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind features für bedingten Zugriff auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Speziell für Identitätsschutz und bedingten Zugriff muss ein Benutzer in eine Gruppe eingeschlossen oder einer Richtlinie für bedingten Zugriff hinzugefügt werden. Die Benutzer- und Gruppenbedingung ist in einer Richtlinie für bedingten Zugriff obligatorisch. In Ihrer Richtlinie können Sie entweder alle **Benutzer** oder bestimmte Benutzer und Gruppen auswählen. Sie sollten nur entsprechend lizenzierte Benutzer und Gruppen auswählen. Weitere Informationen finden Sie unter [Conditional Access: Conditions](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Erweiterte Überwachung

Die erweiterte Überwachung in Microsoft 365 bietet eine einjährige Aufbewahrung von Überwachungsprotokollen für Benutzer- und Administratoraktivitäten und bietet die Möglichkeit, benutzerdefinierte Aufbewahrungsrichtlinien für Überwachungsprotokolle zu erstellen, um die Aufbewahrung von Überwachungsprotokollen für andere Microsoft 365-Dienste zu verwalten. Es bietet auch Zugriff auf wichtige Ereignisse für Untersuchungen und Zugriff mit hoher Bandbreite auf die Office 365-Verwaltungsaktivitäts-API. Weitere Informationen finden Sie unter [Advanced Audit in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

Sie können mit einer Add-On-SKU auch einen Aufbewahrungszeitraum von 10 Jahren aktivieren. Die Add-On-SKU wird ab Anfang 2021 benötigt.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance und Microsoft 365 eDiscovery und Überwachung können von der erweiterten Überwachung profitieren.

Lizenzierte Benutzer mit erweiterter Überwachung und dem 10-Jahres-Add-On "Überwachungsprotokollaufbewahrung" können von der 10-jahres-Überwachungsprotokollaufbewahrung profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von der erweiterten Überwachung, da Überwachungsdatensätze im Zusammenhang mit Benutzeraktivitäten in Microsoft 365-Diensten bis zu einem Jahr aufbewahrt werden können. Darüber hinaus werden hochwertige Überwachungsereignisse protokolliert, z. B. wenn auf Elemente im Postfach eines Benutzers zugegriffen oder gelesen wird. Weitere Informationen finden Sie unter [Advanced Audit in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig ist die erweiterte Überwachung auf Mandantenebene für alle Organisationen aktiviert, die über ein Office 365- oder Microsoft 365 E5-Abonnement verfügen, und bietet automatisch eine einjährige Aufbewahrung von Überwachungsprotokollen für Aktivitäten (die von Benutzern mit der entsprechenden Lizenz ausgeführt werden) in Azure Active Directory, Exchange und SharePoint. Darüber hinaus können Organisationen Aufbewahrungsrichtlinien für Überwachungsprotokolle verwenden, um den Aufbewahrungszeitraum für Überwachungsdatensätze zu verwalten, die durch Aktivitäten in anderen Microsoft 365-Diensten generiert wurden. Die Aufbewahrungsfunktion für Überwachungsprotokolle von 10 Jahren wird auch mithilfe derselben Aufbewahrungsrichtlinien aktiviert. Weitere Informationen finden Sie unter [Verwalten der Aufbewahrungsrichtlinien für Überwachungsprotokolle](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Die einjährige Aufbewahrung von Überwachungsprotokollen und die Überwachung wichtiger Ereignisse gelten nur für Benutzer mit der entsprechenden Lizenz. Darüber hinaus können Administratoren Aufbewahrungsrichtlinien für Überwachungsprotokolle verwenden, um kürzere Aufbewahrungsdauern für die Überwachungsprotokolle bestimmter Benutzer festzulegen.

Die 10-jahres-Aufbewahrung von Überwachungsprotokollen gilt nur für Benutzer mit der entsprechenden Add-On-Lizenz. Die Add-On-SKU ist ab Anfang 2021 erforderlich.
