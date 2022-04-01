---
lab:
  title: 'Lab 5.3: Dynamics 365 Project Operations Capstone-Lab'
  module: 'Module 5: Learn the Fundamentals of Dynamics 365 Project Operations'
ms.openlocfilehash: 29ccc6c69e61b6a2f2da8993e2b5fc29716284e2
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908839"
---
<a name="module-5-learn-the-fundamentals-of-dynamics-365-project-operations"></a>Modul 5 Grundlagen von Dynamics 365 Project Operations erlernen
========================

## <a name="practice-lab-53---dynamics-365-project-operations-capstone-lab"></a>Übungs-Lab 5.3 - Dynamics 365 Project Operations Capstone-Lab

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

Die ABC-Vertriebsmitarbeiter für Unternehmen konzentrieren sich auf Kunden, die spezielle und maßgeschneiderte Unternehmenslösungen für ihre Sicherheit brauchen. Daher umfassen Unternehmensverkäufe oft mehrere Standorte, die miteinander kommunizieren, und für den Projektabschluss sind oft mehrere Ressourcen erforderlich. Die Vertriebszyklen für Unternehmensverkäufe dauern bei ABC oft viele Monate dauern, und die Ausführung ist sehr komplex. 

Nachdem ein Unternehmenskunde ein System gekauft hat, kann es Monate dauern, bis das Projekt implementiert wird. Jedem Projekt wird ein Projektmanager zugewiesen, der die Projektplanung und die alltäglichen Abläufe beaufsichtigt. Dieser Projektmanager erstellt Projektpläne, definiert Projektteams und plant den Einsatz von Ressourcen. 

Als Unternehmensverkäufer sind Sie dafür zuständig, Ihren Kunden hochwertige und maßgeschneiderte Sicherheitslösungen zu verkaufen. Sie haben kürzlich einen Anruf von einem Unternehmen namens „Consolidated Sample“ erhalten. Das Unternehmen benötigt eine komplett integrierte Sicherheitslösung für sämtliche Standorte. Sie werden den Lead für „Consolidated Sample“ in das System eingeben, durch den Projektverkaufszyklus führen und ein entsprechendes Projekt erstellen. 

In diesem Lab werden Sie die folgenden Aufgaben ausführen:

- Alltägliche Aktivitäten im Zusammenhang mit einer Projektverkaufschance verwalten 

- Projektangebot hinzufügen, erstellen und definieren 

- Projektvertrag generieren 

- Projekt erstellen und ein Projektteam definieren 

## <a name="lab-setup"></a>Lab-Einrichtung

  - **Geschätzte Dauer**: 45 Minuten

## <a name="instructions"></a>Anweisungen

## <a name="exercise-1-create-a-project-quote--project-estimate"></a>Übung 1: Erstellen eines Projektangebots und einer Projektschätzung

Die Projektverkaufschance wird verwendet, um allgemeine Details über ein potenzielles Projekt zu erfassen. Wenn weitere Details zum Projekt bekannt werden, können Sie ein Projektangebot erstellen. Das Projektangebot enthält oft Details im Zusammenhang mit verschiedenen Rollen, Zeitachsen und Preisen. Das Projektangebot wird dem Kunden vorgelegt. Im Projektangebot können Sie auch damit beginnen, einen Projektplan für das Projekt zu erstellen, das Sie verkaufen. Auf diese Weise können Sie nach dem Verkaufsabschluss Zeit sparen, da viele Details für das Projekt bereits erfasst wurden.

In dieser Übung erstellen Sie ein Projekt und definieren Details für das Projektangebot. 

### <a name="task-1-create-a-project-quote"></a>Aufgabe 1: Erstellen Sie ein Projektangebot.  

1. Wählen Sie in der geöffneten Projektverkaufschance die Registerkarte **Angebote** aus. 

2. Wählen Sie im Unterraster „Angebote“ die Schaltfläche **Neues Angebot** aus.

