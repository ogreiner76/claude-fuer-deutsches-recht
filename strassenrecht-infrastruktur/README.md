# Straßenrecht und Infrastruktur

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`strassenrecht-infrastruktur`) | [`strassenrecht-infrastruktur.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/strassenrecht-infrastruktur.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Straßenrechtsakte Auenfeld** (`strassenrecht-ortsdurchfahrt-bruecke-auenfeld`) | [Gesamt-PDF lesen](../testakten/strassenrecht-ortsdurchfahrt-bruecke-auenfeld/gesamt-pdf/strassenrecht-ortsdurchfahrt-bruecke-auenfeld_gesamt.pdf) | [`testakte-strassenrecht-ortsdurchfahrt-bruecke-auenfeld.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-strassenrecht-ortsdurchfahrt-bruecke-auenfeld.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin trennt Straßenrecht von Straßenverkehrsrecht: Bau, Widmung, Baulast, Unterhaltung, Sondernutzung, Planfeststellung, Anliegerrechte, Kreuzungen, Umstufung und Straßeninfrastruktur.

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
| `allgemein` | Straßenrecht und Infrastruktur: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |
| `str-001-kaltstart-strassenrechtsfall` | Straßenrecht und Infrastruktur: Kaltstart Straßenrechtsfall. Kaltstart Straßenrechtsfall im Fachgebiet Straßenrecht und Infrastruktur als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `str-autobahn-eilantrag-kostenlast` | Nutze dies bei Str 026 Autobahn Eilantrag Skizzieren, Str 027 Autobahn Kostenlast Prüfen, Str 028 Autobahn Unterhaltung Ruegen, Str 029 Autobahn Dokumente Sortieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüf... |
| `str-autobahn-str-bundesstrasse-str-str` | Nutze dies bei Str 030 Autobahn Dashboard Erstellen, Str 031 Bundesstrasse Baulast Prüfen, Str 032 Bundesstrasse Widmung Lesen, Str 033 Bundesstrasse Planrecht Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Pr... |
| `str-autobahn-widmung-planrecht-sondernutzung` | Nutze dies bei Str 022 Autobahn Widmung Lesen, Str 023 Autobahn Planrecht Prüfen, Str 024 Autobahn Sondernutzung Formulieren, Str 025 Autobahn Einwendung Bauen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `str-baustelle-str-strassenentwaesserung-str` | Nutze dies bei Str 010 Baustelle Und Verkehrsfuehrung, Str 011 Strassenentwaesserung, Str 012 Bruecke Und Tunnel, Str 013 Rastanlage Und Nebenbetrieb: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefer... |
| `str-bruecke-dashboard-tunnel-baulast-widmung` | Nutze dies bei Str 090 Bruecke Dashboard Erstellen, Str 091 Tunnel Baulast Prüfen, Str 092 Tunnel Widmung Lesen, Str 093 Tunnel Planrecht Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den... |
| `str-bruecke-eilantrag-kostenlast-unterhaltung` | Nutze dies bei Str 086 Bruecke Eilantrag Skizzieren, Str 087 Bruecke Kostenlast Prüfen, Str 088 Bruecke Unterhaltung Ruegen, Str 089 Bruecke Dokumente Sortieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `str-bruecke-widmung-planrecht-sondernutzung` | Nutze dies bei Str 082 Bruecke Widmung Lesen, Str 083 Bruecke Planrecht Prüfen, Str 084 Bruecke Sondernutzung Formulieren, Str 085 Bruecke Einwendung Bauen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und... |
| `str-bundesfernstrasse-landesstrasse` | Nutze dies bei Str 002 Bundesfernstrasse Oder Landesstrasse, Str 003 Strassenbaulasttraeger Bestimmen, Str 004 Widmung Und Einziehung Prüfen, Str 005 Umstufung Und Teileinziehung: führt durch diese fachlich verbundenen Module, wählt den... |
| `str-bundesstrasse-sondernutzung-einwendung` | Nutze dies bei Str 034 Bundesstrasse Sondernutzung Formuliere, Str 035 Bundesstrasse Einwendung Bauen, Str 036 Bundesstrasse Eilantrag Skizzieren, Str 037 Bundesstrasse Kostenlast Prüfen: führt durch diese fachlich verbundenen Module, wä... |
| `str-bundesstrasse-unterhaltung-dokumente` | Nutze dies bei Str 038 Bundesstrasse Unterhaltung Ruegen, Str 039 Bundesstrasse Dokumente Sortieren, Str 040 Bundesstrasse Dashboard Erstellen, Str 041 Landesstrasse Baulast Prüfen: führt durch diese fachlich verbundenen Module, wählt de... |
| `str-eilrechtsschutz-aktenplan-infrastruktur` | Nutze dies bei Str 018 Eilrechtsschutz Gegen Bau, Str 019 Aktenplan Infrastruktur, Str 020 Landesstrassengesetz Livecheck, Str 021 Autobahn Baulast Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und l... |
| `str-gemeindestrasse-dashboard-ortsdurchfahrt` | Nutze dies bei Str 070 Gemeindestrasse Dashboard Erstellen, Str 071 Ortsdurchfahrt Baulast Prüfen, Str 072 Ortsdurchfahrt Widmung Lesen, Str 073 Ortsdurchfahrt Planrecht Prüfen: führt durch diese fachlich verbundenen Module, wählt den pa... |
| `str-gemeindestrasse-eilantrag-kostenlast` | Nutze dies bei Str 066 Gemeindestrasse Eilantrag Skizzieren, Str 067 Gemeindestrasse Kostenlast Prüfen, Str 068 Gemeindestrasse Unterhaltung Ruegen, Str 069 Gemeindestrasse Dokumente Sortieren: führt durch diese fachlich verbundenen Modu... |
| `str-gemeindestrasse-widmung-planrecht` | Nutze dies bei Str 062 Gemeindestrasse Widmung Lesen, Str 063 Gemeindestrasse Planrecht Prüfen, Str 064 Gemeindestrasse Sondernutzung Formulie, Str 065 Gemeindestrasse Einwendung Bauen: führt durch diese fachlich verbundenen Module, wähl... |
| `str-kreisstrasse-sondernutzung-einwendung` | Nutze dies bei Str 054 Kreisstrasse Sondernutzung Formulieren, Str 055 Kreisstrasse Einwendung Bauen, Str 056 Kreisstrasse Eilantrag Skizzieren, Str 057 Kreisstrasse Kostenlast Prüfen: führt durch diese fachlich verbundenen Module, wählt... |
| `str-kreisstrasse-unterhaltung-dokumente` | Nutze dies bei Str 058 Kreisstrasse Unterhaltung Ruegen, Str 059 Kreisstrasse Dokumente Sortieren, Str 060 Kreisstrasse Dashboard Erstellen, Str 061 Gemeindestrasse Baulast Prüfen: führt durch diese fachlich verbundenen Module, wählt den... |
| `str-kreuzungsrecht-str-strassenausbaubeitrag` | Nutze dies bei Str 014 Kreuzungsrecht Bahn Wasser Strasse, Str 015 Strassenausbaubeitrag Prüfen, Str 016 Unterhaltungspflicht Und Winterdienst, Str 017 Schaeden Durch Strasse: führt durch diese fachlich verbundenen Module, wählt den pass... |
| `str-landesstrasse-eilantrag-kostenlast` | Nutze dies bei Str 046 Landesstrasse Eilantrag Skizzieren, Str 047 Landesstrasse Kostenlast Prüfen, Str 048 Landesstrasse Unterhaltung Ruegen, Str 049 Landesstrasse Dokumente Sortieren: führt durch diese fachlich verbundenen Module, wähl... |
| `str-landesstrasse-str-kreisstrasse-str-str` | Nutze dies bei Str 050 Landesstrasse Dashboard Erstellen, Str 051 Kreisstrasse Baulast Prüfen, Str 052 Kreisstrasse Widmung Lesen, Str 053 Kreisstrasse Planrecht Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `str-landesstrasse-widmung-planrecht` | Nutze dies bei Str 042 Landesstrasse Widmung Lesen, Str 043 Landesstrasse Planrecht Prüfen, Str 044 Landesstrasse Sondernutzung Formuliere, Str 045 Landesstrasse Einwendung Bauen: führt durch diese fachlich verbundenen Module, wählt den... |
| `str-ortsdurchfahrt-sondernutzung-einwendung` | Nutze dies bei Str 074 Ortsdurchfahrt Sondernutzung Formulier, Str 075 Ortsdurchfahrt Einwendung Bauen, Str 076 Ortsdurchfahrt Eilantrag Skizzieren, Str 077 Ortsdurchfahrt Kostenlast Prüfen: führt durch diese fachlich verbundenen Module,... |
| `str-ortsdurchfahrt-unterhaltung-dokumente` | Nutze dies bei Str 078 Ortsdurchfahrt Unterhaltung Ruegen, Str 079 Ortsdurchfahrt Dokumente Sortieren, Str 080 Ortsdurchfahrt Dashboard Erstellen, Str 081 Bruecke Baulast Prüfen: führt durch diese fachlich verbundenen Module, wählt den p... |
| `str-planfeststellung-strasse-plangenehmigung` | Nutze dies bei Str 006 Planfeststellung Strasse, Str 007 Plangenehmigung Und Uvp, Str 008 Anliegergebrauch Abgrenzen, Str 009 Sondernutzungserlaubnis: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefer... |
| `str-tunnel-sondernutzung-einwendung-bauen` | Nutze dies bei Str 094 Tunnel Sondernutzung Formulieren, Str 095 Tunnel Einwendung Bauen, Str 096 Tunnel Eilantrag Skizzieren, Str 097 Tunnel Kostenlast Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad... |
| `str-tunnel-str-tunnel` | Nutze dies bei Str 098 Tunnel Unterhaltung Ruegen, Str 099 Tunnel Dokumente Sortieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
