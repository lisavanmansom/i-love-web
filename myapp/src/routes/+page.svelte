<script>
	import BinderElement from '$lib/c-binderElement.svelte';
    import Footer from '$lib/c-footer.svelte';

</script>

<main>
    <h1>Welcome to my</h1>

    <BinderElement />

    <h2>Lisa van Mansom</h2>
    <p>frontend designer</p>
</main>

<Footer />

<style>
    main {
        background-color: var(--beijo); color: var(--jupiter);
        display: flex; flex-direction: column;
        align-items: center; justify-content: center;
        overflow-y: hidden;
        width: 100%; min-height: 100dvh;
        text-transform: uppercase;
    }

    h1 { font-weight: 300; font-size: 2em;}
    h2 { font-weight: 200; font-size: 1.4em;}
    p  { font-weight: 100; font-size: 1.2em;}

    @media (min-width: 500px) {
        h1 { font-size: 3em;}
        h2 { font-size: 1.9em;}
        p  { font-size: 1.4em;}
    }

    @media (min-width:860px) {
        h1 { font-size: 4em;}
        h2 { font-size: 2.5em;}
        p  { font-size: 1.8em;}
    }

</style>