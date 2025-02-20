# Predicting Solar Panel Energy Output

## 📌 Project Overview
This project aims to predict the energy output of solar panels based on various environmental factors. By leveraging machine learning techniques, we analyze historical weather and energy production data to develop a predictive model that can assist in optimizing solar energy utilization.

## 📊 Problem Statement
Solar energy production varies due to environmental factors such as temperature, humidity, cloud cover, and solar radiation. The goal of this project is to build a predictive model that accurately estimates solar panel energy output based on these factors. This can help energy companies, researchers, and policymakers in better forecasting and optimizing energy distribution.

## 📂 Dataset
- **Source**: Kaggle & OpenWeatherMap API
- **Key Features**:
  - `Temperature (°C)`
  - `Humidity (%)`
  - `Cloud Cover (%)`
  - `Solar Radiation (W/m²)`
  - `Wind Speed (m/s)`
  - `Energy Output (kWh)` (Target variable)
- **Preprocessing Steps**:
  - Handling missing values
  - Feature scaling
  - Outlier detection & removal

## 🛠️ Methodology
1. **Data Collection & Cleaning**
   - Merging datasets from multiple sources (historical solar panel data + weather conditions)
   - Removing outliers and handling missing values
2. **Exploratory Data Analysis (EDA)**
   - Visualizing the relationship between weather conditions and energy output
   - Identifying trends and seasonality
3. **Feature Engineering**
   - Creating new features based on weather interactions (e.g., Humidity × Temperature)
4. **Model Selection & Training**
   - Regression models tested:
     - Linear Regression
     - Decision Tree Regressor
     - Random Forest Regressor
     - XGBoost
   - Hyperparameter tuning using GridSearchCV
5. **Evaluation Metrics**
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score

## 🔑 Key Findings
- **Cloud cover and solar radiation** are the most significant predictors of energy output.
- **XGBoost** provided the best performance with an R² score of **0.92**, significantly outperforming linear regression.
- Feature engineering (e.g., interaction terms) improved model accuracy by capturing non-linear relationships.
- Predictions were more accurate in summer months compared to winter due to more stable solar radiation patterns.

## 🚀 Technologies Used
- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Matplotlib & Seaborn (for visualization)
- Jupyter Notebook
- OpenWeatherMap API (for real-time weather data integration)

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/MPGarlock/predict-solar-energy.git
   cd predict-solar-energy
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and execute `solar_energy_prediction.ipynb`.

## 📈 Future Work
- Incorporating **deep learning models** like LSTMs for time-series forecasting.
- Expanding the dataset to include **different geographical locations**.
- Deploying the model as an API for real-time energy predictions.

## 🏆 Acknowledgments
- **Kaggle** for providing solar energy datasets.
- **OpenWeatherMap API** for real-time weather data.

## 📬 Contact
For any questions or contributions, feel free to reach out:
📧 Email: matt.garlock@yahoo.com  
🔗 LinkedIn: https://www.linkedin.com/in/matt-garlock/
