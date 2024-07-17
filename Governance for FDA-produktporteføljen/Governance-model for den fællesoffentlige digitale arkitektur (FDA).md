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

## Roller og ansvar

### Produktansvarlig

At være ansvarlig for et produkt udarbejdet af arkitekturteamet
Produktet er fagligt forankret i arkitekturteamet

### Produktadministrator

At være ansvarlig for et produkt udarbejdet af et andet kontor i DIGST eller en ekstern organisation eks. KLVersionering

Versionering består af tre dele MAJOR.MINOR.PATCH alle angivet ved tal som øges med en ad gangen.

MAJOR-delen når man laver inkompatible ændringer
MINOR-delen når man tilføjer funktionalitet på en bagudkompatibel måde
PATCH-delen når man laver bagudkompatible fejlrettelser

For dokumenter kan det fortolkes således

Major-delen øges når dokumentet er substantielt ændret, herunder så det afføder at andre dokumenter el.lign., der henviser til/bygger pågældende dokument må ændres indholdsmæssigt (mere end et nyt sidetal/dybdelink), hvis anbefaling peger i ny retning eller hvis dokumentets scope ændres, fx ved sletning af kapitler. Ved dokumenter der indeholder krav vil indførelsen af nye obligatoriske krav (SKAL/(SKAL IKKE), eller ændring af krav på ”lavere” niveau til SKAL/SKAL-IKKE altid medfører en ny major-version.

Minor-delen øges når ved mindre bagudkompatible ændringer og tilføjelser, herunder fx formidlingsorienterede rettelser, omstruktureringer og tilføjelser af yderligere forklaringer og eksempler/cases eller opdatering af eksempler. Indholdsmæssige tilføjelser kan også være minor, hvis de følger dokumentets oprindelige retning, og ikke forårsager at anvendere risikerer ikke længere at være ”kompliant”. Ved dokumenter er indeholder krav, kan kun valgfrie krav indføres. Obligatoriske krav kan gøres valgfri, men ikke omvendt.

Patch-delen øges ved rettelser der ikke påvirker indhold overhovedet, primært fejlrettelser, fx stave- og grammatikfejl, opdatering af døde links / henvisninger, opdatering af ændrede navne (fx SDA -> UAS), ændringer af layout eller (billed)formater.

Udkast har versionsnumre der starter med nul (fx 0.5.1). 1.0.0 er første færdige (udgivne) version.

## 
