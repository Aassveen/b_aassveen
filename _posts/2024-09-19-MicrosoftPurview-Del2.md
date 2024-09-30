---
title:  "Microsoft Purview del 2: Effektive verktøy for moderne datastyring🔓"
date:   2024-09-19
classes: wide
toc: false
categories: 
- Blog
tags:
  - Purview
  - Data
  - Informasjonsforvaltning
---

***Microsoft Purview del 2: Dette er del 2 av flere deler som omhandler Microsoft Purview og hvilke verktøy man har tilgjengelig der.***

**I denne bloggposten dykker vi ned i to kraftige verktøy i Microsoft Purview: eDiscovery og Content Explorer.**
* Disse verktøyene er essensielle for organisasjoner som ønsker å administrere og beskytte sine data effektivt. Vi tar en titt på hvordan eDiscovery kan hjelpe med å finne og bevare relevant informasjon for juridiske saker og undersøkelser, samt hvordan Content Explorer gir innsikt i dataene dine, slik at du kan identifisere og administrere sensitiv informasjon på en sikker måte. 

***eDiscovery Administrator*** 
eDiscovery i Microsoft 365 er et sett med funksjoner designet for å hjelpe med å søke, samle og eksportere data fra Microsoft 365-organisasjoner. Det er en prosess for å identifisere og levere elektronisk informasjon som kan brukes som bevis i rettssaker eller lignende.  
En eDiscovery Administrator kan utføre de samme oppgavene som en eDiscovery Manager, som inkluderer bruk av eDiscovery søkeverktøy for å søke i innholdsplasseringer i organisasjonen, og utføre forskjellige søkerelaterte handlinger som forhåndsvisning og eksport av søkeresultater. De kan også opprette og administrere saker i Microsoft Purview eDiscovery (Standard) og Microsoft Purview eDiscovery (Premium), legge til og fjerne medlemmer i en sak, opprette saksbeholdninger, kjøre søk knyttet til en sak, og få tilgang til saksdata. 
*I tillegg til dette, kan en eDiscovery Administrator: 
* Få tilgang til alle saker som er oppført på eDiscovery (Standard) og eDiscovery (Premium) sidene i Compliance Portal. 
* Få tilgang til saksdata i eDiscovery (Premium) for enhver sak i organisasjonen. 
* Administrere enhver eDiscovery sak etter at de har lagt seg selv til som medlem av saken. 
* Fjerne medlemmer fra en eDiscovery sak. Bare en eDiscovery Administrator kan fjerne medlemmer fra en sak. 

**Eksempel på bruk av eDiscovery rollen**
La oss si at det er en juridisk sak som involverer en ansatt i organisasjonen din, kalt “Ansatte X”. Du, som eDiscovery Administrator, har fått oppgaven å finne alle e-poster og dokumenter som er relatert til denne saken. 
* Opprett en sak: Først vil du opprette en ny sak i eDiscovery-portalen. Du kan gi den et navn som er relevant for undersøkelsen, for eksempel “Sak Ansatte X”. 
* Legg til medlemmer: Deretter vil du legge til relevante medlemmer til saken. Dette kan være andre administratorer eller juridiske teammedlemmer som trenger tilgang til saken. 
* Opprett en søkeforespørsel: Nå vil du opprette en søkeforespørsel innenfor saken. Du kan bruke nøkkelord, datoer, og spesifisere steder å søke, som postbokser eller OneDrive-kontoer. I dette tilfellet kan du for eksempel søke etter “Ansatte X” i alle e-poster og dokumenter i en bestemt tidsperiode. 
* Gjennomgå resultatene: Når søket er fullført, kan du forhåndsvise resultatene direkte i portalen. Du kan også eksportere resultatene for videre analyse. 
* Opprett en sakbeholdning: Hvis du finner relevant informasjon, kan du opprette en sakbeholdning for å bevare innholdet i en bestemt tidsperiode. Dette sikrer at dataene ikke blir slettet eller endret mens saken pågår. 



 
***Content Explorer***
Content Explorer i Microsoft Purview er et verktøy som gir deg en oversikt over elementene i organisasjonen din som har en sensitivitetsetikett, en bevaringsetikett eller er klassifisert som en sensitiv informasjonstype. 
Her er noen av hovedfunksjonene til Content Explorer: 
* Den viser et øyeblikksbilde av elementene som har en sensitivitetsetikett, en bevaringsetikett eller har blitt klassifisert som en sensitiv informasjonstype i organisasjonen din. 
* Den identifiserer automatisk vanlige typer sensitiv data basert på hundrevis av innebygde datamønstre som personnummer, bankkontoinformasjon eller førerkortnumre. 
* Content Explorer viser også hvor disse datatypene er plassert, og du kan til og med bore ned til filen eller e-postmeldingen som inneholder den. 
* Du kan bruke Content Explorer til å forbedre ytelsen til egendefinerte trenbare klassifiseringer ved å gi dem mer tilbakemelding. 

![image](https://github.com/user-attachments/assets/00109f1d-b16a-4c57-877a-b0c80ea8f79f)


**Tilgang til Content Explorer er sterkt begrenset fordi det lar deg lese innholdet i skannede filer. Det er to roller som gir tilgang til Content Explorer, og det gis ved hjelp av Microsoft Purview compliance portal:**
* Content Explorer List viewer: Medlemskap i denne rollegruppen lar deg se hvert element og dets plassering i listevisning. 
* Content Explorer Content viewer: Medlemskap i denne rollegruppen lar deg se innholdet i hvert element i listen. 

Kontoen du bruker for å få tilgang til Content Explorer, må være i en eller begge rollegruppene. Disse er uavhengige rollegrupper og er ikke kumulative. For eksempel, hvis du vil gi en konto muligheten til bare å se elementene og deres plasseringer, tildel Content Explorer List viewer-rettigheter. Hvis du vil at den samme kontoen også skal kunne se innholdet i elementene i listen, tildel Content Explorer Content viewer-rettigheter også. 
En global administrator kan tildele nødvendig Content Explorer List Viewer og Content Explorer Content Viewer rollegruppemedlemskap. 

`Bjørnar & AI`
