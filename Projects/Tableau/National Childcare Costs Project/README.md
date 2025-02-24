# 📊 Understanding Childcare Costs in the U.S. - Tableau Dashboard

## 🏠 Overview  
This Tableau dashboard provides an **interactive analysis** of childcare costs across the United States, using data from the **National Database of Childcare Prices (2024, U.S. Department of Labor - Women's Bureau)**. The goal is to highlight the **financial burden on families**, **state-by-state comparisons**, and **policy impacts** on childcare affordability.  

 

---

## 📌 Key Insights  
- 🏆 **Most Expensive States:** In some states, families spend **over 15% of their median household income** on childcare.  
- 📉 **Affordability Gap:** Some states provide **subsidies**, making childcare more affordable, while others have soaring costs.  
- 📈 **Rising Costs Over Time:** Childcare costs have increased by **X% since 2018**, outpacing inflation.  
- 💰 **Cost vs. Household Income:** In many states, childcare is more expensive than **housing or college tuition**.  

---

## 📊 Visualizations  
This dashboard includes **four interactive charts**:  

1️⃣ **📍 Childcare Costs by State (Map)**  
   - A color-coded U.S. map showing the **most & least expensive states** for childcare.  
   - Filter by **year (2018-2023)** and **childcare type (Infant, Toddler, Preschool)**.  

2️⃣ **📊 Childcare Costs as % of Household Income (Bar Chart)**  
   - Ranks **states by affordability**, showing the **percentage of income spent on childcare**.  
   - Uses **Median Household Income (MHI)** from the dataset.  

3️⃣ **📈 Trends Over Time (Line Chart)**  
   - Displays **childcare cost growth** from **2018-2023**.  
   - Allows users to **filter by state** and compare trends.  

4️⃣ **🧒 Cost Breakdown by Child Age Group (Stacked Bar Chart)**  
   - Compares childcare costs for **Infants, Toddlers, and Preschoolers** across states.  
   - Uses interactive filters to explore affordability.  


---

## 📂 Dataset  
- **Source:** *National Database of Childcare Prices (U.S. Dept. of Labor, 2024)*  
- **Columns Used:**  
  - `State_Name`, `StudyYear`  
  - `MFCCInfant`, `MFCCToddler`, `MFCCPreschool` (Childcare costs)  
  - `MHI` (Median Household Income)  
    

**Data Processing:**  
- **Cleaned and formatted in Tableau.**  
- **Calculated Field:** `% of Income Spent on Childcare = (Childcare Cost / Median Income) * 100`.  

---

## 🚀 How to Use the Dashboard  
1. **Explore Filters**: Select a state, year, or childcare type to customize the view.  
2. **Hover Over Charts**: See **exact cost values and trends**.  
3. **Compare Policies**: Identify **states where subsidies lower costs**.  

📌 *This dashboard is designed to help parents, policymakers, and researchers make informed decisions about childcare affordability.*  

---

## 📥 How to Use This Repository  
### 📌 Download & Open in Tableau  
1. Clone this repository:  
   ```sh
   git clone https://github.com/MPGarlock/childcare-costs-dashboard.git
