# 🎓 Student Performance Prediction

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Scientific_Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine_Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Machine_Learning-FF6600?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0?style=for-the-badge)
![Google Colab](https://img.shields.io/badge/Google_Colab-Notebook-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

## 📌 Overview

An end-to-end machine learning project that predicts student exam scores using academic, behavioral, and demographic factors.

## 📊 Dataset

- **6,607** student records
- **20** features
- Target: **Exam Score**

Key features include attendance, study habits, parental involvement, and previous academic performance.

## 🔧 Workflow

1. Data Loading & Understanding
2. Data Preprocessing
3. Missing Value Handling
4. Outlier Treatment
5. Categorical Encoding
6. Feature Scaling
7. Exploratory Data Analysis (EDA)
8. Feature Engineering
9. Model Training
10. Hyperparameter Tuning
11. Model Evaluation
12. Feature Importance Analysis

## 🤖 Machine Learning Models

- Linear Regression
- Ridge Regression
- Random Forest Regressor
- XGBoost Regressor

**GridSearchCV** was used for hyperparameter tuning.

## 📈 Results

| Model | R² | MAE | RMSE |
|---|---:|---:|---:|
| XGBoost | **0.914** | **0.60** | **0.99** |

## 🔍 Key Insights

Feature importance analysis identified **attendance, study hours, and previous scores** as important predictors of academic performance.

An early-warning approach was proposed to flag students with **attendance below 75%** for potential academic support.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Google Colab

## 📓 Notebook

The complete implementation is available in:

`Student Performance Analysis.ipynb`

## 🚀 Future Improvements

- Deploy the model as a web application
- Add interactive student score prediction
- Implement SHAP for explainable AI
- Develop an interactive student performance dashboard

## 👨‍💻 Author

**Muhammad Furqan**
