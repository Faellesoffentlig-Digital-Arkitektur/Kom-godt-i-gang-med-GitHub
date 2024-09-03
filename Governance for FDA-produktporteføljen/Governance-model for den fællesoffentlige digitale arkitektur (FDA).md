# Governance-model for den fællesoffentlige digitale arkitektur (FDA)

Kontor for Teknologi og Data i Digitaliseringsstyrelsen står for drift og vedligehold af den fællesoffentlige digitale arkitektur.

Den fællesofentlige digitale arkitektur består af en række produkter (herefter benævnt FDA-produkter). Nyeste version af alle produkter findes både på GitHub og på arkitektur.digst.dk. Tidligere versioner af produkterne kan findes på GitHub - se vejledning til, hvordan man finder tidligere versioner af produkterne.

## Produkter

Der skelnes mellem FDA-produkter og andet fagligt indhold på arkitektur.digst.dk
Eksempel på indhold, der ikke anses for at være et FDA-produkt er ‘FDA-ordbogen’, ‘Kom godt i gang’ og ‘Genbrugssektionen’

Det fagligt indhold på arkitektur.digst.dk vil indgå i en separat proces for drift og vedligehold. 

Et FDA-produkt kan have nogle relaterede dokumenter tilknyttet.
Disse relaterede dokumenter indgår i vedligeholdelses proessen så brugerne oplever en sammenhæng i produktopgraderingen

Der skelnes mellem produkter produceret af arkitekturteamet i DIGST og produkter produceret af andre kontorer i DIGST eller en anden fællesoffentlig aktør
Der tages højde for dette i processen for drift og vedligehold af produktet

## Udfasning af produkter

Et udfaset produktet bliver ikke længere supporteret ikke supporteret.

Hvorfor er det relevant at tale om udfasning Produktporteføljen bør til alle tider være relevant og opdateret

Process for udfasning af produkter

1. Gennem servicetjek indikeres det, af den produktansvarlige, at produktet kan være kandidat til udfasning.

2. Den produktansvarlige præsenterer argumenterne for, hvorfor produktet bør udfases for arkitekturteamet i KTD. Det anbefales at kontorchefen også deltager på mødet.

3. Der skal, af den produktansvarlige, udarbejdes en kort tekst om, hvorfor det anbefales, at produktet udfases.

4. Den produktansvarlige udarbejder en plan for udfasningen. Planen udarbejdes efter følgende skabelon:
   
   4.1.  Argumenter for, hvorfor produktet skal udfases, sendes til UAS-kredsen. Mailen skal foruden argumenter for udfasning af produktet også indeholde en dato for, hvornår UAS-kredsmedlemmerne senest kan komme med indsigelser. Datoen skal ligge umiddelbart efter førstkommende UAS-møde. Modtager vi ingen skriftlige indsigelser antager vi, at UAS-kredsen accepterer udfasningen.
   
   4.2.  Forslaget om udfasning af produktet tages op på førstkommende UAS-møde.
   
   4.3.  Hvis udfasning af produktet accepteres af UAS-kredsen offentliggøres følgende på arkitektur.digst.dk og GitHub:
   
   - Produkt under udfasning (vandmærke/stempel)
   
   - Argumenter for, hvorfor produktet udfases - tilpasset til offentliggørelse, hvis nødvendigt
   
   - Henvisning til alternative produkter og løsninger- såfremt sådanne eksisterer
   
   - Dato for endlig udfasning (seks måneder frem i tiden)
   
   - Link på forsiden af arkitektur.digst.dk til produktet.
   
   4.4.  Det noteres, hvis én eller flere brugere af produktet/interessenter har indsigelser til udfasning af produktet.
   
   4.5.  På den dato, hvor produktet er sat til endelig udfasning, gennemgåes evtuelle indsigelser fra brugere af produktet/interessenter. Hvis der er modtaget relevante og velargumenterede indsigelser, så tages forslaget om udfasning op til revurdering på førstkommende UAS-møde.
   
   4.6.  Hvis der ikke er kommet indsigelser markeres det tydeligt på arkitektur.digst.dk og GitHub at produktet er udfaset og fra hvilken dato. Argumeter for udfasningen samt alternative løsningsforslag bliver ved med at være publiceret på de respektive produktsider.

5. Fra udfasnigsdatoen vil ændringsønsker, spørgsmål og fejlrettelser ikke blive håndteret af arkitekturteamet.

6. Produktet vil stadig være tilgængeligt på arkietktur.digst.dk og GitHub, men det vil tydeligt være opmærket med ‘ikke supporteret’ (vandmærke/stempel)

## Roller og ansvar

### Produktansvarlig

At være ansvarlig for et produkt udarbejdet af arkitekturteamet
Produktet er fagligt forankret i arkitekturteamet

### Produktadministrator

At være ansvarlig for et produkt udarbejdet af et andet kontor i DIGST eller en ekstern organisation eks. KLVersionering

## Versionering

Produkterne versioneres ud fra  består af tre dele major, minor og patch.  Alle angivet ved tal som øges med én ad gangen.

MAJOR-opdatering er når der laves inkompatible ændringer
MINOR-opdatering når man tilføjer funktionalitet på en bagudkompatibel måde
PATCH-opdatering når man laver bagudkompatible fejlrettelser

For dokumenter kan det fortolkes således

Major-opdateringer er når dokumentet ændres substantielt. Det vil ofte betyde ændringerherunder så det afføder at andre dokumenter el.lign., der henviser til/bygger pågældende dokument må ændres indholdsmæssigt (mere end et nyt sidetal/dybdelink), hvis anbefaling peger i ny retning eller hvis dokumentets scope ændres, fx ved sletning af kapitler. Ved dokumenter der indeholder krav vil indførelsen af nye obligatoriske krav (SKAL/(SKAL IKKE), eller ændring af krav på ”lavere” niveau til SKAL/SKAL-IKKE altid medfører en ny major-version.

Minor-opdateringer er når der ændringer er mindre bagudkompatible ændringer og tilføjelser, herunder fx formidlingsorienterede rettelser, omstruktureringer og tilføjelser af yderligere forklaringer og eksempler/cases eller opdatering af eksempler. Indholdsmæssige tilføjelser kan også være minor, hvis de følger dokumentets oprindelige retning, og ikke forårsager at anvendere risikerer ikke længere at være ”kompliant”. Ved dokumenter er indeholder krav, kan kun valgfrie krav indføres. Obligatoriske krav kan gøres valgfri, men ikke omvendt.

Patch-opdateringer øges ved rettelser der ikke påvirker indhold overhovedet, primært fejlrettelser, fx stave- og grammatikfejl, opdatering af døde links / henvisninger, opdatering af ændrede navne (fx SDA -> UAS), ændringer af layout eller (billed)formater.

Udkast har versionsnumre der starter med nul (fx 0.5.1). 1.0.0 er første færdige (udgivne) version.

## Håndtering af issues

Svartiden

Hvem håndterer de enkelte issues - product manager - produktansvarlig
