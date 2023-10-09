# Teori

## Vad står HTML för och vad är dess grundläggande syfte?
HTML står för HyperText Markup Language och är ett språkspråk. HTMLs grundläggande syfte är att det används till att skapa webbsidor genom att strukturera och layouta innehållet på webbsidan . Det HTML gör är att man kan skapa olika rubriker, buttons, paragraf, bilder, navigationer och etc på webbsidan. 

## Beskriv skillnaden mellan HTML-element och HTML.attribut.
Skillnaden mellan element och attribut är att element är som en byggsten i en HTML kod som används till att strukturera webbsidan och beskriver innehållet på webbsidan, som t.ex. p för ett paragraf, img för en bild eller h1 för en rubrik. Attribut är egenskaperna hos en element för att ge mera information om själva elementet som t.ex. attributet "color" för att ange färg hos en en element som kan vara en h1 tagg , "font-size" för att ange tecken storlek för en element eller "background-color" för att ange bakgrundsfärg  för en element.

## Vad är skillnaden mellan en <div> och en <span> i HTML, och när används de vanligtvis? 
Skillnaden mellan en div-tagg och en span-tagg är att en div-tagg är en block-element och skapar en tom låda som kan innehålla olika element som till exempel,  p-taggen, h1-taggen  eller img-taggen. Div-taggen används ofta till när du vill skapa nya block av innehåll på webbsidan eller göra olika delar av webbsidan större. Jämför med span-taggen som är ett inline-element och används ofta till att markerar delar av texten eller innehållet inom en rad för att till exempel styla eller ändra egenskaperna på den delen eller innehållet. 

## Hur skapar du en länk till en annan webbsida i HTML?
Man skapar det genom att använda en anchor alltså <a>-taggen. Vad den gör är att den definierar ett hyperlänk som då används till att länka andra webbsidor och är ett self-closing tag. Länkningen kan se ut så här 
<a href=“https://www.youtube.com”>

## Vad är en HTML-tabell och hur skapar du en enkel tabellstruktur?
HTML-tabell är en tabell som används för att organisera data i rader och kolumner.  En enkel struktur på en tabell kan vara t.ex. 
<table>
   <theader>Table Header</theader>
   <tr>
      <td>Column 1</td>
      <td> Column 2</td>
  </tr>
  <tr>
      <td>Cell 1</td>
      <td> Cell 2</td>
  </tr>
</table>

## Förklara hur du inkluderar externa CSS-stilar i en HTML-sida.
Det första är att man skapar en sub mapp som heter css därefter så skapar man en css fil i sub mappen css därefter så länkar du det i head-taggen genom att använda en anchor  a-taggen. 

##Vad är skillnaden mellan inline, intern och extern CSS?
Skillnaden  mellan de är att inline används inuti taggarna och prioriteras först av webbläsaren, intern är då när man använder style-taggarna för att styla och prioriteras andra av webbläsaren och extern är när man länkar en css fil i 
head-taggen 

## Vad innebär selektorerna id och class i CSS, och hur används de?
Id och class är en attribut för att definiera vissa stilar i CSS. Id är unik vilket innebär att de bara får använda en gång per sida jämfört med en class som kan användas flera gånger per sida. 

## Hur kan du centrera en HTML-element horisontellt och vertikalt med CSS
Det finns många olika sätt att centrera ett HTML-element genom att använda till exempel Flexbox eller Grid. 

## Vad är "box modell" i CSS och vilka ingår i det?
CSS-box modellen är en låda som visar varje HTML-element. I boxmodellen består det Content: är det område där text och bilder visas, Padding: Är det området runt om Content, Border: är gränsen som går runt Content och Padding, Margin: är det området utanför Content,Padding och Border.

## Vad är Bootstrap och vilket syfte tjänar det inom webbutveckling?
Bootstrap är ett ramverk med en library med färdig klara CSS-templates. Fördelen med bootstrap är att det sparar tid genom att det finns färdiga css-templates som är responsiva. Också att bootstrap är en öppen källkod, vilket innebär att vem som helst kan använda deras kod.

## Hur inkluderar du Bootstrap i en HTML-sida genom att använda CDN (Content Delivery Network)?  
Genom att du länkar deras CSS fil som de har i ditt HTML-kod  i head-taggen därefter länkar man deras Javascript fil som de har också i head-taggen

## Vad är Bootstrap-griden och hur använder du den för att skapa responsiva layouter?
Bootstrap-grid är verktyg för att skapa responsiva layouter som är byggt med flexbox. Man använder det genom att lägga till namnet “Container”, “row” och “col-sm” i class attributen i en div så får man en responsiv layout

## Nämn några av de grundläggande komponenterna som Bootstrap erbjuder för att bygga användargränssnitt.
Till exempel Buttons, Navigation Bar, Forms, Tabells och Cards etc

## Vad är JavaScript och hur skiljer det sig från HTML och CSS?
Javascript är ett programmeringsspråk som kan göra logiska funktioner som t.ex. true or false,  jämför med HTML och CSS som inte kan göra det. 




