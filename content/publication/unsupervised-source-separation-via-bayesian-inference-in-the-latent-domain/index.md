---
title: Unsupervised Source Separation via Bayesian Inference in the Latent Domain
publication_types:
  - "3"
authors:
  - Michele Mancusi
  - Emilian Postolache
  - Giorgio Mariani
  - Marco Fumero
  - admin
  - Luca Cosmo
  - Emanuele Rodolà
publication_short: arXiv preprint
abstract: State of the art audio source separation models rely on supervised
  data-driven approaches, which can be expensive in terms of labeling resources.
  On the other hand, approaches for training these models without any direct
  supervision are typically high-demanding in terms of memory and time
  requirements, and remain impractical to be used at inference time. We aim to
  tackle these limitations by proposing a simple yet effective unsupervised
  separation algorithm, which operates directly on a latent representation of
  time-domain signals. Our algorithm relies on deep Bayesian priors in the form
  of pre-trained autoregressive networks to model the probability distributions
  of each source. We leverage the low cardinality of the discrete latent space,
  trained with a novel loss term imposing a precise arithmetic structure on it,
  to perform exact Bayesian inference without relying on an approximation
  strategy. We validate our approach on the Slakh dataset demonstrating results
  in line with state of the art supervised approaches while requiring fewer
  resources with respect to other unsupervised methods.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-07-10T13:59:58.492Z
---
