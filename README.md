# kunskapskontroll 2 - Lisette Rönn
## Beskrivning av steg 1 och 2:
- Övningen inleds att genom att använda Terminalen i VS lokalisera dig bland mapparna på datorn med kortkommandot __pwd.__ Sedan lokalisera vart du vill lägga till en mapp genom korkommandot __ls__ och följa upp med cd "mappnamn".

- är man lokaliserat rätt i den nya mappen, så skapas din README.md fil genom __touch "README.md"__.

## Steg 3 Git och versionshantering
Börjar med att skapa en public repository inne på github. sedan skrevs commandon steg för steg i vs terminalen.
steg:
-  git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/ItisLiss/Kunskapskontroll-2.git
- git push -u origin main

För att nu spara och uppdatera README filen på Github användes förljande kommandon:
- __git status:__ Vilket visar om "branchen" är uppdaterad, sedan får man se exakt vad som inte är "Commitat" ändrats men inte sparat och ger tips på nästa kommando.
- __git add .__ Genom detta kommando väljer du att placera alla ändringar i väntande läge och punkten syftar till den aktuella mappen/dokumentet du arbetar i. 
- __git commit -m 'text'__ commit skapar som en historisk ändring i historiken av arbetet, själva -m 'text' delen är för att lämna en egen text, -m flaggar för meddelande och 'text' är text i form av förklaring eller ett meddelande i historiken.
- __git push__ Laddar upp själva det du sparade från commit kommandot (dina sparade ändringar) från din dator till tex Github.

