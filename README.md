# Crop Yield Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting crop yield (quintals per hectare) using machine learning techniques based on agricultural cost and crop-related parameters. The project demonstrates an end-to-end machine learning workflow including data analysis, model building, evaluation, and prediction.

## 🎯 Problem Statement
Accurate crop yield prediction is important for agricultural planning and decision-making. This project aims to build a regression-based machine learning model to predict crop yield using historical agricultural cost data.

## 📊 Dataset Description
The dataset contains aggregated crop-wise and state-wise agricultural data with the following features:
- Crop
- State
- Cost of Cultivation (A2+FL)
- Cost of Cultivation (C2)
- Cost of Production
- Yield (Quintals per Hectare)

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to understand data distributions, detect outliers, and analyze relationships between features using:
- Distribution plots
- Boxplots
- Scatter plots
- Correlation heatmap

## ⚙️ Data Preprocessing
- Categorical features were encoded appropriately
- Train-test split was applied
- Data was prepared for regression modeling

## 🧠 Models Implemented
- Linear Regression (Baseline Model)
- Random Forest Regressor

## 📈 Model Evaluation
Models were evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Random Forest Regressor achieved better performance with higher R² and lower RMSE.

## 🛠️ Challenges Faced
- Incorrect categorical encoding initially caused constant predictions
- Issue was fixed by ensuring correct encoded feature mapping

## ✅ Results
The final model provides dynamic crop yield predictions based on user input.

## ⚠️ Limitations
- Small and aggregated dataset
- No weather or soil parameters included

## 🔮 Future Scope
- Include weather and soil data
- Use advanced models like XGBoost
- Deploy as a web application

## 🧪 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 👤 Author
**Harshit Chaudhari**  