3. Nachdem der neue Angebotsdatensatz geöffnet wurde, legen Sie im Feld **Produktpreisliste** für das Angebot den Wert **US-Fakturierungsraten** fest. 

4. Wählen Sie die Registerkarte **Angebotszeilen** aus.

5. Wählen Sie die Zeile **Systemimplementierung** aus, und öffnen Sie den Datensatz. 

6. Wählen Sie im Feld **Projekt** die Option **Neues Projekt** aus. 

7. Füllen Sie das Projekt im Bildschirm **Schnellerfassung eines Projekts** wie folgt aus:

    - **Name:** Vollständige globale Implementierung – Ihre Initialen

    - **Projektmanager:** Wählen Sie Ihren Benutzer aus

    - **Kalendervorlage:** Standardarbeitsvorlage

    - **Vertragseinheit:** Fabrikam US

    - **Geschätztes Startdatum:** Eine Woche ab heute

    - **Geschätzte Arbeitskosten:** 175.000 USD

    - **Geschätzte Ausgabenkosten:** 50.000 USD

    - **Geschätzte Gesamtkosten:** 225.000 USD

8. Wählen Sie die Schaltfläche **Speichern und schließen** aus.

9. Als Nächstes legen wir fest, ob wir bestimmte Rollen abrechnen können, die dem Projekt zugewiesen wurden. Wählen Sie die Registerkarte **Fakturierbare Rollen** aus.

10. Wählen Sie die Rolle **Robotikexperte** aus, und legen Sie den Abrechnungstyp auf „Nicht fakturierbar“ fest.

11. Wählen Sie in der **Befehlsleiste** die Option **Speichern und schließen** aus.

12. Wählen Sie die Registerkarte **Detailinformationen zur Angebotsposition** aus.

13. Wählen Sie im Unterraster die Schaltfläche **Neues Detail zur Angebotsposition** aus.

14. Füllen Sie das **Detail zur Angebotsposition** wie folgt aus:

    - **Beschreibung:** Kommunikationsleitung verlegen – Ihre Initialen

    - **Transaktionsklasse:** Zeit

    - **Rolle:** Netzwerktechniker

    - **Kategorie:** Zeit

    - **Startdatum:** Ein Monat ab heute

    - **Enddatum:** Zwei Monate ab heute

    - **Ressourcenzuordnungseinheit:** Fabrikam US

    - **Einheit:** Stunde


15. Wählen Sie die Schaltfläche **Speichern und schließen** aus, um das Detailelement für die Position zu schließen. 

16. Wählen Sie in der **Befehlsleiste** die Option **Speichern und schließen** aus. 


**Hinweis:** Lassen Sie das Projektangebot geöffnet, da Sie es in der nächsten Aufgabe verwenden werden. 


### <a name="task-2-close-the-project-quote-and-create-a-project-contract"></a>Aufgabe 2: Schließen Sie das Projektangebot, und erstellen Sie einen Projektvertrag.

In dieser Aufgabe schließen Sie das zuvor erstellte Projektangebot und konvertieren es zu einem Projektvertrag. Der Projektvertrag kann anschließend in der Ausführungsphase des Projekts genutzt werden. 


1. Wählen Sie auf der Befehlsleiste der Verkaufschance **Vollständige globale Sicherheitsimplementierung – Ihre Initialen** die Schaltfläche **Als „Gewonnen“ schließen** aus. 

2. Wählen Sie im Bildschirm **Möchten Sie das Angebot wirklich schließen** die Option **OK** aus.

3. Nachdem das Angebot geschlossen wurde, wird der neu erstellte Projektvertrag **Vollständige globale Sicherheitsimplementierung – Ihre Initialen** angezeigt. 

 

**Hinweis:** Lassen Sie den Projektvertrag geöffnet, da Sie ihn in der nächsten Aufgabe verwenden werden. 

## <a name="exercise-2-manage-a-project"></a>Übung 2: Projekt verwalten

