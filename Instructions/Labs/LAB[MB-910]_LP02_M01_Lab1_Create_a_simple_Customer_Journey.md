---
lab:
  title: "Lernpfad\_2 – Lab\_2.1: Erstellen eines einfachen Kundenkontaktverlaufs"
  learning path: Explore the fundamentals of Dynamics 365 Marketing
  module: Explore Dynamics 365 Marketing
---

Lernpfad 2 – Modul 1: Erkunden von Dynamics 365 Marketing
========================

## Übungs-Lab 2.1: Erstellen eines einfachen Kundenkontaktverlaufs

## Ziele

In dieser Übung werden Sie sehen, dass Kundenkontaktverläufe eine Schlüsselkomponente in Dynamics 365 Marketing sind. Sie erstellen Kundenkontaktverläufe als Grundlage für alle Marketinganstrengungen, um den Pfad eines Kunden bei der Interaktion mit dem Marketingprozess Ihres Unternehmens zu bestimmen. Das Ziel eines Kontaktverlaufs ist, dass wir diesen in Einnahmen umwandeln.

## Lab-Einrichtung

  - **Geschätzte Dauer**: 20 Minuten

## Anweisungen

1. Öffnen Sie die **Dynamics 365 Marketing-Anwendung**.

2. Ändern Sie den Bereich zu **Ausgehendes Marketing**. 

3. Wählen Sie links im Navigationsbereich unter der Gruppe **Kunden** die Option **Kontakte** aus.

4. Wählen Sie in der Befehlsleiste **Neu**.

5. Füllen Sie die Seite **Neuer Kontakt** wie folgt aus.

    - **Vorname**: Jenny

    - **Nachname**: Jones (Ihre Initialen)

    - **E-Mail**: Geben Sie eine E-Mail-Adresse ein, unter der Sie E-Mails empfangen können.

    - **Adresse 1, Straße 1**: 101 Sample Ave

    - **Adresse 1: Ort**: Fargo

    - **Adresse 1: Bundesland/Kanton** :ND

    - **Adresse 1: Postleitzahl**: 58103

6. Vervollständigen Sie den Kontakt, und wählen Sie **Speichern und schließen** aus.

7. Wählen Sie auf der Befehlsleiste erneut „Neu“ aus, um einen weiteren Kontakt zu erstellen.

8. Vervollständigen Sie den zweiten Kontakt wie folgt:

    - **Vorname**: Marco

    - **Nachname**: Gomez (Ihre Initialen)

    - **E-Mail**: Geben Sie eine E-Mail-Adresse ein, unter der Sie E-Mails empfangen können.

    - **Adresse 1, Straße 1**: 101 Sample Ave

    - **Adresse 1: Ort**: Fargo

    - **Adresse 1: Bundesland/Kanton** :ND

    - **Adresse 1: Postleitzahl**: 58103

**HINWEIS:** Wir verwenden dieselben Adressdaten, um die Erkennung der Kontakte als Beispieldaten zu erleichtern. 

9. Vervollständigen Sie den Kontakt, und wählen Sie **Speichern und schließen** aus.

**WICHTIG**: Aufgrund der Adresse können die Systemeinstellungen für die Erkennung von Duplikaten ausgelöst werden. Wenn der Bildschirm für doppelte Datensätze angezeigt wird, wählen Sie die Schaltfläche **Ignorieren und speichern** aus. 

**Aufgabe 2: Erstellen eines Segments für Fargo** 

Als Nächstes erstellen wir ein neues Segment und fügen die Kontakte hinzu, die wir in der vorherigen Aufgabe erstellt haben. 

1. Wählen Sie links im Navigationsbereich unter **Marketing** die Option **Segmente** aus. 

    2. Wählen Sie in der Befehlsleiste **Neu**.

    3. Wählen Sie im Dropdownmenü die Option **Neues dynamisches Segment** aus.

    4. Wählen Sie im daraufhin geöffneten Dialogfeld **Segmentvorlagen** die Option **Überspringen** aus, um das Dialogfeld zu schließen und zum Bildschirm **Neues Segment** fortzufahren.

    5. Wählen Sie **Abfrageblock hinzufügen** aus, um eine Abfrage für die Kontaktentität zu erstellen. 

    6. Wählen Sie den inaktiven Text **Attribut auswählen** aus. 

    7. Geben Sie dann „Ort“ ein, um die Liste zu filtern, und wählen Sie **Adresse 1: Ort** aus der Liste aus.

    8. Belassen Sie die nächste Dropdownliste auf **Ist gleich**. 

    9. Wählen Sie die dritte Dropdownliste aus, die den inaktiven Text **Suchtext eingeben** enthält, und geben Sie **Fargo** ein.

    10. Klicken Sie oben in der Abfrage auf das Feld **Name**, um es auszuwählen, und geben Sie **Kontakte in Fargo (Ihre Initialen)** ein. (Möglicherweise müssen Sie den nach unten weisenden Pfeil neben „Status“ auswählen.)

    11. Wählen Sie in der Befehlsleiste die Option **Speichern** aus, um Ihr Segment zu speichern.

    12. Wählen Sie **Live schalten** aus, um das Segment zu veröffentlichen.

    13. Warten Sie etwa eine Minute, und klicken Sie dann in der Befehlsleiste auf **Aktualisieren**, um die Seite zu aktualisieren. 

    14. Daraufhin sollte eine neue Registerkarte **Mitglieder** hinzugefügt werden. 

 

