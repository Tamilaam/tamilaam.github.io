---
title: "🧠 Machine Learning Pipeline for Clustering Tumor Mutation Trees Using Graph Kernels"
layout: single
date: 2025-09-04
author_profile: true
read_time: false
comments: false
share: false
last_modified_at: false
---

*ML and biology? Sounded like the best-fit thesis for me.:)*  
*I did my Master's thesis through the Erasmus Exchange Programme, two of the coolest things I ever did in my academic journey.*

During my Master's thesis at the **Algorithmic Bioinformatics Lab**, I developed a machine learning pipeline to cluster tumor mutation trees. The method uses graph kernels (Weisfeiler-Lehman) to extract subtree patterns and computes cosine similarities between graph embeddings, removing the need for neural training. *(Isn't it cool?)*

<p align="center">
  <img src="/assets/images/umap.png" alt="The beauty of UMAP" width="70%">
  <figcaption><strong>Figure 1:</strong> The beauty of UMAP</figcaption>
</p>

To evaluate performance, we compared our approach to the original pipeline, showing improved clustering accuracy (increased silhouette score) and better structural coherence with significantly reduced runtime. Maximum Common Subgraph (MCS) analysis *(my favorite part!)* showed a **728.7% increase** in within-cluster structural similarity over baseline compared to a 683.5% increase in the original pipeline, confirming more biologically meaningful groupings.

The results were compared to the original pipeline which used neural network training. We got highly comparable results through **Adjusted Rand Index (ARI = 0.62)** and **Mantel correlation (r = 0.71)**. *(ARI measures how well our cluster content matches the original — 1 means perfect match. Mantel tells us how correlated two distance matrices are — also max at 1. And yes, my p-value was close to 0. Nothing by accident. :))*

*If it sounds complicated... it's okay. It did for me too. If you write to me, we can talk more!*

We used these clusters to explore co-occurrence and mutual exclusivity of mutations, improving the biological interpretability of mutation events in computational oncology. *(Let's help physicians with diagnostic and therapeutic decisions!)* 

The project deepened my skills in graph-based modeling, machine learning approaches to biological questions, and bioinformatics workflows.

<p align="center">
  <img src="/assets/images/trees.png" alt="trees" width="70%">
  <figcaption><strong>Figure 1:</strong> Orange mutation is the first mutation in these tumours and it just keeps happening with red one. What does it tell us?</figcaption>
</p>

*GitHub repository coming soon...*

