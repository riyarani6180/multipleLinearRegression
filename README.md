# Multiple Linear Regression - Economic Index Prediction

## Project Overview

This project demonstrates the implementation of a Multiple Linear Regression model using Python and machine learning.

The model uses economic data to predict the Stock Index based on two independent variables:

* Interest Rate
* Unemployment Rate

The project is designed as a beginner-friendly machine learning project to understand how multiple input variables can be used to predict a single output variable.

## Dataset

The dataset used in this project is:

`economic_index.csv`

It contains economic information for different years.

### Dataset Features

| Feature           | Description                     |
| ----------------- | ------------------------------- |
| Year              | Year of the observation         |
| Interest_Rate     | Interest rate in percentage     |
| Unemployment_Rate | Unemployment rate in percentage |
| Stock_Index       | Stock market index              |

## Problem Statement

The objective of this project is to predict the Stock Index using Interest Rate and Unemployment Rate.

### Input Features

* Interest_Rate
* Unemployment_Rate

### Target Variable

* Stock_Index

## Machine Learning Algorithm

The project uses Multiple Linear Regression.

The general equation for Multiple Linear Regression is:

```text
Y = b0 + b1X1 + b2X2
```

Where:

* `Y` is the predicted Stock Index
* `X1` is the Interest Rate
* `X2` is the Unemployment Rate
* `b0` is the intercept
* `b1` and `b2` are the coefficients

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
* Jupyter Notebook

## Project Workflow

1. Load the dataset.
2. Import the required Python libraries.
3. Read the CSV file using Pandas.
4. Explore and understand
