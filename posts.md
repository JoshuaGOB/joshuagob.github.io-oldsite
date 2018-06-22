---
layout: archive
permalink: /_posts
title: "Latest Posts"
image:
  teaser: 400x250.gif
  feature: feature-image-filename.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
