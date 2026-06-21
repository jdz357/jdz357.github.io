---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my résumé (PDF)](/files/Jonathan_Zhang_Resume.pdf)

Education
======

**The University of Texas at Austin**, Austin, TX

* **Ph.D., Computational Science, Engineering, and Mathematics**, in progress
  * Advisors: Leszek Demkowicz and George Biros
  * Research interests: finite elements, numerical methods for partial differential equations, high-performance computing, and nonlinear problems
* **M.S., Computational Science, Engineering, and Mathematics**, August 2021–May 2023
* **B.S., Aerospace Engineering**, August 2017–December 2020

Technical skills
======

* **Programming:** Fortran, Python, MATLAB, C++
* **Scientific computing and analysis:** NumPy, SciPy, Pandas, JAX, Mathematica
* **Engineering and visualization:** SolidWorks, ABAQUS, ParaView
* **Tools:** Git, LaTeX, Microsoft Office

Work experience
======

### JPMorganChase — New York, NY

**Quantitative Research Summer Associate, Securitized Products Group**<br>
2026–Present

**Quantitative Analytics Summer Associate, Model Risk, Governance, and Review**<br>
June 2025–August 2025

* Analyzed model assumptions and nonlinear data treatment in a commercial real estate prepayment logistic regression model.
* Investigated joint optimization methods for nonlinear feature transformations using augmented loss functions.
* Developed a neural-network transformation of loan features that outperformed the baseline linear transformation by more than 100 AIC points while preserving explainability.
* Presented results to business leaders and management through presentations and detailed model documentation.

**Quantitative Analytics Summer Associate, Model Risk, Governance, and Review**<br>
June 2024–August 2024

* Implemented a k-means model in Athena to cluster ZIP codes by land share and RVB data for evaluating commercial real estate multifamily market strength.
* Identified technical and methodological flaws in the initial classifier affecting approximately 10% of the commercial real estate portfolio.
* Back-tested the classifier through downstream probability-of-default and loss-given-default models using custom performance metrics.

### Oden Institute for Computational Engineering and Sciences — Austin, TX

**Graduate Research Assistant, Electromagnetics and Acoustics Group**<br>
August 2022–Present

* Explore neural-network applications based on variationally stable problem formulations in biomechanics.
* Study variational formulations for nonlinear elasticity, including the discontinuous Petrov-Galerkin method, to deliver optimal convergence rates with adaptive mesh refinement.

### Sandia National Laboratories — Remote

**Member of Technical Staff, Component Science and Mechanics**<br>
January 2021–August 2021

* Analyzed the influence of structural dynamics on electrical chatter in a pin-and-receptacle assembly using high- and low-fidelity SIERRA models.
* Developed a Craig–Bampton reduced-order model that reduced compute time by 30× on Sandia high-performance computing systems.

### Oden Institute for Computational Engineering and Sciences — Austin, TX

**Moncrief Research Intern**<br>
March 2019–August 2019

* Simulated thin-film interfacial properties in a double-cantilever beam under tension with varying bond strengths using ABAQUS.
* Compared finite-element results with experimental data to determine the significance of imperfect bonding.
* Formulated a polynomial model for imperfect bonding conditions that reproduced the ABAQUS results within 0.2% error.

Publications
======
  {% assign publications_by_date = site.publications | sort: "date" | reverse %}
  <ul>{% for post in publications_by_date %}
    {% unless post.status %}
      {% include archive-single-cv.html %}
    {% endunless %}
  {% endfor %}
  {% for post in publications_by_date %}
    {% if post.status == "Submitted" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
  {% for post in publications_by_date %}
    {% if post.status and post.status != "Submitted" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
