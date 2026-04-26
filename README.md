# Cardio_trained_Model
# Cardiovascular Disease Prediction using Machine Learning

## 📌 Project Overview

This project presents an exploratory data analysis (EDA) and machine learning-based prediction of cardiovascular disease using patient medical attributes. The objective is to analyze health-related factors and evaluate multiple classification models for predicting the presence of cardiovascular disease.

The dataset contains demographic, clinical, and lifestyle attributes of patients.

---

## 📊 Dataset Description

The dataset (`cardio_train.csv`) contains 70,000 patient records and 13 features:

| Feature | Description |
|----------|-------------|
| age | Age in days |
| gender | Gender (1: Female, 2: Male) |
| height | Height in cm |
| weight | Weight in kg |
| ap_hi | Systolic blood pressure |
| ap_lo | Diastolic blood pressure |
| cholesterol | Cholesterol level (1: Normal, 2: Above Normal, 3: Well Above Normal) |
| gluc | Glucose level (1: Normal, 2: Above Normal, 3: Well Above Normal) |
| smoke | Smoking (0: No, 1: Yes) |
| alco | Alcohol intake (0: No, 1: Yes) |
| active | Physical activity (0: No, 1: Yes) |
| cardio | Target variable (0: No Disease, 1: Disease) |

---

## 🔎 Exploratory Data Analysis

The following analyses were performed:

- Data cleaning and preprocessing
- Conversion of age from days to years
- Target variable distribution analysis
- Age distribution visualization
- Blood pressure distribution
- Cholesterol vs Cardiovascular Disease relationship
- Correlation matrix heatmap

---

## 🤖 Machine Learning Models Implemented

The following classification algorithms were evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## ⚙️ Methodology

1. Data preprocessing
2. Feature selection
3. Train-test split (80%-20%)
4. Feature scaling using StandardScaler
5. Model training
6. Performance evaluation using Accuracy Score

---

## 📈 Results

Model performance was evaluated using accuracy metrics.  
Random Forest and Logistic Regression showed competitive performance compared to other models.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone[ https://github.com/Ajju1202/cardio-trained_Model.git
