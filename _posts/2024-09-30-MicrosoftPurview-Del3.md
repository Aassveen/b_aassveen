---
title:  "Microsoft Purview del 3: Sensitive informasjonstyper💾"
date:   2024-09-30
classes: wide
toc: false
categories: 
- Blog
tags:
  - Purview
  - Data
  - Informasjonsforvaltning
---

***Microsoft Purview del 3: Dette er del 3 av flere deler som omhandler Microsoft Purview og hvilke verktøy man har tilgjengelig der.***
**I denne bloggposten dykker vi ned i hvordan man kan identifisere og behandle sensitive informasjonstyper (SITs) i Microsoft Purview.**

### Hva er Sensitive Information Types (SITs)?

Sensitive Information Types (SITs) er mønsterbaserte klassifikatorer som brukes til å identifisere og beskytte sensitiv informasjon i organisasjonens data. Eksempler på sensitiv informasjon inkluderer personnummer, kredittkortnummer, bankkontonummer og andre typer opplysninger. I Microsoft Purview får du en hel del forhåndsdefinerte SITs du kan velge å bruke som de er, kopiere og/eller tilpasse.
Her et eksempel på Norsk persnonnummer.
![image](https://github.com/user-attachments/assets/37d7355d-d548-4269-86a1-35fd657a2b3a)
![image](https://github.com/user-attachments/assets/abca47d3-d2fd-4c27-b3f3-f22e06ad9e77)




### Hvordan fungerer SITs?

SITs bruker mønstre som kan inkludere regulære uttrykk, nøkkelordlister og funksjoner for å oppdage spesifikke typer sensitiv informasjon. Hver SIT består av flere komponenter:
- **Primære elementer**: Hovedmønsteret som SIT leter etter, som kan være et regulært uttrykk eller en nøkkelordliste.
- **Støtteelementer**: Ytterligere mønstre som øker nøyaktigheten av deteksjonen.
- **Tillitsnivå**: Angir hvor sikker SIT er på at den har funnet riktig informasjon, basert på mengden støtteelementer funnet i nærheten av det primære elementet.

### Bruksområder for SITs i Microsoft Purview

Microsoft Purview bruker SITs i flere sikkerhets- og samsvarsfunksjoner:
1. **Data Loss Prevention (DLP) Policies**: For å forhindre tap av sensitiv informasjon ved å overvåke og kontrollere dataoverføringer.
2. **Sensitivity Labels**: For å klassifisere og beskytte dokumenter og e-poster basert på sensitiviteten av innholdet.
3. **Retention Labels**: For å administrere hvor lenge data skal beholdes før de slettes.
4. **Insider Risk Management**: For å oppdage og håndtere risikoer som kommer fra interne brukere.
5. **Communication Compliance**: For å overvåke og sikre at kommunikasjon overholder organisasjonens retningslinjer.

   Eksempel på bruks av SIT (Norsk personnummer) inn i en DLP regel. Denne regelen reagerer på bruk av Norske personnummer på disse plasseringene:
![image](https://github.com/user-attachments/assets/750dfc5f-0a84-48df-927e-3e9b8f2edb68)
![image](https://github.com/user-attachments/assets/f125f92d-39a0-4093-bb83-93e686f7e6d2)

** DLP policyen sender et varsel til sluttbruker om at du nå behandler informasjon som inneholder personnummer.
![image](https://github.com/user-attachments/assets/ff22a59d-3bb7-4d77-8515-cd0fc58a5eae)




### Opprettelse av egendefinerte SITs

Hvis de forhåndskonfigurerte SITs ikke dekker dine behov, kan du opprette egendefinerte SITs. Dette kan gjøres ved å definere nye mønstre eller ved å kopiere og tilpasse eksisterende SITs. Dette gir organisasjoner fleksibiliteten til å tilpasse sikkerhets- og samsvarsstrategier til deres spesifikke krav.

`Bjørnar & AI`
