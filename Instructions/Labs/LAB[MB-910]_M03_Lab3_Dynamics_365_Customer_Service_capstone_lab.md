---
lab:
  title: 'Lab 3.3: Dynamics 365 Customer Service Capstone-Lab'
  module: 'Module 3: Learn the Fundamentals of Dynamics 365 Customer Service'
ms.openlocfilehash: 85f3778dd9ab66a52bdfe2a5a77ad71ccb55544d
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908917"
---
<a name="module-3-learn-the-fundamentals-of-dynamics-365-customer-service"></a>Modul 3: Grundlegende Informationen zu Dynamics 365 for Customer Service
========================

## <a name="practice-lab-33---dynamics-365-customer-service-capstone-lab"></a>Übungs-Lab 3.3 - Dynamics 365 Customer Service Capstone-Lab

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

Es kann vorkommen, dass ein Kunde ein Problem mit einem Gerät hat. Diese Probleme werden dem Helpdesk des Unternehmens ABC gemeldet. Probleme können auf unterschiedliche Arten gemeldet werden. In manchen Fällen werden Probleme von den Geräten proaktiv gemeldet. Agenten versuchen, die gemeldeten Probleme remote zu beheben. Falls dies nicht möglich ist, wird ein Außendiensttechniker entsendet, um das Problem zu beheben. In letzter Zeit haben Sie zahlreiche defekte Sensoren repariert. Ihnen ist aufgefallen, dass die Ursache ein Software-Bug war. Sie möchten einen Knowledge-Artikel erstellen, um anderen Agenten zu helfen, wenn das Problem erneut auftritt. 

Als Helpdesk-Agent sind Sie dafür verantwortlich, die von den Kunden gemeldeten Probleme zu bearbeiten. Sie haben kürzlich einen Anruf von Piper Smith erhalten. Piper hat gemeldet, dass einer der Sensoren in ihrem System nicht funktioniert. Sie müssen Pipers Anruf protokollieren und versuchen, eine Lösung für ihr Problem zu finden. 

In diesem Lab werden Sie die folgenden Aufgaben ausführen:

- Knowledge-Artikel erstellen 

- Anfragen im Kundenservicehub verwalten

- Anfrage erstellen und protokollieren 

- Anfragedatensatz über den gesamten Lebenszyklus hinweg verwalten 

## <a name="lab-setup"></a>Lab-Einrichtung

  - **Geschätzte Dauer**: 45 Minuten

## <a name="instructions"></a>Anweisungen

## <a name="exercise-1-create-and-publish-a-knowledge-article"></a>Übung 1: Knowledge-Artikel erstellen und veröffentlichen

### <a name="task-1-create-a-knowledge-article"></a>Aufgabe 1: Knowledge-Artikel erstellen

1. Öffnen Sie die **Dynamics 365 Customer Service Hub**-Anwendung, falls noch nicht geschehen. 

2. Wählen Sie **Knowledge-Artikel** in der Navigation auf der linken Seite des Bildschirms aus. 

3. Mit dem Dropdownpfeil neben **Meine aktiven Artikel** können Sie jederzeit herausfinden, welche Artikel sich in den einzelnen Phasen befinden. 

4. Wählen Sie **Entwurfsartikel** aus. 

5. Wählen Sie **Genehmigte Artikel** in der Ansichtsauswahl aus.  

6. Wechseln Sie in der Ansichtsauswahl zurück zu **Meine aktiven Artikel**.

7. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus. Warten Sie, bis der neue Datensatz geöffnet wurde, und wählen Sie den Dropdownpfeil neben dem Feld **Statusgrund** im Datensatztitel am oberen Rand aus. Wählen Sie unter **Sprache** die Option **Deutsch – Deutschland** aus.

8. Vervollständigen Sie den Artikel wie folgt:

    - **Titel:** Sensor funktioniert nicht – Ihre Initialen

    - **Schlüsselwörter:** Sensor, beschädigt, funktioniert nicht

    - **Beschreibung:** Dient als Unterstützung, falls ein Sensor nicht funktioniert. 

