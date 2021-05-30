---
title: Microsoft 365 lizenzierungsanleitung für & Compliance
ms.author: office365servicedesc
author: pamelaar
manager: gailw
ms.reviewer: v-trscho
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Dieser Artikel enthält Lizenzierungsanleitungen für Microsoft 365 Compliance, um potenzielle Dienstunterbrechungen aufgrund des nicht lizenzierten Zugriffs zu vermeiden.
ms.openlocfilehash: d1bbf0d60d78d12d0d48ce909dba72ef2478a0c0
ms.sourcegitcommit: b1b852bcef2c7ae0bdce8ca4ae5d3eafe9b454b3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/28/2021
ms.locfileid: "52699061"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Microsoft 365 lizenzierungsanleitung für die &amp; Sicherheitskonformität

Für die Zwecke dieses Artikels ist ein Dienst auf Mandantenebene ein Onlinedienst, der beim Kauf für einen beliebigen Benutzer im Mandanten (eigenständig oder als Teil von Office 365- oder Microsoft 365-Plänen) für alle Benutzer im Mandanten teilweise oder vollständig aktiviert &mdash; &mdash; wird. Obwohl einige nicht lizenzierte Benutzer technisch auf den Dienst zugreifen können, ist eine Lizenz für jeden Benutzer erforderlich, von dem Sie den Dienst nutzen möchten.

> [!NOTE]
> Einige Mandantendienste sind derzeit nicht in der Lage, die Vorteile auf bestimmte Benutzer zu beschränken. Es sollten Anstrengungen unternommen werden, um die Dienstvorteile auf lizenzierte Benutzer zu beschränken. Dies hilft Ihnen, potenzielle Dienstunterbrechungen in Ihrer Organisation zu vermeiden, sobald Zielgruppenfunktionen verfügbar sind.

