# 🧠 Data Science & Machine Learning Projects

This repository contains a collection of projects related to Data Science and Machine Learning, including classification, regression, and real-world data processing tasks.

## 📁 Project Structure

### 🔷 `classification_model/`
This folder contains notebooks demonstrating classification techniques on various datasets using popular algorithms:

- **`KNN.ipynb`**: Apply K-Nearest Neighbors algorithm with hyperparameter tuning using cross-validation.
- **`DecisionTree.ipynb`**: Decision Tree classifier with visualization and explanation of decision rules.
- **`RandomForest.ipynb`**: Use Random Forest ensemble method to improve accuracy and avoid overfitting.
- **`SVM.ipynb`**: Classification with Support Vector Machines, includes kernel trick and margin analysis.

👉 All notebooks include:
- Data preprocessing
- Feature engineering
- Model training & evaluation
- Inline comments and visualizations for better understanding

### 🔷 `regression_model/`
Focuses on predicting continuous values using regression methods:

- **`LinearRegression.ipynb`**: Simple and multiple linear regression models, includes residual plots and performance metrics.
- **`PolynomialRegression.ipynb`**: Fit non-linear patterns using polynomial terms.
- **`RidgeLasso.ipynb`**: Use Ridge and Lasso regularization to reduce overfitting and perform feature selection.

👉 Includes in-depth explanation of evaluation metrics like MAE, MSE, RMSE, and R².

### 🔷 `job_classification/`
This is a real-world NLP classification project to predict job categories from job descriptions.

- Load and clean a dataset containing job listings.
- Perform text preprocessing (tokenization, stopword removal, TF-IDF vectorization).
- Train multiple classification models: Naive Bayes, Logistic Regression, and SVM.
- Evaluate performance using accuracy, confusion matrix, and classification report.

### 🔷 `datasets/`
Contains datasets used by other projects:

## 🛠️ Installation Guide

### 1. Clone the repository

```bash
git clone https://github.com/tuyenmon2201/Data-Science-ML.git
cd Data-Science-ML
```

### 2. (Optional) Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

> 💡 **Note**: If `requirements.txt` is missing, manually install commonly used libraries like `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, etc.

## 🚀 How to Run

- Open `.ipynb` files using **Jupyter Notebook** or **Google Colab**.
- Each notebook includes:
  - Data preprocessing  
  - Model building  
  - Evaluation steps

## 📌 Objectives

- Apply data science knowledge to real-world problems.
- Improve data processing and model evaluation skills.
- Build a personal portfolio in the field of Data Science and Machine Learning.