9. Geben Sie den folgenden Text im **Inhaltsdesigner** ein.   

    Sensor funktioniert nicht

    Gehen Sie wie folgt vor, wenn ein Sensor nicht ordnungsgemäß funktioniert:

    1. Suchen und ersetzen Sie die Batterien im Gerät. 

    2. Halten Sie den Netzschalter drei Sekunden lang gedrückt. 

    3. Das Gerät wird im Administratormodus geöffnet. 

    4. Halten Sie die Koppeln-Taste gedrückt, bis die Lampe von rot zu blau wechselt. 

    5. Drücken Sie die Zurücksetzen-Taste. 

    Nachdem das Gerät neu gestartet wurde, ist es wieder online. 

10. Wählen Sie im Inhaltseditor den Text „Sensor funktioniert nicht“ aus.

11. Ändern Sie den Schriftgrad zu **22**, und wählen Sie die Schaltfläche **Fett** aus. 

12. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Speichern** aus, um den Knowledge-Artikel zu speichern, und lassen Sie ihn offen. 

13. Wählen Sie unter **Neuer Prozess** die Phase **Autor** aus, und legen Sie im Feld **Artikelthema** den Wert **Service** fest. 

14. Legen Sie das Feld **Zur Prüfung markieren** auf **Abgeschlossen** fest.

15. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Prüfen** zu gelangen.

16. Wählen Sie oben auf der **Befehlsleiste** die Schaltfläche **Speichern und schließen** aus, um Ihre Änderungen zu speichern und den Artikel zu schließen.

 

### <a name="task-2-manage-an-article-through-the-approval-process"></a>Aufgabe 2: Artikel mit dem Genehmigungsprozess verwalten

Nachdem ein Autor den Datensatz erstellt hat, durchläuft der Datensatz in den meisten Organisationen zunächst einen Genehmigungsprozess, bevor er live geschaltet wird. Für die Genehmigung ist oft eine andere Person zuständig. In diesem Fall übernehmen wir die Rolle des Genehmigers. 

1. Wechseln Sie unter „Knowledge-Artikel“ zur Ansicht **Vorgeschlagene Artikel**, um Artikel anzuzeigen, die auf Ihre Genehmigung warten. 

2. Öffnen Sie den zuvor erstellten Artikel **Sensor funktioniert nicht – Ihre Initialen**.

3. Wählen Sie unter **Neuer Prozess** die Phase **Prüfen** aus. Legen Sie das Feld **Prüfen** auf **Abgelehnt** fest.

4. Geben Sie im Bildschirm „Knowledge-Artikel ablehnen“ den Text **Lösung funktioniert nicht, Schritte nicht nachvollziehbar** ein.

5. Wählen Sie die Schaltfläche **Ablehnen** aus.

6. Wählen Sie die Schaltfläche **Speichern und schließen** aus, um den Artikeldatensatz zu schließen.

7. Wechseln Sie in der **Ansichtsauswahl** zu **Meine aktiven Artikel**. 

8. Öffnen Sie den Datensatz **Sensor funktioniert nicht – Ihre Initialen**.

9. Wählen Sie anschließend die Registerkarte **Zusammenfassung** aus. 

10. In der **Datensatzzeitachse** erscheint ein Hinweis dazu, dass der Artikel abgelehnt wurde und warum er abgelehnt wurde. 

11. Wählen Sie die Registerkarte **Inhalt** aus.

12. Platzieren Sie Ihren Cursor im Feld **Inhalt** vor das Wort **Drücken** in Schritt 5. 

13. Drücken Sie die **Eingabetaste**. 

14. Geben Sie den Text „Bestätigen-Schaltfläche drücken“ ein. 

15. Wählen Sie in der **Befehlsleiste** die Option **Speichern und schließen** aus.

16. Wechseln Sie mit der **Ansichtsauswahl** zur Ansicht **Vorgeschlagene Artikel**.

17. Öffnen Sie den Artikel **Sensor funktioniert nicht – Ihre Initialen**. 

18. Wählen Sie im Geschäftsprozessflow **Neuer Prozess** die Phase **Prüfen** aus.

19. Ändern Sie den Status zu **Genehmigt**. 

20. Wählen Sie **OK** aus, wenn Sie aufgefordert werden, die Genehmigung des Artikels zu bestätigen. 


