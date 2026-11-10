---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[download CV（PDF）](/files/Academic_CV_Chang_Xu.pdf)

Education
======
* Ph.D in Climate Science, The University of New South Wales, 2023-present
* M.S. in Hydraulic Engineering, Sun Yat-sen University, 2019-2022
* B.S. in Hydrology and Water Resources Engineering, University of Jinan, 2015-2019

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Service and leadership
======
* Visiting Researcher, Max Planck Institute for Meteorology (MPI-M), Germany (2026)
* Founder and Coordinator, Oceanic and Atmospheric Systems Integrated Society (OASIS), UNSW
* Presenter, AMOS 2026 and MPI-M Joint Seminar
* Centre Student, ARC Centre of Excellence for 21st Century Weather, Melbourne (2024 - present)
* Contributor to ARC Centres of Excellence (CLEX & 21st Century Weather) research workshops
* Project Leader in interdisciplinary hydrology–climate research initiatives

Interests
======
Moisture-Convection Coupling, Climate Dynamics, Equatorial Wave Theory, Scientific Computing, Data Visualization, Science Communication


<h2>Technical Expertise</h2>

<div class="cv-skills-grid">
  <div>
    <strong>Programming & Computing</strong>
    <p>Python · Fortran · MATLAB · Linux · HPC</p>
  </div>

  <div>
    <strong>Atmospheric Modelling</strong>
    <p>WRF · ICON · UM · ERA5 Analysis</p>
  </div>

  <div>
    <strong>Data Analysis</strong>
    <p>Spectral & Wavelet Analysis · EOF · Statistical Methods</p>
  </div>

  <div>
    <strong>Languages</strong>
    <p>Chinese (Native) · English (IELTS 7.0) · German (Reading)</p>
  </div>
</div>

<style>
.cv-skills-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 20px 35px;
  margin-top: 22px;
}

.cv-skills-grid strong {
  color: #800020;
  font-size: 15px;
}

.cv-skills-grid p {
  margin: 8px 0 0;
  font-size: 14px;
  line-height: 1.65;
}

@media (max-width: 600px) {
  .cv-skills-grid {
    grid-template-columns: 1fr;
  }
}
</style>
