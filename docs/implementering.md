---
layout: default
title: Implementering
nav_order: 4
has_children: false
---

# Implementering af OS2valghalla
```
På denne side kan du finde brugbare implementeringsoplysninger og vejledninger til opsætning af OS2valghalla i jeres kommune.
```


# Tilkoblingsoplysninger
Når kommunen har indgået en [tilslutningsaftale](https://boks.os2.eu/s/JA26fX6BfLaXcwf) ved OS2, sker den tekniske tilkobling direkte ved driftsleverandøren Precio Fishbone. Denne tilkobling koster kr. 15.000, hvilket er en engangsbetaling, som faktureres af Precio Fishbone.

Tilkobling starter ved, at kommunen udfylder [denne formular](https://forms.office.com/pages/responsepage.aspx?id=CLw0f4V1EUi14xJDBjJcVUSJQzeahFJLg18VVsOuqc5UQkFPRThQV1FaRFlUOFc1QkpCVDNIUlJKQyQlQCN0PWcu&route=shorturl). OBS: Man kan ikke tilkoble sig, hvis man ikke har indgået en tilslutningsaftale!

Der skal benyttes disse oplysninger til processen:

| Oplysning | Note |
|---|-----|
| Kontaktperson | Den person, som Precio Fishbone kan kontakte om kommunens implementeringsproces. |
| Faktureringsoplysninger | EAN- og CVR-nummer mv. som Precio Fishbone kan benytte til fakturering |
| E-mail afsenderadresse | OS2valghalla udsender mails fra mailadressen [xxxxx]@os2valghalla.dk <br>Hvad vil kommunen gerne have til at stå før @os2valghalla.dk? Det kan fx være “korsbaek@os2valghalla.dk” <br>Navnet skal også angives, selvom kommunen ikke planlægger at benytte OS2valghallas mailfunktion |
| E-mail afsendernavn | Hvilket navn skal mails fra OS2valghalla have som afsender? Det kan fx være “Valgsekretariatet - Korsbæk Kommune”

Navnet skal også angives, selvom kommunen ikke planlægger at benytte OS2valghallas mailfunktion |
| Digital Post afsendernavn | Det navn, der kan ses i slutbrugerens digitale postkasse |
| Digital Post CVR-nummer | Det CVR-nummer der bruges til at sende Digital post “på vegne af" |
| Ønskes adgang til logfiler? | Se mere i afsnittet IT- og administrationsopgaver herunder |


# IT- og administrationsopgaver
OS2valghalla er en online SaaS-løsning, så der er ikke driftsmæssige opgaver for IT-afdelingen.

Dog kræves der opsætning og konfiguration i kommunen for give OS2valghalla adgang til at benytte integrationer til den fællesoffentlige infrastruktur på kommunens vegne.

Dette inkluderer disse opgaver, som forventes af tage 1-2 timer for de relevante medarbejdere (som oftest sidder i en IT- eller Digitaliseringsafdeling):

- Godkendelse af OS2valghalla-serviceaftale om Digital Post og indhentning af CPR-data i [Fælleskommunalt Administrationsmodul](https://digitaliseringskataloget.dk/)
- Lokal opsætning af jobfunktionsrolle til OS2valghalla, som giver administrative medarbejdere adgang
  - Disse medarbejdere skal være tilkoblet en IdP, der understøtter Context Handler 2 og kan levere NSIS assurance level
- Registrering af OS2valghalla som NemLog-in system i portalen [NemLog-In Administration](https://administration.nemlog-in.dk/)
- Afgøre om kommunen har brug for adgang til audit log-filer fra OS2valghalla
  - Disse kan hentes via SFTP, og der skal i så fald opsættes lokal procedure for indhentning af filerne


# Databehandleraftale
Der skal indgås en databehandleraftale direkte mellem kommunen og driftsleverandøren. [Det fælleskommunale Databehandlersekretariat](https://kommunedbs.dk/) har udarbejdet en [databehandleraftale](https://viden.os2valghalla.dk/sites/default/files/2024-01/Databehandleraftale%20-%20Precio%20Fishbone%20-%20OS2valghalla.docx), som tilbydes af driftsleverandøren. Dette gælder uanset om kommunen er medlem af Det fælleskommunale Databehandlersekretariat eller ej. Hvis kommunen ikke kan acceptere denne aftale, kontaktes driftsleverandøren direkte om ønskede ændringer.


# Krav til nyt IT-system
Mange kommuner har en fast procedure for godkendelse af nye IT-systemer. Vi har derfor samlet [relevante oplysninger om OS2valghalla](https://os2web.atlassian.net/wiki/spaces/OS2valghalla/pages/2315452417/Implementeringsoplysninger), som vi beder jer om at orientere jer i først.

Hvis I herefter har flere spørgsmål, så skriv til <os2valghalla@os2.eu>.

Hvis I benytter [OS2kravmotor](https://www.os2kravmotor.dk/) til at få svar på tekniske minimumskrav, har OS2 mulighed for at levere svar den vej.


# Vejledninger til opsætning

**Link kommer, når vejledninger er lagt ind**
- Registrering af NemLog-in system
- Godkendelse af serviceaftale i Fælleskommunalt Administrationsmodul
- Opsætning af jobfunktionsrolle og IdP