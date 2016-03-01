---
layout: default
permalink: /
title: "Comunidad de Software Libre de Venezuela"
---

<div align="center">
<img src="images/cslve.png">
</div>

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
