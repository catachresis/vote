---
layout: page
title: 'For Voters'
menutitle: 'For Voters'
permalink: /voters/
childcategory: 'forvoters'
weight: 3
---

<h1 class="exciting-title" id="nomargin"><a href="{{ baseurl }}/voters/tofw">Turn Out For What?</a></h1>

What are you turning out for this election season? <a href="{{ baseurl }}/voters/tofw">Watch a video. Share your own.</a> Turn out.

Did you know that you can still order a mail-in ballot in most states?

<h1 class="exciting-title" id="nomargin"><a href="{{ baseurl }}/forvoters/mailin/">Order a Mail-in Ballot!</a></h1>

{% for post in site.categories['forvoters'] limit: 2 %}
<div class="a-post">
	<h1><a href="{{ post.url }}">{{ post.catpagetitle }}</a></h1>
	{{ post.content }}
</div>
{% endfor %}