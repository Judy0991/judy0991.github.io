---
layout: page
title: Research
permalink: /research/
description: Methodological and applied research in biostatistics, causal inference, and health data science.
nav: true
nav_order: 1
---

My work combines statistical methodology with clinical and real-world data. I
am particularly interested in problems where missingness, heterogeneity, or
limited sample size make standard analyses unreliable, and where a transparent
model is essential for scientific or clinical interpretation.

## Current research

<div class="research-list">
  <article class="research-card featured">
    <div class="research-meta">Causal inference · Missing data · EHR</div>
    <h3>Multiple-imputation empirical-likelihood synthetic control</h3>
    <p>
      I am developing MI-EL SCM, a synthetic-control framework for estimating
      treatment effects when donor pre-intervention outcomes are incomplete.
      The project uses empirical likelihood to give the donor weights a
      tractable representation and studies when pooling across imputations
      recovers the complete-data target.
    </p>
    <p>
      The work includes theoretical analysis, simulation studies under several
      missingness mechanisms, and a longitudinal EHR application involving
      kidney-stone treatment trajectories.
    </p>
    <div class="research-foot">Mentor: Prof. Jing Huang · University of Pennsylvania</div>
  </article>

  <article class="research-card">
    <div class="research-meta">Clinical screening · Longitudinal data · Autism</div>
    <h3>Autism screening and underdiagnosis</h3>
    <p>
      Using clinical screening data from the Children's Hospital of
      Philadelphia, I am studying how early-childhood developmental and autism
      screening measures relate to later ASD diagnosis. The broader goal is to
      understand heterogeneity in screening performance and potential patterns
      of underdiagnosis across patient groups.
    </p>
    <div class="research-foot">Mentor: Prof. Jing Huang · Children's Hospital of Philadelphia</div>
  </article>

  <article class="research-card">
    <div class="research-meta">Medical imaging · Radiomics · Risk prediction</div>
    <h3>Cervical-cancer recurrence prediction from non-contrast MRI</h3>
    <p>
      I compared deep-learning models (3D ResNet50 and FCNN) with traditional
      machine-learning approaches for MRI radiomics. A LASSO-selected XGBoost
      model was incorporated into a nomogram for predicting recurrence and
      progression-free survival after concurrent chemoradiotherapy.
    </p>
    <div class="research-foot">Co-first-author publication · Peking University Cancer Hospital & Institute</div>
  </article>

  <article class="research-card">
    <div class="research-meta">Health AI · Annotation · Auditability</div>
    <h3>Auditable public-health policy communication with AI agents</h3>
    <p>
      I contributed to data annotation and discussions that established the
      annotation standards for an agentic framework designed to support
      auditable public-health policy communication.
    </p>
    <div class="research-foot">Collaborative manuscript submitted to <em>Nature Health</em></div>
  </article>
</div>

## Earlier quantitative work

Before focusing on biostatistics and health data science, I worked on a range of
applied modeling problems: forecasting and production planning for a restaurant
chain, randomness testing for national lottery systems, virus-drug association
prediction, and safe operating boundaries for blue and green water in the
Yellow River Basin. These projects built my foundation in Python, R, MATLAB,
machine learning, optimization, time-series analysis, and scientific computing.

## Research interests

<div class="interest-cloud">
  <span>Biostatistics</span>
  <span>Causal inference</span>
  <span>Missing data</span>
  <span>Synthetic control methods</span>
  <span>Real-world evidence</span>
  <span>Longitudinal data</span>
  <span>Clinical trials</span>
  <span>Health AI</span>
</div>
