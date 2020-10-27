# Eindwerk Serge Steenland

## Beschrijving

Het is de bedoelig dat ik een PLYO Box maak waar al een muziek installatie in zit, zodoende dat trainen op de box net iets leuker word.

Een PLYO Box dient om op te sporten heeft verschillende hoogtes naar gelang je hem plaatst.

De box moet stevig zijn daar hij onder andere gebruikt wordt om op te springen en van te springen.

Wat zeker aan bod komt is:
* Prototyping
* Tekenwerk
* CNC gebruik
* lasergraveren
* 3D printing
* waarschijnlijk Elektronica

## Uitwerking

Eerst heb ik het idee een beetje uitgewerkt en de mogelijkheden bekeken van wat kan en wat de box zou verzwakken.

Het idee om een logo in plexi er in te verwerken bv. Zou de box zeker verzwakken en heb ik dan ook geschrapt uit de lijst

Een muziek systeem inbouwen was dan wel een optie daar ik de luidsprekers in de middenplaat kan monteren dat niet echt de stevigheid zal verminderen.

Om geen hinder in het hebruik van de box te hebben, verkies ik om de bediening binnenin te monteren met toegang van de bediening via de uitsparingen voor handvaten.

## prototyping

Ik heb de box geschaald en gelaserd om te zien of het op die correct was gemaakt

<img src="{{site.baseurl }}/assets/PLYO_Box_Schaal.jpg" width="40%">

## Fusion 360

Daar ik al vertrouwd ben met Fusion360 is dit het programma waar ik mijn tekeningen zal in maken.

<img src="{{site.baseurl }}/assets/3DPlyoboxFusion.jpg" width="40%">

[Fusion file PLYO_BOX v15](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/freemans16/fabzero-Serge/blob/master/assets/PLYO_BOX%20v15.f3d)

Door beperking in vervoer heb ik alles op 3 halve multyplex platen getekend om uit te frezen.

## CNC frezen

Het frezen is met een upcut 8mm gedaan voor de snelheid wat te vergroten van het uitsnijden. Dit resulteerd wel dat de hoekjes met een beitel moet worden bijgewerkt, kan ook met Micky Mous oortjes maar wilde geen openingen in de hoekjes.

<img src="{{site.baseurl }}/assets/20201008_171624.jpg" width="40%">

Het frezen heb ik in Mam gedaan met de Yeti. Plaat moest zeer haaks liggen en het nulpunt zeer correct ingesteld zijn daar de tekening redelijk dicht bij de zijkanten getekend was voor optimaale plaat benutting te hebben.

Ik had alles al eens laten berekenen door het programma Deepnest. Dat zorgt er voor dat je de stukken optimaal kan schikken op je plaat.

Ik heb dan ook de platen in fusion bij getekend en de zijden over de plaaten verdeeld zoals ze in deepnest berekend waren.

Wel heb ik gezorgd dat er voldoende ruimte tussen de verschillende zijden was om de frees te laten passeren zonder dat de stukken los gingen komen.

<img src="{{site.baseurl }}/assets/fusionManufacturing.jpg" width="40%">

### Yeti cnc

Opzetten van de Yeti cnc: eerst exporteren van grbl g_code en op usb gezet om over te brengen.

Plaat van 122 cm op de waste board gelegd met plaats om er voor en er na een stuk hout te leggen van de zelfde dikte en dat omdat de yeti het opervlakte gebruikt om over te rijden en omdat er niet veel ruimte over is op de plaat.

eerste zijden waren de twee zijkanten en middenstuk.

<img src="{{site.baseurl }}/assets/ZijpannelenCnc.jpg" width="40%">

Vervolgens ook de andere kanten op de zelfde mannier gedaan.

Ondertussen was het tijd om de luidsprekers te monteren in het middenstuk.

<img src="{{site.baseurl }}/assets/MiddenpanneelMetLuidsprekers.jpg" width="40%">

Dit was een perfecte maat.

Ondertussen de bedrading van de luidsprekers naar een filter om de juitse klank naar de juiste luidsprekers te sturen en daarna ook een stuurprint er aan te monteren.

Ik heb dan gekozen om de sturing te voeden met een lithium baterij. Dit om geen bekabeling buiten de box te hebben.

Dus was alles klaar voor de eerste test

<img src="{{site.baseurl }}/assets/middenstuk.jpg" width="40%">

Test op baterij werkte naar wens, verbinding via bluetooth was ook goed.

### Montage

Nu kwam de tijd om alles samen te brengen.

Eerst heb ik het frame samen gezet met klemmen om alles mooi voor te boren tegen splitten. dus het schroefgat met een 2mm en de eerste laag met een dikte die net iets groter was dan de schroef zelf om een goede verbinding te kunnen maken.

<img src="{{site.baseurl }}/assets/opbouw2.jpg" width="40%">

daarna nog een stukje verzonken zodoened de kop iets in het hout zou zitten.

Nadien alles eerst verlijmd en ook twee balkjes voorzien om de middenplaat in vast te schroeven zodoende die eventueel er terug uit kan indien nodig.

<img src="{{site.baseurl }}/assets/opbouw1.jpg" width="40%"><img src="{{site.baseurl }}/assets/opbouw3.jpg" width="40%">

De ene kant met handvat word niet verlijmd om toegang te krijgen tot de sturing moest er iets mis lopen.

Niet tegen staand zit hij redelijk klem zonder schroeven (pressfit) en eenmaal hij geschroefd is zal hij zeker niet los komen in gebruik.

<img src="{{site.baseurl }}/assets/opbouw4.jpg" width="40%">

## 3D Printen Tinkercad en fusion 360

### Tinkercad

Ik heb een bestaande doos die gemaakt was voor de XH M422 (audio versterker die ik gebruik) geïmporteerd in tinkercad en aangepast naar wat ik nodig heb.

<img src="{{site.baseurl }}/assets/tinkercad.jpg" width="40%">

### slicer

Als slicer gebruik ik Chitubox, Deze slicer is geschilk voor SLA printers en daar de opervlakte er net op kan is dat mijn voorkeur printer

<img src="{{site.baseurl }}/assets/slicer.jpg" width="40%">

Als printer gebruik ik de Elegoo Mars met een blauwe transparante ABS like resin.

<img src="{{site.baseurl }}/assets/elegooMars.jpg" width="40%">