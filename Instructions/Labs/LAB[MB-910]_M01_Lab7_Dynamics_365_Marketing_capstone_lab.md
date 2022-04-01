---
lab:
  title: 'Lab 1.7: Dynamics 365 Marketing Capstone-Lab'
  module: 'Module 1: Learn the Fundamentals of Dynamics 365 Marketing'
ms.openlocfilehash: d61461c69044ff558890f6f95990c705863e646d
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908894"
---
<a name="module-1-learn-the-fundamentals-of-dynamics-365-marketing"></a>Modul 1: Grundlegende Informationen zu Dynamics 365 for Marketing
========================

## <a name="practice-lab-17---dynamics-365-marketing-capstone-lab"></a>Übungs-Lab 1.7 – Dynamics 365 Marketing Capstone-Lab

**Hinweis:** Marketing-E-Mails können nicht in Internet Explorer erstellt oder bearbeitet werden. Verwenden Sie Microsoft Edge oder Google Chrome für diese Übung.

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

Das Unternehmen ABC spricht seine Privatkunden direkt über gezielte Marketingkampagnen an. Die Kunden werden anhand ihrer Stadt und von anderen Faktoren angesprochen. Das Marketingmaterial wird per E-Mail verschickt, und der Kontaktverlauf hängt von der Interaktion mit der E-Mail ab. 

Aus einer aktuellen Marketingkampagne für Hausbesitzer in Portland sind zahlreiche neue Leads entstanden. ABC konnte viele dieser Leads zu Verkaufserlösen konvertieren. Sie wurden damit beauftragt, eine ähnliche Kampagne für die Region Seattle durchzuführen. 

In diesem Lab werden Sie die folgenden Aufgaben ausführen:

- Benutzerdefinierte Marketing-E-Mail erstellen

- Dynamisches Kundensegment erstellen

- Kundenkontaktverlauf erstellen, der Ihre Marketing-E-Mail und Ihr Kundensegment verwendet 

## <a name="lab-setup"></a>Lab-Einrichtung

  - **Geschätzte Dauer**: 45 Minuten

## <a name="instructions"></a>Anweisungen

## <a name="exercise-1-create-a-marketing-email"></a>Übung 1: Marketing-E-Mail erstellen

1. Öffnen Sie die Dynamics 365 Marketing-Anwendung, falls noch nicht geschehen. 

2. Wählen Sie links im Navigationsbereich unter der Gruppe **Marketing** die Option **Marketing-E-Mail** aus.

3. Wählen Sie auf der **Befehlsleiste** die Option **Neu** aus, um eine neue Marketing-E-Mail zu erstellen.

4. Wählen Sie in der Liste der **Vorlagen für Marketing-E-Mails** die Option **Newsletter 1 Spalte** aus, und wählen Sie die Schaltfläche **Auswählen** aus.

5. Warten Sie, bis der neue Datensatz geöffnet wurde, und wählen Sie den Dropdownpfeil neben dem Feld **Statusgrund** im Datensatztitel am oberen Rand aus. 

6. Geben Sie im Feld **Name** den Text **Sicherheit für Ihr Zuhause – Ihre Initialen** ein. 

7. Geben Sie unter **Betreff** den Text „**Schützen Sie Ihre Familie**!“ ein. Möglicherweise müssen Sie zum Anfang der Designseite scrollen, um das Betrefffeld anzuzeigen.

8. Suchen Sie im Nachrichtenfenster das kleine Bild **über** dem Text mit der Beschriftung **Kurze Überschrift eingeben**, und wählen Sie es aus. 

9. Fahren Sie im Eigenschaftenbereich über die Schaltfläche **Bildergalerie**, und wählen Sie sie aus. 

10. Wählen Sie das Bild **contosologo.png** aus, und wählen Sie die Schaltfläche **Auswählen** aus, um es in Ihre E-Mail einzufügen. 

11. Verwenden Sie die Größenziehpunkte auf dem Bild, um das Bild auf die gewünschte Größe anzupassen. 

12. Wählen Sie das Feld **Kurze Überschrift eingeben** aus. Ändern Sie den Text zu **Fühlen Sie sich rund um die Uhr sicher**.

