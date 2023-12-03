---
Title: Load
Description: En analys av laddningstider och användbarhet.
Template: analysis
---

Utvärdering av webbplatsers laddningstid och användbarhet
=======================

Vi tittar på ett begränsat antal webbplatser och analyserar deras prestanda. Genom att undersöka webbplatsernas resurser och laddningstider får vi förhoppningsvis en uppfattning om prestanda och användbarhet.

Urval
-----------------------

Denna utvärdering är baserad på tre webbplatser som representerar olika svenska vissångare. Webbplatserna är tre utvalda artister från Wikipedias lista över svenska vissångare. 

<a href="https://sv.wikipedia.org/wiki/Kategori:Svenska_viss%C3%A5ngare">vissångare Wikipedia</a>
<br>

Metod
-----------------------

I den här rapporten har två olika metoder används. Dels har webbplatserna analyserats med hjälp av googles verktyg, PageSpeed Insights. Där har prestandan betygsats på en skala mellan noll och hundra där hundra är bästa resultat. Resultatet ger även olika svar beroende på skärmstorlek som hjälper att hitta avikelser i responsiviteten. Webbplatserna har även undersökts med hjälp av firefox devtools och då tittat på laddnings tider, antal resurser och sidans storlek.

Resultat
-----------------------

###Melissa Horn webbplats

![Melissa Horn](%assets_url%/img/mh.png) {.analysis-pic}
<br>

<iframe title="myMmFrame" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTYUh0pwro0bH_l5pOLrOphWRCoemBYHcQA6c-XWuc519xVY-tvdrclLGPGZk4nSh-G1aBBOJNp5nPT/pubhtml?gid=0&amp;single=true&amp;widget=false&amp;headers=false"></iframe>

Denna webbplats verkar ha ganska bra prestanda och laddningstider. Det som ser ut att kunna förbättras skulle kunna vara prestandan på mobila enheter som får lite sämre resultat.

<br>
###Stefan Sundström webbplats

![Stefan Sundström](%assets_url%/img/ss.png) {.analysis-pic}
<br>

<iframe title="mySsFrame" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTYUh0pwro0bH_l5pOLrOphWRCoemBYHcQA6c-XWuc519xVY-tvdrclLGPGZk4nSh-G1aBBOJNp5nPT/pubhtml?gid=167733070&amp;single=true&amp;widget=false&amp;headers=false"></iframe>

Här ser vi att sidan med videos sticker ut och har betydligt längre laddnings tid och även sämre resultat från PageSpeed Insights.

<br>
###Laleh webbplats

![Laleh](%assets_url%/img/la.png) {.analysis-pic}
<br>

<iframe title="myHhFrame" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTYUh0pwro0bH_l5pOLrOphWRCoemBYHcQA6c-XWuc519xVY-tvdrclLGPGZk4nSh-G1aBBOJNp5nPT/pubhtml?gid=371375144&amp;single=true&amp;widget=false&amp;headers=false"></iframe>

Den här webbplatsen sticker ut av urvalet med både långa laddnings tider och något sämre resultat från PageSpeed Insights vilket indikerar att det kan finnas flera olika åtgärder som behövs göras.

Analys
-----------------------

Det första som slår mej här är att Lalehs webbplats sticker ut på flera sätt. Den har både längre laddningstider, flera resurser, större total storlek och även sämre resultat från PageSpeed Insights. Men när du tittar på sidan har den kanske oxå mera mordern och mer avancerad design än övriga. Ett exempel på den mordernare designen kan vara att index sidan har ett bildspel som bakgrund medans övriga har enklare enfärgad bakgrund.

Melissa horns webbplats är till exempel mycket enklare med enfärgad ljus bakgrund, text och enstaka bilder vilket kan tänkas ge kortare laddningstider och bättre prestanda i tester. Men när man tittar närmare och jämför Melissa Horns sida /musik och Lalehs index sida ser vi att dom har 184 respektive 174 resurser och samtidigt laddningstiderna 1.98s respektive 9.23s. Då drar jag ändå slutsatsen att optimeringen av resurserna spelar en ganska stor roll. Med optimering tänker jag på exempelvis bilders format, storlek och komprimering. I jämförelsen kan det även va intressant att titta på storleken på sidan som även den skiljer ganska mycket.

En slutsats man kan tänka sig här är att storleken på webbplatsen verkar påverka laddningstiden mera än antalet resurser vilket ju också pekar mot att optimeringen av resurserna är viktig att tänka på för ökad prestanda.

Efter dessa resultat skulle jag rangordna webbplatserna med Melissa Horn som bästa prestandan, Stefan Sundström i mitten och Lalehs som sist. 

Med resultaten från den här rapporten skulle jag säga att en laddningstid under 2s är en snabb laddningstid och en tid över 4-5s är långsam. Jag upplever skillnad när jag tittar på dom olika sidorna där Melissa Horns och Stefan Sundströms sida känns likvärdigt snabba och användarvänliga medans Laleh är märkbart långsammare. 

Övrigt
-----------------------

Kristoffer Berg

<a href="%base_url%?analysis">tillbaka</a>