---
layout: page
title: Spells
permalink: /spells/
---

### 5e Spellbook

A test of how markdown functions in relation to large amounts of post info


<div class="spells">
	{% for post in site.categories['spells'] %}
		<article class="post">

			<h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

			<div class="entry">
				{{ post.excerpt }}
			</div>

			<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
		</article>
	{% endfor %}
</div>
