---
lab:
  title: 'Lab 3.1: Knowledge-Artikel in Dynamics 365 Customer Service erstellen und veröffentlichen'
  module: 'Module 3: Learn the Fundamentals of Dynamics 365 Customer Service'
ms.openlocfilehash: 3133819d99d9fbb317b731db313b1df7bcf8ebba
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908911"
---
<a name="module-3-learn-the-fundamentals-of-dynamics-365-customer-service"></a>Modul 3: Grundlegende Informationen zu Dynamics 365 for Customer Service
========================

## <a name="practice-lab-31---create-and-publish-a-knowlege-article-in-dynamics-365-customer-service"></a>Übungs-Lab 3.1 - Knowledge-Artikel in Dynamics 365 Customer Service erstellen und veröffentlichen

## <a name="lab-setup"></a>Lab-Einrichtung

  - **Geschätzte Dauer**: 15 Minuten

## <a name="instructions"></a>Anweisungen

1. Öffnen Sie die **Dynamics 365 Customer Service Hub**-Anwendung, falls noch nicht geschehen. 

2. Wählen Sie **Knowledge-Artikel** in der Navigation auf der linken Seite des Bildschirms aus. 

3. Mit dem Dropdownpfeil neben **Meine aktiven Artikel** können Sie jederzeit herausfinden, welche Artikel sich in den einzelnen Phasen befinden. 

4. Wählen Sie die Ansicht **Entwurfsartikel** aus. 

5. Wählen Sie **Genehmigte Artikel** aus. 

6. Wechseln Sie zurück zu **Meine aktiven Artikel**.

7. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus. 

8. Warten Sie, bis der neue Datensatz geöffnet wurde, und wählen Sie den Dropdownpfeil neben dem Feld **Statusgrund** im Datensatztitel am oberen Rand aus. Wählen Sie unter **Sprache** die Option **Deutsch – Deutschland** aus.

8. Vervollständigen Sie den Artikel wie folgt:

    - **Titel:** Artikel beschädigt bei Eingang – Ihre Initialen

    - **Schlüsselwörter:** Defekter Artikel, beschädigt, Rückgabe

    - **Beschreibung:** Hilft bei der Behebung von Problemen, wenn beschädigte Artikel geliefert werden. 

9. Geben Sie den folgenden Text im Inhaltsdesigner ein.   
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

10. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Speichern** aus, um den Knowledge-Artikel zu speichern, und lassen Sie ihn offen. 

11. Wählen Sie unter **Neuer Prozess** die Phase **Autor** aus, und legen Sie im Feld **Artikelthema** den Wert **Lieferung** (unter „Service“) fest. 

12. Legen Sie das Feld **Zur Prüfung markieren** auf **Abgeschlossen** fest.

13. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Prüfen** zu gelangen.

14. Wählen Sie oben auf der **Befehlsleiste** die Schaltfläche **Speichern und schließen** aus, um Ihre Änderungen zu speichern und den Artikel zu schließen.

Nachdem ein Autor den Datensatz erstellt hat, durchläuft der Datensatz zunächst einen Genehmigungsprozess, bevor er live geschaltet wird. Als Nächstes werden wir die Rolle des Genehmigers übernehmen und den Artikel genehmigen. 

15. Wechseln Sie unter „Knowledge-Artikel“ zur Ansicht **Vorgeschlagene Artikel**, um Artikel anzuzeigen, die auf Ihre Genehmigung warten. 

16. Öffnen Sie den zuvor erstellten Artikel **Artikel beschädigt bei Eingang – Ihre Initialen**.

17. Wählen Sie unter **Neuer Prozess** die Phase **Prüfen** aus. Legen Sie das Feld **Prüfen** auf **Abgeschlossen** fest.

18. Wählen Sie **OK** aus, wenn Sie aufgefordert werden, die Genehmigung des Artikels zu bestätigen. 

19. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Veröffentlichen** zu gelangen. 

20. Wählen Sie oben auf der **Befehlsleiste** am oberen Rand des Artikels die **vertikalen Auslassungspunkte** links in der Befehlsleiste aus. Wählen Sie im nächsten Menü die Option **Produkt verknüpfen** aus. 

21. Wählen Sie im Fenster **Produkt verknüpfen** die Option **Office 365 für Unternehmen (Beispiel)** aus.

22. Klicken Sie auf die Schaltfläche **Zuordnen**. 

23. Wählen Sie unter **Neuer Prozess** die Phase **Veröffentlichen** aus. 

24. Legen Sie für **Produktzuordnungen festlegen** den Wert **Abgeschlossen** fest. 

25. Legen Sie das **Ablaufdatum** auf **heute in einem Jahr um 00:00 Uhr** fest. 

26. Wählen Sie die Schaltfläche **Fertig stellen** aus, um den Prozess abzuschließen. 

27. Wählen Sie auf der **Befehlsleiste** für den Artikel die Schaltfläche **Veröffentlichen** aus. 

28. Vergewissern sie sich, dass die folgenden Einstellungen ausgewählt sind:

    - **Veröffentlichen:** Jetzt

    - **Veröffentlichungsstatus:** Veröffentlicht

    - **Ablaufdatum:** Heute in einem Jahr um 00:00 Uhr

    - **Ablaufzustand:** Expired (Abgelaufen)

    - **Ablaufstatus:** Expired (Abgelaufen)

    - **Genehmigte Übersetzungen veröffentlichen:** Keine


