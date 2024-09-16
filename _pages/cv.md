---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download a PDF copy of my CV [here](https://jdz357.github.io/files/paper1.pdf).

Education
======
**The University of Texas at Austin**
* Ph.D., Computational Science, Engineering, and Mathematics, Supervisors: [Dr. Leszek Demkowicz](https://users.oden.utexas.edu/~leszek/) and [Dr. George Biros](https://oden.utexas.edu/people/directory/George-Biros/). (Expected 2026)
* M.S., Computational Science, Engineering, and Mathematics, 2023
* B.S., Aerospace Engineering with Highest Honors, 2021
  * Certificate in Computational Science and Engineering

Skills
======
* Programming Languages: Proficient in Fortran. Python, MATLAB, C++
* Software Packages: NumPy, SciPy, Pandas, Git, LaTeX, Linux, Mathematica, ABAQUS, SolidWorks

Experience
======

* **Graduate Research Assistant** at the Oden Institute
  * Exploring new variational formulations for nonlinear elasticity problems including those using the Discontinuous Petrov-Galerkin (DPG) method to deliver optimal convergence rates with adaptive mesh refinement. (**Fortran**)

* **Quant Analytics Intern** at JP Morgan Chase & Co., Model Risk, Governance, and Review
  * Implemented a _k_-means model in **Athena** to cluster ZIP codes by land share and RVB data to evaluate CRE MFL market strength. (**Python**)
  * Identified several technical and methodological flaws in the initial classifier, impacting up to ~10% of the entire CRE portfolio. 
  * Conducted in-depth independent research on clustering algorithms and evaluation metrics.
  * Proposed a novel Voronoi cell extension to the classifier, generalizing clusterings to use time series data and improving comparability across years.
  * Back-tested classifier using downstream default rate (PD) and loss (LGD) models using custom performance metrics. 
  * Communicated analysis results to business leaders and management through a series of presentations and detailed model documents. 

* **Member of Technical Staff** at Sandia National Laboratories 
  * Analyzed the influence of structural dynamics on electrical chatter in a pin-receptacle using high- and low-fidelity models in SIERRA.
  * Developed a Craig-Bampton reduced-order model for the pin-receptacle, reducing compute time by 30X on Sandia’s high-performance computers.

  

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
Service and leadership
======
* CSEM Student Forum Organizer, 
