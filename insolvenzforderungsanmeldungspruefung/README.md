# Insolvenzforderungsanmeldungsprüfung

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`insolvenzforderungsanmeldungspruefung`) | [`insolvenzforderungsanmeldungspruefung.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/insolvenzforderungsanmeldungspruefung.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Insolvenzforderungsanmeldungsprüfung Phoenix Solar Montage GmbH** (`insolvenzforderungsanmeldungspruefung-phoenix-solar`) | [Gesamt-PDF lesen](../testakten/insolvenzforderungsanmeldungspruefung-phoenix-solar/gesamt-pdf/insolvenzforderungsanmeldungspruefung-phoenix-solar_gesamt.pdf) | [`testakte-insolvenzforderungsanmeldungspruefung-phoenix-solar.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-insolvenzforderungsanmeldungspruefung-phoenix-solar.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Freistehendes Cowork-Plugin für die Prüfung von Insolvenzforderungen vom Eingang bis zur Tabellenfeststellung. Es ist ein vollständiger Arbeitsraum für Verwalterbüro, Sachwaltung, Forderungsmanagement und Prozessnachlauf: Anmeldung erfassen, Mängel erkennen, Belege nachfordern, Grund, Betrag und Rang prüfen, Entscheidung dokumentieren, Tabelle befüllen, Prüfungstermin vorbereiten, Bestreiten oder Feststellung ausgeben und streitige Forderungen bis zur Verteilung nachhalten.

## Wofür das Plugin gedacht ist

- Masseneingang von Forderungsanmeldungen per Post, E-Mail, Portalexport, Tabellenliste oder manuellem Upload.
- Formale Prüfung nach § 174 InsO einschließlich Grund, Betrag, Urkunden, elektronischer Anmeldung, vbuH-/Unterhalts-/Steuerstraf-Hinweis und Nachrang.
- Materielle Plausibilisierung anhand Schuldnerbuchhaltung, OPOS, Verträgen, Titeln, Lieferscheinen, Kontoauszügen und bisherigem Verfahrensstand.
- Entscheidungsvorbereitung für Feststellung, Teilbestreiten, vollständiges Bestreiten, Nachforderung, Rangkorrektur, vbuH-Widerspruch und Masse-/Insolvenzforderung-Abgrenzung.
- Tabellenarbeit nach § 175 InsO, Prüfungstermin nach § 176 InsO, nachträgliche Anmeldung nach § 177 InsO, Feststellungswirkung nach § 178 InsO und Streitnachlauf nach §§ 179 bis 181, 184 und 189 InsO.

## Leitprinzip

Das Plugin arbeitet verzeihend, aber nicht schlampig. Es akzeptiert unsaubere Gläubigeranschreiben, unvollständige Belege, widersprüchliche Rechnungsnummern und doppelte Portaleingänge. Es zieht daraus aber nie automatisch eine Feststellung. Fehlende Substanz wird als Mangel, Risiko oder Rückfrage markiert. Jede Tabellenentscheidung bleibt nachvollziehbar: Was ist angemeldet, was ist belegt, was ist bestritten, warum, durch wen und mit welchem nächsten Schritt.

## Typischer Ablauf

1. Intake öffnen: Eingangsstapel, Metadaten, Gläubiger, Frist, Kanal, Dateinamen und Dublettenverdacht erfassen.
2. § 174-Check: Grund, Betrag, Rang, Belege, vbuH-Kennzeichnung und elektronische Form prüfen.
3. Belegkette bilden: Rechnung, Titel, Vertrag, Lieferung, Zahlung, Buchhaltung, offene Restforderung und Rang verbinden.
4. Prüfentscheidung treffen: feststellen, teilweise feststellen, bestreiten, vorläufig zurückstellen oder Nachforderung schreiben.
5. Tabelle füllen: Tabellenimport, Prüfvermerk, Widerspruchsvermerk und Prüfungsterminmappe erzeugen.
6. Nachlauf steuern: Tabellenauszug, Feststellungsklage, Schuldnerwiderspruch, § 189-Verteilung und Wiedervorlagen kontrollieren.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| ifap-kommandocenter | Startet den gesamten Prüfpfad und entscheidet, welcher Arbeitsmodus passt. |
| ifap-intake-kanalcheck | Erfasst Post, E-Mail, Portal, Stapel, Nachzügler und Metadaten. |
| ifap-aktenanlage-batchregister | Baut Register, Prüfnummern, Gläubigerstamm und Eingangsbuch auf. |
| ifap-formalpruefung-174 | Prüft die formalen Mindestangaben nach § 174 InsO. |
| ifap-beleg-und-urkundencheck | Bildet die Belegkette und erkennt fehlende Urkunden. |
| ifap-grund-betrag-zinsen | Prüft Anspruchsgrund, Betrag, Teilzahlungen und Zinslauf. |
| ifap-rang-nachrang-absonderung | Trennt Insolvenzforderung, Nachrang, Sicherheiten und Ausfall. |
| ifap-masseverbindlichkeit-abgrenzen | Erkennt falsch angemeldete Masseforderungen und Abgrenzungsfälle. |
| ifap-vbuh-pruefung | Prüft vbuH, Unterhalt und Steuerstraftat mit Tatsachenbasis. |
| ifap-dubletten-serienforderungen | Erkennt Mehrfachanmeldungen, Serienrechnungen und Vertreterwechsel. |
| ifap-nachforderung-maengelschreiben | Erstellt präzise Beleg- und Substanznachforderungen. |
| ifap-pruefentscheidung | Erstellt Feststellungs-, Teilbestreitens- und Bestreitensvermerke. |
| ifap-tabellenimport-175 | Baut einen gerichtsfesten Tabellenimport nach § 175 InsO. |
| ifap-pruefungstermin-176 | Bereitet Prüfungstermin oder schriftliches Verfahren vor. |
| ifap-nachtraegliche-anmeldung-177 | Steuert verspätete und geänderte Anmeldungen. |
| ifap-tabellenauszug-178 | Erzeugt Tabellenauszug- und Feststellungswirkungs-Ausgaben. |
| ifap-streitige-forderung-179-180 | Führt den Feststellungsklage- und Rechtsstreit-Nachlauf. |
| ifap-schuldnerwiderspruch-184 | Behandelt Schuldnerwiderspruch und Monatsfrist bei titulierten Forderungen. |
| ifap-verteilung-bestrittene-189 | Hält § 189-Nachweise und Rückbehalte für Verteilungen nach. |
| ifap-quality-gate | Prüft Vollständigkeit, Plausibilität, Quellen, Fristen und Audit-Trail. |

## Grenzen

Das Plugin trifft keine unüberprüfte Rechtsentscheidung und ersetzt keine fachliche Prüfung. Bei streitigen Rechtsfragen, Rechtskraft-/Titelthemen, vbuH, Rangverschiebungen, Absonderungsrechten, § 189-Rückbehalten und drohenden Feststellungsklagen verlangt es ausdrücklich menschliche Freigabe.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein-workflow-chronologie-fristen` | Nutze dies bei Allgemein, Chronologie Und Belegmatrix, Fristen Und Risikoampel, ...: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `anschluss-routing` | Nutze dies zum Einstieg in Anschluss-Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `bestreiten-interessen-betrag` | Nutze dies bei Belege Dokumentenmatrix Und Lueckenliste, Bestreiten Mehrparteien Konflikt Und Interessen, Betrag Behörden Gericht Und Registerweg: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert de... |
| `dokumente-intake` | Nutze dies für Unterlagen zu Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `einstieg-routing` | Nutze dies zum Einstieg in Einstieg und Routing: klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `feststellung-forderungsgrund-rang-grund` | Nutze dies bei Feststellung Internationaler Bezug Und Schnittstellen, Forderungsgrund Rang Und Belegpruefung, Grund Risikoampel Und Gegenargumente: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `iap-anmeldepruefung-bauleiter-aussonderung` | Nutze dies bei Iap Anmeldepruefung Bauleiter, Iap Aussonderung Absonderung Spezial, Iap Konzernforderungen Anfechtung Spezial: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbar... |
| `iap-rangordnung-ifap-aktenanlage-ifap-beleg` | Nutze dies bei Iap Rangordnung Checkliste, Ifap Aktenanlage Batchregister, Ifap Beleg Und Urkundencheck: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ifap-dubletten-serienforderungen` | Nutze dies bei Ifap Dubletten Serienforderungen, Ifap Formalpruefung 174, Ifap Grund Betrag Zinsen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ifap-insolvenzforderungsanmeldungspruefung` | Nutze dies bei Ifap Mandantenkommunikation Entscheidungsvorlage, Insolvenzforderungsanmeldungspruefung Erstpruefung, Intake Tatbestand Beweis Und Belege: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `ifap-intake-kanalcheck-masseverbindlichkeit` | Nutze dies bei Ifap Intake Kanalcheck, Ifap Masseverbindlichkeit Abgrenzen, Ifap Nachforderung Maengelschreiben: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschr... |
| `ifap-nachtraegliche-anmeldung-pruefungstermin` | Nutze dies bei Ifap Nachtraegliche Anmeldung 177, Ifap Pruefungstermin 176, Ifap Quality Gate: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ifap-pruefentscheidung-vbuh` | Nutze dies bei Ifap Kommandocenter, Ifap Pruefentscheidung, Ifap Vbuh Prüfung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ifap-rang-nachrang-schuldnerwiderspruch` | Nutze dies bei Ifap Rang Nachrang Absonderung, Ifap Schuldnerwiderspruch 184, Ifap Streitige Forderung 179 180: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ifap-tabellenauszug-tabellenimport-verteilung` | Nutze dies bei Ifap Tabellenauszug 178, Ifap Tabellenimport 175, Ifap Verteilung Bestrittene 189: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `inso` | Nutze dies bei Mandantenkommunikation, Redteam Qualitygate, Inso Fristen Form Und Zustaendigkeit: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `kanalcheck-beweislast-masseverbindlichkeit` | Nutze dies bei Kanalcheck Beweislast Und Darlegungslast, Masseverbindlichkeit Sonderfall Und Edge Case, Pruefungstermin Compliance Dokumentation Und Akte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `nachforderungen-quellenkarte` | Nutze dies zur Quellenprüfung bei Nachforderungen Quellenkarte: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `output-waehlen` | Nutze dies bei Output wählen: prüft die konkrete Fachfrage mit Normen, Belegen, Risiken, Gegenargumenten und einem verwertbaren Arbeitsergebnis. |
| `quellen-livecheck` | Nutze dies zur Quellenprüfung bei Rechtsquellen-Livecheck: Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rang-tabellenauszug-tabellenimport` | Nutze dies bei Rang Schriftsatz Brief Und Memo Bausteine, Tabellenauszug Formular Portal Und Einreichung, Tabellenimport Zahlen Schwellen Und Berechnung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `unterlagen-luecken` | Nutze dies für Unterlagen zu Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `vbuh` | Nutze dies bei Vbuh Verhandlung Vergleich Und Eskalation: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `verteilung-fehlerkatalog` | Nutze dies als Fehlerbremse bei Verteilung Fehlerkatalog: prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
