# Meta Ads Campaign Performance & Marketing Analytics

An end-to-end marketing analytics project focused on cleaning, analyzing, and evaluating Meta Ads campaign performance using **Microsoft Excel and Python**.

The project demonstrates how raw advertising data can be transformed into meaningful KPIs, performance benchmarks, exploratory analysis, and actionable marketing insights.

---

## 📌 Project Overview

This project analyzes Meta Ads campaign data at multiple levels:

- Platform
- Campaign
- Ad Set
- Individual Ad
- Date / Time

The dataset contains campaign performance metrics along with semi-structured targeting information.

The main objectives of this project were to:

1. Clean and structure raw advertising data
2. Handle semi-structured JSON targeting fields
3. Standardize and validate the dataset
4. Create meaningful marketing KPIs
5. Perform Excel-based Pivot analysis
6. Perform Exploratory Data Analysis using Python
7. Compare campaign, platform, ad set, and ad performance
8. Identify high-performing and underperforming segments
9. Generate data-driven optimization recommendations

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

The dataset required preprocessing before performing analytical operations.

### JSON Data Handling

The raw dataset contained semi-structured targeting information in JSON format.

Relevant attributes were extracted and structured for analysis, including:

- Age range
- Interests
- Behaviors
- Geographic targeting

Unnecessary raw JSON columns were removed after extracting the required information.

### Data Standardization

The dataset was standardized by:

- Converting dates into appropriate formats
- Converting numerical fields into suitable data types
- Cleaning missing and inconsistent values
- Checking Ad ID uniqueness
- Standardizing text-based fields
- Preparing the dataset for Python analysis

### Column Optimization

Unnecessary or highly incomplete fields were removed to improve analytical efficiency.

This included:

- Columns with excessive missing values
- Redundant system-generated metrics
- Hourly breakdown columns
- Derivable weekday fields
- Unnecessary calculated fields

### Feature Engineering

Additional analytical metrics were created, including:

- CTR
- CPC
- Conversion Rate
- CPA
- CPLPV
- Engagement Rate
- ROI
- Monthly performance indicators
- Date-based analytical fields

---

# 📊 Phase 2 — Excel Pivot Analysis

Microsoft Excel was used for structured analysis and Pivot-based reporting.

### Platform-Level Analysis

Performance was compared across advertising platforms using:

- Total Spend
- Total Clicks
- Total Conversions / Payments
- Average CPC
- Conversion Rate
- Overall performance

### Campaign-Level Analysis

Campaigns were evaluated using:

- Total Spend
- Payments
- CPC
- CPLPV
- CTR
- Conversion Rate
- ROI

### Daily Performance Analysis

Daily trends were analyzed using:

- Daily Spend
- Daily Clicks
- Daily Payments
- Daily CPC
- Conversion trends

Pivot Tables were used to summarize and compare performance across different dimensions.

---

# 🐍 Phase 3 — Python Exploratory Data Analysis

Python was used to validate the cleaned dataset and perform deeper exploratory analysis.

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
- Cost-efficiency analysis

### Python Libraries

```text
Pandas
NumPy
Matplotlib
Seaborn
