---
lab:
    title: 'Lab 2.3: Dynamics 365 Sales Capstone-Lab'
    module: 'Modul 2: Mehr über die Grundlagen von Dynamics 365 Sales erfahren'
---

Modul 2: Mehr über die Grundlagen von Dynamics 365 Sales erfahren
========================

## Übungs-Lab 2.3 - Dynamics 365 Sales Capstone-Lab

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

Sie arbeiten als Vertriebsmitarbeiter für den Privatkundenbereich von ABC. Viele Ihrer Leads stammen zwar aus vom Unternehmen gesponserten Veranstaltungen, Marketingkampagnen und eingekauften Listen, aber Sie erhalten trotzdem häufig direkte Anfragen von Kunden. Wenn Sie eine solche Anfrage erhalten, müssen Sie den Lead manuell eingeben und über den kompletten Vertriebslebenszyklus hinweg bearbeiten. 

Sie haben kürzlich einen Anruf von Piper Smith erhalten. In der Nachbarschaft der Kundin gab es eine Reihe von Einbrüchen, und sie möchte Sicherheitsgeräte für ihr Zuhause kaufen. Sie werden den Lead von Piper in das System eingeben und anschließend versuchen, sie zu qualifizieren und durch den Vertriebszyklus zu führen. 

In diesem Lab werden Sie die folgenden Aufgaben ausführen:

- Einen Lead in Dynamics 365 Sales eingeben

- Einen Lead zu einer Verkaufschance qualifizieren und konvertieren

- Alltägliche Aktivitäten im Zusammenhang mit einer Verkaufschance verwalten 

- Ein Angebot zu einer Verkaufschance hinzufügen 

- Eine Verkaufschance abschließen 

- Eine Rechnung generieren 

## Übungsaufbau

  - **Geschätzte Dauer**: 30 Minuten

## Anleitung
  
## Übung 1: Lead in Dynamics 365 Sales erstellen und qualifizieren


### Aufgabe 1: Neuen Lead erstellen

