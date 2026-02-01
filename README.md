# Physik-Leistungskurs - Wiederholung aller Themen

Ein umfassendes LaTeX-Dokument zur Wiederholung aller relevanten Themen für den Physik-Leistungskurs in Baden-Württemberg (Abitur 2026). Es enthält detaillierte Herleitungen zentraler Größen und Formeln sowie Erklärungen wichtiger Phänomene und deren Zusammenhänge.

## Inhalt

- **Schwingungstheorie**: Harmonische Schwingungen, Pendel, Resonanz und Dämpfung.
- **Wellentheorie**: Wellenarten, Ausbreitung, Interferenz und Huygenssches Prinzip.
- **Elektrizitätslehre**: Elektrische Felder, Kondensatoren, Stromkreise und Energie.
- **Magnetismus**: Magnetfelder, Lorentzkraft, Fadenstrahlrohr und Hall-Effekt.
- **Elektromagnetismus**: Induktion, Maxwell-Gleichungen und elektromagnetische Wellen.
- **Wellenoptik & Quantenmechanik**: Beugung, Interferenz, Photoeffekt und Welle-Teilchen-Dualismus.

## Kompilierung

Für die Kompilierung wird eine LaTeX-Distribution (z.B. TeX Live, MiKTeX) benötigt.

1. LaTeX-Distribution installieren.
2. Repository klonen oder herunterladen.
3. Dokument kompilieren:
   ```bash
   pdflatex main.tex
   pdflatex main.tex
   ```
4. Die fertige PDF befindet sich unter `main.pdf`.

## Projektstruktur

```
.
├── main.tex              # Hauptdokument
├── main.pdf              # Kompiliertes PDF
├── figures/              # Abbildungen und Diagramme
└── subdocs/              # Kapitel-Dateien
    ├── preamble.tex
    ├── schwingungstheorie.tex
    ├── wellentheorie.tex
    ├── elektrizitaetslehre.tex
    ├── magnetismus.tex
    ├── elektromagnetismus.tex
    └── wellenoptik_und_quantenmechanik.tex
```
