# Digitaler Klausurplaner für Eltern

Projektarbeit im Modul **Digitale Business-Modelle (DSBBWLPDBM01)** an der
**IU Internationalen Hochschule**.

## Kurzbeschreibung

Dieses Repository dokumentiert die Entwicklung und Validierung eines digitalen
Geschäftsmodells für einen **Digitalen Klausurplaner für Eltern**. Ziel ist es,
Eltern bei der Prüfungs- und Lernorganisation ihrer Kinder zu entlasten, indem
Klausurtermine, Lernumfänge und Überschneidungen zentral und übersichtlich
zusammengeführt werden.

Die Arbeit folgt dem Phasenmodell des Moduls (Problemdefinition, Empirie,
Marktanalyse, Customer Evidence, Business Model Canvas) und sammelt alle
Deliverables als Markdown-Dateien in diesem Repository. Der finale Projektbericht
wird daraus als PDF (7–10 Seiten Hauptteil, APA-Stil) für myCampus exportiert.

## Zielgruppe

**Eltern mit schulpflichtigen Kindern (insb. weiterführende Schulen).**

## Rahmendaten & Sonderregelungen

- **Arbeitsform:** Einzelarbeit (Sonderregelung vom Dozenten genehmigt).
- **Empirische Methode:** anonymer Online-Umfragebogen für Eltern
  (Sonderregelung: **Umfrage statt qualitativer Interviews**).
- **Dokumentations-Stack:** Kiro CLI/IDE + GitHub Markdown Repository + finaler
  PDF-Export für myCampus.

## Repository-Struktur

```text
iu-dsbbwlpdbm01-klausurplaner/
├── README.md                 # Projekt-Hauptübersicht & Status (diese Datei)
├── PROJECT_CONTEXT.md         # Autoritativer Kontext-Prompt für Kiro / LLMs
├── AI_USAGE_LOG.md            # Transparente KI-Dokumentation (IU-Pflicht)
├── docs/
│   ├── 01_problem_brief.md      # Deliverable 1: Problemstellung & Kontext
│   ├── 02_umfragebogen.md       # Fragenkatalog & Befragungskonzept
│   ├── 03_customer_evidence.md  # Auswertung der Umfrageergebnisse
│   ├── 04_market_landscape.md   # Wettbewerbsanalyse (Untis, SchoolFox etc.)
│   └── 05_bmc_v1.md             # Business Model Canvas v1.0
├── data/
│   └── survey_responses.csv     # Anonymisierte Rohdaten der Befragung
└── report/
    └── projektbericht.md        # Entwurf finaler Projektbericht (7–10 S.)
```

## Deliverables im Überblick

| Datei | Inhalt |
| --- | --- |
| [`PROJECT_CONTEXT.md`](PROJECT_CONTEXT.md) | Autoritativer Projektkontext, Problem Statement und Terminologie |
| [`AI_USAGE_LOG.md`](AI_USAGE_LOG.md) | Transparente Dokumentation des KI-Einsatzes (IU-Pflicht) |
| [`docs/01_problem_brief.md`](docs/01_problem_brief.md) | Problemstellung & Nutzungskontext (Phase I) |
| [`docs/02_umfragebogen.md`](docs/02_umfragebogen.md) | Fragenkatalog & Befragungskonzept (Phase II) |
| [`docs/03_customer_evidence.md`](docs/03_customer_evidence.md) | Auswertung der Umfrageergebnisse (Platzhalter bis Datenerhebung) |
| [`docs/04_market_landscape.md`](docs/04_market_landscape.md) | Wettbewerbs- und Marktanalyse (Phase III) |
| [`docs/05_bmc_v1.md`](docs/05_bmc_v1.md) | Business Model Canvas v1.0 (Phase V) |

## Aktueller Status

- **Phase:** Phase I (Problemdefinition) abgeschlossen; Repository-Grundgerüst
  aufgesetzt.
- **Nächste Schritte:** Durchführung der Online-Umfrage, Erhebung der
  Primärdaten (`data/survey_responses.csv`) und Auswertung in
  `docs/03_customer_evidence.md`.
- **Hinweis:** Die Dateien `docs/03_customer_evidence.md`,
  `docs/04_market_landscape.md` und `docs/05_bmc_v1.md` enthalten vor der
  Datenerhebung noch Platzhalter bzw. als Hypothese gekennzeichnete Annahmen.

## Hinweise zu Daten und Datenschutz

Dieses Repository ist öffentlich. Es enthält **keine echten personenbezogenen
Daten (PII)**. Alle Beispiele und Vorlagen verwenden ausschließlich generische
Platzhalter. Die Umfrage wird anonym erhoben.
