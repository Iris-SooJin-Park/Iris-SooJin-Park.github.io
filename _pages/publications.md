---
title: "Research"
permalink: /research/
author_profile: true
---

{% for post in site.publications %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | default: post.abstract | markdownify }}</p>
{% endfor %}
