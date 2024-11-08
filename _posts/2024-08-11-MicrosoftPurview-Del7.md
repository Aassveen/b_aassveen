---
title:  "Insider Risk Management 🥷"
date:   2024-08-11
classes: wide
toc: false
categories: 
- Blog
tags:
  - Purview
  - Data
  - Informasjonsforvaltning
---

***Microsoft Purview del 7: Dette er del 7 av flere deler som omhandler Microsoft Purview og hvilke verktøy man har tilgjengelig der.***

## Hva er Insider Risk Management?
Microsoft Purview Insider Risk Management er en løsning designet for å hjelpe organisasjoner med å identifisere, undersøke og håndtere interne risikoer. Disse risikoene kan inkludere både utilsiktede og ondsinnede handlinger fra ansatte som kan føre til datalekkasjer, tyveri av immaterielle rettigheter (IP), og andre sikkerhetsbrudd.

## Hvilke funksjoner finnes i modulen?
Insider Risk Management tilbyr en rekke funksjoner for å håndtere interne risikoer:
* **Insider Risk policy**: Opprettelse av tilpassede policyer basert på forhåndsdefinerte maler for å overvåke spesifikke risikoer som datalekkasjer og sikkerhetsbrudd
* **Analytics and Insights**: Bruk av avansert analyse og maskinlæring for å identifisere potensielle risikoer og gi innsikt i brukeraktiviteter.
* **Alerting and Case Management**: Generering av varsler og administrasjon av saker for å undersøke og håndtere risikoer effektivt.
* **User Activity Reports**: Detaljerte rapporter om brukeraktiviteter for å identifisere og undersøke mistenkelige handlinger.
* **Privacy Controls**: Innebygde personvernkontroller som pseudonymisering av brukere og rollebasert tilgang for å beskytte brukerens personvern.

## Hvilke lisenser trengs?
**For å bruke Microsoft Purview Insider Risk Management, trenger organisasjonen en Microsoft 365 E5-lisens eller en tilsvarende lisens som inkluderer E5 Compliance.**

## Konkrete eksempler på bruk
* **Forebygging av datalekkasjer**: I eksempelet vist under har jeg opprettet en datalekkasje policy basert på en mal ("Data leaks")
![image](https://github.com/user-attachments/assets/36850b5c-55a4-4847-a6c0-1a0382da0acb)

Policyen kan scopes på alle brukere, utvalgte brukere, utvalgte grupper eller ved å sette et adaptivt scope (basert på metada, eks. alle team som inneholder navn *prosjekt*) 
![image](https://github.com/user-attachments/assets/db75a061-8387-48a5-9f2f-baf5b84c789a)

I neste steg kan du velge å prioritere innhold basert på noen predefinerte valg
![image](https://github.com/user-attachments/assets/ad0216f4-c728-40f5-b265-deb22274e272)

Etter å ha definert hvilke sensitivitets etiketter og sensitive informasjonstyper jeg ønsket skulle være prioritert kan jeg velge om det skal varsles på alle oppdagelser eller bare ved prioritert innhold
![image](https://github.com/user-attachments/assets/318de0f3-1afb-4a7a-9e30-96fa1a32fefc)

I neste steg definerer jeg triggere for policyen før jeg setter terskler. Her kan man velge å bruke Microsoft standard terskler eller definere disse selv.

![image](https://github.com/user-attachments/assets/d7ac371f-8896-4541-bf8d-9bc89d8731d8)
![image](https://github.com/user-attachments/assets/80cd88ba-b70d-47b6-ae27-e60219a34dd9)


Oppsummert vil da policyen se sånn ut

![image](https://github.com/user-attachments/assets/e1b0a3db-d461-406d-b524-6182afced1e9)

## Konklusjon
*Selv om Microsoft Purview Insider Risk Management tilbyr kraftige verktøy for å håndtere interne risikoer, må norske organisasjoner nøye vurdere hvordan de implementerer disse verktøyene for å sikre at de overholder personvernlover og opprettholder et tillitsfullt arbeidsmiljø. Det er viktig å balansere behovet for sikkerhet med respekten for ansattes personvern.*


`Bjørnar & AI`

