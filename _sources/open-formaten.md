# Open formaten

## PDF

:::{figure} figs/open-vorm-pdf.png
:width: 400
:align: right

PDF in verschillende contexten
:::

Het PDF-formaat is niet open:

* de vorm blijft dezelfde, ongeacht de context
* de inhoud is niet aan te passen
* je kunt geen afgeleide versie maken

Het PDF-formaat is niet geschikt als bron-formaat voor open leermaterialen.
Als publicatieformaat (eindproduct) is het PDF-formaat wel relevant.

## Word

:::{figure} figs/open-vorm-word.png
:width: 400
:align: right

Word in verschillende contexten
:::

Het formaat van Word (of van een andere tekstverwerker) is gebaseerd op "WYSIWYG".
Voor eenvoudige documenten is dit gemakkelijk voor de gebruiker.
Voor complexe documenten, of documenten die er in verschillende omgevingen anders moeten uitzien, is dat minder geschikt.

Het Word-formaat is minder geschikt als bron-formaat voor open leermaterialen.
Als publicatie-formaat is het wel relevant.

## HTML

:::{figure} figs/open-vorm-html.png
:width: 400
:align: right

PDF in verschillende contexten
:::

* gebaseerd op platte tekst; "codering" van elementen
* scheiden van inhoud en opmaak
* je kunt eenvoudig metadata aan documenten of onderdelen toevoegen.

"Platte tekst" is in het algemeen geschikt als interface tussen mens en computer: het is door beide goed te verwerken. Voorbeelden hiervan zijn:

* HTML, CSS (voor het beschrijven van een web-pagina)
* JSON (voor het beschrijven van data)
* programmeertalen

### Codering van elementen

### Scheiden van inhoud en opmaak

HTML beschrijft de inhoud en de structuur, onafhankelijk van de vorm (opmaak).
Voor de beschrijving van de vorm gebruik je CSS-bestanden.
Dit betekent dat je dezelfde inhoud op verschillende manieren kunt vormgeven, bijvoorbeeld in verschillende contexten.
Als de huisstijl van je organisatie verandert, kun je de vormgeving aanpassen zonder dat je de bestanden met de inhoud hoeft aan te passen.

:::{admonition} Voorbeeld: CSS Zen garden
Een grote reeks voorbeelden hoe je met CSS een volstrekt andere opmaak voor dezelfde inhoud kunt maken vind je op de website [CSS Zen garden](http://www.csszengarden.com).
:::

:::{admonition} Voorbeeld: Wikipedia
Als je als gebruiker ingelogd bent bij Wikipedia, dan kun je je eigen weergave-formaat ("skin") instellen. Je kunt kiezen uit 5 skins; en daarnaast kun je nog je eigen CSS en JavaScript opgeven.
:::