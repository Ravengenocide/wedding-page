---
layout: article
permalink: /
title: "Latest Posts"
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
{{site.url}}
</div><!-- /.tiles -->