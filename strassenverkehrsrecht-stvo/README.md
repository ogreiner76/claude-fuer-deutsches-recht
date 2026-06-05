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
| `allgemein` | Straßenverkehrsrecht StVO: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `stv-001-kaltstart-stvo-fall` | Straßenverkehrsrecht StVO: Kaltstart StVO-Fall. Kaltstart StVO-Fall im Fachgebiet Straßenverkehrsrecht StVO als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `stv-bewohnerparken-eilrechtsschutz-behoerde` | Nutze dies, wenn Stv 067 Bewohnerparken Eilrechtsschutz Planen, Stv 068 Bewohnerparken Behörde Anschreiben, Stv 069 Bewohnerparken Karte Bauen, Stv 070 Bewohnerparken Risiko Erklaeren im Plugin Strassenverkehrsrecht Stvo konkret bearbeit... |
| `stv-bewohnerparken-zeichen-anordnung` | Nutze dies, wenn Stv 062 Bewohnerparken Zeichen Auslegen, Stv 063 Bewohnerparken Anordnung Angreifen, Stv 064 Bewohnerparken Antrag Schreiben, Stv 065 Bewohnerparken Beweis Sichern im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet... |
| `stv-bussgeldschnittstelle-stv-haltverbot-stv` | Nutze dies, wenn Stv 017 Bussgeldschnittstelle Owig, Stv 026 Haltverbot Bussgeld Abgrenzen, Stv 036 Tempo 30 Bussgeld Abgrenzen, Stv 046 Fahrradstrasse Bussgeld Abgrenzen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden sol... |
| `stv-busspur-anordnung-antrag-schreiben` | Nutze dies, wenn Stv 053 Busspur Anordnung Angreifen, Stv 054 Busspur Antrag Schreiben, Stv 055 Busspur Beweis Sichern, Stv 057 Busspur Eilrechtsschutz Planen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser:... |
| `stv-busspur-behoerde-karte-bauen-risiko` | Nutze dies, wenn Stv 058 Busspur Behörde Anschreiben, Stv 059 Busspur Karte Bauen, Stv 060 Busspur Risiko Erklaeren, Stv 061 Bewohnerparken Regel Prüfen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser: Bitte... |
| `stv-busspur-stv-bewohnerparken-stv-lieferzone` | Nutze dies, wenn Stv 056 Busspur Bussgeld Abgrenzen, Stv 066 Bewohnerparken Bussgeld Abgrenzen, Stv 076 Lieferzone Bussgeld Abgrenzen, Stv 086 Ladezone Bussgeld Abgrenzen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden sol... |
| `stv-fahrradstrasse-antrag-sichern` | Nutze dies, wenn Stv 044 Fahrradstrasse Antrag Schreiben, Stv 045 Fahrradstrasse Beweis Sichern, Stv 047 Fahrradstrasse Eilrechtsschutz Planen, Stv 048 Fahrradstrasse Behörde Anschreiben im Plugin Strassenverkehrsrecht Stvo konkret bearb... |
| `stv-fahrradstrasse-karte-risiko-erklaeren` | Nutze dies, wenn Stv 049 Fahrradstrasse Karte Bauen, Stv 050 Fahrradstrasse Risiko Erklaeren, Stv 051 Busspur Regel Prüfen, Stv 052 Busspur Zeichen Auslegen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser: B... |
| `stv-gefahrenstelle-melden-schulweg` | Nutze dies, wenn Stv 013 Gefahrenstelle Melden, Stv 014 Schulweg Und Verkehrsberuhigung, Stv 015 Baustellenverkehrsrecht, Stv 016 Blaulicht Und Sonderrechte im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser: B... |
| `stv-haltverbot-eilrechtsschutz-behoerde` | Nutze dies, wenn Stv 027 Haltverbot Eilrechtsschutz Planen, Stv 028 Haltverbot Behörde Anschreiben, Stv 029 Haltverbot Karte Bauen, Stv 030 Haltverbot Risiko Erklaeren im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll.... |
| `stv-haltverbot-zeichen-anordnung-angreifen` | Nutze dies, wenn Stv 022 Haltverbot Zeichen Auslegen, Stv 023 Haltverbot Anordnung Angreifen, Stv 024 Haltverbot Antrag Schreiben, Stv 025 Haltverbot Beweis Sichern im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Aus... |
| `stv-ladezone-antrag-sichern-eilrechtsschutz` | Nutze dies, wenn Stv 084 Ladezone Antrag Schreiben, Stv 085 Ladezone Beweis Sichern, Stv 087 Ladezone Eilrechtsschutz Planen, Stv 088 Ladezone Behörde Anschreiben im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslö... |
| `stv-ladezone-karte-risiko-erklaeren` | Nutze dies, wenn Stv 089 Ladezone Karte Bauen, Stv 090 Ladezone Risiko Erklaeren, Stv 091 Schulstrasse Regel Prüfen, Stv 092 Schulstrasse Zeichen Auslegen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser: Bit... |
| `stv-lieferzone-regel-zeichen-auslegen` | Nutze dies, wenn Stv 071 Lieferzone Regel Prüfen, Stv 072 Lieferzone Zeichen Auslegen, Stv 073 Lieferzone Anordnung Angreifen, Stv 074 Lieferzone Antrag Schreiben im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslö... |
| `stv-lieferzone-risiko-ladezone-regel-zeichen` | Nutze dies, wenn Stv 080 Lieferzone Risiko Erklaeren, Stv 081 Ladezone Regel Prüfen, Stv 082 Ladezone Zeichen Auslegen, Stv 083 Ladezone Anordnung Angreifen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser: B... |
| `stv-lieferzone-sichern-eilrechtsschutz-planen` | Nutze dies, wenn Stv 075 Lieferzone Beweis Sichern, Stv 077 Lieferzone Eilrechtsschutz Planen, Stv 078 Lieferzone Behörde Anschreiben, Stv 079 Lieferzone Karte Bauen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Au... |
| `stv-parken-stv-ausnahmegenehmigung-stv` | Nutze dies, wenn Stv 005 Parken Halten Abschleppen, Stv 006 Ausnahmegenehmigung Beantragen, Stv 007 Radverkehr Und Schutzstreifen, Stv 008 E Scooter Und Mikromobilitaet im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll.... |
| `stv-schulstrasse-anordnung-antrag-schreiben` | Nutze dies, wenn Stv 093 Schulstrasse Anordnung Angreifen, Stv 094 Schulstrasse Antrag Schreiben, Stv 095 Schulstrasse Beweis Sichern, Stv 097 Schulstrasse Eilrechtsschutz Planen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet we... |
| `stv-schulstrasse-bussgeld-verkehrszeichen` | Nutze dies, wenn Stv 096 Schulstrasse Bussgeld Abgrenzen, Stv 002 Verkehrszeichen Lesen, Stv 003 Verkehrsrechtliche Anordnung Prüfen, Stv 004 Tempozone Und Beschilderung im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll... |
| `stv-schulstrasse-stv-schulstrasse` | Nutze dies, wenn Stv 098 Schulstrasse Behörde Anschreiben, Stv 099 Schulstrasse Karte Bauen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser: Bitte Stv 098 Schulstrasse Behörde Anschreiben, Stv 099 Schulstras... |
| `stv-schwertransport-stv-fahrerlaubnis-stv-mpu` | Nutze dies, wenn Stv 009 Schwertransport Und Erlaubnis, Stv 010 Fahrerlaubnis Schnittstelle, Stv 011 Mpu Und Fahreignung, Stv 012 Fahrtenbuchauflage im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser: Bitte Stv... |
| `stv-tempo-regel-zeichen-auslegen-anordnung` | Nutze dies, wenn Stv 031 Tempo 30 Regel Prüfen, Stv 032 Tempo 30 Zeichen Auslegen, Stv 033 Tempo 30 Anordnung Angreifen, Stv 034 Tempo 30 Antrag Schreiben im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser: Bit... |
| `stv-tempo-sichern-eilrechtsschutz-planen` | Nutze dies, wenn Stv 035 Tempo 30 Beweis Sichern, Stv 037 Tempo 30 Eilrechtsschutz Planen, Stv 038 Tempo 30 Behörde Anschreiben, Stv 039 Tempo 30 Karte Bauen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden soll. Auslöser:... |
| `stv-tempo-stv-fahrradstrasse-stv-stv` | Nutze dies, wenn Stv 040 Tempo 30 Risiko Erklaeren, Stv 041 Fahrradstrasse Regel Prüfen, Stv 042 Fahrradstrasse Zeichen Auslegen, Stv 043 Fahrradstrasse Anordnung Angreifen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet werden s... |
| `stv-widerspruch-stv-eilrechtsschutz-stv` | Nutze dies, wenn Stv 018 Widerspruch Gegen Verkehrszeichen, Stv 019 Eilrechtsschutz Verkehrszeichen, Stv 020 Kommunikation Mit Strassenverkehrsbeho, Stv 021 Haltverbot Regel Prüfen im Plugin Strassenverkehrsrecht Stvo konkret bearbeitet... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
