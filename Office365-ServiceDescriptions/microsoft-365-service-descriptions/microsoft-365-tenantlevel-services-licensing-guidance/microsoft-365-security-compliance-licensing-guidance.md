---
title: Microsoft 365-Lizenzierungsleitfaden für Sicherheits- & Compliance
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
description: Dieser Artikel enthält Anleitungen zur Lizenzierung Microsoft 365 Compliance, um potenzielle Dienstunterbrechungen aufgrund des nicht lizenzierten Zugriffs zu vermeiden.
ms.openlocfilehash: d4ddb9c492cccef13c86e450c64a2eb6efe61eaa
ms.sourcegitcommit: adcacf68ac75c4db2229ebf55be9c75aecd3070b
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 05/19/2021
ms.locfileid: "52546012"
---
# <a name="microsoft-365-licensing-guidance-for-security-amp-compliance"></a>Microsoft 365-Lizenzierungsanleitung für die Einhaltung der &amp; Sicherheitsvorschriften

Für die Zwecke dieses Artikels ist ein Service auf Mandantenebene ein Onlinedienst, der beim &mdash; Kauf für einen Benutzer im Mandanten (standalone oder als Teil Office 365 oder Microsoft 365-Plänen) für alle Benutzer im Mandanten ganz oder teilweise aktiviert &mdash; wird. Obwohl einige nicht lizenzierte Benutzer technisch auf den Dienst zugreifen können, ist eine Lizenz für jeden Benutzer erforderlich, den Sie von dem Dienst in Anspruch nehmen möchten.

> [!NOTE]
> Einige Mandantendienste sind derzeit nicht in der Lage, die Vorteile auf bestimmte Benutzer zu beschränken. Es sollten Anstrengungen unternommen werden, um die Servicevorteile auf lizenzierte Benutzer zu beschränken. Dadurch können potenzielle Dienstunterbrechungen für Ihre Organisation vermieden werden, sobald Zielfunktionen verfügbar sind.

