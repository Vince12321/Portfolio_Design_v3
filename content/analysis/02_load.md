---
Title: 02_load
Description: 02-load
Template: analysis_one
---

# Kmom05 Laddningstid
<br>
I den här uppgiften ska tre webbsidor analyseras vad gäller hur snabbt de laddas och något kan förbättra laddningstiden.<br><br>

Urval
-----------------------

Jag valde Dagens Nyheter, Moderna Muséet i Stockholm och SJ:s webbplatser.
Dagens Nyheter har mycket content och bilder, Moderna Muséet har mycket bilder som är högupplösta och SJ har lite mindre content och bilder.<br><br>

Metod
-----------------------

Mätningarna görs med Google Pagespeed och devtools nätverksflik.<br><br>

Resultat
-----------------------
<b>Mätningsdata: </b><br>

https://docs.google.com/spreadsheets/d/e/2PACX-1vRA5MLeQJ-iscvci4VQunubTZ9hmADrZ5x-rXigIVZv2pOvEJyzb9Fhp3FhoDN2yUe6NzjOAlctG8GI/pubhtml
<br><br>
<b>Dagens Nyheter:</b>

<a href="%base_url%/image/DN.PNG" target="_self">
    <picture>
        <source media="(min-width: 460px)" srcset="%base_url%/image/DN.PNG&w=770&q=50">
        <img src="%base_url%/image/DN.PNG&w=460&q=50" alt="Dagens Nyheter">
    </picture>
</a>

Den här webbplatsen har mycket reklam som nog tar en del tid men om man inspekterar artikelbilderna så kan man se att de är responsiva, dvs att olika storlekar av bilderna laddas beroende på webbläsarens storlek. Kvalitén på bilderna är 60% vilket fortfarande ser bra ut.
<br><br><br>

<b>Moderna Muséet i Stockholm</b>

<a href="%base_url%/image/moderna_museet.PNG" target="_self">
    <picture>
        <source media="(min-width: 460px)" srcset="%base_url%/image/moderna_museet.PNG&w=770&q=50">
        <img src="%base_url%/image/moderna_museet.PNG&w=787" alt="Moderna Muséet i Stockholm&w=460&q=50">
    </picture>
</a>

På den här webbplatsen är bilderna responsiva och bilderna ser bra ut i alla storlekar på webbläsaren vilket är viktigt då det är konstverk som visas. Kvalitén är nog ingen bra idé att dra ner på heller. Man kanske kan ändra bildformat från .jpg till något annat för att få ner laddningstiden?
<br><br>

<b>SJ:</b>

<a href="%base_url%/image/c.PNG" target="_self">
    <picture>
        <source media="(min-width: 460px)" srcset="%base_url%/image/SJ.PNG&w=770&q=50">
        <img src="%base_url%/image/SJ.PNG&w=787" alt="SJ&w=460&q=50">
    </picture>
</a>

Den här webbplatsen tar lite längre tid att ladda än de andra, hela sidan verkar laddas direkt till skillnad mot t ex Dagens Nyheter där sidan laddas när man scrollar ner.
Bakgrundsbilden verkar finnas i olika storlekar så det är ju bra.

<br><br>

Analys
-----------------------

Alla tre webbplatser jag undersökte använder responsiva bilder. Dagens Nyheter hade dragit ner kvalitén till 60% på bilderna på startsidan vilket nog är bra då det finns mycket innehåll där. SJ:s Webbplats hade nästan dubbel så lång laddningstid och runt tre gånger så mycket att ladda jämfört med de andra. Jag tror det beror på att hela sidorna på SJ:s webbplats laddas direkt och de andra laddar bara det man ser på skärmen och laddar sedan resten när man scrollar ner.

Jag vet inte om det finns så mycket att förbättra när det gäller bildhanteringen på webbplatserna då alla tre anpassar bilderna efter storleken på webbläsaren. Kanske går det att hitta ett effektivare format på bilderna eller dra ner ännu mer på kvalitén.

Överlag så var SJ:s webbplats sämst med dubbel laddningstid och hälften så höga poäng. Framsidan hade dessutom en ganska lågupplöst bakgrundbild. Det var väldigt jämt mellan Dagens Nyheter och Moderna Muséet. Dagens Nyheter hade högre mobilt poäng och Moderna Muséet hade högre desktop-poäng. Det som avgjorde att Dagens Nyheter vann var laddningstiden som i snitt var 100ms snabbare. Om man ska dra en gräns för om en sida laddar snabbt eller långsamt så tycker jag den går vid 1 sekunds laddningstid.






<br><br>

<p class="name-sign"><b>Vincent Wistrand<b></p>
