📌 Predicting Employee Attrition

📝 Project Overview
Employee attrition is a key concern for organizations looking to improve retention, reduce hiring costs, and maintain workforce stability. This project applies data mining techniques to predict employee attrition based on various factors such as job satisfaction, work-life balance, salary, and tenure.

🎯 Objective
Develop a predictive model to determine whether an employee is likely to leave the company.
Identify key factors contributing to employee attrition.
Provide actionable insights for HR departments to improve retention strategies.
📂 Dataset

The dataset used in this project contains employee records with features such as:

Demographic information: Age, gender, marital status
Job-related attributes: Job role, job level, department
Work experience: Years at company, years in current role, job satisfaction
Compensation & benefits: Salary, stock options, benefits
Work-life balance & performance: Overtime, work-life balance rating, performance rating
Attrition: Target variable indicating whether an employee left the company
🔗 Source
The dataset is based on IBM HR Analytics Employee Attrition & Performance dataset (or similar anonymized HR datasets).

🛠️ Methods & Approach

1️⃣ Data Preprocessing
Handled missing values and outliers.
Performed feature encoding (e.g., one-hot encoding for categorical variables).
Standardized numerical features for model optimization.
Balanced the dataset using SMOTE to address class imbalance.
2️⃣ Exploratory Data Analysis (EDA)
Identified key trends and correlations using visualizations (seaborn, matplotlib).
Examined attrition rates across different job roles, departments, and satisfaction levels.
3️⃣ Machine Learning Models
The following models were evaluated for predictive performance:
✅ Logistic Regression (Baseline model)
✅ Random Forest (Feature importance analysis)
✅ Gradient Boosting (XGBoost) (Best-performing model)
✅ Neural Network (Alternative deep learning approach)

4️⃣ Model Evaluation
Performance metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC
Feature importance analysis to determine key factors driving attrition
📊 Results & Insights

The XGBoost model achieved the highest accuracy (~88%) with strong precision and recall.
Top factors influencing attrition:
Low job satisfaction significantly increases attrition risk.
Employees working overtime frequently are more likely to leave.
Lower salary increases or lack of promotions contribute to higher attrition rates.
🔍 Key Takeaways for HR:

Improve work-life balance policies to reduce voluntary turnover.
Re-evaluate compensation structures, especially for high-risk job roles.
Provide clear career progression and growth opportunities to increase retention.
💻 Tech Stack

Python: Pandas, NumPy, Scikit-learn, TensorFlow/Keras, XGBoost
Data Visualization: Matplotlib, Seaborn
Jupyter Notebook for interactive analysis
GitHub for version control
🚀 How to Run the Project

Clone the repository:
git clone https://github.com/MPGarlock/data-mining.git
Navigate to the project folder:
cd predicting-employee-attrition
Install dependencies:
pip install -r requirements.txt
Run the Jupyter Notebook or Python script to train and evaluate models.
📌 Next Steps

Deploy the best model using Flask or FastAPI for real-time attrition predictions.
Enhance feature engineering with sentiment analysis of employee feedback.
Explore deep learning approaches for further improvements.
✨ Contributions & Feedback

Feel free to fork this project, submit issues, or suggest improvements! 🚀

