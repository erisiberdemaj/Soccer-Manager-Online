# Fußball-Liga-Manager

**Autor:** Eris Iberdemaj
**Lehrveranstaltung:** STPRO Labor, FH Wirtschaftsinformatik
**Sprache:** Java (Konsolenprogramm)

## Beschreibung

Der Fußball-Liga-Manager ist ein Konsolenprogramm für eine kleine Liga mit 6 Teams.
Man trägt Spielergebnisse ein, das Programm vergibt automatisch die Punkte
(Sieg = 3, Unentschieden = 1, Niederlage = 0) und zeigt eine Tabelle an.
Die Tabelle ist nach Punkten und bei Gleichstand nach Tordifferenz sortiert.

Die Bedienung läuft über ein Textmenü. Die Eingaben werden mit `Scanner` eingelesen.

## Programmier-Regeln

Das Projekt verwendet nur **strukturierte Programmierung** in Java:

- nur einfache Klassen (oder `record`s)
- nur Arrays zum Speichern von Daten
- **keine** Vererbung, Interfaces oder abstrakten Klassen
- **keine** Collections (`ArrayList`, `List`, `Map` …)
- **keine** Streams und Lambdas
- das Sortieren der Tabelle ist selbst programmiert

## Projektstruktur

```
src/
  Team.java    – Klasse für ein Team (Name, Spiele, Tore, Punkte …)
  Main.java    – Hauptprogramm mit Menü (folgt)
readme.md      – diese Datei
features.md    – nummerierte Liste der Funktionen
agents.md      – Anweisungen für KI-Assistenten
```

## Starten

1. Projekt in IntelliJ IDEA öffnen.
2. `Main.java` ausführen.

Alternativ über die Konsole im Ordner `src`:

```
javac *.java
java Main
```
