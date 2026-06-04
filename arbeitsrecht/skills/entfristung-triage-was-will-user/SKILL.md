---
name: entfristung-triage-was-will-user
description: "Einstieg Entfristungsklage-Workflow: Erkennung ob Nutzer Befristungskontrollklage oder Entfristungsklage anstrebt; Abgrenzung zu Kündigungsschutzklage; Überblick Prüfprogramm TzBfG; Weiterleitung zu passenden Folge-Skills."
---

# Entfristungsklage: Was will der Nutzer?

## V90 Fachkern — Arbeitsrecht
- **Problemfokus dieses Skills:** Bleibe beim konkreten Titel `Entfristungsklage: Was will der Nutzer?` und löse die dort angelegte Fachfrage; keine Flucht in allgemeines Routing, außer eine echte Frist oder Zuständigkeit ist unklar.
- **Normenradar:** BGB §§ 611a, 613a, 615, 623; KSchG §§ 1, 4, 7; TzBfG §§ 14, 15, 16; AGG §§ 1, 3, 7, 15, 22; EntgTranspG §§ 3, 5, 7; BUrlG §§ 1, 3, 7; BetrVG §§ 87, 99, 102; ArbZG; NachwG; SGB IX §§ 164, 167, 168.
- **Verifizierte Anker:** BAG, Urteil vom 23.10.2025 - 8 AZR 300/24 (Entgeltgleichheit, Paarvergleich, Beweislast, bundesarbeitsgericht.de); BAG, Urteil vom 03.06.2025 - 9 AZR 104/24 (kein Verzicht auf gesetzlichen Mindesturlaub im bestehenden Arbeitsverhältnis); bei Kündigungszugang immer § 623 BGB, Zugang nach § 130 BGB, Dreiwochenfrist §§ 4, 7 KSchG und Beweis des konkreten Umschlags trennen.
- **Arbeitsmodus:** Zuerst Status, Zugang, Frist, Beteiligungsrechte, Sonderkündigungsschutz, Beweislast und prozessualen nächsten Schritt sichern; dann erst Materiellrecht vertiefen.
- **Outputpflicht:** Fristenblatt, Zugangsmatrix, Beweisangebot, Mandantenmail, Betriebsrats-/Gegnerbrief oder Klage-/Erwiderungsbaustein.
- **Fehlerbremse:** Tragende Normen/Entscheidungen live oder aus der Akte verifizieren; Rechtsprechung nur mit Gericht, Entscheidungsform, Datum, Aktenzeichen und frei prüfbarer Quelle. Keine BeckRS-, juris-, Kommentar- oder Aufsatz-Blindzitate aus Modellwissen.


## Zentrale Normen (Überblick)

- § 17 TzBfG — 3-Wochen-Klagefrist (kritischste Frist; läuft auch bei Weiterbeschäftigung)
- § 14 Abs. 4 TzBfG — Schriftformerfordernis (häufig übersehener Unwirksamkeitsgrund)
- § 14 Abs. 2 Satz 2 TzBfG — Vorbeschäftigungsverbot
- § 16 TzBfG — Rechtsfolge: Vertrag gilt als unbefristet
- § 4 KSchG — Klagefrist Kündigungsschutz (zur Abgrenzung)
- § 623 BGB — Schriftformerfordernis Kündigung (zur Abgrenzung)

## Aktuelle Rechtsprechung (Kurzüberblick für Triage)

- Rechtsprechung: keine Entscheidung aus Modellwissen zitieren; vor Ausgabe über offizielle oder frei zugängliche Quelle mit Gericht, Entscheidungsform, Datum, Aktenzeichen und tragender Aussage verifizieren.

## Zweck

Dieser Skill ist der Einstieg in den Entfristungs-Workflow. Er klärt, ob das Ziel des Nutzers ist, festzustellen, dass ein angeblich befristeter Vertrag in Wirklichkeit **unbefristet** ist (Befristungskontrollklage / Entfristungsklage).

## Abgrenzung: Entfristungsklage vs. Kündigungsschutzklage

| | Entfristungsklage | Kündigungsschutzklage |
|---|---|---|
| Ausgangssituation | Befristeter Vertrag läuft aus | Kündigung durch Arbeitgeber |
| Ziel | Feststellung: Vertrag ist unbefristet | Feststellung: Kündigung ist unwirksam |
| Rechtsgrundlage | §§ 17, 16 TzBfG | § 4 KSchG |
| Frist | 3 Wochen ab vereinbartem Ende | 3 Wochen ab Zugang der Kündigung |
| Norm Schriftform | § 14 Abs. 4 TzBfG | § 623 BGB |

## Typische Einstiegssituation

Der Nutzer sagt zum Beispiel:
- "Mein befristeter Vertrag läuft am [DATUM] aus, ich glaube er war gar nicht wirksam befristet"
- "Mein Arbeitsvertrag wurde per E-Mail unterschrieben, gilt die Befristung überhaupt?"
- "Ich arbeite schon seit drei Jahren auf Basis aufeinanderfolgender befristeter Verträge"
- "Mein Arbeitgeber hat mir einen neuen Vertrag gegeben ohne dass ich unterschrieben habe"

## Erkennungsmerkmale Entfristungsklage

Das System erkennt den Entfristungs-Bedarf wenn:
- Ein schriftlicher (oder angeblich elektronischer) Vertrag mit Endtermin vorliegt
- Der Arbeitnehmer behauptet, die Befristung sei unwirksam
- Das Ende des Vertrags noch nicht eingetreten ist oder erst kürzlich eingetreten ist

## Kritische Sofortfrage: Dreiwochenfrist § 17 TzBfG

**Sofort prüfen:**

> § 17 TzBfG: Will der Arbeitnehmer geltend machen, dass die Befristung eines Arbeitsvertrags rechtsunwirksam ist, so muss er innerhalb von **drei Wochen nach dem vereinbarten Ende des befristeten Arbeitsvertrags** Klage beim Arbeitsgericht auf Feststellung erheben, dass das Arbeitsverhältnis auf Grund der Befristung nicht beendet ist.

**Wann läuft die Frist?** Ab dem **vereinbarten** (nicht tatsächlichen) Vertragsende. Sie läuft auch wenn der Arbeitnehmer tatsächlich weiterbeschäftigt wird.

## Folge-Skills

| Schritt | Skill |
|---|---|
| Laie oder Anwalt? | `entfristung-laie-oder-anwalt-frage` |
| Dreiwochenfrist § 17 TzBfG | `entfristung-grundwarnung-drei-wochen-frist` |
| Sachgrund prüfen | `entfristung-sachgrund-pruefen-14-abs-1` |
| Schriftform prüfen | `entfristung-schriftform-14-abs-4-erkennen` |
| Elektronische Signatur | `entfristung-elektronische-signatur-vorsicht` |
| Rechtsfolge | `entfristung-rechtsfolge-16-tzbfg-unbefristet` |

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Falsche Sachverhaltsangabe oder falsche Anspruchsgrundlage entwertet das Ergebnis. Dringende Empfehlung anwaltlicher Beratung, insbesondere wegen der Drei-Wochen-Fristen.

Du könntest auf der falschen Wiese unterwegs sein. Dieses System kann das nicht prüfen.
