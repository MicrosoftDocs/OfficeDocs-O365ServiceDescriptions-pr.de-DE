---
title: Microsoft 365-Lizenzierungs Leit Faden für Sicherheits & Compliance
ms.author: office365servicedesc
author: pamelaar
ms.reviewer: v-smandalika
audience: ITPro
ms.topic: reference
ms.date: 12/01/2020
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Dieser Artikel enthält eine Anleitung für die Lizenzierung von Microsoft 365, um mögliche Dienstunterbrechungen aufgrund von nicht lizenziertem Zugriff zu vermeiden.
ms.openlocfilehash: de9d26c576b4dd4e77e18db3b85068eff717b0c9
ms.sourcegitcommit: 7486b1573c592ec7b6356d2cdb070c866239cad5
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 12/11/2020
ms.locfileid: "49624556"
---
# <a name="microsoft-365-licensing-guidance-for-security--compliance"></a>Microsoft 365-Lizenzierungs Leit Faden für Sicherheits & Compliance

Für die Zwecke dieses Artikels handelt es sich bei einem Dienst auf Mandantenebene um einen Onlinedienst, der &mdash; beim Kauf für einen beliebigen Benutzer im Mandanten (eigenständig oder als Teil von Office 365-oder Microsoft 365-Plänen) &mdash; für alle Benutzer im Mandanten vollständig aktiviert wird. Auch wenn einige nicht lizenzierte Benutzer technisch möglicherweise auf den Dienst zugreifen können, ist eine Lizenz für jeden Benutzer erforderlich, den Sie vom Dienst nutzen möchten.

> [!NOTE]
> Einige Mandanten Dienste können derzeit keine Vorteile für bestimmte Benutzer einschränken. Es sollten Anstrengungen unternommen werden, um die Dienst Vorteile für lizenzierte Benutzer zu begrenzen. Auf diese Weise können potenzielle Dienstunterbrechungen in Ihrer Organisation vermieden werden, sobald die Zielfunktionen verfügbar sind.

