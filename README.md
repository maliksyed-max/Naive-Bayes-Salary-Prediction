# Salary Prediction using Naïve Bayes

## 📌 About the Project

This project uses the Naïve Bayes classification algorithm to predict whether an employee's annual salary is above 50K or 50K and below based on demographic and job-related attributes.

## 🎯 Objective

- Predict employee salary categories using machine learning.
- Analyze demographic and employment-related factors.
- Apply the Naïve Bayes classification algorithm.
- Evaluate the model on unseen test data.
- Gain practical experience with classification of categorical and numerical data.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

## 📊 Dataset

The dataset contains employee information such as:

- Age
- Workclass
- Education
- Education Number
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain
- Capital Loss
- Hours per Week
- Native Country

The target variable is **Salary**, representing the employee's income category.

## 🔎 Methodology

1. Load the training and testing datasets.
2. Understand the features and target variable.
3. Preprocess categorical and numerical data.
4. Train a Naïve Bayes classifier.
5. Predict salary categories on test data.
6. Evaluate the classification performance.

## 🤖 About Naïve Bayes

Naïve Bayes is a supervised machine learning algorithm based on Bayes' theorem. It is particularly useful for classification problems and works well with high-dimensional datasets containing categorical features.

## ▶️ How to Run

Install the required libraries:

```bash
pip install pandas numpy scikit-learn openpyxl
```
Run:
```
python Naive_Bayes_salary_data.py
```

📂 Project Files
- Naive_Bayes_salary_data.py — Python implementation of the salary classification model.
- SalaryData_Train.xlsx — Training dataset.
- SalaryData_Test.xlsx — Testing dataset.
- 
📚 Key Learning
This project provided practical experience with data preprocessing, categorical data handling, supervised classification, Naïve Bayes, and model evaluation.
