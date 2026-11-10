# ChordPro Studio

_Version 1.6_

**Songbuch, Setlisten und Akkordwerkzeug für Gitarristen – eine Windows-Desktop-Anwendung (WPF, .NET 10).**

ChordPro Studio verwaltet Lieder im offenen [ChordPro-Format](https://www.chordpro.org), zeigt sie als
Liedblatt mit Akkorden über dem Text an, hilft beim Üben und erstellt druckfertige PDFs für Auftritte.
Es ist ein privates, nicht-kommerzielles Projekt für den eigenen Gebrauch.

## Funktionen

- **Songbuch:** Alle ChordPro-Dateien eines Ordners durchsuchen, sortieren, anzeigen und bearbeiten –
  wahlweise als ChordPro-Quelltext oder als Liedblatt mit farbigen Akkorden über dem Text.
- **Transponieren** in Halbtonschritten, auf Wunsch dauerhaft in die Datei übernommen.
- **ChordPro-Editor** mit Tag-Kontextmenü (Songstruktur, Direktiven, Tab-Vorlagen, eigene Tags).
- **Setlisten** zusammenstellen, sortieren und je Lied transponieren.
- **PDF-Export und Druckvorschau** – einzelne Lieder oder ganze Setlisten, mit Inhaltsverzeichnis,
  ein- oder zweispaltig, mit Griffbildern.
- **Akkorddiagramme** für Gitarre und Klavier sowie ein **Akkordfinder** mit allen spielbaren Griffen eines Akkords
  (Grundstellung, Umkehrungen, Powerchords, Jazz-/Shell-Voicings). Im Songbuch und im PDF wahlweise Gitarre, Klavier oder beides.
- **Songinfos online:** Tonart, Takt, Tempo (BPM) und Laufzeit zum Lied nachschlagen und nach Bestätigung
  als ChordPro-Tags übernehmen.
- **Import aus Text:** Akkord-über-Text (z. B. eingefügter Liedtext mit Akkorden) wird in ChordPro umgewandelt.
- **Teleprompter:** Vollbild mit großer Schrift und Autoscroll für den Auftritt, per Tastatur steuerbar.
- **Medienfenster** (andockbar, frei verschiebbar, skalierbar): Titel aus der eigenen MediaMonkey-Bibliothek
  anspielen sowie YouTube-Videos und Gitarren-Lessons zum Lied eingebettet ansehen.
- **Autoscroll** passend zur Laufzeit des Liedes oder synchron zur Wiedergabe.
- **Darstellung** hell, dunkel oder wie Windows (Fluent-Design); Akzent-, Akkord-, Papier- und Textfarbe, Liedschrift und Schriftgröße sind anpassbar.
- **Alle Fenster andockbar** (Songbuch, Setlisten, Akkordfinder, Creator, Medien); die Anordnung wird gespeichert.
- **Android-Version:** Setlisten lassen sich im gemeinsamen JSON-Format mit der Android-Version austauschen.

## Datenquellen und Dank

Die Song-Informationen stammen aus folgenden Quellen:

- **Tonart, Takt und Tempo (BPM):** [GetSongBPM](https://getsongbpm.com) – vielen Dank für die kostenlose API!
  Auch im Programm verlinkt der Songinfos-Dialog auf [getsongbpm.com](https://getsongbpm.com).
- **Laufzeit:** [Deezer API](https://developers.deezer.com)
- **Eigene Musikbibliothek:** lokale MediaMonkey-Datenbank (nur lesend)

### Credits (English)

Song key, time signature and tempo data are provided by **[GetSongBPM](https://getsongbpm.com)**.
ChordPro Studio is a private, non-commercial Windows songbook application; the song-info dialog
inside the app links back to [getsongbpm.com](https://getsongbpm.com) as well.

## Verwendete Bibliotheken

- [PDFsharp](https://www.pdfsharp.com) – PDF-Erzeugung
- [AvalonDock](https://github.com/Dirkster99/AvalonDock) – andockbare Fenster
- [Microsoft Edge WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) – eingebettete Videos
- [Microsoft.Data.Sqlite](https://learn.microsoft.com/dotnet/standard/data/sqlite/) – MediaMonkey-Datenbank

## Status

Der Quellcode wird derzeit privat entwickelt. Diese Seite beschreibt das Projekt und nennt die genutzten
Datenquellen.
