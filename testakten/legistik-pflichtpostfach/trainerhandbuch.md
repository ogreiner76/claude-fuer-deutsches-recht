# Trainerhandbuch - Schulung "Elektronisches Pflichtpostfach"

Zielgruppe: Legistinnen und Legisten in Bundesministerien und Landesministerien, Referatsleitungen Rechtsetzung, Verbaendevertreter, Studierende der Hochschule des Bundes Standort Rechtswissenschaft.

## Lernziele

Die Teilnehmenden koennen am Ende der Schulung

1. eine politische Vorgabe in einen vollstaendigen Regelungsauftrag uebersetzen,
2. die Normhierarchie richtig waehlen,
3. die Gesetzgebungs- und Satzungskompetenz beurteilen,
4. ein Artikelgesetz im HdR-Layout aufsetzen,
5. eine zweigeteilte Begruendung schreiben,
6. eine Synopse erstellen,
7. eine XML-Paralleldarstellung im LegalDocML.de-Standard ausgeben,
8. den Erfuellungsaufwand korrekt darstellen,
9. die EU-Notifizierung 2015 1535 einleiten,
10. die Mappe fuer das Kabinett vorbereiten und
11. ein lieferfertiges DOCX im offiziellen Layout der Bundesregierung bzw. des Bundestages erzeugen.

## Zwei Schulungsformate

### A. Tagesschulung (8 Stunden)

| Block | Dauer | Skills |
| --- | --- | --- |
| 09:00 - 09:45 | Eroeffnung, Aufgabe | `legistik-auftragsaufnahme` |
| 09:45 - 10:30 | Normhierarchie + Kompetenz | `normhierarchie-routing`, `gesetzgebungskompetenz-pruefen`, `satzungskompetenz-pruefen` |
| 10:30 - 10:45 | Pause | |
| 10:45 - 12:00 | Verfassung + Europa | `verfassungsmaessigkeit-quercheck`, `europarechtskonformitaet`, `goldplating-vermeiden` |
| 12:00 - 13:00 | Mittag | |
| 13:00 - 14:30 | Normentext bauen | `referentenentwurf-bauen`, `inkrafttreten-uebergangsrecht`, `terminologie-konsistenz`, `zirkelschluss-pruefen` |
| 14:30 - 15:00 | Begruendung | `begruendung-allgemein-und-besonders` |
| 15:00 - 15:30 | Synopse, XML | `synopse-erstellen`, `xml-paralleldarstellung` |
| 15:30 - 16:00 | Pause | |
| 16:00 - 16:45 | Folgenabschaetzung + NKR | `folgenabschaetzung-erfuellungsaufwand`, `folgenabschaetzung-nachhaltigkeit`, `normenkontrollrat-kmu-check` |
| 16:45 - 17:00 | Kabinettsmappe + Render | `gesetzesentwurf-kabinett`, `dokumente-rendern-docx-pdf` |

### B. Zwei-Tages-Schulung

Tag 1 wie oben. Tag 2 vertieft anhand der vorliegenden Schulungsakte:

- 09:00 - 10:30: Verbaendeanhoerung und Ressortabstimmung (`verbaendeanhoerung-ressortabstimmung`) - Rollenspiel
- 10:45 - 12:00: Wahl zwischen Stammgesetz und Aenderungsgesetz, Goldplating-Diskussion am DSA-Fall
- 13:00 - 14:30: XML-Paralleldarstellung praktisch
- 14:45 - 16:00: Render-Skill praktisch (DOCX und PDF erzeugen), Vergleich Referentenentwurf vs. BT-Drucksache
- 16:00 - 17:00: Reflexion, Fragen, Best Practices

## Bewusste Lernfallen in dieser Schulungsakte

1. **DSA-Schwelle**: Der Erstentwurf des Referats schreibt "vergleichbar grosse" Plattformen. Skill `goldplating-vermeiden` und `verfassungsmaessigkeit-quercheck` muessen das anpassen und auf den Wortlaut der DSA-Schwelle zurueckfuehren.
2. **Verordnungsermaechtigung**: § 5 PflPostG muss Inhalt, Zweck und Ausmass nach Artikel 80 GG bestimmen. Skill `verordnungsermaechtigung-art80` erzwingt eine textliche Verankerung.
3. **Kompetenztitel**: Mischzustaendigkeit aus Artikel 74 Absatz 1 Nummer 1 GG und der Durchfuehrungskompetenz fuer EU-Verordnungen. Skill `gesetzgebungskompetenz-pruefen` legt die korrekte Begruendung an.
4. **Notifizierung**: Die Stillhaltefrist muss in den Zeitplan einkalkuliert werden. Skill `europarechtskonformitaet` erinnert daran.
5. **Bestimmtheit**: Begriffsbruch "vergleichbar groessenmaessig" vs. "VLOP im Sinne des Artikels 33 DSA". Skill `terminologie-konsistenz` muss greifen.
6. **Inkrafttreten**: Uebergangsfrist von vierundzwanzig Monaten ist erforderlich, sonst Verstoss gegen Verhaeltnismaessigkeit (verfassungsrechtliche Pruefung).

## Lieferergebnisse am Ende der Schulung

- Auftragsblatt
- Referentenentwurf-Markdown (`vorblatt.md`, `gesetzestext.md`, `begruendung-a.md`, `begruendung-b.md`)
- Synopse als CSV und XLSX
- XML-Paralleldarstellung
- NKR-Stellungnahme (Vorlage)
- Bewertete Trainings-DOCX-Dateien im offiziellen Layout (Referentenentwurf, BT-Drucksache, Formulierungshilfe, Synopse, Lesefassung, Kabinettsmappe)

## Hinweise fuer die Trainerin / den Trainer

- Die Schulungsakte ist bewusst so gestaltet, dass an mehreren Stellen Korrekturbedarf entsteht. Die Teilnehmenden sollen die Korrekturen selbst entdecken.
- Das Render-Skript ist in Python 3 implementiert und benoetigt `python-docx` (`pip install python-docx pyyaml`).
- Fuer PDF zusaetzlich LibreOffice (`soffice`).
