# Heart Disease Prediction (Logistic Regression Project)

---

## 📌 Important Note

### All functions used in this project are stored in a collapsible cell, making it easier to navigate through the notebook during the presentation and providing a cleaner view of the results.

Some outputs in this project, such as charts and heatmaps, require an interactive environment (e.g., Jupyter Notebook or Google Colab) to display properly.  
To see the full results, run the notebook locally or in a supported environment.

---

## 📖 Project Overview

This logistic regression project aims to predict the likelihood of coronary heart disease (CHD) within 10 years using patient health data.  
The dataset includes various clinical features such as blood pressure, cholesterol, glucose levels, smoking habits, and medical history.  
The primary goal is to identify important risk factors, evaluate model performance using key metrics, and develop a baseline predictive model following best practices.

---

## 🔍 Key Insights

- Age is the strongest predictor of CHD, especially in older groups
- Blood pressure (sysBP) and cigarette use (cigsPerDay) also had strong positive associations with CHD.
- Total cholesterol (totChol), sex, and glucose had moderate predictive value.
- Cross-validation confirmed the model generalizes reasonably well, with consistent AUC and recall scores across folds.

---

## ⚙️ Requirements to Run This Notebook

To run this project, ensure you have the following dependencies installed:

### ✅ Python 3.7 or later

### ✅ A Python environment that supports interactive notebooks, such as:
- Jupyter Notebook  
- VS Code (with Jupyter extension)  
- PyCharm (Professional Edition with Jupyter support)  
- Google Colab  

### ✅ Libraries:
- pandas  
- numpy  
- seaborn  
- matplotlib  
- IPython.display  
- sklearn:
  - impute (SimpleImputer)
  - model_selection (train_test_split, cross_val_score)
  - preprocessing (StandardScaler)
  - linear_model (LogisticRegression)
  - metrics (accuracy_score, precision_score, recall_score, confusion_matrix, roc_auc_score, roc_curve)
- statsmodels:
  - stats.outliers_influence (variance_inflation_factor)  
  - tools (add_constant)

---

