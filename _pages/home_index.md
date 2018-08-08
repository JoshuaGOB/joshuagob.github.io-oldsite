---

layout: archive

permalink: "/home/"
author_profile: true
classes:
  - landing
---
{% include adjusted_fixed_image_for_home.html %}


<h1>Posts</h1>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
{% unless collection.output == false or collection.label == "posts" %}
  {% capture label %}{{ collection.label }}{% endcapture %}
  {% if label != written_label %}
  <h4>{{ label }}</h4>
  {% capture written_label %}{{ label }}{% endcapture %}
  {% endif %}
{% endunless %}
{% for post in collection.docs %}
  {% unless collection.output == false or collection.label == "posts" %}
  {% include archive-single0.html %}
  {% endunless %}
{% endfor %}
{% endfor %}
