# Breast Cancer Prediction Model 🩺🎗️

This repository contains a **Breast Cancer Prediction Model** implemented using the **Logistic Regression** algorithm from the **scikit-learn** library. The model is trained on a real dataset obtained from the University of California Machine Learning Repository. The purpose of this project is to provide an accurate and efficient way to predict the likelihood of breast cancer based on diagnostic features.

---

## 📁 Dataset Information

- **Source**: [University of California Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
- **Dataset Name**: Breast Cancer Wisconsin (Diagnostic)
- **Features**: The dataset includes 30 numerical features such as mean radius, texture, perimeter, area, smoothness, and others derived from breast mass cell nuclei.
- **Target**:
  - `4`: Malignant
  - `2`: Benign

---

## 📊 Project Objective

To develop a machine learning model that predicts whether a breast mass is **malignant** or **benign** using logistic regression. The aim is to aid in early diagnosis and improve decision-making for healthcare professionals.

---

## 🛠️ Tools & Technologies

- **Python 3.8+**
- **scikit-learn**
- **pandas**
- **NumPy**
- **matplotlib**

---

## Model Pipeline

**1. Data Preprocessing** : 
  - Handling missing values (if any).
  - Standardizing numerical features for better model performance.
                           
**2. Model Training** : Logistic Regression model trained using a 80-20 train-test split.

**3. Evaluation** : Performance based on  ***k-Fold Cross Validation*** 

---

## 📈 Results

The model achieves the following performance on the test dataset:

- **Accuracy**: ~97%
- **Standard Deviation**: 1.97% 

---
## Contact
Email: theindianboy555@gmail.com
