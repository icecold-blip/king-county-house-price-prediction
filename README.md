# king-county-house-price-prediction
House price prediction using exploratory data analysis, feature engineering and machine learning regression.

# House Price Prediction

## Project Overview

This project uses machine learning to predict house prices using the King County house sales dataset.

The project includes exploratory data analysis (EDA), data cleaning, data visualisation, feature engineering, regression modelling, and model evaluation.

## Objectives

- Explore the dataset using descriptive statistics.
- Visualise the distributions of features and their relationships with house prices.
- Investigate missing values, outliers, and unusual data.
- Prepare features for machine learning.
- Train and evaluate regression models.

## Dataset

The project uses the King County house sales dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data loading and inspection
2. Data cleaning
3. Exploratory data analysis
4. Statistical analysis and data visualisation
5. Feature selection and engineering
6. Machine learning model training
7. Model evaluation

## Model Performance

Four regression models were trained and evaluated to determine which performed best on the King County house sales dataset.

| Model | MAE | RMSE | R² Score |
|---|---|---|---|
| Linear Regression  		|  86018 | 130794 | 0.853 |
| Decision Tree     		| 133276 | 214200 | 0.607 |
| Random Forest     		| 110964 | 185800 | 0.704 |
| HistGradientBoostingRegressor | 97714  | 162085 | 0.775 |

### Best-Performing Model

**Best model:** Linear Regression

This model achieved the best overall performance based on [the evaluation metric used to select it].
## How to Run the Project

1. Download or clone this repository.
2. Install the required packages:

   `pip install -r requirements.txt`

3. Download the dataset and place it in the location expected by the notebook.
4. Open the notebook in Jupyter Notebook.
5. Run the cells in order.

## Author

icecold-blip
