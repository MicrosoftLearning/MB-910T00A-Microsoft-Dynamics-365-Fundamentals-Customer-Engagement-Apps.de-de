---
lab:
    title: 'Lab 5.2: Projektbasierte Verkaufschance verwalten'
    module: 'Modul 5: Mehr über die Grundlagen von Dynamics 365 Project Operations erfahren'
---

Modul 5: Mehr über die Grundlagen von Dynamics 365 Project Operations erfahren
========================

## Übungs-Lab 5.2 - Projektbasierte Verkaufschance verwalten

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

Die ABC-Vertriebsmitarbeiter für Unternehmen konzentrieren sich auf Kunden, die spezielle und maßgeschneiderte Unternehmenslösungen für ihre Sicherheit brauchen. Daher umfassen Unternehmensverkäufe oft mehrere Standorte, die miteinander kommunizieren, und für den Projektabschluss sind oft mehrere Ressourcen erforderlich. Die Vertriebszyklen für Unternehmensverkäufe dauern bei ABC oft viele Monate dauern, und die Ausführung ist sehr komplex. 

Nachdem ein Unternehmenskunde ein System gekauft hat, kann es Monate dauern, bis das Projekt implementiert wird. Jedem Projekt wird ein Projektmanager zugewiesen, der die Projektplanung und die alltäglichen Abläufe beaufsichtigt. Dieser Projektmanager erstellt Projektpläne, definiert Projektteams und plant den Einsatz von Ressourcen. 

Als Unternehmensverkäufer sind Sie dafür zuständig, Ihren Kunden hochwertige und maßgeschneiderte Sicherheitslösungen zu verkaufen. Sie haben kürzlich einen Anruf von einem Unternehmen namens „Consolidated Sample“ erhalten. Das Unternehmen benötigt eine komplett integrierte Sicherheitslösung für sämtliche Standorte. Sie werden den Lead für „Consolidated Sample“ in das System eingeben, durch den Projektverkaufszyklus führen und ein entsprechendes Projekt erstellen. 

In diesem Lab werden Sie die folgenden Aufgaben ausführen:

- Einen Lead zu einer Projektverkaufschance qualifizieren und konvertieren

## Übungsaufbau

  - **Geschätzte Dauer**: 20 Minuten
  
## Übung 1: Projektbasierte Verkaufschance verwalten 

Nachdem Sie eine Projektverkaufschance auf Basis eines projektbasierten Leads erstellt haben, können Sie die Verkaufschance nutzen, um allgemeine projektbezogene Details zu definieren. In diesem Schritt definieren Sie Produkte und Arbeitselemente sowie vertriebsrelevante Schätzungen. 

### Aufgabe 1: Verkaufschance verwalten 

1. Wählen Sie **Verkaufschancen** in der Navigation auf der linken Seite des Bildschirms aus. 

2. Finden und öffnen Sie die Verkaufschance **Vollständige globale Sicherheitsimplementierung – Ihre Initialen**, die erstellt wurde, als Sie den Lead qualifiziert haben, in der Liste „Meine offenen Project Service-Verkaufschancen“. Beachten Sie, dass sich der Datensatz bereits in der Phase **Entwickeln** befindet, da er aus einem zuvor qualifizierten Lead erstellt wurde.  

3. Wählen Sie unter **Vollständige globale Sicherheitsimplementierung – Ihre Initialen** oben im Datensatz den Pfeil nach unten neben dem Besitzerfeld aus. 

4. Geben Sie die folgenden Daten ein:

	- **Gesch. Abschlussdatum:** Morgen

	- **Gesch. Umsatz:** 250.000,00

5. Wählen Sie im Geschäftsprozessflow „Lead zu Verkaufschance“ die Phase **Entwickeln** aus. In dieser Phase müssen Sie Stakeholder und Mitbewerber identifizieren.

