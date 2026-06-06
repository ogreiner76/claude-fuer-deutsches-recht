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

Beginne mit `tierschutzrecht-allgemein`. Das Plugin fragt zuerst nach Rolle, Ziel, Frist, Behörde/Gericht/Register, vorhandenen Unterlagen und gewünschtem Output. Danach schlägt es die passenden Spezialskills aus diesem Plugin vor.

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

Automatisch generierte Komplett-Liste aller 100 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `tier-001-kaltstart-tierschutzfall` | Tierschutzrecht: Kaltstart Tierschutzfall. Kaltstart Tierschutzfall im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `tier-002-90a-bgb-richtig-einordnen` | Tierschutzrecht: § 90a BGB richtig einordnen. § 90a BGB richtig einordnen im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, R... |
| `tier-005-haltung-und-betreuung-dokumentieren` | Tierschutzrecht: Haltung und Betreuung dokumentieren. Haltung und Betreuung dokumentieren im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-... |
| `tier-006-anordnung-und-wegnahme-pruefen` | Tierschutzrecht: Anordnung und Wegnahme prüfen. Anordnung und Wegnahme prüfen im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellenchec... |
| `tier-007-tierschutz-strafanzeige-vorbereiten` | Tierschutzrecht: Tierschutz-Strafanzeige vorbereiten. Tierschutz-Strafanzeige vorbereiten im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-... |
| `tier-008-bussgeldverfahren-tierschg` | Tierschutzrecht: Bußgeldverfahren TierSchG. Bußgeldverfahren TierSchG im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risik... |
| `tier-010-tierhalter-zivilrechtlich-beraten` | Tierschutzrecht: Tierhalter zivilrechtlich beraten. Tierhalter zivilrechtlich beraten im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Que... |
| `tier-011-tierarzt-und-behandlungsfehler` | Tierschutzrecht: Tierarzt und Behandlungsfehler. Tierarzt und Behandlungsfehler im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellench... |
| `tier-012-fundtier-und-eigentum` | Tierschutzrecht: Fundtier und Eigentum. Fundtier und Eigentum im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel u... |
| `tier-014-tierheimvertrag-und-kosten` | Tierschutzrecht: Tierheimvertrag und Kosten. Tierheimvertrag und Kosten im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, Ris... |
| `tier-015-zucht-und-qualzucht` | Tierschutzrecht: Zucht und Qualzucht. Zucht und Qualzucht im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und v... |
| `tier-016-tiertransport-pruefen` | Tierschutzrecht: Tiertransport prüfen. Tiertransport prüfen im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoampel und... |
| `tier-017-tierversuch-genehmigung` | Tierschutzrecht: Tierversuch Genehmigung. Tierversuch Genehmigung im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risikoamp... |
| `tier-019-tierschutzverein-handlungsoptionen` | Tierschutzrecht: Tierschutzverein Handlungsoptionen. Tierschutzverein Handlungsoptionen im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Q... |
| `tier-020-beweisfotos-und-datenschutz` | Tierschutzrecht: Beweisfotos und Datenschutz. Beweisfotos und Datenschutz im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, R... |
| `tier-021-hundehaltung-schutzbedarf-pruefen` | Tierschutzrecht: Hundehaltung: Schutzbedarf prüfen. Schutzbedarf prüfen für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quel... |
| `tier-023-hundehaltung-anordnung-angreifen` | Tierschutzrecht: Hundehaltung: Anordnung angreifen. Anordnung angreifen für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quel... |
| `tier-024-hundehaltung-beweise-sichern` | Tierschutzrecht: Hundehaltung: Beweise sichern. Beweise sichern für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck... |
| `tier-025-hundehaltung-strafrisiko-bewerten` | Tierschutzrecht: Hundehaltung: Strafrisiko bewerten. Strafrisiko bewerten für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-026-hundehaltung-bussgeld-verteidigen` | Tierschutzrecht: Hundehaltung: Bußgeld verteidigen. Bußgeld verteidigen für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quel... |
| `tier-028-hundehaltung-halterpflichten-erklaeren` | Tierschutzrecht: Hundehaltung: Halterpflichten erklären. Halterpflichten erklären für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit... |
| `tier-029-hundehaltung-eilantrag-bauen` | Tierschutzrecht: Hundehaltung: Eilantrag bauen. Eilantrag bauen für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck... |
| `tier-030-hundehaltung-vergleich-suchen` | Tierschutzrecht: Hundehaltung: Vergleich suchen. Vergleich suchen für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `tier-032-katzenkolonie-behoerdenantrag-schreibe` | Tierschutzrecht: Katzenkolonie: Behördenantrag schreiben. Behördenantrag schreiben für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `tier-033-katzenkolonie-anordnung-angreifen` | Tierschutzrecht: Katzenkolonie: Anordnung angreifen. Anordnung angreifen für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-034-katzenkolonie-beweise-sichern` | Tierschutzrecht: Katzenkolonie: Beweise sichern. Beweise sichern für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `tier-037-katzenkolonie-kosten-klaeren` | Tierschutzrecht: Katzenkolonie: Kosten klären. Kosten klären für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `tier-038-katzenkolonie-halterpflichten-erklaere` | Tierschutzrecht: Katzenkolonie: Halterpflichten erklären. Halterpflichten erklären für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `tier-039-katzenkolonie-eilantrag-bauen` | Tierschutzrecht: Katzenkolonie: Eilantrag bauen. Eilantrag bauen für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `tier-041-pferdestall-schutzbedarf-pruefen` | Tierschutzrecht: Pferdestall: Schutzbedarf prüfen. Schutzbedarf prüfen für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `tier-042-pferdestall-behoerdenantrag-schreiben` | Tierschutzrecht: Pferdestall: Behördenantrag schreiben. Behördenantrag schreiben für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit No... |
| `tier-043-pferdestall-anordnung-angreifen` | Tierschutzrecht: Pferdestall: Anordnung angreifen. Anordnung angreifen für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `tier-045-pferdestall-strafrisiko-bewerten` | Tierschutzrecht: Pferdestall: Strafrisiko bewerten. Strafrisiko bewerten für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quel... |
| `tier-046-pferdestall-bussgeld-verteidigen` | Tierschutzrecht: Pferdestall: Bußgeld verteidigen. Bußgeld verteidigen für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `tier-047-pferdestall-kosten-klaeren` | Tierschutzrecht: Pferdestall: Kosten klären. Kosten klären für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risi... |
| `tier-048-pferdestall-halterpflichten-erklaeren` | Tierschutzrecht: Pferdestall: Halterpflichten erklären. Halterpflichten erklären für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit No... |
| `tier-050-pferdestall-vergleich-suchen` | Tierschutzrecht: Pferdestall: Vergleich suchen. Vergleich suchen für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck... |
| `tier-051-rinderbetrieb-schutzbedarf-pruefen` | Tierschutzrecht: Rinderbetrieb: Schutzbedarf prüfen. Schutzbedarf prüfen für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-052-rinderbetrieb-behoerdenantrag-schreibe` | Tierschutzrecht: Rinderbetrieb: Behördenantrag schreiben. Behördenantrag schreiben für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `tier-054-rinderbetrieb-beweise-sichern` | Tierschutzrecht: Rinderbetrieb: Beweise sichern. Beweise sichern für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `tier-055-rinderbetrieb-strafrisiko-bewerten` | Tierschutzrecht: Rinderbetrieb: Strafrisiko bewerten. Strafrisiko bewerten für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/... |
| `tier-056-rinderbetrieb-bussgeld-verteidigen` | Tierschutzrecht: Rinderbetrieb: Bußgeld verteidigen. Bußgeld verteidigen für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-057-rinderbetrieb-kosten-klaeren` | Tierschutzrecht: Rinderbetrieb: Kosten klären. Kosten klären für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `tier-059-rinderbetrieb-eilantrag-bauen` | Tierschutzrecht: Rinderbetrieb: Eilantrag bauen. Eilantrag bauen für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `tier-060-rinderbetrieb-vergleich-suchen` | Tierschutzrecht: Rinderbetrieb: Vergleich suchen. Vergleich suchen für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenc... |
| `tier-061-schweinehaltung-schutzbedarf-pruefen` | Tierschutzrecht: Schweinehaltung: Schutzbedarf prüfen. Schutzbedarf prüfen für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm... |
| `tier-063-schweinehaltung-anordnung-angreifen` | Tierschutzrecht: Schweinehaltung: Anordnung angreifen. Anordnung angreifen für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm... |
| `tier-064-schweinehaltung-beweise-sichern` | Tierschutzrecht: Schweinehaltung: Beweise sichern. Beweise sichern für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `tier-065-schweinehaltung-strafrisiko-bewerten` | Tierschutzrecht: Schweinehaltung: Strafrisiko bewerten. Strafrisiko bewerten für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit No... |
| `tier-066-schweinehaltung-bussgeld-verteidigen` | Tierschutzrecht: Schweinehaltung: Bußgeld verteidigen. Bußgeld verteidigen für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm... |
| `tier-068-schweinehaltung-halterpflichten-erklae` | Tierschutzrecht: Schweinehaltung: Halterpflichten erklären. Halterpflichten erklären für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffel... |
| `tier-069-schweinehaltung-eilantrag-bauen` | Tierschutzrecht: Schweinehaltung: Eilantrag bauen. Eilantrag bauen für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `tier-070-schweinehaltung-vergleich-suchen` | Tierschutzrecht: Schweinehaltung: Vergleich suchen. Vergleich suchen für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quel... |
| `tier-072-gefluegelmast-behoerdenantrag-schreibe` | Tierschutzrecht: Geflügelmast: Behördenantrag schreiben. Behördenantrag schreiben für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit... |
| `tier-073-gefluegelmast-anordnung-angreifen` | Tierschutzrecht: Geflügelmast: Anordnung angreifen. Anordnung angreifen für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quel... |
| `tier-074-gefluegelmast-beweise-sichern` | Tierschutzrecht: Geflügelmast: Beweise sichern. Beweise sichern für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck... |
| `tier-077-gefluegelmast-kosten-klaeren` | Tierschutzrecht: Geflügelmast: Kosten klären. Kosten klären für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck, Ri... |
| `tier-078-gefluegelmast-halterpflichten-erklaere` | Tierschutzrecht: Geflügelmast: Halterpflichten erklären. Halterpflichten erklären für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit... |
| `tier-079-gefluegelmast-eilantrag-bauen` | Tierschutzrecht: Geflügelmast: Eilantrag bauen. Eilantrag bauen für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck... |
| `tier-081-tiertransport-schutzbedarf-pruefen` | Tierschutzrecht: Tiertransport: Schutzbedarf prüfen. Schutzbedarf prüfen für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-082-tiertransport-behoerdenantrag-schreibe` | Tierschutzrecht: Tiertransport: Behördenantrag schreiben. Behördenantrag schreiben für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `tier-083-tiertransport-anordnung-angreifen` | Tierschutzrecht: Tiertransport: Anordnung angreifen. Anordnung angreifen für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-085-tiertransport-strafrisiko-bewerten` | Tierschutzrecht: Tiertransport: Strafrisiko bewerten. Strafrisiko bewerten für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/... |
| `tier-086-tiertransport-bussgeld-verteidigen` | Tierschutzrecht: Tiertransport: Bußgeld verteidigen. Bußgeld verteidigen für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-087-tiertransport-kosten-klaeren` | Tierschutzrecht: Tiertransport: Kosten klären. Kosten klären für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `tier-088-tiertransport-halterpflichten-erklaere` | Tierschutzrecht: Tiertransport: Halterpflichten erklären. Halterpflichten erklären für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `tier-090-tiertransport-vergleich-suchen` | Tierschutzrecht: Tiertransport: Vergleich suchen. Vergleich suchen für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenc... |
| `tier-091-schlachthof-schutzbedarf-pruefen` | Tierschutzrecht: Schlachthof: Schutzbedarf prüfen. Schutzbedarf prüfen für Schlachthof im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `tier-092-schlachthof-behoerdenantrag-schreiben` | Tierschutzrecht: Schlachthof: Behördenantrag schreiben. Behördenantrag schreiben für Schlachthof im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit No... |
| `tier-094-schlachthof-beweise-sichern` | Tierschutzrecht: Schlachthof: Beweise sichern. Beweise sichern für Schlachthof im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `tier-095-schlachthof-strafrisiko-bewerten` | Tierschutzrecht: Schlachthof: Strafrisiko bewerten. Strafrisiko bewerten für Schlachthof im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quel... |
| `tier-096-schlachthof-bussgeld-verteidigen` | Tierschutzrecht: Schlachthof: Bußgeld verteidigen. Bußgeld verteidigen für Schlachthof im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `tier-097-schlachthof-kosten-klaeren` | Tierschutzrecht: Schlachthof: Kosten klären. Kosten klären für Schlachthof im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck, Risi... |
| `tier-099-schlachthof-eilantrag-bauen` | Tierschutzrecht: Schlachthof: Eilantrag bauen. Eilantrag bauen für Schlachthof im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `tier-eilrechtsschutz-tierhalter` | Tierschutzrecht: Eilrechtsschutz gegen Haltungsverbot. Eilrechtsschutz gegen Haltungsverbot im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Nor... |
| `tier-gefaehrlicher-hund-zucht-qualzucht` | Tierschutzrecht: Gefährlicher Hund Landesrecht. Gefährlicher Hund Landesrecht im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellenchec... |
| `tier-gefluegelmast-bussgeld-tiertransport` | Tierschutzrecht: Geflügelmast: Bußgeld verteidigen. Bußgeld verteidigen für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quel... |
| `tier-gefluegelmast-schutzbedarf` | Tierschutzrecht: Geflügelmast: Schutzbedarf prüfen. Schutzbedarf prüfen für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quel... |
| `tier-gefluegelmast-strafrisiko-kosten-klaeren` | Tierschutzrecht: Geflügelmast: Strafrisiko bewerten. Strafrisiko bewerten für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-gefluegelmast-suchen-tiertransport` | Tierschutzrecht: Geflügelmast: Vergleich suchen. Vergleich suchen für Geflügelmast im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `tier-hundehaltung-behoerdenantrag-anordnung` | Tierschutzrecht: Hundehaltung: Behördenantrag schreiben. Behördenantrag schreiben für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit... |
| `tier-hundehaltung-kosten-halterpflichten` | Tierschutzrecht: Hundehaltung: Kosten klären. Kosten klären für Hundehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck, Ri... |
| `tier-katzenkolonie-bussgeld-pferdestall` | Tierschutzrecht: Katzenkolonie: Bußgeld verteidigen. Bußgeld verteidigen für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-katzenkolonie-schutzbedarf` | Tierschutzrecht: Katzenkolonie: Schutzbedarf prüfen. Schutzbedarf prüfen für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-katzenkolonie-strafrisiko-kosten-klaeren` | Tierschutzrecht: Katzenkolonie: Strafrisiko bewerten. Strafrisiko bewerten für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/... |
| `tier-katzenkolonie-suchen-pferdestall` | Tierschutzrecht: Katzenkolonie: Vergleich suchen. Vergleich suchen für Katzenkolonie im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenc... |
| `tier-nutztierhaltung-kontrolle` | Tierschutzrecht: Nutztierhaltung Kontrolle. Nutztierhaltung Kontrolle im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, Risik... |
| `tier-pferdestall-beweise-strafrisiko-bewerten` | Tierschutzrecht: Pferdestall: Beweise sichern. Beweise sichern für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `tier-pferdestall-eilantrag-suchen` | Tierschutzrecht: Pferdestall: Eilantrag bauen. Eilantrag bauen für Pferdestall im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellencheck,... |
| `tier-rinderbetrieb-anordnung-beweise-sichern` | Tierschutzrecht: Rinderbetrieb: Anordnung angreifen. Anordnung angreifen für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Qu... |
| `tier-rinderbetrieb-halterpflichten-eilantrag` | Tierschutzrecht: Rinderbetrieb: Halterpflichten erklären. Halterpflichten erklären für Rinderbetrieb im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mi... |
| `tier-schlachthof-anordnung-beweise-sichern` | Tierschutzrecht: Schlachthof: Anordnung angreifen. Anordnung angreifen für Schlachthof im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quelle... |
| `tier-schweinehaltung-behoerdenantrag` | Tierschutzrecht: Schweinehaltung: Behördenantrag schreiben. Behördenantrag schreiben für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffel... |
| `tier-schweinehaltung-kosten-halterpflichten` | Tierschutzrecht: Schweinehaltung: Kosten klären. Kosten klären für Schweinehaltung im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `tier-tierschg-grundsatz-haltung-betreuung` | Tierschutzrecht: TierSchG-Grundsatz und Leiden prüfen. TierSchG-Grundsatz und Leiden prüfen im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Nor... |
| `tier-tiertransport-beweise-strafrisiko` | Tierschutzrecht: Tiertransport: Beweise sichern. Beweise sichern für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `tier-tiertransport-eilantrag-suchen` | Tierschutzrecht: Tiertransport: Eilantrag bauen. Eilantrag bauen für Tiertransport im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit Norm-/Quellenche... |
| `tier-veterinaeramt-bussgeldverfahren-tierschg` | Tierschutzrecht: Veterinäramt-Zuständigkeit. Veterinäramt-Zuständigkeit im Fachgebiet Tierschutzrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten: eigenständiges Prüffeld mit Norm-/Quellencheck, Ris... |
| `tierschutzrecht-kaltstart-triage` | Tierschutzrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |
| `tierschutzrecht-tier-schlachthof-halterpflichten-eilantrag` | Tierschutzrecht: Schlachthof: Halterpflichten erklären. Halterpflichten erklären für Schlachthof im Rahmen von Tierschutzrecht; Zuständigkeit, Tatbestand, Frist, Belege, Risiko und nächsten Schritt trennen: eigenständiges Prüffeld mit No... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
