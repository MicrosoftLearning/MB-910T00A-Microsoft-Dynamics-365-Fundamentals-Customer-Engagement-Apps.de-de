---
lab:
    title: 'Lab 4.3: Dynamics 365 Field Service Capstone-Lab'
    module: 'Modul 4: Mehr über die Grundlagen von Dynamics 365 Field Service erfahren'
---

Modul 4: Mehr über die Grundlagen von Dynamics 365 Field Service erfahren
========================

## Übungs-Lab 4.3 - Dynamics 365 Field Service Capstone-Lab

## Übungsszenario

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

**Service und Support:**

Im Anschluss an die Installation der Systeme bietet ABC seinen Kunden Supportservices an. Wenn bei einem Kunden ein Problem auftritt, kann er sich an den Kundendienst wenden. Ein Agent wird versuchen, das Problem gemeinsam mit dem Kunden remote zu lösen. Falls das Problem nicht remote gelöst werden kann, eskaliert der Support-Agent das Problem zu einem Arbeitsauftrag, der geplant und von einem qualifizierten Außendiensttechniker bearbeitet wird. 

## Ziele

Es gibt drei verschiedene Szenarien, in denen das Unternehmen ABC Techniker entsendet, um Arbeiten vor Ort beim Kunden zu erledigen. 

- Wenn ein neues Sicherheitssystem gekauft wurde und installiert werden muss.

- Wenn ein Helpdesk-Agent ein Problem eines Kunden nicht remote beheben kann.

- Wenn ein Kunde das Unternehmen direkt kontaktiert, um einen Service vor Ort anzufordern. 

Vor Kurzem hat der Kunde „Active Transport, Inc.“ den Support wegen eines Problems mit einer Kamera im Sicherheitssystem des Kunden kontaktiert. Der Helpdesk-Techniker konnte das Problem nicht remote beheben, daher muss ein Außendiensttechniker entsendet werden. In diesem Szenario führen Sie die folgenden Aufgaben aus:

- Anfragedatensatz zu einem Arbeitsauftrag konvertieren

- Arbeitsauftrag planen

- Arbeitsauftrag mit der mobilen App auflösen 

## Übungsaufbau

  - **Geschätzte Dauer**: 45 Minuten

## Anleitung

## Übung 1: Anfrage erstellen und zu einem Arbeitsauftrag eskalieren 

### Aufgabe 1: Anfragedatensatz erstellen

1. Öffnen Sie die **Dynamics 365 Field Service**-Anwendung, falls noch nicht geschehen. 

2. Wählen Sie **Anfragen** in der Navigation auf der linken Seite des Bildschirms aus. 

3. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um einen neuen Anfragedatensatz zu erstellen.

4. Vervollständigen Sie den Anfragedatensatz wie folgt:

	- **Anfragetitel:** Kamera funktioniert nicht

	- **Kunde:** Active Transport Inc.

	- **Ursprung:** Telefon

5. Wählen Sie die Registerkarte **Außendienst** aus.

6. Wählen Sie unter **Vorfalltyp** den Wert **Kamera funktioniert nicht** aus.

7. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Speichern und schließen** aus, um den Anfragedatensatz zu speichern und zu schließen. 

 

### Aufgabe 2: Arbeitsauftrag manuell erstellen

Wir werden später zu Ihrem erstellten Anfragedatensatz zurückkehren. Zunächst werden wir uns ansehen, wie Sie einen Arbeitsauftrag manuell erstellen. 

 

1. Wählen Sie links im Navigationsbereich die Option **Arbeitsaufträge** aus.

2. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um einen neuen Arbeitsauftrag zu erstellen.

3. Füllen Sie die Details des Arbeitsauftrags wie folgt aus:

	- **Dienstkonto:** Bremsen und Zahnräder 

	- **Preisliste:** Standardpreisliste

	- **Primärer Vorfalltyp:** Lüfter ausgefallen

	- **Steuerpflichtig:** Nein

4. Notieren Sie sich die Arbeitsauftragsnummer, um später überprüfen zu können, ob Sie den richtigen Arbeitsauftrag bearbeiten. 

5. Wählen Sie die Registerkarte **Einstellungen** aus.

6. Legen Sie im Feld **Servicegebiet** den Wert **WA** fest.

7. Konfigurieren Sie in den **Einstellungen** die folgenden Zeiteinstellungen:

	– **Zeit von zugesagt:** Morgen um 9:00 Uhr

	– **Zeit bis zugesagt:** Morgen um 11:00 Uhr

8. Wählen Sie **Speichern und schließen** aus, um Ihre Änderungen zu speichern und den neuen Arbeitsauftrag zu schließen.

 

### Aufgabe 3: Arbeitsauftrag aus einer Anfrage heraus erstellen

Sie können Arbeitsaufträge auch erstellen, indem Sie Anfragedatensätze eskalieren. In diesem Beispiel eskalieren wir den zuvor erstellten Anfragedatensatz „Kamera funktioniert nicht“. 

 

