---
layout: single
title: "Research"
permalink: /research/
excerpt: "Research interests and current directions in optimization for machine learning."
author_profile: true
---

<p class="page-intro">I work at the intersection of optimization, machine learning, and distributed systems. My goal is to make large-scale training faster and more communication-efficient while retaining rigorous convergence guarantees.</p>

## Research directions

<div class="research-grid">
  <article class="research-card">
    <p class="eyebrow">Algorithms</p>
    <h3>Stochastic optimization</h3>
    <p>Variance reduction, randomized updates, non-Euclidean geometry, and convergence analysis for modern model training.</p>
  </article>
  <article class="research-card">
    <p class="eyebrow">Scale</p>
    <h3>Distributed & federated learning</h3>
    <p>Local training, sparse synchronization, communication compression, and methods that overlap communication with computation.</p>
  </article>
  <article class="research-card">
    <p class="eyebrow">Efficiency</p>
    <h3>Large-model training</h3>
    <p>Structure-aware optimizers, selective layer updates, model optimization, and techniques that connect theoretical efficiency to wall-clock gains.</p>
  </article>
  <article class="research-card">
    <p class="eyebrow">Foundations</p>
    <h3>Learning theory</h3>
    <p>Generative modeling, representation learning, generalization, and out-of-distribution behavior.</p>
  </article>
</div>

## Current themes

- **Communication-efficient training:** decreasing transferred information, reducing synchronization overhead, and making useful progress while messages are in flight.
- **Matrix-aware optimization:** exploiting the geometry of parameter matrices instead of treating every model as a single flat vector.
- **Adaptive update schedules:** understanding when updating fewer layers or decoupling stochastic estimators improves practical efficiency.
- **Federated second-order methods:** using curvature information and compression to approach second-order stationarity in nonconvex problems.

## Approach

I combine convergence theory, algorithm design, and empirical evaluation. Recent experiments span controlled optimization problems, image classification, and language-model pretraining.

