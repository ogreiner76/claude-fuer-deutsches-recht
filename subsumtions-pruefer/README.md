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
| `allgemein-workflow-chronologie-fristen` | Nutze dies, wenn Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fristen Und Risikoampel im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Allgemein, Workflow Chronologie Und Belegmatrix, Workflow Fri... |
| `anwenden-quellenkarte` | Nutze dies, wenn Anwenden Quellenkarte im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Welche amtliche Quelle prüfe ich zuerst?; Gibt es aktuelle Rechtsprechung?; Bitte Fundstellen verifizieren.. |
| `dokumente-intake` | Nutze dies, wenn Dokumentenintake im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `einstieg-routing` | Nutze dies, wenn Einstieg und Routing im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Ich habe ein neues Thema im Bereich Subsumtions Prüfer.; Welche Unterlagen brauchen Sie?; Welcher Spezialskill passt?. |
| `eu-abgrenzung-einschlaegige-normen` | Nutze dies, wenn De Eu Recht Abgrenzung, Einschlaegige Normen Vorschlagen De, Einschlaegige Normen Vorschlagen Eu im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Bitte De Eu Recht Abgrenzung, Einschlaegige Normen V... |
| `eu-vorabentscheidung-falsche-wiese` | Nutze dies, wenn Eu Vorabentscheidung Prüfen, Falsche Wiese Warnung, Fehlerklasse Bgb At Training im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehen?; Bitte red-team prüfen.; Welche Frist ode... |
| `interessen-rechtsberatung-rechtsfolgen` | Nutze dies, wenn Spezial Prüfen Mehrparteien Konflikt Und Interessen, Spezial Rechtsberatung Internationaler Bezug Und Schnittstellen, Spezial Rechtsfolgen Zahlen Schwellen Und Berechnung im Plugin Subsumtions Prüfer konkret bearbeitet w... |
| `kommentar-literatur-konkurrenzen` | Nutze dies, wenn Kommentar Und Literatur Hinweis, Konkurrenzen Anspruchsgrundlagen, Norm Historie Und Aenderungen im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Kommentar Und Literatur Hinweis, Konkurrenzen... |
| `mandatsabbruch-empfehlung-beweisbedarf` | Nutze dies, wenn Mandatsabbruch Empfehlung An Fachanwalt, Beweisbedarf Und Belege Erfassen, Darlegungs Und Beweislast Verteilen im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Mandatsabbruch Empfehlung An Fac... |
| `norm-zerlegen-mandantenbrief` | Nutze dies, wenn Norm Zerlegen In Tatbestandsmerkmale, Output Memo Und Mandantenbrief, Output Pruefungsdokument Mit Warnhinweisen im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt... |
| `output-alltagssprache-de` | Gibt das Subsumtionsergebnis in verstaendlicher Alltagssprache aus: ohne Fachbegriffe oder mit Erklärung, für Mandanten, Betroffene oder Behoerdenmitarbeiter. Behaelt die Strukturierung bei, vermeidet aber Lateinismen und Fachterminologi... |
| `output-antrag-beschwerde-klageschrift` | Erzeugt Tenor-Bausteine, Rubrum und formale Mindestanforderungen für Antrag, Beschwerde und Klageschrift nach ZPO, VwGO, SGG, FGO und BVerfGG. Gibt Pflichtangaben, Fristen und Einreichungshinweise. Kein anwaltlicher Schriftsatz ohne anwa... |
| `output-fremdsprachig-en-fr` | Gibt das Subsumtionsergebnis auf Englisch oder Franzoesisch aus. Enthaelt obligatorischen Hinweis auf nicht-amtliche Übersetzung und Abweichung von deutschen Originalnormen. Nuetzlich für internationale Mandanten, grenzüberschreitende Sa... |
| `output-juristisch-gestochen-de` | Erzeugt Ausgaben im juristischen Schriftsatzstil auf Deutsch: Antrag-Begründung-Beweismittel-Struktur, Subsumtionsdarstellung im Vier-Schritt, Zitierweise nach BGH-Standard, Rubrum, Tenor. Für Schriftsaetze, Klageschriften, Widersprueche... |
| `rechtsfolge-bestimmen-einreden-interaktiver` | Nutze dies, wenn Rechtsfolge Bestimmen, Spezial Einreden Compliance Dokumentation Und Akte, Spezial Interaktiver Erstpruefung Und Mandatsziel im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Was kann hier schiefgehe... |
| `schema-schritt-subsumtions` | Nutze dies, wenn Spezial Schema Verhandlung Vergleich Und Eskalation, Spezial Schritt Schriftsatz Brief Und Memo Bausteine, Spezial Subsumtions Tatbestand Beweis Und Belege im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Aus... |
| `subsumtion-obersatz-rewrite-klausurton-triage` | Nutze dies, wenn Subsumtion Obersatz Definition Untersatz Ergebnis, Subsumtions Rewrite Klausurton, Triage Rechtsfrage Oder Norm im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Subsumtion Obersatz Definition... |
| `tatbestandsmerkmale-vier-zerlegen` | Nutze dies, wenn Spezial Tatbestandsmerkmale Dokumentenmatrix Und Lueckenliste, Spezial Vier Behörden Gericht Und Registerweg, Spezial Zerlegen Risikoampel Und Gegenargumente im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. A... |
| `tbm-grundrechte-grch-kandidatenloesung` | Nutze dies, wenn Gegen Tbm Und Einreden Prüfen, Grundrechte Prüfung De Und Grch, Kandidatenloesung Subsumtion Prüfen im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Gegen Tbm Und Einreden Prüfen, Grundrechte... |
| `unbestimmte-rechtsbegriffe-ungeschriebene` | Nutze dies, wenn Unbestimmte Rechtsbegriffe Prüfen, Ungeschriebene Merkmale Judikatur, Ziel Und Rechtsweg Bestimmung im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Unbestimmte Rechtsbegriffe Prüfen, Ungeschr... |
| `unterlagen-luecken` | Nutze dies, wenn Unterlagen und Lücken im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Ich lade Unterlagen hoch.; Was fehlt noch?; Bitte Dokumente sortieren.. |
| `verfahrensart-bestimmen-verjaehrung` | Nutze dies, wenn Verfahrensart Bestimmen, Verjaehrung Fristen Prüfen, Generalklauseln Prüfen im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Verfahrensart Bestimmen, Verjaehrung Fristen Prüfen, Generalklausel... |
| `waehlen-rechtsprechung-recherche-europarecht` | Nutze dies, wenn Workflow Output Waehlen, Rechtsprechung Recherche Strategie, Spezial Europarecht Fristen Form Und Zustaendigkeit im Plugin Subsumtions Prüfer konkret bearbeitet werden soll. Auslöser: Bitte Workflow Output Waehlen, Recht... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
