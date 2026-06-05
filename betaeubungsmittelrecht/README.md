# Betäubungsmittelrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`betaeubungsmittelrecht`) | [`betaeubungsmittelrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/betaeubungsmittelrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **BtM-Akte** (`betaeubungsmittelrecht-apotheke-substitution-festival`) | [Gesamt-PDF lesen](../testakten/betaeubungsmittelrecht-apotheke-substitution-festival/gesamt-pdf/betaeubungsmittelrecht-apotheke-substitution-festival_gesamt.pdf) | [`testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-betaeubungsmittelrecht-apotheke-substitution-festival.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin behandelt BtM nicht nur strafrechtlich: Verkehrsfähigkeit, Verschreibung, Apotheke, ärztliche Praxis, Erlaubnis, Strafverteidigung, Therapie, Cannabis-Schnittstelle und Compliance werden getrennt geführt.

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
| `allgemein` | Betäubungsmittelrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `btm-001-kaltstart-btm-fall` | Betäubungsmittelrecht: Kaltstart BtM-Fall. Kaltstart BtM-Fall im Fachgebiet Betäubungsmittelrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `btm-amphetamin-bauen-akteneinsicht` | Nutze dies, wenn Btm 058 Amphetamin Compliance Bauen, Btm 059 Amphetamin Akteneinsicht Vorbereiten, Btm 060 Amphetamin Mandantenbrief Schreiben, Btm 061 Mdma Stoff Prüfen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. A... |
| `btm-amphetamin-sichern-einlassung-planen` | Nutze dies, wenn Btm 054 Amphetamin Beweis Sichern, Btm 055 Amphetamin Einlassung Planen, Btm 056 Amphetamin Therapiepfad Prüfen, Btm 057 Amphetamin Erlaubnis Prüfen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslös... |
| `btm-aufklaerungshilfe-btm-kcang-btm` | Nutze dies, wenn Btm 010 Aufklaerungshilfe 31 Btmg, Btm 011 Kcang Und Medcang Abgrenzen, Btm 012 Neue Psychoaktive Stoffe, Btm 013 Durchsuchung Und Beschlagnahme im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser:... |
| `btm-btm-btm-arztpraxis-btm-apotheke-btm` | Nutze dies, wenn Btm 006 Btm Rezept Und Btmvv, Btm 007 Arztpraxis Compliance, Btm 008 Apotheke Btm Dokumentation, Btm 009 Therapie Statt Strafe im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte Btm 006 Btm... |
| `btm-cannabis-mandantenbrief-kokain-stoff` | Nutze dies, wenn Btm 030 Cannabis Mandantenbrief Schreiben, Btm 031 Kokain Stoff Prüfen, Btm 032 Kokain Menge Einordnen, Btm 033 Kokain Strafrahmen Routen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte B... |
| `btm-cannabis-menge-strafrahmen-routen-sichern` | Nutze dies, wenn Btm 022 Cannabis Menge Einordnen, Btm 023 Cannabis Strafrahmen Routen, Btm 024 Cannabis Beweis Sichern, Btm 025 Cannabis Einlassung Planen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte... |
| `btm-cannabis-therapiepfad-erlaubnis-bauen` | Nutze dies, wenn Btm 026 Cannabis Therapiepfad Prüfen, Btm 027 Cannabis Erlaubnis Prüfen, Btm 028 Cannabis Compliance Bauen, Btm 029 Cannabis Akteneinsicht Vorbereiten im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Ausl... |
| `btm-fentanyl-bauen-akteneinsicht-vorbereiten` | Nutze dies, wenn Btm 078 Fentanyl Compliance Bauen, Btm 079 Fentanyl Akteneinsicht Vorbereiten, Btm 080 Fentanyl Mandantenbrief Schreiben, Btm 081 Methadon Stoff Prüfen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Aus... |
| `btm-fentanyl-sichern-einlassung-planen` | Nutze dies, wenn Btm 074 Fentanyl Beweis Sichern, Btm 075 Fentanyl Einlassung Planen, Btm 076 Fentanyl Therapiepfad Prüfen, Btm 077 Fentanyl Erlaubnis Prüfen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitt... |
| `btm-heroin-mandantenbrief-amphetamin-stoff` | Nutze dies, wenn Btm 050 Heroin Mandantenbrief Schreiben, Btm 051 Amphetamin Stoff Prüfen, Btm 052 Amphetamin Menge Einordnen, Btm 053 Amphetamin Strafrahmen Routen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöse... |
| `btm-heroin-menge-strafrahmen-routen-sichern` | Nutze dies, wenn Btm 042 Heroin Menge Einordnen, Btm 043 Heroin Strafrahmen Routen, Btm 044 Heroin Beweis Sichern, Btm 045 Heroin Einlassung Planen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte Btm 042... |
| `btm-heroin-therapiepfad-erlaubnis-bauen` | Nutze dies, wenn Btm 046 Heroin Therapiepfad Prüfen, Btm 047 Heroin Erlaubnis Prüfen, Btm 048 Heroin Compliance Bauen, Btm 049 Heroin Akteneinsicht Vorbereiten im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bi... |
| `btm-kokain-bauen-akteneinsicht-vorbereiten` | Nutze dies, wenn Btm 038 Kokain Compliance Bauen, Btm 039 Kokain Akteneinsicht Vorbereiten, Btm 040 Kokain Mandantenbrief Schreiben, Btm 041 Heroin Stoff Prüfen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: B... |
| `btm-kokain-sichern-einlassung-planen` | Nutze dies, wenn Btm 034 Kokain Beweis Sichern, Btm 035 Kokain Einlassung Planen, Btm 036 Kokain Therapiepfad Prüfen, Btm 037 Kokain Erlaubnis Prüfen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte Btm 03... |
| `btm-mdma-mandantenbrief-fentanyl-stoff-menge` | Nutze dies, wenn Btm 070 Mdma Mandantenbrief Schreiben, Btm 071 Fentanyl Stoff Prüfen, Btm 072 Fentanyl Menge Einordnen, Btm 073 Fentanyl Strafrahmen Routen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte... |
| `btm-mdma-menge-strafrahmen-routen-sichern` | Nutze dies, wenn Btm 062 Mdma Menge Einordnen, Btm 063 Mdma Strafrahmen Routen, Btm 064 Mdma Beweis Sichern, Btm 065 Mdma Einlassung Planen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte Btm 062 Mdma Men... |
| `btm-mdma-therapiepfad-erlaubnis-bauen` | Nutze dies, wenn Btm 066 Mdma Therapiepfad Prüfen, Btm 067 Mdma Erlaubnis Prüfen, Btm 068 Mdma Compliance Bauen, Btm 069 Mdma Akteneinsicht Vorbereiten im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte Btm... |
| `btm-medizinalcannabis-btm-btm` | Nutze dies, wenn Btm 094 Medizinalcannabis Beweis Sichern, Btm 095 Medizinalcannabis Einlassung Planen, Btm 096 Medizinalcannabis Therapiepfad Prüfen, Btm 097 Medizinalcannabis Erlaubnis Prüfen im Plugin Betaeubungsmittelrecht konkret be... |
| `btm-medizinalcannabis-btm-medizinalcannabis` | Nutze dies, wenn Btm 098 Medizinalcannabis Compliance Bauen, Btm 099 Medizinalcannabis Akteneinsicht Vorber im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte Btm 098 Medizinalcannabis Compliance Bauen, Btm... |
| `btm-methadon-mandantenbrief-medizinalcannabis` | Nutze dies, wenn Btm 090 Methadon Mandantenbrief Schreiben, Btm 091 Medizinalcannabis Stoff Prüfen, Btm 092 Medizinalcannabis Menge Einordnen, Btm 093 Medizinalcannabis Strafrahmen Routen im Plugin Betaeubungsmittelrecht konkret bearbeit... |
| `btm-methadon-menge-strafrahmen-routen-sichern` | Nutze dies, wenn Btm 082 Methadon Menge Einordnen, Btm 083 Methadon Strafrahmen Routen, Btm 084 Methadon Beweis Sichern, Btm 085 Methadon Einlassung Planen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte... |
| `btm-methadon-therapiepfad-erlaubnis-bauen` | Nutze dies, wenn Btm 086 Methadon Therapiepfad Prüfen, Btm 087 Methadon Erlaubnis Prüfen, Btm 088 Methadon Compliance Bauen, Btm 089 Methadon Akteneinsicht Vorbereiten im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Ausl... |
| `btm-stoff-btm-nicht-btm-handeltreiben-btm` | Nutze dies, wenn Btm 002 Stoff Und Anlage Prüfen, Btm 003 Nicht Geringe Menge Livecheck, Btm 004 Handeltreiben Oder Besitz, Btm 005 Einfuhr Ausfuhr Durchfuhr im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitt... |
| `btm-u-btm-einziehung-btm-jugendliche-btm` | Nutze dies, wenn Btm 014 U Haft In Btm Sache, Btm 015 Einziehung Und Wertersatz, Btm 016 Jugendliche Und Btm, Btm 017 Fahrerlaubnis Und Btm im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte Btm 014 U Haft I... |
| `btm-versand-btm-betriebspruefung-btm-btm-btm` | Nutze dies, wenn Btm 018 Internationaler Versand, Btm 019 Betriebspruefung Apotheke, Btm 020 Btm In Einfacher Sprache, Btm 021 Cannabis Stoff Prüfen im Plugin Betaeubungsmittelrecht konkret bearbeitet werden soll. Auslöser: Bitte Btm 018... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
