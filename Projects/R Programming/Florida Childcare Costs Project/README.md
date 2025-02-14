📊 Florida Childcare Cost Analysis

📝 Project Overview

The rising cost of childcare is a significant financial burden for many families in Florida. This project explores the relationship between childcare costs and household income, using R programming for data analysis, visualization, and predictive modeling.

🎯 Objective

Analyze childcare costs in Florida and compare them to median household income.
Identify trends and regional disparities in childcare pricing.
Develop predictive models to estimate childcare affordability for families.
Provide data-driven insights for policymakers and stakeholders.
📂 Dataset

The project utilizes multiple datasets, including:
✅ Florida Household Demographics (income, family size, location, etc.)
✅ Florida Childcare Cost Estimates (2018-2023) (statewide & county-level price variations)
✅ Non-Vital Rate Report (10-year trends) (population trends affecting childcare demand)

📌 Data Source: U.S. Census Bureau, National Database of Childcare Prices, Florida State Reports

🛠️ R Programming & Methodology

1️⃣ Data Preprocessing
🔹 Cleaning & Transformation using dplyr, tidyverse
🔹 Handling missing values & outliers
🔹 Standardizing cost variables for inflation adjustment

2️⃣ Exploratory Data Analysis (EDA) & Visualization
📊 Key insights extracted using:

ggplot2 – Bar charts, boxplots, heatmaps for cost distribution
correlation matrix (corrplot) – Identifying relationships between income & childcare expenses
facet_grid() – Visualizing cost variations across Florida counties
3️⃣ Statistical Analysis & Modeling
📈 Descriptive Statistics: Mean, median, variance of childcare costs
📊 Hypothesis Testing (t.test(), anova()) – Comparing costs across income brackets
📉 Regression Models (lm()) – Predicting affordability based on household income

4️⃣ Predictive Modeling & Machine Learning
✔ Multiple Linear Regression: Understanding key cost-driving factors
✔ Random Forest (randomForest) – Improving accuracy in cost prediction
✔ K-Means Clustering (kmeans()) – Identifying county-level childcare pricing clusters

📊 Results & Key Findings

📌 Median childcare costs exceed 30% of income for low-income families 📌
📌 Rural areas have lower costs but limited childcare availability 📌
📌 High-income counties show larger price fluctuations based on demand 📌

🚀 Policy Implications:

More subsidies are needed for low-income families to afford childcare.
Expansion of childcare facilities in rural areas can improve accessibility.
Price capping mechanisms may help regulate costs in high-income areas.
💻 Tech Stack

🟢 R Programming: tidyverse, dplyr, ggplot2, caret, randomForest
📊 Visualization: ggplot2, corrplot, patchwork
📁 Data Cleaning & Processing: readr, janitor, tidyverse

🚀 How to Run the Project

Clone the repository:
git clone https://github.com/MPGarlock/r-programming-projects.git
Navigate to the project folder:
cd florida-childcare-cost-analysis
Install dependencies in R:
install.packages(c("tidyverse", "ggplot2", "caret", "randomForest", "corrplot"))
Open childcare_analysis.R and run the script in RStudio.
📌 Next Steps

✅ Incorporate time-series forecasting (ARIMA) for future childcare cost predictions
✅ Deploy an interactive Shiny dashboard for real-time cost analysis
✅ Compare Florida’s childcare costs with other states

✨ Contributions & Feedback

Fork, explore, and improve! 🚀 Feel free to submit issues or suggest enhancements.
