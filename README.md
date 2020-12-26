# Rezeptsammlung

Ich sammel hier Rezepte die ich mag - der Inhalt ist daher _Geschmackssache_ ;D

Sinn und Zweck vom Repository ist den Quelltext für alle jene bereitzustellen, die mit LaTeX ihre Rezepte organisieren wollen.

Es geht **nicht** um den Austausch von Rezepten, dafür gibt es genug Möglichkeiten.

Wer einfach nur meine PDF herunterladen möchte, bitteschön: https://github.com/sennewood/rezeptsammlung/releases


## Generierung der PDF

- Alle Rezepte liegen in **content/[kategorie]/** und sind in der **rezeptesammlung.tex** verlinkt.
- Nach einer Änderung einfach immer die **create.bat** ausführen um eine aktualisierte PDF zu erhalten.


## Setup

### LaTeX für Windows

1. Installiert euch MiKTeX: https://miktex.org/howto/install-miktex
1. Öffnet die Eingabeaufforderung (cmd) und testet die Installation: ```pdflatex -version```
1. Passt die Pfade in der **create.bat** entsprechend eurem System an.

### Erstellen der benötigten Dateien

1. Erstellt euch einen Ordner (z. B. "content") in dem ihr eure Rezepte speichert.
1. Kopiert die **dist/titlepage.tex** nach **./titlepage.tex** und passt sie auf euch an.
1. Kopiert die **dist/impressum.tex** nach **./impressum.tex** und passt sie auf euch an.
1. Kopiert die **dist/rezeptsammlung.tex** nach **./rezeptsammlung.tex** und passt sie auf euch an.

### Kopieren der Rezepte (optional)

In **dist/content/** liegen meine Rezepte. Die Rezepte die ihr daraus übernehmen wollt, kopiert ihr einfach in den von euch erstellen Ordner für Rezepte (z. B. "content").
