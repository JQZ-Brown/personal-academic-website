---
title: "scNODE: Generative Model for Temporal Single Cell Transcriptomic Data Prediction"

publication_types:
  - "1"
authors:
  - admin
  - Erica Larschan
  - Jeremy Bigness
  - Ritambhara Singh
doi: https://doi.org/10.1101/2023.11.22.568346
publication: 23rd European Conference on Computational Biology (ECCB 2024)
abstract: "Measurement of single-cell gene expression at different timepoints enables the study of cell development. However, due to the resource constraints and technical challenges associated with the single-cell experiments, researchers can only profile gene expression at discrete and sparsely-sampled timepoints. This missing timepoint information impedes downstream cell developmental analyses. We propose scNODE, an end-to-end deep learning model that can predict in silico single-cell gene expression at unobserved timepoints. scNODE integrates a variational autoencoder (VAE) with neural ordinary differential equations (ODEs) to predict gene expression using a continuous and non-linear latent space. Importantly, we incorporate a dynamic regularization term to learn a latent space that is robust against distribution shifts when predicting single-cell gene expression at unobserved timepoints. Our evaluations on three real-world scRNA-seq datasets show that scNODEE achieves higher predictive performance than state-of-the-art methods. We further demonstrate that scNODE's predictions help cell trajectory inference under the missing timepoint paradigm and the learned latent space is useful for in silico perturbation analysis of relevant genes along a developmental cell path. The data and code are publicly available at https://github.com/rsinghlab/scNODE."
draft: false
featured: true
tags: ["scRNA-seq", "featured"]
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-6-1T04:00:52.017Z
---
