---
title: "Projects"
permalink: /projects/
layout: single
---

# 🧪 Selected Projects

### 🧾 Master’s Thesis – Tumor Mutation Tree Clustering 

Developed a machine learning pipeline for clustering tumor mutation trees using structural features extracted through graph kernels. Applied the method to diverse datasets, including a **real-world AML cohort** (123 trees), a **pan-cancer tree collection** spanning six cancer types, and a **synthetic dataset** designed with known structural patterns. By replacing neural network embeddings with kernel-derived cosine similarities, the pipeline achieved **comparable or better clustering performance** while **reducing runtime significantly**. Key evaluation results include **Adjusted Rand Index (ARI = 0.62)**, **Mantel correlation (r = 0.71)**, and a **+728% improvement in Maximum Common Subgraph (MCS) score** over baseline. This lightweight, interpretable approach offers a practical alternative for analyzing biological graph data with minimal computational cost.


*GitHub repository coming soon.*

---

### 🧬 FOXC2 RNA-seq Differential Expression Analysis  
Analyzed RNA-seq data from FOXC2-knockout mouse melanoma cells to investigate transcriptomic changes related to immune evasion and interferon signaling.  
Pipeline includes quality control, pseudoalignment with Kallisto, differential expression (limma/voom), and GO enrichment (clusterProfiler).  
[🔗 View on GitHub](https://github.com/Tamilaam/RNAseq-FOXC2-Melanoma)

---

### ⚙️ Bioprocess Modeling and Simulation Projects  
A series of simulations and models for microbial bioreactors and biochemical systems using Python during *Mathematical Modeling for Biology* course.

- **Continuous Bioreactor Simulation (Chemostat):**  
  Simulated biomass and substrate dynamics under various dilution rates using Monod kinetics.  
  [🔗 Chemostat Simulation](https://github.com/Tamilaam/bioreactor-chemostat-simulation/blob/main/Bioreactor.ipynb)

- **Nonlinear & Oscillatory Dynamics:**  
  Modeled substrate inhibition, washout, vector fields, and delay effects in bioprocess systems.  
  [🔗 Nonlinear Dynamics Project](https://github.com/Tamilaam/bioprocess-modeling-course-projects/blob/main/Bioreactor_Nonlinear_Dynamics.ipynb)

- **Finite-Element Simulation of Diffusion-Reaction:**  
  Simulated substrate diffusion and Monod-based enzymatic consumption inside a spherical immobilized-cell bead using FEM (FEniCS).  
  Included parameter sweeps, nonlinear solver setup, and radial concentration gradients.  
  [🔗 FEA Monod Diffusion](https://github.com/Tamilaam/FEA_monod-diffusion-simulation/blob/main/FEA_monod_diffusion.ipynb)

---

### 🧠 Machine Learning & Data Science Projects

- **DNA Contour Length Analysis with ML:**  
  Estimated DNA rise-per-residue (rpr) from AFM measurements using both regression and a KNN classifier to distinguish DNA types.  
  [🔗 Contour Length Project](https://github.com/Tamilaam/DataAnalysis_DLVO_IonicStrength/blob/main/DataAnalysis_DLVO_IonicStrength.ipynb)

- **Raman Spectroscopy Classification:**  
  Analyzed Raman spectra of 32 pharmaceutical compounds. Applied PCA, UMAP, and ML classifiers (SVM, Logistic Regression) to identify key spectral features.  
  [🔗 Raman Spectroscopy Project](https://github.com/Tamilaam/MachineLearning_Raman_Spectroscopy_Analysis)

- **Hourly Electricity Load Forecasting (PJM):**  
  Applied time-series feature engineering and *Random Forest regression* to predict short-term electricity demand using historical PJM data.  
  [🔗 Load Forecasting Project](https://github.com/Tamilaam/MachineLearning_electricity_load_forecasting)

- **ML for DNA Sequence Analysis:**  
  Explored supervised learning on DNA sequence features.  
  [🔗 DNA ML Project](https://github.com/Tamilaam/MachineLearning_DNA_Analysis)
