---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Education

**Tsinghua University — Ph.D. in Statistics**<br>
Sep. 2022–present · Department of Mathematical Sciences

- GPA: **3.94/4.00**; rank: **4/115**.
- First-Class Comprehensive Scholarship (2025); Second-Class Comprehensive Scholarship (2023).

**Tsinghua University — B.S. in Mathematics and Applied Mathematics**<br>
Sep. 2018–Jul. 2022

- GPA: **3.77/4.00**; rank: **16/116**.
- Tsinghua Xuetang Talent Program Scholarship; Outstanding Graduate of Tsinghua University.

## Research

My research focuses on the mathematical foundations of diffusion models: accelerated sampling, convergence analysis, and score estimation. I also work on diffusion LLM training and inference, speculative decoding, and multimodal generation and inference acceleration.

**City University of Hong Kong — Research Assistant**<br>
Sep. 2025–Feb. 2026 · Department of Data Science

**City University of Hong Kong — Visiting Ph.D. Student**<br>
Jan.–Jun. 2025

- Supported by Tsinghua University's doctoral short-term overseas visiting fund, awarded in 2024.

## Industry Experience

**Tencent — Algorithm Development Intern, Qingyun Program**<br>
Jul. 2026–present · Tencent Maps, CSIG

- Reconstruct globally consistent, continuously updated vector maps from vehicle camera images. Designed an EM-style vector mapping method and parallelized node updates, achieving a 2× speedup. Used Qwen-VL to assist event filtering and proposal construction; multi-event windows provided a further 2× speedup.
- Post-train multimodal understanding and image editing models for road events and map generation. Work includes end-to-end stylization of construction and accident images, checking lane-level vector maps against drawing rules, and generating clear map drawings with vector-constrained rendering.

**JD Technology / JD Cloud — Algorithm Development Intern**<br>
Feb.–Jul. 2026 · AI Infrastructure R&D

- Optimized speculative decoding with DFlash by increasing draft denoising steps and aligning the draft model's M2T and T2T capabilities during training. Increased accepted draft length from **6.4 to 8.3**. Parallel batching on the draft and verification sides improved throughput by **10%** at higher concurrency. Also explored FDFO-inspired decoding acceleration for Qwen3 models.
- Developed sequential Monte Carlo methods for speculative decoding. Added a speculative correction mechanism before particle resampling to improve throughput and accuracy with few particles, large block sizes, and weak draft models.
- Reproduced TaylorSeer on FLUX and designed nonuniform finite-difference feature prediction, using online local error estimates to select prediction intervals and orders. Explored layer- and token-level feature prediction to improve generation quality.

## Publications

### Conference Papers

{% assign conference_papers = site.publications | where: "category", "conferences" | sort: "publication_year" | reverse %}
{% for paper in conference_papers %}
- **[{{ paper.title }}]({{ paper.url | relative_url }})** — {{ paper.venue }}, {{ paper.publication_year }}. {{ paper.author_note }}.
{% endfor %}

### Manuscripts under Review

{% assign manuscripts = site.publications | where: "category", "manuscripts" %}
{% for paper in manuscripts %}
- **[{{ paper.title }}]({{ paper.url | relative_url }})** — {{ paper.publication_status }} {{ paper.venue }}. {{ paper.author_note }}.
{% endfor %}

## Selected Project

**Llama-3 Fine-Tuning for Long-Text Detection**

- Fine-tuned Llama-3 with QLoRA, staged masking, and a weighted loss. Post-training reduced the formatting error rate to **0.1%**.
- Deployed the model with SGLang and compressed prompts on the CPU with LLMLingua v2, achieving a speed improvement of **over 50%**.

## Competition Awards

- Honorable Mention in Probability and Statistics, S.-T. Yau College Student Mathematics Contests.
- First Prize, National College Student Mathematics Competition.
- Silver Medal, Chinese Mathematical Olympiad (CMO).

## Contact

[{{ site.author.email }}](mailto:{{ site.author.email }}) · [Google Scholar]({{ site.author.googlescholar }}) · [GitHub](https://github.com/{{ site.author.github }})
