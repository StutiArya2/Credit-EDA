# Credit-EDA
This project performs exploratory data analysis (EDA) on a credit dataset to uncover insights and 
trends. It includes cleaning, visualizing, and summarizing data to understand customer behavior, 
credit scores, and risk factors. Features include Python-based analysis using Pandas, Matplotlib,
and Seaborn for meaningful visualizations.


**Use the Below Drive Link to access previous_application.csv and application_data.csv
https://drive.google.com/drive/folders/1q5HJRwYZT7mA4sskdfNsarTDqLZFMVvf?usp=sharing**


Here's a full description you can use for your Jupyter Notebook:

### **Credit Card Default Prediction - Exploratory Data Analysis (EDA)**

This Jupyter notebook focuses on performing **Exploratory Data Analysis (EDA)** on a dataset related to **credit card default prediction**. The goal of the analysis is to understand the underlying patterns and relationships in the data before applying machine learning models for prediction.

#### **Key Features:**

1. **Data Loading & Cleaning:**
   - The dataset is loaded into a DataFrame and cleaned to handle missing values, outliers, and inconsistencies.
   
2. **Data Exploration:**
   - Various methods are used to examine the structure of the dataset, such as checking the number of rows and columns, data types, and summary statistics.
   - Visualizations, including histograms, box plots, and bar plots, are created to understand the distribution and relationships between variables.

3. **Correlation Analysis:**
   - Heatmaps and pairplots are generated to visualize the correlation between different features in the dataset.
   - This helps identify which features may be important predictors for the target variable (default status).

4. **Feature Engineering:**
   - New features or derived features may be created based on existing data to improve the model’s prediction capability.
   - Categorical variables are processed, and scaling is applied to numerical data where needed.

5. **Visualization:**
   - Various visualization techniques (matplotlib, seaborn) are used to plot trends, distributions, and relationships in the data, helping in understanding the features and their impact on the target variable.

6. **Target Variable Analysis:**
   - Special focus is given to understanding the distribution of the target variable (`default` or `not default`), helping in detecting any imbalance in the dataset.

7. **Outlier Detection:**
   - Outliers are detected and visualized to understand their potential impact on model training. These are either treated or removed depending on their significance.

#### **Goals of the Notebook:**
- Perform thorough EDA to uncover insights that could be useful for machine learning models.
- Identify potential data issues such as missing values, skewed distributions, or correlations that could affect model performance.
- Prepare the data for future machine learning model training, such as classification algorithms for predicting credit card defaults.


This notebook serves as an essential first step in the machine learning pipeline, focusing on understanding the data thoroughly before proceeding to build models for credit card default prediction.
