---
title: "Can LLMs Simulate Public Opinion? Initial Findings"
date: 2026-06-10
categories:
  - research
  - computational-social-science
tags:
  - LLM
  - survey
  - simulation
---

In my current research project, I've been exploring whether large language models can accurately simulate how different demographic groups respond to policy questions. Using the [Nemotron-Personas-France](https://huggingface.co/datasets/Pleias/Nemotron-Personas-France) dataset — which contains 6 million synthetic French adult personas based on the 2025 French census — we're comparing LLM-generated responses against real public opinion survey data.

## The Core Question

The fundamental question is: **How well do LLM-simulated policy attitudes align with actual survey data?** And critically, *which* types of questions show better alignment, and how much does this vary across different models?

## Approach

Our technical pipeline involves:

1. **Retrieval** — matching survey questions to relevant demographic-conditioned prompts
2. **LLM Simulation** — generating persona-conditional responses at scale
3. **Statistical Validation** — comparing simulated distributions against ground-truth survey results

## Early Observations

While we're still in the early stages, a few patterns are emerging:

- LLMs tend to capture broad demographic trends (e.g., age-based opinion gaps) reasonably well
- But they often **underestimate variance** — the simulated responses are more "centrist" than real survey data
- Different models (and model sizes) show meaningfully different levels of alignment

## Why This Matters

If LLMs can reliably simulate population attitudes, this could complement traditional survey methods — especially for rapid pre-testing of questionnaires or exploring hypothetical scenarios. But if the alignment is poor or systematically biased, using LLMs as "synthetic respondents" could lead to misleading conclusions.

I'll share more detailed results as the project progresses. Stay tuned!

---

*This project is part of my coursework in the Big Data Communication program at Nanjing University.*
