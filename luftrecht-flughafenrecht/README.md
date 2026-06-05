# Luftrecht und Flughafenrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`luftrecht-flughafenrecht`) | [`luftrecht-flughafenrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/luftrecht-flughafenrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Luftrechtsakte** (`luftrecht-airline-insolvenz-flugzeugpfand-flughafen`) | [Gesamt-PDF lesen](../testakten/luftrecht-airline-insolvenz-flugzeugpfand-flughafen/gesamt-pdf/luftrecht-airline-insolvenz-flugzeugpfand-flughafen_gesamt.pdf) | [`testakte-luftrecht-airline-insolvenz-flugzeugpfand-flughafen.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-luftrecht-airline-insolvenz-flugzeugpfand-flughafen.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Dieses Plugin deckt ziviles und öffentliches Luftrecht ab: Luftfahrzeug, Flughafen, Betriebsgenehmigung, LBA, Luftsicherheit, Slots, Flugzeugfinanzierung, Registerpfandrechte, Pfändung, Airline-Krise und internationale Bezüge.

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
| `allgemein` | Luftrecht und Flughafenrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Spezialskill-Routing und erste Ausgabe. |
| `luft-001-kaltstart-luftrechtsmandat` | 'Mandant erscheint erstmals mit Luftrechtsfall: Airline-Insolvenz Flugzeugbeschlagnahme Slot-Verlust oder Planfeststellungsklage. Klaert Zustaendigkeit LBA vs. Landesbehoerde vs. Gericht sichert Fristen LuftVG §§ 20 ff. und EU-Recht und... |
| `luft-acc3-genehmigung-sicherheitsauflage` | Nutze dies, wenn Luft 095 Acc3 Genehmigung Prüfen, Luft 096 Acc3 Sicherheitsauflage Bewerten, Luft 097 Acc3 Insolvenzrisiko Markieren, Luft 098 Acc3 Local Counsel Briefen, Luft 099 Acc3 Dashboard Bauen im Plugin Luftrecht Flughafenrecht... |
| `luft-acc3-mandantenmemo-slot-register` | Nutze dies, wenn Luft 100 Acc3 Mandantenmemo Schreiben, Luft 102 Slot Register Auswerten, Luft 103 Slot Pfandrecht Vorbereiten, Luft 104 Slot Pfaendung Planen, Luft 105 Slot Genehmigung Prüfen im Plugin Luftrecht Flughafenrecht konkret b... |
| `luft-aircraft-arrest-airline-finanzielle` | Nutze dies, wenn Luft 007 Aircraft Arrest International, Luft 008 Airline Finanzielle Leistungsfaehigkei, Luft 009 Betriebsgenehmigung Airline, Luft 010 Flughafen Planfeststellung, Luft 011 Slots Und Koordination im Plugin Luftrecht Flug... |
| `luft-airline-local-dashboard-bauen` | Nutze dies, wenn Luft 028 Airline Local Counsel Briefen, Luft 029 Airline Dashboard Bauen, Luft 030 Airline Mandantenmemo Schreiben, Luft 032 Flughafen Register Auswerten, Luft 033 Flughafen Pfandrecht Vorbereiten im Plugin Luftrecht Flu... |
| `luft-airline-pfandrecht-pfaendung-planen` | Nutze dies, wenn Luft 023 Airline Pfandrecht Vorbereiten, Luft 024 Airline Pfaendung Planen, Luft 025 Airline Genehmigung Prüfen, Luft 026 Airline Sicherheitsauflage Bewerten, Luft 027 Airline Insolvenzrisiko Markieren im Plugin Luftrech... |
| `luft-bodenabfertigung-insolvenzrisiko-local` | Nutze dies, wenn Luft 117 Bodenabfertigung Insolvenzrisiko Marki, Luft 118 Bodenabfertigung Local Counsel Briefen, Luft 119 Bodenabfertigung Dashboard Bauen im Plugin Luftrecht Flughafenrecht konkret bearbeitet werden soll. Auslöser: Bit... |
| `luft-bodenabfertigung-pruefe-luftvg` | Nutze dies, wenn Luft 111 Bodenabfertigung Zustaendigkeit Pruefe, Luft 002 Luftvg Anwendungsbereich, Luft 004 Flugzeugrolle Und Register, Luft 005 Luftfahrzeugpfandrecht, Luft 006 Pfaendung Flugzeug Deutschland im Plugin Luftrecht Flugha... |
| `luft-bodenabfertigung-register-pfandrecht` | Nutze dies, wenn Luft 112 Bodenabfertigung Register Auswerten, Luft 113 Bodenabfertigung Pfandrecht Vorbereite, Luft 114 Bodenabfertigung Pfaendung Planen, Luft 115 Bodenabfertigung Genehmigung Prüfen, Luft 116 Bodenabfertigung Sicherhei... |
| `luft-drohne-local-dashboard-bauen` | Nutze dies, wenn Luft 078 Drohne Local Counsel Briefen, Luft 079 Drohne Dashboard Bauen, Luft 080 Drohne Mandantenmemo Schreiben, Luft 082 Luftfracht Register Auswerten, Luft 083 Luftfracht Pfandrecht Vorbereiten im Plugin Luftrecht Flug... |
| `luft-drohne-pfandrecht-pfaendung-planen` | Nutze dies, wenn Luft 073 Drohne Pfandrecht Vorbereiten, Luft 074 Drohne Pfaendung Planen, Luft 075 Drohne Genehmigung Prüfen, Luft 076 Drohne Sicherheitsauflage Bewerten, Luft 077 Drohne Insolvenzrisiko Markieren im Plugin Luftrecht Flu... |
| `luft-ersatzteillager-drohne-luftfracht-acc3` | Nutze dies, wenn Luft 061 Ersatzteillager Zustaendigkeit Prüfen, Luft 071 Drohne Zustaendigkeit Prüfen, Luft 081 Luftfracht Zustaendigkeit Prüfen, Luft 091 Acc3 Zustaendigkeit Prüfen, Luft 101 Slot Zustaendigkeit Prüfen im Plugin Luftrec... |
| `luft-ersatzteillager-insolvenzrisiko-local` | Nutze dies, wenn Luft 067 Ersatzteillager Insolvenzrisiko Markie, Luft 068 Ersatzteillager Local Counsel Briefen, Luft 069 Ersatzteillager Dashboard Bauen, Luft 070 Ersatzteillager Mandantenmemo Schreibe, Luft 072 Drohne Register Auswert... |
| `luft-ersatzteillager-register-pfandrecht` | Nutze dies, wenn Luft 062 Ersatzteillager Register Auswerten, Luft 063 Ersatzteillager Pfandrecht Vorbereiten, Luft 064 Ersatzteillager Pfaendung Planen, Luft 065 Ersatzteillager Genehmigung Prüfen, Luft 066 Ersatzteillager Sicherheitsau... |
| `luft-flughafen-dashboard-mandantenmemo` | Nutze dies, wenn Luft 039 Flughafen Dashboard Bauen, Luft 040 Flughafen Mandantenmemo Schreiben, Luft 042 Flugzeugleasing Register Auswerten, Luft 043 Flugzeugleasing Pfandrecht Vorbereiten, Luft 044 Flugzeugleasing Pfaendung Planen im P... |
| `luft-flughafen-pfaendung-genehmigung` | Nutze dies, wenn Luft 034 Flughafen Pfaendung Planen, Luft 035 Flughafen Genehmigung Prüfen, Luft 036 Flughafen Sicherheitsauflage Bewerten, Luft 037 Flughafen Insolvenzrisiko Markieren, Luft 038 Flughafen Local Counsel Briefen im Plugin... |
| `luft-fluglaerm-anwohner-insolvenz` | Nutze dies, wenn Luft 017 Fluglaerm Und Anwohner, Luft 018 Insolvenz Fluggesellschaft, Luft 019 Leasing Und Cape Town Bezuege, Luft 020 Aviation Dashboard, Luft 022 Airline Register Auswerten im Plugin Luftrecht Flughafenrecht konkret be... |
| `luft-flugzeugleasing-genehmigung` | Nutze dies, wenn Luft 045 Flugzeugleasing Genehmigung Prüfen, Luft 046 Flugzeugleasing Sicherheitsauflage Bew, Luft 047 Flugzeugleasing Insolvenzrisiko Markie, Luft 048 Flugzeugleasing Local Counsel Briefen, Luft 049 Flugzeugleasing Dash... |
| `luft-flugzeugleasing-mandantenmemo` | Nutze dies, wenn Luft 050 Flugzeugleasing Mandantenmemo Schreibe, Luft 052 Registerpfandrecht Register Auswerten, Luft 053 Registerpfandrecht Pfandrecht Vorberei, Luft 054 Registerpfandrecht Pfaendung Planen, Luft 055 Registerpfandrecht... |
| `luft-lba-airline-flughafen-flugzeugleasing` | Nutze dies, wenn Luft 003 Lba Zustaendigkeit Prüfen, Luft 021 Airline Zustaendigkeit Prüfen, Luft 031 Flughafen Zustaendigkeit Prüfen, Luft 041 Flugzeugleasing Zustaendigkeit Prüfen, Luft 051 Registerpfandrecht Zustaendigkeit Prue im Plu... |
| `luft-luftfracht-dashboard-mandantenmemo` | Nutze dies, wenn Luft 089 Luftfracht Dashboard Bauen, Luft 090 Luftfracht Mandantenmemo Schreiben, Luft 092 Acc3 Register Auswerten, Luft 093 Acc3 Pfandrecht Vorbereiten, Luft 094 Acc3 Pfaendung Planen im Plugin Luftrecht Flughafenrecht... |
| `luft-luftfracht-pfaendung-genehmigung` | Nutze dies, wenn Luft 084 Luftfracht Pfaendung Planen, Luft 085 Luftfracht Genehmigung Prüfen, Luft 086 Luftfracht Sicherheitsauflage Bewerten, Luft 087 Luftfracht Insolvenzrisiko Markieren, Luft 088 Luftfracht Local Counsel Briefen im P... |
| `luft-luftsicherheit-luftsig` | Nutze dies, wenn Luft 012 Luftsicherheit Luftsig, Luft 013 Zuverlaessigkeitsueberpruefung, Luft 014 Drohnen Uas Betrieb, Luft 015 Gefahrgut Luftfracht, Luft 016 Passagierrechte Schnittstelle im Plugin Luftrecht Flughafenrecht konkret bea... |
| `luft-registerpfandrecht-sicherheitsauflage` | Nutze dies, wenn Luft 056 Registerpfandrecht Sicherheitsauflage, Luft 057 Registerpfandrecht Insolvenzrisiko Mar, Luft 058 Registerpfandrecht Local Counsel Brief, Luft 059 Registerpfandrecht Dashboard Bauen, Luft 060 Registerpfandrecht M... |
| `luft-slot-sicherheitsauflage-insolvenzrisiko` | Nutze dies, wenn Luft 106 Slot Sicherheitsauflage Bewerten, Luft 107 Slot Insolvenzrisiko Markieren, Luft 108 Slot Local Counsel Briefen, Luft 109 Slot Dashboard Bauen, Luft 110 Slot Mandantenmemo Schreiben im Plugin Luftrecht Flughafenr... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
