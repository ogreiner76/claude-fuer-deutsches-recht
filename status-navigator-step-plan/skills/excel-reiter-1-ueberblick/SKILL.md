---
name: excel-reiter-1-ueberblick
description: "Baut Reiter 1 der Step-Plan-Excel: Ueberblick aller fuer die Durchsetzung erforderlichen Dokumente. Spalten Dokument, Datum, Verfuegbarkeit, Unterschriftsstatus, Unterzeichnet von (Partei und Funktion), Rechtsgrundlage (Klausel im zugrunde liegenden Vertrag) und Zweck. Mit Ampelfaerbung und Sortierung nach Vertragsebene."
---

# Reiter 1 Ueberblick Statuslage

> **Hinweis Dokumentenverarbeitung:** Dieser Skill ist Teil des Plugins
> `status-navigator-step-plan` und arbeitet bewusst ohne Normen- und
> Rechtsprechungs-Anker. Reine Dokumentenverarbeitung und Workflow-Strukturierung
> im Sinne des Prompt des Monats von Tom Braegelmann. Die rechtliche Pruefung
> des Materials bleibt anwaltliche Aufgabe.

## Rolle und Fokus
Reiter 1 ist der oberste Gesamtueberblick. Hier landet ALLES, was fuer die
Durchsetzung des Ziels benoetigt wird: vorhanden, fehlend, fragwuerdig.
Reiter 2 bis 4 sind Detailansichten desselben Materials.

## Vorlage-Bezug
Reiter 1 folgt der Excel-Vorlage `step-plan-document-tracker-template.xlsx`.
Spalten in der Reihenfolge der Vorlage:

| Spalte | Inhalt | Bemerkung |
|---|---|---|
| Dokument | Bezeichnung der Urkunde, des Schreibens oder Bescheids | sprechend, eindeutig |
| Datum | Datum des Dokuments | bei Fehlen: FEHLT, sonst Datum |
| Verfuegbarkeit | vorliegend / FEHLT / Entwurf / fragwuerdig | farblich gefuehrt (Ampel) |
| Unterschriftsstatus | vollstaendig / fragwuerdig / Entwurf / n/a | siehe Skill unterschriftspruefung |
| Unterzeichnet von (Partei und Funktion) | konkrete Person + Funktion | wer ist Vertretungsbefugt? |
| Rechtsgrundlage (Klausel im zugrunde liegenden Vertrag) | Paragrafen, Vertragsklausel | Hinweis, keine Wertung |
| Zweck | warum braucht es das Dokument | eine Zeile reicht |

## Vorgehen Schritt fuer Schritt
1. **Rolle und Ziel klaeren.** Wer fragt, welche Rolle (RAin, Inhouse, GF),
   welches Ziel? Ein Satz oben in der Akte, nicht in der Excel.
2. **Material sichten.** Akte chronologisch durchgehen, jedes Dokument einzeln
   notieren. Mehrere Versionen desselben Dokuments einzeln eintragen
   (siehe Skill diskrepanzen-aufdecken).
3. **Strukturieren.** In Reiter 1 eintragen. Status setzen.
4. **Ampelfaerbung.**
   - GRUEN: vorliegend und vollstaendig unterzeichnet
   - GELB: in Bearbeitung, Entwurf, Fristlauf
   - ROT: fehlt, fragwuerdig, schwebend unwirksam, Zugang ungeklaert
5. **Reiter 2 und 3 daraus ableiten.** Reiter 2 = alles GRUENE plus GELBE
   mit Original. Reiter 3 = alles ROTE plus GELBE in Bearbeitung.
6. **Reiter 4 fuer alles, das zu erstellen oder zu beschaffen ist** (siehe
   Skill excel-reiter-4-workflow).

## Anwendungsbeispiel
Mandat: 200-MW-Batteriespeicher LausitzStorage, 22 Vertragsdokumente,
3 Cap-Table-Versionen, 1 Drawstop-Schreiben. Reiter 1 zeigt alle 22
Dokumente plus die drei Cap Tables auf einer einzigen scrollbaren Seite,
sortiert nach Vertragstyp. Auf einen Blick: 11 GRUEN, 6 GELB, 5 ROT.

## Output-Module
- Strukturierte Eintraege fuer Reiter 1 der Excel-Arbeitsmappe
- Ampelfarbe je Zeile als Hex-Vorgabe (GRUEN C6EFCE, GELB FFEB9C, ROT FFC7CE)
- Sortierung nach Vertragsebene (Pacht, Netz, Genehmigung, Finanzierung,
  Gesellschaft, EPC)
- Hinweis am Zeilenende bei Diskrepanzen mit anderen Dokumenten

## Grenzen
- **Keine rechtliche Bewertung.** Wirksamkeitspruefung bleibt anwaltliche Aufgabe.
- **Keine Vollstaendigkeitsgarantie.** Mehrfachpruefung an Originalen erforderlich.
- **Diskrepanz-Hinweise sind Hinweise.** Anwaltliche Verifikation immer.
- **Datenschutz und Berufsrecht.** DSGVO, § 203 StGB, §§ 43a, 43e BRAO beachten.
  Erstpruefung mit anonymisierten Testdaten.

## Plugin-Kontext
Reiter 1 steuert die Reiter 2, 3 und 4. Inhaltliche Tiefe entsteht erst in
diesen Folge-Reitern. Wer Reiter 1 sauber baut, hat 80 Prozent der
Status-Navigator-Arbeit erledigt.
