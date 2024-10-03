---
title:  "Microsoft Purview del 4: Data Loss Prevention (DLP)🔓"
date:   2024-10-03
classes: wide
toc: false
categories: 
- Blog
tags:
  - Purview
  - Data
  - Informasjonsforvaltning
---

***Microsoft Purview del 4: Dette er del 4 av flere deler som omhandler Microsoft Purview og hvilke verktøy man har tilgjengelig der.***

**I denne bloggposten dykker vi ned i hvordan man kan definere og anvende DLP-policyer som identifiserer, overvåker og automatisk beskytter sensitive data.**

### Hva er Data Loss Prevention (DLP) og hvordan kan det brukes?
I dagens digitale verden er beskyttelse av sensitiv informasjon avgjørende for enhver organisasjon. Data Loss Prevention (DLP) hjelper bedrifter med å forhindre at sensitiv informasjon blir delt med uautoriserte personer. Microsoft Purview tilbyr en omfattende DLP-løsning som integrerer med flere Microsoft 365-tjenester som Teams, Exchange, SharePoint og OneDrive, samt Office-applikasjoner som Word, Excel og PowerPoint1.

### Hvordan fungerer DLP?
DLP i Microsoft Purview fungerer ved å definere og anvende DLP-policyer som identifiserer, overvåker og automatisk beskytter sensitive data. Dette oppnås gjennom dyp innholdsanalyse, inkludert nøkkelord, regulære uttrykk, og maskinlæringsalgoritmer. La oss se nærmere på noen av de viktigste funksjonene i DLP:

### Viktige funksjoner i DLP
1. **Identifisering av sensitiv informasjon:** DLP-policyer kan oppdage sensitiv informasjon som kredittkortnumre, personnummer og helseopplysninger ved hjelp av avanserte analysemetoder. For eksempel kan en DLP-policy oppdage og beskytte et dokument som inneholder kredittkortinformasjon som er lagret i OneDrive.
2. **Overvåking og varsling:** Når en DLP-policy oppdager et brudd, kan den automatisk varsle administratorer og brukere. For eksempel, hvis en ansatt prøver å sende en e-post med sensitive data til en ekstern mottaker, kan DLP-policyen blokkere e-posten og varsle både avsenderen og IT-avdelingen.
3. **Automatisk beskyttelse:** DLP kan automatisk beskytte sensitiv informasjon ved å kryptere data eller begrense tilgang. For eksempel kan en DLP-policy automatisk kryptere et dokument som inneholder sensitive data når det lastes opp til SharePoint.
4. **Rapportering og revisjon:** DLP gir omfattende rapporterings- og revisjonsmuligheter som hjelper organisasjoner med å spore og analysere hendelser. Dette gjør det mulig å identifisere mønstre og forbedre sikkerhetstiltakene over tid. Dette gjøres ved å kjøre policyene i simuleringsmodus.
   
### Konkrete eksempler på DLP i aksjon
**Finansinstitusjoner**: En bank kan bruke DLP til å sikre at kunders finansielle data ikke blir delt utenfor organisasjonen. Hvis en ansatt prøver å laste opp en fil med sensitive data til en personlig sky-lagringstjeneste, kan DLP blokkere handlingen og varsle sikkerhetsteamet.
**Helsevesenet**: Et sykehus kan bruke DLP til å beskytte pasientjournaler. Hvis en ansatt prøver å sende en e-post med pasientinformasjon til en uautorisert mottaker, kan DLP-policyen blokkere e-posten og varsle IT-avdelingen.
