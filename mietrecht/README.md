# Mietrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`mietrecht`) | [`mietrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/mietrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Mietstreit Tannenkamp / Strassburger Immobilien GmbH — Altbau Leipzig-Plagwitz, Modernisierung und Mietminderung** (`mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp`) | [Gesamt-PDF lesen](../testakten/mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp/gesamt-pdf/mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp_gesamt.pdf) | [`testakte-mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-mietstreit-altbau-rosenbluete-leipzig-modernisierung-und-minderung-tannenkamp.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Mietrecht für Mieter und Vermieter sowie Wohnungseigentumsrecht mit ausschließlich amtlichen Mietspiegel-Quellen pro Bundesland und für Top- und Universitätsstädte. Workflows für Datenerhebung, Mieterhöhungs-Widerspruch, Mietsenkungsverlangen, Nebenkostenprüfung, Mieteranfragen, Kündigung, Kaution, WEG-Beschlussklage und Klageentwurf Amtsgericht.

## Rechtsstand und Quellen-Gate

Für aktuelle Mietrechts- und WEG-Fragen zuerst `/mietrecht:rechtsstand-mai-2026-faktenbank` laden. Der Skill enthält geprüfte freie Anker zu Mietpreisbremse, Modernisierung, Steckersolargeräten, virtueller Eigentümerversammlung, Verwalterabberufung, WEG-baulichen Veränderungen und Störerhaftung.

