# Kommunalrecht der Länder

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`kommunalrecht-laender`) | [`kommunalrecht-laender.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/kommunalrecht-laender.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Kommunalakte Morgenfurt** (`kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt`) | [Gesamt-PDF lesen](../testakten/kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt/gesamt-pdf/kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt_gesamt.pdf) | [`testakte-kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-kommunalrecht-rathaus-morgenfurt-buergerentscheid-haushalt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist die Werkbank für kommunale Selbstverwaltung: Rat, Bürgermeister, Landkreis, Satzung, Gebühren, Haushalt, Bürgerbegehren, Kommunalaufsicht, kommunale Unternehmen und Landesrecht.

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

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | Kommunalrecht der Länder: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `kom-001-kaltstart-kommunalrechtsfall` | Kommunalrecht der Länder: Kaltstart Kommunalrechtsfall. Kaltstart Kommunalrechtsfall im Fachgebiet Kommunalrecht der Länder als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `kom-ausschuss-finanzierung-dashboard-bauen` | Nutze dies, wenn Kom 094 Ausschuss Finanzierung Erklaeren, Kom 095 Ausschuss Dashboard Bauen, Kom 096 Ausschuss Beteiligung Planen, Kom 097 Ortschaftsrat Landesrecht Routen, Kom 099 Ortschaftsrat Beschluss Bauen und 1 weitere Themen im P... |
| `kom-ausschuss-kom-ortschaftsrat-kom` | Nutze dies, wenn Kom 088 Ausschuss Zustaendigkeit Prüfen, Kom 098 Ortschaftsrat Zustaendigkeit Prüfen, Kom 108 Kommunalaufsicht Zustaendigkeit Pruefe, Kom 118 Kommunalabgabe Zustaendigkeit Prüfen, Kom 128 Strassenreinigung Zustaendigkeit... |
| `kom-ausschuss-landesrecht-beschluss-bauen` | Nutze dies, wenn Kom 087 Ausschuss Landesrecht Routen, Kom 089 Ausschuss Beschluss Bauen, Kom 090 Ausschuss Satzung Redlinen, Kom 091 Ausschuss Gebühr Kalkulieren, Kom 092 Ausschuss Aufsichtsbeschwerde Schreibe und 1 weitere Themen im Pl... |
| `kom-buergermeister-finanzierung-dashboard` | Nutze dies, wenn Kom 074 Buergermeister Finanzierung Erklaeren, Kom 075 Buergermeister Dashboard Bauen, Kom 076 Buergermeister Beteiligung Planen, Kom 077 Landrat Landesrecht Routen, Kom 079 Landrat Beschluss Bauen und 1 weitere Themen i... |
| `kom-buergermeister-landesrecht-beschluss` | Nutze dies, wenn Kom 067 Buergermeister Landesrecht Routen, Kom 069 Buergermeister Beschluss Bauen, Kom 070 Buergermeister Satzung Redlinen, Kom 071 Buergermeister Gebühr Kalkulieren, Kom 072 Buergermeister Aufsichtsbeschwerde Sch und 1... |
| `kom-einwohnerantrag-petition-haushalt` | Nutze dies, wenn Kom 009 Einwohnerantrag Und Petition, Kom 011 Haushalt Und Haushaltssicherung, Kom 012 Kommunales Unternehmen, Kom 013 Oeffentliche Einrichtung, Kom 014 Benutzungsordnung und 1 weitere Themen im Plugin Kommunalrecht Länd... |
| `kom-feuerwehr-kom-feuerwehr` | Nutze dies, wenn Kom 157 Feuerwehr Landesrecht Routen, Kom 159 Feuerwehr Beschluss Bauen im Plugin Kommunalrecht Länder konkret bearbeitet werden soll. Auslöser: Bitte Kom 157 Feuerwehr Landesrecht Routen, Kom 159 Feuerwehr Beschluss Bau... |
| `kom-gemeinde-kom-ratssitzung-kom-beschluss` | Nutze dies, wenn Kom 002 Gemeinde Stadt Landkreis Zuordnen, Kom 004 Ratssitzung Und Tagesordnung, Kom 005 Beschluss Und Befangenheit, Kom 006 Satzung Entwerfen Und Prüfen, Kom 007 Kommunalaufsicht Einschalten und 1 weitere Themen im Plug... |
| `kom-gemeinderat-gebuehr-aufsichtsbeschwerde` | Nutze dies, wenn Kom 041 Gemeinderat Gebühr Kalkulieren, Kom 042 Gemeinderat Aufsichtsbeschwerde Schrei, Kom 043 Gemeinderat Eilantrag Vorbereiten, Kom 044 Gemeinderat Finanzierung Erklaeren, Kom 045 Gemeinderat Dashboard Bauen und 1 wei... |
| `kom-kita-satzung-beschluss-bauen-redlinen` | Nutze dies, wenn Kom 137 Kita Satzung Landesrecht Routen, Kom 139 Kita Satzung Beschluss Bauen, Kom 140 Kita Satzung Satzung Redlinen, Kom 141 Kita Satzung Gebühr Kalkulieren, Kom 142 Kita Satzung Aufsichtsbeschwerde Schre und 1 weitere... |
| `kom-kita-satzung-dashboard-bauen-beteiligung` | Nutze dies, wenn Kom 144 Kita Satzung Finanzierung Erklaeren, Kom 145 Kita Satzung Dashboard Bauen, Kom 146 Kita Satzung Beteiligung Planen, Kom 147 Schultraeger Landesrecht Routen, Kom 149 Schultraeger Beschluss Bauen und 1 weitere Them... |
| `kom-kommunalabgabe-gebuehr` | Nutze dies, wenn Kom 121 Kommunalabgabe Gebühr Kalkulieren, Kom 122 Kommunalabgabe Aufsichtsbeschwerde Sch, Kom 123 Kommunalabgabe Eilantrag Vorbereiten, Kom 124 Kommunalabgabe Finanzierung Erklaeren, Kom 125 Kommunalabgabe Dashboard Bau... |
| `kom-kommunalaufsicht-finanzierung-dashboard` | Nutze dies, wenn Kom 114 Kommunalaufsicht Finanzierung Erklaere, Kom 115 Kommunalaufsicht Dashboard Bauen, Kom 116 Kommunalaufsicht Beteiligung Planen, Kom 127 Strassenreinigung Landesrecht Routen, Kom 129 Strassenreinigung Beschluss Bau... |
| `kom-kommunalaufsicht-landesrecht-beschluss` | Nutze dies, wenn Kom 107 Kommunalaufsicht Landesrecht Routen, Kom 109 Kommunalaufsicht Beschluss Bauen, Kom 110 Kommunalaufsicht Satzung Redlinen, Kom 111 Kommunalaufsicht Gebühr Kalkulieren, Kom 112 Kommunalaufsicht Aufsichtsbeschwerde... |
| `kom-kommunaler-finanzausgleich-interkommunale` | Nutze dies, wenn Kom 016 Kommunaler Finanzausgleich, Kom 017 Interkommunale Zusammenarbeit, Kom 018 Informationsrechte Ratsmitglied, Kom 019 Eilrechtsschutz Kommunalstreit, Kom 020 Kommunalrecht In Einfacher Sprache und 1 weitere Themen... |
| `kom-kommunalrecht-bayern-berlin-routen` | Nutze dies, wenn Kom 022 Kommunalrecht Bayern Routen, Kom 023 Kommunalrecht Berlin Routen, Kom 024 Kommunalrecht Brandenburg Routen, Kom 025 Kommunalrecht Bremen Routen, Kom 026 Kommunalrecht Hamburg Routen und 1 weitere Themen im Plugin... |
| `kom-kommunalrecht-mecklenburg-niedersachsen` | Nutze dies, wenn Kom 028 Kommunalrecht Mecklenburg Vorpommern R, Kom 029 Kommunalrecht Niedersachsen Routen, Kom 030 Kommunalrecht Nordrhein Westfalen Rout, Kom 031 Kommunalrecht Rheinland Pfalz Routen, Kom 032 Kommunalrecht Saarland Rou... |
| `kom-kommunalrecht-sachsen-schleswig-holstein` | Nutze dies, wenn Kom 034 Kommunalrecht Sachsen Anhalt Routen, Kom 035 Kommunalrecht Schleswig Holstein Route, Kom 036 Kommunalrecht Thueringen Routen, Kom 037 Gemeinderat Landesrecht Routen, Kom 039 Gemeinderat Beschluss Bauen und 1 weit... |
| `kom-kreistag-gebuehr-aufsichtsbeschwerde` | Nutze dies, wenn Kom 061 Kreistag Gebühr Kalkulieren, Kom 062 Kreistag Aufsichtsbeschwerde Schreiben, Kom 063 Kreistag Eilantrag Vorbereiten, Kom 064 Kreistag Finanzierung Erklaeren, Kom 065 Kreistag Dashboard Bauen und 1 weitere Themen... |
| `kom-landrat-gebuehr-aufsichtsbeschwerde` | Nutze dies, wenn Kom 081 Landrat Gebühr Kalkulieren, Kom 082 Landrat Aufsichtsbeschwerde Schreiben, Kom 083 Landrat Eilantrag Vorbereiten, Kom 084 Landrat Finanzierung Erklaeren, Kom 085 Landrat Dashboard Bauen und 1 weitere Themen im Pl... |
| `kom-organ-gemeinderat-stadtrat-kreistag` | Nutze dies, wenn Kom 003 Organ Und Zustaendigkeit Prüfen, Kom 038 Gemeinderat Zustaendigkeit Prüfen, Kom 048 Stadtrat Zustaendigkeit Prüfen, Kom 058 Kreistag Zustaendigkeit Prüfen, Kom 068 Buergermeister Zustaendigkeit Prüfen und 1 weite... |
| `kom-ortschaftsrat-gebuehr-aufsichtsbeschwerde` | Nutze dies, wenn Kom 101 Ortschaftsrat Gebühr Kalkulieren, Kom 102 Ortschaftsrat Aufsichtsbeschwerde Schr, Kom 103 Ortschaftsrat Eilantrag Vorbereiten, Kom 104 Ortschaftsrat Finanzierung Erklaeren, Kom 105 Ortschaftsrat Dashboard Bauen u... |
| `kom-schultraeger-gebuehr-aufsichtsbeschwerde` | Nutze dies, wenn Kom 151 Schultraeger Gebühr Kalkulieren, Kom 152 Schultraeger Aufsichtsbeschwerde Schre, Kom 153 Schultraeger Eilantrag Vorbereiten, Kom 154 Schultraeger Finanzierung Erklaeren, Kom 155 Schultraeger Dashboard Bauen und 1... |
| `kom-schultraeger-kom-feuerwehr-kom` | Nutze dies, wenn Kom 148 Schultraeger Zustaendigkeit Prüfen, Kom 158 Feuerwehr Zustaendigkeit Prüfen, Kom 010 Kommunalabgaben Prüfen, Kom 117 Kommunalabgabe Landesrecht Routen, Kom 119 Kommunalabgabe Beschluss Bauen und 1 weitere Themen... |
| `kom-stadtrat-finanzierung-dashboard-bauen` | Nutze dies, wenn Kom 054 Stadtrat Finanzierung Erklaeren, Kom 055 Stadtrat Dashboard Bauen, Kom 056 Stadtrat Beteiligung Planen, Kom 057 Kreistag Landesrecht Routen, Kom 059 Kreistag Beschluss Bauen und 1 weitere Themen im Plugin Kommuna... |
| `kom-stadtrat-landesrecht-beschluss-bauen` | Nutze dies, wenn Kom 047 Stadtrat Landesrecht Routen, Kom 049 Stadtrat Beschluss Bauen, Kom 050 Stadtrat Satzung Redlinen, Kom 051 Stadtrat Gebühr Kalkulieren, Kom 052 Stadtrat Aufsichtsbeschwerde Schreiben und 1 weitere Themen im Plugin... |
| `kom-strassenreinigung-kom-kom` | Nutze dies, wenn Kom 131 Strassenreinigung Gebühr Kalkulieren, Kom 132 Strassenreinigung Aufsichtsbeschwerde, Kom 133 Strassenreinigung Eilantrag Vorbereite, Kom 134 Strassenreinigung Finanzierung Erklaer, Kom 135 Strassenreinigung Dashb... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
