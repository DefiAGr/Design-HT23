---
Title: Bild
Description: This is our Laddningstid page.
Template: analyser
---

Bild rapport
=======================

Denna uppgiift handlar om att undersöka och utvärdera tre hemsidor. Vad vi vill kontrollera är deras bilder de använder och hur snabbt dessa bilder tar att ladda på de olika hemsidorna.

# Urval
-----------------------



Jag har valt följande 3 hemsidor:


- https://www.nintendo.se/: Detta är en hemsida kopplad till varumärket Nintendo som är ett japanskt företag som främst tillverkar spelkonsoler och TV-spel. 
- https://www.golfwang.com/: Det är en klädesplattform med fokus på amerikansk street-wear skapas av musikartisten Tyler the creator.
- https://oddfuture.com/: Det är en plattform för amerikansk street-wear med fokus på Odd future. Odd future är ett hiphop kollektiv och deras färger har fokus på rosa, gul och blå. 


Dessa hemsidor har valts med anledning av att de använder många typer av olika bilder i form av både stilla bild och rörande bilder och animationer.

Jag har alltså valt olika typer av hemsidor för att få en bättre inblick i hur olika aktörer använder sig avbilder för att framhäva olika känslor med sina bilder samtidigt som vi undersöker hur det påverkar prestandan.


# Metod
-----------------------
Målet med detta arbete är att undersöka olika hemsidors val av bild och laddningstider. Därför börjar vi med att besöka deras startsida och samlar oss en överblick.

Vi använder oss av ctrl + shift + r när vi uppdaterar sidan för att alltid ladda om utan cookies. På så sätt ser vi till att ingen bild sparas sedan tidigare och påverkar laddningstiden. 

Det verktyg vi använder oss av för att få fram en score på webbplatsen är med hjälp av Google Pagespeed. Vi ger den tre olika sidor per hemsida och sammanställer snittet för respektive. Det samma gäller med resterande data som vi samlar via devtools för respektive hemsida.

Därefter jämför vi datan och laddningstiderna och kommer fram till vilken hemsida som vinner i testet med bäst mätvärden.


# Resultat
-----------------------

Nedan presenteras de tre olika hemsidorna, med tre olika sidor. Det presenteras i både bild i form av en skärmdump i PNG format, inbäddad mätningsdata samt kommentar gällande laddningstiden. Mätvärdena gäller för dator och inom parantes finns datan för mobil.



# Nintendo

## Startsida:  
<img src="%assets_url%/img/nintendo.png" alt="Nintendo" width="800" height="400">

## Slumpad menyval: 

<img src="%assets_url%/img/nintendo2.png" alt="Nintendo" width="800" height="400">

## Artikelval: 

<img src="%assets_url%/img/nintendo3.png" alt="Nintendo" width="800" height="400">



## Mätningarna


<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQyqwiw3nDesOEl_qaQEhciKgKuRjfGLugAW4S6vGJO_Yx1NaWC2Cn1oZ6HjmkSfhvVI0IvW-cZEdGZ/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" style="width:70%; height:200px;" ></iframe>

Nintendos hemsida använder sig främst av många bilder som framhäver de olika spel de har tillgängligt. Laddningstiden är helt okej med tanke på alla resurser som laddas in.

-----------------------
# Golf Wang 


## Startsida: 

<img src="%assets_url%/img/golf.png" alt="Golf Wang" width="800" height="400">

## Slumpad menyval:

<img src="%assets_url%/img/golf2.png" alt="Golf Wang" width="800" height="400">

## Artikelval: 

<img src="%assets_url%/img/golf3.png" alt="Golf Wang" width="800" height="400">

  

## Mätningarna

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQyqwiw3nDesOEl_qaQEhciKgKuRjfGLugAW4S6vGJO_Yx1NaWC2Cn1oZ6HjmkSfhvVI0IvW-cZEdGZ/pubhtml?gid=1091986551&amp;single=true&amp;widget=true&amp;headers=false" style="width:64%; height:200px;" ></iframe>

Golf Wang är nog den hemsida som har längst laddningstid och sämst mätvärden. Den kan bero bland annat på storleken på de olika bildernas storlek men även på antalet resurser som laddas in. 

-----------------------
# Odd Future

  

## Startsida: 
<img src="%assets_url%/img/oddfuture.png" alt="Hemnet" width="800" height="400">

## Slumpad menyval:

<img src="%assets_url%/img/oddfuture2.png" alt="Hemnet" width="800" height="400">

## Artikelval: 

<img src="%assets_url%/img/oddfuture3.png" alt="Hemnet" width="800" height="400">



   
## Mätningarna

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQyqwiw3nDesOEl_qaQEhciKgKuRjfGLugAW4S6vGJO_Yx1NaWC2Cn1oZ6HjmkSfhvVI0IvW-cZEdGZ/pubhtml?gid=758385823&amp;single=true&amp;widget=true&amp;headers=false" style="width:66%; height:200px;"></iframe>

Odd future sticker ut med väldigt stor variation mellan mobila och dator mätvärdena. 
   
-----------------------
#  Analys
-----------------------

Vad man kan utläsa är att Nintendo har väldigt mycket resurser och storlek på sin startsida som men som ändå har en hyfsad laddningstid jämfört med Odd future som har färre resurser men liknande laddningstid. Golf Wang är skapad för att synas på dator och även där tar det väldigt lång tid för laddningstid, främst för mängden och storleken på bilderna de laddar upp. 

Utseendemässigt är det en annan diskussion hur bilderna används och hur man laddar in färre resurser beronde på om det är mobil eller dator. Här sticker det tydligare ut att Nintendo försöker optimera då en stor del försvinner vid mobil vyn. Detta är något som även sker på de övriga men inte alls i lika stor utsträckning. Golf Wang minskar inte antalet resurser särskilt mycket även när man går över till mobil vyn. Vilket blir tydligt av mätvärdena. 


Enligt statistiken och laddningstiden så är vinnaren Nintendo med den bästa hemsidan sett till helheten även om Odd futures hemsida har bättre prestanda i Desktop vy. Andra platsen går till Odd future som är väldigt nära och som har högre snitt på desktop vy men som inte är lika anpassad. Tredje platsen går till Golf wang som har längst laddningstider och flest resurser och sämst prestanda på både mobil och desktop. 


-----------------------
### Författaren till denna analys är David Benson

