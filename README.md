# animal-image-classifier
# Animal Image Classifier

## Overview

This project explores multiclass animal image classification using deep learning.

The goal is to build a simple CNN baseline and progressively improve generalization using techniques such as data augmentation, regularization, and transfer learning.

## Problem

Given an animal image, predict its corresponding animal class.

This is a single-label multiclass classification problem.

## Project Goals

- Build a clean image-classification data pipeline.
- Train a small CNN from scratch as a baseline.
- Analyze training and validation performance.
- Apply regularization and data augmentation.
- Compare the baseline against transfer learning.
- Perform error analysis using confusion matrices and per-class metrics.
- Explore confidence-based predictions for uncertain examples.

## Evaluation

Primary metrics:

- Accuracy
- Macro F1 score
- Per-class recall
- Confusion matrix

## Planned Experiments

### Experiment 0 — Data Analysis
Inspect class distribution, image quality, imbalance, and potential data leakage.

### Experiment 1 — CNN Baseline
Train a small convolutional neural network from scratch.

### Experiment 2 — Regularization
Evaluate techniques such as dropout, weight decay, and data augmentation.

### Experiment 3 — Transfer Learning
Compare the baseline CNN against a pretrained image-classification model.

### Experiment 4 — Error Analysis
Analyze class-level errors and identify systematic failure modes.

### Experiment 5 — Confidence-Aware Prediction
Investigate whether low-confidence predictions should be marked as uncertain.

## Repository Structure

```text
notebooks/   Exploratory analysis
src/         Training and model code
configs/     Experiment configurations
results/     Metrics and experiment outputs
models/      Saved model checkpoints
```

## Status

Project setup in progress.