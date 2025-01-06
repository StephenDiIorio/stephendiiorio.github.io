---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Physics and Computer Science, Union College, Schenectady, NY, 2015
* Ph.D in Physics and Scientific Computing, University of Michigan, Ann Arbor, MI, 2024

Thesis
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category == 'thesis' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category != 'thesis' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Skills
======
* Proficient in C++, Python, MATLAB, and Fortran
* Experience with OpenMP, MPI, and CUDA

Courses and Certifications
==========================
* High Energy-Density Science Summer School, UCSD, July 29-August 10 2019.
* CERN Accelerator School on high gradient wakefield accelerators, March 11-22 2019.

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
