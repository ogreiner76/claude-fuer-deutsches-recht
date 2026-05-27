---
name: inkasso-zahlungsklage-ersteller
description: "Freistehender Inkasso-Zahlungsklage-Ersteller: Mahnvorlauf, Anspruchs-Gatekeeper, Teilzahlung/Erfuellung, Verzug, Inkassokosten, Gerichtsortfindung. Klage nur fuer klare, faellige und belegte Ansprueche."
---

# Inkasso-Zahlungsklage-Ersteller

## Triage — kläre vor dem Einsatz

1. Liegt ein vollständiger Mahnvorlauf vor (Rechnung mit Fälligkeit, mindestens eine Mahnung mit Fristsetzung)?
2. Ist die Hauptforderung noch nicht vor Klageeinreichung vollständig bezahlt (Erfüllungskontrolle)?
3. Sind Schuldner-Anschrift und Verbraucher-/Unternehmereigenschaft geklärt (Gerichtsstand § 29c ZPO bei Verbrauchern)?
4. Welche Nebenforderungen (Mahnkosten, Verzugszinsen, Inkassokosten) sollen eingeklagt werden — sind sie belegt und verhältnismäßig?
5. Liegt eine Abtretungskette vor — ist die Aktivlegitimation des Gläubigers/Zessionars lückenlos dokumentiert?

## Zentrale Normen

§ 286 BGB (Verzugseintritt) — § 288 BGB (Verzugszinsen: +5 Pp. B2C, +9 Pp. B2B) — § 280 Abs. 2 BGB (Verzugsschaden) — § 249 BGB (Schadensersatz) — § 253 ZPO (Klageschrift) — §§ 12, 13, 29, 29c ZPO (örtliche Zuständigkeit) — §§ 23, 71 GVG (sachliche Zuständigkeit: AG bis 10.000 EUR, LG darüber) — § 93 ZPO (sofortiges Anerkenntnis, Kostenfolge) — § 812 BGB (Bereicherungsrecht als Auffanganspruch)

## Rechtsprechung

BGH, Urt. v. 12.07.2006 – X ZR 157/05, NJW 2006, 3271 — Verzug nach § 286 BGB setzt eine wirksame Mahnung oder eine kalendermäßige Bestimmtheit der Fälligkeit voraus; eine bloße Rechnung ohne Fälligkeitsdatum genügt nicht für den Verzugseintritt ohne weitere Mahnung.

BGH, Urt. v. 23.01.2008 – VIII ZR 246/06, NJW 2008, 1084 — Inkassokosten sind als Verzugsschaden nach § 280 Abs. 2 i.V.m. § 286 BGB erstattungsfähig, wenn ein Rechtsanwalt oder Inkassodienstleister eingeschaltet und die Einschaltung erforderlich war; die Kosten müssen der Höhe nach verhältnismäßig sein.

BGH, Urt. v. 10.01.2018 – VIII ZR 278/16, NJW 2018, 1391 — Hat der Schuldner die Hauptforderung vor Einreichung der Klage vollständig bezahlt und weiß der Gläubiger davon, ist eine Klage auf die Hauptforderung unzulässig (§ 91a ZPO) oder führt zur sofortigen Kostenpflicht nach § 93 ZPO bei sofortigem Anerkenntnis.

BGH, Urt. v. 25.10.2006 – VIII ZR 23/06, NJW 2007, 428 — Bei Abtretung der Forderung muss der Zessionar die lückenlose Abtretungskette darlegen und beweisen; fehlende Belege für die Abtretung führen zur Abweisung wegen fehlender Aktivlegitimation.

## Kommentarliteratur

Zöller, ZPO, 35. Aufl. 2024, § 253 Rn. 1–40 (Klageantrag, Anlagen, Zuständigkeit).
Palandt/Grüneberg, BGB, 83. Aufl. 2024, § 286 Rn. 1–30, § 288 Rn. 1–15 (Verzug, Zinsen, Inkassokosten).
Musielak/Voit, ZPO, 20. Aufl. 2023, §§ 12–29c Rn. 1–50 (örtliche Zuständigkeit, Verbraucherschutz).

## Zweck

