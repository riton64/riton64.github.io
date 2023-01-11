---
title: "Search"
date: 2023-01-10T14:00:00+02:00
layout: default
noindex: true
---


<article>

<header><h1>{{ include.title | default: page.title }}</h1></header>

<!-- Html Elements for Search -->
<form action="http://www.google.com/search" method="get">
    <input type="text" name="q"/>
    <input type="submit" value="search" />
</form>


<!-- Script pointing to search-script.js -->
<!--<script src="/search.js" type="text/javascript"></script> -->
<!-- or without installing anything -->
<!-- <script src="https://unpkg.com/simple-jekyll-search/dest/simple-jekyll-search.min.js"></script> -->
 

<!-- Configuration -->


</article>
