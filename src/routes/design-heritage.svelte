<script>
    import Header from "$lib/Header.svelte";
    import Nav from "$lib/Nav.svelte";
    import Footer from "$lib/Footer.svelte";
</script>

<Nav />
<Header />



<main class="content">
<h3>Design Heritage</h3>
<p class="subtitle">Homework Task</p>

<div class="columns">
    <div class=" box-one column is-half">
        <div class="l-text">SIZE: 1 x A3 Maximum</div>
        Pick one of the following Architects to create an A3 poster, 
        read the assessment criteria:
        
        <ul>
            <li>Mies Van der Rohe</li>
            <li>Zaha Hadid</li>
            <li>Frank Gehery</li>
            <li>Le Cobuisier</li>
            <li>Frank Lloyd Wright</li>
            <li>Daniel Libeskind</li>  
        </ul>
    </div>

        <div class="column">
            <img src="image4.jpg" alt="Art and architecture:their link through the years"/>
        </div>

</div>

<div class="second-section">

<div class="l-text">Creative Challenge...</div>
        Your presentation should reflect the style of the a
        rchitect you have studied (shapes colours textures etc.).
        <br>
        <br>
        <br>
        <br>
        <div class="l-text">Answer...</div>
        <div class="color-t">What are the key features of their work?- 
            aesthetic (looks) and functional (working)</div>
        <ul>
            <li>Include examples of their work and a little notes</li>
        </ul>
        <br>
        
        <p class="color-t">What context do they work within?- what cultural/historica
            l/society or technological things influence their work?</p>

        
        <ul>
            <li>Do they have a design philosophy?- what do they try and do or think about design</li>
            <li>How long have they been designing?</li>
            <li>What are the main materials their buildings are made from?</li>
            <li>Are there any interesting facts you have found about them?</li>
            <li>Include a quote that they have said</li>
        </ul>
    </div>
</main>
<!--mockup one
<main class="content">
<h3>Design Heritage</h3>

<br>
<div class="l-text">Homework Task</div>

<p>
<div class="l-text">SIZE: 1 x A3 Maximum</div>
Pick one of the following Architects to create an A3 poster, read the assessment criteria:


<ul>
    <li>Mies Van der Rohe</li>
    <li>Zaha Hadid</li>
    <li>Frank Gehery</li>
    <li>Le Cobuisier</li>
    <li>Frank Lloyd Wright</li>
    <li>Daniel Libeskind</li>
</ul>
<br>

<p>
<div class="l-text"> Creative Challenge... </div>
Your presentation should reflect the style of the architect you have studied (shapes colours textures etc.).

<br>
<br>
<div class="l-text">Answer...</div>
<div class="colour-t">What are the <u>key features</u> of their work?- aesthetic (looks) and functional (working)</div>
<ul>
    <li>Include examples of their work and a little notes</li>
</ul>
<br>

<div class="colour-t">What <u>context</u> do they work within?- what cultural/historical/society or technological things influence their work?</div>
<ul>
    <li>Do they have a design philosophy?- what do they try and do or think about design</li>
    <li>How long have they been designing?</li>
    <li>What are the main materials their buildings are made from?</li>
    <li>Are there any interesting facts you have found about them?</li>
    <li>Include a quote that they have said</li>
</ul>

<img src="image4.jpg" alt="Art and architecture:their link through the years"/>

</main>-->

<Footer />

<style>
    p{
        font-family: 'Source Sans Pro', sans-serif;
    }
    ul{
        font-family: 'Source Sans Pro', sans-serif;
    }
    .box-one{
        margin-top:50px;
        font-family: 'Source Sans Pro', sans-serif;
    }
    h3{
        text-align:center;
        font-size:2em;
        font-family: 'Josefin Sans', sans-serif;
        color:#C2948A;
    }
    .subtitle{
        font-size:2em;
        margin-top:6em;
        font-family: 'Josefin Sans', sans-serif;
        color:#C2948A;
    }
    .l-text{
        font-size:1.7em;
        font-family: 'Josefin Sans', sans-serif;
        color:#C2948A;
    }
    .columns{
        margin-bottom:8em;
    }
    .second-section{
        margin-left:100px;
    }
    .color-t{
        color:#C2948A;
    }
</style>

<!--style one
<style>
    main{
        font-size:1.2em;
        
    }
    h3{
        text-align:center;
        margin-top:30px;
        margin-bottom:30px;
        font-family: 'Architects Daughter', cursive;
    }
    .l-text{
        font-size:1.2em;
        font-family: 'Architects Daughter', cursive;
        color:#252323;
    }
    .colour-t{
        color:#70798C;
    }
    p{
        font-family: 'Source Sans Pro', sans-serif;
    }
</style>-->