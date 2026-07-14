# ❤️ Heart Disease Prediction using Machine Learning
![Python](https://img.shields.io/badge/Python-3.14-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

This project uses machine learning techniques to predict whether a patient has heart disease based on various medical attributes. Multiple classification algorithms were trained and compared to identify the best-performing model. Hyperparameter tuning and cross-validation were used to optimize and evaluate the final model.

---

## 🎯 Problem Statement

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals make timely decisions and improve patient outcomes.

The objective of this project is to build a machine learning model capable of predicting the presence of heart disease using patient medical data.

---

## 📂 Dataset

The dataset contains patient medical information such as:

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG Results (restecg)
- Maximum Heart Rate Achieved (thalach)
- Exercise-Induced Angina (exang)
- ST Depression (oldpeak)
- Slope of Peak Exercise ST Segment
- Number of Major Vessels (ca)
- Thalassemia (thal)

**Target Variable**

- 0 → No Heart Disease
- 1 → Heart Disease

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Correlation Analysis
- Model Training
- Model Comparison
- Hyperparameter Tuning
- Cross-Validation
- Model Evaluation
- Feature Importance Analysis

---

## 🤖 Machine Learning Models

The following models were trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

After evaluation, **Logistic Regression** achieved the best overall performance and was selected as the final model.

---

## 📈 Model Performance

| Metric | Score |
|---------|------:|
| Accuracy | **84.80%** |
| Precision | **82.16%** |
| Recall | **92.73%** |
| F1-Score | **87.05%** |

The high recall indicates that the model successfully identifies most patients with heart disease, making it suitable for medical screening applications where minimizing false negatives is important.

---

## 🔍 Key Learnings

Through this project I learned:

- Performing Exploratory Data Analysis (EDA)
- Training multiple machine learning models
- Comparing classification algorithms
- Hyperparameter tuning using RandomizedSearchCV and GridSearchCV
- Cross-validation techniques
- Model evaluation using Accuracy, Precision, Recall and F1-score
- Feature Importance Analysis
- Using Git and GitHub for version control

---

## 🚀 Future Improvements

- Collect larger and more diverse datasets
- Perform additional feature engineering
- Experiment with XGBoost, LightGBM and CatBoost
- Deploy the model using Flask or Streamlit
- Evaluate the model on external datasets

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/khushiraj-hash/heart-disease-project.git
```

2. Navigate to the project directory

```bash
cd heart-disease-project
```

3. Install the required libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open:

```
heart_disease_prediction.ipynb
```

---

## 📜 License

This project is intended for educational and learning purposes.
