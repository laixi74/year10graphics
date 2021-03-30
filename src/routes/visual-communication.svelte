<script>
    import Header from "$lib/Header.svelte";
    import Nav from "$lib/Nav.svelte";
    import Footer from "$lib/Footer.svelte";
</script>

<Nav />
<Header />

<main>
    <h3>Assessment Tasks</h3>

    <p>
        1. Perspective
        Use the box examples on this sheet and create on your own page.
         Start by putting in a line for the horizon and the VP’s then the
          front side of each box. Then take the sides back to the vanishing
           points. If you get stuck draw the example. Place boxes in all differ
           ent locations and make them different sizes.

        <img src="image10.jpg" alt="Drawings of boxes from different perspective"/>
    </p>

    <p>
        2. Perspective Bird Houses
Draw the bird houses. Add shadows and textures
<img src="image8.jpg" alt="Bird House draws from different perspective" />
    </p>

    <p>
        3. Scale
explain or work out the following:
<ul>
    <li>What does 1:2 mean?</li>
    <li>Using 1:1 what size would you draw 100mm at?</li>
    <li>Using 1:20 what size would you draw 100mm at? </li>
    <li>Using 1:50 what size would you draw 100mm at?</li>
    <li>How do you work out scale? Explain this</li>
    <li>What unit of measurement must all dimensions be in?</li>

</ul>
    

    <p>
        4. Architectural Symbols

    Draw up a plan view of a room that will show the following. 
    Label each neatly in 3mm caps writing. You can adapt the drawing be
    low or do your own. Think about colour and texture.

    <ul>
        <li>Double doors</li>
        <li>3 windows</li>
        <li>Walls</li>
        <li>A sink, a toilet and bath</li>
        <li>Seating</li>
        <li>Add a north symbol used for architecture</li>
        <li>Tiles</li>
        <li>Wooden flooring</li>
    </ul>
    <img src="image9.jpg" alt="Example of a  drawing of a house using architectural symbols"/>

    <p>
        5. Architectural Plans, & Elevations

        Draw an accurate to scale 1x floor plan, 3 elevations and 1xperspective of the cabin.

        <ul>
            <li>You will be drawing at scale 1:50 for the elevations and floor plan.</li>
            <li>Add the wall thickness (walls are 100mm so will be drawn as 2mm thick )</li>
            <li>Use the diagrams below to work out the correct measurements at scale 1:50</li>
            <li>Once you have completed the plan view (floor plan)
                 complete the 3 elevations and then move onto a perspective sketch.</li>
        </ul>
    <img src="image11.png" alt="Architectural plan of a house"/>
    <img src="image7.png" alt="Different views of a mockup design"/>
    <img src="image6.png" alt="Final production"/>
</main>
<Footer />

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
            /1fr 2.5fr  1fr;
    }
    /* GLOBAL STYLES */
    :global(img) {
        margin:30px;
        width:100%;
    }
</style>