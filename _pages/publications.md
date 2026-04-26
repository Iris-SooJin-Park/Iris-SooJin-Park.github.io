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
  max-width: 1800px !important;
  float: none !important;
  margin-left: auto !important;
  margin-right: auto !important;
}

.list__item {
  clear: both !important;
  margin-bottom: 45px !important;
}

.archive__item-title,
.archive__item-coauthors,
.archive__item-award {
  white-space: nowrap;
}

.research-body {
  display: grid !important;
  grid-template-columns: minmax(850px, 1fr) 560px;
  gap: 70px;
  align-items: start;
  margin-top: 10px;
}

.archive__item-excerpt {
  max-width: none !important;
  line-height: 1.55;
}

.research-image {
  display: flex;
  justify-content: flex-end;
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
    display: block !important;
  }

  .research-image {
    margin-top: 18px;
    justify-content: center;
  }
}
<style>
.page,
.page__inner-wrap,
.archive,
.list__item,
.archive__item {
  width: 100% !important;
  max-width: 1250px !important;
  float: none !important;
  margin-left: auto !important;
  margin-right: auto !important;
}

.list__item {
  clear: both !important;
  margin-bottom: 55px !important;
}

.archive__item-title,
.archive__item-coauthors,
.archive__item-award {
  white-space: nowrap;
}

.research-body {
  display: grid !important;
  grid-template-columns: minmax(0, 720px) 420px;
  gap: 45px;
  align-items: start;
  margin-top: 10px;
}

.archive__item-excerpt {
  max-width: 720px !important;
  line-height: 1.55;
}

.research-image {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
}

.research-image img {
  width: 100%;
  max-width: 420px;
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