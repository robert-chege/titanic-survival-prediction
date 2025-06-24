# 🚢 Titanic Survival Prediction

A machine learning project to predict passenger survival on the Titanic using Logistic Regression.  
This project follows the full ML pipeline — from preprocessing and feature engineering to model training, evaluation, and Kaggle submission.

---

## 📊 Project Overview

- Predicts whether a passenger survived or not (`0` or `1`)
- Uses demographic and ticket-related features (`Age`, `Sex`, `Fare`, `Pclass`, etc.)
- Implements data cleaning, one-hot encoding, log transformation, and model evaluation with visualizations
- Final predictions are generated for Kaggle submission

---

## 🧠 Model Used

- Logistic Regression (baseline model)
- Evaluated using:
  - Classification report (precision, recall, F1-score)
  - ROC AUC Curve
  - Confusion matrix

---

## 📁 Dataset

This project uses the Titanic dataset from Kaggle:  
🔗 [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

Download `train.csv` and `test.csv` from the link above and place them in the project root.

---

## ▶️ Getting Started

1. Clone this repository or download the ZIP
2. Ensure you have Python 3 and install required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib yellowbrick

