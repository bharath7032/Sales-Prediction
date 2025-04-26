# Car Purchase Prediction using Machine Learning

## Task Objectives:
This project aims to predict the car purchase amount a customer is likely to spend based on their demographic and financial details. I have used machine learning models to build and evaluate predictions:
- Linear Regression
- Random Forest Regressor

The goal is to build a reliable model that can predict with high accuracy and analyze the performance of different algorithms.

# Dataset
The dataset consists of 500 entries with the following features:
 **Customer Name** (Ignored in model building)
 **Customer Email** (Ignored in model building)
 **Country** (Ignored in model building)
 **Gender** (0: Male, 1: Female)
 **Age** (Years)
 **Annual Salary** (In dollars)
 **Credit Card Debt** (In dollars)
 **Net Worth** (In dollars)

**Target Variable:**
 Car Purchase Amount (In dollars)

There are no missing values or duplicate records in the dataset, making it clean and ready for analysis.


## Data Exploration and Cleaning:
- Checked for missing values, duplicates, and data types.
- Dropped unnecessary columns (customer name, customer email, country).
- Visualized data distributions and relationships.

**Project Steps**
# Project Structure

Car-Purchase-Prediction/ ├── car_purchasing.csv ├── car_purchase_prediction.ipynb ├── requirements.txt └── README.md

**2. Run the Code**
Open the .ipynb file using Jupyter Notebook or VS Code and run the cells step by step.

**Install Required Libraries:**
Make sure you have Python installed. Then install the necessary libraries:

bash

pip install pandas numpy matplotlib seaborn scikit-learn
or

bash

pip install -r requirements.txt
**Run the Notebook or Python Script**:
Open the Jupyter Notebook or run the Python script to see data analysis, model building, evaluation, and results.

**View Model Performance:**
The final section of the code provides a comparison graph between Linear Regression and Random Forest performances. You can also view actual vs predicted values.

**Results**

Model	R2 Score	RMSE (Root Mean Squared Error)
Linear Regression	1.00	1.45
Random Forest	0.95	2326.70
Linear Regression performed extremely well on this dataset. Random Forest also showed good performance but slightly less compared to Linear Regression.

**Project Highlights**
Achieved high accuracy in predicting car purchase amounts.

Clean and well-documented code with clear structure.

Visualizations to understand data distributions and model behavior.

Performance comparison graph for better model understanding.

**Author**
S. Bharath Kumar
