---
layout: archive
title: "talks and Presentation"
permalink: /presentation/
author_profile: true
---

{% include base_path %}

{% for post in site.presentation reversed %}
  {% include archive-single.html %}
{% endfor %}
