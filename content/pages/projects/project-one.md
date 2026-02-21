---
type: ProjectLayout
title: AI Prostate Cancer Detection with mpMRI
colors: colors-a
date: '2024-06-01'
client: Bachelor Thesis
description: >-
  Built and evaluated a machine-learning pipeline for prostate cancer detection using
  multiparametric MRI (mpMRI), focusing on robust preprocessing and clinically meaningful evaluation.
featuredImage:
  type: ImageBlock
  url: /images/bg1.jpg
  altText: Prostate cancer detection project thumbnail
media:
  type: ImageBlock
  url: /images/bg1.jpg
  altText: Multiparametric MRI project image
---

## Overview
For my bachelor thesis, I explored how machine learning can support **prostate cancer detection** using **multiparametric MRI (mpMRI)**.
The goal was to build and evaluate an end-to-end pipeline that learns from imaging data and produces reliable predictions that can
support clinical decision-making.

## What I did
- **Data understanding & preparation:** worked with mpMRI data and corresponding labels; organized data structures for model training.
- **Preprocessing pipeline:** cleaning and standardization steps to make the input consistent and suitable for ML.
- **Model training & evaluation:** trained and compared models, focusing on performance metrics that matter for medical classification.
- **Error analysis:** investigated failure cases and potential causes (data quality, class imbalance, generalization limits).
- **Documentation:** wrote up the approach, experiments, and results in a thesis report.

## Tech stack
- Python (NumPy / pandas)
- Machine learning (scikit-learn / deep learning framework if applicable)
- Data processing & experimentation workflows

## Outcome
- A documented pipeline + experiments demonstrating the feasibility of ML-based classification on mpMRI data.
- Practical insights into dataset limitations, evaluation strategy, and what would be needed to move toward clinical use.

## What I’d improve next
- Stronger generalization testing
- Better handling of class imbalance and calibration
- More explainability for clinical interpretability
