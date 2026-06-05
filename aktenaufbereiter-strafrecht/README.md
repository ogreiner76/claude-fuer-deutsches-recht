# Aktenaufbereiter Strafrecht

<!-- BEGIN plugin-sofort-download-section (autogen) -->
## ⬇️ Sofort-Downloads

Direkt-Downloads ohne Umwege. Die URLs sind stabil und zeigen immer auf die aktuelle Version (`latest`-Release).

### Plugin als ZIP

| Inhalt | Download |
| --- | --- |
| **Dieses Plugin** (`aktenaufbereiter-strafrecht`) | [`aktenaufbereiter-strafrecht.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/aktenaufbereiter-strafrecht.zip) |

### Demonstrations-Akten

| Akte | PDF lesen | Akten-ZIP |
| --- | --- | --- |
| **EG Juwel Stuttgart — Sammelverfahren bandenmaessiger schwerer Raub, Königstrasse** (`sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub`) | [Gesamt-PDF lesen](../testakten/sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub/gesamt-pdf/sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub_gesamt.pdf) | [`testakte-sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub.zip`](https://github.com/Klotzkette/claude-fuer-deutsches-recht/releases/latest/download/testakte-sammelakte-bandentaeter-eg-juwel-stuttgart-koffer-raub.zip) |

<!-- END plugin-sofort-download-section (autogen) -->

Aktenaufbereiter für die Strafverteidigung. Bringt große Strafakten in den Griff durch sechs Excel-fähige Übersichten — Aktenvorblatt; Personenverzeichnis; Tatkomplexe; Beziehungen; Chronologie; Fristen. Fortlaufend ergänzbar. Erkennt Lücken und Widersprüche. Kein Ersatz für Aktenlektüre.

## Installation in Claude Code

1. ZIP herunterladen (Link oben).
2. Claude Code → **Customize Plugins** → **Install from .zip** → Datei wählen.
3. Fertig. Skills sind sofort verfügbar.

> **Hinweis:** Für den ZIP-Upload muss das Archiv direkt `.claude-plugin/plugin.json`, `skills/`, `assets/` und `references/` im ZIP-Root enthalten. **Nicht** das komplette Repository-ZIP aus "Code → Download ZIP" verwenden.

## Enthaltene Skills

| Skill | Zweck |
| --- | --- |
| `aktenaufbereiter-strafrecht` | Strukturierte Aufbereitung strafrechtlicher Akten für die Verteidigung. Erzeugt sechs Übersichten — Aktenvorblatt mit Blattangaben; Personenverzeichnis mit Rolle und Erstnennung; Tatkomplex- und Vorwurfsverzeichnis … |

## Lizenz

Apache-2.0 OR MIT — Auswahl beim Empfänger.


<!-- BEGIN SKILLS-OVERVIEW (auto-generated) -->

## Alle Skills im Ueberblick

Automatisch generierte Komplett-Liste aller 24 Skills in diesem Plugin. Beschreibungen stammen aus dem `description`-Feld der jeweiligen SKILL.md.

| Skill | Beschreibung |
| --- | --- |
| `aktenaufbereiter-strafrecht` | Strafverteidiger erhaelt Strafakte nach § 147 StPO Akteneinsicht und will diese strukturiert aufbereiten. Wirtschaftsstrafverfahren BtM-Verfahren Vermögensdelikte komplexe Strafverfahren. Sechs Übersichten: Aktenvorblatt Personenverzeich... |
| `aktenaufbereiter-strafrecht-anschluss-routing` | Anschluss-Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `aktenaufbereiter-strafrecht-dokumente-intake` | Dokumentenintake: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `aktenaufbereiter-strafrecht-einstieg-routing` | Einstieg und Routing: Einstieg und Routing; klärt Rolle, Ziel, Frist, Aktenlage und den passenden nächsten Fachpfad. |
| `aktenaufbereiter-strafrecht-mandant-redteam-gate` | Mandant Redteam Gate im Strafakten-Aufbereitung: prüft konkret Mandantenkommunikation im Plugin aktenaufbereiter-strafrecht, Red-Team Qualitygate im Plugin aktenaufbereiter-strafrecht, Chronologie aller Verfahrensschritte. Liefert priori... |
| `aktenaufbereiter-strafrecht-output-waehlen` | Output wählen im Strafakten-Aufbereitung: Diese Output-Weiche für Aktenaufbereiter Strafrecht entscheidet, ob Memo, Antrag, Schriftsatz, Tabelle, Risikoampel, Fragenliste oder Mandantenbrief der richtige nächste Schritt ist. |
| `aktenaufbereiter-strafrecht-quellen-livecheck` | Rechtsquellen-Livecheck: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `aktenaufbereiter-strafrecht-start-chronologie-fristen` | Start Chronologie Fristen im Strafakten-Aufbereitung: prüft konkret Einstieg, Schnelltriage und Fallrouting im Aktenaufbereiter, Chronologie und Belegmatrix im Plugin, Fristen- und Risikoampel im Plugin. Liefert priorisierten Output mit... |
| `aktenaufbereiter-strafrecht-unterlagen-luecken` | Unterlagen und Lücken: sortiert Dokumente, erkennt Lücken, ordnet Beweiswert und formuliert gezielte Rückfragen. |
| `akteneinsicht-uebersicht-aktenvorblatt` | Akteneinsicht Uebersicht Aktenvorblatt im Strafakten-Aufbereitung: prüft konkret Akteneinsicht systematisch auswerten, Erstes Aktenvorblatt fuer eine Strafakte erstellen, Anklageschrift in arbeitsfaehige Bausteine zerlegen. Liefert prior... |
| `beweismittel-katalog-beweisverwertungsverbote` | Beweismittel Katalog Beweisverwertungsverbote im Strafakten-Aufbereitung: prüft konkret Beweismittel-Katalog fuer die Verteidigung, Beweisverwertungsverbote pruefen, Beziehungen zwischen Personen und Tatkomplexen sichtbar. Liefert priori... |
| `beziehungen-spezial-chronologie-ergaenzbar` | Beziehungen Spezial Chronologie Ergaenzbar im Strafakten-Aufbereitung: prüft konkret Beziehungen, Chronologie, Ergaenzbar. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `erkennt-fehlerkatalog` | Erkennt Fehlerkatalog: Fehlerbremse; prüft Fristen, Zuständigkeit, Beweislast, Quellen und taktische Risiken vor Abgabe oder Versand. |
| `ersatz-sonderfall-excel-faehige` | Ersatz Sonderfall Excel Faehige im Strafakten-Aufbereitung: prüft konkret Ersatz, Excel, Faehige. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `fortlaufend-luecken-personenverzeichnis` | Fortlaufend Luecken Personenverzeichnis im Strafakten-Aufbereitung: prüft konkret Fortlaufend, Luecken, Personenverzeichnis. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `fristenliste-strafverfahren-aktenlektuere` | Fristenliste Strafverfahren Aktenlektuere im Strafakten-Aufbereitung: prüft konkret Fristenliste fuer ein Strafverfahren, Aktenlektuere, Fristen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `kronzeugen-regelung-opferzeugen-besondere` | Kronzeugen Regelung Opferzeugen Besondere im Strafakten-Aufbereitung: prüft konkret Spezialfall Kronzeugenregelung § 46b StGB, Opferzeugen bei Sexualdelikten, Kindern, Schutzschriftsachen behandeln. Liefert priorisierten Output mit Norm-... |
| `revision-rechtsfehler-aktenaufbereiter` | Revision Rechtsfehler Aktenaufbereiter im Strafakten-Aufbereitung: prüft konkret Revisionsschrift vorbereiten, Aktenaufbereiter, Aktenvorblatt. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `sechs-u-haft-aussageanalyse` | Sechs U Haft Aussageanalyse im Strafakten-Aufbereitung: prüft konkret Sechs, U-Haft-Fristen ueberwachen, Zeugenaussage mit aussagepsychologischen Realkennzeichen. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem... |
| `strafbefehl-einspruchsstrategie` | Strafbefehl Einspruchsstrategie im Strafakten-Aufbereitung: prüft konkret Strafbefehl § 410 StPO, Strafzumessung § 46 StGB systematisch, Tatkomplexe einer Strafakte gliedern. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel u... |
| `strafrecht-strafverteidigung-uebersichten` | Strafverteidigung Uebersichten im Strafakten-Aufbereitung: prüft konkret Strafrecht, Strafverteidigung, Uebersichten. Liefert priorisierten Output mit Norm-Pinpoints, Risikoampel und nächstem Schritt. |
| `tatkomplexe-quellenkarte` | Tatkomplexe Quellenkarte: Quellenprüfung; Normenstand, Rechtsprechung, Behördenpraxis und Zitierfähigkeit werden vor einer tragenden Aussage verifiziert. |
| `vermoegensabschoepfung-dritt-einziehung` | Vermoegensabschoepfung Dritt Einziehung im Strafakten-Aufbereitung: prüft konkret Spezialfall Dritt-Arrest in der Vermoegensabschoepfung §§, Vermoegensabschoepfung §§ 73 ff, Verstaendigung im Strafverfahren § 257c StPO vorbereiten. Liefe... |
| `widersprueche-beweislast-strafakte-gate` | Widersprueche Beweislast Strafakte Gate im Strafakten-Aufbereitung: prüft konkret Widersprueche, Quality-Gate fuer eine aufbereitete Strafakte, Strafakte fuer Uebergabe an Sozietaetskollegin, Wahlverteidiger oder Pflichtvert. Liefert pri... |

<!-- END SKILLS-OVERVIEW (auto-generated) -->
