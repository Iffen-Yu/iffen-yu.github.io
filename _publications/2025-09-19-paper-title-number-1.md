---
title: "Advancing Wasserstein Convergence Analysis of Score-Based Models: Insights from Discretization andSecond-Order Acceleration"
collection: publications
category: conferences
permalink: /publication/NeurIPS_Advancing_Wasserstein_Convergence_Analysis_of_Score_Based_Models__Insights_from_Discretization_and_Second_Order_Acceleration
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-09-19
venue: 'Advances in Neural Information Processing Systems (NeurIPS), 2025.'
slidesurl: 'https://iffen-yu.github.io/files/slide.pdf'
paperurl: 'https://iffen-yu.github.io/files/NeurIPS_Advancing_Wasserstein_Convergence_Analysis_of_Score_Based_Models__Insights_from_Discretization_and_Second_Order_Acceleration.pdf'
bibtexurl: 'https://iffen-yu.github.io/files/bibtex1.bib'
---
Score-based diffusion models have emerged as powerful tools in generative model-ing, yet their theoretical foundations remain underexplored. In this work, we focuson the Wasserstein convergence analysis of score-based diffusion models. Specifi-cally, we investigate the impact of various discretization schemes, including Eulerdiscretization, exponential integrators, and midpoint randomization methods. Ouranalysis provides the first quantitative comparison of these discrete approximations,emphasizing their influence on convergence behavior.  Furthermore, we explorescenarios where Hessian information is available and propose an accelerated sam-pler based on the local linearization method.  We establish the first Wassersteinconvergence analysis for such a Hessian-based method, showing that it achievesan improved convergence rate of ordere O(√d/ε), which significantly outperformsthe standard ratee O(d/ε2)of vanilla diffusion models. Numerical experiments onsynthetic data and the MNIST dataset validate our theoretical insights.
