# Week 1

## 📆 Maandag 2/09

### Wat heb ik vandaag gedaan/geleerd?

De eerste dagen stond in het teken van het verkennen van een nieuwe framework, namelijk Sveltekit. Hierbij heb ik vandaag de eerste college gehad over Sveltekit en wat dit precies inhoudt. Hierbij heb ik geleerd dat sveltekit een library is gemaakt in svelte. Hierbij zijn er een aantal kenmerken gegeven:
- Component framework
- Scoped styling
- Folder based routing
- Website werkt ook als JS niet beschikbaar is

### Leervragen

- Hoe kan ik tijdens het opzetten van een nieuw project sveltekit installeren?
- Hoe kan ik sveltekit toepassen in mijn projecten?
- Hoe kan ik een goede workflow voor mijzelf maken dmv projectboard (issues), commits, etc?


## 📆 Dinsdag 3/09

### Wat heb ik vandaag gedaan/geleerd?

Vandaag heb ik zelfstandig een project opgezet en geprobeerd hierbij sveltekit te installeren. Dit heb ik gedaan door de gegeven bron, namelijk de docs van directus. Ook heb ik dmv verschillende bronnen mij ingelezen over Sveltekit om een beter beeld te krijgen hiervan en er enigszins bekend mee te worden.

Ook ben ik begonnen met het maken van ideeschetsen / inspiratie opdoen voor de squadpage & mijn visitekaartje. 

### Leervragen

- Hoe kan ik een database, zoals Directus, koppelen en een server aanmaken?
- Hoe maak ik pagina's aan in sveltekit?
- Hoe link ik naar andere pagina's?


## 📆 Woensdag 4/09 & Donderdag 📆 5/09

### Wat heb ik vandaag gedaan/geleerd?

Vandaag is er een college gegeven hoe ik sveltekit kan installeren in nieuwe projecten en hoe je een opzet hierin kan maken. Hierbij is er verteld hoe je routes kan maken, waar de verschillende mappen voor bedoeld zijn en over het ophalen van data. 

Hierna ben ik in mijn team aan de slag gegaan, er is een design uitgekozen en is er een taakverdeling gemaakt. Hieruit is gekomen om allemaal het design na te maken om ook te oefenen met sveltekit. Ik ben hier ook gelijk mee aan de slag gegaan en heb ik de ``HTML`` en de globale ``CSS``.

### Leervragen

- Hoe maak ik componenten in Sveltekit?

# Week 2

## 📆 Maandag 9/09

### Wat heb ik vandaag gedaan/geleerd?

Vandaag is er een 'Kill Your Darlings' workshop gegeven over Figma. Hier is uitgelegd hoe je componenten maakt en hierbij auto-layout en grid-layout kan gebruiken. 

Daarna hebben mijn team en ik weer verder gewerkt aan de squadpage. Ook hebben we een design gemaakt voor de detailpagina in Figma en ook gelijk toegepast wat er in de workshop werd uitgelegd. 
Ook heb ik vandaag inspiratie opgezocht voor mijn visitekaartje. 

## 📆 Dinsdag 10/09

### Wat heb ik vandaag gedaan/geleerd?

Ik heb verder gewerkt aan de squadpage, hiervoor moesten wij inspo en een design maken voor de detailpagina in Figma. Ook heb ik een design gemaakt voor mijn visitekaartje. 

## 📆 Woensdag 11/09

### Wat heb ik vandaag gedaan/geleerd?

Vandaag is er een college gegeven over Creative Coding in CSS & JavaScript en hoe je hierbij je visitekaartje/squadpage leuker kan maken. Hierbij kan je bijvoorbeeld gebruik maken van CSS scroll-driven animations of in JS animaties. Sveltekit heeft een library met transitions die je hieruit kan importen en gebruik van kan maken. Indien je hierbij client-side JS wilt gebruiken, heb je hiervoor de onMount() functie nodig. 

Ook is er verteld dat het soms handig kan zijn om een frisse en schone omgeving te hebben en om even opnieuw te beginnen. Hierbij is er een stappenplan gegeven hoe dit gedaan kan worden: 

1. Maak een tijdelijke kopie van de folder van de squadpage repo
2. Installeer een clean install van sveltekit voor de squadpage
3. Voeg in /routes/+page.js deze regel code toe: ``export let csr = false``
4. Neem in ``/lib/fetch-node.js`` de code over uit hetzelfde bestand van je laatste node.js project van sprint 12
5. Importeer deze function in ``/routes/+page.server.js``
6. Check aan de hand van het voorbeeld of je alles goed gedaan hebt
7. Copy/paste als laatste jullie toegevoegde svelte code terug in ``/routes/+page.svelte``

