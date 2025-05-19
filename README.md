<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# AI-basert digital søknadsbehandling for pass og ID – uten papir

Final project for the Building AI course

## Summary

Jeg foreslår en AI-basert løsning som digitaliserer hele søknadsprosessen for pass og ID-kort, slik at man slipper å skrive ut og levere papirdokumenter. AI hjelper brukeren med å fylle ut søknaden riktig, validere opplastede dokumenter og forstå regelverk. Målet er å redusere papirbruk, spare tid og gjøre offentlige tjenester mer miljøvennlige og brukervennlige.



## Background

Offentlige tjenester som søknad om pass, ID-kort og oppholdstillatelser krever ofte at brukeren skriver ut søknader og dokumenter på papir, kun for å levere dem fysisk og få dem scannet inn igjen. Dette er unødvendig både for brukeren og miljøet, spesielt i en tid hvor digital teknologi og sikker datahåndtering gjør full digitalisering mulig.

Ved å bruke kunstig intelligens kan vi forenkle og forbedre søknadsprosessen samtidig som vi kutter all papirbruk. En AI-basert løsning kan veilede brukeren i sanntid, tolke dokumenter, validere innhold, og sikre at alt er korrekt før innsending – helt digitalt.

Problemer denne løsningen adresserer:

❌ Unødvendig papirbruk og miljøbelastning

❌ Tidsbruk og frustrasjon ved å måtte skrive ut og levere dokumenter fysisk

❌ Risiko for feil eller mangler i manuelle søknader

❌ Lite brukervennlige og tungvinte søknadsprosesser

❌ Begrenset tilgjengelighet for personer med lav digital kompetanse

❌ Språkbarrierer eller misforståelser i skjemaene

❌ Ineffektiv saksbehandling hos offentlige etater

Med en AI-assistent kan hele prosessen bli mer tilgjengelig, effektiv og bærekraftig.


## How is it used?

Hvordan brukes det?

Løsningen er en AI-drevet digital assistent som guider brukeren gjennom hele prosessen med å søke om pass, ID-kort eller lignende offentlige dokumenter – uten papir. Brukeren logger inn på en trygg offentlig nettside (for eksempel Altinn eller politiets passportal), og får hjelp av AI til å:

Forstå kravene (f.eks. nødvendige dokumenter, bildekrav, gyldighet)

Fylle ut søknadsskjemaet korrekt, basert på naturlig språkdialog

Laste opp dokumenter (fødselsattest, bostedsbevis, osv.), som AI automatisk tolker og validerer

Kontrollere søknaden for feil eller mangler før innsending

Få bekreftelse og følge saken digitalt

Når er løsningen nyttig?
Når man søker om pass eller ID og vil unngå unødvendig utskrift og fysisk fremmøte for dokumentinnlevering.

Når man ønsker å spare tid og få veiledning underveis i en ellers tungvint søknadsprosess.

Når man vil bidra til lavere klimaavtrykk i offentlige tjenester.

Hvem er brukerne?
Privatpersoner som søker om pass, ID-kort, førerkort eller andre offisielle dokumenter.

Spesielt nyttig for:

Personer med begrenset digital erfaring

Innbyggere i distriktene

Utenlandsboende som søker om dokumenter via konsulat/ambassade

Miljøbevisste brukere som ønsker papirløse løsninger

Brukerbehov og hensyn:
Enkel og trygg veiledning på flere språk

Tilgjengelighet for personer med nedsatt funksjonsevne

Datasikkerhet og personvern må være ivaretatt fullt ut

Mulighet for menneskelig støtte dersom AI ikke forstår behovet




🧮 Eksempel: Hvor mye papir og miljø vi sparer med AI-løsningen

