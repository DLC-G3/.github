# DLC Groep 3

[Trello board](https://trello.com/invite/b/NkGvCUg1/b032ee17baffac0de82a740150c6d31a/industry-project-dlc-g3) - [Github organization](https://github.com/DLC-G3)

## Rollenverdeling

- Jorik Devreese: <b>Scrum master, Developer</b>

- Tibo Vanbrabandt: <b>Product owner, Developer</b>

- Jonas Faber: <b>Developer</b>





## Project omschrijving


<p>
  DLC wil de mogelijkheid geven aan amateur ploegen om professionele analyses te maken. Momenteel maken ze hiervoor gebruik van een applicatie. Aan de hand van camera’s die gepositioneerd staan op de voetbalvelden kunnen ze de matches en trainingen herbekijken op de app. Ze kunnen belangrijke momenten taggen door op de tijdlijn van de video vlagjes te plaatsen, met kernwoorden zoals ‘doelpunt’ of ‘vrije trap’. Later kunnen ze dan automatisch naar de volgende gebeurtenis gaan, of dus doorspoelen naar een van die tags. Dit maakt het mogelijk om met het voetbalteam de analyse van de matches efficiënter te maken.
</p>

<p>
  Het plaatsen van deze tags is echter manueel en intensief werk. DLC vraagt aan Howest MCT om het taggingprocess te automatiseren aan de hand van AI. Hiervoor geven ze ons toegang tot videomateriaal van matches en trainingen, zodat we de AI modellen kunnen trainen. Ze vragen hierbij dat het model in staat is om de vlagjes in 80% van de gevallen juist te plaatsen.
</p>

## Technische oplossing

<p>
  Automatisering van het proces dat men nu manueel doet. Zorgen dat alle videobeelden automatisch getagd en gegroepeerd worden, zodat men na een match via het cloud dashboard alle fases kunnen bekijken zonder dit gehele proces zelf te moeten uitvoeren.
</p>
<p>
  Hiervoor zouden we gebruik maken van Object Segmentation. Voor dit moeten we alle aparte objecten gaan labelen, hiervoor kunnen we gebruik maken van VOTT of andere gelijkaardige software.
</p>




## Eerste gesprek met klant

### Vragen van ons

#### Welke data krijgen we terug van elke match?

We zouden een video fragment krijgen van alle filmpjes van heel de wedstrijd naast elkaar. Telkens andere kleuren tenue. We kunnen ook korte fragmenten (of tags) van het dashboard halen, waarmee we kunnen treinen. Ook kunnen we zelf nog fragmenten maken door naar het simulatie centrum gaan.
#### Hoeveel data krijgen wij ter beschikking?

Er is al veel data, maar er komt meer ( we gaan zelf nog wedstrijden leveren )
#### Is het de bedoeling dat wij puur de footage trainen, of moeten wij hier ook een visualisatie aan toevoegen?

We moeten in eerste instantie gewoon een lijst geven van tags.


### Nota's

#### Wat is het doel van het project?

Het doel is een AI model te trainen dat de gebeurtenissen in de videobeelden kan benoemen en categoriseren. Voorbeelden van deze gebeurtenissen zijn:
  - Doelpunten
  - Vrije trappen
  - Bal verlies
  - Hoekschoppen
  - ...

#### Wat is er al verwezelijkt?

<p>
  Er zijn een 7-tal camera’s die de match opnemen. Waarvan 2 aan het doel , 1 in het midden dat het spel kan volgen, en de rest aan de zijlijn die de verschillende zones van het veld opnemen. Ook is er een dashboard die de trainers kunnen gebruiken om de video fragmenten te ‘taggen’. Momenteel gebeurt dit handmatig.
</p>

<p>
  Achteraf komen deze fragment op het dashboard en kan men deze gebruiken om strategie duidelijker te maken aan de spelers. Om meer mogelijkheden te bieden worden sommige trainingen ook opgenomen en niet alleen de matches, die op hun beurt ook weer ‘getagt’ kunnen worden.
</p>

<p>
  Nu dat de fragmenten ‘getagt’ zijn kunnen de trainers een tijdlijn zien met heel het fragment met al hun tags op. Ze kunnen automatisch naar de vorige en volgende tags gaan.
</p>

#### Welke faciliteiten zijn er beschikbaar voor ons?

<p>
  We gaan toegang krijgen tot het dashboard om alle fragmenten te kunnen downloaden. Ook zouden we deze fragmenten kunnen taggen moest het nodig zijn. We kunnen daar ook clips maken.
</p>

<p>
  Om toch meer variatie te hebben kunnen we ook zelf fases (of gebeurtenissen) simuleren op afspraak. Moesten we het willen zou het mogelijk zijn om een match te organiseren. 
</p>


