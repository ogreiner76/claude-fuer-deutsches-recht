# Strafbefehl-Verteidiger

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strafbefehl-verteidiger`) | [`strafbefehl-verteidiger.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strafbefehl-verteidiger.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **LUMEN Studios GmbH — Insolvenz- und Wirtschaftsstrafverfahren** (`lumen-studios-insolvenz-strafverfahren`) | [Gesamt-PDF lesen](../testakten/lumen-studios-insolvenz-strafverfahren/gesamt-pdf/lumen-studios-insolvenz-strafverfahren_gesamt.pdf) | [`testakte-lumen-studios-insolvenz-strafverfahren.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-lumen-studios-insolvenz-strafverfahren.zip) |
| **Strafbefehl – Ladendiebstahl und Fahrerflucht** (`strafbefehl-ladendiebstahl-fahrerflucht`) | [Gesamt-PDF lesen](../testakten/strafbefehl-ladendiebstahl-fahrerflucht/gesamt-pdf/strafbefehl-ladendiebstahl-fahrerflucht_gesamt.pdf) | [`testakte-strafbefehl-ladendiebstahl-fahrerflucht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-strafbefehl-ladendiebstahl-fahrerflucht.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein freistehender Strafbefehls-Assistent für Kanzleien: vom Fristnotruf über Akteneinsicht und Einspruch bis zur beschränkten Rechtsfolgenstrategie oder Hauptverhandlung.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn Register, Kanzleisoftware, beA, E-Mail, Datenraum oder Aktenexport fehlen, arbeitet es mit manuellen Uploads oder mit einem klar gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Mit `strafbefehl-kommandocenter` starten.
3. Frist, Zustellung, Aktenzeichen, vorhandene Unterlagen und Mandantenziel nennen.
4. Fehlende Unterlagen nicht raten lassen, sondern mit der passenden Vorlage nachfordern oder Simulation ausdrücklich aktivieren.
5. Vor Versand oder Termin immer das Qualitätstor laufen lassen.

## Enthaltene Skills

- `strafbefehl-kommandocenter` - Strafbefehl-Kommandocenter
- `strafbefehl-aktenanlage` - Aktenanlage Strafbefehl
- `strafbefehl-fristen-einspruch` - Frist und Einspruch nach § 410 StPO
- `strafbefehl-akteneinsicht-147` - Akteneinsicht
- `strafbefehl-zulaessigkeit-407` - Zulässigkeit des Strafbefehls
- `strafbefehl-inhalt-409-pruefung` - Inhaltsprüfung nach § 409 StPO
- `strafbefehl-einspruch-beschraenkung` - Einspruch beschränken oder nicht
- `strafbefehl-wiedereinsetzung` - Wiedereinsetzung
- `strafbefehl-pflichtverteidiger` - Pflichtverteidigung
- `strafbefehl-polizeifilmerei-201-kug` - Film-, Foto- und Tonaufnahmen von Polizeieinsätzen
- `strafbefehl-tagessaetze-geldstrafe` - Tagessätze und Geldstrafe
- `strafbefehl-nebenfolgen-fahrerlaubnis` - Nebenfolgen
- `strafbefehl-beweis-und-einlassung` - Beweis und Einlassung
- `strafbefehl-zeugen-befragungsstrategie` - Zeugenbefragung
- `strafbefehl-hauptverhandlung-vorbereitung` - Hauptverhandlung vorbereiten
- `strafbefehl-abwesenheit-vertretung` - Abwesenheit und Vertretung
- `strafbefehl-einstellung-153-153a-170` - Einstellung und Verständigung
- `strafbefehl-deal-verstaendigung` - Gesprächsstrategie mit Gericht und Staatsanwaltschaft
- `strafbefehl-rechtsmittel-nach-urteil` - Rechtsmittel nach Urteil
- `strafbefehl-rechtsprechungsrecherche` - Rechtsprechungsrecherche
- `strafbefehl-quality-gate` - Qualitätstor

## Vorlagen

- `assets/templates/strafbefehl-mandatskarte.md` - Strafbefehl-Mandatskarte
- `assets/templates/frist-einspruch-410.md` - Frist und Einspruch nach § 410 StPO
- `assets/templates/akteneinsicht-147.md` - Akteneinsicht nach § 147 StPO
- `assets/templates/strafbefehl-inhaltspruefung.md` - Inhaltsprüfung Strafbefehl
- `assets/templates/einspruch-unbeschraenkt.md` - Unbeschränkter Einspruch
- `assets/templates/einspruch-beschraenkt.md` - Beschränkter Einspruch
- `assets/templates/wiedereinsetzung.md` - Wiedereinsetzung
- `assets/templates/pflichtverteidiger-check.md` - Pflichtverteidiger-Check
- `assets/templates/tagessaetze.md` - Tagessatzprüfung
- `assets/templates/einlassungsstrategie.md` - Einlassungsstrategie
- `assets/templates/zeugen-fragenkatalog.md` - Zeugenfragen
- `assets/templates/hauptverhandlung-plan.md` - Hauptverhandlung
- `assets/templates/einstellung-153-153a.md` - Einstellung nach §§ 153, 153a StPO
- `assets/templates/nebenfolgen-fahrerlaubnis.md` - Nebenfolgen
- `assets/templates/rechtsmittel-nach-urteil.md` - Rechtsmittel nach Urteil
- `assets/templates/quality-gate.md` - Qualitätstor

## Freistehende Leitplanken

- Keine stillen Verweise auf andere Plugins.
- Keine produktive Rechtsberatung ohne anwaltliche Prüfung.
- Keine echten Mandatsgeheimnisse in ungeprüfte Cloud- oder KI-Umgebungen.
- Keine erfundenen Fundstellen, Aktenzeichen oder Rechtsprechung.
- Fristen, Rechtsmittel, Aussageverhalten und Nebenfolgen werden sichtbar geprüft.
- Jede Ausgabe muss so gestaltet sein, dass eine Berufsträgerin oder ein Berufsträger sie sofort prüfen, kürzen, freigeben oder verwerfen kann.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aktenanlage-fehlerkatalog` | Nutze dies als Fehlerbremse bei Aktenanlage Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `deal-beweislast-einspruch` | Nutze dies bei Deal Beweislast Und Darlegungslast, Einspruch Risikoampel Und Gegenargumente, Einspruchsentscheidung Und Folgen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstellung-153a-hauptverhandlung` | Nutze dies bei Strafbefehl Einstellung 153 153a 170, Strafbefehl Hauptverhandlung Vorbereitung, Strafbefehl Inhalt 409 Prüfung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `einstellung-fahrerlaubnis` | Nutze dies bei Einstellung Compliance Dokumentation Und Akte, Fahrerlaubnis Mandantenentscheidung, Hauptverhandlung International Schnittstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `nebenfolgen-fahrerlaubnis-strafbefehl` | Nutze dies bei Strafbefehl Nebenfolgen Fahrerlaubnis, Strafbefehl Pflichtverteidiger, Strafbefehl Polizeifilmerei 201 Kug: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren A... |
| `nebenfolgen-strafbefehl-strafbefehls` | Nutze dies bei Nebenfolgen Verhandlung Vergleich Und Eskalation, Strafbefehl Dokumentenmatrix Und Lueckenliste, Strafbefehls Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `pflichtverteidigung-quellenkarte` | Nutze dies zur Quellenprüfung bei Pflichtverteidigung Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rechtsmittel-tagessaetze-geldstrafe` | Nutze dies bei Strafbefehl Rechtsmittel Nach Urteil, Strafbefehl Tagessaetze Geldstrafe, Strafbefehl Wiedereinsetzung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbei... |
| `stbv-einspruch-strafbefehl-fahrerlaubnis` | Nutze dies bei Stbv Einspruch Strafbefehl Leitfaden, Stbv Fahrerlaubnis Bei Strafbefehl Spezial, Stbv Strafbefehl Auslaendischer Mandant Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `stbv-strafbefehl-abwesenheit-vertretung` | Nutze dies bei Stbv Strafbefehl Prüfung Bauleiter, Strafbefehl Abwesenheit Vertretung, Strafbefehl Akteneinsicht 147: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `strafbefehl` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Strafbefehl Rechtsprechungsrecherche: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `strafbefehl-einlassung-deal-verstaendigung` | Nutze dies bei Strafbefehl Beweis Und Einlassung, Strafbefehl Deal Verstaendigung, Strafbefehl Einspruch Beschraenkung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `strafbefehl-einspruch-aktenanlage` | Nutze dies bei Gegen Fristen Form Und Zustaendigkeit, Strafbefehl Fristen Einspruch, Strafbefehl Aktenanlage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `strafbefehl-quality-gate-akteneinsicht` | Nutze dies bei Strafbefehl Kommandocenter, Strafbefehl Quality Gate, Akteneinsicht Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeits... |
| `tagessaetze-verstaendigung-sonderfall` | Nutze dies bei Tagessaetze Schriftsatz Brief Und Memo Bausteine, Verstaendigung Sonderfall Und Edge Case, Verteidiger Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefer... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verteidigung-wiedereinsetzung-zeugenstrategie` | Nutze dies bei Verteidigung Tatbestand Beweis Und Belege, Wiedereinsetzung Zahlen Schwellen Und Berechnung, Zeugenstrategie Mehrparteien Konflikt Und Interessen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `zeugen-befragungsstrategie-strafbefehl` | Nutze dies bei Strafbefehl Zeugen Befragungsstrategie, Strafbefehl Zulaessigkeit 407: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
