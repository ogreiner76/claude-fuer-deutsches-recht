---
name: dokumenten-inventur-grob
description: "Erzeugt eine erste grobe Liste aller vorhandenen Dateien mit Dateiname, Dateityp, Dateigroesse und sichtbarem Datum. Noch keine inhaltliche Pruefung — reine Bestandsaufnahme als Ausgangspunkt fuer die feinere Einordnung."
---

# Dokumenten-Inventur grob

> **Hinweis Dokumentenverarbeitung:** Dieser Skill ist Teil des Plugins `status-navigator-step-plan` und arbeitet bewusst ohne Normen- und Rechtsprechungs-Anker. Es handelt sich um reine Dokumentenverarbeitung und Workflow-Strukturierung im Sinne des Prompt des Monats von Tom Braegelmann (Status-Navigator und Step-Plan-Macher). Die rechtliche Pruefung des Materials bleibt anwaltliche Aufgabe und wird ausdruecklich von diesem Skill nicht vorgenommen.

## Rolle und Fokus
Erste Vollerfassung der Dateinamen

## Vorgehen
Verzeichnis durchgehen, Dateiliste erzeugen, erste Dubletten erkennen

1. **Rolle und Ziel klaeren** — Wer fragt, welche Rolle, welches Ziel des Mandats?
2. **Material sichten** — Welche Dokumente liegen vor, welche fehlen?
3. **Strukturieren** — In die passende Reiterstruktur einsortieren.
4. **Status notieren** — Verfuegbarkeit, Unterschriftsstatus, Zustellung, Diskrepanz.
5. **Naechsten Schritt formulieren** — Wer beschafft was bis wann?

## Anwendungsbeispiel
Ordner mit 120 Dateien wird systematisch erfasst, doppelte Versionen werden markiert.

## Output-Module
- Strukturierte Eintraege fuer die Excel-Arbeitsmappe (Reiter 1 bis 4 plus optionale Reiter).
- Klartextliche Hinweise bei Diskrepanzen, fehlenden Unterschriften und unklaren Zustellungen.
- Vorschlag fuer den naechsten Schritt im Workflow-Reiter.

## Grenzen
- **Keine rechtliche Bewertung.** Wirksamkeitspruefung von Erklaerungen und Vertraegen bleibt anwaltliche Aufgabe.
- **Keine Vollstaendigkeitsgarantie.** Die KI kann Dokumente oder Zusammenhaenge uebersehen. Jede Tabelle ist anhand der Originaldokumente zu verifizieren.
- **Diskrepanz-Hinweise sind Hinweise, keine Befunde.** Sie muessen anwaltlich verifiziert werden.
- **Datenschutz und Berufsrecht.** Nutzung nur mit System, das DSGVO, § 203 StGB und §§ 43a, 43e BRAO erfuellt. Erstpruefung mit anonymisierten Testdaten.

## Plugin-Kontext
Dieser Skill arbeitet im Verbund mit den uebrigen Skills des Plugins `status-navigator-step-plan`. Reiterstruktur und Standardspalten sind im Plugin-README dokumentiert. Workflow-Reiter dient als zentrales Steuerungsinstrument des Mandats.
