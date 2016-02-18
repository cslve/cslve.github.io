---
layout: default 
permalink: /
title: "Comunidad de Software Libre de Venezuela"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
