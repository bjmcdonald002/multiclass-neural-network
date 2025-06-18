# Multiclass Neural Network

This repository contains a single Jupyter notebook, **Multiclass_Neural_Network.ipynb**, which demonstrates how to build, train, and evaluate a fully-connected neural network for multi-class classification. The project was completed as part of a graduate-level deep learning course, and the resulting model achieved the highest test accuracy in the class. 

## Overview

The notebook walks through every stage of a typical deep learning pipeline:
- **Data loading and preprocessing:** Includes shuffling to remove class order bias, normalization of features, and one-hot encoding of class labels.
- **Model architecture comparison:** Systematic evaluation of four neural network architectures, varying the number of hidden layers and neurons per layer.
- **Hyperparameter tuning:** L2 regularization strength and learning rate were manually tuned to maximize model accuracy.
- **Training and evaluation:** Utilizes 4-fold cross-validation, early stopping, and careful reporting of results.
- **Results visualization:** Average test accuracies are presented in a clear bar chart for easy comparison.
- **Final model selection:** The best-performing model is labeled and prepared for use with new data.

## Data Requirements

This notebook expects a CSV named `data2.csv` in the repository root, containing the features and class labels as described in the project.

> **Note:** The dataset was provided by the course instructor and is **not redistributed** here.  
> If you have legitimate access, place your copy of `data2.csv` beside the notebook before running.

## Contents

- `Multiclass_Neural_Network.ipynb` — Main notebook containing the entire workflow, from data preprocessing through model training and evaluation.

## Key Lessons

- The importance of shuffling and normalizing data before training neural networks.
- How systematic experimentation with model architecture and hyperparameters can significantly improve accuracy.
- The value of early stopping and cross-validation for fair, unbiased model selection.
- The practical benefit of iterating, tinkering, and verifying—rather than relying solely on default settings.

## Author

Barrett James McDonald, PhD Student, University of South Florida

---

If you have any questions or feedback, feel free to contact me or open an issue. 💬
