# Heart Disease Classification Using Machine Learning

Machine learning classification project analyzing heart disease risk factors using exploratory data analysis, preprocessing, and logistic regression planning.
 ## Main Notebook

[Open Notebook](./Hands_on_Exercise_1_fin.ipynb)
---

## Project Overview

This project develops a reusable machine learning workflow template for binary classification problems using a heart disease dataset.

The notebook demonstrates the complete machine learning pipeline from problem definition and exploratory data analysis (EDA) to preprocessing, feature engineering, model selection, and evaluation planning.

The primary objective is to predict whether a patient has heart disease using demographic and clinical variables.

---

## Business / Healthcare Motivation

Heart disease is one of the leading causes of death worldwide. Early identification of high-risk patients can improve clinical decision-making, preventive care, and patient outcomes.

Classification models in healthcare can support:
- Early disease detection
- Risk screening
- Clinical decision support
- Preventive intervention strategies

This project demonstrates how machine learning workflows can be applied in healthcare analytics.

---

## Dataset Information

Dataset: Heart Disease Dataset

### Target Variable
- `heart_disease`
  - Binary classification target
  - 0 = No heart disease
  - 1 = Heart disease present

### Predictor Variables
- age
- sex
- max_heart_rate
- angina_level
- non_anginal_pain

---

## Machine Learning Workflow

The notebook follows a structured machine learning workflow:

1. Problem Definition
2. Data Preparation
3. Exploratory Data Analysis (EDA)
4. Missing Value Handling
5. Data Cleaning
6. Feature Engineering
7. Categorical Encoding
8. Correlation Analysis
9. Model Selection
10. Evaluation Planning

---

## Data Cleaning & Preprocessing

Several preprocessing steps were applied to improve data quality and prepare the dataset for machine learning.

### Missing Value Handling
Missing values were identified and handled using:
- Median imputation for numerical variables
- Mode imputation for categorical variables

### Data Cleaning
- Negative heart rate values were identified and removed
- Duplicate records were removed

### Feature Engineering
Categorical variables were converted into numerical format using one-hot encoding.

Encoded variables included:
- sex
- angina_level

---

## Exploratory Data Analysis

The project includes:
- Histograms
- Boxplots
- Correlation matrix analysis
- Target distribution analysis
- Predictor vs target comparisons

### Key Findings
- The dataset is relatively balanced
- Heart disease appears associated with:
  - lower maximum heart rate
  - severe angina
  - male patients
- Age distributions suggest increased disease prevalence in older individuals

---

## Model Selection

### Logistic Regression

Logistic Regression was selected as the baseline model because:
- the target variable is binary,
- the model is interpretable,
- and it is widely used in healthcare analytics.

The notebook focuses on workflow structure and evaluation planning rather than complex modeling.

---

## Planned Evaluation Metrics

The project discusses several evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics help evaluate classification performance and generalization ability.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Main Notebook

[Open Notebook](./heart_disease_classification.ipynb)

---

## Author

Tanishtha Papadkar