1. Klicken Sie im linken Navigationsbereich auf **Anfragen**. 

2. Öffnen Sie die zuvor erstellte Anfrage **Kamera funktioniert nicht**. 

3. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **In Arbeitsauftrag konvertieren** aus. 

4. Warten Sie, bis der Arbeitsauftrag erstellt wurde, und klicken Sie im Popupbildschirm auf die Schaltfläche **OK**, um die Details des Arbeitsauftrags anzuzeigen. 

5. Wählen Sie die Registerkarte **Services** aus, und vergewissern Sie sich, dass die Services **Systemintegrität überprüfen** und **Bewegungsspielraum überprüfen** zum Arbeitsauftrag hinzugefügt wurden. **HINWEIS:** Falls diese Services nicht angezeigt werden, drücken Sie die F5-Taste, um Ihren Bildschirm zu aktualisieren. 

6. Wählen Sie die Registerkarte **Serviceaufgabe** aus, und vergewissern Sie sich, dass vier Aufgaben hinzugefügt wurden.

 

Beide neu erstellten Arbeitsaufträge können jetzt geplant werden. 

## Übung 2: Elemente mit Dynamics 365 Field Service planen  

### Aufgabe 1: Zeitplanung direkt aus einem Arbeitsauftrag

1. Klicken Sie im linken Navigationsbereich auf **Zeitplanübersicht**.

2. Legen Sie oben rechts auf dem Bildschirm unter **Neue Zeitplanübersicht** die Option **EIN** fest. 

3. Geben Sie den Namen Ihres Benutzerkontos in das Suchfeld **Ressourcen suchen** ein (Ihr Ressourceneintrag sollte angezeigt werden).

4. Wählen Sie unten auf dem Bildschirm im Anforderungsbereich die Option **Nicht geplante Arbeitsaufträge** aus.  (Falls der Anforderungsbereich nicht angezeigt wird, wählen Sie den Pfeil am unteren Bildschirmrand aus, um ihn zu erweitern). 

5. Suchen Sie den Arbeitsauftrag für **Active Transport**, den Sie aus dem Anfragedatensatz erstellt haben (Verwenden Sie ggf. die Arbeitsauftragsnummer). 

6. Ziehen Sie den Datensatz für **Active Transport** und platzieren Sie ihn in einem offenen Zeitfenster für Ihren Benutzerdatensatz. 

7. Es kann vorkommen, dass Sie einen Arbeitsauftrag aufgrund von Konflikten im Zusammenhang mit Technikern oder anderen Ressourcen umbuchen müssen. Dazu können Disponenten die Zeitplanübersicht verwenden. 

8. Klicken Sie in der Zeitplanübersicht auf das Feld „Ressourcen suchen“ (über der Spalte „Ressourcenname“), geben Sie **Brady** ein, und suchen Sie den Arbeitsauftrag, für den **Brady Hannon** heute eingeplant ist. 

9. **Klicken Sie mit der rechten Maustaste** auf das geplante Element. Wählen Sie im nächsten Menü die Option **Neu zuweisen** aus. Klicken Sie in das Suchfeld, und wählen Sie Ihren Ressourcendatensatz aus.

 

 

### Aufgabe 2: Planen mit der Zeitplanübersicht

1. Klicken Sie im linken Navigationsbereich auf **Zeitplanübersicht**.

2. Geben Sie den Namen Ihres Benutzerkontos in das Suchfeld **Ressourcen suchen** ein (Ihr Ressourceneintrag sollte angezeigt werden).

3. Wählen Sie unten auf dem Bildschirm im Anforderungsbereich die Option **Nicht geplante Arbeitsaufträge** aus.  (Falls der Anforderungsbereich nicht angezeigt wird, wählen Sie den Pfeil am unteren Bildschirmrand aus, um ihn zu erweitern). 

4. Suchen Sie den Arbeitsauftrag für **Active Transport**, den Sie aus dem Anfragedatensatz erstellt haben (Verwenden Sie ggf. die Arbeitsauftragsnummer). 

5. Ziehen Sie den Datensatz für **Active Transport** und platzieren Sie ihn in einem offenen Zeitfenster für Ihren Benutzerdatensatz. 

6. Es kann vorkommen, dass Sie einen Arbeitsauftrag aufgrund von Konflikten im Zusammenhang mit Technikern oder anderen Ressourcen umbuchen müssen. Dazu können Disponenten die Zeitplanübersicht verwenden. 

7. Klicken Sie in der Zeitplanübersicht auf das Feld „Ressourcen suchen“ (über der Spalte „Ressourcenname“), geben Sie **Brady** ein, und suchen Sie den Arbeitsauftrag, für den **Brady Hannon** heute eingeplant ist. 

8. **Klicken Sie mit der rechten Maustaste** auf das geplante Element. Wählen Sie im nächsten Menü die Option **Ersatzressource** aus. Klicken Sie in das Such- und Auswahlfeld, wählen Sie Ihren Ressourcendatensatz aus, und wählen Sie dann **Neu zuweisen** aus.
