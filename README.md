Task:
In this task, you will work with dummy sales data of a well-known brand on Amazon. Your objective is to build a time series forecasting model that predicts the number of units sold for each item ID.

Description:

This data pertains to Amazon (USA), so feature engineering should be conducted accordingly.
The dataset contains dummy sales data for various items sold by a well-known brand on Amazon. Each row in the dataset represents the sales data for a particular item on a specific date. The columns included in the dataset are:
date: The date on which the sales data was recorded. This column is essential for time series analysis and forecasting. The format is typically YYYY-MM-DD.
Item Id: A unique identifier for each item. This column helps in distinguishing between different products.
Item Name: The name of the item. While this column is not directly used in numerical analysis, it provides a human-readable reference to the items.
anarix_id: An internal identifier that might be used for tracking or categorizing items within the brand's system.
ad_spend: The amount of money spent on advertising for the item on the given date. This column can be useful in understanding the relationship between advertising spend and sales performance.
units: The number of units sold for the item on the given date. This is the target variable for forecasting in this task.
orderedrevenueamount: The total revenue generated from the units sold on the given date. This can be used to calculate metrics like average unit price and return on ad spend.
unit_price: The price per unit of the item. This column helps in understanding the pricing strategy and its impact on sales.


Evaluation
Your model will be evaluated based on its ability to accurately forecast the number of units sold for each item ID. The primary evaluation metric will be the Mean Squared Error (MSE). This metric measures the average magnitude of the errors between the predicted and actual values, with lower MSE values indicating better model performance.
Submission Requirements:
Ensure that you submit your work on Kaggle and also create a Google Drive folder containing the following:
The .ipynb notebook file
A PDF version of the notebook
The file with the predicted results
Expected Content:
Your submission should include the following sections:
Exploratory Data Analysis (EDA)
Feature Engineering
Model Selection
Hyperparameter Tuning
"Individuals who have finished the first task can proceed to Task 2 (for bonus points). In this task, you need to predict unit sales without using ad spend data. You can attach both the PDF of your notebook and the .ipynb file in the sheet below for that too along with your first task inside the drive"