13. Wählen Sie den Abschnitt unter dem Text aus, den Sie soeben bearbeitet haben. 

14. Ersetzen Sie den Text durch den folgenden Text: Wissen Sie stets, was in und um Ihr Zuhause herum vor sich geht? Sie und Ihre Familie haben es verdient, sich sicher und geschützt zu fühlen, egal ob Sie zuhause oder unterwegs sind. Mit dem richtigen Sicherheitssystem können Sie sich nicht nur sicher fühlen, sondern möglicherweise auch Ihre Versicherungsprämie reduzieren. 

15. Wählen Sie das **Bild** unter dem Text aus, den Sie soeben bearbeitet haben. 

16. Wählen Sie die Schaltfläche **Bildergalerie** aus. 

17. Wählen Sie das Bild **safebox.png** aus, und wählen Sie die Schaltfläche **Auswählen** aus, um es in Ihre E-Mail einzufügen. 

18. Passen Sie die Bildgröße an. 

19. Wählen Sie das Feld **Überschrift oder Titel** unter dem Bild aus, und ersetzen Sie den Text durch **Wir haben alles, was Sie brauchen**. 

20. Wählen Sie das Textfeld unter der Überschrift aus, die Sie soeben bearbeitet haben. 

21. Ersetzen Sie den Text durch den folgenden Text: **Lassen Sie sich von unseren preisgekrönten Systemen schützen.**

22. Wählen Sie den gesamten Abschnitt unter dem Abschnitt aus, den Sie soeben bearbeitet haben. Drücken Sie auf das **Papierkorbsymbol**, um den Abschnitt zu entfernen. 

23. Wiederholen Sie den Vorgang für die restlichen Abschnitte oder sonstigen Elemente in der Nachricht.

24. Bevor wir die E-Mail live schalten können, werden wir sie auf Fehler überprüfen. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Auf Fehler prüfen** aus. 

25. Vergewissern Sie sich, dass die E-Mail keine Fehler enthält, und wählen Sie auf der **Befehlsleiste** die Schaltfläche **Live schalten** aus. 

26. Wählen Sie den Dropdownpfeil neben der Schaltfläche **Speichern** in der Befehlsleiste aus, und wählen Sie **Speichern und schließen** aus. 

27. Falls Sie dieselbe E-Mail-Adresse für beide Kontakte verwendet haben, wird der Hinweis **Doppelte Datensätze gefunden** angezeigt. Wählen Sie **Ignorieren und speichern** aus.

## <a name="exercise-2-create-a-segment-in-dynamics-365-marketing"></a>Übung 2: Segment in Dynamics 365 Marketing erstellen

### <a name="task-1-add-some-sample-contacts-to-work-with"></a>Aufgabe 1: Beispielkontakte hinzufügen 

1. Wählen Sie links im Navigationsbereich die Option „Kontakte“ unter der Gruppe „Kunden“ aus.

2. Wählen Sie in der Befehlsleiste **Neu**.

3. Füllen Sie die Seite **Neuer Kontakt** wie folgt aus.

    - **Vorname**: Piper 

    - **Nachname:** Smith – Ihre Initialen

    - **E-Mail**: Geben Sie eine E-Mail-Adresse ein, unter der Sie E-Mails empfangen können.

    - **Adresse 1: Straße 1:** 1989 191<sup data-htmlnode="">st</sup> Ave N

    - **Adresse 1: Ort**: Seattle

    - **Adresse 1: Bundesland/Kanton:** WA

    - **Adresse 1: Postleitzahl:** 98001

4. Vervollständigen Sie den Kontakt, und wählen Sie **Speichern und schließen** aus.

5. Anschließend werden Sie sich selbst als Kontakt hinzufügen, um mit mehreren Personen arbeiten zu können. 

6. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus.

7. Vervollständigen Sie den zweiten Kontakt wie folgt:

    - **Vorname**: Ihr Vorname

    - **Nachname:** Ihre E-Mail-Adresse

    - **E-Mail**: Geben Sie eine E-Mail-Adresse ein, unter der Sie E-Mails empfangen können.

    - **Adresse 1: Straße 1:** 1989 191<sup data-htmlnode="">st</sup> Ave N

    - **Adresse 1: Ort**: Seattle

    - **Adresse 1: Bundesland/Kanton:** WA

    - **Adresse 1: Postleitzahl:** 98001