Keine BeckRS-, juris-, Kommentar- oder Aufsatzzitate aus Modellwissen. Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und freier Quelle; Mietspiegel nur aus amtlicher kommunaler Quelle oder der mitgelieferten Mietspiegel-Referenz.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `allgemein` | Einstieg, Triage und Workflow-Routing im Plugin. Fragt Rolle (Vermieter/Mieter/WEG/Verwalter), Ziel, Fristen, Unterlagen und Risiken ab und schlägt passende Spezial-Skills vor. Bei stummem Upload reagiert der Skill eigenständig: ordnet das Material, prüft Eil- und Fristenhinweise, schlägt den passenden Spezial-Skill vor oder stellt genau eine gezielte Rückfrage. |
| `eigenbedarfskuendigung-erstellen` | Vermietersicht — entwerfe eine ordentliche Kündigung wegen Eigenbedarfs nach § 573 Abs. 2 Nr. 2 BGB. Prüfroutine deckt berechtigtes Interesse (Eigennutzung Familienangehörige Haushaltsangehörige) konkrete Begründ… |
| `klageentwurf-amtsgericht` | Beide Rollen — entwirf eine Klageschrift zum Amtsgericht in einer Mietsache. Sachliche Zuständigkeit für Wohnraummietsachen nach § 23 Nr. 2a GVG ohne Rücksicht auf den Streitwert; bei Geschäftsraummiete allgemeine… |
| `lage-und-ausstattung-erheben` | Strukturierte Datenerhebung für die Einordnung in den Mietspiegel — Adresse Baujahr Wohnfläche Bad Küche Heizung Wohnungsausstattung Gebäudeausstattung. Erfasst alle Merkmale die in qualifizierten Mietspiegeln als… |
| `mahnung-zahlungsverzug-mieter` | Vermietersicht — verfasse Mahnung und ggf. fristlose Kündigung bei Zahlungsverzug des Mieters. Prüfroutine deckt Verzug nach § 286 BGB Fälligkeit der Miete (§ 556b Abs. 1 BGB) Mahnschreiben Aufrechnungsverbot frist… |
| `mandat-triage-mietrecht` | Strukturierte Eingangs-Abfrage für mietrechtliche Mandate. Klärt Mandantenrolle (Vermieter/Mieter/WEG-Eigentümer/Verwalter), Gegenstand (Wohnraum/Gewerbe/WEG) und Sachgebiet (Kündigung, Mieterhöhung, Mietminderung, Modernisierung, Nebenkosten, Mietkaution, Eigenbedarf, Räumung, WEG-Beschluss, WEG-Hausgeld). Fristen-Sofort-Check (§ 573c BGB, § 721 ZPO, § 45 WEG, § 558b BGB). Eskalations-Pfad bei laufenden Fristen. |
| `mieteranfragen-beantworten` | Vermieter- und Hausverwaltungssicht — beantworte Mieteranfragen sachlich und ehrlich. Deckt typische Themen ab (Mietminderung Mangelanzeige Modernisierungsankündigung Schönheitsreparaturen Hausordnung Kaution Eigenb… |
| `mieterhoehung-pruefen-widersprechen` | Mietersicht — prüfe ein Mieterhöhungsverlangen nach ortsüblicher Vergleichsmiete (§§ 558 ff. BGB) auf Form Frist Kappungsgrenze Begründung und entwirf bei Bedarf eine Zustimmungsverweigerung oder Teilzustimmung. P… |
| `mieterhoehungsverlangen-erstellen` | Vermietersicht — verfasse ein Mieterhöhungsverlangen auf ortsübliche Vergleichsmiete (§ 558a BGB) in Textform mit ordnungsgemäßer Begründung (Mietspiegel Sachverständigengutachten oder drei Vergleichswohnungen).… |
| `mietkaution-rueckforderung` | Mietersicht — Workflow zur Rückforderung der Mietkaution nach Beendigung des Mietverhältnisses. Nutzt Normtext, Nutzerangaben und verifizierte Quellen; Rechtsprechung nur nach Live-Prüfung mit Gericht, Datum und Aktenzeichen. |
| `mietpreisueberhoehung-wistrg-1954-mietwucher` | Dreistufige Prüfung überhöhter Wohnraummiete: Mietpreisbremse, § 5 WiStrG 1954 als Ordnungswidrigkeit und § 291 StGB als Straftat; mit Mietspiegel-, Beweis-, Rückforderungs- und Behördenpfad. |
| `mietsenkungsverlangen` | Mietersicht — prüfe eine laufende oder bei Vertragsschluss vereinbarte Miete auf Mietpreisbremse (§§ 556d ff. BGB), § 5 WiStrG 1954 (Mietpreisüberhöhung) und § 291 StGB (Mietwucher). Erzeugt ein… |
| `mietspiegel-quellen` | Verweist auf die mitgelieferte Referenz references/mietspiegel-quellen.md mit ausschließlich amtlichen Mietspiegel-Quellen (Bundesländer Top-Städte Universitätsstädte). Nutze diese Referenz immer wenn die ortsüb… |
| `nebenkostenabrechnung-erstellen` | Vermieter- und Hausverwaltungssicht — Workflow für rechtssichere Betriebskostenabrechnungen nach § 556 BGB und BetrKV. Deckt Abrechnungszeitraum Zugangsfrist (zwölf Monate) Umlagefähigkeit Verteilerschlüssel Heizk… |
| `nebenkostenabrechnung-pruefen` | Mietersicht — prüfe eine Betriebskostenabrechnung auf Form (§ 556 Abs. 3 BGB) Frist (Zugang innerhalb von zwölf Monaten nach Abrechnungszeitraum) Umlagefähigkeit nach BetrKV Verteilerschlüssel rechnerische Richtig… |
| `rechtsstand-mai-2026-faktenbank` | Quellen-Gate: Mietpreisbremse, Modernisierung, Steckersolargeräte, virtuelle Eigentümerversammlung, Verwalterabberufung, WEG-bauliche Veränderung und freie BGH-/Normquellen |
| `weg-beschluss-anfechten` | WEG-Sicht — Prüfraster für die Beschlussanfechtung in der Wohnungseigentümergemeinschaft nach §§ 44 ff. WEG (Reform 2020). Beschluss-, Anfechtungs-, Nichtigkeits- und Feststellungsklage. Prüft formelle Mängel (Ladung, Tagesordnung, Beschlussfähigkeit, Mehrheit, Stimmrechtsausschluss) und materielle Mängel (ordnungsmäßige Verwaltung, Treu und Glauben). Klagefrist ein Monat ab Beschluss (§ 45 WEG). |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

## Quellen-Disclaimer

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `amtlichen-amtsgericht-sonderfall` | Nutze dies bei Amtlichen Risikoampel Und Gegenargumente, Amtsgericht Sonderfall Und Edge Case, Ausschliesslich Dokumentenmatrix Und Lueckenliste: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `bundesland-datenerhebung-grossstadt` | Nutze dies bei Bundesland Verhandlung Vergleich Und Eskalation, Datenerhebung Zahlen Schwellen Und Berechnung, Grossstadt Mietspiegel Und Kappung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `erstellung-fehlerkatalog` | Nutze dies als Fehlerbremse bei Erstellung Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `klageentwurf-amtsgericht-miet-gewerbemiete` | Nutze dies bei Klageentwurf Amtsgericht, Miet Gewerbemiete Vertragsklauseln Spezial, Miet Mietvertrag Bauleiter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschr... |
| `lage-ausstattung-mahnung-zahlungsverzug` | Nutze dies bei Lage Und Ausstattung Erheben, Mahnung Zahlungsverzug Mieter, Mandat Triage Mietrecht: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `miet-kuendigungsschutz-mietminderung` | Nutze dies bei Miet Kuendigungsschutz Checkliste, Miet Mietminderung Mangel Spezial, Mieteranfragen Beantworten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschr... |
| `mieter-mieteranfragen-mandantenentscheidung` | Nutze dies bei Mieter Tatbestand Beweis Und Belege, Mieteranfragen Mandantenentscheidung, Mieterhoehungs Compliance Dokumentation Und Akte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächs... |
| `mieterhoehung-widersprechen` | Nutze dies bei Mieterhoehung Prüfen Widersprechen, Mieterhoehungsverlangen Erstellen, Mietkaution Rueckforderung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssch... |
| `mietpreisueberhoehung-wistrg` | Nutze dies bei Mietpreisueberhoehung Wistrg 1954 Mietwucher, Mietsenkungsverlangen, Mietspiegel Quellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `mietrecht-mietsenkungsverlangen-international` | Nutze dies bei Mietrecht Erstpruefung Und Mandatsziel, Mietsenkungsverlangen International Schnittstellen, Mietspiegel Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `mr-betriebskostenabrechnung-mr` | Nutze dies bei Mr Betriebskostenabrechnung Fehler Spezial, Mr Kuendigungsschutz Praxis, Mr Modernisierung Und Rolling Rent Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `mr-einfuehrung-klageentwurf-beweislast` | Nutze dies bei Mr Einfuehrung Vertragstypen, Klageentwurf Beweislast Und Darlegungslast, Eigenbedarfskuendigung Erstellen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren A... |
| `nebenkostenabrechnung-erstellen-faktenbank` | Nutze dies bei Nebenkostenabrechnung Erstellen, Nebenkostenabrechnung Prüfen, Rechtsstand Mai 2026 Faktenbank: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `nebenkostenpruefung-prozessstrategie` | Nutze dies bei Nebenkostenpruefung Formular Portal Und Einreichung, Prozessstrategie Mieterhoehung, Quellen Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `universitaetsstaedte-quellenkarte-check` | Nutze dies zur Quellenprüfung bei Universitaetsstaedte Quellenkarte Check: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `vermieter` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Vermieter Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `widerspruch-interessen` | Nutze dies bei Widerspruch Mehrparteien Konflikt Und Interessen, Betriebskostenabrechnung Belege Und Formelpruefer, Weg Beschluss Anfechten: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näch... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
