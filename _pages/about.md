---
permalink: /
title: "Haoran Hu"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="home-shell">
  <section class="home-hero" aria-labelledby="home-hero-title">
    <div class="home-hero__copy">
      <p class="home-kicker">Nanjing University / Big Data Communication</p>
      <h1 id="home-hero-title">I build tools and evaluations for reusing large language models.</h1>
      <p class="home-hero__lead">I am Haoran Hu, an undergraduate at Nanjing University. My recent work focuses on model routing, budget-aware inference, and evaluation systems that make model selection more reliable.</p>
      <div class="home-hero__actions" aria-label="Primary links">
        <a class="home-button home-button--primary" href="/portfolio/">View projects</a>
        <a class="home-button" href="/publications/">Publications</a>
        <a class="home-button" href="#contact">Contact</a>
      </div>
    </div>

    <aside class="home-profile-card" aria-label="Profile summary">
      <img src="/images/profile.png" alt="Haoran Hu">
      <div>
        <h2>Haoran Hu</h2>
        <p>Undergraduate researcher working on model reuse, routing, and evaluation.</p>
      </div>
      <dl>
        <div><dt>GPA</dt><dd>4.4 / 5.0, rank 2</dd></div>
        <div><dt>Location</dt><dd>Nanjing, China</dd></div>
        <div><dt>Email</dt><dd>huhr@smail.nju.edu.cn</dd></div>
      </dl>
    </aside>
  </section>

  <section class="home-metrics" aria-label="Highlights">
    <article>
      <strong>FCS 2026</strong>
      <span>ORBIT accepted</span>
    </article>
    <article>
      <strong>EMNLP 2026</strong>
      <span>Routing supervision paper accepted</span>
    </article>
    <article>
      <strong>ICMLW 2026</strong>
      <span>RouteJudge accepted</span>
    </article>
  </section>

  <section class="home-section home-section--intro">
    <p class="home-kicker">Research Area</p>
    <div class="home-section__split">
      <h2>Model reuse, with recent focus on model routing.</h2>
      <p>My recent work studies how existing models can be selected, evaluated, and reused under practical constraints such as quality, cost, risk, and user preference.</p>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section__header">
      <p class="home-kicker">Research Interests</p>
      <h2>Model reuse and routing</h2>
    </div>
    <div class="home-interest-grid" aria-label="Research interests">
      <article>
        <span>01</span>
        <h3>Model Reuse</h3>
        <p>Reusing and adapting existing models under changing tasks, budgets, and deployment constraints.</p>
      </article>
      <article>
        <span>02</span>
        <h3>Model Routing</h3>
        <p>Selecting suitable models for different queries with attention to quality, cost, and preference.</p>
      </article>
      <article>
        <span>03</span>
        <h3>Evaluation</h3>
        <p>Designing benchmarks, protocols, and tools for reproducible comparison of intelligent systems.</p>
      </article>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section__header">
      <p class="home-kicker">Selected Work</p>
      <h2>Selected publications</h2>
    </div>
    <div class="home-publication-list">
      <article class="home-publication-card">
        <img src="/images/publications/dars-framework.png" alt="">
        <div>
          <span>EMNLP 2026</span>
          <h3><a href="https://arxiv.org/abs/2606.06924">From Sampled Outcomes to Capability Distributions</a></h3>
          <p class="home-paper-authors">Guannan Lai, <strong>Haoran Hu</strong>, Long Chen, Zhenguo Li, Han-Jia Ye</p>
          <p>Models routing supervision as capability distributions for more robust model selection.</p>
          <p class="home-paper-links"><a href="https://arxiv.org/pdf/2606.06924">Paper</a><a href="https://github.com/AIGNLAI/DARS">Code</a><a href="https://huggingface.co/datasets/AIGNLAI/DARS">Dataset</a></p>
        </div>
      </article>
      <article class="home-publication-card">
        <img src="/images/publications/orbit.jpg" alt="">
        <div>
          <span>Frontiers of Computer Science</span>
          <h3><a href="https://www.lamda.nju.edu.cn/laign/file/FCS-261310-final.pdf">ORBIT: An Optimal Routing and Budgeted Inference Toolbox</a></h3>
          <p class="home-paper-authors">Guannan Lai, <strong>Haoran Hu</strong>, Hao-Xuan Ma, Han-Jia Ye</p>
          <p>A toolbox for benchmarking, training, and evaluating budget-aware inference routers.</p>
          <p class="home-paper-links"><a href="https://www.lamda.nju.edu.cn/laign/file/FCS-261310-final.pdf">Paper</a><a href="https://github.com/LAMDA-Model-Reuse/ORBIT">Code</a></p>
        </div>
      </article>
      <article class="home-publication-card">
        <img src="/images/publications/routejudge-framework.png" alt="">
        <div>
          <span>ICML 2026 Workshop</span>
          <h3><a href="https://openreview.net/forum?id=qx8X5hC9Kq">RouteJudge: Preference-Based Evaluation of LLM Routers</a></h3>
          <p class="home-paper-authors">Guannan Lai, <strong>Haoran Hu</strong>, Han-Jia Ye</p>
          <p>Evaluates router decisions under pluralistic user preferences and budget constraints.</p>
          <p class="home-paper-links"><a href="https://routejudge.cn">Project Website</a><a href="https://openreview.net/pdf?id=qx8X5hC9Kq">Paper</a><a href="https://openreview.net/forum?id=qx8X5hC9Kq">OpenReview</a></p>
        </div>
      </article>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section__header">
      <p class="home-kicker">Project Portfolio</p>
      <h2>Research systems and data work</h2>
    </div>
    <div class="home-projects">
      <a href="/portfolio/routejudge/">
        <span>Router Evaluation</span>
        <strong>RouteJudge</strong>
        <p>Preference-based evaluation interface for comparing routing decisions under user constraints.</p>
      </a>
      <a href="https://github.com/LAMDA-Model-Reuse/ORBIT">
        <span>Routing Toolbox</span>
        <strong>ORBIT</strong>
        <p>Reusable benchmark and evaluation toolkit for budget-aware model routing research.</p>
      </a>
      <a href="https://github.com/AIGNLAI/DARS">
        <span>Supervision Data</span>
        <strong>DARS</strong>
        <p>Code and dataset pipeline for capability-distribution supervision in LLM routing.</p>
      </a>
      <a href="/portfolio/llm-assistant/">
        <span>AI Application</span>
        <strong>LLM Assistant</strong>
        <p>Assistant experiments around tool use, MCP integration, and applied LLM workflows.</p>
      </a>
    </div>
  </section>

  <section class="home-section home-section--service">
    <div>
      <p class="home-kicker">Beyond Research</p>
      <h2>Teamwork and public-facing practice.</h2>
    </div>
    <div>
      <p>I served as financial manager for a 12-person interdisciplinary summer teaching volunteer team in Shangluo, Shaanxi, managing budget, expenses, and reconciliation with zero errors. I also work on WeChat official account operation and video editing, connecting technical execution with communication practice.</p>
      <ul>
        <li>Excellent Volunteer, Nanyang Dream Plan</li>
        <li>Excellent Member, Xiao Lan Jing</li>
        <li>University-level project approval for summer teaching service</li>
      </ul>
    </div>
  </section>

  <section class="home-contact" id="contact" aria-label="Contact">
    <p class="home-kicker">Contact</p>
    <h2>Open to collaboration, project conversations, and thoughtful technical work.</h2>
    <p class="home-contact__email">huhr@smail.nju.edu.cn</p>
    <div class="home-hero__actions">
      <a class="home-button" href="https://github.com/provided21">GitHub @provided21</a>
      <a class="home-button" href="/cv/">View CV</a>
    </div>
  </section>

  <p class="home-updated">Last updated: September 2026</p>
</section>
