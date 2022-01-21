---
lab:
    title: 'Lab 5.1: Erstellen eines projektbasierten Leads'
    module: 'Modul 5: Mehr über die Grundlagen von Dynamics 365 Project Operations erfahren'
---

Modul 5: Mehr über die Grundlagen von Dynamics 365 Project Operations erfahren
========================

## Übungs-Lab 5.1: Erstellen eines projektbasierten Leads

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

- Einen Projektlead in Dynamics 365 Sales eingeben

## Übungsaufbau

  - **Geschätzte Dauer**: 10 Minuten

## Anleitung

## Übung 1: Erstellen eines projektbasierten Leads

### Aufgabe 1: Neuen Lead erstellen

1. Öffnen Sie einen InPrivate-Browser, und navigieren Sie zu [Https://home.Dynamics.com](https://home.dynamics.com/), falls noch nicht geschehen. 

2. Melden Sie sich mit den Benutzeranmeldeinformationen an, die Sie vom Kursleiter erhalten haben, wenn Sie dazu aufgefordert werden. 

3. Wählen Sie **Project Operations** in der Liste der angezeigten Anwendungen aus. **(Hinweis:** Der Eintrag kann auch als „Projekt-Service“ angezeigt werden)

4. Wählen Sie den Bereich **Projekte** in der Navigation auf der linken Seite des Bildschirms aus. 

5. Wählen Sie im nächsten Menü die Option **Vertrieb** aus.

6. Wählen Sie **Leads** in der Navigation aus. 

7. Um alle aktuellen Vertriebsleads im System anzuzeigen, wählen Sie den Pfeil nach unten neben **Meine offenen Leads** aus, und wählen Sie im nächsten Menü **Aktive Leads** aus. 

8. Um zur Liste Ihrer Leads zurückzukehren, wählen Sie den Pfeil nach unten neben „Aktive Leads“ aus, und wählen Sie im nächsten Menü **Meine offenen Leads** aus. 

9. Als Nächstes werden wir einen neuen Lead für das Unternehmen „Consolidated Sample“ erstellen. Wählen Sie in der Ansicht **Meine offenen Leads** die Schaltfläche **Neu** auf der Befehlsleiste aus.

10. Vervollständigen Sie Ihren neuen Leaddatensatz wie folgt:

	- **Thema:** Vollständige globale Implementierung – Ihre Initialen

	- **Typ:** Arbeitsbasiert

	- **Vorname:** Jean

	- **Nachname:** Anderson – Ihre Initialen

	- **Telefonnummer (geschäftlich):** 888 555-8855

	- **E-Mail:** jean@sample.com

	- **Unternehmen:** Consolidated Sample – Ihre Initialen

	- **Straße 1:** 219 91<sup data-htmlnode="">st</sup> Ave N

	- **Ort:** Seattle

	- **Bundesland/Kanton:** WA

	- **Postleitzahl:** 98001 

11. Wählen Sie die Schaltfläche **Speichern** auf der Befehlsleiste aus, um den neuen Lead zu speichern, und lassen Sie ihn offen.

12. Beachten Sie den Geschäftsprozessflow **Lead für Verkaufschance** am Anfang des Datensatzes. Klicken Sie auf **Phase qualifizieren**, um diese Option auszuwählen. Vervollständigen Sie die Phase wie folgt:

	- **Einkaufszeitrahmen**: Dieses Quartal

	- **Geschätztes Budget:** 25.000  

	- **Kaufvorgang:** Komitee

	- **Entscheidungsträger identifizieren:** Abgeschlossen

13. Klicken Sie auf das **X** im Fenster für die Phase, um das Fenster zu schließen. 

14. Wechseln Sie zu **Datensatzzeitachse** in der Mitte des Bildschirms, und klicken Sie auf das **Pluszeichensymbol**, um eine neue Aktivität hinzuzufügen. 

15. Wählen Sie im nächsten Menü die Option **Telefonanruf** aus.

16. Füllen Sie den Telefonanruf im Fenster „Schnellerstellung eines Telefonanrufs“ wie folgt aus:

	- **Betreff:** Anfänglicher Qualifikationsanruf – Ihre Initialen  

	- **Telefonnummer:** 888 555-8855

	- **Richtung:** Ausgehend

	- **Beschreibung:** Erstkontakt mit Jean, um die anfängliche Qualifikation zu ermitteln. 

17. Klicken Sie auf die Schaltfläche **Speichern und schließen**.

18. Beachten Sie, dass die Aktivität **Anfänglicher Qualifikationsanruf** auf der **Datensatzzeitachse** angezeigt wird. Bewegen Sie den Mauszeiger über die Aktivität, und wählen Sie die Abschlussaktivität **Häkchensymbol** aus, um den Anruf als abgeschlossen zu markieren. 

19. Vergewissern Sie sich im Fenster **Telefonanruf schließen**, dass der Status auf **Abgeschlossen** festgelegt ist, und wählen Sie die Schaltfläche **Schließen** aus.

 

### Aufgabe 2: Lead qualifizieren und zur weiteren Qualifizierung zu einer Verkaufschance konvertieren

1. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Qualifizieren** aus. 

2. Nachdem das System den Lead qualifiziert hat, wird ein neuer Verkaufschancendatensatz erstellt, und der Geschäftsprozess geht in die Phase **Entwickeln** über. Wählen Sie die Phase **Qualifizieren** aus, um den ursprünglichen Leaddatensatz anzuzeigen. 

3. Wählen Sie die Phase **Entwickeln** aus, um zur Verkaufschance zurückzukehren.

4. Klicken Sie auf die Schaltfläche **Speichern und schließen**, um den erstellten Verkaufschancendatensatz zu schließen. 

