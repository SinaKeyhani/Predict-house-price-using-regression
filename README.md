# Predict house price - Random Forest Regression

<p align="center">
<img src="https://github.com/SinaKeyhani/Predict-house-price-using-regression/blob/main/kaggle_5407_media_housesbanner.png" alt="Project Image" width="400" height="300"/>
</p>

## Introduction
For this IBM project, I selected the House Prices dataset from Kaggle, which contains information on homes sold in King County, Washington, between May 2014 and May 2015. My focus in this project was exclusively on utilizing Random Forest regression to accurately predict house prices in this region

Dataset : https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data

## Approach: 
In this notebook, I invested substantial effort into data wrangling and exploratory data analysis to uncover key correlations between features and the target variable. I conducted a thorough analysis of feature importance and leveraged RandomizedSearchCV to fine-tune hyperparameters, significantly boosting model performance across both validation and test sets.

## Installation & Usage
To run this project locally, follow these steps:

1. Ensure Python is installed on your machine.
2. Clone this repository
   ```
    git clone https://github.com/SinaKeyhani/Buke-sharing-demand/tree/main
   ```
3. Install the required Python libraries for this project.

eekdays could be an effective tactic for converting them into subscribers.


## Result: 
After implementing the tuned Model with selectedTop Features, we get the following results :

|              Metric                   |   Training   |   Validation   |    Test        |     
|---------------------------------------|--------------|----------------|----------------|
| Root Mean Squared Error (RMSE)        |  51,206.73  |   130,221.21  |   129,997.93  | 
| Mean Absolute Percentage Error (MAPE) |  5.09%     |  13.68%       |   13.27%       |       
| R-squared Score (R2)                  |  98.16      |   86.92       |   87.04%       |






