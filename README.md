# PSA Verdopplungszeitrechner - Dokumentation 


![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## Überblick

Der PSA Verdopplungszeitrechner ist ein Tool zur Berechnung und Visualisierung von PSA-Werten und deren Verdopplungszeiten.
Funktionen

## 1. Patientendaten

    Eingabe von Vor- und Nachname
    Erfassung von Geburtsdatum
    Dokumentation des OP-Datums
    Daten erscheinen als Überschrift im Diagramm

## 2. PSA-Messungen

    Eingabe von zwei PSA-Messungen mit Datum
    Möglichkeit für Notizen zu jeder Messung
    Automatische Berechnung der Verdopplungszeit
    Werte werden in der Tabelle gespeichert

## 3. Visualisierung

    Grafische Darstellung der PSA-Werte
    Anzeige der Verdopplungszeiten
    Interaktive Tooltips mit allen Informationen
    Übersichtliche Darstellung des Verlaufs

## 4. Datenverwaltung

    Speichern der Daten als JSON-Datei
    Laden gespeicherter Daten
    Bearbeitung der Werte in der Tabelle
    Löschen einzelner Messungen

## 5. Benutzeroberfläche

    Dark Mode für bessere Lesbarkeit
    Übersichtliche Gruppierung der Eingabefelder
    Responsive Design
    Klare Farbkodierung

# Bedienung

## 1. Neue Messung hinzufügen:

    Patientendaten eingeben (optional)
    Datum und PSA-Wert der ersten Messung eingeben
    Datum und PSA-Wert der zweiten Messung eingeben
    Optional Notizen zu den Messungen hinzufügen
    "Berechnen" klicken

## 2. Daten verwalten:

    "Speichern" zum Exportieren der Daten
    "Laden" zum Importieren gespeicherter Daten
    Werte in der Tabelle können direkt bearbeitet werden
    Messungen können über das X-Symbol gelöscht werden

## 3. Visualisierung:

    Graph zeigt PSA-Verlauf und Verdopplungszeiten
    Mit der Maus über Datenpunkte fahren für Details
    Dark Mode über den Schalter rechts oben umschaltbar

# Berechnungsmethode

## Die Verdopplungszeit wird nach folgender Formel berechnet:

    Zeitdifferenz in Monaten zwischen den Messungen
    Wachstumsrate = ln(PSA2/PSA1) / Zeitdifferenz
    Verdopplungszeit = ln(2) / Wachstumsrate

## Technische Hinweise

    Die Daten werden im JSON-Format gespeichert
    Die JSON-Datei kann auch extern bearbeitet werden
    Alle Berechnungen erfolgen clientseitig
    Keine Daten werden an Server übermittelt

## 📝 Lizenz
Dieses Projekt ist offen für alle. Fühle dich frei, es zu kopieren, zu verändern und zu nutzen.