Die Projektverkaufsfunktionen in Project Operations bieten den Vorteil, dass Sie das Prozess schon während des Vertriebsprozesses erstellen können. Das erstellte Projekt ist in verschiedenen vertriebsbezogenen Datensätzen verfügbar, z. B. in Projektangeboten und Projektverträgen. 

In dieser Übung verwalten Sie einige der anfänglichen Aufgaben für ein Projekt und definieren Projektdetails, ein Projektteam und einige Projektaufgaben. 


### <a name="task-1-manage-basic-project-data"></a>Aufgabe 1: Verwalten Sie grundlegende Projektdaten. 

1. Wählen Sie im geöffneten Projektvertrag **Vollständige globale Sicherheitsimplementierung – Ihre Initialen** die Registerkarte **Zugehörig** aus. 

2. Wählen Sie im nächsten Menü die Option **Projekte** aus.

3. Öffnen Sie das Projekt **Vollständige globale Sicherheitsimplementierung – Ihre Initialen**. 

4. Wählen Sie im Geschäftsprozessflow **Projektservice** die Phase **Neu** aus, und wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Angebot** zu gelangen. 

5. Legen Sie in der Phase **Angebot** im Feld **Voraussichtliches Fertigstellungsdatum** den Wert **Sechs Monate ab heute** fest. 

6. Wählen Sie die Schaltfläche **Nächste Phase** aus, um zur Phase **Planen** zu gelangen. 

 
### <a name="task-2-create-a-project-team"></a>Aufgabe 2: Erstellen Sie ein Projektteam.

Jedes Projekt verfügt über ein Team von Mitgliedern, die für die Ausführung des Projekts zuständig sind. In dieser Aufgabe definieren wir die Ressourcen, aus denen die Mitglieder des Projektteams bestehen werden. 

 
1. Wählen Sie im geöffneten Projektdatensatz **Vollständige globale Sicherheitsimplementierung – Ihre Initialen** die Registerkarte **Team** aus.

2. Wählen Sie im Unterraster **Alle Teammitglieder** die Schaltfläche **+ Neu** aus.

3. Konfigurieren Sie den Eintrag für das Teammitglied wie folgt:

    - **Positionsname:** Robotikexperte – Ihre Initialen

    - **Buchbare Ressource:** Allison Dickson

    - **Rolle:** Robotikexperte

4. Wählen Sie den Pfeil neben der Schaltfläche „Speichern und schließen“ aus. Wählen Sie im nächsten Menü die Option **Speichern und neu erstellen** aus.

5. Konfigurieren Sie den Eintrag für das nächste Teammitglied wie folgt:

    - **Positionsname:** Softwareentwickler – Ihre Initialen

    - **Buchbare Ressource:** Bob Kozak

    - **Rolle:** Softwareentwickler

6. Wählen Sie den Pfeil neben der Schaltfläche „Speichern und schließen“ aus. Wählen Sie im nächsten Menü die Option **Speichern und neu erstellen** aus.

7. Konfigurieren Sie den Eintrag für das Teammitglied wie folgt:

    - **Positionsname:** Netzwerktechniker – Ihre Initialen

    - **Buchbare Ressource:** Dianna Woodward

    - **Rolle:** Netzwerktechniker

8. Wählen Sie die Schaltfläche **Speichern und schließen** aus.


### <a name="task-3-define-a-project-schedule"></a>Aufgabe 3: Definieren Sie einen Projektplan.

Beim Definieren von Projekten ist es auch wichtig, die Projektaufgaben und den Zeitplan für das Projekt zu definieren. In dieser Aufgabe fügen wir Projektaufgaben hinzu und ordnen sie zu unterschiedlichen Rollen zu. 


1. Wählen Sie im geöffneten Projekt **Vollständige globale Sicherheitsimplementierung – Ihre Initialen** die Registerkarte **Zeitplan** aus. 

2. Wählen Sie in der Symbolleiste im Unterraster „Zeitplan“ die Schaltfläche **+ Hinzufügen** aus. 

