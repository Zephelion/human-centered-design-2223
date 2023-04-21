# Human Centered Design @cmda-minor-web 2022 - 2023

Human Centered Design is een  methode voor het ontwerpen van gebruiksvriendelijke interactieve toepassingen.

> What distinguishes Human-Centered Design from other problem-solving approaches is its obsessive focus on understanding the perspective of the person who experiences a problem, their needs, and whether the solution that has been designed for them is truly meeting their needs effectively or not. At its most effective, the very people who experience a problem the most are a constant part of the design process and when possible, become part of the design team itself. - [What Is Human-Centered Design?](https://medium.com/dc-design/what-is-human-centered-design-6711c09e2779)

Door regelmatig te testen met je doelgroep kom je tot een beter en passend ontwerp. 
Een Frontender heeft verstand van interactie, vormgeving én techniek. 
Als je web technieken beheerst kun je je ideeën snel prototypen en testen in een browser. Je kan dan aanpassingen doorvoeren, uitproberen en weer testen ...
        
In het vak Human Centered Design gaan we dingen ontwerpen voor echte mensen. 
Is er goede interactie? Kan je 'mens' je product op een prettige manier bedienen? 
Wat voor principes heb je gebruikt en getest? En is het leuk?

## Ontwerpen met en voor echte mensen

Voor dit vak krijg je een ontwerp-opdracht die je gaat maken voor 1 mens. 
Een echt mens. 
Je moet je ontwerp elke week testen. 
Door te testen en te itereren ga je je ontwerp verbeteren. 
Uiteindelijk heb je een ontwerp dat exclusief gemaakt is voor 1 persoon. 
Een _exclusive design_ ... 
Wie is deze persoon dan voor wie je dit gaat maken? 
Wat vindt deze persoon leuk of juist niet? 
Hoe bedient deze persoon een computer?

## Leerdoelen

- _Leren hoe je (design) principles in een ontwerp kan toepassen._
- _User needs begrijpen en gebruiken in je ontwerp._
- _Leren hoe je moet testen en de resultaten gebruiken voor het verbeteren van je ontwerp._

## Opdracht
Marie is Doof (met een hoofdletter inderdaad, dat betekent dat ze zichzelf als Doof identificeert, wat simpelgezegd betekent dat haar eerste taal Nederlandse Gebarentaal is). Je zult begrijpen dat Marie moeite heeft met dingen waar geluid een grote rol speelt.

**Hoe werkt een podcast voor Marie?**
In een transcriptie gaat natuurlijk nogal wat nuance verloren. Maak een oplossing die minimaal net zo prettig is voor iemand die niet kan luisteren als voor iemand die wel kan luisteren.

**Hoe werken closed captions voor Marie?**
Voor Marie gaat er enorm veel nuance verloren tijdens het kijken naar een film of een documentaire. Bij veel films worden closed captions aangeboden, maar die zijn zo neutraal als maar kan. Hoe zou je closed captions kunnen verrijken zodat deze voor Marie meer betekenis krijgen?

### Oplevering
Voor mij de opdracht gekregen om closed captions een sfeer te geven, zodat Marie een wat beter ervaring heeft bij het kijken van films en series.

## Week 1
### Bevindingen
* Afhankelijk van gebarentaal en liplezen
* Dol op series kijken
* Nederlandse tv is een slecht voorbeeld van hoe closed captions moeten worden weergegeven
* Voorbeelden hiervan zijn, ondertiteling neemt niet mee wie wat zegt, omgevingsgeluiden worden niet meegenomen
* Netflix handelt closed captions heel goed
* "spannende muziek" hoe weet ze of het spannend is?
* Een kookprogramma genaamd "High on the hog" is erg goed ondertiteld. Bijvoorbeeld je ziet hoe een man emotioneel verteld over slaafverleden. Man praat dan, en dan staat er [snik of piepende stem dan weet ze de emotie. 
* Stranger Things is het goed, maar slaan ze door. Too obvious dingen zoals explosies die ze ziet worden ook getoond in closed captions.
* Misschien een optie brengen, dat wanneer mensen fluisteren dat de tekst kleiner wordt
* Kleuren gebruik op basis wie praat (GTST)
* Mischien vanuit lettertype bepaalde emoties weergeven bijvoorbeeld wanneer iemand schreeuwt dat het in hoofdletter wordt gezet
* Indicatie van waar geluid vandaan komt
* Closed captions in het algemeen een hele makeover geven
* Spanning aan voelen door trillingen

### Series
Marie bood ons ook scenes uit van sommige series die we kunnen gebruiken in de uitwerking van onze eindoplevering

* The bear
* High on the hock

## Gameplan
Nu de uitdaging om een manier te vinden hoe ik de closed captions ga redesignen in code.

### Opties

1. De tag `<track>` in HTML wordt gebruikt om getimede teksttracks op te geven voor media-elementen zoals `<audio>` en `<video>`. Hier is een voorbeeld van het gebruik van de `<track>`-tag:

```html
<video controls>
  <source src="example.mp4" type="video/mp4">
  <track kind="subtitles" label="English" src="example-en.vtt" default>
  <track kind="subtitles" label="Spanish" src="example-es.vtt">
</video>
```

In dit voorbeeld bevat het `<video>`-element twee geneste `<track>`-elementen. Het kenmerk kind wordt gebruikt om het type teksttrack te specificeren, in dit geval "ondertitels". Het labelkenmerk specificeert het label dat wordt weergegeven voor de teksttrack en het src-kenmerk specificeert de URL van het bestand dat de teksttrackgegevens bevat. Het standaardattribuut wordt gebruikt om aan te geven welke teksttrack standaard moet worden weergegeven.

Merk op dat het src-attribuut moet verwijzen naar een geldig teksttrackbestand in de WebVTT-indeling, wat een eenvoudige op tekst gebaseerde indeling is voor getimede teksttracks.

2. Gebruik maken van een soort van closed caption library. Deze manier geeft me het meeste vrijheid om de closer caption te customizen.





