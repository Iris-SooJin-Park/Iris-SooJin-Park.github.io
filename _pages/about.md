```html
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
  max-width: 1400px !important;
  margin-left: auto !important;
  margin-right: auto !important;
}

/* Smooth scrolling for navigation links */
html {
  scroll-behavior: smooth;
}

/* Layout */
.home-intro {
  display: grid;
  grid-template-columns: 320px minmax(0, 1fr);
  gap: 70px;
  align-items: start;
}

/* Image */
.home-photo img {
  width: 100%;
  max-width: 300px;
  height: auto;
  display: block;
}

/* Text */
.home-about {
  padding-top: 20px;
  max-width: 750px;
}

.home-about h2 {
  margin-top: 0;
}

/* Contact links */
.home-links {
  margin-top: 22px;
  font-size: 0.95em;
  display: flex;
  gap: 24px;
  align-items: center;
  flex-wrap: wrap;
}

.home-links p {
  margin: 0;
}

.home-links i {
  margin-right: 6px;
  color: #555;
}

/* Section styling */
.section-divider {
  margin: 60px 0 35px 0;
  border: none;
  border-top: 1px solid #e5e5e5;
}

.home-section {
  max-width: 900px;
  margin: 0 auto 60px auto;
  padding-top: 25px;
}

.home-section h2 {
  margin-bottom: 18px;
  border-bottom: 1px solid #e5e5e5;
  padding-bottom: 8px;
}

.home-section h3 {
  margin-top: 24px;
  margin-bottom: 8px;
}

.home-section p {
  margin-bottom: 16px;
}

/* Mobile */
@media screen and (max-width: 768px) {
  .home-intro {
    display: block;
  }

  .home-photo {
    margin-bottom: 24px;
  }

  .home-about {
    padding-top: 0;
  }

  .home-section {
    margin-bottom: 45px;
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


<section id="cv" class="home-section">
  <h2>CV</h2>

  <p>
    You can download my CV 
    <a href="/files/Iris_SooJin_Park_CV(recent).pdf" target="_blank">here</a>.
  </p>
</section>


<section id="research" class="home-section">
  <h2>Research</h2>

  <h3>Older Americans and Life Insurance</h3>
  <p>
    This project studies life insurance ownership among older Americans and examines
    how surviving spouses use life insurance payouts.
  </p>

  <h3>When the Choice Should Be Clear: Visual Decision Aids and Health Insurance Selection</h3>
  <p>
    This project studies how visual decision aids affect health insurance choices.
  </p>

  <h3>Evaluating the Effects of Moderate Deductible Increase on Health Care Utilization</h3>
  <p>
    This project examines behavioral responses to a moderate deductible increase in health insurance.
  </p>
</section>


<section id="teaching" class="home-section">
  <h2>Teaching</h2>

  <h3>Teaching Assistant</h3>
  <p>
    Business Analytics II, Wisconsin School of Business, University of Wisconsin-Madison.
  </p>

  <h3>Teaching Interests</h3>
  <p>
    Risk management and insurance, business analytics, health insurance, and behavioral decision-making.
  </p>
</section>
```
