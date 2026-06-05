# Subsumtions-Prüfer

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`subsumtions-pruefer`) | [`subsumtions-pruefer.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/subsumtions-pruefer.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **Subsumtionskontrolle / Klausurkorrektur — Übung für Fortgeschrittene BGB, Uni Bielefeld, Lehrstuhl Pohlmann-Wittfeldt, SS 2026** (`subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann`) | [Gesamt-PDF lesen](../testakten/subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann/gesamt-pdf/subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann_gesamt.pdf) | [`testakte-subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-subsumtions-klausurkorrekt-bgb-fall-fortgeschrittene-uni-bielefeld-pohlmann-eichmann.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Interaktiver Mechanik-Workflow für die juristische Subsumtion nach deutschem Recht und Europarecht. Das Plugin zerlegt Normen in Tatbestandsmerkmale, führt das Vier-Schritt-Schema (Obersatz – Definition – Untersatz – Ergebnis) durch, erfasst Beweisbedarf und erzeugt Ausgabedokumente in verschiedenen Formaten.

**Dieses Plugin ist keine Rechtsberatung.** Es prüft mechanisch eine vom Nutzer behauptete Norm anhand vom Nutzer behaupteter Tatsachen. Die Auswahl der richtigen Norm, die vollständige Sachverhaltsdarstellung und die Bewertung des Ergebnisses bleiben in der Verantwortung des Nutzers und eines zugelassenen Rechtsanwalts.

## Für wen ist dieses Plugin

| Rolle | Primäre Anwendungsfälle |
|---|---|
| Privatpersonen | Verstehen, ob ein Anspruch dem Grunde nach bestehen könnte |
| Paralegal / Rechtsfachwirt | Strukturierte Erstsichtung vor anwaltlicher Prüfung |
| Jurastudent / Referendar | Subsumtionsübung ohne Musterlösung |
| Unternehmensjurist | Schnelle Erstprüfung einer Norm vor Mandatserteilung |
| Behördenmitarbeiter | Strukturiertes Durchprüfen von Tatbestandsvoraussetzungen |

## Abgedeckte Rechtsgebiete

- **Deutsches Recht:** BGB (Schuld-, Sachen-, Familien-, Erbrecht), HGB, StGB, StPO, ZPO, VwGO, VwVfG, GG, AO, SGB, KSchG, AGG, GWB, UWG und Nebengesetze
- **BGB AT:** Für Vertragsschluss, Willenserklärung, Zugang, Geschäftsfähigkeit, Form, Anfechtung, Stellvertretung, Fristen und Verjährung sollte `bgb-at-pruefer` vor oder neben diesem generischen Subsumtions-Plugin geladen werden.
- **Europarecht:** AEUV, EUV, GRCh (Primärrecht); DSGVO, KI-VO, Produkthaftungsrichtlinie, Verbraucherrechterichtlinie, Vergaberichtlinien u. a. (Sekundärrecht); EuGH-Judikatur

## Workflow-Überblick

```
Einstieg
│
├─ triage-rechtsfrage-oder-norm
│   Sachverhalt / Rechtsfrage / Norm erfassen
│
├─ ziel-und-rechtsweg-bestimmung
│   Was will der Nutzer? Welches Gericht?
│
├─ falsche-wiese-warnung
│   Fehlverortungen erkennen
│
├─ de-eu-recht-abgrenzung
│   Welches Recht gilt?
│
Normbestimmung
│
├─ einschlaegige-normen-vorschlagen-de / -eu
├─ norm-historie-und-aenderungen
├─ rechtsprechung-recherche-strategie
│
Subsumtion
│
├─ norm-zerlegen-in-tatbestandsmerkmale
├─ ungeschriebene-merkmale-judikatur
├─ generalklauseln-pruefen
├─ unbestimmte-rechtsbegriffe-pruefen
├─ subsumtion-obersatz-definition-untersatz-ergebnis
├─ beweisbedarf-und-belege-erfassen
├─ darlegungs-und-beweislast-verteilen
├─ gegen-tbm-und-einreden-pruefen
│
Rechtsfolgen
│
├─ rechtsfolge-bestimmen
├─ konkurrenzen-anspruchsgrundlagen
├─ verjaehrung-fristen-pruefen
├─ verfahrensart-bestimmen
├─ eu-vorabentscheidung-pruefen
├─ grundrechte-pruefung-de-und-grch
│
Ausgabe (wählbar)
│
├─ output-juristisch-gestochen-de
├─ output-alltagssprache-de
├─ output-fremdsprachig-en-fr
├─ output-antrag-beschwerde-klageschrift
├─ output-memo-und-mandantenbrief
└─ output-pruefungsdokument-mit-warnhinweisen
```

## Wichtige Warnhinweise

Das System warnt aktiv in folgenden Situationen:

- **Falsche Norm:** Sachverhalt passt nicht zur gewählten Norm (`falsche-wiese-warnung`)
- **Komplexitätsgrenze:** Sachverhalt zu komplex für mechanische Prüfung (`mandatsabbruch-empfehlung-an-fachanwalt`)
- **Generalklauseln:** Kein mechanisch abschließbares Ergebnis möglich (`generalklauseln-pruefen`)
- **Unbestimmte Rechtsbegriffe:** Nur Indiziensammlung, keine Subsumtion (`unbestimmte-rechtsbegriffe-pruefen`)
- **Offene TBM:** Fehlende Belege gefährden das Ergebnis (`beweisbedarf-und-belege-erfassen`)

## Skills (31)

### A. Triage / Workflow-Einstieg

| Skill | Funktion |
|---|---|
| `triage-rechtsfrage-oder-norm` | Interaktive Erfassung der Nutzereingabe |
| `ziel-und-rechtsweg-bestimmung` | Ziel und Rechtsweg ermitteln |
| `falsche-wiese-warnung` | Typische Fehlverortungen erkennen |
| `de-eu-recht-abgrenzung` | Nationales vs. Unionsrecht abgrenzen |
| `mandatsabbruch-empfehlung-an-fachanwalt` | Komplexitätsgrenze erkennen, Fachanwalt empfehlen |

### B. Normbestimmung und Recherche

| Skill | Funktion |
|---|---|
| `einschlaegige-normen-vorschlagen-de` | Deutsche Normen anhand Sachverhalt vorschlagen |
| `einschlaegige-normen-vorschlagen-eu` | EU-Normen anhand Sachverhalt vorschlagen |
| `rechtsprechung-recherche-strategie` | Recherche-Strategie und Fundstellen |
| `norm-historie-und-aenderungen` | Geltende Fassung und Übergangsrecht |
| `kommentar-und-literatur-hinweis` | Standardkommentare und Literaturhinweise |

### C. Tatbestandsmerkmale und Subsumtion

| Skill | Funktion |
|---|---|
| `norm-zerlegen-in-tatbestandsmerkmale` | TBM-Liste mit Definitionen |
| `ungeschriebene-merkmale-judikatur` | Richterrechtlich entwickelte Merkmale |
| `generalklauseln-pruefen` | Generalklauseln — Indizien und Fallgruppen |
| `unbestimmte-rechtsbegriffe-pruefen` | Auslegungsmaßstäbe für unbestimmte Begriffe |
| `subsumtion-obersatz-definition-untersatz-ergebnis` | Vier-Schritt-Schema je TBM |
| `beweisbedarf-und-belege-erfassen` | Beweismittel-Katalog und Tracking |
| `darlegungs-und-beweislast-verteilen` | Beweislast pro TBM |
| `gegen-tbm-und-einreden-pruefen` | Einwendungen und Einreden |

### D. Rechtsfolgen, Konkurrenzen, Verfahren

| Skill | Funktion |
|---|---|
| `rechtsfolge-bestimmen` | Anspruchsinhalt, Höhe, Nebenansprüche |
| `konkurrenzen-anspruchsgrundlagen` | Normkonkurrenzen und Spezialität |
| `verjaehrung-fristen-pruefen` | Verjährung, Hemmung, Neubeginn |
| `verfahrensart-bestimmen` | Passende Verfahrensart und Zuständigkeit |
| `eu-vorabentscheidung-pruefen` | Art. 267 AEUV — Voraussetzungen |
| `grundrechte-pruefung-de-und-grch` | GG und GRCh — Drei-Schritt-Schema |

### E. Output-Erzeugung

| Skill | Funktion |
|---|---|
| `output-juristisch-gestochen-de` | Schriftsatzstil, Rubrum, Tenor |
| `output-alltagssprache-de` | Verständliche Sprache für Betroffene |
| `output-fremdsprachig-en-fr` | Englisch und Französisch (nicht-amtlich) |
| `output-antrag-beschwerde-klageschrift` | Formale Dokument-Bausteine |
| `output-memo-und-mandantenbrief` | Aktennotiz und Mandantenbrief |
| `output-pruefungsdokument-mit-warnhinweisen` | Vollständiges Dokument mit allen Warnhinweisen |

## Lizenz

Apache-2.0 OR MIT — siehe LICENSE im Repository-Root.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 23 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `anwenden-quellenkarte` | Anwenden Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `eu-abgrenzung-einschlaegige-normen` | EU Abgrenzung Einschlaegige Normen im Plugin Subsumtions Pruefer: prüft konkret Klaert die Abgrenzung zwischen nationalem deutschen Recht, Schlaegt anhand eines Lebenssachverhalts einschlaegige, Schlaegt einschlaegige Normen des Unionsre... |
| `eu-vorabentscheidung-falsche-wiese` | EU Vorabentscheidung Falsche Wiese im Plugin Subsumtions Pruefer: prüft konkret Prueft die Voraussetzungen des Vorabentscheidungsersuchens, Warnt vor typischen Falschverortungen im Recht, Ordnet BGB-AT-Fehler in Klausuren. Liefert priori... |
| `interessen-rechtsberatung-rechtsfolgen` | Interessen Rechtsberatung Rechtsfolgen im Plugin Subsumtions Pruefer: prüft konkret Pruefen, Rechtsberatung, Rechtsfolgen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `kommentar-literatur-konkurrenzen` | Kommentar Literatur Konkurrenzen im Plugin Subsumtions Pruefer: prüft konkret Quellenhinweis für vertiefte Subsumtion, Handbuch- oder A, Klaert Konkurrenzfragen zwischen Anspruchsgrundlagen, Prüft die Norm-Historie. Liefert priorisierten... |
| `mandatsabbruch-empfehlung-beweisbedarf` | Mandatsabbruch Empfehlung Beweisbedarf im Plugin Subsumtions Pruefer: prüft konkret Erkennt Indikatoren für Komplexitaetsgrenzen des, Erfasst pro Tatbestandsmerkmal den Beweisbedarf, Verteilt Darlegungs- und Beweislast nach Grundregel (w... |
| `norm-zerlegen-mandantenbrief` | Norm Zerlegen Mandantenbrief im Plugin Subsumtions Pruefer: prüft konkret Zerlegt eine Norm systematisch in ihre Tatbestandsmerkmale, Erzeugt interne Aktennotiz (Rechtsmemo) oder externen, Erzeugt das vollständige Prüfungsdokument mit. L... |
| `output-alltagssprache-de` | Gibt das Subsumtionsergebnis in verstaendlicher Alltagssprache aus: ohne Fachbegriffe oder mit Erklärung, für Mandanten, Betroffene oder Behoerdenmitarbeiter. Behaelt die Strukturierung bei, vermeidet aber Lateinismen und Fachterminologi... |
| `output-antrag-beschwerde-klageschrift` | Erzeugt Tenor-Bausteine, Rubrum und formale Mindestanforderungen für Antrag, Beschwerde und Klageschrift nach ZPO, VwGO, SGG, FGO und BVerfGG. Gibt Pflichtangaben, Fristen und Einreichungshinweise. Kein anwaltlicher Schriftsatz ohne anwa... |
| `output-fremdsprachig-en-fr` | Gibt das Subsumtionsergebnis auf Englisch oder Franzoesisch aus. Enthaelt obligatorischen Hinweis auf nicht-amtliche Übersetzung und Abweichung von deutschen Originalnormen. Nuetzlich für internationale Mandanten, grenzüberschreitende Sa... |
| `output-juristisch-gestochen-de` | Erzeugt Ausgaben im juristischen Schriftsatzstil auf Deutsch: Antrag-Begründung-Beweismittel-Struktur, Subsumtionsdarstellung im Vier-Schritt, Zitierweise nach BGH-Standard, Rubrum, Tenor. Für Schriftsaetze, Klageschriften, Widersprueche... |
| `rechtsfolge-bestimmen-einreden-interaktiver` | Rechtsfolge Bestimmen Einreden Interaktiver im Plugin Subsumtions Pruefer: prüft konkret Bestimmt die Rechtsfolge nach erfolgreicher Subsumtion, Einreden, Interaktiver. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und näc... |
| `schema-schritt-subsumtions` | Schema Schritt Subsumtions im Plugin Subsumtions Pruefer: prüft konkret Schema, Schritt, Subsumtions. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `subsumtion-obersatz-rewrite-klausurton-triage` | Subsumtion Obersatz Rewrite Klausurton Triage im Plugin Subsumtions Pruefer: prüft konkret Führt die klassische juristische Vier-Schritt-Subsumtion, Schreibt falsche oder lueckenhafte Subsumtionen in einen, Interaktiver Einstieg. Liefert... |
| `subsumtions-pruefer-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `subsumtions-pruefer-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `subsumtions-pruefer-start-chronologie-fristen` | Start Chronologie Fristen im Plugin Subsumtions Pruefer: prüft konkret Einstieg, Schnelltriage und Fallrouting im Subsumtions Pruefer-Plugin, Chronologie und Belegmatrix im Plugin subsumtions-pruefer, Fristen- und Risikoampel im Plugin s... |
| `subsumtions-pruefer-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `tatbestandsmerkmale-vier-zerlegen` | Tatbestandsmerkmale Vier Zerlegen im Plugin Subsumtions Pruefer: prüft konkret Tatbestandsmerkmale, Behörden-, Gerichts- oder Registerweg im Plugin subsumtions-pruefer, Zerlegen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoamp... |
| `tbm-grundrechte-grch-kandidatenloesung` | TBM Grundrechte Grch Kandidatenloesung im Plugin Subsumtions Pruefer: prüft konkret Prüft rechtshindernde, rechtsvernichtende und rechtshemmende Einwendungen und Ei, Prüft Grundrechte nach GG (Drei-Schritt, Prueft abgegebene Klausur- ode... |
| `unbestimmte-rechtsbegriffe-ungeschriebene` | Unbestimmte Rechtsbegriffe Ungeschriebene im Plugin Subsumtions Pruefer: prüft konkret Prüft unbestimmte Rechtsbegriffe, Identifiziert judicativ entwickelte ungeschriebene, Ermittelt interaktiv das Nutzerziel (Anspruchsdurchsetzung, Abwe... |
| `verfahrensart-bestimmen-verjaehrung` | Verfahrensart Bestimmen Verjaehrung im Plugin Subsumtions Pruefer: prüft konkret Bestimmt die passende Verfahrensart, Prüft Verjährungsfristen, Prüft Generalklauseln wie Treu und Glauben (§ 242 BGB), gute Sitten (§ 138 BGB). Liefert prio... |
| `waehlen-rechtsprechung-recherche-europarecht` | Waehlen Rechtsprechung Recherche Europarecht im Plugin Subsumtions Pruefer: prüft konkret Output wählen im Plugin subsumtions-pruefer, Gibt eine Strategie für die Rechtsprechungsrecherche, Europarecht. Liefert priorisierten Output mit No... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
