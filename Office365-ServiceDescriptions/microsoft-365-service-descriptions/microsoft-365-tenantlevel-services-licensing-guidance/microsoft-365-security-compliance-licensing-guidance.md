---
title: Microsoft 365 Lizenzierungsleitfaden für die Einhaltung von Sicherheits- &
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
description: Dieser Artikel enthält Lizenzierungsleitfaden für Microsoft 365 Compliance, um potenzielle Dienstunterbrechungen aufgrund eines nicht lizenzierten Zugriffs zu vermeiden.
ms.openlocfilehash: dc52a66990114f9c74ca815c9525f34175e7995b
ms.sourcegitcommit: 0bf671ec5b5ba16bcdc730b88e2607d85a3d4497
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/15/2021
ms.locfileid: "52950164"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Microsoft 365 Lizenzierungsleitfaden für &amp; die Sicherheitscompliance

Für die Zwecke dieses Artikels ist ein Dienst auf Mandantenebene ein Onlinedienst, der &mdash; beim Kauf für einen beliebigen Benutzer im Mandanten (eigenständig oder als Teil von Office 365 oder Microsoft 365 Plänen) für alle Benutzer im Mandanten teilweise oder vollständig aktiviert &mdash; wird. Obwohl einige nicht lizenzierte Benutzer technisch möglicherweise auf den Dienst zugreifen können, ist für jeden Benutzer, der von dem Dienst profitieren möchte, eine Lizenz erforderlich.

> [!NOTE]
> Einige Mandantendienste sind derzeit nicht in der Lage, die Vorteile für bestimmte Benutzer einzuschränken. Es sollten Anstrengungen unternommen werden, um die Dienstvorteile auf lizenzierte Benutzer zu beschränken. Dies trägt dazu bei, potenzielle Dienstunterbrechungen für Ihre Organisation zu vermeiden, sobald Zielfunktionen verfügbar sind.

