---
lab:
  title: 'Lab 4.2: Zeitplanung in Dynamics 365 Field Service'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
ms.openlocfilehash: abbdb5d7f8c2507bebf634a9b0fb1afea8fc8da4
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908819"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>Modul 4: Grundlegende Informationen zu Dynamics 365 for Field Service
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>Übungs-Lab 4.2 - Zeitplanung in Dynamics 365 Field Service

## <a name="lab-setup"></a>Lab-Einrichtung

  - **Geschätzte Dauer**: 20 Minuten

  **Hinweis:** Der Bereich „Buchungsanforderungen“ kann nicht in Internet Explorer geöffnet werden. Verwenden Sie Microsoft Edge oder Google Chrome für diese Übung.
  
## <a name="instructions"></a>Anweisungen

1. Öffnen Sie die **Dynamics 365 Field Service**-Anwendung, falls noch nicht geschehen. 

2. Wählen Sie links im Navigationsbereich den Bereich **Ressourcen** aus, und wählen Sie **Ressourcen** aus.

3. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um eine neue buchbare Ressource zu erstellen.

    - **Ressourcentyp:** Kontakt

    - **Kontakt:** Eleanor Ribeiro

4. Wählen Sie in der **Befehlsleiste** die Option **Speichern und schließen** aus.

5. Wiederholen Sie die Schritte, um drei weitere buchbare Ressourcen zu erstellen.

    - **Ressourcentyp:** Kontakt

    - **Kontakt:** Abbie Gardiner


    - **Ressourcentyp:** Kontakt

    - **Kontakt:** Aidan Knaggs
    
    - Wählen Sie die Registerkarte „Verknüpft“ aus, und fügen Sie „WA“ als neues verknüpftes Gebiet hinzu.


    - **Ressourcentyp:** Kontakt

    - **Kontakt:** Cacilia Viera
    
    - Wählen Sie die Registerkarte „Verknüpft“ aus, und fügen Sie „WA“ als neues verknüpftes Gebiet hinzu.


6. Wählen Sie in der **Befehlsleiste** die Option **Speichern und schließen** aus.

27 Wählen Sie links im Navigationsbereich den Bereich **Dienst** aus, und wählen Sie **Arbeitsaufträge** aus.

8. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um einen neuen Arbeitsauftrag zu erstellen.

9. Füllen Sie die Details des Arbeitsauftrags wie folgt aus:

    - **Dienstkonto:** Adatum Corporation

    - **Arbeitsauftragstyp:** Dienst-

    - **Preisliste:** CRM-Dienst USE (Beispiel)

    - **Steuerpflichtig:** Keine

10. Wählen Sie **Speichern** aus, um Ihre Änderungen zu speichern.

    - **Primärer Vorfalltyp:** Gerät überhitzt (Neu erstellen)

11. Wählen Sie auf der **Befehlsleiste** für den **Arbeitsauftrag** die Schaltfläche **Buchen** aus. Daraufhin wird der **Zeitplan-Assistent** geöffnet. 

12. Dort sollten die Planungsoptionen für den Artikel angezeigt werden. Wählen Sie den Datensatz **Abbie Gardiner** aus.

13. Legen Sie im Fenster **Ressourcenbuchung erstellen** die **Startzeit** auf den Anfang der nächsten Stunde fest.

14. Legen Sie die **Endzeit** auf **2,5 Stunden** später fest. 

15. Wählen Sie die Schaltfläche **Buchen und beenden** aus, um den Artikel zu buchen und das Planungsfenster zu schließen. 

16. Wenn wieder der Arbeitsauftrag angezeigt wird, wählen Sie die Option **Speichern und schließen** in der Befehlsleiste aus. 

17. Wählen Sie im linken Navigationsbereich die Option **Arbeitsaufträge** aus. Wählen Sie die Ansicht **Nicht geplante Arbeitsaufträge** aus.

18. Unten auf der Seite wird der Bereich mit den Buchungsanforderungen angezeigt. Verwenden Sie den Ziehpunkt in der Mitte des Bereichs, um den Bereich zu öffnen. Wählen Sie die Registerkarte **Nicht geplante Arbeitsaufträge** aus.

19. Wählen Sie den zuvor erstellten **Adventure Works**-Arbeitsauftrag anhand der Arbeitsauftragsnummer aus, die Sie sich notiert haben. Wählen Sie in den angezeigten Optionen die Option **Verfügbarkeit finden** aus. 

20. Daraufhin wird der **Zeitplan-Assistent** geöffnet. 

21. Dort sollten die Planungsoptionen für den Artikel angezeigt werden. Wählen Sie den Datensatz „Aidan Knaggs“ aus.

22. Legen Sie im Fenster **Ressourcenbuchung erstellen** die **Startzeit** auf den Anfang der nächsten Stunde fest.

23. Legen Sie die **Endzeit** auf **2,5 Stunden** später fest. 

24. Wählen Sie die Schaltfläche **Buchen und beenden** aus, um den Artikel zu buchen und das Planungsfenster zu schließen. 

25. Es kann vorkommen, dass Sie einen Arbeitsauftrag aufgrund von Konflikten im Zusammenhang mit Technikern oder anderen Ressourcen umbuchen müssen. Dazu können Disponenten die Zeitplanübersicht verwenden. 

26. Wählen Sie das Feld „Ressourcen suchen“ in der Zeitplanübersicht (direkt über der Spalte „Ressourcenname“) aus, geben Sie „Abbie“ ein, und suchen Sie den Arbeitsauftrag, der im Verlauf des heutigen Tages für Abbie geplant ist. 

27. Klicken Sie mit der rechten Maustaste auf den Arbeitsauftrag. Wählen Sie im angezeigten Menü **Ersatzressource** und **Ersatz suchen** aus **.**

