---
---
Rapport Laddningstid
=========================

Urval
-----------------------

Jag använde mig utav Googles PageSpeed Insight samt Google Chrome Dev tools specifikt network tab för att mäta hur dessa 3 sidor presterar.

* feber.se (en hemsida om teknik, film, spel, bilar och nyheter rörande internet)
* aftonbladet.se (Nyheter samt väldigt mycket reklam)
* dribbble.com (Sida för att dela med sig utav design projekt)

Laddningstid/antal resurser/storlek
-----------------------

* feber.se Laddningstid: 2.5s, Storlek: 2.5mb, Resurser: 135
* aftonbladet.se Laddningstid: 3.1s, Storlek: 3.9mb, Resurser: 187
* dribbble.com Laddningstid: 5.14s, Storlek: 8.3mb, Resurser: 117

Resultat
-----------------------

Jag blev lite smått förvånad över att se hur bra Aftonbladet ändå stod upp mot de andra sidorna eftersom jag förknippade Aftonbladet starkt med all dess reklam vilket jag trodde skulle slöa ner sidan. Istället visade det sig att Dribbble i detta fall laddade långsammare vilket nog har sin naturliga förklaring i att man inte vill komprimera bilderna för mycket eftersom det är en sida som är gjort för att visa upp sina designs. I Dribbbles fall hade jag kikat på hur man kan förbättra bilder optimeringen på sidan. För Aftonbladet hade jag försökt se om man kan minimera antal skript som laddas och för feber jag satsat på att försöka förbättra mobil sidan.

Analys
-----------------------

Som jag nämnde ovan var jag ändå smått förvånad över att se hur bra Aftonbladet presterade och hur dåligt resultat feber hade på deras mobil sida. Det är trots allt en sida som bara listar nyheter utan särkilt mycket funktionalitet och design så jag trodde att den skulle presentera bättre. Feber har som sagt en del de kan förbättra på sin mobil sida och något jag såg genom PageSpeed Insights var att de kan göra en stor förbättring genom att vänta med att ladda bilderna längre ner på sidan eftersom läsarna ändå inte kommer att se bilderna när de kommer ni på sidan. Genom detta kan de spara upp till 7s vilket är en stor förbättring. 

Som misstänkte hos Aftonbladet finns det förbättringar att göra med hur de laddar sina scripts, just nu är det otroligt många scripts som laddas samtidigt vilket gör att sidan blir långsammare. Man blir inte alltför förvånad då man går in på aftonbladet utan Adblocker och ser reklam nästan överallt, all denna reklam har scripts som mäter hur de presenterar. Sist men inte minst har vi Dribbble, en sida som fokuserar på att dela med sig utav sina designs, eftersom bilderna är i fokus så är det där fokus för optimering också bör ligga. I detta fall kan man spara om bilderna i de nya bild formaten och se till att bilderna sparar i korrekt storlek för att förbättra laddningstiden hos Dribbble.

Rangordning
-----------------------

* #1 Dribbble
* #2 Feber
* #3 Aftonbladet

Det var otroligt jämnt mellan Feber och Aftonbladet. Även om Dribbble tar lite längre tid att ladda och är lite större så är det något man kan leva med eftersom man gärna inte tummar på kvaliteten av bilderna på en sida som Dribbble, för att de andra två sidorna ska kriga om första platsen så tycker jag att de främst kan dra ner på antal skript och optimera mobil sidan. något som är intressant att se hos de 3 sidorna är hur mycket de presterar på mobil sidorna trots att mobilt användande blir större och större, och för två sidor som Feber och Aftonbladet som troligtvis har mycket mobil trafik tycker jag verkligen att de har lite att jobba på.

Egen uppfattning
-----------------------

Jag tycker att det är svårt att säga, eftersom det finns många olika verktyg för sidan att kännas “snabb” även fast den inte är helt färdig laddad, man kan ladda bilder allt eftersom, man kan ladda fonter allt eftersom. Men i huvudsak tycker jag att sidan inte ska blockeras av script och dylikt i mer än ca 2s, sen får sidan gärna ladda mer efter det men då ska jag kunna integrera med sidan.

Referenser
-----------------------

* https://developers.google.com/speed/pagespeed/insights/?url=feber.se&tab=mobile
* https://developers.google.com/speed/pagespeed/insights/?url=aftonbladet.se&tab=mobile
* https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fdribbble.com%2F&tab=desktop
* https://docs.google.com/spreadsheets/d/1x7ikF8alGupRBMtZe8EcOwvHXImVmu9tSWcRnAGqJBI/edit#gid=0

Övrigt
-----------------------

* Sam Öjling