**HINWEIS:** Wir verwenden dieselben Adressdaten, um die Erkennung der Kontakte als Beispieldaten zu erleichtern. 

### <a name="task-2-create-a-customer-segment"></a>Aufgabe 2: Kundensegment erstellen

Wir erstellen ein Kundensegment, um festzulegen, welche Kunden wir mit bestimmten Marketingaktionen ansprechen möchten. 

1. Wählen Sie links im Navigationsbereich die Option **Segmente** unter der Gruppe **Kunden** aus. 

2. Wählen Sie in der Befehlsleiste **Neu**.

3. Da sich die Mitgliedschaft ändern soll, wenn wir Kontakte hinzufügen, entfernen oder bearbeiten, wählen wir im nächsten Menü **Neues dynamisches Segment** aus. 

4. Wählen Sie im daraufhin geöffneten Dialogfeld **Segmentvorlagen** die Option **Überspringen** aus, um das Dialogfeld zu schließen und zum Bildschirm **Neues Segment** fortzufahren.

5. Warten Sie, bis der neue Datensatz geöffnet wurde, und wählen Sie den Dropdownpfeil neben dem Feld **Statusgrund** im Datensatztitel am oberen Rand aus. 

6. Geben Sie im Feld **Name** den Text **Kunden Seattle – Ihre Initialen** ein. 

7. Wählen Sie im Fenster „Segmentdefinition“ die Option **Abfrageblock hinzufügen** aus.

8. Beachten Sie, dass die Tabelle „Kontakt“ standardmäßig ausgewählt ist. Ändern Sie daran nichts. 

9. Wählen Sie den Text **Attribut auswählen** aus. 

10. Geben Sie das Wort „Ort“ ein, um die Liste zu filtern. Wählen Sie **Adresse 1: Ort** in der Liste aus.

11. Belassen Sie die nächste Dropdownliste auf **Ist gleich**. 

12. Wählen Sie die dritte Dropdownliste aus, die den Text **Text eingeben** enthält, und wählen Sie **Seattle** aus.

13. Wählen Sie in der Befehlsleiste die Option **Speichern** aus, um Ihr Segment zu speichern.

14. Wählen Sie **Live schalten** aus, um das Segment zu veröffentlichen.

15. Warten Sie etwa eine Minute, und klicken Sie dann in der Befehlsleiste auf **Aktualisieren**, um die Seite zu aktualisieren. 

16. Daraufhin sollte eine neue Registerkarte **Mitglieder** hinzugefügt werden.

### <a name="task-3-test-your-customer-segment"></a>Aufgabe 3: Kundensegment testen

Nachdem wir das Segment erfolgreich erstellt haben, überprüfen wir, ob das dynamische Segment korrekt ausgefüllt wird, wenn wir Kontakte hinzufügen oder entfernen. Dazu erstellen wir einen neuen Kontakt, der in Seattle lebt. 

1. Wählen Sie links im Navigationsbereich die Option **Kontakte** unter der Gruppe „Kunden“ aus.

2. Wählen Sie in der Befehlsleiste **Neu**.

3. Füllen Sie die Seite **Neuer Kontakt** wie folgt aus.

    - **Vorname**: Rick

    - **Nachname:** Jones – Ihre Initialen

    - **E-Mail**: Geben Sie eine E-Mail-Adresse ein, unter der Sie E-Mails empfangen können.

    - **Adresse 1: Straße 1:** 1989 191<sup data-htmlnode="">st</sup> Ave N

    - **Adresse 1: Ort**: Seattle

    - **Adresse 1: Bundesland/Kanton:** WA

    - **Adresse 1: Postleitzahl:** 98001

4. Vervollständigen Sie den Kontakt, und wählen Sie **Speichern und schließen** aus.

5. Wählen Sie links im Navigationsbereich die Option **Segmente** unter der Gruppe **Kunden** aus. 

