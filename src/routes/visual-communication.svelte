<script>
    import Header from "$lib/Header.svelte";
    import Nav from "$lib/Nav.svelte";
    import Footer from "$lib/Footer.svelte";
</script>
<Nav />
<Header />



<main class="content">
    <h3>Assessment Tasks</h3>

    <div class="columns">
        <div class="column is-half first-box">
            <div class="l-text">1.Perspective</div>
            <p >Use the box examples on this sheet and create
             on your own page. Start by putting in a line 
             for the horizon and the VP’s then the front side 
             of each box. Then take the sides back to the vanishing
              points. If you get stuck draw the example. Place boxes in 
              all different locations and make them different sizes.
              Use the box examples on this sheet and create on your own page.
              </p>
        </div>

        <div class="column">
            <img src="image10.jpg" alt="Different perspective of boxes"/>       
         </div>
    </div>

    <hr>

    <div class="columns">
        <div class="column is-half">
            <img  src="image8.jpg" alt="Bird houses drawn at different perspective"/>
        </div>

        <div class="column">
            <div class="l-text second-box">2.Perspective Bird Houses</div>
            <p class="second-para">
                Draw the bird houses. Add shadows and textures
            </p>
        </div>
    </div>

    <hr>

    <div class="middle">
        <div class="l-text">3.Scale</div>

    <p>
        explain or work out the following:
    <ul>
        <li>What does 1:2 mean?</li>
        <li>Using 1:1 what size would you draw 100mm at?</li>
        <li>Using 1:20 what size would you draw 100mm at? </li>
        <li>Using 1:50 what size would you draw 100mm at?</li>
        <li>How do you work out scale? Explain this</li>
        <li>What unit of measurement must all dimensions be in?</li>
    </ul>

    </div>


    <hr>

    <div class="columns">
        <div class="column is-half">
            <div class="l-text">4.Architectural Symbols</div>
            <p>
                Draw up a plan view of a room that will show the following. 
                Label each neatly in 3mm caps writing. You can adapt the drawing 
                below or 
                do your own. Think about colour and texture.
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
        </div>

        <div class="column">
            <img src="image9.jpg" alt="floor plan of a room using architectural symbols "/>
        </div>
    </div>

    <hr>

    <div class="columns">
        <div class="column ">
            <img src="image11.png" alt="Example of a plan with measurements"/>
        </div>

        <div class=" five-box column is-two-fifths">
            <div class="l-text">5.Architectural Plans & Elevations</div>
            <p>Draw an accurate
                 to scale 1x floor plan, 3 elevations and 1xperspective of the cabin.</p>
            <br>
            <ul>
                <li>You will be drawing at scale 1:50 for the elevations and floor plan.</li>
                <li>Add the wall thickness (walls are 100mm so will be drawn as 2mm thick )</li>
                <li>Use the diagrams below to work out the correct measurements at scale 1:50</li>
                <li>Once you have completed the plan view (floor plan) complete the 3 e
                    levations and then move onto a perspective sketch.</li>
            </ul>
        </div>
    </div>

    <hr>
    <img src="image7.png" alt="Different view of a mockup design"/>
    <img src="image6.png" alt="Final production"/>
</main>

<!--first mockup
<main class="content">
    <h3>Assessment Tasks</h3>
<br>
    <p>
       <div class="large-text" >1. Perspective</div>
        
        Use the box examples on this sheet and create on your own page.
         Start by putting in a line for the horizon and the VP’s then the
          front side of each box. Then take the sides back to the vanishing
           points. If you get stuck draw the example. Place boxes in all differ
           ent locations and make them different sizes.

        <img class="img-box" src="image10.jpg" alt="Drawings of boxes from different perspective"/>
    

    <p>
        <div class="large-text" >2. Perspective Bird Houses</div>
        
        Draw the bird houses. Add shadows and textures
        <img src="image8.jpg" alt="Bird House draws from different perspective" />
    

    <p>
        <div class="large-text" >3. Scale</div>
        
        explain or work out the following:

<div>
<ol type="a">
    <li> What does 1:2 mean?</li>
    <li>Using 1:1 what size would you draw 100mm at?</li>
    <li>Using 1:20 what size would you draw 100mm at? </li>
    <li>Using 1:50 what size would you draw 100mm at?</li>
    <li>How do you work out scale? Explain this</li>
    <li>What unit of measurement must all dimensions be in?</li>
</ol>
</div>
   <br> 

    <p>
        <div class="large-text" >4. Architectural Symbols</div>

    Draw up a plan view of a room that will show the following. 
    Label each neatly in 3mm caps writing. You can adapt the drawing be
    low or do your own. Think about colour and texture.
    

    <ol type="a">
        <li>Double doors</li>
        <li>3 windows</li>
        <li>Walls</li>
        <li>A sink, a toilet and bath</li>
        <li>Seating</li>
        <li>Add a north symbol used for architecture</li>
        <li>Tiles</li>
        <li>Wooden flooring</li>
    </ol>

    <img src="image9.jpg" alt="Example of a  drawing of a house using architectural symbols"/>

    <p>
        <div class="large-text" >5. Architectural Plans, & Elevations</div>
<br>
        Draw an accurate to scale 1x floor plan, 3 elevations and 1xperspective of the cabin.

        <ul>
            <li>You will be drawing at scale 1:50 for the elevations and floor plan.</li>
            <li>Add the wall thickness (walls are 100mm so will be drawn as 2mm thick )</li>
            <li>Use the diagrams below to work out the correct measurements at scale 1:50</li>
            <li>Once you have completed the plan view (floor plan)
                 complete the 3 elevations and then move onto a perspective sketch.</li>
        </ul>

        
    <img src="image11.png" alt="Architectural plan of a house"/>
    <img class="img-mockup" src="image7.png" alt="Different views of a mockup design"/>
    <img class="img-final" src="image6.png" alt="Final production"/>
</main>-->

<Footer />

<!--style one
<style>
    main{
        font-size:1.2em;
    }
    h3{
        text-align:center;
        font-family: 'Architects Daughter', cursive;
        color:#252323;
    }
    .large-text{
        margin-bottom:5px;
        font-size:1.4em;
        font-family: 'Architects Daughter', cursive;
        
    }
</style>
-->

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
    .l-text{
        font-size:1.8em;
        font-family: 'Josefin Sans', sans-serif;
        color:#C2948A;
    }
    .middle{
        margin-left:300px;
        margin-top:6em;
        margin-bottom:6em;
    }
    .columns{
        margin-top:6em;
        margin-bottom:6em;
    }
    .first-box{
        margin-top:4em;
    }
    .five-box{
        margin:40px;
    }
   h3{
       text-align: center;
       font-size:2.2em;
       font-family: 'Josefin Sans', sans-serif;
       color:#C2948A;
   }
   hr{
       color: rgb(63, 63, 63);
       margin-bottom:2em;
   }

   p{
    font-family: 'Source Sans Pro', sans-serif;
   }

   ul{
    font-family: 'Source Sans Pro', sans-serif;
   }
</style>


