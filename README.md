# Used-car-price-prediction
A PySpark-based project for used car price prediction and data analysis using data preprocessing, exploratory data analysis, Spark SQL, Linear Regression, Decision Tree Regression, and K-Means clustering.
# Used Car Price Prediction and Analysis Using PySpark

## Project Overview

This project focuses on analyzing used car data and exploring machine learning techniques for price prediction using **Apache PySpark**. It demonstrates distributed data processing, data cleaning, exploratory data analysis, SQL-based queries, regression modelling, and customer-independent vehicle segmentation through K-Means clustering.

## Objectives

- Perform data preprocessing and cleaning on used car data.
- Conduct exploratory data analysis to understand vehicle price patterns and characteristics.
- Use Spark SQL to query and analyze vehicle information.
- Build regression models to predict used car prices.
- Evaluate model performance using R², Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).
- Apply K-Means clustering to group vehicles based on selected features.

## Technologies Used

- Python
- Apache PySpark
- Google Colab
- Spark SQL
- Linear Regression
- Decision Tree Regression
- K-Means Clustering

## Project Workflow

1. **Data Loading:** Load the used car dataset into a PySpark DataFrame.
2. **Data Preprocessing:** Clean the data, handle missing values, and prepare features for analysis.
3. **Exploratory Data Analysis:** Examine data distributions, vehicle characteristics, and price patterns.
4. **Spark SQL Analysis:** Execute SQL queries to identify insights, including the most expensive cars.
5. **Regression Modelling:** Train and evaluate Linear Regression and Decision Tree Regression models.
6. **Model Evaluation:** Compare model performance using R², RMSE, and MAE.
7. **Clustering:** Apply K-Means clustering to identify groups of vehicles with similar characteristics.

## Dataset

The project uses a used car dataset containing **4,009 records**. The dataset is used for data cleaning, analysis, price prediction, and clustering.

## Model Evaluation Results

The models were evaluated using a training set of 3,266 records and a testing set of 743 records.

| Model | R² Score | RMSE | MAE |
|---|---:|---:|---:|
| Linear Regression | 0.0521 | 130,949.51 | 26,645.22 |
| Decision Tree Regression | 0.1487 | 124,100.11 | 22,921.88 |

**Result:** Decision Tree Regression performed better than Linear Regression on all three reported evaluation metrics. However, both models achieved relatively low R² scores, indicating that further feature engineering and model improvement may be needed.

## K-Means Clustering

The project uses K-Means with three clusters to explore vehicle groupings.

The recorded cluster distribution was:

- Cluster 0: 1,502 cars
- Cluster 1: 2,504 cars
- Cluster 2: 3 cars

The highly uneven cluster distribution suggests that the selected features and clustering configuration may require further investigation.

## Key Learnings

- Working with PySpark DataFrames and distributed data processing.
- Cleaning and preparing data for machine learning.
- Performing exploratory analysis and Spark SQL queries.
- Training and evaluating regression models.
- Applying K-Means clustering to used car data.
- Interpreting model metrics and identifying opportunities for improvement.

## Future Improvements

- Improve data quality and handle missing or inconsistent values more effectively.
- Explore additional relevant features and feature engineering techniques.
- Tune model parameters and evaluate other regression algorithms.
- Investigate clustering features and parameters to obtain more meaningful groups.

## How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Upload the required dataset or configure its path.
3. Install or configure PySpark if it is not already available in the environment.
4. Run the notebook cells in sequence.
5. Review the analysis, SQL query outputs, model evaluation metrics, and clustering results.

## Project Type

Academic Project | Big Data Analytics | Machine Learning

## Author

**K. Kiran Sai Karthik**
