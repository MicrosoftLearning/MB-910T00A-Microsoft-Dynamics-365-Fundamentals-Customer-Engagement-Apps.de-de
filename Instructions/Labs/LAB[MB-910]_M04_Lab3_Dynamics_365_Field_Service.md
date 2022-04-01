---
lab:
  title: 'Lab 4.3: Dynamics 365 Field Service Capstone-Lab'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
ms.openlocfilehash: f3a0b281cf2f6b342b789bffa977d57de8b9dcf6
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908905"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>Modul 4: Grundlegende Informationen zu Dynamics 365 for Field Service
========================

## <a name="practice-lab-43---dynamics-365-field-service-capstone-lab"></a>Übungs-Lab 4.3 - Dynamics 365 Field Service Capstone-Lab

## <a name="lab-scenario"></a>Übungsszenario

Das Unternehmen ABC spezialisiert sich auf die Herstellung, den Vertrieb, die Installation und die Wartung von Sicherheitsausrüstung. Zu den Produkten des Unternehmens gehören Sicherheitskameras für Innen- und Außenbereiche, Feuchtigkeitssensoren, Brandmelder, Überwachungsdienste und mehr. 

Das Unternehmen ABC nutzt die Dynamics 365-Anwendungen, um mit seinen Kunden in verschiedenen Bereichen vom Vertrieb bis hin zum Service zu interagieren. 

**Vertrieb und Marketing**

Das Unternehmen ABC spricht seine Privatkunden direkt über gezielte Marketingkampagnen an. Die Kunden werden anhand ihrer Stadt und von anderen Faktoren angesprochen. Das Marketingmaterial wird per E-Mail verschickt, und der Kontaktverlauf hängt von der Interaktion mit der E-Mail ab. 

Einige der kleineren Produkte des Unternehmens werden im Einzelhandel verkauft, aber die meisten Produkte werden direkt von internen Vertriebsmitarbeitern an die Verbraucher verkauft.

Intern konzentriert sich das Unternehmen auf zwei Schlüsselbereiche: 

- **Privatkunden:** Privatkunden kaufen normalerweise entweder einzelne Komponenten oder eine komplette Heimlösung. Diese Vertriebszyklen sind normalerweise kürzer und entstehen aus sozialen Netzwerken, Websites, Empfehlungen oder aus direkten Kontakten von Interessenten. Da sich Privatkunden normalerweise für bestimmte Produkte oder kleinere Installationen interessieren, dauern ihre Vertriebszyklen meistens nur einige Tage oder Wochen. 

- **Unternehmenskunden:** Vertriebsmitarbeiter für Unternehmen konzentrieren sich auf Kunden, die spezielle und maßgeschneiderte Unternehmenslösungen brauchen. Unternehmensverkäufe umfassen oft mehrere Standorte, die miteinander kommunizieren, und oft sind für den Projektabschluss mehrere Ressourcen erforderlich. Diese Vertriebszyklen dauern meistens länger und sind wesentlich komplexer. 

Es ist wichtig, dass die Vertriebsmitarbeiter bei der Interaktion mit ihren Kunden von ABC alle erforderlichen Tools, Ressourcen und Anleitungen zur Verfügung haben, egal mit welchem Segment sie sich befassen. 

**Systeminstallation:**

Der Installationsprozess für die verkaufte Sicherheitsausrüstung hängt vom Typ des Käufers ab. 

- **Privatkunden:** Installationen für Privatkunden dauern meistens weniger als einen Tag und werden daher von internen Mitarbeitern erledigt. Nach Abschluss des Verkaufs wird ein Arbeitsauftrag erstellt, und ein qualifizierter Techniker wird identifiziert und für die Installation eingeplant. 

- **Unternehmenskunden:** Installationen in Unternehmen können Monate dauern, und manchmal ist ein Projektmanager erforderlich, um den alltäglichen Betrieb zu koordinieren. Dieser Projektmanager erstellt Projektpläne, definiert Projektteams und plant den Einsatz von Ressourcen. 

**Kundendienst und Support:**

Im Anschluss an die Installation der Systeme bietet ABC seinen Kunden Supportservices an. Wenn bei einem Kunden ein Problem auftritt, kann er sich an den Kundendienst wenden. Ein Agent wird versuchen, das Problem gemeinsam mit dem Kunden remote zu lösen. Falls das Problem nicht remote gelöst werden kann, eskaliert der Support-Agent das Problem zu einem Arbeitsauftrag, der geplant und von einem qualifizierten Außendiensttechniker bearbeitet wird. 

