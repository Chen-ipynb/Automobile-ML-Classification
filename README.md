# Automobile Multi-Class Classification Project 🚗

This project is a machine learning solution to a semi-supervised multi-class classification problem based on an automobile dataset. It was developed as the final project of a machine learning course.

The goal is to predict the `symboling` (risk rating) of a vehicle based on multiple features through data preprocessing, model training, performance evaluation, and result interpretation.

---

## 📂 Project Structure

```
Automobile-ML-Classification/
├── data/
│   └── auto.csv                    # Original dataset
├── notebook/
│   └── Automobile-ML-Classification.ipynb  # Main analysis code (Colab notebook)
├── docs/
│   └── Report.pdf                 # Final report (in English)
├── .gitignore
└── README.md
```

---

## 📊 Dataset Description

- **Source**: UCI Automobile Dataset  
- **Target variable**: `symboling` (a numeric scale representing risk level)  
- **Features**: 25 categorical and numeric attributes (e.g., engine-size, body-style, horsepower)

---

## 🧠 ML Workflow Overview

1. **Data Preprocessing**
   - Missing value imputation (mean/mode)
   - Outlier detection and handling
   - Encoding categorical variables (One-Hot)
   - Feature standardization

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions, outliers, and correlations
   - Class imbalance diagnosis

3. **Resampling & Semi-supervised Setup**
   - SMOTE used to balance class distribution

4. **Model Training**
   - Logistic Regression
   - Random Forest (with GridSearchCV tuning)
   - Support Vector Machine (SVM)

5. **Evaluation**
   - Classification report
   - Confusion matrix
   - Accuracy comparison

---

## ✅ Results Summary

| Model              | Accuracy (%) |
|--------------------|--------------|
| Logistic Regression | ~67%         |
| Random Forest       | **73.17%** (best tuned)
| SVM                 | ~70%         |

- Random Forest delivered the best results after hyperparameter tuning.
- SVM also performed competitively.
- Logistic Regression was slightly lower but consistent.

---

## 📄 Final Report

See full details in [`docs/Report.pdf`](docs/Report.pdf).

---

## ✨ Key Skills Applied

- Data cleaning and feature engineering
- Handling imbalanced classification
- Model comparison and tuning (GridSearchCV)
- Jupyter Notebook/Colab-based reproducible ML workflow

---

## 👩‍💻 Author

**Chen Yizhu (陈奕竹)**  
MSc in Artificial Intelligence, Eötvös Loránd University  
2025 Spring – Machine Learning Final Project

> GitHub: [@Chen-ipynb](https://github.com/Chen-ipynb)  
> Project Repository: [Automobile-ML-Classification](https://github.com/Chen-ipynb/Automobile-ML-Classification)
