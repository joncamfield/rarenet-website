---
layout: archive-wide
classes:
  - wide
permalink: /news/
title: "News"
author_profile: false
header:
  overlay_image: /images/jeremy-thomas-128457-unsplash.jpg
  caption: "Photo by Jeremy Thomas on Unsplash"
---

{% include base_path %}
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