## <a name="objectives"></a>Ziele

Es gibt drei verschiedene Szenarien, in denen das Unternehmen ABC Techniker entsendet, um Arbeiten vor Ort beim Kunden zu erledigen. 

- Wenn ein neues Sicherheitssystem gekauft wurde und installiert werden muss.

- Wenn ein Helpdesk-Agent ein Problem eines Kunden nicht remote beheben kann.

- Wenn ein Kunde das Unternehmen direkt kontaktiert, um einen Service vor Ort anzufordern. 

Vor Kurzem hat der Kunde „Active Transport, Inc.“ den Support wegen eines Problems mit einer Kamera im Sicherheitssystem des Kunden kontaktiert. Der Helpdesk-Techniker konnte das Problem nicht remote beheben, daher muss ein Außendiensttechniker entsendet werden. In diesem Szenario führen Sie die folgenden Aufgaben aus:

- Anfragedatensatz zu einem Arbeitsauftrag konvertieren

- Arbeitsauftrag planen

- Arbeitsauftrag mit der mobilen App auflösen 

## <a name="lab-setup"></a>Lab-Einrichtung

  - **Geschätzte Dauer**: 45 Minuten

## <a name="instructions"></a>Anweisungen

## <a name="exercise-1-create-a-case-and-escalate-to-a-work-order"></a>Übung 1: Anfrage erstellen und zu einem Arbeitsauftrag eskalieren 

### <a name="task-1-create-a-case-record"></a>Aufgabe 1: Anfragedatensatz erstellen

1. Öffnen Sie die **Dynamics 365 Field Service**-Anwendung, falls noch nicht geschehen. 

2. Wählen Sie **Anfragen** in der Navigation auf der linken Seite des Bildschirms aus. 

3. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um einen neuen Anfragedatensatz zu erstellen.

4. Vervollständigen Sie den Anfragedatensatz wie folgt:

    - **Anfragetitel:** Kamera funktioniert nicht

    - **Kunde:** Best For You Organics Company

    - **Ursprung:** Telefon

    Speichern Sie den Eintrag.

5. Wählen Sie die Registerkarte **Außendienst** aus.

6. Wählen Sie unter **Vorfalltyp** den Wert **Kamera funktioniert nicht** aus. (Neu erstellen)

7. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Speichern und schließen** aus, um den Anfragedatensatz zu speichern und zu schließen. 

 

### <a name="task-2-manually-create-a-word-order"></a>Aufgabe 2: Arbeitsauftrag manuell erstellen

Wir werden später zu Ihrem erstellten Anfragedatensatz zurückkehren. Zunächst werden wir uns ansehen, wie Sie einen Arbeitsauftrag manuell erstellen. 

 

1. Wählen Sie links im Navigationsbereich die Option **Arbeitsaufträge** aus.

2. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um einen neuen Arbeitsauftrag zu erstellen.

3. Füllen Sie die Details des Arbeitsauftrags wie folgt aus:

    - **Dienstkonto:** Margie's Travel

    - **Preisliste:** Office 365 US (Beispiel)

    - **Arbeitsauftragstyp:** Dienst-

    - **Steuerpflichtig:** Keine

    Speichern Sie den Datensatz, und weisen Sie den primären Vorfalltyp zu.

    - **Primärer Vorfalltyp:** Lüfter ausgefallen (Neu erstellen)

4. Notieren Sie sich die Arbeitsauftragsnummer, um später überprüfen zu können, ob Sie den richtigen Arbeitsauftrag bearbeiten. 

5. Wählen Sie die Registerkarte **Einstellungen** aus.

6. Legen Sie im Feld **Servicegebiet** den Wert **WA** fest.

7. Konfigurieren Sie in den **Einstellungen** die folgenden Zeiteinstellungen:

    - **Zeit von zugesagt:** Morgen um 9:00 Uhr

    - **Zeit bis zugesagt:** Heute um 11:00 Uhr

8. Wählen Sie **Speichern und schließen** aus, um Ihre Änderungen zu speichern und den neuen Arbeitsauftrag zu schließen.

 

### <a name="task-3-generate-a-work-order-from-a-case"></a>Aufgabe 3: Arbeitsauftrag aus einer Anfrage heraus erstellen