Um die Optionen für die Lizenzierung von Benutzern zu erhalten, die von den Microsoft 365-Kompatibilitätsfunktionen ab dem 1. April 2020 profitieren, laden Sie den detaillierten Vergleich der Microsoft 365-Kompatibilitäts Lizenzierung herunter. [(PDF)](https://www.microsoft.com/download/details.aspx?id=102403)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=102427)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection ist ein Feature des Azure Active Directory Premium P2-Plans, mit dem Sie potenzielle Sicherheitsrisiken erkennen können, die sich auf die Identitäten Ihrer Organisation auswirken, automatisierte Antworten auf erkannte verdächtige Aktionen in Bezug auf die Identitäten Ihrer Organisation konfigurieren und verdächtige Vorfälle untersuchen und geeignete Maßnahmen zur Lösung dieser Vorgänge ergreifen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Analysten und Sicherheitsexperten von seepolizisten profitieren von konsolidierten Ansichten von gekennzeichneten Benutzern und Risikoereignissen basierend auf maschinellen Lernalgorithmen. Endbenutzer profitieren von dem automatischen Schutz, der durch risikobasierter bedingter Zugriff bereitgestellt wird, und der verbesserten Sicherheit durch das Handeln auf Schwachstellen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Kunden mit E1-und E3-Lizenzen können nur auf die standardmäßige Datenschutz-Basisbewertung zugreifen. Kunden mit Office 365 E5/a5-und Microsoft 365 E5/A5-Lizenzen (Compliance, Information Protection & Governance und eDiscovery und Audit-SKUs enthalten) können auf standardmäßigen Assessments für Datenschutz, dsgvo, NIST 800-53 und ISO 27001 zugreifen. Das benutzerdefinierte Bewertungsfeature und die Premium-Bewertungen sind für Office 365 E5/a5-und Microsoft 365 E5/A5-Kunden reserviert. Premium-Bewertungen können in der ersten Hälfte von 2021 bis zu VL, CSP und webdirect erworben werden. 

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Azure AD Identity Protection-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Azure AD Identitätsschutz finden Sie unter [Was ist Azure Active Directory Identity Protection?](https://docs.microsoft.com/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Azure AD Identitätsschutz festlegen, indem Sie Risikorichtlinien zuweisen, mit denen die Ebene für Kennwortzurücksetzungen definiert und der Zugriff nur für lizenzierte Benutzer zugelassen wird. Anweisungen zum Bereich Azure AD Identitätsschutz-Bereitstellungen finden Sie unter [configure the Sign-in Risk Policy](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Identity Governance

Azure Active Directory Identity Governance ermöglicht es Ihnen, den Bedarf Ihrer Organisation an Sicherheit und Mitarbeiterproduktivität mit den richtigen Prozessen und der Sichtbarkeit auszugleichen. Es verwendet Berechtigungsverwaltung, Zugriffsüberprüfungen, privilegiertes Identitätsmanagement und Nutzungsbedingungen, um sicherzustellen, dass die richtigen Personen über den richtigen Zugriff auf die richtigen Ressourcen verfügen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Azure Active Directory Identity Governance steigert die Produktivität von Benutzern, indem es einfacher wird, Zugriff auf apps, Gruppen und Microsoft Teams in einem einzigen Zugriffs Paket anzufordern. Benutzer können auch als genehmigende Personen konfiguriert werden, ohne Administratoren einzubeziehen. Für Zugriffsüberprüfungen können Benutzermitgliedschaften von Gruppen überprüfen, mit intelligenten Empfehlungen, um in regelmäßigen Intervallen Maßnahmen zu ergreifen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Azure Active Directory Premium Plan 2 bieten die Rechte für einen Benutzer, von Azure Active Directory Identity Governance zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Azure AD Identity Governance-Features werden auf Mandantenebene aktiviert, jedoch pro Benutzer implementiert. Informationen zur Azure AD Identitäts Steuerung finden Sie unter [Was ist Azure Active Directory Identity Governance?](https://docs.microsoft.com/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können einen Bereich Azure AD Identitäts Steuerung durch Zuweisen von Zugriffs Paketen, Zugriffsüberprüfungen oder privilegierter Identitätsverwaltung für lizenzierte Benutzer festlegen. Anweisungen zum Bereich Azure AD Identity Governance-Bereitstellungen finden Sie unter:

- [Lizenzanforderungen für Azure AD Berechtigungsverwaltung](https://docs.microsoft.com/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Lizenzanforderungen für Azure AD Access Review](https://docs.microsoft.com/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Lizenzanforderungen für die Verwendung der privilegierten Identitätsverwaltung](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (ehemals Azure Advanced Threat Protection) ist ein clouddienst, der Enterprise-Hybrid Umgebungen vor verschiedenen Arten von erweiterten Ziel-Cyber-Angriffen und Insiderbedrohungen schützt.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

SecOp-Analysten und Sicherheitsexperten profitieren von der Fähigkeit von Microsoft Defender for Identity, erweiterte Bedrohungen, kompromittierte Identitäten und böswillige Insider Aktionen zu erkennen und zu untersuchen. Endbenutzer profitieren davon, dass Ihre Daten von Microsoft Defender für Identity überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Microsoft Defender for Identity for users bieten die Rechte, von Microsoft Defender for Identity zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender for Identity-Funktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Azure ATP finden Sie unter [Create Your Microsoft Defender for Identity instance](https://docs.microsoft.com/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender for Identity Services kann derzeit nicht die Funktionen für bestimmte Benutzer einschränken. Sie müssen jeden Benutzer lizenzieren, den Sie nutzen möchten.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender für Office 365

Microsoft Defender für Office 365 (früher Office 365 Advanced Threat Protection) schützt Organisationen vor ausgeklügelten Angriffen wie Phishing und Zero-Day-Schadsoftware. Microsoft Defender für Office 365 bietet auch umsetzbare Einblicke, indem Sie Signale aus einer breiten Palette von Daten korreliert, um Sie bei der Identifizierung, Priorisierung und der Bereitstellung von Empfehlungen zur Lösung potenzieller Bedrohungen zu unterstützen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Microsoft Defender für Office 365 schützt Benutzer vor ausgeklügelten Angriffen wie Phishing und Zero-Day-Schadsoftware. Die vollständige Liste der in Plan 1 und Plan 2 bereitgestellten Dienste finden Sie unter [Microsoft Defender für Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp?view=o365-worldwide&preserve-view=true).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können? 

Microsoft Defender für Office 365 Pläne 1 und 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Sicherheit und Microsoft 365 Business Premium bieten die Rechte für einen Benutzer, von Microsoft Defender für Office 365 zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig ist Microsoft Defender für Office 365-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Microsoft Defender für Office 365-Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Defender für Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp?view=o365-worldwide&preserve-view=true).


### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Wenn Sie Microsoft Defender für Office 365 Bereich verwenden möchten, befolgten Sie die Bereitstellungsrichtlinien für sichere Links und sichere Anlagen:

- Informationen zum Konfigurieren von sicheren Links für lizenzierte Benutzer finden Sie unter [Einrichten von Microsoft Defender für Office 365 Richtlinien zu sicheren Links](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links?view=o365-worldwide&preserve-view=true).

- Informationen zum Konfigurieren sicherer Anlagen für lizenzierte Benutzer finden Sie unter [Einrichten von Microsoft Defender für Office 365 Richtlinien zu sicheren Anlagen](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-attachments?view=o365-worldwide&preserve-view=true).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud-App-Sicherheit (Ocas) ist eine Teilmenge der Microsoft Cloud-App-Sicherheit, wobei Features auf Office 365 und ohne zusätzliche Sicherheit für Cloud-apps von Drittanbietern und IaaS-Dienste eingeschränkt sind.

Ocas gibt Organisationen Einblick in Ihre Produktivitäts Cloud-apps und-Dienste, stellt ausgefeilte Analysen zum Identifizieren und bekämpfen von Cyber-Bedrohungen bereit und lässt Sie steuern, wie Daten &mdash; über Office 365 transportiert werden.

Informationen zum Vergleichen von Features finden Sie unter [Differences of Microsoft Cloud App Security and Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Ocas erkennt Shadow IT, bietet Schutz vor Bedrohungen in Office 365 und kann steuern, welche apps über die Berechtigung zum Zugriff auf Daten verfügen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Office 365 E5/a3/A5/G5 stellen die Rechte für einen Benutzer zur Verfügung, um von Ocas zu profitieren.
Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing-Datenblatt](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Ocas-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren des Diensts finden Sie unter [Basic Setup for Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Ocas-Bereitstellungen durchsetzen, um zu erzwingen, wie auf bestimmte apps zugegriffen wird, und um Benutzergruppen zu begrenzen, die von Office 365 Cloud-App-Sicherheit überwacht werden. Weitere Informationen finden Sie unter [bereichsbezogene Bereitstellung](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) ist eine CASB-Lösung (Cloud Access Security Broker), die Unternehmen Einblick in Ihre Cloud-apps und-Dienste gibt, hoch entwickelte Analysen zur Identifizierung und Bekämpfung von Cyber-Bedrohungen bietet und Ihnen die Steuerung der Datenübertragung &mdash; über eine Cloud-App ermöglicht.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

MCAS erkennt und beurteilt Shadow IT, bietet Schutz vor Bedrohungen für First-und Third-Party-Cloud-apps und schützt Informationen über Cloud-apps von erst-und Drittanbietern.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Sicherheit, Microsoft 365 E5/A5/G5-Compliance und Microsoft 365 Information Protection and Governance bieten die Rechte für einen Benutzer, von MCAS zu profitieren.

Azure AD P1 stellt die Rechte für einen Benutzer zur Verfügung, um von den Ermittlungsfunktionen in MCAS zu profitieren.

Um von den bedingten Zugriffsfunktionen für App-Steuerelemente in MCAS profitieren zu können, müssen die Benutzer auch für Azure Active Directory P1, die in Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Security enthalten ist,

Um von der automatischen Kennzeichnung profitieren zu können, müssen die Benutzer für Azure Information Protection P2 lizenziert sein, die in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance enthalten ist.

Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing-Datenblatt](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind MCAS-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren von Microsoft Cloud App-Sicherheitsrichtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Cloud App Security Overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können MCAS-Bereitstellungen für lizenzierte Benutzer mithilfe der im Dienst verfügbaren Bereitstellungsfunktionen für Bereiche bereitstellen. Weitere Informationen finden Sie unter [bereichsbezogene Bereitstellung](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="compliance-manager"></a>Compliance-Manager

Vereinfachung der Compliance und Reduzierung des Risikos mit Compliance-Manager. Compliance-Manager unterstützt Organisationen bei der Erfüllung von Vorschriften, Standards, Unternehmensrichtlinien oder anderen gewünschten Steuerungs Frameworks.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Im folgenden werden die Vorteile für die Benutzer des Compliance-Manager-Diensts erfüllt:

- Übersetzt komplizierte Regelungen, Standards, Unternehmensrichtlinien oder andere gewünschte Steuerungs Frameworks in eine einfache Sprache.
- Bietet Zugriff auf eine umfangreiche Bibliothek von vordefinierten Bewertungen und benutzerdefinierten Bewertungen zur Erfüllung eindeutiger Compliance-Anforderungen.
- Ordnet Regulierungs Kontrollen den empfohlenen Verbesserungs Aktionen zu
- Enthält schrittweise Anleitungen zum Implementieren der Lösungen zur Erfüllung behördlicher Anforderungen
- Unterstützt Benutzer bei der Priorisierung von Aktionen, die die höchste Auswirkung auf die Compliance Ihrer Organisation haben, indem eine Partitur mit jeder Aktion verknüpft wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Kunden mit Office 365 E5/a5-und Microsoft 365 E5/A5-Lizenzen können sofort auf die standardmäßigen Bewertungen von Datenschutz Basis, dsgvo, NIST 800-53 und ISO 27001 zugreifen und das benutzerdefinierte Bewertungsfeature verwenden. Premium-Bewertungen können in der ersten Hälfte von 2021 für Office 365 E5/a5-und Microsoft 365 E5/A5-Kunden erworben werden. Sie werden für den Erwerb über VL, CSP und webdirect zur Verfügung stehen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Compliance-Manager ist standardmäßig für Ihren Mandanten vorgesehen. Administratoren legen Benutzerberechtigungen fest und weisen Rollen zu, damit Benutzer von nicht-Administratoren in Ihrer Organisation mit dem Compliance-Manager beginnen können. Weitere Informationen finden Sie unter [Erste Schritte mit Compliance-Manager: Festlegen von Benutzerberechtigungen und Zuweisen von Rollen](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Der Zugriff auf den Compliance-Manager wird durch Festlegen von Benutzerberechtigungen und Zuweisen von Rollen gesteuert. Weitere Informationen finden Sie unter [Erste Schritte mit Compliance-Manager: Festlegen von Benutzerberechtigungen und Zuweisen von Rollen](https://docs.microsoft.com/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender für Endpunkt

Microsoft Defender for Endpoint (ehemals Microsoft Defender ATP) ist eine Endpunkt Sicherheitslösung, die risikobasierte Schwachstellen Verwaltung und-Bewertung umfasst. Funktionen zur angreifenden Oberflächenreduzierung; verhaltensbasierte und Cloud-gesteuerte Schutz für die nächste Generation; Endpunkterkennung und-Antwort (EDR); Automatische Untersuchung und Korrektur; und verwaltete Jagd Dienste. Weitere Informationen finden Sie unter [Microsoft Defender für Endpoint](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection) -Seite.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5 (M365 E5), einschließlich Windows 10 Enterprise E5, Microsoft 365 E5 Security, Microsoft 365 A5 (M365 a5) können von Microsoft Defender for Endpoint profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Analysten und Sicherheitsexperten von seepolizisten profitieren von Endpoint Security-Funktionen von Microsoft Defender für Endpoint für vorbeugenden Schutz, Erkennung nach einem Verstoß, automatische Untersuchung und Reaktion auf Erweiterte Bedrohungen. Endbenutzer profitieren davon, dass böswillige Ereignisse von Microsoft Defender für Endpoint überwacht werden.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender für Endpoint-Funktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zur Bereitstellung finden Sie unter [Bereitstellungshandbuch](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender für Endpunkt Administratoren kann Rollen [basierte Zugriffssteuerung (Role-Based Access Control, RBAC)](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/rbac) zum Erstellen von Rollen und Gruppen innerhalb des Teams für Sicherheitsvorgänge verwenden, um den entsprechenden Zugriff auf das Microsoft Defender-Sicherheits Center zu gewähren.

## <a name="information-protection"></a>Informationsschutz

Informationsschutz unterstützt Organisationen beim entdecken, klassifizieren, beschriften und Schützen vertraulicher Dokumente und e-Mails. Administratoren können Regeln und Bedingungen definieren, um Beschriftungen automatisch anzuwenden, Benutzer können Bezeichnungen manuell anwenden, oder eine Kombination der beiden kann verwendet werden, wobei Benutzern Empfehlungen zum Anwenden von Bezeichnungen gegeben werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren davon, dass Sie die Vertraulichkeits Bezeichnungen manuell auf Ihre Inhalte anwenden können oder dass Ihre Inhalte automatisch klassifiziert werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 und AIP Plan 2 bieten die Rechte für einen Benutzer, der von der manuellen Sensitivitäts Kennzeichnung profitiert.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 und AIP Plan 2 bieten die Rechte für einen Benutzer, von der Anwendung und Anzeige von Sensitivitäts Bezeichnungen in Power BI zu profitieren und Daten beim Export von Power BI nach Excel, PowerPoint oder PDF zu schützen. 

> [!NOTE]
> Power BI ist in Microsoft 365 E5/A5/G5 enthalten; in allen anderen Plänen muss Power BI separat lizenziert werden.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität, Microsoft 365 Information Protection und Governance, Office 365 E5, Office 365 Advanced Compliance, Enterprise Mobility + Security E5 und AIP Plan 2 bieten die Rechte für einen Benutzer, der von der automatischen Sensitivitäts Kennzeichnung profitiert.

Spezifische Rechte nach Lizenz finden Sie im ausführlichen Microsoft 365-Kompatibilitäts Lizenzierungs Vergleich. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Enthält keine Rechte für die automatische Klassifizierung basierend auf dem maschinellen lernen (Lernende Klassifizierungen).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Features für den Informationsschutz auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Richtlinien für lizenzierte Benutzer finden Sie unter Aktivieren von Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Außer bei Verwendung des AIP-Scanner-Features können Richtlinien auf bestimmte Gruppen oder Benutzer beschränkt werden, und Registrierungsfunktionen können bearbeitet werden, um zu verhindern, dass nicht lizenzierte Benutzer Klassifizierungs-oder Kennzeichnungsfeatures verwenden. Anweisungen zum Umfang von AIP-Bereitstellungen finden Sie unter [Konfigurieren der Azure Information Protection-Richtlinie](https://docs.microsoft.com/azure/information-protection/configure-policy).

Für das AIP-Scanner-Feature verpflichtet sich Microsoft nicht, Benutzern, die nicht lizenziert sind, die Datei Klassifizierung, Beschriftung oder Schutzfunktionen bereitzustellen.

## <a name="information-governance"></a>Information Governance

Die Informationssteuerung hilft Organisationen bei der Verwaltung Ihres Risikos, indem Sie Ihre Daten ermitteln, klassifizieren, bezeichnen und steuern. Mit der Information Governance können Unternehmen geschäftliche und behördliche Anforderungen erfüllen und die Angriffsfläche verringern, indem Sie Aufbewahrungs-und Löschfunktionen für Ihre Microsoft 365-und drittanbieterdaten bereitstellen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren davon, dass Sie Daten zu Aufbewahrungszwecken klassifizieren können, um bestimmte Richtlinien und Vorschriften aufrechtzuerhalten.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 F3/Business Premium, Office 365 E1/a1/F3 und eigenständige Exchange-Pläne bieten die Rechte für einen Benutzer, von der manuellen Anwendung von nicht-Daten Satz Aufbewahrungs Bezeichnungen auf Postfachdaten zu profitieren.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/a1/F3 und eigenständige SharePoint-Pläne bieten die Rechte für einen Benutzer, von der manuellen Verwendung von nicht-Daten Satz Aufbewahrungs Bezeichnungen für Dateien in SharePoint oder OneDrive profitieren zu können. 

Microsoft 365 E5/A5/E3/A3/Business Premium, Office 365 E5/A5/E3/A3, Exchange-Plan 2 und Exchange Online Archivierung bieten die Rechte für einen Benutzer, von einer grundlegenden organisationsweiten oder standortweiten Aufbewahrungsrichtlinie für Postfächer zu profitieren und/oder eine nicht-Daten Satz-Aufbewahrungs Bezeichnung auf Postfachdaten manuell anzuwenden.

Microsoft 365 E5/A5/E3/A3, Office 365 E5/A5/E3/a3 und SharePoint Plan 2 bieten die Rechte für einen Benutzer, von einer grundlegenden SharePoint-oder OneDrive-Aufbewahrungsrichtlinie zu profitieren und/oder eine nicht-Daten Satz Aufbewahrungs Bezeichnung manuell auf Dateien in SharePoint oder OneDrive anzuwenden.

Microsoft 365 E5/A5/E3/a3 und Office 365 E5/A5/E3/A3 stellen die Rechte für einen Benutzer zur Verfügung, um von einer Aufbewahrungsrichtlinie für Teams profitieren zu können.

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/a5 und Office 365 Advanced Compliance bieten die Rechte für einen Benutzer, von der automatischen Verwendung von Aufbewahrungs Bezeichnungen oder Richtlinien profitieren zu können. das Anwenden von standardmäßigen Aufbewahrungs Bezeichnungen oder Richtlinien, das Starten des Aufbewahrungszeitraums einer Aufbewahrungs Bezeichnung basierend auf einem benutzerdefinierten Ereignis, das Auslösen einer manuellen Dispositions Überprüfung am Ende des Aufbewahrungszeitraums, das Importieren von drittanbieterdaten über systemeigene Daten Konnektoren, das Deklarieren einer Datei als Datensatz, das Erkennen von beschriftetem Inhalt und das Überwachen von Beschriftungs Aktivitäten

Microsoft 365 E5/A5, Microsoft 365 E5/A5-Konformität, Microsoft 365-Informationsschutz und Steuerung bieten den Benutzern die Rechte, von der automatischen Beibehaltung von Aufbewahrungs Bezeichnungen basierend auf Schulungs Klassifizierern profitieren zu können.

Spezifische Rechte nach Lizenz finden Sie im ausführlichen Microsoft 365-Kompatibilitäts Lizenzierungs Vergleich. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Features für die Informationssteuerung auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren der Informationssteuerung für das Anwenden von autolabeling und Richtlinien für lizenzierte Benutzer finden Sie unter [Manage Information Governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Die Features für die Informationssteuerung können auf lizenzierte Benutzer an bestimmten Orten (Teamwebsites, Gruppen Websites usw.) angewendet werden. Informationen zum Konfigurieren der Informationssteuerung für das Anwenden von autolabeling und Richtlinien für lizenzierte Benutzer finden Sie unter [Manage Information Governance](https://docs.microsoft.com/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Datensatzverwaltung

Die Datensatzverwaltung unterstützt Organisationen bei der Erfüllung ihrer geschäftlichen und behördlichen Pflichten im Zusammenspiel mit der Ermittlung, Klassifizierung, Etikettierung, Aufbewahrung und vertretbaren Löschungs Funktionen in Ihren Microsoft 365-und drittanbieterdaten.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 E5/A5, Microsoft 365 E5/A5-Konformität, Microsoft 365 Information Protection and Governance, Office 365 E5/A5, Office 365 Advanced Compliance bieten die Rechte für einen Benutzer, von der Datensatzverwaltung zu profitieren, einschließlich Deklarieren von Elementen als Datensätze, automatisches Anwenden von Aufbewahrungs-oder Daten Satzbezeichnungen und Ausführen der Prozesse zur Dispositions Überprüfung (ohne automatisches Anwenden einer Aufbewahrungs Bezeichnung

Microsoft 365 E5/A5, Microsoft 365 E5/A5-Konformität, Microsoft 365-Informationsschutz und Steuerung bieten Benutzern die Rechte, von der automatischen Aufbewahrung oder von Daten Satzbezeichnungen basierend auf Schulungs Klassifizierern profitieren zu können.

Spezifische Rechte nach Lizenz finden Sie im ausführlichen Microsoft 365-Kompatibilitäts Lizenzierungs Vergleich. [(PDF)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](https://docs.microsoft.com/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren davon, dass Sie Inhalte als Datensatz deklarieren und Ihren vollständigen Daten Satz Prozess von der Richtliniendefinition und Deklaration bis zur vertretbaren Entsorgung verwalten können.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Datensatzverwaltungsfeatures auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren der Datensatzverwaltung zur Anwendung für lizenzierte Benutzer finden Sie unter [Datensatzverwaltung in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Die Datensatzverwaltungsfeatures können auf lizenzierte Benutzer an bestimmten Orten (Teamwebsites, Gruppen Websites usw.) angewendet werden. Informationen zum Konfigurieren der Datensatzverwaltung zur Anwendung für lizenzierte Benutzer finden Sie unter [Datensatzverwaltung in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Daten-Konnektoren 

Microsoft stellt Daten-Konnektoren von Drittanbietern bereit, die im Microsoft 365 Compliance Center konfiguriert werden können. Eine Liste der von Microsoft bereitgestellten Daten-Konnektoren finden Sie in der Tabelle " [Drittanbieter-Daten Konnektoren](https://docs.microsoft.com/microsoft-365/compliance/archiving-third-party-data) ". In dieser Tabelle werden auch die Kompatibilitätslösungen zusammengefasst, die Sie nach dem Importieren und Archivieren von Daten in Microsoft 365 auf drittanbieterdaten anwenden können, sowie Links zu den schrittweisen Anleitungen für jeden Connector.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Der primäre Vorteil der Verwendung von Daten Konnektoren zum Importieren und Archivieren von drittanbieterdaten in Microsoft 365 besteht darin, dass Sie verschiedene Microsoft 365-Kompatibilitätslösungen auf diese anwenden können, nachdem Sie importiert wurde. Dadurch wird sichergestellt, dass die nicht-Microsoft-Daten Ihrer Organisation den Vorschriften und Standards entsprechen, die sich auf Ihre Organisation auswirken.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Die folgenden Lizenzen bieten die Rechte für einen Benutzer, von den Daten Konnektoren zu profitieren:

- Microsoft 365 E5/a5
- Microsoft 365 E5/A5-Info Schutz & Governance
- Microsoft 365 E5/A5-Konformität
- Microsoft 365 E5/A5 Insider-Risiko Management
- Microsoft 365 E5/A5 eDiscovery und Überwachung
- Office 365 E5/a5
- Office 365 Advanced Compliance

Für Daten-Konnektoren im M365 Security & Compliance Center, die von einem der Partner von Microsoft bereitgestellt werden, benötigt Ihre Organisation eine Geschäftsbeziehung mit dem Partner, bevor Sie diese Connectors bereitstellen können.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Connectors werden mithilfe von Security & Compliance Center und Connector Catalog konfiguriert.

### <a name="how-can-the-service-be-applied-only---to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Data Connectors-Dienste sind ein Wert auf Mandantenebene. Jeder Benutzer, der von diesem Dienst profitieren soll, muss lizenziert sein.

## <a name="microsoft-graph-apis-for-teams-dlp"></a>Microsoft Graph-APIs für Teams DLP

Anfang dieses Jahres haben wir [die öffentliche Vorschau der Microsoft Graph-Änderungs Benachrichtigungs-API für Nachrichten in Teams angekündigt](https://go.microsoft.com/fwlink/?linkid=2143888). Mit dieser API können Entwickler apps erstellen, die Microsoft Teams-Nachrichten in nahezu Echtzeit abhören und DLP-Szenario-Implementierungen sowohl für Kunden als auch für ISVs aktivieren. Darüber hinaus können mit der Microsoft Graph-Patch-API DLP-Aktionen auf Teams-Nachrichten angewendet werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Die Funktionen zur [Verhinderung von Datenverlust (Data Loss Prevention, DLP)](https://docs.microsoft.com/microsoft-365/compliance/dlp-microsoft-teams) werden in Microsoft Teams häufig verwendet, zumal sich Organisationen zu Remote Arbeit verschoben haben. Wenn Ihre Organisation über DLP verfügt, können Sie jetzt Richtlinien definieren, die verhindern, dass Personen vertrauliche Informationen in einem Microsoft Teams-Kanal oder in einer Chatsitzung freigeben.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Sie benötigen eine der folgenden E5-Lizenzen, um Unterstützung für den Schutz vor Datenverlust (Data Loss Prevention, DLP) im Microsoft Teams-Chat zu erhalten:

- Microsoft 365 E5/a5
- Microsoft 365 E5/A5-Konformität
- Microsoft 365 E5/A5 Information Protection and Governance
- Office 365 E5/a5 

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Der API-Zugriff wird auf Mandantenebene konfiguriert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Die Microsoft Graph-API für Teams DLP ist ein Wert auf Mandantenebene. Jeder Benutzer, der von diesem Dienst profitieren soll, muss lizenziert sein.

## <a name="ediscovery"></a>eDiscovery

eDiscovery stellt Ermittlungs-und eDiscovery-Lösungen für IT-Abteilungen und Rechtsabteilungen in Unternehmen bereit, um Inhalte im Zusammenhang mit einer Untersuchung oder einem Rechtsstreit vor dem Export aus dem Microsoft 365-System zu identifizieren, zu sammeln, aufzubewahren, zu reduzieren und zu überprüfen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Ein Benutzer profitiert von Advanced eDiscovery, wenn der Benutzer als Datenverwalter (eine Person mit administrativer Kontrolle über ein Dokument oder eine elektronische Datei) für einen Fall ausgewählt ist.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 und Office 365 Advanced Compliance bieten die Rechte für einen Benutzer, der von der zentralen eDiscovery profitieren kann.
Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität, Microsoft 365 E5/A5 eDiscovery und Überwachung, Office 365 E5/A5/G5 und Office 365 Advanced Compliance bieten die Rechte für einen Benutzer, der von Advanced eDiscovery profitieren kann.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig werden erweiterte eDiscovery-Funktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert, wenn Administratoren eDiscovery-Berechtigungen im Security & Compliance Center zuweisen.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

eDiscovery-Administratoren können bestimmte Benutzer als Datenverwalter für einen Fall auswählen, indem Sie das integrierte Depot Verwaltungstool in Advanced eDiscovery verwenden, wie unter [Add depotbanks to a Advanced eDiscovery Case](https://docs.microsoft.com/microsoft-365/compliance/add-custodians-to-case)beschrieben.

## <a name="office-365-customer-key"></a>Office 365-Kundenschlüssel

Mit dem Kundenschlüssel steuern Sie die Verschlüsselungsschlüssel Ihrer Organisation und konfigurieren Office 365, damit Sie Ihre Daten im Ruhezustand in den Microsoft-Rechenzentren verschlüsseln können. Mit anderen Worten: mit dem Kundenschlüssel können Sie eine Verschlüsselungsebene hinzufügen, die Ihnen gehört, wobei Sie eigene Schlüssel verwenden. Zu den Daten im Ruhezustand gehören Daten aus Exchange Online und Skype for Business, die in Postfächern und Dateien in SharePoint Online und OneDrive für Unternehmen gespeichert werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren vom Kundenschlüssel, indem Sie Ihre Daten auf der Anwendungsebene mithilfe von Verschlüsselungsschlüsseln, die von ihrer eigenen Organisation bereitgestellt, gesteuert und verwaltet werden, in Ruhe verschlüsseln.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/a5 und Office 365 Advanced Compliance bieten die Rechte für einen Benutzer, vom Kundenschlüssel zu profitieren. Um den vollen Nutzen aus dem Kundenschlüssel zu ziehen, müssen Sie auch über ein Abonnement für Azure Key Vault verfügen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Office 365 Verschlüsselungsschlüssel für Kundenschlüssel können für alle Daten aktiviert werden, die in Exchange Online-und Skype for Business-Postfächern sowie in SharePoint Online-, OneDrive für Unternehmen-und Microsoft Teams-Dateien gespeichert sind. Weitere Informationen zum Office 365-Kundenschlüssel sowie zu den ersten Schritten finden Sie unter [Dienst Verschlüsselung mit Kundenschlüssel in Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Für Exchange Online und Skype for Business können Postfächer mit dem Kundenschlüssel verschlüsselt werden. Sie müssen Azure einrichten, bevor Sie Customer Key für Office 365 verwenden können. Unter [Einrichten des Kunden Schlüssels](https://docs.microsoft.com/microsoft-365/compliance/customer-key-set-up) finden Sie die Schritte, die Sie zum Erstellen und Konfigurieren der erforderlichen Azure-Ressourcen und der Schritte zum Einrichten von Kundenschlüssel in Office 365 durchführen müssen. Nachdem Sie das Azure-Setup abgeschlossen haben, legen Sie fest, welche Richtlinie und daher welche Schlüssel zu Postfächern und Dateien in Ihrer Organisation zugewiesen werden sollen. Für Postfächer und Dateien, denen Sie keine Richtlinie zuweisen, werden Verschlüsselungsrichtlinien verwendet, die von Microsoft gesteuert und verwaltet werden. Weitere Informationen zum Kundenschlüssel oder eine allgemeine Übersicht finden Sie unter [Dienst Verschlüsselung mit Kundenschlüssel in Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-key-overview).

## <a name="office-365-customer-lockbox"></a>Office 365-Kunden-Lockbox

Kunden-Lockbox bietet eine zusätzliche Kontrollschicht, indem Kunden die Möglichkeit bieten, explizite Zugriffsautorisierung für Dienstvorgänge zu erteilen. Durch den Nachweis, dass Verfahren für die explizite Datenzugriffs Autorisierung vorhanden sind, kann die Customer Lockbox auch Organisationen dabei helfen, bestimmte Compliance-Verpflichtungen wie HIPAA und FEDRAMP zu erfüllen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von Lockbox-Kunden, die sicherstellen, dass niemand bei Microsoft auf Ihre Inhalte zugreifen kann, um einen Dienstvorgang ohne explizite Genehmigung des Kunden auszuführen. Kunden-Lockbox bringt den Kunden in den Genehmigungsworkflow für Anforderungen für den Zugriff auf Ihre Inhalte. Gelegentlich werden Microsoft-Techniker während des Supportprozesses zur Problembehandlung und zum Beheben von von Kunden gemeldeten Problemen beteiligt. In den meisten Fällen werden Probleme durch umfangreiche Telemetrie-und Debugging-Tools behoben, die Microsoft für seine Dienste implementiert hat. Es kann jedoch vorkommen, dass ein Microsoft-Techniker den Zugriff auf Kunden Inhalte erfordert, um die Ursache zu ermitteln und das Problem zu beheben. Kunden-Lockbox setzt voraus, dass der Techniker den Zugriff vom Kunden als letzten Schritt im Genehmigungsworkflow anfordert. Dadurch erhalten Organisationen die Möglichkeit, diese Anforderungen zu genehmigen oder abzulehnen, sodass Sie direkt steuern können, ob ein Microsoft-Techniker auf die Endbenutzerdaten der Organisation zugreifen kann.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Compliance, Microsoft 365 Insider Risk Management und Office 365 Advanced Compliance bieten die Rechte für einen Benutzer, von der kundensperre zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren können Kunden-Lockbox-Steuerelemente im Microsoft 365 Admin Center aktivieren. Weitere Informationen finden Sie unter [Customer Lockbox in Office 365](https://docs.microsoft.com/microsoft-365/compliance/customer-lockbox-requests). Wenn die Kunden-Lockbox aktiviert ist, muss Microsoft vor dem Zugriff auf Inhalte eine Organisation genehmigen.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Der Kunden-Lockbox-Dienst kann derzeit nicht auf bestimmte Benutzer limitiert werden. Sie müssen jeden Benutzer lizenzieren, den Sie nutzen möchten.

## <a name="privileged-access-management-in-office-365"></a>Privileged Access Management in Office 365

Die [privilegierte Zugriffsverwaltung (Access Management, PAM)](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration) bietet granulare Zugriffssteuerung für privilegierte Verwaltungsaufgaben in Office 365. Nachdem Sie PAM aktiviert haben, müssen Benutzer Just-in-Time-Zugriff über einen Genehmigungsworkflow anfordern, der sehr umfangreich und Zeit gebunden ist, um erhöhte und privilegierte Aufgaben auszuführen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Durch die Aktivierung von PAM können Organisationen mit NULL stehenden rechten arbeiten. Benutzer profitieren von der zusätzlichen Verteidigungsstufe gegen Sicherheitsrisiken, die sich aus dem ständigen administrativen Zugriff ergeben, der den ungehinderten Zugriff auf Ihre Daten ermöglicht.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und Microsoft 365 E5/A5 Information Protection and Governance bieten die Rechte für einen Benutzer, von PAM zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig werden PAM-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von PAM-Richtlinien finden Sie unter [Erste Schritte mit privilegierter Zugriffsverwaltung](https://docs.microsoft.com/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Kunden können PAM auf Benutzerebene über die genehmigende Gruppe und Zugriffsrichtlinien verwalten, die auf lizenzierte Benutzer angewendet werden können. Weitere Informationen finden Sie unter [privileged Access Management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Doppelschlüssel Verschlüsselung für Microsoft 365 

Mit der Doppelschlüssel Verschlüsselung für Microsoft 365 können Sie Ihre hochsensiblen Daten schützen, um spezielle Anforderungen zu erfüllen, und die vollständige Kontrolle über Ihren Verschlüsselungsschlüssel erhalten. Die Doppelschlüssel Verschlüsselung verwendet zwei Schlüssel, um Ihre Daten zu schützen, wobei ein Schlüssel in Ihrem Steuerelement und der zweite Schlüssel sicher Microsoft Azure gespeichert werden. Zum Anzeigen der Daten benötigen Sie Zugriff auf beide Schlüssel. Da Microsoft nur auf einen Schlüssel zugreifen kann, stehen Ihr Schlüssel und auch Ihre Daten für Microsoft nicht zur Verfügung, um sicherzustellen, dass Sie Vollzugriff auf den Datenschutz und die Sicherheit Ihrer Daten haben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von der doppelten Schlüssel Verschlüsselung, indem Sie Ihre verschlüsselten Daten in die Cloud migrieren und den Zugriff durch Drittanbieter verhindern können, solange der Schlüssel die Kontrolle über die Benutzer behält. Endbenutzer können doppelt Schlüssel verschlüsselte Inhalte wie andere geschützte Inhalte mit Vertraulichkeits Bezeichnungen schützen und verwenden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance, Office 365 E5/a5 und Office 365 Advanced Compliance bieten die Rechte für einen Benutzer, um von der doppelten Schlüssel Verschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Die Doppelschlüssel Verschlüsselung unterstützt die Desktop Version von Microsoft Office für Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Wenn Sie den Daten in einer Office 365-und/oder Microsoft 365-Organisation für lizenzierte Benutzer Verschlüsselungsschlüssel zuweisen möchten, befolgen Sie die Anweisungen zur Bereitstellung der doppelten Schlüssel Verschlüsselung.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 Verhinderung von Datenverlust für Exchange Online, SharePoint Online und OneDrive für Unternehmen

Mit Office 365 Verhinderung von Datenverlust (DLP) für Exchange Online, SharePoint Online und OneDrive für Unternehmen können Unternehmen vertrauliche Informationen in e-Mails und Dateien (einschließlich Dateien, die in Microsoft Teams-Datei Repositorys gespeichert sind) identifizieren, überwachen und automatisch schützen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von DLP für Exchange Online, SharePoint Online und OneDrive für Unternehmen, wenn Ihre e-Mails und Dateien auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 a1/E3/A3/Business, Office 365 E3/a3 und Office 365 Verhinderung von Datenverlust bieten die Rechte für einen Benutzer, der von Office 365 DLP für Exchange Online, SharePoint Online und OneDrive für Unternehmen profitieren kann.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Exchange Online-e-Mails, SharePoint-Websites und OneDrive-Konten *Standorte (Arbeitslasten)* für diese DLP-Funktionen für alle Benutzer innerhalb des Mandanten aktiviert. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie unter [Übersicht über Verhinderung von Datenverlust](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Arbeitslasten), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security & Compliance Center unter **Verhinderung von Datenverlust** anpassen  >  .

## <a name="communication-data-loss-prevention-for-teams"></a>Verhinderung von Kommunikationsdaten Verlust für Teams

Mit der Kommunikation DLP für Teams können Organisationen Chats und Kanal Nachrichten blockieren, die vertrauliche Informationen enthalten, beispielsweise Finanzinformationen, personenbezogene Informationen, gesundheitsbezogene Informationen oder andere vertrauliche Informationen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 Information Protection and Governance und Office 365 Advanced Compliance können von der Kommunikations-DLP für Teams profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Absender profitieren davon, dass vertrauliche Informationen in Ihren ausgehenden Chat-und Kanal Nachrichten auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Teams-Chat und Kanal Nachrichten ein *aktivierter Speicherort (Arbeitsauslastung)* für diese DLP-Funktionen für alle Benutzer innerhalb des Mandanten. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie unter [Übersicht über Verhinderung von Datenverlust](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Arbeitslasten), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security & Compliance Center unter **Verhinderung von Datenverlust** anpassen  >  .

## <a name="information-barriers"></a>Informationsbarrieren

Informationsbarrieren sind Richtlinien, die ein Administrator konfigurieren kann, um zu verhindern, dass einzelne Personen oder Gruppen miteinander kommunizieren. Dies ist hilfreich, wenn beispielsweise eine Abteilung Informationen verarbeitet, die nicht für andere Abteilungen freigegeben werden sollten, oder wenn eine Gruppe nicht mit externen Kontakten kommunizieren muss. Richtlinien für Informationsbarrieren verhindern auch Nachschlagevorgänge und Ermittlungen. Dies bedeutet, dass Sie diesen Benutzer nicht in der Personenauswahl finden, wenn Sie versuchen, mit einer Person zu kommunizieren, mit der Sie nicht kommunizieren sollten.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von den erweiterten Kompatibilitätsfunktionen von Informationsbarrieren, wenn Sie von der Kommunikation mit anderen Personen eingeschränkt werden. Zum Beispiel:<br><br>

| Szenario | Wer benötigt eine Lizenz? |
|:------|:------|:------|
| Zwei Gruppen (Gruppe &nbsp; 1 und Gruppe &nbsp; 2) können nicht miteinander kommunizieren (das heißt, die &nbsp; Benutzer von Gruppe 1 dürfen nicht mit Gruppen &nbsp; 2-Benutzern kommunizieren, und Gruppen 2-Benutzer &nbsp; sind von der Kommunikation mit Gruppen &nbsp; 1-Benutzern beschränkt. | Benutzer in Gruppe &nbsp; 1 und Gruppe &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Insider Risk Management, Office 365 E5/a5 und Office 365 Advanced Compliance bieten die Rechte für einen Benutzer, um von Informationsbarrieren zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Richtlinien für Informationsbarrieren mithilfe von PowerShell-Cmdlets im Security & Compliance Center. Administratoren muss die Rolle Microsoft 365 Enterprise Global Administrator, Office 365 globaler Administrator oder Administrator für die Konformitätsrichtlinie zugewiesen sein, um eine Informations Barriere-Richtlinie zu erstellen. Standardmäßig gelten diese Richtlinien für alle Benutzer im Mandanten. Weitere Informationen zu Informationsbarrieren finden Sie unter [Information Barriers in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Standorte (Arbeitsauslastungen), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security & Compliance Center anpassen. Wenn beispielsweise alle Benutzer für Office 365 E3 lizenziert sind und keine für Office 365 Advanced Compliance/E5 lizenziert ist, müssen keine Richtlinien für Informationsbarrieren für die Organisation erstellt werden. Weitere Informationen finden Sie unter [Information Barriers in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

Office 365-Nachrichtenverschlüsselung (Office Message Encryption, OME) ist ein Dienst, der auf Azure Rights Management (Azure RMS) aufbaut und mit dem Sie verschlüsselte E-Mails an Personen innerhalb oder außerhalb Ihrer Organisation senden können, unabhängig von der E-Mail-Zieladresse (Gmail, Yahoo! Mail, Outlook.com usw.).

Zum Anzeigen verschlüsselter Nachrichten können Empfänger eine einmalige Kennung abrufen, sich mit einem Microsoft-Konto anmelden oder sich mit einem Geschäfts-, Schul- oder Unikonto, das Office 365 zugeordnet ist, anmelden. Empfänger können auch verschlüsselte Antworten senden. Sie benötigen kein Abonnement, um verschlüsselte Nachrichten anzuzeigen oder verschlüsselte Antworten zu senden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Nachrichtenabsender profitieren von der zusätzlichen Kontrolle über vertrauliche e-Mails, die von Office 365 Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 E3/A3, Office 365 E3/a3 und Azure Information Protection Plan 1 bieten die Rechte für einen Benutzer, um von Office 365 Nachrichtenverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Office 365 Nachrichten Verschlüsselungsrichtlinien im Exchange Admin Center unter **Nachrichtenfluss**  >  **Regeln**. Diese Regeln gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Office 365 Nachrichten Verschlüsselungsfunktionen finden Sie unter [Einrichten neuer Office 365 Nachrichten Verschlüsselungsfunktionen](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenfluss Regeln für Office 365 Nachrichtenverschlüsselung nur für lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenfluss Regeln finden Sie unter [Definieren von Nachrichtenfluss Regeln zum Verschlüsseln von e-Mail-Nachrichten in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Erweiterte Office 365-Nachrichtenverschlüsselung

Office 365 erweiterte Nachrichtenverschlüsselung hilft Kunden bei der Erfüllung von Compliance-Verpflichtungen, die flexiblere Kontrollen externer Empfänger und deren Zugriff auf verschlüsselte e-Mails erfordern. Mit der erweiterten Nachrichtenverschlüsselung können Administratoren vertrauliche und außerhalb der Organisation freigegebene e-Mails mithilfe automatischer Richtlinien steuern, die vertrauliche Informationstypen erkennen können (beispielsweise personenbezogene Informationen oder finanzielle oder gesundheitliche IDs), oder Sie können Schlüsselwörter verwenden, um den Schutz zu verbessern, indem Sie benutzerdefinierte e-Mail-Vorlagen und ablaufenden Zugriff auf verschlüsselte e-Mails über ein Darüber hinaus können Administratoren verschlüsselte e-Mails, auf die extern über ein sicheres Webportal zugegriffen wird, weiter steuern, indem Sie den Zugriff jederzeit widerrufen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Nachrichtenabsender profitieren von der zusätzlichen Kontrolle über vertrauliche e-Mails, die von der erweiterten Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance, Microsoft 365 Information Protection and Governance und Office 365 Advanced Compliance bieten die Rechte für einen Benutzer, um von der erweiterten Nachrichtenverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten erweiterte Nachrichten Verschlüsselungsrichtlinien im Exchange Admin Center unter Nachrichtenfluss Regeln. Diese Regeln gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Nachrichten Verschlüsselungsfunktionen finden Sie unter [Einrichten neuer Office 365 Nachrichten Verschlüsselungsfunktionen](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenfluss Regeln für erweiterte Nachrichtenverschlüsselung nur für lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenfluss Regeln finden Sie unter [Definieren von Nachrichtenfluss Regeln zum Verschlüsseln von e-Mail-Nachrichten in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Kommunikationscompliance

Die Kommunikations Kompatibilität in Microsoft 365 hilft, Kommunikationsrisiken zu minimieren, indem Sie Sie bei der Erkennung, Erfassung und Durchführung von Korrekturaktionen für ungeeignete Nachrichten in Ihrer Organisation unterstützen. Sie können bestimmte Richtlinien definieren, die interne und externe e-Mails, Microsoft Teams oder Drittanbieter Kommunikationen in Ihrer Organisation erfassen. Bearbeiter können geeignete Korrekturaktionen durchführen, um sicherzustellen, dass Sie mit den Nachrichtenstandards Ihrer Organisation konform sind.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Compliance-Experten profitieren vom Dienst, indem Sie die Organisationskommunikation durch Kommunikationsrichtlinien überwachen lassen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und Microsoft 365 Insider Risk Management bieten die Rechte für einen Benutzer, um von der Kommunikations Konformität zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren und Compliance-Experten erstellen Kommunikationsrichtlinien für Compliance im Microsoft 365 Compliance Center. Diese Richtlinien definieren, welche Kommunikationen und Benutzer in der Organisation überprüft werden sollen, definieren benutzerdefinierte Bedingungen, denen die Kommunikation entsprechen muss, und geben an, wer Überprüfungen durchführen soll.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren wählen bestimmte Benutzer oder Gruppen aus, die in eine Kommunikations Konformitätsrichtlinie eingeschlossen werden sollen. Bei der Auswahl einer Gruppe können Sie auch bestimmte Benutzer in der Gruppe auswählen, die von der Kommunikations Konformitätsrichtlinie ausgeschlossen werden sollen. Weitere Informationen zu Compliance-Richtlinien für die Kommunikation finden Sie unter [Communication Compliance in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Insider-Risikomanagement

Das Insider Risk Management ist eine Lösung in Microsoft 365, mit der interne Risiken minimiert werden, indem Sie riskante Aktivitäten in Ihrer Organisation erkennen, untersuchen und Maßnahmen ergreifen können.
Mit benutzerdefinierten Richtlinien können Sie böswillige und versehentlich riskante Aktivitäten in Ihrer Organisation erkennen und Maßnahmen ergreifen, einschließlich eskalierenden Fällen an Microsoft Advanced eDiscovery bei Bedarf. Risikoanalysten in Ihrer Organisation können schnell geeignete Maßnahmen ergreifen, um sicherzustellen, dass Benutzer mit den Compliance-Standards Ihrer Organisation konform sind.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren davon, dass ihre Aktivitäten auf das Risiko überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten die Rechte, damit ein Benutzer vom Dienst profitieren können?

Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und das Insider Risikomanagement von Microsoft 365 bieten die Rechte für einen Benutzer, um vom Insider Risikomanagement zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Richtlinien für das Insider Risiko Management müssen im Microsoft 365 Compliance Center erstellt und Benutzern zugewiesen werden.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Wählen Sie beim Erstellen einer Richtlinie im Microsoft 365 Compliance Center auf der Seite **Benutzer und Gruppen** auswählen die Option **Benutzer oder Gruppen** auswählen aus, um nur lizenzierte Benutzer auszuwählen, oder, wenn alle Ihre Benutzer lizenziert sind, können Sie das Kontrollkästchen **alle Benutzer und e-Mail-aktivierte Gruppen** aktivieren. Weitere Informationen finden Sie unter [Erste Schritte mit dem Insider Risikomanagement](https://docs.microsoft.com/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Richtlinien für bedingten Zugriff

Bedingter Zugriff ist das Tool, das von Azure Active Directory verwendet wird, um Signale zusammenzuführen, Entscheidungen zu treffen und Organisationsrichtlinien durchzusetzen. Der bedingte Zugriff steht im Mittelpunkt der Identitäts gesteuerten Steuerungsebene. Richtlinien für den bedingten Zugriff am einfachsten sind If-Then-Anweisungen. Wenn ein Benutzer auf eine Ressource zugreifen möchte, muss er eine Aktion abschließen. Beispiel: ein Abrechnungs Manager möchte auf die Lohn-und Gehaltsabrechnung zugreifen und muss mehrstufige Authentifizierung für den Zugriff auf die Anwendung ausführen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium und Azure Active Directory Premium-Plan 1 können von bedingten Zugriffsrichtlinien profitieren. Lizenzierte Benutzer von Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5, Microsoft E5 Security und Azure Active Directory Premium-Plan 2 können vom Identitätsschutz (risikobasierte Richtlinien für bedingten Zugriff) profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Security Operations Analysten und Sicherheitsexperten profitieren von der Möglichkeit, Organisationsrichtlinien für Benutzer durchzusetzen, sodass Sie bestimmte Kriterien erfüllen müssen, bevor Sie Zugriff auf Unternehmensinhalte gewähren. Endbenutzer profitieren davon, dass Sie jederzeit und überall auf Ihre Arbeit zugreifen können, während Sie die Ressourcen des Unternehmens schützen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Funktionen für bedingten Zugriff auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Für den Identitätsschutz und den bedingten Zugriff muss ein Benutzer in einer Gruppe enthalten sein oder einer Richtlinie für bedingten Zugriff hinzugefügt werden. Die Bedingung "Benutzer und Gruppen" ist in einer Richtlinie für den bedingten Zugriff obligatorisch. In Ihrer Richtlinie können Sie entweder **alle Benutzer** oder bestimmte Benutzer und Gruppen auswählen. Sie sollten nur entsprechend lizenzierte Benutzer und Gruppen auswählen. Weitere Informationen finden Sie unter [Was sind Bedingungen in Azure Active Directory bedingter Zugriff?](https://docs.microsoft.com/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Erweiterte Überwachung

Advanced Audit in Microsoft 365 bietet eine einjährige Aufbewahrung von Überwachungsprotokollen für Benutzer-und Administratoraktivitäten und bietet die Möglichkeit, benutzerdefinierte Aufbewahrungsrichtlinien für Überwachungsprotokolle zu erstellen, um die Überwachungsprotokoll Aufbewahrung für andere Microsoft 365-Dienste zu verwalten. Es bietet auch Zugriff auf wichtige Ereignisse für Untersuchungen und Zugriff auf die Office 365 Verwaltungs Aktivitäts-API mit hoher Bandbreite. Weitere Informationen finden Sie unter [Advanced Audit in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

Sie können auch eine Beibehaltungsdauer von 10 Jahren mit einer Add-on-SKU aktivieren. Die Add-on-SKU wird ab Anfang 2021 benötigt.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5, Microsoft 365 E5, Microsoft 365 E5 Compliance und Microsoft 365 eDiscovery und Audit können von der erweiterten Überwachung profitieren.

Lizenzierte Benutzer mit erweiterter Überwachung und das 10-jährige Add-on für die Überwachungsprotokoll Aufbewahrung können von einer zehnjährigen Überwachungsprotokoll Aufbewahrung profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Ein Benutzer profitiert von der erweiterten Überwachung, da Überwachungseinträge im Zusammenhang mit Benutzeraktivitäten in Microsoft 365-Diensten bis zu einem Jahr aufbewahrt werden können. Darüber hinaus werden hochwertige Überwachungsereignisse protokolliert, beispielsweise wenn auf Elemente im Postfach eines Benutzers zugegriffen oder gelesen wird. Weitere Informationen finden Sie unter [Advanced Audit in Microsoft 365](https://docs.microsoft.com/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig ist die erweiterte Überwachung auf Mandantenebene für alle Organisationen aktiviert, die über ein Office 365-oder Microsoft 365 E5-Abonnement verfügen, und bietet automatisch eine einjährige Aufbewahrung der Überwachungsprotokolle für Aktivitäten (durchgeführt von Benutzern mit der entsprechenden Lizenz) in Azure Active Directory, Exchange und SharePoint. Darüber hinaus können Organisationen Überwachungsprotokoll-Aufbewahrungsrichtlinien verwenden, um den Aufbewahrungszeitraum für Überwachungsdatensätze zu verwalten, die von Aktivitäten in anderen Microsoft 365-Diensten generiert werden. Die 10-jährige Überwachungsprotokoll-Aufbewahrungsfunktion wird ebenfalls mithilfe der gleichen Aufbewahrungsrichtlinien aktiviert. Weitere Informationen finden Sie unter [Verwalten der Aufbewahrungsrichtlinien für Überwachungsprotokolle](https://docs.microsoft.com/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Das einjährige aufbewahren von Überwachungsprotokollen und die Überwachung wichtiger Ereignisse gelten nur für Benutzer mit der entsprechenden Lizenz. Darüber hinaus können Administratoren Überwachungsprotokoll-Aufbewahrungsrichtlinien verwenden, um kürzere Aufbewahrungsdauer für die Überwachungsprotokolle bestimmter Benutzer anzugeben.

die Aufbewahrung von Überwachungsprotokollen in 10 Jahren gilt nur für Benutzer mit der entsprechenden Add-on-Lizenz. Die Add-on-SKU wird ab Anfang 2021 benötigt.
