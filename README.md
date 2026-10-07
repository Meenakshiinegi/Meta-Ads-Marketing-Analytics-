# Meta Ads Campaign Performance & Marketing Analytics

An end-to-end marketing analytics project focused on cleaning, analyzing, and evaluating Meta Ads campaign performance using **Excel and Python**.

The project demonstrates how raw advertising data can be transformed into meaningful KPIs, performance benchmarks, and actionable campaign optimization insights.

---

## 📌 Project Overview

This project analyzes Meta Ads campaign data at multiple levels:

- Platform
- Campaign
- Ad Set
- Individual Ad
- Date / Time

The raw dataset contains campaign performance metrics along with semi-structured targeting information.

The main objective was to:

1. Clean and structure the raw advertising data
2. Handle semi-structured JSON targeting fields
3. Create meaningful marketing KPIs
4. Analyze campaign and ad performance
5. Identify high-performing and underperforming segments
6. Generate data-driven optimization recommendations

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data cleaning, transformation & Pivot analysis |
| **Python** | Exploratory Data Analysis |
| **Pandas** | Data manipulation & analysis |
| **NumPy** | Numerical calculations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualization |
| **Git & GitHub** | Version control & project management |

---

# 🧹 Phase 1 — Data Cleaning & Preparation

The dataset required extensive preprocessing before analysis.

### JSON Data Handling

- Extracted relevant targeting attributes from nested JSON data
- Processed fields such as:
  - Age range
  - Interests
  - Behaviors
  - Geographic targeting
- Removed unnecessary raw JSON columns after extracting useful information

### Data Standardization

- Standardized date and numeric fields
- Cleaned missing and inconsistent values
- Verified Ad ID uniqueness
- Converted columns into appropriate analytical data types

### Column Optimization

Removed unnecessary or highly incomplete fields, including:

- Columns with excessive missing values
- Redundant system-generated metrics
- Hourly breakdown columns
- Derivable weekday fields
- Other unnecessary calculated fields

### Feature Engineering

Created analytical metrics such as:

- CTR
- CPC
- Conversion Rate
- CPA
- CPLPV
- Engagement Rate
- ROI
- Monthly performance indicators

---

# 📊 Phase 2 — Excel Pivot Analysis

Pivot-based analysis was performed to evaluate performance across different dimensions.

### Platform Analysis

Analyzed:

- Total Spend
- Total Conversions
- Average CPC
- Conversion Rate

### Campaign Analysis

Compared campaigns using:

- Spend
- Payments
- CPC
- CPLPV
- CTR
- ROI

### Daily Performance

Analyzed:

- Daily Spend
- Payments
- CPC
- Conversion trends

---

# 🐍 Phase 3 — Python Exploratory Data Analysis

Python was used to validate and explore the cleaned dataset.

### Analysis Performed

- KPI recalculation
- Missing-value analysis
- Data-quality checks
- Distribution analysis
- Platform comparison
- Campaign benchmarking
- Correlation analysis
- Outlier detection
- Performance comparison

### Python Libraries

```text
Pandas
NumPy
Matplotlib
Seaborn
