# 💳 Credit Card Spending Analysis & Visualization

> Identified high-risk fraud patterns and optimized customer targeting strategy through transaction-level behavioral analysis of **1.29M+ credit card records**.

---

## 📌 Project Overview

Credit card companies collect massive transaction data but often fail to fully utilize it for customer targeting, marketing optimization, and fraud prevention.

This project transforms raw transaction data into **actionable business insights** — demonstrating how visualization-driven EDA can simultaneously drive growth strategy and risk management.

---

## 🎯 Problem Statement

> *"How can transaction data be transformed into actionable insights for both growth and risk control?"*

---

## 🗂 Dataset

- **Size**: ~1.29 million transactions, 24 features
- **Key fields**: transaction amount, category, timestamp, customer age, occupation, region, fraud label

---

## ⚙️ Methodology

### 1. Data Processing
- Removed unnecessary columns and handled missing values
- Grouped customers by age, occupation, and region
- Engineered time-based features (hour, weekday, month)

### 2. Analysis & Visualization
- Customer behavior analysis across occupation, age & gender, time, and region
- Fraud pattern analysis by transaction amount, category, time, and location

### Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)

---

## 🔍 Key Findings

**Occupation is NOT a strong predictor**
Spending patterns across professions were highly similar — job-based segmentation is ineffective for targeting.

**Spending behavior depends on frequency & amount**
High-value customers show high frequency AND high transaction size — more predictive than any demographic variable.

**Strong time-based patterns**
December spike with a Jan–Feb drop reflects clear seasonality. Monday and weekends are peak spending days — ideal for campaign timing.

**Age-based differences are meaningful**

| Age Group | Profile |
|-----------|---------|
| 30s–50s | Balanced, high-value — core target segment |
| 60+ | High spend per transaction |
| 20s | Low volume and low value |

**Regional differences are limited**
Most categories show similar distribution across regions. Exception: certain regions show elevated transportation spending — regional targeting should be selective, not broad.

---

## 🚨 Fraud Detection Insights

**Fraud transactions are significantly larger**

| Type | Avg Transaction Amount |
|------|----------------------|
| Normal | ~$67 |
| Fraud | ~$531 |

➡ High-value anomaly detection is critical.

**Online transactions are highest risk**
~44.5% of all fraud occurs in online shopping — strong monitoring needed at the channel level.

**High-risk time windows**
Fraud peaks between 10 PM – 3 AM and increases toward weekends — time-based detection rules can significantly reduce exposure.

---

## 💡 Business Impact

**Marketing Strategy**
Focus on high-frequency, high-value users with loyalty programs, personalized rewards, and subscription-based benefits.

**Campaign Timing**
Launch campaigns on Mondays and weekends, with seasonal push in December.

**Customer Targeting**
Core segment: 30–50 age group with high transaction frequency.

**Fraud Prevention**
Monitor high-value transactions, night-time activity (10 PM – 3 AM), and online purchase channels.

---

## 🏆 Key Takeaways

- Behavioral data outperforms demographic data for targeting
- Time-based patterns are highly actionable for both marketing and fraud prevention
- A single dataset can simultaneously drive **growth strategy + risk management**
- Visualization is the most direct path from raw data to business decision

---

## 🔮 Future Improvements

- Machine learning-based fraud detection model
- Customer Lifetime Value (CLV) modeling
- Real-time anomaly detection system
- Dashboard integration (Tableau / Power BI)

---

## 📁 Repository Structure

```
Spending-Pattern-Visualization/
│
├── data/
├── notebooks/
│   └── spending_pattern_analysis.ipynb
├── visualization/
│   ├── monthly_trend.png
│   ├── weekday_heatmap.png
│   ├── age_segment.png
│   └── fraud_amount_dist.png
└── README.md
```

---

## 👤 5 People Team Project — Data Analytics Bootcamp, 2025