6. Klicken Sie auf das **X** im Fenster für die Phase, um Ihre Arbeit fortsetzen zu können. 

7. Beachten Sie, dass **Jean** im Unterraster **Stakeholder** bereits als Stakeholder definiert ist. 

8. Wählen Sie im Unterraster „Vertriebsteam“ die Option **Neue Verbindung** aus (Falls die Schaltfläche **Neue Verbindung** nicht angezeigt wird, wählen Sie die **vertikalen Auslassungspunkte** aus, und wählen Sie im nächsten Menü die Option **Neue Verbindung** aus). 

9. Geben Sie im Feld **Suchen** den Text **System** ein, und wählen Sie den **Benutzerdatensatz aus, den Sie vom Kursleiter erhalten haben**. Klicken Sie dann auf die Schaltfläche **Hinzufügen**. Der Systemadministrator sollte jetzt im Vertriebsteam angezeigt werden. Wählen Sie andernfalls in der Befehlsleiste die Schaltfläche **Aktualisieren** aus. 

10. Wählen Sie im Unterraster „Mitbewerber“ die **Vertikalen Auslassungspunkte** aus. Wählen Sie im nächsten Menü **Bestehenden Mitbewerber hinzufügen** aus. 

11. Suchen Sie nach **Coho Security**, und wählen Sie den Eintrag aus. (Falls „Coho Security“ nicht existiert, wählen Sie **Neuer Datensatz** und anschließend **Mitbewerber** aus. Fahren Sie andernfalls mit Schritt 15 fort.)  

12. Geben Sie auf dem Bildschirm Schnellerstellung: **Mitbewerber** im Feld **Name** den Wert **Coho Security – Ihre Initialen** ein.

13. Wählen Sie **Speichern und schließen** aus.

14. Wählen Sie den Datensatz für „Coho Security“ aus einer vorherigen Übung aus, und wählen Sie die Schaltfläche **Hinzufügen** aus. 

15. Wählen Sie die Phase **Entwickeln** im Geschäftsprozessflow **Lead zu Verkaufschance** aus, und setzen Sie die Schritte **Stakeholder identifizieren** und **Mitbewerber identifizieren** auf **Abgeschlossen**. 

16. Klicken Sie auf die Schaltfläche **Nächste Phase**, um zur Phase **Vorschlagen** zu gelangen.

17. Markieren Sie in der Phase **Vorschlagen** den Punkt **Vertriebsteam identifizieren** als **Abgeschlossen**.

18. Klicken Sie auf das **X** im Fenster für die Phase „Vorschlagen“, um das Fenster zu schließen. 

19. Wählen Sie im Verkaufschancendatensatz die Registerkarte **Verkaufschancenzeilen** aus.

20. Wählen Sie im Unterraster „Projektbasierte Zeilen“ die Schaltfläche „Neue Verkaufschancenposition hinzufügen“ aus. Konfigurieren Sie die neue Verkaufschancenposition wie folgt:

	- **Produkttyp:** Projektbasierter Service

	- **Verkaufschance:** Vollständige globale Sicherheitsimplementierung – Ihre Initialen

	- **Name:** Systementwicklung

	- **Kundenbudget:** 25.000

	- **Abrechnungsmethode:** Festpreis

21. Wählen Sie **Speichern und Schließen** aus.

22. Wählen Sie im Unterraster **Projektbasierte Zeilen** erneut die Schaltfläche **Neue Verkaufschancenposition hinzufügen** aus, um eine weitere Position hinzuzufügen.   
Konfigurieren Sie die neue Verkaufschancenposition wie folgt:

	- **Produkttyp:** Projektbasierter Service

	- **Verkaufschance:** Vollständige globale Sicherheitsimplementierung – Ihre Initialen

	- **Name**: Systemimplementierung 

	- **Kundenbudget:** 100.000 

	- **Abrechnungsmethode:** Nach Aufwand

23. Wählen Sie **Speichern und Schließen** aus.