**Aufgabe 3: Erstellen einer einfachen E-Mail** 

Als Nächstes erstellen wir eine einfache E-Mail aus einer vorhandenen Vorlage, die wir für unseren Kundenkontaktverlauf nutzen können. 

1. Wählen Sie links im Navigationsbereich unter der Gruppe **Marketing** die Option **Marketing-E-Mails** aus.

2. Wählen Sie auf der Befehlsleiste die Option **+ Neu** aus.

3. Wählen Sie auf dem Bildschirm **E-Mail-Vorlagen für Marketing** erst **1 Spalte** und dann die Schaltfläche **Auswählen** aus. 

4. Wählen Sie in der oberen linken Ecke der E-Mail das Feld „Name“ aus. (Der Text ähnelt „Email ypl (1 Spalte)“.)

5. Ändern Sie den Namen zu **Beispiel-E-Mail-Nachricht (Ihre Initialen)** .

6. Geben Sie im Feld **Betreff** den Text **Sehen Sie sich unser Angebot an** ein. 

7. Klicken Sie auf die Schaltfläche **Speichern**. 

8. Wählen Sie die Schaltfläche **Live schalten** aus, um die E-Mail zu veröffentlichen. 

 

**Aufgabe  4: Erstellen eines Kundenkontaktverlaufs** 

Nachdem wir unsere Zielgruppe sowie die zu verwendende E-Mail-Aktivität festgelegt haben, erstellen wir jetzt einen Kundenkontaktverlauf. 

1. Wählen Sie links im Navigationsbereich unter der Gruppe **Marketing** die Option **Kundenkontaktverläufe** aus.

    2. Wählen Sie auf der Befehlsleiste die Option **+ Neu** aus.

    3. Wählen Sie im Popupfenster **Vorlagen für Kundenkontaktverlauf** die Option **Überspringen** aus, um mit der Erstellung eines ganz neuen Kundenkontaktverlaufs zu beginnen.

    4. Wählen Sie **Zielgruppe festlegen** (oder alternativ **+** ). Vergewissern Sie sich, dass der **Quelltyp** auf **Segment** festgelegt ist, und wählen Sie das Segment **Kontakte in Fargo (Ihre Initialen)** aus, das Sie in der vorherigen Übung erstellt haben. Die erste Kachel wird mit dem Segmentnamen ausgefüllt, und im Bereich **Zielgruppe** werden die Segmenteigenschaften angezeigt.

    5. Wählen Sie **+** auf der Canvas aus, und wählen Sie dann **E-Mail senden** im Kontextmenü aus.

    6. Wählen Sie im Abschnitt zum Senden einer E-Mail die **Beispiel-E-Mail (Ihre Initialen)** aus, die Sie zuvor erstellt haben.

    7. Wählen Sie die Registerkarte „Allgemein“ am oberen Rand des Kundenkontaktverlauf-Datensatzes aus. Geben Sie die folgenden Informationen auf der Registerkarte **Allgemein** ein.

        - **Name**: Kundenkontaktverlauf in Fargo (Ihre Initialen)

        - **Startdatum und -zeit**: Geben Sie das heutige Datum ein.

        - **Enddatum und -zeit**: Ein Monat ab heute

        - **Zeitzone**: Wählen Sie Ihre lokale Zeitzone aus.

8. Wählen Sie in der Befehlsleiste **Speichern** aus, um Ihren aktuellen Arbeitsfortschritt zu speichern.

9. Ihr Kontaktverlauf ist jetzt startklar. Um den Kontaktverlauf zu starten, veröffentlichen Sie ihn, indem Sie in der Befehlsleiste die Option **Live schalten** auswählen.

 
