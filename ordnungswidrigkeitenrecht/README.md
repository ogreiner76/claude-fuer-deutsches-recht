# Ordnungswidrigkeitenrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`ordnungswidrigkeitenrecht`) | [`ordnungswidrigkeitenrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/ordnungswidrigkeitenrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **OWiG-Akte** (`ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier`) | [Gesamt-PDF lesen](../testakten/ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier/gesamt-pdf/ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier_gesamt.pdf) | [`testakte-ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-ordnungswidrigkeitenrecht-bussgeldmix-gewerbe-datenschutz-tier.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin ist das allgemeine Betriebssystem für Bußgeldsachen, nicht nur Verkehr: OWiG-Verfahren, Fachordnungswidrigkeiten, Anhörung, Bußgeldbescheid, Einspruch, Akteneinsicht, Amtsgericht und Rechtsbeschwerde.

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
| `allgemein` | Ordnungswidrigkeitenrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |
| `owi-001-kaltstart-bussgeldverfahren` | Ordnungswidrigkeitenrecht: Kaltstart Bußgeldverfahren. Kaltstart Bußgeldverfahren im Fachgebiet Ordnungswidrigkeitenrecht als geführten Arbeitsgang mit Fragen, Dokumentenlogik und Ausgabeformat bearbeiten. |
| `owi-akteneinsicht-owi-verjaehrung-owi` | Nutze dies bei Owi 006 Akteneinsicht Beantragen, Owi 007 Verjaehrung Und Unterbrechung, Owi 008 Zustaendige Verwaltungsbehoerde, Owi 009 Opportunitaet Und Einstellung: führt durch diese fachlich verbundenen Module, wählt den passenden Pr... |
| `owi-amtsgericht-hauptverhandlung` | Nutze dies bei Owi 015 Amtsgericht Hauptverhandlung, Owi 017 Rechtsbeschwerde Prüfen, Owi 018 Kostenentscheidung Angreifen, Owi 020 Owig In Einfacher Sprache: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad un... |
| `owi-aussenwirtschaft-einspruch-einstellung` | Nutze dies bei Owi 094 Aussenwirtschaft Einspruch Begruenden, Owi 095 Aussenwirtschaft Einstellung Anregen, Owi 096 Aussenwirtschaft Beweis Ruegen, Owi 097 Aussenwirtschaft Verjaehrung Berechnen: führt durch diese fachlich verbundenen Mo... |
| `owi-aussenwirtschaft-owi-aussenwirtschaft` | Nutze dies bei Owi 098 Aussenwirtschaft Gerichtstermin Vorber, Owi 099 Aussenwirtschaft Rechtsbeschwerde Prue: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächsten belastbaren Arbeitsschritt. |
| `owi-baurecht-owi-strassenverkehr-owi` | Nutze dies bei Owi 072 Baurecht Frist Prüfen, Owi 082 Strassenverkehr Frist Prüfen, Owi 092 Aussenwirtschaft Frist Prüfen, Owi 004 Bussgeldbescheid Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und l... |
| `owi-baurecht-owi-strassenverkehr-owi-owi` | Nutze dies bei Owi 080 Baurecht Mandantenbrief Schreiben, Owi 081 Strassenverkehr Tatbestand Zerlegen, Owi 083 Strassenverkehr Akteneinsicht Schreibe, Owi 084 Strassenverkehr Einspruch Begruenden: führt durch diese fachlich verbundenen M... |
| `owi-baurecht-ruegen-verjaehrung-berechnen` | Nutze dies bei Owi 076 Baurecht Beweis Ruegen, Owi 077 Baurecht Verjaehrung Berechnen, Owi 078 Baurecht Gerichtstermin Vorbereiten, Owi 079 Baurecht Rechtsbeschwerde Prüfen: führt durch diese fachlich verbundenen Module, wählt den passen... |
| `owi-baurecht-zerlegen-akteneinsicht-schreiben` | Nutze dies bei Owi 071 Baurecht Tatbestand Zerlegen, Owi 073 Baurecht Akteneinsicht Schreiben, Owi 074 Baurecht Einspruch Begruenden, Owi 075 Baurecht Einstellung Anregen: führt durch diese fachlich verbundenen Module, wählt den passende... |
| `owi-datenschutzbussgeld-mandantenbrief-abgabe` | Nutze dies bei Owi 030 Datenschutzbussgeld Mandantenbrief Sch, Owi 014 Abgabe An Staatsanwaltschaft, Owi 002 Tatbestand Fachgesetz Finden, Owi 003 Anhoerung Richtig Behandeln: führt durch diese fachlich verbundenen Module, wählt den pass... |
| `owi-datenschutzbussgeld-owi-owi` | Nutze dies bei Owi 021 Datenschutzbussgeld Tatbestand Zerlege, Owi 023 Datenschutzbussgeld Akteneinsicht Schr, Owi 024 Datenschutzbussgeld Einspruch Begruend, Owi 025 Datenschutzbussgeld Einstellung Anrege: führt durch diese fachlich ver... |
| `owi-datenschutzbussgeld-owi-owi-02` | Nutze dies bei Owi 026 Datenschutzbussgeld Beweis Ruegen, Owi 027 Datenschutzbussgeld Verjaehrung Berech, Owi 028 Datenschutzbussgeld Gerichtstermin Vor, Owi 029 Datenschutzbussgeld Rechtsbeschwerde P: führt durch diese fachlich verbunde... |
| `owi-einspruch-owi-beschlussverfahren-owi` | Nutze dies bei Owi 005 Einspruch Fristgerecht Einlegen, Owi 016 Beschlussverfahren 72 Owig, Owi 019 Jugendliche Im Owi Verfahren, Owi 022 Datenschutzbussgeld Frist Prüfen: führt durch diese fachlich verbundenen Module, wählt den passende... |
| `owi-gewerberecht-frist-umwelt` | Nutze dies bei Owi 032 Gewerberecht Frist Prüfen, Owi 042 Umwelt Owi Frist Prüfen, Owi 052 Lebensmittelrecht Frist Prüfen, Owi 062 Tierschutz Owi Frist Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad u... |
| `owi-gewerberecht-mandantenbrief-umwelt` | Nutze dies bei Owi 040 Gewerberecht Mandantenbrief Schreiben, Owi 041 Umwelt Owi Tatbestand Zerlegen, Owi 043 Umwelt Owi Akteneinsicht Schreiben, Owi 044 Umwelt Owi Einspruch Begruenden: führt durch diese fachlich verbundenen Module, wäh... |
| `owi-gewerberecht-ruegen-verjaehrung-berechnen` | Nutze dies bei Owi 036 Gewerberecht Beweis Ruegen, Owi 037 Gewerberecht Verjaehrung Berechnen, Owi 038 Gewerberecht Gerichtstermin Vorbereite, Owi 039 Gewerberecht Rechtsbeschwerde Prüfen: führt durch diese fachlich verbundenen Module, w... |
| `owi-gewerberecht-zerlegen-akteneinsicht` | Nutze dies bei Owi 031 Gewerberecht Tatbestand Zerlegen, Owi 033 Gewerberecht Akteneinsicht Schreiben, Owi 034 Gewerberecht Einspruch Begruenden, Owi 035 Gewerberecht Einstellung Anregen: führt durch diese fachlich verbundenen Module, wä... |
| `owi-lebensmittelrecht-owi-owi` | Nutze dies bei Owi 054 Lebensmittelrecht Einspruch Begruenden, Owi 055 Lebensmittelrecht Einstellung Anregen, Owi 056 Lebensmittelrecht Beweis Ruegen, Owi 057 Lebensmittelrecht Verjaehrung Berechne: führt durch diese fachlich verbundenen... |
| `owi-lebensmittelrecht-owi-owi-02` | Nutze dies bei Owi 058 Lebensmittelrecht Gerichtstermin Vorbe, Owi 059 Lebensmittelrecht Rechtsbeschwerde Pru, Owi 060 Lebensmittelrecht Mandantenbrief Schre, Owi 061 Tierschutz Owi Tatbestand Zerlegen: führt durch diese fachlich verbund... |
| `owi-strassenverkehr-einstellung-ruegen` | Nutze dies bei Owi 085 Strassenverkehr Einstellung Anregen, Owi 086 Strassenverkehr Beweis Ruegen, Owi 087 Strassenverkehr Verjaehrung Berechnen, Owi 088 Strassenverkehr Gerichtstermin Vorbere: führt durch diese fachlich verbundenen Modu... |
| `owi-strassenverkehr-rechtsbeschwerde` | Nutze dies bei Owi 089 Strassenverkehr Rechtsbeschwerde Pruef, Owi 090 Strassenverkehr Mandantenbrief Schreib, Owi 091 Aussenwirtschaft Tatbestand Zerlegen, Owi 093 Aussenwirtschaft Akteneinsicht Schreib: führt durch diese fachlich verbu... |
| `owi-tierschutz-akteneinsicht-einspruch` | Nutze dies bei Owi 063 Tierschutz Owi Akteneinsicht Schreiben, Owi 064 Tierschutz Owi Einspruch Begruenden, Owi 065 Tierschutz Owi Einstellung Anregen, Owi 066 Tierschutz Owi Beweis Ruegen: führt durch diese fachlich verbundenen Module,... |
| `owi-tierschutz-verjaehrung-gerichtstermin` | Nutze dies bei Owi 067 Tierschutz Owi Verjaehrung Berechnen, Owi 068 Tierschutz Owi Gerichtstermin Vorberei, Owi 069 Tierschutz Owi Rechtsbeschwerde Pruefe, Owi 070 Tierschutz Owi Mandantenbrief Schreibe: führt durch diese fachlich verbu... |
| `owi-umwelt-einstellung-ruegen-verjaehrung` | Nutze dies bei Owi 045 Umwelt Owi Einstellung Anregen, Owi 046 Umwelt Owi Beweis Ruegen, Owi 047 Umwelt Owi Verjaehrung Berechnen, Owi 048 Umwelt Owi Gerichtstermin Vorbereiten: führt durch diese fachlich verbundenen Module, wählt den pa... |
| `owi-umwelt-owi-owi-lebensmittelrecht-owi` | Nutze dies bei Owi 049 Umwelt Owi Rechtsbeschwerde Prüfen, Owi 050 Umwelt Owi Mandantenbrief Schreiben, Owi 051 Lebensmittelrecht Tatbestand Zerlegen, Owi 053 Lebensmittelrecht Akteneinsicht Schrei: führt durch diese fachlich verbundenen... |
| `owi-unternehmen-verbandsgeldbusse` | Nutze dies bei Owi 010 Unternehmen Und Verbandsgeldbusse, Owi 011 Aufsichtspflichtverletzung 130 Owig, Owi 012 Einziehung Und Verfall Prüfen, Owi 013 Nebenfolgen Und Register: führt durch diese fachlich verbundenen Module, wählt den pass... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