1. Öffnen Sie einen InPrivate-Browser, und navigieren Sie zu [Https://home.Dynamics.com](https://home.dynamics.com/), falls noch nicht geschehen. 

2. Melden Sie sich mit den Benutzeranmeldeinformationen an, die Sie vom Kursleiter erhalten haben, wenn Sie dazu aufgefordert werden. 

3. Wählen Sie das **Vertriebshub** in der Liste der angezeigten Anwendungen aus.

4. Wählen Sie über die Navigation auf der linken Seite des Bildschirms **Leads** aus. 

5. Um alle aktuellen Vertriebsleads im System anzuzeigen, wählen Sie den Pfeil nach unten neben **Meine offenen Leads** aus, und wählen Sie im nächsten Menü **Aktive Leads** aus. 

6. Um zur Liste Ihrer Leads zurückzukehren, wählen Sie den Pfeil nach unten neben „Aktive Leads“ aus, und wählen Sie im nächsten Menü **Meine offenen Leads** aus. 

7. Als Nächstes werden wir einen neuen Lead für Piper Smith erstellen. Wählen Sie in der Ansicht **Meine offenen Leads** die Schaltfläche **Neu** auf der Befehlsleiste aus.

8. Vervollständigen Sie Ihren neuen Leaddatensatz wie folgt:

	- **Thema:** Auf der Suche nach neuer Sicherheitsausrüstung – „Ihr Name“

	- **Vorname:** Piper

	- **Nachname:** Smith – Ihre Initialen

	- **Mobiltelefon:** 888 555-1762

	- **E-Mail:** piper@sample.com

	- **Straße 1:** 1989 191<sup data-htmlnode="">st</sup> Ave N

	- **Ort:** Seattle

	- **Bundesland/Kanton:** WA

	- **Postleitzahl:** 98001 

9. Wählen Sie die Schaltfläche **Speichern** auf der Befehlsleiste aus, um den neuen Lead zu speichern, und lassen Sie ihn offen.

10. Beachten Sie den Geschäftsprozessflow **Lead für Verkaufschance** am Anfang des Datensatzes. Klicken Sie auf **Phase qualifizieren**, um diese Option auszuwählen. Vervollständigen Sie die Phase wie folgt:

	- **Einkaufszeitrahmen**: Dieses Quartal

	- **Geschätztes Budget:** 10.000 

	- **Kaufvorgang:** Individuell

	- **Entscheidungsträger identifizieren:** Abgeschlossen

11. Klicken Sie auf das **X** im Fenster für die Phase, um das Fenster zu schließen. 

12. Wechseln Sie zu **Datensatzzeitachse** in der Mitte des Bildschirms, und klicken Sie auf das **Pluszeichensymbol**, um eine neue Aktivität hinzuzufügen. 

13. Wählen Sie im nächsten Menü die Option **Telefonanruf** aus.

14. Füllen Sie den Telefonanruf im Fenster „Schnellerstellung eines Telefonanrufs“ wie folgt aus:

	- **Betreff:** Auf der Suche nach neuer Heimsicherheitsausrüstung

	- **Telefonnummer:** 888 555-1762

	- **Richtung:** Eingehend

	- **Beschreibung:** Nach einigen Einbrüchen in der Nachbarschaft möchte die Kundin ein Sicherheitssystem kaufen. 

15. Klicken Sie auf die Schaltfläche **Speichern und schließen**.

16. Beachten Sie, dass die Aktivität **Auf der Suche nach neuer Heimsicherheitsausrüstung** auf der **Datensatzzeitachse** angezeigt wird. Bewegen Sie den Mauszeiger über die Aktivität, und wählen Sie die Abschlussaktivität **Häkchensymbol** aus, um den Anruf als abgeschlossen zu markieren. 

17. Vergewissern Sie sich im Fenster **Telefonanruf schließen**, dass der Status auf **Abgeschlossen** festgelegt ist, und wählen Sie die Schaltfläche **Schließen** aus.

 

**WICHTIG:** Schließen Sie den Leaddatensatz nicht. Lassen Sie ihn geöffnet, da wir ihn im nächsten Schritt verwenden werden. 

 

### Aufgabe 2: Lead als Verkaufschance qualifizieren

Nach einem Besuch bei Piper stellen Sie fest, dass genügend Interesse bei der Kundin besteht, um den Prozess fortzusetzen, und dass Sie der Kundin passende Produkte und Services anbieten können. Als Nächstes qualifizieren Sie den Leaddatensatz. Dabei wird ein zugehöriger Verkaufschancendatensatz erstellt und die nächste Stufe des Verkaufsprozesses „Lead zu Verkaufschance“ erreicht. 

1. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Qualifizieren** aus. 

2. Nachdem das System den Lead qualifiziert hat, wird ein neuer Verkaufschancendatensatz erstellt, und der Geschäftsprozess geht in die Phase **Entwickeln** über. Wählen Sie die Phase **Qualifizieren** aus, um den ursprünglichen Leaddatensatz anzuzeigen. 

3. Wählen Sie die Phase **Entwickeln** aus, um zur Verkaufschance zurückzukehren.

4. Klicken Sie auf die Schaltfläche **Speichern und schließen**, um den erstellten Verkaufschancendatensatz zu schließen. 

 

 

## Übung 2: Verkaufschance in Dynamics 365 Sales verwalten

Nachdem wir den Lead erfolgreich als Verkaufschance qualifiziert haben, können wir die Verkaufschance über ihren Lebenszyklus hinweg bearbeiten.

### Aufgabe 1: Verkaufschance verwalten und Angebot erstellen 

1. Wählen Sie **Verkaufschancen** in der Navigation auf der linken Seite des Bildschirms aus. 

2. Wählen Sie den Dropdownpfeil neben der Ansicht **Meine offenen Verkaufschancen** aus, und wählen Sie im nächsten Menü **Offene Verkaufschancen** aus.

3. Wählen Sie auf der Befehlsleiste die Option „Diagramm anzeigen“ anzeigen aus. Das Diagramm „Die wichtigsten Kunden“ wird anhand der Tabelle „Verkaufschance“ angezeigt. 

4. Wählen Sie den Dropdownpfeil neben „Die wichtigsten Kunden“ aus, und wählen Sie im nächsten Menü die Option **Verkaufspipeline** aus.

5. Wählen Sie die Option zum Qualifizieren im Trichter aus. Die Liste der Verkaufschancen wird angepasst und zeigt jetzt die Verkaufschancen in der Phase „Qualifizieren“ an. 

6. Klicken Sie in den leeren Bereich im Diagramm, um wieder alle offenen Verkaufschancen anzuzeigen. 

7. Wählen Sie den Dropdownpfeil neben der Ansicht **Offene Verkaufschancen** aus, und wählen Sie im nächsten Menü **Meine offenen Verkaufschancen** aus. Dort wird vermutlich nur das Element **Auf der Suche nach neuer Sicherheitsausrüstung – Ihre Initialen** angezeigt, was sich auch im Diagramm widerspiegelt. 

8. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Diagramm ausblenden** aus. 

9. Finden und öffnen Sie das Element **Auf der Suche nach neuer Ausrüstung – Ihre Initialen**, das erstellt wurde, als Sie den Lead qualifiziert haben. Beachten Sie, dass sich der Datensatz bereits in der Phase **Entwickeln** befindet, da er aus einem zuvor qualifizierten Lead erstellt wurde.  

10. Wählen Sie unter **Auf der Suche nach neuer Ausrüstung – Ihre Initialen** oben im Datensatz den Pfeil nach unten neben dem Besitzerfeld aus. 

11. Geben Sie die folgenden Daten ein:

	- **Gesch. Abschlussdatum:** Morgen

	- **Gesch. Umsatz:** 12.500,00

12. Wechseln Sie zu **Datensatzzeitachse** in der Mitte des Bildschirms, und klicken Sie auf das **Pluszeichensymbol**, um eine neue Aktivität hinzuzufügen. 

13. Wählen Sie im nächsten Menü die Option **Termin** aus.

14. Füllen Sie den Bildschirm **Schnellerfassung: Termin** wie folgt aus:

	- **Betreff:** Kurze Besprechung – Ihre Initialen

	- **Ort:** Online

	- **Startzeit**: Morgen um 10:00 Uhr

	- **Endzeit:** Morgen um 10:30 Uhr

15. Wählen Sie in der Befehlsleiste die Option **Speichern und schließen** aus.

16. Wählen Sie im Geschäftsprozessflow „Lead zu Verkaufschance“ die Phase **Entwickeln** aus. In dieser Phase müssen Sie Stakeholder und Mitbewerber identifizieren.

17. Klicken Sie auf das **X** im Fenster für die Phase, um Ihre Arbeit fortsetzen zu können. 

18. Beachten Sie, dass **Piper** im Unterraster **Stakeholder** bereits als Stakeholder definiert ist. 

19. Wählen Sie im Unterraster „Vertriebsteam“ die **vertikalen Auslassungspunkte** aus. Wählen Sie im nächsten Menü **Neue Verbindung** aus. 

20. Geben Sie im Feld **Suchen** den Text **System** ein, und wählen Sie den Datensatz **Systemadministrator** aus. Klicken Sie dann auf die Schaltfläche **Hinzufügen**. Der Systemadministrator sollte jetzt im Vertriebsteam angezeigt werden. Wählen Sie andernfalls in der Befehlsleiste die Schaltfläche **Aktualisieren** aus. 

21. Wählen Sie im Unterraster „Mitbewerber“ die **vertikalen Auslassungspunkte** aus. Wählen Sie im nächsten Menü **Bestehenden Mitbewerber hinzufügen** aus. 

22. Wählen Sie im Bildschirm **Datensatz suchen** erst **Neuer Datensatz** und dann **Mitbewerber** aus.

23. Geben Sie auf dem Bildschirm Schnellerstellung: **Mitbewerber** im Feld **Name** den Wert **Coho Security – Ihre Initialen** ein.

24. Wählen Sie **Speichern und schließen** aus.

25. Vergewissern Sie sich, dass der zuvor erstellte Datensatz für „Coho Security“ ausgewählt ist, und wählen Sie die Schaltfläche **Hinzufügen** aus. 

26. Wählen Sie die Phase **Entwickeln** im Geschäftsprozessflow **Lead zu Verkaufschance** aus, und setzen Sie die Schritte **Stakeholder identifizieren** und **Mitbewerber identifizieren** auf **Abgeschlossen**. 

27. Klicken Sie auf die Schaltfläche **Nächste Phase**, um zur Phase **Vorschlagen** zu gelangen.

28. Markieren Sie in der Phase **Vorschlagen** den Punkt **Vertriebsteam identifizieren** als **Abgeschlossen**.

29. Klicken Sie auf das **X** im Fenster für die Phase „Vorschlagen“, um das Fenster zu schließen. 

30. Wählen Sie die Registerkarte **Angebote** im Verkaufschancendatensatz aus. 

31. Klicken Sie im Unterraster „Angebote“ auf die Schaltfläche **Neues Angebot**.

 

**WICHTIG:** Da in diesen Umgebungen mehrere Apps von Erstanbietern bereitgestellt werden, kann es passieren, dass nicht das richtige Angebotsformular für Vertriebsfunktionen angezeigt wird. Falls unter dem Angebotsnamen **Auf der Suche nach neuer Sicherheitsausrüstung – Ihre Initialen** der Text **Angebot . Angebot** steht, dann wurde das richtige Formular geladen. Falls dort **Angebot . Field Service-Informationen** steht, müssen Sie zu einem anderen Formular wechseln. Falls Sie zum anderen Formular wechseln müssen, wählen Sie den Dropdownpfeil neben **Angebot . Field Service-Informationen** aus. Wählen Sie im nächsten Menü die Option **Angebot** aus. 

 

### Aufgabe 2: Angebot verwalten

Nachdem Sie ein passendes Angebot haben, können Sie es für die Vorlage beim Kunden vorbereiten. Unter normalen Umständen würden wir Produkte zum Angebotsdatensatz hinzufügen, bevor wir ihn an einen Kunden senden. Da wir in gemeinsam genutzten Umgebungen arbeiten, überspringen wir das Hinzufügen der Angebotspositionen und behandeln stattdessen die Auslieferung des Angebots. 

1. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Angebot aktivieren** aus, um das Angebot zu aktivieren. 

2. Anschließend müssen Sie eine Preisliste auswählen und an die Verkaufschance anfügen.  Wählen Sie unter **Preisliste** im linken Bereich das Suchsymbol aus, und wählen Sie **Standardpreisliste** in den Optionen aus.

3. Nachdem das Angebot erstellt wurde, werden wir den Verkaufschancendatensatz mit den neuen Daten aktualisieren. Wählen Sie im Angebotsdatensatz die Verkaufschance **Auf der Suche nach neuer Sicherheitsausrüstung** – **Ihr Name** im Feld **Verkaufschance** unter dem Abschnitt **Verkaufsinformationen** aus. Der Verkaufschancendatensatz sollte auf Ihrem Bildschirm geöffnet werden. 

3. Wählen Sie im Verkaufschancendatensatz die Phase **Vorschlagen** aus. 

4. die Optionen **Vorschlag entwickeln**, **Interne Prüfung fertigstellen** und **Vorschlag präsentieren** als **Abgeschlossen**, und klicken Sie auf die Schaltfläche **Nächste Phase**, um zur Phase **Schließen** zu gelangen. 

5. Markieren Sie in der Phase **Schließen** die Schritte **Endgültigen Vorschlag fertigstellen**, **Endgültigen Vorschlag präsentieren**, **Dankesschreiben senden**, und **Nachbesprechung ablegen** als **Abgeschlossen**. 

6. Legen Sie **Entscheidungsdatum bestätigen** auf **Heutiges Datum** fest. 

7. Klicken Sie auf die Schaltfläche **Fertig stellen**. 

8. Wählen Sie das **X** im Fenster für die Phase „Schließen“ aus, um das Fenster zu schließen. 

9. Wählen Sie die Registerkarte **Angebote** aus. 

10. Öffnen Sie das Angebot **Auf der Suche nach neuer Sicherheitsausrüstung Ihr Name**. 

11. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Bestellung erstellen** aus.

12. Füllen Sie das Fenster „Bestellung erstellen“ wie folgt aus:

	- **Statusgrund:** Gewonnen

	- **Gewonnen am:** Heutiges Datum

	- **Verkaufschance abschließen:** Ja

	- **Tatsächlichen Umsatz aus Angeboten berechnen:** Nein

	- **Tatsächl. Umsatz:** 12.500$

13. Wählen Sie die Schaltfläche **OK** aus. 

Das System erstellt einen neuen Auftrag für den Artikel. Außerdem werden sowohl der Angebotsdatensatz und der entsprechende Verkaufschancendatensatz geschlossen. Nach Abschluss dieser Vorgänge wird die Bestellung auf Ihrem Bildschirm geöffnet. Lassen Sie die Bestellung geöffnet. 

###  

### Aufgabe 3: Auftrag und Rechnung verwalten

Nachdem Sie eine Bestellung erstellt haben, werden wir die Bestellung schließen und eine Reihenfolge generieren. Unter normalen Umständen werden die Produkte aus dem Angebotsdatensatz zur Bestellung hinzugefügt. Da wir in gemeinsam genutzten Umgebungen arbeiten, werden wir den Vorgang so fortsetzen, als wären die Produkte bereits hinzugefügt worden. 

 

1. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Auftrag erfüllen** aus. 

2. Füllen Sie den Bildschirm „Auftrag erfüllen“ wie folgt aus:

	- **Statusgrund:** Abgeschlossen

	- **Erfüllt am:** Heutiges Datum

3. Wählen Sie die Schaltfläche **Erfüllen** aus. 

4. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Rechnung erstellen** aus. 

5. Warten Sie, bis der Rechnungsdatensatz geöffnet wurde, und wählen Sie **Rechnung bezahlt** aus.
