# 🏠 Predictive Modeling for Real Estate Pricing

## 🎯 Objective
The goal of this project is to **predict real estate prices** using a synthetic dataset. 
The dataset includes property features (area, age, bedrooms, distance to city center, etc.), 
and the target variable is **Price**.  
The project simulates a real-world machine learning workflow where both **linear** and **polynomial relationships** 
affect housing prices.

---

## 📂 Project Workflow

### Phase 1: Data Understanding & Preparation
- Load and inspect dataset (`pandas`).
- Perform Exploratory Data Analysis (EDA).
- Analyze relationships between features & price (scatter plots, heatmaps).
- Handle outliers using IQR/Z-score method.
- Handle missing values (drop, impute).
- Data cleaning & transformations (log transforms, categorical handling).
- Feature scaling (if needed).
- Save EDA insights in `reports/eda_summary.md`.

### Phase 2: Modeling
1. **Baseline Model**  
   - Train a `LinearRegression` model.  
   - Evaluate with RMSE, MAE, and R² Score.  

2. **Polynomial Feature Expansion**  
   - Create polynomial features using `PolynomialFeatures`.  
   - Retrain regression model and compare results.  

3. **Pipeline & Model Saving**  
   - Build an end-to-end `Pipeline` (scaling → polynomial expansion → regression).  
   - Save the best model using `joblib`.  

---

## 📊 Evaluation Metrics
- **Root Mean Squared Error (RMSE)**  
- **Mean Absolute Error (MAE)**  
- **R² Score**

---

## 📁 Project Structure
