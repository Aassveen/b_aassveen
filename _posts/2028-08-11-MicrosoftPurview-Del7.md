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
Microsoft Purview Insider Risk Management er en løsning designet for å hjelpe organisasjoner med å identifisere, undersøke og håndtere interne risikoer. Disse risikoene kan inkludere både utilsiktede og ondsinnede handlinger fra ansatte som kan føre til datalekkasjer, tyveri av immaterielle rettigheter (IP), og andre sikkerhetsbrudd1.

## Hvilke funksjoner finnes i modulen?
Insider Risk Management tilbyr en rekke funksjoner for å håndtere interne risikoer:
* **Insider Risk policy**: Opprettelse av tilpassede policyer basert på forhåndsdefinerte maler for å overvåke spesifikke risikoer som datalekkasjer og sikkerhetsbrudd
* **Analytics and Insights**: Bruk av avansert analyse og maskinlæring for å identifisere potensielle risikoer og gi innsikt i brukeraktiviteter1.
Alerting and Case Management: Generering av varsler og administrasjon av saker for å undersøke og håndtere risikoer effektivt2.
User Activity Reports: Detaljerte rapporter om brukeraktiviteter for å identifisere og undersøke mistenkelige handlinger2.
Privacy Controls: Innebygde personvernkontroller som pseudonymisering av brukere og rollebasert tilgang for å beskytte brukerens personvern1.
Hvilke rettigheter og lisenser trengs?
For å bruke Microsoft Purview Insider Risk Management, trenger organisasjonen en Microsoft 365 Enterprise E5-lisens eller en tilsvarende lisens som inkluderer E5 Compliance3. Administratorer må også tildele riktige tillatelser til brukere som skal administrere og bruke Insider Risk Management-funksjonene3.

## Konkrete eksempler på bruk
* **Forebygging av datalekkasjer**: I eksempelet vist under har jeg opprettet en datalekkasje policy basert på en mal ("Data leaks")
![image](https://github.com/user-attachments/assets/36850b5c-55a4-4847-a6c0-1a0382da0acb)

Policyen kan scopes på alle brukere, utvalgte brukere, utvalgte grupper eller ved å sette et adaptivt scope (basert på metada, eks. alle team som inneholder navn *prosjekt*) 
![image](https://github.com/user-attachments/assets/db75a061-8387-48a5-9f2f-baf5b84c789a)

I neste steg kan du velge å prioritere innhold basert på noen predefinerte valg
![image](https://github.com/user-attachments/assets/ad0216f4-c728-40f5-b265-deb22274e272)





. 
Håndtering av IP-tyveri: En ansatt som har sagt opp jobben, forsøker å sende konfidensielle dokumenter til sin personlige e-post. Systemet fanger opp denne aktiviteten og varsler sikkerhetsteamet, som kan iverksette nødvendige tiltak4.
Overvåking av uvanlige aktiviteter: Gjennom analyse av brukeraktiviteter, oppdager Insider Risk Management at en ansatt har fått tilgang til flere sensitive dokumenter utenfor arbeidstid. Dette utløser en undersøkelse for å sikre at det ikke er noen sikkerhetsbrudd2.
Håper dette utkastet hjelper deg med å komme i gang! Er det noe annet du vil legge til eller justere?
