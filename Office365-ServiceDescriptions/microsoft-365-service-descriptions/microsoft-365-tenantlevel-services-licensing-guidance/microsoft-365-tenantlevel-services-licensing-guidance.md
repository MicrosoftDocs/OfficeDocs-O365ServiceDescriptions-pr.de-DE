---
title: Microsoft 365-Dienste für die Lizenzierung auf Mandantenebene
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-online-service-description
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
description: Dieser Artikel enthält eine Anleitung für die Lizenzierung von Microsoft 365-Diensten auf Mandantenebene, um mögliche Dienstunterbrechungen aufgrund von nicht lizenziertem Zugriff zu vermeiden.
ms.openlocfilehash: b0ff01a92ed1d3c3a5284fd3eba45241a65c0a6a
ms.sourcegitcommit: f69656f34dcb4f4e9a5857d8c4236084c94a05b1
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/31/2019
ms.locfileid: "37890493"
---
# <a name="microsoft-365-tenant-level-services-licensing-guidance"></a>Microsoft 365-Dienste für die Lizenzierung auf Mandantenebene

Für die Zwecke dieses Artikels handelt es sich bei einem Dienst auf Mandantenebene um einen&mdash;Onlinedienst, der beim Kauf für einen beliebigen Benutzer im Mandanten (eigenständig oder als Teil von&mdash;Office 365-oder Microsoft 365-Plänen) für alle Benutzer im Mandanten vollständig aktiviert wird. Auch wenn einige nicht lizenzierte Benutzer technisch möglicherweise auf den Dienst zugreifen können, ist eine Lizenz für jeden Benutzer erforderlich, den Sie vom Dienst nutzen möchten.

> [!NOTE]
> Einige Mandanten Dienste können derzeit keine Vorteile für bestimmte Benutzer einschränken. Es sollten Anstrengungen unternommen werden, um die Dienst Vorteile für lizenzierte Benutzer zu begrenzen. Auf diese Weise können potenzielle Dienstunterbrechungen in Ihrer Organisation vermieden werden, sobald die Zielfunktionen verfügbar sind.

## <a name="azure-active-directory-identity-protection"></a>Azure Active Directory Identity Protection

