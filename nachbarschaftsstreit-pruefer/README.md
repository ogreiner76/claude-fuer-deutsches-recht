# Nachbarschaftsstreit-Prüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`nachbarschaftsstreit-pruefer`) | [`nachbarschaftsstreit-pruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/nachbarschaftsstreit-pruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Nachbarschaftsstreit Rosengartenstraße** (`nachbarschaftsstreit-horrorfall-rosengarten`) | [Gesamt-PDF lesen](../testakten/nachbarschaftsstreit-horrorfall-rosengarten/gesamt-pdf/nachbarschaftsstreit-horrorfall-rosengarten_gesamt.pdf) | [`testakte-nachbarschaftsstreit-horrorfall-rosengarten.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-nachbarschaftsstreit-horrorfall-rosengarten.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Plugin für Nachbarrecht und eskalierte Grundstückskonflikte: Überbau, Überhang, Äste und Wurzeln, Grenzbäume, Einfriedung, Zaun, Mauer, Hecke, Immissionen, Vertiefung, drohender Einsturz, Notweg, Hammerschlags- und Leiterrecht, Beweissicherung, Aufforderungsschreiben, einstweilige Verfügung, Klage und Vergleich.

**Keine Rechtsberatung.** Das Plugin erzeugt strukturierte Prüfungen, Entwürfe und Workflows zur anwaltlichen Kontrolle. Landesnachbarrecht, Baumschutzsatzungen, Bebauungspläne und örtliche Satzungen müssen im konkreten Fall geprüft werden.

## Start

```
/nachbarschaftsstreit-pruefer:allgemein
```

Der Einstieg fragt in kurzer Zeit ab: Grundstücke, Grenze, Bundesland, Streitgegenstand, Gefahr, Beweislage, bisherige Schreiben, gewünschter Ton und Ziel. Danach routet er zu den Spezialskills.

## Skills (20)

| Skill | Zweck |
|---|---|
| `allgemein` | Schöner Einstieg, Fristen-/Gefahrenscan, Routing und Arbeitsplan |
| `nachbarrecht-kaltstart-triage` | Erstaufnahme des Konflikts mit Bundesland, Grundstück, Beteiligten und Risiko |
| `akten-und-grundstuecksaufnahme` | Grundbuch, Liegenschaftskarte, Baulast, Dienstbarkeit, Fotos und Chronologie erfassen |
| `anspruchslandkarte-bgb-nachbarrecht` | Anspruchsgrundlagen nach BGB und Landesrecht sortieren |
| `ueberbau-pruefung` | Überbau nach §§ 912-916 BGB, Widerspruch, Duldung, Rente, Abkauf |
| `ueberhang-aeste-wurzeln` | Überhängende Äste, Wurzeln, Fristsetzung, Selbsthilfe nach § 910 BGB |
| `grenzbaum-und-grenzanlage` | Grenzbaum, Grenzsträucher und gemeinschaftliche Grenzanlagen §§ 921-923 BGB |
| `einfriedung-zaun-mauer-hecke` | Zaun, Mauer, Hecke, Kosten, Standort, Ortsüblichkeit und Landesrecht |
| `immissionen-laerm-geruch-rauch-licht` | Geräusche, Gerüche, Rauch, Licht, Erschütterungen, § 906 BGB |
| `vertiefung-baugrube-stuetzverlust` | Baugrube, Unterfangung, Stütze des Nachbargrundstücks, § 909 BGB |
| `drohender-einsturz-gefahranlage` | Gefährliche Anlagen und Einsturzrisiken, §§ 907, 908 BGB |
| `notweg-zufahrt-wegerecht` | Notweg, Zufahrt, Grunddienstbarkeit, Baulast, §§ 917, 918 BGB |
| `hammerschlags-und-leiterrecht` | Betreten des Nachbargrundstücks für Bau-/Instandhaltungsarbeiten nach Landesrecht |
| `landesnachbarrecht-router` | Bundesland auswählen und landesrechtliche Prüfmodule planen |
| `beweissicherung-ortstermin-fotos` | Ortstermin, Fotoplan, Messpunkte, Sachverständige und selbständiges Beweisverfahren |
| `selbsthilfe-und-eskalationsgrenzen` | Was darf man selbst tun, was nicht, und wann drohen Besitz-/Eigentumsverletzungen? |
| `aufforderungsschreiben-nachbar` | Sachliches, druckvolles Anspruchs- und Fristsetzungsschreiben |
| `einstweilige-verfuegung-und-klage` | Eilrechtsschutz, Unterlassung, Beseitigung, Duldung, Feststellung, Streitwert |
| `vergleich-mediation-nachbarschaftsfrieden` | Vergleich, Nutzungsregelung, Rückschnittplan, Kosten- und Zugangslösung |
| `horrorfall-aktenauswertung` | Große unordentliche Nachbarschaftsakte auswerten und in Arbeitsstränge zerlegen |

