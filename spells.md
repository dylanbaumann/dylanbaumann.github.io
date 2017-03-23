---
layout: page
title: Spells
permalink: /spells/
---

### 5e Spellbook

A test of how markdown functions in relation to large amounts of post info


<section class="spells-list">
	{% for post in site.categories['spells'] %}
		<div class="spells-list-item">
			<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
		</div>
	{% endfor %}
</section>
