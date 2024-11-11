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

Hierna ben ik in mijn team aan de slag gegaan, er is een design uitgekozen en is er een taakverdeling gemaakt. Hieruit is gekomen om allemaal het design na te maken om ook te oefenen met sveltekit. Ik ben hier ook gelijk mee aan de slag gegaan en heb ik de `HTML` en de globale `CSS`.

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
3. Voeg in /routes/+page.js deze regel code toe: `export let csr = false`
4. Neem in `/lib/fetch-node.js` de code over uit hetzelfde bestand van je laatste node.js project van sprint 12
5. Importeer deze function in `/routes/+page.server.js`
6. Check aan de hand van het voorbeeld of je alles goed gedaan hebt
7. Copy/paste als laatste jullie toegevoegde svelte code terug in `/routes/+page.svelte`

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
