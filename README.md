# Branchhantering
## Allmänt
- Vi kopplar alltid på Netlify på våra projekt.
## Branchhantering
- Vi skriver alltid på engelska.
- Ingen skriver kod direkt i `main`.
### Namngivningskonventioner för branches:
Vi använder oss av feature-branches enligt nedan:
Börja med en kategori och namnge den sedan tydligt.
- feature is for adding, refactoring, or removing a feature.
- bugfix is for fixing a bug.
- hotfix is for changing code with a temporary solution and/or without following the usual process (usually because of an emergency).
- test is for experimenting outside of an issue/ticket.
- refactor is for code optimization.
**Exempel:**   
 `bugfix/fixed the broken login button`   
 `feature/added new shopping cart feature`   
 `hotfix/added new form due to high traffic during Christmas sales`
### När en branch är färdigjobbad:
- Merga bara färdiga branches. Ingen merge av halvklara grejer.
- Vi granskar alltid resultatet genom en godkänd site i Netlify innan vi trycker på merge.
#### Delete branch i GitHub:
- Vi tar gemensamt beslut med aktuella utvecklare då en branch deletas från Github. Ingen tar ett eget beslut kring delete av gemensam branch.
---
# Git Commits
## Git Commits
- Blanda inte olika händelser.
- Committa så fort någonting fungerar.
- Committa mellan varje ny uppgift/ämne/grej du gör.
### Våra commitmeddelanden:
Vi försöker använda oss av nedan regler, men känner på hur det fungerar nu i början. Tbc… Utvärderas under loppets gång.   

- feat is for adding a new feature.
- fix is for fixing a bug.
- refactor is for changing code for performance or convenience purpose (e.g. readability).
- chore is for everything else (writing documentation, formatting, adding tests, cleaning useless code etc.).
---
# Konflikthantering i Git
## Konflikthantering
### Förebyggande:
- Jobba med den uppgift du ska göra. Ha disciplin.
- Inga egna initiativ. (Prata med varandra innan förändring, kolla med teamet först!)
### Identifiering:

### Lösning:

### Lärande:
Diskutera hur ni kan lära av konflikter för att förbättra era arbetsprocesser i framtiden. (Frivillig)
---
# Code Reviews
## Code Review
Code Review sker vid pull request innan varje merge.
- Code reviewaren granskar koden.
- Code reviewaren granskar den färdiga sajten på Netlify.
- (Code reviewaren trycker på merge.)
### För smidiga code reviews:
- Kommentera varje kodblock du skriver.
- Kommentar skrivs på raden OVANFÖR det kodblock som kommentaren gäller.
- Kommentarer skrivs på pro engelska.
Exempel på en funktion som innehåller ett if-statement innebär 2 kommentarer eftersom att det är två kodblock.
```javascript
// Kommentar som berättar vad funktionen ska åstadkomma
function myFunction() {
    // Kommentar som berättar vad if-statementet gör
    if (a < b) {
        console.log("hej");
    }
}
