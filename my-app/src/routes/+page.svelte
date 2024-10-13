<script>
	import BinderElement from '$lib/c-binderElement.svelte';
    import Footer from '$lib/c-footer.svelte';
    import Shader from '$lib/shader.svelte';
    import ViewTransition from './navigation.svelte'


</script>

<div class="app">
    <ViewTransition />
  </div>

<main>
    <h1>Welcome to my</h1>

    <BinderElement />

    <div><h2>Lisa van Mansom</h2>
    <p>frontend designer</p></div>
    <Shader />
</main>

<Footer />

<style>
    main {
        color: var(--jupiter);
        display: flex; flex-direction: column;
        align-items: center; justify-content: center;
        overflow: hidden;
        width: 100%; min-height: 100dvh;
        text-transform: uppercase;
        position: relative;
        gap: 4.5em;
        margin: 3em 0;
    }

    main div { text-align: center; padding: .5em 0 0 0;
        display: flex; flex-direction: column;
        align-items: center; justify-content: center;
        width: 100%; min-height: 100%;
    }

    h1 { font-weight: 300; font-size: 2em; z-index: 10;}
    h2 { font-weight: 200; font-size: 1.4em; z-index: 10;}
    p  { font-weight: 100; font-size: 1.2em; z-index: 10;}



    @media (min-width: 500px) {
        h1 { font-size: 3em;}
        h2 { font-size: 1.9em;}
        p  { font-size: 1.4em;}

        main div { padding: 2.5em 0 0 0; }
    }

    @media (min-width:860px) {
        h1 { font-size: 4em;}
        h2 { font-size: 2.5em;}
        p  { font-size: 1.8em;}
    }

</style>