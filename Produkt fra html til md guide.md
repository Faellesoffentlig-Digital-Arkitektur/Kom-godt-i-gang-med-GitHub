**Produkt fra html til md guide**

Guide til hvordan man ændre nuværende produkter fra
[<u>https://arkitektur.digst.dk/</u>](https://arkitektur.digst.dk/) til
markdown og læg op på github repo.  


**INFO: *Produkt Repositories er oprettet på github***


**1. Værktøjer**

**Github desktop**
[<u>https://desktop.github.com/</u>](https://desktop.github.com/) Bruges
til at få sine ændringer op til github og hente nyeste version
**(installer)**

**MarkText** [<u>https://www.marktext.cc/</u>](https://www.marktext.cc/)
Brugervenlig måde at lave overskrifter, tabeller m.m. ala word program
til markdown, gratis program (**installer)**

**Github.com** (Til merge, issues + evt. wiki (howto guides) + projects
til opgaver og issues med forskellige views )

**Html-to-markdown** (Tag en del html fil og ændre til markdown, men der
er noget som skal justeres efterfølgende (fx. billeder).
[<u>https://htmlmarkdown.com/</u>](https://htmlmarkdown.com/))

**2. Ændre produkt fra html til markdown**

- Få adgang til "Organization" https://github.com/Faellesoffentlig-Digital-Arkitektur
  med alle produkt repositories (Hvert produkt har sit eget
  repository) ved hjælp af **github desktop** vælg add og clone det
  produkt du vil arbejde på

- Brug **Html-to-markdown** til at kopier html blokken med teksten m.m. fra produktet som du arbejder på

- Kopier den oprettet markdown fil over i den github folder som du arbejder på (roden)

- Billeder: Download alle billeder fra produktet på https://arkitektur.digst.dk/
  og læg i en "assets" folder på det github produkt som du arbejder på.

- Åben markdown filen med MarkText og start processen med at gennemgå filen for fejl

- Tilføj billeder med ny billede sti.  
  
  > 1. Oppe i venstre hjørne klik på de 3 streger og vælg "File" - \>
  >    Preferences -\> image  
  > 2. Klik "Prefer relative assets folder" sæt den til (grøn).  
  > 3. Drag 'n' drop nu billeder fra assets folderen til de steder hvor
  >    der mangler billeder

**3. Push ændringer**

- Åben github desktop

- I venstre side af github desktop kan du nu se de filer som du har ændre eller tilføjet

- Nede til venstre skal du nu skrive en Summary beskrivelse og klikke commit og push origin

- Hvis der ikke er andre som arbejder på main branch og du ikke har fået en fejl så er dine ændringer nu offentlige.
