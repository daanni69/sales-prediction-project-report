# Sales Prediction using Machine Learning

## 📘 Overview
This project focuses on predicting product sales using advanced data preprocessing, feature engineering, and regression modeling techniques. The dataset was cleaned, analyzed, and modeled to identify key factors influencing sales and to predict future stock demands efficiently.

## ⚙️ Workflow Summary
1. **Data Cleaning & Preprocessing**  
   - Removed missing and duplicate values.  
   - Handled categorical variables using encoding.  
   - Standardized and normalized numerical columns for consistency.  

2. **Feature Engineering**  
   - Created new features like `Stock_per_Category`, `Color_Popularity`, and `Size_Popularity`.  
   - Improved dataset quality for better prediction accuracy.  

3. **Model Building**
   - Trained multiple regression models:  
     - **Random Forest Regressor** (Main Model)  
     - **XGBoost Regressor** (for performance comparison)  
   - Evaluated models using metrics like **MAE, RMSE, R², and MAPE**.

4. **Results**
   - **Random Forest:** R² = 0.9767  
   - **XGBoost:** R² = 0.9790  
   - The model effectively predicts stock demand with high accuracy and minimal error.  

## 📊 Key Insights
- The most impactful feature was **Stock_per_Category**.  
- Random Forest model handled non-linear relationships effectively.  
- Clean and structured data significantly improved model performance.

## 💻 Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🚀 Usage
1. Clone the repository.  
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