Dieser Skill baut aus einer Forderungsakte einen sauberen Mahn- und Klageworkflow. **Eingeklagt werden nur Ansprüche, die klar, fällig, durchsetzbar und belegt sind.** Unsichere Positionen werden nicht eingeklagt, sondern als Rückfrage oder Nichtklage-Empfehlung ausgegeben.

## Sofortregeln

1. Nicht alles einklagen, was im Forderungskonto steht — jede Position braucht Anspruchsgrundlage, Betrag, Fälligkeit, Verzug, Beleg und Einwendungskontrolle.
2. Erfüllung blockt: vor Klageeinreichung bezahlte Hauptforderung darf nicht mehr eingeklagt werden.
3. Nebenforderungen sind kein Autopilot: Mahnkosten, Verzugszinsen, Inkassokosten werden einzeln geprüft.
4. Gerichtsort vor Klage: sachliche und örtliche Zuständigkeit sind zu prüfen und zu dokumentieren.
5. Mahnung vor Eskalation: wenn kein ausreichender Mahnvorlauf vorliegt, zuerst Mahnschreiben.

## Pflichtablauf

### Schritt 1: Akte aufnehmen

Felder: Gläubiger, Schuldner (Verbraucher/Unternehmer), Forderungsgrund, Hauptforderung, Mahnvorlauf, Verzug, Nebenforderungen, Prozessgeschichte, Gerichtsort.

### Schritt 2: Mahnvorlauf prüfen

Mahnchronologie: Rechnung → Zahlungserinnerung → Mahnung(en) → letzte Mahnung mit Klagehinweis → Inkassoschreiben → Zahlungseingänge.

Ampelbeurteilung: grün (klar), gelb (unklar, nacharbeitbar), rot (rechtlich ungeeignet oder bereits erledigt).

### Schritt 3: Anspruchs-Gatekeeper

Prüfe je Position: Anspruchsgrundlage, Betrag, Fälligkeit, Durchsetzbarkeit, Verzug, Verschulden, Prozessrisiko, Gerichtsort.

- GRÜN → in den Klageantrag.
- GELB → Rückfrage oder Belegbedarf.
- ROT → nicht einklagen, Begründung angeben.

### Schritt 4: Gerichtsort finden

Sachlich: AG bis 10.000 EUR (§ 23 GVG), LG darüber (§ 71 GVG). Örtlich: §§ 12, 13, 29, 29c ZPO. Online-Abgleich über justiz.de oder justizadressen.nrw.de; Quelle und Abrufdatum dokumentieren.

### Schritt 5: Output bauen

1. Mahnchronologie als Tabelle.
2. Anspruchsmatrix mit Ampel.
3. Klagefreigabe (was wird eingeklagt, was nicht, warum).
4. Gerichtsortprüfung mit Quellenplatzhalter.
5. Klageentwurf nur für grüne Positionen.
6. Beleg- und Anlagenliste mit K-Sigeln.
7. Kosten-/Risiko-Hinweis zu § 93 ZPO.

## Output-Template

**Inkasso-Zahlungsklage — Anspruchsmatrix**

Schuldner: [...] | Forderungsstand: [...] EUR | Stand: [Datum]

| Position | Betrag EUR | Ampel | Begründung |
|---|---|---|---|
| Hauptforderung | [...] | GRÜN/ROT | [...] |
| Verzugszinsen | [...] | GRÜN/GELB | ab [...] |
| Mahnkosten | [...] | GRÜN/GELB | Beleg: [...] |
| Inkassokosten | [...] | GRÜN/GELB | Verhältnismäßigkeit: [...] |

**Gerichtsort:** AG/LG [...] — Online-Quelle: [...] — Abrufdatum: [...]

**Klageantrag (nur grüne Positionen):**
Der Beklagte wird verurteilt, an den Kläger [...] EUR nebst Zinsen in Höhe von [...] Prozentpunkten über dem Basiszinssatz seit [...] zu zahlen.

**Empfehlung:** [Klage einreichen / zuerst Mahnung / Positionen [...] nicht einklagen]

---

Hinweis: Keine Rechtsberatung. Mechanische Prüfung anhand vom Nutzer behaupteter Tatsachen. Falsche Normwahl oder unvollständiger Sachverhalt kann das Ergebnis vollständig entwerten.
