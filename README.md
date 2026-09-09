# Min webbplats
Denna webbplatsen handlar om mig, min hobby skidåkning och hur du kan ta kontakt med mig.

## Tekniker
Denna hemsidan är enbart byggt med HTML.

## Länkar
Jag har sidan på två ställen:
[GitHub](https://kajsut.github.io/dt225g_kajsa_widen/) ,
[Netlify](https://cheery-melomakarona-6549e3.netlify.app/)

## Q&A
Här kommer svar på fem stycken frågor:
1. **Vad är skillnaden mellan git add och git commit?**  
 Git add lägger till de ändrade filerna i _Staging Area_, det är där ifrån som man sedan gör git commit.  
 När man gör git commit så gör man en ny version av filen i sitt lokala repo.  
 En commit har också ett unikt ID, med hjälp av den kan man se skillnaden mellan de olika commiterna.

2. **Varför använder man branches istället för att jobba direkt i main?**  
  En branch blir helt separat från huvudkoden, det är bra för att:
  * Man kan skriva och hålla på med projektet parallellt med andra utan att det ska störa varandra.
  * Man kan testa funktionerna och validera dom utan att något kan drabbas i main.

3. **Vad händer rent praktiskt när man gör en merge?**  
 Man slår ihop en branch med mainen, och sammanslagningen blir den nya mainen. Detta sker på ett struktuerad och säkert sätt.

4. **Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?**  
 Github hanterar och förvarar versionerna och jag kan uppdatera dom där, medans Netlify enbart publicerar de sidorna som jag skickar till den.

5. **Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?**  
 Då skriver man _.gitignore_, eller om man är inne på VS Code så högertycker man på filen och sedan på _add to .gitignore_.  
 Detta kan vara bra att använda för t.ex. tillfälliga filer som loggar, stora NPM-paketsmappar som man enkelt kan återinstalleras och känsliga filer.  
 