
# Ola Driver Data Analysis with Random Forest

This project is centered on analyzing the Ola driver dataset using a Random Forest model. The analysis involves cleaning and preprocessing the data, followed by extracting feature importance using Mean Decrease in Impurity (MDI) to understand which features are most significant in predicting outcomes.

Project Overview
The primary goal of this project is to extract meaningful insights from the Ola driver dataset and create a machine learning model to predict driver-related outcomes. This project walks through the full data analysis process: from initial data cleaning and preprocessing, to feature engineering, and ultimately, the development of a Random Forest model for prediction and feature importance analysis.

**Key Steps Involved**:
Data Loading and Cleaning: Handle missing values, convert relevant columns to appropriate data types, and clean up unnecessary columns.

**Exploratory Data Analysis (EDA)**: Investigate key variables like gender distribution, education levels, and explore the data for patterns and potential insights.

**Feature Engineering**: Transform columns and create new features that may enhance model performance.

**Model Building**: Use a Random Forest classifier from the scikit-learn library to build a predictive model.

**Feature Importance**: Analyze which features most significantly contribute to the Random Forest model's decision-making using Mean Decrease in Impurity (MDI).

**Visualization**: Use matplotlib to visualize data and the importance of various features.
Objectives

**Understand Driver Behavior**: Identify patterns in driver data, such as how gender, education level, and date of joining impact performance.
Predict Outcomes: Build a model to predict key outcomes based on driver data.

**Feature Importance**: Determine which features (e.g., date of joining, gender, education level) play the most significant role in predicting outcomes.
Data Cleaning and Preprocessing
The dataset is preprocessed to ensure that it is clean and suitable for machine learning tasks. Key steps include:

**Handling Missing Data**: Assess the percentage of missing values in each column and decide whether to impute or drop missing data.
Datetime Conversion: Convert the relevant date fields (MMM-YY, Dateofjoining, LastWorkingDate) into the proper datetime format for easier analysis.

**Feature Encoding**: Transform categorical variables like Gender and Education_Level into numerical formats to be used by the machine learning model.

**Exploratory Data Analysis (EDA)**
Before building the model, the dataset is explored for insights. Some key EDA steps include:

**Distribution of Gender**: Understanding the proportion of male and female drivers.
Education Level Analysis: Analyzing the distribution of education levels among drivers.
Employment Duration: Investigating the average employment duration of Ola drivers and how it varies with different factors.

**Random Forest Model**
The Random Forest algorithm is used for building a predictive model that handles both categorical and numerical data. This ensemble method provides reliable predictions and is useful for assessing the importance of various features in the dataset.

**Model Training**:
A Random Forest model is trained on the dataset, and the number of decision trees, depth, and other hyperparameters are tuned for optimal performance.

**Feature Importance**:
The project focuses on feature importance using Mean Decrease in Impurity (MDI), which gives a measure of how much a particular feature contributes to the accuracy of the model.

**Results**
Feature Importance: The analysis identifies which features (such as Date of Joining, Education Level, etc.) are most significant in predicting key outcomes for Ola drivers.
Data Insights: Provides insights into driver behavior and other relevant patterns.


## Badges



[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
![Python](https://img.shields.io/badge/python-3.8-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-1.2.4-blue.svg)
![NumPy](https://img.shields.io/badge/numpy-1.19.2-orange.svg)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-orange.svg)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.2-yellow.svg)


## Deployment

Clone the repository:

```bash
  git clone <repository-url>
```
Install required Python libraries:

```bash
  pip install pandas numpy matplotlib scikit-learn
```
Open the notebook:
```bash
    jupyter notebook Ola\ notebook(1).ipynb
