# Employee Salary Prediction using Machine Learning

This project is part of the IBM SkillsBuild Internship Program. The goal is to predict whether an employee earns more than $50K per year based on various attributes using classification algorithms.

---

## Project Objective

To build a machine learning model that classifies an employee’s income as either:

- `>50K` (Above 50,000 USD annually)
- `<=50K` (50,000 USD or below)

using features such as:
- Age
- Education Level
- Job Role (Occupation)
- Hours worked per week
- Education Number

---

## Tools & Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn (for visualization)
- Jupyter Notebook
- Git & GitHub

---

## Dataset

- Dataset Name: `adult.csv` (UCI Adult Income Dataset)
- Rows: ~48,000 after cleaning
- Target Column: `income` (`<=50K` / `>50K`)
- Source: UCI Machine Learning Repository

---

## Workflow

1. **Data Cleaning**
   - Replaced missing values
   - Dropped invalid rows

2. **Feature Engineering**
   - Selected relevant features
   - One-hot encoded categorical variables

3. **Model Training**
   - Logistic Regression
   - Random Forest Classifier
   - GradientBoost Classifier
   - Decision Tree
   - SVM
   - KNN

4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score

---

## How to Use

1. Clone this repository
2. Open the `EmployeeSalaryPred.ipynb` notebook
3. Run all cells to:
   - Clean data
   - Train models
   - Evaluate results

---

## 📌 Author

- Samveda Boja
- Internship: IBM SkillsBuild – AI & ML Track (2025)
- Guide: M.Nanthini

---

