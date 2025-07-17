# 🩺 Diabetes Prediction App

A machine learning web application built with **Python**, **Scikit-learn**, and **Gradio** to predict whether a person is diabetic based on their health features.

## 📊 Dataset

The dataset used is the **"Diabetes Prediction Dataset"** sourced from Google Drive, containing 10,000 entries and the following features:

- `gender` (Male/Female)
- `age`
- `hypertension` (0 = No, 1 = Yes)
- `heart_disease` (0 = No, 1 = Yes)
- `bmi`
- `HbA1c_level`
- `blood_glucose_level`
- `diabetes` (Target variable: 0 = Non-Diabetic, 1 = Diabetic)

---

## 🔍 Features

- Preprocessing with **LabelEncoder** and **StandardScaler**
- Model training using:
  - Logistic Regression
  - Random Forest Classifier
  - Support Vector Classifier (SVC)
- Accuracy comparison between models
- Real-time prediction interface using **Gradio**
- Input parameters:
  - Gender
  - Age
  - Hypertension
  - Heart Disease
  - BMI
  - HbA1c Level
  - Blood Glucose Level

---

## 🚀 How It Works

1. Dataset is loaded from Google Drive using Google Colab.
2. Gender is encoded numerically.
3. Features are standardized using `StandardScaler`.
4. Dataset is split into training and testing sets.
5. Three ML models are trained and evaluated.
6. The best-performing model is selected based on accuracy.
7. A **Gradio interface** is launched to take user inputs and predict the outcome.

---

## 🧠 Model Performance

The app compares three models and displays their accuracies. The best model is automatically selected for predictions.

Example Output:
Model Accuracies:
Logistic Regression: 0.84
Random Forest: 0.88
SVM: 0.86

Best model: Random Forest with accuracy 0.88
