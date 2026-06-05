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

Beginne mit `luftrecht-flughafenrecht-allgemein`. Das Plugin fragt zuerst nach Rolle, Ziel, Frist, Behörde/Gericht/Register, vorhandenen Unterlagen und gewünschtem Output. Danach schlägt es die passenden Spezialskills aus diesem Plugin vor.

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
| `luft-001-kaltstart-luftrechtsmandat` | 'Mandant erscheint erstmals mit Luftrechtsfall: Airline-Insolvenz Flugzeugbeschlagnahme Slot-Verlust oder Planfeststellungsklage. Klaert Zustaendigkeit LBA vs. Landesbehoerde vs. Gericht sichert Fristen LuftVG §§ 20 ff. und EU-Recht und... |
| `luft-acc3-genehmigung-sicherheitsauflage` | Luft Acc3 Genehmigung Sicherheitsauflage im Plugin Luftrecht Flughafenrecht: prüft konkret ACC3-Carrier prueft Designierungsstatus und ob alle, ACC3-Carrier erhaelt Sicherheitsauflage nach, ACC3-Carrier zeigt Insolvenzzeichen, Deutsches... |
| `luft-acc3-mandantenmemo-slot-register` | Luft Acc3 Mandantenmemo Slot Register im Plugin Luftrecht Flughafenrecht: prüft konkret Anwalt schreibt Mandantenmemo fuer ACC3-Carrier zu, Mandant will Slot-Bestand einer Airline fuer Sommer- oder, Kreditgeber fragt ob Slots als Sicherh... |
| `luft-aircraft-arrest-airline-finanzielle` | Luft Aircraft Arrest Airline Finanzielle im Plugin Luftrecht Flughafenrecht: prüft konkret Mandant will Flugzeug im Ausland arrestieren oder, LBA prueft finanzielle Leistungsfaehigkeit nach EU-VO, Airline beantragt Betriebsgenehmigung be... |
| `luft-airline-local-dashboard-bauen` | Luft Airline Local Dashboard Bauen im Plugin Luftrecht Flughafenrecht: prüft konkret Deutsches Kanzleiteam muss auslaendischen Anwalt fuer, Kanzlei oder Mandant braucht operatives Airline-Dashboard, Anwalt schreibt Mandantenmemo fuer Air... |
| `luft-airline-pfandrecht-pfaendung-planen` | Luft Airline Pfandrecht Pfaendung Planen im Plugin Luftrecht Flughafenrecht: prüft konkret Kreditgeber will Pfandrecht an Airline-Flugzeug bestellen, Glaeubiger plant Zwangsvollstreckung in Airline-Flugzeug, Airline-Genehmigungsstand ist... |
| `luft-bodenabfertigung-insolvenzrisiko-local` | Luft Bodenabfertigung Insolvenzrisiko Local im Plugin Luftrecht Flughafenrecht: prüft konkret Bodenabfertigungsunternehmen zeigt Insolvenzzeichen, Deutsches Kanzleiteam muss auslaendischen Anwalt fuer, Flughafen oder Bodenabfertigungsunt... |
| `luft-bodenabfertigung-pruefe-luftvg` | Luft Bodenabfertigung Pruefe Luftvg im Plugin Luftrecht Flughafenrecht: prüft konkret Bodenabfertigungs-Mandat, Mandant fragt ob LuftVG gilt, Mandant will Luftfahrzeugrolle abfragen Eigentuemer klaeren, Kreditgeber sichert Flugzeugfinanz... |
| `luft-bodenabfertigung-register-pfandrecht` | Luft Bodenabfertigung Register Pfandrecht im Plugin Luftrecht Flughafenrecht: prüft konkret Mandant will Zulassungsstatus und Entgelt-Tarife von, Kreditgeber will Pfandrecht an Bodenabfertigungs-Equipment, Glaeubiger will Bodenabfertigun... |
| `luft-drohne-local-dashboard-bauen` | Luft Drohne Local Dashboard Bauen im Plugin Luftrecht Flughafenrecht: prüft konkret Deutsches Kanzleiteam muss auslaendischen Anwalt fuer, Drohnenbetreiber oder Regulierer braucht Dashboard fuer, Anwalt schreibt Mandantenmemo fuer Drohne... |
| `luft-drohne-pfandrecht-pfaendung-planen` | Luft Drohne Pfandrecht Pfaendung Planen im Plugin Luftrecht Flughafenrecht: prüft konkret Kreditgeber will Pfandrecht an teurer Drohne oder, Glaeubiger will gewerbliche Drohne oder Drohnenflotte, Drohnenbetreiber braucht Genehmigung fuer... |
| `luft-ersatzteillager-drohne-luftfracht-acc3` | Luft Ersatzteillager Drohne Luftfracht Acc3 im Plugin Luftrecht Flughafenrecht: prüft konkret Ersatzteillager fuer Luftfahrzeuge, Drohnen-Mandat, Luftfracht-Mandat, ACC3-Mandat. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampe... |
| `luft-ersatzteillager-insolvenzrisiko-local` | Luft Ersatzteillager Insolvenzrisiko Local im Plugin Luftrecht Flughafenrecht: prüft konkret MRO-Betrieb oder Airline mit grossem Ersatzteillager zeigt, Deutsches Kanzleiteam muss auslaendischen Anwalt fuer, MRO-Gesellschaft oder Airline... |
| `luft-ersatzteillager-register-pfandrecht` | Luft Ersatzteillager Register Pfandrecht im Plugin Luftrecht Flughafenrecht: prüft konkret Mandant will Register-/Inventar-Status fuer, Kreditgeber will Pfandrecht an Ersatzteillager und, Glaeubiger will Ersatzteillager oder einzelne Flu... |
| `luft-flughafen-dashboard-mandantenmemo` | Luft Flughafen Dashboard Mandantenmemo im Plugin Luftrecht Flughafenrecht: prüft konkret Kanzlei oder Mandant braucht Dashboard fuer Flughafen-Mandat, Anwalt schreibt Mandantenmemo fuer Flughafen-Betreiber oder, Mandant will Register zu... |
| `luft-flughafen-pfaendung-genehmigung` | Luft Flughafen Pfaendung Genehmigung im Plugin Luftrecht Flughafenrecht: prüft konkret Glaeubiger will Flughafen-Grundstuecke oder, Flughafenbetriebsgenehmigung ist unklar, Flughafen erhaelt LuftSiG-Bescheid mit Sicherheitsauflagen, Regi... |
| `luft-fluglaerm-anwohner-insolvenz` | Luft Fluglaerm Anwohner Insolvenz im Plugin Luftrecht Flughafenrecht: prüft konkret Anwohner klagt gegen Fluglaerm oder Flughafen baut, Airline-Insolvenz, Wet-Lease Dry-Lease oder Finance-Lease eines Flugzeugs mit, Mandant braucht Echtze... |
| `luft-flugzeugleasing-genehmigung` | Luft Flugzeugleasing Genehmigung im Plugin Luftrecht Flughafenrecht: prüft konkret Genehmigungsstand fuer geleastes Flugzeug pruefen, Geleaste Flugzeuge unterliegen Sicherheitsauflagen die, Leasinggeber oder Leasingnehmer zeigt Insolvenz... |
| `luft-flugzeugleasing-mandantenmemo` | Luft Flugzeugleasing Mandantenmemo im Plugin Luftrecht Flughafenrecht: prüft konkret Anwalt schreibt Mandantenmemo fuer Leasinggeber oder, Mandant will Pfandrechtsregister AG Braunschweig und, Glaeubigerbank will Pfandrecht an Luftfahrze... |
| `luft-lba-airline-flughafen-flugzeugleasing` | Luft LBA Airline Flughafen Flugzeugleasing im Plugin Luftrecht Flughafenrecht: prüft konkret Mandant erhaelt LBA-Bescheid oder fragt ob LBA oder, Airline-Mandat, Flughafen-Mandat, Flugzeugleasing-Mandat. Liefert priorisierten Output mit... |
| `luft-luftfracht-dashboard-mandantenmemo` | Luft Luftfracht Dashboard Mandantenmemo im Plugin Luftrecht Flughafenrecht: prüft konkret Luftfrachtfuehrer oder grosser Spediteur braucht Dashboard, Anwalt schreibt Mandantenmemo fuer Luftfrachtfuehrer oder, Mandant will ACC3-Designieru... |
| `luft-luftfracht-pfaendung-genehmigung` | Luft Luftfracht Pfaendung Genehmigung im Plugin Luftrecht Flughafenrecht: prüft konkret Glaeubiger will Luftfracht oder Luftfrachtansprueche, Luftfrachtfuehrer oder Spediteur fraucht Genehmigung, Luftfrachtfuehrer oder Spediteur erhaelt... |
| `luft-luftsicherheit-luftsig` | Luft Luftsicherheit Luftsig im Plugin Luftrecht Flughafenrecht: prüft konkret Flughafen oder Airline klaert Sicherheitspflichten oder, Person wurde Zuverlässigkeit nach LuftSiG § 7 versagt oder, Drohnenbetreiber braucht Betriebsgenehmigu... |
| `luft-registerpfandrecht-sicherheitsauflage` | Luft Registerpfandrecht Sicherheitsauflage im Plugin Luftrecht Flughafenrecht: prüft konkret Pfandrecht-Glaeubigers Sicherheiten werden durch, Schuldner zeigt Insolvenzzeichen, Deutsches Kanzleiteam muss auslaendischen Anwalt fuer, Pfand... |
| `luft-slot-sicherheitsauflage-insolvenzrisiko` | Luft Slot Sicherheitsauflage Insolvenzrisiko im Plugin Luftrecht Flughafenrecht: prüft konkret Slot-Zuweisung ist mit Auflagen verbunden oder Slot-Nutzung, Insolvente oder insolvenznahe Airline hat wertvolle, Deutsches Kanzleiteam muss a... |
| `luftrecht-flughafenrecht-kaltstart-triage` | Luftrecht und Flughafenrecht: Kaltstart, Aktenlandkarte, Rollenklärung, Fristen, Quellenprüfung, Fachmodul-Routing und erste Ausgabe. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
