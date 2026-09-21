# Customer Shopping Behavior Analysis

## 📌 Project Overview

An end-to-end **customer shopping behavior analysis** project using transactional data from **3,900 purchases**. The project analyzes customer demographics, purchasing patterns, product preferences, discounts, subscriptions, and customer segments to generate actionable business insights.

## 🛠️ Tools & Technologies

* **Python** — Data cleaning, EDA & feature engineering
* **Pandas** — Data manipulation and analysis
* **PostgreSQL** — Database integration & SQL analysis
* **Power BI** — Interactive dashboard & data visualization

## 📊 Dataset

* **3,900 rows**
* **18 columns**
* Customer demographics
* Purchase details
* Shopping behavior
* Subscription status
* Discounts and promotions
* Ratings and shipping information

The dataset contained **37 missing values in the Review Rating column**.

## 🔄 Project Workflow

1. Loaded and explored the dataset using Python and Pandas.
2. Cleaned missing values and standardized column names.
3. Created new features such as `age_group` and `purchase_frequency_days`.
4. Removed redundant data and prepared the dataset for analysis.
5. Loaded the cleaned data into **PostgreSQL**.
6. Performed SQL-based business analysis.
7. Built an interactive **Power BI dashboard** to visualize key findings.

## 🔍 Key Business Questions

The analysis explored:

* Revenue by gender
* High-spending customers using discounts
* Top-rated products
* Standard vs. Express shipping spending
* Subscribers vs. non-subscribers
* Discount-dependent products
* New, Returning, and Loyal customer segments
* Top products within each category
* Relationship between repeat purchases and subscriptions
* Revenue contribution by age group

## 📈 Dashboard

An interactive **Power BI dashboard** was developed to present the analyzed customer and sales insights visually.

## 💡 Business Recommendations

* Increase subscription adoption through exclusive benefits.
* Develop loyalty programs for repeat customers.
* Review discount strategies to balance sales and margins.
* Promote top-rated and best-selling products.
* Target high-revenue customer age groups and relevant shipping segments.

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── data_cleaning_analysis.py
│
├── sql/
│   └── business_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix

```


