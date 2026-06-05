# Tierschutzrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`tierschutzrecht`) | [`tierschutzrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/tierschutzrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Tierschutzakte Pferdehof Auenwiese** (`tierschutzrecht-veterinaeramt-pferdehof-auenwiese`) | [Gesamt-PDF lesen](../testakten/tierschutzrecht-veterinaeramt-pferdehof-auenwiese/gesamt-pdf/tierschutzrecht-veterinaeramt-pferdehof-auenwiese_gesamt.pdf) | [`testakte-tierschutzrecht-veterinaeramt-pferdehof-auenwiese.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-tierschutzrecht-veterinaeramt-pferdehof-auenwiese.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin nimmt Tiere rechtlich ernst: § 90a BGB als Ausgangspunkt, TierSchG als öffentlich-rechtliches und strafrechtliches Schutzregime, dazu Zivilrecht, Behördenaufsicht, Veterinäramt und Vollzug.

## Start

Beginne mit `allgemein`. Das Plugin fragt zuerst nach Rolle, Ziel, Frist, Behörde/Gericht/Register, vorhandenen Unterlagen und gewünschtem Output. Danach schlägt es die passenden Spezialskills aus diesem Plugin vor.

## Arbeitsweise

- Es arbeitet mit Akten- und Fristenlogik statt mit Bauchgefühl.
- Es trennt Rechtsgrundlage, Verfahren, Beweis, Kosten, Kommunikation und Eskalation.
- Es soll Nutzerinnen und Nutzer befähigen: verständliche Erklärung, präzise Rückfragen, dann belastbarer Entwurf.
- Rechtsprechung und Gesetzesstände werden nicht halluziniert, sondern als Live-Check über amtliche oder frei zugängliche Quellen markiert.

## Typische Outputs

- Kaltstart-Interview und Aktenlandkarte
- Behörden-, Gerichts- oder Gegneranschreiben
- Widerspruchs-/Klage-/Eilantragsbausteine
- Kosten-, Fristen- und Zuständigkeitsmatrix
- Dashboard/Tracker für laufende Vorgänge
- Kurzfassung für Mandant, Vorstand, Verband, Redaktion oder Bürgerin

## Quellenhygiene

