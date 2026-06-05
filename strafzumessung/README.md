# Strafzumessung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strafzumessung`) | [`strafzumessung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strafzumessung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Strafzumessung Bankert — Untreue, LG Frankfurt / BGH Revision** (`strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung`) | [Gesamt-PDF lesen](../testakten/strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung/gesamt-pdf/strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung_gesamt.pdf) | [`testakte-strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-strafzumessung-vermoegensdelikt-bankert-frankfurt-untreue-haupt-und-revisionsverhandlung.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Plugin für die **Strafzumessung nach deutschem Strafrecht** — vom Strafbefehl bis zur großen Strafkammer. Adressaten: Strafverteidiger und Staatsanwaltschaft.

## Worum geht es?

Strafzumessung ist die zentrale richterliche Aufgabe nach Schuldspruch: Bestimmung von Strafart und Strafhoehe innerhalb des gesetzlichen Strafrahmens auf Grundlage der **Schuld** (§ 46 Abs. 1 Satz 1 StGB), unter Beruecksichtigung der **praeventiven Wirkungen** (§ 46 Abs. 1 Satz 2 StGB), nach den **Strafzumessungstatsachen** des § 46 Abs. 2 StGB und unter Beachtung des **Doppelverwertungsverbots** (§ 46 Abs. 3 StGB).

Das Plugin deckt die Strafzumessung vom Strafbefehlsverfahren ueber die Hauptverhandlung bis zur Vollstreckung ab, inklusive Bewaehrung, Strafmilderung, Regelbeispielen, Gesamtstrafenbildung, Verstaendigung und Jugendstrafrecht.

## Schnellstart

1. Mit `orientierung-strafzumessung-triage` einsteigen.
2. Rolle (Strafverteidigung, Staatsanwaltschaft) und Verfahrensstadium (Strafbefehl, Anklage, Hauptverhandlung, Urteil, Berufung, nachtraegliche Gesamtstrafe) angeben.
3. Den vom Triage-Skill empfohlenen Spezial-Skill aktivieren.
4. Bei Bedarf parallel mit den Plugins `strafbefehl-verteidiger` oder `fachanwalt-strafrecht` arbeiten.

## Enthaltene Skills

### Block A — Orientierung und Grundlagen
- `orientierung-strafzumessung-triage` — Einstieg, Triage, Spezial-Skill-Routing.
- `paragraph-46-stgb-grundsatz-strafzumessung` — § 46 StGB, Schuld als Grundlage.
- `strafzumessungs-tatsachen-46-ii-stgb` — Katalog § 46 Abs. 2 StGB.
- `strafrahmen-und-strafzumessungsstufen` — Strafrahmen-Logik vor jeder Zumessung.

### Block B — Geldstrafe
- `geldstrafe-tagessatzanzahl-bestimmen` — § 40 Abs. 1 StGB, Tagessatzanzahl als Schuldgroesse.
- `tagessatzhoehe-40-ii-stgb-nettotagesverdienst` — § 40 Abs. 2 StGB, Nettoeinkommen / 30.
- `geldstrafe-vs-freiheitsstrafe-47-stgb` — Vorrang Geldstrafe; § 47 StGB.

### Block C — Freiheitsstrafe und Bewaehrung
- `freiheitsstrafe-strafmass-pruefen` — Konkrete Zumessung im Strafrahmen.
- `bewaehrung-56-stgb-positive-sozialprognose` — § 56 StGB.
- `bewaehrung-auflagen-und-weisungen-56b-c-stgb` — §§ 56b, 56c StGB.
- `bewaehrungswiderruf-56f-stgb` — § 56f StGB.
- `freiheitsstrafe-ohne-bewaehrung-vollstreckung` — U-Haft-Anrechnung § 51 StGB, Reststrafenaussetzung § 57 StGB.

### Block D — Strafmilderung und Schaerfung
- `strafmilderung-49-stgb-zwingend-fakultativ` — § 49 StGB.
- `minder-schwerer-fall-und-besonders-schwerer-fall` — Strafrahmen-Modifikation.
- `regelbeispiele-rechtsprechung` — § 243 StGB, § 263 Abs. 3 StGB u.a.
- `taeter-opfer-ausgleich-46a-stgb-und-schadenswiedergutmachung` — § 46a StGB; BGH 4 StR 232/25.

### Block E — Strafbefehl und kleine Verfahren
- `strafbefehl-strafzumessung-407-stpo` — Strafzumessung im Strafbefehl.
- `153a-stpo-einstellung-gegen-auflage` — Einstellung mit Auflage.

### Block F — Hauptverhandlung und Verstaendigung
- `verstaendigung-257c-stpo-strafzumessung` — § 257c StPO; BVerfG 2 BvR 2628/10; BGH 1 StR 525/11.
- `gestaendnis-und-strafmilderung` — Gestaendnis als Strafmilderungsgrund.
- `267-iii-stpo-begruendungsanforderungen-strafurteil` — Strafurteil-Begruendung.

### Block G — Gesamtstrafenbildung
- `gesamtstrafenbildung-53-54-stgb-erste-instanz` — §§ 53, 54 StGB.
- `nachtraegliche-gesamtstrafenbildung-55-stgb` — § 55 StGB, Zaesurwirkung, § 460 StPO.
- `haerteausgleich-bei-nachtraeglicher-gesamtstrafenbildung` — BGH-staendige Linie.

### Block H — Sonderfaelle
- `jgg-strafzumessung-jugendstrafe-erziehungsmassregeln` — JGG; § 105 JGG Heranwachsende.

## Querverweise zu anderen Plugins

