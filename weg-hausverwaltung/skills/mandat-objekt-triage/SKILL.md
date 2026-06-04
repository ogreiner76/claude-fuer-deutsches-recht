---
name: mandat-objekt-triage
description: "Erfasst eine WEG-/Hausverwaltungsakte (Stand 05/2026): Objekt, Rollen, Teilungserklärung, Gemeinschaftsordnung, Verwaltervertrag, Beschlusssammlung, Abrechnungen, Vermögensbericht, Angebote, Fristen, Risiken und nächsten Workflow. Identifiziert Fristen aus § 45 WEG, § 556 BGB sowie GEG-/CO2KostAufG-Schnittstellen."
---

# Mandat- und Objekt-Triage

## V90 Fachkern — Miet- und WEG-Recht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Mandat- und Objekt-Triage` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** BGB §§ 535 ff., 536, 543, 546a, 548, 556, 556a, 558 ff., 573 ff.; BetrKV; HeizkostenV; WEG §§ 18, 19, 20, 23, 24, 28, 44, 45; GEG; CO2KostAufG.
- **Verifizierte Anker:** BGH, Urteil vom 20.01.2016 - VIII ZR 93/15 (formelle Betriebskostenabrechnung); BGH, Urteil vom 15.12.2021 - VIII ZR 66/20 (Belegeinsicht Originale/Kopien); BGH, Urteil vom 14.02.2025 - V ZR 128/23 (§ 16 Abs. 2 Satz 2 WEG, Rücklagen/Kostenverteilung); BGH, Urteil vom 14.02.2025 - V ZR 86/24 (§ 20 WEG, bauliche Veränderung, Vorbefassung/Beschlussersetzung).
- **Arbeitsmodus:** Immer erst Verhältnis Miete/WEG/Gewerbe/Verwaltung trennen, dann Frist, Beschlusskompetenz, Umlagefähigkeit, Belege, Gebrauchsnachteil und Kostenfolge prüfen.
- **Outputpflicht:** Abrechnungsprüftabelle, Beschlussvorschlag, Anfechtungs-/Beschlussersetzungsskizze, Mietermail, Vermieterschreiben oder Verwalter-To-do-Liste.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Fachkern: Mandat- und Objekt-Triage
- **Spezialgegenstand:** Mandat- und Objekt-Triage wird als eigener Falltyp behandelt; der Skill muss ein konkretes Ergebnis liefern, nicht nur Einstieg und Routing.
- **Normen-/Quellenanker:** WEG §§ 18-28, 44/45, BGB-Miet-/Werkvertragsrecht, BetrKV, HeizkostenV, GEG, DSGVO und landesrechtliche Bau-/Sicherheitsfragen.
- **Entscheidende Weiche:** Trenne Beschlusskompetenz, ordnungsmäßige Verwaltung, Kostenverteilung, Anfechtungsfrist, Verwalterpflicht, Belegprüfung und Vollzug.
- **Lösungsoutput:** Erzeuge eine fallbezogene Matrix `Norm / Tatbestand / Beleg / Risiko / Gegenargument / nächster Schritt` und benenne passende Anschluss-Skills nur, wenn sie wirklich eine Vertiefung lösen.


Stand: 05/2026.

## Ziel

Aus einer ungeordneten Verwaltungsakte entsteht ein arbeitsfähiges Objektprofil mit Fristen, Zuständigkeiten, Dokumentenlage und nächstem Skill.

## Abfrage

| Bereich | Klären |
| --- | --- |
| Objekt | Adresse, Einheiten, Wohn-/Gewerbeanteil, Baujahr, Verwaltung seit wann, Bundesland |
| Rollen | GdWE, Verwalter, Beirat, einzelne Eigentümer, vermietende Eigentümer, Mieter |
| Grundakte | Teilungserklärung, Gemeinschaftsordnung, Aufteilungsplan, Beschlusssammlung |
| Verwaltung | Verwaltervertrag, Vollmachten, Beiratsbestellung, Sonderzuständigkeiten, Sondervergütungen |
| Finanzen | Wirtschaftsplan, Jahresabrechnung, Vermögensbericht, Erhaltungsrücklage, Hausgeldrückstände, Sonderumlagen |
| Bau/Technik | Instandhaltungsstau, Angebote, Gutachten, Gewährleistungsfristen, GEG-Heizungsstatus, Steckersolar/Wallbox-Anträge |
| Streit | laufende Beschlussklagen, Beschwerden, Störungen, Datenschutzprobleme, vermieterspezifische Mieter-Konflikte |
| Energie/CO₂ | Energieausweis, Brennstoff/Heizart, CO₂-Stufe nach CO2KostAufG, anstehende GEG § 71-Fristen |

## Arbeitsweise

1. **Dokumente benennen und Lücken markieren.** (Liste: vorhanden / fehlt / unklar)
2. **Fristen und irreversible Risiken nach oben ziehen.**
   - § 45 WEG: 1 Monat Klage, 2 Monate Begründung (BGH V ZR 33/23).
   - 1 Jahr Erkundigungsobliegenheit bei Zustellungsverzug (BGH V ZR 17/24).
   - § 556 Abs. 3 BGB: 12 Monate Betriebskostenabrechnung Mieter.
   - Gewährleistung Werkvertrag 5 J. / VOB 4 J.
   - GEG § 71 Übergangsfristen für Heizungstausch (Großstädte 30.06.2026, sonst 30.06.2028).
3. **Vorgänge in Körbe sortieren**: Versammlung, Beschluss, Abrechnung, Bau, Hausgeld, Kommunikation, Datenschutz, Gericht.
4. **Primären Folge-Skill vorschlagen**.

## Output

- `objektprofil.md` (Adresse, Einheiten, Beteiligte, Verwaltervertrag, Beirat, Schlüssel)
- `fristen-und-risiken.md` (nach Datum sortiert, mit Wirkung und Maßnahme)
- `dokumentenluecken.md`
- Skill-Routing mit Priorität (welcher Skill zuerst, mit Begründung)

## Cross-Refs

- Bei Versammlung-Stapel → `eigentuemerversammlung-vorbereiten`
- Bei Abrechnungsfragen → `wirtschaftsplan-jahresabrechnung-28-weg`
- Bei Hausgeld/Liquidität → `hausgeld-sonderumlage-liquiditaet`
- Bei baulichen Veränderungen → `bauliche-veraenderungen-20-weg`
- Bei Konflikt / Eskalation → `eskalation-anwalt-amtsgericht`

## Quellenpflicht

`rechtsstand-mai-2026-faktenbank` laden, sobald rechtliche Bewertung erfolgt.


## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei oder amtlich prüfbarer Quelle absichern.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate. Literatur nur verwenden, wenn der Nutzer sie bereitstellt oder ein lizenzierter Live-Zugriff im konkreten Arbeitsschritt dokumentiert ist.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren und keine Scheinpräzision erzeugen.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
