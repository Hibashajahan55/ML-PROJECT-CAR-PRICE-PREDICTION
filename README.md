# CAR PRICE PREDICTION USING MACHINE LEARNING
# 📌PROJECT OVERVIEW
A Chinese automobile company aims to enter the US market and needs to understand car pricing factors. They have contracted an automobile consulting firm to analyze key variables affecting car prices in the American market. This project models car prices using machine learning algorithms and provides insights for business decision-making.
# 📌DATASET
The dataset contains various features related to cars, including performance metrics, fuel efficiency, size, and engine characteristics. Our goal is to predict car prices using these independent variables.
# 📌STEPS INVOLVED IN THE PROJECT:
## 1. Data Loading and Preprocessing 
Before applying machine learning models, the dataset was cleaned and processed to ensure high-quality input data.
Steps Taken:
* Handling Missing Values: No major missing values were found.
* Feature Engineering: Extracted car brand names from the CarName column for better analysis.
* One-Hot Encoding: Converted categorical variables into numerical representations.
* Dropping Irrelevant Columns: Removed unnecessary attributes such as car_ID and redundant CarName.
## 2.Model Implementation
To predict car prices, five different machine learning models were implemented. Each model was trained, tested, and compared based on performance metrics.
#### i.Linear Regression
#### ii.Decision Tree Regressor
#### iii.Random Forest Regressor
#### iv.Gradient Boosting Regressor
#### v.Support Vector Regressor (SVR)
Each model was trained using 80% of the dataset, while the remaining 20% was used for testing.
## 3.Model Evaluation 
To determine the best model, we compared all five models using key evaluation metrics:
Metrics Used for Model Comparison
#### i.R² Score (Coefficient of Determination): Measures how well independent variables explain the target variable.
#### ii.Mean Squared Error (MSE): Evaluates the average squared difference between actual and predicted prices.
#### iii.Mean Absolute Error (MAE): Measures the average absolute difference between predictions and actual values.
#### iv.Root Mean Squared Error (RMSE): Similar to MSE but with a squared root transformation for interpretability.
## 4. Feature Importance Analysis
To understand which factors influence car prices the most, we analyzed feature importance using tree-based models.
## 5.Hyperparameter Tuning
* To improve model performance by fine-tuning hyperparameters for better accuracy.
* GridSearchCV was applied to Decision Tree, Random Forest, Gradient Boosting, and SVR models.
* Best Hyperparameters Identified:Random Forest
