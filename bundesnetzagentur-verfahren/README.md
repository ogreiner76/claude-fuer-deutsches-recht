# Bundesnetzagentur-Verfahren

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`bundesnetzagentur-verfahren`) | [`bundesnetzagentur-verfahren.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/bundesnetzagentur-verfahren.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Märkische Reserve Süd — Batteriespeicher Brandenburg/Berlin** (`batteriespeicher-brandenburg-berlin-resilienz`) | [Gesamt-PDF lesen](../testakten/batteriespeicher-brandenburg-berlin-resilienz/gesamt-pdf/batteriespeicher-brandenburg-berlin-resilienz_gesamt.pdf) | [`testakte-batteriespeicher-brandenburg-berlin-resilienz.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-batteriespeicher-brandenburg-berlin-resilienz.zip) |
| **Projekt Isarlicht — Kernfusion und Transrapid am Starnberger See** (`kernfusion-transrapid-starnberger-see`) | [Gesamt-PDF lesen](../testakten/kernfusion-transrapid-starnberger-see/gesamt-pdf/kernfusion-transrapid-starnberger-see_gesamt.pdf) | [`testakte-kernfusion-transrapid-starnberger-see.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kernfusion-transrapid-starnberger-see.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Großes Regulierungs-Plugin für anwaltliche Arbeit mit der Bundesnetzagentur in Energie, Telekommunikation, Post, Eisenbahn und Digital Services.

## Wofür dieses Plugin da ist
Anwaltliche Verfahren mit der Bundesnetzagentur: Zuständigkeit, Beschlusskammern, Konsultationen, Auskünfte, Bußgelder, Beschwerden, Energie-, TK-, Post-, Eisenbahn- und DSA-Regulierung.

Das Plugin ist als Arbeitswerkzeug gedacht: Es startet mit einem Kaltstart-Interview, sortiert Unterlagen, prüft Fristen und routet dann in Spezial-Skills. Es soll Anfänger an die Hand nehmen und Profis schnell zu belastbaren Outputs bringen.

## Typischer Workflow
1. **Allgemein-Skill starten:** Rolle, Ziel, Frist, Unterlagen und gewünschtes Ergebnis klären.
2. **Dokumente einlesen:** Verträge, Bescheide, Rechnungen, Tabellen, Registerdaten, Behördenpost oder Screenshots strukturieren.
3. **Spezial-Skill wählen:** Das Plugin schlägt den passenden Skill vor und erklärt, welches Ergebnis damit entsteht.
4. **Live-Quellen prüfen:** Normtext, Behördenseite, EU-Text, Formular oder frei zugängliche Rechtsprechung aktualisieren.
5. **Output erzeugen:** Memo, Antrag, Stellungnahme, Vertragsklausel, Berechnung, Checkliste oder Mandantenbrief.
6. **Red-Team:** Fristen, Zuständigkeit, Zahlen, Quellen und Gegenargumente kontrollieren.

## Quellenanker
- Amtliche Gesetzestexte: gesetze-im-internet.de.
- EU-Recht: EUR-Lex und amtliche Kommissionsseiten.
- Behördenpraxis: zuständige Bundes-/Landesbehörden, Bundesnetzagentur, BaFin, BfArM, G-BA, BKartA oder Länderstellen je nach Thema.
- Rechtsprechung nur mit Gericht, Datum, Aktenzeichen und frei/amtlich prüfbarer Quelle.

## Skill-Schwerpunkte
| Gruppe | Inhalt |
| --- | --- |
| Einstieg und Workflow | Kaltstart, Dokumentenintake, Fristen, Quellencheck, Output-Wahl, Red-Team |
| Materielle Prüfung | Tatbestände, Ausnahmen, Schwellen, Beweislast, Berechnungen, Rechtsfolgen |
| Verfahren und Kommunikation | Anträge, Anhörungen, Beschwerden, Schriftsätze, Behördenkontakt, Mandantenkommunikation |
| Spezialthemen | Branchen-, Vertrags-, Gebühren-, Aufsichts-, EU- und Edge-Case-Prüfungen |

## Quellen- und Halluzinationsschutz
Dieses Plugin soll keine nicht prüfbaren Fundstellen produzieren. Bei unsicherer oder dynamischer Rechtslage wird der Live-Quellencheck ausdrücklich vorgeschaltet.

## Lizenz
Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 32 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Einstieg, Schnelltriage und Workflow-Routing im Bundesnetzagentur-Verfahren-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, erkennt stumme Uploads und schlägt passende Spezial-Skills aus diesem Plugin vor. |
| `anhoerung-auskunftsbeschluss-digital-services` | Nutze dies, wenn Anhoerung Auskunftsbeschluss Fristenplan, Digital Services Melde Und Abhilfeverfahren Notice And Action, Eilverfahren Verwaltungsgericht Strategie, Energie Regulierungsakte Bbplg Leitungsvorhaben Fristen Und Besc im Plug... |
| `digital-services-algorithmen` | Nutze dies, wenn Digital Services Algorithmen Empfehlungssysteme Dsa, Digital Services Aussergerichtliche Streitbeilegungsstelle Dsa, Digital Services Dark Patterns Dsa Schnittstelle, Digital Services Datenzugang Forscher Dsa, Digital Se... |
| `eilrechtsschutz-vwgo-festlegungsverfahren` | Nutze dies, wenn Verfahren Eilrechtsschutz 80 Vwgo, Verfahren Festlegungsverfahren Beschlusskammer, Verfahren Gebühren Kosten Bnetza, Verfahren Geschaeftsgeheimnisse Im Verwaltungsverfahren, Verfahren Konsultationsverfahren Stellungnahme... |
| `eisenbahn-digital-services-trusted-flagger` | Nutze dies, wenn Digital Services Transparenzberichte Online Plattformen, Digital Services Trusted Flagger Anerkennung, Digital Services Vlop Vlose Koordination Eu Kommission, Eisenbahn Anreizsetzung Schiene, Eisenbahn Baumassnahmen Und... |
| `eisenbahn-kapazitaetskonflikt-fahrplan` | Nutze dies, wenn Eisenbahn Kapazitaetskonflikt Fahrplan, Eisenbahn Netznutzungsbedingungen, Eisenbahn Regulierungsvereinbarung Db Netz Infrago, Eisenbahn Serviceeinrichtungen, Eisenbahn Stationszugang und 3 weitere Themen im Plugin Bunde... |
| `energie-bbplg-leitungsvorhaben-bilanzkreis` | Nutze dies, wenn Energie Bbplg Leitungsvorhaben, Energie Bilanzkreis Gas, Energie Bilanzkreis Strom, Energie Eeg Netzanschluss Einspeisemanagement, Energie Energieverbraucher Beschwerde und 3 weitere Themen im Plugin Bundesnetzagentur Ve... |
| `energie-kapazitaetsvergabe-gas-kwkg` | Nutze dies, wenn Energie Kapazitaetsvergabe Gas, Energie Kwkg Zuschlaege, Energie Ladesaeulen Elektromobilitaet, Energie Lieferantenwechsel Energie, Energie Messstellenbetrieb Msbg Smart Meter und 3 weitere Themen im Plugin Bundesnetzage... |
| `energie-netzentgelte-gas-strom-offshore` | Nutze dies, wenn Energie Netzentgelte Gas, Energie Netzentgelte Strom, Energie Offshore Netzanbindung, Energie Redispatch 2 0, Energie Regelenergie und 3 weitere Themen im Plugin Bundesnetzagentur Verfahren konkret bearbeitet werden soll... |
| `energie-regulierungsakte-anreizregulierung` | Nutze dies, wenn Energie Regulierungsakte Anreizregulierung Erloesobergrenze Unte, Energie Regulierungsakte Bbplg Leitungsvorhaben Rechtsmittel Che, Energie Regulierungsakte Bbplg Leitungsvorhaben Stellungnahme En, Energie Regulierungsak... |
| `energie-regulierungsakte-bilanzkreis-strom` | Nutze dies, wenn Energie Regulierungsakte Bilanzkreis Gas Fristen Und Bescheidana, Energie Regulierungsakte Bilanzkreis Strom Fristen Und Bescheida, Energie Regulierungsakte Grosshandelsdaten Transparenz Fristen U, Energie Regulierungsak... |
| `energie-regulierungsakte-eeg-netzanschluss` | Nutze dies, wenn Energie Regulierungsakte Eeg Netzanschluss Einspeisemanagement F, Energie Regulierungsakte Eeg Netzanschluss Einspeisemanagement R, Energie Regulierungsakte Eeg Netzanschluss Einspeisemanagement S, Energie Regulierungsak... |
| `energie-regulierungsakte-kapazitaetsvergabe` | Nutze dies, wenn Energie Regulierungsakte Kapazitaetsvergabe Gas Stellungnahme En, Energie Regulierungsakte Kapazitaetsvergabe Gas Unterlagenanford, Energie Regulierungsakte Kwkg Zuschlaege Rechtsmittel Check, Energie Regulierungsakte Kw... |
| `energie-regulierungsakte-kwkg-ladesaeulen` | Nutze dies, wenn Energie Regulierungsakte Kwkg Zuschlaege Fristen Und Bescheidana, Energie Regulierungsakte Ladesaeulen Elektromobilitaet Fristen U, Energie Regulierungsakte Nabeg Planfeststellung Fristen Und Besc, Energie Regulierungsak... |
| `energie-regulierungsakte-messstellenbetrieb` | Nutze dies, wenn Energie Regulierungsakte Messstellenbetrieb Msbg Smart Meter Rec, Energie Regulierungsakte Messstellenbetrieb Msbg Smart Meter Ste, Energie Regulierungsakte Messstellenbetrieb Msbg Smart Meter Unt, Energie Regulierungsak... |
| `energie-regulierungsakte-netzanschluss-strom` | Nutze dies, wenn Energie Regulierungsakte Netzanschluss Strom Rechtsmittel Check, Energie Regulierungsakte Netzanschluss Strom Stellungnahme Entwu, Energie Regulierungsakte Netzanschluss Strom Unterlagenanforderu, Energie Regulierungsakt... |
| `energie-regulierungsakte-offshore` | Nutze dies, wenn Energie Regulierungsakte Offshore Netzanbindung Rechtsmittel Che, Energie Regulierungsakte Offshore Netzanbindung Stellungnahme En, Energie Regulierungsakte Offshore Netzanbindung Unterlagenanford, Energie Regulierungsak... |
| `energie-regulierungsakte-redispatch` | Nutze dies, wenn Energie Regulierungsakte Redispatch 2 0 Fristen Und Bescheidanal, Energie Regulierungsakte Regelenergie Fristen Und Bescheidanalys, Energie Regulierungsakte Remit Marktmissbrauch Energie Fristen U, Energie Regulierungsak... |
| `energie-regulierungsakte-remit` | Nutze dies, wenn Energie Regulierungsakte Remit Marktmissbrauch Energie Stellungn, Energie Regulierungsakte Remit Marktmissbrauch Energie Unterlage, Energie Regulierungsakte Unbundling Entflechtung Rechtsmittel Ch, Energie Regulierungsak... |
| `energie-regulierungsakte-tk` | Nutze dies, wenn Energie Regulierungsakte Redispatch 2 0 Stellungnahme Entwurf, Energie Regulierungsakte Regelenergie Stellungnahme Entwurf, Tk Regulierungsakte Frequenzauktion Stellungnahme Entwurf, Tk Regulierungsakte Frequenzzuteilung... |
| `energie-regulierungsakte-wasserstoffnetz` | Nutze dies, wenn Energie Regulierungsakte Wasserstoffnetz Regulierung Rechtsmitte, Energie Regulierungsakte Wasserstoffnetz Regulierung Stellungnah, Energie Regulierungsakte Wasserstoffnetz Regulierung Unterlagena, Energie Remit Marktmis... |
| `kaltstart-bundesnetzagentur-mandat` | Workflow zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Kaltstart Bundesnetzagentur-Mandat. |
| `post-arbeitsbedingungen-postmarkt-beschwerde` | Nutze dies, wenn Post Arbeitsbedingungen Postmarkt Schnittstelle, Post Beschwerde Brief Paket, Post Grenzueberschreitende Paketzustellung, Post Laufzeitmessung Qualitaet, Post Paketdienst Verbraucherrechte und 3 weitere Themen im Plugin... |
| `post-postlizenz-anzeige-postmarktregulierung` | Nutze dies, wenn Post Postlizenz Anzeige, Post Postmarktregulierung, Post Postuniversaldienst, Post Zugang Postfachanlage, Stellungnahme Und Compliance Aktionsplan und 3 weitere Themen im Plugin Bundesnetzagentur Verfahren konkret bearbe... |
| `telekommunikation-frequenzauktion` | Nutze dies, wenn Telekommunikation Frequenzauktion, Telekommunikation Frequenzzuteilung, Telekommunikation Glasfaserausbau Mitnutzung, Telekommunikation Inhouse Verkabelung Gebaeudenetze, Telekommunikation Mehrwertdienste Preisansage und... |
| `telekommunikation-nummernverwaltung` | Nutze dies, wenn Telekommunikation Nummernverwaltung, Telekommunikation Providerwechsel Minderungsrecht, Telekommunikation Roaming Eu Schnittstelle, Telekommunikation Routerfreiheit Endgeraete, Telekommunikation Rufnummernmissbrauch und... |
| `telekommunikation-stoerung-telekommunikation` | Nutze dies, wenn Telekommunikation Stoerung Entstoerung Verbraucherrechte, Telekommunikation Telekommunikationsgeheimnis, Telekommunikation Tk Verbraucherschlichtung, Telekommunikation Tkg Marktregulierung Betraechtliche Marktmacht, Tele... |
| `tk-regulierungsakte-frequenzauktion` | Nutze dies, wenn Tk Regulierungsakte Frequenzauktion Unterlagenanforderung, Tk Regulierungsakte Frequenzzuteilung Rechtsmittel Check, Tk Regulierungsakte Frequenzzuteilung Unterlagenanforderung, Tk Regulierungsakte Nummernverwaltung Rech... |
| `tk-regulierungsakte-tk-akteneinsicht` | Nutze dies, wenn Tk Regulierungsakte Nummernverwaltung Fristen Und Bescheidanalys, Tk Regulierungsakte Rufnummernmissbrauch Fristen Und Bescheidana, Verfahren Akteneinsicht Drittbeteiligte, Verfahren Auskunftsersuchen Bnetza Beantworten,... |
| `tk-regulierungsakte-tk-aktenzugang` | Nutze dies, wenn Tk Regulierungsakte Nummernverwaltung Stellungnahme Entwurf, Tk Regulierungsakte Rufnummernmissbrauch Stellungnahme Entwurf, Aktenzugang Geschaeftsgeheimnisse Schwaerzung, Beschwerde Verbraucher Unternehmen Verband im Pl... |
| `tk-regulierungsakte-tkg-marktregulierung` | Nutze dies, wenn Tk Regulierungsakte Tkg Marktregulierung Betraechtliche Marktm 3, Tk Regulierungsakte Tkg Marktregulierung Betraechtliche Marktm 4, Tk Regulierungsakte Tkg Marktregulierung Betraechtliche Marktmac im Plugin Bundesnetzage... |
| `vorstandsvorlage-regulierungsrisiko` | Nutze dies, wenn Verfahren Vorstandsvorlage Regulierungsrisiko, Verfahren Widerspruch Klage Verwaltungsgericht, Zustaendigkeitsradar Energie Telekom Post Eisenbahn Digitales, Energie Regulierungsakte Bilanzkreis Gas Stellungnahme Entwurf... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
