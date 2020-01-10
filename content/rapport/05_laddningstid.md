---
---
Kmom05 laddningstid
=======================

I denna rapport kommer jag mäta och analysera 3 olika webbplatsers laddningstid. Jag kommer även gå igenom om det finns eventulla förbättringar som kan utföras för respektive webbplats.

Urval
-----------------------

Jag valde tre utav världens största nyhetssidor, The New York Times, CNN International och BBC. De va dessa tre sidor jag egentligen tänkt arbeta med i förra kursmomentet, men då ingen av dem innehåller värst mycket färg så valde jag att jobba med tre andra webbplatser i stället. Till detta kursmomentet tyckte jag däremot att dessa sidor lämpar sig utmärkt, då de alla tre innehåller en heldel info och bilder.

Metod
-----------------------

Efter jag valt mina webbplatser skapade jag ett excelark i Google Sheets. Detta använde jag sedan för att documentera mina resultat under undersökningens gång. När detta var  klart tog jag en snapshot på varje webbplats och valde ut de tre sidor som ska undersökas för respektive webbplats. För varje undersida gjorde jag sedan tester i Google Pagespeed Desktop, Google Pagespeed Mobile och Devtols. Resultaten från dessa tester documenterades i ett [excelark](https://docs.google.com/spreadsheets/d/189Jkq8aIjhYCdqlFTSvNUp6KWXItCQlcspRhnNakzBQ/edit?usp=sharing).

Resultat
-----------------------

Klicka [här](https://docs.google.com/spreadsheets/d/189Jkq8aIjhYCdqlFTSvNUp6KWXItCQlcspRhnNakzBQ/edit?usp=sharing) för excelark.

**The New York Times**
[FIGURE src=image/nytimes.png?w=500]

Sida 1: [Startsida](https://www.nytimes.com/)  
Sida 2: [World News](https://www.nytimes.com/section/world)  
SIda 3: [Technology](https://www.nytimes.com/section/technology)

Mät värden från undersökningen finns under rubriken 'The New York Times' [här](https://docs.google.com/spreadsheets/d/189Jkq8aIjhYCdqlFTSvNUp6KWXItCQlcspRhnNakzBQ/edit?usp=sharing).

För alla de tre sidor som jag undersökte från The New York Times handlar de flesta förbättringar de kan utföra om bildhantering. De två bästa förbättringar de kan göra är att skicka bilder i mordernare format och att skjuta upp inläsningen av bilder som inte används på sidan. En annan förbättring de borde utföra som inte handlar om bildhantering är att rensa i sin CSS kod.

**CNN International**
[FIGURE src=image/cnn.png?w=500]

Sida 1: [Startsida](https://edition.cnn.com/)  
Sida 2: [World](https://edition.cnn.com/world)  
Sida 3: [Travel](https://edition.cnn.com/travel)

Mät värden från undersökningen finns under rubriken 'CNN International' [här](https://docs.google.com/spreadsheets/d/189Jkq8aIjhYCdqlFTSvNUp6KWXItCQlcspRhnNakzBQ/edit?usp=sharing).

För CNNs tre sidor finns det en hel del olika förbättringar som bör genomföras. CNN var den webbplats som fick sämt resultat i undersökningen och det handlar främst om att de borde läsa in viktiga resurser i förväg och aktivera textkomprimering. Andra åtgärder de borde genomföra är bland annat att minifiera JavaScript, ta bort oanvänd CSS kod, skicka bilder i modernare format och skjuta upp inläsningen av bilder som inte visas på skärmen.

**BBC**
[FIGURE src=image/bbc.png?w=500]

Sida 1: [Startsida](https://www.bbc.com/)  
Sida 2: [News](https://www.bbc.com/news)  
SIda 3: [Travel](http://www.bbc.com/travel)

Mät värden från undersökningen finns under rubriken 'BBC' [här](https://docs.google.com/spreadsheets/d/189Jkq8aIjhYCdqlFTSvNUp6KWXItCQlcspRhnNakzBQ/edit?usp=sharing).

Färbättringarna från nämda för ovanstående webbplatser återkommer även på CNNs webbplats, dock inte i lika stor utsträckning. De har helt klart bättre bildhantering än övriga webbplatser i undersökningen. Trots allt så borde de förbättra att de skickar bilder i mordernare format, tar bort resurser som blockerar renderingen, tar bort oanvänd CSS och minifierar JavaScript.

Analys
-----------------------

Det finns en hel del att förbättra för samtliga webbplatser i min undersökning. Allra sämst är de för mobilversionerna där det högsta betyget hamnade på 68 och resterande betyg hamnde under 30. Den vanligaste förbättringsåtgärden för samtliga webbplatser är bildhantering. De borde bland annat skicka bilder i mordernare format och skjuta upp inläsningen av bilder som inte visas på skärmen. Ett annat åtkommande problem är oänvänd CSS kod som borde rensas bort.

Under undersökningens gång så upptäkte jag att samtliga av mina webbplatser verkar vara så kallade evighetsloppar. Jag spekulerar i att då det handlar om nyhetssidor med anonser så har det att göra med att anonserna laddas om men då jag inte har något stöd för detta i min undersökning så bortser jag från detta i resultatet.

För att utse en vinnare har jag valt att slå samman betygen från Google Pagespeed och även kolla på genomsnitts värderna från devtols undersökningen. Överlägsen vinnare på både mobil och desktop blir BBC med ett genomsnittsbetyg på 74 på desktop och 36 på mobil. Tvåa kom The New Tork Times med genomsnittsbetygen 43,66 på desktop och 21 på mobil. Och sist med skamligt dåliga betyg kom CNN International med genomsnittsbetygen 32,66 på desktop och 10 på mobil.

När det kommer till laddnings tid var det svårt att bedömma sidorna. Som nämt ovan så verkar samtliga av webbplatserna i undersökningen vara så kallade eveghetslopar. Dock såg jag inte detta som ett problem när jag besökte webplatserna. Infon och bilderna på samtliga webbplatser var laddade inom 2-3 sek vilket inte är ett numer som störde mig i samanhanget. Jag skulle nog säga att min gräns för vad som hade stört mig i laddningstid hamnar på 3 sek. Är laddningstiden längre än det så blir det något jag reagerar på. Så även om sidorna förtsatte att ladda efter de ursprungliga 2-3 sekunderna så var det inget som märktes.

Referenser
-----------------------

Google Pagespeed  
Devtols  
[The New York Times](https://www.nytimes.com/)  
[CNN International](https://edition.cnn.com/)  
[BBC](https://www.bbc.com/)

Övrigt
-----------------------

Frida Larsson
