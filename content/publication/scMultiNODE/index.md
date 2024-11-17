---
title: "scMultiNODE: Integrative Model for Multi-Modal Temporal Single-Cell Data"

publication_types:
  - "1"
authors:
  - admin
  - Manav Chakravarthy
  - Ritambhara Singh
doi: https://doi.org/10.1101/2024.10.27.620531
publication: biorxiv
abstract: "Measuring single-cell genomic profiles at different timepoints enables our understanding of cell development. This understanding is more comprehensive when we perform an integrative analysis of multiple measurements (or modalities) across various developmental stages. However, obtaining such measurements from the same set of single cells is resource-intensive, restricting our ability to study them integratively. We propose an unsupervised integration model, scMultiNODE, that integrates gene expression and chromatin accessibility measurements in developing single cells while preserving cell type variations and cellular dynamics. scMultiNODE uses autoencoders to learn nonlinear low-dimensional cell representation and optimal transport to align cells across different measurements. Next, it utilizes neural ordinary differential equations to explicitly model cell development with a regularization term to learn a dynamic latent space. Our experiments on four real-world developmental single-cell datasets show that scMultiNODE can integrate temporally profiled multi-modal single-cell measurements better than existing methods that focus on cell type variations and tend to ignore cellular dynamics. We also show that scMultiNODE's joint latent space helps with the downstream analysis of single-cell development. The data and code are publicly available at https://github.com/rsinghlab/scMultiNODE."
draft: false
featured: true
tags: ["multi-modal integration", "featured"]
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-11-01T00:00:00.000Z
url_slides: ""
publishDate: 2024-11-01T00:00:00.000Z
---