Laden Sie die Tabelle Microsoft 365 Vergleich herunter Microsoft 365, um die Optionen für die Lizenzierung Ihrer Microsoft 365 [zu sehen.](https://go.microsoft.com/fwlink/?linkid=2139145)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection ist ein Feature des Azure Active Directory Premium-P2-Plans, mit dem Sie potenzielle Sicherheitsrisiken erkennen können, die sich auf die Identität Ihrer Organisation ausdingen, automatisierte Antworten auf erkannte verdächtige Aktionen im Zusammenhang mit den Identitäten Ihrer Organisation konfigurieren und verdächtige Vorfälle untersuchen und geeignete Maßnahmen ergreifen, um sie zu beheben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

SecOps-Analysten und Sicherheitsexperten profitieren von konsolidierten Ansichten gekennzeichneter Benutzer und Risikoereignissen basierend auf Algorithmen für maschinelles Lernen. Endbenutzer profitieren von dem automatischen Schutz, der durch risikobasierten bedingten Zugriff bereitgestellt wird, und von der verbesserten Sicherheit, die durch das Handeln auf Sicherheitsrisiken bereitgestellt wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Azure Active Directory Premium Plan 2 bieten benutzern die Rechte, von Azure Active Directory Identity Protection zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Azure AD Identity Protection-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Weitere Informationen zu Azure AD Identity Protection finden Sie unter [Was ist Identity Protection?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Azure AD Identity Protection durch Zuweisen von Risikorichtlinien, die die Stufe für Kennwortzurücksetzungen definieren und den Zugriff nur für lizenzierte Benutzer zulassen, auf den Bereich festlegen. Anweisungen zum Bereich von Azure AD Identity Protection-Bereitstellungen finden Sie unter Konfigurieren und Aktivieren [von Risikorichtlinien](/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Identity Governance

Azure Active Directory Identity Governance ermöglicht Es Ihnen, die Anforderungen Ihrer Organisation an Sicherheit und Mitarbeiterproduktivität mit den richtigen Prozessen und Sichtbarkeit in Balance zu bringen. Sie verwendet Berechtigungsverwaltung, Zugriffsüberprüfungen, Verwaltung privilegierter Identitäten und Nutzungsbedingungen, um sicherzustellen, dass die richtigen Personen den richtigen Zugriff auf die richtigen Ressourcen haben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Azure Active Directory Identity Governance erhöht die Produktivität der Benutzer, indem der Zugriff auf Apps, Gruppen und Microsoft Teams in einem Einzigen Zugriffspaket vereinfacht wird. Benutzer können auch als genehmigende Personen konfiguriert werden, ohne Dass Administratoren beteiligt werden müssen. Bei Zugriffsüberprüfungen können Benutzer Die Mitgliedschaften von Gruppen mit intelligenten Empfehlungen überprüfen, um in regelmäßigen Abständen Maßnahmen zu ergreifen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Azure Active Directory Premium Plan 2 bieten benutzern die Rechte, von der Azure Active Directory Identity Governance zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Azure AD Identity Governance-Features werden auf Mandantenebene aktiviert, aber pro Benutzer implementiert. Weitere Informationen zur Azure AD Identity Governance finden Sie unter [Was ist Azure AD Identity Governance?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können azure AD Identity Governance durch Zuweisen von Zugriffspaketen, Zugriffsüberprüfungen oder privilegierter Identitätsverwaltung nur für lizenzierte Benutzer nutzen. Anweisungen zum Bereich von Azure AD Identity Governance-Bereitstellungen finden Sie unter:

- [Lizenzanforderungen für die Azure AD-Berechtigungsverwaltung](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Lizenzanforderungen für den Azure AD-Zugriff überprüfen](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Lizenzanforderungen für die Verwendung Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (früher Azure Advanced Threat Protection) ist ein Clouddienst, der Unternehmenshybridumgebungen vor mehreren Arten von erweiterten gezielten Cyberangriffen und Insiderbedrohungen schützt.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

SecOp-Analysten und Sicherheitsexperten profitieren von der Möglichkeit von Microsoft Defender for Identity, erweiterte Bedrohungen, gefährdete Identitäten und schädliche Insideraktionen zu erkennen und zu untersuchen. Endbenutzer profitieren davon, dass ihre Daten von Microsoft Defender for Identity überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security und Microsoft Defender for Identity für Benutzer bieten die Rechte, von Microsoft Defender for Identity zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender for Identity-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Azure ATP finden Sie unter [Create your Microsoft Defender for Identity instance](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender for Identity-Dienste sind derzeit nicht in der Lage, Funktionen auf bestimmte Benutzer zu beschränken. Sie müssen jeden Benutzer lizenzen, den Sie nutzen möchten.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender für Office 365

Microsoft Defender for Office 365 (früher Office 365 Advanced Threat Protection) schützt Organisationen vor anspruchsvollen Angriffen wie Phishing und Zero-Day-Schadsoftware. Microsoft Defender for Office 365 bietet auch umsetzbare Einblicke, indem Signale aus einer breiten Palette von Daten korreliert werden, um mögliche Bedrohungen zu identifizieren, zu priorisieren und Empfehlungen zu geben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Microsoft Defender for Office 365 schützt Benutzer vor komplexen Angriffen wie Phishing und Zero-Day-Schadsoftware. Die vollständige Liste der in Plan 1 und Plan 2 bereitgestellten Dienste finden Sie unter [Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren? 

Microsoft Defender für Office 365 Pläne 1 und 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security und Microsoft 365 Business Premium bieten benutzern die Rechte, von Microsoft Defender für Office 365 zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender für Office 365 auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Microsoft Defender Office 365 Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Befolgen Sie die Bereitstellungsrichtlinien für sichere Links und sichere Anlagen, um Microsoft Defender für Office 365 zu verwenden:

- Informationen zum Konfigurieren sicherer Links für lizenzierte Benutzer finden Sie unter [Safe Links in Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Informationen zum Konfigurieren sicherer Anlagen für lizenzierte Benutzer finden Sie unter [Safe Attachments in Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/atp-safe-attachments).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) ist eine Teilmenge von Microsoft Cloud App Security mit Features, die auf Office 365 und ohne zusätzliche Sicherheit für Cloud-Apps von Drittanbietern und IaaS-Dienste beschränkt sind.

OCAS bietet Organisationen Einblick in ihre Produktivitäts-Cloud-Apps und -Dienste, bietet ausgefeilte Analysen zur Identifizierung und Bekämpfung von Cyberbedrohungen und ermöglicht es ihnen, zu steuern, wie Daten &mdash; Office 365.

Informationen zum Vergleichen von Features finden Sie unter [Unterschiede zwischen Microsoft Cloud App Security und Office 365 Cloud App Security](/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

OCAS ermittelt die Schatten-IT, bietet Schutz vor Bedrohungen Office 365 und kann steuern, welche Apps über die Berechtigung zum Zugreifen auf Daten verfügen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A3/A5/G5 bieten einem Benutzer die Rechte, von OCAS zu profitieren.
Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind OCAS-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren des Diensts finden Sie unter [Basic setup for Cloud App Security](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können OCAS-Bereitstellungen einschränken, um zu erzwingen, wie auf bestimmte Apps zugegriffen wird, und benutzergruppen, die von benutzern überwacht Office 365 Cloud App Security. Weitere Informationen finden Sie unter [Scoped deployment](/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) ist eine Cloud Access Security Broker (CASB)-Lösung, mit der Organisationen Einblick in ihre Cloud-Apps und -Dienste erhalten, eine ausgefeilte Analyse zur Identifizierung und Bekämpfung von Cyberbedrohungen bietet und sie steuern kann, wie Daten über jede Cloud-App verteilt &mdash; werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

MCAS ermittelt und bewertet die Schatten-IT, bietet Bedrohungsschutz für Cloud-Apps von Erst- und Drittanbietern und schützt Informationen über Cloud-Apps von Erst- und Drittanbietern hinweg.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance bieten benutzern die Rechte, von MCAS zu profitieren.

Azure AD P1 bietet benutzern die Rechte, von den Discoveryfunktionen in MCAS zu profitieren.

Um von den Funktionen der App-Steuerung für bedingten Zugriff in MCAS zu profitieren, müssen Benutzer auch für Azure Active Directory P1 lizenziert werden, das in Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Security enthalten ist.

Um von der automatischen clientseitigen Bezeichnung zu profitieren, müssen Benutzer für Azure Information Protection P2 lizenziert sein, das in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance enthalten ist.

> [!NOTE]
> Die automatische serverseitige Bezeichnung erfordert Information Protection für Office 365 - Premium Lizenzen ( `MIP_S_CLP2` oder `efb0351d-3b08-4503-993d-383af8de41e3` ). Referenz finden Sie unter [Product names and service plan identifiers for licensing](/azure/active-directory/enterprise-users/licensing-service-plan-reference).

Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind MCAS-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren Microsoft Cloud App Security Richtlinien für lizenzierte Benutzer finden Sie [unter Microsoft Cloud App Security Übersicht](/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können mcAS-Bereitstellungen mithilfe der im Dienst verfügbaren Bereichsbereitstellungsfunktionen auf lizenzierte Benutzer ausdingen. Weitere Informationen finden Sie unter [Scoped deployment](/cloud-app-security/scoped-deployment).

## <a name="compliance-manager"></a>Compliance-Manager

Vereinfachen Sie die Compliance und verringern Sie das Risiko mit dem Compliance-Manager. Der Compliance-Manager unterstützt Organisationen dabei, Anforderungen an Vorschriften, Standards, Unternehmensrichtlinien oder andere gewünschte Kontrollframeworks zu erfüllen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Im Folgenden finden Sie die Vorteile für die Benutzer vom Compliance-Manager-Dienst:

- Übersetzt komplizierte Vorschriften, Standards, Unternehmensrichtlinien oder andere gewünschte Steuerungsframeworks in einfache Sprache.
- Bietet Zugriff auf eine umfangreiche Bibliothek mit out-of-the-Box-Bewertungen und benutzerdefinierten Bewertungen, um eindeutige Complianceanforderungen zu erfüllen
- Karten aufsichtsrechtliche Kontrollen zu empfohlenen Verbesserungsmaßnahmen
- Enthält schrittweise Anleitungen zum Implementieren der Lösungen zur Erfüllung gesetzlicher Anforderungen
- Hilft Benutzern bei der Priorisierung von Aktionen, die die größte Auswirkung auf die Organisationskonformität haben, indem jeder Aktion eine Bewertung zuzuordnen ist.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Kunden mit E1- und E3/G3-Lizenzen können nur auf die standardmäßige Data Protection Baseline-Bewertung zugreifen. Kunden mit Office 365 E5/A5- und Microsoft 365 E5/A5-Lizenzen (Compliance, Info Protection & Governance sowie eDiscovery- und Audit-SKUs enthalten) können auf die Standardbewertung für Datenschutz, DSGVO, NIST 800-53 und ISO 27001 zugreifen. Kunden mit Office 365 G5 und Microsoft 365 G5 können auf die Datenschutzgrundwerte, die DSGVO, NIST 800-53, ISO 27001 und die CmMC(Cybersecurity Maturity Model Certification) Level 1 bis 5 out-of-the-box-Bewertungen zugreifen. Das benutzerdefinierte Bewertungsfeature und die Premiumbewertungen sind Office 365 E5/A5/G5- und Microsoft 365 E5/A5/G5-Kunden reserviert. Premium, z. B. FedRAMP Moderate, FedRAMP High und andere, stehen Kunden mit E5/A5/G5-Lizenzen im ersten Halbjahr 2021 über VL, CSP und WebDirect zum Kauf zur Verfügung. Wenden Sie sich an Ihren #A0 oder #A1 zum Kauf über VL- bzw. CSP-Kanäle. Informationen zum Kauf über WebDirect finden Sie unter [WebDirect](https://aka.ms/ComplianceManager/WebDirect).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Compliance Manager wird standardmäßig für Ihren Mandanten bereitgestellt. Administratoren legen Benutzerberechtigungen fest und weisen Rollen zu, damit Benutzer, die keine Administratoren in Ihrer Organisation sind, den Compliance-Manager verwenden können. Weitere Informationen finden Sie unter [Erste Schritte mit Compliance-Manager: Festlegen von Benutzerberechtigungen und Zuweisen von Rollen.](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender für Endpunkt

Microsoft Defender for Endpoint (früher Microsoft Defender ATP) ist eine Endpunktsicherheitslösung, die risikobasierte Sicherheitsrisikomanagement und Bewertung umfasst. Funktionen zur Reduzierung der Angriffsfläche; verhaltensbasierter und cloudgestützter Schutz der nächsten Generation; EDR (EDR); automatische Untersuchung und Korrektur; und verwaltete Dienste für die Suche. Weitere Informationen finden Sie auf der Seite [Microsoft Defender for Endpoint.](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, einschließlich Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5 Security, können von Microsoft Defender for Endpoint profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

SecOps-Analysten und Sicherheitsexperten profitieren von den Endpunktsicherheitsfunktionen von Microsoft Defender for Endpoint, um vorbeugenden Schutz, die Erkennung nach der Verletzung, automatisierte Untersuchung und Reaktion auf erweiterte Bedrohungen zu ermöglichen. Endbenutzer profitieren von böswilligen Ereignissen, die von Microsoft Defender for Endpoint überwacht werden.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender for Endpoint-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zur Bereitstellung finden Sie unter [Bereitstellungsphasen](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender for Endpoint-Administratoren können rollenbasierte Zugriffssteuerung (Role-Based Access Control, RBAC) verwenden, um Rollen und Gruppen innerhalb des Sicherheitsbetriebsteams zu erstellen, um den entsprechenden Zugriff auf die Microsoft Defender Security Center. Weitere Informationen finden Sie unter [Verwalten des Portalzugriffs mithilfe der rollenbasierten Zugriffssteuerung](/windows/security/threat-protection/microsoft-defender-atp/rbac).

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365 Analyse der Datenklassifizierung: Übersicht über den &amp; Inhaltsaktivitäts-Explorer

Analysefunktionen für die Datenklassifizierung sind in Microsoft 365 Compliance Center verfügbar. Übersicht zeigt die Speicherorte digitaler Inhalte und die gängigsten Typen und Bezeichnungen für vertrauliche Informationen. Der Inhalts-Explorer bietet Einblick in Menge und Typen vertraulicher Daten und ermöglicht Benutzern das Filtern nach Bezeichnung oder Vertraulichkeitstyp, um eine detaillierte Ansicht der Speicherorte zu erhalten, an denen die vertraulichen Daten gespeichert werden. Der Aktivitäts-Explorer zeigt Aktivitäten im Zusammenhang mit vertraulichen Daten und Bezeichnungen an, z. B. Herabstufungen von Bezeichnungen oder externe Freigaben, die Ihre Inhalte riskant machen könnten.

Der Aktivitäts-Explorer bietet Administratoren einen einzigen Ausschnitt, um Einblick in Aktivitäten zu erhalten, die mit vertraulichen Informationen im Zusammenhang stehen, die von Endbenutzern verwendet werden. Zu diesen Daten gehören Bezeichnungsaktivitäten, DLP-Protokolle (Data Loss Prevention, Verhinderung von Datenverlust), automatische Bezeichnungen, Endpunkt-DLP und vieles mehr.

Der Inhalts-Explorer bietet Administratoren die Möglichkeit, die vertraulichen Dokumente zu indizieren, die in unterstützten Microsoft 365 gespeichert sind, und die von ihnen gespeicherten vertraulichen Informationen zu identifizieren. Darüber hinaus hilft der Inhalts-Explorer, Dokumente zu identifizieren, die mit Vertraulichkeits- und Aufbewahrungsbezeichnungen klassifiziert sind.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Informationsschutz- und Complianceadministratoren können auf den Dienst zugreifen, um Zugriff auf diese Protokolle und indizierten Daten zu erhalten, um zu verstehen, wo vertrauliche Daten gespeichert werden und welche Aktivitäten im Zusammenhang mit diesen Daten stehen und von Endbenutzern ausgeführt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Lizenzierte Benutzer von Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection Governance und Office 365 E5 können von Microsoft 365 &amp; Datenklassifizierungsanalysen profitieren. 

Microsoft 365 E3/A3/G3 und Office 365 E3/A3/G3 können Benutzer nur von der Inhalts-Explorer-Datenaggregation profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Features des Inhalts- und Aktivitäts-Explorers auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren der Datenklassifizierungsanalyse für lizenzierte Benutzer finden Sie unter:

- **Inhalts-Explorer**: [Erste Schritte mit dem Inhalts-Explorer – Microsoft 365 Compliance-| Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer).
- **Aktivitäts-Explorer**: [Erste Schritte mit dem Aktivitäts-Explorer – Microsoft 365 Compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer).
- **Anmerkungen zur Datenklassifizierung:** Anmerkungen zur [Datenklassifizierung – Microsoft 365 Compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Dieses Feature muss für Benutzer verfügbar sein, die die Lösung aktiv innerhalb des Microsoft 365 verwenden.

## <a name="information-protection"></a>Informationsschutz

Information Protection hilft Organisationen dabei, vertrauliche Dokumente und E-Mails zu entdecken, zu klassifizieren, zu beschriften und zu schützen. Administratoren können Regeln und Bedingungen definieren, um Bezeichnungen automatisch anzuwenden, Benutzer können Bezeichnungen manuell anwenden, oder eine Kombination aus beiden kann verwendet werden, wobei Benutzern Empfehlungen zum Anwenden von Bezeichnungen gegeben werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von der Möglichkeit, Vertraulichkeitsbezeichnungen manuell auf ihre Inhalte anzuwenden oder ihre Inhalte automatisch klassifiziert zu lassen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 und AIP Plan 2 bieten benutzern die Rechte, von der manuellen Vertraulichkeitsbezeichnung zu profitieren.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 und AIP Plan 2 bieten einem Benutzer die Rechte, vom Anwenden und Anzeigen von Vertraulichkeitsbezeichnungen in Power BI zu profitieren und Daten zu schützen, wenn sie aus Power BI in Excel, PowerPoint oder PDF exportiert werden. 

> [!NOTE]
> Power BI ist in Microsoft 365 E5/A5/G5 enthalten. In allen anderen Plänen muss Power BI separat lizenziert werden.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection und Governance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 und AIP Plan 2 bieten einem Benutzer die Rechte, von der automatischen Vertraulichkeitsbezeichnung zu profitieren.

Information Protection umfasst keine Rechte auf automatische Klassifizierung basierend auf Machine Learning (trainierbare Klassifizierungen).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Informationsschutzfeatures auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Richtlinien für lizenzierte Benutzer finden Sie unter Aktivieren von Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Mit Ausnahme der Verwendung des AIP-Scannerfeatures können Richtlinien auf bestimmte Gruppen oder Benutzer und Registrierungsstellen begrenzt werden, um zu verhindern, dass nicht lizenzierte Benutzer Klassifizierungs- oder Bezeichnungsfeatures ausführen. Anweisungen zum Bereich von AIP-Bereitstellungen finden Sie unter [Configuring the Azure Information Protection policy](/azure/information-protection/configure-policy).

Für das AIP-Scannerfeature verpflichtet sich Microsoft nicht, Benutzern, die nicht lizenziert sind, Dateiklassifizierungs-, Bezeichnungs- oder Schutzfunktionen zur Verfügung zu stellen.

## <a name="information-governance"></a>Information Governance

Information Governance hilft Organisationen beim Verwalten ihres Risikos durch das Ermitteln, Klassifizieren, Bezeichnungen und Steuern ihrer Daten. Mit Information Governance können Organisationen geschäfts- und behördliche Anforderungen erfüllen und ihre Angriffsfläche reduzieren, indem sie Aufbewahrungs- und Löschfunktionen für ihre Microsoft 365 und Drittanbieterdaten bereitstellen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Die Benutzer profitieren davon, dass sie Daten zu Aufbewahrungszwecken klassifizieren können, um bestimmte Richtlinien und Vorschriften einzuhalten.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 und eigenständige Exchange-Pläne bieten benutzern die Rechte, von der manuellen Anwendung von Aufbewahrungsbezeichnungen ohne Datensatz auf Postfachdaten zu profitieren.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 und eigenständige SharePoint-Pläne bieten benutzern die Rechte, von der manuellen Anwendung von Aufbewahrungsbezeichnungen ohne Datensatz auf Dateien in SharePoint oder OneDrive zu profitieren. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plan 2 und Exchange Online-Archivierung bieten einem Benutzer die Rechte, von einer grundlegenden organisationsweiten oder standortweiten Postfachaufbewahrungsrichtlinie zu profitieren und/oder eine Nicht-Datensatzaufbewahrungsbezeichnung manuell auf Postfachdaten anzuwenden.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 und SharePoint Plan 2 bieten einem Benutzer die Rechte, von einer grundlegenden SharePoint- oder OneDrive-Aufbewahrungsrichtlinie zu profitieren und/oder eine Nicht-Datensatzaufbewahrungsbezeichnung manuell auf Dateien in SharePoint oder OneDrive anzuwenden.

Microsoft 365 E5/A5/G5/E3/A3 und Office 365 E5/A5/G5/E3/A3 bieten einem Benutzer die Rechte, von einer Teams profitieren.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5, und Office 365 E5/A5 bieten einem Benutzer die Rechte, von der automatischen Anwendung von Aufbewahrungsbezeichnungen oder -richtlinien, der Anwendung von Standardaufbewahrungsbezeichnungen oder -richtlinien, dem Starten des Aufbewahrungszeitraums einer Aufbewahrungsbezeichnung basierend auf einem benutzerdefinierten Ereignis, dem Auslösen einer manuellen Dispositionsüberprüfung am Ende des Aufbewahrungszeitraums der Bezeichnung, dem Importieren von Drittanbieterdaten über systemeigene Datenconnectors, dem Deklarieren einer Datei als Datensatz, dem Ermitteln von gekennzeichneten Inhalten und der Überwachung der Bezeichnungsaktivität zu profitieren.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection und Governance bieten benutzern die Rechte, von der automatischen Anwendung von Aufbewahrungsbezeichnungen basierend auf trainierbaren Klassifizierungen zu profitieren.

Informationen zu bestimmten Rechten nach Lizenz finden Sie im detaillierten Microsoft 365 Vergleich der Compliancelizenzierung. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Features für die Informationsverwaltung auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren der Information Governance zum Anwenden von automatischer Kennzeichnung und Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Features für die Informationsverwaltung können auf lizenzierte Benutzer an bestimmten Standorten (Teamwebsites, Gruppenwebsites usw.) angewendet werden. Informationen zum Konfigurieren der Information Governance zum Anwenden von automatischer Kennzeichnung und Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Datensatzverwaltung

Die Datensatzverwaltung hilft Organisationen bei der Erfüllung ihrer geschäftlichen und behördlichen Datensatzaufbewahrungspflichten durch das Ermitteln, Klassifizieren, Bezeichnungs-, Aufbewahrungs- und defensible Löschfunktionen für ihre Microsoft 365- und Drittanbieterdaten.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection und Governance E5/A5/G5 und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von der Datensatzverwaltung zu profitieren, einschließlich deklarieren von Elementen als Datensätze oder behördliche Datensätze, automatisches Anwenden von Aufbewahrungs- oder Datensatzbezeichnungen und Ausführen von Dispositionsüberprüfungsprozessen (ohne das automatische Anwenden einer Aufbewahrungsbezeichnung basierend auf trainierbaren Klassifizierungen).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection und Governance bieten benutzern die Rechte, von der automatischen Anwendung von Aufbewahrungs- oder Datensatzbezeichnungen basierend auf trainierbaren Klassifizierungen zu profitieren.

Informationen zu bestimmten Rechten nach Lizenz finden Sie im detaillierten Microsoft 365 Vergleich der Compliancelizenzierung. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von der Möglichkeit, Inhalte als Datensatz zu deklarieren und ihren vollständigen Datensatzprozess von der Richtliniendefinition und -deklaration bis hin zur verwerfbaren Entsorgung zu verwalten.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Features für die Datensatzverwaltung auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren der Datensatzverwaltung für lizenzierte Benutzer finden Sie unter [Learn about records Management in Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Features für die Datensatzverwaltung können auf lizenzierte Benutzer an bestimmten Standorten (Teamwebsites, Gruppenwebsites usw.) angewendet werden. Informationen zum Konfigurieren der Datensatzverwaltung für lizenzierte Benutzer finden Sie unter [Learn about records Management in Microsoft 365](/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Datenconnectors 

Microsoft stellt Datenconnectors von Drittanbietern zur Verfügung, die im compliance center Microsoft 365 konfiguriert werden können. Eine Liste der von Microsoft bereitgestellten Datenconnectors finden Sie in der Tabelle [Datenconnectors von](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) Drittanbietern. In dieser Tabelle werden auch die Compliancelösungen zusammengefasst, die Sie auf Drittanbieterdaten anwenden können, nachdem Sie Daten in Microsoft 365 importiert und archiviert haben, und links zu den schrittweisen Anweisungen für jeden Connector.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Der hauptvorteil der Verwendung von Datenconnectors zum Importieren und Archivieren von Drittanbieterdaten in Microsoft 365 besteht in der Anwendung verschiedener Microsoft 365-Compliancelösungen auf die Daten nach dem Importieren. Dadurch wird sichergestellt, dass die Nicht-Microsoft-Daten Ihrer Organisation den Vorschriften und Standards entsprechen, die sich auf Ihre Organisation auswirken.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Die folgenden Lizenzen bieten benutzern die Rechte, von Datenconnectors zu profitieren:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Info Protection &amp; Governance
- Microsoft 365 E5/A5/G5 Compliance
- Microsoft 365 E5/A5/G5 Insider Risk Management
- Microsoft 365 E5/A5/G5 eDiscovery and Audit
- Office 365 E5/A5/G5

Für Datenconnectors im Microsoft 365 Security Compliance Center, die von einem Microsoft-Partner bereitgestellt werden, benötigt Ihre Organisation eine Geschäftsbeziehung mit dem Partner, bevor Sie diese Connectors &amp; bereitstellen können.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Connectors werden mit dem Security &amp; Compliance Center und dem Connectorkatalog konfiguriert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Data Connectors-Dienste sind ein Wert auf Mandantenebene. Jeder Benutzer, der von diesem Dienst profitieren soll, muss lizenziert sein.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Microsoft Graph APIs für Teams Verhinderung von Datenverlust (Data Loss Prevention, DLP)

Anfang dieses Jahres haben wir die öffentliche Vorschau der Microsoft Graph Change Notification API für Nachrichten [in Teams.](https://go.microsoft.com/fwlink/?linkid=2143888) Diese API ermöglicht Entwicklern das Erstellen von Apps, die Microsoft Teams Nachrichten in echtzeitnaher Zeit abhören und DLP-Szenarioimplementierung für Kunden und ISVs aktivieren können. Darüber hinaus ermöglicht microsoft Graph Patch-API das Anwenden von DLP-Aktionen auf Teams Nachrichten.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

[Funktionen zur Verhinderung von Datenverlust (Data](/microsoft-365/compliance/dlp-microsoft-teams) Loss Prevention, DLP) werden in vielen Microsoft Teams, insbesondere da Organisationen auf Remotearbeit umschichtet haben. Wenn Ihre Organisation über DLP verfügt, können Sie jetzt Richtlinien definieren, die verhindern, dass Personen vertrauliche Informationen in einer Microsoft Teams oder Chatsitzung freigeben.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Sie benötigen eine der folgenden Lizenzen, um Unterstützung für den DLP-Schutz in Teams erhalten:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Compliance
- Microsoft 365 E5/A5/G5 Information Protection and Governance
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Der API-Zugriff wird auf Mandantenebene konfiguriert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Graph-API für Teams DLP ist ein Wert auf Mandantenebene. Jeder Benutzer, der von diesem Dienst profitieren soll, muss lizenziert sein.

## <a name="ediscovery"></a>eDiscovery

eDiscovery bietet Untersuchungs- und eDiscovery-Lösungen für IT- und Rechtsabteilungen in Unternehmen, um Inhalte im Zusammenhang mit einer Untersuchung oder einem Rechtsstreit vor dem Export aus dem Microsoft 365 zu identifizieren, zu sammeln, zu erhalten, zu reduzieren und zu überprüfen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Ein Benutzer profitiert von Advanced eDiscovery, wenn der Benutzer als Datenverwahrer (eine Person mit administrativer Kontrolle über ein Dokument oder eine elektronische Datei) für einen Fall ausgewählt wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5/E3/A3/G3 bieten Office 365 E5/A5/G5/E3/A3/G3 die Rechte für einen Benutzer, von Core eDiscovery zu profitieren.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 eDiscovery und Audit und Office 365 E5/A5/G5 bieten den Benutzern die Rechte, von Advanced eDiscovery zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Advanced eDiscovery Funktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert, wenn Administratoren eDiscovery-Berechtigungen im Security &amp; Compliance Center zuweisen.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

eDiscovery-Administratoren können bestimmte Benutzer als Datenverwahrer für einen Fall auswählen, indem sie das integrierte Verwaltungstool für Verwalter in Advanced eDiscovery verwenden, wie unter Hinzufügen von Verwaltern zu einem Advanced eDiscovery [beschrieben.](/microsoft-365/compliance/add-custodians-to-case)

## <a name="customer-key-for-microsoft-365"></a>Kundenschlüssel für Microsoft 365

Mit dem Kundenschlüssel steuern Sie die Verschlüsselungsschlüssel Ihrer Organisation und konfigurieren Microsoft 365, um diese zum Verschlüsseln ihrer ruhenen Daten in Microsoft-Rechenzentren zu verwenden. Mit anderen Worten: Mit dem Kundenschlüssel können Sie eine Verschlüsselungsebene hinzufügen, die Ihnen gehört, indem Sie Ihre eigenen Schlüssel verwenden. Ruhedaten umfassen Daten aus Exchange Online und Skype for Business, die in Postfächern und Dateien in SharePoint Online und OneDrive for Business.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren vom Kundenschlüssel, indem ihre Ruhedaten auf der Anwendungsebene mithilfe von Verschlüsselungsschlüsseln verschlüsselt werden, die von ihrer eigenen Organisation bereitgestellt, gesteuert und verwaltet werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, vom Kundenschlüssel zu profitieren. Um den vollen Nutzen des Kundenschlüssels zu erhalten, müssen Sie auch über ein Abonnement für Azure Key Vault verfügen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Kundenschlüssel für Microsoft 365-Verschlüsselungsschlüssel können für alle in Exchange Online- und Skype for Business-Postfächern gespeicherten Daten sowie SharePoint Online-, OneDrive for Business- und Teams aktiviert werden. Weitere Informationen zum Kundenschlüssel, einschließlich der ersten Schritte, finden Sie unter [Service encryption with Customer Key](/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Für Exchange Online und Skype for Business können Postfächer mithilfe des Kundenschlüssels verschlüsselt werden. Sie müssen Azure einrichten, bevor Sie den Kundenschlüssel für die Microsoft 365. Unter [Einrichten des Kundenschlüssels](/microsoft-365/compliance/customer-key-set-up) finden Sie die Schritte, die Sie ausführen müssen, um die erforderlichen Azure-Ressourcen zu erstellen und zu konfigurieren, sowie die Schritte zum Einrichten des Kundenschlüssels in Microsoft 365. Bestimmen Sie nach Abschluss des Azure-Setups, welche Richtlinie und daher welche Schlüssel Postfächern und Dateien in Ihrer Organisation zugewiesen werden sollen. Weitere Informationen zu Kundenschlüsseln und Inhalten zu Daten aus Exchange Online, Skype for Business, SharePoint Online, OneDrive for Business und Teams finden Sie unter [Service encryption with Customer Key](/microsoft-365/compliance/customer-key-overview).

## <a name="office-365-customer-lockbox"></a>Office 365-Kunden-Lockbox

Customer Lockbox bietet eine zusätzliche Steuerungsebene, indem Kunden die Möglichkeit bieten, explizite Zugriffsautorisierungen für Dienstvorgänge zu geben. Durch den Nachweis, dass Verfahren für die explizite Autorisierung des Datenzugriffs durchgeführt werden, kann Customer Lockbox Organisationen auch dabei helfen, bestimmte Complianceverpflichtungen wie HIPAA und FedRAMP zu erfüllen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Customer Lockbox stellt sicher, dass niemand bei Microsoft auf Kundeninhalte zugreifen kann, um einen Dienstvorgang ohne ausdrückliche Genehmigung des Kunden durchzuführen. Customer Lockbox führt den Kunden in den Genehmigungsworkflow für Anforderungen zum Zugriff auf ihre Inhalte. Gelegentlich sind Microsoft-Techniker während des Supportprozesses beteiligt, um Probleme zu beheben, die vom Kunden gemeldet wurden. In den meisten Fällen werden Probleme durch umfangreiche Telemetrie- und Debuggingtools behoben, die Microsoft für seine Dienste installiert hat. Es kann jedoch Fälle gibt, in denen ein Microsoft-Techniker auf Kundeninhalte zugreifen muss, um die Ursache zu ermitteln und das Problem zu beheben. Kunden-Lockbox setzt voraus, dass der Techniker den Zugriff vom Kunden als letzten Schritt im Genehmigungsworkflow anfordert. Dadurch haben Organisationen die Möglichkeit, diese Anforderungen zu genehmigen oder zu verweigern, wodurch sie direkt steuern können, ob ein Microsoft-Techniker auf die Endbenutzerdaten der Organisation zugreifen kann.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Insider Risk Management bieten einem Benutzer die Rechte, von Customer Lockbox zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren können customer lockbox im Microsoft 365 aktivieren. Weitere Informationen finden Sie unter [Customer Lockbox in Office 365](/microsoft-365/compliance/customer-lockbox-requests). Wenn Die Kunden-Lockbox aktiviert ist, muss Microsoft die Genehmigung einer Organisation vor dem Zugriff auf einen ihrer Inhalte erhalten.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Derzeit kann der Customer Lockbox-Dienst nicht auf bestimmte Benutzer beschränkt werden. Sie müssen jeden Benutzer lizenzen, den Sie nutzen möchten.

## <a name="privileged-access-management-in-office-365"></a>Privileged Access Management in Office 365

[Pam (Privileged Access Management) bietet](/microsoft-365/compliance/privileged-access-management-configuration) eine präzise Zugriffssteuerung für privilegierte Administratoraufgaben in Office 365. Nach der Aktivierung von PAM müssen Benutzer zum Abschließen von Aufgaben mit erhöhten rechten Rechten just-in-time-Zugriff über einen Genehmigungsworkflow anfordern, der in hohem Umfang und zeitgebunden ist.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Wenn Sie PAM aktivieren, können Organisationen mit null stehenden Berechtigungen arbeiten. Benutzer profitieren von der zusätzlichen Schutzebene gegen Sicherheitsrisiken, die durch den ständigen Administratorzugriff entstehen, der einen uneingeschränkten Zugriff auf ihre Daten ermöglicht.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und Microsoft 365 E5/A5 Information Protection and Governance bieten benutzern die Rechte, von PAM zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind PAM-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von PAM-Richtlinien finden Sie unter [Erste Schritte mit privilegierter Zugriffsverwaltung](/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Kunden können PAM auf Benutzerbasis über genehmigende Gruppen und Zugriffsrichtlinien verwalten, die auf lizenzierte Benutzer angewendet werden können. Weitere Informationen finden Sie unter [Privileged access management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Doppelschlüsselverschlüsselung für Microsoft 365 

Double Key Encryption for Microsoft 365 können Sie Ihre hochsensiblen Daten schützen, um spezielle Anforderungen zu erfüllen und die volle Kontrolle über Ihren Verschlüsselungsschlüssel zu behalten. Die Doppelschlüsselverschlüsselung verwendet zwei Schlüssel, um Ihre Daten zu schützen, mit einem Schlüssel in Ihrem Steuerelement und dem zweiten Schlüssel, der von der Microsoft Azure. Zum Anzeigen der Daten müssen Sie auf beide Schlüssel zugreifen können. Da Microsoft nur auf einen Schlüssel zugreifen kann, sind Ihr Schlüssel und auch Ihre Daten für Microsoft nicht verfügbar, um sicherzustellen, dass Sie die vollständige Kontrolle über den Datenschutz und die Sicherheit Ihrer Daten haben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von der Doppelschlüsselverschlüsselung, indem sie ihre verschlüsselten Daten in die Cloud migrieren können, wodurch der Zugriff durch Drittanbieter verhindert wird, solange der Schlüssel die Kontrolle über die Benutzer hat. Benutzer können verschlüsselte Inhalte mit doppelten Schlüsseln schützen und nutzen, ähnlich wie andere geschützte Inhalte mit Vertraulichkeitsbezeichnungen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance und Office 365 E5/A5/G5 bieten benutzern die Rechte, von der Doppelschlüsselverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Double Key Encryption unterstützt die Desktopversion von Microsoft Office für Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Befolgen Sie die Anweisungen zur Bereitstellung von Double Key Encryption, um Daten Office 365 und/oder Microsoft 365 lizenzierten Benutzern Verschlüsselungsschlüssel zuzuordnen.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 Verhinderung von Datenverlust für Exchange Online, SharePoint Online und OneDrive for Business

Mit Office 365 Verhinderung von Datenverlust (Data Loss Prevention, DLP) für Exchange Online, SharePoint Online und OneDrive for Business können Organisationen vertrauliche Informationen in E-Mails und Dateien (einschließlich dateien, die in Microsoft Teams-Dateirepositorys gespeichert sind) identifizieren, überwachen und automatisch schützen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von DLP für Exchange Online, SharePoint Online und OneDrive for Business, wenn ihre E-Mails und Dateien auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 und Office 365 Verhinderung von Datenverlust bieten einem Benutzer die Rechte, von Office 365 DLP für Exchange Online, SharePoint Online und OneDrive for Business zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Exchange Online E-Mails, SharePoint Websites und OneDrive-Konten aktivierte Speicherorte *(Workloads)* für diese DLP-Features für alle Benutzer innerhalb des Mandanten. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie [unter Overview of data loss prevention](/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security Compliance Center unter Speicherorte zur Verhinderung von Datenverlust &amp;   >  **anpassen.**

## <a name="communication-data-loss-prevention-for-teams"></a>Verhinderung von Kommunikationsdatenverlusten für Teams

Mit Kommunikations-DLP für Teams können Organisationen Chats blockieren und Nachrichten kanalieren, die vertrauliche Informationen enthalten, z. B. Finanzinformationen, persönliche Identifizierung von Informationen, gesundheitsbezogene Informationen oder andere vertrauliche Informationen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Information Protection and Governance können von Kommunikations-DLP für Teams.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Absender profitieren davon, dass vertrauliche Informationen in ihren ausgehenden Chats und Kanalnachrichten auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Teams Chat- und Kanalnachrichten ein aktivierter *Speicherort (Workload)* für diese DLP-Features für alle Benutzer innerhalb des Mandanten. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie [unter Overview of data loss prevention](/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security Compliance Center unter Speicherorte zur Verhinderung von Datenverlust &amp;   >  **anpassen.**

## <a name="information-barriers"></a>Informationsbarrieren

Informationsbarrieren sind Richtlinien, die ein Administrator konfiguriert, um zu verhindern, dass Einzelpersonen oder Gruppen miteinander kommunizieren können. Dies ist z. B. hilfreich, wenn eine Abteilung Informationen verwendet, die nicht mit anderen Abteilungen geteilt werden sollten, oder wenn eine Gruppe an der Kommunikation mit außen sten Kontakten gehindert werden muss. Richtlinien für Informationsbarrieren verhindern auch Nachschlage- und Ermittlungsinformationen. Dies bedeutet, dass Sie diesen Benutzer nicht in der Personenauswahl finden, wenn Sie versuchen, mit einer Person zu kommunizieren, mit der Sie nicht kommunizieren sollten.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von den erweiterten Compliancefunktionen von Informationsbarrieren, wenn sie nicht mit anderen kommunizieren können. Richtlinien für Informationsbarrieren können definiert werden, um zu verhindern, dass bestimmte Benutzersegmente mit den einzelnen Segmenten kommunizieren oder bestimmte Segmente nur mit bestimmten anderen Segmenten kommunizieren können. Weitere Informationen zum Definieren von Richtlinien für Informationsbarrieren finden Sie unter [Define information barrier policies](/microsoft-365/compliance/information-barriers-policies). In Szenarien, in denen zwei Gruppen nicht miteinander kommunizieren können, benötigen Benutzer in beiden Gruppen eine Lizenz, um von dem Dienst zu profitieren (siehe unten).<br><br>

| Szenario | Wer eine Lizenz erforderlich? |
|:------|:------|
| Zwei Gruppen (Gruppe 1 und Gruppe 2) können nicht miteinander kommunizieren (d. h. Benutzer der Gruppe 1 können nicht mit Benutzern der Gruppe 2 kommunizieren, und Benutzer der Gruppe 2 können nicht mit Benutzern der Gruppe &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1 kommunizieren. | Benutzer in Gruppe &nbsp; 1 und Gruppe &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Insider Risk Management und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von Informationsbarrieren zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Richtlinien für Informationsbarrieren mithilfe von PowerShell-Cmdlets im Security &amp; Compliance Center. Administratoren muss die Rolle Microsoft 365 Enterprise globalen Administrator, Office 365 globalen Administrator oder Complianceadministrator zugewiesen werden, um eine Richtlinie für Informationsbarrieren zu erstellen. Diese Richtlinien gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zu Informationsbarrieren finden Sie unter [Informationsbarrieren in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security &amp; Compliance Center anpassen. Wenn beispielsweise alle Benutzer für Office 365 E3 lizenziert sind und keiner für Office 365 Advanced Compliance/E5 lizenziert ist, müssen sie keine Richtlinien für Informationsbarrieren für die Organisation erstellen. Weitere Informationen finden Sie unter [Informationsbarrieren in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

Office 365-Nachrichtenverschlüsselung (Office Message Encryption, OME) ist ein Dienst, der auf Azure Rights Management (Azure RMS) aufbaut und mit dem Sie verschlüsselte E-Mails an Personen innerhalb oder außerhalb Ihrer Organisation senden können, unabhängig von der E-Mail-Zieladresse (Gmail, Yahoo! Mail, Outlook.com usw.).

Zum Anzeigen verschlüsselter Nachrichten können Empfänger eine einmalige Kennung abrufen, sich mit einem Microsoft-Konto anmelden oder sich mit einem Geschäfts-, Schul- oder Unikonto, das Office 365 zugeordnet ist, anmelden. Empfänger können auch verschlüsselte Antworten senden. Sie benötigen kein Abonnement, um verschlüsselte Nachrichten anzeigen oder verschlüsselte Antworten senden zu können.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Nachrichtensender profitieren von der zusätzlichen Kontrolle über vertrauliche E-Mails, die von Office 365-Nachrichtenverschlüsselung.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 und Azure Information Protection Plan 1 bieten einem Benutzer die Rechte, von der Office 365-Nachrichtenverschlüsselung.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Office 365-Nachrichtenverschlüsselung Richtlinien im Exchange Admin Center unter **Nachrichtenflussregeln**  >  . Diese Regeln gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Office 365-Nachrichtenverschlüsselung finden Sie unter [Einrichten neuer Nachrichtenverschlüsselungsfunktionen](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenflussregeln für Office 365-Nachrichtenverschlüsselung nur auf lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenflussregeln finden Sie unter Definieren von [Nachrichtenflussregeln zum Verschlüsseln von E-Mail-Nachrichten.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Erweiterte Office 365-Nachrichtenverschlüsselung

Office 365 Advanced Message Encryption hilft Kunden, Complianceverpflichtungen zu erfüllen, die flexiblere Kontrollen über externe Empfänger und ihren Zugriff auf verschlüsselte E-Mails erfordern. Mit der erweiterten Nachrichtenverschlüsselung können Administratoren vertrauliche E-Mails steuern, die außerhalb der Organisation freigegeben wurden, indem sie automatische Richtlinien verwenden, mit denen vertrauliche Informationstypen (z. B. persönliche Identifizierung von Informationen oder Finanz- oder Integritäts-IDs) erkannt werden können, oder sie können Schlüsselwörter verwenden, um den Schutz zu verbessern, indem sie benutzerdefinierte E-Mail-Vorlagen anwenden und den Zugriff auf verschlüsselte E-Mails über ein sicheres Webportal ablaufen lassen. Darüber hinaus können Administratoren verschlüsselte E-Mails, auf die extern über ein sicheres Webportal zugegriffen wird, weiter steuern, indem sie den Zugriff jederzeit wieder enignen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Nachrichtensender profitieren von der zusätzlichen Kontrolle über vertrauliche E-Mails, die von der erweiterten Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Information Protection and Governance bieten benutzern die Rechte, von der erweiterten Nachrichtenverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten erweiterte Nachrichtenverschlüsselungsrichtlinien im Exchange Admin Center unter **Nachrichtenflussregeln**  >  . Diese Regeln gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Nachrichtenverschlüsselungsfunktionen finden Sie unter [Set up new Office 365-Nachrichtenverschlüsselung capabilities](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenflussregeln für die erweiterte Nachrichtenverschlüsselung nur auf lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenflussregeln finden Sie unter [Define mail flow rules to encrypt email messages in Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Kommunikationscompliance

Kommunikationskonformität in Microsoft 365 hilft, Kommunikationsrisiken zu minimieren, indem Sie Ihnen helfen, unangemessene Nachrichten in Ihrer Organisation zu erkennen, zu erfassen und Abhilfemaßnahmen zu ergreifen. Sie können bestimmte Richtlinien definieren, die interne und externe E-Mails, Microsoft Teams oder Drittanbieterkommunikation in Ihrer Organisation erfassen. Prüfer können geeignete Korrekturmaßnahmen ergreifen, um sicherzustellen, dass sie den Nachrichtenstandards Ihrer Organisation entsprechen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Compliancespezialisten profitieren von dem Dienst, indem sie die Unternehmenskommunikation durch Richtlinien zur Kommunikationskonformität überwachen lassen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Insider Risk Management bieten benutzern die Rechte, von der Kommunikationskonformität zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren und Compliancespezialisten erstellen Kommunikations-Compliancerichtlinien im Microsoft 365 Compliance Center. Diese Richtlinien definieren, welche Kommunikationen und Benutzer in der Organisation überprüft werden müssen, definieren benutzerdefinierte Bedingungen, die die Kommunikation erfüllen muss, und geben an, wer Rezensionen durchführen soll.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren wählen bestimmte Benutzer oder Gruppen aus, die in eine Kommunikationskonformitätsrichtlinie enthalten sein sollten. Wenn sie eine Gruppe auswählen, können sie auch bestimmte Benutzer in der Gruppe auswählen, die aus der Kommunikationskonformitätsrichtlinie ausgeschlossen werden sollen. Weitere Informationen zu Kommunikationskonformitätsrichtlinien finden Sie unter Erste Schritte [mit kommunikationskonformität in Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Insider-Risikomanagement

Insider-Risikomanagement ist eine Lösung in Microsoft 365, die interne Risiken minimiert, indem Sie riskante Aktivitäten in Ihrer Organisation erkennen, untersuchen und Maßnahmen ergreifen können.

Mit benutzerdefinierten Richtlinien können Sie bösartige und versehentlich riskante Aktivitäten in Ihrer Organisation erkennen und ergreifen, einschließlich der Eskalierung von Fällen an Microsoft Advanced eDiscovery, falls erforderlich. Risikoanalysten in Ihrer Organisation können schnell geeignete Maßnahmen ergreifen, um sicherzustellen, dass Benutzer den Compliancestandards Ihrer Organisation entsprechen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Die Benutzer profitieren davon, dass ihre Aktivitäten auf Risiken überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten den Benutzern die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Insider Risk Management bieten einem Benutzer die Rechte, vom Insider Risk Management zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Richtlinien für das Insider-Risikomanagement müssen im Microsoft 365 erstellt und Benutzern zugewiesen werden.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Aktivieren Sie beim Erstellen einer Richtlinie im  Microsoft 365 Compliance Center auf  der Seite Benutzer und Gruppen auswählen das Kontrollkästchen Benutzer oder Gruppen auswählen, um nur lizenzierte Benutzer auszuwählen. Wenn alle Benutzer lizenziert sind, können Sie das Kontrollkästchen Alle Benutzer und **E-Mail-aktivierte** Gruppen aktivieren. Weitere Informationen finden Sie unter [Erste Schritte mit insider risk management](/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Richtlinien für bedingten Zugriff

Bedingter Zugriff ist das Tool, das von Azure Active Directory verwendet wird, um Signale zusammenzubringen, Entscheidungen zu treffen und Organisationsrichtlinien durchzusetzen. Bedingter Zugriff steht im Mittelpunkt der identitätsgesteuerten Steuerung. Bedingte Zugriffsrichtlinien sind auf ihre einfachste Weise if-then-Anweisungen. Wenn ein Benutzer auf eine Ressource zugreifen möchte, muss er eine Aktion abschließen. Beispiel: Ein Gehaltsmanager möchte auf die Lohnabrechnungsanwendung zugreifen und muss eine mehrstufige Authentifizierung ausführen, um darauf zu zugreifen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium und Azure Active Directory Premium Plan 1 können von Richtlinien für bedingten Zugriff profitieren. Lizenzierte Benutzer von Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security und Azure Active Directory Premium Plan 2 können von Identitätsschutz (risikobasierte Richtlinien für bedingten Zugriff) profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Analysten und Sicherheitsexperten für Sicherheitsvorgänge profitieren von der Möglichkeit, Organisationsrichtlinien für Benutzer durchzusetzen und bestimmte Kriterien zu erfüllen, bevor sie Zugriff auf Unternehmensinhalte gewähren. Endbenutzer profitieren davon, dass sie jederzeit und überall auf ihre Arbeit zugreifen können und gleichzeitig die Ressourcen der Organisation schützen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Features für bedingten Zugriff auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Speziell für Identitätsschutz und bedingten Zugriff muss ein Benutzer in einer Gruppe enthalten sein oder einer Richtlinie für bedingten Zugriff hinzugefügt werden. Die Benutzer- und Gruppenbedingung ist in einer Richtlinie für bedingten Zugriff obligatorisch. In Ihrer Richtlinie können Sie entweder **Alle Benutzer oder** bestimmte Benutzer und Gruppen auswählen. Sie sollten nur entsprechend lizenzierte Benutzer und Gruppen auswählen. Weitere Informationen finden Sie unter [Conditional Access: Conditions](/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Erweiterte Überwachung

Advanced Audit in Microsoft 365 bietet eine einjährige Aufbewahrung von Überwachungsprotokollen für Benutzer- und Administratoraktivitäten und bietet die Möglichkeit, benutzerdefinierte Aufbewahrungsrichtlinien für Überwachungsprotokolle zu erstellen, um die Aufbewahrung von Überwachungsprotokollen für andere Microsoft 365 verwalten. Außerdem bietet es Zugriff auf wichtige Ereignisse für Untersuchungen und zugriff mit hoher Bandbreite auf die Office 365 Management Activity API. Weitere Informationen finden Sie unter [Advanced Audit in Microsoft 365](/microsoft-365/compliance/advanced-audit).

Sie können auch einen Aufbewahrungszeitraum von 10 Jahren mit einer Add-On-SKU aktivieren. Die Add-On-SKU ist ab Anfang 2021 erforderlich.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 eDiscovery und Audit können von der erweiterten Überwachung profitieren.

Lizenzierte Benutzer mit erweiterter Überwachung und dem 10-Jahres-Add-On Überwachungsprotokollaufbewahrung können von der 10-jahres-Überwachungsprotokollaufbewahrung profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von der erweiterten Überwachung, da Überwachungsdatensätze im Zusammenhang mit Benutzeraktivitäten in Microsoft 365 bis zu einem Jahr aufbewahrt werden können. Darüber hinaus werden hochwertige Überwachungsereignisse protokolliert, z. B. wenn auf Elemente im Postfach eines Benutzers zugegriffen oder gelesen wird. Weitere Informationen finden Sie unter [Advanced Audit in Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig ist die erweiterte Überwachung auf Mandantenebene für alle Organisationen aktiviert, die über ein Office 365- oder Microsoft 365 E5/A5/G5-Abonnement verfügen, und bietet automatisch eine einjährige Aufbewahrung von Überwachungsprotokollen für Aktivitäten (die von Benutzern mit der entsprechenden Lizenz ausgeführt werden) in Azure Active Directory, Exchange und SharePoint. Darüber hinaus können Organisationen Aufbewahrungsrichtlinien für Überwachungsprotokolle verwenden, um den Aufbewahrungszeitraum für Überwachungsdatensätze zu verwalten, die durch Aktivitäten in anderen Diensten Microsoft 365 werden. Die 10-jährige Überwachungsprotokollaufbewahrungsfunktion wird auch mithilfe derselben Aufbewahrungsrichtlinien aktiviert. Weitere Informationen finden Sie unter [Verwalten der Aufbewahrungsrichtlinien für Überwachungsprotokolle](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Die einjährige Aufbewahrung von Überwachungsprotokollen und die Überwachung wichtiger Ereignisse gelten nur für Benutzer mit der entsprechenden Lizenz. Darüber hinaus können Administratoren Aufbewahrungsrichtlinien für Überwachungsprotokolle verwenden, um kürzere Aufbewahrungsdauern für die Überwachungsprotokolle bestimmter Benutzer anzugeben.

Die 10-jährige Aufbewahrung von Überwachungsprotokollen gilt nur für Benutzer mit der entsprechenden Add-On-Lizenz. Die Add-On-SKU ist ab Anfang 2021 erforderlich.