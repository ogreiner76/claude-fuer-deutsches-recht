# Plugin für die studentische Rechtsberatungsstelle

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`rechtsberatungsstelle`) | [`rechtsberatungsstelle.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/rechtsberatungsstelle.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Rechtsberatungsstelle Köln-Kalk — Monatsmix August 2026, Dr. Pellbach-Tannenfels** (`rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach`) | [Gesamt-PDF lesen](../testakten/rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach/gesamt-pdf/rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach_gesamt.pdf) | [`testakte-rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-rechtsberatungsstelle-koeln-quartier-kalk-q3-2026-monatsmix-pellbach.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

*KI-gestützte Unterstützung für universitäre Refugee Law Clinics, studentische Rechtsberatungen und Pro-Bono-Initiativen – mit klaren RDG-Grenzen.*

Ein Plugin für Einrichtungen, in denen Studierende – unter Anleitung zur Anleitung berechtigter Volljuristen – unentgeltliche Rechtsberatung für Menschen leisten, die sich anwaltliche Hilfe nicht leisten können oder keinen Zugang dazu haben: Aufenthalts- und Asylrecht, Sozialrecht (SGB II/XII, SGB IX), Mietrecht, Verbraucherrecht, Familienrecht.

**Jede Ausgabe ist ein Entwurf für die Analyse durch Studierende und die Freigabe durch den anleitenden Volljuristen – gekennzeichnet, gestuft und protokolliert. Das Plugin gibt Struktur; die Studierenden denken juristisch; der Anleiter prüft und gibt frei. Nichts verlässt die Beratungsstelle ohne Durchlaufen dieses Aufsichtsmodells.**

---

## Wichtiger Hinweis: Rechtliche Grenzen nach dem RDG

> **Diese Beratungsstelle erbringt Rechtsdienstleistungen ausschließlich im Rahmen von § 6 Abs. 2 Nr. 2 RDG (unentgeltliche Rechtsdienstleistungen durch Volljuristen anleitungsberechtigt) oder § 8 RDG (Verbraucherzentralen, Sozialberatung). Jede entgeltliche Rechtsdienstleistung durch Nicht-Zugelassene ist nach § 3 RDG untersagt und nach § 20 RDG bußgeldbewehrt.**

**Für Studierende gilt:**
- Rechtliche Auskünfte dürfen nur unter Anleitung und Aufsicht eines zur Anleitung berechtigten Volljuristen erteilt werden (§ 6 Abs. 2 Nr. 2 RDG).
- Schriftsätze, Stellungnahmen und Widersprüche sind **Entwürfe** – keine fertigen, abzusendenden Dokumente.
- Jede strategische Entscheidung (Klage ja/nein, Rücknahme, Vergleich) liegt beim anleitenden Anwalt.
- Das Mandat liegt formal beim Anleiter, nicht beim Studierenden.
- Verschwiegenheit nach § 43a Abs. 2 BRAO analog, § 203 StGB – auch nach Semesterende.

---

## Das Problem, das dieses Plugin löst

Beratungsstellen sind strukturell kapazitätsbeschränkt. Ein anleitender Jurist betreut 5–12 Studierende. Jede Studierende trägt eine Handvoll Mandate, während sie gleichzeitig Lehrveranstaltungen besucht. Studierende wechseln jedes Semester. Verwaltungsaufgaben – Intake-Protokoll, Erstentwürfe, Rechercheansätze, Statusberichte, Semesterübergaben – verschlingen Stunden, die besser in die juristische Analyse investiert wären. Das Ergebnis: lange Wartelisten, begrenzte Fallzahlen, Ratsuchende, die aufgeben.

Dieses Plugin senkt die Zeitkosten für alles **rund um die Rechtsarbeit**, damit dieselben Studierenden und ihr Anleiter deutlich mehr Mandanten sinnvoll betreuen können – und die Studierenden mehr Zeit für Analyse und Strategie haben, die das Kernanliegen studentischer Rechtsbildung ausmacht.

**Es beschleunigt die nicht-lehrenden Teile. Es bewahrt die analytische Arbeit.** Das ist das Gestaltungsprinzip.

---

## Wer nutzt das Plugin?

| Rolle | Startet | Erhält |
|---|---|---|
| **Anleitender Volljurist** | `/kaltstart-interview` (einmalig), `/anleiter-pruefwarteschlange` (wenn formelle Prüfung aktiviert) | Konfigurierter Beratungsstellenkontext, Prüfung studentischer Arbeit |
| **Studierende** | `/einarbeitung` (Semesterbeginn), dann `/mandant-aufnahme`, `/entwurf`, `/memo`, `/recherche-start`, `/status`, `/mandantenbrief` | Strukturierte Arbeitshilfen, Entwürfe, Rechercheeinstiege |
| **Mandant** | – | Empfängt fertig geprüfte Briefe (Studierender + Anleiter haben freigegeben) |

---

## Schnellstart

```
/rechtsberatungsstelle:rechtsberatungsstelle-kaltstart-interview   # Anleiter: Beratungsstelle konfigurieren
/rechtsberatungsstelle:einarbeitung                   # Studierender: Einarbeitung zum Semesterbeginn
/rechtsberatungsstelle:mandant-aufnahme          # Neues Mandat aufnehmen
/rechtsberatungsstelle:memo                   # Gutachtenstil-Memo erstellen
/rechtsberatungsstelle:entwurf                  # Schriftsatz entwerfen
/rechtsberatungsstelle:fristen              # Fristen prüfen
/rechtsberatungsstelle:mandantenbrief          # Mandantenbrief in einfacher Sprache
/rechtsberatungsstelle:semester-uebergabe       # Semesterübergabe vorbereiten
```

---

## Beratungsstellentypen, die dieses Plugin unterstützt

### Universitäre Refugee Law Clinics (RLC)

Hochschulverankerte Kliniken wie die **Refugee Law Clinic Berlin** (HU Berlin/FU Berlin), die **Refugee Law Clinic Bremen** (Universität Bremen) oder die **Refugee Law Clinic Köln** (Universität zu Köln) beraten Asylsuchende und Geduldete zu Fragen des AsylG, AufenthG und SGB II. Besonderheiten:
- Kurze Fristen (§§ 36, 74 AsylG): Klagen gegen BAMF-Bescheide oft binnen 1–2 Wochen nach Zustellung.
- Sprachbarrieren: Dolmetscher-Koordination ist Teil des Intakes.
- Schnittstellen zu § 76b SGB IX (Eingliederungshilfe für Geflüchtete).

### Studentische Rechtsberatung nach § 6 Abs. 2 Nr. 2 RDG

Allgemeine studentische Beratungsstellen an Universitäten (oft "JuRI", "Jura hilft" o. ä.). Fokus: SGB II (Bürgergeld), Mietrecht, Verbraucherrecht, Familienrecht. Betrieb ausschließlich unter Aufsicht zugelassener Anwälte oder habilitierter Volljuristen.

### AnwVer/DAV Pro-Bono-Initiativen

Anwaltsverein-getragene Pro-Bono-Programme (z. B. **Pro Bono Berlin e. V.**, **DAV Pro Bono**): hier beraten zugelassene Anwälte direkt, die Plugin-Komponenten `entwurf`, `memo` und `recherche-start` unterstützen die Mandatsarbeit.

### Verbraucherzentralen (§ 8 RDG)

Verbraucherzentralen besitzen eine Sondererlaubnis nach § 8 Abs. 1 Nr. 4 RDG. Das Plugin unterstützt Standardfälle: Mieterhöhung, Kündigung, AGB-Kontrolle (§§ 305 ff. BGB), Energiekosten-Nachforderungen.

### Sozialberatung

Anerkannte Beratungsträger (AWO, Caritas, Diakonie, DRK, Paritätischer) arbeiten nach § 8 Abs. 1 Nr. 4 RDG. Schwerpunkte: SGB II, SGB XII, SGB IX, Rentenrecht (§ 109 SGB VI), Pflegegeld (§ 76b SGB IX).

---

## Beispiele: Pro-Bono-Initiativen in Berlin und Bremen

| Initiative | Ort | Schwerpunkt | Rechtsgrundlage |
|---|---|---|---|
| Refugee Law Clinic Berlin (HU/FU) | Berlin | AsylG, AufenthG, SGB II | § 6 II Nr. 2 RDG |
| Pro Bono Berlin e. V. | Berlin | Zivilrecht, Mietrecht, Familienrecht | Zugelassene Anwälte |
| Berliner Mieterverein – Rechtsberatung | Berlin | Mietrecht | § 8 I Nr. 3 RDG (Verband) |
| Refugee Law Clinic Bremen | Bremen | AsylG, AufenthG | § 6 II Nr. 2 RDG |
| Verbraucherzentrale Bremen | Bremen | Verbraucherrecht, Mietrecht | § 8 I Nr. 4 RDG |
| JuRI – Juristische Interessenvertretung (Uni Bremen) | Bremen | SGB II, allg. Zivilrecht | § 6 II Nr. 2 RDG |
| Caritas Berlin – Migrationsberatung | Berlin | AufenthG, SGB II | § 8 I Nr. 4 RDG |

---

## Fachbereiche und Skills

| Skill | Zweck | Primäre Normen |
|---|---|---|
| `leitfaden-erstellen` | Leitfaden zum Aufbau einer Beratungsstelle | RDG, BRAO |
| `mandanten-kommunikations-log` | Mandantenkommunikations-Logbuch | § 43a BRAO, § 203 StGB |
| `mandant-aufnahme` | Intake mit RDG-Konfliktprüfung | § 6 II Nr. 2 RDG |
| `mandantenbrief` | Mandantenbrief in einfacher Sprache | BORA |
| `rechtsberatungsstelle-kaltstart-interview` | Ersteinrichtung der Beratungsstelle | RDG, BRAO |
| `rechtsberatungsstelle-anpassen` | Beratungsstellenprofil anpassen | – |
| `fristen` | Fristenkontrolle | § 84 SGG, § 74 VwGO, §§ 36, 74 AsylG |
| `entwurf` | Schriftsatzentwurf | ZPO, VwGO, SGG |
| `formular-erzeugung` | Formularerstellung (PKH, BerHG, KSchG) | §§ 114 ff. ZPO, BerHG |
| `memo` | Memo im Gutachtenstil | – |
| `einfache-sprache-briefe` | Einfache Sprache | BORA |
| `einarbeitung` | Einarbeitung Studierende | § 6 II Nr. 2 RDG |
| `recherche-start` | Rechercheeinstieg | juris, Beck-Online, gesetze-im-internet.de |
| `semester-uebergabe` | Semesterübergabe | – |
| `status` | Statusbericht | – |
| `anleiter-pruefwarteschlange` | Aufsichts-Reviewqueue | § 6 II Nr. 2 RDG, § 43a BRAO |

---

## Qualitätssicherung

Alle studentischen Outputs tragen den Vermerk:

> **[KI-GESTÜTZTER ENTWURF – Analyse durch Studierende und Freigabe durch anleitenden Volljuristen erforderlich. Kein Versand ohne Prüfung.]**

Nur der anleitende Jurist kann diesen Vermerk entfernen. Dokumente, die diesen Vermerk tragen, dürfen nicht unmittelbar an Mandanten oder Behörden gesendet werden.

---

## Zitierweise

Alle juristischen Quellen folgen `../references/zitierweise.md`. Beispiele:
- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.
- Krenzler, in: Krenzler (Hrsg.), RDG, 2. Aufl. 2021, § 6 Rn. 45.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 25 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anlaufstellen-beweislast-anleiter-bono` | Anlaufstellen Beweislast Anleiter Bono im Plugin Rechtsberatungsstelle: prüft konkret Anlaufstellen, Anleiter, Bono. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `anleiter-pruefwarteschlange` | 'Supervisoren-Prüfwarteschlange — studentische Arbeitsergebnisse warten hier auf die Supervisoren-Freigabe, bevor sie an Mandanten oder Gerichte gehen. Nur aktiv, wenn das Supervisionsmodell 'formelle Prüfwarteschlange' gewählt wurde; an... |
| `briefe-erstberatung-rdg-konform` | Briefe Erstberatung RDG Konform im Plugin Rechtsberatungsstelle: prüft konkret Briefe, Erstberatung mit RDG-Grenzen und Triage, Konform. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `entwurf-einarbeitung-einfache-sprache` | Entwurf Einarbeitung Einfache Sprache im Plugin Rechtsberatungsstelle: prüft konkret Erstellt einen Erstentwurf häufiger Schriftstücke der, Semestereinarbeitung für neue studentische Berater —, Anwalts- und Behoerdenbriefe in leichte ode... |
| `erzeugung-leitfaden-erstellen-mandanten` | Erzeugung Leitfaden Erstellen Mandanten im Plugin Rechtsberatungsstelle: prüft konkret Formulare und Antragsdokumente für Rechtsberatungsstelle, Leitfaden und Merkblatt für Rechtsberatungsstelle erstellen, Mandantenkommunikation dokument... |
| `fristen-fristenkontrolle-rdg` | Fristen Fristenkontrolle RDG im Plugin Rechtsberatungsstelle: prüft konkret Fristenmanagement für die Rechtsberatungsstelle — Fristen, gesamtüberg, Fristenkontrolle, RDG. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und n... |
| `mandant-aufnahme` | Mandantenaufnahme in der Rechtsberatungsstelle strukturieren: Anwendungsfall Student nimmt erstmals Mandanten auf und muss Sachverhalt strukturiert erfassen Rechtsgebiet einordnen und naechste Schritte bestimmen. BeratungsHiG § 2 Beratun... |
| `mandantenbrief-memo-rbs-beratungshilfe` | Mandantenbrief Memo RBS Beratungshilfe im Plugin Rechtsberatungsstelle: prüft konkret Mandantenbrief für Rechtsberatungsstelle verfassen, Erstellt ein Gutachten-Gerüst nach der deutschen, Beratungshilfe BerHG und PKH in der Praxis. Liefe... |
| `mandantenfreundliche-quellenkarte-check` | Mandantenfreundliche Quellenkarte Check: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `mandantenintake-mandatsuebergabe` | Mandantenintake Mandatsuebergabe im Plugin Rechtsberatungsstelle: prüft konkret Mandantenintake, Mandatsuebergabe, Pro-Bono-Mandatsübergabe mit Fristen und Zuständigkeiten. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und... |
| `pruefwarteschlange-red-rbst-recherche` | Pruefwarteschlange RED Rbst Recherche im Plugin Rechtsberatungsstelle: prüft konkret Pruefwarteschlange, Rbst, Recherche. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `rbs-einfuehrung-rdg-rbst-anlaufstellen` | RBS Einfuehrung RDG Rbst Anlaufstellen im Plugin Rechtsberatungsstelle: prüft konkret Rechtsberatungsstelle einfuehrend, Spezialfall RDG-Grenzen, Bauleiter Anlaufstellen Rechtsberatung. Liefert priorisierten Output mit Norm-Pinpoints, Ri... |
| `rbst-beratungshilfe-prozesskostenhilfe` | Rbst Beratungshilfe Prozesskostenhilfe im Plugin Rechtsberatungsstelle: prüft konkret Leitfaden Beratungshilfe und Prozesskostenhilfe, Spezialfall niedrigschwellige Onlineberatung mit, Spezialfall RDG-Grenzen fuer Nichtanwaelte. Liefert... |
| `recherche-start-rechtsberatungsstelle` | Recherche Start Rechtsberatungsstelle im Plugin Rechtsberatungsstelle: prüft konkret Recherchefahrplan für eine Rechtsfrage — einschlägige Normen, Rechtsprechungsber, Rechtsberatungsstelle-Plugin an spezifische Kanzlei oder, Semesterabsc... |
| `rechtsberatung-uebergabe-schriftsatz-brief-memo-bausteine-status` | Rechtsberatung Uebergabe Schriftsatz Brief Memo Bausteine Status im Plugin Rechtsberatungsstelle: prüft konkret Uebergabe, Fallstatuszusammenfassung nach Zielgruppe —. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näch... |
| `rechtsberatungsstelle-anschluss-router` | Anschluss Router im Plugin Rechtsberatungsstelle: prüft konkret Einstieg, Schnelltriage und Fallrouting im, Anschluss-Skills Router im Plugin rechtsberatungsstelle, Chronologie und Belegmatrix im Plugin rechtsberatungsstelle. Liefert pri... |
| `rechtsberatungsstelle-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `rechtsberatungsstelle-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `rechtsberatungsstelle-fristen-risikoampel-mandantenkommunikation` | Fristen Risikoampel Mandantenkommunikation im Plugin Rechtsberatungsstelle: prüft konkret Fristen- und Risikoampel im Plugin rechtsberatungsstelle, Mandantenkommunikation im Plugin rechtsberatungsstelle, Red-Team Qualitygate im Plugin re... |
| `rechtsberatungsstelle-kaltstart-interview` | Rechtsberatungsstelle Kaltstart und Erst-Konfiguration: Anwendungsfall neue Rechtsberatungsstelle oder neues Semester startet und Plugin muss mit Rechtsgebieten Hochschule Anleiter und Beratungsregeln eingerichtet werden. BeratungsHiG §... |
| `rechtsberatungsstelle-output-waehlen` | Output wählen im Plugin Rechtsberatungsstelle: Diese Output-Weiche für Rechtsberatungsstelle entscheidet, ob Memo, Antrag, Schriftsatz, Tabelle, Risikoampel, Fragenliste oder Mandantenbrief der richtige nächste Schritt ist. |
| `rechtsberatungsstelle-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `rechtsberatungsstelle-rechtsberatungsstellen` | Rechtsberatungsstellen im Plugin Rechtsberatungsstelle: prüft konkret Rechtsberatungsstelle, Rechtsberatungsstellen, Semesterende. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `rechtsberatungsstelle-sonderfall-edge-case` | Kaltstart: Sonderfall und Edge-Case-Prüfung im Plugin Rechtsberatungsstelle: 1. Welche Rolle hat die fragende Person und wer ist Gegenüber? 2. Welches konkrete Ziel soll erreicht oder verhindert werden? 3. Welche Frist, Zustellung, Schwe... |
| `rechtsberatungsstelle-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
