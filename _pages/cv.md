---
layout: archive
title: "Short CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download full resume: [English version](https://axelledrouard.github.io/files/cv_english.pdf) \| [French version](https://axelledrouard.github.io/files/cv_french.pdf)

Born in Saint-Nazaire (France) on October the 25th 1998.

Work experience
======
* November 2025 - Today: Post-doctoral researcher at Centre Borell, ENS Paris-Saclay / CEA

Education
======
* 2022 - 2025: Ph.D in Applied Mathematics, LiHPC, CEA, Paris-Saclay University -- **Kinetic methods for hyperbolic problems on ustructured meshes**
* 2020 - 2022: Master's degree in Applied Mathematics, Nantes University
* 2017 - 2020: Bachelor's degree in Mathematics, Nantes University

Internship
======
* April 2022 - September 2022: **Study of a finite volume scheme with nodal fluxes for parabolic problems on unstructured meshes**, CEA. Supervisors:

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

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
