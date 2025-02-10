# 🏡 Florida Income vs. Housing Market: Data Preparation & Analysis

## 📌 Project Overview  
This project explores the relationship between **household income in Florida** and **housing market trends** to assess **housing affordability** over time. By cleaning and preparing datasets from Zillow and U.S. Census sources, the project enables **data-driven analysis of income disparities and real estate price trends**.

Understanding how income levels compare to housing prices is crucial for assessing **economic challenges**, affordability concerns, and policy implications for Florida residents. The dataset was processed for missing values, inconsistencies, and feature engineering to create a structured dataset for further analysis and predictive modeling.

---

## 📊 Data Sources  
- **Zillow Housing Market Data (CSV)** – Contains **median home prices, rental rates, and historical trends**.  
- **U.S. Census Household Income Data** – Includes **median household income, cost of living adjustments, and regional economic indicators**.  
- **Florida Economic Indicators** – Provides **unemployment rates, inflation, and other macroeconomic trends impacting affordability**.  

These datasets were integrated and preprocessed to **analyze the affordability gap** between income levels and housing costs across different Florida regions.

---

## 🔍 Key Research Questions  
1. **How has the gap between median household income and housing costs changed over time?**  
2. **Which Florida regions have the highest affordability challenges?**  
3. **What is the correlation between income growth and housing market trends?**  
4. **How do inflation and unemployment impact housing affordability in Florida?**  

---

## ⚙️ Data Preparation & Cleaning Steps  
### **1. Handling Missing Values & Inconsistencies**  
- Addressed missing or inconsistent records in the **housing and income datasets**.  
- Applied **median imputation and forward-fill techniques** for missing time-series values.  

### **2. Data Transformation & Standardization**  
- Converted price values to **inflation-adjusted dollars** for fair comparisons.  
- Normalized income and housing prices across different counties using **Z-scores and percent change calculations**.  

### **3. Merging & Feature Engineering**  
- Combined datasets by matching **county names, ZIP codes, and time periods**.  
- Created new features, such as **housing-to-income ratios, affordability indices, and regional economic indicators**.  

### **4. Exploratory Data Analysis (EDA)**  
- Visualized **income trends vs. home price appreciation rates**.  
- Analyzed regional variations in affordability using **heatmaps and correlation matrices**.  

---

## 📈 Key Insights & Findings  
- **The income-to-housing price gap has widened significantly** in major Florida cities over the past decade, making homeownership increasingly unattainable for middle-income households.  
- **Certain counties, such as Miami-Dade and Orange County, show severe affordability challenges**, with home price increases far outpacing income growth.  
- **Rental costs have also risen disproportionately**, leading to a higher burden on lower-income groups.  
- **Inflation and interest rate hikes have exacerbated affordability issues**, with mortgage costs increasing at a rate higher than wage growth.  

These findings provide **critical insights for policymakers, real estate investors, and economic analysts** in addressing Florida’s housing affordability crisis.

---

## 🛠 Technologies Used  
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** – Data cleaning, preprocessing, and visualization.  
- **SQL** – Data extraction and querying for regional trends.  
- **Power BI / Tableau** – Interactive dashboards for affordability analysis.  

---

## 📂 Repository Structure 
/florida-housing-analysis
│── data/ # Raw and cleaned datasets
│── notebooks/ # Jupyter notebooks for analysis
│── scripts/ # Python scripts for data cleaning and transformation
│── visualizations/ # Charts and dashboards
│── README.md # Project documentation


---

## 📬 Contact  
For questions, discussions, or collaborations, feel free to connect!  
📧 **Email:** matt.garlock@yahoo.com  
🔗 **LinkedIn:** https://www.linkedin.com/in/matt-garlock/ 

🚀 *Stay tuned for further insights and predictive modeling based on this dataset!*

