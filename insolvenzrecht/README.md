# Insolvenzrecht-Plugin

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`insolvenzrecht`) | [`insolvenzrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/insolvenzrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Fortbestehensprognose Paragrafix GmbH** (`fortbestehensprognose-paragrafix-gmbh`) | [Gesamt-PDF lesen](../testakten/fortbestehensprognose-paragrafix-gmbh/gesamt-pdf/fortbestehensprognose-paragrafix-gmbh_gesamt.pdf) | [`testakte-fortbestehensprognose-paragrafix-gmbh.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-fortbestehensprognose-paragrafix-gmbh.zip) |
| **LUMEN Studios GmbH — Insolvenz- und Wirtschaftsstrafverfahren** (`lumen-studios-insolvenz-strafverfahren`) | [Gesamt-PDF lesen](../testakten/lumen-studios-insolvenz-strafverfahren/gesamt-pdf/lumen-studios-insolvenz-strafverfahren_gesamt.pdf) | [`testakte-lumen-studios-insolvenz-strafverfahren.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-lumen-studios-insolvenz-strafverfahren.zip) |
| **Projekt Nachtfalter — Private Equity Buyout, Schuldschein und NPL-Portfolio** (`private-equity-buyout-schuldschein-npl-heidelberg`) | [Gesamt-PDF lesen](../testakten/private-equity-buyout-schuldschein-npl-heidelberg/gesamt-pdf/private-equity-buyout-schuldschein-npl-heidelberg_gesamt.pdf) | [`testakte-private-equity-buyout-schuldschein-npl-heidelberg.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-private-equity-buyout-schuldschein-npl-heidelberg.zip) |
| **Sanierungsgewinn im Insolvenzplan — Grossbach Druckguss & Präzision GmbH & Co. KG Erfurt (2026)** (`sanierungsgewinn-insolvenzplan-grossbach-druckguss-erfurt-2026`) | [Gesamt-PDF lesen](../testakten/sanierungsgewinn-insolvenzplan-grossbach-druckguss-erfurt-2026/gesamt-pdf/sanierungsgewinn-insolvenzplan-grossbach-druckguss-erfurt-2026_gesamt.pdf) | [`testakte-sanierungsgewinn-insolvenzplan-grossbach-druckguss-erfurt-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-sanierungsgewinn-insolvenzplan-grossbach-druckguss-erfurt-2026.zip) |
| **Sanierungsgewinn bei solventer GmbH-Liquidation — Strassburger Handelshof GmbH (Berlin-Charlottenburg)** (`sanierungsgewinn-solvente-liquidation-strassburger-handelshof-2026`) | [Gesamt-PDF lesen](../testakten/sanierungsgewinn-solvente-liquidation-strassburger-handelshof-2026/gesamt-pdf/sanierungsgewinn-solvente-liquidation-strassburger-handelshof-2026_gesamt.pdf) | [`testakte-sanierungsgewinn-solvente-liquidation-strassburger-handelshof-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-sanierungsgewinn-solvente-liquidation-strassburger-handelshof-2026.zip) |
| **Sanierungsgewinn im StaRUG-Plan — Pellbach Windenergie GmbH Brandenburg (2026)** (`sanierungsgewinn-starug-plan-windenergie-pellbach-2026`) | [Gesamt-PDF lesen](../testakten/sanierungsgewinn-starug-plan-windenergie-pellbach-2026/gesamt-pdf/sanierungsgewinn-starug-plan-windenergie-pellbach-2026_gesamt.pdf) | [`testakte-sanierungsgewinn-starug-plan-windenergie-pellbach-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-sanierungsgewinn-starug-plan-windenergie-pellbach-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Insolvenz- und sanierungsrechtliche Skills nach deutschem Recht (InsO, StaRUG, COVInsAG-Nachwirkungen). Zielgruppe: Insolvenzverwalter, beratende Rechtsanwälte (Insolvenz-/Sanierungsrecht), Geschäftsführer, Vorstände, Sanierungsberater, Wirtschaftsprüfer (IDW-S-11-/S-6-/S-9-Praxis).


## Enthaltene Skills

| Skill | Zweck |
|---|---|
| `zahlungsunfaehigkeit-pruefung-17-inso` | Prüfung der Zahlungsunfähigkeit gem. § 17 InsO anhand BGH-Liquiditätsstatus (10%-/3-Wochen-Schwelle) |
| `ueberschuldung-pruefung-19-inso` | Zweistufige Überschuldungsprüfung gem. § 19 InsO: Fortbestehensprognose + insolvenzrechtlicher Überschuldungsstatus |
| `liquiditaetsvorschau-insolvenzrechtlich` | Rollierende 13-/26-/52-Wochen-Liquiditätsvorschau mit Ampel als Beweismittel für § 17 InsO und Fortbestehensprognose § 19 InsO; Excel-Export |
| `antragspflicht-15a-inso` | Höchstfrist nach § 15a InsO, Haftung bei Insolvenzverschleppung, Schutz Geschäftsführer/Vorstand |
| `glaeubigerantrag-pruefung` | Prüfung Zulässigkeit/Begründetheit eines Gläubigerantrags (§ 14 InsO), Glaubhaftmachung Forderung + Eröffnungsgrund |

## Abgrenzung zu den Schwester-Plugins

- Rechtsprechung live prüfen: Keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über amtliche oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

Dieses Plugin `insolvenzrecht` ist **gerichtsfähig-formal** ausgerichtet: Es liefert die rechtlichen Subsumtionsbausteine und Beweismittel, wenn die Krise bereits eingetreten ist — Zeitpunkt der Zahlungsunfähigkeit, Überschuldungsstatus zum Stichtag, Antragspflichtfrist, Haftung Geschäftsleiter.

## Rechtlicher Rahmen (übergreifend)

- **InsO**: §§ 14, 15, 15a, 16, 17, 18, 19, 130, 131, 133, 142
- **StaRUG**: §§ 29 ff. (Restrukturierungsverfahren), § 102 (Hinweispflicht)
- **GmbHG**: § 64 a.F. (ersetzt durch § 15b InsO), § 30 (Auszahlungsverbot)
- **AktG**: § 92 Abs. 2 (Anzeigepflichten), § 93 (Sorgfaltspflicht)
- **HGB**: § 252 Abs. 1 Nr. 2 (going concern)
- **StGB**: §§ 283–283d (Bankrott, Verletzung der Buchführungspflicht), § 266a (Vorenthalten Arbeitsentgelt)

## Leitentscheidungen

- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

## Quellenregel

Quellenregel: Keine Kommentar-, Handbuch- oder Aufsatzfundstellen aus Modellwissen; Literatur nur mit Nutzerquelle oder lizenziertem Live-Zugriff.
## Lizenz

Doppellizenziert unter Apache License, Version 2.0 ODER MIT License, nach Wahl der Nutzerin / des Nutzers (`SPDX-License-Identifier: Apache-2.0 OR MIT`). Siehe `LICENSE`, `LICENSE-APACHE`, `LICENSE-MIT` und `NOTICE` im Repository-Wurzelverzeichnis.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 29 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anfechtungsrechte-antragspflicht-15a` | Anfechtungsrechte Antragspflicht 15A im Plugin Insolvenzrecht: prüft konkret Insolvenzverwalter klagt auf Rückgewaehr einer Zahlung vor, Analysiert die Insolvenzantragspflicht des Geschäftsleiters, die, Register- und Grundbuchvollzug bei... |
| `feststellung-sonderfall-glaeubigerantrag-inso` | Feststellung Sonderfall Glaeubigerantrag Inso im Plugin Insolvenzrecht: prüft konkret Feststellung, Glaeubigerantrag, InsO, Insolvenzrecht. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `glaeubigerantrag-glaeubigerausschuss` | Glaeubigerantrag Glaeubigerausschuss im Plugin Insolvenzrecht: prüft konkret Prüft Zulässigkeit und Begründetheit eines Gläubigerantrags, Mandant ist Mitglied des Gläubiger-ausschusses oder soll in, Art, Checkliste Eroeffnungsantrag § 13... |
| `glaeubigerausschuss-fristennotiz` | Glaeubigerausschuss Fristennotiz im Plugin Insolvenzrecht: prüft konkret Glaeubigerausschuss, Ueberschuldung, Insolvenzverwalter verklagt Geschäftsführer und, Haftung des Insolvenzverwalters und Sachwalters nach. Liefert priorisierten Ou... |
| `inso-gerichtliche-aufsichtswege` | Inso Gerichtliche Aufsichtswege im Plugin Insolvenzrecht: prüft konkret Rechtsdurchsetzung gegen Auskunfteien, Glaeubigerausschuss in der Praxis, Spezialfall Glaeubigerausschuss und Zustimmungsvorbehalte, Zusammenspiel öffentlicher Insol... |
| `inso-lma-facility-massearmut` | Inso LMA Facility Massearmut im Plugin Insolvenzrecht: prüft konkret Prüft syndizierte LMA-Finanzierung in Insolvenz/StaRUG, Spezialfall Massearmut und Massekostenmangel § 207 InsO, Belegpaket gegen negative Auskunfteieinträge, Praktisch... |
| `inso-npl-kreditkauf-restschuldbefreiung` | Inso NPL Kreditkauf Restschuldbefreiung im Plugin Insolvenzrecht: prüft konkret Prüft Kreditkauf notleidender Darlehen vor und im, Restschuldbefreiung Verbraucher und Unternehmer, SCHUFA-/Auskunfteieinträge nach Restschuldbefreiung lösch... |
| `inso-pl` | Inso PL im Plugin Insolvenzrecht: prüft konkret Mandantenkommunikation im Plugin insolvenzrecht, Red-Team Qualitygate im Plugin insolvenzrecht, Insolvenzrechtsverfahren einfuehrend, Finanzamt als Glaeubiger im Insolvenzverfahren. Liefert... |
| `inso-tabelle-verbraucherinsolvenz-leitfaden` | Inso Tabelle Verbraucherinsolvenz Leitfaden im Plugin Insolvenzrecht: prüft konkret Spezialfall Tabelle und Feststellung, Leitfaden Verbraucherinsolvenz §§ 304 ff, Rangruecktritt und Paragraph 5 Absatz 2a EStG im Insolvenz-, Arbeitnehmer... |
| `insol-sanierungsgewinn-7b-debt-equity` | Insol Sanierungsgewinn 7B Debt Equity im Plugin Insolvenzrecht: prüft konkret Gewerbesteuerliche Parallelregelung Paragraph 7b GewStG, Debt-Equity-Swap (DES) im Insolvenzplan und StaRUG-Plan, Eigenverwaltung nach Paragraph 270 InsO und d... |
| `insol-sanierungsgewinn-insolvenzreife` | Insol Sanierungsgewinn Insolvenzreife im Plugin Insolvenzrecht: prüft konkret Massehaftungsbefreiung und bilanzielle Verbuchung des, Insolvenzreife, Antragspflicht und Haftung, Paragraph 3a EStG im Insolvenzplan-Kontext (Paragraphen 217.... |
| `insol-sanierungsgewinn-liquidation` | Insol Sanierungsgewinn Liquidation im Plugin Insolvenzrecht: prüft konkret Wahlentscheidung Insolvenzplan versus Liquidation und die, Mandantenbrief an Insolvenzverwalter, Sachwalter, CRO und Schuldner zur rechtzei. Liefert priorisierten... |
| `insol-sanierungsgewinn-uebertragende` | Insol Sanierungsgewinn Uebertragende im Plugin Insolvenzrecht: prüft konkret Uebertragende Sanierung als Asset Deal (Paragraphen 159 ff, Stundung Paragraph 222 AO und Erlass Paragraph 227 AO als, Vorab-Pruefung der Verrechnungsreihenfolg... |
| `insolvenzrecht-anschluss` | Anschluss im Plugin Insolvenzrecht: prüft konkret Einstieg, Schnelltriage und Fallrouting im Insolvenzrecht-Plugin, Anschluss-Skills Router im Plugin insolvenzrecht, Chronologie und Belegmatrix im Plugin insolvenzrecht. Liefert priorisie... |
| `insolvenzrecht-antragspflicht-15a-17-19` | Antragspflicht 15A 17 19 im Plugin Insolvenzrecht: prüft konkret Antragspflicht, Belegmatrix, Chronologie, Einfuehrung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `insolvenzrecht-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `insolvenzrecht-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `insolvenzrecht-kaltstart-interview` | Kaltstart-Interview für das Insolvenzrecht-Plugin. Befüllt das Praxisprofil unter ~/.claude/plugins/config/claude-fuer-deutsches-recht/insolvenzrecht/CLAUDE.md mit Angaben zur Rolle (Insolvenzverwalter / Sachwalter / beratender Anwalt /... |
| `insolvenzrecht-output-waehlen` | Output wählen im Plugin Insolvenzrecht: Diese Output-Weiche für Insolvenzrecht entscheidet, ob Memo, Antrag, Schriftsatz, Tabelle, Risikoampel, Fragenliste oder Mandantenbrief der richtige nächste Schritt ist. |
| `insolvenzrecht-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `insolvenzrecht-rechtsquellen` | Rechtsquellen: Zahlen, Schwellenwerte und Berechnung im Insolvenzrecht: fachlich vertiefter Fachmodul mit Normenradar (InsO/StaRUG/GesR), Tatbestands-/Beweislastmatrix, Fristen- und Formcheck, Gegenargumenten, Fehlerbremse und direkt nut... |
| `insolvenzrecht-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `insolvenzrechtliche-livecheck-red-team` | Insolvenzrechtliche Livecheck RED Team im Plugin Insolvenzrecht: prüft konkret Insolvenzrechtliche, Livecheck, Mandat, Tabelle. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `internationales-drittstaaten-konzerninsolvenz` | Internationales Drittstaaten Konzerninsolvenz im Plugin Insolvenzrecht: prüft konkret Drittstaatliche Insolvenzverfahren in Deutschland prüfen, Mehrere Gesellschaften eines Konzerns sind insolvent und, Eingangs-Abfrage für insolvenzrecht... |
| `liquiditaetsvorschau-insolvenzrechtlich` | Erstellt und bewertet die rollierende Liquiditätsvorschau als strukturierte Arbeitsgrundlage für insolvenzrechtliche Tatbestände nach § 17 InsO (Zahlungsunfähigkeit) und § 19 Abs. 2 InsO (Fortbestehensprognose). Lädt, wenn geprüft werden... |
| `rechtsabteilung-lieferantenpool-npl` | Rechtsabteilung Lieferantenpool NPL im Plugin Insolvenzrecht: prüft konkret Rechtsabteilungs-Fachmodul für Lieferantenpool und, Rechtsabteilungs-Fachmodul für NPL-Käufer im, Rechtsabteilungs-Fachmodul für Schufa-Löschung nach, Rechtsabte... |
| `triage-verbraucherinsolvenz` | Triage Verbraucherinsolvenz im Plugin Insolvenzrecht: prüft konkret Triage, Verbraucherinsolvenz, Zahlungsunfaehigkeit, Führt die zweistufige Überschuldungsprüfung gem. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näc... |
| `uebertragende-sanierung-auslaendischer-office` | Uebertragende Sanierung Auslaendischer Office im Plugin Insolvenzrecht: prüft konkret Insolvenzverwalter will Geschäftsbetrieb verkaufen oder, Prüft, ob und wie ein US debtor in possession, kanadischer trustee. Liefert priorisierten Outp... |
| `verfahrenstypen-quellenkarte` | Verfahrenstypen Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
