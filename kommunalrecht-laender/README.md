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
| `allgemein` | Kommunalrecht der Länder: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |
| `kom-001-kaltstart-kommunalrechtsfall` | Kommunalrecht der Länder: Kaltstart Kommunalrechtsfall. Kaltstart Kommunalrechtsfall im Fachgebiet Kommunalrecht der Länder als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `kom-ausschuss-finanzierung-dashboard-bauen` | Nutze dies bei Kom 094 Ausschuss Finanzierung Erklaeren, Kom 095 Ausschuss Dashboard Bauen, Kom 096 Ausschuss Beteiligung Planen, Kom 097 Ortschaftsrat Landesrecht Routen: führt durch diese fachlich verbundenen Module, wählt den passende... |
| `kom-ausschuss-kom-ortschaftsrat-kom` | Nutze dies bei Kom 088 Ausschuss Zustaendigkeit Prüfen, Kom 098 Ortschaftsrat Zustaendigkeit Prüfen, Kom 108 Kommunalaufsicht Zustaendigkeit Pruefe, Kom 118 Kommunalabgabe Zustaendigkeit Prüfen: führt durch diese fachlich verbundenen Mod... |
| `kom-ausschuss-landesrecht-beschluss-bauen` | Nutze dies bei Kom 087 Ausschuss Landesrecht Routen, Kom 089 Ausschuss Beschluss Bauen, Kom 090 Ausschuss Satzung Redlinen, Kom 091 Ausschuss Gebuehr Kalkulieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfa... |
| `kom-buergermeister-finanzierung-dashboard` | Nutze dies bei Kom 074 Buergermeister Finanzierung Erklaeren, Kom 075 Buergermeister Dashboard Bauen, Kom 076 Buergermeister Beteiligung Planen, Kom 077 Landrat Landesrecht Routen: führt durch diese fachlich verbundenen Module, wählt den... |
| `kom-buergermeister-landesrecht-beschluss` | Nutze dies bei Kom 067 Buergermeister Landesrecht Routen, Kom 069 Buergermeister Beschluss Bauen, Kom 070 Buergermeister Satzung Redlinen, Kom 071 Buergermeister Gebuehr Kalkulieren: führt durch diese fachlich verbundenen Module, wählt d... |
| `kom-einwohnerantrag-petition-haushalt` | Nutze dies bei Kom 009 Einwohnerantrag Und Petition, Kom 011 Haushalt Und Haushaltssicherung, Kom 012 Kommunales Unternehmen, Kom 013 Oeffentliche Einrichtung: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad u... |
| `kom-feuerwehr-kom-feuerwehr` | Nutze dies bei Kom 157 Feuerwehr Landesrecht Routen, Kom 159 Feuerwehr Beschluss Bauen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `kom-gemeinde-kom-ratssitzung-kom-beschluss` | Nutze dies bei Kom 002 Gemeinde Stadt Landkreis Zuordnen, Kom 004 Ratssitzung Und Tagesordnung, Kom 005 Beschluss Und Befangenheit, Kom 006 Satzung Entwerfen Und Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `kom-gemeinderat-gebuehr-aufsichtsbeschwerde` | Nutze dies bei Kom 041 Gemeinderat Gebuehr Kalkulieren, Kom 042 Gemeinderat Aufsichtsbeschwerde Schrei, Kom 043 Gemeinderat Eilantrag Vorbereiten, Kom 044 Gemeinderat Finanzierung Erklaeren: führt durch diese fachlich verbundenen Module,... |
| `kom-kita-satzung-beschluss-bauen-redlinen` | Nutze dies bei Kom 137 Kita Satzung Landesrecht Routen, Kom 139 Kita Satzung Beschluss Bauen, Kom 140 Kita Satzung Satzung Redlinen, Kom 141 Kita Satzung Gebuehr Kalkulieren: führt durch diese fachlich verbundenen Module, wählt den passe... |
| `kom-kita-satzung-dashboard-bauen-beteiligung` | Nutze dies bei Kom 144 Kita Satzung Finanzierung Erklaeren, Kom 145 Kita Satzung Dashboard Bauen, Kom 146 Kita Satzung Beteiligung Planen, Kom 147 Schultraeger Landesrecht Routen: führt durch diese fachlich verbundenen Module, wählt den... |
| `kom-kommunalabgabe-gebuehr` | Nutze dies bei Kom 121 Kommunalabgabe Gebuehr Kalkulieren, Kom 122 Kommunalabgabe Aufsichtsbeschwerde Sch, Kom 123 Kommunalabgabe Eilantrag Vorbereiten, Kom 124 Kommunalabgabe Finanzierung Erklaeren: führt durch diese fachlich verbundene... |
| `kom-kommunalaufsicht-finanzierung-dashboard` | Nutze dies bei Kom 114 Kommunalaufsicht Finanzierung Erklaere, Kom 115 Kommunalaufsicht Dashboard Bauen, Kom 116 Kommunalaufsicht Beteiligung Planen, Kom 127 Strassenreinigung Landesrecht Routen: führt durch diese fachlich verbundenen Mo... |
| `kom-kommunalaufsicht-landesrecht-beschluss` | Nutze dies bei Kom 107 Kommunalaufsicht Landesrecht Routen, Kom 109 Kommunalaufsicht Beschluss Bauen, Kom 110 Kommunalaufsicht Satzung Redlinen, Kom 111 Kommunalaufsicht Gebuehr Kalkulieren: führt durch diese fachlich verbundenen Module,... |
| `kom-kommunaler-finanzausgleich-interkommunale` | Nutze dies bei Kom 016 Kommunaler Finanzausgleich, Kom 017 Interkommunale Zusammenarbeit, Kom 018 Informationsrechte Ratsmitglied, Kom 019 Eilrechtsschutz Kommunalstreit: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `kom-kommunalrecht-bayern-berlin-routen` | Nutze dies bei Kom 022 Kommunalrecht Bayern Routen, Kom 023 Kommunalrecht Berlin Routen, Kom 024 Kommunalrecht Brandenburg Routen, Kom 025 Kommunalrecht Bremen Routen: führt durch diese fachlich verbundenen Module, wählt den passenden Pr... |
| `kom-kommunalrecht-mecklenburg-niedersachsen` | Nutze dies bei Kom 028 Kommunalrecht Mecklenburg Vorpommern R, Kom 029 Kommunalrecht Niedersachsen Routen, Kom 030 Kommunalrecht Nordrhein Westfalen Rout, Kom 031 Kommunalrecht Rheinland Pfalz Routen: führt durch diese fachlich verbunden... |
| `kom-kommunalrecht-sachsen-schleswig-holstein` | Nutze dies bei Kom 034 Kommunalrecht Sachsen Anhalt Routen, Kom 035 Kommunalrecht Schleswig Holstein Route, Kom 036 Kommunalrecht Thueringen Routen, Kom 037 Gemeinderat Landesrecht Routen: führt durch diese fachlich verbundenen Module, w... |
| `kom-kreistag-gebuehr-aufsichtsbeschwerde` | Nutze dies bei Kom 061 Kreistag Gebuehr Kalkulieren, Kom 062 Kreistag Aufsichtsbeschwerde Schreiben, Kom 063 Kreistag Eilantrag Vorbereiten, Kom 064 Kreistag Finanzierung Erklaeren: führt durch diese fachlich verbundenen Module, wählt de... |
| `kom-landrat-gebuehr-aufsichtsbeschwerde` | Nutze dies bei Kom 081 Landrat Gebuehr Kalkulieren, Kom 082 Landrat Aufsichtsbeschwerde Schreiben, Kom 083 Landrat Eilantrag Vorbereiten, Kom 084 Landrat Finanzierung Erklaeren: führt durch diese fachlich verbundenen Module, wählt den pa... |
| `kom-organ-gemeinderat-stadtrat-kreistag` | Nutze dies bei Kom 003 Organ Und Zustaendigkeit Prüfen, Kom 038 Gemeinderat Zustaendigkeit Prüfen, Kom 048 Stadtrat Zustaendigkeit Prüfen, Kom 058 Kreistag Zustaendigkeit Prüfen: führt durch diese fachlich verbundenen Module, wählt den p... |
| `kom-ortschaftsrat-gebuehr-aufsichtsbeschwerde` | Nutze dies bei Kom 101 Ortschaftsrat Gebuehr Kalkulieren, Kom 102 Ortschaftsrat Aufsichtsbeschwerde Schr, Kom 103 Ortschaftsrat Eilantrag Vorbereiten, Kom 104 Ortschaftsrat Finanzierung Erklaeren: führt durch diese fachlich verbundenen M... |
| `kom-schultraeger-gebuehr-aufsichtsbeschwerde` | Nutze dies bei Kom 151 Schultraeger Gebuehr Kalkulieren, Kom 152 Schultraeger Aufsichtsbeschwerde Schre, Kom 153 Schultraeger Eilantrag Vorbereiten, Kom 154 Schultraeger Finanzierung Erklaeren: führt durch diese fachlich verbundenen Modu... |
| `kom-schultraeger-kom-feuerwehr-kom` | Nutze dies bei Kom 148 Schultraeger Zustaendigkeit Prüfen, Kom 158 Feuerwehr Zustaendigkeit Prüfen, Kom 010 Kommunalabgaben Prüfen, Kom 117 Kommunalabgabe Landesrecht Routen: führt durch diese fachlich verbundenen Module, wählt den passe... |
| `kom-stadtrat-finanzierung-dashboard-bauen` | Nutze dies bei Kom 054 Stadtrat Finanzierung Erklaeren, Kom 055 Stadtrat Dashboard Bauen, Kom 056 Stadtrat Beteiligung Planen, Kom 057 Kreistag Landesrecht Routen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpf... |
| `kom-stadtrat-landesrecht-beschluss-bauen` | Nutze dies bei Kom 047 Stadtrat Landesrecht Routen, Kom 049 Stadtrat Beschluss Bauen, Kom 050 Stadtrat Satzung Redlinen, Kom 051 Stadtrat Gebuehr Kalkulieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad un... |
| `kom-strassenreinigung-kom-kom` | Nutze dies bei Kom 131 Strassenreinigung Gebuehr Kalkulieren, Kom 132 Strassenreinigung Aufsichtsbeschwerde, Kom 133 Strassenreinigung Eilantrag Vorbereite, Kom 134 Strassenreinigung Finanzierung Erklaer: führt durch diese fachlich verbu... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
