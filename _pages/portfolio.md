---
title: "Portfolio"
layout: collection
permalink: /portfolio/
collection: portfolio
entries_layout: grid
author_profile: true
---

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
