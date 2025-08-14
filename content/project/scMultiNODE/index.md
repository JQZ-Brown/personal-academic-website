---
title: "scNODE: Generative Model for Temporal Single Cell Transcriptomic Data Prediction"
summary: "We introduce scMultiNODE, an unsupervised integration model that combines gene expression and chromatin accessibility measurements in developing single cells, while preserving cell type variations and cellular dynamics. First, scMultiNODE uses a scalable, Quantized Gromov-Wasserstein optimal transport to align a large number of cells across different measurements. Next, it utilizes neural ordinary differential equations to explicitly model cell development with a regularization term to learn a dynamic latent space."
date: "2024-04-15"

# Optional external URL for project (replaces project detail page).
external_link: https://github.com/rsinghlab/scNODE

featured: true

url_code: https://github.com/rsinghlab/scNODE
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example


links:
  - icon: book
    icon_pack: fas
    name: Related Paper
    url: "/publication/scNODE/"


image:
  caption: "Visualization of scNODE"
  focal_point: Smart
  preview_only: false
---

scNODE is a generative model that simulates and predicts realistic in silico single-cell gene expressions at any timepoint. scNODE integrates the idea of variational autoencoder (VAE) and neural ordinary differential equation (ODE) to model cell developmental landscapes on the non-linear manifold. 

