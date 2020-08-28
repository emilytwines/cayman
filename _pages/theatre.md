---
layout: archive
title: "Theatre"
permalink: /theatre/
author_profile: true
---

{% include base_path %}

{% for post in site.theatre reversed %}
  {% include archive-single.html %}
{% endfor %}
