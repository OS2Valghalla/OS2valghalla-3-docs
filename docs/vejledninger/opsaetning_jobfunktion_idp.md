---
layout: default
title: "Opsætning af jobfunktionsrolle og lokal IdP"
parent: "Vejledninger"
---

Adgangs- og rettighedsstyring til den administrative hjemmeside styres ved hjælp af [Fælleskommunal
Adgangsstyring for brugere](https://digitaliseringskataloget.dk/l%C3%B8sninger/adgangsstyring-brugere) (også kendt som Context Handler). Det er altså kommunens egen opsætning af
brugere og jobfunktionsroller, som styrer, hvilke medarbejdere der kan få adgang.

OS2valghalla benytter Context Handler 2 og kræver som udgangspunkt, at brugere er godkendt til NSIS
sikringsniveau ‘Betydelig’. Det er derfor en forudsætning, at kommunens IdP har etableret trust til Context
Handler 2, og der er angivet NSIS assurance level for IdP’en i Fælleskommunalt Administrationsmodul.

---