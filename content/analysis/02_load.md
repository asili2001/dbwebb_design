---
Title: Analysis
Description: This is my report page.
Template: analysis
---
Titel på rapporten
=====================
En utvärdering av webbplatsers laddningstid och användbarhet. 

Urval 
=====================

För detta kursmoment valde jag tre av de mest sökta nyhets webbplatser i Sverige. Den första är dn.se som är en nyhetsorganisation som är oberoende, står fri från partier, organisationer och ekonomiska maktsfärer.<br>
dn.se och Dagens Nyheters papperstidning läses av omkring 1,3 miljoner människor och är landets största annonsmedium på tidningssidan.<br><br>

Den andra webbplatsen är aftonbladet.se som är ett nyhets webbplats grundad den 6 december 1830 av Lars Hierta.<br>
Aftonbladets vision är att vara Sveriges mest engagerande nyhetskälla som värnar sanningen, granskar makten och ger dig inflytande genom journalistik. <br><br>

Den tredje webbplatsen är newsworthy.se som är ett nyhets webbplats som gör lokal journalistik av data. <br>
Deras mission är att förstå, förklara och granska samhället med hjälp av data. <br><br>

Metod 
=====================

Jag börjar med att söka och dokumentera ner webbplatsen samt webbplatsens syfte i en Word dokument.<br>
Mäter webbplatsens laddningshastighet samt kollar hur man kan förbättra resultatet med hjälp av pagespeed.web.dev, ett perfekt verktyg för att kolla webbplatsens prestanda samt CLS av Google. <br><br>

CLS (Cumulative Layout Shift) är ett formulär som Google använder för att räkna ut antal saker som flyttar på sig efter webbplatsen laddar.<br>
Att knappar och andra saker flyttar på sig är dålig användarupplevelse och sådana finns överallt som gjorde att Google hittar lösning för detta problem med CLS.<br>
CLS resultat påverkar webbplatsens rank på SEO och mycket mer över hela webben. <br><br>

![Exempel CLS](%base_url%/image/cls.gif)


<style type='text/css'>
    img { height: 200px }
</style>


Resultat 
=====================

Dn.se
-----------

![dn.se home page](%base_url%/image/dn.se.jpg?h=300)
![dn.se PageSpeed Insights](%base_url%/image/dn.se.pagespeed.jpg?h=300)

Dn.se har en ganska dålig prestandascore enligt Googles pagespeed verktyget.<br>
Den har 62 till 64 av 100. Man kan höja upp resultatet genom att minska oanvända JavaScript.<br>
Enligt pagespeed så finns det totalt 5 oanvända JavaScript filer. Detta påverkar laddningstiden samt bredbandet.<br>

För att förbättra resultaten ännu bättre så kan de ha en sorts lazy loading till bilderna som laddas. <br>
Detta hjälper med att sidan inte väntar på bilderna tills de laddar klar utan att ladda utan att vänta på bilderna. <br>

Dn.se använder .png format på vissa bilder. .png brukar vara jättestora samt att de inte är det bästa på webben.<br>
Det är bra att använda .jpg och ännu bättre att använda .webp format. Detta hjälper mycket med laddningstiden. <br>

DN:s tillgänglighetsscore ligger på 83 av 100. Detta kan förbättras genom att ha [alt] attribut på deras img taggar som förklarar vad bilden handlar om.<br>
Detta hjälper bland annat screen readers samt om bilderna inte laddas. Annars följer dn.se de generella rekommendationerna för sökmotoroptimering och tillgänglighet. <br><br>

Expressen.se 
-----------

![Expressen.se home page](%base_url%/image/expressen.se.jpg?h=300)
![Expressen.se PageSpeed Insights](%base_url%/image/expressen.se.pagespeed.jpg?h=300)


Expressens prestanda är ganska dålig enligt Googles pagespeed verktyget.<br>
Den ligger på 55 till 59 av 100. Man kan förbättra resultatet genom att förminska(minify) JavaScript filerna för en mindre fil och script parse tid. <br>
Annars följer expressen.se de generella rekommendationerna för sökmotoroptimering och tillgänglighet. <br><br>

Newsworthy.se 
-----------

![Newsworthy.se home page](%base_url%/image/newsworthy.se.jpg?h=300)
![Newsworthy.se PageSpeed Insights](%base_url%/image/newsworthy.pagespeed.jpg?h=300)


Enligt Googles pagespeed verktyget så har Newsworthy.se ganska dålig prestandascore.<br>
Den ligger på 55 av 100. Man kan förbättra resultatet genom att minska oanvända JavaScript filer.<br>
Enligt pagespeed verktyget så finns det en fil på 76KiB som inte används. <br><br>

Newsworthy.se använder HTTP/1 istället för HTTP/2. <br>
Skillnaden mellan http/2 och http/1 är att http/1 skickar en enda request i en TCP anslutning. <br>
Vill man ha tillexempel index.html och main.css så blir det två requests till servern.<br>
 http/2 skickar flera requests i en TCP anslutning och Komprimerar requestet samt responsen mellan servern och klienten. <br>
 Det är jätteviktigt att använda http/2 för snabbare laddning och mindre användning av bredbandet. <br><br>

Newsworthy.se använder .png bildformat på vissa bilder. .png brukar vara jättestora samt att de inte är det bästa på webben.<br>
Det är bra att använda .jpg och ännu bättre att använda .webp format. Detta hjälper mycket med laddningstiden. <br><br>

<iframe src="%base_url%/sheets/load/index.html" height= "400" width= "100%"></iframe>

Analys 
=====================

Eftersom jag valde 3 sajter med samma kategori så kan jag märka till att alla tre sajter har problem med prestandascore som beror på inkludering av oanvända JavaScript som i sin tur förminskar prestandan på sajten.<br>
De följer inte heller tillgängligheten 100%. <br><br>

Referenser 
=====================

Pagespeed by google : [www.pagespeed.web.dev](www.pagespeed.web.dev)<br>
Dn.se : [www.dn.se ](www.Dn.se )<br>
Expressen : [www.expressen.se](www.expressen.se)<br>
Newworthy : [Newworthy.se](Newworthy.se )<br>
Page Experience, UX and Accessibility: Get Ready for Google’s 2021 Update : [medium.com](https://medium.com/swlh/page-experience-ux-and-accessibility-get-ready-for-googles-2021-update-4ba70f10caac)


Övrigt 
=====================

Författare: Ahmad Asili 

 