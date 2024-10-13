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

## Week / 1

Op maandag heb ik met mijn groepje voorbereidingen getroffen voor briefing / debriefing. Als groepje hebben we ook een teamcanvas ingevuld. Op woensdag hebben we een datamodel gemaakt en een sitemap, door een datamodel te maken zorg je ervoor dat het duidelijk is wat er in de CMS is. Op donderdag heb ik de CMS ingevuld doormiddel van het datamodel. Verder was er op woensdag de briefing / debriefing, hier heb ik meerdere vragen gesteld aan de opdrachtgever. Op vrijdag hadden we een feedback moment met de leraren, hieruit bleek dat nog niet iedereen uit mijn groepje goed opweg was.

### Hoe zorg je ervoor dat een team resultaat levert en dat iedereen hun taak voltooid?

Op vrijdag hadden we een feedback moment met leraren, daaruit bleek dat er nu al gaten vallen in onze samenwerking. Om dit verder te voorkomen gaan we maandag opnieuw afspraken maken en het teamcanvas nog een keer nalopen. Door dit te doen gaat de samenwerking hopelijk beter en levert iedereen het gewenste resultaat.

### Hoe zorg je dat de briefing die je ontvangt duidelijk is en dat je vanuit daar knelpunten kan analyseren en aangeven?

Onze briefing bestond uit vragen stellen en vanuit daar ging de opdrachtgever een het uitleggen. Hierdoor was het belangrijk om zelf met de vragen te komen en te luisteren totdat de boodschap helder is. Om die reden was het makkelijker om door te vragen en verifieren omdat de briefing voornamelijk uit vragen bestonden die ik had gesteld. Daardoor was het ook eenvoudiger om knelpunten aan te geven, als voorbeeld, de opdrachtgever wil een AI-chatbot in haar website, dit kunnen we niet maken en zou in de toekomst een knelpunt kunnen worden. Omdat we zelf met vragen moesten komen was het aangeven van een knelpunt zoals dat makkelijker en had ik dat gelijk gedaan.

### Hoe zorg je dat alle data in een CMS komt te staan met structuur?

We hadden als groepje vooraf een datamodel en een sitemap geschetst. Hierdoor was het vooraf duidelijker wat er moest gebeuren. Alsnog ging het mis met het toevoegen van de data in Directus op woensdag. Op donderdag had ik met de hulp van een leraar het juist opgezet. Nu heeft het de juiste conventies en structuur en het ging makkelijker door het geschetste datamodel.

## Maandag / 30 sept
### Sveltekit principles

**Structuur**

In src staat alles wat svelte nog moet uitvoeren
Vite -> buildtools voor webomgeving

**Error handeling**

+error.svelte —> voor error handeling
error.html —> voor errorr handeling als svelte niet meer werkt.

+layout.svelte —> layout format gerendered

**Loading data**

In server.js (vb code) —>

Return { For: “”; Bar: 42; Type: “”;}

In +page.svelte —> Export let data

**Binding**

<Input bind:value={name} />
<p>hello {name}<p/>

**Library**

In de index.js moet een verzameling.van componenten staan (wat ik nu soort van heb in de script)

Toepassing in index.js (file in lib):
```
export { default as MeshgradBlue } from './meshgrad-blue.svelte'
export { default as MeshgradRed } from './meshgrad-red.svelte'
export { default as MeshgradGreen } from './meshgrad-green.svelte'
export { default as MeshgradPink } from './meshgrad-pink.svelte'
export { default as ArrowL } from './arrow-l.svelte'
export { default as ArrowR } from './arrow-r.svelte'
```

Uitwerking in +page.svelte:

```
import {MeshgradBlue, MeshgradRed, MeshgradGreen, MeshgradPink, ArrowL, ArrowR} from '$lib'
```

**Export**

In +page.svelte in script -> Import {header, footer} from $lib

### Samenwerking

