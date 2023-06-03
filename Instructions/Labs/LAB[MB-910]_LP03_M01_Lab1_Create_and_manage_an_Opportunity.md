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

    - **Thema**: Möchte die vorhandene Ausrüstung aktualisieren

    - **Vorname**: Jane

    - **Nachname**: Anderson (Ihre Initialen)

    - **Position:** CEO

    - **Telefon (geschäftlich)** : 888-555-6767

    - **E-Mail-Adresse**: [JaneA@sample.com](mailto:JaneA@sample.com)

    - **Unternehmen**: ABC Consulting

    - **Straße 1**: 1987 191<sup data-htmlnode="">st</sup> Ave N

    - **Ort**: Fargo

    - **Bundesland/Kanton**: ND

    - **Postleitzahl**: 58102

5. Wählen Sie die Schaltfläche **Speichern** aus, um den neuen Lead zu speichern, und lassen Sie die Seite offen. 

    - **Einkaufszeitrahmen:** Dieses Quartal

    - **Budgetbetrag:** 50.000

    - **Kaufvorgang:** Individuell

6. Wählen Sie im Vertriebsprozess **Lead für Verkaufschance** die Phase **Qualifizieren** aus.

7. Gehen Sie wie folgt weiter vor:

    - **Einkaufszeitrahmen**: Sofort

    - **Geschätztes Budget**: 50.000 USD 

    - **Kaufvorgang:** Komitee

8. Klicken Sie mit der Maus außerhalb der Phase **Qualifizieren**, um sie zu schließen. 

9. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Qualifizieren** aus. 

    Das System schließt den Datensatz **Lead** und erstellt einen neuen Datensatz **Verkaufschance**. Beachten Sie, dass der Geschäftsprozessflow **Lead zu Verkaufschance** automatisch in die Phase **Entwickeln** weitergegeben wurde. 

10. Wählen Sie unter **Kopfzeile der Verkaufschance** oben im Datensatz den Abwärtspfeil neben dem Feld **Besitzer** aus.

11. Gehen Sie wie folgt weiter vor:
    - **Gesch. Abschlussdatum:** Zwei Tage ab heute

    - **Gesch. Umsatz**: 50.000 USD
        
12. Beachten Sie im Unterraster **Stakeholder**, dass **Jane Anderson** (Ihre Initialen) bereits als Stakeholder definiert ist.

13. Wählen Sie im Unterraster **Vertriebsteam** die **vertikalen Auslassungspunkte** aus. Wählen Sie im nächsten Menü **Neue Verbindung** aus.

14. Suchen Sie nach Ihrem Benutzerdatensatz, und wählen Sie ihn aus. Wenn Sie fertig sind, klicken Sie auf die Schaltfläche **Hinzufügen**.

15. Wählen Sie im Unterraster „Mitbewerber“ die **vertikalen Auslassungspunkte** aus (drei untereinander angeordnete Punkte). Wählen Sie im nächsten Menü **Bestehenden Mitbewerber hinzufügen** aus.

16. Wählen Sie im Bildschirm **Datensatz suchen** erst **Neuer Datensatz** und dann **Mitbewerber** aus.

17. Legen Sie auf dem Bildschirm **Schnellerfassung für Mitbewerber** das Feld **Name** auf **Coho Technologies (Ihre Initialen)** fest.

18. Wählen Sie **Speichern und schließen** aus.

19. **Coho Technologies** sollte im Suchdatensatzfenster ausgewählt werden. Klicken Sie auf die Schaltfläche **Hinzufügen**, um das Hinzufügen des Mitbewerbers abzuschließen.

20. Wählen Sie im Geschäftsprozessflow **Lead zu Verkaufschance** die Phase **Entwickeln** aus. 

21. Gehen Sie wie folgt weiter vor:

    - **Stakeholder identifizieren**: Markieren Sie diese Phase als abgeschlossen.

    - **Mitbewerber identifizieren**: Markieren Sie diese Phase als abgeschlossen. 

22. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Vorschlagen** zu gelangen. 

23. Markieren Sie in der Phase **Vorschlagen** alle vier Aufgaben als **abgeschlossen**. 

24. Markieren Sie in der Phase **Abschließen** alle Aufgaben als **abgeschlossen**. 

25. Wählen Sie im Geschäftsprozessflow die Schaltfläche **Fertigstellen** aus. 

26. Wählen Sie auf der Zeitachse die Schaltfläche „Neu“ aus. Nachdem Sie den Geschäftsprozess abgeschlossen haben, müssen Sie die Verkaufschance schließen. Wählen Sie auf der **Befehlsleiste** der Verkaufschance die Schaltfläche **Als „Gewonnen“ schließen** aus.

27. Klicken Sie auf dem Bildschirm **Verkaufschance schließen** auf die Schaltfläche **OK**, um den Datensatz der Verkaufschance vollständig zu schließen.


