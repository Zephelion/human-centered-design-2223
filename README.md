# Human Centered Design - Improvement on closed captions

Human Centered Design is een  methode voor het ontwerpen van gebruiksvriendelijke interactieve toepassingen. Ik heb de opdracht gekregen om een verbetering te maken op closed captions voor mijn klant Marie van Driesche.

> What distinguishes Human-Centered Design from other problem-solving approaches is its obsessive focus on understanding the perspective of the person who experiences a problem, their needs, and whether the solution that has been designed for them is truly meeting their needs effectively or not. At its most effective, the very people who experience a problem the most are a constant part of the design process and when possible, become part of the design team itself. - [What Is Human-Centered Design?](https://medium.com/dc-design/what-is-human-centered-design-6711c09e2779)

![Plaatje](/images/plaatjereadme.png)

## Onderzoeksvraag
hoe kan ik de nuances die soms worden gemist in closed captions beter overbrengen aan een blind persoon?

- Wat zijn dingen die Marie niet prettig vind aan closed captions?
- Hoe kan ik dingen zoals geluid proberen te simuleren voor Marie?

## Probleemdefinitie
Mary is doof (inderdaad met een hoofdletter, wat betekent dat ze zichzelf als doof beschouwt, wat simpelweg betekent dat haar moedertaal Nederlandse Gebarentaal is). Je zult begrijpen dat Mary moeite heeft met dingen waarbij de stem een ​​grote rol speelt.
Voor Marie gaat er enorm veel nuance verloren tijdens het kijken naar een film of een documentaire. Bij veel films worden closed captions aangeboden, maar die zijn zo neutraal als maar kan. Hoe zou je closed captions kunnen verrijken zodat deze voor Marie meer betekenis krijgen?

## Oplossing
Mijn oplossing was om closed captions te verbeteren en effects beter naar voren te brengen. Ik heb een paar functie hiervoor geimplementeerd.

* Accent van bepaalde personages naar voren brengen.
* Wanneer bepaalde effecten in beeld komen (*pot drops*) een interactie sturen naar Marie hiervoor maak ik gebruik van een tril.
* Onnodige dingen die in closed captions ziten weghalen.

## Link
Hier is een oplossing van hoe ik closed captions zou verbeteren klik de onderstaande link om de fragment te bekijken.
[Oplossing](https://zephelion.github.io/human-centered-design-2223/)

## Design principles
In deze sectie zal ik uitleggen hoe ik elke van de design prinipes heb toegepast. Ik probeerde elke design principe zo goed mogelijk uit te werken om de applicatie zo exclusief mogelijk voor Mary te maken.

### Study Situation
Het ontwerpprincipe van de studiesituatie, of gesitueerd leren, is met name relevant voor dove personen, aangezien zij vaak te maken hebben met unieke uitdagingen bij het verkrijgen van toegang tot informatie en leren in traditionele klasomgevingen.

Ik had gelukkig de mogelijkheid om Mary te kunnen interviewen op de eerste dag. Waardoor ik aan de hand van de kort interview meteen de situatie kon schetsen voor Mary en de problemen die zei tegen komt bij het gebruik van closed captions. Wat ik al eerder heb gezegd is, dat Mary moeite heeft om bepaalde nuances in closed captions te begrijpen en ze vindt ook in het algemeen dat sommige closed captions heel overdreven zijn en sommmige momenten dan te weinig informatie geven.

### Prioritise Identity
Prioriteit geven aan identiteit bij ontwerp en productontwikkeling houdt in dat rekening wordt gehouden met de culturele, sociale en persoonlijke identiteit van de personen die het product zullen gebruiken. Deze benadering erkent dat mensen unieke identiteiten hebben die hun voorkeuren, behoeften en gedrag beïnvloeden, en dat producten die zijn ontworpen met deze identiteiten in het achterhoofd, waarschijnlijk relevanter, toegankelijker en wenselijker zijn voor de beoogde gebruikers.

Mary is doof en ze heeft al aangegeven, dat closed captions beter kunnen, maar om de product nog prettiger te maken had Mary een paar series aan ons gegeven die zij heel leuk vond. Deze series waren The Bear en The Last of Us. Ik heb er voor gekozen om een scene uit de The last of Us te pakken en de closed captions door op te verbeten. Mary is bekend met The Last of Us dus ik denk dat het wel prettiger voor haar is.

### Ignore Conventions
Het ontwerpprincipe "Ignore Conventions" betekent het opzettelijk negeren van gevestigde ontwerpnormen en het verkennen van nieuwe en onconventionele benaderingen om iets innovatiefs en unieks te creëren. Dit principe moedigt ontwerpers aan om traditionele ontwerppraktijken uit te dagen, te experimenteren met nieuwe ideeën en de grenzen te verleggen van wat in hun vakgebied als "normaal" of "aanvaardbaar" wordt beschouwd.

Door conventies te negeren, kunnen ontwerpers producten en ontwerpen maken die zich onderscheiden van de massa, de aandacht van mensen trekken en de status quo uitdagen. Deze aanpak kan met name effectief zijn op gebieden als kunst, mode en technologie, waar innovatie en creativiteit hoog in het vaandel staan.

Omdat closed captions heel "blant" zijn probeerde ik sowieso emotie wat meer naar voren te brengen in bepaalde situaties bijvoorbeeld wanneer een persoon schreeuwt alles in caps lock maken of wanneer een situatie "suspense" opbouwt met tril werken om zo dat gevoel te simuleren.

### Add nonsense
Van wat ik heb begrepen is nonsense toevoegen het concept om een wat niet normale element in je applicatie te introduceren. Ik probeerde deze principes toe te passen door gebasseerd op hoe langzamer hand een persoon in dr emotie begint te verdiepen dan zou de UI hierop reageren. Bijvoorbeeld hoe bozer een persoon is hoe roder bijvoorbeeld de scherm wordt (hier komt ik later op terug:)).

<hr>


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
<hr>

## Week 1
In de eerste week hadden ik en me groepje de mogelijkheid om Mary te interviewen hiervoor hadden we een reeks van vragen aan haar gesteld om een beter beeld te krijgen wat voor haar kunnen maken.
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
* The Last of Us

Ik heb gekozen voor een scene uit The Last of Us om daar de closed caption te kunnen verbeteren. Hiervoor heb ik de panick attack scene gekozen en probeerde ik voor de eerste minuut de closed captions te verbeteren.
[Joe has a panick attack](https://www.youtube.com/watch?v=mOvWvB7QKQA)

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

3. Uiteindelijk had ik ervoor gekozen om gwn een soort van object te maken die de captions displayed op een bepaalde tijd. Als je benieuwd er naar bent mag je even in de code koekeloeren.




