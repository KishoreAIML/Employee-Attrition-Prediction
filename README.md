# Employee Attrition Prediction

## Project Overview

Employee attrition (employee turnover) is a major challenge for organizations. High attrition leads to:

* Increased recruitment and training costs
* Loss of experienced employees
* Reduced productivity
* Lower team morale

This project builds a **Machine Learning model to predict employee attrition** using historical HR data. The model identifies employees who are most likely to leave the company, allowing organizations to take **proactive retention measures**.

---

## Problem Statement

A company is experiencing **high employee turnover**, leading to increased recruitment costs and a negative impact on productivity.

The goal of this project is to build a **predictive model that identifies employees at risk of leaving the organization**, enabling HR teams to implement effective **employee retention strategies**.

---

## Project Objectives

1. Develop a **Machine Learning model** to predict employee attrition.
2. Identify **key factors contributing to employee turnover**.
3. Provide **actionable recommendations** to reduce attrition.

---

## Project Goals

* Achieve a **classification accuracy of at least 85%**
* Identify the **top 3 factors influencing employee attrition**
* Provide **data-driven retention strategies**

---

## Dataset Description

The dataset contains historical employee information including:

* Demographics
* Job role
* Salary details
* Performance metrics
* Work environment factors
* Employee satisfaction indicators

### Example Features

| Feature         | Description                     |
| --------------- | ------------------------------- |
| Age             | Age of employee                 |
| JobRole         | Employee's job role             |
| MonthlyIncome   | Employee salary                 |
| JobSatisfaction | Satisfaction level              |
| WorkLifeBalance | Work-life balance rating        |
| YearsAtCompany  | Total years in the company      |
| OverTime        | Whether employee works overtime |
| Attrition       | Target variable (Yes / No)      |

---

## Project Workflow

The project follows a **standard machine learning pipeline**.

### 1 Data Analysis

* Understanding dataset structure
* Checking missing values
* Statistical summaries
* Exploratory Data Analysis (EDA)

### 2 Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Feature scaling
* Removing duplicates

### 3 Feature Engineering

Creating new features related to:

* Employee satisfaction
* Work engagement
* Experience level
* Compensation balance

---

### 4 Model Development

We implemented classification models to predict attrition:

* Logistic Regression
* Random Forest
* Decision Tree
* Gradient Boosting (optional)

---

### 5 Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Curve

Target performance:

**≥ 85% Accuracy**

---

### 6 Model Interpretation

To understand **why employees leave**, we analyzed:

* Feature importance
* Correlation analysis
* Model explainability

Key factors identified include:

1. Overtime work
2. Job satisfaction
3. Monthly income

---

## Project Architecture

```
Employee Attrition Prediction
│
├── data
│   └── employee_dataset.csv
│
├── notebooks
│   └── EDA_and_Modeling.ipynb
│
├── src
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   └── evaluate_model.py
│
├── models
│   └── attrition_model.pkl
│
├── requirements.txt
└── README.md
```

---

## Tech Stack

Programming Language

* Python

Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

Optional Tools

* Jupyter Notebook
* MLflow (for experiment tracking)
* Docker (for containerization)

---

## Installation

Clone the repository

```bash
git clone [https://github.com/yourusername/employee-attrition-prediction.git](https://github.com/KishoreAIML/Employee-Attrition-Prediction.git)
```

Navigate to the project folder

```bash
cd employee-attrition-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

Run the notebook

```bash
jupyter notebook
```

Or train the model using Python script

```bash
python src/train_model.py
```

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 84%      |
| Decision Tree       | 82%      |
| Random Forest       | **88%**  |

Best Model: **Random Forest Classifier**

---

## Key Insights

Important factors affecting employee attrition:

1. **Overtime workload**
2. **Low job satisfaction**
3. **Low monthly income**
4. **Poor work-life balance**

Employees working **frequent overtime with low satisfaction** were more likely to leave.

---

## Business Recommendations

Based on model insights, the following retention strategies are recommended:

### Improve Work-Life Balance

* Reduce excessive overtime
* Implement flexible working policies

### Increase Employee Satisfaction

* Conduct regular feedback sessions
* Provide career development opportunities

### Competitive Compensation

* Review salary structures
* Introduce performance-based incentives

### Employee Engagement Programs

* Recognition programs
* Skill development initiatives
* Mentorship programs

---

## Future Improvements

Possible improvements for this project:

* Use **Deep Learning models**
* Implement **SHAP for model explainability**
* Deploy model using **FastAPI**
* Track experiments using **MLflow**
* Deploy using **Docker + Kubernetes**

---

## Real World Applications

This project can help organizations:

* Reduce employee turnover
* Improve HR decision-making
* Identify high-risk employees early
* Save recruitment and training costs

---

## Author

**Kishore Tirumani**

Aspiring **AI / Machine Learning Engineer**

Skills:

* Machine Learning
* Deep Learning
* NLP
* Model Deployment
* AWS
* Kubernetes
