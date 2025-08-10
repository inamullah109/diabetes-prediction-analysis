Diabetes Prediction Analysis
Project Author: Inam Ullah
Dataset: diabetes_binary_5050split_health_indicators_BRFSS2015.csv
Source: Kaggle
Tools: R, RStudio, tidyverse, caret, ggplot2, pROC, corrplot

📌 Project Overview
As a data analyst, I conducted a comprehensive analysis of the Diabetes Binary Health Indicators (BRFSS 2015) dataset from Kaggle.
The dataset contains 70,692 observations and 22 variables representing clinical, demographic, and lifestyle health indicators.
The main goal was to explore patterns, identify significant risk factors, and build a predictive model for diabetes classification.

🎯 Objectives
Perform data cleaning and preprocessing to prepare the dataset for analysis.
Conduct exploratory data analysis (EDA) to identify trends, distributions, and relationships.
Apply statistical tests (Chi-square, correlation analysis) to confirm associations.
Build a logistic regression model to predict diabetes status.
Evaluate model performance using confusion matrix and ROC-AUC.
🛠 Steps & Key Points
Step 1: Data Loading & Inspection
Loaded required libraries and imported the dataset.
Checked structure, variable types, and summary statistics.
Step 2: Data Cleaning & Preprocessing
Verified no missing values.
Removed duplicates for data integrity.
Converted binary/ordinal variables to factors for proper analysis.
Step 3: Exploratory Data Analysis (EDA)
Visualized class balance for the target variable.
Plotted continuous variables (BMI, MentHlth, PhysHlth) to assess distribution.
Created bar plots for categorical variables to detect skewed distributions.
Step 4: Bivariate Analysis
Compared health/lifestyle factors against diabetes status.
Found HighBP, HighChol, Heart Disease, and Stroke strongly associated with diabetes.
Physical activity, fruit/vegetable intake, income, and education showed protective trends.
Step 5: Correlation Analysis
Checked correlations among continuous variables to avoid multicollinearity.
Step 6: Feature Engineering
Added BMI categories (Normal, Overweight, Obese) to enrich model features.
Step 7: Data Splitting & Model Building
Split data (70% train, 30% test).
Trained logistic regression model.
Achieved Accuracy: ~75% and AUC: 0.824 on test data.
📊 Final Model Performance
Accuracy: 74.96%
Sensitivity: 71.85%
Specificity: 77.98%
AUC-ROC: 0.824
📈 Conclusion
This project successfully demonstrated how structured EDA, proper preprocessing, and logistic regression modeling can be applied to a large public health dataset.
The analysis identified key factors associated with diabetes and showed that a relatively simple model can achieve strong predictive performance.

📂 Files in This Repository
diabetes_analysis.Rmd → Full R Markdown analysis file with code and explanations.
diabetes_analysis.html → Rendered HTML report with visualizations.
README.md → This project overview file.
💡 Key Learnings
Importance of data cleaning and factor conversion for categorical variables.
How EDA helps detect trends before modeling.
Logistic regression remains a powerful baseline model for binary classification.
Author: Inam Ullah
Dataset Source: Kaggle | CDC BRFSS 2015 Dataset