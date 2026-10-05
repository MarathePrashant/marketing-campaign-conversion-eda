# 🎯 Marketing Campaign Conversion & Customer Propensity EDA

[![Python](https://img.shields.io/badge/Python-EDA%20%26%20Profiling-3776AB?style=flat-square\&logo=python)](#)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=flat-square)](#)
[![Pandas](https://img.shields.io/badge/Pandas-Feature_Engineering-150458?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)](#)

## 📌 Executive Summary & Business Problem

Direct marketing campaigns can experience declining returns and increased acquisition costs when customer targeting is not supported by behavioral and demographic analysis.

This exploratory data analysis evaluates customer demographics, household characteristics, income levels, previous campaign responses, purchasing behavior, and marketing channels to identify high-propensity customer segments and opportunities to improve campaign targeting.

## 🛠️ Data Pipeline & Technical Approach

* **Feature Engineering:** Created analytical features including `Household Size`, `Total Children`, `Customer Tenure (Days)`, and `Total Promotional Expenditure`.
* **Data Cleaning & Outlier Analysis:** Examined missing values, distributions, and potential outliers using statistical techniques including IQR-based analysis.
* **Customer Profiling:** Compared customer demographics, income, purchasing behavior, and previous campaign responses across different customer segments.
* **Channel Performance Analysis:** Evaluated customer response patterns across Web, Catalog, and Store marketing channels.
* **Exploratory Data Analysis:** Used Pandas, Matplotlib, and statistical visualizations to identify relationships between customer characteristics and campaign outcomes.

## 📂 Project Structure

```text id="v5k2px"
├── data/               # Campaign response and customer demographic datasets
├── notebooks/          # Jupyter Notebook containing end-to-end EDA
├── visuals/            # Campaign response charts and analytical visualizations
└── README.md           # Business case study, methodology, and insights
```

## 📊 Key Business Insights

* **Income-Based Propensity:** Higher-income customer segments demonstrated stronger engagement with premium promotional campaigns, indicating an opportunity for income-based audience segmentation.
* **Previous Campaign Response:** Customers with a history of accepting previous campaigns showed stronger subsequent engagement, making past response behavior a useful targeting signal.
* **Response Fatigue:** Repeated non-response patterns indicated lower campaign engagement, suggesting that continuously targeting inactive customers may reduce marketing efficiency.
* **Channel Performance:** Campaign response varied across Web, Catalog, and Store channels, highlighting the importance of matching marketing channels with customer characteristics and engagement behavior.

## 💡 Strategic Business Recommendations

* **Non-Responder Suppression:** Introduce engagement-based suppression rules for customers with repeated campaign non-responses to reduce unnecessary marketing spend.
* **Channel Optimization:** Allocate campaign budgets according to customer segment and historical channel performance rather than using a single channel strategy for the entire customer base.
* **High-Propensity Targeting:** Prioritize customers with strong historical campaign engagement for premium offers, early-access promotions, and personalized campaigns.
* **Customer Segmentation:** Combine income, household characteristics, purchasing behavior, tenure, and campaign history to develop more effective audience segments.

## 🚀 How to Explore This Project

1. **Review the EDA Notebook:** Open `/notebooks` to explore data cleaning, feature engineering, customer profiling, and exploratory analysis.
2. **Review the Visualizations:** Open `/visuals` to examine campaign response patterns, income distributions, customer segments, and channel-level analysis.
3. **Review the Dataset:** Explore `/data` to understand the customer, demographic, purchasing, and campaign-response attributes used in the analysis.

## 👤 Author

**Prashant Marathe**

* **LinkedIn:** https://www.linkedin.com/in/prashantmarathe17
* **Portfolio:** https://prashant-marathe.framer.website/
* **Email:** [p04747391@gmail.com](mailto:p04747391@gmail.com)
* **Location:** Pune, Maharashtra, India
