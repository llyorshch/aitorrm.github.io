---
layout: splash
permalink: /
author_profile: false
date:
header:
  overlay_color: "#5e616c"
  overlay_image: home_header.jpg
  caption:
excerpt: 'Mi visión particular del extenso mundo del desarrollo software.<br /> <small>Java EE, Tendencias, Arquitectura SW, Metodologías, Testing, ...</small><br />'
---

{% include base_path %}

<h3 class="archive__subtitle">Recent Posts</h3>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}
