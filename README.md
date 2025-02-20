# Power BI Project: Customer Churn Analysis in the Credit Card Industry

## Project Overview

This project analyzes **credit card customer churn** using Power BI. The goal was to identify high-risk customer segments, understand churn patterns, and explore the impact of credit utilization, spending behavior, and inactivity periods on churn. This project uses a dataset from Kaggle, and the visualizations provide actionable insights to inform customer retention strategies in the financial sector.

[Kaggle Dataset: Predicting Credit Card Customer Attrition](https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m)

## Objectives

- **Identify high-risk customer segments** based on demographic and behavioral patterns.
- **Assess the correlation** between credit utilization, spending behavior, and inactivity periods with churn.
- **Detect seasonal churn patterns** and potential churn triggers using time-based visualizations.
- **Provide data-driven recommendations** for customer retention strategies.

## Key Features

### Visualizations:
- **Dynamic Churn Rate Visualization**: A color spectrum (red for high churn ~32%, green for low churn ~0%) to quickly assess churn risk.
- **Bar Charts & Heatmaps**: To analyze churn trends across customer segments like income groups, education levels, and card types.
- **Pie Charts**: To segment churned vs. retained customers by marital status, gender, and education level.
- **Scatter Plots**: To correlate transaction behavior (total amount, frequency) with churn likelihood.
- **Time Series Analysis**: Line and combo charts to detect seasonal churn patterns.
- **Customer Segmentation**: Grouping customers based on spending behavior and inactivity periods.

### Insights:
- Churn rate of 16%, with a dynamic color scale for quick visual interpretation.
- Higher churn observed among single customers, those with lower education, and customers with high credit utilization (>80%).
- Transaction behavior indicates that churn tends to peak between 20-40 months of account tenure.
- Seasonal trends suggest that external economic factors and promotional cycles influence churn.

## Methods & Techniques

- **Data Cleaning**: Cleaned and preprocessed the dataset to handle missing values, outliers, and inconsistencies.
- **Exploratory Data Analysis (EDA)**: Performed to uncover relationships between variables and churn.
- **Power BI Features**:
  - Dynamic visualizations using Power BI's color formatting and conditional logic.
  - Interactive dashboards for real-time filtering of customer segments.
  - Custom measures and calculated columns for churn rate and customer segmentation.

## Getting Started

### Prerequisites:
- **Power BI Desktop**: To open and interact with the Power BI report file (.pbix).
  - Download Power BI Desktop from [here](https://powerbi.microsoft.com/desktop/).
- **Kaggle Dataset**: Download the dataset used in the project from [Kaggle](https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m).

### Installation:
1. Clone this repository to your local machine.
2. Download the dataset from Kaggle and place it in the appropriate folder (if required).
3. Open the `.pbix` file using Power BI Desktop.
4. Explore the interactive dashboards and visualizations.

```bash
git clone https://github.com/saimahithae/customer-churn-analysis.git
