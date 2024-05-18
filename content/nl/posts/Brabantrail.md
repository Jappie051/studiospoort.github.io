---
title: Brabantrail 
date: '2024-05-10'
description: "Een fictieve netkaart voor een tramnetwerk in Noord-Brabant"
author: "Jappie"

---

> Een fictieve netkaart voor een tramnetwerk in Noord-Brabant <br>
> BrabantRail is een project waar ik al een flinke tijd mee bezig ben, het is mijn eerste grote kaartproject.

{{< figure src="images/Brabolandklein.png" width="100%" link="/BrabantRail.pdf" >}}
> Een pdf op volle schaal kan je [hier](/BrabantRail.pdf) vinden. Je kan ook op de afbeelding hierboven klikken.

# Introductie

Noord-Brabant is een dichtbevolkte provincie. 
Via het spoor zijn alle grote steden verbonden met de IC-treinen van NS. 
Hieronder vallen de tienminutentreinen vanaf Eindhoven naar Amsterdam en de IC Direct door Breda over de HSL.
Ook heb je in het oosten enkele stations van de Maaslijn (Arriva).

Vroeger waren er echter 4 extra spoorlijnen:
- [Bels Lijntje](https://nl.wikipedia.org/wiki/Spoorlijn_29_Aarschot_-_Tilburg) - verbindde Turnhout (BE) en Tilburg
- [Spoorlijn 18](https://nl.wikipedia.org/wiki/Spoorlijn_18_Winterslag_-_Eindhoven) - verbindde Eindhoven met Pelt (BE) en Hasselt (BE)
- [Langstraatspoorlijn of Halvenzolenlijntje](https://nl.wikipedia.org/wiki/Spoorlijn_Lage_Zwaluwe_-_%27s-Hertogenbosch) - verbindde Lage Zwaluwe met 's-Hertogenbosch via Waalwijk
- [Duits Lijntje](https://nl.wikipedia.org/wiki/Spoorlijn_Boxtel_-_Wesel) - verbindde Boxtel met Goch (DE) via Uden en Gennep

Vanwege hun eensporig en ongeëlektrificeerde karakter zijn deze spoorlijnen in de 20e eeuw opgeheven.
Verschillende stukken spoor liggen er nog, maar het meeste is weggehaald.
Grote delen zijn ook onderdeel geworden van snelfietsroutes.
Ondanks dat deze lijnen al een tijdje weg zijn, kan je nog vrij makkelijk op kaarten zien waar ze vroeger lagen.
Omdat in grote mate de ruimte die door deze spoorwegen gebruikt werd nog beschikbaar is, heb ik meerdere lijnen over deze routes geleid.

# Lijnnummering en -ontwerp

Het netwerk kent twee lijntypes: `Regionale en stadslijnen`

## Regionale lijnen

Deze lijnen zijn geletterd `A-P`, gesorteerd op de lengte van de lijn. 
Een lijn kwalificeert als regionale lijn als die meerdere agglomeraties doorkruist. 
Deze lijnen maken ook het meest gebruik van bestaande vrije banen,
dit kan een voormalige spoorlijn zijn, 
maar kan ook parallel aan een bestaande spoorweg liggen.
Ook busbanen kunnen gebruikt worden als vrije baan.

## Stadslijnen

Stadslijnen beperken zich tot één agglomeratie, gebruiken busbanen waar mogelijk. Elders zullen ze op of langs straten rijden. In enkele gevallen kan een viaduct of tunnel voorkomen.
De trams op deze lijnen zullen een hogere doorstroomcapaciteit hebben, wat in de praktijk vooral betekent dat er veel staanplaatsen en deuren zullen zijn. (Denk aan de Utrechtse Sneltram)

Elk van deze lijnen is genummerd met 2 cijfers, waarvan de eerste aangeeft in welke stad de lijn ligt:

  - 10 - Eindhoven
  - 20 - Tilburg
  - 30 - Breda
  - 40 - 's-Hertogenbosch
  - 50 - Helmond
  - 60 - Roosendaal
  - 70 - Bergen op Zoom
  - 80 - Oss
  - 90 - Oosterhout

### Ringlijnen

Ringlijnen beginnen altijd met een `R`, gevolgd door de eerste letter van de stad, waarna een getal komt.
Oneven getallen rijden met de klok mee, even getallen rijden tegen de klok in.

`bv. RE1 rijdt met de klok mee door Eindhoven`

# Netwerkoverwegingen

Gedurende het ontwerpproces moest ik uiteraard overwegen waar de lijnen te tekenen.
In steden betekende dit meerdere radiale en tangentiële (orbitale) lijnen maken om tot een goed verbonden netwerk te komen. Hierbij kwam steeds de keuze van welke straten te gebruiken. Uiteraard moesten belangrijke gebouwen zo veel mogelijk verbonden worden.

Met de regionale lijnen was het steeds van belang om het al bestaande spoornet in het achterhoofd te houden. Het regionale tramnet heeft als bedoeling juist de plekken zonder bestaande spoorverbindingen een verbinding geven.
Dit is waar de eerdergenoemde voormalige spoorlijnen te pas komen. Deze oude vrije banen zijn met name op lijn `A`, `B`, `H` & `J` gebruikt.
Hiermee hebben vooral Uden, Veghel en Schijndel een verbetering van OV-verbindingen gekregen.
Andere overwegingen bij de regionale lijnen waren de stopafstand binnen woonplaatsen en of bestaande wegen gebruikt moeten worden, of dat er een directere route genomen moet worden.

# Gebruikte Tools

Als eerste stap in het ontwerpproces heb ik de kaarttegels van [OpenTopoNL](https://www.imergis.nl/htm/opensimpletopo3200.htm) gedownload. Op deze geografische kaart kon ik in Adobe Illustrator de lijnen gaan tekenen.

Hierna ben ik begonnen aan kleine kaarten voor elke stad binnen de Provincie. 
Deze heb ik uiteindelijk gecombineerd tot één grote kaart voor de gehele provincie. 
Echter was dit slechts een eerste versie. De kaart was zeer ruim opgezet.
Hierna ben ik dus aan de huidige versie begonnen, waarin de lijnen een stuk compacter zijn.
Deze kaart was in één keer ontworpen, met Eindhoven Centraal als startpunt, vanuit waar ik de kaart steeds verder uit kon werken.

Als laatste is het halteregister in Excel gemaakt. Hiervoor is de layer-data uit een `.svg`-bestand gebruikt.