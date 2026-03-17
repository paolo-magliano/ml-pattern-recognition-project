# Fingerprint Recognition with Machine Learning

Implementation and evaluation of **classical machine learning models**
for fingerprint matching.

The project compares **generative and discriminative approaches**,
including calibration and model fusion, on a binary classification
task.\
Developed as part of the *Machine Learning and Pattern Recognition*
course at Politecnico di Torino (**10/10**).

------------------------------------------------------------------------

## Features

-   Comparative analysis of **MVG, Logistic Regression, SVM, and GMM**
-   Evaluation under **different priors and cost-sensitive scenarios**
-   Study of **feature distributions and class separability**
-   **Score calibration and model fusion** for performance improvement

------------------------------------------------------------------------

## Overview

The task consists of classifying fingerprint pairs as:

-   **Genuine** (same fingerprint)
-   **Impostor** (different fingerprints)

The dataset is a **6-dimensional feature representation** extracted from
fingerprint images.

The project investigates how different models behave under
**distributional complexity**, **non-linearity**, and
**application-dependent costs**.

------------------------------------------------------------------------

## Models

-   **Multivariate Gaussian Models (MVG)**
-   **Logistic Regression (LR)**
-   **Support Vector Machines (SVM)**
-   **Gaussian Mixture Models (GMM)**

------------------------------------------------------------------------

## Methodology

-   Feature analysis and visualization\
-   Dimensionality reduction (PCA, LDA)\
-   Linear vs non-linear model comparison\
-   Evaluation using cost-based metrics (DCF)\
-   Score calibration and fusion

------------------------------------------------------------------------

## Results

-   **GMM (diagonal, 8 components)** achieved the best standalone
    performance\
-   **Polynomial SVMs** effectively captured non-linear feature
    interactions\
-   **Model fusion (SVM + GMM)** yielded the best overall results\
-   Calibration had limited impact compared to fusion

------------------------------------------------------------------------

## Report

A detailed description of the methodology, experiments, and results is
available in:

📄 `report.pdf`

------------------------------------------------------------------------

## Notes

This project emphasizes: - rigorous evaluation of ML models\
- cost-sensitive decision making\
- benefits of combining complementary models
