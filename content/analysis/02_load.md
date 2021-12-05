---
Title: 02 Load
Description: Load
Template: analysis-article
---

Laddningstid för tre olika butikskedjors webbplatser
=======================

Laddningstiden för tre olika webbplatser mäts för att avgöra hur användarvänliga de är, och det undersöks ifall om de kan förändra något för att förbättra sin laddningstid.

Urval
-----------------------

Urvalet består av webbplatserna för Åhlens, Clas Ohlson och IKEA. De valdes för att de är stora butiker som många besöker, samt har många varor i sina utbud. För varje webbplats valdes sedan tre undersidor ut slumpmässigt, se sidorna som valdes under "Referenser".

Metod
-----------------------

Hastigheten för varje webbsida avgörs genom användning av Googles webbplats "PageSpeed Insights", i vilken man fyller i en webbadress och får data över hur webbsidan presterar i form av bl a tid till att sidan är interaktiv, ett värde på "speed index" och ett prestandavärde. Detta görs för både Mobile och Desktop för de tre webbplatserna och betygen noteras i ett Excel-dokument.

För varje webbsida noteras även sidornas laddningstid, och även hur många resurser och mycket data som laddas ner, genom att använda nätverksfliken i webbläsarens utvecklingsverktyg. Notera att kortkommandot Ctrl+Shift+R används för mätningarna, detta för att sidan ska laddas in i sin helhet, utan att använda cachade filer. Tre mätningar görs med hjälp av utvecklingsverktyget, och ett medelvärde av dessa mätningar beräknas. Datan dokumenteras i Excel-dokumentet. Det tas även screenshots av de olika webbplatserna.


Resultat
-----------------------

Nedanstående bild visar screenshots av de tre webbplatserna och i tabellen under återfinns mätvärdena från de olika mätningarna.

<picture class = "pages-load">
    <img class = "page-load" src = "%assets_url%/img/analysis/load/ahlens.JPG">
    <img class = "page-load" src = "%assets_url%/img/analysis/load/ikea.JPG">
    <img class = "page-load" src = "%assets_url%/img/analysis/load/clasohlson.JPG">
</picture>

<!-- <a href = "https://docs.google.com/spreadsheets/d/e/2PACX-1vSrVdTWF9UdbNQcTR_LFyjO9y0wclPbU7hRhvA4JjbeXWFx-YrC25OmoEBUk1CXdEoHqLBSpEh1OoqV/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"> -->
<!-- <picture class = "measurements"> -->
<div class = "measurements table-box">
    <iframe class = "measurements" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSrVdTWF9UdbNQcTR_LFyjO9y0wclPbU7hRhvA4JjbeXWFx-YrC25OmoEBUk1CXdEoHqLBSpEh1OoqV/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false">
    </iframe>
</div>

När det gäller Åhléns har de tre undersidorna en laddningstid på i snitt 3,98s/ 6,3MB. Det mesta som skickas är JavaScript, sedan bilder.

IKEA har ett snitt på 5,04s/ 8,2 MB för de tre undersidorna. De skickar också mycket JavaScript, men bilderna tar väldigt liten plats. 

Clas Ohlson har ett snitt på 2,43s/ 8,5MB för de tre undersidorna. De skickar en mindre andel JavaScript jämfört med de två ovanstående webbplatserna. Ungefär hälften av den data som skickas är bilder. 

Tydligt för alla tre webbplatserna är att de mobila varianterna presterar betydligt sämre.

Analys
-----------------------

Åhléns skulle kunna ha nytta av att se över ifall all JavaScript verkligen används, och behövs, och även se om de kan miska på bilderna storlek. IKEA skulle liksom Åhléns kunna ha nytta av att se över sin JavaScript. Clas Ohlson bör till skillnad från de två ovanstående webbplatserna inte fokusera lika mycket på att minska mängden JavaScript, utan mer på att minska bildernas storlek.

Något dessa webbplatser generellt skulle kunna tänka på är alltså att se över mängden JavaScript, och även vara noga med att skicka bilder i rätt storlek och format, eftersom dessa delar tar störst plats.

Av webbplatserna anser jag att Clas Ohlson är en vinnare i och med att webbplatsen är stor, men ändå har en kort laddningstid. Det är mer jämnt mellan de andra- och tredjeplatsen, men jag skulle ändå utse Åhléns till andra plats, främst pga laddningstiden. Även om IKEAs sida är större så är det viktigt för en användare att det inte tar för lång tid att ladda in sidorna.

Jag själv anser att gränsen för om en webbplats känns snabb eller långsam går vid runt 3s. Jag tycker inte det behöver gå fortare än kanske en sekund, för det tar en stund för mig att ställa in mig på vad jag ska titta på efter att jag skrivit in adressen och tryckt på Enter, jag vill hinna med att uppfatta att sidan laddas in, men om det tar mer än några sekunder sitter man bara och väntar.

Jag tycker webbplatserna klarade sig lite sämre än jag trott. Jag har som användare inte tänkt på att någon av dessa skulle vara särskilt långsam att ladda in, men det är ju också en subtil känsla som bidrar till ett allmänt intryck av sidan. Jag lägger främst märke till när någon sida är alldeles för långsam.

Referenser
-----------------------

Addresser till de använda webbsidorna återfinns nedan:<br />

PageSpeed Insights: http://www.pagespeed.web.dev

- Åhléns:
    1. https://www.ahlens.se/
    2. https://www.ahlens.se/Inredning
    3. https://www.ahlens.se/Mode
<br /><br />
- IKEA:
    1. https://www.ikea.com/se/sv/
    2. https://www.ikea.com/se/sv/rooms/bedroom/
    3. https://www.ikea.com/se/sv/cat/foervaring-st001/
<br /><br />
- Clas Ohlson:
    1. https://www.clasohlson.se/
    2. https://www.clasohlson.com/se/Hem/F%C3%B6rvaring/c/1844
    3. https://www.clasohlson.com/se/Jul/Julbak/c/2643
<br /><br />

Övrigt
-----------------------

Skrivet av: Åsa Höglund
