<script>
    import Header from "$lib/Header.svelte";
    import Nav from "$lib/Nav.svelte";
    import Footer from "$lib/Footer.svelte";
</script>

<Header />
<Nav />


<!--mockup one
<main>
<img src="image12.jpg" alt="Drawing of a large Cabin Design"/>
<img src="image2.png" alt="Cabin design example" /> 
</main>-->

<Footer />


<!--style one
<style>
    /* LAYOUT */
    :global(Header) { grid-area: h; }
    :global(Nav)    { grid-area: n; }
    :global(main)   { grid-area: m; }
    :global(Footer) { grid-area: f; }
  
    :global(#svelte) {
      display: grid;
      grid: " .   n   ." auto
            " .   h   ." auto
            " .   m   ." auto
            " f   f   f" auto
            /1fr 2fr  1fr;
    }
    /* GLOBAL STYLES */
    :global(img) {
        margin:30px;
        width:100%;
    }
</style>
-->

