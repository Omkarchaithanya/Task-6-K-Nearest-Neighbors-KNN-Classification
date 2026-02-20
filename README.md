# K-Nearest Neighbors (KNN) Classification

## Overview

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm for a classification problem using **Scikit-learn, Pandas, and Matplotlib**.

The objective is to understand how KNN works, experiment with different values of K, evaluate model performance, and visualize decision boundaries.

---

## Objective

- Implement KNN for classification
- Normalize features
- Experiment with different K values
- Evaluate using accuracy and confusion matrix
- Visualize decision boundaries

---

## Dataset

This project uses the built-in **Iris dataset** from Scikit-learn.

For simplicity and visualization:
- Only the first two features are used
- The problem is converted into binary classification:
  - Class 0 vs Other classes

**Features used:**
- Feature 1: Sepal Length
- Feature 2: Sepal Width

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Project Workflow

### 1. Import Libraries
Load required libraries for preprocessing, modeling, and visualization.

### 2. Load Dataset
Use `load_iris()` from Scikit-learn.

### 3. Train-Test Split
Split dataset into:
- 70% Training
- 30% Testing

### 4. Feature Scaling
Apply `StandardScaler` because KNN is distance-based and sensitive to feature magnitude.

### 5. Model Training

Use:

```python
from sklearn.neighbors import KNeighborsClassifier
