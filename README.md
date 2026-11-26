# Timexjs

1. `zeiterfassung.html` in Microsoft Edge öffnen.
2. Einmal "Ordner verbinden" anklicken und genau diesen Ordner auswählen.
3. `Arbeitszeiterfassung.xlsx` ist die Masterdatei.

Timexjs verwendet eine feste, einfache Excel-Struktur ohne Excel-Tabellenobjekte und ohne dynamisches Einfügen/Löschen von Zeilen.
Ein Monatsblatt wird erst beim ersten Speichern echter Daten angelegt.

Vor jedem Speichern wird der bisherige Stand der Masterdatei automatisch als `Arbeitszeiterfassung.backup.xlsx` im selben Ordner gesichert. Ungespeicherte Änderungen lösen beim Verlassen der Seite eine Browser-Warnung aus.

## Feiertagsregion

- Schweiz alle Kantone
- Deutschland – Niedersachsen mit 10 gesetzlichen Feiertagen.
