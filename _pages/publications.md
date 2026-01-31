---
title: "Research"
permalink: /research/
author_profile: true
---

{% for post in site.publications %}
<h3>
  {% if post.no_link %}
    {{ post.title }}
  {% else %}
    <a href="{{ post.url }}">{{ post.title }}</a>
  {% endif %}
</h3>
  <p>{{ post.excerpt | default: post.abstract | markdownify }}</p>
{% endfor %}
