# Classification

## Overview

This project implements a supervised classification workflow using a tabular dataset. It includes data loading, data analysis, preprocessing, model training (Logistic Regression, Decision Tree, and Naive Bayes), hyperparameter tuning, evaluation on a held-out test set, and generation of predictions on a blinded test set. All steps are encapsulated in `Classification.ipynb`.

## Repository Structure

- **Classification.ipynb**  
  Jupyter Notebook containing:
  - Library imports
  - Data loading and inspection
  - Handling missing/infinite values
  - Train/validation split
  - Feature scaling
  - Models:
    - Logistic Regression 
    - Decision Tree 
    - Gaussian Naive Bayes
  - Evaluation metrics (Accuracy, AUROC, Recall, Specificity, F1‐score, Classification Report)
  - Generation of blinded test‐set predictions and saving CSV outputs.

- **train_set.csv**  
  Labeled training data. 

- **test_set.csv**  
  Labeled test data used for final model evaluation.

- **blinded_test_set.csv**  
  Unlabeled test data for which the notebook’s trained models will generate predictions. 



