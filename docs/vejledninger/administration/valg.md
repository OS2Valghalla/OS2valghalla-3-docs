---
layout: default
title: "Valg"
parent: "Administration"
has_children: false
---

# Forklaring
Ved hjælp af et valg konfigureres de afgørende elementer i valgafviklingen:
- Valgtypen, som afgør hvordan det valideres om deltagerne må tage en opgave
- Hvilken periode kommunen skal have løst opgaver
- Valgdatoen
- Låseperiode
- Hvilke arbejdssteder, der skal løses opgaver på
- Kommunikationskonfiguration
- Aktivering/deaktivering

# Vigtigt om redigering af et valg
Bemærk at man ikke kan redigere valgtype, datointerval og valgdato samt fjerne arbejdssteder på et
eksisterende valg. Det skyldes stor kompleksitet i sammenhængen mellem disse elementer og fordelingen af opgaver i valget.

Hvis du har behov for at redigere disse elementer anbefaler vi, at du duplikerer det eksisterende valg og ændrer det nødvendige på den nye kopi.


### Trin for trin

<br>
<details>
  <summary><strong>Trin 1: Administration af valg</strong></summary>
  <p>Fra forsiden skal du:</p>
  <ol>
    <li>Vælge Administration i topmenuen</li>
    <li>Klikke på Valg</li>
  </ol>
  <p>Du står nu på valgoverblikket.</p><br>br
  <img src="../../images/img_administration/administration-valg.PNG" alt="Administrartion - Valg">
</details>
---

<details>
  <summary><strong>Trin 2: Valgoverblikket</strong></summary>
  <p>På denne side har du en oversigt over alle valg i din løsning, både aktive og inaktive.</p>
  <p>Du har også mulighed for at:</p>
  <ol>
    <li>Oprette nye valg</li>
    <li>Redigere eksisterende valg</li>
    <li>Redigere kommunikationskonfiguration på eksisterende valg</li>
    <li>Duplikere valg</li>
    <li>Slette valg</li>
  </ol>
  <img src="../../images/img_administration/administration-valg-valgoverblik.PNG" alt="Valgoverblik">
</details>
---

<details>
  <summary><strong>Trin 3: Opret valg</strong></summary>
  <p>Når du skal oprette et nyt valg skal du trykke på knappen opret valg</p><br><br>
  <img src="../../images/img_administration/administration-valgtyper-opret.png" alt="Administration - Valg - Opret valg">

  <details>
    <summary><strong>Trin 3.1: Titel og Type</strong></summary>
    <p>På første trin skal du opsætte de første grundlæggende indstillinger for et valg:</p>
    <ol>
      <li>En titel på valget. F.eks. EU-parlamentsvalg 2024</li>
      <li>Vælge en valgtype</li>
      <li>Angive en låseperiode</li>
    </ol>
    <p>Valgtypen afgør, hvilken validering der kan foretages af deltagerne. Som udgangspunkt er OS2valghalla sat op efter lovens bestemmelser, men du kan også selv ændre i valideringen under administration af <a href="valgtyper">Valgtyper</a>.</p>
    <p>Låseperioden angiver det tidsrum før valgdatoen, hvor deltagere ikke længere selv kan afmelde sig opgaver. I det tidsrum skal de kontakte den valgansvarlige, hvilket de oplyses om.</p><br><br>
    <img src="../../images/img_administration/Administration-valg-titel-type.png" alt="Administration - Valg - Titel og type">
  </details>

  <details>
    <summary><strong>Trin 3.2: Datoer</strong></summary>
    <p>På andet trin skal du opsætte datoer:</p>
    <ol>
      <li>Opsætte datointerval fra første dato til sidste dato du skal bemande arbejdspladser</li>
      <li>Vælge en valgdato</li>
    </ol>
    <img src="../../images/img_administration/administration-valg-datoer.PNG" alt="Administration - Valg - Dato">
  </details>

  <details>
    <summary><strong>Trin 3.3: Arbejdssteder</strong></summary>
    <p>På tredje trin skal du vælge de arbejdssteder, du skal bemande. Du opsætter, hvilke arbejdssteder der skal fremgå på listen under administration af <a href="arbejdssteder">Arbejdssteder</a>.</p><br><br>
    <img src="../../images/img_administration/administration-valg-arbejdssteder.PNG" alt="Administration - Valg - Arbejdssteder">
  </details>

  <details>
    <summary><strong>Trin 3.4: Kommunikation</strong></summary>
    <p>På sidste trin skal du opsætte kommunikation for valget. Du skal først vælge skabeloner til standardbeskeder. Disse skabeloner bruges til alt kommunikation, som ikke bliver styret af opgavespecifik opsætning.</p>
    <p>Du kan have tre typer af skabeloner - Digital Post, E-mail eller SMS. Det er vigtigt, du har opsat de rigtige typer af skabeloner i skabelonadministrationen. Du opsætter skabelonerne under administration af <a href="../kommunikation/beskedskabeloner">Beskedskabeloner</a>.</p>
    <p>Når du har udfyldt de fire trin, vil det være muligt at trykke på OK, og valget bliver nu oprettet. Bemærk at du kan redigere opsætningen af kommunikation senere.</p><br><br>
    <img src="../../images/img_administration/administration-valg-komm-beskeder.PNG" alt="Administration - Valg - Kommunikation">
  </details>
