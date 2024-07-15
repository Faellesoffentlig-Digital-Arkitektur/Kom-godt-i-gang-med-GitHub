**Governance-model for den fællesoffentlige arkitektur (FDA)**

## Versionering

Versionering består af tre dele MAJOR.MINOR.PATCH alle angivet ved tal som øges med en ad gangen.

MAJOR-delen når man laver inkompatible ændringer
MINOR-delen når man tilføjer funktionalitet på en bagudkompatibel måde
PATCH-delen når man laver bagudkompatible fejlrettelser

For dokumenter kan det fortolkes således

Major-delen øges når dokumentet er substantielt ændret, herunder så det afføder at andre dokumenter el.lign., der henviser til/bygger pågældende dokument må ændres indholdsmæssigt (mere end et nyt sidetal/dybdelink), hvis anbefaling peger i ny retning eller hvis dokumentets scope ændres, fx ved sletning af kapitler. Ved dokumenter der indeholder krav vil indførelsen af nye obligatoriske krav (SKAL/(SKAL IKKE), eller ændring af krav på ”lavere” niveau til SKAL/SKAL-IKKE altid medfører en ny major-version.

Minor-delen øges når ved mindre bagudkompatible ændringer og tilføjelser, herunder fx formidlingsorienterede rettelser, omstruktureringer og tilføjelser af yderligere forklaringer og eksempler/cases eller opdatering af eksempler. Indholdsmæssige tilføjelser kan også være minor, hvis de følger dokumentets oprindelige retning, og ikke forårsager at anvendere risikerer ikke længere at være ”kompliant”. Ved dokumenter er indeholder krav, kan kun valgfrie krav indføres. Obligatoriske krav kan gøres valgfri, men ikke omvendt.

Patch-delen øges ved rettelser der ikke påvirker indhold overhovedet, primært fejlrettelser, fx stave- og grammatikfejl, opdatering af døde links / henvisninger, opdatering af ændrede navne (fx SDA -> UAS), ændringer af layout eller (billed)formater.

Udkast har versionsnumre der starter med nul (fx 0.5.1). 1.0.0 er første færdige (udgivne) version.
