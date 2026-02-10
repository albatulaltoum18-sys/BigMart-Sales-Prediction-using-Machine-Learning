BigMart Sales Prediction using Machine Learning

This project focuses on analyzing and predicting retail sales using machine learning techniques. The goal is to understand how product attributes and store characteristics influence sales and to build an accurate predictive model for Item Outlet Sales.

Overview
The project includes extensive data analysis, visualization, feature engineering, and the application of multiple regression models. Various machine learning algorithms were evaluated to identify the most effective approach for sales prediction.

Methodology
The workflow begins with data cleaning and preprocessing, including handling missing values, encoding categorical features, feature scaling, and correlation analysis. The dataset is then split into training and testing sets. Multiple regression models are trained and evaluated, followed by hyperparameter tuning and ensemble learning using a Voting Regressor.

Models Used
Several models were implemented and compared, including Linear Regression, Ridge, Lasso, ElasticNet, Support Vector Regression, Decision Tree, Random Forest, Gradient Boosting, and XGBoost. The final solution uses a Voting Regressor to combine the strengths of multiple models.

Results
The ensemble model achieved strong performance with an R-squared score of approximately 0.62 on the test set. Gradient Boosting and Random Forest models showed the most balanced performance among individual models.

Dataset
The project uses the BigMart Sales dataset, which contains over 8,500 records with multiple product and outlet features commonly used in retail analytics.

Tools and Technologies
Python
NumPy
Pandas
Scikit-learn
XGBoost
Matplotlib
Seaborn
Jupyter Notebook

Project Files

BigMart_Sales_Prediction_ML.ipynb

BigMart_Sales_Prediction_Report.pdf
README.md

How to Run
Open the Jupyter Notebook file and run the cells sequentially after preparing the dataset and required libraries.

Purpose
This project applies machine learning and data analytics to a real-world retail sales prediction problem.

Author
Albatul Altoum (team project)