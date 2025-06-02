# 🚲 Predicting Urban Mobility with Capital Bikeshare Data: A Supervised Learning Approach

This project presents a comprehensive supervised machine learning pipeline using the **Capital Bikeshare** dataset. It focuses on predictive modeling and model evaluation through the application of regression, classification, and regularization techniques.

---

## 📁 Dataset Information

The dataset (`Data.zip`) contains Capital Bikeshare trip data for the months of **February, March, and April 2024**. Due to file size limitations, the dataset is not included in this repository.

📥 **Download Dataset:** [Click here to access the dataset on Google Drive](https://drive.google.com/drive/u/2/folders/174NY1K1BwPbKH00253POWrBfH2U-k1M6)

> ⚠️ Please ensure the file structure remains unchanged after extraction for smooth execution of the notebook.

---

## 🎯 Problem Statement

The primary objective is to explore and model bike-sharing usage patterns through:

- **Regression models** to predict continuous values such as pollutant concentration levels (`PU_ct`, `DO_ct`)
- **Classification models** to predict categorical outcomes
- **Regularization & Cross-Validation** to enhance model generalization and tune model complexity

---

## 📊 Techniques Applied

### ✅ 1. Regression Modeling
- Multiple Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Evaluation Metrics: **Mean Squared Error (MSE)**, **R² Score**

### ✅ 2. Classification Tasks
- K-Nearest Neighbors (KNN)  
- Logistic Regression  
- Support Vector Classifiers (Linear and RBF kernel)  
- Performance Evaluation using **Accuracy Scores**

### ✅ 3. Model Regularization & Cross-Validation
- Applied **Lasso Regression** for regularization:
  - Coefficient path visualization
  - **GridSearchCV** and **LassoCV** for optimal `alpha` selection
  - Cross-validated performance metrics
- Evaluated **out-of-sample MSE** for robustness and generalizability

---

## 📈 Project Highlights

- ✔️ Feature scaling and dummy encoding implemented
- ✔️ Lasso Regularization effectively selected key predictors
- ✔️ Hyperparameter tuning via cross-validation improved performance
- ✔️ Visual analysis of how regularization influences model simplicity

---
---

## ✅ Conclusion

This project showcases a complete **supervised machine learning workflow**, encompassing:
- Data preprocessing  
- Regression and classification modeling  
- Hyperparameter tuning  
- Model evaluation  

Using real-world data, it demonstrates practical skills in **Python**, **Scikit-learn**, and **data science best practices**. The insights derived can inform urban mobility strategies and support data-driven decision-making for bikeshare operations.

---
