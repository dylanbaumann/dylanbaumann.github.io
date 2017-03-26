---
layout: player
title: Players
permalink: /players/
---

# The Stars of Flywheel D&amp;D Campaign &rsquo;17

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


<section class="player-list">
	{% for post in site.categories['players'] %}
		<div class="player-list-item">
			<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
		</div>
	{% endfor %}
</section>
