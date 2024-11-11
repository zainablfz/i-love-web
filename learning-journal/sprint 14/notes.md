# Week 1

## 📆 Maandag 23/09

### Wat heb ik vandaag geleerd?

Een Jamstack is een manier om websites te bouwen die sneller, veiliger en schaalbaar zijn. Een Jamstack is onderverdeeld in twee groepen:

- Site Generators: Sveltekit, Astro, etc.
- Headless CMS: Prism, Hygraph, Directus, etc.

### Wat heb ik vandaag gedaan?

Vandaag ben ik begonnen met het opzetten van een nieuw project (WOGO). Zo hebben we een projectboard opgesteld, team canvas opgesteld, briefing opstellen en het project werkend proberen te krijgen, dit is nog niet helemaal gelukt, aangezien wij moeten doorwerken op code wat vorig jaar is gemaakt en wij hiervoor een API Key voor nodig hebben.

Het is ook de start van het mentorprogramma voor jaar 1. Hierbij hebben wij uitleg gekregen wat het inhoudt om een mentor te zijn en wat de verantwoordelijkheden zijn:

- Je helpt in een workshop als de studenten een opdracht hebben gekregen
- Je doet code/design reviews op leertaken
- Je beantwoordt vragen over HTML, CSS en JS
- Je geeft in Portflow feedback op reflecties van eerstejaars en bespreekt hun bewijslast

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

# Week 2

## 📆 Maandag 30/09

### Wat heb ik vandaag geleerd?

Frameworks hebben vaak een vaste structuur.

- Structuur

- Project

  - Src - Lib
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

- Good design is innovative
- Good design makes a product useful
- Good design is aesthetic
- Good design makes a product understandable
- Good design is honest
- Good design is unobtrusive
- Good design is long lasting
- Good design is thorough down to the last detail
- Good design is environmentally friendly
- Good design is as little design as possible

### Wat heb ik vandaag gedaan?

Met wat ik vandaag heb geleerd heb ik met de workshop Design Critique feedback gegeven op designs van andere projecten. Ook hebben we met team WOGO met Justus gezeten om meer inzicht te krijgen over contentful. Hierna hadden we een iets beter beeld over hoe het is ingedeeld en hoe de code is opgebouwd.

## 📆 Vrijdag 4/10

### Wat heb ik vandaag gedaan?

In de ochtend ben ik mentor geweest voor eerstejaars en hebben wij besproken hoe zij de Layout In CSS opdracht hebben uitgewerkt. Zo hebben we ieders code vergeleken en van elkaar geleerd. Hierna heb ik wat issues ingeschoten over de code die zij hebben geschreven voor hun project.
Daarna hadden Patrick en ik een design review bij docenten en hebben hier feedback op gekregen, voornamelijk over de informatie architectuur van de website. We kregen wel complimenten over het design.

# Week 3

## 📆 Maandag 30/09

### Wat heb ik vandaag gedaan?

Vandaag heb ik de feedback van mijn design verwerkt en begonnen met het testen van de website die er al staat, om deze punten te verbeteren.

## 📆 Dinsdag 1/10

### Wat heb ik vandaag gedaan?

Vandaag ben ik bezig geweest met mijn i-love-web site om vooral de lay-out te maken en onderzocht hoe ik markdown files kan renderen op de website.

## 📆 Woensdag 2/10

### Wat heb ik vandaag geleerd?

Wrap-up:

- Refactored Code: gestructureerde code (conventies), semantiek, geen commented code, geen console.log(), goede tabs, een versie release, goede pull request strategie, components, linter installeren
- Readme.md: Kenmerken, live link, screenshot(s?), Instructies (uitleg over het gebruik), Installatiehandleiding, CMS Uitleg, Huisstijl (of waar die te vinden is), bijdragen? (hints voor volgende dev-teams), gebruikte bronnen, badges met gebruikte technologie, link naar projectboard, introductie, licentie, changelog (o.b.v. versies)
- Testen: performance, keyboard, screenreader, lighthouse, kleurcontrast, WCAG, html validator, user test, browsertest, devicetest, css validator
- Klant: vragen wat zij willen
- Live zetten: Github pages, Vercel, Netlify, onrender

Sprint review: Kijken we je gedaan hebt en hoever je bent met de opdrachtgever

Doel:

- Specifieke vragen bedenken voor feedback
- Specifieke vragen stellen om feedback te krijgen
- Agenda maken
- Demo:
  - Langs user stories gaan van deze sprint
  - Website laten zien, naast het design
  - Laten zien wat er nog niet is gelukt a.d.h.v het design
  - Tijdens de demo benadrukken wat de punten zijn waar je feedback op wilt
  - Doe het met enthousiasme 😎
- Voorstel om een functionaliteit beter te maken (feedback geven aan de opdrachtgever)
- Uitkomst van testen bespreken, bijv over huisstijl en kleurcontrast
- Plan voor de komende sprint- Werk opleveren + de vraag hoe willen jullie het hebben

Rollen:

- Presentator
- Feedback verwerker, notulist (verwerkt ook in issues)
- Cheerleader
- Timekeeper
- Testen: performance, screenreader, key-board test, device test, browser test, kleurcontrast, WCAG, html validator, usertest.

Aan de klant vragen hoe zij de oplevering willen

- Live zetten: github pages, Vercel, Netlify, onrender

### Wat heb ik vandaag gedaan?

Vandaag ben ik begonnen met het maken van de Walks pagina. Wanneer ik wilde beginnen kwam ik een bug tegen, omdat de links waren veranderd in contentful. Na dit gewijzigd en opgelost te hebben ben ik begonnen met de tabs van de verschillende steden.

## 📆 Donderdag 3/10

### Wat heb ik vandaag gedaan?

Vanochtend heb ik de sprint review gehad met mijn projectteam, we hebben best goede feedback ontvangen:

Algemene feedback:

- Met design zijn jullie goed op weg, merk ook dat jullie de opdracht goed begrijpen
- Werk meer met icons en minder tekst, dit is begrijpelijker voor de gebruiker/klant.

Persoonlijke feedback:

- Het design van de pagina's zien er goed uit, homepagina ziet er ook netjes uit!
- Op de walks pagina zijn de tabs een goed idee, is het een idee dat wanneer je in de navigation er op hovert er dan ook de steden tevoorschijn komen en dan op de gewenste stad kan klikken?
- Het carroussel component behouden ipv onder elkaar op de homepagina
- Het tweede design van de card is duidelijker, alleen nog kijken waar de 'NEW' label geplaatst kan worden
- De animaties op de pagina zou zij graag willen behouden

Vragen:
Welke benaming is beter in de nav en op de pagina?

- Het is duidelijker als je cocktail walks of tours gaat gebruiken.

Volgende sprint
Voor de volgende sprint is het de bedoeling dat beide teams verder gaan werken op ons design. Ook is het dan de bedoeling dat we de pagina's gaan verdelen en dezelfde styleguide gaan aanhouden.
