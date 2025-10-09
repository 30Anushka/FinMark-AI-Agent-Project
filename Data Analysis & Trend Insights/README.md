# 📊 Phase 4 — Customer Data Analysis & Trend Insights

## 🎯 Objective
This phase focuses on **analyzing and visualizing trends** in both:
1. **Faker-generated (seed) customers** — `customers.csv`
2. **HMA Synthesizer (SDV-expanded) customers** — `customers_hma_10000.csv`

The goal is to:
- Compare the realism of synthetic data vs. seed data  
- Understand income, credit score, and savings trends  
- Identify relationships and patterns in customer financial behavior  



## 🧩 Datasets Analyzed

| Dataset | Description | Source Phase |
|----------|--------------|--------------|
| `customers.csv` | Original seed dataset generated using Faker (2000+ young professionals). | Phase 1 |
| `customers_hma_10000.csv` | AI-generated synthetic customer dataset expanded using HMA Synthesizer. | Phase 2 |



## ⚙️ Scripts Included

| Script | Description |
|--------|--------------|
| `faker_customer_analysis.py` | Analyzes the **seed customer dataset** for distributions, trends, and correlations. |
| `hma_customer_analysis.py` | Analyzes the **HMA synthetic customer dataset** for income, credit, savings, and time-based trends. |

Both scripts:
- Automatically create folders in your **Downloads** directory  
- Save all plots as `.png` with timestamps (so runs never overwrite)  
- Use `matplotlib` and `seaborn` for professional-quality visuals  


## 📈 Visual Analyses Performed

| Analysis Type | Description | Visual Output |
|----------------|--------------|----------------|
| **Scatter Plot** | Shows relationships between numeric variables (e.g., income vs credit score, age vs income). | `income_vs_credit_score.png`, `age_vs_income.png` |
| **Box Plot** | Highlights category-wise distributions (e.g., income by employment type, credit score by job role). | `income_by_employment_type.png`, `credit_score_by_job_role.png` |
| **Trend Analysis** | Reveals how income affects savings or other ratios. | `savings_rate_trend.png` |
| **Time Series Analysis** | Analyzes trends over time based on `joined_date` (monthly averages). | `income_trend_by_join_date.png` |
| **Correlation Heatmap** | Displays interrelationships among numeric variables (income, credit score, balance, savings). | `correlation_heatmap.png` |



## 🧮 Output Structure

Each script automatically saves outputs as:

