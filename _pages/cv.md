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
* **B.A. in Big Data Communication**, Nanjing University, 2024–Present (Expected 2027)
  * **GPA: 4.4 / 5.0** — Rank 2 in major
  * Big Data Communication Experimental Class, School of Journalism and Communication
  * **Relevant Coursework:** Machine Learning, Data Science & Analytics, Probability & Statistics, Data Structures & Algorithms, AI Programming, Database Systems, Discrete Mathematics, Introduction to AI

Research Experience
======
* **RoutingToolBox — LLM Routing Benchmark** (2025–Present)
  * Contributed to building a comprehensive LLM routing benchmark pipeline
  * Processed three datasets: Mixinstruct, Routereval (public), and MMRbench (unreleased multimodal)
  * Developed algorithm interfaces and general-purpose utility functions
  * Independently built **RouteJudge**, a full-stack application for routing decision evaluation
  * Second-author paper, **"RouterJudge: Preference-Based Evaluation of LLM Routers under Pluralistic User Preferences"** — accepted at **ICML Workshop**
  * Second-author paper, **"Priors in LLM Routing: From Initialization to Regularization"** — under review at **TMLR**
  * Second-author paper, **"From Sampled Outcomes to Capability Distributions: Rethinking Supervision for LLM Routing"** — under review at **EMNLP**

* **LLM Population Simulation Project** (Spring 2026)
  * Investigating alignment between LLM-simulated policy attitudes and real-world survey data
  * Using Nemotron-Personas-France dataset (6M synthetic personas)
  * Building retrieval-augmented LLM pipelines for demographic-conditioned response generation

Competitions
======
* **Kaggle NCAA March Madness Prediction** — Top 40%+
  * Predictive modeling, feature engineering, competition pipeline

Projects
======
* **Digital Communication Knowledge Graph** (Coursework, 2026)
  * Built an Obsidian-based course knowledge graph covering 14 areas of digital communication
  * Created 41 SVG structure diagrams + 41 Mermaid relationship maps
  * Human-AI collaborative notes with transparent attribution
* **LLM-Assistant** — AI assistant application with MCP protocol integration (open source)
* **Douban Movie Crawler** — Automated web scraping tool for movie information
* **RouteJudge** — Full-stack web application for LLM routing evaluation

Technical Skills
======
* **Programming Languages:** Python (primary), SQL, C++, JavaScript (frontend basics)
* **Data Science:** pandas, NumPy, scikit-learn, statistical modeling, dataset processing
* **AI/ML:** LLM inference, model routing, API integration, benchmark construction
* **Tools:** Git/GitHub, VS Code, Jupyter, Obsidian, MCP toolchain
* **Communication:** WeChat official account operation, video editing, data visualization

Honors & Awards
======
* **Excellent Volunteer**, Nanyang Dream Plan (南星梦想计划)
* **Excellent Member**, Xiao Lan Jing (小蓝鲸)
* **University-Level Project Approval** (校级立项), Summer Teaching Volunteer Program

Field & Leadership Experience
======
* **Financial Manager**, Summer Teaching Volunteer Program, Shangluo, Shaanxi
  * Managed full-team budget, expense control, and financial reconciliation for a 12-person interdisciplinary team
  * Achieved zero-error accounting under resource-constrained conditions
  * Built effective communication with local communities in unfamiliar environments
  * Project received university-level project approval (校级立项)

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

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