## 📆 Donderdag 12/09

### Wat heb ik vandaag gedaan/geleerd?

Vandaag ben ik verder gegaan met mijn visitekaartje en ben ik bezig geweest met de styling hiervan. 

## 📆 Vrijdag 13/09

### Wat heb ik vandaag gedaan/geleerd?

Eerst heb ik een we love web gevolgd van Vasilis van Gemert over dat je met code helemaal los kan gaan en dus in website dit ook kan hanteren en dat er geen eentonige websites meer komen. Ook heeft hij het even gehad over hoe belangrijk toegankelijkheid is. 

Hierna hebben wij een code/design review gehad en andere teams gereviewed. 

# Week 3

## 📆 Maandag 16/09

### Wat heb ik vandaag gedaan/geleerd?

Vandaag heb ik een workshop Samenwerken & Prioriteren gekregen en heb ik geleerd hoe je van een epic --> (user) stories --> tasks in projectboard. Epics zijn een handige manier om werk te organiseren en een hiërarchie te creëren, het idee is om werk op te splitsen in opleverbare stukken, zodat grotere projecten kunnen worden afgerond en klanten op regelmatige basis waarde krijgen. Vorm van userstories:

Als … , wil ik … , om (te) …

Vervolgens hebben mijn team en ik dit gehanteerd in ons projectboard en hier meer tasks in gedaan aan de hand van het gegeven college en deze labels aan gegeven met de Moscow methode en planningpoker. 

## 📆 Dinsdag 17/09

### Wat heb ik vandaag gedaan/geleerd?

Vandaag ben ik aan de slag gegaan met een feature in de detailpagina. Hierbij heb ik de HTML met daarin de opgehaalde data met de CSS. 

## 📆 Woensdag 18/09

### Wat heb ik vandaag gedaan/geleerd?

Vandaag stond in het teken van een wrap-up van het project en hebben wij met zn alle besproken hoe je het project oplevert bij de opdrachtgever:

**Code:**

- gestructueerde code (conventies)
- semantiek
- geen comments
- geen console.log()
- goede tabs

**Readme.md:**

1. kenmerken 
2. livelink 
3. visuals
4. instructies 
5. installatiehandleiding 
6. CMS uitleg 
7. huisstijl 
8. bijdragen (hints voor volgende dev-teams) 
9. bronnen 


**Live zetten:**

- Github pages
- Vercel
- Netlify

Vervolgens hebben wij met het team alle feature branches naar de main gemerged en issues gesloten. 

# Week 2

## 📆 Maandag 23/09

### Wat heb ik vandaag geleerd?

Een Jamstack is een manier om websites te bouwen die sneller, veiliger en schaalbaar zijn. Een Jamstack is onderverdeeld in twee groepen:

- Site Generators: Sveltekit, Astro, etc.
- Headless CMS: Prism, Hygraph, Directus, etc.

### Wat heb ik vandaag gedaan?

Vandaag ben ik begonnen met het opzetten van een nieuw project (WOGO). Zo hebben we een projectboard opgesteld, team canvas opgesteld, briefing opstellen en het project werkend proberen te krijgen, dit is nog niet helemaal gelukt, aangezien wij moeten doorwerken op code wat vorig jaar is gemaakt en wij hiervoor een API Key voor nodig hebben. 

Het is ook de start van het mentorprogramma voor jaar 1. Hierbij hebben wij uitleg gekregen wat het inhoudt om een mentor te zijn en wat de verantwoordelijkheden zijn:

* Je helpt in een workshop als de studenten een opdracht hebben gekregen
* Je doet code/design reviews op leertaken
* Je beantwoordt vragen over HTML, CSS en JS
* Je geeft in Portflow feedback op reflecties van eerstejaars en bespreekt hun bewijslast


## 📆 Dinsdag 24/09

### Wat heb ik vandaag gedaan?

Vandaag heb ik aan de laatste dingen verder gewerkt voor het opzetten van het project. Wij kregen van Joost ook de API Keys die we in de .env bestand kunnen zetten, alleen krijg ik nog steeds een `Bad Request`. 
Verder ben ik begonnen aan het ontwerpen van mijn i-love-web pagina. 


## 📆 Woensdag 25/09

### Wat heb ik vandaag geleerd?

Over hoe het structureren en organiseren van informatie op de frontend invloed heeft op de Content modelling van je (headless) CMS (Informatie Architectuur)

### Wat heb ik vandaag gedaan?

