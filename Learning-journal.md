# Sprint 13

## Leervragen

* Hoe combineer je een CMS met framework?
* Hoe zet je een project met een framework op?
* Hoe ga ik stijlelementen dynamische inzetten in combinatie van een framework?
* Hoe maak ik gebruik van Svelte?
* Hoe kan ik mijn bewijslast op de juiste manier opleveren?
* Hoe kan ik mijn sterke en zwakke punten gebruiken om andere te helpen en inzicht krijgen daarin?

## Dinsdag 3/sep

### Framework

Een framework is een set tools, library, en richtlijnen die helpen bij het bouwen van structuren van softwaretoepassingen. Daarnaast zorgt het voor een basisstructuur.

### Getting started
**What is SvelteKit?**

SvelteKit helps you build web apps while following modern best practices and providing solutions to common development challenges. It offers everything from basic functionalities 

The outcome of this approach is not only smaller application bundles and better performance, but also a developer experience that is more approachable for people that have limited experience of the modern tooling ecosystem.

Svelte sticks closely to the classic web development model of HTML, CSS, and JS, just adding a few extensions to HTML and JavaScript. It arguably has fewer concepts and tools to learn than some of the other framework options.

**Creating a project**

[Bron](https://kit.svelte.dev/docs/creating-a-project)

`npm create svelte@latest my-app`
`cd my-app`
`npm install`
`npm run dev`

2 basic concepts:

1. Each page of your app is a [Svelte](https://svelte.dev/) component
2. You create pages by adding files to the src/routes directory of your project. These will be server-rendered so that a user's first visit to your app is as fast as possible, then a client-side app takes over

**Other sources**

- [Project structure](https://kit.svelte.dev/docs/project-structure)
- [Web standards](https://kit.svelte.dev/docs/web-standards)

### Svelte interactieve tutorial

1.

<img width="600" alt="Scherm­afbeelding 2024-09-03 om 14 07 18" src="https://github.com/user-attachments/assets/014174aa-7514-4ba5-820c-90530588a7cf">

2.

<img width="600" alt="Scherm­afbeelding 2024-09-03 om 14 13 21" src="https://github.com/user-attachments/assets/0584d049-6fb3-482f-a751-4c2e294c9347">

### SvelteKit tutorial

Daarna heb ik de SvelteKit tutorial gevolgd.

## Woensdag 4/sep

### Aantekeningen

Recap node

Node.js: Javascript runtime (server.js file);
API-url: url naar database;
Renderen: inladen date + bestanden in de view;

Sveltekit

- Svelte -> compiler die bestanden gegenereerd;
- Sveltekit -> library geschreven in Svelte (web framework voor het ontwikkelen van websites);
- Lightweight;
- Scoped styling;
- Reactive state (automatisch omgaan met data updates);
- Component framework;
- CSR;
- Compiler;
- Folder based routing;
- Get and Post request ‘onder water’ afgehandeld;
- Elke route heeft 0.a een server en component (view) bestand;
- Data wordt geëxporteerd van het server bestand naar het Svelte component;
- Code op gedeeld op client en op server;
- Website werkt echter ook als er geen JS is;
- Wij beginnen Server-side only.

Metaframework (kit) -> SSR, SPA, MPA, SSG;

Directus

- Models ->structuur die data definieert;
- Content-> plaatjes, img, etc;
- Data  -> gegevens.

Demo

Global css -> extern ingeladen -> styling voor hele pagina -> root etc (static map)

### Voortgangsvragen

#### Wat is Svelte en Sveltekit?

- Svelte -> compiler die bestanden gegenereerd;
- Sveltekit -> library geschreven in Svelte (web framework voor het ontwikkelen van websites);

SvelteKit helps you build web apps while following modern best practices and providing solutions to common development challenges. It offers everything from basic functionalities. 

#### Hoe zet je een project met een framework op?

Ik heb geoefend met het opzetten van een framework in een project op een eigen repo. Ik heb gebruik gemaakt van deze [bron.](https://docs.directus.io/blog/getting-started-directus-sveltekit.html) Hierbij heb ik de stappen gebruikt die op de website staan. Het resultaat heb ik [gecommit](https://github.com/lisavanmansom/tribeforlife-squadpage/commit/000f78aa3a8c8074999434d5fb4ba0986fa4ef5f) naar GitHub.

#### Hoe verloopt het samenwerken?

Op maandag hadden we afgesproken om een allemaal een concept te maken, op woensdag hebben we hieruit het beste concept gekozen. [Mijn concept](https://github.com/lisavanmansom/tribeforlife-squadpage/issues/1) was niet gekozen omdat het een beetje niet passend was voor de squadpage was de mening van mijn teamgenoten. Om die reden hebben we gekozen voor Misah, wat een clean design is. Verder hebben we codeconventies vastgesteld (comments achterlaten, dry code, overzichtelijke code). Als laatste hadden we afgesproken om voor vrijdag allemaal een eigen versie te coderen van Misah's design op een branch en vanuit daar kiezen we de beste versie. Daarna gaan we verder op componenten coderen op eigen branches.

## Donderdag 4/sep

Donderdag was ik verder gegaan met werken op mijn [branch](https://github.com/zoepje/your-tribe-for-life-squad-page/commits/squadpage-lisa/), ik heb hier fonts, root en een connection met directus gemaakt. Ik ben tijdens het process tegen een aantal error's aangelopen, grotendeels heb ik ze zelf opgelost, op vrijdag had ik nog een kleine error en daarbij had [Zoë](https://github.com/zoepje) geholpen.

#### Hoe identificeer je error's in Svelte?

In Svelte heb je ook een terminal, hier staat af en toe waar de error is, maar vaak linkt de error ook naar een gegenereerd bestand waar duidelijk niet de error zit. Ik heb tot nu toe mijn error's opgelost door stappen terug te nemen en kijken waar het fout is gegaan. In het begin was het duidelijk dat een aantal dingen miste, zoals npm install, maar naar mate verder, was het vooral stappen terug nemen en kijken wat er mis is gegaan. Op die manier kon ik grotendeels van de tijd de error identificeren en vanuit daar verder gaan bouwen.

#### Wat is nuttig om te doen als je errors heb in je code?

In ons geval hadden we afgesproken dat we een interactie allemaal gaan maken, tijdens mijn error nam ik een korte pauze van het oplossen en ging ik brainstormen voor ideeën wat ik komende week kan gaan coderen. Verder is het nuttig om je verder in Svelte in te lezen, wat ik ook had gedaan. Door andere activiteiten te doen had ik alsnog efficiënt mijn tijd gevuld.

## Vrijdag 6/sep

Vrijdag hebben we een standup gedaan met het team, verder hebben we elkaar feedback gegeven en hebben we een brainstorm-sessie gehouden voor een individuele opdracht (profilecard). Daarnaast heb we ik ook feedback gegeven aan 1e jaars.

Gegeven feedback 1e jaars:
- [Issue 1](https://github.com/ArmanVD/your-tribe-profile-card/issues/8);
- [Issue 2](https://github.com/ArmanVD/your-tribe-profile-card/issues/9);
- [Issue 3](https://github.com/ColindeGroot/your-tribe-profile-card/issues/2).

#### Hoe geef je feedback in de 'zone of proximate development'?

Ik heb 2x feedback gegeven over responsive units, dit onderwerp was nog niet aanbod gekomen bij de 1e jaars en had dat ook benoemd. Ik heb een bron erbij gelinkt zodat ze het konden inlezen, ook heb ik een codesnippet toegevoegd, hierdoor kunnen ze ook zien waar het verbeterpunt is.

## Week /2

### Hoe maak je darkmode / lightmode toggle?

Ik heb via een input checkbox (html) 2 toggles gemaakt, 1 voor lightmode en de ander voor darkmode, daarna was het via CSS de root aanpassen als een bepaalde label wordt gecheckt

[Pull request](https://github.com/zoepje/your-tribe-for-life-squad-page/pull/11)

#### Hoe verloopt het samenwerken?

Op maandag hadden we een standup en hadden we verschillende taken verdeeld. Ik zou een darkmode maken voor woensdag, vanaf woensdag zouden we allemaal animaties designen. Ik had de standup van woensdag gemist, dus heb ik vrijdag mijn werk laten zien. Onze squadpage is grotendeels in de 1e week gecodeerd, om die reden zijn er niet super veel taken meer. Vrijdag hebben we pull requests gedaan en een code/design review gehad. 

### Hoe maak je functioneel gebruik van een projectboard pt.1?

Als feedback hadden we ontvangen dat we niet genoeg gebruik maken van issues in het projectboard, aangezien we geen wiki meer gebruiken is dit de manier van documenteren. Voordat we deze feedback ontvingen hadden we vooral globale taken genoteerd en was het zelf invullen wat je daarmee ging doen. Als iemand het project dan zou overnemen is het niet duidelijk wat er is gedaan, wat er gedaan moet worden en of er bugs zijn. Dat is iets wat je wilt voorkomen. Ik heb na deze feedback meerdere issues aangemaakt in het [projectboard](https://github.com/users/zoepje/projects/5/views/1), hierdoor is het duidelijk waar we nu mee bezig zijn en wat er nog moet worden gedaan.

## We love web - Semester 3
### Vasilis van Gemert - CMD docent

Webbureau websites waar alles serieus was (werkplek). Om die reden zijn eigen website (digital garden) gestart.

Eigen website gestart -> Love nonsense.
Hij houdt van achterkanten van schilderijen en van tijd (klokken), dit heeft hij meerdere keren in zijn design geïmplementeerd.

## Week /3
### Samenwerken en prioriteren

Epic -> Stories -> Tasks

Epic: handige manieren om werk te organiseren en hiërarchie te creëren. Epics helpen teams werk op te splitsen terwijl ze naar een grotere doel toewerken. Epics zijn dus grote stukken werk die kunnen worden opgesplitst in kleinere taken, die vervolgens in sprints kunnen worden voltooid.

In 1 zin noemen wat het project is. (epic)

Stories: Een epic kan je onderverdelen in stories (userstories). Userstories hebben altijd dezelfde vorm, “als gebruiker - wil ik”. Door userstories maak je bespreekbaar wat er moet worden gedaan. Stories zijn minder concreet dan userstories. Stories zijn een directe taak, userstories zijn concrertere taken van de stories.

#### Planning poker

Consensus-gebaseerde techniek voor het schatten, vooral gebruikt voor timeboxing in Agile principes. Leden van de groep geven schattingen door genummerde kaarten op tafel te leggen of een getal op te schrijven in plaats van dit hardop te zeggen. De kaarten worden omgedraaid en de schattingen worden vervolgens besproken. Door de cijfers te verbergen, kan cognitieve bias van veeranking vermijden, waarbij het eerste hardop gesproken cijfer een precedent schept voor volgende schattingen.

#### Prioriteren 

**Moscow principes:**
- Must haves -> dit moet af op de deadline, als het niet af is dan is het project gefaald.
- Should haves -> dit zou eigenlijk best wel af moeten, het project is eenbeetje jammer, als het niet af is.
- Could haves -> dit kan, mits we tijd over hebben
- Want to have but will not have this sprint -> dit zijn goede ideeën en nuttig om te noteren maar we komen er nu niet aan toe.

### Hoe maak je functioneel gebruik van een projectboard pt.2?

Door de moscow technieken en planning poker techniekene toe te passen. Hierdoor geef je waarde aan taken en kan je makkelijker er overzicht in krijgen, vanuit daar is het prioriteren van de taken ook eenvoudiger. In het projectboard kan je labels toevoegen aan taken waardoor alles ook overzichtelijker is en maak je door deze prinicpes en technieken functioneler gebruik van een projectboard.

#### Hoe maak ik een component in svelte?

In mijn i-love-website heb ik voor het eerst met een svelte component gewerkt. In de [link](https://github.com/lisavanmansom/i-love-web/issues/14#issuecomment-2355135232) is het uitgelegd doormiddel van een commit.

#### Hoe verloopt het samenwerken?

We doen elke fysieke schooldag een standup, hierdoor krijgen we een duidelijk overzicht waar mensen staan en wat ernog moet worden gedaan. Deze week ging dat hetzelfde, op maandag hadden we vanuit de standup takenverdeeld. Verder hebben we ook op maandag het projectboard een functie gegeven door de principes van moscow toe te voegen en een planningpoker te doen. Woensdag hadden we een korte standup. Vrijdag gaan we een kampvuur doen en is de retrospect van het project.

## Retrospect

### Hoe combineer je een CMS met framework?

Door gebruik te maken van een fetch-json.js, dat te combineren met een ander js-bestand waar je de API url linkt. Het is vrijwel hetzelfde als semester 2 data ophalen, alleen gebruik je kleinere bestanden.

### Hoe zet je een project met een framework op?

Door gebruik te maken van de volgende stappen zet je een project op met Svelte:
* npm create svelte@latest my-app
* cd my-app
* npm install
* npm run dev

### Hoe ga ik stijlelementen dynamische inzetten in combinatie van een framework?

Doormiddel van componenten te creëren in je library kan je het dynamisch gebruiken. In de [link](https://github.com/lisavanmansom/i-love-web/issues/14#issuecomment-2355135232) is het uitgelegd doormiddel van een commit.

### Hoe maak ik gebruik van Svelte?

Door het installatie process te volgen van het opzetten van een project, verder kan je gebruik maken van een aantal documenten zoals global.css en kan je een CMS linken. Vanuit daar kan je coderen in componenten of voor een andere werkwijze kiezen. Het is vrij open natuurlijk wat/hoe je gebruik maakt van Svelte.

### Hoe kan ik mijn bewijslast op de juiste manier opleveren?

Op vrijdag 20 sept hebben we de retrospect, tijdens de retrospect wordt het pas echt duidelijk. Zelf ga ik vanuit dat als je een compleet projectboard hebt dat je er dan aan toe zal komen.

### Hoe kan ik mijn sterke en zwakke punten gebruiken om andere te helpen en inzicht krijgen daarin?

Door gebruik te maken van mijn kennis heb ik bij eerste jaars feedback gegeven doormiddel van issues. Verder doe ik 1x per week studentassistent, hier help ik CMD-studenten met het maken van een website. In beide gevallen is het helpen tot nu toe minimaal. Op donderdag 19 sept wordt er verwacht dat de CMD-studenten code hebben, vanaf dat punt kan ik mensen meer helpen. Om deze vraag beter te kunnen beantwoorden, was het ook handig geweest om mijn sterke en zwakke punten te identificeren. Ik ben van plan om deze leervraag volgende sprint nog een keer te doen.

Op donderdag 19 september waren er voortgangsgesprekken, hieruit kwam naarvoren de diversiteit in kennis en skills in het vakgebied per CMD-student. In die gesprekken is er vooral mondelijk feedback gegeven over codestructeren. In een excel bestand hebben we de feedback / de voortgang genoteerd.

<img width="1200" alt="Scherm­afbeelding 2024-09-22 om 11 57 16" src="https://github.com/user-attachments/assets/6d91836d-0859-4407-9aba-19f4fa8c5963">

# Sprint 14

## Leervragen

* Hoe kan ik Svelte efficient inzetten? (denk componenten etc)
* Hoe maak ik subtiel gebruik van een JS library?
* Hoe kan ik mijn sterke en zwakke punten gebruiken om andere te helpen en inzicht krijgen daarin?
* Hoe kan ik bijdragen in een goede samenwerking?

## Week /1

Op maandag heb ik met mijn groepje voorbereidingen getroffen voor briefing / debriefing. Als groepje hebben we ook een teamcanvas ingevuld. Op woensdag hebben we een datamodel gemaakt en een sitemap, door een datamodel te maken zorg je ervoor dat het duidelijk is wat er in de CMS is. Op donderdag heb ik de CMS ingevuld doormiddel van het datamodel. Verder was er op woensdag de briefing / debriefing, hier heb ik meerdere vragen gesteld aan de opdrachtgever. Op vrijdag hadden we een feedback moment met de leraren, hieruit bleek dat nog niet iedereen uit mijn groepje goed opweg was.

### Hoe zorg je ervoor dat een team resultaat levert en dat iedereen hun taak voltooid?

Op vrijdag hadden we een feedback moment met leraren, daaruit bleek dat er nu al gaten vallen in onze samenwerking. Om dit verder te voorkomen gaan we maandag opnieuw afspraken maken en het teamcanvas nog een keer nalopen. Door dit te doen gaat de samenwerking hopelijk beter en levert iedereen het gewenste resultaat.

### Hoe zorg je dat de briefing die je ontvangt duidelijk is en dat je vanuit daar knelpunten kan analyseren en aangeven?

Onze briefing bestond uit vragen stellen en vanuit daar ging de opdrachtgever een het uitleggen. Hierdoor was het belangrijk om zelf met de vragen te komen en te luisteren totdat de boodschap helder is. Om die reden was het makkelijker om door te vragen en verifieren omdat de briefing voornamelijk uit vragen bestonden die ik had gesteld. Daardoor was het ook eenvoudiger om knelpunten aan te geven, als voorbeeld, de opdrachtgever wil een AI-chatbot in haar website, dit kunnen we niet maken en zou in de toekomst een knelpunt kunnen worden. Omdat we zelf met vragen moesten komen was het aangeven van een knelpunt zoals dat makkelijker en had ik dat gelijk gedaan.

### Hoe zorg je dat alle data in een CMS komt te staan met structuur?

We hadden als groepje vooraf een datamodel en een sitemap geschetst. Hierdoor was het vooraf duidelijker wat er moest gebeuren. Alsnog ging het mis met het toevoegen van de data in Directus op woensdag. Op donderdag had ik met de hulp van een leraar het juist opgezet. Nu heeft het de juiste conventies en structuur en het ging makkelijker door het geschetste datamodel.




