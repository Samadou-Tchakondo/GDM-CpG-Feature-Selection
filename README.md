# Machine Learning Feature Selection for Gestational Diabetes Prediction

## Overview

This repository contains a reproducible machine learning analysis aimed at identifying CpG DNA methylation biomarkers associated with gestational diabetes mellitus (GDM).

The study evaluates twelve candidate CpG sites measured during the first trimester of pregnancy to determine their predictive value for GDM using multiple machine learning algorithms.

The analysis compares model performance and identifies CpG markers that consistently contribute to prediction across different modelling approaches.

---

## Methods

Seven machine learning models were implemented:

- Logistic Regression
- LASSO (L1-regularized logistic regression)
- K-Nearest Neighbours (KNN)
- Support Vector Machine (RBF kernel)
- Naïve Bayes
- Random Forest
- XGBoost

Model performance was evaluated using **10-fold cross-validation** and quantified using the **Area Under the Receiver Operating Characteristic Curve (AUC)**.

Feature importance was extracted using model-specific importance measures and permutation importance for SVM.

---

## Dataset

The dataset consists of:

- **258 participants**
- **12 CpG methylation markers**
- Outcome variable: **Gestational Diabetes Mellitus (GDM)**

DNA methylation values are represented as **beta values measured in the first trimester**.

---

## Repository Structure
# GDM-CpG-Feature-Selection
Machine learning analysis to identify CpG methylation biomarkers for gestational diabetes prediction
