# ❤️ Heart Disease Prediction using Machine Learning

## Overview

This project predicts the presence of heart disease using machine learning techniques based on patient clinical data. The model is trained and evaluated using Python and Scikit-learn.

---

## 📂 Dataset

- **File:** `heart_disease_data.csv`

---

## 📊 Dataset Description

The dataset contains clinical parameters used to predict the presence of heart disease.  
All personal identifiers such as names and social security numbers were removed and replaced with dummy values to ensure privacy.

---

## 🔢 Features

- **age:** Age of the patient (in years)

- **sex:** Gender of the patient (1 = male, 0 = female)

- **chest pain type (cp):** Chest pain type (4 values)

- **resting blood pressure (trestbps):** Resting blood pressure (in mm Hg)

- **serum cholesterol (chol):** Serum cholesterol level in mg/dl

- **fasting blood sugar (fbs):** Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)

- **resting electrocardiographic results (restecg):** Values (0, 1, 2)

- **maximum heart rate achieved (thalach):** Maximum heart rate achieved

- **exercise induced angina (exang):** Exercise-induced angina (1 = yes, 0 = no)

- **oldpeak:** ST depression induced by exercise relative to rest

- **slope:** Slope of the peak exercise ST segment

- **ca:** Number of major vessels (0–3) colored by fluoroscopy

- **thal:** Thalassemia  
  - 0 = Normal  
  - 1 = Fixed defect  
  - 2 = Reversible defect  

- **target:**  
  - 1 = Presence of heart disease  
  - 0 = Absence of heart disease  

---

## 🤖 Model Used

- Logistic Regression

---

## 📈 Results

- Accuracy achieved: **~85%**
- Evaluation performed using:
  - Confusion Matrix  
  - Classification Report  

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Google Colab  

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/binaryanushka/heart-disease-prediction.git
