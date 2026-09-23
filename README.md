# Customer Churn Analysis

> End-to-end customer churn analysis using Python, exploratory data analysis, statistical analysis, and machine learning to identify high-risk customer segments and support customer retention strategies.

## Overview

Customer churn is an important business problem for subscription-based companies. Losing customers can affect recurring revenue, customer lifetime value, and long-term business growth.

This project analyzes customer demographics, services, contracts, billing information, tenure, and churn behavior to identify patterns associated with customer churn.

The objective is to transform customer-level data into actionable business insights and evaluate whether machine learning can help identify customers with higher churn risk.

## Business Problem

A subscription-based company wants to understand why customers leave and identify customer segments that may require targeted retention strategies.

The analysis focuses on understanding customer behavior rather than relying solely on predictive performance.

## Objectives

This project aims to:

- Identify customer segments associated with higher churn.
- Analyze relationships between customer characteristics and churn.
- Investigate the effect of tenure and contract type on churn.
- Examine customer service and payment patterns.
- Build machine learning models for churn prediction.
- Translate analytical findings into actionable business insights.

## Business Questions

1. Which customer segments have the highest churn rate?
2. How does customer tenure relate to churn?
3. Which contract types are associated with higher churn?
4. How do payment methods relate to customer churn?
5. Which customer services are associated with churn behavior?
6. Which variables are most informative for predicting churn?
7. How can the findings support customer retention strategies?

## Dataset

The project uses a publicly available Telco Customer Churn dataset containing information about customer demographics, services, contracts, billing, tenure, and churn status.

### Main Variables

The dataset includes variables related to:

- Customer demographics
- Contract type
- Internet services
- Additional services
- Payment method
- Monthly charges
- Total charges
- Customer tenure
- Churn status

The original dataset source and applicable licensing terms should be reviewed before redistribution.

## Analytical Workflow

The project follows the following analytical workflow:

Business Understanding  
↓  
Data Understanding  
↓  
Data Quality Assessment  
↓  
Data Cleaning  
↓  
Exploratory Data Analysis  
↓  
Statistical Analysis  
↓  
Feature Engineering  
↓  
Machine Learning  
↓  
Model Evaluation  
↓  
Business Insights  
↓  
Recommendations

## Data Preparation

The data preparation process includes:

- Checking missing values
- Detecting duplicate records
- Validating data types
- Checking inconsistent categories
- Investigating numerical variables
- Identifying potential outliers
- Preparing variables for analysis and modeling

All major data preparation decisions are documented in the analysis notebook.

## Exploratory Data Analysis

The exploratory analysis investigates customer behavior across several dimensions, including:

### Customer Characteristics

- Gender
- Senior citizen status
- Partner status
- Dependents

### Customer Relationship

- Tenure
- Contract type

### Services

- Internet service
- Online security
- Online backup
- Device protection
- Technical support

### Financial Variables

- Monthly charges
- Total charges
- Payment method

The analysis focuses on identifying meaningful differences between customers who churn and customers who remain.

## Statistical Analysis

Statistical analysis is used to investigate relationships between customer characteristics and churn.

The analysis distinguishes between:

- Observed patterns
- Statistical relationships
- Business interpretations

Statistical conclusions are evaluated based on the appropriate assumptions and methods used in the analysis.

## Machine Learning

Several classification algorithms are evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

Model evaluation considers both predictive performance and business relevance.

## Key Findings

The analysis identifies customer characteristics and behavioral patterns associated with churn.

Key findings will include:

- Customer segments with higher churn rates
- Relationships between tenure and churn
- Contract-related churn patterns
- Payment and service patterns
- Important variables for churn prediction

Detailed findings and supporting visualizations are presented in the analysis notebook.

## Business Insights

The analysis is intended to help businesses:

- Identify high-risk customer segments
- Prioritize retention efforts
- Improve customer onboarding
- Investigate contract conversion opportunities
- Develop targeted retention strategies

## Recommendations

Business recommendations are developed based on the analytical findings rather than assumptions.

Potential areas of action include:

1. Prioritizing customer segments with elevated churn risk.
2. Strengthening early-stage customer engagement.
3. Investigating retention strategies for short-term contracts.
4. Monitoring customer behavior after acquisition.
5. Evaluating targeted retention campaigns.

## Technologies

| Category | Tools |
|---|---|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Statistics | SciPy |
| Machine Learning | Scikit-learn, XGBoost |
| Environment | Jupyter Notebook |
| Version Control | GitHub |

## Reproducibility

The analysis is designed to be reproducible using the Python dependencies listed in requirements.txt.
Project Status

Status: Portfolio project

Future improvements may include additional statistical testing, feature engineering, model optimization, and model interpretability.

## Author

Abdillah Farhan

Data Analyst | Data Science

Areas of interest:
- Data Analytics
- Business Intelligence
- Statistics
- Customer Analytics
- Marketing Analytics
- Machine Learning

## Repository Structure

```text
customer-churn-analysis/
│
├── data/
├── notebooks/
├── outputs/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore








