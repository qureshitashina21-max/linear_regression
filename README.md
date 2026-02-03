

####### Insurance Cost Prediction using Machine Learning
 Project Overview
This project focuses on predicting medical insurance expenses using Machine Learning.
By analyzing key factors such as age, BMI, gender, smoking status, number of children, and region, the model identifies which features strongly affect insurance charges and builds accurate prediction models.
 Dataset Description
The dataset contains important health and demographic attributes:
Column
Description
age
Age of the individual
sex
Gender (male/female)
bmi
Body Mass Index
children
Number of dependents
smoker
Whether the person smokes (yes/no)
region
Residential region
expenses
Medical insurance cost (target variable)
 Steps Performed in the Project
1️⃣ Data Cleaning
Checked for missing values
Removed duplicates
Converted data types
Renamed inconsistent values
2️⃣ Exploratory Data Analysis (EDA)
Visualizations done using Matplotlib and Seaborn:
Distribution plots for age, bmi, expenses
Count plots for sex, children, smoker, region
Boxplots to detect outliers
Correlation heatmap for numeric features
3️⃣ Feature Engineering
Created BMI categories: Underweight, Normal, Overweight, Obese
Applied One-Hot Encoding for categorical columns
Scaled numeric features using StandardScaler
Performed Chi-Square test to select important categorical features
Calculated Pearson correlation for numeric features
4️⃣ Model Building
Used Linear Regression Model for prediction.
✔ Model Performance:
R² Score: ~0.756
Adjusted R² Score: ~0.781
These scores show that the model explains most of the variation in insurance expenses.
5️⃣ Prediction for Unseen Data
Model successfully predicts expenses for new inputs using the trained regression model and scaling transformation.
 Conclusion
Smoking is the most impactful variable on insurance cost.
BMI and Age also show noticeable influence.
Gender and region have weaker relationships.
The Linear Regression model performs well with R² ≈ 75%.
The project demonstrates the entire ML pipeline:
Cleaning → EDA → Feature Engineering → Model Training → Evaluation → Prediction.
📦 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
SciPy
