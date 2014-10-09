---
layout: ovm-page
title: '#OurVotesMatter | Reported Violations'
catpagetitle: 'Reported Violations'
menutitle: 'Reported Violations'
categories: 
- exclude
- ourvotesmatter
permalink: /ourvotesmatter/violations/
date: 2014-09-02
---
<iframe width="630" height="400" scrolling="no" frameborder="no" src="https://www.google.com/fusiontables/embedviz?q=select+col1+from+1CYtVvXfAynsATyN8yT5sTlzj6qtt4XqhAZ8d2sYW&amp;viz=MAP&amp;h=false&amp;lat=39.5033&amp;lng=-98.35&amp;t=1&amp;z=4&amp;l=col1&amp;y=2&amp;tmplt=2&amp;hml=GEOCODABLE"></iframe>

## Stories

{% for post in site.categories['violations'] %}
<div class="a-post">
	<h1><a href="{{ post.url }}">{{ post.catpagetitle }}</a></h1>
	{{ post.content }}
</div>
{% endfor %}