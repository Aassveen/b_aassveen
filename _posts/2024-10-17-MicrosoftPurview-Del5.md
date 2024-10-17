---
title:  "Levetidsregler 📦️"
date:   2024-10-17
classes: wide
toc: false
categories: 
- Blog
tags:
  - Purview
  - Data
  - Informasjonsforvaltning
---

***Microsoft Purview del 5: Dette er del 5 av flere deler som omhandler Microsoft Purview og hvilke verktøy man har tilgjengelig der.***

## Data lifecycle management i Microsoft Purview: Levetidsregler
Velkommen til del 5 av bloggserien om Microsoft Purview!🔓 I denne delen skal vi dykke ned i Data Lifecycle Management (DLM) og hvordan levetidsregler kan hjelpe deg med å administrere dataene dine effektivt gjennom hele livssyklusen.

### Hva er Data Lifecycle Management?
Data Lifecycle Management (DLM) er en strategi for å administrere data fra det øyeblikket de opprettes til de slettes. Målet er å sikre at dataene er tilgjengelige, sikre og i samsvar med regelverk gjennom hele deres livssyklus. Microsoft Purview tilbyr en robust plattform for DLM, som inkluderer funksjoner for dataklassifisering, styring og beskyttelse.

### Introduksjon til Levetidsregler
Levetidsregler i Microsoft Purview er en sentral komponent i DLM. Disse reglene lar deg automatisere håndteringen av data basert på deres alder, type og andre kriterier. Ved å bruke levetidsregler kan du:
* **Automatisere dataarkivering:** Flytt eldre data til arkivlagring for å redusere kostnader og frigjøre plass.
* **Slette utdaterte data:** Fjern data som ikke lenger er nødvendige for å redusere risikoen for datalekkasjer og overholdelse av regelverk.
* **Beholde viktige data:** Sikre at kritiske data oppbevares i henhold til juridiske og forretningsmessige krav.

### Hvordan Opprette Levetidsregler i Microsoft Purview
Å opprette levetidsregler i Microsoft Purview er en enkel prosess. Her er en trinnvis guide:
* **Naviger til Data Lifecycle Management:** Gå til Microsoft Purview-portalen og velg “Data Lifecycle Management” fra menyen.
* **Opprett en ny regel:** Klikk på “Policies” og velg "Retention Policies".
* **Definer kriterier:** Angi kriteriene for regelen, som datotype, alder og andre relevante parametere.
* **Konfigurer handlinger:** Velg hvilke handlinger som skal utføres når kriteriene er oppfylt, som å flytte data til arkivlagring eller slette dem.
* **Aktiver regelen:** Lagre og aktiver regelen for å begynne å administrere dataene dine automatisk.

Et eksempel på en levetidsregel (som er veldig aktuell i disse dager, se tidligere bloggpost: [Viva Engage](https://aassveen.com/blog/VivaEngage/). ) 
Skjermbildet kan være litt forvirrende da Yammer navnet enda henger igjen flere steder hos Microsoft, men denne regelen treffer altså Viva Engage poster og kommentarer som ikke er *editert siste 5 år*.

![image](https://github.com/user-attachments/assets/a42335fb-a183-4bf6-abbc-66f3d6d2df83)


### Fordeler med Levetidsregler
Implementering av levetidsregler i Microsoft Purview gir flere fordeler:
**Kostnadsbesparelser:** Reduser lagringskostnader ved å flytte eldre data til billigere lagringsalternativer.
**Forbedret sikkerhet:** Minimer risikoen for datalekkasjer ved å slette utdaterte data. Ved å holde datamengden nede får man bedre kontroll, oversikt og bedre datakvalitet.
**Overholdelse av regelverk:** Sikre at dataene dine oppbevares i samsvar med juridiske krav og interne retningslinjer.

### Nice to know
Levetidsregler fokuserer på data og innhold. For eksempel i et Team i Teams kan du sette levetid på kanalsamtaler og innhold men ikke på selve teamet. Om du ønsker å automatisere sletting av Team i Teams som ikke er aktive gjøres dette ved å sette utløpspolicy på Microsoft 365 grupper. 
Eier av Teamet mottar varsel om fornyelse 30, 15 og 1 dag før Teamets utløpsdato. Når Teameiere (Her anbefales minimum 2 Team eiere pr. Team) mottar varselet, kan de velge "forny nå" i teaminnstillingene for å fornye teamet. Om Teamet ikke har en eller flere eiere kan man sette opp en e-post adresse som får disse varslene.
![image](https://github.com/user-attachments/assets/93f97331-acae-4f56-bd05-07b9cfafd3a6)

#### Utløpspolicy (Expiration Policy)
**Automatisk opprydding:** Microsoft 365-gruppeutløpspolicyen kan automatisk rydde opp i ubrukte team. Når en utløpspolicy er satt opp, vil teameiere motta varsler om fornyelse 30 dager, 15 dager og 1 dag før teamets utløpsdato.
**Fornyelse:** Teameiere kan fornye teamet ved å velge “Forny nå” i teaminnstillingene. Hvis teamet ikke fornyes og det ikke er noen aktivitet, vil teamet bli satt i en “myk-slettet” tilstand, som betyr at det kan gjenopprettes innen 30 dager.
**Automatisk fornyelse:** Hvis et team har minst ett kanalbesøk fra et medlem før utløpsdatoen, vil det automatisk bli fornyet uten manuell inngripen.