Als feedback hadden we vrijdag gekregen dat we afspraken moeten maken. Deze afspraken hebben we vastgelegd in het [projectboard.](https://github.com/orgs/fdnd-agency/projects/37/views/1?pane=issue&itemId=81595450) Gemaakte afspraken:
- Als je een taak hebt ben je zelf verantwoordelijk voor het projectboard, de taken / progress / splitst;
- Harde deadline --> 7 oktober;
- Standups bijhouden;
- Bij afwezigheid melden in groepchat in de ochtend;
- Als afspraken niet worden nagevolgd kan eventueel een samenwerkingsverband verbroken.

## Dinsdag / 1 okt
### One-pager PE

Het gedeelte wat ik maak bij Drop&Heal is een one-pager waarbij je maar 1 section tegerlijk kan zien, dit heb ik niet eerder gedaan dus had ik onderzoek ernaar gedaan. In de [documentatie](https://github.com/orgs/fdnd-agency/projects/37/views/1?pane=issue&itemId=81733588) staat de gehele uitleg. Als eerste ben ik begonnen met bronnen / voorbeelden bekijken, vanuit hier heb ik meerdere opties geprobeerd. In eerste instantie dacht ik dat het a-element moest worden gemaakt, dit werkte niet helemaal, dus toen heb ik de bronnen toegepast, hier gebruikte ze vooral input radio / checkbox. Dit werkte ook niet, door dit te doen kwam ik wel op de code die ik uiteindelijk nodig had voor het resultaat. Dit is gemaakt met het a-element. Ik moet het nog testen of het werkt als de JS uitstaat, aangezien er wel 1 regel JS is.

#### Code

**script:**

```
let current = 1;
```

**html (4x):**

```
<section id="rt-1" class:show={current === 1} class:hide={current != 1}>
        <h2>Rouwtaak <em>1</em></h2>
        <h3>Het verlies aanvaarden</h3>
        <p>Ontdek hoe je de realiteit van het verlies kunt omarmen.</p> 
        <MeshgradBlue class="meshgrad" />

        <div aria-busy="true" aria-describedby="progress-bar"></div>
        <progress value="20" max="100"></progress>

        <div class="d-a">
            <a href="#rt-2" on:click={() => current = 2}><ArrowR /></a>
        </div>
      </section>
```

**css:**

```
.show {
        opacity: 1;
        visibility: visible;
    }

    .hide {
        opacity: 0;
        visibility: hidden;
     }
```

### Student-assistent

Op dinsdag heb ik geholpen bij CMD-studenten als student-assistent, na verloop van deze lessen ben ik erachter gekomen dat ze vaak niet om hulp vragen, als student-assistent loop je rondjes en vraag je of het lukt en grotendeels van de tijd is het antwoord 'ja' of ze reageren niet. Vandaag heb ik vooral geholpen met screenreader, SVG's, overflow van een page, flex voor een nav en Javascript. Op donderdag zijn voortgangsgesprekken en meestal vanuit daar kan je meer helpen omdat je dan ook echt in de code gaat.

## Donderdag / 3 okt

### Rouwvormen animeren

Op donderdag was ik gestart met [rouwvormen animeren](https://github.com/orgs/fdnd-agency/projects/37/views/1?pane=issue&itemId=81035744), ik was van plan om een svg te animeren. Toen ik van start ging had ik de gedachte dat het beeldmateriaal in het figma-file een svg was, echter was dat niet zo. Hierdoor was ik te lang bezig met het omzetten van de png naar svg, wat uiteindelijk niet het gewenste resultaat opleverde. Toen besloot ik om de 1e twee rouwvormen, de png, te animeren. Dit was niet het orginele resultaat en plan waar ik voor wou gaan, om die reden kon ik het ook niet met een JS-library animeren zoals ik voor ogen had in mijn opgezette leervraag begin deze sprint. 

### Student-assistent

Op donderdag waren voortgansgsgesprekken, hier hebben we besproken waar de studenten tegen aan lopen tijdens het coderen. De meeste lopen aan tegen kleine problemen zoals een height / width toevoegen aan elementen. Verder moeten veel studenten een carousel maken, hiervoor hebben we scroll snap geadviseerd om te gebruiken. Bij sommige studenten hadden we ook een aantal error's opgelost, bijvoorbeeld de header met daarin een navigatie van een student die de site van Louisvuitton maakt. Hierin ging het om het goed gebruik maken van positionering, wat zij bijna had maar nog niet helemaal. Vaak zie je ook dat studenten nog moeten beginnen met css of weinig hebben en in die gevallen kan je ze allemaal tips geven over toekomstige problemen waar ze waarschijnlijk tegen aan gaan lopen. Veel studenten waren na deze gesprekken gemotiveerd om verder te gaan met coderen en meerdere zeiden dat ze er echt wat aan hadden.

## Week / 3

### Over Agile, scrummed en project management

**Waterval vs Agile**

Waterval: Specification related paradigms;
Agile: Comprehensive-system.

Nieuwe Agile instrumenten

Get Agile

### View transitions

Voor een smooth overgang zijn er view transitions nodig. Ik ben begonnen om verschillende bronnen door te nemen.

**Bron:**
- https://developer.chrome.com/docs/web-platform/view-transitions?hl=nl
- https://developer.mozilla.org/en-US/docs/Web/API/View_Transitions_API
- https://codepen.io/bramus/pen/GRVRjYE
- https://www.youtube.com/watch?v=q_2irZO4SS8

#### Code

Om viewtransitions te maken moet je een nieuw file aanmaken en dit file linken op elke page waar je viewtransitions wil.  Door dit toe de onderstaande code toe te voegen ontstaat er een viewtransitions als je navigeert in-between-pages.

**new file:**

```
<script lang="ts">
    import { onNavigate } from '$app/navigation';
    onNavigate((navigation) => {
        if (!document.startViewTransition) return;
        return new Promise(resolve => {
            document.startViewTransition(async () => {
                resolve();
                await navigation.complete;
            });
        });
    });
</script>

```

**script:**

```
  import ViewTransition from '../navigation.svelte'
```

**html:**

```
  <div class="app">
    <ViewTransition />
  </div>
```

### Voorbereiden sprint review & retrospect

Sprint review: kijken wat je gedaan hebt en hoe ver je bent gekomen (met de opdrachtgever)

**Doel:**
- specifieke vragen stellen voor feedback (van tevoren hebt bedacht);
- demo;
- langs user stories gaan van de ze sprint;
- website laten zien, naast het design;
- laten zien wat er nog niet is gelukt a.d.h.v. het design;
- tijdens de demo benadrukken wat de punten zijn waar je feedback op wilt hebben;
- met enthousiasme;
- voorstel om een functionaliteit beter te maken (feedback geven aan de opdrachtgever);
- uitkomst testen bespreken;
- plan voor de komende sprint;
- werk opleveren.

**Rollen:**
- presentator;
- feedback verwerker / notulist (issues);
- cheerleader;
- timekeeper.

## Retrospect

### Hoe kan ik Svelte efficient inzetten? (denk componenten etc)

Door in de library een 'index.js' file aan te maken. In dit bestand kan je componenten linken die ook in de library staan.

```
export { default as MeshgradBlue } from './meshgrad-blue.svelte'
export { default as MeshgradRed } from './meshgrad-red.svelte'
export { default as MeshgradGreen } from './meshgrad-green.svelte'
export { default as MeshgradPink } from './meshgrad-pink.svelte'
export { default as BlurgradBlue } from './blurgrad-blue.svelte'
export { default as BlurgradRed } from './blurgrad-red.svelte'
export { default as BlurgradGreen } from './blurgrad-green.svelte'
export { default as BlurgradPink } from './blurgrad-pink.svelte'
export { default as ArrowL } from './arrow-l.svelte'
export { default as ArrowR } from './arrow-r.svelte'
```

In het file waar je html/css/js staat heb je de volgende regel:

```
  import {MeshgradBlue, ArrowR} from '$lib'
```

Hierdoor kan je efficienter te werk gaan doordat je gebruik maakt van componenten en ziet het er overzichtelijker uit in het werk-file omdat je maar 1 regel toepast.

### Hoe maak ik subtiel gebruik van een JS library?

In deze sprint wilde ik gebruik maken van een JS library om een svg te animeren, ik had deze taak als een 'should have' gemarkeerd omdat het niet de grootste prioriteit had. Toen het eenmaal zover was om deze taak te doen zat ik in de 2e week van de sprint, op dat moment kwam ik erachter dat het beeldmateriaal een png was inplaats van een svg, ik heb gevraagd aan een cmd-student of die het beeldmateriaal kon omzetten naar een svg. Dit was op een donderdag en op een vrijdag krijg ik feedback over iets wat en hogere prioriteit had, om die reden ben ik er niet aan toe gekomen om met een JS library te werk te gaan. Om alsnog wel een animatie te maken op het element heb ik gebruik gemaakt van CSS keyframes

```
    @keyframes aBlue {
    25% { transform: scale(1.2); }
    50% { transform: scale(1.1); }
    75% { transform: scale(1.2); }
    }
```


### Hoe kan ik mijn sterke en zwakke punten gebruiken om andere te helpen en inzicht krijgen daarin?

Deze sprint hadden we voortgangsgesprekken, hierdoor kan ik mijn sterke en zwakke punten makkelijker inzetten om andere te helpen en inzicht krijgen.

Ik had voornamelijk geholpen met een hamburger-menu, hier hoort het 3-stappenplan van JS bij en een aantal CSS principes. Over het algemeen moeten ze gebruik maken van CSS-properties die ze dan niet kennen, zo nu en dan kan je een bron meegeven, maar vaak door het antwoord te zeggen komen ze er direct zelf uit (denk aan als ze een width / height vergeten). Door zulke kennis in te zetten bij problemen van andere kan je ze helpen met inzicht krijgen in hun probleem.

**complete documentatie:**
- https://github.com/lisavanmansom/i-love-web/edit/main/Learning-journal.md#student-assistent-1
- https://github.com/lisavanmansom/i-love-web/edit/main/Learning-journal.md#student-assistent
  
### Hoe kan ik bijdragen in een goede samenwerking?

We zijn gestart met een teamcanvas in te vullen, hier hebben we afspraken, doelen, rollen, etc vastgelegd. Na feedback van leraren hebben we nog een keer de week daarna duidelijkere afspraken gemaakt. Verder hebben we om codeconventies opgezet zodat hier geen conflicten kunnen ontstaan. Daarnaast hebben we later in de sprint de rollen nog expliciter benoemd zodat het duidelijk is voor iedereen wat er verwacht kan worden van hun en van andere. Ten slot zijn alle standups gedocumenteerd, hierdoor zijn de ontwikkelingen in het team duidelijk terug te lezen.

Door al deze dingen te doen was het doel dat er een goede samenwerking zou zijn, iedereen heeft bovendien z'n individuele taken gedaan. Maar alsnog ging het niet helemaal soepel, alle taken die collectief voor de groep in voordeel zouden zijn, zijn door mij gemaakt omdat niemand echt initatief toonde. Als voorbeeld, bij het opzetten van Directus was de vraag wie gaat dat doen, de aanwezige teamleden kijken schaapachtige naar mij omdat hun het niet echt zagen zitten, ik merkte dat mijn teamleden vanuit gingen dat de taken die voor de groep collectief waren wel voor hun zouden worden gedaan. Ook waren een aantal gezamelijke taken zoals duidelijke afspraken opzetten, hier had ik besloten om hun aan het woord te laten zodat ik niet alles zou 'bepalen, alleen hadden ze niks te zeggen / voorgesteld, dus uiteindelijk heb ik dat ook in mijn eentje opgezet.

Om tot conclusie te komen, ik heb eigenlijk te veel bijgedragen maar als ik het niet zou doen, dan was het niet gedaan. Bij veel taken heb je het nodig als bewijslast, dus dan moet het alsnog worden gedaan en is er uiteindelijk niet echt een keus.

**Overzicht taken gedaan:**
- Readme, opzetten projectboard, opzetten svelte, documenteren in het projectboard, standups, directus inrichten, directus linken, data ophalen, rollen benoemen, afspraken opzetten, debriefing, livezetten, briefing gesprek leiden, contact leggen met de opdrachtgever

**Documentaties:**
- https://github.com/fdnd-agency/drop-and-heal/issues/5
- https://github.com/fdnd-agency/drop-and-heal/issues/47
- https://github.com/fdnd-agency/drop-and-heal/issues/27
- https://github.com/fdnd-agency/drop-and-heal/issues/2
- https://github.com/fdnd-agency/drop-and-heal/issues/1

## Zondag 13/okt
### WebGL notities

**bron:** https://thebookofshaders.com

### Shaders
#### Fragment shader

**Why are shaders fast?**
Because of parallel processing. Instead of having a couple of big and powerful microprocessors, it is smarter to have lots of tiny microprocessors running in parallel at the same time. That’s what a Graphic Processor Unit (GPU) is.

**What is GLSL?**
GLSL stands for openGL Shading Language

Hello world! -> In GPU-land rendering text is an overcomplicated task for a first step, instead we'll choose a bright welcoming color to shout our enthusiasm!

// De gl_FragColor = vec4(0.549,0.512,1.000,1.000) -> geeft kleur aan

```
#ifdef GL_ES
precision mediump float;
#endif

uniform float u_time;

void main() {
	gl_FragColor = vec4(0.549,0.512,1.000,1.000);
}
```

**Substantial knowledge from lines of code:**
1. Shader Language has a single main function that returns a color at the end. 
2. The final pixel color is assigned to the reserved global variable gl_FragColor.
3. This C-flavored language has built in variables (like gl_FragColor), functions and types. In this case we've just been introduced to vec4 that stands for a four dimensional vector of floating point precision. 
4. The four arguments respond to the RED, GREEN, BLUE and ALPHA channels.
5. Float types are vital in shaders, so the level of precision is crucial. Lower precision means faster rendering, but at the cost of quality. You can be picky and specify the precision of each variable that uses floating point. In the second line (precision mediump float;) we are setting all floats to medium precision. But we can choose to set them to low (precision lowp float;) or high (precision highp float;).

#### Uniforms

Uniforms are effectively global variables you set before you execute your shader program. Each thread receives the same data which it can read but cannot change. Uniforms are defined with the corresponding type at the top of the shader right after assigning the default floating point precision.

**Most of the supported types:**
1. float
2. vec2
3. vec3
4. vec4
5. mat2
6. mat3
7. mat4
8. sampler2D
9. samplerCube

```
ifdef GL_ES
precision mediump float;
#endif

uniform vec2 u_resolution;  // Canvas size (width,height)
uniform vec2 u_mouse;       // mouse position in screen pixels
uniform float u_time;       // Time in seconds since load

// u_time (time in seconds since the shader started), u_resolution (billboard size where the shader is being drawn) and u_mouse (mouse position inside the billboard in pixels).

uniform vec3 iResolution;   // viewport resolution (in pixels)
uniform vec4 iMouse;        // mouse pixel coords. xy: current, zw: click
uniform float iTime;        // shader playback time (in seconds)

// shader toy uniforms
```

### WebGL uitwerking
