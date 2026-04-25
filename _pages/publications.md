---
title: "Research"
permalink: /research/
layout: archive
author_profile: false
---

<style>
.page {
  width: 100% !important;
  max-width: 1200px !important;
  float: none !important;
  margin-left: auto !important;
  margin-right: auto !important;
}

.page__inner-wrap {
  max-width: 1200px !important;
}

.archive {
  width: 100% !important;
  max-width: 1200px !important;
  float: none !important;
}

.research-item {
  display: grid;
  grid-template-columns: 1.1fr 0.9fr;
  gap: 40px;
  align-items: start;
  margin-bottom: 60px;
}

.research-image img {
  width: 100%;
  height: auto;
  display: block;
}

@media screen and (max-width: 768px) {
  .research-item {
    display: block;
  }

  .research-image {
    margin-top: 16px;
  }
}
</style>

{% include base_path %}

## Working Papers

{% assign working_papers = site.publications | where: "category", "working_papers" %}
{% for post in working_papers %}
  {% include archive-single.html %}
{% endfor %}

## Work in Progress

{% assign work_in_progress = site.publications | where: "category", "work_in_progress" %}
{% for post in work_in_progress %}
  {% include archive-single.html %}
{% endfor %}