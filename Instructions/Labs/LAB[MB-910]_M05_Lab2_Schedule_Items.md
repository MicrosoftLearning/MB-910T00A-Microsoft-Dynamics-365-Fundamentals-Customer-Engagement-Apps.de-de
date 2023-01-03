---
lab:
  title: "Lab\_5.2: Zeitplanung in Dynamics 365 Field Service"
  module: 'Module 5: Learn the Fundamentals of Dynamics 365 Field Service'
---

<a name="module-5-learn-the-fundamentals-of-dynamics-365-field-service"></a>Modul 5 Mehr über die Grundlagen von Dynamics 365 Field Service erfahren
========================

## <a name="practice-lab-52---schedule-items-in-dynamics-365-field-service"></a>Übungs-Lab 5.2: Zeitplanung in Dynamics 365 Field Service

## <a name="lab-setup"></a>Lab-Einrichtung

  - **Geschätzte Dauer**: 20 Minuten

  **Hinweis:** Der Bereich „Buchungsanforderungen“ kann nicht in Internet Explorer geöffnet werden. Verwenden Sie Microsoft Edge oder Google Chrome für diese Übung.
  
## <a name="instructions"></a>Anweisungen

1. Öffnen Sie die **Dynamics 365 Field Service**-Anwendung, falls noch nicht geschehen.

2. Wählen Sie links im Navigationsbereich die Option **Arbeitsaufträge** aus.

3. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um einen neuen Arbeitsauftrag zu erstellen.

4. Füllen Sie die Details des Arbeitsauftrags wie folgt aus:

    - Dienstkonto: Adatum Corporation

    - Primärer Vorfalltyp: MRI-Scanner ausgefallen

    - Preisliste: US-Fakturierungsraten

    - Arbeitsauftragstyp: Wählen Sie in der Suche die Option „Dienstanruf“ aus.

    - Steuerpflichtig: Keine

5. Wählen Sie **Speichern** aus, um Ihre Änderungen zu speichern und weiterhin den neu erstellten Datensatz zu verwenden.

6. Wählen Sie auf der **Befehlsleiste** für den **Arbeitsauftrag** die Schaltfläche **Buchen** aus. Daraufhin wird der **Zeitplan-Assistent** geöffnet.

7. Dort sollten die Planungsoptionen für den Artikel angezeigt werden. Wählen Sie den Datensatz **Ryan Brim** aus.

8. Legen Sie im Fenster **Ressourcenbuchung erstellen** die **Startzeit** auf den **Anfang der nächsten Stunde** fest.

9. Legen Sie die **Endzeit** auf 2,5 Stunden später fest.

10. Wählen Sie die Schaltfläche **Buchen und beenden** aus, um den Artikel zu buchen und das Planungsfenster zu schließen.

11. Daraufhin gelangen Sie zurück zum Arbeitsauftrag. Wählen Sie die Schaltfläche **Speichern und schließen** in der **Befehlsleiste** aus.

12. Klicken Sie im linken Navigationsbereich auf **Zeitplanübersicht**.

13. Wählen Sie unten auf dem Bildschirm im Anforderungsbereich die Option **Nicht geplante Arbeitsaufträge** aus.

14. Wählen Sie den zuvor erstellten **Adventure Works**-Arbeitsauftrag fest, und verwenden Sie die Arbeitsauftragsnummer, die Sie sich notiert haben. Wählen Sie in den angezeigten Optionen die Option **Verfügbarkeit finden** aus.

15. Daraufhin wird der **Zeitplan-Assistent** geöffnet.

16. Dort sollten die Planungsoptionen für den Artikel angezeigt werden. Wählen Sie den Datensatz „Bob Kozak“ aus.

17. Legen Sie im Fenster **Ressourcenbuchung erstellen** die **Startzeit** auf den **Anfang der nächsten Stunde** fest.

18. Legen Sie die **Endzeit** auf 2,5 Stunden später fest.

19. Wählen Sie die Schaltfläche **Buchen und beenden** aus, um den Artikel zu buchen und das Planungsfenster zu schließen.

20. Es kann vorkommen, dass Sie einen Arbeitsauftrag aufgrund von Konflikten im Zusammenhang mit Technikern oder anderen Ressourcen umbuchen müssen. Dazu können Disponenten die Zeitplanübersicht verwenden.

21. Klicken Sie in der Zeitplanübersicht auf das Feld „Ressourcen suchen“ (über der Spalte „Ressourcenname“), geben Sie „Ryan“ ein, und suchen Sie den Arbeitsauftrag, für den Ryan heute eingeplant ist.

22. Klicken Sie mit der rechten Maustaste auf den Arbeitsauftrag. Wählen Sie im angezeigten Menü **Ersatzressource** und **Ersatz suchen** aus.
