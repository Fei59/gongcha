# Procesverslag
Markdown is een simpele manier om HTML te schrijven.  
Markdown cheat cheet: [Hulp bij het schrijven van Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Nb. De standaardstructuur en de spartaanse opmaak van de README.md zijn helemaal prima. Het gaat om de inhoud van je procesverslag. Besteedt de tijd voor pracht en praal aan je website.

Nb. Door *open* toe te voegen aan een *details* element kun je deze standaard open zetten. Fijn om dat steeds voor de relevante stuk(ken) te doen.





## Jij

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Auteur:
  Chi-fei Chi

  #### Je startniveau:
  Blauw

  #### Je focus:
  Responsive
 
</details>





## Je website

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Je opdracht:
  https://www.gong-cha.com/

  #### Screenshot(s) van de eerste pagina (small screen): 
  hier de naam van de pagina  
  <img src="/readme-images/eerstepagina.jpeg" width="375px" alt="Home pagina van gong cha">

  #### Screenshot(s) van de tweede pagina (small screen):
  hier de naam van de pagina  
  <img src="/readme-images/tweedepagina.jpeg" width="375px" alt="Producten pagina van gong cha">
 
</details>



## Toegankelijkheidstest 1/2 (week 1)

<details>
  <summary>uitwerken na test in 2<sup>e</sup> werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen:
  - De screenreader leest tekst voor die niet op de pagina zichtbaar is.
  <img src="/readme-images/verstopte-tekst.jpeg" width="375px" alt="De tekst die je nergens op de pagina ziet.">

  - Ik vond het goed dat er een introductie wordt gegeven wanneer je de website bezoekt met een screenreader. <img src="/readme-images/introductiesite.jpeg" width="375px" alt="Je hoort een introductie van op welk pagina je bevindt via de screenreader.">

  - Er wordt geen geldige HTML gebruikt.
  <img src="/readme-images/geldigehtml.jpeg" width="375px" alt="De HTML-checker toont veel errors.">

  - Niet alle afbeeldingen hebben een beschrijvende alt-tekst en voor decoratieve afbeeldingen wordt geen leeg alt-attribuut toegepast.
  <img src="/readme-images/alt.jpeg" width="375px" alt="De afbeelding heeft als alt-tekst “Tea 02 1.png”, wat niet beschrijvend is en ook niet leeg is.">

  - Er wordt geen h1 gebruikt.
  <img src="/readme-images/geenh1.jpeg" width="375px" alt="De hoofdkop is een span in plaats van een h1.">

  - De contrastverhouding van de website is voldoende.
  <img src="/readme-images/contrast.jpeg" width="375px" alt="De contrastverhouding is 6,23, wat voldoet aan de WCAG-richtlijnen">

  - Er is rekening gehouden met kleurenblindheid; de meeste inhoud blijft goed leesbaar.
  <img src="/readme-images/kleurenblind.jpeg" width="375px" alt="Zo ziet de website eruit voor kleurenblinde gebruikers.">

  - Er worden div-elementen gebruikt om lijsten te structureren in plaats van ul,ol,dl.

  - Ze gebruiken button-elementen, maar niet voor alle knoppen.

  - De website heeft een unieke titel voor elke pagina.

  - Het attribuut lang wordt toegepast in de website.

  - Op deze website wordt een h3-element eerder gebruikt dan een h2-element, wat de hiërarchie van koppen doorbreekt.

  - De website past zich niet aan de dark/light modus.

  - Zelfs wanneer de optie “beweging verminderen” is ingeschakeld en geanimeerde afbeeldingen zijn uitgeschakeld, wordt er nog steeds een animatie afgespeeld bij hover over de bubble tea afbeelding.

  - Ze gebruiken eenvoudige taal om het voor iedereen gemakkelijk leesbaar te maken.

  - Je zou niet alle content kunnen zien als je met Tab op de website navigeert.

  - Je zou op de website kunnen inzoomen.

  - Ze gebruiken het a-element voor links.

</details>



## Breakdownschets (week 1)

<details>
  <summary>uitwerken na afloop 3<sup>e</sup> werkgroep</summary>

  ### de hele pagina: 
  <img src="/readme-images/breakdown.jpg" width="375px" alt="Afbeelding van de breakdown-schets die ik heb gemaakt.">

  ### dynamisch deel (bijv menu): 
  <img src="/readme-images/animatie.jpg" width="375px" alt="Breakdown van een dynamisch deel.">

  ### wellicht nog een dynamisch deel (bijv filter): 
  <img src="/readme-images/hover.jpg" width="375px" alt="breakdown van nog een dynamisch deel">

</details>





## Voortgang 1 (week 2)

<details>
  <summary>uitwerken voor 1<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  Het opzetten van het document en het maken van de header ging goed. Alleen wist ik niet waarom de inspector in Google Chrome mijn achtergrondafbeelding niet als een afbeelding herkende. Daarom vroeg ik het aan de docent. Het probleem bleek te liggen aan het feit dat ik geen directe verbinding had gemaakt in mijn CSS. Ik had 
  /images/eersteachtergrond.png gebruikt, maar Google kon dit niet lezen; je moest het verbinden als ../images/eersteachtergrond.png. 
  
  Daarna had ik nog drie vragen, tenzij ik aan mijn website ging werken:
  1. Hoe kan ik margin-top: -1em; op een semantisch correcte manier toepassen?
  2. Hoe kan ik een knop in een knop plaatsen? 
  <img src="/readme-images/buttoninbutton.jpeg" width="375px" alt="In deze afbeelding zie je een knop in een knop">
  3. Wat is de beste manier om de overgang naar een witte pagina te maken? 
  <img src="/readme-images/wittepagina.jpeg" width="375px" alt="In deze afbeelding zie je een overgang van een achtergrond met kleur naar een witte pagina">


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  1. Door margin: 0 en de padding aan te passen, krijg je het gewenste effect zonder -1em te gebruiken. Dit komt doordat de h1 automatisch een margin krijgt.
  2. Door transition: all 1s ease toe te voegen, komen de blokken vloeiender samen. Je kunt daarnaast de knop verplaatsen door de margin-right toe te passen.
  3. Door de body wit te maken en de rode achtergrond die je nu hebt als achtergrondafbeelding op een section te plaatsen, kun je de achtergrondafbeelding aanpassen. Daarnaast kun je ook de SVG die op de website wordt gebruikt, als achtergrond toevoegen, zodat je de effect krijg die ze ook hebben.

</details>





## Voortgang 2 (week 3)

<details>
  <summary>uitwerken voor 2<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  Het maken van het hamburgermenu en de carousel was erg lastig. Ik heb in totaal drie uur geprobeerd om het te maken, maar het lukte niet. Wel is mijn pagina grotendeels af, dus dat is goed.
  
  Tijdens het coderen vroeg ik me af waar ik mijn cookies moest plaatsen en of ik de hele cookiepagina ook moest maken.
  <img src="/readme-images/cookie.jpeg" width="375px" alt="In deze afbeelding zie je een cookie">


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

- Voor de footer heb ik algemeen alleen de afbeelding en wat padding nodig. 
- Verwijder de <span> (gebruik geen flex of grid daarvoor).
- Je zou de site responsive kunnen maken met @media in HTML (zie presentatie van 17 september).
- Plaats de @media-regels onderaan je CSS-bestand.
- Het zou handig zijn als je de cookies maakt.
- De knop die van boven naar onder de pagina gaat, is eigenlijk een a-element.

</details>





## Toegankelijkheidstest 2/2 (week 4)

<details>
  <summary>uitwerken na test in 9<sup>e</sup> werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen (geef ook aan wat er verbeterd is):

</details>





## Voortgang 3 (week 4)

<details>
  <summary>uitwerken voor 3<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  Het maken van een responsive ontwerp ging beter dan ik had verwacht. In het begin had ik wel wat problemen, omdat de @media niet werkte. Dat heb ik opgelost door het op te zoeken, uiteindelijk bleek het probleem te zijn dat ik de min-width te hoog had ingesteld. Daarbij moet ik de toegankelijkheidstest nog doen. Als laatste heb ik een vraag: mag ik grid gebruiken op alle elementen?


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
  - ...

</details>





## Eindgesprek (week 5)

<details>
  <summary>uitwerken voor eindgesprek</summary>

  ### Je uitkomst - karakteristiek screenshots:
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="uitomst opdracht 1">


  ### Dit ging goed/Heb ik geleerd: 
  Korte omschrijving met plaatjes

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="top">


  ### Dit was lastig/Is niet gelukt:
  Korte omschrijving met plaatjes

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="bummer">
</details>





## Bronnenlijst

<details open>
  <summary>continu bijhouden terwijl je werkt</summary>

  Nb. Wees specifiek ('css-tricks' als bron is bijv. niet specifiek genoeg). 
  Nb. ChatGpT en andere AI horen er ook bij.
  Nb. Vermeld de bronnen ook in je code.

  1. https://chatgpt.com/share/68d28dda-d214-800d-843d-78c02d5d5675 
  2. bron 2
  3. ...

</details>
