---
title: page_one
layout: page
---
# Bonjour le monde !!!
<bg>
 <img src="/images/biarritz1-1-23.jpg">
 <figcaption>Biarritz ce 1er janvier 2023.</figcaption>
 <bg>
  <img src="/images/costume0.jpg">
  <figcaption>Ma chatte virtuelle bien aimée</figcaption>
  
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Page principale</title>
    <link rel="stylesheet" href="site.css">
    <link rel="stylesheet" href="theme.css" />
	<script src="jquery.min.js"></script>
    <script src="jquery-ui.js"></script>
	<script>
      $(function() {
        $("#menu").menu();
      });
    </script>
  </head>
  <body>
    <header id="entete">
	  <img id="image" src="html5css3jQuery.png">
      <span id="titre">Balade en Bigorre  mars 2020</span>
    </header>
    <nav id="lemenu">
	  <ul id="menu">
	    <li><a href="apropos.htm">Album Photos</a></li>
        
      </ul>  
	</nav>	
	  
	<article id="corps">
		<p id ="titre">
	  Album de photos
		Prises autour de Lourdes by Henri</p>
    </article>	
    <footer id="basdepage">
      
      <span id="copy">Copyright (c) 2020</span>
	</footer> 
    <script>
      $(function(){
        $('#uni').click(function(){
	      $('#corps').css('background','white');
	    });
      });
    </script>
  </body>
</html>
