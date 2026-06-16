---
permalink: /
title: "Iris SooJin Park"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
.page,
.page__inner-wrap,
.page__content,
.archive {
  width: 100% !important;
  max-width: 1180px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  float: none !important;
}

html {
  scroll-behavior: smooth;
}

.page__content {
  font-size: 0.92em;
}

/* Intro */
.home-intro {
  display: grid;
  grid-template-columns: 250px minmax(0, 1fr);
  gap: 50px;
  align-items: start;
  max-width: 980px;
  margin: 0 auto 32px auto;
}

.home-photo img {
  width: 100%;
  max-width: 235px;
  height: auto;
  display: block;
}

.home-about {
  padding-top: 6px;
  max-width: 700px;
}

.home-about h2 {
  margin-top: 0;
  margin-bottom: 10px;
}

.home-about p {
  margin-bottom: 11px;
}

.job-market-note {
  font-size: 1.02em;
  margin-bottom: 12px !important;
  color: #000;
}

/* Contact links */
.home-links {
  margin-top: 15px;
  font-size: 0.92em;
  display: flex;
  gap: 18px;
  align-items: center;
  flex-wrap: wrap;
}

.home-links p {
  margin: 0;
}

.home-links i {
  margin-right: 5px;
  color: #555;
}

/* Sections */
.section-divider {
  max-width: 980px;
  margin: 28px auto 24px auto;
  border: none;
  border-top: 1px solid #e6e6e6;
}

.home-section {
  width: 980px !important;
  max-width: 980px !important;
  margin: 0 auto 42px auto;
  padding-top: 4px;
}

.home-section h2 {
  margin-top: 0;
  margin-bottom: 18px;
  border-bottom: 1px solid #e5e5e5;
  padding-bottom: 8px;
  font-size: 1.35em;
}

.home-section h3 {
  margin-top: 22px;
  margin-bottom: 14px;
}

.home-section p {
  margin-bottom: 10px;
  max-width: none !important;
}

/* CV */
.cv-section {
  margin-bottom: 36px;
}

.cv-section p {
  margin-bottom: 0;
}

/* Research */
.research-section {
  width: 980px !important;
  max-width: 980px !important;
}

.research-category {
  margin-top: 22px !important;
  margin-bottom: 16px !important;
  font-size: 1.08em;
  font-weight: 700;
  color: #444;
}

.research-section .list__item,
.research-section .custom-archive-item,
.research-section .archive__item,
.research-section .custom-archive-article {
  width: 980px !important;
  max-width: 980px !important;
  clear: both !important;
  float: none !important;
  margin-left: 0 !important;
  margin-right: 0 !important;
}

/* Publication card */
.publication-card {
  width: 980px !important;
  max-width: 980px !important;
  padding: 20px 0 24px 0;
  border-bottom: 1px solid #eeeeee;
}

.publication-card.has-image {
  display: grid !important;
  grid-template-columns: 700px 190px !important;
  gap: 36px !important;
  align-items: start !important;
}

.publication-text {
  width: 700px !important;
  max-width: 700px !important;
}

/* Paper title */
.research-section .archive__item-title,
.research-section .archive__item-title a {
  width: 700px !important;
  max-width: 700px !important;
  white-space: normal !important;
  margin-top: 0;
  margin-bottom: 8px;
  font-size: 1.04rem !important;
  line-height: 1.25;
}

/* Coauthors / abstract line */
.publication-abstract,
.publication-abstract p {
  width: 700px !important;
  max-width: 700px !important;
  white-space: normal !important;
  line-height: 1.45;
  margin-top: 4px;
  margin-bottom: 8px;
}

/* Links */
.publication-links {
  width: 700px !important;
  max-width: 700px !important;
  margin-top: 6px;
  margin-bottom: 10px;
}

/* Award */
.research-section .archive__item-award {
  width: 700px !important;
  max-width: 700px !important;
  margin-top: 6px;
  margin-bottom: 10px;
  color: #000;
  white-space: normal !important;
  line-height: 1.35;
}

/* Body */
.research-section .archive__item-excerpt,
.research-section .archive__item-excerpt p {
  width: 700px !important;
  max-width: 700px !important;
  line-height: 1.48;
  margin-top: 6px;
}

/* No-image papers use full width */
.publication-card:not(.has-image),
.publication-card:not(.has-image) .publication-text,
.publication-card:not(.has-image) .archive__item-title,
.publication-card:not(.has-image) .archive__item-title a,
.publication-card:not(.has-image) .publication-abstract,
.publication-card:not(.has-image) .publication-abstract p,
.publication-card:not(.has-image) .publication-links,
.publication-card:not(.has-image) .archive__item-excerpt,
.publication-card:not(.has-image) .archive__item-excerpt p {
  width: 980px !important;
  max-width: 980px !important;
}

/* Image starts at title level, but stays modest */
.research-image {
  width: 190px !important;
  max-width: 190px !important;
  display: flex;
  align-items: flex-start;
  justify-content: center;
  padding-top: 2px;
}

.research-image img {
  width: 190px !important;
  max-width: 190px !important;
  height: auto !important;
  max-height: 190px !important;
  object-fit: contain;
  display: block;
  border: 1px solid #eeeeee;
  background: #ffffff;
}

/* Compact Work in Progress list */
.work-in-progress-list {
  margin-top: 4px;
  margin-bottom: 24px;
}

