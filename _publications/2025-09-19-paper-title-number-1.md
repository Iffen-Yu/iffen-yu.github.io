---
title: "Advancing Wasserstein Convergence Analysis of Score-Based Models: Insights from Discretization andSecond-Order Acceleration"
collection: publications
category: conferences
permalink: /publication/NeurIPS_Advancing_Wasserstein_Convergence_Analysis_of_Score_Based_Models__Insights_from_Discretization_and_Second_Order_Acceleration
excerpt: 'This paper is about an Hessian-based accelerated sampler of diffusion model.'
date: 2025-09-19
venue: 'Advances in Neural Information Processing Systems (NeurIPS)'
slidesurl: 'https://iffen-yu.github.io/files/slide.pdf'
paperurl: 'https://iffen-yu.github.io/files/NeurIPS_Advancing_Wasserstein_Convergence_Analysis_of_Score_Based_Models__Insights_from_Discretization_and_Second_Order_Acceleration.pdf'
bibtexurl: 'https://iffen-yu.github.io/files/bibtex1.bib'
---
Score-based diffusion models have emerged as powerful tools in generative modeling, yet their theoretical foundations remain underexplored. In this work, we focuson the Wasserstein convergence analysis of score-based diffusion models. Specifically, we investigate the impact of various discretization schemes, including Euler discretization, exponential integrators, and midpoint randomization methods. Our analysis provides the first quantitative comparison of these discrete approximations, emphasizing their influence on convergence behavior.  Furthermore, we explore scenarios where Hessian information is available and propose an accelerated sampler based on the local linearization method.  We establish the first Wassersteinconvergence analysis for such a Hessian-based method, showing that it achieves an improved convergence rate of order $\tilde{O}(\sqrt{d}/\varepsilon)$, which significantly outperforms the standard rate $\tilde{O}(d/\varepsilon^2)$ of vanilla diffusion models. Numerical experiments on synthetic data and the MNIST dataset validate our theoretical insights.
