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
  max-width: 1450px !important;
  float: none !important;
  margin-left: auto !important;
  margin-right: auto !important;
}

.list__item {
  clear: both !important;
  margin-bottom: 40px !important;
}

.archive__item-title,
.archive__item-coauthors,
.archive__item-award {
  white-space: nowrap;
  max-width: 100%;
  overflow: visible;
}

.research-body {
  display: grid;
  grid-template-columns: minmax(0, 0.95fr) minmax(420px, 0.85fr);
  gap: 55px;
  align-items: start;
  margin-top: 8px;
}

.archive__item-excerpt {
  max-width: none !important;
  line-height: 1.55;
}

.research-image {
  display: flex;
  justify-content: flex-end;
  align-items: flex-start;
}

.research-image img {
  width: 100%;
  max-width: 560px;
  height: auto;
  display: block;
}

@media screen and (max-width: 900px) {
  .archive__item-title,
  .archive__item-coauthors,
  .archive__item-award {
    white-space: normal;
  }

  .research-body {
    display: block;
  }

  .research-image {
    margin-top: 18px;
    justify-content: center;
  }
}
</style>
.page {
  width: 100% !important;
  max-width: 1550px !important;
  float: none !important;
  margin-left: auto !important;
  margin-right: auto !important;
  padding-left: 40px !important;
  padding-right: 40px !important;
}

.page__inner-wrap {
  max-width: 1550px !important;
}

.archive {
  width: 100% !important;
  max-width: 1550px !important;
  float: none !important;
}

.research-item {
  display: grid;
  grid-template-columns: 1.1fr 1.2fr;
  gap: 90px;
  align-items: center;
  margin-bottom: 90px;
}

.research-text {
  max-width: 700px;
}

.research-image {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

.research-image img {
  width: 100%;
  max-width: 720px;
  height: auto;
  display: block;
}

@media screen and (max-width: 768px) {
  .research-item {
    display: block;
  }

  .research-image {
    margin-top: 16px;
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