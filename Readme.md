🎓 Student Performance Prediction

""Python" (https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)" (https://www.python.org/)
""Pandas" (https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)" (https://pandas.pydata.org/)
""NumPy" (https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy&logoColor=white)" (https://numpy.org/)
""Scikit-learn" (https://img.shields.io/badge/Scikit--learn-ML-F7931E?logo=scikit-learn&logoColor=white)" (https://scikit-learn.org/)
""XGBoost" (https://img.shields.io/badge/XGBoost-ML-FF6600)" (https://xgboost.readthedocs.io/)
""Matplotlib" (https://img.shields.io/badge/Matplotlib-Visualization-11557C)" (https://matplotlib.org/)
""Seaborn" (https://img.shields.io/badge/Seaborn-Visualization-4C72B0)" (https://seaborn.pydata.org/)
""Google Colab" (https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?logo=googlecolab&logoColor=white)" (https://colab.research.google.com/)

📌 Overview

An end-to-end machine learning project that predicts student exam scores using academic, behavioral, and demographic factors.

The project also analyzes important performance indicators to support the early identification of students who may require additional academic assistance.

📊 Dataset

- Records: 6,607 students
- Features: 20
- Target: Exam Score

The dataset includes factors such as:

- 📚 Study habits
- 📅 Attendance
- 👨‍👩‍👧 Parental involvement
- 📈 Previous academic performance
- 👤 Demographic factors

🔧 Project Workflow

- Data Loading & Understanding
- Data Cleaning & Preprocessing
- Missing Value Handling
- Outlier Treatment
- Categorical Encoding
- Numerical Feature Scaling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Hyperparameter Tuning
- Model Evaluation
- Feature Importance Analysis

🤖 Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Ridge Regression
- Random Forest Regressor
- XGBoost Regressor

GridSearchCV was used for hyperparameter tuning.

📈 Results

The XGBoost Regressor achieved the strongest performance in the evaluated models:

Metric| Score
R²| 0.914
MAE| 0.60
RMSE| 0.99

🔍 Key Insights

Feature importance analysis highlighted attendance, study hours, and previous scores as important predictors of exam performance.

The project also proposes an early-warning approach for students with attendance below 75%, allowing educators to consider targeted academic support.

🛠️ Technologies

Python • Pandas • NumPy • Scikit-learn • XGBoost • Matplotlib • Seaborn • Google Colab

📓 Notebook

The complete project implementation is available in:

"Student Performance Analysis.ipynb"

🚀 Future Improvements

- Deploy the model as a web application
- Add interactive student score prediction
- Implement SHAP for explainable AI
- Develop an interactive student performance dashboard

👨‍💻 Author

Muhammad Furqan
