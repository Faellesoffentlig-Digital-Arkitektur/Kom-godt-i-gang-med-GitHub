# Brugervejledning til github

## Værktøjer

**Github desktop** https://desktop.github.com/ Bruges til at få sine ændringer op til github og hente nyeste version (installer)

**MarkText** https://www.marktext.cc/ Brugervenlig måde at lave overskrifter, tabeller m.m. ala word program til markdown, gratis program (installer)

**Github.com** (Til merge, issues + evt. wiki (howto guides) + projects til opgaver og issues med forskellige views )

**Html-to-markdown** (Tag en del af en html fil og ændre til markdown, men der er noget som skal justeres efterfølgende (fx. billeder, links). https://htmlmarkdown.com/)

## Guides

### Invitation til repository

1. **Gå til dit repository**:
   
   - Log ind på GitHub.
   
   - Gå til det repository, hvor du
     vil invitere en ny bruger.  

2. **Gå til 'Settings'**:
   
   - Klik på 'Settings' øverst til
     højre i dit repository.  

3. **Gå til 'Collaborators and teams'**:
   
   - Klik på knappen 'Invite people'  

4. **Find brugere**:
   
   - Skriv brugernavnet eller
     e-mailadressen på den person, du vil invitere.
   
   - Klik på 'Select a member above'  

5. **Send invitationen**:
   
   - Den inviterede person vil modtage
     en e-mail med en invitation til at blive bidragsyder til dit
     repository.
   
   - Når personen accepterer invitationen, vil de få adgang til
     dit repository afhængigt af den rolle, du har tildelt dem.

**Husk**  
For at kunne invitere andre til et repository,
skal du have de nødvendige rettigheder (typisk som ejer eller
administrator af repositoryet).  

Bruger skal minimum have
write tilladelse for at push til main repo. Alle kan lave et pull
request som en admin så kan tage stilling til

### Hvordan oprettes tags og releases.

**(LINK TIL Release procedure for produkter)**

At lave tags i GitHub Desktop og oprette en release i GitHub.com
er en to-trins proces, der involverer både det lokale GitHub
Desktop-program og den online GitHub.com-tjeneste. Her er en trinvis
vejledning:

### Opret et tag i GitHub Desktop

1. **Åbn GitHub Desktop**:
   
   - Start GitHub Desktop og åbn det
     repository, hvor du vil oprette et tag.

2. **Opret et tag**:
   
   - Commit din ændring hvor der er
     skal laves en ny release
   
   - Klik på History
   
   - Højre på din release
   
   - Klik på `Create tag`
   
   - Indtast tag-navnet (f.eks., `v1.``3`)
     og en besked, hvis det er nødvendigt.
   
   - Klik på `Create Tag`.

3. **Synkroniser dine ændringer**:
   
   - Klik på `Push origin` for at
     sende dit nye tag til GitHub repository.

### Opret en release i GitHub.com

1. **Åbn dit repository på GitHub.com**:
   
   - Gå til GitHub.com og naviger til
     dit repository.

2. **Opret en ny release**:
   
   - Klik på `Releases` sektionen i højre menu eller naviger til
     `https://github.com/<dit-brugernavn>/<dit-repository>/releases`.
   
   - Klik på `Draft a new release` knappen.

3. **Udfyld release oplysninger**:
   
   - Under `Tag version`, vælg det tag, du lige har oprettet i GitHub
     Desktop.
- Indtast en titel for din release
   (f.eks., `Version v1.``3`).

- Skriv en beskrivelse af
   ændringerne i denne release. Du kan inkludere ændringer,
   forbedringer, eller fejlrettelser, som er inkluderet i denne
   version.  
2. **Publicer releasen**:
   
   - Når alle oplysninger er udfyldt, klik på `Publish release` knappen.



### Hvordan finder man gamle versioner af et produkt (releases)

- Naviger til det repository, hvor du ønsker at finde en anden version .

- Klik på pilen til højre for main

- Klik Tags

- klik på den version (release) som du skal bruge

![Hvordan finder man gamle versioner af et produkt.png](assets/75b98b4913536ef88bec803d0aefcfdbc9aadb3e.png)



### Hvordan Lægges rettelser på github

### Merge og håndtering af konflikter

For at **merge** branches ved hjælp af GitHub Desktop, følg disse trin:

#### Trin-for-trin vejledning

1. **Åbn GitHub Desktop** og sørg for, at du har
   klonet det repository, du vil arbejde på.

2. **Vælg den branch**, du ønsker at merge
   ændringerne til. Dette er typisk `main` eller en anden primær branch. Du kan vælge branch i øverste
   venstre hjørne af GitHub Desktop-vinduet.

3. **Klik på "Branch"** i menulinjen og
   vælg derefter "Merge into current branch...".

4. **Vælg den branch**, du vil merge fra, i den
   liste, der vises. Dette vil typisk være den feature branch, du har
   arbejdet på.

5. **Klik på "Merge [branch name] into [current
   branch]"**. GitHub Desktop vil nu forsøge at merge
   ændringerne.

#### Håndtering af konflikter

Hvis der opstår merge-konflikter, vil GitHub Desktop informere
dig om det. Du kan så åbne den konfliktfyldte fil ved at klikke på
filnavnet i GitHub Desktop og manuelt rette konflikten ved at vælge
hvilke ændringer der skal beholdes.

