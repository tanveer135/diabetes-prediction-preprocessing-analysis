# Diabetes Prediction Using Machine Learning

## 📌 Project Overview
This project analyzes the impact of data preprocessing techniques and model selection on diabetes prediction using structured clinical data.

The goal is not only to build predictive models, but to understand how preprocessing decisions influence model performance.

---

## 📊 Dataset
- Source: Kaggle (Ziya07, 2023)
- Size: 100,000 records
- Features include:
  - Age, BMI, HbA1c level, blood glucose
  - Hypertension, heart disease
  - Gender, smoking history
- Target:
  - Diabetes (0 = No, 1 = Yes)

---

## 🔍 Exploratory Data Analysis
Key insights:
- Dataset is highly imbalanced (~91.5% non-diabetic)
- HbA1c and blood glucose are strongest predictors
- BMI contains outliers
- No missing values

---

## ⚙️ Preprocessing
- Removed irrelevant features (clinical_notes, race, location)
- One-hot encoding for categorical variables
- Outlier handling using IQR (BMI capping)
- Stratified train-test split
- SMOTE applied to handle class imbalance

---

## 🤖 Models Used
- Random Forest
- Logistic Regression
- Gradient Boosting

---

## 📈 Results Summary
- Random Forest achieved highest accuracy (~97%)
- Logistic Regression achieved highest recall
- Gradient Boosting achieved best overall performance (ROC-AUC ≈ 0.97)

👉 Gradient Boosting was selected as the best model due to balanced performance.

---

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

## 📁 Project Structure
notebooks/ → analysis & modeling


---

## 🚀 Key Contribution
This project demonstrates that preprocessing techniques, especially class balancing (SMOTE), significantly impact model performance in healthcare prediction tasks.

---

## 📚 References
- Sisodia & Sisodia (2018)
- Zou et al. (2018)
- Brateanu et al. (2017)

---

## ⚠️ Note
Dataset is publicly available on Kaggle and used for educational purposes.

---

## 👤 Author
Tanveer Hussan
