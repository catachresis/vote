---
layout: ovm-page
title: '#OurVotesMatter'
menutitle: '#OurVotesMatter'
permalink: /ourvotesmatter/
childcategory: 'ourvotesmatter'
weight: 4
---
## What is #OurVotesMatter?

The right to vote is under attack. It's not just that the Supreme Court gutted the Voting Rights Act last summer. It's that those rights still protected by the VRA are also routinely violated. Reports of voting rights violations were rampant in during the 2012 general election, and there is no reason to believe the sands have shifted. To that end, we have created a tool to report voting rights violations – including everything from voter intimidation, racial and ethnic segregation at the polls, demands for proof of citizenship, and inadequate language translation. 

If you’ve witnessed or heard about any kind of voter disenfranchisement, we encourage you to tell us about it. We’re putting together this data to tell our ballot box stories and to illuminate the pressing need for voter protections – especially in the wake of the Supreme Court’s gutting of the Voting Rights Act. If you indicate that you’d like further assistance with your grievance, we’ll do our best to connect you with advocacy and grassroots groups who may assist you.

We are committed to protecting the identity of all reporters and victims. We will only use anonymized data to map the location and offense. All personal information will be held in confidence and only shared with advocacy partners are the request of victims and reporters.

## Reported Hotspots

<iframe width="500" height="300" scrolling="no" frameborder="no" src="https://www.google.com/fusiontables/embedviz?q=select+col1+from+1CYtVvXfAynsATyN8yT5sTlzj6qtt4XqhAZ8d2sYW&amp;viz=MAP&amp;h=false&amp;lat=38.444984668894705&amp;lng=-95.90927124023438&amp;t=1&amp;z=4&amp;l=col1&amp;y=2&amp;tmplt=2&amp;hml=GEOCODABLE"></iframe>

_[View more reporting data here]({{ baseurl }}/ourvotesmatter/violations)._

{% for post in site.categories['ourvotesmatter'] limit: 2 %}
<div class="a-post">
	<h1><a href="{{ post.url }}">{{ post.catpagetitle }}</a></h1>
	{{ post.content }}
</div>
{% endfor %}