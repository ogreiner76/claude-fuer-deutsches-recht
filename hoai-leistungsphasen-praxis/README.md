# HOAI Leistungsphasen Praxis

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`hoai-leistungsphasen-praxis`) | [`hoai-leistungsphasen-praxis.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/hoai-leistungsphasen-praxis.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Kita Mühlenhof Lichtenrade - HOAI-Leistungsphasen und Bauüberwachung 2026** (`hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026`) | [Gesamt-PDF lesen](../testakten/hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026/gesamt-pdf/hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026_gesamt.pdf) | [`testakte-hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-hoai-leistungsphasen-kita-muehlenhof-lichtenrade-2026.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Ein großes Arbeitsplugin für die Leistungsphasen der HOAI. Es begleitet Bauherrinnen, Architekten, Ingenieure, Bauleiter, Bauunternehmen, Subunternehmer, Anwälte, Sachverständige und Projektsteuerer durch die Phasen 1 bis 9: von der Grundlagenermittlung über Planung, Genehmigung, Ausführung, Vergabe und Bauüberwachung bis zur Objektbetreuung.

Die HOAI kennt für Gebäude und Innenräume nach § 34 HOAI neun Leistungsphasen. Dieses Plugin bildet deshalb LPH 1 bis LPH 9 ab; eine zehnte Leistungsphase gibt es in diesem Leistungsbild nicht. Für andere Leistungsbilder wie Freianlagen, Ingenieurbauwerke, Verkehrsanlagen, Tragwerksplanung oder technische Ausrüstung muss das Plugin zunächst auf das richtige HOAI-Leistungsbild routen.

## Kaltstart

Starte mit `hoai-allgemeiner-kaltstart` oder `hoai-leistungsphasen-router`. Lade Vertrag, Angebot, Honorarvereinbarung, Planstände, Protokolle, Kostenstand, Terminplan, Vergabeunterlagen, Baustellenberichte, Mängellisten und Rechnungen hoch. Das Plugin ordnet dann erst, in welcher LPH das Problem hängt, und schlägt die passenden Spezialskills vor.

## Fachfragen-Layer

Neben den LPH-Skills gibt es jetzt einen querliegenden Fachfragen-Layer für die harten Aktenprobleme: anrechenbare Kosten, mitzuverarbeitende Bausubstanz, Honorarzone, Baukostenobergrenze, Stufenbeauftragung, Zielfindungsphase, Verbraucherhinweis, Planungsänderungen, Ausführungsplanungstiefe, Vergabereife, Bieterspiegel, Bauüberwachungstiefe, Rechnungsprüfung, Abnahme/Mängel, Gewährleistungsmanagement, Fachplanerkoordination, Baugrund/Altlasten, SiGeKo/Projektsteuerung, BIM/CDE, Fördermittelbindung, prüffähige Schlussrechnung und Sachverständigenfragen. Der Router schlägt diese Skills zusätzlich zur passenden Leistungsphase vor.

## Leistungsphasen für Gebäude und Innenräume

| LPH | Bezeichnung | Bewertungsanker Gebäude/Innenräume |
| --- | --- | --- |
| 1 | Grundlagenermittlung | 2 % |
| 2 | Vorplanung | 7 % |
| 3 | Entwurfsplanung | 15 % |
| 4 | Genehmigungsplanung | 3 % Gebäude / 2 % Innenräume |
| 5 | Ausführungsplanung | 25 % Gebäude / 30 % Innenräume |
| 6 | Vorbereitung der Vergabe | 10 % Gebäude / 7 % Innenräume |
| 7 | Mitwirkung bei der Vergabe | 4 % Gebäude / 3 % Innenräume |
| 8 | Objektüberwachung, Bauüberwachung und Dokumentation | 32 % |
| 9 | Objektbetreuung | 2 % |

## Typische Ergebnisse

- LPH-Matrix mit Input, Output, Freigabe, Risiko und Nachtrag
- Plan-/Protokoll-/Kostenstand-Check
- Bauüberwachungs- und Mängelmanagement
- Vergabe- und Bieterspiegelprüfung
- Honorar-/Nachtragsnotiz
- Mandantenbrief, Bauherrnupdate oder anwaltlicher Prüfvermerk
- Sachverständigenfragen und Beweisakte für Streitfälle

## Amtliche Startquellen

- [HOAI Gesamtverordnung](https://www.gesetze-im-internet.de/hoai_2013/)
- [HOAI § 34 Gebäude und Innenräume](https://www.gesetze-im-internet.de/hoai_2013/__34.html)
- [HOAI Anlage 10 Gebäude und Innenräume](https://www.gesetze-im-internet.de/hoai_2013/anlage_10.html)
- [HOAI § 7 Honorarvereinbarung](https://www.gesetze-im-internet.de/hoai_2013/__7.html)
- [BGB § 650p Architekten- und Ingenieurvertrag](https://www.gesetze-im-internet.de/bgb/__650p.html)
- [BGB § 650q](https://www.gesetze-im-internet.de/bgb/__650q.html), [§ 650r](https://www.gesetze-im-internet.de/bgb/__650r.html), [§ 650s](https://www.gesetze-im-internet.de/bgb/__650s.html), [§ 650t](https://www.gesetze-im-internet.de/bgb/__650t.html)

## Quellenhygiene

Die HOAI ist nicht mehr das alte zwingende Mindestsatzregime für Neuverträge ab 2021. Honorar, Leistungsumfang und Vertrag müssen sauber getrennt werden. Rechtsprechung wird nur ausgegeben, wenn Gericht, Datum, Aktenzeichen und frei zugänglicher Fundlink geprüft sind.

<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 50 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anwaltlicher-pruefvermerk-bauherrnfreigabe` | Anwaltlicher Pruefvermerk Bauherrnfreigabe im HOAI-Leistungsphasen: prüft konkret HOAI LPH 8 Objektüberwachung - Bauüberwachung und. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `bim-datenraum-dokumentation-belegakte` | BIM Datenraum Dokumentation Belegakte im HOAI-Leistungsphasen: prüft konkret HOAI LPH 6 Vorbereitung der Vergabe. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `bim-datenraum-dokumentation-belegakte-02` | BIM Datenraum Dokumentation Belegakte 02 im HOAI-Leistungsphasen: prüft konkret HOAI LPH 2 Vorplanung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `bim-modell-kostenobergrenze-budget-lph` | BIM Modell Kostenobergrenze Budget LPH im HOAI-Leistungsphasen: prüft konkret HOAI-Fachfrage, HOAI LPH 1 Grundlagenermittlung, HOAI LPH 2 Vorplanung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `dokumentation-belegakte-fachplaner` | Dokumentation Belegakte Fachplaner im HOAI-Leistungsphasen: prüft konkret HOAI LPH 8 Objektüberwachung - Bauüberwachung und. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `gebaeude-innenraeume-hoai-gerichtsfeste` | Gebaeude Innenraeume HOAI Gerichtsfeste im HOAI-Leistungsphasen: prüft konkret HOAI-Praxis. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-anwaltliche-red-team-runde` | HOAI-Praxis: sucht Fehler, falsche LPH-Zuordnung, fehlende Freigaben und Beleglücken; für Architekten, Ingenieure, Bauleiter, Bauunternehmen, Anwälte, Sachverständige und Bauherren. |
| `hoai-baubesprechung-protokoll-baugrund` | Baubesprechung Protokoll Baugrund im HOAI-Leistungsphasen: prüft konkret HOAI-Praxis, HOAI-Fachfrage. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-claim-timeline-dokumentenindex` | Claim Timeline Dokumentenindex im HOAI-Leistungsphasen: prüft konkret HOAI-Praxis, HOAI-Fachfrage. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-kaltstart-routing` | HOAI-Praxis: führt durch Projektart, Rolle, LPH-Stand, Vertrag, Honorar, Druck und gewünschtes Ergebnis; für Architekten, Ingenieure, Bauleiter, Bauunternehmen, Anwälte, Sachverständige und Bauherren. |
| `hoai-kostensteuerung-mandanten-mangel-claim-03` | Kostensteuerung Mandanten Mangel Claim 03 im HOAI-Leistungsphasen: prüft konkret HOAI LPH 1 Grundlagenermittlung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-kostensteuerung-mandanten-mangel-claim-04` | Kostensteuerung Mandanten Mangel Claim 04 im HOAI-Leistungsphasen: prüft konkret HOAI LPH 3 Entwurfsplanung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-kostensteuerung-mandanten-mangel-nachtrag` | Kostensteuerung Mandanten Mangel Nachtrag im HOAI-Leistungsphasen: prüft konkret HOAI LPH 7 Mitwirkung bei der Vergabe. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-leistungsphasen-lph-abnahme-anwaltlicher` | LPH Abnahme Anwaltlicher im HOAI-Leistungsphasen: prüft konkret HOAI-Praxis, HOAI LPH 1 Grundlagenermittlung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-lph-01-red-team-pruefung` | HOAI LPH 1 Grundlagenermittlung: sucht Widersprüche, vergessene Beteiligte, falsche Annahmen und unklare Zuständigkeit; mit Fokus auf Aufgabenstellung klären, Ortsbesichtigung, Untersuchungsbedarf, Beteiligte auswählen, Ergebnisse dokume... |
| `hoai-lph-02-red-team-pruefung` | HOAI LPH 2 Vorplanung: sucht Widersprüche, vergessene Beteiligte, falsche Annahmen und unklare Zuständigkeit; mit Fokus auf Grundlagen analysieren, Planungskonzept mit Alternativen, Kostenschätzung, Vorverhandlungen und Entscheidungsgrun... |
| `hoai-lph-03-red-team-pruefung` | HOAI LPH 3 Entwurfsplanung: sucht Widersprüche, vergessene Beteiligte, falsche Annahmen und unklare Zuständigkeit; mit Fokus auf stimmige Entwurfsfassung, Kostenberechnung, Termin-/Objektbeschreibung, Integration der Fachplanung und Bewe... |
| `hoai-lph-04-red-team-pruefung` | HOAI LPH 4 Genehmigungsplanung: sucht Widersprüche, vergessene Beteiligte, falsche Annahmen und unklare Zuständigkeit; mit Fokus auf öffentlich-rechtlich genehmigungsfähige Unterlagen, Anträge, Behördenabstimmung und Auflagenlogik und Be... |
| `hoai-lph-05-red-team-pruefung` | HOAI LPH 5 Ausführungsplanung: sucht Widersprüche, vergessene Beteiligte, falsche Annahmen und unklare Zuständigkeit; mit Fokus auf durcharbeitete ausführungsreife Planung, Detailpläne, Koordination der Fachplaner und Fortschreibung und... |
| `hoai-lph-06-red-team-pruefung` | HOAI LPH 6 Vorbereitung der Vergabe: sucht Widersprüche, vergessene Beteiligte, falsche Annahmen und unklare Zuständigkeit; mit Fokus auf Mengen, Leistungsverzeichnisse, Schnittstellen, Kostenanschlag und Vergabestruktur und Bewertungsan... |
| `hoai-lph-belegakte-fachplaner-foerdermittel` | LPH Belegakte Fachplaner Foerdermittel im HOAI-Leistungsphasen: prüft konkret HOAI LPH 1 Grundlagenermittlung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-lph-bim-belegakte-fachplaner` | LPH BIM Belegakte Fachplaner im HOAI-Leistungsphasen: prüft konkret HOAI LPH 4 Genehmigungsplanung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-lph-kostensteuerung-mandantenbericht` | LPH Kostensteuerung Mandantenbericht im HOAI-Leistungsphasen: prüft konkret HOAI LPH 5 Ausführungsplanung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-lph-outputpaket-planfreigabe` | LPH Outputpaket Planfreigabe im HOAI-Leistungsphasen: prüft konkret HOAI LPH 7 Mitwirkung bei der Vergabe. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-lph-risikoregister-sachverstaendigen` | LPH Risikoregister Sachverstaendigen im HOAI-Leistungsphasen: prüft konkret HOAI LPH 4 Genehmigungsplanung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-lph6-lv-lph7-bieterspiegel-lph8-maengel` | Lph6 LV Lph7 Bieterspiegel Lph8 Maengel im HOAI-Leistungsphasen: prüft konkret HOAI-Fachfrage LPH 6, HOAI-Fachfrage LPH 7, HOAI-Fachfrage LPH 8. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-mitzuverarbeitende-bausubstanz` | Mitzuverarbeitende Bausubstanz im HOAI-Leistungsphasen: prüft konkret HOAI-Fachfrage, HOAI-Praxis. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-sigeko-projektsteuerung-abnahmefahrplan` | Sigeko Projektsteuerung Abnahmefahrplan im HOAI-Leistungsphasen: prüft konkret HOAI-Fachfrage, HOAI-Praxis. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `hoai-stufenbeauftragung-abruf-subunternehmer` | Stufenbeauftragung Abruf Subunternehmer im HOAI-Leistungsphasen: prüft konkret HOAI-Fachfrage, HOAI-Praxis. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `honorar-prozentwert-input-zielcheck` | Honorar Prozentwert Input Zielcheck im HOAI-Leistungsphasen: prüft konkret HOAI LPH 1 Grundlagenermittlung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `honorarvereinbarung-paragraph-honorarzone` | Honorarvereinbarung Paragraph Honorarzone im HOAI-Leistungsphasen: prüft konkret HOAI-Praxis, HOAI-Fachfrage. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `kostensteuerung-mandantenbericht-mangel-claim` | Kostensteuerung Mandantenbericht Mangel Claim im HOAI-Leistungsphasen: prüft konkret HOAI LPH 9 Objektbetreuung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `lph-haftungsfalle-planerhaftung-grundlagen` | LPH Haftungsfalle Planerhaftung Grundlagen im HOAI-Leistungsphasen: prüft konkret HOAI LPH 9 Objektbetreuung, HOAI-Praxis, HOAI-Fachfrage. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `lph-verbraucher-maengelmanagement-end` | LPH Verbraucher Maengelmanagement END im HOAI-Leistungsphasen: prüft konkret HOAI LPH 7 Mitwirkung bei der Vergabe, HOAI-Praxis. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `lph4-bis-lph8-haftungsfallen` | Lph4 BIS Lph8 Haftungsfallen im HOAI-Leistungsphasen: prüft konkret HOAI LPH 4 Genehmigungsplanung, HOAI LPH 5 Ausführungsplanung, HOAI LPH 6 Vorbereitung der Vergabe, HOAI LPH 7 Mitwirkung bei der Vergabe. Liefert priorisierten Output m... |
| `lph8-bauueberwachung-altvertrag` | Lph8 Bauueberwachung Altvertrag im HOAI-Leistungsphasen: prüft konkret Bauueberwachung HOAI LPH 8 fuer Windpark-Fundamente und, HOAI-Praxis, HOAI LPH 1 Grundlagenermittlung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel un... |
| `lph8-bauueberwachung-bueroneubau-dachdeckung` | Lph8 Bauueberwachung Bueroneubau Dachdeckung im HOAI-Leistungsphasen: prüft konkret Bauueberwachung nach HOAI LPH 8 fuer Bueroneubau mit, Bauueberwachung HOAI LPH 8 fuer Flachdach- und, Bauueberwachung HOAI LPH 8 fuer Deichbauten und. Li... |
| `lph8-bauueberwachung-dokumentenanalyse` | Lph8 Bauueberwachung Dokumentenanalyse im HOAI-Leistungsphasen: prüft konkret Methodikskill HOAI LPH 8 — Strukturierter fuer, Bauueberwachung nach HOAI LPH 8 fuer Doppelhaeuser und, Bauueberwachung nach HOAI LPH 8 fuer Einfamilienhaeuser... |
| `lph8-bauueberwachung-klaeranlage-krankenhaus` | Lph8 Bauueberwachung Klaeranlage Krankenhaus im HOAI-Leistungsphasen: prüft konkret Bauueberwachung HOAI LPH 8 fuer Klaeranlage-Becken mit, Bauueberwachung nach HOAI LPH 8 fuer Krankenhausneubauten, Bauueberwachung nach HOAI LPH 8 fuer L... |
| `lph8-bauueberwachung-lph2` | Lph8 Bauueberwachung Lph2 im HOAI-Leistungsphasen: prüft konkret Bauueberwachung HOAI LPH 8 fuer Erdbauarbeiten mit Fokus, HOAI-Fachfrage LPH 2, HOAI-Fachfrage LPH 3, HOAI-Fachfrage LPH 4. Liefert priorisierten Output mit Norm-Pinpoints,... |
| `lph8-bauueberwachung-trockenbau-tunnel` | Lph8 Bauueberwachung Trockenbau Tunnel im HOAI-Leistungsphasen: prüft konkret Bauueberwachung HOAI LPH 8 fuer, Bauueberwachung nach HOAI LPH 8 fuer Tunnelbauwerke im, Methodikskill HOAI LPH 8 — Strukturierter fuer die, Methodikskill HOAI... |
| `lph9-gewaehrleistungsmanagement-lph8` | Lph9 Gewaehrleistungsmanagement Lph8 im HOAI-Leistungsphasen: prüft konkret HOAI-Fachfrage LPH 9, Methodikskill HOAI LPH 8 — Abnahmeprotokoll-Erstellung fuer, Methodikskill HOAI LPH 8 — Bautagebuch-Erstellung und, Bauueberwachung HOAI LP... |
| `qualitaetscheck-release-rechnungspruefung` | Qualitaetscheck Release Rechnungspruefung im HOAI-Leistungsphasen: prüft konkret HOAI-Praxis. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `risikoregister-sachverstaendigen-pruefung` | Risikoregister Sachverstaendigen Pruefung im HOAI-Leistungsphasen: prüft konkret HOAI LPH 6 Vorbereitung der Vergabe. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `risikoregister-sachverstaendigen-pruefung-02` | Risikoregister Sachverstaendigen Pruefung 02 im HOAI-Leistungsphasen: prüft konkret HOAI LPH 7 Mitwirkung bei der Vergabe. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `risikoregister-sachverstaendigen-pruefung-03` | Risikoregister Sachverstaendigen Pruefung 03 im HOAI-Leistungsphasen: prüft konkret HOAI LPH 8 Objektüberwachung - Bauüberwachung und. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `risikoregister-sachverstaendigen-pruefung-04` | Risikoregister Sachverstaendigen Pruefung 04 im HOAI-Leistungsphasen: prüft konkret HOAI LPH 2 Vorplanung. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `vertrag-beauftragungsumfang` | Vertrag Beauftragungsumfang im HOAI-Leistungsphasen: prüft konkret HOAI LPH 3 Entwurfsplanung, HOAI LPH 4 Genehmigungsplanung, HOAI LPH 5 Ausführungsplanung, HOAI LPH 6 Vorbereitung der Vergabe. Liefert priorisierten Output mit Norm-Pinp... |
| `vertrag-beauftragungsumfang-vertragliche` | Vertrag Beauftragungsumfang Vertragliche im HOAI-Leistungsphasen: prüft konkret HOAI LPH 8 Objektüberwachung - Bauüberwachung und, HOAI LPH 9 Objektbetreuung, HOAI-Praxis. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `vob-b-wiederholungsleistungen` | VOB B Wiederholungsleistungen im HOAI-Leistungsphasen: prüft konkret HOAI-Praxis, HOAI-Fachfrage. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
