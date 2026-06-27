# Employee Attrition Prediction using Machine Learning

## Overview

Employee attrition is a major challenge for organizations because replacing experienced employees increases recruitment costs, training expenses, and productivity loss. This project builds a Machine Learning model to predict whether an employee is likely to leave the company based on HR-related features such as job satisfaction, monthly income, work-life balance, years at the company, overtime, and job role.

The project follows a complete end-to-end Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), model building, evaluation, and business recommendations.

---

## Objectives

* Predict employee attrition using Machine Learning.
* Perform data cleaning and preprocessing.
* Analyze factors that influence employee turnover.
* Compare multiple classification models.
* Identify the most important features affecting employee attrition.
* Generate business insights and HR recommendations.

---

## Dataset

**Dataset:** IBM HR Analytics Employee Attrition Dataset

* Total Records: 1,470
* Target Variable: `Attrition` (Yes / No)

The dataset contains employee information such as:

* Age
* Department
* Job Role
* Monthly Income
* Job Satisfaction
* Work-Life Balance
* Years at Company
* Overtime
* Performance Rating
* Education
* Marital Status
* and several other HR-related attributes.

---

## Project Workflow

### 1. Data Exploration

* Loaded the dataset using Pandas
* Examined dataset shape and data types
* Identified numerical and categorical features
* Calculated overall attrition rate

### 2. Data Preprocessing

* Checked for missing values
* Removed irrelevant and constant columns
* Encoded categorical variables using One-Hot Encoding
* Converted the target variable into binary format
* Standardized numerical features using StandardScaler

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

* Attrition by Department
* Attrition by Job Role
* Monthly Income vs Attrition
* Work-Life Balance vs Attrition
* Years at Company vs Attrition

---

## Machine Learning Models

The following classification models were trained and compared:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

---

## Model Evaluation

Models were evaluated using:

* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

The best-performing model was selected based on these evaluation metrics.

---

## Visualizations

The project includes the following visualizations:

* Attrition Rate by Department
* Attrition Rate by Job Role
* Monthly Income vs Attrition (Box Plot)
* Work-Life Balance vs Attrition
* Years at Company vs Attrition
* Confusion Matrix
* Top 10 Feature Importance
* ROC Curve Comparison

---

## Business Insights

The analysis provides actionable business insights such as:

* Overall employee attrition trends.
* Departments with the highest employee turnover.
* Job roles that require greater retention efforts.
* The relationship between salary, work-life balance, and employee attrition.
* Employee tenure patterns associated with higher resignation rates.

---

## HR Recommendations

Based on the analysis, the project recommends:

* Prioritizing retention efforts for high-risk departments and job roles.
* Providing mentoring, career development opportunities, and regular feedback for employees during their early years in the company.
* Improving work-life balance and employee engagement initiatives.
* Using predictive analytics to identify employees at risk of leaving before attrition occurs.

---

## Project Structure

```
EmployeeAttritionPrediction/
│
├── analysis.ipynb
├── HR_Attrition.csv
├── README.md
├── summary.pdf
└── charts/
    ├── attrition_department.png
    ├── attrition_jobrole.png
    ├── income_boxplot.png
    ├── confusion_matrix.png
    ├── feature_importance.png
    └── roc_curve.png
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Key Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing and feature engineering
* Exploratory Data Analysis (EDA)
* Handling categorical variables
* Building classification models
* Model comparison and evaluation
* Feature importance analysis
* Translating Machine Learning results into business recommendations

---

## Future Improvements

* Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
* Cross-validation for improved model reliability
* Experimenting with advanced boosting algorithms such as XGBoost or LightGBM
* Building a web application using Streamlit or Flask for real-time attrition prediction

---

## Author

**Amit Kumar Singh**

Aspiring AI / Machine Learning Engineer

GitHub: https://github.com/Amit905460
