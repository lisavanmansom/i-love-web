<script>
    import Footer from '$lib/c-footer.svelte';
    import TextAbout from '$lib/text-aboutme.svelte';
    import ViewTransition from '../navigation.svelte';
    import ShaderAbout from '$lib/shader-about.svelte';

    let current = 1;
</script>

<div class="app">
    <ViewTransition />
  </div>

<main>
    <header>
        <h1>Hi, I am Lisa van Mansom</h1>
        <p>Frontend developer</p>
        <p>I am keen on funky websites, animations, eclastic designs, literature and art.</p>
        <img width="100" height="100" loading="lazy" alt="" src="../images/about-1.png">
    </header>

    <section>
        <hgroup>
            <h2>Selected works</h2>
            <p> I've worked on the integration of several websites, focusing solely on the front-end interface. At times, I worked from mockups provided by designers, while other times I handled the UX/UI myself. </p>
        </hgroup>

        <div class="l-d">
        <article>
            <div class="a-d">
                <a href="https://github.com/lisavanmansom/proof-of-concept">
                    <div>
                        <h3>Fresk digital</h3>
                        <h4>June 2024</h4>
                        <p>Dotenv / chart.js / node & express </p>
                    </div>
                </a>
            </div>
            <div>
                <img width="100" height="100" alt="website for fresk digital, data dashboard" src="../images/fresk-1.png">
                <img width="100" height="100" alt="website for fresk digital, login screen" src="../images/fresk-2.png">
            </div>
        </article>

        <article>
            <div class="a-d"> 
            <a href="https://github.com/lisavanmansom/pleasurable-ui">
                <div>
                    <h3>Tumi Mundo</h3>
                    <h4>May 2024</h4>
                    <p>GSAP / node & express </p>
                </div>
                </a>
            </div>
            <div>
                <img width="100" height="100" loading="lazy" alt="website for Tumi Mundo" src="../images/tumi-1.png">
                <img width="100" height="100" loading="lazy" alt="website for Tumi Mundo" src="../images/tumi-2.png">
            </div>
            
        </article>

        <article>
            <div class="a-d">
            <a href="https://github.com/lisavanmansom/fix-the-flow-interactive-website">
                <div>
                    <h3>Funda</h3>
                    <h4>December 2023</h4>
                    <p>html / css / Javascript</p>
                </div>
            </a>
            </div>
            <div>
                <img width="100" height="100" loading="lazy" alt="website for funda" src="../images/funda-1.png">
                <img width="100" height="100" loading="lazy" alt="website for funda" src="../images/funda-2.png">
            </div> 
        </article>

        <article>
            <div class="a-d">
            <a href="https://github.com/lisavanmansom/drop-and-heal">
                <div>
                    <h3>Drop & Heal</h3>
                    <h4>October 2023</h4>
                    <p>Sveltekit / React </p>
                </div>
            </a>
            </div>
            <div>
                <img width="100" height="100" loading="lazy" alt="website for drop and heal, rouwtaak 3" src="../images/dropheal-1.png">
                <img width="100" height="100" loading="lazy" alt="website for drop and heal, rouwtaak 2" src="../images/dropheal-2.png">
            </div>
        </article>

        <article>
            <div class="a-d">
            <a href="https://github.com/lisavanmansom/the-startup-website-bnr">
                <div>
                    <h3>BNR</h3>
                    <h4>January 2023</h4>
                    <p>html / css / Javascript</p>
                </div>
            </a>
            </div>
            <div>
                <img width="100" height="100" loading="lazy" alt="website for bnr" src="../images/bnr-1.png">
                <img width="100" height="100" loading="lazy" alt="website for bnr" src="../images/bnr-2.png">
            </div>
        </article>

        <article>
            <div class="a-d">
            <a href="https://github.com/lisavanmansom/connect-your-tribe-profile-card">
                <div>
                    <h3>Profile card / 2</h3>
                    <h4>February 2024</h4>
                    <p>node & express</p>
                </div>
            </a>
            </div>
            <div>
                <img width="100" height="100" loading="lazy" alt="" src="../images/pf-1.png">
                <img width="100" height="100" loading="lazy" alt="" src="../images/pf-2.png">
            </div>
            
        </article>

        <article>
            <div class="a-d">
            <a href="https://github.com/lisavanmansom/connect-your-tribe-squad-page">
                <div>
                    <h3>Squadpage museum</h3>
                    <h4>February 2024</h4>
                    <p>node & express</p>
                </div>
            </a>
            </div>
            <div>
                <img width="100" height="100" loading="lazy" alt="" src="../images/museum-2.png">
                <img width="100" height="100" loading="lazy" alt="" src="../images/museum-1.png">
            </div>
        </article>

        <article>
            <div class="a-d">
            <a href="https://github.com/lisavanmansom/tribeforlife-squadpage">
                <div>
                    <h3>Squadpage</h3>
                    <h4>September 2024</h4>
                    <p>Sveltekit</p>
                </div>
            </a>
            </div>
            <div>
                <img width="100" height="100" loading="lazy" alt="#" src="../images/squadw-1.png">
                <img width="100" height="100" loading="lazy" alt="#" src="../images/squadw-2.png">
            </div> 
        </article>
        
    </div>

    <ShaderAbout />

    </section>

    <section>
        <article>
            <h2>about me</h2>
            <p>Madison Blackstone is a director of brand marketing, with experience managing global teams and multimillion-dollar campaigns. Her background in brand strategy, visual design, and account management informs her mindful but competitive approach. Madison is fueled by her passion for understanding the nuances of cross-cultural advertising. She considers herself a "forever student," eager to both build on her academic foundations in psychology and sociology, and stays in tune with the latest digital marketing strategies through continued coursework.</p>
        </article>

        <article>
            <h2>experience</h2>
            <p>Madison Blackstone is a director of brand marketing, with experience managing global teams and multimillion-dollar campaigns. Her background in brand strategy, visual design, and account management informs her mindful but competitive approach. Madison is fueled by her passion for understanding the nuances of cross-cultural advertising. She considers herself a "forever student," eager to both build on her academic foundations in psychology and sociology, and stays in tune with the latest digital marketing strategies through continued coursework.</p>
        </article>

        <article>
            <h2>contact</h2>
            <ul>
                <li><a href="https://github.com/lisavanmansom">Github</a></li>
                <li><a href="https://www.linkedin.com/in/lisa-van-mansom-b78059231/">Linkedin</a></li>
                <li><a href="mailto:lisavanmansom@gmail.com">Mail</a></li>
                <li><a href="tel:0642629104">0642629104</a></li>
            </ul>
        </article>
    </section>

    