</details>
---

<details>
  <summary><strong>Trin 4: Aktivér og deaktivér valg</strong></summary>
  <p>Når et valg aktiveres, sker der to ting:</p>
  <ol>
    <li>Mere funktionalitet aktiveres på den eksterne hjemmeside, så deltagerne kan få adgang til opgaver og logge ind.
      <ol>
        <li>Funktioner til team- og arbejdsstedsansvarlige bliver også tilgængelige</li>
      </ol>
    </li>
    <li>Der udsendes automatisk invitationer til de deltagere, som er blevet tildelt en opgave
      <ol>
        <li>Bemærk at der udsendes en bekræftelse i stedet for en invitation, hvis du allerede har svaret ja på vegne af en deltager</li>
      </ol>
    </li>
  </ol>
  <p>Der udsendes ikke automatiske beskeder fra et deaktiveret valg.</p>
  <p><strong>OBS!</strong> Automatiske beskeder udsendes ikke igen, hvis man deaktiverer et igangværende valg og aktiverer det igen. Systemet registrerer, at de allerede er sendt.</p>

  <details>
    <summary><strong>Trin 4.1: Aktivér valg</strong></summary>
    <p>Klik på det røde kryds ud for det valg, som du ønsker at aktivere</p>
    <img src="../../images/img_administration/administration-valg-4-aktiver.png" alt="Aktiver valg">
  </details>

  <details>
    <summary><strong>Trin 4.2: Deaktivér valg</strong></summary>
    <p>Klik på det grønne flueben kryds ud for det valg, som du ønsker at deaktivere</p><br><br>
    <img src="../../images/img_administration/administration-valg-4-deaktiver.png" alt="Deaktiver valg">
  </details>
</details>
---

<details>
  <summary><strong>Trin 5: Skifte valg</strong></summary>
  <p>Du kan skifte mellem de oprettede valg. Bemærk at de fleste data i OS2valghalla gælder på tværs af valg. Det drejer sig om:</p>
  <ul>
    <li>Grundlæggende oplysninger konfigureret under menupunktet Administration</li>
    <li>Deltagere</li>
    <li>Beskedskabeloner</li>
  </ul>
  <p>Ved at skifte mellem valg skiftes følgende elementer:</p>
  <ul>
    <li>Opgaver, som er tilknyttet det valgte valg</li>
    <li>Potentielle modtagere af <a href="../kommunikation/send_besked">manuelt udsendte beskeder</a></li>
    <li>Oplysninger, som kan eksporteres under menupunktet <a href="../../vejledninger/lister">Lister</a></li>
  </ul>
  <p>Sådan skifter du:</p>
  <ol>
    <li>Scroll ned i bunden af siden</li>
    <li>Klik på "Skift valg"</li>
    <li>Vælg det ønskede valg i den dialog, som vises</li>
    <li>Klik OK</li>
  </ol>
  <img src="../../images/img_administration/administration-valg-5-skift.png" alt="Skifte af valg">
