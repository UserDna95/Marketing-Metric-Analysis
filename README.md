# 📈 Marketing Campaign Exploratory Data Analysis 
This project analyzes marketing campaign performance using data from Kaggle. It includes data cleaning, descriptive statistics, correlation analysis, and hypothesis testing.

## 🔍 Objectives
•	 Understand campaign effectiveness

•	 Identify key metrics driving conversions and revenue

•	 Test statistical significance between campaign types

## 🧪 Methods Used 
T-test, ANOVA

## 📁 Tools
Excel for cleaning and stats

## 🔢 Steps
1)	🧹 Data Cleaning
   
      •	Remove duplicates, handle missing values
      
      •	Standardize column names (e.g., Clicks, Conversions, Revenue) by campaign names
      
      •	Format dates, categories, and numeric fields via campaign names in Pivot Table
      
      •  Add calculated columns for Click-through rate (Clicks/Impressions), Conversion rate for leads (Leads/Clicks), Conversion rate for orders (Orders/Clicks), Cost per click (Cost/Clicks), Return on Ad Spend (Revenue/Spent)

2)	🧪 Hypothesis Testing
   
      •	ANOVA: Test Click-through rate (Clicks/Impressions), Conversion rate for leads (Leads/Clicks), Conversion rate for orders (Orders/Clicks), Cost per click (Cost/Clicks), Return on Ad Spend (Revenue/Spent) across four Facebook campaigns for the top performer per platform
      
      •	ANOVA: Test the same as above across three Instagram campaigns for the top performer per platform
      
      •	T-test: Test the same as above across two Google campaigns for the top performer per platform
      
      •	ANOVA: Test Return on Ad Spend (Revenue/Spent) across top campaigns per platform
      
      •	ANOVA: Test Conversion rate for orders (Orders/Clicks) across top campaigns per platform
      
      •	ANOVA: Test Cost per click (Cost/Clicks) across top campaigns per platform
      
      •	ANOVA: Test Click-through rate (Clicks/Impressions) across top campaigns per platform

3)	📊 Build Executive Summary in Dashboard style
   
      •	Table to summarize top and lowest performers
      
      •	Ranking table based on averages and weighted scores 
      
      •	Budget relocation suggestions
      
      •	Next steps table for suggestions on current findings and future testing 

## 📌 Dataset

Source: Digital Marketing Metrics & KPIs to Measure (SQL)

Source: Statistics Foundations | Coursera By META was incredibly useful in creating this mini-project

