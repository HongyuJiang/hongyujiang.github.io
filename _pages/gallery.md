---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

{% include base_path %}

{% for post in site.gallery reversed %}
  {% include archive-single.html %}
{% endfor %}
