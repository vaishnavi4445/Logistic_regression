# 🧠 AI & ML Internship – Task 4: Logistic Regression

This project demonstrates binary classification using Logistic Regression on the Breast Cancer Wisconsin dataset. It includes data preprocessing, model training, evaluation, ROC curve visualization, and threshold tuning.

## 📊 Dataset
- Source: `sklearn.datasets.load_breast_cancer`
- Target: `diagnosis` (Malignant = 1, Benign = 0)
- Features: 30 numeric measurements

## 🚀 How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run `logistic_regression.ipynb` in Jupyter or Colab

## 📈 Evaluation Metrics
- Confusion Matrix
- Precision, Recall, F1 Score
- ROC Curve & AUC Score

## 📌 Threshold Tuning
Tested thresholds: 0.3, 0.5, 0.7  
Observed trade-offs between precision and recall

## 📚 Requirements
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn