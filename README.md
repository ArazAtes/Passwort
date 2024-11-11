# Passwort Generator - README

## Projektbeschreibung

Dieses Projekt ist eine einfache, webbasierte Anwendung zum Generieren sicherer Passwörter. Benutzer können die Länge des Passworts sowie enthaltene Zeichentypen (Großbuchstaben, Zahlen und Sonderzeichen) auswählen. Ein Klick auf den "Passwort generieren"-Button erzeugt ein Passwort, das im Bereich unterhalb der Schaltfläche angezeigt wird.

## Funktionen

- **Passwortlänge**: Benutzer können die Länge des Passworts zwischen 6 und 30 Zeichen einstellen.
- **Zeichenoptionen**:
  - Großbuchstaben (A-Z)
  - Zahlen (0-9)
  - Sonderzeichen (!@#$%^&*() u. a.)
- **Passwortanzeige**: Das generierte Passwort wird fett gedruckt unterhalb des Buttons angezeigt.

## Installation

1. **Voraussetzungen**: Ein moderner Webbrowser (Chrome, Firefox, Edge oder Safari).
2. **Datei öffnen**: Speichern Sie den Code als `passwort_generator.html` und öffnen Sie die Datei im Webbrowser.

## Verwendung

1. **Passwortlänge auswählen**: Geben Sie im Eingabefeld die gewünschte Passwortlänge (6-30 Zeichen) ein.
2. **Zeichentypen auswählen**: Aktivieren oder deaktivieren Sie die Kontrollkästchen für Großbuchstaben, Zahlen und Sonderzeichen je nach Wunsch.
3. **Passwort generieren**: Klicken Sie auf den Button "Passwort generieren".
4. **Ergebnis anzeigen**: Das generierte Passwort wird sofort unter dem Button angezeigt.

## Codeübersicht

### HTML-Struktur
- Enthält die grundlegenden Eingabeelemente und den Bereich zur Passwortanzeige.
- Die `<label>`- und `<input>`-Elemente ermöglichen die Anpassung der Passwortoptionen.

### CSS-Styling
- Ein zentrales, einfaches Design für Benutzerfreundlichkeit und Lesbarkeit.
- Stile für das Layout, Schaltflächen und den Passwort-Anzeigebereich.

### JavaScript-Funktionalität
- Die `generatePassword()`-Funktion wird durch den Button-Klick ausgelöst:
  - Liest die gewählten Passwortoptionen aus.
  - Baut einen Zeichensatz auf, basierend auf den Benutzerwünschen.
  - Generiert ein Passwort, indem zufällige Zeichen aus dem Zeichensatz ausgewählt werden.
  - Zeigt das generierte Passwort im Browser an.

## Anpassungen

- Sie können die Zeichensätze in der JavaScript-Funktion (`lowercaseChars`, `uppercaseChars`, `numberChars`, `symbolChars`) nach Belieben anpassen.
- Die Standardlänge und Stiloptionen lassen sich in den entsprechenden HTML- und CSS-Bereichen verändern.

## Lizenz

Dieses Projekt ist frei nutzbar und kann beliebig angepasst und erweitert werden.