3. Geben Sie in der neu hinzugefügten Zeile im Feld **Name** den Wert **Systementwicklung** ein.

4. Wählen Sie in der Symbolleiste im Unterraster „Zeitplan“ erneut die Schaltfläche **+ Hinzufügen** aus, um ein weiteres Element hinzuzufügen. 

5. Konfigurieren Sie das Element wie folgt:

    - **Name:** Systemlayout erstellen

    - **Aufwand:** 25

6. Wählen Sie in der Symbolleiste im Unterraster „Zeitplan“ erneut **+ Hinzufügen** aus, um eine weitere Aufgabe hinzuzufügen. 

7. Konfigurieren Sie das Element wie folgt:

    - **Name:** Kameras gestalten

    - **Vorherige Aktivität:** Systemlayout erstellen

    - **Aufwand:** 50

8. Wählen Sie in der Symbolleiste im Unterraster „Zeitplan“ die Schaltfläche **+ Hinzufügen** aus, um eine letzte Aufgabe hinzuzufügen. 

9. Konfigurieren Sie das Element wie folgt:

    - **Name:** Design prüfen und genehmigen

    - **Vorherige Aktivität:** Kameras gestalten

    - Aufwand: 8 

 
**Hinweis:** Lassen Sie die Registerkarte „Zeitplan“ geöffnet, da wir dort in der nächsten Aufgabe weitere Änderungen vornehmen werden. 


### <a name="task-4-associate-resources-with-a-project"></a>Aufgabe 4: Ordnen Sie Ressourcen zu einem Projekt zu.

Beim Definieren des Projektzeitplans können Sie angeben, welche Ressourcen eingesetzt werden, um die Personalanforderungen zu erfüllen. Dabei können Sie entweder tatsächliche benannte Ressourcen oder generische Ressourcen verwenden, die später durch benannte Ressourcen ersetzt werden. In dieser Aufgabe definieren sie sowohl benannte als auch generische Ressourcen für die erstellten Projektaufgaben. 

1. Öffnen Sie ggf. das Projekt **Vollständige globale Sicherheitsimplementierung – Ihre Initialen**, und wählen Sie die Registerkarte **Zeitplan** aus. 

2. Suchen Sie die zuvor erstellte Aufgabe **Systemlayout erstellen** im Feld **Ressourcen**, und wählen Sie sie aus. 

3. Wählen Sie im nächsten Menü die Option **Erstellen** aus. 

4. Konfigurieren Sie das Projektteammitglied wie folgt:

    - **Positionsname:** Generischer Robotikexperte – Ihre Initialen

    - **Buchbare Ressource:** Generische Ressource

    - **Rolle:** Robotikexperte

5. Wählen Sie **Speichern und schließen** aus. 

6. Vergewissern Sie sich, dass die Ressourcen **Generischer Robotikexperte – Ihre Initialen** zum Feld „Ressourcen“ hinzugefügt wurden. 

7. Suchen Sie die Aufgabe **Kameras gestalten**, und wählen Sie das Feld **Ressourcen** aus. 

8. Wählen Sie im nächsten Menü die Option **Erstellen** aus. 

9. Konfigurieren Sie das Projektteammitglied wie folgt:

    - **Positionsname:** Generischer Robotikexperte – Ihre Initialen

    - **Buchbare Ressource:** Generische Ressource

    - **Rolle:** Robotikexperte

10. Wählen Sie **Speichern und schließen** aus. 

11. Suchen Sie die Aufgabe **Design prüfen und genehmigen**, und wählen Sie das Feld **Ressourcen** aus. 

12. Wählen Sie im nächsten Menü die Option **Allison Dickson** aus. 


Glückwunsch! Sie haben ein Projekt in Dynamics 365 Project Operations verkauft und erstellt. Hier könne Projektmanager verschiedene Aspekte des Projekts verwalten und beispielsweise Ressourcen planen, den Projektzeitplan überwachen und Zeit und Kosten verwalten. 

 

 
