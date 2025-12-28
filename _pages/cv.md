---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download CV
======
You can download my CV here: [Download CV (PDF)]({{ base_path }}/files/MertGencturkCV.pdf)

Education
======
* M.S. in Computer Science, Bilkent University, 2025 - Present
* B.S. in Computer Science, Bilkent University, 2020 - 2025
  * CGPA: 3.7, High Honor Student
  * Ranking: 20th in Department

Work experience
======
* 2025 - Present: Graduate Research Assistant
  * Bilkent University - Cicek Lab
  * Developing deep learning models for copy number variant (CNV) and structural variant (SV) detection from whole exome sequencing data
  * Advisor: Dr. Ercument Cicek

* March 2024 - August 2025: Algorithm Engineer (Part-time)
  * Getir, Istanbul
  * Worked on scheduled delivery services, optimizing courier assignment and delivery estimations
  * Implemented VRP solver with dynamic clustering on OR Tools

* July 2024 - February 2025: Undergraduate Research Assistant
  * Bilkent University - Generative Deep Learning Research Lab
  * Worked on video style transfer with temporal consistency using diffusion models

* September 2023 - 2025: Undergraduate Research Assistant
  * Bilkent University - Applied Security and Privacy Lab
  * Research on privacy-preserving federated learning for healthcare applications

* June 2022 - March 2024: Fullstack Engineer (Part-time)
  * Monad Software and Consultancy
  * Implemented 60+ features in hospital administration software

Skills
======
* Areas: Deep Learning, Machine Learning, Backend Development, Fullstack Development, Bioinformatics, Optimization
* Technologies: Python, PyTorch, Java, Springboot, Django, FastAPI, NodeJS, SQL, Docker, AWS, GCP

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
