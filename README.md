

# E-commerce Demand Forecasting

This repository contains a Jupyter notebook for demand forecasting in an e-commerce setting. The dataset includes features such as day index, Google clicks, Facebook impressions, and quantity sold.

## File Description

- `df_on_e_commerce.ipynb`: The main notebook that includes data preprocessing, exploratory data analysis, and demand forecasting using machine learning models.

## Dataset

The dataset used in this notebook contains the following columns:
- `day_index`: The index representing the day.
- `google_clicks`: The number of clicks from Google ads.
- `facebook_impressions`: The number of impressions from Facebook ads.
- `quantity`: The quantity of items sold.

## Project Overview

The goal of this project is to predict the quantity of items sold based on the features provided. The notebook includes the following steps:

1. **Data Preprocessing**: Cleaning and preparing the data for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizing and understanding the relationships between different features.
3. **Feature Engineering**: Creating new features and transforming existing ones to improve model performance.
4. **Modeling**: Training and evaluating machine learning models to predict the quantity of items sold.
5. **Evaluation**: Assessing the performance of the models using appropriate metrics.

## Dependencies

The following Python packages are required to run the notebook:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these packages using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
