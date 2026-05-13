# Machine-Learning-Models-for-Molecular-Toxicity-Prediction-in-Early-Drug-Discovery

This repository contains the datasets and Jupyter notebooks used in the study:

## Overview

Drug candidates frequently fail in clinical development due to toxic effects. Early prediction of molecular toxicity is therefore essential to reduce late-stage failures and associated costs. In this study, we developed machine learning (ML) models for toxicity prediction of small molecules using a variety of molecular descriptor and fingerprint representations.

Multiple classification algorithms from the scikit-learn library were systematically evaluated. The best-performing models were optimized using hyperparameter tuning and assessed through repeated 10-fold cross-validation. External validation was performed using independent datasets covering different toxicity endpoints. To improve robustness and predictive stability, an ensemble voting approach combining multiple models was also implemented.

The results show that ensemble models provide more consistent performance across datasets compared to individual classifiers, highlighting their potential for reliable toxicity screening in early-stage drug discovery.

---
## Contents

- `data/` — training and external validation datasets  
- `notebooks/` — Jupyter notebooks for data preprocessing, model development, and evaluation  

## Usage

Notebooks can be run in a standard Python environment with common scientific libraries (e.g., scikit-learn, pandas, numpy).

Run the notebooks in sequence to reproduce the workflow.

## Contact

Berna Doğan — bernadogan@itu.edu.tr
