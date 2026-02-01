# Physik-Leistungskurs – Wiederholung aller Themen

Ein umfassendes LaTeX-Dokument zur Wiederholung aller relevanten Themen für den Physik-Leistungskurs in Baden-Württemberg (Abitur 2026).

## Inhalt

Das Dokument behandelt folgende Themengebiete:

- **Schwingungstheorie** – Harmonische Schwingungen, Pendel, Resonanz
- **Wellentheorie** – Wellenarten, Ausbreitung, Interferenz
- **Elektrizitätslehre** – Elektrische Felder, Kondensatoren, Stromkreise
- **Magnetismus** – Magnetfelder, Lorentzkraft, magnetische Induktion
- **Elektromagnetismus** – Maxwell-Gleichungen, elektromagnetische Wellen
- **Wellenoptik & Quantenmechanik** – Beugung, Interferenz, Photoeffekt, Dualismus

## Voraussetzungen

- LaTeX-Distribution (z.B. TeX Live, MiKTeX)
- Editor mit LaTeX-Unterstützung (z.B. VS Code mit LaTeX Workshop)

## Kompilierung

```bash
pdflatex main.tex
```

Für die Erstellung eines vollständigen Dokuments mit Inhaltsverzeichnis:

```bash
pdflatex main.tex
pdflatex main.tex
```

## Projektstruktur

```
.
├── main.tex          # Hauptdokument
├── main.pdf          # Kompiliertes PDF
├── figures/          # Abbildungen und Diagramme
└── subdocs/          # Kapitel-Dateien
    ├── preamble.tex
    ├── schwingungstheorie.tex
    ├── wellentheorie.tex
    ├── elektrizitaetslehre.tex
    ├── magnetismus.tex
    ├── elektromagnetismus.tex
    └── wellenoptik_und_quantenmechanik.tex
```

## Lizenz

Dieses Projekt ist für den persönlichen Gebrauch bestimmt.
