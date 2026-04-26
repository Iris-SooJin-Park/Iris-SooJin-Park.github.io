---
title: "Research"
permalink: /research/
layout: archive
author_profile: false
---
<style>
.page,
.page__inner-wrap,
.archive,
.list__item,
.archive__item {
  width: 100% !important;
  max-width: 1400px !important;
  float: none !important;
  margin-left: auto !important;
  margin-right: auto !important;
}

.list__item {
  clear: both !important;
  margin-bottom: 50px !important;
}

.archive__item-title {
  white-space: normal;
}

.archive__item-coauthors,
.archive__item-award {
  white-space: nowrap;
}

.research-body.has-image {
  display: grid !important;
  grid-template-columns: minmax(0, 900px) 300px;
  gap: 40px;
  align-items: start;
  margin-top: 10px;
}

.archive__item-excerpt {
  line-height: 1.55;
  max-width: 900px !important;
}

.archive__item-excerpt.no-image {
  max-width: 1100px !important;
}

.research-image {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
}

.research-image img {
  width: 100%;
  max-width: 300px;
  height: auto;
  display: block;
}

@media screen and (max-width: 900px) {
  .archive__item-coauthors,
  .archive__item-award {
    white-space: normal;
  }

  .research-body.has-image {
    display: block !important;
  }

  .research-image {
    margin-top: 18px;
    justify-content: center;
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