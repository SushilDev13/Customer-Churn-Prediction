# Retail Analytics & Uplift Testing
Detect Churn Risk by building features around cost sensitivity, tenure, & engagement patterns, and training a Random Forest model that adjusts for imbalance in churn data.

## Problem Statement
PowerCo currently sees a 10% churn rate among their customers.

## Project Goals
- Predict customers at risk of churning using behavioral and financial indicators.
- Uncover drivers of churn by analyzing tenure, margin sensitivity, and sales channel performance.
- Equip the business with actionable insights for targeted interventions and uplift strategies.

## Key Insights
- Churned customers tend to skew toward higher cost brackets, indicating that cost sensitivity is a key driver of customer churn.
- Churn is highest among mid-tenure customers (2-4 years), while long-tenure customers show strong loyalty.
- Some acquisition campaigns & sales channels are linked to noticeably higher churn rate.

## Programming & Data Analysis
- Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn)
- Jupyter Notebook
- Random Forest Model

## Results Summary
- While overall accuracy is modest, the **churn recall (0.55)** shows that the model can identify a meaningful portion of at-risk customers.
- However, **precision for churners is low (0.16)**, indicating a higher false positive rate which may be acceptable in proactive churn prevention strategies.
- **Margin Gross Power Electric & Margin Net Power Electric** are key factors driving churn in this model.