.compact__item.custom-archive-item {
  width: 100% !important;
  max-width: 980px !important;
  margin-bottom: 9px !important;
}

.compact-paper-item {
  width: 100% !important;
  max-width: 980px !important;
  line-height: 1.45;
  margin-bottom: 9px;
}

.compact-paper-title {
  font-weight: 700;
}

.compact-paper-title a {
  text-decoration: underline;
}

.compact-paper-meta,
.compact-paper-meta p {
  color: #333;
  display: inline;
  margin: 0;
}

/* Compact Teaching list */
.teaching-list {
  margin-top: 4px;
  margin-bottom: 24px;
}

.teaching_compact__item.custom-archive-item {
  width: 100% !important;
  max-width: 980px !important;
  margin-bottom: 14px !important;
}

.compact-teaching-item {
  width: 100% !important;
  max-width: 980px !important;
  padding: 0 0 14px 0;
  margin-bottom: 14px;
  border-bottom: 1px solid #eeeeee;
}

.compact-teaching-title {
  font-weight: 700;
  font-size: 1.02rem;
  line-height: 1.35;
  margin-bottom: 4px;
}

.compact-teaching-meta {
  font-size: 0.95rem;
  line-height: 1.4;
  color: #333;
}

/* Mobile */
@media screen and (max-width: 900px) {
  .page,
  .page__inner-wrap,
  .page__content,
  .archive,
  .home-section,
  .research-section,
  .teaching-section,
  .publication-card,
  .publication-text {
    width: 100% !important;
    max-width: 100% !important;
  }

  .home-intro {
    display: block;
    max-width: 100%;
  }

  .home-photo {
    margin-bottom: 18px;
  }

  .home-photo img {
    max-width: 230px;
  }

  .home-about {
    padding-top: 0;
  }

  .publication-card.has-image {
    display: block !important;
  }

  .research-section .archive__item-title,
  .research-section .archive__item-title a,
  .publication-abstract,
  .publication-abstract p,
  .publication-links,
  .research-section .archive__item-award,
  .research-section .archive__item-excerpt,
  .research-section .archive__item-excerpt p {
    width: 100% !important;
    max-width: 100% !important;
  }

  .research-image {
    margin-top: 14px;
    width: 100% !important;
    max-width: 100% !important;
    justify-content: center;
  }

  .research-image img {
    width: 210px !important;
    max-width: 210px !important;
    height: auto !important;
    max-height: none !important;
  }

  .home-section {
    margin-bottom: 32px;
  }
}
</style>

<div class="home-intro">

  <!-- Photo -->

  <div class="home-photo">
    <img src="images/DSC09184_edit.jpg" alt="Iris Park">
  </div>

  <!-- About -->

  <div class="home-about">
    <h2>A little about me</h2>

<p class="job-market-note">
  <strong>I am currently on the 2026–2027 academic job market.</strong>
</p>

<p>
  I am a PhD candidate in the 
  <a href="https://business.wisc.edu/faculty-research/risk-insurance/">
    Department of Risk and Insurance
  </a>
  at the University of Wisconsin-Madison's Wisconsin School of Business, 
  with an expected graduation in Spring 2027.
</p>

<p>
  My interests include the study of health insurance, household financial 
  decision-making under risk, and behavioral responses to insurance design, 
  incentives, and information.
</p>

<p>
  Before joining the risk and insurance department, I earned undergraduate 
  degrees in economics and mathematics from the University of Wisconsin-Madison 
  in May 2021, graduating with distinction.
</p>

<!-- Contact -->
<div class="home-links">
  <p><i class="fa fa-fw fa-university"></i> UW-Madison</p>

  {% if site.author.email %}
    <p>
      <i class="fa fa-fw fa-envelope"></i>
      <a href="mailto:{{ site.author.email }}">Email</a>
    </p>
  {% endif %}

  {% if site.author.linkedin %}
    <p>
      <i class="fab fa-fw fa-linkedin"></i>
      <a href="https://www.linkedin.com/in/{{ site.author.linkedin | replace: '/', '' }}">
        LinkedIn
      </a>
    </p>
  {% endif %}
</div>

  </div>

</div>

<hr class="section-divider">

<section id="cv" class="home-section cv-section">
  <h2>CV</h2>

  <p>
    You can download my CV 
    <a href="/files/Iris_SooJin_Park_CV(recent).pdf" target="_blank">here</a>.
  </p>
</section>

<section id="research" class="home-section research-section">
  <h2>Research</h2>

{% include base_path %}

  <h3 class="research-category">Working Papers</h3>

{% assign working_papers = site.publications | where: "category", "working_papers" %}
{% for post in working_papers reversed %}
{% include archive-single.html %}
{% endfor %}

  <h3 class="research-category">Work in Progress</h3>

  <div class="work-in-progress-list">
    {% assign work_in_progress = site.publications | where: "category", "work_in_progress" %}
    {% for post in work_in_progress reversed %}
      {% include archive-single.html type="compact" %}
    {% endfor %}
  </div>

</section>

<section id="teaching" class="home-section teaching-section">
  <h2>Teaching</h2>

  <div class="teaching-list">
    {% include base_path %}

    {% for post in site.teaching reversed %}
      {% include archive-single.html type="teaching_compact" %}
    {% endfor %}
  </div>
</section>
