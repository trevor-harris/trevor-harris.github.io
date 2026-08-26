---
layout: home
title: Home
permalink: /
---

<section class="hero">
  <aside class="profile-card">
    <img class="profile-photo" src="/assets/images/trevor.jpg" alt="Trevor Harris" />
    <p class="profile-name">Trevor Harris, PhD</p>
    <p class="profile-role">Assistant Professor<br />Department of Statistics<br />University of Connecticut</p>
    <div class="profile-links">
      <a class="button button-primary" href="/assets/pdf/CV/CV.pdf">CV</a>
      <a class="button" href="mailto:trevor.a.harris@uconn.edu">Email</a>
      <a class="button" href="https://github.com/trevor-harris">GitHub</a>
      <a class="button" href="https://statistics.uconn.edu/person/trevor-harris/">UConn</a>
    </div>
  </aside>

  <div class="hero-copy">
    <p class="eyebrow">Statistics · Machine Learning · Scientific Computing</p>
    <h1>Reliable uncertainty for modern scientific machine learning.</h1>
    <p class="lede">My research develops rigorous statistical machine learning methods for uncertainty-aware prediction and decision-making in complex, high-dimensional systems. I focus on calibrated predictive distributions, conformal inference, generative modeling, operator learning, and structured prediction for spatiotemporal data.</p>
    <div class="topic-list" aria-label="Research topics">
      <span>Conformal inference</span>
      <span>Generative modeling</span>
      <span>Operator learning</span>
      <span>Climate and environmental systems</span>
    </div>
  </div>
</section>

## Recent work

<div class="work-grid">
  <article class="work-card">
    <p class="card-meta">2026 · NeurIPS, in review</p>
    <h3>Flow-Based Conformal Predictive Distributions</h3>
    <p>Turns high-dimensional conformal prediction sets into calibrated distributions that can be sampled and used in downstream scientific tasks.</p>
    <p class="card-links"><a href="https://arxiv.org/abs/2602.07633">Paper</a><a href="https://github.com/trevor-harris/flowcp">Code</a></p>
  </article>

  <article class="work-card">
    <p class="card-meta">2026 · Preprint</p>
    <h3>Manifold Constrained Conformal Prediction for Spatial Events</h3>
    <p>Builds calibrated, geometrically plausible prediction sets for spatial event clouds such as tropical cyclone genesis and earthquakes.</p>
    <p class="card-links"><a href="https://arxiv.org/abs/2607.10008">Paper</a></p>
  </article>

  <article class="work-card">
    <p class="card-meta">2025 · TMLR, in review</p>
    <h3>Locally Adaptive Conformal Inference for Operator Models</h3>
    <p>Provides locally adaptive, function-valued uncertainty sets for neural operators with finite-sample statistical guarantees.</p>
    <p class="card-links"><a href="https://arxiv.org/abs/2507.20975">Paper</a><a href="https://github.com/trevor-harris/LSCI">Code</a></p>
  </article>
</div>

## Research program

<div class="research-themes">
  <section class="theme-block">
    <p class="theme-number">01</p>
    <div>
      <h3>Calibrated generative inference</h3>
      <p>I develop conformal predictive distributions and flow-based methods that retain finite-sample reliability while representing uncertainty over fields, functions, trajectories, and point processes. The goal is to make modern generative models statistically calibrated and usable for downstream decisions.</p>
    </div>
  </section>

  <section class="theme-block">
    <p class="theme-number">02</p>
    <div>
      <h3>Scientific machine learning for climate and spatiotemporal systems</h3>
      <p>Climate provides a demanding test bed for model evaluation, distribution shift, operator learning, and uncertainty quantification. My work develops distributional metrics for climate-model validation and methods that integrate simulations with observational data to produce more reliable projections.</p>
    </div>
  </section>

  <section class="theme-block">
    <p class="theme-number">03</p>
    <div>
      <h3>Dependence, extremes, and environmental decisions</h3>
      <p>I study spatiotemporal dependence, teleconnections, extremes, and intervention in environmental systems. Applications include compound climate risk, West Nile virus forecasting, mosquito-control policy, and other settings where incomplete monitoring and changing environments complicate prediction.</p>
    </div>
  </section>
</div>

<div class="figure-grid">
  <figure class="research-figure">
    <img src="/assets/images/research/conformal-ensembles.png" alt="Conformal climate projections for temperature and precipitation" />
    <figcaption>Conformal ensembles combine climate-model output with observations to produce tighter, calibrated projections.</figcaption>
  </figure>
  <figure class="research-figure">
    <img src="/assets/images/research/extreme-teleconnections.png" alt="Map of estimated extremal teleconnection structure" />
    <figcaption>Estimated extremal teleconnection structure reveals regions that may contribute to compound climate risk.</figcaption>
  </figure>
</div>

## About

I am an Assistant Professor in the Department of Statistics at the University of Connecticut. Before joining UConn in 2024, I was an Assistant Professor of Statistics at Texas A&M University. I received my PhD in Statistics from the University of Illinois Urbana-Champaign. My work has appeared in NeurIPS, the *Annals of Applied Statistics*, JASA, *Technometrics*, JABES, and scientific application journals, and has been supported by Sandia National Laboratories and private foundations.
