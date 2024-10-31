---
title:  "Microsoft Purview del 6: Audit 👀"
date:   2024-10-31
classes: wide
toc: false
categories: 
- Blog
tags:
  - Purview
  - Data
  - Informasjonsforvaltning
---

***Microsoft Purview del 6: Dette er del 6 av flere deler som omhandler Microsoft Purview og hvilke verktøy man har tilgjengelig der.***

## Audit i Microsoft Purview
Velkommen til del 6 av bloggserien om Microsoft Purview!🔓 I denne delen skal vi dykke ned i Audit løsningen som ligger i Purview portalen.

### Hva er Audit i Microsoft Purview?
Audit i Microsoft Purview er en funksjon som lar organisasjoner spore og logge aktiviteter utført av brukere og administratorer i forskjellige Microsoft-tjenester. Dette inkluderer handlinger som pålogginger, filtilgang, endringer i innstillinger, og mye mer.
##### Audit-modulen i Microsoft Purview kan brukes til flere formål:
* **Tekniske undersøkelser**: Hjelper med å etterforske sikkerhetshendelser ved å gi detaljert innsikt i bruker- og adminaktiviteter.
* **Overholdelse av regelverk**: Sikrer at organisasjonen overholder juridiske og regulatoriske krav ved å bevare revisjonslogger.
* **Intern revisjon**: Gir internrevisorer muligheten til å overvåke og evaluere interne kontroller og prosesser.


### Hvilke funksjoner dekker Audit-modulen?
* **Søking i revisjonslogger**: Mulighet til å søke etter spesifikke aktiviteter utført av brukere eller administratorer.
* **Tilpassede oppbevaringspolicyer**: Opprettelse av tilpassede policyer for å beholde revisjonslogger basert på tjenesten der aktivitetene skjer, spesifikke aktiviteter, eller brukeren som utfører aktiviteten.
* **Smart innsikt**: Gir avanserte analyser og innsikter basert på revisjonsdataene.
* **Langvarig oppbevaring**: Mulighet til å beholde revisjonslogger i opptil 10 år med en tilleggslisens.


### Eksempler på bruk

Audit søk og Audit policyer kan som det meste annet i Microsoft settes opp og styres både fra GUI og Powershell direkte, under er noen eksempler på bruk og oppsett av policyer. 

*Audit Policy*

**GUI** 

![image](https://github.com/user-attachments/assets/64903c42-eb1d-4c58-b04a-5cf7e1798028)



**Powershell** 

`New-UnifiedAuditLogRetentionPolicy -Priority "2" -Name  "TheUsualSuspectsAgain" -Description "Policy for spesielle brukere" -UserIds "Bjornar.Aassveen@innivarmen.onmicrosoft.com" -RecordTypes "ExchangeItem, SharePoint" -RetentionDuration "FiveYears" `

Denne snutten oppretter en policy som beholder Auditposter for Exchange og SharePoint for brukeren i 5 år på lik linje som GUI oppsettet vist over. 


*Audit søk*
Audit søk er en kraftig søkemotor på tvers av alle Audit logger i Microsoft 365. Her kan man fingranulere søk basert på applikasjon, sites, workloads, brukere etc. 
![image](https://github.com/user-attachments/assets/bfdf5854-1406-4bec-8934-564f9be4d620)

Eksempelet under viser et bredt søk på bruker, her kan man eks. se alle "log in" aktiviteter på tvers. 

![image](https://github.com/user-attachments/assets/dce3d42c-d949-4835-89b8-0a76c49b5d38)



`Bjørnar & AI`
