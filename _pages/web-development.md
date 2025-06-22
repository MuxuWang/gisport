---
layout: archive
title: "Web Development"
permalink: /web-development/
author_profile: true
---
[WildinWords](https://wildinwords.github.io/wiw/) is a minimalist writing platform I designed and developed to explore raw storytelling through constraint-driven creativity. The website is a digital blog series aims to bridge public art and environmental education by making biodiversity learning easy, engaging, and meaningful.

---

{% include base_path %}

{% for post in site.GIS-maps %}
  {% include archive-single.html %}
{% endfor %}
