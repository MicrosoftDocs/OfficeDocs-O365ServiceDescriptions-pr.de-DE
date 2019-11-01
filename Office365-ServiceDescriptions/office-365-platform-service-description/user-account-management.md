---
title: Benutzerkontenverwaltung
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
description: Microsoft Office 365 unterstützt die folgenden Methoden zum Erstellen, verwalten und Authentifizieren von Benutzern.
ms.openlocfilehash: a43ecb83bface37e21cca7ca2aa877e878ef362b
ms.sourcegitcommit: 637906376f304e76a32ecf889394687cb6714493
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 10/31/2019
ms.locfileid: "37911791"
---
# <a name="user-account-management"></a>Benutzerkontenverwaltung

Microsoft Office 365 unterstützt die folgenden Methoden zum Erstellen, verwalten und Authentifizieren von Benutzern. 
  
> [!NOTE]
> Dieses Thema enthält keine Informationen über Sicherheitsfunktionen, die den Zugriff auf einzelne Office 365-Ressourcen zulassen oder verhindern (z. B. rollenbasierte Zugriffssteuerung in Microsoft Exchange Online oder Konfigurieren von Sicherheit in Microsoft SharePoint Online). Weitere Informationen zu diesen Funktionen finden Sie in der [Exchange Online-Dienstbeschreibung](../exchange-online-service-description/exchange-online-service-description.md) und der [SharePoint Online-Dienstbeschreibung](../sharepoint-online-service-description/sharepoint-online-service-description.md). 
  
