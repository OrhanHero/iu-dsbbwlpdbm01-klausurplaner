# PROJECT_CONTEXT.md – Digitale Business-Modelle (DSBBWLPDBM01)

> Diese Datei ist der autoritative Kontext-Prompt für Kiro / LLMs und die
> Referenzquelle für Terminologie, Zielgruppe und das wörtliche Problem
> Statement. Alle anderen Dateien im Repository müssen hierzu konsistent sein.

## 1. Rahmendaten & Sonderregelungen

- Modul: Digitale Business-Modelle (DSBBWLPDBM01) – IU Internationale Hochschule
- Projekt-Repository: https://github.com/OrhanHero/iu-dsbbwlpdbm01-klausurplaner.git
- Arbeitsform: Einzelarbeit (Sonderregelung vom Dozenten genehmigt)
- Empirische Methode: Online-Umfragebogen für Eltern (Sonderregelung: Umfrage statt qualitativer Interviews)
- Dokumentations-Stack: Kiro CLI/IDE + GitHub Markdown Repository + Finaler PDF-Export für myCampus (7–10 Seiten Hauptteil, APA-Stil)

## 2. Problemstellung & Target Audience

- Thema: Digitaler Klausurplaner für Eltern
- Zielgruppe: Eltern mit schulpflichtigen Kindern (insb. weiterführende Schulen)
- Problem Statement (Phase I): "Eltern von Schulkinder:innen haben im Schulalltag während der Prüfungsphasen das Problem, den Überblick über bevorstehende Klausurtermine, Lernumfänge und Überschneidungen ihrer Kinder zu verlieren, weil Klausurpläne dezentral über Zettel, unterschiedliche Schul-Apps (Untis, SchoolFox etc.) oder mündliche Informationen kommuniziert werden. Bisher wird dieses Problem durch manuelles Übertragen in den Familienkalender, Nachfragen bei den Kindern oder Eltern-Chatgruppen gelöst. Dabei besteht insbesondere das Defizit, dass Termine kurzfristig übersehen werden, Vorbereitungszeiten fehlen und hoher organisatorischer Stress im Familienalltag entsteht."

## 3. Markt- & Wettbewerbslandschaft (Phase III)

- Direkte B2B Schul-Apps: WebUntis, SchoolFox, Sdui, Schulmanager Online. Defizit: Schulzentriert; Eltern-Ansichten oft passiv/eingeschränkt; Klausur-Module lizenzabhängig von Schulen oft gar nicht freigeschaltet.
- Indirekte B2C Familien-Apps: TimeTree, Google/Apple Familienkalender. Defizit: Generisch; hoher manueller Übertragungsaufwand; keine schul- oder lernspezifischen Funktionen.
- Substitute: Analoge Wandkalender, Hausaufgabenhefte, WhatsApp-Elterngruppen, Kühlschranknotizen.

## 4. Methodik & Empirie (Phase II & Customer Evidence)

- Erhebung mittels anonymem Online-Umfragebogen (Ziel: 20–40 Antworten von Eltern).
- 5-Abschnitte-Struktur: 1. Screening & Demografie 2. Ist-Zustand & Informationskanäle 3. Schmerzpunkte & Belastung (Likert-Skalen 1–5 & qualitative O-Töne) 4. Bisherige Ausweichlösungen & Defizite 5. Lösungsbedarf (Problem-Solution-Fit)
- Speicherung der Rohdaten unter data/survey_responses.csv und Auswertung in docs/03_customer_evidence.md.

## 5. Meilensteine & Repository-Struktur

```text
iu-dsbbwlpdbm01-klausurplaner/
├── README.md                 # Projekt-Hauptübersicht & Status
├── PROJECT_CONTEXT.md         # Dieser Kontext-Prompt für Kiro / LLMs
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
