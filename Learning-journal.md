# Sprint 13

## Leervragen

* Hoe combineer je een CMS met framework?
* Hoe zet je een project met een framework op?
* Hoe ga ik stijlelementen dynamische inzetten in combinatie van een framework?
* Hoe haal je data uit een Headless CMS door middel van een framework te renderen in een website?
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

[Pull request](https://github.com/zoepje/your-tribe-for-life-squad-page/pull/11)

#### Hoe verloopt het samenwerken?

## Retrospect

### Hoe combineer je een CMS met framework?

### Hoe zet je een project met een framework op?

### Hoe ga ik stijlelementen dynamische inzetten in combinatie van een framework?

### Hoe haal je data uit een Headless CMS door middel van een framework te renderen in een website?

### Hoe maak ik gebruik van Svelte?

### Hoe kan ik mijn bewijslast op de juiste manier opleveren?

### Hoe kan ik mijn sterke en zwakke punten gebruiken om andere te helpen en inzicht krijgen daarin?