### <a name="task-3-approve-the-knowledge-article"></a>Aufgabe 3: Knowledge-Artikel genehmigen

Nachdem der Artikel genehmigt wurde, werden wir ihn veröffentlichen, um ihn für andere Personen bei der Bearbeitung von Anfragen verfügbar zu machen. 

1. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Veröffentlichen** zu gelangen. 

2. Legen Sie für **Produktzuordnungen festlegen** den Wert **Abgeschlossen** fest. 

3. Legen Sie das **Ablaufdatum** auf **heute in einem Jahr um 00:00 Uhr** fest. 

4. Wählen Sie die Schaltfläche **Fertig stellen** aus, um den Prozess abzuschließen. 

5. Wählen Sie auf der **Befehlsleiste** für den Artikel die Schaltfläche **Veröffentlichen** aus. 

6. Vergewissern sie sich, dass die folgenden Einstellungen ausgewählt sind:

    - **Veröffentlichen:** Jetzt

    - **Veröffentlichungsstatus:** Veröffentlicht

    - **Ablaufdatum:** Heute in einem Jahr um 00:00 Uhr

    - **Ablaufzustand:** Expired (Abgelaufen)

    - **Ablaufstatus:** Expired (Abgelaufen)

7. Wählen Sie die Schaltfläche **Veröffentlichen** aus, um den Artikel zu veröffentlichen.


## <a name="exercise-2-manage-a-support-case-through-its-lifecycle"></a>Übung 2: Supportanfrage über ihren Lebenszyklus hinweg verwalten


### <a name="task-1-create-and-manage-a-case"></a>Aufgabe 1: Anfrage erstellen und verwalten

1. Öffnen Sie die **Dynamics 365 Customer Service Hub**-Anwendung, falls noch nicht geschehen. 

2. Wählen Sie **Dashboards** in der Navigation auf der linken Seite des Bildschirms aus. Daraufhin wird das **Ebene-1**-Dashboard geöffnet. 

3. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Visuellen Filter anzeigen** aus.


4. Zusätzliche Dashboards enthalten weitere Details zum aktuellen Anfragevolumen. Sie können die Dashboard-Auswahl verwenden, um zu den anderen Dashboards zu gelangen. Wechseln Sie vom **Ebene-1-Dashboard** zum **Ebene-2-Dashboard**. 

 

Nachdem Sie sich mit den unterschiedlichen Ansichten und Dashboards vertraut gemacht haben, werden wir eine neue Anfrage erstellen, um Piper bei ihrem Problem zu unterstützen.

 

10. Wählen Sie **Anfragen** in der Navigation auf der linken Seite des Bildschirms aus. 

11. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um einen neuen Anfragedatensatz zu erstellen.

12. Vervollständigen Sie den Anfragedatensatz wie folgt:

    - **Anfragetitel:** Sensor funktioniert nicht – Ihre Initialen

    - **Kunde:** Piper Smith

    - **Ursprung:** Telefon

    - **Beschreibung:** Piper hat gemeldet, dass einer der Sensoren, die sie erhalten hat, nicht ordnungsgemäß funktioniert. 

13. Wählen Sie die Schaltfläche **Speichern** aus, um den Datensatz zu speichern, und lassen Sie ihn geöffnet. 

14. Wählen Sie auf der **Datensatzzeitachse** das **Pluszeichensymbol** aus, um eine neue Aktivität zu erstellen. 

15. Wählen Sie im nächsten Menü die Option **Telefonanruf** aus.

16. Füllen Sie die Aktivität im Formular **Schnellerstellung: Telefonanruf** wie folgt aus:

    - **:** Piper zurückrufen

    - **Richtung:** Ausgehend

    - **Telefonnummer:**  888 555-1762

    - **Dauer:** 15 Minuten

17. Wählen Sie **Speichern und schließen** aus. 

18. Wählen Sie unter **Telefon-zu-Anfrage-Prozess** die Phase **Identifizieren** aus.

19. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Recherche** zu gelangen. 

20. Wählen Sie das **X** im Fenster für die Phase **Recherche** aus, um das Fenster zu schließen und Ihre Arbeit fortsetzen zu können. 