Laden Sie die [Microsoft 365 Vergleichstabelle](https://go.microsoft.com/fwlink/?linkid=2139145)herunter, um die Optionen für die Lizenzierung Ihrer Benutzer anzuzeigen, um von Microsoft 365 Compliancefeatures zu profitieren.

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identitätsschutz ist ein Feature des Azure Active Directory Premium P2 Plans, mit dem Sie potenzielle Sicherheitsrisiken erkennen können, die sich auf die Identitäten Ihrer Organisation auswirken, automatisierte Antworten auf erkannte verdächtige Aktionen konfigurieren können, die mit den Identitäten Ihrer Organisation zusammenhängen, und verdächtige Vorfälle untersuchen und entsprechende Maßnahmen ergreifen können, um sie zu beheben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

SecOps-Analysten und Sicherheitsexperten profitieren von konsolidierten Ansichten von gekennzeichneten Benutzern und Risikoereignissen basierend auf Machine Learning-Algorithmen. Endbenutzer profitieren von dem automatischen Schutz durch risikobasierten bedingten Zugriff und der verbesserten Sicherheit, die durch die Verwendung von Sicherheitsrisiken bereitgestellt wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Azure Active Directory Premium Plan 2 bieten einem Benutzer die Rechte, von Azure Active Directory Identity Protection zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Azure AD Identity Protection-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zu Azure AD Identity Protection finden Sie unter ["Was ist Identitätsschutz"?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können azure AD Identity Protection einschränken, indem sie Risikorichtlinien zuweisen, die die Ebene für kennwortzurücksetzungen definieren und nur lizenzierten Benutzern den Zugriff erlauben. Anweisungen zum Einschränken von Azure AD Identity Protection-Bereitstellungen finden Sie unter [Konfigurieren und Aktivieren von Risikorichtlinien.](/azure/active-directory/identity-protection/howto-sign-in-risk-policy)

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Identitätsgovernance

Azure Active Directory Identitätsgovernance ermöglicht es Ihnen, die Anforderungen Ihrer Organisation an Sicherheit und Mitarbeiterproduktivität mit den richtigen Prozessen und Sichtbarkeit in Einklang zu bringen. Es verwendet Berechtigungsverwaltung, Zugriffsüberprüfungen, privileged Identity Management und Nutzungsbedingungen, um sicherzustellen, dass die richtigen Personen den richtigen Zugriff auf die richtigen Ressourcen haben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Azure Active Directory Identitätsgovernance erhöht die Produktivität der Benutzer, indem es einfacher wird, den Zugriff auf Apps, Gruppen und Microsoft Teams in einem Zugriffspaket anzufordern. Benutzer können auch als Genehmiger konfiguriert werden, ohne Administratoren einzubeziehen. Für Zugriffsüberprüfungen können Benutzer Mitgliedschaften von Gruppen mit intelligenten Empfehlungen überprüfen, um in regelmäßigen Abständen Maßnahmen zu ergreifen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Azure Active Directory Premium Plan 2 bieten einem Benutzer die Rechte, von Azure Active Directory Identity Governance zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Azure AD Identity Governance-Features sind auf Mandantenebene aktiviert, werden jedoch pro Benutzer implementiert. Informationen zur Azure AD Identity Governance finden Sie unter [Was ist Azure AD Identity Governance?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können azure AD Identity Governance einschränken, indem sie Nur lizenzierten Benutzern Zugriffspakete, Zugriffsüberprüfungen oder privileged Identitätsverwaltung zuweisen. Anweisungen zum Einschränken von Azure AD Identity Governance-Bereitstellungen finden Sie unter:

- [Lizenzanforderungen für die Azure AD-Berechtigungsverwaltung](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Lizenzanforderungen für die Azure AD-Zugriffsüberprüfung](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Lizenzanforderungen für die Verwendung von Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (früher Azure Advanced Threat Protection) ist ein Clouddienst, der Unternehmenshybridumgebungen vor mehreren Arten von erweiterten gezielten Cyberangriffen und Insider-Bedrohungen schützt.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

SecOp-Analysten und Sicherheitsexperten profitieren von der Fähigkeit von Microsoft Defender for Identity, fortgeschrittene Bedrohungen, kompromittierte Identitäten und böswillige Insideraktionen zu erkennen und zu untersuchen. Endbenutzer profitieren davon, dass ihre Daten von Microsoft Defender for Identity überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security und Microsoft Defender for Identity for Users bieten die Rechte, von Microsoft Defender for Identity zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender for Identity-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Azure ATP finden Sie unter [Erstellen Ihrer Microsoft Defender for Identity-Instanz.](/defender-for-identity/install-step1)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender for Identity-Dienste sind derzeit nicht in der Lage, die Funktionen auf bestimmte Benutzer zu beschränken. Sie müssen jeden Benutzer, von dem Sie profitieren möchten, lizenzen.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender für Office 365

Microsoft Defender für Office 365 (früher Office 365 Advanced Threat Protection) schützt Organisationen vor komplexen Angriffen wie Phishing und Zero-Day-Schadsoftware. Microsoft Defender für Office 365 bietet auch umsetzbare Einblicke, indem Signale aus einer breiten Palette von Daten korreliert werden, um potenzielle Bedrohungen zu identifizieren, zu priorisieren und Empfehlungen bereitzustellen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Microsoft Defender für Office 365 schützt Benutzer vor komplexen Angriffen wie Phishing und Zero-Day-Schadsoftware. Eine vollständige Liste der in Plan 1 und Plan 2 bereitgestellten Dienste finden Sie unter [Microsoft Defender für Office 365.](/microsoft-365/security/office-365-security/office-365-atp)

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren? 

Microsoft Defender für Office 365 Pläne 1 und 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security und Microsoft 365 Business Premium einem Benutzer die Rechte gewähren, von Microsoft Defender für Office 365 zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Die Features von Microsoft Defender für Office 365 auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Microsoft Defender für Office 365 Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Defender für Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Um Microsoft Defender auf Office 365 zu beschränken, befolgen Sie die Bereitstellungsrichtlinien für Safe Links und Safe Anlagen:

- Informationen zum Konfigurieren Safe Links für lizenzierte Benutzer finden Sie unter [Safe Links in Microsoft Defender für Office 365.](/microsoft-365/security/office-365-security/atp-safe-links)

- Informationen zum Konfigurieren von Safe Anlagen für lizenzierte Benutzer finden Sie unter [Safe Anlagen in Microsoft Defender für Office 365.](/microsoft-365/security/office-365-security/atp-safe-attachments)

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) ist eine Teilmenge der Microsoft Cloud App Security, mit Features, die auf Office 365 und ohne zusätzliche Sicherheit für Cloud-Apps von Drittanbietern und IaaS-Dienste beschränkt sind.

OCAS bietet Organisationen Einblicke in ihre Produktivitätscloud-Apps und -Dienste, bietet komplexe Analysen, um Cyberbedrohungen zu erkennen und zu bekämpfen, und ermöglicht es ihnen zu steuern, wie Daten über Office 365 übertragen &mdash; werden.

Informationen zum Vergleichen von Features finden Sie unter [Unterschiede zwischen Microsoft Cloud App Security und Office 365 Cloud App Security.](/cloud-app-security/editions-cloud-app-security-o365)

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

OCAS entdeckt Schatten-IT, bietet Bedrohungsschutz über Office 365 hinweg und kann steuern, welche Apps über die Berechtigung für den Zugriff auf Daten verfügen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A3/A5/G5 bieten einem Benutzer die Rechte, von OCAS zu profitieren.
Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing Datasheet.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind OCAS-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren des Diensts finden Sie unter [Grundlegendes Setup für Cloud App Security](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können OCAS-Bereitstellungen einschränken, um zu erzwingen, wie auf bestimmte Apps zugegriffen wird, und benutzergruppen einschränken, die von Office 365 Cloud App Security überwacht werden. Weitere Informationen finden Sie unter ["Bereichsbezogene Bereitstellung".](/cloud-app-security/scoped-deployment)

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) ist eine Casb-Lösung (Cloud Access Security Broker), die Organisationen Einblicke in ihre Cloud-Apps und -Dienste bietet, komplexe Analysen zur Identifizierung und Bekämpfung von Cyberbedrohungen bietet und sie steuern kann, wie Daten &mdash; in jeder Cloud-App übertragen werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

MCAS ermittelt und bewertet Schatten-IT, bietet Bedrohungsschutz für Erst- und Drittanbieter-Cloud-Apps und schützt Informationen in Cloud-Apps von Erst- und Drittanbietern.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance bieten einem Benutzer die Rechte, von MCAS zu profitieren.

Azure AD P1 bietet einem Benutzer die Rechte, von den Discovery-Funktionen in MCAS zu profitieren.

Um von den Funktionen der App-Steuerung für bedingten Zugriff in MCAS zu profitieren, müssen Benutzer auch für Azure Active Directory P1 lizenziert werden, das in Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Security enthalten ist.

Um von der automatischen clientseitigen Bezeichnung profitieren zu können, müssen Benutzer für Azure Information Protection P2 lizenziert sein, das in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance enthalten ist.

> [!NOTE]
> Die automatische serverseitige Bezeichnung erfordert Information Protection für Office 365 – Premium Lizenzen ( `MIP_S_CLP2` oder `efb0351d-3b08-4503-993d-383af8de41e3` ). Referenzinformationen finden Sie unter [Produktnamen und Serviceplanbezeichner für die Lizenzierung.](/azure/active-directory/enterprise-users/licensing-service-plan-reference)

Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing Datasheet.](https://www.aka.ms/mcaslicensing)

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind MCAS-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren Microsoft Cloud App Security Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Cloud App Security Übersicht.](/cloud-app-security/what-is-cloud-app-security)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können MCAS-Bereitstellungen auf lizenzierte Benutzer beschränken, indem sie die bereichsbezogenen Bereitstellungsfunktionen verwenden, die im Dienst verfügbar sind. Weitere Informationen finden Sie unter ["Bereichsbezogene Bereitstellung".](/cloud-app-security/scoped-deployment)

## <a name="compliance-manager"></a>Compliance-Manager

Vereinfachen Sie die Compliance und tragen Sie dazu bei, das Risiko mit dem Compliance-Manager zu verringern. Compliance-Manager hilft Organisationen dabei, Anforderungen von Vorschriften, Standards, Unternehmensrichtlinien oder anderen gewünschten Kontrollframeworks zu erfüllen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Nachfolgend sind die Vorteile für die Benutzer vom Compliance-Manager-Dienst aufgeführt:

- Übersetzt komplizierte Vorschriften, Standards, Unternehmensrichtlinien oder andere gewünschte Steuerungsframeworks in einfache Sprache.
- Bietet Zugriff auf eine umfangreiche Bibliothek mit sofort einsatzbereiten Bewertungen und benutzerdefinierten Bewertungen, um die einzigartigen Complianceanforderungen zu erfüllen.
- Ordnet regulatorische Kontrollen empfohlenen Verbesserungsmaßnahmen zu
- Enthält schrittweise Anleitungen zur Implementierung der Lösungen zur Erfüllung behördlicher Anforderungen.
- Hilft Benutzern bei der Priorisierung von Aktionen, die den größten Einfluss auf die Compliance ihrer Organisation haben, indem jeder Aktion eine Bewertung zugeordnet wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Kunden mit E1- und E3/G3-Lizenzen können nur auf die standardmäßige Bewertung der Datenschutzgrundwerte zugreifen. Kunden mit Office 365 E5/A5- und Microsoft 365 E5/A5-Lizenzen (Compliance, Info Protection & Governance sowie eDiscovery- und Audit-SKUs enthalten) können auf Die Datenschutzgrundwerte, DSGVO, NIST 800-53 und ISO 27001 zugreifen. Kunden mit Office 365 G5 und Microsoft 365 G5 können auf die Datenschutzgrundwerte DSGVO, NIST 800-53, ISO 27001 und CMMC (Cybersecurity Maturity Model Certification) der Stufen 1 bis 5 zugreifen. Die benutzerdefinierte Bewertungsfunktion und die Premiumbewertungen sind für Office 365 E5/A5/G5- und Microsoft 365 E5/A5/G5-Kunden reserviert. Premiumbewertungen, z. B. FedRAMP Moderate, FedRAMP High und andere, stehen Kunden mit E5/A5/G5-Lizenzen in der ersten Hälfte 2021 über VL, CSP und WebDirect zum Kauf zur Verfügung. Wenden Sie sich an Ihren Microsoft-Verkäufer oder Microsoft-Partner, um den Kauf über VL- oder CSP-Kanäle zu tätigen. Informationen zum Kauf über WebDirect finden Sie unter [WebDirect.](https://aka.ms/ComplianceManager/WebDirect)

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Compliance-Manager wird standardmäßig für Ihren Mandanten bereitgestellt. Administratoren legen Benutzerberechtigungen fest und weisen Rollen zu, sodass Benutzer, die keine Administratoren sind, in Ihrer Organisation mit der Verwendung des Compliance-Managers beginnen können. Weitere Informationen finden Sie unter ["Erste Schritte mit Compliance-Manager": Festlegen von Benutzerberechtigungen und Zuweisen von Rollen.](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles)

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender für Endpunkt

Microsoft Defender für Endpunkt (früher Microsoft Defender ATP) ist eine Endpunktsicherheitslösung, die das risikobasierte Verwalten und Bewerten von Sicherheitsrisiken umfasst. Attack Surface Reduction-Funktionen; verhaltensbasierter und cloudgestützter Schutz der nächsten Generation; Endpunkterkennung und -antwort (Endpoint Detection and Response, EDR); automatische Untersuchung und Behebung; und verwaltete Suchdienste. Weitere Informationen finden Sie auf der Microsoft [Defender für Endpunkt-Seite.](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, einschließlich Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5 Security, können von Microsoft Defender für Endpunkt profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

SecOps-Analysten und Sicherheitsexperten profitieren von den Endpunktsicherheitsfunktionen von Microsoft Defender für Endpunkt, um präventiven Schutz, Erkennung nach einer Verletzung, automatisierte Untersuchung und Reaktion auf fortgeschrittene Bedrohungen zu bieten. Endbenutzer profitieren von bösartigen Ereignissen, die von Microsoft Defender für Endpunkt überwacht werden.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender für Endpunkt-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zur Bereitstellung finden Sie unter [Bereitstellungsphasen.](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender für Endpunkt-Administratoren können die rollenbasierte Zugriffssteuerung (Role-Based Access Control, RBAC) verwenden, um Rollen und Gruppen innerhalb des Sicherheitsteams zu erstellen, um den entsprechenden Zugriff auf das Microsoft Defender Security Center zu gewähren. Weitere Informationen finden Sie unter [Verwalten des Portalzugriffs mithilfe der rollenbasierten Zugriffssteuerung.](/windows/security/threat-protection/microsoft-defender-atp/rbac)

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365-Datenklassifizierungsanalyse: Übersicht über den &amp; Inhaltsaktivitäts-Explorer

Analysefunktionen für die Datenklassifizierung sind in der Microsoft 365 Compliance Center-Umgebung verfügbar. Die Übersicht zeigt die Speicherorte digitaler Inhalte und die gängigsten Typen und Bezeichnungen vertraulicher Informationen. Der Inhalts-Explorer bietet Einblicke in die Menge und typen vertraulicher Daten und ermöglicht Benutzern das Filtern nach Bezeichnung oder Vertraulichkeitstyp, um eine detaillierte Ansicht der Speicherorte der vertraulichen Daten zu erhalten. Der Aktivitäts-Explorer zeigt Aktivitäten im Zusammenhang mit vertraulichen Daten und Bezeichnungen an, z. B. Herabstufungen von Bezeichnungen oder externe Freigaben, die Ihre Inhalte einem Risiko aussetzen könnten.

Der Aktivitäts-Explorer bietet Administratoren einen einzigen Bereich, um Einblicke in Aktivitäten zu erhalten, die sich auf vertrauliche Informationen beziehen, die von Endbenutzern verwendet werden. Diese Daten umfassen Bezeichnungsaktivitäten, DLP-Protokolle (Data Loss Prevention, Verhinderung von Datenverlust), automatische Bezeichnungen, Endpunkt-DLP und vieles mehr.

Der Inhalts-Explorer bietet Administratoren die Möglichkeit, die vertraulichen Dokumente zu indizieren, die in unterstützten Microsoft 365-Workloads gespeichert sind, und die vertraulichen Informationen zu identifizieren, die sie speichern. Darüber hinaus hilft der Inhalts-Explorer beim Identifizieren von Dokumenten, die mit Vertraulichkeits- und Aufbewahrungsbezeichnungen klassifiziert sind.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Administratoren von Informationsschutz und Compliance können auf den Dienst zugreifen, um Zugriff auf diese Protokolle und indizierten Daten zu erhalten, um zu verstehen, wo vertrauliche Daten gespeichert werden und welche Aktivitäten mit diesen Daten zusammenhängen und von Endbenutzern ausgeführt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Lizenzierte Benutzer von Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection &amp; Governance und Office 365 E5 können von Microsoft 365-Datenklassifizierungsanalysen profitieren. 

Mit Microsoft 365 E3/A3/G3 und Office 365 E3/A3/G3 können Benutzer nur von der Inhalts-Explorer-Datenaggregation profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Features des Übersichtsinhalts- und Aktivitäts-Explorers auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Datenklassifizierungsanalysen für lizenzierte Benutzer finden Sie unter:

- **Inhalts-Explorer:** [Erste Schritte mit dem Inhalts-Explorer – Microsoft 365 Compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer).
- **Aktivitäten-Explorer:** [Erste Schritte mit dem Aktivitäten-Explorer – Microsoft 365 Compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer).
- **Versionshinweise zur Datenklassifizierung:** [Versionshinweise zur Datenklassifizierung – Microsoft 365 Compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Dieses Feature muss auf Benutzer beschränkt sein, die die Lösung aktiv im Microsoft 365 Compliance-Portal verwenden.

## <a name="information-protection"></a>Informationsschutz

Information Protection hilft Organisationen dabei, vertrauliche Dokumente und E-Mails zu erkennen, zu klassifizieren, zu kennzeichnen und zu schützen. Administratoren können Regeln und Bedingungen definieren, um Bezeichnungen automatisch anzuwenden, Benutzer können Bezeichnungen manuell anwenden, oder eine Kombination der beiden Können verwendet werden, wobei Benutzern Empfehlungen zum Anwenden von Bezeichnungen gegeben werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von der Möglichkeit, Vertraulichkeitsbezeichnungen manuell auf ihre Inhalte anzuwenden oder ihre Inhalte automatisch klassifizieren zu lassen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 und AIP Plan 2 bieten einem Benutzer die Rechte, von manuellen Vertraulichkeitsbezeichnungen zu profitieren.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 und AIP Plan 2 bieten einem Benutzer die Rechte, von der Anwendung und Anzeige von Vertraulichkeitsbezeichnungen in Power BI zu profitieren und Daten zu schützen, wenn sie aus Power BI nach Excel, PowerPoint oder PDF exportiert werden. 

> [!NOTE]
> Power BI ist in Microsoft 365 E5/A5/G5 enthalten. in allen anderen Plänen muss Power BI separat lizenziert werden.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection und Governance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 und AIP Plan 2 bieten einem Benutzer die Rechte, von der automatischen Vertraulichkeitsbezeichnung zu profitieren.

Information Protection umfasst keine Rechte zur automatischen Klassifizierung basierend auf Machine Learning (trainierbare Klassifizierer).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Informationsschutzfeatures auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Richtlinien für lizenzierte Benutzer finden Sie unter Aktivieren von Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Mit Ausnahme der AIP-Scannerfunktion können Richtlinien auf bestimmte Gruppen oder Benutzer beschränkt werden, und Registrierungen können bearbeitet werden, um zu verhindern, dass nicht lizenzierte Benutzer Klassifizierungs- oder Bezeichnungsfunktionen ausführen. Anweisungen zum Einschränken von AIP-Bereitstellungen finden Sie unter [Konfigurieren der Azure Information Protection-Richtlinie.](/azure/information-protection/configure-policy)

Für die AIP-Scannerfunktion verpflichtet sich Microsoft nicht, Benutzern, die nicht lizenziert sind, Dateiklassifizierungs-, Bezeichnungs- oder Schutzfunktionen bereitzustellen.

## <a name="information-governance"></a>Informationsgovernance

Informationsgovernance hilft Organisationen bei der Verwaltung ihres Risikos, indem sie ihre Daten ermitteln, klassifizieren, bezeichnen und verwalten. Informationsgovernance ermöglicht es Organisationen, geschäftliche und behördliche Anforderungen zu erfüllen sowie ihre Angriffsfläche zu reduzieren, indem sie Aufbewahrungs- und Löschungsfunktionen in ihren Microsoft 365- und Drittanbieterdaten bereitstellen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren durch die Möglichkeit, Daten für Aufbewahrungszwecke zu klassifizieren, um bestimmte Richtlinien und Vorschriften zu erfüllen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 und eigenständige Exchange-Pläne bieten einem Benutzer die Rechte, von der manuellen Anwendung von Aufbewahrungsbezeichnungen ohne Datensatz auf Postfachdaten zu profitieren.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 und eigenständige SharePoint-Pläne bieten einem Benutzer die Rechte, von der manuellen Anwendung von Aufbewahrungsbezeichnungen ohne Datensätze auf Dateien in SharePoint oder OneDrive zu profitieren. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plan 2 und Exchange Online Archiving bieten einem Benutzer die Rechte, von einer grundlegenden organisationsweiten oder standortweiten Postfachaufbewahrungsrichtlinie zu profitieren und/oder eine Aufbewahrungsbezeichnung ohne Datensatz manuell auf Postfachdaten anzuwenden.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 und SharePoint Plan 2 bieten einem Benutzer die Rechte, von einer grundlegenden Aufbewahrungsrichtlinie für SharePoint oder OneDrive zu profitieren und/oder manuell eine Aufbewahrungsbezeichnung ohne Datensatz auf Dateien in SharePoint oder OneDrive anzuwenden.

Organisationen können Aufbewahrungsrichtlinien verwenden, um Teams-Nachrichten gemäß ihren Richtlinien zu speichern oder zu löschen. Dies umfasst das Verwalten von Nachrichten in Teams-Chats und -Unterhaltungen.

Die folgenden Lizenzen bieten einem Benutzer die Rechte, von einer Aufbewahrungsrichtlinie für Teams zu profitieren:

- Microsoft 365 E5/G5/A5/E3/G3/A3
- Office 365 E5/G5/A5/E3/G3/A3/F3/E1/G1

Beachten Sie, dass für Benutzer mit den folgenden Lizenzen der unterstützte Mindestaufbewahrungs- oder Löschzeitraum 30 Tage beträgt:

- Microsoft 365 F1/F3, Business Basic, Business Standard und Business Premium
- Office 365 E1/G1 und F3

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5, und Office 365 E5/A5 bieten einem Benutzer die Rechte, automatisch Aufbewahrungsbezeichnungen oder -richtlinien anzuwenden, Standardaufbewahrungsbezeichnungen oder -richtlinien anzuwenden, den Aufbewahrungszeitraum einer Aufbewahrungsbezeichnung basierend auf einem benutzerdefinierten Ereignis zu starten, eine manuelle Löschungsprüfung am Ende des Aufbewahrungszeitraums der Bezeichnung auszulösen, Drittanbieterdaten über systemeigene Datenconnectors zu importieren, eine Datei als Datensatz zu deklarieren, gekennzeichnete Inhalte zu ermitteln und Bezeichnungsaktivitäten zu überwachen.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection und Governance bieten einem Benutzer die Rechte, von der automatischen Anwendung von Aufbewahrungsbezeichnungen basierend auf trainierbaren Klassifizierern zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Information Governance-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Information Governance zum Anwenden der automatischen Bezeichnung und Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Information Governance in Microsoft 365.](/microsoft-365/compliance/manage-information-governance)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Features für die Informationsgovernance können auf lizenzierte Benutzer an bestimmten Orten (Teamwebsites, Gruppenwebsites usw.) angewendet werden. Informationen zum Konfigurieren von Information Governance zum Anwenden der automatischen Bezeichnung und Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Information Governance in Microsoft 365.](/microsoft-365/compliance/manage-information-governance)

## <a name="records-management"></a>Datensatzverwaltung

Die Datensatzverwaltung hilft Organisationen bei der Erfüllung ihrer geschäftlichen und behördlichen Verpflichtungen zur Datensatzführung durch Ermitteln, Klassifizieren, Bezeichnen, Aufbewahren und verdeckender Löschungsfunktionen in ihren Microsoft 365- und Drittanbieterdaten.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von der Datensatzverwaltung zu profitieren, einschließlich des Deklarierens von Elementen als Datensätze oder regulatorischer Datensätze, des automatischen Anwendens von Aufbewahrungs- oder Datensatzbezeichnungen und des Ausführens von Löschungsüberprüfungsprozessen (mit Ausnahme der automatischen Anwendung einer Aufbewahrungsbezeichnung basierend auf trainierbaren Klassifizierern).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance bieten einem Benutzer die Rechte, von der automatischen Anwendung von Aufbewahrungs- oder Datensatzbezeichnungen basierend auf trainierbaren Klassifizierern zu profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von der Möglichkeit, Inhalte als Datensatz zu deklarieren und ihren vollständigen Datensatzprozess von der Richtliniendefinition und -deklaration aus durch eine verwendbare Entsorgung zu verwalten.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Datensatzverwaltungsfunktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren der Datensatzverwaltung für lizenzierte Benutzer finden Sie unter [Informationen zur Datensatzverwaltung in Microsoft 365.](/microsoft-365/compliance/records-management)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Die Datensatzverwaltungsfeatures können auf lizenzierte Benutzer an bestimmten Orten (Teamwebsites, Gruppenwebsites usw.) angewendet werden. Informationen zum Konfigurieren der Datensatzverwaltung für lizenzierte Benutzer finden Sie unter [Informationen zur Datensatzverwaltung in Microsoft 365.](/microsoft-365/compliance/records-management)

## <a name="data-connectors"></a>Datenconnectors 

Microsoft stellt Datenconnectors von Drittanbietern bereit, die im Microsoft 365 Compliance Center konfiguriert werden können. Eine Liste der von Microsoft bereitgestellten Datenkonnektoren finden Sie in der [Tabelle "Datenkonnektoren](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) von Drittanbietern". Diese Tabelle enthält außerdem eine Zusammenfassung der Compliancelösungen, die Sie nach dem Importieren und Archivieren von Daten in Microsoft 365 auf Drittanbieterdaten anwenden können, sowie Links zu den schrittweisen Anweisungen für jeden Connector.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Der Hauptvorteil der Verwendung von Datenconnectors zum Importieren und Archivieren von Daten von Drittanbietern in Microsoft 365 besteht darin, dass Sie verschiedene Microsoft 365-Compliancelösungen auf die Daten anwenden können, nachdem sie importiert wurden. Dadurch wird sichergestellt, dass die Nicht-Microsoft-Daten Ihrer Organisation den Vorschriften und Standards entsprechen, die sich auf Ihre Organisation auswirken.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Die folgenden Lizenzen bieten einem Benutzer die Rechte, von Datenconnectors zu profitieren:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Info Protection &amp; Governance
- Microsoft 365 E5/A5/G5 Compliance
- Microsoft 365 E5/A5/G5 Insider-Risikomanagement
- Microsoft 365 E5/A5/G5 eDiscovery und Überwachung
- Office 365 E5/A5/G5

Für Datenconnectors im Microsoft 365 Security &amp; Compliance Center, die von einem Microsoft-Partner bereitgestellt werden, benötigt Ihre Organisation eine Geschäftsbeziehung mit dem Partner, bevor Sie diese Connectors bereitstellen können.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Connectors werden mithilfe des Security &amp; Compliance Centers und des Connector-Katalogs konfiguriert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Datenkonnektordienste sind ein Wert auf Mandantenebene. Jeder Benutzer, der von diesem Dienst profitieren möchte, muss lizenziert sein.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Microsoft Graph-APIs für Die Verhinderung von Datenverlust in Teams (Data Loss Prevention, DLP)

Anfang dieses Jahres haben wir [die öffentliche Vorschau der Microsoft Graph-Änderungsbenachrichtigungs-API für Nachrichten in Teams angekündigt.](https://go.microsoft.com/fwlink/?linkid=2143888) Mit dieser API können Entwickler Apps erstellen, die Microsoft Teams-Nachrichten nahezu in Echtzeit abhören und DLP-Szenarioimplementierungen für Kunden und ISVs aktivieren können. Darüber hinaus ermöglicht die Microsoft Graph-Patch-API das Anwenden von DLP-Aktionen auf Teams-Nachrichten.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

[DLP-Funktionen (Data Loss Prevention, Verhinderung von Datenverlust)](/microsoft-365/compliance/dlp-microsoft-teams) werden in Microsoft Teams häufig verwendet, insbesondere, wenn Organisationen auf Remotearbeit umgestellt sind. Wenn Ihre Organisation über DLP verfügt, können Sie jetzt Richtlinien definieren, die verhindern, dass Personen vertrauliche Informationen in einem Microsoft Teams-Kanal oder einer Chatsitzung freigeben.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Sie benötigen eine der folgenden Lizenzen, um Unterstützung für den DLP-Schutz im Teams-Chat zu erhalten:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Compliance
- Microsoft 365 E5/A5/G5 Information Protection and Governance
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Der API-Zugriff wird auf Mandantenebene konfiguriert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Die Microsoft Graph-API für Teams-DLP ist ein Wert auf Mandantenebene. Jeder Benutzer, der von diesem Dienst profitieren möchte, muss lizenziert sein.

## <a name="ediscovery"></a>eDiscovery

eDiscovery bietet Untersuchungs- und eDiscovery-Lösungen für IT- und Rechtsabteilungen innerhalb von Unternehmen, um Inhalte im Zusammenhang mit einer Untersuchung oder einem Rechtsstreitigkeiten vor dem Export aus dem Microsoft 365-System zu identifizieren, zu sammeln, beizubehalten, zu reduzieren und zu überprüfen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Ein Benutzer profitiert von Advanced eDiscovery, wenn der Benutzer als Datenverwahrer (eine Person mit administrativer Kontrolle über ein Dokument oder eine elektronische Datei) für einen Fall ausgewählt wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3 bieten einem Benutzer die Rechte, von Core eDiscovery zu profitieren.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 eDiscovery and Audit und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von Advanced eDiscovery zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Advanced eDiscovery-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert, wenn Administratoren eDiscovery-Berechtigungen im Security &amp; Compliance Center zuweisen.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

eDiscovery-Administratoren können bestimmte Benutzer als Datenverwahrer für einen Fall auswählen, indem sie das integrierte Verwaltungstool für Verwahrer in Advanced eDiscovery verwenden, wie unter Hinzufügen von [Verwahrern zu einem Advanced eDiscovery-Fall](/microsoft-365/compliance/add-custodians-to-case)beschrieben.

## <a name="customer-key-for-microsoft-365"></a>Kundenschlüssel für Microsoft 365

Mit Customer Key steuern Sie die Verschlüsselungsschlüssel Ihrer Organisation und konfigurieren Microsoft 365 so, dass sie zum Verschlüsseln Ihrer ruhenden Daten in Microsoft-Rechenzentren verwendet werden. Mit anderen Worten: Mit Customer Key können Sie eine Verschlüsselungsebene hinzufügen, die Ihnen gehört, indem Sie Ihre eigenen Schlüssel verwenden. Ruhedaten umfassen Daten aus Exchange Online und Skype for Business, die in Postfächern und Dateien in SharePoint Online und OneDrive for Business gespeichert sind.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von Customer Key, indem ihre ruhenden Daten auf der Anwendungsebene mithilfe von Verschlüsselungsschlüsseln verschlüsselt werden, die von ihrer eigenen Organisation bereitgestellt, gesteuert und verwaltet werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von Customer Key zu profitieren. Um den vollen Nutzen von Customer Key zu erhalten, müssen Sie auch über ein Abonnement für Azure Key Vault verfügen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Kundenschlüssel für Microsoft 365-Verschlüsselungsschlüssel können für alle Daten aktiviert werden, die in Exchange Online- und Skype for Business-Postfächern sowie SharePoint Online-, OneDrive for Business- und Teams-Dateien gespeichert sind. Weitere Informationen zu Customer Key, einschließlich der ersten Schritte, finden Sie unter [Dienstverschlüsselung mit Customer Key.](/microsoft-365/compliance/customer-key-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Für Exchange Online und Skype for Business können Postfächer mithilfe von Customer Key verschlüsselt werden. Sie müssen Azure einrichten, bevor Sie Customer Key für Microsoft 365 verwenden können. Informationen zu den Schritten, die Sie ausführen müssen, um die erforderlichen Azure-Ressourcen zu erstellen und zu konfigurieren, sowie die Schritte zum Einrichten von Customer Key in Microsoft 365 finden Sie unter ["Einrichten](/microsoft-365/compliance/customer-key-set-up) von Kundenschlüssel". Bestimmen Sie nach Abschluss des Azure-Setups, welche Richtlinie und daher welche Schlüssel Postfächern und Dateien in Ihrer Organisation zugewiesen werden sollen. Weitere Informationen zu Customer Key und Inhalten zu Daten aus Exchange Online, Skype for Business, SharePoint Online, OneDrive for Business und Teams finden Sie unter [Dienstverschlüsselung mit Customer Key.](/microsoft-365/compliance/customer-key-overview)

## <a name="office-365-customer-lockbox"></a>Office 365-Kunden-Lockbox

Kunden-Lockbox bietet eine zusätzliche Steuerungsebene, indem Kunden die Möglichkeit geboten wird, explizite Zugriffsautorisierung für Dienstvorgänge zu erteilen. Durch den Nachweis, dass Verfahren für die explizite Autorisierung des Datenzugriffs eingerichtet sind, kann die Kunden-Lockbox Organisationen auch dabei helfen, bestimmte Complianceverpflichtungen wie HIPAA und FedRAMP zu erfüllen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Kunden-Lockbox stellt sicher, dass niemand bei Microsoft ohne die ausdrückliche Genehmigung des Kunden auf Kundeninhalte zugreifen kann, um einen Dienstvorgang auszuführen. Kunden-Lockbox bringt den Kunden in den Genehmigungsworkflow für Anforderungen für den Zugriff auf seine Inhalte. Gelegentlich sind Microsoft-Techniker während des Supportprozesses beteiligt, um von Kunden gemeldete Probleme zu beheben und zu beheben. In den meisten Fällen werden Probleme durch umfangreiche Telemetrie- und Debuggingtools behoben, die Microsoft für seine Dienste zur Verfügung hat. Es kann jedoch Fälle geben, in denen ein Microsoft-Techniker auf Kundeninhalte zugreifen muss, um die Ursache zu ermitteln und das Problem zu beheben. Kunden-Lockbox setzt voraus, dass der Techniker den Zugriff vom Kunden als letzten Schritt im Genehmigungsworkflow anfordert. Dadurch haben Organisationen die Möglichkeit, diese Anforderungen zu genehmigen oder zu verweigern, wodurch sie direkt steuern können, ob ein Microsoft-Techniker auf die Endbenutzerdaten der Organisation zugreifen kann.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Insider Risk Management bieten einem Benutzer die Rechte, von der Kunden-Lockbox zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren können den Kunden-Lockbox im Microsoft 365 Admin Center aktivieren. Weitere Informationen finden Sie unter [Kunden-Lockbox in Office 365.](/microsoft-365/compliance/customer-lockbox-requests) Wenn die Kunden-Lockbox aktiviert ist, muss Microsoft die Genehmigung einer Organisation einholen, bevor auf einen ihrer Inhalte zugegriffen wird.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Derzeit kann der Kunden-Lockbox-Dienst nicht auf bestimmte Benutzer beschränkt werden. Obwohl die Mandantendienste derzeit nicht in der Lage sind, die Vorteile für bestimmte Benutzer einzuschränken, sollten Sie sich bemühen, die Dienstvorteile auf lizenzierte Benutzer zu beschränken. Dies trägt dazu bei, potenzielle Dienstunterbrechungen zu vermeiden, sobald Zielfunktionen verfügbar sind.

## <a name="privileged-access-management-in-office-365"></a>Privileged Access Management in Office 365

[Privileged Access Management (PAM)](/microsoft-365/compliance/privileged-access-management-configuration) bietet eine präzise Zugriffssteuerung für privilegierte Administratoraufgaben in Office 365. Nach der Aktivierung von PAM müssen Benutzer zum Ausführen von Aufgaben mit erhöhten und privilegierten Rechten Just-in-Time-Zugriff über einen Genehmigungsworkflow anfordern, der in hohem Umfang und zeitgebunden ist.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Durch die Aktivierung von PAM können Organisationen ohne ständige Berechtigungen arbeiten. Benutzer profitieren von der zusätzlichen Schutzebene gegen Sicherheitsrisiken, die sich aus dem ständigen administrativen Zugriff ergeben, der uneingeschränkten Zugriff auf ihre Daten ermöglicht.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und Microsoft 365 E5/A5 Information Protection and Governance bieten einem Benutzer die Rechte, von PAM zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind PAM-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von PAM-Richtlinien finden Sie unter ["Erste Schritte mit privileged access management".](/microsoft-365/compliance/privileged-access-management-configuration)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Kunden können PAM pro Benutzer über Genehmigergruppen und Zugriffsrichtlinien verwalten, die auf lizenzierte Benutzer angewendet werden können. Weitere Informationen finden Sie unter [Privileged Access Management in Office 365.](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751)

## <a name="double-key-encryption-for-microsoft-365"></a>Doppelschlüsselverschlüsselung für Microsoft 365 

Mit der Doppelschlüsselverschlüsselung für Microsoft 365 können Sie Ihre streng vertraulichen Daten schützen, um spezielle Anforderungen zu erfüllen und die vollständige Kontrolle über Ihren Verschlüsselungsschlüssel zu behalten. Die Verschlüsselung mit Doppelschlüssel verwendet zwei Schlüssel zum Schutz Ihrer Daten, wobei ein Schlüssel in Ihrem Steuerelement und der zweite Schlüssel von Microsoft Azure sicher gespeichert werden. Um die Daten anzuzeigen, müssen Sie Zugriff auf beide Schlüssel haben. Da Microsoft nur auf einen Schlüssel zugreifen kann, sind Ihr Schlüssel und auch Ihre Daten für Microsoft nicht verfügbar, um sicherzustellen, dass Sie die vollständige Kontrolle über den Datenschutz und die Sicherheit Ihrer Daten haben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von der Doppelschlüsselverschlüsselung, indem sie ihre verschlüsselten Daten in die Cloud migrieren können, wodurch der Zugriff von Drittanbietern verhindert wird, solange der Schlüssel die Kontrolle über die Benutzer hat. Benutzer können verschlüsselte Inhalte mit Doppelschlüssel schützen und nutzen, ähnlich wie alle anderen geschützten Inhalte mit Vertraulichkeitsbezeichnungen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von der Verschlüsselung mit Doppelschlüssel zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Double Key Encryption unterstützt die Desktopversion von Microsoft Office für Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Um Daten in einer Office 365- und/oder Microsoft 365-Organisation Verschlüsselungsschlüssel für lizenzierte Benutzer zuzuweisen, befolgen Sie die Bereitstellungsanweisungen für die Doppelschlüsselverschlüsselung.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Verhinderung von Datenverlust in Office 365 für Exchange Online, SharePoint Online und OneDrive for Business

Mit Office 365 Data Loss Prevention (DLP) für Exchange Online, SharePoint Online und OneDrive for Business können Organisationen vertrauliche Informationen über E-Mails und Dateien hinweg identifizieren, überwachen und automatisch schützen (einschließlich Dateien, die in Microsoft Teams-Dateirepositorys gespeichert sind).

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von DLP für Exchange Online, SharePoint Online und OneDrive for Business, wenn ihre E-Mails und Dateien auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 und Office 365 Data Loss Prevention bieten einem Benutzer die Rechte, von Office 365 DLP für Exchange Online, SharePoint Online und OneDrive for Business zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Exchange Online-E-Mails, SharePoint-Websites und OneDrive-Konten *aktivierte Speicherorte (Workloads)* für diese DLP-Features für alle Benutzer innerhalb des Mandanten. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie unter ["Übersicht über die Verhinderung von Datenverlust".](/microsoft-365/compliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security &amp; Compliance Center unter "Speicherorte **zur Verhinderung von Datenverlust"**  >  anpassen.

## <a name="communication-data-loss-prevention-for-teams"></a>Verhinderung von Kommunikationsdatenverlust für Teams

Mit Kommunikations-DLP für Teams können Organisationen Chats und Kanalnachrichten blockieren, die vertrauliche Informationen enthalten, z. B. Finanzinformationen, persönlich identifizierende Informationen, gesundheitsbezogene Informationen oder andere vertrauliche Informationen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Information Protection and Governance können von Kommunikations-DLP für Teams profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Absender profitieren davon, dass vertrauliche Informationen in ihren ausgehenden Chat- und Kanalnachrichten auf vertrauliche Informationen geprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Teams-Chat- und -Kanalnachrichten ein *aktivierter Speicherort (Workload)* für diese DLP-Features für alle Benutzer innerhalb des Mandanten. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie unter ["Übersicht über die Verhinderung von Datenverlust".](/office365/securitycompliance/data-loss-prevention-policies)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Speicherorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security &amp; Compliance Center unter "Speicherorte **zur Verhinderung von Datenverlust"**  >  anpassen.

## <a name="information-barriers"></a>Informationsbarrieren

Informationsbarrieren sind Richtlinien, die ein Administrator konfiguriert, um zu verhindern, dass Einzelpersonen oder Gruppen miteinander kommunizieren können. Dies ist beispielsweise nützlich, wenn eine Abteilung Informationen verarbeitet, die nicht mit anderen Abteilungen geteilt werden sollen, oder wenn eine Gruppe daran gehindert werden muss, mit externen Kontakten zu kommunizieren. Richtlinien für Informationsbarrieren verhindern auch Nachschlagevorgänge und Ermittlungen. Dies bedeutet: Wenn Sie versuchen, mit einer Person zu kommunizieren, mit der Sie nicht kommunizieren sollten, finden Sie diesen Benutzer nicht in der Personenauswahl.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von den erweiterten Compliance-Funktionen von Informationsbarrieren, wenn sie nicht mit anderen kommunizieren können. Richtlinien für Informationsbarrieren können definiert werden, um zu verhindern, dass bestimmte Benutzersegmente mit jedem Segment kommunizieren, oder dass bestimmte Segmente nur mit bestimmten anderen Segmenten kommunizieren können. Weitere Informationen zum Definieren von Richtlinien für Informationsbarrieren finden Sie unter [Definieren von Richtlinien für Informationsbarrieren.](/microsoft-365/compliance/information-barriers-policies) Für Szenarien, in denen zwei Gruppen nicht miteinander kommunizieren können, benötigen Benutzer in beiden Gruppen eine Lizenz, um vom Dienst zu profitieren (siehe beispiel unten).<br><br>

| Szenario | Wer benötigt eine Lizenz? |
|:------|:------|
| Zwei Gruppen (Gruppe &nbsp; 1 und Gruppe &nbsp; 2) können nicht miteinander kommunizieren (d. h. Benutzer der Gruppe &nbsp; 1 können nicht mit Benutzern der Gruppe &nbsp; 2 kommunizieren, und Benutzer der Gruppe &nbsp; 2 können nicht mit Benutzern der Gruppe &nbsp; 1 kommunizieren. | Benutzer in Gruppe &nbsp; 1 und Gruppe &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Insider Risk Management und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von Informationsbarrieren zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Richtlinien für Informationsbarrieren mithilfe von PowerShell-Cmdlets im Security &amp; Compliance Center. Administratoren muss die Rolle "Globaler Administrator von Microsoft 365 Enterprise", "Globaler Office 365-Administrator" oder "Complianceadministrator" zugewiesen werden, um eine Richtlinie für Informationsbarrieren zu erstellen. Standardmäßig gelten diese Richtlinien für alle Benutzer im Mandanten. Weitere Informationen zu Informationsbarrieren finden Sie unter ["Informationsbarrieren" in Microsoft Teams.](/MicrosoftTeams/information-barriers-in-teams)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Standorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security &amp; Compliance Center anpassen. Wenn beispielsweise alle Benutzer für Office 365 E3 und keine für Office 365 Advanced Compliance/E5 lizenziert sind, müssten sie keine Richtlinien für Informationsbarrieren für die Organisation erstellen. Weitere Informationen finden Sie unter [Informationsbarrieren in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

Office 365-Nachrichtenverschlüsselung (Office Message Encryption, OME) ist ein Dienst, der auf Azure Rights Management (Azure RMS) aufbaut und mit dem Sie verschlüsselte E-Mails an Personen innerhalb oder außerhalb Ihrer Organisation senden können, unabhängig von der E-Mail-Zieladresse (Gmail, Yahoo! Mail, Outlook.com usw.).

Zum Anzeigen verschlüsselter Nachrichten können Empfänger eine einmalige Kennung abrufen, sich mit einem Microsoft-Konto anmelden oder sich mit einem Geschäfts-, Schul- oder Unikonto, das Office 365 zugeordnet ist, anmelden. Empfänger können auch verschlüsselte Antworten senden. Sie benötigen kein Abonnement, um verschlüsselte Nachrichten anzuzeigen oder verschlüsselte Antworten zu senden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Nachrichtensender profitieren von der zusätzlichen Kontrolle über vertrauliche E-Mails, die von der Office 365-Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 und Azure Information Protection Plan 1 bieten einem Benutzer die Rechte, von der Office 365-Nachrichtenverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Office 365-Nachrichtenverschlüsselungsrichtlinien im Exchange Admin Center unter **"Nachrichtenflussregeln".**  >   Standardmäßig gelten diese Regeln für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Office 365-Nachrichtenverschlüsselungsfunktionen finden Sie unter ["Einrichten neuer Nachrichtenverschlüsselungsfunktionen".](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenflussregeln für die Office 365-Nachrichtenverschlüsselung nur auf lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenflussregeln finden Sie unter [Definieren von Nachrichtenflussregeln zum Verschlüsseln von E-Mail-Nachrichten.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="office-365-advanced-message-encryption"></a>Erweiterte Office 365-Nachrichtenverschlüsselung

Office 365 Advanced Message Encryption hilft Kunden bei der Einhaltung von Compliance-Verpflichtungen, die flexiblere Kontrollen über externe Empfänger und deren Zugriff auf verschlüsselte E-Mails erfordern. Mit der erweiterten Nachrichtenverschlüsselung können Administratoren vertrauliche E-Mails, die außerhalb der Organisation freigegeben wurden, mithilfe automatischer Richtlinien steuern, die typen vertraulicher Informationen erkennen können (z. B. persönliche Informationen oder Finanz- oder Gesundheits-IDs), oder sie können Schlüsselwörter verwenden, um den Schutz zu verbessern, indem sie benutzerdefinierte E-Mail-Vorlagen anwenden und den Zugriff auf verschlüsselte E-Mails über ein sicheres Webportal ablaufen lassen. Darüber hinaus können Administratoren verschlüsselte E-Mails, auf die extern über ein sicheres Webportal zugegriffen wird, weiter steuern, indem sie den Zugriff jederzeit widerrufen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Nachrichtensender profitieren von der zusätzlichen Kontrolle über vertrauliche E-Mails, die von der erweiterten Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Information Protection and Governance bieten einem Benutzer die Rechte, von der erweiterten Nachrichtenverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten erweiterte Nachrichtenverschlüsselungsrichtlinien im Exchange Admin Center unter **Nachrichtenflussregeln.**  >   Standardmäßig gelten diese Regeln für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Nachrichtenverschlüsselungsfunktionen finden Sie unter [Einrichten neuer Office 365-Nachrichtenverschlüsselung Funktionen.](/office365/securitycompliance/set-up-new-message-encryption-capabilities)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenflussregeln für die erweiterte Nachrichtenverschlüsselung nur auf lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenflussregeln finden Sie unter [Definieren von Nachrichtenflussregeln zum Verschlüsseln von E-Mail-Nachrichten in Office 365.](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email)

## <a name="communication-compliance"></a>Kommunikationscompliance

Die Kommunikationscompliance in Microsoft 365 trägt dazu bei, Kommunikationsrisiken zu minimieren, indem sie Ihnen dabei hilft, unangemessene Nachrichten in Ihrer Organisation zu erkennen, zu erfassen und zu beheben. Sie können bestimmte Richtlinien definieren, die interne und externe E-Mails, Microsoft Teams oder Kommunikationen von Drittanbietern in Ihrer Organisation erfassen. Prüfer können geeignete Korrekturmaßnahmen ergreifen, um sicherzustellen, dass sie den Nachrichtenstandards Ihrer Organisation entsprechen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Compliance-Spezialisten profitieren von dem Dienst, indem sie die Kommunikation der Organisation anhand von Kommunikationscompliancerichtlinien überwachen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Insider Risk Management bieten einem Benutzer die Rechte, von der Kommunikationscompliance zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren und Compliance-Spezialisten erstellen Kommunikationscompliancerichtlinien im Microsoft 365 Compliance Center. Diese Richtlinien definieren, welche Kommunikationen und Benutzer in der Organisation überprüft werden, definieren benutzerdefinierte Bedingungen, die die Kommunikation erfüllen muss, und geben an, wer Überprüfungen durchführen soll.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren wählen bestimmte Benutzer oder Gruppen aus, die in eine Richtlinie zur Kommunikationscompliance einbezogen werden sollen. Bei der Auswahl einer Gruppe können sie auch bestimmte Benutzer in der Gruppe auswählen, die von der Richtlinie zur Kommunikationscompliance ausgeschlossen werden sollen. Weitere Informationen zu Richtlinien zur Kommunikationscompliance finden Sie unter ["Erste Schritte mit der Kommunikationscompliance" in Microsoft 365.](/microsoft-365/compliance/communication-compliance-configure)

## <a name="insider-risk-management"></a>Insider-Risikomanagement

Das Insider-Risikomanagement ist eine Lösung in Microsoft 365, die interne Risiken minimiert, indem Sie riskante Aktivitäten in Ihrer Organisation erkennen, untersuchen und maßnahmen ergreifen können.

Benutzerdefinierte Richtlinien ermöglichen es Ihnen, bösartige und versehentlich riskante Aktivitäten in Ihrer Organisation zu erkennen und maßnahmen zu ergreifen, einschließlich der Eskalation von Fällen an Microsoft Advanced eDiscovery, falls erforderlich. Risikoanalysten in Ihrer Organisation können schnell geeignete Maßnahmen ergreifen, um sicherzustellen, dass die Benutzer den Compliance-Standards Ihrer Organisation entsprechen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren davon, dass ihre Aktivitäten auf Risiken überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Insider Risk Management bieten einem Benutzer die Rechte, von Insider-Risikomanagement zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Richtlinien für das Insider-Risikomanagement müssen im Microsoft 365 Compliance Center erstellt und Benutzern zugewiesen werden.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Wählen Sie beim Erstellen einer Richtlinie im Microsoft 365 Compliance Center auf der Seite **"Benutzer und Gruppen** auswählen" die Option **"Benutzer oder Gruppen** auswählen" aus, um nur lizenzierte Benutzer auszuwählen. Wenn alle Ihre Benutzer lizenziert sind, können Sie das Kontrollkästchen **"Alle Benutzer und E-Mail-aktivierte Gruppen"** aktivieren. Weitere Informationen finden Sie unter ["Erste Schritte mit dem Insider-Risikomanagement".](/microsoft-365/compliance/insider-risk-management-configure)

## <a name="conditional-access-policies"></a>Richtlinien für bedingten Zugriff

Der bedingte Zugriff ist das Tool, das von Azure Active Directory verwendet wird, um Signale zusammenzuführen, Entscheidungen zu treffen und Organisationsrichtlinien durchzusetzen. Der bedingte Zugriff ist das Herzstück der identitätsgesteuerten Steuerung. Richtlinien für bedingten Zugriff sind am einfachsten If-then-Anweisungen. Wenn ein Benutzer auf eine Ressource zugreifen möchte, muss er eine Aktion ausführen. Beispiel: Ein Gehaltsabrechnungsmanager möchte auf die Gehaltsabrechnungsanwendung zugreifen und muss eine mehrstufige Authentifizierung durchführen, um darauf zugreifen zu können.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium und Azure Active Directory Premium Plan 1 können von Richtlinien für bedingten Zugriff profitieren. Lizenzierte Benutzer von Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security und Azure Active Directory Premium Plan 2 können von Identity Protection (risikobasierte Richtlinien für bedingten Zugriff) profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Sicherheitsanalysten und Sicherheitsexperten profitieren von der Möglichkeit, organisatorische Richtlinien für Benutzer durchzusetzen, die erfordern, dass sie bestimmte Kriterien erfüllen, bevor sie Zugriff auf Unternehmensinhalte gewähren. Endbenutzer profitieren davon, dass sie jederzeit und überall auf ihre Arbeit zugreifen können und gleichzeitig die Ressourcen der Organisation schützen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Features für bedingten Zugriff auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Speziell für Identitätsschutz und bedingten Zugriff muss ein Benutzer in eine Gruppe eingeschlossen oder einer Richtlinie für bedingten Zugriff hinzugefügt werden. Die Bedingung für Benutzer und Gruppen ist in einer Richtlinie für bedingten Zugriff obligatorisch. In Ihrer Richtlinie können Sie entweder **alle Benutzer** oder bestimmte Benutzer und Gruppen auswählen. Sie sollten nur entsprechend lizenzierte Benutzer und Gruppen auswählen. Weitere Informationen finden Sie unter ["Bedingter Zugriff: Bedingungen".](/azure/active-directory/conditional-access/conditions)

## <a name="advanced-audit"></a>Erweiterte Überwachung

Die erweiterte Überwachung in Microsoft 365 bietet eine einjährige Aufbewahrung von Überwachungsprotokollen für Benutzer- und Administratoraktivitäten und bietet die Möglichkeit, benutzerdefinierte Aufbewahrungsrichtlinien für Überwachungsprotokolle zu erstellen, um die Aufbewahrung von Überwachungsprotokollen für andere Microsoft 365-Dienste zu verwalten. Es bietet auch Zugriff auf wichtige Ereignisse für Untersuchungen und Zugriff mit hoher Bandbreite auf die Office 365-Verwaltungsaktivitäts-API. Weitere Informationen finden Sie unter ["Erweiterte Überwachung" in Microsoft 365.](/microsoft-365/compliance/advanced-audit)

Sie können auch einen Aufbewahrungszeitraum von 10 Jahren mit einer Add-On-SKU aktivieren. Die Add-On-SKU ist ab Anfang 2021 erforderlich.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 eDiscovery und Überwachung können von der erweiterten Überwachung profitieren.

Lizenzierte Benutzer mit erweiterter Überwachung und dem 10-Jahres-Add-On für die Aufbewahrung von Überwachungsprotokollen können von der 10-jahres-Aufbewahrung von Überwachungsprotokollen profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von der erweiterten Überwachung, da Überwachungsdatensätze im Zusammenhang mit Benutzeraktivitäten in Microsoft 365 Diensten bis zu einem Jahr aufbewahrt werden können. Darüber hinaus werden hochwertige Überwachungsereignisse protokolliert, z. B. wenn auf Elemente im Postfach eines Benutzers zugegriffen oder gelesen wird. Weitere Informationen finden Sie unter ["Erweiterte Überwachung" in Microsoft 365.](/microsoft-365/compliance/advanced-audit)

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig ist die erweiterte Überwachung auf Mandantenebene für alle Organisationen aktiviert, die über ein Office 365- oder Microsoft 365 E5/A5/G5-Abonnement verfügen, und bietet automatisch eine einjährige Aufbewahrung von Überwachungsprotokollen für Aktivitäten (die von Benutzern mit der entsprechenden Lizenz ausgeführt werden) in Azure Active Directory, Exchange und SharePoint. Darüber hinaus können Organisationen Aufbewahrungsrichtlinien für Überwachungsprotokolle verwenden, um den Aufbewahrungszeitraum für Überwachungsdatensätze zu verwalten, die von Aktivitäten in anderen Microsoft 365-Diensten generiert werden. Die 10-Jahres-Funktion für die Aufbewahrung von Überwachungsprotokollen ist auch mit denselben Aufbewahrungsrichtlinien aktiviert. Weitere Informationen finden Sie unter [Verwalten der Aufbewahrungsrichtlinien für Überwachungsprotokolle](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Die einjährige Aufbewahrung von Überwachungsprotokollen und die Überwachung wichtiger Ereignisse gelten nur für Benutzer mit der entsprechenden Lizenz. Darüber hinaus können Administratoren Aufbewahrungsrichtlinien für Überwachungsprotokolle verwenden, um kürzere Aufbewahrungsdauern für die Überwachungsprotokolle bestimmter Benutzer festzulegen.

Die 10-jahres-Aufbewahrung von Überwachungsprotokollen gilt nur für Benutzer mit der entsprechenden Add-On-Lizenz. Die Add-On-SKU ist ab Anfang 2021 erforderlich.