Sie können Arbeitsaufträge auch erstellen, indem Sie Anfragedatensätze eskalieren. In diesem Beispiel eskalieren wir den zuvor erstellten Anfragedatensatz „Kamera funktioniert nicht“. 

 

1. Klicken Sie im linken Navigationsbereich auf **Anfragen**. 

2. Öffnen Sie die zuvor erstellte Anfrage **Kamera funktioniert nicht**. 

3. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **In Arbeitsauftrag konvertieren** aus. 

4. Nachdem der Arbeitsauftrag erstellt wurde, wählen Sie die Schaltfläche **OK** im Popupbildschirm aus, um die Details des Arbeitsauftrags anzuzeigen. 

 

Beide neu erstellten Arbeitsaufträge können jetzt geplant werden. 

## <a name="exercise-2-schedule-items-with-dynamics-365-field-service"></a>Übung 2: Elemente mit Dynamics 365 Field Service planen  

### <a name="task-1-schedule-directly-from-a-work-order"></a>Aufgabe 1: Zeitplanung direkt aus einem Arbeitsauftrag

1. Klicken Sie im linken Navigationsbereich auf **Zeitplanübersicht**.

2. Legen Sie oben rechts auf dem Bildschirm unter **Neue Zeitplanübersicht** die Option **EIN** fest. 

3. Geben Sie „Aidan Knaggs“ in das Suchfeld **Ressourcen suchen** ein. 

4. Wählen Sie unten auf dem Bildschirm im Anforderungsbereich die Option **Nicht geplante Arbeitsaufträge** aus.  (Falls der Anforderungsbereich nicht angezeigt wird, wählen Sie den Pfeil am unteren Bildschirmrand aus, um ihn zu erweitern). 

5. Suchen Sie den Arbeitsauftrag für **Munson's Pickles**, den Sie aus dem Anfragedatensatz erstellt haben (Verwenden Sie ggf. die Arbeitsauftragsnummer). 

6. Ziehen Sie den Datensatz für **Munson's Pickles** und platzieren Sie ihn in einem offenen Zeitfenster für Aidens Kontaktdatensatz. 

7. Es kann vorkommen, dass Sie einen Arbeitsauftrag aufgrund von Konflikten im Zusammenhang mit Technikern oder anderen Ressourcen umbuchen müssen. Dazu können Disponenten die Zeitplanübersicht verwenden. 

 

### <a name="task-2-schedule-with-the-schedule-board"></a>Aufgabe 2: Planen mit der Zeitplanübersicht

1. Klicken Sie im linken Navigationsbereich auf **Zeitplanübersicht**.

2. Geben Sie den Namen Ihres Benutzerkontos in das Suchfeld **Ressourcen suchen** ein (Ihr Ressourceneintrag sollte angezeigt werden).

3. Wählen Sie unten auf dem Bildschirm im Anforderungsbereich die Option **Nicht geplante Arbeitsaufträge** aus.  (Falls der Anforderungsbereich nicht angezeigt wird, wählen Sie den Pfeil am unteren Bildschirmrand aus, um ihn zu erweitern). 

4. Suchen Sie den Arbeitsauftrag für **Active Transport**, den Sie aus dem Anfragedatensatz erstellt haben (Verwenden Sie ggf. die Arbeitsauftragsnummer). 

5. Ziehen Sie den Datensatz für **Active Transport** und platzieren Sie ihn in einem offenen Zeitfenster für Ihren Benutzerdatensatz. Der Text wird in grün angezeigt, wenn das Zeitfenster mit dem bevorzugten Zeitfenster des Kunden übereinstimmt.

6. Es kann vorkommen, dass Sie einen Arbeitsauftrag aufgrund von Konflikten im Zusammenhang mit Technikern oder anderen Ressourcen umbuchen müssen. Dazu können Disponenten die Zeitplanübersicht verwenden. 

7. Wählen Sie das Feld „Ressourcen suchen“ in der Zeitplanübersicht (direkt über der Spalte „Ressourcenname“) aus, geben Sie **Brady** ein, und suchen Sie den Arbeitsauftrag, der im Verlauf des heutigen Tages für **Brady Hannon** geplant ist. 

8. **Klicken Sie mit der rechten Maustaste** auf das geplante Element. Wählen Sie im nächsten Menü die Option **Ersatzressource** aus. Wählen Sie das Auswahl-/Suchfeld aus, wählen Sie Ihren Ressourcendatensatz aus, und wählen Sie **Neu zuweisen** aus.
