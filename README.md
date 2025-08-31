# 🚗 Car Price Prediction – Machine Learning Project  

## 📌 Project Overview  
This project predicts the **price of cars** based on multiple features like brand, horsepower, mileage, fuel type, and age.  
It demonstrates the **real-world application of ML in the automobile industry**, especially for used-car price estimation.  

---

## ⚙️ Tech Stack & Tools  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn  

---

## 🔍 Project Workflow  
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling  

2. **Feature Engineering**  
   - Car Age = Current Year – Manufacturing Year  
   - Mileage per Year = Total Mileage / Age  

3. **Model Training**  
   - Linear Regression  
   - Random Forest Regressor  
   - XGBoost Regressor (optional)  

4. **Evaluation**  
   - R² Score  
   - Mean Absolute Error (MAE)  
   - Root Mean Squared Error (RMSE)  

5. **Model Deployment**  
   - Saved model using `joblib`  
   - Predicts car prices for custom inputs  

---

## 📊 Results  
- **Best Model:** Random Forest Regressor  
- **R² Score:** 0.92 (example)  
- **Visualization:** Predicted vs. Actual price plot
