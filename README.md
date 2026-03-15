# 1962-2022 KO Stock Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Files Provided](#files-provided)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis and Data Analysis](#exploratory-data-analysis-and-data-analysis)
- [Analysis Finding](#analysis-finding)
- [Insight](#insight)
- [Visualization](#visualization)
- [Complete Analysis](#complete-analysis)
- [Recommendation](#recommendation)
- [Author](#author)

## Project Overview
Analysis of Coca-Cola Inc. (KO) daily OHLCV data highlights a robust 60-year growth path that evolved from sparse trading volumes in the 1960s to elevated monthly averages (1962–2022), demonstrating exceptional resilience across diverse market cycles.
It narrows down the trends to show steady performance over decades. Power BI visuals make it clear with optimised Power BI area charts that track price and volume growth, clustered columns that break down monthly and quarterly patterns, and KPI cards that highlight win rates and returns.
Skills demonstrated include: Power BI dashboard design, DAX measure creation (AVERAGE, SUM, CALCULATE), cross-filtering interactivity, data transformation, financial visualisation, and critical thinking in matching aggregation trends, making it ideal for financial data analysis and business intelligence.


## Files Provided    

## Data Sources
Google Stock Dataset (1962–2022) by Kalilur Rahman on Kaggle (15,311 rows × 8 columns). [Download](https://www.kaggle.com/datasets/kalilurrahman/coca-cola-stock-live-and-updated)

## Tools Used
**Excel** 
- Initial data preview and exploration
- Quick validation of row and column distributions

**Power BI**
- Power BI Power Query (data cleaning and transformation)
- Power BI Desktop (analysis, area charts, clustered columns, KPI cards)

**Workflow**: Excel preview → Power Query cleaning & transformation → Power BI analysis, KPI cards, and charts.

## Data Cleaning and Preparation

### Data Quality Assessment

- Verified data types and standardized them for consistency.
- Dropped redundant columns to streamline the dataset.
- Checked for duplicates using Date as the unique identifier (no duplicates found).
- Inspected for missing values (none detected).
- Renamed key columns (e.g., Open → Open Price, High → High Price).
- Confirmed chronological date order date maintained.
  
## Exploratory Data Analysis and Data Analysis  

### DAX Measures
| Measure | Purpose |
|---------|---------|
| Average Close Price | Shows the trend analysis for closing price across all 60 years of trading days |
| Average Daily Volatility | Shows the daily trend behaviour of the stock |
| Close > Open % | Percentage of days stock closed higher than it opened |
| Total Trading Days | Total number of active trading days |

### Analytical Methods Applied
- **Time Series Analysis**: 60-year trends + seasonality
- **Volatility Analysis**: Daily range % of close price
- **Win Rate Analysis**: Close>Open percentage  
- **Aggregation Validation**: Checks the accuracy of measures and calculations
- **Interactive EDA**: Cross-filtering + drill-through


## Analysis Finding
### 5 Business Questions Answered
| Q | Question | Result |
|---| ---------|--------|
| **Q1** | **Which year saw the highest trading activity in GOOG shares, and what drove the volume spikes?** | 2005 saw the highest trading activity in GOOG shares (~108 billion), driven by the post-IPO rush. 2025 had the lowest (~4 billion) due to incomplete year data.|
| **Q2** | **Which year had the highest average daily trading volume for GOOG shares, and why?**  | 2005 dominated GOOG's average daily trading volume (429 million shares/day) due to post-IPO excitement, while 2024 had the lowest (20 million shares/day) amid stock maturity and splits. |
| **Q3** | **How do GOOG's average daily returns vary by month across 2004-2025?** | The monthly seasonality patterns of GOOG's 2004-2025 average daily returns show October as the strongest and February as the weakest. |
| **Q4** | **GOOG's closing price evolution from IPO (2004) to 2025, including performance during major stress periods like the 2008 crisis, 2020 COVID crash, and 2022 bear market?** | GOOG showed 82x growth from ~$2.50 (2004 IPO) to ~$204 (2025). Handled 2008 (-55%, quick bounce), 2020 COVID (-30%, sharp recovery), 2022 (-40%, steady climb back). |
| **Q5** | **How do GOOG's 20-day and 50-day moving averages reveal short-term trends and trading signals from 2020-2025?** | GOOG's 20-day and 50-day moving averages (MAs) reveal short-term trends through their direction and crossovers from 2020-2025. |


## Insight
### 1. Trading Volume Pattern
When Google launched its IPO, 2005 exploded with massive trading volume, the highest in both total shares traded and average daily volume. This is largely due to the rush to own shares. As the stock appreciated post-IPO, volumes declined due to institutionalised trading. 2025 had the lowest total volume (incomplete year), and 2024 had the lowest average daily volume.


### 2. Monthly Returns Pattern  
Looking at average returns by month, October consistently delivers the highest gains for GOOG investors. On the other hand, investors earned less or even lost money in the months of February, June, and August.


### 3. Stock Volatility Amid Crisis  
GOOG stock bounces back strongly from every crisis. Handled the 2008 panic with quick recovery, didn't have a major drawdown in the COVID hit, and steadily climbed out of the 2022 slowdown, showing the stock's proven ability to recover from shocks.


## Visualization  
Key insights from GOOG stock data analysis:  
<img src="https://raw.githubusercontent.com/Nwokora/2004-to-2025-Google-Stock-Analysis/main/GOOG%20Stock/GOOG%20Excel%20Preview.png" width="48%" height="300"/>



## Complete Analysis
[GOOG Analysis](<GOOG Stock Analysis.ipynb>)
(interactive charts + code)


## Recommendation
**BUY & HOLD GOOG**  
- Steady 20-year growth proves volatility handling ✅  
- Survived **every crash** (2008, COVID, 2022) ✅  
- Perfect for investors who want to save for future gain ✅