Vandaag heb ik met mijn team een data model & site map gemaakt, om inzicht te krijgen over de informatie architectuur. 

## 📆 Donderdag 26/09

### Wat heb ik vandaag gedaan?

Vandaag stond de briefing op de planning met WOGO. Hier is de opdracht uitgelegd en wat zij voor ogen ziet. Hier hebben wij nog wat vragen gesteld om de opdracht duidelijker te maken. Aan de hand van de briefing hebben wij de debriefing gemaakt en opgestuurd. Hierna hebben wij ook de taken gemaakt aan de hand van de user stories en deze verdeeld. 

## 📆 Vrijdag 27/09

### Wat heb ik vandaag gedaan?

Vandaag hebben wij samengezeten met docenten om feedback te krijgen op ons projectboard 

Feedback: Taken die groot worden ingeschat zoals 8 en 13 kun je het beste opsplitsen in kleinere taken. Dit zorgt voor overzichtelijke pull requests en dat het werk goed verdeeld kan worden.


## 📆 Maandag 30/09

### Wat heb ik vandaag geleerd?

Frameworks hebben vaak een vaste structuur. 

- Structuur  

- Project 
    - Src
            - Lib
        - Routes 
        - app.html 
    - Static
        - Afbeeldingen  
        - Favicon 
        - Global.css 
    - .gitignore 
    - .env 
    - .env.example 
    - package.json
    - Svelte.config.js
    - vite.config.js


- Routing 

Twee types routes:
- Static 
- Dynamic: [id]


- Error handling
    - +error.svelte

```
Import { page } from ‘$app/stores

<p> {$page.status} | {$page.error.message}
```
Layouts kun je nesten.
De error page pakt nog steeds je layout file.

- Loading data 

```
Export async function load () {
 Return {

  }
}
```
Serverside kan je werken met een api key 

- Binding 

```
Script 
Let name = ‘world’
$: shout = name + ‘ rocks!’

<input bind: value={name}

<h1> Hello {name} <h1>
```

- Library & Components

Header.svelte 
```
Export { default as Header } from ‘./Header.svelte’
```
```
+layout.svelte
Import {header from’ $lib’

Import {Header from’ $lib’
```

VScode: settings > workbench > editor management > label format > short of medium
Voordat je het live zet: check of alles er goed uit ziet door eerst npm run build te doen en vervolgens npm run preview.



### Wat heb ik vandaag gedaan?

Vandaag hebben wij een meeting gehad met Joost om te kijken waarom er steeds een `Bad Request` gegeven wordt, blijkbaar zaten wij in de verkeerde branche en moesten wij de branche ‘release-candidate’ overnemen. 

## 📆 Dinsdag 1/10

### Wat heb ik vandaag gedaan?

Vandaag ben ik aan de slag gegaan met het maken van designs van de twee pagina’s.


## 📆 Woensdag 2/10

### Wat heb ik vandaag geleerd?

Hoe je kritisch kan kijken naar een design op basis van 10 principes van Dieter Rams en hiermee feedback geeft

De 10 principes: 

* Good design is innovative
* Good design makes a product useful
* Good design is aesthetic
* Good design makes a product understandable
* Good design is honest
* Good design is unobtrusive
* Good design is long lasting
* Good design is thorough down to the last detail
* Good design is environmentally friendly
* Good design is as little design as possible


### Wat heb ik vandaag gedaan?

Met wat ik vandaag heb geleerd heb ik met de workshop Design Critique feedback gegeven op designs van andere projecten. Ook hebben we met team WOGO met Justus gezeten om meer inzicht te krijgen over contentful. Hierna hadden we een iets beter beeld over hoe het is ingedeeld en hoe de code is opgebouwd. 


## 📆 Vrijdag 4/10


### Wat heb ik vandaag gedaan?

In de ochtend ben ik mentor geweest voor eerstejaars en hebben wij besproken hoe zij de Layout In CSS opdracht hebben uitgewerkt. Zo hebben we ieders code vergeleken en van elkaar geleerd. Hierna heb ik wat issues ingeschoten over de code die zij hebben geschreven voor hun project. 
Daarna hadden Patrick en ik een design review bij docenten en hebben hier feedback op gekregen, voornamelijk over de informatie architectuur van de website. We kregen wel complimenten over het design. 


## 📆 Maandag 30/09


### Wat heb ik vandaag gedaan?

Vandaag heb ik de feedback van mijn design verwerkt en begonnen met het testen van de website die er al staat, om deze punten te verbeteren. 

## 📆 Dinsdag 1/10

### Wat heb ik vandaag gedaan?

