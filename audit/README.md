# Audit-Verzeichnis

Dieses Verzeichnis dokumentiert Halluzinations-Audits ueber alle Aktenzeichen
in den SKILL.md-Dateien des Repos.

## Wellen

| Welle | Datum | Umfang | Status |
|---|---|---|---|
| 1 — Stichprobe v14.2.4 | 27.05.2026 | 25 Skills aus User-Report | abgeschlossen, in v14.2.4 gefixt |
| 2 — Vollaudit | 27.05.2026 | 3228 unique AZ, 22 parallele Subagenten | abgeschlossen, Befunde in `audit_problems_2026-05-27.json` |
| 3 — Reparatur (AZ-Strip) | 29.05.2026 | 969 problematische AZ aus 88 Skills entfernt | abgeschlossen, in v24.1.0 |
| 4 — References-Konsistenz | 29.05.2026 | 17 tote Verweise, 83 verwaiste Files | abgeschlossen, Befunde in `references_audit_2026-05-29.json` |

## Welle 2 — Methodik

22 parallele Subagenten haben je ~147 unique Aktenzeichen geprueft. Pro AZ:

1. `pplx search web "<court> <az>"` gegen dejure.org / openJur / bundesgerichtshof.de / curia.europa.eu
2. Vergleich des im Skill behaupteten Themas mit der echten Entscheidung
3. Klassifikation:
   - **OK**: AZ existiert und Kontext passt
   - **WRONG_TOPIC**: AZ existiert, aber Kontext beschreibt anderen Sachverhalt
   - **NOT_FOUND**: AZ findet sich nicht
   - **UNVERIFIABLE**: Quellenlage zu duenn

## Ergebnis Welle 2

- **3228** unique Aktenzeichen geprueft
- **1062** OK (32,9 %)
- **893** UNVERIFIABLE (27,7 %) — meist OLG/LG/FG ohne oeffentlichen Volltext
- **621** WRONG_TOPIC (19,2 %)
- **355** NOT_FOUND (11,0 %)
- **976 Problemfaelle** (30,2 %) sind in `audit_problems_2026-05-27.json`
  detailliert aufgelistet

## Hinweis zur Datenqualitaet

Der hohe WRONG_TOPIC-Anteil zeigt: das Aktenzeichen existiert, aber
die im Skill behauptete Aussage trifft nicht auf das tatsaechliche Urteil zu.
Typische Muster sind falsche Senate (z.B. IX ZR statt VIII ZR), falsche
Jahrgaenge oder voellig andere Themen unter identischem AZ.

Diese Faelle muessen in einer Folge-Welle (Welle 3 — Reparatur) systematisch
bereinigt werden: betroffene Skill-Stellen entweder ersatzlos streichen
oder durch verifizierte AZ ersetzen.

Die UNVERIFIABLE-Faelle sind nicht zwangslaeufig fehlerhaft; sie konnten
nur ohne juris-/Beck-Zugang nicht abschliessend gegengeprueft werden.

## Folgeschritte

1. Welle 3 — Reparatur: 976 Problemfaelle systematisch fixen – erledigt in v24.1.0 (Strip ueber `strip_az.py`)
2. Optional: 893 UNVERIFIABLE mit juris/Beck-Zugang nachpruefen
3. CI-Hook etablieren, der neue AZ-Aufnahmen gegen dejure-API gegenprueft

## Welle 3 — AZ-Strip (29.05.2026)

Alle 969 als WRONG_TOPIC oder NOT_FOUND klassifizierten Aktenzeichen wurden
aus den betroffenen SKILL.md entfernt. Strategie:

- Pro Audit-Eintrag wurde die AZ-Zeichenkette in der jeweils betroffenen
  SKILL.md gesucht und die enthaltende Markdown-Zeile/Bulletpoint geloescht.
- YAML-Frontmatter wurde nicht angetastet (Schutz gegen Header-Beschaedigung).
- Konsekutive Leerzeilen wurden kollabiert.
- Ergebnis: 175 Dateien geaendert, 392 Zeilen entfernt.
- Validatoren (`validate-plugin-structure`, `validate-yaml-frontmatter`,
  `welle5_komma_check`) anschliessend gruen.

## Welle 4 — References-Audit (29.05.2026)

Pruefung der Markdown-Verweise auf `references/`-Dateien:

- 115 References-Dateien gesamt
- 29 davon werden mindestens einmal verlinkt
- 83 sind nicht verlinkt (werden aber durch Skill-Engine via Glob geladen,
  also nicht zwingend tot)
- 17 tote Verweise: SKILL.md/README.md referenzieren Dateien, die nicht
  existieren. Beispiel: `rechtsberatungsstelle/.../SKILL.md` verwies auf
  `references/pruef-warteschlange.yaml`, faktisch heisst die Datei aber
  `review-queue.yaml` (in dieser Welle gefixt).

Vollstaendige Liste in `references_audit_2026-05-29.json`. Die restlichen
16 toten Verweise sind in der naechsten Welle einzeln zu adressieren
(entweder Datei anlegen oder Verweis aus dem Skill entfernen).
