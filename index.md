<html>

<head>
  <meta charset="UTF-8">
  <title>Side-saddle scrollytelling with position sticky and enterview</title>
  
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css">

  
      <link rel="stylesheet" href="css/style.css">

  
</head>

<body>

<!--   <section class='filler'>
  <p>
    <h1>Welcome!</h1>
  </p>
</section> -->
<!-- 
<input type="button" value="Go Back From Whence You Came!" onclick="history.back(-1)" />
<input type="button" value="back to main page" onclick="https://natephil.github.io/" /> -->

<form action="https://natephil.github.io/">
    <input type="submit" value="Back to homepage" />
</form>


<section id='scrolly-side'>
  
  <div class='scrolly'>
    
    <!--  step text   -->
	  <article>
      <div class='step' data-width='10%' data-index='0'>
          <p>Bar is 10%</p>
      </div>
      <div class='step' data-width='90%' data-index='1'>
         <p>Bar is 90%</p>
      </div>
      <div class='step' data-width='50%' data-index='2'>
        <p>Bar is 50%</p>
      </div>
      <div class='step' data-width='75%' data-index='3'>
        <p>Bar is 75%</p>
      </div>
	  </article>
    
     <!--  sticky graphic   -->
	  <figure class='sticky'>
		  <div class='bar-outer'>
			  <div class='bar-inner'></div>
  		</div>
  	</figure>
    
  </div>
  
</section>

<!-- <section class='filler'>
  <p>
    End
  </p>
</section> -->
  <script src='https://unpkg.com/d3@5.4.0/dist/d3.min.js'></script>
<script src='https://unpkg.com/enter-view@1.0.0/enter-view.min.js'></script>
<script src='https://unpkg.com/stickyfilljs@2.0.5/dist/stickyfill.js'></script>

  

    <script  src="js/index.js"></script>

<footer>
  The above graph was made by Nathan Cahn<br>
  &#x1F34C;
</footer>

</body>

</html>
