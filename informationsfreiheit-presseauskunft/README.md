# Informationsfreiheit und Presseauskunft

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`informationsfreiheit-presseauskunft`) | [`informationsfreiheit-presseauskunft.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/informationsfreiheit-presseauskunft.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **IFG-/Presseauskunftsakte Hafenstadt** (`informationsfreiheit-presseauskunft-klinikdaten-hafenstadt`) | [Gesamt-PDF lesen](../testakten/informationsfreiheit-presseauskunft-klinikdaten-hafenstadt/gesamt-pdf/informationsfreiheit-presseauskunft-klinikdaten-hafenstadt_gesamt.pdf) | [`testakte-informationsfreiheit-presseauskunft-klinikdaten-hafenstadt.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-informationsfreiheit-presseauskunft-klinikdaten-hafenstadt.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist das Cockpit für Menschen, Journalistinnen, Kanzleien, NGOs und Unternehmen, die amtliche Informationen bekommen wollen, ohne an Zuständigkeitsnebel, Gebührenbescheiden oder Ausweichantworten hängen zu bleiben.

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
| `allgemein` | Informationsfreiheit und Presseauskunft: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |
| `ifg-001-informationsbegehren-sortier` | Informationsfreiheit und Presseauskunft: Kaltstart Informationsbegehren sortieren. Kaltstart Informationsbegehren sortieren im Fachgebiet Informationsfreiheit und Presseauskunft als geführten Arbeitsgang mit Fragen, Dokumentenlogik und A... |
| `ifg-ablehnungsbescheid-angriffspunkte` | Nutze dies bei Ifg 013 Ablehnungsbescheid In Angriffspunkte Z, Ifg 014 Widerspruch Gegen Ifg Ablehnung, Ifg 015 Verpflichtungsklage Und Eilrechtsschut, Ifg 016 Gebuehrenbescheid Angreifen: führt durch diese fachlich verbundenen Module, w... |
| `ifg-archivrecht-ifg-ifg-ifg-ifg` | Nutze dies bei Ifg 098 Archivrecht Zustaendigkeit Prüfen, Ifg 099 Archivrecht Frist Setzen, Ifg 002 Ifg Oder Presseauskunft Richtig Routen, Ifg 003 Bundesbehoerde Oder Landesbehoerde Erk: führt durch diese fachlich verbundenen Module, wä... |
| `ifg-fristenkalender-ifg-ifg-ifg-ifg-ifg` | Nutze dies bei Ifg 006 Fristenkalender Und Untaetigkeitstrack, Ifg 038 Ifg Bund Zustaendigkeit Prüfen, Ifg 039 Ifg Bund Frist Setzen, Ifg 048 Ifggebv Gebuehren Zustaendigkeit Pruef: führt durch diese fachlich verbundenen Module, wählt de... |
| `ifg-ifg-ifg-ifg-ifg-ifg-ifg-ifg` | Nutze dies bei Ifg 037 Ifg Bund Antrag Formulieren, Ifg 040 Ifg Bund Kosten Deckeln, Ifg 041 Ifg Bund Schwaerzung Angreifen, Ifg 042 Ifg Bund Drittanhoerung Begleiten: führt durch diese fachlich verbundenen Module, wählt den passenden Pr... |
| `ifg-ifg-ifg-ifg-ifg-ifg-ifg-ifg-02` | Nutze dies bei Ifg 043 Ifg Bund Widerspruch Bauen, Ifg 044 Ifg Bund Klage Vorbereiten, Ifg 045 Ifg Bund Presseantwort Nachfassen, Ifg 046 Ifg Bund Tracking Aktualisieren: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `ifg-ifggebv-gebuehren-klage-vorbereiten` | Nutze dies bei Ifg 053 Ifggebv Gebuehren Widerspruch Bauen, Ifg 054 Ifggebv Gebuehren Klage Vorbereiten, Ifg 055 Ifggebv Gebuehren Presseantwort Nachfa, Ifg 056 Ifggebv Gebuehren Tracking Aktualisier: führt durch diese fachlich verbunden... |
| `ifg-ifggebv-gebuehren-kosten-deckeln` | Nutze dies bei Ifg 047 Ifggebv Gebuehren Antrag Formulieren, Ifg 050 Ifggebv Gebuehren Kosten Deckeln, Ifg 051 Ifggebv Gebuehren Schwaerzung Angreife, Ifg 052 Ifggebv Gebuehren Drittanhoerung Begle: führt durch diese fachlich verbundenen... |
| `ifg-ifggebv-ifg-uig-ifg-uig-ifg-vig` | Nutze dies bei Ifg 049 Ifggebv Gebuehren Frist Setzen, Ifg 058 Uig Umweltinformation Zustaendigkeit P, Ifg 059 Uig Umweltinformation Frist Setzen, Ifg 069 Vig Lebensmittel Und Produkte Frist Se: führt durch diese fachlich verbundenen Mod... |
| `ifg-informationszugang-beliehenen-parlaments` | Nutze dies bei Ifg 017 Informationszugang Bei Beliehenen Priv, Ifg 018 Parlaments Und Rechnungshofgrenzen, Ifg 019 Sicherheitsinteressen Und Geheimschutz, Ifg 020 Veroeffentlichung Erhaltene Dokumente: führt durch diese fachlich verbunde... |
| `ifg-informationszugang-ifg-ifg` | Nutze dies bei Ifg 021 Informationszugang Baden Wuerttemberg, Ifg 022 Informationszugang Bayern Livecheck, Ifg 023 Informationszugang Berlin Livecheck, Ifg 024 Informationszugang Brandenburg Liveche: führt durch diese fachlich verbundene... |
| `ifg-informationszugang-ifg-ifg-02` | Nutze dies bei Ifg 025 Informationszugang Bremen Livecheck, Ifg 026 Informationszugang Hamburg Livecheck, Ifg 027 Informationszugang Hessen Livecheck, Ifg 028 Informationszugang Mecklenburg Vorpomm: führt durch diese fachlich verbundenen... |
| `ifg-informationszugang-ifg-ifg-03` | Nutze dies bei Ifg 029 Informationszugang Niedersachsen Livec, Ifg 030 Informationszugang Nordrhein Westfalen, Ifg 031 Informationszugang Rheinland Pfalz Liv, Ifg 032 Informationszugang Saarland Livecheck: führt durch diese fachlich verb... |
| `ifg-informationszugang-ifg-ifg-04` | Nutze dies bei Ifg 033 Informationszugang Sachsen Livecheck, Ifg 034 Informationszugang Sachsen Anhalt Live, Ifg 035 Informationszugang Schleswig Holstein, Ifg 036 Informationszugang Thueringen Livechec: führt durch diese fachlich verbun... |
| `ifg-kein-ifg-kostenrisiko-ifg` | Nutze dies bei Ifg 004 Kein Ifg Im Land Ersatzwege Finden, Ifg 005 Kostenrisiko Und Gebuehrenankuendigung, Ifg 007 Drittbeteiligung Bei Betriebsgeheimnis, Ifg 008 Personenbezogene Daten Und Schwaerzung: führt durch diese fachlich verbund... |
| `ifg-landespressegesetz-ifg-ifg` | Nutze dies bei Ifg 078 Landespressegesetz Zustaendigkeit Prue, Ifg 079 Landespressegesetz Frist Setzen, Ifg 088 Transparenzgesetz Zustaendigkeit Pruef, Ifg 089 Transparenzgesetz Frist Setzen: führt durch diese fachlich verbundenen Module... |
| `ifg-landespressegesetz-ifg-ifg-02` | Nutze dies bei Ifg 082 Landespressegesetz Drittanhoerung Begl, Ifg 083 Landespressegesetz Widerspruch Bauen, Ifg 084 Landespressegesetz Klage Vorbereiten, Ifg 085 Landespressegesetz Presseantwort Nachf: führt durch diese fachlich verbund... |
| `ifg-landespressegesetz-ifg-transparenzgesetz` | Nutze dies bei Ifg 086 Landespressegesetz Tracking Aktualisie, Ifg 087 Transparenzgesetz Antrag Formulieren, Ifg 090 Transparenzgesetz Kosten Deckeln, Ifg 091 Transparenzgesetz Schwaerzung Angreife: führt durch diese fachlich verbundenen... |
| `ifg-transparenzgesetz-ifg-archivrecht` | Nutze dies bei Ifg 096 Transparenzgesetz Tracking Aktualisier, Ifg 097 Archivrecht Antrag Formulieren: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `ifg-transparenzgesetz-ifg-ifg` | Nutze dies bei Ifg 092 Transparenzgesetz Drittanhoerung Begle, Ifg 093 Transparenzgesetz Widerspruch Bauen, Ifg 094 Transparenzgesetz Klage Vorbereiten, Ifg 095 Transparenzgesetz Presseantwort Nachfa: führt durch diese fachlich verbunden... |
| `ifg-uig-ifg-uig-ifg-uig-ifg-uig` | Nutze dies bei Ifg 057 Uig Umweltinformation Antrag Formulier, Ifg 060 Uig Umweltinformation Kosten Deckeln, Ifg 061 Uig Umweltinformation Schwaerzung Angr, Ifg 062 Uig Umweltinformation Drittanhoerung B: führt durch diese fachlich verbu... |
| `ifg-uig-ifg-uig-ifg-uig-ifg-uig-02` | Nutze dies bei Ifg 063 Uig Umweltinformation Widerspruch Baue, Ifg 064 Uig Umweltinformation Klage Vorbereite, Ifg 065 Uig Umweltinformation Presseantwort Na, Ifg 066 Uig Umweltinformation Tracking Aktuali: führt durch diese fachlich ver... |
| `ifg-uig-ifg-vig-ifg-akteneinsicht-ifg` | Nutze dies bei Ifg 009 Uig Und Umweltinformationen Abgrenzen, Ifg 010 Vig Und Verbraucherinformationen Nutze, Ifg 011 Akteneinsicht Oder Auskunft Oder Kopie, Ifg 012 Presseanfrage Schnell Und Knapp Formul: führt durch diese fachlich verb... |
| `ifg-vig-ifg-landespressegesetz-ifg-ifg` | Nutze dies bei Ifg 076 Vig Lebensmittel Und Produkte Tracking, Ifg 077 Landespressegesetz Antrag Formulieren, Ifg 080 Landespressegesetz Kosten Deckeln, Ifg 081 Landespressegesetz Schwaerzung Angreif: führt durch diese fachlich verbunden... |
| `ifg-vig-ifg-vig-ifg-vig-ifg-vig` | Nutze dies bei Ifg 067 Vig Lebensmittel Und Produkte Antrag F, Ifg 068 Vig Lebensmittel Und Produkte Zustaend, Ifg 070 Vig Lebensmittel Und Produkte Kosten D, Ifg 071 Vig Lebensmittel Und Produkte Schwaerz: führt durch diese fachlich ver... |
| `ifg-vig-ifg-vig-ifg-vig-ifg-vig-02` | Nutze dies bei Ifg 072 Vig Lebensmittel Und Produkte Drittanh, Ifg 073 Vig Lebensmittel Und Produkte Widerspr, Ifg 074 Vig Lebensmittel Und Produkte Klage Vo, Ifg 075 Vig Lebensmittel Und Produkte Pressean: führt durch diese fachlich ver... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
