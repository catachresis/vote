---
layout: page
title: 'For Voters'
menutitle: 'For Voters'
permalink: /voters/
childcategory: 'forvoters'
weight: 3
---

<h1 class="exciting-title" id="nomargin"><a href="https://register2.rockthevote.com/?partner=16591&source=embed-rtv234x60v1" class="floatbox" data-fb-options="width:618 height:max scrolling:yes">Click here to Get Registered!</a></h1>
<script type="text/javascript" src="https://register2.rockthevote.com/widget_loader.js"></script>

Registering to vote is your first, but all-important, step. Mark your calendar for Election Day!

If you prefer to vote by mail, chances are you need to order a ballot. Order quickly here:

<h1 class="exciting-title" id="nomargin"><a href="{{ baseurl }}/forvoters/mailin/">Order a Mail-in Ballot!</a></h1>

{% for post in site.categories['forvoters'] limit: 2 %}
<div class="a-post">
	<h1><a href="{{ post.url }}">{{ post.catpagetitle }}</a></h1>
	{{ post.content }}
</div>
{% endfor %}