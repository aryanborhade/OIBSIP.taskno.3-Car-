🚗 Car Price Prediction Model
📖 Project Overview

This project builds a Machine Learning regression model to predict the selling price of used cars based on various features such as manufacturing year, fuel type, transmission type, and kilometers driven.

The goal is to understand price-driving factors and build a highly accurate prediction model.

Used car prices depend on multiple factors like:
Car age
Present showroom price
Fuel type
Transmission type
Kilometers driven
Ownership history
This project aims to predict the Selling Price using regression techniques.

Dataset Information
Total Rows: 301
Total Columns: 9
Target Variable: Selling_Price

🔑 Features:
Car_Name
Year
Present_Price
Driven_kms
Fuel_Type
Selling_type
Transmission
Owner

🛠️ Technologies Used:
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

## 🔄 Project Workflow:

### 1️⃣ Data Preprocessing
- Checked for missing values
- Encoded categorical variables (Fuel_Type, Selling_type, Transmission)
- Dropped irrelevant columns (Car_Name)
- Split dataset into training and testing sets
  
### 2️⃣ Feature Engineering
- Created Car Age = Current Year - Manufacturing Year
- Removed original Year column after transformation
  
### 3️⃣ Exploratory Data Analysis (EDA)
- Generated correlation heatmap to understand feature relationships
- Analyzed distribution of Selling Price
- Studied relationship between Car Age and Selling Price
- Analyzed impact of Fuel Type and Transmission on price
  
### 4️⃣ Model Building
- Implemented Linear Regression
- Implemented Random Forest Regressor
- Compared models using R² Score and RMSE

## 📈 Model Performance:
### 🔹 Linear Regression
- R² Score: 0.8488
- RMSE: 1.8658
  
### 🔹 Random Forest Regressor
- R² Score: 0.9594
- RMSE: 0.9664
  
## 🏆 Best Model
Random Forest Regressor performed better than Linear Regression because it captures non-linear relationships between features like mileage, present price, and car age, and reduces overfitting by averaging multiple decision trees.

## 🌍 Real-World Application
- Can be used by car resale platforms
- Helps dealerships estimate fair market value
- Assists buyers and sellers in price negotiation
  
## 🚀 How to Run the Project
1. Clone the repository
2. Install dependencies using: pip install -r requirements.txt
3. Run the Jupyter Notebook using: jupyter notebook

## 🔮 Future Improvements
- Hyperparameter tuning using GridSearchCV
- Try advanced models like XGBoost
- Deploy using Streamlit or Flask
- Add cross-validation
  
## 📚 Key Learnings
- Practical implementation of regression algorithms
- Importance of feature engineering
- Understanding model evaluation metrics like R² and RMSE
- Comparing linear and ensemble models.
