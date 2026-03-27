---
layout: default
title: "Kommunikationslog"
parent: "Kommunikation"
---

# Forklaring
I kommunikationsloggen kan du se alle beskeder, der er sendt fra OS2valghalla. Det inkluderer både
automatisk og manuelt udsendte beskeder.

Du har også mulighed for at se status på afsendelsen: Det vil sige, om de står i kø til afsendelse, om de er
afsendt succesfuldt eller om der er fejl. Ved at klikke på beskeden kan du se detaljer om den.

### Trin for trin

<br>
<details>
  <summary><strong>Trin 1: Tilgå kommunikationslog</strong></summary>
  
  <p>Fra forsiden skal du:</p>
  <ol>
    <li>Vælge Kommunikation i topmenuen</li>
    <li>Klikke på kommunikationslog</li>
  </ol>

  <img src="../../images/img_kommunikation/kommunikation-komm-log.PNG" alt="Kommunikation - Kommunikationslog">

</details>

<details>
  <summary><strong>Trin 2: Brug kommunikationsloggen</strong></summary>
  
  <p>Kommunikationsloggen er delt op i:</p>
  <ol>
    <li>Overbliksbillede</li>
    <li>Søgefunktion</li>
    <li>Filter</li>
  </ol>

  <p>Overbliksbilledet indeholder oplysninger om alle forsendelser Valghalla har foretaget. Hver række svarer til en forsendelse – både dem der er lykkes, fejlet og dem som er i kø.</p>

  <p><strong>Søgefunktion</strong></p>

  <img src="../../images/img_kommunikation/kommunikation-brug-log.PNG" alt="Kommunikation - Kommunikationslog - Overbliksbillede">

  <details>
    <summary><strong>Trin 2.1: Overbliksbillede</strong></summary>

    <p>Overbliksbilledet er opdelt i seks kolonner med informationer:</p>

    <p><strong>Beskedtype:</strong> Beskriver hvilken kanal der er brugt til den pågældende forsendelse.</p>
    <p><strong>Udsendelse:</strong> Beskriver hvorvidt forsendelsen er sket automatisk eller manuelt.</p>
    <p><strong>Modtager:</strong> Viser hvem der er modtager af henvendelsen. Ved klik tilgår du deltagerens profil.</p>
    <p><strong>Besked:</strong> Viser titlen på forsendelsen.</p>
    <p><strong>Oprettet den:</strong> Dato og klokkeslet for oprettelsen.</p>
    <p><strong>Status:</strong> Viser om forsendelsen er lykkes, fejlet eller sat i kø. Fejlede vises med rød markering.</p>

  </details>

  <details>
    <summary><strong>Trin 2.2: Søgefunktion og filter</strong></summary>

    <p>Både søgefunktion og filter kan hjælpe til at navigere i overbliksbilledet.</p>

    <p><strong>Søgefunktionen:</strong> Søger i både modtager- og beskedkolonnen. Du kan finde forsendelser til en specifik modtager eller med samme titel.</p>

    <p><strong>Filter:</strong> Kan sortere mellem forsendelser der er lykkes og dem der er fejlet.</p>

  </details>

</details>

<details>
  <summary><strong>Trin 3: Se detaljer om en besked</strong></summary>

  <p>Du kan se alle detaljer om en besked:</p>

  <ol>
    <li>Klik på det ord, der står ud for en besked i kolonnen "Status"
      <ol>
        <li>Ord kan være Succes, Afventer og Fejl</li>
      </ol>
    </li>
  </ol>

  <p><strong>Eksempler på fejlbeskeder:</strong></p>
  <ul>
    <li>Deltager kan ikke modtage Digital Post: <code>"Message":"Participant does not have Digital Post"</code></li>
    <li>Der er ikke oprettet en mailadresse på deltageren: <code>"Message":"Participant does not have email yet"</code></li>
  </ul>

  <img src="../../images/img_kommunikation/kommunikation-detaljer2.png" alt="Eksempler på fejlbeskeder">

</details>