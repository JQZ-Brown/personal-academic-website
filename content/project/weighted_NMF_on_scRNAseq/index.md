---
title: Dropout-Aware Weighted NMF on scRNA-seq Data
summary: The final project for CS2952Q Robust Algorithms for Machine Learning.
tags:
- Course
- scRNA-seq
date: "2022-12-29T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Poster
  focal_point: Smart



url_code: ""
url_pdf: "./Dropout_Aware_Weighted_NMF_on_scRNA_seq_Data.pdf"
url_slides: "./Non-negative Matrix Factorization on scRNA-seq Data.pdf"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This is the final project for *CS2952Q Robust Algorithms for Machine Learning*. 

Non-negative matrix factorization (NMF) aims to infer low-dimensional structure from high-dimensional genomic data to understand and visualize complex biological processes. In recent years, the rapid development of single-cell RNA sequencing (scRNA-seq) enables a single-cell level of gene profiling. Previous studies have applied NMF on scRNA-seq data to obtain a finer resolution of biological system understanding, but the high sparsity and the complicated structure of dropouts (i.e., zero values) in scRNA-seq data pose challenges to NMF optimization. To address this problem, in this study, we propose a dropout-aware weighted non-negative matrix factorization (DA-WNMF) to deal with the high sparsity based on Bayesian factorization. On experimental scRNA-seq data, DA-WNMF outperforms previous works when the data is not too sparse (e.g., has around 80% zeros) but fails for very-sparse data (i.e., has more than 90% zeros).  
