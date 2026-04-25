---
title: "Research"
permalink: /research/
layout: archive
author_profile: false
---

<style>
.page {
  width: 100% !important;
  max-width: 1450px !important;
  float: none !important;
  margin-left: auto !important;
  margin-right: auto !important;
}

.page__inner-wrap {
  max-width: 1450px !important;
}

.archive {
  width: 100% !important;
  max-width: 1450px !important;
  float: none !important;
}

.research-item {
  display: grid;
  grid-template-columns: 0.85fr 1.15fr;
  gap: 65px;
  align-items: center;
  margin-bottom: 90px;
}

.research-text {
  max-width: 560px;
}

.research-image {
  display: flex;
  justify-content: center;
  align-items: center;
}

.research-image img {
  width: 100%;
  max-width: 650px;
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