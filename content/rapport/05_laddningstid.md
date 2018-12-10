---
---
Laddningstid
=========================

Ett antal webbplatser analyseras och testas utifrån hur snabbt de laddas samt om de innehåller saker som kan förbättras utifrån snabbare laddningstid och användarbarhet.


Urval
-----------------------

Denna rapport kommer att analysera tre stycken webbplatser, wikipedia.org, aftonbladet.se samt blizzard.com.
Urvalet baseras på sidor vi själv frekvent använder och som förhoppningsvis ger så pass olika resultat att en jämförande analys kan utföras.

Metod
-----------------------

Analysen stöder sig på Googles PageSpeed Insights (https://developers.google.com/speed/pagespeed/insights/) samt Google Chromes dev tools. Med hjälp av dessa kommer parametrar som sidans laddningstid, storlek och antal laddade resurser jämföras tillsammans med första meningsfulla skärmuppritningen, innehållsrenderingen och hastighetsindex.

Resultat
-----------------------
För varje webbplats, har vi gjort följande:

Tagit en snapshot (bild) på webbplatsen.
Valt ut tre sidor (bifoga länkarna) som mäts med Google Pagespeed, både på Mobile och Desktop.
För varje sida, mätt med devtools flik networks och noterat sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. Varje sida har mätts tre gånger, varefter ett snittvärde presenterats.

Den Score som presenteras i bilderna nedanför hänvisar till en total beräkning av tre variabler vi ämnar att analysera. Det pekar på den första meningsfulla skärmuppritningen, innehållsrenderingen och hastighetsindex som varje sida har. Under varje resultat som vi presenterar kommer vi att redovisa för Dev Tools och Insights score för varje sida.


<h3>Wikipedia.org</h3>


<h6>Snapshot:</h6>

[FIGURE src="img/wikipedia.png"]

<h6>Desktop:</h6>

[FIGURE src="img/wikipediadesktop.png"]

<h6>Mobile:</h6>

[FIGURE src="img/wikipediamobile.png"]


<h6>Dev tools & PageSpeed Insights:</h6>


<h6>Wikipedia.com (i snitt):</h6>

Laddningstid: 0,3 sek.
<br>
Antal resurser: 3 st.
<br>
Total storlek: 560kb.
<br><br>
PageSpeed Insights Score Mobil/Desktop: 98/100

<h6>https://sv.wikipedia.org/wiki/Barack_Obama (i snitt):</h6>

Laddningstid: 5 sek.
<br>
Antal resurser: 51 st.
<br>
Total storlek: 560kb.
<br><br>
PageSpeed Insights Score Mobil/Desktop: 79/100

<h6>https://sv.wikipedia.org/wiki/Madonna_(artist) (i snitt):</h6>

Laddningstid: 0,63 sek.
<br>
Antal resurser: 34 st.
<br>
Total storlek: 119kb.
<br><br>
PageSpeed Insights Score Mobil/Desktop: 89/100

<h6>Förbättringsförslag</h6>
Wikipedias möjligheter för att förbättra snabbheten på webbplatsen innebär en rensning av resurser som blockerar renderingen av sidan. När användaren dirigeras till Wikipedias sida kan inläsning av mindre viktig kod läsas in vid ett senare tillfälle. Detta gäller endast mobilversionen, Insight föreslår inga möjligheter till förbättring på desktop sidan. Wikpedias desktop version fick 9.8 sekunder i score och mobilvarianten fick 20.2 sekunder enligt de resultat vi har utarbetat.


<h3>Aftonbladet.se</h3>

<h6>Snapshot:</h6>

[FIGURE src="img/aftonbladet.png"]

<h6>Desktop:</h6>

[FIGURE src="img/aftonbladetdesktop.png"]



<h6>Mobile:</h6>

[FIGURE src="img/aftonbladetmobile.png"]



<h6>Dev tools & PageSpeed Insights:</h6>

<h6>aftonbladet.se (i snitt):</h6>

Laddningstid: 6,77 sek.
<br>
Antal resurser: 180 st.
<br>
Total storlek: 3140 kb.
<br><br>
PageSpeed Insights Score: 37/96

<h6>https://www.aftonbladet.se/sportbladet (i snitt):</h6>

Laddningstid: 7,37 sek.
<br>
Antal resurser: 134 st.
<br>
Total storlek: 3930 kb.
<br><br>
PageSpeed Insights Score Mobil/Desktop: 52/98

<h6>https://tv.aftonbladet.se/abtv/ (i snitt):</h6>

Laddningstid: 1,3 sek.
<br>
Antal resurser: 64 st.
<br>
Total storlek: 4590 kb.
<br><br>
PageSpeed Insights Score Mobil/Desktop: 72/100

<h6>Förbättringsförslag</h6>
Aftonbladets möjligheter till förbättringar när det gäller på desktop syftar på att ta bort resurser som blockerar renderingen av sidan. Mobilapplikationen menar också på att detta behövs göras. Den anser också att alla bilder som ligger utanför skärmen och dolda bilder bör läsas in senare, och inte direkt för att öka hastigheten på sidan. Mobilvarianten har också CSS element som inte används och därav vill Insights ta bort regler som inte används. Utifrån det resultat ovan, går det att utläsa en score av 9.4 sekunder för desktop och 28,5 sekunder för mobilapplikationen, det är stor skillnad i prestanda och hur lång tid det tar för att ladda in båda versionerna av sidan.


<h3>Blizzard.com</h3>

<h6>Snapshot:</h6>
[FIGURE src="img/blizzard.png"]


<h6>Desktop</h6>

[FIGURE src="img/blizzarddesktop.png"]


<h6>Mobile:</h6>

[FIGURE src="img/blizzardmobile.png"]


<h6>Dev tools & PageSpeed Insights:</h6>

<h6>blizzard.com (i snitt):</h6>

Laddningstid: 10,3 sek.
<br>
Antal resurser: 143 st.
<br>
Total storlek: 10,066kb.
<br><br>
PageSpeed Insights Score Mobil/Desktop: 10/79

<h6>https://news.blizzard.com/en-us (i snitt):</h6>

Laddningstid: 4,36 sek.
<br>
Antal resurser: 143 st.
<br>
Total storlek: 12,400 kb.
<br><br>
PageSpeed Insights Score Mobil/Desktop: 22/99

<h6>https://eu.shop.battle.net/en-gb (i snitt):</h6>

Laddningstid: 6,04 sek.
<br>
Antal resurser: 133 st.
<br>
Total storlek: 11,200kb.
<br><br>
PageSpeed Insights Score Mobil/Desktop: 1/55

<h6>Förbättringsförslag</h6>
Blizzards möjligheter till förbättringar innehåller mycket fler förslag enligt Insight. Den hänvisar till att bilder inte kodas effektivt, inte befinner sig i modernt bildformat och i fel storlek. Den menar också på att sidan bör undvika omdirigeringar, skjuta upp CSS och ta bort onödiga resurser som inte behövs vid inladdning av sidan. Detta gäller även för mobila versionen, men där är effekten av dessa förbättringar mycket tyngre och påverkar prestandan enormt enligt de resultat som vi har framställt. Desktop versionen fick ett resultat på 27.2 sekunder i Score och deras mobilversion 106.9 sekunder i Score.

Sammanställning
-----------------------

I figurerna ovan presenteras webbsidornas resultat när det gäller antalet sekunder för att ladda in varje sida och deras variabler. Weight står för antal sekunder. De variabler som mäts är Första uppritningen av innehåll, Första meningsfulla skärmuppritningen och Hastighetsindex.

När det gäller Dev Tools Total Score och vår egna undersökning hänvisar lägre score till bättre laddningstid och när det gäller PageSpeed Insights resultat går vi på hur högt resultatet är mellan 1-100.

De gränser vi har satt upp för varje resultatfaktor när det gäller absolut laddningstid syftar på:
<br><br>
Vår egen undersökning - Mobile/Desktop: 20s/50s
<br>
Dev Tools Total Score: 10s
<br>
PageSpeed Insights Median Mobile/Desktop: 75s/90s

För vår egen undersökning och Dev Tools score har vi summerat upp varje sidas totala inladdningstid med varandra för att få totala scoren. För PageSpeed Insights har medelvärdet beräknats utifrån de olika webbplatsernas tre sidor för att få ett ungefärligt resultat.
<h6>Wikipedia</h6>
Vår egen undersökning -  Wikipedia Mobile/Desktop: 9.8s/20.2s Score <br> Dev Tools Total Score: 5.93s <br> PageSpeed Insights Median -  Mobile: 88.66s Desktop: 100
<br>
<h6>Aftonbladet</h6>
Vår egen undersökning -  Aftonbladet Mobile/Desktop: 9.4s/28.5s Score <br> Dev Tools Total Score: 15,44s <br> PageSpeed Insights Median - Mobile: 53.66 Desktop: 98
<br>
<h6>Blizzard</h6>
Vår egen undersökning -  Blizzard Mobil/Desktop: 27.2s/106.9s Score <br> Dev Tools Total Score: 20,7s <br> PageSpeed Insights Median -  Mobile: 11 Desktop: 77.66

Analys
-----------------------

Analysen kommer att utgå ifrån de gränser som presenteras i sammanställning.

Alla sidor har mycket gemensamt när det gäller förbättringsförslag. De resultat som har framställts tyder på förbättringar i hur resurser laddas in på sidan samt hur bildhanteringen ser ut. Insight ser gärna att onödiga resurser som inte behövs för sidans inladdningsprocess bör sållas bort. Mobilversionen av de olika webbsidorna påvisar en markant prestandaförlust i inladdningen av bilderna på grund av fel bildstorlekar och att det finns onödiga inläsningar av bilder som är dolda eller inte visas direkt vid inladdning.

För att konkretisera och precisera våra resultat kommer sammanställningen beskrivas mer detaljerat:

För vår egna undersökning ser vi en tydlig utveckling för varje sida, där vi ser att Wikipedia har mest fördelaktiga resultatet med en låg score på 9.8s i laddningstid för Desktop och 20.2s i laddningstid för mobil, medan Blizzard exempelvis har 27.2s i laddningstid för desktop och 106.9s i laddningstid för mobil. Det är en signifikant skillnad i hastigheten. Aftonbladet hamnar mittimellan de båda sidorna, med en desktop score på 9.4s och mobil score på 28.5s.

Det går också att utläsa att Dev Tools totala score stödjer idén om att Wikipedia är snabbast med en låg score på 5.93s i jämförelse med Blizzards höga score på 20.7s, Aftonbladet hamnar här på en total score av 15.44s vilket inte är under gränsen för vad vi anser är snabbt.

I PageSpeed Insights score, ser vi också att Wikipedia vinner i laddningstid och hastighet med en stabil score på 88.66 för mobil och 100 för desktop. Aftonbladet hamnar på 53.66 på mobil och 98 på desktop vilket tyder på att deras desktopversion är bra optimerad. Blizzard får 11 i score för mobilen och 77.66 för desktop. Det är en sida med mycket innehåll vilket därför leder till lägre hastighet.

Således vinner Wikipedia undersökningen, utifrån de tre olika testresultaten från vår egna undersökning, Dev Tools och PageSpeed Insights score.

Vi ber dock läsaren att ta hänsyn till webbplatserna olika syften. Wikipedia har förmodligen bättre hastighet och inladdningstid på grund av dess innehåll som mestadels består av text, medan Blizzard och Aftonbladet använder bilder, live-bilder, videoklipp och animationer. Detta ser naturligtvis till att sidan kräver mer. Vi menar på att det är en orättvis jämförelse i relation till vad sidorna har som uppgift att göra för deras användare.

Referenser
-----------------------

Wikipedia.com
<br>
Blizzard.com
<br>
Aftonbladet.se
<br>
https://developers.google.com/speed/pagespeed/insights/

Övrigt
-----------------------

Ludwig Hermansson
Mikael Bratt Wallgren
