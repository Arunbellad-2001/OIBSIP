# Car Price Prediction Using Machine Learning

## Introduction

This project focuses on predicting the selling price of used cars using
machine learning regression algorithms.

The dataset contains information about used cars such as manufacturing
year, present price, kilometers driven, fuel type, seller type,
transmission, and owner.

The target variable is `Selling_Price`.

## Dataset

The dataset contains 301 rows and 9 original columns.

The original columns are:

- Car_Name
- Year
- Selling_Price
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner

A new feature called `Car_Age` was created from the `Year` column.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Steps

1. Loaded the car dataset using pandas.
2. Checked the dataset shape and column names.
3. Checked data types and dataset information.
4. Checked missing values.
5. Checked duplicate rows.
6. Performed statistical analysis.
7. Explored numerical and categorical columns.
8. Created the `Car_Age` feature.
9. Performed exploratory data analysis using charts.
10. Selected features and target variable.
11. Converted categorical columns using one-hot encoding.
12. Split the dataset into training and testing data.
13. Applied feature scaling for Linear Regression.
14. Trained three regression models.
15. Evaluated the models using MAE, RMSE, and R-squared score.
16. Compared the model results.
17. Selected the best-performing model.
18. Predicted the selling price of a sample car.

## Machine Learning Models

The following models were trained:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error
- Root Mean Squared Error
- R-squared Score

## Model Results

| Model | MAE | RMSE | R2 Score |
|---|---:|---:|---:|
| Linear Regression | 1.472892 | 2.524035 | 0.752815 |
| Decision Tree | 1.361174 | 3.171043 | 0.609847 |
| Random Forest | 1.610752 | 3.967231 | 0.389331 |

## Best Model

Linear Regression performed best based on the R-squared score.

The result was:

- MAE: 1.472892
- RMSE: 2.524035
- R-squared Score: 0.752815

The Linear Regression model was selected as the final model for this
project.

## Key Findings

- The dataset did not contain missing values.
- The dataset contained numerical and categorical features.
- Present price had an important relationship with selling price.
- Car age and kilometers driven were useful features.
- Categorical columns were converted into numerical values.
- Linear Regression achieved the highest R-squared score among the tested
  models.

## Conclusion

In this project, used car data was analyzed and machine learning models
were trained to predict selling prices.

Data cleaning, exploratory data analysis, feature engineering,
categorical encoding, train-test splitting, model training, and model
evaluation were performed.

Among the three tested models, Linear Regression achieved the highest
R-squared score of approximately 0.753.

This project helped in understanding regression algorithms and the
complete machine learning workflow.

The model can be improved in the future by using a larger dataset,
additional features, and hyperparameter tuning.