Vandaag ben ik bezig geweest met mijn i-love-web site om vooral de lay-out te maken en onderzocht hoe ik markdown files kan renderen op de website. 


## 📆 Woensdag 2/10


### Wat heb ik vandaag geleerd?

Wrap-up:

* Refactored Code: gestructureerde code (conventies), semantiek, geen commented code, geen console.log(), goede tabs, een versie release, goede pull request strategie, components, linter installeren
* Readme.md: Kenmerken, live link, screenshot(s?), Instructies (uitleg over het gebruik), Installatiehandleiding, CMS Uitleg, Huisstijl (of waar die te vinden is), bijdragen? (hints voor volgende dev-teams), gebruikte bronnen, badges met gebruikte technologie, link naar projectboard, introductie, licentie, changelog (o.b.v. versies)
* Testen: performance, keyboard, screenreader, lighthouse, kleurcontrast, WCAG, html validator, user test, browsertest, devicetest, css validator
* Klant: vragen wat zij willen
* Live zetten: Github pages, Vercel, Netlify, onrender

Sprint review: Kijken we je gedaan hebt en hoever je bent met de opdrachtgever

Doel:
* Specifieke vragen bedenken voor feedback
* Specifieke vragen stellen om feedback te krijgen
* Agenda maken
* Demo:
    * Langs user stories gaan van deze sprint
    * Website laten zien, naast het design
    * Laten zien wat er nog niet is gelukt a.d.h.v het design
    * Tijdens de demo benadrukken wat de punten zijn waar je feedback op wilt
    * Doe het met enthousiasme 😎
* Voorstel om een functionaliteit beter te maken (feedback geven aan de opdrachtgever)
* Uitkomst van testen bespreken, bijv over huisstijl en kleurcontrast
* Plan voor de komende sprint- Werk opleveren + de vraag hoe willen jullie het hebben

Rollen:
* Presentator
* Feedback verwerker, notulist (verwerkt ook in issues)
* Cheerleader
* Timekeeper
* Testen: performance, screenreader, key-board test, device test, browser test, kleurcontrast, WCAG, html validator, usertest.

Aan de klant vragen hoe zij de oplevering willen

* Live zetten: github pages, Vercel, Netlify, onrender

### Wat heb ik vandaag gedaan?

Vandaag ben ik begonnen met het maken van de Walks pagina. Wanneer ik wilde beginnen kwam ik een bug tegen, omdat de links waren veranderd in contentful. Na dit gewijzigd en opgelost te hebben ben ik begonnen met de tabs van de verschillende steden. 

## 📆 Donderdag 3/10

### Wat heb ik vandaag gedaan?

Vanochtend heb ik de sprint review gehad met mijn projectteam, we hebben best goede feedback ontvangen: 

Algemene feedback:
* Met design zijn jullie goed op weg, merk ook dat jullie de opdracht goed begrijpen
* Werk meer met icons en minder tekst, dit is begrijpelijker voor de gebruiker/klant.

Persoonlijke feedback:
* Het design van de pagina's zien er goed uit, homepagina ziet er ook netjes uit!
* Op de walks pagina zijn de tabs een goed idee, is het een idee dat wanneer je in de navigation er op hovert er dan ook de steden tevoorschijn komen en dan op de gewenste stad kan klikken?
* Het carroussel component behouden ipv onder elkaar op de homepagina
* Het tweede design van de card is duidelijker, alleen nog kijken waar de 'NEW' label geplaatst kan worden
* De animaties op de pagina zou zij graag willen behouden

Vragen:
Welke benaming is beter in de nav en op de pagina?
* Het is duidelijker als je cocktail walks of tours gaat gebruiken.

Volgende sprint
Voor de volgende sprint is het de bedoeling dat beide teams verder gaan werken op ons design. Ook is het dan de bedoeling dat we de pagina's gaan verdelen en dezelfde styleguide gaan aanhouden.


# Sprint 15

# Week 1

## 📆 Maandag 14/10

### Wat heb ik vandaag geleerd?

Vandaag was de springplanning van sprint 15, choices, choices. Justus heeft de opdracht uitgelegd en meer informatie gegeven over de vrije ruimte en de meesterproef. 

Tijdens deze sprint:
* Onderzoek je een nieuwe tech-stack voor het ontwerpen en bouwen van een website voor een opdrachtgever
* Verantwoord en presenteer je jouw gemaakte keuze

    * Je kan 10 weken of 20 weken stage lopen. Wanneer je 20 weken stage volgt dan doe je je meesterproef bij je stage. 
    * Je kan ook een schakelprogramma doen naar CMD, denk hier wel aan dat sommige indicatoren hier niet haalbaar zijn
    * Ook kun je FDND-Agency gaan doen, meer eigen verantwoording, je brengt de websites naar publicatiegereedheid
    * Bewijslast voor midterm en endterm is volledig je eigen verantwoordelijkheid