6. Öffnen Sie das zuvor erstellte Segment **Kunden in Seattle – Ihre Initialen**. 

7. Wählen Sie die Registerkarte **Mitglieder** aus. Dort sollte jetzt **Rick Jones – Ihre Initialen** angezeigt werden. Möglicherweise müssen Sie die Ansicht aktualisieren.

**WICHTIG:** Da wir in einer gemeinsamen Umgebung arbeiten und alle Benutzer dasselbe System verwenden, werden vermutlich auch andere Kontakt im dynamischen Marketingsegment angezeigt. Dies ist für den Zweck dieses Kurses in Ordnung. 

## <a name="exercise-3-create-a-customer-journey"></a>Übung 3: Kundenkontaktverlauf erstellen

Nachdem wir den Marketinginhalt erstellt haben, den wir verteilen möchten, und ein Kundensegment definiert haben, das wir ansprechen möchten, können wir einen Kundenkontaktverlauf erstellen, um mit den Kunden zu interagieren. 

1. Wählen Sie links im Navigationsbereich unter der Gruppe **Marketing** die Option **Kundenkontaktverläufe** aus.

2. Wählen Sie auf der Befehlsleiste die Option **Neu** aus. 

3. Die Seite **Neuer Kundenkontaktverlauf** wird mit dem Dialogfeld **Vorlage für den Kundenkontaktverlauf auswählen** geöffnet. Wählen Sie **Überspringen** aus, um einen neuen Kontaktverlauf zu erstellen.

4. Vergewissern Sie sich, dass im Bereich **Zielgruppe** unter **Quelltyp** die Option **Segment** ausgewählt ist. 

5. Wählen Sie die Segmentsuche unter dem Dropdownfeld **Einschluss** aus. 

6. Geben Sie den Text **Seattle** ein, und wählen Sie das zuvor erstellte Segment **Kunden in Seattle** aus. 

7. Bewegen Sie Ihren Mauszeiger auf dem Designcanvas zwischen **Start** und **Ende**. Wählen Sie das **+** -Zeichen aus, und wählen Sie im nächsten Menü die Option **E-Mail senden** aus.

8. Geben Sie den Text **Zuhause** ein, und wählen Sie die Marketing-E-Mail **Sicherheit für Ihr Zuhause – Ihre Initialen** aus, die Sie in Übung 1 erstellt haben. 

9. Zeigen Sie mit dem Mauszeiger auf die Option „E-Mail senden“. Wählen Sie das **+** -Zeichen aus, und wählen Sie im nächsten Menü die Option **Falls/dann** aus.

10. Wählen Sie im Bereich **Falls/dann** links auf dem Bildschirm unter „Bedingungen“ das Feld **Quelle auswählen** aus. 

11. Wählen Sie das Segment **Sicherheit für Ihr Zuhause – Ihre Initialen** aus. 

12. Wählen Sie das Feld **Bedingung auswählen** aus. Wählen Sie **Es wurde auf einen Link geklickt** aus.

13. Wählen Sie im Pfad **Ja** das **+** -Zeichen aus. Wählen Sie im nächsten Menü die Option **Lead erstellen** aus.

14. Belassen Sie den Pfad **Nein** unverändert. 

15. Wählen Sie die Registerkarte „Allgemein“ am oberen Rand des Kundenkontaktverlauf-Datensatzes aus. Geben Sie die folgenden Informationen auf der Registerkarte **Allgemein** ein.

    - **Name:** Herbstangebot für die Region Seattle – Ihre Initialen

    - **Startdatum und -zeit**: Geben Sie das heutige Datum ein.

    - **Enddatum und -zeit**: Ein Monat ab heute

    - **Zeitzone**: Wählen Sie Ihre lokale Zeitzone aus. 

16. Wählen Sie in der Befehlsleiste **Speichern** aus, um Ihren aktuellen Arbeitsfortschritt zu speichern.

17. Ihr Kontaktverlauf ist jetzt startklar. Um den Kontaktverlauf zu starten, veröffentlichen Sie ihn, indem Sie in der Befehlsleiste die Option **Live schalten** auswählen.

 