Wenn Sie Informationen zu Tools benötigen, die Ihnen bei der Ausführung von Verwaltungsaufgaben helfen, gehen Sie zu [Tools zum Verwalten von Office 365-Konten](https://docs.microsoft.com/office365/enterprise/manage-office-365-accounts). Informationen zum Ausführen täglicher Verwaltungsaufgaben finden Sie unter [Allgemeine Verwaltungsaufgaben für Office 365](https://docs.microsoft.com/office365/admin/manage/manage).
  
## <a name="need-help-signing-in-installing-or-uninstalling-or-canceling-your-subscription"></a>Benötigen Sie Hilfe bei der Anmeldung, Installation, Deinstallation oder der Kündigung Ihres Abonnements?

Hier finden Sie Unterstützung: [Anmelden bei Office 365](https://support.office.com/article/where-to-sign-in-to-office-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4) | [Installieren oder Deinstallieren von Office](https://support.office.com/article/download-and-install-or-reinstall-office-365-or-office-2019-on-a-pc-or-mac-4414eaaf-0478-48be-9c42-23adc4716658) | [Kündigen von Office 365](https://support.office.com/article/Cancel-Office-365-for-business-b1bc0bef-4608-4601-813a-cdd9f746709a)
  
Bei sonstigen Problemen mit Office 365 finden Sie Hilfe im [Support-Center von Microsoft](https://support.microsoft.com/contactus/). Support für Office 365 betrieb von 21Vianet in China erhalten Sie vom [21Vianet-Supportteam](https://support.office.com/article/Get-technical-billing-and-subscription-support-for-Office-365-operated-by-21Vianet-671FB12E-F5D8-4CDF-B3E9-E8068A9AA496). Ansprechpartner für Office 365 Deutschland ist das [Office 365 Deutschland-Supportteam](https://support.office.com/article/Get-technical-and-billing-support-for-Office-365-Germany-83ef2266-2543-48d7-a41a-1b56b403a8e9?ui=en-US&amp;rs=en-US&amp;ad=US&amp;fromAR=1). 
  
## <a name="sign-in-options"></a>Anmeldeoptionen

Office 365 hat zwei Systeme für die Verwendung bei der Benutzeridentitäten:
  
- **Arbeits- oder Schulkonto (Cloudidentität)** Die Benutzer erhalten (zusätzlich zu Desktop- oder Unternehmensanmeldeinformationen) Azure Active Directory-Cloudanmeldeinformationen für die Anmeldung bei Office 365 und anderen Microsoft Cloud-Dienste. Dies ist die Standardidentität. Sie wird empfohlen, um die Komplexität der Bereitstellung zu minimieren. Für Kennwörter für Arbeits- oder Schulkonten wird die Azure Active Directory [-Kennwortrichtlinie](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)) verwendet.
    
- **Verbundkonto (Verbundidentität)** Bei allen Abonnements in Organisationen mit einem lokalen Active Directory, das Single Sign-On verwendet, können Benutzer sich bei Office 365-Diensten mit ihren Active Directory-Anmeldeinformationen anmelden. Das firmeneigene Active Directory speichert und steuert die Kennwortrichtlinie. Weitere Informationen über SSO finden Sie unter [Fahrplan für einmaliges Anmelden](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Die Art der Identität hat Auswirkungen auf die Benutzerfreundlichkeit, Verwaltungsoptionen für Benutzerkonten, Hardware- und Softwareanforderungen sowie weitere Bereitstellungsüberlegungen.
  
### <a name="custom-domains-and-identity-options"></a>Benutzerdefinierte Domänen und Identitätsoptionen

Wenn Sie einen neuen Benutzer erstellen, werden der Anmeldename und die e-Mail-Adresse des Benutzers der Standarddomäne zugewiesen, die im Microsoft 365 Admin Center festgelegt ist. Weitere Informationen finden Sie unter [Hinzufügen Ihrer Benutzer und Domänen zu Office 365](https://support.office.com/article/Add-your-users-and-domain-to-Office-365-6383f56d-3d09-4dcb-9b41-b5f5a5efd611). 
  
Standardmäßig wird für das Office 365-Abonnement die Domäne \< _company name_\> **.onmicrosoft.com** verwendet, die zusammen mit dem Konto erstellt wurde.\* Sie können Office 365 eine oder mehrere benutzerdefinierte Domänen hinzufügen, statt die Domäne „onmicrosoft.com" zu behalten, und Sie können Benutzer für die Anmeldung einer beliebigen der überprüften Domänen zuweisen. Die einem Benutzer zugewiesene Domäne ist die E-Mail-Adresse, die in gesendeten und empfangenen E-Mails angezeigt wird. 
  
Sie können bis zu 900 registrierte Internetdomänen in Office 365 hosten, die jeweils durch einen anderen Namespace dargestellt werden. 
  
In Organisationen, die einmaliges Anmelden verwenden, müssen alle Benutzer in einer Domäne dasselbe Identitätssystem verwenden: Cloudidentität oder Verbundidentität. Sie können beispielsweise eine Gruppe von Benutzern haben, die nur eine Cloud-Identität benötigt, da Sie nicht auf lokale Systeme zugreifen, und eine andere Gruppe von Benutzern, die Office 365 und lokale Systeme verwenden. Sie würden Office 365 zwei Domänen hinzufügen, wie Contractors.contoso.com und staff.contoso.com, und nur SSO für eine davon einrichten. Eine ganze Domäne kann von Cloudidentität in Verbundidentität und von Verbundidentität in Cloudidentität konvertiert werden.
  
Weitere Informationen zu Domänen in Office 365 finden Sie unter [Domänen](domains.md). 
  
\* Bei Verwendung von Office 365 betrieben von 21Vianet in China lautet die Standarddomäne \<Name des Unternehmens\> **.onmsChina.cn**. Wenn Sie Office 365 Deutschland verwenden, lautet die Standarddomäne \<Name des Unternehmens\> **.onmicrosoft.de**.
  
## <a name="authentication"></a>Authentifizierung

Mit der Ausnahme von Websites für anonymen Zugriff, die mit SharePoint Online erstellt wurden, müssen Benutzer authentifiziert werden, wenn sie auf Office 365-Dienste zugreifen. 
  
- **Moderne Authentifizierung** Die moderne Authentifizierung ermöglicht eine auf der Active Directory-Authentifizierungsbibliothek (ADAL) basierende Anmeldung bei Office-Client-Apps über Plattformen hinweg. Dadurch werden Anmeldefeatures wie Multi-Factor Authentication (MFA, mehrstufige Authentifizierung), SAML-basierte Drittanbieter-Identitätsanbieter mit Office-Clientanwendungen sowie eine Smartcard- und zertifikatbasierte Authentifizierung ermöglicht. Außerdem muss Microsoft Outlook nicht mehr das grundlegende Authentifizierungsprotokoll verwenden. Weitere Informationen, einschließlich der Verfügbarkeit moderner Authentifizierung in Office-Anwendungen, finden Sie unter [Funktionsweise der modernen Authentifizierung für Office 2013-und Office 2016-Client-apps](https://docs.microsoft.com/office365/enterprise/modern-auth-for-office-2013-and-2016).
    
    Die moderne Authentifizierung ist für Exchange Online standardmäßig aktiviert. Informationen zum Aktivieren oder Deaktivieren dieser Funktion finden Sie unter [Aktivieren der modernen Authentifizierung in Exchange Online](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/enable-or-disable-modern-authentication-in-exchange-online).
    
- **Authentifizierung der Cloudidentität** Benutzer mit Cloudidentitäten werden mit herkömmlichen Methoden für Herausforderung/Rückmeldung authentifiziert. Der Webbrowser wird an den Office 365-Anmeldedienst weitergeleitet, bei dem Sie den Benutzernamen und das Kennwort für Ihr Arbeits- oder Schulkonto angeben. Der Anmeldedienst authentifiziert Ihre Anmeldeinformationen und generiert ein Diensttoken, das der Webbrowser dem angeforderten Dienst bereitstellt, und Sie werden angemeldet. 
    
- **Authentifizierung der Verbundidentität** Benutzer mit Verbundidentitäten werden mit Active Directory-Verbunddienste (AD FS) 2.0 oder anderen Sicherheitstokendiensten authentifiziert. Der Webbrowser wird an den Office 365-Anmeldedienst weitergeleitet, bei dem Sie Ihre Unternehmens-ID als Benutzerprinzipalnamen (UPN, User Principal Name, z. B. isabel@contoso.com) eingeben. Der Anmeldedienst ermittelt, dass Sie Teil einer Verbunddomäne sind, und bietet an, Sie zur Authentifizierung an den lokalen Verbundserver weiterzuleiten. Wenn Sie am Desktop angemeldet sind (Domänenbeitritt), werden Sie authentifiziert (mit Kerberos oder NTLMv2), und der lokale Sicherheitstokendienst generiert ein Anmeldetoken, das der Webbrowser dem Office 365-Anmeldedienst bereitstellt. Der Anmeldedienst generiert mithilfe des Anmeldetokens ein Diensttoken, das vom Webbrowser an den angeforderten Dienst weitergeleitet wird, und meldet Sie an. Eine Liste verfügbarer Sicherheitstokendienste finden Sie unter [Fahrplan für einmaliges Anmelden](https://docs.microsoft.com/previous-versions/azure/azure-services/hh967643(v=azure.100)).
    
Office 365 verwendet die formularbasierte Authentifizierung, und der Authentifizierungsdatenverkehr über das Netzwerk wird immer an Port 443 mit TLS/SSL verschlüsselt. Der Authentifizierungsdatenverkehr beansprucht einen zu vernachlässigenden prozentualen Anteil der Bandbreite für Office 365-Dienste. 
  
### <a name="multi-factor-authentication-for-office-365"></a>Mehrstufige Authentifizierung für Office 365

Bei der mehrstufigen Authentifizierung für Office 365 müssen Benutzer nach der korrekten Eingabe Ihres Kennworts einen Telefonanruf, eine Textnachricht oder eine APP-Benachrichtigung auf dem Smartphone bestätigen. Erst nach dieser zweiten Authentifizierung kann sich der Benutzer anmelden. Office 365 Administratoren können Benutzer für die mehrstufige Authentifizierung im Microsoft 365 Admin Center registrieren. Erfahren Sie mehr über die mehrstufige [Authentifizierung für Office 365](https://docs.microsoft.com/office365/admin/security-and-compliance/set-up-multi-factor-authentication).
  
### <a name="rich-client-authentication"></a>Rich-Client-Authentifizierung

Rich-Clients wie Microsoft Office-Desktopanwendungen können auf zwei Arten authentifiziert werden:
  
- **Microsoft Online Services-Anmeldeassistent** Der Anmeldeassistent, der beim Office 365-Desktopsetup installiert wird, enthält einen Clientdienst, der ein Diensttoken vom Office 365-Anmeldedienst abruft und an den Rich-Client zurückgibt. 
    
  - Wenn Sie über eine Cloudidentität verfügen, werden Sie zur Angabe der Anmeldeinformationen aufgefordert. Diese werden vom Clientdienst zur Authentifizierung an den Office 365-Anmeldedienst gesendet (mit WS-Trust).
    
  - Wenn Sie über eine Verbundidentität verfügen, kontaktiert der Clientdienst zuerst den AD FS 2.0-Server, um die Anmeldeinformationen zu authentifizieren (mit Kerberos oder NTLMv2) und ein Anmeldetoken abzurufen, das an den Office 365-Anmeldedienst gesendet wird (mit WS-Verbund und WS-Trust).
    
- **Einfache/Proxyauthentifizierung über SSL** Der Outlook-Client übergibt einfache Anmeldeinformationen für die Authentifizierung über SSL an Exchange Online. Exchange Online leitet die Authentifizierungsanforderung über einen Proxy an die Office 365-Identitätsplattform und dann an den lokalen Active Directory-Verbundserver weiter (für SSO). 
    
Um eine ordnungsgemäße Erkennung und Authentifizierung von Office 365-Diensten sicherzustellen, müssen Administratoren auf jede Arbeitsstation, die Rich-Clients (wie Microsoft Office 2010) verwendet und eine Verbindung mit Office 365 herstellt, eine Reihe von Komponenten und Updates anwenden. Office 365-Desktopsetup ist ein automatisiertes Tool zum Konfigurieren von Arbeitsstationen mit den erforderlichen Updates. Weitere Informationen finden Sie im Artikel zum Thema [Verwenden installierter Office-Desktop-Apps mit Office 365](https://support.office.com/article/set-up-office-2010-desktop-programs-to-work-with-office-365-for-business-3324b8b8-dceb-45e2-ac24-c642720108f7?ocmsassetID=HA102817827&CorrelationId=8eb1b198-827a-4999-a584-05a05a92d224&ui=en-US&rs=en-US&ad=US).
  
### <a name="sign-in-experience"></a>Anmeldung

Die Anmeldung hängt von der verwendeten Office 365-Identität ab:
  
||**Cloudidentität**|**Verbundidentität**|
|:-----|:-----|:-----|
|Outlook 2016  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Outlook 2013  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Outlook 2010 oder Office 2007 auf Windows 7  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Outlook 2010 oder Office Outlook 2007 auf Windows Vista  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Microsoft Exchange ActiveSync  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|POP, IMAP, Outlook für Mac  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
|Weberlebnisse: Office 365-Portal/Outlook im Internet/SharePoint Online/Office für das Internet  <br/> |Jede Browsersitzung anmelden <sup>4</sup> <br/> |Jede Sitzung anmelden <sup>3</sup> <br/> |
|Office 2010 oder Office 2007 mit SharePoint Online  <br/> |Jede SharePoint Online-Sitzung anmelden <sup>4</sup> <br/> |Jede SharePoint Online-Sitzung anmelden <sup>3</sup> <br/> |
|Skype for Business Online  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Keine Aufforderung  <br/> |
|Outlook für Mac  <br/> |Jede Sitzung anmelden <sup>1</sup> <br/> |Jede Sitzung anmelden <sup>2</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> Wenn Sie zum ersten Mal aufgefordert werden, können Sie Ihr Kennwort für die spätere Verwendung speichern. Sie erhalten keine weitere Aufforderung, bis Sie das Kennwort ändern. <br/> 
<sup>2</sup> geben Sie Ihre Unternehmensanmeldeinformationen ein. Sie können Ihr Kennwort speichern und werden nicht wieder aufgefordert, bis Sie Ihr Kennwort ändern. <br/> 
<sup>3</sup> für alle apps müssen Sie Ihren Benutzernamen eingeben oder auswählen, um sich anzumelden. Sie werden nicht zur Kennworteingabe aufgefordert, wenn Ihr Computer der Domäne hinzugefügt wurde. Wenn Sie die Option **angemeldet lassen** auswählen, werden Sie erst wieder aufgefordert, nachdem Sie sich abgemeldet haben. <br/> 
<sup>4</sup> Wenn Sie die Option **angemeldet lassen** auswählen, werden Sie erst wieder aufgefordert, wenn Sie sich abmelden. 
  
## <a name="creating-user-accounts"></a>Erstellen von Benutzerkonten

Es gibt mehrere Methoden zum Hinzufügen von Benutzern zu Office 365. Weitere Informationen finden Sie unter [Hinzufügen von Benutzern einzeln oder in loser Schüttung zu Office 365-Admin-Hilfe](https://docs.microsoft.com/office365/admin/add-users/add-users) und [hinzufügen, entfernen und Verwalten von Benutzern in der Microsoft 365 Admin Center-Vorschau](https://support.office.com/article/add-remove-and-manage-users-in-the-new-office-365-admin-center-6e80db58-c36b-4add-b1c8-cc5135f111f3?amp%3Bclcid=0x409&ui=en-US&rs=en-US&ad=US). Wenn Sie Office 365 im Betrieb durch 21Vianet in China verwenden, finden Sie Informationen unter [Erstellen oder Bearbeiten von Benutzerkonten in Office 365 betrieben von 21Vianet - Admininstratorhilfe](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="deleting-accounts"></a>Löschen von Konten

Wie Sie Konten löschen, hängt davon ab, ob Sie die Verzeichnissynchronisierung nutzen: 
  
- Wenn Sie die Verzeichnissynchronisierung nicht nutzen, können Konten mit der Office 365-Verwaltungsseite oder mit Windows PowerShell gelöscht werden.
    
- Wenn Sie die Verzeichnissynchronisierung nutzen, müssen Sie Benutzer aus der lokalen Active Directory-Instanz und nicht aus Office 365 löschen.
    
Wenn ein Konto gelöscht wird, wird es inaktiv. Sie können das Konto für etwa 30 Tage nach dem Löschen wiederherstellen. Weitere Informationen zum Löschen und Wiederherstellen von Konten finden Sie unter [Löschen von Benutzern in Office 365](https://docs.microsoft.com/office365/admin/add-users/delete-a-user) und [Wiederherstellen von Benutzern in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user) oder, wenn Sie Office 365 betrieben von 21Vianet in China verwenden, finden Sie unter [erstellen oder Bearbeiten von Benutzerkonten in Office 365 betrieben von 21Vianet-Administratorhilfe](https://docs.microsoft.com/office365/admin/add-users/add-users).
  
## <a name="password-management"></a>Kennwortverwaltung

Die Richtlinien und Verfahren für die Kennwortverwaltung hängen vom Identitätssystem ab.
  
 **Kennwortverwaltung bei Cloudidentitäten:**
  
Bei der Verwendung von Cloudidentitäten werden Kennwörter automatisch generiert, wenn das Konto erstellt wird.
  
- Die Anforderungen für sichere Kennwörter bei Cloudidentitäten finden Sie unter [Kennwortrichtlinie](https://docs.microsoft.com/previous-versions/azure/jj943764(v=azure.100)).
    
- Zur Verbesserung der Sicherheit müssen Benutzer ihre Kennwörter beim ersten Zugriff auf Office 365-Dienste ändern. Bevor Benutzer also auf Office 365-Dienste zugreifen können, müssen sie sich beim Office 365-Portal anmelden, wo sie zum Ändern der Kennwörter aufgefordert werden.
    
- Administratoren können die Kennwortablaufrichtlinie festlegen. Weitere Informationen finden Sie unter [Festlegen der Ablaufrichtlinie für ein Benutzerkennwort](https://docs.microsoft.com/office365/admin/manage/set-password-expiration-policy).
    
Es gibt mehrere Tools zum Zurücksetzen von Kennwörtern für Benutzer mit Cloudidentitäten:
  
- **Kennwort wird vom Administrator zurückgesetzt** Wenn Benutzer ihre Kennwörter verlieren oder vergessen, können Administratoren die Kennwörter von Benutzern im Office 365-Portal oder mit Windows PowerShell zurücksetzen. Benutzer können ihr eigenes Kennwort nur ändern, wenn sie ihr bestehendes Kennwort kennen. 
    
    Wenn Administratoren für Enterprise-Pläne ihre Kennwörter verlieren oder vergessen, kann ein anderer Administrator mit der globalen Administratorrolle die Kennwörter von Administratoren im Microsoft 365 Admin Center oder mithilfe von Windows PowerShell zurücksetzen. Weitere Informationen finden Sie im Artikel zum Thema [Zurücksetzen von Administratorkennwörtern](https://docs.microsoft.com/office365/admin/add-users/reset-passwords). Wenn Sie Office 365 über 21Vianet in China verwenden, lesen Sie [Change or reset your password in Office 365 operated by 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Benutzer ändert Kennwörter mit Outlook im Internet** Die Seite Outlook auf der Weboptionen enthält einen Hyperlink Kennwort ändern, mit dem Benutzer zur Seite **Kennwort ändern** umgeleitet werden. Der Benutzer muss das bisherige Kennwort kennen. Weitere Informationen finden Sie im Artikel zum Thema [Ändern des Kennworts](https://support.office.com/article/change-password-in-outlook-web-app-50bb1309-6f53-4c24-8bfd-ed24ca9e872c). Wenn Sie Office 365 über 21Vianet in China verwenden, lesen Sie [Change or reset your password in Office 365 operated by 21Vianet](https://support.office.com/article/change-or-reset-your-password-in-office-365-operated-by-21vianet-d8eb5b62-9d0e-4267-a9bf-2aa491ee6d0b).
    
- **Rollenbasierte Rechte zum Zurücksetzen von Kennwörtern** Bei Enterprise-Plänen kann autorisierten Benutzern wie Helpdeskmitarbeitern das Benutzerrecht **Kennwort zurücksetzen** und das Recht zum Ändern von Kennwörtern über die vordefinierten oder benutzerdefinierten Office 365-Rollen zugewiesen werden, ohne dass sie dadurch zu vollständigen Dienstadministratoren werden. Für Enterprise-Pläne ist standardmäßig vorgesehen, dass Administratoren mit der Rolle "Globaler Administrator", "Kennwortadministrator" oder "Benutzerverwaltungsadministrator" Kennwörter ändern können. Weitere Informationen finden Sie unter [Zuweisen von Adminrollen](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
    
- **Zurücksetzen von Kennwörtern mit Windows PowerShell** Dienstadministratoren können mit Windows PowerShell Kennwörter zurücksetzen. 
    
 **Kennwortverwaltung bei Verbundidentitäten:**
  
Bei der Verwendung von Verbundidentitäten werden Kennwörter in Active Directory verwaltet. Der lokale Sicherheitstokendienst verhandelt die Authentifizierung mit Office 365 Verbund Gateway, ohne die lokalen Active Directory-Kennwörter der Benutzer über das Internet an Office 365 zu übergeben. Lokale Kennwortrichtlinien werden verwendet, oder für Webclients zweistufige Identifikation. Outlook im Internet enthält keinen Link zum Ändern eines Kennworts. Benutzer ändern ihre Kennwörter mit standardmäßigen, lokalen Tools oder mit Ihren Desktop-PC-Anmeldeoptionen.
  
Falls [Verzeichnissynchronisierung mit einmaligem Anmelden (SSO)](https://docs.microsoft.com/previous-versions/azure/azure-services/dn441213(v=azure.100)) in Ihrer Office 365-Umgebung aktiviert ist und es zu einem Ausfall kommt, der Ihren Partneridentitätsanbieter beeinträchtigt, bietet die Kennwortsynchronisierungssicherung für die Verbundanmeldung die Möglichkeit, Ihre Domäne manuell auf Kennwortsynchronisierung umzuschalten. Mit der Kennwortsynchronisierung können Ihre Benutzer auf Office 365 zugreifen, während der Ausfall behoben wird. Erfahren Sie, [wie Sie vom einmaligen Anmelden auf Kennwortsynchronisierung umschalten](https://go.microsoft.com/fwlink/p/?LinkId=509832).
  
## <a name="license-management"></a>Lizenzverwaltung

Eine Office 365-Lizenz ermöglicht einem Benutzer den Zugriff auf verschiedene Office 365-Dienste. Ein Administrator weist jedem Benutzer für jeden Dienst, auf den er zugreifen muss, eine Lizenz zu. Sie können beispielsweise einem Benutzer den Zugriff auf Skype for Business Online, aber nicht auf SharePoint Online gewähren.
  
Office 365-Rechnungsadministratoren können Änderungen an Abonnementdetails wie der Anzahl der Benutzerlizenzen oder der zusätzlichen Dienste vornehmen, die Ihr Unternehmen nutzt. Weitere Informationen finden Sie im Artikel zum Thema [Zuweisen oder Entfernen von Lizenzen in Office 365](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users). Wenn Sie Office 365 über 21Vianet verwenden, lesen Sie [Assign or remove licenses in Office 365 operated by 21Vianet](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users).
  
## <a name="group-management"></a>Gruppenverwaltung

Sicherheitsgruppen werden in SharePoint Online zum Steuern des Zugriffs auf Websites verwendet. Sicherheitsgruppen können im Microsoft 365 Admin Center erstellt werden. Weitere Informationen zu Sicherheitsgruppen finden Sie unter [Erstellen, Bearbeiten oder Entfernen einer Sicherheitsgruppe](https://docs.microsoft.com/office365/admin/email/create-edit-or-delete-a-security-group).
  
## <a name="administrator-roles"></a>Administratorrollen

Office 365 Enterprise nutzt ein Modell der rollenbasierten Zugriffssteuerung (Role Based Access Control, RBAC): Berechtigungen und Funktionen werden durch Verwaltungsrollen definiert. Die Person, die sich für ihre Organisation für Office 365 registriert, wird automatisch globaler Administrator (oder Hauptadministrator). Es gibt fünf Administratorrollen: globaler Administrator, Rechnungsadministrator, Kennwortadministrator, Dienstadministrator und Benutzerverwaltungsadministrator. Weitere Informationen zu den Administratorrollen in Office 365 Enterprise sowie dazu, inwiefern diese für die Verwaltung von Exchange Online, SharePoint Online und Skype for Business Online gelten, finden Sie im Artikel zum Thema [Zuweisen von Administratorrollen](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/jj878348(v=ws.11)). Wenn Sie Office 365 über 21Vianet in China verwenden, lesen Sie [Zuweisen von Administratorrollen in Office 365 Business](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles).
  
## <a name="delegated-administration-and-support-for-partners"></a>Delegierte Verwaltung und Unterstützung für Partner

Partner können zum Verwalten von Konten im Namen von Kunden autorisiert werden. Der Kunde benötigt kein Benutzerkonto für den Partner, und es wird auch keine Office 365-Lizenz genutzt, wenn delegierte Verwaltungsrechte gewährt werden. Partner können Benutzern in ihrer Organisation vollständigen oder eingeschränkten Zugriff zuweisen. Zum eingeschränkten Zugriff gehören Rechte wie das Zurücksetzen von Kennwörtern, das Verwalten von Serviceanfragen und das Überwachen des Dienstzustands. 
  
> [!NOTE]
> Die Möglichkeit zum Verwenden und Angeben eines Partners als delegierter Administrator kann je nach Region variieren. 
  
## <a name="azure-active-directory-services"></a>Azure Active Directory-Dienste

Azure Active Directory (AD) bietet umfassende Identitäts- und Zugriffsverwaltungsfunktionen für Office 365. Es kombiniert Verzeichnisdienste, erweiterte Identity Governance, Anwendungszugriffsverwaltung und eine funktionsreiche standardbasierte Plattform für Entwickler. Weitere Informationen zu Active Directory-Features in Office 365 finden Sie in diesem Blogbeitrag zum Thema [Branding der Anmeldeseite und Self-Service-Kennwortzurücksetzung für Cloudbenutzer](https://www.microsoft.com/en-us/microsoft-365/blog/2015/02/17/sign-page-branding-cloud-user-self-service-password-reset-office-365/). Hier erfahren Sie mehr über die [Azure Active Directory-Editionen Free, Basic und Premium](https://msdn.microsoft.com/library/azure/dn532272.aspx). 
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Office 365 Platform Service Description](office-365-platform-service-description.md).
  
