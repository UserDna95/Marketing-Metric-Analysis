# 📊 Marketing Campaign Performance Analysis 

## End-to-end marketing analytics workflow combining Excel, Python, and statistical inference to support campaign investment decisions.

### 🔍 Project Overview
This project evaluates digital marketing campaign performance and determines whether observed differences in ROAS are statistically significant and decision-relevant.
It demonstrates a production-style analytics pipeline: data preparation → statistical validation → executive reporting.

### 🧰 Tools & Technologies

•	Excel & Power Query — data ingestion, validation, metric engineering

•	Python (Jupyter) — statistical testing & effect size estimation

•	pandas, scipy, statsmodels — ANOVA, post-hoc analysis

•	Excel Dashboards — executive-ready visualization

### 📈 Business Questions Answered

•	Do campaign ROAS differences represent real performance gaps or random variation?

•	Which campaigns statistically outperform others?

•	How large is the impact of campaign selection on revenue efficiency?

•	Which campaigns should be scaled, optimized, or deprioritized?

### 🧪 Analytical Workflow

Stage 1 — Data Preparation & Exploration (Excel)

•	Ingested raw marketing data (unchanged source)

•	Automated data validation and normalization via Power Query

•	Engineered KPIs: CTR, Conversion Rate, CPC, ROAS

•	Exploratory analysis and descriptive dashboarding

Stage 2 — Statistical Analysis (Python / Jupyter)

•	Imported analysis-ready dataset from Excel

•	Assumption testing (normality, variance equality)

•	Applied Welch ANOVA due to heteroskedasticity

•	Calculated effect size (η²) to quantify business impact

•	Conducted Tukey HSD to identify statistically distinct campaigns

•	Exported validated results back to Excel

Stage 3 — Decision Dashboard (Excel)

•	Consumed Python outputs via Power Query (no recalculation)

•	Ranked campaigns by statistically validated performance

•	Grouped campaigns into performance tiers:

   o	Scale
   
   o	Maintain & optimize
   
   o	Monitor
   
   o	Deprioritize

<img width="1019" height="566" alt="2026-01-01" src="https://github.com/user-attachments/assets/f87ddf45-4df9-40c4-b312-c5ce44c35fb8" />

### 📌 Dataset

Source: Digital Marketing Metrics & KPIs to Measure (SQL)

Source: Statistics Foundations | Coursera By META was incredibly useful in creating this mini-project

