README: Credit Card Default Survival Analysis Notebook
# Project Overview

This notebook applies survival analysis to the Taiwan Credit Card Default Dataset to study time-to-first-payment-delay patterns.

## The analysis includes:

Kaplan-Meier survival curve for the full population
Kaplan-Meier comparison by customer groups
Cox Proportional Hazards regression
Partial effects plots from the Cox model
Interpretation of default/delay risk factors

The main goal is to understand which customer characteristics are associated with earlier payment delays.

Dataset
The notebook uses the Taiwan Credit Card Default Dataset with 30,000 customer accounts.

## Expected dataframe name:

  df
  
## Required columns include:
  ID
  LIMIT_BAL
  SEX
  EDUCATION
  MARRIAGE
  AGE
  PAY_0, PAY_2, PAY_3, PAY_4, PAY_5, PAY_6
  BILL_AMT1 to BILL_AMT6
  PAY_AMT1 to PAY_AMT6
  default.payment.next.month
  Time to first delay
  
## The column below is used as the time-to-event variable

  Time to first delay
  
# Required Python Libraries
 pip install -r requirements.txt
 There are %pip installs built into the code since the venv was acting stupid
 
