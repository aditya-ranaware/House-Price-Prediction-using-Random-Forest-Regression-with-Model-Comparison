🏷️ Project Title

House Price Prediction using Random Forest Regression with Model Comparison

📌 Overview

This project focuses on predicting house prices using Random Forest Regression and comparing its performance with Linear Regression and Decision Tree models.

The goal is to understand ensemble learning, model behavior, and performance differences across algorithms.

🎯 Objectives
Build a Random Forest Regression model
Reduce overfitting observed in Decision Tree
Evaluate model performance
Compare with Linear Regression and Decision Tree
📊 Dataset Description

The dataset includes features such as:

House size (sqft)
Number of bedrooms
Age of house
Location
Condition
Furnishing

🎯 Target: house_price_usd

⚙️ Methodology
1. Data Preprocessing
Dropped unnecessary columns
Applied one-hot encoding
Prepared dataset for modeling
2. Model Building
Implemented Random Forest Regressor
3. Model Evaluation
R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
4. Overfitting Analysis
Compared training and testing performance
📊 Results
🔹 Random Forest
Training R²: 0.998
Testing R²: 0.985
🔹 Linear Regression
R²: 0.998
🔹 Decision Tree
R²: 0.970
⚖️ Model Comparison
Linear Regression achieved the best performance
Random Forest improved over Decision Tree by reducing overfitting
Decision Tree showed lower generalization
🧠 Key Learnings
Ensemble models improve stability
Random Forest reduces overfitting
Simpler models can outperform complex ones
Model selection depends on data
📌 Conclusion

Linear Regression proved to be the best model for this dataset due to strong linear relationships, while Random Forest provided robust performance and better generalization compared to Decision Tree.

🚀 Future Work
Apply Gradient Boosting (XGBoost, LightGBM)
