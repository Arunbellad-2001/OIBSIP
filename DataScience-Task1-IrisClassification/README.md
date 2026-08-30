# Iris Flower Classification

## Project Overview

This project was completed as part of the **Oasis Infobyte Data Science Internship**.

The objective of this project is to build a machine learning classification model that can identify the species of an iris flower based on its physical measurements.

The three species are:

- Setosa
- Versicolor
- Virginica

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Analyze relationships between iris features
- Visualize feature distributions
- Identify the most discriminative features
- Train multiple machine learning classification models
- Evaluate model performance
- Select the best-performing model

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

The Iris dataset is obtained directly from `scikit-learn`.

It contains:

- 150 samples
- 4 numerical features
- 3 target classes

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Exploratory Data Analysis

The project includes:

- Dataset shape inspection
- Data type analysis
- Missing value checking
- Descriptive statistics
- Pairplot visualization
- Box plot visualization
- Feature selection analysis

The analysis showed that **petal length and petal width** provide the clearest separation between the three iris species.

## Machine Learning Models

Two classification models were trained:

1. Logistic Regression
2. Random Forest Classifier

### Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| Random Forest | 90.00% |

### Best Model

**Logistic Regression** was selected as the best-performing model because it achieved the highest test accuracy of **96.67%**.

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Project Files

```text
DataScience-Task1-IrisClassification/
│
├── Iris_Flower_Classification.ipynb
└── README.md

## Internship

Organization: Oasis Infobyte
Track: Data Science
Task: Task 1 - Iris Flower Classification

## Conclusion

This project demonstrates the complete machine learning workflow, including data exploration, visualization, feature analysis, model training, and evaluation. Logistic Regression achieved the best performance with an accuracy of 96.67% on the test dataset.-