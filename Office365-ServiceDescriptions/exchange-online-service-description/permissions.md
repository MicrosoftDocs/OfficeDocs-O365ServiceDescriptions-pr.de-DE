---
title: Berechtigungen
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013.
ms.openlocfilehash: 0593c98857a7ce0c487c628018097395d7a5fe50
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132689"
---
# <a name="permissions"></a>Berechtigungen

Microsoft Exchange Online uses a Role Based Access Control (RBAC) model to allow organization administrators to finely control what users and IT employees can do in the service. For example, if a compliance officer is responsible for mailbox search requests, the administrator can delegate this administrative feature to the officer through RBAC. Exchange Online uses the same RBAC framework as Microsoft Exchange Server 2013. 
  
At its highest level, RBAC is made up of management roles, management role groups, and management role assignment policies. The following sections provide more information about each RBAC component.
  
Weitere Informationen zu dem in Exchange Online verwendeten RBAC-Berechtigungsmodell finden Sie unter [Berechtigungen](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Rollenbasierte Berechtigungen

In Exchange Online, the permissions that you grant to administrators and users are based on management roles. A role defines the set of tasks that an administrator or user can perform. For example, a management role called  `Mail Recipients` defines the tasks that someone can perform on a set of mailboxes, contacts, and distribution groups. When a role is assigned to an administrator or user, that person is granted the permissions provided by the role. 
  
Es gibt zwei Typen von Rollen, Administratorrollen und Endbenutzerrollen:
  
- **Administrative Rollen** Diese Rollen umfassen Berechtigungen, die Administratoren oder spezialisierten Benutzern mithilfe von Rollengruppen zur Verwaltung eines bestimmten Bereichs der Exchange Online-Organisation (z. B. Empfänger, Server oder Datenbanken) zugewiesen werden können. 
    
- **Endbenutzerrollen** Mit diesen Rollen, die mithilfe von Rollenzuweisungsrichtlinien zugewiesen werden, können Benutzer Aspekte ihrer eigenen Postfächer und Verteilergruppen verwalten. Endbenutzerrollen beginnen mit dem Präfix  `My`.
    
Roles give administrators and users permissions to perform tasks by making cmdlets available to those who are assigned the roles. Because the Exchange admin center (EAC) and Exchange Management Shell use cmdlets to manage Exchange Online, granting access to a cmdlet gives the administrator or user permission to perform the task in each of the Exchange Online management interfaces.
  
The role-based permissions for Microsoft Online Services overlap with those of Exchange Online RBAC in two ways. First, users who are Global Administrators or Service Administrators in Microsoft Online are automatically assigned to the Organization Management role group in Exchange Online. Second, users who are Help Desk Administrators in Microsoft Online are automatically assigned to the Help Desk role group in Exchange Online. Otherwise, the two security models are managed separately.
  
> [!IMPORTANT]
> Einige Rollen, die in der lokalen Version von Microsoft Exchange Server 2013 verfügbar sind, stehen in Exchange Online möglicherweise nicht zur Verfügung. 
  
Weitere Informationen zu Berechtigungen in Exchange Online finden Sie unter [Rollenbasierte Berechtigungen](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Rollengruppen

Verwaltungsrollengruppen ordnen Verwaltungsrollen einer Gruppe von Administratoren oder spezialisierten Benutzern zu. Administratoren verwalten eine umfassende Konfiguration der Exchange Online-Organisation oder -Empfänger. Spezialisierte Benutzer verwalten bestimmte Features von Exchange Online, beispielsweise Richtlinientreue, oder sie verfügen über beschränkte Verwaltungsfunktionen, wie Helpdeskmitglieder, ihnen wurden aber keine umfassenden Administratorrechte gewährt. Rollengruppen ordnen in der Regel Verwaltungsrollen zu, mit denen Administratoren und spezialisierte Benutzer die Konfiguration Ihrer Organisation und ihrer Empfänger verwalten können. Ob Administratoren Empfänger verwalten oder Postfachdiscoveryfeatures verwenden können, wird beispielsweise durch Rollengruppen gesteuert. 
  
> [!IMPORTANT]
> Einige Rollengruppen, die in der lokalen Version von Microsoft Exchange Server 2013 verfügbar sind, stehen in Exchange Online möglicherweise nicht zur Verfügung. 
  
Weitere Informationen zu Rollengruppen finden Sie unter [Rollengruppen und Rollenzuweisungsrichtlinien](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Rollenzuweisungsrichtlinien

Management role assignment policies associate end-user management roles to users. Role assignment policies consist of roles that control what users can do with their mailboxes or distribution groups. These roles don't allow management of features that aren't directly associated with the user. When you create a role assignment policy, you define everything a user can do with his or her mailbox. For example, a role assignment policy might allow a user to set the display name, set up voice mail, and configure Inbox rules. Another role assignment policy might allow a user to change the address, use text messaging, and set up distribution groups. Every user with an Exchange Online mailbox, including administrators, is given a role assignment policy by default. You can decide which role assignment policy should be assigned by default, choose what the default role assignment policy should include, override the default for certain mailboxes, or not assign any role assignment policies by default.
  
> [!IMPORTANT]
> Einige Rollenzuweisungen, die in der lokalen Version von Microsoft Exchange Server 2013 verfügbar sind, stehen in Exchange Online möglicherweise nicht zur Verfügung. 
  
Weitere Informationen zu Rollenzuweisungsrichtlinien finden Sie unter [Rollengruppen und Rollenzuweisungsrichtlinien](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  

