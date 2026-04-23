# Trader Performance vs Market Sentiment

## Objective

Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance.

---

## Project Structure -
trader-sentiment-analysis/
│
├── data/
│   ├── fear_greed_index.csv
│   └── historical_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── outputs/
│   ├── pnl_by_sentiment.png
│   ├── trade_frequency.png
│
├── README.md
├── requirements.txt
└── summary.md
## Datasets Used

1. Bitcoin Market Sentiment (Fear/Greed Index)
2. Historical Trader Data (Hyperliquid)

---
# Sections-
  1. Problem Statement

  2. Data Loading

  3. Data Understanding

 4. Data Cleaning

 5. Feature Engineering

 6. Data Merging

 7. Exploratory Data Analysis (EDA)

 8. Segmentation Analysis

 9. Key Insights

 10. Strategy Recommendations

## Methodology

* Cleaned and validated datasets
* Converted timestamps and aligned data at daily level
* Engineered key features:

  * Daily PnL
  * Win Rate
  * Trade Count
  * Average Trade Size
  * Long/Short Ratio
* Merged datasets based on date
* Performed exploratory data analysis
* Built a predictive model to classify profitability

---

## Key Insights

* Traders perform better during Fear phases compared to Greed phases.
* Trading activity and position size increase significantly during Fear periods.
* High-leverage traders generate higher returns but carry increased risk.
* Profitability is influenced by multiple behavioral factors rather than a single metric.

---

##  Strategy Recommendations

* Increase trading activity during Fear phases while maintaining risk control.
* Reduce exposure and avoid overtrading during Greed periods.
* Apply differentiated strategies based on trader risk profiles.

---

##  Bonus: Predictive Model

* Built a Random Forest model to predict trader profitability
* Behavioral features such as trade frequency and leverage were key predictors

---

##  How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open:

```bash
notebooks/analysis.ipynb
```

---

##  Outputs

Charts available in `/outputs` folder
