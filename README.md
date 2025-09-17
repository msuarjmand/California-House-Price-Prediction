# California House Price Prediction
This project applies machine learning techniques to predict housing prices in California, using the California Housing dataset.

The dataset contains 20640 entries and 10 variables:

 - Longitude
 - Latitude
 - Housing Median Age
 - Total Rooms
 - Total Bedrooms
 - Population
 - Households
 - Median Income
 - Median House Value
 - Ocean Proximity


The target variable is the median house value for California districts, expressed in hundreds of thousands of dollars ($100,000).

This dataset was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

A household is a group of people residing within a home. Since the average number of rooms and bedrooms in this dataset is provided per household, these columns may take surprisingly large values for block groups with few households and many empty houses, such as vacation resorts.

It can be downloaded/loaded using the
:func:`sklearn.datasets.fetch_california_housing` function.

- Pace, R. Kelley and Ronald Barry, Sparse Spatial Autoregressions, Statistics and Probability Letters, 33 (1997) 291-297

This project focuses on predicting housing prices in California using machine learning techniques.

# Project Overview

- Exploratory Data Analysis (EDA): Perform a thorough analysis of the dataset to gain insights into the distribution, relationships, and patterns of the features.
- Data Preprocessing: Preprocess the data by handling missing values, scaling features, and encoding categorical variables.
- Model Building: Develop three models for predicting housing prices: VIG, Lasso, and Ridge. These models will leverage the processed data to make accurate predictions.

