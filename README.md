# ACE OF SPADES — CSV Matrix 2.0

This repository contains the Python-based case study analysis prepared by **Team Ace of Spades** for **CSV Matrix 2.0**. The project focuses on analyzing **bank customer churn** and building data-driven insights to help a financial institution retain high-value customers and improve customer experience

## Project Overview

ABC Bank was facing a growing customer churn problem, with customers closing accounts or moving to competitors.  
Our objective was to use exploratory data analysis, segmentation, and visualization to identify churn patterns and suggest actionable retention strategies 

The analysis covers:
- Overall churn rate.
- Churn by tenure.
- Churn by age, gender, and geography.
- Customer segmentation by credit score and balance.
- Identification of at-risk customers.
- Correlation analysis of key churn drivers.
- Customer lifetime value (CLV) estimation and retention insights 

## Team

- **Amit Kumar Mahato** — 2023UGMM004 
- **Aditya Raj Tewary** — 2023UGMM006 
- **Filza Ahsan** — 2023UGMM028 
## Tools and Technologies

The project was built using:
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Google Colab**
- **MS Excel**
- **Google Sheets** 

## Problem Statement

ABC Bank needed support in understanding why customers were leaving and how to retain profitable segments.  
The dataset included customer demographics, account details, transaction behavior, and activity indicators, which were analyzed to produce strategic recommendations 
## Key Analyses

### 1. Churn Rate and Tenure
We calculated the overall churn rate and studied how churn varied across customer tenure groups.  
The analysis showed that churn does not follow a simple linear pattern with tenure, and newly acquired as well as long-tenure customers showed notable churn tendencies

### 2. Demographic Churn Patterns
We analyzed churn by:
- Age
- Gender
- Geography

The findings indicated that:
- Customers in the **50–60** age group were more likely to churn.
- **Female** customers showed higher churn.
- Customers from **Germany** had the highest churn tendency

### 3. Customer Segmentation
We created customer segments using:
- Credit score
- Balance
- Geography

This helped identify which customer groups were most vulnerable to churn and where average balances were concentrated

### 4. At-Risk Customer Identification
We filtered the dataset using specific risk criteria to identify customers who were more likely to attrite.  
This analysis helped isolate a small at-risk group and study their regional and demographic distribution 

### 5. Correlation Analysis
We studied the correlation between churn and:
- Tenure
- Age
- Estimated Salary
- Balance
- Credit Score
- Number of Products

Age showed the strongest positive relationship with churn, while balance had a smaller positive correlation. Other variables showed weaker relationships

### 6. Customer Lifetime Value
We estimated CLV for non-churned customers and analyzed:
- Region-wise revenue contribution.
- CLV distribution by credit score.
- CLV across age groups and geographies.

This helped identify the long-term value of retained customers and highlight the strongest regions for revenue contribution 

## Business Insights

- Churn prevention should focus on older customers and selected high-risk regions.
- Customer engagement strategies may need to differ by age and geography.
- Credit score alone was not a strong predictor of CLV, but it remained useful for segmentation.
- Retention efforts should prioritize high-value and at-risk customers rather than treating all customers equally

## Repository Structure

```text
.
├── data/
├── notebooks/
├── outputs/
├── README.md
└── ACE-OF-SPADES_CSV-MATRIX-2.0-2.pdf
```

## How to Use

1. Open the notebook or Python script in Google Colab or Jupyter Notebook.
2. Load the dataset used for the churn analysis.
3. Run the exploratory analysis, visualizations, and CLV calculations.
4. Review the generated charts and strategic insights.

## Competition Context

This project was developed as part of **CSV Matrix 2.0**, where the team presented a Python-driven analysis of bank churn behavior and retention strategy design
---

**Team Ace of Spades**  
CSV Matrix 2.0
