# See- und Schifffahrtsrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`seerecht-schifffahrtsrecht`) | [`seerecht-schifffahrtsrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/seerecht-schifffahrtsrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Schifffahrtsakte** (`seerecht-schiffshypothek-werft-wrack-bermuda`) | [Gesamt-PDF lesen](../testakten/seerecht-schiffshypothek-werft-wrack-bermuda/gesamt-pdf/seerecht-schiffshypothek-werft-wrack-bermuda_gesamt.pdf) | [`testakte-seerecht-schiffshypothek-werft-wrack-bermuda.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-seerecht-schiffshypothek-werft-wrack-bermuda.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin verbindet deutsches Seehandels- und Registerrecht mit internationaler Schifffahrtspraxis: Schiffbau, Verkauf, Finanzierung, Schiffshypothek, Arrest, Wrack/Bergung, Charter, Kollision, Insolvenz und ITLOS/UNCLOS.

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

Automatisch generierte Komplett-Liste aller 26 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `allgemein` | See- und Schifffahrtsrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |
| `see-001-kaltstart-schifffahrtsmandat` | 'Erstkontakt mit Schifffahrtsmandat: Mandant meldet Schiffsunfall; Arrest oder neues Mandat. Sofort-Triage nach HGB §§ 476-480 (Reeder/Ausruester); SchRG §§ 8-74 (Hypothek); UNCLOS Art. 94 (Flaggenstaat); ISM-Code. Klaert Schiffstyp; Fla... |
| `see-auslandsflagge-local-insolvenz-reederei` | Nutze dies bei See 012 Auslandsflagge Und Local Counsel, See 014 Insolvenz Der Reederei, See 015 Versicherung P I Hull, See 016 Hafenrecht Und Liegegeld: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und lie... |
| `see-bermuda-see-seeschiff-see-schiffsregister` | Nutze dies bei See 013 Bermuda Struktur Prüfen, See 002 Seeschiff Oder Binnenschiff, See 003 Schiffsregister Und Eigentum, See 004 Schiffshypothek Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und li... |
| `see-binnenschiff-arrest-wrackpflicht` | Nutze dies bei See 084 Binnenschiff Arrest Vorbereiten, See 085 Binnenschiff Wrackpflicht Prüfen, See 086 Binnenschiff Versicherung Melden, See 087 Binnenschiff Local Counsel Instruieren: führt durch diese fachlich verbundenen Module, wä... |
| `see-binnenschiff-see-see-kreuzfahrtschiff-see` | Nutze dies bei See 089 Binnenschiff Klagepfad Waehlen, See 090 Binnenschiff Risiko Memo Schreiben, See 091 Kreuzfahrtschiff Register Prüfen, See 092 Kreuzfahrtschiff Hypothek Bestellen: führt durch diese fachlich verbundenen Module, wähl... |
| `see-charterparty-local-closing-planen` | Nutze dies bei See 117 Charterparty Local Counsel Instruieren, See 118 Charterparty Closing Planen, See 119 Charterparty Klagepfad Waehlen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächs... |
| `see-charterparty-register-hypothek-bestellen` | Nutze dies bei See 111 Charterparty Register Prüfen, See 112 Charterparty Hypothek Bestellen, See 114 Charterparty Arrest Vorbereiten, See 115 Charterparty Wrackpflicht Prüfen: führt durch diese fachlich verbundenen Module, wählt den pas... |
| `see-charterparty-see-fracht-see-havarie-see` | Nutze dies bei See 007 Charterparty Einordnen, See 008 Fracht Und Konnossement, See 009 Havarie Und Kollision, See 010 Bergung Und Wrack: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefert den nächste... |
| `see-containerschiff-local-closing-planen` | Nutze dies bei See 067 Containerschiff Local Counsel Instruie, See 068 Containerschiff Closing Planen, See 069 Containerschiff Klagepfad Waehlen, See 070 Containerschiff Risiko Memo Schreiben: führt durch diese fachlich verbundenen Modul... |
| `see-containerschiff-register-hypothek` | Nutze dies bei See 061 Containerschiff Register Prüfen, See 062 Containerschiff Hypothek Bestellen, See 064 Containerschiff Arrest Vorbereiten, See 065 Containerschiff Wrackpflicht Prüfen: führt durch diese fachlich verbundenen Module, w... |
| `see-konnossement-versicherung-local-counsel` | Nutze dies bei See 106 Konnossement Versicherung Melden, See 107 Konnossement Local Counsel Instruieren, See 108 Konnossement Closing Planen, See 109 Konnossement Klagepfad Waehlen: führt durch diese fachlich verbundenen Module, wählt de... |
| `see-kreuzfahrtschiff-see-konnossement-see-see` | Nutze dies bei See 100 Kreuzfahrtschiff Risiko Memo Schreiben, See 101 Konnossement Register Prüfen, See 102 Konnossement Hypothek Bestellen, See 104 Konnossement Arrest Vorbereiten: führt durch diese fachlich verbundenen Module, wählt d... |
| `see-kreuzfahrtschiff-wrackpflicht` | Nutze dies bei See 095 Kreuzfahrtschiff Wrackpflicht Prüfen, See 096 Kreuzfahrtschiff Versicherung Melden, See 097 Kreuzfahrtschiff Local Counsel Instrui, See 098 Kreuzfahrtschiff Closing Planen: führt durch diese fachlich verbundenen Mo... |
| `see-offshore-schiff-arrest-vorbereiten` | Nutze dies bei See 072 Offshore Schiff Hypothek Bestellen, See 074 Offshore Schiff Arrest Vorbereiten, See 075 Offshore Schiff Wrackpflicht Prüfen, See 076 Offshore Schiff Versicherung Melden: führt durch diese fachlich verbundenen Modul... |
| `see-offshore-schiff-klagepfad-waehlen-risiko` | Nutze dies bei See 078 Offshore Schiff Closing Planen, See 079 Offshore Schiff Klagepfad Waehlen, See 080 Offshore Schiff Risiko Memo Schreiben, See 081 Binnenschiff Register Prüfen: führt durch diese fachlich verbundenen Module, wählt d... |
| `see-offshore-see-binnenschiff-see` | Nutze dies bei See 073 Offshore Schiff Kaufvertrag Scopen, See 083 Binnenschiff Kaufvertrag Scopen, See 093 Kreuzfahrtschiff Kaufvertrag Scopen, See 103 Konnossement Kaufvertrag Scopen: führt durch diese fachlich verbundenen Module, wähl... |
| `see-schiffbauvertrag-werft-schiffshypothek` | Nutze dies bei See 005 Schiffbauvertrag Werft, See 023 Schiffshypothek Kaufvertrag Scopen, See 033 Schiffbauwerk Kaufvertrag Scopen, See 041 Werftvertrag Register Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `see-schiffbauwerk-risiko-yachtkauf-register` | Nutze dies bei See 040 Schiffbauwerk Risiko Memo Schreiben, See 051 Yachtkauf Register Prüfen, See 052 Yachtkauf Hypothek Bestellen, See 054 Yachtkauf Arrest Vorbereiten: führt durch diese fachlich verbundenen Module, wählt den passenden... |
| `see-schiffbauwerk-wrackpflicht-versicherung` | Nutze dies bei See 035 Schiffbauwerk Wrackpflicht Prüfen, See 036 Schiffbauwerk Versicherung Melden, See 037 Schiffbauwerk Local Counsel Instruiere, See 038 Schiffbauwerk Closing Planen: führt durch diese fachlich verbundenen Module, wäh... |
| `see-schiffshypothek-arrest-wrackpflicht` | Nutze dies bei See 024 Schiffshypothek Arrest Vorbereiten, See 025 Schiffshypothek Wrackpflicht Prüfen, See 026 Schiffshypothek Versicherung Melden, See 027 Schiffshypothek Local Counsel Instruie: führt durch diese fachlich verbundenen M... |
| `see-schiffshypothek-klagepfad-risiko` | Nutze dies bei See 029 Schiffshypothek Klagepfad Waehlen, See 030 Schiffshypothek Risiko Memo Schreiben, See 031 Schiffbauwerk Register Prüfen, See 032 Schiffbauwerk Hypothek Bestellen: führt durch diese fachlich verbundenen Module, wähl... |
| `see-umwelt-marpol-itlos-hamburg-dokumenten` | Nutze dies bei See 018 Umwelt Und Marpol, See 019 Itlos Hamburg Und Unclos, See 020 Dokumenten Cockpit Schiff, See 021 Schiffshypothek Register Prüfen: führt durch diese fachlich verbundenen Module, wählt den passenden Prüfpfad und liefe... |
| `see-werftvertrag-closing-klagepfad-waehlen` | Nutze dies bei See 048 Werftvertrag Closing Planen, See 049 Werftvertrag Klagepfad Waehlen, See 050 Werftvertrag Risiko Memo Schreiben, See 053 Yachtkauf Kaufvertrag Scopen: führt durch diese fachlich verbundenen Module, wählt den passen... |
| `see-werftvertrag-kaufvertrag-arrest` | Nutze dies bei See 043 Werftvertrag Kaufvertrag Scopen, See 044 Werftvertrag Arrest Vorbereiten, See 045 Werftvertrag Wrackpflicht Prüfen, See 046 Werftvertrag Versicherung Melden: führt durch diese fachlich verbundenen Module, wählt den... |
| `see-yachtkauf-versicherung-local-counsel` | Nutze dies bei See 056 Yachtkauf Versicherung Melden, See 057 Yachtkauf Local Counsel Instruieren, See 058 Yachtkauf Closing Planen, See 059 Yachtkauf Klagepfad Waehlen: führt durch diese fachlich verbundenen Module, wählt den passenden... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