21. Wählen Sie auf der **Datensatzzeitachse** das **Pluszeichensymbol** aus, um eine neue Aktivität zu erstellen. 

22. Wählen Sie im nächsten Menü die Option **Aufgabe** aus.

23. Füllen Sie die Aktivität im Formular **Schnellerstellung: Telefonanruf** wie folgt aus:

    - **:** Von Piper gemeldetes Problem recherchieren

    - **Beschreibung:** Wissensdatenbank nutzen, um das von Piper gemeldete Problem zu recherchieren 

    - **Dauer:** 30 Minuten

24. Wählen Sie **Speichern und schließen** aus. 

25. Suchen Sie auf der rechten Seite des Anfragebildschirms das Buchsymbol **Wissen**, und wählen Sie es aus (Das Symbol befindet sich direkt unter dem Schraubenschlüsselsymbol).

26. Beachten Sie, dass der Suchtext automatisch als Titel für die Anfrage verwendet wird. Suchen Sie den zuvor erstellten Artikel **Sensor funktioniert nicht – Ihre Initialen**, und wählen Sie ihn aus. 

27. Der komplette Inhalt des Artikels wird angezeigt. Wählen Sie das Symbol **Daumen hoch** am Ende des Artikels aus, um anzugeben, dass der Artikel hilfreich war. 

28. Wählen Sie das Symbol **Diesen Artikel mit aktuellem Datensatz verknüpfen** aus. Vergewissern Sie sich, dass der Hinweis **Mit Fall verknüpft** angezeigt wird. 

 

### <a name="task-2-close-the-case"></a>Aufgabe 2: Anfrage abschließen

Nachdem wir eine Lösung für das von der Kundin gemeldete Problem haben, können wir uns darauf vorbereiten, die Anfrage abzuschließen. Dazu werden wir zunächst alle offenen Aktivitäten schließen, die zur Anfrage zugeordnet sind. 

1. Zeigen Sie in der **Datensatzzeitachse** auf die zuvor erstellte Aufgabe **Von Piper gemeldetes Problem recherchieren** **.** Wählen Sie das Häkchensymbol **Als erledigt markieren** aus, um die Aktivität abzuschließen. 

2. Vergewissern Sie sich im Fenster **Aufgabe schließen**, dass der Status auf Abgeschlossen festgelegt ist, und wählen Sie die Schaltfläche **Schließen** aus. Der Status der Aufgabe sollte als **Geschlossen** angezeigt werden. 

3. Zeigen Sie auf die zuvor erstellte Telefonanrufaktivität **Piper zurückrufen** **.** Wählen Sie das Häkchensymbol **Als erledigt markieren** aus, um die Aktivität abzuschließen. 

4. Vergewissern Sie sich im Fenster **Telefonanruf schließen**, dass der **Zustand** als **Abgeschlossen** und der **Status** als **Erledigt** angezeigt wird. Wählen Sie die Schaltfläche **Schließen** aus. Vergewissern sie sich, dass die Aktivität in der Zeitachse als geschlossen angezeigt wird 

5. Wählen Sie unter **Telefon-zu-Anfrage-Prozess** die Phase **Recherchieren** aus, und wählen Sie **Nächste Phase** aus, um zur Phase **Auflösen** zu gelangen. 

6. Wählen Sie in der Phase **Auflösen** die Schaltfläche **Fertig stellen** aus, um den Prozessflow abzuschließen. 

7. Wählen Sie auf der **Befehlsleiste** für den Anfragedatensatz die Schaltfläche **Anfrage abschließen** aus.

8. Legen Sie im Fenster **Anfrage abschließen** im Feld **Auflösung** den Wert **Knowledge-Artikel** fest. 

9. Vergewissern Sie sich, dass in den Feldern **Gesamtzeit** und **Fakturierbare Zeit** jeweils der Wert **45 Minuten** angezeigt wird (Dieser Wert entspricht der Gesamtzeit für den Telefonanruf und die Aufgabenaktivitäten, die zum Datensatz hinzugefügt wurden). 

10. Wählen Sie die Schaltfläche **Auflösen** aus, um den Vorgang abzuschließen. 