</main>

<Footer />

<style lang="postcss">
main {  color: var(--horizonte);
        display: flex; flex-direction: column;
        align-items: center; justify-content: center;
        overflow-x: hidden;
        width: 100%; min-height: 100dvh;
        text-transform: uppercase;
    }
    
    h1 { font-weight: 200; font-size: 1.5em; }
    h2 { font-weight: 200; font-size: 2em; }
    h3 { font-weight: 400; font-size: 1em; }
    h4 { font-weight: 100; font-size: .9em; }
    p  { font-weight: 100; font-size: .8em; }
    a  { text-decoration: none; cursor: pointer; color: var(--beijo);}

    header {
        display: flex;
        flex-direction: column;
    }

   section:nth-of-type(1) {
    position: relative;
    width: 100%;
    /* padding: .5em .25em; */
    /* box-shadow: 0px 0px 140px rgb(17, 255, 0); */
   }

   section:nth-of-type(1) hgroup {
    background-color: var(--horizonte);
    width: 100%;
    color: var(--beijo);
   }

   section:nth-of-type(1) hgroup h2 {
    padding: .5em .25em 0;
   }

   section:nth-of-type(1) hgroup p {
    padding: .5em 1em;
    max-width: 75ch;
   }

   .l-d {
    background: linear-gradient(135deg, rgba(255, 255, 255, 0.418), rgba(124, 90, 196, 0.304));
    backdrop-filter: blur(10px);
    container: list-banner / inline-size;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    -webkit-backdrop-filter: blur(10px);
   }

   section:nth-of-type(1) article {
    align-items: center;
    border: .1em solid var(--horizonte);
    color: var(--beijo);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    min-height: 34em;
    position: relative;
   }

   /* div in article, staat om de a heen */
   .a-d {
    background-color: var(--horizonte);
    /* box-shadow: 0px 0px 140px rgb(17, 255, 0); */
    display: flex;
    flex-direction: column;
   }

   .a-d a {
    display: flex;
    flex-direction: column;
   }

   .a-d a div {
    align-items: center;
    display: flex;
    flex-wrap: wrap;
    height: 4em;
    justify-content: space-between;
    padding: .5em .25em;
    width: 100vw;
   }

    .a-d a div p {
      font-weight: 100; 
      font-size: .8em;
      width: 100%;
    }
   
   section:nth-of-type(1) article img {
    height: 10em;
    object-fit: cover;
    width: 10em;
   }

   section:nth-of-type(1) article div:nth-of-type(2) {
     height: 10em;
     order: -1;
     display: flex;
     align-items: center;
     justify-content: center;
     transition: all 5s ease-in-out;
   }

   section:nth-of-type(1) article div:nth-of-type(2):hover {
     img:nth-of-type(1) {
        transform: matrix(2.1, 0, 0.6, 2.3, -30, 213);
     }
    img:nth-of-type(2) {
        transform: matrix(2.1, 0, -0.4, 2, 46, 101);
    }
   }

   section:nth-of-type(1) article img:nth-of-type(1) {
    transform: matrix(2.1, 0, -0.4, 2, 46, 101);
    position: absolute;
   }

   section:nth-of-type(1) article img:nth-of-type(2) {
     transform: matrix(2.1, 0, 0.6, 2.3, -30, 213);
     position: absolute;
   }

   /* section 2 styling // about me */
   section:nth-of-type(2) {
    color: var(--horizonte);
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 2em;
    padding: 0 2em;
    margin: 5em 0 5em 0;
    container: ab-banner / inline-size;
   }
   section:nth-of-type(2) article {
    display: flex;
    flex-direction: column;
    gap: 1em;
   }

   section:nth-of-type(2) h2 {
    width: 80%;
    border-bottom: .1em solid white;
   }

   section:nth-of-type(2) p {
    font-size: 1em;
    font-weight: 200;
    text-transform: initial;
    max-width: 75ch;
   }

   section:nth-of-type(2) ul {
    list-style: none;
   }
   section:nth-of-type(2) ul a {
    color: var(--horizonte);
    font-weight: 200;
   }

   @container ab-banner (min-width: 500px) {
        section:nth-of-type(2) h2 {
        width: 410px;
   }
    }

   @container list-banner (min-width: 550px) {
        article {
            width: 50%;
        }

        .a-d a div {
          max-width: 50vw;
          padding: .5em .75em;
        }
    }

    @container list-banner (min-width: 1000px) {
        article {
            width: 33.3%;
        }

        .a-d a div {
          max-width: 33.3vw;
          padding: .5em .95em;
        }
    }

    @container list-banner (min-width: 2500px) {
        article {
            width: 25%;
        }

        .a-d a div {
          max-width: 25vw;
          padding: .5em 1.15em;
        }
    }

</style>