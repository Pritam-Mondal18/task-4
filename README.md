# 🤖 Logistic Regression Binary Classification

## 📌 Project Overview

This project implements a **binary classification model using Logistic Regression** as part of an AI & ML Internship task.

The goal is to build a classifier, evaluate its performance using multiple metrics, tune the classification threshold, and understand how the sigmoid function converts predictions into probabilities.

---

## 🎯 Objectives

1. Choose a binary classification dataset  
2. Perform train/test split and standardize features  
3. Train a Logistic Regression model  
4. Evaluate model using confusion matrix, precision, recall, and ROC-AUC  
5. Tune classification threshold and understand sigmoid function  

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Dataset

- Dataset used: Binary classification dataset (`data.csv`)
- Target variable: `diagnosis`
- Features: All remaining columns

---

## 🔎 Steps Performed

### 1️⃣ Dataset Selection
- Loaded dataset using Pandas
- Separated features and target variable

---

### 2️⃣ Train/Test Split & Standardization
- Split data into training and testing sets (80/20)
- Applied feature scaling using StandardScaler

---

### 3️⃣ Logistic Regression Model Training
- Trained Logistic Regression classifier on scaled training data
- Model learns probability of belonging to class 1

---

### 4️⃣ Model Evaluation

#### Confusion Matrix
Shows:
- True Positives
- True Negatives
- False Positives
- False Negatives

#### Precision
Measures how many predicted positives are actually correct.

#### Recall
Measures how many actual positives were correctly identified.

#### ROC-AUC Score
Measures model’s ability to distinguish between classes.

#### ROC Curve
Visual representation of model performance at different thresholds.

---

### 5️⃣ Threshold Tuning

Default classification threshold = 0.5  

Changing threshold:
- Lower threshold → Higher recall
- Higher threshold → Higher precision

Threshold tuning helps balance false positives and false negatives.

---

## 📈 Sigmoid Function

Logistic Regression uses the sigmoid function to convert predictions into probabilities.

Formula:
σ(z) = 1 / (1 + e^-z)


Properties:
- Output range: 0 to 1
- Converts linear output into probability
- Used for classification decision making

---

## 📊 Key Learnings

- Logistic Regression is used for binary classification.
- Feature scaling improves model performance.
- Precision and recall measure different aspects of accuracy.
- ROC-AUC evaluates model discrimination ability.
- Threshold tuning changes model sensitivity.
- Sigmoid function maps predictions to probabilities.
