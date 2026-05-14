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