Um die Optionen für die Lizenzierung Ihrer Benutzer anzuzeigen, um von Microsoft 365 Compliance-Funktionen zu profitieren, laden Sie den detaillierten Microsoft 365 Compliance-Lizenzierungsvergleich herunter. [(PDF)](https://www.microsoft.com/download/details.aspx?id=103010)  |  [(Excel)](https://www.microsoft.com/download/details.aspx?id=103006)

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identitätsschutz ist ein Feature des Azure Active Directory Premium P2-Plans, mit dem Sie potenzielle Sicherheitsanfälligkeiten erkennen können, die sich auf die Identitäten Ihrer Organisation auswirken, automatisierte Antworten auf erkannte verdächtige Aktionen konfigurieren können, die mit den Identitäten Ihrer Organisation zusammenhängen, verdächtige Vorfälle untersuchen und geeignete Maßnahmen ergreifen können, um diese zu beheben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

SecOps-Analysten und Sicherheitsexperten profitieren von konsolidierten Ansichten von gekennzeichneten Benutzern und Risikoereignissen, die auf Machine Learning-Algorithmen basieren. Endbenutzer profitieren vom automatischen Schutz durch risikobasierten bedingten Zugriff und der verbesserten Sicherheit, die durch das Handeln auf Schwachstellen gewährleistet wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Azure Active Directory Premium Plan 2 bieten einem Benutzer die Rechte, von Azure Active Directory Identity Protection zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Azure AD Identity Protection-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Weitere Informationen zum Azure AD Identity Protection finden Sie unter [Was ist Identitätsschutz?](/azure/active-directory/identity-protection/overview-identity-protection)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Azure AD Identity Protection durch Zuweisen von Risikorichtlinien, die die Ebene für Kennwortzurücksetzungen definieren und den Zugriff nur für lizenzierte Benutzer zulassen, erweitern. Anweisungen zum Umfang von Azure AD Identity Protection-Bereitstellungen finden Sie unter Konfigurieren und Aktivieren von [Risikorichtlinien](/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-active-directory-identity-governance"></a>Azure Active Directory Identity Governance

Azure Active Directory Mit Identity Governance können Sie den Bedarf Ihrer Organisation an Sicherheit und Mitarbeiterproduktivität mit den richtigen Prozessen und Transparenz in Einklang bringen. Es verwendet Berechtigungsverwaltung, Zugriffsüberprüfungen, privilegierte Identitätsverwaltung und Nutzungsbedingungen, um sicherzustellen, dass die richtigen Personen den richtigen Zugriff auf die richtigen Ressourcen haben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Azure Active Directory Identity Governance steigert die Produktivität der Benutzer, indem sie den Zugriff auf Apps, Gruppen und Microsoft Teams in einem Zugriffspaket erleichtert. Benutzer können auch als Genehmiger konfiguriert werden, ohne Administratoren einzubeziehen. Für Zugriffsüberprüfungen können Benutzer Mitgliedschaften von Gruppen mit intelligenten Empfehlungen überprüfen, um in regelmäßigen Abständen Maßnahmen zu ergreifen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Security und Azure Active Directory Premium Plan 2 bieten einem Benutzer die Rechte, von Azure Active Directory Identity Governance zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Azure AD Identity Governance-Funktionen werden auf Mandantenebene aktiviert, aber pro Benutzer implementiert. Weitere Informationen zu Azure AD Identity Governance finden Sie unter [Was ist Azure AD Identity Governance?](/azure/active-directory/governance/identity-governance-overview)

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Azure AD Identity Governance durch Zuweisen von Zugriffspaketen, Zugriffsüberprüfungen oder privilegierter Identitätsverwaltung nur für lizenzierte Benutzer erweitern. Anweisungen zum Umfang von Azure AD Identity Governance-Bereitstellungen finden Sie unter:

- [Azure AD-Berechtigungsverwaltungslizenzanforderungen](/azure/active-directory/governance/entitlement-management-overview#license-requirements)
- [Azure AD-Zugriffsüberprüfungslizenzanforderungen](/azure/active-directory/governance/access-reviews-overview#license-requirements)
- [Lizenzanforderungen für die Nutzung Privileged Identity Management](/azure/active-directory/privileged-identity-management/subscription-requirements)

## <a name="microsoft-defender-for-identity"></a>Microsoft Defender for Identity

Microsoft Defender for Identity (früher Azure Advanced Threat Protection) ist ein Clouddienst, der Unternehmenshybridumgebungen vor mehreren Arten von erweiterten gezielten Cyberangriffen und Insiderbedrohungen schützt.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

SecOp-Analysten und Sicherheitsexperten profitieren von der Fähigkeit von Microsoft Defender for Identity, erweiterte Bedrohungen, kompromittierte Identitäten und böswillige Insider-Aktionen zu erkennen und zu untersuchen. Endbenutzer profitieren davon, dass ihre Daten von Microsoft Defender for Identity überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Enterprise Mobility + Security E5/A5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security und Microsoft Defender for Identity for Users bieten die Rechte, von Microsoft Defender for Identity zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender for Identity-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Azure ATP finden Sie unter [Erstellen ihrer Microsoft Defender for Identity-Instanz](/defender-for-identity/install-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender for Identity-Dienste sind derzeit nicht in der Lage, Funktionen auf bestimmte Benutzer zu beschränken. Sie müssen jedem Benutzer lizenzieren, von dem Sie profitieren möchten.

## <a name="microsoft-defender-for-office-365"></a>Microsoft Defender für Office 365

Microsoft Defender for Office 365 (früher Office 365 Advanced Threat Protection) schützt Unternehmen vor ausgeklügelten Angriffen wie Phishing und Zero-Day-Malware. Microsoft Defender for Office 365 bietet außerdem umsetzbare Einblicke, indem Signale aus einer breiten Palette von Daten korreliert werden, um potenzielle Bedrohungen zu identifizieren, zu priorisieren und Empfehlungen zu geben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Microsoft Defender for Office 365 schützt Benutzer vor ausgeklügelten Angriffen wie Phishing und Zero-Day-Malware. Die vollständige Liste der in Plan 1 und Plan 2 bereitgestellten Dienste finden Sie unter [Microsoft Defender für Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren? 

Microsoft Defender for Office 365 Plans 1 und 2, Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security und Microsoft 365 Business Premium einem Benutzer die Rechte zur Verfügung stellen, um von Microsoft Defender für Office 365 zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender für Office 365 Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Microsoft Defender für Office 365 Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Defender for Office 365](/microsoft-365/security/office-365-security/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Um Microsoft Defender für Office 365 zu erweitern, befolgen Sie die Bereitstellungsrichtlinien für sichere Links und sichere Anlagen:

- Informationen zum Konfigurieren sicherer Links für lizenzierte Benutzer finden Sie [unter Sichere Links in Microsoft Defender für Office 365](/microsoft-365/security/office-365-security/atp-safe-links).

- Informationen zum Konfigurieren sicherer Anlagen für lizenzierte Benutzer finden Sie unter [Sichere Anlagen in Microsoft Defender für Office 365](/microsoft-365/security/office-365-security/atp-safe-attachments).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud App Security (OCAS) ist eine Teilmenge Microsoft Cloud App Security mit Funktionen, die auf Office 365 und ohne zusätzliche Sicherheit für Cloud-Apps und IaaS-Dienste von Drittanbietern beschränkt sind.

OCAS gibt Unternehmen Einblick in ihre Produktivitäts-Cloud-Apps und -Dienste, bietet ausgeklügelte Analysen zur Identifizierung und Bekämpfung von Cyberbedrohungen und ermöglicht es ihnen, zu steuern, wie Daten über Office 365 hinweg &mdash; fließen.

Informationen zum Vergleichen von Features finden Sie unter [Unterschiede zwischen Microsoft Cloud App Security und Office 365 Cloud App Security](/cloud-app-security/editions-cloud-app-security-o365).

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

OCAS erkennt Shadow IT, bietet Bedrohungsschutz in Office 365 und kann steuern, welche Apps über die Berechtigung zum Zugriff auf Daten verfügen.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A3/A5/G5 bietet einem Nutzer die Rechte, von OCAS zu profitieren.
Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind OCAS-Funktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren des Dienstes finden Sie unter [Grundlegendes Einrichten für Cloud App Security](/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können OCAS-Bereitstellungen einschränken, um zu erzwingen, wie auf bestimmte Apps zugegriffen wird, und Benutzergruppen einzuschränken, die von Office 365 Cloud App Security überwacht werden. Weitere Informationen finden Sie unter [Bereichsbereitstellung](/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) ist eine Cloud Access Security Broker (CASB)-Lösung, die Unternehmen Einblick in ihre Cloud-Apps und -Dienste bietet, ausgeklügelte Analysen zur Identifizierung und Bekämpfung von Cyberbedrohungen bereitstellt und die Art und Weise steuern kann, wie Daten &mdash; über jede Cloud-App gesendet werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

MCAS entdeckt und bewertet shadow IT, bietet Bedrohungsschutz für Cloud-Apps von Erst- und Drittanbietern und schützt Informationen über Cloud-Apps von Erst- und Drittanbietern hinweg.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Security, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance bieten einem Benutzer die Rechte, mcAS zu nutzen.

Azure AD P1 bietet einem Benutzer die Rechte, von den Discovery-Funktionen in MCAS zu profitieren.

Um von den Funktionen der Conditional Access App Control in MCAS zu profitieren, müssen Benutzer auch für Azure Active Directory P1 lizenziert sein, das in Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/A3/G3, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Security enthalten ist.

Um von der automatischen clientseitigen Kennzeichnung zu profitieren, müssen Benutzer für Azure Information Protection P2 lizenziert sein, das in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance enthalten ist.

> [!NOTE]
> Die automatische serverseitige Kennzeichnung erfordert Informationsschutz für Office 365 - Premium Lizenzen ( `MIP_S_CLP2` oder `efb0351d-3b08-4503-993d-383af8de41e3` ). Weitere Informationen finden Sie unter [Produktnamen und Dienstplan-IDs für die Lizenzierung](/azure/active-directory/enterprise-users/licensing-service-plan-reference).

Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing Datasheet](https://www.aka.ms/mcaslicensing).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind MCAS-Funktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren Microsoft Cloud App Security Richtlinien für lizenzierte Benutzer finden Sie in [Microsoft Cloud App Security Übersicht](/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können MCAS-Bereitstellungen auf lizenzierte Benutzer ausderlassen, indem sie die im Dienst verfügbaren Bereitstellungsfunktionen verwenden. Weitere Informationen finden Sie unter [Bereichsbereitstellung](/cloud-app-security/scoped-deployment).

## <a name="compliance-manager"></a>Compliance-Manager

Vereinfachen Sie die Compliance und reduzieren Sie risiken mit Compliance Manager. Compliance Manager unterstützt Unternehmen dabei, die Anforderungen an Vorschriften, Standards, Unternehmensrichtlinien oder andere gewünschte Kontrollrahmen zu erfüllen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Im Folgenden sind die Vorteile für die Benutzer aus dem Compliance Manager-Service:

- Übersetzt komplizierte Vorschriften, Standards, Unternehmensrichtlinien oder andere gewünschte Kontrollrahmen in einfache Sprache
- Bietet Zugriff auf eine umfangreiche Bibliothek mit sofort einsatzbereiten Bewertungen und benutzerdefinierten Bewertungen, um einzigartige Compliance-Anforderungen zu erfüllen
- Karten regulatorischer Kontrollen zu empfohlenen Verbesserungsmaßnahmen
- Bietet Schritt-für-Schritt-Anleitungen zur Implementierung der Lösungen zur Erfüllung gesetzlicher Anforderungen
- Unterstützt Benutzer bei der Priorisierung von Aktionen, die die höchsten Auswirkungen auf die Compliance ihrer Organisation haben, indem sie jeder Aktion eine Punktzahl zuordnen

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Kunden mit E1- und E3/G3-Lizenzen können nur auf die standardmäßige Data Protection Baseline-Bewertung zugreifen. Kunden mit Office 365 E5/A5- und Microsoft 365 E5/A5-Lizenzen (Compliance, Info Protection & Governance sowie eDiscovery- und Audit-SKUs) können auf Data Protection Baseline, DSGVO, NIST 800-53 und ISO 27001 sofort einsatzbereite Bewertungen zugreifen. Kunden mit Office 365 G5 und Microsoft 365 G5 können auf Data Protection Baseline, DSGVO, NIST 800-53, ISO 27001 und Cybersecurity Maturity Model Certification (CMMC) Level 1 bis 5 Out-of-the-Box-Bewertungen zugreifen. Die kundenspezifische Bewertungsfunktion und Die Premium-Bewertungen sind Office 365 E5/A5/G5- und Microsoft 365 E5/A5/G5-Kunden vorbehalten. Premium-Bewertungen wie FedRAMP Moderate, FedRAMP High und andere, werden Kunden mit E5/A5/G5-Lizenzen im ersten Halbjahr 2021 über VL, CSP und WebDirect zum Kauf zur Verfügung stehen. Wenden Sie sich an Ihren Microsoft-Verkäufer oder Microsoft-Partner, um über VL- bzw. CSP-Kanäle zu kaufen. Informationen zum Kauf über WebDirect finden Sie unter [WebDirect](https://aka.ms/ComplianceManager/WebDirect).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Compliance Manager wird standardmäßig für Ihren Mandanten bereitgestellt. Administratoren legen Benutzerberechtigungen fest und weisen Rollen zu, damit Nicht-Admin-Benutzer in Ihrer Organisation mit dem Verwenden von Compliance Manager beginnen können. Weitere Informationen finden Sie unter [Erste Schritte mit Compliance Manager: Festlegen von Benutzerberechtigungen und Zuweisen von Rollen](/microsoft-365/compliance/compliance-manager-setup#set-user-permissions-and-assign-roles).

## <a name="microsoft-defender-for-endpoint"></a>Microsoft Defender für Endpunkt

Microsoft Defender for Endpoint (früher Microsoft Defender ATP) ist eine Endpunktsicherheitslösung, die risikobasierte Sicherheitsrisikomanagement und Bewertung umfasst. Angriffsoberflächenreduktionsfunktionen; verhaltensbasierter und cloudbasierter Schutz der nächsten Generation; EDR (EDR); automatische Untersuchung und Sanierung; und verwaltete Jagddienste. Weitere Informationen finden Sie auf [der Seite Microsoft Defender für Endpoint.](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)

### <a name="which-users-benefit-from-the-service"></a>Welche Nutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Windows 10 Enterprise E5, Windows 10 Education A5, Microsoft 365 E5/G5, einschließlich Windows 10 Enterprise E5, Microsoft 365 E5/A5/G5 Security, können von Microsoft Defender for Endpoint profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

SecOps-Analysten und Sicherheitsexperten profitieren von den Endpunktsicherheitsfunktionen von Microsoft Defender for Endpoint, um vorbeugenden Schutz, Erkennung nach der Verletzung, automatisierte Untersuchung und Reaktion auf erweiterte Bedrohungen durchzuführen. Endbenutzer profitieren davon, dass böswillige Ereignisse von Microsoft Defender for Endpoint überwacht werden.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Defender for Endpoint-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zur Bereitstellung finden Sie unter [Bereitstellungsphasen](/windows/security/threat-protection/microsoft-defender-atp/deployment-phases).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Defender for Endpoint-Administratoren können rollenbasierte Zugriffssteuerung (RBAC) verwenden, um Rollen und Gruppen innerhalb des Sicherheitsdienstteams zu erstellen, um den entsprechenden Zugriff auf die Microsoft Defender Security Center zu gewähren. Weitere Informationen finden Sie unter [Verwalten des Portalzugriffs mithilfe der rollenbasierten Zugriffssteuerung](/windows/security/threat-protection/microsoft-defender-atp/rbac).

## <a name="microsoft-365-data-classification-analytics-overview-content-amp-activity-explorer"></a>Microsoft 365 Datenklassifizierungsanalysen: Übersicht Content &amp; Activity Explorer

Datenklassifizierungsanalysefunktionen sind innerhalb Microsoft 365 Compliance Center-Erfahrung verfügbar. Die Übersicht zeigt die Speicherorte digitaler Inhalte und der häufigsten vertraulichen Informationstypen und -etiketten. Der Inhalts-Explorer bietet Einblick in Menge und Typen vertraulicher Daten und ermöglicht benutzern das Filtern nach Beschriftung oder Empfindlichkeitstyp, um eine detaillierte Ansicht der Speicherorte zu erhalten, an denen die vertraulichen Daten gespeichert werden. Der Aktivitäts-Explorer zeigt Aktivitäten im Zusammenhang mit vertraulichen Daten und Beschriftungen an, z. B. Beschriftungsdowngrades oder externe Freigaben, die Ihre Inhalte einem Risiko aussetzen könnten.

Der Aktivitäts-Explorer bietet einen einzelnen Glasbereich für Administratoren, um Einblick in Aktivitäten zu erhalten, die sich auf vertrauliche Informationen beziehen, die von Endbenutzern verwendet werden. Zu diesen Daten gehören Etikettenaktivitäten, DLP-Protokolle (Data Loss Prevention), Auto-Labeling, Endpoint DLP und mehr.

Der Inhalts-Explorer bietet Administratoren die Möglichkeit, vertrauliche Dokumente, die in unterstützten Microsoft 365-Workloads gespeichert sind, zu indizieren und die vertraulichen Informationen zu identifizieren, die sie speichern. Darüber hinaus hilft der Inhalts-Explorer dabei, Dokumente zu identifizieren, die mit Empfindlichkeits- und Aufbewahrungsbezeichnungen klassifiziert werden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Informationsschutz- und Compliance-Administratoren können auf den Dienst zugreifen, um Zugriff auf diese Protokolle und indizierten Daten zu erhalten, um zu verstehen, wo vertrauliche Daten gespeichert werden und welche Aktivitäten mit diesen Daten zusammenhängen und von Endbenutzern ausgeführt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Lizenzierte Benutzer von Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection &amp; Governance und Office 365 E5 können von Microsoft 365 Datenklassifizierungsanalysen profitieren. 

Microsoft 365 E3/A3/G3 und Office 365 E3/A3/G3 ermöglichen es Benutzern, nur von der Datenaggregation des Inhalts-Explorers zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind die Features "Übersichtsinhalt" und "Aktivitäts-Explorer" auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Datenklassifizierungsanalysen für lizenzierte Benutzer finden Sie unter:

- **Content Explorer**: [Erste Schritte mit Content Explorer - Microsoft 365 Compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-content-explorer).
- **Aktivitäts-Explorer**: [Erste Schritte mit Aktivitäts-Explorer - Microsoft 365 Compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-activity-explorer).
- **Versionshinweise** zur Datenklassifizierung : [Versionshinweise zur Datenklassifizierung - Microsoft 365 Compliance | Microsoft Docs](/microsoft-365/compliance/data-classification-pub-preview-relnotes).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Diese Funktion muss für Benutzer, die die Lösung aktiv im Microsoft 365 Compliance-Portal verwenden, in den Mittelpunkt stehen.

## <a name="information-protection"></a>Informationsschutz

Informationsschutz hilft Unternehmen dabei, vertrauliche Dokumente und E-Mails zu erkennen, zu klassifizieren, zu kennzeichnen und zu schützen. Administratoren können Regeln und Bedingungen definieren, um Beschriftungen automatisch anzuwenden, Benutzer können Beschriftungen manuell anwenden, oder eine Kombination aus beidem kann verwendet werden, wenn Benutzer Empfehlungen zum Anwenden von Etiketten erhalten.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren davon, dass sie die Möglichkeit haben, Empfindlichkeitsetiketten manuell auf ihren Inhalt anzuwenden, oder indem sie ihren Inhalt automatisch klassifiziert.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, Office 365 E5/A5/E3/A3/F3, AIP Plan 1 und AIP Plan 2 bieten einem Benutzer die Rechte, von der manuellen Empfindlichkeitskennzeichnung zu profitieren.

Microsoft 365 E5/A5/G5/E3/A3/G3/F1/F3/Business Premium, Enterprise Mobility + Security F3/E3/E5, AIP Plan 1 und AIP Plan 2 bieten einem Benutzer das Recht, von der Anwendung und Anzeige von Empfindlichkeitsetiketten in Power BI zu profitieren und Daten zu schützen, wenn sie von Power BI in Excel, PowerPoint oder PDF exportiert werden. 

> [!NOTE]
> Power BI ist in Microsoft 365 E5/A5/G5 enthalten; in allen anderen Plänen müssen Power BI separat lizenziert werden.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection und Governance, Office 365 E5, Enterprise Mobility + Security E5/A5/G5 und AIP Plan 2 bieten einem Benutzer die Rechte, von der automatischen Empfindlichkeitskennzeichnung zu profitieren.

Spezifische Rechte nach Lizenz finden Sie in der detaillierten Microsoft 365 Compliance-Lizenzierungsvergleich. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx) Enthält keine Rechte zur automatischen Klassifizierung auf der Grundlage Machine Learning (trainierbare Klassifikatoren).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Informationsschutzfunktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Richtlinien für lizenzierte Benutzer finden Sie unter Aktivieren von Azure Rights Management.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Außer bei Verwendung der AIP-Scannerfunktion können Richtlinien auf bestimmte Gruppen oder Benutzer beschränkt werden, und Registrierungsstellen können bearbeitet werden, um zu verhindern, dass nicht lizenzierte Benutzer Klassifizierungs- oder Beschriftungsfeatures ausführen. Anweisungen zum Bereichsumfang von AIP-Bereitstellungen finden Sie unter [Konfigurieren der Azure Information Protection-Richtlinie](/azure/information-protection/configure-policy).

Für die AIP-Scannerfunktion verpflichtet sich Microsoft nicht, Benutzern, die nicht lizenziert sind, Dateiklassifizierungs-, Beschriftungs- oder Schutzfunktionen zur Verfügung zu stellen.

## <a name="information-governance"></a>Information Governance

Information Governance hilft Unternehmen, ihr Risiko zu managen, indem sie ihre Daten ermitteln, klassifizieren, kennzeichnen und steuern. Mit Information Governance können Unternehmen geschäftliche und behördliche Anforderungen erfüllen und ihre Angriffsfläche reduzieren, indem sie Aufbewahrungs- und Löschfunktionen für ihre Microsoft 365 und Daten von Drittanbietern bereitstellen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren davon, dass sie Daten für Aufbewahrungszwecke klassifizieren können, um bestimmte Richtlinien und Vorschriften einzuhalten.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 F3/Business Premium, Office 365 E1/A1/F3 und eigenständige Exchange-Pläne bieten einem Benutzer die Rechte, von der manuellen Anwendung von Nicht-Datensatzaufbewahrungsetiketten auf Postfachdaten zu profitieren.

Microsoft 365 F3/F1/Business Premium, Office 365 E1/A1/F3 und eigenständige SharePoint-Pläne bieten einem Benutzer die Rechte, von der manuellen Anwendung von Nicht-Datensatzaufbewahrungsetiketten auf Dateien in SharePoint oder OneDrive zu profitieren. 

Microsoft 365 E5/A5/G5/E3/A3/Business Premium, Office 365 E5/A5/G5/E3/A3, Exchange Plan 2 und Exchange Online-Archivierung einem Benutzer die Rechte einräumen, von einer grundlegenden organisations- oder standortweiten Postfachaufbewahrungsrichtlinie zu profitieren und/oder eine nicht Datensatzaufbewahrungskennzeichnung manuell auf Postfachdaten anzuwenden.

Microsoft 365 E5/A5/G5/E3/A3, Office 365 E5/A5/G5/E3/A3 und SharePoint Plan 2 bieten einem Benutzer die Rechte, von einer grundlegenden SharePoint oder OneDrive Aufbewahrungsrichtlinie zu profitieren und/oder ein Nicht-Datensatzaufbewahrungsetikett manuell auf Dateien in SharePoint oder OneDrive anzuwenden.

Microsoft 365 E5/A5/G5/E3/A3 und Office 365 E5/A5/G5/E3/A3 bieten einem Nutzer die Rechte, von einer Teams-Aufbewahrungsrichtlinie zu profitieren.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 und Office 365 E5/A5 bieten einem Benutzer die Rechte, automatisch Aufbewahrungsetiketten oder -richtlinien anzuwenden, Standard-Aufbewahrungsetiketten oder -richtlinien anzuwenden, den Aufbewahrungszeitraum einer Aufbewahrungsbezeichnung basierend auf einem benutzerdefinierten Ereignis zu beginnen, eine manuelle Überprüfung am Ende der Aufbewahrungsfrist des Etiketts auszulösen, Daten von Drittanbietern über systemeigene Datenkonnektoren zu importieren, einen Datensatz zu deklarieren, beschriftete Inhalte zu entdecken und die Besiegelung saktivzumachen.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection und Governance bieten einem Benutzer die Rechte, automatisch Retentionsetiketten auf der Grundlage von trainierbaren Klassifikatoren anzuwenden.

Spezifische Rechte nach Lizenz finden Sie in der detaillierten Microsoft 365 Compliance-Lizenzierungsvergleich. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Informations-Governance-Funktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren der Informationssteuerung zum Anwenden von Autolabeling und Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Information Governance-Funktionen können auf lizenzierte Benutzer an bestimmten Standorten (Teamwebsites, Gruppenwebsites usw.) angewendet werden. Informationen zum Konfigurieren der Informationssteuerung zum Anwenden von Autolabeling und Richtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Information Governance in Microsoft 365](/microsoft-365/compliance/manage-information-governance).

## <a name="records-management"></a>Datensatzverwaltung

Records Management unterstützt Unternehmen bei der Erfüllung ihrer geschäftlichen und regulatorischen Aufzeichnungspflichten durch Das Entdecken, Klassifizieren, Etikettieren, Aufbewahren und vertretbare Löschungsfunktionen in ihren Microsoft 365 und Daten von Drittanbietern.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 Information Protection and Governance E5/A5/G5 und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von Records Management zu profitieren, einschließlich der Deklaration von Elementen als Datensätze oder behördliche Datensätze, der automatischen Anwendung von Aufbewahrungs- oder Datensatzetiketten und der Ausführung von Dispositionsüberprüfungsprozessen (ohne automatische Anwendung eines Aufbewahrungsetiketts auf der Grundlage von trainierbaren Klassifizierern).

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 Information Protection and Governance bieten einem Benutzer die Rechte, automatisch Aufbewahrungs- oder Datensatzetiketten auf der Grundlage von trainierbaren Klassifikatoren anzuwenden.

Spezifische Rechte nach Lizenz finden Sie in der detaillierten Microsoft 365 Compliance-Lizenzierungsvergleich. [(PDF)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.pdf)  |  [(Excel)](/office365/servicedescriptions/downloads/microsoft-365-compliance-licensing-comparison.xlsx)

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren davon, dass sie Inhalte als Datensatz deklarieren und ihren vollständigen Datensatzprozess von der Richtliniendefinition und -deklaration über eine vertretbare Entsorgung verwalten können.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Datensatzverwaltungsfunktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren der Datensatzverwaltung für lizenzierte Benutzer finden Sie unter [Informationen zur Datensatzverwaltung in Microsoft 365](/microsoft-365/compliance/records-management).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Records Management-Funktionen können auf lizenzierte Benutzer an bestimmten Standorten (Teamwebsites, Gruppenwebsites usw.) angewendet werden. Informationen zum Konfigurieren der Datensatzverwaltung für lizenzierte Benutzer finden Sie unter [Informationen zur Datensatzverwaltung in Microsoft 365](/microsoft-365/compliance/records-management).

## <a name="data-connectors"></a>Datenkonnektoren 

Microsoft stellt Datenconnectors von Drittanbietern bereit, die im Microsoft 365 Compliance Center konfiguriert werden können. Eine Liste der von Microsoft bereitgestellten Datenconnectors finden Sie in der Tabelle [Datenconnectors von Drittanbietern.](/microsoft-365/compliance/archiving-third-party-data#third-party-data-connectors) In dieser Tabelle werden auch die Konformitätslösungen zusammengefasst, die Sie nach dem Importieren und Archivieren von Daten in Microsoft 365 auf Daten von Drittanbietern anwenden können, und links zu den schrittweisen Anweisungen für jeden Connector.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Der Hauptvorteil der Verwendung von Datenkonnektoren zum Importieren und Archivieren von Daten von Drittanbietern in Microsoft 365 besteht darin, dass Sie verschiedene Microsoft 365 Compliance-Lösungen auf die Daten anwenden können, nachdem sie importiert wurden. Auf diese Weise wird sichergestellt, dass die Nicht-Microsoft-Daten Ihrer Organisation den Vorschriften und Standards entsprechen, die sich auf Ihre Organisation auswirken.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Die folgenden Lizenzen bieten einem Benutzer die Rechte, von Data Connectors zu profitieren:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5 Info Protection &amp; Governance
- Microsoft 365 E5/A5/G5-Konformität
- Microsoft 365 E5/A5/G5 Insider Risikomanagement
- Microsoft 365 E5/A5/G5 eDiscovery und Audit
- Office 365 E5/A5/G5

Für Datenconnectors im Microsoft 365 Security Compliance Center, die &amp; von einem Microsoft-Partner bereitgestellt werden, benötigt Ihre Organisation eine Geschäftsbeziehung mit dem Partner, bevor Sie diese Connectors bereitstellen können.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Connectors werden mit dem Security &amp; Compliance Center und dem ConnectorKatalog konfiguriert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Data Connectors-Dienste sind ein Wert auf Mandantenebene. Jeder Benutzer, der diesen Dienst in Anspruch nehmen soll, muss lizenziert sein.

## <a name="microsoft-graph-apis-for-teams-data-loss-prevention-dlp"></a>Microsoft Graph APIs für Teams Data Loss Prevention (DLP)

Anfang dieses Jahres haben wir [die öffentliche Vorschau der Microsoft Graph Change Notification API für Nachrichten in Teams angekündigt.](https://go.microsoft.com/fwlink/?linkid=2143888) Mit dieser API können Entwickler Apps erstellen, die nachrichtennah Microsoft Teams Nachrichten nahezu in Echtzeit abhören und DLP-Szenarioimplementierungen für Kunden und ISVs aktivieren können. Darüber hinaus ermöglicht die Microsoft Graph Patch-API das Anwenden von DLP-Aktionen auf Teams Nachrichten.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

[DLP-Funktionen (Data Loss Prevention)](/microsoft-365/compliance/dlp-microsoft-teams) werden häufig in Microsoft Teams eingesetzt, insbesondere da Unternehmen auf Remote-Arbeit umgestellt haben. Wenn Ihre Organisation über DLP verfügt, können Sie jetzt Richtlinien definieren, die verhindern, dass Personen vertrauliche Informationen in einem Microsoft Teams Kanal oder einer Chatsitzung freigeben.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Sie benötigen eine der folgenden Lizenzen, um Unterstützung für den DLP-Schutz in Teams Chat zu erhalten:

- Microsoft 365 E5/A5/G5
- Microsoft 365 E5/A5/G5-Konformität
- Microsoft 365 E5/A5/G5 Informationsschutz und Governance
- Office 365 E5/A5/G5 

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Der API-Zugriff wird auf Mandantenebene konfiguriert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft Graph API für Teams DLP ist ein Wert auf Mandantenebene. Jeder Benutzer, der diesen Dienst in Anspruch nehmen soll, muss lizenziert sein.

## <a name="ediscovery"></a>eDiscovery

eDiscovery bietet Untersuchungs- und eDiscovery-Lösungen für IT- und Rechtsabteilungen in Unternehmen, um Inhalte im Zusammenhang mit einer Untersuchung oder einem Rechtsstreit vor dem Export aus dem Microsoft 365-System zu identifizieren, zu sammeln, zu bewahren, zu reduzieren und zu überprüfen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Ein Benutzer profitiert von Advanced eDiscovery, wenn der Benutzer als Datenverwalter (eine Person, die die administrative Kontrolle über ein Dokument oder eine elektronische Datei hat) für einen Fall ausgewählt wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5/E3/A3/G3, Office 365 E5/A5/G5/E3/A3/G3, bieten einem Benutzer die Rechte, von Core eDiscovery zu profitieren.

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 eDiscovery und Audit sowie Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von Advanced eDiscovery zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig werden Advanced eDiscovery Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert, wenn Administratoren eDiscovery-Berechtigungen im Security &amp; Compliance Center zuweisen.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

eDiscovery-Administratoren können bestimmte Benutzer als Datenverwalter für einen Fall auswählen, indem sie das integrierte Verwaltungstool für Verwahrstellen in Advanced eDiscovery verwenden, wie unter [Hinzufügen von Verwahrern zu einem Advanced eDiscovery Fall](/microsoft-365/compliance/add-custodians-to-case)beschrieben.

## <a name="customer-key-for-microsoft-365"></a>Kundenschlüssel für Microsoft 365

Mit Customer Key steuern Sie die Verschlüsselungsschlüssel Ihrer Organisation und konfigurieren Microsoft 365, sie zum Verschlüsseln Ihrer ruhenden Daten in Microsoft-Rechenzentren zu verwenden. Mit anderen Worten, Customer Key ermöglicht es Ihnen, eine Verschlüsselungsebene hinzuzufügen, die Ihnen gehört, mit Ihren eigenen Schlüsseln. Zu den ruhenden Daten gehören Daten aus Exchange Online und Skype for Business, die in Postfächern und Dateien in SharePoint Online und OneDrive for Business gespeichert sind.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren vom Customer Key, indem sie ihre ruhenden Daten auf Anwendungsebene mithilfe von Verschlüsselungsschlüsseln verschlüsseln lassen, die von ihrer eigenen Organisation bereitgestellt, gesteuert und verwaltet werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, vom Kundenschlüssel zu profitieren. Um den vollen Nutzen aus dem Customer Key zu erhalten, müssen Sie auch über ein Abonnement für Azure Key Vault verfügen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Der Benutzerschlüssel für Microsoft 365 Verschlüsselungsschlüssel kann für alle Daten aktiviert werden, die in Exchange Online und Skype for Business Postfächern gespeichert sind, sowie für SharePoint Online-, OneDrive for Business- und Teams-Dateien. Weitere Informationen zum Kundenschlüssel, einschließlich der ersten Schritte, finden Sie unter [Serviceverschlüsselung mit Customer Key](/microsoft-365/compliance/customer-key-overview).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Für Exchange Online und Skype for Business können Postfächer mit dem Kundenschlüssel verschlüsselt werden. Sie müssen Azure einrichten, bevor Sie den Kundenschlüssel für Microsoft 365 verwenden können. Weitere Informationen zum Erstellen und Konfigurieren der erforderlichen Azure-Ressourcen und der Schritte zum Einrichten des Kundenschlüssels in Microsoft 365 finden Sie unter [Einrichten des Kundenschlüssels.](/microsoft-365/compliance/customer-key-set-up) Nachdem Sie die Azure-Einrichtung abgeschlossen haben, legen Sie fest, welche Richtlinie und daher welche Schlüssel Postfächern und Dateien in Ihrer Organisation zugewiesen werden sollen. Weitere Informationen zu Customer Key und Zudeninhalten zu Daten aus Exchange Online, Skype for Business, SharePoint Online, OneDrive for Business und Teams finden Sie unter [Serviceverschlüsselung mit Customer Key](/microsoft-365/compliance/customer-key-overview).

## <a name="office-365-customer-lockbox"></a>Office 365-Kunden-Lockbox

Customer Lockbox bietet eine zusätzliche Steuerungsebene, indem es Kunden die Möglichkeit bietet, explizite Zugriffsberechtigungen für Servicevorgänge zu erteilen. Durch den Nachweis, dass Verfahren für die explizite Datenzugriffsautorisierung vorhanden sind, kann Customer Lockbox Auch Organisationen helfen, bestimmte Compliance-Verpflichtungen wie HIPAA und FedRAMP zu erfüllen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Customer Lockbox stellt sicher, dass niemand bei Microsoft auf Kundeninhalte zugreifen kann, um einen Servicevorgang ohne die ausdrückliche Zustimmung des Kunden auszuführen. Customer Lockbox bringt den Kunden in den Genehmigungsworkflow für Anfragen, auf deren Inhalte zuzugreifen. Gelegentlich sind Microsoft-Ingenieure während des Supportprozesses beteiligt, um vom Kunden gemeldete Probleme zu beheben und zu beheben. In den meisten Fällen werden Probleme durch umfangreiche Telemetrie- und Debugtools behoben, die Microsoft für seine Dienste eingerichtet hat. Es kann jedoch Fälle geben, in denen ein Microsoft-Techniker auf Kundeninhalte zugreifen muss, um die Ursache zu ermitteln und das Problem zu beheben. Kunden-Lockbox setzt voraus, dass der Techniker den Zugriff vom Kunden als letzten Schritt im Genehmigungsworkflow anfordert. Dadurch haben Organisationen die Möglichkeit, diese Anforderungen zu genehmigen oder zu verweigern, wodurch sie direkt kontrollieren können, ob ein Microsoft-Techniker auf die Endbenutzerdaten der Organisationen zugreifen kann.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Insider Risk Management bieten einem Benutzer die Rechte, von Customer Lockbox zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren können Customer Lockbox im Microsoft 365 Admin Center aktivieren. Weitere Informationen finden Sie unter [Customer Lockbox in Office 365](/microsoft-365/compliance/customer-lockbox-requests). Wenn Customer Lockbox aktiviert ist, muss Microsoft die Genehmigung einer Organisation einholen, bevor sie auf einen ihrer Inhalte zugreift.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Derzeit kann der Customer Lockbox-Dienst nicht auf bestimmte Benutzer beschränkt werden. Sie müssen jedem Benutzer lizenzieren, von dem Sie profitieren möchten.

## <a name="privileged-access-management-in-office-365"></a>Privileged Access Management in Office 365

[Die Privileged Access Management (PAM)](/microsoft-365/compliance/privileged-access-management-configuration) bietet eine detaillierte Zugriffssteuerung für privilegierte Administratoraufgaben in Office 365. Nach dem Aktivieren von PAM, um erhöhte und privilegierte Aufgaben abzuschließen, müssen Benutzer Just-in-Time-Zugriff über einen Genehmigungsworkflow anfordern, der stark begrenzt und zeitgebunden ist.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Durch die Aktivierung von PAM können Organisationen mit Null-Standing-Berechtigungen arbeiten. Benutzer profitieren von der zusätzlichen Schutzebene gegen Schwachstellen, die sich aus dem ständigen administrativen Zugriff ergeben, der einen ungehinderten Zugriff auf ihre Daten bietet.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren? 

Office 365 E5/A5, Microsoft 365 E5/A5, Microsoft 365 E5/A5 Compliance und Microsoft 365 E5/A5 Information Protection and Governance bieten einem Benutzer die Rechte, von PAM zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind PAM-Funktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von PAM-Richtlinien finden Sie unter [Erste Schritte mit der privilegierten Zugriffsverwaltung](/microsoft-365/compliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Kunden können PAM benutzerspezifisch über Genehmiger Gruppen- und Zugriffsrichtlinien verwalten, die auf lizenzierte Benutzer angewendet werden können. Weitere Informationen finden Sie unter [Privilegierte Zugriffsverwaltung in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="double-key-encryption-for-microsoft-365"></a>Doppelschlüsselverschlüsselung für Microsoft 365 

Mit Double Key Encryption for Microsoft 365 können Sie Ihre hochsensiblen Daten schützen, um spezielle Anforderungen zu erfüllen und die volle Kontrolle über Ihren Verschlüsselungsschlüssel zu behalten. Double Key Encryption verwendet zwei Schlüssel, um Ihre Daten zu schützen, mit einem Schlüssel in Ihrem Steuerelement und dem zweiten Schlüssel, der sicher von Microsoft Azure gespeichert wird. Zum Anzeigen der Daten müssen Sie Zugriff auf beide Schlüssel haben. Da Microsoft nur auf einen Schlüssel zugreifen kann, sind Ihr Schlüssel und auch Ihre Daten für Microsoft nicht verfügbar, um sicherzustellen, dass Sie die volle Kontrolle über den Datenschutz und die Sicherheit Ihrer Daten haben.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von Double Key Encryption, indem sie ihre verschlüsselten Daten in die Cloud migrieren können, was den Zugriff von Drittanbietern verhindert, solange der Schlüssel die Kontrolle über die Benutzer hat. Benutzer können Double Key Encrypted-Inhalte schützen und diese verwenden, ähnlich wie bei anderen sensibel gekennzeichneten Inhalten.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Information Protection and Governance und Office 365 E5/A5/G5 bieten einem Benutzer die Rechte, von der Double Key Encryption zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Double Key Encryption unterstützt die Desktopversion von Microsoft Office für Windows.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Befolgen Sie die Anweisungen zur Bereitstellung von Doppelschlüsselverschlüsselung, um Daten innerhalb einer Office 365 und/oder Microsoft 365 Organisation für lizenzierte Benutzer zuzuweisen.

## <a name="office-365-data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Office 365 Datenverlustprävention für Exchange Online, SharePoint Online und OneDrive for Business

Mit Office 365 Data Loss Prevention (DLP) für Exchange Online, SharePoint Online und OneDrive for Business können Unternehmen vertrauliche Informationen in E-Mails und Dateien (einschließlich Dateien, die in Microsoft Teams Datei-Repositorys gespeichert sind) identifizieren, überwachen und automatisch schützen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von DLP für Exchange Online, SharePoint Online und OneDrive for Business, wenn ihre E-Mails und Dateien auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E3/A3/Business Premium, Office 365 E3/A3 und Office 365 Data Loss Prevention bieten einem Benutzer die Rechte, von Office 365 DLP für Exchange Online, SharePoint Online und OneDrive for Business zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Exchange Online E-Mails, SharePoint Websites und OneDrive Konten für diese DLP-Funktionen für alle Benutzer innerhalb des Mandanten *aktivierte Speicherorte (Workloads).* Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie [unter Übersicht über die Verhinderung von Datenverlust](/microsoft-365/compliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Standorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security Compliance Center unter Speicherorte zur Verhinderung von &amp; **Datenverlust**  >  anpassen.

## <a name="communication-data-loss-prevention-for-teams"></a>Kommunikationsdatenverlustprävention für Teams

Mit Communication DLP for Teams können Organisationen Chats blockieren und Nachrichten kanalisieren, die vertrauliche Informationen enthalten, z. B. Finanzinformationen, personenbezogene Informationen, gesundheitsbezogene Informationen oder andere vertrauliche Informationen.

### <a name="which-users-benefit-from-the-service"></a>Welche Nutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Information Protection and Governance können von Der Kommunikation DLP für Teams profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Absender profitieren davon, dass vertrauliche Informationen in ihren ausgehenden Chat- und Kanalnachrichten auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Teams Chat- und Kanalnachrichten ein *aktivierter Speicherort (Workload)* für diese DLP-Funktionen für alle Benutzer innerhalb des Mandanten. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie [unter Übersicht über die Verhinderung von Datenverlust](/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Standorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security Compliance Center unter Speicherorte zur Verhinderung von &amp; **Datenverlust**  >  anpassen.

## <a name="information-barriers"></a>Informationsbarrieren

Informationsbarrieren sind Richtlinien, die ein Administrator konfiguriert, um zu verhindern, dass Einzelpersonen oder Gruppen miteinander kommunizieren können. Dies ist z. B. nützlich, wenn eine Abteilung Informationen verarbeitet, die nicht für andere Abteilungen freigegeben werden sollten, oder wenn eine Gruppe daran gehindert werden muss, mit externen Kontakten zu kommunizieren. Richtlinien für Informationsbarrieren verhindern auch Such- und Ermittlungsmaßnahmen. Das bedeutet, dass Sie diesen Benutzer nicht in der Personenauswahl finden, wenn Sie versuchen, mit jemandem zu kommunizieren, mit dem Sie nicht kommunizieren sollten.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von den erweiterten Compliance-Funktionen von Informationsbarrieren, wenn sie nicht mit anderen kommunizieren können. Richtlinien für Informationsbarrieren können definiert werden, um zu verhindern, dass bestimmte Benutzermitbenutzer mit jedem Benutzer kommunizieren, oder bestimmte Segmente nur mit bestimmten anderen Segmenten kommunizieren. Weitere Informationen zum Definieren von Informationsbarriererichtlinien finden Sie unter [Definieren von Informationsbarriererichtlinien](/microsoft-365/compliance/information-barriers-policies). Für Szenarien, in denen zwei Gruppen nicht miteinander kommunizieren können, benötigen Benutzer in beiden Gruppen eine Lizenz, um von dem Dienst zu profitieren (siehe beispiel unten).<br><br>

| Szenario | Wer eine Lizenz benötigt? |
|:------|:------|
| Zwei Gruppen (Gruppe &nbsp; 1 und Gruppe &nbsp; 2) können nicht miteinander kommunizieren (d. h., Benutzer der Gruppe 1 dürfen nicht mit Benutzern der Gruppe 2 kommunizieren, und Benutzer der Gruppe 2 dürfen nicht mit Benutzern der &nbsp; Gruppe 1 &nbsp; &nbsp; &nbsp; kommunizieren. | Benutzer in Gruppe &nbsp; 1 und Gruppe &nbsp; 2 |

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance, Microsoft 365 E5/A5/G5 Insider Risk Management und Office 365 E5/A5/G5, bieten einem Benutzer die Rechte, von Informationsbarrieren zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Richtlinien für Informationsbarrieren mithilfe von PowerShell-Cmdlets im Security &amp; Compliance Center. Administratoren müssen die Rolle Microsoft 365 Enterprise Global Administrator, Office 365 Global Administrator oder Compliance Administrator zugewiesen werden, um eine Richtlinie für Informationsbarrieren zu erstellen. Standardmäßig gelten diese Richtlinien für alle Benutzer im Mandanten. Weitere Informationen zu Informationsbarrieren finden Sie [unter Informationsbarrieren in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Standorte (Workloads), eingeschlossene Benutzer und ausgeschlossene Benutzer im Security &amp; Compliance Center anpassen. Wenn z. B. alle Benutzer für Office 365 E3 lizenziert sind und keine für Office 365 Advanced Compliance/E5 lizenziert ist, müssen sie keine Richtlinien für Informationsbarrieren für die Organisation erstellen. Weitere Informationen finden Sie unter [Informationsbarrieren in Microsoft Teams](/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

Office 365-Nachrichtenverschlüsselung (Office Message Encryption, OME) ist ein Dienst, der auf Azure Rights Management (Azure RMS) aufbaut und mit dem Sie verschlüsselte E-Mails an Personen innerhalb oder außerhalb Ihrer Organisation senden können, unabhängig von der E-Mail-Zieladresse (Gmail, Yahoo! Mail, Outlook.com usw.).

Zum Anzeigen verschlüsselter Nachrichten können Empfänger eine einmalige Kennung abrufen, sich mit einem Microsoft-Konto anmelden oder sich mit einem Geschäfts-, Schul- oder Unikonto, das Office 365 zugeordnet ist, anmelden. Empfänger können auch verschlüsselte Antworten senden. Sie benötigen kein Abonnement, um verschlüsselte Nachrichten anzuzeigen oder verschlüsselte Antworten zu senden.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Nachrichtenabsender profitieren von der zusätzlichen Kontrolle über vertrauliche E-Mails, die von Office 365-Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E3/A3/G3, Office 365 E3/A3/G3 und Azure Information Protection Plan 1 bieten einem Benutzer die Rechte, von Office 365-Nachrichtenverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Office 365-Nachrichtenverschlüsselung Richtlinien im Exchange Admin Center unter **Mailflussregeln**  >  . Standardmäßig gelten diese Regeln für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Office 365-Nachrichtenverschlüsselung-Funktionen finden Sie unter [Einrichten neuer Nachrichtenverschlüsselungsfunktionen](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenflussregeln für Office 365-Nachrichtenverschlüsselung nur auf lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenflussregeln finden Sie unter Definieren von [Nachrichtenflussregeln zum Verschlüsseln von E-Mail-Nachrichten](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="office-365-advanced-message-encryption"></a>Erweiterte Office 365-Nachrichtenverschlüsselung

Office 365 Advanced Message Encryption kunden bei der Erfüllung von Compliance-Verpflichtungen unterstützt, die flexiblere Kontrollen externer Empfänger und ihren Zugriff auf verschlüsselte E-Mails erfordern. Mit der erweiterten Nachrichtenverschlüsselung können Administratoren vertrauliche E-Mails steuern, die außerhalb der Organisation geteilt werden, indem sie automatische Richtlinien verwenden, die vertrauliche Informationstypen erkennen können (z. B. persönliche Identifizierungsinformationen oder Finanz- oder Integritäts-IDs), oder sie können Schlüsselwörter verwenden, um den Schutz zu verbessern, indem sie benutzerdefinierte E-Mail-Vorlagen anwenden und den Zugriff auf verschlüsselte E-Mails über ein sicheres Webportal auszeichnen. Darüber hinaus können Administratoren verschlüsselte E-Mails, auf die extern über ein sicheres Webportal zugegriffen wird, weiter steuern, indem sie den Zugriff jederzeit widerrufen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Nachrichtenabsender profitieren von der zusätzlichen Kontrolle über vertrauliche E-Mails, die von Der erweiterten Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Information Protection and Governance bieten einem Benutzer die Rechte, von der erweiterten Nachrichtenverschlüsselung zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Erweiterte Nachrichtenverschlüsselungsrichtlinien im Exchange Admin Center unter **E-Mail-Flussregeln**  >  . Standardmäßig gelten diese Regeln für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Nachrichtenverschlüsselungsfunktionen finden Sie unter [Einrichten neuer Office 365-Nachrichtenverschlüsselung Funktionen](/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenflussregeln für die erweiterte Nachrichtenverschlüsselung nur auf lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenflussregeln finden Sie unter Definieren von [Nachrichtenflussregeln zum Verschlüsseln von E-Mail-Nachrichten in Office 365](/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="communication-compliance"></a>Kommunikationscompliance

Die Kommunikationskonformität in Microsoft 365 trägt zur Minimierung von Kommunikationsrisiken bei, indem Sie Ihnen helfen, unangemessene Nachrichten in Ihrer Organisation zu erkennen, zu erfassen und Zuhebungsmaßnahmen durchzuführen. Sie können bestimmte Richtlinien definieren, die interne und externe E-Mails, Microsoft Teams oder Drittanbieterkommunikationen in Ihrer Organisation erfassen. Bearbeiter können geeignete Behebungsmaßnahmen ergreifen, um sicherzustellen, dass sie den Nachrichtenstandards Ihrer Organisation entsprechen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Compliance-Spezialisten profitieren von dem Service, da die Kommunikation der Organisation durch Richtlinien zur Einhaltung der Kommunikation überwacht wird.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Insider Risk Management bieten einem Benutzer die Rechte, von der Kommunikationskonformität zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren und Compliance-Spezialisten erstellen Richtlinien für die Kommunikationscompliance im Microsoft 365 Compliance Center. Diese Richtlinien definieren, welche Kommunikationen und Benutzer in der Organisation überprüft werden können, definieren benutzerdefinierte Bedingungen, die die Kommunikation erfüllen muss, und geben an, wer Überprüfungen durchführen soll.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren wählen bestimmte Benutzer oder Gruppen aus, die in eine Richtlinie für die Kommunikationskonformität aufgenommen werden sollen. Bei der Auswahl einer Gruppe können sie auch bestimmte Benutzer in der Gruppe auswählen, die von der Richtlinie für die Kommunikationskonformität ausgeschlossen werden sollen. Weitere Informationen zu Richtlinien für die Kommunikationskonformität finden Sie unter [Erste Schritte mit der Kommunikationskonformität in Microsoft 365](/microsoft-365/compliance/communication-compliance-configure).

## <a name="insider-risk-management"></a>Insider-Risikomanagement

Das Insider-Risikomanagement ist eine Lösung in Microsoft 365, die dazu beiträgt, interne Risiken zu minimieren, indem Sie riskante Aktivitäten in Ihrem Unternehmen erkennen, untersuchen und Maßnahmen ergreifen können.

Benutzerdefinierte Richtlinien ermöglichen es Ihnen, böswillige und unbeabsichtigt riskante Aktivitäten in Ihrer Organisation zu erkennen und Maßnahmen zu ergreifen, einschließlich eskalierender Fälle an Microsoft Advanced eDiscovery, falls erforderlich. Risikoanalytiker in Ihrer Organisation können schnell geeignete Maßnahmen ergreifen, um sicherzustellen, dass die Benutzer den Compliance-Standards Ihrer Organisation entsprechen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Die Nutzer profitieren davon, dass ihre Aktivitäten auf Risiken überwacht werden.

### <a name="which-licenses-provide-the-rights-for-a-user-to-benefit-from-the-service"></a>Welche Lizenzen bieten einem Benutzer die Rechte, von dem Dienst zu profitieren?

Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 Insider Risk Management bieten einem Benutzer die Rechte, vom Insider Risk Management zu profitieren.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Insider-Risikomanagement-Richtlinien müssen im Microsoft 365 Compliance Center erstellt und Benutzern zugewiesen werden.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Wenn Sie eine Richtlinie im Microsoft 365-Compliance-Center erstellen, wählen Sie auf der Seite **Benutzer und Gruppen auswählen** die Option Benutzer oder Gruppen **auswählen** aus, um nur lizenzierte Benutzer auszuwählen, oder wenn alle Benutzer lizenziert sind, können Sie das Kontrollkästchen Alle Benutzer **und E-Mail-aktivierten Gruppen** aktivieren. Weitere Informationen finden Sie unter [Erste Schritte mit Insider-Risikomanagement](/microsoft-365/compliance/insider-risk-management-configure).

## <a name="conditional-access-policies"></a>Richtlinien für bedingten Zugriff

Bedingter Zugriff ist das Tool, das von Azure Active Directory verwendet wird, um Signale zusammenzubringen, Entscheidungen zu treffen und Organisationsrichtlinien durchzusetzen. Bedingter Zugriff ist das Herzstück der identitätsgesteuerten Steuerung. Bedingte Zugriffsrichtlinien sind in ihrer einfachsten Weise if-then-Anweisungen. Wenn ein Benutzer auf eine Ressource zugreifen möchte, muss er eine Aktion abschließen. Beispiel: Ein Lohnmanager möchte auf die Lohnabrechnungsanwendung zugreifen und muss für den Zugriff auf die Lohnabrechnungsanwendung eine mehrstufige Authentifizierung durchführen.

### <a name="which-users-benefit-from-the-service"></a>Welche Nutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Enterprise Mobility + Security E3/A3, Microsoft 365 F3/E3/A3/Business Premium und Azure Active Directory Premium Plan 1 können von Richtlinien für bedingten Zugriff profitieren. Lizenzierte Benutzer Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft E5/G5 Security und Azure Active Directory Premium Plan 2 können von Identitätsschutz (risikobasierte Conditional Access-Richtlinien) profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Sicherheits-Analysten und Sicherheitsexperten profitieren davon, dass sie in der Lage sind, Organisationsrichtlinien für Benutzer durchzusetzen, und sie verpflichten, bestimmte Kriterien zu erfüllen, bevor sie Zugriff auf Unternehmensinhalte gewähren. Endbenutzer profitieren davon, dass sie jederzeit und überall auf ihre Arbeit zugreifen können und gleichzeitig die Ressourcen der Organisation schützen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Conditional Access-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Speziell für den Identitätsschutz und den bedingten Zugriff muss ein Benutzer in eine Gruppe aufgenommen oder einer Richtlinie für bedingten Zugriff hinzugefügt werden. Die Benutzer- und Gruppenbedingung ist in einer Richtlinie für bedingten Zugriff obligatorisch. In Ihrer Richtlinie können Sie entweder **Alle Benutzer** oder bestimmte Benutzer und Gruppen auswählen. Sie sollten nur entsprechend lizenzierte Benutzer und Gruppen auswählen. Weitere Informationen finden Sie unter [Bedingter Zugriff: Bedingungen](/azure/active-directory/conditional-access/conditions).

## <a name="advanced-audit"></a>Erweiterte Überwachung

Advanced Audit in Microsoft 365 bietet ein Jährige Aufbewahrung von Überwachungsprotokollen für Benutzer- und Administratoraktivitäten und bietet die Möglichkeit, benutzerdefinierte Überwachungsprotokollaufbewahrungsrichtlinien zu erstellen, um die Aufbewahrung von Überwachungsprotokollen für andere Microsoft 365 Dienste zu verwalten. Es bietet auch Zugriff auf wichtige Ereignisse für Untersuchungen und Zugriff auf die Office 365 Management Activity API. Weitere Informationen finden Sie unter [Erweiterte sgemäße Prüfung in Microsoft 365](/microsoft-365/compliance/advanced-audit).

Sie können auch eine Aufbewahrungsdauer von 10 Jahren mit einer Add-On-SKU aktivieren. Die Add-on-SKU wird ab Anfang 2021 erforderlich sein.

### <a name="which-users-benefit-from-the-service"></a>Welche Nutzer profitieren von dem Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5 Compliance und Microsoft 365 E5/A5/G5 eDiscovery und Audit können von Advanced Audit profitieren.

Lizenzierte Benutzer mit Advanced Audit und dem 10-Jahres-Audit Log Retention Add-on können von der 10-jährigen Audit Log Retention profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer von dem Dienst?

Benutzer profitieren von Der erweiterten Überwachung, da Überwachungsdatensätze im Zusammenhang mit Benutzeraktivitäten in Microsoft 365 Diensten bis zu einem Jahr aufbewahrt werden können. Darüber hinaus werden hochwertige Überwachungsereignisse protokolliert, z. B. wenn auf Elemente im Postfach eines Benutzers zugegriffen oder gelesen wird. Weitere Informationen finden Sie unter [Erweiterte sgemäße Prüfung in Microsoft 365](/microsoft-365/compliance/advanced-audit).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig ist Die erweiterte Überwachung auf Mandantenebene für alle Organisationen aktiviert, die über ein Office 365 oder Microsoft 365 E5/A5/G5-Abonnement verfügen, und stellt automatisch die einjährige Aufbewahrung von Überwachungsprotokollen für Aktivitäten (die von Benutzern mit der entsprechenden Lizenz ausgeführt werden) in Azure Active Directory, Exchange und SharePoint bereitstellt. Darüber hinaus können Organisationen Überwachungsprotokollaufbewahrungsrichtlinien verwenden, um den Aufbewahrungszeitraum für Überwachungsdatensätze zu verwalten, die durch Aktivitäten in anderen Microsoft 365 Diensten generiert werden. Die 10-Jahres-Funktionalität für die Aufbewahrung von Überwachungsprotokollen wird ebenfalls mithilfe derselben Aufbewahrungsrichtlinien aktiviert. Weitere Informationen finden Sie unter [Verwalten der Aufbewahrungsrichtlinien für Überwachungsprotokolle](/microsoft-365/compliance/audit-log-retention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Ein jahrliche Aufbewahrung der Auditprotokolle und die Überwachung wichtiger Ereignisse gelten nur für Benutzer mit der entsprechenden Lizenz. Darüber hinaus können Administratoren Überwachungsprotokollaufbewahrungsrichtlinien verwenden, um kürzere Aufbewahrungsdauern für die Überwachungsprotokolle bestimmter Benutzer anzugeben.

Die 10-Jahres-Aufbewahrung der Überwachungsprotokolle gilt nur für Benutzer mit der entsprechenden Add-On-Lizenz. Die Add-on-SKU wird ab Anfang 2021 benötigt.