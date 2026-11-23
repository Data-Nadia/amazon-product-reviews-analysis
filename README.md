# 📦 Amazon Product Reviews: Customer & Product Analytics

## 📋 Project Overview
This project explores Amazon product reviews to understand customer satisfaction, evaluate brand and product performance, and identify potential areas for improvement.
Using Python, Pandas, and Matplotlib, I performed data extraction, transformation, cleaning, exploratory data analysis (EDA), and data visualization to turn raw customer review data into meaningful business insights.

Focus: Data Cleaning | ETL | Exploratory Data Analysis | Data Visualization | Business Insights

## 🎯 Business Objective

The main objective is to analyze customer feedback and answer key business questions:
- How satisfied are customers with the products?
- Which brands receive the highest and lowest average ratings?
- How are customer reviews distributed across product categories?
- Which products may require further investigation based on their ratings?
- Do verified and non verified purchases show differences in average ratings?

## 📂 Dataset

- Source: [Amazon Product Reviews Dataset — Kaggle](https://www.kaggle.com/datasets/promptcloud/amazon-product-reviews-dataset)

## 🛠️ Tool Purpose

**Python** for Data analysis and processing

**Pandas** for Data cleaning, transformation, aggregation, and EDA

**Matplotlib** for Data visualization

## ⚙️ Project Workflow

Data Extraction: Imported the raw Amazon reviews dataset using Pandas and inspected its structure, columns, data types, and missing values.

**1. Data Cleaning & ETL:</mark> (saved as Notebook: 01_data_cleaning.ipynb, Cleaned Dataset: amazon_reviews_clean.csv)**  


  Handled missing values

  Removed fully empty columns

  Converting date fields into appropriate datetime formats

  Cleaning and converting helpful review counts into numeric values

  Checked for duplicates

 
**2. Exploratory Data Analysis (EDA):  (savea as Notebook: 02_eda.ipynb)**


 Analyzed rating distribution

 Brand and product performance 

 Category distribution

 Review content and length

   
**3. Data Visualization:(saved visualizations as PNG files)**


 Used Matplotlib to create three visualizations highlighting customer rating

# 📊 Sample Visuals
<img width="703" height="559" alt="Screenshot 2026-11-23 200855" src="https://github.com/user-attachments/assets/de5fa30b-d105-44d4-b4e9-ab23889fc25a" />
<img width="703" height="559" alt="Screenshot 2026-11-23 201230" src="https://github.com/user-attachments/assets/aec678b3-0e68-4119-a668-c821abcdab1d" />

## 💡 Key Findings & Business Insights
- Customer Satisfaction: The average review rating was 4.18 out of 5. Approximately 78% of reviews received 4 or 5 stars.
- Negative Feedback: 16% of reviews received 1 or 2 stars, highlighting potential areas for improvement.
- Brand Performance: Schmidt's Deodorant had the highest review volume (20 reviews) and the lowest average brand rating (3.60).
- Positive Brand Feedback: SheaMoisture received an average rating of 4.67 across 15 reviews.
- Product Performance: Products B071YYMZ19 and B07WDL82Z4 each had 10 reviews, with average ratings of 3.50 and 3.70 respectively.
- Purchase Verification: Verified purchases had an average rating of 4.26, compared with 3.25 for non-verified purchases. The non verified group contained only four reviews, so this comparison should be interpreted cautiously.

## 📈 Business Recommendations
Based on the exploratory findings:
1. Investigate negative customer reviews to identify recurring product issues.
2. Prioritize products with relatively high review volumes and lower average ratings for further investigation.
3. Monitor brand performance using both review volume and average rating.



