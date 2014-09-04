---
layout: page
title: 'For Partners'
menutitle: 'For Partners'
permalink: /partners/
childcategory: forpartners
weight: 2
---
Becoming a partner is easy! All you have to do is sign up, set up a simple widget, and you're on your way to registering voters online through your website.

As a partner, you get access to support from the 18MR team, the list of voters you've registered via your widget, and more. Here's what it takes to get started:

{% for post in site.categories['forpartners'] %}
<div class="a-post">
	<h1><a href="{{ post.url }}">{{ post.catpagetitle }}</a></h1>
	{{ post.content }}
</div>
{% endfor %}