---
title: Berechtigungen
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-permissions
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7803d7c0-93e6-43a2-b2a4-3a39abe25500
description: In Microsoft Exchange Online wird ein Modell der rollenbasierten Zugriffssteuerung (Role Based Access Control, RBAC) verwendet, damit Organisationsadministratoren genau steuern können, welche Funktionen Benutzer und IT-Mitarbeiter in dem Dienst nutzen können. Wenn beispielsweise ein Compliance Officer für Postfachsuchanfragen zuständig ist, kann der Administrator dieses administrative Feature über RBAC an diesen Mitarbeiter delegieren. Exchange Online verwendet das gleiche RBAC-Framework wie Microsoft Exchange Server 2013.
ms.openlocfilehash: 365bf87eb0b81364f3268b6e9defdb6f289ae609
ms.sourcegitcommit: 2b9f68f7731dfd6f9d3f33e31e6303e81985ebb2
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/26/2019
ms.locfileid: "39262748"
---
# <a name="permissions"></a>Berechtigungen

In Microsoft Exchange Online wird ein Modell der rollenbasierten Zugriffssteuerung (Role Based Access Control, RBAC) verwendet, damit Organisationsadministratoren genau steuern können, welche Funktionen Benutzer und IT-Mitarbeiter in dem Dienst nutzen können. Wenn beispielsweise ein Compliance Officer für Postfachsuchanfragen zuständig ist, kann der Administrator dieses administrative Feature über RBAC an diesen Mitarbeiter delegieren. Exchange Online verwendet das gleiche RBAC-Framework wie Microsoft Exchange Server 2013. 
  
Auf der obersten Ebene setzt sich RBAC aus Verwaltungsrollen, Verwaltungsrollengruppen und Zuweisungsrichtlinien für Verwaltungsrollen zusammen. Die folgenden Abschnitte enthalten weitere Informationen zu den einzelnen RBAC-Komponenten.
  
