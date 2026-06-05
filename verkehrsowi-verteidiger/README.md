# VerkehrsOWi-Verteidiger

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`verkehrsowi-verteidiger`) | [`verkehrsowi-verteidiger.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/verkehrsowi-verteidiger.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Norderhof-Tannenmoor — Abstandsverstoß Section Control BAB 7 Bispingen, Bußgeld und Fahrverbot** (`verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof`) | [Gesamt-PDF lesen](../testakten/verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof/gesamt-pdf/verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof_gesamt.pdf) | [`testakte-verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verkehrsowi-abstand-section-control-bab-7-bispingen-bussgeld-und-fahrverbot-norderhof.zip) |
| **VerkehrsOWi – Qualifizierter Rotlichtverstoß, Tempoüberschreitung und Fahrverbot** (`verkehrsowi-rotlicht-tempo`) | [Gesamt-PDF lesen](../testakten/verkehrsowi-rotlicht-tempo/gesamt-pdf/verkehrsowi-rotlicht-tempo_gesamt.pdf) | [`testakte-verkehrsowi-rotlicht-tempo.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-verkehrsowi-rotlicht-tempo.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein freistehender Verteidigungsassistent für Verkehrsordnungswidrigkeiten: vom Anhörungsbogen über Einspruch, Akteneinsicht, Messakte und Punkte bis zur Amtsgerichtsverhandlung.

Dieses Plugin ist **vollständig freistehend**. Es erwartet keine anderen Plugins, keine externen Agenten und keine besonderen Repo-Dateien außerhalb seines eigenen Ordners. Wenn Register, Kanzleisoftware, beA, E-Mail, Datenraum oder Aktenexport fehlen, arbeitet es mit manuellen Uploads oder mit einem klar gekennzeichneten Simulationsmodus.

## Schnellstart

1. Plugin aktivieren oder die ZIP aus dem Release installieren.
2. Mit `verkehrsowi-kommandocenter` starten.
3. Frist, Zustellung, Aktenzeichen, vorhandene Unterlagen und Mandantenziel nennen.
4. Fehlende Unterlagen nicht raten lassen, sondern mit der passenden Vorlage nachfordern oder Simulation ausdrücklich aktivieren.
5. Vor Versand oder Termin immer das Qualitätstor laufen lassen.

## Enthaltene Skills

- `verkehrsowi-kommandocenter` - VerkehrsOWi-Kommandocenter
- `verkehrsowi-aktenanlage` - Aktenanlage und Dokumentenregister
- `verkehrsowi-anhoerung-bussgeldbescheid` - Anhörung und Bußgeldbescheid prüfen
- `verkehrsowi-fristen-einspruch` - Fristen und Einspruch
- `verkehrsowi-verjaehrung-zustellung` - Verjährung und Zustellung
- `verkehrsowi-akteneinsicht-messakte` - Akteneinsicht und Messakte
- `verkehrsowi-messverfahren-geschwindigkeit` - Geschwindigkeitsmessung
- `verkehrsowi-rotlicht-abstand-handy` - Rotlicht, Abstand und Handy
- `verkehrsowi-alkohol-drogen-24a` - Alkohol und Drogen nach § 24a StVG
- `verkehrsowi-fahreridentifizierung` - Fahreridentifizierung
- `verkehrsowi-punkte-fahrverbot-flensburg` - Punkte, Fahrverbot und Flensburg
- `verkehrsowi-haertefall-fahrverbot` - Härtefall beim Fahrverbot
- `verkehrsowi-beweisverwertung-standardisiert` - Beweisverwertung und Standardisierung
- `verkehrsowi-zeugen-polizei-strategie` - Zeugen- und Polizeibefragung
- `verkehrsowi-hauptverhandlung-amtsgericht` - Hauptverhandlung vor dem Amtsgericht
- `verkehrsowi-rechtsbeschwerde` - Rechtsbeschwerde
- `verkehrsowi-rechtsprechungsrecherche` - Rechtsprechungsrecherche
- `verkehrsowi-mandantenkommunikation` - Mandantenkommunikation
- `verkehrsowi-simulation-training` - Simulation und Training
- `verkehrsowi-quality-gate` - Qualitätstor

## Vorlagen

- `assets/templates/verkehrsowi-mandatskarte.md` - VerkehrsOWi-Mandatskarte
- `assets/templates/frist-und-verjaehrung.md` - Fristen- und Verjährungsblatt
- `assets/templates/anhoerungsbogen-check.md` - Anhörungsbogen-Check
- `assets/templates/bussgeldbescheid-pruefung.md` - Bußgeldbescheid-Prüfung
- `assets/templates/einspruch-owig-67.md` - Einspruch nach § 67 OWiG
- `assets/templates/akteneinsicht-messakte.md` - Akteneinsicht und Messakte
- `assets/templates/messverfahren-checkliste.md` - Messverfahren-Checkliste
- `assets/templates/fahreridentifizierung.md` - Fahreridentifizierung
- `assets/templates/punkte-fahrverbot-matrix.md` - Punkte- und Fahrverbotsmatrix
- `assets/templates/haertefall-fahrverbot.md` - Härtefallpaket Fahrverbot
- `assets/templates/zeugen-polizei-fragenkatalog.md` - Zeugen- und Polizeifragen
- `assets/templates/hauptverhandlung-amtsgericht.md` - Hauptverhandlung Amtsgericht
- `assets/templates/rechtsbeschwerde-check.md` - Rechtsbeschwerde-Check
- `assets/templates/rechtsprechungsrecherche.md` - Rechtsprechungsrecherche
- `assets/templates/mandantenanschreiben.md` - Mandantenanschreiben
- `assets/templates/quality-gate.md` - Qualitätstor

## Freistehende Leitplanken

- Keine stillen Verweise auf andere Plugins.
- Keine produktive Rechtsberatung ohne anwaltliche Prüfung.
- Keine echten Mandatsgeheimnisse in ungeprüfte Cloud- oder KI-Umgebungen.
- Keine erfundenen Fundstellen, Aktenzeichen oder Rechtsprechung.
- Fristen, Rechtsmittel, Aussageverhalten und Nebenfolgen werden sichtbar geprüft.
- Jede Ausgabe muss so gestaltet sein, dass eine Berufsträgerin oder ein Berufsträger sie sofort prüfen, kürzen, freigeben oder verwerfen kann.

## Arbeitsakte

Zum Arbeiten liegt die Akte unter `testakten/verkehrsowi-rotlicht-tempo`. Sie wird im Release als `testakte-verkehrsowi-rotlicht-tempo.zip` bereitgestellt und ist kein Bestandteil des Plugin-ZIPs.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `abstand-quellenkarte` | Nutze dies, wenn Abstand Quellenkarte im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `alkohol-drogen-beweisverwertung` | Nutze dies, wenn Verkehrsowi Alkohol Drogen 24A, Verkehrsowi Beweisverwertung Standardisiert, Verkehrsowi Fahreridentifizierung im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Verkehrsowi Alkohol Drogen... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflo... |
| `amtsgericht-drogen-interessen-einspruch` | Nutze dies, wenn Spezial Amtsgericht Mandantenkommunikation Entscheidungsvorlage, Spezial Drogen Mehrparteien Konflikt Und Interessen, Spezial Einspruch Dokumentenmatrix Und Lueckenliste im Plugin Verkehrsowi Verteidiger konkret bearbeit... |
| `anhoerung-verkehrsowi-einspruch-messverfahren` | Nutze dies, wenn Spezial Anhoerung Fristen Form Und Zustaendigkeit, Verkehrsowi Fristen Einspruch, Verkehrsowi Messverfahren Geschwindigkeit im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Spezial Anhoer... |
| `anschluss-routing` | Nutze dies, wenn Anschluss-Routing im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Verkehrsowi Verteidiger.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Verkehrsowi Verteidiger.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `fahrverbot-geschwindigkeit-handy` | Nutze dies, wenn Spezial Fahrverbot Behörden Gericht Und Registerweg, Spezial Geschwindigkeit Verhandlung Vergleich Und Eskalation, Spezial Handy Zahlen Schwellen Und Berechnung im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden... |
| `hauptverhandlung-sonderfall-messakte-messung` | Nutze dies, wenn Spezial Hauptverhandlung Sonderfall Und Edge Case, Spezial Messakte Formular Portal Und Einreichung, Spezial Messung Fahrverbot Punkte im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Spe... |
| `output-waehlen` | Nutze dies, wenn Output wählen im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Output wählen prüfen.; Erstelle eine Arbeitsfassung zu Output wählen.; Welche Normen und Nachweise brauche ich?. |
| `punkte-rotlicht-verkehrsowi` | Nutze dies, wenn Spezial Punkte Risikoampel Und Gegenargumente, Spezial Rotlicht Schriftsatz Brief Und Memo Bausteine, Spezial Verkehrsowi Erstpruefung Und Mandatsziel im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Aus... |
| `quellen-livecheck` | Nutze dies, wenn Rechtsquellen-Livecheck im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `simulation-training-verjaehrung-zustellung` | Nutze dies, wenn Verkehrsowi Simulation Training, Verkehrsowi Verjaehrung Zustellung, Verkehrsowi Zeugen Polizei Strategie im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Verkehrsowi Simulation Training,... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verkehrsowi` | Nutze dies, wenn Workflow Mandantenkommunikation, Workflow Redteam Qualitygate, Verkehrsowi Rechtsprechungsrecherche im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team p... |
| `verkehrsowi-haertefall-fahrverbot` | Nutze dies, wenn Verkehrsowi Haertefall Fahrverbot, Verkehrsowi Hauptverhandlung Amtsgericht, Verkehrsowi Mandantenkommunikation im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Verkehrsowi Haertefall Fah... |
| `verkehrsowi-punkte-fahrverbot` | Nutze dies, wenn Verkehrsowi Punkte Fahrverbot Flensburg, Verkehrsowi Rechtsbeschwerde, Verkehrsowi Rotlicht Abstand Handy im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Verkehrsowi Punkte Fahrverbot Fl... |
| `verteidiger-beweislast-verkehrsowi` | Nutze dies, wenn Spezial Verteidiger Beweislast Und Darlegungslast, Verkehrsowi Aktenanlage, Verkehrsowi Akteneinsicht Messakte im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Spezial Verteidiger Beweisl... |
| `vowi-akteneinsicht` | Nutze dies, wenn Vowi Akteneinsicht Rohmessdaten Leitfaden im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Vowi Akteneinsicht Rohmessdaten Leitfaden prüfen.; Erstelle eine Arbeitsfassung zu Vowi Aktenein... |
| `vowi-bussgeldbescheid-verkehrsowi-quality` | Nutze dies, wenn Vowi Bussgeldbescheid Prüfung Bauleiter, Verkehrsowi Kommandocenter, Verkehrsowi Quality Gate im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bitte Vowi Bussgeldbescheid Prüfung Bauleiter, Ver... |
| `vowi-handyverstoss-akteneinsicht-alkohol` | Nutze dies, wenn Vowi Handyverstoss Spezial, Spezial Akteneinsicht Internationaler Bezug Und Schnittstellen, Spezial Alkohol Compliance Dokumentation Und Akte im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bi... |
| `vowi-tempomessverfahren-bussgeldbescheid` | Nutze dies, wenn Vowi Tempomessverfahren Fehlerquellen Spezial, Spezial Bussgeldbescheid Tatbestand Beweis Und Belege, Verkehrsowi Anhoerung Bussgeldbescheid im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Bit... |
| `zeugenstrategie-fehlerkatalog` | Nutze dies, wenn Zeugenstrategie Fehlerkatalog im Plugin Verkehrsowi Verteidiger konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist oder Beweislast übersehe ich?. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
