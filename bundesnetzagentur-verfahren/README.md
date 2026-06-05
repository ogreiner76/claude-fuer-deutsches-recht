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
| `anhoerung-auskunftsbeschluss-digital-services` | Anhoerung Auskunftsbeschluss Digital Services im Bundesnetzagentur-Verfahren: prüft konkret zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Anhörung Auskunf, Digital Services / Melde- und Abhilfeverfahren Notice and, Prio... |
| `bundesnetzagentur-verfahren-kaltstart-triage` | Einstieg, Schnelltriage und Fallrouting im Bundesnetzagentur-Verfahren-Plugin. Fragt Rolle, Ziel, Fristen, Unterlagen, Risiken und Wunsch-Output ab, erkennt stumme Uploads und schlägt passende Fachmodule aus diesem Plugin vor. |
| `digital-services-algorithmen` | Digital Services Algorithmen im Bundesnetzagentur-Verfahren: prüft konkret Digital Services / Algorithmen Empfehlungssysteme DSA, Digital Services / Außergerichtliche Streitbeilegungsstelle, Digital Services / Dark Patterns DSA Schnittst... |
| `eilrechtsschutz-vwgo-festlegungsverfahren` | Eilrechtsschutz Vwgo Festlegungsverfahren im Bundesnetzagentur-Verfahren: prüft konkret Verfahren / Eilrechtsschutz § 80 VwGO, Verfahren / Festlegungsverfahren Beschlusskammer, Verfahren / Gebühren Kosten BNetzA, Verfahren / Geschäftsgeh... |
| `eisenbahn-digital-services-trusted-flagger` | Eisenbahn Digital Services Trusted Flagger im Bundesnetzagentur-Verfahren: prüft konkret Digital Services / Transparenzberichte Online-Plattformen, Digital Services / Trusted Flagger Anerkennung, Digital Services / VLOP VLOSE Koordinatio... |
| `eisenbahn-kapazitaetskonflikt-fahrplan` | Eisenbahn Kapazitaetskonflikt Fahrplan im Bundesnetzagentur-Verfahren: prüft konkret Eisenbahn / Kapazitätskonflikt Fahrplan, Eisenbahn / Netznutzungsbedingungen, Eisenbahn / Regulierungsvereinbarung DB Netz InfraGO, Eisenbahn / Servicee... |
| `energie-bbplg-leitungsvorhaben-bilanzkreis` | Energie Bbplg Leitungsvorhaben Bilanzkreis im Bundesnetzagentur-Verfahren: prüft konkret Energie / BBPlG Leitungsvorhaben, Energie / Bilanzkreis Gas, Energie / Bilanzkreis Strom, Energie / EEG Netzanschluss Einspeisemanagement. Liefert p... |
| `energie-kapazitaetsvergabe-gas-kwkg` | Energie Kapazitaetsvergabe GAS Kwkg im Bundesnetzagentur-Verfahren: prüft konkret Energie / Kapazitätsvergabe Gas, Energie / KWKG Zuschläge, Energie / Ladesäulen Elektromobilität, Energie / Lieferantenwechsel Energie. Liefert priorisiert... |
| `energie-netzentgelte-gas-strom-offshore` | Energie Netzentgelte GAS Strom Offshore im Bundesnetzagentur-Verfahren: prüft konkret Energie / Netzentgelte Gas, Energie / Netzentgelte Strom, Energie / Offshore-Netzanbindung, Energie / Redispatch 2.0. Liefert priorisierten Output mit... |
| `energie-regulierungsakte-anreizregulierung` | Energie Regulierungsakte Anreizregulierung im Bundesnetzagentur-Verfahren: prüft konkret Anreizregulierung Erlösobergrenze, BBPlG Leitungsvorhaben. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `energie-regulierungsakte-bilanzkreis-strom` | Energie Regulierungsakte Bilanzkreis Strom im Bundesnetzagentur-Verfahren: prüft konkret Bilanzkreis Gas, Bilanzkreis Strom, Großhandelsdaten Transparenz, Kapazitätsvergabe Gas. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampe... |
| `energie-regulierungsakte-eeg-netzanschluss` | Energie Regulierungsakte EEG Netzanschluss im Bundesnetzagentur-Verfahren: prüft konkret EEG Netzanschluss Einspeisemanagement. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `energie-regulierungsakte-kapazitaetsvergabe` | Energie Regulierungsakte Kapazitaetsvergabe im Bundesnetzagentur-Verfahren: prüft konkret Kapazitätsvergabe Gas, KWKG Zuschläge. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `energie-regulierungsakte-kwkg-ladesaeulen` | Energie Regulierungsakte Kwkg Ladesaeulen im Bundesnetzagentur-Verfahren: prüft konkret KWKG Zuschläge, Ladesäulen Elektromobilität, NABEG Planfeststellung, Netzanschluss Gas. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel... |
| `energie-regulierungsakte-messstellenbetrieb` | Energie Regulierungsakte Messstellenbetrieb im Bundesnetzagentur-Verfahren: prüft konkret Messstellenbetrieb MsbG Smart Meter, NABEG Planfeststellung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `energie-regulierungsakte-netzanschluss-strom` | Energie Regulierungsakte Netzanschluss Strom im Bundesnetzagentur-Verfahren: prüft konkret Netzanschluss Strom, Netzentgelte Gas. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `energie-regulierungsakte-offshore` | Energie Regulierungsakte Offshore im Bundesnetzagentur-Verfahren: prüft konkret Offshore-Netzanbindung, Redispatch 2.0. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `energie-regulierungsakte-redispatch` | Energie Regulierungsakte Redispatch im Bundesnetzagentur-Verfahren: prüft konkret Redispatch 2.0, Regelenergie, REMIT Marktmissbrauch Energie, Unbundling Entflechtung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näch... |
| `energie-regulierungsakte-remit` | Energie Regulierungsakte Remit im Bundesnetzagentur-Verfahren: prüft konkret REMIT Marktmissbrauch Energie, Unbundling Entflechtung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `energie-regulierungsakte-tk` | Energie Regulierungsakte TK im Bundesnetzagentur-Verfahren: prüft konkret Redispatch 2.0, Regelenergie, Frequenzauktion, Frequenzzuteilung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `energie-regulierungsakte-wasserstoffnetz` | Energie Regulierungsakte Wasserstoffnetz im Bundesnetzagentur-Verfahren: prüft konkret Wasserstoffnetz Regulierung, Energie / REMIT Marktmissbrauch Energie. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `kaltstart-bundesnetzagentur-mandat` | Kaltstart Bundesnetzagentur-Mandat: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `post-arbeitsbedingungen-postmarkt-beschwerde` | Post Arbeitsbedingungen Postmarkt Beschwerde im Bundesnetzagentur-Verfahren: prüft konkret Post / Arbeitsbedingungen Postmarkt Schnittstelle, Post / Beschwerde Brief Paket, Post / Grenzüberschreitende Paketzustellung, Post / Laufzeitmess... |
| `post-postlizenz-anzeige-postmarktregulierung` | Post Postlizenz Anzeige Postmarktregulierung im Bundesnetzagentur-Verfahren: prüft konkret Post / Postlizenz Anzeige, Post / Postmarktregulierung, Post / Postuniversaldienst, Post / Zugang Postfachanlage. Liefert priorisierten Output mit... |
| `telekommunikation-frequenzauktion` | Telekommunikation Frequenzauktion im Bundesnetzagentur-Verfahren: prüft konkret Telekommunikation / Frequenzauktion, Telekommunikation / Frequenzzuteilung, Telekommunikation / Glasfaserausbau Mitnutzung, Telekommunikation / Inhouse-Verka... |
| `telekommunikation-nummernverwaltung` | Telekommunikation Nummernverwaltung im Bundesnetzagentur-Verfahren: prüft konkret Telekommunikation / Nummernverwaltung, Telekommunikation / Providerwechsel Minderungsrecht, Telekommunikation / Roaming EU Schnittstelle, Telekommunikation... |
| `telekommunikation-stoerung` | Telekommunikation Stoerung im Bundesnetzagentur-Verfahren: prüft konkret Telekommunikation / Störung Entstörung Verbraucherrechte, Telekommunikation / Telekommunikationsgeheimnis, Telekommunikation / TK-Verbraucherschlichtung, Telekommun... |
| `tk-regulierungsakte-frequenzauktion` | TK Regulierungsakte Frequenzauktion im Bundesnetzagentur-Verfahren: prüft konkret Frequenzauktion, Frequenzzuteilung, Nummernverwaltung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `tk-regulierungsakte-tk-akteneinsicht` | TK Regulierungsakte TK Akteneinsicht im Bundesnetzagentur-Verfahren: prüft konkret Nummernverwaltung, Rufnummernmissbrauch, Verfahren / Akteneinsicht Drittbeteiligte, Verfahren / Auskunftsersuchen BNetzA beantworten. Liefert priorisierte... |
| `tk-regulierungsakte-tk-aktenzugang` | TK Regulierungsakte TK Aktenzugang im Bundesnetzagentur-Verfahren: prüft konkret Nummernverwaltung, Rufnummernmissbrauch, zur strukturierten Aufnahme, Priorisierung und Ausgabe im Thema Aktenzugang Gesc. Liefert priorisierten Output mit... |
| `tk-regulierungsakte-tkg-marktregulierung` | TK Regulierungsakte TKG Marktregulierung im Bundesnetzagentur-Verfahren: prüft konkret TKG Marktregulierung beträchtliche Marktmacht. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `vorstandsvorlage-regulierungsrisiko` | Vorstandsvorlage Regulierungsrisiko im Bundesnetzagentur-Verfahren: prüft konkret Verfahren / Vorstandsvorlage Regulierungsrisiko, Verfahren / Widerspruch Klage Verwaltungsgericht, zur strukturierten Aufnahme, Priorisierung und Ausgabe i... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
