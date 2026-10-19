---
layout: about
title: Home
permalink: /
profile_page: true
description: Levi Silvers, Research Scientist in the Department of Atmospheric Science at Colorado State University.
subtitle: Research Scientist · Department of Atmospheric Science · Colorado State University
profile:
  image: prof_pic.jpg
  image_circular: false
---

<div class="profile-home">
  <section class="profile-home__hero" aria-labelledby="profile-name">
    <div class="profile-home__intro">
      <p class="profile-home__eyebrow">Research Scientist</p>
      <h1 id="profile-name">Levi Silvers</h1>
      <p class="profile-home__lead">
        Department of Atmospheric Science, Colorado State University
      </p>
      <p>
        My current research interests include the influence of the large-scale environment on tropical cyclones and the how various modes of climate 
        variability such as ENSO and the Madden-Julien Oscillation influence the characteristics of tropical cyclones.  Additionally, I am involved in a different research project that is examining
        the interactions between the northern and southern hemispheres to balance the hemispheric water and energy budgets.   Becuase I have had the pleasure of working 
        at multiple laboratories and universities my past reasearch has covered a wide range of topics, most of which are related to the influence of clouds on the Earth's 
        climate.  This includes the study of climate change, cloud-feedbacks, idealized modeling in the form of radiative-convective equilibrium, and the development of 
        physics-based numerical models of the Earth system.  
      </p>
      <div class="profile-home__actions">
        <a class="profile-home__button" href="mailto:{{ site.email }}">Get in touch</a>
        <a class="profile-home__text-link" href="https://tinyurl.com/ScholarSilvers">Google Scholar <span aria-hidden="true">→</span></a>
        <a class="profile-home__text-link" href="{{ '/assets/pdf/Levi_Glenn_Silvers_CV.pdf' | relative_url }}" download>Download CV (PDF) <span aria-hidden="true">↓</span></a>
      </div>
    </div>

    <aside class="profile-home__contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact information</h2>
      <dl>
        <dt>Email</dt>
        <dd><a href="mailto:{{ site.email }}">{{ site.email }}</a></dd>
        <dt>Department</dt>
        <dd>Atmospheric Science, Colorado State University</dd>
        <dt>Address</dt>
        <dd>Fort Collins, CO 80523</dd>
        <dt>ORCID</dt>
        <dd><a href="https://orcid.org/0000-0003-4304-2545">0000-0003-4304-2545</a></dd>
      </dl>
      <img
        class="profile-home__portrait"
        src="{{ '/assets/img/prof_pic.jpg' | relative_url }}"
        alt="Portrait of Levi Silvers"
        loading="eager"
      >
    </aside>
  </section>

  <section class="profile-home__section" aria-labelledby="research-heading">
    <div class="profile-home__section-heading">
      <p class="profile-home__eyebrow">Research interests</p>
      <h2 id="research-heading">Research</h2>
    </div>
    <ul class="profile-home__interest-list">
      <li>Tropical cyclones</li>
      <li>Climate change and internal variability</li>
      <li>The role of clouds and water vapor</li>
      <li>Cloud feedback mechanisms</li>
      <li>Large-scale fluid dynamics</li>
      <li>Development of atmospheric numerical models</li>
    </ul>
  </section>

  <section class="profile-home__section" aria-labelledby="appointments-heading">
    <div class="profile-home__section-heading">
      <p class="profile-home__eyebrow">Career</p>
      <h2 id="appointments-heading">Academic appointments</h2>
    </div>
    <ol class="profile-home__timeline">
      <li><time>2024–Present</time><div><h3>Research Scientist</h3><p>Department of Atmospheric Science, Colorado State University, Fort Collins, CO</p></div></li>
      <li><time>2019–2024</time><div><h3>Research Scientist</h3><p>School of Marine and Atmospheric Science, Stony Brook University, Stony Brook, NY</p></div></li>
      <li><time>2015–2019</time><div><h3>Associate Research Scholar</h3><p>Princeton University / Geophysical Fluid Dynamics Laboratory, Princeton, NJ</p></div></li>
      <li><time>2012–2015</time><div><h3>Post-Doctoral Scientist</h3><p>The Max Planck Institute for Meteorology, Hamburg, Germany</p></div></li>
    </ol>
  </section>

  <section class="profile-home__section" aria-labelledby="education-heading">
    <div class="profile-home__section-heading">
      <p class="profile-home__eyebrow">Education</p>
      <h2 id="education-heading">Education</h2>
    </div>
    <ul class="profile-home__education-list">
      <li><time>2011</time><span>Ph.D., Atmospheric Science, Colorado State University</span></li>
      <li><time>2007</time><span>M.S., Atmospheric Science, Colorado State University</span></li>
      <li><time>2004</time><span>B.S., Physics, Gordon College; minor in Mathematics</span></li>
    </ul>
  </section>

  <section class="profile-home__section" aria-labelledby="publications-heading">
    <div class="profile-home__section-heading">
      <p class="profile-home__eyebrow">Peer-reviewed work</p>
      <h2 id="publications-heading">Selected publications</h2>
    </div>
    <div class="profile-home__publication-list">
      {% bibliography --group_by none --query @*[selected=true]* %}
    </div>
    <p class="profile-home__publication-more">
      <a class="profile-home__text-link" href="{{ '/publications/' | relative_url }}">View publications page <span aria-hidden="true">→</span></a>
    </p>
  </section>
</div>
