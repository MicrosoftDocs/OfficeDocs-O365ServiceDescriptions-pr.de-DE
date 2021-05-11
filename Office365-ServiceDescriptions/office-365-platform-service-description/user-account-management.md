---
title: User account management
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-user-account-management
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc_top
- Adm_ServiceDesc
ms.assetid: e7616079-5b13-4f1c-99ed-b20174e0808d
description: Microsoft unterstützt die folgenden Methoden zum Erstellen, Verwalten und Authentifizieren von Benutzern.
ms.openlocfilehash: 16c12692107e789692b28351eed7dae5b32b18d9
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652409"
---
# <a name="user-account-management"></a>User account management

Microsoft unterstützt die folgenden Methoden zum Erstellen, Verwalten und Authentifizieren von Benutzern. 
  
> [!NOTE]
> Dieses Thema enthält keine Informationen zu Sicherheitsfeatures, die den Zugriff auf einzelne Microsoft-Ressourcen zulassen oder verbieten (z. B. rollenbasierte Zugriffssteuerung in Microsoft Exchange Online oder Konfigurieren der Sicherheit in Microsoft Office SharePoint Online). Ausführliche Informationen zu diesen Features finden Sie in Exchange Online [Dienstbeschreibung](../exchange-online-service-description/exchange-online-service-description.md) und SharePoint [Online-Dienstbeschreibung](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Wenn Sie Informationen zu Tools benötigen, mit deren Hilfe Sie Administrative Aufgaben ausführen können, finden Sie weitere Informationen unter [Tools to manage Microsoft accounts](/office365/enterprise/manage-office-365-accounts). Informationen zum Ausführen von täglichen Verwaltungsaufgaben finden Sie unter [Allgemeine Verwaltungsaufgaben](/office365/admin/manage/manage).
  
## <a name="need-help-with-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>Benötigen Sie Hilfe beim Anmelden, Installieren oder Deinstallieren oder Kündigen Ihres Abonnements?

Hilfe zu: [Anmelden beim Installieren](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4)oder  |  [Deinstallieren Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658)Abbrechen  |  [Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Weitere Probleme finden Sie im [Microsoft Support Center](https://support.microsoft.com/contactus/). Support für Office 365 betrieb von 21Vianet in China erhalten Sie vom [21Vianet-Supportteam](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Ansprechpartner für Office 365 Deutschland ist das [Office 365 Deutschland-Supportteam](https://support.office.com/article/83ef2266-2543-48d7-a41a-1b56b403a8e9). 
  
## <a name="sign-in-options"></a>Anmeldeoptionen

Microsoft verfügt über zwei Systeme, die für Benutzeridentitäten verwendet werden können:
  
- **Geschäfts- oder Schulkonto (Cloudidentität)** – Benutzer erhalten Azure Active Directory Cloudanmeldeinformationen , die von anderen Desktop- oder Unternehmensanmeldeinformationen getrennt sind, für die Anmeldung bei Microsoft Cloud Services. Dies ist die Standardidentität und wird empfohlen, um die Komplexität der Bereitstellung zu minimieren. Kennwörter für Arbeits- oder Schulkonten verwenden die Azure Active Directory [Kennwortrichtlinie](/previous-versions/azure/jj943764(v=azure.100)).
    
- **Verbundkonto (Verbundidentität)** – Für alle Abonnements in Organisationen mit lokalem Active Directory, die einmaliges Anmelden (Single Sign-On, SSO) verwenden, können sich Benutzer mit ihren Active Directory-Anmeldeinformationen bei Microsoft-Dienste anmelden. Das firmeneigene Active Directory speichert und steuert die Kennwortrichtlinie. Weitere Informationen über SSO finden Sie unter [Fahrplan für einmaliges Anmelden](/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Die Art der Identität hat Auswirkungen auf die Benutzerfreundlichkeit, Verwaltungsoptionen für Benutzerkonten, Hardware- und Softwareanforderungen sowie weitere Bereitstellungsüberlegungen.
  
### <a name="custom-domains-and-identity-options"></a>Benutzerdefinierte Domänen und Identitätsoptionen

Wenn Sie einen neuen Benutzer erstellen, werden der Anmeldename und die E-Mail-Adresse des Benutzers der Standarddomäne zugewiesen, wie im Microsoft 365 festgelegt. Weitere Informationen finden Sie unter [Add your users and domain](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
Standardmäßig verwendet das Abonnement den < > **.onmicrosoft.com,die** mit dem Konto erstellt wurde. Wenn Sie die von 21Vianet in China betriebene Office 365 verwenden, ist die Standarddomäne <> **Firmenname .onmsChina.cn**. Wenn Sie Office 365 Deutschland verwenden, ist die Standarddomäne < > **Firmenname .onmicrosoft.de**. Sie können Microsoft eine oder mehrere benutzerdefinierte  Domänen hinzufügen, anstatt die onmicrosoft.com-Domäne zu behalten, und Benutzern die Anmeldung bei einer der überprüften Domänen zuweisen. Die einem Benutzer zugewiesene Domäne ist die E-Mail-Adresse, die in gesendeten und empfangenen E-Mails angezeigt wird. 
  
Sie können bis zu 900 registrierte Internetdomänen hosten, die jeweils durch einen anderen Namespace dargestellt werden. 
  
In Organisationen, die einmaliges Anmelden verwenden, müssen alle Benutzer in einer Domäne dasselbe Identitätssystem verwenden: Cloudidentität oder Verbundidentität. Sie könnten beispielsweise eine Gruppe von Benutzern haben, die nur eine Cloudidentität benötigt, da sie nicht auf lokale Systeme zugreifen, und eine andere Gruppe von Benutzern, die Microsoft und lokale Systeme verwenden. Sie würden zwei Domänen zu Office 365 hinzufügen, z. B. **contractors.contoso.com** und **staff.contoso.com**, und nur SSO für eine dieser Domänen einrichten. Eine ganze Domäne kann von Cloudidentität in Verbundidentität und von Verbundidentität in Cloudidentität konvertiert werden.
  
Weitere Informationen zu Domänen in Office 365 finden Sie unter [Domänen](domains.md). 
  
## <a name="authentication"></a>Authentifizierung

Mit Ausnahme von Internetwebsites für anonymen Zugriff, die mit SharePoint Online erstellt wurden, müssen Benutzer authentifiziert werden, wenn sie auf Microsoft-Dienste. 
  
- **Moderne Authentifizierung** – Moderne Authentifizierung sorgt für die plattformbasierte Anmeldung Office Client-Apps. Dadurch werden Anmeldefeatures wie Multi-Factor Authentication (MFA, mehrstufige Authentifizierung), SAML-basierte Drittanbieter-Identitätsanbieter mit Office-Clientanwendungen sowie eine Smartcard- und zertifikatbasierte Authentifizierung ermöglicht. Außerdem muss Microsoft Outlook nicht mehr das grundlegende Authentifizierungsprotokoll verwenden. Weitere Informationen, einschließlich der Verfügbarkeit der modernen Authentifizierung in Office-Anwendungen, finden Sie unter Funktionsweise der modernen Authentifizierung für [Office 2013 und Office 2016-Client-Apps](/office365/enterprise/modern-auth-for-office-2013-and-2016).
    
    Die moderne Authentifizierung ist standardmäßig für Exchange Online. Informationen zum Aktivieren oder Deaktivieren finden Sie unter Aktivieren der modernen [Authentifizierung in Exchange Online](/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Cloudidentitätsauthentifizierung** : Benutzer mit Cloudidentitäten werden mithilfe herkömmlicher Herausforderungen/Antworten authentifiziert. Der Webbrowser wird an den Microsoft-Anmeldedienst umgeleitet, in dem Sie den Benutzernamen und das Kennwort für Ihr Arbeits- oder Schulkonto eingeben. Der Anmeldedienst authentifiziert Ihre Anmeldeinformationen und generiert ein Diensttoken, das der Webbrowser dem angeforderten Dienst bereitstellt, und Sie werden angemeldet. 
    
- **Verbundidentitätsauthentifizierung** : Benutzer mit Verbundidentitäten werden mithilfe von Active Directory Federation Services (AD FS) 2.0 oder anderen Sicherheitstokendiensten authentifiziert. Der Webbrowser wird an den Microsoft-Anmeldedienst umgeleitet, bei dem Sie Ihre Unternehmens-ID in form eines Benutzerprinzipalnamens (User Principal Name, UPN) eingeben, z. B. *isabel@contoso.com*. Der Anmeldedienst ermittelt, dass Sie Teil einer Verbunddomäne sind, und bietet an, Sie zur Authentifizierung an den lokalen Verbundserver weiterzuleiten. Wenn Sie am Desktop angemeldet sind (Domäne beigetreten), werden Sie authentifiziert (mit Kerberos oder NTLMv2), und der lokale Sicherheitstokendienst generiert ein Anmeldetoken, das der Webbrowser an den Microsoft-Anmeldedienst postet. Der Anmeldedienst generiert mithilfe des Anmeldetokens ein Diensttoken, das vom Webbrowser an den angeforderten Dienst weitergeleitet wird, und meldet Sie an. Eine Liste der verfügbaren Sicherheitstokendienste finden Sie unter Roadmap für einmaliges [Anmelden](/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Microsoft verwendet die formularbasierte Authentifizierung, und der Authentifizierungsverkehr über das Netzwerk wird immer mit TLS/SSL über Port 443 verschlüsselt. Authentifizierungsverkehr verwendet einen vernachlässigbaren Prozentsatz der Bandbreite für Microsoft-Dienste. 
  
### <a name="multi-factor-authentication"></a>Mehrstufige Authentifizierung

Bei der mehrstufigen Authentifizierung müssen Benutzer einen Anruf, eine SMS oder eine App-Benachrichtigung auf ihrem Smartphone bestätigen, nachdem sie ihr Kennwort richtig eingegeben haben. Erst nach dieser zweiten Authentifizierung kann sich der Benutzer anmelden. Microsoft-Administratoren können Benutzer für die mehrstufige Authentifizierung im Microsoft 365 registrieren. Erfahren Sie mehr [über mehrstufige Authentifizierung](/office365/admin/security-and-compliance/set-up-multi-factor-authentication).
  
### <a name="rich-client-authentication"></a>Rich-Client-Authentifizierung

Rich-Clients wie Microsoft Office-Desktopanwendungen können auf zwei Arten authentifiziert werden:
  
- **Microsoft Online Services Sign-In-Assistent** : Der Vom Desktop-Setup installierte Anmelde-Assistent enthält einen Clientdienst, der ein Diensttoken vom Anmeldedienst erhält und an den Rich-Client zurückgibt. 
    
  - Wenn Sie über eine Cloudidentität verfügen, erhalten Sie eine Eingabeaufforderung für Anmeldeinformationen, die der Clientdienst zur Authentifizierung an den Anmeldedienst sendet (mithilfe von WS-Trust).
    
  - Wenn Sie über eine Verbundidentität verfügen, kontaktiert der Clientdienst zuerst den AD FS 2.0-Server, um die Anmeldeinformationen zu authentifizieren (mithilfe von Kerberos oder NTLMv2) und ein Anmeldetoken abzurufen, das an den Anmeldedienst gesendet wird (mithilfe von WS-Federation und WS-Trust).
    
- **Standard-/Proxyauthentifizierung** über SSL – Der Outlook-Client übergibt grundlegende Authentifizierungsanmeldeinformationen über SSL an Exchange Online. Exchange Online die Authentifizierungsanforderung an die Identitätsplattform und dann an den lokalen Active Directory-Verbundserver (für SSO) weiter. 
    
Um eine ordnungsgemäße Erkennung und Authentifizierung von Microsoft-Dienste sicherzustellen, müssen Administratoren auf jede Arbeitsstation, die Rich Clients (z. B. Microsoft Office 2010) verwendet, eine Reihe von Komponenten und Updates anwenden und eine Verbindung mit Office 365. Desktopeinrichtung ist ein automatisiertes Tool zum Konfigurieren von Arbeitsstationen mit den erforderlichen Updates. Weitere Informationen finden Sie unter [Use my current Office desktop apps](https://support.office.com/article/3324b8b8-dceb-45e2-ac24-c642720108f7).
  
### <a name="sign-in-experience"></a>Anmeldung

Die Anmeldeerfahrung ändert sich abhängig vom verwendeten Identitätstyp:<br><br>
  
| Dienst | Cloudidentität | Identitätsverbund |
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Outlook 2010 oder Office 2007 auf Windows 7  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Outlook 2010 oder Office Outlook 2007 auf Windows Vista  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|POP, IMAP, Outlook für Mac  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Weberfahrungen: Microsoft 365 Admin Center / Outlook im Web/ SharePoint Online / Office für das Web  <br/> |Jede Browsersitzung anmelden <sup>4</sup> <br/> |Jede Sitzung anmelden <sup>3</sup> <br/> |
|Office 2010 oder Office 2007 mit SharePoint Online  <br/> |Jede SharePoint Online-Sitzung anmelden <sup>4</sup> <br/> |Jede SharePoint Online-Sitzung anmelden <sup>3</sup> <br/> |
|Skype for Business Online  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Keine Aufforderung  <br/> |
|Outlook für Mac  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Wenn Sie zum ersten Mal dazu aufgefordert werden, können Sie Ihr Kennwort für die zukünftige Verwendung speichern. Sie erhalten keine weitere Aufforderung, bis Sie das Kennwort ändern. <br/> 
<sup>2</sup> Sie geben Ihre Unternehmensanmeldeinformationen ein. Sie können Ihr Kennwort speichern und werden nicht wieder aufgefordert, bis Sie Ihr Kennwort ändern. <br/> 
<sup>3</sup> Für alle Apps müssen Sie Ihren Benutzernamen eingeben oder auswählen, um sich anmelden zu können. Sie werden nicht zur Kennworteingabe aufgefordert, wenn Ihr Computer der Domäne hinzugefügt wurde. Wenn Sie **Anmelden** anmelden auswählen, werden Sie erst dann erneut aufgefordert, wenn Sie sich abmelden. <br/> 
<sup>4</sup> Wenn Sie **Anmelden** anmelden auswählen, werden Sie erst wieder aufgefordert, wenn Sie sich abmelden. 
  
## <a name="create-user-accounts"></a>Create user accounts

Es gibt mehrere Möglichkeiten zum Hinzufügen von Benutzern. Weitere Informationen finden Sie unter [Add users individually or in bulk - Admin Help](/office365/admin/add-users/add-users) and [Add, remove, and manage users in Microsoft 365 admin center Preview](https://support.office.com/article/6e80db58-c36b-4add-b1c8-cc5135f111f3). Wenn Sie Office 365 im Betrieb durch 21Vianet in China verwenden, finden Sie Informationen unter [Erstellen oder Bearbeiten von Benutzerkonten in Office 365 betrieben von 21Vianet - Admininstratorhilfe](/office365/admin/add-users/add-users).
  
## <a name="delete-user-accounts"></a>Löschen von Benutzerkonten

Wie Sie Konten löschen, hängt davon ab, ob Sie die Verzeichnissynchronisierung nutzen: 
  
- Wenn Sie keine Verzeichnissynchronisierung verwenden, können Konten mithilfe der Administratorseite oder mithilfe von Windows PowerShell.
    
- Wenn Sie die Verzeichnissynchronisierung nutzen, müssen Sie Benutzer aus der lokalen Active Directory-Instanz und nicht aus Office 365 löschen.
    
Wenn ein Konto gelöscht wird, wird es inaktiv. Sie können das Konto ungefähr 30 Tage nach dem Löschen wiederherstellen. Weitere Informationen zum Löschen und [](/office365/admin/add-users/delete-a-user) Wiederherstellen [](/office365/admin/add-users/restore-user) von Konten finden Sie unter Löschen von Benutzern und Wiederherstellen von Benutzern oder, wenn Sie Office 365 betrieben von 21Vianet in China verwenden, finden Sie unter Create [or edit user accounts in Office 365 operated by 21Vianet - Admin Help](/office365/admin/add-users/add-users).
  
## <a name="password-management"></a>Kennwortverwaltung

Die Richtlinien und Verfahren für die Kennwortverwaltung hängen vom Identitätssystem ab.
  
### <a name="cloud-identity-password-management"></a>Verwaltung von Cloudidentitätskennworten
  
Bei der Verwendung von Cloudidentitäten werden Kennwörter automatisch generiert, wenn das Konto erstellt wird.
  
- Die Anforderungen für sichere Kennwörter bei Cloudidentitäten finden Sie unter [Kennwortrichtlinie](/previous-versions/azure/jj943764(v=azure.100)).
    
- Um die Sicherheit zu erhöhen, müssen Benutzer ihre Kennwörter ändern, wenn sie zum ersten Mal auf Microsoft-Dienste. Daher müssen sich Benutzer, bevor sie auf Microsoft-Dienste zugreifen können, beim Microsoft 365 Admin Center anmelden, wo sie aufgefordert werden, ihre Kennwörter zu ändern.
    
- Administratoren können die Kennwortablaufrichtlinie festlegen. Weitere Informationen finden Sie unter [Festlegen der Ablaufrichtlinie für ein Benutzerkennwort](/office365/admin/manage/set-password-expiration-policy).
    
Es gibt mehrere Tools zum Zurücksetzen von Kennwörtern für Benutzer mit Cloudidentitäten:
  
- **Administrator setzt Kennwort zurück** – Wenn Benutzer ihre Kennwörter verlieren oder vergessen, können Administratoren die Kennwörter der Benutzer im Admin Center oder mithilfe von Windows PowerShell. Benutzer können ihr eigenes Kennwort nur ändern, wenn sie ihr bestehendes Kennwort kennen. 
    
    Wenn Administratoren bei Unternehmensplänen ihre Kennwörter verlieren oder vergessen, kann ein anderer Administrator mit der Rolle Globaler Administrator die Kennwörter von Administratoren im Microsoft 365 Admin Center oder mithilfe von Windows PowerShell. Weitere Informationen finden Sie im Artikel zum Thema [Zurücksetzen von Administratorkennwörtern](/office365/admin/add-users/reset-passwords). Wenn Sie Office 365 über 21Vianet in China verwenden, lesen Sie [Change or reset your password in Office 365 operated by 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Benutzer ändert Kennwörter mit Outlook** im Web – Die Outlook auf der Weboptionenseite enthält einen Kennwortlink ändern, der Benutzer zur Seite Kennwort ändern umleitt.  Der Benutzer muss das bisherige Kennwort kennen. Weitere Informationen finden Sie im Artikel zum Thema [Ändern des Kennworts](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Wenn Sie Office 365 über 21Vianet in China verwenden, lesen Sie [Change or reset your password in Office 365 operated by 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- Rollenbasierte Zurücksetzen von Kennwortrechten **–** Für Unternehmenspläne können autorisierten  Benutzern wie Helpdeskmitarbeitern das Benutzerrecht Kennwort zurücksetzen und das Recht zum Ändern von Kennwörtern mithilfe vordefinierter oder benutzerdefinierter Rollen zugewiesen werden, ohne Volldienstadministratoren zu werden. In Unternehmensplänen können Administratoren mit der Rolle globaler Administrator, Kennwortadministrator oder Benutzerverwaltungsadministrator standardmäßig Kennwörter ändern. Weitere Informationen finden Sie unter [Zuweisen von Adminrollen](/office365/admin/add-users/assign-admin-roles).
    
- **Zurücksetzen von Kennwörtern Windows PowerShell** - Dienstadministratoren können Windows PowerShell zum Zurücksetzen von Kennwörtern verwenden. 
    
### <a name="federated-identity-password-management"></a>Verwaltung von Verbundidentitätskennworten
  
Bei Verwendung von Verbundidentitäten werden Kennwörter in Active Directory verwaltet. Der lokale Sicherheitstokendienst handelt die Authentifizierung mit dem Verbundgateway aus, ohne die lokalen Active Directory-Kennwörter der Benutzer über das Internet an Office 365. Lokale Kennwortrichtlinien werden verwendet, oder für Webclients wird die zwei-Faktor-Identifikation verwendet. Outlook im Web enthält keinen Link Kennwort ändern. Benutzer ändern ihre Kennwörter mit standardmäßigen, lokalen Tools oder über ihre Desktop-PC-Anmeldeoptionen.
  
Wenn Sie die Verzeichnissynchronisierung mit einmaligem Anmelden [(Single Sign-On, SSO)](/previous-versions/azure/azure-services/dn441213(v=azure.100)) in Ihrer Organisationsumgebung aktiviert haben und ein Ausfall vor liegt, der sich auf Ihren Verbundidentitätsanbieter aus wirkt, bietet die Kennwortsynchronisierungssicherung für die Verbundregistrierung die Möglichkeit, Ihre Domäne manuell auf Kennwortsynchronisierung umzusetzen. Die Verwendung der Kennwortsynchronisierung ermöglicht Benutzern den Zugriff, während der Ausfall behoben ist. Erfahren [Sie, wie Sie von single Sign-On zu Password Sync wechseln.](https://go.microsoft.com/fwlink/p/?LinkId=509832)
  
## <a name="license-management"></a>Lizenzverwaltung

Eine Lizenz bietet einem Benutzer Zugriff auf eine Reihe von Microsoft-Dienste. Ein Administrator weist jedem Benutzer für jeden Dienst, auf den er zugreifen muss, eine Lizenz zu. Sie können beispielsweise einem Benutzer den Zugriff auf Skype for Business Online, aber nicht auf SharePoint Online gewähren.
  
Microsoft-Abrechnungsadministratoren können Änderungen an Abonnementdetails vornehmen, z. B. die Anzahl der Benutzerlizenzen und die Anzahl zusätzlicher Dienste, die Ihr Unternehmen verwendet. Lesen Sie [Zuweisen oder Entfernen einer Lizenz](/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Wenn Sie Office 365 über 21Vianet verwenden, lesen Sie [Assign or remove licenses in Office 365 operated by 21Vianet](/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Gruppenverwaltung

Sicherheitsgruppen werden in SharePoint Online zum Steuern des Zugriffs auf Websites verwendet. Sicherheitsgruppen können im Microsoft 365 erstellt werden. Weitere Informationen zu Sicherheitsgruppen finden Sie unter [Erstellen, Bearbeiten oder Entfernen einer Sicherheitsgruppe](/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Administratorrollen

Office 365 für Unternehmen folgt einem rollenbasierten Zugriffssteuerungsmodell(RBAC): Berechtigungen und Funktionen werden durch Verwaltungsrollen definiert. Die Person, die sich für ihre Organisation für Office 365 registriert, wird automatisch globaler Administrator (oder Hauptadministrator). Es gibt fünf Administratorrollen: globaler Administrator, Rechnungsadministrator, Kennwortadministrator, Dienstadministrator und Benutzerverwaltungsadministrator. Weitere Informationen zu Administratorrollen in Office 365 für Unternehmen, einschließlich ihrer Anwendung auf Exchange Online, SharePoint Online und Skype for Business Onlineverwaltung, finden Sie unter [Assigning administrator roles](/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). Wenn Sie Office 365 über 21Vianet in China verwenden, lesen Sie [Zuweisen von Administratorrollen in Office 365 Business](/office365/admin/add-users/assign-admin-roles).
  
## <a name="delegated-administration-and-support-for-partners"></a>Delegierte Verwaltung und Unterstützung für Partner

Partner können zum Verwalten von Konten im Namen von Kunden autorisiert werden. Der Kunde benötigt kein Benutzerkonto für die Von partnern verwendeten Und nutzt keine Lizenz, wenn er delegierte Verwaltungsbehörde gewährt. Partner können Benutzern in ihrer Organisation vollständigen oder eingeschränkten Zugriff zuweisen. Zum eingeschränkten Zugriff gehören Rechte wie das Zurücksetzen von Kennwörtern, das Verwalten von Serviceanfragen und das Überwachen des Dienstzustands. 
  
> [!NOTE]
> Die Möglichkeit zum Verwenden und Angeben eines Partners als delegierter Administrator kann je nach Region variieren. 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory-Dienste

Azure Active Directory (AD) bietet umfassende Identitäts- und Zugriffsverwaltungsfunktionen für Office 365. Es kombiniert Verzeichnisdienste, erweiterte Identity Governance, Anwendungszugriffsverwaltung und eine funktionsreiche standardbasierte Plattform für Entwickler. Weitere Informationen zu AD-Features in Office 365 finden Sie unter [Sign in page branding and cloud user self-service password reset]() https://go.microsoft.com/fwlink/?linkid=2144147 . Hier erfahren Sie mehr über die [Azure Active Directory-Editionen Free, Basic und Premium](/previous-versions/azure/dn532272(v=azure.100)). 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zur Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Microsoft 365 und Office 365 Plattformdienstbeschreibung](office-365-platform-service-description.md).
