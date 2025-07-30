# 🩺 KNN Algorithm for Diabetes Prediction

This repository contains a machine learning project demonstrating the **K-Nearest Neighbors (KNN)** algorithm to predict the likelihood of diabetes in patients based on given medical data.

---

## 🚀 Project Overview

The **KNN algorithm** is a supervised learning technique used for classification and regression problems. In this project, we:

- Analyze a dataset containing medical parameters (like glucose level, BMI, age, etc.)
- Preprocess and scale the data for better accuracy
- Train a **KNN classifier** to predict whether a person has diabetes
- Evaluate the model using accuracy, confusion matrix, and performance metrics

---

## 📂 Dataset

- The dataset contains features like:
  - Pregnancies
  - Glucose Level
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age

- Target variable: **Outcome (1 = Diabetic, 0 = Not Diabetic)**

---

## 🛠️ Libraries Used

- **Python 3.x**
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📌 Steps in the Project

1. **Importing Libraries** – Load all required packages
2. **Data Loading & Exploration** – Understand dataset structure
3. **Data Preprocessing** – Handle missing values, scale data
4. **Splitting Dataset** – Train-Test Split
5. **Model Building** – Apply KNN classifier
6. **Choosing Optimal K** – Use different K-values to check performance
7. **Model Evaluation** – Accuracy score, confusion matrix
8. **Results & Visualization** – Graphical representation of predictions

---

## 📊 Output

- Model predicts whether a person is likely diabetic or not
- Accuracy and performance metrics shown for various **K-values**
- Visualization of decision boundaries (if 2D projection)

---

## 🏁 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/nilj07/KNN-Diabetes-Prediction.git