* Tech-stack:
    * React is handig om te kennen, er is veel werkgelegenheid in
    * Factors for choosing a tech-stack:
        * Platform
        * Project type
        * Scalability
        * Performace
        * Team Experience
        * Maintenance
        * Cost
        * Size 
    * User Experience, Developer Experience, Development Experience 
    * De combinatie van user experience, content-management-experience & developer-experience wegen mee bij de keuze voor een tech-stack
    * Optioneel: andere Headless CMS


### Wat heb ik vandaag gedaan?

In de ochtend ben ik mentor geweest bij de eerstejaars, zij hadden de springplanning over All Human, over toegankelijkheid. 

De opdracht was om een nieuwe tech-stack te kiezen voor het ontwerpen en bouwen van een website voor een opdrachtgever. Werk aan dezelfde epic als in sprint 14, maar dan met een ander framework en/of headless CMS en/of andere tooling.
Ik heb gekozen voor het framework Astro, met dezelfde Headless CMS, namelijk Contentful. Ik heb de documentatie doorgelezen van Astro om te kijken wat dit framework voor staat en wat het kan doen. 


## 📆 Dinsdag 15/10

### Wat heb ik vandaag gedaan?

Vandaag heb ik het project opgezet met Astro, hierbij heb ik het stappenplan in de docs voor gebruikt. Ook heb ik de mappenstructuur, in hoeverre dat kan, opgezet. Dit is vergelijkbaar met Sveltekit, alleen is er een andere naamgeving ervoor. 


## 📆 Woensdag 16/10

### Wat heb ik vandaag geleerd?

Er waren vandaag 2 talks van Kevin Lewis (Directs) & Shyanta (Triple). Hierbij hebben zij beide gepraat over het maken van een keuze voor de tech-stack en welke zij gebruiken. 

### Wat heb ik vandaag gedaan?

Vandaag ben ik begonnen met het koppelen van mijn Headless CMS. 

## 📆 Vrijdag 18/10


### Wat heb ik vandaag gedaan?

Vandaag heb ik de we-love-web bezocht van Dion Pieters en hebben wij een code/design-review gehouden

# Week 2

## 📆 Maandag 21/10


### Wat heb ik vandaag gedaan?

Vandaag ben ik bezig geweest met het schetsen van mijn ontwikkeling, het maken van mijn praatplaat tijdens de workshop Visual Thinking. Ook hebben wij in de squad besproken over de do’s & dont’s tijdens het mentoren van eerstejaars. 

### Wat heb ik vandaag geleerd?

Mentoring Do's:
* Weet waar de les over gaat, zodat je actief mee kan doen
* Pro actieve houding, vragen stellen, erbij gaan zitten
* Vragen met een tegenvraag beantwoorden, mensen op weg helpen naar het antwoord zonder het voor te kauwen
* Bewust informatie doseren, neem niveau mee in feedback in geedback geven. Constructieve feedback. Houd het klein.
* Feedback in issues schrijven maar ook mondeling uitleggen. Geef ook een bron mee
* Communiceren over planning met docenten
* Kijk naar mentor planning, letten op diversiteit. Let op samenstelling van de mentoren
* Sandwichmethode van feedbackgeven: Tip, top, tip
* Als mentor hoef je niet alles te weten, je kunt samen op zoek gaan naar het antwoord
* Feedback vragen aan studenten over het mentoren

Mentoring Don'ts:
* Te streng zijn
* Afdwalen en op teveel feedback geven
* Lang wegblijven en niet de halve les wegblijven
* Niet aanwezig / te laat komen
* Mensen afkraken
* Niet geïrriteerd reageren


## 📆 Dinsdag 22/10

### Wat heb ik vandaag gedaan?

Ik heb onderzoek gedaan naar mijn tech-stack en hier argumenten voor genoteerd en heb ik mijn portflow bijgevuld. 


## 📆 Woensdag 23/10

### Wat heb ik vandaag geleerd?

Er waren vandaag 2 talks van Kevin Lewis (Directs) & Shyanta (Triple). Hierbij hebben zij beide gepraat over het maken van een keuze voor de tech-stack en welke zij gebruiken. 

### Wat heb ik vandaag gedaan?

Ik heb de schets-je-ontwikkeling deeltaak afgemaakt met mijn praatplaat. 







