---
title: Planung und Bereitstellung
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-planning-and-deployment
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: e44e5e61-1f5d-4e68-981d-77a42f0ea0d4
ms.openlocfilehash: e722bec332e67e93647b10bbbf4916e7e059c1b7
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132659"
---
# <a name="planning-and-deployment"></a>Planung und Bereitstellung

## <a name="planning-for-service-changes-and-growth"></a>Planung von Dienständerungen und Wachstum

Organisationen sollten die Migrationsoptionen basierend auf den Quell-E-Mail-Systemen, dem gewünschten Endzustand (vollständig oder teilweise gehostet), der Anzahl von zu migrierenden Benutzern sowie basierend darauf auswählen, wie schnell der gewünschte Endzustand erreicht werden soll.
  
## <a name="deployment-options"></a>Bereitstellungsoptionen

- **Reine Cloudbereitstellung** Alle Benutzerpostfächer der Organisation werden in Exchange Online gehostet. 
    
- **Hybride Exchange-Bereitstellung** Einige Benutzerpostfächer der Organisation werden in einer lokalen Exchange-Organisation gehostet, einige Benutzerpostfächer werden in Exchange Online gehostet. 
    
### <a name="cloud-only"></a>Rein cloudbasiert

A cloud-only deployment is one where your organization in the Exchange Online service isn't connected with an on-premises Exchange organization. All users and mailboxes are hosted and managed in Exchange Online and Office 365.
  
### <a name="hybrid"></a>Hybrid

Available for Microsoft Exchange 2003, Exchange 2007, Exchange 2010 and Exchange 2013 on-premises organizations, a hybrid deployment offers either a long-term coexistence configuration with some mailboxes hosted on-premises and some mailboxes hosted in Exchange Online or a migration path to hosting all user mailboxes in Exchange Online. A hybrid deployment offers organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. Hybrid deployment features include secure mail transport, shared calendar free/busy information, and message tracking between the on-premises and Exchange Online organizations.
  
