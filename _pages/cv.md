---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: false
body_class: cv-page
redirect_from:
  - /resume
---

<div class="cv-intro">
  <p>An undergraduate researcher in the Big Data Communication Experimental Program at Nanjing University, working across model routing and computational communication.</p>
  <p class="home-paper-links"><a href="mailto:huhr@smail.nju.edu.cn">Email</a><a href="https://scholar.google.com/citations?user=btFg5GIAAAAJ&amp;hl=en">Google Scholar</a><a href="https://orcid.org/0009-0000-9570-0998">ORCID</a></p>
</div>

Education
======
* **B.A. in Big Data Communication**, Nanjing University, 2024–Present (Expected 2028)
  * Big Data Communication Experimental Program, School of Journalism and Communication
  * **GPA: 4.44 / 5.0** · **Rank: 2 / 16**

Research Experience
======
* **Model Routing and Evaluation**, 2026–Present
  * Research on supervision, preference-based evaluation, and budget-aware inference for LLM routing.
  * Contributed to ORBIT, DARS, and RouteJudge through benchmark construction, system development, and evaluation.

* **Computational Communication**, 2026–Present
  * LLM-based simulation of policy attitudes using large-scale synthetic personas.
  * Study of behavioral adoption in intelligent payment infrastructure.

Publications
======
  <ul>{% assign accepted_publications = site.publications | where: "status", "accepted" | sort: "publication_order" %}{% for post in accepted_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Preprints
======
  <ul>{% assign preprints = site.publications | where: "status", "preprint" | sort: "publication_order" %}{% for post in preprints %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected Practice
======
* **NJU Xiao Lanjing** — Content planning, photography, filming, editing, and post-production; Outstanding Member, 2025–2026.
* **Global Field Study · Singapore & Malaysia** — On-site visits, communication, and field research with the enterprise group.

Technical Skills
======
* **Programming:** Python, SQL, C++, JavaScript
* **Data & AI:** pandas, NumPy, scikit-learn, LLM inference, model routing, statistical modeling
* **Media:** Content planning, photography, filming, video editing, data visualization
