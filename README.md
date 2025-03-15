# Saudi Arabia House Prices Prediction

## Overview
This project focuses on predicting house prices in Saudi Arabia using machine learning techniques. The goal is to build a robust model that accurately estimates real estate prices based on various property attributes. The analysis involves **exploratory data analysis, feature engineering, model selection, and evaluation** to determine the most effective approach.

## Key Aspects of the Project

### 1. Exploratory Data Analysis (EDA)
- Analyzed the dataset to understand distributions, missing values, and key price-influencing factors.  
- Investigated correlations between features and house prices.  

### 2. Preprocessing Pipeline
- Handled missing values and categorical data encoding.  
- Applied feature scaling and transformations to improve model performance.  

### 3. Feature Selection & Extraction
- Used **Principal Component Analysis (PCA)** for dimensionality reduction.  
- Implemented **K-Means clustering** to explore potential segmentation patterns in the data.  

### 4. Model Training & Evaluation
- Tested multiple models, including:  
  - **Linear Regression**  
  - **Decision Trees**  
  - **Support Vector Machines (SVM)**  
  - **XGBoost**  

- **XGBoost achieved the best Mean Squared Error (MSE), outperforming other models.**  
- Used **GridSearchCV** for hyperparameter tuning to optimize model performance.  

### 5. Final Model & Submission
- Selected **XGBoost** as the final model due to its superior accuracy.  
- Generated predictions and prepared submission files for deployment or competition evaluation.  

## Conclusion
This project provides **valuable insights into real estate pricing trends in Saudi Arabia** and demonstrates how **machine learning can improve property valuation accuracy**.
