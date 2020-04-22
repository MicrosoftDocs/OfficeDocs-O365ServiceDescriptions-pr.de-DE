---
title: User account management
ms.author: sharik
author: skjerland
manager: mnirkhe
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
description: Microsoft unterstützt die folgenden Methoden zum Erstellen, verwalten und Authentifizieren von Benutzern.
ms.openlocfilehash: 2de28edc6e85e2ac0f849d797639e29fdc62d5f9
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/21/2020
ms.locfileid: "43639823"
---
# <a name="user-account-management"></a>User account management

Microsoft unterstützt die folgenden Methoden zum Erstellen, verwalten und Authentifizieren von Benutzern. 
  
> [!NOTE]
> Dieses Thema enthält keine Informationen zu Sicherheitsfeatures, die den Zugriff auf einzelne Microsoft-Ressourcen zulassen oder verbieten (beispielsweise rollenbasierte Zugriffssteuerung in Microsoft Exchange Online oder Konfigurieren der Sicherheit in Microsoft SharePoint Online). Ausführliche Informationen zu diesen Features finden Sie unter [Exchange Online Dienstbeschreibung](../exchange-online-service-description/exchange-online-service-description.md) und [SharePoint Online Dienstbeschreibung](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Wenn Sie Informationen zu Tools benötigen, die Ihnen bei der Ausführung von Verwaltungsaufgaben helfen können, finden Sie unter [Tools to manage Microsoft Accounts](https://docs.microsoft.com/office365/enterprise/manage-office-365-accounts). Informationen zum Ausführen täglicher Verwaltungsaufgaben finden Sie unter [Allgemeine Verwaltungsaufgaben für Office 365](https://docs.microsoft.com/office365/admin/manage/manage).
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>Benötigen Sie Hilfe bei der Anmeldung, Installation, Deinstallation oder der Kündigung Ihres Abonnements?

Hier finden Sie Unterstützung: [Anmelden bei Office 365](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4) | [Installieren oder Deinstallieren von Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658) | [Kündigen von Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Weitere Probleme finden Sie im [Microsoft Support Center](https://support.microsoft.com/contactus/). Support für Office 365 betrieb von 21Vianet in China erhalten Sie vom [21Vianet-Supportteam](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Ansprechpartner für Office 365 Deutschland ist das [Office 365 Deutschland-Supportteam](https://support.office.com/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1). 
  
## <a name="sign-in-options"></a>Anmeldeoptionen

Microsoft verfügt über zwei Systeme, die für Benutzeridentitäten verwendet werden können:
  
- **Geschäftliches oder Schulkonto (Cloud-Identität)** Benutzer erhalten Azure Active Directory Cloud-Anmeldeinformationen – getrennt von anderen Desktop-oder Unternehmensanmeldeinformationen – für die Anmeldung bei Microsoft Cloud Services. Dies ist die Standardidentität und wird empfohlen, um die Komplexität der Bereitstellung zu minimieren. Kennwörter für Arbeits-oder Schul Konten verwenden die Azure Active Directory- [Kennwortrichtlinie](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- **Verbund Konto (Verbundidentität)** Für alle Abonnements in Organisationen mit lokalen Active Directory, die einmaliges Anmelden (Single Sign-on, SSO) verwenden, können sich Benutzer mit Ihren Active Directory Anmeldeinformationen bei Microsoft-Diensten anmelden. Das firmeneigene Active Directory speichert und steuert die Kennwortrichtlinie. Weitere Informationen über SSO finden Sie unter [Fahrplan für einmaliges Anmelden](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Die Art der Identität hat Auswirkungen auf die Benutzerfreundlichkeit, Verwaltungsoptionen für Benutzerkonten, Hardware- und Softwareanforderungen sowie weitere Bereitstellungsüberlegungen.
  
### <a name="custom-domains-and-identity-options"></a>Benutzerdefinierte Domänen und Identitätsoptionen

Wenn Sie einen neuen Benutzer erstellen, werden der Anmeldename und die e-Mail-Adresse des Benutzers der Standarddomäne zugewiesen, die im Microsoft 365 Admin Center festgelegt ist. Weitere Informationen finden Sie unter [Hinzufügen Ihrer Benutzer und Domänen zu Office 365](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
Standardmäßig verwendet das Abonnement die Domäne \< " _Company Name_ \> **. onmicrosoft.com** ", die mit dem Konto erstellt wurde. \* Sie können eine oder mehrere benutzerdefinierte Domänen zu Microsoft hinzufügen, anstatt die onmicrosoft.com-Domäne beizubehalten, und Sie können Benutzern zuweisen, sich mit einer der überprüften Domänen anzumelden. Die einem Benutzer zugewiesene Domäne ist die E-Mail-Adresse, die in gesendeten und empfangenen E-Mails angezeigt wird. 
  
Sie können bis zu 900 registrierte Internetdomänen hosten, die jeweils durch einen anderen Namespace dargestellt werden. 
  
In Organisationen, die einmaliges Anmelden verwenden, müssen alle Benutzer in einer Domäne dasselbe Identitätssystem verwenden: Cloudidentität oder Verbundidentität. Sie können beispielsweise eine Gruppe von Benutzern haben, die nur eine Cloud-Identität benötigt, da Sie nicht auf lokale Systeme zugreifen, und eine andere Gruppe von Benutzern, die Microsoft und lokale Systeme verwenden. Sie würden Office 365 zwei Domänen hinzufügen, wie Contractors.contoso.com und staff.contoso.com, und nur SSO für eine davon einrichten. Eine ganze Domäne kann von Cloudidentität in Verbundidentität und von Verbundidentität in Cloudidentität konvertiert werden.
  
Weitere Informationen zu Domänen in Office 365 finden Sie unter [Domänen](domains.md). 
  
\* Bei Verwendung von Office 365 betrieben von 21Vianet in China lautet die Standarddomäne \<Name des Unternehmens\> **.onmsChina.cn**. Wenn Sie Office 365 Deutschland verwenden, lautet die Standarddomäne \<Name des Unternehmens\> **.onmicrosoft.de**.
  
## <a name="authentication"></a>Authentifizierung

Mit Ausnahme von Internetwebsites für anonymen Zugriff, die mit SharePoint Online erstellt wurden, müssen Benutzer beim Zugriff auf Microsoft-Dienste authentifiziert werden. 
  
- **Moderne Authentifizierung** Die moderne Authentifizierung ermöglicht eine auf der Active Directory-Authentifizierungsbibliothek (ADAL) basierende Anmeldung bei Office-Client-Apps über Plattformen hinweg. Dadurch werden Anmeldefeatures wie Multi-Factor Authentication (MFA, mehrstufige Authentifizierung), SAML-basierte Drittanbieter-Identitätsanbieter mit Office-Clientanwendungen sowie eine Smartcard- und zertifikatbasierte Authentifizierung ermöglicht. Außerdem muss Microsoft Outlook nicht mehr das grundlegende Authentifizierungsprotokoll verwenden. Weitere Informationen, einschließlich der Verfügbarkeit moderner Authentifizierung in Office-Anwendungen, finden Sie unter [Funktionsweise der modernen Authentifizierung für Office 2013-und Office 2016-Client-apps](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016).
    
    Die moderne Authentifizierung ist für Exchange Online standardmäßig aktiviert. Informationen zum Aktivieren oder Deaktivieren dieser Funktion finden Sie unter [Aktivieren der modernen Authentifizierung in Exchange Online](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Authentifizierung der Cloudidentität** Benutzer mit Cloudidentitäten werden mit herkömmlichen Methoden für Herausforderung/Rückmeldung authentifiziert. Der Webbrowser wird an den Microsoft-Anmeldedienst umgeleitet, in dem Sie den Benutzernamen und das Kennwort für Ihr geschäftliches oder Schulkonto eingeben. Der Anmeldedienst authentifiziert Ihre Anmeldeinformationen und generiert ein Diensttoken, das der Webbrowser dem angeforderten Dienst bereitstellt, und Sie werden angemeldet. 
    
- **Identitätsverbund Authentifizierung** Benutzer mit Verbundidentitäten werden mit Active Directory-Verbunddienste (AD FS) 2.0 oder anderen Sicherheitstokendienst authentifiziert. Der Webbrowser wird an den Microsoft-Anmeldedienst umgeleitet, in dem Sie Ihre Unternehmens-ID in das Formular als Benutzerprinzipalname (UPN) eingeben (beispielsweise Isabel@contoso.com). Der Anmeldedienst ermittelt, dass Sie Teil einer Verbunddomäne sind, und bietet an, Sie zur Authentifizierung an den lokalen Verbundserver weiterzuleiten. Wenn Sie am Desktop (Domäne Joined) angemeldet sind, werden Sie authentifiziert (mit Kerberos oder NTLMv2), und der lokale Sicherheitstokendienst generiert ein Anmelde Token, das der Webbrowser an den Microsoft-Anmeldedienst sendet. Der Anmeldedienst generiert mithilfe des Anmeldetokens ein Diensttoken, das vom Webbrowser an den angeforderten Dienst weitergeleitet wird, und meldet Sie an. Eine Liste der verfügbaren Sicherheits Token-Dienste finden Sie unter [Single Sign-on Roadmap](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Microsoft verwendet die formularbasierte Authentifizierung, und der Authentifizierungsdatenverkehr über das Netzwerk wird immer mit TLS/SSL mit Port 443 verschlüsselt. Der Authentifizierungsdatenverkehr verwendet einen vernachlässigbaren Prozentsatz an Bandbreite für Microsoft-Dienste. 
  
### <a name="multi-factor-authentication-for-office-365"></a>Mehrstufige Authentifizierung für Office 365

Bei der mehrstufigen Authentifizierung für Office 365 müssen Benutzer nach der korrekten Eingabe Ihres Kennworts einen Telefonanruf, eine Textnachricht oder eine APP-Benachrichtigung auf dem Smartphone bestätigen. Erst nach dieser zweiten Authentifizierung kann sich der Benutzer anmelden. Microsoft-Administratoren können Benutzer für die mehrstufige Authentifizierung im Microsoft 365 Admin Center registrieren. Erfahren Sie mehr über die mehrstufige [Authentifizierung für Office 365](https://docs.microsoft.com/office365/admin/security-and-compliance/set-up-multi-factor-authentication).
  
### <a name="rich-client-authentication"></a>Rich-Client-Authentifizierung

Rich-Clients wie Microsoft Office-Desktopanwendungen können auf zwei Arten authentifiziert werden:
  
- **Microsoft Online Services-Anmeldeassistent** Der Sign-in-Assistent, der von Desktop Setup installiert wird, enthält einen Client Dienst, der ein Diensttoken aus dem Anmeldedienst abruft und es an den Rich-Client zurückgibt. 
    
  - Wenn Sie über eine Cloud-Identität verfügen, erhalten Sie eine Aufforderung zur Eingabe von Anmeldeinformationen, die der Client Dienst zur Authentifizierung (mithilfe von WS-Trust) an den Anmeldedienst sendet.
    
  - Wenn Sie über eine Verbundidentität verfügen, kontaktiert der Client Dienst zuerst den AD FS 2.0-Server, um die Anmeldeinformationen zu authentifizieren (mit Kerberos oder NTLMv2) und ein Anmeldetoken abzurufen, das an den Anmeldedienst gesendet wird (mithilfe von WS-Federation und WS-Trust).
    
- **Einfache/Proxyauthentifizierung über SSL** Der Outlook-Client übergibt einfache Anmeldeinformationen für die Authentifizierung über SSL an Exchange Online. Exchange Online Proxys die Authentifizierungsanforderung an die Identitäts Plattform und anschließend an den lokalen Active Directory Verbund Server (für SSO). 
    
Um eine ordnungsgemäße Ermittlung und Authentifizierung für Microsoft-Dienste sicherzustellen, müssen Administratoren eine Reihe von Komponenten und Updates auf jeder Arbeitsstation anwenden, die Rich-Clients (wie Microsoft Office 2010) verwendet und eine Verbindung mit Office 365 herstellt. Desktop Setup ist ein automatisches Tool zum Konfigurieren von Arbeitsstationen mit den erforderlichen Updates. Weitere Informationen finden Sie unter [Use My Current Office Desktop Apps](https://support.office.com/article/set-up-office-2010-desktop-programs-to-work-with-office-365-for-business-3324b8b8-dceb-45e2-ac24-c642720108f7?ocmsassetID=HA102817827&CorrelationId=8eb1b198-827a-4999-a584-05a05a92d224&ui=en-US&rs=en-US&ad=US).
  
### <a name="sign-in-experience"></a>Anmeldung

Die Anmelde Erfahrung ändert sich abhängig vom verwendeten Identitätstyp:
  
||**Cloudidentität**|**Verbundidentität**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Outlook 2010 oder Office 2007 auf Windows 7  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Outlook 2010 oder Office Outlook 2007 auf Windows Vista  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|POP, IMAP, Outlook für Mac  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Weberlebnisse: Microsoft 365 Admin Center/Outlook im Internet/SharePoint Online/Office für das Internet  <br/> |Jede Browsersitzung anmelden <sup>4</sup> <br/> |Jede Sitzung anmelden <sup>3</sup> <br/> |
|Office 2010 oder Office 2007 mit SharePoint Online  <br/> |Jede SharePoint Online-Sitzung anmelden <sup>4</sup> <br/> |Jede SharePoint Online-Sitzung anmelden <sup>3</sup> <br/> |
|Skype for Business Online  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Keine Aufforderung  <br/> |
|Outlook für Mac  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Wenn Sie zum ersten Mal aufgefordert werden, können Sie Ihr Kennwort für die spätere Verwendung speichern. Sie erhalten keine weitere Aufforderung, bis Sie das Kennwort ändern. <br/> 
<sup>2</sup> geben Sie Ihre Unternehmensanmeldeinformationen ein. Sie können Ihr Kennwort speichern und werden nicht wieder aufgefordert, bis Sie Ihr Kennwort ändern. <br/> 
<sup>3</sup> für alle apps müssen Sie Ihren Benutzernamen eingeben oder auswählen, um sich anzumelden. Sie werden nicht zur Kennworteingabe aufgefordert, wenn Ihr Computer der Domäne hinzugefügt wurde. Wenn Sie die Option **angemeldet lassen** auswählen, werden Sie erst wieder aufgefordert, nachdem Sie sich abgemeldet haben. <br/> 
<sup>4</sup> Wenn Sie die Option **angemeldet lassen** auswählen, werden Sie erst wieder aufgefordert, wenn Sie sich abmelden. 
  
## <a name="creating-user-accounts"></a>Erstellen von Benutzerkonten

Es gibt mehrere Methoden zum Hinzufügen von Benutzern zu Office 365. Weitere Informationen finden Sie unter [Hinzufügen von Benutzern einzeln oder in der Hilfe zum Massen Administrator](https://docs.microsoft.com/office365/admin/add-users/add-users) sowie [hinzufügen, entfernen und Verwalten von Benutzern in der Microsoft 365 Admin Center-Vorschau](https://support.office.com/article/add-remove-and-manage-users-in-the-new-office-365-admin-center-6e80db58-c36b-4add-b1c8-cc5135f111f3?amp%3Bclcid=0x409&ui=en-US&rs=en-US&ad=US). Wenn Sie Office 365 im Betrieb durch 21Vianet in China verwenden, finden Sie Informationen unter [Erstellen oder Bearbeiten von Benutzerkonten in Office 365 betrieben von 21Vianet - Admininstratorhilfe](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="deleting-accounts"></a>Löschen von Konten

Wie Sie Konten löschen, hängt davon ab, ob Sie die Verzeichnissynchronisierung nutzen: 
  
- Wenn Sie die Verzeichnissynchronisierung nicht verwenden, können Konten mithilfe der Administratorseite oder mithilfe von Windows PowerShell gelöscht werden.
    
- Wenn Sie die Verzeichnissynchronisierung nutzen, müssen Sie Benutzer aus der lokalen Active Directory-Instanz und nicht aus Office 365 löschen.
    
Wenn ein Konto gelöscht wird, wird es inaktiv. Sie können das Konto für etwa 30 Tage nach dem Löschen wiederherstellen. Weitere Informationen zum Löschen und Wiederherstellen von Konten finden Sie unter [Löschen von Benutzern in Office 365](https://docs.microsoft.com/office365/admin/add-users/delete-a-user) und [Wiederherstellen von Benutzern in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user) oder, wenn Sie Office 365 betrieben von 21Vianet in China verwenden, finden Sie unter [erstellen oder Bearbeiten von Benutzerkonten in Office 365 betrieben von 21Vianet-admin Help](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="password-management"></a>Kennwortverwaltung

Die Richtlinien und Verfahren für die Kennwortverwaltung hängen vom Identitätssystem ab.
  
 **Kennwortverwaltung bei Cloudidentitäten:**
  
Bei der Verwendung von Cloudidentitäten werden Kennwörter automatisch generiert, wenn das Konto erstellt wird.
  
- Die Anforderungen für sichere Kennwörter bei Cloudidentitäten finden Sie unter [Kennwortrichtlinie](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- Um die Sicherheit zu verbessern, müssen Benutzer ihre Kennwörter ändern, wenn Sie zum ersten Mal auf Microsoft-Dienste zugreifen. Daher müssen Sie sich beim Microsoft 365 Admin Center anmelden, damit Sie aufgefordert werden, ihre Kennwörter zu ändern, bevor Benutzer auf Microsoft-Dienste zugreifen können.
    
- Administratoren können die Kennwortablaufrichtlinie festlegen. Weitere Informationen finden Sie unter [Festlegen der Ablaufrichtlinie für ein Benutzerkennwort](https://docs.microsoft.com/office365/admin/manage/set-password-expiration-policy).
    
Es gibt mehrere Tools zum Zurücksetzen von Kennwörtern für Benutzer mit Cloudidentitäten:
  
- **Administratorkennwort zurück** setzen Wenn Benutzer ihre Kennwörter verlieren oder vergessen, können Administratoren die Kennwörter von Benutzern im Admin Center oder mithilfe von Windows PowerShell zurücksetzen. Benutzer können ihr eigenes Kennwort nur ändern, wenn sie ihr bestehendes Kennwort kennen. 
    
    Wenn Administratoren für Enterprise-Pläne ihre Kennwörter verlieren oder vergessen, kann ein anderer Administrator mit der globalen Administratorrolle die Kennwörter von Administratoren im Microsoft 365 Admin Center oder mithilfe von Windows PowerShell zurücksetzen. Weitere Informationen finden Sie im Artikel zum Thema [Zurücksetzen von Administratorkennwörtern](https://docs.microsoft.com/office365/admin/add-users/reset-passwords). Wenn Sie Office 365 über 21Vianet in China verwenden, lesen Sie [Change or reset your password in Office 365 operated by 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Benutzer ändert Kennwörter mit Outlook im Internet** Die Seite Outlook auf der Weboptionen enthält einen Hyperlink Kennwort ändern, mit dem Benutzer zur Seite **Kennwort ändern** umgeleitet werden. Der Benutzer muss das bisherige Kennwort kennen. Weitere Informationen finden Sie im Artikel zum Thema [Ändern des Kennworts](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Wenn Sie Office 365 über 21Vianet in China verwenden, lesen Sie [Change or reset your password in Office 365 operated by 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Rollenbasierte kennwortrechte für das Zurücksetzen** Für Enterprise-Pläne können autorisierten Benutzern wie Helpdesk-Mitarbeitern das Benutzerrecht " **Kennwort zurücksetzen** " und das Recht zum Ändern von Kennwörtern mithilfe vordefinierter oder benutzerdefinierter Rollen zugewiesen werden, ohne dass Sie vollständige Dienstadministratoren werden. Für Enterprise-Pläne ist standardmäßig vorgesehen, dass Administratoren mit der Rolle "Globaler Administrator", "Kennwortadministrator" oder "Benutzerverwaltungsadministrator" Kennwörter ändern können. Weitere Informationen finden Sie unter [Zuweisen von Adminrollen](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
    
- **Zurücksetzen von Kennwörtern mit Windows PowerShell** Dienstadministratoren können mit Windows PowerShell Kennwörter zurücksetzen. 
    
 **Kennwortverwaltung bei Verbundidentitäten:**
  
Bei der Verwendung von Verbundidentitäten werden Kennwörter in Active Directory verwaltet. Der lokale Sicherheitstokendienst verhandelt die Authentifizierung mit dem Verbund Gateway, ohne die lokalen Active Directory Kennwörter der Benutzer über das Internet an Office 365 zu übergeben. Lokale Kennwortrichtlinien werden verwendet, oder für Webclients zweistufige Identifikation. Outlook im Internet enthält keinen Link zum Ändern eines Kennworts. Benutzer ändern ihre Kennwörter mit standardmäßigen, lokalen Tools oder mit Ihren Desktop-PC-Anmeldeoptionen.
  
Wenn Sie die [Verzeichnissynchronisierung mit einmaligem Anmelden (SSO)](https://docs.microsoft.com/previous-versions/azure/azure-services/dn441213(v=azure.100)) in Ihrer Organisationsumgebung aktiviert haben und ein Ausfall auftritt, der sich auf Ihren Partner Identitätsanbieter auswirkt, bietet die Kenn Wort Synchronisierungs Sicherung für die Verbundanmeldung die Möglichkeit, Ihre Domäne manuell zur Kennwortsynchronisierung zu wechseln. Durch die Verwendung der Kennwortsynchronisierung können Ihre Benutzer zugreifen, während der Ausfall behoben ist. Hier erfahren Sie, [wie Sie von der einmaligen Anmeldung zur Kennwortsynchronisierung wechseln](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Lizenzverwaltung

Eine Lizenz ermöglicht einem Benutzer den Zugriff auf eine Reihe von Microsoft-Diensten. Ein Administrator weist jedem Benutzer für jeden Dienst, auf den er zugreifen muss, eine Lizenz zu. Sie können beispielsweise einem Benutzer den Zugriff auf Skype for Business Online, aber nicht auf SharePoint Online gewähren.
  
Microsoft-Abrechnungs Administratoren können Änderungen an den Abonnementdetails vornehmen, beispielsweise die Anzahl der Benutzerlizenzen und die Anzahl der zusätzlichen Dienste, die Ihr Unternehmen verwendet. Auschecken [zuweisen oder Entfernen einer Lizenz](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Wenn Sie Office 365 über 21Vianet verwenden, lesen Sie [Assign or remove licenses in Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Gruppenverwaltung

Sicherheitsgruppen werden in SharePoint Online zum Steuern des Zugriffs auf Websites verwendet. Sicherheitsgruppen können im Microsoft 365 Admin Center erstellt werden. Weitere Informationen zu Sicherheitsgruppen finden Sie unter [Erstellen, Bearbeiten oder Entfernen einer Sicherheitsgruppe](https://docs.microsoft.com/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Administratorrollen

Office 365 Enterprise nutzt ein Modell der rollenbasierten Zugriffssteuerung (Role Based Access Control, RBAC): Berechtigungen und Funktionen werden durch Verwaltungsrollen definiert. Die Person, die sich für ihre Organisation für Office 365 registriert, wird automatisch globaler Administrator (oder Hauptadministrator). Es gibt fünf Administratorrollen: globaler Administrator, Rechnungsadministrator, Kennwortadministrator, Dienstadministrator und Benutzerverwaltungsadministrator. Weitere Informationen zu den Administratorrollen in Office 365 Enterprise sowie dazu, inwiefern diese für die Verwaltung von Exchange Online, SharePoint Online und Skype for Business Online gelten, finden Sie im Artikel zum Thema [Zuweisen von Administratorrollen](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). Wenn Sie Office 365 über 21Vianet in China verwenden, lesen Sie [Zuweisen von Administratorrollen in Office 365 Business](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
  
## <a name="delegated-administration-and-support-for-partners"></a>Delegierte Verwaltung und Unterstützung für Partner

Partner können zum Verwalten von Konten im Namen von Kunden autorisiert werden. Der Kunde benötigt kein Benutzerkonto für die Partner, und es wird keine Lizenz verwendet, wenn Delegierte Verwaltungsautorität erteilt wird. Partner können Benutzern in ihrer Organisation vollständigen oder eingeschränkten Zugriff zuweisen. Zum eingeschränkten Zugriff gehören Rechte wie das Zurücksetzen von Kennwörtern, das Verwalten von Serviceanfragen und das Überwachen des Dienstzustands. 
  
> [!NOTE]
> Die Möglichkeit zum Verwenden und Angeben eines Partners als delegierter Administrator kann je nach Region variieren. 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory-Dienste

Azure Active Directory (AD) bietet umfassende Identitäts- und Zugriffsverwaltungsfunktionen für Office 365. Es kombiniert Verzeichnisdienste, erweiterte Identity Governance, Anwendungszugriffsverwaltung und eine funktionsreiche standardbasierte Plattform für Entwickler. Weitere Informationen zu Active Directory-Features in Office 365 finden Sie in diesem Blogbeitrag zum Thema [Branding der Anmeldeseite und Self-Service-Kennwortzurücksetzung für Cloudbenutzer](https://www.microsoft.com/en-us/microsoft-365/blog/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/). Hier erfahren Sie mehr über die [Azure Active Directory-Editionen Free, Basic und Premium](https://msdn.microsoft.com/library/azure/dn532272.aspx). 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Office 365 Platform Service Description](office-365-platform-service-description.md).
  
