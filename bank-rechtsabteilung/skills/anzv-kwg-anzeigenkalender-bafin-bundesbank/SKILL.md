---
name: anzv-kwg-anzeigenkalender-bafin-bundesbank
description: "AnzV-Anzeigenkalender für KWG-Institute: Organpersonen, LEI, Beteiligungen, enge Verbindungen, Auslandsbeziehungen, Auslagerungen, Vergütung, Einreichweg und BaFin-/Bundesbank-Nachweise in einen fristfesten Legal-Workflow bringen."
---

# AnzV-Anzeigenkalender KWG

## Zweck

Dieser Skill baut aus KWG und AnzV einen operativen Anzeigenkalender. Er ist für Bank-Legal, Vorstandsbüro, Compliance, HR, Beteiligungsmanagement, IT-Auslagerung, Risk und Finance gedacht. Ziel: keine Anzeige vergessen, keine falsche Bundesbank-Stelle wählen, keine Unterlagen in der falschen Form einreichen.

## Intake

Frage sofort:

- Welcher Anlass liegt vor: Organperson, Beteiligung, enge Verbindung, Auslagerung, Auslandsbezug, Vergütung, LEI, Registerdaten?
- Ist das Institut CRR-Kreditinstitut, Finanzdienstleistungsinstitut, Finanzholding, gemischte Finanzholding oder Teil einer Gruppe?
- Ist BaFin, Bundesbank, EZB/SSM oder ein elektronischer Einreichweg betroffen?
- Gibt es Closing, Organbestellung, Vertragsbeginn oder sonstigen Vollzugstermin?
- Welche Unterlagen liegen vor und wer ist Owner?

## Anzeigenmatrix

| Anlass | Typische Unterlagen | Legal-Prüfung |
| --- | --- | --- |
| Geschäftsleiter/Aufsichtsorgan | Lebenslauf, Führungszeugnis, Registerauszüge, Eignung, Zeitbudget | Vollständigkeit, Widersprüche, Interessenkonflikte |
| LEI/Rechtsträgerkennung | LEI-Nachweis, Stammdaten | Aktualität und Zuordnung zur richtigen Einheit |
| Aktivische Beteiligung | Quoten, Stimmrechte, Unternehmensdaten, Ausland | Schwellen 20/30/50 %, enge Verbindung, Risikofolge |
| Passive Beteiligung | Aktionärs-/Gesellschafterstruktur, Stimmrechtsabreden | Inhaberkontrolle und KWG-Meldepflicht trennen |
| Auslagerung | Vertrag, Risikoanalyse, Registereintrag, Beginn/Änderung/Ende | DORA/MaRisk/KWG-Melde- und Registerlogik |
| Auslandsbezug | Sitz, Tochter/Zweigstelle, Aufsicht, Bilanzsumme | Zuständigkeit und Gruppenfolgen |
| Vergütung/Risikoträger | Vergütungsdaten, Rollen, Kontrollfunktionen | Frist, Format, Datenschutz, Board-Review |

## Verfahrenslogik

1. Anlasstag bestimmen: Beschluss, Absicht, Vertragsschluss, Vollzug, Änderung, Beendigung.
2. Anzeigepflicht aus KWG und AnzV herleiten.
3. Einreichadressat bestimmen: BaFin, zuständige Bundesbank-Hauptverwaltung, EZB/SSM-Schnittstelle oder elektronischer Kanal.
4. Unterlagenstand prüfen: vollständig, unterschrieben, aktuell, übersetzt, plausibel.
5. Interne Freigabe: Vorstand, Aufsichtsrat, Compliance, Risk, HR, Datenschutz.
6. Versand- und Nachweislog: Datum, Kanal, Aktenzeichen, Empfang, Nachforderung.

## Output

Erzeuge einen Anzeigenkalender mit:

- Anzeigeanlass und Normanker.
- Einreichadressat und Kanal.
- Frist/Trigger.
- Unterlagenliste.
- Owner.
- Status: Entwurf, Freigabe, eingereicht, Nachforderung, erledigt.
- Red Flag: Vollzug vor Anzeige, unvollständige Fit-and-Proper-Unterlagen, falsche Einheit, fehlende LEI, nicht gepflegtes Auslagerungsregister.

## Qualität

Nicht behaupten, ein PDF-Formular oder Portalweg sei aktuell, ohne Live-Check auf BaFin/Bundesbank. Bei SSM-Instituten immer prüfen, ob nationale AnzV-Route, IMAS/MVP oder EZB-Prozess den praktischen Einreichweg bestimmt.
