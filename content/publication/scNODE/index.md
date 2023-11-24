---
title: scNODE -- Generative Model for Temporal Single Cell Transcriptomic Data Prediction

publication_types:
  - "2"
authors:
  - admin
  - Erica Larschan
  - Jeremy Bigness
  - Ritambhara Singh
doi: https://doi.org/10.1101/2023.11.22.568346
abstract: "Temporal measurements using single-cell RNA sequencing (scRNA-seq) technology enable the study of gene expression programs of individual cells for normal developmental processes or diseased physiological states. However, due to the labor, expense, and technical challenges associated with these experiments, researchers are only able to profile gene expression at discrete and sparsely spaced time points. This results in information loss between consecutive discrete time points and impedes the downstream developmental analysis. To address this problem, we propose scNODE, an end-to-end model that can simulate and predict realistic in silico single-cell samples at any time point to enable temporal downstream analyses. Our method integrates a variational autoencoder (VAE) with neural ordinary differential equations (ODEs) to predict gene expression in a continuous and non-linear latent space. Importantly, scNODE adds a regularization term to integrate overall dynamics of cell developments to the latent space, such that the learned latent representation is informative and interpretable. Our evaluations on six real-world scRNA-seq datasets show that scNODE achieves higher predictive performance than state-of-the-art methods. We further demonstrate that scNODE learns an interpretable latent space, and helps recapitulate cell-type developmental trajectories. The data and code are publicly available at https://github.com/rsinghlab/scNODE"
draft: false
featured: true
tags: ["scRNA-seq", "featured"]
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2023-11-24T04:00:52.017Z
---