Azure Active Directory Identity Protection (AADIP) ist ein Feature des Azure Active Directory Premium P2-Plans, mit dem Sie potenzielle Sicherheitsanfälligkeiten erkennen können, die sich auf die Identitäten Ihrer Organisation auswirken, und konfigurieren Sie automatisierte Antworten auf erkannte verdächtige Aktionen im Zusammenhang mit den Identitäten Ihrer Organisation und untersuchen von verdächtigen Vorfällen und ergreifen geeigneter Maßnahmen zur Lösung dieser Probleme.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Sicherheit und Azure Active Directory Premium-Plan 2 können von AADIP profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Analysten und Sicherheitsexperten von seepolizisten profitieren von konsolidierten Ansichten von gekennzeichneten Benutzern und Risikoereignissen basierend auf maschinellen Lernalgorithmen. Endbenutzer profitieren von dem automatischen Schutz, der durch risikobasierter bedingter Zugriff bereitgestellt wird, und der verbesserten Sicherheit durch das Handeln auf Schwachstellen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind AADIP-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von AADIP finden Sie unter [Aktivieren von Azure Active Directory Identity Protection](https://docs.microsoft.com/azure/active-directory/identity-protection/enable).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können den Bereich AADIP, indem Sie Risikorichtlinien zuweisen, mit denen die Ebene für Kennwortzurücksetzungen definiert und der Zugriff nur für lizenzierte Benutzer zugelassen wird. Anweisungen zum Umfang von AADIP-Bereitstellungen finden Sie unter [configure the Sign-in Risk Policy](https://docs.microsoft.com/azure/active-directory/identity-protection/howto-sign-in-risk-policy).

## <a name="azure-advanced-threat-protection"></a>Azure Advanced Threat Protection

Azure Advanced Threat Protection (ATP) ist ein clouddienst, der Enterprise-Hybrid Umgebungen vor unterschiedlichen Arten von erweiterten, zielgerichteten Cyber-Angriffen und Insiderbedrohungen schützen kann.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Sicherheit und Azure Advanced Threat Protection für Benutzer können von Azure ATP profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

SecOp-Analysten und Sicherheitsexperten profitieren von der Fähigkeit von Azure ATP, erweiterte Bedrohungen, kompromittierte Identitäten und böswillige Insider Aktionen zu erkennen und zu untersuchen. Endbenutzer profitieren davon, dass Ihre Daten von Azure ATP überwacht werden.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig werden Azure ATP-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von Azure ATP finden Sie unter [Erstellen Ihrer Azure ATP-Instanz](https://docs.microsoft.com/azure-advanced-threat-protection/install-atp-step1).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft stellt Funktionen für die Erkennung von Bedrohungen für lizenzierte Benutzer bereit.

## <a name="azure-information-protection"></a>Azure Information Protection

Azure Information Protection (AIP) unterstützt Organisationen beim entdecken, klassifizieren, beschriften und Schützen vertraulicher Dokumente und e-Mails. Administratoren können Regeln und Bedingungen definieren, um Beschriftungen automatisch anzuwenden, Benutzer können Bezeichnungen manuell anwenden, oder eine Kombination der beiden kann verwendet&mdash;werden, wenn Benutzern Empfehlungen zum Anwenden von Bezeichnungen gegeben werden.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Microsoft 365 F1, Microsoft 365 Business, Microsoft 365 E3/A3/G3 und AIP-Plan 1 können von AIP-Plan 1 profitieren. Lizenzierte Benutzer von Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität und AIP-Plan 2 können von AIP Plan 2 profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Das AIP-Scanner-Feature klassifiziert, beschriftet und schützt Dateien, die sich in lokalen Datei Repositories befinden, automatisch.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

In der Standardeinstellung werden AIP-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von AIP-Richtlinien für lizenzierte Benutzer finden Sie unter [Aktivieren von Azure Rights Management](https://docs.microsoft.com/azure/information-protection/activate-service).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

AIP-Funktions Richtlinien (mit Ausnahme des Scanner-Features) können auf bestimmte Gruppen oder Benutzer beschränkt werden. Registrierungen können bearbeitet werden, um zu verhindern, dass nicht lizenzierte Benutzer AIP-Klassifikationen oder Kenn zeichnungfunktionen durchführen. Anweisungen zum Umfang von AIP-Bereitstellungen finden Sie unter [Konfigurieren der Azure Information Protection-Richtlinie](https://docs.microsoft.com/azure/information-protection/configure-policy).

Für das AIP-Scanner-Feature verpflichtet sich Microsoft nicht, Benutzern, die nicht lizenziert sind, die Datei Klassifizierung, Beschriftung oder Schutzfunktionen bereitzustellen. Im Laufe der Zeit werden dem AIP Lizenzprüfungen oder zielgerichtete Tools hinzugefügt, um sicherzustellen, dass das Scanner-Feature lizenzierten Benutzern zugeordnet werden kann.

## <a name="office-365-advanced-threat-protection"></a>Office 365 Advanced Threat Protection

Advanced Threat Protection (ATP) schützt Organisationen vor ausgeklügelten Angriffen wie Phishing und Zero-Day-Schadsoftware. Es bietet auch umsetzbare Einblicke durch Korrelieren von Signalen aus einer breiten Palette von Daten zur Unterstützung bei der Identifizierung, Priorisierung und Bereitstellung von Empfehlungen zur Lösung potenzieller Bedrohungen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Sicherheit, Microsoft 365 Business und Office 365 ATP-Pläne 1 und 2 können von ATP profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

ATP schützt Benutzer vor ausgeklügelten Angriffen wie Phishing und Zero-Day-Schadsoftware. Eine vollständige Liste der in Plan 1 und Plan 2 bereitgestellten Dienste finden Sie unter [Office 365 Advanced Threat Protection](https://products.office.com/exchange/advance-threat-protection).

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig werden ATP-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von ATP-Richtlinien für lizenzierte Benutzer finden Sie unter [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Für den Bereich ATP befolgten die Bereitstellungsrichtlinien für sichere Links und sichere Anlagen:

  - Informationen zum Konfigurieren von sicheren Links für lizenzierte Benutzer finden Sie unter [Einrichten Office 365 ATP-Richtlinien für sichere Links](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-links-policies).

  - Informationen zum Konfigurieren von sicheren Anlagen für lizenzierte Benutzer finden Sie unter [Einrichten Office 365 ATP-Richtlinien für sichere Anlagen](https://docs.microsoft.com/office365/securitycompliance/set-up-atp-safe-attachments-policies).

## <a name="office-365-cloud-app-security"></a>Office 365 Cloud App Security

Office 365 Cloud-App-Sicherheit (Ocas) ist eine Teilmenge der Microsoft Cloud-App-Sicherheit, wobei Features auf Office 365 und ohne zusätzliche Sicherheit für Cloud-apps von Drittanbietern und IaaS-Dienste eingeschränkt sind.

Ocas gibt Organisationen Einblick in Ihre Produktivitäts Cloud-apps und-Dienste, stellt ausgefeilte Analysen zum Identifizieren und bekämpfen von Cyber-Bedrohungen bereit und&mdash;lässt Sie steuern, wie Daten über Office 365 transportiert werden.

Informationen zum Vergleichen von Features finden Sie unter [Differences of Microsoft Cloud App Security and Office 365 Cloud App Security](https://docs.microsoft.com/cloud-app-security/editions-cloud-app-security-o365).

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5 können von Ocas profitieren.

Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing-Datenblatt](https://www.aka.ms/mcaslicensing).

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Ocas erkennt Shadow IT, bietet Schutz vor Bedrohungen in Office 365 und kann steuern, welche apps über die Berechtigung zum Zugriff auf Office 365 Daten verfügen.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Ocas-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren des Diensts finden Sie unter [Basic Setup for Cloud App Security](https://docs.microsoft.com/cloud-app-security/general-setup).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Ocas-Bereitstellungen durchsetzen, um zu erzwingen, wie auf bestimmte apps zugegriffen wird, und um Benutzergruppen zu begrenzen, die von Office 365 Cloud-App-Sicherheit überwacht werden. Weitere Informationen finden Sie unter [bereichsbezogene Bereitstellung](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="microsoft-cloud-app-security"></a>Microsoft Cloud App Security

Microsoft Cloud App Security (MCAS) ist eine CASB-Lösung (Cloud Access Security Broker), die Unternehmen Einblick in Ihre Cloud-apps und-Dienste gibt, hoch entwickelte Analysen zum Identifizieren und bekämpfen von Cyber-Bedrohungen bietet und Ihnen die Kontrolle darüber ermöglicht, wie Daten reist&mdash;über eine Cloud-app.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von MCAS, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Security können von MCAS profitieren.

Lizenzierte Benutzer von Azure AD P1 können von den Ermittlungsfunktionen in MCAS profitieren.

Um von den [bedingten Zugriffsfunktionen für App-Steuerelemente](https://docs.microsoft.com/cloud-app-security/proxy-intro-aad) in MCAS profitieren zu können, müssen die Benutzer auch für Azure Active Directory P1 lizenziert werden, die in Enterprise Mobility + Security E3/A3/G3, Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E3/ A3/G3, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5-Sicherheit.

Um von der [automatischen Kennzeichnung](https://docs.microsoft.com/cloud-app-security/data-protection-policies)profitieren zu können, müssen die Benutzer für Azure Information Protection P2 lizenziert sein, die in Enterprise Mobility + Security E5/A5/G5, Microsoft 365 E5/A5/G5 und Microsoft 365 E5/A5/G5 Compliance enthalten ist.

Weitere Informationen finden Sie im [Microsoft Cloud App Security Licensing-Datenblatt](https://www.aka.ms/mcaslicensing).

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

MCAS erkennt und beurteilt Shadow IT, bietet Schutz vor Bedrohungen für First-und Third-Party-Cloud-apps und schützt Informationen über Cloud-apps von erst-und Drittanbietern.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind MCAS-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert.

Informationen zum Konfigurieren von Microsoft Cloud App-Sicherheitsrichtlinien für lizenzierte Benutzer finden Sie unter [Microsoft Cloud App Security Overview](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können MCAS-Bereitstellungen für lizenzierte Benutzer mithilfe der im Dienst verfügbaren Bereitstellungsfunktionen für Bereiche bereitstellen. Weitere Informationen finden Sie unter [bereichsbezogene Bereitstellung](https://docs.microsoft.com/cloud-app-security/scoped-deployment).

## <a name="office-365-advanced-data-governance"></a>Office 365 Advanced Data Governance

Die erweiterte Datensteuerung (Advanced Data Governance, ADG) unterstützt Organisationen bei der Erfüllung der Anforderungen an die Informationssteuerung mit Richtlinien zur Aufbewahrung und Löschung. Mit ADG können Organisationen Inhalte basierend auf dem Typ vertraulicher Informationen automatisch bezeichnen und Richtlinien auf diese Inhalte anwenden.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität und Office 365 erweiterte Kompatibilität können von ADG profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Mit ADG können Benutzer Bezeichnungen auf bestimmte Daten anwenden, um bestimmte Richtlinien beizubehalten, Inhalte automatisch als Datensatz zu bezeichnen und den vollständigen Daten Satz Prozess von der Deklaration bis zur Entsorgung zu verwalten.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind ADG-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von ADG für die Anwendung der automatischen Kennzeichnung und von Richtlinien für lizenzierte Benutzer finden Sie unter [Overview of Retention Labels](https://docs.microsoft.com/office365/securitycompliance/labels).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

ADG-Aufbewahrungsrichtlinien können über die automatische Klassifizierung auf lizenzierte Benutzer an bestimmten Orten (Teamwebsites, Gruppen Websites usw.) angewendet werden. Anweisungen zum Anwenden von ADG-Aufbewahrungsrichtlinien finden Sie unter [Anwenden einer Aufbewahrungsrichtlinie auf eine gesamte Organisation oder bestimmte Standorte](https://docs.microsoft.com/office365/securitycompliance/retention-policies#applying-a-retention-policy-to-an-entire-organization-or-specific-locations).

## <a name="office-365-advanced-ediscovery"></a>Office 365 Advanced eDiscovery

Office 365 Advanced eDiscovery stellt Ermittlungs-und eDiscovery-Lösungen für IT-Abteilungen und Rechtsabteilungen in Unternehmen bereit, um Inhalte im Zusammenhang mit einer Untersuchung oder eines Rechtsstreits vor dem Export aus dem zu ermitteln, zu sammeln, aufzubewahren, zu reduzieren Office 365 System.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität und Office 365 erweiterte Compliance können von Advanced eDiscovery profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Ein Benutzer profitiert von Advanced eDiscovery, wenn der Benutzer als Datenverwalter (eine Person mit administrativer Kontrolle über ein Dokument oder eine elektronische Datei) für einen Fall ausgewählt ist.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig werden erweiterte eDiscovery-Funktionen auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert, wenn Administratoren eDiscovery-Berechtigungen im Security #a0 Compliance Center zuweisen.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

eDiscovery-Administratoren können bestimmte Benutzer als Datenverwalter für einen Fall auswählen, indem Sie das integrierte Depot Verwaltungstool in Advanced eDiscovery verwenden, wie unter [Add depotbanks to a Advanced eDiscovery Case](https://docs.microsoft.com/office365/securitycompliance/compliance20/add-custodians-to-case)beschrieben.

## <a name="office-365-customer-key"></a>Office 365-Kundenschlüssel

Mit dem Kundenschlüssel steuern Sie die Verschlüsselungsschlüssel Ihrer Organisation und konfigurieren Office 365, damit Sie Ihre Daten im Ruhezustand in den Microsoft-Rechenzentren verschlüsseln können. Mit anderen Worten: mit dem Kundenschlüssel können Sie eine Verschlüsselungsebene hinzufügen, die Ihnen gehört, wobei Sie eigene Schlüssel verwenden. Zu den Daten im Ruhezustand gehören Daten aus Exchange Online und Skype for Business, die in Postfächern und Dateien in SharePoint Online und OneDrive für Unternehmen gespeichert werden.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Compliance und Office 365 Advanced Compliance können von Kunden Schlüsseln profitieren. Um den vollen Nutzen aus dem Kundenschlüssel zu ziehen, müssen Sie auch über ein Abonnement für Azure Key Vault verfügen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren vom Kundenschlüssel, indem Sie Ihre Daten auf der Anwendungsebene mithilfe von Verschlüsselungsschlüsseln, die von ihrer eigenen Organisation bereitgestellt, gesteuert und verwaltet werden, in Ruhe verschlüsseln.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Office 365 Verschlüsselungsschlüssel für Kundenschlüssel können für alle Daten aktiviert werden, die in Exchange Online-und Skype for Business-Postfächern gespeichert sind, sowie SharePoint Online und OneDrive für Unternehmen Dateien. Informationen zum Konfigurieren Office 365 Kunden Schlüssels zum Verschlüsseln von Daten im Ruhezustand finden Sie unter [Steuern der Daten in Office 365 mithilfe des Kunden Schlüssels](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Wenn Sie Daten in einem Office 365-und/oder Microsoft 365-Mandanten für lizenzierte Benutzer mit Verschlüsselungsschlüsseln versehen möchten, befolgen Sie die Bereitstellungsanweisungen für die Schlüssel zur Verschlüsselung der Kunden:

  - Für SharePoint Online und OneDrive für Unternehmen können Dateien auf mindestens einer Website wie hier beschrieben mit dem Kundenschlüssel verschlüsselt werden: Einrichten [des Kunden Schlüssels für SharePoint Online und OneDrive für Unternehmen](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-sharepoint-online-and-onedrive-for-business).

  - Für Exchange Online und Skype for Business Online können Postfächer mithilfe von Kunden Schlüsseln verschlüsselt werden, wie hier beschrieben: [Einrichten des Kunden Schlüssels für Exchange Online und Skype for Business](https://docs.microsoft.com/office365/securitycompliance/controlling-your-data-using-customer-key#office-365-setting-up-customer-key-for-exchange-online-and-skype-for-business)

## <a name="office-365-customer-lockbox"></a>Office 365-Kunden-Lockbox

Kunden-Lockbox bietet eine zusätzliche Kontrollschicht, indem Kunden die Möglichkeit bieten, explizite Zugriffsautorisierung für Dienstvorgänge zu erteilen. Durch den Nachweis, dass Verfahren für die explizite Datenzugriffs Autorisierung vorhanden sind, kann die Customer Lockbox auch Organisationen dabei helfen, bestimmte Compliance-Verpflichtungen wie HIPAA und FEDRAMP zu erfüllen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität und die Office 365 Advanced Compliance können von der Customer Lockbox profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von Lockbox-Kunden, die sicherstellen, dass niemand bei Microsoft auf Ihre Inhalte zugreifen kann, um einen Dienstvorgang ohne explizite Genehmigung des Kunden auszuführen. Kunden-Lockbox bringt den Kunden in den Genehmigungsworkflow für Anforderungen für den Zugriff auf Ihre Inhalte. Gelegentlich werden Microsoft-Techniker während des Supportprozesses zur Problembehandlung und zum Beheben von von Kunden gemeldeten Problemen beteiligt. In den meisten Fällen werden Probleme durch umfangreiche Telemetrie-und Debugging-Tools behoben, die Microsoft für seine Dienste implementiert hat. Es kann jedoch vorkommen, dass ein Microsoft-Techniker den Zugriff auf Kunden Inhalte erfordert, um die Ursache zu ermitteln und das Problem zu beheben. Kunden-Lockbox erfordert, dass der Techniker Zugriff vom Kunden als letzten Schritt im Genehmigungsworkflow anfordert. Dadurch erhalten Organisationen die Möglichkeit, diese Anforderungen zu genehmigen oder abzulehnen, sodass Sie direkt steuern können, ob ein Microsoft-Techniker auf die Endbenutzerdaten der Organisation zugreifen kann.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren können Kunden-Lockbox-Steuerelemente im Microsoft 365 Admin Center aktivieren. Weitere Informationen finden Sie unter [Customer Lockbox in Office 365](https://docs.microsoft.com/Office365/Admin/manage/customer-lockbox-requests). Wenn die Kunden-Lockbox aktiviert ist, muss Microsoft vor dem Zugriff auf Inhalte eine Organisation genehmigen.

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Microsoft bietet Kunden sperrbox-Zugriffs Steuerungs Genehmigungsanforderungen für Benutzer in Ihrer Office 365 Organisation.

## <a name="privileged-access-management-in-office-365"></a>Privileged Access Management in Office 365

Die privilegierte Zugriffsverwaltung (Access Management, PAM) bietet granulare Zugriffssteuerung für privilegierte Verwaltungsaufgaben in Office 365. Nachdem Sie PAM aktiviert haben, müssen Benutzer Just-in-Time-Zugriff über einen Genehmigungsworkflow anfordern, der sehr umfangreich und Zeit gebunden ist, um erhöhte und privilegierte Aufgaben auszuführen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität und Office 365 erweiterte Kompatibilität können von PAM profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Durch die Aktivierung von PAM können Organisationen mit NULL stehenden rechten arbeiten. Benutzer profitieren von der zusätzlichen Verteidigungsstufe gegen Sicherheitsrisiken, die sich aus dem ständigen administrativen Zugriff ergeben, der den ungehinderten Zugriff auf Ihre Daten ermöglicht.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig werden PAM-Features auf Mandantenebene für alle Benutzer innerhalb des Mandanten aktiviert. Informationen zum Konfigurieren von PAM-Richtlinien finden Sie unter [Configuring privileged Access Management in Office 365](https://docs.microsoft.com/office365/securitycompliance/privileged-access-management-configuration).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Kunden können PAM auf Benutzerebene über die genehmigende Gruppe und Zugriffsrichtlinien verwalten, die auf lizenzierte Benutzer angewendet werden können. Weitere Informationen finden Sie unter [privileged Access Management in Office 365](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Privileged-access-management-in-Office-365-is-now-Generally/ba-p/261751).

## <a name="data-loss-prevention-for-exchange-online-sharepoint-online-and-onedrive-for-business"></a>Verhinderung von Datenverlust für Exchange Online, SharePoint Online und OneDrive für Unternehmen

Mit der Verhinderung von Datenverlust (Data Loss Prevention, DLP) für Exchange Online, SharePoint Online und OneDrive für Unternehmen können Unternehmen vertrauliche Informationen in e-Mails und Dateien identifizieren, überwachen und automatisch schützen (einschließlich Dateien, die in der Microsoft Teams-Datei gespeichert sind. Repositories).

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E3/A3/G3, Microsoft 365 Business, Microsoft 365 a1/E3/A3/G3 und Office 365 Verhinderung von Datenverlust können DLP für Exchange Online, SharePoint Online und OneDrive für Unternehmen nutzen.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von DLP für Exchange Online, SharePoint Online und OneDrive für Unternehmen, wenn Ihre e-Mails und Dateien auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Exchange Online-e-Mails, SharePoint-Websites und OneDrive-Konten *Standorte (Arbeitslasten)* für diese DLP-Funktionen für alle Benutzer innerhalb des Mandanten aktiviert. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie unter [Übersicht über Verhinderung von Datenverlust](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können > **Speicherorte (** Arbeitslasten), eingeschlossene Benutzer und ausgeschlossene Benutzer im Office 365 Security #a0 Compliance Center unter **Verhinderung von Datenverlust**anpassen.

## <a name="data-loss-prevention-for-teams-chat-and-channel-messages"></a>Verhinderung von Datenverlust für Chat-und Kanal Nachrichten in Microsoft Teams

Mit der Verhinderung von Datenverlust (Data Loss Prevention, DLP) für Microsoft Teams-Chat und Kanal Nachrichten können Organisationen Chats und Kanal Nachrichten blockieren, die vertrauliche Informationen enthalten, beispielsweise Finanzinformationen, personenbezogene Informationen, gesundheitsbezogene Informationen oder andere vertrauliche Informationen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität und Office 365 erweiterte Kompatibilität können von DLP für Chat-und Kanal Nachrichten von Teams profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Absender profitieren davon, dass vertrauliche Informationen in Ihren ausgehenden Chat-und Kanal Nachrichten auf vertrauliche Informationen überprüft werden, wie in der DLP-Richtlinie der Organisation konfiguriert.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Standardmäßig sind Microsoft Teams-Chat und Kanal Nachrichten ein *aktivierter Speicherort (Arbeitsauslastung)* für diese DLP-Funktionen für alle Benutzer innerhalb des Mandanten. Weitere Informationen zur Verwendung von DLP-Richtlinien finden Sie unter [Übersicht über Verhinderung von Datenverlust](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können > **Speicherorte (** Arbeitslasten), eingeschlossene Benutzer und ausgeschlossene Benutzer im Office 365 Security #a0 Compliance Center unter **Verhinderung von Datenverlust**anpassen.

## <a name="information-barriers"></a>Informationsbarrieren

Informationsbarrieren sind Richtlinien, die ein Administrator konfigurieren kann, um zu verhindern, dass einzelne Personen oder Gruppen miteinander kommunizieren. Dies ist hilfreich, wenn beispielsweise eine Abteilung Informationen verarbeitet, die nicht für andere Abteilungen freigegeben werden sollten, oder wenn eine Gruppe nicht mit externen Kontakten kommunizieren muss. Richtlinien für Informationsbarrieren verhindern auch Nachschlagevorgänge und Ermittlungen. Dies bedeutet, dass Sie diesen Benutzer nicht in der Personenauswahl finden, wenn Sie versuchen, mit einer Person zu kommunizieren, mit der Sie nicht kommunizieren sollten.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität und Office 365 erweiterte Compliance können von Informationsbarrieren profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren von den erweiterten Kompatibilitätsfunktionen von Informationsbarrieren, wenn Sie von der Kommunikation mit anderen Personen eingeschränkt werden. Zum Beispiel:

| Szenario                                                                                                                                                                                                              | Wer benötigt eine Lizenz? |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| Zwei Gruppen (Gruppe 1 und Gruppe 2) können nicht miteinander kommunizieren (das heißt, die Benutzer von Gruppe 1 dürfen nicht mit Gruppen 2-Benutzern kommunizieren, und Gruppen 2-Benutzer sind von der Kommunikation mit Gruppen 1-Benutzern beschränkt. | Benutzer in Gruppe 1 und Gruppe 2                    |
| Benutzer in Gruppe 1 sind von der Kommunikation mit dem Rest des Unternehmens eingeschränkt.                                                                                                                                       | Nur Benutzer in Gruppe 1                                |
| Der Rest des Unternehmens ist von der Kommunikation mit Gruppe 1 eingeschränkt.                                                                                                                                                 | Alle Benutzer mit Ausnahme der in Gruppe 1                    |
| Benutzer von Gruppe 1 sind von der Kommunikation mit Benutzern der Gruppe 2 eingeschränkt, Benutzer von Gruppe 2 können jedoch mit Gruppen 1-Benutzern kommunizieren.                                                                                              | Nur Benutzer in Gruppe 1                                |

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Richtlinien für Informationsbarrieren mithilfe von PowerShell-Cmdlets im Security #a0 Compliance Center. Administratoren muss die Rolle Microsoft 365 Enterprise Global Administrator, Office 365 globaler Administrator oder Administrator für die Konformitätsrichtlinie zugewiesen sein, um eine Informations Barriere-Richtlinie zu erstellen. Standardmäßig gelten diese Richtlinien für alle Benutzer im Mandanten. Weitere Informationen zu Informationsbarrieren finden Sie unter [Information Barriers in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren können Standorte (Arbeitslasten), eingeschlossene Benutzer und ausgeschlossene Benutzer im Office 365 Security #a0 Compliance Center anpassen. Wenn beispielsweise alle Benutzer für Office 365 E3 lizenziert sind und keine für Office 365 Advanced Compliance/E5 lizenziert ist, müssen keine Richtlinien für Informationsbarrieren für die Organisation erstellt werden. Weitere Informationen finden Sie unter [Information Barriers in Microsoft Teams](https://docs.microsoft.com/MicrosoftTeams/information-barriers-in-teams).

## <a name="office-365-message-encryption"></a>Office 365-Nachrichtenverschlüsselung

Office 365-Nachrichtenverschlüsselung (Office Message Encryption, OME) ist ein Dienst, der auf Azure Rights Management (Azure RMS) aufbaut und mit dem Sie verschlüsselte E-Mails an Personen innerhalb oder außerhalb Ihrer Organisation senden können, unabhängig von der E-Mail-Zieladresse (Gmail, Yahoo! Mail, Outlook.com usw.).

Zum Anzeigen verschlüsselter Nachrichten können Empfänger entweder eine einmalige Kennung abrufen, sich mit einem Microsoft-Konto anmelden oder sich mit einem Geschäfts- oder Schulkonto anmelden, das Office 365 zugeordnet ist. Empfänger können auch verschlüsselte Antworten senden. Sie benötigen kein Office 365-Abonnement, um verschlüsselte Nachrichten anzuzeigen oder verschlüsselte Antworten zu senden.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E3/A3/G3, Microsoft 365 E3/A3/G3 und Azure Information Protection Plan 1 können von der Office 365 Nachrichtenverschlüsselung profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Nachrichtenabsender profitieren von der zusätzlichen Kontrolle über vertrauliche e-Mails, die von Office 365 Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten Office 365 Nachrichten Verschlüsselungsrichtlinien im Exchange Admin Center unter **Nachrichtenfluss** > **Regeln**. Diese Regeln gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Office 365 Nachrichten Verschlüsselungsfunktionen finden Sie unter [Einrichten neuer Office 365 Nachrichten Verschlüsselungsfunktionen](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenfluss Regeln für Office 365 Nachrichtenverschlüsselung nur für lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenfluss Regeln finden Sie unter [Definieren von Nachrichtenfluss Regeln zum Verschlüsseln von e-Mail-Nachrichten in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).


## <a name="office-365-advanced-message-encryption"></a>Erweiterte Office 365-Nachrichtenverschlüsselung

Die erweiterte Nachrichtenverschlüsselung hilft Kunden bei der Erfüllung von Compliance-Verpflichtungen, die flexiblere Kontrollen über externe Empfänger und deren Zugriff auf verschlüsselte e-Mails erfordern. Mit der erweiterten Nachrichtenverschlüsselung können Administratoren vertrauliche und außerhalb der Organisation freigegebene e-Mails mithilfe automatischer Richtlinien steuern, mit denen vertrauliche Informationstypen erkannt werden können (beispielsweise persönlich identifizierende Informationen oder Finanz-oder Integritäts-IDs) oder Sie können Schlüsselwörter verwenden, um den Schutz zu verbessern, indem benutzerdefinierte e-Mail-Vorlagen und ablaufenden Zugriff auf verschlüsselte e-Mails über ein sicheres Webportal angewendet werden. Darüber hinaus können Administratoren verschlüsselte e-Mails, auf die extern über ein sicheres Webportal zugegriffen wird, weiter steuern, indem Sie den Zugriff jederzeit widerrufen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität und Office 365 erweiterte Kompatibilität können von der erweiterten Nachrichtenverschlüsselung profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Nachrichtenabsender profitieren von der zusätzlichen Kontrolle über vertrauliche e-Mails, die von der erweiterten Nachrichtenverschlüsselung bereitgestellt werden.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen und verwalten erweiterte Nachrichten Verschlüsselungsrichtlinien im Exchange Admin Center unter Nachrichtenfluss Regeln. Diese Regeln gelten standardmäßig für alle Benutzer im Mandanten. Weitere Informationen zum Einrichten neuer Nachrichten Verschlüsselungsfunktionen finden Sie unter [Einrichten neuer Office 365 Nachrichten Verschlüsselungsfunktionen](https://docs.microsoft.com/office365/securitycompliance/set-up-new-message-encryption-capabilities).

### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren sollten Nachrichtenfluss Regeln für erweiterte Nachrichtenverschlüsselung nur für lizenzierte Benutzer anwenden. Weitere Informationen zum Definieren von Nachrichtenfluss Regeln finden Sie unter [Definieren von Nachrichtenfluss Regeln zum Verschlüsseln von e-Mail-Nachrichten in Office 365](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email).

## <a name="supervision-policies"></a>Aufsichtsrichtlinien

Aufsichtsrichtlinien in Office 365 ermöglichen es Ihnen, Mitarbeiter Kommunikationen zur Untersuchung durch designierte Bearbeiter zu erfassen. Sie können bestimmte Richtlinien definieren, die interne und externe e-Mails, Microsoft Teams oder Drittanbieter Kommunikationen in Ihrer Organisation erfassen. Bearbeiter können dann die Nachrichten überprüfen, um sicherzustellen, dass Sie mit den Nachrichtenstandards Ihrer Organisation übereinstimmen und diese mit dem Klassifizierungs lösen.

### <a name="which-users-benefit-from-the-service"></a>Welche Benutzer profitieren vom Dienst?

Lizenzierte Benutzer von Office 365 E5/A5/G5, Microsoft 365 E5/A5/G5, Microsoft 365 E5/A5/G5-Konformität und Office 365 erweiterte Compliance können von Aufsichtsrichtlinien profitieren.

### <a name="how-do-users-benefit-from-the-service"></a>Wie profitieren Benutzer vom Dienst?

Benutzer profitieren vom Dienst, indem ihre Kommunikation durch Aufsichtsrichtlinien überwacht wird.

### <a name="how-is-the-service-provisioneddeployed"></a>Wie wird der Dienst bereitgestellt/bereitgestellt?

Administratoren erstellen Aufsichtsrichtlinien im Security #a0 Compliance Center. Diese Richtlinien definieren, welche Kommunikation und welche Benutzer in der Organisation überprüft werden sollen, definieren benutzerdefinierte Bedingungen, denen die Kommunikation entsprechen muss, und geben an, wer Überprüfungen durchführen soll.
 
### <a name="how-can-the-service-be-applied-only-to-users-in-the-tenant-who-are-licensed-for-the-service"></a>Wie kann der Dienst nur auf Benutzer im Mandanten angewendet werden, die für den Dienst lizenziert sind?

Administratoren wählen bestimmte Benutzer oder Gruppen aus, die in eine Aufsichtsrichtlinie eingeschlossen werden sollen. Bei der Auswahl einer Gruppe können Sie auch bestimmte Benutzer in der Gruppe auswählen, die von der Aufsichtsrichtlinie ausgeschlossen werden sollen. Weitere Informationen zur Aufsichtsrichtlinie finden Sie unter [Aufsichtsrichtlinien in Office 365](https://docs.microsoft.com/office365/SecurityCompliance/supervision-policies).
