---
title: Awards
layout: default
---

### EventFlow: Forecasting Temporal Point Processes with Flow Matching

### [EventFlow: Forecasting Temporal Point Processes with Flow Matching](/virtual/2026/award/13628)

Gavin Kerrigan ⋅ Kai Nelson ⋅ Padhraic Smyth

<span class="eyebrow-text">Abstract</span>

Continuous-time event sequences, in which events occur at irregular intervals, are ubiquitous across a wide range of industrial and scientific domains. The contemporary modeling paradigm is to treat such data as realizations of a temporal point process, and in machine learning it is common to model temporal point processes in an autoregressive fashion using a neural network. While autoregressive models are successful in predicting the time of a single subsequent event, their performance can degrade when forecasting longer horizons due to cascading errors and myopic predictions. We propose EventFlow, a non-autoregressive generative model for temporal point processes. The model builds on the flow matching framework in order to directly learn joint distributions over event times, side-stepping the autoregressive process. EventFlow is simple to implement and achieves a 20\\-53\\ lower forecast error than the nearest baseline on standard TPP benchmarks while simultaneously using fewer model calls at sampling time.

### [We Still Don’t Understand High-Dimensional Bayesian Optimization](/virtual/2026/award/13739)

Colin Doumont ⋅ Donney Fan ⋅ Natalie Maus ⋅ Jacob Gardner ⋅ Henry Moss ⋅ Geoff Pleiss

<span class="eyebrow-text">Abstract</span>

Existing high-dimensional Bayesian optimization (BO) methods aim to overcome the curse of dimensionality by carefully encoding structural assumptions, from locality to sparsity to smoothness, into the optimization procedure. Surprisingly, we demonstrate that these approaches are outperformed by arguably the simplest method imaginable: Bayesian linear regression. After applying a geometric transformation to avoid boundary-seeking behavior, Gaussian processes with linear kernels match state-of-the-art performance on tasks with 60- to 6,000-dimensional search spaces. Linear models offer numerous advantages over their non-parametric counterparts: they afford closed-form sampling and their computation scales linearly with data, a fact we exploit on molecular optimization tasks with \>20,000 observations. Coupled with empirical analyses, our results suggest the need to depart from past intuitions about BO methods in high-dimensions.

### [Non-stochastic Best Arm Identification and Hyperparameter Optimization](/virtual/2026/award/14090)

Kevin Jamieson ⋅ Ameet Talwalkar

<span class="eyebrow-text">Abstract</span>

Motivated by the task of hyperparameter optimization, we introduce the \em non-stochastic best-arm identification problem. We identify an attractive algorithm for this setting that makes no assumptions on the convergence behavior of the arms’ losses, has no free-parameters to adjust, provably outperforms the uniform allocation baseline in favorable conditions, and performs comparably (up to \log factors) otherwise. Next, by leveraging the iterative nature of many learning algorithms, we cast hyperparameter optimization as an instance of non-stochastic best-arm identification. Our empirical results show that, by allocating more resources to promising hyperparameter settings, our approach achieves comparable test accuracies an order of magnitude faster than the uniform strategy. The robustness and simplicity of our approach makes it well-suited to ultimately replace the uniform strategy currently used in most machine learning software packages.