## Quellenstand

Stand: 05/2026. Kernnormen: BGB §§ 903, 906-923, 823, 862, 1004; Landesnachbarrechtsgesetze und kommunale Satzungen nach Bundesland/Gemeinde.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anschluss-router` | Nutze dies bei Allgemein, Anschluss Skills Router, Chronologie Und Belegmatrix: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anspruchslandkarte-bgb-aufforderungsschreiben` | Nutze dies bei Anspruchslandkarte Bgb Nachbarrecht, Aufforderungsschreiben Nachbar, Beweissicherung Ortstermin Fotos: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `aufforderung-beweise-red-grenzbaum` | Nutze dies bei Aufforderung Mandantenkommunikation Entscheidungsvorlage, Beweise Red Team Und Qualitaetskontrolle, Grenzbaum Schriftsatz Brief Und Memo Bausteine: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfa... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `drohender-einsturz-einfriedung-zaun` | Nutze dies bei Drohender Einsturz Gefahranlage, Einfriedung Zaun Mauer Hecke, Einstweilige Verfuegung Und Klage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschr... |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `fristen-risikoampel-mandantenkommunikation` | Nutze dies bei Fristen Und Risikoampel, Mandantenkommunikation, Redteam Qualitygate: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `fristennotiz-naechster-ueberbau-akten` | Nutze dies bei Prüfer Fristennotiz Und Naechster Schritt, Ueberbau Fristen Form Und Zustaendigkeit, Akten Und Grundstuecksaufnahme: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten bela... |
| `grenzbaum-grenzanlage-hammerschlags` | Nutze dies bei Grenzbaum Und Grenzanlage, Hammerschlags Und Leiterrecht, Horrorfall Aktenauswertung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `hammerschlagsrecht-hecke-immissionen` | Nutze dies bei Hammerschlagsrecht Formular Portal Und Einreichung, Hecke Zahlen Schwellen Und Berechnung, Immissionen Compliance Dokumentation Und Akte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lief... |
| `immissionen-laerm-landesnachbarrecht` | Nutze dies bei Immissionen Laerm Geruch Rauch Licht, Landesnachbarrecht Router, Nach Grenzbebauung Ueberhang Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeit... |
| `kaltstart-abschlussprodukt-und-uebergabe` | Nutze dies zum Einstieg in Kaltstart: Abschlussprodukt und Übergabe: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `klage-beweislast-nachbarrecht` | Nutze dies bei Klage Beweislast Und Darlegungslast, Nachbarrecht Erstpruefung Und Mandatsziel, Nachbarschaftsstreit Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `laermimmissionen-mediation-vorrang` | Nutze dies bei Nach Laermimmissionen Spezial, Nach Mediation Vorrang Leitfaden, Nach Nachbarrechtsuebersicht Bauleiter: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbe... |
| `mauer-quellenkarte` | Nutze dies zur Quellenprüfung bei Mauer Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `nachbarrecht-kaltstart-triage` | Erstaufnahme eines Nachbarrechtsfalls: Beteiligte, Grundstücke, Bundesland, Grenze, Streitgegenstand, Gefahr, Fristen, Beweise, bisherige Eskalation und Ziel klären; danach in die passenden Fachmodule routen. |
| `notweg-ueberhang-sonderfall-edge` | Nutze dies bei Notweg Internationaler Bezug Und Schnittstellen, Ueberhang Dokumentenmatrix Und Lueckenliste, Vergleich Sonderfall Und Edge Case: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `notweg-zufahrt-selbsthilfe-eskalationsgrenzen` | Nutze dies bei Notweg Zufahrt Wegerecht, Selbsthilfe Und Eskalationsgrenzen, Aeste Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssc... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `ueberbau-ueberhang-aeste-mediation` | Nutze dies bei Ueberbau Prüfung, Ueberhang Aeste Wurzeln, Vergleich Mediation Nachbarschaftsfrieden: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `vertiefung-baugrube` | Nutze dies bei Vertiefung Baugrube Stuetzverlust: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `vertiefung-interessen-wurzeln-zaun` | Nutze dies bei Vertiefung Mehrparteien Konflikt Und Interessen, Wurzeln Behörden Gericht Und Registerweg, Zaun Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