```
def calculate_environmental_savings(num_applications):
    # Antagelser:
    pages_per_application = 5       # Hvor mange A4-ark én søknad krever
    grams_per_page = 5              # Ett ark veier ca. 5 gram
    pages_per_tree = 8333           # Ett tre gir ca. 8333 A4-sider papir

    total_pages = num_applications * pages_per_application
    total_paper_grams = total_pages * grams_per_page
    total_kg_paper = total_paper_grams / 1000
    trees_saved = total_pages / pages_per_tree

    print(f"Antall digitale søknader: {num_applications}")
    print(f"Papir spart: {total_pages} sider (~{total_kg_paper:.2f} kg)")
    print(f"Trær spart: {trees_saved:.2f} trær")

# Eksempel: 100 000 digitale søknader
calculate_environmental_savings(100000)

```
Antall digitale søknader: 100000
Papir spart: 500000 sider (~2500.00 kg)
Trær spart: 60.00 trær

📌 Forklaring:
Hver papirsøknad bruker f.eks. 5 sider (kan justeres).

Vi beregner hvor mye papir og vekt dette tilsvarer.

Deretter regner vi hvor mange trær det tilsvarer å ikke bruke.



## Challenges

Selv om løsningen digitaliserer søknadsprosessen og reduserer papirbruk betydelig, løser den ikke alle utfordringer knyttet til offentlige tjenester. Her er noen begrensninger og hensyn:

❗ Begrensninger:
Digital tilgang og ferdigheter: Ikke alle har tilgang til internett, datamaskiner eller har digital kompetanse nok til å bruke AI-verktøy på egen hånd.

Avhengighet av datasystemer: Hvis systemet går ned eller opplever feil, kan det føre til forsinkelser og frustrasjon.

Språk og kulturforståelse: Selv med flerspråklig støtte, kan AI misforstå nyanser, dialekter eller spesielle behov i enkelte søknader.

Unntakssaker: Kompleks eller atypisk dokumentasjon (f.eks. utenlandske dokumenter eller nødsituasjoner) kan være vanskelig for AI å behandle korrekt.

⚖️ Etiske hensyn:
Personvern: Søknader om pass og ID inneholder svært sensitive personopplysninger. Løsningen må følge strenge GDPR-krav og sørge for sikker databehandling og lagring.

Bias og ulik behandling: AI må trenes på representative datasett for å unngå skjev behandling basert på språk, bakgrunn eller dokumenttype.

Menneskelig støtte: Det må alltid være mulig å kontakte et menneske for hjelp – AI bør ikke være eneste inngang.

Hva nå?
Dette prosjektet har potensial til å bli en fullverdig offentlig tjeneste, og kan også utvides til søknader om førerkort, bostøtte, studielån og andre offentlige dokumenter – alt papirløst og AI-støttet.

For å ta prosjektet videre trenger jeg:

Tekniske ferdigheter: Samarbeid med utviklere som har erfaring med kunstig intelligens, maskinlæring (NLP, OCR) og sikker databehandling.

Brukerdesign (UX/UI): For å sikre at løsningen er enkel å bruke for alle, inkludert eldre og personer med lav digital kompetanse.

Offentlig samarbeid: Kontakt med statlige etater (f.eks. politiet, Skatteetaten eller Altinn) som kan pilotere løsningen i praksis.

Datasett: Tilgang til realistiske, anonymiserte søknadsdata for å trene og teste AI-systemet på en sikker og etisk måte.

Etisk rådgivning og juss: For å sikre at personvern, sikkerhet og tilgjengelighet ivaretas i hele prosessen.



Dette prosjektet er inspirert av ønsket om å gjøre offentlige tjenester mer miljøvennlige, effektive og tilgjengelige for alle.

Takk til:

Elements of AI for å ha inspirert meg til å tenke kreativt rundt bruk av kunstig intelligens i samfunnet.

FNs bærekraftsmål, spesielt mål 13 (Stoppe klimaendringene), som motiverte fokuset på papirreduksjon og digitalisering.

Informasjon om papirforbruk og miljøpåvirkning er basert på åpne kilder fra WWF og The World Counts.

Illustrasjonsideen om AI og miljø ble utviklet med hjelp av OpenAI ChatGPTs bildegenerering, og brukes kun i konseptuell og ikke-kommersiell sammenheng.
