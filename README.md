# Meta Ads Campaign Performance Analysis

## Project Overview
An exploratory data analysis project focused on evaluating Meta Ads campaign performance, identifying cost-efficient campaigns, and generating data-driven marketing recommendations.

The project uses a Meta Ads dataset containing **237 rows and 644 columns before cleaning**, as observed in the local notebook. The dataset includes campaign details, advertising metrics, audience targeting information, and time-based performance fields.

## Objectives
- Understand advertising campaign performance.
- Identify missing values, duplicate records, and data-quality issues.
- Analyze clicks, impressions, spend, and payments.
- Compare campaign performance using marketing KPIs.
- Identify opportunities for campaign optimization.

## Tools & Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Microsoft Excel
- Jupyter Notebook
- Git and GitHub

## Data Cleaning & Preparation
- Inspected dataset dimensions, data types, duplicate records, and missing values.
- Identified columns with 100% missing values and removed completely empty columns.
- Investigated high-missing-value fields.
- Prepared data for exploratory analysis and visualization.
- Used column-name checks to resolve errors caused by inconsistent column names.

## Key Analysis Areas
- Campaign-level advertising spend.
- CTR (Click-Through Rate) by target age range.
- CPC (Cost Per Click) and payment performance.
- Target-region distribution.
- Time-based campaign trends.
- Audience and campaign performance comparisons.

## KPI Formulas

**CTR (%)**
Clicks / Impressions × 100

**CPC**
Advertising Spend / Clicks

**Cost per Payment**
Advertising Spend / Number of Payments

**Conversion Rate**
Conversions / Clicks × 100

*Note: Conversion Rate must use a consistent definition throughout the analysis.*

## Current Notebook Results
- Initial dataset dimensions: 237 rows × 644 columns.
- Duplicate rows identified in the initial inspection: 0.
- Missing values identified initially: 93,463.
- Columns with 100% missing values identified: 41.
- After removing completely empty columns: 237 rows × 603 columns.
- Generated a bar chart comparing average CTR across target age ranges.
- Generated a pie chart showing the distribution of target regions.

## Business Value
This project demonstrates practical experience in data quality assessment, exploratory data analysis, marketing KPI calculations, visualization, and interpreting advertising performance to support data-driven decisions.

## Repository Contents
- `META_ads_dataset_data_cleaning_insight_eda.ipynb` — analysis notebook.
- `meta_ads_with_json_dataset_sample.xlsx` — dataset sample.
- `final_clean_ads.csv` — cleaned dataset, if this is the final exported output.
- `Meta_ads_Insights_Reporting...` — reporting file, if included in the repository.



**Project Type:** Marketing Analytics & Exploratory Data Analysis