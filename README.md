# Data-Science-Project-Series

## Project 1-Stock Market Analysis and Prediction

Project Overview:
This project involves performing comprehensive Exploratory Data Analysis (EDA) and developing predictive models to analyze and forecast stock market trends. Utilizing a CSV dataset named infolimpioavanzadoTarget.csv, which comprises various stock-related metrics, the goal is to understand the data's structure, visualize key statistics, and build a model to predict closing prices with high accuracy.

### Dataset:
#### The dataset infolimpioavanzadoTarget.csv contains the following columns:

- date: The date of the stock data.
- open: Opening price of the stock.
- high: Highest price of the stock during the trading period.
- low: Lowest price of the stock during the trading period.
- close: Closing price of the stock.
- adjclose: Adjusted closing price of the stock.
- volume: Volume of stocks traded.
- ticker: Stock ticker symbol.
- RSIadjclose15: Relative Strength Index of the adjusted close price over 15 periods.
- RSIvolume15: Relative Strength Index of the volume over 15 periods.
- high-15: Highest price of the stock over the last 15 periods.
- K-15: %K value of the stochastic oscillator over 15 periods.
- D-15: %D value of the stochastic oscillator over 15 periods.
- stochastic-k-15: Stochastic %K value over 15 periods.
- stochastic-d-15: Stochastic %D value over 15 periods.
- stochastic-kd-15: Stochastic %K-%D value over 15 periods.
- volumenrelativo: Relative volume.
- diff: Difference between consecutive closing prices.
- INCREMENTO: Incremental value.
- TARGET: Target variable for predictive modeling.

### Objectives:

#### 1. Exploratory Data Analysis (EDA):

- Understand the structure and characteristics of the dataset.
- Visualize key statistics and trends in stock prices.
- Identify patterns and relationships between different variables.

#### 2. Predictive Modeling:

- Develop a predictive model to forecast stock closing prices.
- Evaluate the model's performance using appropriate metrics.

### Steps and Methodologies:

#### 1. Loading and Understanding the Data:

- Load the CSV file using Pandas.
- Display the first few rows and summary statistics of the dataset.
- Check for missing values and data types of each column.

#### 2. Data Visualization:

- Plot the distribution of closing prices using histograms.
- Create a time series plot of closing prices.
- Generate a correlation matrix to understand relationships between variables.
- Use boxplots to visualize closing prices by ticker.
- Use pairplots to explore relationships between key variables.

### Tools and Technologies:

- Programming Language: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### Outcome:
The project aims to provide insights into stock market trends through EDA and develop a reliable predictive model to forecast stock closing prices. This analysis can help investors make informed decisions based on historical data and predictive insights.

---

## Project 2- Breast Cancer Diagnosis Using Support Vector Machine

Project Overview:
This project aims to develop a robust machine learning model for classifying breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin (Diagnostic) dataset. The primary goal is to enhance the predictive accuracy through meticulous data preprocessing, feature selection, and engineering, followed by implementing a Support Vector Machine (SVM) for classification.

### Phase 1: Data Preprocessing

### Objective: Clean and preprocess the dataset to ensure data quality and integrity.
#### Tasks:
- Load and explore the dataset.
- Handle missing values and drop irrelevant columns.
- Remove duplicates and outliers to refine the data.


### Phase 2: Feature Selection and Engineering

### Objective: Identify and engineer features to improve the model's predictive performance.
#### Tasks:
- Analyze the correlation matrix to select relevant features.
- Create new features by combining existing ones to capture additional information.


### Phase 3: Machine Learning Model (SVM)

### Objective: Develop and evaluate an SVM model for accurate tumor classification.
#### Tasks:
- Split the dataset into training and testing sets.
- Train the SVM model using the selected features.
- Evaluate the model's performance using metrics such as accuracy, confusion matrix, and classification report.


### Outcome:
The project successfully demonstrates the application of data preprocessing techniques and SVM in classifying breast cancer tumors with high accuracy, providing valuable insights for early diagnosis and treatment.
