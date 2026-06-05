# Straßenverkehrsrecht StVO

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strassenverkehrsrecht-stvo`) | [`strassenverkehrsrecht-stvo.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strassenverkehrsrecht-stvo.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **StVO-Akte Schulstraße/Lieferzone** (`strassenverkehrsrecht-stvo-schulstrasse-lieferzone`) | [Gesamt-PDF lesen](../testakten/strassenverkehrsrecht-stvo-schulstrasse-lieferzone/gesamt-pdf/strassenverkehrsrecht-stvo-schulstrasse-lieferzone_gesamt.pdf) | [`testakte-strassenverkehrsrecht-stvo-schulstrasse-lieferzone.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-strassenverkehrsrecht-stvo-schulstrasse-lieferzone.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin erklärt und prüft das Verhalten im Straßenverkehr und die behördliche Verkehrssteuerung: StVO, StVG, FeV, Zeichen, Anordnungen, Sondernutzungsschnittstellen, Ausnahmegenehmigung und Rechtsschutz.

## Start

Beginne mit `allgemein`. Das Plugin fragt zuerst nach Rolle, Ziel, Frist, Behörde/Gericht/Register, vorhandenen Unterlagen und gewünschtem Output. Danach schlägt es die passenden Spezialskills aus diesem Plugin vor.

## Arbeitsweise

- Es arbeitet mit Akten- und Fristenlogik statt mit Bauchgefühl.
- Es trennt Rechtsgrundlage, Verfahren, Beweis, Kosten, Kommunikation und Eskalation.
- Es soll Nutzerinnen und Nutzer befähigen: verständliche Erklärung, präzise Rückfragen, dann belastbarer Entwurf.
- Rechtsprechung und Gesetzesstände werden nicht halluziniert, sondern als Live-Check über amtliche oder frei zugängliche Quellen markiert.

## Typische Outputs

- Kaltstart-Interview und Aktenlandkarte
- Behörden-, Gerichts- oder Gegneranschreiben
- Widerspruchs-/Klage-/Eilantragsbausteine
- Kosten-, Fristen- und Zuständigkeitsmatrix
- Dashboard/Tracker für laufende Vorgänge
- Kurzfassung für Mandant, Vorstand, Verband, Redaktion oder Bürgerin

## Quellenhygiene

Siehe [`references/QUELLEN.md`](./references/QUELLEN.md). Dieses Plugin gibt keine endgültige Rechtsberatung, sondern robuste Arbeitsfassungen, Prüfpfade und Dokumentationshilfen.

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 27 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Straßenverkehrsrecht StVO: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |
| `stv-001-kaltstart-stvo-fall` | Straßenverkehrsrecht StVO: Kaltstart StVO-Fall. Kaltstart StVO-Fall im Fachgebiet Straßenverkehrsrecht StVO als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `stv-bewohnerparken-eilrechtsschutz-behoerde` | Nutze dies bei Stv 067 Bewohnerparken Eilrechtsschutz Planen, Stv 068 Bewohnerparken Behörde Anschreiben, Stv 069 Bewohnerparken Karte Bauen, Stv 070 Bewohnerparken Risiko Erklaeren: führt durch diese fachlich verbundenen Module, wählt d... |
| `stv-bewohnerparken-zeichen-anordnung` | Nutze dies bei Stv 062 Bewohnerparken Zeichen Auslegen, Stv 063 Bewohnerparken Anordnung Angreifen, Stv 064 Bewohnerparken Antrag Schreiben, Stv 065 Bewohnerparken Beweis Sichern: führt durch diese fachlich verbundenen Module, wählt den... |
| `stv-bussgeldschnittstelle-stv-haltverbot-stv` | Nutze dies bei Stv 017 Bussgeldschnittstelle Owig, Stv 026 Haltverbot Bussgeld Abgrenzen, Stv 036 Tempo 30 Bussgeld Abgrenzen, Stv 046 Fahrradstrasse Bussgeld Abgrenzen: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `stv-busspur-anordnung-antrag-schreiben` | Nutze dies bei Stv 053 Busspur Anordnung Angreifen, Stv 054 Busspur Antrag Schreiben, Stv 055 Busspur Beweis Sichern, Stv 057 Busspur Eilrechtsschutz Planen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `stv-busspur-behoerde-karte-bauen-risiko` | Nutze dies bei Stv 058 Busspur Behörde Anschreiben, Stv 059 Busspur Karte Bauen, Stv 060 Busspur Risiko Erklaeren, Stv 061 Bewohnerparken Regel Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `stv-busspur-stv-bewohnerparken-stv-lieferzone` | Nutze dies bei Stv 056 Busspur Bussgeld Abgrenzen, Stv 066 Bewohnerparken Bussgeld Abgrenzen, Stv 076 Lieferzone Bussgeld Abgrenzen, Stv 086 Ladezone Bussgeld Abgrenzen: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `stv-fahrradstrasse-antrag-sichern` | Nutze dies bei Stv 044 Fahrradstrasse Antrag Schreiben, Stv 045 Fahrradstrasse Beweis Sichern, Stv 047 Fahrradstrasse Eilrechtsschutz Planen, Stv 048 Fahrradstrasse Behörde Anschreiben: führt durch diese fachlich verbundenen Module, wähl... |
| `stv-fahrradstrasse-karte-risiko-erklaeren` | Nutze dies bei Stv 049 Fahrradstrasse Karte Bauen, Stv 050 Fahrradstrasse Risiko Erklaeren, Stv 051 Busspur Regel Prüfen, Stv 052 Busspur Zeichen Auslegen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und l... |
| `stv-gefahrenstelle-melden-schulweg` | Nutze dies bei Stv 013 Gefahrenstelle Melden, Stv 014 Schulweg Und Verkehrsberuhigung, Stv 015 Baustellenverkehrsrecht, Stv 016 Blaulicht Und Sonderrechte: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und l... |
| `stv-haltverbot-eilrechtsschutz-behoerde` | Nutze dies bei Stv 027 Haltverbot Eilrechtsschutz Planen, Stv 028 Haltverbot Behörde Anschreiben, Stv 029 Haltverbot Karte Bauen, Stv 030 Haltverbot Risiko Erklaeren: führt durch diese fachlich verbundenen Module, wählt den passenden Prü... |
| `stv-haltverbot-zeichen-anordnung-angreifen` | Nutze dies bei Stv 022 Haltverbot Zeichen Auslegen, Stv 023 Haltverbot Anordnung Angreifen, Stv 024 Haltverbot Antrag Schreiben, Stv 025 Haltverbot Beweis Sichern: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpf... |
| `stv-ladezone-antrag-sichern-eilrechtsschutz` | Nutze dies bei Stv 084 Ladezone Antrag Schreiben, Stv 085 Ladezone Beweis Sichern, Stv 087 Ladezone Eilrechtsschutz Planen, Stv 088 Ladezone Behörde Anschreiben: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `stv-ladezone-karte-risiko-erklaeren` | Nutze dies bei Stv 089 Ladezone Karte Bauen, Stv 090 Ladezone Risiko Erklaeren, Stv 091 Schulstrasse Regel Prüfen, Stv 092 Schulstrasse Zeichen Auslegen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `stv-lieferzone-regel-zeichen-auslegen` | Nutze dies bei Stv 071 Lieferzone Regel Prüfen, Stv 072 Lieferzone Zeichen Auslegen, Stv 073 Lieferzone Anordnung Angreifen, Stv 074 Lieferzone Antrag Schreiben: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `stv-lieferzone-risiko-ladezone-regel-zeichen` | Nutze dies bei Stv 080 Lieferzone Risiko Erklaeren, Stv 081 Ladezone Regel Prüfen, Stv 082 Ladezone Zeichen Auslegen, Stv 083 Ladezone Anordnung Angreifen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und l... |
| `stv-lieferzone-sichern-eilrechtsschutz-planen` | Nutze dies bei Stv 075 Lieferzone Beweis Sichern, Stv 077 Lieferzone Eilrechtsschutz Planen, Stv 078 Lieferzone Behörde Anschreiben, Stv 079 Lieferzone Karte Bauen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfp... |
| `stv-parken-stv-ausnahmegenehmigung-stv` | Nutze dies bei Stv 005 Parken Halten Abschleppen, Stv 006 Ausnahmegenehmigung Beantragen, Stv 007 Radverkehr Und Schutzstreifen, Stv 008 E Scooter Und Mikromobilitaet: führt durch diese fachlich verbundenen Module, wählt den passenden Pr... |
| `stv-schulstrasse-anordnung-antrag-schreiben` | Nutze dies bei Stv 093 Schulstrasse Anordnung Angreifen, Stv 094 Schulstrasse Antrag Schreiben, Stv 095 Schulstrasse Beweis Sichern, Stv 097 Schulstrasse Eilrechtsschutz Planen: führt durch diese fachlich verbundenen Module, wählt den pa... |
| `stv-schulstrasse-bussgeld-verkehrszeichen` | Nutze dies bei Stv 096 Schulstrasse Bussgeld Abgrenzen, Stv 002 Verkehrszeichen Lesen, Stv 003 Verkehrsrechtliche Anordnung Prüfen, Stv 004 Tempozone Und Beschilderung: führt durch diese fachlich verbundenen Module, wählt den passenden P... |
| `stv-schulstrasse-stv-schulstrasse` | Nutze dies bei Stv 098 Schulstrasse Behörde Anschreiben, Stv 099 Schulstrasse Karte Bauen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `stv-schwertransport-stv-fahrerlaubnis-stv-mpu` | Nutze dies bei Stv 009 Schwertransport Und Erlaubnis, Stv 010 Fahrerlaubnis Schnittstelle, Stv 011 Mpu Und Fahreignung, Stv 012 Fahrtenbuchauflage: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert d... |
| `stv-tempo-regel-zeichen-auslegen-anordnung` | Nutze dies bei Stv 031 Tempo 30 Regel Prüfen, Stv 032 Tempo 30 Zeichen Auslegen, Stv 033 Tempo 30 Anordnung Angreifen, Stv 034 Tempo 30 Antrag Schreiben: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `stv-tempo-sichern-eilrechtsschutz-planen` | Nutze dies bei Stv 035 Tempo 30 Beweis Sichern, Stv 037 Tempo 30 Eilrechtsschutz Planen, Stv 038 Tempo 30 Behörde Anschreiben, Stv 039 Tempo 30 Karte Bauen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `stv-tempo-stv-fahrradstrasse-stv-stv` | Nutze dies bei Stv 040 Tempo 30 Risiko Erklaeren, Stv 041 Fahrradstrasse Regel Prüfen, Stv 042 Fahrradstrasse Zeichen Auslegen, Stv 043 Fahrradstrasse Anordnung Angreifen: führt durch diese fachlich verbundenen Module, wählt den passende... |
| `stv-widerspruch-stv-eilrechtsschutz-stv` | Nutze dies bei Stv 018 Widerspruch Gegen Verkehrszeichen, Stv 019 Eilrechtsschutz Verkehrszeichen, Stv 020 Kommunikation Mit Strassenverkehrsbeho, Stv 021 Haltverbot Regel Prüfen: führt durch diese fachlich verbundenen Module, wählt den... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
