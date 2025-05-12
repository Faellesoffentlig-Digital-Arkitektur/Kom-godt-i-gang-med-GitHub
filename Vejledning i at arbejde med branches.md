# Branches

## Brug af branches og review-proces for tekstfiler (.md) i GitHub

Denne vejledning beskriver, hvordan vi arbejder effektivt med branches og review-processer i GitHub, når vi opdaterer dokumenter i [Fællesoffentlig Digital Arkitektur](https://github.com/Faellesoffentlig-Digital-Arkitektur). Formålet er at skabe gennemsigtighed, sporbarhed og sikre samarbejde.

---

### 1. Navngivning af branches

**Branch-navne bør følge formatet:**

```
<type>_<kort-navn>_v<versionsnummer>
```

**Eksempel:**  
`minor_reviewguideline_v2.1.2`

**Type-angivelse:**

- `fix`: mindre rettelser, fx sprog eller layout.
- `minor`: nye afsnit, mindre ændringer i indhold.
- `major`: større ændringer i struktur eller formål.

**Versionsnummer (SemVer-inspireret):**

- `MAJOR.MINOR.PATCH` – fx `2.1.2`
  - Øg `PATCH` ved små rettelser.
  - Øg `MINOR` ved nye funktioner eller afsnit.
  - Øg `MAJOR` ved gennemgribende ændringer.

---

### 2. Samarbejde og pull requests

Når I er flere om at opdatere en tekstfil (fx Maya og dig):

- **Trin 1:** Opret en ny branch som beskrevet ovenfor.
- **Trin 2:** Lav dine ændringer og commit dem løbende.
- **Trin 3:** Opret et **Pull Request (PR)** fra din branch til `main`.

**Sådan gør du PR synlig og åben for kommentarer:**

- Beskriv kort ændringerne i beskrivelsesfeltet.
- Brug @mention for at invitere specifikke kolleger til at kommentere.
- Alle med adgang kan nu læse, foreslå ændringer og kommentere via GitHub UI.

---

### 3. Versionshistorik og opdatering på FDA

**Hvor noteres versionen?**

- Nederst i dokumentet i en sektion kaldet fx `## Versionshistorik`.
- Brug format:
  
  ```
  - v2.1.2 (2025-05-12): Tilføjet afsnit om branches og review-proces. [Birgitte Buchhave]
  ```

**Opdateringer i Drubal/FDA:**

- Den produktansvarlige opdaterer:
  - **“Seneste opdateringsdato”** og **versionsnummer** i metadata-feltet.
  - **Indholdsfortegnelse** genereres som regel automatisk (ved brug af heading-tags i Markdown).
  - Husk at sikre **webtilgængelighed** (korrekte headings, alt-tekster på figurer mv.).

---

### 4. Skal vi bruge "Tags" og "Releases"?

**Ja, men med måde.**  
Brug `Tag` og `Release` til vigtige milepæle. Fx når en ny vejledning er klar til publicering.

- **Tag:** Navngives som versionen – fx `v2.1.2`
- **Release:** Beskriver hvad der er ændret, og linker til pull request og versionshistorik.

---

### 5. Opdatering af figurer (fx fra Majlen)

- Figurer gemmes typisk i mappen `/figures` eller lignende.
- Når du udskifter en figur:
  - Upload den nye via “Upload files”-funktionen i GitHub.
  - Opdater linket i .md-filen:
    
    ```md
    ![Alt-tekst](../figures/nyfigur.png)
    ```

---

### 6. Webtilgængelighed

Følg disse tjekpunkter:

- Brug altid korrekte heading-niveauer (`##`, `###` osv.).
- Tilføj alt-tekster til billeder.
- Undgå kun at bruge farver til at formidle budskaber.
- Brug tabelstruktur korrekt – undgå at bruge dem til layout.

---

### 7. Sådan redigerer du korrekt

**Værktøj og visning:**

- På GitHub.com: vælg **Edit this file** > **Edit in place**.
- I MarkText: skift til **Source Code mode**, så linjenumre matcher mellem review og visning.

---

### 8. Forstå de forskellige visninger i en pull request

- **Commits:** Vis ændringer over tid. Nyeste nederst.
- **Files changed:** Her ser du hvad der konkret er ændret. Bruges til review.
- **Kommentarer:** Bruges til at give feedback – også til ting, der *ikke* er rettet.

**Tips:**

- Lav alle rettelser samlet for at undgå mange notifikationer.
- Hvis du som reviewer er enig → ingen kommentar.
- Hvis du er uenig eller har spørgsmål → skriv en kommentar.
- Når du er færdig med at reviewe → klik på **Review changes** > vælg **Approve**.

---

### Bonus: Opsæt mails fra GitHub

- Brug din mailklient til at sortere GitHub-mails i egen mappe, fx ved at filtrere på afsender `notifications@github.com`.
