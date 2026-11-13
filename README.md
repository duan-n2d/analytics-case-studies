# Analytics Case Studies

A curated collection of my analytics work — BI dashboards, customer analytics, data science experiments, and competition submissions. Each folder is a self-contained project with its own README, data (where licensing allows), and deliverables.

> Looking for data engineering work? See my platform projects on my [GitHub profile](https://github.com/duan-n2d).

## Projects

### 📊 BI Dashboards

| Project | Business question | Stack |
|---|---|---|
| [Amazon Sales](bi-dashboards/amazon-sales) | How do B2B/B2C sales, fulfilment, and regions drive ₹78.6M revenue across 121K orders? | Power BI |
| [Food Delivery Profitability](bi-dashboards/food-delivery-profitability) | Which discounts and delivery costs turn orders into losses? | Python, Pandas, Power BI |
| [Adventure Works BI](bi-dashboards/adventure-works-bi) | End-to-end BI for a sales module: ETL → data warehouse → OLAP cube → dashboards | SQL Server, SSIS, SSAS, Power BI |

### 👥 Customer Analytics

| Project | Business question | Stack |
|---|---|---|
| [RFM + K-Means Segmentation](customer-analytics/rfm-kmeans-segmentation) | Which customer segments should marketing target, combining RFM scores with clustering? | Python, scikit-learn |
| [SQL RFM & Marketing Engine](customer-analytics/sql-rfm-marketing-engine) | 11-persona RFM segmentation, segment movement, journey performance, and market basket analysis — fully in SQL | SQL |

### 🧪 Data Science

| Project | Business question | Stack |
|---|---|---|
| [Bank Marketing EDA](data-science/bank-marketing-eda) | Which customer attributes predict term-deposit subscription? | Python, Pandas, Seaborn |
| [Credit Card Fraud Detection](data-science/credit-card-fraud-detection) | How do classical ML, boosting, and deep learning compare on imbalanced fraud data? | scikit-learn, XGBoost, TensorFlow (DNN, LSTM) |

### 🧹 Data Preparation

| Project | Business question | Stack |
|---|---|---|
| [Excel Data Cleaning](data-prep/excel-data-cleaning) | Turning raw sales data into an analysis-ready table and pivot summaries | Excel |

### 🏆 Competitions — Data Got Talent 2024 (Team Pentagon)

| Round | Case | Stack |
|---|---|---|
| [Round 1](competitions/data-got-talent-2024/round-1-cinema) | Business, customer, and operational performance of a cinema chain | Python, Microsoft Fabric, Power BI |
| [Final](competitions/data-got-talent-2024/final-wagering) | Customer RFM segmentation and revenue forecasting (ARIMA, LSTM, GRU) for a wagering operator | Python, statsmodels, Keras |

## Repository layout

```text
bi-dashboards/        Power BI and Microsoft BI stack projects
customer-analytics/   Segmentation and marketing analytics (Python and SQL)
data-science/         EDA and machine-learning experiments
data-prep/            Data cleaning and preparation
competitions/         Data Got Talent 2024 submissions
```

## Notes

- `.pbix` files require [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows). Screenshots are included in each README for quick viewing.
- Datasets are public (Kaggle, competition-provided, or Microsoft sample databases); source links are in each project README.
- Some projects were team work at the University of Economics and Law (VNU-HCM); contributors are credited in each README.

## License

[MIT](LICENSE)
