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
| `aktenanlage-fehlerkatalog` | Nutze dies, wenn Aktenanlage Fehlerkatalog im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflo... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Strafbefehl Verteidiger.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `deal-beweislast-einspruch` | Nutze dies, wenn Spezial Deal Beweislast Und Darlegungslast, Spezial Einspruch Risikoampel Und Gegenargumente, Spezial Einspruchsentscheidung Und Folgen im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Sp... |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstellung-153a-hauptverhandlung` | Nutze dies, wenn Strafbefehl Einstellung 153 153A 170, Strafbefehl Hauptverhandlung Vorbereitung, Strafbefehl Inhalt 409 Prüfung im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Strafbefehl Einstellung 15... |
| `einstellung-fahrerlaubnis` | Nutze dies, wenn Spezial Einstellung Compliance Dokumentation Und Akte, Spezial Fahrerlaubnis Mandantenentscheidung, Spezial Hauptverhandlung International Schnittstellen im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll.... |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Strafbefehl Verteidiger.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `nebenfolgen-fahrerlaubnis-strafbefehl` | Nutze dies, wenn Strafbefehl Nebenfolgen Fahrerlaubnis, Strafbefehl Pflichtverteidiger, Strafbefehl Polizeifilmerei 201 Kug im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Strafbefehl Nebenfolgen Fahrerl... |
| `nebenfolgen-strafbefehl-strafbefehls` | Nutze dies, wenn Spezial Nebenfolgen Verhandlung Vergleich Und Eskalation, Spezial Strafbefehl Dokumentenmatrix Und Lueckenliste, Spezial Strafbefehls Erstpruefung Und Mandatsziel im Plugin Strafbefehl Verteidiger konkret bearbeitet werd... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `pflichtverteidigung-quellenkarte` | Nutze dies, wenn Pflichtverteidigung Quellenkarte im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `rechtsmittel-tagessaetze-geldstrafe` | Nutze dies, wenn Strafbefehl Rechtsmittel Nach Urteil, Strafbefehl Tagessaetze Geldstrafe, Strafbefehl Wiedereinsetzung im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Strafbefehl Rechtsmittel Nach Urtei... |
| `stbv-einspruch-strafbefehl-fahrerlaubnis` | Nutze dies, wenn Stbv Einspruch Strafbefehl Leitfaden, Stbv Fahrerlaubnis Bei Strafbefehl Spezial, Stbv Strafbefehl Auslaendischer Mandant Spezial im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Stbv Ein... |
| `stbv-strafbefehl-abwesenheit-vertretung` | Nutze dies, wenn Stbv Strafbefehl Prüfung Bauleiter, Strafbefehl Abwesenheit Vertretung, Strafbefehl Akteneinsicht 147 im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Stbv Strafbefehl Prüfung Bauleiter,... |
| `strafbefehl` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Strafbefehl Rechtsprechungsrecherche im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team p... |
| `strafbefehl-einlassung-deal-verstaendigung` | Nutze dies, wenn Strafbefehl Beweis Und Einlassung, Strafbefehl Deal Verstaendigung, Strafbefehl Einspruch Beschraenkung im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Strafbefehl Beweis Und Einlassung,... |
| `strafbefehl-einspruch-aktenanlage` | Nutze dies, wenn Spezial Gegen Fristen Form Und Zustaendigkeit, Strafbefehl Fristen Einspruch, Strafbefehl Aktenanlage im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Spezial Gegen Fristen Form Und Zusta... |
| `strafbefehl-quality-gate-akteneinsicht` | Nutze dies, wenn Strafbefehl Kommandocenter, Strafbefehl Quality Gate, Spezial Akteneinsicht Behörden Gericht Und Registerweg im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Strafbefehl Kommandocenter, S... |
| `tagessaetze-verstaendigung-sonderfall` | Nutze dies, wenn Spezial Tagessaetze Schriftsatz Brief Und Memo Bausteine, Spezial Verstaendigung Sonderfall Und Edge Case, Spezial Verteidiger Formular Portal Und Einreichung im Plugin Strafbefehl Verteidiger konkret bearbeitet werden s... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verteidigung-wiedereinsetzung-zeugenstrategie` | Nutze dies, wenn Spezial Verteidigung Tatbestand Beweis Und Belege, Spezial Wiedereinsetzung Zahlen Schwellen Und Berechnung, Spezial Zeugenstrategie Mehrparteien Konflikt Und Interessen im Plugin Strafbefehl Verteidiger konkret bearbeit... |
| `zeugen-befragungsstrategie-strafbefehl` | Nutze dies, wenn Strafbefehl Zeugen Befragungsstrategie, Strafbefehl Zulässigkeit 407 im Plugin Strafbefehl Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Strafbefehl Zeugen Befragungsstrategie, Strafbefehl Zulässigkeit 407... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
