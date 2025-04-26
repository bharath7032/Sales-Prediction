# Sales-Prediction
Predicting Car Purchase Amounts Using Machine Learning Models This project uses Linear Regression and Random Forest Regression to predict how much a customer is likely to spend on purchasing a car based on personal financial data. The project includes data preprocessing, model training, evaluation, and performance comparison.

Car Purchase Prediction using Machine Learning
Task Objectives :
This project aims to predict the car purchase amount a customer is likely to spend based on their demographic and financial details.
We have used machine learning models to build and evaluate predictions:

Linear Regression

Random Forest Regressor

The goal is to build a reliable model that can predict with high accuracy and analyze the performance of different algorithms.

Dataset :
The dataset consists of 500 entries with the following features:

Customer Name (Ignored in model building)

Customer Email (Ignored in model building)

Country (Ignored in model building)

Gender (0: Male, 1: Female)

Age (Years)

Annual Salary (In dollars)

Credit Card Debt (In dollars)

Net Worth (In dollars)

Target Variable:

Car Purchase Amount (In dollars)

Project Steps
Data Exploration and Cleaning:

Checked for missing values, duplicates, and data types.

Dropped unnecessary columns (customer name, customer email, country).

Visualized data distributions and relationships.

Feature Scaling:

Applied StandardScaler to scale numeric features before feeding them into the models.

Model Building:

Split the dataset into Training and Testing sets (80%-20%).

Trained two models:

Linear Regression

Random Forest Regressor

Model Evaluation:

Evaluated using R2 Score and RMSE (Root Mean Squared Error).

Compared model performances through a graph.


There are no missing values or duplicate records in the dataset, making it clean and ready for analysis.