For more information about hybrid deployments, see [Exchange Server 2013 Hybrid Deployments](https://go.microsoft.com/fwlink/p/?LinkId=287035). If you are using Office 365 operated by 21Vianet, see [Configuring Exchange hybrid deployment features with Office 365 operated by 21Vianet](https://go.microsoft.com/fwlink/?LinkID=733373&amp;clcid=0x409).
  
> [!IMPORTANT]
> On-premises Exchange 2003 organizations must install at least one Exchange 2010 Client Access/Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2007 organizations must install at least one Exchange 2010 or Exchange 2013 Client Access and Mailbox server to configure a hybrid deployment with Exchange Online. On-premises Exchange 2010 and Exchange 2013 organizations natively support hybrid deployments with Exchange Online. For more information about Exchange server compatibility in hybrid deployments, see [Hybrid Deployment Prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=243541)> On-premises Exchange organizations must configure their organization for a hybrid deployment. We strongly recommend that administrators use the Exchange Server Deployment Assistant and the Hybrid Configuration Wizard to configure the hybrid deployment. Learn more at [Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036)
  
## <a name="migration-options"></a>Migrationsoptionen

Organizations should choose migration options based on their source email systems, the desired end state (fully hosted or partially hosted), the number of users to migrate, and how quickly the end state needs to be reached. Possible migration options are:
  
- **IMAP-Migration** Migrieren Sie Postfachdaten von IMAP-basierten E-Mail-Systemen zu Exchange Online. 
    
- **Exchange-Übernahmemigration** Migrieren Sie Postfächer von Exchange Server 2003, Exchange Server 2007, Exchange Server 2010, Exchange 2013 und gehosteten Exchange-Systemen mithilfe einer einzelnen Übernahmemigration zu Exchange Online. 
    
- **Phasenweise Exchange-Migration** Führen Sie eine phasenweise Migration durch, um Postfächer von Exchange Server 2003 oder Exchange Server 2007 mithilfe von webbasierten Migrationstools und minimalen Änderungen an der lokalen Infrastruktur zu migrieren. 
    
- **Remote move migration** Migrate on-premises Exchange mailboxes to Exchange Online in an Exchange hybrid deployment. You must have an Exchange hybrid deployment to use a remote move migration. 
    
Weitere Informationen zum Migrieren von E-Mails und Postfächern zu Exchange Online finden Sie unter [Migrieren von Postfächern zu Exchange Online](https://support.office.com/en-us/article/-a3e3bddb-582e-4133-8670-e61b9f58627e).
  
### <a name="imap-migration"></a>IMAP-Migration

Exchange Online offers a web-based tool for migrating mailbox data from email systems that support IMAP. It guides administrators through the following migration steps: 
  
1. Erstellen von leeren Postfächern in der Cloud für Benutzer in der Organisation (typischerweise geschieht dies durch Hochladen einer CSV-Datei oder durch Verwendung von Windows PowerShell).
    
2. Eingeben der Einstellungen für die Remoteserververbindung.
    
3. Verwendung einer CSV-Datei zum Angeben der Postfächer, deren Daten zu Exchange Online-Postfächern migriert werden.
    
4. Nach Eingabe dieser Informationen beginnt Exchange Online mit der Migration der Postfachinhalte über IMAP (Kalenderelemente, Kontakte, Aufgaben und weitere, nicht E-Mail-bezogene Elemente werden nicht migriert).
    
Weitere Informationen zur IMAP-Migration finden Sie unter [Migrieren von E-Mails von einem IMAP-Server zu Exchange Online-Postfächern](https://support.office.com/en-ie/article/Migrate-your-IMAP-mailboxes-to-Office-365-3fe19996-29bc-4879-aab9-5a622b2f1481) und [Migrieren anderer Typen von IMAP-Postfächern](https://support.office.com/en-ie/article/Migrate-other-types-of-IMAP-mailboxes-to-Office-365-58890ccd-ce5e-4d94-be75-560a3b70a706).
  
> [!IMPORTANT]
> Exchange Online baut weniger als 10 Verbindungen mit dem IMAP-Server auf, um eine Überlastung von Ressourcen und Bandbreite des Remoteservers zu vermeiden. 
  
### <a name="cutover-exchange-migration"></a>Exchange-Übernahmemigration

Exchange Online offers a web-based tool for migrating data from on-premises Exchange Server 2003, Exchange Server 2007, or Exchange Server 2010 environments. It guides an administrator through the following migration steps:
  
1. Unter Verwendung der E-Mail-Adresse und der Anmeldedaten für ein lokales Administratorkonto stellt Exchange Online über den AutoErmittlungsdienst eine Verbindung mit der lokalen E-Mail-Organisation her.
    
2. Exchange Online verwendet eine RPC/HTTP-Verbindung, um Verzeichnisinformationen vom Remoteserver zu lesen und Postfächer in Exchange Online zu erstellen.
    
3. Exchange Online synchronizes the mailbox content to the cloud mailboxes. Users remain connected to their original mailboxes while their data is being migrated to Exchange Online.
    
4. Nach Abschluss der anfänglichen Migration werden Änderungen alle 24 Stunden mit der Cloud synchronisiert, bis der Administrator den Migrationsbatch anhält oder löscht.
    
Um Benutzer zu ihren Cloud-Postfächern zu wechseln, konfigurieren Administratoren ihren MX-Eintrag so, dass er auf Microsoft verweist und die Benutzerprofile in Outlook neu konfiguriert. Wenn Benutzer auf ihre Cloudpostfächer wechseln, werden ihre lokalen Offlineordner (OST-Dateien) erneut synchronisiert, was dazu führt, dass migrierte E-Mails auf die Clientarbeitsstation heruntergeladen werden. Benutzer können nach der Migration auf alte Nachrichten in ihren Postfächern antworten.
  
Weitere Informationen zu einer Exchange-Übernahmemigration finden Sie unter [Wichtige Informationen zur E-Mail-Übernahmemigration zu Office 365](https://support.office.com/en-us/article/What-you-need-to-know-about-a-cutover-email-migration-to-Office-365-961978ef-f434-472d-a811-1801733869da).
  
> [!IMPORTANT]
> An organization can migrate a maximum of 2,000 Exchange 2003, Exchange 2007, Exchange 2010, or Exchange 2013 mailboxes to the cloud using a cutover Exchange migration. > Exchange Online must connect to an on-premises Exchange Server, so the on-premises server must have a certificate issued by a trusted certificate authority and a public IP address. 
  
### <a name="staged-exchange-migration"></a>Phasenweise Exchange-Migration

With a staged migration, users can be migrated to the cloud using the web-based Exchange migration tool and the Directory Synchronization tool. Instead of migrating all users at once, like a cutover Exchange migration, administrators migrate users in batches. This is accomplished by uploading a .csv file to specify a partial list of users to migrate. In a staged migration, all of the users in an organization can share the same email domain name.
  
Staged Exchange migration requires administrators to use the Online Services Directory Synchronization tool. This provides users with a unified Global Address List (GAL) where the online environment is continuously synchronized with the on-premises environment.
  
Weitere Informationen zu mehrstufigen Exchange-Migrationen finden Sie unter [Wichtige Informationen zur mehrstufigen E-Mail-Migration zu Office 365](https://support.office.com/en-ie/article/What-you-need-to-know-about-a-staged-email-migration-to-Office-365-7e2c82be-5f3d-4e36-bc6b-e5b4d411e207).
  
> [!IMPORTANT]
> Organizations can't use a staged Exchange migration to migrate Exchange 2010 and Exchange 2013 mailboxes. If you have fewer than 2,000 Exchange 2010 or Exchange 2013 mailboxes in your organization, you can use a cutover Exchange migration. If you have more than 2,000 Exchange 2010 or Exchange 2013 mailboxes, you can implement a hybrid deployment. > During migration, administrators must use the Online Services Directory Synchronization tool to provide users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
  
## <a name="migration-tools"></a>Migrationstools

Microsoft provides several tools to help migrate an existing email environment to Exchange Online. Which ones are appropriate depends on the organization's current environment and deployment goals:
  
- **Migration dashboard** Administrators can use the Migration dashboard in the Exchange admin center to manage mailbox migration to Exchange Online in a cutover or staged Exchange migration. Administrators can also use the dashboard to migrate the contents of users' mailboxes from an on-premises IMAP server to existing Exchange Online mailboxes. The dashboard gives administrators the following capabilities: 
    
  - **Create and start multiple migration batches** Administrators can create and queue up to 100 migration batches. Only one migration batch runs at a time, but administrators can queue up multiple batches, so when a migration batch is finished running the next batch in the queue starts. 
    
  - **Restart a migration batch with failures** After the initial synchronization for a migration batch, where items are copied from on-premises mailboxes to the cloud mailboxes for each user in the migration batch, some mailboxes may fail synchronization. Administrators can restart that migration batch to try to synchronize the failed mailboxes. 
    
  - **Anzeige von Informationen zu übersprungenen Elementen** Bei IMAP-Migrationen, Übernahmemigrationen und mehrstufigen Migrationen zeigt das Dashboard Informationen zu bestimmten Elementen an, die übersprungen wurden. Es wird auch angezeigt, aus welchen Gründen ein Element übersprungen wurde, und wo im Benutzerpostfach sich das Element befindet. 
    
  - **Öffnen von Migrationsberichten** Administratoren können direkt aus dem Dashboard Migrationsstatistiken oder den Migrationsfehlerbericht für einen Migrationsbatch öffnen. 
    
  - **Bearbeiten eines Migrationsbatches** Wenn sich ein Migrationsbatch für eine phasenweise Exchange-Migration oder eine IMAP-Migration in der Migrationswarteschlange befindet, derzeit aber nicht ausgeführt wird, können Administratoren den Migrationsbatch bearbeiten. 
    
- **Azure Active Directory Sync tool** The Azure Active Directory Sync tool plays an important role in migration to hybrid email scenarios that utilize both Exchange Online and an on-premises Exchange Server. The tool performs a one-way synchronization from on-premises Active Directory to Exchange Online. After migration is complete, administrators only need to use Exchange Online to manage Active Directory users and groups. The tool also provides users with a unified Global Address List where the online environment is continuously synchronized with the on-premises environment. 
    
    Weitere Informationen zum Azure Active Directory-Synchronisierungstool finden Sie in der [Roadmap Verzeichnissynchronisierung](https://go.microsoft.com/fwlink/p/?LinkId=287034).
    
- **Hybrid Configuration Wizard** The Hybrid Configuration Wizard streamlines the hybrid deployment process by simplifying the on-premises and Exchange Online configuration of features and services. Introduced as part of Exchange Server 2010 Service Pack 2, the Hybrid Configuration Wizard is run only in on-premises organizations and has the following components: 
    
  - Einen Assistenten für die Exchange-Verwaltungskonsole, der Administratoren durch die gesamte Konfiguration einer Hybridbereitstellung leitet.
    
  - Einen Satz Befehle für die Exchange-Verwaltungsshell zur Abstimmung des Konfigurationsprozesses.
    
    Weitere Informationen zum Assistenten für die Hybridkonfiguration finden Sie unter [Assistent für die Hybridkonfiguration](https://go.microsoft.com/fwlink/p/?LinkId=271734).
    
- **Remote Windows PowerShell** As part of the Exchange Online December 2011 Service Update, remote Windows PowerShell can be used to help troubleshoot migration errors. For instance, administrators can display diagnostic information for migration batches, as well as migration statistics and diagnostic information for users based on their primary SMTP addresses. 
    
## <a name="feature-availability"></a>Verfügbarkeit von Funktionen

Informationen zum Anzeigen der Verfügbarkeit von Features in Plänen, eigenständigen Optionen und lokalen Lösungen finden Sie unter [Exchange Online Service Description](exchange-online-service-description.md).
  

