# Employee Performance Analysis using Machine Learning

## Project Overview

This project focuses on analyzing employee performance data of INX Future Inc. using Machine Learning and HR Analytics techniques. The objective is to identify the major factors affecting employee performance and build predictive models that can help organizations improve workforce productivity and decision-making.

The project includes:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Machine Learning Model Building
- Hyperparameter Tuning
- Feature Importance Analysis
- Model Saving using Pickle

---

# Business Problem

INX Future Inc. observed a decline in employee performance and customer satisfaction. The company wants to identify:
- Department-wise employee performance
- Key factors affecting employee performance
- Predictive models for employee performance rating
- Business recommendations for workforce improvement

---

# Objectives

- Analyze employee performance trends
- Identify top features affecting performance
- Build machine learning models for prediction
- Compare model performance
- Generate business insights and recommendations
- Save final trained model for future deployment

---

# Dataset Information

The dataset contains employee-related information such as:
- Age
- Gender
- Department
- Job Role
- Work Experience
- Salary Hike
- Job Satisfaction
- Work-Life Balance
- Environment Satisfaction
- Attrition
- Performance Rating

Target Variable:
- `PerformanceRating`

---

# Technologies Used

## Programming Language
- Python

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Pickle

---

# Project Workflow

1. Business Problem Understanding
2. Data Loading
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Data Preprocessing
7. Model Building
8. Model Evaluation
9. Hyperparameter Tuning
10. Feature Importance Analysis
11. Final Recommendations
12. Model Saving

---

# Exploratory Data Analysis

The following analyses were performed:
- Department-wise Performance Analysis
- Job Satisfaction Analysis
- Work-Life Balance Analysis
- Environment Satisfaction Analysis
- Overtime Analysis
- Attrition Analysis
- Correlation Analysis

---

# Feature Engineering

Additional features created:
- AgeGroup
- ExperienceLevel
- SalaryHikeCategory

These engineered features improved business interpretation and model understanding.

---

# Machine Learning Models Used

The following models were trained and evaluated:

| Model | Accuracy |
|------|------|
| Logistic Regression | 84.16% |
| Decision Tree | 88.75% |
| Random Forest | 94.58% |
| XGBoost | 95.41% |

---

# Best Model

## XGBoost Classifier

XGBoost achieved the highest prediction accuracy of approximately **95.41%**, making it the best-performing model for employee performance prediction.

---

# Feature Importance

Top factors affecting employee performance:
- Employee Environment Satisfaction
- Salary Hike Percentage
- Work-Life Balance
- Work Experience
- Job Satisfaction

---

# Business Insights

- Employee performance varies across departments.
- Employees with better work-life balance tend to perform better.
- Higher environment satisfaction positively impacts performance.
- Salary hike percentage is strongly associated with employee productivity.
- Ensemble models outperform traditional machine learning models for this dataset.

---

# Business Recommendations

- Improve employee engagement and workplace environment.
- Strengthen work-life balance initiatives.
- Implement performance-based reward systems.
- Conduct targeted employee training programs.
- Use predictive analytics in recruitment and workforce planning.

---

# Model Saving

The final trained XGBoost model and scaler were saved using Pickle files:
- `employee_performance_model.pkl`
- `scaler.pkl`

---

# Project Structure

```bash
Employee-Performance-Analysis/
│
├── Employee_Performance_Analysis.ipynb
├── employee_performance_model.pkl
├── scaler.pkl
├── README.md
├── requirements.txt
├── .gitignore
└── dataset/
    └── INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls
```

---

# Future Scope

- Deploy model using Streamlit or Flask
- Build HR Analytics Dashboard using Power BI
- Integrate real-time prediction system
- Use larger enterprise HR datasets
- Develop automated employee monitoring systems

---

# Author

## Heet Vadadoriya

Aspiring Data Scientist | Machine Learning Enthusiast | HR Analytics Project
