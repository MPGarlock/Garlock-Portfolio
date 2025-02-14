🔍 Employee Churn Prediction

📝 Project Overview

Employee churn (attrition) is a critical challenge for businesses, affecting productivity, morale, and hiring costs. This project applies predictive analytics to identify employees at risk of leaving, enabling companies to take proactive retention measures.

📌 Key Use Case:

Help HR departments forecast employee turnover.
Identify key drivers of attrition to improve retention strategies.
Reduce hiring and training costs by minimizing churn.
🎯 Objective

Analyze employee data to uncover patterns in churn behavior.
Build machine learning models to predict whether an employee will leave.
Provide data-driven insights for improving workforce retention.
📂 Dataset

The dataset contains key employee attributes, including:

Demographics: Age, gender, marital status
Job Factors: Job role, department, years at company, promotions
Salary & Benefits: Monthly income, stock options, compensation level
Work-Life Balance: Overtime hours, job satisfaction, workload
Target Variable: Attrition (Yes/No)
📌 Data Source: HR Analytics datasets from IBM or Kaggle

🛠️ Predictive Analytics & Machine Learning Approach

1️⃣ Data Preprocessing & Feature Engineering
🔹 Handling missing values (SimpleImputer)
🔹 Encoding categorical variables (OneHotEncoder, LabelEncoder)
🔹 Feature scaling (StandardScaler)
🔹 Class balancing using SMOTE to address imbalance in attrition data

2️⃣ Exploratory Data Analysis (EDA)
📊 Visualizations using matplotlib & seaborn

Attrition rate by department & job role
Impact of salary & promotions on churn
Correlation heatmap for feature relationships
3️⃣ Machine Learning Models for Prediction
✅ Logistic Regression (Baseline model)
✅ Random Forest Classifier (Feature importance analysis)
✅ XGBoost Classifier (Best-performing model)
✅ Neural Network (MLPClassifier) (Deep learning approach)

4️⃣ Model Evaluation & Performance Metrics
📉 Accuracy, Precision, Recall, F1-score
📊 Confusion Matrix & ROC Curve
📈 SHAP Analysis – Identifying key drivers of churn

📊 Results & Key Findings

📌 Job satisfaction and work-life balance are strong predictors of attrition.
📌 Employees with fewer promotions & low salary increases are more likely to leave.
📌 XGBoost achieved the highest accuracy (90%) with strong recall for predicting churn.

🚀 Business Recommendations:

Implement better career growth plans to retain high-performing employees.
Improve work-life balance policies to reduce voluntary turnover.
Adjust compensation structures to align with industry standards.
💻 Tech Stack

Python: pandas, numpy, scikit-learn, xgboost, tensorflow
Data Visualization: matplotlib, seaborn, shap
Data Preprocessing: imbalanced-learn, SMOTE for handling class imbalance
Jupyter Notebook for interactive modeling
🚀 How to Run the Project

Clone the repository:
git clone https://github.com/MPGarlock/predictive-analytics.git
Navigate to the project folder:
cd employee-churn-prediction
Install dependencies:
pip install -r requirements.txt
Run the Jupyter Notebook or Python script to train and evaluate models.
📌 Next Steps

✅ Deploy the best model using Flask or FastAPI for real-time predictions
✅ Enhance feature engineering by incorporating sentiment analysis of employee feedback
✅ Develop an interactive dashboard using Power BI or Streamlit

✨ Contributions & Feedback

Fork, explore, and enhance! 🚀 Feel free to submit issues or suggest improvements.