Weitere Informationen zu dem in Exchange Online verwendeten RBAC-Berechtigungsmodell finden Sie unter [Berechtigungen](https://go.microsoft.com/fwlink/p/?LinkId=271935).
  
## <a name="role-based-permissions"></a>Rollenbasierte Berechtigungen

In Exchange Online basieren die Berechtigungen, die Administratoren und Benutzern erteilt werden können, auf Verwaltungsrollen. Eine Rolle definiert die Aufgaben, die ein Administrator oder Benutzer ausführen kann. Die Verwaltungsrolle  `Mail Recipients` definiert z. B. die Aufgaben, die ein Benutzer für Postfächer, Kontakte und Verteilergruppen ausführen kann. Wenn einem Administrator oder Benutzer eine Rolle zugewiesen wird, erhält dieser die von der Rolle bereitgestellten Berechtigungen. 
  
Es gibt zwei Typen von Rollen, Administratorrollen und Endbenutzerrollen:
  
- **Administrative Rollen** Diese Rollen umfassen Berechtigungen, die Administratoren oder spezialisierten Benutzern mithilfe von Rollengruppen zur Verwaltung eines bestimmten Bereichs der Exchange Online-Organisation (z. B. Empfänger, Server oder Datenbanken) zugewiesen werden können. 
    
- **Endbenutzerrollen** Mit diesen Rollen, die mithilfe von Rollenzuweisungsrichtlinien zugewiesen werden, können Benutzer Aspekte ihrer eigenen Postfächer und Verteilergruppen verwalten. Endbenutzerrollen beginnen mit dem Präfix  `My`.
    
Mit Rollen werden Administratoren und Benutzern Berechtigungen zum Ausführen von Aufgaben erteilt, indem ihnen die entsprechenden Cmdlets zur Verfügung gestellt werden. Da die Exchange-Verwaltungskonsole und die Exchange-Verwaltungsshell zur Verwaltung von Exchange Online Cmdlets verwenden, können Administratoren oder Benutzer mit Zugriff auf ein Cmdlet die entsprechende Aufgabe über jede der Exchange Online-Verwaltungsoberflächen ausführen.
  
Die rollenbasierten Berechtigungen für Microsoft Online Services überschneiden sich in zwei Punkten mit denen von Exchange Online-RBAC. Erstens werden Benutzer, die in Microsoft Online globale Administratoren oder Dienstadministratoren sind, automatisch der Rollengruppe "Organisationsverwaltung" in Exchange Online zugewiesen. Zweitens werden Benutzer, die in Microsoft Online Helpdeskadministratoren sind, automatisch der Rollengruppe "Helpdesk" in Exchange Online zugewiesen. Ansonsten werden die beiden Sicherheitsmodelle getrennt verwaltet.
  
> [!IMPORTANT]
> Einige Rollen, die in der lokalen Version von Microsoft Exchange Server 2013 verfügbar sind, stehen in Exchange Online möglicherweise nicht zur Verfügung. 
  
Weitere Informationen zu Berechtigungen in Exchange Online finden Sie unter [Rollenbasierte Berechtigungen](https://go.microsoft.com/fwlink/p/?LinkId=271936).
  
## <a name="role-groups"></a>Rollengruppen

Verwaltungsrollengruppen ordnen Verwaltungsrollen einer Gruppe von Administratoren oder spezialisierten Benutzern zu. Administratoren verwalten eine umfassende Konfiguration der Exchange Online-Organisation oder -Empfänger. Spezialisierte Benutzer verwalten bestimmte Features von Exchange Online, beispielsweise Richtlinientreue, oder sie verfügen über beschränkte Verwaltungsfunktionen, wie Helpdeskmitglieder, ihnen wurden aber keine umfassenden Administratorrechte gewährt. Rollengruppen ordnen in der Regel Verwaltungsrollen zu, mit denen Administratoren und spezialisierte Benutzer die Konfiguration Ihrer Organisation und ihrer Empfänger verwalten können. Ob Administratoren Empfänger verwalten oder Postfachdiscoveryfeatures verwenden können, wird beispielsweise durch Rollengruppen gesteuert. 
  
> [!IMPORTANT]
> Einige Rollengruppen, die in der lokalen Version von Microsoft Exchange Server 2013 verfügbar sind, stehen in Exchange Online möglicherweise nicht zur Verfügung. 
  
Weitere Informationen zu Rollengruppen finden Sie unter [Rollengruppen und Rollenzuweisungsrichtlinien](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="role-assignment-policies"></a>Rollenzuweisungsrichtlinien

Durch die Richtlinien für die Verwaltungsrollenzuweisung werden Endbenutzer-Verwaltungsrollen den Benutzern zugeordnet. Rollenzuweisungsrichtlinien bestehen aus Rollen, die steuern, welche Aufgaben Benutzer an ihren Postfächern oder Verteilergruppen durchführen können. Diese Rollen lassen nicht die Verwaltung von Funktionen zu, die dem Benutzer nicht direkt zugeordnet sind. Beim Erstellen einer Rollenzuweisungsrichtlinie definieren Sie alle Aufgaben, die ein Benutzer an seinem Postfach durchführen kann. Beispielsweise kann eine Rollenzuweisungsrichtlinie einem Benutzer das Festlegen des Anzeigenamens, das Einrichten von Voicemail und das Konfigurieren von Posteingangsregeln ermöglichen. Eine weitere Rollenzuweisungsrichtlinie kann einem Benutzer das Ändern der Adresse, die Verwendung von Textnachrichten und das Einrichten von Verteilergruppen gestatten. Alle Benutzer mit einem Exchange Online-Postfach, einschließlich der Administratoren, erhalten standardmäßig eine Rollenzuweisungsrichtlinie. Sie können entscheiden, welche Rollenzuweisungsrichtlinie standardmäßig zugewiesen werden soll, auswählen, was die standardmäßige Rollenzuweisungsrichtlinie enthalten soll, den Standard für bestimmte Postfächer außer Kraft setzen oder auch keine Rollenzuweisungsrichtlinien standardmäßig zuweisen.
  
> [!IMPORTANT]
> Einige Rollenzuweisungen, die in der lokalen Version von Microsoft Exchange Server 2013 verfügbar sind, stehen in Exchange Online möglicherweise nicht zur Verfügung. 
  
Weitere Informationen zu Rollenzuweisungsrichtlinien finden Sie unter [Rollengruppen und Rollenzuweisungsrichtlinien](https://go.microsoft.com/fwlink/p/?LinkId=271937).
  
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Office 365 Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  

