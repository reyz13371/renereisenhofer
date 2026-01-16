---
name: Breast Cancer Diagnosis – Machine Learning Classification
tools: [Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, JupyterLab]
image: /renereisenhofer/assets/images/krankheitsdiagnoseBoxplots.png
description: A machine learning project that classifies breast tumors as benign or malignant using the Wisconsin Breast Cancer dataset.
---

# Breast Cancer Diagnosis (ML)

![Feature Distribution Boxplots](/renereisenhofer/assets/images/krankheitsdiagnoseBoxplots.png)

### 🛠 Tech Stack

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- JupyterLab

---

### 🧠 Project Overview

This project implements a complete machine learning pipeline to classify breast tumors as **benign or malignant** based on numerical tumor features such as radius, texture, perimeter, area, concavity, and symmetry.

The focus was on understanding the full workflow of a classification problem:  
data preparation, feature analysis, model training, evaluation, and optimization.

---

### 📊 Data Preparation & Exploration

- Loaded and cleaned the dataset
- Removed unused columns and encoded diagnosis labels
- Split data into training and test sets
- Applied feature scaling using `StandardScaler`
- Explored feature distributions and outliers using boxplots

![Data Preparation & Encoding](/renereisenhofer/assets/images/krankheitsdiagnoseDatenaufbereitung.png)

---

### 🤖 Model Training & Evaluation

A **Decision Tree Classifier** was trained as a baseline model.

Evaluation included:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

The baseline model achieved an accuracy of approximately **95%**.

![Confusion Matrix](/renereisenhofer/assets/images/krankheitsdiagnose5.png)

---

### 🔧 Hyperparameter Tuning

The Decision Tree was optimized using `RandomizedSearchCV`, tuning:
- Maximum tree depth
- Minimum samples per split and leaf
- Splitting criterion (gini / entropy)

After tuning, model accuracy improved to **~97%**.

![Hyperparameter Tuning Results](/renereisenhofer/assets/images/krankheitsdiagnose6.png)

---

### 🔍 Model Comparison (Extension)

To evaluate alternative approaches, multiple classifiers were trained and compared:

- Random Forest
- Logistic Regression
- Support Vector Machine (SVM)

These models achieved comparable or slightly better performance, especially in terms of ROC-AUC and robustness.

![Model Comparison Results](/renereisenhofer/assets/images/krankheitsdiagnose7.png)

---

### 📌 Project Status

Completed personal machine learning project.  
