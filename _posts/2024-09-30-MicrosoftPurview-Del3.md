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

Sensitive Information Types (SITs) er mønsterbaserte klassifikatorer som brukes til å identifisere og beskytte sensitiv informasjon i organisasjonens data. Eksempler på sensitiv informasjon inkluderer personnummer, kredittkortnummer, bankkontonummer og andre typer opplysninger.

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
5. **Communication Compliance**: For å overvåke og sikre at kommunikasjon overholder organisasjonens retningslinjer¹.

### Opprettelse av egendefinerte SITs

Hvis de forhåndskonfigurerte SITs ikke dekker dine behov, kan du opprette egendefinerte SITs. Dette kan gjøres ved å definere nye mønstre eller ved å kopiere og tilpasse eksisterende SITs. Dette gir organisasjoner fleksibiliteten til å tilpasse sikkerhets- og samsvarsstrategier til deres spesifikke krav.

`Bjørnar & AI`
