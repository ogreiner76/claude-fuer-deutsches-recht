# JVEG-Kostenprüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`jveg-kostenpruefer`) | [`jveg-kostenpruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/jveg-kostenpruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Akte JVEG Zeugenentschädigung – Dr. Sophia Berger / LG Tübingen** (`jveg-zeugin-berger-lg-tuebingen`) | [Gesamt-PDF lesen](../testakten/jveg-zeugin-berger-lg-tuebingen/gesamt-pdf/jveg-zeugin-berger-lg-tuebingen_gesamt.pdf) | [`testakte-jveg-zeugin-berger-lg-tuebingen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-jveg-zeugin-berger-lg-tuebingen.zip) |
| **Akte LG Regensburg — Sieglinger gegen Burgwald Energietechnik GmbH** (`sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger`) | [Gesamt-PDF lesen](../testakten/sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger/gesamt-pdf/sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger_gesamt.pdf) | [`testakte-sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-sachverstaendigengutachten-ki-vorwurf-lg-regensburg-sieglinger.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Cowork-Plugin zur Prüfung von Kosten, Vorschüssen, Entschädigungen und Vergütungen nach dem Justizvergütungs- und -entschädigungsgesetz. Es ist auf echte Aktenarbeit zugeschnitten: Unterlagen strippen, Anspruchsart erkennen, JVEG-Positionen rechnen, Belege prüfen, Gerichtsschreiben angreifen oder bestätigen und am Ende ein belastbares Schreiben samt Rechenprotokoll erzeugen.

Die Beispielakte enthält den Fall der Zeugin Sophia Berger vor dem Landgericht Tübingen, Az. 7 O 118/23, mit Vorschussantrag, Gerichtsschreiben, anwaltlichem Schriftsatz und Word-Abschrift.

## Was das Plugin prüft

- Vorschuss nach § 3 JVEG
- Geltendmachung, Erlöschen, Wiedereinsetzung und Verjährung
- Fahrtkosten nach § 5 JVEG
- Tagegeld und Übernachtung nach § 6 JVEG
- sonstige notwendige Aufwendungen nach § 7 JVEG
- Zeugenentschädigung nach §§ 19 bis 22 JVEG
- Sachverständigen-, Dolmetscher- und Übersetzervergütung
- Kürzungs- und Wegfallrisiken nach § 8a JVEG
- Festsetzungs-, Beschwerde- und Ergänzungsschreiben

## Grundworkflow

1. Akte hochladen: Ladung, Antrag, Gerichtsschreiben, Belege, Rechnung oder Schriftsatz.
2. Rolle bestimmen: Zeuge, Sachverständiger, Dolmetscher, Übersetzer, Dritter oder ehrenamtlicher Richter.
3. Frist und Belehrung prüfen.
4. Jede Kostenposition mit Norm, Beleg und Rechenweg erfassen.
5. Kappungen und Doppelposten prüfen.
6. Beleglücken freundlich als Rückfragen ausgeben.
7. Rechenblatt, Prüfbericht und passendes Gerichtsschreiben erzeugen.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| jveg-kommandocenter | Startet die JVEG-Kostenprüfung, trennt Rolle, Anspruchsart, Frist, Belege, Rechenweg und gewünschten Output. |
| jveg-aktenstripper | Liest Gerichtsschreiben, Anträge, Rechnungen, Belege und Kostenfestsetzungsunterlagen in eine prüfbare JVEG-Datenmatrix aus. |
| jveg-anspruchsberechtigung | Kläert, ob Zeuge, Dritter, Sachverständiger, Dolmetscher, Übersetzer, Protokollperson oder ehrenamtlicher Richter betroffen ist. |
| jveg-fristen-erloeschen | Prüft Geltendmachung, Drei-Monats-Frist, Belehrung, Wiedereinsetzung, Verjährung und sichere Fristennotizen. |
| jveg-vorschuss | Prüft Vorschussanträge nach § 3 JVEG mit Schwerpunkt erhebliche Fahrtkosten, Übernachtung und Teilleistungen. |
| jveg-zeugenentschaedigung | Rechnet und plausibilisiert Zeugenentschädigung nach §§ 19 bis 22 JVEG. |
| jveg-fahrtkosten | Prüft Bahn, Flug, eigenes Kfz, Kilometerpauschale, Parkkosten, Auslandsanreise und Wirtschaftlichkeit. |
| jveg-uebernachtung-aufwand | Prüft Tagegeld, notwendige Übernachtung, BRKG-Anknüpfung, Belege und gerichtliche Obergrenzen. |
| jveg-verdienstausfall-haushalt-zeit | Trennt Verdienstausfall, Haushaltsführungsnachteile und Zeitversäumnis, damit keine Doppelberechnung entsteht. |
| jveg-sonstige-aufwendungen-belege | Prüft sonstige notwendige bare Auslagen, Begleitpersonen, Vertretung, Kopien, Dateien und Belegfähigkeit. |
| jveg-sachverstaendigenrechnung | Prüft Sachverständigenvergütung: Honorargruppe, erforderliche Zeit, Reisezeit, Nebenkosten, § 8a-Risiken und Vorschussüberlauf. |
| jveg-dolmetscher-uebersetzer | Prüft Dolmetscher- und Übersetzervergütung, Stundensatz, Zeilen-/Textumfang, Reisezeiten und Sprach-/Terminlogik. |
| jveg-kuerzung-wegfall-8a | Findet Kürzungs- und Wegfallrisiken: Verwertbarkeit, Hinweisobliegenheit, Befangenheit, Vorschussüberschreitung und Mängel. |
| jveg-gerichtsschreiben-pruefung | Prüft Gerichtsschreiben und Kostenbeamtenargumente auf Tatbestandsfehler, Ermessensfehler, Beleganforderungen und Antwortbedarf. |
| jveg-rechenblatt | Erstellt ein prüfbares Rechenblatt mit Norm, Eingabewert, Kappung, Beleg, Rechenschritt und Ergebnis. |
| jveg-antragsgenerator | Erzeugt Vorschuss-, Nachzahlungs-, Festsetzungs- und Ergänzungsschreiben mit Anlagen- und Belegliste. |
| jveg-festsetzung-beschwerde | Führt durch gerichtliche Festsetzung, Erinnerung/Beschwerdeprüfung, Beschwer, Frist und knappe Angriffsmittel. |
| jveg-quality-gate | Letzte Prüfung vor Versand: Normstand, Mathematik, Belege, keine Doppelposten, Fristen, Ton und eindeutiger Antrag. |

## Beispiel Berger

Die Beispielakte bildet einen realistisch aussehenden Vorschussstreit ab: Barcelona nach Tübingen, 2.500 km Hin- und Rückfahrt, zwei Übernachtungen, geltend gemachter Verdienstausfall und gerichtliche Ablehnung des Vorschusses wegen angeblich fehlender Bedürftigkeit. Das Plugin markiert insbesondere, dass § 3 JVEG bei erheblichen Fahrtkosten und sonstigen Aufwendungen ansetzt und die Kostenpositionen getrennt nach Erstattungsfähigkeit, Vorschussfähigkeit und Belegstatus geprüft werden müssen.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `beschwerde-dolmetscher-sonderfall` | Nutze dies bei Beschwerde Internationaler Bezug Und Schnittstellen, Dolmetscher Sonderfall Und Edge Case, Dolmetscherkosten Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `fahrtkosten-festsetzung-interessen` | Nutze dies bei Fahrtkosten Behörden Gericht Und Registerweg, Festsetzung Mehrparteien Konflikt Und Interessen, Freistehender Erstpruefung Und Mandatsziel: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `gate-beweislast-jveg-quality` | Nutze dies bei Gate Beweislast Und Darlegungslast, Jveg Tatbestand Beweis Und Belege, Quality Mandantenkommunikation Entscheidungsvorlage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächst... |
| `jveg` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Jveg Fristen Erloeschen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `jveg-anspruchsberechtigung-antragsgenerator` | Nutze dies bei Jveg Anspruchsberechtigung, Jveg Antragsgenerator, Jveg Dolmetscher Uebersetzer: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `jveg-dolmetscher-uebersetzer-fahrtkosten` | Nutze dies bei Jveg Dolmetscher Uebersetzer Spezial, Jveg Fahrtkosten, Jveg Festsetzung Beschwerde: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `jveg-gate-rechenblatt` | Nutze dies bei Jveg Quality Gate, Jveg Rechenblatt, Jveg Sachverstaendigenrechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `jveg-gerichtsschreiben-jveg-kuerzung-wegfall` | Nutze dies bei Jveg Gerichtsschreiben Prüfung, Jveg Kommandocenter, Jveg Kuerzung Wegfall 8a: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `jveg-sonstige-aufwendungen-uebernachtung` | Nutze dies bei Jveg Sonstige Aufwendungen Belege, Jveg Uebernachtung Aufwand, Jveg Verdienstausfall Haushalt Zeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitssc... |
| `jveg-vorschuss-kostenrisiko` | Nutze dies bei Jveg Vorschuss, Jveg Vorschuss Kostenrisiko Spezial, Jveg Zeugenentschaedigung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `jveg-zeugenentschaedigung` | Nutze dies bei Jveg Zeugenentschaedigung Checkliste, Prüfung Sachverstaendigengutachten Ki Deklaration, Belegfeste Formular Portal Und Einreichung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `kostenfestsetzung-kostenpruefer` | Nutze dies bei Fristen Compliance Dokumentation Und Akte, Kostenfestsetzung Belege Und Fristen, Kostenpruefer Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nä... |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rechenprotokolle-fehlerkatalog` | Nutze dies als Fehlerbremse bei Rechenprotokolle Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `sachverstaendigen-quellenkarte` | Nutze dies zur Quellenprüfung bei Sachverstaendigen Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `uebernachtung-verdienstausfall-vorschuss` | Nutze dies bei Uebernachtung Schriftsatz Brief Und Memo Bausteine, Verdienstausfall Verhandlung Vergleich Und Eskalation, Vorschuss Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpf... |
| `uebersetzer-fristennotiz-jveg` | Nutze dies bei Uebersetzer Fristennotiz Und Naechster Schritt, Jveg Sachverstaendigenrechnung Bauleiter, Jveg Aktenstripper: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `zeugenentschaedigung` | Nutze dies bei Zeugenentschaedigung Dokumentenmatrix Und Lueckenliste: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
