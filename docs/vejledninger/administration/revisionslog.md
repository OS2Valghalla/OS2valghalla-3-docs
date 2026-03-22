---
layout: default
title: "Revisionslog"
parent: "Administration"
has_children: false
---

# Forklaring
I revisionsloggen (også kaldet audit log) kan du finde information om alle aktiviteter foretaget i systemet. Det gælder både handlinger knyttet til automatiske og manuelle processer.

Formålet med loggen er primært at undersøge, om brugere har tilgået personlige data. Derfor er filteret 'Deltager' aktiveret, når man går ind på siden, så disse aktiviteter vises som udgangspunkt.

Hvis du fjerner Deltager-filteret, vil du se mange handlinger. Fx registreres det hver gang en bruger logger ind eller får vist en side (det fremgår som en anmodning til API, hvor fx "/api/administration/area/queryarealisting" betyder, at en bruger har fået vist oversigten over områder). Denne del af revisionsloggen kan være svær at navigere i.


### Trin for trin

<br>
<details>
  <summary><strong>Trin 1: Brug af Revisionslog</strong></summary>

<p>Fra forsiden skal du:</p>

<ol>
    <li>Vælge Administration i topmenuen</li>
    <li>Klikke på Revisionslog</li>
</ol>

<img src="../../images/img_administration/administration-revisionslog.PNG" alt="Administration - Revisionslog">

</details>
---

<details>
  <summary><strong>Trin 2: Overblik</strong></summary>

<p>På overbliksbilledet kan du se de handlinger, der er foretaget ud fra det opsatte filter.</p>

<p>Som default er filteret sat til at vise handlinger på deltagere.</p>

<ul>
    <li>Du kan fjerne filteremner ved at trykke på krydset ud for dem.</li>
    <li>Du kan sortere listen efter dato ved at trykke på tidspunkts-kolonnen.</li>
</ul>

<img src="../../images/img_administration/Administration-Overblik.PNG" alt="Administration - Revisionslog - Overblik">

</details>
---

<details>
  <summary><strong>Trin 3: Tilgå filteropsætning</strong></summary>

<p>Du kan tilgå filteropsætning ved at trykke på knappen Filtrer.</p>

<img src="../../images/img_administration/administration-filtrer.PNG" alt="Administration - Revisionslog - Filtrer">

</details>
---

<details>
  <summary><strong>Trin 4: Opsæt filter</strong></summary>

<p>Du kan filtrere i to kategorier:</p>

<ul>
    <li>Type</li>
    <li>Handling</li>
</ul>

<p>I Type-kategorien kan du vælge følgende:</p>

<ul>
    <li>Deltager</li>
    <li>Liste</li>
    <li>Teamansvarlig</li>
    <li>Arbejdsstedansvarlig</li>
    <li>API</li>
    <li>Andre</li>
</ul>

<p>I Handlings-kategorien kan du vælge følgende:</p>

<ul>
    <li>Opret</li>
    <li>Vis</li>
    <li>Rediger</li>
    <li>Slet</li>
    <li>Slå CPR op</li>
    <li>Generer</li>
    <li>Eksportér</li>
    <li>Anmod</li>
</ul>

<p>Du kan vælge flere punkter fra begge kategorier og derved lave et meget præcist filter.</p>

<p>Når du har opsat det ønskede filter, skal du trykke <strong>Luk</strong>.</p>
<p>Du kan rydde filteret ved at trykke <strong>Ryd</strong>.</p>

<img src="../../images/img_administration/administration-filter-soeg.PNG" alt="Administration - Revisionslog - Filter">

</details>