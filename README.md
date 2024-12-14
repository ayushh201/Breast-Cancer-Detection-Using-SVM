# Breast Cancer Detection - Classification Problem

## Project Overview
This project focuses on detecting breast cancer using a classification approach. We use machine learning techniques such as Support Vector Machines (SVM) to classify tumors as malignant or benign based on specific features.

---

## Table of Contents
1. [Data Visualization](#data-visualization)
2. [Model Training Using SVM](#model-training-using-svm)
3. [Model Evaluation](#model-evaluation)
4. [Improving Model Performance](#improving-model-performance)
   - Feature Scaling and Normalization
   - Tuning SVM Parameters (C and Gamma)

---

## Data Visualization
- We begin by exploring the dataset through visualizations to understand feature distributions and relationships.
- Techniques used include:
  - Histograms
  - Pair plots
  - Correlation heatmaps

---

## Model Training Using SVM
- The Support Vector Machine (SVM) model is used for classification.
- Steps:
  - Data pre-processing
  - Splitting data into training and testing sets
  - Training the model using default SVM parameters

---

## Model Evaluation
- We evaluate the trained model using the **classification report**, which includes:
  - Precision
  - Recall
  - F1-score
  - Accuracy
- A confusion matrix is also plotted for better insight into model performance.

---

## Improving Model Performance
### Feature Scaling and Normalization
- We apply MinMaxScaler and StandardScaler to scale features and improve model performance.

### Tuning SVM Parameters (C and Gamma)
- We perform hyperparameter tuning using GridSearchCV.
- Best parameter values for **C** (regularization) and **Gamma** (kernel coefficient) are identified to enhance accuracy.

---