</details>
---

<details>
  <summary><strong>Trin 6: Duplikere valg</strong></summary>
  <p>Du kan duplikere et tidligere valg fra valgoverblikket. Klik på kopi-ikonet ud for det valg, som du ønsker at duplikere.</p><br>
  <p>Ved duplikering er det muligt at ændre på alle parametre fra det tidligere valg som fx valgperiode, valgdato og tilknyttede arbejdssteder.</p><br>
  <p>Når et valg duplikeres, overføres opgavefordelingen på de tilknyttede valgsteder. Deltagernes placering på opgaverne vil dog ikke blive overført.</p><br><br>
  <img src="../../images/img_administration/administration-valg-6-dupliker.png" alt="Dupliker valg">

  <details>
    <summary><strong>Trin 6.1: Duplikeret data</strong></summary>
    <p>Disse oplysninger duplikeres 1:1 fra det oprindelige til det nye valg:</p><br>
    <ul>
      <li>Titel</li>
      <li>Valgtype</li>
      <li>Låseperiode</li>
      <li>Arbejdssteder</li>
      <li>Kommunikationskonfiguration</li>
      <li>Opgavefordeling på arbejdssteder</li>
    </ul>
    <p>Alle oplysninger kan redigeres under duplikationen.</p><br>

    <p>Datointervallet konverteres til antal dage:</p><br>
    <p>For at sikre at opgavefordelingen duplikeres korrekt, kan systemet ikke duplikere datointervallet baseret på datoer. I stedet angives hvor mange dage før og efter valget, der skal løses opgaver.</p><br>

    <p>Disse oplysninger duplikeres ikke:</p>
    <ul>
      <li>Valgdato</li>
      <li>Deltageres placering på opgaver - det er altså kun opgavefordelingen, der duplikeres.</li>
    </ul>
    <img src="../../images/img_administration/administration-valg-6-dupliker-data.png" alt="Illustration af duplikeret data">
  </details>
</details>
---

<details>
  <summary><strong>Trin 7: Slette et valg</strong></summary>
  <p>Du kan slette et deaktiveret valg efter behov. Sammen med valget slettes fordelingen af opgaver på de tilknyttede arbejdssteder. Desuden slettes deltagernes tilknytning til opgaver i valget, så det kan være en god idé at eksportere en liste med oplysningerne inden valget slettes.</p><br>
  <p>Hvis du har behov for at gemme opgavefordelingen, kan du duplikere valget, inden du sletter det.</p>
  <ol>
    <li>Gå til valgoverblikket</li>
    <li>Klik på skraldespandsikonet ud for det valg, som du ønsker at slette</li>
    <li>Klik OK i den dialog som vises.</li>
  </ol>
  <img src="../../images/img_administration/administration-valg-7-slet.png" alt="Slet et valg">
</details>
---

<details>

  <summary><strong>Trin 8: Redigere kommunikationskonfiguration</strong></summary>
  
  <p>Det er muligt at ændre konfigurationen af, hvilke beskedskabeloner der benyttes i et valg, og om de udsendes med Digital Post, E-mail eller SMS.</p>
  <ol>
    <li>Gå til valgoverblikket</li>
    <li>Klik på talebobleikonet ud for det valg, som du vil ændre kommunikationskonfigurationen på</li>
    <li>I kolonnen <strong>Standardbeskeder</strong> opsættes de beskeder, der udsendes som standard på tværs af opgavetyper</li>
    <li>I kolonnen <strong>Opgavespecifikke beskeder</strong> kan du lave undtagelser til standarden
      <ol>
        <li>Det er fx muligt at opsætte medarbejder-rettede opgavetyper til at udsende beskeder via E-mail. Bemærk at det kræver en beskedskabelon af typen E-mail.</li>
      </ol>
    </li>
    <li>Lav de ændringer, som du ønsker</li>
    <li>Klik på OK</li>
  </ol>
  <img src="../../images/img_administration/administration-valg-8-redigere.png" alt="Rediger kommunikationskonfiguration">
</details>