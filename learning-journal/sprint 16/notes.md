# Week 1

## 📆 Maandag 12 november

## Wat heb ik vandaag gedaan?

Sprintplanning Sprint 16 - Don't Repeat Yourself
Over component library & Quality Assurance

Dit is wat wij deze sprint moeten doen, naast de deeltaken i-love-web en javascript-fundamentals:

- Leertaak: Dont Repeat Yourself Component Library. Je leert hoe je herbruikbare stukken code op een systematische manier ontsluit zodat jij en jouw mede frontenders ze kunnen gebruiken in andere projecten.

- Deeltaak: Component Building Block. De focus ligt op het ontwerpen en bouwen van een robuust, goed werkend component, waarin de belangen van de eindgebruiker centraal staan. Denk aan Responsive, Accessible, Performing & Progessive Enhanced (RAP/PE). (Dit moet vrijdag af zijn voor de code/design review)

Dit waren de opdrachten die wij voor vandaag kregen om in teamverband bespreken en er daarna individueel aan de slag te gaan:

- Opdracht: Identificeer jouw componenten Analyseer jullie website en identificeer componenten die niet té complex zijn maar ook niet té eenvoudig zijn. Zorg minimaal voor interactie. Ideeën? Formulieren, tabbed content, carrousel, zoeken/filters, navigatie, favorieten, comments, etc.

- Opdracht: Morphological chart. (Dit moet voor woensdag af zijn)

Wat is een morphological chart? They are used in product design and are particularly useful to come up with unexpected alternatives for complex designs. Their origin lies in the field of industrial product design.

Benodigdheden:

- Wil om veel varianten van een app te bedenken
- Een systematische manier van werken
- Maak minstens 8 variaties voor jouw component. Zoek variaties door een goede morphological chart te maken. Werk daarna verschillende versie van je component uit in Figma. Dit moet woensdag af.

## Wat heb ik vandaag geleerd?

Component Library: Verzameling vooraf gemaakte, geteste en goed gedocumenteerde UI-componenten die eenvoudig kunnen worden hergebruikt in de gebruikersinterface van een product. Het zorgt ervoor dat het product een consistente uitstraling en gevoel heeft en bevordert efficiëntie en schaalbaarheid

Met component libraries kunnen ontwerpers en ontwikkelaars snel nieuwe functies en pagina’s toevoegen, terwijl de algehele ontwerp consistentie en kwaliteit behouden blijft - quality assurance

### Hoe werkt dit in Sveltekit?

Elke `$lib` is in principe een component library. Je kan ook een externe library aanmaken door middel val npm packages en dit installeren in je project met `npm install`.

## 📆 Dinsdag 13 november

## Wat heb ik vandaag gedaan?

## 📆 Woensdag 14 november

## Wat heb ik vandaag geleerd?

### College: Typografie in Web Design

Typografie en fonts

Variable Fonts
Handig om Variable fonts te gebruiken, bijvoorbeeld om te animeren.

Wakamaifondue.com: geeft je inzichten in hoe deze font een variable axes heeft, om daarmee te animeren.

Bekijk verschillende fonts om te kijken welke je wilt gebruiken. Ook handig om te kijken hoe het staat met wit op zwart & zwart op wit.

Web Design is 95% typography.

- Micro typography: font-variation-settings, word-spacing, letter-spacing
- Macro-Typography: type font, size, hierarchie, line-height, columns

Font-property in CSS: een shorthand om de font te definiëren, voor bijvoorbeeld de body (DRY!).

Om een font te laten zien aan iemand, kan je een downloaded font gebruiken. Een installed font is op bijn alle operating systems te zien, dit kan gebruikt worden als fallback font. sans-serif & monospace is een generic font-family is op alle beschikbaar, als dit niet zo is doet de browser de fallback automatisch.

Met CSS Font Stack kan je kijken of fonts web safe zijn, die pre-installed zijn bij veel operating systems.

Het monospaced lettertype zorgt ervoor dat elke letter en cijfer dezelfde breedte heeft.

Opdracht: Variable fonts animeren met CSS

1. Check de fonts die je nu in je project hebt met wakamaifondue. Bestudeer de eigenschappen van de fonts: Wat voor fonts gebruik jij in je project? WOFF? WOFF2? Hoeveel KB?
2. Is een van de fonts een variable font? Zo niet, zoek dan een variable font om mee te animeren. Bv op google fonts
3. Analyseer de variable axes van het variable font
4. Maak de HTML, laad het font en gebruik de font-variation-settings in CSS om het font te laten animeren.

