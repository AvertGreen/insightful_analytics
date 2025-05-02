# Credit Overdue Analysis

## Project Description

This project analyzes data on loans and payments (both planned and actual) to study customer behavior regarding late payments.  
The main objectives were:
- To identify trends in overdue payments (growth or decrease);  
- Understanding how customer behavior changes over time.  

Inconsistencies in the data were interpreted based on logical assumptions and documented in the final conclusions.

## Data Description

The dataset includes the following fields:  
- `order_id` — application ID  
- `created_at` — application creation date  
- `put_at` — loan issuance date  
- `closed_at` — loan closure date  
- `issued_sum` — issued loan amount  
- `plan_at` — planned payment date  
- `plan_sum_total` — planned total payment amount (cumulative)  
- `paid_at` — actual payment date  
- `paid_sum` — actual payment amount  

## Tools and Libraries  
- Python 3  
- Jupyter Notebook  
- pandas  
- numpy  
- matplotlib  
- seaborn  

## Main Stages of Work  
1. Data loading and initial cleaning;  
2. Missing values, duplicates, and anomaly checks;  
3. Feature engineering to identify overdue cases;  
4. Visualization of overdue payment dynamics over time;  
5. Summary of insights and recommendations based on the analysis.  

## Results  
- Built visualizations to illustrate the dynamics of overdue payments;  
- Identified key patterns in customer payment behavior;  
- Suggested areas for further analysis and optimization of credit processes.
