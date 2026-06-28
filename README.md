# Employee Attrition Prediction using Machine Learning

## 📌 Project Overview

Employee attrition is a major challenge for organizations, leading to increased recruitment costs, productivity loss, and employee replacement expenses. This project uses Machine Learning to predict whether an employee is likely to leave the company based on HR-related factors such as job role, monthly income, overtime, business travel, work-life balance, and years at the company.

The project includes data preprocessing, exploratory data analysis (EDA), model building, evaluation, and business recommendations that can help HR teams make informed retention decisions.

---

## 🎯 Objectives

- Analyze employee data to identify factors contributing to attrition.
- Perform data cleaning and preprocessing.
- Explore employee attrition patterns using EDA.
- Build and compare multiple Machine Learning models.
- Identify the best-performing model.
- Provide actionable HR recommendations based on the analysis.

---

## 📂 Dataset

**Dataset:** IBM HR Analytics Employee Attrition Dataset

- Total Records: **1,470**
- Source: Kaggle
- File Used: `WA_Fn-UseC_-HR-Employee-Attrition.csv`

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Employee Attrition Rate
- Department-wise Attrition Analysis
- Job Role-wise Attrition Analysis
- Monthly Income vs Attrition
- Work-Life Balance vs Attrition
- Years at Company vs Attrition

---

## 🤖 Machine Learning Models

Three classification models were trained and compared:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Class imbalance was handled using:

- `class_weight='balanced'`

---

## 📈 Model Evaluation

Models were evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

### 🏆 Best Performing Model

**Logistic Regression**

The Logistic Regression model achieved the best overall performance for this dataset and was selected as the final prediction model.

---

## 🔍 Top Factors Influencing Employee Attrition

Based on the Logistic Regression model, the most influential factors were:

- Job Role (Laboratory Technician)
- OverTime
- Business Travel (Travel Frequently)
- Job Level
- Total Working Years
- Sales Representative
- Business Travel (Travel Rarely)
- Education Field (Life Sciences)
- Years Since Last Promotion
- Department (Sales)

---

## 📊 Key Business Insights

- The Sales department recorded the highest employee attrition rate (20.63%).
- Sales Representatives had the highest attrition rate (39.76%) among all job roles.
- Employees with lower monthly income were generally more likely to leave the organization.
- Overtime and frequent business travel were identified as strong indicators of employee attrition.
- Employee attrition is influenced by multiple workplace factors rather than salary alone.

---

## 💡 HR Recommendations

- Conduct regular retention discussions with employees in the Sales department, especially Sales Representatives.
- Reduce excessive overtime and improve work-life balance initiatives.
- Review business travel requirements for frequently traveling employees.
- Provide career development opportunities and recognition programs for high-risk employee groups.

---

## 📁 Project Structure

```
Employee-Attrition-Prediction/
│
├── analysis.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md
├── charts/
│   ├── department_attrition.png
│   ├── jobrole_attrition.png
│   ├── income_boxplot.png
│   ├── confusion_heatmap.png
│   ├── feature_importance.png
│   └── roc_curve.png
│
└── HR_Attrition_Summary.docx
```

---


## 📷 Project Output

The project generates:

- Cleaned dataset
- Exploratory Data Analysis
- Machine Learning models
- Model comparison
- Confusion Matrix
- ROC Curve
- Feature Importance Chart
- HR Business Recommendations

---

## 📌 Future Improvements

- Hyperparameter tuning
- Cross-validation
- SHAP explainability
- XGBoost and LightGBM implementation
- Interactive HR dashboard using Streamlit or Power BI

---

## 👩‍💻 Author

**Tanishka Gandhi**

Computer Engineering Student

Passionate about Data Analytics, Machine Learning, and Business Intelligence.

---

## 🏅 Internship Project

This project was completed as part of the **XYlofy AI Machine Learning Internship** under the Week 2 assignment, focusing on solving a real-world HR analytics problem using Machine Learning techniques.