- `strafbefehl-verteidiger` — Spezial-Plugin Strafbefehlsverfahren.
- `fachanwalt-strafrecht` — Strafrechts-Gesamtverteidigung, Plaedoyer, Revision.
- `verkehrsowi-verteidiger` — Verkehrs-OWi-Strafzumessung.
- `urteilsbauer-relationsmacher` — Urteilsverfassung.
- `subsumtions-pruefer` — vor Schuldspruch.

## Hinweise zur Anwendung

- **Quellenregel beachten**: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen. Aktenzeichen vor Zitat in **dejure.org** oder **openjur.de** verifizieren. Lizenzierte Datenbanken nur bei vorhandenem Zugang.
- **Keine Praejudizienbindung** (Ausnahme § 31 BVerfGG). BGH-Linien sind argumentationsstuetzend, nicht bindend.
- **Mandantengeheimnis** wahren (§ 43a Abs. 2 BRAO; § 203 StGB).
- **Frueher BGH-Beschluss** zum TOA: BGH, Beschluss vom 20.11.2025 — 4 StR 232/25 (friedensstiftender kommunikativer Prozess).
- **BVerfG zur Verstaendigung**: 2 BvR 2628/10 vom 19.03.2013.
- **BGH-Belehrungspflicht**: 1 StR 525/11 vom 07.02.2012.

## Stand

- 05/2026.
- §§ 38 ff. StGB, §§ 407 ff. StPO, JGG, BtMG.
- Aktualitaetspruefung jaehrlich empfohlen.

## Lizenz

Apache-2.0 OR MIT (siehe Plugin-Root).


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `153a-stpo-iii-stpo-bewaehrung-stgb` | Nutze dies bei 153a Stpo Einstellung Gegen Auflage, 267 Iii Stpo Begruendungsanforderungen Strafurteil, Bewaehrung 56 Stgb Positive Sozialprognose: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `bewaehrung-auflagen-bewaehrungswiderruf-56f` | Nutze dies bei Bewaehrung Auflagen Und Weisungen 56b C Stgb, Bewaehrungswiderruf 56f Stgb, Freiheitsstrafe Ohne Bewaehrung Vollstreckung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `bewaehrung-interessen-deutschem` | Nutze dies bei Bewaehrung Mehrparteien Konflikt Und Interessen, Deutschem Tatbestand Beweis Und Belege, Freiheitsstrafe Compliance Dokumentation Und Akte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `freiheitsstrafe-strafmass-geldstrafe` | Nutze dies bei Freiheitsstrafe Strafmass Prüfen, Geldstrafe Tagessatzanzahl Bestimmen, Geldstrafe Vs Freiheitsstrafe 47 Stgb: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbare... |
| `geldstrafe-grossen-rechtsmittel` | Nutze dies bei Geldstrafe Zahlen Schwellen Und Berechnung, Grossen Risikoampel Und Gegenargumente, Rechtsmittel Und Gesamtstrafenfolgen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten... |
| `gesamtstrafenbildung-stgb-gestaendnis` | Nutze dies bei Gesamtstrafenbildung 53 54 Stgb Erste Instanz, Gestaendnis Und Strafmilderung, Haerteausgleich Bei Nachtraeglicher Gesamtstrafenbildung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `jgg-jugendstrafe-minder-schwerer` | Nutze dies bei Jgg Strafzumessung Jugendstrafe Erziehungsmassregeln, Minder Schwerer Fall Und Besonders Schwerer Fall, Nachtraegliche Gesamtstrafenbildung 55 Stgb: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpf... |
| `orientierung-triage-paragraph-stgb-besonders` | Nutze dies bei Orientierung Strafzumessung Triage, Paragraph 46 Stgb Grundsatz Strafzumessung, Besonders Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `regelbeispiele` | Nutze dies bei Chronologie Und Belegmatrix, Fristen Und Risikoampel, Regelbeispiele Rechtsprechung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `regelbeispiele-stgb-strafbefehl` | Nutze dies bei Regelbeispiele Internationaler Bezug Und Schnittstellen, Stgb Schriftsatz Brief Und Memo Bausteine, Strafbefehl Dokumentenmatrix Und Lueckenliste: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `schwerer-fehlerkatalog` | Nutze dies als Fehlerbremse bei Schwerer Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `strafbefehl-stpo-strafmilderung-stgb` | Nutze dies bei Strafbefehl Strafzumessung 407 Stpo, Strafmilderung 49 Stgb Zwingend Fakultativ, Strafrahmen Und Strafzumessungsstufen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten b... |
| `strafkammer-strafzumessung` | Nutze dies bei Strafkammer Behörden Gericht Und Registerweg, Strafzumessung Erstpruefung Und Mandatsziel, Strafzumessungstatsachen Vergleich Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `strafrecht-verfahrensstadium-strafbefehl` | Nutze dies bei Strafrecht Fristen Form Und Zustaendigkeit, Verfahrensstadium Strafbefehl Bis Kammer, Taeter Opfer Ausgleich 46a Stgb Und Schadenswiedergutmachung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfa... |
| `strafz-aufklaerungshilfe-kronzeuge` | Nutze dies bei Strafz Aufklaerungshilfe Kronzeuge Spezial, Strafz Sicherungsverwahrung Spezial, Strafz Strafrahmenmilderung Leitfaden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten b... |
| `strafz-strafzumessungstatsachen` | Nutze dies bei Strafz Strafzumessungstatsachen Bauleiter, Strafzumessungs Tatsachen 46 Ii Stgb, Tagessatzhoehe 40 Ii Stgb Nettotagesverdienst: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `tagessatz-quellenkarte` | Nutze dies zur Quellenprüfung bei Tagessatz Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verstaendigung-257c` | Nutze dies bei Verstaendigung 257c Stpo Strafzumessung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