## Typografie en Hierarchie

Visuele Hiërarchie

- Grootte
- Positie op het scherm
- Witruimte
- Kleur / contrast
- Animatie

### The inverted pyramid of writing

3 niveau's:

- Belangrijkste info
- Belangrijke details
- Achtergrondinformatie

Modular Scale: optimale verhouding tussen font-sizes.

Opdracht: Varieren met hiërarchie en de Modular Scale

Maak in Figma nieuwe variaties van jouw component.

- Gebruik de inverted pyramid of writing om te bepalen wat de belangrijkste informatie, belangrijke details en achtergrondinformatie van jouw component is. Noteer dit in Figma.
- Maak 3 variaties waarbij je verschillende modular scales toepast. Gebruik hiervoor de website Typescale.com. Zet de variaties naast elkaar in Figma en noteer de scale.
- Maak per ontwerp nog 3 variaties waarbij je verschillende posities, witruimte en kleur/contrast gebruikt. Zet deze variaties eronder en noteer wat je hebt toegepast.
- Je hebt nu 9 variaties. Welke werkt het best? Bespreek de variaties met iemand die een ander project heeft. Benoem de scales en visuele hiërarchie en krijg feedback.

## Bronnen

- [Web Design is 95% Typography](https://ia.net/topics/the-web-is-all-about-typography-period)
- [Word-spacing](https://developer.mozilla.org/en-US/docs/Web)
- [Font property](https://css-tricks.com/almanac/properties/f/font/)
- [CSS Font Stack](https://www.cssfontstack.com/)
- [Font-face](https://css-tricks.com/snippets/css/using-font-face-in-css/)
- [Variable Fonts](https://variablefonts.io/)
- [Wakamai Fondue](https://wakamaifondue.com/)
- [Interactivity and Animation with Variable Fonts](https://24ways.org/2019/interactivity-and-animation-with-variable-fonts)
- [Typescale](https://typescale.com/)

## Wat heb ik vandaag gedaan?

Vandaag heb ik aan de opdrachten gewerkt die tijdens het college gegeven zijn. Bij deze heb ik gekeken naar de typografie en visuele hierarchie van mijn design. Deze punten en feedback heb ik verwerkt om een beter design van mijn component te krijgen. Verder heb ik ook een begin gemaakt met het maken van het component in Sveltekit.

## 📆 Donderdag 14 november

## 📆 Vrijdag 15 november

### Wat heb ik vandaag gedaan?

In de ochtend ben ik gaan mentoren. Hier hebben zij een ander groepje gereviewed over de stylesheet. Ik heb hierbij geassisteerd bij twee groepen en vragen beantwoord, over onder andere code, issues schrijven en design.

## 📆 Maandag 18 november

### Wat heb ik geleerd?

College: Advanced Components Concept

We're not designing pages, we're desigining systems of components.

Component library: een verzameling herbruikbare en generieke componenten die je aan je project kunt toevoegen, er bestaan vele standaard component libraries die je kunt downloaden en gebruiken.

Het gebruik van een component library:

- Versnelt ontwikkeling door hergebruikt
- Zorgt voor consistentie in je projecten
- Vergroot de onderhoudbaarheid

Het gevaar van component libraries:

- Grotere kans op fout
- Alles ziet er hetzelfde uit
- Vergroot de chaos

Chaos bedwingen door:

- Naamgeving van componenten
- Naamgeving van variaties van componenten
- Naamgeving van properties binnen componenten
- Metanaamgeving: componenten, patronen, etc. indeling van de $lib folder

Metanaamgeving = een hierarchische benadering om het over bepaalde soorten componenten te hebben

- Geneste componenten
- Variaties op componenten
- Samengestelde componenten

Structuur

- Pages: volledige pagina's of schermen met een specifieke context bestaand uit sections
- Sections: secties van een pagina bestaand uit componenten
- Components: herbruikbare componenten, zoals buttons, forms.

Voorbeelden van structuren/ indelingen binnen component libraries:

Functional Layering

- Inputs: componenten voor gebruikersinvoer (buttons, forms)
- Display: componenten voor weergeven van informatie (tabellen en grafieken)
- Navigation: componenten voor navigatie (menu, breadcrumbs)
- Structural: layout-elementen die structuur bieden (grids, containers)

LEGO

- Bricks: kleine, niet herbruikbare stukjes (icoon, tekstblokjes)
- Blocks: herbruikbare basis componenten (button of image)
- Assemblage: geocmbineerde componenten met een specifieke functie (form, card)
- Constructions: complexe pagina secties of templates (dashboard)

Atomic Design

- Atoms: basis bouwblokken van je pagina: button, label, input.
- Molecules: een groep atomen bij elkaar, een search form met een input, label en button
- Organism: een groep moleculen die samen een sectie vormen van je website, een header balk met een zoekformulier
- Templates: een group organismen die samen een paginatype vormen
- Pages: ingevulde template met inhoud

Presenter-containers

- Presentational components: UI-specifieke, stateless componenten die bepalen hoe data getoond wordt (bijvoorbeeld image)

- Container components: componenten die de prestational components van data voorzien en hun gedrag bepalen

- Compositions: combinatie van beide die specifieke pagina-secties vormen.

Sveltekit 5

Er is een nieuwe sveltekit versie, waarbij er sommige dingen die wij nu gewend zijn deprecated zijn. Hierbij moeten wij nu werken met `runes` ipv `slots` & `$$restProps`.
Ook het gebruiken van snippets is een nieuwe feature, waarbij je bijvoorbeeld in een if/else statement.

Bronnen:

- [Runes](https://svelte.dev/docs/svelte/what-are-runes)
- [Snippets](https://svelte.dev/docs/svelte/snippet)

### Wat heb ik gedaan?

## 📆 Maandag 20 november

### Wat heb ik geleerd?

The New Responsive

User-preference styles (queries): prefers-contrast, prefers-reduced-motion, prefers-color-scheme
Viewport and form-factor media queries.
Macro layouts: container styles/queries, macro components that contains other components

De anatomie van een media-query

1. Aanroepen van de media query
2. Media types: screen, print, all, etc
3. Media features
4. De conditie waaraan voldaan moet worden

Opdracht: Onderzoek met je tafel bij de media queries specificaties van het W3C welke media features van media queries er zijn in level 3, 4 en 5.

User preference media features level 5

- Prefers-reduced-motion
- Prefers-reduced-transparency
- Prefers-reduced-contrast
- Forced-colors
- Prefers-color-scheme
- Prefers-reduced-data

Prefers-reduced motion: @media (prefers-reduced-motion: no-preference)

Container-Queries & Container-style-queries
Responsive to the form factor

- @media (spanning: single-fold-vertical)
- @media (horizontal-vierport-segments-2)

Opdracht: The New Responsive

Bespreek een strategie hoe je de drie onderdelen kan toepassen op jullie component library

Noteer per onderdeel van het artikel minimaal 1 ding dat je nog niet kent, zoek een bron en maak aantekeningen in je learning journal zodat je het later nog een keer kan onderzoeken.

Bronnen:

- [Responsive Web Design](https://alistapart.com/article/responsive-web-design/)
- [New-responsive](https://web.dev/articles/new-responsive)
- [Using media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries)
- [W3C - Media Queries](https://www.w3.org/TR/mediaqueries-4/)
- [CSS Tricks - Color Scheme](https://css-tricks.com/almanac/properties/c/color-scheme/)
- Codepen Container Queries - Miriam Suzanne

## 📆 Maandag 25 november

### Wat heb ik geleerd?

State Management

- Shared Persistent State

Je wilt niet dat het dingen onthoud die voor alle gebruikers gelden.

- Non Shared Non Persistent State

- Non Shared Semi Persistent State

- Non Shared Persistent State

## 📆 Maandag 2 december

### Wat heb ik geleerd?

Sprint 17: User Needs

Programming Spikes and Creative Coding

Coding Spike: is a type of computer programming in which the goal is to create something to expressive instead of something functional.

Kan de gebruiker verrast worden met een bijzondere interactie?

Deeltaak Creative Coding Spike

- Doe vooronderzoek en bepaal jouw stijl
- Schets jouw concept. Bedenk welke interacties, animaties en geluidsondersteuning je nodig hebt.
- Maak een breakdown Schets
- Implementeer jouw concept
-

## 📆 Woensdag 4 december

### Wat heb ik geleerd?

Compositie in Web Design

## 📆 Woensdag 11 december

### Wat heb ik geleerd?

Kleur in Web Design
