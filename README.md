# Churn Analysis Project (EDA)

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a customer churn dataset.  
The goal is to analyze patterns and factors that influence customer churn in a bank.

## Dataset
- Dataset used: `Churn_Modelling.csv`
- Contains: Customer information, demographics, account details, and churn status
- Features include:
  - `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`, `Exited`

## Exploratory Data Analysis (EDA)
1. **Count Plots:** Distribution of customers by Geography, Gender, and Exited
2. **Histograms:** Age and Balance distribution
3. **KDE Plots:** Age distribution of churned vs non-churned customers
4. **Correlation Heatmap:** Correlation of numeric features with `Exited`
5. **Age Bins:** Customers grouped into age categories (0-20, 21-40, 41-60, Above 60)

## Key Insights
- Most churned customers belong to age group 41-60
- Customers in France are the highest in number
- Older customers are slightly more likely to churn
- `Balance`, `Age`, and `CreditScore` show patterns with churn

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/Abdul-Samad43/Churn-Project-EDA.git
