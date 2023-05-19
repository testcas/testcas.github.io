---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
