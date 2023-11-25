---
lab:
  title: "Lernpfad\_3 – Lab\_3.1: Erstellen und Verwalten einer Verkaufschance in Dynamics 365 Sales"
  learning path: Explore the fundamentals of Microsoft Dynamics 365 Sales
  module: Explore Dynamics 365 Sales
---


Lernpfad 3 – Modul 1: Erkunden von Dynamics 365 Sales
========================

## Übungs-Lab 3.1: Erstellen und Verwalten einer Verkaufschance in Dynamics 365 Sales 

## Ziele

Während dieser Übung erstellen Sie manuell einen Lead für Jane Anderson. Jane arbeitet für eine Firma namens **ABC Consulting**. Sie erfassen nicht nur die Leadinformationen im System, sondern nutzen auch die in Dynamics 365 Sales verfügbaren Tools, um den Lead als Verkaufschance zu qualifizieren und bis zum Abschließen zu bearbeiten.

## Lab-Einrichtung

  - **Geschätzte Dauer**: 20 Minuten

## Anweisungen

1. Öffnen Sie die **Dynamics 365 Sales Hub**-Anwendung, falls noch nicht geschehen.

2. Wählen Sie über die Navigation auf der linken Seite des Bildschirms **Leads** aus. 

3. Wählen Sie in der Ansicht **Meine offenen Leads** die Schaltfläche **Neu** aus, um einen neuen Lead zu erstellen. 

4. Geben Sie folgende Informationen zum **Lead** ein:

    - **Thema:** Möchte vorhandenes Arbeitsgerät aktualisieren (Ihre Initialen)

    - **Vorname**: Jane

    - **Nachname**: Anderson (Ihre Initialen)

    - **Position:** CEO

    - **Telefon (geschäftlich)** : 888-555-6767

    - **E-Mail:** JaneA(Ihre Initialen)@sample.com

    - **Unternehmen:** ABC Consulting (Ihre Initialen)

    - **Straße 1**: 1987 191st Ave N

    - **Stadt**: Fargo

    - **Bundesland/Kanton**: ND

    - **Postleitzahl**: 58102

5. Wählen Sie im Vertriebsprozess **Lead für Verkaufschance** die Phase **Qualifizieren** aus.

6. Gehen Sie wie folgt weiter vor:

    - **Kaufzeitrahmen**: Sofort

    - **Geschätztes Budget**: 50.000 USD 

    - **Kaufvorgang:** Komitee

7. Schließen Sie das Fly-Out der **Qualifikationsphase** . 

8.  Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Qualifizieren** aus. 

    **Hinweis:** Wenn die Schaltfläche Qualifizieren nicht angezeigt wird, wählen Sie die Schaltfläche **Weitere Befehle** aus (die drei vertikalen Punkte). 

    Das System schließt den Datensatz **Lead** und erstellt einen neuen Datensatz **Verkaufschance**. Beachten Sie, dass der Geschäftsprozessflow **Lead zu Verkaufschance** automatisch in die Phase **Entwickeln** weitergegeben wurde. 

9. Wählen Sie unter **Kopfzeile der Verkaufschance** oben im Datensatz den Abwärtspfeil neben dem Feld **Besitzer** aus. 

10. Gehen Sie wie folgt weiter vor:

    - **Gesch. Abschlussdatum:** Zwei Tage ab heute

    - **Gesch. Umsatz**: 50.000 USD
    
11. Beachten Sie im Unterraster **Stakeholder**, dass **Jane Anderson** (Ihre Initialen) bereits als Stakeholder definiert ist. 

12. Wählen Sie im Unterraster **Vertriebsteam** die **vertikalen Auslassungspunkte** aus. Wählen Sie im nächsten Menü **Neue Verbindung** aus. 

13. Suchen Sie nach Ihrem Benutzerdatensatz, und wählen Sie ihn aus. Wenn Sie fertig sind, wählen Sie die Schaltfläche **Hinzufügen** aus. 

14. Wählen Sie im Unterraster **Mitbewerber** die **vertikalen Auslassungspunkte** aus (drei untereinander angeordnete Punkte). Wählen Sie im nächsten Menü **Bestehenden Mitbewerber hinzufügen** aus. 

15. Wählen Sie im Bildschirm **Datensatz suchen** erst **Neuer Datensatz** und dann **Mitbewerber** aus.

16. Legen Sie auf im Formular **Schnellerfassung für Mitbewerber** das Feld **Name** auf **Coho Technologies (Ihre Initialen)** fest.

17. Wählen Sie **Speichern und schließen** aus.

18. **Coho Technologies** sollte im Suchdatensatzfenster ausgewählt werden. Klicken Sie auf die Schaltfläche **Hinzufügen**, um das Hinzufügen des Mitbewerbers abzuschließen.

19. Wählen Sie unter Geschäftsprozessflow **Lead zu Verkaufschance** die Phase **Entwickeln** aus. 

20. Gehen Sie wie folgt weiter vor: 

    - **Stakeholder identifizieren**: Abgeschlossen 

    - **Mitbewerber identifizieren**: Abgeschlossen 

21. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Vorschlagen** zu gelangen. 

22. Markieren Sie in der Phase **Vorschlagen** alle vier Aufgaben als **abgeschlossen**. Wählen Sie **Nächste Phase** aus.

23. Markieren Sie in der Phase **Abschließen** alle Aufgaben als **abgeschlossen**. 

24. Wählen Sie im Geschäftsprozessflow die Schaltfläche **Fertigstellen** aus. 

    Nachdem Sie den Geschäftsprozess abgeschlossen haben, müssen Sie die Verkaufschance schließen.

25. Wählen Sie auf der **Befehlsleiste** der Verkaufschance die Schaltfläche **Als „Gewonnen“ schließen** aus.

26. Wählen Sie im Dialogfeld **Verkaufschance abschließen** die Schaltfläche **OK** aus, um das Abschließen der Verkaufschance fertigzustellen. 

