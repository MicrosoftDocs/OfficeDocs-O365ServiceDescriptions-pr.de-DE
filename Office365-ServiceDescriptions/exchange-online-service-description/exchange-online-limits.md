---
title: Exchange Online-Begrenzungen
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-limits
ms.service: o365-administration
localization_priority: High
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 70b38a05-6cfa-4ced-a137-116019262fed
description: Suchen Sie die Exchange Online-Begrenzungen für eine Vielzahl von Service-Bereichen, einschließlich Adressbuchbeschränkungen, Speicherbegrenzungen für Postfächer und Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung, um nur einige zu nennen.
ms.openlocfilehash: 325396d0046e857d1c7812f9d8640a95018c248b
ms.sourcegitcommit: bd0cf8920c64e171967d7dd61b7f988bd093c073
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 02/02/2021
ms.locfileid: "50080291"
---
# <a name="exchange-online-limits"></a>Exchange Online-Begrenzungen

Suchen Sie die Exchange Online-Begrenzungen für eine Vielzahl von Service-Bereichen, einschließlich Adressbuchbeschränkungen, Speicherbegrenzungen für Postfächer und Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung, um nur einige zu nennen.

> [!NOTE]
> Wenn Sie Unterstützung bei einer Aufgabe benötigen oder ein Problem lösen müssen, könnten die folgenden Artikel hilfreich sein:
> - [E-Mail](https://support.office.com/article/94275804-7147-4332-9ccd-5d421760a9ed) (zur Unterstützung beim Erstellen und Senden von E-Mails)
>- [E-Mail in Microsoft 365 Business – Administratorhilfe](https://go.microsoft.com/fwlink/?linkid=529722)
>- [Beheben von Outlook- und Microsoft 365-Problemen mit dem Support- und Wiederherstellungs-Assistenten von Microsoft](https://diagnostics.office.com/)
>- [Unzustellungsberichte für E-Mails](https://go.microsoft.com/fwlink/?linkid=526653)
>- [Exchange Online Help](https://go.microsoft.com/fwlink/?linkid=825607)

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
> - Die für eine Microsoft 365-Organisation angewendeten Grenzwerte können je nachdem, wie lange die Organisation für den Dienst registriert wurde, abweichen.
> - Wenn ein Grenzwert in Microsoft-Datencentern geändert wird, kann es eine Weile dauern, um die Änderung für alle vorhandenen Kunden zu übernehmen.
> - Die meisten dieser Grenzwerte können zwar nicht geändert werden, sie sollten Ihnen und den Benutzern jedoch bekannt sein.
> - Diese Grenzwerte gelten sowohl für interne als auch für externe Empfänger.
> - Standardmäßig schützt Exchange Online Protection (EOP) Exchange Online-Postfächer. Beschränkungen, die für die EOP-Features in Exchange Online gelten, finden Sie unter [Exchange Online Protection-Grenzwerte.](../exchange-online-protection-service-description/exchange-online-protection-limits.md)
> - Informationen zu Office 365-Gruppenbeschränkungen finden Sie unter "Wie verwalte ich meine Gruppen?" in [Erfahren Sie mehr über Microsoft 365-Gruppen.](https://go.microsoft.com/fwlink/?linkid=846714)

## <a name="address-book-limits"></a>Adressbuchbeschränkungen

- **Adresslistengrenzwert:** Die maximale Anzahl von Adresslisten, die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können. Diese Zahl schließt die Standardadresslisten in Exchange Online ein, z. B. alle Kontakte und alle Gruppen.

    > [!NOTE]
    > Einem einzelnen Offlineadressbuch (OAB) können bis zu 20 Adresslisten zugewiesen werden.

- **Grenzwert für** Offlineadressbücher: Die maximale Anzahl von Offlineadressbüchern(OAB), die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden können.

- **Grenzwert für Adressbuchrichtlinien:** Die maximale Anzahl von Adressbuchrichtlinien, die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden.

- **Globale Adresslisten:** Die maximale Anzahl von globalen Adresslisten (GAL), die in einer Exchange Online- oder Exchange Server 2013-Organisation erstellt werden.

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
> Es ist nicht zulässig, Journaling, Transportregeln oder Regeln zur automatischen Weiterleitung zu verwenden, um Nachrichten zur Archivierung in ein Exchange Online-Postfach zu kopieren. Das Archivpostfach eines Benutzers ist nur für diesen Benutzer vorgesehen. Microsoft behält sich das Recht vor, die unbegrenzte Archivierung in Fällen zu verweigern, in denen das Archivpostfach eines Benutzers zum Speichern von Archivdaten für andere Benutzer oder in anderen Fällen unangemessener Verwendung verwendet wird.

### <a name="storage-limits"></a>Speichergrenzwerte

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Benutzerpostfächer|50 GB|50 GB|50 GB|100 GB|100 GB|2 GB|
|Archivpostfächer<sup>7,8</sup>|50 GB|50 GB|50 GB|Unbegrenzt<sup>1</sup>|Unlimited<sup>1</sup>|Nicht verfügbar<sup>4</sup>|
|Freigegebene Postfächer<sup>10</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50 GB<sup>2</sup>|50/100 GB<sup>2,9</sup>|50/100 GB<sup>2,9</sup>|50 GB<sup>2</sup>|
|Ressourcenpostfächer|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3,9</sup>|50 GB<sup>3</sup>|
|Websitepostfächer<sup>5</sup>|50 GB|50 GB|50 GB|50 GB|50 GB|Nicht verfügbar|
|Postfächer für öffentliche Ordner|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|100 GB<sup>6</sup>|
|Gruppenpostfächer|50 GB|50 GB|50 GB|50 GB|50 GB|50 GB|

> [!NOTE]
> <sup>1</sup> Jeder Benutzer erhält anfänglich 100 GB Speicherplatz im Archivpostfach. Wenn die automatisch erweiterte Archivierung aktiviert ist, wird automatisch zusätzlicher Speicher hinzugefügt, wenn die Speicherkapazität von 100 GB erreicht ist. Weitere Informationen finden Sie unter [Übersicht zur unbeschränkten Archivierung in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). <br/> <sup>2</sup> Für den Zugriff auf ein freigegebenes Postfach muss ein Benutzer über eine Exchange Online-Lizenz verfügen, für das freigegebene Postfach ist jedoch keine separate Lizenz erforderlich. Ohne Lizenz sind freigegebene Postfächer auf 50 GB beschränkt. Um die Größenbeschränkung auf 100 GB zu erhöhen, muss dem freigegebenen Postfach eine Exchange Online Plan 2-Lizenz oder eine Exchange Online Plan 1-Lizenz mit einer Exchange Online-Archivierung-Add-On-Lizenz zugewiesen werden. Auf diese Weise können Sie auch die Archivierung mit automatischer Erweiterung für eine unbegrenzte Menge an Archivspeicherkapazität aktivieren. Ebenso muss das freigegebene Postfach über eine Exchange Online Plan 2-Lizenz oder eine Exchange Online Plan 1-Lizenz mit einer Exchange Online-Archivierung-Add-On-Lizenz verfügen, wenn Sie für ein freigegebenes Postfach das Rechtsstreitigkeiten aktivieren möchten. Wenn Sie erweiterte Features wie Microsoft Defender für Office 365, Advanced eDiscovery oder automatische Aufbewahrungsrichtlinien anwenden möchten, muss das freigegebene Postfach für diese Features lizenziert werden. <br/> <sup>3</sup> Für Ressourcenpostfächer ist keine Lizenz erforderlich. Ohne Lizenz sind Ressourcenpostfächer jedoch auf 50 GB beschränkt. Um die Postfachgröße zu erhöhen, muss eine E3- oder E5-Lizenz zugewiesen werden. Dadurch wird die Postfachgröße auf 100 GB erhöht. <br/> <sup>4</sup> Archivpostfächer sind im Exchange Online-Kiosk nicht enthalten. Sie können jedoch als Add-On über Exchange Online-Archivierung erworben werden. Weitere Informationen finden Sie in der Exchange Online-Archivierung [Dienstbeschreibung.](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md) <br/> <sup>5</sup> Websitepostfächer wurden 2017 aus Exchange Online und SharePoint Online entfernt. <br/> <sup>6</sup> Sie sind auf 1.000 Postfächer für öffentliche Ordner beschränkt, und die Gesamtgröße aller Postfächer für öffentliche Ordner beträgt 100 TB. Postfächer, die die Hierarchie versorgen, sind auf 100 Postfächer für öffentliche Ordner beschränkt. <br/> <sup>7</sup> In Archivpostfächern können lediglich Mails für einen einzelnen Benutzer oder eine einzelne Entität (z. B. ein freigegebenes Postfach) archiviert werden, für die eine Lizenz angewendet wurde. Archivpostfächer dürfen nicht zum Speichern von Mails von mehreren Benutzern oder Entitäten verwendet werden. Ein IT-Administrator ist beispielsweise nicht berechtigt, ein freigegebenes Postfach zu erstellen und die Benutzer anzuweisen, dieses freigegebene Postfach zum expliziten Zweck der Archivierung in E-Mails zu adressieren (auf CC oder BCC bzw. über eine Transportregel). Ein freigegebenes Postfach, das von mehreren Benutzern verwendet wird, speichert keine E-Mails für die einzelnen Benutzer. Mehrere Benutzer können darauf zugreifen und E-Mails als das freigegebene Postfach senden. Daher sind die einzigen E-Mails, die im freigegebenen Postfach gespeichert *sind,* diejenigen, die als freigegebenes Postfach an oder von diesem postfach gesendet werden. <br/> <sup>8</sup> Wenn Sie in Exchange Online eine Aufbewahrungsrichtlinie festgelegt haben, werden Nachrichten automatisch in das Archivpostfach des Benutzers verschoben, sofern sein primäres Postfach größer als 10 MB ist. Die Aufbewahrungsrichtlinie für Postfächer kleiner 10 MB nicht automatisch ausgeführt. <br/> <sup>9</sup> Für freigegebene und Ressourcenpostfächer ist keine Lizenz erforderlich. Ohne eine Lizenz sind diese Postfächer jedoch auf 50 GB beschränkt. Um die Postfachgröße zu erhöhen, muss eine E3- oder E5-Lizenz zugewiesen werden. Dadurch wird die Postfachgröße auf 100 GB erhöht. <br/> <sup>10</sup> Freigegebenen Postfächern ist standardmäßig ein aktives Benutzerkonto mit einem vom System generierten (unbekannten) Kennwort zugeordnet. Informationen zum Blockieren der Anmeldung für das zugeordnete freigegebene Postfachkonto finden Sie unter "Blockieren der [Anmeldung für das freigegebene Postfachkonto".](https://docs.microsoft.com/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)

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
> <sup>1</sup> Dies ist die standardmäßige Postfachgröße für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. Es gibt keine obere Speicherbegrenzung für lokale Postfächer. <br/> <sup>2</sup> Jeder Benutzer erhält anfänglich 100 GB Speicherplatz im Archivpostfach. Wenn die automatisch erweiterte Archivierung aktiviert ist, wird automatisch zusätzlicher Speicher hinzugefügt, wenn die Speicherkapazität von 100 GB erreicht ist. Weitere Informationen finden Sie unter [Übersicht zur unbeschränkten Archivierung in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Details zur Verfügbarkeit für die Archivierung mit automatischer Erweiterung finden Sie in der [Microsoft 365-Roadmap.](https://go.microsoft.com/fwlink/?LinkId=509914) <br/> <sup>3</sup> Für den Zugriff auf ein freigegebenes Postfach muss ein Benutzer über eine Exchange Online-Lizenz verfügen, für das freigegebene Postfach ist jedoch keine separate Lizenz erforderlich. Ohne Lizenz sind freigegebene Postfächer auf 50 GB beschränkt. Um die Größenbeschränkung auf 100 GB zu erhöhen, muss dem freigegebenen Postfach eine Exchange Online Plan 2-Lizenz oder eine Exchange Online Plan 1-Lizenz mit einer Exchange Online-Archivierung-Add-On-Lizenz zugewiesen werden. Auf diese Weise können Sie auch die Archivierung mit automatischer Erweiterung für eine unbegrenzte Menge an Archivspeicherkapazität aktivieren. Ebenso muss das freigegebene Postfach über eine Exchange Online Plan 2-Lizenz oder eine Exchange Online Plan 1-Lizenz mit einer Exchange Online-Archivierung-Add-On-Lizenz verfügen, wenn Sie für ein freigegebenes Postfach das Rechtsstreitigkeiten aktivieren möchten. Wenn Sie erweiterte Features wie Microsoft Defender für Office 365, Advanced eDiscovery oder automatische Aufbewahrungsrichtlinien anwenden möchten, muss das freigegebene Postfach für diese Features lizenziert werden. <br/> <sup>4</sup> Für Ressourcenpostfächer ist keine Lizenz erforderlich. Ohne Lizenz sind Ressourcenpostfächer jedoch auf 50 GB beschränkt. Um die Postfachgröße zu erhöhen, muss eine Exchange Online Plan 2-Lizenz zugewiesen werden. Dadurch wird die Postfachgröße auf 100 GB erhöht. <br/> <sup>5</sup> Archivpostfächer sind im Exchange Online-Kiosk nicht enthalten. Sie können jedoch als Add-On über Exchange Online-Archivierung erworben werden. Weitere Informationen finden Sie in der Exchange Online-Archivierung [Dienstbeschreibung.](../exchange-online-archiving-service-description/exchange-online-archiving-service-description.md) <br/> <sup>6</sup> Dies ist die standardmäßige Postfachgröße für Microsoft Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. In Exchange Server 2013 können Sie maximal 100 Postfächer für öffentliche Ordner nutzen, und die Gesamtgröße aller Postfächer für öffentliche Ordner ist auf 50 TB begrenzt. <br/> <sup>7</sup> In Exchange Online können Sie maximal 1.000 Postfächer für öffentliche Ordner nutzen, und die Gesamtgröße aller Postfächer für öffentliche Ordner ist auf 50 TB begrenzt.  <br/> <sup>8</sup> In Archivpostfächern können lediglich Mails für einen einzelnen Benutzer oder eine einzelne Entität archiviert werden, für die eine Lizenz angewendet wurde. Ein Archivpostfach darf nicht zum Speichern von Mails von mehreren Benutzern oder Entitäten verwendet werden. IT-Administratoren ist beispielsweise nicht berechtigt, ein freigegebenes Postfach zu erstellen und die Benutzer anzuweisen, dieses freigegebene Postfach zum expliziten Zweck der Archivierung in E-Mails zu adressieren (auf CC oder BCC bzw. über eine Transportregel). <br/> <sup>9</sup> Wenn Sie in Exchange Online eine Aufbewahrungsrichtlinie festgelegt haben, werden Nachrichten automatisch in das Archivpostfach des Benutzers verschoben, sofern sein primäres Postfach größer als 10 MB ist. Die Aufbewahrungsrichtlinie für Postfächer kleiner 10 MB nicht automatisch ausgeführt. <br/> <sup>10</sup> Freigegebene und Ressourcenpostfächer erfordern keine Lizenz. Ohne eine Lizenz sind diese Postfächer jedoch auf 50 GB beschränkt. Um die Postfachgröße zu erhöhen, muss eine Exchange Online Plan 2-Lizenz zugewiesen werden. Dadurch wird die Postfachgröße auf 100 GB erhöht. <br/> <sup>11</sup> Freigegebenen Postfächern ist standardmäßig ein aktives Benutzerkonto mit einem vom System generierten (unbekannten) Kennwort zugeordnet. Informationen zum Blockieren der Anmeldung für das zugeordnete freigegebene Postfachkonto finden Sie unter "Blockieren der [Anmeldung für das freigegebene Postfachkonto".](https://docs.microsoft.com/office365/admin/email/create-a-shared-mailbox#block-sign-in-for-the-shared-mailbox-account)

## <a name="capacity-alerts"></a>Kapazitätswarnungen

Exchange Online bietet drei Arten von Benachrichtigungen, wenn das Postfach eines Benutzers sich der Kapazitätsgrenze nähert oder sie erreicht:

- **Warnung:** Der Benutzer erhält eine E-Mail-Warnung, dass das Postfach sich der maximalen Größenbeschränkung nähert. Mit dieser Warnung sollen Benutzer dazu aufgefordert werden, unerwünschte E-Mails zu löschen.

- **Senden verbieten:** Der Benutzer erhält eine Benachrichtigungs-E-Mail zum Senden verbieten, wenn die Größenbeschränkung des Postfachs erreicht ist. Der Benutzer kann neue Nachrichten erst senden, wenn genügend E-Mails gelöscht wurden, um das Postfach unter die Größenbeschränkung zu bringen.

- **Senden/Empfangen** verbieten: Exchange Online lehnt eingehende E-Mails ab, wenn die Postfachgröße erreicht ist, und sendet einen Unzustellbarkeitsbericht an den Absender. Der Absender hat die Möglichkeit, die E-Mail später erneut zu versenden. Um wieder Nachrichten zu erhalten, muss der Benutzer E-Mails löschen, bis die Größe des Postfachs wieder unter dem Grenzwert liegt.

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

- **Maximale Anzahl von Nachrichten pro Postfachordner:** Gibt die maximale Anzahl von Nachrichten für einen Postfachordner an. Sobald dieser Grenzwert erreicht wird, können keine neuen Nachrichten mehr übermittelt oder in einem Ordner gespeichert werden.

- **Warnung zur Anzahl der** Nachrichten pro Postfachordner: Gibt die Anzahl der Nachrichten an, die ein Postfachordner enthalten kann, bevor Exchange Online eine Warnmeldung an den Postfachbesitzer sendet. Wenn dieses Kontingent erreicht ist, werden einmal am Tag Warnmeldungen gesendet.

- **Maximale Anzahl von Nachrichten** pro Ordner im Ordner "Wiederherstellbare Elemente": Gibt die maximale Anzahl von Nachrichten an, die in jedem Ordner im Ordner "Wiederherstellbare Elemente" enthalten sein können. Wenn ein Ordner diesen Grenzwert überschreitet, können darin keine Nachrichten mehr gespeichert werden. Wenn der Ordner "Löschen" im Ordner "Wiederherstellbare Elemente" die maximale Anzahl an Nachrichten überschritten hat und der Postfachbesitzer versucht, Elemente permanent aus seinem Postfach zu löschen, wird der Löschvorgang fehlschlagen.

- **Warnung** zur Anzahl der Nachrichten pro Ordner im Ordner "Wiederherstellbare Elemente": Gibt die Anzahl der Nachrichten an, die jeder Ordner im Ordner "Wiederherstellbare Elemente" enthalten kann, bevor Exchange Online ein Ereignis im Anwendungsereignisprotokoll protokolliert.

- **Maximale Anzahl von Unterordnern pro** Postfachordner: Gibt die maximale Anzahl von Unterordnern an, die in einem Postfachordner erstellt werden können. Der Postfachbesitzer wird keinen neuen Unterordner erstellen können, wenn dieser Grenzwert erreicht ist.

- **Warnung zur Anzahl** der Unterordner pro Postfachordner: Gibt die Anzahl der Unterordner an, die in einem Postfachordner erstellt werden können, bevor Exchange Online eine Warnmeldung an den Postfachbesitzer sendet. Wenn dieses Kontingent erreicht ist, werden einmal am Tag Warnmeldungen gesendet.

- **Maximale Ordnerhierarchietiefe:** Gibt die maximale Anzahl von Ebenen in der Ordnerhierarchie eines Postfachs an. Der Postfachbesitzer wird keine neue Ebene in der Ordnerhierarchie des Postfachordners erstellen können, wenn dieser Grenzwert erreicht ist.

- **Warnung zur Ordnerhierarchietiefe:** Gibt die Anzahl der Ebenen in der Ordnerhierarchie eines Postfachordners an, die erstellt werden können, bevor Exchange Online eine Warnmeldung an den Postfachbesitzer sendet. Wenn dieses Kontingent erreicht ist, werden einmal am Tag Warnmeldungen gesendet.

- **Maximale Anzahl öffentlicher Ordner:** Gibt die maximale Anzahl von öffentlichen Ordnern in der gesamten Hierarchie öffentlicher Ordner an. Wenn diese Grenze erreicht wird, müssen vorhandene öffentliche Ordner gelöscht werden, bevor neue öffentliche Ordner erstellt werden können.

- **Maximale Anzahl von Unterordnern pro** öffentlichem Ordner: Gibt die maximale Anzahl von Unterordnern an, die in einem öffentlichen Ordner erstellt werden können. Neue Unterordner können in einem öffentlichen Ordner nicht erstellt werden, wenn diese Grenze erreicht ist.

- **Warnung zur Anzahl** der Unterordner pro öffentlichem Ordner: Gibt die Anzahl der Unterordner an, die in einem öffentlichen Ordner erstellt werden können, bevor Exchange Online eine Warnmeldung an den Ordnerbesitzer sendet. Falls kein Eigentümer vorhanden ist, werden Warnmeldungen an Benutzer mit Eigentümerberechtigungen geschickt. Wenn dieses Kontingent erreicht ist, werden einmal am Tag Warnmeldungen gesendet.

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
> <sup>1</sup> Dies ist das Speicherkontingent für den Ordner „Wiederherstellbare Elemente", nicht das Kontingent für das gesamte Archivpostfach. Das Speicherkontingent für das Archivpostfach ist für Benutzer mit einer Exchange Online Plan 2-Lizenz oder mit einer Exchange Online Plan 1- und einer Exchange Online-Archivierungslizenz unbegrenzt. Informationen zum Erhöhen des Kontingents für wiederherstellbare Elemente finden Sie unter [Erhöhen des Kontingents für wiederherstellbare Elemente für der In-Situ-Aufbewahrung zugewiesene Postfächer](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>2</sup> Das anfängliche Speicherkontingent für den Ordner "Wiederherstellbare Elemente" in einem Archivpostfach beträgt 100 GB. Wenn die automatisch erweiterte Archivierung aktiviert ist, wird automatisch zusätzlicher Speicher hinzugefügt, wenn die Speicherkapazität für den Ordner „Wiederherstellbare Elemente“ erreicht ist. Weitere Informationen finden Sie unter [Übersicht zur unbeschränkten Archivierung in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Details zur Verfügbarkeit der Automatisch erweiterten Archivierung finden Sie in der [Microsoft 365-Roadmap.](https://go.microsoft.com/fwlink/?LinkId=509914)
> <sup>2</sup> Dies ist ein Speicherlimit. Es handelt sich um eine der Einschränkungen für Postfachform. Für jedes übergeordnete Element können nur 10.000 direkte untergeordnete Ordner verwendet werden. Dies gilt unabhängig von der Migration oder anderen Clients, die Ordner erstellen.

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
> <sup>1</sup> Microsoft empfiehlt, dass nicht mehr als 1.000.000 Nachrichten pro Postfachordner vorhanden sind. > <br/> <sup>2</sup> Dies ist das Speicherkontingent für den Ordner "Wiederherstellbare Elemente", nicht das Kontingent für das gesamte Archivpostfach. Das Speicherkontingent für das Archivpostfach ist für Benutzer mit einer Exchange Online Plan 2-Lizenz oder mit einer Exchange Online Plan 1- und einer Exchange Online-Archivierungslizenz unbegrenzt. Informationen zum Erhöhen des Kontingents für wiederherstellbare Elemente finden Sie unter [Erhöhen des Kontingents für wiederherstellbare Elemente für der In-Situ-Aufbewahrung zugewiesene Postfächer](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold). <br/> <sup>3</sup> Das anfängliche Speicherkontingent für den Ordner "Wiederherstellbare Elemente" in einem Archivpostfach beträgt 100 GB. Wenn die automatisch erweiterte Archivierung aktiviert ist, wird automatisch zusätzlicher Speicher hinzugefügt, wenn die Speicherkapazität für den Ordner „Wiederherstellbare Elemente“ erreicht ist. Weitere Informationen finden Sie unter [Übersicht zur unbeschränkten Archivierung in Office 365](https://go.microsoft.com/fwlink/?linkid=844060). Details zur Verfügbarkeit der Automatisch erweiterten Archivierung finden Sie in der [Microsoft 365-Roadmap.](https://go.microsoft.com/fwlink/?LinkId=509914)

## <a name="message-limits"></a>Nachrichtengrenzwerte

Die folgenden Grenzwerte gelten für sämtliche E-Mails.

- **Beschränkung der Nachrichtengröße:** Nachrichtengrößenbeschränkungen sind erforderlich, um zu verhindern, dass große Nachrichten die Zustellung anderer Nachrichten blockieren und die Dienstleistung für alle Benutzer beeinträchtigen. Diese Beschränkungen umfassen auch Anlagen, und sie gelten organisationsweit für alle Nachrichten (eingehende, ausgehende und interne). Nachrichten, die größer sind, werden nicht zugestellt, und der Absender erhält einen Unzustellbarkeitsbericht. Während die Grenzwerte für die Nachrichtengröße nicht nach oben oder unten oder für die einzelnen Benutzer geändert werden können, können Administratoren auch Transportregeln einrichten, um die maximale Größe einzelner Anlagen zu beschränken. Weitere Informationen finden Sie unter [Microsoft unterstützt größere E-Mail-Nachrichten.](https://go.microsoft.com/fwlink/?linkid=2144144)

    > [!NOTE]
    > Einige E-Mail-Clients haben möglicherweise niedrigere Nachrichtengrößenbeschränkungen oder beschränken die Größe einer einzelnen Dateianlage auf einen Wert, der kleiner als der Grenzwert für die Exchange Online-Nachrichtengröße ist.

- **Größenbeschränkung für** Nachrichtenkopfzeilen: Gibt die maximale Größe aller Nachrichtenkopffelder in einer Nachricht an. Der aktuelle Grenzwert beträgt 256 KB. Wenn die Gesamtgröße aller Nachrichtenköpfe 256 KB überschreitet, lehnt Exchange Online die Nachricht mit dem Fehler "552 5.3.4 Kopfgröße überschreitet feste Maximalgröße" ab. Die Größe des Nachrichtentexts oder der Anlagen wird nicht berücksichtigt. Da die Kopffelder unformatierten Text enthalten, wird die Größe des Kopfes durch die Anzahl der Zeichen in jedem Kopffeld sowie durch die Gesamtanzahl der Kopffelder bestimmt. Jedes Textzeichen belegt 1 Byte.

- **Grenzwert für die Länge des** Betreffs: Die maximale Anzahl von Textzeichen, die in der Betreffzeile einer E-Mail zulässig sind.

- **Grenzwert für Dateianlagen:** Die maximal zulässige Anzahl von Dateianlagen in einer E-Mail-Nachricht. Auch wenn die Gesamtgröße aller Dateianlagen nicht gegen das Nachrichtengrößenlimit verstößt, gibt es dennoch eine Grenze der Anzahl der zulässigen Anlagen in der Nachricht. Dieser Grenzwert wird vom Grenzwert für mehrteiligen Nachrichten gesteuert.

- **Größenbeschränkung für Dateianlage:** Die maximale Dateigröße einer einzelnen Anlage.

    > [!NOTE]
    > Dies ist die maximale Dateigröße einer einzelnen Anlage. Einzelne Clientprogramme, einschließlich Outlook im Web, können die Größe von Anlagen unter diesem Höchstwert begrenzen. Exchange ActiveSync implementiert keine Größenbeschränkungen für Anlagen auf basis einzelner Anlagen. Die Gesamtgröße aller Anlagen an eine Exchange ActiveSync muss kleiner als die Nachrichtengrößenbeschränkung sein.

- **Grenzwert für mehrteilige** Nachrichten: Die maximale Anzahl von Nachrichtentextteilen, die in einer mehrteiligen MIME-Nachricht zulässig sind. Dieser Grenzwert steuert außerdem die maximale Anzahl Dateianlagen, die in einer Nachricht zulässig sind.

- **Grenzwert für die Tiefe eingebetteter** Nachrichten: Die maximale Anzahl weitergeleiteter E-Mail-Nachrichten, die in einer E-Mail zulässig sind.

### <a name="message-limits"></a>Nachrichtengrenzwerte

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Grenzwert für Nachrichtengröße – Outlook|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Grenzwert für Nachrichtengröße – OWA|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|
|Grenzwert für Nachrichtengröße – Outlook für Mac|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|
|Nachrichtengrößenbeschränkung - Migration|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|150 MB <sup>1, 4</sup>|
|Grenzwert für Nachrichtengröße – Outlook für iOS und Android | 33 MB| 33 MB| 33 MB| 33 MB| 33 MB| 33 MB|
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die die Office 365-Nachrichtenverschlüsselung mit neuen Funktionen verwenden)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die die ältere Version der Office 365-Nachrichtenverschlüsselung verwenden)<sup>5</sup>|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Grenzwert für Länge des Betreffs|255 Zeichen|255 Zeichen|255 Zeichen|255 Zeichen|255 Zeichen|255 Zeichen|
|Grenzwert für Dateianlagen|250 Anlagen|250 Anlagen|250 Anlagen|250 Anlagen|250 Anlagen|250 Anlagen|
|Größenlimit für Dateianlagen – Outlook|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Größenlimit für Dateianlagen – OWA |112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|112 MB<sup>3, 6</sup>|
|Größenlimit für Dateianlagen – Outlook für Mac|150 MB|150 MB|150 MB|150 MB|150 MB|150 MB|
|Größenbeschränkung für Dateianlage – Outlook für iOS und Android|33 MB |33 MB |33 MB |33 MB |33 MB |33 MB |
|Grenzwert für mehrteilige Nachrichten|250 Teile|250 Teile|250 Teile|250 Teile|250 Teile|250 Teile|
|Grenzwert für die Tiefe der Nachrichteneinbettung|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|

> [!NOTE]
> <sup>1</sup> Die standardmäßige maximale Nachrichtengröße für Microsoft-Postfächer beträgt 25 MB. Administratoren von Microsoft können einen benutzerdefinierten Grenzwert zwischen 1 MB und 150 MB festlegen. Die Größe der Nachricht, die Sie senden oder empfangen können, ist jedoch auch davon abhängig, was in Ihrem E-Mail-Client oder in Ihrer E-Mail-Lösung unterstützt wird. Weitere Informationen zum Anpassen der maximal zulässigen Nachrichtengröße für Ihre Organisation finden Sie unter [Microsoft unterstützt größere E-Mail-Nachrichten.](https://go.microsoft.com/fwlink/?linkid=2144144) 
<br/> <sup>2</sup> Sie können bis zu 150 MB Nachrichten zwischen Benutzern senden und empfangen (wobei die Nachricht niemals die Microsoft-Rechenzentren verlässt). Nachrichten, die außerhalb der Microsoft-Rechenzentren geroutet werden, unterliegen einer zusätzlichen Übersetzungscodierung von 33 %, in diesem Fall beträgt die maximale Nachrichtengröße 112 MB. <br/> 
<sup>3</sup> OWA bietet die Möglichkeit, dass Ihre Nachricht der Codierungssteigerung von 33 % unterliegt, und schränkt die Größe der Nachricht ein, die Sie senden können, auf 25 % weniger als die konfigurierte Einstellung. Wenn Sie beispielsweise die Einstellungen für eine maximale Nachrichtengröße von 100 MB anpassen, können Sie Nachrichten mit bis zu 75 MB senden. 
<br/> <sup>4</sup> Die Größe der Nachrichten, die in Exchange Online verschoben werden sollen, wird von Exchange Online berechnet. Ältere Exchange-Versionen als Exchange Server 2013 melden möglicherweise eine geringere Elementgröße. Dieser Grenzwert gilt für verschiebenbasierte Migrationen mit einem beliebigen unterstützten Exchange-Postfachreplikationsdienst. Andere Migrationsmethoden (einstufig, mehrstufig, IMAP, PST-Datei) und andere Tools von Drittanbietern werden durch allgemeine Nachrichtengröße begrenzt. <br/> 
<sup>5</sup> Informationen zu OME mit neuen Funktionen finden Sie unter Einrichten neuer Office 365-Nachrichtenverschlüsselungsfunktionen, die auf [Azure Information Protection aufgebaut sind.](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e) <br/> 
<sup>6 Klassische</sup> Dateianlagen haben ein Limit von 112 MB, #A0 können jedoch bis zu 2 GB groß sein.


### <a name="message-limits-across-standalone-options"></a>Nachrichtengrenzwert in eigenständigen Produkten

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Grenzwert für Nachrichtengröße – Outlook|10 MB<sup>4</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>1, 2</sup>|150 MB<sup>2</sup>|
|Grenzwert für Nachrichtengröße – OWA|10 MB<sup>4</sup>|112 MB<sup>1, 3</sup>|112 MB<sup>1, 3</sup>|150 MB<sup>1, 2</sup>|
|Grenzwert für Nachrichtengröße – Outlook für Mac|10 MB<sup>4</sup>|150 MB|150 MB||
|Nachrichtengrößenbeschränkung - Migration|Nicht zutreffend|150 MB <sup>5</sup>|150 MB <sup>5</sup>|150 MB <sup>5</sup>|
|Grenzwert für Nachrichtengröße – Outlook für iOS und Android |25 MB |33 MB |33 MB |33 MB |
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die die Office 365-Nachrichtenverschlüsselung mit neuen Funktionen verwenden)<sup>6</sup>|150 MB|150 MB|150 MB|150 MB|
|Maximale Größe für verschlüsselte Nachrichten (für Abonnenten, die eine ältere Version der Office 365-Nachrichtenverschlüsselung verwenden)<sup>6</sup>|25 MB|25 MB|25 MB|25 MB|
|Grenzwert für Länge des Betreffs|255 Zeichen|255 Zeichen|255 Zeichen|255 Zeichen|
|Grenzwert für Dateianlagen|1024 attachments<sup>4</sup>|250 Anlagen|250 Anlagen|250 Anlagen|
|Größenlimit für Dateianlagen – Outlook|35 MB<sup>4</sup>|150 MB|150 MB|150 MB|
|Größenlimit für Dateianlagen – OWA|35 MB<sup>4</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|112 MB<sup>3</sup>|
|Größenlimit für Dateianlagen – Outlook für Mac|35 MB<sup>4</sup>|150 MB|150 MB|35 MB|
|Größenbeschränkung für Dateianlage – Outlook für iOS und Android|25 MB |33 MB|33 MB|33 MB|
|Grenzwert für mehrteilige Nachrichten|250 Teile|250 Teile|250 Teile|250 Teile|
|Grenzwert für die Tiefe der Nachrichteneinbettung|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|30 eingebettete Nachrichten|

> [!NOTE]
> <sup>1</sup> Microsoft-Administratoren können einen benutzerdefinierten Grenzwert zwischen 1 MB und 150 MB festlegen. Die Größe der Nachricht, die Sie senden oder empfangen können, ist jedoch auch davon abhängig, was in Ihrem E-Mail-Client oder in Ihrer E-Mail-Lösung unterstützt wird. Weitere Informationen zum Anpassen der maximal zulässigen Nachrichtengröße für Ihre Organisation finden Sie unter [Microsoft unterstützt größere E-Mail-Nachrichten.](https://go.microsoft.com/fwlink/?linkid=2144144) <br/> <sup>2</sup> Sie können bis zu 150 MB Nachrichten zwischen Benutzern senden und empfangen (wobei die Nachricht niemals die Microsoft-Rechenzentren verlässt). Nachrichten, die außerhalb der Microsoft-Rechenzentren geroutet werden, unterliegen einer zusätzlichen Übersetzungscodierung von 33 %, in diesem Fall beträgt die maximale Nachrichtengröße 112 MB. <br/> 
<sup>3</sup> OWA bietet die Möglichkeit, dass Ihre Nachricht der Codierungssteigerung von 33 % unterliegt, und schränkt die Größe der Nachricht ein, die Sie senden können, auf 25 % weniger als die konfigurierte Einstellung. Wenn Sie beispielsweise die Einstellungen für eine maximale Nachrichtengröße von 100 MB anpassen, können Sie Nachrichten mit bis zu 75 MB senden. <br/> 
<sup>4</sup> Dies ist der Standardgrenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. <br/> 
<sup>5</sup> Die Größe von Nachrichten, die in Exchange Online verschoben werden sollen, wird von Exchange Online berechnet. Ältere Exchange-Versionen als Exchange Server 2013 melden möglicherweise eine geringere Elementgröße. <br/> 
<sup>6</sup> Informationen zu OME mit neuen Funktionen finden Sie unter Einrichten neuer Office 365-Nachrichtenverschlüsselungsfunktionen, die auf [Azure Information Protection aufgebaut sind.](https://support.office.com/article/7ff0c040-b25c-4378-9904-b1b50210d00e)

## <a name="receiving-and-sending-limits"></a>Empfangs- und Sendegrenzen

Empfangs- und Sendegrenzen werden angewendet, um Spam und Massen-E-Mail-Würmer oder -Viren zu bekämpfen. Diese Grenzwerte tragen dazu bei, die Integrität unserer Systeme sowie unsere Benutzer zu schützen.

### <a name="receiving-limits"></a>Empfangsgrenzen

Empfangsgrenzen gelten für die Anzahl von Nachrichten, die ein Benutzer, eine Gruppe oder ein öffentlicher Ordner pro Stunde empfangen kann. Dies gilt sowohl für Nachrichten, die aus dem Internet als auch von lokalen Servern empfangen werden. Wird die Empfangsgrenze überschritten, erhalten die Absender von E-Mails an dieses Postfach einen Unzustellbarkeitsbericht mit der Information, dass das Postfach den zulässigen Schwellenwert für die Anzahl zugestellter Nachrichten überschritten hat. Nach einer Stunde wird die Grenze zurückgesetzt, und das Postfach kann wieder Nachrichten empfangen.

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard Office | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Empfangene Nachrichten|3.600 Nachrichten pro Stunde|3.600 Nachrichten pro Stunde|3.600 Nachrichten pro Stunde|3.600 Nachrichten pro Stunde|3.600 Nachrichten pro Stunde|3600 Nachrichten pro Stunde|

### <a name="sending-limits"></a>Sendegrenzen

Sendegrenzen gelten für die Anzahl von Empfängern, die Anzahl von Nachrichten und die Anzahl von Empfängern pro Nachricht, die ein Benutzer aus seinem Exchange Online-Konto senden kann.

> [!NOTE]
> Für im Adressbuch einer Organisation gespeicherte Verteilergruppen wird die Gruppe als ein Empfänger betrachtet. Für Verteilergruppen, die im Ordner "Kontakte" eines Postfachs gespeichert sind, werden die Mitglieder der Gruppe einzeln gezählt.

- **Empfängerratengrenzwert:** Um die Zustellung unerwünschter Massennachrichten zu verhindern, verfügt Exchange Online über Empfängerbeschränkungen, die benutzer und Anwendungen daran hindern, große Mengen an E-Mails zu senden. Diese Grenzwerte gelten pro Benutzer für alle ausgehenden und internen Nachrichten.

    > [!NOTE]
    > Exchange Online-Kunden, die seriöse kommerzielle E-Mails versenden müssen (z. B. Kunden-Newsletter), sollten einen Drittanbieter in Anspruch nehmen, der sich auf diese Dienste spezialisiert.

- **Empfängergrenzwert:** Dies ist die maximale Anzahl von Empfängern, die in den Feldern "An:", "Cc:" und "Bcc:" für eine einzelne E-Mail zulässig sind.

    > [!NOTE]
    > Eine Verteilerliste, die im freigegebenen Adressbuch der Organisation gespeichert ist, zählt in Bezug auf den Empfängerratengrenzwert und die Empfängereinschränkung als ein Empfänger. In einer persönlichen Verteilerliste wird jeder Empfänger separat gezählt.

- **Empfängerproxyadressenlimit:** Der Grenzwert für die Empfängerproxyadresse ist die maximale Anzahl von Aliasen (E-Mail-Adressen), die ein Empfängerpostfach haben kann. 

- **Nachrichtenrategrenzwert:** Nachrichtenrategrenzwerte bestimmen, wie viele Nachrichten ein Benutzer über sein Exchange Online-Konto innerhalb eines bestimmten Zeitraums senden kann. Dieser Grenzwert verhindert, dass systemressourcen durch einen einzelnen Absender überschreitet werden. Wenn ein Benutzer Nachrichten mit einer Häufigkeit übermittelt, welche die SMTP-Clientübermittlungsgrenze überschreitet, werden die Nachrichten abgelehnt, und der Client muss es erneut versuchen.

#### <a name="sending-limits"></a>Sendegrenzen

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Empfängersatzgrenzwert<sup>1</sup>|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|10.000 Empfänger pro Tag|
|<sup>Empfängergrenzwert 2</sup>|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|Anpassbar bis zu 1.000 Empfänger|
|Grenzwert für Empfängerproxyadresse|400|400|400|400|400|400|
|Nachrichtenrategrenzwert<sup>3</sup>|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|

> [!NOTE]
> <sup>1</sup> Nachdem der Grenzwert für die Empfängerrate erreicht wurde, können Nachrichten erst aus dem Postfach gesendet werden, wenn die Anzahl der Empfänger, die in den letzten 24 Stunden Nachrichten gesendet haben, unter den Grenzwert fällt. Beispielsweise sendet ein Benutzer um 09:00 Uhr eine E-Mail-Nachricht an 5000 Empfänger, dann um 10:00 Uhr eine weitere Nachricht an 2500 Empfänger und dann um 11:00 Uhr eine weitere Nachricht an 2500 Empfänger und erreicht den Grenzwert von 10.000 Nachrichten. Der Benutzer kann nachrichten erst um 09:00 Uhr am nächsten Tag erneut senden.  
> <sup>2</sup> Sie können empfängerbeschränkungen zwischen 1 und 1000 für vorhandene Postfächer und für neue Postfächer anpassen, die in Zukunft erstellt werden. Bearbeiten Sie die Empfängerbeschränkung für vorhandene Postfächer einzeln oder massenverteilt über das Exchange Admin Center, und passen Sie die Standardeinstellung für neue Postfächer über Remote PowerShell an. Weitere Informationen finden Sie unter [Anpassbare Empfängerbeschränkungen in Office 365.](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228)  
> <sup>3</sup> Wenn Volumes für ausgehende Nachrichten das Nachrichtenratelimit überschreiten, werden alle Überschreitungen der Nachrichtenübermittlung gedrosselt und nacheinander auf die folgenden Minuten übertroffen. Dadurch wird in der Regel das Konto des Absenders nicht blockiert, exchange Online ist jedoch nicht für Massensendungsszenarien geeignet. Für diesen Verwendungsfall werden stattdessen die Optionen 2 und [3](https://docs.microsoft.com/exchange/mail-flow-best-practices/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-microsoft-365-or-office-365) empfohlen.

#### <a name="sending-limits-across-standalone-options"></a>Sendegrenzwerte bei Optionen für eigenständige Pläne

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Empfängerratengrenzwert|Keine Beschränkung<sup>1</sup>|10.000 Empfänger pro Tag<sup>2</sup>|10.000 Empfänger pro Tag<sup>2</sup>|10.000 Empfänger pro Tag<sup>2</sup>|
|Empfängergrenzwert|1000 Empfänger<sup>1</sup>|1000 Empfänger|1000 Empfänger|1000 Empfänger|
|Grenzwert für Empfängerproxyadresse|400|400|400|400|
|Nachrichtenratengrenzwert|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|30 Nachrichten pro Minute|

> [!NOTE]
> <sup>1</sup> Dies ist der standardmäßige Grenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern.<br/>
<sup>2</sup> Nachdem der Grenzwert für die Empfängerrate erreicht wurde, können Nachrichten erst aus dem Postfach gesendet werden, wenn die Anzahl der Empfänger, die in den letzten 24 Stunden Nachrichten gesendet haben, unter den Grenzwert fällt. Beispielsweise sendet ein Benutzer um 09:00 Uhr eine E-Mail-Nachricht an 5000 Empfänger, dann um 10:00 Uhr eine weitere Nachricht an 2500 Empfänger und dann um 11:00 Uhr eine weitere Nachricht an 2500 Empfänger und erreicht den Grenzwert von 10.000 Nachrichten. Der Benutzer kann nachrichten erst um 09:00 Uhr am nächsten Tag erneut senden.

## <a name="reporting-and-message-trace-limits"></a>Grenzwerte für Berichterstellung und Nachrichtenablaufverfolgung

Informationen zu Grenzwerten für Berichterstellung und Nachrichtenverfolgung finden Sie im Abschnitt "Verfügbarkeit und Latenz von Daten in Berichterstellung und Nachrichtenverfolgung" [in Exchange Online Protection](https://go.microsoft.com/fwlink/p/?LinkId=394248).

## <a name="retention-limits"></a>Aufbewahrungsgrenzwerte

Mit diesen Grenzwerten wird gesteuert, für welchen Zeitraum auf Elemente in bestimmten Ordnern im Posteingang zugegriffen werden kann.

- **Aufbewahrungszeitraum des Ordners**"Gelöschte Elemente": Die maximale Anzahl von Tagen, die Elemente im Ordner "Gelöschte Elemente" verbleiben können, bevor sie automatisch entfernt werden.

- **Aufbewahrungszeitraum für** Elemente, die aus dem Ordner "Gelöschte Elemente" entfernt wurden: Die maximale Anzahl von Tagen, die aus dem Ordner "Gelöschte Elemente" entfernte Elemente aufbewahrt werden, bevor sie endgültig gelöscht werden.

- **Aufbewahrungszeitraum des** Junk-E-Mail-Ordners: Die maximale Anzahl von Tagen, die Elemente im Junk-E-Mail-Ordner verbleiben können, bevor sie automatisch entfernt werden.

> [!NOTE]
> Ein soft-deleted user mailbox &mdash; a mailbox deleted using the Microsoft 365 admin center or the Remove-Mailbox cmdlet in Exchange Online PowerShell and that is still in the Azure Active Directory recycle bin is &mdash; recoverable within 30 days.

### <a name="retention-limits"></a>Aufbewahrungsgrenzwerte

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Aufbewahrungszeitraum des Ordners "Gelöschte Elemente"|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|Keine Beschränkung<sup>1</sup>|
|Aufbewahrungszeitraum für Elemente, die aus dem Ordner "Gelöschte Elemente" entfernt wurden|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|14 Tage<sup>1</sup>|
|Aufbewahrungszeitraum des Ordners "Junk-E-Mail"|30 Tage|30 Tage|30 Tage|30 Tage|30 Tage|30 Tage|

> [!NOTE]
> <sup>1</sup> Dies ist der Standardwert für Microsoft 365-Organisationen. Ein Administrator kann diesen Grenzwert für Postfächer in seiner Organisation auf maximal 30 Tage ändern.

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

- **Maximale Anzahl von Verteilergruppenmitgliedern:** Die Gesamtzahl der Empfänger wird nach der Erweiterung der Verteilergruppe bestimmt.

- **Senden von Nachrichten an große Verteilergruppen** beschränken: Verteilergruppen, die die durch diesen Grenzwert angegebene Anzahl von Mitgliedern enthalten, müssen Zustellungsverwaltungs- oder Nachrichtengenehmigungsoptionen konfiguriert haben. In der Zustellungsverwaltung kann eine Liste von Absendern angegeben werden, die Nachrichten an die Verteilergruppe senden dürfen. Für die Nachrichtengenehmigung werden ein oder mehrere Moderatoren angegeben, die alle an die Verteilergruppe gesendeten Nachrichten genehmigen müssen.

- **Maximale Nachrichtengröße für** große Verteilergruppen: Wenn eine Nachricht an 5.000 oder mehr Empfänger gesendet wird, darf die Nachrichtengröße diesen Grenzwert nicht überschreiten. Übersteigt die Nachrichtengröße den Grenzwert, wird die Nachricht nicht zugestellt, und der Absender erhält einen Unzustellbarkeitsbericht (Non-Delivery Report, NDR).

### <a name="distribution-group-limits"></a>Verteilergruppen-Grenzwerte

| Feature | Microsoft 365 Business Basic | Microsoft 365 Business Standard | Office 365 Enterprise E1 | Office 365 Enterprise E3 | Office 365 Enterprise E5 | Office 365 Enterprise F3 |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Maximale Anzahl Mitglieder einer Verteilergruppe<sup>1</sup>|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|
|Grenzwert für das Senden von Nachrichten an große Verteilergruppe|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|
|Obergrenze für Nachrichten an Verteilergruppen mit 5.000 bis 99.999 Mitgliedern|25 MB|25 MB|25 MB|25 MB|25 MB|25 MB|
|Obergrenze für Nachrichten an Verteilergruppen mit 100.000 Mitgliedern|5 MB|5 MB|5 MB|5 MB|5 MB|5 MB|
|Maximale Anzahl von Verteilergruppenbesitzern|10 |10 |10 |10 |10 |10 |
|Maximale Anzahl von Gruppen, die ein Benutzer erstellen kann|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|300,000<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Wenn Sie Azure Active Directory DirSync verwenden, beträgt die maximale Anzahl von Verteilergruppenmitgliedern, die sie vom lokalen Active Directory mit Azure Active Directory synchronisieren können, 15.000. Wenn Sie Azure AD Connect verwenden, beträgt die Anzahl 50.000. <br/> <sup>2</sup> Dieser Grenzwert gilt auch für Administratoren.

### <a name="distribution-group-limits-across-standalone-options"></a>Grenzwerte für Verteilergruppen in eigenständigen Produkten

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Maximale Anzahl Mitglieder einer Verteilergruppe|100.000 Mitglieder<sup>1</sup>|100.000 Mitglieder|100.000 Mitglieder|100.000 Mitglieder|
|Grenzwert für das Senden von Nachrichten an große Verteilergruppe|5.000 oder mehr Mitglieder<sup>1</sup>|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|5.000 oder mehr Mitglieder|
|Maximale Anzahl von Verteilergruppenbesitzern|10 |10 |10 |10 |
|Maximale Anzahl von Gruppen, die ein Benutzer erstellen kann|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|250<sup>2</sup>|

> [!NOTE]
> <sup>1</sup> Dies ist der standardmäßige Grenzwert für Exchange Server 2013-Organisationen. Administratoren können diesen Wert für ihre Organisation ändern. <br/> <sup>2</sup> Dieser Grenzwert gilt auch für Administratoren.

## <a name="journal-transport-and-inbox-rule-limits"></a>Journal-, Transport- und Posteingangsregelgrenzen

Die folgende Liste enthält Grenzwerte, die für Journalregeln, Transportregeln (auch als organisationsweite Regeln bezeichnet) und Für Posteingangsregeln gelten. Posteingangsregeln werden von einzelnen Benutzern festgelegt und auf Nachrichten angewendet, die vom Postfach des entsprechenden Benutzers gesendet und empfangen werden.

- **Maximale Anzahl von Journalregeln:** Die maximale Anzahl von Journalregeln, die in der Organisation vorhanden sein können.

- **Maximale Anzahl von Transportregeln:** Die maximale Anzahl von Regeln, die in der Organisation vorhanden sein können.

- **Maximale Größe einer einzelnen Transportregel:** Die maximale Anzahl von Zeichen, die in einer einzelnen Transportregel verwendet werden können. The characters are used in the conditions, exceptions, and actions.

- **Zeichenlimit für alle regulären Ausdrücke,** die in allen Transportregeln verwendet werden: Die Gesamtzahl der verwendeten Zeichen, einschließlich aller regulären Ausdrücke in allen Transportregelbedingungen und Ausnahmen in der Organisation. Sie können wenige Regeln verwenden, in denen lange und komplexe reguläre Ausdrücke verwendet werden, oder Sie können viele Regeln verwenden, in denen einfache reguläre Ausdrücke verwendet werden.

- **Überprüfungsgrenzwerte** für Anlageninhalte: Mit den Transportregelbedingungen können Sie den Inhalt von Nachrichtenanlagen untersuchen, aber nur die ersten 1 MB des aus einer Anlage extrahierten Texts werden überprüft. Dieser Grenzwert von 1 MB bezieht sich auf den aus der Anlage extrahierten Text, nicht auf die Dateigröße der Anlage. Beispielsweise kann eine 2 MB große Datei weniger als 1 MB Text enthalten, sodass der ganze Text überprüft wird.

- **Maximale Anzahl von** Empfängern, die einer Nachricht von allen Transportregeln hinzugefügt werden: Wenn eine Nachricht von unterschiedlichen Transportregeln verwendet wird, kann der Nachricht nur eine begrenzte Anzahl von Empfängern hinzugefügt werden. Nachdem die Grenze erreicht wurde, werden verbleibende Empfänger der Nachricht nicht hinzugefügt. Außerdem können einer Nachricht von einer Transportregel keine Verteilergruppen hinzugefügt werden.

- **Weiterleitungsgrenzwert:** Die maximale Anzahl von Empfängern, die für eine Posteingangs- oder Transportregel mit einer Umleitungsaktion konfiguriert werden können. Sollte eine Regel festgelegt werden, eine Nachricht an mehr als diese Anzahl von Empfängern weiterzuleiten, würde diese Regel nicht angewendet werden, und jede regelkonforme Nachricht würde nicht an die in dieser Regel aufgelisteten Empfänger weitergeleitet werden.
    
- **Anzahl der Umleiten einer** Nachricht: Gibt an, wie oft eine Nachricht basierend auf Posteingangsregeln automatisch umgeleitet, weitergeleitet oder beantwortet wird. Benutzer A verfügt beispielsweise über eine Posteingangsregel, die Nachrichten basierend auf dem Absender an Benutzer B umleitiert. Benutzer B verfügt über eine Posteingangsregel, mit der Nachrichten basierend auf Schlüsselwörtern in der Betreffzeile an Benutzer C weitergeleitet werden. Wenn eine Nachricht beide Bedingungen erfüllt, wird die Nachricht nur an Benutzer B gesendet. Er wird nicht an Benutzer C weitergeleitet, da nur eine Umleitung zulässig ist. In diesem Fall wird die Nachricht gelöscht, ohne einen Unzustellbarkeitsbericht (Non-Delivery Report, NDR) an Benutzer B zu senden, der angibt, dass die Nachricht nicht an Benutzer C zugestellt wurde. Wir verwenden den X-MS-Exchange-Inbox-Rules-Loop-Header, um zu ermitteln, wie oft eine Nachricht umgeleitet wurde. Diese Kopfzeile bleibt auch über Die Grenzen der Organisation hinweg bestehen.

- **Anzahl der Umleiten einer Nachricht** durch Transportregeln: Gibt an, wie oft eine Nachricht basierend auf Transportregeln umgeleitet wird. Die Exchange-Organisation Tailspin Toys verfügt beispielsweise über eine Transportregel, um jede Nachricht, die an Benutzer A gesendet wurde, an Benutzer B umzuleiten, der sich in der Exchange-Organisation Contoso befindet. Innerhalb der #A0 Contoso gibt es eine Transportregel zum Umleiten jeder Nachricht, die an Benutzer B gesendet wurde, an Benutzer C, der sich in der #A1 A. Datum Corporation befindet. In diesem Fall wird die Nachricht gelöscht, und es wird ein Unzustellbarkeitsbericht (Non-Delivery Report, NDR) mit Statuscode angezeigt, und die Nachricht *550 5.7.128 TRANSPORT wird abgelehnt. REGELN. RejectMessage; Die Anzahl der Transportregeln wurde überschritten, und die abgelehnte* Nachricht wird an Benutzer A gesendet. Wir verwenden den X-MS-Exchange-Transport-Rules-Loop-Header, um zu bestimmen, wie oft eine Nachricht von Transportregeln umgeleitet wurde. Diese Kopfzeile bleibt auch über Die Grenzen der Organisation hinweg bestehen.

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
|Anzahl der Umleiten einer Nachricht durch Transportregeln|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|
|Anzahl der Umleitungen einer Nachricht|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|1 Umleitung|
|Posteingangsregel|256 kb<sup>1</sup>|256 kb<sup>1</sup>|256 kb<sup>1</sup>|256 kb<sup>1</sup>|256 kb<sup>1</sup>|256 kb<sup>1</sup>|

> [!NOTE]
> <sup>1</sup> Wenn ein Postfach zu Exchange Online migriert wurde, kann der Grenzwert für Posteingangsregel auf den Wert festgelegt werden, der niedriger als der Standardmäßige EXO-Wert ist. In diesem Fall kann der Wert der Posteingangsregel erhöht werden. Anweisungen finden Sie unter [Ändern des von Posteingangsregeln in Exchange Online verwendeten Speicherplatzes.](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-on-the-web/increase-the-space-used-by-inbox-rules) 

### <a name="journal-transport-and-inbox-rule-limits-across-standalone-options"></a>Journal-, Transport- und Posteingangsregelbeschränkungen für eigenständige Optionen

| Feature | Exchange Server 2013 | Exchange Online Plan 1 | Exchange Online Plan 2 | Exchange Online-Kiosk |
|:-----|:-----|:-----|:-----|:-----|
|Maximale Anzahl von Journalregeln|Unbegrenzt|50 Regeln|50 Regeln|50 Regeln|
|Maximale Anzahl Transportregeln|Keine Begrenzung|300 Regeln|300 Regeln|300 Regeln|
|Maximale Größe einer einzelnen Transportregel|40 KB|8 KB|8 KB|8 KB|
|Zeichenbegrenzung für reguläre Ausdrücke in allen Transportregeln|Keine Begrenzung|20 KB|20 KB|20 KB|
|Maximale Anzahl der aufgrund alle Transportregeln zu einer Nachricht hinzugefügten Empfänger|Keine Begrenzung|100 Empfänger|100 Empfänger|100 Empfänger|
|Weiterleitungsgrenzwert|Keine Begrenzung|10 Empfänger|10 Empfänger|10 Empfänger|
|Anzahl der Umleitungen einer Nachricht|3 Umleitungen|1 Umleitung|1 Umleitung|1 Umleitung|
|Anzahl der Umleiten einer Nachricht durch Transportregeln|Keine Begrenzung|1 Umleitung|1 Umleitung|1 Umleitung|

## <a name="moderation-limits"></a>Moderationsgrenzwerte

Diese Grenzwerte steuern die Moderationseinstellungen für die Nachrichtengenehmigung, die auf Verteilergruppen und Transportregeln angewendet wird.

- **Maximale Größe des** Vermittlungspostfachs: Wenn das Vermittlungspostfach diesen Grenzwert überschreitet, werden Nachrichten, die Moderation erfordern, in einem Unzustellbarkeitsbericht an den Absender zurückgegeben.

- **Maximale Anzahl von Moderatoren:** Die maximale Anzahl von Moderatoren, die Sie einer einzelnen moderierten Verteilergruppe zuweisen oder die einer Nachricht mithilfe einer einzelnen Transportregel hinzugefügt werden können. Note that you can't specify a distribution group as a moderator.

- **Ablauf für Nachrichten, die auf Moderation warten:** Standardmäßig läuft eine Nachricht, die auf Moderation wartet, nach zwei Tagen ab. Die Verarbeitung abgelaufener moderierter Nachrichten wird jedoch jeweils nach sieben Tagen durchgeführt. Dies bedeutet, dass eine moderierte Nachricht in einem Zeitraum von zwei bis neun Tagen jederzeit ablaufen kann.

- **Maximale Rate für abgelaufene** Moderationsbenachrichtigungen: Dieser Grenzwert legt die maximale Anzahl von Benachrichtigungen für abgelaufene moderierte Nachrichten in einem Zeitraum von einer Stunde fest. Der Grenzwert gilt für jede Postfachdatenbank im Datencenter.

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

- **Exchange ActiveSync Gerätelimit:** Die maximale Anzahl Exchange ActiveSync Geräte pro Postfach.

- **Exchange ActiveSync Gerätelöschgrenzwert:** Die maximale Anzahl Exchange ActiveSync Geräte, die ein Exchange-Administrator in einem einzelnen Monat löschen kann.

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
