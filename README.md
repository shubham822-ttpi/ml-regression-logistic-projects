# 💻 Machine Learning Projects: Regression & Classification

This repository contains complete implementations of *Linear Regression, **Ridge Regression, and **Logistic Regression* using real-world datasets in Python with scikit-learn. The notebook demonstrates full ML workflows including data preprocessing, model training, hyperparameter tuning, evaluation, and visualization.

---

## 📁 Contents

### 🔹 1. *Linear Regression* – Boston Housing Dataset
- Predicts median house prices (medv)
- Scaled features using StandardScaler
- Evaluated with *RMSE* and *R² Score*
- Visualized actual vs predicted distribution using Seaborn

---

### 🔹 2. *Ridge Regression* – Boston Housing Dataset
- Added *L2 regularization* to control overfitting
- Tuned alpha using GridSearchCV
- Best alpha = 10 with improved error metrics
- Compared prediction distribution with actual prices

---

### 🔹 3. *Logistic Regression* – Heart Disease Dataset
- Binary classification: Heart Disease Presence (1) or Absence (0)
- Preprocessed labels using .map() function
- Tuned hyperparameters (C, penalty, max_iter) with GridSearchCV
- Achieved *92% accuracy*
- Evaluated with:
  - *Classification Report*
  - *Confusion Matrix Heatmap*
  - *Precision, Recall, F1-score*

---

## 🧪 Techniques Used
- Train/test split
- Feature scaling (StandardScaler)
- Regularization (L1, L2)
- Hyperparameter tuning (GridSearchCV)
- Model evaluation metrics (RMSE, R², Accuracy, F1-score)
- Data visualization (Seaborn, Matplotlib)

---

## 🛠 Tools & Libraries
- Python
- Jupyter Notebook
- scikit-learn
- pandas
- numpy
- seaborn
- matplotlib

---

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/shubham822-ttpi/ml-regression-logistic-projects.git
   cd ml-regression-logistic-projects

