---
name: einspruch-finanzamt
description: Entwirft einen begruendeten Einspruch gegen einen Steuerbescheid nach §§ 347 ff. AO. Frist ein Monat nach Bekanntgabe (§ 355 Abs. 1 AO; ein Jahr bei fehlender Rechtsbehelfsbelehrung § 356 AO). Einspruchsbefugnis (§ 350 AO) Adressat (Finanzamt das den Bescheid erlassen hat § 357 AO) Form (schriftlich elektronisch oder zur Niederschrift). Inkludiert hilfsweisen Antrag auf Aussetzung der Vollziehung (§ 361 Abs. 2 AO) und Antrag auf Akteneinsicht.
---

# Einspruch beim Finanzamt

## Eingaben

- Analyseprotokoll aus `steuerbescheid-analyse`.
- Steuererklaerung des Veranlagungsjahres und Belege.
- Bescheid im Original.

## Struktur

### 1. Rubrum

- Einspruchsfuehrer (Steuerpflichtiger) mit Anschrift und Steuernummer.
- Vertreter (RA mit beA-Adresse).
- Empfangsfinanzamt mit Aktenzeichen / Steuernummer.
- Bezug: Bescheid vom (Datum) ueber (Steuerart) (Veranlagungsjahr).

### 2. Antrag

"Hiermit lege ich Einspruch gegen den Bescheid vom (Datum) ueber (Steuerart) (Jahr) ein und beantrage:

1. den angefochtenen Bescheid aufzuheben;
2. die Steuer wie folgt festzusetzen: ... EUR;
3. hilfsweise Aussetzung der Vollziehung gemaess § 361 Abs. 2 AO;
4. Akteneinsicht in die Steuerakten gemaess § 364 AO im Einspruchsverfahren."

### 3. Begruendung

- Formale Mangel zuerst (Bekanntgabe Begruendung Adressat).
- Materielle Mangel:
  - Sachverhaltsfehler (Einkuenftezuordnung Werbungskosten Sonderausgaben Aussergewoehnliche Belastungen).
  - Rechtsanwendungsfehler.
  - Schaetzung unrealistisch (§ 162 AO).
- BFH-Rechtsprechung mit Pinpoint.
- Verweis auf BMF-Schreiben falls einschlaegig.
- Bei Schaetzungsbescheid: bestreitete Schaetzungsgrundlagen plus eigene plausible Berechnung.

### 4. Belege

- Anlagen mit Sigel E1 E2 E3.
- Vollstaendige Belegliste (Belegart Datum Inhalt).

### 5. Form und Frist

- **Frist** ein Monat nach Bekanntgabe (§ 355 Abs. 1 AO).
- **Drei-Tages-Fiktion** § 122 Abs. 2 Nr. 1 AO bei Postbescheiden.
- **Form** schriftlich elektronisch (beA / De-Mail / qualifizierte elektronische Signatur) oder zur Niederschrift.
- **Bei fehlender Rechtsbehelfsbelehrung** ein Jahr (§ 356 AO).

### 6. Aussetzung der Vollziehung

Hilfsantrag im Einspruchsschreiben:

"Hilfsweise wird die Aussetzung der Vollziehung gemaess § 361 Abs. 2 AO beantragt. Es bestehen ernstliche Zweifel an der Rechtmaessigkeit des angefochtenen Bescheids; die Vollziehung wuerde fuer den Steuerpflichtigen eine unbillige nicht durch ueberwiegende oeffentliche Interessen gebotene Haerte zur Folge haben."

Bei Ablehnung Antrag durch FA: Antrag an Finanzgericht § 69 Abs. 3 FGO (siehe Skill `aussetzung-vollziehung`).

### 7. Akteneinsicht

Im Einspruchsverfahren Anspruch nach § 364 AO Steuerakten und Akten der Aussenpruefung.

## Verfahrensgang

1. **Einspruch eingelegt** → Finanzamt prueft.
2. **Hinweis nach § 367 Abs. 2 AO** wenn das FA die Steuer verboesern (Verschlechtern) will → der Einspruch kann zurueckgenommen werden um Verboeserung zu vermeiden.
3. **Einspruchsentscheidung** mit Rechtsbehelfsbelehrung → bei Ablehnung Klage zum FG (Skill `klage-finanzgericht`).
4. **Untaetigkeit** des FA: nach sechs Monaten kann Klage erhoben werden (§ 46 FGO).

## Ausgabe

- `einspruch-<az>-<datum>.docx` und Markdown-Spiegel.
- Eintrag im Fristenbuch.
- Eintrag im Postausgang.

## Versand

Ueber beA (RA-Pflicht). Vor Versand `versand-vor-check` aus `kanzlei-cowork`.
