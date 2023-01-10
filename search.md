---
title: "Search"
date: 2023-01-10T14:00:00+02:00
layout: default
noindex: true
---

<style>
	#search-container {
	    max-width: 100%;
	}

	input[type=text] {
	    outline: none;
	    padding: 1rem;
		background: rgb(236, 237, 238);
		width: calc(100% - 2em);
		-webkit-appearance: none;
		font-family: inherit;
		font-size: 100%;
		border: none;
	}
</style>


<article>

<header><h1>{{ include.title | default: page.title }}</h1></header>

<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="Search...">
<ul id="results-container" class="archive"></ul>
</div>

<!-- Script pointing to search-script.js -->
<script src="/search.js" type="text/javascript"></script>
<!-- or without installing anything -->
<!-- <script src="https://unpkg.com/simple-jekyll-search/dest/simple-jekyll-search.min.js"></script> -->

<!-- Configuration -->
<script type="text/javascript">
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json',
  searchResultTemplate: '<li><time>{date}</time><a href="{url}">{title}</a></li>',
  noResultsText: 'No results found',
  limit: 29,
  fuzzy: false,
  exclude: ['Welcome']
})
</script>

</article>
