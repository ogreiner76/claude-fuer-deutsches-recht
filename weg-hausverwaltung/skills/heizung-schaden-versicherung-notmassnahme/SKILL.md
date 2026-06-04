---
name: heizung-schaden-versicherung-notmassnahme
description: "Bearbeitet Heizungsstörungen, Wasserschäden, Feuchtigkeit, Frost, Versicherung und Notmaßnahmen in WEG-Anlagen. Prüft Zuständigkeit, Sofortmaßnahmen, Beweise, Handwerker, Beschlussbedarf, Umlage und Mieterkommunikation. Output: Maßnahmenplan."
---

# Heizung, Schaden, Versicherung, Notmaßnahme

## V90 Fachkern — Miet- und WEG-Recht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Heizung, Schaden, Versicherung, Notmaßnahme` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** BGB §§ 535 ff., 536, 543, 546a, 548, 556, 556a, 558 ff., 573 ff.; BetrKV; HeizkostenV; WEG §§ 18, 19, 20, 23, 24, 28, 44, 45; GEG; CO2KostAufG.
- **Verifizierte Anker:** BGH, Urteil vom 20.01.2016 - VIII ZR 93/15 (formelle Betriebskostenabrechnung); BGH, Urteil vom 15.12.2021 - VIII ZR 66/20 (Belegeinsicht Originale/Kopien); BGH, Urteil vom 14.02.2025 - V ZR 128/23 (§ 16 Abs. 2 Satz 2 WEG, Rücklagen/Kostenverteilung); BGH, Urteil vom 14.02.2025 - V ZR 86/24 (§ 20 WEG, bauliche Veränderung, Vorbefassung/Beschlussersetzung).
- **Arbeitsmodus:** Immer erst Verhältnis Miete/WEG/Gewerbe/Verwaltung trennen, dann Frist, Beschlusskompetenz, Umlagefähigkeit, Belege, Gebrauchsnachteil und Kostenfolge prüfen.
- **Outputpflicht:** Abrechnungsprüftabelle, Beschlussvorschlag, Anfechtungs-/Beschlussersetzungsskizze, Mietermail, Vermieterschreiben oder Verwalter-To-do-Liste.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Fachkern: Heizung, Schaden, Versicherung, Notmaßnahme
- **Spezialgegenstand:** Heizung, Schaden, Versicherung, Notmaßnahme wird als eigener Falltyp behandelt; der Skill muss ein konkretes Ergebnis liefern, nicht nur Einstieg und Routing.
- **Normen-/Quellenanker:** WEG §§ 18-28, 44/45, BGB-Miet-/Werkvertragsrecht, BetrKV, HeizkostenV, GEG, DSGVO und landesrechtliche Bau-/Sicherheitsfragen.
- **Entscheidende Weiche:** Trenne Beschlusskompetenz, ordnungsmäßige Verwaltung, Kostenverteilung, Anfechtungsfrist, Verwalterpflicht, Belegprüfung und Vollzug.
- **Lösungsoutput:** Erzeuge eine fallbezogene Matrix `Norm / Tatbestand / Beleg / Risiko / Gegenargument / nächster Schritt` und benenne passende Anschluss-Skills nur, wenn sie wirklich eine Vertiefung lösen.


Nutze diesen Skill bei Heizungsausfall, Druckverlust, Wasserschaden, Feuchtigkeit, Geruch aus Technikräumen, Frostschäden oder streitiger Kostenverteilung.

## Sofortprüfung

1. Gefahr für Personen oder Gebäude?
2. Gemeinschaftseigentum oder Sondereigentum?
3. Darf/muss die Verwaltung sofort handeln?
4. Versicherung unverzüglich informieren?
5. Beweise sichern: Fotos, Feuchtewerte, Handwerkerbericht, Temperaturprotokoll, Zeugen.
6. Mieterkommunikation nötig?
7. Beschluss nachholen oder Maßnahme auf nächste Versammlung setzen?

## Dokumentationspaket

- Störungsmeldung mit Uhrzeit
- Handwerker-Notbericht
- Fotos/Video
- betroffene Einheiten
- Kostenangebot oder Rechnung
- Versicherungsnummer und Schadenmeldung
- Beschluss- oder Eilmaßnahmenvermerk
- Mieterminderung-/Nebenkosten-Risiko für vermietende Eigentümer

## Beschlussbaustein

```text
Die Gemeinschaft beschließt, die Verwaltung zu beauftragen und zu bevollmächtigen, die zur Beseitigung der Heizungsstörung/des Wasserschadens erforderlichen Maßnahmen am Gemeinschaftseigentum zu beauftragen, Angebote einzuholen, Versicherungsleistungen geltend zu machen und die Maßnahme bis zu einem Kostenrahmen von [...] EUR brutto umzusetzen. Die Finanzierung erfolgt aus [...]. Über Mehrkosten ist der Beirat unverzüglich zu informieren.
```

## Red Flags

- Schaden wird als Sondereigentum abgetan, obwohl Steigleitungen, Dach, Heizzentrale oder Abdichtung betroffen sind.
- Versicherung wird zu spät informiert.
- Eigentümer werden ohne Beschluss mit hohen Kosten belastet.
- Mieterminderungen und Ausfallrisiken werden ignoriert.
- Technische Sofortmaßnahme wird mit Modernisierung vermischt.


## Qualitäts-Hardening

- Arbeite aktennah: Tatsachen, Belege, Fristen, Zuständigkeit und gewünschtes Arbeitsprodukt zuerst klären.
- Keine Rechtsprechung aus Modellwissen zitieren. Jede Entscheidung vor Ausgabe mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei oder amtlich prüfbarer Quelle absichern.
- Keine BeckRS-, juris-, Kommentar-, Handbuch- oder Aufsatz-Blindzitate. Literatur nur verwenden, wenn der Nutzer sie bereitstellt oder ein lizenzierter Live-Zugriff im konkreten Arbeitsschritt dokumentiert ist.
- Wenn eine Quelle, Randnummer, Behördenpraxis oder Frist nicht sicher geprüft ist, sichtbar als Prüfpunkt markieren und keine Scheinpräzision erzeugen.
- Ergebnisse so liefern, dass sie sofort weiterverwendbar sind: Kurzbild, Prüfpfad, Risikoampel, Lückenliste und konkrete nächste Schritte.
