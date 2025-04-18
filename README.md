# 📊 Amazon Review Insights — Tableau Data Storytelling
This project presents five interactive Tableau dashboards built for **Data Storytelling**. Using 2021 Electronics Amazon review and metadatasets, the dashboards explore customer behavior, sentiment trends, review anomalies, and product comparisons — all tailored to uncover meaningful business insights in a visual and engaging way.

## 🎯 Objective

The goal of this project is to apply data storytelling techniques to Amazon review data using Tableau. The dashboards are designed to be self-explanatory, interactive, and visually compelling — answering critical business questions **without the need for external reporting**.

---
## 🧹 Data Preparation

The dataset was prepared using Python by combining and preprocessing and merging Amazon review and metadata focused on the **Electronics** category for the year **2021**. The following key steps were performed:

- Inspected raw JSONL files to understand the structure and key fields using sample reads.
- Convert JSON to CSV file.
- Calculated sentiment polarity for each review using TextBlob and labeled them as **Positive**, **Negative**, or **Neutral**.
- Extracted high-frequency keywords from combined review text and product titles for word cloud generation.
- Cleaned and exported the final dataset as **CSV files**, optimized for Tableau visualizations.

These steps ensured the dashboards were built on clean, meaningful, and analysis-ready data.

All data preprocessing notebooks are available in the `data-preparation/` folder.

---

## 📊 Dashboards Overview

### 1. **Customer Review WordCloud**
- **Visuals**: Word cloud
- **Filters**: Words, Frequency of words
- **Insight**: What were most common words in customers reviews?

### 2. **Sentiment Trends Over Time**
- **Visuals**: Time-series chart with trend lines
- **Filters**: Date, rating, SentimentLabels
- **Insight**: Do seasonal patterns influence sentiments?

### 3. **Product Comparison**
  - **Visuals**: Ghant charts comparing high- vs. low-rated products
- **Metrics**: Count of sentiment, review volume
- **Insight**: Which products consistently receive high ratings?

### 4. **Fraud Detection & Anomaly Analysis**
- **Visuals**: Top reviewers, unverified high ratings, low helpfulness votes, spikes over time
- **Filters**: Verified purchases, star ratings
- **Insight**: Are there signs of fake reviews or review manipulation?

### 5. **Purchase Behavior Patterns**
- **Visuals**: Heatmaps and breakdowns by sentiment vs. verified purchases
- **Metrics**: Review counts, demographics, star distribution
- **Insight**: Do verified purchases lead to more trustworthy reviews?

---

## 📷 Dashboard Previews

All dashboard screenshots are available in the `/DashboardImages/` folder.

---

## 💡 Key Insights Summary

- Products with consistent 5-star ratings often have verified purchases and positive keywords like *“value”*, *“quality”*, and *“fast delivery.”*
- Unverified reviews with high ratings often show up in accounts with repeated activity — a sign of possible manipulation.
- Review spikes during major sales seasons (like November) indicate strong seasonal trends.
- Negative sentiment clusters around terms like *“broken,” “fake,”* and *“not as described.”*
- Verified purchases tend to have more balanced ratings and helpful votes.

---

## 🚀 Technologies Used

- **Tableau Desktop**
- **Python / Pandas** (for initial data prep)
- **Amazon Review Datasets** (including Amazon Meta) Link: https://cseweb.ucsd.edu/~jmcauley/datasets/amazon/links.html?utm_source=chatgpt.com 
---

## 📌 Submission

- ✔️ Tableau `.twbx` file: stored in `dashboards/`
- ✔️ All screenshots: stored in `DashboardImages/`
- ✔️ README with project overview and insights
- ✔️ GitHub Repo: [Tableau-Storytelling-Amazon](https://github.com/AimenFatimaa/Tableau-Storytelling-Amazon)

---

> *Let data do the talking.* 📈
