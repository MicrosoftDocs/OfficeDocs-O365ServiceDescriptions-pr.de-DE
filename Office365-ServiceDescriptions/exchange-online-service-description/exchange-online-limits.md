---
title: Exchange Online-Begrenzungen
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: Priority
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Suchen Sie die Exchange Online-Begrenzungen für eine Vielzahl von Service-Bereichen, einschließlich Adressbuchbeschränkungen, Speicherbegrenzungen für Postfächer und Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung, um nur einige zu nennen.
ms.openlocfilehash: 06017db419d1f62c907e5bd5004d8d2eef2f54c1
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173710"
---
# <a name="exchange-online-limits"></a>Exchange Online-Begrenzungen

Suchen Sie die Exchange Online-Begrenzungen für eine Vielzahl von Service-Bereichen, einschließlich Adressbuchbeschränkungen, Speicherbegrenzungen für Postfächer und Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung, um nur einige zu nennen.

> [!NOTE]
> Wenn Sie Unterstützung bei einer Aufgabe benötigen oder ein Problem lösen müssen, könnten die folgenden Artikel hilfreich sein:
> - [E-Mail](https://support.office.com/article/94275804-7147-4332-9ccd-5d421760a9ed) (Hilfe zum Erstellen und Senden von E-Mails)
>- [E-Mails in Microsoft 365 for Business – Hilfe für Administratoren](/microsoft-365/admin/email/)
>- [Beheben von Outlook- und Microsoft 365-Problemen mit dem Support- und Wiederherstellungs-Assistenten für Office 365](https://diagnostics.office.com/)
>- [E-Mail-Unzustellbarkeitsberichte](/Exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/non-delivery-reports-in-exchange-online)
>- [Hilfe zu Exchange Online](/exchange/exchange-online)

Die Grenzwerte bei Microsoft Exchange Online fallen in eine der folgenden Kategorien:

- [Adressbuchbeschränkungen](#address-book-limits)

- [Speicherbegrenzungen für Postfächer](#mailbox-storage-limits)

- [Kapazitätswarnungen](#capacity-alerts)

- [Mailbox folder limits](#mailbox-folder-limits)

- [Nachrichtengrenzwerte](#message-limits)

- [Empfangs- und Sendegrenzen](#receiving-and-sending-limits)

- [Reporting and message trace limits](#reporting-and-message-trace-limits)

- [Aufbewahrungsgrenzwerte](#retention-limits)

- [Verteilergruppen-Grenzwerte](#distribution-group-limits)

- [Journal-, Transport- und Posteingangsregelgrenzen](#journal-transport-and-inbox-rule-limits)

- [Moderationsgrenzwerte](#moderation-limits)

- [Grenzwerte für Exchange ActiveSync](#exchange-activesync-limits)

> [!IMPORTANT]
> - Die für eine Microsoft 365-Organisation geltenden Grenzwerte können anders lauten, abhängig davon, wie lange Ihre Organisation bereits bei dem Dienst registriert ist.
> - Wenn ein Grenzwert in Microsoft-Datencentern geändert wird, kann es eine Weile dauern, um die Änderung für alle vorhandenen Kunden zu übernehmen.
> - Die meisten dieser Grenzwerte können zwar nicht geändert werden, sie sollten Ihnen und den Benutzern jedoch bekannt sein.
> - Diese Grenzwerte gelten sowohl für interne als auch für externe Empfänger.
> - Standardmäßig schützt Exchange Online Protection (EOP) Exchange Online-Postfächer. Informationen zu Beschränkungen für EOP-Funktionen in Exchange Online finden Sie unter [Exchange Online Protection-Begrenzungen](../exchange-online-protection-service-description/exchange-online-protection-limits.md).
> - Informationen zu Office 365-Gruppenbegrenzungen finden Sie unter "Wie verwalte ich meine Gruppen?" in den [Informationen zu Microsoft 365-Gruppen](https://go.microsoft.com/fwlink/?linkid=846714).

## <a name="address-book-limits"></a>Adressbuchbeschränkungen

- **Adresslistenbeschränkung**: Die maximale Anzahl an Adresslisten, die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können. Diese Zahl schließt die Standardadresslisten in Exchange Online ein, z. B. alle Kontakte und alle Gruppen.

    > [!NOTE]
    > Einem einzelnen Offlineadressbuch (OAB) können bis zu 20 Adresslisten zugewiesen werden.

- **Offlineadressbuch-Beschränkung**: Die maximale Anzahl an Offlineadressbüchern (OAB), die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können.

- **Adressbuchrichtlinien-Beschränkung**: Die maximale Anzahl an Adressbuchrichtlinien (ABP), die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können.

- **Globale Adresslisten**: Die maximale Anzahl an globalen Adresslisten (GAL), die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können.

### <a name="address-book-limits"></a>Adressbuchbeschränkungen

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Adresslistenbeschränkung|1000|1000|1000|1000|1000|1000|
|Beschränkung für Offlineadressbuch (OAB)|250|250|250|250|250|250|
|Beschränkung für Adressbuchrichtlinien (ABP)|250|250|250|250|250|250|
|Beschränkung für globale Adresslisten|250|250|250|250|250|250|

### <a name="address-book-limits-across-standalone-plans"></a>Beschränkungen für Adressbücher für eigenständige Pläne

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Adresslistenbeschränkung|1000|1000|1000|1000|
|Beschränkung für Offlineadressbuch (OAB)|250|250|250|250|
|Beschränkung für Adressbuchrichtlinien (ABP)|250|250|250|250|
|Beschränkung für globale Adresslisten|250|250|250|250|

## <a name="mailbox-storage-limits"></a>Speicherbegrenzungen für Postfächer

Die Größe des verfügbaren Postfachspeichers ist abhängig von Postfachtyp und Abonnementlizenz des Benutzers. Administratoren können die maximale Postfachgröße pro Benutzer oder global reduzieren.

> [!NOTE]
> Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung in ein Exchange Online-Postfach zu kopieren. Das Archivpostfach eines Benutzers ist nur für diesen Benutzer vorgesehen. Microsoft behält sich das Recht vor, die uneingeschränkte Archivierung dann zu verweigern, wenn das Archivpostfach eines Benutzers zum Speichern von Archivdaten für andere Benutzer oder auf eine andere unangemessene Weise verwendet wird.

### <a name="storage-limits"></a>Speichergrenzwerte

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Benutzerpostfächer|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|
|Archivipostfächer<sup>7,8</sup>|50 GB|50 GB|50 GB|Unbegrenzt<sup>1</sup>|Unlimited<sup>1</sup>|Nicht verfügbar<sup>4</sup>|
|Freigegebene Postfächer<sup>10</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50/100 GB<sup>2,9</sup>|50/100 GB<sup>2,9</sup>|50 GB<sup>2</sup>|
|Ressourcenpostfächer|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3</sup>|
|Websitepostfächer<sup>5</sup>|50 GB|50 GB|50 GB|50 GB|50 GB|Nicht verfügbar|
|Postfächer für öffentliche Ordner|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|
|Gruppenpostfächer|50 GB|50 GB|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Jeder Benutzer erhält anfänglich 100 GB Speicherplatz im Archivpostfach. Wenn die automatisch erweiterte Archivierung aktiviert ist, wird automatisch zusätzlicher Speicher hinzugefügt, wenn die Speicherkapazität von 100 GB erreicht ist. Weitere Informationen finden Sie unter [Übersicht zur unbeschränkten Archivierung in Office 365](/microsoft-365/compliance/unlimited-archiving). <br/> <sup>2</sup> Um auf ein freigegebenes Postfach zugreifen zu können, benötigt ein Benutzer eine Exchange Online-Lizenz, das freigegebene Postfach selber erfordert aber keine eigene Lizenz. Ohne eine Lizenz sind freigegebene Postfächer auf 50 GB beschränkt. Wenn Sie die Größenbeschränkung auf 100 GB erhöhen möchten, muss dem freigegebene Postfach eine Exchange Online Plan 2-Lizenz oder eine Exchange Online Plan 1-Lizenz mit einer zusätzlichen Exchange Online-Archivierungslizenz zugewiesen werden. Auf diese Weise können Sie auch die automatische Erweiterung der Archivierung für eine unbegrenzte Menge an Archivspeicherkapazität aktivieren. Ähnlich verhält es sich, wenn Sie ein freigegebenes Postfach in die Status „Aufbewahrung für juristische Zwecke“ setzen möchten: Das freigegebene Postfach muss über eine Exchange Online Plan 2-Lizenz oder eine Exchange Online Plan 1-Lizenz mit einer zusätzlichen Exchange Online-Archivierungslizenz verfügen. Wenn Sie erweiterte Funktionen wie Microsoft Defender für Office 365, Advanced eDiscovery oder automatische Aufbewahrungsrichtlinien anwenden möchten, muss das freigegebene Postfach für diese Funktionen lizenziert sein. <br/> <sup>3</sup> Für Ressourcenpostfächer ist keine Lizenz erforderlich. Ohne eine Lizenz sind Ressourcenpostfächer jedoch auf 50 GB beschränkt. Um die Postfachgröße zu erhöhen, muss eine E3- oder E5-Lizenz zugewiesen werden. Dadurch wird die Postfachgröße auf 100 GB erhöht. <br/> <sup>4</sup> Archivpostfächer sind im Exchange Online-Kiosk nicht enthalten. Sie können jedoch als Add-On über Exchange Online-Archivierung erworben werden. Weitere Informationen finden Sie in der [Beschreibung des Exchange Online-Archivierungsdiensts](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>5</sup> Websitepostfächer wurden 2017 aus Exchange Online und SharePoint Online entfernt. <br/> <sup>6</sup> Sie können maximal 1.000 Postfächer für öffentliche Ordner nutzen, und die Gesamtgröße aller Postfächer für öffentliche Ordner ist auf 100 TB begrenzt. Postfächer, die die Hierarchie versorgen, sind auf 100 Postfächer für öffentliche Ordner beschränkt. <br/> <sup>7</sup> In Archivpostfächern können lediglich Mails für einen einzelnen Benutzer oder eine einzelne Entität (z. B. ein freigegebenes Postfach) archiviert werden, für die eine Lizenz angewendet wurde. Archivpostfächer dürfen nicht zum Speichern von Mails von mehreren Benutzern oder Entitäten verwendet werden. Ein IT-Administrator ist beispielsweise nicht berechtigt, ein freigegebenes Postfach zu erstellen und die Benutzer anzuweisen, dieses freigegebene Postfach zum expliziten Zweck der Archivierung in E-Mails zu adressieren (auf CC oder BCC bzw. über eine Transportregel). Ein freigegebenes Postfach, das von mehreren Benutzern verwendet wird, speichert keine E-Mails für die einzelnen Benutzer. Mehrere Benutzer können darauf zugreifen und E-Mails als das freigegebene Postfach senden. Aus diesem Grund werden im freigegebenen Postfach nur die E-Mails gespeichert, die an *das* freigegebene Postfach und von diesem Postfach gesendet werden. <br/> <sup>8</sup> Wenn Sie in Exchange Online eine Aufbewahrungsrichtlinie festgelegt haben, werden Nachrichten automatisch in das Archivpostfach des Benutzers verschoben, sofern sein primäres Postfach größer als 10 MB ist. Die Aufbewahrungsrichtlinie für Postfächer kleiner 10 MB nicht automatisch ausgeführt. <br/> <sup>9</sup> Für freigegebene und Ressourcenpostfächer ist keine Lizenz erforderlich. Ohne eine Lizenz sind diese Postfächer jedoch auf 50 GB beschränkt. Um die Postfachgröße zu erhöhen, muss eine E3- oder E5-Lizenz zugewiesen werden. Dadurch wird die Postfachgröße auf 100 GB erhöht. <br/> <sup>10</sup> Standardmäßig verfügen freigegebene Postfächer über ein aktives Benutzerkonto mit einem vom System generierten (unbekannten) Kennwort. Um das Anmelden für das zugeordnete freigegebene Postfachkonto zu blockieren, lesen Sie [Blockieren der Anmeldung für das freigegebene Postfachkonto](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

### <a name="storage-limits-across-standalone-plans"></a>Speicherbegrenzungen in eigenständigen Plänen

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Benutzerpostfächer|2 GB<sup>1</sup>|50 GB|100 GB|2 GB|
|Archivieren von Postfächern<sup>8, 9</sup>|100 GB<sup>1</sup>|50 GB|Unbegrenzt<sup>2</sup>|Nicht verfügbar<sup>5</sup>|
|Freigegebene Postfächer<sup>11</sup>|2 GB<sup>1</sup>|50 GB<sup>3</sup>|50 GB<sup>3,10</sup>|50 GB<sup>3</sup>|
|Ressourcenpostfächer|2 GB<sup>1</sup>|50 GB<sup>4</sup>|50 GB<sup>4,10</sup>|50 GB<sup>4</sup>|
|Postfächer für öffentliche Ordner|2 GB<sup>6</sup>|50 GB<sup>7</sup>|100 GB<sup>7</sup>|Nicht verfügbar|
|Gruppenpostfächer|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Dies ist die standardmäßige Postfachgröße für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. Es gibt keine obere Speicherbegrenzung für lokale Postfächer. <br/> <sup>2</sup> Jeder Benutzer erhält anfänglich 100 GB Speicherplatz im Archivpostfach. Wenn die automatisch erweiterte Archivierung aktiviert ist, wird automatisch zusätzlicher Speicher hinzugefügt, wenn die Speicherkapazität von 100 GB erreicht ist. Weitere Informationen finden Sie unter [Übersicht zur unbeschränkten Archivierung in Office 365](/microsoft-365/compliance/unlimited-archiving). Informationen zur Verfügbarkeit der automatisch erweiterten Archivierung finden Sie unter [Microsoft 365 Roadmap](https://go.microsoft.com/fwlink/?LinkId=509914). <br/> <sup>3</sup> Um auf ein freigegebenes Postfach zugreifen zu können, benötigt ein Benutzer eine Exchange Online-Lizenz, das freigegebene Postfach selber erfordert aber keine eigene Lizenz. Ohne eine Lizenz sind freigegebene Postfächer auf 50 GB beschränkt. Wenn Sie die Größenbeschränkung auf 100 GB erhöhen möchten, muss dem freigegebene Postfach eine Exchange Online Plan 2-Lizenz oder eine Exchange Online Plan 1-Lizenz mit einer zusätzlichen Exchange Online-Archivierungslizenz zugewiesen werden. Auf diese Weise können Sie auch die automatische Erweiterung der Archivierung für eine unbegrenzte Menge an Archivspeicherkapazität aktivieren. Ähnlich verhält es sich, wenn Sie ein freigegebenes Postfach in die Status „Aufbewahrung für juristische Zwecke“ setzen möchten: Das freigegebene Postfach muss über eine Exchange Online Plan 2-Lizenz oder eine Exchange Online Plan 1-Lizenz mit einer zusätzlichen Exchange Online-Archivierungslizenz verfügen. Wenn Sie erweiterte Funktionen wie Microsoft Defender für Office 365, Advanced eDiscovery oder automatische Aufbewahrungsrichtlinien anwenden möchten, muss das freigegebene Postfach für diese Funktionen lizenziert sein. <br/> <sup>4</sup> Für Ressourcenpostfächer ist keine Lizenz erforderlich. Ohne eine Lizenz sind Ressourcenpostfächer jedoch auf 50 GB beschränkt. Um die Postfachgröße zu erhöhen, muss eine Exchange Online Plan 2-Lizenz zugewiesen werden. Dadurch wird die Postfachgröße auf 100 GB erhöht. <br/> <sup>5</sup> Archivpostfächer sind im Exchange Online-Kiosk nicht enthalten. Sie können jedoch als Add-On über Exchange Online-Archivierung erworben werden. Weitere Informationen finden Sie in der [Beschreibung des Exchange Online-Archivierungsdiensts](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md). <br/> <sup>6</sup> Dies ist die standardmäßige Postfachgröße für Microsoft Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. In Exchange Server 2013 können Sie maximal 100 Postfächer für öffentliche Ordner nutzen, und die Gesamtgröße aller Postfächer für öffentliche Ordner ist auf 50 TB begrenzt. <br/> <sup>7</sup> In Exchange Online können Sie maximal 1.000 Postfächer für öffentliche Ordner nutzen, und die Gesamtgröße aller Postfächer für öffentliche Ordner ist auf 50 TB begrenzt.  <br/> <sup>8</sup> In Archivpostfächern können lediglich Mails für einen einzelnen Benutzer oder eine einzelne Entität archiviert werden, für die eine Lizenz angewendet wurde. Ein Archivpostfach darf nicht zum Speichern von Mails von mehreren Benutzern oder Entitäten verwendet werden. IT-Administratoren ist beispielsweise nicht berechtigt, ein freigegebenes Postfach zu erstellen und die Benutzer anzuweisen, dieses freigegebene Postfach zum expliziten Zweck der Archivierung in E-Mails zu adressieren (auf CC oder BCC bzw. über eine Transportregel). <br/> <sup>9</sup> Wenn Sie in Exchange Online eine Aufbewahrungsrichtlinie festgelegt haben, werden Nachrichten automatisch in das Archivpostfach des Benutzers verschoben, sofern sein primäres Postfach größer als 10 MB ist. Die Aufbewahrungsrichtlinie für Postfächer kleiner 10 MB nicht automatisch ausgeführt. <br/> <sup>10</sup> Für freigegebene und Ressourcenpostfächer ist keine Lizenz erforderlich. Ohne eine Lizenz sind diese Postfächer jedoch auf 50 GB beschränkt. Um die Postfachgröße zu erhöhen, muss eine Exchange Online Plan 2-Lizenz zugewiesen werden. Dadurch wird die Postfachgröße auf 100 GB erhöht. <br/> <sup>11</sup> Standardmäßig verfügen freigegebene Postfächer über ein aktives Benutzerkonto mit einem vom System generierten (unbekannten) Kennwort. Um das Anmelden für das zugeordnete freigegebene Postfachkonto zu blockieren, lesen Sie [Blockieren der Anmeldung für das freigegebene Postfachkonto](/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account).

## <a name="capacity-alerts"></a>Kapazitätswarnungen

Exchange Online bietet drei Arten von Benachrichtigungen, wenn das Postfach eines Benutzers sich der Kapazitätsgrenze nähert oder sie erreicht:

- **Warnung**: Der Benutzer erhält eine Warnung per E-Mail, dass das Postfach sich dem oberen Grenzwert für die Größe nähert. Mit dieser Warnung sollen Benutzer dazu aufgefordert werden, unerwünschte E-Mails zu löschen.

- **Senden verbieten**: Der Benutzer erhält eine Benachrichtigungs-E-Mail "Senden verbieten", wenn der Grenzwert der Postfachgröße erreicht wurde. Der Benutzer kann keine neuen Nachrichten mehr senden, bis ausreichend E-Mails gelöscht wurden, um die Größe des Postfachs auf einen Wert unter dem Grenzwert zu senken.

- **Senden/Empfangen verbieten**: Exchange Online weist alle eingehenden Mails ab, wenn der Grenzwert für die Postfachgröße erreicht wurde, und sendet einen Unzustellbarkeitsbericht an den Absender. Der Absender hat die Möglichkeit, die E-Mail später erneut zu versenden. Um wieder Nachrichten zu erhalten, muss der Benutzer E-Mails löschen, bis die Größe des Postfachs wieder unter dem Grenzwert liegt.

### <a name="capacity-alerts"></a>Kapazitätswarnungen

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Warnung|49 GB|49 GB|49 GB|98 GB|98 GB|1,96 GB|
|Senden verbieten|49,5 GB|49.5 GB|49.5 GB|99 GB|99 GB|1.98 GB|
|Senden/Empfangen verbieten|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|

### <a name="capacity-alerts-across-standalone-plans"></a>Kapazitätswarnungen in eigenständigen Plänen

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Warnung|1,9 GB<sup>1</sup>|49 GB|98 GB|1,96 GB|
|Senden verbieten|2 GB<sup>1</sup>|49.5 GB|99 GB|1.98 GB|
|Senden/Empfangen verbieten|2,3 GB<sup>1</sup>|50 GB|100 GB|2 GB|

> [!NOTE]
> <sup>1</sup> Dies ist die standardmäßige Größe für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern.

## <a name="mailbox-folder-limits"></a>Begrenzungen für Postfachordner

Diese Begrenzungen sollen Postfächer im Rahmen bekannter Abmessungen halten, die in Exchange Online unterstützt werden können. Mit diesen Begrenzungen soll verhindert werden, dass eine unbegrenzte Anzahl von Postfachelementen pro Ordner bzw. eine unbegrenzte Anzahl von Ordnern pro Postfach oder eine unbegrenzte Anzahl von öffentlichen Ordnern pro Exchange Online-Organisation möglich ist. Praktisch gesehen ist die Anzahl der Postfachordner quasi unbegrenzt, sodass die meisten Exchange-Postfächer und lokalen Postfächer unterstützt werden, die zu Exchange Online migriert werden.

- **Maximale Anzahl von Nachrichten pro Postfachordner**: Maximal zulässige Anzahl von Nachrichten in einem Postfachordner. Sobald dieser Grenzwert erreicht wird, können keine neuen Nachrichten mehr übermittelt oder in einem Ordner gespeichert werden.

- **Warnung zur Anzahl der Nachrichten pro Postfachordner**: Anzahl der Nachrichten, die in einem Postfachordner gespeichert werden können, bevor Exchange Online eine Warnmeldung an den Eigentümer des Postfachs schickt. Wenn dieses Kontingent erreicht ist, werden einmal am Tag Warnmeldungen gesendet.

- **Maximale Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"**: Maximale Anzahl der Nachrichten, die in jedem Ordner im Ordner "Wiederherstellbare Elemente" gespeichert werden können. Wenn ein Ordner diesen Grenzwert überschreitet, können darin keine Nachrichten mehr gespeichert werden. Wenn der Ordner "Löschen" im Ordner "Wiederherstellbare Elemente" die maximale Anzahl an Nachrichten überschritten hat und der Postfachbesitzer versucht, Elemente permanent aus seinem Postfach zu löschen, wird der Löschvorgang fehlschlagen.

- **Warnung zur Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"**: Anzahl der Nachrichten, die in jedem Ordner im Ordner "Wiederherstellbare Elemente" gespeichert werden können, bevor Exchange Online ein Ereignis im Anwendungsereignisprotokoll vermerkt.

- **Maximale Anzahl von Unterordnern pro Postfachordner**: Maximal zulässige Anzahl von Unterordnern, die in einem Postfachordner erstellt werden können. Der Postfachbesitzer wird keinen neuen Unterordner erstellen können, wenn dieser Grenzwert erreicht ist.

- **Warnung zur Anzahl der Unterordner pro Postfachordner**: Anzahl der Unterordner, die in einem Postfachordner erstellt werden können, bevor Exchange Online eine Warnmeldung an den Eigentümer des Postfachs schickt. Wenn dieses Kontingent erreicht ist, werden einmal am Tag Warnmeldungen gesendet.

- **Maximale Ordnerhierarchie-Tiefe**: Maximale Anzahl an Ebenen in der Ordnerhierarchie eines Postfachs. Der Postfachbesitzer wird keine neue Ebene in der Ordnerhierarchie des Postfachordners erstellen können, wenn dieser Grenzwert erreicht ist.

- **Warnung zur Ordnerhierarchie-Tiefe**: Anzahl der Ebenen, die in der Ordnerhierarchie eines Postfachordners erstellt werden können, bevor Exchange Online eine Warnmeldung an den Eigentümer des Postfachs schickt. Wenn dieses Kontingent erreicht ist, werden einmal am Tag Warnmeldungen gesendet.

- **Maximale Anzahl öffentlicher Ordner**: Gibt die maximale Anzahl öffentlicher Ordner in der gesamten öffentlichen Ordnerhierarchie an. Wenn diese Grenze erreicht wird, müssen vorhandene öffentliche Ordner gelöscht werden, bevor neue öffentliche Ordner erstellt werden können.

- **Maximale Anzahl von Unterordnern pro öffentlichem Ordner**: Maximal zulässige Anzahl von Unterordnern, die in einem öffentlichen Ordner erstellt werden können. Neue Unterordner können in einem öffentlichen Ordner nicht erstellt werden, wenn diese Grenze erreicht ist.

- **Warnung zur Anzahl der Unterordner pro öffentlichem Ordner**: Anzahl der Unterordner, die in einem öffentlichen Ordner erstellt werden können, bevor Exchange Online eine Warnmeldung an den Eigentümer des Ordners schickt. Falls kein Eigentümer vorhanden ist, werden Warnmeldungen an Benutzer mit Eigentümerberechtigungen geschickt. Wenn dieses Kontingent erreicht ist, werden einmal am Tag Warnmeldungen gesendet.

### <a name="mailbox-folder-limits"></a>Begrenzungen für Postfachordner

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Maximale Anzahl von Nachrichten pro Postfachordner|1 Million|1 Million|1 Million|1 Million|1 Million|1 Million|
|Warnung zur Anzahl der Nachrichten pro Postfachordner|900,000|900,000|900,000|900,000|900,000|900,000|
|Maximale Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"|3 Million|3 Million|3 Million|3 Million|3 Million|3 Million|
|Speicherkontingent für Ordner „Wiederherstellbare Elemente“ im primären Postfach (keine Aufbewahrung aktiviert)|30 GB|30 GB|30 GB|30 GB|30 GB|30 GB|
|Speicherkontingent für Ordner „Wiederherstellbare Elemente“ im primären Postfach (Aufbewahrung aktiviert)|100 GB|100 GB|100 GB|100 GB|100 GB|100 GB|
|Speicherkontingent für Ordner „Wiederherstellbare Elemente“ im Archivpostfach (keine Aufbewahrung aktiviert)|30 GB|30 GB|30 GB|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|30 GB|
|Speicherkontingent für Ordner „Wiederherstellbare Elemente“ im Archivpostfach (Aufbewahrung aktiviert)|100 GB<sup>1</sup>|100 GB<sup>1</sup>|100 GB<sup>1</sup>|Unlimited<sup>2</sup>|Unlimited<sup>2</sup>|100 GB<sup>1</sup>|
|Warnung zur Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"|2.75 Million|2.75 Million|2.75 Million|2.75 Million|2.75 Million|2.75 Million|
|Maximale Anzahl von Unterordnern pro Postfachordner|10.000<sup>2</sup>|10.000<sup>2</sup>|10.000<sup>2</sup>|10.000<sup>2</sup>|10.000<sup>2</sup>|10.000<sup>2</sup>|
|Warnung zur Anzahl der Unterordner pro Postfachordner|9000|9000|9000|9000|9000|9000|
|Maximale Ordnerhierarchie-Tiefe|300|300|300|300|300|300|
|Warnung zur Ordnerhierarchie-Tiefe|250|250|250|250|250|250|
|Maximale Anzahl öffentlicher Ordner|500.000|500.000|500.000|500.000|500.000|Nicht verfügbar|
|Maximale Anzahl von Unterordnern pro öffentlichem Ordner|10,000|10,000|10,000|10,000|10,000|Nicht verfügbar|
|Warnung zur Anzahl der Unterordner pro öffentlichem Ordner|9000|9000|9000|9000|9000|Nicht verfügbar|

> [!NOTE]
> <sup>1</sup> Dies ist das Speicherkontingent für den Ordner „Wiederherstellbare Elemente", nicht das Kontingent für das gesamte Archivpostfach. Das Speicherkontingent für das Archivpostfach ist für Benutzer mit einer Exchange Online Plan 2-Lizenz oder mit einer Exchange Online Plan 1- und einer Exchange Online-Archivierungslizenz unbegrenzt. Informationen zum Erhöhen des Kontingents für wiederherstellbare Elemente finden Sie unter [Erhöhen des Kontingents für wiederherstellbare Elemente für der In-Situ-Aufbewahrung zugewiesene Postfächer](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>2</sup> Das anfängliche Speicherkontingent für den Ordner "Wiederherstellbare Elemente" in einem Archivpostfach beträgt 100 GB. Wenn die automatisch erweiterte Archivierung aktiviert ist, wird automatisch zusätzlicher Speicher hinzugefügt, wenn die Speicherkapazität für den Ordner „Wiederherstellbare Elemente“ erreicht ist. Weitere Informationen finden Sie unter [Übersicht zur unbeschränkten Archivierung in Office 365](/microsoft-365/compliance/unlimited-archiving). Informationen zur Verfügbarkeit der automatisch erweiterten Archivierung finden Sie unter [Microsoft 365 Roadmap](https://go.microsoft.com/fwlink/?LinkId=509914).
> <sup>2</sup> Dies ist ein Speichergrenzwert und ist eine der Postfach-Shape-Einschränkungen. Es können nur 10.000 direkte untergeordnete Ordner für jeden übergeordneten Ordner angegeben werden. Dies gilt unabhängig von der Migration oder anderen Clients, die Ordner erstellen.

### <a name="mailbox-folder-limits-across-standalone-plans"></a>Begrenzungen für Postfachordner in eigenständigen Plänen

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Maximale Anzahl von Nachrichten pro Postfachordner|Keine Beschränkung<sup>1</sup>|1 Million|1 Million|1 Million|
|Warnung zur Anzahl der Nachrichten pro Postfachordner|Unbegrenzt|900,000|900,000|900,000|
|Maximale Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"|Keine Begrenzung|3 Million|3 Million|3 Million|
|Speicherkontingent für Ordner „Wiederherstellbare Elemente“ im primären Postfach (keine Aufbewahrung aktiviert)|30 GB|30 GB|30 GB|30 GB|
|Speicherkontingent für Ordner „Wiederherstellbare Elemente“ im primären Postfach (Aufbewahrung aktiviert)|100 GB|100 GB|100 GB|100 GB|
|Speicherkontingent für Ordner „Wiederherstellbare Elemente“ im Archivpostfach (keine Aufbewahrung aktiviert)|30 GB|30 GB|30 GB|30 GB|
|Speicherkontingent für Ordner „Wiederherstellbare Elemente“ im Archivpostfach (Aufbewahrung aktiviert)|100 GB<sup>2</sup>|100 GB<sup>2</sup>|Unlimited<sup>3</sup>|Unlimited<sup>3</sup>|
|Warnung zur Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente"|Keine Begrenzung|2.75 Million|2.75 Million|2.75 Million|
|Maximale Anzahl von Unterordnern pro Postfachordner|Unbegrenzt|1000|1000|1000|
|Warnung zur Anzahl der Unterordner pro Postfachordner|Unbegrenzt|900|900|900|
|Maximale Ordnerhierarchie-Tiefe|Unbegrenzt|300|300|300|
|Warnung zur Ordnerhierarchie-Tiefe|Unbegrenzt|250|250|250|
|Maximale Anzahl öffentlicher Ordner|1,000,000|100,000|100,000|Nicht verfügbar|
|Maximale Anzahl von Unterordnern pro öffentlichem Ordner|Nicht zutreffend|1,000|1,000|Nicht verfügbar|
|Warnung zur Anzahl der Unterordner pro öffentlichem Ordner|Nicht zutreffend|900|900|Nicht verfügbar|

> [!NOTE]
> <sup>1</sup> Microsoft empfiehlt, dass nicht mehr als 1.000.000 Nachrichten pro Postfachordner vorhanden sind. > <br/> <sup>2</sup> Dies ist das Speicherkontingent für den Ordner "Wiederherstellbare Elemente", nicht das Kontingent für das gesamte Archivpostfach. Das Speicherkontingent für das Archivpostfach ist für Benutzer mit einer Exchange Online Plan 2-Lizenz oder mit einer Exchange Online Plan 1- und einer Exchange Online-Archivierungslizenz unbegrenzt. Informationen zum Erhöhen des Kontingents für wiederherstellbare Elemente finden Sie unter [Erhöhen des Kontingents für wiederherstellbare Elemente für der In-Situ-Aufbewahrung zugewiesene Postfächer](/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>3</sup> Das anfängliche Speicherkontingent für den Ordner "Wiederherstellbare Elemente" in einem Archivpostfach beträgt 100 GB. Wenn die automatisch erweiterte Archivierung aktiviert ist, wird automatisch zusätzlicher Speicher hinzugefügt, wenn die Speicherkapazität für den Ordner „Wiederherstellbare Elemente“ erreicht ist. Weitere Informationen finden Sie unter [Übersicht zur unbeschränkten Archivierung in Office 365](/microsoft-365/compliance/unlimited-archiving). Informationen zur Verfügbarkeit der automatisch erweiterten Archivierung finden Sie unter [Microsoft 365 Roadmap](https://go.microsoft.com/fwlink/?LinkId=509914).

## <a name="message-limits"></a>Nachrichtengrenzwerte

Die folgenden Grenzwerte gelten für sämtliche E-Mails.

- **Nachrichtengrößenbeschränkung**: Nachrichtengrößenbeschränkungen sind notwendig, um zu verhindern, dass große Nachrichten die Zustellung von anderen Nachrichten blockieren und dass die Leistung des Diensts für alle Benutzer beeinträchtigt wird. Diese Beschränkungen umfassen auch Anlagen, und sie gelten organisationsweit für alle Nachrichten (eingehende, ausgehende und interne). Nachrichten, die größer sind, werden nicht zugestellt, und der Absender erhält einen Unzustellbarkeitsbericht. Während die Grenzwerte für die Nachrichtengröße nicht nach oben oder unten oder für die einzelnen Benutzer geändert werden können, können Administratoren auch Transportregeln einrichten, um die maximale Größe einzelner Anlagen zu beschränken. Weitere Informationen finden Sie unter [Microsoft unterstützt größere E-Mail-Nachrichten](https://go.microsoft.com/fwlink/?linkid=2144144).

    > [!NOTE]
    > Einige E-Mail-Clients haben niedrigere Nachrichtengrößengrenzwerte oder beschränken die Größe einer einzelnen Dateianlage auf einen Wert, der unter dem Nachrichtengrößengrenzwert von Exchange Online liegt.

- **Größenbeschränkung für Nachrichtenkopf**: Gibt die maximale Größe aller Nachrichtenkopffelder in einer Nachricht an. Der aktuelle Grenzwert beträgt 256 KB. Wenn die Gesamtgröße aller Nachrichtenköpfe 256 KB überschreitet, lehnt Exchange Online die Nachricht mit dem Fehler "552 5.3.4 Kopfgröße überschreitet feste Maximalgröße" ab. Die Größe des Nachrichtentexts oder der Anlagen wird nicht berücksichtigt. Da die Kopffelder unformatierten Text enthalten, wird die Größe des Kopfes durch die Anzahl der Zeichen in jedem Kopffeld sowie durch die Gesamtanzahl der Kopffelder bestimmt. Jedes Textzeichen belegt 1 Byte.

- **Grenzwert für die Länge des Betreffs**: Die maximale Anzahl von in der Betreffzeile einer E-Mail zulässigen Textzeichen.

- **Grenzwert für Dateianlagen**: Die maximale Anzahl der zulässigen Dateianlagen in einer E-Mail. Auch wenn die Gesamtgröße aller Dateianlagen nicht gegen das Nachrichtengrößenlimit verstößt, gibt es dennoch eine Grenze der Anzahl der zulässigen Anlagen in der Nachricht. Dieser Grenzwert wird vom Grenzwert für mehrteiligen Nachrichten gesteuert.

- **Dateianlagengrößenlimit**: Die maximale Dateigröße einer einzelnen Anlage.

    > [!NOTE]
    > Dies ist die maximale Dateigröße einer einzelnen Anlage. Einzelne Clientprogramme, u. a. Outlook im Web, schränken die Größe von Anlagen ggf. noch weiter ein. Exchange ActiveSync implementiert keine Anlagengrößenlimits für einzelne Anlagen. Die Gesamtgröße aller Anlagen einer Exchange ActiveSync-Nachricht muss kleiner sein als die Nachrichtengrößeneinschränkung.

- **Grenze für mehrteilige Nachrichten**: Die maximale Anzahl der Nachrichtentextteile, die in einer mehrteiligen MIME-Nachricht zugelassen sind. Dieser Grenzwert steuert außerdem die maximale Anzahl Dateianlagen, die in einer Nachricht zulässig sind.

- **Grenzwert für die Tiefe der Nachrichteneinbettung**: Die maximale Anzahl von weitergeleiteten E-Mails, die in einer E-Mail zulässig sind.

### <a name="message-limits"></a>Nachrichtengrenzwerte

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Grenzwert für Nachrichtengröße – Outlook|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Grenzwert für Nachrichtengröße – OWA|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|
|Grenzwert für Nachrichtengröße – Outlook für Mac|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Nachrichtengrößenbeschränkung - Migration|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|
|Grenzwert für Nachrichtengröße – Outlook für iOS und Android | 33 MB| 33 MB| 33 MB| 33 MB| 33 MB| 33 MB|
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die die Office 365-Nachrichtenverschlüsselung mit neuen Funktionen verwenden)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die die ältere Version der Office 365-Nachrichtenverschlüsselung verwenden)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Grenzwert für Länge des Betreffs|255 Zeichen|255 Zeichen|255 Zeichen|255 Zeichen|255 Zeichen|255 Zeichen|
|Grenzwert für Dateianlagen|250 Anlagen|250 Anlagen|250 Anlagen|250 Anlagen|250 Anlagen|250 Anlagen|
|Größenlimit für Dateianlagen – Outlook|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Größenlimit für Dateianlagen – OWA |112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|
|Größenlimit für Dateianlagen – Outlook für Mac|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Größenlimit für Dateianlagen – Outlook für iOS und Android|33 MB |33 MB |33 MB |33 MB |33 MB |33 MB |
|Grenzwert für mehrteilige Nachrichten|250 Teile|250 Teile|250 Teile|250 Teile|250 Teile|250 Teile|
|Grenzwert für die Tiefe der Nachrichteneinbettung|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|

> [!NOTE]
> <sup>1</sup> Die standardmäßige maximale Nachrichtengröße für Microsoft-Postfächer beträgt 25 MB. Microsoft-Administratoren können einen benutzerdefinierten Grenzwert zwischen 1 MB und 150 MB festlegen. Die Größe der Nachricht, die Sie senden oder empfangen können, ist jedoch auch davon abhängig, was in Ihrem E-Mail-Client oder in Ihrer E-Mail-Lösung unterstützt wird. Weitere Informationen zum Anpassen von der maximal zulässigen Nachrichtengröße für Ihre Organisation finden Sie unter [Microsoft unterstützt größere E-Mail-Nachrichten](https://go.microsoft.com/fwlink/?linkid=2144144). 
<br/> <sup>2</sup> Sie können Nachrichten mit bis zu 150 MB zwischen Benutzern senden und empfangen (die Nachricht verlässt dabei nie die Microsoft-Datencenter). Nachrichten, die außerhalb der Microsoft-Datencenter weitergeleitet werden, werden aufgrund der Übersetzungscodierung noch einmal um 33 % größer. In diesem Fall beträgt die maximale Nachrichtengröße 112 MB. <br/> 
<sup>3</sup> OWA berücksichtigt die Möglichkeit, dass Ihre Nachricht aufgrund der Codierung um 33 % größer wird, und beschränkt die Größe der Nachricht, die Sie senden können, auf einen um 25 % niedrigeren Wert als die konfigurierte Einstellung. Wenn Sie beispielsweise die Einstellungen für eine maximale Nachrichtengröße von 100 MB anpassen, können Sie Nachrichten mit bis zu 75 MB senden. 
<br/> <sup>4</sup> Die Größe der Nachrichten, die in Exchange Online verschoben werden sollen, wird von Exchange Online berechnet. Ältere Exchange-Versionen als Exchange Server 2013 melden möglicherweise eine geringere Elementgröße. Dieser Grenzwert gilt für auf Verschiebungen basierende Migrationen mit einem beliebigen unterstützten Exchange-Postfachreplikationsdienst. Andere Migrationsmethoden (einstufig, mehrstufig, IMAP, PST-Datei) und andere Tools von Drittanbietern werden durch allgemeine Nachrichtengröße begrenzt. <br/> 
<sup>5</sup> Informationen zu OME mit neuen Funktionen finden Sie unter [Einrichten der neuen Office 365-Nachrichtenverschlüsselungsfunktionen, die auf Azure Information Protection aufbauen](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e).<br/> 
<sup>6</sup> Klassische Dateianlagen sind auf 112 MB beschränkt, OneDrive-Dateianlagen können jedoch bis zu 2 GB groß sein.


### <a name="message-limits-across-standalone-options"></a>Nachrichtengrenzwert in eigenständigen Produkten

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Grenzwert für Nachrichtengröße – Outlook|10 MB<sup>4</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>2</sup>|
|Grenzwert für Nachrichtengröße – OWA|10 MB<sup>4</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|150 MB<sup>1, 2</sup>|
|Grenzwert für Nachrichtengröße – Outlook für Mac|10 MB<sup>4</sup>|150 MB|150 MB||
|Nachrichtengrößenbeschränkung - Migration|Nicht zutreffend|150 MB <sup>5</sup>|150 MB <sup>5</sup>|150 MB <sup>5</sup>|
|Grenzwert für Nachrichtengröße – Outlook für iOS und Android |25 MB |33 MB |33 MB |33 MB |
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die die Office 365-Nachrichtenverschlüsselung mit neuen Funktionen verwenden)<sup>6</sup>|150 MB|150 MB|150 MB|150 MB|
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die eine ältere Version der Office 365-Nachrichtenverschlüsselung verwenden)<sup>6</sup>|25 MB|25 MB|25 MB|25 MB|
|Grenzwert für Länge des Betreffs|255 Zeichen|255 Zeichen|255 Zeichen|255 Zeichen|
|Grenzwert für Dateianlagen|1024 attachments<sup>4</sup>|250 Anlagen|250 Anlagen|250 Anlagen|
|Größenlimit für Dateianlagen – Outlook|35 MB<sup>4</sup>|150 MB|150 MB|150 MB|
|Größenlimit für Dateianlagen – OWA|35 MB<sup>4</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|
|Größenlimit für Dateianlagen – Outlook für Mac|35 MB<sup>4</sup>|150 MB|150 MB|35 MB|
|Größenlimit für Dateianlagen – Outlook für iOS und Android|25 MB |33 MB|33 MB|33 MB|
|Grenzwert für mehrteilige Nachrichten|250 Teile|250 Teile|250 Teile|250 Teile|
|Grenzwert für die Tiefe der Nachrichteneinbettung|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|

> [!NOTE]
> <sup>1</sup> Microsoft-Administratoren können einen benutzerdefinierten Grenzwert zwischen 1 MB und 150 MB festlegen. Die Größe der Nachricht, die Sie senden oder empfangen können, ist jedoch auch davon abhängig, was in Ihrem E-Mail-Client oder in Ihrer E-Mail-Lösung unterstützt wird. Weitere Informationen zum Anpassen von der maximal zulässigen Nachrichtengröße für Ihre Organisation finden Sie unter [Microsoft unterstützt größere E-Mail-Nachrichten](https://go.microsoft.com/fwlink/?linkid=2144144). <br/> <sup>2</sup> Sie können Nachrichten mit bis zu 150 MB zwischen Benutzern senden und empfangen (die Nachricht verlässt dabei nie die Microsoft-Datencenter). Nachrichten, die außerhalb der Microsoft-Datencenter weitergeleitet werden, werden aufgrund der Übersetzungscodierung noch einmal um 33 % größer. In diesem Fall beträgt die maximale Nachrichtengröße 112 MB. <br/> 
<sup>3</sup> OWA berücksichtigt die Möglichkeit, dass Ihre Nachricht aufgrund der Codierung um 33 % größer wird, und beschränkt die Größe der Nachricht, die Sie senden können, auf einen um 25 % niedrigeren Wert als die konfigurierte Einstellung. Wenn Sie beispielsweise die Einstellungen für eine maximale Nachrichtengröße von 100 MB anpassen, können Sie Nachrichten mit bis zu 75 MB senden. <br/> 
<sup>4</sup> Dies ist der standardmäßige Grenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. <br/> 
<sup>5</sup> Die Größe der Nachrichten, die in Exchange Online verschoben werden sollen, wird von Exchange Online berechnet. Ältere Exchange-Versionen als Exchange Server 2013 melden möglicherweise eine geringere Elementgröße. <br/> 
<sup>6</sup> Informationen zu OME mit neuen Funktionen finden Sie unter [Einrichten der neuen Office 365-Nachrichtenverschlüsselungsfunktionen, die auf Azure Information Protection aufbauen](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e).

## <a name="receiving-and-sending-limits"></a>Empfangs- und Sendegrenzen

Empfangs- und Sendegrenzen werden angewendet, um Spam und Massen-E-Mail-Würmer oder -Viren zu bekämpfen. Diese Grenzwerte tragen dazu bei, die Integrität unserer Systeme sowie unsere Benutzer zu schützen.

### <a name="receiving-limits"></a>Empfangsgrenzen

Empfangsgrenzen gelten für die Anzahl von Nachrichten, die ein Benutzer, eine Gruppe oder ein öffentlicher Ordner pro Stunde empfangen kann. Dies gilt sowohl für Nachrichten aus dem Internet als auch für Nachrichten von lokalen Servern. Wird die Empfangsgrenze überschritten, erhalten die Absender von E-Mails an dieses Postfach einen Unzustellbarkeitsbericht mit der Information, dass das Postfach den zulässigen Schwellenwert für die Anzahl zugestellter Nachrichten überschritten hat. Nach einer Stunde wird die Grenze zurückgesetzt, und das Postfach kann wieder Nachrichten empfangen.

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard Office | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Empfangene Nachrichten|3.600 Nachrichten pro Stunde|3.600 Nachrichten pro Stunde|3.600 Nachrichten pro Stunde|3.600 Nachrichten pro Stunde|3.600 Nachrichten pro Stunde|3600 Nachrichten pro Stunde|

### <a name="sending-limits"></a>Sendegrenzen

Sendegrenzen gelten für die Anzahl von Empfängern, die Anzahl von Nachrichten und die Anzahl von Empfängern pro Nachricht, die ein Benutzer aus seinem Exchange Online-Konto senden kann.

> [!NOTE]
> Für im Adressbuch einer Organisation gespeicherte Verteilergruppen wird die Gruppe als ein Empfänger betrachtet. Für Verteilergruppen, die im Ordner "Kontakte" eines Postfachs gespeichert sind, werden die Mitglieder der Gruppe einzeln gezählt.

- **Empfängerratengrenzwert**: Um die massenhafte Zustellung von Junk-E-Mails zu unterbinden, verfügt Exchange Online über Empfängerbeschränkungen, mit denen Benutzer und Anwendungen daran gehindert werden, große Mengen E-Mails zu versenden. Diese Grenzwerte gelten pro Benutzer für alle ausgehenden und internen Nachrichten.

    > [!NOTE]
    > Exchange Online-Kunden, die seriöse kommerzielle E-Mails versenden müssen (z. B. Kunden-Newsletter), sollten einen Drittanbieter in Anspruch nehmen, der sich auf diese Dienste spezialisiert.

- **Empfängergrenzwert**: Dies ist die maximale Anzahl von Empfängern, die in den Feldern "An:", "Cc:" und "Bcc:" für eine einzelne E-Mail zulässig ist.

    > [!NOTE]
    > Eine Verteilerliste, die im freigegebenen Adressbuch der Organisation gespeichert ist, zählt in Bezug auf den Empfängerratengrenzwert und die Empfängereinschränkung als ein Empfänger. In einer persönlichen Verteilerliste wird jeder Empfänger separat gezählt.

- **Grenzwert für Empfängerproxyadresse**: Der Grenzwert für die Empfängerproxyadresse ist die maximale Anzahl von Aliasen (E-Mail-Adressen), die ein Empfängerpostfach haben kann. 

- **Nachrichtenratengrenzwert**: Nachrichtenratengrenzwerte bestimmen, wie viele Nachrichten ein Benutzer innerhalb eines festgelegten Zeitraums von seinem Exchange Online-Konto senden kann. Dieser Grenzwert verhindert den übermäßigen Verbrauch von Systemressourcen durch einen einzelnen Absender. Wenn ein Benutzer Nachrichten mit einer Häufigkeit übermittelt, welche die SMTP-Clientübermittlungsgrenze überschreitet, werden die Nachrichten abgelehnt, und der Client muss es erneut versuchen.

#### <a name="sending-limits"></a>Sendegrenzen

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Empfängerratengrenzwert<sup>1</sup>|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|
|Empfängerbeschränkung<sup>2</sup>|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|
|Grenzwert für Empfängerproxyadresse|400|400|400|400|400|400|
|Nachrichtenratengrenzwert<sup>3</sup>|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|

> [!NOTE]
> <sup>1</sup> Wenn der Empfängerratengrenzwert erreicht ist, können Nachrichten erst wieder aus dem Postfach gesendet werden, wenn die Anzahl von Empfängern, an die in den letzten 24 Stunden Nachrichten gesendet wurden, unter den Grenzwert fällt. Beispielsweise sendet ein Benutzer um 09:00 Uhr eine E-Mail an 5.000 Empfänger, um 10:00 Uhr eine weitere an 2.500 Empfänger und dann um 11:00 Uhr eine weitere Nachricht an 2.500 Empfänger und erreicht dabei den Grenzwert von 10.000 Nachrichten. Der Benutzer kann dann erst am nächsten Tag um 09:00 Uhr wieder Nachrichten senden.  
> <sup>2</sup> Sie können die Empfängergrenzwerte für vorhandene Postfächer und für neue Postfächer, die in Zukunft erstellt werden, zwischen 1 und 1000 anpassen. Bearbeiten Sie die Empfängerbeschränkung für vorhandene Postfächer einzeln oder massenweise mithilfe des Exchange Admin Centers, und passen Sie die Standardeinstellung für neue Postfächer über Remote PowerShell an. Weitere Informationen finden Sie unter [Anpassbare Empfängerbeschränkungen in Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).  
> <sup>3</sup> Wenn die Menge der ausgehenden Nachrichten den Grenzwert für den Nachrichtenratengrenzwert erreicht, wird jede übermäßige Nachrichtenübermittlung gedrosselt und schrittweise in die anschließenden Minuten übertragen. Dadurch wird in der Regel das Konto des Absenders nicht blockiert, Exchange Online ist jedoch nicht für Massensendungen geeignet. Für diesen Fall werden stattdessen die Optionen 2 und 3 [hier](/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365) empfohlen.

#### <a name="sending-limits-across-standalone-options"></a>Sendegrenzwerte bei Optionen für eigenständige Pläne

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Empfängerratengrenzwert|Keine Beschränkung<sup>1</sup>|10.000 Empfänger pro Tag<sup>2</sup>|10.000 Empfänger pro Tag<sup>2</sup>|10.000 Empfänger pro Tag<sup>2</sup>|
|Empfängergrenzwert|1.000 Empfänger<sup>1</sup>|1.000 Empfänger|1.000 Empfänger|1.000 Empfänger|
|Grenzwert für Empfängerproxyadresse|400|400|400|400|
|Nachrichtenratengrenzwert|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|

> [!NOTE]
> <sup>1</sup> Dies ist der standardmäßige Grenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern.<br/>
<sup>2</sup> Wenn der Empfängerratengrenzwert erreicht ist, können Nachrichten erst wieder aus dem Postfach gesendet werden, wenn die Anzahl von Empfängern, an die in den letzten 24 Stunden Nachrichten gesendet wurden, unter den Grenzwert fällt. Beispielsweise sendet ein Benutzer um 09:00 Uhr eine E-Mail an 5.000 Empfänger, um 10:00 Uhr eine weitere an 2.500 Empfänger und dann um 11:00 Uhr eine weitere Nachricht an 2.500 Empfänger und erreicht dabei den Grenzwert von 10.000 Nachrichten. Der Benutzer kann dann erst am nächsten Tag um 09:00 Uhr wieder Nachrichten senden.

## <a name="reporting-and-message-trace-limits"></a>Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung

Weitere Informationen zu Grenzwerten für Berichterstellung und Nachrichtenablaufverfolgung finden Sie im Abschnitt "Datenverfügbarkeit und Latenz bei Berichterstellung und Nachrichtenablaufverfolgung" in [Berichterstellung und Nachrichtenablaufverfolgung in Exchange Online Protection](/microsoft-365/security/office-365-security/reporting-and-message-trace-in-exchange-online-protection).

## <a name="retention-limits"></a>Aufbewahrungsgrenzwerte

Mit diesen Grenzwerten wird gesteuert, für welchen Zeitraum auf Elemente in bestimmten Ordnern im Posteingang zugegriffen werden kann.

- **Aufbewahrungszeitraum im Ordner "Gelöschte Elemente"**: Die maximale Anzahl von Tagen, die Elemente im Ordner "Gelöschte Elemente" verbleiben können, bevor sie automatisch entfernt werden.

- **Aufbewahrungszeitraum für Elemente, die aus dem Ordner "Gelöschte Elemente" entfernt wurden**: Die maximale Anzahl von Tagen, die die aus dem Ordner "Gelöschte Elemente" entfernten Elemente aufbewahrt werden, bevor sie endgültig gelöscht werden.

- **Aufbewahrungszeitraum im Ordner "Junk-E-Mail"**: Die maximale Anzahl von Tagen, die Elemente im Ordner "Junk-E-Mail" verbleiben können, bevor sie automatisch entfernt werden.

> [!NOTE]
> Ein vorläufig gelöschtes Benutzerpostfach&mdash;ein Postfach, das über das Microsoft 365 Admin Center oder das Cmdlet "Remove-Mailbox" in Exchange Online PowerShell gelöscht wurde und sich noch im Azure Active Directory-Papierkorb&mdash;befindet, kann innerhalb von 30 Tagen wiederhergestellt werden.

### <a name="retention-limits"></a>Aufbewahrungsgrenzwerte

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Aufbewahrungszeitraum des Ordners "Gelöschte Elemente"|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|
|Aufbewahrungszeitraum für Elemente, die aus dem Ordner "Gelöschte Elemente" entfernt wurden|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|
|Aufbewahrungszeitraum des Ordners "Junk-E-Mail"|30 Tage|30 Tage|30 Tage|30 Tage|30 Tage|30 Tage|

> [!NOTE]
> <sup>1</sup>Dies ist der Standardwert für Microsoft 365-Organisationen. Ein Administrator kann diesen Grenzwert für Postfächer in seiner Organisation auf maximal 30 Tage ändern.

### <a name="retention-limits-across-standalone-options"></a>Aufbewahrungszeitraum in eigenständigen Produkten

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Aufbewahrungszeitraum des Ordners "Gelöschte Elemente"|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|
|Aufbewahrungszeitraum für Elemente, die aus dem Ordner "Gelöschte Elemente" entfernt wurden|14 Tage<sup>1</sup>|14 Tage<sup>2</sup>|14 Tage<sup>2</sup>|14 Tage<sup>2</sup>|
|Aufbewahrungszeitraum des Ordners "Junk-E-Mail"|2 Jahre<sup>1</sup>|30 Tage|30 Tage|30 Tage|

> [!NOTE]
> <sup>1</sup>   Dies ist die Standardeinstellung. Administratoren können diesen Wert für ihre Organisation ändern. <br/> <sup>2</sup> Dies ist der standardmäßige Wert für Exchange Online-Organisationen. Ein Administrator kann diesen Grenzwert für Postfächer in seiner Organisation auf maximal 30 Tage ändern.

## <a name="distribution-group-limits"></a>Verteilergruppen-Grenzwerte

Diese Grenzwerte gelten für Verteilergruppen im freigegebenen Adressbuch Ihrer Organisation.

- **Maximale Anzahl von Verteilergruppenmitgliedern**: Die Gesamtzahl der Empfänger wird nach der Erweiterung der Verteilergruppe ermittelt.

- **Senden von Nachrichten an große Verteilergruppen beschränken**: Verteilergruppen, die die von diesem Grenzwert vorgegebene Anzahl von Mitgliedern enthalten, müssen über eine Zustellungsverwaltung oder konfigurierte Optionen für die Nachrichtengenehmigung verfügen. In der Zustellungsverwaltung kann eine Liste von Absendern angegeben werden, die Nachrichten an die Verteilergruppe senden dürfen. Für die Nachrichtengenehmigung werden ein oder mehrere Moderatoren angegeben, die alle an die Verteilergruppe gesendeten Nachrichten genehmigen müssen.

- **Maximale Nachrichtengröße für große Verteilergruppen**: Wenn eine Nachricht an 5.000 oder mehr Empfänger gesendet wird, darf die Nachrichtengröße diese Grenze nicht überschreiten. Übersteigt die Nachrichtengröße den Grenzwert, wird die Nachricht nicht zugestellt, und der Absender erhält einen Unzustellbarkeitsbericht (Non-Delivery Report, NDR).

### <a name="distribution-group-limits"></a>Verteilergruppen-Grenzwerte

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Maximale Anzahl Mitglieder einer Verteilergruppe<sup>1</sup>|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|
|Grenzwert für das Senden von Nachrichten an große Verteilergruppe|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|
|Obergrenze für Nachrichten an Verteilergruppen mit 5.000 bis 99.999 Mitgliedern|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Obergrenze für Nachrichten an Verteilergruppen mit 100.000 Mitgliedern|5 MB|5 MB|5 MB|5 MB|5 MB|5 MB|
|Maximale Anzahl von Verteilergruppenbesitzern|10|10|10|10|10|10|
|Maximale Anzahl von Gruppen, die ein Benutzer erstellen kann|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Wenn Sie Azure Active Directory DirSync verwenden, beträgt die maximale Anzahl von Verteilergruppenmitgliedern, die sie vom lokalen Active Directory mit Azure Active Directory synchronisieren können, 15.000. Wenn Sie Azure AD Connect verwenden, beträgt die Anzahl 50.000. <br/> <sup>2</sup> Dieser Grenzwert gilt auch für Administratoren.

### <a name="distribution-group-limits-across-standalone-options"></a>Grenzwerte für Verteilergruppen in eigenständigen Produkten

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Maximale Anzahl Mitglieder einer Verteilergruppe|100.000 Mitglieder<sup>1</sup>|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|
|Grenzwert für das Senden von Nachrichten an große Verteilergruppe|5.000 oder mehr Mitglieder<sup>1</sup>|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|
|Maximale Anzahl von Verteilergruppenbesitzern|10|10|10|10|
|Maximale Anzahl von Gruppen, die ein Benutzer erstellen kann|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Dies ist der standardmäßige Grenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. <br/> <sup>2</sup> Dieser Grenzwert gilt auch für Administratoren.

## <a name="journal-transport-and-inbox-rule-limits"></a>Journal-, Transport- und Posteingangsregelgrenzen

Die folgende Liste enthält Grenzwerte, die für Journalregeln, Transportregeln (auch als organisationsweite Regeln bezeichnet) sowie für Grenzwerte gelten, die für Posteingangsregeln gelten. Posteingangsregeln werden von einzelnen Benutzern festgelegt und auf Nachrichten angewendet, die vom Postfach des entsprechenden Benutzers gesendet und empfangen werden.

- **Maximale Anzahl von Journatregeln**: Die maximale Anzahl von Journalregeln, die in der Organisation vorhanden sein können.

- **Maximale Anzahl von Transportregeln**: Die maximale Anzahl von Regeln, die in der Organisation vorhanden sein können.

- **Maximale Größe einer einzelnen Transportregel**: Die maximale Anzahl von Zeichen, die in einer einzelnen Transportregel verwendet werden können. Die Zeichen werden in den Bedingungen, Ausnahmen und Aktionen verwendet.

- **Maximale Zeichenanzahl für alle regulären Ausdrücke in allen Transportregeln**: Die Gesamtzahl der Zeichen, die in der Organisation von allen regulären Ausdrücken in allen Bedingungen und Ausnahmen von Transportregeln verwendet werden. Sie können wenige Regeln verwenden, in denen lange und komplexe reguläre Ausdrücke verwendet werden, oder Sie können viele Regeln verwenden, in denen einfache reguläre Ausdrücke verwendet werden.

- **Grenzwerte für die Überprüfung von Anlageninhalten**: Mit den Transportregelbedingungen können Sie den Inhalt von Nachrichtenanlagen untersuchen, es werden jedoch nur die ersten 1 MB des aus einer Anlage extrahierten Texts überprüft. Dieser Grenzwert von 1 MB bezieht sich auf den aus der Anlage extrahierten Text und nicht auf die Dateigröße der Anlage. Eine 2 MB große Datei kann weniger als 1 MB Text enthalten. Auf diese Weise wird der gesamte Text geprüft.

- **Maximale Anzahl von Empfängern, die einer Nachricht von allen Transportregeln hinzugefügt werden**: Wenn auf eine Nachricht unterschiedliche Transportregeln angewendet werden, kann der Nachricht nur eine begrenzte Anzahl von Empfängern hinzugefügt werden. Nachdem die Grenze erreicht wurde, werden verbleibende Empfänger der Nachricht nicht hinzugefügt. Außerdem können einer Nachricht von einer Transportregel keine Verteilergruppen hinzugefügt werden.

- **Weiterleitungsgrenzwert**: Die maximale Anzahl Empfänger, die für eine Postfach- oder Transportregel konfiguriert werden können, wenn die Weiterleitungs- oder Umleitungsaktion verwendet wird. Sollte eine Regel festgelegt werden, eine Nachricht an mehr als diese Anzahl von Empfängern weiterzuleiten, würde diese Regel nicht angewendet werden, und jede regelkonforme Nachricht würde nicht an die in dieser Regel aufgelisteten Empfänger weitergeleitet werden.
    
- **Anzahl der Weiterleitungen einer Nachricht**: Die Anzahl der auf Postfachregeln basierenden Umleitungen, Weiterleitungen oder automatischen Antworten einer Nachricht. Beispiel: Benutzer A hat eine Postfachregel, die, je nach Sender, Nachrichten an Benutzer B weiterleitet. Benutzer B hat eine Postregel, die, je nach Schlüsselwörtern in der Betreffzeile, Nachrichten an Benutzer C weiterleitet. Erfüllt eine Nachricht beide Bedingungen, wird sie nur an Benutzer B gesendet. Sie wird nicht an Benutzer C weitergeleitet, da nur eine Weiterleitung zulässig ist. In diesem Fall wird die Nachricht gelöscht, ohne einen Unzustellbarkeitsbericht (NDR) an Benutzer B zu senden, der angibt, dass die Nachricht nicht an Benutzer C zugestellt wurde. Wir verwenden die Kopfzeile "X-MS-Exchange-Inbox-Rules-Loop", um zu ermitteln, wie oft eine Nachricht umgeleitet wurde. Diese Kopfzeile bleibt auch über Exchange-Organisationsgrenzen hinweg erhalten.

- **Anzahl der Umleitungen einer Nachricht nach Transportregeln**: Die Anzahl der auf Transportregeln basierenden Umleitungen einer Nachricht. So verfügt beispielsweise die Exchange-Organisation Tailspin Toys über eine Transportregel zum Umleiten jeder Nachricht, die an Benutzer A gesendet wurde, an Benutzer B, der sich in der Exchange-Organisation Contoso befindet. Innerhalb der Exchange-Organisation Contoso gibt es eine Transportregel zum Umleiten jeder Nachricht, die an Benutzer B gesendet wurde, an Benutzer C, der sich in der Exchange-Organisation A. Datum Corporation befindet. In diesem Fall wird die Nachricht gelöscht, und es wird ein Unzustellbarkeitsbericht (Non-Delivery Report, NDR) mit Statuscode und der Ablehnungsnachricht *550 5.7.128 TRANSPORT.RULES.RejectMessage; Die Transportregel-Schleifenanzahl wurde überschritten und die Nachricht abgelehnt* an Benutzer A gesendet. Wir verwenden den X-MS-Exchange-Transport-Rules-Loop-Header, um zu ermitteln, wie oft eine Nachricht nach Transportregeln umgeleitet wurde. Diese Kopfzeile bleibt auch über Exchange-Organisationsgrenzen hinweg erhalten.

### <a name="journal-transport-and-inbox-rule-limits"></a>Journal-, Transport- und Posteingangsregelgrenzen

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Maximale Anzahl von Journalregeln|300 Regeln|300 Regeln|300 Regeln|300 Regeln|300 Regeln|300 Regeln|
|Maximale Anzahl Transportregeln|300 Regeln|300 Regeln|300 Regeln|300 Regeln|300 Regeln|300 Regeln|
|Maximale Größe einer einzelnen Transportregel|8 KB|8 KB|8 KB|8 KB|8 KB|8 KB|
|Zeichenbegrenzung für reguläre Ausdrücke in allen Transportregeln|20 KB|20 KB|20 KB|20 KB|20 KB|20 KB|
|Überprüfungsgrenzwerte für Anlageninhalt|1 MB|1 MB|1 MB|1 MB|1 MB|1 MB|
|Maximale Anzahl der aufgrund alle Transportregeln zu einer Nachricht hinzugefügten Empfänger|100 Empfänger|100 Empfänger|100 Empfänger|100 Empfänger|100 Empfänger|100 Empfänger|
|Weiterleitungsgrenzwert|10 Empfänger|10 Empfänger|10 Empfänger|10 Empfänger|10 Empfänger|10 Empfänger|
|Anzahl der Umleitungen einer Nachricht|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|
|Anzahl der Umleitungen einer Nachricht über Transportregeln|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|
|Anzahl der Umleitungen einer Nachricht|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|
|Posteingangsregel|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|256kb<sup>1</sup>|

> [!NOTE]
> <sup>1</sup> Wenn ein Postfach nach Exchange Online migriert wurde, wird der Grenzwert Posteingangsregeln möglicherweise auf den Wert festgelegt, der niedriger als der EXO-Standardwert ist. In diesem Fall kann der Posteingangsregelwert erhöht werden. Anweisungen finden Sie unter [Ändern des von Posteingangsregeln in Exchange Online verwendeten Speicherplatzes](/exchange/clients-and-mobile-in-exchange-online/outlook-on-the-web/increase-the-space-used-by-inbox-rules). 

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Grenzwerte für Journal-, Transport- und Postfachregeln in eigenständigen Produkten

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Maximale Anzahl von Journalregeln|Unbegrenzt|50 Regeln|50 Regeln|50 Regeln|
|Maximale Anzahl Transportregeln|Keine Begrenzung|300 Regeln|300 Regeln|300 Regeln|
|Maximale Größe einer einzelnen Transportregel|40 KB|8 KB|8 KB|8 KB|
|Zeichenbegrenzung für reguläre Ausdrücke in allen Transportregeln|Keine Begrenzung|20 KB|20 KB|20 KB|
|Maximale Anzahl der aufgrund alle Transportregeln zu einer Nachricht hinzugefügten Empfänger|Keine Begrenzung|100 Empfänger|100 Empfänger|100 Empfänger|
|Weiterleitungsgrenzwert|Keine Begrenzung|10 Empfänger|10 Empfänger|10 Empfänger|
|Anzahl der Umleitungen einer Nachricht|3 Umleitungen|1 Umleitung|1 Umleitung|1 Umleitung|
|Anzahl der Umleitungen einer Nachricht über Transportregeln|Keine Begrenzung|1 Umleitung|1 Umleitung|1 Umleitung|

## <a name="moderation-limits"></a>Moderationsgrenzwerte

Diese Grenzwerte steuern die Moderationseinstellungen für die Nachrichtengenehmigung, die auf Verteilergruppen und Transportregeln angewendet wird.

- **Maximale Größe des Vermittlungspostfachs**: Wenn das Vermittlungspostfach diese Grenze überschreitet, werden Nachrichten, die eine Moderation erfordern, zusammen mit einem Unzustellbarkeitsbericht an den Absender zurückgesendet.

- **Maximale Anzahl von Moderatoren**: Die maximale Anzahl von Moderatoren, die Sie einer einzelnen moderierten Verteilergruppe zuweisen können oder die Sie mithilfe einer einzelnen Transportregel einer Nachricht hinzufügen können. Beachten Sie, dass Sie keine Verteilergruppe als Moderator angeben können.

- **Ablauf für Nachrichten, die auf Moderation warten**: Standardmäßig läuft eine Nachricht, die auf Moderation wartet, nach zwei Tagen ab. Die Verarbeitung abgelaufener moderierter Nachrichten wird jedoch jeweils nach sieben Tagen durchgeführt. Dies bedeutet, dass eine moderierte Nachricht in einem Zeitraum von zwei bis neun Tagen jederzeit ablaufen kann.

- **Maximale Rate für abgelaufene Moderationsbenachrichtigungen**: Dieser Grenzwert gibt die maximale Anzahl von Benachrichtigungen für abgelaufene moderierte Nachrichten in einem Zeitraum von einer Stunde an. Der Grenzwert gilt für jede Postfachdatenbank im Datencenter.

Bei hoher Auslastung kann es vorkommen, dass einige Absender keine Benachrichtigungen über abgelaufene moderierte Nachrichten erhalten. Diese Benachrichtigungen können anhand von Übermittlungsberichten jedoch nachvollzogen werden.

### <a name="moderation-limits"></a>Moderationsgrenzwerte

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Maximale Größe des Vermittlungspostfachs|10 GB|10 GB|10 GB|10 GB|10 GB|10 GB|
|Maximale Anzahl Moderatoren|10 Moderatoren|10 Moderatoren|10 Moderatoren|10 Moderatoren|10 Moderatoren|10 Moderatoren|
|Ablauf für Nachrichten, die auf Moderation warten|2 Tage|2 Tage|2 Tage|2 Tage|2 Tage|2 Tage|
|Maximale Rate für abgelaufene Moderationsbenachrichtigungen|300 Ablaufbenachrichtigungen pro Stunde|300 Ablaufbenachrichtigungen pro Stunde|300 Ablaufbenachrichtigungen pro Stunde|300 Ablaufbenachrichtigungen pro Stunde|300 Ablaufbenachrichtigungen pro Stunde|300 Ablaufbenachrichtigungen pro Stunde|

### <a name="moderation-limits-across-standalone-options"></a>Moderationsgrenzwerte in eigenständigen Produkten

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Maximale Größe des Vermittlungspostfachs|Keine Beschränkung<sup>1</sup>|10 GB|10 GB|10 GB|
|Maximale Anzahl Moderatoren|Keine Begrenzung|10 Moderatoren|10 Moderatoren|10 Moderatoren|
|Ablauf für Nachrichten, die auf Moderation warten|5 Tage<sup>1</sup>|2 Tage|2 Tage|2 Tage|
|Maximale Rate für abgelaufene Moderationsbenachrichtigungen|300 Ablaufbenachrichtigungen pro Stunde|300 Ablaufbenachrichtigungen pro Stunde|300 Ablaufbenachrichtigungen pro Stunde|300 Ablaufbenachrichtigungen pro Stunde|

> [!NOTE]
> <sup>1</sup> Dies ist der standardmäßige Grenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern.

## <a name="exchange-activesync-limits"></a>Grenzwerte für Exchange ActiveSync

Die folgenden Grenzwerte gelten für Microsoft Exchange ActiveSync. Hierbei handelt es sich um ein Clientprotokoll, das Postfachdaten zwischen Mobilgeräten und Exchange synchronisiert.

- **Exchange ActiveSync-Gerätebegrenzung**: Die maximale Anzahl an Exchange ActiveSync-Geräten pro Postfach.

- **Exchange ActiveSync-Gerätelöschbegrenzung**: Die maximale Anzahl an Exchange ActiveSync-Geräten, die ein Exchange-Administrator in einem einzelnen Monat löschen kann.

### <a name="exchange-activesync-limits"></a>Grenzwerte für Exchange ActiveSync

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Exchange ActiveSync-Gerätebegrenzung|100|100|100|100|100|100|
|Exchange ActiveSync-Gerätelöschbegrenzung|20|20|20|20|20|20|

### <a name="exchange-activesync-limits-across-standalone-options"></a>Exchange ActiveSync-Grenzwerte über eigenständige Optionen hinweg

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Exchange ActiveSync-Gerätebegrenzung|100|100|100|100|
|Exchange ActiveSync-Gerätelöschbegrenzung|20|20|20|20|