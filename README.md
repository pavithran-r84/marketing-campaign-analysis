# Marketing Campaign Performance & Sales Analysis
# Project Overview

This project focuses on analyzing marketing campaign data to understand how different advertising channels influence product sales and overall marketing efficiency.

The objective was to transform raw marketing data into meaningful business insights using Microsoft Excel and Power BI, and present them through an interactive dashboard.

# Objectives

+ Convert raw marketing data into analysis-ready format
+ Analyze the relationship between marketing spend and sales
+ Identify high-performing advertising channel
+ Evaluate cost efficiency
+ Build a professional, business-focused dashboard
+ Generate actionable insights for decision-making

# Dataset Description

The dataset contains information related to:

+ Product Sold
+ Traditional, Digital, Partnership, and Trust Spend
+ Performance Channel
+ Support Channel
+ Total Spend
+ Cost Per Sale

Initially, the dataset was not suitable for direct analysis and required multiple preprocessing steps.

# Tools Used

+ Microsoft Excel – Data cleaning and initial analysis
+ Power BI – Data modeling, DAX calculations, and dashboard creation

# Data Preparation & Transformation

To prepare the dataset for analysis, the following steps were performed:

**1. Data Type Correction**

+ Converted Product_Sold to Whole Number
+ Converted spend columns to Decimal format
+ Converted category fields to Text

**2. Category Grouping**

Marketing methods were grouped into four categories:

+ Traditional (TV, Billboard)
+ Digital (Google Ads, Social Media)
+ Partnership (Affiliate Marketing)
+ Trust (Influencer Marketing)

This simplified the analysis and made it more business-relevant.

**3. Channel Classification**

Categories were further grouped into:

+ Performance Channel → Traditional, Digital
+ Support Channel → Partnership, Trust

This helped in comparing core and supporting marketing efforts.

**4. Sales Bucketing**

Product sold values were grouped into ranges:

+ 0–5000
+ 5000–7000
+ 7000–9000
+ 9000+

This made it easier to analyze trends across sales levels.

**5. Calculated Columns**

Using DAX and Excel formula, the following were created:

+ Product Sold Range
+ Bucket Order (for sorting)
+ Total Spend
+ Cost Per Sale

**6. Use of Averages**

Since bucket sizes were uneven, average values were used instead of totals to ensure fair comparison across segments.

# Dashboard Features

The Power BI dashboard includes:

+ Cards (Total Spend, Average Cost per Sale, Total Sales)
+ Spend Distribution by Category
+ Channel Performance Comparison
+ Cost Efficiency Analysis
+ Category Performance Summary

All visuals are designed to support business decision-making.

# Key Insights

+ Traditional and Digital channels generate the highest sales
+ Higher sales volumes require higher marketing investment
+ Cost per sale remains stable at higher sales levels
+ Mid-sales segment (5000–9000) drives most revenue
+ Support channels need further optimization

# Business Recommendations

+ Increase focus on Traditional and Digital channels
+ Optimize Partnership and Trust campaigns
+ Focus on mid-sales segment for growth
+ Monitor cost efficiency regularly
+ Reallocate budget based on performance

# Learning Outcomes

Through this project, I learned:

+ Data preprocessing and transformation
+ Power BI data modeling
+ DAX calculations
+ Business-focused analysis
+ Dashboard storytelling

# Conclusion

This project demonstrates how raw marketing data can be converted into actionable business insights through structured analysis and visualization. It strengthened my understanding of marketing analytics and real-world data analysis practices.
