---
layout: default
title: "Eksporter deltagere fra Valghalla til Valg Central"
parent: "Deltagere"
has_children: false
---

# Export af deltagere fra Valghalla

<details>
  <summary><strong>Trin 1: Husk at dine arbejdssteder skal have et afstemningsområde</strong></summary>
  <p>I Valg Central har alle afstemningsområder et fortløbende nummer. Dette nummer skal fremgå af arbejdsstedet i Valghalla, så Valg Central ved hvilke afstemningsområde deltagerne skal oprettes på.</p>
  <p>Se eventuelt her hvordan du opretter og redigerer dine arbejdssteder i Valghalla: <a href="../administration/arbejdssteder">Klik her</a></p>
  <img src="../../images/img_deltagere/deltagere-eksp-valgcentral-omr.png" alt="Husk at angive afstemningsområde">
</details><br>

<details>
  <summary><strong>Trin 2: Vælg Lister i Topmenu</strong></summary>
  <p>Klik på Lister i menuen i toppen af Valghalla</p>
  <img src="../../images/img_deltagere/deltagere-eksp-valgcentral-klister.png" alt="Vælg lister i topmenu">
</details><br>

<details>
  <summary><strong>Trin 3: Vælg Eksport til valgsystemet</strong></summary>
  <p>Klik på Eksport til valgsystemet</p>
  <img src="../../images/img_deltagere/deltagere-eksp-valgcentral-3.png" alt="Eksport til valgsystemet">
</details><br>

<details>
  <summary><strong>Trin 4: Vælg hvilke deltagere der skal eksporteres</strong></summary>
  <p>Vælg ved hjælp af valglisterne Opgavetype, Opgavedag og Arbejdssted hvilke deltagere i Valghalla der skal eksporteres til Valg Central.</p>
  <p>Brug Vis preview til at se resultatet.</p>
  <p>Vælg Eksporter som CSV-fil når du er tilfreds med dit udtræk.</p>
  <p>Filen gemmes automatisk på din PC i overførselsmappen.</p>
  <p>Husk at Valgsekretærer skal indgå i listen, da de ellers ikke kan tilgå Valg-Lokal på valgdagen.</p>
  <img src="../../images/img_deltagere/deltagere-eksp-valgcentral-deltagere.png" alt="Vælg deltagere til eksport">
</details><br>

<details>
  <summary><strong>Trin 5: Klargør filen til import i Valg Central</strong></summary>

  <!-- #ecfa9d -->
  <!-- #ffb0e5 -->
  <!-- <mark>OBS, gul highlight</mark> -->

  <p><span style="background-color: #ecfa9d;">OBS vær opmærksom på at opgaverne fra Valghalla skal ændres så de passer til Valg Central</span></p>
  <p><span style="background-color: #ecfa9d;">Valg Central overskriver data når du importere dem, så listen skal indeholde alle de deltagere der skal anvende Valg Lokal når du importerer dem.</span></p>

  <details>
    <summary><strong>Trin 5.1: Klargør ny fil til import i Valg Central trin 1</strong></summary>
    <ol>
      <li>Åben et nyt tomt regneark</li>
      <li>Klik på <strong>Data</strong> i topmenuen</li>
      <li>Vælg <strong>Hent data</strong></li>
      <li>Vælg <strong>Fra fil</strong> og herefter <strong>Fra tekst/csv</strong></li>
      <li>Vælg filen som Valghalla har gemt i din mappe Overførsler på din PC</li>
    </ol>
    <img src="../../images/img_deltagere/deltagere-eksp-valgcentral-hent-fil1.png" alt="Hent data"><br>
    <img src="../../images//img_deltagere/deltagere-eksp-valgcentral-hent-fil2.png" alt="Hent data fra fil">
  </details><br>

  <details>
    <summary><strong>Trin 5.2: Klargør ny fil til import i Valg Central trin 2</strong></summary>
    <ol>
      <li>I det vindue der kommer frem vælger du <strong>Indlæs</strong></li>
      <li>Nu kommer filen frem på din skærm – vær OBS på om der automatisk oprettes 2 ark – hvis der gør skal du slette <strong>Ark 1</strong> (højreklik og vælg slet)</li>
    </ol>
    <img src="../../images/img_deltagere/deltagere-eksp-valgcentral-import-fil1.png" alt="Importer fil"><br>
    <img src="../../images/img_deltagere/deltagere-eksp-valgcentral-import-fil2.png" alt="Slet ark 2">
  </details><br>

  <details>
    <summary><strong>Trin 5.3: Omdøb dine opgavetyper så de passer til Valg Central</strong></summary>
    <p>Importen til Valg Central <strong>må kun indeholde rollerne Valgsekretær og Tilforordnet.</strong></p>
    <p>Hvis du har brugt andre opgavetyper i Valghalla <strong>skal</strong> du derfor tilrette rollerne i kolonne A, så de passer til kravet fra Valg Central.</p>
    <p>Hvis du har Valgstyrere på listen skal disse omdøbes til Tilforordnet.</p>
  </details>

  <details>
    <summary><strong>Trin 5.4: Gem filen inden import til Valg Central</strong></summary>
    <p>Når du har tilrettet filen skal du gemme den som CSV UTF-8 (kommasepareret).</p>
    <p>Vælg <strong>Gem Som</strong> og derefter den korrekte filtype.</p>
    <img src="../../images/img_deltagere/deltagere-eksp-gem-som-utf.png" alt="Gem fil før import til valgcentral">
  </details>

</details>