---
lab:
  title: 'Lernpfad 5 – Lab 5.1: Erstellen von Arbeitsaufträgen in Dynamics 365 Field Service'
  learning path: Learn the Fundamentals of Dynamics 365 Field Service
  module: Explore Dynamics 365 Field Service
---

Modul 1: Informationen zu Dynamics 365 Field Service
========================

# Übungs-Lab 5.1: Erstellen von Arbeitsaufträgen in Dynamics 365 Field Service

## Lab-Einrichtung

**Hinweis für Kursleiter*innen:** *Damit dieses Lab wie für Lernende vorgesehen funktioniert, müssen Sie einige Konfigurationsschritte ausführen. Die Konfigurationsschritte finden Sie im Leitfaden zur Vorbereitung für Trainer für MB-910T00A. Die Demodaten für Field Service finden Sie hier: [https://github.com/MicrosoftLearning/MB-910T00A-Microsoft-Dynamics-365-Fundamentals-Customer-Engagement-Apps/tree/master/Instructions/Labs ]*

  - **Geschätzte Dauer**: 20 Minuten

## Anweisungen

1. Öffnen Sie die **Dynamics 365 Field Service**-Anwendung, falls noch nicht geschehen.

2. Wählen Sie **Anfragen** in der Navigation auf der linken Seite des Bildschirms aus.

3. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um einen neuen Anfragedatensatz zu erstellen.

4. Vervollständigen Sie den Anfragedatensatz wie folgt:

    - **Titel des Falls**: Überhitzung der Steuereinheit (Ihre Initialen)

    - **Kunde**: A. Datum Corporation

    - **Ursprung:** Telefon

5. Wählen Sie die Registerkarte **Außendienst** aus.

6. Legen Sie das Feld **Incidenttyp** auf **Überhitzung der Einheit** fest.

7. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Speichern und schließen** aus, um den Anfragedatensatz zu speichern und zu schließen.

Wir werden später zu Ihrem erstellten Anfragedatensatz zurückkehren. Zunächst werden wir uns ansehen, wie Sie einen Arbeitsauftrag manuell erstellen.

8. Wählen Sie links im Navigationsbereich die Option **Arbeitsaufträge** aus.

9. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **Neu** aus, um einen neuen Arbeitsauftrag zu erstellen.

10. Füllen Sie die Details des Arbeitsauftrags wie folgt aus:

    - **Dienstkonto:** Adventure Works

    - **Preisliste:** US-Fakturierungsraten

    - **Primärer Incidenttyp**: Leitung getrennt

11. Wählen Sie die Registerkarte **Einstellungen** aus.

12. Legen Sie im Feld **Servicegebiet** den Wert **WA** fest.

13. Konfigurieren Sie in den **Einstellungen** die folgenden Zeiteinstellungen:

    - **Zeit von zugesagt:** Morgen um 9:00 Uhr

    - **Zeit bis zugesagt:** Heute um 11:00 Uhr

14. Wählen Sie **Speichern und schließen** aus, um Ihre Änderungen zu speichern und den neuen Arbeitsauftrag zu schließen.

Sie können Arbeitsaufträge auch erstellen, indem Sie Anfragedatensätze eskalieren. In diesem Beispiel eskalieren wir den Fall „Überhitzung der Steuereinheit“, den wir zuvor erstellt haben.

15. Klicken Sie im linken Navigationsbereich auf **Anfragen**.

16. Öffnen Sie den Fall **Überhitzung der Steuereinheit** **(Ihre Initialen)** , den Sie zuvor erstellt haben.

17. Wählen Sie auf der **Befehlsleiste** die Schaltfläche **In Arbeitsauftrag konvertieren** aus.

18. Nachdem der Arbeitsauftrag erstellt wurde, klicken Sie im Popupbildschirm auf die Schaltfläche **OK**, um die Details des Arbeitsauftrags anzuzeigen.

19. Wählen Sie die Registerkarte **Services** aus, und vergewissern Sie sich, dass die Services **Systemintegrität überprüfen** und **Bewegungsspielraum überprüfen** zum Arbeitsauftrag hinzugefügt wurden.

**Hinweis**: Falls sie zunächst nicht angezeigt werden, drücken Sie die Taste F5, um Ihren Bildschirm zu aktualisieren.

20. Wählen Sie die Registerkarte **Serviceaufgabe** aus, und überprüfen Sie, ob der Task **Einheit überprüfen** hinzugefügt wurde.

Ihre neuen Arbeitsaufträge können jetzt geplant werden.

