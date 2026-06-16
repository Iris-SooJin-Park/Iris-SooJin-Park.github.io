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
  max-width: 1320px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  float: none !important;
}

html {
  scroll-behavior: smooth;
}

.page__content {
  font-size: 0.94em;
}

/* Intro layout */
.home-intro {
  display: grid;
  grid-template-columns: 270px minmax(0, 1fr);
  gap: 58px;
  align-items: start;
  max-width: 1120px;
  margin: 0 auto 34px auto;
}

.home-photo img {
  width: 100%;
  max-width: 255px;
  height: auto;
  display: block;
}

.home-about {
  padding-top: 8px;
  max-width: 780px;
}

.home-about h2 {
  margin-top: 0;
  margin-bottom: 10px;
}

.home-about p {
  margin-bottom: 12px;
}

.job-market-note {
  font-size: 1.02em;
  margin-bottom: 13px !important;
  color: #000;
}

/* Contact links */
.home-links {
  margin-top: 16px;
  font-size: 0.93em;
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
  max-width: 1120px;
  margin: 28px auto 24px auto;
  border: none;
  border-top: 1px solid #e6e6e6;
}

.home-section {
  width: 100% !important;
  max-width: 1120px !important;
  margin: 0 auto 42px auto;
  padding-top: 6px;
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

/* Research section */
.research-section {
  width: 100% !important;
  max-width: 1120px !important;
}

.research-category {
  margin-top: 24px !important;
  margin-bottom: 18px !important;
  font-size: 1.08em;
  font-weight: 700;
  color: #444;
}

/* Each publication item */
.research-section .list__item,
.research-section .custom-archive-item {
  clear: both !important;
  width: 100% !important;
  max-width: 1120px !important;
  margin-bottom: 24px !important;
}

.research-section .archive__item,
.research-section .custom-archive-article {
  width: 100% !important;
  max-width: 1120px !important;
  float: none !important;
  margin-left: 0 !important;
  margin-right: 0 !important;
}

/* Card-like paper layout */
.publication-card {
  width: 100% !important;
  max-width: 1120px !important;
  padding: 18px 0 20px 0;
  border-bottom: 1px solid #eeeeee;
}

.publication-card.has-image {
  display: grid !important;
  grid-template-columns: minmax(0, 1fr) 170px;
  gap: 34px;
  align-items: start;
}

.publication-text {
  width: 100% !important;
  max-width: 900px !important;
}

.research-section .archive__item-title,
.research-section .archive__item-title a {
  white-space: normal !important;
  max-width: 900px !important;
  margin-top: 0;
  margin-bottom: 8px;
  font-size: 1.05em;
  line-height: 1.25;
}

.publication-abstract,
.publication-abstract p {
  width: 100% !important;
  max-width: 900px !important;
  white-space: normal !important;
  line-height: 1.45;
  margin-top: 4px;
  margin-bottom: 8px;
}

.publication-links {
  width: 100% !important;
  max-width: 900px !important;
  margin-top: 6px;
  margin-bottom: 10px;
}

.research-section .archive__item-award {
  margin-top: 6px;
  margin-bottom: 10px;
  color: #000;
  white-space: normal !important;
  line-height: 1.35;
}

.research-section .archive__item-excerpt,
.research-section .archive__item-excerpt p {
  width: 100% !important;
  max-width: 900px !important;
  line-height: 1.48;
  margin-top: 6px;
}

.research-section .archive__item-excerpt.no-image,
.research-section .archive__item-excerpt.no-image p {
  max-width: 1050px !important;
}

.research-image {
  width: 170px !important;
  max-width: 170px !important;
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  padding-top: 2px;
}

.research-image img {
  width: 170px !important;
  max-width: 170px !important;
  height: auto;
  display: block;
  border: 1px solid #eeeeee;
}

/* Teaching */
.teaching-section {
  width: 100% !important;
  max-width: 1120px !important;
}

.teaching-section .list__item,
.teaching-section .custom-archive-item {
  clear: both !important;
  width: 100% !important;
  max-width: 1120px !important;
  margin-bottom: 18px !important;
}

.teaching-section .archive__item,
.teaching-section .custom-archive-article {
  width: 100% !important;
  max-width: 1120px !important;
  float: none !important;
  margin-left: 0 !important;
  margin-right: 0 !important;
  padding-bottom: 14px;
  border-bottom: 1px solid #eeeeee;
}

.teaching-section .archive__item-title {
  white-space: normal !important;
  max-width: 1050px !important;
  margin-top: 0;
  margin-bottom: 5px;
  font-size: 1.02em;
}

.teaching-meta {
  width: 100% !important;
  max-width: 1050px !important;
  white-space: normal !important;
  line-height: 1.45;
  margin-top: 4px;
  margin-bottom: 8px;
}

/* Mobile */
@media screen and (max-width: 900px) {
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

  .publication-text,
  .publication-abstract,
  .publication-abstract p,
  .publication-links,
  .research-section .archive__item-excerpt,
  .research-section .archive__item-excerpt p {
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
