# Customer-Churn-Analysis-in-Telecommunications Using Python
# Customer Churn Analysis in Telecommunications
## Project Overview

Customer churn is a critical challenge in the telecommunications industry, where customers discontinue services. This project focuses on analyzing customer data to identify patterns, trends, and key factors influencing churn.

The goal is to support data-driven decision-making for improving customer retention strategies.

## Objectives
* Understand customer behavior and churn patterns
* Perform data preprocessing and cleaning
* Conduct Exploratory Data Analysis (EDA)
* Visualize key insights using graphs
* Identify factors contributing to customer churn

## Dataset Information
* **Source**: Kaggle
* **Dataset Type**: Telecom Customer Data
* **Rows**: 7043
* **Columns**: 21

## Features Include:
* Customer demographics (gender, senior citizen, etc.)
* Services subscribed (internet, phone, streaming)
* Account information (tenure, contract type)
* Billing details (monthly charges, total charges)
* Target variable: Churn (Yes/No)

# Phase 1: Data Understanding
## Objective

* To understand the dataset structure, features, and data types.

## Activities Performed

* Loaded dataset using Pandas
* Viewed dataset structure using .head(), .shape
* Checked column names and data types
* Used .info() and .describe() for summary statistics

## Observations

* Dataset contains both categorical and numerical variables
* Target variable is Churn
* Dataset is well-structured and suitable for analysis

# Phase 2: Data Preprocessing
## Objective

* To clean and prepare the dataset for analysis.

## Steps Performed

* Checked missing values using isnull()
* Verified duplicate records using duplicated()
* Converted data types where necessary
* Standardized categorical values

## Note

* The dataset obtained from Kaggle was already well-cleaned.
* Only minimal preprocessing was required to ensure consistency and correctness.

## Output

* Cleaned dataset ready for analysis

# Phase 3: Exploratory Data Analysis (EDA)
## Objective

* To explore data and identify patterns, trends, and relationships.

## Analysis Performed

ðŸ”¹ **Univariate Analysis**
* Distribution of churn
* Distribution of tenure and charges

ðŸ”¹ **Bivariate Analysis**
* Churn vs Contract Type
* Churn vs Tenure
* Churn vs Payment Method

ðŸ”¹ **Multivariate Analysis**
* Used groupby() and pivot tables
* Compared churn across multiple features

ðŸ”¹ **Statistical Analysis**
* Generated summary statistics
* Performed correlation analysis

## Key Findings

* Customers with short tenure are more likely to churn
* Month-to-month contracts show higher churn rates
* Higher monthly charges are associated with increased churn

# Phase 4: Data Visualization
## Objective

* To represent insights visually for better understanding.

## Visualizations Used
* Countplots (Churn distribution)
* Barplots (categorical relationships)
* Boxplots (numerical comparisons)
* Heatmap (correlation analysis)

## Insights from Visualization
* High churn observed in flexible contracts
* Pricing plays a significant role in churn
* Strong relationship between tenure and total charges

## Tools & Technologies
* Programming Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn
* Environment: Jupyter Notebook

## Key Insights
* Short-term customers are more likely to churn
* Customers with higher charges tend to leave
* Long-term contracts improve retention
* Payment methods influence churn behavior

## Conclusion

* This project demonstrates how data analysis can be used to understand customer behavior and reduce churn. The insights derived can help telecom companies design effective retention strategies and improve customer satisfaction.

# Project Structure
Customer-Churn-Analysis/
â”‚
â”œâ”€â”€ Phase_1_Data_Understanding/
â”œâ”€â”€ Phase_2_Data_Preprocessing/
â”œâ”€â”€ Phase_3_EDA/
â”œâ”€â”€ Phase_4_Visualization/
â”‚
â”œâ”€â”€ Dataset/
â”‚   â”œâ”€â”€ raw_dataset.csv
â”‚   â””â”€â”€ cleaned_dataset.csv
â”‚
â””â”€â”€ notebook.ipynb

## Acknowledgment

* Dataset sourced from Kaggle.
