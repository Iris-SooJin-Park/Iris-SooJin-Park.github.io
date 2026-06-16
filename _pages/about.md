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
.page__inner-wrap {
  width: 100% !important;
  max-width: 1350px !important;
  margin-left: auto !important;
  margin-right: auto !important;
}

html {
  scroll-behavior: smooth;
}

.page__content {
  font-size: 0.92em;
}

/* Intro layout */
.home-intro {
  display: grid;
  grid-template-columns: 260px minmax(0, 1fr);
  gap: 55px;
  align-items: start;
  max-width: 1100px;
  margin: 0 auto 24px auto;
}

/* Photo */
.home-photo img {
  width: 100%;
  max-width: 240px;
  height: auto;
  display: block;
}

/* About text */
.home-about {
  padding-top: 8px;
  max-width: 760px;
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

/* Section layout */
.section-divider {
  max-width: 1100px;
  margin: 24px auto 20px auto;
  border: none;
  border-top: 1px solid #e5e5e5;
}

.home-section {
  max-width: 1100px;
  margin: 0 auto 30px auto;
  padding-top: 4px;
}

.home-section h2 {
  margin-top: 0;
  margin-bottom: 12px;
  border-bottom: 1px solid #e5e5e5;
  padding-bottom: 5px;
}

.home-section h3 {
  margin-top: 15px;
  margin-bottom: 5px;
}

.home-section p {
  margin-bottom: 9px;
  max-width: none !important;
}

/* CV */
.cv-section p {
  margin-bottom: 0;
}

/* Research */
.research-section {
  max-width: 1100px;
}

.research-category {
  margin-top: 18px !important;
  margin-bottom: 14px !important;
}

.research-section .list__item,
.research-section .custom-archive-item {
  clear: both !important;
  width: 100% !important;
  max-width: 1100px !important;
  margin-bottom: 28px !important;
}

.research-section .archive__item,
.research-section .custom-archive-article {
  width: 100% !important;
  max-width: 1100px !important;
  float: none !important;
  margin-left: 0 !important;
  margin-right: 0 !important;
}

.research-section .archive__item-title {
  white-space: normal !important;
  max-width: 1100px !important;
  margin-top: 0;
  margin-bottom: 6px;
  font-size: 1.05em;
}

.research-section .archive__item-title a {
  white-space: normal !important;
}

.research-section .archive__item-coauthors,
.research-section .archive__item-award {
  white-space: normal !important;
  max-width: 1100px !important;
}

.publication-abstract,
.publication-abstract p,
.publication-links {
  width: 100% !important;
  max-width: 1100px !important;
  white-space: normal !important;
  line-height: 1.45;
  margin-top: 5px;
  margin-bottom: 8px;
}

.research-section .archive__item-award {
  margin-top: 6px;
  margin-bottom: 8px;
  color: #000;
  white-space: normal !important;
}

.research-section .research-body {
  width: 100% !important;
  max-width: 1100px !important;
}

.research-section .research-body.has-image {
  display: grid !important;
  grid-template-columns: minmax(0, 1fr) 150px;
  gap: 22px;
  align-items: start;
  margin-top: 6px;
}

.research-section .archive__item-excerpt,
.research-section .archive__item-excerpt p,
.research-section .archive__item p {
  width: 100% !important;
  max-width: 1100px !important;
  line-height: 1.45;
  margin-top: 5px;
}

.research-section .research-image {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
}

.research-section .research-image img {
  width: 100%;
  max-width: 150px;
  height: auto;
  display: block;
}

/* Teaching */
.teaching-section {
  max-width: 1100px;
}

.teaching-section .list__item,
.teaching-section .custom-archive-item {
  clear: both !important;
  width: 100% !important;
  max-width: 1100px !important;
  margin-bottom: 24px !important;
}

.teaching-section .archive__item,
.teaching-section .custom-archive-article {
  width: 100% !important;
  max-width: 1100px !important;
  float: none !important;
  margin-left: 0 !important;
  margin-right: 0 !important;
}

.teaching-section .archive__item-title {
  white-space: normal !important;
  max-width: 1100px !important;
  margin-top: 0;
  margin-bottom: 5px;
  font-size: 1.05em;
}

.teaching-meta {
  width: 100% !important;
  max-width: 1100px !important;
  white-space: normal !important;
  line-height: 1.45;
  margin-top: 5px;
  margin-bottom: 8px;
}

.teaching-section .archive__item-excerpt,
.teaching-section .archive__item-excerpt p,
.teaching-section .archive__item p {
  width: 100% !important;
  max-width: 1100px !important;
  line-height: 1.45;
  margin-top: 5px;
}

/* Very strong homepage archive overrides */
.home-section .archive__item,
.home-section .custom-archive-article,
.home-section .archive__item-excerpt,
.home-section .archive__item-excerpt p,
.home-section .archive__item p,
.home-section .publication-abstract,
.home-section .publication-abstract p,
.home-section .publication-links,
.home-section .teaching-meta {
  width: 100% !important;
  max-width: 1100px !important;
  white-space: normal !important;
}

.home-section .archive__item-title,
.home-section .archive__item-title a {
  max-width: 1100px !important;
  white-space: normal !important;
}

.home-section .research-body,
.home-section .research-body.has-image {
  width: 100% !important;
  max-width: 1100px !important;
}

/* Mobile */
@media screen and (max-width: 768px) {
  .home-intro {
    display: block;
    max-width: 100%;
  }

  .home-photo {
    margin-bottom: 18px;
  }

  .home-photo img {
    max-width: 220px;
  }

  .home-about {
    padding-top: 0;
  }

  .home-section {
    margin-bottom: 26px;
  }
}

@media screen and (max-width: 900px) {
  .research-section .research-body.has-image {
    display: block !important;
  }

  .research-section .research-image {
    margin-top: 14px;
    justify-content: center;
  }

  .research-section .research-image img {
    max-width: 210px;
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

{% assign work_in_progress = site.publications | where: "category", "work_in_progress" %}
{% for post in work_in_progress reversed %}
{% include archive-single.html %}
{% endfor %}

</section>

<section id="teaching" class="home-section teaching-section">
  <h2>Teaching</h2>

{% include base_path %}

{% for post in site.teaching reversed %}
{% include archive-single.html %}
{% endfor %}

</section>
