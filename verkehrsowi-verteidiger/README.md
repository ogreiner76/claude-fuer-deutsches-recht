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
| `abstand-quellenkarte` | Nutze dies zur Quellenprüfung bei Abstand Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `alkohol-drogen-beweisverwertung` | Nutze dies bei Verkehrsowi Alkohol Drogen 24a, Verkehrsowi Beweisverwertung Standardisiert, Verkehrsowi Fahreridentifizierung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbar... |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `amtsgericht-drogen-interessen-einspruch` | Nutze dies bei Amtsgericht Mandantenkommunikation Entscheidungsvorlage, Drogen Mehrparteien Konflikt Und Interessen, Einspruch Dokumentenmatrix Und Lueckenliste: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `anhoerung-verkehrsowi-einspruch-messverfahren` | Nutze dies bei Anhoerung Fristen Form Und Zustaendigkeit, Verkehrsowi Fristen Einspruch, Verkehrsowi Messverfahren Geschwindigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `fahrverbot-geschwindigkeit-handy` | Nutze dies bei Fahrverbot Behörden Gericht Und Registerweg, Geschwindigkeit Verhandlung Vergleich Und Eskalation, Handy Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `hauptverhandlung-sonderfall-messakte-messung` | Nutze dies bei Hauptverhandlung Sonderfall Und Edge Case, Messakte Formular Portal Und Einreichung, Messung Fahrverbot Punkte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbar... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `punkte-rotlicht-verkehrsowi` | Nutze dies bei Punkte Risikoampel Und Gegenargumente, Rotlicht Schriftsatz Brief Und Memo Bausteine, Verkehrsowi Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `simulation-training-verjaehrung-zustellung` | Nutze dies bei Verkehrsowi Simulation Training, Verkehrsowi Verjaehrung Zustellung, Verkehrsowi Zeugen Polizei Strategie: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `verkehrsowi` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Verkehrsowi Rechtsprechungsrecherche: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `verkehrsowi-haertefall-fahrverbot` | Nutze dies bei Verkehrsowi Haertefall Fahrverbot, Verkehrsowi Hauptverhandlung Amtsgericht, Verkehrsowi Mandantenkommunikation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastba... |
| `verkehrsowi-punkte-fahrverbot` | Nutze dies bei Verkehrsowi Punkte Fahrverbot Flensburg, Verkehrsowi Rechtsbeschwerde, Verkehrsowi Rotlicht Abstand Handy: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Ar... |
| `verteidiger-beweislast-verkehrsowi` | Nutze dies bei Verteidiger Beweislast Und Darlegungslast, Verkehrsowi Aktenanlage, Verkehrsowi Akteneinsicht Messakte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbei... |
| `vowi-akteneinsicht` | Nutze dies bei Vowi Akteneinsicht Rohmessdaten Leitfaden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vowi-bussgeldbescheid-verkehrsowi-quality` | Nutze dies bei Vowi Bussgeldbescheid Prüfung Bauleiter, Verkehrsowi Kommandocenter, Verkehrsowi Quality Gate: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vowi-handyverstoss-akteneinsicht-alkohol` | Nutze dies bei Vowi Handyverstoss Spezial, Akteneinsicht Internationaler Bezug Und Schnittstellen, Alkohol Compliance Dokumentation Und Akte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den näc... |
| `vowi-tempomessverfahren-bussgeldbescheid` | Nutze dies bei Vowi Tempomessverfahren Fehlerquellen Spezial, Bussgeldbescheid Tatbestand Beweis Und Belege, Verkehrsowi Anhoerung Bussgeldbescheid: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |
| `zeugenstrategie-fehlerkatalog` | Nutze dies als Fehlerbremse bei Zeugenstrategie Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
