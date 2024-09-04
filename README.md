## Machine learning Project

1. Project Title and Description
Title: Diamond Price Prediction using Machine Learning
Description:
This project utilizes machine learning techniques to predict the prices of diamonds based on various attributes such as carat, cut, color, clarity, depth, and table. The model is trained on a dataset of diamond prices to help users estimate the value of diamonds with high accuracy.


### Introduction About the Data :

**The dataset** The goal is to predict `price` of given diamond (Regression Analysis).

There are 10 independent variables (including `id`):

* `id` : unique identifier of each diamond
* `carat` : Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
* `cut` : Quality of Diamond Cut
* `color` : Color of Diamond
* `clarity` : Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
* `depth` : The depth of diamond is its height (in millimeters) measured from the culet (bottom tip) to the table (flat, top surface)
* `table` : A diamond's table is the facet which can be seen when the stone is viewed face up.
* `x` : Diamond X dimension
* `y` : Diamond Y dimension
* `x` : Diamond Z dimension

Target variable:
* `price`: Price of the given Diamond.

Dataset Source Link :
[https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv](https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv)

# Methodology

'Data Preprocessing': Handling missing values, feature engineering, and scaling.
'Exploratory Data Analysis (EDA)': Analyzing the relationship between attributes and diamond prices.
'Model Selection': Training various machine learning models (e.g., Linear Regression, Decision Trees, Random Forest) to find the most accurate predictor.
'Model Evaluation': Evaluating model performance using metrics like Mean Absolute Error (MAE) and R-squared.

# Model
The Random Forest Regressor model was chosen as the final model due to its high accuracy and robustness against overfitting.
The model was trained on 80% of the dataset and tested on the remaining 20%.

# Results
Best Model Found , Model Name : DecisionTree , R2 Score : 0.9544837557267948