Siehe [`references/QUELLEN.md`](./references/QUELLEN.md). Dieses Plugin gibt keine endgültige Rechtsberatung, sondern robuste Arbeitsfassungen, Prüfpfade und Dokumentationshilfen.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Tierschutzrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |
| `tier-001-kaltstart-tierschutzfall` | Tierschutzrecht: Kaltstart Tierschutzfall. Kaltstart Tierschutzfall im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `tier-eilrechtsschutz-tierhalter` | Nutze dies bei Tier 009 Eilrechtsschutz Gegen Haltungsverbot, Tier 010 Tierhalter Zivilrechtlich Beraten, Tier 011 Tierarzt Und Behandlungsfehler, Tier 012 Fundtier Und Eigentum: führt durch diese fachlich verbundenen Module, wählt den p... |
| `tier-gefaehrlicher-hund-zucht-qualzucht` | Nutze dies bei Tier 013 Gefaehrlicher Hund Landesrecht, Tier 015 Zucht Und Qualzucht, Tier 016 Tiertransport Prüfen, Tier 017 Tierversuch Genehmigung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefer... |
| `tier-gefluegelmast-bussgeld-tiertransport` | Nutze dies bei Tier 076 Gefluegelmast Bussgeld Verteidigen, Tier 086 Tiertransport Bussgeld Verteidigen, Tier 096 Schlachthof Bussgeld Verteidigen, Tier 002 90a Bgb Richtig Einordnen: führt durch diese fachlich verbundenen Module, wählt... |
| `tier-gefluegelmast-schutzbedarf` | Nutze dies bei Tier 071 Gefluegelmast Schutzbedarf Prüfen, Tier 072 Gefluegelmast Behoerdenantrag Schreibe, Tier 073 Gefluegelmast Anordnung Angreifen, Tier 074 Gefluegelmast Beweise Sichern: führt durch diese fachlich verbundenen Module... |
| `tier-gefluegelmast-strafrisiko-kosten-klaeren` | Nutze dies bei Tier 075 Gefluegelmast Strafrisiko Bewerten, Tier 077 Gefluegelmast Kosten Klaeren, Tier 078 Gefluegelmast Halterpflichten Erklaere, Tier 079 Gefluegelmast Eilantrag Bauen: führt durch diese fachlich verbundenen Module, wä... |
| `tier-gefluegelmast-suchen-tiertransport` | Nutze dies bei Tier 080 Gefluegelmast Vergleich Suchen, Tier 081 Tiertransport Schutzbedarf Prüfen, Tier 082 Tiertransport Behoerdenantrag Schreibe, Tier 083 Tiertransport Anordnung Angreifen: führt durch diese fachlich verbundenen Modul... |
| `tier-hundehaltung-behoerdenantrag-anordnung` | Nutze dies bei Tier 022 Hundehaltung Behoerdenantrag Schreiben, Tier 023 Hundehaltung Anordnung Angreifen, Tier 024 Hundehaltung Beweise Sichern, Tier 025 Hundehaltung Strafrisiko Bewerten: führt durch diese fachlich verbundenen Module,... |
| `tier-hundehaltung-kosten-halterpflichten` | Nutze dies bei Tier 027 Hundehaltung Kosten Klaeren, Tier 028 Hundehaltung Halterpflichten Erklaeren, Tier 029 Hundehaltung Eilantrag Bauen, Tier 030 Hundehaltung Vergleich Suchen: führt durch diese fachlich verbundenen Module, wählt den... |
| `tier-katzenkolonie-bussgeld-pferdestall` | Nutze dies bei Tier 036 Katzenkolonie Bussgeld Verteidigen, Tier 046 Pferdestall Bussgeld Verteidigen, Tier 056 Rinderbetrieb Bussgeld Verteidigen, Tier 066 Schweinehaltung Bussgeld Verteidigen: führt durch diese fachlich verbundenen Mod... |
| `tier-katzenkolonie-schutzbedarf` | Nutze dies bei Tier 031 Katzenkolonie Schutzbedarf Prüfen, Tier 032 Katzenkolonie Behoerdenantrag Schreibe, Tier 033 Katzenkolonie Anordnung Angreifen, Tier 034 Katzenkolonie Beweise Sichern: führt durch diese fachlich verbundenen Module... |
| `tier-katzenkolonie-strafrisiko-kosten-klaeren` | Nutze dies bei Tier 035 Katzenkolonie Strafrisiko Bewerten, Tier 037 Katzenkolonie Kosten Klaeren, Tier 038 Katzenkolonie Halterpflichten Erklaere, Tier 039 Katzenkolonie Eilantrag Bauen: führt durch diese fachlich verbundenen Module, wä... |
| `tier-katzenkolonie-suchen-pferdestall` | Nutze dies bei Tier 040 Katzenkolonie Vergleich Suchen, Tier 041 Pferdestall Schutzbedarf Prüfen, Tier 042 Pferdestall Behoerdenantrag Schreiben, Tier 043 Pferdestall Anordnung Angreifen: führt durch diese fachlich verbundenen Module, wä... |
| `tier-nutztierhaltung-kontrolle` | Nutze dies bei Tier 018 Nutztierhaltung Kontrolle, Tier 019 Tierschutzverein Handlungsoptionen, Tier 020 Beweisfotos Und Datenschutz, Tier 021 Hundehaltung Schutzbedarf Prüfen: führt durch diese fachlich verbundenen Module, wählt den pas... |
| `tier-pferdestall-beweise-strafrisiko-bewerten` | Nutze dies bei Tier 044 Pferdestall Beweise Sichern, Tier 045 Pferdestall Strafrisiko Bewerten, Tier 047 Pferdestall Kosten Klaeren, Tier 048 Pferdestall Halterpflichten Erklaeren: führt durch diese fachlich verbundenen Module, wählt den... |
| `tier-pferdestall-eilantrag-suchen` | Nutze dies bei Tier 049 Pferdestall Eilantrag Bauen, Tier 050 Pferdestall Vergleich Suchen, Tier 051 Rinderbetrieb Schutzbedarf Prüfen, Tier 052 Rinderbetrieb Behoerdenantrag Schreibe: führt durch diese fachlich verbundenen Module, wählt... |
| `tier-rinderbetrieb-anordnung-beweise-sichern` | Nutze dies bei Tier 053 Rinderbetrieb Anordnung Angreifen, Tier 054 Rinderbetrieb Beweise Sichern, Tier 055 Rinderbetrieb Strafrisiko Bewerten, Tier 057 Rinderbetrieb Kosten Klaeren: führt durch diese fachlich verbundenen Module, wählt d... |
| `tier-rinderbetrieb-halterpflichten-eilantrag` | Nutze dies bei Tier 058 Rinderbetrieb Halterpflichten Erklaere, Tier 059 Rinderbetrieb Eilantrag Bauen, Tier 060 Rinderbetrieb Vergleich Suchen, Tier 061 Schweinehaltung Schutzbedarf Prüfen: führt durch diese fachlich verbundenen Module,... |
| `tier-schlachthof-anordnung-beweise-sichern` | Nutze dies bei Tier 093 Schlachthof Anordnung Angreifen, Tier 094 Schlachthof Beweise Sichern, Tier 095 Schlachthof Strafrisiko Bewerten, Tier 097 Schlachthof Kosten Klaeren: führt durch diese fachlich verbundenen Module, wählt den passe... |
| `tier-schlachthof-tier-schlachthof` | Nutze dies bei Tier 098 Schlachthof Halterpflichten Erklaeren, Tier 099 Schlachthof Eilantrag Bauen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `tier-schweinehaltung-behoerdenantrag` | Nutze dies bei Tier 062 Schweinehaltung Behoerdenantrag Schrei, Tier 063 Schweinehaltung Anordnung Angreifen, Tier 064 Schweinehaltung Beweise Sichern, Tier 065 Schweinehaltung Strafrisiko Bewerten: führt durch diese fachlich verbundenen... |
| `tier-schweinehaltung-kosten-halterpflichten` | Nutze dies bei Tier 067 Schweinehaltung Kosten Klaeren, Tier 068 Schweinehaltung Halterpflichten Erklae, Tier 069 Schweinehaltung Eilantrag Bauen, Tier 070 Schweinehaltung Vergleich Suchen: führt durch diese fachlich verbundenen Module,... |
| `tier-tierschg-grundsatz-haltung-betreuung` | Nutze dies bei Tier 003 Tierschg Grundsatz Und Leiden Prüfen, Tier 005 Haltung Und Betreuung Dokumentieren, Tier 006 Anordnung Und Wegnahme Prüfen, Tier 007 Tierschutz Strafanzeige Vorbereiten: führt durch diese fachlich verbundenen Modu... |
| `tier-tiertransport-beweise-strafrisiko` | Nutze dies bei Tier 084 Tiertransport Beweise Sichern, Tier 085 Tiertransport Strafrisiko Bewerten, Tier 087 Tiertransport Kosten Klaeren, Tier 088 Tiertransport Halterpflichten Erklaere: führt durch diese fachlich verbundenen Module, wä... |
| `tier-tiertransport-eilantrag-suchen` | Nutze dies bei Tier 089 Tiertransport Eilantrag Bauen, Tier 090 Tiertransport Vergleich Suchen, Tier 091 Schlachthof Schutzbedarf Prüfen, Tier 092 Schlachthof Behoerdenantrag Schreiben: führt durch diese fachlich verbundenen Module, wähl... |
| `tier-veterinaeramt-bussgeldverfahren-tierschg` | Nutze dies bei Tier 004 Veterinaeramt Zustaendigkeit, Tier 008 Bussgeldverfahren Tierschg, Tier 014 Tierheimvertrag Und Kosten, Tier 026 Hundehaltung Bussgeld Verteidigen: führt durch diese fachlich verbundenen Module, wählt den passende... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
