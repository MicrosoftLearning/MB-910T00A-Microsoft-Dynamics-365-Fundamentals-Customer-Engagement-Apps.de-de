---
lab:
  title: 'Lab 4.1: Knowledge-Artikel in Dynamics 365 Customer Service erstellen und veröffentlichen'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Customer Service'
ms.openlocfilehash: 2e2c5b6947bb5b366c0daba9d37518981662b28b
ms.sourcegitcommit: 5d822ceab64fbb8615808dcdebeff848eec6ee25
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/06/2022
ms.locfileid: "147855083"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-customer-service"></a>Modul 4 Mehr über die Grundlagen von Dynamics 365 Customer Service erfahren
========================

## <a name="practice-lab-41---create-and-publish-a-knowledge-article-in-dynamics-365-customer-service"></a>Übungs-Lab 4.1: Knowledge-Artikel in Dynamics 365 Customer Service erstellen und veröffentlichen

## <a name="lab-setup"></a>Lab-Einrichtung

  - **Geschätzte Dauer**: 15 Minuten

## <a name="instructions"></a>Anweisungen

1. Öffnen Sie die **Dynamics 365 Customer Service Hub**-Anwendung, falls noch nicht geschehen. 

2. Wählen Sie **Knowledge-Artikel** in der Navigation auf der linken Seite des Bildschirms aus. 

3. Mit dem Dropdownpfeil neben **Meine aktiven Artikel** können Sie jederzeit herausfinden, welche Artikel sich in den einzelnen Phasen befinden. 

4. Wählen Sie **Entwurfsartikel** aus. 

5. Wählen Sie **Genehmigte Artikel** aus. Mindestens ein genehmigter Artikel sollte angezeigt werden.  

6. Wechseln Sie zurück zu **Meine aktiven Artikel**.

7. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus. 

8. Warten Sie, bis der neue Datensatz geöffnet wurde, und wählen Sie den Dropdownpfeil neben dem Feld **Statusgrund** im Datensatztitel am oberen Rand aus. Wählen Sie unter **Sprache** die Option **Deutsch – Deutschland** aus.

9. Vervollständigen Sie den Artikel wie folgt:

    - **Titel:** Artikel beschädigt bei Eingang – Ihre Initialen

    - **Schlüsselwörter:** Defekter Artikel, beschädigt, Rückgabe

    - **Beschreibung:** Hilft bei der Behebung von Problemen, wenn beschädigte Artikel geliefert werden. 

10. Geben Sie den folgenden Text im Inhaltsdesigner ein.   
‎  
‎   Artikel beschädigt geliefert

    Gehen Sie wie folgt vor, wenn ein beschädigter Artikel geliefert wird:

    1. Öffnen Sie unser Webportal.

    2. Suchen Sie Ihre Bestellung.

    3. Wählen Sie „Rückgabeartikel“ aus.

    4. Wählen Sie „Beschädigt“ als Begründung aus.

    5. „Drucken“ auswählen

    Sobald wir den zurückgegebenen beschädigten Artikel erhalten haben, wird Ihnen der Betrag gutgeschrieben.

    **HINWEIS:** Sie können den Text bei Bedarf formatieren. 

11. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Speichern** aus, um den Knowledge-Artikel zu speichern, und lassen Sie ihn offen. 

12. Wählen Sie unter **Neuer Prozess** die Phase **Autor** aus, und legen Sie im Feld **Artikelthema** den Wert **Lieferung** (unter „Service“) fest. 

13. Legen Sie das Feld **Zur Prüfung markieren** auf **Abgeschlossen** fest.

14. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Prüfen** zu gelangen.

15. Wählen Sie oben auf der **Befehlsleiste** die Schaltfläche **Speichern und schließen** aus, um Ihre Änderungen zu speichern und den Artikel zu schließen.

Nachdem ein Autor den Datensatz erstellt hat, durchläuft der Datensatz zunächst einen Genehmigungsprozess, bevor er live geschaltet wird. Als Nächstes werden wir die Rolle des Genehmigers übernehmen und den Artikel genehmigen. 

16. Wechseln Sie unter „Knowledge-Artikel“ zur Ansicht **Vorgeschlagene Artikel**, um Artikel anzuzeigen, die auf Ihre Genehmigung warten. 

17. Öffnen Sie den zuvor erstellten Artikel **Artikel beschädigt bei Eingang – Ihre Initialen**.

18. Wählen Sie unter **Neuer Prozess** die Phase **Prüfen** aus. Legen Sie das Feld **Prüfen** auf **Abgeschlossen** fest.

19. Wählen Sie **OK** aus, wenn Sie aufgefordert werden, die Genehmigung des Artikels zu bestätigen. 

20. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Veröffentlichen** zu gelangen. 

21. Wählen Sie oben auf der **Befehlsleiste** am oberen Rand des Artikels die **vertikalen Auslassungspunkte** links in der Befehlsleiste aus. Wählen Sie im nächsten Menü die Option **Produkt verknüpfen** aus. 

22. Wählen Sie im Fenster **Produkt verknüpfen** die Option **Office 365 für Unternehmen (Beispiel)** aus.

23. Klicken Sie auf die Schaltfläche **Zuordnen**. 

24. Wählen Sie unter **Neuer Prozess** die Phase **Veröffentlichen** aus. 

25. Legen Sie für **Produktzuordnungen festlegen** den Wert **Abgeschlossen** fest. 

26. Legen Sie das **Ablaufdatum** auf **heute in einem Jahr um 00:00 Uhr** fest. 

27. Wählen Sie die Schaltfläche **Fertig stellen** aus, um den Prozess abzuschließen. 

28. Wählen Sie auf der **Befehlsleiste** für den Artikel die Schaltfläche **Veröffentlichen** aus. 

29. Vergewissern sie sich, dass die folgenden Einstellungen ausgewählt sind:

    - **Veröffentlichen:** Jetzt

    - **Veröffentlichungsstatus:** Veröffentlicht

    - **Ablaufdatum:** Heute in einem Jahr um 00:00 Uhr

    - **Ablaufzustand:** Expired (Abgelaufen)

    - **Ablaufstatus:** Expired (Abgelaufen)

    - **Genehmigte Übersetzungen veröffentlichen:** Keine
    
30. Klicken Sie auf die Schaltfläche **Veröffentlichen**, um den Artikel zu veröffentlichen.


