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
* Ph.D in Mechanical Engineering, University of Kentucky, (Aug 2019- July 2025(expected))
* B.Tech. (B.S equivalent) in Mechanical Engineering, KIIT University, 2014-2018

Work experience
======
* August 2019 - Present: Graduate Research Assistant, University of Kentucky
  * My training is in scientific computing and over the years I have mastered scientific software development, where I develop large-scale (distributed computing) ray tracing software in C/C++. The major aim of the ray tracing is to understand light-matter interaction (through principles of electromagnetics/ Mie theory and geometric optics). The material over here refers to composite structures (carbon and silica based) which are primarily used in re-entry vehicles as thermal protection systems. The optical coefficients that are computed from the ray tracing solver, is input to a finite volume (FVM) based material response solver which essentially shows the in-depth radiative heating in materials.
  * In addition to ray tracing software, I have developed software to generate synthetic microstructures and reconstruct materials from X-ray computed tomography (XRCT) scans. HERMES (the microstructure reconstruction code) is a Python-based toolkit developed and deployed on cross-platform environments (Windows, Mac, and Linux). The code generates microstructures in STL and voxel formats apart from computing material properties. Principles of computational geometry, adaptive mesh refinement, and machine learning algorithms are implemented in the software to perform volumetric reconstruction and composite material segmentation.
  * Additionally, I mentor new PhD students, masters students and undergraduate on principles of scientific computing and problem solving approaches in research

* May 2024 - December 2024: Advanced Development Intern, KLA Corporation
  * Development of a novel system model for holographic spectroscopic ellipsometry using self-interfering rays for the FaST division.
  * The principles of image and signal processing along with Fourier transforms were integrated into the system model, as certain segment of the code required inverse analysis. 

  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
