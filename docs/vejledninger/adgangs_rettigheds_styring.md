---
layout: default
title: "Adgangs- og rettighedsstyring"
parent: "Vejledninger"
---

##  Administrativ hjemmeside 

Adgangs- og rettighedsstyring til den administrative hjemmeside styres ved hjælp af [Fælleskommunal Adgangsstyring for brugere](https://digitaliseringskataloget.dk/l%C3%B8sninger/adgangsstyring-brugere) (også kendt som Context handler). Det er altså kommunens egen opsætning af brugere og jobfunktionsroller, som styrer, hvilke medarbejdere der kan få adgang.

Anonyme brugere kan ikke tilgå den administrative hjemmeside, men vil blive mødt af et krav om login, hvis det forsøges.

### Brugerroller

Der er kun en enkelt brugerrolle i den administrative hjemmeside: Administrator.

Rollen giver disse rettigheder:

  * Kan oprette deltagere manuelt for at hjælpe de deltagere, der ikke selv kan finde ud af det eller ikke har MitID.
  * Kan se, redigere og slette alle deltagere for at sikre at oplysningerne er korrekte.
  * Kan oprette deltagere og tildele disse rettigheder baseret på de opgaver, der falder indenfor rollens ansvarsområde.
  * Kan eksportere deltagerlister så de kan gemmes i et ESDH-system.
  * Bliver gjort opmærksom på alle deltagere, der ikke kan modtage Digital Post.
  * Kan ændre konfigurationer så systemet tilpasses den kommune, administratoren tilhører. Disse konfigurationer inkluderer arbejdssteder, opgavetyper, tilmeldingsskabeloner og oplysningserklæring.
  * Kan oprette opgaver og tildele dem til deltager eller generere links, som gør det muligt for deltagere selv at tilmelde sig opgaver via den eksterne hjemmeside
  * Kan sende kommunikation via Digital Post, e-mail og SMS til deltagere



##  Ekstern hjemmeside 

Adgang til den eksterne hjemmeside kan kun ske med MitID. Dette gælder både for borgere og medarbejdere, der skal løse opgaver i forbindelse med valget.

NemLog-In benyttes som MitID-broker.

### Brugerroller

En deltager kan oprette sig selv, hvis personen inviteres til et team eller tilmelder sig en opgave.

I den administrative hjemmeside kan der tildeles ekstra rettigheder til en deltager som teamansvarlig og arbejdsstedsansvarlig.

Der er fire forskellige roller.

  * **Anonym** : Bruger, der ikke er logget ind. Kan tilgå den eksterne hjemmeside og se noget af indholdet.
  * **Deltager** : Almindelig deltager i valget. Skal være tilknyttet mindst et team
  * **Teamansvarlig** : Har samme rettigheder som en deltager samt mulighed for at se teamoplysninger, status på teamets opgaver og links til opgaverne
  * **Arbejdsstedansvarlig** : Har samme rettigheder som en deltager samt mulighed for at se oplysninger om de deltagere, der er tilknyttet et arbejdssted



I oversigten kan du se, hvilke områder af OS2valghalla, der er tilgængelig for forskellige brugerroller.

Test|  Anonym |  Deltager |  Teamansvarlig |  Arbejdssteds-ansvarlig  
---|---|---|---|---  
**Forside** | X | X | X | X  
**Kontaktoplysninger** | X | X | X | X  
**Opgaver**  
**(delt via link)** | X | X | X | X  
**Teamets opgaver** |  | X | X | X  
**Mine opgaver** |  | X | X | X  
**Min profil** |  | X | X | X  
**FAQ** | X | X | X | X  
**Mit team** |  |  | X |   
**Opgavefordeling** |  |  | X |   
**Mit arbejdssted** |  |  |  | X