1. **Klik på den konfliktfyldte fil** i listen
   over konflikter.

2. **Rediger filen** for at løse konflikten. Dette
   kan gøres direkte i GitHub Desktop eller ved at åbne filen i din
   foretrukne teksteditor.

3. Når konflikten er løst, **marker konflikten som løst** i GitHub Desktop ved at klikke på "Mark as resolved".

4. **Commit de løste konflikter** ved at skrive en
   commit-besked og klikke på "Commit merge".

### Markdown editor (MarkText)

#### Tilføj billeder, ved nyt produkt eller rediger produkt

1. Oppe i venstre hjørne klik på de 3 streger og vælg "File" - > Preferences -> image 
2. Klik "Prefer relative assets folder" som den er sat til (grøn).
3. Drag 'n' drop nu billeder fra assets folderen til de steder hvor der mangler  billeder

Merge og håndtering af konflikter

### Issues og krydshenvisninger guide

Hvordan bruges issue-funktionen i GitHub i public repositories
· Den interne proces – fra issue til rettelse
· Notifikation vedr. issues

#### Issues

Når et nyt issue oprettes på GitHub, kan forskellige brugere modtage notifikationer baseret på deres involvering og indstillinger. Her er en oversigt over, hvem der typisk får notifikationer:

1. **Repository Ejer og Collaborators**: Alle, der har write eller administrativ adgang til repository, vil som standard modtage notifikationer om nye issues, medmindre de specifikt har slået dem fra.

2. **Watchers**: Brugere, der har valgt at "watch" repository, vil modtage notifikationer om alle aktiviteter, herunder nye issues. Der er forskellige niveauer af watching:
   
   - **Watching**: Modtager notifikationer om alle aktiviteter.
   - **Not watching**: Modtager kun notifikationer, når de bliver nævnt direkte eller involveret i en tråd.
   - **Ignoring**: Modtager ingen notifikationer overhovedet.

3. **Nævnte Brugere**: Hvis en bruger bliver nævnt i et issue ved hjælp af @-mention (f.eks. @username), vil denne bruger få en notifikation.

4. **Tidligere Deltagere**: Brugere, der tidligere har deltaget i en tråd (f.eks. kommenteret på et tidligere issue eller pull request), vil typisk modtage notifikationer om nye kommentarer eller ændringer.

5. **Team Mention**: Hvis et helt team nævnes (f.eks. @org/team-name), vil alle medlemmer af dette team modtage en notifikation.

Indstillinger for notifikationer kan tilpasses af den enkelte bruger i deres GitHub-indstillinger, hvor de kan vælge præferencer for, hvordan og hvornår de vil modtage notifikationer.

#### krydshenvisninger

For at lave en krydshenvisning til en issue, pull request eller commit på
GitHub, kan du bruge deres nummer eller hash, som følger:

- **Issues:** Brug `#` efterfulgt af issue-nummeret.
  
  ```
  Se issue #42 for mere information.
  ```

- **Pull Requests:** Brug `#` efterfulgt af pull request-nummeret.
  
  ```
  Dette løser problemet beskrevet i pull request #123.
  ```

- **Commits:** Brug `@` efterfulgt af commit-hashen.
  
  ```
  Dette problem blev løst i commit @abcdef.
  ```

#### Krydshenvisninger til Tekstlokationer i

Markdown-filer

Hvis du vil krydshenvise til en specifik placering i en
Markdown-fil, som f.eks. en bestemt sektion, en tabel, eller en
kodeblok:

**Tekstlokation:**

På github naviger ind på en fil som du skal henvise til og gøre som på billedet

![link til tekst i md fil.png](assets/9bf4da23a29ac8db2ac0a6419025398e67c84479.png)

Indsæt derefter i din kommentar nye issue eller andre steder på github

#### Krydshenvisninger i Kommentarer og Pull

Disse krydshenvisninger fungerer i kommentarer, issues, pull
requests og pull request-beskrivelser på GitHub. Når du bruger
disse links, vil GitHub automatisk generere et klikbart link til det
pågældende issue, pull request eller fillokation.

**Eksempel på Krydshenvisning**

Her er et eksempel på, hvordan du ville oprette en
krydshenvisning i en GitHub Issue til en specifik linje i en
Markdown-fil:

```
Jeg har fundet et problem på [linje 15 i README.md](https://github.com/brugernavn/repository/blob/main/README.md#L15). Kan nogen tage et kig?
```

Når dette er skrevet i en GitHub Issue eller en anden kommentar, vil
det generere et link, der direkte fører læseren til den pågældende
linje i README.md-filen.

Ved at bruge disse krydshenvisningsmetoder kan du effektivt
forbinde forskellige elementer og filer på GitHub, hvilket gør det
lettere for brugerne at navigere og finde relevant information.

#### Ændre e-mail notifikationer på et repository

- Naviger til det repository, hvor du ønsker at ændre notifikationsindstillingerne.

- Klik på pilen til højre for unwatch

![Ændre notifikationer på et repository.png](assets/3034c681dc9cc668c15b5e2778a80515a71e7c19.png)
