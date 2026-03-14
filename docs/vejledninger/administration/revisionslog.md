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