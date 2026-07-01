# Assignment 1: k-NN and Decision Tree Classifiers

## Project Overview
This project focuses on implementing and evaluating **k-Nearest Neighbors (k-NN)** and **Decision Tree** classifiers using the Breast Cancer Wisconsin dataset. It covers hands-on experience in data preprocessing, hyperparameter tuning, model evaluation, and medical misclassification analysis.

## Dataset
* **Breast Cancer Wisconsin Dataset:** 569 samples with 30 numerical features computed from digitized images of fine needle aspirate (FNA) biopsies.
* **Task:** Binary classification (predicting whether a tumor is Malignant or Benign).

## Key Implementation Steps
1. **Data Preprocessing & Analysis:** 
   * Class distribution analysis and feature statistics.
   * Data visualization (feature histograms).
   * Feature standardization (zero mean, unit variance) properly fitted only on the training set to prevent data leakage.
2. **k-Nearest Neighbors (k-NN):**
   * Hyperparameter tuning across $k \in \{1,3,5,7,9,15,21\}$.
   * Performance evaluation using validation set accuracy curves, test accuracy, and confusion matrix analysis.
3. **Decision Tree Classifier:**
   * Grid search tuning for `max_depth` and `min_samples_split`.
   * Evaluation via confusion matrix and feature importance visualization (bar charts).
4. **Medical Misclassification Analysis:**
   * Evaluation of False Positives vs. False Negatives in a healthcare context to determine which error is more critical.
